##### 안녕하세요 플레이데이터입니다. 
##### 2020년 3월 교육과정 수강생들의 사전교육을 위한 repository(=repo)입니다.

##### 대략적인 순서는 다음과 같습니다.
1. python 설치
2. pycharm(IDE) 설치
3. github 회원 가입
4. git bash 설치
5. github내 encore-playdata/202003_ai의 repository를 Clone하기
6. 과제작성 후 pull request하기

##### pull request 해주시면 확인 후 업데이트 해드립니다.
##### 처음엔 git을 사용하는 방법이 생소하겠지만, 실무에서 꼭 필요한 도구이니 많이 사용해보시기를 권장드립니다.

<br/>
<br/>


# [과제 가져오기] 

#### 1. Github 회원가입을 아직 하지 않은 분들은 회원가입을 먼저 해주세요. 
<br/>

#### 2. 우측상단의 'Fork' 버튼을 클릭해주세요. !!!!!!!사진 변경!!!!!!!
![Fork](images/fork.jpg)
<br/><br/>

#### 3. 'Fork' 버튼을 클릭하면 다른 사람의 repo를 내 계정으로 가져올 수 있습니다. !!!!!!!사진 변경!!!!!!!
![Start](images/start.jpg)
<br/><br/>

#### 4. 이제 프로젝트를 내 로컬환경으로 clone하겠습니다. !!!!!!!사진을 변경해주세요!!!!!!!
'clone or download' 버튼을 클릭하고 주소를 복사합니다. 

![Clone](images/cloning.jpg)
<br/><br/>

#### 5. 로컬 환경으로 돌아가 terminal(git bash 등)을 킵니다. 
![Gitbash](images/bash.jpg)
<br/><br/>

#### 6. terminal에서 명렬어를 이용해 바탕화면에 폴더를 생성하고 폴더에 파일을 clone합니다.

바탕화면으로 이동 (cd 이동하고싶은폴더명)<br/>
cd Desktop/<br/>
<br/>

바탕화면에 폴더 만들기 (mkdir 만들고싶은폴더명)<br/>
mkdir playdata<br/>
<br/>

생성한 폴더로 이동 <br/>
cd playdata/<br/>
<br/>

내가 만든 폴더 내에 github에 있는 파일을 복사하기 <br/>
git clone (복사한 주소)<br/>
<br/>

잘 복사되었는지 확인하기<br/>
ls <br/>
<br/>

복사된 폴더로 들어가기<br/>
cd (폴더명)<br/>
<br/>

에디터 실행하기<br/>
code .<br/>

![Terminal_1](images/terminal_1.jpg)
<br/><br/>


#### 7. 이제 pycharm을 실행해 문제를 확인하고 과제를 해결합니다. 
<br/><br/>

# 아래는 과제를 하고 내 컴퓨터에 있는 파일을 github로 옮기는 작업입니다.

#### 먼저 Git에 대해 간단히 알아보겠습니다.
#### 깃은 아래와 같은 흐름으로 이루어져 있습니다.
![git](images/git.png)

- 간단하게 보면, 우리가 workspace에서 작업하여 파일이 변경되면 add 라는 명령어로 index에 반영시킵니다.
- index에 commit하면, local repository에 반영되고, remote repository(github)에 저장가능한 상태가 됩니다.
- 이 때, push 라는 명령어로 remote repository에 업로드하게 됩니다
- remote repository, 즉 온라인 github에 있는 데이터를 내 컴퓨터로 가져올 때는 pull 이라는 명령어를 사용합니다.
- 정리하면 github에 업로드하기 위해서는 add -> commit -> push 순서로 진행하고,
- 반대로 github 내용을 가져오기 위해서는 clone이나 pull 등을 이용합니다.

- 아직은 무슨말인지 잘 이해가 안가실텐데요, 아래 적혀있는대로 따라해보면서 고민도 하고, 찾아보았으면 좋겠습니다.
- 상세한 내용은 https://www.opentutorials.org/course/2708 이곳에서 공부하셔도 좋습니다.
- 나중에 git 사용법은 특강이 있을 예정이니 너무 걱정마세요!

# 여러분은 위에서 이미 내 repository에 202003_ai를 fork해서 내 컴퓨터에 clone까지 완료된 상황입니다.
# 이제 내가 만든 파일을 나의 github에 업로드를 해보겠습니다. 일단은 쭉 따라해보세요!

#### 1. 10번까지 문제를 풀고 현재 상황을 저장해보겠습니다. 
터미널에 아래 명령어를 입력하세요. <br/>
git status<br/>
<br/><br/>

#### 2. git status를 입력하면 변경된 사항들을 확인할 수 있습니다. 

#### 3. 로컬 repo에 과제 올리기 
git add <file name>
  <br/>

#### 4. 커밋하기 
git commit -m "전달하고 싶은 메시지" <br/>
<br/>

이런식으로 문제를 하나씩 풀때마다 커밋을 통해 변경된 사항을 저장해주세요. <br/>
<br/>

# 3. 최종 제출하기 

#### 1. 자신의 repo에 변경된 사항을 업데이트합니다. 
git push origin master
<br/>

#### 2. GitHub에서 repository에 업데이트 된 내역을 확인하세요. 

#### 3. 상단 메뉴의 'Pull Request' 탭을 클릭하고, 'New Pull Request' -> 'Create Pull Request' 버튼을 클릭합니다. 

#### 4. 제목에 과정명과 이름을 쓰고 'Create Pull Request'를 클릭합니다. 
