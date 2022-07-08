# Machine-learning-approaches-for-classification-of-Plasmodium-falciparum-life-cycle



<br />
<div align="center">
  
<h3 align="center">Machine learning approaches for classification of
Plasmodium falciparum life cycle stages using
single-cell transcriptomes</h3>

 
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
        <li><a href="#how_to_run">How to run</a></li>
      </ul>
    </li>
    <li><a href="#usage">File details</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`

Malaria, spread by the female Anopheles mosquito, is a highly fatal disease widespread
in many parts of the world, causing 0.4 million deaths globally. Vital gene expressions
form the basis in the detection of malaria infection levels. Quantification of malaria
parasite infected RBCs and classification of its life cycle stages are done at macroscopic
level by experts, for making informed decisions. Off late multiple computational ap-
proaches have been proposed to circumvent the problem of dimensionality leading to
accurate predicted results. In this work a dimensionality reduction technique based
on Genetic Algorithm (GA) is applied on P. falciparum single-cell transcriptomics to
arrive at an optimized subset of features from the larger dataset. Features are chosen
based on their class variants considering increased efficiency and accuracy, to sepa-
rately transform the selected elements into a lower dimension. For the classification of the life cycle of malaria parasite based on single cell transcriptome data, a three-
pronged approach employing the multiclass Support Vector Machine (SVM), Logistic
Regression (LR) and Random Forest (RF) techniques is used. Distribution of cells was
visualised and mapped using the R-based Seurat package. Further, we constructed pro-
tein interaction networks of the genes identified by the feature selection method and
elucidated the role of the proteins in progression of the parasite through it’s life cycle.
Our approach presents a novel protocol to implement ML techniques on scRNA seq
datasets and subsequently harnessing the extracted information for biomarker/drug
target detection.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* Python 3.5
* sklearn
* sklearn-genetic

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

These are the steps to run the code locally on your pc:
### Prerequisites


* pip install all the required library
  

### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/swarnimshukla/Machine-learning-approaches-for-classification-of-Plasmodium-falciparum-life-cycle.git
   ```
2. Install pip packages
   ```sh
   pip3 install
   ```
### How to run
```sh
   Run ga_feature_selection.ipynb on jupyter notebook after installing all the libraries.
   ```
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## File Details

* Data.zip -> input data
* ExploratoryDataAnalysis.ipynb -> input data analysis
* ga_feature_selection.ipynb -> main file with feature selection code
* classification_without_feature_selection.ipynb -> code for classification without feature selection
* Classification_of_selected_features.ipynb -> code for classification with feature selection
* random300_features.ipynb -> randomly 300 features classifcation 
* mutual_information_of_CM.ipynb -> mutual information of selected features
* mutual_information_of_CM-full_features.ipynb -> mutual information with all features
* heatmap.ipynb -> Expression profile of the selected features
* bar_graph_plot.ipynb -> bar plot generated in the paper



<p align="right">(<a href="#top">back to top</a>)</p>





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Swarnim Shukla - swarnim.shukla@research.iiit.ac.in

Project Link: [https://github.com/swarnimshukla/Machine-learning-approaches-for-classification-of-Plasmodium-falciparum-life-cycle.git](https://github.com/swarnimshukla/Machine-learning-approaches-for-classification-of-Plasmodium-falciparum-life-cycle.git)

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 