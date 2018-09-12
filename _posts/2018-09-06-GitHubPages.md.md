---
layout: post
title: Introduction to Github Pages (and Markdown and Jekyll)
description: Learning about encoding
---

# Creating a Github Pages Website

## Introduction

Recently flat HTML platforms [like Jekyll][1] have been getting lots of buzz: they load quickly and don't have all the overhead of a database-driven platform like Wordpress. Once the system is set up they're remarkably easy to use, but the setup is more complicated than "out of the box" solutions like Wordpress. As we learn about Jekyll and Github Pages, we will largely follow Barry Clark's tutorial, [Build A Blog With Jekyll And GitHub Pages][2], though some details have changed since 2014. 

## Step 1: Set up a Github Account

If you don't yet have a [Github][3] account, you'll need to sign up for one. You'll be able to use a free Github account for this class, but if you decide to continue using Github for other projects, you might consider applying for an free [Github Education Account][4]. 

## Step 2: Find a Theme You Like and Fork It

As of last year, all Jekyll themes should work with Github pages, though some require more tinkering than others. Check out [this list of supported Jekyll themes][5], sorted by how many people like them. Find one you like, but make sure it's a theme that supports blogging. The easiest way to know is to see if there's a folder titled `_posts` in the repository after you fork it.  We can work during the semester to customize these themes, so it doesn't need to be perfect: just good enough. When you click on a theme name in this list you'll see its files. Most of these pages will include a link to a sample site, which will give you a sense of what your site would  look like.

Once you've found a theme you like, we will fork the repository. Don't worry if that phrase sounds like nonsense: we'll do it together and I'll explain what it means.

## Step 3: Review Your Site's Structure

Once everyone has their own Github Pages repository, we will spend some time studying the structure of a Jekyll website together. I will show you where to find the files for static pages, blog posts, and basic configuration files.

## Step 4: Edit the \_config.yml File

The \_config.yml file includes all the basic configurations for a Jekyll website. We need to customize these for each of your individual sites. We will work through this together as well.

## Authorize Prose

