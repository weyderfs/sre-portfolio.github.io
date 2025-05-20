# My Portfolio

## A Bit About My Story

<p align="center" width="100%">
    <img width="60%"src="https://github.com/weyderfs/sre-portfolio/blob/main/assets/asset01.jpg?raw=true" />
</p>

Hello, I'm Weyder. I come from a humble background, and I started working with IT in 2007, while still in my teens, after an uncle gifted me a Computer Assembly, Maintenance & Networks course at a Microlins unit in my city. Until then, I didn't imagine I would become an IT infrastructure professional; I dreamt of being an automotive mechanic. But while taking the courses, I fell in love with it, as I started understanding how a computer worked from _hardware_ to _software_ and then communication networks.

## Academic Career

In 2011, already an adult, I left my hometown and went to college in a bigger city. I started with Computer Engineering, but after a year of much struggle and reflection, I concluded it wasn't for me. I also didn't want to study Computer Science; my passion was Infra and Hardware. Since I was already working as an Infrastructure Analyst, I opted for a quicker and more focused degree in IT Management, and it was indeed the best choice I made for my career.

## Career Transition

Around 2012, I started getting interested in Linux operating systems, initially only for server use. But from 2015 onwards, I adopted it as my main operating system for daily use and work. It was also at this time, after taking a preparatory course for the Linux LPIC-1 certification, that I shifted my career focus from Microsoft environments to Linux environments and Computer Networks.

In 2015, I completed my degree in IT Management and continued studying in certification preparation courses like LPIC-2 and the old Cisco CCENT, always seeking my professional development.

## First Certification

In 2016, I obtained my first Linux certification, [LPIC-1](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview), which consists of two exams: 101-500, which I aced, and 102-500, where I scored over 85%. I am still grateful to my teacher Fernando for the excellent classes he gave at Senac.

<p align="center" width="100%">
    <img width="60%"src="https://github.com/weyderfs/sre-portfolio/blob/main/assets/lpic1.png?raw=true" />
</p>

