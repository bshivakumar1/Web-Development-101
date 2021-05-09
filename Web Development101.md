

WEB DEVELOPMENT 101

**What is the Internet?**

The origin of the Internet dates back to the 1960s, with it starting out as a way to

connect computers across the United States. Today, billions of devices

are **interconnected** over the Internet.

In the following video, Vint Cerf, one of the *fathers of the internet* explains the history

of the net and how no one person or organization is really in charge of it.

https://youtu.be/Dxcc6ycZ73M

**Client & Server**

When you're browsing the Internet, you usually start by typing in an address into the

browser's address bar, or by intiating a search.

This means that information needs to flow from a machine (somewhere in the world)

connected to the Internet, to your computer, which is also connected to the Internet.

·

·

The machine that requests some info (your PC, for example) is called **the client**.

The machine that stores the information is called **the server**.

For example, if you want to know the current weather in your city today, you might

start by opening up a web browser. Next, you type in the web address that provides

weather. https://weather.com, for example, and press *Enter*.

In that moment your computer starts talking to another computer over Internet, called

a server, usually thousands of miles away. And in milliseconds your computer asks

that server for a web document (in our case, weather.com) and the server starts to

talk back to your computer using a couple of different language, the most important

of which is HTML - **H**yper **T**ext **M**arkup **L**anguage - which is used to tell a web

browser how a page looks.

All of a web document's contents are transferred over the Internet using a set of

rules called **HTTP (HyperText Transfer Protocol)**. Such rules are often

called *protocols*, and there are a few different kinds used in the Internet. HTTP is the

most common one.

**Hops**

If you've watched the earlier video about how the Internet works, then you probably

noticed that machines connected to the Internet don't talk to each other directly.

Instead, *packets* of information sent across the internet might *hop* across many

machines on their journey from the *client* to the *server*. This makes the Internet

resilient to failures. Even if one path from a client to a server fails, another can still be

taken by the packets that are sent out.

However, this introduces a big problem. Every machine that a packet *hops*

*through* gets to keep that *packet* for a short time, during which it can be *read*.

**Security**

You might have noticed that web addresses often start with https://. The HTTPS is

the *Secure* version of the HyperText Transfer Protocol, and is used by almost all





WEB DEVELOPMENT 101

websites and web applications - the protocol guarantees that only the client and the

server can understand the information that is sent from one side to the other.

Watch the following video to learn more about how the Internet is used to send

information securely from you to the server and back.

https://youtu.be/kBXQZMmiA4s

**IP Address**

Just as every house is assigned a specific and unique postal address, all computers

connected to the Internet are also assigned an *IP Address*. IP stands

for **I**nternet **P**rotocol.

There are are two kinds of IP addresses: *IPv4* and *IPv6*.

An example of an IPV4 address looks like a combination of 4 numbers:

216.58.193.68

**IPv4** is the older version which allows for a maximum of around **4.3 billion** IP

addresses. While that might sound like a lot of addresses, it isn't anywhere near

enough to satisfy today's numbers of devices connected to the internet.

To satisfy the need for *addressing* the ever-growing number internet users and

devices, a new **IPv6** version was created that can provide *many more* addresses.

An example of a *full* IPv6 IP address would be:

2001:0db8:0000:0000:0000:ff00:0042:8329

Notice how the IPv6 address is much longer than IPv4? It greatly increases the

available address space.

How much more?

340,282,366,920,938,463,463,374,607,431,768,211,456 addresses

That's approximately 3.4×1038. That's a lot - we're not going to need another version

of IP addresses for a long while (if ever).

**Do you want to know what your IP address is?**

**The simplest way to discover your current IP address is by typing "What is my**

**IP" in Google search. Google will display your IP address at the top of the**

**search results page.**

**Domain Names**

Since IP addresses are unique, they are useful for computers to connect with each

other, but we humans have a difficult time reading them, or remembering them.

**Domains** associate an IP address like 216.58.193.68 with a string of text

like google.com. Thanks to the **Domain Name System** (DNS), both are

interchangeable. You can go to **http://216.58.193.68** or **http://google.com** and end

up on the exact same website.

When you type in a domain name into your browser's address bar, your browser

contacts the DNS to figure out its IP address, and then uses *that* to actually contact

the server that belongs to the domain.





WEB DEVELOPMENT 101

In short, a domain name is a unique, easy-to-remember address used to access

websites.

**What's a URL?**

**URL** stands for *Uniform Resource Locator*, it's simply a web address that uniquely

identifies a specific resource in the computer network or the Internet.

For example, the current page’s URL

is https://www.pupilfirst.school/targets/12078, and it can be divided in 3 parts:

· https:// is the protocol.

· www.pupilfirst.school is the domain.

· /targets/12078 is the path to a *resource*.

Watch the video below to learn more about how networks talk to each other, and

how the Internet works.

https://youtu.be/5o8CwafCxnU

**The Web**

The World Wide Web is commonly shortened to *WWW*, or simply called *the Web*.

A broader definition comes from the organization that Web inventor Tim Berners-Lee

helped found, the **World Wide Web Consortium (W3C)**.

**The World Wide Web is the universe of network-accessible information, an**

**embodiment of human knowledge.**

In simple terms, the World Wide Web is a network of public webpages connected to

one another so that information is exchanged between computers on the Internet.

**Note: The *Internet* and the *Web* are different things: The *Web* uses**

**the *Internet* to pass through information.**

**Webpage**

A *webpage* is a document on the World Wide Web, created using HTML, that can be

viewed in a web browser.

To access a webpage you can either:

·

·

Type its URL, like http://google.com in your Web browser...

...or click on a link, like **this one**.

**What's a website?**

**A *webpage* is a single HTML document. A collection of such documents,**

**usually linked to each other under the same domain is called a *website*.**

**Web browser**

A web browser, or simply *browser* is an application used to access websites.

Popular web browsers include Microsoft Edge, Google Chrome and Mozilla Firefox.

**In this course, we're using *Google Chrome* in all of our video demonstrations.**

**You can install Google Chrome by visiting this link.**





WEB DEVELOPMENT 101

We'll be using Visual Studio Code (VSCode) in many parts of this course. Watch the

following video to learn how to install VSCode on your system.

https://code.visualstudio.com/download

Let's begin using VSCode by installing the *Prettier* extension. Prettier helps keep our

code *pretty* (hence the name).

\---------------------------------------------------------------------------------------------------------------------------

Install Ubuntu in Windows, using WSL

**Important Note**: This lesson is for Windows users only. If you're using

macOS, or Linux, simply mark this one as complete and move on.

**Why Linux, why not Windows?**

You can develop perfectly fine on any operating system. However, many

developers choose Linux or OSX (Mac) as their development environment

because a lot of developer *tools* are built for Unix systems *first*. This makes

