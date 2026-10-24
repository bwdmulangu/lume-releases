# Lume para Windows

[Baixar uma versão beta do Lume](https://github.com/bwdmulangu/lume-releases/releases) — abra a versão mais recente numerada e, em **Assets**, baixe o arquivo **Lume-…-Setup.exe**. A release **channel-beta** contém o manifesto de atualização, não o instalador.

Este repositório público contém instaladores e arquivos de atualização. O código-fonte permanece privado. Player, biblioteca, downloads e Estúdio de Widgets estão incluídos; não é necessário instalar Python, Node.js ou ferramentas de mídia.

No aplicativo, use **Preferências → Atualizações** para verificar, baixar e instalar uma nova versão. A partir da beta.14, o Lume também procura atualizações ao abrir, a cada dez minutos e ao voltar à janela após cinco minutos sem consulta. A bolinha azul em Preferências indica uma versão disponível ou pronta para instalar. O aplicativo não reinicia nem instala sem sua ação.

Feche o Lume antes da instalação manual. Atualizações preservam músicas, playlists e preferências. A exclusão pela biblioteca oferece dez segundos para desfazer e depois envia o áudio para a Lixeira. A desinstalação preserva músicas por padrão e pode oferecer uma revisão opcional dos downloads.

Os widgets usam a música, o tempo e o áudio do player. A opção Alta · 2× aumenta a resolução da fonte de navegador; use as dimensões indicadas no Estúdio e reduza para o tamanho sugerido na cena. Uso prolongado no OBS e em computadores diferentes ainda precisa de validação.

Os manifestos do canal beta são assinados com Ed25519. O aplicativo verifica assinatura, versão, tamanho e SHA-256 antes de executar o instalador. Essa assinatura é independente do certificado de publicador do Windows, ainda não configurado nesta beta. Avisos do Windows podem continuar aparecendo.

**Versão de testes.** As notas e os arquivos de cada versão estão na página de releases.
