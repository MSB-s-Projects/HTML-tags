<!-- <!DOCTYPE html> -->

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="description"
      content="Website that contains all the HTML tags taught in Web Development Bootcamp by Dr. Angela Yu"
    />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Playbook</title>
  </head>

<body>
    <h1 align="center">HTML playbook</h1>
    <!-- <hr color="black" /> -->

<ol type="i">
<li id="1.<h1>-<h6>">
  <h2>&lt;h1&gt; - &lt;h6&gt; : Heading Tags</h2>

  <strong>Example:</strong>
  <h1>This is a heading of level 1</h1>
  <h2>This is a heading of level 2</h2>
  <h3>This is a heading of level 3</h3>
  <h4>This is a heading of level 4</h4>
  <h5>This is a heading of level 5</h5>
  <h6>This is a heading of level 6</h6>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      Attributes:
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>

  <br />
  <ul>
    <li>Heading tag is used to create headings of different levels.</li>
    <li>There are 6 heading tags from &lt;h1&gt; to &lt;h6&gt;.</li>
    <li>
      &lt;h1&gt; is the largest heading tag, and &lt;h6&gt; is the
      smallest heading tag.
    </li>
  </ul>
</li>

<li id="2.<br>">
  <h2>&lt;br&gt; : line break tag</h2>
  <strong>Example:</strong>
  <p>
    This is a paragraph. <br />
    This is another line in the same paragraph.
  </p>

  <ul>
    <li>Tag Omission: True</li>
    <li>
      Attributes:
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;br&gt; is the line break tag which basically works like the
      enter key in out keyboard.
    </li>
  </ul>
</li>

<li id="3.<hr>">
  <h2>&lt;hr&gt; : horizontal rule tag</h2>
  <strong>Example:</strong>
  <hr />

  <ul>
    <li>Tag Omission: True</li>
    <li>
      <strong> Attributes : </strong> align, color, noshade, size, width.
    </li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;hr&gt; the horizontal tag is used to create a horizontal line in
      our website.
    </li>
  </ul>
</li>

<li id="4.<center>">
  <h2>&lt;center&gt; : center tag</h2>
  <strong>Example:</strong>
  <center>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
  </center>

  <ul>
    <li>Tag Omission: None</li>
  </ul>
  <br />
  <ul>
    <li>
      This is a deprecated tag. So, it is not recommended to use it.
    </li>
    <li>&lt;center&gt; is used to center align the content inside it.</li>
  </ul>
</li>

<li id="5.<!-- -->">
  <h2>&lt;!-- --&gt; : comment tag</h2>
  <strong>Example:</strong>
  <pre>
    &lt;!-- This is a comment --&gt;
  </pre>

  <ul>
    <li>Tag Omission: True</li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;!-- --&gt; is used to add comments in our HTML code. These
      comments are not visible to the user.
    </li>
  </ul>
</li>

<li id="6.<!DOCTYPE html>">
  <h2>&lt;!DOCTYPE html&gt;</h2>
  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;!DOCTYPE html&gt; is used to declare that the document is an
      HTML5 document.
    </li>
    <li>
      It is not an HTML tag. It is an instruction to the web browser about
      what version of HTML the page is written in.
    </li>
  </ul>
</li>

<li id="7.<html>">
  <h2>&lt;html&gt; : HTML tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li><strong>Attributes :</strong> lang, manifest, version, xmlns</li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;html&gt; is the root element of an HTML document. It is used to
      enclose all the HTML elements in a web page.
    </li>
    <li>
      The &lt;html&gt; element is a container for all the other HTML
      elements.
    </li>
  </ul>
</li>

<li id="8.<head>">
  <h2>&lt;head&gt; : head tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li><strong>Attributes :</strong> profile</li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;head&gt; is used to provide information about the document.
    </li>
    <li>
      The &lt;head&gt; element contains meta information, like page title,
      scripts, styles, links, etc.
    </li>
  </ul>
</li>

