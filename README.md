# Placer Style Guide

**The official guide for creating clear, consistent and professional content at Placer.**

_Last updated: 2025-09-27_  
_Version 2.5.4, revision Placer-Style-Guide:09-2025_

This style guide provides the essential standards and best practices for all Placer content, from product documentation and website copy to marketing materials and internal communications. By adhering to these guidelines, we ensure a unified voice, enhance readability and reinforce Placer’s brand identity across all our platforms.

This guide aims to be a helpful, practical resource that empowers our content creators. Consistent application of these standards helps us deliver high‐quality, precise information efficiently.

## 1. Voice and tone

Placer’s content voice is **authoritative, helpful and precise, yet approachable.** We aim to:

- **Be clear and concise:** Get straight to the point without unnecessary jargon.
- **Be empowering:** Guide users confidently through tasks and explanations.
- **Be respectful:** Use inclusive language and address users directly (using “you”).
- **Be professional:** Maintain a high standard of accuracy and presentation.
- **Be enthusiastic (especially for marketing/promotional content):** Convey passion for our tools and their benefits.

**Do:** Use active voice. Address the user directly (“you”). Use plain language.  
**Don’t:** Use passive voice unless specified. Be overly casual or overly formal. Use jargon without explanation.

## 2. General writing principles

### 2.1. Audience

Our primary audience consists of developers, designers and technical users who are seeking clear, accurate and actionable information about Placer Toolkit. Content should be written to be understood by someone familiar with web development concepts but may not be an expert in every specific area.

### 2.2. Active vs passive voice

We generally prefer **active voice** because it is clearer, more direct and more concise, clearly identifying the performer of an action.

- **Preferred (Active):** “Users can update their profile information.”
- **Avoid (Passive):** “The profile information can be updated by users.”

Use **passive voice** only when:

- The performer of the action is unknown or unimportant.
    - **Example:** “The software was updated overnight.” (The specific individual who updated it is not relevant.)
- You want to emphasise the action or the receiver of the action.
    - **Example:** “Security vulnerabilities were discovered and patched promptly.”

### 2.3. Capitalisation

- **Product names and specifications:** Use **Title Case** for product names or specifications (e.g., Placer Style Guide).
- **All other headings and body text:** Use **Sentence case** (e.g., “This is a section heading.”).
- **Product names:** Always capitalise product names as officially designated (e.g., Placer Toolkit).
- **UI elements:** Capitalise the names of specific user interface elements (e.g., **Close** button, **Item 1** dropdown item).
- **Proper nouns:** Standard capitalisation rules apply (names, places, specific organisations).

### 2.4. Numbers and measurements

- **Numbers over 10:** Always use numerals (e.g., 15 users, 200 devices, 10 steps).
- **Numbers 0–9:** Generally spell out these numbers (e.g., three steps, seven days). Exceptions can be made in tables, graphs or for specific technical contexts where consistency with surrounding numerals is critical (e.g., “version 1.9.2”).
- **Time formats:** Use the 12‐hour format with “a.m.” and “p.m.” including full stops (e.g., 8:12 a.m., 3:45 p.m.). Do not use “AM” or “PM”.

## 3. Punctuation

For general punctuation rules, we largely follow the **Associated Press Stylebook**, unless otherwise specified below.

### 3.1. Hyphens, en‐dashes, em‐dashes and the mathematical minus symbol

Distinguish clearly between these symbols for precision.

- **“True hyphen” (`‐`, U+2010):**
    - Use for compound words (e.g., well‐being, state‐of‐the‐art).
    - Don’t use the “true hyphen” for established product names or terms that incorporate a hyphen‐minus (e.g., SHA-512, Mercedes-Benz, ISBN 978-1-5416-9989-2).
- **Non‐breaking hyphen (`‑`, U+2011):**
    - Use when the hyphenated word or name should never break across lines (e.g., co‑founder, Jean‑Paul).
    - Prevents awkward line breaks that separate parts of a compound word.
- **En‐dash (`–`, U+2013):**
    - Use for ranges (e.g., 1–10, March–April, London–New York flight).
- **Em‐dash (`—`, U+2014):**
    - Use for abrupt breaks in a sentence, unspaced (e.g., “Em‐dashes break up sentences—like that.”).
    - Use to set off a parenthetical phrase for emphasis.
