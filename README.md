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

:heavy_check_mark: Feature 1;\
:heavy_check_mark: Feature 2;\
:heavy_check_mark: Feature 3;

## :rocket: Technologies ##

The following tools were used in this project:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

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


Made with :heart: by <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">{{YOUR_NAME}}</a>

&#xa0;


**Related Papper:**
[Unsupervised Dual-Layer Aggregation for Feature Fusion on Image Retrieval Tasks](https://ieeexplore.ieee.org/abstract/document/10716343)
_37th SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI), 2024._

### Citation

If you use this code, please cite our paper:

```bibtex```
@INPROCEEDINGS{10716343,
  author={Junior, Ademir Moreno and Pedronette, Daniel Carlos Guimarães},
  booktitle={2024 37th SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI)}, 
  title={Unsupervised Dual-Layer Aggregation for Feature Fusion on Image Retrieval Tasks}, 
  year={2024},
  pages={193-198},
  doi={10.1109/SIBGRAPI62404.2024.10716343}
}

<a href="#top">Back to top</a>
