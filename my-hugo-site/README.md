# My Hugo Site

This is a simple Hugo site project that serves as a welcome page.

## Project Structure

```
my-hugo-site
├── archetypes
│   └── default.md
├── content
│   └── _index.md
├── layouts
│   ├── index.html
│   └── partials
│       └── header.html
├── static
│   └── css
│       └── styles.css
├── config.toml
└── README.md
```

## Setup Instructions

1. **Install Hugo**: Make sure you have Hugo installed on your machine. You can download it from [Hugo's official website](https://gohugo.io/getting-started/installation/).

2. **Clone the Repository**: Clone this repository to your local machine.

   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:

   ```
   cd my-hugo-site
   ```

4. **Run the Hugo Server**: Start the Hugo server to view the site locally.

   ```
   hugo server
   ```

5. **Open Your Browser**: Go to `http://localhost:1313` to see your welcome page.

## Usage

- The `content/_index.md` file contains the main content for the welcome page.
- The `layouts/index.html` file defines the HTML structure of the welcome page.
- The `static/css/styles.css` file is used for styling the site.
- Modify the `config.toml` file to change site parameters and settings.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.