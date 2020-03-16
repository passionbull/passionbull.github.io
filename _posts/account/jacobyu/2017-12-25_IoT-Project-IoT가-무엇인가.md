
---
title: '[IoT Project] IoT가 무엇인가?'
permlink: IoT-Project-IoT가-무엇인가
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2017-12-25 04:59:06
categories:
- 개발
- iot
tags:
- kr-dev
- kr-friendship
- kr-news
- jiwon23
- kr
thumbnail: 'http://www.lgblog.co.kr/wp-content/uploads/2015/09/%EC%9C%A0%ED%94%8C%EB%9F%AC%EC%8A%A4-IOT.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


4차 산업, 로봇, IoT, 사물 인터넷 등 최근에 핫한 키워드이다.

오늘은 IoT에 대해 정리를 해보려고 한다.
<h3>IoT (Internet of Things)의 정의를 먼저 보자!</h3>
<blockquote><b>사물 인터넷</b>(Internet of Things, 약어로 IoT)은 각종 사물에 <a title="센서" href="https://ko.wikipedia.org/wiki/%EC%84%BC%EC%84%9C">센서</a>와 통신 기능을 내장하여 <a title="인터넷" href="https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%84%B7">인터넷</a>에 연결하는 기술을 의미한다. <strong>인터넷으로 연결된 사물들이 데이터를 주고받아 스스로 분석하고 학습한 정보를 사용자에게 제공하거나 사용자가 이를 원격 조정할 수 있는 <a title="인공지능" href="https://ko.wikipedia.org/wiki/%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5">인공지능</a> 기술이다.</strong><sup id="cite_ref-1" class="reference"><a href="https://ko.wikipedia.org/wiki/%EC%82%AC%EB%AC%BC_%EC%9D%B8%ED%84%B0%EB%84%B7#cite_note-1">[1]</a></sup> 여기서 사물이란 가전제품, 모바일 장비, 웨어러블 컴퓨터 등 다양한 <a title="임베디드 시스템" href="https://ko.wikipedia.org/wiki/%EC%9E%84%EB%B2%A0%EB%94%94%EB%93%9C_%EC%8B%9C%EC%8A%A4%ED%85%9C">임베디드 시스템</a>이 된다. 사물 인터넷에 연결되는 사물들은 자신을 구별할 수 있는 유일한 <a title="인터넷 프로토콜" href="https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%84%B7_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C">아이피</a>를 가지고 인터넷으로 연결되어야 하며, 외부 환경으로부터의 데이터 취득을 위해 센서를 내장할 수 있다.<sup id="cite_ref-2" class="reference"><a href="https://ko.wikipedia.org/wiki/%EC%82%AC%EB%AC%BC_%EC%9D%B8%ED%84%B0%EB%84%B7#cite_note-2">[2]</a></sup><sup id="cite_ref-3" class="reference"><a href="https://ko.wikipedia.org/wiki/%EC%82%AC%EB%AC%BC_%EC%9D%B8%ED%84%B0%EB%84%B7#cite_note-3">[3]</a></sup> 모든 사물이 <a title="해킹" href="https://ko.wikipedia.org/wiki/%ED%95%B4%ED%82%B9">해킹</a>의 대상이 될 수 있어 사물 인터넷의 발달과 보안의 발달은 함께 갈 수밖에 없는 구조이다. - 위키백과</blockquote>
길다!!

내가 생각하는 방식으로 요약하자면..
위키백과와 유사하지만 아래와 같다.
<blockquote>IoT는 사물 (인터넷에 연결될 수 있는 모든 것)간에 연결되어 서로 통신할 수 있는 시스템 - Jacob</blockquote>
IoT가 갑자기 나온 기술 같지만 그렇지 않다.

혹시 유비쿼터스 (Ubiquitous), 유비쿼터스 컴퓨팅를 아시는가? IoT랑 똑같은 말이다.
<blockquote>'Ubiquitous'와 컴퓨팅이 결합된 단어로 '언제 어디서든 어떤 기기를 통해서도 컴퓨팅할 수 있는 것'을 의미한다. - 위키백과</blockquote>
IoT, 유비쿼터스가 같은 꿈, 목표를 갖고 있는 것을 볼 수 있다.

즉, 옛날부터 항상 꿈꿔왔지만 환경, 기반이 안되었다.

임베디드 보드도 비싸고, 통신 칩도 비싸고

요즘은 점점 싸지면서 이런 환경을 갖출수있는 기반이 되었다고 생각한다.
<h3>예를 들어 어떤 것들이 있을까?</h3>
<strong>홈서비스가 대표적인 IoT라고 생각한다.
<a href="http://smartincome.tistory.com/250" target="_blank" rel="noopener">IoT 여러 서비스</a>
</strong>
<ul>
 	<li>Google Homeservice</li>
 	<li><strong>LG IoT@Home - 홈서비스</strong></li>
</ul>
스마트폰으로 집 안에 여러 디바이스들에 접근할 수 있다.

가스밸브는 잠궜는지, 불은 껐는지

내가 10시에 들어가니 그 때맞춰서 불켜놔!

에어컨도 돌려놓고! 등등 여러가지로 활용가능하다.

<img class="" src="http://www.lgblog.co.kr/wp-content/uploads/2015/09/%EC%9C%A0%ED%94%8C%EB%9F%AC%EC%8A%A4-IOT.jpg" alt="LG IoT@Home에 대한 이미지 검색결과" width="470" height="331" />

거기에다가 최근에는

LG의 홈 서비스 시스템에 네이버의 인공지능 스피커를 넣겠다는 소식이 있었다.
<strong><a href="http://biz.khan.co.kr/khan_art_view.html?artid=201712181046001&amp;code=920501" target="_blank" rel="noopener">LG와 네이버 힘을 합치다 - 뉴스</a></strong>

즉, 스마트폰으로 여러 명령을 하는 것 대신에

말만해도 원하는 것을 하는!! 그런 시대가 올 거라 믿는다.

- - -

This page is synchronized from the post: ['[IoT Project] IoT가 무엇인가?'](https://steempeak.com/@jacobyu/iot)
