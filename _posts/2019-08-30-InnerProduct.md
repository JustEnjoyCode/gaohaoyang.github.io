---
layout: post
title:  "벡터의 내적 기초"
date:   2019-08-30 17:00:00 +0900
categories: 기초수학
tags: 기하
author: booknu
mathjax: true
---

* content
{:toc}
## 내적의 정의

$$\vec{a} \cdot \vec{b} = |\vec{a}||\vec{b}|\cos\theta = a_1b_1+a_2b_2$$

- 벡터를 다른 벡터에 정사영시킨 크기의 곱

## 내적의 특징

- 내적의 결과로 **스칼라** 값이 나옴
- 두 벡터 중 하나라도 $\vec{0}$이면 내적의 결과는 $0$
- :$\vec{a} \cdot \vec{a} = |\vec{a}||\vec{a}|\cos0 = |\vec{a}|^2$
- :$\vec{a}//\vec{b}\ 이면\ \vec{a}\cdot \vec{b} = \pm|\vec{a}||\vec{b}| $
  - 벡터가 평행하다는 뜻은, $\theta=$ $0$ or $\pi$
- $\vec{a} \perp \vec{b}\ 이면\ \vec{a} \cdot \vec{b} = 0$
- $\vec{a} \cdot \vec{b} = |\vec{a}||\vec{b}|\cos\theta=|\vec{a}|\times|\vec{b}|의\ 정사영$

## 내적의 성질

- 교환 법칙
- 스칼라배는 자유롭게 이동 가능
- 분배법칙 성립

## 내적의 응용

- 수직 판별 (내적이 $0$)
- 두 벡터의 각
  - $$\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|} = \frac{a_1b_1+a_2b_2}{\sqrt{{a_1}^2+{a_2}^2} \times \sqrt{{b_1}^2+{b_2}^2}}$$

