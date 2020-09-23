![Image](figure1.png){: width="80%"}{: .center}

## Table of contents
{:.no_toc}
* toc
{:toc}

## Abstract
In this paper, we propose Universal MelGAN: a robust waveform generation model for high-fidelity speech synthesis. The proposed model was improved as follows. 1) We increased the hidden channel sizes of the generator by 4 times and applied gated activation unit to the last layer of each residual stack. 2) To alleviate the over-smoothing problem in high frequency domain caused by the larger model size, we designed multi-resolution spectrogram discriminators and attached to the model. As a result, our model trained by hundreds of speakers recorded the best MOS score among the competing baselines in most seen and unseen domain scenarios such as speaker, language, recording condition or emotion in both Korean and English. In text-to-speech, high-fidelity audio was produced regardless of whether seen or unseen speakers(a real-time synthesis speed of 0.028 RTF on NVIDIA V100 GPU). This result obtained without any explicit domain information suggests the possibility of the proposed model as a universal vocoder.


## Welcome to GitHub Page

You can use the [editor on GitHub](https://github.com/kallavinka8045/icassp2021/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<tr>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
  <td><audio controls ><source src="wav_for_mos/eng/wavernn/eng_seen_single/LJ021-0045.wav" type="audio/wav"></audio></td>
</tr>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kallavinka8045/icassp2021/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
