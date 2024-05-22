# Using Social Media (SoMe) to Understand Cultural Ecosystem Services (CES)
Linder and Lusseau (2024)
https://doi.org/10.1016/j.scitotenv.2024.172813

Repository for paper on using social media data (Reddit and Twitter) to understand the contexts of human-nature interactions providing CES.

This repository includes code and instructions for:
- Building a repertoire of CES human activities and CES nature feature based on Reddit data
- Sampling Twitter (Academic Research API) for CES related tweets based on the lists of nature features and human activities
- Preparing the Twitter data for analysis

### CES activity list rules
1.	Remove verbs that are not gerunds.
2.	Remove transitive verb, i.e. verbs that must be followed by an object. Without an object to affect, the sentence that a transitive verb inhabits will seem incomplete. 
3.	Remove actions that can also be used as an adjective e.g. exciting, charming, calming.
4.	Remove actions that can be used in reference to involuntary bodily functions, e.g. bleeding, freezing, or involuntary movements, e.g. tripping, falling.
5.	Remove actions that are most often referring to nature objects or animals as the subject, e.g. howling, babbling, flowing, erupting, blooming, mating.
6.	Remove actions that describe a temporary physical motion, e.g. spinning, rolling, skipping, snapping, cracking.

### CES feature list rules
1.  Keep nouns describing habitat types
2.  Remove nouns referring to species/species groups, e.g. grass, tree, flower.
3.  Remove nouns referring to geological features, e.g. rock, sand.
4.  Remove nouns referring to natural elements, e.g. water, air.
6.  Remove nouns referring to natural phenomena, e.g. sunset, sunrise, wind, rain, snow, thunder, lighting.
