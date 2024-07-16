# Dreamteam
![뼝아리](https://github.com/user-attachments/assets/3f985233-99bc-42f9-aa08-766139e74a05)


### 프로젝트 주제 : 

#### 팀 구성
- Front-End: 하늘, 동렬
- Back-End: 다희, 준상
- AI: 원명

#### 기술 스택
- 프론트엔드 : HTML, CSS, JS, React, Bootstrap, Figma 등
- 백엔드 : Spring
- 데이터베이스 : 예) MySQL, Oracle 등
- AI : Tensorflow 2, Keras 등

#### 팀원
[하늘, 동렬, 다희, 준상, 원명]
- 하늘의 깃허브 주소
- 동렬의 깃허브 주소
- 다희의 깃허브 주소
- 준상의 깃허브 주소
- 원명의 깃허브 주소

## GitHub에 코드 올리는 방법
#### 초기세팅

#### git remote add origin https://github.com/genjiskang/Dreamteam.git
-> 이거는 깃허브 주소랑 내 파일이랑 연결하는 과정

#### git fetch origin
-> 깃허브의 내용을 내 파일 연결된 것과 연동되도록 새로고침

#### git pull origin main or git pull origin 브랜치명 
-> 깃허브에 올라와 있는 내용을 내 파일로 땡겨오기 pull

<개발시에는 각자 개인 브랜치를 생성해야 함 -> 충돌과 에러 방지>
#### 1. git checkout -b "새로운 브랜치명"
-> 새로운 브랜치를 파면서 그 브랜치로 이동

#### 2. git add .
-> 내 파일의 변경사항을 전부 올리기 위해 전체 체크 하는 것

#### 3. git commit -m "커밋메세지"
-> 메세지를 등록, 메세지를 등록하지 않으면 push가 불가능

#### 4. git push origin 브랜치명
-> 브랜치명에 적혀있는 브랜치로 모든 코드를 깃허브로 push

#### 5. 깃허브 사이트에 접속 후 pull request 하기
-> 새로운 브랜치에서 main branch로 병합)

#### 7. merge
-> Pull Request가 승인되면 병합 진행

#### 8. 다른 사람들의 코드도 다 main으로 merge 되었다면 git pull origin main
