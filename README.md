# &lt;form-mail&gt;

Web Component wrapper for a simple contact form using Polymer.

> Maintained by [Mateus Correia](https://github.com/correiamateus).

## Demo

> [Check it live](http://correiamateus.github.io/form-mail-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/form-mail.html">
	```

3. Start using it!

	```html
	<form-mail></form-mail>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`action`   | *string*                  | `""`                | Form action
`method`   | `post`, `get` 	           | `post`              | Form send method


## TODO

* Create method that allow show/hide label and placeholder
* Create method that allow custom label and placeholder text

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 September 4, 2013
	* Initial development
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)