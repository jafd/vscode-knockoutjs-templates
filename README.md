# knockoutjs-templates README

The KnockoutJS framework expects to see its directives in two places
(unless you use extensions): in HTML comments that look like this

```
<!-- ko binding: javascript -->
```

or `data-bind` attributes on HTML tags. Which by default will be shown to you
as either a comment, or a string, and this is not useful.

This extension will make Visual Studio Code highlight these fragments as Javascript,
which is way more helpful in finding out what was wrong with those errors parsing bindings.

## Known Limitations

