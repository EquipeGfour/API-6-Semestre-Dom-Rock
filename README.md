# API-6-Semestre-Dom-Rock


## Sumarização Automática de Comentários de Clientes com PLN

**Objetivo:**

O objetivo deste projeto é desenvolver um sistema inovador que utiliza inteligência artificial (IA) em linguagem natural para sumarizar automaticamente grandes volumes de comentários de clientes. O sistema irá gerar resumos concisos e informativos, categorizados por diversos critérios relevantes para análise, como produto, categoria, recomendação, geografia e demografia.

**Funcionalidades:**

* **Sumarização automática:** O sistema utiliza um modelo de IA de última geração para gerar resumos concisos e informativos de cada comentário, capturando os pontos principais e a sentiment geral.
* **Segmentação por critérios:** O sistema permite segmentar os comentários por diversos critérios, como produto, categoria, data, geografia, demografia e outros, facilitando a análise direcionada e a identificação de padrões específicos.
* **Visualização intuitiva:** Os resultados da análise são apresentados em dashboards interativos e intuitivos, com gráficos, tabelas e filtros que facilitam a compreensão e a visualização dos dados.
* **Exportação de dados:** O sistema permite exportar os resultados para diferentes formatos, como PDF, CSV e outros, para compartilhamento e análise posterior.

**Benefícios:**

* **Agilidade na análise de dados:** O sistema automatiza a sumarização dos comentários, reduzindo significativamente o tempo e o esforço manual necessário para analisar grandes volumes de dados.
* **Melhoria na tomada de decisões:** A análise de sentiment e a segmentação por critérios fornecem insights valiosos que auxiliam na tomada de decisões estratégicas e na identificação de áreas de melhoria.
* **Maior compreensão dos clientes:** O sistema ajuda a entender melhor as necessidades, expectativas e percepções dos clientes, possibilitando a criação de produtos e serviços mais relevantes e personalizados.
* **Aumento da produtividade:** A automatização da sumarização libera tempo para que as equipes se concentrem em tarefas mais estratégicas e de alto valor.

**Aplicações:**

Este sistema inovador pode ser aplicado em diversos setores para analisar feedback de clientes, como:

* **E-commerce:** Avaliar a satisfação com produtos, identificar pontos de melhoria e otimizar a experiência do cliente.
* **Atendimento ao cliente:** Agilizar a resolução de problemas, identificar áreas de aprimoramento e oferecer um atendimento mais personalizado.
* **Pesquisa de mercado:** Coletar insights sobre tendências, preferências do público e oportunidades de mercado.
* **Desenvolvimento de produtos:** Obter feedback sobre novos produtos, identificar necessidades dos clientes e aprimorar o processo de desenvolvimento.

**Conclusão:**

O sistema de sumarização automática de comentários de clientes com IA é uma ferramenta poderosa que oferece diversos benefícios para empresas que buscam aprimorar a análise de feedback, tomar decisões mais assertivas e oferecer uma experiência superior aos seus clientes.

**Repositórios Do Projeto:**

* Repositório Front-End: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-Front-end
* Repositório Back-End: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-Back-end
* Repositório PLN: https://github.com/EquipeGfour/API-6Semestre-Dom-Rock-PLN


<h2> 🎓 Equipe GFour</h2>
    

Integrantes da Equipe | Função | Linkedin | Github| 
:--------- | :-------: | :-------: | :-------: |
Natália Bessa de Moura | Dev | [Linkedin](https://www.linkedin.com/in/natalia-bessa-59b671220/) | [Github](https://github.com/lirabessa)|
Rodrigo Ribeiro dos Santos | Dev | [Linkedin](https://www.linkedin.com/in/rodrigo-ribeiro-5008211b8/) | [Github](https://github.com/rodrigoribeiro027)|
Rafael Peressoni Waltrick | PO | [Linkedin](https://www.linkedin.com/in/rafael-p-waltrick-7211b4221) |  [Github](https://github.com/rafawaltrick)|
Nicolas Lima de Holanda Galindo | Dev | [Linkedin](https://www.linkedin.com/in/nicolas-lima-2a75a3220/) | [Github](https://github.com/Nicolas734)|
Kevin Ferreira Mirenda | SM | [Linkedin](https://br.linkedin.com/in/vin%C3%ADcius-barbosa-78111a206?trk) | [Github](https://github.com/KevinFMfatec)
Raniel Francisco Santos de Paula | Dev | [Linkedin](https://www.linkedin.com/in/raniel-santos-204878222/)| [Github](https://github.com/Raniel-Santos)|
Vinícius Andrade Barborsa | Dev | [Linkedin](https://br.linkedin.com/in/kevin-mirenda-a54a64220) | [Github](https://github.com/ViniciusAndBar)

<br>

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
* MySql: Para o banco de dados
* Python: Para a PLN
* Python com o Framework FastAPI: Para o Backend
* JavaScrip com React: Para o Frontend

<br>


<details>
     <summary><h2>Primeira Sprint</h2></summary>

### Entregáveis:
    
* Pré-processamento
* Upload de arquivos
* Tela de visualização do processamento

</details>

<details>
    <summary><h2>Segunda Sprint</h2></summary>

### Entregáveis:

* O Processo de agrupamento
* A Revisão
* Melhorias no Banco de Dados
* Melhorias na Dashboard

#### Burndown:

<img src="https://media.discordapp.net/attachments/962838523302535198/1236783833538625576/image.png?ex=66394434&is=6637f2b4&hm=00087bc1620b36339dbc366c95b4a56f083584d906afeb4279001aaf75d26e8a&=&format=webp&quality=lossless"></img>

</details>
