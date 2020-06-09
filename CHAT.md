# 대화 키보드

## Body: 
```json
{
    "type": <"keyboard"|"all_friend"|"friend">
    "body": string|number|true|false
    "userId": <Friend id>
}
```
### 사용 가능 문자
일반 문자
닌텐도가 추가한 개인 사용 영역

### 사용 불가 문자 (상단 왼쪽 🚫표시)
Emoji
\n

### 무시되는 문자
\b
\r
\n

### 참고
\u0000 이후의 문자는 무시 됨 '(길게\u0000누르면)' -> '(길게'
〔\u000e\u0000\u0003\u0002\u0001PRO 디자인\u000e\u0000\u0003\u0002\uFFFF〕
