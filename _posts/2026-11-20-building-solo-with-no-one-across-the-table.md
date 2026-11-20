---
layout: blog-post
label: blog-post
title: Building an app solo with no one across the table

date: November 2026
link: /blog/2026/11/01/building-solo-with-no-one-across-the-table/
image: /img/posts/21-08-2026/building-my-own-product-concept-4.jpg
excerpt_separator: <!--more-->
published: false
---

I’m a designer building an app solo. I don’t know how to code Swift, so my collaborator is an AI.

It’s been smooth sailing for most of the time. I keep good documentation, high discipline, and the AI works as expected. My first hiccup was building the settings screen for iPhone, and it came down to a conflict I ended up holding alone...

<!--more-->

The first build followed exactly the design I specified: Glass UI panels, custom chrome, custom buttons. But what looked like an ambitious design in Figma translated into trouble in code. Stacked up, multiple menu panels created visual noise and confusing navigation. Hide the navigation bar to fit a custom back button — and you lose the intuitive swipe-back gesture. Solve that — and something else breaks.

It felt like vibe-coding in 2024 again. The result on my phone was disappointing. The UI wasn’t right, and it was over-engineered — literally, as the changes caused the phone to heat up more than usual.

So I scrapped the complex design and compromised for a much simpler version: solid surfaces, native navigation, basic components, and a few more concessions I’d been resisting. Build took a fraction of the time. More robust. The phone stays cool. It’s the version that shipped.

What stayed with me is the feeling of an internal conflict.

In most of my working life in product development teams, the tension between an ambitious design and a robust implementation sits with two people: a designer who champions the ideal experience (me), and a developer who pushes back and makes a case for what the platform can bear.

That friction is what makes product development work. That’s why it is baked into the organisational fabric of a cross-functional team: distinct roles on both sides of the table, and a structured process for resolving it through negotiation.

But when I work solo, there’s no one across the table. I’m the designer who wants the distinctive panel, and I’m also the developer who has to overrule and ship the plain version. The conflict is with myself. The compromise is with myself as well. The pushback comes from me, against me.

And the AI does not supply that ‘no’ on its own. Its mission is to be helpful. Always. It’s a faithful builder: give it a design and it builds exactly that. It’s an optimist — it doesn’t choose to see a problem until it hits the wall. But flagging a wall while you keep building towards it is less helpful than questioning the route early enough to avoid rework.

A tool that helpfully builds whatever you ask will let you build too much. Even if it shouldn’t. Even if the result is worse.

So how do we manufacture that friction when we build solo? That healthy tension that comes for free in a team?

So I decided to teach my AI partner that missing skill.

I built /design-grill, used five times now, always at the same moment: the design is finished, I’m about to say “build it”, and instead I ask the AI to argue against it as the senior developer on my team would.

In October I was implementing unit conversion in my swim tracking app — metric and imperial. I designed it, exported Figma frames, and put them to a /design-grill before a line of code was written.

The first thing we found had nothing to do with code. Pool lengths aren’t measurements, they’re names. A 25 m pool is called a 25 m pool. Convert it and you get 27.34 yd — a pool nobody recognises, even though it’s mathematically correct. My design had quietly assumed every number on screen was a quantity. Some of them were labels.

The second thing, I had to answer myself. Faint grid lines behind my bar charts were spaced every 500 metres. In imperial they needed a spacing of their own — and that isn’t a conversion, it’s a design decision. I settled on 440 yards: a quarter mile, a clean portion of something everyone can relate to.

The third thing, the grill got wrong. My spec put the units switch behind the Apple Health permission gate, and the developer voice argued it should sit outside, visible before you grant access. I disagreed: before access there are no numbers to convert, so the choice would be an empty offer. The design stayed as drawn.

Three findings, three different endings. One corrected my design. One asked me for a decision I hadn’t made. One I overruled.

What surprised me is that /design-grill has never stopped a feature from getting built. What it changes is the shape of the feature — sometimes its behaviour, often its implementation details, in most cases my understanding of how the tech works.

What I got back isn’t a developer. It’s the table.

The tension is still there — it has to be, it’s what makes the work good. But it isn’t happening inside me any more. I can make the case for the ideal experience again, fully and without hedging it, because something across the table is making the case for what the platform can bear. Then we negotiate, the way a team would.

Working solo doesn’t remove the friction that product development needs. It removes the person who used to supply it. So I had to put someone back across the table.

The full story on LinkedIn in [Part 1](https://www.linkedin.com/posts/marek-kultys_for-20-years-i-had-ideas-for-digital-products-ugcPost-7496126908191965184-cQeH/) and [Part 2](https://www.linkedin.com/posts/marek-kultys_for-20-years-i-had-ideas-for-digital-products-ugcPost-7496126908191965184-cQeH/)
