# ELKProject

## Project Settings
- jdk
- spring boot
- elastic search : 8.15.1
- logstach : 8.15.1
- kibana : 8.15.1
  

## Code convention

- 명사는 주어(클래스), 목적어(매개변수,변수)로 사용됨을 인식하고 변수명을 정해자.

- 동사 원형을 사용하는 경우는 함수의 메서드를 첫 단어로 사용한다.(동사와 명사가 하나에 복합어로 사용될 때는 동사가 앞에 나옵니다.)

- 과겨형은 없다.

- 과거분사는 형용사라고 생각하고 사용하자, 수동의 의미 , boolean 변수에 사용됩니다.

- 단수와 복수를 구별해서 사용하자

- 일반적으로 리스트는 복수, 리스트의 아이템은 단수로 사용한다. 리스트는 가급적 복수형으로 작성합니다.

- 중복을 제거하자

- 문장을 읽을 때 한 문장안에 단어가 반복되면 이질감을 느끼게된다. 클래스 내부함수는 클래스에 사용된 단어는 가급적 빼고 작성합니다.


## git commit rule

- 깃 커밋 메세지
  타입 : 주제(제목) 
  바디

- 깃모지 활용
  https://gitmoji.dev/
  ```
  gitmoji -c
  ```


## git flow
- master : 최종 브랜치 
- develop : pr 완료 후 갱신
- feature : 단위 기능 개발
- hotfix : 크리티컬한 버그 긴급 수정

## branch naming
- feature-이슈넘버-본인이름(닉네임)

