<!-- This file is the page shown at https://github.com/divergent-futures It only renders if this repository is named exactly `.github`. This is the one place the structure is drawn rather than implied — GitHub can't nest anything. When a project or a channel is added, update it here. --> <div align="center">
Divergent Futures

An independent studio building in the open.

The problems worth solving, and the paths out of them.

divergentfutures.co · tj@divergentfutures.co

</div>
How this is organised

Everything here belongs to Divergent Futures. Repositories are grouped by what they are, and tagged with which channel they serve — so there are two ways to find something.

                          DIVERGENT FUTURES
                                 │
        ┌──────────────┬─────────┴────────┬──────────────┐
        │              │                  │              │
      hw-            app-               lab-           ops-
    hardware     applications         research        studio

Browse by division — scroll down, the repository list sorts this way too.

Filter by channel: divergent-futures · humans-in-space · living-on-the-spectrum · cosmos

Each channel has its own site: Divergent Futures · Humans in Space · Living on the Spectrum · Cosmos

🔧 hw- · Hardware

Physical things, published as buildable documentation. Reciprocally licensed under CERN-OHL-S — build on them freely, improvements come back to the commons.

hw-slipstream

in progress · Divergent Futures

An aerodynamic, all-electric camping trailer designed to be towed behind an EV without destroying its range. Modular — roughly 80% invariant core, 20% configurable — and tiered by build complexity rather than by spec, so the documentation tells you what you can attempt rather than what you can afford.

Pre-build, flagship first. Configurator figures are researched estimates and are labelled as such; they get replaced with measured values as Build #1 produces them.

hw-house-bus

in progress · Divergent Futures

An all-electric self-moving dwelling built on one premise: stop solving heating, cooling, power and storage as four separate problems. One structural battery, one coolant loop, one DC bus. 300 kWh sodium-ion at 800 V, with a small CHP generator whose waste heat is the point rather than a loss.

⚠️ Not a validated build. High-voltage and combustion hazards are documented in the repository. Read them before proposing changes — and before building anything.

💻 app- · Applications

Software you can download and run.

app-writers-codex

in progress · Cosmos · AGPL-3.0 · Svelte + Vite PWA

A local-first, offline-capable organiser for story worlds — characters, timelines, places, threads. Runs in your browser, stores everything on your own machine, works with the network switched off. No account, no cloud, no backend.

app-pulse

built, not shipped · Living on the Spectrum · AGPL-3.0 · Python

A privacy-first desktop companion that nudges movement, protects deep focus, and builds gentle self-knowledge. A mirror, not a tracker — no account, no sync, nothing leaves your machine. Designed for, though not limited to, ADHD and autistic minds.

🔬 lab- · Research

Models, calculators and analyses. These produce answers rather than tools, and they feed the channels.

lab-mars-supplies-calculator

live · Humans in Space

An interactive model of what a crewed Mars mission actually has to carry. Change the crew size and duration, watch the mass climb. Every assumption is visible and editable — a supply model that hides its inputs is an opinion with decimal places.

lab-synapse

built, not shipped · Divergent Futures · MIT

Feed it an exhibitor list from a maker event; it emits a self-contained HTML application mapping who's working on what and where domains are quietly converging — classified as abundance, progress, stagnation or collapse.

⚙️ ops- · Studio

The machinery that makes the rest possible.

ops-websites

live · all channels · Astro

The four public sites: one monorepo, one shared design system, four independent static deployments. No JavaScript framework on the page, no analytics, no cookie banner. Source for everything at divergentfutures.co.

How things are labelled

Every project states its real status rather than its aspiration.

Status	Means
live	In use. Works.
in progress	Actively being built. Expect it to change under you.
built, not shipped	It works, but there's no release, no installer, no support.
parked	Was real, isn't being worked on.
archived	Finished or abandoned. Kept for the record.

Nothing is hard-deleted here. A project that didn't work out gets archived, not removed — an honest record includes the things that didn't land.

Contributing

Issues and pull requests are welcome on any repository. Start with that repo's README; the hardware projects carry safety context you need before suggesting changes.

Corrections are the most valuable contribution. If a number is wrong, a source is misread, or a calculation doesn't hold — open an issue. You don't need to supply a fix.

The contributing guide, code of conduct and security policy are shared across every repository here.

Licences

Chosen per project rather than one compromise for everything:

Hardware — CERN-OHL-S-2.0 · reciprocal, so improvements come back
Code — MIT or AGPL-3.0, depending on the project
Documentation — CC-BY-4.0

Each repository states its own. Where they differ, the repository wins.
