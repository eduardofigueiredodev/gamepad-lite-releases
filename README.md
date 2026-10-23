<img src="assets/app.png" width="64" height="64" alt="Ícone do GamePad Lite">

# GamePad Lite

Seus controles, seus ajustes. Um utilitário para Windows com emulação Xbox, perfis, iluminação e efeitos.

**Windows 10 e 11 · 64 bits · .NET incluído**

## [↓ Baixar para Windows](https://github.com/eduardofigueiredodev/gamepad-lite-releases/releases/latest/download/GamePadLite-Instalar.exe)

Este é o **instalador ONLINE recomendado**: um arquivo pequeno que precisa de internet para baixar e instalar o aplicativo. Ele cria atalhos na **Área de Trabalho** e no **Menu Iniciar**. Não precisa de conta no GitHub.

[Instalador OFFLINE — aplicativo completo](https://github.com/eduardofigueiredodev/gamepad-lite-releases/releases/latest/download/GamePadLite-Setup.exe) · [Novidades da versão](https://github.com/eduardofigueiredodev/gamepad-lite-releases/releases/latest) · [Relatar um problema](https://github.com/eduardofigueiredodev/gamepad-lite-releases/issues)

**Escolha apenas um instalador.** ONLINE baixa o aplicativo ao instalar; OFFLINE já traz o aplicativo inteiro. Os dois instalam a mesma versão. Se estiver em dúvida, use o botão “Baixar para Windows”.

Os arquivos SHA-256 e “Source code” da lista de downloads não são instaladores e podem ser ignorados.

---

### Comece em três passos

1. **Instale e abra** o GamePad Lite.
2. **Conecte o controle** por USB ou Bluetooth.
3. Para emular Xbox, instale o driver pelo botão **Preferências → Instalar driver Xbox**, se ele estiver ausente, e ative a emulação.

O instalador do driver pode pedir permissão de administrador e reinicialização do Windows. Internet é necessária para baixar o driver; HidHide é opcional e não é instalado automaticamente.

### Ajuste do seu jeito

- Monitore botões, analógicos, gatilhos, sensores e touchpad disponíveis no controle.
- Ajuste vibração, iluminação e gatilhos adaptativos compatíveis.
- Salve perfis e personalize deadzones e curvas dos analógicos.
- Use efeitos enviados por jogos e mods via UDP.

### Atualize quando for conveniente

O aplicativo instalado verifica novidades ao abrir. Em **Preferências**, use **Atualizar e reiniciar** para aplicar. Ele não reinicia durante o jogo por conta própria e preserva seus perfis e configurações.

### Compatibilidade

| Controle | Recursos |
|**Escolha apenas um instalador.** ONLINE baixa o aplicativo ao instalar; OFFLINE já traz o aplicativo inteiro. Os dois instalam a mesma versão. Se estiver em dúvida, use o botão “Baixar para Windows”.

Os arquivos SHA-256 e “Source code” da lista de downloads não são instaladores e podem ser ignorados.

---|**Escolha apenas um instalador.** ONLINE baixa o aplicativo ao instalar; OFFLINE já traz o aplicativo inteiro. Os dois instalam a mesma versão. Se estiver em dúvida, use o botão “Baixar para Windows”.

Os arquivos SHA-256 e “Source code” da lista de downloads não são instaladores e podem ser ignorados.

---|
| **DualSense / Edge** | Entradas, sensores, Xbox virtual, vibração, iluminação e gatilhos adaptativos compatíveis |
| **DualShock 4 — experimental** | Entradas, Xbox virtual, vibração e barra RGB; ainda requer validação física por modelo |
| **Genéricos — experimental** | XInput nativo ou modo D via driver legado WinMM, com mapeamento ajustável; cobertura depende do driver |

A proteção contra conflitos com a Steam vem ativada e bloqueia/encerra a V2 enquanto ela estiver aberta. O funcionamento da Game Bar depende da instalação e das configurações do Windows.

<details>
<summary>Informações técnicas e segurança do download</summary>

- Os instaladores são publicados neste repositório oficial. `SHA256SUMS.txt` permite conferir a integridade dos downloads.
- O instalador online usa o .NET Framework do Windows; o aplicativo inclui seu próprio runtime .NET.
- A V2 ainda não tem assinatura digital própria; o Windows pode mostrar editor desconhecido.
- O ViGEmBus é baixado da [publicação oficial da Nefarius](https://github.com/nefarius/ViGEmBus/releases/tag/v1.22.0), com hash verificado.
- Os dados da versão instalada ficam em `%LocalAppData%\GamePadLite\UserData`.
- Este repositório contém apenas documentação e instaladores. O código-fonte do aplicativo é privado; os arquivos “Source code” adicionados automaticamente pelo GitHub não são o aplicativo.
- Pacotes internos de atualização são mantidos em um repositório técnico separado e baixados pela própria V2.

</details>

Encontrou um problema? [Abra um chamado](https://github.com/eduardofigueiredodev/gamepad-lite-releases/issues) com a versão, o modelo do controle e o tipo de conexão. Não inclua informações pessoais.