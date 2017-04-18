# GitHub Issues to PDF
### A program to help collect GitHub issues as PDF files.

## Installation
1. Clone or Download GitHub Issues to PDF (GIP).
2. Run `npm install` inside the folder containing GIP.
3. To avoid GitHub API limits (60 requests for anonymous calls) create your own [Personal Access Token](https://github.com/settings/tokens/new) and copy/paste it in line 206: ````token: 'PERSONAL ACCESS TOKEN GOES HERE'````
4. From the command line, navigate to the GIP folder and run `node gip.js`

The pdfs will render to './rendered_pdfs'; if the folder does not exist yet, it will be created.