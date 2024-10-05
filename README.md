Paperless NGX Metadata Extractor using Ollama Models
This repository contains an extension for Paperless NGX that leverages local Ollama language models to automatically extract key metadata from documents as they are added. It utilizes the PAPERLESS_POST_CONSUME_SCRIPT environment variable to trigger the extraction process after a document is ingested.

Key Metadata Extracted
Title
Description
Tags
Date
Author
Features
Automated Metadata Extraction: Automatically uses local Ollama language models to extract metadata whenever a document is added to Paperless NGX.
Seamless Integration: Works with the Paperless NGX document management system.
Configurable via PAPERLESS_POST_CONSUME_SCRIPT: Uses this script to run after document ingestion and extract metadata without manual intervention.
Supports various document formats like PDF, Word, and others.
Improves document organization and searchability with structured metadata.
Requirements
A working Paperless NGX installation.
Local Ollama language models.
The PAPERLESS_POST_CONSUME_SCRIPT environment variable set to point to this script.
Installation
Install Paperless NGX.
Install Ollama language models locally.
Clone this repository and follow the setup instructions.
Set PAPERLESS_POST_CONSUME_SCRIPT in your Paperless NGX configuration to point to the script.
Make the script executable: Run chmod +x <script_name> to ensure Paperless NGX can execute it.
Usage
Once installed and configured, the extension will automatically extract and apply metadata when documents are added to Paperless NGX, allowing for better organization and search functionality.

This includes the necessary instruction for making the script executable. Let me know if there’s anything else!
