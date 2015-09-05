---
layout: post
title: The browser wars are over. Please notify the enterprise.
permalink: /notify-the-enterprise/

summary: I shouldn't have to install a virtual machine to sign up for insurance.
published: true

accent: 00A2EB
---
<figure>
<img src="/images/post-images/2015-09-05-enrollment.jpg" alt="Important information about recommended browsers for annual enrollment memo" />
<figcaption>It gets worse.</figcaption>
</figure>

I received my annual benefits and insurance guide in the mail this week, along with a pre-emptive note titled "Important information about recommended browsers for annual enrollment". I found this interesting as someone who spends a lot of time thinking about and implementing responsive web design solutions to make information accessible across devices, web browsers and assistive technologies. I also do the print design and layout for my organization's biannual employee newsletter, which includes information about insurance plan changes each year.

My insurance provider covers an estimated 300,000 individuals, according to their website. This memo was sent to home addresses in reference to logging onto the employee self-service portal to review insurance and benefits information before making changes: 

<blockquote>You probably will not be able to complete your benefits or enrollment selections if you use the following browser or devices: <ul><li>Chrome</li>
<li>Any Mobile Devices
<ul>
<li>iPads</li>
<li>iPhones</li>
<li>Android Phones</li>
<li>Android Tablets</li>
<li>Windows Phones</li>
<li>Windows Tablets</li>
</ul></li>
</ul></blockquote>

Here are the two browsers they did recommend:

> Internet Explorer 9.0 or 10.0 is your best choice and is available for most computers.

