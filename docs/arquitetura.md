# 🧱 Arquitetura do Sustentax

---

## 🌍 Visão Geral

O **Sustentax** é uma plataforma educacional baseada na integração entre tecnologia, sustentabilidade e engajamento comunitário.

A solução combina ferramentas digitais simples com práticas pedagógicas para gerar impacto socioambiental real e mensurável.

---

## ⚙️ Estrutura da Plataforma

A arquitetura do sistema é composta por:

- 📱 **Interface:** Aplicativo desenvolvido no Glide
- 📊 **Base de Dados:** Google Sheets
- 🔄 **Lógica de Negócio:** Conversão automática de resíduos em Sustentax
- 🏆 **Gamificação:** Sistema de pontuação, ranking e conquistas

---

## 🧩 Componentes do Sistema

### 1. Cadastro de Correntistas
Responsável pelo registro dos usuários da plataforma.

Campos principais:
- ID_Correntista
- Nome
- Segmento (Aluno, Servidor, Comunidade)
- Turma

---

### 2. Registro de Resíduos
Módulo de entrada de dados das entregas.

- Tipo de resíduo
- Quantidade
- Data
- Conversão automática para Sustentax

---

### 3. Sistema de Pontuação
Motor de cálculo da moeda social.

- Saldo acumulado
- Histórico de movimentações
- Regras de conversão

---

### 4. Gamificação
Mecanismo de engajamento dos usuários.

- Ranking por desempenho
- Sistema de conquistas
- Metas individuais e coletivas

---

## 🔐 Segurança e Privacidade

- Nenhum dado sensível é armazenado neste repositório
- Informações pessoais são tratadas conforme a LGPD
- Dados operacionais permanecem em ambiente controlado (Glide/Sheets)

---

## 🚀 Escalabilidade

A arquitetura permite:

- Expansão para múltiplas escolas
- Integração com dashboards analíticos
- Adaptação para políticas públicas educacionais
