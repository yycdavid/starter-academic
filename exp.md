+++
abstract = "We consider a usage model for automated machine learning (AutoML) in which users can influence the generated pipeline by providing a *weak pipeline specification*: an unordered set of API components from which the AutoML system draws the components it places into the generated pipeline. Such specifications allow users to express preferences over the components that appear in the pipeline, for example a desire for interpretable components to appear in the pipeline.  We present AMS, an approach to automatically strengthen weak specifications to include unspecified complementary and functionally related API components, populate the space of hyperparameters and their values, and pair this configuration with a search procedure to produce a *strong pipeline specification*: a full description of the search space for candidate pipelines. AMS uses normalized pointwise mutual information on a code corpus to identify complementary components, BM25 as a lexical similarity score over the target API's documentation to identify functionally related components, and frequency distributions in the code corpus to extract key hyperparameters and values. We show that strengthened specifications can produce pipelines that outperform the pipelines generated from the initial weak specification and an expert annotated variant, while producing pipelines that still reflect the user preferences captured in the original weak specification."

authors = ["**José Cambronero**", "Jürgen Cito", "Martin Rinard"]
date = "2020-06-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*FSE 2020*"
#publication_short = "In *ICMEW*"
selected = true
title = "AMS: Generating AutoML search spaces from weak specifications"
#url_code = "#"
#url_dataset = "#"
url_pdf = "pdf/fse-2020.pdf"
url_project = "https://github.com/josepablocam/ams"
url_slides = "pdf/fse-2020-slides.pdf"
url_video = "https://www.youtube.com/watch?v=5KLwOjcxi20&feature=youtu.be"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
