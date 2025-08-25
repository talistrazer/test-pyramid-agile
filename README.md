# 🧪 Pirâmide de Testes & Quadrante Ágil

![GitHub last commit](https://img.shields.io/github/last-commit/TalissaStrazer/test-pyramid-agile?color=blue&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/TalissaStrazer/test-pyramid-agile?color=green&style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/TalissaStrazer/test-pyramid-agile?color=yellow&style=flat-square)
![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)

Este repositório apresenta conceitos e boas práticas sobre **estratégias de testes em software**, com base na **Pirâmide de Testes de Mike Cohn** e no **Quadrante Ágil**.  
O objetivo é ajudar times de desenvolvimento e QA a estruturarem uma suíte de testes eficiente, equilibrando **custo, velocidade e qualidade**.  

---

## 📖 Introdução

A **Pirâmide de Testes** é uma metáfora visual que sugere a distribuição de testes em diferentes camadas.  
Criada por Mike Cohn no livro *Succeeding with Agile*, ela orienta sobre **quantidade, granularidade e foco** de cada tipo de teste.

👉 Times que invertem a pirâmide acabam sofrendo com **refatorações lentas, alto custo e baixa confiança** nos deploys.  

![Pirâmide de Testes](https://miro.medium.com/v2/resize:fit:720/format:webp/1*B_GFdYyAzDQJ5xpoEphQfA.png)

---

## 🔺 Estrutura da Pirâmide

### 1️⃣ Unit Tests (Unidade)
- **Categoria**: Automatizado  
- **Custo/Tempo**: Baixo  
- **Responsável**: Devs (mas QAs também podem contribuir)  
- **Objetivo**: Validar pequenas funções isoladas com execução rápida.  
- **Volume recomendado**: **80–85%**  

---

### 2️⃣ Service Tests (Integração + Componente)
- **Categoria**: Automatizado  
- **Custo/Tempo**: Médio  
- **Responsável**: Devs e QAs  
- **Objetivo**: Validar a interação entre serviços e componentes.  
- **Exemplo**: Um produto cadastrado que não aparece no banco de dados.  
- **Volume recomendado**: **20–30%**  

---

### 3️⃣ UI Tests (Interface do Usuário + Exploratórios)
- **Categoria**: Manual / Automatizado em menor escala  
- **Custo/Tempo**: Alto  
- **Responsável**: QAs e Devs  
- **Objetivo**: Garantir acessibilidade, usabilidade e fluxo ponta a ponta.  
- **Volume recomendado**: **5–10%**  

---

### ⚡ Testes de Segurança e Performance (Fora da Pirâmide)
- **Categoria**: Ferramentas e análises especializadas  
- **Custo/Tempo**: Alto  
- **Responsável**: Devs + QAs + Arquitetura  
- **Objetivo**: Validar memória, performance, carga e segurança do sistema.  

---

## ✅ Benefícios da Pirâmide de Testes
- 🔹 **Agilidade**: testes de unidade rodam em segundos.  
- 🔹 **Menos gargalos**: menos dependência de testes lentos de ponta a ponta.  
- 🔹 **Maior confiança**: feedback rápido em cada commit.  
- 🔹 **Escalabilidade**: suite de testes mais sustentável a longo prazo.  

---

## 📊 Quadrante Ágil

O **Quadrante Ágil de Testes** divide os tipos de testes em **4 pilares**:  
1. **Foco em Negócio**  
2. **Crítica ao Produto**  
3. **Suporte ao Time**  
4. **Foco em Tecnologia**  


### Benefícios dessa visão:
- 🎯 **Priorização**: começar pelos testes mais rápidos e baratos.  
- 🤝 **Assertividade**: escolher a categoria correta em cada etapa.  
- ⚙️ **Automação inteligente**: saber o que realmente vale automatizar.  
- 📈 **Qualidade contínua**: visão completa do ciclo de desenvolvimento.  

---

## 🚀 Conclusão

A **Pirâmide de Testes** e o **Quadrante Ágil** juntos oferecem:  
- Melhor gestão de custos e tempo de execução.  
- Mais clareza sobre quais testes escrever em cada fase.  
- Entregas mais seguras, sustentáveis e ágeis.  

💡 Lembre-se: **a base (unit tests) garante velocidade, o topo (UI tests) garante confiabilidade**. O equilíbrio é a chave da qualidade.  

---

## 💬 Contribua

Gostou do conteúdo?  
Deixe seu comentário, abra uma **issue** ou envie um **PR** com sugestões.  

Um abraço ✨  
