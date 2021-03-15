---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Deformation Recovery Control and Post-impact Trajectory Replanning for Collision-resilient Mobile Robots "
authors:
- Z. Lu
- admin
- K. Karydis 
date: 2021-10-13T23:10:03-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-14T23:10:03-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "Under Review"

abstract: "The paper focuses on collision-inclusive motion planning
for impact-resilient mobile robots. We propose a new
deformation recovery and replanning strategy to handle
collisions that may occur at run-time. Contrary to
collision avoidance methods that generate trajectories only
in conservative local space or require collision checking
that has high computational cost, our method directly
generates (local) trajectories with imposing only waypoint
constraints. If a collision occurs, our method then
estimates the post-impact state and computes from there an
intermediate waypoint to recover from the collision. To
achieve so, we develop two novel components: 1) a
deformation recovery controller that optimizes the robot's
states during post-impact recovery phase, and 2) a
post-impact trajectory replanner that adjusts the next
waypoint with the information from the collision for the
robot to pass through and generates a polynomial-based
minimum effort trajectory. The proposed strategy is
evaluated experimentally with an omni-directional
impact-resilient wheeled robot. The robot is designed in
house, and it can perceive collisions with the aid of Hall
effect sensors embodied between the robot's main chassis
and a surrounding deflection ring-like structure. "

# Summary. An optional shortened abstract.
summary: ""

tags: 
- Motion and Path Planning
- Wheeled Robots 
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
