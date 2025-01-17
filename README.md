# [atet](https://github.com/atet) / [**_csv_**](https://github.com/atet/csv/blob/main/README.md#atet--csv)

[![.img/logo_csv.png](.img/logo_csv.png)](#nolink)

This reference will show R and Python code to read, view, manipulate, transform, and save out comma-separated value (CSV) files. More advanced tabular file formats such as Excel Workbooks will not be covered here.

----------------------------------------------------------------------------

## Table of Contents

* [0. Requirements](#0-requirements)
* [1. Introduction](#1-introduction)
* [2. Installation](#2-installation)
* [3. Basic Examples](#3-basic-examples)
* [4. Next Steps](#4-next-steps)

### Supplemental

* [Other Resources](#other-resources)
* [Troubleshooting](#troubleshooting)

----------------------------------------------------------------------------

## 0. Requirements

Only [R](https://www.r-project.org/about.html) and Python will be used in this reference. To quickly deploy either (or both, if you're adventurous!) of these programming languages and their development environments, I would suggest leveraging Docker.

Instructions to install Docker for Windows 10/11 can be found here: [https://github.com/atet/wsl](https://github.com/atet/wsl?tab=readme-ov-file#4-cli-docker)

After Docker is installed on your computer, click to expand the steps below to easily download and create the development environments:

<details>
<summary><a>R and RStudio</a></summary>

</br>

In your WSL terminal, download the `rocker/rstudio`<sup>1</sup> Docker image (~700 MB) and start the container:

```bash
$ docker pull rocker/rstudio:4.4.2
$ docker run -dit -p 8787:8787 --name rstudio -e PASSWORD=rstudio rocker/rstudio:4.4.2
```

In a web browser, visit http://localhost:8787 and log into RStudio using the username `rstudio` and password `rstudio`.

</details>
<details>
<summary><a>Python and Jupyter Notebook</a></summary>

</br>

In your WSL terminal, download the `jupyter/minimal-notebook`<sup>2</sup> Docker image (~450 MB) and start the container:

```bash
$ docker pull jupyter/minimal-notebook:x86_64-ubuntu-22.04
$ docker run -dit -p 8888:8888 --name jupyter -e JUPYTER_TOKEN=jupyter jupyter/minimal-notebook:x86_64-ubuntu-22.04
```

In a web browser, visit http://localhost:8888 and log into Jupyter using the token `jupyter`.

</details>

</br>

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 1. Introduction

INTRODUCTION.

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 2. Installation

INSTALLATION.

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 3. Basic Examples

BASIC EXAMPLES.

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 4. Next Steps

NEXT STEPS.

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Other Resources

**Description** | **URL Link**
--- | ---
null | null

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Troubleshooting

Issue | Solution
--- | ---
**"It's not working!"** | This concise tutorial has distilled hours of sweat, tears, and troubleshooting; _it can't not work_

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## References

Citation | Description | Docker Hub Link
--- | --- | ---
**1** | R and RStudio Server Docker image from [Rocker Project](https://rocker-project.org/) | https://hub.docker.com/r/rocker/rstudio
**2** | Python and Jupyter Labs Docker image from [Jupyter Project](https://jupyter.org/) | https://hub.docker.com/r/jupyter/minimal-notebook

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

<p align="center">Copyright © 2025-∞ Athit Kao, <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a></p>