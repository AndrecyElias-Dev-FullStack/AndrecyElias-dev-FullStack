<div align="center">
  <h1 align="center">Olá 👋, Eu sou Andrecy Elias Franco Conceição</h1>
  <h3 align="center">Atualmente Suporte N1</h3>
  <p align="center">
    "Com 30 anos de trajetória no setor de tecnologia, possuo sólida experiência em operação, manutenção e desenvolvimento de sistemas. Minha missão é transformar desafios técnicos em soluções eficientes, focando sempre na resolução de problemas complexos."
  </p>
</div>

<hr>

<p align="left">
  <strong>🔗 GitHub:</strong> <a href="https://github.com/AndrecyElias-Dev-FullStack">AndrecyElias-Dev-FullStack</a><br>
  <strong>🔭 Atualmente:</strong> Trabalho no Grupo Tesoura de Ouro (GTO).<br>
  <strong>📫 E-mail:</strong> <a href="mailto:andrecyeliasfrancoconcecao@gmail.com">andrecyeliasfrancoconcecao@gmail.com</a>
</p>

<hr>

<h2>🛠️ Instruções para Git</h2>

<h3>1. Configurar Credenciais</h3>
<p>Verifique se existem credenciais setadas:</p>
<code>git config --list</code>

<p>Caso precise trocar as credenciais existentes:</p>
<pre>
git config --global --unset-all user.name
git config --global --unset-all user.email
</pre>

<p>Sete suas novas credenciais:</p>
<pre>
git config user.name "seu_nome_de_usuario"
git config user.email "seu_email@seu_email.com"
</pre>

<h3>2. Criar e Enviar Repositório Local</h3>
<pre>
git init
git add .
git commit -m "Mensagem do seu commit."
git remote add origin &lt;url&gt;
git branch -M main
git push -u origin main
</pre>

<h3>3. Atualizar Repositório (Local e Remoto)</h3>
<pre>
git add .
git commit -m "Mensagem do seu commit."
git push
</pre>

<h3>4. Clonar e Sincronizar</h3>
<p>Para baixar em outra máquina:</p>
<code>git clone &lt;url&gt;</code>

<p>Para atualizar seu local com o conteúdo remoto (faça isso antes de começar a codar):</p>
<code>git pull</code>
