{
    "title":"Scientific Exchange Scholar",
     "description":"Michigan States University (MSU) United States of America Duration=31-08-2015 to 20-11-2015",
    "featured":true,
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"100",
    "sitemap": {"priority" : "0.8"}
}

Addressed pretty significant page load performance issue founde in larger deployments. Eliminates uses of intensive backend query, replacing it with an asynchronous API call against a lucene index. This change reduces page load from from 2+ minutes to nearly instant, with an incredibly responsive UI.
