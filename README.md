# ✨ Placer Style Guide

**The official style guide for projects made by Placer. ✨**

> [!TIP]
> Design tokens listed in this style guide are referring to our internal project we’re currently working on called “Placer Toolkit”. We won’t tell you what it is though, _yet_. But we’ll give you a little hint: It’s a UI library of components, but what revolutionary technology are we using? Find out yourself! 🤫

## Font stacks

We recommend using these fonts when contributing to any project made by Placer or is related to it.

### Sans‐serif fonts

**Main font:** Quicksand  
**Fallback fonts:** System font, Apple system font (Safari), Apple system font (Chromium‐based browsers), Segoe UI Variable, Segoe UI, Roboto, Open Sans, Helvetica Neue, default sans‐serif font

### Serif fonts

**Main font:** Playfair Display  
**Fallback fonts:** Georgia, Times New Roman, default serif font

### Monospace fonts

**Main font:** JetBrains Mono  
**Fallback fonts:** Source Code Pro, IBM Plex Mono, Consolas, Menlo, default monospace font

### Emoji fonts

We recommend adding these as fallback fonts after the default sans‐serif fonts to render emojis as expected and not to use the emoji font over the proper sans‐serif fonts.

**Main font:** Apple Color Emoji  
**Fallback fonts:** Segoe UI Emoji, Segoe UI Symbol

### Exported CSS

And here is the requested CSS to the fonts used. You can paste these into your CSS `:root` block to use across your site globally:

```CSS
--pc-font-sans: "Quicksand", system-ui, -apple-system, BlinkMacSystemFont,
    "Segoe UI Variable", "Segoe UI", "Roboto", "Open Sans", "Helvetica Neue",
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
--pc-font-serif: "Playfair Display", "Georgia", "Times New Roman", serif;
--pc-font-mono: "JetBrains Mono", "Source Code Pro", "IBM Plex Mono",
    "Consolas", "Menlo", monospace;
```

## Font sizes

Use these font sizes accordingly to what that section of text is best described by in this table.

> [!NOTE]
> Font values from `rem` converted to px values are based on a root font size of 16px.

| Text style        | Design token               | Font size       | Use case              |
| :---------------- | :------------------------- | :-------------- | :-------------------- |
| Title (Heading 1) | `var(--pc-font-size-xxxl)` | 2.5rem (40px)   | Titles, main headings |
| Heading 2         | `var(--pc-font-size-xxl)`  | 2rem (32px)     | Main sections         |
| Heading 3         | `var(--pc-font-size-xl)`   | 1.5rem (24px)   | Subsections, cards    |
| Body text         | `var(--pc-font-size-m)`    | 1rem (16px)     | Paragraphs            |
| Small text        | `var(--pc-font-size-s)`    | 0.875rem (14px) | Captions, footnotes   |

We find headings 4, 5 and 6 are largely unnecessary and can be often replaced with `<small>`.

## Font weights

Font weights are crucial to define the emphasis of blocks of text. We define basic font weights for use for maximum compatibility with all fonts with enough flexibility for most users.

| Font weight | Design token                     | Use case                                                                             |
| :---------- | :------------------------------- | :----------------------------------------------------------------------------------- |
| 300         | `var(--pc-font-weight-light)`    | _No use case available yet_                                                          |
| 400         | `var(--pc-font-weight-normal)`   | Body text, captions, footnotes and most other types of text                          |
| 500         | `var(--pc-font-weight-medium)`   | For body text and most other types of text with a very slight emphasis               |
| 600         | `var(--pc-font-weight-semibold)` | _No use case available yet, occassionally mixed in with font weight bold (700)_      |
| 700         | `var(--pc-font-weight-bold)`     | For body text with strong emphasis, titles and headings, as well as other large text |

## Letter spacing

We usually don’t adjust letter spacing, but Placer Toolkit offers some design tokens for adjusting letter spacing.

| Letter spacing | Design token                      |
| :------------- | :-------------------------------- |
| −0.03em        | `var(--pc-letter-spacing-denser)` |
| −0.015em       | `var(--pc-letter-spacing-dense)`  |
| Normal (0em)   | `var(--pc-letter-spacing-normal)` |
| 0.075em        | `var(--pc-letter-spacing-loose)`  |
| 0.15em         | `var(--pc-letter-spacing-looser)` |

## Line height

Line heights improve the flow of text and makes text easier to read. But using improper line heights may impact readability, so we provide the best line heights for an optimal reading experience for users.

| Line height | Design token                   | Use case                                                                 |
| :---------- | :----------------------------- | :----------------------------------------------------------------------- |
| 1           | `var(--pc-line-height-denser)` | This is provided for consistency, but we generally don’t use this at all |
| 1.4         | `var(--pc-line-height-dense)`  | Titles, headings, sections, subsections                                  |
| 1.8         | `var(--pc-line-height-normal)` | Body text, paragraphs, captions, footnotes                               |
| 2.2         | `var(--pc-line-height-loose)`  | Lists                                                                    |
| 2.6         | `var(--pc-line-height-looser)` | This is provided for consistency, but we generally don’t use this at all |

