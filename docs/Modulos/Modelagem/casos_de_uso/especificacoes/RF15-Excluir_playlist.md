Data | Responsável | Versão|
--------- | ------| --------|
26/04/2018 | Eduardo Júnio |   1.0   |
27/05/2018 | Eduardo Júnio |   2.0   |

# ✅ [UC15] - Excluir playlists
## 1. Nome do Caso de Uso
- Excluir playlists

## 2. Breve descrição
- Permite a exclusão de uma playlist selecionada pelo usuário.

## 3.  Atores
- Usuário.

## 4.  Pré-Condição
- O usuário deve possuir uma conta no spotify.
- Ter o aplicativo do Spotify instalado
- Estar conectado à internet.

## 5.  Fluxo de eventos

### 5.1 Fluxo básico

1. O caso de uso começa quando o ator abre o aplicativo.
2. O sistema exibe a tela inicial do aplicativo.
3. O usuário seleciona a opção Acessar biblioteca.
4. O sistema exibe as opções de funcionalidades disponíveis na biblioteca.
5. O usuário seleciona uma playlist.[FA01]
6. O sistema apresenta as músicas salvas na playlist.
7. O usuário seleciona a opção apagar.[FA01]
8. O sistema exclui a playlist.

## 5.2 Fluxos alternativos

FA01 - O usuário cancela a operação
1. O usuário cancela a operação corrente.
2. O sistema redireciona o usuário para outra tela.

FA02 - O usuário não possui playlists salvas.
1. O usuário não possui playlists.
2. O sistema apresenta ao usuário a opção criar playlist.

## 5.3 Fluxos de Exceção

FE01 - Não ter acesso a Internet durante o procedimento
1. O sistema informa "O spotify está offline"[M1].
2. A operação é interrompida.
3. O caso de uso se encerra.

FE02 - Aplicativo parar de funcionar
1. O sistema informa: "O aplicativo encerrou inesperadamente."[M2]
2. A operação é interrompida.
3. O caso de uso se encerra.

## 6 Mensagens
- [M1] O spotify está offline.
- [M2] O aplicativo encerrou inesperadamente.