<li id="9.<meta>">
  <h2>&lt;meta&gt; : meta tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
        &lt;meta charset="UTF-8"&gt;
        &lt;meta name="description" content="Free Web tutorials"&gt;
        &lt;meta name="keywords" content="HTML, CSS, JavaScript"&gt;
        &lt;meta name="author" content="John Doe"&gt;
        &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: True</li>
    <li>
      <strong>Attributes :</strong> charset, content, http-equiv, name
    </li>
  </ul>
  <br />
  <ul>
    <li>
      &lt;meta&gt; is used to provide metadata about the HTML document.
    </li>
    <li>
      Metadata will not be displayed on the page, but will be machine
      parsable.
    </li>
    <li>
      Metadata typically define the document title, character set, styles,
      scripts, and other meta information.
    </li>
  </ul>

  <h3>charset attribute</h3>

  <strong>Example:</strong>
  <pre>
    &lt;meta charset="UTF-8"&gt;
  </pre>

  <ul>
    <li>
      The charset attribute specifies the character encoding for the HTML
      document.
    </li>
    <li>
      The charset attribute is used together with the &lt;meta&gt; tag to
      declare a character set for the HTML document.
    </li>
    <li>
      The charset attribute is required if the character encoding is not
      UTF-8.
    </li>
  </ul>

  <h3>content attribute</h3>

  <strong>Example:</strong>
  <pre>
    &lt;meta name="description" content="Free Web tutorials"&gt;
  </pre>
  <ul>
    <li>
      The content attribute specifies the value associated with the http-
      equiv or name attribute.
    </li>
    <li>
      The content attribute is used together with the &lt;meta&gt; tag to
      declare metadata for the HTML document.
    </li>
  </ul>

  <h3>http-equiv attribute</h3>

  <strong>Example:</strong>
  <pre>
    &lt;meta http-equiv="Content-Type" content="text/html; charset=UTF-8"&gt;
  </pre>

  <ul>
    <li>
      The http-equiv attribute provides an HTTP header for the information
      /value of the content attribute.
    </li>
    <li>
      The http-equiv attribute is used together with the &lt;meta&gt; tag
      to declare metadata for the HTML document.
    </li>
  </ul>

  <h3>name attribute</h3>

  <strong>Example:</strong>
  <pre>
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  </pre>

  <ul>
    <li>The name attribute specifies a name for the metadata.</li>
    <li>
      The name attribute is used together with the &lt;meta&gt; tag to
      declare metadata for the HTML document.
    </li>
  </ul>
</li>

<li id="10.<title>">
  <h2>&lt;title&gt; : title tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;title&gt; is used to specify a title for the document.</li>
    <li>
      The &lt;title&gt; element is required in all HTML documents and
      should be the first element in the &lt;head&gt; element.
    </li>
    <li>
      The &lt;title&gt; element defines the title in the browser toolbar,
      the title in the page's tab, and the title that is displayed in
      search engine results.
    </li>
  </ul>
</li>

<li id="11.<body>">
  <h2>&lt;body&gt; : body tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;Page Title&lt;/title&gt;
      &lt;/head&gt;
      &lt;body&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph.&lt;/p&gt;
      &lt;/body&gt;
    &lt;/html&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> alink, background, bgcolor,
      bottommargin, leftmargin, link, onafterprint, onbeforeprint,
      onbeforeunload, onblur, onerror, onfocus, onhashchange,
      onlanguagechange, onload, onmessage, onoffline, ononline,
      onpopstate, onredo, onresize, onstorage, onundo, onunload,
      rightmargin, text, topmargin, vlink
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;body&gt; is used to define the document's body.</li>
    <li>
      The &lt;body&gt; element contains all the contents of an HTML
      document, such as text, hyperlinks, images, tables, lists, etc.
    </li>
    <li>
      The &lt;body&gt; element is a container for all the visible contents
      such as headings, paragraphs, images, hyperlinks, tables, lists,
      etc.
    </li>
    <li>
      The &lt;body&gt; element is a required element in an HTML document.
    </li>
  </ul>
</li>

<li id="12.<p>">
  <h2>&lt;p&gt; : paragraph tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;p&gt;This is a paragraph.&lt;/p&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;p&gt; is used to define a paragraph.</li>
    <li>
      The &lt;p&gt; element is used to group related content in a
      document.
    </li>
    <li>The &lt;p&gt; element is used to define a block of text.</li>
  </ul>
</li>

<li id="13.<em>">
  <h2>&lt;em&gt; : emphasis tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;p&gt;I am &lt;em&gt;emphasized&lt;/em&gt; text.&lt;/p&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;em&gt; is used to define emphasized text.</li>
    <li>
      The &lt;em&gt; element is used to define emphasized text with no
      special importance.
    </li>
    <li>
      The &lt;em&gt; tag is a phrase tag. It renders as emphasized text.
    </li>
  </ul>

  <h3>&lt;em&gt; vs &lt;i&gt;</h3>
  <ul>
    <li>
      The &lt;em&gt; tag is a phrase tag. It renders as emphasized text.
    </li>
    <li>The &lt;i&gt; tag is a phrase tag. It renders as italic text.</li>
    <li>The &lt;em&gt; tag is more semantic than the &lt;i&gt; tag.</li>
    <li>
      The &lt;em&gt; tag is used to define text with stress emphasis.
    </li>
    <li>
      The &lt;i&gt; tag is used to define a part of text in an alternate
      voice or mood.
    </li>
  </ul>