it typically (much) easier to set up on Unix systems. It is also generally

accepted that the Unix command line is superior to the Windows command

line.

In this course, we're assuming that you have access to a Linux

development environment because it makes it easier to build and maintain

the course content when it targets just one environment.

**Using WSL**

Follow the official Windows instructions for installing WSL on your

computer running Windows 10.

**https://docs.microsoft.com/en-us/windows/wsl/install-win10#manual-**

**installation-steps**

Notes

\1. You'll need administrative permissions on your computer to be able

to set up WSL.

\2. Most of you will want to follow the **manual installation steps**. As of

March 2021, the *Simplified Installation* feature of WSL is only

available to users of *Windows Insiders*.

The manual installation steps are quite easy to follow, so we

recommend following those steps instead of joining the *Windows*

*Insiders* program.





WEB DEVELOPMENT 101

\3. When you reach **Step 6 - Install your Linux distribution of choice**,

search for and install *Ubuntu 20.04 LTS* - this is the latest version of

Ubuntu available via the Windows Store.

\4. There are two versions of WSL; version 1 is older and is not

recommended. When you install Ubuntu, it should default to using

the newer version 2 of WSL.

You can make and host your very own website today!

Before we get started with programming in earnest, let's have some fun and create

our own websites!

Our first HTML page - in about 10 minutes

Watch and follow the steps below to make your first webpage!

The <img> tag - let's show an image in our page

All text and no pictures make any website boring :)

So, let's add an image to our page.

To learn more about various HTML tags, **W3Schools** is an excellent

resource.

<h1 style="background-color:burlywood;">

This is my first webpage and its title.

</h1>

<h2>

This is my second heading.

</h2>

<p>

This is my paragraph.

</p>

<img style="width: 150px;" src="backwater.jfif" alt="A scenic water image">

<h2>

A story about the time when I visited a backwater

</h2>

<p>

last year,I visited a backwater,before everything changed.

</p>





WEB DEVELOPMENT 101

Looking inside websites using "Inspect Element"

Every website you see on the internet is made with HTML tags just like the

ones you learned before.

And you can actually see their sources!

There are a few ways to access Google Chrome Inspect Element:

· Right-click anywhere on the webpage, and at the very bottom of the

menu that pops up, you will see *Inspect*. Click that.

· Click the hamburger menu (the icon with 3 stacked dots) on the far

right of your Google Chrome toolbar, click *More Tools*, then

select *Developer Tools*. Alternately, in the file menu, click *View >*

*Developer > Developer Tools*.

· Prefer keyboard shortcuts? Press ⌘+⌥+I on macOS, or F12 on

Windows to open *Inspect Elements* without clicking anything

· <h1 style="background-color:burlywood;">

·

B SHIVA KUMAR - personal info

· </h1>

· <p>

·

ECE Undergraduate pursuing Btech in Anurag group of Institutions,Hy

derabad.

· </p>

· <img style="width: 240px;;" src="shiva.jpg" alt="profile photo">

· <h2>

·

Career Objective:

· </h2>

· <p>

·

To secure a challenging position, where I can use my skills to cont

ribute to the benefits of organization and get an

opportunity to work with new technologies.

·

· </p>

· <h2>

·

Technical skills:

· </h2>

· <p>

·

·

·

C,

Python,

OOPS through Java,





WEB DEVELOPMENT 101

·

·

Matlab,

Machine Learning.

· </p>

**Important Reminder: If this target appears as *Locked*, please check Level 1**

**lessons, and make sure that you have completed all *milestones* (including**

**answering quizzes) before you start working on the assignment here.**

**Once you have moved up to Level 2, this lesson will include a *Complete* tab**

**that'll let you submit the link to your webpage for review.**

Once you make a website, it is no fun if it just sits in your computer and no one else

can see it.

So, in this tutorial we'll see how to upload it to the internet and get a URL through

which anyone in the world can access it!

Watch the tutorial, and then submit the URL to your webpage hosted on Glitch. We'll

try to visit it, and check to make sure that it's accessible. Submitting a link here will

let you move onto the next level.

Keeping *Cascading Style Sheets* (CSS) inside of HTML files isn't a common

practice. Let's start by learning how we can keep our styles in their own .css files.

To learn move about CSS, check out **w3schools.com, which has a very detailed**

**tutorial**. The number of different ways that you can style a web page is infinite.

You're limited only by your imagination, so take your time and experiment!

Recap: How to include CSS in your webpage

·

**Inline:** There's no need to use *selectors* here, directly include a style attribute in the

element. For example: <h1 style="color: red;">Heading</h1>

·

·

**Embedded:** We can place CSS in the HTML file using a <style> ... </style> tag.

**External:** The CSS is kept in a seperate file, and we use a link tag, like so: <link

rel="stylesheet" href="path/to/my/custom.css">. This is generally the preferred

way of writing custom CSS.

Index1.html

<link rel="stylesheet" href="index.css">

<h1 class="my-heading emphasis">

B SHIVA KUMAR - personal info

</h1>

<p>

ECE Undergraduate pursuing Btech in Anurag group of Institutions,Hyderabad

.

</p>

<img style="width: 240px;;" src="shiva.jpg" alt="profile photo">

<h2>

Career Objective:

</h2>





WEB DEVELOPMENT 101

<p>

To secure a challenging position, where I can use my skills to contribute

to the benefits of organization and get an

opportunity to work with new technologies.

</p>

<h2>

Technical skills:

</h2>

<p>

C,

Python,

OOPS through Java,

Matlab,

Machine Learning.

</p>

**Index.css**

.my-heading{

*background-color*:sandybrown;

*text-decoration*: underline;

}

.emphasis{

*font-style*: italic;

}

o/p:





WEB DEVELOPMENT 101

Learn more about CSS

Are you interested to learn more about what you've seen in the previous

lesson? Want to learn how to write custom CSS of your own?

Unfortunately, we don't have the time to dig deeper into CSS in *this* course.

However, we think that the best way to learn CSS is by *experimenting* with

it.

If you want a structured way to learn the traditional way of writing CSS, one

of your best options is to follow along with **a tutorial like the one offered**

**by w3schools.com**.

**Some suggestions**

\1. Follow along for the first few chapters, try things out in your web

page.

\2. Don't feel pressured to complete such tutorials - CSS is a *vast* topic.

\3. Skim through some of the options that CSS gives you - play around

with some CSS properties.

\4. Look at websites that you like and try to build elements that look

similar. This might seem difficult at first - use tutorials to learn more

about specific properties that'll help you achieve the look that you

want.

Finally, don't rush. As we've mentioned before, CSS is complex topic - give

yourself plenty of time to absorb all of the tools that it offers.

Introduction to Tailwind CSS

In this course, we're not going into detail about everything that you can do

with CSS.

