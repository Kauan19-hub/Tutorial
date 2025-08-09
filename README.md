**<h3>🚀 Sobre esse projeto:<h3/>**

###

Este repositório foi criado para aprender e compartilhar conceitos, comandos e boas práticas de uso do Git e GitHub. <br>
Se você está começando ou quer reforçar o conhecimento, aqui vai encontrar passo a passo, dicas e exemplos reais.

###

**<h3>💎 Conteúdo:<h3/>**

###

- O que é Git e GitHub? Possuem diferenças?
- Instalação
- Comandos básicos;
- Trabalho básico;
- Práticas;
- Passo a passo simplificado;
- Subir projetos.

###

**<h3>🧠 O que é Git e GitHub?<h3/>**

###

Git → Sistema de controle de versão para rastrear alterações no código.

GitHub → Plataforma online para hospedar repositórios Git, colaborar em projetos e gerenciar código.

📌 Resumo: Git = ferramenta local | GitHub = nuvem + colaboração.

###

**<h3>💻 Instalação:<h3/>**

###

```Python
    # Instale o Git (Windows, Linux ou Mac)
    https://git-scm.com/downloads

    # Configure seu usuário e email
    git config --global user.name "Seu Nome"
    git config --global user.email "seu@email.com"
```

###

**<h3>🥇 Trabalho básico:<h3/>**

###

```Python
    #Clonar um repositório
    git clone https://github.com/usuario/repositorio.git
    git add .
    git commit -m "Mensagem descritiva"
    git push origin main
```

###

**<h3>🌟 Boas práticas:<h3/>**

###

✅ Use mensagens de commit clarasm, curtas e objetivas;<br>
✅ Mantenha a branch "Main" estável. Pode alterar para "Master", porém, a "Main" é mais recomendada;<br>
✅ Use branches para novas features ou correções;<br>
✅ Faça pull antes de começar novas alterações;<br>
✅ Antes de usar o "git add .", use "git status" para ver se há arquivos em verde (salvos);<br>
✅ Após o "git add .", use "git status" novamente. Você verá que seus arquivos estarão verdes.<br>

###

**<h3>🔗 Links úteis:<h3/>**

###

- [Documentação oficial do Git](https://git-scm.com/doc)  
- [Guia GitHub para iniciantes](https://docs.github.com/pt/get-started)  
- [Markdown Guide](https://www.markdownguide.org/)


###

**<h3>🚀 Como Subir um Projeto no GitHub (Passo a Passo) 🚀<h3/>**

###

**Autor:** Kauan Vinícius  
**GitHub:** [Kauan19-hub](https://github.com/Kauan19-hub)  
**Última atualização:** 07/08/2025  

###

**<h3>📌 Objetivo:<h3/>**

###

Este guia ensina como **subir um projeto local para o GitHub** pela primeira vez, de forma simples, direta e prática.

###

Existem duas formas para realizar esse processo:

###

1. **Usar o Prompt de Comando** *(Avançado)*
2. **Usar o Terminal Git Bash no VSCode** *(Iniciante)*

###

**<h3>🧰 Requisitos<h3/>**

###

✔️ Conta no GitHub → [Criar conta](https://github.com)  
✔️ Git instalado na máquina → [Baixar Git](https://git-scm.com)  
✔️ Terminal (cmd, bash, PowerShell ou Git Bash)  
✔️ Projeto criado localmente (pasta com arquivos)  

###

**<h3>📚 Tutorial Usando Prompt de Comando<h3/>**

###

1️⃣ **Inicialize um repositório local**
```bash
git init
```

###

2️⃣ **Adicione os arquivos para commit**
```bash
git add .
```

###

3️⃣ **Faça o primeiro commit**
```bash
git commit -m "Primeiro Commit"
```

###

4️⃣ **Crie um repositório no GitHub**

###

- Vá até GitHub
<br>
- Clique em ➕ New Repository
<br>
- Escolha um nome (ex: meu-projeto)
<br>
- (Opcional) Adicione descrição, README e .gitignore
<br>
- Clique em Create Repository

###

⚠️ Se você já criou README/.gitignore no GitHub, será necessário clonar ou fazer pull antes de dar push.

###

5️⃣ **Vincule o repositório remoto**

###

Copie o link HTTPS do repositório (ex: https://github.com/seuusuario/meu-projeto.git) e execute:

###
```bash
git remote add origin https://github.com/seuusuario/meu-projeto.git
```

###
```bash
git remote -v
```

###

6️⃣ **Envie os arquivos para o GitHub**

###
```bash
git push -u origin master
```

###
```bash
#Caso estiver usando main
git push -u origin main
```

###

7️⃣ **Confira se deu certo**

###

Abra o repositório no navegador. Se tudo funcionou, os arquivos estarão lá! 🎉

###

📌 **Comandos úteis para o futuro**

###
```bash
# Verificar status
git status

# Histórico de commits
git log

# Subir novas alterações
git add .
git commit -m "Nova atualização"
git push
```

###

**<h3>🖥 Tutorial Usando Terminal Git Bash no VSCode<h3/>**

###

1️⃣ **Adicione os arquivos para commit**

###
```bash
git add .
```

###
```bash
#Arquivo específico
git add index.html style.css
```

###

2️⃣ **Faça um commit com mensagem**

###
```bash
git commit -m "mensagem explicando o que foi feito"
```

###

3️⃣ **Crie um repositório no GitHub**

###

- Acesse: https://github.com
<br>
- Clique no botão + → New repository
<br>
- Escolha um nome para o repositório
<br>
- Não marque README, .gitignore ou License
<br>
- Clique em Create repository

###

4️⃣ **Conecte o repositório local ao GitHub**

###
```bash
git remote add origin https://github.com/seu-usuario/nome-do-repo.git
```

###

5️⃣ **Envie os arquivos para o GitHub**

###
```bash
#Defina a branch
git branch -M main
git branch -M main
```

###

📋 Na primeira vez, o Git pode pedir seu usuário e Token de Acesso Pessoal (PAT)<br>
no lugar da senha. [Gerar token aqui](https://github.com)

###

🎉 **Pronto! Seu projeto está no GitHub!** 🎉

###

Para atualizar futuramente:

###
```bash
git add .
git commit -m "sua mensagem"
git push
```

###

**<h3>📬 Contato<h3>**

###

📧 E-mail: saleskauan308@gmail.com<br>
💼 LinkedIn: Kauan Vinícius<br>
💻 Instagram: @kauanl01<br>

**<h3>👋 Muito obrigado e bons estudos!<h3/>**





















