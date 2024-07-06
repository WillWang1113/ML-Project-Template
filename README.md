# ML-Project-Template
Python template for machine learning

## Usage
Before cloning this template, first build a new repo in your GitHub.

1. Clone the bare repo:
```
git clone --bare https://github.com/WillWang1113/ML-Project-Template.git
```

2. Push this template repo to your new repo
```
cd ML-Project-Template.git
git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
```

3. Delete the bare repo and clone your own repo
```
cd ..
rm -rf ML-Project-Template.git
git clone https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
```

## Stuctrue
```
./
├── configs
│   ├── json_config.json
│   └── yaml_config.yaml
├── LICENSE
├── notebooks
│   └── my_notebook.ipynb
├── README.md
├── run.sh
├── scripts
│   └── my_experiments.py
├── setup.py
├── src
│   └── __init__.py
└── tests
```
