[Blade]  `HTML::link`
======================

The `HTML::link()` function in blade is used to generate `<a href="#">...</a>` In html.

| Blade code                                                                  | Rendering                                                                       |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| `{{ HTML::link('http://www.example.com') }}`                                | `<a href="http://www.example.com">http://www.example.com</a>`                   |
| `{{ HTML::link('http://www.example.com', 'Link') }}`                        | `<a href="http://www.example.com">Link</a>`                                     |
| `{{ HTML::link('http://www.example.com', array('Attribute' => 'Value')) }}` | `<a href="http://www.example.com" arrtibute="value">http://www.example.com</a>` |