There are different ways to edit the files for your Github Pages account. You can simply edit files directly (I'll show you this today) and you can sync the files with your desktop and use an application on your computer (I'll show you this in the future if you like. [Prose.io][6] is a useful application for editing the files online, and that's what we'll use today and next Monday for learning how to edit your website using Markdown.

## Step 6: Edit at Least One Page

We will work together to edit at least one of your site's pages, so that you know what to do to edit others going forward. To work with Jekyll's content you'll need to know how to use the Markdown text convention (see below). 

## Step 7: Create a Sample Post

We will work together to create one sample post, which will be much like editing a page save some different metadata in the header. Here too you'll use the Markdown text conventions to edit your posts (see below). 

## Step 8: Customize Your Pages and Begin Blogging

## Other Jekyll/Github Pages Resources

1. Other [Jekyll themes][7] that will work with Github Pages, though they might require a bit more tinkering. 
2. Amanda Visconti's [Jekyll/Github Pages tutorial][8] at the Programming Historian

# Writing in Markdown

## What is Markdown?

Markdown is a lightweight standard for writing in plain text while encoding the **structure of your document** for later representation in a format like Word, PDF, or HTML. If you have ever marked up a text using HTML tags, Markdown works quite similarly, but uses simple typographical symbols to encode text rather than longer HTML tags. There are a number of *affordances* to working in Markdown, including:

1. Simplicity. Because Markdown is a plain-text system of encoding structural elements typographically—rather than, as in proprietary formats like `docx`, though hidden, underlying code—Markdown files are small in size and simple to compose. You do not need to interrupt your writing to format your document while writing in Markdown.
2. Flexibility. When writing in Markdown you encode directions for styling your text, but you do not style it directly. Because of this, an `md` file can be easily converted to many other standard file types, including `html` or `pdf`. You can easily convert a single `.md` file into a range of other formats, giving you flexibility when you wish to publish your writing. When you send me your fieldbooks in Markdown, our website will translate the Markdown you wrote into HTML for display online. 
3. Durability. Unlike files composed in specific version of proprietary software, Markdown files are, essentially, plain text files. This means they can be opened by a wide range of applications and they will look essentially the same, and that they are not subject to the vicissitudes of software updates or platform dependencies. You can open and edit a Markdown file on virtually any computer, and you will likely be able to do well into the future. Even if the conventions of Markdown are no longer understood, the central text should remain widely compatible and portable. 

As with any medium, of course, there are also *limitations* to writing in Markdown, such as:

1. You have less granular control over the appearance of your text than you would in a full featured word processor. In order to ensure the flexibility and durability of Markdown, its grammar is relatively constrained. While you can indicate text should be `bold` or formatted in a `numbered list` using Markdown, for instance, you could indicate that one paragraph's font should be 2 points larger than another. 
2. You typically have to convert Markdown files into another format before publication. This is not *quite* true on the web, where some frameworks (like [Jekyll]()(https://jekyllrb.com/), in which our class website is built) can understand Markdown directly, but usually the production stage for a Markdown document involves converting you `md` file into another format and converting its structural encoding into actual stylistic changes.

For our class, writing in Markdown will help you reflect on the relationship of your texts' structure to the media of their presentation. If you follow the Github Pages option for your website, you will edit your pages and write your posts in Markdown using [Prose.io][10] or one of the desktop applications listed below.

## Markdown References

Below I will describe the most common Markdown syntax, but for additional reference you can consult:

+ The [Markdown Wikipedia page]()(https://en.wikipedia.org/wiki/Markdown), which includes a very handy chart of the syntax.
+ John Gruber's [introduction to Markdown]()(https://daringfireball.net/projects/markdown/syntax). Gruber developed the standard and knows what he's talking about!
+ This [interactive Markdown tutorial]()(http://www.markdowntutorial.com/), which will teach you the syntax in a few minutes.
+ You can also download [the Markdown version of this page]()(https://raw.githubusercontent.com/rccordell/s18tot/gh-pages/\_posts/labs/2018-01-12-Lab1-Markdown.md) if you'd like to compare what you see in your browser with the marked-up text that created it.

In short, in Markdown your text will not include any visible stylistic variations such as italics or bold text; Markdown is a *plain text* format. However, if you're using an editor such as [Prose.io][15] you will be able to preview the way your documents will look like when they're styled.

## Applications for Writing in Markdown

One advantage to this flat-text format is that you can write valid Markdown in many, many editors, including the free text editors (such as TextEdit on the Mac or Wordpad on the PC) that come with most computers. You can also write in Markdown in my favorite writing application, [Scrivener]()(https://www.literatureandlatte.com/scrivener.php). 

There are many dedicated Markdown composition applications with additional features, such as syntax highlighting or the ability to preview what your documents. Some are paid, but here are some free ones:

+ [Macdown]()(http://macdown.uranusjr.com/) (Mac)
+ [Mou]()(http://25.io/mou/) (Mac)
+ [Markdownpad]()(http://markdownpad.com/) (Windows XP-8)
+ [Markdown Edit]()(http://markdownedit.com/) (Windows)
+ [Ghostwriter]()(http://wereturtle.github.io/ghostwriter/) (Windows & Linux)
+ [Remarkable]()(https://remarkableapp.github.io/) (Linux)
+ [Hashify]()(http://hashify.me/IyBUaXRsZQ==) (online) 
+ a bit more complicated to get started with, but [Atom]()(https://atom.io/) is more full-featured than some of those above (Mac, Windows, Linux)

To write your blog posts using these desktop applications, you will need to sync your Github repository, which I can show you how to do next week.

## Markdown Syntax

So, a few basics:

1. If you want your text to be italicized, then *enclose it in single asterisks*. (i.e. \*enclose it in single asterisks\*).
2. If you want your text to be bold, then **enclose it in double asterisks**. (i.e. \*\*enclose it in double asterisks\*\*).
3. To start a new paragraph, simply hit return twice, so that you see a single line space in between paragraphs.
4. To start a new line without a paragraph break, add two spaces to the end of the first line and then hit return once.
5. To create a hyperlink, enclose the [words you want linked in brackets and the link in parentheses following]()(http://s17tot.ryancordell.org/). 
	i.e. [words you want linked in brackets and the link in parentheses following]\(http://s18tot.ryancordell.org/\)    

You can also create headlines of descending sizes, lists (numbered or bulleted), footnotes, block quotations, embedded images, and more. See the reference materials above for details on these other elements. 

[1]:	https://jekyllrb.com/
[2]:	https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/
[3]:	https://github.com/
[4]:	https://help.github.com/articles/applying-for-an-academic-research-discount/
[5]:	https://github.com/topics/jekyll-theme?o=desc&s=stars
[6]:	https://prose.io/
[7]:	http://jekyllthemes.org/
[8]:	https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages
[10]:	https://prose.io/
[15]:	https://prose.io/
