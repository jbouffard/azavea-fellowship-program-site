---
published: true # change to true once ready to post

title: "Cloud detection with neural networks" # project title inside quotes
excerpt: "Apply neural network techniques being researched by Azavea staff to the problem of cloud detection in satellite imagery." # shows on project list page
seo_description: "" # goes in project meta description

# project attributes
requirements: # bullet list of requirements – one requirement per line – follow below format
  - "Familiarity with Keras, TensorFlow and CNN architectures"
tags: # one tag per line – spaces are allowed in tags – use tags other posts use – follow below format
  - "deep learning"
  - "machine learning"
difficulty: "hard" # easy, medium, hard – pick one
mentors: # github username without the @ – example: designmatty
  - "jerheff"
  - "lossyrob"
  - "lewfish"

# This file uses Kramdown. See https://kramdown.gettalong.org/syntax.html for syntax
---

At Azavea, we have been researching the use of convolutional neural networks for image segmentation on aerial imagery (see <https://github.com/azavea/keras-semantic-segmentation>). This project will expand this research to use CNNs, or possibly RNNs over temporal imagery, to classify cloud cover in RGB images.

#### Milestones

##### PREPARATION

- Determine the project roadmap.
- Getting familiar with existing keras image segmentation code

##### CODING PHASE 1

- Modify existing keras image segmentation codebase to train on imagery

##### CODING PHASE 2

- Development and evaluation of NN architectures for identifying clouds in RGB imagery
- Developing a workflow for classifying clouds in imagery based on trained models.

##### CODING PHASE 3

- Documenting and publish results