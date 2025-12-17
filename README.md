# 🏭 Electric-Vehicle Production System Optimization using Arena Simulation

## 📌 Project Overview
This project optimizes a production system using discrete-event simulation
(Arena). Starting from a **baseline model**, the system was improved by
optimizing **equipment quantity and workforce allocation**, resulting in a
final optimized model.

## 🔍 Problem Definition
The baseline production model showed:
- Bottlenecks in specific processes
- Long waiting times and limited throughput
- Inefficient allocation of equipment and labor

The objective was to **improve system performance** without redesigning the
entire process flow.

## ⚙️ Methodology
1. Built a **baseline Arena simulation model**
2. Identified bottleneck processes through performance metrics
3. Conducted scenario-based optimization by:
   - Increasing equipment quantity
   - Adjusting workforce allocation
4. Compared baseline vs optimized model performance

## 📊 Performance Metrics
- Throughput
- Average waiting time
- Work-in-Process (WIP)
- Resource utilization

## 📈 Key Results
- Optimized model achieved higher throughput
- Average waiting time significantly reduced
- Bottleneck process capacity improved by additional resources
- Marginal improvement observed beyond certain resource levels

## 🆚 Model Comparison
| Metric | Baseline Model | Optimized Model |
|------|----------------|-----------------|
| Throughput | ↓ | ↑ |
| Waiting Time | High | Reduced |
| Resource Utilization | Unbalanced | Improved |

## 🧠 Insights
- Adding resources selectively is more effective than uniform expansion
- Bottleneck-oriented optimization yields the highest performance gains
- Simulation enables risk-free evaluation of operational decisions

## 🗂 Files
- `arena_model/basic_model.doe` : Baseline model
- `arena_model/final_model.doe` : Optimized model
- `figures/` : Model screenshots and performance comparison
- `results/` : Simulation output data

> Arena software is required to run `.doe` files.
> Model files are provided for reference.
