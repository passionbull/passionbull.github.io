
---
title: '[워드프레스 플러그인] 글 자동 업데이트 wordpress -> steem'
permlink: 워드프레스-플러그인-글-자동-업데이트-wordpress---steem
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2018-01-29 17:29:06
categories:

tags:
- kr-dev
- kr
- kr-newbie
- jjangjjangman
- wordpress
thumbnail: 'http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb-300x170.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


<p>안녕하세요.</p>
<p>저는 최근에 주말이나 퇴근 후에</p>
<p>워드프레스 플러그인을 개발하고 있었습니다.</p>
<p>사실 웹쪽은 잘 모르다보니 개발하는데 오래 걸렸습니다.</p>
<p>플러그인은 처음 만들어보는데</p>
<p>개발을 잘해보려고 서점을 가서 워드프레스 관련 책도 읽었습니다.</p>
<p>개발 과정도 올리면 재밌을 것 같아요! ㅎㅎ</p>
<p><strong>열정으로 해결했습니다!</strong></p>
<p><img class="alignnone size-medium wp-image-873" src="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb-300x170.jpg" alt="" width="300" height="170" srcset="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb-300x170.jpg 300w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb-768x435.jpg 768w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb-700x400.jpg 700w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/dcbdbb81ad89dc4ca6dd6bf6f87869bb.jpg 912w" sizes="(max-width: 300px) 85vw, 300px" /></p>
<hr />
<h4>소개</h4>
<p>제가 개발중인 워드프레스 플러그인은</p>
<p>워드프레스에서 글을 작성하면</p>
<p>스팀잇에 업데이트 해주는 플러그인입니다.</p>

<p><img class="alignnone size-large wp-image-877" src="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/캡처333-1024x438.png" alt="" width="840" height="359" srcset="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/캡처333-1024x438.png 1024w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/캡처333-300x128.png 300w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/캡처333-768x329.png 768w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/캡처333-1200x514.png 1200w" sizes="(max-width: 709px) 85vw, (max-width: 909px) 67vw, (max-width: 1362px) 62vw, 840px" /></p>
<p>좋은 점은 아래와 같아요.</p>
<ul>
<li>워드프레스의 환경 그대로 사용할 수  있다는 것 (여러 도구들을 활용 가능)</li>
<li>작성한 글을 내 홈페이지에서도 볼 수 있다는 것</li>
<li>워드프레스를 그대로 활용하기 때문에 글 관리가 편합니다. 검색도 가능하죠.</li>
</ul>
<hr />
<h4>만들게 된 이유</h4>
<p>저는 워드프레스로 만든 홈페이지를 갖고 있었는데요.</p>
<p>처음 스팀잇을 접했을 때, 글쓰는게 너무 불편했고</p>
<p>워드프레스에서 글을 적은걸 그대로 옮기면 참 좋겠다 생각이 들었습니다.</p>
<p>그래서 찾았던 플러그인이 wp-steem이였는데요.</p>
<p>현재 동작하지 않고, 많은 사람들도 찾는 것 같아 개발하게 되었습니다.</p>
<p><img src="https://camo.githubusercontent.com/0c534586f4d866616b61ef26e37849f3a1ce414c/68747470733a2f2f737465656d6974696d616765732e636f6d2f44516d527a7534466e5374645265326d70656d68595a51646550396d755a64596d705634434435455574474a58686d2f62616e6e65722d31353434783530302e706e67" alt="wp-steem에 대한 이미지 검색결과" /></p>
<hr />
<h4>실행 과정은 아래와 같아요.</h4>
<ul>
<li>아이디, 포스팅키, 원하는 태그를 적습니다.</li>
</ul>
<p><img class="alignnone wp-image-869 size-full" src="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/steem-post.png" alt="" width="853" height="723" srcset="http://128.134.57.131/wordpress/wp-content/uploads/2018/01/steem-post.png 853w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/steem-post-300x254.png 300w, http://128.134.57.131/wordpress/wp-content/uploads/2018/01/steem-post-768x651.png 768w" sizes="(max-width: 709px) 85vw, (max-width: 909px) 67vw, (max-width: 1362px) 62vw, 840px" /></p>
<ul>
<li>글을 씁니다.</li>
<li>자동으로 업데이트가 됩니다.</li>
</ul>
<hr />
<h4><strong>추가적으로 개발할 사항</strong></h4>
<ul>
<li>셋팅 페이지 개선</li>
<li>글 작성 페이지에서 Tag 수정</li>
<li>테스트</li>
<li>기타 요구사항</li>
<li>워드프레스 플러그인 배포</li>
</ul>
<hr />
<p>아직 개발이 덜 되었지만 필요하신 분이 있으시다면</p>
<p>설치 파일을 보내드리도록 하겠습니다.</p>
<p>감사합니다.</p>

----

ps.
2018-01-31, 오늘 발견한 글인데요.. ㅋㅋ

Steempress라는 이름으로 이미 9일전에 올린 사람이 있더라고요!!

내가 생각한 것은 다른 사람도 다 할 수 있고, 그렇군요..

심지어 $1346를 보팅을 받았고.. 큭..

내가 찾아볼때는 없었는데.. ㅜㅜ 이미 워드프레스에 플러그인도 등록했더라고요.

아래는 다른사람이 제가 한 것과 거의 같은 기능으로 steem-press 플러그인에 대한 소개입니다.

https://steemit.com/utopian-io/@howo/introducing-steempress-beta-a-wordpress-plugin-for-steem

https://utopian.io/project/drov0/steempress/github/116627747/all

아래는 제 깃허브입니다.

https://steemit.com/utopian-io/@howo/introducing-steempress-beta-a-wordpress-plugin-for-steem

제 것을 개선해나갈지, howo님이 개발한 것을 사용하고 부족한 부분을 기여할지
고민을 해보려고요!

- - -

This page is synchronized from the post: ['[워드프레스 플러그인] 글 자동 업데이트 wordpress -> steem'](https://steempeak.com/@jacobyu/872-hj-kr-dev)
