---
title: 'IceFormer: Accelerated Inference with Long-Sequence Transformers on CPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - yuzhen
  - Martin Ester
  - keli

# Author notes (optional)
author_notes:

date: '2024-05-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The Twelfth International Conference on Learning Representations
publication_short: ICLR 2024

abstract: One limitation of existing Transformer-based models is that they cannot handle very long sequences as input since their self-attention operations exhibit quadratic time and space complexity. This problem becomes especially acute when Transformers are deployed on hardware platforms equipped only with CPUs. To address this issue, we propose a novel method for accelerating self-attention at inference time that works with pretrained Transformer models out-of-the-box without requiring retraining. We experiment using our method to accelerate various long-sequence Transformers, including a leading LLaMA 2-based LLM, on various benchmarks and demonstrate a greater speedup of 2.73x - 7.63x while retaining 98.6% - 99.6% of the accuracy of the original pretrained models. The code is available on our project website at https://yuzhenmao.github.io/IceFormer/.

# Summary. An optional shortened abstract.
# summary: Given a set of images from different views and their corresponding camera poses, PAPR learns a point-based surface representation of the scene and a rendering pipeline from scratch. Additionally, PAPR enables practical applications such as geometry editing, object manipulation, texture transfer, and exposure control.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=6RR3wU4mSZ'
url_code: 'https://github.com/yuzhenmao/IceFormer'
url_dataset: ''
url_poster: ''
url_project: 'https://yuzhenmao.github.io/IceFormer/'
url_slides: ''
url_source: 'https://yuzhenmao.github.io/IceFormer/'
url_video: 'https://youtu.be/6W0DtYRzFng'

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
  - IceFormer

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
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
@inproceedings{
mao2024iceformer,
title={IceFormer: Accelerated Inference with Long-Sequence Transformers on {CPU}s},
author={Yuzhen Mao and Martin Ester and Ke Li},
booktitle={The Twelfth International Conference on Learning Representations},
year={2024},
url={https://openreview.net/forum?id=6RR3wU4mSZ}
}
```