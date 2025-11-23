import React from "react";

// Single-file React component (Tailwind CSS assumed available) // Default export: Portfolio page for Ndumiso Praysworth Zama

export default function PortfolioPage() { return ( <div className="min-h-screen bg-gray-50 text-gray-900 antialiased"> <header className="max-w-5xl mx-auto px-6 py-8 flex items-center justify-between"> <div> <h1 className="text-2xl font-extrabold tracking-tight">Ndumiso Praysworth Zama</h1> <p className="text-sm text-gray-600">AI Automation Specialist • Chatbot Developer • No-Code App Builder</p> </div> <nav className="space-x-4 text-sm"> <a href="#projects" className="hover:underline">Projects</a> <a href="#experience" className="hover:underline">Experience</a> <a href="#skills" className="hover:underline">Skills</a> <a href="#contact" className="hover:underline">Contact</a> </nav> </header>

<main className="max-w-5xl mx-auto px-6 pb-20">
    <section className="bg-white rounded-2xl p-8 shadow-sm">
      <div className="md:flex md:items-center md:justify-between">
        <div className="md:w-2/3">
          <h2 className="text-3xl font-bold leading-tight">AI Automation Specialist & Product Builder</h2>
          <p className="mt-4 text-gray-700">I build AI-first automation systems, chatbots (WhatsApp + web), and no-code workflows that convert business needs into working digital tools. Creator of NexaAI — an orchestration system designed to turn natural language intent into repeatable engineering workflows.</p>

          <div className="mt-6 flex flex-wrap gap-3">
            <a href="/Ndumiso_Portfolio.pdf" className="inline-block px-4 py-2 rounded-lg border border-gray-200 text-sm font-medium hover:bg-gray-50">Download PDF</a>
            <a href="mailto:your.email@example.com" className="inline-block px-4 py-2 rounded-lg bg-slate-900 text-white text-sm font-medium hover:opacity-95">Email</a>
            <a href="https://linkedin.com/in/your-linkedin" target="_blank" rel="noreferrer" className="inline-block px-4 py-2 rounded-lg border border-gray-200 text-sm font-medium hover:bg-gray-50">LinkedIn</a>
          </div>
        </div>

        <div className="mt-6 md:mt-0 md:w-1/3 flex justify-center">
          <div className="w-40 h-40 rounded-xl bg-gradient-to-br from-indigo-600 to-sky-400 flex items-center justify-center text-white font-bold text-lg">ND</div>
        </div>
      </div>
    </section>

    <section id="projects" className="mt-8">
      <h3 className="text-2xl font-semibold">Selected Projects</h3>
      <div className="mt-4 grid gap-6 md:grid-cols-2">
        <article className="bg-white p-6 rounded-lg shadow-sm">
          <h4 className="font-semibold">NexaAI — Orchestration & Automation Ecosystem</h4>
          <p className="mt-2 text-sm text-gray-700">Designed an AI orchestration system: intent parsing, orchestrator, memory store, model layer, connectors (WhatsApp, CRM), and a deployable pipeline. Produced architecture spec and MVP roadmap.</p>
          <ul className="mt-3 text-xs text-gray-600 space-y-1">
            <li>Tech: OpenAI, n8n, Rasa, Postgres, React</li>
            <li>Deliverables: Architecture spec, workflows, prompt library</li>
          </ul>
        </article>

        <article className="bg-white p-6 rounded-lg shadow-sm">
          <h4 className="font-semibold">WhatsApp Business AI Assistant</h4>
          <p className="mt-2 text-sm text-gray-700">Built a WhatsApp AI assistant covering FAQ automation, booking flows, stock enquiries, and lead collection — designed for SME adoption in South Africa.</p>
          <ul className="mt-3 text-xs text-gray-600 space-y-1">
            <li>Tech: WhatsApp Cloud API, OpenAI, n8n</li>
            <li>Impact: Reduced manual handling by up to 60% in pilot flows</li>
          </ul>
        </article>

        <article className="bg-white p-6 rounded-lg shadow-sm">
          <h4 className="font-semibold">Web Chatbot & Engagement Agent</h4>
          <p className="mt-2 text-sm text-gray-700">Integrated website chatbot for product discovery, add-to-cart flows, and CX handoffs to human agents.</p>
          <ul className="mt-3 text-xs text-gray-600 space-y-1">
            <li>Tech: JavaScript, REST APIs, lightweight React components</li>
            <li>Focus: Conversion lift & reduced support load</li>
          </ul>
        </article>

        <article className="bg-white p-6 rounded-lg shadow-sm">
          <h4 className="font-semibold">Chrome Task-Capture Prototype</h4>
          <p className="mt-2 text-sm text-gray-700">Chrome extension prototype to capture web context and convert it into tasks for the NexaAI pipeline (summaries, research jobs, task creation).</p>
          <ul className="mt-3 text-xs text-gray-600 space-y-1">
            <li>Tech: Chrome Manifest V3, background scripts, API hooks</li>
          </ul>
        </article>
      </div>
    </section>

    <section id="experience" className="mt-12 bg-white p-6 rounded-lg shadow-sm">
      <h3 className="text-2xl font-semibold">Experience</h3>
      <div className="mt-4 space-y-4 text-sm text-gray-700">
        <div>
          <h4 className="font-medium">Sales Assistant — Maxhosa Africa</h4>
          <p className="text-xs text-gray-600">2024 – Present</p>
          <p className="mt-1">Supported in-store digital systems, improved CX through tech-enabled displays, and coordinated customer-facing automation pilots.</p>
        </div>

        <div>
          <h4 className="font-medium">Assistant Manager — All Good Things</h4>
          <p className="text-xs text-gray-600">2021 – 2024</p>
          <p className="mt-1">Managed operations, banking oversight, staff training, and helped implement process improvements.</p>
        </div>

        <div>
          <h4 className="font-medium">Floor Supervisor — Vodacom Pavilion</h4>
          <p className="text-xs text-gray-600">2019 – 2021</p>
          <p className="mt-1">Led floor operations, trained staff, and resolved technical product queries.</p>
        </div>
      </div>
    </section>

    <section id="skills" className="mt-12">
      <h3 className="text-2xl font-semibold">Skills & Tech Stack</h3>
      <div className="mt-4 grid gap-4 md:grid-cols-3">
        <div className="bg-white p-5 rounded-lg shadow-sm">
          <h5 className="font-semibold">AI & Automation</h5>
          <p className="mt-2 text-sm text-gray-700">OpenAI, Claude, Rasa, n8n, Make, Zapier</p>
        </div>

        <div className="bg-white p-5 rounded-lg shadow-sm">
          <h5 className="font-semibold">Development</h5>
          <p className="mt-2 text-sm text-gray-700">HTML, CSS, JavaScript, React (basics), REST APIs</p>
        </div>

        <div className="bg-white p-5 rounded-lg shadow-sm">
          <h5 className="font-semibold">Project Skills</h5>
          <p className="mt-2 text-sm text-gray-700">Agile, Documentation, System Design, POPIA-aware practices</p>
        </div>
      </div>
    </section>

    <section id="contact" className="mt-12 bg-white p-6 rounded-lg shadow-sm">
      <h3 className="text-2xl font-semibold">Contact</h3>
      <p className="mt-3 text-sm text-gray-700">Email: <a href="mailto:your.email@example.com" className="text-sky-600 hover:underline">your.email@example.com</a></p>
      <p className="mt-1 text-sm text-gray-700">LinkedIn: <a href="https://linkedin.com/in/your-linkedin" target="_blank" rel="noreferrer" className="text-sky-600 hover:underline">linkedin.com/in/your-linkedin</a></p>

      <form className="mt-6 grid gap-3 sm:grid-cols-2">
        <input aria-label="name" placeholder="Your name" className="p-3 rounded-md border" />
        <input aria-label="email" placeholder="Email" className="p-3 rounded-md border" />
        <textarea aria-label="message" placeholder="Message" className="p-3 rounded-md border sm:col-span-2" rows={4} />
        <button type="button" className="sm:col-span-2 inline-block px-4 py-2 rounded-md bg-slate-900 text-white">Send Message</button>
      </form>
    </section>

    <footer className="mt-16 text-center text-xs text-gray-500">© {new Date().getFullYear()} Ndumiso Praysworth Zama — Portfolio</footer>
  </main>
</div>

); }
