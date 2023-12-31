---
subtitle: Results
permalink: /results/
---


<h1>Benchmark Results</h1>
The following tables show the results of our experiments

### forecast task, 900 points (1-step MSE):

| model             |   Advection |    Burgers |   Gas Dynamics |   Kuramoto-Sivashinsky |   Reaction-Diffusion |       Wave |
|:------------------|------------:|-----------:|---------------:|-----------------------:|---------------------:|-----------:|
| CNN               | 5.30848e-05 | 0.0110988  |     0.00420368 |            0.000669837 |          0.00036918  | 0.00143387 |
| FeaSt             | 0.000130351 | 0.0116155  |     0.0162     |            0.0117867   |          0.000488848 | 0.00523298 |
| GAT               | 0.00960113  | 0.0439986  |     0.037483   |            0.0667057   |          0.00915208  | 0.0151498  |
| GCN               | 0.026397    | 0.13899    |     0.0842611  |            0.436563    |          0.164678    | 0.0382004  |
| GraphPDE          | 0.000137098 | 0.0107391  |     0.0194755  |            0.00719822  |          0.000142114 | 0.00207144 |
| KernelNN          | 6.31157e-05 | 0.0106146  |     0.013354   |            0.00668698  |          0.000187019 | 0.00542925 |
| NeuralPDE         | 8.24453e-07 | 0.0112373  |     0.00373416 |            0.000536958 |          0.000303176 | 0.00169871 |
| Persistence       | 0.0812081   | 0.0367688  |     0.186985   |            0.142243    |          0.147124    | 0.113805   |
| Point Transformer | 4.41633e-05 | 0.0103098  |     0.00724899 |            0.00489711  |          0.000141248 | 0.00238447 |
| PointGNN          | 2.82496e-05 | 0.00882528 |     0.00901649 |            0.00673036  |          0.000136059 | 0.00138772 |
| ResNet            | 2.15721e-06 | 0.0148052  |     0.00321235 |            0.000490104 |          0.000156752 | 0.00145884 |

### forecast task, 900 points (1-step MSE):

| model             |       Advection |   Burgers |   Gas Dynamics |   Kuramoto-Sivashinsky |   Reaction-Diffusion |     Wave |
|:------------------|----------------:|----------:|---------------:|-----------------------:|---------------------:|---------:|
| CNN               |     0.00161331  |  0.554554 |       0.995382 |            1.26011     |          0.0183483   | 0.561433 |
| FeaSt             |     1.48288     |  0.561197 |       0.819594 |            3.74448     |          0.130149    | 1.61066  |
| GAT               | 41364.1         |  0.833353 |       1.21436  |            5.68925     |          3.85506     | 2.38418  |
| GCN               |     3.51453e+13 | 13.0876   |       7.20633  |            1.70612e+24 |          1.75955e+07 | 7.89253  |
| GraphPDE          |     1.07953     |  0.729879 |       0.969208 |            2.1044      |          0.0800235   | 1.02586  |
| KernelNN          |     0.897431    |  0.72716  |       0.854015 |            2.00334     |          0.0635278   | 1.57885  |
| NeuralPDE         |     0.000270308 |  0.659789 |       0.443498 |            1.05564     |          0.0224155   | 0.247704 |
| Persistence       |     2.39393     |  0.679261 |       1.457    |            1.89752     |          0.275678    | 2.61281  |
| Point Transformer |     0.617025    |  0.503865 |       0.642879 |            2.09746     |          0.0564399   | 1.27343  |
| PointGNN          |     0.660665    |  1.04342  |       0.759257 |            2.82063     |          0.0582293   | 1.30743  |
| ResNet            |     8.64621e-05 |  1.86352  |       0.480284 |            1.0697      |          0.00704612  | 0.299457 |
