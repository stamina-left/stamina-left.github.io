---
layout: page
title: Readdy - Reading Assistant
description: An app that helps dyslexic reads documents or books very well.
img: /assets/img/readdy-v1-screenshots/project_thumbnail.jpg
importance: 1

---

## How did it all start?

It began when one of my friends having an urge to provides access to people with dyslexia. He explained how dyslexic struggles with slow reading, labored writing and delayed speaking because of what did they see when they read. To reduce the incidence of future problems in their learning, behavior, and health, they need an early childhood intervention. 

But then we had some big questions, what about the dyslexic person who never had an early childhood intervention? How can they handle it from primary school until right now? Can they catch up just like an ordinary person? We want to find out how did they manage themselves without early intervention.

---

#### My Role

I did some research about dyslexia to empower our solution to make the most impactful solution for an adult dyslexic. As a programmer, I ensure the interfaces look the same as the prototypes to make the users feel satisfied with how accessible the information is through our app.

#### The Challenge

Give the most impactful solution for adult dyslexics to read.

#### The Outcome

A native iOS app that helps adult dyslexics to read with ease and have a better reading experience.

---

## The discovery

In general, dyslexia without early intervention will have long-term educational, social, and economic consequences when it comes to being adults. Doing a late intervention will be trouble at recognizing comorbidities such as anxiety, depression, and low self-esteem.

Untreated dyslexia will increase the risk of becoming a criminal. Additionally, adults with learning disabilities most likely unemployed, and their annual incomes are below national averages.

---

## The proposed solution

To improve their ability to process information, they need a multisensory approach, such as involving both visions and hearing when reading. This approach will enhance their memory and learning of written language simultaneously.

Using sans serif fonts, such as San Francisco and Gill Sans, is the best choice because the letters appear to be less crowded. Adjustable font size, character spacing, line spacing, and the background color is a must because some dyslexic people will have their preference.

This solution will help them have the advantage of making all written communication easier on their eye for everyone.

---

## Validation

We've interviewed five adults with dyslexia to ask about their dyslexic's experience and test our proposed solution. Builds upon our test, they love the reading adjustments feature.

Two adults had thought that the multisensory approach is outstanding because it will help them when they had reading fatigue. From here, we quickly create our minimum viable product.

---

## Rollout and reflection

We showed our app to one adult with dyslexia that we met before and experts in UI/UX design, and the result is far from satisfactory. Most of our interface isn't very intuitive, it can't stop or change the speed of text-to-speech, and there is something that needs improvement in our copywriting.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/readdy-v1-screenshots/Not Intuitive Design 1.jpeg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/readdy-v1-screenshots/Not Intuitive Design 2.gif' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Users accidentally go to the home screen when they're about to swipe up the drawer. It's a bad UX if we see someone struggles to use our app.
</div>

They end up criticize our not intuitive design and our copywriting rather than telling how it will be impactful for themselves. Before we validate our prototype to someone else, I think we need to reassure our pattern, does it looks familiar with the native interface design or not.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/readdy-v1-screenshots/Safari Reader Mode.gif' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/readdy-v1-screenshots/Books Type Setting.gif' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Here are examples of intuitive design for reading adjustment from Safari's reader mode and Books.
</div>

Using a familiar design pattern will make the users know what to do. Rather than placing the type settings in the drawer, replace it with the popover from the navigation controller.

The key is to pick the best design pattern for our apps. Does the drawer fit on the reading screen? It may be fit, but does it intuitive? Why do you pick the drawer than the popover? These questions should we ask ourselves when we choose an unusual pattern for our design.

Our improvement isn't only in terms of design, but also in terms of implementation. Some of our code isn't readable because it doesn't have a proper format in naming convention, writing order, and forgot to add a markup, so it's harder to understand.

This unreadable code exists because when we learn how to create these features superficially. We only think of does it works or not, without thinking much about future changes and ignoring the possibility of other programmers touching our code.

To maintain our code, we decided to use a clean architecture pattern so that it's easy to understand and easy to change as the project grows. One of our team suggested learning the iOS architecture pattern by Oleh Kudinov. For more Oleh Kudinov's iOS architecture pattern details, you can <a href="https://tech.olx.com/clean-architecture-and-mvvm-on-ios-c9d167d9f5b3" target="blank">visit this article at Medium</a>.

---

## Coming soon

In the next session, I will tell you how we redesign and refactor our app based on the feedback and our reflection. Stay tuned!
