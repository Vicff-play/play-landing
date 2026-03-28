export default function PlayTemporaryLanding() {
  return (
    <main className="min-h-screen bg-white text-zinc-900">
      <section className="mx-auto flex min-h-screen max-w-6xl flex-col items-center justify-center px-6 py-16 text-center">
        <div className="mb-6 inline-flex items-center rounded-full border border-orange-200 bg-orange-50 px-4 py-2 text-sm font-medium text-orange-700">
          Em breve
        </div>

        <div className="mb-8 flex items-center gap-3">
          <div className="flex h-14 w-14 items-center justify-center rounded-2xl bg-orange-500 text-2xl font-bold text-white shadow-lg">
            P
          </div>
          <h1 className="text-4xl font-extrabold tracking-tight sm:text-5xl">Play</h1>
        </div>

        <h2 className="max-w-4xl text-4xl font-extrabold leading-tight sm:text-6xl">
          Conectando <span className="text-orange-500">músicos</span> a eventos de forma simples e segura.
        </h2>

        <p className="mt-6 max-w-2xl text-base leading-7 text-zinc-600 sm:text-lg">
          O Play é a plataforma que aproxima artistas e clientes para contratação de apresentações musicais em festas, casamentos, eventos corporativos, cultos e muito mais.
        </p>

        <div className="mt-10 flex flex-col items-center gap-4 sm:flex-row">
          <a
            href="#contato"
            className="rounded-2xl bg-orange-500 px-6 py-3 text-base font-semibold text-white shadow-lg transition hover:scale-[1.02]"
          >
            Quero saber mais
          </a>
          <a
            href="https://vicff-play.github.io/play-landing/"
            className="rounded-2xl border border-zinc-300 px-6 py-3 text-base font-semibold text-zinc-800 transition hover:bg-zinc-50"
          >
            Ver versão atual
          </a>
        </div>

        <div className="mt-16 grid w-full max-w-4xl gap-4 sm:grid-cols-3">
          <div className="rounded-3xl border border-zinc-200 bg-zinc-50 p-6 text-left shadow-sm">
            <h3 className="text-lg font-bold">Para músicos</h3>
            <p className="mt-2 text-sm leading-6 text-zinc-600">
              Divulgue seu trabalho, receba propostas e conquiste novas oportunidades.
            </p>
          </div>

          <div className="rounded-3xl border border-zinc-200 bg-zinc-50 p-6 text-left shadow-sm">
            <h3 className="text-lg font-bold">Para clientes</h3>
            <p className="mt-2 text-sm leading-6 text-zinc-600">
              Encontre músicos para o seu evento com mais praticidade, organização e confiança.
            </p>
          </div>

          <div className="rounded-3xl border border-zinc-200 bg-zinc-50 p-6 text-left shadow-sm">
            <h3 className="text-lg font-bold">Contratação segura</h3>
            <p className="mt-2 text-sm leading-6 text-zinc-600">
              Acompanhe propostas, confirmações e pagamentos em um só lugar.
            </p>
          </div>
        </div>

        <section id="contato" className="mt-16 w-full max-w-3xl rounded-[2rem] bg-zinc-900 px-8 py-10 text-white shadow-xl">
          <h3 className="text-2xl font-bold sm:text-3xl">Estamos preparando algo incrível</h3>
          <p className="mt-3 text-sm leading-6 text-zinc-300 sm:text-base">
            Em breve, o Play estará disponível para transformar a forma como músicos e clientes se conectam.
          </p>

          <div className="mt-6 rounded-2xl bg-white/10 px-4 py-4 text-sm text-zinc-200">
            Contato provisório: <span className="font-semibold text-white">play.app.contato@gmail.com</span>
          </div>
        </section>
      </section>
    </main>
  );
}
