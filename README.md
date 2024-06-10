# API-6-Semestre-Dom-Rock

## Sumarização Automática de Comentários de Clientes com PLN

<p align="center">

<br id="topo">
<p align="center">
    <a href="#objetivo">Objetivos</a>  |  
    <a href="#funcionalidades">Funcionalidades</a>  |
    <a href="#benefícios">Benefícios</a>  |
    <a href="#aplicações">Aplicações</a>  | 
    <a href="#conclusão">Conclusão</a>  |
    <a href="#backlog">BackLog</a>  |
    <a href="#repositorio">Repositórios do Projeto</a>  |
    <a href="#equipe">G-Four</a>  |
    <a href="#entregas">Entregas</a>  |
</p>

<span id="objetivo">
<h2> 🎯Objetivo:</h2>

O objetivo deste projeto é desenvolver um sistema inovador que utiliza inteligência artificial (IA) em linguagem natural para sumarizar automaticamente grandes volumes de comentários de clientes. O sistema irá gerar resumos concisos e informativos, categorizados por diversos critérios relevantes para análise, como produto, categoria, recomendação, geografia e demografia.

→ [Voltar ao topo](#topo)

<span id="funcionalidades">
<h2> Funcionalidades:</h2>

* **Sumarização automática:** O sistema utiliza um modelo de IA de última geração para gerar resumos concisos e informativos de cada comentário, capturando os pontos principais e a sentiment geral.
* **Segmentação por critérios:** O sistema permite segmentar os comentários por diversos critérios, como produto, categoria, data, geografia, demografia e outros, facilitando a análise direcionada e a identificação de padrões específicos.
* **Visualização intuitiva:** Os resultados da análise são apresentados em dashboards interativos e intuitivos, com gráficos, tabelas e filtros que facilitam a compreensão e a visualização dos dados.
* **Exportação de dados:** O sistema permite exportar os resultados para diferentes formatos, como PDF, CSV e outros, para compartilhamento e análise posterior.

→ [Voltar ao topo](#topo)

<span id="benefícios">
<h2> Benefícios: </h2>

* **Agilidade na análise de dados:** O sistema automatiza a sumarização dos comentários, reduzindo significativamente o tempo e o esforço manual necessário para analisar grandes volumes de dados.
* **Melhoria na tomada de decisões:** A análise de sentiment e a segmentação por critérios fornecem insights valiosos que auxiliam na tomada de decisões estratégicas e na identificação de áreas de melhoria.
* **Maior compreensão dos clientes:** O sistema ajuda a entender melhor as necessidades, expectativas e percepções dos clientes, possibilitando a criação de produtos e serviços mais relevantes e personalizados.
* **Aumento da produtividade:** A automatização da sumarização libera tempo para que as equipes se concentrem em tarefas mais estratégicas e de alto valor.

→ [Voltar ao topo](#topo)

<span id="aplicações">
<h2> Aplicações: </h2>

Este sistema inovador pode ser aplicado em diversos setores para analisar feedback de clientes, como:

* **E-commerce:** Avaliar a satisfação com produtos, identificar pontos de melhoria e otimizar a experiência do cliente.
* **Atendimento ao cliente:** Agilizar a resolução de problemas, identificar áreas de aprimoramento e oferecer um atendimento mais personalizado.
* **Pesquisa de mercado:** Coletar insights sobre tendências, preferências do público e oportunidades de mercado.
* **Desenvolvimento de produtos:** Obter feedback sobre novos produtos, identificar necessidades dos clientes e aprimorar o processo de desenvolvimento.

→ [Voltar ao topo](#topo)

<span id="conclusão">
<h2> Conclusão: </h2>

O sistema de sumarização automática de comentários de clientes com IA é uma ferramenta poderosa que oferece diversos benefícios para empresas que buscam aprimorar a análise de feedback, tomar decisões mais assertivas e oferecer uma experiência superior aos seus clientes.

→ [Voltar ao topo](#topo)

<span id="backlog">
<h2> Backlog: </h2>

**Introdução:**

Este documento descreve o backlog de tarefas para o desenvolvimento do API com a Empresa Dom Rock. O backlog é organizado por área de trabalho (Frontend, Backend e PLN) e priorizado por nível de importância (Alta, Média e Baixa).

**Gestão de Projeto:**

***Todo o controle das tarefas e o andamento das atividades é feito através da ferramenta JIRA.***

**Frontend:**

* **Criar tela de login/cadastro de usuários:**
    * Implementar formulários para criação de novas contas e autenticação de usuários existentes.
    * Validar entradas de dados e fornecer feedback ao usuário.
    * Integrar com o sistema de autenticação do backend.
* **Implementar funcionalidade de upload de arquivo:**
    * Permitir que os usuários carreguem arquivos de texto para sumarização.
    * Suporte para diferentes formatos de arquivo (por exemplo, .txt, .pdf, .docx).
    * Indicar o status do upload e fornecer feedback ao usuário.
* **Criar barra de progresso e indicador de tempo restante:**
    * Visualizar o progresso do processamento de sumarização em tempo real.
    * Estimar o tempo restante para a conclusão do processo.
* **Desenvolver dashboard com visualizações dos sumários:**
    * Apresentar os sumários gerados de forma organizada e intuitiva.
    * Permitir que os usuários filtrem e explorem os sumários por diferentes critérios.
    * Oferecer opções para baixar os sumários em diferentes formatos.
* **Implementar filtros e opções de download:**
    * Permitir que os usuários filtrem os sumários por produto, categoria, data e outros critérios.
    * Oferecer opções para baixar os sumários em formato PDF, CSV ou outros formatos desejados.

**Backend:**

* **Definir estrutura da API REST e documentá-la:**
    * Projetar uma API REST robusta e fácil de usar para interação com o sistema.
    * Documentar a API de forma clara e concisa, incluindo endpoints, métodos HTTP, parâmetros e respostas.
* **Implementar endpoints para upload, processamento e consulta de resultados:**
    * Criar endpoints para upload de arquivos, processamento de sumarização e consulta de resultados.
    * Validar requisições e retornar respostas adequadas em formato JSON.
    * Tratar erros e fornecer mensagens informativas ao usuário.
* **Integrar modelo PLN de sumarização:**
    * Integrar o modelo de sumarização PLN com o backend para processar os arquivos enviados pelos usuários.
    * Chamar o modelo PLN de forma assíncrona para otimizar o desempenho.
    * Armazenar os resultados da sumarização no banco de dados.
* **Armazenar dados e resultados em banco de dados:**
    * Criar um banco de dados para armazenar informações sobre usuários, arquivos, resultados de sumarização e outros dados relevantes.
    * Implementar consultas eficientes para recuperar e gerenciar os dados armazenados.
    * Garantir a segurança e integridade dos dados.
* **Implementar sistema de autenticação de usuários:**
    * Implementar um sistema de autenticação seguro para proteger o acesso ao sistema.
    * Permitir que os usuários criem contas, autentiquem-se e gerenciem suas informações.
    * Integrar o sistema de autenticação com a API REST.

**PLN:**

* **Coletar e preparar dataset de comentários de clientes:**
    * Reunir um conjunto de dados de comentários de clientes relevantes para o domínio do projeto.
    * Limpar e pré-processar os dados para garantir sua qualidade e adequação para treinamento do modelo.
* **Treinar modelo de sumarização de textos:**
    * Treinar um modelo de sumarização de textos usando o dataset de comentários de clientes preparado.
    * Experimentar diferentes arquiteturas de modelo e técnicas de treinamento para otimizar o desempenho.
    * Avaliar o desempenho do modelo em conjunto de dados de validação.
* **Otimizar modelo para melhor desempenho e qualidade:**
    * Ajustar os hiperparâmetros do modelo para obter o melhor desempenho possível.
    * Experimentar diferentes técnicas de otimização para reduzir o tempo de treinamento e melhorar a precisão.
    * Monitorar o desempenho do modelo em produção e fazer ajustes conforme necessário.
* **Avaliar e ajustar modelo para diferentes tipos de produtos e categorias:**
    * Avaliar o desempenho do modelo em diferentes tipos de produtos e categorias.
    * Ajustar o modelo para lidar com diferentes estilos de escrita e tópicos.
    * Garantir que o modelo seja robusto e generalize bem para diferentes tipos de dados.

**Priorização:**

**Prioridade Alta:**

* Upload de arquivo e processamento assíncrono
* Sumarização por produto e categorias
* Visualização dos sumários no dashboard

**Prioridade Média:**

* Sumarização por recomendação e geografia/demografia
* Filtros e opções de download
* Autenticação de usuários

**Prioridade Baixa:**

* Refinamento do modelo PLN
* Monitoramento do sistema e logs de erros


## Requisitos Funcionais:

### Frontend:

* Autenticação de usuário
* Upload de arquivo de comentários em formato CSV ou TXT
* Acompanhamento do processamento em tempo real com barra de progresso e estimativa de tempo restante
* Dashboard com visualização dos sumários:
* Por produto e categorias
* Por recomendação (positiva, neutra, negativa)
* Por geografia e demografia
* Gráficos e tabelas interativos para melhor análise dos dados
* Filtros para refinar a visualização dos resultados
* Opção de download dos sumários em formato PDF ou CSV

<br>

### Backend:

* API REST documentada para comunicação com o frontend
* Processamento assíncrono dos arquivos de comentários
* Implementação do modelo PLN de sumarização de textos
* Armazenamento dos dados e resultados em banco de dados
* Gerenciamento de usuários e permissões

<br>

### PLN:

* Treinamento de modelo de sumarização de textos com base em dataset específico de comentários de clientes
* Otimização do modelo para melhor desempenho e qualidade dos sumários
* Adaptação do modelo para diferentes tipos de produtos e categorias
* Identificação de entidades e sentimentos nos comentários
* Geração de resumos concisos e informativos

<br>

### Requisitos Não Funcionais:

* Interface web amigável e intuitiva
* Aplicação web responsiva para acesso em diferentes dispositivos
* Segurança da informação com criptografia de dados e autenticação de usuários
* Desempenho eficiente e escalável para lidar com grandes volumes de dados
* Documentação completa da API REST e do código-fonte
* Monitoramento do sistema e logs de erros

<br>

### Tecnologias Utilizadas

* Figma: Para o Mockup
* MySql: Para o Banco de Dados
* Python: Para a PLN
* Python com o Framework FastAPI: Para o Backend
* JavaScrip com React: Para o Frontend

→ [Voltar ao topo](#topo)

<span id="repositorio">
<h2> Repositórios Do Projeto: </h2>

* Repositório Front-End: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-Front-end
* Repositório Back-End: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-Back-end
* Repositório PLN: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-PLN

→ [Voltar ao topo](#topo)

<span id="equipe">
<h2> 🎓 Equipe GFour </h2>
    

Integrantes da Equipe | Função | Linkedin | Github| 
:--------- | :-------: | :-------: | :-------: |
Natália Bessa de Moura | Dev | [Linkedin](https://www.linkedin.com/in/natalia-bessa-59b671220/) | [Github](https://github.com/lirabessa)|
Rodrigo Ribeiro dos Santos | Dev | [Linkedin](https://www.linkedin.com/in/rodrigo-ribeiro-5008211b8/) | [Github](https://github.com/rodrigoribeiro027)|
Rafael Peressoni Waltrick | PO | [Linkedin](https://www.linkedin.com/in/rafael-p-waltrick-7211b4221) |  [Github](https://github.com/rafawaltrick)|
Nicolas Lima de Holanda Galindo | Dev | [Linkedin](https://www.linkedin.com/in/nicolas-lima-2a75a3220/) | [Github](https://github.com/Nicolas734)|
Kevin Ferreira Mirenda | SM | [Linkedin](https://br.linkedin.com/in/vin%C3%ADcius-barbosa-78111a206?trk) | [Github](https://github.com/KevinFMfatec)
Raniel Francisco Santos de Paula | Dev | [Linkedin](https://www.linkedin.com/in/raniel-santos-204878222/)| [Github](https://github.com/Raniel-Santos)|
Vinícius Andrade Barborsa | Dev | [Linkedin](https://br.linkedin.com/in/kevin-mirenda-a54a64220) | [Github](https://github.com/ViniciusAndBar)

→ [Voltar ao topo](#topo)

<span id="entregas">
<h2> 🎯 Entregas </h2>

Sprint ID | Data | Tag | Status
----------|------|-----|--------
#0 | 04/03 - 08/03 | Kick - Off | :stopwatch: |
#1 | 25/03 - 14/04 |[Sprint 1](https://github.com/EquipeGfour/API-6-Semestre-Dom-Rock/releases/tag/Sprint_1)|✅ Concluída|
#2 | 14/04 - 05/05 |[Sprint 2](https://github.com/EquipeGfour/API-6-Semestre-Dom-Rock/releases/tag/Sprint_2) |✅ Concluída|
#3 | 06/05 - 26/05 |[Sprint 3](https://github.com/EquipeGfour/API-6-Semestre-Dom-Rock/releases/tag/Sprint_3)|✅ Concluída| 
#4 | 27/05 - 16/06 |[Sprint 4](https://github.com/EquipeGfour/API-6-Semestre-Dom-Rock/releases/tag/Sprint_4)|Em Andamento| 
#5 | 27/06 | Feira de Soluções | :trophy: |
<br>

→ [Voltar ao topo](#topo)
