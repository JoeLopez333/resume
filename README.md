## Resume Preview
Download the .pdf ![here](out/resume-latest.pdf)
![Resume](out/resume-latest.png)

## Repo overview
This resume is built in ![LaTeX](https://www.latex-project.org/) and compiled and released using github workflows. To see the latest source code, visit the ![main branch](https://github.com/JoeLopez333/resume/tree/main). \n

Based on !(https://github.com/zachscrivena/simple-resume-cv)[https://github.com/zachscrivena/simple-resume-cv]

## Local compilation
To compile, checkout the main branch and use 
```
latexmk -xelatex -pvc "resume.tex"
```

## Github actions
Github actions will automatically update the release branch with the latest generated pdf and png files when changes are pushed to main, see [ci_build.yml](https://github.com/JoeLopez333/resume/blob/main/.github/workflows/ci_build.yml)
