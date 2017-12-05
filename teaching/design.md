---
layout: teaching
permalink: /teaching/design.html
title: "How to Teach Programming (and Other Things): Lesson Design Template"
---

# Lesson Design Template
<!--: \label{design} :-->

Designing a good course is as hard as designing good software.  To
help you, this appendix summarizes a process based on evidence-based
teaching practices:

- It lays out a step-by-step progression to help you figure out what
  to think about in what order.
- It provides spaced check-in points so you can re-scope or redirect
  effort.
- The end product specifies deliverables clearly so you can finish
  development without major surprises.
- Everything from Step 2 onward goes into your final course, so there
  is no wasted effort.
- Writing sample exercises early lets you check that everything you
  want your students to do actually works.

This backward design process was developed independently by
[[Wiggins2005](biblio.html#wiggins-mctighe)],
[[Biggs2011](biblio.html#biggs-tang-quality)], and
[[Fink2013](biblio.html#fink-significant)].  We have slimmed it down
by removing steps related to meeting curriculum guidelines and other
institutional requirements.

> Note: the steps are described in order of increasing detail, but the
> process itself is always iterative.  You will frequently go back to
> revise earlier work as you learn something from your answer to a
> later question or realize that your initial plan isn't going to play
> out the way you first thought.

## Step 1: Brainstorming

The first step is to throw together some rough ideas so that you and
your colleagues can make sure your thoughts about the course are
aligned.  To do this, write some point-form answers to three or four
of the questions listed below.  You aren't expected to answer all of
them, and you may pose and answer others if you think it's helpful,
but you should always include a couple of answers to the first.

1. What problem(s) will student learn how to solve?
2. What concepts and techniques will students learn?
3. What technologies, packages, or functions will students use?
4. What terms or jargon will you define?
5. What analogies will you use to explain concepts?
6. What heuristics will help students understand things?
7. What mistakes or misconceptions do you expect?
8. What datasets will you use?

You may not need to answer every question for every course, and you
will often have questions or issues we haven't suggested, but couple
of hours of thinking at this stage can save days of rework later on.

Checkin: a rough scope for the course that you have agreed with your colleagues.

## Step 2: Who Is This Course For?

"Beginner" and "expert" mean different things to different people, and
many factors besides pre-existing knowledge influence who a course is
suitable for.  The second step in designing a course is therefore to
figure out who your audience is.  To do this, you should either create
some [learner personas](lessons.md), or (preferably) reference ones that
you and your colleagues have drawn up together.

After you are done brainstorming, you should go through these personas
and decide which of them your course is intended for, and how it will
help them.  While doing this, you should make some notes about what
specific prerequisite skills or knowledge you expect students to have
above and beyond what's in the persona.

Checkin: brief summaries of who your course will help and how.

## Step 3: What Will Learners Do Along the Way?

The best way to make the goals in Step 1 firmer is to write full
descriptions of a couple of exercises that students will be able to do
toward the end of the course.  Writing exercises early is directly
analogous to [test-driven development][tdd]: rather than working
forward from a (probably ambiguous) set of learning objectives,
designers work backward from concrete examples of where their students
are going.  Doing this also helps uncover technical requirements that
might otherwise not be found until uncomfortably late in the lesson
development process.

To complement the full exercise descriptions, you should also write
brief point-form descriptions of one or two exercises per lecture hour
to show how quickly you expect learners to progress.  (Again, these
serve as a good reality check on how much you're assuming, and help
uncover technical requirements.)  One way to create these "extra"
exercises is to make a point-form list of the skills needed to solve
the major exercises and create an exercise that targets each.

Checkin: 1-2 fully explained exercises that use the skills the student
is to learn, plus half a dozen point-form exercise outlines.

Note: be sure to include solutions with example code so that you can
check that your software can do everything you need.

## Step 4: How Are Concepts Connected?

In this stage, you put the exercises in a logical order then derive a
point-form course outline for the entire course from them.  This is
also when you will consolidate the datasets your formative assessments
have used.

Checkin: a course outline.

Note:

-   The final outline should be at the lecture and formative assessment
    level, e.g., one major bullet point for each hour of work with 3-4
    minor bullet points for the episodes in that hour.

-   It's common to change assessments in this stage so that they can
    build on each other.

-   You are likely to discover things you forgot to list earlier during
    this stage, so don't be surprised if you have to double back a few
    times.

## Step 5: Course Overview

You can now write a course overview consisting of:

- a one-paragraph description (i.e., a sales pitch to students)
- half a dozen learning objectives
- a summary of prerequisites

Doing this earlier often wastes effort, since material is usually
added, cut, or moved around in earlier steps.

Checkin: course description, learning objectives, and prerequisites.

Note: see the appendix for a discussion of how to write good learning
objectives.

## Reminder

As noted at the start, this process is described as a sequence, but in
practice you will loop back repeatedly as each stage informs you of
something you overlooked.

[tdd]: https://en.wikipedia.org/wiki/Test-driven_development
