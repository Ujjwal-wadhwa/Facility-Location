# Facility Location Problem

## Overview

This repository tackles the Facility Location Problem, a critical challenge in logistics and operations research. The problem involves determining the optimal number and locations of warehouses to efficiently supply a group of supermarkets. We use a mathematical optimization approach, specifically Mixed-Integer Programming (MIP), to find the best solution.

## Getting Started

Before diving into the problem, you should have a few prerequisites:

- **Python Knowledge:** Familiarity with Python programming.
- **Gurobi License:** Access to the Gurobi Optimizer, which is used to find the optimal solutions.

## Problem Description

Imagine a scenario where a large retail chain plans to open new supermarkets in an area. The supermarket locations are decided, but the company must determine where to build warehouses for efficient product distribution.

Several potential warehouse locations are under consideration. However, opening warehouses has associated costs, while not having enough can lead to higher delivery expenses.

Our goal is to strike the right balance between minimizing delivery costs and managing warehouse construction expenses.

## Solution Approach

We approach this problem using Mixed-Integer Programming (MIP). This approach allows us to formulate the problem mathematically and find the best solution through optimization.

## Model Formulation

### Key Components

- **Sets and Indices:** Representing supermarket and warehouse locations.
- **Parameters:** Including construction costs, distances, and shipping costs.
- **Decision Variables:** Indicating which warehouses to build and how much supply each supermarket receives.

### Objective

Our objective is to minimize total costs, which encompass construction and shipping expenses.

### Constraints

We ensure that customer demand is met, and shipping only occurs from built facilities.

## Repository

You can download this repository, by [clicking here]([repository_link](https://github.com/Ujjwal-wadhwa/Facility-Location/archive/refs/heads/main.zip)https://github.com/Ujjwal-wadhwa/Facility-Location/archive/refs/heads/main.zip).

