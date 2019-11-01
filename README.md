Linux Notes And Tips
====================

This repository will be my notes and tips on Linux, especially the command-line. I am learning how to use `vi`, `cut`, `sed`, `awk` and such useful commands in Linux. This repository will consist of command-line tools, editors and tips about such tools on Linux.

TOC
---
- [1 Vi Editor](#1-vi-editor) <br/>
  * [1-a- General](#1-a-general) <br/>
  * [1-b- Moving Cursor](#1-b-moving-cursor) <br/>

 1 Vi Editor
------------

 1-a General
------------

| command | description |
| --- | --- |
| Esc               | Command Mode                              |
| i                 | Insert Mode                               |
| :q                | Quit                                      |
| :q!               | ! means ignoring modification on file     |
| :wq               | Write and quit                            |
| ZZ                | Write and quit                            |
| :w filename2.txt  | Write to another filename                 |

[Go back to Vi Editor](#1-vi-editor) <br/>
[Go back to TOC](#toc)


 1-b Cursor Movement
--------------------

Basic cursor movement:

| command | description |
| --- | --- |
| k                 | Move cursor up                            |
| j                 | Move cursor down                          |
| h                 | Move cursor left                          |
| l                 | Move cursor right                         |
| nk                | Move cursor up    n times                 |
| nj                | Move cursor down  n times                 |
| nh                | Move cursor left  n times                 |
| nl                | Move cursor right n times                 |

<pre>
         k

         |
         |
         |
h  ------.------  l
         |
         |
         |

         j
</pre>

Move cursor within the line:

| command | description |
| --- | --- |
| 0 or \|           | Start of the line                     |
| $                 | End of the line                       |

Move cursor by word:

| command | description |
| --- | --- |
| w                 | Next word                             |
| b                 | Previous word                         |

Move cursor by sentence:

| command | description |
| --- | --- |
| (                 | Beginning of the sentence, based on . |
| )                 | End of the sentence, based on .       |

Move cursor by paragraph:

| command | description |
| --- | --- |
| }                 | Next paragraph                        |
| {                 | Previous paragraph                    |

Move cursor by character:

| command | description |
| --- | --- |
| f?                | Next ? in the current line            |
| F?                | Previous ? in the current line        |

Move cursor to the border of the view:

| command | description |
| --- | --- |
| 1G or gg          | Begining                              |
| G                 | End                                   |
| nG                | nth line                              |
| --- | --- |
| H                 | Top of the view                       |
| M                 | Mid of the view                       |
| L                 | Low of the view                       |

Move cursor by line:

| command | description |
| --- | --- |
| nH                | nth line from Top                     |
| nL                | nth line from Low                     |
| --- | --- |
| :n                | Move cursor to the nth line           |
| --- | --- |
| ctrl+b            | One page up                           |
| ctrl+u            | Half page up                          |
| ctrl+d            | Half page down                        |
| ctrl+f            | One page down                         |
| --- | --- |
| ctrl+y            | One line up                           |
| ctrl+e            | One line down                         |

[Go back to Vi Editor](#1-vi-editor) <br/>
[Go back to TOC](#toc)

