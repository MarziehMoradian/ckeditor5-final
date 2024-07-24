# Custome CKEditor5 

Here’s how you can create a ready-made CKEditor 5 editor that is right-to-left (RTL) and Persian language enabled, along with instructions on how to use it in your project:

Step-by-Step Guide
Install CKEditor 5 Packages:

1.First, install the necessary CKEditor 5 packages using npm:
npm install --save @ckeditor/ckeditor5-react ckeditor5-final

2.Create a CKEditor Component:

```
import Editor from "ckeditor5-final/build/ckeditor";


<CKEditor
  editor={Editor}
  config={{
      language: "fa",
  }}
/>

```

You can add custom features in the configuration.
In version 1.1.4, the table feature is not available, but it is present in the latest version.
						
Features:
 * Alignment
 * Autoformat
 * Autosave
 * Base64UploadAdapter
 * BlockQuote
 * Bold
 * CloudServices
 * CodeBlock
 * Essentials
 * FindAndReplace
 * FontBackgroundColor
 * FontColor
 * FontSize
 * Heading
 * Highlight
 * Image
 * ImageCaption
 * ImageResize
 * ImageStyle
 * ImageToolbar
 * ImageUpload
 * Indent
 * Italic
 * Link
 * List
 * Mention
  *  Paragraph
  *  PasteFromOffice
   * Table,
  *  TableCellProperties
  *  TableProperties
   * TableToolbar,
  * TableColumnResize
   * TableCaption
  *  Undo
