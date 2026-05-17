# Projeto Engenharia de Prompt - AutoGen Studio

Este repositório contém a documentação da execução do projeto de Engenharia de Prompt: uma pesquisa de aceitação para um novo refrigerante sabor **Pitanga com Gengibre**, usando um sistema multiagente no AutoGen Studio.

## LLM utilizada nas inferências

A execução final foi feita localmente pelo **LM Studio**, sem uso de API paga da OpenAI ou Google.

- **Modelo / LLM:** `gemma-2b-aps-it`
- **Origem no LM Studio:** `lmstudio-community/gemma-2b-aps-it-GGUF`
- **Arquivo carregado:** `gemma-2b-aps-it-Q6_K.gguf`
- **Execução:** local, via LM Studio Local Server
- **Endpoint usado pelo AutoGen Studio:** `http://localhost:1234/v1`
- **Interface multiagente:** AutoGen Studio em `http://localhost:8081`

Foram testadas alternativas com OpenAI GPT-4o Mini e Google Gemini, mas a execução entregue foi realizada com o modelo local **Gemma 2B** no LM Studio, por não depender de quota de API externa.

## Agentes

Os prompts dos agentes utilizados nas inferências estão em:

- `prompts_agentes.md`

Agentes configurados:

- `PesquisadorAceitacaoAI`
- `EsportistaAI`
- `MinimalistaAI`
- `TechLoverAI`

