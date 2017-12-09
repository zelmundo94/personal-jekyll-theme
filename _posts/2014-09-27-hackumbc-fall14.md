---
layout: post
section-type: post
title: HackUMBC Fall '14
category: tech
tags: [ 'tech', 'hackumbc', 'Denzel' ]
---

This past weekend, I participated in the 2nd annual UMBC Hackathon, needless to say, it was awesome! I formed a team last minute and we were able to create a hack that I believe could shed light on computer users that do not receive enough attention. The users I am referring to are disabled individuals. We knew we wanted our end goal to revolve around helping others with disabilities. Our hack was ultimately intended for the use of disabled individuals who may suffer from muscle deficiency or even older individuals who may have trouble with interacting with the computer keyboard. Initially, we thought it would be great to create a hack that could increase productivity for people, college students in particular. However, this idea seemed vague, causing us to pivot on to something more specific. This led to us hacking a gestural device known as the <i>Myo Band</i>. The Myo Band is equipped with 7 hand gestures, rotation data, and acceleration. One of my teammates were sparked by the idea of using a password manager named KeePass to manipulate entry fields hands-free. Basically, our mission was to hack the gestures that were equipped with the Myo Band. Sounds pretty simple, right? It actually was not. First, we had to compile a plugin in Visual Studio, using a build system named CMake and a plugin framework known as <b>Firebreath</b>.  Despite running into problems with latency, we were able to deploy the plugin in a timely fashion and integrate it with KeePass login and sync data. We then edited the script manager for Myo Band, which was written in Lua. This was done by seeking out the parameters that needed to be customized with special commands within the plugin we deployed that would enter information into the entry fields. The end result is in the video below! (Side note: Don't mind the narrator of the video, he was sleepy... wink wink)

<iframe width="870" height="612" src="https://www.youtube.com/embed/RkxJgzjHTBo" frameborder="0" allowfullscreen></iframe>
