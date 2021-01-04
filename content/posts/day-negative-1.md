---
title: "#66 Days of Data - Day -1"
date: 2021-01-02T22:26:38-08:00
tags: [66DaysOfData]
---

*Yes, that's intentially a -1*.

I've been on a journey of #66DaysOfData for the past 20 or so days. The original concept of this is to dedicate at least 5 minutes a day learning or working towards something data science-related.

Some people would think I had misread it because I've been pouring in close to 5 hours a day on this for the past few weeks.

This is my chronicle of things I've done to work towards becoming a data scientist. And once I do land a job as a data scientist, I will continue because I will always want to become a *better* one.

So, to kick things off, here is what I learned today.

## SQL
I went through 4 chapters of [Practical SQL](https://nostarch.com/practicalSQL). A general gist of what I learned was:
* There's a `percentile` operator in SQL
    * There's also the `percentile_cont` method that takes in an array and requires unnesting if you want multiple rows of values
* Joins don't just accept equality operators, you can also join on any type of expression
* Cross joins exists and are typically used to make combinations
* There's a `CHECK` constraint that accepts an expression
* The difference between natural and surrogate keys
* Composite keys
* Foreign keys have to reference a column in another table
    * are super powerful because they have constraints to check if the value is in the other table's primary key column
* You can set `DELETE CASCADE` onto a foreign key to delete both a foreign key record and the primary key record it references
* You can add constraints ex post facto by using `ADD CONSTRAINT`
* When to add indexes
    * If the column is often joined on
    * If the column is often used in `WHERE`s
    * a foreign key is low-hanging fruit to consider indexing
* Primary keys are automatically indexes, but *not foreign keys*
* `COUNT(DISTINCT variable)`
* To calculate percent change easily: `value2 - value1 / value1 * 100`
* `HAVING` works on post-aggregated data, `WHERE` works on pre-aggregated data

## Projects
I finished up an [exploratory data analysis](https://www.kaggle.com/tacastillo/cms-medicare-outpatient-charges-eda) on CMS outpatient charges data.

## Other
I set up this blog! That's a pretty big deal for me.

I also made a roadmap in [Notion](https://www.notion.so) of what I plan on doing for the next ~66 days or so. It's a little flimsy because it depends on when/if I land a job within the next 66 days. The general gist of it though is, that, for every day:
* Post on LinkedIn every day (500 characters)
* Post on Discord every day
* Track what you learned via this blog
* 1 Leetcode/Hackerrank SQL questions a day
    * Give it 30 minutes, look at the answer, digest the answer, try again
* 1 Leetcode/Hackerrank Python question a day
* 1 [Pramp](https://www.pramp.com) interview every other day
* Apply to every relevant job daily
* Cold email 10 people from companies you're applying to daily
* 1 statistics concept a day
I also plan on drilling down on a larger concept (such as statistics, SQL, or advanced Python) for two weeks every two weeks. For the first two week sprint, I am focusing on SQL.