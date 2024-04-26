---
layout: splash
classes: wide
title: RealCycle
permalink: /realcycle/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /_pages/projects/realcycle/realcycleHeader.jpg
---
## Demo video
<iframe width="1452" height="541" src="https://www.youtube.com/embed/hHX-DubwpzA" title="RealCycle Final Promotion Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Foreword
- My first Year Long project in ISDN Major
- I am the leader of a team of 5 passionate students
- We practiced Design thinking process and product prototyping process

## Project Details
### Problem
- We discover that in Hong Kong when you throw 100 plastic bottles into recycle bin, only 4 of them is actually recycled
- We interviewed different industry leaders to get more insights
- We found 3 mean causes
    - It is expensive to process plastic - Multiple types of plastic requiring different processing plant to properly recycle. Too expensive to filter out other types of plastic and then send to another processing plant.
    - High transportation cost - The bottles are not compressed when they are being transported, leading to the truck transporting mostly air, instead of plastic. Plastic per truck is too low
    - Contamination - Small contaminents like water or coke will ruin the entire batch of plastic bottles
- We asked "Why not install compressors in recycle bin? It will increase the 'Plastic bottle per truck ratio'."
    - Ans: If we compress the bottle, and it has liquid inside, it ruins the entire batch of plastic and also cuase hygene problems.

### Solution
- We went through the ideation process iteratively to arrive in the final solution
- A smart recycle bin consist of 3 main component to solve the problems
- Components
    - Computer vision system (CV)
        - Computer vision (CV) system that identifies contaminants inside bottles and would reject the bottle if they are detected
        - The CV system combines with weight sensor to estimate the expected weight of the bottle
        - If the actual weight exceeds the expected weight, we reject the bottle
        - This systems works for non-transparent bottles

<video autoplay muted loop style="max-width: 450px">
    <source src="/_pages/projects/realcycle/CV Camera view.mp4" type="video/mp4">
</video>
<br>

- NIR spectrometer
    - We use NIR spectrometer to identify the type of plastic
    - We sort the plastic at the source, so that there is not "Second stage transportation"
    - ![Alt text](_pages/projects/realcycle/NIR_spectrometer.png)
- Mechanical Compressor
    - We compressor that shrinks the volume of bottles after it is identified to be clean
    - Due to safety concerns, we did not implement it in the lab prototype

### Computer Vision System
- I was in charge of developing the computer vision system
- I have built my own dataset of 5000+ images
- Built and trained my own model using Tensorflow and Keras
- The following is a snippet of my technical research report
![](/_pages/projects/realcycle/screencapture-hkust-isdworks-about-3-2024-04-26-23_02_20.png)
