[![Build status](https://travis-ci.org/abdonrd/moment-element.svg?branch=master)](https://travis-ci.org/abdonrd/moment-element)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/abdonrd/moment-element)

## \<moment-element\>

Web Component (with Polymer) wrapper for the [moment](https://github.com/moment/moment) library.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="moment-element.html">
    <div>
      <dom-bind>
        <template>
          <next-code-block></next-code-block>
        </template>
      </dom-bind>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<moment-element output="{{outputA}}">[[outputA]]</moment-element>

<moment-element datetime="1991-12-31" output="{{outputB}}"></moment-element>
<div>[[outputB]]</div>
```
