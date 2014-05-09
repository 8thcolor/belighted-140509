## Code Quality, meh?!

Christophe Philemotte, Belighted, 9 May 2013

---

### About me

* Developer ([@toch on GitHub](https://github.com/toch), [@_toch on Twitter](https://twitter.com/_toch))
* Author on [blog.8thcolor.com](http://blog.8thcolor.com)
* CoFounder of PullReview [https://pullreview.com](https://pullreview.com)

---

![Mr Happy Man](images/Mr-Happy-Man.png)

---

> I hope to see Ruby help every programmer in the world to be productive, and to
> enjoy programming, and to be happy. That is the primary purpose of Ruby
> language.
> **Matz, 2008**

---

> Code is like farts. It stinks if it isn't yours.

---

![wtfpm](images/wtfm.jpg)

---

![blured](images/BlurredText.jpg)

---

![meh](images/meh.jpg)

---

![time and money](images/time-money.jpg)

---

![tech debt](images/techdebt.png)

---

### For Developer

* productivity / time
* confidence

---

### For Company

* money
* confidence

---

### 2 Aspects

* Functional
* Structural

---

### Functional

How it complies to the:

* user stories
* specs
* functionalities
* requirements

---

### Structural

* Reliability
* Efficiency
* Security
* Maintainability
* Size

---

### How to check them?

---

![Safety Nets](images/safety-net.jpg)

---

* Tests
* _
* _

---

* Tests
* Code Review
* _

---

* Tests
* Code Review
* Static Analysis

---

### What can we measure with Static Analysis?

---

* Reliability
* (Efficiency)
* Security
* Maintainability
* Size

---

### How can we measure?

---

* Complexity
* Duplication
* Code Style
* Test infection
* Suspicious constructs / Flaws
* Code Smells
* Best Practices
* Security

---

### Complexity

---

>  How complex it is to understand and modify your code.

---

It's correlated to the number of bugs.

---

```
def hello_world
 puts "Hello world"
end
```

![complexity 1](images/complexity1.png)

---

```
def hello(name)
 if name
    puts "Hello #{name}"
 end
end
```

![complexity 2](images/complexity2.png)

---

```
def hello(name)
 return unless name
 puts "Hello #{name}"
end
```

![complexity 3](images/complexity3.png)

---

### Duplication

---

![Copy Paste](images/copypaste.jpg)

---

It's correlated to the number of bugs.

---

### Code Style

---

![obfuscated](images/obfuscated.gif)

---

### Test infection

---

![infection](images/infection.jpg)

---

To find untested code

---

### Suspicious constructs / Flaws

### Code Smells

### Best Practices

---

![suspicious](images/suspicious.jpg)


---

### Security

---

![security](images/security-vulnerability.jpg)

---

# Thanks! Questions?
