# ML_Conductors

Data from [kaggle](https://www.kaggle.com/c/nomad2018-predict-transparent-conductors).

## Setup:

```bash
conda create --name ml_project python=3.7
conda activate ml_project
pip install -r requirements.txt
```

## Running instructions
- Exploratory data analysis can be found in the `exploratoryanalysis.ipynb` notebook
- For the final chosen submission using XGBoost and the 3D cube representation, run `final_submission.ipynb`
- To try out approach 1, first run `visualization_dataprep.ipynb` to get `train_extrainfo.csv` and `test_extrainfo.csv` in the data folder. It has not een included due to it' large size (600MB+). i/o examples are in the same file.
- For approach 2, run the cells in the `cube_method.ipynb` notebook.

