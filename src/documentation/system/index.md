---
layout: page
title: System overview
page_id: system-overview
redirects:
  - /docs/
---

{% row_full %}

There are three main areas to consider when starting to understand the infrastructure.

![System overview](/images/documentation/overview/system_overview.jpg)

---

{% endrow_full %}


{% row_image_text_links The Crazyflie family of devices; /images/documentation/overview/CFfamily_thumbnail.jpg %}
{% row_text %}
The Crazyflie family members are the **[Crazyflie 2.0](https://store.bitcraze.io/products/crazyflie-2-0)** nano quadcopter, the **[Crazyflie 2.1](https://store.bitcraze.io/products/crazyflie-2-1)** nano quadcopter, the **[Crazyflie Bolt](https://store.bitcraze.io/products/crazyflie-bolt)** quadcopter controller and
the **[Roadrunner](https://store.bitcraze.io/products/roadrunner)** UWB positioning tag. They are all based on similar hardware but
have a bit different flavours and properties. They run similar firmware and can be used with the other components in the Crazyflie ecosystem,
such as clients and positioning systems.
{% endrow_text %}
{% row_links %}
* {% id_link overview_crazyflie %}
{% endrow_links %}
{%endrow_image_text_links%}


{% row_image_text_links Crazyradio and clients; /images/documentation/overview/CFclients_thumbnail.jpg %}
{% row_text %}
The main client for controling the Crazyflie device family is the **python client** that runs on a PC and communicates via the **[Crazyradio PA](https://store.bitcraze.io/products/crazyradio-pa)** USB dongle. The client uses a **python library**, which also is the main connection point for programs and scripts that communicate with the devices.

Swarms of Crazyflies can be controlled through the python library, the external **CrazySwarm** project or other software.

There are **mobile phone apps** for Android and IOS that connects via BLE, mainly for manual flight.
{% endrow_text %}
{% row_links %}
* {% id_link overview_clients %}
* [CrazySwarm](https://crazyswarm.readthedocs.io/en/latest/)
{% endrow_links %}
{%endrow_image_text_links%}


{% row_image_text_links Positioning technologies; /images/documentation/overview/positioning_thumbnail.jpg %}
{% row_text %}
Positioning support is needed for automated or autonomous flight. There are two in-house position systems in the Crazyflie ecosystem: the **Lighthouse positioning system** that uses SteamVR Base Stations and the Ultra Wide Band based **Loco Positioning System**. It is also possible to integrate with external positioning systems, for instance Motion Capture systems.
{% endrow_text %}
{% row_links %}
* {% id_link overview_positioning %}
{% endrow_links %}
{%endrow_image_text_links%}
