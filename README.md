# Lume para Windows

Este repositório público contém somente instaladores e arquivos de atualização. O código-fonte do Lume permanece em um repositório privado.

[Baixar Lume 2.0.0-beta.6 (.exe)](https://github.com/bwdmulangu/lume-releases/releases/download/v2.0.0-beta.6/Lume-2.0.0-beta.6-Setup.exe) · [Versões](https://github.com/bwdmulangu/lume-releases/releases)

Um instalador inclui player local, biblioteca, downloads e Estúdio de Widgets. Não é necessário instalar Python, Node.js ou ferramentas de mídia. Feche o Lume antes da instalação manual; músicas, playlists e preferências são preservadas.

Na beta.3, beta.4 ou beta.5, abra Preferências → Atualizações → Verificar atualização para encontrar a beta.6. Quem usa beta.1 ou beta.2 precisa instalar a beta.6 manualmente uma vez. O aplicativo consulta o canal beta e oferece baixar e instalar novas versões. A versão precisa ser compilada, verificada e publicada no canal: editar o código no GitHub sozinho não distribui uma atualização.

A beta.4 acrescenta Terminal, Album Poster, Split Player e Neon Pulse, mantendo Circular Spectrum e os modelos anteriores em Clássicos. Os widgets usam a música, o tempo e o áudio real do player.

A beta.5 corrige os formatos de capa, separa seu arredondamento, mostra controles de vinil apenas quando têm efeito e aumenta o espaço da prévia. Em Fonte de transmissão, a opção Alta · 2× aumenta a resolução. Use as dimensões indicadas nas propriedades da fonte e reduza para o tamanho sugerido na cena. Padrão · 1× continua disponível; o custo real do modo 2× no OBS ainda precisa de medição.

A beta.6 move as músicas selecionadas para a Lixeira do Windows após confirmação. Se um arquivo falhar, ele continua na biblioteca. Remover de uma playlist preserva o áudio; JPGs separados e pastas também são preservados. A exclusão atualiza o catálogo uma vez por lote, e a fila evita buscas repetidas ao restaurar a ordem após embaralhar.

Os manifestos do canal beta são assinados com Ed25519. O aplicativo verifica a assinatura, versão, tamanho e SHA-256 antes de executar um instalador. Nenhum token ou chave privada fica dentro do aplicativo. Essa assinatura é independente do certificado de publicador do Windows, ainda não configurado nesta beta.

Versão de testes. Composição e reconexão no OBS e uso em diferentes computadores ainda precisam de validação.
