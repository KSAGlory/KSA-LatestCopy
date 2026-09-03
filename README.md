<p align="center">
  <img src="assets/logo.svg" width="96" height="96" alt="KSA Latest Copy logo">
</p>

<h1 align="center">KSA Latest Copy</h1>

<p align="center">
  A Windows utility that helps you check whether a newer copy of your document exists.
</p>

**Status:** In development

![KSA Latest Copy interface preview](assets/product-preview-dark.png)

## About the project

The idea came from a common office problem. You are ready to send a document, but your folders contain several files with names like `Report Final.docx`, `Report Final 2.docx`, and `Report Final New.docx`. It is easy to choose the wrong one.

KSA Latest Copy is being built to check a selected document against folders approved by the user. It will look for related files, compare useful details, and clearly explain what it finds.

## Planned workflow

1. Choose the folders the application may check.
2. Drop a DOCX, XLSX, PPTX, or PDF file into the window.
3. Review any newer or closely related copies found on the computer.
4. Open the recommended file or locate it in File Explorer.

The application will never replace, rename, move, or delete a document automatically.

## Privacy

Document checks take place on the Windows device.

- No account is required.
- Documents are not uploaded.
- Only folders selected by the user are checked.
- No advertising or usage tracking is planned.
- Online-only cloud files will not be downloaded without permission.

## Development progress

- Product research and feature planning are complete.
- The light and dark interface designs are complete.
- The application logo has been approved.
- The technical architecture and privacy rules are complete.
- Windows application development is the next stage.

## Technology

The application is planned for Windows using C#, .NET 10, WinUI 3, and MSIX packaging. Office documents will be read through Open XML, and PDF comparison will run locally.

## Source code

This is the public page for the project. It contains product information and approved presentation material only.

The application source code is private because KSA Latest Copy is proprietary software. The finished application is planned as a free Microsoft Store download, but it will not be open source.

All product names, branding, and materials in this repository are reserved. No permission is granted to copy, modify, or redistribute them.
