---
title: "Script-Guidelines"
date: 2023-06-25
---

## Scripting general guidelines

### Initial questions

- What are the main and specific goals of the script?
- What is needed to achieve them?
- What output is expected? How many files will be generated?
- Will it need to be parallelized?

### Logics

- Major coding blocks
- Detail in graphics or English
- Detail closer to coding language
- Code, adding comments
- Identify fail cases, design solutions and/or error messages

### Script checks and reproducibility

- Include a step to check if the output filename already exists by default (allow it to be disabled)
- Include a step to check if the necessary files are all available
- Check whether the input data appears to be formatted correctly
- What temporary output should be displayed? Perhaps progress or message at key points
- Include an option to disable verbose output
- Which parameters of the analysis should be saved to file?
- Generate log file (main parameters, explanations, perhaps header of used input file)
