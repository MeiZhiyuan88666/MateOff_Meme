<div align="center">
    <h1 align="center">
        <img src="./assets/logo.png" alt="logo" height="35" style="vertical-align: middle; margin-right: 10px;" />
        <b><em>MetaOff-Meme: A Metaphor-Enriched Benchmark for Meme Offensiveness Detection</em></b>
    </h1>
    <a href="https://meizhiyuan88666.github.io/MetaOff-Meme.github.io/" target="_blank">
        <img alt="Website" src="https://img.shields.io/badge/🌎Website-MetaOff--Meme-blue.svg" height="25"/>
    </a>
    <a>
        <img src="https://img.shields.io/github/stars/MeiZhiyuan88666/MateOff_Meme?style=flat&logo=github" alt="GitHub stars" height="25"/>
    </a>
    <a>
        <img src="https://img.shields.io/github/forks/MeiZhiyuan88666/MateOff_Meme?style=flat&logo=github" alt="GitHub forks" height="25"/>
    </a></div><br>


we construct a meme offensiveness detection dataset, MetaOff-Meme, with metaphorical annotations, providing valuable resources for advancing research in this field.

The dataset labels are in the file `data/data.json` directory.

The appendix of the paper is located in `paper/MetaOff_Appendix.pdf`.

For the image dataset, please click [here](https://drive.google.com/file/d/1R4pAiawNSOJnPBPe9_BSnJJlWc1O_gy2/view?usp=sharing).

🚨***Disclaimer: The examples provided in this article may be disturbing.***

## 🌟Introduction to MetaOff-meme

<p align="center">
  <img src="./assets/F2.png" style="width: 90%; height: auto">
</p>

### (1): Offensiveness Annotation:

> > 1.Offensiveness:	non-offensive(0);	offensive(1)
> >
> > 2.Offensive Topic:	Group(0);	Gender(1);	Political(2);	Individual(3);	Other(4)
> >
> > 3.Offensive Level:	Not(0);	Slightly(1);	Moderately(2);	Very(3)	
> >
> > 4.Offensive Scope:	Individual(0);	Group(1)

### (2):Metaphor Annotation: 

> > 1.source domain, target domain: 	the relevant description of things.
> >
> > 2.source modality, target modality : text(0);	image(1);	complementary(2)
> >
> > 3.metaphor relation: 	attribute description of the comparison between the source domain and the target domain
> >
> > 4.metaphor overall explanation
> >
> > **Note that some metaphoric relationships in memes may have two instances. Therefore, we add subscripts _1 and _2 to different metaphors to distinguish their corresponding relationships.**

## ❗Ethics Statement

We believe that the benefits of the provided resources outweigh the associated risks and that their use can contribute meaningfully to scientific advancements.  All resources are intended solely for scientific research purposes and are strictly prohibited from commercial use.  Users are expected to adhere to ethical guidelines and applicable regulations when utilizing the dataset.

## 📄 License

![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg) ![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg) **Usage and License Notices**: The data and code are intended and licensed for research use only.
License: Attribution-NonCommercial 4.0 International It should abide by the policy of OpenAI: https://openai.com/policies/terms-of-use
