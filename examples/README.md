# Examples
## Competitions
| Place         | Competition   | Description | Solution  |
| ------ |:------------- | --------- | --------- |
| 1st | [2024 AutoML Grand Prix](https://www.kaggle.com/automl-grand-prix) | Team "LightAutoML testers" | [1 stage](https://www.kaggle.com/competitions/playground-series-s4e5/discussion/500700), [3 stage](https://www.kaggle.com/competitions/playground-series-s4e7/discussion/516860), [4 stage](https://www.kaggle.com/competitions/playground-series-s4e8/discussion/523732), [5 stage](https://www.kaggle.com/competitions/playground-series-s4e9/discussion/531884) |


## Code snippets
1. `demo0.py` - building ML pipeline from blocks and fit + predict the pipeline itself.
2. `demo1.py` - several ML pipelines creation (using importances based cutoff feature selector) to build 2 level stacking using AutoML class
3. `demo2.py` - several ML pipelines creation (using iteartive feature selection algorithm) to build 2 level stacking using AutoML class
4. `demo3.py` - several ML pipelines creation (using combination of cutoff and iterative FS algos) to build 2 level stacking using AutoML class
5. `demo4.py` - creation of classification and regression tasks for AutoML with loss and evaluation metric setup
6. `demo5.py` - 2 level stacking using AutoML class with different algos on first level including LGBM, Linear and LinearL1
7. `demo6.py` - AutoML with nested CV usage
8. `demo7.py` - AutoML preset usage for tabular datasets (predefined structure of AutoML pipeline and simple interface for users without building from blocks)
9. `demo8.py` - creation pipelines from blocks to build AutoML, solving multiclass classification task
10. `demo9.py` - AutoML time utilization preset usage for tabular datasets (predefined structure of AutoML pipeline and simple interface for users without building from blocks)
11. `demo10.py` - creation pipelines from blocks (including CatBoost) to build AutoML, solving multiclass classification task
12. `demo11.py` - AutoML NLP preset usage for tabular datasets with text columns
13. `demo12.py` - AutoML tabular preset usage with custom validation scheme and multiprocessed inference
14. `demo13.py` - AutoML TS preset usage with lag and diff transformers' parameters selection
15. `demo14.py` - Groupby features (using TabularAutoML preset and custom pipeline)
