# Collections in Islandora

## About

This repository contains information about we've traditionally created MODS metadata.

## Schema

This chart shows the number of records that have a particular element, how often the element appears, and if the element contains complex relationships.

| key                                                                   | types                                 | occurrences | percents               |
| --------------------------------------------------------------------- | ------------------------------------- | ----------- | ---------------------- |
| metadata.mods.accessCondition                                         | Object (6644),String (245)            |        6889 | 100.000000000000000000 |
| metadata.mods.identifier                                              | Array (4612),Object (2277)            |        6889 | 100.000000000000000000 |
| metadata.mods.location                                                | Object                                |        6889 | 100.000000000000000000 |
| metadata.mods.location.url                                            | Array                                 |        6889 | 100.000000000000000000 |
| metadata.mods.location.url.XX.#text                                   | String                                |        6889 | 100.000000000000000000 |
| metadata.mods.location.url.XX.@access                                 | String                                |        6889 | 100.000000000000000000 |
| metadata.mods.location.url.XX.@usage                                  | String                                |        6889 | 100.000000000000000000 |
| metadata.mods.originInfo                                              | Object (6644),Array (245)             |        6889 | 100.000000000000000000 |
| metadata.mods.physicalDescription                                     | Object                                |        6889 | 100.000000000000000000 |
| metadata.mods.relatedItem                                             | Array (6167),Object (722)             |        6889 | 100.000000000000000000 |
| metadata.mods.titleInfo                                               | Object (6806),Array (83)              |        6889 | 100.000000000000000000 |
| metadata.mods.typeOfResource                                          | String (6874),Array (15)              |        6889 | 100.000000000000000000 |
| oai_provider                                                          | String                                |        6889 | 100.000000000000000000 |
| record_id                                                             | String                                |        6889 | 100.000000000000000000 |
| metadata.mods.subject                                                 | Array (6691),Object (188)             |        6879 |  99.854841050950795989 |
| metadata.mods.titleInfo.title                                         | String                                |        6806 |  98.795180722891572600 |
| metadata.mods.@xmlns:xs                                               | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.accessCondition.#text                                   | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.accessCondition.@type                                   | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.language                                                | Object                                |        6644 |  96.443605748294388036 |
| metadata.mods.language.languageTerm                                   | Object                                |        6644 |  96.443605748294388036 |
| metadata.mods.language.languageTerm.#text                             | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.language.languageTerm.@authority                        | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.language.languageTerm.@type                             | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.location.physicalLocation                               | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.originInfo.dateCreated                                  | Array                                 |        6644 |  96.443605748294388036 |
| metadata.mods.originInfo.dateCreated.XX.#text                         | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.originInfo.dateCreated.XX.@encoding                     | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.originInfo.dateCreated.XX.@keyDate                      | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.physicalDescription.digitalOrigin                       | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.physicalDescription.form                                | Object (6318),Array (14),String (312) |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo                                              | Object                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.languageOfCataloging                         | Object                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm            | Object                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.#text      | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@authority | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@type      | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.recordContentSource                          | String (6463),null (181)              |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.recordIdentifier                             | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.recordInfo.recordOrigin                                 | String                                |        6644 |  96.443605748294388036 |
| metadata.mods.name                                                    | Array (286),Object (6324)             |        6610 |  95.950065321527077344 |
| metadata.mods.name.namePart                                           | String                                |        6324 |  91.798519378719703354 |
| metadata.mods.name.role                                               | Object (6316),Array (8)               |        6324 |  91.798519378719703354 |
| metadata.mods.physicalDescription.form.#text                          | String                                |        6318 |  91.711424009290169579 |
| metadata.mods.physicalDescription.form.@authority                     | String                                |        6318 |  91.711424009290169579 |
| metadata.mods.name.role.roleTerm                                      | Object                                |        6316 |  91.682392219480334461 |
| metadata.mods.name.role.roleTerm.#text                                | String                                |        6316 |  91.682392219480334461 |
| metadata.mods.name.role.roleTerm.@type                                | String                                |        6316 |  91.682392219480334461 |
| metadata.mods.relatedItem.XX.@type                                    | String                                |        6167 |  89.519523878647120796 |
| metadata.mods.relatedItem.XX.titleInfo                                | Object                                |        6167 |  89.519523878647120796 |
| metadata.mods.relatedItem.XX.titleInfo.title                          | String                                |        6167 |  89.519523878647120796 |
| metadata.mods.subject.XX.topic                                        | String (6106),null (2)                |        6106 |  88.634054289446950747 |
| metadata.mods.name.role.roleTerm.@authority                           | String                                |        6071 |  88.125997967774708286 |
| metadata.mods.physicalDescription.form.@valueURI                      | String                                |        6003 |  87.138917114240086903 |
| metadata.mods.relatedItem.XX.@displayLabel                            | String                                |        5922 |  85.963129626941494621 |
| metadata.mods.name.role.roleTerm.@valueURI                            | String                                |        5759 |  83.597038757439392498 |
| metadata.mods.physicalDescription.internetMediaType                   | String                                |        5703 |  82.784148642763824455 |
| metadata.mods.physicalDescription.extent                              | String (5133),null (1)                |        5134 |  74.524604441863843363 |
| metadata.mods.originInfo.place                                        | Object (4682),Array (84)              |        4766 |  69.182755116852959532 |
| metadata.mods.subject.XX.@authority                                   | String                                |        4736 |  68.747278269705333287 |
| metadata.mods.originInfo.place.@supplied                              | String                                |        4682 |  67.963419944839600362 |
| metadata.mods.originInfo.place.placeTerm                              | Object                                |        4682 |  67.963419944839600362 |
| metadata.mods.originInfo.place.placeTerm.@type                        | String                                |        4682 |  67.963419944839600362 |
| metadata.mods.identifier.XX.#text                                     | String                                |        4612 |  66.947307301495143861 |
| metadata.mods.identifier.XX.@type                                     | String                                |        4612 |  66.947307301495143861 |
| metadata.mods.relatedItem.XX.identifier                               | Object                                |        3756 |  54.521701262882857009 |
| metadata.mods.relatedItem.XX.identifier.#text                         | String                                |        3756 |  54.521701262882857009 |
| metadata.mods.relatedItem.XX.identifier.@type                         | String                                |        3756 |  54.521701262882857009 |
| metadata.mods.subject.XX.@valueURI                                    | String                                |        3582 |  51.995935549426619104 |
| metadata.mods.subject.XX.geographic                                   | Object (3006),String (824),null (1)   |        3533 |  51.284656699085495291 |
| metadata.mods.abstract                                                | String (3480),Array (18)              |        3498 |  50.776600377413267040 |
| metadata.mods.originInfo.place.placeTerm.#text                        | String                                |        3307 |  48.004064450573380896 |
| metadata.mods.subject.XX.cartographics                                | Object                                |        3091 |  44.868631151110463406 |
| metadata.mods.subject.XX.cartographics.coordinates                    | String (3090),null (2)                |        3091 |  44.868631151110463406 |
| metadata.mods.subject.XX.geographic.#text                             | String                                |        3006 |  43.634780084192193783 |
| metadata.mods.subject.XX.geographic.@authority                        | String                                |        3006 |  43.634780084192193783 |
| metadata.mods.subject.XX.geographic.@valueURI                         | String                                |        2999 |  43.533168819857742449 |
| metadata.mods.subject.XX.name                                         | Object                                |        2623 |  38.075192335607489724 |
| metadata.mods.subject.XX.name.namePart                                | String                                |        2623 |  38.075192335607489724 |
| metadata.mods.originInfo.place.placeTerm.@valueURI                    | String                                |        2545 |  36.942952533023664330 |
| metadata.mods.name.@type                                              | String                                |        2535 |  36.797793583974453213 |
| metadata.mods.genre                                                   | String (440),Object (2041)            |        2481 |  36.013935259108727394 |
| metadata.mods.recordInfo.recordChangeDate                             | Array (2154),Object (315)             |        2469 |  35.839744520249674054 |
| metadata.mods.location.holdingSimple                                  | Object                                |        2442 |  35.447815357816807591 |
| metadata.mods.location.holdingSimple.copyInformation                  | Object                                |        2442 |  35.447815357816807591 |
| metadata.mods.location.holdingSimple.copyInformation.shelfLocator     | String                                |        2442 |  35.447815357816807591 |
| metadata.mods.relatedItem.XX.location                                 | Object                                |        2441 |  35.433299462911890032 |
| metadata.mods.relatedItem.XX.location.url                             | String                                |        2441 |  35.433299462911890032 |
| metadata.mods.subject.XX.temporal                                     | String (2432),null (2)                |        2434 |  35.331688198577445803 |
| metadata.mods.originInfo.dateCreated.XX.@qualifier                    | String                                |        2427 |  35.230076934242994469 |
| metadata.mods.identifier.#text                                        | String                                |        2277 |  33.052692698504863245 |
| metadata.mods.identifier.@type                                        | String                                |        2277 |  33.052692698504863245 |
| metadata.mods.recordInfo.recordChangeDate.XX.#text                    | String                                |        2154 |  31.267237625199594930 |
| metadata.mods.recordInfo.recordChangeDate.XX.@encoding                | String                                |        2154 |  31.267237625199594930 |
| metadata.mods.subject.XX.@displayLabel                                | String                                |        2154 |  31.267237625199594930 |
| metadata.mods.originInfo.dateCreated.XX.@point                        | String                                |        2130 |  30.918856147481491803 |
| metadata.mods.@xmlns:iso20775                                         | String                                |        2090 |  30.338220351284657994 |
| metadata.mods.location.holdingExternal                                | Object                                |        2090 |  30.338220351284657994 |
| metadata.mods.location.holdingExternal.holding                        | Object                                |        2090 |  30.338220351284657994 |
| metadata.mods.location.holdingExternal.holding.@xsi:schemaLocation    | String                                |        2090 |  30.338220351284657994 |
| metadata.mods.location.holdingExternal.holding.physicalAddress        | Object                                |        2090 |  30.338220351284657994 |
| metadata.mods.location.holdingExternal.holding.physicalAddress.text   | Array                                 |        2090 |  30.338220351284657994 |
| metadata.mods.recordInfo.recordCreationDate                           | Object                                |        2090 |  30.338220351284657994 |
| metadata.mods.recordInfo.recordCreationDate.#text                     | String                                |        2090 |  30.338220351284657994 |
| metadata.mods.recordInfo.recordCreationDate.@encoding                 | String                                |        2090 |  30.338220351284657994 |
| metadata.mods.genre.@authority                                        | String                                |        2038 |  29.583393816228770845 |
| metadata.mods.genre.#text                                             | String                                |        2037 |  29.568877921323849733 |
| metadata.mods.note                                                    | String (1480),Array (534),null (1)    |        2015 |  29.249528233415588829 |
| metadata.mods.genre.@valueURI                                         | String                                |        1795 |  26.056031354332993999 |
| metadata.mods.subject.XX.name.@authority                              | String                                |        1436 |  20.844825083466396620 |
| metadata.mods.subject.XX.name.@valueURI                               | String                                |        1430 |  20.757729714036869950 |
| metadata.mods.originInfo.publisher                                    | String (1097),null (1)                |        1098 |  15.938452605603135481 |
| metadata.mods.physicalDescription.note                                | String                                |         823 |  11.946581506749891943 |
| metadata.mods.name.@authority                                         | String                                |         801 |  11.627231818841631039 |
| metadata.mods.name.@valueURI                                          | String                                |         801 |  11.627231818841631039 |
| metadata.mods.relatedItem.@displayLabel                               | String                                |         722 |  10.480476121352880980 |
| metadata.mods.relatedItem.@type                                       | String                                |         722 |  10.480476121352880980 |
| metadata.mods.relatedItem.titleInfo                                   | Object                                |         722 |  10.480476121352880980 |
| metadata.mods.relatedItem.titleInfo.title                             | String                                |         722 |  10.480476121352880980 |
| metadata.mods.relatedItem.location                                    | Object                                |         630 |   9.145013790100160023 |
| metadata.mods.relatedItem.location.url                                | String                                |         630 |   9.145013790100160023 |
| metadata.mods.titleInfo.nonSort                                       | String                                |         584 |   8.477282624473799544 |
| metadata.mods.relatedItem.XX.part                                     | Object                                |         413 |   5.995064595732326751 |
| metadata.mods.relatedItem.XX.part.detail                              | Object (1),Array (412)                |         413 |   5.995064595732326751 |
| metadata.mods.relatedItem.XX.part.detail.XX.@type                     | String                                |         412 |   5.980548700827405639 |
| metadata.mods.relatedItem.XX.part.detail.XX.number                    | String                                |         412 |   5.980548700827405639 |
| metadata.mods.relatedItem.XX.titleInfo.nonSort                        | String                                |         386 |   5.603135433299462953 |
| metadata.mods.recordInfo.recordChangeDate.#text                       | String                                |         315 |   4.572506895050080011 |
| metadata.mods.recordInfo.recordChangeDate.@encoding                   | String                                |         315 |   4.572506895050080011 |
| metadata.mods.name.@usage                                             | String                                |         311 |   4.514443315430396453 |
| metadata.mods.name.XX.namePart                                        | String                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role                                            | Object                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role.roleTerm                                   | Object                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role.roleTerm.#text                             | String                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role.roleTerm.@authority                        | String                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role.roleTerm.@type                             | String                                |         286 |   4.151545942807373990 |
| metadata.mods.name.XX.role.roleTerm.@valueURI                         | String                                |         286 |   4.151545942807373990 |
| metadata.mods.relatedItem.abstract                                    | String                                |         256 |   3.716069095659747301 |
| metadata.mods.titleInfo.partName                                      | String                                |         256 |   3.716069095659747301 |
| metadata.mods.originInfo.dateIssued                                   | Object                                |         249 |   3.614457831325301296 |
| metadata.mods.originInfo.dateIssued.#text                             | String                                |         249 |   3.614457831325301296 |
| metadata.mods.originInfo.dateIssued.@encoding                         | String                                |         249 |   3.614457831325301296 |
| metadata.mods.originInfo.dateIssued.@keyDate                          | String                                |         249 |   3.614457831325301296 |
| metadata.mods.originInfo.XX.dateOther                                 | String                                |         245 |   3.556394251705617737 |
| metadata.mods.originInfo.XX.publisher                                 | String                                |         245 |   3.556394251705617737 |
| metadata.mods.part                                                    | Object                                |         245 |   3.556394251705617737 |
| metadata.mods.part.detail                                             | Object                                |         245 |   3.556394251705617737 |
| metadata.mods.part.detail.title                                       | String                                |         245 |   3.556394251705617737 |
| metadata.mods.relatedItem.XX.identifer                                | Object                                |         245 |   3.556394251705617737 |
| metadata.mods.relatedItem.XX.identifer.#text                          | String                                |         245 |   3.556394251705617737 |
| metadata.mods.relatedItem.XX.identifer.@type                          | String                                |         245 |   3.556394251705617737 |
| metadata.mods.name.XX.@type                                           | String                                |         213 |   3.091885614748149269 |
| metadata.mods.originInfo.dateIssued.@qualifier                        | String                                |         177 |   2.569313398170997242 |
| metadata.mods.name.XX.@authority                                      | String                                |         133 |   1.930614022354478099 |
| metadata.mods.name.XX.@valueURI                                       | String                                |         133 |   1.930614022354478099 |
| metadata.mods.subject.name                                            | Object                                |         132 |   1.916098127449557209 |
| metadata.mods.subject.name.namePart                                   | String                                |         132 |   1.916098127449557209 |
| metadata.mods.subject.name.@authority                                 | String                                |         129 |   1.872550442734794540 |
| metadata.mods.subject.name.@valueURI                                  | String                                |         129 |   1.872550442734794540 |
| metadata.mods.originInfo.place.XX.@supplied                           | String                                |          84 |   1.219335172013354729 |
| metadata.mods.originInfo.place.XX.placeTerm                           | Object                                |          84 |   1.219335172013354729 |
| metadata.mods.originInfo.place.XX.placeTerm.@type                     | String                                |          84 |   1.219335172013354729 |
| metadata.mods.originInfo.place.XX.placeTerm.#text                     | String                                |          83 |   1.204819277108433839 |
| metadata.mods.originInfo.place.XX.placeTerm.@valueURI                 | String                                |          83 |   1.204819277108433839 |
| metadata.mods.titleInfo.XX.@type                                      | String                                |          83 |   1.204819277108433839 |
| metadata.mods.titleInfo.XX.title                                      | String                                |          83 |   1.204819277108433839 |
| metadata.mods.subject.topic                                           | String                                |          53 |   0.769342429960807039 |
| metadata.mods.relatedItem.XX.abstract                                 | String                                |          25 |   0.362897372623022185 |
| metadata.mods.subject.@authority                                      | String                                |          20 |   0.290317898098417793 |
| metadata.mods.physicalDescription.form.XX.#text                       | String                                |          14 |   0.203222528668892427 |
| metadata.mods.physicalDescription.form.XX.@authority                  | String                                |          14 |   0.203222528668892427 |
| metadata.mods.physicalDescription.form.XX.@valueURI                   | String                                |          14 |   0.203222528668892427 |
| metadata.mods.classification                                          | Object                                |          13 |   0.188706633763971537 |
| metadata.mods.classification.#text                                    | String                                |          13 |   0.188706633763971537 |
| metadata.mods.classification.@authority                               | String                                |          13 |   0.188706633763971537 |
| metadata.mods.subject.@valueURI                                       | String                                |          12 |   0.174190738859050648 |
| metadata.mods.name.role.XX.roleTerm                                   | Object                                |           8 |   0.116127159239367103 |
| metadata.mods.name.role.XX.roleTerm.#text                             | String                                |           8 |   0.116127159239367103 |
| metadata.mods.name.role.XX.roleTerm.@authority                        | String                                |           8 |   0.116127159239367103 |
| metadata.mods.name.role.XX.roleTerm.@type                             | String                                |           8 |   0.116127159239367103 |
| metadata.mods.name.role.XX.roleTerm.@valueURI                         | String                                |           8 |   0.116127159239367103 |
| metadata.mods.name.XX.@usage                                          | String                                |           3 |   0.043547684714762662 |
| metadata.mods.subject.cartographics                                   | Object                                |           3 |   0.043547684714762662 |
| metadata.mods.subject.cartographics.coordinates                       | String                                |           3 |   0.043547684714762662 |
| metadata.mods.subject.geographic                                      | String                                |           3 |   0.043547684714762662 |
| metadata.mods.titleInfo.XX.partName                                   | String                                |           3 |   0.043547684714762662 |
| metadata.mods.@xmlns:mods                                             | String                                |           1 |   0.014515894904920888 |
| metadata.mods.originInfo.place.XX.placeTerm.@authority                | String                                |           1 |   0.014515894904920888 |
| metadata.mods.relatedItem.XX.part.detail.@type                        | String                                |           1 |   0.014515894904920888 |
| metadata.mods.relatedItem.XX.part.detail.number                       | String                                |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic                       | Object                                |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.city                  | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.citySection           | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.continent             | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.country               | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.county                | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.province              | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.subject.XX.hierarchicalGeographic.region                | null                                  |           1 |   0.014515894904920888 |
| metadata.mods.titleInfo.subTitle                                      | null                                  |           1 |   0.014515894904920888 |

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