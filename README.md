# Plugin Compatibility List
The tables below show whether each plugin runs on different Geeklog and PHP versions.  Plugin names in **boldface** are core plugins shipped with Geeklog.


## Geeklog 2.2.2 (not relased yet, will work with PHP 7.4 and PHP 8.0) ##
|      Plugin Name|Plugin Version|PHP 7.4|PHP 8.0|PostgreSQL|                                         Plugin Home Page|  Released|
|             ----|         :---:|  :---:|  :---:|     :---:|                                                    :---:|     :---:|
|     **Calendar**|         1.1.9|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|        **Links**|         2.1.8|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|        **Polls**|         2.2.1|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|    **reCAPTCHA**|         1.2.4|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|        **Spamx**|         1.3.6|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|  **Staticpages**|         1.7.3|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|   **Xmlsitemap**|         2.0.3|    Yes|    Yes|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2022-??-??|
|         Autotags|         1.1.3|    Yes|    Yes|        No|    [GitHub](https://github.com/Geeklog-Plugins/autotags)|2020-04-18|
|              Ban|         2.0.4|    Yes|    Yes|       Yes|         [GitHub](https://github.com/Geeklog-Plugins/ban)|2022-01-20|
|        Downloads|       1.2.3.1|    Yes|    Yes|        No|   [GitHub](https://github.com/Geeklog-Plugins/downloads)|2022-03-08|
|              FAQ|       1.2.0.2|    Yes|    Yes|        No|         [GitHub](https://github.com/Geeklog-Plugins/faq)|2022-03-10|
|           Faqman|         0.9.2|    Yes|    Yes|        No|      [GitHub](https://github.com/Geeklog-Plugins/faqman)|2022-01-18|
|    Media Gallery|       1.7.2.5|    Yes|    Yes|        No|[GitHub](https://github.com/Geeklog-Plugins/mediagallery)|2022-03-10|
|             Menu|       1.2.8.1|    Yes|    Yes|        No|        [GitHub](https://github.com/Geeklog-Plugins/menu)|2022-03-10|
|        Messenger|         1.9.6|    Yes|    Yes|       Yes|   [GitHub](https://github.com/Geeklog-Plugins/messenger)|2022-01-18|
|        Net Tools|         2.1.3|    Yes|Partial|       Yes|    [GitHub](https://github.com/Geeklog-Plugins/nettools)|2020-04-20|
|      Search Rank|         1.2.2|    Yes|    Yes|        No|  [GitHub](https://github.com/Geeklog-Plugins/searchrank)|2022-03-08|

* GUS-1.7.6.1 doesn't work with Geeklog 2.2.2, but its next version will.
* Net Tools-2.1.3 works with PHP 8.0, but whois feature errors out because accessing array elements with curly braces was dropped with PHP 8.0.

## Geeklog 2.2.1sr1 (released on 2020-04-16, works with PHP 7.3) ##
|      Plugin Name|Plugin Version|PHP 7.3|PHP 8.0|PostgreSQL|                                         Plugin Home Page|  Released|
|             ----|         :---:|  :---:|  :---:|     :---:|                                                    :---:|     :---:|
|     **Calendar**|         1.1.8|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|        **Links**|         2.1.7|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|        **Polls**|         2.2.0|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|    **reCAPTCHA**|         1.2.1|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|        **Spamx**|         1.3.6|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|  **Staticpages**|         1.7.2|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|   **Xmlsitemap**|         2.0.2|    Yes|      ?|       Yes|                  [Geeklog Home](https://www.geeklog.net)|2020-04-16|
|         Autotags|         1.1.3|    Yes|      ?|        No|    [GitHub](https://github.com/Geeklog-Plugins/autotags)|2020-04-18|
|              Ban|         2.0.3|    Yes|      ?|        No|         [GitHub](https://github.com/Geeklog-Plugins/ban)|2019-09-28|
|           Faqman|         0.9.1|    Yes|     No|        No|      [GitHub](https://github.com/Geeklog-Plugins/faqman)|2018-06-07|
|              GUS|       1.7.6.1|    Yes|    Yes|        No|         [GitHub](https://github.com/Geeklog-Plugins/gus)|2020-04-28|
|    Media Gallery|       1.7.2.4|    Yes|      ?|        No|[GitHub](https://github.com/Geeklog-Plugins/mediagallery)|2020-06-09|
|        Messenger|         1.9.5|    Yes|     No|       Yes|   [GitHub](https://github.com/Geeklog-Plugins/messenger)|2020-06-09|
|        Net Tools|         2.1.3|    Yes|Partial|       Yes|    [GitHub](https://github.com/Geeklog-Plugins/nettools)|2020-04-20|

* Net Tools doesn't use database.
