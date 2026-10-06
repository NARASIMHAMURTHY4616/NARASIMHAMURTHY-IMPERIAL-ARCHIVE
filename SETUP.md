# Imperial Archive — GitHub Profile Setup

## Folder structure

```text
NARASIMHAMURTHY4616/
├── README.md
└── assets/
    ├── rajya-gate.svg
    ├── royal-seal.svg
    ├── realm-map.svg
    ├── sabha.svg
    ├── arsenal.svg
    ├── abhiyan-ransomwatch.svg
    ├── abhiyan-trinetra.svg
    ├── abhiyan-studyrag.svg
    ├── abhiyan-cybercrew.svg
    ├── nakshatra.svg
    ├── chronicle.svg
    └── footer-seal.svg
```

## Git method

```bash
git clone https://github.com/NARASIMHAMURTHY4616/NARASIMHAMURTHY4616.git
cd NARASIMHAMURTHY4616

cp /path/to/README.md .
cp -r /path/to/assets .

git add README.md assets/
git commit -m "Reforge profile as imperial archive"
git push origin main
```

If your default branch is not `main`, push to the correct branch.

## Important

The profile repository must be:

`NARASIMHAMURTHY4616/NARASIMHAMURTHY4616`

The README uses relative asset paths (`./assets/...`), so the SVGs are self-hosted by the profile repository.

The only external live widgets are the GitHub stats and streak images in the `NAKSHATRA` section. They can be removed without affecting the rest of the design.
