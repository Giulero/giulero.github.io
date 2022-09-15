---
title: 'Online non-linear centroidal MPC for humanoid robot locomotion with step adjustment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Romualdi Giulio
  - Stefano Dafarra
  - Giuseppe L’Erario
  - Ines Sorrentino
  - Silvio Traversaro
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  International Conference on Robotics and Automation
# publication_short: In *ICRA*

abstract: This paper presents a Non-Linear Model Predictive Controller for humanoid robot locomotion with online step adjustment capabilities. The proposed controller considers the Centroidal Dynamics of the system to compute the desired contact forces and torques and contact locations. Differently from bipedal walking architectures based on simplified models, the presented approach considers the reduced centroidal model, thus allowing the robot to perform highly dynamic movements while keeping the control problem still treatable online. We show that the proposed controller can automatically adjust the contact location both in single and double support phases. The overall approach is then tested with a simulation of one-leg and two-leg systems performing jumping and running tasks, respectively. We finally validate the proposed controller on the position-controlled Humanoid Robot iCub. Results show that the proposed strategy prevents the robot from falling while walking and pushed with external forces up to 40 Newton for 1 second applied at the robot arm.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/iel7/9811522/9811357/09811670.pdf'
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
projects:
  - example

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
