# Lume para Windows

Este repositório público contém somente instaladores e arquivos de atualização. O código-fonte do Lume permanece em um repositório privado.

[Baixar Lume 2.0.0-beta.3 (.exe)](https://github.com/bwdmulangu/lume-releases/releases/download/v2.0.0-beta.3/Lume-2.0.0-beta.3-Setup.exe) · [Versões](https://github.com/bwdmulangu/lume-releases/releases)

Um instalador inclui player local, biblioteca, downloads e Estúdio de Widgets. Não é necessário instalar Python, Node.js ou ferramentas de mídia. Feche o Lume antes da instalação manual; músicas, playlists e preferências são preservadas.

Quem usa beta.1 ou beta.2 precisa instalar a beta.3 manualmente uma vez. A partir dela, o aplicativo consulta o canal beta e oferece baixar e instalar novas versões em Preferências. A versão precisa ser compilada, verificada e publicada no canal: editar o código no GitHub sozinho não distribui uma atualização.

Os manifestos do canal beta são assinados com Ed25519. O aplicativo verifica a assinatura, versão, tamanho e SHA-256 antes de executar um instalador. Nenhum token ou chave privada fica dentro do aplicativo. Essa assinatura é independente do certificado de publicador do Windows, ainda não configurado nesta beta.

Versão de testes. Composição e reconexão no OBS e uso em diferentes computadores ainda precisam de validação.