</li>

<li id="14.<strong>">
  <h2>&lt;strong&gt; : strong tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;p&gt;I am &lt;strong&gt;strong&lt;/strong&gt; text.&lt;/p&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      <a href="https://devdocs.io/html/global_attributes"
        >global_attributes</a
      >
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;strong&gt; is used to define important text.</li>
    <li>The &lt;strong&gt; element is used to define important text.</li>
    <li>
      The &lt;strong&gt; tag is a phrase tag. It renders as bold text.
    </li>
  </ul>

  <h3>&lt;strong&gt; vs &lt;b&gt;</h3>
  <ul>
    <li>
      The &lt;strong&gt; tag is a phrase tag. It renders as bold text.
    </li>
    <li>The &lt;b&gt; tag is a phrase tag. It renders as bold text.</li>
    <li>
      The &lt;strong&gt; tag is more semantic than the &lt;b&gt; tag.
    </li>
    <li>
      The &lt;strong&gt; tag is used to define text with strong
      importance.
    </li>
    <li>
      The &lt;b&gt; tag is used to define bold text without any extra
      importance.
    </li>
  </ul>
</li>

<li id="15.<ul>">
  <h2>&lt;ul&gt; : unordered list tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;ul&gt;
      &lt;li&gt;Item 1&lt;/li&gt;
      &lt;li&gt;Item 2&lt;/li&gt;
      &lt;li&gt;Item 3&lt;/li&gt;
    &lt;/ul&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li><strong>Attributes :</strong> compact, type,</li>
  </ul>
  <br />
  <ul>
    <li>&lt;ul&gt; is used to define an unordered list.</li>
    <li>
      The &lt;ul&gt; element is used to define an unordered list (a list
      that does not have a number next to each item).
    </li>
    <li>
      The &lt;ul&gt; element is used to group a set of unordered list
      items.
    </li>
    <li>
      The &lt;ul&gt; element is used to define a list of items in no
      particular order.
    </li>
  </ul>
</li>

<li id="16.<ol>">
  <h2>&lt;ol&gt; : ordered list tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;ol&gt;
      &lt;li&gt;Item 1&lt;/li&gt;
      &lt;li&gt;Item 2&lt;/li&gt;
      &lt;li&gt;Item 3&lt;/li&gt;
    &lt;/ol&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li><strong>Attributes :</strong> compact, reversed, start, type</li>
  </ul>
  <br />
  <ul>
    <li>&lt;ol&gt; is used to define an ordered list.</li>
    <li>
      The &lt;ol&gt; element is used to define an ordered list (a list
      that has a number next to each item).
    </li>
    <li>
      The &lt;ol&gt; element is used to group a set of ordered list items.
    </li>
    <li>
      The &lt;ol&gt; element is used to define a list of items in a
      specific order.
    </li>
  </ul>
</li>

<li id="17.<li>">
  <h2>&lt;li&gt; : list item tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;ul&gt;
      &lt;li&gt;Item 1&lt;/li&gt;
      &lt;li&gt;Item 2&lt;/li&gt;
      &lt;li&gt;Item 3&lt;/li&gt;
    &lt;/ul&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li><strong>Attributes :</strong> value, type</li>
  </ul>
  <br />
  <ul>
    <li>&lt;li&gt; is used to define a list item.</li>
  </ul>
</li>

<li id="18.<img>">
  <h2>&lt;img&gt; : image tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;img src="image.jpg" alt="image"&gt;
  </pre>

  <ul>
    <li>Tag Omission: True</li>
    <li>
      <strong>Attributes :</strong>
      alt, crossorigin, decoding, fetchpriority, height, ismap, loading,
      referrerpolicy, sizes, src, srcset, usemap, width, align, border,
      hspace, longdesc, name, vspace
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;img&gt; is used to define an image.</li>
    <li>
      The &lt;img&gt; element is used to embed an image in an HTML page.
    </li>
    <li>
      The &lt;img&gt; tag is empty, it contains attributes only, and does
      not have a closing tag.
    </li>
    <li>The &lt;img&gt; tag has two required attributes: src and alt.</li>
  </ul>