CSS is a very large and complex topic that deserves a separate course of

its own.

So, instead of learning more about *traditional* CSS, we're going to quickly

jump over to using a *framework*. Developers often

use *frameworks* or *libraries* to make their job easier, and **Tailwind** is one

such CSS framework.

As we've mentioned in the video, one of things that a CSS library like

Tailwind does is to *reset* the base styles of all elements on the page to a

safe default.





WEB DEVELOPMENT 101

If you would like to learn more about why such a CSS reset is required, we

recommend reading the article **Reboot, Resets, and Reasoning**, authored

by Chris Coyier.

https://css-tricks.com/reboot-resets-reasoning/

https://tailwindcss.com/docs/installation#using-tailwind-via-cdn

index.html

<link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="style

sheet">

<h1 class="font-bold bg-green-400 text-3xl italic p-4">

This is my first webpage and its title.

</h1>

<h2>

This is my second heading.

</h2>

<p>

This is my paragraph.

</p>

<img style="width: 150px;" src="backwater.jfif" alt="A scenic water image">

<h2>

A story about the time when I visited a backwater

</h2>

<p>

last year,I visited a backwater,before everything changed.

</p>

<p>

last year,I visited a backwater,before everything changed.

</p>

o/p





WEB DEVELOPMENT 101

Working with Tailwind

Here's a whirldwind tour of how we can use some of Tailwind's features to

make a web-page look better. This video will also tell you where to go

to **learn more about Tailwind**.

It's important to note that Tailwind isn't the only option when it comes to

choosing a CSS framework. In the video, we've

mentioned **Bootstrap** and **Materialize**, but there are **more good options**.

Index.html

<link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="style

sheet">

<h1 class="font-bold bg-green-400 text-3xl italic p-4">

GUITAR..

</h1>

<div class="container mx-auto px-4 mt-4">

<!-- ... -->

<h2 class="font-bold text-xl my-2">

Musical instrument

</h2>

<img class="float-left max-w-auto md:max-w-lg mdimr-

4" src="guitar.jpg" alt="Image of Guitar">

<h2 class="font-bold text-xl my-2">

Few lines about guitar... :)





WEB DEVELOPMENT 101

</h2>

<p class="p-2">

The guitar is a fretted musical instrument that typically has six strings.

It is held flat against the player's body and played by strumming or plucking

the strings with the dominant hand, while simultaneously pressing the strings

against frets with the fingers of the opposite hand. A plectrum or individual

finger picks may be used to strike the strings. The sound of the guitar is pr

ojected either acoustically, by means of a resonant chamber on the instrument,

or amplified by an electronic pickup and an amplifier.

</p>

<p class="p-2">

The guitar is classified as a chordophone – meaning the sound is produced

by a vibrating string stretched between two fixed points. Historically, a guit

ar was constructed from wood with its strings made of catgut. Steel guitar str

ings were introduced near the end of the nineteenth century in the United Stat

es;[1] nylon strings came in the 1940s.[1] The guitar's ancestors include the

gittern, the vihuela, the four-course Renaissance guitar, and the five-

course baroque guitar, all of which contributed to the development of the mode

rn six-string instrument.

</p>

</div>

Tailwind's relationship with JavaScript

The usage of modern web development tools is deeply tied to the JavaScript

ecosystem. Learn how properly using a CSS framework like Tailwind is also

dependent on knowing your way around JS.





WEB DEVELOPMENT 101

What is JavaScript?

Most websites that you use these days will send code to your browser in these three

languages:

\1. **HTML - HyperText Markup Language**: Gives structure to a webpage.

\2. **CSS - Cascading Style Sheets**: Affects the look and feel of a webpage.

\3. **JS - JavaScript**: Adds behaviour, or interactivity to a webpage.

With this level, we're introducing you to the JavaScript.

So, let's begin learning the **most popular programming language** in the world!





WEB DEVELOPMENT 101

**Begin playing with strings**

Text values are represented by the String data type in JavaScript. Let's begin by

learning a few fundamental operations with String type values which are necessary

for building useful programs.

Introduction to strings

Strings are one of the fundamental type of values for representing text in

the JavaScript programming language. This lesson will teach you how to

create strings, store them in variables for later use and print them to the

web browser console for display.

**Additional reading: let, const and var.**

In this lesson, you've seen us define variables using the let keyword. For

most of this course, we'll be using the let keyword to create variables.

There are two other ways to create variables: const and var:

const

The const keyword creates immutable values. For example:

const MY\_STRING = "Hello world";

// The following line will cause an error.

MY\_STRING = "Another string";





WEB DEVELOPMENT 101

You'll often find constants being named using all-caps. This makes them

easy to identify. Constants, once created, cannot be reassigned to a new

value. Trying to do so will cause an error.

var

In older scripts, you may also find another keyword: var instead of let.

The var keyword is *almost* the same as let. However, it is an *old* way of

defining variables, and can have some surprising behavior. It is almost

never used in modern JavaScript code, and we will avoid using var as

much as possible in this course.

If you'd still like to learn more, here's an excellent resource on **the old**

**"var"**.





WEB DEVELOPMENT 101

Join strings together

You'll learn how to join multiple String type values into a single String type value.

This is one of the most frequently used features of strings in programming.





WEB DEVELOPMENT 101

**Switching to the VSCode editor**

Let's try writing, saving and opening an HTML file that also includes some Javascript.

Putting HTML and JS together

The <script> tag is used to embed client-side script (JavaScript) into HTML

pages.

The <script> element either contains the script itself, or it points to an

external script file using the src property.

Common uses for JavaScript are image manipulation, form validation, and

dynamic changes of content.





WEB DEVELOPMENT 101

Adding comments to HTML and JS

Comments are used to add documentation to your code. Comments are

always ignored when code executes.

With HTML and JS, the browser is most often where the code executes, so

while the browser may receive comments as part of website's payload, it

will simply ignore all comments that it sees.





WEB DEVELOPMENT 101

**Comments in HTML**

You can add comments to your HTML source by using the following syntax:

<body>

<!-- This is valid single-line comment. -->

<p>This is a paragraph.</p>

<!--

The same characters can be used to write multi-line

comments, just like this.

-->

</body>

**Comments in JavaScript**

Single line comments start with //. Any text between // and the end of the

line will be ignored.

var a = 2;

// Declare a, give it the value of 2

var b = a + 2; // Declare b, give it the value of a + 2

Multiple lines of comments can be easily written by starting with /\* and

ending with \*/. Any text between /\* and \*/ will be ignored by JavaScript.

/\*

The code below will change

the heading with id = "heading"

in my web page:

\*/

document.getElementById("heading").innerHTML = "My First Page";

**Continue playing with strings**

Let's continue learning about strings - we'll start writing code in files, in addition to

using the browser's developer console.

