---
author:
 name: Design & Management
title: “Team, we're faster than Siri!”
summary: Speed is crucial for voice interfaces. This is how we improved our speed by 350%.
---

```
Challenge:
Our speech recognition takes up to 3 seconds or more until a word appears on the screen.

Approach:
Impress upon engineers how slow that is and why increasing that speed is important.

Contribution:
Product Designer and Product Manager
```

## Situation
When AppTek speech recognition technology debuted, it recorded the audio data, sent it to the servers, and then sent it back to the device as text. The ability to send text back while still recording / speaking was one of relatively new features that made a voice assistant possible in the first place. The crux was that it took 2.7 seconds or more until the uttered word was displayed on the device, which made the interface feel sluggish. Especially when it was compared to other voice recognition systems. Back then the team was not aware that this was too slow for the user. It "worked" and there were other problems the team needed to solve.

## Approach
First, we had to understand as a team that this was a real issue. In human-computer interaction, three time limits (LINK) are crucial, and every interaction designer should know them: 0.1 second, 1.0 second and 10 seconds. In our case, only the first two were relevant:

- 0.1 second is about the limit for having the user feel that the system is reacting instantaneously.

- 1.0 second is about the limit for the user's flow of thought to stay uninterrupted, even though the user will notice the delay."

The closer a response is to the 0.1 barrier, the more instantaneous it feels. The further away a response is from the 1.0 barrier, the more sluggish it will feel.

After sharing this fact, I needed data points to show how slow the recognition was. I needed to come up with a simple and pragmatic way to do that without stressing out developers and binding their resources. So, I recorded the speech recognition with screen recording software, or I just took a video of two or three smartphones with DIVA and other voice recognition software next to each other. Then I replayed the recording and counted the frames between the uttering of word and the word being displayed on the screen. Then I just needed to calculate the seconds based on the fps of the video file. I would do that with two different sentences every now and then. All competitive voice recognition software was faster than 1.0 second, with Google being the fastest. DIVA was way behind. Fixing this was not an easy task. There are different systems that work together and different reasons why it was taking longer for DIVA.

Every time I did the test I shared the results in our weekly meetings and asked the team what we could do about it. The engineers came up with ideas. After those were deployed, I tested again and shared the results. It was important to keep pressing on the issue continuously. Just having it as a ticket in the backlog would not work. It is only when a problem haunts you that you think continuously about solutions. To ensure this was the case, the team needed to be made aware of the issue. The process went on for nine months. Not every change we deployed made it better. But every change meant we were trying, and gave us a new way of looking at things. The engineers also would come up with ideas for simple visual indicators that the system was working or for debugging techniques so the user could see on the screen when something was stuck. 

Here are a couple of video recordings:

https://www.youtube.com/watch?v=wkhvE5JUb60
https://www.youtube.com/watch?v=JxhHsZK1IY4
https://youtu.be/l1FXgdjkP70
https://youtu.be/Z8zWNs3hvTw

Nine months later we broke the 1.0 second barrier. It only took 0.6 seconds until an uttered word was displayed on the device. That was 350% faster than when we started. We were even faster than Apple Siri, and nearly as fast as Google speech recognition. This was a big achievement for the team.

[Make a diagram showing the speed of Google, Siri and DIVA over time)

Design is not how it looks, but how it works. And only close teamwork between engineering and design can make it work smoothly.