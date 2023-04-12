# Welcome to the SLSA demo

Alba systems is a fictive company.

The aim of this demo is to demonstrate how to achieve SLSA level 3 (build track) by using Github [reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows).

You'll find two repositories : 

- [slsa-provenance-generator](https://github.com/albasystems/slsa-provenance-generator) : a repo responsible for generating SLSA provenance for all the repos of the company. This repo is a fork of the original [slsa-github-generator](https://github.com/slsa-framework/slsa-github-generator), the aim is to represent a real enterprise use case where keeping control over provenance generation is important . This repo is managed by a **security team**.

- [hello-slsa](https://github.com/albasystems/hello-slsa) : a repo for a standard business application. This repo is managed by a **dev team**.
