# Data-Driven Model Predictive Control for TMA Multi-Aircraft Routing Under Travel Time Uncertainty

The proposed scheduler is a closed-loop framework to provide conflict-free routing and scheduling solutions for Terminal Manoeuvring Area (TMA) multi-aircraft, with the aim to smooth the landing process and reduce the TMA congestion.
This repository is aiming to provide the simulation results and videos for the following paper.

For more details, please find from paper: "Data-Driven Model Predictive Control for TMA Multi-Aircraft Routing
Under Travel Time Uncertainty", presented at the Workshop on Artificial Intelligence for Air Transportation (AI4AT) @ AAAI 2026, and accepted as Conference Paper for the IEEE International Conference on Intelligent Transportation Systems (ITSC 2026).

## Repository structure

Folder "exp1_computationTest" gives the first experiment results in the paper, targeting on computational time and cost quality analysis.

Folder "exp2_with_without_rolling_test" provides the second experiment results in the paper, including both numerical results and video animations.

Folder "exp3_monte_carlo_test" provides the third experiment results in the paper, aiming to compare the robustness between Gurobi-based MPC and search-based MPC.

## Citation

If you find this helpful in your research, please cite:

```
@article{zhang2025data,
  title={A Data-Driven Model Predictive Control Framework for Multi-Aircraft TMA Routing Under Travel Time Uncertainty},
  author={Zhang, Yi and Long, Yushen and Huang, Liping and Zhang, Yicheng and Zhang, Sheng and Yin, Yifang},
  journal={arXiv preprint arXiv:2511.19452},
  year={2025}
}
```