Find the length of a string

Here you'll learn how to find the number of characters present in a string (including

whitespace characters).





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Search for a string inside another string

When given a body of text, or a string value you may need to quickly find out if a

certain string is present within this other text or string value.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

String equality comparison

Here you'll learn how to compare two different strings and figure out if they

are the same or not.





WEB DEVELOPMENT 101

Sort a collection of strings

How do you arrange a collection of strings in random order into their

alphabetical order. This process is known as sorting. Here you'll learn how

easy it is to sort a collection of strings in JavaScript.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Split strings by a pattern

You'll learn how to split text into different string values based on a

repeating pattern. This is the opposite of joining where multiple strings are

combined or concatenated into a single string. Here we split an existing

string into multiple strings.





WEB DEVELOPMENT 101

Which built-in method returns the string representation of the number's

value?

**Your Correct Answer:** toString()

**Number Data Type**

In JavaScript both integers and floating-point numbers have a common Number

type. In other programming languages this is often not the case. You will learn the

essential operations on numbers for writing useful programs.

You'll learn how to:

\1. Perform basic calculations with numbers

\2. Comparing two numbers (boolean comparisons)

\3. Convert a number stored in string format to the Number type

\4. Take advantage of math functions already available in JavaScript





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

**Submission #1**

**Submitted on April 24, 2021**

**Question 1**

**Correct**

How can you convert a string to a number in JavaScript?

**Your Correct Answer:** Number()





WEB DEVELOPMENT 101

**Question 2**

**Correct**

Which represents an invalid number in JavaScript?

**Your Correct Answer:** NaN

**Question 3**

**Incorrect**

What do you think will be logged to the console by the following block of

code?

let a = 8 + "8";

console.log(a);

**Your Answer:** Nothing; an error will occur.

**Correct Answer:** A string 88.

**Question 4**

**Correct**

Which one of the two *area* variables would contain the

more *accurate* result?

let radius = 10;

let area1 = 3.14 \* Math.pow(radius, 2);

let area2 = Math.PI \* Math.pow(radius, 2);

**Your Correct Answer:** area2

**Question 5**

**Correct**

What do you think will be logged to the console by the following block of

code?

let add1 = "20" + 21;

let add2 = Number("20") + 21;

console.log("add1: " + add1);

console.log("add2: " + add2);

**Your Correct Answer:**

add1: 2021

add2: 41

**Boolean Data Type**

The boolean data type represents the values **true** or **false** in any program.





WEB DEVELOPMENT 101

Boolean - comparisons and logical operations

A boolean true or false value represents the result of comparing two values

whether they are of the String, Number or any other type. The JavaScript

language also has boolean operators.

You can build simple predicates (expressions which return a boolean type

value) and compose them with other predicates to build complex

conditions. These complex conditions often represent some rules or

policies in the real world which we can represent in the program.

In this lesson you'll learn how all of this works in practice.

**Special syntax: Single-line if-s**

In the above video, you've seen us write if followed by some code in curly

braces ({ ... }).

With simple statements, it's actually possible to leave out the curly braces.

For example:

// Using curly braces.

if (isValidPassword) {

console.log("This password is valid!");

}

// Leaving out the curly braces.

if (isValidPassword) console.log("This password is valid!");

Both the examples above do the same thing. The latter is simply shorter.

In most cases, you'll want to use curly braces to *contain* your code;

however, it is possible to leave it out if the result or action because of an

expression is simple.

Boolean - comparisons and logical operations

A boolean true or false value represents the result of comparing two values

whether they are of the String, Number or any other type. The JavaScript

language also has boolean operators.

You can build simple predicates (expressions which return a boolean type

value) and compose them with other predicates to build complex

conditions. These complex conditions often represent some rules or

policies in the real world which we can represent in the program.

In this lesson you'll learn how all of this works in practice.

**Special syntax: Single-line if-s**

In the above video, you've seen us write if followed by some code in curly

braces ({ ... }).





WEB DEVELOPMENT 101

With simple statements, it's actually possible to leave out the curly braces.

For example:

// Using curly braces.

if (isValidPassword) {

console.log("This password is valid!");

}

// Leaving out the curly braces.

if (isValidPassword) console.log("This password is valid!");

Both the examples above do the same thing. The latter is simply shorter.

In most cases, you'll want to use curly braces to *contain* your code;

however, it is possible to leave it out if the result or action because of an

expression is simple.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

**Object Literals**

It is a collection of **name-value** pairs for representing a logical unit of data.

**Object Literals - create, read & update + nesting objects**

At this point you know how to represent text values, numbers and write simple

boolean expressions. This is enough to represent pretty much any logical unit of

information from the real world.

Here you'll learn how to create object literals for representing a single logical unit of

data as **key-value** pairs.

You will also learn how to represent hierarchical information as nested objects.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

**Arrays**

Represents a collection of JavaScript values.

**Arrays - handling ordered values**

You'll learn how to use arrays as a container for a collection of JavaScript values.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

**Function**

A function is a piece of code that can be called multiple times. It is the building block

for writing larger programs. A large program is a collection of functions. A function

takes zero or more input arguments and either produces a side-effect or returns a

computed value.

Functions - Part 1

console.log is a function you have used numerous times by now. At the end

of this lesson you will have learned how to write your own functions.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Functions - Part 2

We will work on a longer example which is written in the procedural manner

and **refactor** it to use small functions.

When we **refactor** code the structure of the code changes. We do not change the

functionality or the existing behaviour of the code.

Programmers refactor the code they've written often to make it easier to read,

understand, and modify by themselves in the future, and also to make it easier for

other people to work with the same code.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Explicitly return a value from a function

A function like console.log performs a side-effect. It does not return any

value, but it prints the string we passed as argument to the web browser

console.





WEB DEVELOPMENT 101

In our programs we often need functions which can accept one or more

arguments, perform some work, and then return the result of that

computation.

In this lesson you will learn how to do this.

**Special Case: Single line functions**

There is one special case that you need to be aware of - single-line

functions. Here's an example.

let sumOfSquaresSingleLine = (x, y) => Math.pow(x, 2) + Math.pow(y, 2);

let sumOfSquaresMultiLine = (x, y) => {

return Math.pow(x, 2) + Math.pow(y, 2);

};

Both functions will return *sum of squares* of two arguments. However, note

how the *single-line* function omits the return keyword.

With such single-line functions, it is assumed that the result of the

expression is returned by the function - the return keyword isn't required.

However, when curly braces ({ ... }) are used to delimit the operations

performed by a function, the return keyword is **required** for the function

to *return* anything.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Passing a function as an argument

In JavaScript a function is also just a value like the string, number, boolean,

object or array. The implication is that you can pass a function itself as an

argument to another function. Because after all it also only a value, there is

nothing special about functions.

