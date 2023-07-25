# Google Tag Manager Templates
A Google Tag Manager (GTM) template files for use of setup of websites.

These templates contains tags for Google Analytics Property 4 (GA4).

You will need to create the following 'Custom Dimensions' under 'Admin > Property > Custom Definitions > Custom Dimensions' so you can use them in GA4:
- event_level_1
- event_level_2
- event_level_3

If you require more then add more levels sequentially (eg. event_level_4 and so on).

More information can be found here: https://support.google.com/analytics/answer/10075209?hl=en

In the situation where you have hardcoded events on your site, it's most likely that they followed the previous structure of Universal Analytics (UA). By adjusting the values to the below it allows you to distinguish in GA4 if the parameter is passed on by GTM or a hardcoded event:
- event_category
- event_action
- event_label

You will need to also create these as 'Custom Dimensions' if you choose to do this.

## Recommended Chrome Extensions
- Tag Assistant Legacy (by Google): https://chrome.google.com/webstore/detail/tag-assistant-legacy-by-g/kejbdjndbnbjgmefkgdddjlbokphdefk
- dataslayer: https://chrome.google.com/webstore/detail/dataslayer/ikbablmmjldhamhcldjjigniffkkjgpo

## Other Chrome Extensions
- Datalayer Checker (https://chrome.google.com/webstore/detail/datalayer-checker/ffljdddodmkedhkcjhpmdajhjdbkogke)
- Tag Assistant Companion (https://chrome.google.com/webstore/detail/tag-assistant-companion/jmekfmbnaedfebfnmakmokmlfpblbfdm)
- Tag Assistant for Conversions Beta (https://chrome.google.com/webstore/detail/tag-assistant-for-convers/llpfnmnallbompdmklfkcibfpcfpncdd)
- WASP.inspector: Analytics Solution Profiler (https://chrome.google.com/webstore/detail/waspinspector-analytics-s/niaoghengfohplclhbjnjheodgkejpih)
## GUA (Universal Analytics) Note
Google announced that on July 1, 2023 Google Universal Analytics was sunset and stopped processing new hits meaning no new data would be collected.

They further stated that you will be still able to access your previously processed data for "at least six months"
