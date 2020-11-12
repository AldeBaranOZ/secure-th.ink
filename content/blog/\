+++
title = "Introduction to Security Thoughts"
author = "Allen Baranov"
date = "2020-11-12"
tags = ["meta", "blog", "bizsec", "future"]
[[images]]
 src = "img/2019/03/pic03.jpg"
 alt = "Valley"
 stretch = "horizontal"
+++

### Hello World!

(Again)

I was reading someone's blog yesterday and thinking just how lucky they were to have a working blog and then I reminded myself that I also have a blog - it is just not working. So I configured it and I now have the ability to blog once more. 

My first blog was created way back in the Golden Age of blogging and I actually like some of the content on it. I still believe that Information Security has not caught up with the ideas that I had even then and a lot of what we take for granted now was cutting edge then. 

But that was then and this is now and this blog represents a lot of the new for me. It is hosted elsewhere but it is written on my own server. The changes are all logged by git so I can keep track of what has changed and why. 

It is also a lot lighter than my old blog and it is static so, if I do host it, then I will be able to do so more securely and on hardware that does not have to worry about querying a database for some of the mostly static content. 

There are many new static blogging platforms out there that can deliver most of what you need form wordpress. I know because I have tried them all. Most of the time it has taken to get this blog up is my fiddling around looking for the perfect solution. I don't think I have found it but it has been an interesting journey. And... at least I finally have something to show for it.

### So, why the urgency?

Well... my brain is getting fill and I need somewhere to dump my knowledge and so this is it. I get bored very quickly so I always like to be on the cutting edge of my industry. 

### Ok, but Allen, you are in GRC. 

And so GRC can't be cutting edge? 

Fair enough. But GRC sits on the border between "the business" and "IT" and "Infosec" and all three of those are rapidly changing and sometimes in totally different directions. 

> “The future is already here – it's just not evenly distributed.
> - William Gibson

I have been privileged to work with many different companies and teams and people over the past few years. Some have been stuck in the early 2000s with 6 month development cycles, uneven patching and dated compliance processes, some have been on the bleeding edge of innovation using docker, kubenetes, CI/CD etc backed up with Agile processes and DevOps philosophies. 

The strange thing is that both of those scenarios can exist in the very same organisation. 

### Yeah but... buzzword bingo

Yep, Agile, CI/CD, Lean, DevOps, Customer-centric, etc

They are all buzzwords and a lot of organisations manage to implement them without understanding them and then tick the "we are cool" box but don't actually derive benefit.

The interesting thing about these "buzzwords" as opposed to the others like "AI/ML" and "Cloud" and "Zero Trust" is that they are actually non-technical. 

At least - they are supposed to be non-technical. Sure you can implement a waterfall development cycle and do it using a CI/CD pipeline and you can take your legacy servers and host them on EC2 virtual machines and you can have "scrums" and "daily stand-ups" and "kanbans" without changing your work processes but... you won't really derive the benefits. The business benefits. 

### So, where to from here?

You will notice that one word I have not used is "devsecops" - I don't like it and refuse to use it. For two reasons:

1. It is very restrictive
2. It is just plain wrong

So...what do I mean?

DevOps is not the "coming together of the dev and ops" or a technology solution or whatever (all things I have come across). At a technical level it is assigning the duties of what was traditionally performed by the operations team to the developers. I won't get into the details but this is something that can be done these days because a lot of the menial operational tasks that were required a few years ago can now be automated. 

But DevOps is even more than just that - it is also a new way of doing everything in IT. Everything. 
> "More is more than more. It is different."
> - Kevin Kelly

If you change from a 6 monthly deployment cycle to a 3 monthly cycle then not much has changed really. What if you work out how to deploy more quickly? Maybe monthly? Not a whole lot there either. What about a few deploments every day? Yes. Now you are talking about something totally different. You can not afford to have a CAB meeting each time you want to deploy if you do it hourly. You can't afford to have firewall rule reviews. You can't afford to have a process where you add users to the server and have their access authorised by two people. You are in something different now. This is DevOps. 

Does security deserve to be slotted into DevOps to make DevSecOps? What about tesing? What about business decisions? DevSecBusQAOps? Fine but you are missing the whole point. The point is this: the person performing the change on the systems is accountable for EVERYTHING. Because that is the ONLY way this works. Everyone else is there to support them. Which feels weird for Security but it is where we are. 

(I seem to have taken a bit of a deep dive into "devsecops" which was really not my intention - I may take this out and move it into an article of its own)

Most people I have come across who talk about DevSecOps mean it to be code assessment - either dynamic or static and usually automated either in the IDE or in the pipeline. Which is fine but it missed out on the "ops" bit - how do you use this method of rapid deployment to also make sure that patches are current, that libraries are current, that code is maintained. That code is clear and concice. That servers are deployed with minimum access and minimum services runnings. That incidents can be quickly attended to and logs are meaningful. That complexity is removed. All of these things can be benefits of DevOps but not if you only concentrate on code analysis. 

But I don't like the term "DevSecOps" anyway so the "devsecops = code analysis" people can have it. 

### And so....?

Well... there needs to be a better terminology in place for the benefits derived from applying a security thinking mindset to devops (and agile, lean, etc) and there isn't one. 

### Resiliency

What about resiliency? I have heard that term thrown around and usually by people I really respect but it doesn't quite work for me. It feels like it is only really looking at the availability of a system and not the intgrity and confidentiality. It also sounds very negative. 

### What do you suggest Mr Smart Guy?

The term that I have come up with is (for better or worse) **BizSec**. 
