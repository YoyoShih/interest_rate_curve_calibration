# Interest Rate Curve Calibration
This project applies various spline-based interpolation to calibrate interest rate curves using Python and real market bond data (start with simulated one first)

## Project Objective
To construct a smooth zero-coupon interest rate curve (zero curve) that fits market bond prices or yields using spline-based calibration methods.

## Features
- Cubic spline
- Bootstrapping of spot rates from market bond data
- Visualization of the yield curve

## Background
Interest rate curves are essential in pricing, risk management, and asset-liability modeling. This project focuses on using interpolation techniques (especially splines) to construct smooth and arbitrage-free yield or zero-coupon curves.

## Project Structure
interest-rate-curve-spline/
├── data/ # Market bond data (csv format)
├── src/ # Core logic and implementation
│ ├── preprocessing.py # Bond data loading and preprocessing
│ ├── curve_builder.py # Spline calibration engine
│ └── visualization.py # Plotting yield/zero/forward curves
├── notebooks/ # Jupyter notebooks for demo and testing
│ └── curve_fitting_demo.ipynb
├── requirements.txt # Python dependencies
└── README.md # Project description

