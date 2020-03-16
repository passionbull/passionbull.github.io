
---
title: 'AWS S3를 aws-cli로 관리하자'
permlink: AWS-S3를-aws-cli로-관리하자
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-03-14 11:47:36
categories:
- 개발
- tool
- aws
tags:
- kr-dev
- busy
- jjangjjangman
thumbnail: 'https://steemitimages.com/0x0/https://i.ibb.co/q5zvPfj/720c17602a67.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


<h4>AWS S3</h4>
<p>AWS s3는 아마존에서 제공하는 스토리지 서비스입니다다.</p>
<p>쉽게 말하면, 구글 드라이브나 드랍박스 같은 느낌입니다.</p>
<p>데이터 확장에 용이하다고 해서 사용해보게 됐습니다. (돈만 내면 된다.)</p>
<p>지금은 Free tier라서 무료로 사용중입니다.</p>
<h4>AWS S3가 필요했던 이유</h4>
<p>저는 AWS-s3를 이미지 호스팅, 데이터 저장을 위해 사용하고 있습니다.</p>
<p>데이터 양이 적어 console page에서 파일을 관리했었습니다.</p>
<p>근데 파일이 점점 많아지고, 수정하거나 새로 업데이트한 파일 목록을 열람할 필요가 있어서 콘솔만으로는 안되겠다 생각했습니다.</p>
<p>aws-s3 explorer로 찾아보다 ftp, aws-cli등이 있었습니다. 저는 aws-cli를 선택했습니다.</p>
<h4>AWS S3 관리 시스템 필요</h4>
<p>aws-cli를 활용해서 관리하기로 했습니다.</p>
<blockquote><p>https://console.aws.amazon.com/iam/home?region=ap-northeast-2#/security_credentials</p>
<ul>
<li>create new access key</li>
</ul>
<p>sudo apt-get -y install awscli</p>
<p>aws configure</p>
<ul>
<li>발급받은 access key, private key를 입력합니다. bucket의 지역도 입력합니다.</li>
</ul>
<p>aws s3 sync s3://buckey_name/folder ~/workspace/aws-s3-storage</p>
<p>aws s3 sync ~/workspace/aws-s3-storage/ s3://bucket_name/folder –acl public-read</p>
<ul>
<li>s3 to local folder, local folder to s3가 가능하다. sync는 업데이트된 파일만 업로드한다.</li>
<li>–acl public-read는 누구나 파일을 읽을 권한을 주는 것을 말한다.</li>
</ul>
</blockquote>
<p>aws-cli 짱!</p>

감사합니다.

<hr />
<h4>참고</h4>
<p>https://github.com/blackmaz/saltstack_test/wiki/AWS-S3-%ED%8C%8C%EC%9D%BC%EC%84%9C%EB%B2%84%EB%A1%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0</p>
<p>https://ngee.tistory.com/1137</p>


- - -

This page is synchronized from the post: ['AWS S3를 aws-cli로 관리하자'](https://steempeak.com/@jacobyu/1920-aws-cli-for-aws-s3)