## Style rules

And this is possibly the complex part to fully adhere to, and that is the style rules. We have very strict, specific style rules that allow for consistency, professionalism and improve the flow of text.

### Title case or sentence case?

Usually, it is sentence case. But occassionally, title case is used, but often for product names and similar. There’s an example right on this page, the title at the top is written in title case. But everything else **must** be sentence case if you want to fully adhere to our style rules.

### Punctuation

We are very aware that adhering to our punctuation rules are really hard (we know!), so we provide some general rules that you have to adhere to at a minimum.

-   You **must** use commas, full stops (or periods), semicolons and other punctuation symbols correctly.
-   You **mustn’t** use true hyphens (‐, U+2010) in your text.

    > If you do use true hyphens, you should **only** use them in text that mustn’t adhere to it (e.g. pre‐sent). Pre‐established terms **must** use regular hyphen‐minuses if the pre‐established term uses a hyphen‐minus in the term, which it generally does (e.g. SHA-512, Mercedez‐Benz).

-   You **must** use en‐dashes (–), em‐dashes (—) and the mathematical minus symbol (−) correctly.
-   You **must** use the ellipsis symbol (…) instead of three full stops (...).
-   You **must** use smart quotes (“”) instead of straight quotes ("") correctly.
-   You **mustn’t** use the Oxford comma (i.e. the serial comma).
-   You **must** use the 12‐hour format in English and the 24‐hour format in other languages that prefer the 24‐hour format.
-   For visual weight, you **must** use the numbers rather than the words for numbers over 10. For numbers below that, it generally doesn’t matter, as long as the visual weight feels right.
-   You **mustn’t** use true hyphens, en‐dashes, em‐dashes, the mathematical minus symbol, the ellipsis symbol and smart quotes in code, unless if it’s a string, then you must adhere to these rules.

#### Ellipses

We prefer the ellipsis symbol (…) instead of three full stops (...), as that is the more typographically correct one and flows better into the sentence.

#### Hyphens

Hyphens… oh yes. You should generally use true hyphens (‐, U+2010) over traditional hyphen‐minuses (-, U+002D) that were introduced during the typewriter era. But there are exceptions. You shouldn’t use true hyphens for pre‐established terms that use hyphens in their name, that don’t officially use true hyphens, which is generally the case. Examples include SHA-512 and Mercedez-Benz.

#### En‐dashes, Em‐dashes and the mathematical minus symbol

You might be asking yourself, “When should I use this over the other?”, and a bunch load of other questions. This is typical. So here’s a short summary on when to use what:

-   Use en‐dashes (–) for ranges (e.g. 1–10 or London–New York flight).
-   Use em‐dashes (—) for breaks in a sentence (e.g. “Em‐dashes break up sentences—like that”).
-   Use the mathematical minus symbol (−) for obviously, referring to the mathematical minus operator (e.g. 4 − 2 = 2)

> [!TIP]
> Replace the em‐dash with a spaced out en‐dash if it’s in a title (e.g. **The Summary – Maths in 2024**), for standard sentences, please use an unspaced em‐dash.

#### Oxford comma (serial comma)

We recommend using no Oxford/serial comma in titles, lists and sentences.

TL;DR:

An Oxford comma (or serial comma) is a practise of adding commas before the word “and” or “or” in a list. Examples include “Apples, bananas, and strawberries”, “What’s the first, second, and third quarter like?” Removing them involves removing the comma before the word “and” and “or” in a list, so “Apples, bananas, and strawberries” turns into “Apples, bananas and strawberries”, as well as “What’s the first, second and third quarter like?”

But there is an exception. Occassionally, the Oxford comma/serial comma is necessary to prevent confusion. Here’s an example:

**With Oxford/serial comma:** “I love my parents, my dog, and my cat.” You love your parents, but also your dogs and your cats.
**Without Oxford/serial comma:** “I love my parents, my dog and my cat” It could possibly mean that you love your parents, and they’re your dog and your cat.

Here, you should use the Oxford/serial comma to prevent confusion.

#### Numbers over 10

For numbers over 10, you should **always** use the number rather than the word. It’s often easier to read, is more concise and is understandable in all languages. For numbers under 10, you can choose if you want the number or the word, it just has to fit the visual weight of the sentence.

#### Commas and full stops

We borrow most comma and full stop rules from the [Associated Press Stylebook](https://www.apstylebook.com). You can check it out there and see the rules used there, as it’s usually very similar across the board.

#### 12‐hour vs 24‐hour format

Very simple to talk about, use the 12‐hour format in English and use the 24‐hour format in other languages that prefer it over the 12‐hour format.

© 2025 Placer and its contributors
