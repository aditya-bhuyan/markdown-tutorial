This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](/basic-syntax) and [extended syntax](/extended-syntax).

Basic Syntax
------------

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

|Element|Markdown Syntax|
|:------|:--------------|
|[Heading](/basic-syntax/#headings)|`# H1           ## H2           ### H3`|
|[Bold](/basic-syntax/#bold)|`**bold text**`|
|[Italic](/basic-syntax/#italic)|`*italicized text*`|
|[Blockquote](/basic-syntax/#blockquotes-1)|`> blockquote`|
|[Ordered List](/basic-syntax/#ordered-lists)|`         1. First item         2. Second item         3. Third item       `|
|[Unordered List](/basic-syntax/#unordered-lists)|`           - First item           - Second item           - Third item         `|
|[Code](/basic-syntax/#code)|`` `code` ``|
|[Horizontal Rule](/basic-syntax/#horizontal-rules)|`---`|
|[Link](/basic-syntax/#links)|`[title](https://www.example.com)`|
|[Image](/basic-syntax/#images-1)|`![alt text](image.jpg)`|

Extended Syntax
---------------

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

|Element|Markdown Syntax|
|:------|:--------------|
|[Table](/extended-syntax/#tables)|`           | Syntax      | Description |           | ----------- | ----------- |           | Header      | Title       |           | Paragraph   | Text        |       `|
|[Fenced Code Block](/extended-syntax/#fenced-code-blocks)|```` ```       {         "firstName": "John",         "lastName": "Smith",         "age": 25       }       ```        ````|
|[Footnote](/extended-syntax/#footnotes)|`         Here's a sentence with a footnote. [^1]          [^1]: This is the footnote.       `|
|[Heading ID](/extended-syntax/#heading-ids)|`### My Great Heading {#custom-id}`|
|[Definition List](/extended-syntax/#definition-lists)|`         term         : definition       `|
|[Strikethrough](/extended-syntax/#strikethrough)|`~~The world is flat.~~`|
|[Task List](/extended-syntax/#task-lists)|`         - [x] Write the press release         - [ ] Update the website         - [ ] Contact the media       `|


