## Search Filters

In addition to the What, Where and When tools, there are a number of filters that each operate on a specific field in the metadata that can be used to refine the returned search results.

### Resource Type

The Resource type is an ARIADNE concept designed to categorise the resources into general areas of interest to archaeologists and the names are mostly self-explanatory. 

| Resource Type | Description |
| ----------- | ----------- |
| ![image](../assets/21-Resource-types.png){ width="350" } | Those Resource types that may need clarification are: <Br><Br>**Fieldwork** – normally a record relating to specific fieldwork e.g. evaluations, interventions, etc. <Br><Br>**Fieldwork report** – these always have a link (URL or DOI) to the actual document.<Br><Br>**Fieldwork archive** – the record refers to a collection of documents, images etc. relating to a site (accessible from the DOI supplied).<Br><Br>**Dating** – datasets using for dating materials e.g. radio carbon and dendrology. |

More than one Resource type can be selected but note that the default operator on terms within a filter is ‘AND’ so this will only result in records being found where all the selected terms have been used. For example, all “Maritime” resources are also classified as Resource type “Site/monument” so combining both Resource types has the same result as selecting just ”Maritime” (this is logical as currently the maritime records relate to ship wrecks). Conversely, Resource type  “Artefacts” and “Coins” have been applied separately and the only record that is returned matching both Resource types is the Collection record for the Portable Antiquities Scheme. In most cases, this filter is useful for excluding records that do not match the specified Resource type.

### Getty AAT Subjects

The Getty Arts and Architecture Thesaurus (AAT) has been used to classify each resource, mapping the original subject(s) to those found in this extensive ontology. Over one thousand terms have been used and each resource usually has more than one term assigned to it.

![image](../assets/22-Getty-AAT-subjects.png)

<p><i>The Getty Arts & Architecture Thesaurus Subjects filter</i></p>

The Getty AAT is hierarchical in structure and when a (single) higher level term is specified in this filter, the search results will also include all the sub-categories. So, the general term “weapons” will also include resources with terms such as “knives”, “spears” and “daggers” as these are sub0-categories of “weapons”.

When multiple terms are used as a filter, logical ‘AND’ is applied so only resources matching all the terms will be returned in the search results. Hierarchical sub-categories are not used with multiple terms, only the term specified. Hence, if a search was made for “Weapons”  and “Warships”, there are no results but if “Cannons (artillery)” is used instead of "Weapons", then there are results as both the exact terms have been used for the matching resources. 

When a set of search results is displayed, the Getty AAT filter will only show the first 20 terms found within the current set of resources, starting with the most numerous matches ordered by size. More terms can be displayed by clicking on the “Get 20 more results..” box at the end of the displayed list which extends the list with a scroll bar. This can be repeated until all the matching terms may be viewed. 


