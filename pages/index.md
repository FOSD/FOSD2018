---
title: Home
---
## About
The FOSD meeting is an informal meeting designed to bring together researchers working on feature-oriented software development (FOSD). 
It started in 2009 and has since evolved and expanded in what now is an international event. 
Since 2014, the meeting is held in English. 
More details about FOSD and previous FOSD meetings can be found at [fosd.net](http://fosd.net). 
For the [FOSD2016 Workshop](http://fosd.net/workshop2016), please visit FOSD'16 WORKSHOP

The format of the FOSD meeting consists of short presentations from each participant (approx 15 min) with plenty of time for discussion.
Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations.
FOSD is a place for discussion, not a publication venue.
Participants can present previously published work as well as unpublished work, including early ideas and work in progress.
The key is to encourage discussions, to receive feedback and to create a network for new collaboration

An invited talk will be given by Julia Lawall (INRIA)

Every year there is an informal competition, FOSD Cool Wall, where everyone votes for the coolest name of a tool that has been presented during the meeting.

**The deadline for the abstract is January 16th, 2017.**
We will provide notifications one week later. If you need more lead time for visa application or travel planning, reach out to us.

### Your Stay
The fee includes your stay, all meals, the social event on Wednesday afternoon and a bus transfer to Darmstadt main station on Friday.
Please just ask me for your personal printout of the receipt of your payment during the next week.
*IMPORTANT:* We decided to exclude drinks from the fee to keep the overall costs moderate (the only exception is coffee and tea during the coffee breaks).
You can purchase all kinds of drinks at any time at the hotel during your stay (payment cash or by credit card).
Since tap water is of very good quality in Germany, we recommend you to bring with you a drinking bottle which you can refill in your room.
In addition, we will try to organize some drinks at cost price for the evening time.

### Your Talk
This year, every participant has an allocated slot of 25 minutes.
Please prepare slides that do not require more than 13 minutes of presentation such that we have at least half of the slot for discussions.
We will enforce the 13 min time limit strictly.

![participants]({% link assets/img/participants.jpg %})

## Location & Travel Information
The FOSD meeting 2017 will take place in TBD.

{% comment -%}
    TODO Google Maps... braucht einen API Key usw.
    Liquid Funktion bauen?
{%- endcomment -%}

### Arrival by car
TBD
### Arrival by train
TBD
### Arrival by plane
TBD
### Departure
TBD

## Keynote Speakers

## Schedule
{% for conf_day in site.data.schedule %}
#### Schedule {{ conf_day.day | date: "%A, %b %e" }}
{% for session in conf_day.sessions %}
Session: {{ session.from | date: "%R" }} - {{ session.to | date: "%R" }}, Chair: {{ session.chair }}
{% for talk in session.talks %}
* **{{ talk.speaking }}**: {{ talk.title }}
{% endfor %}
{% endfor %}
{% endfor %}

## Participants
We are glad to have the following participants.

{% assign participants_sorted = site.data.participants | sort: "lastname" %}
|Name|Title|University|
|:-: +:-   +:-        |
{% for p in participants_sorted -%}
|{{ p.firstname }} {{ p.lastname }}|{{ p.title }}|{{ p.university }}|
{% endfor %}{: id="participants_table" }


## VISA Information
If you are a non EU citizen, please find if you need a visa for entering Germany and Schengen Area.
A list for citizen of countries that need a visa can be found here [Do I need a visa?](http://www.auswaertiges-amt.de/EN/EinreiseUndAufenthalt/Visabestimmungen_node.html).

## Contact
For abstract submission or any other questions please send an e-mail to Malte Lochau: malte **dot** lochau at es **dot** tu-darmstadt **dot** de.
