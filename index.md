---
layout: default
title: Ascend
comments: True
---

## Introduction

SMS as a tool for humanitarian aid is becoming an increasingly common tool. UNICEF piloted an [SMS program](http://unicefinnovation.org/projects/rapidsms-nigeria-0) in Nigeria. The Red Cross has developed their own system, [TERA](http://www.ifrc.org/en/what-we-do/beneficiary-communications/tera/). A host of other smaller organizations have sprouted up on the basis of providing aid via SMS.[^1] [UNHCR Innovation](http://www.unhcrinnovation.org/) recently piloted an SMS system in two UNHCR operations: Esmeraldas, Ecuador and San José, Costa Rica. Along the way we made a few blunders, but also did a few things right. We wanted to share our experiences piloting FrontlineCloud in San José, Costa Rica and our lessons learned.

The project, named Ascend, began as a collaboration between Stanford University and UNHCR. The two institutions developed a class called “Rethinking Refugee Communities.” From this, Ascend was born out of a student group with the initial intention of tackling early camp registration by using mobile phone devices. The course took the students through the design process: research, challenge definition, ideation and prototyping. Along the way, UNHCR colleagues were in contact with the students to provide feedback.

About six months after the course ended, Ascend iterated based on needs and limitations discovered in a need-finding trip to Ethiopia. Ascend shifted from a tool to help registration to general purpose messaging. A few key takeaways were observed: one, the need for message classification to handle a large number of inbound SMS (think Gmail classifying messages as priority or not priority); two, the ability to have a feature rich application to conduct polls and surveys via SMS; three, a focus on visualizing the data received and report generation in order to convey effectiveness to potential donors.

![ETHIOPIA]({{ site.baseurl }}/images/ETHIOPIA.jpg)
<small>A Stanford student conducting interviews in Ethiopia to learn more about communications within a camp&nbsp;setting</small>

By the end of 2013, the Ascend group was adopted into UNHCR Innovation where the project would continue and have better access to piloting locations. The decision was made to use FrontlineCloud as a prototype with the goal of better understanding SMS in humanitarian contexts. The first pilot was conducted, as mentioned, in Esmeraldas, Ecuador. In April 2014, FrontlineCloud was piloted in San José, Costa Rica. The following is an account of the process we went through to pilot FrontlineCloud in San José.


## Choosing to prototype

Before any plans and preparations were made, we asked ourselves, “What do we hope to achieve with this prototype?” This framed our pilot with specific objectives. The goals for this particular pilot were:

1.	How do we best utilize SMS to connect with refugees residing in an urban area?
2.	How do we embed a new tool like SMS in organizations to be sustainable, even after the pilot is over?
3.	What types of utilities does an SMS application need to appropriately handle the requirements of UNHCR and non-governmental organization (NGO) staff?

These questions arose from gaps and assumptions we made when conceptualizing the SMS system as well as from the previous pilot in Esmeraldas, Ecuador. With our priorities set, we could now start to frame the pilot to answer these questions.  Based on these goals, we chose to pilot FrontlineCloud. FrontlineCloud is an off-the-shelf solution for SMS that would easily let us answer these questions without having to invest vast amounts of time and financial resources into building our own system only to find out later that SMS perhaps wasn’t an ideal tool for refugees in an urban context.

{% include fidelity.html %}

## Identifying a location

<!-- ![San Jose, Costa Rica]({{ site.baseurl }}/images/MAP.png) -->
<!-- <small>San José, Costa Rica</small> -->

The location and type of population you test can greatly impact the results of your pilot. We found it important to understand the biases that Costa Rica would bring to our results. There were multiple reasons for choosing San José.

*	__Interest from “the field”__ – in the case of Costa Rica, we received a request from their office to pilot the SMS program.  With both headquarters and the field operation committed to working on the project, we believed the pilot would have a high probability of success.
*	__Stability within the region__ – while no refugee situation is truly stable, it is fair to say the refugee situation in Costa Rica is less turbulent than a place like Lebanon. In extreme emergency situations such as in Lebanon, many other things are rightly prioritized over an SMS pilot.
*	__Mobile phone precedence__ – not all UNHCR operations work with populations that have mobile phones or live in areas where there is a strong mobile phone signal. In some areas, the literacy rate isn’t high enough for SMS to be used effectively as a tool of communication. However, Costa Rica ended up being an ideal operation where both literacy rates and cellphone usage were quite high.[^2]

While it isn’t always the best option to prototype in an ideal location, for our purposes we thought it would be the most appropriate way to discover how to effectively use SMS. We assumed that, over time, more and more locations will experience an increase in literacy rates and mobile phone penetration.

## Preparation

A first stage of our innovation process is to ensure that the need for that project actually exists. This was done in Costa Rica through discussions with focus groups and UNHCR staff. Through these methods we decided to focus on three areas that SMS could immediately impact. This helped us define the scope of the project and where we’d focus our efforts. We identified these areas:

*	__Livelihood trainings__ – one of the NGOs we were working with, Association of International Consultants and Advisors or ACAI, offers an array of courses to refugees, including English classes and computer training. ACAI creates these projects and more for asylum seekers and refugees to facilitate integration into the community. Currently they were having difficulty notifying refugees of the new courses that were available and when they were starting. SMS could easily provide a way to inform the relevant people, especially since ACAI already had a database of phone numbers.
*	__Participatory Assessments__ – in a few months time, UNHCR Costa Rica would be conducting Participatory Assessments, which are surveys that UNHCR gives to refugees to evaluate different aspects of the operation. We planned to use SMS as a way to notify and remind people to complete the assessment.
*	__Microcredit Program__ – the last program we’d tackle was a Microcredit program established by an organization called [Aprode](https://www.facebook.com/profile.php?id=100005436465164&fref=ts). Aprode gives out small loans incrementally to refugees as well as other Costa Ricans to start businesses. Throughout the process though, it’s important for Aprode to maintain contact with the people they’ve lent money to in order to assess whether they would need more assistance.

<p class="as-quote">
A first stage of our innovation process is to ensure that the need for that project actually exists.
  <a target="_blank" class="click-to-tweet" href="http://ctt.ec/UaqCB"><i class="fa fa-twitter"></i></a>
</p>

We concretely defined the scope for the pilot so that we’d have clear areas we could focus on. Despite all our advanced preparation though, we learned that the scope often grows as we're responding to real world contexts.

### Choosing a champion

A champion is someone within the organization where you will be piloting who is enthusiastic and strongly supportive of the project. This person often advocates for the project and ensures that it succeeds.  For many reasons identifying a champion is critical for the success of the pilot.

Early on with Costa Rica we identified our champion, Valentina Duque. Valentina had been involved in our Innovation [fellowship program](http://www.unhcrifellows.org/) and proved to be an excellent champion. She was instrumental in coordinating the implementation, getting key stakeholders involved and ensuring follow up from various other organizations.

![Valentina Duque]({{ site.baseurl }}/images/VALENTINA.jpg)
<small>Valentina helping out during a training with Aprode</small>

### Preparation tasks

Depending on the pilot, there’d be a varying number of tasks that need to be completed before the pilot takes place. Ordinarily, we would assume most of the responsibility to complete these tasks in order to save the operation some time and effort. However, for a couple reasons, the opposite could be beneficial. One, if the operation is unable to complete a few tasks before the pilot because of time constraints, then this often indicates that the operation does not have the capacity to take on this pilot. Two, when the work comes from the operation, there is more ownership over the pilot and thus there is greater effort to make the pilot succeed. We worked with the Costa Rica operation to complete these tasks before the pilot began:

*	__Contact database development__ - This comprised of aggregating the disparate sources of phone numbers from ACAI, Aprode, and UNHCR. With an Excel sheet containing all of the phone numbers, we would be prepared to send messages as soon as the software was ready.
*	__Monitoring and evaluation plan__ – Before starting the pilot, we wanted to agree on outputs that we’d focus on and the indicators to help measure the success of achieving those outputs.
*	__Pilot implementation plan__ – This was a rough plan of how the software would be rolled out to the various organizations.
*	__Software and phone installation__ – To ensure that everything would work upon arrival, we walked through the installation of FrontlineCloud over video conference.

## Implementation

Even after months of preparation, the ability to improvise on the ground is almost always a necessity. In Costa Rica the biggest hiccups came when it was time to run the actual FrontlineCloud software. Here was our process for an eleven-day mission.

{% include gantt.html %}

Most of the time was spent preparing the messages and the software. Our trainings consisted of two parts. The first part was the "theory" part where we explained what FrontlineCloud could do and the different benefits of SMS. The second part was the "practical" part where we would have each person interact with FrontlineCloud and practice sending messages. By frontloading the mission with trainings, it was easier to then focus on the types of messages we would send for the rest of the pilot.

![Running practical training]({{ site.baseurl }}/images/TRAINING.jpg)

<small>Conducting a training with ACAI. This was the hands-on component.</small>

## Community involvement

At UNHCR, we try as hard as possible to keep refugees at the center of our work. That means for pilots and projects we try to get as much feedback from refugees as we can. Before the implementation of the project, we sat down with four refugees to engage in a conversation about communication with organizations like UNHCR. We've anonymized the interviews and posted our notes for your [viewing](https://docs.google.com/document/d/1bMDeYQ0fI1IrIPhDY2ofc4iKdH96ln03KL-8HOw5nY4/edit). In short, some key takeaways were:

* __Phone presence__ - most of the interviewees had mobile phones and used them, though some only used them for family matters. The majority cited mobile phones as a good means of reaching them. There were also two who said it was better to call rather than send an SMS.
* __SMS uses__ - by and large, most of the interviewees wanted more information on activities and opportunities that were available to them. In addition, some thought it would be a good way to ask questions to UNHCR, ACAI, or Aprode.
* __Challenges faced__ - the biggest challenges for the refugees upon arrival was surviving in a context they were not used to. In a similar vein, they also found it very difficult to find jobs.

<p class="as-quote">
At UNHCR, we try as hard as possible to keep refugees at the center of our work. That means that for pilots and projects we try to get as much feedback from refugees as we can.
  <a target="_blank" class="click-to-tweet" href="http://ctt.ec/c2fcI"><i class="fa fa-twitter"></i></a>
</p>
From these interviews we were able to begin formulating ways to address the challenges presented by the refugees. At the end of the monitoring and evaluation phase, we again contacted the same refugees to get their opinion on the project. These interviews were conducted over the phone and can be viewed [here](https://docs.google.com/document/d/1-5v-UI1kdsaQiAjk2EUTT21DXQKpPQV9Z6IT1teRTlA/edit). The responses were overwhelmingly positive which is a big success for the pilot as a whole.


{% include interviews.html %}

## Follow up and Monitoring

Now that FrontlineCloud had been installed and trainings had been conducted, the monitoring and evaluation plan (M&E) that was setup upon arrival and then reviewed before the end of the pilot became essential.

When done correctly, M&E allows us to iterate on our solution. Without it we are merely guessing at how to improve. For Costa Rica we chose the indicators listed below as the ones we would record. There was a fine balance between overly bureaucratizing the process, reducing the quality of information recorded and selecting too few indicators, making it difficult to determine how to iterate.

| Indicator | Purpose |
| -------- | -------- |
| # of messages sent per week | This is to measure an organization's engagement with the SMS system   |
| % of refugees interested in using SMS to communicate with UNHCR | This is to measure the population of concern's interest in the project |
| # of refugees participating in the pilot | To determine growth of system |
| % of refugees who actively send messages to UNHCR staff | To measure the population of concern's engagement with the system |
| % of refugees who respond to a poll sent by UNHCR staff | To measure the effectiveness of questions asked in polls |

{% include acai.html %}


We conducted a three-month period of monitoring. The first six weeks included Skype meetings each week to detail progress of the system. During the meetings we would discuss things that were going well and thing that weren’t. These sessions were also critical for understanding how the system was performing.

At the end of the three-month evaluation period, we created two surveys for Costa Rican staff to complete. One survey was for those that interacted with the FrontlineCloud software directly, while the other was for those in the organization that did have direct contact with the software but were still able to send messages through their focal point.

In addition to gathering feedback from the staff members themselves, we also conducted interviews with refugees about who had been receiving SMS from FrontlineCloud.

<p class="as-quote">
  When done correctly, M&E allows us to iterate on our solution. Without it we are merely guessing at how to improve.
  <a target="_blank" class="click-to-tweet" href="http://ctt.ec/6q5hJ"><i class="fa fa-twitter"></i></a>
</p>

## Lessons Learned

After monitoring for three months, we underwent the process of consolidating and processing the data to come up with tangible lessons learned from the pilot. These lessons will serve to shape the steps we take to improve the solution.

### Technical Issues

A few issues with the software became apparent when working with FrontlineCloud. All these issues have been reported to FrontlineCloud and hopefully will be corrected in the future. Here are a few common software "gotchas" that should always be checked before a pilot begins, including this one.

*	__Internationalization/Locality__ - The compatibility across all languages and regions was a feature we initially overlooked. When using FrontlineCloud we came across several issues when using characters outside the Roman alphabet. Another thing to be cognizant of is the incompatibility of file types in different regions. While rare, it was an issue we experienced.
*	__Scalability__ – When testing FrontlineCloud beforehand, only small contact databases were used. However, upon arrival we needed to use much larger databases and the software did not work as well. We should have tested the software on representative database sizes.
*	__Low connectivity__ – In places where the Internet connection could be unreliable, SMS software needs to be able to handle syncing. FrontlineCloud worked well when the connection was great. However, we experienced difficulties in buildings where the Internet connection would sporadically go out. The result was sometimes duplicate messages in the system, or worse, missing messages.

### Trust Building

Initially we had started the pilot with a prepared list of contacts to message. Sending the blast welcome message explaining the project elicited many responses saying, “Who is this?” or “Why am I receiving this?” After interviewing refugees we began to see a pattern. People were hesitant to trust a message from an unknown number. We ended up tackling this issue by first advertising the number in UNHCR and the other NGOs so that people would become familiar with the project and expect to receive messages. In addition to that, we set up boxes in which people could drop their contact information and we would then add that phone number to the FrontlineCloud database. In this way we increased trust in and awareness for the project.

![SMS poster for Costa Rica]({{ site.baseurl }}/images/SMS-COSTARICA-POSTERS.png)

{% include poster_caption.html %}

### Invalid or unused phone numbers

Currently, there is no functionality in FrontlineCloud that enables you to determine whether a phone number you just messaged is inactive. This ended up being an issue since the contact databases were widely known to be out of date. Therefore, we had to assume that the only people who received the SMS were those that responded. In fact, to get a better estimate of the number invalid phone numbers in use, one of the UNHCR workers did a small trial on the existing contacts. UNHCR sent out a poll to 50 random contacts. For those that did not respond to the poll, he proceeded to followup by calling the number. After each call he annotated the reason for not responding to the poll. Below features a graph of the 50 contacts - the fraction that replied to the poll and the others who he had called to follow up.

{% include phone_breakdown.html %}

Looking at the above chart it is easy to see that 20 out of 50 contacts need to be updated - a full 40% of the contacts were out of date. This gave us an indication that the Excel contact database desperately needed to be updated or we could miss 40% of potential recipients. After this discovery, UNHCR worked with ACAI to update all 670 contacts. The database is now much more complete and better formatted. This though represents a problem that many UNHCR operations face when they work in cities. Refugees tend to change address and phone number on a relatively frequent basis.

{% include stat_significance.html %}

### Consistent SMS programming

One strategy that worked well for UNHCR was setting up a consistent messaging program. Every week UNHCR would send out some sort of asylum-related fact or interesting event that was happening. This became a way for UNHCR to engage with its users on a weekly basis, and they garnered many positive responses from the receivers.

Here are a few sample SMS sent by UNHCR and ACAI:

{% include sms.html %}

### Two-way communication

At ACAI, we planned to send many broadcast messages and polls to their entire contact database. After a few weeks, ACAI found that it was more useful to use the system to communicate on an individual level. This is why you'll notice the dip in messages sent by ACAI after the beginning weeks of the pilot.

### Institutional knowledge of the system

A very difficult part of running a pilot is embedding the system knowledge within the organization. We accomplished this through establishing a champion for the project who would be able to carry on the project after UNHCR Innovation had left. In addition to this, we ran as many trainings as possible with UNHCR, ACAI, and Aprode. At the trainings we would include as many people as we could, including managers. The training was broken down into two sections. The first was a one-hour overview of the system designed for those who wouldn’t be interacting directly with the system. The second training was more practical in nature, geared toward those who would be using FrontlineCloud.

### Behavior change

In addition to embedding a culture of SMS within an organization, it is also takes time to introduce the program to refugees and more time to have it gain traction. Using SMS at UNHCR represents a shift in the traditional way refugees contact staff. This change should be addressed early on. New refugees and asylum seekers are now briefed about the system to ensure that each person is aware that SMS is an option for communication.

### Time of sending the messages

We knew it took hours (sometimes, even a whole day) to send bulk messages to hundreds of contacts. However we overlooked the fact that if we sent the bulk message at 6pm, many people wouldn't receive it until the wee hours of the morning. We received a few complaints about this and promptly decided that broadcast messages had to be sent in the morning or they’d have to be delayed until the next day.

### Usage guidelines

We soon discovered a need for establishing a human system for each organization to send SMS after the pilot was over. We didn't want everyone haphazardly sending messages, but we also didn't want one person to have absolute control over the system. Under these constraints, we came up with a plan that composed of:

* __Focal point__ - This person was responsible for sending broadcasts and polls. S/he was also the person to receive message requests from others in the organization.
* __Daily messenger__ - This person handled all the messages that were sent into the system on an individual basis.
* __Supervisor__ - The supervisor was in charge of giving the final check on the broadcast messages that were sent.

You can view our more detailed version [here](https://docs.google.com/document/d/14C5gVPdaXYDcRy6uoHMVeJlnFavVHKuHurwKriIJDoI/edit). This also includes a few guidelines on the types of messages that should and should not be sent.

<p class="as-quote">
  A very difficult part of running a pilot is embedding the system knowledge within the organization. We accomplished this through establishing a champion for the project who would be able to carry on the project after UNHCR Innovation had left.
  <a target="_blank" class="click-to-tweet" href="http://ctt.ec/P91dA"><i class="fa fa-twitter"></i></a>
</p>

## Conclusion

After a pilot that began in January 2014 and came to a close in September 2014, what did these nine months teach us? We first went back and looked at the [questions]({{ site.baseurl }}/#choosing-to-prototype) we set out to answer.

Did we find out ways to best utilize SMS to connect with refugees? Of course there's always more to learn, but we would still answer yes. We learned about different roles an SMS system can play. Will it mainly be used for polling, broadcast messages, answering individual queries or all three? SMS can go a long way to educating asylum seekers and refugees about their rights and opportunities.

Did we find out ways to embed an SMS system into an organization? By conducting as many trainings as possible, and setting up a guideline for usage within an organization, we were able to establish a lasting and sustainable impact on the Costa Rica operation.

Did we find out what staff need in an SMS application? After becoming deeply familiar with FrontlineCloud, we've developed lots of areas where the SMS applications could be improved. From this pilot, we can now make recommendations for the requirements that a UNHCR SMS system would have.

There were many bumps along the road and not everything worked out as planned, but we'd undoubtedly say the pilot was a success. The Costa Rica UNHCR operation is now planning on setting up FrontlineCloud with two other refugee organizations in San José, after receiving requests to do so. Most importantly, the feedback from refugees was extremely positive and indicates that this should be a part of more operations.

The next steps for us would be advocate that UNHCR adopts a common SMS system that is deployed in each operation. Currently, UNHCR has many SMS systems randomly spattered across the globe. The lack of consolidation to date is influenced mostly by the level of technical capacity that a specific country office has. In fact, there exists a giant spreadsheet of all the different SMS systems that UNHCR currently uses. Moving forward, it would be ideal to have a deploy kit that UNHCR can use to setup SMS capabilities.

As often as possible, UNHCR Innovation tries to be as transparent as possible. Please feel free to leave any feedback or questions!

Hate the web? <a target="_blank" href="{{ site.baseurl }}/report_content.pdf">Download the PDF.</a>

{% include contact.html %}

{% include comments.html %}

[^1]: [Souktel](http://www.souktel.org/development), [Dimagi](http://www.dimagi.com/mobile-health/), [Voix des Kivus](http://www.ushahidi.com/blog/2011/05/16/voix-des-kivus-a-crowd-seeding-system-in-drc/), [Medic Mobile](http://medicmobile.org/), [Telerivet](https://telerivet.com/)
[^2]: Cell phone subscriptions per 100 inhabitants in [Costa Rica and Colombia](http://www.google.com/publicdata/explore?ds=emi9ik86jcuic_&ctype=l&strail=false&bcs=d&nselm=h&met_y=i911&scale_y=lin&ind_y=false&rdim=country&idim=country:CR:CO&ifdim=country&hl=en_US&dl=en&ind=false&icfg)

<script type="text/javascript">
//<![CDATA[
  (function() {
    var shr = document.createElement('script');
    shr.setAttribute('data-cfasync', 'false');
    shr.src = '//dsms0mj1bbhn4.cloudfront.net/assets/pub/shareaholic.js';
    shr.type = 'text/javascript'; shr.async = 'true';
    shr.onload = shr.onreadystatechange = function() {
      var rs = this.readyState;
      if (rs && rs != 'complete' && rs != 'loaded') return;
      var site_id = 'dcc228027f8c3c12fefc7de7391790db';
      try { Shareaholic.init(site_id); } catch (e) {}
    };
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(shr, s);
  })();
//]]>
</script>
