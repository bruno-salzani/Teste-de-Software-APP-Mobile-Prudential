# 📱 Projeto de QA Mobile — Prudential LMS

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Plataforma](https://img.shields.io/badge/Plataforma-iOS%20%7C%20Android-lightgrey)
![Duração](https://img.shields.io/badge/Duração-2%20Anos-blue)
![Função](https://img.shields.io/badge/Função-Analista%20de%20QA-orange)

Este repositório documenta minha atuação como **Analista de Testes (QA)** na validação do aplicativo Prudential LMS, uma plataforma educacional corporativa disponível para **iOS (iPhone/iPad)** e **Android**.

Entre 2021 e 2023, fui responsável por garantir qualidade ponta a ponta, cobrindo validação funcional, experiência do usuário, sincronização entre dispositivos, estabilidade e mitigação de riscos em produção.

---

# 🎯 Objetivo do Projeto

Garantir a integridade completa da jornada do usuário:

Login → Consumo de Conteúdo → Interação Multimídia → Sincronização → Conclusão de Cursos

## Foco Principal

- Conformidade com requisitos de negócio  
- Experiência fluida e intuitiva  
- Validação visual Pixel Perfect  
- Estabilidade em múltiplos dispositivos  
- Prevenção de regressões  
- Previsibilidade de releases  

---

# 🛠️ Ferramentas & Stack

## 📌 Gestão e Processo

- Jira (workflow ágil com controle de severidade)
- Participação ativa em refinamentos, planning e reviews
- Definição formal de critério Go/No-Go para releases
- Abordagem orientada a risco

## 📄 Documentação

- Excel (RTM — Matriz de Rastreabilidade de Requisitos)
- Casos de teste estruturados por prioridade
- Checklist de regressão mobile
- Relatórios de validação por sprint

## 🎨 Validação de Interface

- Figma (validação de fidelidade visual e consistência de UI)
- Comparação Pixel Perfect

## 📱 Testes em Dispositivos Físicos

### iOS
- iPhone (múltiplas versões de iOS)
- iPad (validação de responsividade)

### Android
- Diferentes fabricantes
- Múltiplos tamanhos de tela e densidades
- Testes focados em fragmentação

---

# 🧠 Estratégia de Testes

## 🔁 Estrutura de Regressão

- **Smoke Test:** Fluxos críticos (login, acesso a curso, player, sincronização)
- **Regressão Completa:** Executada ao final de cada sprint
- **Validação Cross-Platform:** Comparação de comportamento entre iOS e Android
- **Regressão Orientada a Risco:** Foco em áreas historicamente críticas

## 🚫 Critério de Bloqueio de Release

- Nenhum bug Blocker ou Critical aberto
- Fluxos principais totalmente validados
- Sincronização confirmada entre dispositivos
- Ausência de regressão em áreas críticas

---

## ⚠️ Classificação de Severidade

- **Blocker:** Sistema inutilizável
- **Critical:** Quebra do fluxo principal
- **Major:** Impacta experiência, mas possui workaround
- **Minor:** Ajustes visuais ou comportamentos secundários

---

# 📲 Estratégia Específica para Mobile

Testes focados nos principais riscos de ambiente mobile:

- Interrupção por chamada telefônica
- App em background e retomada de sessão
- Rotação de tela
- Alternância entre Wi-Fi e dados móveis
- Simulação de rede instável
- Validação de cache
- Expiração de sessão
- Atualização de versão sem perda de progresso
- Sincronização de progresso entre dispositivos

---

# 🔍 Escopo Funcional Validado

## 📚 Cursos e Trilhas

- Fluxos sequenciais obrigatórios
- Regras de bloqueio/desbloqueio
- Controle de progresso
- Validação de regras de conclusão

## 🎥 Player Multimídia

- Play / Pause
- Buffering
- Sincronização de tempo assistido
- Retomada após interrupção
- Testes sob rede instável

## 📄 PDFs e eBooks

- Renderização correta
- Responsividade
- Scroll e navegação
- Validação de atividades interativas

## 🔄 Sincronização

- Continuidade de progresso entre dispositivos
- Validação de consistência no backend
- Cenários de conflito de dados
- Login em novo dispositivo

---

# 🧪 Tipos de Teste Aplicados

- Testes Funcionais
- Testes de Regressão
- Testes de Interface (Pixel Perfect)
- Testes de Usabilidade (UX)
- Testes Exploratórios Estruturados
- Testes de Compatibilidade
- Testes de Interrupção
- Testes de Rede
- Testes Orientados a Risco

---

# 📊 Gestão de Riscos

## 🔎 Principais Riscos Identificados

- Inconsistência entre iOS e Android
- Falha na sincronização de progresso
- Perda de sessão
- Quebra de layout em tablets
- Problemas de buffering em rede instável

## 🛡️ Mitigações Aplicadas

- Checklists específicos por sistema operacional
- Regressão focada em fluxos críticos
- Comparação lado a lado entre plataformas
- Validação antecipada em ambiente de homologação
- Critério formal de aprovação de release

---

# 🖼️ Telas da Aplicação

| Tela | Evidência |
|------|-----------|
| Login | `/Imagens/login.jpg` |
| Splash | `/Imagens/splash.png` |
| Home | `/Imagens/home.jpg` |
| Conteúdos | `/Imagens/conteudos.jpg` |
| Cursos | `/Imagens/cursos.jpg` |
| Trilhas | `/Imagens/trilhas.jpg` |
| Player | `/Imagens/video.jpg` |
| Atividades | `/Imagens/atividades.jpg` |
| eBook | `/Imagens/ebook.jpg` |

---

# 📈 Resultados Alcançados

- Redução aproximada de 40% nos bugs críticos em produção após formalização da regressão
- Cobertura superior a 95% dos requisitos mapeados via RTM
- Redução significativa de retrabalho do time de desenvolvimento
- Aumento da previsibilidade de releases
- Padronização do processo de QA
- Onboarding mais rápido de novos QAs

---

# 📂 Artefatos Produzidos

- Matriz de Rastreabilidade (RTM)
- Casos de Teste Estruturados
- Checklist de Regressão Mobile
- Relatórios de Validação por Sprint
- Registro detalhado de bugs com evidências

---

# 🚀 Diferenciais Técnicos

- Forte atuação em fragmentação Android
- Validação aprofundada de sincronização entre dispositivos
- Testes robustos de interrupção e retomada
- Mentalidade orientada a risco
- Atuação preventiva (defeitos identificados antes da produção)

---

# 🤝 Conclusão

Este projeto consolidou minha especialização em **QA Mobile**, fortalecendo competências em:

- Estratégia de regressão
- Gestão de risco
- Validação cross-platform
- Fragmentação de dispositivos
- Experiência do usuário
- Governança de qualidade em releases

Projeto conduzido com foco em estabilidade, previsibilidade e melhoria contínua da qualidade.
