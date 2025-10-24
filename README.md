<!-- #  (NeurIPS 2025)
![poster](./fig/teaser.png) -->

<h1 align="center">GOATex: Geometry &amp; Occlusion-Aware Texturing</h1>
<div align="center">
  
## **NeurIPS 2025**
![teaser](fig/teaser.png)

[Hyunjin Kim](https://kormachine.github.io)<sup>*1</sup>, &nbsp; 
[Kunho Kim](https://soulmates2.github.io/)<sup>*2</sup>, &nbsp; 
[Adam Lee](https://scholar.google.com/citations?user=uVYIIp0AAAAJ&hl=en)<sup>3</sup>, &nbsp; 
[Wonkwang Lee](https://1konny.github.io/whoami/)<sup>1,4</sup> (\* equal contribution)

<sup>1</sup>KRAFTON AI, &nbsp; <sup>2</sup>NC AI, &nbsp; <sup>3</sup>UC Berkeley, &nbsp; <sup>4</sup>SNU

<br>


<!-- <a href='https://arxiv.org/abs/'><img src='https://img.shields.io/badge/arXiv.svg'></a> &nbsp; -->
<a href='https://goatex3d.github.io/'><img src='https://img.shields.io/badge/Project-Page-Green'></a> &nbsp;

<br>

</div>

## Introduction
Official Pytorch Implementation of **GOATex: Geometry &amp; Occlusion-Aware Texturing** (NeurIPS 2025)
> We present GOATex, a diffusion-based method for 3D mesh texturing that generates high-quality textures for both exterior and interior surfaces. While existing methods perform well on visible regions, they inherently lack mechanisms to handle occluded interiors, resulting in incomplete textures and visible seams. To address this, we introduce an occlusion-aware texturing framework based on the concept of hit levels, which quantify the relative depth of mesh faces via multi-view ray casting. This allows us to partition mesh faces into ordered visibility layers, from outermost to innermost. We then apply a two-stage visibility control strategy that progressively reveals interior regions with structural coherence, followed by texturing each layer using a pretrained diffusion model. To seamlessly merge textures obtained across layers, we propose a soft UV-space blending technique that weighs each texture’s contribution based on view-dependent visibility confidence. Empirical results demonstrate that GOATex consistently outperforms existing methods, producing seamless, high-fidelity textures across both visible and occluded surfaces. Unlike prior works, GOATex operates entirely without costly fine-tuning of a pretrained diffusion model and allows separate prompting for exterior and interior mesh regions, enabling fine-grained control over layered appearances.

## Release
Code will be released soon.

##  Citation
```
@inproceedings{kim2025goatex,
  author    = {Kim, Hyunjin and Kim, Kunho and Lee, Adam and Lee, Wonkwang},
  title     = {GOATex: Geometry & Occlusion Aware Texturing},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2025}
}
```
