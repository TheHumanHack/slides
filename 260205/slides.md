---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 'The Human Hack: The Future of Consulting Culture'
info: |
  ## The Human Hack: The Future of Consulting Culture
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
layout: two-cols
class: text-center
---
<!-- SECTION 2: INTRODUCTIONS -->

::left::

<img src="https://avatars.githubusercontent.com/u/12345" class="rounded-full h-40 w-40 mx-auto" alt="Dan Barber">

### Dan Barber
Microsoft MVP

<!-- Add Dan's bio or key points here -->
 
::right::

<img src="https://avatars.githubusercontent.com/u/90565164" class="rounded-full h-40 w-40 mx-auto" alt="Ian Tweedie">

### Ian Tweedie
Seasoned Leader

<!-- Add Ian's bio or key points here -->

<!--
A brief introduction to your hosts.

Dan Barber:
- Microsoft MVP with deep expertise in...
- Passionate about community and...

Ian Tweedie:
- Years of experience leading consulting teams...
- Focused on building cultures of excellence...

We're here to share our stories, our scars, and the lessons we've learned along the way. We want this to be a conversation, so please bring your questions and get involved.
-->

---
layout: center
class: text-center
---
<!-- SECTION 3: LANDING PAGE -->

# Exploring the Human Hack

Choose a topic to dive into.

<div class="grid grid-cols-2 gap-4 mt-10">
  <div @click="$slidev.nav.go(7)" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">People Over Process</h3>
    <p class="text-sm">Fostering critical thinking and building trust.</p>
  </div>
  <div @click="$slidev.nav.go(8)" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">Missionaries vs Mercenaries</h3>
    <p class="text-sm">Moving from transactional delivery to purposeful impact.</p>
  </div>
  <div @click="$slidev.nav.go(9)" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
    <h3 class="text-xl">A Culture of Excellence</h3>
    <p class="text-sm">How treating employees well translates to client success.</p>
  </div>
  <div @click="$slidev.nav.go(10)" class="p-4 border rounded-lg hover:bg-gray-200 hover:bg-opacity-10 cursor-pointer">
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

---
layout: default
---
<!-- MINI-DECK 1: PEOPLE OVER PROCESS -->

# People Over Process

### Sharpen Critical Thinking
- **Ask "Why" Five Times:** Encourage teams to dig beyond the surface to find the root cause.
- **Challenge Assumptions:** Create a safe environment to question the "givens."
- **Focus on Business Value:** Frame every task in the context of the client's goals.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

<!--
**Detailed Notes for "People Over Process"**

**Sharpening Critical Thinking:**
- The "Five Whys" is a simple but powerful technique. If a client says "We need a new dashboard," don't just build it. Ask why. "Why do you need a new dashboard?" -> "Because we can't see our sales data." -> "Why can't you see it?" -> "Because the current report is too slow." -> "Why is it slow?" -> "Because the database query is inefficient." -> "Why is it inefficient?" -> "Because it wasn't designed for this kind of reporting." The root problem isn't the dashboard, it's the data structure. Solving that provides much more value.
- Psychological safety is key to challenging assumptions. Your team must know they won't be punished for speaking up, even if they're wrong. Leaders must model this behavior by being open to being challenged themselves.
- Connecting to business value changes the conversation from "I'm building a feature" to "I'm helping the client increase revenue by 5%." This is motivating and ensures alignment.

**Building Trust:**
- Empathy is about understanding the client's world. What are their personal and professional pressures? What does a "win" look like for them?
- Radical transparency means sharing bad news early. A client who finds out about a problem from you will see you as a partner. A client who discovers a problem on their own will see you as a vendor who hid something.
- Curiosity builds rapport. Ask about their industry, their career, their challenges. People want to work with people they like and who are genuinely interested in them.
-->

---
layout: default
---

# People Over Process

### Build Strong Relationships
- **Encourage Empathy:** Train consultants to see the world from the client's perspective.
- **Promote Open Communication:** Share the good, the bad, and the ugly—early.
- **Be Genuinely Curious:** A consultant's greatest tool is curiosity.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

---
layout: default
---
<!-- MINI-DECK 2: MISSIONARY VS MERCENARY -->

# Missionaries vs. Mercenaries

<div class="grid grid-cols-2 gap-4">
<div>
  <h3>Mercenaries (The "What")</h3>
  <ul>
    <li>Motivated by compensation.</li>
    <li>Execute tasks in the contract.</li>
    <li>Engagement is transactional.</li>
    <li>Asks: "What do you want me to build?"</li>
  </ul>
</div>
<div>
  <h3>Missionaries (The "Why")</h3>
  <ul>
    <li>Motivated by the mission.</li>
    <li>Believe in the client's success.</li>
    <li>Own the outcome.</li>
    <li>Asks: "Why are we building this?"</li>
  </ul>
</div>
</div>

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

<!--
**Detailed Notes for "Missionaries vs. Mercenaries"**

This is a concept popularized by John Doerr of Kleiner Perkins. It's a fundamental distinction in team culture.

