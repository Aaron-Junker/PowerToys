# **Priview pane - Adding previews with monaco**

<img align="right" src="./images/Logo.png" />

- **What is it:** Implementing [#1527](https://github.com/microsoft/PowerToys/issues/1527)
- **Authors:** Aaron Junker ([@aaron-junker](https://github.com/aaron-junker)), Clint Rutkas ([@crutkas](https://github.com/crutkas))
- **Spec Status:** In progress

# 1 Overview

Creating a new preview handler for all Developer files. For this we use [Microsoft Monaco editor](https://github.com/microsoft/monaco-editor). 

## 1.1 Technical implemention 



## 1.2 Why?

Many people asking us for supporting new file types in the preview panes. With implementing this we will support many developer files (for Example .py, .php,.cs, and many more).

### 1.2.1 Why Monaco?

* Monaco supports many different language styles. 
* It supports dark mode
* Clickable links
* Monaco has also the MIT-license

# 2 What does this implement

If we implement this we could close the issues:

* [#1527](https://github.com/microsoft/PowerToys/issues/1527)
* [#1841](https://github.com/microsoft/PowerToys/issues/1841)
 
# 3 Goals and non-goals
## 3.1 Goals
 
* Create working implementation of Monaco in the preview pane
* Support many languages
 
## 3.2 Non-goals

* Replacing existing previewpanes (like .txt)
* Publishing a crashing system

# 4 Stages of developing
|Stage|Expetation|
|---|---|
|1|Developing the main feature|
<!-- in work by Aaron -->
