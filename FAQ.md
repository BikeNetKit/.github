# BikeNetKit FAQ
Frequently asked questions about [BikeNetKit](https://bikenetkit.org/).

## What is BikeNetKit?
BikeNetKit is a collection of free, open-source Python software tools to help plan and develop [bicycle networks](https://github.com/BikeNetKit/.github/blob/main/FAQ.md#what-is-a-bicycle-network), developed collaboratively at [github.com/BikeNetKit](https://github.com/BikeNetKit). It comes with an interactive visualization platform at [bikenetkit.org](https://bikenetkit.org/).

## Why does BikeNetKit exist?
We developed BikeNetKit because most cities do not have a well-connected network of protected bike lanes, and our toolkit helps designing and visualizing them.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
BikeNetKit exists for an ultimate and for a practical reason. 

Ultimately, most cities on the planet do not offer infrastructure for safe cycling, at least no [*functional*](#when-is-a-bicycle-network-functional) infrastructure, despite the latent demand of many people who want to do so. Enabling people to cycle has massive societal benefits from environmental to public health. Increasing cycling while reducing the harm by cars is also the most effective approach to tackle fundamental issues in mobility and urban planning, [much more than "solutions" pushed by corporate interests like electric cars](https://theconversation.com/cycling-is-ten-times-more-important-than-electric-cars-for-reaching-net-zero-cities-157163).

Practically, BikeNetKit exists because since 2019 [we have pioneered a *Science of Bicycle Networks*](#what-is-your-expertise-on-the-topic), developing several computational approaches to growing or fixing bicycle networks as support tool prototypes for urban planners. However, most of these algorithms were only the outcomes of research projects and thus not user-friendly nor maintained, therefore not usable as practical tools. In 2025, we won a grant to change this, by turning our raw algorithms into user-friendly software called *BikeNetKit*.
<hr>
</details>

## What is the goal of BikeNetKit?
The goal of the BikeNetKit software is to provide decision support tools to urban planners for various bicycle network planning tasks, or for proactive citizens to create a compelling vision for urban cycling in their city. Another aim is to foster future research on bicycle networks. The goal of the accompanying interactive [bikenetkit.org](https://bikenetkit.org/) platform is to visualize the software's potential, to attract policy makers and to guide users.

## What is the philosophy of BikeNetKit?
BikeNetKit provides tools from the research community as a public good that city planners can use freely. These tools make it easy for planners to use their own data sets and local know-how to plan the best bike network fitting their own city.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
BikeNetKit is an alternative to extractive practices of bicycle network planning where cities outsource their know-how, often spending extensive amounts of public money to consultancies that use proprietary tools to prepare a one-off report. While such one-off reports can be valuable, this mode of operation comes with the danger of creating a perpetual cycle of follow-up contracts, vendor lock-ins, and declining competence within city administrations. This declining internal competence can vaporize solidarity among residents and their city administration, hindering collective action.  

BikeNetKit provides an alternative: It provides free, open-source software as a public good developed in a community effort, which cities or proactive citizens can use *directly* to explore and revisit many different scenarios of bicycle network development. This exploration is also data-driven and fully customizable, as cities can import their own data sets such as traffic crash or mobility data to adapt the software to their own needs.  

To prevent extractive use and to keep BikeNetKit's results always transparent and reproducible, it uses the [AGPL license](https://choosealicense.com/licenses/agpl-3.0/) which ensures that all derivations of the software must disclose their source code.
<hr>
</details>

## How can I help to make BikeNetKit better?
As a citizen, you can help us spread the word:

- Follow us on social media: [Mastodon](https://fosstodon.org/@bikenetkit) • [BlueSky](https://bsky.app/profile/bikenetkit.bsky.social) • [LinkedIn](https://www.linkedin.com/company/bikenetkit)
- Post about BikeNetKit on social media or otherwise write about it. We recommend using the hashtag *#BikeNetKit*.
- Show it to a politician or planner in your city, or to other people who (should) care about cycling.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
We are especially interested in *feedback from planners*, to make BikeNetKit as useful as possible for making a real change in cities: What is missing, what could be better? Please let us know at: contact@bikenetkit.org  

If you are familiar with Python, please feel free to:  

- Try out the software. Let us know what works and what doesn't work, ideally in Github issues. If you are not a Github user, let us know via email and we can create the issues for you.
- Help with "good first issue"s on Github.
- Make pull requests on Github (after having created or commented on an issue). This can be anything from correcting typos to bugfixes or new feature development.
- Follow us on Github and "star" our repositories: [Github](https://github.com/BikeNetKit) • [BikeNetKit repositories](https://github.com/orgs/BikeNetKit/repositories)
<hr>
</details>

## What is a bicycle network?
A bike network is a collection of protected bike lanes or car-free streets on which everyone feels safe to cycle.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
There is no generally agreed definition of a bicycle network. However, having pioneered the field, we have a good understanding of the nuances: Here we define it broadly as the set of infrastructure elements (implemented by physical and/or legal means) which allows people of all ages and demographics to safely cycle - both subjectively and objectively. One necessary prerequisite for such infrastructure is practically no mixing with vehicular traffic. 

Because this infrastructure often consists of pieces connecting places, one can think of it as a network where nodes can be intersections or places of interest and links are the infrastructure pieces inbetween them.
<hr>
</details>

## When is a bicycle network functional?
A bike network is functional if it is well-connected, reaches the whole city, and allows direct travel without having to take large detours. Most cities don't have a functional bicycle network - yet.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
A bicycle network could be defined as "functional" if it is well connected, covers most of the area, and provides direct connections without significant detours. A technical definition of "well-connectedness" could be the largest connected network component being above a certain threshold, for example making up more than 50% of the bicycle network. By these definitions, the vast majority of cities on the planet unfortunately do not have a functional bicycle network - yet.
<hr>
</details>

## Are bicycle networks a good solution?

Connected, safe bike routes are well-proven to make cycling easier and safer. But bike lanes alone are not enough. Safe speeds, safe crossings and streets with less traffic matter too. **There is no one-size-fits-all solution.** Different measures can work together to make cycling safer and easier.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
Implementing a bicycle network is in general a good idea as it allows many citizens to cycle and to improve their quality of life, but the devil is in the details. For example, Copenhagen's cohesive network of protected bicycle lanes allows many people to cycle, which makes it a successful cycling city. However, this design also leaves out children, elderly, or anyone who feels unsafe cycling through unprotected intersections or next to fast mopeds or electric bikes. This kind of bicycle network does successfully reduce traffic risk, but it does not remove it.  

Therefore, before implementing any particular kind of bike lane or local measure as a network, which can take decades, more global approaches should be prioritized. For example, it is much more effective to reduce speed limits or to implement measures that remove vehicular traffic, like road pricing. In the end there is not one "best" approach, but it is a good idea to try several different things.  

We discourage the term "solution" as it implies that there is a technical fix to a well-defined problem, a.k.a. techno-solutionism. As the world is a complex socio-technical system, this is not the case. 
<hr>
</details>

## Is BikeNetKit's output realistic?
As with many things that are politically contested, BikeNetKit's bike network designs are realistic if there is the political will to implement them. Spread the word to your politicians, and it will become more realistic!

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
BikeNetKit's tools produce city-wide visions of how a concrete, functional bicycle network could look like. Whether such visions are "realistic" to implement within a certain timeframe is an ill-defined question, since many things can be realized if there is the political will. However, several BikeNetKit tools also provide a prioritization or ranking of the suggested measures, which directly translates into which measures to implement first, given a fixed budget, to arrive at a functional network early.
<hr>
</details>

## Is BikeNetKit useful for planning concrete bicycle infrastructure?
BikeNetKit's goal is to be useful for planning real bike networks.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
The original raw algorithms behind some of BikeNetKit's software was not useful for concrete planning tasks, as it provided statistical, unrefined outputs on a city-wide scale without an aspiration for concrete recommendations. However, one goal of BikeNetKit is to expand those original algorithms into useful tools that allow the incorporation of local knowledge and data, and of tweaking details, in order to become useful for concrete planning tasks.  

If you would like to use BikeNetKit for such concrete tasks but run into limitations, please let us know! We would love to improve our software to be as useful as possible.
<hr>
</details>

## Why does bikenekit.org show weird results for some cities?
The platform [bikenekit.org](https://bikenetkit.org/) is built on map data that can contain some mistakes. Also, the visualizations were built for over 400 cities automatically, so they were not all double-checked by hand. An urban planner could use BikeNetKit with their own data sets and expertise to fix such issues and produce better results.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
There are several reasons why some results can look "weird". 

1) BikeNetKit relies on OpenStreetMap data which is of very high coverage and quality in Europe, but can still contain mistakes or inaccuracies. If you spot OpenStreetMap issues, please feel free to update the data set yourself and let us know - after all it is crowdsourced data.  

2) The platform [bikenekit.org](https://bikenetkit.org/) visualizes the results of BikeNetKit for 400+ European cities, *running the tools with their default settings*. These default settings usually produce reasonable results, but sometimes they don't because local context is missing. For example, a human user might use a BikeNetKit tool's possibilities to import custom data sets, to naturally limit the study area to a city's populated areas, to only consider a certain set of streets for bicycle network growth, or to otherwise configure the tool's settings to make the outcome more realistic.  

3) It is possible that BikeNetKit could be improved, for example to update its default definition of protected bicycle infrastructure. If you can think of improvements, please let us know!
<hr>
</details>

## How did you evaluate BikeNetKit's results, for example with Strava data of cyclist flows?
Our research evaluated BikeNetKit's tools as well as we could. In general, we aim to actively build better cities for people instead of building better streets for cars.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
Such cyclist mobility data is a reflection of the existing underlying cycling infrastructure (or lack of it). It is thus carrying strong survivorship bias, apart from other biases. Therefore, such data cannot be used for evaluation. It is not the point of BikeNetKit to reinforce the existing status quo, but to fix or extend existing infrastructure, or to propose good infrastructure from scratch. BikeNetKit's approach thus follows [the OECD's recommendation](https://www.oecd.org/en/publications/transport-strategies-for-net-zero-systems-by-design_0a20f779-en.html) to replace the outdated "predict and provide" planning paradigm with the vision-led "decide and provide" principle.  

That being said, we have attempted validations of our approaches in [our research](#what-is-your-expertise-on-the-topic) whenever possible, for example showing that GrowBikeNet indeed recreates well the existing bicycle network in Copenhagen, or that FixBikeNet indeed tends to suggest filling gaps where citizens ask for it. For this reason, some tools of BikeNetKit allow the incorporation of custom data (like mobility or citizen surveys) to shape their results.
<hr>
</details>

## Does BikeNetKit use transport modelling?
BikeNetKit was developed by mobility experts with a background in network science - the science of how to best connect things and places. They use the latest know-how from the field.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
Most tools of BikeNetKit are built on network science concepts like directness or betweenness (a proxy for flow), but do not use a classic transport modelling approach because that is not the best approach and level of detail for the goal of city-wide transformation through bicycle networks.  

Transport modelling has its place for certain applications, but in state-of-the-art sustainable city planning and systems design, the short-term dynamics or predictions studied by engineering approaches like transport modelling are overtrumped by long-term behavioral effects due to mode shift elasticity: Induced demand posits that the development of a functional cycling infrastructure will generally drive a modal shift towards cycling, while the reclamation of ineffectively used automobile space will naturally lead to disappearing traffic.  

For sustainable transport system planning, the so far prevalent "predict and provide" planning paradigm, which focuses on providing roads for flow and is inherent in transport modelling, is being replaced with the vision-led, system-level "decide and provide" principle. For more explanations, see the OECD document [Transport Strategies for Net‑Zero Systems by Design](https://www.oecd.org/en/publications/transport-strategies-for-net-zero-systems-by-design_0a20f779-en.html).  

That being said, some BikeNetKit tools allow to go beyond betweenness-based flow modelling, for example to import Origin-Destination data.
<hr>
</details>

## Is BikeNetKit accounting for other modes of transport?
No, and it is not really necessary because building better bike networks -if done well- leads to more people cycling, so streets become less congested automatically.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
No, that is not the point of BikeNetKit and would go beyond its scope; please see the previous answer. That being said, some of our research looked into potential effects of bicycle network growth on vehicular transport. However, such short-term flow-based predictions are not suited here, as they are easily overtrumped by behavioral effects explained above.
<hr>
</details>

## Will BikeNetKit replace human planners?
No, BikeNetKit is just a tool that needs human oversight.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
It is not the aspiration of BikeNetKit to replace human planners. We do not think algorithmic design should be competing with manual approaches - rather it should be complementing them. There always has to be human judgement "in the loop", because such human, local domain knowledge is crucial when designing systems for other humans.
<hr>
</details>

## How will you maintain BikeNetKit in the long term?
We will maintain BikeNetKit in the long term, beyond 2026, by building up a community. 

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
Being aware of the burdens of open-source maintenance, we would like to build a community of cycling researchers and advocates around BikeNetKit, increasing the project's [bus factor](https://en.wikipedia.org/wiki/Bus_factor) and its longevity. Apart from featuring single, well-defined tools, part of BikeNetKit is the general-purpose library [BikeNetLib](https://github.com/BikeNetKit/BikeNetLib) which aspires to offer core utilities, useful for *anybody* who wants to study or work with bicycle network data.
<hr>
</details>

## What is your expertise on the topic?
Since 2019 we have pioneered a *Science of Bicycle Networks*, exploring the topic from many different angles.

<details>
<summary><i>Advanced answer for planners & experts</i></summary>
<hr>
Our key publications are:

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

Our research builds on planning guidelines like the Dutch CROW Design manual for bicycle traffic, and was performed in collaboration with practitioners such as [Dansk Kyst- og Naturturisme](https://www.kystognaturturisme.dk/) or urban planners from different cities in the EU Horizon Project [JUST STREETS](https://www.just-streets.eu/).  

Funders of this research include: The Danish Ministry of Transport, the EU Horizon Project [JUST STREETS](https://www.just-streets.eu/). The development of BikeNetKit is now also funded by the Innovation Fund Denmark.
<hr>
</details>