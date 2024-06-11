---
title: 'PAPR: Proximity Attention Point Rendering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - yanshu
  - shichong
  - alireza
  - keli

# Author notes (optional)
author_notes:

date: '2024-04-28'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-28'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Conference on Neural Information Processing Systems 2023
publication_short: NeurIPS 2023

abstract: Learning accurate and parsimonious point cloud representations of scene surfaces from scratch remains a challenge in 3D representation learning.  Existing point-based methods often suffer from the vanishing gradient problem or require a large number of points to accurately model scene geometry and texture. To address these limitations, we propose Proximity Attention Point Rendering (PAPR), a novel method that consists of a point-based scene representation and a differentiable renderer. Our scene representation uses a point cloud where each point is characterized by its spatial position, influence score, and view-independent feature vector. The renderer selects the relevant points for each ray and produces accurate colours using their associated features. PAPR effectively learns point cloud positions to represent the correct scene geometry, even when the initialization drastically differs from the target geometry. Notably, our method captures fine texture details while using only a parsimonious set of points. We also demonstrate four practical applications of our method, which are zero-shot geometry editing, object manipulation, texture transfer, and exposure control. More results and code are available at https://zvict.github.io/papr.

# Summary. An optional shortened abstract.
summary: Given a set of images from different views and their corresponding camera poses, PAPR learns a point-based surface representation of the scene and a rendering pipeline from scratch. Additionally, PAPR enables practical applications such as geometry editing, object manipulation, texture transfer, and exposure control.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2307.11086'
url_code: 'https://zvict.github.io/papr/'
url_dataset: 'https://zvict.github.io/papr/'
url_poster: ''
url_project: 'https://zvict.github.io/papr/'
url_slides: ''
url_source: 'https://zvict.github.io/papr/'
url_video: 'https://youtu.be/1atBGH_pDHY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - PAPR

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above.
{{% /callout %}} -->


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

<iframe width="100%" height="315"
src="https://youtube.com/embed/xKt6YYY4hq8">
</iframe>

<!-- include image coders.jpg -->
<!-- <p>
In the following figure, we can see how the Adaptive IMLE algorithm shrinks neighbourhoods around data points in a toy example. You can find a jupyter notebook that includes a basic implementation of Adaptive IMLE here.
</p> -->
<!-- <img src="https://mehranagh20.github.io/AdaIMLE/assets/img/adaptive_imle_training.gif" alt="training" width="50%" center/> -->

<!-- <br/> -->
<!-- include a citation block in markdown -->
<!-- <p>
If you find our work useful in your research, please consider citing:
</p> -->

```bibtex
@inproceedings{zhang2023papr,
    title={PAPR: Proximity Attention Point Rendering},
    author={Yanshu Zhang and Shichong Peng and Seyed Alireza Moazenipourasil and Ke Li},
    booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
    year={2023}
}
```