# OSS_Final-Project_2020-fall
### SCE331_ 오픈소스SW입문(F083-2) 기말 프로젝트
Open Source Software 도구 한글 번역 기여하기 : Bitcoin 0.21.x

소프트웨어학과 201920707 정세빈

제출일 : 2020.12.20.

## Transifex Bitcoin 0.21.x Translation Project
#### Transifex BitcoinCore 0.21.x Korean

https://www.transifex.com/bitcoin/bitcoin/language/ko/

Copyright © Bitcoin Project 2009-2020 Released under the MIT license
#### Transifex Bitcoin 0.21.x Translation Project Report
Copyright © 2020 Jeong Sebin, Ajou University 

## 목차
* [서론](##서론)
* [이론적 배경](##이론적-배경)
* [본론](##본론)
* [결과물](##결과물)
* [결론 및 소감](##결론-및-소감)
* [참고 자료](##참고-자료)

&nbsp;
## 서론
&nbsp;&nbsp;구글 검색창에 “과거로 돌아가면”을 입력하면 뒤에 “비트코인”이 따라붙은 자동검색어가 뜬다. 급상승과 하락을 짧은 기간 내에 겪은 대표적인 디지털 화폐 비트코인. 돈과 투자에 관심이 없는 사람조차도 비트코인에 대해서 한 번씩은 들어봤을 것이다. 0과 1로 이루어진 데이터 쪼가리로 가치도 없을 것 같은 이 가상의 화폐는 어느 날 갑자기 개당 현실 돈의 몇 천만씩으로 가격이 뛰면서 유명해졌다. 로또보다 대박 터진 잭팟으로 이목을 끈 비트코인의 성공에 비슷한 디지털 화폐인 이더리움, 리플 등도 뒤따라 재조명받았고, 암호 화폐와 관련된 블록체인 기술의 연구도 활성화되었다.

&nbsp;올해 초까지만 해도 비트 코인의 전망은 그리 밝지 않았다. 그러나 간편 결제 서비스 페이팔(Paypal)이 비트코인 등 암호 화폐와의 거래를 지원한다는 소식 이후 비트코인 가격이 급등하기 시작하더니 현재는 2달 전의 가격 두배를 넘어 3년만에 최고점을 찍었다. 2차 열풍이 불고 있는 것이다.

&nbsp;나는 평소에 비트 코인이나 주식 등 투자에 많은 관심을 가지고 있으나 아직 학생 신분이며, 여윳돈 또한 별로 없고, 투자의 위험성이 두려워 제대로 투자에 참여해 본 경험은 없다. 개인적으로 투자를 시작하기 위해서는 먼저 대상에 대해 잘 알아야 한다고 생각해서 아직 도전하지 않기도 하였다. 그래서 이번 기회를 빌려 비트 코인을 번역하고 알아가는 시간을 가지게 되었다.

&nbsp;
## 이론적 배경
### 비트 코인은 무엇인가?

>"비트코인은 새로운 지불 시스템이자 완전한 디지털 화폐를 가능하게 하는 합의된 네트워크입니다. 중앙 권력이나 중간 상인이 없이 사용자에 의해 작동하는 최초의 분권화된 P2P 지불망입니다. 사용자 관점에서 볼 때, 비트코인은 인터넷 현금과 매우 유사합니다. 비트코인은 현존하는 가장 탁월한 삼식 부기 시스템이기도 합니다." 
> &nbsp;
> **- Bitcoin.org. [비트코인 자주 묻는 질문](https://bitcoin.org/ko/faq)**

&nbsp;2008년, 나카모토 사토시는 공개키-개인키 암호기술과 디지털 서명, 그리고 P2P 기술을 융합하여 블록체인이라고 알려지게 된 새로운 분산 데이터베이스를 개발함으로써 탈중앙화된 결제 시스템을 만들어냈다. 이것이 지금 우리가 잘 알고 있는 비트 코인이다.

&nbsp;비트 코인은 전자메일을 떠올리면 이해하기 쉬운 구조이다. 사람들은 누구의 허락 없이 가명의 계정을 만들 수 있다. 만든 계정으로 ‘거래’를 실행하고, 여기에 개인키로 디지털 서명을 함으로써 전 세계 누구와도 몇 분 안에 비트 코인을 주고받을 수 있다. 어떠한 거래에 대한 서명이 이루어지면, 비트 코인 네트워크의 구성원들은 그 거래가 유효하다는 것을 확인한 후 해당 비트 코인 계정의 잔고를 업데이트한다. 이 업데이트는 비트 코인 프로토콜의 적용을 받는 비트 코인 블록체인(공동의 저장 장치)에 기록된다. 비트 코인의 결제 네트워크가 P2P 네트워크에 의존하고 있으므로 회복력이 강하고 셧다운 하기 어려우며, 전 세계의 컴퓨터들에 동일한 복제본이 저장되어 있다. 게다가 보안성과 안정성을 위해 정보를 추가, 수정, 삭제하는 것이 매우 복잡하게 되어있기 때문에 비트코인 네트워크에 합류하는 누구든지 비트코인 블록체인의 전체 기록을 내려받거나 검토할 수 있고 비트코인 거래를 추적할 수 있다.


### Transifex는 무엇인가?

>"**트랜시펙스**(Transifex)는 세계화 관리 시스템 (GMS)이라고도 알려진, 웹 기반의 번역 플랫폼이다. 그것은 소프트웨어, 설명문서와 웹사이트와 같은 자주 업데이트되는 내용이 있는 기술적인 프로젝트를 대상으로 하며 개발자가 사용하는 도구와 통합하여 지역화 워크플로의 자동화를 권장한다. 트랜시펙스는 Software as a Service로 제공하고 상용 계획과 오픈 소스 프로젝트를 위한 무료 계정을 둘 다 갖춘다."
> &nbsp;
>**- 위키백과. [트랜시픽스](https://ko.wikipedia.org/wiki/%ED%8A%B8%EB%9E%9C%EC%8B%9C%ED%8E%99%EC%8A%A4)**

&nbsp;Transifex는 위키백과와 비슷한 집단 지성을 활용하는 번역 플랫폼이다. 사용법은 간단하다. 번역을 원하는 컨텐츠를 플랫폼에 올리면, 전세계 사람들이 자유롭게 팀에 가입하여 자신이 사용할 수 있는 언어로 번역을 한다.

&nbsp;Transifex의 번역 프로젝트에 참가하는 기여자들은 처음에는 번역가(translator)로만 참가할 수 있으며, string을 번역하고 수정하는 것만 할 수 있다. 이후 매니저 혹은 관리자의 승인을 받으면 maintainer 또는 reviewer가 되면, string을 review 할 수 있게 된다.
 

&nbsp;
## 본론
### 번역 대상: Bitcoin Core 0.21.x
![transifex_bitcoin_main_screen](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_bitcoin_main_screen.PNG)

&nbsp;Bitcoin은 2012년 7월부터 Transifex 사이트를 통해 번역 프로젝트를 시작해왔다.

&nbsp;Transifex에는 두 가지의 bitcoin 관련 프로젝트가 있다. Bitcoin.org와 Bitcoin이다. Bitcoin.org는 비트코인을 설명하고 소개하는 사이트 글을 번역하는 팀이고, Bitcoin은 Bitcoin Core, 클라이언트를 구동하는 비트코인 소프트웨어의 String을 번역하는 팀이다.

&nbsp;나는 Bitcoin으로 명시 되어있는 Bitcoin core 번역에 참가하였다. Bitcoin core은 0.12.x 버전 부터 시작하여 현재는 0.19.x, 0.20.x, 0.21.x 3가지 버전을 122개의 서로 다른 언어로 번역될 수 있도록 오픈하고 있다. 그 중에서도 나는 가장 최신 버전인 0.21.x를 번역하였다. 

&nbsp;0.21x는 20년 5월부터 시작된 프로젝트로, 한국어팀에 속한 번역가는 34명이다. 원래 마감 예정 기한은 12월 3일로 되어있었으나 Bitcoin.org팀으로부터 기한이 지나도 번역 수정은 계속해도 괜찮다는 대답을 들었고, 번역을 계속 진행하게 되었다.

&nbsp;Bitcoin Core 프로그램은 https://bitcoincore.org/ 사이트에서 다운 받을 수 있다. 12월 20일 기준 0.20.x 버전까지 오픈되어 있으며, 내가 번역에 참가한 0.21x 버전은 아쉽게도 아직 나와있지 않다.

&nbsp;
&nbsp;
### 번역 진행
&nbsp;Bitcoin 0.21.x의 총 string은 987개, 단어 5577개이다.

![transifex_0.21.x_korean](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_0.21.x_korean.PNG)

&nbsp;내가 번역하면서 찾은 문제점은 다음과 같다.
- Transifex의 경우 많은 사람이 한꺼번에 번역에 참여하는 프로젝트이기 때문에 각자의 스타일에 따라 번역이 중구난방이며 매끄럽게 끝나지 않는다. 
- Bitcoin 프로젝트는 프로젝트를 시작할때 새로운 업그레이드 버전에 전단계 버전의 string을 그대로 가져온다는 특징이 있다. 이는 처음부터 모든 것을 번역하지 않아도 되게 해주며 부담을 줄여주는 좋은 기능이나, 막상 확인해보니 string의 내용 자체가 달라져서 번역이 쓸모 없는 경우 또한 존재하였다.
- 비트 코인에서만 사용하는 단어들, 사전에 등록되어 있지 않은 단어들이 꽤 존재한다.

&nbsp;
&nbsp;
&nbsp;따라서 위 문제점들에 신경을 쓰며 번역을 하였다.
&nbsp;

&nbsp;1. 번역의 뼈대는 번역이 100퍼센트 완료 되어있는 프랑스어 번역과 중국어 번역을 참고하였다.
- 프랑스어: 유일하게 review가 되어있으며, review가 100퍼센트 되어있는 언어.
-  &nbsp; &nbsp; 중국어: 한국어와 같이 라틴어/알파벳을 글자로 사용하지 않는 언어.
&nbsp;
![transifex_bitcoin_languages](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_bitcoin_languages.PNG)


&nbsp;2. 프로젝트 매니저의 공지사항을 숙지하였다.
- &는 위치 네비게이션을 위한 문자이기 때문에 무조건 지정된 글자의 앞에 두어야한다. 따라서 Warning을 무시하고 괄호를 사용하였다.
- %들은 string이 들어가야 하는 곳이므로 ASCII percent-sign이 들어가야 한다. 마찬가지로 s,n등 뒤따라오는 단어가 정확히 원본과 같아야한다.
- %들은 string이 들어가야 하는 곳이므로 ASCII percent-sign이 들어가야 한다. 마찬가지로 s,n등 뒤따라오는 단어가 정확히 원본과 같아야한다. 
![transifex_anouncement_2](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_anouncement_2.bmp)


- %는 숫자가 아닌 이상 영어와 어순이 비슷하게 번역해야한다. %가 두개 이상 사용되었을 경우 순서가 바뀌면 안 된다라는 뜻이다. 
![transifex_anouncement_1](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_anouncement_1.bmp)


&nbsp;3. 종결 어미는 '하십시오'에 맞춰 최대한으로 통일하였다. 관리자가 입력한 첫번째 string의 종결 어미였기 때문에 이를 중심으로 한 것이다.

|종결 어미 | 하십시오체|
|----: | ----|
|평서문 | -(습/ㅂ)니다|
|의문문 | -(습/ㅂ)니까|
|명령문 | -(ㅂ)시오|
|청유문 | -(ㅂ)시다|

&nbsp;4. 번역이 통일되지 않은 단어를 상황에 맞게 통일시켰다.

&nbsp;&nbsp;ex) Transition
- transition이 PSBT로 쓰일경우 -> 트랜지션
- transitiion이 그냥 홀로 쓰인 경우 -> 거래

&nbsp;5. 한글화를 최대화시키고 번역을 매끄럽게 하기 위해 사전에 없는 단어들을 임의로 번역하기도 하였다.
- Fallbackfee = 고장대체 수수료
- Replace-By-Fee 수수료-대체
- mempool 메모리 풀
- keypoolrefill : 키 풀 리필
- addrMan: 어드맨(bitcoin storage. address of other peers)
- satoshi: 비트코인 단위 사토시
  
&nbsp;6. 반면에 비트코인에서 전용적으로 사용하는 용어나, 프로그래밍과 관련된 단어는 번역하지 않기도 하였다.
- Tor, onion, asmap 등의 고유어로 사용되는 소프트웨어
- Ipv6 Ipv4,SOCKS5와 같은 약자가 사용되어 번역하면 너무 길어지는 단어
- -reindex-chainstate 등의 앞에 -가 붙은 bitcoin의 코딩 단어
- uacomments, pre split keypool 등 구글에 검색했을때 비트코인 사용자들이 영어로 사용하는 단어 
 
&nbsp;
## 결과물

![transifex_bitcoin_my_translations](https://git.ajou.ac.kr/JSB/oss_final-project_2020-fall/-/raw/master/image/transifex_bitcoin_my_translations.PNG)

https://www.transifex.com/bitcoin/bitcoin/viewstrings/#ko/qt-translation-021x/302586000

-  직접적으로 수정한 string은 필터 창에 "translator: jsebin1327"을 검색하여 찾아볼 수 있다. 혹은 Users -> Translator -> jsebin1327 으로도 검색이 가능하다.
- 총 270개의 string, 2439개의 단어를 손보았으며, 나머지는 다른 분들의 번역을 참고하여 최대한 살리려고 노력하였다.
- 검색되지 않은 string 또한 모두 검토한 string들이다.

&nbsp;
## 결론 및 소감

&nbsp;기말 프로젝트 승인을 받을 때, 번역할 string의 양이 적어 부족해보인다는 의견을 수렴하여 0.20x와 0.21x를 한꺼번에 번역하려고 하였다. 그러나 0.21x가 0.20의 업그레이드 버전이며 0.21x에 0.20x의 string이 모두 포함되어있다는 것을 알게 된 뒤 번역할 양이 더 많고 업그레이드 된 0.21.x만을 번역하기로 하였다. 0.21.x 프로젝트의 예정일은 12월 3일임에 비해 0.20.x의 경우 1년전에 마감된 프로젝트라는 점 또한 이 결정을 도왔다. 그러나 아직 0.21.x가 다운로드 페이지에 보이지 않는 것을 보면 0.20.x의 번역을 우선시 하는 것이 나았을까라는 생각이 들었다.

&nbsp;Transifex를 이번 학기에 처음 알게 되어, 낯선 것이 너무 많아 실수를 많이 하였는데, 가장 큰 실수는 번역 팀을 헷갈린 것이었다고 생각한다. 나름 철저히 준비를 하고 조사를 하며 다른 번역가들과도 소통을 하기 위해 텔레그램에 가입까지 하였는데, 알고보니 내가 참가한 방이 Bitcoin.org번역가들을 위한 방이었다. 의욕만 너무 앞선 것을 반성한다. Transifex에 Bitcoin 관련 프로젝트가 두 개 존재한다는 것도 이 실수를 통해 알게 되었다. 나중에서야 원 프로젝트의 매니저를 찾고 Bitcoin core 번역가들을 위한 gmail 공지방에 가입하였다.

&nbsp;그래도 결과적으로는 잘한 실수라고 생각한다. 텔레그램에서 Bitcoin.org팀의 번역가들과 대화하면서 Transifex 번역에 대해 많은 도움을 받았다.

&nbsp;내가 팀에 가입할 당시 번역되지 않은 string은 약 200개 정도 였는데, 11월 말과 12월 초에는 나 말고도 다른 사람들도 번역에 활발하게 참여하여 12월 3일에는 번역이 되지 않은 string이 없었다. 따라서 번역이 생각보다 수월할 것이라고 생각하였다. 그러나 예상과 달리 꽤 많은 시간을 잡아먹었다.

&nbsp;사람들이 활발하게 참여하여 내가 최종 과제를 제출할 때 string이 바뀔 것을 염려하여 중간 중간에 내가 번역을 마친 부분에서 따로 파일을 다운로드 해두었는데, string 모두 번역 완료되기 전인 초반 말고는 그 뒤로 아무도 접속하지 않았다. Transifex를 통한 소통을 기대했는데, 이 부분에서는 조금 아쉬웠다.

&nbsp;개인적으로는 성당과 시장 번역때보다 번역이 어려웠던 것 같다.
&nbsp;성당과 시장 같은 경우 전체적인 하나의 글이기 때문에 문맥상 의미를 파악하고 상황에 맞는 번역을 하기 수월했다. 그러나 bitcoin의 경우에는 모든 string이 짧은 문장과 단어로 끊어져있어 유동적인 번역이 어려웠다. 비트코인에서만 사용하는 고유 용어가 들어가서 해석에 좀 더 애를 먹기도 하였다. 성당과 시장보다 코딩 용어등 컴퓨터 언어가 훨씬 더 많이 들어가기도 했다. 그래서 직역으로 뜻을 최대한 살리는 방향으로 번역을 하려고 노력하였다.

&nbsp;성당과 시장 번역때는 조원들과 따로 카톡방에서 소통을 했었는데, Transifex 자체에서는 다른 번역가들과 소통 하기가 힘들었던 것도 이유라고 생각한다. 왜 번역팀들이 따로 채팅방, 공지방을 두었는지 느꼈다. 메세지함 또한 페이지에 접속하지 않는 이상 알람이 뜨지 않는 것 같았다.

&nbsp;Bitcoin의 경우 큰 프로젝트 이기 때문에 번역하는 사람이 많았는데, 그에 비해 Reviewer는 거의 없었다. Transifex 메세지를 통해 총 관리자와 한국팀 매니저에게 Reviewer 신청도 하였지만 아무래도 좀 늦게 물어본 탓인지 답장도 받지 못했다. Reviewer가 되었다면 검토한 흔적도 확실히 남을 것이라고 생각되어 아쉬웠다.

&nbsp;Bitcoin 프로젝트는 정기적으로 번역 프로그램을 열고 있으니 다음번에도 시간을 낼 수 있다면 Reviewer 신청까지 받아 확실하게 참여해보고 싶다. 아니면 Bitcoin.org의 사이트 번역에도 참여하면 재미있을 것 같다. 앞으로도 가끔 transifex에 들려 관심가는 프로젝트를 둘러봐야겠다.

&nbsp;
## 참고 자료

#### 1. 사전
1. TTA 용어사전 - <http://word.tta.or.kr/main.do>
2. KS 용어사전 - <https://standard.go.kr/KSCI/dictionary/getDictionaryList.do?menuId=60401&topMenuId=558&upperMenuId=558>
3. 국립국어원 대사전 - <https://stdict.korean.go.kr/main/main.do>
---
#### 2. 추가 참고문
1. 프리마베라 드 필리피 외 1명(2020). 코드가 지배하는 세상이 온다. 미래의 창
2. 위키백과. 비트코인 위키. <https://en.bitcoin.it/wiki/Main_Page>
3. Transifex 사용법. <https://docs.transifex.com/intro/transifex-terms>
4. Github. 비트코인 0.21.x 번역 일정. <https://github.com/bitcoin/bitcoin/issues/18947>
5. 국립국어원. 상대높임법2. <https://www.korean.go.kr/front/onlineQna/onlineQnaView.do?mn_id=216&qna_seq=62639>