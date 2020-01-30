title:
permalink: jekyll
tags: tests 

this is really for me, not for you but ok.

the most annoying difference between [blot](blot) and [jekyll](jekyll) is that the live website on [github](github) pages doesn't update immediately — sometimes it doesn't update until 20 minutes later and so when you look at the site you don't know if what you did isn't working, or the old version of the site is stuck in the cache, or the site hasn't been generated yet or it has failed to build the site.

THEREFORE THE MOST IMPORTANT THING IF THE NEW SITE IS NOT LOADING IS TO CHECK YOUR EMAIL BECAUSE YOU WILL GET AN EMAIL IF THE SITE FAILED TO BUILD. 

i guess the solution to this is to run jekyll on your own machine so you can preview it locally but there are differences between the way jekyll interprets the code locally to the way its interpreted on github pages :(

the second most annoying difference

<hr>

30-1-20 :

if you set things up properly it's not difficult to start again with a clean version of the site 🙂

but why would you do that?

because for one reason or another which is not made clear the build of the site fails which is why :

THE MOST IMPORTANT THING IF A SITE IS NOT LOADING IS TO CHECK YOUR EMAIL BECAUSE YOU WILL GET AN EMAIL IF THE SITE FAILED TO BUILD. 

----------------------







----------------------

#### this is probably useful

cheatsheet : https://devhints.io/jekyll

If you want a page not to appear in the menu, set the title in the front matter of the page to ``&nbsp;``. Simply leaving the title blank does not work!

*Or does it?*

----------------------

29-1-20 : the main problem with site at the beginning of the day (and the latter half of yesterday) was that it puts the title at the top of the page twice for no good reason. that is now fixed as describe below.

the #1 problem now is that i don't want the list of posts on the front (index)page. it doesn't seem to matter which template i assign to it.
	maybe i can make my own template?

<hr>

i need :
- more space around the horizontal rules but the css code that i put in didn't work but i am hopeless at css.
- no capitals in titles but the css code that i put in didn't work but i am hopeless at css.

----------------------

### does frontmatter matter?

---  the documentation says you need to have three dashes and at least a blank line and then another three dashes in order for jekyll to generate the page but i have mad posts that have nothing at all except the page content and they work fine. ---

for example 

what you do need for a file to be interpreted as a dated post is for it to be named with the date and then a dash and some letters. if you don't nominate a title, this will be the title.

eg 2020-01-29-post.md

----------------------

### double titles

out of the box jekyll put the title of a page twice which is really stupid and you need a plug in to fix it.
https://github.com/benbalter/jekyll-titles-from-headings

additional considerations : https://talk.jekyllrb.com/t/title-derived-from-heading-appears-twice-on-top-of-page/1686/4

### on the index page is this notice

Content added below the "---" mark will appear in the home page between the top bar and the list of recent posts.

To change the home page layout, edit the _layouts/home.html file.

See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults


# things to investigate

submodules

https://help.github.com/en/github/working-with-github-pages/using-submodules-with-github-pages

## not jekyll but old blot notes

### headline3

Test.[^This is an inline footnote.]

#### headline4

a footnote with the referred tekst in small and grey font online and it autonumbers the footnotes so the first footnore is always 1 it doesn't seem to matter what number you give it yourself[^3]

[^3]: <small>see?  it autonumbers the footnotes so the first footnore is always 1 it doesn't seem to matter what number you give it yourself</small>

------

**bold**

*italic* or _italic_

~~strike~~    

<strike>a hack in my template on blot make this tekst appear highlighted</strike>

<small>small text</small>

{>|} and this is some text that sits in the white space on the left and if it isn't too much, like one sentence it is good.

{|<} puts it in the space on the right and you can put some space in it — by using the old use view source to see this  &nbsp;<br>&nbsp;<br>

<small>[apologies to derwent may](apologies-to-derwent-may)</small>

------

an autoplaying sound file

<audio autoplay src="http://johannesk.com.s3.amazonaws.com/2019/we%20are%20fine%20sharon%20van%20etten%20WFMU%2028-01-2012.mp3" preload controls></audio>

----------------------

this is some text and [this is a link to a site where you can get colour codes](https://www.w3schools.com/colors/colors_shades.asp) more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and if you put a ~tilde~ in front of a word that's what happens and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and what you get is[^1]this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and you can highlight some text but you need to use a hack by manipulating the css for the actual strike tag and then <strike>what you get is this</strike>. this is some text and this is some more text and here is a whole lot more text and copy and paste that text and what you get is this : some text and this isomer more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this is more text and here is a whole lot more text and copy and paste that text and what you get is



<h1 id="anchor">This is an anchor</h1>
so you can link to this part of the page with http://www.johannesk.com/misc/test#anchor

this is some text and  [here is yet another link to google](google.com)  more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this  is some more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this  is some more text and here is a whole lot more text and copy and paste that text and what you get is[^2]this is some text and this is some more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and you can highlight some text but you need to use the actual strike tag and then <strike>what you get is this</strike>. but [it's a hack](https://codepen.io/anon/pen/KbgjYV?&editable=true). this is some text and this is some more text and here is a whole lot more text and copy and paste that text and what you get isthis is some text and this  is some more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this isomer more text and here is a whole lot more text and copy and paste that text and what you get is this is some text and this is more text and here is a whole lot more text and copy and paste that text and what you get is

> of course this is a block quote and it is good and beautiful and if you have them it is great but you don't always need them so you should only use them if you actually do otherwise you forget about it.

[^1]: this is the first footnote 
[^2]: this is the second footnote 

<html><text-align:right>if you want to align something to the right you have to use html.</html>

<a href="http://www.johannesk.com/misc/test#anchor">anchor test


