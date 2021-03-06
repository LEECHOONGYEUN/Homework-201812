

# 개발게임 시스템 및 참고지식

## 1.클라이언트
### 1-1 운영체제
#### 안드로이드

시장성 우수함 : 시장 점유율이 80%가 넘을정도로 가장 많은 사용자 보유  
신속한일처리가능: 어플리케이션 등록후 배포도 iOS에 비해서 빠르다. 

**(+참고지식 :버전 별 각종 재밌는 네이밍)**

2.0 진저브레드(생강빵)

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/gin.png)

3.0 허니콤 

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/honey.jpg)

4.0 아이스크림 샌드위치 - 2011년 10월 19일 정식공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/icecream.jpg)

4.1~4.3 젤리빈  - 2012년 6월 28일 정식공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/jelly.jpg)

4.4 킷캣 - 2013년 10월 31일 정식공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/kitkat.png)

5.0 롤리팝 -  2014년 10월 16일 정식공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/loli.png)

6.0 마시멜로 - 2015년 10월 6일 정식공개!

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/masi.jpg)

7.0 누가 - 2016년 8월 23일 정식공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/noga.jpg)

8.0 오레오 - 2017년 8월 22일 정식 공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/oreo.png)

9.0 파이 - 2018년 8월 6일 정식 공개

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/pie.jpg)



### **1-2 개발**

####  유니티 엔진(주 사용언어 C#)

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/unity.jpg)

2005년 6월 8일 처음 발표.  2018년 5월 말 한글패치 제공, 공식 네이버 카페 있음.

**장점**  
1.GUI가 아주 직관적, 툴 사용이 서툰 사람도 편하게 사용하기 좋다.  
2.버튼 몇 번만 누르면 다양한 플랫폼으로 빌드가 가능( 물론 별도 최적화 작업은 필요)  
3.인디 게임개발자,초보개발자들에게 유리한 이점인 애셋스토어가 존재한다.  
 각종 리소스,스크립트,플러그인 구매가능  
4.라이센스 비용이 매우 저렴하다, 매출이 나오지 않을경우 라이센스 비용 무료  

**(+참고지식: 애셋 스토어)**  
 디자인,모델링,플러그인등을 서로 유무료로 배포할 수 있는 일종의 커뮤니티장터이다.  
코딩에 익숙하지 않은 디자이너나 리소스 제작이 힘든 개발자들이 애셋 스토어에서 구매하거나 무료로 다운받아 사용이가능하다.  

#### 주 사용언어 C#

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/c%23mark.png)

마이크로소프트에서 개발한 객체 지향 프로그래밍 언어  
닷넷 프레임워크의 한부분  
C++과 자바와 비슷한 문법을 가지고있음.  

**C#과 C++ 의 주 차이점**  
C#에는 전역 변수 및 전역함수가 존재 하지 않으며, 클래스 안에 선언되어야함  
C#의 bool은 오직 true와 false 논리값만 가질수 있음.  
C#에서는 static 키워드를 오직 한 번만 초기화를 수행한다는 의미로 이용 할 수 없다.  
C# 은 C++과 달리 직접적인 메모리 해제 명령이 없다.  
C#은 C++과 달리 부모 클래스를 하나만 사용 할 수 있다.  
C# 3.0부터는 임의의 자료형인 var타입을 지원한다. var의 실제 형식은 컴파일시 결정된다.  
C# 3.0부터는 기존의 SQL구문을 활용한 LINQ 식을 지원한다.  
C++에서는 함수 포인터를 이용하여 함수의 시작점을 전달 했지만, C#에서는 보다 유연한 델리게이트와 무명 메서드를 지원한다.  
C#에서는 데이터 은닉과 보안성 향상을 위해 프렌드 함수를 지원하지 않는다.  
C#에서는 인라인 함수가 지원되지 않으며, 전역 함수나 전역 변수도 허용되지 않는다.  
C#은 C/C++과 달리 전처리기의 사용이 제한적이다.  
C++에서 특정 컴파일러 제작사마다 조금씩 다른 방식으로 구현되었던 런타임 형식 정보는  
C#에서 리플렉션으로 확장하여 사용하는 것이 가능하다. 리플렉션은 자바 언어의 리플렉션과 같은 개념이다.  
C#은 C++보다 형 안전성에 대하여 더 관대하다. 이 말은 형 안정성을 보장할 수 없다는 것도 동시에 뜻한다.  

