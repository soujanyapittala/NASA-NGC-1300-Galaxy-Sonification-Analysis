# NASA-NGC-1300-Galaxy-Sonification-Analysis
Analyzed NASA's NGC 1300 galaxy sonification using Computer Vision, EDA, Image Segmentation, and Audio Signal Processing. Extracted visual and audio features, quantified galaxy structure, and evaluated the relationship between luminosity and sound intensity through statistical analysis

# 🎯 Project Objectives

- Extract visual information from NASA's sonification video
- Analyze image brightness and contrast
- Measure bright and dark pixel density
- Segment major galactic structures
- Detect high-intensity luminous regions
- Analyze the corresponding audio signal
- Measure the relationship between image brightness and sound intensity
- Evaluate the effectiveness of NASA's image-to-sound sonification
# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- OpenCV
- Librosa
- Matplotlib
- Seaborn
# 📊 Image Analysis

The following image features were extracted from every frame of the sonification video:

- Average Brightness
- Image Contrast
- Bright Pixel Density
- Dark Pixel Density
- Frame-to-Frame Variation
- Galaxy Morphology

---

# 🌌 Galaxy Segmentation

Threshold-based segmentation was performed to isolate the brightest structures of the galaxy.

## Detected Structures

- Galactic Nucleus
- Stellar Bar
- Spiral Arms
- Dust Lanes
- Background Space

### Structural Composition

| Structure | Percentage |
|-----------|-----------:|
| Dust Lanes | 59.85% |
| Background Space | 26.38% |
| Spiral Arms | 9.08% |
| Stellar Bar | 3.94% |
| Galactic Nucleus | 0.75% |

Approximately **3,856 high-intensity luminous regions** were detected through threshold-based image analysis.

---

# 🎵 Audio Signal Analysis

Audio extracted from the sonification was analyzed using Librosa.

Analysis included:

- Waveform Analysis
- Spectrogram Analysis
- Frequency Spectrum
- Audio Intensity
- Energy Distribution

---

# 📈 Statistical Analysis

The project measured relationships between visual features and generated sound.

## Correlation Results

| Variables | Correlation |
|-----------|------------:|
| Brightness ↔ Contrast | **0.95** |
| Contrast ↔ Bright Pixel Density | **0.96** |
| Brightness ↔ Bright Pixel Density | **0.89** |
| Brightness ↔ Dark Pixel Density | **-0.70** |

A **strong positive correlation (>0.75)** was also observed between **image brightness** and **audio intensity**.

---

# 🔍 Key Findings

- Brightness peaks occurred when the scan crossed the galactic nucleus, stellar bar, and spiral arms.
- Bright regions exhibited higher structural complexity.
- Approximately **3,856 high-intensity luminous regions** were identified.
- The majority of the galaxy consisted of dust lanes and background space.
- Audio intensity increased consistently while scanning brighter regions.
- Statistical analysis suggests that NASA's sonification preserves meaningful visual information rather than producing arbitrary sound.

---
