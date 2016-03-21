# Lesson 01: Starting Out With HTML

HTML stands for HyperText Markup Language. It makes up every page you see on the internet. You can think of it as what happens behind the scenes on a webpage. As you follow these tutorials, you'll learn how HTML is used to make webpages and eventually be able to make your own!

###### Note: We'll be using a file on our GitHub repository as an example for this tutorial. You can find it [here](https://github.com/GrlDevelopers/web_dev/blob/master/01_thebasics.html), and a live version is [here](http://grldevelopers.github.io/ada.html).

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

The `<head>` tag is used to describe things about the document stuff. Kind of like when you put your name, class period, and date at the top of your assignments at school. In this example, the `<title>` tag is used. This tag is used to set the name of the html page--if you look at the top of your browser, the tab title is what the `<title>` tag sets. Pretty straightforward. I reccommend that you try it yourself!

Let's go through the rest of the document. The next line says

```html
	<body>
```

This is the body tag--one of the most important tags in HTML. Within the body tag is everything that appears within your web page, like the text you're reading now! Let's go through the body content. Under that tag, we find

```html
	<h1>Ada Lovelace</h1>
```

Here, we encounter another tag, `<h1>`. This basically means 'header'. It will output bigger text than normal. The number after h allows us to control how big the header is. A bigger number means bigger text. Look at the rest of the document. Can you find other header tags? Compare those on the live webpage, and see which are bigger. Note that these header tags go from 1 to 6.

Unfortunately, this is where our short intro to html ends. For more info on HTML, please visit our [main website](http://www.grldevelopers.com/html-intro/)!
