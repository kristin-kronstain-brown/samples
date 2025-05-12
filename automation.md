# Automation samples

Take a look at these examples of topics that are automatically updated by daily automation.


## Markdown Enricher

[Github repo](https://github.com/IBM/md-enricher-for-cicd)

### Markdown Enricher features

- Install directly from a Github repo by using `pip install`.
- Establish downstream content locations sets to split the content into.
- Use HTML-style tags on characters, sections, or whole pages to certain locations.
- Allow content reuse.
- Include auto-generated [site maps](https://cloud.ibm.com/docs/instructlab?topic=instructlab-sitemap&interface=ui) for those that just prefer `CTRL+F` to search.
- Push output directly to Github branches or repositories.


### Why was the Markdown Enricher fun to create?

We used to have different Github branches as the source for different content locations. You had to either keep the branches completely in line with each other to use PRs to merge between them, make manual changes by copying back and forth, or be comfortable cherry-picking commits between the branches. 

By adopting the Markdown Enricher as a pre-processing step, we were able to single source content, keep the build processes we already had, simplify life for our content contributors (especially for those who were not full-time writers by trade), and get changes out faster to our customers than before. 

I loved being able to solve problems for my peers and myself in a practical, low cost, and low maintenance way.



## Link checker

I wrote a Python-based link checker for my documentation team. It's usage grew from our team of about 10 writers, to about 6 teams, then it was adopted as part of the automated checks for all IBM Cloud Docs. It was enabled in 381+ repositories and initially identified 10,521 links that required updates. Over 9 years, I have continued to refine its accuracy, speed, and capabilities.

### Link checker features
- Install directly from an IBM-internal repo by using `pip install`.
- Checks links in web pages, markdown, DITA, DITAMAPs, HTML, JSON, PDF, and YAML source files.
- HTTP links, marked-it style links used by IBM Cloud Docs, relative links used by standard markdown topics, anchors, and image links are checked.
- Redirect notifications are provided in the results as warnings. The redirect is also validated and can also be applied to the source topics automatically. 
- Checks all links, HTTP links only, peer links only (for links to other IBM Cloud Docs collections), or local links only.
- You can choose to provide Github credentials to check links to private repos and to minimize rate limiting.
- Define a list of links to check with Selenium when the `requests` module isn't getting a valid error code.
- Set ignore lists by source file type, `nofollow` attributes, or phrases in links.
- Results can be displayed in CSV, markdown, or JSON output.

### Why was the link checker fun to create?

The link checker was the first thing I ever wrote in Python in 2016. I am proud of how much it has improved over the years. It is a tool I frequently go back to, trying to increase its speed without sacrificing its accuracy.


Example CSV output:

![Link checker results](images/link-checker.png)






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