% typehuman: a markup language for the humanities
% Pablo Rodríguez

# Introduction

After using LaTeX for a decade and after switching to ConTeXt, I
started using `pandoc` to generate HTML and ePub output.

`markdown`---as implemented by `pandoc`---has many nice features, but it
may also be difficult to use for editors other than `emacs`, `vim` or
similar ones.

I also help some people I know to typeset books. I convert a Microsoft
Word document to ConTeXt. But once the conversion is done, it is
almost impossible for the other person to edit the document in TeX
source. And it would be easier for me if I could start working with a
source in a lightweight markup language. So I would avoid the
conversion and the other person could edit the work at will.

`markdown` might be an option, but I’m afraid it might be too complex
and not especially clear for people that have never dealt with
markup. In fact, I tried to teach `markdown` to someone in order to
have a source document that I could typeset automatically, but I
failed. It was easier to convert from Word to TeX and have the printed
output with handwritten notes.

So I came with the idea to develop a new markup language. It is
heavily inspired in `markdown`, but it also borrows some elements from
`textile`. It might be considered a simpler and clearer `markdown`. Or
even `markdown` for simpler usage.

The new language is called `typehuman`. This stands for “type
humanities”, which is my background.

# Inline elements

# Block elements

# The two basic rules

There are two basic rules that build

* A paragraph is marked by a blank line. This rule applies also to lists.

* Indentation requires two spaces.

# Code blocks

Code blocks are exclusively marked with
# Dashes

As in TeX, you get en--dash is printed from two single dashes (``) and em--dash is printed from three single dashes.
