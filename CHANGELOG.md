# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0](https://github.com/lotusnoir/ansible-system_network/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`0556e96`](https://github.com/lotusnoir/ansible-system_network/commit/0556e960fcf57da1d7e4373cd8b0d9475f32e2d0)
- update core and molecule [`971b23a`](https://github.com/lotusnoir/ansible-system_network/commit/971b23acc3fa919c1b0be71fc0e540fe27f03a4a)
- add oraclelinux10 support + lint and core fixes [`3145337`](https://github.com/lotusnoir/ansible-system_network/commit/31453378f149800b2c0a50b8cc56485fd825596e)

## [3.0.0](https://github.com/lotusnoir/ansible-system_network/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`e84bd46`](https://github.com/lotusnoir/ansible-system_network/commit/e84bd46c8e19a2b87b8e54313cee4943a3279686)
- update core, molecule + gitlab-ci [`244ea9a`](https://github.com/lotusnoir/ansible-system_network/commit/244ea9a45ce5723ddf9e9149115360fb7df1bb60)
- fix lint [`c65b22d`](https://github.com/lotusnoir/ansible-system_network/commit/c65b22d2e54497ea744752032c7e693f932f9e95)
- fix molecule paralelism and little updates [`15122f8`](https://github.com/lotusnoir/ansible-system_network/commit/15122f8e6d8ded286b9f2c941f59eb8f101bfa8b)
- add support for ubuntu24 [`145cada`](https://github.com/lotusnoir/ansible-system_network/commit/145cadaffd6c46e5d4803f8310ae5e6d2db6af0d)
- add version on molecule play image to maintain support on old release [`5849c0b`](https://github.com/lotusnoir/ansible-system_network/commit/5849c0b77e4134c04a4472fe0fe2ee43fe8858d9)
- update molecule [`668afb1`](https://github.com/lotusnoir/ansible-system_network/commit/668afb190f8967563ae1e7fd3e323537148cc9cd)
- add redhat 9 to default supported distrib [`0c6843e`](https://github.com/lotusnoir/ansible-system_network/commit/0c6843ea287badf67324e7bfeb3474b53e997ebd)
- add redhat 8 to default supported distrib [`a3d9cec`](https://github.com/lotusnoir/ansible-system_network/commit/a3d9cec86b3822671df94b4472201586b5edad9a)
- sort testing distrib to avoid random changes [`96ce10c`](https://github.com/lotusnoir/ansible-system_network/commit/96ce10c2b729eb201d891d1a02871ddbd6a3ac22)

## [2.0.0](https://github.com/lotusnoir/ansible-system_network/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`8339715`](https://github.com/lotusnoir/ansible-system_network/commit/8339715af243abcd9e9f986b2cb180525b6a1b87)
- update readme + precommit + include vars [`83c5527`](https://github.com/lotusnoir/ansible-system_network/commit/83c5527ae846505514b6f1998f46f994916ff36b)
- change import tasks to include in order to support facts on name [`6a521d2`](https://github.com/lotusnoir/ansible-system_network/commit/6a521d2f67ae76675a63ebc3bc7870f12c02b5d9)

## [1.1.0](https://github.com/lotusnoir/ansible-system_network/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`36fcee0`](https://github.com/lotusnoir/ansible-system_network/commit/36fcee0d1c518c24445850bd731a95539481da9a)

## [1.0.0](https://github.com/lotusnoir/ansible-system_network/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`c9773f5`](https://github.com/lotusnoir/ansible-system_network/commit/c9773f525773e02e0cc1152fb8d9ba4629eebfd8)
- add precommit for lint [`a4a64a5`](https://github.com/lotusnoir/ansible-system_network/commit/a4a64a5625f118b5a24b413aa92a1974adedc71d)
- fix checks [`e558edc`](https://github.com/lotusnoir/ansible-system_network/commit/e558edcdcb5373d688f0a24cbec232cebbc9fd11)
- add new molecule all scenario [`8955c3d`](https://github.com/lotusnoir/ansible-system_network/commit/8955c3d1e86a9b68d9d6bc165b3a29d94aaab4fb)
- split distro for molecule tests on ci [`670dfeb`](https://github.com/lotusnoir/ansible-system_network/commit/670dfeb227a42a7b3f11469ce6b7c2d01465b9d9)
- update checks and Readme [`513d359`](https://github.com/lotusnoir/ansible-system_network/commit/513d35995bf14116268fe1be4710ef6b58c445ba)
- add molecule fix for ora9 [`a03d394`](https://github.com/lotusnoir/ansible-system_network/commit/a03d3946ff78033c902f776e7002e6c3a77400db)
- update checks [`fd60e51`](https://github.com/lotusnoir/ansible-system_network/commit/fd60e516525a91d4e8ae37e5c977eb5eb6d2a3c8)
- fix test and pipeline [`998c105`](https://github.com/lotusnoir/ansible-system_network/commit/998c105bcf4565dd922ff1d531e32510fa9e1a18)

## [0.3.0](https://github.com/lotusnoir/ansible-system_network/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`8f5cc54`](https://github.com/lotusnoir/ansible-system_network/commit/8f5cc540be457e81448c0be377b696261ee3d50e)
- minor: add oracleLinux support + little fixes [`ae8953d`](https://github.com/lotusnoir/ansible-system_network/commit/ae8953d30b3635d797d2c6410c8513b74e38eadd)

## [0.2.0](https://github.com/lotusnoir/ansible-system_network/compare/0.1.0...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`95f27d4`](https://github.com/lotusnoir/ansible-system_network/commit/95f27d4984cc60b417117ac1dc5aa3decf31bdfd)
- fix: remove unsupported centos8 + minor fixes [`102d46b`](https://github.com/lotusnoir/ansible-system_network/commit/102d46bd82c7e2c1d2d379c3dabc913750295f82)

## 0.1.0 - 2021-11-19

### Commits

- initial commit [`d363ce4`](https://github.com/lotusnoir/ansible-system_network/commit/d363ce4e9e0c9a28f737191efca0835a9c661c33)
