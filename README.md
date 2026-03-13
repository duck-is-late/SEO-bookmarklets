# GSC Regex Bookmarklets

A curated collection of Google Search Console (GSC) Regex Bookmarklets. You can either download the <a href="https://github.com/duck-is-late/SEO-bookmarklets/blob/main/gsc%20bookmarklets.html">full html file</a> and upload in your browser och drag these links directly to your bookmarks bar. They let you instantly filter GSC queries for whatever domain you are currently browsing. 

By <a href="https://www.linkedin.com/in/aleand/">Alexander Andersen</a>
Inspired by the following post by<a href="https://www.linkedin.com/posts/daniel-foley-assertive_seo-tip-use-the-following-in-google-search-activity-7437497605279907841-lV2N">Daniel Foley Carter</a>

*Note: These bookmarklets automatically strip `www.` and target GSC "Domain Properties".* - it doesn't work for url prefix since that uses a different url in search console.

---

## 📏 Word Count / Length

<a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+$'),'_blank');})();">Single-word queries only</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+\\s\\w+$'),'_blank');})();">Exactly 2-word queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+\\s\\w+\\s\\w+$'),'_blank');})();">Exactly 3-word queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+(\\s\\w+){4,}$'),'_blank');})();">5+ word queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+(\\s\\w+){6,}$'),'_blank');})();">7+ word queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^.{60,}$'),'_blank');})();">Queries over 60 characters</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^.{1,20}$'),'_blank');})();">Short queries under 20 characters</a>

## ❓ Question / Intent

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(how|what|why|when|where|who|which|can|does|is|are|will|should|do)\\s'),'_blank');})();">All question-style queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^how\\s(to|do|does|can|much|many|long)\\s'),'_blank');})();">How to / how do / how much etc</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^what\\s(is|are|does|do|was|were)\\s'),'_blank');})();">Definitional "what" queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(is|are|can|does|do|will|should|has|have)\\s'),'_blank');})();">Yes/no style questions</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^why\\s(is|are|does|do|won.t|can.t)\\s'),'_blank');})();">Why is / why does / why won't</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(guide|tutorial|tips|learn|explained|examples|ideas).*'),'_blank');})();">Educational/informational intent</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(what is|what are|definition of|meaning of|overview of).*'),'_blank');})();">Definitional queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^how\\sto\\s'),'_blank');})();">"How to" specifically (anchored)</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(for beginners|step by step|getting started).*'),'_blank');})();">Beginner/intro intent</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|top|vs|versus|compare|comparison|alternative|alternatives|review|reviews).*'),'_blank');})();">Commercial investigation</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*\\svs\\s.*'),'_blank');})();">Direct comparison queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|top)\\s.*\\s(for|to)\\s'),'_blank');})();">"Best X for Y" pattern</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(worth it|should i|is it good|recommended).*'),'_blank');})();">Evaluation intent</a>

## 💳 Transactional

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(buy|purchase|order|shop|price|pricing|cost|costs|hire|get).*'),'_blank');})();">Transactional signals</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(cheap|affordable|budget|discount|deal|coupon|offer).*'),'_blank');})();">Price-sensitive queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(free|download|trial|sign up|register|get started).*'),'_blank');})();">Acquisition intent</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(near me|nearby|close to).*'),'_blank');})();">Local transactional intent</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(quote|demo|consultation|book|booking).*'),'_blank');})();">High-intent service queries</a>

## 🧭 Navigational

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(login|log in|sign in|account|dashboard|portal).*'),'_blank');})();">Navigational/login queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(website|site|app|software|tool|platform)$'),'_blank');})();">Brand + product-type queries</a>

## 🔠 Singular / Plural Forms

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(tip|tool|idea|strategy|example|way|option|method|step)(\\s|$)'),'_blank');})();">Plural Forms</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(tips|tools|ideas|strategies|examples|ways|options|methods|steps)(\\s|$)'),'_blank');})();">Singular forms</a>

## 📍 Locations

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*\\sin\\s[a-z]+$'),'_blank');})();">Location queries</a>

## 📅 Year Specific & Freshness

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(2024|2025|2026).*'),'_blank');})();">Year-specific queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(latest|new|updated|recent|this year|now).*'),'_blank');})();">Freshness-seeking queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(still|anymore|yet).*'),'_blank');})();">"Is X still working / relevant" queries</a>

## 🛠️ Problem / Troubleshooting

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(not working|broken|fix|issue|problem|error|slow|wrong|failed).*'),'_blank');})();">Troubleshooting queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(how to fix|how to stop|how to avoid|how to prevent).*'),'_blank');})();">Solution-seeking queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^why\\s.*(not|won.t|doesn.t|can.t).*'),'_blank');})();">Frustration/failure queries</a>

## 🎯 TOFU / BOFU / MOFU

* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(what|how|why|who|when)\\s'),'_blank');})();">TOFU — question-led awareness queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|vs|review|compare|alternative).*'),'_blank');})();">MOFU — consideration queries</a>
* <a href="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(buy|price|pricing|cost|hire|quote|demo|trial).*'),'_blank');})();">BOFU — decision queries</a>
