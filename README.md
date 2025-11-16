# Scheme-Lisp-Scala-Haskell-Clojure-Groovy  
**The Ultimate Functional Programming Fusion Project**  
**함수형 패러다임 극대화 실험실**

프런트엔드 언어 → SpongeLang 백엔드로 컴파일되는  
함수형·리습·정적·동적 패러다임 융합 실험 프로젝트.

이 언어는 Scheme/Lisp의 최소 코어,  
Haskell·Scala의 타입·의미 기반 구조,  
Clojure·Groovy의 동적·데이터 중심 철학을  
**단일 의미 체계(semantic core)** 안에서 결합한다.

최종 출력은 **SpongeLang IR → NASM/native**,  
런타임은 SpongeLang Meaning-Level Engine을 사용한다.

---

## 아키텍처




[Source Code]
↓
Parser (Lisp/Scala Hybrid)
↓
Semantic Layer (Type inference + Pattern match)
↓
SpongeLang IR Generator
↓
[SpongeLang VM / SpongeLang → NASM]
↓
Native Binary



---

## 언어 목표

### Lisp/Scheme Core  
- prefix 기반  
- hygienic macro  
- minimal kernel  

### Haskell/Scala Semantic System  
- 선택형 정적 타입  
- 타입 추론  
- 패턴 매칭  
- 의미 기반 타입 시행  

### Clojure Data Philosophy  
- immutable-first  
- literal 중심  
- REPL 친화  

### Groovy Dynamic Flavor  
- dynamic-first  
- script-first 실행  

---

## SpongeLang 백엔드

- Meaning-Level Runtime  
- All-is-Heap 메모리 모델  
- SpongeLang IR 기반 multi-stage compilation  
- 구조적/의미 기반 최적화(pass) 자동 적용  

---

## 예제 코드

### Lisp 스타일



(def square (x) (* x x))



### Scala/Haskell 스타일



square = x -> x * x



### 패턴 매칭



(match value
(0 -> "zero")
((x > 0) -> "positive")
(_ -> "other"))



---

## 빌드 / 실행 흐름




yourlangc input.your → output.sp
spongevm --emit-nasm output.sp → output.asm
nasm -felf64 output.asm
ld output.o -o app
./app



---

## 상태
- 초기 설계 단계  
- 파서/타입 시스템 구축 중  
- SpongeLang 백엔드 연동 구조 확정됨 

---

## 라이선스
MIT


