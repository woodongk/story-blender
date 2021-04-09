## seq2seq 모델을 적용시킨 스토리 문장 생성 연구
- ︎Human-Like Story Generation from Caption Using Seq2Seq Model ( 🤖 machine-like ➡️ 🧑 human-like )
- 2018년도 아주대학교 미디어학과 졸업 프로젝트 최우수상 수상 

```bash
"the fireworks are shooting off in the sky" -> [Seq2Seq model] -> "the fireworks were beautiful"
```
---

## Requirement
- tensorflow 2.2.0
- keras 2.4.3
---

### 프로젝트 목적 
- Sequence-to-Sequence (Seq2Seq) 모델은 주로 **한 도메인인(예: 한국어 문장)에서 다른 도메인**(예: 영어로 번역된 동일한 문장)의 sequence로 sequence를 변환하기 위한 모델을 말한다. 
- "기계가 생성한 딱딱한 문장을 인간이 쓴 듯한 언어로 변형하면 어떨까?"라는 단순한 생각에서 시작하게 된 프로젝트

### 1. 데이터셋 : VIST

- 본 프로젝트를 위한 데이터로 마이크로소프트 사에서 제공하는 VIST(Visual Storytelling Dataset)을 사용함 
- VIST는 주로 image captioning task에 쓰이는 데이터셋으로, 특정 이벤트로 묶인 순차적인 이미지들을 각각 캡션 문장(descriptions for images in isolation, DII)과 순차적인 스토리 문장(stories for images in sequence, SIS)의 쌍으로 제공
- image captioning task에 쓰이는 기술은 현 시점에서 매우 발전되어 있기에 데이터셋 또한 쉽게 구할 수 있었음 
- [[Code]](https://github.com/woodongk/story-blender/blob/master/1.%20VIST_data%20preprocessing.ipynb)

### 2. seq2seq 모델



### Reference
- [Kim, Y. (2014). Convolutional neural networks for sentence classification.](https://arxiv.org/abs/1408.5882)
- [CNN in keras with pretrained word2vec weights | Kaggle](https://www.kaggle.com/marijakekic/cnn-in-keras-with-pretrained-word2vec-weights)
- [Using pre-trained word embeddings in a Keras model](https://blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html)
- [Implementing a CNN for Text Classification in TensorFlow – WildML](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)



