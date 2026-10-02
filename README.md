# ☁️ OpenStack Second Brain: IA Aplicada ao Estudo de Computação em Nuvem

> Projeto desenvolvido como parte do Desafio de Projeto **"Entendendo uma IA de Aprendizagem: Explore o Poder do NotebookLM"** pela [DIO (Digital Innovation One)](https://dio.me), integrado aos estudos da disciplina de **Computação em Nuvem** do curso de **Desenvolvimento de Sistemas Multiplataforma (DSM)**.

---

## 🎯 Objetivo do Projeto

> **"Sintetizar a arquitetura e o papel operacional do OpenStack Horizon frente a outros provedores de nuvem, estruturando uma análise crítica para uma apresentação de 20 minutos sobre a relevância das interfaces gráficas em ambientes IaaS."**

O foco central é investigar o modo operacional de painéis de controle em nuvem (tomando o **OpenStack Horizon** como referência), analisando se a interface gráfica (GUI) é apenas um recurso de conveniência ou se constitui um elemento arquitetural relevante para governança, segurança, RBAC e abstração de APIs.

---

## 🎓 Contexto Acadêmico e Desafio

Na matéria de Nuvem da faculdade, foi demandada a elaboração de uma apresentação técnica de **20 minutos** com a seguinte pauta:

1. **O papel do dashboard na arquitetura de nuvem:** como o Horizon atua consumindo APIs REST sem reter estado de infraestrutura.
2. **Comparação entre provedores:** como OpenStack, AWS, Azure e GCP implementam essa camada.
3. **Tabela comparativa:** contrastando modelos de operação, abstração e extensibilidade.
4. **Discussão crítica:** até que ponto a GUI é apenas conveniência ou um componente arquitetural vital para a operação e adoção da nuvem.

Para vencer o excesso de informações dispersas e a obsolescência de tutoriais na internet, foi criado um **Segundo Cérebro no Google NotebookLM** para atuar como mentor e sintetizador de conhecimento.

---

## 🧠 Diretriz de Comportamento (Prompt da IA)

Para garantir respostas embasadas e com rigor técnico, o NotebookLM foi configurado com a seguinte diretriz de persona:

```text
Comporte-se como um professor especialista em Nuvens e seus principais provedores públicos.
Entregue conhecimento em OpenStack, AWS, Azure, Oracle Cloud, Google Cloud, entre outros
provedores populares.
Ensine, explique, tire dúvidas, revise conteúdo explicado, prepare simulados etc.
```

---

## 📚 Curadoria de Fontes e Critérios de Seleção

No ecossistema OpenStack, versões desatualizadas ensinam comandos e conceitos já descontinuados. Por isso, a seleção de fontes seguiu um critério rígido de alto sinal técnico e baixo ruído.

### Fontes Selecionadas

- 🌐 [OpenStack Official Portal](https://www.openstack.org/): base institucional e visão geral dos projetos da OpenInfra Foundation.
- 📖 [OpenStack Docs — versão 2025.1 Epoxy](https://docs.openstack.org/2025.1/index.html): documentação técnica oficial da versão estudada em sala de aula.
- 🎥 [Curso Completo de OpenStack](https://www.youtube.com/watch?v=_gWfFEuert8): fonte em vídeo para fundamentação teórica e prática.
- 🎥 [Hands-on OpenStack Horizon](https://www.youtube.com/watch?v=MUQ0Ev5iM30): demonstração direta do funcionamento e da operação do dashboard.

### 🔍 Critério de Descarte

Durante as buscas e sugestões automáticas, foram deliberadamente eliminadas fontes como:

- Artigos colaborativos sem revisão técnica rigorosa, como a Wikipédia genérica.
- Plataformas de compartilhamento de arquivos sem garantia de versão, como o Scribd.
- Blogs não verificados e tutoriais antigos que misturavam comandos descontinuados.

---

## 🚀 Resultados Gerados no NotebookLM

Com as fontes devidamente carregadas e processadas, a IA gerou os seguintes artefatos para a apresentação:

1. **Roteiro estruturado de 20 minutos**
   - Divisão de tempo por bloco temático: Introdução à Arquitetura, O Papel do Horizon, Comparativo de Provedores, Debate Crítico, Conclusão e Q&A.
2. **Proposta de conteúdo para os slides**
   - Tópicos objetivos e direcionamentos visuais para cada slide, garantindo dinamismo e clareza.
3. **Tabela comparativa de dashboards**
   - Contraste entre o OpenStack Horizon — open source, modular, extensível via Django/Python e desacoplado — e os consoles de nuvens públicas, como AWS Management Console, Azure Portal e Google Cloud Console.
4. **Fundamentação para o debate crítico**
   - Argumentos técnicos sobre como o dashboard viabiliza o Self-Service Portal, aplica políticas de Role-Based Access Control (RBAC) via Keystone e democratiza o consumo da nuvem sem anular a filosofia API-first.

---

## 💡 Principais Aprendizados

> "A experiência com o NotebookLM foi surpreendente. Antes da ferramenta, existia uma sensação de estar perdido sobre onde pesquisar e no que focar diante da imensidão do OpenStack. A ferramenta permitiu filtrar o ruído, focar no que era essencial para a matéria e transformou a preparação do trabalho em um processo real e profundo de aprendizado."

- **Pesquisa aumentada:** o NotebookLM foi superior a chats genéricos por responder estritamente ancorado nas fontes confiáveis selecionadas (grounding).
- **Domínio arquitetural:** compreensão de que interfaces em nuvem não são apenas telas visuais, mas clientes de APIs que moldam a experiência operacional e a governança corporativa.

---

## 🔗 Link para visualizar o Notebook

[Visualizar o projeto no NotebookLM](https://notebook.google.com/notebook/5f6d5b04-68f1-4883-a94c-2e9dadeb6a36)

---

## 🛠️ Tecnologias e Ferramentas

- [Google NotebookLM](https://notebook.google.com/): IA para síntese, ancoragem de fontes e geração de roteiro.
- [OpenStack Horizon](https://docs.openstack.org/horizon/latest/): dashboard canônico de IaaS open source.
- **Markdown e GitHub:** documentação e versionamento do projeto.

---

## 👨‍💻 Autor

Desenvolvido por [Thiago Lima de Carvalho Bastos Luiz](https://github.com/thibastos0)

Estudante de Desenvolvimento de Sistemas Multiplataforma

[LinkedIn](https://linkedin.com/in/thibastos0) • [GitHub](https://github.com/thibastos0)
