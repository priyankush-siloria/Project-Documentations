# The first largest heading tag.
## The second largest heading tag.
### The third largest heading tag.
#### The third smallest heading tag.
##### The second smallest heading tag.
###### The first smallest heading tag.

**This text is bold.**
__This text is also bold.__

*This text is bold.*
_This text is also bold._

~~This text is Strikethrough.~~

**Text is bold but this word is _italic_.**

***Whole text bold and italic.***

> Text with Quote.

This is a `Backticks` text.

Use triple (```) - (fenced code block) for format the code on its own distinct block.

```
a = 5
b = 6
c = a + b
```

If you want to make the block as language specific. Please add the language identifier (name) after the fenced code block.

> Example for python

```python
def sample(*args) -> int:
    total: int = 0
    for element in args: total += element
    else: return total
```

> Example for JavaScript
```javascript
function your_name(name="Dummy") {
    return name;
};

let with_mention = your_name("Sample User");
console.log(with_mention);
let without_mention = your_name();
console.log(without_mention);
```