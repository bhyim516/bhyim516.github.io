---
title: "Sample"
date: 2018-12-27 16:40:00 -0400
categories: computer vision
use_math: true
---
Camera2Camera 캘리브레이션
Corner Detection -> sub-pixel and orientation refinement -> structure recovery -> matching -> optimization

A. Corner Detection
  1) x-y축과 정렬된 edge에 의해 나타나는 코너와 45도 기울어진 축과 정렬된 edge에 의해 나타나는 코너 2가지의 corner prototype을 이용하여 corner likelihood를 계산
     (Perspective 변환에 의한 distortion이 존재할 때, 위 필터가 코너를 찾는데 충분한 성능을 보인다)
     
     ![screenshot from 2018-12-27 16-36-09](https://user-images.githubusercontent.com/17023023/50470867-ae743680-09f5-11e9-9b3c-95a74e74e1f7.png)
  2) 
