# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good Cloud Engineer uses Cpdeblocks wheneber possible.

Because it allows other to copy and past their code tp replicate or research issues


- In order to create codeblocks in markdown you need to use three backticks ( ` )
- not to be confused with quotation ( ' )
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple HTML Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    
    <main>
        <section>
            <h2>About Me</h2>
            <p>I'm a web developer with a passion for creating interactive and user-friendly websites.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
</body>
</html>

```
- When you can you should attempt to apply syntax highlighting to your codeblocks
``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple HTML Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    
    <main>
        <section>
            <h2>About Me</h2>
            <p>I'm a web developer with a passion for creating interactive and user-friendly websites.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
</body>
</html>

```
Just a note the location of the **Backtick** may vary depending on the type of your keyboard layout, mostly it will be above the *tab key*.

![Backtick](https://github.com/Kayani-124/github-doc-example/assets/77053468/ea5bb85d-47c1-42ca-adf8-14ff8cb34b4e)

Good Cloud Engineers use codeblocks for both code and errors that appear in the console.

``` bash
./error.sh: line 4: non_existent_command: command not found
```
> Here is an example of using a codeblock for an error that appears on bash.

## Step 3 - Using github flavoured Task List

Github ectends Markdown to have a list where you can check off items.[<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Using Emojis (Optional Task)

GitHub Flavored Markdown (GFM) supports emojis shortcodes.
> Here are some examples

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with Lighting | `:cloud_wwith_lighting:` | 🌩️ |

# Step 5 - How to ceate a Table

You can use the below format to create Tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with Lighting | `:cloud_wwith_lighting:` | 🌩️ |
```
Github extends the functionality of markdown tables to provide more alignment and table cell format options. [<sup>[2]</sup>](#external-references)

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
  
- [Basic writing and formatting syntax (Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)
  
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
  
- [GFM - Tables (extension)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
