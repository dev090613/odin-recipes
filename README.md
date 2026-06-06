# odin-recipes
## 결과물
- [프로젝트의 링크](https://dev090613.github.io/odin-recipes/)
- [프로젝트에 대한 상세한 요구사항](https://www.theodinproject.com/lessons/foundations-recipes)

## About
- 유명한 오픈소스 웹 프로젝트인 ["The Odin Project"](https://www.theodinproject.com/about)의 [첫 번째 과제](https://www.theodinproject.com/lessons/foundations-recipes)이다. 아주 간단한 웹 페이지를 만들고 링크로 연결해본다.
- **해당 과제를 완료하는 과정에서 아래와 같은 기술을 적용하였다.**

## Learn
- index.html을 포함하여 웹 사이트의 초기 구조를 작성할 수 있다.
- Emmet 설정하기(LSP 설치 및 등록):
    1. :Mason 창에서 LSP(emmet-language-server)를 설치(실행 파일 다운로드)한다.
    2. `~/.config/nvim/init.lua` 파일의 servers 테이블에 `emmet_language_server = {}` 코드를 추가하여 LSP를 등록한다.
- `<a>` 태그를 사용하여 서로 다른 웹 페이지를 연결할 수 있다.
- Tailscale로 서로 다른 기기를 연결하며, 로컬 머신에서 원격으로 개발할 수 있다.
- Tailsclae 네트워크에 속한 기기 간에 이미지 파일을 전송하고 수신할 수 있다.
- 웹페이지에 이미지를 삽입할 수 있다. (`<img>` 태그를 사용하여)
- 적절한 헤딩 크기를 결정하여 웹 페이지의 계층 구조를 구분할 수 있다.
- `<ul>` 태그와 `<ol>` 태그를 구분하여 목록을 작성할 수 있다.
- Telescope을 사용하여 Git braches를 전환하며 작업할 수 있다.
- Github 저장소에서 웹 프로젝트를 직접 배포할 수 있다.


## Assignment(과제)
### Step 1. Iteration 1: initial structure(초기 구조 잡기)
- 보일러 플레이트를 생성한 후, `index.html` file 을 생성한다.
- “Odin Recipes”(`h1`)을 추가한다.

### Step 2. Iteration 2: recipe page(레시피 페이지 만들기)
1. 새 Directory(`odin-recipes/recipes/`)를 만든다.
2. 레시피의 이름을 따서 파일을 생성한다. 예를 들어서 `steamed-eggs.html`. 해당 파일은 기본 HTML 템플릿을 포함해야 한다.
3. 일단 이 파일(레시피 페이지)은 레시피 이름을 내용으로 하는 `<h1>` 헤딩만 포함한다.
4. `index.html` 파일에 레시피 페이지로 연결되는 링크를 추가한다.
5. 레시피 페이지에 인덱스 페이지로 돌아가는 링크를 추가한다.

### Step 3. Iteration 3: recipe page content(레시피 페이지 내용 채우기)
1. 이전에 추가한 `<h1>` 헤딩 아래에 완성된 요리의 무료 이미지(저작권 프리 이미지)를 넣는다.
2. 이미지 아래에 "Description"(설명) 헤딩을 넣고, 레시피를 설명하는 한두 개의 단락(paragraph)을 추가한다.
3. "Ingredients"(재료) 헤딩을 추가한 다음, 레시피에 필요한 재료들을 순서 없는 목록(`<ul>`)으로 나열한다.
4. 마지막으로, "Steps"(조리 순서) 헤딩을 추가하고 요리를 만들기 위한 단계들을 순서 있는 목록(`<ol>`)으로 나열한다.

### Step 4. Iteration 4: add more recipes(레시피 추가하기)
1. 이미 만든 레시피 페이지와 동일한 페이지 구조를 가진 레시피를 두 개 더 추가한다.
2. `index.html` 페이지에 새 레시피로 연결되는 링크를 추가한다. 또한, 모든 링크이 간격을 가질 수 있도록 순서 없는 목록(`<ul>`) 안에 넣는다.

### 기타

- 레시피 참고 자료: [만개의레시피](https://www.10000recipe.com/index.html)
