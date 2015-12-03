# FieldQuestioner

This is a test for an Android app. I know next to nothing about Java programming, but in my new work I will need to get into it relatively fast. So I started to work with some of my ideas where Java could be quite crucial.

It happens extremely often that we are working with someone on the field, and suddenly, though just moments ago you had a wonderful set of questions in your head, now your mind hits empty. If you've been working with some topic for longer time, let's say weeks, interviewing people daily, bringing specific topics into your regular conversations, naturally this problem does not tend to occur. But especially when you just get to the field after a break it may take some time to get into the mood.

I was thinking it could be really nice to have an app in your watch, (I don't have an Android watch, but maybe in a few years everyone has), which would give you a new fresh question, as an example, when you shake your wrist or something. This is of course bit more complicated than this, but in principle the model is very simple.

- Set of questions
- Reaction to something (a button, a shake, a specific length of silence with umms and mhms?)

And that is it! Naturally one can then make it as difficult as one wants:

- The questions should vary depending from the timing within the recording session (there are questions you've likely covered in the beginning, in the end there could be more obscure stuff)
- The questions are not random, but actually follow specific "patterns" or "paths", i.e. some questions are ok only when some related questions have been asked in order to create the right context, also one may not want to have too abrupt changes in topic
- It is assumed that a recorder is running the same time with the app. How do these two communicate? The app can of course store a timestamp for everything it does or when something is changed, which allows synchronizing this with the audio track with no problems. Well, one problem remains, mainly that there is no way to set a smartphone and recorder into same time with millisecond level of exactness. In principle the smartphone could make a soundsignal when it starts, as an example, on some higher frequencies which do not bother the recording too much...

As I don't have an Android watch, I've started to set this up for my smartphone (Samsung Galaxy III).

## What does this mean?

Using and designing smartphone/tablet/smartwatch applications is directly related to adapting digital workflows into our fieldwork practices. This is in its infancy, but there certainly is need to automatize i.e. the way how some questionnaire based data elicitation could be turned instantly into a digital format.

I strongly believe that it is possible to design useful software in a rather minimalistic framework which can easily be adapted into other uses. Instead of having lots of features in one app, it could be more useful to do something simple very well in a thoroughly documented manner, as then also interested individuals who are not so much into programming could probably customize it to their needs.
