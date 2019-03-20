<!--
.. title: Setting Up Git Pages With Gandi.net Domain
.. slug: setting-up-git-pages-with-gandinet-domain
.. date: 2018-12-28 17:11:04 UTC-05:00
.. tags: News, domain, Gandi
.. category: 
.. link: 
.. description: 
.. type: text
-->
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I would to thank the customer service of <a href="https://twitter.com/github?ref_src=twsrc%5Etfw">@github</a> and <a href="https://twitter.com/gandibar?ref_src=twsrc%5Etfw">@gandibar</a> for helping me with my Git Pages and custom domain.  I will have a blog post on how to do a custom domain with <a href="https://t.co/393tKUJM5K">https://t.co/393tKUJM5K</a> ready by the end of this weekend!  Or today.</p>&mdash; Svetlana Belkin (@senseopenness) <a href="https://twitter.com/senseopenness/status/1078774158165766150?ref_src=twsrc%5Etfw">December 28, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

After a week or so of trying to get the custom domain to work with Git Pages from Git Hub, I got it to work. Once again, it was from not doing my homework on how domains work as from what I bolded in the e-mail that Dante A. from Gandi.net's customer support. But I can't blame myself on doing my homework.

>Hello again,

>Here is the current configuration of your DNS Records:

>Github 1800 IN A 185.199.108.153

>Github 1800 IN A 185.199.109.153

>Github 1800 IN A 185.199.110.153

>Github 1800 IN A 185.199.111.153

>blog 10800 IN CNAME username.github.io

>webmail 10800 IN CNAME webmail.gandi.net.

>www 10800 IN CNAME webredir.vip.gandi.net.

>If you want this to be available at your bare domain and 'www' subdomain, you should change these records to the following:

>@ 1800 IN A 185.199.108.153

>@ 1800 IN A 185.199.109.153

>@ 1800 IN A 185.199.110.153

>@ 1800 IN A 185.199.111.153

>blog 10800 IN CNAME username.github.io.

>webmail 10800 IN CNAME webmail.gandi.net.

>www 10800 IN CNAME username.github.io.

>**The '@' A record represents your bare domain. Please make these changes to the records and allow for them to propagate. Once done, your site should point to the Github page as expected.**

>Best,
>--
>\o/ Dante A.
>G https://www.gandi.net/

Hopefully there will not be anymore issues with my site and blog.