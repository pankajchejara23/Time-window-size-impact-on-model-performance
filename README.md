# **Impact of Time Window Size on Model Performance**
This repository contains the source code and supplementary materials for the research paper:

"Impact of Window Size on the Generalizability of Collaboration Quality Estimation Models Developed Using Multimodal Learning Analytics."
The research investigates how varying time window sizes affect the performance and generalizability of machine learning models for collaboration quality estimation using multimodal data.

**🎖️ Honorable Mention:** This paper received an **Honorable Mention award (top 5% of submissions)** at the prestigious Learning Analytics and Knowledge (LAK'23) conference.

[![DOI](https://zenodo.org/badge/doi/10.1145/ACM.3576050.svg)](https://doi.org/10.1145/3576050.3576143)

---

## 📜 Abstract
Multimodal Learning Analytics (MMLA) leverages diverse data sources to assess collaboration quality in educational settings. A key question addressed in this study is how the choice of time window size impacts the generalizability of these models across different contexts. Using audio and log data, our findings reveal optimal window sizes for various collaboration dimensions, with significant implications for MMLA research and practice.

For more details, refer to the [full paper]([https://doi.org/XXXXXXX](https://doi.org/10.1145/3576050.3576143)).


---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Required Python libraries (see [requirements.txt](requirements.txt))

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/pankajchejara23/Time-window-size-impact-on-model-performance.git
   cd Time-window-size-impact-on-model-performance
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---


## 📊 Results

Key findings:
- **Collaboration Quality & Argumentation:** Optimal performance with a **60-second window size**.
- **Other Dimensions (e.g., Coordination, Information Processing):** Best performance with 180-second windows.
- **Across-context Generalizability:** Models trained with larger windows (e.g., 180s) exhibit higher generalizability across diverse learning settings.

---

## 📖 Citation
If you use this code in your research, please cite:

```bibtex
@inproceedings{10.1145/3576050.3576143,
author = {Chejara, Pankaj and Prieto, Luis P. and Rodriguez-Triana, Maria Jesus and Ruiz-Calleja, Adolfo and Khalil, Mohammad},
title = {Impact of window size on the generalizability of collaboration quality estimation models developed using Multimodal Learning Analytics},
year = {2023},
isbn = {9781450398657},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3576050.3576143},
doi = {10.1145/3576050.3576143},
booktitle = {LAK23: 13th International Learning Analytics and Knowledge Conference},
pages = {559–565},
numpages = {7},
keywords = {Collaboration Quality, Generalizability, Machine Learning, MultiModal Learning Analytics, Temporal Window},
location = {Arlington, TX, USA},
series = {LAK2023}
}
```


---

## 📧 Contact
For questions or further information, contact:
- **Pankaj Chejara**: [pankajch@tlu.ee](mailto:pankajch@tlu.ee)

---

## 📝 License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the  "Software"), to deal in the Software without restriction, including  without limitation the rights to use, copy, modify, merge, publish,  distribute, sublicense, and/or sell copies of the Software, and to  permit persons to whom the Software is furnished to do so, subject to  the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,  EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF  MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY  CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,  TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE  SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