**(+참고지식:C#의 역사)**  

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/c%23man.jpg)

 C#은 마이크로소프트(MS)가 개발한 언어로 덴마크 소프트웨어 개발자 아네르스 하일스베르가 주도한 프로젝트. 처음에는 C#이라고 불리지 않고, 쿨(Cool)이라는 이름을 가졌었다.   
 Cool은 C-like Object Oriented Language의 약자를 따온 단어였다. 한글로 풀이하면 ‘C와 비슷한 객체지향언어’였다. 하지만 법률팀이 C#을 법적 트래이드 마크로 사용하기 힘들다는 조언을 제공하고 다른 이름을 찾기 시작했다.   
  C의 영향을 받은 언어라는 점을 강조하기 위해 ‘e-C, 세이프 C, C-스퀘어, C-큐브, C-프라임, C-스타, 세슘 등을 후보로 내놓았다고 한다.  C++처럼 뭔가 한단계 올라갔다는 단어를 고민하다가 ‘C++++’라는 단어도 추천했다. C#에서 샵에는 +표시가 4개 엮어 있고, 음악 용어에서도 C#은 C에서 1도 위 음을 뜻해 좋은 단어였다.   
  그리하여 MS는 이중적인 의미를 가진 C#으로 최종 이름을 결정했다  

**(+참고지식: JAVA의 역사)**  

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/javaman.jpg)

JAVA는 캐나다의 소프트웨어 개발자 제임스 고슬링이 만든 언어이다.  
자바는 원래 ‘오크’라고 불렸던 프로젝트다. 자바 창시자 제임스 고슬링의 사무실 밖에 오크 나무가 보여 이를 활용했다고 한다.  
 하지만 ‘오크 테크놀로지’라는 기업이 이미 존재했고, 법적인 문제를 피하기 위해 새로운 이름을 찾아야만 했다. 오크 프로젝트 팀 멤버들은 머리를 맞대고 다양한 이름을 후보로 추천했다.   
 ‘자바’도 그 중 하나였다. 자주 마시는 커피를 보고 자바라는 단어를 제안했다고 한다. 이 외에도 나머지에는 DNA, 실키, 레보루션너리, 임팩트같은 이름도 추천됐지만 최종적으로 자바가 선택됐다.   

**(+참고지식 : C++의 역사)**  

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/c%2B%2Bman.jpg)

C++은 덴마크의 컴퓨터 과학자 비야네 스트롭스트룹가 만든 프로젝트이다.  
C언어보다 객체 지향화한 언어라고 볼 수 있다. C++의 처음 이름은 ‘클래스를 가진 C(C with Classes)’였는데 향후 C++로 변경됐다.   
++은 C 언어에서 증가연산자이기 때문에 C++이란 말 자체가 C에 1을 더한 언어, 한가지 추가한 언어라는 해석이 가능하다.  

## 2.서버

### 2-1 아마존 클라우드 서버

