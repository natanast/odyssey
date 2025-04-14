# Odyssey

Odyssey is an R shiny application for the exploration of Molecular Biodiversity in Greece.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Related_Publications](#related_publications)

## Installation

To install Odyssey, follow these steps:
1. Install the necessary R packages. You can use the following command to install all dependencies:
```r
# Install necessary packages
install.packages(c("shiny", "data.table", "bslib", "stringr", "ggplot2", "paletteer", "reactable", "lubridate", "leaflet", "leaflet.extras", "htmltools", "echarts4r", "crosstalk"))
```
2. Clone the repository from GitHub
```r
git clone https://github.com/BiodataAnalysisGroup/ELIXIR-BFSP-Odyssey.git
```

## Usage
To run the Odyssey Shiny app, follow these steps:

1. Open the main.R script in RStudio.
2. Execute the script by clicking the "Run" button

## Contributing
Your input is invaluable - whether it's suggesting a new chart/analysis or reporting a bug, we welcome and greatly appreciate your feedback! 

Feel free to open a [GitHub issue](https://github.com/npechl/MBioG/issues) or contact us via `inab.bioinformatics@lists.certh.gr`.


## License
This work, as a whole, is licensed under the [MIT license](https://github.com/npechl/MBioG/blob/main/LICENSE).

The code contained in this website is simultaneously available under the MIT license; this means that you are free to use it in your own packages, as long as you cite the source.

## Related_Publications
- N. Pechlivanis, A. Anastasiadou, A. Papageorgiou, E. Pafilis, and F. Psomopoulos, “Odyssey: an Interactive R Shiny App Approach to explore Molecular Biodiversity in Greece,” **23rd European Conference On Computational Biology (ECCB24)**, Sep. 2024, doi: [10.5281/ZENODO.14186452](https://zenodo.org/records/14186453).

<div align='center'>
<img src="https://github.com/natanast/odyssey/blob/main/pic/ECCB2024_poster.png" alt="ECCB2024 Poster" style="height: 750px; width:550px;"/>
</div>
