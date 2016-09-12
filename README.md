# Collections in Islandora

## About

This repository contains information about we've traditionally created MODS metadata.

## Schema

This chart shows the number of records that have a particular element, how often the element appears, and if the element contains complex relationships.

| key                                                                   | types                                 | occurrences | percents               |
| --------------------------------------------------------------------- | ------------------------------------- | ----------- | ---------------------- |
| metadata.mods.accessCondition                                         | Object (7164),String (245)            |        7409 | 100.00000000000000000 |
| metadata.mods.identifier                                              | Array (4946),Object (2463)            |        7409 | 100.00000000000000000 |
| metadata.mods.location                                                | Object                                |        7409 | 100.00000000000000000 |
| metadata.mods.location.url                                            | Array                                 |        7409 | 100.00000000000000000 |
| metadata.mods.location.url.XX.#text                                   | String                                |        7409 | 100.00000000000000000 |
| metadata.mods.location.url.XX.@access                                 | String                                |        7409 | 100.00000000000000000 |
| metadata.mods.location.url.XX.@usage                                  | String                                |        7409 | 100.00000000000000000 |
| metadata.mods.originInfo                                              | Object (7164),Array (245)             |        7409 | 100.00000000000000000 |
| metadata.mods.physicalDescription                                     | Object                                |        7409 | 100.00000000000000000 |
| metadata.mods.relatedItem                                             | Array (6501),Object (908)             |        7409 | 100.00000000000000000 |
| metadata.mods.titleInfo                                               | Object (7326),Array (83)              |        7409 | 100.00000000000000000 |
| metadata.mods.typeOfResource                                          | String (7394),Array (15)              |        7409 | 100.00000000000000000 |
| oai_provider                                                          | String                                |        7409 | 100.00000000000000000 |
| record_id                                                             | String                                |        7409 | 100.00000000000000000 |
| metadata.mods.subject                                                 | Array (7027),Object (372)             |        7399 |  99.86502901876096416 |
| metadata.mods.titleInfo.title                                         | String                                |        7326 |  98.87974085571602245 |
| metadata.mods.@xmlns:xs                                               | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.accessCondition.#text                                   | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.accessCondition.@type                                   | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.language                                                | Object                                |        7164 |  96.69321095964367885 |
| metadata.mods.language.languageTerm                                   | Object                                |        7164 |  96.69321095964367885 |
| metadata.mods.language.languageTerm.#text                             | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.language.languageTerm.@authority                        | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.language.languageTerm.@type                             | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.location.physicalLocation                               | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.originInfo.dateCreated                                  | Array                                 |        7164 |  96.69321095964367885 |
| metadata.mods.originInfo.dateCreated.XX.@encoding                     | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.originInfo.dateCreated.XX.@keyDate                      | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.physicalDescription.digitalOrigin                       | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.physicalDescription.form                                | Object (6838),Array (14),String (312) |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo                                              | Object                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.languageOfCataloging                         | Object                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm            | Object                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.#text      | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@authority | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@type      | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.recordContentSource                          | String (6983),null (181)              |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.recordIdentifier                             | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.recordInfo.recordOrigin                                 | String                                |        7164 |  96.69321095964367885 |
| metadata.mods.originInfo.dateCreated.XX.#text                         | String                                |        7162 |  96.66621676339586600 |
| metadata.mods.name                                                    | Array (286),Object (6844)             |        7130 |  96.23430962343095985 |
| metadata.mods.name.namePart                                           | String                                |        6844 |  92.37413955999460313 |
| metadata.mods.name.role                                               | Object (6836),Array (8)               |        6844 |  92.37413955999460313 |
| metadata.mods.physicalDescription.form.#text                          | String                                |        6838 |  92.29315697125117879 |
| metadata.mods.physicalDescription.form.@authority                     | String                                |        6838 |  92.29315697125117879 |
| metadata.mods.name.role.roleTerm                                      | Object                                |        6836 |  92.26616277500338015 |
| metadata.mods.name.role.roleTerm.#text                                | String                                |        6836 |  92.26616277500338015 |
| metadata.mods.name.role.roleTerm.@type                                | String                                |        6836 |  92.26616277500338015 |
| metadata.mods.name.role.roleTerm.@authority                           | String                                |        6591 |  88.95937373464704478 |
| metadata.mods.physicalDescription.form.@valueURI                      | String                                |        6523 |  88.04157106222162099 |
| metadata.mods.relatedItem.XX.@type                                    | String                                |        6501 |  87.74463490349575068 |
| metadata.mods.relatedItem.XX.titleInfo                                | Object                                |        6501 |  87.74463490349575068 |
| metadata.mods.relatedItem.XX.titleInfo.title                          | String                                |        6501 |  87.74463490349575068 |
| metadata.mods.subject.XX.topic                                        | String (6332),null (2)                |        6332 |  85.46362532055607630 |
| metadata.mods.name.role.roleTerm.@valueURI                            | String                                |        6279 |  84.74827911998920627 |
| metadata.mods.relatedItem.XX.@displayLabel                            | String                                |        6256 |  84.43784586313942953 |
| metadata.mods.physicalDescription.internetMediaType                   | String                                |        5703 |  76.97395060062086714 |
| metadata.mods.physicalDescription.extent                              | String (5133),null (1)                |        5134 |  69.29410176811985878 |
| metadata.mods.originInfo.place                                        | Object (4868),Array (84)              |        4952 |  66.83762990956944350 |
| metadata.mods.identifier.XX.#text                                     | String                                |        4946 |  66.75664732082601915 |
| metadata.mods.identifier.XX.@type                                     | String                                |        4946 |  66.75664732082601915 |
| metadata.mods.subject.XX.@authority                                   | String                                |        4939 |  66.66216763395870260 |
| metadata.mods.originInfo.place.@supplied                              | String                                |        4868 |  65.70387366716155952 |
| metadata.mods.originInfo.place.placeTerm                              | Object                                |        4868 |  65.70387366716155952 |
| metadata.mods.originInfo.place.placeTerm.@type                        | String                                |        4868 |  65.70387366716155952 |
| metadata.mods.relatedItem.XX.identifier                               | Object                                |        4090 |  55.20313132676474766 |
| metadata.mods.relatedItem.XX.identifier.#text                         | String                                |        4090 |  55.20313132676474766 |
| metadata.mods.relatedItem.XX.identifier.@type                         | String                                |        4090 |  55.20313132676474766 |
| metadata.mods.subject.XX.geographic                                   | Object (3052),String (946),null (1)   |        3656 |  49.34539074099068756 |
| metadata.mods.subject.XX.@valueURI                                    | String                                |        3599 |  48.57605614792819893 |
| metadata.mods.abstract                                                | String (3480),Array (18)              |        3498 |  47.21284923741395545 |
| metadata.mods.originInfo.place.placeTerm.#text                        | String                                |        3493 |  47.14536374679443753 |
| metadata.mods.subject.XX.cartographics                                | Object                                |        3180 |  42.92077203401268548 |
| metadata.mods.subject.XX.cartographics.coordinates                    | String (3179),null (2)                |        3180 |  42.92077203401268548 |
| metadata.mods.subject.XX.geographic.#text                             | String                                |        3052 |  41.19314347415305377 |
| metadata.mods.subject.XX.geographic.@authority                        | String                                |        3052 |  41.19314347415305377 |
| metadata.mods.subject.XX.geographic.@valueURI                         | String                                |        3045 |  41.09866378728573011 |
| metadata.mods.relatedItem.XX.location                                 | Object                                |        2775 |  37.45444729383182647 |
| metadata.mods.relatedItem.XX.location.url                             | String                                |        2775 |  37.45444729383182647 |
| metadata.mods.originInfo.place.placeTerm.@valueURI                    | String                                |        2731 |  36.86057497638007874 |
| metadata.mods.subject.XX.name                                         | Object                                |        2637 |  35.59184775273315893 |
| metadata.mods.subject.XX.name.namePart                                | String                                |        2637 |  35.59184775273315893 |
| metadata.mods.name.@type                                              | String                                |        2535 |  34.21514374409501613 |
| metadata.mods.note                                                    | String (1978),Array (541),null (1)    |        2520 |  34.01268727223646948 |
| metadata.mods.genre                                                   | String (440),Object (2041)            |        2481 |  33.48630044540423967 |
| metadata.mods.recordInfo.recordChangeDate                             | Array (2154),Object (315)             |        2469 |  33.32433526791739808 |
| metadata.mods.identifier.#text                                        | String                                |        2463 |  33.24335267917398085 |
| metadata.mods.identifier.@type                                        | String                                |        2463 |  33.24335267917398085 |
| metadata.mods.location.holdingSimple                                  | Object                                |        2442 |  32.95991361857200985 |
| metadata.mods.location.holdingSimple.copyInformation                  | Object                                |        2442 |  32.95991361857200985 |
| metadata.mods.location.holdingSimple.copyInformation.shelfLocator     | String                                |        2442 |  32.95991361857200985 |
| metadata.mods.originInfo.dateCreated.XX.@qualifier                    | String                                |        2441 |  32.94641652044810343 |
| metadata.mods.subject.XX.temporal                                     | String (2432),null (2)                |        2434 |  32.85193683358077976 |
| metadata.mods.recordInfo.recordChangeDate.XX.#text                    | String                                |        2154 |  29.07274935888784029 |
| metadata.mods.recordInfo.recordChangeDate.XX.@encoding                | String                                |        2154 |  29.07274935888784029 |
| metadata.mods.subject.XX.@displayLabel                                | String                                |        2154 |  29.07274935888784029 |
| metadata.mods.originInfo.dateCreated.XX.@point                        | String                                |        2144 |  28.93777837764880445 |
| metadata.mods.@xmlns:iso20775                                         | String                                |        2090 |  28.20893507895802443 |
| metadata.mods.location.holdingExternal                                | Object                                |        2090 |  28.20893507895802443 |
| metadata.mods.location.holdingExternal.holding                        | Object                                |        2090 |  28.20893507895802443 |
| metadata.mods.location.holdingExternal.holding.@xsi:schemaLocation    | String                                |        2090 |  28.20893507895802443 |
| metadata.mods.location.holdingExternal.holding.physicalAddress        | Object                                |        2090 |  28.20893507895802443 |
| metadata.mods.location.holdingExternal.holding.physicalAddress.text   | Array                                 |        2090 |  28.20893507895802443 |
| metadata.mods.recordInfo.recordCreationDate                           | Object                                |        2090 |  28.20893507895802443 |
| metadata.mods.recordInfo.recordCreationDate.#text                     | String                                |        2090 |  28.20893507895802443 |
| metadata.mods.recordInfo.recordCreationDate.@encoding                 | String                                |        2090 |  28.20893507895802443 |
| metadata.mods.genre.@authority                                        | String                                |        2038 |  27.50708597651505016 |
| metadata.mods.genre.#text                                             | String                                |        2037 |  27.49358887839114729 |
| metadata.mods.genre.@valueURI                                         | String                                |        1795 |  24.22729113240653120 |
| metadata.mods.subject.XX.name.@authority                              | String                                |        1436 |  19.38183290592522567 |
| metadata.mods.subject.XX.name.@valueURI                               | String                                |        1430 |  19.30085031718180488 |
| metadata.mods.name.@authority                                         | String                                |        1321 |  17.82966662167633842 |
| metadata.mods.name.@valueURI                                          | String                                |        1321 |  17.82966662167633842 |
| metadata.mods.originInfo.publisher                                    | String (1283),null (1)                |        1284 |  17.33027399109191435 |
| metadata.mods.physicalDescription.note                                | String (925),Array (232)              |        1157 |  15.61614252935618907 |
| metadata.mods.relatedItem.@displayLabel                               | String                                |         908 |  12.25536509650425110 |
| metadata.mods.relatedItem.@type                                       | String                                |         908 |  12.25536509650425110 |
| metadata.mods.relatedItem.titleInfo                                   | Object                                |         908 |  12.25536509650425110 |
| metadata.mods.relatedItem.titleInfo.title                             | String                                |         908 |  12.25536509650425110 |
| metadata.mods.relatedItem.location                                    | Object                                |         630 |   8.50317181805911737 |
| metadata.mods.relatedItem.location.url                                | String                                |         630 |   8.50317181805911737 |
| metadata.mods.titleInfo.nonSort                                       | String                                |         591 |   7.97678499122688578 |
| metadata.mods.relatedItem.abstract                                    | String                                |         442 |   5.96571737076528574 |
| metadata.mods.relatedItem.XX.part                                     | Object                                |         413 |   5.57430152517208821 |
| metadata.mods.relatedItem.XX.part.detail                              | Object (1),Array (412)                |         413 |   5.57430152517208821 |
| metadata.mods.relatedItem.XX.part.detail.XX.@type                     | String                                |         412 |   5.56080442704818445 |
| metadata.mods.relatedItem.XX.part.detail.XX.number                    | String                                |         412 |   5.56080442704818445 |
| metadata.mods.relatedItem.XX.titleInfo.nonSort                        | String                                |         386 |   5.20987987582669732 |
| metadata.mods.relatedItem.XX.abstract                                 | String                                |         359 |   4.84545822648130642 |
| metadata.mods.recordInfo.recordChangeDate.#text                       | String                                |         315 |   4.25158590902955869 |
| metadata.mods.recordInfo.recordChangeDate.@encoding                   | String                                |         315 |   4.25158590902955869 |
| metadata.mods.name.@usage                                             | String                                |         311 |   4.19759751653394542 |
| metadata.mods.name.XX.namePart                                        | String                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role                                            | Object                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role.roleTerm                                   | Object                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role.roleTerm.#text                             | String                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role.roleTerm.@authority                        | String                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role.roleTerm.@type                             | String                                |         286 |   3.86017006343636115 |
| metadata.mods.name.XX.role.roleTerm.@valueURI                         | String                                |         286 |   3.86017006343636115 |
| metadata.mods.titleInfo.partName                                      | String                                |         256 |   3.45525711971926031 |
| metadata.mods.originInfo.dateIssued                                   | Object                                |         249 |   3.36077743285193664 |
| metadata.mods.originInfo.dateIssued.#text                             | String                                |         249 |   3.36077743285193664 |
| metadata.mods.originInfo.dateIssued.@encoding                         | String                                |         249 |   3.36077743285193664 |
| metadata.mods.originInfo.dateIssued.@keyDate                          | String                                |         249 |   3.36077743285193664 |
| metadata.mods.originInfo.XX.dateOther                                 | String                                |         245 |   3.30678904035632337 |
| metadata.mods.originInfo.XX.publisher                                 | String                                |         245 |   3.30678904035632337 |
| metadata.mods.part                                                    | Object                                |         245 |   3.30678904035632337 |
| metadata.mods.part.detail                                             | Object                                |         245 |   3.30678904035632337 |
| metadata.mods.part.detail.title                                       | String                                |         245 |   3.30678904035632337 |
| metadata.mods.relatedItem.XX.identifer                                | Object                                |         245 |   3.30678904035632337 |
| metadata.mods.relatedItem.XX.identifer.#text                          | String                                |         245 |   3.30678904035632337 |
| metadata.mods.relatedItem.XX.identifer.@type                          | String                                |         245 |   3.30678904035632337 |
| metadata.mods.name.XX.@type                                           | String                                |         213 |   2.87488190039141589 |
| metadata.mods.originInfo.dateIssued.@qualifier                        | String                                |         177 |   2.38898636793089469 |
| metadata.mods.subject.geographic                                      | String (118),Object (47)              |         165 |   2.22702119044405444 |
| metadata.mods.subject.name                                            | Object                                |         134 |   1.80861114860305028 |
| metadata.mods.subject.name.namePart                                   | String                                |         134 |   1.80861114860305028 |
| metadata.mods.name.XX.@authority                                      | String                                |         133 |   1.79511405047914696 |
| metadata.mods.name.XX.@valueURI                                       | String                                |         133 |   1.79511405047914696 |
| metadata.mods.subject.name.@authority                                 | String                                |         129 |   1.74112565798353347 |
| metadata.mods.subject.name.@valueURI                                  | String                                |         129 |   1.74112565798353347 |
| metadata.mods.subject.cartographics                                   | Object                                |          99 |   1.33621271426643262 |
| metadata.mods.subject.cartographics.coordinates                       | String                                |          99 |   1.33621271426643262 |
| metadata.mods.originInfo.place.XX.@supplied                           | String                                |          84 |   1.13375624240788220 |
| metadata.mods.originInfo.place.XX.placeTerm                           | Object                                |          84 |   1.13375624240788220 |
| metadata.mods.originInfo.place.XX.placeTerm.@type                     | String                                |          84 |   1.13375624240788220 |
| metadata.mods.originInfo.place.XX.placeTerm.#text                     | String                                |          83 |   1.12025914428397888 |
| metadata.mods.originInfo.place.XX.placeTerm.@valueURI                 | String                                |          83 |   1.12025914428397888 |
| metadata.mods.titleInfo.XX.@type                                      | String                                |          83 |   1.12025914428397888 |
| metadata.mods.titleInfo.XX.title                                      | String                                |          83 |   1.12025914428397888 |
| metadata.mods.subject.topic                                           | String                                |          73 |   0.98528816304494538 |
| metadata.mods.subject.geographic.#text                                | String                                |          47 |   0.63436361182345791 |
| metadata.mods.subject.geographic.@authority                           | String                                |          47 |   0.63436361182345791 |
| metadata.mods.subject.geographic.@valueURI                            | String                                |          47 |   0.63436361182345791 |
| metadata.mods.subject.@authority                                      | String                                |          29 |   0.39141584559319748 |
| metadata.mods.subject.@valueURI                                       | String                                |          21 |   0.28343906060197055 |
| metadata.mods.physicalDescription.form.XX.#text                       | String                                |          14 |   0.18895937373464705 |
| metadata.mods.physicalDescription.form.XX.@authority                  | String                                |          14 |   0.18895937373464705 |
| metadata.mods.physicalDescription.form.XX.@valueURI                   | String                                |          14 |   0.18895937373464705 |
| metadata.mods.classification                                          | Object                                |          13 |   0.17546227561074368 |
| metadata.mods.classification.#text                                    | String                                |          13 |   0.17546227561074368 |
| metadata.mods.classification.@authority                               | String                                |          13 |   0.17546227561074368 |
| metadata.mods.name.role.XX.roleTerm                                   | Object                                |           8 |   0.10797678499122688 |
| metadata.mods.name.role.XX.roleTerm.#text                             | String                                |           8 |   0.10797678499122688 |
| metadata.mods.name.role.XX.roleTerm.@authority                        | String                                |           8 |   0.10797678499122688 |
| metadata.mods.name.role.XX.roleTerm.@type                             | String                                |           8 |   0.10797678499122688 |
| metadata.mods.name.role.XX.roleTerm.@valueURI                         | String                                |           8 |   0.10797678499122688 |
| metadata.mods.name.XX.@usage                                          | String                                |           3 |   0.04049129437171008 |
| metadata.mods.titleInfo.XX.partName                                   | String                                |           3 |   0.04049129437171008 |
| metadata.mods.@xmlns:mods                                             | String                                |           1 |   0.01349709812390336 |
| metadata.mods.originInfo.place.XX.placeTerm.@authority                | String                                |           1 |   0.01349709812390336 |
| metadata.mods.relatedItem.XX.part.detail.@type                        | String                                |           1 |   0.01349709812390336 |
| metadata.mods.relatedItem.XX.part.detail.number                       | String                                |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic                       | Object                                |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.city                  | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.citySection           | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.continent             | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.country               | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.county                | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.province              | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.subject.XX.hierarchicalGeographic.region                | null                                  |           1 |   0.01349709812390336 |
| metadata.mods.titleInfo.subTitle                                      | null                                  |           1 |   0.01349709812390336 |

## Controlled Vocabularies / Ontologies

This is a list of the vocabularies and ontologies we've historically used.

* language.languageTerm.@authority
	* iso639-2b
* recordInfo.languageOfCataloging.languageTerm.@authority
	* iso639-2b
* physicalDescription.form.@authority
	* aat
	* http://vocab.getty.edu/aat/300046300 (looks like a mistake)
* name.role.roleTerm.@authority
	* marcrelator
* subject.@authority
	* lcsh
	* local
	* dots
	* agrovoc
	* fast
* subject.geographic.@authority
	* lcsh
	* naf
	* dots
* genre.@authority
	* dct
	* lcsh
	* lctgm
	* lcgft
* subject.name.@authority
	* naf
	* lcsh
	* dots
* name.@authority
	* naf
* classifciation.@authority
	* lcc
* originInfo.place.placeTerm.@authority
	* marccountry