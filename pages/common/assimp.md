# assimp

> Client for the Open Asset Import Library.
> Supports loading of 40+ 3D file formats, and exporting to several popular 3D formats.
> More information: <https://manned.org/assimp>.

- List all supported import formats:

`assimp listext`

- List all supported export formats:

`assimp listexport`

- Convert a file to one of the supported output formats, using the default parameters:

`assimp export {{input_file.stl}} {{output_file.obj}}`

- Convert a file using custom parameters (the dox_cmd.h file in assimp's source code lists available parameters):

`assimp export {{input_file.stl}} {{output_file.obj}} {{parameters}}`

- Display a summary of a 3D file's contents:

`assimp info {{path/to/file}}`

- Display help:

`assimp help`

- Display help for a specific subcommand:

`assimp {{subcommand}} --help`
