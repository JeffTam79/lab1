# Lab 1
## HTML Basics

This is my first repository on GitHub!

- [My website on Pages](https://jefftam79.github.io/lab1/)

My website on Pages: https://jefftam79.github.io/lab1/

### The Content Covered:
1. Basic Structure of an HTML Document
2. The Meta Tag
3. Other Tags: `<html>`, `<head>`, `<title>`, `<body>`
4. Paragraph Elements (`<p>`)
5. Heading Levels
6. HTML Entities & HTML Code 

###HTML Tag Cheat Sheet
<table>
<tr>
<td> Syntax </td> <td> Description </td> <td> Syntax </td>
</tr>
<tr>
<td> 
```HTML
{
    <html>
        <head>
            <title></title>
        </head>
        <body>
        </body>
    </html>      
}
```
</td>
<td>The basic structure of an HTML document.</td>
<table>
    <thead>
        <tr>
            <th>Syntax</th>
            <th>Description</th>
            <th>Example</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <pre><code>&lt;html&gt;
    &lt;head&gt;
        &lt;title&gt;&lt;/title&gt;
    &lt;/head&gt;
    &lt;body&gt;
    &lt;/body&gt;
&lt;/html&gt;
                </code></pre>
            </td>
            <td>The basic structure of an HTML document.</td>
            <td>
                <pre><code>&lt;html&gt;
    &lt;head&gt;
        &lt;meta charset="utf-8"&gt;
        &lt;title&gt;&lt;/title&gt;
    &lt;/head&gt;
    &lt;body&gt;
    &lt;/body&gt;
&lt;/html&gt;
                </code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;meta&gt;</code></pre>
            </td>
            <td>A tag that provides additional information about a webpage to search engines and browsers, like a page description, author, keywords, or viewport settings. It is usually placed within the <code>&lt;head&gt;</code> section of the HTML document and is not visible to users.</td>
            <td>
                <pre><code>&lt;meta charset="utf-8"&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;html&gt;</code></pre>
            </td>
            <td>A tag that indicates that anything between it is HTML code. Use the <code>lang</code> attribute inside the <code>&lt;html&gt;</code> tag to declare the language of the web page. The purpose of this attribute is to assist search engines and browsers.</td>
            <td>
                <pre><code>&lt;html lang="en"&gt;</code></pre>
            </td>
        </tr>
    </tbody>
</table>
