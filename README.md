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
| [rrelocation](https://github.com/Riviss/rrelocation) | Earthquake relocation pipeline: DBSCAN clustering, waveform cross-correlation, GrowClust3D |
| [spectral_magnitude](https://github.com/Riviss/spectral_magnitude) | Web app for moment magnitude (Mw) from displacement spectra using Brune source model fitting |

### Publications

Gosselin, J.M., H. Kao, R.M.H. Dokht, and **R. Visser** (2026). Robust probabilistic estimation of statistical variations in earthquake records: application to induced seismicity in western Canada. *Geophysical Journal International*, 244(3), ggaf450. [doi:10.1093/gji/ggaf450](https://academic.oup.com/gji/article/244/3/ggaf450/8437922)

Kao, H., R.M.H. Dokht, **R. Visser**, and S. Venables (2026). Seismogenic potential of hydraulic fracturing in the South Montney Play, northeast British Columbia: a seismogenic index approach. *Seismological Research Letters*, 97(1), 383–398. [doi:10.1785/0220240224](https://pubs.geoscienceworld.org/ssa/srl/article/97/1/383/660397)

Wang, B., H. Kao, H. Yu, R.M.H. Dokht, and **R. Visser** (2024). Unveiling key factors governing seismogenic potential and seismogenic productivity of hydraulic fracturing pads: insights from machine learning in the southern Montney Play. *Earth and Planetary Science Letters*, 626, 118511. [doi:10.1016/j.epsl.2023.118511](https://www.sciencedirect.com/science/article/abs/pii/S0012821X2300523X)

Wang, B., H. Kao, R.M.H. Dokht, **R. Visser**, and H. Yu (2022). Delineating the controlling factors of hydraulic fracturing-induced seismicity in the northern Montney Play, northeastern British Columbia, Canada, with machine learning. *Seismological Research Letters*, 93(5), 2439–2450. [doi:10.1785/0220220046](https://pubs.geoscienceworld.org/ssa/srl/article-abstract/93/5/2439/613485)

**Visser, R.**, H. Kao, R.M.H. Dokht, A. Babaie Mahani, and S. Venables (2021). A comprehensive earthquake catalogue for northeastern British Columbia: the Northern Montney Trend from 2017 to 2020 and the Kiskatinaw Seismic Monitoring and Mitigation Area from 2019 to 2020. *Geological Survey of Canada, Open File 8831*.

Babaie Mahani, A., D. Malytskyy, **R. Visser**, M. Hayes, M. Gaucher, and H. Kao (2021). Well-log-based velocity and density models for the Montney unconventional resource play in northeast British Columbia, Canada, applicable to induced seismicity monitoring and research. *Seismological Research Letters*, 92(2A), 886–894. [doi:10.1785/0220200316](https://pubs.geoscienceworld.org/ssa/srl/article-abstract/92/2A/886/592865)

**Visser, R.**, H. Kao, B. Smith, C. Goerzen, B. Kontou, R.M.H. Dokht, et al. (2020). A comprehensive earthquake catalogue for the Fort St. John–Dawson Creek region, British Columbia, 2017–2018. *Geological Survey of Canada, Open File 8713*.

Babaie Mahani, A., F. Esfahani, H. Kao, M. Gaucher, M. Hayes, **R. Visser**, and S. Venables (2020). A systematic study of earthquake source mechanism and regional stress field in the southern Montney unconventional play of northeast British Columbia, Canada. *Seismological Research Letters*, 91(1), 195–206. [doi:10.1785/0220190230](https://www.researchgate.net/publication/337462484)

Kao, H., **R. Visser**, B. Smith, and S. Venables (2018). Performance assessment of the induced seismicity traffic light protocol for northeastern British Columbia and western Alberta. *The Leading Edge*, 37(2), 117–126. [doi:10.1190/tle37020117.1](https://library.seg.org/doi/10.1190/tle37020117.1)

**Visser, R.**, B. Smith, H. Kao, A. Babaie Mahani, J. Hutchinson, and J.E. McKay (2017). A comprehensive earthquake catalogue for northeastern British Columbia and western Alberta, 2014–2016. *Geological Survey of Canada, Open File 8335*. [doi:10.4095/306292](https://publications.gc.ca/site/eng/9.856883/publication.html)

### Tech

Python, ObsPy, SeisBench, NumPy/SciPy, PostgreSQL, Redis, Docker, React/TypeScript, Julia
