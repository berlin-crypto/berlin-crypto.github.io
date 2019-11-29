---
#leave this alone
layout: post

#Whats the title of your event.
title:  "Shared-Secrets Service - Why GnuPG wasn't secure enough."

#The date of the event.
date:   2019-12-11 18:30:00 +0000

#Start time of the event
start_time: "19:00"

#end time of the event
end_time: "22:00"

#event organiser details
organiser: "Christoph Hamsen"

#Make sure you setup your Organiser details in the \_data directory in the organisers.yml file

cover: '../sharedsecrets.png'
location: SSE - Secure Systems Engineering, Gebäude F, 5. Stock, Mauerstraße 79, 10117 Berlin
cover_credit: '<p>Event cover photo <a href="https://pixabay.com/vectors/dangling-giving-hands-human-keys-2023222/">"Dangling Keys"</a><span> and <a href="https://pixabay.com/illustrations/background-christmas-vintage-old-1787033/">"Vintage Christmas Background"</a><span> from <a href="https://pixabay.com/">pixabay</a></span> is licensed under <a href="https://pixabay.com/service/license/" style="margin-right: 5px;">Pixabay License</a></p>'
cover_credit_short: 'pixabay'

---

In our Christmas edition, we will learn about sharing secrets securely without storing them on a webserver and why sometimes GnuPG simply isn't secure enough.

Join us at SSE ([Secure Systems Engineering](https://securesystems.de/)) where Kenny will talk about "Shared-Secrets Service - Why GnuPG wasn't secure enough". Doors will open at 18:30 with some drinks and snacks. There will be plenty of time to socialise and discuss any issues of interest.

So get out your best Christmas sweater and join our community of Berliners interested in everything around cryptography!

# Shared-Secrets Service - Why GnuPG wasn't secure enough. (Kenny Niehage)
Shared-Secrets is a web application that can be used to create links containing encrypted secret information. The application used GnuPG but was recently rewritten to use a custom message format. This talk delves into why GnuPG just wasn't secure enough.

The source code can be found on [GitHub](https://github.com/syseleven/shared-secrets). An example implementation is hosted by [SysEleven](https://secrets.syseleven.de/).

<br/>
<!--<a href=' https://www.eventbrite.co.uk/e/shared-secrets-service-why-gnupg-wasnt-secure-enough-tickets-83945622617?ref=estw' class="button button-primary">Register</a>-->
<div id="eventbrite-widget-container-83945622617"></div>

<script src="https://www.eventbrite.co.uk/static/widgets/eb_widgets.js"></script>

<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Order complete!');
    };

    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '83945622617',
        iframeContainerId: 'eventbrite-widget-container-83945622617',

        // Optional
        iframeContainerHeight: 425,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>