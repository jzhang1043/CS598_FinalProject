# CS598_FinalProject
# Cite:
```
@inproceedings{kipf2017semi,
  title={Semi-Supervised Classification with Graph Convolutional Networks},
  author={Kipf, Thomas N. and Welling, Max},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2017}
}
@article{kipf2016semi,
  title={Semi-Supervised Classification with Graph Convolutional Networks},
  author={Kipf, Thomas N and Welling, Max},
  journal={arXiv preprint arXiv:1609.02907},
  year={2016}
}
```
# Original paper’s repo:
```
https://github.com/tkipf/keras-gcn/tree/master
```
# Dependencies:
  * Python 2.7 or 3.6
  * PyTorch 0.4 or 0.5
# Dataset:
```
http://www.cs.umd.edu/~sen/lbc-proj/LBC.html
![graph_classification](https://github.com/jzhang1043/CS598_FinalProject/blob/main/data_s.png)
```
# Usage
```
command lines showed in CS598FinalProject.ipynb
python train.py
```
# Main Results:
| Learning Rate | Classification Accuracy |
| ------------- | ------------- |
| 0.00001  | 0.155 |
| 0.0001   | 0.138 |
| 0.001  | 0.340 |
| 0.01   | 0.824 |
| 0.1  | 0.838 |

| Dropout Rate | Classification Accuracy |
| ------------- | ------------- |
|0.1  |0.831 |
|0.2  |0.835 |
|0.3  |0.838 |
|0.4  |0.833 |
|0.5  |0.824 |
|0.6  |0.836 |
|0.7  |0.805 |
|0.8  |0.798 |
|0.9  |0.701 |

| Dataset | Classification Accuracy |
| ------------- | ------------- |
| 0.00001  | 0.155 |
| 0.0001   | 0.138 |
| 0.001  | 0.340 |
| 0.01   | 0.824 |
| 0.1  | 0.838 |
|Cornell |0.829|
|Texas|0.834|
|Washington |0.836|
|Wisconsin|0.823|

