---
title: Home
---
## About
The FOSD meeting is a yearly informal meeting to bring together researchers working on feature-oriented software development (which includes product lines, software variability, configuration management, software architecture, and more).
The meeting started 9 years ago to bring several research groups with common interests closer together, has successfully been expanded and repeated 9 times with 20 to 50 participants each, and has established countless collaborations since.

The format of the FOSD meeting consists of short presentations from each participant (approx 15 min) with plenty of time for discussion.
Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations.
FOSD is a place for discussion, not a publication venue.
Participants can present previously published work as well as unpublished work, including early ideas and work in progress.
The key is to encourage discussions, to receive feedback and to create a network for new collaboration

Every year there is an informal competition, FOSD Cool Wall, where everyone votes for the coolest name of a tool that has been presented during the meeting.

The FOSD meeting 2018 will be held in Gothenburg, Sweden, from June 4 to June 7.
More details about FOSD and previous FOSD meetings can be found at [fosd.net](http://fosd.net). 
For the [FOSD2018 Workshop](http://fosd.net/workshop2018), please visit FOSD'18 WORKSHOP

An invited talk will be given by Prof. Myra Cohen (https://cse.unl.edu/~myra/).

**The deadline for the abstract is February 1, 2018.**
We will provide notifications one week later. If you need more lead time for visa application or travel planning, reach out to us.

### Hotel
The fee includes your stay, all meals, the social event on Wednesday afternoon and a bus transfer to Darmstadt main station on Friday.
Please just ask me for your personal printout of the receipt of your payment during the next week.
*IMPORTANT:* We decided to exclude drinks from the fee to keep the overall costs moderate (the only exception is coffee and tea during the coffee breaks).
You can purchase all kinds of drinks at any time at the hotel during your stay (payment cash or by credit card).
Since tap water is of very good quality in Germany, we recommend you to bring with you a drinking bottle which you can refill in your room.
In addition, we will try to organize some drinks at cost price for the evening time.

We made room reservations at Quality Hotel Panorama, which is just 900m away from the Chalmers Campus. The hotel is paid directly via the registration fee.

Quality Hotel Panorama Gothenburg
Eklandagatan 51-53
Gothenburg, Sweden
http://quality-hotel-panorama.gothenburg-hotels.com/en/



### Your Talk
This year, every participant has an allocated slot of 25 minutes.
Please prepare slides that do not require more than 13 minutes of presentation such that we have at least half of the slot for discussions.
We will enforce the 13 min time limit strictly.

![participants]({% link assets/img/participants.jpg %})

## Location & Travel Information
The FOSD Meeting 2018 will take place at Chalmers Technical University in Gothenburg, Sweden. Specifically, it will be held at Campus Johanneberg (http://www.chalmers.se/en/about-chalmers/premises-and-campus/Pages/find-your-way-to-chalmers.aspx), which is the larger one of the two Chalmers Campus (the smaller one is at Lindholmen).

{% comment -%}
    TODO Google Maps... braucht einen API Key usw.
    Liquid Funktion bauen?
{%- endcomment -%}

### Arrival via Rail
Exit the train at the central station/the Nils Ericsson terminal.  Take bus 16, destination Högsbohöjd, from the stop Nordstan, just outside the terminal. From Drottningstorget, also just outside the central station, you can take tram 13, heading "Sahlgrenska", to Chalmers. From Brunnsparken, approximately 500 meters from the central station there are additional tram lines that will take you to Chalmers. From there you can walk to the hotel or come directly to the FOSD meeting on campus. Please visit Västtrafik for details.  

### Arrival via Air
Landvetter Airport in Gothenburg has daily flights to and from most major European cities. It is possible to take a Taxi from the airport directly to the hotel, and the price from the airport to the city center is around SEK 400 (45€).
http://www.taxigoteborg.se/En/Home

There is also a convenient airport bus service that connects Landvetter Airport to the Central Station in Gothenburg. The bus stop is right outside the airport’s entrance and 2-4 buses run every hour. The travel time to the Central Station is about 30 minutes, and the trip costs SEK 105 (approximately 11 €). The buses are called Flygbussarna and tickets can be purchased online (and shown to the driver on the mobile phone), via totems at the airport, or directly on the bus (a bit more expensive). If you want to use these busses to get to Chalmers Johanneberg Campus or to the hotel, get off the airport bus at station Korsvägen. It is the first stop when the bus arrives Gothenburg, after only 15min travel time.
https://www.flygbussarna.se/en/landvetter 

### Departure
TBD

## Keynote Speakers
Prof. Myra Cohen (https://cse.unl.edu/~myra/)

## Schedule
{% for conf_day in site.data.schedule %}
June 4 to June 7, 2018
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
For abstract submission please send an e-mail to Shurui Zhou:  <shuruiz@cs.cmu.edu>. <br />
For other questions please send an e-mail to Thorsten Berger:  <thorsten.berger@chalmers.se>.

## Organizers
Thorsten Berger <thorsten.berger@chalmers.se> <br />
Shurui Zhou <shuruiz@cs.cmu.edu> <br />
Christian Kästner <kaestner@cs.cmu.edu>  <br />
Sven Apel <apel@uni-passau.de><br />

