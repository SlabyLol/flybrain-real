# Real Fly Brain Torture Chamber 🦋💀

**Real** interactive Drosophila brain simulation using the FlyWire connectome.

## Quick Start (GitHub Pages)

1. Enable GitHub Pages on this repo:
   - Settings → Pages → Source: Deploy from a branch
   - Branch: `main` / folder: `/ (root)`
2. Wait 1-2 minutes
3. Open: `https://slabylol.github.io/flybrain-real/`

**Important:** The full binary connectome data (~60MB) is large. For the complete working version with all 139k neurons:

```bash
git clone https://github.com/snedea/flybrain.git
cd flybrain
# Then copy the data/ folder into this repo or run locally by opening index.html
```

Or just use the live original: **https://flybrain.app**

## What you can do

- **Feed** the fly
- **Touch** different body parts
- Blow **Air**
- Change **Light** and **Temperature**
- Watch real-time neuron firing in the connectome panel
- Toggle 3D brain view

Behavior is **not scripted**. It emerges from signal propagation through the real measured connections.

## Full Python / GPU options

See the previous README commits or:
- https://github.com/lixiang1076/fly-brain (chat interface)
- https://github.com/philshiu/Drosophila_brain_model (precise control)
- https://github.com/eonfathom/FastFly (GPU)

Torture responsibly.
