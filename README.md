<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg" />
  <img width="100%" src="./assets/header-dark.svg" alt="Ipshita Bhardwaj — AI/ML engineer and researcher" />
</picture>

<p align="center">
  <b>AI/ML engineer & researcher</b> building models and software whose decisions can be explained, tested and replayed.
  <br />
  <sub>B.Tech Robotics & Artificial Intelligence · Chandigarh Engineering College, CGC Landran · 2024–2028</sub>
</p>

<p align="center">
  <a href="https://ipshitabhardwaj.me"><img src="https://img.shields.io/badge/portfolio-ipshitabhardwaj.me-e6edf3?style=flat-square&labelColor=0d1117" /></a>
  <a href="https://linkedin.com/in/ipshita-bhardwaj"><img src="https://img.shields.io/badge/linkedin-ipshita--bhardwaj-e6edf3?style=flat-square&labelColor=0d1117" /></a>
  <img src="https://img.shields.io/badge/patents_filed-5-e6edf3?style=flat-square&labelColor=0d1117" />
</p>

<br />

### `00` &nbsp;The short version

I work on models that read messy real-world data, including satellite imagery, aerial photos, speech, sensor signals and plain-language documents, and on the software that turns their output into something a person can act on. The common thread is accountability. A cyclone grade comes with a Grad-CAM map and a confidence score. A policy audit comes with a replayable path and the exact sentence it rests on. If a system can't show why it decided something, I don't consider it finished.

<br />

### `01` &nbsp;Selected builds

<table>
<tr>
<td width="50%" valign="top">

**Dry Run** <!-- add repo link -->
<br /><sub>Python · FastAPI · Pydantic · Ollama (Phi-4-mini) · pytest</sub>

Compiles a written policy or SOP into an explicit state machine using a local open-weight LLM, then finds where a real person would get stuck. A deterministic engine runs exhaustive BFS with 6 failure-injection classes. Every finding carries a replayable path and sentence-level citations.

<sub>Solo build · MIT · 46 tests in CI · Top 10, MLH Hacktoberfest Hack Day</sub>

</td>
<td width="50%" valign="top">

**Cyclone Intensity Classifier & Forecaster** <!-- add repo link -->
<br /><sub>PyTorch · EfficientNet-B0 · GRU · Streamlit</sub>

A dual-head EfficientNet-B0 grades cyclones on IMD's 8-category scale and estimates wind speed and pressure from 1,032 real satellite images. A GRU forecaster then predicts wind speed at +6h, +12h and +24h, with MC-Dropout confidence and rapid-intensification alerts.

<sub>Team build · SIH 2026 · 24h MAE 30.6 vs 38.5 km/h persistence baseline</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Disaster Severity** <!-- add repo link -->
<br /><sub>TensorFlow/Keras · OpenCV · Streamlit</sub>

Explainable damage classification on 16,700+ aerial images across 4 classes. Includes a review dashboard with Grad-CAM, confidence-based triage and PDF reports.

<sub>97% accuracy · 0.96 macro F1</sub>

</td>
<td width="50%" valign="top">

[**PaperPilot**](https://github.com/ipshitabhardwaj/Paper-Pilot)
<br /><sub>React · TypeScript · Node.js · Gemini API · arXiv API</sub>

A research platform for uploaded PDFs and arXiv papers. It produces summaries and reviewer-style critique, and answers questions through a RAG pipeline grounded in the document.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

[**GitScope**](https://github.com/ipshitabhardwaj/GitScope) &nbsp;<sub>Next.js · TypeScript · D3 · Cytoscape · Sigma.js · Drizzle</sub>
<br />
Repository intelligence that maps 2,000+ nodes across contributor networks, commit history and file dependencies, served through real-time APIs.

</td>
</tr>
</table>

<sub>Earlier work: [VocalMind](https://github.com/ipshitabhardwaj/Vocalmind) (voice + text stress detection) · [Luna](https://github.com/ipshitabhardwaj/AI_Comfort_Pet) (7-class emotion recognition) · [Whisper.txt](https://github.com/ipshitabhardwaj/whisper.txt) (anonymous messaging with AI reflections)</sub>

<br />

### `02` &nbsp;Inventions

Five patent applications filed. Each one is built around a model that reads a raw signal, catches a problem early, and responds without getting in the way.

| | Invention | Core idea |
|:--:|:--|:--|
| **I** | Stutter correction via TinyML | Lightweight on-device model that corrects stutters in real time while preserving natural prosody |
| **II** | Radar-based haptic guidance | Interpreting mmWave radar motion data to drive haptic feedback for skill training |
| **III** | In-pipe acoustic leak detection | Acoustic signal analysis that detects and localises leaks inside water pipelines |
| **IV** | Vibration-based condition monitoring | Vibration-signal models that flag failing industrial machines before breakdown |
<!-- | **V** | FIFTH PATENT TITLE | ONE-LINE CORE IDEA | -->

<br />

### `03` &nbsp;Recognition

```
2026  Smart India Hackathon         Grand Finale          cyclone classification & forecasting (SIH26070)
2026  MLH Hacktoberfest Hack Day    Top 10 Finalist       Dry Run, Best Open-Source AI Project track
2026  ICCMST                        1st Prize, Poster     KinesisPro research
2026  INNOTECH, Science City        1st Place
2026  Amazon ML Challenge           Rank 454              of 89,000+ registrants
      IIM Rohtak, Mind Your Metrics National Rank 4       business analytics
      CGC x GeeksforGeeks           1st Place             Innovators Hub project display
```

<br />

### `04` &nbsp;Toolkit

<p>
  <img src="https://skillicons.dev/icons?i=python,ts,js,cpp,c,pytorch,tensorflow,sklearn,fastapi,nodejs,express,react,nextjs,postgres,sqlite,githubactions,aws,git&perline=9&theme=dark" />
</p>

<sub>Also: NumPy · Pandas · OpenCV · Hugging Face · Ollama · RAG · Pydantic · pytest · Vitest · Streamlit · TinyML</sub>

<br />
<br />

### `05` &nbsp;Where I'm headed

Industry ML engineering and applied research, especially explainable models, local LLMs, and multimodal systems that have to work outside the lab.

<br />

<p align="center">
  <sub>Open to research collaborations and ML roles · <a href="https://ipshitabhardwaj.me">ipshitabhardwaj.me</a></sub>
</p>
