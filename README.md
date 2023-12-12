# mipcvs-wiki
[![pages-build-deployment](https://github.com/WCRP-CMIP/mipcvs-wiki/actions/workflows/pages/pages-build-deployment/badge.svg?branch=production)](https://github.com/WCRP-CMIP/mipcvs-wiki/actions/workflows/pages/pages-build-deployment)
[![MkDocs Build + Deploy](https://github.com/WCRP-CMIP/mipcvs-wiki/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/WCRP-CMIP/mipcvs-wiki/actions/workflows/deploy.yml)


Contents for the MIPCVs wiki. See [wiki.mipcvs.dev](https://wiki.mipcvs.dev/)
---


## Editing the documentation.
Docmentation is found in the `docs` folder with the file names and hierarchy affecting the navigational menu. 

### Editing materials. 

#### menu/page name is determined by the `#` header tag at the top of a file. 

#### Demo files and structure: 
https://github.com/selfhostedshow/wiki/tree/master

#### Permissable items
https://squidfunk.github.io/mkdocs-material/reference/admonitions/




## developer notes
The following are Notes and will be tidied away in due course. 

https://squidfunk.github.io/mkdocs-material/getting-started/



### install
docker pull squidfunk/mkdocs-material

### creating a site. Dont run.
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .

### preview 
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

### build 

docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build
