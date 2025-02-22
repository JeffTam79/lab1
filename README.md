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

### HTML Tag Cheat Sheet
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
        <tr>
            <td>
                <pre><code>&lt;head&gt;</code></pre>
            </td>
            <td>A tag that contains metadata.</td>
            <td>
                <pre><code>&lt;html&gt;
    &lt;head&gt;
        &lt;title&gt;&lt;/title&gt;
    &lt;/head&gt;
&lt;/html&gt;
                </code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;title&gt;&lt;/title&gt;</code></pre>
            </td>
            <td>A tag that displays the content of the <code>&lt;title&gt;</code> element at the top of the browser window or page's tab.</td>
            <td>
                <pre><code>&lt;title&gt;My Web Page&lt;/title&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;body&gt;&lt;/body&gt;</code></pre>
            </td>
            <td>A tag that contains the document itself. It indicates that anything between it and the closing <code>&lt;/body&gt;</code> tag should be shown inside the main browser window.</td>
            <td>
                <pre><code>&lt;body&gt;Hello, World!&lt;/body&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;p&gt;&lt;/p&gt;</code></pre>
            </td>
            <td>A tag that creates paragraphs for web content. It helps structure content, separating text into distinct blocks.</td>
            <td>
                <pre><code>&lt;p&gt;Some text.&lt;/p&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&lt;h1&gt;&lt;/h1&gt;</code></pre>
            </td>
            <td>A tag that is used to indicate the primary topic of your webpage to visitors and search engines. Heading tags 1 - 6 are structured this way to format the text on a page.</td>
            <td>
                <pre><code>&lt;h1&gt;Title&lt;/h1&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&amp;lt &amp;gt</code></pre>
            </td>
            <td>HTML entity names are used to escape text.</td>
            <td>
                <pre><code>Hello, this is my home page. &amp;lt;what a simple page&amp;gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td>
                <pre><code>&amp;#60 &amp;#62</code></pre>
            </td>
            <td>HTML code is also used to escape text.</td>
            <td>
                <pre><code>Hello, this is my home page. &amp;#60;what a simple page&amp;#62;</code></pre>
            </td>
        </tr>
    </tbody>
</table>
