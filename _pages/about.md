---
layout: home
permalink: /
title: "Linjun Wu"
excerpt: "Personal homepage of Linjun Wu"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<section class="home-hero" aria-label="Profile">
  <div class="home-hero__visual">
    <img class="home-hero__avatar" src="{{ base_path }}/images/{{ site.author.avatar }}" alt="{{ site.author.name }}">
  </div>
  <div class="home-hero__text">
    <h1 class="home-hero__name">{{ site.author.name }}</h1>
    <p class="home-hero__tagline">
      Ph.D. candidate at the State Key Lab of CAD&amp;CG, Zhejiang University, working on character animation and controllable human motion generation.
    </p>
    <div class="home-hero__social" aria-label="Profile links">
      {% if site.author.github %}
        <a class="home-hero__social-link" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
          <i class="fab fa-github" aria-hidden="true"></i>
        </a>
      {% endif %}
      {% if site.author.googlescholar %}
        <a class="home-hero__social-link" href="{{ site.author.googlescholar }}" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar">
          <i class="fas fa-graduation-cap" aria-hidden="true"></i>
        </a>
      {% endif %}
      {% if site.author.orcid %}
        <a class="home-hero__social-link" href="{{ site.author.orcid }}" target="_blank" rel="noopener noreferrer" aria-label="ORCID">
          <i class="ai ai-orcid" aria-hidden="true"></i>
        </a>
      {% endif %}
      {% if site.author.email %}
        <a class="home-hero__social-link" href="mailto:{{ site.author.email }}" aria-label="Email">
          <i class="fas fa-envelope" aria-hidden="true"></i>
        </a>
      {% endif %}
    </div>
  </div>
  <p class="home-hero__updated">Last updated: 2026-05-19</p>
</section>

<section class="home-section" id="welcome">
  <h2 class="home-section__title">Welcome</h2>
  <div class="home-prose">
    <p>
      I am Linjun Wu, a third-year Ph.D. candidate at the State Key Lab of CAD&amp;CG, Zhejiang University, advised by Prof.
      <a href="http://www.cad.zju.edu.cn/home/jin" target="_blank" rel="noopener noreferrer">Xiaogang Jin</a>.
      I received my bachelor’s degree in Artificial Intelligence from Zhejiang University in 2023 and was enrolled in Chu Kochen Honors College.
    </p>
    <p>
      My research focuses on character animation, with particular interests in text-driven human motion generation, motion stylization, motion in-betweening, and real-time animation systems.
    </p>
  </div>
</section>

<section class="home-section" id="research">
  <h2 class="home-section__title">Research</h2>
  <div class="research-grid">
    <article class="research-card">
      <span class="research-card__label">Motion Generation</span>
      <p>Precise keyframe control and semantic guidance for text-to-motion and diffusion-based animation.</p>
    </article>
    <article class="research-card">
      <span class="research-card__label">Motion Stylization</span>
      <p>Semantically consistent motion stylization and fine-grained transfer for expressive character motion.</p>
    </article>
    <article class="research-card">
      <span class="research-card__label">Interactive Animation</span>
      <p>Fast, controllable motion transition and retargeting systems for game and interactive scenarios.</p>
    </article>
  </div>
</section>

