- [Home](./index.md)
- [Installation](./install.md)
- [Guide](./use.md)
- [About](./about.md)

## Installation 

Download the Zip-File from this Shiny App and set your working direction to this path and run:

```bash
# Test if shiny is installed:
if("shiny" %in% rownames(installed.packages())){
  library(shiny)} else{
  install.packages("shiny")}
```

```bash
library(shiny)
runApp("app.R")
```
Or use the function ```runGitHub()``` from the package *shiny*:

```bash
library(shiny)
runGitHub("MRI_Analysis", "SandraKla")
```

All required [packages](./about.md) must be downloaded before starting this app. 