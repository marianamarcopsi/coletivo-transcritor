# Transcritor do Coletivo AutonomIA

Arquivos do transcritor usados pela skill **Editor de vídeo** do Coletivo AutonomIA.

A skill baixa estes arquivos sozinha, dentro do Claude. Você não precisa baixar nada daqui.

- `modelos/base`: transcritor leve (padrão).
- `modelos/small`: transcritor preciso (erra menos palavras, é mais lento).

O arquivo `model.bin` está dividido em partes menores. A skill junta as partes e confere se o arquivo ficou certo (`manifesto.json`).

Os modelos são o Whisper (OpenAI), convertido para o formato do faster-whisper pela SYSTRAN. Licença MIT, veja `LICENSE`.
