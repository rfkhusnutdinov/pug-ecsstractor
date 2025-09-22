# PUG eCSStractor for VSCode README

VSCode plugin for extracting class names from PUG and generate CSS stylesheet for following work.

# Usage

Open any document contain PUG and do one of the following:

- Press **Cmd+Shift+P** on Mac OS X or **Ctrl+Shift+P** on Windows/Linux to launch command palette and choose:
  - PUG eCSStractor Run
  - PUG eCSStractor Run (With BEM Nesting)
  - PUG eCSStractor Run (With BEM Nesting and comments)
  - PUG eCSStractor Run (Without BEM Nesting)
- Right click and select PUG eCSStractor Run

Then you will see new tab with CSS selectors extracted from document or copy them to the clipboard (depending on settings).

Plugin can process either selected text or whole file.

# Settings

- **Brackets** - Add brackets. Useful for Sass syntax and Stylus
- **Brackets newline after** - Add new line
- **Destination** - Where to put result ("tab" or "clipboard")
- **Bem nesting** - BEM Nesting. Generate nested stylesheet for preprocessors
- **Indentation** - Indent symbol
- **Element separator** - Separator between block and element names
- **Modifier separator** - Separator between block or element and they modifier
- **Parent symbol** - Parent symbol. Ex.: &\_\_element {}
- **Empty line before nested selector** - Empty line before nested element/modifier
- **Add comment** - Add comments to nested stylesheets for preprocessors
- **Comment style** - Comment style. Either CSS (/\* \*/) or SCSS (//)

# Notes

- Port from [eCSStractor for VSCcode](https://github.com/yurasovm/eCSStractor-for-VSCode/)
- Extension icon from [iconfinder.com](https://www.iconfinder.com/icons/2308969/css_document_file_format_type_icon)
