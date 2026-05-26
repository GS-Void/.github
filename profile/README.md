# 🌌 VOID | Advanced Recovery Lab

> **A tecnologia espacial aplicada ao limite do corpo humano.**

Bem-vindo à organização oficial do projeto **VOID**. Desenvolvido para a Global Solution 2026/1, o VOID é um ecossistema focado na telemetria de micro-esforços para atletas de alto rendimento e pacientes em reabilitação severa (ODS 3 - Saúde e Bem-Estar).

Inspirado nos rigorosos protocolos de monitoramento de atrofia muscular utilizados por astronautas na Estação Espacial Internacional (ISS), trazemos a precisão da microgravidade para a fisioterapia terrestre.

---

## 🏗️ Nossa Arquitetura & Repositórios

O ecossistema VOID é modular, projetado com uma arquitetura coesa e focado em eficiência computacional e de custos. Abaixo estão os repositórios que compõem a nossa solução:

### 📱 [void-mobile-app](link-do-repo)
O painel de controle do fisioterapeuta. Construído em **React Native**, possui uma interface *black-and-grey* cinemática, realista e direta ao ponto. Focado puramente na usabilidade do CRUD de pacientes e no *dashboard* de fadiga muscular, consumindo a nossa API REST.

### ⚙️ [void-api-java](link-do-repo)
O coração da aplicação. Uma API RESTful em **Java (Spring Boot)** estruturada de forma simples, limpa e altamente coesa. Implementa segurança JWT, modelagem avançada (Herança/Chave Composta) e documentação OpenAPI/Swagger.

### 🗄️ [void-database](link-do-repo)
A inteligência de persistência. Repositório contendo a modelagem relacional e os scripts estruturados em **Oracle PL/SQL**. Priorizamos lógicas de programação básicas e diretas — utilizando Blocos Anônimos, `FOR LOOP` e `IF/ELSE` essenciais — para automatizar a trava de segurança de esforço do paciente de forma imediata e sem sobrecarga de funções nativas.

### 📡 [void-iot-telemetry](link-do-repo)
A captação na ponta. Simulação de um *wearable* de monitoramento contínuo via **ESP32**. Lê os dados do sensor EMG simulado (potenciômetro) e aciona o *feedback* local (LED de fadiga/LCD) enquanto sincroniza as métricas via Wi-Fi com o *backend*.

### ☁️ [void-cloud-devops](link-do-repo)
A infraestrutura em nuvem. Configurações e tutoriais de *deploy* utilizando **Docker** (API e Banco conteinerizados na mesma rede). Arquitetura provisionada na Azure com foco absoluto em otimização de recursos e custo-benefício para validação do ambiente.

### 📄 [void-compliance-docs](link-do-repo)
O mapeamento estratégico. Documentação completa da arquitetura (Negócios, Sistemas e Tecnologia) modelada no padrão **TOGAF** utilizando a ferramenta Archimate.

---

## 👨‍🚀 A Equipe - 2TDSPO

Este ecossistema foi idealizado e construído por:

* **Pedro Henrique Luiz Alves Duarte**
* **Guilherme Macedo Martins**
* **Henrique Martins**

*"Transformando dados em superação."*
