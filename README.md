<h1 align="center">Romain Andres</h1>
<h3 align="center">AI Engineer — Explainable AI & Deep Learning for Oncology and Personalized Medicine</h3>

<p align="center">
  <a href="https://vendenix.github.io/portfolio/"><strong>Portfolio & CV</strong></a> ·
  <a href="https://vendenix.github.io/portfolio/publications/">Publications</a> ·
  <a href="https://www.linkedin.com/in/romain-andres-6b551b203/">LinkedIn</a> ·
  <a href="mailto:contact.randres@gmail.com">Email</a>
</p>

I build deep learning systems for oncology that clinicians can actually trust — from segmentation models deployed in radiotherapy workflows to explainability pipelines that catch a model relying on the wrong signal before it reaches a clinic. Co-first author on a *NeuroImage* paper, first author on a manuscript currently under review. Currently looking for my next step: a **CIFRE PhD** or a **research/AI engineer role**.

## Featured work

<table>
<tr>
<td width="220"><img src="images_readme/xai-glioblastoma.gif" width="200"></td>
<td>

**Explainability & Clinical Trust of Deep Learning in Glioblastoma Treatment Response** — *first-author manuscript, under review*

A multi-layered XAI pipeline (Grad-CAM, LRP, LIME, linear probing, causal activation patching) auditing a ResNet-51q model — and catching it relying on a proxy for surgical resection status instead of real tumoral features.

[`Read the write-up →`](https://vendenix.github.io/portfolio/blog/2025/xai-glioblastoma-treatment-response/) · [`Code`](https://github.com/VendenIX/GBM-Treatment-Response-XAI)

</td>
</tr>
<tr>
<td width="220"><img src="images_readme/metia-neuroimage.gif" width="200"></td>
<td>

**MetIA — Deep Learning Interface for Brain Metastases Segmentation** — *co-first author, published in [NeuroImage](https://doi.org/10.1016/j.neuroimage.2025.121002), Vol. 306 (2025)*

UNETR-based segmentation model deployed into a clinical OHIF Viewer interface at Centre François Baclesse, from Flask API to ML Ops on the center's infrastructure.

[`Read the write-up →`](https://vendenix.github.io/portfolio/blog/2024/metia-ohif-brain-segmentation/) · [`Code`](https://github.com/VendenIX/BrainMetaSegmentatorUI-Front)

</td>
</tr>
<tr>
<td width="220"><img src="images_readme/genetic-pedigree.gif" width="200"></td>
<td>

**GeneticPedigreeChartToPed — Digitizing Family Trees for Hereditary Cancer Risk**

A six-model computer vision pipeline (YOLO, EasyOCR, DeepLSD, graph reconstruction) turning hand-drawn pedigree charts into structured data for tools like CanRisk.

[`Read the write-up →`](https://vendenix.github.io/portfolio/blog/2023/genetic-pedigree-chart-to-ped/) · [`Code`](https://github.com/VendenIX/GeneticPedigreeChartToPedAI)

</td>
</tr>
</table>

<details>
<summary><strong> Earlier projects</strong> (coursework & side projects)</summary>
<br>

| Project | Description |
|---|---|
| [Sorting Algorithms Visualizer](https://vendenix.github.io/portfolio/blog/2023/sorting-algorithms-visualizer/) | C++ visualizer + Python/Jupyter benchmarking of sorting algorithms across data distributions. |
| [AI vs. AI — Virus Board Game](https://vendenix.github.io/portfolio/blog/2022/virus-board-game-ai/) | Minimax/Alpha-Beta Pruning agents battling on a custom board game. |
| [Todolist — React Native](https://vendenix.github.io/portfolio/blog/2022/todolist-react-native/) | First React project: a to-do app on a Node.js/GraphQL CRUD API. |
| [Fractal Flowers Generator](https://vendenix.github.io/portfolio/blog/2021/fractal-flowers-lsystem/) | Procedural flora generation from scratch using L-systems (Java). |

</details>

## Publications
Most of this work was carried out at Centre François Baclesse (Caen) under the supervision of Dr. Aurélien Corroyer-Dulmont (PhD, HDR).

| Title | Venue | My contribution |
|---|---|---|
| [Development and routine implementation of a deep learning algorithm for automatic brain metastases segmentation on MRI for RANO-BM criteria follow-up](https://doi.org/10.1016/j.neuroimage.2025.121002) | NeuroImage, Vol. 306 (2025) | **Co-first author**<br>Optimized model inference, built the clinical integration (OHIF Viewer, Flask API, deployment), and contributed to method design, data curation, results analysis, and manuscript writing and review. |
| Explainability and Clinical Trust of Deep Learning in Glioblastoma Treatment Efficacy Prediction | Manuscript under review (2025) | **First author**<br>Led the study end to end: designed and implemented the XAI pipeline, performed image segmentation with computer vision methods, ran the analysis, produced the figures, and drafted and revised the manuscript. |

Full abstracts and BibTeX on the [publications page](https://vendenix.github.io/portfolio/publications/).

## Tech stack

- **Deep learning & XAI:** PyTorch · Grad-CAM/LRP/LIME · UNet/UNETR/ResNet · Fed-BioMed
- **Medical imaging:** DICOM · NIfTI · OHIF Viewer
- **Data & backend:** Python (NumPy/SciPy/pandas) · Flask · GraphQL · PostgreSQL · MongoDB
- **Tools:** Docker · Kubernetes · Git · Linux

<p align="left">
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="36" height="36"/></a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="36" height="36"/></a>
  <a href="https://kubernetes.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" alt="kubernetes" width="36" height="36"/></a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="36" height="36"/></a>
  <a href="https://pytorch.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="pytorch" width="36" height="36"/></a>
  <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"><img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="36" height="36"/></a>
  <a href="https://graphql.org" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="36" height="36"/></a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="36" height="36"/></a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="36" height="36"/></a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="36" height="36"/></a>
  <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="36" height="36"/></a>
</p>

## Contact
<p>
  contact.randres@gmail.com
</p>
<p align="left">
  <a href="https://www.linkedin.com/in/romain-andres-6b551b203/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="36" height="36"/>
  </a>
</p>
