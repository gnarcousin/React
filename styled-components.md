## styled-components 라이브러리

`yarn add styled-components` 명령어로 설치

### 적용, 변수 설정
```javascript
import styled from 'styled-components';

const 변수명 = styled.(html)태그`
  HTML 태그 적용 가능
`
```

### 사용법 예시

```javascript
<div>
  <변수명>
    내용
  </변수명>
</div>
```

### styled-components 사용시 원하는 값을 props로 넘겨받을 수 있다.

```javascript
const 변수명 = styled.(html)태그`
  ${props => props.isRed && `
  color: red
`

//속성을 주지 않아도 기본 false 상태로 돌아감
<변수명 isRed={true}>
  내용
</변수명>

```
