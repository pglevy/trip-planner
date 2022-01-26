{% include components/dropdown.html label="Passengers" values="1,2,3,4" %}
{: .padding-bottom-3}

{% include components/checkbox.html legend="Route" labels="Take Acela (if available)" %}
{: .margin-bottom-5}

{% include components/radio-buttons.html legend="Cabin" labels="Coach,Business" %}
{: .margin-bottom-5}

{% include content/summary-box.html %}
{: .tablet:width-mobile .margin-bottom-5}

{% include components/button.html label="Checkout" %}