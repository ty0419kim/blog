---
layout: post
title:  "Simple Linear Regression Coefficients"
categories: Deep-Learning Simple-Linear-Regression
permalink: /:categories/:title:output_ext
---


## Estimating the Coefficients

<script
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript">
</script>

기본 방법은 least sum of squared error 값이 최소가 되는 parameters(Coefficients)를 구하는 것이다.

아래 수식에서 $$b_{0}$$, $$b_{1}$$를 유도한다.

$$\hat y=\hat b_{0}+\hat b_{1}x $$

# Normal Equation
![Regression Coefficient Estimation - 1]({{site.baseurl}}/assets/img/RegCoeffEst_1.JPG)

# Linear Algerbra 방식을 사용해서 유도
Projection 특성을 이용해서 계산한다.
![Coefficient Est by Linear Algerbra-1]({{site.baseurl}}/assets/img/RegCoeff_by_LinAlg.JPG)
![Coefficient Est by Linear Algerbra-2]({{site.baseurl}}/assets/img/RegCoeff_by_LinAlg_2.JPG)

# 결론
Normal Equation과 선형대수의 Vector의 Projection 특성을 사용한 방법 모두 사용 가능.
![Normal Equ vs Linear Alg(Projection)]({{site.baseurl}}/assets/img/IMG_8296.JPG)
