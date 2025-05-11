# Automation samples

Take a look at these examples of topics that are automatically updated by daily automation.


## Markdown Enricher

[Github repo](https://github.com/IBM/md-enricher-for-cicd)


## Link checker

I wrote a Python-based link checker for my documentation team. It's usage grew from our team of about 10 writers, to about 6 teams, then it was adopted as part of the automated checks for all IBM Cloud Docs. It was enabled in 381+ repositories and initially identified 10,521 links that required updates. Over 9 years, I have continued to refine its accuracy and add enhancements.

Link checker features:
- HTTP links, marked-it style links used by IBM Cloud Docs, relative links used by standard markdown topics, anchors, and image links are checked.
- Redirect notifications are provided in the results as warnings or they can be applied to the source topics automatically. 
- Results can be displayed in CSV, markdown, or JSON output.

![Link checker results](images/link-checker.png)


## Site maps



[Example site map](https://cloud.ibm.com/docs/instructlab?topic=instructlab-sitemap&interface=ui)


## Topic updates

These are examples of topics that are automatically updated by pulling data from the IBM Cloud Kubernetes Service API.

### Cluster flavors

![Cluster flavors](images/cluster-flavors.jpg)

### Cluster add-on versions

![Cluster add-on versions](images/add-on-versions.jpg)

### Region availability for service resources

![Locations](images/locations.png)

### Supported operating system versions

![Operating systems](images/os.jpg)


### Change logs

![Change logs](images/changelogs.jpg)