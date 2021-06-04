## Dart 기초 문법 정리

### 자료형

int, string, var  같은 자료형은 코틀린과 동일하다.

**dynamic** - 자동으로 자료형에 따라 변경한다.

**final** - 선언 후 데이터를 변경할 수 없다.

```dart
void main (){
	var a = l;
	dynamic b = 2;
	final c = 3;
	
	print(a.runtimeType); //int
	print(b.runtimeType); //int
	print(c.runtimeType); //int
	
	b = 3.14;
	c = 4; //final로 선언했기 때문에 오류
	
	print(b.runtimeType); //double
}
```

### 문자열

