# : What is Nutshell?

<iframe width="750" height="300" src="indexpage/splash.html" data-splash="yes"></iframe>

**Nutshell** is a tool to make "expandable, embeddable explanations", like this! They can even be [:recursive](#Recursion). (← click me 👆) This lets your readers learn what they need, just-in-time, always-in-context.

What's more, **you can embed explanations from _other_ webpages and authors, even stuff written _before_ Nutshell was made!** (Example: a snippet from [:my pretentious 2014 blog post](https://blog.ncase.me/explorable-explanations/#ProceduralRhetoric).) This works because Nutshell doesn't require writing in a new format – just good ol' headings, paragraphs, and links. This way, you don't have to write all your expandable explanations from scratch: you can just build upon others', and others can build upon yours.

But why not links? Well, unlike links, Nutshell lets you include *only* the snippet you need, not the whole page. And instead of a jungle of new tabs, your reader stays on one page, keeping their flow of reading. Even if you [:interrupt a sentence](#Interruption), Nutshell recaps the sentence afterwards, so your reader never loses context.

*But wait, there's more!* It's not just text & pictures you can embed! You can also embed [:interactive playthings](indexpage/malicious.html#InteractivePlay), [:YouTube videos](https://www.youtube.com/watch?v=i_RLYSaPvak), and – hey, why not – [:Wikipedia articles](https://en.wikipedia.org/wiki/Catgirl). (That includes [:other languages](https://fr.wikipedia.org/wiki/Baguette_(pain)) and [:Simple Wikipedia](https://simple.wikipedia.org/wiki/Universe), too!)

So: whether you're writing a blog, a news article, a glossary, educational material, code documentation, etc... I hope Nutshell helps you help _your_ readers.

Bite-sized, yet nutritious. Let's get crackin' with Nutshell!

# : How do I use Nutshell?

It's dead-parrot simple! Just copy-paste this *one line* onto your site: ([:more details](#IncludingNutshell))

<iframe src='indexpage/include_nutshell.html?url=full' width='750' height='22' data-include='yes'></iframe>

Then, to write a Nutshell snippet, just use headings & paragraphs. To embed a snippet, just make a link, but with a :colon in the front, <span data-fake-link>:like this</span>, so that Nutshell knows to make it expandable. ([:caveat](#CaveatOnLinking)) *Click to play the below 1-minute tuorial video:*

<video width="615" controls>
    <source src="indexpage/screenies/instructions.mp4" type="video/mp4">
    oh no! your browser does not support the video tag. :(
</video>

(even if you don't make links, the above one line of code makes all the sections of your blog post embeddable for *others*:)

<img src="indexpage/screenies/embedthis.gif" data-border="yes" width="400"/>

And that's all! To try Nutshell online, check out:

✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨    
👉 [**TRY NUTSHELL**: the interactive demo!](try) 👈    
✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨    

For more features & options, [check out the documentation!](https://github.com/ncase/nutshell#advanced-features--options)

# : Tips on writing Nutshells

If you'd like to explain something in a nutshell (ayyyy title drop), here's some advice:

* Show, *then* tell. Start with concrete examples & pictures, *then* lay down the abstract definitions.
* Write your first draft, get a word count (you can use [wordcounter.net](https://wordcounter.net/)), then cut 10% of your words.
* This ain't Wikipedia. Use your own voice, not Neutralese.
* I know recursion is fun, but *do* show restraint. [:Don't](#DontDoThis) [:stuff](#DontDoThis) [:your](#DontDoThis) [:explanations](#DontDoThis) [:with](#DontDoThis) [:Nutshells](#DontDoThis) [:like](#DontDoThis) [:this](#DontDoThis2). Embed only what's essential.

For more advice, see [:3Blue1Brown on making math explainers](https://youtu.be/ojjzXyQCzso?t=512), my [:Stanford mini-talk](https://www.youtube.com/watch?v=b-M2U3Jl1Cg#with_summary), or [:my FAQ](https://ncase.me/faq/#writing_accessible_explanations).

# : What inspired this?

Once upon a time, back when folks believed connecting the world's people would birth a new era of empathy and enlightenment (ha ha h*a hA HA HAAAAA--*)

...in that time, the inventor Ted Nelson proposed something called **StretchText**. The idea was this: you're reading an article at a high-level, but can "stretch" sentences into more detail. Then you can stretch *that* detail into more detail, and so on, while everything stays in one continuous context.

(See [:its original 1967 design document](#StretchTextOriginal), and Nelson [:showing it off in a Werner Herzog documentary](https://youtu.be/Bqx6li5dbEY?t=150))

Since then, the idea's been re-discovered a few times. In 2008, a viral website named [Telescopic Text](https://www.telescopictext.org/text/KPx0nlXlKTciC) let you stretch "I made tea" into a short story. In 2018, Wikipedia added a "hover to preview article" feature. ([:more StretchText-likes](#MoreStretchTextLikes))

And now, in 2022, I give you Nutshell! My main value-add, compared to previous StretchText-likes, is that you can embed snippets from *other websites & authors, even stuff written long ago*. That way, we can build upon each others' explanations.

Hey, maybe *that'll* birth the new era of empathy and enlightenment!

`NARRATOR: it won't.`

# : Who made this?

[:Nicky Case](#NickyCase) is to blame for this thing. This thing is [:open source](#OpenSource), available [on Github](https://github.com/ncase/nutshell).

**Special Thanks to**: Andy Matuschak, DominoPivot, Mike Cook, NachoBIT for gifting early feedback; [Kaira Imer](https://github.com/spaciecat) for writing code on an previous version; [Amber Thomas](https://twitter.com/ProQuesAsker/status/1440125223685165061) for inspiring the "dots opening & closing" animation.

Nicky <strike>panhandles on the internet</strike> was supported by these kind folks:

<iframe src='https://ncase.me/thanks/aug2022.html?credits=1&v=2' width='750px' height='400px'></iframe>

If you'd like to help Nicky keep making free educational stuff & talking about themselves in the third person, dispose of your disposable cash **[on their Patreon!](https://www.patreon.com/ncase)**

But seriously, thank you to everyone above. I appreciate y'all.

🥜,    
~ Nicky Case

## : Recursion

<img src="indexpage/sprites/recursion.gif" data-float="left" width="200"/>

**Recursion** is when something contains a copy of itself. It's often used in math and programming, to get infinite potential out of finite stuff.

See also [:recursion](#recursion).

## : Interruption

all work and no play makes jack a dull boy all work and no play makes jack a dull boy all work and no play makes jack a dull boy all work and no play makes jack a dull boy all work and no play makes jack a dull boy

## : Wikipedia's Hover To Preview

This thing:

![](indexpage/screenies/wiki.gif "a GIF showing Wiki's hover-to-preview feature; when a cursor hovers over a link, a preview of the article shows up in a bubble")

It only goes one level deep & only previews a few paragraphs, but it *is* helpful, and an inspiration for Nutshell.

Wikipedia is cool, ok? Give Jimmy your money.

## : Including Nutshell

To install Nutshell, you need to be able to edit the [:HTML](#HTML) of your blog/site. Here's instructions on how to do so [for WordPress](https://wordpress.com/support/adding-code-to-headers/), [for Tumblr](https://help.tumblr.com/hc/en-us/articles/230778847-Custom-HTML), and [for Ghost](https://ghost.org/tutorials/use-code-injection-in-ghost/#add-js-to-the-site-footer). I personally use [GitHub Pages](https://pages.github.com/).

Just paste this one line of code anywhere, preferably the header:

<iframe src='indexpage/include_nutshell.html?url=full' width='750' height='22' data-include='yes'></iframe>

Or, smaller "minified" file:

<iframe src='indexpage/include_nutshell.html?url=min' width='750' height='22' data-include='yes'></iframe>

(You can also download & re-host the files yourself {[full](https://cdn.jsdelivr.net/gh/ncase/nutshell/nutshell.js), [minified](https://cdn.jsdelivr.net/gh/ncase/nutshell/nutshell.min.js)}. Also, Nutshell doesn't require a package manager; I copy-pasted all dependencies into it. Like a *savage*.)

Alas, some platforms like Medium and Substack don't let you add *any* code, not even *one line.* You can't use Nutshell on those platforms. 😿

## : HTML/CSS/JS

Webpages are made of code. Specifically, 3 kinds of code: HTML, CSS, and JavaScript.

**HTML** is the page's raw content. (HTML = HyperText Markup Language)

**CSS** tells the page how to be stylish. (CSS = Cascading Style Sheets)

**JavaScript** tells the page how to be interactive. (JavaScript has nothing to do with the programming language Java. It was... some marketing thing? Ugh, programming sucks.)

## : Caveat on Linking

Alas, an annoying catch: the other webpage needs to *also* have Nutshell installed, or [:CORS](#CORS) enabled. If you own the other page, that's not a problem! But if not, you'll have to mirror/copy the other page. Sorry!

## : CORS

**Cross-Origin Resource Sharing (CORS)** are rules that exist because web security programmers are paranoid, and rightfully so.

Let's say you're visiting Facebook.com. Your web browser (Firefox, Chrome, Safari, Microsoft Edge, etc) pings Facebook, and Facebook gives you back your personal info. So far so good.

But now let's say you visit TotallyNotCyberCriminals.com. *If it weren't for CORS, this could happen:* the sneaky site makes your browser ping Facebook, Facebook sends back your info, and *bam*, the sneaky site now has your info. (Well, a different sneaky site.)

Browsers *could* say, "A site can only get info from itself: Facebook can only get info from Facebook, etc". But that'd make it impossible to do cool web things, like Nutshell.

So the security programmers chose a compromise: Site X can get info from Site Y _only if Site Y says Site X (or \*all\* sites) can have it._ These are rules for sharing resources across different sites, different origins. Hence: "Cross-Origin Resource Sharing".

P.S: [:a message for you web developers](#CORSForWebDevs)

## : CORS For Web Devs

If your webpage has no private info, I highly recommend setting your CORS rules to "*everyone* can get this page's info". That way, cool tools like Nutshell can easily embed your stuff!

Check out [Enable-CORS.org](https://enable-cors.org/) for how to do this. Personally, I host all my sites on [Github Pages](https://pages.github.com/) – *I promise this message is not sponsored* – which enables permissive CORS by default.

## : Don't Do This

don't do this.

## : Don't Do This 2

you just *had* to open all of these, didn't you?

## : Stretch Text Original Document

![](indexpage/screenies/StretchText.png)

## : More StretchText-Likes

From top-to-bottom: [Wikiwand](https://en.wikipedia.org/wiki/Wikiwand), [LessWrong](https://en.wikipedia.org/wiki/LessWrong), [Gwern.net](https://www.gwern.net/)⤵ ("retweets are not endorsements", yadda yadda...)

<img src="indexpage/screenies/stretchtextlikes.png" width="500"/>

There's probably many more StretchText-likes, but I haven't heard of 'em.

## : Nicky Case

<img src="indexpage/sprites/nicky.png" data-float="left" width="200"/>

Nicky Case is an internet person who explains stuff with games, "games", and pictures with words. See what they've wrought upon humanity at [ncase.me](https://ncase.me).

## : Open Source

**Open source** code is (*usually but not always\**) code that's free to use, remix & re-distribute – even for profit, with no or few\** requirements.

\* "Free" is an annoyingly confusing word. *Very roughly speaking,* think "free as in freedom of the press", not necessarily "free as in Wi-Fi at Starbucks."

\** One common requirement is "give credit". Fair enough. Some open source licenses go further: they require that your remix *also* be published under the same license. These are called **copyleft** licenses. Licenses without that requirement are called **permissive** licenses.