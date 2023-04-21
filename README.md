# EML Parse

EML Parse is a Python script that parses and processes EML-formatted email files. It allows users to view the email structure, extract URLs, and save any attachments to a specified folder.

## Features

- Read and parse EML files
- Print the email structure with color-coded highlights
- Extract URLs from the email content
- Save attachments to a specified folder ("/Users/malware/")

## Usage

1. Grab the repo, change the privs, then run the script using Python, providing the path to the target EML file as a command-line argument:

```bash
git clone http://gitlab.speakes/cspeakes/eml-email-file-parser.git
cd eml-email-file-parser/
pip3 install -r requirements.txt
chmod +x eml_parse
mv eml_parse /usr/local/bin/
eml_parse -f /path/to/your/eml/file.eml
```

This script will parse the "example.eml" file, print its structure, extract any URLs, and save any attachments to the "local" folder.
