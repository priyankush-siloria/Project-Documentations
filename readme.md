<!-- Start -->
> Headings
    
    - Largest to Smallest

# The first largest heading tag.
## The second largest heading tag.
### The third largest heading tag.
#### The third smallest heading tag.
##### The second smallest heading tag.
###### The first smallest heading tag.
----------------------------------------------------------------------

<!-- End -->

<!-- Start -->
> Bold with `**`

**This text is bold.**

> Bold with `__`

__This text is also bold.__

----------------------------------------------------------------------

<!-- End -->

<!-- Start -->
> Italic with `*`

*This text is italic.*

> Italic with `_`

_This text is also italic._

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Strike Through

~~This text is Strikethrough.~~

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Bold with Italic

**Text is bold but this word is _italic_.**

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Whole text bold and italic

***Whole text bold and italic.***

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Text with Quote.

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Highlighted

This is a `Backticks` text.

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Fenced Code Block

Use triple (```) - (fenced code block) for format the code on its own distinct block.

```
a = 5
b = 6
c = a + b
```

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
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

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> For adding a link. Use the following parameters:

    - `[]` place the link text inside square braces.
    - `()` place the URL inside round braces.

Google Link [Google](https://www.google.com)

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> For adding a image link, also showing image. Use the following parameters:

    - `[]` place the link text inside square braces.
    - `()` place the URL inside round braces.
    - `!` add this symbol before the square braces.

![Dummy Image](https://source.unsplash.com/user/c_v_r/1900x800)

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Foot Notes

- Sample 1[^1].
- Sample 2[^2].
- Sample 3[^3].
- Sample 4[^4].

[^1]: Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

[^2]: Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

[^3]: Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

[^4]: Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> List

> Unordered list with `-`

- Item 1.
- Item 2.
- Item 3.
- Item 4.
- Item 5.

> Unordered list with `*`

* Item 1.
* Item 2.
* Item 3.
* Item 4.
* Item 5.

> Ordered List

1. Item 1.
2. Item 2.
3. Item 3.
4. Item 4.
5. Item 5.

> Nested List

1. Main Item 1.
    - Nested Item 1.
    - Nested Item 2.
    - Nested Item 3.
2. Main Item 2.
    * Nested Item 1.
    * Nested Item 2.
    * Nested Item 3.

> Nested List Again

1. Main Item 1.
    - Nested Item 1.
        - Nested Item 1.
        - Nested Item 1.
    - Nested Item 2.
        * Nested Item 1.
        * Nested Item 1.
    - Nested Item 3.
        - Nested Item 1.
        * Nested Item 1.

----------------------------------------------------------------------
<!-- End -->

<!-- Start -->
> Task List

    - Add empty square braces `[ ]` with space inside braces to make test pending.
    - Add square braces `[X]` with `X` inside braces to make test complete.

- [X] Done.
- [ ] Pending.

----------------------------------------------------------------------
<!-- End -->