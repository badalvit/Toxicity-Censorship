# Toxicity Censorship model

This is a small deep learning project where I built a model to detect toxic comments.  
You give it a sentence, and it tells you if it’s toxic (insult, threat, etc.).

I made this mainly to understand how NLP models actually work in real life.

---

## How it works

- Text is converted into numbers  
- Passed through an LSTM model  
- Outputs scores for different toxicity labels  

---

## Tech used

Python, TensorFlow/Keras, Pandas

---

## Files

- Train.py → trains the model  
- Predict.py → tests it  
- Toxicity_Detector.h5 → saved model  

---

## Dataset

Dataset is not included (around 66 MB).

Download from Kaggle and place it in the folder, then:

python Train.py  
python Predict.py  

---

## Notes

Still a basic model. Accuracy can be improved and UI can be added later.
