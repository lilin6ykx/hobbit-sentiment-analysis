# Quantifying Emotional Tone in Tolkien’s *The Hobbit*  
### Dialogue Sentiment Analysis Using RegEx, NRC-VAD, and Python

This repository contains the code, visualizations, and processing workflow used in the study:

**"Quantifying Emotional Tone in Tolkien’s *The Hobbit*: Dialogue Sentiment Analysis with RegEx, NRC-VAD, and Python"**

The code in this project was originally developed and executed in **Google Colab**, where the full workflow — from regex dialogue extraction to sentiment analysis and visualization — was prototyped and tested.

Please note that **some input files**, such as the full *Hobbit* source text, as well as **certain output files**, such as chapter-level extracted text, **are not included** in this repository due to copyright restrictions. Users will need to provide their own legally obtained text sources to reproduce the full workflow.

This project demonstrates how computational approaches can reveal literary emotional structure and support digital philology.

---

## 🔧 Method Overview

1. **Dialogue Extraction** using regex from full text  
2. **Preprocessing**: tokenization, normalization, punctuation removal, contraction handling, stopword filtering  
3. **Sentiment Analysis with NRC-VAD**  
4. **Visualization** of emotional trajectory + word clouds  
5. **Chapter-based emotional comparison**

Primary libraries used: `re`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `wordcloud`, `nltk`.

---

## 🔗 External Resources

Extended English stopword list used in preprocessing:  
https://gist.githubusercontent.com/rg089/35e00abf8941d72d419224cfd5b5925d/raw/12d899b70156fd0041fa9778d657330b024b959c/stopwords.txt

NRC-VAD Lexicon:  
https://saifmohammad.com/WebPages/nrc-vad.html

---

## 📜 Citation

If you use the code, visualizations, or methodology in research:

```
Lilin Qiu (2025). Quantifying Emotional Tone in Tolkien’s The Hobbit:
Dialogue Sentiment Analysis with RegEx, NRC-VAD, and Python.
GitHub Repository. https://github.com/lilin6ykx/hobbit-sentiment-analysis
```

---

## 📬 Contact

Author: **Lilin Qiu**  
Email: laurenqiu12@proton dot me

---

### ⭐ If this project helps you, consider starring the repo to support it!

