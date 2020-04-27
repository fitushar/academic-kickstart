---
title: Mass Detection in Breast Using Transfer Learning for Computer Aided Diagnosis
subtitle: Medical Sensor Project ​(Second Semester of MAIA at University of Cassino and Southern Lazio, June 2018)
authors:
- M. K. Hasan, Lavsen Dahal F. I. Tushar
date: "2018-06-25"
#doi: "arXiv:1810.04637"

# Schedule page publish date (NOT publication's date).


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: 	arXiv:1810.04637


abstract: "Mammography is the most widely used gold standard method for the screening of the breast cancer and Mass detection is the prominent pre-processing step. State-of-art performances of the DCNN architectures in the field of classification made them an obvious choice for the image classifications. However, due to limited availability of medical data, application of DCNN architectures in medical images is challenging. In this project our contribution was mass detection in mammographic images using two different approaches. First approach was applying transfer learning concept which lessen the demand of data to use a pre-trained publicly available VGG16 model and second approach was training a Alexnet from the scratch to classify mass and non-mass mammographic images. Both the models were trained and tested with different hyperparameters and different data size. From the experiment results, it can be concluded that transfer learning approach for VGG16, training from fully connected layer 2 (fc2) has promising expected result for mass detection. In our research, maximum accuracy for mass detection was 93.60% for VGG16 with 13500 train images."

# Summary. An optional shortened abstract.
summary: ''

tags:
- CNN
- Transfer Learning
- AlexNet
- VGG16
- Mass classification

featured: true

links:
- name: Slides
  url: https://drive.google.com/open?id=16j2Fu-pLfawkY9cKF7Q8T9ayLVQXJHJl
url_pdf: https://github.com/fitushar/Deep-Learning-for-java--Mass-Classification-using-Transfer-learning/blob/master/Mass%20Detection%20in%20Breast%20Using%20Transfer%20Learning%20for-Report.pdf
url_code: https://github.com/fitushar/Deep-Learning-for-java--Mass-Classification-using-Transfer-learning



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Mass Classification'
  focal_point: ""
  preview_only: false

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
slides: example
---
