# Network Traffic Analyzer

A beginner-friendly Python project for analyzing network traffic data, summarizing activity by source IP address, and flagging unusual records for review.

## Project Overview

This project uses a synthetic network traffic dataset to demonstrate basic network traffic analysis and rule-based anomaly flagging.

## Features

- Analyze network traffic records using Pandas.
- Summarize packets, transferred bytes, and connection counts by source IP.
- Visualize traffic volume using Matplotlib.
- Flag records that exceed configurable packet or data-transfer thresholds.
- Display a summary chart of flagged and unflagged records.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Google Colab

## How It Works

1. Load a synthetic network traffic dataset.
2. Calculate traffic statistics.
3. Group records by source IP address.
4. Visualize traffic volume.
5. Flag records that exceed the configured thresholds for further review.

## Important Note

This project uses **synthetic data** and illustrative thresholds for educational purposes. Flagged records are not confirmed security incidents. This project is not a production intrusion detection system.

## Learning Objectives

- Data analysis with Python.
- Network traffic statistics.
- Data visualization.
- Basic rule-based anomaly detection.
- Introductory cybersecurity concepts.
