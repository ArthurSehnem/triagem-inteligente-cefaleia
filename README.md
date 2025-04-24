# 🧠 Sistema Especialista para Avaliação de Dor de Cabeça

Este projeto tem como objetivo desenvolver um **sistema especialista baseado em lógica de decisão clínica** para auxiliar profissionais da saúde no atendimento de pacientes que relatam **dor de cabeça**.

Através de uma série de perguntas estruturadas, o sistema é capaz de:
- Identificar **sinais de alerta**
- Orientar a **conduta adequada**
- Recomendar **cuidados não farmacológicos**
- Sugerir **encaminhamento para outro profissional**, quando necessário

---

## 🚀 Tecnologias Utilizadas

- **Expert SINTA** – Ferramenta de criação de sistemas especialistas, disponibilizada pela Universidade Federal do Ceará
- Lógica baseada em **árvore de decisão clínica**
- Interface interativa para uso em contextos clínicos

---

## 🔎 Fluxo de Decisão (Árvore Lógica)

O paciente é avaliado por meio de perguntas sequenciais. Abaixo está um resumo dos critérios:

### 1. Tempo de duração da dor
- ⏱️ Menos de 7 dias → seguir
- ⚠️ Mais de 7 dias → **Encaminhar**

### 2. Frequência da dor
- 📅 < 15 dias/mês ou episódios esporádicos → seguir
- ⚠️ > 15 dias/mês ou > 3 meses → **Encaminhar**

### 3. Características do sintoma
- ✅ Continuar se: dor bilateral em aperto, sensibilidade pericraniana, padrão estável, pulsátil com diagnóstico prévio
- ⚠️ Encaminhar se: dor unilateral explosiva, mudança de padrão, dor occipital intensa, piora ao deitar

### 4. Intensidade da dor
- 🔹 Leve a moderada → seguir
- 🔺 Moderada a grave (incapacitante) → **Encaminhar**

### 5. Situações associadas
- 🧘‍♀️ Estresse, menstruação, jejum, privação de sono → seguir
- ⚠️ Situações de alerta → **Encaminhar**

### 6. Fatores de alívio/agravamento
- 🌑 Alívio em ambiente escuro e silencioso → seguir
- ⚠️ Agravo com alimentos/odores (sem diagnóstico de enxaqueca) → **Encaminhar**

### 7. Sinais associados
- ✅ Fotofobia/fonofobia isoladas → seguir
- ⚠️ Febre, confusão, rigidez de nuca, gestação avançada, imunossupressão, idade >50 com 1º episódio → **Encaminhar**

### 8. Condições clínicas agravantes
- ⚠️ Hipertensão, trauma, glaucoma, câncer, apneia, bruxismo, DPOC, uso limitado de medicamentos → **Encaminhar**

### 9. Uso de medicamentos
- ⚠️ Uso abusivo, falha terapêutica, suspeita de reação → **Encaminhar**

---

## ✅ Conduta Quando Não Há Sinais de Alerta

Se o paciente **não apresentar sinais de alerta**, o sistema orienta:

### 🩺 Níveis de Acompanhamento
- ✔️ **Remissão** da dor
- 🔍 **Acompanhamento próximo** em caso de melhora parcial

### 🌿 Cuidados Não Farmacológicos
- Descanso em ambiente escuro e silencioso
- Compressas frias ou quentes
- Sono e alimentação regulares
- Técnicas de relaxamento

### 💊 Medicamentos Isentos de Prescrição
- Ibuprofeno, naproxeno, AAS, paracetamol, dipirona, vasoconstritores
- Preferência por combinações com cafeína (quando necessário)

---

> ⚠️ **Atenção:** Este sistema **não substitui a avaliação médica completa** e **não deve ser usado para prescrição de medicamentos controlados**.

---

## 👨‍⚕️ Público-Alvo

- Profissionais da saúde (enfermeiros, médicos, farmacêuticos)
- Estudantes da área da saúde
- Ambientes clínicos de atenção primária
