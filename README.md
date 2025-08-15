# Quant Modeling — EDA + Baseline

## Run
1) conda create -n jpm -y python=3.10 && conda activate jpm
2) pip install -U pip && pip install pandas numpy scikit-learn matplotlib scipy torch notebook jupyterlab ipykernel python-dateutil
3) python -m ipykernel install --user --name jpm --display-name "Python (jpm)"
4) Put data in `data/`: training_loan_data.csv, testing_loan_data.csv
5) jupyter lab
6) Run `notebooks/01_EDA_Git.ipynb` then `notebooks/02_Modeling_Inference.ipynb`
7) Predictions: `outputs/test_predictions.csv` (id,bad_flag)

## Notes
- EDA visuals saved in `reports/figures/*` and tables in `reports/tables/*`.
- Baseline: Logistic Regression;  NN.
