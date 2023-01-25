---      
title:  "git bash 터미널에서 한글 파일명이 깨지는 경우"   
tag: [git, bash, git-bash, korean, broken, 한글, 파일명, 깨짐, filename]      
category:
    - git
    - git-bash
    - 한글
layout: single
#classes: wide
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
---

# Document Information   
- docNo: 20230122-1255   
- tag: #git #bash #git-bash #korean #broken #한글 #파일명 #깨짐 #filename   
   
# Contents   
   
git bash 터미널창에서 아래의 명령어를 실행하면 됩니다.    
   
```bash   
git config --global core.quotepath false   
```   
   