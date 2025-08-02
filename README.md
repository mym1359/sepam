# Sepam - AI-Powered Banking Credit Assessment System

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview

Sepam is an intelligent credit scoring system for banking customers using machine learning algorithms. The system can:

- Predict customer credit risk
- Calculate intelligent credit scores
- Detect fraud patterns
- Optimize credit decision-making

## Key Features

✅ High accuracy in credit risk prediction  
✅ Automated financial data processing  
✅ Analytical reporting generation  
✅ Integration capability with banking systems  
✅ Retrainable models with new data  

## Installation

1. First, clone the repository:

```bash
git clone https://github.com/yourusername/sepam.git
cd sepam
```

2. Create and activate virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate    # For Windows
```

3. Install requirements:

```bash
pip install -r requirements.txt
```

## Usage

1. Place sample data in `data/customer_data.csv`
2. Run the main script:

```bash
python sepam_system.py
```

## Project Structure

```
sepam/
├── data/                   # Sample data folder
│   └── customer_data.csv
├── models/                 # Trained models
│   └── sepam_credit_model.pkl
├── sepam_system.py         # Main system code
├── requirements.txt        # Requirements
└── README.md               # This file
```

## Input Data Format

The CSV file should contain the following columns:

| age | monthly_income | credit_history | current_loans | debt_amount | debt_to_income_ratio | violation_history | fixed_assets | credit_risk |
|-----|----------------|----------------|---------------|-------------|----------------------|-------------------|--------------|-------------|
| 35  | 15000000       | 5              | 1             | 5000000     | 0.33                 | 0                 | 200000000    | low         |

## Contributing

Your contributions are welcome. Please:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions and suggestions:

Email: mym1359@gmail.com  
