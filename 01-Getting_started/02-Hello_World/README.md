# Subsection 1.2 - Display Hello World using PHP

OK, now we have an ancient HTML file. What's next ?

Well, the tradition says: _"Let's start with hello world."_

## PHP is a preprocessor engine

PHP is basically a preprocessor. When you access a `.php` file, your webserver consider it as an HTML file with a bunch of PHP statements, it executes PHP once before serving the result to the client. Then the PHP instance shutdowns.

If you access a second page in the same server, everything is forgotten. _(Save this information in your brain for later.)_

## What to do

### Rename file

So start by renaming **`sample.html`** to **`sample.php`**

### Add a statement with a single instruction

PHP statements start with 

```
<?php
```

and end with

```
?>
```

Between them, we can call the `echo` instruction and a string `Hello, World!`. Don't forget a semi-colon at the end to tell the syntax engine it is the end of the instruction. **Otherwise, you'll get an error.**

It will look like:

```
<?php echo 'Hello, World!'; ?>
```

Single quotes are here to set start and end of the characters string.

## See the sample.php file

Go read the source code.

This source code should be rendered as the same HTML code as **`sample.html`** in the first subsection before being sent to web browsers.