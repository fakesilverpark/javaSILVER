# 컬렉션 프레임워크의 핵심 인터페이스

### 01 List
: 순서가 있는 데이터의 집합 (데이터 중복 허용)
ex - 대기자 명단

- 구현 클래스: ArrayList, LinkedList, Stack, Vector 등

### 02 Set
: 순서를 유지하지 않는 데이터 집합 (데이터 중복 허용 안함)
ex - 양의 정수집합, 소수의 집합

- 구현 클래스: HashSet, TreeSet 등

### 03 Map
: 키 (key) 와 값 (value) 의 쌍으로 이루어진 데이터 집합 (순서 유지 X, 키 - 중복 X, 값 - 중복 O)
ex - 우편번호, 전화번호

- 구현 클래스: HashMap, TreeMap, HashTable, Properties 등

#### 컬렉션 프레임워크의 모든 컬렉션 클래스들은 List, Set, Map 중의 하나를 구현하고 있으며, 구현한 인터페이스의 이름이 클래스 이름에 포함되어 있어서 이름만으로도 클래스의 특징을 쉽게 알 수 있다.