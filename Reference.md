# Headings

| Markdown             | HTML                       | Output                   |
| -------------------- | -------------------------- | ------------------------ |
| `# Heading level 1`  | `<h1>Heading level 1</h1>` | <h1>Heading level 1</h1> |
| ` # Heading level 2` | `<h2>Heading level 2</h2>` | <h2>Heading level 2</h2> |
| ` # Heading level 3` | `<h3>Heading level 3</h3>` | <h3>Heading level 3</h3> |
| ` # Heading level 4` | `<h4>Heading level 4</h4>` | <h4>Heading level 4</h4> |
| ` # Heading level 5` | `<h5>Heading level 5</h5>` | <h5>Heading level 5</h5> |
| ` # Heading level 6` | `<h6>Heading level 6</h6>` | <h6>Heading level 6</h6> |

### Alternate Syntax

Alternatively, **_on the line below the text_**, add any number of **==** _characters for heading level 1_ or **--** _characters for heading level 2_.

| Markdown                                 | HTML                       | Output                   |
| ---------------------------------------- | -------------------------- | ------------------------ |
| ` Heading level`<br> `=============`     | `<h1>Heading level 1</h1>` | <h1>Heading level 1</h1> |
| ` Heading level 2`<br> `---------------` | `<h2>Heading level 2</h2>` | <h2>Heading level 2</h2> |

#### Heading Best Practices

- _always put a space between the_ **number signs** and the **heading name**

  | ✅Do this            | ❌ Don't do this    |
  | -------------------- | ------------------- |
  | `# Here's a Heading` | `#Here's a Heading` |

- _You should also put_ **blank lines** _before and after a heading for compatibility._

  | ✅Do this            | ❌ Don't do this                                                                                             |
  | -------------------- | ------------------------------------------------------------------------------------------------------------ |
  | `# Here's a Heading` | Without blank lines, this might not look right. <br>`# Heading` <br> <font color="red">Don't do this!</font> |

  ***

# Paragraphs

| Markdown                                                         | HTML                                                                    | Output                                                        |
| ---------------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------- |
| ` I really like using Markdown.`                                 | `<p>I really like using Markdown.</p>`                                  | I really like using Markdown.                                 |
| ` I think I'll use it to format all of my documents from now on` | `<p>I think I'll use it to format all of my documents from now on.</p>` | I think I'll use it to format all of my documents from now on |

#### Heading Best Practices

| ✅Do this                                                     | ❌ Don't do this                                   |
| ------------------------------------------------------------- | -------------------------------------------------- |
| Don't put **tabs** or **spaces** in front of your paragraphs. | This can result in unexpected formatting problems. |

---

# Line Breaks

| Markdown                                                  | HTML                                                                     | Output                                                    |
| --------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------- |
| This is the first line. <br> And this is the second line. | `<p>This is the first line. <br>`<br> `And this is the second line.</p>` | This is the first line. <br> And this is the second line. |

---

# Emphasis

### Bold

To bold text, \*add two **asterisks** or **underscores\*** before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

| Markdown                      | HTML                                      | Output                     |
| ----------------------------- | ----------------------------------------- | -------------------------- |
| ` I just love **bold text**.` | `I just love <strong>bold text</strong>.` | I just love **bold text**. |
| ` I just love __bold text__.` | `I just love <strong>bold text</strong>.` | I just love **bold text**. |
| ` Love**is**bold`             | `Love<strong>is</strong>bold`             | Love**is**bold             |

#### Bold Best Practices

| ✅Do this        | ❌ Don't do this |
| ---------------- | ---------------- |
| `Love**is**bold` | `Love__is__bold` |

# Italic

| Markdown                                | HTML                                          | Output                               |
| --------------------------------------- | --------------------------------------------- | ------------------------------------ |
| ` Italicized text is the *cat's meow*.` | `Italicized text is the <em>cat's meow</em>.` | Italicized text is the _cat's meow_. |
| ` Italicized text is the _cat's meow_.` | `Italicized text is the <em>cat's meow</em>.` | Italicized text is the _cat's meow_. |
| `A*cat*meow`                            | `A<em>cat</em>meow`                           | A*cat*meow                           |

#### Italic Best Practices

| ✅Do this    | ❌ Don't do this |
| ------------ | ---------------- |
| `A*cat*meow` | `	A_cat_meow`     |
