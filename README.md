# SBB Repository

<Details>

<summary> DB 테이블

## DB 데이터 베이스

### Question(질문) 테이블
|속성이름|설명|
|:----------|:-------------------|
|id|질문 데이터의 고유번호<span style="color:red">**(기본키 PrimaryKey)**</span>|
|subject|질문 데이터의 제목|
|content|질문 데이터의 내용|
|createDate|질문 데이터를 작성한 일시|

### Answer(답변) 테이블
|속성이름|설명|
|:----------|:-------------------|
|id|답변 데이터의 고유번호<span style="color:red">**(기본키 PrimaryKey)**</span>|
|question|질문 데이터|
|content|답변 데이터의 내용|
|createDate|답변데이터를 작성한 일시|

</Deatils>