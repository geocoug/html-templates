# Use GitHub Styling for Rendering Markdown

## [Dark Theme](./Example-Dark.html)

```bash
pandoc -s Example.md -c github-dark.css -o Example-Dark.html --embed-resources --standalone --metadata title="GitHub Dark"
```

## [Light Theme](./Example-Light.html)

```bash
pandoc -s Example.md -c github-light.css -o Example-Light.html --embed-resources --standalone --metadata title="GitHub Light"
```
