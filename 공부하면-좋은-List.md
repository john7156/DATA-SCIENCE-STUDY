## 질문 잘 하는 법
- 개발을 공부하다 보면 질문을 해야되는 경우가 있습니다
- 올바른 답변을 얻기 위해선 질문을 잘 해야 합니다
- 관련 주제로 발표하신 코드스쿼드 정호영님 [동기부여 - 질문 잘 하는 법](https://www.youtube.com/watch?v=L2p1mdpxD5w)을 참고해주세요!


## Git
- Git은 가장 많이 사용하는 버전 관리 도구
	- 버전 관리 도구 : 개발된 코드의 이력(새로 무언가가 추가되거나 삭제되는 내용) 관리를 위한 도구
- 개발된 코드의 History를 관리
- 협업을 위한 코드 공유 및 Review 수행을 위해 사용합니다
- History를 관리하기 때문에 문제가 생길 경우 Rollback 가능합니다

### Github
- Git 소스 저장소
- Github Page 무료로 호스팅
- 포트폴리오로 활용 가능
- 기업에서 점점 Github 주소를 요구
- 대학생일 경우 [Github Education](https://education.github.com/)에 가입하면 여러 혜택을 받을 수 있습니다
	- Private Repo 생성 가능 

### 공부할 자료
- 진유림님의 [초심자를 위한 Github 협업](https://realhanbit.co.kr/books/125/)
- [누구나 쉽게 이해할 수 있는 Git 입문](https://backlog.com/git-tutorial/kr/)

## Linux
- 데이터 분석, 머신러닝/딥러닝, 데이터 엔지니어링 실제 업무시엔 "서버"에서 작업합니다
	- 로컬 컴퓨터는 하드웨어의 한계가 존재할 수 있어 서버 컴퓨터 파워를 사용합니다
- 그 서버의 OS는 대부분 Linux
- 따라서 Linux에 대해 이해를 하면 할수록 좋습니다
- 로컬 컴퓨터의 OS를 Linux로 설치해서 경험해 보는 것이 Best
- 저는 [김태용의 리눅스 쉘 스크립트 프로그래밍 입문](http://www.yes24.co.kr/24/goods/3538385), [만화로 배우는 리눅스 시스템 관리 2](http://www.yes24.com/24/Goods/33569480?Acode=101)를 통해 공부했습니다

## Python
- 데이터 분석에서 자주 사용하는 프로그래밍 언어는 R 또는 Python입니다
- 각 언어마다 장단점이 있으며 필요할 경우 두 언어를 모두 사용하면 좋습니다
- 처음 프로그래밍 언어를 접할 경우, 상대적으로 자료가 많은 Python을 추천하고 있습니다
	- 웹 프로그래밍, 데이터 분석 등 범용적으로 사용할 수 있는 것이 Python이라고 생각해서 추천하고 있습니다
- 저는 [점프 투 파이썬](https://wikidocs.net/book/1), 최성철 교수님의 [데이터 과학을 위한 Python 입문](https://www.inflearn.com/course/python-%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EC%9E%85%EB%AC%B8-%EA%B0%95%EC%A2%8C/)를 통해 파이썬 기초를 익혔습니다
- 또한 데이터 분석에서 자주 사용하는 Numpy, Pandas를 추가적으로 학습했고 [numpy_exercises](https://github.com/rougier/numpy-100), [pandas_exercises](https://github.com/guipsamora/pandas_exercises)를 풀었습니다

## 머신러닝 딥러닝 기초
- 머신러닝/딥러닝에 대한 지식은 반드시 꼭!
- Andrew ng님의 Coursera [Machine Learning](https://www.coursera.org/learn/machine-learning)
- 김성훈 교수님의 [모두를 위한 딥러닝](https://www.youtube.com/playlist?list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm)
- 책은 [밑바닥부터 시작하는 딥러닝](http://www.yes24.com/24/goods/34970929?scode=032&OzSrank=1), [핸즈온 머신러닝](http://www.yes24.com/24/goods/59878826?scode=032&OzSrank=1)이 좋습니다
	- 밑바닥부터 시작하는 딥러닝 : 딥러닝 프레임워크를 사용하지 않고 Numpy로 직접 구현해보는 책입니다
	- 핸즈온 머신러닝 : 머신러닝/딥러닝에 관해 잘 정리된 책입니다. 커버 범위도 넓고 다양한 팁들이 있습니다. 단, 수학적으로 접근하진 않는 편입니다 

## 데이터 크롤링
- 데이터 관련 프로젝트를 할 때 제일 고민되는 것 중 하나는 "데이터를 어디에서 구하지?"입니다	
- 공공 데이터, API, 캐글 등에서 데이터를 구할 수 있지만 제한된 데이터일 경우가 많습니다
- 따라서 데이터를 직접 수집해오는 데이터 크롤링을 해야합니다
- 크롤링에 대한 내용은 이준범님의 [나만의 웹 크롤러 만들기](https://beomi.github.io/gb-crawling/) 자료를 추천합니다

## Cloud Service
- Linux의 맥락과 유사하게 실제 업무시엔 서버에서 작업합니다. 서버는 대부분 클라우드 서비스(AWS, Azure, GCP, IBM, NBP 등 )를 사용하기 때문에 클라우드 서비스를 배우는 것을 추천합니다
- [AWS](https://aws.amazon.com/)는 [AWS Educate](https://aws.amazon.com/ko/education/awseducate/)에 가입할 경우 $100를 제공합니다
- [Azure](https://azure.microsoft.com/)는 (누구나) 가입시 1달간 사용할 수 있는 $200를 제공합니다
- [GCP](https://cloud.google.com/)는 (누구나) 가입시 1년간 사용할 수 있는 $300를 제공합니다
- [IBM Cloud](https://www.ibm.com/cloud/)는 (누구나) 가입시 1달간 사용할 수 있는 $200를 제공합니다
- [NBP](https://www.ncloud.com/)는 (누구나) 가입시 1년간 사용할 수 있는 30만원 크레딧을 제공합니다
- 많이 사용하는 플랫폼은 AWS, Azure, GCP 순입니다


## 선형대수
- 선형대수는 벡터공간을 공부하는 학문입니다
- 우리가 보고 느끼는 공간은 기본적으로 3차원이지만 머신러닝/딥러닝에서 나오는 문제들은 모두 4차원 이상의 고차원 문제를 다룹니다 
- 이런 문제를 쉽게 이해할 때 도움주는 것이 선형대수입니다!
- 이상화 교수님의 [선형대수](https://www.youtube.com/playlist?list=PLSN_PltQeOyjDGSghAf92VhdMBeaLZWR3)
- [칸아카데미 선형대수 강의(한글자막)](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/vector-introduction-linear-algebra)
- 임성빈님의 [Matrix calculus](https://www.slideshare.net/ssuser7e10e4/matrix-calculus)