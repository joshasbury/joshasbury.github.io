---
id: 878
title: Scaling Economically
date: 2018-11-08T20:44:53-05:00
author: Josh Asbury
excerpt: 'I’m excited to be a panelist at Digital Ocean’s TIDE SF: The Power Of Simplicity next week.1 Preparing for the panel gave me an opportunity to organize my thoughts on how we scaled HubTran. In particular, I’m going to focus on server scaling today. I’ll write more about scaling other parts of the organization in the future. Are you in San Francisco? You should come by! It’s free! '
layout: post
guid: https://hubtran.wpmudev.host/?p=878
permalink: /scaling-economically/
eg-cs-description:
  - ""
qode_page_background_image_fixed:
  - 'yes'
qode_hide-featured-image:
  - 'yes'
qode_post_style_masonry_date_image:
  - full
qode_post_style_masonry_gallery:
  - default
qode_show-sidebar:
  - default
gallery_type:
  - slider
video_format_choose:
  - youtube
slide_template:
  - default
eg_sources_html5_mp4:
  - ""
eg_sources_html5_ogv:
  - ""
eg_sources_html5_webm:
  - ""
eg_sources_youtube:
  - ""
eg_sources_vimeo:
  - ""
eg_sources_wistia:
  - ""
eg_sources_image:
  - ""
eg_sources_iframe:
  - ""
eg_sources_soundcloud:
  - ""
eg_vimeo_ratio:
  - "1"
eg_youtube_ratio:
  - "1"
eg_wistia_ratio:
  - "1"
eg_html5_ratio:
  - "1"
eg_soundcloud_ratio:
  - "1"
eg_sources_revslider:
  - ""
eg_sources_essgrid:
  - ""
eg_featured_grid:
  - ""
eg_settings_custom_meta_skin:
  - 'a:2:{i:0;s:2:"16";i:1;s:2:"16";}'
eg_settings_custom_meta_element:
  - 'a:2:{i:0;s:6:"layout";i:1;s:6:"layout";}'
eg_settings_custom_meta_setting:
  - 'a:2:{i:0;s:16:"content-bg-color";i:1;s:13:"item-bg-color";}'
eg_settings_custom_meta_style:
  - 'a:2:{i:0;s:7:"#41b8a7";i:1;s:7:"#41b8a7";}'
eg_custom_meta_216:
  - 'true'
eg_votes_count:
  - "0"
qode_show-page-title:
  - 'yes'
eg-post-author:
  - Mike Mangino
image: /wp-content/uploads/2020/03/iStock-1134187868.jpg
categories:
  - Bottom Section
  - Technology
---
\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;full\_width&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; z\_index=&#8221;&#8221; background\_color=&#8221;#efefef&#8221; css=&#8221;.vc\_custom\_1581932050197{background-color: #efefef !important;}&#8221; border\_color=&#8221;#ffffff&#8221; el\_class=&#8221;footer-orange-curve&#8221;\]\[vc\_column\]\[vc\_empty\_space height=&#8221;180px&#8221; el\_class=&#8221;insights-post-top-space&#8221;\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;grid&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; z\_index=&#8221;&#8221; el\_class=&#8221;beginning-of-indiv-case-study-content&#8221;\]\[vc\_column\]\[vc\_empty\_space height=&#8221;60px&#8221;\]\[vc\_row\_inner row\_type=&#8221;row&#8221; type=&#8221;full\_width&#8221; text\_align=&#8221;left&#8221; css\_animation=&#8221;&#8221;\]\[vc\_column\_inner\][vc\_column\_text]

<div id="back-to-insights">
  <div id="back-to-case-studies-text">
    <a href="/insights"><i class="fa fa-caret-left" aria-hidden="true"></i> BACK TO INSIGHTS</a>
  </div>
</div>

