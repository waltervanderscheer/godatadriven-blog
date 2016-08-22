Title: Sharing Data Science Insights
Date: 2016-08-22 23:00
Slug: sharing-data-science-insights
Author: Giovanni Lanzani
Excerpt:
Status: draft
Template: article
Latex:

The real world (and real data) are much messier than we are thought during our education.
Things are much fuzzier, people and processes are involved. We get more experienced with time, but
in a consultancy company very often you work in projects either alone or in small teams. Chatting
with your colleagues help, but how can you ensure that you're actually passing that useful
knowledge along?

These questions have bugged me since I've stepped in as Chief Science Officer at GoDataDriven. We
already had a mechanism in place, the Tour de Table, but not without shortcomings.

The Tour de Table is pretty simple: every four weeks, we gather together at the end of the
afternoon, and, in approximately 3 minutes per person, we share what we are working on. Since we're
mostly twenty at each gathering, this takes an hour.

While it serves well as an overview, you don't get much insights into the learnings and challenges
we face. That is why, in addition to the Tour de Table, I've introduced two new concepts

- a deep(er) dive session every two weeks;
- Basecamp automatic check-ins.

The deep dive session is pretty simple: you prepare some slides about the work you are doing: the
business question, the data, and the algorithms you use to solve the question. Usually we present
work in progress, so that the audience suggests possible alternatives and improvements. Everybody
that attends has something new to learn usually, be it experienced data scientists, our
[managing director](https://www.godatadriven.com/players/rob-dielemans),
or our [chief marketing](https://www.godatadriven.com/players/walter-vanderscheer). These
presentations have the side-effect that the presenter gets better at exposing and defending idea's,
but also better at implementing external feedback.

The Basecamp automatic check-ins is an idea I ~~stole~~ got inspired from this
[Jason Fried article](https://m.signalvnoise.com/the-tool-we-built-to-keep-everyone-in-the-loop-at-basecamp-69bc58312014#.lym9yynbl).

There Jason presents how 37signals keeps people across the company in the loop about what’s going
on in the company. The idea is very simple: every Monday at 9AM, Basecamp sends a notification to
everybody asking **What are you working on?**. There we write the things that will keep up busy the
week. This is a general question and not very fine grained, so that's why we have a second question
(this one gets asked every day at 5PM) saying **What did you work on today?**. This is more
specific and allows us to go deeper our the daily work. It's also the place where I learned, for
example, that [Vincent](https://www.godatadriven.com/players/vincent-warmerdam) was having an issue
with Spark executor dying and that I help in solve within minutes of him posting it.

Daily updates like this can be overwhelming, that's why we're still experimenting with the
frequency of the more fine grained updates.