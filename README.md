# 🚀 Projeto 1: Testes Web, Mobile e API — Urban Scooter

## 1. Objetivo do Projeto
O objetivo principal deste projeto foi realizar a garantia de qualidade (QA) de ponta a ponta na plataforma Urban Scooter. O foco centrou-se na validação das regras de negócio do sistema, simulação da experiência do utilizador em diferentes plataformas (Web e Mobile) e garantia da integridade da comunicação dos dados através de testes rigorosos na API de backend.

## 2. Resultado
* **Cenários Cobertos:** Mapeamento completo e execução de testes funcionais, testes de fumaça (Smoke Testing) e testes de regressão nas interfaces Web e Mobile.
* **Gestão de Erros:** Identificação, isolamento e documentação detalhada de bugs críticos na plataforma, com relatórios estruturados enviados para a equipa de desenvolvimento.
* **Validação de API:** Garantia de que todos os endpoints integrados respondiam com os status codes corretos (ex: 200 OK, 201 Created, 400 Bad Request) e que os payloads JSON/XML cumpriam rigorosamente os requisitos do sistema.

## 3. Ferramentas Utilizadas
* **Testes de API & Tráfego:** Postman, Charles Proxy.
* **Ambiente Mobile:** Android Studio Emulator.
* **Gestão & Rastreamento de Bugs:** Jira.
* **Formatos de Dados:** JSON, XML.

## 4. O que Aprendi (Habilidades & Competências Adquiridas)
* Aplicação prática de técnicas de design de testes (Classes de Equivalência e Análise de Valores Limite) para criar casos de teste mais eficientes e robustos.
* Análise detalhada de tráfego de rede e inspeção de logs de sistema para isolar e reportar a origem exata de falhas de software.
* Trabalho estruturado num fluxo ágil com ferramentas de mercado (Jira), mimetizando o dia a dia real de uma equipa de Engenharia de QA.

## 5. Existem Melhorias a Serem Feitas?
Sim. Como próximos passos para este projeto, planeio:
1. **Automação de API:** Converter a coleção de testes manuais do Postman em scripts de testes automatizados utilizando o próprio runner do Postman ou integrando com Newman.
2. **Automação Web:** Desenvolver scripts em Python com Selenium WebDriver para cobrir o fluxo principal de agendamento da Urban Scooter de forma 100% automatizada.

---

### 📋 Extras: Metodologia e Execução
* **Metodologia:** Foi seguido o ciclo de vida tradicional de teste de software (STLC), iniciando pela análise detalhada de requisitos, escrita de casos de teste, execução em ambiente controlado e encerramento com o reporte de defeitos.
* **Como Executar as Validações:** Para verificar a coleção de testes da API, basta importar o arquivo da collection (disponível na pasta `/specs` deste repositório) diretamente no seu Postman e executar o Runner.
