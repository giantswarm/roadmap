---
name: Upgrade Apps
about: Create issue to upgrade Managed Apps
title: Managed Apps Upgrades (Month of {enter date})
labels: kind/upgrade, team/halo
assignees: ''

---

Aim to focus on 30DU and get them done within 2 days.

**NGINX Ingress Controller** @giantswarm/app-squad-nginx  
https://github.com/giantswarm/nginx-ingress-controller-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**External DNS** @giantswarm/app-squad-external-dns  
https://github.com/giantswarm/external-dns-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**Cert Manager** @giantswarm/app-squad-cert-manager  
https://github.com/giantswarm/cert-manager-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**EFK** @giantswarm/app-squad-efk  
https://github.com/giantswarm/efk-stack-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**Kong** @giantswarm/app-squad-kong  
https://github.com/giantswarm/kong-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**Prometheus Operator** @giantswarm/app-squad-prometheus  
https://github.com/giantswarm/prometheus-operator-app

* Link to latest release: 
* If won't upgrade, why?

- [ ] upgrade
- [ ] release

**~~aqua~~**  
https://github.com/giantswarm/aqua-app  

- [ ] ~~upgrade~~
- [ ] ~~release~~

* Link to latest release: 
* If won't upgrade, why? @jgsqware or @yasn77 we'll skip checking for any upgrades unless you tell us to.

---

Notes
* Team divides the app upgrades amongst ourselves. Please add @ name beside the app
* [30 Day Upgrade Promise](https://intranet.giantswarm.io/docs/product/pdr/003_30-day-upgrade-promise/): By default, we upgrade our apps within 30 days of an upstream release. We know that falling behind releases and putting upgrades off for extended amounts of time, especially when there’s breaking changes, almost always comes back to bite us.
* Engineer can override this default and decide not to upgrade with good reason.
