### seq2seq modeling

#### paper: https://paperswithcode.com/paper/a-memory-network-based-solution-for
#### 논문에서는 LSTM을 Enoder로 사용하였지만, CNN이 특징추출에 도움이 될거라고 생각해서 LSTM 대신에 CNN(Conv1d)를 사용하였습니다.
#### 그리고 kernel size 를 1x1로 하여서 local한 특징보다는 Sequence 하나하나의 특징을 얻게 하였습니다.
