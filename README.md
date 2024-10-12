# **BiblioAngelis**

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
[![Licença MPL 2.0](https://img.shields.io/github/license/LuizLourenco/BiblioAngelis)](./LICENSE)


## **Descrição**

**BiblioAngelis** é um sistema gerenciador de bibliotecas, desenvolvido para instituições e casas espíritas no Brasil. Nosso objetivo é criar uma aplicação web multiplataforma, simples e eficiente, mesmo em computadores com poucos recursos. Idealizado por Luiz Lourenço, o projeto está em fase de planejamento e busca colaboradores para transformar essa ideia em uma ferramenta poderosa para o movimento espírita brasileiro.


### **Funcionalidades principais**:
- 📚 **Gerenciamento de Acervos**: Cadastro e controle de livros, incluindo autores convencionais e autores espirituais.
- 👥 **Cadastro de Usuários e Leitores**: Gestão de usuários do sistema e leitores vinculados a atividades.
- 📊 **Relatórios**: Geração de relatórios de atividades, acervos, empréstimos e usuários.
- 🔗 **Cadastro de Atividades**: Controle de atividades às quais os leitores estão vinculados.



## **Estado atual do projeto**

O projeto BiblioAngelis encontra-se na fase de planejamento, onde estamos focados na definição de requisitos e na modelagem do sistema. Embora ainda não haja código implementado, este é um momento crucial para alinhar os objetivos do software e mapear todas as funcionalidades essenciais. Buscamos a colaboração de desenvolvedores Java com experiência em Spring Boot e de especialistas em engenharia de requisitos para dar início ao desenvolvimento. A contribuição de profissionais para modelagem UML e SQL também será fundamental para estruturarmos o sistema de maneira eficaz.

## Cronograma de Desenvolvimento


## Fase 1: Planejamento e Requisitos
**Duração:** 1 a 2 semanas

### Tarefas:
- Definição dos objetivos do software e levantamento de requisitos.
- Identificação de stakeholders e mapeamento das funcionalidades principais.
- Modelagem UML inicial (diagramas de casos de uso, diagramas de classe, etc.).
- Escolha da arquitetura (Monolítica, Microservices) e tecnologias (Spring Boot, PostgreSQL, etc.).
- Definição dos ambientes de desenvolvimento, homologação e produção.

### Entregáveis:
- Documento de requisitos.
- Roadmap do projeto.

---

## Fase 2: Configuração do Ambiente de Desenvolvimento
**Duração:** 1 semana

### Tarefas:
- Configuração do IDE (IntelliJ, Eclipse, VSCode).
- Configuração do controle de versão (Git, GitHub).
- Criação do projeto Spring Boot inicial usando o **Spring Initializr**.
- Configuração do banco de dados (ex: PostgreSQL) e dependências no arquivo `pom.xml`.

### Entregáveis:
- Repositório Git configurado e projeto inicial criado.
- Conexão ao banco de dados estabelecida.

---

## Fase 3: Desenvolvimento Backend - Primeira Iteração
**Duração:** 4 a 6 semanas

### Tarefas:
- Implementação dos modelos de domínio.
- Criação de repositórios, serviços e controladores REST.
- Implementação do CRUD básico para entidades principais.
- Configuração de segurança básica (ex: Spring Security).
- Testes unitários com **JUnit** e integração contínua (CI).

### Entregáveis:
- API funcional com CRUD básico.
- Testes unitários escritos e validados.

---

## Fase 4: Desenvolvimento Frontend
**Duração:** 3 a 4 semanas

### Tarefas:
- Integração com frameworks frontend (Angular, React, Thymeleaf, ou outros).
- Implementação de interfaces gráficas de acordo com os requisitos.
- Integração com a API REST (consumindo endpoints criados no backend).
- Criação de testes de interface e automação de testes se necessário.

### Entregáveis:
- Interface do usuário completa para as funcionalidades principais.
- Integração frontend-backend funcionando.

---

## Fase 5: Integração e Testes
**Duração:** 2 a 3 semanas

### Tarefas:
- Integração entre todas as partes (frontend, backend, banco de dados).
- Testes de integração (backend e banco de dados).
- Testes de aceitação com base nos casos de uso definidos.
- Identificação e correção de bugs.

### Entregáveis:
- Sistema integrado e testado.
- Correções de bugs aplicadas.

---

## Fase 6: Homologação
**Duração:** 1 a 2 semanas

### Tarefas:
- Implementação do sistema em ambiente de homologação.
- Validação pelos stakeholders (clientes, equipe de QA).
- Testes de carga e desempenho.
- Feedback final para ajustes e correções.

### Entregáveis:
- Versão homologada e aprovada.

---

## Fase 7: Preparação para Produção
**Duração:** 1 semana

### Tarefas:
- Otimização do sistema (performance, segurança).
- Configuração de logs e monitoramento.
- Definição do pipeline de CI/CD (ex: Jenkins, GitLab CI).
- Criação de scripts de deploy e configuração do ambiente de produção (AWS, Azure, Heroku, etc.).

### Entregáveis:
- Ambiente de produção configurado.
- Scripts e pipelines prontos para deploy.

---

## Fase 8: Deploy para Produção
**Duração:** 1 a 2 dias

### Tarefas:
- Deploy da aplicação no ambiente de produção.
- Verificação das funcionalidades em produção.
- Monitoramento de possíveis erros.
- Ajustes emergenciais, se necessário.

### Entregáveis:
- Aplicação em produção.
- Monitoramento ativo.

---

## Fase 9: Manutenção e Suporte Pós-Deploy
**Duração:** Contínua

### Tarefas:
- Monitoramento do sistema (logs, métricas, alertas).
- Correção de bugs emergentes.
- Implementação de novas funcionalidades conforme feedback dos usuários.

### Entregáveis:
- Relatórios de desempenho e feedback do usuário.
- Atualizações e correções implementadas conforme necessidade.



## **Como Participar**

Se você tem interesse em contribuir para este projeto colaborativo, estamos procurando pessoas com habilidades em:

- 💻 **Desenvolvimento Java Spring Boot**
- 📐 **Modelagem UML**
- 🗃️ **SQL e banco de dados PostgreSQL**
- 🎨 **Criação de fluxos e mockups**


### Como começar

1. **Faça um fork do repositório**: [BiblioAngelis no GitHub](https://github.com/LuizLourenco/BiblioAngelis)
2. **Clone o repositório para sua máquina local**:
   ```bash
   git clone git@github.com:LuizLourenco/BiblioAngelis.git
