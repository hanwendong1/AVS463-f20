---
title: Getting Started
nav: true
--- 

# Boolean Logic
When conducting college-level research, there is a general process to follow:

{% capture text %}

1. Select topic
2. Use Boolean logic to expand or narrow key concepts or keywords
3. Select a database
4. Evaluate and revise search strategy
5. Choose items and find full-text online or in print

{% endcapture %}

{% include card.md text=text header="Research Process" %}

Since you have already selected your topic, this guide will focus on the other aspects of research process. First, let’s talk about Boolean logic. 

Boolean logic used Boolean operators (such as `AND`, `OR`, `NOT`) to narrow, expand, or define your search, and is applicable to conducting searches in library catalog and most databases. Writing out your search terms using Boolean operators by connecting pieces of information and coming up with synonyms is a good exercise as it can specify wanted results and filter out unrelated results. These are some of the most common Boolean operators you can use:

<html>
<head>
<style>
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
</style>
</head>
<body>

<h2>HTML Table</h2>

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Laughing Bacchus Winecellars</td>
    <td>Yoshi Tannamuri</td>
    <td>Canada</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Giovanni Rovelli</td>
    <td>Italy</td>
  </tr>
</table>

</body>
</html>


{% capture alert %}*Note:* Jekyll does not officially support Windows, however it is cross platform (they just don’t officially write windows documentation or check for bugs).
There is a [Jekyll on Windows](https://jekyllrb.com/docs/windows/#installation) page, but it can be out of date and inaccurate.{% endcapture %}
{% include alert.md text=alert color="warning" %}

# Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
