![alt text](https://upload.wikimedia.org/wikipedia/commons/9/92/LaTeX_logo.svg)

# LATEX MANUAL - BASIC ELEMENTS OF LATEX DOCUMENT

### _**Introduction**_

**LaTeX** is a document preparation system for high-quality typesetting. It is most often used for medium-to-large technical or scientific documents,however, it can be used for almost any form of publishing.Not only can it create beautifully typeset documents, but it allows users to very quickly tackle the more complicated parts of typesetting, such as inputting mathematics, creating tables of contents, referencing and creating bibliographies, and having a consistent layout across all sections.

[Official LaTeX Website](https://www.latex-project.org/)



### _**The preamble of a document**_

Everything in the file appearing before **\begin{document}** is called a &#39;preamble&#39;. In that area of the document a few elements are defined: type of the document, the language of the document, the packages that are being used.
Basic elements of a preamble:
+ **documentclass** - the first command of a LaTeX document. Identifies the type of document contained in the input file. All LaTeX documents must include the \documentclass markup tag. This controls the overall layout of the document, with different classes offering different default settings.
The _\documentclass_ markup always appears at the beginning of the document and allows you to pick the overall document type. 
+ **usepackage** - Packages add new functions to LaTeX. All packages must be included in the preamble. Packages add features such as support for pictures, links and bibliography

In order to set the environment for the document, use **\begin{document}** command after the preamble and **\end{document}** at the end.

Example below:

![alt text](https://sites.google.com/site/kochiuyu/latex/LaTeX_HelloWorld1.png?attredirects=0)

#### _**Adding a title, author and date**_

In order to add a title, author or date, three liners need to be included in the preamble **(not in the main body of the document!)**:
+ **\title{Title of the document}**
+ **\author{Author of the document}**
+ **\date{yyyy-mm-dd}** (command \date{\today} may be used in order to automatically generate the date of creation of the document)  

Example below:

![alt text](https://sites.google.com/site/kochiuyu/_/rsrc/1501158400735/latex/LaTeX_Frontmatter1.png)

### _**Sections**_

LaTex provides the user with a prossibility to divide the document into sections and subsections, which is a very useful option especially for academics and students willing to write their papers or dissertations in LaTeX.

In order to create a section use **\section{name of the section}** command. Remember to leave a space between sections for the redability. 

_**Sections and subsections in LaTeX are numbered automatically**_, therefore do not include the number of the section in its name.

Example below:

![alt text](https://sites.google.com/site/kochiuyu/_/rsrc/1501158504848/latex/LaTeX_Sections1.png)