Who gets to define "computer"? In 2015 the number of mobile-only internet users [exceeded the number of desktop-only users](https://www.comscore.com/Insights/Blog/Number-of-Mobile-Only-Internet-Users-Now-Exceeds-Desktop-Only-in-the-U.S). This was already [estimated back in 2011](http://www.lukew.com/ff/entry.asp?1405). Today's smartphone has more computing power than the technology powering the first moon landing. Unfortunately, if we limit the definition of "computer" to "desktop PC", this is also a misleading statement, when applied broadly. The last major version of IE was 11 (it's called Microsoft Edge now). Most enormous technology companies do not want to support older versions of their products or make old versions widely available. Starting in 2011 (IE version 9.), Microsoft began [releasing Internet Explorer with automatic updates turned on by default](https://web.archive.org/web/20120103192928/http://windowsteamblog.com/ie/b/ie/archive/2011/12/15/ie-to-start-automatic-upgrades-across-windows-xp-windows-vista-and-windows-7.aspx). This is standard practice for most major web browsers and a lot of software these days. From the language in Microsoft's own press release:

<figure>
<blockquote>The Web overall is better &ndash; and safer &ndash; when more people run the most up-to-date browser... For consumers, the safety benefits are one of the key reasons that the industry has been moving towards automatic updates as the norm. This is increasingly important since the biggest online threat these days is socially engineered malware, which typically targets outdated software like Web browsers.</blockquote>
<figcaption>Ryan Gavin, <a href="https://web.archive.org/web/20120103192928/http://windowsteamblog.com/ie/b/ie/archive/2011/12/15/ie-to-start-automatic-upgrades-across-windows-xp-windows-vista-and-windows-7.aspx">IE to Start Automatic Upgrades across Windows XP, Windows Vista, and Windows 7</a>, Dec. 15, 2011. Retrieved from the Internet Archive Sept. 5, 2015</figcaption></figure>

One of the great ironies in web development is that browser makers tell their consumers to update their software for security reasons, and enterprise organizations do not support newer software versions for....security reasons. 

Legacy IE is very common in large enterprise organizations for their internal operations and web portals. Oftentimes these portals will only operate on specific versions of a web browser, and will only be updated after the next major release (or two). Microsoft fully understands this, and prioritizes [legacy support into each release cycle](https://blogs.windows.com/msedgedev/2015/08/26/how-microsoft-edge-and-internet-explorer-11-on-windows-10-work-better-together-in-the-enterprise/) of its web browser. Enterprises and consumers can turn this auto-update feature off if they want. But Microsoft prefers you to use the new product, and you're probably better off doing so, especially if you are more "consumer" than "enterprise". If you do not have a Windows PC, however, this is the message you get when you try to get the "best choice available to most computers":

<img class="browser" src="/images/post-images/IE-fail.png" alt="Screenshot text: Looking for Internet Explorer? You’re in the right place, but Internet Explorer requires a Windows PC."/>

If you are on Mac or Linux, the cheapest way to get older versions of Internet Explorer is to run a Virtual Machine. The information and downloads for doing so are housed on a [section of the Microsoft website for developers](http://dev.modern.ie/tools/vms/). I don't work for a technology company. We have more than 10,000 employees in our organization, and only a handful of these are developer, programmers or technologists. Why should'nt this access be available on more browsers, or more types of computers?

This is not a blog post entry in some kind of Mac vs. Windows debate. And I can actually understand an enterprise portal being slow to update. Benefits and insurance enrollment is an annual process that requires some reading through the changes and logging into a system from the web, usually done on an employee's own time. For this reason I would like to see enrollment treated in a more consumer-oriented way than an enterprise-oriented way. 

The vast majority of internet users probably [do not know which web browser they use](http://www.sitepoint.com/what-is-a-web-browser/). They simply expect the app to work or the content to be there when they visit a website.

<div class="video-box">
<iframe width="100%" height="auto" src="https://www.youtube.com/embed/o4MwTvtyrUQ" frameborder="0" allowfullscreen></iframe></div>

The kind of web development I do is about information and content. I do not work on complex web applications or proprietary "portals", but I do use these things, and think a lot about the user experience, and how to make applications accessible to the widest audience possible. Every website I work on today is developed with [progressive enhancement](http://sixrevisions.com/web-development/progressive-enhancement/) in mind, so my websites work on IE 10 and 9 (and older!) but support newer versions, other browsers, and assistive technology (like screen readers) too. Last year I worked on the communications team on our workplace's employee engagement survey. One of the issues we were working on was figuring ways to get employees who might not have daily access to a PC for their job to take a paper version of the electronic survey during work hours. Filling out a workplace survey is entirely voluntary, but we wanted the highest possible response rate. <strong>Limiting access to enrollment information perpetuates an outdated view of how the web is supposed to work.</strong>

The last part of the memo I'll quote from:

> Although they are not recommended, other browsers might work. Call Center Staff will try to help you if you have other browsers. But, you may still have issues. For instance, it might take you longer to enroll than if you use Internet Explorer 9 or 10. Or you might not be able to view all your information accurately on the enrollment screens, which could mean that you don't get properly enrolled in your choices. If these issues cannot be resolved, you will need to use a recommended browser.

15-20 years ago it was very common to see statements like "This website best viewed in Netscape version x or Internet Explorer version x," or "Requires Flash player." Thankfully browsers have become more standardized and more web developers prefer standards and open platforms. Google is rightfully beginning to punish search rankings for websites that show an ad asking mobile users to install an app before displaying content. A growing area of web and mobile development is ["Offline First"](http://hood.ie/blog/say-hello-to-offline-first.html), caching assets and content, and securely saving data locally to create a web and app experience that doesn't require a permanent internet or data connection. In 2015, a memo like this should be laughable, except that with insurance and benefits, so much of someone's livelihood is at stake, its more embarassing than funny.

This memo may not affect me as much as it could other users. I think I was able to do everything OK in Firefox last year, but if that fails, I know how to run IE10 on a virtual machine and do it at work. <strong>I'll be OK.</strong> I'm more worried about others who don't know how to install a VM, or have IE 11 and have to try to revert back. Or only a cell phone at home with an EDGE connection. Or don't have access to a PC at work. Or the call center employees who get to troubleshoot all this over the phone.

In January, [IE 11 will be the minimum supported version](https://blogs.windows.com/msedgedev/2015/08/26/how-microsoft-edge-and-internet-explorer-11-on-windows-10-work-better-together-in-the-enterprise/) to receive security and technical support on Windows 7 and 8.1. When enterprise technology is pushed to upgrade their browser support to IE 11 and Edge, why not extend it to the rest of the web as well?

####Related Reading/Listening/Viewing
* Eric Meyer, ["This Web App Best Viewed by Someone Else"](https://www.youtube.com/watch?v=r38al1w-h4k) (2015 conference talk video about the inverse of this problem).
* Jen Simmons, The Web Ahead Ep. 94, ['Rethinking Microsoft's Browser with Rey Bango'](http://thewebahead.net/94) (podcast discussion about Project Spartan/Microsoft Edge and supporting legacy features for Enterprise).
* Michael Endler/<em>InformationWeek</em>, [Microsoft Dumps Support For Old IE Versions](http://www.informationweek.com/software/enterprise-applications/microsoft-dumps-support-for-old-ie-versions/d/d-id/1297896), published August 2014.
* Kurt Mackie/Redmond Magazine, [Microsoft's IE 11 'Enterprise Mode' Aims To Break Old Habits](https://redmondmag.com/articles/2014/04/10/ie-11-enterprise-mode.aspx), published April 2014.
* Itzek Spitzen, ['HTML5 for Rich Web Enterprise Applications'](http://www.methodsandtools.com/archive/archive.php?id=125), published in the Fall 2011 issue of Methods and Tools.
* Aaron Gustafson, ['Our Work Here is Done'](http://www.webstandards.org/2013/03/01/our-work-here-is-done/), published March 2013 (A little background information on the "browser wars" and the Web Standards Project).