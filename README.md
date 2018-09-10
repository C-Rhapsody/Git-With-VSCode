# Git-With-VSCode
VSCode를 사용하면서 Git 실사용 적용기
(VSCode 및 Git 초기 사용방법 숙지)

## 설치
### 환경 : 윈도우 10 64bit

참고한 사이트 : <https://demun.github.io/vscode-tutorial/git/>

1. VsCode 설치 : 
<https://code.visualstudio.com/download>

1. Git SCM 설치 : 
<https://git-scm.com/download/win>

1. Cdoe Highlight
    - PowerShell
    - Python
    - Javascript
  
## Git Command

참고한 사이트 : <https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/>

1. 프로젝트 생성
  - 'git remove add origin https://github.com/*user*/*repo*.git'
  - 'git remove -v'

1. 생성된 프로젝트에 업로드
  - 생성한 디렉토리 이동
  - 'git init'
  - 'git commit -m "코멘트"'
  - 'git remote add origin *remote reposity URL*
    - 1번에서 생된된 uri 확인
  - 'git remove -v'
  - 'git push origin master'