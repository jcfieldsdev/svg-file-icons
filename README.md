# svg-file-icons

This is an SVG version of the [Teambox Free File Icons set](https://github.com/teambox/Free-file-icons). The icons were generated using Affinity Designer, based on the "icons.ai" file provided in the original repository.

It omits some of the icons present in the original set but also adds some new icons. Since I created these for my own use, the selection will vary depending on what I found useful for my own needs.

It is organized by MIME type. For some file types, there may not be an official registered MIME type (or it may not have a unique one), so I picked or created one somewhat arbitrarily.

The file "mimetypes.csv" associates file extensions with MIME types. The intended usage is a script that takes the file extension from a file name, finds a MIME type for it using the CSV file, checks if an icon exists for that MIME type, and then uses it if available (otherwise, it picks a generic file icon).

## Acknowledgments

Based on [Free File Icons](https://github.com/teambox/Free-file-icons) by [Teambox Technologies](http://teambox.com/).

## Authors

- J.C. Fields <jcfields@jcfields.dev>

## License

- [MIT license](https://opensource.org/licenses/mit-license.php)
