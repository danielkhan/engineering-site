---
title: "ProbMinHash -- A Class of Locality-Sensitive Hash Algorithms for the (Probability) Jaccard Similarity"
authors:
- otmar

author_notes:
- "Equal contribution"

date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: The probability Jaccard similarity was recently proposed as a natural generalization of the Jaccard similarity to measure the proximity of sets whose elements are associated with relative frequencies or probabilities. In combination with a hash algorithm that maps those weighted sets to compact signatures which allow fast estimation of pairwise similarities, it constitutes a valuable method for big data applications such as near-duplicate detection, nearest neighbor search, or clustering. This paper introduces a class of one-pass locality-sensitive hash algorithms that are orders of magnitude faster than the original approach. The performance gain is achieved by calculating signature components not independently, but collectively. Four different algorithms are proposed based on this idea. Two of them are statistically equivalent to the original approach and can be used as drop-in replacements. The other two may even improve the estimation error by introducing statistical dependence between signature components. Moreover, the presented techniques can be specialized for the conventional Jaccard similarity, resulting in highly efficient algorithms that outperform traditional minwise hashing and that are able to compete with the state of the art.

# Summary. An optional shortened abstract.
summary: A Class of Locality-Sensitive Hash Algorithms for the (Probability) Jaccard Similarity

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: "https://arxiv.org/abs/1911.00675"
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
