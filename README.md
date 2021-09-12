# Speech Command Recognition

Audio classifier network using M5 network architecture for recognizing trigger commands.

Using the [SpeechCommands](https://arxiv.org/abs/1804.03209) dataset, we preprocess the data by generating encodings and lookups, followed by collating 
data and padding so tensors have consistent shape.

The M5 model is optimized using Adam optimizer with weight decay regularization and custom learning rate scheduler.

After training 20 epochs on training set, model achieves 87.3% testing accuracy.

### References:
- [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)
- [Very Deep Convolutional Neural Networks for Raw Waveforms](https://arxiv.org/pdf/1610.00087.pdf)











