# JSP 기본 다지기
**JSP**는 HTML 코드에 java코드를 넣어 동적웹페이지를 생성하는 웹어플리케이션 도구입니다. JSP의 기본을 다지기 위해 여러가지 기능들을 살펴보았습니다.

# JSP 코드 표기법

|**코드**|**기능**|
|:---:|:---:|
|<%@   %>|지시문으로, jsp 페이지 속성 지정합니다.|
|<%   %>|스크립트릿으로, 자바 코드 블록, 변수 선언만 가능합니다.|
|<%!   %>|선언문으로, 전역변수 혹은 메소드를 선언합니다.|  
|<%=   %>|표현식으로, 웹브라우저에 직저 결과 값을 출력합니다.|
|<%--   -->|여러줄을 주석으로 처리할때 사용합니다.|
|<jsp:action>   </jsp:action>|액션태그로, 다른 페이지를 포함 혹은 이동을 명령할때 사용합니다.|
|**java api 패키지**|**기능**|
|java.lang|자바 프로그래밍 기본 기능을 제공합니다.(생략이 가능)|
|java.io|입출력에 관한 기능을 제공합니다.|
|java.sql|sql 관련 기능을 제공합니다.|
|java.time|날짜와 관련된 기능을 제공합니다.|



# 예시 첫번째


> **코드**

<img width="473" alt="image" src="https://user-images.githubusercontent.com/102296551/170400292-63ef2985-7b7d-4638-b734-ebb96a8aa964.png">

```
전역변수와 지역변수의 적용범위르 알아보기 위해 작성한 코드입니다.
```

# 예시 두번째


> **코드**

<img width="454" alt="image" src="https://user-images.githubusercontent.com/102296551/170401009-7229b4dd-5fe3-49f7-8118-ea15366fb006.png">

```
변수와 연산자를 이용하여 두 수를 비교해 덧세 혹은 뺄셈의 결과를 화면의 출력하는 과정을 자세히 알아보기 위해 작성한 코드입니다.
```

# 예시 세번째


> **코드**

<img width="470" alt="image" src="https://user-images.githubusercontent.com/102296551/170401134-9607e0ce-b6ec-4102-9aac-cf5d6012cd80.png">

```
1차원 배열 두개를 선언하고 출력합니다. 변수 sum과 avg를 선언하고 배열과 같이 출력하는 코드를 작성하였습니다.
```

# 예시 3-1번째


> **코드**

<img width="573" alt="image" src="https://user-images.githubusercontent.com/102296551/170401247-3a0a3318-1082-4983-88bc-4971a76eb876.png">

```
1차원 배열을 선언 및 초기화 후 for문을 사용, 학생의 과목명과 점수, 평균과 총점을 화면에 출력하는 과정을 작성한 코드입니다.
```


# 예시 4번째


> **코드**

<img width="466" alt="image" src="https://user-images.githubusercontent.com/102296551/170401463-82984bb1-0809-4a39-a710-513511c102ce.png">

```
2차원 배열을 선언하고, 변수 sum1,2와 avg1,2를 선언하였습니다. sum에는 총점을 계산하여 넣어주고, avg는 총점/3의 값을 넣어주어서 화면에 출력하는 코드를 작성하였습니다.

# 예시 4-1번째


> **코드**

<img width="685" alt="image" src="https://user-images.githubusercontent.com/102296551/170401590-44caa35a-e518-4da0-9689-c4dab063cde8.png">

```
2차원 배열을 선언하고, 이중 for문을 사용하여 처음 for문에서는 모든 행을 탐색하고, 두번째 for문에서는 모든 칸을 탐색합니다. 해당줄의 모든 칸에 들어있는 값을 누적, 더합니다.
스크립트 릿에서 for문을 활용하여 출력하는 코드르 작성해보았습니다. 
```

# 예시 5번째

> **코드**

<img width="713" alt="image" src="https://user-images.githubusercontent.com/102296551/170401817-d3c4c34a-240e-43d2-a3b4-81fe5fbb8075.png">
<img width="539" alt="image" src="https://user-images.githubusercontent.com/102296551/170401845-237a4865-d2c2-4647-af16-c2069a3b8dc2.png">

```
계좌번호와 잔액 정보를 가진 Account클래스를 만들고, 계좌번호를 매개변수로 받아들이는 생성자도 만듭니다. 계좌가 있으며 예금,출금을 할 수 있느 프로세스 메소드를 선언합니다. (deposit, payment)
생성된 클래스와 변수를 바탕으로 변수 ...don을 선언합니다. 이 변수들을 사용하여 예금 프로세스와 출금 프로세스를 작성하고 출금 프로세스에서는 if문으로 출금액과 잔액을 비교해 잔액이 출금액보다 적을 경ㅇ 잔액 부족을 띄워주는 코드를 작성해보았습니다.
```

# 예시 6번째


> **코드**

<img width="469" alt="image" src="https://user-images.githubusercontent.com/102296551/170401889-5ef7835d-94b2-4636-aff0-f289e1b8ddc6.png">

```
String id, pass, log, logpw, msg를 생성, if문을 활용하여 id와 log가 같고, pass와 logpw도 같으면 msg에서 ok를 띄어주고, 아니며 no를 띄워주는 코드르 작성해보았습니다.
```