\[/vc\_column\_text\]\[/vc\_column\_inner\]\[/vc\_row\_inner\]\[vc\_empty\_space height=&#8221;60px&#8221;\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;grid&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; el\_class=&#8221;case-study-individual-page-content&#8221; z\_index=&#8221;&#8221;\]\[vc\_column el\_id=&#8221;case-study-body-content-row&#8221;\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[vc\_column\_text\]

<div id="author-section">
  <div id="author-image">
    <img class="alignnone size-full wp-image-805" src="https://hubtran.wpmudev.host/wp-content/uploads/2020/03/HubTran_Website_Headshots_MikeMangino_Small.png" alt="" width="55" height="56" />
  </div>
  
  <div id="author-name">
    <h2 class="h2-case-study-category-title">
      <span style="color: #5e6970;"><strong>MIKE MANGINO</strong> | November 8, 2018</span>
    </h2>
  </div>
</div>

<div id="hubtran-author-bio">
  Mike Mangino is HubTran&#8217;s Chief Technology Officer and unofficial voice of reason. His broad base of experience in both the corporate and start-up worlds prepared him to forge new frontiers with HubTran. He is based in Cincinnati, Ohio.
</div>

\[/vc\_column\_text\]\[vc\_empty\_space height=&#8221;10px&#8221;\]\[vc\_separator type=&#8221;normal&#8221; color=&#8221;#e9933b&#8221; thickness=&#8221;2px&#8221;\]\[vc\_empty\_space height=&#8221;20px&#8221;\][vc\_column_text]

# <span style="color: #5e6970;">Scaling Economically</span> {.h1-case-study-title}

\[/vc\_column\_text\]\[vc\_empty\_space height=&#8221;30px&#8221;\][vc\_column\_text]I’m excited to be a panelist at Digital Ocean’s [TIDE SF: The Power Of Simplicity](https://tidesf.splashthat.com/) next week.<sup id="fnref:tide"><a class="footnote" href="https://engineering.hubtran.com/2018/11/08/scaling-economically.html#fn:tide">1</a></sup> Preparing for the panel gave me an opportunity to organize my thoughts on how we scaled HubTran. In particular, I’m going to focus on server scaling today. I’ll write more about scaling other parts of the organization in the future.

&nbsp;

&nbsp;

### Day 1 {#day-1}

One of the biggest mistakes I see startups make is worrying about scaling too early. Sure, there are a small number of domains where you might need to worry about scale from the start, but that’s probably not you. At this point, the most important task is to validate the idea of your business. It typically takes longer than you think to get your first customers, so worrying about scale is misguided. You are also targeting early adopters. These folks are more willing to deal with an incomplete product. Your product may be more enjoyable to use if it’s faster, but if you’re providing enough value, people will wait.

&nbsp;

&nbsp;

### Beyond Early Adopters {#beyond-early-adopters}

So you’ve got a market! You’re starting to sign up new customers. Now’s the time to build that autoscaling cluster with [Kubernetes](https://kubernetes.io/), right? Probably not. At this point, you don’t have a ton of customers. You’re more likely to be able to just move to a bigger server and worrying about scaling later. This is the time where you want to focus on building a full featured and valuable product.

&nbsp;

&nbsp;

### Time For More Servers {#time-for-more-servers}

Okay, so now you’ve outgrown your single server. Autoscale it is! Or, not. You’ve outgrown your single server and moved to a cluster, but do you really need to autoscale? Can you just figure out the approximate required number of servers and then double it? From my experience, until you get to 100 servers, your server cost is significantly lower than the cost of an engineer. It’s far cheaper to just have too many servers than to deal with the time and complexity of more advanced solutions.

&nbsp;

&nbsp;

### 100+ Servers {#100-servers}

So when is the time to start looking at complex automation? We chose to wait until the savings from dynamic sizing would pay for the engineering cost to build it. At our current size, we can afford to have a full time person working on auto scaling. As we grow, that advantage goes straight to the bottom line.

&nbsp;

&nbsp;

### In Summary {#in-summary}

Obviously, this isn’t scientific, but it’s worked for us. We’re very happy with the tradeoffs we made. We believe that waiting to worry about scaling has enabled us to feature more of our energy on building the features that attract customers. Just as importantly, we haven’t had to drag the baggage of a complex server architecture with us as we learned more about our product. If you’re in San Francisco, I hope to see you next week!\[/vc\_column\_text\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;grid&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; el\_class=&#8221;case-study-individual-page-content&#8221; z\_index=&#8221;&#8221;\]\[vc\_column width=&#8221;2/3&#8243; offset=&#8221;vc\_col-lg-9 vc\_col-md-8 vc\_col-xs-12&#8243;\]\[/vc\_column\]\[vc\_column width=&#8221;1/3&#8243; offset=&#8221;vc\_col-lg-3 vc\_col-md-4 vc\_col-xs-12&#8243;\]\[vc\_row\_inner row\_type=&#8221;row&#8221; type=&#8221;full\_width&#8221; text\_align=&#8221;left&#8221; css\_animation=&#8221;&#8221; css=&#8221;.vc\_custom\_1581120747833{padding-top: 25px !important;padding-right: 25px !important;padding-bottom: 25px !important;padding-left: 25px !important;}&#8221;\]\[vc\_column\_inner el\_class=&#8221;share-this-post-insights&#8221;\][vc\_column\_text]

<div id="share-this-post-text">
  SHARE THIS POST
</div>

\[/vc\_column\_text\]\[vc\_empty\_space height=&#8221;10px&#8221;\]\[vc\_raw\_html]JTVCRElTUExBWV9VTFRJTUFURV9TT0NJQUxfSUNPTlMlNUQ=[/vc\_raw\_html\]\[vc\_empty\_space height=&#8221;60px&#8221;\]\[/vc\_column\_inner\]\[/vc\_row\_inner\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;grid&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; el\_class=&#8221;case-study-individual-page-content&#8221; z\_index=&#8221;&#8221; background\_color=&#8221;#efefef&#8221;\]\[vc\_column\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[vc\_column\_text\]

## <span style="color: #5e6970; font-style: italic;">More Articles You&#8217;ll Love</span> {.}

\[/vc\_column\_text\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;grid&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; z\_index=&#8221;&#8221; background\_color=&#8221;#efefef&#8221;\]\[vc\_column\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[vc\_raw\_html\]JTVCZXNzX2dyaWQlMjBhbGlhcyUzRCUyMm1vcmUtaW5zaWdodHMlMjIlNUQ=\[/vc\_raw\_html\]\[vc\_empty\_space height=&#8221;10px&#8221;\]\[vc\_row\_inner row\_type=&#8221;row&#8221; type=&#8221;full\_width&#8221; text\_align=&#8221;left&#8221; css\_animation=&#8221;&#8221;\]\[vc\_column\_inner\][vc\_column_text]

<div id="back-to-insights">
  <div id="back-to-case-studies-text" style="text-align: center;">
    <a href="/insights"><i class="fa fa-caret-left" aria-hidden="true"></i> BACK TO INSIGHTS</a>
  </div>
</div>

\[/vc\_column\_text\]\[/vc\_column\_inner\]\[/vc\_row\_inner\]\[vc\_empty\_space height=&#8221;30px&#8221;\]\[/vc\_column\]\[/vc\_row\]\[vc\_row css\_animation=&#8221;&#8221; row\_type=&#8221;row&#8221; use\_row\_as\_full\_screen\_section=&#8221;no&#8221; type=&#8221;full\_width&#8221; angled\_section=&#8221;no&#8221; text\_align=&#8221;left&#8221; background\_image\_as\_pattern=&#8221;without\_pattern&#8221; z\_index=&#8221;&#8221; background\_color=&#8221;#efefef&#8221; css=&#8221;.vc\_custom\_1581932050197{background-color: #efefef !important;}&#8221; border\_color=&#8221;#ffffff&#8221; el\_class=&#8221;footer-orange-curve&#8221;\]\[vc\_column\]\[vc\_row\_inner row\_type=&#8221;row&#8221; type=&#8221;full\_width&#8221; text\_align=&#8221;left&#8221; css\_animation=&#8221;&#8221; background\_color=&#8221;#efefef&#8221; border\_color=&#8221;#ffffff&#8221;\]\[vc\_column\_inner el\_class=&#8221;ht-footer-column-1&#8243;\]\[vc\_single\_image image=&#8221;387&#8243; img\_size=&#8221;full&#8221; qode\_css\_animation=&#8221;&#8221; el\_class=&#8221;footer-orange-curve-image&#8221;\]\[/vc\_column\_inner\]\[/vc\_row\_inner\]\[/vc\_column\][/vc_row]