# Awesome Dhall-Lang [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
    <div>
        <img width="500" src="img/dhall-logo.svg" alt="dhall-logo">
    </div>
</div>

A curated list of awesome dhall-lang binding, libraries and anything related to dhall-lang!

## Contents
- [Binding](#binding)
- [Integration](#integration)
- [Output Formats](#output-formats)
- [Libraries](#libraries)
- [Projects](#projects)
- [Text Editor Support](#text-editor-support)

## Binding
- [dhall-haskell](https://github.com/dhall-lang/dhall-haskell) - Haskell language support.
- [dhallj](https://github.com/travisbrown/dhallj) - Java language support.
- [dhall-clj](https://github.com/f-f/dhall-clj) - Clojure language support.
- [dhall-golang](https://github.com/philandstuff/dhall-golang) - Go language support.
- [dhall-purescript](https://github.com/MonoidMusician/dhall-purescript) - PureScript language support.
- [dhall-rust](https://github.com/Nadrieril/dhall-rust) - Rust language support.
- [dhall-ruby](https://git.sr.ht/~singpolyma/dhall-ruby) - Ruby language support.
- [dhall-python](https://github.com/s-zeng/dhall-python) - Python language support.
- [dhall-unison](https://github.com/hagl/dhall-unison) - Unison language support.
- [scall](https://github.com/winitzki/scall) - Scala language support.
- [idrall](https://github.com/alexhumphreys/idrall) - Idris language support.

## Integration
- [dhall-rails](https://git.sr.ht/~singpolyma/dhall-rails)
- [dhall-to-etlas](https://github.com/eta-lang/dhall-to-etlas)

## Output Formats
- [dhall-json](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-json)
- [dhall-yaml](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-yaml)
- [dhall-to-cabal](https://github.com/dhall-lang/dhall-to-cabal)
- [dhall-nix](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-nix)
- [dhall-bash](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-bash)
- [dhall-toml](https://github.com/dhall-lang/dhall-haskell/tree/main/dhall-toml)
- [dhall-csv](https://github.com/dhall-lang/dhall-haskell/tree/main/dhall-csv)
- [dhall-xml-ruby](https://git.sr.ht/~singpolyma/dhall-xml-ruby)

## Libraries
- [dhall-prelude](https://github.com/dhall-lang/dhall-lang/tree/master/Prelude) - Standard Libraries for dhall.
- [dhall-kubernetes](https://github.com/dhall-lang/dhall-kubernetes) - Typecheck, template and modularize your Kubernetes definitions with Dhall.
- [dhall-kong](https://github.com/RyanSiu1995/dhall-kong) - Dhall types definition for Kong declarative configuration file.
- [dhall-terraform](https://github.com/blast-hardcheese/dhall-terraform) - Tooling to manage complexity and increase discoverability in Terraform by writing in Dhall.
- [dhall-nethack](https://github.com/dhall-lang/dhall-nethack) - Generate NetHack configurations using Dhall.
- [dada](https://github.com/sellout/dada) - Recursion schemes.
- [dhall-bhat](https://github.com/FormationAI/dhall-bhat/) - Abstractions.
- [vmchale/github-actions-dhall](https://github.com/vmchale/github-actions-dhall) - Dhall helpers for GitHub actions.
- [regadas/github-actions-dhall](https://github.com/regadas/github-actions-dhall) - Typecheck, template and modularize your GitHub Action definitions with Dhall.
- [bgamari/dhall-gitlab-ci](https://github.com/bgamari/dhall-gitlab-ci) - Dhall types for GitLab CI/CD.
- [dhall-kops](https://github.com/coralogix/dhall-kops) - Dhall types for Kops.
- [dhall-prometheus-operator](https://github.com/coralogix/dhall-prometheus-operator) - Dhall types for the Prometheus Operator.
- [dhall-genode](https://git.sr.ht/~ehmry/dhall-genode) - Genode OS configuration types and functions.
- [dhall-openssl](https://github.com/jvanbruegge/dhall-openssl) - Generate a type-safe openssl configuration file with dhall.
- [nats.dhall](https://github.com/wallyqs/nats.dhall) - Dhall types to setup NATS.io on Kubernetes.
- [dhall-ansible](https://github.com/softwarefactory-project/dhall-ansible) - Dhall types for Ansible.
- [dhall-concourse](https://github.com/coralogix/dhall-concourse) - Dhall types for Concourse.
- [dhall-dot](https://github.com/Gabriel439/dhall-dot) - Dhall types and renderer for the DOT Graph description language.
- [dhall-openstacksdk](https://github.com/softwarefactory-project/dhall-openstacksdk) - Dhall types for OpenStack clouds.yaml.
- [dhall-nomad](https://github.com/seatgeek/dhall-nomad) - Dhall types for HashiCorp's Nomad job scheduler
- [dhall-aws-cloudformation](https://github.com/jcouyang/dhall-aws-cloudformation) - Dhall types for AWS CloudFormation
- [dhall-tsconfig](https://github.com/maxdeviant/dhall-tsconfig) - Dhall bindings for [TSConfig](https://www.typescriptlang.org/tsconfig).
- [dhall-webmanifest](https://gitlab.com/toastal/dhall-webmanifest) - Types for building Web Application Manifest files.
- [dhall-css-color](https://gitlab.com/toastal/dhall-css-color) - CSS4 colors.
- [dhall-semver](https://github.com/Gabriella439/dhall-semver) - Dhall support for [semantic version numbers](https://semver.org/).
- [dhall-security-txt](https://github.com/coralogix/dhall-security-txt) - Generate standard-compliant [security.txt](https://securitytxt.org/) files using Dhall.
- [dhall-grafana](https://github.com/weeezes/dhall-grafana) - Build Grafana dashboards with Dhall.
- [dhall-docker-compose](https://github.com/sbdchd/dhall-docker-compose) - A library for writing Docker Compose files in Dhall.
- [dhall-containerfile](https://github.com/softwarefactory-project/dhall-containerfile) - Dhall types for Containerfile.
- [dhall-resume](https://github.com/gaelreyrol/dhall-resume) - Dhall bindings to the [JSON Resume](https://jsonresume.org) schema.
- [dhall-prometheus](https://github.com/softwarefactory-project/dhall-prometheus) - Dhall bindings to Prometheus configuration.
- [dhall-semaphore](https://github.com/maxdeviant/dhall-semaphore) - Dhall bindings for Semaphore CI.
- [dhall-spinnaker](https://github.com/zendesk/dhall-spinnaker) - Dhall bindings to the Spinnaker Pipeline API.
- [dhall-sgf](https://github.com/TristanCacqueray/dhall-sgf) - Dhall support for the Smart Game Format.
- [dhall-rook](https://github.com/jbellerb/dhall-rook) - Dhall bindings for [Rook](https://rook.io/).

## Projects
- [cpkg](https://github.com/vmchale/cpkg) - A build tool/package manager for C, configured with Dhall.
- [updo](https://github.com/cabalism/updo) - From Dhall configuration, generate Stack and Cabal projects with Dhall text templating.
- [dhall-mock](https://github.com/dhall-mock/dhall-mock) - A HTTP mock server based on Dhall configuration.
- [approportionment](https://github.com/akazukin5151/approportionment) - [Yee diagram](https://electowiki.org/wiki/Yee_diagram) generator for multi-winner electoral methods designed for proportional representation, configured with Dhall.
- [podenv](https://github.com/podenv/podenv) - A container runtime wrapper using Dhall to define functional environments.
- [animation-fractal](https://gitlab.com/TristanCacqueray/animation-fractal) - A graphic engine using Dhall to define demos, see the [Using Dhall To Animate Fractal](https://tristancacqueray.github.io/blog/using-dhall-to-animate-fractal) blog post.
- [cv-static](https://github.com/mstksg/cv-static) - Generate CV in HTML and PDF using Dhall.
- [resume](https://github.com/s-zeng/resume) - Generate résumé in a number of formats from a Dhall specification.
- [RuneSlayer](https://github.com/MaxOw/RuneSlayer) - A role-playing game meant to help learning a natural language.
- [Xe/site](https://github.com/Xe/site) - a [personal site](https://xeiaso.net) using Dhall in a substantial way.
- [grafdhall](https://github.com/softwarefactory-project/grafdhall) - Takes Grafana dashboards in Dhall format, and submits them to a Grafana service.

## Text Editor Support
- [dhall-vim](https://github.com/vmchale/dhall-vim) - Syntax highlighting in Vim for Dhall.
- [vscode-language-dhall](https://github.com/PanAeon/vscode-language-dhall) - Dhall Syntax Highlighting for VS Code.
- [vscode-dhall-lsp-server](https://github.com/dhall-lang/vscode-dhall-lsp-server) - VSCode plugin that provides Language Server Protocol support for Dhall.
- [atom-language-dhall](https://github.com/jmitchell/atom-language-dhall) - Dhall language support in Atom.
- [dhall-mode](https://github.com/psibi/dhall-mode) - Dhall language support in Emacs.
- [dhall-lsp-server](https://github.com/dhall-lang/dhall-haskell/tree/main/dhall-lsp-server) - Language Server Protocol server for Dhall.
- [dhall-sublime-syntax-highlighting](https://github.com/kukimik/dhall-sublime-syntax-highlighting) - Dhall syntax highlighting for Sublime Text.

## Miscellaneous
- [relude](https://github.com/kowainik/relude/tree/main/hlint) - A custom Haskell Prelude that uses Dhall to generate rules for the HLint linter, see the [blog post](https://kowainik.github.io/posts/2018-09-09-dhall-to-hlint).

## Contributing
Anyone who finds something interesting about dhall-lang is welcome to submit a pull request to add it to our list!
Please conduct the [CONTRIBUTING.md](CONTRIBUTING.md) before submitting the pull request.