In this lesson you will learn about two functions available in the web

browser:

\1. setTimeout

\2. setInterval

Both these functions take a **callback** function as its argument. After a time

delay the **callback** function is executed.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Convert name to initials.

Now that you have a good idea of Javascript functions, let's test what you have

learned by attempting a small task to write a function.

The function should basically take an input name(a string) and convert the same to

initials, for e.g John Doe to JD.

Here are few conditions to be met:





WEB DEVELOPMENT 101

\1. A single-worded name must return the first two letters of the word as

initials. Eg. John should have an initial JO

\2. A two-worded name must return the first letter of each of the words in the

name. Eg. John Doe should have an initial JD

\3. A name with more words should return the starting letter of the first and the

last word as initial. Eg. John Doe Honai should have an initial JH

\4. The function should return all initials in uppercase.

We have attached a skeleton file and you are expected to just complete the empty

function without renaming the function that is present with the

name createInitialsFromName. Changing the function will lead to the rejection of your

submitted code.

**Important: Make sure you** return **the initials string from the function - do not**

**print it to the console.**

**JS file to complete the task**

*nameInitials.js*

Download the file above and complete the function createInitialsFromName with the

conditions mentioned above.

Once complete save and upload the file in the *Submit* tab of this module.

Good luck with the task! Have fun! :)

/\* This function should convert a name to initials. Here are few conditions to

be met:

\1. A single worded name must return the first two letters of the word as

initials. Eg. John should have an initial JO

\2. A two worded name must return the first letter of each of the word in

the name. Eg. John Doe should have an initial JD

\3. A name with more words should return the starting letter of the first

and the last word as initial. Eg. John Doe Honai should have an initial JH

\4. The function should return all initials in uppercase.

\*/

function createInitialsFromName(name) {

// Complete the function

let firstName = name.split(' ')[0];

let lastName = name.split(' ')[1];

let firstLetters = firstName[0] + lastName[0];





WEB DEVELOPMENT 101

return firstLetters;

}

module.exports = createInitialsFromName;

Need additional help?

To complete the *milestone target* in this level of the course, you'll need to

do some things that *haven't* been taught in the course.

This is intentional.

If you're having trouble creating a working solution for the

assignment, *this* lesson will give you some hints on how to proceed.

/\* This function should convert a name to initials. Here are few conditions to

be met:

\1. A single worded name must return the first two letters of the word as

initials. Eg. John should have an initial JO





WEB DEVELOPMENT 101

\2. A two worded name must return the first letter of each of the word in

the name. Eg. John Doe should have an initial JD

\3. A name with more words should return the starting letter of the first

and the last word as initial. Eg. John Doe Honai should have an initial JH

\4. The function should return all initials in uppercase.

\*/

function createInitialsFromName(name) {

// Complete the function

let words=name.split(" ");

let wordlen=words.length;

//console.log("Words length is "+wordlen);

//console.log("Name is "+name);

//console.log("Words are ----> "+words);

if(wordlen==1){

let x=name.charAt(0).toUpperCase();

let y=name.charAt(1).toUpperCase();

return x+y;

}else if(wordlen==2){

let

x=words[0].charAt(0).toUpperCase();

let

y=words[1].charAt(0).toUpperCase();

return x+y;

}else{

let x=words[0].charAt(0).toUpperCase();

let

y=words[wordlen-1].charAt(0).toUpperCase();

return x+y;

}

}

module.exports = createInitialsFromName;





WEB DEVELOPMENT 101

Iterating over an array using the forEach method

Information is often represented as a collection of values. In JavaScript this

neatly maps to an array of values.

So far you've learned how to apply a function to a single value to either

return a result or perform a side-effect like logging to the browsers console.

When you have an array of values the function can be repeatedly applied

to every value in that array. This is known as iterating over an array of

values.

You will learn about the forEach method for iterating over an array of values.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Generate an HTML list from an array

This is a practical application for the array forEach method. An HTML list will

be programmatically generated from an input array of string values.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

What does document.getElementById() do?

**Your Answer:** It selects all the element specified by the id

**Correct Answer:** It selects a single element that has that id

Using the index of the array value during iteration

Sometimes when iterating over an array value it is necessary to also know the index

of that value within the array. An example of this would be to display the values as a

numbered list.

In this lesson, we'll talk about a different form of the callback function passed to the

array forEach method. The first argument is the value and the second argument is

the index of the value in that array.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Nested Array iteration

It's pretty common to find arrays that contain values like strings, numbers,

objects and booleans. However the value inside an array can also be

another array.

For example, consider a 2-dimensional array. This is an array whose

values are themselves arrays. In JavaScript it'll look something like like this:

let values = [

[100, 99, 100], // index 0

[99, 99, 99],

[100, 100, 100] // index 2

];

// index 1

The values array contains 3 array items. Each array item contains 3 number

type values.

How do you iterate over such a 2D array? Or, how do you generate a 2D

array using iteration?

Let us learn about such arrays using an example where we render

multiplication tables to HTML.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Transforming from one array to another using the map method

You can apply a function to an array of values to produce a new array. This

function will be applied to each value in the input array. The resulting array

will contain the same number of items as the input array. The item at index

0 will be the result of applying the function on the item at index 0 of the

input array.

The array function which does this is called map.

The functionality of map can be simulated using forEach. In the section on

array iteration we used forEach to generate a list of HTML elements. Using

the map function is easier than doing the same using forEach.

Let us first learn how to use map function on an array of values. You will see

that most of what you learned about the functioning of the forEach function

applies here for map as well.





WEB DEVELOPMENT 101

Generate an HTML list from an array using the map function

It is better to use the map function to create a new array, rather than

simulating it using the forEach function.

This is demonstrated by refactoring an earlier example written

using forEach to generate an HTML list to instead use the map function.





WEB DEVELOPMENT 101

What does the map function do in JavaScript?

**Your Correct Answer:** It creates a new array with the results of calling a

function for every array element.

Using index of array value with map

Here we use the second argument to the callback function which tells us

the index of the current value when using the map function. This should

begin to look familiar if you know how this works when using

the forEach function.





WEB DEVELOPMENT 101

Transforming Nested Arrays

The multiplication tables we built earlier uses a 2-dimensional (2D) array. It was

generated through nested iteration. The outer iteration happened over the numbers,

and the inner iteration happened over the multipliers.

Here we will see how the code becomes simpler when the forEach is substituted with

the map function.





WEB DEVELOPMENT 101

The inner iteration generates a single table containing the multiplication line items.

This can be done using map. The outer iteration generates all the multiplication tables

which are arrays themselves. This too can be done using map.

Let us see how that can be done.





WEB DEVELOPMENT 101

Filter an array based on some criteria

Another operation that you frequently need to do on an array of values is to

select a few from the list, that match one or more conditions. We call this

