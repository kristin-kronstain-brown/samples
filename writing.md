# Writing samples for Kristin Brown

Take a look at these samples.



## Getting started with AI

My introduction to large-language modeling for AI has been through writing documentation for the Red Hat AI InstructLab on IBM Cloud. The service makes it possible to generate synthetic data and models from QNA files as part of a taxonomy. 

With a service like this, there must be balance. We want to make the purpose and value of the service clear. But we don't want to over-document the capabilities of InstructLab. Red Hat has its own documentation for that. We don't want to over-document what you do with the model. There are other services to deploy the model in with their own documentation. So context is so important to keep in mind in each topic, though especially in the Getting Started topic.

View the topic: [https://cloud.ibm.com/docs/instructlab?topic=instructlab-getting-started](https://cloud.ibm.com/docs/instructlab?topic=instructlab-getting-started&interface=ui)

![Red Hat AI InstructLab on IBM Cloud](images/instructlab-gs.png)



## Strategy for high availability

Use cases for a service can be varied. You might have users just perusing, looking to understand what a service is capable of. But then you might have subject matter experts who are looking for intricate details of the architecture. Conceptual topics are a great delivery system for information that bridges the gaps between those user experiences. 

With the IBM Cloud Kubernetes Service, users have a high degree of flexibility in the setup of their Kubernetes clusters. This flexibility can give them a sense of ownership, but it can also allow them to make short cuts that aren't always in their best interest. I consolidated many best practices around high availability and disaster recovery into a topic that helps guide users through the process of establishing a strategy for cluster management. 

Each section of this topic is a decision point for the cluster admin to make, including recommendations to lead them toward best practices.

View the topic: [https://cloud.ibm.com/docs/containers?topic=containers-strategy](https://cloud.ibm.com/docs/containers?topic=containers-strategy)

![IBM Cloud Kubernetes Service cluster strategy topic](images/iks-cluster-strategy.png)



## FAQ

I wrote many of the IBM Cloud InstructLab Service FAQ entries. I added several entries around billing this year. Billing can be a tricky area to write about. The information must describe how costs are calculated, but without providing concrete numbers. IBM has separate pricing calculators for that, so we must avoid potentially providing information that could conflict. 

View the topic: [https://cloud.ibm.com/docs/instructlab?topic=instructlab-faq](https://cloud.ibm.com/docs/instructlab?topic=instructlab-faq)

![IBM Cloud InstructLab Service FAQ](images/faq.png)



## Responsibilities

I worked with a distinguished engineer to develop the original version of the Responsibilities topic. Though the idea for the topic was his, we worked together to find the right level of detail to describe what IBM's service maintenance responsibilities were versus what the customer responsibilities were. 

As we worked on the topic, I continually considered how we were making the service and IBM look.
- Are we accurately representing the information?
- Are we making it visually obvious that IBM holds the majority of the responsibilities, making this a marketing opportunity? 
- Can the customer can clearly understand which pieces they are responsible for and navigate to information about those pieces?

We got positive feedback on the high-level clarity that the information brought to the users. Eventually, this topic became a standard in IBM Cloud Docs and is used in many of its services.

View the topic: [https://cloud.ibm.com/docs/containers?topic=containers-responsibilities_iks](https://cloud.ibm.com/docs/containers?topic=containers-responsibilities_iks)

![IBM Cloud Kubernetes Service responsibilities](images/responsibilities.png)



## Release notes

Though release notes might not take a lot of skill to put together, timeliness is an important part of information development. A new feature cannot be considered delivered if users don't know it's there. 

I use agile methodologies to meet deadlines and automation wherever possible to make updates to production content in a timely manner. 

View the topic: [https://cloud.ibm.com/docs/containers?topic=containers-containers-relnotes](https://cloud.ibm.com/docs/containers?topic=containers-containers-relnotes)

![IBM Cloud Kubernetes Service release notes](images/release-notes.png)



## Troubleshooting

For the IBM Cloud InstructLab Service troubleshooting docs, I was given the following information from development.

```
Failed to read secret data from secrets manager. Double check the authorization policy and that the secret exists.
```

I turned that information into the following topic.

![Secret data troubleshooting topic](images/secret-data.png)



## Markdown Enricher docs

I developed a Python-based CI/CD pre-processing tool for markdown. Our team needed to single-source markdown files, share them across services, and deliver them to different downstream public and enterprise Github repositories. It includes content parsing, a variety of content validation steps, and  both CLI and API calls for failover attempts to deliver the files.

Though this documentation is maintained and developed internally at IBM, the Markdown Enricher is used to provide a subset of the documentation externally.

Markdown Enricher documentation in Github pages:
[https://ibm.github.io/md-enricher-for-cicd](https://ibm.github.io/md-enricher-for-cicd/#/)