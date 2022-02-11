# java-blackjack

# 📌 연료 주입
## 기능 요구 사항

우리 회사는 렌터카를 운영하고 있다. 

현재 보유하고 있는 차량은 Sonata 2대, Avante 1대, K5 2대로 총 5대의 차량을 보유하고 있다.

고객이 인터넷으로부터 예약할 때 여행할 목적지의 대략적인 이동거리를 입력 받는다. 

이 이동거리를 활용해 차량 별로 필요한 연료를 주입한다. 차량 별로 주입해야 할 연료량을 확인할 수 있는 보고서를 생성해야 한다.

```
* Sonata : 10km/리터
* Avante : 15km/리터
* K5 : 13km/리터
```

## 프로그래밍 요구 사항

- 상속과 추상 메서드를 활용한다.
- 위 요구사항을 `if/else` 절을 쓰지 않고 구현해야 한다.

## 기능 구현 사항

- [x] `Car` 클래스 추상화 (`Car`)
  - [x] 주입해야할 연료량 계산 (`Car.getChargeQuantity()`)
- [x] 파생 클래스 구현

  - [x] `Sonata` 클래스 구현 (`Sonata`)
    - [x] 리터당 이동 거리 계산 (`Sonata.getDistancePerLiter()`)
    - [x] 여행하려는 거리 반환 (`Sonata.getTripDistance()`)
    - [x] 차종의 이름 반환 (`Sonata.getName()`)
    
  - [x] `Avante` 클래스 구현 (`Avante`)
    - [x] 리터당 이동 거리 계산 (`Avante.getDistancePerLiter()`)
    - [x] 여행하려는 거리 반환 (`Avante.getTripDistance()`)
    - [x] 차종의 이름 반환 (`Avante.getName()`)
    
  - [x] `K5` 클래스 구현 (`K5`)
    - [x] 리터당 이동 거리 계산 (`K5.getDistancePerLiter()`)
    - [x] 여행하려는 거리 반환 (`K5.getTripDistance()`)
    - [x] 차종의 이름 반환 (`K5.getName()`)