filtering.

To filter an array we can use the array filter method. Whereas map returns

an array with the same number of values as the input array, this is not

necessarily true for filter.





WEB DEVELOPMENT 101

The result of filtering an array could return any number of results, up to the

original length of the array. This means that, depending on the criteria, the

resulting array could be empty (no element satisfies the criteria), the same

as the original array (all elements satify the criteria), or some length less

than the original array (some elements satify the criteria).

The filter function works very similarly to the forEach and map functions.

The callback function provided to a filter function should return

either true or false. The callback function is expected to run a test on the

array value. If it meets the filtering criteria, then return true. This includes

that value in the resulting array. If the callback function returns false the

corresponding value is excluded from the resulting array.

Let us try it out with a working example.





WEB DEVELOPMENT 101

What will be the output of the following code snippet:

console.log([-1,1,3,4,-5].filter((item)=>{

return item>0

}).length)

**Your Answer:** [1,3,4]

**Correct Answer:** 3

A minimal UI for filtering flight search results

You have used filters if you have done shopping, or booked tickets, or ordered food

online. Filters are very useful in narrowing down the number of items we want to look

at in the user interface.

Let us look at a narrow slice of filtering functionality common to most flight booking

apps.

This examples uses HTML & CSS to display a bunch of search results. The user can

then filter search results form the browser. We will write JavaScript which make this

functionality possible.

This small scale example will show you how most applications are implemented at a

larger scale.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Use the index of the array value with filter

Let us look at an example which requires us to know the index of the value

when using the filter function on an array.

You are provided the daily unique visitors to your webpage. The value at 0

index is the count for Monday, 1 for Tuesday, 2 for Wednesday, ..., 6 for

Sunday.





WEB DEVELOPMENT 101

This time-series data can now be filtered in various ways. Put another way

you can find out how many visitors arrived at your webpage over the

weekend etc.

Task: Create a function to filter data

**LearnDiscussComplete**

**Create a log date filter function**

Let's get hands-on and test what you have learned by trying to implement a

small function.

The function should accept an array of log entries (objects). Here's an

example log entry object to understand its shape.

{ name: "Johny" , date: "2021-01-21T02:53:42+05:30" }

The function should accept an array of these objects and return the names

of those entries whose date matches the current date, as a string. The

names should be separated by a comma.

For example, if today is the 21st of January, 2021 (2021-01-21), and the

function is given an array of these three entries:

[

{ name: "Johnny", date: "2021-01-21T02:53:42+05:30" },

{ name: "Sugar", date: "2021-01-22T02:53:42+05:30" },

{ name: "Sun", date: "2021-01-21T03:53:42+05:30" }

]

...the function should return the value Johnny,Sun.

Note how the names are separated by a comma without any spaces in

between.





WEB DEVELOPMENT 101

Here's a skeleton JS file, which you can download, where you need to

implement the function without changing the function name or any other

part of the file.

**JS file to complete the task**

*todaysEntries.js*

Download the file above and complete the function todaysEntries with the

conditions mentioned above.

Once complete save and upload the file in the *Submit* tab of this module.

Good luck with the task! Have fun! :)

**Intro & Setup**

Just a quick intro to what the canvas element is all about, and how you can set up

your system to complete this level.

Why should you learn about the HTML canvas element?

Install Node.Js on your PC and serve up some HTML & JS

**LearnDiscussMark as Complete**

**Installing Node.js**

To follow along with the lessons in this level, you'll need to first

install **Node.js**.

Node.js is an application that lets you run Javascript code on your

computer, outside of the browser. Click the following link to visit the

official *download* page for Node.js.

**https://nodejs.org/en/download/**

Download and install the package that matches your operating system.

On Windows

**Important note: The following information is relevant if you're trying**

**to develop directly in Windows. If you're using Ubuntu inside**





WEB DEVELOPMENT 101

**Windows using either WSL or Virtualbox, use the installation method**

**for Ubuntu (Linux) instead.**

If you have a computer running Windows, download the Windows Installer

(.msi) file - you'll want the *64-bit* version.

*Download the version matching for your operating system.*

Once you've downloaded the installer, run it by double-clicking on the file

and follow the instructions - use the default settings in the installer.

*Follow the instructions on the installation wizard.*

Once installation is complete, you should be able to run

the node and npx commands from the command-line. To test that out, open

up the command line application, and type in:

node --version

npx --version





WEB DEVELOPMENT 101

That should print output that looks like this:

*Test running node and npx on the command prompt.*

Node.js is now installed on your computer!

You can now use the npx http-server command from within directories that

contain HTML and JS files.

The first time you execute npx http-server, Windows may show your a

security alert. Use the following settings and *Allow* access to the

application.





WEB DEVELOPMENT 101

*Allow Node.js access only to "Private networks".*

Once the application is running, simply open the URL presented in the

terminal window in a web browser.

In some of the upcoming lessons, you'll be supplied with *"starter"* code as a

ZIP file which you can use to follow along. Download this *starter* code to

your computer, unzip it, open the directory on the command prompt, and

run npx http-server to make it accessible on your browser.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

First Steps with Canvas

Let's begin by playing around with the <canvas> element.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Dynamic Drawings

You've probably used applications like *Microsoft's Paint* to create images. So you

might be wondering why we went to the trouble of drawing a stick figure inside

a <canvas>, where every step had to be programmed in.

In this lesson, we're going to look at one situation where using a <canvas> lets us do

something that we would find difficult to do with static images.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Martial Arts Sim - Intro

Let's take a look at a project that's a bit more ambitious that what we've attempted so

far.





WEB DEVELOPMENT 101

Loading External Images

Let's begin working on our martial arts simulator!

To help you work on this project, we've prepared a collection of images that

we'll need to build this project.

In each of the upcoming targets, we're going to supply a *starter* ZIP archive

that contains all the image files necessary for the code we'll write.

https://www.pupilfirst.school/rails/active\_storage/blobs/eyJfcmFpbHMiOnsibWVzc

2FnZSI6IkJBaHBBbEpDIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--

5e2265826d4e35d8a1e74fce0a48192c5b2a03f1/loading-external-images-starter.zip





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Using Callbacks

Let's take a quick detour, and learn a bit about writing our own functions that accept

callbacks.





WEB DEVELOPMENT 101

Animating with Images

Let's make things move!

Here's a new *starter* ZIP that contains all of the images you'll need to

complete this lesson:

https://www.pupilfirst.school/rails/active\_storage/blobs/eyJfcmFpbHMiOnsibWVzc

2FnZSI6IkJBaHBBbE5DIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--

a7fd5a41cb3fa0dc6d2fb5b34d6988c34af571df/animating-with-images-starter.zip





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Loading Multiple Animations

More animations!

