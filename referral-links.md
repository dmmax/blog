---
permalink: /referral-links
layout: default
title: Referral links
n26_code: maksimd7489
n26_url: https://n26.com/r/maksimd7489
n26_start_usage: 2019-12-15

getsafe_url: https://www.hellogetsafe.com/en-de/referral?n=Maksim&r=T5UT-8FVX&s=1
getsafe_start_usage: 2021-05-01
---
<div class="wrapper">
    <p><a href="/">back to home</a></p>
</div>
{% assign today_days = 'now' | date: "%s" | divided_by: 86400 %}
---
{: data-content="N26 - Online banking"}
{% assign n26_start_usage_days = page.n26_start_usage | date: "%s" | divided_by: 86400 %}
> [N26]({{page.n26_url}}) is a German mobile-only bank, with no physical branches. It is a member of the German Banking Association and is 
regulated by the German Federal Financial Supervisory Authority (BaFin). The app is in English and the support staff English pretty well. 
I have used the bank for more than {{ today_days | minus: n26_start_usage_days | divided_by: 365.25 | round }} years now.

**Referral code**: {{page.n26_code}}

**Referral link**: {{page.n26_url}}

---
{: data-content="Getsafe - Insurance"}
{% assign getsafe_start_usage_days = page.getsafe_start_usage | date: "%s" | divided_by: 86400 %}
> [Get Safe]({{page.getsafe_url}}) is a digital insurance company, all operations you can achieve just using the app. The app is fully in 
> English (also German is supported) and when I contacted the support they answered very well in English. I have used it for more than 
> {{ today_days | minus: getsafe_start_usage_days | divided_by: 365.25 | round }} years now.

**Referral link**: {{page.getsafe_url}}

---