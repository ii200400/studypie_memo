# 정사영 (1일차)

https://ko.khanacademy.org/math/linear-algebra/alternate-bases#orthogonal-projections

## 부분공간에 대한 정사영

계속 이전에 설명했다는 말이 많이 나오는데 그 동영상을 안보고 넘어가는 커리큘럼이라 대충 유추해서 들었다;\
이전에 들었던 정사영의 개념이 부분공간에서도 성립한다는 이야기이다. 그냥.. 복습이다.

+ 직교 여공간 (orthogonal complement) : 주어진 부분공간과 수직인 벡터들의 공간
+ 행렬 A의 영공간과 대칭행렬의 열공간은 직교여공간이다.

## 평면에 대한 정사영 시각화

바로 이전의 동영상에 대한 예시를 시각화해주며 복습한다.

## 부분공간에 대한 정사영이 선형변환이라는 것 확인하기

제목 그대로 부분공간에 대한 정사형이 선형변환 조건에 부합하는지 확인한다.\
위의 과정에서 투사를 위한 변환행렬을 구할 수 있다는 것을 증명하기도 하였다.

## 부분공간 정사영 행렬의 예제

위에서 도출해낸 식에 특정 숫자를 넣어 정사영의 계산 예시를 보인다.\
증명을 하는 것도 아니고 그냥 계산식에 숫자 대입해서 풀어보는 것 뿐이므로 내용은 쉽다.

## 정사영 행렬의 다른 예제

부분공간에 대한 정사영 증명을 한번 더 복습하면서 계산예시를 보인다.
직전 동영상과는 다른 방법으로 정사영 행렬을 찾는다.

## 정사영은 부분공간에서 제일 가까운 벡터라는 것을 확인하기

+ 부분 공간 V에 벡터 x를 투영한 벡터 P(x)는 V에서 x로의 가장 가까운 벡터이다.
  + 벡터 a가 P(x)와 직교인 것과 피타고라스 삼각공식을 생각하면 가장 가까운 벡터라는 것을 쉽게 알 수 있다.

# 정사영(약 45분)

https://ko.khanacademy.org/math/linear-algebra/alternate-bases#orthogonal-projections

[참고 유투브 동영상](https://www.youtube.com/watch?v=jNwf-JUGWgg)

## 최소제곱 근삿값

+ 행렬 A와 벡터 x, b에 대해 A(x)=b일 때, 해가 없다면 가장 근접한 해를 정사영으로 구할 수 있다.
  + 위의 결과물을 최소제곱 근삿값이라고 부른다.

## 최소제곱 예제

정사영을 활용하여 근삿값을 구하는 예제를 보여준다.

## 다른 최소제곱의 예제

정사영을 활용하여 여러 점들과의 거리의 합이 가장 적게되는 선분을 찾는 예시를 보인다.

# 실습 - PCA1 가우시안 분포의 PCA (3일차)

Tensorflow 2.0을 활용하여 가우시안 분포 실습을 해본다.

[실습코드](https://colab.research.google.com/drive/1-hdnbUCfOUYUj8kcAZ8ABN2StGXEqYQY)

# 실습 - PCA2 암 판별 데이터 PCA 차원 축소 (4일차)

Tensorflow 2.0을 활용하여 PCA2 암 판별 데이터 PCA 차원 축소 실습을 해본다.

[실습코드](https://colab.research.google.com/drive/1cAjjlQL8KRHIPQKuPo38VtmP-30d-pOJ)

# 실습 - 주성분분석(PCA) (5일차)

Tensorflow 2.0을 활용하여 주성분분석(PCA) 실습을 해본다.

[실습코드](https://colab.research.google.com/drive/1muGf4mY9A9bZE8wwS-0DH_YeqyL8lJzk)
