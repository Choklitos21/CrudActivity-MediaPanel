# CrudActivity-MediaPanel
#### Diego Alejandro Morales Montoya
#### [Webpage]()

---

## Description

This website used HTML tags to build a simple web page.

## TAGS used

---

+ **Structure:** These elements tell the browser and search engines what type of content is in that section, helping to 
create a well-structured document that is accessible and optimized for machine reading.
  + html, head, body, title, base, meta, link.

+ **Semantics:** Tags that add meaning to the content they enclose, describing the nature and purpose of that portion 
of the page, rather than just its visual appearance.
  + header, nav, main, section, article, aside, footer, address, time, ul, ol.

+ **No semantics:** Are elements used to group or structure content without assigning any inherent meaning or function 
to that content.
  + div.

+ **Text:** Are elements used to structure, format, and add semantics (meaning) to the text itself within a web page.
  + h1–h3, p, strong, em, abbr.

+ **Tables:** Are a set of elements specifically designed to organize data in rows and columns.
  + table, tr, th, td.

+ **Forms:** They are a set of elements designed to create interactive forms on a web page.
  + form, label, input, textarea, button.

+ **Multimedia:** Are elements specifically designed to embed and control multimedia content (such as audio, video, 
and images) directly on web pages.
  + img, audio, video, source.

## Differences between Semantic and No Semantic TAGS

---

+ **Semantic TAG:** Semantic tags are those that add meaning or purpose to the content they enclose, describing the
nature and role of that portion of the page.
  + When to use: It is better to use semantic tags when you are defining the main structure or content
  type of section of the page, in this case the nav bar
    ```html
        <nav>
            <ul>
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </nav>
    ```

+ **No Semantic TAG:** Non-semantic tags are generic containers used to group or structure content without assigning 
any inherent structural or functional meaning to it.
  + When to use: It is better to use non-semantic tags when you need a container only for styling or scripting 
  purposes, and there is no a good semantic tag for the content.
    ```html
        <p>
          This is just a simple <span class="importantStyle">Text</span>
        </p>
    ```

## Focus on uncommon tags

---

+ **< base > :** The **< base >** tag specifies the base URL for all relative links (relative URLs) that appear on the 
page. It must always be placed within the **< head >** tag.

+ **< abbr > :** The **< abbr >** tag is used to indicate that the enclosed text is an abbreviation or acronym. It 
improves accessibility by allowing screen readers or the mouse cursor to display the full text of the abbreviation.

+ **< time > :** The **< time >** tag is used to represent a specific point in time or a range of time.

+ **Multimedia:** HTML5's native multimedia tags (such as **< video >** and **< audio >**) offer significant advantages 
over simply linking to the multimedia file. The content plays directly on the page, without the user having to download 
the file or be redirected to another page/application.

### References

---

+ **Web3School**
+ **freeCodeCamp**
+ **MDN Web Docs**
+ **Markdown.es**
