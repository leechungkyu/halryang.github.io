---
layout: post
title: Review - Ulysses for Mac
date: 2016-12-30 00:19
tags: review Ulysses mac_app
---
* 목차
{:toc}

## 들어가며

[Ulysses for Mac][1]을 [Setapp][2][^1] 덕분에 써볼 수 있게 되었습니다. 사실 이전에 체험판을 써봤지요. 그때 느끼기엔 너무 예쁘고, 기능도 깔끔하게 들어 있지만 제가 주로 사용하는 Dropbox를 기반으로 작동하는 것이 아니고 iCloud를 기반으로 하는 점과, 제가 쓰는 마크다운 문법(MMD)와는 다른 Markdown XL이라는 자체 문법을 사용한다는 점에서 약간 거리감을 느꼈습니다. 하지만 Ulysses에서 기본 마크다운 문법으로 내보내기가 가능하고, Dropbox 외부 폴더도 지원이 가능하기에 다시 사용해보려고 합니다.

## 글쓰기에 적합한 환경

### 보기 좋은 앱이 쓰기도 좋다!

Ulysses의 매력 중 하나는 **예쁩니다**. 뭐 다른 말이 필요하겠어요. 그냥 참 예쁩니다. 언젠가부터 글을 쓰는 행위에 집중할 수 있도록 minimal, distraction-free 글쓰기 앱이 상당히 많아졌습니다. 제가 즐겨쓰는 Byword도 그렇고, Scrivener도 컴포지션 모드를 사용하면 정말 군더더기 없이 글을 쓰는 데 집중할 수 있는 환경이 됩니다. Ulysses에서도 에디터 화면만 보이도록 하고 전체화면 모드를 사용하면 텅 빈 종이에 글을 쓰는 느낌으로 **”쓰기”**에 집중할 수 있습니다. 

### Typewriter 모드

편집 중인 부분을 항상 그 자리에 고정시키는 Typewriter 모드(`⌘⌥T`)도 지원합니다. 한 번 Typewriter 모드를 써보시면 시선을 계속해서 움직이지 않고 글을 쓸 수 있다는 것이 생각보다 더 집중에 도움이 되는 것을 아실 수 있을 겁니다.

다양한 테마도 적용할 수 있습니다. 기본적으로 제공하는 테마도 훌륭하지만, [테마 페이지][4]에 더 다양한 테마가 올라와 있으니 둘러보세요.

### 스플릿 뷰

![Split view of Safari and Ulysses][image-1]

스플릿 뷰를 지원하는 것도 글을 쓸 때 상당히 유용합니다. 사파리를 띄워두고 참고하면서 글을 쓰거나, Ulysses 안에 있는 글을 참고할 때도 두 글을 스플릿 뷰로 보면서 작업할 수 있습니다. 지금 이 글을 쓰면서도 위의 이미지처럼 사파리와 나란히 띄우고 작업하고 있습니다.

### 키보드 네비게이션

하나의 시트 안에 글이 길어졌을 때 `⌘8`을 눌러보세요. 시트 안에 헤딩을 목차처럼 보여주어 원하는 곳으로 빠르게 이동할 수 있습니다. 마크다운으로 헤더 레벨을 글 중간중간 사용한 경우에 유용합니다.

## 시트(Sheet), Ulysses의 문서 단위

제가 계속 Ulysses를 탐하는 이유는 블로그 글을 적는 용도에 딱 맞을 것 같아서입니다. 메모 정도의 짧은 글도 아니고 몇 개의 소제목을 포함하는 글을 적기에는 [nvALT][5], [Byword][6]와 [Scrivener][7]사이에 절묘하게 포지셔닝이 가능하지 않을까 기대합니다. 

이를 위해 중요한 것은 시트(sheet)[^2]를 작성하고 손쉽게 순서를 바꿀 수 있어야 합니다. 원하는 때에 단락을 나누고 또 합칠 수 있어야 겠죠. Ulysses에서 시트를 나누는 것은 나누고 싶은 위치에 캐럿을 위치하고 Split at Selection(`⌘⇧B`)하면 됩니다. 각 시트는 임의로 붙여서(glue) 활용할 수도 있고, 합치기(merge)도 가능합니다. 이런 과정은 Scrivener에서도 사용했던 것과 비슷해 편하게 접근할 수 있었습니다. 기본적으로 시트는 수동, 제목순, 생성 날짜 순, 수정한 날짜 순으로 정렬할 수 있습니다. 

### 그룹과 필터

라이브러리에서 그룹 안에 새로운 그룹을 만들 수 있습니다. 하위 그룹을 만드는 것도 가능합니다. 외부 폴더(Dropbox) 안에 만든 그룹은 폴더가 됩니다. 블로그를 여러 개 운영하는 경우 각 블로그마다 그룹을 만들고 그 안에 카테고리 별로 하위 그룹을 만들어 포스트를 나누어 담는 것도 가능합니다. 그룹은 보통 익숙한 폴더의 개념으로 생각하시면 되겠습니다.

