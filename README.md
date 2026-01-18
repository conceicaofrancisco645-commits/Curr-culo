# Curr-culo
Currículo Francisco
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Francisco Conceição da Silva Santos - Currículo</title>
  <meta name="description" content="Currículo online de Francisco Conceição da Silva Santos — Tecnologia e Logística, Produto, Dados, BI e Projetos." />
  <meta name="theme-color" content="#2c3e50" />

  <!-- Ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <style>
    *{ margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }

    body{
      background-color:#f5f5f5;
      color:#333;
      line-height:1.6;
      padding:20px;
      max-width:1000px;
      margin:0 auto;
    }

    .top-actions{
      display:flex;
      gap:10px;
      justify-content:flex-end;
      margin: 0 0 14px 0;
      flex-wrap:wrap;
    }

    .btn{
      cursor:pointer;
      border:0;
      border-radius:10px;
      padding:10px 14px;
      font-weight:600;
      display:inline-flex;
      align-items:center;
      gap:8px;
      box-shadow:0 4px 12px rgba(0,0,0,.08);
      transition: transform .15s ease, opacity .15s ease;
    }
    .btn:hover{ transform: translateY(-1px); opacity:.95; }
    .btn-primary{ background:#2c3e50; color:#fff; }
    .btn-light{ background:#fff; color:#2c3e50; border:1px solid #e6e6e6; }

    .resume-container{
      display:flex;
      background-color:white;
      box-shadow:0 5px 15px rgba(0,0,0,0.1);
      border-radius:12px;
      overflow:hidden;
    }

    .left-column{
      flex:1;
      background-color:#2c3e50;
      color:white;
      padding:30px;
    }

    .right-column{
      flex:2;
      padding:30px;
    }

    .profile{
      display:flex;
      align-items:center;
      gap:14px;
    }

    .avatar{
      width:76px;
      height:76px;
      border-radius:50%;
      background:#1f2a36;
      border:3px solid rgba(255,255,255,.25);
      overflow:hidden;
      display:flex;
      align-items:center;
      justify-content:center;
      flex:0 0 auto;
    }
    .avatar img{
      width:100%;
      height:100%;
      object-fit:cover;
      display:none; /* aparece quando carregar */
    }

    h1{
      font-size:26px;
      margin-bottom:2px;
      color:white;
      line-height:1.15;
    }

    .headline{
      margin-top:6px;
      font-weight:700;
      color:#a8d6ff;
      font-size:14px;
    }

    h2{
      font-size:18px;
      margin-top:22px;
      margin-bottom:12px;
      padding-bottom:8px;
      border-bottom:2px solid #3498db;
      color:#2c3e50;
    }
    .left-column h2{ color:white; }

    h3{
      font-size:16px;
      margin-top:16px;
      margin-bottom:6px;
      color:#2c3e50;
    }
    .left-column h3{ color:#ecf0f1; }

    .job-title{
      font-weight:800;
      color:#3498db;
      font-size:16px;
      margin-bottom:12px;
    }

    .contact-info{ list-style:none; margin-top:14px; }
    .contact-info li{ margin-bottom:10px; display:flex; align-items:center; gap:10px; }
    .contact-info i{ color:#3498db; width:18px; text-align:center; }

    .contact-info a{
      color:white;
      text-decoration:none;
      transition: color .2s ease;
      word-break:break-word;
    }
    .contact-info a:hover{ color:#3498db; text-decoration:underline; }

    .education-item, .experience-item, .certification-item{ margin-bottom:16px; }

    .date{
      font-style:italic;
      font-size:13px;
      margin-top:2px;
      color:#7f8c8d;
    }
    .left-column .date{ color:#bdc3c7; }

    ul{ padding-left:20px; margin-bottom:10px; }
    li{ margin-bottom:5px; }

    .skills-list{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      margin-top:10px;
    }

    .skill-tag{
      background-color:#3498db;
      color:white;
      padding:6px 12px;
      border-radius:999px;
      font-size:13px;
      display:inline-block;
      will-change: transform;
    }

    .summary p{ margin-top:8px; }

    .professional-objective{
      background-color:#f8f9fa;
      padding:14px;
      border-radius:10px;
      margin-top:10px;
      border-left:4px solid #3498db;
    }

    .references{
      margin-top:18px;
      font-style:italic;
      color:#7f8c8d;
    }

    .divider{ height:1px; background:#eaeaea; margin:14px 0; }

    @media (max-width:768px){
      body{ padding:12px; }
      .resume-container{ flex-direction:column; }
      .left-column, .right-column{ padding:20px; }
      .top-actions{ justify-content:stretch; }
      .btn{ flex:1; justify-content:center; }
      .profile{ flex-direction:column; text-align:center; }
      .avatar{ margin-bottom:15px; }
    }

    /* impressão limpa */
    @media print{
      body{ background:#fff; padding:0; max-width:none; }
      .top-actions{ display:none; }
      .resume-container{ box-shadow:none; border-radius:0; }
      .left-column{ -webkit-print-color-adjust:exact; print-color-adjust:exact; }
    }
  </style>
</head>

<body>
  <div class="top-actions" aria-label="Ações">
    <button class="btn btn-light" id="btnShare" type="button">
      <i class="fa-solid fa-share-nodes"></i> Compartilhar
    </button>
    <button class="btn btn-primary" onclick="window.print()" type="button">
      <i class="fa-solid fa-file-pdf"></i> Salvar em PDF
    </button>
  </div>

  <div class="resume-container">
    <!-- COLUNA ESQUERDA -->
    <aside class="left-column">
      <div class="profile">
        <div>
          <h1>FRANCISCO CONCEIÇÃO DA SILVA SANTOS</h1>
          <div class="headline">Tecnologia • Logística • Dados • Produto</div>
        </div>
      </div>

      <h2>Detalhes de Contato</h2>
      <ul class="contact-info">
        <li><i class="fas fa-envelope"></i>
          <a href="mailto:conceicaofrancisco645@gmail.com">conceicaofrancisco645@gmail.com</a>
        </li>
        <li><i class="fas fa-phone"></i> (11) 94006-4366</li>
        <li><i class="fas fa-map-marker-alt"></i> São Paulo - SP</li>
        <li><i class="fab fa-linkedin"></i>
          <a href="https://www.linkedin.com/in/francisco-concei%C3%A7%C3%A3o-da-silva-santos/" target="_blank" rel="noopener">
            LinkedIn
          </a>
        </li>
      </ul>

      <h2>Formação Acadêmica</h2>
      <div class="education-item">
        <h3>Graduação em Análise e Desenvolvimento de Sistemas</h3>
        <p class="date">Em andamento (Previsão: 06/2026)</p>
      </div>
      <div class="education-item">
        <h3>Pós-Graduação em Gestão Tributária</h3>
        <p class="date">Conclusão: 2022</p>
      </div>
      <div class="education-item">
        <h3>Graduação em Tecnologia em Logística</h3>
        <p class="date">Conclusão: 2020</p>
      </div>

      <h2>Competências-Chave</h2>
      <div class="skills-list" aria-label="Competências">
        <span class="skill-tag">Gestão de Produtos Digitais</span>
        <span class="skill-tag">Análise de Dados</span>
        <span class="skill-tag">Business Intelligence</span>
        <span class="skill-tag">Marketing Digital</span>
        <span class="skill-tag">Gestão de Projetos</span>
        <span class="skill-tag">Arquitetura de Software</span>
        <span class="skill-tag">Estratégia e OKRs</span>
      </div>
    </aside>

    <!-- COLUNA DIREITA -->
    <main class="right-column">
      <section class="summary">
        <h2>Resumo Profissional</h2>
        <p>
          Profissional multidisciplinar com forte atuação em Produto, Dados, Marketing, Projetos e Tecnologia.
          Certificado pela Escola DNC em múltiplas trilhas estratégicas, com domínio de metodologias ágeis,
          análise de dados, business intelligence, growth marketing e gestão de produtos digitais.
          Experiência prática em ambientes corporativos, projetos data-driven e melhoria contínua.
        </p>
      </section>

      <section class="professional-objective">
        <h2>Objetivo Profissional</h2>
        <p>
          Atuar em posições estratégicas nas áreas de <strong>Tecnologia e Logística</strong>, integrando
          <strong>análise de dados, automação de processos e sistemas digitais</strong> para otimizar operações,
          reduzir custos e aumentar a eficiência organizacional. Contribuir com <strong>visão sistêmica,
          pensamento analítico e tomada de decisão orientada a dados</strong>, apoiando a evolução tecnológica
          da cadeia logística, gestão de estoques, operações e projetos corporativos de alto impacto.
        </p>
      </section>

      <section>
        <h2>Certificações - Escola DNC (Trilhas Completas)</h2>

        <div class="certification-item">
          <h3>PRODUTO</h3>
          <ul>
            <li>Analista de Produto (APM)</li>
            <li>Product Owner (PO)</li>
            <li>Product Manager (PM)</li>
            <li>Group Product Manager (GPM)</li>
          </ul>
        </div>

        <div class="certification-item">
          <h3>DADOS</h3>
          <ul>
            <li>Analista de Dados</li>
            <li>Analista de BI</li>
            <li>Engenheiro de Dados</li>
            <li>Cientista de Dados</li>
            <li>Gerente de Dados</li>
          </ul>
        </div>

        <div class="certification-item">
          <h3>MARKETING</h3>
          <ul>
            <li>Analista de Marketing</li>
            <li>Analista de Growth Marketing</li>
            <li>Analista de Social Media</li>
            <li>Gestor de Tráfego</li>
            <li>Analista de CRM</li>
            <li>Gerente de Marketing</li>
          </ul>
        </div>

        <div class="certification-item">
          <h3>PROJETOS E PROCESSOS</h3>
          <ul>
            <li>Analista de Projetos</li>
            <li>Especialista de Projetos</li>
            <li>Gerente de Projetos</li>
            <li>Analista de Processos</li>
          </ul>
        </div>

        <div class="certification-item">
          <h3>TECNOLOGIA</h3>
          <ul>
            <li>Desenvolvedor Front-End</li>
            <li>Desenvolvedor Back-End</li>
            <li>Engenheiro de Software</li>
            <li>Tech Lead</li>
            <li>Arquiteto de Software</li>
          </ul>
        </div>

        <div class="certification-item">
          <h3>OUTRAS CERTIFICAÇÕES</h3>
          <ul>
            <li>Power BI Aplicado à Gestão — ENAP (25h)</li>
            <li>Modelagem de Dados no Power BI — Fundação Bradesco (11h)</li>
            <li>Microsoft Power BI Módulo I, II e III — Evolua (16h cada)</li>
            <li>Excel Básico e Intermediário</li>
          </ul>
        </div>
      </section>

      <section>
        <h2>Experiência Profissional</h2>

        <div class="experience-item" id="currentRole">
          <h3>Controlador de Estoque</h3>
          <p class="job-title">SEGULA Technologies Brasil</p>
          <p class="date">09/2025 — Atual</p>
          <ul>
            <li>Controle de estoque e análise de indicadores operacionais</li>
            <li>Suporte à tomada de decisão baseada em dados</li>
          </ul>
        </div>

        <div class="experience-item">
          <h3>Assistente de Expedição</h3>
          <p class="job-title">Agru Tecnologia em Plástico Brasil Ltda</p>
          <p class="date">05/2023 — 09/2025</p>
          <ul>
            <li>Gestão logística, inventário e expedição</li>
          </ul>
        </div>

        <div class="experience-item">
          <h3>Auxiliar Administrativo</h3>
          <p class="job-title">Perfumaria Sumirê</p>
          <p class="date">04/2021 — 04/2023</p>
          <ul>
            <li>Análises administrativas, faturamento e relatórios de notas fiscais</li>
          </ul>
        </div>

        <div class="experience-item">
          <h3>Conferente de Fatura / Fiscal de Loja</h3>
          <p class="job-title">Perfumaria Sumirê</p>
          <p class="date">09/2018 — 02/2021</p>
          <ul>
            <li>Conferência e validação de documentos fiscais</li>
            <li>Funções de fiscalização em ambiente de varejo</li>
          </ul>
        </div>

        <div class="references">
          <p>Referências disponíveis mediante solicitação</p>
        </div>
      </section>
    </main>
  </div>

  <script>
    // Hover suave nas skills + destaque no cargo atual
    document.addEventListener("DOMContentLoaded", () => {
      document.querySelectorAll(".skill-tag").forEach(tag => {
        tag.addEventListener("mouseenter", function(){
          this.style.transform = "scale(1.05)";
          this.style.transition = "transform 0.15s ease";
        });
        tag.addEventListener("mouseleave", function(){
          this.style.transform = "scale(1)";
        });
      });

      const current = document.getElementById("currentRole");
      if(current){
        current.style.backgroundColor = "#f8f9fa";
        current.style.padding = "14px";
        current.style.borderRadius = "10px";
        current.style.borderLeft = "4px solid #2ecc71";
      }

      // Compartilhar (funciona em celular e alguns navegadores)
      const btnShare = document.getElementById("btnShare");
      if(btnShare){
        btnShare.addEventListener("click", async () => {
          const data = {
            title: document.title,
            text: "Meu currículo online",
            url: window.location.href
          };
          try{
            if(navigator.share) await navigator.share(data);
            else alert("Copie o link do navegador para compartilhar.");
          }catch(e){
            // usuário cancelou / navegador não suportou
          }
        });
      }
    });
  </script>
</body>
</html>
