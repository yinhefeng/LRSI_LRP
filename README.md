# LRSI_LRP
Low rank matrix recovery with structural incoherence plus low rank projection matrix
<br>
<br>
The code is for the following conference paper, in which we present a new method which is based on low rank matrix recovery with structural incoherence and low rank projection (LRSI_LRP). LRSI_LRP is able to tackle the situation when both training and test samples are corrupted due to occlusion and disguise. First, the training images are decomposed into a set of clean images and sparse errors via LRSI, and the derived clean images from distinct classes are encouraged to be as independent as possible by introducing structural incoherence regularization term into robust PCA. Then a low-rank projection matrix is learned based on the original training images and the recovered clean ones, and this low-rank projection matrix can correct corrupted test samples by projecting them onto their corresponding underlying subspaces. Finally, the corrected test samples are classified based on sparse representation based classification (SRC).
<br>
<br>
He-Feng Yin, Xiao-Jun Wu. Face Recognition Based on Structural Incoherence and Low Rank Projection. 2016 International Conference on Intelligent Data Engineering and Automated Learning (IDEAL 2016), pp. 68-78.
