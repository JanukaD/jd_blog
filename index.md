---
layout: default
title: Home
nav_order: 1
permalink: /
---

<style>
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
  border: 2px solid #dddddd;
}

td, th {
  border: 2px solid #dddddd;
  text-align: left;
  padding: 8px;
  background-color: #a28cb8;
}

tr:nth-child(even) {
  background-color: #a28cb8;
}
</style>

# Bug Zero Support Site
{: .fs-9 }
        
Welcome to Bug Zero Support Site!
{: .fs-6 .fw-300 }

This is where you can get familiar with Bug Zero and explore our
product features. We provide some tips here that you might find
useful. This site is open to all and we welcome your feedback!
{: .fs-4 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/scorelab/bugzero-supports){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### Who are we?

We, at Bug Zero provide end to end support for every bug bounty programs.

If you are a hacker and want to learn more about the security vulnerability ecosystem, we provide 
a platform to learn security by testing real-world systems while earning money for 
security bugs you find. We also provide essential security training materials to help 
become a renowned infosec professional.

If you are an organization that has sensitive information to guard and no internal 
staff to find security bugs (vulnerabilities), you can use Bug Zero to hire infosec 
professionals and only pay for what they find.

### Choose which tab you’d like to explore for more details.

<table><tr>
<th><center>For Hackers</center></th>
<th><center>For Organizations</center></th>
</tr>
<tr>
<td><a href="{{ site.url }}{% link docs/hacker-support/hacker-support.md %}"><img src="assets/images/image_hack.png" alt="hacker" width="400"/></a></td>
<td><a href="{{ site.url }}{% link docs/organization-support/organization-support.md %}"><img src="assets/images/image.png" alt="company" width="400"/></a></td>
</tr></table>

### How to Contribute?

When contributing to Bug Zero Documentation repository, please first discuss the change you wish to make via issue with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/scorelab/bugzero-supports/blob/master/README.md).

#### Thank you to the contributors of Bug Zero Documentation!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

[//]: # ### Code of Conduct

[//]: # Just the Docs is committed to fostering a welcoming community.

[//]: # [View our Code of Conduct](https://github.com/scorelab/bugzero-supports) on our GitHub repository.
