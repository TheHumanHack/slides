---
# try also 'default' to start simple
#theme: seriph
theme: the-unnamed
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 'The Human Hack: The Future of Consulting Culture'
info: |
  This isn’t about tools, templates, frameworks, or even just the latest AI technologies it’s about people and mindset. In this honest and practical session, we explore how as consultants and delivery leads, we can rediscover and develop better consulting cultures in a world obsessed with tools and delivery speed.

  Expect a candid conversation as two seasoned leaders in the Microsoft consulting community are interviewed by a fellow highly experienced leader. The session will be filled with, stories, audience Q&A, and actionable advice you can put straight into action back on your projects and in your teams. Bring your questions and get involved.
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

<!-- SECTION 1: INTRODUCTION -->

# The Human Hack
## The Future of Consulting Culture

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/thehumanhack/slides" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
Welcome everyone. Today we're talking about something that sits at the very core of successful consulting, but is often overlooked in our rush to adopt new tools and technologies. We're calling it 'The Human Hack'.
-->

---
layout: statement
---

# The Core Problem

It’s not about tools, templates, or AI.

It’s about **people** and **mindset**.

<br>

Our industry is obsessed with delivery speed, often at the expense of the human elements that drive true success.

<!--
Let's be honest, how many of us have been on projects that felt like they were technically perfect, but somehow missed the mark? The code was clean, the platform was deployed, but the client wasn't happy, or the solution didn't get adopted.

This session is about why that happens and how we can fix it. We're going to explore how we, as consultants and leaders, can build better cultures in a world that's becoming increasingly focused on tools and speed.
-->

---
layout: image-left
image: https://cover.sli.dev
---

# The Challenge We Face

AI and automation are accelerating the focus on **tools and frameworks**.

This creates a risk of losing the **human experience** and the **consulting mindset**.

<br>
<br>

<p v-click>
If you’ve ever felt your work was technically perfect but somehow missed the mark, this session is for you.
</p>

<!--
The rise of AI is a double-edged sword. It offers incredible opportunities for efficiency, but it also pushes us further towards a transactional, tool-focused model of consulting.

This can lead to a few key problems:
- We solve the *stated* problem, not the *real* problem.
- We deliver solutions that people don't want to use.
- Our work becomes a commodity, easily replaced by the next tool or a cheaper competitor.
- Our teams burn out, feeling like they are just part of a feature factory.

Today, we'll show you how to reclaim the mission and become the kind of consultant the industry desperately needs.
-->

---
layout: about-me
---
<!-- SECTION 2: INTRODUCTIONS -->

<img src="https://avatars.githubusercontent.com/u/12345" class="rounded-full h-40 w-40 mx-auto" alt="Dan Barber">

### Dan Barber
Microsoft MVP

<!-- Add Dan's bio or key points here -->

<!--
A brief introduction to your hosts.

Dan Barber:
- Microsoft MVP with deep expertise in...
- Passionate about community and...
-->
---
layout: about-me
helloMsg: Hello!
name: Ian Tweedie
imageSrc: https://avatars.githubusercontent.com/u/90565164
position: right
job: <job title>
line1: 
line2: 
social1: 
social2: 
social3: 
---
<!-- SECTION 2: INTRODUCTIONS -->

<!-- Add Ian's bio or key points here -->
<!--
A brief introduction to your hosts.
Ian Tweedie:
- Years of experience leading consulting teams...
- Focused on building cultures of excellence...

We're here to share our stories, our scars, and the lessons we've learned along the way. We want this to be a conversation, so please bring your questions and get involved.
-->

---
layout: center
class: text-center
routeAlias: explore
---
<!-- SECTION 3: EXPLORE PAGE -->

# Exploring the Human Hack

Choose a topic to dive into.

<div class="grid grid-cols-2 gap-4 mt-10">
  <div @click="$slidev.nav.go('people-over-process')" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">People Over Process</h3>
    <p class="text-sm">Fostering critical thinking and building trust.</p>
  </div>
  <div @click="$slidev.nav.go('missionaries-vs-mercenaries')" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">Missionaries vs Mercenaries</h3>
    <p class="text-sm">Moving from transactional delivery to purposeful impact.</p>
  </div>
  <div @click="$slidev.nav.go('culture-of-excellence')" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">A Culture of Excellence</h3>
    <p class="text-sm">How treating employees well translates to client success.</p>
  </div>
  <div @click="$slidev.nav.go('thinking-like-a-partner')" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">Thinking Like a Partner</h3>
    <p class="text-sm">Moving from vendor to valued partner.</p>
  </div>
</div>

<!--
Now, we want to dive deeper into three core pillars of the 'Human Hack'. We've structured this as an interactive session. I'll give a brief overview of each, and then you can choose where we go next.

1.  **People Over Process:** This is about sharpening our critical thinking skills and building the strong, trusting relationships that are the bedrock of any successful engagement.

2.  **Missionaries vs. Mercenaries:** This explores the powerful difference between a team that works for a paycheck and a team that works for a purpose, and how to build the latter.

3.  **A Culture of Excellence:** This is about the undeniable link between your internal culture and your external results. How the way you treat your team directly impacts how they treat your clients.

So, where should we start?
-->

---
src: ./pages/people-over-process.md
---
src: ./pages/missionaries-vs-mercenaries.md
---
src: ./pages/culture-of-excellence.md
---
src: ./pages/thinking-like-a-partner.md
---
layout: center
class: text-center
---
<!-- SECTION 4: CLOSE OUT -->


# Key Takeaways

- **Think Critically:** Always ask "why" to get to the true root of a problem.
- **Build Trust:** Encourage open communication, curiosity, and teamwork.
- **Deliver Value:** Ensure your work has a clear, measurable impact on people, processes, and technology.

Don’t let yourself drift into transactional delivery. Reclaim the mission, rebuild the mindset.

---
layout: end
---



<!--
Now, we want to dive deeper into three core pillars of the 'Human Hack'. We've structured this as an interactive session. I'll give a brief overview of each, and then you can choose where we go next.

1.  **People Over Process:** This is about sharpening our critical thinking skills and building the strong, trusting relationships that are the bedrock of any successful engagement.

2.  **Missionaries vs. Mercenaries:** This explores the powerful difference between a team that works for a paycheck and a team that works for a purpose, and how to build the latter.

3.  **A Culture of Excellence:** This is about the undeniable link between your internal culture and your external results. How the way you treat your team directly impacts how they treat your clients.

So, where should we start?
-->
