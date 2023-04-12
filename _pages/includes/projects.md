
# 📝 Selected Projects 
## 🎙 Speech Synthesis


**Few-shot Voice Cloning and Style Transfer**

- Achieved few-shot voice cloning using 20 utterances. The Similarity-MOS of timbre reached 4.6  with a MOS of 3.8 and a clear pronunciation correction effect on L2 English speakers.
- Pre-train and finetune paradigm and frame-level pitch modeling are used to achieve few-shot style transfer using 20 utterances. The style SMOS has been improved from 3.5 to 4.5 while naturalness MOS remains above 4.0.



## 💬 Speech Recognition & Evaluation
**Recognition and Evaluation of Oral English**
- Design and optimize the Goodness Of Pronunciation (GOP) feature, implementation, and tuning of LR, XGBoost, LSTM classifiers. Attained **SOTA** English oral evaluation consistency rate. 
- Full pipeline chain-model training and optimization based on Kaldi framework, including corpus crawling, language and acoustic model training, Bi-RNN implementation, RNN-Rescore, etc.
- Achieved 5\%-10\% WER on various benchmark datasets and outperformed Google ASR API on children datasets.

## 🗣️ Voice Conversion
- Improved the similarity of voice timbre of an any-to-one PPG-pipeline VC system by adjusting the bottleneck of hidden features
- Implement and learn many-to-many VC models such as VQ-VAE, StarGAN-VC.


## 🎼 Music 

**Probabilistic Topic Models Based Music Recommendation System** *supervisor: [Vladimir Pavlovic](https://www.semanticscholar.org/author/V.-Pavlovic/144658464)* 
- Implement Latent Dirichlet Allocation (LDA) and Hierarchical Dirichlet Process (HDP) probabilistic topic models.
- Use KL divergence to compute the similarity of song-topic probability distributions and use it for the recommendation.