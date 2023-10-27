---
title: 'Sentiment Analysis on Streaming User Reviews via Dual-Channel Dynamic Graph Neural Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Linhai Zhang
  - Deyu Zhou

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-10-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *EMNLP 2023 Conference*
publication_short: In *ICW*

abstract: Sentiment analysis on user reviews has achieved great success thanks to the rapid growth of deep learning techniques. The large number of online streaming reviews also provides the opportunity to model temporal dynamics for users and products on the timeline. However, existing methods model users and products in the real world based on a static assumption and neglect their time-varying characteristics. In this paper, we present DC-DGNN, a dual-channel framework based on a dynamic graph neural network (DGNN) that models temporal user and product dynamics for sentiment analysis. Specifically, a dual-channel text encoder is employed to extract current local and global contexts from review documents for users and products. Moreover, user review streams are integrated into the dynamic graph neural network by treating users and products as nodes and reviews as new edges. Node representations are dynamically updated along with the evolution of the dynamic graph and used for the final score prediction. Experimental results on five real-world datasets demonstrate the superiority of the proposed method.


# Summary. An optional shortened abstract.
summary: Sentiment Analysis; Streaming User Reviews; Dynamic Graph Neural Network; Online Review Websites

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
