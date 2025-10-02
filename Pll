import React from "react"; import { motion } from "framer-motion";

// PortfolioSite.jsx - PL Studio Design // Adaptado para o perfil @pl.studio_design

export default function PortfolioSite() { const NAME = "PL Studio Design"; const TITLE = "Criações Digitais"; const BIO = Design que conecta ideias e pessoas.  Artes digitais | Flyers | Posts para redes sociais.;

const PROJECTS = [ { title: "Artes Digitais", description: "Criações visuais únicas para projetos e marcas, com ilustrações, conceitos e elementos gráficos.", tech: ["Illustrator", "Photoshop", "Figma"], link: "https://instagram.com/pl.studio_design", image: null, }, { title: "Flyers Criativos", description: "Flyers digitais modernos para divulgação de eventos, negócios e iniciativas pessoais.", tech: ["CorelDraw", "Photoshop"], link: "https://instagram.com/pl.studio_design", image: null, }, { title: "Posts para Redes Sociais", description: "Layouts otimizados para engajamento, pensados para fortalecer a presença digital de marcas.", tech: ["Canva Pro", "Figma"], link: "https://instagram.com/pl.studio_design", image: null, }, ];

const CONTACT = { email: "plstudio.design@email.com", linkedin: "https://linkedin.com/in/seu-perfil", instagram: "https://instagram.com/pl.studio_design", whatsapp: "https://wa.me/seunumerowhatsapp", };

return ( <div className="min-h-screen bg-gray-900 text-gray-100 antialiased"> <header className="max-w-5xl mx-auto p-6 flex items-center justify-between"> <div> <h1 className="text-3xl font-bold text-blue-400">{NAME}</h1> <p className="text-sm text-gray-400">{TITLE}</p> </div> <nav className="space-x-6 text-sm"> <a href="#projects" className="hover:underline"> Portfólio </a> <a href="#about" className="hover:underline"> Sobre </a> <a href="#services" className="hover:underline"> Serviços </a> <a href="#contact" className="hover:underline"> Contato </a> </nav> </header>

<main className="max-w-5xl mx-auto p-6">
    {/* Hero */}
    <section className="grid grid-cols-1 md:grid-cols-3 gap-6 items-center py-10">
      <div className="md:col-span-2">
        <motion.h2
          initial={{ opacity: 0, y: 10 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.5 }}
          className="text-4xl font-extrabold leading-tight text-white"
        >
          Conectando ideias e pessoas através do design.
        </motion.h2>
        <p className="mt-4 text-gray-300 whitespace-pre-line">{BIO}</p>

        <div className="mt-6 flex gap-3">
          <a
            href={CONTACT.instagram}
            target="_blank"
            rel="noopener noreferrer"
            className="px-5 py-2 rounded-lg shadow-sm border border-blue-400 text-blue-400 hover:bg-blue-500 hover:text-white transition"
          >
            Instagram
          </a>
          <a
            href={CONTACT.whatsapp}
            target="_blank"
            rel="noopener noreferrer"
            className="px-5 py-2 rounded-lg shadow-sm border border-green-400 text-green-400 hover:bg-green-500 hover:text-white transition"
          >
            WhatsApp
          </a>
        </div>
      </div>

      <div className="flex items-center justify-center">
        <div
          className="w-40 h-40 bg-gradient-to-tr from-blue-500 to-indigo-600 rounded-2xl flex items-center justify-center text-white font-bold"
          role="img"
          aria-label="Logo do PL Studio"
        >
          PL
        </div>
      </div>
    </section>

    {/* Projects */}
    <section id="projects" className="py-10">
      <h3 className="text-2xl font-semibold mb-6 text-blue-400">Portfólio</h3>
      <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
        {PROJECTS.map((p, i) => (
          <article
            key={i}
            className="bg-gray-800 rounded-2xl p-5 shadow-sm hover:shadow-md transition-shadow"
          >
            <div className="h-36 bg-gray-700 rounded-md flex items-center justify-center">
              <span className="text-sm text-gray-400">{p.title}</span>
            </div>
            <h4 className="mt-3 font-semibold text-white">{p.title}</h4>
            <p className="text-sm text-gray-400 mt-2">{p.description}</p>
            <p className="text-xs text-gray-500 mt-3">Tecnologias: {p.tech.join(", ")}</p>
            <div className="mt-4">
              <a
                href={p.link}
                target="_blank"
                rel="noopener noreferrer"
                className="text-sm text-blue-400 hover:underline"
              >
                Ver no Instagram
              </a>
            </div>
          </article>
        ))}
      </div>
    </section>

    {/* Services */}
    <section id="services" className="py-10">
      <h3 className="text-2xl font-semibold mb-6 text-blue-400">Serviços</h3>
      <ul className="space-y-3 text-gray-300">
        <li>🎨 Artes Digitais criativas e personalizadas</li>
        <li>📢 Flyers digitais para eventos e negócios</li>
        <li>📱 Posts otimizados para redes sociais</li>
        <li>🖌️ Identidade visual básica (logo + paleta de cores)</li>
      </ul>
    </section>

    {/* About */}
    <section id="about" className="py-10">
      <h3 className="text-2xl font-semibold mb-6 text-blue-400">Sobre</h3>
      <div className="bg-gray-800 p-6 rounded-2xl shadow-sm">
        <p className="text-gray-300">
          O <strong>PL Studio</strong> é especializado em artes digitais criativas, conectando estética e estratégia para potencializar a marca de cada cliente.
        </p>
      </div>
    </section>

    {/* Contact */}
    <section id="contact" className="py-10">
      <h3 className="text-2xl font-semibold mb-6 text-blue-400">Contato</h3>
      <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div className="bg-gray-800 p-6 rounded-2xl shadow-sm">
          <p className="text-gray-300">Entre em contato para solicitar orçamentos ou parcerias:</p>
          <ul className="mt-4 text-sm text-gray-400 space-y-2">
            <li>
              📧 Email: <a href={`mailto:${CONTACT.email}`} className="hover:underline">{CONTACT.email}</a>
            </li>
            <li>
              📱 WhatsApp: <a href={CONTACT.whatsapp} target="_blank" rel="noopener noreferrer" className="hover:underline">Clique aqui</a>
            </li>
            <li>
              📷 Instagram: <a href={CONTACT.instagram} target="_blank" rel="noopener noreferrer" className="hover:underline">@pl.studio_design</a>
            </li>
          </ul>
        </div>
      </div>
    </section>

    <footer className="py-12 text-center text-sm text-gray-500">
      <p>© {new Date().getFullYear()} {NAME} — Criando conexões com design.</p>
    </footer>
  </main>
</div>

); }

