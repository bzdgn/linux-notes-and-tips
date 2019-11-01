Linux Notes And Tips
====================

This repository will be my notes and tips on linux, especially command line. I am learning how to use vi, cut, sed, awk and such useful commands in Linux. This repository will consist of command line tools, editors and tips about such tools on Linux. 

TOC
---
- [1 Vi Editor](#0-vi-editor) <br/>
  * [1-a- General](#1-a-general) <br/>

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

[Go back to Vi Editor](#0-vi-editor) <br/>
[Go back to TOC](#toc)


 2-a Moving Cursor
------------------

Move Cursor
-----------

Basic cursor movement;

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

Move cursor within the line;

| command | description |
| --- | --- |
| 0 or \|           | Move cursor to the start of the line      |
| $                 | Move cursor to the end of the line        |

Move cursor based on word;

| command | description |
| --- | --- |
| w                 | Position the cursor to the next word      |
| b                 | Position the cursor to the previous word  |

Move cursor based on sentence;

| command | description |
| --- | --- |
| (                 | Move beginning of the sentence based on . |
| )                 | Move end of the sentence based on .       |

Move based on char within the line;

| command | description |
| --- | --- |
| f?                | Moves to the next ? in the line           |
| F?                | Moves to the previous ? in the line       |

Move cursor to the border of the view;

| command | description |
| --- | --- |
| 1G                | Begining                                  |
| G                 | End                                       |
| nG                | nth line                                  |
| --- | --- |
| H                 | Top of the view                           |
| M                 | Mid of the view                           |
| L                 | Low of the view                           |



[Go back to Vi Editor](#0-vi-editor) <br/>
[Go back to TOC](#toc)