Here's a new *starter* ZIP archive that contains the new images you'll need to follow along

with this lesson:





WEB DEVELOPMENT 101

https://www.pupilfirst.school/rails/active\_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBB

bFJDIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--

c3fa79effec884723e7587163d6176698976d847/loading-multiple-animations-starter.zip





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Taking Control

Let's add some controls to our simulator!

If you've been following along with the lessons using the starter archive ZIPs that we've

provided, then you don't need to download the archive below to finish this lesson.

Instead, the following archive contains additional images that you can use to continue

working on the simulator after you've completed the lesson. We'll explain more about it in the

video below.





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101





WEB DEVELOPMENT 101

Recommended: Install Ubuntu using VMware Workstation Player

**Completed**

**LearnDiscussCompleted**

**Note: You'll need around one hour to complete installation of *VMware Workstation***

***Player* and Ubuntu.** This excludes the time required to download *VMware Workstation*

*Player* and the Ubuntu image file, which will depend on the speed of your internet

connection. If you know a friend who has these downloaded, you can fetch it from them to

save time!

**If you have doubts about any of these steps, or have suggestions on how to improve this**

**content, create a query on the web development community to let us know!**

Let's get started by installing *VMware Workstation Player*.

Install VMware Workstation Player

**VMware Workstation Player** will let us create *virtual machines* in your computer - that'll

let us emulate a system *within* Windows that's running a different OS.

You should download it VMware Workstation Player from its

website: **https://www.vmware.com/in/products/workstation-player/workstation-player-**

**evaluation.html**

VMware offers a free version of the software for non-commercial, personal and home use.

Download Ubuntu

The ISO (installation disk image) for Ubuntu can be downloaded from its official

website: **https://ubuntu.com/download/desktop**.

As of March 2021, the latest LTS (long-term support) version of Ubuntu available is 20.04.

Go ahead and download the ISO file for this version.

While it's downloading, we can create a new virtual machine using *VMware Workstation*

*Player*.

Create a new virtual machine (VM)

With *VMware Workstation Player* running, use the following steps:





WEB DEVELOPMENT 101

\1. Begin by clicking the *Create a New Virtual Machine* link.

\2. Select the *Installer disc image file (iso)* option, and browse to the Ubuntu ISO file

you'd downloaded earlier.

When you select the ISO, the software should show a message underneath the

selection saying *"This operating system will use Easy Install."*

\3. Fill in information required for the *Easy Install* process. This will include your full

name, a username, and password for logging into the OS.

\4. Next, you can name your virtual machine. You can leave these options at their

defaults.

\5. In the next step, you will be able to review the settings for the virtual machine. You

can also use the *Customize Hardware* option to change the configuration of the virtual

machine. However, the defaults should work perfectly fine.

The software will begin automated installation of Ubuntu. At this point, you may be asked to

install additional tools to help with the *Easy Install* process. If a dialog pops up asking for

installtion of such tools, confirm it to allow installation.

You'll need to wait several minutes for the software to complete installation of Ubuntu.

Once it's done, it'll present you with a login screen:

*The installation process should present you with a login screen at its end.*

Use the password you'd set earlier to login to the operating system.

When you log into Ubuntu for the first time, it may show some additional introductory steps -

feel free to skip these.





WEB DEVELOPMENT 101

*Feel free to skip the initial setup steps offered by Ubuntu.*

At this point, you have access to a fully functional system running Ubuntu.

Let's start by learning how developers often install tools on Ubuntu; we'll use Ubuntu's

package manager to install a set of tools commonly required for development.

Click *Activities* at the top-left (or just hit *Windows* key), and type terminal, and hit Enter or

click on it when the application is shown.





WEB DEVELOPMENT 101

*Launch the Terminal application using the Activities tab.*

In the *Terminal* window that opens, type in the following command:

sudo apt install build-essential

You may be asked to enter your password to authorize the installation.

This tells apt, the package manager, to install a collection of tools commonly used to

compile software, and one other application - htop.





WEB DEVELOPMENT 101

*Use apt to install build-essential and htop.*

The installation may take a few minutes. Once installation is complete, type htop to see your

information on system resource usage. It should list CPU usage for the number of CPU-s you

assigned, memory use, a list of running processes, and many other things.

htop

Press q to exit from htop. The q key is often used to quit from terminal applications that take

over the entire window.





WEB DEVELOPMENT 101

*Check out system resource usage using htop.*

That's it. You have a functional Ubuntu installation, and you know the most common way

used to install new packages on your virtual machine.

https://www.vmware.com/in/products/workstation-player/workstation-player-

evaluation.html

**Dashboard**

**Coaches**

BS

**Web Development 101**

**CurriculumReport**

Close





WEB DEVELOPMENT 101

Install Ubuntu in Windows, using Virtualbox

**LearnDiscussVisit Link to Complete**

**Note: You'll need around one hour to complete installation of Virtualbox and**

**Ubuntnu.** This excludes the time required to download VirtualBox and the Ubuntu image

file, which will depend on the speed of your internet connection. If you know a friend who

has these downloaded, you can fetch it from them to save time!

**If you have doubts about any of these steps, or have suggestions on how to improve this**

**content, create a query on the web development community to let us know!**

Let's get started by installing Virtualbox.

Install Virtualbox

**Virtualbox** will let us create *virtual machines* in your computer - that'll let us emulate a

system *within* Windows that's running a different OS.

You should download it Virtualbox from its

website: **https://www.virtualbox.org/wiki/Downloads**

Download Ubuntu

The ISO (installation disk image) for Ubuntu can be downloaded from its official

website: **https://ubuntu.com/download/desktop**.

As of March 2021, the latest LTS (long-term support) version of Ubuntu available is 20.04.

Go ahead and download the ISO file for this version.

While it's downloading, we can create a new virtual machine using Virtualbox.

Create a new virtual machine (VM)

In the Virtualbox application, create a new virtual machine (see screenshots below):

Begin by clicking the *New* button.

*Click the 'New' button.*

Use the following settings for creating the virtual machine. You'll find screenshots of these

steps below:

\1. For *Name and Operating System*, type in *Ubuntu for Web Development* as the name of the

VM we're creating. The *Type* and *Version* should automatically be set to *Linux* and *Ubuntu*

*(64-bit)*. Click *Next*.

\2. For *Memory Size*, set it to no more than half of your total system memory. We'll select 2 GB

(2048 MB) in this example. Click *Next*.





WEB DEVELOPMENT 101

\3. For *Hard disk*, leave it at the default option of *Create a virtual hard disk now*. Click *Create*.

\4. For *Hard disk file type*, leave it at the default setting of *VDI*. Click *Next*.

\5. For *Storage on physical hard disk*, leave it at the default setting of *Dynamically allocated*.

Click *Next*.

\6. For *File location and size*, we recommend that you increase the *File size* to at least 25 GB -

