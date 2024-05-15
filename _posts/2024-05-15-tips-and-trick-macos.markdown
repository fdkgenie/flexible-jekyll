---
layout: post
title: Một số mẹo hay sử dụng MacOS
date: 2024-05-15 13:32:20 +0300
description: Bài viết gom nhặt tạm một số mẹo và thủ thuật khi làm việc trên MacOS, sẽ được bổ cập dần dần theo thời gian :) # Add post description (optional)
img: macos-tips-tricks.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Tips, Tricks]
---

## Cài đặt PATH
### Với shell mặc định zshrc: mở file .zshrc trong thư mục làm việc gốc ($HOME)
* Chạy lệnh: 
    >   nano $HOME/.zshrc
* Thêm các dòng lệnh export:
    >   export CPATH=/opt/homebrew/include

    >   export LIBRARY_PATH=/opt/homebrew/lib

    >   export PATH=$PATH:$HOME/LMGC/rockable-folked/INSTALL

* Tạo alias:
        alias rrun="rockable"

        alias rsee="see"

        alias rclean="rrun -c"

        alias rcleana="rclean && rm *.tga"

        alias rrock="rrun input.txt && rsee"

### Với shell khác...

## Cài đặt package với homebrew

## ...


