# Ultrasound Report Generator

Lightweight web tool for abdominal ultrasound report text generation.

The current working app is a simple browser page:

- open `preview.html`
- enter measurements
- select common findings
- copy the generated report into an existing reporting system

No patient database, no saved previous studies, and no medical platform workflow are required.

## Included Report Logic

- Clinical indication dropdown:
  - Elevated liver enzymes
  - Abdominal pain
  - Gallbladder disease
  - Flank pain
  - Health check-up
- Liver craniocaudal length classification in the midclavicular line:
  - `<= 15.5 cm`: normal liver size
  - `15.6-17.0 cm`: mild hepatomegaly
  - `> 17.0 cm`: hepatomegaly
- Hepatic steatosis wording
- Gallbladder stones, sludge, polyp wording and recommendations
- CBD diameter interpretation
- Pancreas appearance
- Kidney, spleen, and abdominal aorta measurements
- Copy report and print buttons
- Dark mode

## Use

Open this file in a browser:

```text
preview.html
```

The React source is also kept under `frontend/` for a future packaged version.