<section class="home-section" id="publications">
  <h2 class="home-section__title">
    Selected Publications
    <a class="home-section__view-all" href="{{ base_path }}/publications/">(view all &gt;&gt;)</a>
  </h2>
  <ul class="paper-list">
    <li class="paper-card">
      <div class="paper-card__main">
        <span class="paper-card__venue">CVPR 2026</span>
        <h3 class="paper-card__title">Unifying Precise Keyframes and Semantic Control via Multi-level Diffusion</h3>
        <p class="paper-card__authors">
          <strong>Linjun Wu</strong>, Jiejia Yu, Leyang Jin,
          <a href="http://drhewang.com/" target="_blank" rel="noopener noreferrer">He Wang</a>, Bowen Zheng, Xu Yang, Hao Jiang, Fei Xia, Fei Ling, Jun Deng,
          <a href="http://www.cad.zju.edu.cn/home/jin/" target="_blank" rel="noopener noreferrer">Xiaogang Jin</a>
        </p>
        <div class="paper-card__links" aria-label="Publication links">
          <a class="paper-card__link" href="https://fivezerojun.github.io/UnifyingKeyframesSemantics/" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-external-link-alt" aria-hidden="true"></i>
            <span>Project</span>
          </a>
          <a class="paper-card__link" href="https://fivezerojun.github.io/UnifyingKeyframesSemantics/figures/Poster.png" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-image" aria-hidden="true"></i>
            <span>Poster</span>
          </a>
          <a class="paper-card__link" href="https://www.youtube.com/watch?v=qtKtr4O8TAI" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-youtube" aria-hidden="true"></i>
            <span>Video</span>
          </a>
        </div>
      </div>
      <figure class="paper-card__media">
        <img src="{{ base_path }}/images/cvpr2026.png" alt="Preview for Unifying Precise Keyframes and Semantic Control">
      </figure>
    </li>

    <li class="paper-card">
      <div class="paper-card__main">
        <span class="paper-card__venue">SIGGRAPH 2025</span>
        <h3 class="paper-card__title">Semantically Consistent Text-to-Motion with Unsupervised Styles</h3>
        <p class="paper-card__authors">
          <strong>Linjun Wu</strong>,
          <a href="https://yuyujunjun.github.io/" target="_blank" rel="noopener noreferrer">Xiangjun Tang</a>, Jingyuan Cong,
          <a href="http://drhewang.com/" target="_blank" rel="noopener noreferrer">He Wang</a>, Bo Hu, Xu Gong, Songnan Li, Yuchen Liao,
          <a href="https://onethousandwu.com/" target="_blank" rel="noopener noreferrer">Yiqian Wu</a>, Chen Liu,
          <a href="http://www.cad.zju.edu.cn/home/jin/" target="_blank" rel="noopener noreferrer">Xiaogang Jin</a>
        </p>
        <div class="paper-card__links" aria-label="Publication links">
          <a class="paper-card__link" href="https://dl.acm.org/doi/10.1145/3721238.3730641" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-file-alt" aria-hidden="true"></i>
            <span>Paper</span>
          </a>
          <a class="paper-card__link" href="https://fivezerojun.github.io/stylization.github.io/" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-external-link-alt" aria-hidden="true"></i>
            <span>Project</span>
          </a>
          <a class="paper-card__link" href="https://github.com/fivezerojun/Semantically-Consistent-Text-to-Motion-with-Unsupervised-Styles" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-github" aria-hidden="true"></i>
            <span>Code</span>
          </a>
          <a class="paper-card__link" href="https://www.youtube.com/watch?v=ZYCjhcN-T5s" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-youtube" aria-hidden="true"></i>
            <span>Video</span>
          </a>
        </div>
      </div>
      <figure class="paper-card__media">
        <img src="{{ base_path }}/images/stylization.jpg" alt="Preview for Semantically Consistent Text-to-Motion with Unsupervised Styles">
      </figure>
    </li>
  </ul>
</section>

<section class="home-section" id="contact">
  <h2 class="home-section__title">Contact</h2>
  <div class="contact-panel">
    <p>
      Address: Zijingang Campus of Zhejiang University, 866 Yuhangtang Rd, Hangzhou, China.<br>
      Email: <a href="mailto:12321232@zju.edu.cn">12321232@zju.edu.cn</a>; <a href="mailto:woollen9@163.com">woollen9@163.com</a>
    </p>
    <div class="contact-links">
      {% if site.author.github %}
        <a class="contact-link" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-github" aria-hidden="true"></i>
          <span>GitHub</span>
        </a>
      {% endif %}
      {% if site.author.googlescholar %}
        <a class="contact-link" href="{{ site.author.googlescholar }}" target="_blank" rel="noopener noreferrer">
          <i class="fas fa-graduation-cap" aria-hidden="true"></i>
          <span>Scholar</span>
        </a>
      {% endif %}
      {% if site.author.email %}
        <a class="contact-link" href="mailto:{{ site.author.email }}">
          <i class="fas fa-envelope" aria-hidden="true"></i>
          <span>Email</span>
        </a>
      {% endif %}
    </div>
  </div>
</section>
