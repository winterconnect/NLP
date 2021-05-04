

## NLP 코드모음

혼자서 공부하면서, 혹은 강의를 들으면서 틈틈이 정리한 NLP 관련 코드들의 모음입니다.

제가 제일 재밌게 작업하는 레포이기 때문에, 계속해서 업데이트될 예정입니다.





### 목록

1. Word2Vec English

   - Data Preprocessing
   - Tokenization(nltk)
   - Word2Vec(gensim)

   

2. Word2Vec Korean

   - 네이버 영화 리뷰 데이터 사용
   - Data Preprocessing (정규표현식, 불용어 제거)
   - Tokenization(KoNLPy Okt)
   - 데이터 분포 시각화
   - Word2Vec(gensim)

   

3. Pre-trained Word2Vec Embedding

   - English: GoogleNews-vector-negative300
   - Korean: ko.bin

   

4. Skipgram with Negative Sampling(SGNS)

   - Data Preprocessing(Null 제거, 정규화, 소문자화, 불용어 제거)
   - Tokenization(Keras)
   - Skip-gram(Keras)
   - Skip-gram with Negative Sampling(Keras)

   

5. Tagging Task using Bidirectional LSTM

   - Data Preprocessing(정규화, 단어-태깅 분리)
   - Tokenization(Keras)
   - OOV로 대체된 단어 확인
   - Bi-LSTM 개체명 인식기(Keras)

   

6. Machine Translation using LSTM

   - Load Data: kor-eng.zip
   - 글자단위 번역기: encoder(LSTM), decoder(LSTM)
   - 단어단위 번역기: encoder(LSTM), decoder(LSTM)

   

7. Attention

   - Load Data: Reviews(English)
   - Data Preprocessing: 동일한 의미지만 스펠링이 다른 단어 정규화
   - Modeling: Encoder(LSTM) + Decoder(LSTM + attention)

   

8. Transformer

   - 모델에 대한 전반적인 이해
   - Positional Encoding
   - Scaled dot-product Attention(Query, Key, Value)
   - Multi-head Attention
   - Masking
   - Encoder & Decoder

   

9. Chatbot using Transformer

   - Load Data: Chatbotdata%20
   - Data Cleansing
     - 구두점 앞에 공백 추가
     - 단어집합 생성
     - 정수인코딩과 패딩
   - 챗봇 모델링 & 평가

   

10. Text Summarzation using Attention & seq2seq

    - 7번 모델의 보완모델

    

11. TextRank Summarization





### 느낀점
- 데이터 전처리의 방법은 정말 다양하다
- 양질의 데이터를 학습시키는 것이 정말 중요한데, 그것을 위해 중요하고 중요한 것이 바로.... 전처리다
- 자연스럽게 말하는 모델을 만드는 게 정말정말 어렵다.
- Transformer의 성능이 좋아서, 이 모델 기반의 Bert, GPT를 사용해보고 싶다 (조만간)






