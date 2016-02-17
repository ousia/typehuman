---
title: _typehuman_
subtitle. A Markup Language for the Humanities
author: Pablo Rodríguez
publisher: http://www.typehuman.tk
date: 2016
...

# Introduction

After using LaTeX for a decade and after switching to ConTeXt, I started using `pandoc` to generate (mainly) ePub documents.

_Markdown_—as implemented by `pandoc`, known as extended _Markdown_—has many nice features. But it may also be difficult to use with editors other than `emacs`, `vim` or similar ones.

I also help some people I know to typeset their books. I convert a Microsoft Word document to ConTeXt. But once the conversion is done, it is almost impossible for the other person to edit the document in ConTeX format. It would be also easier for me, if I could start working with a source in a lightweight markup language. So I would avoid the conversion and the other person could edit the work at will. And ePub generation would be much easier.

_Markdown_ might be an option to typeset books. but I’m afraid it might be too complex and not especially clear for people that have never dealt with markup. In fact, I tried to teach _Markdown_ to someone in order to have a source document that I could typeset automatically, but I failed. It was easier to convert from _Word_ to TeX and have the printed output with handwritten notes.

So I came with the idea to develop a new markup code. It is heavily inspired in _Markdown_. It also borrows some elements from _textile_. It might be considered a simpler and clearer _Markdown_. Or even _Markdown_ for simpler usage.

The new markup is called _typehuman_. This stands for “type humanities”, which is my background.

# Development Status

This document is still a draft. And in its very early stages. I want to finish it as soon as possible.

But I have plenty of other things to do. Also in the part of free time I spend writing.

# Design Principles

The main design principle in _typehuman_ can be summarized with “text markup for the rest of us”.

_Markdown_ and _CommonMark_ are great. It would be simply stupid to deny that its markup is wrong. What I’m afraid of is that they may be too complex for the average user.

The principles for designing _typehuman_ are—to the extent that it is possible—:

* Tagging should be visually consistent.

    Only one character for one mark. I mean, having underscore for both emphasis and strong emphasis makes mistakes easier to happen. At least, I’m not a cyborg (especially when I’m sleepy).

* Marks should be easy to type.

    Probably you won’t write your _typehuman_ documents with your smartphone.
    But you shouldn’t require a special editor to type the tagged text.

    Side–marking may be clearer to read, but it isn’t simple to write. Since _typehuman_ is a kind of extended markup made easy, it should have opening and closing tags—characters—also for all block elements.

* Tags should be simple (and also logically consistent).

    If divisions and spans are related in XML, I can’t see the point in marking them with different characters. They should use the same character.

The basic idea of _typehuman_ is such an easy markup that anyone could learn it.

# Elements

# Inline elements

## Emphasis and strong emphasis

Emphasis and double emphasis should be marked with different

# Block elements

# The two basic rules

There are two basic rules that build

* A paragraph is marked by a blank line. This rule applies also to lists.

* Indentation requires two spaces.

# Code blocks

Code blocks are exclusively marked with three baticks

## Dashes

As in TeX, you get en–dash is printed from two single dashes (`--`) and em–dash is printed from three single dashes (`---`).

# Comments

If you have something to say about _typehuman_, please [open an issue](https://github.com/ousia/typehuman/issues/new).

Just for the record. I think (you may think I should write “I’m afraid”) I have a pretty idea of how _typehuman_ should be. I must be getting old, because I have pretty strong opinions on it. (Once, this was called experience.)

But I’m open to new approaches. You only have to convince me with stronger reasons.

# License

© 20016 by Pablo Rodríguez. <http://www.typehuman.tk>. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

* Neither the names “typehuman”, “human” or any derived word from those ones—even phonetically—, nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

This software is provided by the copyright holders and contributors “as is” and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. In no event shall the copyright owner or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.

<!-- Licensing terms are simple:

* You may use this specification in source or binary forms.

* Acknowledgement is required to its original author and this website: <http://www.typehuman.tk>.

* Redistribution is allowed, but it should contain the warning to check the latest version at <http://www.typehuman.tk>.

* You may modify this specification and redistribute it.

    But first, you must use a different name than _typehuman_ or _human_—or any derived word from those, even phonetically—.

    And you must
-->
