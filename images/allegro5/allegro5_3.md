---
title: Allegro5_3 窗口
date: 2019-05-26T08:45:33+08:00
lastmod: 2019-05-26T08:45:33+08:00
author: 蓝小狼
#cover: /img/cover.jpg
categories: ["allegro5"]
tags: ["allegro5"]
#draft: true
---

# Allegro5窗口显示

<!--more-->
# 1.需要的头文件

Allegro5的核心头文件 `include <allegro5/allegro.h>` 这里面包含了图形库的基本功能，
只有包含了该头文件，才能使用allegro5图形库。

完整的代码示例：

```cpp
include <stdio.h>
include <allegro5/allegro.h>

int main(int argc,char **argv)
{
  return 0;
}
```

这里我们使用`main(int argc,char **argv)`的原因是，防止图形库中的重新声明了主函数。    
一般建议这样写，在SDL2图形库中就要必须这样写，在这里最好是统一一下，以后的代码示例同样如此。



