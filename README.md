# R + julia + Python + Jupyterlab


![imag](screen.png)

[JupyterLab](https://jupyter.org/) es flexible, permite trabajar con una amplia gama de flujos de trabajo en ciencia de datos. [R](https://www.r-project.org/), [Julia](https://julialang.org/) se integran perfectamente.

## Instalación

> Lo siguiente es para distribuciones basadas en Arch, se probo en Manjaro, el proceminto es similar para distribuciones basadas en debian como ubuntu.

* JupyterLab

> pip install jupyterlab

* R  

> sudo pacman -S r tk

> sudo pacman -S zeromq curl openssl

> sudo -i R

> install.packages(c('repr', 'IRdisplay', 'IRkernel'), type = 'source')

> IRkernel::installspec()

> IRkernel::installspec(user = FALSE)

* Julia

> sudo pacman -S julia

> sudo pacman -S mbedtls

> julia

> using Pkg

> Pkg.add("IJulia")


## Uso

> jupyter lab
