---
layout: publications
permalink: /publications/
title: Publications

years: [1967, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---

## Transportation Electrification and Infrastructure Planning

Many industrial sites rely on diesel-powered light-duty trucks to transport workers and small-scale facilities, which has resulted in a signification amount of green house emissions (GHGs). To address this, we
developed a two-stage robust charging infrastructure planning model for electrifying light-duty trucks at industrial sites. We developed a mixed-integer linear programming (MILP) that optimizes the
charging infrastructure, selected from multiple charger types and potential locations, and determines opportunity charging schedules for each truck based on the chosen infrastructure. Given the strict schedules and fixed routes at industrial sites, we introduced a scheduling-with-abandonment problem, where trucks forgo charging if their waiting times exceed a maximum threshold. We also further incorporated the impacts of overnight charging and range anxiety on drivers’ waiting and abandonment behaviors. To represent stochastic, heterogeneous parking durations of trucks, we constructed a decision-dependent robust uncertainty set in which parking time variability flexibly depends on drivers’ charging choices. We applied the model in a case study of an open-pit mining site, which plans charger installations in eight zones and schedules a fleet of around 200 trucks. Using an iterative scheduling and planning approach, for the whole year optimization horizon, the model achieves an optimality gap of less than 1% within a reasonable computation time under diverse uncertainty scenarios.

### Working paper: Decision-dependent robust charging infrastructure planning for light-duty truck electrification at industrial sites: scheduling and abandonment

- Presented at Yale School of Management

- Presented at 2025 INFORMS International in Singapore

---
## Data Center Planning and Operations

The rise of artificial intelligence is driving surging electricity demand from data centers, expected to double or triple by 2030. My work explores two questions: (1) how to power energy-intensive hyperscale data centers with 24/7 renewable energy, and (2) how to manage their loads in real time to support grid stability.

### Paper 1: Repurposing coal power plants into thermal energy storage for supporting zero-carbon data center[Paper](../assets/teaching/IAP_GenX_introduction_2025.pdf)[Code][Media]

### Working Paper 2: Distributionally robust games for data center demand response coordination based on CPU utilization and quality of service

- Presented at IEEE PES General Meeing 2025 in July, 2025

- Accepted to present at INFORMS Workshop on Data Science 2025 in October, 2025

---

## Machine Learning (ML) and Data-Driven Optimization for Large-scale Capacity Planning Problem

Capcity expansion problem is one of the most classical problems in energy system planning, which requires multiple data sources as inputs. I leveraged the ML techniques 

### Paper 1: The role of coal plant retrofitting strategies in developing India’s net-zero power system: a data-driven sub-national analysis [Paper](../assets/teaching/IAP_GenX_introduction_2025.pdf)[Code][Media]

### Paper 2: A dataset of the operating station heat rate for 806 Indian coal plant units using machine learning [Paper](../assets/teaching/IAP_GenX_introduction_2025.pdf)[Code][Media]

---

## Distributionally Robust Optimization (DRO) for Power Network Under Contingencies and Renewable Uncertainty

In light of a reliable and resilient power system under extreme weather and natural disasters, networked microgrids integrating local renewable resources have been adopted extensively to supply demands when the main utility experiences blackouts. However, the stochastic nature of renewables and unpredictable contingencies are difficult to address with the deterministic energy management framework. The paper proposes a comprehensive distributionally robust joint chance-constrained (DR-JCC) framework that incorporates microgrid island, power flow, distributed batteries and voltage control constraints. All chance constraints are solved jointly and each one is assigned to an optimized violation rate. To highlight, the JCC problem with the optimized violation rates has been recognized as NP-hard and challenging to solve. This paper proposes a novel evolutionary algorithm that successfully solves this problem and reduces the solution conservativeness (i.e., operation cost) by around 50% compared with the baseline Bonferroni Approximation. We construct three data-driven ambiguity sets to model uncertain solar forecast error distributions. The solution is thus robust for any distribution in sets with the shared moments and shape assumptions. The proposed method is validated by robustness tests based on these sets and firmly secures the solution robustness.

### Paper 1: Distributionally Robust Joint Chance-Constrained Optimization for Networked Microgrids Considering Contingencies and Renewable Uncertainty [Paper](../assets/teaching/IAP_GenX_introduction_2025.pdf)

