[Blade]  `HTML::link`
======================

The `HTML::link()` function in blade is used to generate `<a href="#">...</a>` In html.

| Blade code                                               | Rendering                             |
| -------------------------------------------------------- | ------------------------------------- |
| `{{ HTML::link('/Home') }}`                              | `<a href="/Home">/Home</a>`           |
| `{{ HTML::link('/Home', 'Link') }}`                      | `<a href="/Home">Link</a>`            |
| `{{ HTML::link('/, array('Attribute' => 'Value')) }}`    | `<a href="/" arrtibute="value">/</a>` |