또 글을 분류하는 기능으로는 필터가 있습니다. 제가 쓰는 지킬 블로그는 각 포스트가 하나의 마크다운 파일이고 `yyyy-mm-dd-post-url.md` 형식으로 모든 파일명에 발행한 날짜가 들어갑니다. 이를 이용해서 파일명에 `2016-12`가 들어간 파일을 찾도록 `2016년 12월`이라는 필터를 설정하면 2016년 12월에 발행한 글에 빠르게 접근할 수 있습니다. 파일명 외에도 파일 내에 특정 문자열이 들어가는 경우나 키워드로, 혹은 파일생성날짜나 수정한 날짜를 기준으로 필터를 만들수도 있으니 **최근 30일 내에 수정한 문서** 등의 필터도 만들 수 있습니다. 필터는 일종의 스마트 폴더라고 생각하면 될 것 같습니다.

### 키워드, 별표, 책갈피

키워드는 보통 생각하는 태그입니다. 원하는 시트를 별표(favorites)하고 나중에 보거나 책갈피(bookmark)에 추가하는 것도 가능합니다.

Ulysses에 있는 시트를 찾아 여는 가장 빠른 방법은 Quick Open(`⌘O`)으로 찾는 글을 입력하고 리턴키를 누르면 바로 해당 글이 열립니다. 그룹 내 검색, 전문 검색도 당연히 가능합니다.

## Markdown XL

![Markdown XL][image-2]

Ulysses는 기본값으로 Markdown XL라는 자체 마크다운 문법을 사용합니다. 이외 옵션으로 markdown, Minimark, Textile’d를 사용할 수 있습니다. 기본 마크다운 문법에서는 각주도 지원하지 않기에 저는 멀티마크다운 문법을 주로 사용하고 있는데, 아쉽게도 MMD는 선택지에 없습니다. 하지만 마크다운 사용자라면 Markdown XL도 금방 적응할 수 있는 정도입니다.  Ulysses내 어디서나 `⌘9`를 누르면 문법 도움말이 나와 참조할 수 있습니다. Markdown XL에서 기본 마크다운 문법에 없는 부분은 다음과 같습니다.

- Marked `::…::`
- Delete `||…||`
- Image `(img)`
- Video `(vid)`
- Footnote `(fn)`
- Annotation `{...}`
- Comment `++...++`
- Comment Block `%%`
- Raw Source `~...~`
- Raw Source Block `~~`

이 중에서 보통 블로그 글을 쓸 때 Image, Video, Footnote 정도가 많이 쓰이는데 모두 괄호 안에 각 축약어를 넣는 정도로 기억하기 편합니다. 다만 Markdown XL은 링크 주소가 바로 보이지 않고 해당 링크가 걸린 단어를 눌러야 확인할 수 있습니다. 보기에 좋지만, 불편한 점도 있는 거죠.

## Dropbox 지원

Ulysses는 기본적으로 iCloud를 사용합니다. 맥 앱과 iOS 앱이 iCloud를 통해 동기화 되죠. iOS 버전을 사용해 보지는 않았지만, 상당히 완성도 있다고 알고 있습니다. 하지만 저는 아직 iCloud가 불안정하다고 여겨서 문서를 모두 Dropbox에 넣고 동기화합니다. 

Ulysses에서는 Dropbox를 "외부 폴더 추가" 기능으로 지원합니다. 원하는 Dropbox 폴더를 추가하면 Ulysses의 라이브러리에 그룹으로 보입니다. 폴더 안에 하위 폴더가 있는 경우엔 그룹 내 하위 그룹으로 보입니다. 따로 설명이 필요 없을 정도로 직관적입니다.

![file tag for file name in Dropbox][image-3]

Dropbox에는 파일이 있기에 각 파일은 시트로 보입니다. 시트의 가장 위에 `@: 파일 이름`의 형식으로 파일명이 나옵니다. Ulysses는 각 시트가 글의 단위이지만 따로 파일이라는 개념이 없기에 Dropbox 외부 폴더에만 보이는 보이는 태그입니다.

하지만 외부 폴더인 Dropbox를 사용하는 데 따르는 제약이 있습니다.

* 파일(Ulysses에서는 시트)을 둘로 나눌 수 있지만, 두 파일을 병합할 수 없습니다.
* 이미지나 노트, 시트 별 목표, 키워드를 사용할 수 없습니다. 이미지를 주소 형식으로 링크하는 것은 가능합니다. 맥에서 드롭박스 파일에 키워드를 지정할 수는 있지만, Ulysses for iOS 에 동기화가 되지 않는다고 합니다.
* 마크다운으로 글을 쓸 때 Comments, Annotations, Delete 를 사용할 수 없습니다.

