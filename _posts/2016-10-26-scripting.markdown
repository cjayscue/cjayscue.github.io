---
layout: post
title: Delving into Scripting
---

The time has come to submit ```Assignment 3```.

During this portion of the course we were introduced to text conversion using Pandoc.  
Again, this was completely new ground for me but I wanted to really grasp the terms
and concepts that we were covering.

To streamline the text conversion process, we learned the basics of scripting.  In esssence, scripting gives the ability to complete a multitude of commands all at
once.  In this case I uploaded a paper I wrote for my class, ```Foundations of Information Science```,
and proceeded to compose a script that would enable that document to be converted from
**markdown** to ***docx, odt, pdf,*** and ***html*** all at the same time.  This script consisted
of several pandoc commands that caused each conversion to take place by simply running the script.

The paper I uploaded and converted was an analysis of the information in my world and how I organize it. I provided 
detailed descriptions of where certain information is stored and how it is accessed and used regardless of whether it is digital 
or physical.  I also took photographs that displayed certain aspects or features of
my personal information system. 

An interesting thing I discovered with the first paper that I tried 
to upload (from a different class) was that any photos I had previously grouped with labels in Word were not recognized.  I even tried ungrouping and uploading them to my workspace,
but the Markdown file still did not recognize them.  So instead, I used a recent paper I written that included unlabeled photos!

Here are the links to each file and the script itself:

* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/201paper.md">Original Source Document</a> 
* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/201paper.odt">Converted to ODT</a> 
* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/201paper.docx">Converted to DOCX</a>
* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/201paper.html">Converted to HTML</a> 
* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/201paper.pdf">Converted to PDF</a> 
* <a href= "https://github.com/inls161/assignment-3-cjayscue/blob/master/cjayscue-convert-docs.sh">The Script</a>

This class continues to simultaneously challenge and intrigue me.  There are often moments where I feel lost but I keep 
pressing forward and access <a href= "https://google.com">Google</a> whenever necessary. Even though this assignment was in 
no way a piece of cake for me I found last Monday immensely encouraging.  I initially thought I had no clue of how to proceed with 
Assignment 3 and then all of a sudden I just started to put it together. Also, today in class I began to 
really understand **flags** and their importance.  There was an unnesscary table of contents and title included in
the converted pdf file and I was able to identify the flags and remove them from the script.
This was the final command that did not produce a **title** or a **table of contents**...

 > pandoc -S -o $filebase.html $fileName && pandoc -S -o $filebase.pdf $filebase.html

I look forward to what is around the corner next! <i class="fa fa-cubes" aria-hidden="true"></i>
