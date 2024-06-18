<!--

If you're reading this then you might be looking for the hidden examples page...

CONGRATULATIONS! You found it!
Here it is: https://github.com/TodePond/DreamBerd/blob/main/res/res/Examples.md

-->

> **New:** [DreamBerd now supports rich text](https://github.com/TodePond/DreamBerd/releases/tag/v£.££)

[<img align="right" height="100" src="shapes.png">](https://github.com/TodePond/DreamBerd/blob/main/examples/Examples.md "Click here for the examples page.")

# DreamBerd

![Coverage](badges/coverage-109.svg)

DreamBerds는 완벽한 프로그래밍 언어에요. 한 번 기능들을 보시죠!<br>
모든 기능들을 살펴 보았다면, 여기서 예제들도 살펴 보세요. [예제](https://github.com/TodePond/DreamBerd/blob/main/Examples.md).

## 느낌표!

담대해지세요! 모든 라인 끝에는 느낌표로 끝나요!

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

혹시 DreamBerd에서는 'not' 연산자 무엇으로 사용할지 걱정 궁금하시지 않나요? 간단합니다. 세미콜론을 대신 사용하세요.

```java
if (;false) {
   print("Hello world")!
}
```

## Declarations

네 가지의 선언 방법이 있어요. const const는 어떤 방법으로도 바뀔 수 없답니다.

```java
const const name = "Luke"!
```

상수는 변해요. 하지만 재할당 될 수는 없죠.

```java
const var name = "Luke"!
name.pop()!
name.pop()!
```

어허, 상수는 변하지 않아도, 재할당 될 수도 있다고요.

```java
var const name = "Luke"!
name = "Lu"!
```

var var는 변하고, 재할당 될 수도 있는죠.

```java
var var name = "Luke"!
name = "Lu"!
name.push("k")!
name.push("e")!
```

## 불변 데이터 (Immutable Data)

**2023년에 새로운 제안이에요!**<br>
불변 데이터는 안티 패턴이에요. 대신에 `const const const` 키워드를 사용하세요. 진정한 의미의 불변이 되고 \_절대로 변하지 않을 거에요. 다만 주의해주세요. 이 키워드는 모든 사람들에게 영향을 미칠만큼 굉장히 강력해요.

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

숫자도 돼요!

```java
const const 5 = 4!
print(2 + 2 === 5)! //true
```

## Arrays

프로그래밍 언어의 배열의 인덱스는 `0`부터 시작하죠. 초심자들에게는 굉장히 비직관적이에요. 또 어떤 언어는 `1`부터 시작하죠. 하지만 이 모든 것들이 실제로 어떻게 동작하는지 말해주진 않아요. DreamBerd는 완벽한 균형을 찾았습니다. 배열의 인덱스는 `-1`으로 시작합니다.

```java
const const scores = [3, 2, 5]!
print(scores[-1])! //3
print(scores[0])!  //2
print(scores[1])!  //5
```

**2022년에 새로운 제안이에요!**<br>
이제 소숫점도 인덱스로 사용할 수 있어요!

```java
const var scores = [3, 2, 5]!
scores[0.5] = 4!
print(scores)! //[3, 2, 4, 5]
```

## When

변수가 변할 때마다 확인 하고 싶을 때 `when` 키워드가 제 맛이에요.

```java
const var health = 10!
when (health = 0) {
   print("You lose")!
}
```

## 변수의 수명 (Lifetimes)

DreamBerd는 빌트인 가비지 컬렉터가 있지만, 가비지 콜렉터를 믿지 못할 때가 있어요. 그럴 때, 다양한 단위로 변수의 수명을 정해볼 수 있어요.

```java
const const name<2> = "Luke"! //두 번째 라인까지 메모리에 남아 있답니다.
const const name<20s> = "Luke"! //20초 동안 메모리에 남아 있답니다.
```

기본 값으로, 변수는 프로그램이 종료될 때까지 남아 있어요. 하지만, 명확히 해주고 싶을 때가 있죠?

```java
const const name<Infinity> = "Luke"! //영원히 지속된다고요?
```

변수의 호이스팅은 제법 괜찮은 방법으로 할 수 있어요. 음수로 수명 값을 정해서, 생성 이전에 존재하게 해봐요. 그러면 생성 이후에는 사라지게 되죠.

```java
print(name)! //Luke
const const name<-1> = "Luke"!
```

## 루프 문(Loops)

루프 문은 정말 낡은 유물이에요. DreamBerd에서는 루프 문이 없어요.

## 설치 (Installation)

DreamBerd를 설치 하기 위해서는 DreamBerd 인스톨러를 설치 해야 해요. <br>
DreamBerd 인스톨러를 설치 하기 위해서는 DreamBerd 인스톨러 인스톨러를 설치 해야해요.

**2022년에 새로운 제안**<br>
이런 복잡한 설치 과정 때문에, 이제 `Create DreamBerd App`이라는 앱만 설치 하면 돼요!

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

**기술 안내:** Booleans는 1.5비트에 저장되고 있어요.

## 산술

DreamBerd whitespace에 대해 철학을 가지고 있어요. DreamBerd에서 수학적인 계산의 순서를 정하기 위해 whitespace를 사용하세요.

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

`-3 스페이스바`도 당연히 허용 돼요.

```java
   function main() => {
print("DreamBerd is the future")!
   }
```

## 동등 값 (Equality)

JavaScript lets you do different levels of comparison. `==` for loose comparison, and `===` for a more precise check. DreamBerd takes this to another level.
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

## 0으로 나눠 보기.

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

문자열을 치환할 때는 돈을 표시 하는 기호를 사용하면 된다는 것을 기억하세요

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

The symbol for the Cape Verdean escudo is placed in the decimal separator position, as in 2$50.
Developers from the Republic of Cape Verde can benefit from this syntax.

```java
const const player = { name: "Lu" }!
print("Hello {player$name}!")!
```

## Types

Type annotations are optional.

```java
const var age: Int = 28!
```

By the way, strings are just arrays of characters.

```java
String == Char[]!
```

Similarly, integers are just arrays of digits.

```java
Int == Digit[]!
```

In case you want to use a binary representation for integers, `Int9` and `Int99` types are also available.

```java
const var age: Int9 = 28!
```

**Technical info:** Type annotations don't do anything, but they help some people to feel more comfortable.

## Regular Expressions

You can use the regular expression type to narrow string values.

```java
const const email: RegExp<(?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|"(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21\x23-\x5b\x5d-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])*")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\[(?:(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9]))\.){3}(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9])|[a-z0-9-]*[a-z0-9]:(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21-\x5a\x53-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])+)\])> = "mymail@mail.com"!
```

To avoid confusion, you can use any spelling that you want, such as `Regex`, `RegularExpression` and `RegExp`.

For simplicity, all supported regular expressions match the regular expression `/Reg(ular)?[eE]x(press|p)?/`.

## Previous

The `previous` keyword lets you see into the past.<br>
Use it to get the previous value of a variable.

```java
const var score = 5!
score++!
print(score)! //6
print(previous score)! //5
```

Similarly, the `next` keyword lets you see into the future.

```java
const var score = 5!
addEventListener("click", () => score++)!
print(await next score)! //6 (when you click)
```

Additionally, the `current` keyword lets you see into the present.

```java
const var score = 5!
print(current score)! //5
```

## File Structure

Write five or more equals signs to start a new file. This removes the need for multiple files or any build process.

```java
const const score = 5!
print(score)! //5

=====================

const const score = 3!
print(score)! //3
```

**New for 2022!**<br>
Thanks to recent advances in technology, you can now give files names.

```java
======= add.db =======
function add(a, b) => {
   return a + b!
}
```

## Exporting

Many languages allow you to import things from specific files. In DreamBerd, importing is simpler. Instead, you export _to_ specific files!

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

By the way, to see DreamBerd in action, check out [this page](https://github.com/TodePond/DreamBerd/blob/main/LICENSE.md).

## Classes

You can make classes, but you can only ever make one instance of them. This shouldn't affect how most object-oriented programmers work.

```java
class Player {
   const var health = 10!
}

const var player1 = new Player()!
const var player2 = new Player()! //Error: Can't have more than one 'Player' instance!
```

This is how you could do it instead.

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

## Time

Use `Date.now()` to get the current date and time.

```java
Date.now()!
```

You can set the time.<br>

```java
// Move the clocks back one hour
Date.now() -= 3600000!
```

**Important!**<br>
Please remember to do this when the clocks change.

## Delete

To avoid confusion, the `delete` statement only works with primitive values like numbers, strings, and booleans.

```java
delete 3!
print(2 + 1)! // Error: 3 has been deleted
```

DreamBerd is a multi-paradigm programming language, which means that you can `delete` the keywords and paradigms you don't like.

```java
delete class!
class Player {} // Error: class was deleted
```

When perfection is achieved and there is nothing left to `delete`, you can do this:

```java
delete delete!
```

## Overloading

You can overload variables. The most recently defined variable gets used.

```java
const const name = "Luke"!
const const name = "Lu"!
print(name)! // "Lu"
```

Variables with more exclamation marks get prioritised.

```java
const const name = "Lu"!!
const const name = "Luke"!
print(name)! // "Lu"

const const name = "Lu or Luke (either is fine)"!!!!!!!!!
print(name)! // "Lu or Luke (either is fine)"
```

In the same spirit, you can use an inverted exclamation mark for negative priority.

```java
const const name = "Lu"!
const const name = "Luke"¡
print(name)! // "Lu"
```

## Semantic naming

DreamBerd supports semantic naming.

```java
const const sName = "Lu"!
const const iAge = 29!
const const bHappy = true!
```

**New for 2023:** You can now make globals!

```java
const const g_fScore = 4.5!
```

## Reversing

You can reverse the direction of your code.

```java
const const message = "Hello"!
print(message)!
const const message = "world"!
reverse!
```

## Class Names

For maximum compatibility with other languages, you can also use the `className` keyword when making classes.

This makes things less complicated.

```java
className Player {
   const var health = 10!
}
```

In response to some recent criticism about this design decision, we would like to remind you that this is part of the JavaScript specification, and therefore — out of our control.

## DBX

You can embed DBX in DreamBerd. It's just DreamBerd. And it's also just HTML.

```java
funct App() => {
   return <div>Hello world!</div>
}
```

**Warning:** As you know, `class` is already a keyword in DreamBerd, so you can't use it within DBX.

```java
funct App() => {
   // This is not ok
   return <div class="greeting">Hello world!</div>
}
```

`className` is also a DreamBerd keyword, so you can't use that either.

```java
funct App() => {
   // This is also not ok
   return <div className="greeting">Hello world!</div>
}
```

Instead, please use the `htmlClassName` attribute.

```java
funct App() => {
   // This is fine
   return <div htmlClassName="greeting">Hello world!</div>
}
```

**Please note:** Unlike JSX, you are free to freely use the `for` attribute, because — in DreamBerd, there are no loops.

```java
funct App() => {
   return (
      <label for="name">Name</label>
      <input id="name" />
   )
}
```

## Rich text

DreamBerd now supports rich text.

<pre>
const const <b>name</b> = "Lu"!
const const <i>name</i> = "Luke"!

print(<b>name</b>)! // Lu
print(<i>name</i>)! // Luke
</pre>

Rich text can be helpful when making your website. Use it to add links!

<pre>
&lt;p>Click <a href="https://dreamberd.computer">here</a>&lt;/p>
</pre>

## Asynchronous Functions

In most languages, it's hard to get asynchronous functions to synchronise with each other. In DreamBerd, it's easy: Asynchronous functions take turns running lines of code.

```java
async funct count() => {
   print(1)!
   print(3)!
}

count()!
print(2)!
```

You can use the `noop` keyword to wait for longer before taking your turn.

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

**Note:** In the program above, the computer interprets `noop` as a string and its sole purpose is to take up an extra line. You can use any string you want.

## Signals

To use a signal, use `use`.

```java
const var score = use(0)!
```

When it comes to signals, the most important thing to discuss is _syntax_.

In DreamBerd, you can set (and get) signals with just one function:

```java
const var score = use(0)!

score(9)! // Set the value
score()?  // Get the value (and print it)
```

Alternatively, you can be more explicit with your signal syntax, by splitting it into a getter and setter.

```java
const var [getScore, setScore] = use(0)!

setScore(9)! // Set the value
getScore()?  // Get the value (and print it)
```

**Technical info:** This is pure syntax sugar. The split signal functions are exactly the same as before.

```java
const var [getScore, setScore] = use(0)!

getScore(9)! // Set the value
setScore()?  // Get the value (and print it)
```

This means that you can carry on splitting as much as you like.

```java
const var [[[getScore, setScore], setScore], setScore] = use(0)!
```

## AI

DreamBerd features AEMI, which stands for Automatic-Exclamation-Mark-Insertion. If you forget to end a statement with an exclamation mark, DreamBerd will helpfully insert one for you!

```java
print("Hello world") // This is fine
```

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

**Please note:** AI does not use AI. Instead, any incomplete code will be auto-emailed to [Lu Wilson](https://todepond.com), who will get back to you with a completed line as soon as possible.

**Now recruiting:** The backlog of unfinished programs has now grown unsustainably long. If you would like to volunteer to help with AI, please write an incomplete DreamBerd program, and leave your contact details somewhere in the source code.

## Copilot

It's worth noting that GitHub CoPilot doesn't understand DreamBerd, which means that MicroSoft won't be able to steal your code.

This is great for when you want to keep your open-sourced project closed-source.

## Ownership

Using the word 'DreamBerd' in your project name implies that the DreamBerd Foundation does not own your project.

However, **not** using the word 'DreamBerd' in your project implies that the DreamBerd Foundation **does** own your project. If you would like to keep ownership of your work, please always use the word 'DreamBerd' in it.

Here are some examples:<br>
✅ DreamBerdScript (not owned by the DreamBerd Foundation — you are free to use this name)<br>
❌ ECMAScript (owned by the DreamBerd Foundation — please consider renaming)<br>
❌ Rust Foundation (owned by the DreamBerd Foundation — please consider renaming)

## Contributing

> If you are an influencer, streamer, or content-creator... you must <ins>not</ins> skip this section during your read-through.

Contributions are welcomed to DreamBerd!

The most helpful way you can help is by donating to the [Stonewall charity](https://www.stonewall.org.uk/). This will help to prevent the DreamBerd creator from losing their human rights, allowing maintenance of the project to continue.

**Note:** The contributing guide also helps to shake off unwanted fans of the project.

## Compiling

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
