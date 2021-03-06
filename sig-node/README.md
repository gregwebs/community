<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# Node Special Interest Group


## Meetings
* Regular SIG Meeting: [Tuesdays at 10:00 PT (Pacific Time)](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (weekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=10:00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1Ne57gvidMEWXR70OxxnRkYquAoMpt56o75oZtg-OeBg/edit?usp=sharing).
  * [Meeting recordings](https://www.youtube.com/watch?v=FbKOI9-x9hI&list=PL69nYSiGNLP1wJPj5DYWXjiArF-MJ5fNG).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* Dawn Chen (**[@dchen1107](https://github.com/dchen1107)**), Google
* Derek Carr (**[@derekwaynecarr](https://github.com/derekwaynecarr)**), Red Hat

## Contact
* [Slack](https://kubernetes.slack.com/messages/sig-node)
* [Mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-node)
* [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fnode)

## Subprojects

The following subprojects are owned by sig-node:
- **cri-api**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes/cri-api/master/OWNERS
- **cri-o**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes-sigs/cri-o/master/OWNERS
- **cri-tools**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes-sigs/cri-tools/master/OWNERS
- **frakti**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes/frakti/master/OWNERS
- **kubelet**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes/kubernetes/master/cmd/kubelet/OWNERS
    - https://raw.githubusercontent.com/kubernetes/kubernetes/master/pkg/kubelet/OWNERS
- **node-api**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes/node-api/master/OWNERS
    - https://raw.githubusercontent.com/kubernetes/kubernetes/master/staging/src/k8s.io/node-api/OWNERS
- **node-feature-discovery**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes-sigs/node-feature-discovery/master/OWNERS
- **node-problem-detector**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes/node-problem-detector/master/OWNERS
- **rktlet**
  - Owners:
    - https://raw.githubusercontent.com/kubernetes-incubator/rktlet/master/OWNERS

## GitHub Teams

The below teams can be mentioned on issues and PRs in order to get attention from the right people.
Note that the links to display team membership will only work if you are a member of the org.

| Team Name | Details | Description |
| --------- |:-------:| ----------- |
| @kubernetes/sig-node-api-reviews | [link](https://github.com/orgs/kubernetes/teams/sig-node-api-reviews) | API Changes and Reviews |
| @kubernetes/sig-node-bugs | [link](https://github.com/orgs/kubernetes/teams/sig-node-bugs) | Bug Triage and Troubleshooting |
| @kubernetes/sig-node-feature-requests | [link](https://github.com/orgs/kubernetes/teams/sig-node-feature-requests) | Feature Requests |
| @kubernetes/sig-node-pr-reviews | [link](https://github.com/orgs/kubernetes/teams/sig-node-pr-reviews) | PR Reviews |
| @kubernetes/sig-node-proposals | [link](https://github.com/orgs/kubernetes/teams/sig-node-proposals) | Design Proposals |
| @kubernetes/sig-node-test-failures | [link](https://github.com/orgs/kubernetes/teams/sig-node-test-failures) | Test Failures and Triage |

<!-- BEGIN CUSTOM CONTENT -->
## Goals

The following topics fall under scope of this SIG.

- Kubelet and its features
- Pod API and Pod behaviors (with [sig-architecture](../sig-architecture))
- Node API (with [sig-architecture](../sig-architecture))
- Node controller
- Node level performance and scalability (with [sig-scalability](../sig-scalability))
- Node reliability (problem detection and remediation)
- Node lifecycle management (with [sig-cluster-lifecycle](../sig-cluster-lifecycle))
- Container runtimes
- Device management
- Image management
- Node-level resource management (with [sig-scheduling](../sig-scheduling))
- Hardware discovery
- Issues related to node, pod, container monitoring (with [sig-instrumentation](../sig-instrumentation))
- Node level security and Pod isolation (with [sig-auth](../sig-auth))
- Host OS and/or kernel interactions (to a limited extent)

We also work closely with [sig-storage](../sig-storage) and [sig-network](../sig-network). As you can see, this is a very cross-functional team!
<!-- END CUSTOM CONTENT -->
