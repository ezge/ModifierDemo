Modifiers are created using instances of the Compose
Modifier object and are passed as parameters to
composables to change appearance and behavior. A
modifier is configured by calling methods on the Modifier
object to define settings such as size, padding, rotation,
and background color. Most of the built-in composables
provided with the Compose system will accept a modifier as
a parameter. It is also possible (and recommended) to add
modifier support to your own composable functions. If a
composable function accepts a modifier, it will always be
the first optional parameter in the function’s parameter list,
but positioned after any mandatory parameters.
