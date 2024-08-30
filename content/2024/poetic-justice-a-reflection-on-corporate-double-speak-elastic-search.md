---
author: "Stephen Gutekanst"
title: "[Poetic Justice] A reflection on corporate double speak (Elastic Search)"
date: "2024-08-29"
categories:
- tech
draft: false
images: []
description: "In case you missed it, 'Elasticsearch is open source, again' - announced in their latest blog post, using a weird writing style where every paragraph begins with [D.N.A], [LOVE.], [Not Like Us], and other Kendrick Lamar songs. I'll carry on their tradition and do the same I guess, in this reflection on corporate double-speak."
---

In case you missed it, ['Elasticsearch is open source, again'](https://news.ycombinator.com/item?id=41394797) - announced in their latest blog post, using a weird writing style where every paragraph begins with `[D.N.A]`, `[LOVE.]`, `[Not Like Us]`, and other Kendrick Lamar songs. _I'll carry on their tradition and do the same I guess._

_[Bitch, Don't Kill My Vibe]_ because I have no vested interest here; I don't use Elastic Search, it's not really my cup of tea - the product doesn't appeal to me - so I don't really care what happens to it as software. I'm more interested in the corporate double-speak in what they wrote, and their motivations for proclaiming to be 'open source' again.

> Open source is in my DNA. It is in Elastic DNA. Being able to call Elasticsearch Open Source again is pure joy.
> ...
> But being able to use the term Open Source, by using AGPL, an OSI approved license, removes any questions, or fud, people might have.
> ...
> We never stopped believing in Open Source at Elastic

_[Money Trees]_ don't grow in just any environment, they grow when you give out free apples, wait for people to bite, and once their stomach is full tell them it was poisoned and offer an antidote for a price. It's got to be painful that AWS' OpenSearch [product page](https://aws.amazon.com/what-is/opensearch/) paints their fork in such a shining light, proclaiming to be the saviors of open source because big-bad Elastic had to go and make their license proprietary. It _must_ feel joyful in such a circumstance to have found a potential outlet.

> 3 years later, Amazon is fully invested in their fork, the market confusion has been (mostly) resolved, and our partnership with AWS is stronger than ever. We were even named AWS partner of the year. I had always hoped that enough time would pass that we could feel safe to get back to being an Open Source project - and it finally has.

_[Hood Politics]_ sometimes means making friends with your enemies. For example, sometimes you lose the battle, and your enemy has a stronghold over the market where your product (no, not drugs, but your software) can be sold. Is it the [AWS Marketplace private offers of Elastic Cloud](https://aws.amazon.com/marketplace/pp/prodview-voru33wi6xs7k?sr=0-1&ref_=beagle&applicationId=AWSMPContessa)? I don't know, but I do know that many companies allocate budget to AWS - and requesting new budgets is _tough_ - so sometimes if you can buy _other things_ using your pre-allocated AWS budget ... it makes things simpler. I guess if you do well enough, you could even become partner of the year. The big guy in the room doesn't care, he gets his cut both ways.

> we are simply adding another option [AGPL], and not removing anything

_[Vanity Slaves]_ Adding another option _does_ mean you can _factually_ proclaim to be open-source according to the OSI definition. You got all the checkboxes checked, you did it right, you are open source, I agree. But we wouldn't want any enterprise customers misreading 'we're now open source' as 'we maybe don't need to renew our enterprise license' or thinking 'we can't use AGPL!', would we? Good call adding this clarification that _the other licenses_ are also available.

> We chose AGPL, vs another license [..] Heck, maybe AGPL is enough for infrastructure software like us with how things have progressed since we had to change the license (for example, Grafana who moved to it from Apache2). We are committed to figure it out.

_[Still Hustlin]_ is how I imagine the Google Docs comments reviewing this public statement looked: 'the key point to drive home with this paragraph is we want Elastic to be considered Open Source, we want the developer sentiment boost which comes with that, we _want_ to be able to tell people we're giving away our amazing software because we're amazing. [but we also need to get paid]'

> With any change, there can be confusion, and, of course, there can be trolls. (Aren’t there always trolls?)

_[Bitch I'm in the Club]_ that's me I guess! sorry?

> “AGPL is not true open source, license X is”: AGPL is an OSI approved license, and it's a widely adopted one. [...] MongoDB [...] Grafana [...] AGPL doesn’t affect usage or **popularity.** 

_[Hol' Up]_ is that [_literally_ me](https://news.ycombinator.com/item?id=41276315)? fuck! In that case, I'll get a bit serious: I don't think there is anything wrong with Elastic, Mongo, Grafana, or whatever using AGPL. By all means, it's your software, your license, do as you please. But I think the spirit of the article titled 'Elasticsearch is open source, again' is to convey that things have returned to _how they once were_. **But wait, wasn't Elastic Apache licensed before?** - why the change to AGPL then?

_[You Ain't Gotta Lie (Momma Said)]_ the truth is that there are two types of people looking for 'open source': you've got the OSI who defines Open Source and says AGPL is Open Source (and, Elastic, again, you've got those checkboxes checked - congrats you are open source!) But, if I had to speculate, one of the values of Elastic being 'open source' before was that someone could go to their boss and say 'yo, this tool is great, let's use it' and not need to procure a license for it from you? Like 'use it my preferred way' style. Unfortunately, with AGPL (almost certainly as your lawyers advised you) [is a non-starter for most companies](https://opencoreventures.com/blog/2023-10-agpl-license-is-a-non-starter-for-most-companies/) and is outright banned by most legal departments for use within companies. The answer to that employee would most certainly be 'we cannot use that software unless we contact our procurement team to get a license from their sales team' - but I'm sure you know that, because that is indeed basically [the business strategy of companies like Grafana and other infrastructure companies that you refer to](https://news.ycombinator.com/item?id=41396278).

> “Elastic changes the license because they are not doing well” - I will start by saying that I am as excited today as ever about the future of Elastic. I am tremendously proud of our products and our team's execution. We shipped Stateless Elasticsearch, ES|QL, and tons of vector database/hybrid search improvements for GenAI use cases. We are leaning heavily into OTel in logging and Observability. And our SIEM product in Security keeps adding amazing features and it's one of the fastest growing in the market. Users' response has been humbling. The stock market will have its ups and downs. What I can assure you, is that we are always thinking long term, and this change is part of it.

_[These Walls]_ are closing in, I've seen [that graph](https://news.ycombinator.com/item?id=41397398) showing how OpenSearch is closing in and eating all your new installs. That's fucking scary, I don't envy you - I have sympathy - best of luck to you adding the differentiation features to make your product uniquely valuable again. I do think that's the right move for yourself.

![](/img/2024/elastic.jpg)

[United in Grief] I think it's unfortunate and regrettable how conflated the term 'open source' has become. Is Elastic not being 'OSI-approved open source' a good reason for people to switch to OpenSearch? I don't think so. Is it wrong that Amazon can take some code you gave away for free, under permissive terms in hopes of gaining popularity, and sell it to their customers? I also don't think so.

[I Am] just a bit frustrated by the double-speak, I understand why you have to do it, I just wish you didn't have to. I wish you could be honest about what the license actually is ('you can see our code and contribute to it, but to use it in a company you must purchase a license') or just declare it closed-source like some other companies I've seen (_cough_) rather than having to hide behind lucrative knowledge of how enterise customers' legal teams will scoff at the idea of Elastic being AGPL software.. just so that they can tell your users to go talk to their procurement team if they need it so you can get sales. That's so many weirdly convoluted layers to go through (oh god, did I say convoluted layers?) and when I read seemingly hidden agendas, veiled proclaimations of being 'the good guys', and quirky-fun ways of writing public statements with Kendrick Lamar songs as openings - I sometimes feel like _I am the one_ who should be [Institutionalized]. Blegh!

[YAH.] that's all. No harm or malice to ya'll intended, just some genuine criticism of our world and your role in it. Also this is my 💩 thoughts feed, I am a clown and shouldn't be taken seriously.
