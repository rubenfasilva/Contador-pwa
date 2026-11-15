# Leitura Contador SMAS

PWA que lê o contador da água com a câmara e abre o marcador do telemóvel com a
sequência de teclas para comunicar a leitura aos SMAS por telefone.

## Modelo de leitura de dígitos

Os ficheiros `digitos.json` e `digitos.bin` contêm os pesos do modelo
`dig-class100-0182-s2_q.tflite` do projecto
[AI-on-the-edge-device](https://github.com/jomjol/AI-on-the-edge-device),
convertidos para serem executados em JavaScript dentro da página. É uma versão
modificada e não é fornecida pelos autores originais. A licença do projecto
original está em `MODELO-LICENCA.md` e só permite uso privado e não comercial.
