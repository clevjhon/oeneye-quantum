# oeneye-quantum 🐱⚛️

### ORNOP Cat Suite - Quantum Classical Gates
![Cat Diagram](cat-diagram.png)
![Logo](logo.png)

**ornop.qasm** = OR + NOP
- OR: `a,b -> a v b`
- NOP: phase-tracked no-op
- Cat: |ψ⟩ = α|alive⟩ + β|dead⟩

Built entirely on Android - Termux + Ubuntu proot
Author: clevjhon (oeneye@proton.me)

## Files
- `ornop.qasm` - ORNOP gate
- `omq.qasm` - OR + Measurement + Qubit cat
- `cat-diagram.png` - superposition diagram
- `logo.png` - qubit cat logo

## 🐛 Launchpad Bug #2170612

[![Launchpad Bug](https://img.shields.io/badge/Launchpad-Bug%20%232170612-critical?logo=launchpad)](https://bugs.launchpad.net/launchpad/+bug/2170612)

**Xenial snap builders fail: snapd socket missing**
- cURL: libcurl3-gnutls 7.47.0-1ubuntu2.19 verified - no fetch attempted
- CHECKSUM: SHA256 5b35c47516499f82bc23dd85d4146c8b04b9e4dd06141fc73d379817893f234 MD5 66ecd534dc947e0b04d56e07c950583
- Full: BUG_REPORT.md + https://bugs.launchpad.net/launchpad/+bug/2170612
