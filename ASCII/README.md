### 시저 암호
### 문제 설명
- 어떤 문장의 각 알파벳을 일정한 거리만큼 밀어서 다른 알파벳으로 바꾸는 암호화 방식을 시저 암호라고 합니다. 예를 들어 "AB"는 1만큼 밀면 "BC"가 되고, 3만큼 밀면 "DE"가 됩니다. "z"는 1만큼 밀면 "a"가 됩니다. 문자열 s와 거리 n을 입력받아 s를 n만큼 민 암호문을 만드는 함수, solution을 완성해 보세요.

### 제한 조건
- 공백은 아무리 밀어도 공백입니다.
- s는 알파벳 소문자, 대문자, 공백으로만 이루어져 있습니다.
- s의 길이는 8000이하입니다.
- n은 1 이상, 25이하인 자연수입니다.

### 풀이 방법 1
1. 문자를 아스키코드로 바꾼다( ord함수 )
2. 아스키코드에 n만큼 더해서 문자로 바꾸어준다( chr함수 )

### 풀이 방법 2
1. 대소문자 문자열 두개를 나란히 선언한다
2. 26으로 나누어 같은 문자를 결과값에 추가한다.