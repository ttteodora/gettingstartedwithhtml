
<head>
  <title>Getting Started with HTML</title>
</head>

<h1>Getting Started with HTML</h1>

<h3>Introduction to the Web</h3>

<p><b>The World Wide Web</b> is a collection of files linked together by Hyperlinks. It was invented in the early 90s. Today, there are over 30 billion pages. </p> <p>
The major components of the web are:<br>
&emsp;1. <b>the clients</b> (computer and browser)<br>
&emsp;2. <b>the Internet</b> - the world’s largest computer network<br>
&emsp;3. <b>HTTP protocol</b> (<em>Hypertext Transfer Protocol</em>) - the main protocol that unites the web<br>
&emsp;4. <b>servers</b> - computers optimized for hosting files that make up the web<br>
We use <b>URLs</b> to refer to documents on the web.
</p>

<h3>HTML (<em>HyperText Markup Language</em>)</h3>
<p>
<b>HTML</b> is the main document type of the web.<br>
It is made up of:<br>
&emsp;1. <b>text content</b> - what you see<br>
&emsp;2. <b>markup</b> - what the text content looks like. (<a href="https://www.udacity.com/course/viewer#!/c-nd000/l-3873828673/m-48724340"> This
  video</a>) gives a good overview.<br> 
&emsp;3. <b>references to other documents</b>, e.g. images or videos<br>
&emsp;4. <b>links</b> to other pages</p>

<h3>HTML Markup</h3>

HTML Markup is made up of <b>tags</b>.
<p> <textarea><NAME>Contents</NAME></textarea> is the element<br>
<textarea><NAME> </textarea>is the opening tag<br>
<textarea></NAME></textarea> is the closing tag <br>
If the closing tag is missing all text after the opening tag is affected.</p>

Examples of tags:
<p>Bold tag <br>
<textarea><b>contents</b></textarea>
<br>
Italics tag<br>
<textarea><em>contents</em></textarea></p>

<p>Tags can have <b>attributes</b>, they are assigned as follows:
<textarea><TAG ATTR=”value”>contents</TAG></textarea> <br>
Example: anchor tag <br>
<textarea><a href=”url”>contents</a></textarea></p>

<p>Tags with no contents are called <b>void tags</b>.<br>
Example: Image tag
<textarea><img src=”url” alt=”text”></textarea></p>
<br>

<p>In order to render text on multiple lines, we can use one of the following: <br>
&emsp;1. the break tag:  <textarea><br></textarea> <br>
&emsp;2. the paragraph tag:  <textarea><p>content</p></textarea><br><br>
The break tag is an <b>inline</b> element, because it merely ends a line, while the paragraph tags consitute a <b>block</b> element, because they create a sort of invisible box around a section of text, which can also have specific height and width.</p>

<h3>Why are computers stupid?</h3>
<p>Computers are sometimes refered to as "stupid" because they interpret lanugage literally. This means that typos and small mistakes cannot be properly detected by the machine - only by "smart" humans. </p>

















