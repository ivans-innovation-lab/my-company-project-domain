# [projects](http://ivans-innovation-lab.github.io/projects)/my-company-project-domain [![CircleCI](https://circleci.com/gh/ivans-innovation-lab/my-company-project-domain.svg?style=svg)](https://circleci.com/gh/ivans-innovation-lab/my-company-project-domain) [![release](http://github-release-version.herokuapp.com/github/ivans-innovation-lab/my-company-project-domain/release.svg?style=flat)](https://github.com/ivans-innovation-lab/my-company-project-domain/releases/latest)

This component processes commands. Commands are actions which change state in some way. The execution of these commands results in Events being generated which are persisted by Axon, and propagated out to other components (possibly on other VMs). In event-sourcing, events are the sole records in the system. They are used by the system to describe and re-build domain aggregates on demand, one event at a time.

## Running instructions / Installation
 
Make sure that you have this libraries installed in your local maven repsoitory:

 - [my-company-common](https://github.com/ivans-innovation-lab/my-company-common)

```bash
$ cd my-company-project-domain
$ ./mvnw clean install
```

