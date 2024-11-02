![You can get stuff like this](img/1.gif)
_You can get stuff like this with Network Policies..._

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

# Kubernetes Network Policy Recipes

This repository contains various use cases of Kubernetes
[Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
and sample YAML files to leverage in your setup. If you ever wondered
how to drop/restrict traffic to applications running on Kubernetes, read on.

Easiest way to try out Network Policies is to create a new [Google Kubernetes
Engine](https://cloud.google.com/kubernetes-engine) cluster. Applying Network
Policies on your existing cluster can disrupt the networking. At the time of
writing, most cloud providers do not provide built-in network policy support.

If you are not familiar with Network Policies at all, I recommend reading my
[Securing Kubernetes Cluster Networking](https://nholuong.im/blog/kubernetes-network-policy/)
article first.

### Before you begin

It will help you understand this repo
better.

- [Create a cluster](00-create-cluster.md)

### Basics

- [DENY all traffic to an application](01-deny-all-traffic-to-an-application.md)
- [LIMIT traffic to an application](02-limit-traffic-to-an-application.md)
- [ALLOW all traffic to an application](02a-allow-all-traffic-to-an-application.md)

### Namespaces

- [DENY all non-whitelisted traffic in the current namespace](03-deny-all-non-whitelisted-traffic-in-the-namespace.md)
- [DENY all traffic from other namespaces](04-deny-traffic-from-other-namespaces.md) (a.k.a. LIMIT access to the current namespace)
- [ALLOW traffic to an application from all namespaces](05-allow-traffic-from-all-namespaces.md)
- [ALLOW all traffic from a namespace](06-allow-traffic-from-a-namespace.md)
- [ALLOW traffic from some pods in another namespace](07-allow-traffic-from-some-pods-in-another-namespace.md)

### Serving External Traffic

- [ALLOW traffic from external clients](08-allow-external-traffic.md)

### Advanced

- [ALLOW traffic only to certain port numbers of an application](09-allow-traffic-only-to-a-port.md)
- [ALLOW traffic from apps using multiple selectors](10-allowing-traffic-with-multiple-selectors.md)

### Controlling Outbound (Egress) Traffic 🔥🆕🔥

- [DENY egress traffic from an application](11-deny-egress-traffic-from-an-application.md)
- [DENY all non-whitelisted egress traffic in a namespace](12-deny-all-non-whitelisted-traffic-from-the-namespace.md)
- 🔜 LIMIT egress traffic from an application to some pods
- 🔜 ALLOW traffic only to Pods in a namespace
- [LIMIT egress traffic to the cluster (DENY external egress traffic)](14-deny-external-egress-traffic.md)

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: Nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* [PayPal.me](https://www.paypal.com/paypalme/nholuongut)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
