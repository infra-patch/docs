
## Infrastructure [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/ABOUT/INFRA.md)
The growing complexity of today’s IT reality is indisputable: Software is becoming more complex, and the infrastructure it runs on is equally so. This complexity comes, in part, from adding layers upon layers to the infrastructure we manage—from bare metal servers to VMs to containers to function-based computing—and from how quickly we cycle in new technologies and how slowly old technologies are cycled out.


Ephemeral and multi-generational infrastructure (often side by side) are the new normal. Old and new technologies co-mingle, and while new technologies may be shiny and exciting, they quickly become ordinary as the next new thing comes along.

Here’s a sobering stat: In Q4 2017, IBM’s mainframe business grew by 32%. So even while cloud, AI and security initiatives are on the rise at IBM, mainframes sustain a bulk of their business. Old tech perseveres, and we have to find new solutions to bridge the gap between old and new.

The hodgepodge of technologies—and the challenges they bring—are compounded further when we’re talking about big infrastructure.



What Qualifies as Big Infrastructure?

For the purpose of this discussion, big infra is an organization that has been around for at least 10 years. That means they’ve had success, they’ve grown and their infrastructure has grown along with them, and the technologies at play have expanded as well.

Your organization’s exact age, size and revenue aren’t particularly material; what matters is you’ve had enough time to accumulate resources, people, practices and technologies to create what I think of as a trail mix problem—basically enough legacy infrastructure to start creating problems.
The Challenges of Big Infrastructure

The challenges of big infra stem from the technology itself and from the way people use that technology. As an organization grows, its teams often become larger and more siloed, and departmental goals become disconnected. Even when working toward the same goal, departments diverge in their methods for reaching that goal.

Now, add tools and technology to the mix: Over time, teams choose tools they prefer, or build their own, which works out okay for a while until they have to collaborate with another department that uses different tools and a completely different set of practices.

Now, add in different work styles and personality types and company politics, and everything gets tangled up fairly quickly. Trying to keep track of who’s using what, how they’re using it and what’s working (or not) is no easy task.

One customer, for example, had one team using Chef and was all in, and were trying to get buy in from other teams as well, but there was another team that was early days Docker, hand rolling Docker hosts, and didn’t want to adopt Chef. Then there was a different team who was early days Kubernetes and didn’t want to use Docker, and yet another team using Puppet. Once they had to work with each other, things broke down—someone has to win out. You almost have to maintain a logical map of what team uses what tools as a precursor to prepare for a meeting with these business units. Not only is there no consistency in how applications are deployed, there’s also no consistency in how these different technologies are monitored.

For example, in the past, Netflix stated monitoring accounts for 30% of their infrastructure cost, and recently mentioned they’re planning to spend $1.9 billion on infrastructure in 2019. Think about the scale and complexity involved—they’re storing and analyzing the logs, behavior and metrics for systems supporting some 125 million subscribers.
Connecting Disparate Data Across Big Infra

So, how can you streamline and connect all of the data spread across fragmented tools and systems?

One solution is a data lake, a centralized repository that lets you funnel data into one place, so you have a holistic view of your infrastructure. In reality, big infra ends up spawning multiple data lakes that become siloed from one another.

You also likely have a square peg/round hole situation—data in one format needs to be transformed to another format before it can get into one of the data lakes.

This is where a monitoring tool becomes essential. Look for a monitoring tool designed to collect data in disparate data types and transform it into any number of formats, so you can set up an automated workflow to get data flowing from legacy systems (e.g., mainframes) alongside modern infrastructure like containers.

An example of this idea is with Sensu, and our support of the Nagios plugin spec and Prometheus exporter metrics (amongst many other metric formats). By using a monitoring tool that works with various metric formats, companies can plug the service checks they’re already using plus data from multi-cloud infrastructure into their monitoring setup and get valuable information about their systems.

A visualization tool such as Grafana is the icing on the cake. With Grafana, you can hook up data wherever it’s stored (e.g., Graphite, InfluxDB, Prometheus, etc.), visualize the data and display it on shareable graphs and dashboards. Using a monitoring tool as a data source for Grafana means companies can display monitoring incidents and inventory—and even mix that data with different data sources on the same Grafana dashboard. Combining a holistic monitoring solution with Grafana’s visualization capabilities gives a data-driven view of your infrastructure that you need—even if it remains a multi-generational, multi-siloed, multi-data-laked, 2,000-different-format-typed trail mix of big infra.


