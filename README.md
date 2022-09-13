# ESN Twente Guides

This is the source for the ESN Twente survival and housing and guides.

Live versions:
* [Survival Guide](https://esntwente.nl/guide)
* [Housing Guide](https://esntwente.nl/housing)

## Rendering
[Pandoc](https://github.com/jgm/pandoc) is required to render the document.
 ```bash
pandoc housing_guide.md --wrap=none | sed 's/href="h/target="_blank" href="h/g' > housing_guide.html
```

## Contributing

We are happy to receive your contributions to our guides. Simply open a Pull Requests with your suggestions.
