> Headings --> Largest to Smallest

# The first largest heading tag.
## The second largest heading tag.
### The third largest heading tag.
#### The third smallest heading tag.
##### The second smallest heading tag.
###### The first smallest heading tag.

> Bold with `**`

**This text is bold.**

> Bold with `__`

__This text is also bold.__


> Italic with `*`

*This text is italic.*

> Italic with `_`

_This text is also italic._

> Strike Through

~~This text is Strikethrough.~~

> Bold with Italic

**Text is bold but this word is _italic_.**

> Whole text bold and italic

***Whole text bold and italic.***

> Text with Quote.

> Highlighted

This is a `Backticks` text.

> Fenced Code Block

Use triple (```) - (fenced code block) for format the code on its own distinct block.

```
a = 5
b = 6
c = a + b
```

> If you want to make the block as language specific. Please add the language identifier (name) after the fenced code block.

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

> For adding a link. Use the following parameters:

    - `[]` place the link text inside square braces.
    - `()` place the URL inside round braces.

Google Link [Google](https://www.google.com)

> For adding a image link, also showing image. Use the following parameters:

    - `[]` place the link text inside square braces.
    - `()` place the URL inside round braces.
    - `!` add this symbol before the square braces.

![Dummy Image](https://source.unsplash.com/user/c_v_r/1900x800)


> Foot Notes

[^1]: Heading 1.

[^2]: Heading 2.

[^3]: Heading 3.

[^4]: Heading 4.

Sample[^1].
