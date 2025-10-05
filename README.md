<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Prichoa</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
/* Importando fonte */
body {
  font-family: 'Roboto', sans-serif;
  margin: 10;
  padding: 0;
  background: #000000;
  color: #ffffff;
  line-height: 1.6;
}

/* Cabeçalho */
.header {
  text-align: center;
  padding: 4rem 1rem;
  background: linear-gradient(135deg, #1f2937, #133172);
}

.header-content {
  margin-bottom: 1rem;
}

.profile-img {
  width: 320px;
  height: 220px;
  border-radius: 50%;
  border: 7px solid #36a9eb;
  margin-bottom: 1rem;
}

.header h1 {
  font-size: 2rem;
  margin: 0.5rem 0;
}

.header p {
  font-weight: 300;
  color: #9ca3af;
}

/* Navegação */
.nav-links {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 4rem;
  padding: 0;
}

.nav-links a {
  text-decoration: none;
  color: #36a9eb;
  font-weight: 500;
  transition: 0.3s;
}

.nav-links a:hover {
  color: #36a9eb;
}

/* Seções */
.section {
  max-width: 900px;
  margin: 3rem auto;
  padding: 2rem;
  background: #1f2937;
  border-radius: 12px;
  box-shadow: 0px 4px 15px rgba(0,0,0,0.4);
}

.section h2 {
  color: #36a9eb;
  margin-bottom: 1rem;
}

/* Projetos */
.projetos-grid {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.projeto-card {
  background: #161b26;
  padding: 1.5rem;
  border-radius: 12px;
  transition: transform 0.3s;
}

.projeto-card:hover {
  transform: translateY(-5px);
}

.projeto-card h3 {
  margin-top: 0;
  color: #36a9eb;
}

.projeto-card a {
  display: inline-block;
  margin-top: 1rem;
  color: #36a9eb;
  text-decoration: none;
  font-weight: 500;
}

.projeto-card a:hover {
  text-decoration: underline;
}

/* Contato */
.contato-list {
  list-style: none;
  padding: 0;
}

.contato-list li {
  margin: 0.5rem 0;
}

.contato-list a {
  color: #36a9eb;
  text-decoration: none;
}

.contato-list a:hover {
  text-decoration: underline;
}

/* Rodapé */
.footer {
  text-align: center;
  padding: 1.5rem;
  background: #111827;
  color: #9ca3af;
  font-size: 0.9rem;
}

  </body>
<header class="header">
    <div class="header-content">
      <img src="./Assets/Img/MinhaFoto.jpg" alt="Minha Foto" class="profile-img">
      <h1>Kelvyn Pimentel Prichoa</h1>
      <p>Estudante de Programação| Dedicado ao conhecimento e a tecnologia</p>
    </div>
    <nav>
      <ul class="nav-links">
        <li><a href="#sobre">Sobre Mim</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <!-- Sobre Mim -->
  <section id="sobre" class="section">
    <h2>Sobre Mim</h2>
    <p>
      Sou kelvyn Pimentel Prichoa, sou apaixonado por games,e criar interfaces, responsivas, funcionais e radicais, sou estudante de programação,sou carismático e mantenho o bom humor, trabalho tanto em grupo quanto individualmente, atualmente estou no 2º trimestre do curso técnico em informática no Colégio Ulbra São lucas, e estou sempre buscando aprender mais conhecimento sobre tecnologias. 
      Tenho experiência em Lógica de Prigramação, HTML, CSS, e Computação Gráfica, sempre buscando melhorar minhas habilidades e entregar projetos de alto impacto.
    </p>
  </section>

  <!-- Projetos -->
  <section id="projetos" class="section">
    <h2>Meus Projetos</h2>
    <div class="projetos-grid">
      <div class="projeto-card">
        <h3>Projeto dos Signos</h3>
        <p>No projeto eu fui contratado para desenvolver um sistema para uma empresa chamada "Sei de Tudo", que oferece consultoria de Zodíaco. O programa que eles pediram deveria solicitar as seguintes informações do usuário: Nome, sexo, dia, mês e ano de nascimento. Com base nesses dados, pediram para mim fazer um programa que calculasse a idade do usuário, identificaria o signo correspondente, e apresentaria as informações personalizadas, como o número da classificação e a cor da classificação. </p>
        <a href="https://github.com/prichoa7/TrabalhoDosSignos" target="_blank">Ver Projetoa</a>

      </div>
      <div class="projeto-card">
        <h3>Projeto Emoções</h3>
        <p>Este era um Projeto em grupo de 4 pessoas que precisavamos fazer um artigo dentro do contexto de um projeto técnico, tecnológico ou educacional e atrair tanto o publico infantil,jovem e adulto para fazerem testes em nossos sites.</p>
        <a href="https://github.com/2009Lucas/ProjetoEmocao" target="_blank">Ver Projeto</a>
      </div>
      <div class="projeto-card">
        <h3>Projeto Designes</h3>
        <p>Um projeto de pura tranquilidade com treinos de traçados em imagens jpg e svg.</p>
        <a href="https://drive.google.com/drive/folders/172K4-0e1JAHBq8V4MBNZCbR58LVRhbFH?usp=drive_link" target="_blank">Ver Projeto</a>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="section">
    <h2>Contato</h2>
    <p>Entre em contato comigo através do:</p>
    <ul class="contato-list">
      <li>Email: <a href="mailto:kelvynprichoa@gmail.com">kelvynprichoa@gmail.com</a></li>
      <li>Whatsapp: (54) 99977-1092</li>
      <li>GitHub: <a href="https://github.com/prichoa7" target="_blank">https://github.com/prichoa7</a></li>
    </ul>
  </section>

  <!-- Rodapé -->
  <footer class="footer">
    <p>&copy; 2025 - Meu Portifólio - Kelvyn Pimentel Prichoa</p>
  </footer>
</body>
</html>