this will depend on how much free space you have on your computer's drives. Once you're

happy with the settings, click *Create*.

This will leave you with a brand new virtual machine waiting for an OS to be installed.

*Steps involved in creating a virtual machine.*

Install Ubuntu in the VM

*Double-click* on the VM entry or click the *Start* button after selecting it.





WEB DEVELOPMENT 101

\1. When the VM starts for the first time, you will be asked to *Select startup-disk*. Click the

folder icon on the bottom-left.

*Click the little folder icon at the bottom-right of the dialog.*

\2. In the *Optical Disk Selector* menu that pops up, click the *Add* button at the top-left,

navigate to the ISO file that you downloaded, and select it. Once it appears in the selector's

list, click the *Choose* button at the bottom-right.

*Select the ISO file that you downloaded to continue.*





WEB DEVELOPMENT 101

\3. With the ISO file selected, click *Start*. The Ubuntu disk image will now boot up in the

virtual machine - this process may take a few minutes - be patient.

*With the ISO selected, click the Start button.*

*It'll take a few minutes for the installation to load its interface.*

**If at any point during this process, your keyboard or mouse stop responding, it's**

**probably because the VM has *captured* them. By default, the *Right Control* key on your**

**keyboard will detach the keyboard and mouse from the VM and return it to Windows'**

**control.**





WEB DEVELOPMENT 101

\4. Eventually, the VM will load to a *Welcome* menu that offers two choices. Pick the option

to *Install Ubuntu*.

*Let's pick the 'Install Ubuntu' option.*

\5. The Keyboard layout should default to *English (US)*. Click *Continue*.





WEB DEVELOPMENT 101

*You shouldn't have to change anything here. Just click 'Continue'.*

\6. In the *Updates and other software* menu, select the *Install third-party software* option

before clicking *Continue*.





WEB DEVELOPMENT 101

*Let's include additional software to improve usability of Ubuntu.*

\7. In the *Installation type* menu, leave it at the default of *Erase disk and install Ubuntu*. You

can safely ignore the warning shown here. This action **will not** affect files on your Windows

computer because the hard disk is *also virtual* - remember that we created a *separate* virtual

disk image for this VM. Click *Install Now*.





WEB DEVELOPMENT 101

*You shouldn't have to change anything on this screen. Continue!*

\8. Click *Continue* when the installation asks you to confirm *changes to disks*. Installation to

the virtual disk will start at this point - however the process will ask for a bit more info while

it's copying files.





WEB DEVELOPMENT 101

*Confirm this dialog as well.*

\9. You'll be asked about your location and identity. Choose *Kolkata* as location

(Asia/Kolkata is India's timezone), and fill in your name, computer name, username, and a

password to log in. **Don't forget your username and password.** You'll need them later to

install applications in Ubuntu. Then click *Continue*.





WEB DEVELOPMENT 101

*The timezone should be automatically set. Change it, if it's incorrect.*

*Then fill in details to create a user account in Ubuntu.*

That's it - the installation process will continue to copy files, and download updates if you're

connected to the internet. Once it's done, it'll ask for confirmation to restart the VM.





WEB DEVELOPMENT 101

*Installation is complete! Restart the VM.*

Confirm the request and the VM will reboot. If you get an additional request to *remove the*

*installation medium, and then press Enter*, just hit *Enter* - VirtualBox should have

automatically removed the ISO image we mounted at the beginning of this process.





WEB DEVELOPMENT 101

*Just hit 'Enter' if this shows up.*

*The VM should restart into Ubuntu!*





WEB DEVELOPMENT 101

However, before continuing, we'll want to make a few improvements to our installation of

Ubuntu.

**Improve performance and usability of Ubuntu**

Once you're inside Ubuntu, there are a two things we can do quickly to improve performance

and usability.

\1. Install build-essentialfrom the terminal

Let's use Ubuntu's package manager to install a set of tools commonly required for

development.

Click *Activities* at the top-left (or just hit *Windows* key), and type terminal, and hit Enter or

click on it when the application is shown.

*Use the 'Activities' tab to search for installed applications. Open the Terminal app with it.*

In the *Terminal* window that opens, type in the following command:

sudo apt install build-essential

You may be asked to enter your password to authorize the installation.

This tells apt, the package manager, to install a collection of tools commonly used to

compile software. The next step will use some of these tools.

The installation may take a few minutes. Once installation is complete, move onto the next

step.

\2. Install VirtualBox Guest Additions

Click the *Devices* menu option and select *Insert Guest Additions CD Image...*





WEB DEVELOPMENT 101

*Insert the virtual CD into the virtual CD drive in the virtual machine... :-)*

A few seconds after you do this, Ubuntu should pop up an alert asking you if you'd like to run

software from the *CD* we just inserted. Click *Run*, and enter your password when prompted.





WEB DEVELOPMENT 101

*Select 'Run' from the dialog menu that pops up.*

*A terminal will pop open showing installation progress.*

The process running in the terminal should complete its work in a few minutes and ask you to

press *Return* (the *Enter* key) to close the window. Do so, and then restart your VM by using

the top-right dropdown, clicking the power button, and then choosing the *Restart* option.





WEB DEVELOPMENT 101

*Restart the VM to load it with VBox guest additions.*

Your VM should perform better now. You'll also notice that if you resize the VM window,

it'll automatically change the resolution of the VM's virtual *screen* to fit the Windows

application. The mouse pointer can now also freely move between Windows and Ubuntu

without getting *locked*, and you can even copy and paste text between Ubuntu and Windows,

share USB devices, and more.

\3. Increase the number of CPU cores assigned to the VM

By default, VirtualBox will assign only one CPU to the VM. If you have a system with more

than two CPU cores (pretty common these days), then you'll want to assign two or three to

the VM to allow it to perform better.

After shutting down the VM, head to *Settings* > *System* > *Processor*, and increase the number

of CPU-s assigned. In the example, I'm assigning 3 cores of a quad-core system. Hit *OK* to

confirm changes.





WEB DEVELOPMENT 101

*Increase the number of CPU cores assigned to the VM, if possible.*

Let's check if our VM has more CPU-s now - start it, and open up a terminal, and type in the

following command:

sudo apt install htop

You may be asked to enter your password to authorize the installation.

This tells apt, the package manager, to install the htop application. Once it's installed,

type htop to see your information on system resource usage. It should list CPU usage for the

number of CPU-s you assigned, memory use, a list of running processes, and many other

things.

htop

Press q to exit from htop. The q key is often used to quit from terminal applications that take

over the entire window.





WEB DEVELOPMENT 101

*htop is a system activity monitor! Press 'q' to exit from it.*

Visit Link To Complete

https://www.virtualbox.org/wiki/Downloads





WEB DEVELOPMENT 101


