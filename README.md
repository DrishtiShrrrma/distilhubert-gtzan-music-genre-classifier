# Important

1. set the random seed

# Models to be Assessed

1. DistilHuBERT
2. Wav2Vec2
3. HuBERT  ---> batch_size -->25, 32 --> ran into OOM error + batch_size =18 --> 1h 40m

# Constraints to be Assessed

1. Model Performance
2. Training Time
3. Amount of Overfitting, train_loss, val_loss
4. other metrics


# Observations

1. DistilHuBERT
- Batch_size --> 8, time: 1h 52min 40s, Accuracy = 84%
- Batch_size --> 16, time: 1h 51min 29s, Accuracy = 87%

2. HuBERT
- Batch_size --> 8, time: 31min 41s , Accuracy = 100% (sth is wrong w this model!)
- Batch_size --> 16, time: , Accuracy = OOM Error

