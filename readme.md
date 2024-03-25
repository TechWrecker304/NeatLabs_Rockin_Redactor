# NeatLabs Rockin' Redactor

The NeatLabs Rockin' Redactor is a powerful and user-friendly tool designed to assist in redacting sensitive information from text files, Word documents, and PDF files. With this program, you can easily identify and redact various types of sensitive data, such as social security numbers, credit card numbers, email addresses, and more.

## Features

- **File Support**: Open and redact text from plain text files (.txt), Word documents (.docx), and PDF files (.pdf).
- **Redaction Patterns**: Predefined redaction patterns for common types of sensitive information, including social security numbers, credit card numbers, IP addresses, email addresses, postal codes, phone numbers, passport numbers, bank account numbers, license plate numbers, and URLs.
- **Customizable Redaction**: Select specific redaction patterns to apply or use the "Select All" option to redact all supported types of sensitive information.
- **Redaction Recommendations**: Automatically analyze the input text and provide recommendations on what should be redacted based on the predefined redaction patterns.
- **Redacted Text Preview**: View the redacted text in real-time as you select or deselect redaction patterns.
- **Save Redacted Text**: Save the redacted text in various formats, including plain text (.txt), Word document (.docx), PDF (.pdf), and HTML (.html).
- **Clear Functionality**: Clear the input text and redaction recommendations with a single click using the "Clear" button.
- **User-Friendly Interface**: Intuitive and visually appealing graphical user interface (GUI) built with the ttkbootstrap library, providing a modern and responsive design.

## Installation

1. Clone the repository or download the source code files.
2. Ensure you have Python 3.x installed on your system.
3. Install the required dependencies by running the following command:
   ```
   pip install ttkbootstrap python-docx PyPDF2 reportlab
   ```
4. Run the program by executing the following command:
   ```
   python redactor.py
   ```

## Usage

1. Launch the NeatLabs Rockin' Redactor program.
2. Open a text file, Word document, or PDF file using the "Open File" button.
3. The input text will be displayed in the main text area, and redaction recommendations will be provided based on the predefined redaction patterns.
4. Select the desired redaction patterns using the checkboxes in the "Redaction Patterns" section. You can also use the "Select All" checkbox to toggle all redaction patterns at once.
5. Click the "Redact" button to apply the selected redaction patterns to the input text.
6. The redacted text will be displayed in the main text area, with sensitive information replaced by the corresponding redaction labels.
7. Save the redacted text in the desired format using the "Save as TXT", "Save as DOCX", "Save as PDF", or "Save as HTML" buttons.
8. To clear the input text and redaction recommendations, click the "Clear" button.

## Contributing

Contributions to the NeatLabs Rockin' Redactor are welcome! If you have any ideas, suggestions, or bug reports, please open an issue on the GitHub repository. If you'd like to contribute code improvements or new features, feel free to submit a pull request.

## License

This program is released under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for both commercial and non-commercial purposes.

## Acknowledgements

The NeatLabs Rockin' Redactor was developed using the following open-source libraries:
- [ttkbootstrap](https://github.com/israel-dryer/ttkbootstrap) - A modern and customizable theme extension for tkinter.
- [python-docx](https://github.com/python-openxml/python-docx) - A library for creating and updating Microsoft Word (.docx) files.
- [PyPDF2](https://github.com/py-pdf/PyPDF2) - A pure-python PDF library capable of splitting, merging, cropping, and transforming PDF pages.
- [reportlab](https://www.reportlab.com/) - A library for generating PDFs and graphics.

We would like to express our gratitude to the developers and contributors of these libraries for their valuable work.

## Contact

If you have any questions, feedback, or suggestions regarding the NeatLabs Rockin' Redactor, please feel free to contact us. We appreciate your input and strive to continuously improve the program to meet the needs of our users.

Happy redacting and stay secure!
