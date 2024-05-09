Any : 모든 타입을 지칭

AnyObject : 모든 클래스의 타입 지칭하는 프로토콜

nil : 없음을 의미

## Any

데이터 타입의 위치에 들어갈 수 있다

모든 타입 수용 가능

## AnyObject

class 인스턴스

ex)

```swift
class SomeClass {}
var someAnyObject: AnyObject = SomeClass()
```

## nil

Any 에는 못 들어감 (Any는 빈 값은 못 들어감)

null 과 유사