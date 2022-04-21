# 심화 CSS | 실무사용 04
## CSS perspective
  - 화면을 바라보는 거리가 perspective임. 그래서 거리가 짧아질수록 변화가 더 크게보임. 왜냐? 가까이서 보게 되는거니까.
    - 부모요소에 perspective 넣기
    - transform-style:preserve-3d; 속성을 넣어줘야 우리가 평상시 이해하는 3d 형상의 모습이 완성됌.

## 우리가 기본적으로 파악하고 있어야 하는 해상도
  - QHD : 960 * 540
  - HD : 1280 * 720
  - HD+ : 1600 * 900
  - FHD : 1920 * 1080
  - QHD(WQHD) : 2560 * 1440
- 다만 너무 걱정하지 말것. 신입에게 해상도 작업을 맡기진 않음
## 미디어쿼리
  - 맥스가 붙으면 0부터 백스까지
  - max, min 차이 구분해보기 (맥스는 ~까지 min은 부터)

## 논리연산자
      true 참 1
      false 거짓 0
      
      and 논리 곱
      or 논리 합
      not 부정
      
      true and false = 0 ⇒ false
      false and true = 0 ⇒ false
      false and false = 0 ⇒ false
      true and true = 1 ⇒ true
      
      not true ⇒ false
      not false ⇒ true
   - 이후 자바스크립트에서 유용하게 사용 될 개념. 잘 파악해두고 있자. 

