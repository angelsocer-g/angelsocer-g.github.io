---
title: "Python?"
last_modified_at: 2021-09-11
toc: true
toc_sticky: true
categories:
  - python
tags:
  - python
  - python3
  - get started
---

# #Python
## 2021.09.11
> [파이썬? Python?](https://www.python.org/)  

대중적(내 주변 기준)으로 가장 인지도가 높은 프로그래밍 언어다.  
👉 대중적이다 = 많은 사람들이 선택했다 = 괜찮은 선택일 확율이 높다.

### TMI
> 흔한 일상 Episode.
- `어떤 기획자`: 파이썬 할줄아세요?
- `어떤 개발자`: 아뇨, 해본적은 있져. 뭐 책이나 회사교육이나.. 왜요?
- `어떤 기획자`: 아 코딩 공부 해보려고 하는데, 도움 받을 수 있을까해서요.
- `어떤 개발자`: (파이썬이 대중적이구나!!) 

### TMI 2
> 나한테 Python 이란?
- 라이브러리 생태계가 잘 구축되있다. 
  - Google에 Keyword만 잘 넣으면 당장 사용가능한 라이브러리가 대부분 있다.
- 즉, 내가 필요한 기능을 빨리 구현해서 사용할때 좋다.
- 구글 좋아요, 파이썬 좋아요. 구독하기 알림설정까지 👍 .. 응?

## Overview
> 파이썬을 설치한다 👉 가상환경 구성 해본다 👉 끝 

## How to start?
> 뭐든 시작이 어렵다. 시작만 하면 끝내는건 쉽다. 
 
⭐️ **작성환경**   
`-` MacBook Air (M1, 2020) Apple M1  
`-` OS : MacOS Big Sur 버전 11.3
{: .notice--info}

### Need to know
- 작성환경을 위에 적은건 내용이 Mac OS 기준이기 때문입니다.
- python은 2개다?
  - ~~python2~~ - End Of Service, 2020.01
  - **python3** - python = python3  👉 우린 EOS 안쳐준다.
- [pip](https://ko.wikipedia.org/wiki/Pip_(%ED%8C%A8%ED%82%A4%EC%A7%80_%EA%B4%80%EB%A6%AC%EC%9E%90))
  - python library 설치하는 CLI
  - 우리는 python3 쓸거니까 **pip3**

### 환경구성
- python3 설치 (Homebrew)
  ```shell
  # 설치
  brew install python3
  # 예의상 버전확인
  python3 --version
  # workspace 생성
  mkdir -p workspace-python/demo
  ```
  
- 가상환경 구성
  
  ⭐️ **Please Note**  
  나는 주로 라이브러리를 가져다 쓰는 용도로 사용하기 때문에  
  그때그때 [가상환경](https://docs.python.org/ko/3/tutorial/venv.html){:target="_blank"}
  으로 구성한다.
  {: .notice--info}  

  ```shell
  # 가상환경 만들기 👉 가상환경이름 = `demo-env`
  python3 -m venv demo-env
  # 가상환경 활성화
  source demo-env/bin/activate
  # 가상환경에 library 설치 👉 demo니까 아무거나 `selenium` 설치 
  pip3 install selenium
  # 가상환경 종료
  deactivate
  ```

## 🛬 마무리
> 어떤 프로그래밍 언어든 각각의 철학이 있고 멋지다.  
> 현재 나에게 파이썬이란     
> `무언가 빨리 가져다 가볍게 만들어 쓰기 좋은 프로그래밍 언어` 정도 인 것 같다.  
> 파이썬 사랑해요 💚

## References
- [docs.python.org - 가상환경 및 패키지](https://docs.python.org/ko/3/tutorial/venv.html){:target="_blank"}
- [가상환경 잘 정리된 blog](https://velog.io/@kyle13/Python-%EA%B0%80%EC%83%81%ED%99%98%EA%B2%BD-venv){:target="_blank"}