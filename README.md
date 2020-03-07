# Blue Prism Populate Word Document Example

A Blue Prism Release Package containing an example Visual Business Object (VBO) and Process to demonstrate populate a Word document in docx format by replacing placeholder values in its xml structure.

The Release Package was created with Blue Prism 6.4.

## Getting Started

In order to populate a Word document, you will need a document (.docx) to use as a template, with placeholder values included. An example Word document with placeholder values matching the example Blue Prism process is available here: [Example Word Document](Document Template.docx).

### Installing

Download the [Example Blue Prism Package](ShmoopySoftBluePrismPopulateWordDocumentExample.bprelease)

1. Launch Blue Prism
2. Click File -> Import
3. Select the 'ShmoopySoftBluePrismPopulateWordDocumentExample.bprelease' Release Package
4. Follow the Blue Prism import wizard to install the package

### Running

1. In Process Studio, open the process named 'Populate Word Document Process'
2. Edit the 'vPathToWordTemplate' data item to set the full path of the Word document to use as a template
3. Edit the 'vExtractionFolder' data item to set the name of the folder to use to temporarily save working files in
4. Edit the 'vPathToWordDocument' data item to set the full path of the Word document to save with poulated values
5. Click the Run button, or press F5

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
