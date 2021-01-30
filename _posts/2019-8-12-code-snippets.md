---
layout: post
title:  Code snippets in a blog post
categories: [HTML,Code]
---

This post demonstrate the use of code snippets in the theme. The code snippets are powered by [Pygments](http://pygments.org/) and the code theme that is been used in Reverie is called [Draula](https://draculatheme.com/).

Swift:
```swift
var test: String = "hello"

struct LoginView: View {
    ...

    var body: some View {
        VStack {
            ...
            Group {
                Button("Log in") {
                    ...
                }
                Button("I forgot my password") {
                    ...
                }
            }
            .padding()
            .background(Color.blue)
            .foregroundColor(.white)
            .cornerRadius(20)
        }
    }
}
```

This is a raw snippet:

```
hello world
123
This is a text snippet
```

This is a PHP snippet:

```php
<?php
    echo 'Hello, World!';
?>
```

This is a JavaScript snippet:

```js
const add = (a, b) => a + b
const minus = (a, b) => a - b

console.log(add(100,200))  // 300
console.log(minus(100,200))  // -100
```

This is a Python snippet:

```python
def say_hello():
    print("hello world!")

say_hello()   // "hello world!"
```