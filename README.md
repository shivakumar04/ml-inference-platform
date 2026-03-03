# Cloud-Native ML Inference Platform

## Problem Statement

## System Architecture

Client
  → FastAPI Service (Azure App Service)
     → Load Model (Azure Blob Storage)
     → PostgreSQL (Prediction Logs)
     → Drift Monitor (Evidently)
  → Monitoring Dashboard

## Data & Features

## Model & Metrics

## API Design

## Deployment Architecture

## Monitoring & Drift Detection

## Trade-offs & Design Decisions

- Why Logistic Regression (baseline)
- Why Azure App Service
- Why Blob Storage for model artifacts
- Why Evidently for drift
- Why no online retraining
