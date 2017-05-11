# Web Design for Industry (SWD6

## The pattern library

Minimum of 6 production components:
- Navigation Bar (Nav)
- HEader Element (Carousel or just static)
- A range of six button types
- Jumbotron (Call to action)
- Foooter incorporating social media icon links
- Component of your choice

You are required to make a ## Pattern library consisting of 6 components, which should be supported by examples , documentation and code snippets that can be cut and pasted. You can create more components if you wish to create a more comprehensive pattern lib

### Using the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Use this command to set up a blank Foundation for Sites project with this template:

```bash
foundation new --framework sites --template basic
```

The CLI will prompt you to give your project a name. The template will be downloaded into a folder with this name.

### Manual Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/zurb/foundation-sites-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run the Sass compiler. It will re-run every time you save a Sass file.
