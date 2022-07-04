# Short Guide to Pandoc
## What Is Pandoc

Pandoc is a versatile script/tool that reads files in one format, and outputs them in a different format. It __greatly__ simplifies file conversions. When a program interconverts a file for you, very often the program is using Pandoc in the background. The full guide to Pandoc is [here](https://pandoc.org/).


## Why Use Pandoc?

If you spend more than a few minutes a week extracting text from one file format to use somewhere else, Pandoc could become your best friend. If you have to convert several files at one time, Pandoc definitely is your best friend, because Pandoc can do them in a batch with one command, rather than you doing them one at a time.


## How Do You Use Pandoc?

Pandoc is a terminal command, which can be scary at first. Don't worry though; Pandoc cannot make changes to files that you do not tell it to make. It has a very simple command structure that looks more complicated than it really is.

This is the command to change our workshop handouts from Markdown to Word:

```
pandoc -s /desktop/ABLE_2022_Workshop/1_ABLE_2022_Workshop_Markdown_6-16.md -o 
/desktop/ABLE_2022_Workshop/1_ABLE_2022_Workshop_Markdown_6-16.docx
```
This is how the command breaks down:

1. The word "pandoc" simply says "send this line of instructions to the Pandoc program.
2. "-s" tells Pandoc you are entering information about the source file that needs to be converted.
    + "/desktop/ABLE\_2022\_Workshop/" is the location in the file folders on my computer.
    + "1\_ABLE\_2022\_Workshop\_Markdown_6-16.md" is the actual file's name. The ".md" extension tells Pandoc what file type it is.
3. "-o" tells Pandoc that the next information refers to the output file it will make.
    + The location of the folder for receiving the output file can be the same (like this example) or anywhere else you want to put it.
    + The extension on the filename after "-o" tells Pandoc what file type you want to make. The ".docx" extension in the example tells Pandoc I want to convert to a Word file. If I wanted an HTML document, the extension would be ".html". 
    + Personally I keep the same file folder and name for my output files, and just change the extension (which is ".docx" in this example.) It makes it easier to find the converted files if they are all in the same place.


## What Can Pandoc Convert?

The types of files that Pandoc can inter-convert include:

__Document Files__
* asciidoc (AsciiDoc) 
* asciidoctor (AsciiDoctor)
* docbook4 (DocBook 4)
* docbook5 (DocBook 5)
* docx (Word docx)
* epub
* epub2 (EPUB v2)
* epub3 (EPUB v3 book)
* fb2 (FictionBook2 e-book)
* icml (InDesign ICML)
* odt (OpenOffice text document)
* opendocument (OpenDocument)
* pdf (PDF) (_Pandoc can export a PDF, but cannot read or convert them to other formats_)
* rst (reStructuredText)
* rtf (Rich Text Format)
* texinfo (GNU Texinfo)
* textile (Textile)
* txt (plain text)

__Wiki Markup Files__
* dokuwiki (DokuWiki markup)
* jira (Jira/Confluence wiki markup)
* mediawiki (what Wikipedia uses)
* tikiwiki
* twiki
* xwiki (XWiki markup)
* zimwiki (ZimWiki markup)

__Markdown Formatted Files__
* commonmark (CommonMark Markdown)
* commonmark\_x (CommonMark Markdown with extensions)
* gfm (GitHub-Flavored Markdown)
* haddock (Haddock markup)
* markdown (Pandoc’s Markdown)
* markdown\_mmd (MultiMarkdown)
* markdown\_phpextra (PHP Markdown Extra)
* markdown_strict (original unextended Markdown)


__HTML/XML Files__
* html5 (HTML, i.e. HTML5/XHTML polyglot markup)
* html4 (XHTML 1.0 Transitional)


__LaTeX Formatted Files__
* bibtex (BibTeX bibliography)
* biblatex (BibLaTeX bibliography)
* context (ConTeXt)
* latex (LaTeX)


__Slide Files__
* beamer (LaTeX beamer slide show)
* pptx (PowerPoint slide show)
* slideous (Slideous HTML and JavaScript slide show)
* slidy (Slidy HTML and JavaScript slide show)
* dzslides (DZSlides HTML5 + JavaScript slide show),
* revealjs (reveal.js HTML5 + JavaScript slide show)
* s5 (S5 HTML and JavaScript slide show)


__JATS Files__
* jats, jats\_archiving (JATS XML, Archiving and Interchange Tag Set)
* jats\_articleauthoring (JATS XML, Article Authoring Tag Set)
* jats\_publishing (JATS XML, Journal Publishing Tag Set)


__Computer Languages__
* csljson (CSL JSON bibliography)
* ipynb (Jupyter notebook)
* json (JSON version of native AST)
* man (roff man)
* ms (roff ms)
* muse (Muse)
* native (native Haskell)
* opml (OPML)
* org (Emacs Org mode)
* tei (TEI Simple)
