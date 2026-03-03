# 📱 Teste de Software - APP Mobile (Prudential LMS)

![QA Status](https://img.shields.io/badge/Status-Concluído-brightgreen)  
![Platform](https://img.shields.io/badge/Plataforma-iOS%20%7C%20Android-lightgrey)  
![Years](https://img.shields.io/badge/Duração-2%20Anos-blue)

Este repositório documenta minha atuação como **Analista de Testes (QA)** na validação do aplicativo Prudential LMS, plataforma educacional corporativa distribuída para **iOS (iPhone/iPad)** e **Android**.

Atuei de 2021 a 2023 garantindo qualidade ponta a ponta, cobrindo requisitos funcionais, experiência do usuário, estabilidade, sincronização entre dispositivos e mitigação de riscos em produção.

---

## 🎯 Objetivo do Projeto

Garantir a integridade completa da jornada do usuário:

Login → Consumo de Conteúdo → Interação Multimídia → Sincronização → Conclusão de Cursos

Foco principal:

- Conformidade com requisitos de negócio  
- Experiência fluida e intuitiva  
- Consistência visual (Pixel Perfect)  
- Estabilidade em múltiplos dispositivos  
- Prevenção de regressões  

---

## 🛠️ Stack Utilizada

### Gestão e Processos

- Jira (Workflow Ágil com controle de severidade)
- Participação em refinamentos técnicos com PO e desenvolvedores
- Definição de critério formal de Go/No-Go para releases

### Documentação

- Microsoft Excel (RTM – Matriz de Rastreabilidade)
- Casos de teste estruturados por prioridade
- Checklist de regressão mobile

### Design & Validação Visual

- Figma (validação de fidelidade visual e inconsistências de UI)

### Dispositivos Físicos

#### iOS

- iPhone (múltiplas versões de iOS)
- iPad (validação de responsividade e layout adaptativo)

#### Android

- Dispositivos de diferentes fabricantes
- Testes em múltiplas resoluções e densidades (fragmentação)

---

## 🧠 Estratégia de Testes

### Estrutura de Regressão

- **Smoke Test:** Fluxos críticos (login, abertura de curso, player, sincronização)
- **Regressão Completa:** Executada ao final de cada sprint
- **Validação Cross-Platform:** Comparação de comportamento entre iOS e Android

**Critério de bloqueio de release:**

- Nenhum bug Blocker ou Critical aberto
- Funcionalidades core estáveis
- Sincronização validada em dispositivos distintos

---

### Classificação de Severidade

- **Blocker:** Impede uso do sistema
- **Critical:** Afeta fluxo principal
- **Major:** Impacta experiência, mas possui workaround
- **Minor:** Ajustes visuais ou pequenos comportamentos

---

### Estratégia Mobile Específica

Foram aplicados testes focados nos principais riscos de ambiente mobile:

- Interrupção por chamada telefônica
- App em background e retomada de sessão
- Rotação de tela
- Alternância entre Wi-Fi e dados móveis
- Testes em rede instável
- Validação de cache e sessão expirada
- Atualização de versão sem perda de progresso
- Sincronização de progresso entre dispositivos

---

## 🔍 Escopo Funcional Validado

### 📚 Cursos e Trilhas

- Fluxos sequenciais obrigatórios
- Regras de bloqueio/desbloqueio
- Controle de progresso
- Validação de regras de conclusão

### 🎥 Player Multimídia

- Play e Pause
- Buffering
- Sincronização de tempo assistido
- Retomada automática após interrupção
- Testes em rede instável

### 📄 PDFs e eBooks

- Renderização correta
- Responsividade
- Scroll e navegação
- Interação com atividades integradas

### 🔄 Sincronização

- Continuidade de progresso entre dispositivos
- Validação de consistência backend
- Testes de conflito de dados
- Validação pós-login em novo dispositivo

---

## 🧪 Tipos de Teste Aplicados

- Testes Funcionais
- Testes de Regressão
- Testes de Interface (UI Pixel Perfect)
- Testes de Usabilidade (UX)
- Testes Exploratórios Estruturados
- Testes de Compatibilidade
- Testes de Interrupção
- Testes de Rede

---

## 📊 Gestão de Riscos

### Principais Riscos Identificados

- Inconsistência entre iOS e Android
- Falha na sincronização de progresso
- Perda de sessão
- Quebra de layout em tablets
- Problemas de buffering em redes instáveis

### Mitigações Aplicadas

- Checklists específicos por sistema operacional
- Execução regressiva focada em áreas críticas
- Testes comparativos lado a lado
- Validação antecipada em ambientes de homologação

---

## 🖼️ Evidências de Telas

| Tela | Evidência |
|------|-----------|
| Login | /Imagens/login.jpg |
| Splash | /Imagens/splash.png |
| Home | /Imagens/home.jpg |
| Conteúdos | /Imagens/conteudos.jpg |
| Cursos | /Imagens/cursos.jpg |
| Trilhas | /Imagens/trilhas.jpg |
| Player | /Imagens/video.jpg |
| Atividades | /Imagens/atividades.jpg |
| eBook | /Imagens/ebook.jpg |

---

## 📈 Resultados Alcançados

- Redução aproximada de 40% nos bugs críticos reportados em produção após formalização da regressão.
- Cobertura funcional superior a 95% dos requisitos mapeados via RTM.
- Redução significativa de retrabalho da equipe de desenvolvimento.
- Aumento da previsibilidade de release através de critérios formais de aprovação.
- Padronização de processos que aceleraram o onboarding de novos QAs.

---

## 🧾 Artefatos Produzidos

- Matriz de Rastreabilidade (RTM)
- Casos de Teste Estruturados
- Checklist de Regressão Mobile
- Relatórios de Validação por Sprint
- Registro detalhado de bugs com evidências

---

## 🚀 Diferenciais Técnicos

- Forte atuação em fragmentação Android
- Validação detalhada de sincronização entre dispositivos
- Testes aprofundados de interrupção e retomada
- Mentalidade orientada a risco
- Foco preventivo (bug identificado antes de chegar em produção)

---

## 🤝 Conclusão

A atuação no Prudential LMS consolidou minha especialização em QA Mobile, com domínio de:

- Estratégia de regressão
- Gestão de risco
- Fragmentação de dispositivos
- Validação cross-platform
- Experiência do usuário

Projeto conduzido com foco em estabilidade, previsibilidade e qualidade contínua.
