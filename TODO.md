Forecaster Classes
- [x] unified inputs `y` and `exog` to pandas Series and pandas Dataframe
- [x] unified `predict` and `predict_interval`
- [x] unified inputs checks as static methods
- [x] ForecasterBase as parent class
- [ ] add examples in docstrings (statsmodels)
- [ ] add references in docstrings (statsmodels)

Module model_selection
- [x] unified cross-validation and backtsting throught argument `refit`
- [ ] unified `grid_search` methods throught argument `refit`

Model_selection_statsmodels:
- [x] Change all inputs of `y` and `exog` to pandas Series and pandas DataFrame
- [x] Combine `backtesting_sarimax_statsmodels` and `cv_sarimax_statsmodels` in a single function

Module utils
- [x] all static methods for checking and preprocessing inputs of ForecasterBase moved to module utils

Unit testing:
- [ ] ForecasterAutoreg
- [ ] ForecasterAutoregCustom
- [ ] ForecasterAutoregMultioutput
- [ ] model_selection
- [x] utils

