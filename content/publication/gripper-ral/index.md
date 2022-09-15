---
title: 'Dynamic control of a rigid pneumatic gripper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rocco Antonio Romeo
  - Luca Fiorio
  - Giuseppe L’Erario
  - Marco Maggiali
  - Giorgio Metta
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Robotics and Automation Letters
# publication_short: In *RAL*

abstract: Pneumatic grippers are hugely employed in robotic applications. Nonetheless, their control is not easy due to difficulty in managing the pressure inside their air chambers. Pneumatic grippers have often simple structure though the lack of affordable control algorithms complicates their usage. Motivated by these reasons, we wish to deliver a new control architecture for the closed-loop control of pneumatic grippers actuated by pressure regulators. The proposed architecture is composed of a main controller resorting to an optimization algorithm and of a state observer that estimates pressures in both gripper chambers, along with the exerted force. Instead, measured quantities (i.e. physical pressure in the gripper chambers and force recorded by a load cell between the gripper fingers) are used as inputs for the state observer to improve its output. The pneumatic gripper performance benefits from the joint action of the controller and of the state observer, as experimentally demonstrated. The gripper response will be shown for different types of inputs and on different setups.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/iel7/7083369/8932682/09000722.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
