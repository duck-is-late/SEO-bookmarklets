<!DOCTYPE NETSCAPE-Bookmark-file-1>
<META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=UTF-8">
<TITLE>Bookmarks</TITLE>
<H1>Bookmarks</H1>
<DL><p>
    <DT><H3>GSC Regex Filters</H3>
    <DL><p>
        <DT><H3>Word Count / Length</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+$'),'_blank');})();">Single-word queries only</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+\\s\\w+$'),'_blank');})();">Exactly 2-word queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+\\s\\w+\\s\\w+$'),'_blank');})();">Exactly 3-word queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+(\\s\\w+){4,}$'),'_blank');})();">5+ word queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^\\w+(\\s\\w+){6,}$'),'_blank');})();">7+ word queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^.{60,}$'),'_blank');})();">Queries over 60 characters</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^.{1,20}$'),'_blank');})();">Short queries under 20 characters</A>
        </DL><p>

        <DT><H3>Question / Intent</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(how|what|why|when|where|who|which|can|does|is|are|will|should|do)\\s'),'_blank');})();">All question-style queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^how\\s(to|do|does|can|much|many|long)\\s'),'_blank');})();">How to / how do / how much" etc</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^what\\s(is|are|does|do|was|were)\\s'),'_blank');})();">Definitional "what" queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(is|are|can|does|do|will|should|has|have)\\s'),'_blank');})();">Yes/no style questions</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^why\\s(is|are|does|do|won.t|can.t)\\s'),'_blank');})();">Why is / why does / why won't</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(guide|tutorial|tips|learn|explained|examples|ideas).*'),'_blank');})();">Educational/informational intent</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(what is|what are|definition of|meaning of|overview of).*'),'_blank');})();">Definitional queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^how\\sto\\s'),'_blank');})();">"How to" specifically (anchored)</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(for beginners|step by step|getting started).*'),'_blank');})();">Beginner/intro intent</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|top|vs|versus|compare|comparison|alternative|alternatives|review|reviews).*'),'_blank');})();">Commercial investigation</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*\\svs\\s.*'),'_blank');})();">Direct comparison queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|top)\\s.*\\s(for|to)\\s'),'_blank');})();">"Best X for Y" pattern</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(worth it|should i|is it good|recommended).*'),'_blank');})();">Evaluation intent</A>
        </DL><p>

        <DT><H3>Transactional</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(buy|purchase|order|shop|price|pricing|cost|costs|hire|get).*'),'_blank');})();">Transactional signals</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(cheap|affordable|budget|discount|deal|coupon|offer).*'),'_blank');})();">Price-sensitive queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(free|download|trial|sign up|register|get started).*'),'_blank');})();">Acquisition intent</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(near me|nearby|close to).*'),'_blank');})();">Local transactional intent</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(quote|demo|consultation|book|booking).*'),'_blank');})();">High-intent service queries</A>
        </DL><p>

        <DT><H3>Navigational</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(login|log in|sign in|account|dashboard|portal).*'),'_blank');})();">Navigational/login queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(website|site|app|software|tool|platform)$'),'_blank');})();">Brand + product-type queries</A>
        </DL><p>

        <DT><H3>Singular/Plural Forms</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(tip|tool|idea|strategy|example|way|option|method|step)(\\s|$)'),'_blank');})();">Plural Forms</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(tips|tools|ideas|strategies|examples|ways|options|methods|steps)(\\s|$)'),'_blank');})();">Singular forms</A>
        </DL><p>

        <DT><H3>Locations</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*\\sin\\s[a-z]+$'),'_blank');})();">Location queries</A>
        </DL><p>

        <DT><H3>Year Specific & Freshness</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(2024|2025|2026).*'),'_blank');})();">Year-specific queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(latest|new|updated|recent|this year|now).*'),'_blank');})();">Freshness-seeking queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(still|anymore|yet).*'),'_blank');})();">"Is X still working / relevant" queries</A>
        </DL><p>

        <DT><H3>Problem / Troubleshooting</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(not working|broken|fix|issue|problem|error|slow|wrong|failed).*'),'_blank');})();">Troubleshooting queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(how to fix|how to stop|how to avoid|how to prevent).*'),'_blank');})();">Solution-seeking queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^why\\s.*(not|won.t|doesn.t|can.t).*'),'_blank');})();">Frustration/failure queries</A>
        </DL><p>

        <DT><H3>TOFU / BOFU / MOFU</H3>
        <DL><p>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('^(what|how|why|who|when)\\s'),'_blank');})();">TOFU — question-led awareness queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(best|vs|review|compare|alternative).*'),'_blank');})();">MOFU — consideration queries</A>
            <DT><A HREF="javascript:(function(){window.open('https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3A'+encodeURIComponent(window.location.hostname.replace(/^www\./,''))+'&search_type=WEB&query=~'+encodeURIComponent('.*(buy|price|pricing|cost|hire|quote|demo|trial).*'),'_blank');})();">BOFU — decision queries</A>
        </DL><p>
    </DL><p>
</DL><p>
