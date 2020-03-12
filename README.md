# RPC-Leaderboard


<div style="text-align: justify">

## The RPC dataset leaderboard
Experimental settings are consistent with the settings in [the RPC paper](https://arxiv.org/abs/1901.07249): 53k single exemplar images for training, and 24k checkout images for test.

| *Method*             |   *cAcc* |  *mCIoU* |  *ACD* | *mCCD* |  *mAP50* |   *mmAP* | *link* |
| :---                 |   ---: |   ---: | ---: | ---: |   ---: |   ---: | :--- |
| Eleme: Syn+Render    | 92.20% | 99.22% | 0.09 | 0.01 | 99.04% | 83.86% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/7) |
| DPNet: Syn+Render    | 80.51% | 97.33% | 0.34 | 0.03 | 97.91% | 77.04% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/6), [paper](https://arxiv.org/abs/1904.04978) |
| CommNet: Syn+Render  | 75.93% | 96.84% | 0.39 | 0.03 | 97.41% | 75.78% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/10) |
| Baseline: Syn+Render | 56.68% | 93.19% | 0.89 | 0.07 | 96.57% | 73.83% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/3), [project](http://rpc-dataset.github.io) |
| Baseline: Render     | 45.60% | 90.58% | 1.25 | 0.10 | 95.50% | 72.76% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/2), [project](http://rpc-dataset.github.io) |
| Baseline: Syn        |  9.27% | 69.65% | 4.27 | 0.35 | 80.66% | 53.08% | [detail](https://github.com/RPC-Dataset/RPC-Leaderboard/issues/1), [project](http://rpc-dataset.github.io) |


</br>

If you have been successful in creating a model based on the training set and it performs well on the validation set, we encourage you to run your model on the test set. The [`rpctool`](https://github.com/DIYer22/retail_product_checkout_tools) will contribute to return the corresponding results of the evaluation metrics. You can submit your results on the RPC leaderboard by creating a new issue. Your results will be ranked in the leaderboard and to benchmark your approach against that of other machine learners. We are looking forward to your submission. Please click [RPC-Dataset/RPC-Leaderboard/issues](https://github.com/RPC-Dataset/RPC-Leaderboard/issues)

</div>
