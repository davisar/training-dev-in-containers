# 🚧 This content is incomplete and currently under development. 🚧

# Isolating your Development Inside of Containers
All about how to keep development dependencies isolated and off of your main machine!

Bonus: Project development requirements in code.

# Why
**tl;dr: I want isolated, easy to start development environments.**

Frankly, it's always annoyed me a bit when I join a new project and have to go through some sort of "onboarding" document in order to get my development environment properly configured. 

Worse yet is that noone seems to have a "clean" development environment - If by sheer dumb luck we all have similar toolsets installed there's probably some SDK that's actually a _requirement_ that noone has realized. The first time you need to actually do something you'll inevitably hear "Huh...It works on my machine. I don't know what could be different..." 🙄

For example (note the snark in parentheses):
```
1. Install VSCode or other editor of choice. 
    (But we all use VsCode so noone is going to help if you pick up something else)
2. Install .Net Version 3.7.2 
    (which you'll quickly find isn't actually the case because the docs are out of date)
3. Install some other random SDKs
4. Build the code 
    (It'll probably fail because some dependency noone has realized or understood)

(oh - and noone has mentioned that there's these three formatters or misc
editor plugins that are _super_ helpful for development and your life will
be pain and suffering until you install them)
```

# How to Navigate the Training Content
Start with the slides. These are hosted (or will be soon) via github pages.

As you start the training content you may want to create your own branch to work from and save your progress.

## Slides - Main Branch
Slides are hosted on the main branch if you want to view the source. I recommend the github pages view, since it'll be easier to walk through.
The slides are intended to walk you through step by step, but ultimately this is an interactive training so you will want to be prepared to clone this repository and be comfortable switching between branches using git.

## Training Checkpoints - Other Branches
Training Checkpoints are intended to give you certain "known good" points to work from if either you get lost, need to find a reset point, or otherwise want to jump around to see the code state at a particular point.
Training checkpoints can be identified by the other (non-"main") branches under the Checkpoints/ structure. For example: Checkpoints/01-FirstDevContainer would be identified in the slides at the appropriate point and represents a particular checkpoint in the training.
In some cases the training may instruct you to specifically switch branches to a checkpoint branch to help you get started or demonstrate a concept in isolation.
