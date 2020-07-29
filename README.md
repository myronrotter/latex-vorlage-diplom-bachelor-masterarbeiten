# thesis-template

This LaTeX-template can be used for technical reports, BSc or MSc thesis.
Refer to [./src/thesis-template.pdf](./src/thesis-template.pdf).

# Docker

The environment to create pdf files can be run in a Docker container. For this task, the provided [Dockerfile](./Dockerfile) can be used.

The Docker image can be created with the command `docker build -t maknesium/latexvorlage:latest`. Then, the container can be created with the command `docker run -d --name latexvorlage-container -v /pfad/zum/ordner/src:/app/src maknesium/latexvorlage:latest`. The container is not deleted after it is finished compiling the tex files and can simply be started again to compile the tex files again with the command `docker start latexvorlage-container`.

# License

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Germany License.
http://creativecommons.org/licenses/by-nc-sa/3.0/de/
Check out the original [repo](https://github.com/maknesium/latex-vorlage-diplom-bachelor-masterarbeiten).
