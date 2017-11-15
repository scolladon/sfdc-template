# sfdc-template
CI project template

This repository purpose is to centralized a project template/squeleton/backbone
It contains only the master branch.
You can create your own gitflow on it.

### Installing

```
$ cd /your/workspace
$ git clone --recursive git@github.com:scolladon/sfdc-template.git new-sfdc-project
$ cd new-sfdc-project
$ git remote remove origin
$ git remote add origin <your-repo-url>

# Then
$ cd build
$ npm install
```

## Built With

* [sfdc-ci-toolkit](https://github.com/scolladon/sfdc-ci-toolkit) - CI Scripts for Salesforce projects.

## Versioning

[SemVer](http://semver.org/) is used for versioning.

## Authors

* **Sebastien Colladon** - *Initial work* - [scolladon](https://github.com/scolladon)