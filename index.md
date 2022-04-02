---
title: Switch CFW Tutorial GitBook (CFW 튜토리얼 깃북)
layout: home
---

---

![atmosphere.png](assets/images/index/480418a92aaf116ecc55c59f04e763ace5c065b7.png)

### 😊 Nintendo Switch Custom firmware 설치 가이드 튜토리얼에 오신것을 환영합니다.

<br>한국 상황에 맞추어 친절하게 소개된 내용이 많지 않아 어려움이 많았던, 순정 아트모 스피어로의 설치에 어려움을 겪는 사용자를 위해 제작된 깃북 스타일의 튜토리얼입니다.

> 본 튜토리얼을 통해 스위치 **Custom firmware(커스텀 펌웨어)**인 [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) 를 설치하고, 필수 프론트 엔드인 [Hekate](https://github.com/CTCaer/hekate) 를 구성하는 과정으로 진행됩니다.
>
> 하드웨어 취약점을 가진 구형 스위치를 기준으로 **Nintendo Switch(닌텐도 스위치)**에서 홈브류 및 사용자 정의 펌웨어를 얻는 데 필요한 모든 단계를 안내합니다.

<br>

## Why Jekyll with GitBook

GitBook is an amazing frontend style to present and organize contents (such as book chapters
and blogs) on Web. The typical to deploy GitBook at [Github Pages][1]
is building HTML files locally and then push to Github repository, usually to the `gh-pages`
branch. It's quite annoying to repeat such workload and make it hard for people do version
control via git for when there are generated HTML files to be staged in and out.

This theme takes style definition out of generated GitBook site and provided the template
for Jekyll to rendering markdown documents to HTML, thus the whole site can be deployed
to [Github Pages][1] without generating and uploading HTML bundle every time when there are
changes to the original repo.

## How to Get Started

This theme can be used just as other [Jekyll themes][1].

[Fork][3] this repository and add your markdown posts to the `_posts` folder.

### Deploy Locally with Jekyll Serve

This theme can be ran locally using Ruby and Gemfiles.

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) - GitHub

## Full-text search

The search functionality in jekyll-gitbook theme is powered by the [gitbook-plugin-search-pro][5] plugin and is enabled by default.

[https://sighingnow.github.io/jekyll-gitbook/?q=generated](https://sighingnow.github.io/jekyll-gitbook/?q=generated)

## Code highlight

The code highlight style is configurable the following entry in `_config.yaml`:

```yaml
syntax_highlighter_style: colorful
```

The default code highlight style is `colorful`, the full supported styles can be found from [the rouge repository][6]. Customized
style can be added to [./gitbook/rouge/](./gitbook/rouge/).

## How to generate TOC

The jekyll-gitbook theme leverages [jekyll-toc][4] to generate the _Contents_ for the page.
The TOC feature is not enabled by default. To use the TOC feature, modify the TOC
configuration in `_config.yml`:

```yaml
toc:
  enabled: true
  h_min: 1
  h_max: 3
```

## Jekyll with GitBook

Live demo on Github Pages: [Jekyll Gitbook](https://sighingnow.github.io/jekyll-gitbook)

[![Jekyll Themes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com/jekyll-gitbook/)

본 튜토리얼은 위 지킬 깃북 테마를 이용해 작성했습니다.

## License

> 이 튜토리얼은 Creative Commons Attribution-ShareAlike 4.0 International 저작권을 준수합니다. 라이센스 전문은 [https://creativecommons.org/licenses/by-sa/4.0](https://creativecommons.org/licenses/by-sa/4.0/) 에서 확인하세요.
