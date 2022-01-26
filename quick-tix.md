---
layout: sidebar
header: true
prose: true
sidebar: options.md
sidebar-reverse: true
save-data: true
---

# QuickTix

Need simple tickets for common routes? Start here.
{: .usa-intro}

{% include components/combo-box.html label="Starting point" values=site.data.cities %}

{% include components/combo-box.html  label="Destination" values=site.data.cities %}

{% include components/date-picker.html label="Start date" type="text" %}

{% include components/date-picker.html label="Return date" type="text" %}

{% include components/checkbox.html labels="Dates are flexible" %}
{: .margin-bottom-3}

Need more options? [Use CustomTix](#)