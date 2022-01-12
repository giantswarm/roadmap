---
name: Upgrade Apps
about: Create issue to upgrade Managed Apps
title: Managed Apps Upgrades (Month of {enter date})
labels: kind/upgrade
assignees: ''

---

Aim to focus on 30DU and get them done within 2 days.

**NGINX Ingress Controller** @giantswarm/app-squad-nginx  
https://github.com/giantswarm/nginx-ingress-controller-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release

**External DNS** @giantswarm/app-squad-external-dns  
https://github.com/giantswarm/external-dns-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release
- [ ] request to include in next AWS + Azure release ([HowTo](https://intranet.giantswarm.io/docs/product/releases/requesting-changes-in-next-platform-release/))

**Cert Manager** @giantswarm/app-squad-cert-manager  
https://github.com/giantswarm/cert-manager-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release
- [ ] request to include in next AWS release ([HowTo](https://intranet.giantswarm.io/docs/product/releases/requesting-changes-in-next-platform-release/))

**EFK** @giantswarm/app-squad-efk  
https://github.com/giantswarm/efk-stack-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release

**Kong** @giantswarm/app-squad-kong  
https://github.com/giantswarm/kong-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release

**Prometheus Operator** @giantswarm/app-squad-prometheus  
https://github.com/giantswarm/prometheus-operator-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] upgrade
- [ ] release

**Loki & Promtail** @giantswarm/app-squad-prometheus  @giantswarm/app-squad-loki
https://github.com/giantswarm/loki-app https://github.com/giantswarm/promtail-app 

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] Check Promtail and release together with loki
- [ ] upgrade
- [ ] release

**Linkerd** @giantswarm/app-squad-linkerd
https://github.com/giantswarm/linkerd2-app https://github.com/giantswarm/linkerd2-cni-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] tick this box if there is no new upstream release and no need for upgrade
- [ ] Check linkerd2-cni-app and release together with linkerd2-cni
- [ ] upgrade
- [ ] release

**briefing prepared**
- [ ] 
---

Notes
* Team divides the app upgrades amongst ourselves. Please add @ name beside the app
* [30 Day Upgrade Promise](https://intranet.giantswarm.io/docs/product/pdr/003_30-day-upgrade-promise/): By default, we upgrade our apps within 30 days of an upstream release. We know that falling behind releases and putting upgrades off for extended amounts of time, especially when there’s breaking changes, almost always comes back to bite us.
* Engineer can override this default and decide not to upgrade with good reason.
* The team creates a short briefing for AE/SA so customers are aware they should upgrade
