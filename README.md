<br>

## 💬 QnA 서비스
<br>

### 💯 QnA 서비스
- 질문과 답변을 달 수 있다.
- 질문자는 자신의 질문을 삭제할 수 있다. (단, 답변이 달렸으면 삭제할 수 없다)

<br>
<br>

### 💻 프로젝트의 목표와 성과
#### 목표
- JPA로 실제 도메인 모델을 어떻게 구성하고 객체와 테이블을 어떻게 매핑해야 하는지 알아본다.
- 데이터 중심 개발이 아닌 객체 지향 설계에 맞게 각각의 객체가 맡은 역할과 책임이 있고 관련 있는 객체끼리 참조하도록 설계한다.

#### 성과
- Answer, Question, User, DeleteHistory 엔티티를 매핑하며 ORM 기반의 도메인 모델을 구성하였다. <br>
  [↳ JPA에 관한 블로그 포스팅 시리즈 (@yyy96)](https://velog.io/@yyy96/series/JPA)
  
- 질문 삭제 기능을 Service Layer에서 Question 도메인으로 이동하며 도메인 주도 개발의 중요성에 대해 깨달을 수 있었다. <br>
  [↳ 도메인 주도 설계에 관한 블로그 포스팅 (@yyy96)](https://velog.io/@yyy96/비즈니스로직)
  
- 팀원과의 페어프로그래밍을 통해 영속성 컨텍스트에 대한 학습을 심층적으로 진행할 수 있었다. <br>
  ↳ `ConstraintViolationException` 오류의 원인을 살펴보며 연관관계를 맺어주는 엔티티의 생명주기에 대해 다시 한번 숙지하였다. <br>
  [↳ `ConstraintViolationException` 오류에 관한 블로그 포스팅 시리즈 (@yyy96)](https://velog.io/@yyy96/JPA-ConstraintViolationException)


<br>
<br>

### [📝 코드 리뷰 및 리팩터링 과정](https://github.com/next-step/jwp-qna/pulls?q=is%3Apr+is%3Aclosed+author%3Ayyy96)
![image](https://user-images.githubusercontent.com/65826145/196315593-12b42b38-c09e-4607-a962-78b3c1f14130.png)
