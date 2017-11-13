---
layout: post
title:  "GTM-GA 전자상거래연동"
author: hawoong.yun
date: 2017-11-13
tags: [GTM],[GA],[ECOMMERCE]
categories: GTM
comments : true
---


엄청난삽질을 하다가 알게된 GTM-GA연동

기본적으로 GTM-GA-쇼핑몰 연동을 하셨다면

향상된 전자상거래 항목을 어찌 추가해야하는지 어려움이 많으신 분들이 많을 것이라고 생각됩니다.

차근차근 진행해보겠습니다.

일단 개념부터 생각을 해볼까요?

1. 전자상거래에 어떤 데이터를 전송할지 생각해보세요(ex. 구매완료된 상품을 GA로 보내고 싶어요!)
2. GTM에서 GA로 보낼 수 있는 TAG를 생성해야하겠군요 (ex. 구매완료 )
3. 어떤 상황에서 TAG를 실행시킬 것인지 생각해서 만들어야합니다. (ex. pageURL에 구매완료페이지 이름이 들어가면 TAG를 실행시키고 싶어요)
4. 전자상거래에 맞는 GTM에서 제시한 데이터를 setting해줘야 TAG에서 해당 데이터를 가져갈 수 있어요.


개념은 위의 양식대로 생각했지만 순서는 반대로 하시면 되요.(사실 편하신대로 해도 관계없어요)

구매완료를 추적하기 위해 GTM에서 제시한 데이터 setting을 먼저 해볼까요? 

GTM 공식 사이트에서는 
(hawoong12.github.io/images/gtm-ga_measuring_purchases.JPG)
