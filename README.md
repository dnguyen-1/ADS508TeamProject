# Ecogrid AI - Real-Time Grid Monitoring

## Authors
Authors: Duy Nguyen, Jordan Torres, Kirsten -Drennen

## Overview
Rising energy costs and workplace inefficiencies are driving the need for smarter solutions. Our AI-powered systems analyze real-time energy grid data, smart meters, and patterns to automate energy-saving decisions. By detecting waste and burnout risk, EcoGrid AI recommends smart shutdowns and efficiency boosts. Helping customers cut costs, lower carbon footprints, and enhance wellbeing.

## Technologies
* AWS Sagemaker (Python)
* AWS Athena
* AWS S3
* AWS DeepAR (Build-In Time Series Forecasting)


## Installation
Clone repository https://github.com/dnguyen-1/ADS508TeamProject.git (AWS Sagemaker recommended)

Navigate to [installation requirement](installation/Installation%20%26%20Set-Up.ipynb) to ensure your environment is set up to execute the model in Sagemaker AI

## Abstract

Rising energy costs and workplace inefficiencies are driving the need for smarter energy solutions. EcoGrid AI is an AI-powered platform that analyzes real-time energy grid data, smart meters, and patterns to automate energy-saving decisions. By detecting waste and burnout risk, EcoGrid AI recommends smart shutdowns and efficiency boosts, aiming to reduce costs, lower carbon footprints, and enhance wellbeing.

## Problem statement and Solution

Both businesses and individual consumers struggle with energy inefficiency. Unnecessary power consumption, poor scheduling, and lack of real-time information lead to higher costs and an increased carbon footprint. Consumers often leave appliances running longer than needed, while businesses fail to optimize resources and equipment usage.

Our AI-powered solution analyzes smart meter data, grid trends, and workplace activity to automate energy-saving decisions and optimize work schedules. By detecting wasteful energy consumption and patterns linked to inefficiency, our system provides smart recommendations that help both customers and businesses reduce energy consumption while improving sustainability.

## Data Sources

Data sourced from the U.S. Energy Information Administration, extracted by an application programming interface (API), and stored on AWS service S3 Bucket to be processed in AWS Sagemaker. Daily usage of megawatt hours were ingested for the period of 1/1/2024 to 12/31/2024 for the following 
*	Electricity Overview (demand, forecast demand, generation, and total interchange)
*	Electricity demand by region
*	Electricity generation by energy source
*	Electricity interchange with neighboring countries

## Presentation and Notebook



