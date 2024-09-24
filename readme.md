# Fallacies of ~~Distributed Computing~~ OpenSource Contribution

1. The ~~network is~~ notifications are reliable;
2. Latency is zero;
3. Bandwidth is infinite;
4. Topology doesn't change;
5. ~~Transport~~ Maintenance cost is zero;
6. The ~~network is~~ repositories and issues are homogeneous;
7. The party you are communicating with is trustworthy;
8. My contribution is important.

Mostly, the fallacies result in delays in reviews.

## The Notifications are Reliable

In the K8s repository, there have been ~81K pull requests over ten years -- about one PR per hour.
Maintainers usually receive notifications per email, resulting in 24 emails daily, not including comments or
updates on existing PRs. Notifications can easily be overlooked.

## Latency is Zero

Reviews take time. Ignoring this fact can cause frustration and message (a PR author to maintainers)
amplification overwhelming maintainers and causing them to miss important notifications.

## Bandwidth is Infinite

Maintainers are limited in number, and pull requests are reviewed one by one.

## Topology Doesn't Change

Organisations change, new SIGs emerge, repository owners leave.

## Maintenance Cost is Zero

Introducing a new feature or dependency increases the workload for maintainers.

## The Repositories and Issues are Homogeneous

In umbrella projects like Kubernetes, some repositories are less active. Pull requests are reviewed according to their
priorities.

Review of a pull request with a typo fix in a repository with no activities in the last 6 months will probably be
delayed.

## The Party you are Communicating With is Trustworthy

This fallacy affects repository owners. Ignoring it can lead
to [issues](https://en.wikipedia.org/wiki/XZ_Utils_backdoor) with CVSS score 10/10.

## My Contribution is Important

No.

---

Original [fallacies](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing).
