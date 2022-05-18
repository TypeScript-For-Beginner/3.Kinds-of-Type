# 3장 Kinds-of-Type

자바스크립트에는 없는 타입스크립트만의 고유한 개념 중 가장 핵심이 되는 것은 타입이다. 타입스크립트와 자바스크립트는 서로 호환되어야 한다. 이를 위해 타입스크립트는 자바스크립트가 사용하는 타입은 물론 타입스크립트의 타입도 사용할 수 있게 제공하고 있다. 

## 14.1 자바스크립트와 타입스크립트의 기본 타입

|타입의 종류|JavaScript|TypeScript|
|------|---|---|
|수|Number|number|
|불리언|Boolean|boolean|
|문자열|String|string|
|객체|Object|object|

 타입스크립트는 기본적으로 12가지 타입을 가지고 있다.
 ```
boolean
bumber
string
object
array
tuple
enum
any
void
null
undefined
never
 ```
  이 타입들로 자바스크립트의 변수, 함수 따위의 코드에 타입을 정의할 수 있다.



