<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Projetos da Faculdade — Caroline</title>
  <style>
    /* Minimalista e neutro */
    :root {
      --text: #111;
      --muted: #6b7280;
      --accent: #111;
      --maxw: 760px;
      --pad: 28px;
      --gap: 20px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%}
    body{
      color:var(--text);
      margin:0;
      display:flex;
      align-items:flex-start;
      justify-content:center;
      background:#fff;
      line-height:1.5;
      -webkit-font-smoothing:antialiased;
      padding:40px 18px;
    }
    .wrap{
      max-width:var(--maxw);
      width:100%;
      padding:var(--pad);
    }
    h1{
      margin:0 0 6px 0;
      font-weight:600;
      letter-spacing: -0.2px;
      font-size:20px;
    }
    p.lead{
      margin:0 0 18px 0;
      color:var(--muted);
      font-size:13.5px;
    }
    hr{border:0;border-top:1px solid #eee;margin:20px 0}
    .period{margin-bottom:18px}
    .discipline{margin:8px 0}
    .title{font-weight:600;font-size:14px;margin:0}
    .desc{margin:6px 0;color:var(--muted);font-size:13px}
    .link{font-size:13px;color:var(--accent);text-decoration:none;border-bottom:1px solid rgba(0,0,0,0.04);padding-bottom:2px}
    .footer{margin-top:28px;color:var(--muted);font-size:13px}
    @media (prefers-color-scheme:dark){
      :root{--text:#e6eef8;--muted:#9aa6b2;background:#0b0f12}
      body{background: #041018}
      hr{border-top:1px solid rgba(255,255,255,0.04)}
    }
  </style>
</head>
<body>
  <div class="wrap" role="main">
    <header>
      <h1>Projetos da Faculdade</h1>
      <p class="lead">Minha jornada no curso de <strong>Sistemas de Informação</strong>. Projetos organizados por período — direto e minimalista.</p>
    </header>

    <hr />

    <section class="period">
      <div class="discipline">
        <p class="title">2º Período — Laboratório de Programação II</p>
        <p class="desc">Exercícios e desafios em Python.</p>
        <a class="link" href="https://github.com/caroline/python-lab2" target="_blank" rel="noopener">→ Repositório</a>
      </div>
    </section>

    <hr />

    <section class="period">
      <div class="discipline">
        <p class="title">3º Período — Estrutura de Dados</p>
        <p class="desc">Implementações de listas, pilhas, filas, árvores, grafos e recursividade em Java.</p>
        <a class="link" href="https://github.com/caroline/java-estrutura-de-dados" target="_blank" rel="noopener">→ Repositório</a>
      </div>

      <div class="discipline" style="margin-top:12px">
        <p class="title">3º Período — Laboratório de Programação III</p>
        <p class="desc">Aplicação To-Do List (HTML, CSS, JavaScript).</p>
        <a class="link" href="https://github.com/caroline/web-todo-list" target="_blank" rel="noopener">→ Repositório</a>
      </div>
    </section>

    <hr />

    <section class="period">
      <div class="discipline">
        <p class="title">4º Período — Programação Orientada a Objetos</p>
        <p class="desc">Exercícios práticos de herança, polimorfismo e interfaces em Java.</p>
        <a class="link" href="https://github.com/caroline/java-poo-exercicios" target="_blank" rel="noopener">→ Repositório</a>
      </div>
    </section>

    <div class="footer">
      Feito por <strong>Caroline</strong> · em constante aprendizado.
    </div>
  </div>
</body>
</html>
