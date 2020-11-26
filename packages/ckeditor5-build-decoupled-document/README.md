CKEditor 5 document editor custom build
========================================

Forked from [ckeditor/ckeditor5](https://github.com/ckeditor/ckeditor5) to create a custom build for `CKEditor 5 document editor build` in order to:

* Remove the original styling
* Customize the list of included plugins

## Documentation

Refer to the original [README.md](https://github.com/ckeditor/ckeditor5/blob/master/packages/ckeditor5-build-decoupled-document/README.md) for the documentation about **CKEditor 5 document editor build**.

## Modifications

* _package.json_: added **empty-string-loader** as dev dependency

* _webpack.config.js_: used **empty-string-loader** as loader for **.css** and **.svg** to remove them from the build

* _src/ckeditor.js_: customized the list of loaded plugins and set the default toolbar to empty

## License

Licensed under the terms of [GNU General Public License Version 2 or later](http://www.gnu.org/licenses/gpl.html). For full details about the license, please check the `LICENSE.md` file or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license).
