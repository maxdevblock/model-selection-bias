# model-selection-bias
Model selection bias: simulations

---

This is a collection of Jupyter Notebooks to help understand and experimentally verify the effects of model selection.

Currently:

1. [A simple simulation](https://github.com/maxdevblock/model-selection-bias/blob/main/model_selection_bias.ipynb): forward stepwise model selection applied to linear regression

2. [A simple solution](https://github.com/maxdevblock/model-selection-bias/blob/main/split_the_dataset.ipynb): can the simple solution of splitting the data into two parts (one for the model selection and the other for inference) really solve the model selection bias?

3. [Prediction and forecast](https://github.com/maxdevblock/model-selection-bias/blob/main/prediction_forecast.ipynb): does the model selection bias affect prediction/forecast also?

---

System requirements

- `Python 3.11.13`

```
conda create -n model-selection python=3.11.13
```

Suggested packages' versions
- `numpy 1.26.4` 
- `pandas 2.3.1`
- `scipy 1.16.0`
- `statsmodels 0.14.5`
- `matplotlib 3.10.0`
- `seaborn 0.13.2`
- `tqdm 4.67.1`
- `jupyter_client 8.6.3`
- `jupyter_core 5.8.1`
- `jupyterlab_widgets 3.0.15`
- `ipython 9.5.0`