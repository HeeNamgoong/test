## GIT

* 분산 버전관리 시스템
* local <-> remote 간의 연동
  * git <명령어>를 통해서 관리
* git에 변경사항 반영
  * git status - 현재 git 상태 확인
  * git add <filename> - file을 생성 or 수정했을 때, 이를 commit에 반영하고 싶은 경우
  * git commit -m "<commit msg>" - 변경사항이 반영된 new commit 생성
  * git log - commit 기록 확인하기
* Git Branch
  * 코드의 흐름을 분산시키는 기능 - 더욱 효율적인 개발이 가능
  * Branch 생성
    * git branch <branch_name>
  * Branch 전환
    * git checkout <branch_name>
   * Branch 병함
    * git merge <branch_name>
   * Branch 삭제
    * git branch -d <branch_name>
    
  ## Github
  
  * 다른사람과 협업하기 위한 원격저장소, 협업 도구
  * Git을 지원하는 웹 호스팅 서비스 시스템(클라우드)의 한 종류
  * 즉 내 컴퓨터에 있는 깃의 히스토리를 가져와서 깃허브 웹사이트에 올릴 수 있음, 변경된 히스토리를    확인할 수 있음.
  
 ## Markdown
 
 * 웹상에서 글을 쓰는 모든 사람들을 위한 글쓰기 도구
 * 마크다운 문법
  * 제목(Header)
    * `#` 뒤에 띄어쓰기를 넣어주는 것이 권장
  * 줄바꿈(Line Breaks)
    * 띄어쓰기 2번 또는 `<br/>`
  * 글자 강조(Emphasis)
    *  `**<내용~>**` 의 형식
