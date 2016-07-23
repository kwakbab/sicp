# SICP 릴레이 문제 풀이

## 순서

- 김은민 todd 
- 오광수 andy
- 곽윤도 lester `1.3 진행중`
- 전다영글 hogle
- 이민선 joony
- 김세시나 amy
- 김용훈 poet

## 읽기표

     
|3.3.1 변형 가능한 리스트                                                |   |   |   |   |   |   |   |  
|3.3.2 큐                                                                |   |   |   |   |   |   |   |   
|3.3.3 표                                                                |   |   |   |   |   |   |   |
|3.3.4 디지털 회로 시뮬레이터                                            |   |   |   |   |   |   |   |                    
|3.3.5 관계 알리기(constraint propagation)                               |   |   |   |   |   |   |   |                   
|3.4 병행성竝行性 : 시간은 중요하다                                      |   |   |   |   |   |   |   |
|3.4.1 병행 시스템에서 시간의 성질본질                                   |   |   |   |   |   |   |   |                    
|3.4.2 병행성을 다스리는 방법                                            |   |   |   |   |   |   |   |                    
|3.5 스트림                                                              |   |   |   |   |   |   |   |   
|3.5.1 스트림과 (계산을) 미룬 리스트                                     |   |   |   |   |   |   |   |                  
|3.5.2 무한 스트림(infinite stream)                                      |   |   |   |   |   |   |   |               
|3.5.3 스트림 패러다임                                                   |   |   |   |   |   |   |   |             
|3.5.4 스트림과 셈미룸 계산법                                            |   |   |   |   |   |   |   |                   
|3.5.5 모듈로 바라본 함수와 물체                                         |   |   |   |   |   |   |   |                   

## 문제표

