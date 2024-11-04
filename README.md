# my-first-app

## Setup

Create a virtual environment (first time only):
```sh
conda create -n reports-env-2024 python=3.10
```

Activate a virtual environment (whenever you come back to this project):
```sh
conda activate reports-env-2024
```

Install packages:
```sh
pip install -r requirements.txt
```


## Usage

Run the example script:
```sh
python app/my_script.py
```

Run the unemployment report:
```sh
ALPHAVANTAGE_API_KEY="OPEKNZB4Q8AUFTDY" python app/unemployment.py
```