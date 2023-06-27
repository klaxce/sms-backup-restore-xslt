# Stylesheet for XML from SMS Backup &amp; Restore

This repository contains XSLT stylesheets for transforming XML files
created by the SMS Backup & Restore app.

Currently supported is a "text message bubble" styled HTML format.

## Usage

To use the .xslt files you will need an XSLT processor. I use the _xsltproc_ processor on Windows via Chocolatey.

```bash
xsltproc -o output.html style.xslt example.xml
```

