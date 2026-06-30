# Workshop: DevSecOps com SDLC - Lab 02

Bem-vindo ao laboratório prático de DevSecOps! 🚀

Este repositório foi criado para demonstrar a importância da segurança automatizada no Ciclo de Vida de Desenvolvimento de Software (SDLC), focando em SCA (Software Composition Analysis) usando ferramentas nativas.

🎯 Objetivo do Lab
Identificar e corrigir vulnerabilidades em dependências de terceiros utilizando o GitHub Dependabot.

🛠 Pré-requisitos
Conta no GitHub com MFA ativado.

📝 Passo a Passo
Fork: Faça um fork deste repositório para sua conta pessoal.

Configuração: Acesse Settings > Code security and analysis e habilite o Dependabot (alerts, security updates e malware alerts).

Ativação: Certifique-se de que o arquivo .github/dependabot.yml existe na raiz do projeto.

Scan: Aguarde o GitHub analisar as dependências vulneráveis e disparar os alertas na aba Security.

Fix: Analise os Pull Requests automáticos gerados pelo Dependabot para corrigir as vulnerabilidades.

Merge: Revise as alterações e aceite os PRs para atualizar seu projeto para versões seguras.

⚠️ Aviso
Este repositório contém dependências propositalmente vulneráveis para fins educacionais. Não utilize este código em produção!

Workshop ministrado por: [Fernando Anunciacao]
Linkedin: fernando-anunciacao-3415b5241
