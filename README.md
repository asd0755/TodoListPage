# Task
#### 9월 21일
- [x] Local에서 MySQL 연동
- [x] MySQL Table 생성
- [x] Router 폴더 생성, 리팩토링

```
Name, Tel, Email 데이터를 받아오는 예제 연습
```

#### 9월 22일
- [x] POST형식으로 받은 데이터를 DB에 추가하는 기능 구현 (Email 예제. email.js와 form.html 수정)
- [x] Local에서 Sequelize MariaDB 연동
- [x] sudo Permission denied 이유 여쭈어보기

```
Local에서만 작업하여 Putty 서버에서 컴파일 시 에러가 너무 많음
이후 Putty 서버에서만 컴파일
```

#### 9월 23일
- [x] MySQL Table 이름을 my_todo.todo-table에서 my_todo.todo_table로 수정 | Naming Convention : 예약어 주의!!
- [x] MySQL Table Column 추가 
- [x] todo_table에 테스트용 데이터 추가
- [x] MySQL와 Putty Server 연동(192.168.1.70:3001/)
- [x] nodemon 모듈 설치
- [x] MySQL Setting 후 간단한 쿼리문 실행(select * from todo_table)
- [x] MySQL 대신에 MariaDB Setting 후 간단한 쿼리문 실행(select * from todo_table)
- [x] PORT 이해

```
DB 관련 백엔드를 우선 개발
```

#### 9월 24일
- [x] src/api, assets, router, views 폴더 추가
- [x] todo_table의 모든 데이터를 html table로 출력
- [x] POST 기능을 Ajax로 구현 | ID만 받아옴
- [x] "192.168.1.70:3001/test" 페이지를 루트 페이지로 수정

```
DB 데이터 출력, 추가
```

#### 9월 25일
- [x] Upgrade DB Insert Form. Modify DB Column Type. (DATE >> DATETIME, Priority INT >> INT with Min 0 Max 10)
- [x] Add DB Delete Function by del_flag. (default : 0, delete : 1)


#### 9월 28일
- [x] index.js를 api폴더로 옮기기 / 코드 정리
- [ ] Sequelize로 MariaDB 연동 ??
- [ ] UI 꾸미기

```
<코드리뷰>
1. map 등 JS문법 공부
2. 새로고침없이 데이터로딩 eventListener('load', () => { ... })
3. /delete/:id 적용방법
```

```
<해야할 일>
1. Sequelize 설치(v.5.x.x)
2. sequelize에서 쓰기 위해 todo DB 테이블 model 작성(js)
3. Sequelize로 데이터쿼리
4. postman, client(본인 컴퓨터 DB나 아무 클라이언트 프로그램 사용) 등
```

#### 9월 29일
- [x] Sequelize 설치(v.5.x.x)

```
MariaDB가 아닌 SQLite 기반의 Sequelize 튜토리얼을 참고해 삽질한 날 
```

#### 10월 5일
- [x] sequelize에서 쓰기 위해 todo DB 테이블 model 작성(js)
- [x] Sequelize로 데이터쿼리


#### 10월 6일
- [x] postman, client(본인 컴퓨터 DB) 등 아무 클라이언트 프로그램 사용(postman에서 http://192.168.1.70:3001/ 접속)
- [ ] POST 방식으로 DB Insert 시 새로고침 없이 데이터 로딩(eventListener('load') 사용)
