# The Neo theme
*Neo is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](https://techie-joe.github.io/neo/), or even [use it today](#usage).*

**Neo** helps you build websites easily. It has everything pre-configured to get you started right away. You can write contents of your website in both Markdown and HTML. When you commit your code, GitHub Pages will build your website from the content of your repository.

<a href="https://techie-joe.github.io/neo/pages/" title="See how you can use this template to build your website" class="_bt -l -blue" style="width:10rem;height:3rem;font-size:1.2rem;padding:0;margin:1em 0;">See demo</a>

---

## Usage

To use the Neo theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: techie-joe/neo
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```
