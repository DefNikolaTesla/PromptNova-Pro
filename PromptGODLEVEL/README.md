# PromptNova Pro Ultra ⚡

**PromptNova Pro Ultra** is a next-generation, autonomous, 100% offline-capable AI prompt engineering engine designed for ultra-realistic photography and cinematic image generation.

Unlike legacy prompt tools that require paid cloud API keys or external server dependencies, PromptNova Pro Ultra contains a deep, procedural NLP photorealism synthesizer engine that runs entirely within the client browser in under 5 milliseconds.

---

## 🚀 Key Features

### 1. ⚡ 100% Autonomous & Zero-API Required
- Generates exhaustive 850–950+ word master photographic briefs without needing any API key, internet access, or cloud subscription.
- Completely private: your scene ideas and prompts never leave your device.
- Optional Cloud Connector available (Groq, OpenAI, Ollama) if external LLM inference is desired, with seamless zero-latency offline fallback.

### 2. 📸 Deep 6-Layer Photographic Physics Simulation
Every prompt rigorously encodes:
- **Layer 1: Camera Hardware & Optics**: Real-world mechanical signatures from legendary systems (Leica M11 with Summilux 50mm f/1.4 ASPH, Hasselblad X2D 100C with 16-bit HNCS color, Sony A7R V with 85mm GM II, ARRI Alexa Mini LF Anamorphic, Canon EOS R5, iPhone 16 Pro Max ProRAW).
- **Layer 2: Optical Physics & Imperfections**: True-to-life optical behaviors including chromatic aberration (cyan/red edge fringing), natural vignetting falloff (-0.8 EV), spherical lens flare, anamorphic streaks, and exact depth-of-field transition zones.
- **Layer 3: Sensor Dynamics & Film Stocks**: Authentic color science profiles for Kodak Portra 400, CineStill 800T (crimson halation), Fujifilm Superia 400, Kodak Tri-X 400, and Kodachrome 64, paired with monochromatic luminance noise in shadows.
- **Layer 4: Human Anatomy Truth**: Biological asymmetry (1.5mm eye level disparity, 0.8° nasal deviation), visible epidermal pores, cheek peach fuzz (velus hair) in sidelight, sebum shine along T-zone, natural lavender under-eye undertones, organic flyaway hairs, and realistic clothing tension creases.
- **Layer 5: Lived-in Environmental Depth**: 4 distinct focal zones (out-of-focus foreground occlusion, tack-sharp subject plane, textured contextual midground, creamy bokeh background) with volumetric light shafts and dust motes.
- **Layer 6: Candid Compositional Reality**: Authentic 0.9°–2.2° horizon tilt, rule-of-thirds deviation, and spontaneous candid framing.

### 3. 🎯 4 Output Synthesis Modes
1. **Narrative Realism**: 850–950 words continuous photographic prose brief.
2. **SPP JSON Spec**: Structured Parameter Prompt JSON object with 25+ granular parameters.
3. **Platform Tokens**: Weighted token syntax optimized for Midjourney v6.1 (`--style raw`, `--ar`, `--q 2`, `--seed`), FLUX.1 (`--guidance`, `--steps`), SDXL, and DALL-E 3.
4. **Negative Matrix**: Scene-aware negative prompt preventing plastic skin, CGI gloss, and unnatural symmetry.

### 4. 🔮 3-Way Cinematic Variation Matrix
Generate 3 radically distinct photographic interpretations of your scene simultaneously with one click:
- **Variant 1**: Raw Candid Street Documentary (Leica M11)
- **Variant 2**: 35mm Vintage Analog Film (CineStill 800T / Canon R5)
- **Variant 3**: Hollywood Anamorphic Cinema (ARRI Alexa Mini LF)

### 5. 🎛️ Interactive Creative Suite
- **RAW Grittiness Dial**: Scale from L1 (Clean Studio) to L4 (Brutal RAW Documentary).
- **Face Reference Match Studio**: Anchor 10 individual facial features from an attached reference photo.
- **Prompt Archive & Favorites**: Automatic local storage persistence with 1-click restore.
- **🎲 Surprise Me**: Instant inspiration engine with curated cinematic scenes.
- **Interactive Audio Feedback**: Subtle mechanical click sound effects synthesized via Web Audio API.
- **Keyboard Shortcuts**: `Cmd/Ctrl + Enter` to synthesize, `Cmd/Ctrl + K` to clear.

---

## 🛠️ Getting Started

Simply open `index.html` in any modern web browser. No `npm install`, build step, or server configuration is required.

```bash
# Open directly on macOS
open index.html

# Or serve locally using Python
python3 -m http.server 8080
```

---

## 📱 PWA Support

PromptNova Pro Ultra includes a Service Worker (`sw.js`) and Web App Manifest (`manifest.json`), allowing it to be installed as a standalone desktop or mobile application that works 100% offline.

---

## 📄 License
MIT License