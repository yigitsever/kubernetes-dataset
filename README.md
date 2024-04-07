# Kubernetes Dataset

This repository hosts the flow files, generated from `.pcap` files using [this fork of the CICFlowMeter](https://github.com/GintsEngelen/CICFlowMeter) tool, as part of the paper [A Kubernetes dataset for misuse detection](https://www.itu.int/pub/S-JNL-VOL4.ISSUE2-2023-A26).
Please refer to the paper for the dataset creation steps and the details on the attack scenarios.

# Data Overview

| Scenario                  | Label |
|---------------------------|-------|
| Benign                    | 0     |
| CVE‑2020‑13379            | 1     |
| Node-RED Reconnaissance   | 2     |
| Node-RED RCE              | 3     |
| Node-RED Container Escape | 4     |
| CVE‑2021‑43798            | 5     |
| CVE‑2019‑20933            | 6     |
| CVE‑2021‑30465            | 7     |
| CVE‑2021‑25741            | 8     |
| CVE‑2022‑23648            | 9     |
| CVE‑2019‑5736             | 10    |

# Publications

If you use this dataset for academic research, please cite the paper "[A Kubernetes dataset for misuse detection](https://www.itu.int/pub/S-JNL-VOL4.ISSUE2-2023-A26)".

```bibtex
@article{severKubernetes2023,
    title = {A {Kubernetes} dataset for misuse detection},
    author = {Sever, Yigit and Dogan, Adnan Harun},
    volume = {4},
    url = {https://www.itu.int/pub/S-JNL-VOL4.ISSUE2-2023-A26},
    doi = {https://doi.org/10.52953/FPLR8631},
    number = {2},
    journal = {ITU Journal on Future and Evolving Technologies},
    month = jun,
    year = {2023},
    pages = {383--388},
}
```
