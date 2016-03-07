# Alpine-Kaggle

Docker Image for Kaggle competitions.

```bash
$ docker run --rm -i smly/alpine-kaggle which xgboost
/opt/xgboost-0.47/xgboost

$ docker run --rm -i smly/alpine-kaggle python -c 'import xgboost; print(xgboost.__version__)'
0.4
```
