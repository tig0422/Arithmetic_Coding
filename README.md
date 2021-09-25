Used weight file for Arithmetic coding


# Original FP32 weight

FP32 weight of AlexNet : https://github.com/BVLC/caffe/tree/master/models/bvlc_alexnet


# Pruning

Pruned weight for AlexNet : https://github.com/kaiqzhan/admm-pruning

Reference : Zhang, Tianyun, et al. "A systematic dnn weight pruning framework using alternating direction method of multipliers." Proceedings of the European Conference on Computer Vision (ECCV). 2018.

Pruned weight for CaffeNet : https://github.com/kaiqzhan/ADAM-ADMM

Reference : Zhang, Tianyun, et al. "Adam-admm: A unified, systematic framework of structured weight pruning for dnns." arXiv preprint arXiv:1807.11091 2.3 (2018).


# Quantization

We quantized "pruned weight" to 5-bit by Incremental Network Quantization

Quantized weight of AlexNet : https://drive.google.com/file/d/1iDSELUYTPTHqZ4VHGhKr2z22tiXuPt58/view?usp=sharing 

Quantized weight of CaffeNet : https://drive.google.com/file/d/1lxK-2RzjEJhQgyK323k68RLxMlk7UQRy/view?usp=sharing

Reference : Zhou, Aojun, et al. "Incremental network quantization: Towards lossless cnns with low-precision weights." arXiv preprint arXiv:1702.03044 (2017).
