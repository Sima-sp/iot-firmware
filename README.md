# SIMA-SP · firmware do sensor

Firmware do sensor de nível de água do SIMA-SP: ESP32 com sensor de distância por ultrassom, que
mede a distância até a água e envia a leitura por Wi-Fi.

## Onde está o código hoje

O firmware e o servidor do sensor (Node) usados na feira de 07/10/2026 estão na pasta
[`iot/` do `Sima-sp/mobile-app`](https://github.com/Sima-sp/mobile-app/tree/main/iot), com o
passo a passo para gravar a placa e rodar o servidor. Este repositório fica reservado para o
firmware quando ele passar a evoluir separado do app.

## Como o grupo trabalha

- Ninguém envia direto para a `main`: cada mudança vai numa branch e entra por pull request.
- O merge é sempre *squash* e a branch é apagada depois.
- A senha do Wi-Fi e qualquer chave nunca vão para o git.
