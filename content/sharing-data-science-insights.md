Title: Sharing Data Science Insights
Date: 2016-08-22 23:00
Slug: sharing-data-science-insights
Author: Giovanni Lanzani
Excerpt: The real world (and real data) is much messier than we thought during our education.  Things are much fuzzier as people and imperfect processes are involved. We get more experienced with time.  However, in a consultancy company, you seldomly work with your whole team. Chatting with your colleagues help, but how can you ensure that you're actually passing that useful knowledge and insights along?
Template: article
Latex:

The real world (and real data) is much messier than we thought during our education.  Things are
much fuzzier as people and imperfect processes are involved. We get more experienced with time.
However, in a consultancy company, you seldomly work with your whole team. Chatting with your
colleagues help, but how can you ensure that you're actually passing that useful knowledge and
insights along?

These question have bugged me since I've stepped in as Chief Science Officer at GoDataDriven. We
already had a mechanism in place, the Tour de Table, but it has its shortcomings.

The Tour de Table is pretty simple: every four weeks, we gather together at the end of the
afternoon, and each of us, in approximately 3 minutes, share what she is working on. Since we're
mostly twenty at each gathering, this takes an hour.

While it serves well as an overview, you don't get much insights into the learnings and challenges
we face. That is why, in addition to the Tour de Table, I've introduced two new concepts:

- A deep(er) dive session every two weeks;
- Basecamp automatic check-ins.

The deep dive session is pretty simple: you prepare some slides about the work you are doing: the
business question, the data, and the algorithms you plan to use or have used to solve the question.
Usually we present work in progress, so that the audience suggests possible alternatives and
improvements. Everybody that attends has something new to learn, be it experienced data
scientists, our [managing director](https://www.godatadriven.com/players/rob-dielemans), or our
[chief marketing](https://www.godatadriven.com/players/walter-vanderscheer).

The data scientists learn how to tackle a particular problem, but also what are the issues when
going down a particular road. Sales and marketing get a much better idea of what we're (not)
capable of, so that it helps give an accurate description of our expertise[^1].

On top of that, these presentations have the side-effect that the presenter gets better at exposing
and defending idea's, but also better at implementing external feedback. Especially for the less
experienced members, this is incredibly valuable.

On the other hand, the Basecamp automatic check-ins is an idea I ~~stole~~ got inspired from this
[Jason Fried article](https://m.signalvnoise.com/the-tool-we-built-to-keep-everyone-in-the-loop-at-basecamp-69bc58312014#.lym9yynbl).

In the article Jason presents how 37signals keeps people across the company in the loop about
what's going on in the company. The idea is very simple: every Monday at 9AM, Basecamp sends a
notification to asking **What are you working on this week?**. Then, every day at 5PM, Basecamp
asks **What did you work on today?**. This is more specific and allows us to go deeper into our the
daily work. It's also the place where I learned, for example, that
[Vincent](https://www.godatadriven.com/players/vincent-warmerdam) was having an issue with Spark
executors dying. As I was having the same struggle weeks before, I could quickly help him solve the
issue.

Daily updates like this can be overwhelming and we're still experimenting with the
frequency of the more fine grained updates. But overall these two new concepts are turning out to
be a terrific way to share knowledge and keep everybody in the loop.

[^1]: We cannot stand over-promising and under-delivering. If there is one thing we stand for, it
  is focus on what we can do best instead of delivering mediocre results.
