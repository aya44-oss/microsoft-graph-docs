---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc print printers jobs patch --printer-id {printer-id} --print-job-id {printJob-id} --body '{\
  "configuration": {\
    "feedOrientation": "longEdgeFirst",\
    "pageRanges": [\
      {\
        "start": 1,\
        "end": 1\
      }\
    ],\
    "quality": "medium",\
    "dpi": 600,\
    "orientation": "landscape",\
    "copies": 1,\
    "duplexMode": "oneSided",\
    "colorMode": "blackAndWhite",\
    "inputBin": "by-pass-tray",\
    "outputBin": "output-tray",\
    "mediaSize": "A4",\
    "margin": {\
      "top": 0,\
      "bottom": 0,\
      "left": 0,\
      "right": 0\
    },\
    "mediaType": "stationery",\
    "finishings": null,\
    "pagesPerSheet": 1,\
    "multipageLayout": "clockwiseFromBottomLeft",\
    "collate": false,\
    "scaling": "shrinkToFit",\
    "fitPdfToPage": false\
  }\
}\
'

```