Afterward, I started preparing for the [LPIC-2](https://www.lpi.org/pt-br/our-certifications/lpic-2-overview) certification and was also finishing my Cisco CCENT course.

## A New Career Shift

Around 2015, the DevOps culture movement started gaining strength in Brazil, heavily driven by the Cloud computing "boom" in the country. At that time, I already saw migrating to this segment as the future of my career. Since I had already gained good experience in Linux environments, starting to study Docker containers, Infrastructure as Code with Terraform at the time, and AWS as a cloud provider wasn't too complex.

In 2016, given the crisis that occurred in the Brazilian political scenario, it became necessary for me to start entrepreneurship. I opened my first company and began providing consulting services, managing company environments, participating in environment and network migration projects, selling equipment, etc.

In 2018, I moved to another city again and also changed my professional focus, definitively shifting from working in mixed environments to working as a Linux Specialist, focusing on Linux Servers, Network Security, and Cloud. I was always studying modern technologies and tools used in the DevOps culture. This year, I also got my first DevOps Essentials certification.

In 2019, after much study, I got my first job as a Cloud Infrastructure Analyst with a focus on DevOps Culture. Many challenges arose, as I now genuinely started dealing with entirely Cloud AWS environments and tools like Kubernetes, Terraform, among others, which built the professional experience that brought me to where I am professionally today.

In the same year, I obtained my second DevOps Professional certification and also completed a Kubernetes preparatory course for the CKA.

# Fun Facts :thinking:

- I like motorsports, cars, and I'm occasionally a Kart driver.
- I'm a musician; I took a popular keyboard course and graduated, there was even a CD recording.
- I like games and collect old video games.
- I have a YouTube channel called [OPS Talks](https://youtube.com/@opstalks).
- I like the Financial Market and Investments.
- I am a volunteer and responsible for the Technology part of [Instituto Social Biss](https://institutobiss.com.br).

# Skills :books:

* **Languages:** Shellscript, Python
* **Frameworks/Libraries:** FastAPI
* **Tools:** Kubernetes, Terragrunt, Terraform/OpenTofu, Git, Docker, Prometheus, Grafana, Datadog, Elastistack, etc.
* **Cloud:** AWS, Google Cloud
* **Databases:** SQL, NoSQL (MongoDB, PostgreSQL, MySQL, etc.)
* **Others:** Agile Methodologies (Scrum, Kanban), Jira.

# Projects

## Forger

During my studies with [Fast API](https://fastapi.tiangolo.com) and [SQL Model](https://sqlmodel.tiangolo.com), I needed to have mocked fake data. However, it's not always easy to find a dictionary exactly in the model you need. Given this, I decided to create Forger, a solution that generates a mass of data for you.

- **Repository**: [GitHub](https://github.com/Ops-Talks/forger)
- **Technologies**: [Python](https://python.org), [Typer](https://typer.tiangolo.com), [Poetry](https://python-poetry.org), and [Faker](https://faker.readthedocs.io/en/stable)


## TGEnv

To handle multiple versions of Terragrunt used in the environment during the growth of IaC, the TGEnv tool emerged. It was initially created and maintained by another person in the community, but it eventually ceased to be maintained and no longer receives updates.

To prevent it from becoming orphaned and to continue its maintenance, I posted in the community at the time to see if there was interest in continuing to maintain it through a GitHub fork. New interested parties soon appeared, and today I maintain it along with other community members.

- **Repositories**: [GitHub](https://github.com/Ops-Talks/forger)
- **Technologies**: [Shell](https://pt.wikipedia.org/wiki/Shell_script)


## Terraform/OpenTofu Modules Developer

With the skills I acquired working with IaC, I felt a strong need for standardization and module creation for daily work. And since I believe in the power of Open Source Software, I also make my modules available to the community:

### Modules for AWS

<p align="left" width="100%">
    <img width="10%" src="https://github.com/weyderfs/sre-portfolio/blob/main/assets/aws01.png?raw=true" />
</p>

* **Repository:** [GitHub](https://github.com/weyderfs/terraform-aws-modules)
* **Technologies:** [Terraform](https://developer.hashicorp.com/terraform)/[OpenTofu](https://opentofu.org), [AWS Provider](https://github.com/hashicorp/terraform-provider-aws)

### Modules for Datadog

<p align="left" width="100%">
    <img width="10%" src="https://github.com/weyderfs/sre-portfolio/blob/main/assets/dd01.png?raw=true" />
</p>

* **Repository:** [GitHub](https://github.com/weyderfs/terraform-datadog-modules)
* **Technologies:** [Terraform](https://developer.hashicorp.com/terraform)/[OpenTofu](https://opentofu.org), [Datadog](https://www.datadoghq.com), Observability.

### Modules for Spot IO

<p align="left" width="100%">
    <img width="18%"src="https://github.com/weyderfs/sre-portfolio/blob/main/assets/spot01.png?raw=true" />
</p>

* **Repository:** [GitHub](https://github.com/weyderfs/terraform-spot-modules)
* **Technologies:** [Terraform](https://developer.hashicorp.com/terraform)/[OpenTofu](https://opentofu.org), [Spot](https://spot.io), FinOPS

### Modules for Database Engines

<p align="left" width="100%">
    <img width="50%"src="https://github.com/weyderfs/terraform-db-modules/raw/master/assets/logo.png" />
</p>

* **Repository:** [GitHub](https://github.com/weyderfs/terraform-db-modules)
* **Technologies:** [Terraform](https://developer.hashicorp.com/terraform)/[OpenTofu](https://opentofu.org), [MySQL](https://www.mysql.com), [MariaDB](https://mariadb.com), [Postgres](https://www.postgresql.org), and [MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-database)

## Contact 🔛

- [**LinkedIn**](https://linkedin.com/in/weyderfs)
- **Email:** weyderfs@gmail.com
- [**OPS Talks on YouTube**](https://youtube.com/@opstalks)
- [**OPS Talks Newsletter**](https://opstalksit.substack.com)

---

[Back to Home](https://github.com/weyderfs/sre-portfolio/tree/main) | [View in Portuguese](https://github.com/weyderfs/sre-portfolio/tree/pt-br)