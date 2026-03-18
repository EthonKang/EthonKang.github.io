<table>
  <tr>
    <td width="180" valign="center">
      <img src="ksir.jpg" alt="ksir" height="200">
    <td valign="top">

# Ethon Kang <!-- omit in toc -->

<a href="https://jekyll-themes.com">
  <img src="https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg" height="20" alt="Jekyll Themes Shield">
</a>

**Ethon Kang** is a PhD student in Computer Science and Engineering at Central South University, expected to graduate in 2028.

> My current research interests cover machine learning and computer vision, involving few-shot learning, domain adaptation learning, and visual and language learning, among other topics.
>
> -- <a href="https://github.com/EthonKang/EthonKang.github.io/"><cite>Ethon Kang</cite></a>
  </tr>
</table>

## Table of Contents <!-- omit in toc -->

- [Researches](#Researches)
- [Publications](#Publication)
- [Publications2](#Publication2)
- [Usage](#usage)
  - [Configuration](#configuration)
  - [Customizing Head](#customizing-head)
  - [Creating Themes](#creating-themes)
  - [Customizing Navigation](#customizing-navigation)
  - [Customizing Cover Image](#customizing-cover-image)
  - [Customizing Social Links](#customizing-social-links)
  - [Enabling Posts Archive](#enabling-posts-archive)
  - [Enabling TOC](#enabling-toc)
  - [Enabling MathJax](#enabling-mathjax)
  - [Something More](#something-more)
- [Development](#development)
- [License](#license)

## Researches
- PhD Candidate specializing in AI-driven algorithms for agricultural equipment, including object detection, regression, and domain adaptation. 
- Developing intelligent solutions for agriculture through computer vision and machine learning.


## Publications
**2026**
<div class="publication-item"> 
  <div class="publication-title">TSNet with Sigma-Adaptive Spectral Sampling for Real-Time Tea Moisture Monitoring in Industrial Processing</div> 
  <div class="publication-authors">
    <strong>Yisen Kang</strong>, Fang Qi, Liyuan Deng, Dengpeng Zou, Huan Wang, Yang Li, Yang Wei, Xinlin Wei, Zhe Tang
  </div> 
  <div class="publication-venue">
    <em>Journal of Food Measurement and Characterization</em>, 2026
  </div> 
  <div class="publication-links">
    <a href="#" target="_blank">[PDF]</a>
    <a href="#" target="_blank">[DOI]</a>
  </div> 
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>Accurate, non-destructive estimation of leaf moisture during tea withering is foundational for closed-loop control and quality assurance in industrial tea processing.Although near-infrared spectroscopy is widely adopted for this purpose, field deployment remains fragile: leaf folding/occlusion and pose drift introduce spectral instability and necessitate frequent recalibration, undermining robustness and scalability.To overcome these limitations, we develop SpecTea, an end-to-end system that integrates robust spectral acquisition, sequence modeling, and real-time inference.The method exploits the dynamics of withering to enhance spectral separability and reduce information entropy, and introduces a SASS strategy that combines spatially adaptive five-point segmentation with dynamic Poisson-disk sampling to select informative regions.A custom spectroscopic apparatus secures representative measurements, which are modeled by TSNet, a sequence architecture that fuses self-attention with GRUs for moisture prediction.On held-out tests, TSNet achieves a correlation coefficient of 0.9917, an RMSE of 2.7612, and an RPD of 2.7552, surpassing traditional machine-learning baselines and recent deep models.The SASS-enabled acquisition consistently reduces inter-spectral variance, improving generalization across batches and processing conditions. When deployed on the withering line, the system attains an average error of 3.89%, comfortably meeting the $\leq 5\%$ industrial threshold and demonstrating stable online performance despite leaf pose and occlusion variations. The approach also lowers recalibration frequency, reducing operational burden and downtime. By unifying adaptive sampling with attention-based sequence learning in a deployable pipeline, SpecTea delivers a practical, scalable solution for real-time NIR moisture sensing, offering a transferable blueprint for robust quality control in tea manufacturing and related agri-food processes.</p>
    </details>
  </div> 
</div>

<div class="publication-item"> 
  <div class="publication-title">Image Shadow Detection and Removal via Illumination Estimation and Chromaticity Guidance</div> 
  <div class="publication-authors">
    Yang Li, Jindong He, Dengpeng Zou, <strong>Yisen Kang</strong>, Wei Xiang, Fang Qi, Zhe Tang
  </div> 
  <div class="publication-venue">
    <em>IEEE Transactions on Automation Science and Engineering</em>, 2026
  </div> 
  <div class="publication-links">
    <a href="#" target="_blank">[PDF]</a>
    <a href="https://doi.org/10.1109/TASE.2025.3595929" target="_blank">[DOI]</a>
  </div> 
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>Current deep learning-based shadow detection and removal algorithms exhibit critical limitations in adequately modeling the physical properties of shadows and exploring their inherent luminance and chrominance characteristics. To tackle these challenges, this paper proposes a shadow detection and removal model via illumination estimation and chromaticity guidance (CI-GAN).</p>
    </details>
  </div> 
</div>

**2025**
<div class="publication-item"> 
  <div class="publication-title">Enhanced Sensitivity of SPR Sensor Using Au@Bi<sub>2</sub>Se<sub>3</sub> Core-Shell Nanoparticles and Lead Ion Detection</div> 
  <div class="publication-authors">
    Tingyu Wang, <strong>Yisen Kang</strong>, Leyong Jiang, Zhiwei Zheng, Shan Liang
  </div> 
  <div class="publication-venue">
    <em>IEEE Sensors Journal</em>, 2025
  </div> 
  <div class="publication-links">
    <a href="#" target="_blank">[PDF]</a>
    <a href="https://doi.org/10.1109/JSEN.2025.3605113" target="_blank">[DOI]</a>
  </div> 
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>Surface Plasmon Resonance (SPR) sensors are widely used for sensitive and label-free detection in various fields, but their performance is often limited by the low sensitivity and non-specific targeting of conventional gold film-based sensors. This study proposes a novel SPR sensor incorporating gold nanocubes (AuNCs) and bismuth selenide (Bi<sub>2</sub>Se<sub>3</sub>) in a core-shell structure (Au@Bi<sub>2</sub>Se<sub>3</sub>) to enhance sensor performance. By utilizing the seed-mediated growth method, Au@Bi<sub>2</sub>Se<sub>3</sub> particles were prepared and integrated with a gold film-based SPR platform for the detection of lead ions (Pb<sup>2+</sup>). Experimental results showed that the sensor fabricated with Au@Bi<sub>2</sub>Se<sub>3</sub> particles exhibited a sensitivity of 6522.72 nm/RIU, surpassing the performance of conventional SPR sensors. Additionally, the sensor demonstrated excellent detecting capabilities for lead ion, with a linear relationship observed between the reflectance curve and Pb<sup>2+</sup> concentration. This study highlights the potential of the Au@Bi<sub>2</sub>Se<sub>3</sub> core-shell structure to significantly improve SPR biosensor sensitivity and specificity, offering promising applications in environmental monitoring and medical diagnostics.</p>
    </details>
  </div> 
</div>

**2024**
<div class="publication-item"> 
  <div class="publication-title">Sensor-Integrated Transformer-RF Model for HAR</div> 
  <div class="publication-authors">
    <strong>Yisen Kang</strong>, Zheng Wang, Xiaoqi Sun, Huan Wang, Ruiqi Lu, Dengpeng Zou, Mingyuan Liao, Xiaokang Shi, Yanwen Wang, Renfa Li
  </div> 
  <div class="publication-venue">
    <em>2024 IEEE 30th International Conference on Parallel and Distributed Systems (ICPADS)</em>, 2024
  </div> 
  <div class="publication-links">
    <a href="#" target="_blank">[PDF]</a>
    <a href="https://doi.org/10.1109/ICPADS63350.2024.00084" target="_blank">[DOI]</a>
  </div> 
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>This paper proposes a HAR algorithm based on Transformer and Random Forest (RF), introducing a sensor-integrated Transformer-RF model for human activity recognition.</p>
    </details>
  </div> 
</div>

<div class="publication-item"> 
  <div class="publication-title">FireSonic: Design and Implementation of an Ultrasound Sensing-Based Fire Type Identification System</div> 
  <div class="publication-authors">
    Zheng Wang, Yanwen Wang, Mingyuan Liao, Yi Sun, Shuke Wang, Xiaoqi Sun, Xiaokang Shi, <strong>Yisen Kang</strong>, Mi Tian, Tong Bao, Ruiqi Lu
  </div> 
  <div class="publication-venue">
    <em>Sensors</em>, 2024, 24(13): 4360
  </div> 
  <div class="publication-links">
    <a href="https://www.mdpi.com/1424-8220/24/13/4360/pdf" target="_blank">[PDF]</a>
    <a href="https://doi.org/10.3390/s24134360" target="_blank">[DOI]</a>
  </div> 
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>This paper introduces FireSonic, an acoustic sensing system that leverages ultrasound signals for fire type identification. The system is designed to provide accurate and prompt recognition of different fire sources under real-world conditions, aiming to improve firefighting response and reduce damage.</p>
    </details>
  </div> 
</div>


## Publications2

You can choose one of the following methods to install Not Pure Poole:

- Directly specify the `not-pure-poole` gem.

    1. Add `gem 'not-pure-poole'` into your `Gemfile`.
    2. Add the below lines into your `_config.yml`.

        ```yml
        plugins:
          - not-pure-poole
        ```

- If your site is hosted on GitHub Pages, you can use [`jekyll-remote-theme`](https://github.com/benbalter/jekyll-remote-theme) to import the master branch of Not Pure Poole.

    1. Add `gem 'jekyll-remote-theme'` into your `Gemfile`.
    2. Add the below lines into your `_config.yml`.

        ```yml
        plugins:
          - jekyll-remote-theme

        remote_theme: vszhub/not-pure-poole
        ```

## Usage

You can read this [example post](https://vszhub.github.io/not-pure-poole/2020/09/29/welcome-to-not-pure-poole/) to see the rendering result in this theme, and put the [source](_posts/2020-09-29-welcome-to-not-pure-poole.md) aside to learn some basic usages.

### Configuration

The [`_config.yml`](_config.yml) file in this repository already contains some variables, you can try to override them in your repository.

### Customizing Head

Not Pure Poole leaves a placeholder to allow defining custom head, in principle, you can add anything here, e.g. favicons. All you need to do is just creating a file `_includes/custom-head.html` and put data into it.

### Creating Themes

If you want to make your own color schemes, modify the CSS variables in the `_sass/_variables.scss` stylesheet with a scoped data attribute or class name.

For example, below we've created the beginnings of a blue theme:

```scss
// Example blue theme
[data-theme="blue"] {
  --body-bg: var(--blue);
  --body-color: #fff;
}
```

Then, apply the theme by adding `data-theme="blue"` to the `<html>` element.

### Customizing Navigation

You can create a file `_data/navigation.yml` to configure links to some pages. For example,

```yml
- title: Blog
  url: /
- title: About
  url: /about/
```

### Customizing Cover Image

You can set your own cover image by modifying the `cover_image` variable in `_config.yml`, and you can also set different cover images on different pages by setting the `cover_image` variable on each page.

If you discover that the contrast between the cover text color and the cover background color is not enough, you can also adjust these two variables:

```yml
cover_bg_color: rgb(40, 73, 77)
cover_color: rgb(255, 255, 255)
```

### Customizing Social Links

You can set your social links in `_data/social.yml`. You can custom titles, URLs, and icons (only support [Font Awesome](https://fontawesome.com/) currently), for example:

```yml
- title: Email
  url: mailto://vszhub@gmail.com
  icon: fas fa-envelope
- title: Twitter
  url: https://twitter.com/vszhub
  icon: fab fa-twitter
- title: GitHub
  url: https://github.com/vszhub/not-pure-poole
  icon: fab fa-github
```

### Enabling Posts Archive

Not Pure Poole supports posts archive by date, categories, and tags. For enabling that, you should put some data like below into `_data/archive.yml`:

```yml
- type: dates
  title: Dates
  url: /dates/
- type: categories
  title: Categories
  url: /categories/
- type: tags
  title: Tags
  url: /tags/
```

After that, the navigation to these archive pages would be shown on the top of the homepage.

Then, you can create a category archive page, and set the below parameters on that page:

```yml
---
layout: archive-taxonomies
type: categories
---
```

Or a tag archive page:

```yml
layout: archive-taxonomies
type: tags
```

Or archive by dates:

```yml
layout: archive-dates
```

### Enabling TOC

If you want to show the TOC of a page on the right side, just set `toc: true` on that page.

### Enabling MathJax

If you want to write mathematics on a page, just set `math: true` on that page to enable MathJax.

### Something More

Just **hack** into the code and see what you can get.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `not-pure-poole.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
