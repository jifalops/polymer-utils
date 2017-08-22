[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/polymer-utils)

# PolymerUtils

Polymer utility functions, commonly needed mixins, and a utility base-class that incorporates the mixins

* `PolymerUtils` -- utility class with static methods
* `PolymerUtilsBase` -- Base class with mixins already applied.
* `mixins/` -- A few handy mixins.

## Installation

```
bower i -S polymer-utils        # Polymer 2.0, ES6 classes
```

## Usage
Extend `PolymerUtilsBase` or use the `PolymerUtils.*` async and debounce methods.

## Demo
<!--
```
<custom-element-demo>
  <dom-bind>
    <template is="dom-bind">
      <script src="../webcomponentsjs/webcomponents-lite.js"></script>
      <link rel="import" href="demo/polymer-utils-demo.html">
      <link rel="import" href="demo/polymer-utils-base-demo.html">
      <next-code-block></next-code-block>
    </template>
  </dom-bind>
</custom-element-demo>
```
-->

```html
<polymer-utils-base-demo></polymer-utils-base-demo>
<hr/>
<polymer-utils-demo></polymer-utils-demo>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/polymer-utils/demo/demo/index.html)
| [github](https://jifalops.github.io/polymer-utils/components/polymer-utils/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/polymer-utils/polymer-utils)


## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)