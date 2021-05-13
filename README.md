#### 작업예정 : jQuery 제이쿼리 JSON 데이터 파싱
- 외부 data.js 파일에서 json 데이터를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공하는(RestAPI서버) json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
- RestAPI서버주소 : https://coroname.me/getdata

#### 20210513(목) 작업내역
- 제이쿼리 코어 다운 받기 : min버전(압축-속도UP), 일반버전(개발-속도normal)
- jQuery 미처리 작업은 다음주하고,
- 오늘부터는 모바일 메인 페이지 1개 만들어서 과제물로 제출 ->      스프링에서 프로그램 입히는 소스로 사용하게 됩니다.
- 애니데스크(독일산): 팀뷰어(독일산)
- html5.html, css.html, js.html 여기까지
- jQuery 기본구조만 실습했습니다.

#### 20210512(수) 작업내역
- git clone으로 프로젝트를 가져온 경우 아래 내용을 추가해주셔야합니다.
- 터미널에서 아래 2가지 실행
- git config --list 확인에서 user.name, user.email 없으면 아래추가
- 터미널에서 아래 2가지 실행
- git config --local user.name 영문이름
- git config --local user.email 영문이메일
- 프로젝트를 1명 제작하는 경우 없기 때문에, 2명 이상 일 때 소스 수정한 사람 확인용 정보입니다.


#### 20210511(화) 작업내역
- 로렘 입숨 한글URL : http://guny.kr/stuff/klorem/#/dl-html
- 로렘 입숨 영어URL : https://loremipsum.io/generator/
- URL경로(path): /루트, /test/html5.html
- html5의 레이아웃 구조 제작합니다.
- 서버(응답하는프로그램=response) = 아파치서버,톰캣서버
- 클라이언트(요청하는프로그램=request) = 웹브라우저
- HTML은 마크업이 태그로 구성됩니다.<의미있는문자>...</의미있는문자>
- http://127.0.0.1:80[8080,9000,5500,6500]
- PC의 네트워크 내부주소(공통): 127.0.0.1 == localhost
- 고유주소: yahoo.com(도메인) == 74.6.143.25(IP주소) == 주민번호
- IP주소버전: IPv4, IPv6
- HTML도 버전 : HTML5, HTML4.01(old)

#### 20210510(월) 작업내역
- git에서 'user.name' 및 'user.email'을 구성하라고 떠요!
- 업로드절차 :1. 커밋(commit) 2. 푸시(push)
- 다운로드절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 상황
- 레포지토리(저장소) 초기화: git init
- 개발PC(html) 과 깃 저장소와 연결시킵니다.
- 포트의 역할이 트렌드로 많이 사용됩니다.
- 포트(port): 포트번호로 서비스를 만드는것이 트렌드
- 이전에는 80포트에 모든 서비스 묶어놓았습니다.
- 모든서비스를 개별로 분리하는 트렌트가 있습니다.: 
마이크로서비스라고 합니다. == RestAPI로 구현이 됩니다.
- 도메인(http://naver.com:1451241/네이버 인증서비스 개발)
- 외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가
사용
- html : Hyter Text MarkUp language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어