- **Mathematical minus (`−`, U+2212):**
    - Use specifically for mathematical minus operations (e.g., $4 − 2 = 2$).
    - This is visually distinct from the hyphen and en‐dash.
    - Make sure to use non‐breaking spaces (` `) within the equation, otherwise, it may break up into new lines.
        - We recommend [MathML](https://developer.mozilla.org/en-US/docs/Web/MathML) for maths instead, unless necessary, prefer using this.

> [!TIP]
> In titles, replace an em‐dash (`—`) with an **en‐dash** spaced out with non‐breaking spaces (` – `) for better visual flow.
>
> - **Preferred (Within a title):** Debugging complex applications – A step‐by‐step guide
> - **Preferred (Within a sentence):** Em‐dashes break up sentences—like that.

### 3.2. SI conventions

We recommend following SI conventions throughout your content.

- Add a **narrow non‐breaking space (` `, U+202F)** between the unit and the number (per cent is also treated as a unit).
- Use the same narrow non‐breaking space for the **thousands separator**.
- Use a comma instead of a full stop for **decimal separators** (although SI allows both).

Make sure you also use the proper SI units and avoid incorrect forms (e.g., **kB** for kilobyte instead of KB).

**Thousands separator:**

- ✅ 1 234 567,89
- ❌ 1,234,567.89
- ❌ 1.234.567,89
- ❌ 12,34,567.89

**Distances:**

- ✅ 3,2 km
- ❌ 3.2km

**Percentages:**

- ✅ 79 %
- ❌ 79%

**Time:**

- ✅ 12 min 36 s
- ❌ 12 min. 36 sec.

### 3.3. Ellipsis symbol

- Always use the single **ellipsis character (`…`, U+2026)** instead of three individual full stops (`...`).
- The ellipsis symbol is more typographically correct and flows better within the sentence.

### 3.4. Smart quotes vs straight quotes

- Use **smart quotes (`“”` for double, `‘’` for single)** whenever possible for a professional typographic appearance.
- Do not use straight quotes (`""` or `'`).

**Apostrophes:**

- Always use the **closing single smart quote (`’`)** for apostrophes (e.g., it’s, users’ feedback).
- For contractions starting with an apostrophe (e.g., ’em, ’90s), also use the closing single smart quote (`’`). Many word processors may incorrectly convert this to an opening smart quote (`‘`); please manually review and correct.

**Prime and double prime symbols:**

- Use the **prime (`′`, U+2032)** and **double prime (`″`, U+2033)** symbols for geographic coordinates, not apostrophes or straight quotes.
    - **Example:**
        - ✅ `51° 28′ 37″ N, 0° 0′ 2″ W`
        - ❌ `51° 28’ 37” N, 0° 0’ 2” W`
        - ❌ `51° 28' 37" N, 0° 0' 2" W`

### 3.5. Oxford comma (Serial comma)

- We **do not** use the Oxford/serial comma (the comma before “and” or “or” in a list) in titles, lists or sentences.
    - **Example:** Apples, bananas and strawberries
    - **Example:** What’s the first, second and third quarter like?

**Exception: Prevent confusion**

- Use the Oxford/serial comma **only when its omission would cause ambiguity or misinterpretation.**
    - **Ambiguous (Without):** “I love my parents, my dog and my cat.” (Could imply the dog and cat are the parents.)
    - **Clear (With):** “I love my parents, my dog, and my cat.” (Clearly lists three separate entities.)

## 4. Formatting and structure

### 4.1. Headings

- Ensure a logical heading hierarchy (Heading 1, Heading 2, Heading 3, etc.).
- All headings (Heading 2 and below) should use **Sentence case**.
- The main document title (Heading 1) uses **Title Case** for components and **Sentence case** for other stuff.

### 4.2. Lists

- **Punctuation:** For lists where each item is a complete sentence, use a full stop at the end of each item. For lists of sentence fragments, use no punctuation at the end of each item.
- **Parallelism:** Ensure all items in a list are grammatically parallel (e.g., all start with verbs, all are nouns).

### 4.3. Emphasis

- Use **bold** for emphasis on key terms, UI elements (buttons, menus) or important warnings.
- Use _italics_ sparingly for titles of books/software, terms being defined or foreign words. You may also use italics in sentences if you want to provide emphasis, but not as much emphasis as **bolding** would do.

### 4.4. Code formatting

- Use appropriate code blocks for code examples.
- Do not use typographic symbols like true hyphens, en‐dashes, em‐dashes, mathematical minus symbols, ellipsis symbols or smart quotes **within code**, unless they are part of a string literal.
    - **Example:** `console.log("It’s great!")` (Smart quote in string is correct.)
    - **Example:** `myVariable - anotherVariable` (Hyphen‐minus is used, not mathematical minus.)

### 4.5. User interface elements

- Refer to UI elements (buttons, menu items, fields, tabs) consistently.
- Generally capitalise and use bold for UI element names that appear in the software interface.
    - **Example:** Click the **OK** button.
    - **Example:** Select the **General** tab.
- But for UI element names that end in some punctuation mark, like an ellipsis (`…`) or an exclamation mark (`!`), omit the full stop.
    - **Example:** Navigate to **File > Save as…**

---

_This work is licenced under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You may view our human‐generated summary at [LICENSE.md](./LICENSE.md) or obtain a copy of the official licence at [https://creativecommons.org/licenses/by/4.0](https://creativecommons.org/licenses/by/4.0)._

© 2025 Placer and its contributors
