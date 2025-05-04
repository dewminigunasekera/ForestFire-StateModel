
# Forest Fire Modeling: A Statistical Mechanics Perspective

This repository contains a spatial-temporal analysis of forest fires in Portugal, with a critical evaluation of standard regression-based modeling. Using data visualization, coordinate-wise recurrence analysis, and insights from statistical mechanics, we argue that fire behavior exhibits state-transition characteristics that invalidate naive regression approaches.

## 🧠 Core Insight

- Fire area prediction is **not a regression problem**.
- Each coordinate experiences at most **one significant burn** → indicating **fuel exhaustion**.
- Without fuel state data, the system becomes **partially observable** and **non-ergodic**.
- This approach bridges **environmental modeling, spatial statistics**, and **stochastic state theory**.

## 📁 Contents

- `Portugal_FF.ipynb`: Jupyter notebook containing full analysis.
- `Forest_Fire_Theory_Insight.pdf`: Theoretical write-up.
- `chart_spatial_pattern.png`: Visualization of fire coordinates by month.
- `data/forestfires.csv`: Original dataset (UCI Forest Fire Dataset).

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ForestFire_StochasticInsight.git
   cd ForestFire_StochasticInsight
   ```

2. Install required libraries (use virtualenv if needed):
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Portugal_FF.ipynb
   ```

## 📜 License

This work is shared under the MIT License.  
For academic or research reuse, please cite the PDF write-up.

## 🤝 Contact

For collaborations or inquiries, reach out via GitHub or connect on LinkedIn.

