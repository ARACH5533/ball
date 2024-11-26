# 자유 낙하 공 시물레이션 V1.0
간단히 프로그래밍된 자유 낙하 공 시물레이션

오픈 소스로 누구나 코드 수정이 가능
***
**배포** : [사이트](http://blue-ball-simulation.kro.kr)

코드 내에서 아래 부분을 편집해서 여러 상황 구현이 가능함
```javascript
const ball = {
        x: 400,
        y: 300,
        radius: 20,
        velocityY: -10,
        velocityX: 10,
        color: 'blue'
    };
```
`ball.x` 공의 위치 x

`ball.y` 공의 위치 y

`ball.radius` 공의 반지름

`ball.velocityY` 공의 수직(y)방향 속도

`ball.velocityX` 공의 연직(x)방향 속도

`ball.color` 공의 색상

배포가 어렵다면 사이트에서 개발자 도구로 스크립트를 직접 입력할 수 있음.
# 예시

## 값 수정

`ball.x=10;` 공의 위치x를 10으로 변경

`ball.y=500;` 공의 위치y를 500으로 변경

`ball.radius=10;` 공의 반지름을 10으로 변경

`ball.velocityY=-10;` 공의 수직(y)방향 속도를 -10으로 변경

`ball.velocityX=10;` 공의 연직(x)방향 속도를 10으로 변경

`ball.color='red';` 공의 색상

기본값으로 초기화

```javascript
ball.x=400;
ball.y=300;
ball.radius=20;
ball.velocityY=-10;
ball.velocityX=10;
ball.color='blue';
```
***
# 업데이트될 사항

## 캔버스 크기 조정

캔버스 크기를 사이트에서 조정 가능함

## 시뮬레이션 속도 조정

시뮬레이션 속도를 스크립트 없이 조정 가능함

## 장애물 랜더링

장애물을 스크립트 없이 추가할 수 있음

## 객채 속성 수정 기능

스크립트 없이 객채 속성을 수정하고 추가할 수 있음



