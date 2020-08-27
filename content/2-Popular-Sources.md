---
title: Popular Sources
nav: true
---

The assignment requires gathering information on consumers’ perceptions of your chosen subject. We will primarily use Academic Search Premier and CQ Researcher to find popular sources. 

# Academic Search Premier

Academic Search Premier is a multi-disciplinary database that contains full-text versions of thousands of publications, including academic titles, popular magazines, and newspapers. Since it covers nearly all fields of study, it's a good place to start a research project.

You can access Academic Search Premier from the [library’s homepage](https://www.lib.uidaho.edu/) under the catalog search bar. Once you log in with you UI credentials, you can type in your keyword search terms in the search box. For example, if your topic is *Use of bST (growth hormone) to increase milk production*, you can type bST in the search box and click the `Search` button. 

This search yields over 4,000 results. You may notice that most of the results are not relevant to our topic. Some of the results that came up when searching bST include Band Segmented Transmission, Behavior skills training, Barium Strontium Titanate, etc. Let’s revise our search strategy. 

This time spell out the abbreviation of bST, which stands for Bovine somatotropin. Since you are searching for the exact phrase, use quotation marks to wrap around the keywords by typing *Bovine somatotropin* in the search box, then click the `Search` button.

This search yields over 1,000 relevant results that include a mix of popular and scholarly sources. If you are only interested in popular sources for now, check the boxes for News and Magazines under Source Types on the left side of the screen. You may also change the Publication Date to limit the results to recent sources from the last few years. 

On the search results page, you can click the titles of the articles to access the abstracts and contents. The publishers and publication dates can be useful. For instance, since you are looking for sources that cover consumer’s perception of using bST to increase milk production, an article published by Consumers' Research Magazine or FDA Consumer would provide such perspective. If you are interested in reading about the topic with recent research, looking at articles published in the last few years would be appropriate; or, you can look at articles published in a span of ten or 20 years if you are interested in researching on a more holistic perspective of the topic and how the public opinion has changed over time.

Additionally, feel free to conduct a [CRAAP test](https://libguides.uidaho.edu/c.php?g=363237&p=2453602) to evaluate the sources based on various criteria.

Subjects is another field that is incredibly useful. Think of subjects as tags—information professionals categorize each information source based on what it is about—that an article may be related to the topic that you are interested in, but the keywords you used do not appear in the title or the content. For example, [this article](https://uidaho.idm.oclc.org/login?url=http://search.ebscohost.com/login.aspx?direct=true&db=f5h&AN=9610111153&site=ehost-live&scope=site) is about *bovine somatotropin*, but the language only included *bovine growth hormone* so a keyword search may not display this source. This is why searching with subject terms can be more reliable than with keywords.
Other relevant subjects include:
-	DRUG side effects
-	MILK yield
-	ANIMAL health
-	FOOD safety 
-	DAIRY industry 
-	HEALTH 
-	MILK consumption

Experiment with different combinations of subjects and see which ones work best for you needs.

Other useful features of Academic Search Premier include `HTML Full Text` and `PDF Full Text` on the search results page, and `print`, `email`, and `export` tools in the Tools panel on the search record page.

# Opposing Viewpoints

Opposing Viewpoints is another useful database to search for popular sources. The database includes topic overviews, pro/con viewpoint essays, thousands of podcasts (including premier NPR programs), etc. New reference content is added on an ongoing basis, and new full-text periodical and newspaper articles are added every day. Click this link to access [Opposing Viewpoints](https://go-gale-com.uidaho.idm.oclc.org/ps/dispBasicSearch.do?userGroupName=mosc00780&prodId=OVIC).

In the search box, type in your search terms (*antibiotics farms*, for instance). Under `SHOWING RESULTS FOR`, click `Viewpoints` to access viewpoint essays. Other useful content types include `Audio`, `News`, and `Magazines`.

# CQ Researcher

The CQ Researcher explores a single 'hot' issue in the news in depth each week. Topics range from social and teen issues to environment, health, education and science and technology. There are 44 reports produced each year including four expanded reports. Every 12,000-word report is written by an experienced journalist and features comments from experts, lawmakers and citizens on all sides of every issue. Numerous charts, graphs and sidebar articles -- plus a pro-con feature, a chronology, lengthy bibliographies and a list of contacts -- round out each report. Follow this link to access [CQ Researcher](https://library-cqpress-com.uidaho.idm.oclc.org/cqresearcher/index.php).

If your research topic is on *Organic vs. conventional farming*, click [this link](https://library-cqpress-com.uidaho.idm.oclc.org/cqresearcher/document.php?id=cqresrre2018110200) to access the full report. You can skim most of the article; the Pro/Con part may be the section that you are most interested in.

## Components Includes

`workshop-template-b` contains a series of [Liquid "includes"](https://jekyllrb.com/docs/includes/) to add basic [Bootstrap components](https://getbootstrap.com/docs/4.1/components/) to your Markdown content.
Examples below demonstrate the includes.

--------

#### Figures 

`{% raw %}{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}{% endraw %}`

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}

----------

#### Alerts

`{% raw %}{% include alert.md text="This is a Bootstrap [Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}{% endraw %}`

{% include alert.md text="This is a [Bootstrap Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}

-----------

#### Link Buttons 

`{% raw %}{% include button.md text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}{% endraw %}`

{% include button.md text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}

---------

#### Cards

```{% raw %}
{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.md text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}{% endraw %}
```

{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.md text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}

------------

#### Modal

`{% raw %}{% include modal.md button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}{% endraw %}`

{% include modal.md button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}

-------------

#### YouTube embed

`{% raw %}{% include video-embed.html youtubeid="SWVjQsvQocA" caption="Example video" %}{% endraw %}`

{% include video-embed.html youtubeid="SWVjQsvQocA" caption="Example video" %}
