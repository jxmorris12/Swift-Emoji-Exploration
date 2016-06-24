# Swift-Emoji-Exploration
an example of how weird things can get with Swift's unicode support

download or just run this code in Swift Playgrounds:

```
typealias 🌭🌭🌭🌭🌭🌭 = String
typealias 🎾 = UnicodeScalar

let 🎲 = 0x1F601
let 🎸 = 0x1F64F

let 🌵 = " "
var 🏈 = ""

for 🐶 in 🎲...🎸 {
  var 👽 = 🌭🌭🌭🌭🌭🌭(🎾(🐶))
  🏈 += 👽 + 🌵
}

print(🏈)
```
