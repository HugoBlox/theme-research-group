---
title: 'CHIMLE: Conditional Hierarchical IMLE for Multimodal Conditional Image Synthesis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - shichong
  - alireza
  - keli

# Author notes (optional)
author_notes:

date: '2022-11-29'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-24'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Advances in Neural Information Processing Systems 2022
publication_short: NeurIPS 2022

abstract: A persistent challenge in conditional image synthesis has been to generate diverse output images from the same input image despite only one output image being observed per input image. GAN-based methods are prone to mode collapse, which leads to low diversity. To get around this, we leverage Implicit Maximum Likelihood Estimation (IMLE) which can overcome mode collapse fundamentally. IMLE uses the same generator as GANs but trains it with a different, non-adversarial objective which ensures each observed image has a generated sample nearby. Unfortunately, to generate high-fidelity images, prior IMLE-based methods require a large number of samples, which is expensive. In this paper, we propose a new method to get around this limitation, which we dub Conditional Hierarchical IMLE (CHIMLE), which can generate high-fidelity images without requiring many samples. We show CHIMLE significantly outperforms the prior best IMLE, GAN and diffusion-based methods in terms of image fidelity and mode coverage across four tasks, namely night-to-day, 16x single image super-resolution, image colourization and image decompression. Quantitatively, our method improves Fréchet Inception Distance (FID) by 36.9% on average compared to the prior best IMLE-based method, and by 27.5% on average compared to the best non-IMLE-based general-purpose methods. More results and code are available on the [project website](https://niopeng.github.io/CHIMLE/).

# Summary. An optional shortened abstract.
summary: We present Conditional Hierarchical IMLE (CHIMLE), a general purposed conditional image synthesis method that generates diverse and high-quality output images. We show CHIMLE significantly outperforms the prior best IMLE, GAN and diffusion-based methods in terms of image fidelity and mode coverage across four tasks, namely night-to-day, 16x single image super-resolution, image colourization and image decompression.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2211.14286'
url_code: 'https://github.com/niopeng/CHIMLE/tree/main/code'
url_dataset: ''
url_poster: ''
url_project: 'https://niopeng.github.io/CHIMLE/'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/plgPL3XyzRg?feature=shared'

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
  - CHIMLE

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


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

<iframe width="100%" height="315"
src="https://www.youtube.com/embed/plgPL3XyzRg">
</iframe>

<!-- include image coders.jpg -->

<br/>
<!-- include a citation block in markdown -->
<p>
If you find our work useful in your research, please consider citing:
</p>

```bibtex
@inproceedings{peng2022chimle,
   title={CHIMLE: Conditional Hierarchical IMLE for Multimodal Conditional Image Synthesis},
   author={Shichong Peng and Alireza Moazeni and Ke Li},
   booktitle={Advances in Neural Information Processing Systems},
   year={2022}
}
```