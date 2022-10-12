# ogbl_d

## Requirements
```
Python==3.7
Pytorch==1.8.1+cu101
dgl-cu101==0.8.1
torch-cluster==1.5.9
torch-geometric==2.0.1
torch-scatter==2.0.6
torch-sparse==0.6.12
ogb==1.3.4
```

## Reproduce
```
sh ddi.sh
```

## Performance

|  Model   | Test Hits@20 (%) | Validation Hits@20 (%) |
|  ----  | ----  | ----  |
| PLNLP | 90.88±3.13 | 82.42±2.53 |
| AGDN | 95.38±0.94 | 89.43±2.81 |
| GIDN@YITU | 95.42±0.00 | 82.58±0.00 |


## Reference
- https://ogb.stanford.edu/
- https://github.com/skepsun/Adaptive-Graph-Diffusion-Networks/
