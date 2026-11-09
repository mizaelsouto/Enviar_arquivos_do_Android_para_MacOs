# Enviar arquivos do Android para o macOS

Manual em português para copiar arquivos de um celular Android (testado num Galaxy A56) para o Mac, já que o macOS não lê Android sozinho.

**Ver como site:** https://mizaelsouto.github.io/Enviar_arquivos_do_Android_para_MacOs/

## Conteúdo

- `Manual_Galaxy_A56_Mac.html` — visão geral, modo desenvolvedor e Depuração USB, problemas comuns e comandos.
- `Procedimentos_Cabo_e_WiFi.html` — passo a passo por cabo (OpenMTP, ADB) e por Wi-Fi (LocalSend, ADB sem fio).

## Ferramentas

| Ferramenta | Uso | Instalação no Mac |
|---|---|---|
| LocalSend | Envio pelo Wi-Fi, sem cabo | `brew install --cask localsend` |
| OpenMTP | Janela com as pastas do celular, via cabo | `brew install --cask openmtp` |
| ADB | Cópia de pastas pelo terminal | `brew install --cask android-platform-tools` |

As telas do manual são ilustrações; o visual real pode variar conforme a versão do One UI e do macOS.

## Autor

Mizael Souto
