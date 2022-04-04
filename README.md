# Java

> **생활코딩 Java** 강의 듣기 (1~17강 수강)
* Java 와 Eclipse 를 Install 함.
* Code(.java) → Comfile(.class) → 실행

![image](https://user-images.githubusercontent.com/102607435/161495458-4ba8c682-fbe4-4997-a689-e7d9a70660fb.png)

* package explorer → new → package 에서 .(dot) 을 이용하여 파일 분류하여 생성 가능
* 생성된 pakage → new → class → public static void main (String args) 체크 하면 쉽게 코딩 가능
***
## Eclipse 와 Github 연동
* window → show view → other → git repositories →  open → clone git repository →  URI 및 USER, P/W 입력
* 코딩한 폴더 team → share project →  add index → commit
***
## Eclipse 와 Github 연동시 오류사항 및 해결방법
> **기존에 다른 아이디로 작성된 기록이 있어서 User 와 E-mail 기존 것으로 자동 입력되어 있어 fetching 오류 해결**

<img width="941" alt="20220404_165424" src="https://user-images.githubusercontent.com/102607435/161500710-9920b880-a06f-4f06-98c1-c8139273b729.png">


* window → preferences → git → donfiguration → add entry → user.name 과 user.email 입력 → apply and close

> **Commit 시 권한이 없다는 오류 해결**
* github 계정 → 설정  → 왼쪽 카테고리에 [Developer settins] → 왼쪽 메뉴 [Personal access token] → 오른쪽 상단[Generate new token] 
* → 필요한 권한 선택(Select scopes)후 생성 → commit 할 때 P/W 는 발급된 토큰으로 기입하면 권한이 없다는 오류 해결
