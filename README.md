# MIND-Thesis-2026

# SISU’M: Thesis 2026, Arcada MIND Program

**Thesis title:** A Transparent Closed-Loop Orchestration System for 
Verifying Machine Learning–Predicted Cloud Cost Savings on AWS: 
Design, Implementation, and Evaluation

**Author:** Victor O. Ibe  
**Program:** Master in Machine Intelligence and Data Science (MIND)  
**Institution:** Arcada University of Applied Sciences, Finland  
**Year:** 2026  
**Supervisor:** Andrej Shcherbakov

## Overview

This repository contains all code, data pipelines, notebooks, 
and documentation for the SISU'M thesis project. The research 
investigates whether AWS Compute Optimizer's machine learning 
predictions can be empirically verified against realized cost 
savings measured through AWS Cost Explorer and Cost and Usage 
Reports, using a transparent closed-loop orchestration system 
as the experimental instrument.

## Repository structure

thesis-2026-MIND/
├── docs/                  # Thesis draft and research plan
├── src/                   # Orchestration system source code
│   ├── step_functions/    # AWS Step Functions state machine definitions
│   ├── lambda/            # AWS Lambda function handlers
│   └── actionlog/         # DynamoDB ActionLog schema and utilities
├── notebooks/             # Exploratory analysis and evaluation notebooks
├── data/                  # Sample data and schema definitions (no raw CUR data)
└── README.md


## Research questions

**RQ1:** How accurately does AWS Compute Optimizer predict EC2 cost 
savings compared to realized savings measured via Cost Explorer and 
Cost and Usage Reports 14 to 30 days after a change is applied?

**RQ2:** Can AWS Cost Anomaly Detection reliably identify cost 
regressions caused by a specific system-initiated action within 
48 hours, enabling safe automated rollback?


## Status

Work in progress - active development April–May 2026.
