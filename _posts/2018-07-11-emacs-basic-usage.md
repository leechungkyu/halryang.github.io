---
layout: post
title: Emacs 기본 사용법
date: 2018-07-11 13:34:40
tags: Emacs jekyll blogging
---

파일 저장은 `C-x-s`
파일 열기 `C-x-f`

명령의 취소는 C-g로 합니다.

### helm Projectile

[Helm Projectile](https://github.com/bbatsov/helm-projectile "Helm Projectile")은 현재(2018-07-11) 개발자가 본인이 사용하고 있지 않으므로 유지할 사람을 찾는다고 깃헙에 글을 올려둔 상태라서 얼마나 더 지원이 될지 모르겠지만 일단 세팅해두고 사용하고 있습니다.

MELPA Stable repository를 통해 설치하였고 `M-x helm-projectile` 이후 사용할 수 있습니다.

* 프로젝트 안의 파일 찾기 `C-c p F`
* 프로젝트 간 스위치 `C-c p p`
* 프로젝트 버퍼 스위치 `C-c p b`
* Incremental grep `C-c p s g`

### Magit

Emacs로 Jekyll 블로그에 글을 적고 나서 바로 GitHub에 commit, push하고 싶어서 Magit을 찾아서 설치했습니다. [Getting Started with Magit](https://magit.vc/manual/magit/Getting-Started.html#Getting-Started "Getting Started with Magit")을 참고하면 `M-x magit-status RET`로 현재 Git repository의 상태를 확인할 수 있습니다. 이 명령어를 자주 사용할 수 있으니 `.emacs`에 `(global-set-key (kbd "C-x g") 'magit-status)`로 `C-x g`를 할당할 수 있습니다.

* 섹션 이동 `p`, `n`
* 포인트가 있는 섹션의 expand or collapse `TAB`
* Staging `s`, Unstaging `u`
* `c c` commit, 메시지 적고 `C-c C-c`로 커밋 생성
* Push `P p`

가장 기본적으로 사용하는 Commit & Push를 하는 정도는 할 수 있게 되었습니다. 그 외에는 필요에 따라 찾아보려고 합니다.
