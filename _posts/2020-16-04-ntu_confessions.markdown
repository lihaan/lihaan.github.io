---
# Configuration
layout: post
permalink: post/visualising_ntu_confessions_data # generate random number?

# Content
title: Visualising NTU Confessions Data
date: 2021-04-16 13:59:10 +0800
post-type: Project
author: Li Han
description: A dive into classifying the user-submitted's confession posts found on the NTU Confessions website
categories: [Data Science, Machine Learning]
# TODO: just provide the link to the article
rel-article-1: {title: My GovTech internship experience, url: "https://google.com"}
rel-article-2: {title: From 50 to 75 words per minute, url: "" }
rel-article-3: {title: News Media Lab, url: "" }

---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse accumsan mauris lectus, eget ornare lectus bibendum id. Suspendisse aliquet massa vitae luctus maximus. Nam vel ipsum ac mauris commodo porta id sed ligula. Vestibulum sodales augue scelerisque quam euismod accumsan vel vel tellus. Sed eu quam lobortis, ultrices magna ultrices, tempus elit. Donec auctor id eros id dapibus. Sed facilisis dignissim sodales. Fusce vel elit massa. Etiam pharetra tellus arcu. Cras vestibulum fringilla lectus vitae mattis.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse accumsan mauris lectus, eget ornare lectus bibendum id. Suspendisse aliquet massa vitae luctus maximus. Nam vel ipsum ac mauris commodo porta id sed ligula.

Vestibulum sodales augue scelerisque quam euismod accumsan vel vel tellus. Sed eu quam lobortis, ultrices magna ultrices, tempus elit. Donec auctor id eros id dapibus. Sed facilisis dignissim sodales. Fusce vel elit massa. Etiam pharetra tellus arcu. Cras vestibulum fringilla lectus vitae mattis.

![Drag Racing](/assets/Group2.png){:class="float-left"}
Screengrab from NUS Confessions

```
# for each empty tile, find out which 4 directions are available to move
def check_directions(y, x):
    move_list = []
    if y+1 < height:
        if map_original[y+1][x] == 0:
            move_list.append((y+1, x))
    if x+1 < width:
        if map_original[y][x+1] == 0:
            move_list.append((y, x+1))
    if y-1 >= 0:
        if map_original[y-1][x] == 0:
            move_list.append((y-1, x))
    if x-1 >= 0:
        if map_original[y][x-1] == 0:
            move_list.append((y, x-1))
    
    if len(move_list) > 2:
        split_tiles.add((y,x))
    return move_list # [(y1,x1),(y2,x2),(y3,x3)]
```

Donec sed congue massa. Donec facilisis sed magna ac faucibus. Phasellus scelerisque nec tellus sit amet feugiat. Fusce ornare vel tellus in facilisis. Mauris placerat sed lacus quis tincidunt. Maecenas vehicula, quam eget dapibus ultricies, urna eros vehicula felis, eu euismod mi erat a tellus. Ut condimentum efficitur magna, quis scelerisque nunc. Sed auctor felis ac felis eleifend auctor ut eleifend erat.

Etiam lobortis metus sapien, ut ullamcorper arcu rutrum sed. Integer vel diam vel ex consectetur iaculis sed id dolor. Nam cursus erat nec risus hen.