# 마크다운(Markdwon)

>일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서 정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다.



## 1. 문법

### 1.1 Header

> 헤더는 제목을 표현할 때 사용합니다. 단순히 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다.

* `<h1>` 부터 `<h6>`까지 표현가능합니다.
* `#` 의 개수로 표현하거나 `<h1></h1>`의 형태로 표현 가능합니다.



# h1 태그입니다.

## h2 태그입니다.
###  h3 태그입니다.
#### h4 태그입니다.
##### h5 태그입니다.
###### h6 태그입니다.



### 1.2 List

> 목록을 나열할 때 사용합니다. 순서가 필요한 항목과 그렇지 않은 항목으로 구별할 수 있습니다. 순서가 있는 항목 아래 순서가 없는 항목을 지정할 수 있으며 그 반대도 가능합니다.

- 순서가 있는 목록

  - `1.`을 누르고 스페이스바를 누르면 생성할 수 있습니다.
  - `tab`키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동할 수 있습니다.

- 순서가 없는 목록

  - `-`(하이픈)을 쓰고 스페이스바를 누르면 생성할 수 있습니다.

  - `tab`키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab`키를 눌러서 상위 항목으로 이동할 수 있습니다.

    

1. 순서가 있는 항목
2. 순서가 있는 항목
   1. 순서가 있는 하위 항목
   2. 순서가 있는 하위 항목



- 순서가 없는 항목
- 순서가 없는 항목
  - 순서가 없는 하위 항목
  - 순서가 없는 하위 항목



### Code Block

> 코드 블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼 때 사용합니다. 인라인과 블럭 단위로 구분 할 수 있습니다.

- Inline
  - 인라인 블럭으로 처리하고 싶은 부분을 `(백틱)으로 감싸줍니다.
- Block
  - ` (백틱)을 3번 입력하고 ``Enter``를 눌러 생성합니다



`add`한 요소를 remote 저장소에 올리려면 `$ git push origin master`를 터미널에 입력합니다

```bash
$ git add .
$ git commit -m 'first commit'
$ git push origin master
```



#### 1.4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 활용하여 이미지를 나타낼 때 사용합니다.

- `![]()`을 작성하고 `()`안에 이미지 주소를 입력합니다. `[]` 안에는 이미지 파일의 이름을 작성합니다.
- 로컬에 이미 파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장합니다.

![dd](data:image/png;base64,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 )

![d](data:image/png;base64,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)





<img src="C:\Users\ShinDongWha\Desktop\qr.png" ;" />



### 1.5 Link

> 특정 주소를 링크를 걸 때 사용합니다

- `[]()`을 작성하고 `()` 안에 링크 주소를 작성하고 `[]`안에 어떤 링크 주소인지 작성합니다



[git 공식문서]()

[github 공식문서]()



### 1.6 Table

> 표를 작성하여 요소를 구분할 수 있습니다

- `|`(파이프) 사이에 컬럼을 작성하고 `enter`를 입력합니다
- 마지막 컬럼을 작성하고 뒤에 `|` 를 붙여줍니다



| working directory | statgint area | remoe repo |
| ----------------- | ------------- | ---------- |
| working tree      | index         | history    |
| working copy      | cache         | tree       |



### 1.7 기타

#### 인용문

- `>`을 입력하고 `enter`키를 누릅니다

> git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다.

- 인용문 안에 인용문을 작성하면 중첩해서 사용할 수 있습니다.

> $ git add .
>
> > $ git commit -m 'first commit'
> >
> > > $ git push origin master



#### 수평선

- `---`, `***`, `___`을 입력하여 작성합니다.

Working Directory

---

Staging Area

***

Remote Repository

___



#### 강조

- 이텔릭체는 해당부분을 `*` 혹은`_`(언더바)로 감싸줍니다.
- 보드체는 해당 부분을 `**`혹은`__`(언더바 2개)로 감싸줍니다.
- 취소선은 `~~`표시를 사용합니다.

이것은 _이텔릭체_입니다.

이것은 __보드체__입니다.

이것은 ~~취소선~~입니다.



### 2. 과제

> 현재의 pdf 문서를 마크다운 문법을 활용하여 `00_markdown_basic.md`로 만들어 보세요.