</li>

<li id="19.<a>">
  <h2>&lt;a&gt; : anchor tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;a href="https://www.google.com"&gt;Google&lt;/a&gt;
  </pre>

  <ul>
    <li>Tag Omission: False</li>
    <li>
      <strong>Attributes :</strong>
      download, href, hreflang, ping, referrerpolicy, rel, target, type,
      charset, coords, name, rev, shape
    </li>
  </ul>
  <br />
  <ul>
    <li>&lt;a&gt; is used to define a hyperlink.</li>
    <li>
      The &lt;a&gt; element is used to define a hyperlink, which is used
      to link from one page to another.
    </li>
    <li>
      The &lt;a&gt; tag is used to create a link to another document.
    </li>
  </ul>
</li>

<li id="20.<table>">
  <h2>&lt;table&gt; : table tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;tr&gt;
        &lt;th&gt;Firstname&lt;/th&gt;
        &lt;th&gt;Lastname&lt;/th&gt;
        &lt;th&gt;Age&lt;/th&gt;
      &lt;/tr&gt;
      &lt;tr&gt;
        &lt;td&gt;John&lt;/td&gt;
        &lt;td&gt;Doe&lt;/td&gt;
        &lt;td&gt;50&lt;/td&gt;
      &lt;/tr&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      align, bgcolor, border, cellpadding, cellspacing, frame, rules,
      summary, width
    </li>
  </ul>
  <br />
  <ul>
    <li>The &lt;table&gt; element is used to define an HTML table.</li>
    <li>
      The &lt;table&gt; element is used to add tables to a web page.
    </li>
  </ul>
</li>

<li id="21.<tr>">
  <h2>&lt;tr&gt; : table row tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;tr&gt;
        &lt;th&gt;Firstname&lt;/th&gt;
        &lt;th&gt;Lastname&lt;/th&gt;
        &lt;th&gt;Age&lt;/th&gt;
      &lt;/tr&gt;
      &lt;tr&gt;
        &lt;td&gt;John&lt;/td&gt;
        &lt;td&gt;Doe&lt;/td&gt;
        &lt;td&gt;50&lt;/td&gt;
      &lt;/tr&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> align, bgcolor, char, charoff, valign
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;tr&gt; element is used to define a row in an HTML table.
    </li>
  </ul>
</li>

<li id="22.<td>">
  <h2>&lt;td&gt; : table data tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;tr&gt;
        &lt;th&gt;Firstname&lt;/th&gt;
        &lt;th&gt;Lastname&lt;/th&gt;
        &lt;th&gt;Age&lt;/th&gt;
      &lt;/tr&gt;
      &lt;tr&gt;
        &lt;td&gt;John&lt;/td&gt;
        &lt;td&gt;Doe&lt;/td&gt;
        &lt;td&gt;50&lt;/td&gt;
      &lt;/tr&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong>
      align, bgcolor, char, charoff, colspan, headers, rowspan, scope,
      valign
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;td&gt; element is used to define a cell in an HTML table.
    </li>
  </ul>
</li>

<li id="23.<theader>">
  <h2>&lt;theader&gt; : table header tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;thead&gt;
        &lt;tr&gt;
          &lt;th&gt;Firstname&lt;/th&gt;
          &lt;th&gt;Lastname&lt;/th&gt;
          &lt;th&gt;Age&lt;/th&gt;
        &lt;/tr&gt;
      &lt;/thead&gt;
      &lt;tbody&gt;
        &lt;tr&gt;
          &lt;td&gt;John&lt;/td&gt;
          &lt;td&gt;Doe&lt;/td&gt;
          &lt;td&gt;50&lt;/td&gt;
        &lt;/tr&gt;
      &lt;/tbody&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> align, bgcolor, char, charoff, valign
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;thead&gt; element is used to group the header content in an
      HTML table.
    </li>
  </ul>
</li>

<li id="24.<th>">
  <h2>&lt;th&gt; : table header tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;tr&gt;
        &lt;th&gt;Firstname&lt;/th&gt;
        &lt;th&gt;Lastname&lt;/th&gt;
        &lt;th&gt;Age&lt;/th&gt;
      &lt;/tr&gt;
      &lt;tr&gt;
        &lt;td&gt;John&lt;/td&gt;
        &lt;td&gt;Doe&lt;/td&gt;
        &lt;td&gt;50&lt;/td&gt;
      &lt;/tr&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> align, bgcolor, char, charoff,
      colspan, headers, height, rowspan, scope, valign, width
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;th&gt; element is used to define a header cell in an HTML
      table.
    </li>
  </ul>
