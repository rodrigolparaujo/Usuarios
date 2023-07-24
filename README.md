# Usuarios
Funções úteis de Usuário

Segue algumas funções úteis referente aos dados do usuário do sistema.

## UsrFullName – Retorna o nome do completo do usuario

Sinxtaxe: UsrFullName(cUserID)

Onde: cUserID é o código do usuário

Retorno: Nome completo do usuário

## RetCodUsr – Retorna o codigo do Usuario Corrente

Sintaxe: RetCodUsr()

Retorno: Codigo do usuario corrente

## UsrRetGrp – Retorna os grupos do usuario.

Sintaxe: UsrRetGrp(cUserID)
Onde: cUserID é o código do usuário

Retorno: Array contendo os grupos

Obs: Se não informar o código do usuário o sistema considera o usuário logado.

## UsrRetName – Retorna o nome do usuario

Sintaxe: UsrRetName(cUserID)

Onde: cUserID é o código do usuário

Retorno: Nome do usuário

## UsrRetMail – Retorna o e-mail do usuario

Sintaxe: UsrRetMail(cUserID)

Onde: cUserID é o código do usuário

Retorno: E-mail do usuario

## UsrExist – Verifica se o usuario existe

Sintaxe: UsrExist(cUserID)

Onde: cUserID é o código do usuário

Retorno: .T. ou .F.

## UsrGrComp – Retorna os Grupos de Compras do Usuario

Sintaxe: UsrGrComp(cUserID)

Onde: cUserID é o código do usuário

Retorno: Array contendo os codigos dos grupos

## VldGrComp – Verifica se o usuario pertence a um grupo de compras

Sintaxe: VldGrComp(cUserID,cGrupo)

Onde: cUserID é o código do usuário
cGrupo é o Codigo do grupo a ser verificado

Retorno: .T. ou .F.
