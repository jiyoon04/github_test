# github 활용을 위한 연습

1. git init
   프로젝트 시작 전 딱 한번만 해당 폴더에서 진행

2. git commit
   git add 후 git commit
   이 때 -m 을 덧붙여 어떤 내용의 commit인지 넣자

3. git push
   저장소를 만든 후 로컬과 연결
   git remote add origin <url>
   git push origin main

4. git pull
   수정 사항이 있는 경우 원격 저장소에서 pull 해올 수 있다

5. git merge
   branch를 만들고 다시 merge할 수 있다
   git checkout -b new-branch
   이 때 수정 사항을 새 브랜치에서 커밋

   새 브랜치에서 하는 작업이 끝나 merge하고 싶다면
   git checkout main
   git merge new-branch


6. 잘 모르겠고 피곤하다 아침이니가
