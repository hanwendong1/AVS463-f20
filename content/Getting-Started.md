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


| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

| Boolean Operator 	| Explanation 	| Example 	|
|:----------------:	|-------------	|---------	|
|        AND       	|All search terms must be present in the results             	|Antibiotic AND farm         	|
|        OR        	|             	|         	|
|                  	|             	|         	|
|                  	|             	| dsf     	|
|                  	|             	|         	|
|                  	|             	|         	|
|                  	|             	|         	|

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>


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
