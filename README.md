

# StreamingT2V

This repository is the official implementation of [StreamingT2V](https://streamingt2v.github.io/).


**[StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773)**
</br>
Roberto Henschel,
Levon Khachatryan,
Daniil Hayrapetyan,
Hayk Poghosyan,
Vahram Tadevosyan,
Zhangyang Wang, Shant Navasardyan, Humphrey Shi
</br>

[arXiv preprint](https://arxiv.org/abs/2403.14773) | [Video](https://twitter.com/i/status/1770909673463390414) | [Project page](https://streamingt2v.github.io/)


<p align="center">
<img src="__assets__/github/teaser/teaser_final.png" width="800px"/>  
<br>
<em>StreamingT2V is an advanced autoregressive technique that enables the creation of long videos featuring rich motion dynamics without any stagnation. It ensures temporal consistency throughout the video, aligns closely with the descriptive text, and maintains high frame-level image quality. Our demonstrations include successful examples of videos up to 1200 frames, spanning 2 minutes, and can be extended for even longer durations. Importantly, the effectiveness of StreamingT2V is not limited by the specific Text2Video model used, indicating that improvements in base models could yield even higher-quality videos.</em>
</p>

## News

* [03/21/2024] Paper [StreamingT2V](https://arxiv.org/abs/2403.14773) released!


## Setup



1. Clone this repository and enter:

``` shell
git clone https://github.com/Picsart-AI-Research/StreamingT2V.git
cd StreamingT2V/
```
2. Install requirements using Python 3.10 and CUDA >= 11.6
``` shell
conda create -n st2v python=3.10
conda activate st2v
pip install -r requirements.txt
```
3. (Optional) Install FFmpeg if it's missing on your system
``` shell
conda install conda-forge::ffmpeg
```



---  


[![Everything Is AWESOME](//img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](//www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")
## Results

### 1200 FRAMES @ 2 MINUTES
<table class="center">
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
  <td>Placeholder</td>
</tr>
<tr>
  <td width=25% align="center">"Explore the coral gardens of the sea..."</td>
  <td width=25% align="center">"Camera moving in a wide bright ice cave."</td>
  <td width=25% align="center">"Experience the dance of jellyfish..."</td>
  <td width=25% align="center">"Wide shot of battlefield, stormtroopers running..."</td>
</tr>
</table>

### 600 FRAMES @ 1 MINUTE
<table>
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
  <td>Placeholder</td>
</tr>
<tr>
  <td width=25% align="center">"Camera following a pack of crows flying in the sky."</td>
  <td width=25% align="center">"Marvel at the diversity of bee species..."</td>
  <td width=25% align="center">"Close flyover over a large wheat field..."</td>
  <td width=25% align="center">"Camera moving down into colorful coral reefs..."</td>
</tr>
</table>

### 240 FRAMES @ 24 SECONDS
<table>
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
</tr>
<tr>
  <td width=25% align="center">"Fluids mixing and changing colors."</td>
  <td width=25% align="center">"Santa Claus is dancing."</td>
  <td width=25% align="center">"Explosion."</td>
</tr>
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
</tr>
<tr>
  <td width=25% align="center">"Flying through nebulas and stars."</td>
  <td width=25% align="center">"Camera moving closely over beautiful roses blooming timelapse."</td>
  <td width=25% align="center">"Documenting the growth cycle of vibrant lavender flowers..."</td>
</tr>
</table>


### 80 FRAMES @ 8 SECONDS
<table>
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
  <td>Placeholder</td>              
</tr>
<tr>
  <td width=25% align="center">"Ants, beetles and centipede nest."</td>
  <td width=25% align="center">"Fishes swimming in ocean camera moving."</td>
  <td width=25% align="center">"A squirrel on a table full of big nuts."</td>
  <td width=25% align="center">"Enter the fascinating world of bees..."</td>
</tr>
<tr>
  <td>Placeholder</td>
  <td>Placeholder</td>
  <td>Placeholder</td>              
  <td>Placeholder</td>              
</tr>
<tr>
  <td width=25% align="center">"A hummingbird flutters among colorful flowers..."</td>
  <td width=25% align="center">"Drone fly to a mansion in a tropical forest."</td>
  <td width=25% align="center">"Flying above a breathtaking limestone structure..."</td>
  <td width=25% align="center">"Beneath the majestic Northern Lights of Iceland."</td>
</tr>
</table>

## License
Our code is published under the CreativeML Open RAIL-M license. The license provided in this repository applies to all additions and contributions we make upon the original stable diffusion code. The original stable diffusion code is under the CreativeML Open RAIL-M license, which can found [here](https://github.com/CompVis/stable-diffusion/blob/main/LICENSE).


## BibTeX
If you use our work in your research, please cite our publication:
```
@article{henschel2024streamingt2v,
  title={StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text},
  author={Henschel, Roberto and Khachatryan, Levon and Hayrapetyan, Daniil and Poghosyan, Hayk and Tadevosyan, Vahram and Wang, Zhangyang and Navasardyan, Shant and Shi, Humphrey},
  journal={arXiv preprint arXiv:2403.14773},
  year={2024}
}
```

