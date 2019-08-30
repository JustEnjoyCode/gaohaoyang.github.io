---
layout: post
title:  "벡터의 외적 기초"
date:   2019-08-30 17:00:00 +0900
categories: 기초수학
tags: 기하
author: booknu
mathjax: true
---

* content
{:toc}
## 외적의 정의

$\vec{a}\times\vec{b} = (a_2b_3-a_3b_2,\ a_3b_1-a_1b_3,\ a_1b_2-a_2b_1)$

$$\vec{a}\times\vec{b}\\=\begin{vmatrix}a_2 & a_3 \\ b_2 & b_3\end{vmatrix}\vec{i}-\begin{vmatrix}a_1 & a_3 \\ b_1 & b_3\end{vmatrix}\vec{j}+\begin{vmatrix}a_1 & a_2 \\ b_1 & b_2\end{vmatrix}\vec{k}\\=\begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \end{vmatrix}$$     $(\vec{i}, \vec{j}, \vec{k}$ 는 각 축의 단위 벡터$)$

- **방향**: 두 벡터와 동시에 수직
- **크기**: 두 벡터를 변으로 하는 평행사변형의 넓이
  - $\lvert\vec{a}\times\vec{b}\rvert = \lvert\vec{a}\rvert\lvert\vec{b}\rvert\sin\theta$

![]({{site.url}}/img/190830_OuterProduct/finger.png)

## 외적의 성질

- 분배 법칙
  - $\vec{a}\times(\vec{b}+\vec{c}) = (\vec{a}\times\vec{b})+(\vec{a}\times\vec{c})$
- 교환 법칙 성립 안 함
  - $\vec{a}\times\vec{b} = -\vec{b}\times\vec{c}$
- 스칼라배는 자유롭게 이동 가능
- $\vec{a} \times \vec{a} = \vec{0}$



## 외적의 활용

### 삼각형 넓이

![]({{site.url}}/img/190830_OuterProduct/tri.png)



### 평행사변형 넓이

![]({{site.url}}/img/190830_OuterProduct/parallel.png)



### 점과 직선 사이의 거리

![]({{site.url}}/img/190830_OuterProduct/dist.png)



### 평면의 법선

![]({{site.url}}/img/190830_OuterProduct/normal1.png)

![]({{site.url}}/img/190830_OuterProduct/normal2.png)



## 출처

https://j1w2k3.tistory.com/635

https://assortrock.com/24

https://m.blog.naver.com/PostView.nhn?blogId=mindo1103&logNo=90103361104&proxyReferer=https%3A%2F%2Fwww.google.com%2F