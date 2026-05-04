# CePEX - Centro Paulista de integração de dados para monitoramento de Eventos eXtremos

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![AI](https://img.shields.io/badge/IA-Deep%20Learning-purple)
![Platform](https://img.shields.io/badge/Platform-ArcGIS%20%2F%20React-green)

Sistema integrado para monitoramento, análise e visualização de eventos meteorológicos extremos, utilizando múltiplas fontes de dados, arquitetura computacional escalável e técnicas avançadas de Inteligência Artificial para apoio à tomada de decisão.

**Site do Projeto:** https://cepex-sp.github.io/cepex-sp/

---

# Sobre o Projeto

O CePEX está inserido no contexto do **CePEX — Centro Paulista de integração de dados para monitoramento de Eventos eXtremos**, iniciativa financiada pela **FAPESP** em conjunto com a **Defesa Civil do Estado de São Paulo**, voltada ao desenvolvimento de pesquisas integradas sobre monitoramento, previsão e suporte à decisão diante de eventos de desastre no estado de São Paulo.

A proposta busca integrar diferentes fontes de dados meteorológicos, ambientais e operacionais em uma única arquitetura computacional, permitindo armazenamento, recuperação, processamento e visualização espacial das informações de maneira eficiente.

O projeto considera a utilização de:

- Radares meteorológicos distribuídos em regiões estratégicas do estado
- Plataformas de coleta de dados ambientais
- Sensores meteorológicos
- Redes de detecção de raios
- Bases públicas de sensoriamento remoto
- APIs institucionais
- Dados hidrológicos e climáticos
- Sistemas operacionais de apoio à Defesa Civil

A plataforma tem como objetivo centralizar informações críticas relacionadas a:

- Tempestades severas
- Eventos hidrológicos extremos
- Alagamentos
- Deslizamentos
- Ondas de calor
- Ondas de frio
- Incêndios florestais
- Eventos climáticos de risco

---

# Objetivos

O projeto possui como principais objetivos:

- Integrar diferentes fontes de dados em uma arquitetura unificada
- Estruturar processos de ETL para coleta, transformação e disponibilização dos dados
- Organizar dados com diferentes resoluções espaciais e temporais
- Desenvolver modelos preditivos utilizando Inteligência Artificial
- Facilitar análises operacionais por meio de visualizações integradas
- Disponibilizar informações estratégicas para analistas e gestores públicos
- Apoiar ações preventivas e processos de tomada de decisão

---

# Inteligência Artificial e Modelos Analíticos

Após a consolidação da base integrada de dados, o projeto prevê a aplicação de metodologias avançadas de Inteligência Artificial e aprendizado profundo para desenvolvimento de modelos capazes de antecipar cenários críticos.

Entre as abordagens previstas:

- Redes neurais convolucionais (CNN)
- Redes neurais recorrentes (RNN/LSTM)
- Modelos preditivos hidrológicos
- Modelos Fundacionais
- Análise espaço-temporal
- Detecção de padrões meteorológicos
- Classificação e previsão de eventos extremos
- Modelos híbridos físicos e analíticos

Os estudos buscam gerar suporte operacional para identificação antecipada de eventos de risco e mitigação de impactos ambientais e urbanos.

---

# Plataforma de Visualização

O sistema prevê uma plataforma integrada de visualização espacial e análise operacional, permitindo:

- Sobreposição de camadas geográficas
- Visualização de dados meteorológicos em tempo real
- Consulta de informações históricas
- Download de dados específicos
- Monitoramento centralizado
- Integração com mapas e dashboards
- Apoio à operação técnica e tomada de decisão

A plataforma deverá evoluir progressivamente ao longo do projeto, incorporando novas funcionalidades, modelos e fontes de dados.

---

# Fontes de Dados

Fontes previstas e em estudo para integração:

- SEMADEN
- INMET
- SIAGRO
- Defesa Civil
- ENEL
- Sensores e sirenes
- IPMET
- Bases públicas de sensoriamento remoto
- APIs meteorológicas
- Redes de radares meteorológicos

## Bases de dados disponíveis:

- [IPMet Radar Dataset](https://github.com/rafaepires/IPMet-Radar-Dataset/tree/main)

---

# Arquitetura Tecnológica

## Backend e Processamento

- Python
- APIs REST
- ETL de dados
- Processamento assíncrono
- Integração de múltiplas fontes
- Kafka (Ingestão de dados)

## Banco de Dados

- PostgreSQL
- PostGIS
- MySQL

## Visualização e Interface

- ArcGIS
- React
- Dashboards interativos
- Visualização geoespacial

## Inteligência Artificial

- PyTorch
- TensorFlow
- Deep Learning
- Modelos Fundacionais
- Modelos espaço-temporais

---

# Estrutura do Projeto

```text
docs/           Documentação técnica
backend/        APIs e serviços
etl/            Processos de coleta e transformação
frontend/       Interface e dashboards
database/       Estrutura e scripts SQL
models/         Modelos de IA
notebooks/      Estudos e experimentos
assets/         Diagramas, imagens e materiais visuais
```

---

# Roadmap Inicial

- [ ] Levantamento e documentação das fontes de dados
- [ ] Estruturação da arquitetura computacional
- [ ] Desenvolvimento dos processos ETL
- [ ] Integração das APIs meteorológicas
- [ ] Estruturação do banco geoespacial
- [ ] Desenvolvimento do painel inicial
- [ ] Integração com ArcGIS
- [ ] Desenvolvimento dos primeiros modelos preditivos
- [ ] Estudos de visualização espacial
- [ ] Implementação de análises operacionais

---

# Status do Projeto

Projeto em fase de estruturação arquitetural, levantamento técnico das fontes de dados e definição dos processos de integração e análise.

---

# Pesquisadores/Desenvolvedores do projeto

Victor Hugo Santana Felix & Juliana da Costa Feitosa

# Pesquisadores Principais:

- João Paulo Papa (https://bv.fapesp.br/pt/pesquisador/3113/joao-paulo-papa/)
- Rogério Galante Negri (https://bv.fapesp.br/pt/pesquisador/64752/rogerio-galante-negri/)


Projeto voltado a estudos e desenvolvimento em monitoramento meteorológico, integração de dados, inteligência artificial e apoio à gestão de eventos extremos.
