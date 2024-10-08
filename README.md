# mongodb-quartz-properties

## About / Synopsis

This plugin contributes a new `quartz.properties.nxftl` that allows you to provide additonal **Quartz** configuration variables.

It was generated with the following commands:
```
mkdir mongodb-quartz-properties && cd $_
nuxeo b multi-module
nuxeo b package
# Edit assembly.xml (comment <config addtemplate>), nuxeo.defaults, and quartz.properties.nxftl
```

## Requirements

Building requires the following software:

* git
* maven

## Build

```
git clone ...
cd mongodb-quartz-properties

mvn clean install
```

## Installation

```
nuxeoctl mp-install mongodb-quartz-properties/mongodb-quartz-properties-package/target/mongodb-quartz-properties-*.zip
```

## Support

**These features are not part of the Nuxeo Production platform, they are not supported**

These solutions are provided for inspiration and we encourage customers to use them as code samples and learning resources.

This is a moving project (no API maintenance, no deprecation process, etc.) If any of these solutions are found to be useful for the Nuxeo Platform in general, they will be integrated directly into platform, not maintained here.


## License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## About Nuxeo

Nuxeo Platform is an open source Content Services platform, written in Java. Data can be stored in both SQL & NoSQL databases.

The development of the Nuxeo Platform is mostly done by Nuxeo employees with an open development model.

The source code, documentation, roadmap, issue tracker, testing, benchmarks are all public.

Typically, Nuxeo users build different types of information management solutions for [document management](https://www.nuxeo.com/solutions/document-management/), [case management](https://www.nuxeo.com/solutions/case-management/), and [digital asset management](https://www.nuxeo.com/solutions/dam-digital-asset-management/), use cases. It uses schema-flexible metadata & content models that allows content to be repurposed to fulfill future use cases.

More information is available at [www.nuxeo.com](https://www.nuxeo.com).

