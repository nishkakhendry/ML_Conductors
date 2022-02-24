# ML_Conductors

Data from [kaggle](https://www.kaggle.com/c/nomad2018-predict-transparent-conductors).

## Setup:

```bash
conda create --name ml_project python=3.7
conda activate ml_project
pip install -r requirements.txt
```

> Run `visualization_dataprep.ipynb` to get `train_extrainfo.csv` in the data folder. It's not commited as it's huge (600MB+). i/o examples are in the same file.

## Notes

- the magnitude of each vector (in the xyz file) is the `lattice_vector_1_ang` and so on. Magnitude refers to the vector length
- the lattice vectors span the entire stuctures give, so they are a primitive unit of the crystal lattices they form

## possible ideas

- diff mol structures, same composition
