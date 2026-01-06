# Personal Website

A personal portfolio website built with [Quarto](https://quarto.org) showcasing projects, work experience, and more.

## Structure

- `index.qmd` - Homepage with introduction
- `about.qmd` - About me page with background and skills
- `projects.qmd` - Portfolio of projects
- `experience.qmd` - Work experience and professional background
- `_quarto.yml` - Quarto configuration file
- `styles.css` - Custom CSS styles

## Setup

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system

### Installation

1. Clone this repository:
```bash
git clone https://github.com/kashish1928/website.git
cd website
```

2. Install Quarto by following the instructions at [quarto.org](https://quarto.org/docs/get-started/)

## Usage

### Preview the website locally

```bash
quarto preview
```

This will start a local server and open the website in your browser. The preview will automatically reload when you make changes.

### Build the website

```bash
quarto render
```

This generates the static website in the `_site` directory.

### Publish to GitHub Pages

```bash
quarto publish gh-pages
```

This builds and deploys the website to GitHub Pages.

## Customization

1. **Personal Information**: Update the content in each `.qmd` file with your own information
2. **Links**: Update GitHub and LinkedIn links in `_quarto.yml` and content pages
3. **Styling**: Modify `styles.css` to customize the appearance
4. **Theme**: Change the theme in `_quarto.yml` (options: default, cosmo, flatly, darkly, etc.)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
