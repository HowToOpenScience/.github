# Resources

This contains a list of useful resources that can be used to obtain more information on open science and reproducibility practices.

## Software

### [Git][git]

Git is a version control system for project management. Git projects stored on a remote git host (e.g. [GitHub][github] ([ToS][github-terms]), [GitLab][gitlab] ([ToU][gitlab-terms]), etc.) can be integrated into an OSF project for proper version control. Almost all public materials that use a codebase are hosted within a git repository, so you will need to be aware of some basic commands to clone existing repositories and create your own.

Git is licensed under the [GPL-2.0 License][git-license].

#### [Git Clients][gclient]

If you would like to use a GUI Client instead of inputting the commands through the terminal, a Git Client can be used instead. In addition to the built-in tools, there a number of third-party tools. Make sure to adhere to the Licenses and ToU / ToS provided.

### [Visual Studio Code (VSCode)][vsc]

Visual Studio Code is a rich text editor created by Microsoft commonly used for programming and integration. Users can build extensions for better support of a particular file. There are other rich text editors or IDEs used by other researcher; however, this tutorial will be centered around using VSCode.

VSCode is available under a [Microsoft Software License][vsc-terms]; however, it can be built manually under the [MIT License][vsc-license].

### [Docker][docker]

Docker is a combination of open source projects used to create and manage applications. One of the core features of Docker is the development and distribution of containers: a snapshot of the current working environment, such as an OS. These are particularly useful to ship alongside existing materials such that the user is able to use your environment for reproducibility or replicability of the available research.

Docker is provided under the following [Terms of Service][docker-terms] with its consumed projects under the [Apache-2.0 License][docker-license] and others.

### [Python][py]

Python is a programming language generally used to produce relatively efficient proof-of-concept code. Researchers typically use Python since it is relatively simple to understand / use and has a large number of packages / modules that can be consumed.

Python 3 is licensed under the [PSF License Agreement][psf].

### [R][rlang]

R is a programming language used for statistical computation and graphic representations. Researchers who require more complex mathematics typically use R as the language and packages are written by other mathematicians.

R is licensed under [GPL-2.0 License][rlang-license].

#### [RStudio][rstudio]

RStudio is an IDE created by [Posit][posit] for programming with R. It is one of the most commonly used IDEs by researchers for R development.

RStudio is licensed under [AGPL-3.0 License][rstudio-license].

### [ECMAScript][js]

JavaScript is a programming language typically used for scripting in web applications. A good portion of user-facing web applications use JavaScript or one of its many consumers to provide client-side logic and interactions. Researchers will typically use [ECMAScript][ecma], a JavaScript standard, in web applications, so it is highly recommended to have a basic understanding of how the language functions.

ECMASCript is provided under the [ECMA Copyright Notice][emca-copyright] and software is licensed under the [BSD-3-Clause License][emca-license].

#### [Node.js][node]

