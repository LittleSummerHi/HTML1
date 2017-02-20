# HTML1
HTML/CSS basic 
<!DOCTYPE html>
<!-- This is an HTML comment -->
<head>
  <title>Andy's Notes</title>
  <link rel="stylesheet" href="andy-style.css">
</head>
<body>
  <div class="TOC">
    <h1>Table of Contents</h1>
    <ol>
      <li><a href="#lesson-1">Lesson 1: The Basics of the Web and HTML</a>
        <ul>
          <li><a href="#lesson-1-1">How the Web Works</a></li>
          <li><a href="#lesson-1-2">HTML</a></li>
          <li><a href="#lesson-1-3">Tags and Elements</a></li>
          <li><a href="#lesson-1-4">Why Computers are Stupid</a></li>
          <li><a href="#lesson-1-5">Inline vs Block Elements</a></li>
        </ul>
      </li>
      <li class="TOC-lesson"><a href="#lesson-2">Lesson 2: Creating a Structured Document with HTML</a>
        <ul>
          <li><a href="#lesson-2-1">Developer Tools</a></li>
          <li><a href="#lesson-2-2">HTML's "tree-like" Structure</a></li>
          <li><a href="#lesson-2-3">Indentations and Boxes</a></li>
          <li><a href="#lesson-2-4">Text Editors</a></li>
        </ul>
      </li>
      <li class="TOC-lesson"><a href="#lesson-3">Lesson 3: Adding CSS Style to HTML Structure</a>
        <ul>
          <li><a href="#lesson-3-1">Avoiding Repetition</a></li>
          <li><a href="#lesson-3-2">CSS</a></li>
          <li><a href="#lesson-3-3">Coding Resources</a></li>
        </ul>
      </li>
    </ol>
  </div>
  <h1>Important Concepts</h1>
  <div class="lesson">
    <h2 id="lesson-1">Lesson 1: The Basics of the Web and HTML</h2>
    <div class="concept" id="lesson-1-1">
      <div class="concept-title">
        How the Web Works
      </div>
      <div class="concept-description">
        <p>
          The web is a bunch of computers that communicate with
          each other. When a person goes to a web page like
          www.google.com, their computer sends a
          <em>HTTP Request</em> to
          a <em>server</em>.
        </p>
        <p>
          The server finds the appropriate HTML document and sends
          it back to the user's computer where a <em>
          web browser</em> interprets the page and displays it on
          the user's screen.
          <a href="https://www.udacity.com/course/viewer#!/c-ud721/l-3508959201/e-48329854/m-48480496">This video</a>
          does a good job of explaining more.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-1-2">
      <div class="concept-title">
        HTML
      </div>
      <div class="concept-description">
        <p>
          HTML stands for <em>Hypertext Markup
          Language.</em> HTML documents form the majority of the
          content on the web.
        </p>
        <p>
          HTML documents contain <em>text
          content</em> which describes "what you see" and
          <em>markup</em> which describes
          "how it looks". <a href="https://www.udacity.com/course/viewer#!/c-ud721/l-3508959201/m-48724340">This
          video</a> gives a good overview.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-1-3">
      <div class="concept-title">
        Tags and Elements
      </div>
      <div class="concept-description">
        <p>
          HTML documents are made of HTML
          <b>elements</b>. When writing HTML, we
          tell browsers the type of each element by using HTML
          <b>tags</b>.
          <a href="https://www.udacity.com/course/viewer#!/c-ud721/l-3508959201/m-48723444">This video</a> explains the
          distinction well.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-1-4">
      <div class="concept-title">
        Why Computers are Stupid
      </div>
      <div class="concept-description">
        <p>
          Computers are stupid because they interpret
          instructions literally. This makes them very
          unforgiving since a small mistake by a
          programmer can cause huge problems in a program.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-1-5">
      <div class="concept-title">
        Inline vs Block Elements
      </div>
      <div class="concept-description">
        <p>
          HTML elements are either <b>inline</b>
          or <b>block</b>. Block elements form
          an "invisible box" around the content inside of them.
        </p>
      </div>
    </div>
  </div>
  <div class="lesson">
    <h2 id="lesson-2">Lesson 2: Creating a Structured Document with HTML</h2>
    <div class="concept" id="lesson-2-1">
      <div class="concept-title">
        Developer Tools (in the Browser)
      </div>
      <div class="concept-description">
        <p>
          HTML elements are either <b>inline</b>
          or <b>block</b>. Block elements form
          an "invisible box" around the content inside of them.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-2-2">
      <div class="concept-title">
        The "tree-like structure" of HTML
      </div>
      <div class="concept-description">
        <p>
          The "tree-like structure" comes from the fact that HTML
          elements can have other elements inside of them. You can
          draw this relationship like a family tree. My mother
          had multiple children. So did her mother, and so on...
        </p>
        <p>
          In a browser, this structure shows up as a series
          of nested boxes. There are boxes inside of boxes
          inside of boxes, and so on...
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-2-3">
      <div class="concept-title">
        The relationship between indented HTML and boxes
      </div>
      <div class="concept-description">
        <p>
          When you read an HTML document as
          <em>text</em>, you see a wave of
          changing indentations going up and down the left side
          of the document. The more indented an element is, the
          more deeply nested its corresponding "box" is.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-2-4">
      <div class="concept-title">
        Text Editors (for programming)
      </div>
      <div class="concept-description">
        <p>
          When writing code, programmers use special text editors
          (like Sublime Text for example). These editors make the
          programmer's life easier. For example, some text editors
          will automatically generate a closing HTML tag when you
          write an opening tag.
        </p>
      </div>
    </div>
  </div>
  <div class="lesson">
    <h2 id="lesson-3">Lesson 3: Adding CSS Style to HTML Structure</h2>
    <div class="concept" id="lesson-3-1">
      <div class="concept-title">
        Avoiding Repetition
      </div>
      <div class="concept-description">
        <p>
          Avoiding repetition is important for a variety of reasons.
        </p>
        <p>
          <b>Avoiding Errors:</b> When programmers <em>don't</em> avoid repetition, they will often have to do the same thing over and over. This may mean copy and pasting certain style attributes into many HTML elements or rewriting the same code (sometimes with minor differences) many times. This can lead to errors when the programmer decides to make a change to something. If they don't dilligently make that same change everywhere the repeated code appears, problems will arise.
        </p>
        <p>
          <b>Consistency:</b> In this web page, I wanted every lesson to look the same. Instead of manually giving each one the same style, I was able to assign each lesson <span class="code">div</span> the same <span class="code">class</span> and then specify the style for that class in only one place! By avoiding repetion, it's now very easy for me to make changes to this style.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-3-2">
      <div class="concept-title">
        CSS
      </div>
      <div class="concept-description">
        <p>
          CSS stands for Cascading Style Sheets and they give programmers a way to control the style of related HTML elements. This is done by giving similar HTML elements the same <span class="code">class</span> name and then specifying the style that should apply to that class.
        </p>
      </div>
    </div>
    <div class="concept" id="lesson-3-3">
      <div class="concept-title">
        Coding Resources
      </div>
      <div class="concept-description">
        <p>
          The following coding resources will help me learn to "think like a programmer":
        </p>
        <p>
          <b><a href="https://www.udacity.com/">Udacity</a></b> - From the Udacity homepage I can access lots of classes to help me on my journey, including the Intro to Programming Nanodegree program! I can find lots of support under the "Resources" tab of my Nanodegree program
        </p>
        <p>
          <b><a href="https://discussions.udacity.com/">Udacity Discussion Forums</a></b> - The Udacity Discussion Forums are a great place to go if I need help with a lesson or project.
        </p>
        <p>
          <b><a href="http://stackoverflow.com/">Stack Overflow</a></b> - Stack Overflow is a site professional programmers use all the time when debugging code. There are many years of discussion and troubleshooting help on this site!
        </p>
        <p>
          <b><a href="http://pythontutor.com/">Python Tutor</a></b> - Python Tutor is a site that could be really helpful when I start lerning the Python programming language in Stage 2. It helps me to visualize how code runs.
        </p>
      </div>
    </div>
  </div>
</body>
