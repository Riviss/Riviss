## Hi, I'm Ryan

Seismologist at **Natural Resources Canada** (Pacific Geoscience Centre, Sidney, BC), focused on induced seismicity monitoring in northeastern British Columbia.

I build tools that automate earthquake detection, association, and characterization — from real-time SeedLink ingestion through ML-based phase picking to source parameter estimation.

### What I work on

- **Real-time seismic processing** — live pipelines that ingest waveforms, pick phases with deep learning (SeisBench), associate picks into events, and locate them automatically
- **Induced seismicity analysis** — linking earthquakes to hydraulic fracturing and disposal well operations using probabilistic spatial-temporal association
- **Earthquake relocation** — improving hypocenter precision through waveform cross-correlation and double-difference methods (GrowClust3D)
- **Source characterization** — moment magnitude from spectral analysis, focal mechanisms, stress drop estimation

### Projects

| Repository | Description |
|-----------|-------------|
| [eq_well_association](https://github.com/Riviss/eq_well_association) | Probabilistic association of earthquakes with well activities (HF, disposal, production) in the Montney region |
| [rrelocation](https://github.com/Riviss/rrelocation) | Earthquake relocation pipeline: DBSCAN clustering → waveform cross-correlation → GrowClust3D |
| [spectral_magnitude](https://github.com/Riviss/spectral_magnitude) | Web app for moment magnitude (Mw) from displacement spectra using Brune source model fitting |

### Tech

Python, ObsPy, SeisBench, NumPy/SciPy, PostgreSQL, Redis, Docker, React/TypeScript, Julia

### Contact

📧 ryanvssr@gmail.com
