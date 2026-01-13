<h1 align="center">UDLA</h1>

<div align="center">
  <img width="677" height="369" alt="UDLA_logo(1)" src="https://github.com/user-attachments/assets/b76c5a3a-6e48-42e2-b37f-8fffb358418a" />
</div>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/Unsupervised-Dual-layer-Aggregation/udla?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/Unsupervised-Dual-layer-Aggregation/udla?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Unsupervised-Dual-layer-Aggregation/udla?color=56BEB8">
  <img alt="License" src="https://img.shields.io/github/license/Unsupervised-Dual-layer-Aggregation/udla?color=56BEB8">
</p>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Unsupervised Dual-Layer Aggregation (UDLA) addresses the challenge of selecting and fusing diverse visual features (CNNs and Transformers) without labeled data. The method utilizes unsupervised effectiveness estimation measures to identify the most promising feature sets. It operates through a dual-layer process: 1. First Layer (Precision): Fuses selected feature pairs using contextual rank aggregation (RDPAC) to improve top-rank precision. 2. Second Layer (Recall): Re-evaluates and aggregates the best pairs using Cartesian Product of Ranking References (CPRR) to maximize recall in the final ranked list.

Experimental results on public datasets demonstrate that UDLA yields superior retrieval performance compared to both best-isolated features and recent baselines.


## :sparkles: Features ##

:heavy_check_mark: **Dual-Layer Architecture**: A unique approach that fuses features in two stages—first optimizing for precision using RDPAC, then for recall using CPRR.
:heavy_check_mark: **Unsupervised & Automated**: Automatically selects the best CNN and Transformer features using graph-density effectiveness estimation, with zero need for labeled data.
:heavy_check_mark: **Hybrid Feature Fusion**: seamlessly integrates architectures like Swin Transformer, ViT, ResNet, and DPN.
:heavy_check_mark: **High Accuracy**: Outperforms state-of-the-art unsupervised methods on datasets like Flowers17 and Corel5k.


## :rocket: Technologies ##

The development and evaluation of UDLA relied on the following technologies and architectures:

* [cite_start]**Implementation Framework**: Built upon the **Unsupervised Distance Learning Framework (UDLF)**, which provided the base for fusion methodologies and contextual rank aggregation methods.
* **Visual Transformers (ViT)**:
    * [cite_start]**Swin Transformer (SwinTF)** 
    * [cite_start]**Vision Transformer (ViT-B16)** 
* **Convolutional Neural Networks (CNNs)**:
    * [cite_start]**ResNet152** (Residual Network) 
    * [cite_start]**DPN92** (Dual Path Networks) 
    * [cite_start]**SENet154** (Squeeze-and-Excitation Network) 
    * [cite_start]**Xception** (Extreme Inception) 
* **Rank Aggregation Methods**:
    * [cite_start]**RDPAC** (Rank Diffusion with Assured Convergence) for precision-focused fusion[cite: 136].
    * [cite_start]**CPRR** (Cartesian Product of Ranking References) for recall-focused fusion[cite: 151].
    * [cite_start]**Borda Count** for effectiveness estimation ranking[cite: 124].

## :white_check_mark: Requirements ##

To run this code, you will need **Python 3.x** and the following dependencies. The project relies on the **Unsupervised Distance Learning Framework (UDLF)** for rank aggregation tasks.

### Core Dependencies
* **Python 3.8+**
* [cite_start]**UDLF (Unsupervised Distance Learning Framework)**: Used for the implementation of fusion methods and contextual rank aggregation.
* [cite_start]**NumPy & SciPy**: For matrix operations and distance calculations (Euclidean distance)[cite: 56].

### Feature Extraction (Optional)
[cite_start]If you intend to extract features from scratch using the models described in the paper (Swin Transformer, ViT, ResNet, etc.), you will also need:
* **PyTorch** or **TensorFlow** (depending on your backbone implementation).
* [cite_start]**Pre-trained weights** on ImageNet[cite: 24, 57].

### Datasets
[cite_start]The code is configured to work with the datasets evaluated in the paper[cite: 163, 164]:
* Flowers17
* Corel5k
* Cub200

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/{{YOUR_GITHUB_USERNAME}}/udla

# Access
$ cd udla

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE) file.


Made with :heart: by <a href="https://github.com/ademirj93" target="_blank">Ademir M. Junior</a>

&#xa0;


**Related Papper:**
[Unsupervised Dual-Layer Aggregation for Feature Fusion on Image Retrieval Tasks](https://ieeexplore.ieee.org/abstract/document/10716343)
_37th SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI), 2024._

### Citation

If you use this code, please cite our paper:

```bibtex
@INPROCEEDINGS{10716343,
  author={Junior, Ademir Moreno and Pedronette, Daniel Carlos Guimarães},
  booktitle={2024 37th SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI)}, 
  title={Unsupervised Dual-Layer Aggregation for Feature Fusion on Image Retrieval Tasks}, 
  year={2024},
  pages={193-198},
  doi={10.1109/SIBGRAPI62404.2024.10716343}
}
```

<a href="#top">Back to top</a>
