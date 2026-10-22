# GamePad Lite

Utilitário para controles no Windows 10/11 **x64**. Código-fonte privado; este repositório distribui apenas instaladores, pacotes de atualização e documentação.

## Instalar

Baixe [GamePadLite-Instalar.exe](https://github.com/eduardofigueiredodev/gamepad-lite-releases/releases/latest/download/GamePadLite-Instalar.exe) e abra. Ele consulta a versão pública mais recente, baixa o instalador completo, verifica SHA-256 e inicia a instalação. Não é necessário login no GitHub nem instalar o .NET 8 manualmente. O instalador online usa o .NET Framework do Windows; o aplicativo inclui seu próprio runtime.

Para instalação sem baixar novamente o aplicativo, use [GamePadLite-Setup.exe](https://github.com/eduardofigueiredodev/gamepad-lite-releases/releases/latest/download/GamePadLite-Setup.exe). Internet ainda é necessária se precisar instalar o driver Xbox.

## Driver e atualizações

Em Preferências, use **Instalar driver Xbox** se o ViGEmBus estiver ausente. O instalador oficial pede permissão de administrador e pode solicitar reinicialização do Windows. HidHide é opcional e não é instalado automaticamente.

A V2 verifica novas versões automaticamente quando abre. Para aplicar, vá a Preferências e clique em **Atualizar e reiniciar**. Não há reinício automático durante jogos. Perfis e configurações ficam fora da pasta substituída nas atualizações, em `%LocalAppData%\GamePadLite\UserData`.

## Controles

DualSense/Edge: entradas, sensores, vibração, iluminação e gatilhos adaptativos. PS é encaminhado ao botão Guide do Xbox virtual.

DS4 e genéricos estão em suporte experimental, sem confirmação física em todos os modelos. DS4: entradas, vibração e barra RGB, sem gatilhos adaptativos. Genéricos em modo X usam XInput nativo; modo D depende do driver estar disponível via joystick legado do Windows (WinMM). O mapeamento fica em Preferências. Vibração e luz proprietárias de genéricos em modo D não estão implementadas.

A Steam pode entrar em conflito com a emulação; a proteção da V2 encerra/bloqueia o app enquanto a Steam estiver aberta. A Game Bar depende da instalação e das configurações do Windows.

## Distribuição

Os arquivos da V2 ainda não têm assinatura digital própria; o Windows pode exibir editor desconhecido. Downloads são distribuídos por este repositório oficial e acompanhados por `SHA256SUMS.txt`. O driver ViGEmBus é baixado da [publicação oficial da Nefarius](https://github.com/nefarius/ViGEmBus/releases/tag/v1.22.0).

Relate problemas em [Issues](https://github.com/eduardofigueiredodev/gamepad-lite-releases/issues), informando versão, modelo do controle e conexão. Evite publicar arquivos com dados pessoais.
