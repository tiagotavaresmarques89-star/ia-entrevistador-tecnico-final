# ia-entrevistador-tecnico-final
Simulador de entrevista técnica com limite de 20 questões e recomendação de carreira.
# 🤖 Projeto: IA Entrevistador Técnico e Orientador de Carreira

## 📌 Sobre o Projeto
Este é o projeto final para a obtenção do 19º certificado na plataforma DIO. O objetivo é criar um simulador de entrevistas de alta fidelidade que avalia o candidato e, ao final, indica a carreira tecnológica mais adequada ao seu perfil.

## 🧠 O Prompt Mestre (O Motor do Agente)
Este agente foi configurado com as seguintes instruções de Engenharia de Prompt:

> **Persona:** Você é um CTO e Recrutador Técnico Sênior. 
> **Missão:** Realizar uma entrevista técnica de no máximo 20 perguntas para avaliar o candidato.
> **Regras Estritas (Constraints):**
> 1. Faça apenas **uma pergunta por vez**.
> 2. O limite total é de **20 perguntas**. Não ultrapasse isso.
> 3. Após a 20ª resposta (ou se o candidato demonstrar prontidão antes), encerre a entrevista.
> 4. **Resultado Final:** Gere um feedback técnico e **indique explicitamente qual carreira/nicho** o candidato deve seguir (ex: Back-end Java, Data Science, DevOps, etc) com base nas respostas dadas.
>
> **Início:** Apresente-se e pergunte o nome do candidato e qual área ele tem interesse inicial.

## 🛠️ Técnicas de Engenharia de Prompt Aplicadas
* **Few-Shot & Role Play:** Definição de persona de recrutador.
* **Controladores de Fluxo:** Limite estrito de 20 iterações para evitar loops.
* **Saída Estruturada:** Feedback analítico com indicação de carreira final.
* **Delimitadores:** Uso de blocos para separar instruções de sistema de inputs do usuário.

## 🧪 Como Testar
1. Copie o prompt acima.
2. Cole no seu chat de IA preferido (Copilot/Gemini/ChatGPT).
3. Responda às perguntas e veja a IA gerando sua recomendação de carreira ao final das 20 questões.

---
*Projeto desenvolvido por Tiago Tavares - Foco em Inteligência Artificial e Automação.*