Node.js is a JavaScript runtime environment built on top of [Google's V8 engine][v8]. Node.js is commonly used by researchers for web applications due to its commonality, integration, and numerous packages written. It is still a useful material to read up on if you have the time.

Node.js is licensed under the [MIT License][node-license] with included external libraries under a variety of licenses.

#### [npm]

npm is a package manager for Node.js. Most applications created by researchers are most likely built with npm since it tends to have easy runtime support and standardized access to published packages. It is highly recommended to review this topic in case you would like to build a front-end web application yourself.

npm is licensed under the [Artistic-2.0 License][npm-license] with its public registry under the following [Terms of Use][npm-terms]

#### [nvm]

nvm is a version manager for Node.js and npm. This is particularly useful if you need to use someone else's environment or make your own more robust.

All nvm implementations recommended by npm are licensed under the [MIT License][nvm-license].

## Services

### [ORCID iD][orcid]

An ORCID iD is a universally unique digital identifier for a researcher. It is  highly recommended for you as a researcher to have one such that all papers you have written can be linked back to you.

ORCID iDs are provided under the following [Terms of Use][orcid-terms].

### [Open Science Framework (OSF)][osf]

The Open Science Framework, commonly known as OSF, is a project manager which allows researchers to provide, document, archive, collaborate, share, and register methodologies, materials, data, and outcomes. You can also create preregistrations and preprints for your project or as an independent entity. OSF accounts can be created from an [ORCID iD][sect-orcid].

The Open Science Framework is provided under the [Terms of Use][osf-terms] provided by the Center for Open Science, Inc.

### [AsPredicted][ap]

AsPredicted allows a researcher to create a preregistration for their given project. Many researchers use AsPredicted to host their preregistrations.

AsPredicted is provided under the following [Terms of Use][ap-terms].

### [Code Ocean][codeocean]

Code Ocean is a reproducibility platform that allows researchers and developers to share, discover, and run code for a given project. All  works are open access.

Code Ocean is provided under the following [Terms of Use][codeocean-terms].

## Explanations and Tutorials

### [Let's Discover Open Science and Reproducibility][ldosr-substack]

*Let's Discover Open Science and Reproducibility* is a blog written by Aaron Haim, one of the maintainers of this site, reviewing and explaining topics on how to best make your work open and reproducible for someone who has never encountered the subject before.

The blog is currently available on [Substack][ldosr-substack] and [Cohost][ldosr-cohost] with plans to make online videos on them in the future.

As a blog, the contents are within the Public Domain.

### [Improving Your Statistical Inferences][iysi-site]

* Lakens, D. (2022). Improving Your Statistical Inferences (v1.0.0). Zenodo. Retrieved from [https://lakens.github.io/statistical_inferences/index.html][iysi-site]. [https://doi.org/10.5281/zenodo.6409077][iysi-doi]

*Improving Your Statistical Inferences* is a website containing information on how to improve the analysis conducted on a set of data.  Additionally, it contains information on preregistrations and reproducibility of the written analysis. The website revolves around its implementation in R.

The website is licensed under [CC-BY-NC-SA-4.0][ccbyncsa]

[orcid]: https://orcid.org
[orcid-terms]: https://info.orcid.org/terms-of-use
[sect-orcid]: #orcid-id

[osf]: https://osf.io
[osf-terms]: https://github.com/CenterForOpenScience/cos.io/blob/master/TERMS_OF_USE.md

[ap]: https://aspredicted.org
[ap-terms]: https://aspredicted.org/messages/terms.php

[iysi-site]: https://lakens.github.io/statistical_inferences/index.html
[iysi-doi]: https://doi.org/10.5281/zenodo.6409077
[ccbyncsa]: https://creativecommons.org/licenses/by-nc-sa/4.0/

[ldosr-substack]: https://osreproducible.substack.com/
[ldosr-cohost]: https://cohost.org/osreproducible

[codeocean]: https://codeocean.com/
[codeocean-terms]: https://codeocean.com/terms-of-use/

[git]: https://git-scm.com
[github]: https://github.com
[github-terms]: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
[gitlab]: https://about.gitlab.com
[gitlab-terms]: https://about.gitlab.com/terms
[git-license]: https://git-scm.com/about/free-and-open-source

[gclient]: https://git-scm.com/downloads/guis

[vsc]: https://code.visualstudio.com/
[vsc-terms]: https://code.visualstudio.com/License
[vsc-license]: https://github.com/microsoft/vscode/blob/main/LICENSE.txt

[docker]: https://www.docker.com
[docker-terms]: https://www.docker.com/legal/docker-terms-service
[docker-license]: https://www.docker.com/community/open-source

[py]: https://www.python.org
[psf]: https://docs.python.org/3/license.html#psf-license-agreement-for-python-release

[rlang]: https://www.r-project.org
[rlang-license]: https://www.r-project.org/COPYING

[rstudio]: https://posit.co/products/open-source/rstudio
[posit]: https://posit.co/
[rstudio-license]: https://github.com/rstudio/rstudio/blob/main/COPYING

[js]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[ecma]: https://www.ecma-international.org/publications-and-standards/standards/ecma-262/
[emca-copyright]: https://www.ecma-international.org/policies/by-ipr/ecma-text-copyright-policy/
[emca-license]: https://262.ecma-international.org/#sec-copyright-and-software-license

[node]: https://nodejs.org
[v8]: https://github.com/v8/v8
[node-license]: https://github.com/nodejs/node/blob/HEAD/LICENSE

[npm]: https://www.npmjs.com
[npm-license]: https://github.com/npm/cli/blob/latest/LICENSE
[npm-terms]: https://docs.npmjs.com/policies/open-source-terms

[nvm]: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm#using-a-node-version-manager-to-install-nodejs-and-npm
[nvm-license]: https://opensource.org/licenses/MIT

--8<-- "includes/abbreviations.md"