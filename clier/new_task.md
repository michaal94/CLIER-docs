---
layout: default
title: New tasks
parent: CLIER
nav_order: 5
---

Adding new tasks to CLIER is simple. In order to do that you have to create your instructions with structuring the ground truth program to include your new subgoals.

E.g. when creating task that requires measuring the stiffness of the material, you have to add something like `measure_stiffness` to the program (see template in [Intruction generation](/CLIER-docs/clier/instruction_gen.html)).

Further, to enable automatic ground truth generation, you can modify ActionPlanner class to respond to new programs.