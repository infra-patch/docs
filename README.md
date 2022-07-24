
![logo.infrapatch.com](https://logo.infrapatch.com/1/cover.png)

# [Dokumentacja - docs.infrapatch.com](https://docs.infrapatch.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/DOCS/MENU.md) 

+ [Strona informacyjna: www.infrapatch.com](https://www.infrapatch.com/)
+ [Logotyp: logo.infrapatch.com](https://logo.infrapatch.com/)
+ [Przykłady - examples.infrapatch.com](http://examples.infrapatch.com)

+ [LICENSE](../LICENSE)



## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/ABOUT/ABOUT_EN.md)

Infra Patch Manager

A tool which helps to maintain the remote infra patching.
There is a scenario, a distributed system is running on multiple servers.
Repeated activity will be performed to logging in each and every server's application to apply the scenario of changes.

WHat can he do for you?
+ upgrade:
    + system
    + apps
+ change
    + config
    +
+ check and repair bugs
    + on server
    + dns records
    + name server with API to registrar

it helps to maintain an upgrade at centralized place and apply at required destination with help of few scenarios.


You like [**InfraPatch**](http://www.infrapatch.com/)?  
[![Github](https://img.shields.io/github/followers/tom-sapletta-com?label=Follow&style=social)](https://github.com/tom-sapletta-com)

Support it via GitHub Sponsors:

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4-lightgrey?style=social&logo=GitHub)](https://github.com/sponsors/tom-sapletta-com)  
[![One-Time Donation](https://img.shields.io/badge/One--Time%20Donation-$1-lightgrey?style=social&logo=GitHub)](https://github.com/sponsors/tom-sapletta-com?frequency=one-time&sponsor=tom-sapletta-com#sponsors:~:text=%241%20one%20time)


👋 All examples are rendered through one run in shell, supported languages:
+ **sh/bash** + **php** + **js** + **java** + **groovy**


👋 Run Your code on remote server, supported environments:
+ **Docker** + **kubernetes**


👋 Use an external API:
+ **github** + **gitlab** + **cloudflare** + **digitalcloud**


[Sourcecode](http://bash.infrapatch.com/) - [Usecases](http://examples.infrapatch.com/) - [Documentation](http://docs.infrapatch.com/) - [Roadmap](http://roadmap.infrapatch.com/) -  [Offer](http://offer.infrapatch.com/)


## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/ABOUT/ABOUT.md)

infrapatch służy do naprawiania niedziałających elementów infrastruktury
wedle schematu dopasowanego do typu awarii czy usterki.

### Jakie problemy można rozwiązać dzięki rozwiązaniu infrapatch?

#### Certyfikaty SSL
Częstym problemem dla firm utrzymujących własną domenę jest aktualizowanie certyfikatu SSL
Jest to tym trudniejsze im więcej stron www i subdomen musimy monitorować.

#### Rekordy NS domeny 
Problemy dotyczące ustawień rekordów domen, to często proste rzeczy, typu:
+ zmiana nameserwera
+ rekordu w DNS
+ przekierowanie...

Wszystko jest łatwiejsze, gdy posiada się jeden serwer i domenę u tego samego providera, gdzie
można uzyskać fachową pomoc supportu.

Wraz ze wzrostem organizacji i rozbudową infrastruktury, trudno wszystko ustawić w jednym panelu i u jednego usługodawcy.
Trzeba się zalogować na kilka platform i wiedzieć co jak ustawić a to kosztuje czas...

#### Outsourcing DevOps

Zapewniamy równiez specjalistę d/s bezpieczeństwa i związanym z tym zapotrzebowaniem na dorywcze zlecenia lub stały outsourcing
głównie na błedach infrastryuktury


## Korzyści
Możliwość naprawiania błędów, niezależnie od platformy, w sposób pół automatyczny
nie potrzebny jest kontakt z klientem,
wystarczy wykrycie i akceptacja, wyrażenie chęci naprawy.
pojawia się błąd, naprawiamy.





## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/CONTRIBUTION.md)

### Update

apifork
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
./apifork update
```

apipackage
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
./apipackage update
```

### Remove


apifork
```bash
./apifork remove
```

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```


Install package list after created project
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
echo "https://github.com/letwhois/bash apidsl/apidsl/bash letwhois" >> "apipackage.txt"
./apipackage install
```

Edit documentation with flatedit
```bash
echo '#!/bin/bash' > 'readme'
echo './flatedit/readme.sh readme.txt' >> 'readme'
echo "./DOCS/MENU.md" >> "readme.txt"
echo "./DOCS/ABOUT.md" >> "readme.txt"
echo "./DOCS/FOOT.md" >> "readme.txt"
```

### Update documentation

```bash
 ./readme
```

### Config project file

The config file: **.apifork** can be another, e.g. **apifork.txt**

Just change the first line in  **.apifork** on **apifork.txt**
```bash
apifork.txt
```


### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```

### update

```bash
./apifork update
```


### remove

```bash
./apifork remove
```


## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/DOCS/TODO.md)


echo "UPDATE: infraMonit.com"
echo "UPDATE: grabWhois.com"
echo "UPDATE: ApiPong.com"
echo "UPDATE: AirScanning.com"
echo "UPDATE: MultiSiteMap.com"


install
https://github.com/infra-patch/ultimate-nmap-parser

skanuje hosty
git clone https://github.com/desecsecurity/parsing_html_bash
./parsing_html.sh www.google.com


+ skrypty do detekcji
+ skrypty do naprawy
+ schematy naprawy / template w zalezności od sytuacji



## Infrastructure [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/ABOUT/INFRA.md)

The growing complexity of today’s IT reality is indisputable: Software is becoming more complex, and the infrastructure it runs on is equally so. This complexity comes, in part, from adding layers upon layers to the infrastructure we manage—from bare metal servers to VMs to containers to function-based computing—and from how quickly we cycle in new technologies and how slowly old technologies are cycled out.


### infrastructure

Ephemeral and multi-generational infrastructure (often side by side) are the new normal.
Old and new technologies co-mingle, and while new technologies may be shiny and exciting, 
they quickly become ordinary as the next new thing comes along.

Here’s a sobering stat: In Q4 2017, IBM’s mainframe business grew by 32%. So even while cloud,
AI and security initiatives are on the rise at IBM, mainframes sustain a bulk of their business. 
Old tech perseveres, and we have to find new solutions to bridge the gap between old and new.




### What Qualifies as Big Infrastructure?

The hodgepodge of technologies—and the challenges they bring—are compounded further when we’re talking about big infrastructure.

For the purpose of this discussion, big infra is an organization that has been around for at least 10 years.
That means they’ve had success, they’ve grown and their infrastructure has grown along with them, 
and the technologies at play have expanded as well.

Your organization’s exact age, size and revenue aren’t particularly material; 
what matters is you’ve had enough time to accumulate resources, people,
practices and technologies to create what I think of as a trail mix problem—basically enough legacy infrastructure to start creating problems.
The Challenges of Big Infrastructure


### The challenges

#### Grwoth

The challenges of big infra stem from the technology itself and from the way people use that technology. 
As an organization grows, its teams often become larger and more siloed, and departmental goals become disconnected. 
Even when working toward the same goal, departments diverge in their methods for reaching that goal.

#### Time

Now, add tools and technology to the mix: Over time, teams choose tools they prefer,
or build their own, which works out okay for a while until they have to collaborate with another department that uses different tools and a completely different set of practices.

#### Culture

Now, add in different work styles and personality types and company politics, 
and everything gets tangled up fairly quickly. Trying to keep track of who’s using what, how they’re using it and what’s working (or not) is no easy task.

#### Customer

One customer, for example, had one team using Chef and was all in, and were trying to get buy in from other teams as well, but 
there was another team that was early days Docker, hand rolling Docker hosts, and didn’t want to adopt Chef.

#### Environment

+ Docker
+ Puppet
+ Kubernetes

Then there was a different team who was early days Kubernetes and didn’t want to use Docker, and yet another team using Puppet. 
Once they had to work with each other, things broke down—someone has to win out. You almost have to maintain a logical map of what team uses what tools as a precursor to prepare for a meeting with these business units. Not only is there no consistency in how applications are deployed, there’s also no consistency in how these different technologies are monitored.

#### Example

Netflix stated monitoring accounts for 30% of their infrastructure cost, and recently mentioned they’re planning to spend $1.9 billion on infrastructure in 2019. Think about the scale and complexity involved—they’re storing and analyzing the logs, behavior and metrics for systems supporting some 125 million subscribers.


### Big Infra

Connecting Disparate Data Across Big Infra

So, how can you streamline and connect all of the data spread across fragmented tools and systems?

One solution is a data lake, a centralized repository that lets you funnel data into one place, so
you have a holistic view of your infrastructure. 
In reality, big infra ends up spawning multiple data lakes that become siloed from one another.

You also likely have a square peg/round hole situation—data in one format needs to be transformed to another format before it can get into one of the data lakes.

This is where a monitoring tool becomes essential. 
Look for a monitoring tool designed to collect data in disparate data types and transform it into any number of formats, 
so you can set up an automated workflow to get data flowing from legacy systems (e.g., mainframes)
alongside modern infrastructure like containers.

## Monitoring

By using a monitoring tool that works with various metric formats, companies can plug the service checks they’re already using plus data from multi-cloud infrastructure into their monitoring setup and get valuable information about their systems.


### Tools

 
+ Puppet
+ Rancher

Metrics:
+ Prometheus
+ Nagios
+ Sensu
+ Graphite
+ InfluxDB
+ Prometheus
+ Inframonit
+ Infrapatch

#### Grafana

A visualization tool such as Grafana is the icing on the cake. 

With Grafana, you can hook up data wherever it’s stored (e.g., Graphite, InfluxDB, Prometheus, etc.),
visualize the data and display it on shareable graphs and dashboards. 
Using a monitoring tool as a data source for Grafana means companies can display monitoring incidents and inventory—and even mix that data with different data sources on the same Grafana dashboard. Combining a holistic monitoring solution with Grafana’s visualization capabilities gives a data-driven view of your infrastructure that you need—even if it remains a multi-generational, multi-siloed, multi-data-laked, 2,000-different-format-typed trail mix of big infra.




---

+ [infra-patch/docs](https://github.com/infra-patch/docs)
