---
layout: post
title: Jekyll 세팅할 때 Ruby 부터 문제가 발생할 때
tags:
  - Jekyll
---

새로운 마음으로 블로그를 시작하려는 데, 설치 권한 문제가 발생했다.
평소처럼 sudo로 해결 될 줄 알았으나 해결이 안되서 구글링을 계속하다가 보니,
이미 공식 사이트에서 발견한 문제였다. 

macOS Mojave 10.14 이상에서 루비 2.3 버전 대가 사용되야 하는데,
루비가 설치된 기존 경로에는 sudo를 써도 권한 오류가 생긴다.
**rbenv**를 통해 새 버전의 루비를 깔고 지킬을 설치한다.


[Jekyll on macOS](https://jekyllrb.com/docs/installation/macos/)


