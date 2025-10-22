---
theme: default
title: Sustainable Open Source Technology Business Models
author: Juan Pablo Sarmiento
info: |
  Impact First Summit
  20–25 minute talk
fonts:
  sans: "Figtree"
  mono: "Fira Code"
layout: cover
transition: slide-left
drawings:
  persist: false
colorSchema: light
mdc: true
---

<div class="absolute top-6 flex space-x-3 items-center">
  <img src="./white_logo.png" width="30" alt="Avandar logo"/>
  <div class="uppercase tracking-[0.35em]">Avandar Labs</div>
</div>

# Sustainable Open Source Technology Business Models

<div class="opacity-80">
  <div>Juan Pablo Sarmiento &bullet; Founder & CEO of Avandar Labs</div>
  <div class="mt-8">
    <div>Impact First Summit 2025</div>
    <div class="opacity-70">October 15, 2025</div>
  </div>
</div>

---
layout: statement
transition: slide-up
---

# Principles without substance cannot last

Open source values need structural support to endure

<!--
- Open source is a value system, not just a license.

- However, being dogmatic about these principles and ethics can lead to unviable
business models. This dogmatism can hurt the social sector more than it helps.

- Idealism without structure collapses. Unfortunately, we live in a world where
structural support often involves money.
-->

---
layout: default
transition: slide-left
---

# The types of &ldquo;Open&rdquo;

<div class="grid grid-cols-3 gap-10 mt-22">
  <div v-click class="flex flex-col items-center gap-4">
    <carbon-plug class="text-7xl text-blue-500" />
    <span class="text-2xl font-semibold">Open Standards</span>
    <p class="text-lg opacity-80 text-center">Shared protocols keep systems interoperable</p>
  </div>
  <div v-click class="flex flex-col items-center gap-4">
    <carbon-data-structured class="text-7xl text-emerald-500" />
    <span class="text-2xl font-semibold">Open Data</span>
    <p class="text-lg opacity-80 text-center">Transparency enables trust and accountability</p>
  </div>
  <div v-click class="flex flex-col items-center gap-4">
    <carbon-code class="text-7xl text-indigo-500" />
    <span class="text-2xl font-semibold">Open Source</span>
    <p class="text-lg opacity-80 text-center">
      Reusable code accelerates collective progress
    </p>
  </div>
</div>

<!--
- First, let's talk about some key terms. What are the types of "open" we
are talking about?
- Emphasize that none of these definitions require "free" of cost.
- It's about transparency and freedom of reuse, but not free from costs.
- The social sector has conflated openness with non-commercialism.
- Open is the starting point, not a rejection of sustainability.
-->

---
layout: two-cols
layoutClass: gap-16
transition: slide-up
---

<div class="space-y-4">
  <div class="flex space-x-2">
    <carbon-unlocked class="text-4xl text-emerald-500" />
    <h1>Dogmatic Openness</h1>
  </div>
  <v-clicks>
    <div class="text-2xl font-semibold">Everything must be open</div>
    <div class="text-2xl opacity-80">Grants fund launches, not longevity</div>
    <div class="text-2xl opacity-80">Services-only business models</div>
    <div class="text-2xl opacity-80">Little incentive to innovate</div>
    <div class="text-2xl opacity-80">Freeloading</div>
  </v-clicks>
</div>

::right::

<div class="space-y-4">
  <v-clicks>
    <div class="flex space-x-2">
      <carbon-locked class="text-4xl text-rose-500" />
      <h1>Faux Openness</h1>
    </div>
    <div class="text-2xl font-semibold">Open-washing</div>
    <div class="text-2xl opacity-80">Code is open but unusable</div>
    <div class="text-2xl opacity-80">Community editions are limiting or poorly supported</div>
    <div class="text-2xl opacity-80">Lack of documentation makes self-hosting impossible</div>
  </v-clicks>
</div>

<!--
- This has lead to two competing approaches to open source in the social sector,
each equally dangerous.
- Dogmatic openness rejects any proprietary boundaries. Well-intentioned
businesses and nonprofits are left without legal protections or
sustainable business models. So they go under. They can't help people if they
no longer exist.
- So to fight this, other businesses adopt unethical approaches to open source,
just so they can check that box of being "open source" and still receive grants
and contracts.
- So they "open-wash" their product.
- Faux openness publishes code but keeps code and documentation so poorly
maintained that users are obligated to work with the sotware vendor to use the
software.
- Or, community editions are so limiting that users are essentially forced
to pay for an enterprise edition to get any real value.
- These open-washed approaches do not respect the spirit of open source and
provide none of the benefits of open source.
-->

