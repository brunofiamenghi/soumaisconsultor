## Módulo: SIGAESTN (Estoque Nacional / Regulação e Armazenagem Especial)  
--- ### GUN  
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC  
GUN|01|GUN_FILIAL|C|6|0|Filial|Filial
GUN|02|GUN_CODTAB|C|6|0|Cod Tabela|Identificacao da Tabela
GUN|03|GUN_TPTAB|C|1|0|Tipo Tabela|Tipo da Tabela
GUN|04|GUN_DUPSEN|C|1|0|Ida e Volta|Ida e Volta
GUN|05|GUN_DATDE|D|8|0|Ini Validade|Inicio Validade
GUN|06|GUN_DATATE|D|8|0|Fim Validade|Fim Validade
GUN|07|GUN_NRCIOR|C|7|0|Cid Origem|Cidade Origem
GUN|08|GUN_NRREOR|C|6|0|Reg Origem|Regiao Origem
GUN|09|GUN_CDREM|C|14|0|Remetente|Codigo Remetente
GUN|10|GUN_NRCIDS|C|7|0|Cid Dest|Cidade Destino
GUN|11|GUN_NRREDS|C|6|0|Reg Dest|Regiao Destino
GUN|12|GUN_CDDEST|C|14|0|Destinatario|Codigo Destinatario
GUN|13|GUN_INFRTO|C|120|0|Rota Origem|Rota de Origem
GUN|14|GUN_INFRTD|C|120|0|Rota Destino|Rota Destino
GUN|15|GUN_CDTPOP|C|10|0|Tipo Oper|Tipo de Operacao
GUN|16|GUN_DSTPOP|C|50|0|Desc Tp Op|Descricao Tipo Operacao
GUN|17|GUN_CDTPVC|C|10|0|Tipo Veiculo|Tipo Veiculo
GUN|18|GUN_DSTPVC|C|50|0|Desc Tp Veic|Descricao Tipo de Veiculo
GUN|19|GUN_CDGRP|C|4|0|Cod Grupo|Cod Grupo Transp
GUN|20|GUN_DSGRP|C|50|0|Grupo Transp|Grupo Transportador
GUN|21|GUN_CDTRP|C|14|0|Transp|Transportador
GUN|22|GUN_NMTRP|C|80|0|Nome Transp|Nome do Transportador
GUN|23|GUN_MODAL|C|1|0|Modal|Modal de Transporte
GUN|24|GUN_TPPRAZ|C|1|0|Tipo Prazo|Tipo Prazo
GUN|25|GUN_PRAZO|N|3|0|Prazo|Prazo Máximo de Entrega
GUN|26|GUN_DMEST|N|6|1|Dist Estimad|Distância Estimada em KM
GUN|27|GUN_PRIOR|N|3|0|Prioridade|Nível de Prioridade
GUN|28|GUN_CDCLFR|C|4|0|Class Frete|Classificacao de Frete
GUN|29|GUN_DSCLFR|C|50|0|Desc Class|Descricao Classific Frete
GUN|30|GUN_MAXQBR|N|5|2|% Max Quebra|% máximo quebra de peso
GUN|31|GUN_FRTPES|N|8|2|Frete Peso|Frete Peso de Referência
GUN|32|GUN_PERIMP|N|5|2|Aliq Imposto|Alíquota de Imposto
GUN|33|GUN_ENVIAE|C|1|0|Soli Cot|Solicita Cotação?
GUN|34|GUN_EMAIL|C|50|0|Email|Email Solicitação
GUN|35|GUN_PERIOD|N|2|0|Período|Período de Solicitação
GUN|36|GUN_STATUS|C|1|0|Sit Solicit|Situação Solicitação
GUN|37|GUN_DTATU|D|8|0|Data Atu|Data Ultima Atualização
GUN|38|GUN_HRATU|C|5|0|Hora Atu|Hora Última Atualização
GUN|39|GUN_IMPINC|C|1|0|Imposto Inc|Imposto Incluído?
GUN|40|GUN_TPREF|C|1|0|Tipo Ref|Tipo Referência
GUN|41|GUN_PERVIG|C|1|0|Prox Vigenc|Periodo Prox Vigencia
GUN|42|GUN_QTDANT|N|2|0|Qtd Dias Ant|Qtde Dias Antecedência
GUN|43|GUN_QTDPRZ|N|2|0|Qtd Prz Resp|Qtde Prazo Resposta
GUN|44|GUN_QTDLEM|N|2|0|Dias Lembret|Qtde Dias Lembrete
GUN|45|GUN_TPFREQ|C|1|0|Tipo Freq|Tipo Frequência
GUN|46|GUN_RECOR|C|1|0|Recorrência|Controle da Recorrência
GUN|47|GUN_SOLMOD|C|1|0|Modo Solicit|Modo de Solicitação
GUN|48|GUN_SOLSIT|C|1|0|Sit Solicit|Situação da Solicitação
GUN|49|GUN_WFSIT|C|1|0|Sit Env WF|Situaçao Envio Workflow
GUN|50|GUN_UMPESO|C|2|0|Unid Peso|Unidade Med Peso
GUN|51|GUN_SOLDTP|D|8|0|Dat Prox Sol|Data Próxima Solicitação
GUN|52|GUN_SOLDTS|D|8|0|Dat Soli Sol|Data Efetuada Solicitação
GUN|53|GUN_SOLDTU|D|8|0|Dat Lim Res|Data Limite Resposta
GUN|54|GUN_SOLDTL|D|8|0|Dat Env Lemb|Data Envio Lembrete
GUN|55|GUN_SOLDTB|D|8|0|Dat Lembrado|Data Lembrado
GUN|56|GUN_SOLDTR|D|8|0|Dat Resposta|Data Resposta
GUN|57|GUN_SOLDTE|D|8|0|Dat Resp Exp|Data Resposta Expirada
GUN|58|GUN_SOLEMI|C|254|0|Comunicar|Destinatários Comunicação
GUN|59|GUN_SOLMFE|C|254|0|Falha Env WF|Falha Envio Workflow
GUN|60|GUN_CRIUSU|C|10|0|Usuar Cria|Usuário Criação
GUN|61|GUN_CRIDAT|D|8|0|Data Cria|Data Criação
GUN|62|GUN_ALTUSU|C|10|0|Usuar Alt|Usuário Alteração
GUN|63|GUN_ALTDAT|D|8|0|Data Alt|Data Alteração

