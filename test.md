2021년 12월 Log4j 취약점 이슈가 전세계를 강타한다.

\[[https://www.krcert.or.kr/data/secNoticeView.do?bulletin\_writing\_sequence=36389](https://www.krcert.or.kr/data/secNoticeView.do?bulletin_writing_sequence=36389 "https://www.krcert.or.kr/data/secNoticeView.do?bulletin_writing_sequence=36389")\]

![](https://t1.daumcdn.net/keditor/emoticon/friends1/large/012.gif)

내가 관리하는 웹서비스라고 그러한 이슈를 피해갈 수 없었지만,

다행히 해당 취약점은 Log4j 2의 일부 버전에 국한된 문제였고,

Log4j 1버전을 사용하고 있던 오래디 오래된 우리의 서비스는 풍파를 피해 살아남았다.

[##_Image|kage@b033fv/btrsQpMcwpZ/AAQTB3XCBhl0GS8Mmu9kY0/img.png|CDM|1.3|{"originWidth":598,"originHeight":113,"style":"alignCenter","caption":"보안취약점 - 초기발표 버전","filename":"blob"}_##]

하지만 회사의 관리체계는 수직적으로 작용하였고, 문제는 없었지만 아직도 1버전을

사용하냐는 질타와 함께 강제로 최신버전 업데이트를 명 받았다.

![](https://t1.daumcdn.net/keditor/emoticon/face/large/029.png)

처음에는 Maven Dependency의 버전정보만 수정하면 문제가 없을거라 생각했다.

그리고 가벼운 마음으로 Maven Dependency를 확인하였고, 작업은 생각만큼 순탄하지 않았다.
