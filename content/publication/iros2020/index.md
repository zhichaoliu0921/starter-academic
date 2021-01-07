---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Motion Planning for Collision-resilient Mobile Robots in Obstacle-cluttered Unknown Environments with Risk Reward Trade-offs"
authors: 
- Z. Lu
- admin
- K. Karydis
date: 2020-10-30T22:15:32-08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-04T22:15:32-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE/RSJ International Conference on Intelligent Robots and Systems"
publication_short: "IROS (In press)"

abstract: "Collision avoidance in unknown obstacle-cluttered environments may not always be feasible. In this work we focus on an emerging paradigm shift in which potential collisions with the environment can be harnessed instead of being avoided altogether. To this end, we introduced a new sampling-based online planning algorithm that can explicitly handle the risk of colliding with the environment and can switch between collision avoidance and collision exploitation. Central to the planner's capabilities is a novel joint optimization function that evaluates the effect of possible collisions using a reflection model. This way, the planner can make deliberate decisions to collide with the environment if such collision is expected to help the robot make progress toward its goal. To make the algorithm online, we presented a state expansion pruning technique that significantly reduces the search space while ensuring completeness. The proposed algorithm was evaluated experimentally with a built-in-house holonomic wheeled robot that can withstand collisions. We performed an extensive parametric study to investigate trade-offs between (user-tuned) levels of risk, deliberate collision decision making, and trajectory statistics such as time to reach the goal and path length."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: arXiv
   url: https://arxiv.org/abs/2009.01973
   icon_pack: 
   icon: 

url_pdf: media/iros2020.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: 
url_video: https://youtu.be/S3oYebJRfA0

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
