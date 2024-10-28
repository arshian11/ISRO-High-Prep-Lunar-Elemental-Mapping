# High-Resolution Elemental Mapping of Lunar Surface

## Problem Description

X-ray fluorescence (XRF) lines are detected in CLASS during solar flares. The XRF line energy identifies the element, while the intensity depends on solar flare strength, solar zenith angle, and composition. By taking linear ratios, the angular dependence and incident solar flux dependence can be eliminated to some extent.

For example, Mg/Si and Al/Si ratios can reflect the compositional heterogeneity fairly well (Figure 1).<br>
Global XRF line ratio maps at a spatial resolution of ~12 km can be generated from CLASS data, which would create a new independent map useful for geochemical and resource mapping.

![Figure 1](assets/aa40321-21-fig2.jpg)

The observed spectrum in CLASS (Figure 2) consists of XRF lines, scattered solar X-rays, and background arising from particles in the lunar orbit. The routine CLASS data analysis pipeline models the X-ray spectra with good statistics to derive elemental abundances. <br>
Several spectra are added to achieve statistics, except for occasions when the incident solar flux is high.

The objective here is to utilize the entire set of XRF spectra measured by CLASS to derive XRF line intensities and create a high-resolution elemental ratio map that would identify compositional differences at kilometer scales.
