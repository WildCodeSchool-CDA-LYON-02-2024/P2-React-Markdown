# P2-React-Markdown

Our Markdown to HTML Components Library provides a solution for converting Markdown text into HTML effortlessly.

- [1. Initialization](#Get-started)
  - [1.1 Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)


[I. Initialization](#Initialization)

[I. Initialization](#Initialization)

[I. Initialization](#Initialization)
[I. Initialization](#Initialization)
[I. Initialization](#Initialization)
[I. Initialization](#Initialization)

[//]: # (
TODO 
    - GET STARTED
        - Initialization
        - Features
    - Description
        - Components
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Modules
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Services
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Layouts
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Hooks
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Config
            - General presentation table name, type, description / Tableau presentation général nom, type, description
        - Constants
            - General presentation table name, type, description / Tableau presentation général nom, type, description
    - Benefits / Avantages
    - Next features / Prochaines fonctionnalités
    - Next released / Prochaine versions
)
## Get started

### Initialization

```
git clone https://github.com/WildCodeSchool-CDA-LYON-02-2024/P2-React-Markdown
```

### Features

- **Markdown to HTML Conversion**: Easily convert Markdown text into HTML, saving you time and effort.
- **Support for Standard Markdown Elements**: We support a wide range of standard Markdown elements including headers, lists, links, images, and more.
- **Input and Output Components**: Integration is made simple with dedicated Input and Output components. Input your Markdown text and instantly view the converted HTML output.
- **Customizable Appearance**: Tailor the look and feel of your HTML output with our customizable theme system, offering both pre-defined and personalized themes.
- **Retrieve Generated HTML**: Easily access the HTML generated from your Markdown text for seamless integration into other parts of your application.
- **Interactive Example Site**: Explore the library's features through our interactive example site, showcasing demonstrations of each component in action.
- **Visual Exploration with StoryBook**: Dive deep into our components with StoryBook, providing a comprehensive visual and interactive exploration experience.

### Usage

```js
import ReactDOM from "react-dom";

const domContainer = document.getElementById("root");
const root = ReactDOM.createRoot(domContainer);
root.render(<Markdown># Heading 1</Markdown>);
```

#### Component Props

- value: text content
- onClick: assign the conversion category
