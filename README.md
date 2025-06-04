# PURPOSE

I’ve always liked using ChatGPT. Not just because it’s smart or helpful, but because it actually feels kind of friendly. I know it sounds weird, but sometimes it’s like having a virtual friend. There have been times when I’ve asked it the most random or even personal stuff, just because it was there and easy to talk to.

At some point, me and a friend started calling it JuanGPT. I don’t even remember exactly why. I guess giving it a name made it feel more human. More like someone you could talk to, not just a chatbot sitting on a website.

One day I thought, what if I actually built the real JuanGPT? Not just as a joke, but for real.

I didn’t want just another assistant that gives robotic answers. I wanted something with personality. Something that felt alive. A voice that could joke around, say things with attitude, maybe even roast me or hype me up if I needed it.

I also wanted it to be free. Not stuck in a browser. Not always needing internet. I pictured something that could run from my phone, maybe even walk or roll around like a little sidekick.

JuanGPT started as a fun idea, but now it’s become something more. For me, it’s a way to make AI feel closer to how we connect in real life. With humor, emotion, and a bit of chaos.

# EARLY DEVELOPMENT

The idea from the start was to make JuanGPT something I could actually carry with me. I didn’t want it stuck on a desktop or always needing a browser. I thought it would be cool to run it on my old phone or maybe even on my Raspberry Pi. Something small and personal. A little assistant I could talk to wherever I wanted.

So I began building the first version on my computer. That was the easiest place to experiment and get things working before trying to move it to a smaller device. The goal was simple. I wanted it to take my voice, send the message to ChatGPT, and then talk back to me. Nothing more.

I used Python to make it work. For voice input I used a library called speech recognition. For the responses I connected it to the OpenAI API. And to make it talk I used a text to speech tool. It wasn’t fancy but it worked. I could speak and hear it answer. That alone felt kind of magical.

That first version ran inside a terminal. I had to press a key to activate it. The voice sounded robotic and awkward but the moment it gave me a smart or funny reply I knew it had potential. JuanGPT was no longer just a joke I made with a friend. It was real. And I couldn’t stop there.

# Making JUANGPT Smarter

Once I had the voice working, I wanted more. Talking was cool, but I needed JuanGPT to actually be useful. I didn’t want it to just respond with words. I wanted it to help me with my day.

So I started adding new features. First, I made it play music. I used a bit of Python magic with libraries like pydub and some local files to make it play songs directly from my computer. Later I connected it with tools to stream audio straight from YouTube. Now I could just say “play something chill” and boom, music would start.

Then I gave it the ability to tell me the weather. For that, I used a weather API like OpenWeatherMap. I taught JuanGPT how to fetch real-time info and say things like “It’s gonna rain in the afternoon, grab a jacket.” That was the moment it really started feeling like an assistant.

But the biggest step was when I gave it memory.

I wanted to say something like “Tomorrow I have to go to the gym” and not have to remind it again later. So I built a basic memory system where it could save and recall stuff I told it. Not just facts, but little personal things. Now when I said “Don’t let me forget my presentation” or “Remind me to buy eggs,” it actually remembered.

That changed everything. JuanGPT wasn’t just reacting. It was starting to know me.

JUANGPT ON MY PHONE

Once JuanGPT was running smoothly on my computer, I wanted to carry it around. The plan was to run it on my old Android phone using Termux, which basically turns your phone into a little Linux machine. It sounded easy. It wasn’t.

At the beginning, I couldn’t even talk to it. I had to type every message like some kind of caveman. Android doesn’t allow real-time audio capture from terminal apps, and Python doesn’t have a reliable way to use the mic under Android unless you build a full native app. Which I wasn’t about to do. So for a while, JuanGPT was mute and I had to talk to it with my thumbs.

After hours of searching and trying weird things, I finally found a way. Termux has a plugin called termux-speech-to-text. It’s not perfect, but it works. I integrated it into the code, and just like that, I could speak and have the message transcribed directly into the terminal. It wasn’t smooth at first, but it worked well enough to feel like real progress.

And after all the frustration, it actually felt kind of amazing.
