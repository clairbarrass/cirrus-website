# Cirrus Website

Cirrus is EPCC's Tier-2 High Performance Computing (HPC) cluster.

This repository contains the website for the service available at:
<http://www.cirrus.ac.uk>

## How to Contribute

To contribute to this website, first you have to fork it on GitHub and
clone it to your machine, see [Fork a Repo](https://help.github.com/articles/fork-a-repo/) for the GitHub
documentation on this process.

Once you have made your changes and updated your Fork on GitHub you will
need to [Open a Pull Request](https://help.github.com/articles/using-pull-requests/).

## Building the website locally

You do not need to be able to build the website locally to make changes but it can
be useful to see what effect your changes have before opening a Pull Request.

If you wish to build the website locally, then you should install Jekyll:

- <https://jekyllrb.com/>

Once Jekyll is installed, you can test the website with:

```
make serve
```

This will run a temporary webserver from which you can view the updated website locally.
