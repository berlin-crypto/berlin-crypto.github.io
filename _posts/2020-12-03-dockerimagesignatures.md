---
#leave this alone
layout: post

#Whats the title of your event.
title:  "Integrity of Docker Images - Signatures, Verification and a Tool for k8s"

#The date of the event.
date:   2020-12-03 19:00:00 +0000

#Start time of the event
start_time: "19:00"

#end time of the event
end_time: "21:00"

#event organiser details
organiser: "Christoph Hamsen"

#Make sure you setup your Organiser details in the \_data directory in the organisers.yml file

cover: '../containerimagesignatures.jpg'
location: Remote via Microsoft Teams (link below)
cover_credit: '<p>Event cover photo "The Connaisseur" by SSE - Secure Systems Engineering</p>'
cover_credit_short: 'SSE'

---

After a long break due to the COVID-19 situation, we are back with our first online event just before Christmas!

This time, my colleague Philipp from [SSE](https://securesystems.de/) will give a talk on practical application of cryptography for signing and verifying Docker images in Kubernetes including a live demo of our open-source solution Connaisseur ([GitHub](https://github.com/sse-secure-systems/connaisseur)).

So sign up, get your Christmas sweater, a cold or hot beverage and join us for this event!

[**Join via Microsoft Teams**](https://teams.microsoft.com/l/meetup-join/19%3ameeting_NWMxYzY0NDUtOTM4YS00ZDEzLTk1YjItYTA2YTBmOTUwNzQz%40thread.v2/0?context=%7b%22Tid%22%3a%2269e6ba83-404c-4550-9e3d-f26613ec0fb3%22%2c%22Oid%22%3a%2223633975-4d32-40d0-922c-01973f1a8fc8%22%7d) **on December 3rd 2020 at 7pm.**

<br/>


# Integrity of Docker Images - Signatures, Verification and a Tool for k8s (Philipp Belitz)
In modern software development, the introduction of containers and their orchestration have led to faster delivery, more flexible deployment and higher scalability and stability of applications. These packaged applications are distributed via images that serve as immutable starting snapshots for containers in the runtime environments.

Consequently, ensuring integrity and authenticity of images is of critical importance for the secure deployment of software. This can be achieved by adding signatures to guarantee authenticated and unaltered code. However, practical implementation of image signing and verification has remained a major challenge. This talk dives into current solutions and shortcomings for the two most popular containerization and orchestration engines, Docker and Kubernetes. It will touch on Docker Content Trust (DCT), Notary and The Update Framework (TUF) used for Docker image signing and introduce [Connaisseur](https://github.com/sse-secure-systems/connaisseur), a signature verification tool for Kubernetes. Live demo included ;-)


Get slides [(pdf)](/assets/Berlin Crypto Connaisseur.pdf)

<br/>
<a href=' https://www.eventbrite.com/e/integrity-of-docker-images-signatures-verification-and-a-tool-for-k8s-tickets-129022328257?ref=estw' class="button button-primary">Register</a>

