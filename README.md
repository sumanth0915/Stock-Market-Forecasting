# StockNeuro – Intelligent Stock Market Forecasting System

## Project Overview

**StockNeuro** is a deep learning-based stock market forecasting system designed to predict future stock prices using historical financial data. The project compares the performance of:

- Recurrent Neural Networks (RNN)
- Long Short-Term Memory Networks (LSTM)

The system provides:
- Real-time stock lookup
- Prediction visualization
- Interactive charts
- Model comparison dashboards
- BUY / SELL / HOLD confidence verdicts

The platform is implemented as a full-stack web application using:
- React.js frontend
- FastAPI backend
- PyTorch deep learning models

---

# Background of the Study

Stock market prediction is challenging because financial markets are:
- Dynamic
- Non-linear
- Volatile
- Influenced by global events and investor sentiment

Traditional methods like:
- ARIMA
- Moving Averages
- Linear Regression

struggle to capture long-term dependencies in stock prices.

Deep learning approaches such as:
- RNN
- LSTM

have shown significant improvements in handling sequential time-series financial data.

---

# Problem Statement

Traditional forecasting models fail to effectively learn complex sequential dependencies in stock market data.

This project aims to:
- Build an intelligent forecasting system
- Predict future stock prices
- Compare RNN and LSTM performance
- Eliminate data leakage
- Provide accurate financial insights

---

# Objectives

## Primary Objectives

- Collect historical stock data
- Implement RNN and LSTM models
- Train models using PyTorch with CUDA acceleration
- Compare model performance
- Visualize prediction accuracy
- Build a production-grade forecasting platform

## Evaluation Metrics

- RMSE
- MAE
- MAPE
- sMAPE
- MASE
- R² Score
- Tolerance Accuracy

---

# Scope of the Project

The project focuses on:
- Predicting future closing prices
- Comparing deep learning sequence models
- Visualizing forecasting results

The project does **not** include:
- Real-time trading automation
- Brokerage API integration
- Sentiment analysis
- Automated trading strategies

---

# Motivation

The project was motivated by:
- The intersection of AI and Finance
- Increasing retail investor participation
- Need for transparent forecasting systems
- Need for leakage-free evaluation pipelines
- Need for reproducible stock forecasting benchmarks

StockNeuro exposes:
- Metrics
- Prediction confidence
- Model comparisons
- Forecasting transparency

---

# Applications

## Portfolio Management
Helps investors analyze future price trends.

## Risk Management
Assists institutions in evaluating market risk.

## Algorithmic Trading Research
Provides baseline forecasting models.

## Academic Benchmarking
Supports reproducible deep learning experiments.

## Fintech Integration
Can be integrated into financial analytics platforms.

---

# Tech Stack

## Frontend
- React 18
- Vite
- Recharts
- Axios
- Tailwind CSS

## Backend
- Python 3.11
- FastAPI
- Uvicorn

## Machine Learning
- PyTorch
- NumPy
- Scikit-learn

## Deployment
- Render (Backend)
- Vercel (Frontend)

## Authentication
- JWT Authentication
- python-jose

---

# Dataset Information

## Data Source
Yahoo Finance API via RapidAPI

## Stocks Used
- AAPL
- GOOGL
- MSFT
- TSLA

## Dataset Features
- Open
- High
- Low
- Close
- Volume (OHLCV)

## Data Split
- 80% Training
- 20% Testing

---

# System Architecture

```text
Client Layer (React Frontend)
          ↓
FastAPI Backend
          ↓
Prediction Service
          ↓
RNN / LSTM Models
          ↓
Yahoo Finance API
