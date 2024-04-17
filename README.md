# Be01 - Final Project - T5
![image](https://private-user-images.githubusercontent.com/150888333/317901783-7ef4f093-e965-4f5d-9cfb-17e4992c692f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMTk3MzksIm5iZiI6MTcxMzMxOTQzOSwicGF0aCI6Ii8xNTA4ODgzMzMvMzE3OTAxNzgzLTdlZjRmMDkzLWU5NjUtNGY1ZC05Y2ZiLTE3ZTQ5OTJjNjkyZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNDE3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDQxN1QwMjAzNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lNTk0NmE5NjM5NmNhZjA3NmVjZDZmMjRkZjljOWQ4MmEwM2JlNWI5ZGY3NTAxNWVhOGY2MTMwYmYwODI5MjAxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ZIeOe1tslsbPytjf-gmfNhEb2vWBxmzbG0unRPfjMy4)

안녕하세요! BPS입니다!!!🖐️🖐️🖐️
## Team Introduction

### 🏆 Team Name
 BPS(방문판매사람들) 

---
### 🕹 Team Role


<div align="center">

|**PROJECT MANAGER** | **GIT MANAGER** | **TECH LEADER** | **AGILE COACH** |
| :------: |  :------: | :------: | :------: |
[<img src="https://avatars.githubusercontent.com/u/62015109?v=4" height=150 width=150> <br/> 안우용🧛‍♂️](https://github.com/INAUGURATE-Ryong)| [<img src="https://avatars.githubusercontent.com/u/149128094?v=4" height=150 width=150> <br/> 임성현🐹](https://github.com/dhkdtld37) | [<img src="https://avatars.githubusercontent.com/u/150888333?v=4" height=150 width=150> <br/> 정수민🐰](https://github.com/jsmin6330) | [<img src="https://avatars.githubusercontent.com/u/148880521?v=4" height=150 width=150> <br/> 박민성👻](https://github.com/parc02) 

</div>

<br>

## Project Introduction


### ✔ Topic
- 제약사의 의약품 도매 영업 관리 시스템 구축

---
### 🗓 Duration
- 2024-03-04 ~ 2024-04-25

---  
###  Purpose
- 제약 제품의 중간 유통 과정에서 발생할 수 있는 손실을 최소화하고, 매출과 이익률을 증대시켜 영업활동의 효율성 향상

---
### 🔧 Stacks
DB <br>
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) <br>
BE<br>
<br>
FE<br>

<br>
CI/CD<br>
<br>

---
### - Ecosystem
- 여기에 구성을 적습니다.(DB, FE, BE, DEPLOY)


### - 요구사항 정의서

---
### 🖥 화면 설계

<details>
<summary>  ERD  </summary>
<div markdown="1">
 
![image](https://github.com/Team5-be01-Final-Project/.github/assets/149128094/7ccb4b1d-da73-4729-bea6-c0af69b90236)

</div>
</details>

<details>
<summary>  Figma  </summary>
<div markdown="1">
 
![image](https://github.com/Team5-be01-Final-Project/.github/assets/149128094/09a744e9-ed8e-4662-b7ca-bd1844c2b944)


</div>
</details>

### 시스템 아키텍쳐

### 📌 주요 기능
- 기능1
- 기능2


--- 
### 🚩 Git Flow

<img src="https://github.com/Team5-be01-Final-Project/Main/assets/150888333/8147a8de-9d3a-434f-bc95-6080ca72240f" width="600">

<details>
  <summary><b>Git 전략 설명<b></summary>
  <div markdown="1">

#### Main 브랜치
- 릴리즈가 끝난 최종 상태의 브랜치

#### Release 브랜치 ( 2024-03-18 추가 )
- Develop에서 Feature의 코드를 합치고 에러가 없을 시 배포 후 QA를 위한 브랜치

#### Develop(dev) 브랜치
- 다음 배포(릴리즈)를 대비하여 개발한 코드를 모아두는 브랜치
- 개발 및 테스트가 완료되면, Main 브랜치로 merge

#### Feature 브랜치
- 기능 단위 개발 브랜치
- feature에서 개발 완료 후, dev 브랜치로 merge

0.x.x : 정식 배포 버전

0.0.x : 기능 추가 버전

0.0.0 : 에러 및 간단한 수정 사항

  </div>
</details>

--- 
### ✒ Branch 전략

WBS NUMBER / 0.0.0 / 담당자이니셜

<img src="https://github.com/Team5-be01-Final-Project/Main/assets/150888333/870fe34b-4c32-4bc2-9d9a-69a07fd787c1" width="400">

<details>
  <summary><b>Branch 설명<b></summary>
  <div markdown="1">

- 예시

![image](https://github.com/Team5-be01-Final-Project/.github/assets/149128094/b7c6dc48-6f86-41a5-b1de-a8fca555f7fa)

```

4.2.1   /   1.          1.          0          /  SH
WBS넘버 /  배포버전. 기능추가.  버그픽스      /  담당자
4.2.1   /   1.        ' 2. '        0          /  SH
                      ㄴ 기능적인 추가 혹은 수정 사항 
4.2.1   /   1.          2.        ' 1 '        /  SH
                                  ㄴ 오타나, 문서 등 자잘 한 수정사항 
4.2.1   / ' 2.'         1.          0          /  SH
            ㄴ 릴리즈 버전 업데이트 시 2번째, 3번째 넘버링 초기화

```

  </div>
</details>

---
### 커밋 메세지 규칙
 태그(tag) + 제목(subject) " 으로 구성
 태그는 영어로, 첫 문자는 대문자로 작성
"[태그] 제목" 의 형태로 제목에 한글로 작업한 wbs의 타이틀이나 작업한 내용을 작성

### 태그 리스트
- Feat : 새로운 기능을 추가한 경우
- Fix : 버그나 에러를 고친 경우
- Docs : 기타 문서를 수정한 경우, 코드X (ex : README.MD, changelog.md, package.json)
- Test : 테스트 코드
- Chore : 빌드 업무 수정, 패키지 매니저 수정
- Design : CSS 등 사용자가 UI 디자인을 변경했을 때
- Rename : 파일명(or 폴더명) 을 수정한 경우
- Remove : 코드(파일) 의 삭제가 있을 때. "Clean", "Eliminate" 를 사용하기도 함
- Add : 코드나 테스트, 예제, 문서등의 추가 생성이 있는경우
- Move : 코드의 이동이 있는경우

```bash
PR 생성 시
$ git commit -m "[Feat] 4.5.3/2.1.0/SH 이상온도알림 기능 구현"

추가 커밋 시
$ git commit -m "[Add] 이상온도알림 권한 코드 추가"
``` 

---
### 💾 Repositories
- ### [BackEnd](https://github.com/Team5-be01-Final-Project/Backend)
- ### [FrontEnd](https://github.com/Team5-be01-Final-Project/Frontend2)
- ### [Main Issues](https://github.com/Team5-be01-Final-Project/.github/issues)


---
### 💼 Documents
- [5팀 공유문서함](https://drive.google.com/drive/u/0/folders/1fuUfSboLm9YcFC8DAtG9McZ_AvR78DKZ)

- [KANBAN](https://github.com/orgs/Team5-be01-Final-Project/projects/1)

- [WBS](https://docs.google.com/spreadsheets/d/12YSTL03Vkp5sJB98k0OAiqpQV4MevNZT/edit#gid=305925292)

- [회의록](https://drive.google.com/drive/folders/1YHgWk-RPJCpE0LFaWgjVYvfAAKFwEZ4T)

- [기획안](https://docs.google.com/document/d/14ydCPkxF4Ui37WrlQTBx6Izzfz7MLiTvDKk_WpHeFEc/edit)
