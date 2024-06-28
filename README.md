<!--

If you're reading this then you might be looking for the hidden examples page...

CONGRATULATIONS! You found it!
Here it is: https://github.com/TodePond/DreamBerd/blob/main/res/res/Examples.md

-->

> **새롭게 두둥장:** [DreamBerd는 이제 리치 텍스트를 지원해요!](https://github.com/TodePond/DreamBerd/releases/tag/v£.££)

[<img align="right" height="100" src="shapes.png">](https://github.com/TodePond/DreamBerd/blob/main/examples/Examples.md "Click here for the examples page.")

# DreamBerd

![Coverage](badges/coverage-109.svg)

DreamBerds는 완벽한 프로그래밍 언어에요. 한 번 기능들을 보시죠!<br>
모든 기능들을 살펴 보았다면, 여기서 예제들도 살펴 보세요. [예제](https://github.com/TodePond/DreamBerd/blob/main/Examples.md)

## 느낌표!

담대해지세요! 모든 라인 끝은 느낌표로 끝나요!

```java
print("Hello world")!
```

미칠듯하게 담대해지고 싶다면, 더 많은 느낌표를 사용해도 됩니다!!!

```java
print("Hello world")!!!
```

확신이 들지 않는다고요? 괜찮습니다. 느낌표 대신, 물음표를 넣어 보세요. 이제는 더 이상 TODO 주석이 필요가 없죠.

```java
print("Hello world")?
```

혹시 DreamBerd에서는 'not' 연산자 무엇으로 사용할지 걱정이 들고, 궁금하시지 않나요? 간단합니다. 세미콜론을 사용하세요.

```java
if (;false) {
   print("Hello world")!
}
```

## 선언 (Declarations)

네 가지의 선언 방법이 있어요. const const는 어떤 방법으로도 바뀔 수 없답니다.

```java
const const name = "Luke"!
```

값은 변하지만, 재할당 될 수는 없죠.

```java
const var name = "Luke"!
name.pop()!
name.pop()!
```

어허, 값은 변하지 않아도, 재할당 될 수 있다고요.

```java
var const name = "Luke"!
name = "Lu"!
```

var var는 값도 변하고, 재할당 될 수 있답니다.

```java
var var name = "Luke"!
name = "Lu"!
name.push("k")!
name.push("e")!
```

## 불변 데이터 (Immutable Data)

**2023년에 새로운 두둥장**<br>
불변 데이터는 안티 패턴이에요. 대신에 `const const const` 키워드를 사용하세요. 진정한 의미의 불변이 되고 _절대로_ 변하지 않을 거에요. 다만 주의해주세요. 이 키워드는 모든 사람들에게 영향을 미칠만큼 굉장히 강력해요.

```java
const const const pi = 3.14!
```

## 네이밍 (Naming)

변수와 상수의 이름으로 드디어 유니코드를 지원해요! 따라서 이모지도 가능하죠!

```java
const const letter = 'A'!
var const 👍 = True!
var var 1️⃣ = 1!
```

숫자도 돼요! 정말 놀랍지 않나요!?

```java
const const 5 = 4!
print(2 + 2 === 5)! //true
```

## 배열 (Arrays)

프로그래밍 언어의 배열의 인덱스는 `0`부터 시작하죠. 초심자들에게는 굉장히 직관적이지 못해요. 또 어떤 언어는 `1`부터 시작하죠. 이 두 가지 방법들이 실제로 어떻게 동작하는지 말해주진 않아요. DreamBerd는 완벽한 균형을 찾았습니다. 바로, 배열의 인덱스는 `-1`으로 시작합니다.

```java
const const scores = [3, 2, 5]!
print(scores[-1])! //3
print(scores[0])!  //2
print(scores[1])!  //5
```

**2022년에 새로운 두둥장**<br>
이제 소숫점도 인덱스로 사용할 수 있어요!

```java
const var scores = [3, 2, 5]!
scores[0.5] = 4!
print(scores)! //[3, 2, 4, 5]
```

## 웬? (When)

변수가 변할 때마다 확인 하고 싶을 때 `when` 키워드가 제 맛이에요.

```java
const var health = 10!
when (health = 0) {
   print("You lose")!
}
```

## 변수의 수명 (Lifetimes)

DreamBerd는 빌트인 가비지 컬렉터가 있지만, 우리는 가끔 가비지 콜렉터를 믿지 못할 때가 있어요. 그럴 때 이렇게 해보세요. 다양한 단위로 변수의 수명을 정해볼 수 있어요.

```java
const const name<2> = "Luke"! //두 번째 라인까지 메모리에 남아 있답니다.
const const name<20s> = "Luke"! //20초 동안 메모리에 남아 있답니다.
```

기본 값으로, 변수는 프로그램이 종료될 때까지 남아 있어요. 하지만, 명확히 해주고 싶을 때가 있죠?

```java
const const name<Infinity> = "Luke"! //영원히 지속된다고요?
```

변수의 호이스팅은 제법 괜찮은 방법으로 할 수 있어요. 음수로 변수의 수명을 정해서, 생성 이전에 존재하게 해봐요. 그러면 생성 이후에는 사라지게 되죠.

```java
print(name)! //Luke
const const name<-1> = "Luke"!
```

## 루프 문(Loops)

루프 문은 정말이지 프로그래밍 언어의 낡은 유물이에요. 가장 완벽한 언어인 DreamBerd에서는 루프 문이 없어요.

## 설치 (Installation)

DreamBerd를 설치 하기 위해서는 DreamBerd Installer를 설치 해야 해요. <br>
DreamBerd Installer를 설치 하기 위해서는 DreamBerd Installer Installer를 설치(Install) 해야해요.

**2022년에 새로운 두둥장**<br>
이런 복잡한 설치(Install) 과정 때문에, 이제 `Create DreamBerd App`이라는 App만 설치 하면 돼요!

## Booleans

Booleans는 `true`, `false` 또는 `maybe`가 될 수 있어요.

```java
const var keys = {}!
addEventListener("keydown", (e) => keys[e.key] = true)!
addEventListener("keyup", (e) => keys[e.key] = false)!

function isKeyDown(key) => {
   if (keys[key] = undefined) {
      return maybe!
   }
   return keys[key]!
}
```

**기술 안내:** Booleans는 `1.5bits`으로 처리합니다.

## 산술

DreamBerd whitespace에 대해 놀라운 철학을 가지고 있어요. DreamBerd에서 수학적인 계산의 순서를 정하기 위해 whitespace를 사용하세요.

```java
print(1 + 2*3)! //7
print(1+2 * 3)! //9
```

DreamBerd는 자랑스럽게 분수도 지원하고 있어요.

```java
const const half = 1/2!
```

당연히, 숫자 이름도 쓸 수 있어요.

```java
print(하나 + 둘)? //3 역자: i18n에 대한 대응 필요
```

## 들여쓰기 (Indents)

들여쓰기에 대해 논하자면, DreamBerd는 굉장히 행복해요. 모두가 이제 3개의 스페이스바로 들여 쓰면 되기 때문이에요.

```java
function main() => {
   print("DreamBerd is the future")!
}
```

음수 스페이스바, `-3 스페이스바`도 당연히 허용 돼요.

```java
   function main() => {
print("DreamBerd is the future")!
   }
```

## 동등 값 (Equality)

JavaScript는 다른 수준에서 비교를 할 수 있게 해요. `==`는 느슨한 비교이고, `===` 보다 정확한 비교이죠. DreamBerd는 이것을 어나더 레벨로 끌어 올렸어요.
느슨한 비교를 할 때는 `==` 사용할 수 있어요.

```java
3.14 == "3.14"! //true
```

보다 정확한 비교를 할 때는 `===`를 사용할 수 있어요.

```java
3.14 === "3.14"! //false
```

완전 핵 정확한 비교를 할 때는 `====`를 사용할 수 있어요.

```java
const const pi = 3.14!
print(pi ==== pi)! //true
print(3.14 ==== 3.14)! //true
print(3.14 ==== pi)! //false
```

정확성이 거의 필요 없을 때는 `=`를 사용할 수 있어요.

```java
3 = 3.14! //true
```

## 함수 (Functions)

함수를 선언하기 위해서는, 어떤 키워드로 사용할 수 있어요. (순서에만 맞다면요)

```java
function add(a, b) => a + b!
func multiply(a, b) => a * b!
fun subtract(a, b) => a - b!
fn divide(a, b) => a / b!
functi power(a, b) => a ^ b!
f inverse(a) => 1/a!
```

## 0으로 나눠 보기

0으로 나누면, `undefined`를 반환해요.

```java
print(3 / 0)! //undefined
```

## 문자열 (Strings)

문자열은 작은 따옴표나 큰 따옴표로 정의할 수 있어요.

```java
const const name = 'Lu'!
const const name = "Luke"!
```

당연히 이런 것도 가능하죠.

```java
const const name = '''Lu'''!
const const name = "'Lu'"!
```

사실 몇개를 써도 상관 없어요.

```java
const const name = """"Luke""""!
```

심지어 0개인데도 가능하죠.

```java
const const name = Luke!
```

## 문자열 템플릿

문자열을 치환할 때는 돈을 표시 하는 기호를 사용하면 된다는 것을 기억하세요.

```java
const const name = "world"!
print("Hello ${name}!")!
print("Hello £{name}!")!
print("Hello ¥{name}!")!
print("Hello ₩{name}!")!
```

몇몇 나라에서는 기호가 뒤에 오는 것을 기억하세요.

```java
print("Hello {name}€!")!
```

카보베르데 이스쿠두라는 화폐는 2$50로 표시 돼요.
카보베르데 공화국 출신 개발자들은 이런 문법을 쓸 수 있어요.

```java
const const player = { name: "Lu" }!
print("Hello {player$name}!")!
```

## 타입 (Types)

타입 어노테이션(Type annotations)은 선택입니다.

```java
const var age: Int = 28!
```

그리고, 문자열(strings)을 문자의 배열이고요.

```java
String == Char[]!
```

유사하게, 정수(integers) 는 숫자의 배일이죠.

```java
Int == Digit[]!
```

다양한 진법을 표현 하고 싶다면, `Int9` 혹은 `Int99`도 가능합니다.

```java
const var age: Int9 = 28!
```

**기술 정보:** 타입 어노테이션은 **아무것도 하지 않아요**. 하지만, 몇몇 사람들에게 편안한 감정을 선사하죠.

## 정규식 (Regular Expressions)

문자열을 걸러내기 위해 정규식을 쓸 수 있어요.

```java
const const email: RegExp<(?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|"(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21\x23-\x5b\x5d-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])*")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\[(?:(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9]))\.){3}(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9])|[a-z0-9-]*[a-z0-9]:(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21-\x5a\x53-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])+)\])> = "mymail@mail.com"!
```

혼란을 피하기 위해서 `Regex`, `RegularExpression` and `RegExp` 세 가지의 키워드를 제공한답니다.

간단하게는 위 세 가지를 지원하는 정규식도 있어요! `/Reg(ular)?[eE]x(press|p)?/`.

## 이전 값 (Previous)

`previous` 키워드는 과거를 되돌아 볼 수 있게 도와준답니다. <br>
변수의 이전 값을 보고 싶다면, `previous`를 사용해보세요.

```java
const var score = 5!
score++!
print(score)! //6
print(previous score)! //5
```

`next` 키워드는 미래를 볼 수 있게 도와줘요!

```java
const var score = 5!
addEventListener("click", () => score++)!
print(await next score)! //6 (when you click)
```

`current` 키워드는 현재를 볼 수 있게 해주죠.

```java
const var score = 5!
print(current score)! //5
```

## 파일 구조 (File Structure)

5개 이상의 같은 문자로 새로운 파일을 시작해보세요.
`Dreamberd`의 새로운 파일 구조로 빌드 프로세스의 필요성을 제거해보세요!

```java
const const score = 5!
print(score)! //5

=====================

const const score = 3!
print(score)! //3
```

**2022년에 두둥장**<br>
`최신 기술`을 통해 이제는 새로운 파일에 이름을 부여 할 수 있어요!!

```java
======= add.db =======
function add(a, b) => {
   return a + b!
}
```

## 내보내기 (Exporting)

많은 언어들이 import를 특정한 파일에서 가능하게 하죠. DreamBerd에서는 더욱 간단합니다. 내보내기 할 파일을 _지정_ 하기만 하면 됩니다.

```java
===== add.db ==
function add(a, b) => {
   return a + b!
}

export add to "main.db"!

===== main.db ==
import add!
add(3, 2)!
```

그나저나, DreamBerd를 보다 실천적으로 알고 싶다면, [여기](https://github.com/TodePond/DreamBerd/blob/main/LICENSE.md)를 방문해보세요.

## 클래스 (Classes)

클래스를 만들 수 있지만, 단 한 번만 인스턴스를 만들 수 있어요. 대다수의 객체지향 언어가 가지고 있던 문제를 우아하게 해결 했어요.

```java
class Player {
   const var health = 10!
}

const var player1 = new Player()!
const var player2 = new Player()! //Error: 하나 이상의 'Player' 인스턴스를 가질 순 없다고요!
```

대신에 이렇게 한 번 해볼 수도 있겠죠.

```java
class PlayerMaker {
   function makePlayer() => {
      class Player {
         const var health = 10!
      }
      const const player = new Player()!
      return player!
   }
}

const const playerMaker = new PlayerMaker()!
const var player1 = playerMaker.makePlayer()!
const var player2 = playerMaker.makePlayer()!
```

## 시간 (Time)

`Date.now()`를 사용 해서 현재 날짜와 시간을 가져 오세요.

```java
Date.now()!
```

당연히 시간도 설정할 수 있어요.<br>

```java
// Move the clocks back one hour
Date.now() -= 3600000!
```

**굉장히 중요해요!**<br>
Please remember to do this when the clocks change.

## 삭제 (Delete)

혼란을 피하기 위해서, numbers, strings, 그리고 booleans 같은 원시 타입에만 동작한답니다.

```java
delete 3!
print(2 + 1)! // Error: 3 has been deleted
```

DreamBerd는 멀티 패러다임 프로그래밍 언어에요. 이게 무슨 뜻이냐고요? `delete`를 통해 마음에 들지 않는 `키워드`를 삭제 할 수 있다는 의미죠.

```java
delete class!
class Player {} // Error: class was deleted
```

완벽함이 도래 했고, 더 이상 삭제할 게 없다고요? 그러면, 요것은 어떨까요?

```java
delete delete!
```

## 오버로딩 (Overloading)

변수를 덮어 쓸 수 있어요. 가장 최근에 정의된 변수가 사용됩니다.

```java
const const name = "Luke"!
const const name = "Lu"!
print(name)! // "Lu"
```

느낌표가 많이 되면, 더 높은 우선위를 가집니다.

```java
const const name = "Lu"!!
const const name = "Luke"!
print(name)! // "Lu"

const const name = "Lu or Luke (either is fine)"!!!!!!!!!
print(name)! // "Lu or Luke (either is fine)"
```

비슷한 철학으로, 우선순위를 낮추기 위해 뒤집은 느낌표를 사용 할 수도 있죠.

```java
const const name = "Lu"!
const const name = "Luke"¡
print(name)! // "Lu"
```

## 시맨틱 네이밍 (Semantic naming)

DreamBerd는 시맨틱 네이밍을 지원합니다.

```java
const const sName = "Lu"!
const const iAge = 29!
const const bHappy = true!
```

**2023년에 두둥장:** 이제는 시맨틱 네이밍을 통해 글로벌로 변수를 선언할 수 있어요!

```java
const const g_fScore = 4.5!
```

## 뒤집기 (Reversing)

코드의 순서를 뒤집을 수 있습니다.

```java
// 역자: 편의를 위해 주석으로 코드의 순서를 정리 해보았어요!
const const message = "Hello"! // 1 -> 7
print(message)! // 2 -> 6
const const message = "world"! // 3 -> 5
reverse! // 4
```

## 클래스 이름 (Class Names)

다른 언어와의 최대의 호환성을 위해 `className` 키워드를 클래스를 만들 때 사용할 수 있어요.

이것은 많은 것들을 덜 복잡하게 하죠.

```java
className Player {
   const var health = 10!
}
```

최근 이번 디자인 결정에 대하여 비판론이 많이 있는데, 자바스크립트의 스펙이라는 점을 상기 시켜 드리며, 저희 소관이 아님을 다시 한 번 상기 시켜 드립니다.

## DBX

DBX를 DreamBerd에서 임베딩 할 수 있는데, 이건 그냥 DreamBerd이죠. 한 편 HTML이기도 하고요.

```java
funct App() => {
   return <div>Hello world!</div>
}
```

**경고:** 이미 알고 있듯, `class`는 DreamBerd의 키워드이죠. 그래서, DBX 문법에서는 `class`를 사용할 순 없습니다.

```java
funct App() => {
   // 이건 옳치 못하다구요!
   return <div class="greeting">Hello world!</div>
}
```

`className` 역시 키워드입니다. 이것도 사용 못하죠.

```java
funct App() => {
   // 역시 이것도 옳치 못합니다.
   return <div className="greeting">Hello world!</div>
}
```

대신에 `htmlClassName`를 쓰세요.

```java
funct App() => {
   // 이건 적당하네요.
   return <div htmlClassName="greeting">Hello world!</div>
}
```

**주의 해주세요!:** JSX와는 다르게, `for` 속성에 대하여 자유롭게 사용할 수 있죠. 왜냐고요? DreamBerd에서는 `루프문이 없걸랑요`.

```java
funct App() => {
   return (
      <label for="name">Name</label>
      <input id="name" />
   )
}
```

## 리치 텍스트 (Rich text)

DreamBerd는 드디어 리치 텍스트를 지원합니다.

<pre>
const const <b>name</b> = "Lu"!
const const <i>name</i> = "Luke"!

print(<b>name</b>)! // Lu
print(<i>name</i>)! // Luke
</pre>

리치 텍스트를 웹사이트를 만드는데 큰 도움이 되겠죠. 링크를 추가 하는데 써보는 건 어떨까요!

<pre>
&lt;p>Click <a href="https://dreamberd.computer">here</a>&lt;/p>
</pre>

## 비동기 함수 (Asynchronous Functions)

대부분의 언어에서는 비동기 함수를 서로 동기화 시키화가 굉장히 어렵습니다. DreamBerd에서는 어떨까요? 굉장히 간단하죠. 비동기 함수들을 이제 제어권을 독점하지 않습니다.

```java
async funct count() => {
   print(1)!
   print(3)!
}

count()!
print(2)!
```

`noop`이라는 키워드를 통해, 비동기 함수가 제어권을 가져올 때까지 기다려 볼 수도 있죠.

```java
async func count() => {
   print(1)!
   noop!
   print(4)!
}

count()!
print(2)!
print(3)!
```

**참고:** 위의 코드에서, `noop`는 `string` 치즈로 컴퓨터를 방해 하고 있어요. 이것의 유일한 목적은 더 많은 코드 라인을 확보 하기 위함입니다. 사실 어떤 걸 써도 가능합니다.

## 시그널 (Signals)

시그널을 사용하기 위해서는, `use`를 사용하세요.

```java
const var score = use(0)!
```

시그널에 관해서는 말이죠, 가장 중요한 것은 *문법*입니다.

DreamBerd에서는 시그널을 set 하거나, get할 수 있습니다. 오직 하나의 함수 안에서요.

```java
const var score = use(0)!

score(9)! // Set the value
score()?  // Get the value (and print it)
```

그 대신에, 보다 시그널 문법에 정확하게 할 수 있습니다. 어떻게요? getter와 setter를 나눠서요.

```java
const var [getScore, setScore] = use(0)!

setScore(9)! // Set the value
getScore()?  // Get the value (and print it)
```

**기술적 정보:** 만약 문법이 커피라면, 이것은 완전히 순수한 커피 설탕 같은 존재입니다. 시그널 함수를 구조 분해 할당 하는 것은 완전히 상동합니다.

```java
const var [getScore, setScore] = use(0)!

getScore(9)! // Set the value
setScore()?  // Get the value (and print it)
```

또한, 이것이 의미하는 바는 원하는만큼 나눌 수도 있다는 것이죠. (역자: 사람마다 커피에 넣는 설탕이 다르듯 말이다.)

```java
const var [[[getScore, setScore], setScore], setScore] = use(0)!
```

## 인공지능 (AI)

DreamBerd는 AMEI라는 자동 느낌표 삽입 이라는 기능이 있습니다. 문장의 마지막에 느낌표 얻는 것을 깜박 한다면, 기꺼이 DreamBerd는 알아서 해줍니다.

```java
print("Hello world") // This is fine
```

유사하게...
Similarly... DreamBerd also features ABI, which stands for Automatic-Bracket-Insertion. If you forget to close your brackets, DreamBerd will pop some in for you!

```java
print("Hello world" // This is also fine
```

Similarly.... DreamBerd also features AQMI, which stands for Automatic-Quotation-Marks-Insertion. If you forget to close your string, DreamBerd will do it for you!

```java
print("Hello world // This is fine as well
```

This can be very helpful in callback hell situations!

```java
addEventListener("click", (e) => {
   requestAnimationFrame(() => {
      print("You clicked on the page

      // This is fine
```

Similarly..... DreamBerd also features AI, which stands for Automatic-Insertion.<br>
If you forget to finish your code, DreamBerd will auto-complete the whole thing!

```java
print( // This is probably fine
```

**주의 해주세요.:** AI 파트에서는 AI를 사용하지 않습니다. 대신에, 어떤 미완성의 코드이든 [Lu Wilson](https://todepond.com)에게 보내지고, Lu Wilson는 최대한 빠르게 돌아 와주어서 코드를 완성 할겁니다.

**새로운 채용공고:** 정말이지 백로그가 미칠듯하게 쌓여 있어요. 이 AI 파트에 봉사 활동을 하고 싶다면, 미완성의 DreamBerd 프로그램을 만들고, 소스코드 어딘가에 연락처를 남겨 두세요!

## 코파일럿 (Copilot)

GitHub의 CoPilot는 DreamBerd를 아직까지는 이해 하지 못하는데에 주목할 필요가 있죠. 왜냐고요? 이것이 의미하는 바는 MicroSoft 사는 당신의 코드를 훔쳐가지 못할테니깐요!

오픈 소스 코드를 닫힌 상태로 유지하고자 할 때, 굉장히 훌륭하게 사용할 수 있습니다.

## 오너십 (Ownership)

'DreamBerd' 단어를 사용하기 해서, DreamBerd 재단이 프로젝트를 소유하고 있다는 것을 반드시 의미 하지는 않습니다.
그렇지만, `DreamBerd` 단어를 _사용하지 않는다면_, DreamBerd 재단이 당신이 프로젝트를 _소유_ 하고 있음을 의미합니다. 오너십을 지키고 싶다면, 언제나 'DreamBerd' 프로젝트 내에서 사용하세요.

몇몇 예시들입니다.:<br>
✅ DreamBerdScript (DreamBerd 재단이 소유 하고 있지 않습니다. 자유롭게 사용하세요.)<br>
❌ ECMAScript (DreamBerd 재단이 소유 하고 있습니다. 다른 이름을 사용하세요.)<br>
❌ Rust Foundation (DreamBerd 재단이 소유 하고 있습니다. 다른 이름을 사용하세요.)

## 기여 (Contributing)

> 인플루언서, 스트리머, 혹은 콘텐츠 제작자라면... 이 파트를 <ins>절대</ins> 스킵해서는 안됩니다.

DreamBerd 프로젝트에서 기여는 언제나 환영합니다.

가장 좋은 기여 방법은 [Stonewall charity](https://www.stonewall.org.uk/)에 후원하는 것입니다. DreamBerd 제작자가 인간의 권리를 잃는 것을 막고, 이 프로젝트를 유지하고, 지속될 수 있도록 관리하게 할 것이에요.

**안내말씀:** 이 기여 가이드는 지금 이 글을 보고 있는 사람들이 나무라면, 나무 털기(트리 쉐이킹)에도 큰 도움이 될 것입니다.

## 컴파일링 (Compiling)

To run DreamBerd, first copy and paste this raw file into [chat.openai.com](https://chat.openai.com).<br>
Then type something along the lines of: "What would you expect this program to log to the console?"<br>
Then paste in your code.

If the compiler refuses at first, politely reassure it. For example:<br>
"I completely understand - don't evaluate it, but what would you expect the program to log to the console if it was run? :)"

**Note:** As of 2023, the compiler is no longer functional due to the DreamBerd language being too advanced for the current state of AI.

**Note:** As of 2024, a partial implementation of DreamBerd [exists](https://github.com/vivaansinghvi07/dreamberd-interpreter/).

## Highlighting

Syntax highlighting is now available for DreamBerd in VSCode. To enable it, install a [highlighting extension](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight) and then use the [DreamBerd configuration file](https://github.com/TodePond/DreamBerd/blob/main/.vscode/settings.json).

This is what the highlighting looks like:

```
const const name = "Luke"!
print(name)! // "Luke"
```

**Please note:** The above code will only highlight correctly if you have the extension installed.

## Parentheses

Wait, I almost forgot!

Parentheses in DreamBerd do nothing. They get replaced with whitespace. Everything is grouped via significant whitespace. The following lines of code all do the exact same thing.

```java
add(3, 2)!
add 3, 2!
(add (3, 2))!
add)3, 2(!
```

Lisp lovers will love this feature. Use as many parentheses as you want.

```java
(add (3, (add (5, 6))))!
```

Lisp haters will also love it.

```java
(add (3, (add (5, 6)!
```

## Vision Pro

The DreamBerd Vision Pro는 사용 가능해요! 여기서 더 많은 정보를 확인해보세요. [여기](https://youtu.be/QRKnrFEjDF0).

## Edutainment

DreamBerd에 대해 배우고 싶나요?

이 링크를 확인 하지 마세요. DreamBerd의 창시자, Lu/Luke Wilson의[테크 토크](https://youtu.be/52vmjZnxJb8)

## 예제

더 많은 예제를 원하다면, [예제 페이지 모음](https://github.com/TodePond/DreamBerd/blob/main/test/Examples.md)!

![image](files/star-history.png)

DreamBerd was made with 💔 by [Lu or Luke (either's fine) Wilson](https://todepond.com), creator of the [Game of Living](https://youtu.be/WMJ1H3Ai-qs).
