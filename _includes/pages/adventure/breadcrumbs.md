{% assign campaign = site.campaigns | where: "slug", page.campaign | first %}

---

[Back to Home]({{site.baseurl}}/)
|
[Back to Campaigns]({{site.baseurl}}/campaigns)
|
[Back to {{campaign.name}}]({{site.baseurl}}/campaigns/{{campaign.slug}})
|
[Back to Adventures]({{site.baseurl}}/campaigns/{{campaign.slug}}/adventures)