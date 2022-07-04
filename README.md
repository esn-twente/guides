# Housing Guide

This is the source of the ESN Twente housing guide. You can find a live version of the guide on our website, [esntwente.nl/housing](https://esntwente.nl/housing)

## Rendering

```bash
cmark --validate-utf8 --to html --smart --unsafe  housing_guide.md | sed 's/href="h/target="_blank" h/g' > housing_guide.html
```

## Contributing

We are happy to receive suggestions to the guide. Simple open a Pull Requests with your suggestions.
