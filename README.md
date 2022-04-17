# ML_Conductors

Data from [kaggle](https://www.kaggle.com/c/nomad2018-predict-transparent-conductors).

## Setup:

```bash
conda create --name ml_project python=3.7
conda activate ml_project
pip install -r requirements.txt
```

## Running instructions
- Run the cells in the `cube_method.ipynb` notebook.
- To try out other approaches, first Run `visualization_dataprep.ipynb` to get `train_extrainfo.csv` and `test_extrainfo.csv` in the data folder. It's not committed as it's huge (600MB+). i/o examples are in the same file.
- Exploratory data analysis is in the `exploratoryanalysis.ipynb` notebook
