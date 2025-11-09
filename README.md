# Brandon Li - Personal Website

This is a personal website built with [Hugo](https://gohugo.io/) using the [Blowfish](https://github.com/nunocoracao/blowfish) theme.

## Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- [Go](https://go.dev/) (for Hugo Modules)

### Development

To start the development server:

```bash
hugo server
```

The site will be available at `http://localhost:1313`

### Building

To build the site for production:

```bash
hugo
```

The generated site will be in the `public/` directory.

## Project Structure

```
.
├── config/          # Site configuration files
│   └── _default/    # Default configuration
├── content/         # Site content
│   ├── posts/       # Blog posts
│   └── about/       # About page
├── go.mod           # Go module file
└── README.md        # This file
```

## Customization

### Configuration

Edit the files in `config/_default/` to customize your site:

- `hugo.toml` - Main site configuration
- `params.toml` - Theme parameters
- `menus.en.toml` - Menu configuration
- `languages.en.toml` - Language and author settings

### Content

- Edit `content/_index.md` for the homepage
- Edit `content/about/_index.md` for the about page
- Add blog posts in `content/posts/`

## Theme Updates

To update the Blowfish theme:

```bash
hugo mod get -u
hugo mod tidy
```

## Resources

- [Blowfish Theme Documentation](https://blowfish.page/)
- [Hugo Documentation](https://gohugo.io/documentation/)

# brandonliyao-xyz
