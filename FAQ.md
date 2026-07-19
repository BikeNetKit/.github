# BikeNetKit FAQ
Frequently asked questions about BikeNetKit.

## Why does BikeNetKit exist?
BikeNetKit exists for an ultimate and for a practical reason. 

Ultimately, most cities on the planet do not offer infrastructure for safe cycling, at least no [*functional*](#when-is-a-bicycle-network-functional) infrastructure, despite the latent demand of many people who want to do so. Enabling people to cycle has massive societal benefits from environmental to public health. Increasing cycling while reducing the harm by cars is also the most effective approach to tackle fundamental issues in mobility and urban planning, [much more than "solutions" pushed by corporate interests like electric cars](https://theconversation.com/cycling-is-ten-times-more-important-than-electric-cars-for-reaching-net-zero-cities-157163).

Practically, BikeNetKit exists because since 2019 [we have pioneered a *Science of Bicycle Networks*](#what-is-your-expertise-on-the-topic), developing several computational approaches to growing or fixing bicycle networks as support tools for urban planners. However, these algorithms were part of research projects and thus not user-friendly nor maintained, therefore not usable for this purpose in practice. In 2025, we won a grant to change this, by turning our raw algorithms into user-friendly software called *BikeNetKit*.

## What is the goal and philosophy of BikeNetKit?
The goal of the BikeNetKit software is to provide  decision support tools to urban planners for various bicycle network planning tasks, or for proactive citizens to create a compelling vision for urban cycling in their city. Another aim is to foster future research on bicycle networks. The goal of the accompanying interactive [bikenetkit.org](https://bikenetkit.org/) platform is to visualize the software's potential, to attract policy makers and to guide users.

BikeNetKit is an alternative to extractive practices of bicycle network planning where cities overpay consultancies for a one-off pdf report. Instead, BikeNetKit provides free, open-source software in a community effort, which cities or proactive citizens can use to explore many different scenarios of bicycle network development. This exploration is also data-driven, as cities can import their own data sets such as traffic crash or mobility data to adapt the software to their own needs. 

To prevent extractive use and to keep BikeNetKit's results always transparent and reproducible, it uses the [AGPL license](https://choosealicense.com/licenses/agpl-3.0/) which ensures that all derivations of the software must disclose their source code.

## How can I help to make BikeNetKit better?
From easiest to most specialized:

- Follow us on social media: [Mastodon](https://fosstodon.org/@bikenetkit) • [BlueSky](https://bsky.app/profile/bikenetkit.bsky.social) • [LinkedIn](https://www.linkedin.com/company/bikenetkit)
- Follow us on Github and "star" our repositories: [Github](https://github.com/BikeNetKit) • [BikeNetKit repositories](https://github.com/orgs/BikeNetKit/repositories)
- Post about BikeNetKit on social media or otherwise write about it. We recommend using the hashtag *#BikeNetKit*.
- Try out the software. Let us know what works and what doesn't work, ideally in Github issues. If you are not a Github user, let us know via email and we can create the issues for you.
- Help with "good first issue"s on Github. 
- Make pull requests on Github (after having created or commented on an issue). This can be anything from correcting typos to bugfixes or new feature development.


## What is a bicycle network?
There is no generally agreed definition of a bicycle network. However, having pioneered the field, we have a good understanding of the nuances: Here we define it broadly as the set of infrastructure elements (implemented by physical and/or legal means) which allows people of all ages and demographics to safely cycle - both subjectively and objectively. One necessary prerequisite for such infrastructure is practically no mixing with vehicular traffic. 

Because this infrastructure often consists of pieces connecting places, one can think of it as a network where nodes can be intersections or places of interest and links are the infrastructure pieces inbetween them.

## When is a bicycle network functional?
A bicycle network could be defined as "functional" if it is well connected, covers most of the area, and provides direct connections without significant detours. A technical definition of "well-connectedness" could be the largest connected network component being above a certain threshold, for example making up more than 50% of the bicycle network. By these definitions, the vast majority of cities on the planet unfortunately do not have a functional bicycle network - yet.

## For what is a bicycle network a good solution?
Implementing a bicycle network is in general a good idea as it allows many citizens to cycle and to improve their quality of life, but the devil is in the details. For example, Copenhagen's network of protected bicycle lanes allows many people to cycle, which makes it a successful cycling city. However, this design also leaves out children, elderly, or anyone who feels unsafe cycling through unprotected intersections or next to fast mopeds or electric bikes. This kind of bicycle network does successfully reduce traffic risk, but it does not remove it.

Therefore, before implementing any particular kind of bike lane or local measure as a network, which can take decades, more global approaches should be prioritized. For example, it is much more effective to reduce speed limits or to implement measures that remove vehicular traffic, like road pricing. In the end there is not one "best" approach, but it is a good idea to try several different things.

We discourage use of the term "solution" as it implies that there is a technical fix to a well-defined problem, a.k.a. techno-solutionism. As the world is a complex socio-technical system, this is not the case. 

## Is BikeNetKit's output realistic?
BikeNetKit's tools produce city-wide visions of how a concrete, functional bicycle network could look like. Whether such visions are "realistic" to implement within a certain timeframe is an ill-defined question, since many things can be realized if there is the political will. However, several BikeNetKit tools also provide a prioritization or ranking of the suggested measures, which directly translates into which measures to implement first, given a fixed budget, to arrive at a functional network early.

## Is BikeNetKit useful for planning concrete bicycle infrastructure?
The original algorithms behind most of BikeNetKit's software was not useful for concrete planning tasks, as it provided statistical, unrefined outputs on a city-wide scale without an aspiration for concrete recommendations. However, one goal of BikeNetKit is to expand those original algorithms into useful tools that allow the incorporation of local knowledge and data, and of tweaking details, in order to become useful for concrete planning tasks.

If you would like to use BikeNetKit for such concrete tasks but run into limitations, please let us know! We would love to improve our software to be as useful as possible.

## Will BikeNetKit replace human planners?
It is not the aspiration of BikeNetKit to replace human planners. We do not think algorithmic design should be competing with manual approaches - rather it should be complementing them. There always has to be human judgement "in the loop", because such human, local domain knowledge is crucial when designing systems for other humans.

## What is your expertise on the topic?
Since 2019 we have pioneered a *Science of Bicycle Networks*, exploring the topic from many different angles such as:

- [Sebastiao & Szell, Findings 163938 (2026)](https://doi.org/10.32866/001c.163938) 
- [Sebastiao et al, Appl Net Sci (2026)](https://link.springer.com/article/10.1007/s41109-026-00792-5) 
- [Szell, Vybornova & Vierø, arxiv:2604.07029 (2026)](https://arxiv.org/abs/2604.07029)
- [Vybornova et al, EPB 52 (2025)](https://journals.sagepub.com/doi/10.1177/23998083251355999)
- [Vierø & Szell, Geog Anal 57 (2025)](https://onlinelibrary.wiley.com/doi/10.1111/gean.12400)
- [Lonardi, Szell & De Bacco, R Soc Int 22 (2025)](https://royalsocietypublishing.org/doi/10.1098/rsif.2024.0532)
- [Wolf, Vierø & Szell, Sci Rep 15 (2025)](https://www.nature.com/articles/s41598-025-97200-2)
- [Vierø, Vybornova & Szell, EPB 51 (2024)](https://journals.sagepub.com/doi/10.1177/23998083231184471)
- [Büth, Vybornova & Szell, JOSS 9 (2024)](https://joss.theoj.org/papers/10.21105/joss.06798)
- [Folco et al, EPB 50 (2023)](https://doi.org/10.1177/23998083221135611)
- [Vybornova et al, Geog Anal 55 (2023)](https://onlinelibrary.wiley.com/doi/epdf/10.1111/gean.12324)
- [Szell et al, Sci Rep 12 (2022)](https://www.nature.com/articles/s41598-022-10783-y)
- [Breum, Kostic & Szell, Findings 56683 (2022)](https://findingspress.org/article/56683-computational-desire-line-analysis-of-cyclists-on-the-dybbolsbro-intersection-in-copenhagen)
- [Natera et al, R Soc Open Sci 7 (2020)](https://royalsocietypublishing.org/doi/10.1098/rsos.201130)

Funders of this research include: The Danish Ministry of Transport, the EU Horizon Project [JUST STREETS](https://www.just-streets.eu/). The development of BikeNetKit is now also funded by the Innovation Fund Denmark.
