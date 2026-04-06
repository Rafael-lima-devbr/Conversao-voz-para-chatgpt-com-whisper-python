# 🎤 Conversão de Voz para ChatGPT com Whisper e Python

Este projeto demonstra um pipeline completo de interação com inteligência artificial utilizando voz. O sistema captura áudio do usuário, converte em texto, envia para um modelo de IA e retorna a resposta em áudio.

---

## 🚀 Funcionalidades

- 🎤 Gravação de áudio diretamente no navegador (Google Colab)
- 🧠 Transcrição de áudio para texto com Whisper
- 💬 Envio do texto para um modelo de IA (ChatGPT)
- 🔊 Conversão da resposta em áudio utilizando gTTS

---

## 🧠 Como funciona

Áudio → Transcrição (Whisper) → IA → Resposta → Áudio

---

## ⚙️ Tecnologias utilizadas

- Python
- Whisper (OpenAI)
- JavaScript (MediaStream API)
- gTTS (Google Text-to-Speech)
- Google Colab

---

## ⚠️ Limitações encontradas

Durante o desenvolvimento deste projeto, algumas limitações importantes foram identificadas:

- A API da OpenAI, utilizada originalmente, atualmente é paga e não oferece mais acesso gratuito contínuo.
- A tentativa de utilizar a API do Gemini como alternativa não foi viável devido à exigência de idade mínima (18 anos) para criação e uso da conta.
- Por esses motivos, não foi possível concluir totalmente a integração com APIs de IA em tempo real.

---

## 📌 Observações

Apesar das limitações externas, o projeto foi desenvolvido e compreendido em sua totalidade, incluindo:

- Captura de áudio via navegador utilizando JavaScript
- Processamento e manipulação de dados em Python
- Uso de modelos de transcrição de fala (speech-to-text)
- Estruturação de integração com APIs de inteligência artificial

---

## 🔮 Trabalhos futuros

Pretendo evoluir este projeto futuramente, considerando:

- Utilização de APIs pagas quando houver condição financeira
- Uso das APIs ao atingir a idade mínima exigida
- Busca por alternativas gratuitas ou open-source
- Evolução do sistema para um assistente de voz mais completo
- Criação de um assistente inspirado no Jarvis que rode em segundo plano no PC, ativando com uma wake word e desativando com outra palavra-chave, de forma que, enquanto inativo, o sistema apenas monitore ondas sonoras sem transcrever desnecessariamente, economizando processamento. Esse projeto futuramente poderia ser distribuído como um executável (.exe).

---

## 🙏 Créditos

A implementação da gravação de áudio foi baseada no seguinte código:

https://gist.github.com/korakot/c21c3476c024ad6d56d5f48b0bca92be

Essa parte foi adaptada e integrada ao restante do projeto.

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## 💡 Conclusão

Este projeto representa não apenas uma implementação técnica, mas também a adaptação a mudanças reais no ecossistema de tecnologia. Mesmo com limitações externas, o aprendizado sobre integração de IA, áudio e automação foi plenamente alcançado.
