---
layout: page
title: Create an event
navigation_title: Create Event
permalink: /create/
cover: '../title_pic.jpg'
---


# Getting started
Create a new .md file or copy an existing post in the  `_posts` directory to get started. The post file name must be in this format:

{% highlight markdown %}
YYYY-MM-DD-title.md
{% endhighlight %}

# Config for posts

{% highlight markdown %}
---
#leave this alone
layout: post

#Whats the title of your event.
title:  "Talk on Provable Verifiable Randomness Extractors"

#Url to your cover photo for your event. [optional - default will be used if not given]
cover: "https://frontendmasters.com/assets/es6-logo.png"

#The date of the event.
date:   2016-02-01 16:04:19 +0000

#Start time of the event
start_time: "12:00"

#end time of the event
end_time: "13:00"

#event organiser details
organiser: "Jane Doe"

#Make sure you setup your Organiser details in the \_data directory in the organisers.yml file

#Alternatively organiser details can be given as follows.
organiser_email: "jane.doe@example.com"
organiser_name : "Jane Doe"
organiser_photo: "https://example.com/jane.doe.jpg"

---
{% endhighlight %}

# Post content

After you have setup your config, all you need to do now is write your content using markdown.

# Test locally
`jekyll serve` allows you to test the website locally.

# File a pull request with your changes
Take your changes and file a PR against [https://github.com/berlin-crypto/berlin-crypto.github.io](https://github.com/berlin-crypto/berlin-crypto.github.io).
