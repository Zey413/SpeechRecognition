加入注意力机制的端到端语音识别，采用TIMIT数据集，对音频数据进行处理加工为MFCC特征，实现对音频音素的识别。Listener模块实现了三层pyramidal Bi-LSTM (pBLSTM)的结构对训练速度进行提升。Speller模块加入attention机制计算context vector改进传统循环神经网络。
