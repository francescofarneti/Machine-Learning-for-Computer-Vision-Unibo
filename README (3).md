# Open-World Semantic Segmentation — Project README

## Overview

All the experiments, analyses, and results are contained in a **single Jupyter notebook**, designed to be easily reproducible and self-explanatory.

---

## Project Structure

- The entire project is implemented in **`main.ipynb`**.
- The notebook makes extensive use of **Markdown cells** to:
  - Explain design choices
  - Motivate architectural and methodological decisions
  - Discuss qualitative and quantitative results
  - *Note:* Plots were removed to keep the file size under 20 MB, but they can be reproduced by running the cells preceded by the markdown 'qualitative results'.
  - The model's weights are downloaded on Colab during the execution of the notebook; they are also provided in this OneDrive folder: https://liveunibo-my.sharepoint.com/:f:/g/personal/francesco_farneti7_studio_unibo_it/IgB4-RaUhZOJQKtxnzGESsjRAbkbv9VVTrKJEbwuU6jtFpc?e=kdSsHG
The notebook is meant to provide a **compact yet complete overview** of everything that was implemented, without requiring navigation across multiple files.

---

## Execution Environment

- The notebook is intended to be executed on **Google Colab**.
- No local setup is required.
- All necessary instructions and execution steps are **clearly indicated inside the notebook itself**.
- **Note:** Model training was performed exclusively on Kaggle. Training scripts are **not meant to be rerun inside Colab**.

---

## How to Run the Project

1. Open `main.ipynb` in **Google Colab**.
2. Follow the notebook sequentially or run the cells you are interested in (Note: the cells in which the quantitative results are generated have relatively long execution times, because all the models under analysis are run on the test set, and the calculation of AUPR takes on average 6–7 minutes per model.
)
3. No additional setup is required (no need to run external scripts)
4. The notebook allows to:
   - Reproduce **quantitative results**
   - Visualize **qualitative outputs**
   - Experiment with different parts of the pipeline independently


