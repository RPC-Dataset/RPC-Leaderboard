# RPC-Leaderboard

If you have been successful in creating a model based on the training set and it performs well on the validation set, we encourage you to run your model on the test set. The *rpc-tool* (in the next section in this project page) will contribute to return the corresponding results of the evaluation metrics. You can submit your results on the RPC leaderboard by creating a new issue. Your results will be ranked in the leaderboard and to benchmark your approach against that of other machine learners. We are looking forward to your submission. Please click [RPC-Dataset/RPC-Leaderboard/issues](https://github.com/RPC-Dataset/RPC-Leaderboard/issues)

## The RPC dataset leaderboard
Experimental settings are consistent with the settings in [the RPC paper](dd): 53k single exemplar images for training, and 24k checkout images for test.

| method               |   cAcc |  mCIoU |  ACD | mCCD |  mAP50 |   mmAP | link |
| :---                 |   ---: |   ---: | ---: | ---: |   ---: |   ---: | :--- |
| Baseline: Syn        |  9.27% | 69.65% | 4.27 | 0.35 | 80.66% | 53.08% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/3), [project](http://rpc-dataset.github.io) |
| Baseline: Render     |  45.6% | 90.58% | 1.25 |  0.1 |  95.5% | 72.76% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/3), [project](http://rpc-dataset.github.io) |
| Baseline: Syn+Render | 56.68% | 93.19% | 0.89 | 0.07 | 96.57% | 73.83% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/3), [project](http://rpc-dataset.github.io) |