| 문제 | 김은민 | 오광수 | 곽윤도 | 전다영글 | 이민선 | 김세시나 | 김용훈 | 릴레이 주자 링크 |
| ---- | ------ | ------ | ------ | -------- | ------ | -------- | ------ | ---------- |
| 1.1  |    ✔   |        |        |          |    ✔   |          |        | [ex_1_1.clj](https://github.com/eunmin/sicp/blob/master/src/sicp/todd/ex_1_1.clj)
| 1.2  |        |        |        |          |    ✔   |          |        | [ex_1_2.clj](https://github.com/eunmin/sicp/blob/master/src/sicp/andy/ex_1_2.clj)
| 1.3  |        |        |        |          |    ✔   |          |        |
| 1.4  |        |        |        |          |        |          |        |
| 1.5  |        |        |        |          |        |          |        |
| 1.6  |        |        |        |          |        |          |        |
| 1.7  |        |        |        |          |        |          |        |
| 1.8  |        |        |        |          |        |          |        |
| 1.9  |        |        |        |          |        |          |        |
| 1.10 |        |        |        |          |        |          |        |
| 1.11 |        |        |        |          |        |          |        |
| 1.12 |        |        |        |          |        |          |        |
| 1.13 |        |        |        |          |        |          |        |
| 1.14 |        |        |        |          |        |          |        |
| 1.15 |        |        |        |          |        |          |        |
| 1.16 |        |        |        |          |        |          |        |
| 1.17 |        |        |        |          |        |          |        |
| 1.18 |        |        |        |          |        |          |        |
| 1.19 |        |        |        |          |        |          |        |
| 1.20 |        |        |        |          |        |          |        |
| 1.21 |        |        |        |          |        |          |        |
| 1.22 |        |        |        |          |        |          |        |
| 1.23 |        |        |        |          |        |          |        |
| 1.24 |        |        |        |          |        |          |        |
| 1.25 |        |        |        |          |        |          |        |
| 1.26 |        |        |        |          |        |          |        |
| 1.27 |        |        |        |          |        |          |        |
| 1.28 |        |        |        |          |        |          |        |
| 1.29 |        |        |        |          |        |          |        |
| 1.30 |        |        |        |          |        |          |        |
| 1.31 |        |        |        |          |        |          |        |
| 1.32 |        |        |        |          |        |          |        |
| 1.33 |        |        |        |          |        |          |        |
| 1.34 |        |        |        |          |        |          |        |
| 1.35 |        |        |        |          |        |          |        |
| 1.36 |        |        |        |          |        |          |        |
| 1.37 |        |        |        |          |        |          |        |
| 1.38 |        |        |        |          |        |          |        |
| 1.39 |        |        |        |          |        |          |        |
| 1.40 |        |        |        |          |        |          |        |
| 1.41 |        |        |        |          |        |          |        |
| 1.42 |        |        |        |          |        |          |        |
| 1.43 |        |        |        |          |        |          |        |
| 1.44 |        |        |        |          |        |          |        |
| 1.45 |        |        |        |          |        |          |        |
| 1.46 |        |        |        |          |        |          |        |
| 2.1  |        |        |        |          |        |          |        |
| 2.2  |        |        |        |          |        |          |        |
| 2.3  |        |        |        |          |        |          |        |
| 2.4  |        |        |        |          |        |          |        |
| 2.5  |        |        |        |          |        |          |        |
| 2.6  |        |        |        |          |        |          |        |
| 2.7  |        |        |        |          |        |          |        |
| 2.8  |        |        |        |          |        |          |        |
| 2.9  |        |        |        |          |        |          |        |
| 2.10 |        |        |        |          |        |          |        |
| 2.11 |        |        |        |          |        |          |        |
| 2.12 |        |        |        |          |        |          |        |
| 2.13 |        |        |        |          |        |          |        |
| 2.14 |        |        |        |          |        |          |        |
| 2.15 |        |        |        |          |        |          |        |
| 2.16 |        |        |        |          |        |          |        |
| 2.17 |        |        |        |          |        |          |        |
| 2.18 |        |        |        |          |        |          |        |
| 2.19 |        |        |        |          |        |          |        |
| 2.20 |        |        |        |          |        |          |        |
| 2.21 |        |        |        |          |        |          |        |
| 2.22 |        |        |        |          |        |          |        |
| 2.23 |        |        |        |          |        |          |        |
| 2.24 |        |        |        |          |        |          |        |
| 2.25 |        |        |        |          |        |          |        |
| 2.26 |        |        |        |          |        |          |        |
| 2.27 |        |        |        |          |        |          |        |
| 2.28 |        |        |        |          |        |          |        |
| 2.29 |        |        |        |          |        |          |        |
| 2.30 |        |        |        |          |        |          |        |
| 2.31 |        |        |        |          |        |          |        |
| 2.32 |        |        |        |          |        |          |        |
| 2.33 |        |        |        |          |        |          |        |
| 2.34 |        |        |        |          |        |          |        |
| 2.35 |        |        |        |          |        |          |        |
| 2.36 |        |        |        |          |        |          |        |
| 2.37 |        |        |        |          |        |          |        |
| 2.38 |        |        |        |          |        |          |        |
| 2.39 |        |        |        |          |        |          |        |
| 2.40 |        |        |        |          |        |          |        |
| 2.41 |        |        |        |          |        |          |        |
| 2.42 |        |        |        |          |        |          |        |
| 2.43 |        |        |        |          |        |          |        |
| 2.44 |        |        |        |          |        |          |        |
| 2.45 |        |        |        |          |        |          |        |
| 2.46 |        |        |        |          |        |          |        |
| 2.47 |        |        |        |          |        |          |        |
| 2.48 |        |        |        |          |        |          |        |
| 2.49 |        |        |        |          |        |          |        |
| 2.50 |        |        |        |          |        |          |        |
| 2.51 |        |        |        |          |        |          |        |
| 2.52 |        |        |        |          |        |          |        |
| 2.53 |        |        |        |          |        |          |        |
| 2.54 |        |        |        |          |        |          |        |
| 2.55 |        |        |        |          |        |          |        |
| 2.56 |        |        |        |          |        |          |        |
| 2.57 |        |        |        |          |        |          |        |
| 2.58 |        |        |        |          |        |          |        |
| 2.59 |        |        |        |          |        |          |        |
| 2.60 |        |        |        |          |        |          |        |
| 2.61 |        |        |        |          |        |          |        |
| 2.62 |        |        |        |          |        |          |        |
| 2.63 |        |        |        |          |        |          |        |
| 2.64 |        |        |        |          |        |          |        |
| 2.65 |        |        |        |          |        |          |        |
| 2.66 |        |        |        |          |        |          |        |
| 2.67 |        |        |        |          |        |          |        |
| 2.68 |        |        |        |          |        |          |        |
| 2.69 |        |        |        |          |        |          |        |
| 2.70 |        |        |        |          |        |          |        |
| 2.71 |        |        |        |          |        |          |        |
| 2.72 |        |        |        |          |        |          |        |
| 2.73 |        |        |        |          |        |          |        |
| 2.74 |        |        |        |          |        |          |        |
| 2.75 |        |        |        |          |        |          |        |
| 2.76 |        |        |        |          |        |          |        |
| 2.77 |        |        |        |          |        |          |        |
| 2.78 |        |        |        |          |        |          |        |
| 2.79 |        |        |        |          |        |          |        |
| 2.80 |        |        |        |          |        |          |        |
| 2.81 |        |        |        |          |        |          |        |
| 2.82 |        |        |        |          |        |          |        |
| 2.83 |        |        |        |          |        |          |        |
| 2.84 |        |        |        |          |        |          |        |
| 2.85 |        |        |        |          |        |          |        |
| 2.86 |        |        |        |          |        |          |        |
| 2.87 |        |        |        |          |        |          |        |
| 2.88 |        |        |        |          |        |          |        |
| 2.89 |        |        |        |          |        |          |        |
| 2.90 |        |        |        |          |        |          |        |
| 2.91 |        |        |        |          |        |          |        |
| 2.92 |        |        |        |          |        |          |        |
| 2.93 |        |        |        |          |        |          |        |
| 2.94 |        |        |        |          |        |          |        |
| 2.95 |        |        |        |          |        |          |        |
| 2.96 |        |        |        |          |        |          |        |
| 2.97 |        |        |        |          |        |          |        |
| 3.1  |        |        |        |          |        |          |        |
| 3.2  |        |        |        |          |        |          |        |
| 3.3  |        |        |        |          |        |          |        |
| 3.4  |        |        |        |          |        |          |        |
| 3.5  |        |        |        |          |        |          |        |
| 3.6  |        |        |        |          |        |          |        |
| 3.7  |        |        |        |          |        |          |        |
| 3.8  |        |        |        |          |        |          |        |
| 3.9  |        |        |        |          |        |          |        |
| 3.10 |        |        |        |          |        |          |        |
| 3.11 |        |        |        |          |        |          |        |
| 3.12 |        |        |        |          |        |          |        |
| 3.13 |        |        |        |          |        |          |        |
| 3.14 |        |        |        |          |        |          |        |
| 3.15 |        |        |        |          |        |          |        |
| 3.16 |        |        |        |          |        |          |        |
| 3.17 |        |        |        |          |        |          |        |
| 3.18 |        |        |        |          |        |          |        |
| 3.19 |        |        |        |          |        |          |        |
| 3.20 |        |        |        |          |        |          |        |
| 3.21 |        |        |        |          |        |          |        |
| 3.22 |        |        |        |          |        |          |        |
| 3.23 |        |        |        |          |        |          |        |
| 3.24 |        |        |        |          |        |          |        |
| 3.25 |        |        |        |          |        |          |        |
| 3.26 |        |        |        |          |        |          |        |
| 3.27 |        |        |        |          |        |          |        |
| 3.28 |        |        |        |          |        |          |        |
| 3.29 |        |        |        |          |        |          |        |
| 3.30 |        |        |        |          |        |          |        |
| 3.31 |        |        |        |          |        |          |        |
| 3.32 |        |        |        |          |        |          |        |
| 3.33 |        |        |        |          |        |          |        |
| 3.34 |        |        |        |          |        |          |        |
| 3.35 |        |        |        |          |        |          |        |
| 3.36 |        |        |        |          |        |          |        |
| 3.37 |        |        |        |          |        |          |        |
| 3.38 |        |        |        |          |        |          |        |
| 3.39 |        |        |        |          |        |          |        |
| 3.40 |        |        |        |          |        |          |        |
| 3.41 |        |        |        |          |        |          |        |
| 3.42 |        |        |        |          |        |          |        |
| 3.43 |        |        |        |          |        |          |        |
| 3.44 |        |        |        |          |        |          |        |
| 3.45 |        |        |        |          |        |          |        |
| 3.46 |        |        |        |          |        |          |        |
| 3.47 |        |        |        |          |        |          |        |
| 3.48 |        |        |        |          |        |          |        |
| 3.49 |        |        |        |          |        |          |        |
| 3.50 |        |        |        |          |        |          |        |
| 3.51 |        |        |        |          |        |          |        |
| 3.52 |        |        |        |          |        |          |        |
| 3.53 |        |        |        |          |        |          |        |
| 3.54 |        |        |        |          |        |          |        |
| 3.55 |        |        |        |          |        |          |        |
| 3.56 |        |        |        |          |        |          |        |
| 3.57 |        |        |        |          |        |          |        |
| 3.58 |        |        |        |          |        |          |        |
| 3.59 |        |        |        |          |        |          |        |
| 3.60 |        |        |        |          |        |          |        |
| 3.61 |        |        |        |          |        |          |        |
| 3.62 |        |        |        |          |        |          |        |
| 3.63 |        |        |        |          |        |          |        |
| 3.64 |        |        |        |          |        |          |        |
| 3.65 |        |        |        |          |        |          |        |
| 3.66 |        |        |        |          |        |          |        |
| 3.67 |        |        |        |          |        |          |        |
| 3.68 |        |        |        |          |        |          |        |
| 3.69 |        |        |        |          |        |          |        |
| 3.70 |        |        |        |          |        |          |        |
| 3.71 |        |        |        |          |        |          |        |
| 3.72 |        |        |        |          |        |          |        |
| 3.73 |        |        |        |          |        |          |        |
| 3.74 |        |        |        |          |        |          |        |
| 3.75 |        |        |        |          |        |          |        |
| 3.76 |        |        |        |          |        |          |        |
| 3.77 |        |        |        |          |        |          |        |
| 3.78 |        |        |        |          |        |          |        |
| 3.79 |        |        |        |          |        |          |        |
| 3.80 |        |        |        |          |        |          |        |
| 3.81 |        |        |        |          |        |          |        |
| 3.82 |        |        |        |          |        |          |        |

## 문제 풀고 올리는 방법

### leiningen 설치
```bash
brew install leiningen
==> Downloading https://homebrew.bintray.com/bottles/leiningen-2.6.1.el_capitan.bottle.tar.gz
######################################################################## 100.0%
==> Pouring leiningen-2.6.1.el_capitan.bottle.tar.gz
==> Caveats
Dependencies will be installed to:
  $HOME/.m2/repository
To play around with Clojure run `lein repl` or `lein help`.

Bash completion has been installed to:
  /usr/local/etc/bash_completion.d

zsh completion has been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/leiningen/2.6.1: 8 files, 14.7M
```

### 프로젝트 clone
```
git clone https://github.com/eunmin/sicp.git
```

### 문제 풀어서 올리는 방법

- `연습문제 1.1`를 푼다고 하면 `src/sicp/자기아이디/ex_1_1.clj` 파일을 만들고 아래와 같은 형식으로 파일을 작성합니다.

```clojure
(ns sicp.자기아이디.ex-1-1)

(def 문제
  "두 숫자를 인자로 받아 두 값을 덧셈하여 내놓는 프로시저를 정의하라.")

;; 아래에 자유롭게 연습 문제 코드를 작성합니다.
(defn add [x y]
  (+ x y))
```

- 파일명은 _이고 `ns` 옆에 붙는 것은 - 인 것에 주의하세요.
- 서술형 문제인 경우 주석 `;; ` 뒤에 작성합니다.

### 문제 실행해 보기

- 프로젝트 최상위 폴더에서 아래와 같이 명령어를 입력해 REPL을 실행합니다.
```bash
lein repl
```

- 내가 작성한 연습문제를 로딩합니다.
```bash
user=> (ns sicp.자기아이디.ex-1-1)
sicp.자기아이디.ex-1-1=> (load "ex_1_1")
sicp.자기아이디.ex-1-1=> (add 1 2)
3
sicp.자기아이디.ex-1-1=>
```

- 파일을 고치고 다시 실행하려면 다시 로드 합니다.
```bash
sicp.자기아이디.ex-1-1=> (load "ex_1_1")
sicp.자기아이디.ex-1-1=> (add3 1 2)
6
sicp.자기아이디.ex-1-1=>
```

### 문제 파일을 다 작성하면 커밋 후 Push 하고 단톡방에 다했다고 메시지를 남깁니다.
