# TI Eficaz: OMPI Fast-Track 🏭💻

> Solução Web Intranet para Gestão de Chamados de TI de Baixa Complexidade.

![Status do Projeto](https://img.shields.io/badge/Status-Protótipo%20Funcional-green)
![License](https://img.shields.io/badge/License-Apache%202.0-blue)
![Stack](https://img.shields.io/badge/Stack-HTML5%20|%20CSS3%20|%20JS-orange)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC), em resposta a uma demanda real da **OMPI do Brasil** através do SENAI.

O objetivo é otimizar o fluxo de chamados internos de TI de baixa complexidade (troca de toner, acesso à internet, reset de senhas), que anteriormente não possuíam controle métrico, gerando gargalos na alocação da equipe técnica.

A solução é um sistema **Web Lightweight** que opera sem necessidade de aquisição de novas licenças de software, focada na usabilidade em ambiente fabril (chão de fábrica).

## 🚀 Funcionalidades Principais

* **Interface do Solicitante:** Design simplificado com "Acesso Rápido" para operadores não técnicos.
* **Dashboard Kanban:** Gestão visual para a equipe de TI (Pendente, Em Andamento, Concluído).
* **Métricas de Tempo:** Registro automático de timestamps para cálculo de SLA e KPIs de atendimento.
* **Zero Deploy:** Funciona diretamente no navegador, compatível com a infraestrutura legada da planta.
* **Responsividade:** Interface adaptável para desktops, tablets industriais e smartphones.

## 🛠 Tecnologias Utilizadas

O projeto segue a arquitetura **Vanilla Web** para garantir leveza e facilidade de manutenção interna:

* **Frontend:** HTML5 (Semântico), CSS3 (Flexbox/Grid/Variaveis).
* **Lógica:** JavaScript (ES6+).
* **Persistência (Protótipo):** LocalStorage (Simulando Banco de Dados SQL).
* **Persistência (Produção):** SQL Server / MySQL (Arquitetura proposta).

## 📂 Estrutura do Projeto
├── index.html # Tela de Login ├── abertura.html # Tela de Abertura de Chamados (Usuário) ├── dashboard.html # Painel de Gestão Kanban (TI) ├── style.css # Folhas de estilo (Tema Industrial) ├── script.js # Lógica de negócio e manipulação do DOM ├── LICENSE # Licença Apache 2.0 └── README.md # Documentação
## 🏁 Como Executar

Como este é um protótipo *client-side* desenvolvido para demonstração imediata:

1.  Clone este repositório ou baixe os arquivos.
2.  Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox).
3.  **Para testar o Admin (TI):** Use o usuário `admin` e qualquer senha.
4.  **Para testar o Usuário (Fábrica):** Use o usuário `fabrica` e qualquer senha.

> **Nota:** Os dados são salvos no *LocalStorage* do seu navegador. Para limpar os dados e reiniciar os testes, utilize o botão "Limpar Dados (Dev)" no Dashboard.

## 🔮 Melhorias Futuras

Para a implantação final na OMPI, o roadmap inclui:

1.  Substituição do `LocalStorage` por uma API REST (Node.js ou PHP).
2.  Conexão com Banco de Dados SQL Relacional para persistência a longo prazo.
3.  Implementação de autenticação via LDAP/Active Directory da empresa.
4.  Geração automática de relatórios em PDF.

## 📄 Licença

Este projeto está licenciado sob a Licença Apache 2.0 - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autores

* ** Maiderson Junio de Souza Oliveira ** - *Desenvolvedor Full Stack*
* ** Lorena Santos Figueredo ** - *Analista de QA*
* ** Raissa Ellen de Moraes ** - * Diretora *
* ** Matheus Henrique Teixeira Munis ** - *Auxiliar de Infraestrutura*
* ** Eric Gonçalves Amaral ** - *Engenheiro Chefe*
* ** Gizele Telheiro dos Santos ** - *Engenheira de Software*
---
*Projeto desenvolvido para o curso de Informática para Internet - SENAI.*
