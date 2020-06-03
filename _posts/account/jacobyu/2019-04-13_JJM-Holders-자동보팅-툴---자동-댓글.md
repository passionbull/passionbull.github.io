
---
title: '[JJM Holders] 자동보팅 툴 - 자동 댓글'
permlink: JJM-Holders-자동보팅-툴---자동-댓글
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-04-13 02:40:54
categories:

tags:
- kr-dev
- busy
- jjm
- kr
thumbnail: 'https://steemitimages.com/0x0/https://i.ibb.co/q5zvPfj/720c17602a67.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


<p>안녕하세요. 제이콥입니다. JJM 홀더 페이지를 만들고 있습니다.</p>
<p>개발하고 있는 부분을 공유합니다.</p>
<p>보팅을 할 때 미리 정해진 댓글 달기 기능을 개발 중입니다.</p>
<p>그리고 필터링 부분에 실수가 있어 수정하였습니다.</p>
<p>이제는 JJM이 보팅을 할 때 댓글을 남길 수 있게됐습니다!!­</p>

https://passionbull.github.io/jjm-list/

<p>https://ipfs.busy.org/ipfs/QmbFG8GqpBr7chuLVRBB3ELQJJrHeZtzjaBNddux7QPX8U</p>
<p> </p>
<hr />
<h3>버그 수정된 부분</h3>
<p>자동 보팅 툴 지난버젼에서 실수가 있었습니다. <strong>‘jjm’ 태그의 사용 여부</strong> 필터링을 제대로 체크못했습니다.</p>

> 7일 이내  글을 썻다. 
'virus707'님의 보팅이 안됐다. 
JJM 보유량에 따라 정렬한다.

<p>위의 3개는 지켰으나, 중요한 조건 중에 하나인 ‘jjm’ 태그 여부를 빼먹었습니다.</p>
<p>그래서, 지금까지의 보팅은 홀더가 7일 이내 글을 썻다면 ‘jjm’여부와 관계없이 제일 최신 글에 됐습니다.</p>
<p>이번에 ‘jjm’ 태그 필터링을 넣음으로, 원래 보팅룰을 지킬 수 있게됐습니다.</p>
<p>몇 개 글을 체크해봤을때, 모두 jjm이 들어가 있어서, <strong>‘jjm’ 태그의 사용 여부</strong>를 넣다고 생각했습니다.</p>
<p>다음에는 이런 실수를 빨리 해결하거나 미연의 방지할 수 있도록 노력하겠습니다.</p>
<hr />
<h3>JJM 필터링</h3>
<p>jjm의 필터링은 아래의 과정으로 이뤄집니다.</p>
<p>스팀에 작성된 글에는 언제 작성하였는지, 몇 명이 보팅하였는지, 베너피셔리는 있는지, 태그는 어떤 것을 사용했는지 등등.</p>
<p>많은 정보가 포함되어 있습니다.</p>
<p>저는 여기서 json_meta의 tags정보를 활용하여 이 태그들 중에 ‘jjm’이 있는지 확인합니다.</p>
<p>https://ipfs.busy.org/ipfs/Qmem5d7hcWvK9fgceZQAEHE7XfaYWuXtpbhGKz2NnZdih8</p>
<hr />
<h3>자동 댓글 작성</h3>
<p>댓글 작성은 지금까지 구현을 해놓은 게 있어서 편했습니다.</p>
<p>보팅을 하는 함수에서 추가적으로 댓글을 다는 부분을 붙였습니다.</p>
<p>하지만 코드에다가 댓글내용을 픽스해 놓을 경우, 넣고싶은 댓글이 달라질때마다 코드를 수정해야하는 일이 생깁니다.</p>
<p>그래서, 댓글의 내용은 제 서버에 간단한 API 서버에 저장할 예정입니다. 이렇게 하면, 넣고 싶은 댓글을 언제든지 수정 가능합니다.</p>
<p>현재는 코드에 댓글 내용을 적어놨지만, 빠른 시일 내에 서버 관련 부분을 개발할 계획입니다. (이 부분은 공부해놓은게 있어서 금방 할 것 같습니다.)</p>
<hr />
<p>JJM 보팅 룰대로 보팅이 안되고 있다거나, 문제가 있는 경우 언제든지 말씀해주세요!</p>
<p>감사합니다.</p>


- - -

This page is synchronized from the post: ['[JJM Holders] 자동보팅 툴 - 자동 댓글'](https://steempeak.com/@jacobyu/2018-jjm-holders-dev-3)
