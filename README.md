# Giant Swarm Product Roadmap

This repository represents Giant's Swarm's product roadmap.

The [Giant Swarm Roadmap project](https://github.com/orgs/giantswarm/projects/273) provides a **Kanban-style overview** of  things we are working on by the development stage they are in, even if we are still thinking about them.

Refer to this [issues](https://github.com/giantswarm/roadmap/issues) list to search roadmap stories.

## FAQs
**Q: Why did we build this?**

A: In the spirit of the open source ecosystem and towards the goal of delighting our customers, we are completely transparent with our roadmap. We want to provide our customers the opportunity to understand better how we work, how decisions were made, and what priorities we have.

**Q: Why are there no dates on our roadmap?**

A: Our primary focus is on security and operational stability. As such, we can't provide specific target dates for features.

**Q: Is it possible to know which features will be included in which release?**

A: Yes! We use [Milestones](https://github.com/giantswarm/roadmap/milestones) to group features by releases so our customers can plan ahead.

Explicit version number, e.g. v13.0.0, means that the feature will be included in this Major release. Non-explicit version number, e.g. v13.x.x, means that the feature will be included in a Minor or Patch release for that Major version. 

Closer to release date, Milestones' description will be updated with link to release PR where you can find the full scope of the release, including release notes and detailed changelog. 

**Q: What do the roadmap categories mean?**

A: We have 6 columns in order to allow us to be very clear on the stages of the development process:

- **Under consideration:**
This lists the features we are thinking about. We have not committed to them, since we are still checking with our customers, upstream and the market as a whole.

- **Future:**
We intend to work on it in the future, but there is no active development yet.

- **Near Term:**
At this stage we know what we want to build and when we plan to build it. These features are next up to be allocated to development teams. We are working on technical specifications, designs, PoCs.

- **In Progress:**
This is our construction site and you get a clear view of what it is that we are building at the moment. These items will be ready in 1-3 months.

- **Ready Soon:**
We are testing these features and preparing them for release. Expect the features in this column to be available within 4 weeks.

- **Released:**
Congratulations! The feature is now available to you. Let us know what you think.

**Q: How to navigate the roadmap?**

A: Teams in Giant Swarm are devided into 3 product areas:

- [**KaaS (Kubernetes as a Service):**](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fkaas)
Improving Giant Swarm's product offering for customers running their operations on Azure, AWS, onprem as well as keeping up to date with new kubernetes versions. Use label [`area/kaas`](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fkaas) to filter features for this area or corresponding `provider` labels to view only provider-related features (e.g. [`provider/aws`](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aprovider%2Faws), [`provider/azure`](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aprovider%2Fazure))

- [**Managed Apps:**](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fmanaged-apps)
Enabling our customers to get the most out of their cloud-native stack, by offering fully managed optional Apps. Use label [`area/managed-apps`](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fmanaged-apps) to filter features for this area.

- [**Empowerment:**](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fempowerment) 
Empowering other product teams by improving our internal platforms, particularly towards release engineering, observability, and operations. Use label [`area/empowerment`](https://github.com/giantswarm/roadmap/projects/1?fullscreen=true&card_filter_query=label%3Aarea%2Fempowerment) to filter features for this area.

**Q: Are all our plans and projects on the roadmap?**

A: Typicaly yes. Please note, that things may move around, we may do things we didn't list and cancel things that we planned.
We track postmortems and security related issues privately and don't include them in the Roadmap to ensure the safety of our customers.

**Q: How can I provide feedback or ask for more information?**

A: We encourage you to comment and provide feedback on the issues themselves.

**Q: How can I request a feature be added to the roadmap?**

A: Please open an issue! Please only use [Feature Request](https://github.com/giantswarm/roadmap/issues/new?assignees=&labels=feature-request&template=feature_request.md&title=) template for submitting your ideas. Community submitted issues will be tagged "Feature-request" and will be reviewed by the team.

## Security disclosures

If you think you’ve found a potential security issue, please follow the instructions [here](https://www.giantswarm.io/responsible-disclosure).

## License

PROJECT is under the Apache 2.0 license. See the [LICENSE](LICENSE) file for details.

Learn more about Giant Swarm at https://www.giantswarm.io
