---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Caution from '../../components/Caution.astro
title: Getting started
order: 1
description: Create a basic hello world kernel
---

In this post, we'll get up and running with a simple kernel that just prints "Hello, World!" to the screen

To start, you'll need the following software installed:
- [Zig](https://ziglang.org)
- [Gyro](https://github.com/mattnite/gyro)
- [QEMU](https://www.qemu.org)
- [Xorriso](https://www.gnu.org/software/xorriso/)
- [Git](https://git-scm.com)

<Caution>
It's strongly encouraged to use Linux to develop an OS. if you don't, you'll likely run into problems down the road.
</Caution>