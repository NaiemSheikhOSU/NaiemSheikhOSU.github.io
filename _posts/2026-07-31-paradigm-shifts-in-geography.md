---
layout: post
title: "From Determinism to GeoAI: Six Paradigm Shifts in Geographic Thought"
date: 2026-07-31
description: Geography has reinvented its dominant mode of explanation roughly every generation. Tracing that pattern from environmental determinism to spatially explicit AI — and asking what the current shift is likely to cost.
tags: geography geoai gis history-of-thought
categories: essays
toc:
  sidebar: left
related_posts: false
---

Every discipline tells itself a story about how it got here. Geography's is unusually turbulent. Over roughly a century and a half, the field has changed not just its answers but its idea of what counts as a question — and each change arrived with a fight.

Thomas Kuhn's language of paradigm shifts fits loosely at best. In physics, a new paradigm displaces the old one. In geography, the old paradigms rarely die; they retreat into subfields, accumulate critics, and resurface decades later wearing different clothes. What follows is less a relay race than a series of overlapping occupations of the same intellectual ground.

I write this as someone working squarely inside the newest of these shifts, which is worth stating up front: I am not a neutral observer of the GeoAI moment.

## 1. Environment as cause (c. 1880–1920)

Geography professionalized in the late nineteenth century by claiming a distinctive causal story: physical environment shapes human society. Friedrich Ratzel's *Anthropogeographie* (1882) treated states as organisms competing for space. Ellen Churchill Semple carried the argument into American geography, and Ellsworth Huntington extended it to climate and civilizational vigor.

The appeal was that it made geography a science with a law-like mechanism, at a moment when disciplines were competing for legitimacy inside the modern university. The cost was that the mechanism was wrong, and the way it was wrong was not accidental. Environmental determinism supplied a scientific-sounding rationale for colonial hierarchy — it explained European dominance as a consequence of latitude. The discipline has never fully stopped reckoning with that inheritance.

The first correction came from the French school. Paul Vidal de la Blache proposed *genres de vie* — ways of life through which communities work with, rather than merely under, their environments. Lucien Febvre put the reversal in its most quoted form: there are, he wrote, <cite>"no necessities, but everywhere possibilities."</cite>

## 2. The region as object (c. 1920–1950)

Possibilism opened the door to regional geography, which became the discipline's center of gravity for a generation. If environment does not determine, then each place is a unique synthesis of physical and human factors, and geography's task is to describe that synthesis.

Richard Hartshorne's *The Nature of Geography* (1939) gave this program its most systematic defense: geography studies areal differentiation, the way phenomena combine differently from place to place. Carl Sauer's Berkeley school pursued a related project through the cultural landscape — the visible imprint of human activity on physical terrain.

Regional geography produced remarkable scholarship. It also produced an enormous quantity of description that explained nothing, and it left the discipline vulnerable to a devastating question: if every region is unique, what exactly is being discovered? A field that cannot generalize cannot predict, and a field that cannot predict looked, to mid-century eyes, like a field that was not a science.

## 3. The quantitative revolution (c. 1950–1970)

The attack came in 1953, when Fred K. Schaefer published a critique arguing that Hartshorne's exceptionalism had exiled geography from science. Geography, Schaefer argued, should search for laws of spatial organization like any other nomothetic discipline.

What followed was the field's most complete methodological rupture. William Bunge's *Theoretical Geography* (1962) and Peter Haggett's *Locational Analysis in Human Geography* (1965) recast geography as a spatial science. Brian Berry brought central place theory into empirical work on urban systems; Torsten Hägerstrand built models of innovation diffusion and, later, time geography. Statistics, models, and formal spatial theory displaced regional description almost entirely at the leading departments.

Waldo Tobler's 1970 formulation became the field's closest thing to a law, holding that <cite>"near things are more related than distant things."</cite> It is a claim about spatial autocorrelation, and nearly every method I use in my own research — kriging, spatial cross-validation, neighborhood-based feature engineering — is a technical elaboration of it.

Meanwhile, Roger Tomlinson was building the Canada Geographic Information System through the 1960s, the first true GIS. At the time it was infrastructure, not theory. That would change.

## 4. The critical turn (c. 1970–1990)

The quantitative revolution's authority collapsed faster than it was built, and partly from the inside. David Harvey published *Explanation in Geography* in 1969, a definitive statement of positivist method — then, four years later, published *Social Justice and the City*, arguing that the spatial science he had helped formalize was incapable of addressing poverty, segregation, and the production of urban inequality. Counting the distribution of deprivation is not the same as explaining what produces it.

Radical and Marxist geography followed, insisting that space is not a neutral container but something actively produced by capital. Doreen Massey developed a relational account in which places are constituted by their connections to elsewhere, and power runs unevenly through those connections.

A parallel humanistic critique came from a different direction. Yi-Fu Tuan's *Topophilia* (1974) and *Space and Place* (1977) argued that lived experience of place — attachment, meaning, memory — is a legitimate object of geographic knowledge and is precisely what abstraction discards. Anne Buttimer made related arguments from phenomenology.

