# All Year Cooling report verification

Reviewed September 8, 2026. Scope: all sections of the public report in `allyear/index.html`.

The report now distinguishes direct public observations, qualitative feedback, recommendations, and measurements that need supporting data. This pass does not certify that every underlying business system works or that public sources are always current.

## Phone inventory

Removed the unrelated contact number and every claim derived from that attribution. Each distinct public number appears once, with its observed sources grouped together. Different published numbers do not establish broken routing, inconsistent ownership, or failed attribution.

| Number | Observed sources |
| --- | --- |
| (888) 820-8705 | Google Business Profile and BBB |
| (954) 507-0702 | Website header call and text options |
| (888) 204-5554 | Website contact page, website footer, BBB additional phone, and HomeAdvisor |

Sources: [Google Maps][maps], [BBB][bbb], [website][home], [contact page][contact], [HomeAdvisor][ha]. A previously reported Facebook number was not reverified and is excluded from the verified inventory. The inventory is not exhaustive. No calls, messages, bookings, or test leads were submitted.

## Changes across the report

| Topic | Verification result and report change |
| --- | --- |
| Company identity | Retained BBB's entity name, Tommy Smith as its listed president, December 27, 1973 start date, and the public Coral Springs and Naples addresses. Alternate names are identified as BBB listings, without claiming registered DBA status. Annual revenue and exact employee count remain unverified. |
| Ownership | Removed the assertion of verified independence and no parent or outside sponsorship. [Creative Service Partners announced All Year Cooling joining its family of brands][csp]. Current ownership percentages and control were not independently established. |
| Composite score and revenue estimate | Withheld the numerical health score and projected revenue loss. Reproducible scoring inputs, search volumes, call volumes, conversion rates, and average-ticket records were not available to validate those outputs. No replacement numbers were invented. |
| Map and organic rankings | Removed the asserted ranking order, Page 1 absence, and guaranteed improvement timing. A retained geographic scan and dated query records are needed. Google review counts do not establish search ranking. |
| Performance | Removed the asserted mobile load time and percentage-based Core Web Vitals claims. The public PageSpeed API returned a quota error and no usable result. Current LCP, INP, and CLS data remain unverified. |
| Reviews | Updated the subject's Google snapshot to 4.7 stars / 2,592 reviews, BBB customer reviews to 3.38 / 16, and HomeAdvisor to 4.7 / 505. BBB's A+ business rating and accreditation are distinct from its customer-review average. Yelp's precise metrics were not reverified. |
| Customer feedback | Retained sourced reports of communication, warranty, and repair concerns as customer accounts, alongside positive feedback. Removed the unsupported sentiment percentage and claims that establish an overall failure rate. |
| Competitive comparison | Rechecked the nine competitor profiles in native Google Maps and linked each listing. The table now uses Google reviews only, in alphabetical order. Corrected the cross-platform comparison and noted Expert Cool's Margate location and Aire Serv's service-area listing. |
| Hours | Corrected Google hours to Monday through Saturday, 7:30 AM to 10 PM, and Sunday, 9 AM to 5 PM. HomeAdvisor shows Monday through Saturday, 7 AM to 10 PM, and Sunday, 7 AM to 8 PM. The website advertises 24/7 service. Recommend clarifying the scope of each schedule. |
| Chat and booking | Removed the claim that no chat exists. The live site has booking, texting, inquiry forms, and a visible chat/text request form. Netic scheduler and widget scripts are present. Response time and successful handoff were not tested. |
| Tracking and advertising | GTM, GA4, and Meta Pixel code are present in retrieved homepage source. Removed conclusions about active campaigns or accurate conversion attribution; code presence alone does not verify those. |
| Social profiles | Retained the six destinations linked from the official website. Removed precise audience and engagement metrics, inactivity claims, paid-view claims, and unsupported assessments of channel purpose. Platform access did not support revalidation. |
| Plumbing coverage | Confirmed dedicated plumbing service content and the Coral Springs plumbing page. Removed the unsupported assertion of zero search presence. |
| Crawler policy | Confirmed named exclusions in robots.txt and the absence of a dedicated OAI-SearchBot block. Removed the claim that these rules make the company invisible in all AI answers. Training controls and search controls are treated separately. |
| Sitemaps and content | Corrected the inventory to 404 page URL entries, 295 post entries, and 8 plumbing-service entries. These are not verified indexed-page totals. Removed the sweeping characterization of the archive as thin content. |
| Test and education pages | Confirmed the public dummy test page returns HTTP 200, carries an index/follow directive, and appears in the page sitemap. The education page has content-hub material, so it requires review before any removal decision. |
| Structured data | Confirmed Organization and Yoast markup in homepage source. One JSON-LD block decodes to a string. LocalBusiness/HVACBusiness types were not found in the retrieved homepage source; no site-wide absence is asserted. Removed promises of self-serving review stars. |
| GBP state and directory coverage | Retained publicly observable profile contents. Public appearance does not prove the account's verification state. Thumbtack and Yellow Pages absence was not established. |
| Website review summary | Confirmed the homepage summary references 1,873 Google reviews against the native profile snapshot of 2,592, a difference of 719. Recommend refreshing it or making the snapshot date clear. |
| Recommendations and source list | Rebased action items on the supported observations and missing measurements. Removed unsupported deadlines, causal guarantees, bankruptcy narrative, and citations that were not actually verified in this pass. |

## Evidence and limits

Each retained factual finding has a source link in the report. Review counts are snapshots and can differ across Google surfaces. Some web retrievals may use cached content. Public reviews are customer reports, not adjudicated facts or a representative survey.

Technical observations came from the [homepage][home], [robots.txt](https://allyearcooling.com/robots.txt), [sitemap index](https://allyearcooling.com/sitemap_index.xml), [page sitemap](https://allyearcooling.com/page-sitemap.xml), [test page](https://allyearcooling.com/dummy-test-page/), [education page](https://allyearcooling.com/education/), and [Coral Springs plumbing page](https://allyearcooling.com/coral-springs-plumbing-services/). Interpretation was checked against [Google local ranking guidance](https://support.google.com/business/answer/7091), [Web Vitals documentation](https://web.dev/articles/vitals), [Google structured data guidance](https://developers.google.com/search/docs/appearance/structured-data/local-business), [review-snippet eligibility](https://developers.google.com/search/docs/appearance/structured-data/review-snippet), [OpenAI crawler documentation](https://developers.openai.com/api/docs/bots), and [Google crawler documentation](https://developers.google.com/crawling/docs/crawlers-fetchers/google-common-crawlers).

Remaining measurements require original audit exports, analytics or advertising access, platform data, or direct testing. Their absence is a verification limit, not evidence of a business failure.

[maps]: https://www.google.com/maps/place/All+Year+Cooling+%26+Plumbing/@26.2841914,-80.2943434,17z/data=!3m1!4b1!4m6!3m5!1s0x88d901a71411b2f9:0x987c84ac1322328f!8m2!3d26.2841914!4d-80.2917685!16s%2Fg%2F1hhwy8z0p
[bbb]: https://www.bbb.org/us/fl/coral-springs/profile/air-conditioning-contractor/all-year-cooling-and-heating-inc-0633-4003950
[home]: https://allyearcooling.com/
[contact]: https://allyearcooling.com/contact/
[ha]: https://www.homeadvisor.com/rated.AllYearCooling.19297135.html
[csp]: https://www.linkedin.com/posts/creative-service-partners_all-year-cooling-joins-creative-service-partners-activity-7181019590003425281-QwJ7