</li>

<li id="25.<tbody>">
  <h2>&lt;tbody&gt; : table body tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;table&gt;
      &lt;thead&gt;
        &lt;tr&gt;
          &lt;th&gt;Firstname&lt;/th&gt;
          &lt;th&gt;Lastname&lt;/th&gt;
          &lt;th&gt;Age&lt;/th&gt;
        &lt;/tr&gt;
      &lt;/thead&gt;
      &lt;tbody&gt;
        &lt;tr&gt;
          &lt;td&gt;John&lt;/td&gt;
          &lt;td&gt;Doe&lt;/td&gt;
          &lt;td&gt;50&lt;/td&gt;
        &lt;/tr&gt;
      &lt;/tbody&gt;
    &lt;/table&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> align, bgcolor, char, charoff, valign
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;tbody&gt; element is used to group the body content in an
      HTML table.
    </li>
  </ul>
</li>

<li id="26.<form>">
  <h2>&lt;form&gt; : form tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;form action="demo_form.asp" method="get"&gt;
      First name: &lt;input type="text" name="fname" /&gt;&lt;br /&gt;
      Last name: &lt;input type="text" name="lname" /&gt;&lt;br /&gt;
      &lt;input type="submit" value="Submit" /&gt;
    &lt;/form&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> accept, accept-charset, action,
      autocomplete, enctype, method, name, novalidate, target
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;form&gt; element is used to create an HTML form for user
      input.
    </li>
    <li>
      The &lt;form&gt; element is a container for different types of input
      elements, such as: text fields, checkboxes, radio buttons, submit
      buttons, etc.
    </li>
    <li>
      The &lt;form&gt; element is used together with the &lt;input&gt;
      element to create interactive forms that allow users to input data.
    </li>
  </ul>
</li>

<li id="27.<label>">
  <h2>&lt;label&gt; : label tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;form action="demo_form.asp" method="get"&gt;
      &lt;label&gt;First Name:&lt;/label&gt;
      &lt;input type="text" name="fname" /&gt;&lt;br /&gt;
    &lt;/form&gt;
  </pre>

  <ul>
    <li>Tag Omission: None</li>
    <li>
      <strong>Attributes :</strong> for, form, accesskey, class,
      contenteditable, contextmenu, dir, draggable, dropzone, hidden, id,
      lang, spellcheck, style, tabindex, title, translate
    </li>
  </ul>
  <br />
  <ul>
    <li>
      The &lt;label&gt; element defines a label for many form elements.
    </li>
    <li>
      The &lt;label&gt; element is useful for screen-reader users, because
      the screen-reader will read out loud the label when the user focus
      on the input element.
    </li>
    <li>
      The &lt;label&gt; element also help users who have difficulty
      clicking on very small regions (such as radio buttons or checkboxes)
      - when the user clicks on the text within the &lt;label&gt; element,
      it toggles the radio button/checkbox.
    </li>
  </ul>
</li>

<li id="28.<input>">
  <h2>&lt;input&gt; : input tag</h2>

  <strong>Example:</strong>
  <pre>
    &lt;form action="demo_form.asp" method="get"&gt;
      First name: &lt;input type="text" name="fname" /&gt;&lt;br /&gt;
      Last name: &lt;input type="text" name="lname" /&gt;&lt;br /&gt;
      &lt;input type="submit" value="Submit" /&gt;
    &lt;/form&gt;
  </pre>

  <ul>
    <li>Tag Omission: True</li>
    <li>
      <strong>Attributes :</strong> accept, alt, autocomplete, autofocus,
      checked, dirname, disabled, form, formaction, formenctype,
      formmethod, formnovalidate, formtarget, height, list, max,
      maxlength, min, multiple, name, pattern, placeholder, readonly,
      required, size, src, step, type, value, width
    </li>
  </ul>
  <br />
  <ul>
    <li>The &lt;input&gt; element is the most important form element.</li>
    <li>
      The &lt;input&gt; element is used to create interactive controls for
      web-based forms in order to accept data from the user.
    </li>
    <li>
      The &lt;input&gt; element can be displayed in many ways, depending
      on the type attribute.
    </li>
    <li>
      <p>
        To See all the types of of &lt;input&gt;
        <a href="inputs.html" target="_blank">click here</a>.
      </p>
    </li>
  </ul>
</li>

</ol>
  </body>
</html>
