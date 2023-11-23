---
layout: post
title: "C++: Thread Safe Initialization Requirements"
comments: false
tags: gist c++
---

Did you know... standard C++ has since C++11 required that block-scope variables with static or thread storage duration get initialized in a thread safe way.
Seems this comes up enough when I'm discussing C++ with others, that I decided to put together [a GitHub Gist](https://gist.github.com/louis-langholtz/3c08fbf10d6923db912689bb87812d58) with references to the standard by version on this.

