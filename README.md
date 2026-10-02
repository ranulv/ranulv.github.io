Ranul says Hi! 👋 
===============================

### Doctoral Student - Imperial College London
-----------------------------------------------------------

I am a passionate doctoral researcher with a focus on Human-Robot Interaction (HRI), Child-Robot Interaction (CRI), and Socially Assistive Robotics. My work centers on enhancing the synergy between humans and robots, aiming to create systems that can intuitively understand and respond to human needs and emotions.

* 🌍  I'm based at the PAIR Lab, Imperial College London, UK, supervised by Dr. Nicole Salomons.
* ✉️  You can contact me at [r.thalahitiya-vithanage25@imperial.ac.uk](mailto:r.thalahitiya-vithanage25@imperial.ac.uk)

### Connect with me:

[![website](./img/globe-light.svg)](https://ranul-vithanage.art/#gh-light-mode-only)
[![website](./img/globe-dark.svg)](https://ranul-vithanage.art/#gh-dark-mode-only)
&nbsp;&nbsp;
[![linkedin](./img/linkedin-light.svg)](https://linkedin.com/in/ranul-vithanage#gh-light-mode-only)
[![linkedin](./img/linkedin-dark.svg)](https://linkedin.com/in/ranul-vithanage#gh-dark-mode-only)
&nbsp;&nbsp;
[![github](./img/github-light.svg)](https://github.com/ranulv/#gh-light-mode-only)
[![github](./img/github-dark.svg)](https://github.com/ranulv/#gh-dark-mode-only)


### Languages and Tools

[<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/python/python-original.svg" style="padding-right:10px;" />][github]
[<img align="left" alt="C++" width="26px" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/cplusplus/cplusplus-original.svg" style="padding-right:10px;" />][github]
[<img align="left" alt="MATLAB" width="26px" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/matlab/matlab-original.svg" style="padding-right:10px;" />][github]

[website]: https://ranulv.github.io/
[github]: https://github.com/ranulv/
[linkedin]: https://linkedin.com/in/ranul-vithanage


## Website template credits

This website adapts [Pascal Michaillat's website template](https://github.com/pmichaillat/pmichaillat.github.io/), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see [LICENSE.md](LICENSE.md)). The content, identity, navigation, and assets have been adapted for Ranul Vithanage. The original author's research and teaching materials have been removed.

The site uses Hugo and the [PaperMod theme](https://github.com/adityatelange/hugo-PaperMod/), whose [MIT license and copyright notices](themes/PaperMod/LICENSE.md) are retained.

## Build

Run `hugo --minify --cleanDestinationDir` to rebuild `public/` and remove obsolete generated files. GitHub Pages builds the site through `.github/workflows/hugo.yml`.

## Naming publications

Use a short, descriptive title in lowercase with hyphens for each paper:

- Page source: `content/publications/<paper-name>.md`
- Page URL: `/publications/<paper-name>/`
- PDF source: `static/papers/<paper-name>.pdf`
- PDF link in Markdown: `[Full Paper](/papers/<paper-name>.pdf)`

Keep page aliases when changing existing page URLs. The former numbered paper pages redirect to their descriptive URLs; the numbered PDF files have been renamed, so update any externally shared PDF links.

## Adding photos

Put images in `static/images/` (create the folder as needed). In a project or publication Markdown file, add or update its existing `cover` block in the front matter:

```yaml
cover:
    image: "/images/my-project.jpg"
    alt: "A short description of what the photo shows"
    caption: "Description shown beneath the image"
    relative: false
```

The cover appears on the Projects or Publications listing and at the top of its detail page. For additional photos within the page, use `![Description](/images/another-photo.jpg)` in the Markdown body. Avoid inserting the cover again in the body.

The homepage portrait is controlled by `params.profileMode.imageUrl` in `config.yml`.

## Publication resource buttons

Publication detail pages render buttons from `resources` in the front matter. Keep the abstract in the Markdown body and put the venue/status in `publicationNote`:

```yaml
publicationNote: "Conference Paper — Conference Name, Year"
resources:
  - label: "Read paper"
    url: "/papers/my-paper.pdf"
    kind: pdf
  - label: "Publisher page"
    url: "https://doi.org/YOUR-DOI"
    kind: publisher
```

Omit any resource that is not available. These links appear beneath the title, before the cover photo and abstract.

Cover captions appear beneath photos on detail pages only; listing cards hide captions. Set `cover.caption` to edit the visible description; if omitted, `cover.alt` is shown instead. Keep `alt` descriptive for screen readers.
