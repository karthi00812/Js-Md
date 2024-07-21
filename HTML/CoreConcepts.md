HTML (HyperText Markup Language) is the standard language used to create and design documents on the web. Here are the core concepts of HTML:

### 1. **Elements and Tags**
- **Elements**: HTML documents are made up of elements. An element usually consists of a start tag, content, and an end tag. For example, `<p>This is a paragraph.</p>`.
- **Tags**: Tags are used to create elements. They are enclosed in angle brackets. For example, `<h1>` is a tag that creates a level 1 heading.

### 2. **Attributes**
- Attributes provide additional information about an element. They are always included in the opening tag and come in name/value pairs like `name="value"`. For example, `<a href="https://www.example.com">This is a link</a>`, where `href` is an attribute of the `<a>` tag.

### 3. **Document Structure**
- An HTML document has a specific structure:
    - `<!DOCTYPE html>`: Declares the document type and version of HTML.
    - `<html>`: The root element of an HTML page.
    - `<head>`: Contains meta-information about the HTML document, such as the title, character set, styles, and links to scripts.
    - `<body>`: Contains the content of the HTML document, such as text, images, links, and other media.

### 4. **Common HTML Tags**
- **Headings**: `<h1>` to `<h6>` tags are used to define headings, with `<h1>` being the highest level.
- **Paragraph**: `<p>` tag is used to define a paragraph.
- **Links**: `<a>` tag is used to create hyperlinks.
- **Images**: `<img>` tag is used to embed images, with the `src` attribute specifying the image source.
- **Lists**:
    - `<ul>` for an unordered list.
    - `<ol>` for an ordered list.
    - `<li>` for list items.
- **Tables**: `<table>` tag for creating tables, with `<tr>` for table rows, `<th>` for header cells, and `<td>` for standard cells.
- **Forms**: `<form>` tag for creating forms, with various input elements like `<input>`, `<textarea>`, `<button>`, `<select>`, etc.

### 5. **Semantic HTML**
- Semantic elements clearly describe their meaning in a human- and machine-readable way. Examples include:
    - `<header>`: Defines a header for a document or section.
    - `<nav>`: Defines navigation links.
    - `<main>`: Specifies the main content of the document.
    - `<section>`: Defines a section in a document.
    - `<article>`: Defines an independent piece of content.
    - `<footer>`: Defines a footer for a document or section.
    - `<aside>`: Defines content aside from the main content.

### 6. **HTML Forms**
- Forms are used to collect user input. The `<form>` element wraps the form elements, and commonly used elements include:
    - `<input>`: Used for various types of user input (text, radio, checkbox, etc.).
    - `<label>`: Defines a label for an `<input>` element.
    - `<textarea>`: Multi-line text input.
    - `<button>`: Clickable button.
    - `<select>` and `<option>`: Drop-down list.

### 7. **Media Elements**
- HTML supports various multimedia elements:
    - `<img>`: Embeds images.
    - `<audio>`: Embeds audio files.
    - `<video>`: Embeds video files.
    - `<canvas>`: Used for drawing graphics via scripting (usually JavaScript).
    - `<svg>`: Used to define vector-based graphics.

### 8. **Global Attributes**
- These attributes can be used on any HTML element:
    - `class`: Specifies one or more class names for an element.
    - `id`: Specifies a unique id for an element.
    - `style`: Specifies an inline CSS style for an element.
    - `title`: Provides extra information about an element (displayed as a tooltip).
    - `lang`: Specifies the language of the element’s content.

### 9. **HTML Comments**
- Comments are used to insert notes or explanations within the HTML code and are ignored by browsers. They are written as `<!-- Comment -->`.

### 10. **Character Entities**
- Special characters in HTML are represented by character entities, like `&lt;` for `<`, `&gt;` for `>`, and `&amp;` for `&`.

Understanding these core concepts provides a solid foundation for creating and structuring web pages using HTML.