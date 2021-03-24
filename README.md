# SQL
> 칼퇴족 김대리는 알고 나만 모르는 SQL
## 01. 데이터베이스란?
> 데이터가 유기적으로 결합하여 저장된 집합체
- 정의 : 여러사람에게 공유되어 사용될 목적을 가지고, 구조적인 방식으로 관리되는 데이터의 집합
- DBMS : Database Management System (데이터 추가, 변경, 삭제, 검색 등의 기능)
### DBMS의 특성
1. Real-time-proceessing : 지속적이며 실시간 처리
2. Continuous evolution : 동적(insert, delete, update)으로 정확한 데이터 유지
3. Concurrent sharing : 다수가 접근, 이용
4. Contents reference : 데이터 참조는 레코드의 주소나 위치가 아니라 사용자가 요구하는 데이터의 내용, 즉 데이터가 가지고 있는 값에 따라 참조된다.
### 용어
1. table : = 엑셀의 spreadsheet와 같다. 동일한 2개의 table 이름은 존재할 수 없다.
2. schema : 테이블에 데이터가 저장되는 방식을 정의한다.
3. column : 열, 테이블을 구성하는 각각의 정보, 각 열에는 고유한 데이터 형식이 지정된다.(정수, 문자, 통화, 날짜, 시간 등)
4. row : 행, 레코드라고 표현하기도 한다. 테이블의 데이터가 저장된다.
5. primary key : 각 행을 고유하게 하는 열. 데이터베이스 제어 및 관리, 최적화를 위해 각 테이블에 기본키를 반드시 설정해야한다.

## 02. SQL이란?
> 데이터베이스에서 데이터를 읽고 쓰기 위한 언어.
### SQL의 개요
- Structured Query Language (SQL) : 사용자 - 데이터베이스 시스템 사이의 의사소통 언어
> 관계형 데이터베이스 언어
### SQL의 종류
> SQL은 구조화된 질의 언어이다.
1. DDL : data definition language (데이터 정의어)
- CREATE : 데이터베이스 테이블 생성
- DROP : 데이터베이스 테이블 삭제
- ALTER : 기존 데이터베이스 테이블 재정의
2. DML : data manipulation language (데이터 조작어)
- INSERT : 테이블에 데이터 삽입/입력
- DELETE : 테이블에 데이터 삭제
- UPDATE : 기존 테이블 안의 데이터 수정
- SELECT : 테이블 내 데이터 검색
3. DCL : data control languate
- GRANT : 테이블에 권한 부여
- REVOKE : 부여한 권한 취소/회수
