MSA 프로젝트, 커피 주문 시스템 ☕️
================

> 2020년, 팀 프로젝트 서비스의 기능들을 구현하며 하나의 기능에 장애가 났을 때 전체 서비스가 먹통이 되는 점, <br />
> 그리고 이에 따라 서비스의 개선이 어렵고 수정 시 장애의 영향도 파악이 어렵다는 불편함을 느꼈습니다. <br />
> 이러한 문제를 해결하고, 또 추후 서비스가 커졌을 때 부분적인 scale-out이 수월한 'MSA 아키텍쳐'를 도입해야겠다고 생각했습니다. 그래서 자주 이용하던 스타벅스의 사이렌 오더(커피 주문 시스템)을 MSA 구조로 구현하는 MSA-COFFEE-ORDER 프로젝트를 진행하였습니다. <br />
<br />

## Why MSA?
+ 부분 장애가 전체 서비스로 전파된다.
+ 부분적인 서비스의 scale-out이 어렵다.
+ 서비스의 개선이 어렵고, 수정 시 장애의 영향도 파악이 어렵다. 
+ 서비스의 전체 코드가 하나의 프로젝트로 구성되어 배포가 오래걸린다.
<br />

## MSA 프로젝트의 목표
+ 하나의 서비스 장애가 다른 서비스로 전파되지 않는다.
+ 코드 복잡성 및 의존성을 제거해 영향도 파악을 용이하게 한다.
+ 추후 서비스의 고 가용성과 확장성을 확보한다.

<br />
<hr />

## 사용 기술
+ Kubernetes
+ Docker
<br />
<hr />

## 프로젝트 전체 구성
![vnilla_ERD](https://user-images.githubusercontent.com/68539040/173878465-f58e8db6-4239-4142-94ef-0bf088dca791.png)
<img width="762" alt="msa00" src="https://user-images.githubusercontent.com/68539040/173878465-f58e8db6-4239-4142-94ef-0bf088dca791.png">
