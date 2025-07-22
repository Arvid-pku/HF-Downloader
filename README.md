# Hugging Face Batch Downloader

A Tampermonkey userscript that adds batch download functionality to Hugging Face model pages.

## Features

- 📦 **Batch Selection**: Checkboxes for selecting multiple files
- ⬇️ **One-Click Download**: Download all selected files at once  
- 🏷️ **Smart Naming**: Files tagged with model name `[Org-Model] filename.ext`
- 🎯 **Clean UI**: Integrates seamlessly with Hugging Face design

## Installation

1. **Install Tampermonkey**: 
   - [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/) | [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)

2. **Install Script**:
   - Click Tampermonkey icon → "Create a new script"
   - Copy contents of `hf-batch-downloader.user.js`
   - Paste and save (`Ctrl+S`)

3. **Use**: Visit any HF model page (e.g., `huggingface.co/Qwen/Qwen3-1.7B/tree/main`)

## Usage

1. **Batch Download**: Use the control panel that appears at the top:
   - Select All / Select None
   - Check individual files  
   - Click "Download Selected"

2. **File Names**: Downloads as `[Qwen-Qwen3-1.7B] config.json` format

## Supported Sites

- `huggingface.co/*/tree/*` and `/blob/*` pages
- `hf-mirror.com/*/tree/*` and `/blob/*` pages

## Troubleshooting

- **Not loading**: Check Tampermonkey is enabled and script is active
- **Downloads fail**: Check browser pop-up blocker settings
- **Console errors**: Press F12 to see detailed error messages

## License

Open source - modify and distribute freely. 
