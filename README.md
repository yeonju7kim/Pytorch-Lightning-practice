# Pytorch-Lightning-practice

## MNIST 테스트

## 학습 조건

- 1080ti 1개
- i7 4세대

``` python
trainer = pl.Trainer(gpus=1, num_nodes=1, precision=16, limit_train_batches=0.5)
```

## 학습 결과
|Epoch|train loss|
|---|---|
|0|0.0462|
|1|0.0438|
|2|0.0425|
|3|0.0416|
|4|0.0411|
|5|0.0406|
|6|0.0402|
|7|0.0399|
|8|0.0396|
|9|0.0394|
|10|0.391|
|11|0.390|
