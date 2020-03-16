
---
title: '[JJM Holders] 자동보팅 툴, 개발 과정'
permlink: JJM-Holders-자동보팅-툴-개발-과정
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-04-07 04:20:24
categories:

tags:
- kr-dev
- busy
- jjm
- kr
- steem-engine
thumbnail: 'https://steemitimages.com/0x0/https://i.ibb.co/q5zvPfj/720c17602a67.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


<p>안녕하세요. 제이콥입니다.</p>
<p>JJM 홀더 페이지를 만들고 있습니다.</p>
<p>이번에는 자동보팅 기능을 넣어봤습니다.</p>
<p><a href="https://passionbull.github.io/jjm-list/">https://passionbull.github.io/jjm-list/</a></p>
<p>https://ipfs.busy.org/ipfs/QmSo24cBTN2JquKKf44bkitiGhunq645J18jc6PbAu6wHs</p>
<hr />
<h3>과정은 이렇습니다.</h3>
<ol>
<li>프로그램이 실행되는 시간 -7일 이내 각 홀더의 글들을 찾습니다.</li>
<li>프로그램을 실행시키는 시간 – 1일 이내 ‘virus707’의 계정으로 보팅이 됐는지 확인합니다.
<ol>

    - 보팅이 돼있다면, 이미 JJM보팅을 받은것으로 취급합니다.

</ol>
</li>
<li>필터링합니다.

    - 7일 이내  JJM태그를 붙여 글을 썻다.

    - 보팅이 안됐다.

    - JJM 보유량에 따라 정렬한다.

</li>
<li>스팀커넥트로 계정을 연결합니다.</li>
<li>보팅 퍼센트대로 보팅합니다.</li>
</ol>
<hr />
<h3>한번 테스트 해보겠습니다.</h3>
<p>지금 웨이팅 리스트를 뽑아보니,</p>
<p>3월31일 오전 6시 14분 이후 글을 썼지만 보팅이 안된 리스트입니다.</p>
<p>https://ipfs.busy.org/ipfs/QmXbx6QNLqq4tJFPoyfLYLxzsVYoKTrKNR7jyTWpHJnetv</p>
<p>테스트를 하기 위해, 제 계정으로 보팅을 해봤습니다.</p>
<p>잘 되는것 같습니다!</p>
<hr />
<h3>문제점</h3>
<p>유저들의 정보를 가져오는데 오래걸립니다.</p>
<p>각 유저마다 7일 이내의 글에 보팅이 있었는지 확인하기 위해 재귀호출을 합니다.</p>
<p>서버를 하나 두고, 미리 작업을 한 후, 웹페이지에서 요청할 때 값을 주는 식으로 하면 좀더 빠르게 할 수 있겠다 생각했습니다.</p>
<p>아니면, steem db를 사용하면 좀 더 빠르게 데이터를 가져올 수 있지 않을까 생각했습니다.</p>
<p>보팅을 하는데도 꽤 오래걸립니다.</p>
<p>steemConnect를 활용해서 보팅을 하는데, 한번에 여러개 보팅을 못합니다.</p>
<p>그래서 보팅이 끝나고 다음 보팅을 할 수 있도록 해봤습니다.</p>
<hr />
<h3>JJM Holders 개발 계획</h3>
<p>1. 리액트로 변경, UI 개선</p>
<p>2. 자동 배당 툴 기능 추가</p>
<hr />
<h3>참고</h3>
<p><a href="https://github.com/steemit/steem-js/tree/master/doc">스팀 자바스크립트 라이브러리</a></p>
<p><a href="https://steemit.com/kr-dev/@codingman/steem-js-post">스팀포스팅 재귀함수</a></p>
<p><a href="https://gafani.tistory.com/entry/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EB%82%A0%EC%A7%9C-%EB%B9%84%EA%B5%90-%EC%9D%B4%EC%A0%84-%EC%9D%B4%ED%9B%84-%EB%82%A0%EC%A7%9C-%EA%B3%84%EC%82%B0%ED%95%98%EA%B8%B0">자바스크립트 날짜 계산</a></p>
<p><a href="https://stackoverflow.com/questions/43397803/how-to-re-render-flatlist">react-native flatlist의 리랜더링</a></p>
<p><a href="https://ndb796.tistory.com/216">리액트 메테리얼 ui</a></p>
<p><a href="https://www.vobour.com/%EB%B2%A0%EC%8A%A4%ED%8A%B8-10-%EB%A6%AC%EC%95%A1%ED%8A%B8-ui-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-10-best-react-ui-lib">리액트 ui 라이브러리 리스트</a></p>
<p> </p>
<p>혹시 잘못표기된게 있거나 궁금한것, 제안, 조언, 버그 발견 등등 편하게 말해주세요.</p>
<p>감사합니다!</p>


- - -

This page is synchronized from the post: ['[JJM Holders] 자동보팅 툴, 개발 과정'](https://steempeak.com/@jacobyu/1989-jjm-holders-dev-2)
