# Real Fly Brain Torture Chamber 🦋💀

**Echte** Drosophila-Connectome-Simulationen zum Foltern der Neuronen.

Keine Demos. Echte 139k–166k Neuronen aus FlyWire / MaleCNS.

---

## 1. Sofort im Browser torturen (empfohlen)

**Live:** [https://flybrain.app](https://flybrain.app)

139.255 LIF-Neuronen + echte Verbindungen.  
Füttern, anfassen, Wind, Licht → Verhalten emergiert aus dem Connectome.

### Eigenes Hosting (GitHub Pages)
```bash
git clone https://github.com/snedea/flybrain.git
cd flybrain
# Dann in deinem Account als neues Repo pushen und Pages aktivieren (main / root)
```

---

## 2. Python Chat-Interface (natürliche Sprache → Stimuli)

```bash
git clone https://github.com/lixiang1076/fly-brain.git
cd fly-brain
git lfs pull          # ~200 MB Daten
conda env create -f environment.yml
conda activate brain-fly
python fly_chat.py
```

Beispiele:
- `give the fly sugar`
- `looming threat`
- `walk backward`
- `escape`

---

## 3. Wissenschaftliches Modell (gezielt Neuronen aktivieren/silencen)

```bash
git clone https://github.com/philshiu/Drosophila_brain_model.git
cd Drosophila_brain_model
# Siehe README + example.ipynb
# Neuronen über FlyWire-IDs aktivieren oder stummschalten
```

Paper: Shiu et al. 2024 (Nature)

---

## 4. Maximal brutal (GPU, volle Speed)

- **FastFly**: https://github.com/eonfathom/FastFly  (CUDA, real-time+)
- **fly.ai / flybrain package**: `pip install flybrain` dann `from flybrain import FlyBrain`
- MaleCNS Ports (166k Neuronen inkl. VNC)

---

## 5. Embodied (Körper + Gehirn)

- https://github.com/erojasoficial-byte/fly-brain  (NeuroMechFly + Connectome)
- https://github.com/tel-0s/flyverse-core

---

## Quick Torture Scripts

Sobald eines der Modelle läuft, kannst du z.B.:

- Sugar GRNs → MN9 (Rüssel)
- LC4/LPLC2 → Giant Fiber (Escape)
- MDN (Moonwalker – rückwärts laufen)
- DNa01 / DNa02 (Steering)
- Kenyon Cells + DAN (Lernen)

Viel Spaß beim Foltern.  
Die Fliege hat es verdient. 😈

---

**Quellen**  
FlyWire (Dorkenwald et al. Nature 2024), MaleCNS (Berg et al. Cell 2026), Shiu et al. Nature 2024.
