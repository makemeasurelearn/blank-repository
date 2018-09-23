# Style Guide

## Contents


##### [About](#1%20about) | [General](#2%20general) | [HTML](#3%20html) | [CSS](#4%20css) | [Notes](#5%20notes)


## 1 About

This document is based on the [Google HTML/CSS style guide](https://google.github.io/styleguide/htmlcssguide.html) and others, as cited. The purpose of this document is to define the format and style for HTML and CSS. The syntax of this document is [https://help.github.com/articles/basic-writing-and-formatting-syntax](GitHub Flavored Markdown) (GFM), licensed under [https://creativecommons.org/licenses/by-sa/4.0](Attribution-ShareAlike 4.0 International) and has been validated by [https://atom.io/packages/linter-markdown](linter-markdown) 5.2.2.

## 2 General
-   ### 2.1 General Style
    -   #### 2.1.1 Protocol
    -   Use the HTTPS protocol for embedded resources where possible
-   ### 2.2 General Format
    -   #### 2.2.1 Indentation
    -   Two spaces per `tab`
    -   Use [https://atom.io/packages/atom-beautify](Atom-Beautify) to format
    -   #### 2.2.2 Capitalization
    -   Use only lowercase unless `text/CDATA`
    -   #### 2.2.3 Trailing whitespace
    -   Remove trailing white spaces.
-   ### 2.3 General Meta
    -   #### 2.3.1 Encoding
    -   Use UTF-8 (no BOM). Make sure your editor uses UTF-8 as character encoding, without a byte order mark.
    -   #### 2.3.2 Comments
    -   Explain where possible
    -   #### 2.3.3 Action items
    -   Mark todos and action items only with keyword `TODO`.
    -   Append a contact `TODO(John)`
    -   Append action items after a colon as in `TODO : action item`

## 3 HTML
-   ### 3.1 HTML Style
    -   #### 3.1.1 Document Type
    -   HTML5 (HTML syntax) is preferred for all HTML documents: `<!DOCTYPE html>`
    -   #### 3.1.2 HTML Validity
    -   Use valid HTML where possible.
    -   [https://google.github.io/styleguide/htmlcssguide.html#HTML_Validity](Example)
    -   #### 3.1.3 Semantics
    -   Use HTML according to its purpose.
    -   Use elements (sometimes incorrectly called “tags”) for what they have been created for. For example, use heading elements for headings, p elements for paragraphs, a elements for anchors, etc.
    -   Using HTML according to its purpose is important for accessibility, reuse, and code efficiency reasons.
    -   #### 3.1.4 Multimedia Fallback
    -   Provide alternative contents for multimedia.
    -   For multimedia, such as images, videos, animated objects via `canvas`, make sure to offer alternative access. For images that means use of meaningful alternative text (`alt`) and for video and audio transcripts and captions, if available.
    -   #### 3.1.5 Separation of Concerns
    -   Strictly keep structure (markup), presentation (styling), and behavior (scripting) apart, and try to keep the interaction between the three to an absolute minimum.
    -   That is, make sure documents and templates contain only HTML and HTML that is solely serving structural purposes. Move everything presentational into style sheets, and everything behavioral into scripts.
    -   In addition, keep the contact area as small as possible by linking as few style sheets and scripts as possible from documents and templates.
    -   #### 3.1.6 Entity References
    -   There is no need to use entity references like `&mdash;`, `&rdquo;`, or `&#x263a;`, assuming the same encoding (UTF-8) is used for files and editors as well as among teams.
    -   The only exceptions apply to characters with special meaning in HTML (like `<` and `&`) as well as control or “invisible” characters (like no-break spaces).
    -   #### 3.1.7 Optional Tags (subjective)
    -   Omit optional tags (optional) BUT PLAY WELL WITH OTHERS.
    -   For file size optimization and scannability purposes, consider omitting optional tags. The [https://html.spec.whatwg.org/multipage/syntax.html#syntax-tag-omission](HTML5 specification) defines what tags can be omitted.
    -   #### 3.1.8 `type` Attributes
    -   Do not use `type` attributes for style sheets (unless not using CSS) and scripts (unless not using JavaScript).
    -   Specifying `type` attributes in these contexts is not necessary as HTML5 implies `text/css` and `text/javascript` as defaults.
-   ### 3.2 HTML Format
    -   #### 3.2.1

## 4 CSS
-   ### 4.1 CSS Style
-   ### 4.2 CSS Format
-   ### 4.3 CSS Meta

## 5 Notes
