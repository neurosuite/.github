# Neurosuite

Free software for visualising and processing neurophysiological recordings:
**NeuroScope** (viewer for local field potentials, spikes, events and animal position),
**Klusters** (manual spike sorting), **NDManager** (recording parameters and processing
pipeline) and **ndmanager-plugins** (conversion, filtering, spike extraction, PCA, video
tracking). Originally written by Lynn Hazan in György Buzsáki's lab, with Michaël Zugaro.

If you use them, please cite: L. Hazan, M. Zugaro, G. Buzsáki (2006). Klusters, NeuroScope,
NDManager: a free software suite for neurophysiological data processing and visualization.
*J Neurosci Methods* 155:207-216.

**Status (October 2026):** being ported to Qt 6; see the
[revival roadmap](https://github.com/neurosuite/neuroscope/issues/7). Until the first Qt 6
release, the all-in-one 2.0.0 package for current Ubuntu is available on
[SourceForge](https://sourceforge.net/projects/neurosuite/files/).

| Repository | What |
|---|---|
| [neuroscope](https://github.com/neurosuite/neuroscope) | Viewer |
| [klusters](https://github.com/neurosuite/klusters) | Cluster cutting |
| [ndmanager](https://github.com/neurosuite/ndmanager) | Parameter and pipeline manager |
| [ndmanager-plugins](https://github.com/neurosuite/ndmanager-plugins) | Processing scripts and tools |
| [libneurosuite](https://github.com/neurosuite/libneurosuite) | Shared library (formerly libklustersshared) |
| [neurosuite-mime](https://github.com/neurosuite/neurosuite-mime) | MIME types and icons (formerly nphys-data) |
| [neurosuite.github.io](https://github.com/neurosuite/neurosuite.github.io) | Website |

The file formats stay stable; SpikeInterface, neo, neuroconv, pynapple and CellExplorer read
them. Licence: GPL-3.0-or-later. Contributions are welcome, see
[CONTRIBUTING](https://github.com/neurosuite/.github/blob/main/CONTRIBUTING.md).
