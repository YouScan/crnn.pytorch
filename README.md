Convolutional Recurrent Neural Network
======================================

This software implements the Convolutional Recurrent Neural Network (CRNN) in pytorch.
Origin software could be found in [crnn](https://github.com/meijieru/crnn.pytorch)

Train a new model
-----------------
1. Construct dataset and alphabeth  following `generate_lmdb_dataset.ipynb`
2. Execute ``PYTHONIOENCODING=utf-8 python3.6 train.py --adadelta --trainRoot train_sample --valRoot test_sample --cuda --random_sample -alphabeth alphabeth``. Explore ``train.py`` for details.
