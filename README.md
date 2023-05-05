# DBDocs_Sample

## 생성 목적

> 해당 프로젝트는 DBDocs에 대한 포스트를 작성하고자 Sample을 작성할 때 사용한 저장소로 혹시라도 DBML파일이 필요할 경우 자유롭게 사용 할 수 제작하였습니다.

---

## 해당 레포지토리 코드확인 페이지

- [DBDiagram, ERD](https://dbdiagram.io/d/64551676dca9fb07c49405bc)
- [DBDocs, 문서화 페이지](https://dbdocs.io/donsonioc2010/DBDocsSample)

---

## 제작자 관련 포스트

---

### 사용방법에 대한 포스트

- [DBDiagram의 사용 방법](https://devjong12.tistory.com/67)<br>
- [DBDocs의 문서화 방법](https://devjong12.tistory.com/68)<br>
- [DBDocs의 CI 방법](https://devjong12.tistory.com/69)<br><br>

### 실제 사용 예제

- [자동화해서 사용중인 주인장의 실제 Repository](https://github.com/donsonioc2010/NooBLoL_DbDocs)

### 공식문서 Reference

- [DBDocs 튜토리얼](https://dbdocs.io/docs)
- [DBDiagram](https://dbdiagram.io/home)

---

## 23.05.03 추가사항

### 변경 이유

> DBDocs를 오랫동안 사용하면서 실제 현업에서 많은 스키마를 같은 DB안에서 동시에 다뤄보게 되었었고, 다뤄보면서 느낀 부분은 스키마에 대한 정리를 확실히 해볼 필요가 있다 싶어서 변경을 진행하게 되었다.
>
> 또한 스키마별로 구분을 하면서 Table의 Color기능이 DBDocs에서는 무료로 현재(23.05.03 작성일 기준) 사용이 가능하고 해당 기능도 매우 유용하다 생각하여 변경을 진행하게 됨.

PS. 작성자는 유료로 사용중이다

### 변경 내용

1. Github Actions CD추가
   - 과거에 사용했던 프로젝트만 CD가 존재해 sample.dbml(해당 파일 DBML)과 관계가 달라서 파악이 힘들수 있겠다는 생각이 들어서 해당 프로젝트 CD추가
2. Git Ignore추가
   - 기본적으로 VSCode를 활용하고 있어서 추가하였다.
   - TIL에 간간히 기록을 하고 있는데 설정파일이 알아서 생기는 문제에 대해서 안해줬다가 봉변을 맞아서다...
   - [이그노어 자동 생성페이지](https://www.toptal.com/)해당 페이지에서 vscode랑 git정도만 추가했다. 따로 제외하면 안되는 파일이 없어서..
3. 임의의 컬럼이 아닌 실제 사용을 해볼만한 토이 프로젝트로 구성하였다
   - 게.시.판!
   - 다중 스키마로 구현을 진행해봤다.
   - 다중 PK를 자연스럽게 녹여봤다.
   - Index를 최대한 활용해보고자 했다.
