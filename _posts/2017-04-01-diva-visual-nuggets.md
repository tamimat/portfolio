---
author:
 name: Interaction Design
title: Bit by bit
summary: Teaching the user different voice interaction commands with little non-interrupting visual-nuggets.
---

```
Challenge:
Users don't know which kind of voice commands they can use.

Approach:
Design Workshop with the engineer and implementation.

Contribution:
Researcher, Workshop Organizer, Product Designer
```

## The problem
When we showed DIVA to others, we always needed to show the features that DIVA was capable of doing, such as "Search for price range” or ”Search for attributes". The users said, "Ah, you can do that". 
In visual interfaces, features that are important can be consistently shown. The user sees the feature. There is an external signal that reminds him of it. For example, if you search in a commerce website, you can see the filters, or when you type the keywords, suggestions will be shown, with autocomplete for each new letter that you type. Features of voice interfaces lack that ability. The question is how can the user be shown what capabilities the NLU has without making tours that everybody dismisses and nobody watches.

## Approach
DIVA has a display and is not a voice-only interface. There are quite a few similar voice assistants out there. All of them have the same problem and take slightly different approaches to solving it. Since this was a good problem that can be discussed in a workshop, the iOS engineer and I teamed up together.

## Workshop
First, I collected screenshots from all the other assistants and printed them out:

{Images from various voice assistants}
Cortana, Hound, Siri, Google, Ozlo, Bing, Alexa

We went through all the different solutions and discussed the pros and cons of each. We figured out the interaction patterns that were used in all solutions and decided together what could work for our case, or if we could come up with a better approach. We preferred when the information was little and not in list form. Another thing we liked was when a skill was visualized as an icon. We felt that giving the user the information in small chunks of teaching would be the best approach. We had two opportunities to do that, the start screen and the product list view screen. We sketched on the printed-out screens how and where the visual-nuggets could be placed and what we would want to teach the user.


## Design & Prototype
I went straight to Sketch with the ideas and came up with different solutions. There was a back and forth between me and the engineer in Slack. The start screen looked like this:

(Start Screen 1)

The start screen with the high-res images was too distracting. It felt like advertising. So, I changed those to very simple icons that I found on thenounproject.com. That way they looked more like examples of searches. To show the variety we used different examples with different text attributes, searching for color or price that changed randomly.


(Start Screen 2)

The other opportunity to teach the user was the product list screen. The first approach looked like this:

(Product list Screen)

To give the text nuggets more space, I placed the microphone button on the right side. But looking at it, that didn't feel right. So, we worked on making the text shorter and placing the microphone button in the middle.

(Product list Screen)

This felt like the better approach. We also had ideas to make the suggestions relevant to the first question. Implementing this "intelligence" would be possible, but would cost us more time and resources from other engineers. Therefore, we decided to push that update through and implement the intelligent part later.
