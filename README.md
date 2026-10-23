# Lume para Windows

Este repositório público contém somente instaladores e arquivos de atualização. O código-fonte do Lume permanece em um repositório privado.

[Baixar Lume 2.0.0-beta.7 (.exe)](https://github.com/bwdmulangu/lume-releases/releases/download/v2.0.0-beta.7/Lume-2.0.0-beta.7-Setup.exe) · [Versões](https://github.com/bwdmulangu/lume-releases/releases)

Um instalador inclui player local, biblioteca, downloads e Estúdio de Widgets. Não é necessário instalar Python, Node.js ou ferramentas de mídia. Feche o Lume antes da instalação manual; músicas, playlists e preferências são preservadas.

A beta.7 já está disponível pelo instalador acima. A ativação desta versão no canal de atualização do aplicativo ainda está em conclusão; por enquanto, use o EXE. Depois de ativado, o canal permite verificar, baixar e instalar pelo próprio Lume. Uma mudança no código precisa ser compilada, testada e publicada para chegar ao aplicativo.

A beta.4 acrescenta Terminal, Album Poster, Split Player e Neon Pulse, mantendo Circular Spectrum e os modelos anteriores em Clássicos. Os widgets usam a música, o tempo e o áudio real do player.

A beta.5 corrige os formatos de capa, separa seu arredondamento, mostra controles de vinil apenas quando têm efeito e aumenta o espaço da prévia. Em Fonte de transmissão, a opção Alta · 2× aumenta a resolução. Use as dimensões indicadas nas propriedades da fonte e reduza para o tamanho sugerido na cena. Padrão · 1× continua disponível; o custo real do modo 2× no OBS ainda precisa de medição.

A beta.6 move as músicas selecionadas para a Lixeira do Windows após confirmação. Se um arquivo falhar, ele continua na biblioteca. Remover de uma playlist preserva o áudio; JPGs separados e pastas também são preservados. A exclusão atualiza o catálogo uma vez por lote, e a fila evita buscas repetidas ao restaurar a ordem após embaralhar.

A beta.7 acrescenta Usar as cores da capa imediatamente ao lado do fundo branco da prévia, sincronizado com a opção em Aparência. As cores automáticas preservam matizes predominantes e ganham contraste; as escolhas manuais ficam guardadas. O processamento usa uma amostra pequena e cache de capas.

Os manifestos do canal beta são assinados com Ed25519. O aplicativo verifica a assinatura, versão, tamanho e SHA-256 antes de executar um instalador. Nenhum token ou chave privada fica dentro do aplicativo. Essa assinatura é independente do certificado de publicador do Windows, ainda não configurado nesta beta.

Versão de testes. Composição e reconexão no OBS e uso em diferentes computadores ainda precisam de validação.
