:warning: This element is **DEPRECATED**. We recommend to use [marked-element](https://github.com/PolymerElements/marked-element) in new projects.

# &lt;juicy-markdown&gt;

> Polymer Element with GitHub Flavored Markdown (GFM) viewer

## Demo

[Check it live!](http://Juicy.github.io/juicy-markdown)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-markdown --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-markdown/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-markdown/juicy-markdown.html">
    ```

3. Start using it!

    ```html
    <juicy-markdown value="# Markdown here"></juicy-markdown>
    ```

## Options

Attribute | Options  | Default | Description
---       | ---      | ---     | ---
`value`   | *string* | ``      | Markdown to render.
`ghcss`   | *boolean* | `false` | Should ghithub-markdown.css be imported?

## See also

 - [`<juicy-markdown-editor>`](https://github.com/Juicy/juicy-markdown-editor) - simple Markdown editor
 - [`<juicy-markdown-tabbededitor>`](https://github.com/Juicy/juicy-markdown-tabbededitor) - Markdown editor, with tabs like the one at GitHub.com

## Notes
- `juicy-markdown` is a [hybrid element](https://www.polymer-project.org/2.0/docs/devguide/hybrid-elements). 

## [Contributing and Development](CONTRIBUTING.md)

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-markdown/releases).

## License

MIT
