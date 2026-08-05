# Comprehensive Klinkenberg Effect & Gas Permeability Analysis

Advanced petrophysics and reservoir engineering analysis demonstrating gas slippage effects and equivalent liquid permeability estimation using Ordinary Least Squares (OLS) regression.

---

## Mathematical Foundation
Gas permeability ($k_g$) varies inversely with mean pore pressure ($P_m$) due to Knudsen slip flow along pore walls:

$$k_g = k_l \left( 1 + \frac{b}{P_m} \right)$$

- $k_l$: True equivalent liquid permeability (mD)
- $b$: Klinkenberg slippage factor (psi)
- $P_m$: Mean pore pressure ($\frac{P_{in} + P_{out}}{2}$)

---

## Key Results
![Klinkenberg Regression Analysis](figures/klinkenberg_regression.png)

- **Calculated Liquid Permeability ($k_l$):** `15.951 mD`
- **Slippage Factor ($b$):** `253.48 psi`
- **Coefficient of Determination ($R^2$):** `0.99892`

---

## Quickstart

1. **Clone Repository:**
   ```bash
   git clone [https://github.com/your-username/klinkenberg-permeability-analysis.git](https://github.com/your-username/klinkenberg-permeability-analysis.git)
   cd klinkenberg-permeability-analysis
