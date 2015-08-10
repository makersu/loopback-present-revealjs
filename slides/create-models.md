#  Create a simple API
##  Create models

```console
$ cd hello-world
$ slc loopback:model

[?] Enter the model name: person
[?] Select the data-source to attach person to: db (memory)
[?] Select model's base class: PersistedModel
[?] Expose person via the REST API? Yes
[?] Custom plural form (used to build REST URL): people
Let's add some person properties now.

Enter an empty property name when done.
[?] Property name: firstname

[?] Property type: (Use arrow keys)
❯ string
  number
  boolean
  object
  array
  date
  buffer
  geopoint
  (other)

[?] Required? (y/N) y

```