---
layout: quote
transition: slide-left
---

# How do open source products stay alive?

What's the middle ground?

<!--
- We need to find an ethical middle ground for financially sustainable open
collaboration.
- We'll look at real-world approaches that have worked.
-->

---
layout: two-cols-header
layoutClass: gap-16
transition: slide-left
---

# Licenses: your first line of defense

::left::

<div class="bg-slate-800 rounded-md border border-2 border-slate-900 shadow-lg">
  <div
    class="
      text-lg uppercase tracking-wider
      opacity-80 border-b-2 border-b-slate-900
      px-6 py-1
      rounded-t-md
      bg-slate-900
    ">
      Permissive
    </div>
  <div class="p-6">
    <div class="text-2xl font-semibold mt-3">MIT · Apache</div>
    <p class="text-md opacity-80 mt-4">Maximize adoption and reuse.</p>
  </div>
</div>

::right::

<div class="bg-slate-800 rounded-md border border-2 border-slate-900 shadow-lg">
  <div
    class="
      text-lg uppercase tracking-wider
      opacity-80 border-b-2 border-b-slate-900
      px-6 py-1
      rounded-t-md
      bg-slate-900
    ">
      Copyleft
    </div>
  <div class="p-6">
    <div class="text-2xl font-semibold mt-3">GPL · AGPL · CPAL</div>
    <p class="text-md opacity-80 mt-4">Guarantee openness downstream.</p>
  </div>
</div>

<!--
- Licenses are your first line of defense.
- Open Source Initiative (OSI) licenses have been legally tested and can be
used to set conditions to how your software can be reused, while still
remaining truly open source.
- Permissive licenses boost adoption but offer fewer business protections.
- Copyleft licenses still offer openness but says that if anyone copies your
software they must also keep it open source and document all changes. This means
nobody can take your code and make it proprietary.
- Some strong copyleft licenses, that are approved by the Digital Public Goods
Alliance as still being ethically in line with the Digital Principles for
Development, are:

GPL = GNU General Public License
AGPL = GNU Affero General Public License
CPAL = Common Public Attribution License

Avandar uses CPAL. It requires attribution to Avandar if any Avandar code is reused.
-->

---
src: ./pages/business-models.md
---

---
transition: slide-left
---

# The Ethical Playbook

<div class="space-y-6 text-3xl mt-12">
<ol>
  <v-clicks>
    <li>Be explicit about what is open and why.</li>
    <li>License intentionally to support viability.</li>
    <li>Ensure deployability. <strong>Do not open-wash.</strong></li>
    <li>Price transparently so value is understood.</li>
    <li>Ensure the open version provides real value.</li>
    <li>Share governance to practice openness beyond code.</li>
  </v-clicks>
  </ol>
</div>

<!--
Highlight the final point: merely publishing your code is not sufficient.
True openness is about collaboration. Therefore, you need to find ways to
share governance.
-->

---
layout: center
transition: fade
class: text-center
---

# Ethics + Sustainability = Durable Open Source

Durability keeps communities and missions alive.

<!--
A durable open source model builds trust, longevity, and ethical social impact.
-->

---
layout: statement
transition: fade
class: text-center
---

# Open source must be durable to be ethical

Your software can't be ethical if it stops working

<!--
Open source must be durable to be ethical.

Simply put, for software to be ethical it needs to exist in the first place.

If your business stops existing, you can't help anyone.
-->

---
layout: end
---

<div class="text-white">
  <h1>Open source must be durable to be ethical</h1>
  <carbon-chat class="text-6xl text-sky-400"  />
</div>

<div class="inline-block space-x-2 flex justify-center items-center">
  <carbon-email class="text-lg" />
  <a href="mailto:pablo@avandarlabs.com">pablo@avandarlabs.com</a>
</div>

<div class="relative top-18 text-white flex flex-col items-center">
  <img :style="{ marginBottom: '-0.75rem' }"  src="./white_logo.png" width="70" alt="Avandar logo" />
  <p>Avandar Labs · avandarlabs.com</p>
</div>

<style>
  .slidev-layout.end {
    --uno: bg-slate-600
  }
</style>
