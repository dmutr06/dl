# Deep Learning Labs

Lab reports as executed Jupyter notebooks ([lab1](lab1/lab1.ipynb), [lab3](lab3/lab3.ipynb)). Each notebook downloads its Kaggle data on first run and can submit at the end.

## Run

1. Join the competition on Kaggle and create an API token at https://www.kaggle.com/settings.
2. Provide the token:
   - locally: `export KAGGLE_API_TOKEN=...` (or `~/.kaggle/kaggle.json`), then `cd lab3 && uv sync && uv run --with jupyter jupyter lab`;
   - in Google Colab: add a `KAGGLE_API_TOKEN` secret (key icon) and, for lab 3, pick a GPU runtime.
3. Run all cells. Set `SUBMIT = True` in the first code cell to upload `submission.csv` to Kaggle.
