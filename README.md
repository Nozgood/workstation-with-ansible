# Workstation with Ansible

L'objectif de ce projet est de permettre le bootstrap d'un poste de dev grace au mecanisme de **ansible-pull**
Ce projet s'inscrit dans un contexte professionnel (LBaaS) mais ajoute egalement des outils que j'utilise personnellement (neovim, lazygit, tmux ...)

Pour l'instant ce repo n'a vocation a s'executer que sur un environnement Linux et + precisement Ubuntu 24.04

## Pre-requis

Sur son poste ou sa VM, avoir:
- ubuntu 24.04 (pas teste sur d'autres versions et/ou OS)
- git
- python 3.14
- ansible 2.21.0
- la possibilite de clone ce repo soit en ssh soit en https (preferer le ssh si possible)

Note: les versions des outils sont figes car le projet a ete developpe avec ces versions mais il est possible que ca fonctionne avec des versions superieures, mais comme je n'ai pas teste je ne peux pas l'assurer a 100%

