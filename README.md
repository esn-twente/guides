# Housing Guide

This is the source of the ESN Twente housing guide. You can find a live version of the guide on our website, [esntwente.nl/housing](https://esntwente.nl/housing)

## Rendering
[Pandoc](https://github.com/jgm/pandoc) is required to render the document.
 ```bash
```bash
pandoc housing_guide.md --wrap=none | sed 's/href="h/target="_blank" href="h/g' > housing_guide.html
```

## Contributing

We are happy to receive suggestions to the guide. Simple open a Pull Requests with your suggestions.
