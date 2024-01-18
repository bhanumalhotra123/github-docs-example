# github-docs-example




## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you beed to use three backticks (`)
- Not to be confused with quotation (')
- Its should appeaer above the tab key, but it may vary based on your keyboard layout.


<img width="200" src=assets/backtick.png>

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

```
# Get input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Add the numbers
sum_result = num1 + num2

# Print the result
print("The sum of {} and {} is: {}".format(num1, num2, sum_result))

```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```python

# Get input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))


# Add the numbers
sum_result = num1 + num2

# Print the result
print("The sum of {} and {} is: {}".format(num1, num2, sum_result))

```



Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "your_file.py", line 12, in <module>
    result = divide_numbers(10, 0)
  File "your_file.py", line 4, in divide_numbers
    raise ValueError("Division by zero is not allowed")
ValueError: Division by zero is not allowed
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lighting:` | 🌩️ |
| Scream | `:scream:` | 😱 |

# Step 5 - how to create a table

YOu can use the following markedown format to create tables:
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lighting:` | 🌩️ |
| Scream | `:scream:` | 😱 |
```
Github extends the functionality of markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)
 

[Secret Window Hidden Garden](secret-window/hidden-garden.md)


## External References
- [Basic writing and formatting syntax(Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [ GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [ GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>




<img width="200" src="https://github.com/bhanumalhotra123/github-docs-example/assets/144083659/81e2fb52-3c0e-4114-ad07-43c3cce98d39" />
  
- Hello! This picture of me was taken at The Beatles Ashram in Rishikesh.
- This tranquil ashram nestled in the spiritual haven of Rishikesh served as a creative retreat for The Beatles during a crucial phase in their musical journey.

