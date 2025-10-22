---
transition: slide-up
---

<div class="space-x-4 flex mb-12">
  <carbon-document-multiple-01 class="text-4xl text-amber-500" />
  <h1>Dual Licensing</h1>
</div>

<div class="space-y-12 text-3xl">
  <v-clicks>
    <div v-click class="uppercase tracking-wide opacity-70">
      Case: MySQL
    </div>
    <div>Community uses a copyleft license freely.</div>
    <div>Commercial users license proprietary integrations.</div>
    <div>Maintains openness while funding ongoing stewardship.</div>
  </v-clicks>
</div>

<!--
- Same codebase but two licenses.
- Open source license lets you use the code freely in any non-proprietary code.
- But if you want to embed MySQL in any closed products, you must pay for
the commercial (non-open source) license.
- Great if you are offering a tool that can be embedded into other technology
stacks.
-->

---
transition: slide-up
---

<div class="space-x-4 flex mb-12">
  <carbon-tools class="text-4xl text-emerald-500" />
  <h1>Support & Services</h1>
</div>

<div class="space-y-12 text-3xl">
  <v-clicks>
    <div class="uppercase tracking-wide opacity-70">
      Case: DHIS2
    </div>
    <div>Software remains free to adopt and adapt.</div>
    <div>Revenue comes from expertise, training, and deployments.</div>
    <div>Strengthens local capacity alongside the tech.</div>
  </v-clicks>
</div>

<!--
- Open source product but offer consulting, guidance, or certification
services.
- Revenue is around services and consulting.
- Mission alignment stays intact.
-->

---
layout: default
class: text-left
transition: slide-up
---

<div class="space-x-4 flex mb-12">
  <carbon-cognitive class="text-4xl text-sky-500" />
  <h1>Open Core</h1>
</div>

<div class="space-y-12 text-3xl">
  <v-clicks>
    <div class="uppercase tracking-wide opacity-70">
      Case: Airbyte, GitLab, DataBricks
    </div>
    <div>Core capabilities stay fully open-source</div>
    <div>Premium extensions fund focused innovation</div>
    <div>Community and enterprise invest in the same roadmap</div>
  </v-clicks>
</div>

<!--
- The core innovation of your product is open source.
- Premium features are only available to paid (non-open source) licenses.
- Challenge: striking the balance between making your open source version
truly valuable to the community, but ensuring your premium features provide
sufficient value to justify their cost (without intentionally making your
open source version worse).
- Ideal for tools that can be easily broken down into a core tool and add-on
features.
- Ideal for tools where the core innovation is inherently valuable and a public
good, but relies on "how you use it" to generate real-world impact. Your
business can focus on premium features that enhance the "how you use it"
component.
-->

---
layout: default
class: text-left
transition: slide-up
---

<div class="space-x-4 flex mb-12">
  <carbon-cloud-services class="text-4xl text-indigo-500" />
  <h1>Managed Hosting / SaaS</h1>
</div>

<div class="space-y-12 text-3xl">
  <v-clicks>
    <div class="uppercase tracking-wide opacity-70">
      Case: Supabase, Wordpress
    </div>
    <div>Codebase remains open and self-hostable</div>
    <div>Customers pay for convenience, uptime, and compliance</div>
    <div>Transparency builds trust in mission-aligned sectors</div>
  </v-clicks>
</div>

<!--
- Codebase is purely open source and self-hostable by anyone.
- You offer a cloud-hosted managed service.
- Users are paying for the convenience of your business hosting the service
and providing ongoing maintenance.
- This is only financially viable if the indirect costs of your software
(hosting, technical expertise, maintenance) would be more expensive to a
nonprofit, so it is cheaper for them to pay for your cloud-hosted subscription.
- It is unethical to intentionally make your software poorly documented
or difficult to self-host just to force users to pay for your managed service.
-->

---
transition: slide-up
---

<div class="space-x-4 flex mb-12">
  <carbon-delivery-truck class="text-4xl text-rose-500" />
  <h1>Hybrid Platforms</h1>
</div>

<div class="space-y-10 text-3xl">
  <v-clicks>
    <div class="uppercase tracking-wide opacity-70">
      Case: Docker, Avandar
    </div>
    <div>Core infrastructure remains fully open-source.</div>
    <div class="pl-6">
      <span class="uppercase">Docker</span>:
      Proprietary complementary tools but free to use.
    </div>
    <div class="pl-6">
      <span class="uppercase">Avandar</span>:
      data moat, curated data is proprietary
    </div>
    <div>Recurring revenue flows from subscriptions and cloud services.</div>
  </v-clicks>
</div>

<!--
Docker:
- Mix between open core and SaaS. Their core innovation is open source.
- Their managed service is free to use.
- But their add-ons, such as Docker Desktop, are proprietary. But they are
still offered free of cost.
- Their revenue generation comes from subscriptions fees if your needs exceed
their free tier.

Avandar Labs:
- SaaS with proprietary data curation.
- Software is open source and it is easy to self-host.
- However, Avandar offers curation of plugins and open data.
- Organizations can self-host but they will not have access to the Avandar
data ecosystem, since that is accessible only in the cloud-hosted Avandar
databases. So this keeps Avandar valuable as a standalone product, and there
is nothing stopping organizations from finding plugins and open datasets on
their own and then manually importing them into Avandar. Being a part of
Avandar's paid cloud-hosted instance gives users acceess to a more
user-friendly data and plugin ecosystem, allowing them to spend more time
focusing on their missions.
-->
