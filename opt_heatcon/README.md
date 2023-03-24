# Execution Results

## Creep rupture

このデータはMIntを利用した最適化のフレームワークであるMIOptにより実行された最適化の結果です。

This data is the result of optimization performed by MIOpt, a MInt-based optimization framework.

| File                            | Description   |
|:--------------------------------|:--------------|
| Creep_rupture_input.csv         |Initial data　 |
| Creep_rupture_BatchBO_0.001.csv |Result of BatchBO with jitter=0.001|
| Creep_rupture_BatchBO_0.005.csv |Result of BatchBO with jitter=0.005|
| Creep_rupture_BatchBO_0.02.csv  |Result of BatchBO with jitter=0.02|
| Creep_rupture_BatchBO_0.1.csv   |Result of BatchBO with jitter=0.1|
| Creep_rupture_Cubist.csv        |Result of Cubist update|
| Creep_rupture_jParaBO.csv       |Result of jParaBO with jitter=[0.001, 0.005, 0.02, 0.1]|
| Creep_rupture_SeqBO.csv         |Combined SeqBO results run at jitter=0.001, 0.005, 0.02, 0.1|

## Rosen brock

このデータはRosenbrock式を利用したMIOptの最適化のベンチマークの結果です。

This data is the result of benchmarking the optimization of MIOpt using the Rosenbrock formula.

| File                            | Description   |
|:--------------------------------|:--------------|
| Rosenbrock_input.csv            |Initial data　 |
| Rosenbrock_BatchBO_0.001.csv    |Result of BatchBO with jitter=0.001|
| Rosenbrock_BatchBO_0.005.csv    |Result of BatchBO with jitter=0.005|
| Rosenbrock_BatchBO_0.02.csv     |Result of BatchBO with jitter=0.02|
| Rosenbrock_BatchBO_0.1.csv      |Result of BatchBO with jitter=0.1|
| Rosenbrock_Cubist.csv           |Result of Cubist update|
| Rosenbrock_jParaBO.csv          |Result of jParaBO with jitter=[0.001, 0.005, 0.02, 0.1]|
| Rosenbrock_SeqBO.csv            |Combined SeqBO results run at jitter=0.001, 0.005, 0.02, 0.1|
