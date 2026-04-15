# Emotion-classifier
I have build an emotion detection model which detects emotions from texts, By finetuning BERT transformer model(bert-base-uncased).
- Dataset used : Go Emotions dataset(Google)
- I have done **Multi-label classification** over here.
- Hosted on Hugging Face Spaces too
  
  HF space link : https://huggingface.co/spaces/nayadrika/emotion_detection_model
- Loss function used : BCEWithLogitsLoss
- Model is trained to recognize **28 emotions**,

  such as :
  
| # | Emotion | # | Emotion |
|---|---------|---|---------|
| 1 | admiration | 15 | fear |
| 2 | amusement | 16 | gratitude |
| 3 | anger | 17 | grief |
| 4 | annoyance | 18 | joy |
| 5 | approval | 19 | love |
| 6 | caring | 20 | nervousness |
| 7 | confusion | 21 | optimism |
| 8 | curiosity | 22 | pride |
| 9 | desire | 23 | realization |
|10 | disappointment | 24 | relief |
|11 | disapproval | 25 | remorse |
|12 | disgust | 26 | sadness |
|13 | embarrassment | 27 | surprise |
|14 | excitement | 28 | neutral |

## 📊 Evaluation Metrics

| Metric | Score |
|-------|------|
| **Micro F1** | 0.606 |
| **Macro F1** | 0.466 |
| **Precision** | 0.592 |
| **Recall** | 0.620 |
| **Evaluation Loss** | 0.169 |
