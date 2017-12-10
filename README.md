# [projects](http://ivans-innovation-lab.github.io/projects)/my-company-project-domain [![CircleCI](https://circleci.com/gh/ivans-innovation-lab/my-company-project-domain.svg?style=svg)](https://circleci.com/gh/ivans-innovation-lab/my-company-project-domain) [![release](http://github-release-version.herokuapp.com/github/ivans-innovation-lab/my-company-project-domain/release.svg?style=flat)](https://github.com/ivans-innovation-lab/my-company-project-domain/releases/latest)

This component processes commands. Commands are actions which change state in some way. The execution of these commands results in Events being generated which are persisted by Axon, and propagated out to other components (possibly on other VMs). In event-sourcing, events are the sole records in the system. They are used by the system to describe and re-build domain aggregates on demand, one event at a time.

## Development

This project is driven using [Maven][mvn].

[mvn]: https://maven.apache.org/

### Run/Install locally
 
Make sure that you have this libraries installed in your local maven repsoitory:

 - [my-company-common](https://github.com/ivans-innovation-lab/my-company-common)

```bash
$ cd my-company-project-domain
$ ./mvnw clean install
```

### Run tests

This component comes with tests. Use the following command to execute the tests using Maven:

```bash
$ ./mvnw test
```

---
Created by [Ivan Dugalic][idugalic]@[lab][lab].
Need Help?  [Join our Slack team][slack].

[idugalic]: http://idugalic.pro
[lab]: http://lab.idugalic.pro
[slack]: https://communityinviter.com/apps/idugalic/idugalic
[atomist]: https://www.atomist.com/

