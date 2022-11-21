# Resolve-Ables: Visualize AI Nose Classifications With Light Painting

[<img src="https://i.ytimg.com/an_webp/t5ct2JIEhFU/mqdefault_6s.webp?du=3000&sqp=COO67ZsG&rs=AOn4CLBCbyeb5ULtO-WIHASQz8lvsRB3LQ" width="100%">](https://www.youtube.com/watch?v=t5ct2JIEhFU)


This repo contains all the files, code, designs, and materials to replicate this project. If I'm missing anything please let me know!

## Introduction

Inspired by [Benjamin Cabé's Artificial Nose Project](https://blog.benjamin-cabe.com/2021/08/03/how-i-built-a-connected-artificial-nose/amp) & [Shawn Hymel's Sensor Fusion AI Nose Project](https://www.digikey.com/en/maker/projects/how-to-make-an-ai-powered-artificial-nose/3fcf88a89efa47a1b231c5ad209771), I wanted to create a system where two phenomena (smell and ML classification) could be visualized. My approach is through light painting, where the TFT screen on the Seeed Studio's Wio Terminal is photographed using long exposure to visualize the smells the AI nose detects and its confidence in the classification. The way it's currently programmed the color changes based on the scent recognized, and the circle on the TFT gets bigger or smaller based on the model’s confidence in its classification (more confident = larger circle), but this can be reprogrammed to any mapping you like. For the video above, blue is cologne, and white is ambient room smell.

In this GitHub Wiki, you'll learn how to fabricate and program your own AI nose light painting wearable! With the device, you can train it to detect different scents and customize the output to create various artistic representations of smell and ML.

If you have any questions, want to keep up with my work, or toss around ideas, please do so on my Twitter: @[4Eyes6Senses](https://twitter.com/4Eyes6Senses). Thanks!

## Repository contents

* 🧰 [Bill of materials](./bom/README.md) ;
* 💻 [Code](./code) ;
* 🖨️ [Enclosure files](./enclosure_STLs/README.md).
