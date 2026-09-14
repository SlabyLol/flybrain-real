# Real Fly Brain Torture Chamber 🦋💀

**Real** Drosophila connectome simulations. No demos. Real 139k–166k neurons from FlyWire / MaleCNS.

Torture the neurons. Break pathways. Watch the fly react.

---

## 1. Instant Browser Torture (Recommended)

**Live right now:** [https://flybrain.app](https://flybrain.app)

- 139,255 real LIF neurons + real connections from FlyWire FAFB v783
- Behavior emerges from the wiring (not scripted)
- Feed it, touch it, blow air, change light/temperature
- Live spike visualization of all neurons

### Host your own copy
```bash
git clone https://github.com/snedea/flybrain.git
cd flybrain
# Push to your own repo and enable GitHub Pages (main branch, / root)
```

---

## 2. Python Natural-Language Torture Interface

Talk to the brain in English (or Chinese).

```bash
git clone https://github.com/lixiang1076/fly-brain.git
cd fly-brain
git lfs pull                    # ~200 MB of real connectome data
conda env create -f environment.yml
conda activate brain-fly
python fly_chat.py
```

Example commands you can type:
- `give the fly sugar`
- `bitter taste`
- `looming shadow` / `escape`
- `walk forward` / `walk backward`
- `groom antenna`
- `danger smell`
- `freeze`

It translates language → real neural stimulation → full-brain LIF simulation → describes what the fly does.

---

## 3. Scientific Model – Precise Neuron Control

Activate or silence any neurons by FlyWire ID (optogenetics-style).

```bash
git clone https://github.com/philshiu/Drosophila_brain_model.git
cd Drosophila_brain_model
# Follow README + open example.ipynb
```

Paper: Shiu et al., Nature 2024  
"A leaky integrate-and-fire computational model based on the connectome of the entire adult Drosophila brain"

You can:
- Activate specific cell types or single neurons at chosen frequencies
- Silence neurons (zero their synapses)
- Record spike times and rates across the whole brain

---

## 4. Maximum Brutality (GPU / Full Speed)

| Project | What it does | Link |
|---------|--------------|------|
| **FastFly** | CUDA-accelerated, real-time or faster than real time | [eonfathom/FastFly](https://github.com/eonfathom/FastFly) |
| **flybrain (PyPI)** | `pip install flybrain` → full MaleCNS in a few lines of Python | [alextitonis/fly.ai](https://github.com/alextitonis/fly.ai) |
| **MaleCNS ports** | 166k neurons including ventral nerve cord | various 2026 releases |

---

## 5. Embodied (Brain + Body)

Real connectome driving a physical body simulation:

- [erojasoficial-byte/fly-brain](https://github.com/erojasoficial-byte/fly-brain) – NeuroMechFly + full connectome
- [tel-0s/flyverse-core](https://github.com/tel-0s/flyverse-core) – room + table + fruit + walking/flying

---

## Classic Torture Targets (real circuits)

| Stimulus | Key neurons / pathway | Effect |
|----------|-----------------------|--------|
| Sugar | Sugar GRNs → MN9 | Proboscis extension (feeding) |
| Bitter | Bitter receptors | Rejection, retraction |
| Looming | LC4 / LPLC2 → Giant Fiber (DNp01) | Ultra-fast escape takeoff |
| Backward walk | MDN (Moonwalker Descending Neuron) | Reverse walking |
| Forward / steer | DNa01, DNa02 | Walking direction |
| Freeze | DNp09 and related | Stop locomotion |
| Learning | Kenyon Cells + Dopamine neurons (DAN) → MBON | Associative memory |
| Grooming | Mechanosensory → front-leg circuits | Antenna cleaning |

---

## License & Sources

All data comes from public scientific releases:
- FlyWire FAFB (Dorkenwald et al., Nature 2024)
- MaleCNS (Berg et al., Cell 2026)
- Computational model: Shiu et al., Nature 2024

Use responsibly. The fly did nothing wrong.

---

**Want more?** Open an issue or just scream at me. I can add ready-to-run torture scripts, automated stimulus sequences, or help you deploy any of these.
