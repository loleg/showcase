---
datapackage:
  title: Community Showcase 2024
  description: The Opendata.ch/2024 Forum is Switzerland’s leading conference on open data and data use in the public interest. We feature a small selection of projects from hackathons, community events and social media. Here we package the data of our showcase.
  created: 2024-05-24
  updated: 2024-05-27
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  sources:
  - path: https://showcase.opendata.ch/api/event/3/projects.csv
    title: Dribdat API
  resources:
  - name: dribdat-2024
    title: 2024 Showcase
    description: Dribdat Export of projects from the 2024 Showcase
    lastModified: 2024-05-27
    path: dribdat-2024.csv
---

The [Opendata.ch/2024 Forum](https://opendata.ch/2024) is Switzerland’s leading conference on open data and data use in the public interest. On 24 May, our 14th conference will bring together experts and enthusiasts from government, research, business, and civil society at the University of Fribourg to ignite discussions, network and learn from each other. Don’t miss your chance to shape the future of data in Switzerland. We will feature a small selection of projects from hackathons, community events and social media, at the annual Forum.

# Overview

Projects were nominated by the Opendata.ch team, and submitted on location by participants. They were added to Dribdat to put all the information in one place. 

Dribdat aggregates data from other Dribdat instances, GitHub and other repositories, using the Sync feature. This way we were able to very quickly build a showcase that contains rich data, which is evidence that work has been done on these projects.

In this Data Package, we would like to see an overview of the work that was involved in developing these use cases. It would be nice to add a graph showing the relative number of people, event length and total activities of the projects.

# Data format

Dribdat natively supports the [hackathon.json format](https://schema.org/Hackathon), which should be the basis for the table schema in this data package as well. 

Some more details on Dribdat's web services can be found in the [API guide](https://dribdat.cc/contribute.html#api-guide).

An application that reads the Dribdat format to visualize project boards can be found at [Backboard](https://github.com/dribdat/backboard).

# Visuals

<Iframe
  data={{
    url: 'https://showcase.opendata.ch/event/3?embed=1'
  }}
  style={{
    height: '320px',
    width: '100%'
  }}
/>

_Embedded visualization of the Dribdat project grid_

![](https://cdn.fosstodon.org/media_attachments/files/112/495/862/687/690/349/original/fc27e1e48d246a32.png)

_Screenshot of the digital showcase by [@loleg](https://fosstodon.org/@loleg/112495874861545709)_

![[https://cdn.fosstodon.org/media_attachments/files/112/495/936/705/743/259/original/e66b05e40e4b5a7a.jpg]]

_Photo of the physical showcase by [@loleg](https://fosstodon.org/@loleg/112495939202174047)_


