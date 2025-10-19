---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}


<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-3GCYPY09SM"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-3GCYPY09SM');
</script>




<span class='anchor' id='about-me'></span>
# 🔥 Biography
I am a research fellow at Nanyang Technological University, working with Prof. [Yang Liu](https://personal.ntu.edu.sg/yangliu/). I received my Ph.D. Degree from the University of Chinese Academy of Sciences, advised by Professor [Xiaochun Cao](https://scst.sysu.edu.cn/members/caoxiaochun.htm). My PhD research interests include computer vision, adversarial attack, adversarial training and reinforcement learning etc. 

I was a visiting student (Remote) from February, 2023 to September, 2023 in the [Torr Vision Group](https://torrvision.com/), University of Oxford. I was a research intern  from March, 2022 to February, 2023 at  Ali Group Security. I was a research intern from May, 2020 to February, 2022 at Tencent AI Lab. 

At present, I am focused on issues related to the security of large models, including jailbreaking attacks on LLM (Large Language Models), adversarial transferability on VLM (Vision Language Models), and so on.
<p style="color: blue;">I am actively seeking highly self-motivated students who have a strong background and interests in my research topics (but are not limited). Please drop me an email with your CV if you are interested in working with me (Email: jiaxiaojunqaq@gmail.com). Together, we have the chance to embark on a gratifying journey, confronting real-world problems and achieving substantial, tangible impacts.</p>



# 🎉 News
- *2025.10*: &nbsp; One papers on Security of VLM is accepted in TIFS2025.
- *2025.09*: &nbsp; Two papers on Security of MLLM/Agent are accepted in NeurIPS2025.
- *2025.09*: &nbsp; One papers on Security of Agent are accepted in S&P2025.
- *2025.08*: &nbsp; Three papers on Security of MLLM are accepted in EMNLP2025.
- *2025.07*: &nbsp; One papers on Privacy of VLMs are accepted in ACM MM2025.
- *2025.06*: &nbsp; Four papers on Security of MLLM are accepted in ICCV2025.
- *2025.06*: &nbsp; One paper on Adversarial Transferability for VLP models accepted in TPAMI2025.
- *2025.05*: &nbsp; Two papers on Satety of LLMs are accepted in ACL2025.
- *2025.05*: &nbsp; Two papers on Satety of MLLMs are accepted in ICML2025.
- *2025.04*: &nbsp; One paper on Dataset Ownership Verification for MLLM is accepted in SIGIR2025.
- *2025.03*: &nbsp; One paper on Jailbreak Defense for MLLM is accepted in TOSEM2025.
- *2025.02*: &nbsp; One paper on Ownership Verification is accepted in TPAMI2025.
- *2025.02*: &nbsp; One paper on Adversarial Attack for Arbitrary-scale Super-resolution is accepted in TIFS2025.
- *2025.01*: &nbsp; One paper on Jailbreak Attack for LLM is accepted in ICLR2025.

<!--
- *2024.12*: &nbsp; One paper on Jailbreak Attack for T2I Models is accepted in AAAI2025.
- *2024.12*: &nbsp; One Journal paper on Adversarial Attack for MLLMs is accepted to TIFS2025.
- *2024.08*: &nbsp; Champion in CCDM 2024 Red Teaming Multimodal Large Language Model Security Challenge.
- *2024.07*: &nbsp; One paper on Unlearnable Examples for VLP is accepted in ACM MM2024.
- *2024.07*: &nbsp; One paper on Transferability of Adversarial Examples on VLP is accepted in ECCV2024.
- *2024.06*: &nbsp; One paper on Fast Adversarial Training is accepted in TIFS2024.
- *2024.05*: &nbsp; One paper on Universal Adversarial Examples is accepted in TIFS2024.
- *2024.04*: &nbsp; One paper on Survey on Transferability of Adversarial Examples is accepted in TMLR2024.
- *2024.03*: &nbsp; One paper on Fast Adversarial Training is accepted in TPAMI2024.
- *2024.02*: &nbsp; One paper on Adversarial Attack on 3D is accepted in CVPR2024.
- *2024.01*: &nbsp; One paper on Backdoor Attack is accepted in ICLR2024.
- *2024.01*: &nbsp; One Journal paper on Backdoor Attack is accepted to TIFS2024.
- *2023.12*: &nbsp; Second runner-up in NeurIPS 2023 Red Teaming Track - Base Model Subtrack.
- *2023.12*: &nbsp; One paper on AI safety and robustness is accepted in AAAI2024.
- *2023.12*: &nbsp; One Journal paper on AI safety and robustness is accepted in IJCV2024.
- *2023.10*: &nbsp; One Journal paper on Fast Adversarial Training is accepted to TIFS2024.-->


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/2025PAMI_SA_AET.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Semantic-Aligned Adversarial Evolution Triangle for High-Transferability Vision-Language Attack](https://arxiv.org/pdf/2411.02669), <br />
**Xiaojun Jia**, Sensen Gao, Qing Guo, Ke Ma, Yihao Huang, Simeng Qin, Yang Liu, Ivor Tsang Fellow, Xiaochun Cao, <br />
**IEEE Transactions on Pattern Analysis and Machine Intelligence 2025 (TPAMI 2025)** \| [**Project**](https://arxiv.org/pdf/2411.02669) \| [Github](https://github.com/jiaxiaojunQAQ/SA-AET)
  
</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/2025ACL_POUGH.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Efficient Universal Goal Hijacking with Semantics-guided Prompt Organization](https://arxiv.org/abs/2405.14189), <br />
Yihao Huang, Chong Wang, **Xiaojun Jia(Corresponding Author)**, Qing Guo, Felix Juefei-Xu, Jian Zhang, Yang Liu, Geguang Pu, <br />
**Annual Meeting of the Association for Computational Linguistics 2025 (ACL2025)** \| [**Project**](https://arxiv.org/abs/2405.14189) 
  
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/2025SIGIR_PATFinger.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [PATFinger: Prompt-Adapted Transferable Fingerprinting against Unauthorized Multimodal Dataset Usage](https://arxiv.org/pdf/2504.11509), <br />
Wenyi Zhang, Ju Jia, **Xiaojun Jia**, Yihao Huang, Xinfeng Li, Cong Wu, and Lina Wang, <br />
**International ACM SIGIR Conference on Research and Development in Information Retrieval 2025 (SIGIR2025)**  \| [**Project**](https://arxiv.org/pdf/2504.11509)
  
</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/TPAMI2025_Move.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Move: Effective and harmless ownership verification via embedded external features](https://arxiv.org/abs/2208.02820), <br />
  Yiming Li, Linghui Zhu, **Xiaojun Jia(Corresponding Author)**, Yang Bai, Yong Jiang, Shu-Tao Xia, Xiaochun Cao, Kui Ren, <br />
  **IEEE Transactions on Pattern Analysis and Machine Intelligence 2025 (TPAMI 2025)** \| [**Project**](https://arxiv.org/abs/2208.02820) \| [Github](https://github.com/THUYimingLi/MOVE)

</div>
</div> 




<div class='paper-box'><div class='paper-box-image'><div><img src='images/TIFS2025_SI.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- [Scale-Invariant Adversarial Attack against Arbitrary-scale Super-resolution](https://arxiv.org/pdf/2503.04385), <br />
Yihao Huang, Xin Luo, Qing Guo, Felix Juefei-Xu, **Xiaojun Jia(Corresponding Author)**, Weikai Miao, Geguang Pu, Yang Liu <br />
 **IEEE Transactions on Information Forensics and Security 2025 (TIFS 2025)** \| [**Project**](https://ieeexplore.ieee.org/document/10919122) \| [Github](https://github.com/Ecnu-luobote/SIAGT)

</div>
</div> 








<div class='paper-box'><div class='paper-box-image'><div><img src='images/ICLR2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Improved techniques for optimization-based jailbreaking on large language models](https://arxiv.org/abs/2405.21018),  <br />
**Xiaojun Jia**, Tianyu Pang, Chao Du, Yihao Huang, Jindong Gu, Yang Liu, Xiaochun Cao, Min Lin,  <br />
**International Conference on Learning Representations 2025 (ICLR 2025)** \| [**Project**](https://arxiv.org/abs/2405.21018) \| [Github](https://github.com/jiaxiaojunQAQ/I-GCG)


</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/PJI.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- [Perception-guided Jailbreak against Text-to-Image Models](https://arxiv.org/pdf/2408.10848), <br />
Yihao Huang, Le Liang, Tianlin Li, **Xiaojun Jia(Corresponding Author)**, Run Wang, Weikai Miao, Geguang Pu, Yang Liu <br />
 **Thirty-Ninth AAAI Conference on Artificial Intelligence (AAAI-25)** \| [**Project**](https://arxiv.org/pdf/2408.10848) \| [Github](https://github.com/LeLiang-SJTU/PGJ-T2l)

</div>
</div> 




<div class='paper-box'><div class='paper-box-image'><div><img src='images/AdvDiffVLM.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- [Efficient Generation of Targeted and Transferable Adversarial Examples for Vision-Language Models via Diffusion Models](https://arxiv.org/abs/2404.10335), <br />
Qi Guo, Shanmin Pang, **Xiaojun Jia(Corresponding Author)**, Yang Liu, Qing Guo <br />
 **IEEE Transactions on Information Forensics and Security 2025 (TIFS 2025)** \| [**Project**](https://ieeexplore.ieee.org/abstract/document/10812818) \| [Github](https://github.com/gq-max/AdvDiffVLM)

</div>
</div> 




<div class='paper-box'><div class='paper-box-image'><div><img src='images/ACMMM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Multimodal Unlearnable Examples: Protecting Data against Multimodal Contrastive Learning](https://arxiv.org/pdf/2407.16307), <br />
Xinwei Liu, **Xiaojun Jia(Corresponding Author)**, Yuan Xun, Siyuan Liang, Xiaochun Cao, <br />
**Proceedings of the 32nd ACM International Conference on Multimedia 2024 (ACM MM, 2024)**  \| [**Project**](https://arxiv.org/pdf/2407.16307) \| [Github](https://github.com/thinwayliu/Multimodal-Unlearnable-Examples)

</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/ECCV2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Boosting Transferability in Vision-Language Attacks via Diversification along the Intersection Region of Adversarial Trajectory](https://arxiv.org/pdf/2403.12445), <br />
Sensen Gao, **Xiaojun Jia(Corresponding Author)**, Xuhong Ren, Ivor Tsang, and Qing Guo <br />
**European Conference on Computer Vision 2024 (ECCV 2024)** \| [**Project**](https://arxiv.org/pdf/2403.12445) \| [Github](https://github.com/SensenGao/VLPTransferAttack)

</div>
</div> 




<div class='paper-box'><div class='paper-box-image'><div><img src='images/FGSM_LAW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Revisiting and Exploring Efficient Fast Adversarial Training via LAW: Lipschitz Regularization and Auto Weight Averaging](https://arxiv.org/pdf/2308.11443.pdf), <br />
  **Xiaojun Jia**,  Yuefeng Chen, Xiaofeng Mao, Ranjie Duan, Jindong Gu, Rong Zhang, Hui Xue, Yang Liu, and Xiaochun Cao, <br />
  **IEEE Transactions on Information Forensics and Security 2024 (TIFS 2024)**  \| [**Project**](https://ieeexplore.ieee.org/abstract/document/10574880) \| [Github](https://github.com/jiaxiaojunQAQ/FGSM-LAW)

</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/TIFS2024_UAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Texture Re-scalable Universal Adversarial Perturbation](https://arxiv.org/pdf/2406.06089), <br /> 
  Yihao Huang, Qing Guo, Felix Juefei-Xu, Ming Hu,  **Xiaojun Jia(Corresponding Author)**, Xiaochun Cao, Geguang Pu and Yang Liu, <br />
  **IEEE Transactions on Information Forensics and Security 2024 (TIFS 2024)**  \| [**Project**](https://ieeexplore.ieee.org/document/10559847) \| [Github]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [A Survey on Transferability of Adversarial Examples Across Deep Neural Networks](https://openreview.net/pdf?id=AYJ3m7BocI), <br />
  Jindong Gu, **Xiaojun Jia**, Pau de Jorge, Wenqian Yu, Xinwei Liu, Avery Ma, Yuan Xun, Anjun Hu, Ashkan Khakzar, Zhijiang Li, Xiaochun Cao, Philip Torr,<br />
  **Transactions on Machine Learning Research 2024 (TMLR 2024)** \| [**Project**](https://openreview.net/forum?id=AYJ3m7BocI&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DTMLR%2FAuthors%23your-submissions)) \| [Github](https://github.com/JindongGu/awesome_adversarial_transferability)

</div>
</div> 





<div class='paper-box'><div class='paper-box-image'><div><img src='images/FGSM_PGK.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Improving Fast Adversarial Training with Prior-Guided Knowledge](https://arxiv.org/pdf/2304.00202.pdf), <br />
  **Xiaojun Jia**, Yong Zhang, Xingxing Wei, Baoyuan Wu, Ke Ma, Jue Wang, and Xiaochun Cao, <br />
  **IEEE Transactions on Pattern Analysis and Machine Intelligence 2024 (TPAMI 2024)** \| [**Project**](https://ieeexplore.ieee.org/abstract/document/10478545) \| [Github](https://github.com/jiaxiaojunQAQ/FGSM-PGK)

</div>
</div> 




<div class='paper-box'><div class='paper-box-image'><div><img src='images/Hit_adv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Hide in Thicket: Generating Imperceptible and Rational Adversarial Perturbations on 3D Point Clouds](https://arxiv.org/pdf/2403.05247.pdf), <br />
Tianrui Lou,  **Xiaojun Jia(Corresponding Author)**, Jindong Gu, Li Liu, Siyuan Liang, Bangyan He, Xiaochun Cao, <br />
**Computer Vision and Pattern Recognition Conference 2024 (CVPR 2024)** \| [**Project**](https://arxiv.org/pdf/2403.05247.pdf) \| [Github](https://github.com/TRLou/HiT-ADV)

</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/ICLR2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Poisoned Forgery Face: Towards Backdoor Attacks on Face Forgery Detection](https://arxiv.org/pdf/2402.11473.pdf),  <br />
Jiawei Liang, Siyuan Liang, Aishan Liu, **Xiaojun Jia**, Junhao Kuang, Xiaochun Cao,  <br />
**International Conference on Learning Representations 2024 (ICLR 2024)** \| [**Project**](https://openreview.net/pdf?id=8iTpB4RNvP) \| [Github](https://github.com/JWLiang007/PFF?tab=readme-ov-file)


</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Minimalism_is_King_TIFS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Minimalism is King! High-Frequency Energy-based Screening for Data-Efficient Backdoor Attacks](https://ieeexplore.ieee.org/document/10478135), <br />
  Yuan Xun, **Xiaojun Jia(Corresponding Author)**, Jindong Gu, Xinwei Liu, Qing Guo, Xiaochun Cao, <br />
  **IEEE Transactions on Information Forensics and Security 2024 (TIFS 2024)**  \| [**Project**]([https://ieeexplore.ieee.org/abstract/document/10574880](https://ieeexplore.ieee.org/document/10478135)) \| [Github]

</div>
</div> 





<div class='paper-box'><div class='paper-box-image'><div><img src='images/AAAI2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Does Few-shot Learning Suffer from Backdoor Attacks?](https://arxiv.org/pdf/2401.01377.pdf), <br />
Xinwei Liu, **Xiaojun Jia(Corresponding Author)**, Jindong Gu, Yuan Xun, Siyuan Liang, Xiaochun Cao,<br />
**Thirty-Eighth AAAI Conference on Artificial Intelligence (AAAI 2024)**

</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/IJCV2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Context-Aware Robust Fine-Tuning](https://arxiv.org/pdf/2211.16175.pdf),<br />
Xiaofeng Mao, Yufeng Chen, **Xiaojun Jia**, Rong Zhang, Hui Xue and Zhao Li,<br />
**International Journal of Computer Vision (IJCV 2023)**

</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/FP_Better.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Propagation is Better: Accelerating Single-Step Adversarial Training via Sampling Subnetwork](https://arxiv.org/pdf/2310.15444.pdf), <br />
**Xiaojun Jia**, Jianshu Li, Jindong Gu, Yang Bai and Xiaochun Cao, <br />
**IEEE Transactions on Information Forensics and Security 2024 (TIFS 2024)**  \| [**Project**](https://ieeexplore.ieee.org/abstract/document/10471619) \| [Github](https://github.com/jiaxiaojunQAQ/FP-Better)

</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Hi_SIGIR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Hi-SIGIR: Hierachical Semantic-Guided Image-to-image Retrieval via Scene Graph](https://dl.acm.org/doi/10.1145/3581783.3612283), <br />
Yulu Wang, Pengwen Dai, **Xiaojun Jia**, Zhitao Zeng, Rui Li, Xiaochun Cao, <br />
**Proceedings of the 31st ACM International Conference on Multimedia 2023 (ACM MM, 2023)**  \| [**Project**](https://dl.acm.org/doi/10.1145/3581783.3612283) \| [Github](https://github.com/lulu1999Wang/Hi-SIGIR)

</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/INTERSPEECH.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Robust Automatic Speech Recognition via WavAugment Guided Phoneme Adversarial Training](https://arxiv.org/abs/2307.12498), <br />
Gege Qi, Yuefeng Chen, Xiaofeng Mao, **Xiaojun Jia**, Ranjie Duan, rong zhang, hui xue,  <br />
**INTERSPEECH 2023**  \| [**Project**](https://arxiv.org/abs/2307.12498) \| [Github](https://github.com/alibaba/easyrobust/tree/main/examples/asr/WAPAT)

</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/ICLR2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Inequality phenomenon in adversarial training, and its unrealized threats](https://openreview.net/forum?id=4t9q35BxGr), <br />
Ranjie Duan, YueFeng Chen, Yao Zhu, **Xiaojun Jia**, Rong Zhang, Hui Xue  <br />
**International Conference on Learning Representations 2023 (ICLR 2023)** \| [**Project**](https://openreview.net/forum?id=4t9q35BxGr) \| [Github](https://github.com/RjDuan/Inequality_Phenomenon_in_AT)

</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/attack_3D.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Generating Transferable 3D Adversarial Point Cloud via Random Perturbation Factorization](https://ojs.aaai.org/index.php/AAAI/article/view/25154), <br />
Bangyan He, Jian Liu, Yiming Li, Siyuan Liang, Jingzhi Li, **Xiaojun Jia(Corresponding Author)**, Xiaochun Cao <br />
**Association for the Advance of Artificial Intelligence 2023 (AAAI 2023)** \| [**Project**](https://ojs.aaai.org/index.php/AAAI/article/view/25154) \| [Github](https://github.com/HeBangYan/PF-Attack)

</div>
</div> 



<div class='paper-box'><div class='paper-box-image'><div><img src='images/GAR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [A Large-scale Multiple-objective Method for Black-box Attack against Object Detection](https://link.springer.com/chapter/10.1007/978-3-031-19772-7_36), <br />
Siyuan Liang, Longkang Li, Yanbo Fan, **Xiaojun Jia**, Jingzhi Li, Baoyuan Wu, and Xiaochun Cao <br />
**European Conference on Computer Vision 2022 (ECCV 2022)** \| [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:roLk4NBRz8UC) \| [Github](https://github.com/LiangSiyuan21/GARSDC)

</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/WV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Watermark Vaccine: Adversarial Attacks to Prevent Watermark Removal](https://link.springer.com/chapter/10.1007/978-3-031-19781-9_1), <br />
  Xinwei Liu, Jian Liu, Yang Bai, Jindong Gu, Tao Chen, **Xiaojun Jia(Corresponding Author)**, Xiaochun Cao <br />
  **European Conference on Computer Vision 2022 (ECCV 2022)** \| [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:ufrVoPGSRksC) \| [Github](https://github.com/jiaxiaojunQAQ/Watermark-Vaccine)

</div>
</div>  


<div class='paper-box'><div class='paper-box-image'><div><img src='images/FGSM_PGI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Prior-Guided Adversarial Initialization for Fast Adversarial Training](https://link.springer.com/chapter/10.1007/978-3-031-19772-7_33), <br />
  **Xiaojun Jia**, Yong Zhang, Xingxing Wei, Baoyuan Wu, Ke Ma, Jue Wang, Xiaochun Cao  <br />
  **European Conference on Computer Vision 2022 (ECCV 2022)** \| [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:WF5omc3nYNoC) \| [Github](https://github.com/jiaxiaojunQAQ/FGSM-PGI)

</div>
</div>  


<div class='paper-box'><div class='paper-box-image'><div><img src='images/FGSM_SDI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Boosting Fast Adversarial Training with Learnable Adversarial Initialization](https://arxiv.org/pdf/2110.05007.pdf), <br />
**Xiaojun Jia**, Yong Zhang, Baoyuan Wu, Jue Wang, Xiaochun Cao <br />
**IEEE Transactions on Image Processing 2022 (TIP 2022)**  \| [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:zYLM7Y9cAGgC) \| [Github](https://github.com/jiaxiaojunQAQ/FGSM-SDI)

</div>
</div>  


<div class='paper-box'><div class='paper-box-image'><div><img src='images/LAS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [LAS-AT: Adversarial Training with Learnable Attack Strategy(Oral)](https://arxiv.org/pdf/2203.06616.pdf), <br />
**Xiaojun Jia**, Yong Zhang, Baoyuan Wu, Ke Ma, Jue Wang,  Xiaochun Cao <br />
**Computer Vision and Pattern Recognition Conference 2022 (CVPR(Oral), 2022)** \| [**Project**](https://arxiv.org/pdf/2203.06616.pdf) \| [Github](https://github.com/jiaxiaojunQAQ/LAS-AT)

</div>
</div>  

<div class='paper-box'><div class='paper-box-image'><div><img src='images/EEF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Defending against Model Stealing via Verifying Embedded External Features](https://arxiv.org/pdf/2112.03476.pdf), <br />
Yiming Li, Linghui Zhu, **Xiaojun Jia**, Yong Jiang, Shu-Tao Xia, Xiaochun Cao <br />
**Association for the Advance of Artificial Intelligence 2021 (AAAI 2021)** \| [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:Y0pCki6q_DkC) \| [Github](https://github.com/jiaxiaojunQAQ/Backdoor-attack-against-speaker-verification)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/advwatermark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- [Adv-watermark: A novel watermark perturbation for adversarial examples](https://dl.acm.org/doi/pdf/10.1145/3394171.3413976),<br />
**Xiaojun Jia**, Xingxing Wei, Xiaochun Cao, Xiaoguang Han <br />
**Proceedings of the 28th ACM International Conference on Multimedia 2020 (ACM MM, 2020)** \| [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:9yKSN-GCB0IC) \| [Github](https://github.com/jiaxiaojunQAQ/Adv-watermark)
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/comdefend.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Comdefend: An efficient image compression model to defend adversarial examples](https://openaccess.thecvf.com/content_CVPR_2019/papers/Jia_ComDefend_An_Efficient_Image_Compression_Model_to_Defend_Adversarial_Examples_CVPR_2019_paper.pdf), <br />
**Xiaojun Jia**, Xingxing Wei, Xiaochun Cao, Hassan Foroosh <br />
**Computer Vision and Pattern Recognition Conference 2019 (CVPR 2019)** \| [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:2osOgNQ5qMEC) \| [Github](https://github.com/jiaxiaojunQAQ/Comdefend)

</div>
</div>









# 🎉 Professional Service 
- *Reviewer or Program Committee*: CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, AAAI, IJCAI, ACM MM, IEEE TPAMI, IEEE TIP, IEEE TIFS, IEEE TDSC
- *Senior Program Committee*: AAAI-26-AIA
- *Associate Editor*: Pattern Recognition

<!--
# 🎉 Preprints
- [Boosting Fast Adversarial Training with Learnable Adversarial Initialization](https://arxiv.org/pdf/2110.05007.pdf), **Xiaojun Jia**, Yong Zhang, Baoyuan Wu, Jue Wang, Xiaochun Cao  \| [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=retTWnEAAAAJ&citation_for_view=retTWnEAAAAJ:zYLM7Y9cAGgC) \| [Github](https://github.com/jiaxiaojunQAQ/FGSM-SDI)-->

# 🎖 Honors and Awards
- *2025.07* [IJCAI 2025 Workshop & Challenge on Deepfake Detection, Localization, and Interpretability, Generative Large Model Security Track](https://tianchi.aliyun.com/competition/entrance/532362), 1st Place.
- *2024.08* [CCDM 2024 Red Teaming Multimodal Large Language Model Security Challenge](https://mp.weixin.qq.com/s/HFGjGQeefuvl73VYk58ecA), 1st Place.
- *2023.12* [NeurIPS 2023 Red Teaming Track - Base Model Subtrack](https://trojandetection.ai/leaderboards), 3rd place.
- *2021.06* [ACM MM2021 Security AI Challenger: Robust Logo Detection](https://s.alibaba.com/challenge/ACMMM2021ChallengeRobustLogoDetection/?spm=5176.12281976.0.0.783430499dGPgZ), 2nd place. 
- *2021.11* [Face security confrontation in OPPO Security Challenge](https://security.oppo.com/challenge/competition-detail.html), 2nd place. 
- *2021* Best Paper of Adversarial for Good Award, ICML AdvML Workshop.

# 🚩 Organization
- *2024* Global Challenge for Safe and Secure LLMs.
- *2024* DataCon2024 Big Data Security Analysis Competition.

# 📖 Educations
- *2023.08 - now* Nanyang Technological University, Research Fellow.
- *2018.06 - 2023.07* School of Cyberspace Security, University of Chinese Academy of Sciences, PhD.  
- *2014.09 - 2018.06*, School of Information Engineering, China University of Geosciences, Bachelor. 

# 💬 Invited Talks

- *2025.04*, [2025 Black Hat Asia - AI Summit](https://www.blackhat.com/asia-25/summit-sessions/schedule/index.html#track/ai-summit), Singapore, Title “LLM Firewalls: Are They the Future of AI Security?”
- *2024.10*, [2024 Patian White Hat Hacker Annual Ceremony](https://whc.butian.net/2024), China, Title “The dual threat of large vision-language models: an in-depth exploration from adversarial to jailbreak attacks”
- *2024.07*, [2024 World Al Conference & High-levelMeeting on Global Al Governance](https://english.shanghai.gov.cn/en-2024waic/index.html), China, Title “An in-depth exploration from machine learning safety to large model safety”

  
<!--
- *2022.11*, Department of Electronic Engineering,Tsinghua University. \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/%E6%B8%85%E5%8D%8E-%E5%AF%B9%E6%8A%97%E8%AE%AD%E7%BB%83%20.pdf)
- *2022.11*, Huawei Shield Lab. \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/%E5%8D%8E%E4%B8%BA-%E5%AF%B9%E6%8A%97%E8%AE%AD%E7%BB%83.pdf)
- *2022.07*, Institute of Information Engineering, University of Chinese Academy of Sciences. \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/%E4%BF%A1%E5%B7%A5%E6%89%80_LAS_AT.pdf)
- *2022.06*, AI Drive. \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/AI_Drive_LAS_AT.pdf)
- *2022.06*, 机器之心synced. \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/%E6%9C%BA%E5%99%A8%E4%B9%8B%E5%BF%83_LAS_AT.pdf)
- *2022.03*, School of Computer Science, China University of Geosciences.  \| [Slide](https://github.com/jiaxiaojunQAQ/jiaxiaojunQAQ.github.io/blob/main/Talking/%E8%AE%A1%E7%AE%97%E6%9C%BA%E9%A1%B6%E4%BC%9A%E6%8A%95%E7%A8%BF%E5%88%86%E4%BA%AB%E4%B8%8E%E4%BA%A4%E6%B5%81.pdf)-->

# 💻 Internships
- *2020.05 - 2022.02*, Research Intern, Tencent AI Lab, Tencent, China.
- *2022.03 - 2023.07*, Research Intern, Ali Group Security, China.


<div style="width: 200px; height: 100px; ">
 <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=lZAcR37iWfG21cUl-pOdK4D6_NnKXlW2av3JfhfpQHg&cl=ffffff&w=a"></script>
</div>





