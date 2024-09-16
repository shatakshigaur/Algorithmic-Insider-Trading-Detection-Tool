<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/tuhinmallick/InsiderTrader">
    <img src="docs/images/logo.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">InsiderTrader</h3>

  <p align="center">
    InsiderTrader is a python package that helps in detecting insider trading activities in the stock market.
    <br />
    <a href="https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/blob/main/notebooks/Insider_trading_analysis.ipynb">View Demo</a>
    ·
    <a href="https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/issues">Report Bug</a>
    ·
    <a href="https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Insider trading refers to the practice of buying or selling securities by individuals who possess non-public information about a company. This information may include financial results, mergers and acquisitions, or other confidential information that is not yet available to the public. The individuals who engage in insider trading are typically corporate insiders, such as company executives and board members, but it can also include anyone who possesses non-public information.

Description
The Algorithmic Insider Trading Detection Tool is designed to identify suspicious trading activities using advanced machine learning and data analysis techniques. The tool leverages the `insider_eda` Python package to conduct comprehensive exploratory data analysis (EDA) on insider trading data, enabling the detection of potentially unlawful trading behavior.

Features:
Exploratory Data Analysis (EDA): Utilizes `insider_eda` to analyze insider trading patterns and market behavior.
Data Preprocessing: Cleans and processes raw data from financial reports and stock trading data sources.
Machine Learning Models: Detects patterns of insider trading using supervised and unsupervised learning models.
Visualization: Provides insightful visualizations of trading activities, highlighting suspicious patterns.
Customizable: Users can extend the package for specific datasets and detection algorithms.

Technologies Used:
Programming Language: Python
Packages/Frameworks:
  - `insider_eda` (Custom package for EDA)
  - `Pandas`, `NumPy` for data manipulation
  - `Matplotlib`, `Seaborn` for data visualization
  - `Scikit-learn` for machine learning algorithms


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!--
### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

Install [InsiderTrader](https://pypi.org/project/insidertrader/0.1.0/) from pypi

```bash
  pip install insidertrader
```


### Usage

1. Clone the repo
   ```bash
   git clone https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool.git
   ```
2. Go to the project directory
   ```bash
   cd InsiderTrader
   ```
3. Install environment or dependecies
   ```bash
   conda env create -n ENVNAME --file docs/environment.yml
   ```
   or
   ```bash
   pip install -r requirements.txt
   ```
4. Import the package in `.py`
   ```bash
   from insider_eda.eda_base import Exploratory_data_analysis
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Example

_For more examples, please refer to the [Notebook](https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/blob/main/notebooks/Insider_trading_analysis.ipynb)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Granger casaulty test
- [x] AD Fuller test
- [ ] Make package pip installable
  - [ ] Make readme.rst

See the [open issues](https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 🛡 License

[![License](https://img.shields.io/github/license/tuhinmallick/InsiderTrader)](https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/blob/master/LICENSE)

This project is licensed under the terms of the `MIT` license. See [LICENSE](https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool/blob/master/LICENSE) for more details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Authors

- [@shatakshigaur](https://www.github.com/shatakshigaur)

<!-- CONTACT -->

## Contact

Your Name - [@shatakshigaur] - shatakshigaur.sg@gmail.com

Project Link: [https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool](https://github.com/shatakshigaur/Algorithmic-Insider-Trading-Detection-Tool)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [ilyaryabov](https://www.kaggle.com/datasets/ilyaryabov/insider-trading-sp500-inside-info)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->


