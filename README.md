https://umustmw.github.io./index.html#/

Link 는 ReactRouterDom 버전 문제로 작동하지 않음
: 메인 페이지로 돌아갈 때마다 다시 로딩하는 현상(Link 정상 연결시 바로 불러옴)

루트에서 메인 페이지가 나타나지 않기 때문에 추후 업데이트시 리다이렉트해주는 것이 필요함
(업데이트보다는 다시 만드는 것이 좋아보임: 함수형 컴포넌트, useState, ReactRouterDom v6 사용) 

// 레퍼런스가 ReactRouterDom 5.2 ver 이고, 클래스형 컴포넌트를 쓰다보니 현재 문법과 다른 부분이 많음