![](https://github.com/LEECHOONGYEUN/-12-/blob/master/aws.png)

**확장이 용이함**  
 Amazon Web Services(AWS)는 라우드 서비스 플랫폼으로서, 컴퓨팅 능력, 데이터베이스 스토리지, 콘텐츠 전송 및 기타 기능을 제공하여 확장이 용이함  

**여러가지 지원**  
 개발부터 서버관리, 서비스지원까지 어느정도 지원을 받을수 있는 장점을 가졌다.  
AWS는 다양한 프로그래밍 언어를 위한 소프트웨어 개발 도구(SDK)를 제공하고 있음.  
 따라서, AWS Mobile SDK for Unity는 Unity를 통해서 모바일 게임 등을 개발할 때 직접 Unity 코드에서 SDK를 이용하여 AWS 에서 제공하는 서비스들을 편리하게 사용할 수 있습니다.  
커뮤니티를 통해서 솔루션을 받을수 있는것도 한가지 장점이다.  

**저렴한 가격**  
 사용의 규모에 따른 과금정책 및 스타트업을 위한 가격정책이 되어 있어 매우 저렴하게 서버를 운용할 수 있다.  

### 2-2 DATABASE 프레임워크 : Django 

### ![](https://github.com/LEECHOONGYEUN/-12-/blob/master/django.png)

Django는 2005년부터 시작된 Python의 오픈 소스 웹 프레임워크이다.  
Django는 풀 스택 프레임워크이다. Python 툴을 이용해 제작한다.  

장고는 웹 개발에서 번거로운 요소들을 새로 개발할 필요 없이 내장된 기능만을 이용해 빠른 개발을 할 수 있다는 장점이 있다.  

**구성**  
 장고는 파이썬으로 코딩한 모델을 관계형 데이터베이스로 구축해주는 모델(Model), HTTP 요청을 처리하는 웹 템플릿 시스템인 뷰(View), URL의 라우팅을 처리하는 URL 컨트롤러 (Controller) 로 구성된 MVC 디자인 패턴을 따른다.  

 하지만 전통적인 MVC 디자인 패턴에서 이야기하는 컨트롤러의 기능을 프레임워크를 자체에서 하기 때문에 모델(Model), 템플릿(Template), 뷰(View)로 분류해 MTV 프레임워크라고 보기도 한다  


**내장 애플리케이션**  
장고에는 아래와 같은 웹 개발에서 자주 쓰이는 애플리케이션이 'contrib' 패키지에 내장되어있다.  
  
확장가능한 사용자 인증 시스템  
동적 관리자 인터페이스  
RSS 또는 아톰을 위한 피드 생성  
사이트맵 생성  
사이트 간 요청 위조(CSRF)  
사이트 간 스크립팅(XSS)  
SQL 인젝션과 같은 해킹 시도에 대한 보안 대책  

**외부 패키지**  
 내장된 요소들 중에 원하는 것이 없으면 장고를 위해 개발된 외부 패키지를 이용할 수도 있다. 장고에서 사용할 수 있는 패키지들을 모아놓은 웹사이트 Django Packages 의 경우에는 3600개가 넘는 패키지가 등록되어있는 것을 알 수 있으며, 커뮤니티 멤버들의 꾸준한 기여 덕분에 많은 양질의 패키지들이 개발되고 있다. 이는 파이썬의 "건전지 포함"(Batteries Included) 의 정신에 입각한 것으로 볼 수도 있다.  

**(+참고지식: Django의 역사)**  
 Django는 2003~2004년에 로렌스 저널-월드(Lawrence Journal-World)라는 신문사의 인턴 웹 프로그래머였던 에이드리안 홀로바티(Adrian Holovaty)와 사이먼 윌리슨(Simon Willison)이 파이썬을 이용해 애플리케이션을 만들기 시작하면서 처음 개발되었다.   

 당시 로렌스 신문사의 웹사이트는 PHP 기반으로 쓰여졌었는데, 홀로바티와 윌리슨은 당시 PHP가 규모가 큰 웹사이트에 적합하지 않다고 생각했고 평소에 관심을 가지고 있던 파이썬으로 웹 개발을 하기로 결심했다. 하지만 규모가 큰 웹 개발에 적합한 파이썬 도구가 없다는 것을 깨닫고 새롭게 장고를 개발하게 된 것이다.  

 개발을 처음 할 때 사실 장고를 웹 프레임워크라고 생각한 적은 없었고, 그냥 CMS 를 개발하는 것이라고 생각했다고 한다. 개발자가 개발 당시의 기억들을 풀어놓은 글을 읽고 싶다면 여기(영어)에 사이먼 윌리슨 본인이 직접 쓴 글이 있다. (공동 개발자인 에이드리안도 따봉을 눌렀다!) 장고라는 이름은 홀로바티가 좋아하던 기타리스트 장고 라인하르트에서 따온 것이라고 한다.  

 또한 장고는 사실 오직 로렌스 웹사이트를 구동하기 위해 개발된 것이었지만, 홀로바티와 윌리슨이 로렌스의 오너 기업인 더 월드 컴퍼니(The World Company)를 설득하여 오픈 소스로 2005년 7월에 BSD 라이선스로 공개하게 되었다. 윌리슨은 더 월드 컴퍼니도 다른 오픈 소스 프로젝트을 많이 사용했었기 때문에 쉽게 설득할 수 있었다고 얘기했다.  
