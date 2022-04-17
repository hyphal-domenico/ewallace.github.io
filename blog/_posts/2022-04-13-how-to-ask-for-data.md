---
layout: news
title: "How to ask for data from a paper"
author: "Edward Wallace"
author_handle: "ew"
image: /assets/images/news/default-news.png
category: blog
tags: [papers, open science, riboviz]
---
{% include JB/setup %}


How should you go about asking for data from a published paper?

## The question

A student asked me (Edward Wallace):

> I would like some advice on how to approach a PI to ask for data from their paper. 
> For context, this lab's 2015 transcriptomics paper focused on up/down-regulated genes involved in lipid metabolism after stress. 
> I would like to look at expression changes in (my favourite pathway) specifically.
> I don't think her data is publicly available so would need to request it from her.

> I assume that PIs generally want something in return. If so, what should I offer her? 
> Would citing her paper and acknowledging her contribution be enough or do I have to offer her co-author in a paper if I use her data?
> As a PhD student, I feel like a nobody at the moment to be requesting precious data from another lab.
> Also I'm clearly clueless about academic politics

(posted with permission and minor edits)

I thought about this, which is very different from my perspective as a mid-career PI and open science advocate.
There aren't a huge amount of resources around to help.


## My views and values

My views on this are straightforward: sharing data is a basic requirement not a favour.
Sharing is almost certainly mandated by the [research funder's policies](https://www.dcc.ac.uk/guidance/policy/overview-funders-data-policies) and hopefully also by [the journal's policies](https://doi.org/10.7717/peerj.3208).
The proper way to acknowledge re-use of published data is citation, not co-authorship. 
For reasonable people, citation is fine, that increases the impact of their work while also assigning credit appropriately.

To be clear: asking for co-authorship to re-use published data, without any further intellectual contribution, would be a breach of research ethics.
Sometimes agreeing to a request for co-authorship might be the only way to get the data you need, but only as a last resort because it is not ok.


## What to do practically? 

I have asked for data accompanying publications many times, even when I was a lowly postdoc and PhD student. 
80% of the time, I am sent the data.

First double-check if the authors made the data available.
Check the "data availability" section of the manuscript.
Look on the authors' lab website.
Search the authors' names on archives appropriate to the data type.
For transcriptomic, genomic, or other sequencing or microarray data search on [GEO](http://ncbi.nlm.nih.gov/geo/) and/or [ENA](https://www.ebi.ac.uk/ena/browser/home).
Other archives with different scope are discussed in [public repositories episode, FAIR in biological practice lesson](https://carpentries-incubator.github.io/fair-bio-practice/13-data-repositories/index.html).
Maybe you'll find the data that you need in a format that you can use?
If so, your problem is solved.

However, the data might not be avaiable, or might be available only in a format that isn't useful.
You might need summaries but only the raw data are available, or the other way round.

Second, in that case, prepare a nice email to the author.
Say how much you enjoyed their paper, and if possible praise something specific in it. (That is just about being a good colleague - everyone loves hearing about the impact of their work regardless of whether they are being asked for anything.) 
Then say what you've said here, "I am working on (my favourite pathway) and I would like to look at changes in (favourite pathway) genes during stress in your published dataset from (citation to paper)." 
Ideally you would ask for data in some specific format that helps you, e.g. counts table or log-fold-change.
A reasonable and specific request is easy to say yes to.

It's good practice to check with your PI before you contact the author for their data.
Draft your email, run the email past your PI before sending, and cc them in on the external email.
This is about getting a second opinion and making sure everyone's in the loop.
It also gives a chance to discuss whether you *really* need that data or whether there's an even better option.

After the authors receive your nice email, they should send you the data.
They might ask you for a call to tell you about your work - say yes, that is good networking.
They might email the graduate student who generated the data asking them to send it, or have the data in a different format but not the format you need.
Basically, they should share the data.

Or the authors might not reply.
It's easier to assume that everyone is too busy, or on holiday or distracted, rather than anything else.
After 2 weeks, write to them again ultra-politely to check they received your initial email.

Alternatively there might be some ridiculousness.
The authors might refuse to share the data, or ask for co-authorship, or do something else unreasonable.
Exceptionally, there might be some reason for that, such as commercial or clinical confidentiality.
But generally scientific publication in the 21st century comes with a commitment to share the data.
That's a good idea too, because [sharing data is associated with increased citations](https://doi.org/10.1371/journal.pone.0225883).

In case of ridiculousness, the proper thing to do is to check the funder and journal data access statements and to reply quoting the parts that mandate data sharing.
This is "proper" but could be troublesome.
And [it might not work](https://doi.org/10.1371/journal.pone.0007078).
If the data are still not sent after reasonable request, your request could be escalated by writing to the journal, funder, and indeed to the university's research integrity office.
Sadly, that's a lot of effort to go to, to prove a point that is ethically sound but that might not win you friends or get you the data that you need.
And it would all be due to someone else not doing their job with integrity.


## Other resources

- [Quora gives basically the same advice, only concisely](https://www.quora.com/How-do-I-ask-the-authors-of-a-scientific-research-paper-to-share-the-data-and-source-code-they-used)
- [Eleven quick tips for finding research data, PLoS Computational Biology](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006038)
- [Why share your research data, The Open University](https://www.open.ac.uk/library-research-support/research-data-management/why-share-your-research-data)
- [Data sharing and how it can benefit your scientific career, Nature Career feature](https://doi.org/10.1038/d41586-019-01506-x)
- [FAIR in Biological Practice lesson](https://carpentries-incubator.github.io/fair-bio-practice/index.html)
