---
title: "Hybrid-Traj-Guard: Asynchronous AI Decision Architecture"
date: 2026-04-13 23:58:00 +0800
categories:
  - portfolio
tags:
  - Autonomous Driving
  - Reinforcement Learning
  - LLM
---

## Problem

In autonomous driving, pure LLM-based decision systems face latency bottlenecks that can impact real-time safety. The project aimed to design a collaborative architecture that preserves intelligence while meeting strict execution constraints.

## Data

- Autonomous driving trajectory and decision scenarios
- Simulation data for collision and path-planning evaluation
- Baseline systems from reproduced ICLR-style setup

## Approach

- Designed an asynchronous architecture with LLM as decision layer and CNN/RNN as execution layer
- Integrated PPO reinforcement learning and Barrier Function constraints into trajectory planning
- Added dual-output mode: trajectory prediction plus semantic intent explanation

## Outcome & Impact

- Reduced collision rates by approximately 40%-60% versus baseline methods
- Achieved average trajectory error (ADE) <= 0.2m
- Improved interpretability for complex decision processes through semantic intent outputs

## My Role

- Project Leader and Architecture Owner
- Designed the asynchronous decision/execution split between LLM and CNN/RNN modules
- Integrated PPO and barrier-function safety constraints into trajectory planning
- Led evaluation design and baseline comparison reporting

## Tech Stack

Python, PPO, CNN/RNN, trajectory planning, safety constraint optimization
