---
layout: page
title: About Us
subtitle: Meet the Team!
---



## Executive Leadership
The executive board forms the leadership of WCRL. They are in charge of logistics, organization and any future projects that help expand WCRL.
<!--- handy trick found on stackoverflow to use html in md files --->
{% capture team-section %}
{% include team-section.html role = "Executive Leadership" %} 
{% endcapture %}
{{ team-section | replace: '    ', ''}}

## League Coordinator
The league coordinators are in charge of bridging the gap between the the executive board and the general body of WCRL. They send out the monthly newsletters and are in charge of the social media as well.
{% capture team-section %}
{% include team-section.html role = "League Coordinator" %} 
{% endcapture %}
{{ team-section | replace: '    ', ''}}

## Build Technicians
Build Technicians form the heart and soul of WCRL. They are the elite squad in charge of helping you guys design, build, and debug (yay!) your robots.
{% capture team-section %}
{% include team-section.html role = "Build Technician" %} 
{% endcapture %}
{{ team-section | replace: '    ', ''}}

## Freshman Ambassadors
Fresman Ambassadors are the newbies to WCRL. During their first semester they will compete in the semesterly tournament (just like you) and will slowly be more integreated into the E-board.
{% capture team-section %}
{% include team-section.html role = "Freshman Representative" %} 
{% endcapture %}
{{ team-section | replace: '    ', ''}}

## 3lb Robot Team?