---
title: chirpy --- layout home Index page ---
description: chirpy 테마 적용 중 index.html에 있는 --- layout home Index page ---만 나오는 증상 해결
author: solon
date: 2024-05-01 20:55:00 +0800
categories:
  - Blogging
tags: 
pin: true
media_subpath: /posts/20180809
---

github 블로그로 chirpy 테마를 선택했다. 

github page 설정과 custom domain까지 설정했으나 
![[Pasted image 20240501183917.png]]

찾아보니 여러가지 해결법이 나오는데 여러 개를 해봐서 정확히 어떤 것이 문제인지 정확한 해결책인지 모르겠다.
다만 마지막으로 본 블로그는 아래이다.
https://jjikin.com/posts/Jekyll-Chirpy-%ED%85%8C%EB%A7%88%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-Github-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0(2023-6%EC%9B%94-%EA%B8%B0%EC%A4%80)/

나의 경우 로컬에서 루비 설치 및  jekyll serve까지 확인한 후 커밋했으나 여전히 위의 오류가 발생했고 
1. github action에서 configure, commit changes
2. .gitignore에서 assets/js/dist
3. **커밋 한  번 더**한 후에 해결됐다.


