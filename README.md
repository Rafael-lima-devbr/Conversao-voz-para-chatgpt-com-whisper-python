# Conversão de Voz para ChatGPT com Whisper e Python

Projeto de aprendizagem desenvolvido como desafio da **DIO** para explorar um pipeline de interação por voz com IA.

**Status:** Protótipo incompleto / desenvolvimento interrompido

Este repositório permanece público porque está vinculado ao projeto publicado na plataforma DIO.

## Objetivo

A proposta era construir um fluxo capaz de:

```text
Áudio -> transcrição -> modelo de IA -> resposta -> áudio
```

O notebook explora:

- gravação de áudio no navegador em Google Colab;
- transcrição com Whisper;
- integração planejada com um modelo de IA;
- síntese de voz com gTTS.

## Tecnologias

- Python
- Whisper
- JavaScript / MediaStream API
- gTTS
- Google Colab

## Estado atual

A captura de áudio, o processamento em Python e a transcrição com Whisper foram estudados e integrados ao notebook. A etapa de interação em tempo real com um modelo externo não foi concluída.

Durante o desenvolvimento, a integração original dependia da API da OpenAI, cujo uso contínuo exige créditos pagos. Uma alternativa com Gemini também não pôde ser utilizada naquele momento devido aos requisitos de idade da conta.

Por isso, este repositório deve ser interpretado como um **protótipo de aprendizagem**, e não como um assistente de voz finalizado.

## Arquivo principal

```text
Assistente_de_Voz_Multi_Idiomas_Com_Whisper_e_ChatGPT.ipynb
```

O notebook concentra a experimentação com captura, transcrição e estrutura do fluxo de resposta por voz.

## Limitações

- integração com LLM externo não concluída;
- dependência de serviços externos para algumas etapas;
- execução pensada para Google Colab, não como aplicação desktop;
- ausência de empacotamento ou interface de produção.

## Possíveis evoluções

Caso o projeto seja retomado, caminhos possíveis incluem:

- uso de um modelo local ou alternativa open source;
- separação do pipeline em módulos independentes;
- interface própria fora do Colab;
- ativação por wake word;
- empacotamento como aplicação desktop.

## Créditos

A implementação da gravação de áudio foi adaptada a partir de:

https://gist.github.com/korakot/c21c3476c024ad6d56d5f48b0bca92be

## Licença

MIT License.
