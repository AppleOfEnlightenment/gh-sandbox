name: report
description: Upload run reports
title: "[REPORT] user"
labels: [Report]
body:
- type: file
  attributes:
    label: `bb-cuda.zip`
    description: Attach your report .zip
    extensions: ["zip"]
    pattern: "bb-host-report.*\.zip"
    required: true
