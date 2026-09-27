# Tufts Face Database

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FTufts--Face--Database-181717?logo=github)](https://github.com/biometric-community/Tufts-Face-Database)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://tdface.ece.tufts.edu/)

**Tufts Face Database** — tbiom catalog packaging for `tufts` (cross-spectral; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/Tufts-Face-Database
- **Upstream source**: http://tdface.ece.tufts.edu/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `tufts` |
| Category | `cross-spectral` |
| Access | `register` |
| Upstream homepage | http://tdface.ece.tufts.edu/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Tufts multi-modal face (VIS/NIR/thermal/...).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/Tufts-Face-Database.git
cd Tufts-Face-Database
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_tufts.sh
```

Place licensed archives under `projects/datasets/tufts/` (gitignored).

## Dataset structure

```text
Tufts-Face-Database/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://tdface.ece.tufts.edu/
- Packaging: https://github.com/biometric-community/Tufts-Face-Database/issues
