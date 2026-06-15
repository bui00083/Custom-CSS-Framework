# ProjectTrack CSS

ProjectTrack CSS is a custom CSS framework designed for weekly project status dashboards and project management interfaces. It includes reusable components, themed HTML elements, Sass variables, and utility classes for common styling.

## Features

- Built with Sass and Sass partials
- Custom theme for headings, buttons, forms, inputs, tables, lists, and project dashboard sections
- Reusable components such as buttons, cards, tables, and project information blocks
- Utility classes for colours, font weight, font size, margin, padding, border, and border radius
- Sass variables for colours and typography
- Compiled CSS file included in the `css` folder

## Installation

Clone the repository:

```bash
git clone https://github.com/bui00083/Custom-CSS-Framework.git
```

Install dependencies:

```bash
npm install
```

Run Sass watch:

```bash
npm run dev
```

## Usage

Link the compiled CSS file:

```html
<link rel="stylesheet" href="css/projecttrack.css">
```

## Customization

Colours and typography can be customized in:

```text
src/variables/_colors.scss
src/variables/_typography.scss
```


## Framework Structure

```text
src/
├── base/
├── components/
│   ├── _button.scss
│   ├── _card.scss
│   ├── _info.scss
│   └── _table.scss
├── fonts/
├── utilities/
└── variables/
```