## 내보내기 & 공유하기

Ulysses에서 작성한 글을 PDF, DOCX, HTML(CSS 적용 가능), ePub, RTF로 내보낼 수 있습니다. Dropbox 외부 폴더를 추가해서 사용하는 것이 가능하니 당연히 마크다운 형식에 맞게 `.md`파일로 내보내는 것도 가능합니다.

Wordpress와 Medium으로 공유하기를 지원합니다. 따로 웹에 접속하지 않고 앱 안에서 올릴 수 있습니다. 메일로 보낼 수도 있고, 메일에 첨부할 수도 있습니다. 다른 앱으로 내보내는 것도 지원하여 여러 맥 앱으로 보낼 수 있습니다. 예를 들면, Marked 2로 내보내서 미리보기를 할 수 있습니다.[^3]

## 주의점 - 장문의 글을 한 시트에 넣으면 느려진다?

[백투더맥의 Ulysses 소개글][8]에 달린 댓글에 따르면 장문의 글을 한 시트에 작성하면 도저히 사용할 수 없을 정도로 느려진다고 합니다. 다른 사용자로부터 동일한 경험을 했다는 이야기도 들었습니다. 이에 호기심이 동하여 시험해봤습니다.

![long text in one sheet][image-4]

한글 로렘 입숨 생성기를 통해 4만 글자, 단어로 2만 단어가 약간 안 되는 정도까지 한 시트에 붙여넣고 얼마나 느려지는지 봤는데, 느려지는 것을 체감하지 못했습니다. 이렇게 길어질 정도라면 아마 여러 시트로 나누어서 쓰지 않을까 싶어서 그만할까 하다가 몇 번 더 붙여넣어 6만 단어까지 더 붙여넣고 봤을 때도 느려지는 현상은 일어나지 않았습니다. 하지만 이건 제 사용환경에서 느려지지 않은 것이기에 Ulysses를 구매를 고려하는 분이라면 체험판으로 시험해보시는 것이 좋겠습니다. 체험판은 [여기][9]에서 구하실 수 있습니다.

## 맺음말

지금까지 Ulysses for Mac을 간단히 훑었습니다. Ulysses는 한 마디로 말하자면, 매우 매력적인 앱입니다. 글을 쓰는 것은 물론 그룹, 필터, 키워드를 통해 글을 관리하는 것도 편하고, 시트를 재배치하거나 나누고 합치는 모든 과정이 부드럽게 이어집니다. Scrivener의 corkboard view 모드까지는 아니어도 상당히 편하게 사용할 수 있을 것 같습니다. 앱 안에서 여러 스타일로 실시간 미리보기를 제공하는 것과 다양한 테마는 Scrivener에는 없는 기능입니다. **“Ulysses는 Scrivener에서 딱 필요한 기능만 덜어낸 최적의 글쓰기 앱”**이라는 평가도 있다고 봤는데, 그렇게 생각할 수도 있겠다 싶습니다. 기능면으로 봤을 때는 nvALT + Byword에 Scrivener의 기능 몇 가지를 추가한 느낌도 들어요. 어쨌든 맥으로 글을 쓰는 모든 분에게 한 번쯤 사용해 보시라고 권할 만합니다. 이 글은 앞으로 Ulysses를 쓰면서 조금씩 업데이트 하겠습니다.

[^1]:	Setapp에 대해 궁금하신 분은 [이전에 쓴 글][3]을 참고해주세요. :)

[^2]:	Ulysses에서는 글의 단위를 Sheet라고 합니다. 각 sheet가 보통 생각하는 하나의 텍스트 파일이라고 생각하면 됩니다. 외부폴더에서 파일을 가져오면 각 파일이 하나의 sheet가 됩니다.

[^3]:	Ulysses 내의 미리보기를 사용하는 것은 실시간으로 Live preview가 가능합니다만, Marked 2의 강력한 미리보기 기능과 부가 기능을 원하는 경우에는 유용합니다.

[1]:	https://itunes.apple.com/kr/app/ulysses/id623795237?l=en&mt=12
[2]:	https://setapp.com/ "Setapp Your shortcut to get the best apps for Mac"
[3]:	http://www.halryang.net/Setapp/
[4]:	http://styles.ulyssesapp.com/themes/?ref=u3_markupPrefs
[5]:	http://brettterpstra.com/projects/nvalt/
[6]:	https://www.bywordapp.com/
[7]:	https://www.literatureandlatte.com/scrivener.php
[8]:	http://macnews.tistory.com/5344
[9]:	http://media.the-soulmen.com/ulyssesapp/Ulysses%20Demo.zip "Try the Mac Demo"

[image-1]:	http://dr.halryang.net/rljm+
[image-2]:	http://dr.halryang.net/a2w1+
[image-3]:	http://dr.halryang.net/qAAE+
[image-4]:	http://dr.halryang.net/bUKS+