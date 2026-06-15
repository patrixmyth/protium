# HBES Nuclear Decay Workbook

A Jupyter notebook demonstrating nuclear decay Q-values and half-lives in the native units of the **Hydrogen Blip Exponential Scale (HBES)** framework.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/patrixmyth/protium/blob/main/hbes_decay_workbook.ipynb)

## Units

| Unit | Definition | SI equivalent |
|------|-----------|---------------|
| **BLIP** | 10¹⁰ × τ(H) | ≈ 7.04 s |
| **QUIP** | h × f(H) | ≈ 9.41 × 10⁻²⁵ J |
| **CHIP** | QUIP / c² | ≈ 1.05 × 10⁻⁴¹ kg |

τ(H) = 1 / 1,420,405,751.768 Hz — period of the hydrogen 21 cm hyperfine transition.

## Files

- `hbes_decay_workbook.ipynb` — main notebook
- `hbes_decays.json` — decay data table (Q-values, half-lives, HBES quantities)

## Usage

**Colab:** Click the badge above.

**Local:**
```bash
git clone https://github.com/patrixmyth/protium.git
cd protium
jupyter notebook hbes_decay_workbook.ipynb
```

**Offline export:** The notebook auto-detects whether the `hbes` library is installed and falls back to inline constants if not. `hbes_decays.json` is fetched from GitHub when running in Colab, or read from the local directory otherwise.

## Part of

[redacted.space](https://redacted.space) — BLIP/HBES notation and tooling.
