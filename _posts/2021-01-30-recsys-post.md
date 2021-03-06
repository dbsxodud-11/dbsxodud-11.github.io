---
title : Overview of Recommendation System
categories : categories
date : 2021-01-30 17-40-00
use_math : true
---

# 추천 시스템이란?

---

추천 시스템이란 주어진 데이터를 바탕으로 사용자의 아이템에 대한 선호도를 예측해서, 사용자가 좋아할만한 아이템을 사용자에게 보여주는 것입니다. 어떤 아이템에 대한 사용자의 선호도를 어떤 데이터와 모델을 사용하여 예측하는 것이 가장 효과적일 지 고민하는 일이 추천 시스템 개발자가 하는 일이라고 생각할 수 있겠습니다.


추천 시스템이 사용자의 니즈를 정확이 파악하기 위해서 많은 추천 방법론이 등장했습니다. 가장 대표적인 추천 방법론으로는 **협업 필터링(Collaborative Filtering)**과 **콘텐츠 기반 필터링(Content-Based Filtering)**이 있습니다. 최근에는 **딥러닝(Deep-Learning)**이나 **강화학습(Reinforcement Learning)**을 활용하는 연구도 계속 진행되고 있습니다. 이번 글에서는 먼저 가장 많이 사용되는 협업 필터링과 콘텐츠 기반 필터링에 대해 설명하도록 하겠습니다.


### 협업 필터링(Collaborative Filtering)
 

협업 필터링은 콘텐츠 사용 패턴이 비슷한 사람들이 동일한 아이템에 대해서 서로 비슷한 선호도를 가지고 있을 것이라는 아이디어로부터 출발하였습니다. 협업 필터링에서는 사용자들의 아이템에 대한 선호도 등의 데이터를 바탕으로 사용자들의 유사도를 계산하고, 이 유사도에 따라 사용자가 사용하지 않았던 아이템에 대한 선호도를 예측합니다.


협업 필터링에서 가장 흔히 사용되는 기술은 **행렬 분해(Matrix Factorization)** 방식입니다. 행렬 분해 방식에서는 사용자가 사용한 아이템에 대한 선호도를 <span style="color:darkgray">그림1</span> 와 같이 행렬로 나타냅니다. 이 행렬을 랭크가 작은 두 개의 행렬로 나눈 다음, 이 두 개의 행렬의 곱이 원래 행렬과 비슷한 값을 가지도록 학습하는 방법입니다. 기존 행렬을 나누고 다시 복원하는 과정에서 사용자가 소비하지 않았던 아이템에 대한 선호도를 계산할 수 있습니다. 학습은 아래 식에 있는 비용 함수(Cost function)을 최소화하는 방향으로 진행되는데, 주로 ALS(Alternating Least Squares)나 SGD(Stochastic Gradient Descent)방법을 사용하여 파라미터를 학습시킵니다.

![Matrix Factorization](C:/Projects/dbsxodud-11.github.io/assets/images/matrix_factorization.png)

최근에는 단순히 행렬 분해를 통해 사용자의 선호도를 예측하는 것이 아니라, **오토인코더(AutoEncoder)**를 사용하여 원본 데이터에서 중요한 값들만 뽑아낸 다음, 뽑아낸 핵심 값들을 사용하여 원본 데이터를 복원하는 방식으로 사용자의 선호도를 예측하기도 합니다. 최근에 가장 각광받고 있는 베리에이션 오토인코더(VAE, Variational AutoEncoder)에서는 원본 데이터를 인코더(Encoder)에 집어넣어 중요한 값들(Latent Feature)의 분포 정보를 얻은 다음, 얻은 분포 정보를 활용해 중요한 값들을 뽑아 디코더(Decoder)에 집어넣어 원본 데이터와 같은 차원(Dimension)을 가지는 벡터를 복원하는 방식으로 학습을 진행합니다. <span style="color:darkgray">그림2</span> 를 통해 쉽게 이해할 수 있습니다.

![VAE](C:/Projects/dbsxodud-11.github.io/assets/images/variational_autoencoder.png)

### 콘텐츠 기반 필터링(Content-Based Filtering)


<div style="text-align: left">  콘텐츠 기반 필터링은 사용자나 아이템 자체의 정보를 분석해 사용자가 좋아한 아이템과 유사한 아이템을 찾아내는 방법입니다. 아이템에 따라서 텍스트, 이미지, 영상 등 다양한 데이터를 사용할 수 있고, 딥러닝 방법을 사용해 각 데이터에서 중요한 특성(feature)를 뽑아내는 방법이 많이 연구되고 있습니다. 


대표적으로 자연어 처리 도메인에서 나온 **Word2Vec** 알고리즘을 사용하여 텍스트로부터 아이템의 정보를 얻을 수 있습니다. Word2Vec은 많은 문장들(Corpus)을 통해 단어의 의미를 벡터로 저장하는 모델입니다. Word2Vec에서 단어 벡터(임베딩이라고도 합니다)를 학습하는 방법에는 CBOW(Continuous Bag of Words)와 SkipGram이 있습니다. 전자는 주변 단어들을 가지고 중심 단어가 등장할 확률을 최대화하는 방식으로, 후자는 중심 단어로부터 주변 단어들이 등장한 확률을 최대화하는 방법으로 학습을 진행합니다.</div> 










