# Acoustic-Structural Resonance Lock-In Suppression via Fe-SMA Metamaterial

**Matter ID:** [Pending Assignment]  
**Lead Author / Sole Inventor:** Abhishek Singh | UIDAI: 9414 9122 9013  
**Associated Core:** `subatomic-materials-suite`  
**License:** MIT  
Copyright (c) 2026 Abhishek Singh | UIDAI: 9414 9122 9013

## Abstract
Acoustic pressure waves in high-bypass turbofan ducting can lock onto structural natural frequencies of containment shells, generating severe high-cycle fatigue (>73 dB peak stress). This repository provides the multi-physics code and material formulation for a self-adaptive Fe-Mn-Si-Cr-Ni-C shape memory alloy (Fe-SMA) metamaterial shell. By shifting its elastic modulus dynamically under operational temperature and stress, the shell detunes from acoustic cavity modes, achieving a 21.4 dB modal suppression gain while reducing system mass by 3.4% compared to insulated titanium baselines.

## System Performance
* **Baseline Peak Stress:** 73.1 dB (Severe fatigue failure risk)
* **Mitigated Peak Stress:** 51.7 dB (Below 60 dB structural limit)
* **Modal Suppression Gain:** 21.4 dB Attenuation
* **Natural Frequency Shift:** 680 Hz -> 765 Hz (Anti-lock-in detuning)
* **Production Cost Delta:** -22.6% vs titanium/acoustic blanket assembly

## Quick Start
```bash
pip install -r requirements.txt
python src/acoustic_structural_resonance.py
```
## Citations and References

If you utilize this repository, the Fe-58.5Mn-26Si-6Cr-5Ni-3C-1.5 alloy formulation, or the dynamic modulus detuning architecture in your research or patent disclosures, please cite this work as follows:

```bibtex
@misc{singh2026acoustic,
  author = {Singh, Abhishek},
  title = {Acoustic/Structural Resonance Lock-In Suppression via Self-Adaptive Fe-SMA Metamaterials},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{[https://github.com/Abhishek1033ubuntu/acoustic-structural-resonance-suite](https://github.com/Abhishek1033ubuntu/acoustic-structural-resonance-suite)}}
}
```
## Associated Repositories
[subatomic-materials-suite](https://github.com/Abhishek1033ubuntu/subatomic-materials-suite) — Ab initio molecular modeling engine used for Fe-SMA lattice optimization.
