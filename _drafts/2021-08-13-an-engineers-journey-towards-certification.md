---
title:  "An engineer's journey towards professional certification"
date:   2021-08-13
---

After a few years working on Google Cloud Platform, I figured out I was painfully lacking a global and professional view 
of how machine learning and data science are carried out on the cloud.

## Approaching the problem

First thing to do was to understand on which topics I needed to ramp up. With a data scientist background, I saw the 
current development of more production-oriented jobs as an opportunity to try to bridge the gap between a more theoretical, 
model-centered role and a more software-engineering-like role.\
Put simply, I used to rely on computer science as a tool for solving problems using a mathematical, statistical and probabilistic mindset, rather than trying to think like a 
software engineer from the beginning of the development of a project, be it dedicated to solving a problem using machine
learning.

## Defining the goal

My goal was not to become a software engineer, neither a data engineer. There are tons of brilliant software engineers
out there, working in top tech companies or in smaller organisations. There are tons of brilliant data engineers as well, 
working in the same top tech companies or in the same smaller organisations.\
I love data science, and even if there also are tons of brilliant data scientists and machine learning engineers out there, solving problems using models based on reliable 
and properly gathered data was what I had been doing for the previous 5 years, and I still didn't want to leave it. 
Instead, I aimed at getting a little further and widening my scope by adding software engineering and data engineering 
best practices and principles to my toolbox for becoming a better machine learning engineer.\
After having looked at the online resources for improving data science skills, found loads of books on how to become a 
machine learning engineer, I figured out I wanted to follow a more classical path and do what I had always done so well 
since I was in high scool: learning. A professional certification was the best option, and since I had been working on GCP 
for almost 4 years, I decided to go for the recently created Google Cloud Professional Machine Learning Engineer certification.

## Understanding what a certification is about

In France, you're under constant evaluation from primary school until when you land your first job. That means a student 
pursuing a Masters will spend around twenty years preparing exams and receiving grades for the work he's done. 
That's what I did, and when I decided to get into the certification learning track I believed getting back at it after 
almost five years of work would be a piece of cake. Well, things were not that easy.\
The first thing to grasp when dealing with such certifications is about how what you learn will be assessed at the exam. 
In other words, you can be a data engineer with 10 years of hands-on experience, a machine learning PhD holder with a 
highly solid theoretical education, or a simple data scientist as I was, the chances are that you will get a fail if you 
don't understand what the exam is asking for. Put simple: know how to learn as Google wants you to learn.\
The second point, and maybe the most critical concerning this certification and more generally speaking any school-like
learning you will carry out during your career, is to understand how best you can get experience from preparing and taking
the exam. In other words, don't just learn for the exam, learn for your own career.

## A complete learning path

For what concerns my own experience, I decided to take the Google Cloud Professional Machine Learning Engineer certification
exam. [Google's exam guide](https://cloud.google.com/certification/guides/machine-learning-engineer) is divided in various chapters, covering a wide range of topics
* Framing ML problems. This first part is a broad overview on how to think like a problem solver using machine learning,
where the most important is not to use ML wherever you can, but wherever you should, with the highest possible success rate,
and at minimal risk.
* Architecting ML solutions. This part is mainly about designing ML solutions, where you learn how to think about which tool
to use for which use case, be it a piece of software (e.g., Cloud Dataflow, BigQuery) or hardware (e.g., CPU, GPU, TPU,
edge devices), and how to build secure and ready-to-deploy architectures.
* Designing data preparation and processing systems. This part gets deeper into concrete data manipulation, from exploration
to validation and feature engineering.
* Developing ML models. This can be thought about as the heart of any data science / ML engineering job, as it encompasses
stages like coding, training, testing and serving models. But you will learn that it's actually only a tiny fraction of 
the whole job of an ML engineer.
* Automating and orchestrating ML pipelines. Here comes the part where the difference between pure data science and ML 
engineering is made. You will go further than just coding, training, and testing models, by incorporating a little 
software engineering way of thinking and learn about continuous integration / continuous delivery / continuous training,
and more generally about packaging what you've learned so far into actual pipelines.
* Monitoring, optimising, and maintaining ML solutions. Last but not least, when a training and serving pipeline is up and
running, it is of critical importance to be able to monitor its performance and be ready to troubleshoot it when required.

## Stepping back

When I first had a read at the Google's learning guide, I was impressed by the amount of work that is carried out by ML
engineers before and after just coding and training models. It was the first time I had a idea of how things can be done
when not just carried out locally on a single laptop.\
With this new view in mind, I realised passing the final exam would require a little more than just motivation. First, I
needed to master the whole data engineering part, before trying my best to use what working as a data scientist had taught 
me about the ML part. At this time, there was no better option than getting through another Google learning track, namely the [Professional Data 
Engineer](https://cloud.google.com/certification/data-engineer). \
Fortunately, Google is regularly offering discounts on learning paths and even exam sessions. I decided to give it a try,
and began their learning track on Qwiklabs late December. 

Needless to say that going through all the pure data engineering stuff on GCP was not an easy task. Concepts like different 
kinds of storage, OLAP vs. OLTP processing systems, streaming vs. batch ingestion, were completely new. I found a bunch of 
practice exams, the most useful ones were held on Linux Academy (now A Cloud Guru), and helped encompass what I already
talked about at the beginning of this article: it's not only about what you know about GCP, it's about how you can render
it when asked at the exam. One month after having subscribed for the learning track, I was certified as a Google Cloud 
Professional Data Engineer.

## From Professional Data Engineer to Professional ML Engineer

After the Professional Data Engineer certification, time was to take the Professional ML Engineer certification. Again,
things were not so easy. I still needed to digest all the actual continuous training/serving/monitoring part, and be able
to think about how to put things in production, not only about building shiny models. 

Here is where I found the Professional Data Engineer certification and the Professional ML Engineer certification were
pretty different. When thinking about the Professional Data Engineer certification preparation, you have to be prepared 
to face actual technical challenges, for example "Which command would you use for querying a BigQuery table in that way?", 
or "At what level can you control Pub/Sub IAM permissions ?". Pretty concrete indeed. For what concerns the Professional 
ML Engineer certification, it is much more about _concepts_, instead of concrete situations. Obviously you can be asked 
about how to set up an architecture for training and serving TensorFlow model, but always bear in mind that you are a 
machine learning engineer, and you work for putting systems in production.

After a couple of months (the learning track is much longer for the Professional ML Engineer certification than for the 
Professional Data Engineer one), I was certified as a Google Cloud Professional Machine Learning Engineer.

## Conclusion

Again this article is not a must-follow to get certified. I would not even say certifications are a must have. In fact, 
it is still too early for me to have an actual view of what these two certifications will offer in terms of professional
development.\
If instead you are searching for a pure technical challenge, then I would strongly encourage you to go give it a try. At
least the learning track will give you enough learning experience for projects you could have to work on later. 

## Useful links

During my preparation, on top of the Google's guides, I used resources from several blogs and learning platforms. Most 
of them are free to read, some are constrained to subscription. I build my own learning track strongly inspired by the 
Google's guidelines, you can find it [here on Pluralsight](https://app.pluralsight.com/channels/details/579d2562-ed2f-460c-8efb-a646a6e25ced?s=1). 
This article has not been sponsored by any author or company.