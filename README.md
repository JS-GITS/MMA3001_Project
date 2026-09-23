# MMA3001_Project | Automated Pork Packaging Quality Inspection

> A computer-vision and machine-learning system for automated pass/fail
> inspection of packaged pork rashers in a manufacturing environment.

## Overview

Automated quality inspection is an important component of modern food
manufacturing systems. Manual inspection can be time-consuming and may
produce inconsistent results, particularly when production volumes are high.

This project investigates the use of computer vision and machine learning to
automatically classify packaged pork rasher trays as **Pass** or **Fail** based
on visible packaging and product-placement defects.

The project is developed as part of MMA3001 – Numerical Methods and Machine
Learning.

## Engineering Problem

The objective is to develop and evaluate a computational inspection method
that could form part of an automated production-line quality-control system.

The system accepts an RGB image of a packaged pork tray and produces a binary
classification:

- **Pass** — packaging/product placement satisfies the selected inspection criteria
- **Fail** — one or more relevant defects are detected

The engineering challenge is not only to achieve high classification
performance, but also to investigate reliability, robustness, computational
cost and suitability for practical production-line inspection.

## Project Objectives

The project aims to:

- Develop a reproducible image-processing and machine-learning pipeline;
- Extract and analyse relevant visual features from packaging images;
- Establish a baseline classification method;
- Develop an improved machine-learning or deep-learning model;
- Evaluate performance using independent validation/test data;
- Investigate false-positive and false-negative inspection decisions;
- Analyse computational performance and model trade-offs;
- Assess limitations relevant to real-world manufacturing deployment.
