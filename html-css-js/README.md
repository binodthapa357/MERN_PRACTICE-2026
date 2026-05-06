# html/css/js

## web

- WWW = world wide web
- System of interlinked docs accessed through the internet using web.
- Website are made of HTML(Structure), CSS(Styling), JavaScript(Behaviour)

## Client-Server Model

- Client : The browser or app that send request to server
- Server: The machine or computer that process the request and send responds(HTML, CSS, DATA).

## HTML: Hyper Text Markup Language

1. Text Element

- Heading --> <h1> to <h5>
- Paragraph ---> <p>
- Bold ---> <strong>
- Emphasize ---> <em>
- Super Sript ---> <sup>
- Sub Scrip ---> <sub>
- Pre-formatted Text ---> <pre>

2. Link and Media

- Anchor ---> <a>
- Images ---> <img>
- Videos ---> <video>

3. Lists

- Ordered List ---> <ol>
- Un-ordered List ---> <ul>
- List item ---> <li>

4. Misc Properties

- Line break ---> <br>
- Divider ---> <hr>
- Iframe ---> <iframe>

5. Table
- <table>
- <tr> ---> Table Row
- <td> ---> Table Data
- <th> ---> Table Heading
- <thead>
- <tbody>
- <tfoot>

6. Form
- <form>
- <input>: text, number, email, tel, checkbox, radio, file, date, password, time, range, color, submit, search
- <label>
- <textarea>
- <select> & <options>

7. Inline & Block Elements
- Inline element covers only the required space or width. for ex: anchor, img, video, span
- Block element occupies full width of the screen. for eg: h1, p, div, list

8. Semantics HTML (how to write Standard code/ professional code)
- All HTML Tag should be in lowercase.
- Use proper elements as per their positions and usage.
- Always add alternative <alt>  properties in the image tag.
- Always add title <title> properties in button esp with icons only button.
- HTML file must be in Kebab case. for eg. index.html   

### CSS - Cascading Style Sheet
- Website Style like color, font-size, alignment, spacing

**Syntax**
...
<selector> {
    property: value;
    property: value;
    ...
}

for e.g;

// Element
h1 {
    color: red;
    text-align: center;
    font-size: 2rem;
    ...
}

// Class
.title {
    ...
}

// Id
#title {
    color: green;
    ...
}
...
**Selector**
1. Element || Lowest Priority
2. Class: '.title'
3. ID: `#title` || Highest Priority

**Class vs id**
- For CSS, always use class.
- For JS, always use id.

**CS usage**
- Inline CSS
- Internal CSS
- External CSS

**CSS Properties**
1. Color, Background Color
2. Text
3. font
4. display
5. Box model: margin, padding, border
6. Flex
7. List
8. Unit







