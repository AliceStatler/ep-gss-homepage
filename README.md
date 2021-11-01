# Google Smart Shopping App Homepage

## Dependencies

This website is built with the help of the static site generator [Hugo](https://gohugo.io/).

See https://gohugo.io/getting-started/installing for instructions how to install Hugo.

## Development

Run the following command to preview changes in a browser:

```
hugo server
```

## Localization

```
{{ i18n "concept.description" }}
```

## Page params

```
```

## Architecture

```
<link href="{{ "css/styles.css" | relURL }}" rel="stylesheet" />

{{ partial "teaser.html" . }}
```

## License

This website is licensed with default copyright.

### Credits

- https://startbootstrap.com/theme/new-age
- https://www.bootdey.com/snippets/view/microsoft-metro-tiles-bootstrap#html
- https://nanmu.me/en/posts/2020/hugo-i18n-automatic-language-redirection/