Feminist geography then showed that the supposedly neutral observer had a position all along. Gillian Rose's *Feminism and Geography* (1993) argued the discipline's claim to a detached, comprehensive gaze was itself gendered and particular. Postmodern geography, in Edward Soja's *Postmodern Geographies* (1989) and Derek Gregory's *Geographical Imaginations* (1994), pressed the point that representations of space are never innocent.

By 1990, human geography had built a sophisticated apparatus for interrogating the politics of any claim to objective spatial knowledge. And that is precisely when GIS arrived at scale.

## 5. The GIS wars (c. 1990–2005)

The collision your intuition points to is real, and it has a name. In the early 1990s GIS moved from technical infrastructure to disciplinary center — funding, hiring lines, degree programs. Critical human geographers saw a positivism they thought they had buried returning with better graphics and far more money.

The critique was substantive, not merely territorial. GIS was charged with encoding an epistemology in which only what fits a data model exists; with rendering contested social categories as clean polygons; with serving military, corporate, and surveillance interests that funded its development; and with reinstalling the detached observer that feminist geography had spent two decades dismantling. John Pickles's edited volume *Ground Truth* (1995) collected the argument at its sharpest.

The defense, from Michael Goodchild and others, was that the critics were attacking a tool for the uses to which some users put it. Goodchild's 1992 case for *geographic information science* — as opposed to systems — reframed the field around research questions of representation, uncertainty, and scale rather than software operations.

What is striking, and worth remembering now, is that this conflict mostly resolved productively. Critical GIS and participatory GIS emerged as genuine syntheses. Scholars including Nadine Schuurman, Sarah Elwood, and Mei-Po Kwan took the epistemological critique seriously and did technical work anyway — Kwan's feminist visualization of women's activity spaces is neither a concession nor a compromise but a demonstration that the two programs could produce something neither could alone. The critics did not stop GIS. They made it a discipline instead of a toolkit.

## 6. GeoAI (c. 2017–present)

The current shift has the same shape and moves considerably faster. Deep learning entered geographic research through remote sensing image classification, then spread to spatial prediction, trajectory modeling, geographic knowledge graphs, and now geospatial foundation models pretrained on global Earth observation archives.

Krzysztof Janowicz, Song Gao, Wenwen Li, and colleagues have argued the meaningful version of this is *spatially explicit* AI — models that encode spatial dependence, heterogeneity, and scale rather than treating coordinates as ordinary tabular features. That distinction matters. A convolutional network applied to satellite imagery is computer vision that happens to use geographic data. A model that respects Tobler's law in its architecture and its validation design is doing geography.

The asymmetry you have noticed in funding and publication volume is real, and it is not new. Geography's resource distribution has swung with each of these shifts — toward regional survey, then spatial science, then critical theory, and now toward computation again. What is different this time is the pace and the fact that much of the money originates outside the discipline entirely, in agencies and companies with their own priorities for what Earth observation is *for*.

Human geography's critique of this moment is largely a continuation of the GIS wars with higher stakes: models trained on data that encodes historical inequality reproduce it at scale and behind an interface that makes the encoding invisible; benchmark performance substitutes for explanation; a system that predicts crop yield accurately still tells you nothing about who owns the field or who bears the risk of a bad season. Agnieszka Leszczynski, Jim Thatcher, and Luke Bergmann have developed versions of this argument for digital and data-driven geographies.

Those of us doing the technical work should take it seriously, for a self-interested reason on top of the principled one. The GIS wars produced better GIS. A GeoAI that engages its critics will be more durable than one that treats them as an obstacle to be outspent.

## What the pattern suggests

Four things recur across all six shifts.

**Nothing is fully replaced.** Regional geography survives in area studies. Spatial science never left. Critical theory remains the dominant idiom across much of human geography. The shifts are additions to a widening field, not substitutions — which is why geography feels less like one discipline than several sharing a name and a building.

**Every shift promises the same thing.** Determinism, spatial science, and GeoAI have each been announced as the moment geography finally becomes rigorous. Each delivered real gains. None delivered the finality.

**The critique usually arrives from where the previous paradigm was weakest.** Determinism collapsed on its politics. Regional geography collapsed on its inability to generalize. Spatial science was attacked for what it could not see. If the pattern holds, the serious challenge to GeoAI will land on interpretability and on data provenance — the two places where the current methods are least able to account for themselves.

**Synthesis beats victory.** The most valuable work of the last thirty years came from people who took both sides seriously enough to be uncomfortable in each.

I spend most of my time on the computational side of this divide, building models that predict corn yield from drone imagery. The most useful discipline I have found is to keep asking the human geography question about my own work: a model that generalizes across seasons is a real achievement, but generalizes *for whom*, and who gets to act on what it produces? That question does not slow the modeling down. It tends to make it better.

---

*Suggested further reading: Hartshorne (1939); Schaefer (1953); Harvey (1973); Tuan (1977); Rose (1993); Pickles (1995); Goodchild (2007); Janowicz et al. (2020).*
