# 이펙트 연습
슈리켄으로 만드는 유니티 게임 이펙트 입문 책을 읽고 실습 및 정리

## 게임에서의 이펙트란 ?
### 게임 이펙트의 종류
* 이펙트는 캐릭터 이외의 움직이는 모든 "효과"를 의미한다.
* RPG 게임에서 사용되는 공격, 히트, 회복, 마법 사용 이펙트 등 => 플레이어에게 지금 무언가가 일어나고 있다 등의 상황을 효과적으로 전달
* 게임 내부의 환경을 나타내는 것도 있다 => 비, 눈, 번개, 구름, 안개와 같은 날씨/ 나비처럼 화면에서 움직이는 대부분의 것들이 이펙트이다.
### 게임 이펙트 표현의 폭
* 크게 두 종류로 나눌 수 있다.
* 현실 세계에 있는 현상
    * 날씨 또는 흩날리는 벚꽃 등
* 상상 속의 세계에만 있는 현상
    * 회복, 공격 마법 이펙트
### 이펙트의 외형
* 실루엣, 디테일, 색 3가지 요소가 멋진 이펙트를 만들 때 중요하다.
#### 실루엣
* 이펙트가 어떠한 형태를 하고 있고, 어떠한 움직임을 하는지를 나타내는 것
* 예를 들어 화염에서 타오르는 불꽃, 빛, 연기의 움직임 등
#### 디테일 
* 표현하고 싶은 이펙트를 더 현실적으로 보이게 만들기 위한 세부적인 사항 
* 예로 화염에서 튀어 오르는 불똥
#### 색
* 글자 그대로 대상의 색
### 이펙트의 움직임
* 발생 -> 연출 -> 소멸
#### 발생
* 이펙트가 출현하는 시점을 의미
* 표현하고 싶은 이펙트가 조금씩 나타나거나, 순간적으로 나타나거나, 불타오르면서 나타나거나, 확대되면서 나오는 등의 다양한 표현 방법이 있다.
#### 연출
* 이펙트의 효과를 표현하는 시간
#### 소멸
* 이펙트가 사라지는 것을 의미
* 순간적으로 사라지거나, 긴 시간을 두고 사라지거나, 축소되면서 사라지거나 하는 것처럼 다양한 표현 방법이 있다.

## 파티클 시스템이란?
* 유니티에는 파티클 시스템이라는 표준 파티클 시스템 컴포넌트가 있다.
* 이를 통해 불꽃, 불, 바람, 번개, 마법 등의 다양한 이펙트를 구현할수 있다.
* 주요 설정 항목[https://www.notion.so/Particle-System-Object-1a27e0671aa94d21826da6bac82b04e0?pvs=4]