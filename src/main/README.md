## 한글 오탈자 교정을 위한 토큰 필터입니다.

### Enviroment
- Elasticsearch version: 7.13.2
- Build JDK: JDK 11 azul
- Language: Java

### Components
- 자소분리 필터
- 초성 필터
- 한 -> 영 변환 필터
- 영 -> 한 변환 필터

### 사용법

analyzer 생성시 tokenizer는 Nori tokenizer를 적용하고, 필터를 위의 컴포넌트들을 추가하여 분석기를 구성한다.