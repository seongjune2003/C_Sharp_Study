# C-Study

일단 Csharp 언어랑 객체지향, 컴퓨터구조부터 제대로 기반다지고 가자. 


CSharp, 컴퓨터 구조 -> 유니티 기능 -> 디자인 패턴 ->  알고리즘(정렬, 탐색) + 자료구조(배열,리스트,스택,큐,트리) -> 셰이더 기초, UI, 파일 입출력 -> 서버연동



대략적인 준비 커리큘럼.
1. C# / 유니티
2. 자료구조 / 알고리즘
3. 유니티 포폴 만들기 - 모바일 출시까지
4. CS (운영체제 / DB / 네트워크 / 디자인패턴)  (깊게 공부 안하고 면접용으로)
5. 입사지원 / 면접준비







---------------------------------------------------------------------------------------------------------------------------------








# 앞으로 게임개발을 위해 공부해나가야 할 것들.

1.컴퓨터 구조

1)컴퓨터 메모리에 대한 이해 (스택,힙) -> 최적화로 이어짐

2)이진법, 비트연산 

3)컴퓨터가 밑바닥부터 어떻게 돌고 있는지 개념적으로라도 알면 좋음.

<br/>


2.알고리즘

정렬,탐색

<br/>


3.자료구조 - 보통 개념만 알아도 실제 자료구조구현보다는 사용하는 언어에서 제공하는걸 쓰거나 커스텀함.

배열,리스트,스택,큐,트리

<br/>


3.수학  - 아래 정도면 크게 문제없는듯.

->대학교 1~2학년 수준 수학

->선형대수(벡터,행렬,공간) 

<br/>


4.자체엔진 제작 - 게임학원 수강( 좀 옛날에 다녀서 요즘은 자체엔진 제작 안하는데도 많음)

->C++기반으로 윈도우,다이렉트x로 프레임워크 제작, 기획,아트와 협업해서 인디게임제작.

<br/>


5.유니티 (언리얼,유니티를 보통 취사 선택하는데 고사양 그래픽이 목적이 아니라면 유니티가 선호됨)

->유니티 엔진에 대한 이해 (강의영상 찾아보면 많음)

#개인적으로 생각하는 유니티의 중요 공부사항

->엔진업데이트 순서(awake->enable->uddate 정도만 일단 파악해도 큰도움)

->GameObject.Transform,Monobehavior 이 3개가 유니티의 핵심키워드.

->시스템 함수(Update,Start등)에 대한 사용법 

->애니메이션 - 메카님은 보통 잘안쓰고 레거시 애니메이션만 주로 씀.

->3d모델포팅, 2d이미지 포팅 등

->외부 라이브러리 적용

->에디터 프로그래밍 - 유니티를 내마음대로 커스텀해서 메뉴도 넣고.

->자잘한 기능에 대한 정보는  엄청 많으므로 쉽게 찾음.

<br/>


6.C# (유니티로 주로 제작하는 경우 c#에 대한 깊은 이해는 개발을 도와줌)

->기본 문법(변수,제어문 등)

->object로 이루어진 c#의 핵심구조에 대한 이해

->제네릭에 대한 깊은 이해

->델리게이트,무명메소드,람다에 대한 이해

->강력한 리플렉션 기능 이해

->c#의 가장 좋아하는 기능 class확장기능(extention) 

->partial클래스 -> 사용 잘하면 유연한 프로그래밍

->네임스페이스 효과적인 사용.

<br/>


7.디자인패턴(개인적으로 자주 썼던것만 - 패턴은 정답이 없고 개인취향을 매우 탐)

싱글톤,프록시,팩토리,옵저버 등등

<br/>


8.그래픽스에 대한 이해

->월드,뷰,프로젝션에 대한 기본개념 (로컬->월드->카메라->뷰)

->드로우콜 최적화

->메모리 최적화(거의 텍스쳐 관련 - 텍스쳐 압축, 아틀라싱등)

<br/>


9.셰이더

셰이더의 기초 이해

유니티를 사용했으므로 유니티의 서피스쉐이더,버텍스프래그먼트쉐이더 차이 및 사용법

셰이더코드는 밑바닥부터 만들기 보다는 에셋스토어 활용도 추천 - 단 코드를 분석하고 커스텀할줄 알아야 제대로 쓸수있음

<br/>


10.UI

유니티를 사용하고 있으므로 Ngui(예전부터 있던 유명한 모듈) vs Ugui(자체 내장) 인데 현업도 대부분 신작은 Ugui로 쓰고있음

스프라이트 관리 -> 아틀라스 혹은 스프라이터 팩커 

버튼,스크롤,이미지,캔버스,캔버스그룹, 레이캐스팅, 뎁스조정

GrayScale( 회색처리)

UI 매니징 기법 (많은 ui를 관리하는방법.  모바일게임의 경우 stack개념으로 해서 백버튼 누를시 하나씩 처리 하는등)

UI이펙트 - 보통 tween관련 모듈을 사용함 -> TweenPostion,TweenScale,TweenAlpha 3개면 대부분의 ui이펙트 처리 가능

UI와 파티클을 동시에 사용하는 경우 특수한 뎁스조정이 필요 -> 보통 파티클에 뎁스조정 스크립트 사용

<br/>




11.파일 입출력

json,엑셀,xml 파서제작(데이터 저장및 로드)

유니티등 엔진을 사용하더라도 데이터 저장구조는 보통 따로 만듬

나는 엑셀전용파서를 만들어서 씀. 엑셀에 가령 캐릭터정보를 넣어놓고 그걸 읽어서 실제 데이터로 사용.

<br/>


12.서버연동

->네이티브(안드로이드 자바, 애플 스위프트) 코드 - 겉만 슬쩍

-->구글및 애플 로그인모듈,결제모듈,푸시메시지,광고붙이기

->서버 프로그래머와 협업을 위한 기본지식 - 핑캐치,딜레이 전송, 서버프로그래머에 맞춰서 버퍼구조(나는 주로 구글 프로토버퍼씀)

->db에 대한 기본적인 이해 (할줄 알면 좋은건데 그정도까진 힘들고 그냥 어떻게 테이블 설계를 해야 db에 부담이 덜가는지 고민)

<br/>


13.Google에 검색하는 스킬 (가장 중요하다)

->첨엔 궁금한거 한글로 검색하다가 노답이라는걸 깨달음

-> 영문으로 필요한 내용을 검색하는게 좋음. 우리가 궁금한건 누군가도 궁금했음 대부분 다 해답이 있음.

->에러메시지가 뜨면 그냥 복사해서 같다가 붙이면 왠만한건 다 고칠수있음.

->물론 정확히 파악하고 검색어를 잘 선정하면 양질의 정보를 많이 얻을수있음














