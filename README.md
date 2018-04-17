# \<file-input\>

A custom file input builded with polymer 2.0 class based

## Install with bower

First, make sure you have the [Bower](https://bower.io) installed. Then run the next line for install the element.

```
$ bower install framled/file-input --save
```

## example:

<!--
```
<custom-element-demo>
	<template>
		<link rel="import" href="file-input.html">
		<link rel="import" href="image-input.html">
		<next-code-block></next-code-block>
	</template>
</custom-element-demo>
```
-->

You can use a `<file-input>` element for use import files, for default file-input use a paper button

```html
<file-input></file-input>
```

you can use a custom input-button slot
```html
<file-input>
	<paper-button slot="input-button">
		<iron-icon></iron-icon>
		Choose File
	</paper-button>
</file-input>
```

A fancy element for select a image
```html
<image-input></image-input>
```

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt) (C) Copyright.
