---
title: "A study of deep learning-based multi-horizon building energy forecasting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhongjun Ni
- Chi Zhang
- Magnus Karlsson
- Shaofang Gong

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-01-15T00:00:00Z"
doi: "https://doi.org/10.1016/j.enbuild.2023.113810"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Energy and Buildings*
# publication_short: In *ICW*

abstract: Building energy forecasting facilitates optimizing daily operation scheduling and long-term energy planning. Many studies have demonstrated the potential of data-driven approaches in producing point forecasts of energy use. Despite this, little work has been undertaken to understand uncertainty in energy forecasts. However, many decision-making scenarios require information from a full conditional distribution of forecasts. This study has adapted and applied state-of-the-art deep learning architectures to address the problem of multi-horizon building energy forecasting. Eight different methods, including seven deep learning-based ones, were investigated to develop models to perform point and probabilistic forecasts. A comprehensive case study was conducted in two public historic buildings with different operating modes, namely the City Museum and the City Theatre, in Norrköping, Sweden. The performance of the developed models was evaluated, and the predictability of different scenarios of energy consumption was studied. The results show that incorporating future information on exogenous factors that determine energy use is critical for making accurate multi-horizon predictions. Furthermore, changes in the operating mode and activities held in a building bring more uncertainty in energy use and deteriorate the prediction accuracy of models. As assessed by the coefficient of variance of the root mean square error (CV-RMSE), the temporal fusion transformer (TFT) model exhibited strong competitiveness in performing point forecasts. The TFT model outperformed other models in predicting both types of energy use of the City Museum (CV-RMSE 29.7% for electricity consumption and CV-RMSE 8.7% for heating load) and heating load of the City Theatre (CV-RMSE 13.3%). In contrast to the dominance of the TFT model in point forecast, none of the models dominated the probabilistic forecast. The TFT, long short-term memory (LSTM), and gated recurrent unit (GRU) models made better probabilistic forecasts than others. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S037877882301040X'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
