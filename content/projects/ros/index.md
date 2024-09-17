---
title: Design of mobile robots for visually impaired people based on semantic information

event: Student Research Training Program (SRTP)
# event_url: https://example.org

# location: Hugo Blox Builder HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: By using semantic correlation between objects to guide the robot to help visually impaired people to find items

abstract: In order to address the challenge faced by visually impaired people in finding objects, we have designed a guide robot for the visually impaired that is driven by target semantic information. First, we utilized Mask R-CNN and skip-gram to obtain a semantic correlation model, which is used to analyze the association of common indoor objects. Then, with the aforementioned model and the ROS framework, we designed a strategy that continuously seeks objects with stronger semantic correlations, enabling the robot to efficiently locate the given target. Finally, by integrating the classic ORB-SLAM2 system method, we helped the robot construct a highly usable environmental map and find a navigable path while moving. Simulation results have verified that the proposed strategy can effectively assist the robot in navigating to the target without human intervention. Moreover, this strategy has been deployed on a turtlebot3 robot.Responsible for ROS robot object detection and motion decision deployment, program optimization, and communication between server and robot under Ubuntu system.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-09-01T13:00:00Z'
date_end: '2021-08-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2021-08-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - []
---
<!-- 
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
