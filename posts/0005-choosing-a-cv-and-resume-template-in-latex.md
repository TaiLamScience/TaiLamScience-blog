# 5: Choosing a CV and résumé template in LaTeX

I made a résumé in LaTeX when I needed to apply for a job about 2 years ago, and it was not great.
While it served its purpose, I wasn't happy with it when it came to long-term code upkeep.  (I can't
remember the source of the template for my first "real" résumé.)  The template I chose at the time
had weird quirks, and I told myself I'd tried to get a simpler template the next time I needed to
make a CV/résumé.

Well, I got my head start on a maintainable résumé now.  Better start now, while I have the time to
properly component test everything.<!--more-->

I was sort of reminded of myself, back when I was writing my undergraduate research paper.  I chose
a previously created and known LaTeX environment for pseudocode.  Initially, I believed the one I
had chosen the environment that was easiest to use, but then it turned out that it didn't break over
page breaks at all.  I ended up manually creating page breaks in LaTeX to match the actual printed
output in a [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG), which is not in line with the
[WYSIWYM](https://en.wikipedia.org/wiki/WYSIWYM) mindset of LaTeX.  (I will make sure that doesn't
happen the next time I write a scientific paper.)

So, what's the difference?  Armed with only my GrapheneOS phone, DuckDuckGo, and the Cromite
browser; I only sifted through the first page of results.

First, I found an [article](https://www.baeldung.com/cs/latex-moderncv-resume) from Baeldung, which
is a website I've gotten some helpful Linux and programming related tips from.  However, I found the
final result to be like the New Age templates on Typst, which really just look like a very polished
Microsoft Office résumé that most people would make (which isn't bad, but I really wanted to still
use [Computer Modern](https://en.wikipedia.org/wiki/Computer_Modern)).  Also, I'm not a fan of the
numeric bar numbers for each skill you have.  I've learned quite a number of (surprisingly) useful
bits of knowledge from video games, but the numeric RPG-style skill tree progression isn't one of
them.

Thanks for explaining each part of the LaTeX template, though.

Second, I found an [article](https://latex-tutorial.com/cv-latex-guide/) on LaTeX Tutorial about a
minimalistic CV/résumé.  It was getting closer to what I wanted (part of which included not moving
too far away from the default Computer Modern font.

However, it changed the majority of the text (or at least used a non-default font type almost
immediately in the preamble).

Maybe I would've chosen this if I was making this for my first real job outside of undergrad
studies, but I felt I could do better.

The third and last was a CV/résumé template posted onto [GitHub](https://github.com/sc932/resume) in
October 2016.

As they say in vintage carnival contexts that are inspired by something out of _Cuphead_:

> We have a winner!

This is the LaTeX [file](https://github.com/sc932/resume/blob/master/ScottClarkCV.tex) for the CV
(with its corresponding [PDF](https://github.com/sc932/resume/blob/master/ScottClarkCV.pdf)) and
this is the LaTeX [file](https://github.com/sc932/resume/blob/master/ScottClarkResume.tex) for the
résumé (with its corresponding [PDF](https://github.com/sc932/resume/blob/master/ScottClarkResume.pdf)).

The last file needed is the style [file](https://github.com/sc932/resume/blob/master/shading.sty).

I'm not sure why I was so successful now, compared to when I was finishing my undergrad studies --
but I'll take it.

