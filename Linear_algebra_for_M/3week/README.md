#  고유값, 고유벡터 (1일차)

https://ko.khanacademy.org/math/linear-algebra/alternate-bases/alternate-bases/eigen-everything/v/linear-algebra-introduction-to-eigenvalues-and-eigenvectors

## 고유값과 고유벡터란?

+ 고유벡터(eigenvector) : 선형 변환이 일어난 후에도 방향이 변하지 않는, 영벡터가 아닌 벡터
+ 고유값(eigenvalue) : 고유벡터가 변환되는 '크기'
 + 만약 변환 T에 의해 벡터 v가 스칼라 c만큼만 변한다면(T(v)=cv) c는 고유값, v는 고유벡터이다.
 + 고유벡터로 적절한 기저벡터를 만들기 쉽다.

## 고유값을 결정하는 식 증명

이전에 설명했던 선형독립의 특징을 사용하여 고유값을 결정하는 식을 증명한다.

## 2x2 행렬의 고유값을 구하는 예제

위에서 구한 λv-Av=0 과 v가 영벡터가 아님을 이용하여 고유값을 구하는 예시를 보여준다. (A는 행렬, v는 벡터, λ는 고유값)\
위의 식은 (λ-A)의 행렬식이 0이 참인 조건이 되며 이를 이용하여 λ를 구한다.

## 고유벡터와 고유공간을 구하는 예제

+ 고유공간(eigenspace) : 특정 고유값(λ)에 대응되는 고유벡터(v)들의 집합
  + 고유값에 대응하는 고유공간은 영공간을 구하는 것처럼 기약사다리꼴 행렬을 만들어서 구한다.
  + 고유값과 해당 고유값의 고유공간의 벡터가 지정되어있다면 어떤 A를 넣더라도 A에 (고유값 만큼의)스칼라 곱을 한 결과만이 나온다.

## 3x3 행렬의 고유값

2x2 행렬의 고유값을 구하는 방법을 그대로 3x3 행렬에 적용시키는 예시를 보인다.

## 3x3 행렬의 고유벡터와 고유공간

2x2 행렬의 특정 고유값의 고유벡터를 구하는 방법을 그대로 3x3 행렬에 적용시키는 예시를 보인다.\
동영상에서 구한 2개의 고유공간은 서로 직교라는 것이 밝혀진다.

## 고유기저와 좌표계

+ 고유기저(eigenbasis) : 어떤 선형변환(T=Av)의 고유 벡터들로 구성된 v의 기저
+ 좌표계(coordinate system) : 기저를 기준으로 좌표를 표현하는 방법 (잘 모르겠다.)

# 실습 - 고유값 분해(Eigendecomposition) (2일차)

Tensorflow 2.0을 활용하여 고유값 분해(Eigendecomposition) 실습을 해본다.

+ 고유값 분해(eigen decomposition) : 고유값과 고유벡터로부터 유도되는 고유값 행렬과 고유벡터 행렬에 의해 분해될수있는 행렬의 표현

# 실습 - 특이값 분해(Singular Value Decomposition) (3일차)

Tensorflow 2.0을 활용하여 특이값 분해(Singular Value Decomposition) 실습을 해본다.

+ 특이값 분해(Singular Value Decomposition, SVD) : 행렬을 특정한 구조로 분해하는 방식

참고 동영상 - [Singular Value Decomposition](https://www.youtube.com/watch?v=cq5qlYtnLoY)

# 실습 - 무어-펜로즈 의사역행렬(Pseudo Inverse) (4일차)

Tensorflow 2.0을 활용하여 무어-펜로즈 의사역행렬(Pseudo Inverse) 실습을 해본다.

+ 무어-펜로즈 유사역행렬(Moore–Penrose pseudoinverse matrix) : 가역 행렬의 역행렬 연산을 일반화하는 연산이다.
  + 모든 모양의 행렬에 대하여 정의되는 연산이다.
  + 특이값 분해를 통해 계산할 수 있다.

참고 블로그 - [의사역행렬(Pseudo inverse)](https://bskyvision.com/256)

[2~4일차 실습코드](https://colab.research.google.com/drive/1r7s7tKVoylQXGldLridqX1MdBpQ3IJSa)

# 실습 - SVD Image compression 및 Eigenface (5일차)
 
Tensorflow 2.0을 활용하여 SVD Image compression과  실습을 해본다.

[실습코드 - SVD Image compression](https://colab.research.google.com/drive/1KM4j26dCH9Zgq0oJkY7lg_CEsW6oQ5jN)

[실습코드 - Eigenface](https://colab.research.google.com/drive/1K-gUxAEhasjuCOE4fbfDrEVNo0lVlI6i)

---

## 궁금한 점

+ 행렬식(determinant) : 정사각행렬에서만 정의되는 값으로, 행렬의 가역성을 판별해준다
  + 행렬 A의 행렬식이라면 det(A)라고 표현한다.
  + 고유값이나 고유벡터 증명에 사용된다.


---
