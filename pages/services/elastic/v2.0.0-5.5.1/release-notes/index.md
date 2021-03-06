---
layout: layout.pug
navigationTitle:  Release Notes
title: Release Notes
menuWeight: 120
excerpt:
featureMaturity:
enterprise: false
---

<!-- This source repo for this topic is https://github.com/dcos-commons/frameworks/elastic -->


# Version 2.0.0-5.5.1

## Improvements
- Based on the latest stable release of the dcos-commons SDK, which provides numerous benefits:
  - Integration with DC/OS features such as virtual networking and integration with DC/OS access controls.
  - Orchestrated software and configuration update, enforcement of version upgrade paths, and ability to pause/resume updates.
  - Placement constraints for pods.
  - Uniform user experience across a variety of services.
- Update to 5.5.1 version of Elastic.
- Separate Kibana into its own package.
- Automatic management of gateway settings.
- Default to 0 ingest nodes.

## Breaking Changes
- This is a major release.  You cannot upgrade to version 2.0.0-5.5.1 from a 1.0.x version of the package.  To upgrade, you must perform a fresh install and replicate data across clusters. Additionally, Kibana is now a separate service.