**Mercenaries:**
- They are skilled professionals who do good work. There is nothing inherently wrong with being a mercenary.
- However, their loyalty is to the paycheck. They will deliver exactly what is asked, but rarely more.
- They are less likely to challenge a client's bad idea, because their job is to fulfill the contract, not to guarantee the client's long-term success.
- This culture is easier to build but harder to sustain. It leads to high churn and a constant need to "sell" the next project.

**Missionaries:**
- They are driven by a purpose. They believe in the company's mission and the client's success.
- They see the client's problem as their own problem.
- They will challenge, innovate, and push back to ensure the *right* thing gets built, not just the *asked-for* thing.
- This creates immense trust and turns a client relationship into a true partnership.
- These are the teams that create breakthrough results.
-->

---
layout: default
---

# Driving a Missionary Culture

- **Define and Live the Mission:** Your purpose must be more than profit. It should guide hiring, project selection, and daily decisions.
- **Hire for Belief, Not Just Skill:** During interviews, ask about their proudest moments, their motivations, and the impact they want to have.
- **Empower and Trust Your Team:** Give them the "why" and the strategic goals, then give them the autonomy to figure out the "how." Micromanagement kills the missionary spirit.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

---
layout: default
---
<!-- MINI-DECK 3: CULTURE OF EXCELLENCE -->

# The Golden Rule of Consulting Culture

### The way you treat your employees is the way they will treat your clients.

It is a direct and unavoidable reflection.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

<!--
**Detailed Notes for "A Culture of Excellence"**

This is the most critical takeaway for any leader. You cannot expect world-class performance for your clients from a team that is treated poorly internally.

- **If you treat employees like a number...** they will treat clients like a line item on a contract. The relationship will be purely transactional. They will do the bare minimum to meet the SOW.
- **If you micromanage and don't trust your employees...** they won't feel empowered to take ownership. They will be afraid to bring creative solutions to your clients for fear of being reprimanded for stepping outside the box.
- **If you don't invest in your employees' growth...** they won't have the confidence or the skills to be true advisors. They will become order-takers.

The opposite is also true.
- **When you treat employees with respect and empathy...** they learn to treat clients with that same respect and empathy. This builds the strong, trust-based relationships that lead to long-term partnerships.
- **When you create psychological safety internally...** your team will have the confidence to ask the tough, critical questions of your clients that uncover real value.
- **When you invest in your team...** they feel valued. A valued employee doesn't just complete tasks; they go the extra mile because they are proud of their work and their company.
-->

---
layout: default
---

# Building a Culture of Excellence

- **Respect and Empathy:** Model the behavior you want to see.
- **Psychological Safety:** Make it safe to fail, to ask questions, and to challenge the status quo.
- **Invest in Growth:** Support not just technical skills, but also communication, leadership, and empathy.

A valued employee doesn't just complete tasks; they go the extra mile because they are proud of their work and their company.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

---
layout: center
class: text-center
---
<!-- MINI-DECK 4: THINKING LIKE A PARTNER -->
layout: statement
---

# From Vendor to Partner

It's not about what you build. It's about the **business outcome** you create.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

<!--
**Detailed Notes for "Thinking Like a Partner"**

This is the core mindset shift. A vendor delivers a scope. A partner delivers an outcome. Our goal is to become partners. This means we measure our success not by whether the code is deployed, but by whether we moved the needle on a key business metric for our client.
-->

---
layout: default
---

# Shifting Your Focus

A simple change in perspective from a technical focus to a business focus.

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
    subgraph Technical Focus (Vendor)
        A[Requirements] --> B{Build Feature}
        B --> C[Deploy Code]
    end

    subgraph Business Focus (Partner)
        D[Strategic Goals] --> E{Identify Problem/Opportunity}
        E --> F[Define Measurable Outcome]
        F --> G(Co-create Solution)
        G --> H[Drive Adoption & Measure Impact]
    end
```

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

<!--
This diagram shows the two mindsets. The vendor mindset is linear and focused on execution. The partner mindset is a cycle focused on value. It starts with the client's high-level goals and ends with measuring the real-world impact of the solution. It's about being involved in the "why" and the "so what," not just the "what."
-->

---
layout: image-right
image: https://cover.sli.dev
---

# How to Think Like a Partner

- **Start with Strategic Context:** What are the client's biggest goals and challenges for the year?
- **Translate Tech to Business:** Frame problems in terms of Time, Money, or Risk.
- **Define Success with Metrics:** Agree on measurable KPIs before you start.
- **Speak the Language of Value:** Always answer the "So what?" for the client.
- **Think About People:** A solution no one uses is a failure. Plan for change.

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>

---
layout: two-cols
---

# Before and After

A practical example of shifting the language.

::left::

### Before (Vendor-Speak)

"We need to refactor the authentication service and migrate the user database to a new server."

**Focus:** Technical tasks.

::right::

### After (Partner-Speak)

"We've identified a **risk** with the current login system. By improving it, we can increase security and cut user login **time** by 50%, saving an estimated 1,000 employee hours per year."

**Focus:** Business impact (Risk, Time, Money).

<div class="mt-4">
  <span @click="$slidev.nav.go(5)" class="cursor-pointer text-sm opacity-75 hover:opacity-100">&lt; Back to Exploration</span>
</div>
