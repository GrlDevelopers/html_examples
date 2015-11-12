# Lesson 01: Starting Out With HTML

HTML stands for HyperText Markup Language. It makes up every page you see on the internet. You can think of it as what happens behind the scenes on a webpage. As you follow these tutorials, you'll learn how HTML is used to make webpages and eventually be able to make your own!

###### Note: We'll be using a file on our GitHub repository as an example for this tutorial. You can find it on [github.com/GrlDevelopers](https://github.com/GrlDevelopers) under the repo titled "web_dev". The file is called "01_thebasics.html"

## The Structure of an HTML file

To make an HTML page work, we need to follow a set of instructions made specifically for HTML. You can think of this as how grammar tells us to say *"we are"* instead of *"we is"*. In coding, that's called syntax, and we must follow it so that our code works.

## Opening Up With Tags

In HTML's syntax, **tags** are very important. If you open up our sample file mentioned earlier, you'll see that the first lines of the file say:

```html
<!DOCTYPE html>
<html>
```

The **tags** we mentioned earlier are denoted with a `<` at the beginning and some text, with a `>` at the end. The tags above are known as opening tags, which tell the web browser, *Hey, I want you to show this thing that is specified in the tags.*
In the example above, `<!DOCTYPE html>` and `<html>` are used to mark the beginning of an HTML file. If you open up a file and see those tags at the beginning, you'll know that it's an HTML file.

Let's move on to the next lines of the document. After the previous two tags above, you'll see:

```html
<head>
	<title>About Ada Lovelace</title>
</head>
```