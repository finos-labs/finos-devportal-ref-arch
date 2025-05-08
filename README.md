![badge-labs](https://user-images.githubusercontent.com/327285/230928932-7c75f8ed-e57b-41db-9fb7-a292a13a1e58.svg)

# finos-devportal-ref-arch

This repository is not the actual Backstage development repository.
Rather, it is an example implementation of the Backstage developer portal, with additional work to test and deploy into the FINOS hosted environments.

This repository is meant to be an example of best practices from a few different perspectives:

* demonstrate production-ready deployment architecture
* demonstrate security and compliance guardrails around the development and implementation
* provide Developer Portal for FINOS project teams (eg. TraderX)

## Development setup

Currently, this repository will run out-of-the-box on your laptop for experimentation:

```sh
npm install
npm start
```

## Roadmap

* Set up infrastructure environment for running Backstage under FINOS
* Set up githup actions to build and deploy updates to the Dev Portal
* Identify beta teams / services in TraderX to onboard to the FINOS Dev Portal
* Develop onboarding documentation for wider adoption within FINOS projects
* Collaborate with teams to identify useful plugins, and how to implement within the constraints of a heavily-regulated industry (like Financial Services)

## Contributing

### Using DCO to sign your commits

All commits must be signed with a DCO signature to avoid being flagged by the DCO Bot.
This means that your commit log message must contain a line that looks like the following one, with your actual name and email address:

```
Signed-off-by: John Doe <john.doe@example.com>
```

Adding the `-s` flag to your `git commit` will add that line automatically.
You can also add it manually as part of your commit log message or add it afterwards with `git commit --amend -s`.

#### Helpful DCO Resources
- [Git Tools - Signing Your Work](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)
- [Signing commits
](https://docs.github.com/en/github/authenticating-to-github/signing-commits)

### Steps

* Create your issue [here](https://github.com/finos-labs/finos-devportal-ref-arch/issues/new).
* Fork the repo (<https://github.com/finos/finos-devportal-ref-arch/fork>)
* Create your feature branch (`git checkout -b feature/###-short-label`)
* Read our [contribution guidelines](.github/CONTRIBUTING.md) and [Community Code of Conduct](https://www.finos.org/code-of-conduct)
* Commit your changes (`git commit -s -am 'feat(###): short description of feature'`)
* Push to the branch (`git push origin feature/###-short-label`)
* Create a new Pull Request

## License

Copyright 2025 FINOS Dev Portal Reference Architecture Authors

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
