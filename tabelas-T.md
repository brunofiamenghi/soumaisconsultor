## Módulo: SIGAPCP (Planejamento e Controle da Produção)
--- ### T4C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4C|01|T4C_FILIAL|C|6|0|Filial|Filial do sistema
T4C|02|T4C_CALEND|C|10|0|Calendário|Calendário
T4C|03|T4C_LOCGRP|C|15|0|Grupo Arm|Grupo de Armazéms
--- ### T4D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4D|01|T4D_FILIAL|C|6|0|Filial|Filial do Sistema
T4D|02|T4D_COD|C|15|0|Código|Código do Produto
T4D|03|T4D_COMP|C|15|0|Componente|Código do Componente
T4D|04|T4D_DESC|C|70|0|Descrição|Descrição do Componente
T4D|05|T4D_TRT|C|3|0|Sequência|Sequência
T4D|06|T4D_QUANT|N|12|6|Quantidade|Quantidade
T4D|07|T4D_PERDA|N|5|2|Índice Perda|Índice de Perda
T4D|08|T4D_INI|D|8|0|Dt Inicial|Data Inicial da Validade
T4D|09|T4D_FIM|D|8|0|Dt Final|Data Final da Validade
T4D|10|T4D_OBSERV|C|45|0|Observação|Observações do Produto
T4D|11|T4D_FIXVAR|C|1|0|Qtd. Fix/Var|Qtde. Estr. Fixa/Variável
T4D|12|T4D_GROPC|C|3|0|Grupo Opcio.|Grupo de Opcionais
T4D|13|T4D_OPC|C|4|0|Item Opcion.|Item do Gr. de Opcionais
T4D|14|T4D_REVINI|C|3|0|Rev. Inicial|Revis. Inicial Componente
T4D|15|T4D_REVFIM|C|3|0|Rev. Final|Rev. Final do Componente
T4D|16|T4D_NV|C|2|0|Nível|Nível do Produto
T4D|17|T4D_NVINV|C|2|0|Nível Invert|Nível Invertido
T4D|18|T4D_POTENC|N|6|2|Potência|Potência do Lote
T4D|19|T4D_OK|C|4|0|Ok|Substituir Componentes
T4D|20|T4D_TIPVEC|C|6|0|Tipo Vetor|Tipo do Vetor
T4D|21|T4D_VECTOR|C|6|0|Vetor|Vetor
T4D|22|T4D_VLCOMP|C|1|0|Vl.Com.Perda|Valor Comercial da perda
T4D|23|T4D_LOCCON|C|2|0|Armazém|Armazém de Consumo
T4D|24|T4D_FANTAS|C|1|0|Fantasma ?|Componente Fantasma ?
T4D|25|T4D_CTALTE|C|10|0|Con.Alt.Eng.|Cod.Cont.Alt.Engenharia
T4D|26|T4D_LISTA|C|10|0|Lista|Lista de Componentes
T4D|27|T4D_USAALT|C|1|0|Usa Altern.?|Usa Alternativo ?
T4D|28|T4D_DTALT|D|8|0|Data Alter.|Data de Alteração
T4D|29|T4D_HRALT|C|8|0|Hora Alter.|Horário de Alteração
T4D|30|T4D_ALTPRG|C|8|0|Prog Alter.|Programa alterador
T4D|31|T4D_USRALT|C|8|0|Usua. Alter.|Usário da Alteração
--- ### T4E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4E|01|T4E_FILIAL|C|6|0|Filial|Código da Filial
T4E|02|T4E_MESAPU|C|2|0|Mês SPED|Mês Apuração SPED
T4E|03|T4E_ANOAPU|C|4|0|Ano SPED|Ano apuração SPED
T4E|04|T4E_REG|C|4|0|Registro|Código do Registro
T4E|05|T4E_OP|C|14|0|Ord. Prod.|Ordem de Produção
T4E|06|T4E_PRODUT|C|15|0|Produto|Código do Produto
T4E|07|T4E_DTSAID|D|8|0|Data Saida|Data Saída Estoque
T4E|08|T4E_QTSAID|N|16|6|Qtd. Saída|Qtd. Saída Estoque
T4E|09|T4E_DTRET|D|8|0|Data Retorno|Data Retorno Estoque
T4E|10|T4E_QTRET|N|16|6|Qtd. Retorno|Qtd. Retorno Estoque
T4E|11|T4E_PRGORI|C|10|0|Prog. Orig.|Programa Origem
T4E|12|T4E_SEMRET|C|1|0|Sem Retrab|Sem Produto Retrabalho
--- ### T4F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4F|01|T4F_FILIAL|C|6|0|Filial|Filial do Sistema
T4F|02|T4F_MESAPU|C|2|0|Mês SPED|Mês apuração SPED
T4F|03|T4F_ANOAPU|C|4|0|Ano SPED|Ano apuração SPED
T4F|04|T4F_REG|C|4|0|Registro|Código do Registro
T4F|05|T4F_PRODUT|C|15|0|Produto|Código do Produto
T4F|06|T4F_QTDCON|N|16|6|Qt. Cons.|Quantidade Consumida
T4F|07|T4F_QTDRET|N|16|6|Qtd. Ret.|Quantidade Retornada
T4F|08|T4F_OP|C|14|0|Ord. Prod,|Ordem de Produção
T4F|09|T4F_PRGORI|C|10|0|Prog. Orig.|Programa Origem
--- ### T4G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4G|01|T4G_FILIAL|C|6|0|Filial|Código da Filial
T4G|02|T4G_MESSPE|C|2|0|Mês SPED|Mês apuração SPED
T4G|03|T4G_ANOSPE|C|4|0|Ano SPED|Ano de apuração SPED
T4G|04|T4G_REG|C|4|0|Registro|Código do Registro
T4G|05|T4G_DT_INI|C|8|0|Dt Ini|Data Inicial
T4G|06|T4G_DT_FIN|C|8|0|Dt Fim|Data Final
T4G|07|T4G_COD_OP|C|14|0|Ord. Prod.|Ordem de Produção
T4G|08|T4G_COD_IT|C|15|0|Produto|Código do Produto
T4G|09|T4G_QTD_PO|N|16|3|Qtd Positiva|Quantidade Positiva
T4G|10|T4G_QTD_NE|N|16|3|Qtd Negativa|Quantidade Negativa
T4G|11|T4G_ORIGEM|C|1|0|Origem|Origem
T4G|12|T4G_BLK_CO|C|4|0|Blc Corrig|Bloco Corrigido
T4G|13|T4G_PRGORI|C|10|0|Prog. Orig.|Programa Origem
--- ### T4H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4H|01|T4H_FILIAL|C|6|0|Filial|Código da Filial
T4H|02|T4H_MESSPE|C|2|0|Mês SPED|Mês de apuração do SPED
T4H|03|T4H_ANOSPE|C|4|0|Ano SPED|Ano de apuração do SPED
T4H|04|T4H_REG|C|4|0|Registro|Código do Registro
T4H|05|T4H_PRODUT|C|15|0|Componente|Código do Componente
T4H|06|T4H_QTD_PO|N|16|3|Qtd Positiva|Quantidade Positiva
T4H|07|T4H_QTD_NE|N|16|3|Qtd Negativa|Quantidade Negativa
T4H|08|T4H_INS_SU|C|60|0|Insumo Subst|Insumo Substituído
T4H|09|T4H_OP|C|14|0|Ord. Prod.|Ordem de Produção
T4H|10|T4H_BLK_CO|C|4|0|Blc Corrig|Bloco Corrigido
T4H|11|T4H_CF|C|3|0|Tipo RE/DE|Tipo de Requisicao/devolu
T4H|12|T4H_PRGORI|C|10|0|Prog. Orig.|Programa Origem
--- ### T4I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4I|01|T4I_FILIAL|C|6|0|Filial|Filial do Sistema
T4I|02|T4I_NUM|C|10|0|Número|Número
T4I|03|T4I_LOCALI|C|15|0|Endereço|Endereço da Composição
T4I|04|T4I_NUMSER|C|20|0|Num de Serie|Num de Serie da Composica
T4I|05|T4I_QUANT|N|12|2|Quantidade|Quantidade
--- ### T4J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4J|01|T4J_FILIAL|C|6|0|Filial|Filial do sistema
T4J|02|T4J_DATA|D|8|0|Data|Data da demanda
T4J|03|T4J_PROD|C|90|0|Produto|Produto
T4J|04|T4J_REV|C|3|0|Revisão|Revisão
T4J|05|T4J_ORIGEM|C|1|0|Origem|Origem da demanda
T4J|06|T4J_DOC|C|30|0|Documento|Documento da demanda
T4J|07|T4J_QUANT|N|12|2|Quantidade|Quantidade
T4J|08|T4J_LOCAL|C|10|0|Armazém|Armazém
T4J|09|T4J_PROC|C|1|0|Processado?|Flag de Processamento
T4J|10|T4J_IDREG|C|200|0|ID Demanda|Identificador da demanda
T4J|11|T4J_MOPC|M|10|0|Opcionais|Opcionais da demanda
T4J|12|T4J_ERPOPC|C|80|0|Opcional ERP|Opcional do ERP
T4J|13|T4J_ERPMOP|M|10|0|M. Opcional|Opcional MEMO da demanda
T4J|14|T4J_NRMRP|C|6|0|Nr. MRP|Número Proc. MRP
T4J|15|T4J_CODE|C|15|0|Cod.Demanda|Código da Demanda
--- ### T4K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4K|01|T4K_FILIAL|C|6|0|FIlial|Filial do Sistema
T4K|02|T4K_MARK|C|2|0|Mark|Mark
T4K|03|T4K_SEQ|C|6|0|Sequência|Sequência de inclusão
T4K|04|T4K_TM|C|3|0|TP Movimento|TP Movimento
T4K|05|T4K_COD|C|15|0|Produto|Código do Produto
T4K|06|T4K_QUANT|N|12|2|Quantidade|Quantidade do Movimento
T4K|07|T4K_UM|C|2|0|Unidade|Unidade de Medida
T4K|08|T4K_OP|C|14|0|Ord Producao|Ordem de Producao
T4K|09|T4K_LOCAL|C|2|0|Armazem|Código do Armazém
T4K|10|T4K_DOC|C|9|0|Documento|Número do documento
T4K|11|T4K_EMISSA|D|8|0|DT Emissao|Data de Emissão
T4K|12|T4K_TRT|C|3|0|Sequencia|Sequencia da Estrutura
T4K|13|T4K_LOTECT|C|10|0|Lote|Lote
T4K|14|T4K_DTVALI|D|8|0|Valid. Lote|Validade do Lote inform.
T4K|15|T4K_NUMLOT|C|6|0|Sub-Lote|Sub-Lote
T4K|16|T4K_LOCALI|C|15|0|Endereço|Endereço
T4K|17|T4K_NUMSER|C|20|0|Num de Serie|Num de Serie do Produto
T4K|18|T4K_POTENC|N|6|2|Potencia Lot|Potência do Lote
T4K|19|T4K_REVISA|C|3|0|Rev. Estrutu|Revisão da Estrutura
T4K|20|T4K_TEATF|C|3|0|Tipo Entrada|Tipo de Entrada da Nota
T4K|21|T4K_DATA|D|8|0|Dt. Inclusão|Data de inclusão Apont.
T4K|22|T4K_HORA|C|5|0|Hora Inclus.|Hora da Inclusão
T4K|23|T4K_USER|C|25|0|Usuário Inc.|Usuário da inclusão
T4K|24|T4K_ORIGEM|C|7|0|Origem|Rotina de Origem
T4K|25|T4K_OPERAC|C|2|0|Operacao|Operacao
T4K|26|T4K_RECURS|C|6|0|Recurso|Recurso
T4K|27|T4K_FERRAM|C|6|0|Ferramenta|Ferramenta
T4K|28|T4K_DATAIN|D|8|0|Data Inicial|Data Inicial
T4K|29|T4K_HORAIN|C|5|0|Hora Inicial|Hora Inicial
T4K|30|T4K_DATAFI|D|8|0|DT Final|Data Final
T4K|31|T4K_HORAFI|C|5|0|Hora Final|Hora Final
T4K|32|T4K_MENSAG|M|10|0|Mensagens|Mensagens de Erros
T4K|33|T4K_PARCTO|C|1|0|Parc/Total|Parcial ou total
T4K|34|T4K_PERDA|N|11|2|Perda|Perda do Movimento
T4K|35|T4K_STATUS|C|1|0|Status|Status
T4K|36|T4K_STRAUT|M|10|0|StrAuto|String Rotina Automatica
--- ### T4L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4L|01|T4L_FILIAL|C|6|0|Filial|Código da filial
T4L|02|T4L_ID|C|10|0|ID|Código identificador
T4L|03|T4L_EPC|C|24|0|EPC|Código da EPC
T4L|04|T4L_QUANT|N|14|2|Quantidade|Quantidade da EPC
T4L|05|T4L_STATUS|C|1|0|Status|Status
--- ### T4M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4M|01|T4M_FILIAL|C|6|0|Filial|Filial do sistema
T4M|02|T4M_PROD|C|90|0|Produto|Produto
T4M|03|T4M_DTINI|D|8|0|Data Inicial|Data Inicial
T4M|04|T4M_DTFIN|D|8|0|Data Final|Data Final
T4M|05|T4M_QNTDE|N|12|2|Quant. De|Quantidade De:
T4M|06|T4M_QNTATE|N|12|2|Quant. Até|Quantidade Até:
T4M|07|T4M_REV|C|3|0|Revisão|Revisão
T4M|08|T4M_IDREG|C|200|0|ID Versão|ID Versão da Produção
T4M|09|T4M_ROTEIR|C|2|0|Roteiro|Roteiro
T4M|10|T4M_ARMCON|C|10|0|Arm. Consumo|Armazém de consumo
--- ### T4N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4N|01|T4N_FILIAL|C|6|0|Filial|Filial do sistema
T4N|02|T4N_PROD|C|90|0|Produto|Código do produto pai
T4N|03|T4N_QTDB|N|7|0|Qtd. Base|Quantidade base
T4N|04|T4N_COMP|C|90|0|Componente|Código do componente
T4N|05|T4N_SEQ|C|10|0|Sequência|Sequência do componente
T4N|06|T4N_REVINI|C|3|0|Rev. Ini.|Revisão inicial
T4N|07|T4N_REVFIM|C|3|0|Rev. Fim|Revisão final
T4N|08|T4N_QTD|N|12|6|Quantidade|Quantidade necessária
T4N|09|T4N_DTINI|D|8|0|Vld. Inicial|Validade inicial
T4N|10|T4N_DTFIM|D|8|0|Vld. Final|Validade final
T4N|11|T4N_PERDA|N|5|2|% Perda|Percentual de perda
T4N|12|T4N_FIXA|C|1|0|Fixa?|Quantidade fixa?
T4N|13|T4N_GROPC|C|3|0|Grupo|Grupo de opcionais
T4N|14|T4N_ITOPC|C|4|0|Item|Item opcional
T4N|15|T4N_POTEN|N|6|2|Potência|Potência de lote
T4N|16|T4N_ARMCON|C|10|0|Armazém|Armazém de consumo
T4N|17|T4N_FANTAS|L|1|0|Fantasma|Produto Fantasma
T4N|18|T4N_IDREG|C|200|0|Id. Registro|Id. do Registro
--- ### T4O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4O|01|T4O_FILIAL|C|6|0|Filial|Filial do sistema
T4O|02|T4O_ALTERN|C|90|0|Alternativo|Produto alternativo
T4O|03|T4O_TPCONV|C|1|0|Conversão|Tipo de conversão
T4O|04|T4O_FATCON|N|6|2|Fator|Fator de conversão
T4O|05|T4O_DATA|D|8|0|Vigência|Data de Vigência
T4O|06|T4O_ESTOQ|C|1|0|Estoque|Utilização de alternativo
T4O|07|T4O_SEQ|C|2|0|Sequência|Sequência de utilização
T4O|08|T4O_IDEST|C|200|0|ID Est.|ID Estrutura
--- ### T4P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4P|01|T4P_FILIAL|C|6|0|Filial|Filial do Sistema
T4P|02|T4P_API|C|60|0|API|Identificador da API
T4P|03|T4P_TPEXEC|C|1|0|Tipo Exec.|Tipo de execução da API
T4P|04|T4P_ATIVO|C|1|0|Ativo ?|Integração Ativa ?
T4P|05|T4P_ALTER|C|1|0|Alteração?|Indicador de alteração
--- ### T4Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4Q|01|T4Q_FILIAL|C|6|0|Filial|Filial do Sistema
T4Q|02|T4Q_PROD|C|90|0|Produto|Produto da Ordem
T4Q|03|T4Q_LOCAL|C|10|0|Armazém|Armazém de produção
T4Q|04|T4Q_QUANT|N|15|3|Quantidade|Quantidade de produção
T4Q|05|T4Q_SALDO|N|15|3|Saldo Ordem|Saldo da Ordem
T4Q|06|T4Q_DATPRI|D|8|0|Data Inicio|Data de Inicio da Ordem
T4Q|07|T4Q_DATA|D|8|0|Data entrega|Data de entrega
T4Q|08|T4Q_MOPC|M|10|0|Opcional|Opcional
T4Q|09|T4Q_TIPO|C|1|0|Tipo Ordem|Tipo de Ordem de Produção
T4Q|10|T4Q_IDREG|C|200|0|Id Ordem|ID da Ordem de Produção
T4Q|11|T4Q_SITUA|C|1|0|Situação|Situação da OP
T4Q|12|T4Q_OP|C|14|0|Ordem Prod.|Número da Ordem de Prod.
T4Q|13|T4Q_OPPAI|C|14|0|OP Pai|Ordem de Producao Pai
T4Q|14|T4Q_ERPOPC|C|80|0|Opcional|Opcional
T4Q|15|T4Q_ERPMOP|M|10|0|Memo OPC|Memo Opcional
T4Q|16|T4Q_PATHOP|M|10|0|Path OP|Path estrutura da OP
--- ### T4R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4R|01|T4R_FILIAL|C|6|0|Filial|Filial do sistema
T4R|02|T4R_API|C|60|0|API|API Integradora
T4R|03|T4R_STATUS|C|1|0|Status|Status do registro
T4R|04|T4R_IDREG|C|200|0|Id Registro|Id do registro do MRP
T4R|05|T4R_DTENV|D|8|0|Data Envio|Data de envio do registro
T4R|06|T4R_HRENV|C|8|0|Hora Envio|Horário do envio
T4R|07|T4R_PROG|C|10|0|Programa|Programa integrador
T4R|08|T4R_MSGRET|C|200|0|Retorno|Mensagem de retorno
T4R|09|T4R_DTREP|D|8|0|Data Reproc|Data de Reprocessamento
T4R|10|T4R_HRREP|C|8|0|Hora Reproc|Horário Reprocessamento
T4R|11|T4R_MSGENV|M|10|0|Mensg. Env.|Mensagem enviada
T4R|12|T4R_TIPO|C|1|0|Tipo|Tipo do movimento
T4R|13|T4R_DADOS|M|10|0|Dados env.|Dados pendentes de envio
T4R|14|T4R_IDPRC|C|36|0|ID Processo|Identificador de processo
--- ### T4S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4S|01|T4S_FILIAL|C|6|0|Filial|Filial do Sistema
T4S|02|T4S_PROD|C|90|0|Produto|Produto empenhado
T4S|03|T4S_OP|C|14|0|Ordem Prod.|Ordem de produção
T4S|04|T4S_OPORIG|C|14|0|OP Origem|Ordem de Produçao Origem
T4S|05|T4S_DT|D|8|0|Data Empenho|Data do Empenho
T4S|06|T4S_SEQ|C|10|0|Sequência|Sequência do empenho
T4S|07|T4S_QTD|N|15|3|Quantidade|Quantidade do empenho
T4S|08|T4S_QSUSP|N|15|3|Qtd. Suspen.|Quantidade Suspensa
T4S|09|T4S_LOCAL|C|10|0|Armaz.Cons|Armazém de consumo
T4S|10|T4S_IDREG|C|200|0|Id Empenho|Id. do Empenho
--- ### T4T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4T|01|T4T_FILIAL|C|6|0|Filial|Filial do sistema
T4T|02|T4T_NUM|C|6|0|Solicitação|Solicitação de Compras
T4T|03|T4T_SEQ|C|4|0|Sequência|Sequência
T4T|04|T4T_PROD|C|90|0|Produto|Código do Produto
T4T|05|T4T_OP|C|14|0|Ord.Produção|Ordem de Produção
T4T|06|T4T_DTENT|D|8|0|Data Entrega|Data de Entrega
T4T|07|T4T_QTD|N|15|3|Quantidade|Quantidade
T4T|08|T4T_QUJE|N|15|3|Qtde. em Ped|Quantidade em Pedido
T4T|09|T4T_LOCAL|C|10|0|Armazem|Armazem de recebimento
T4T|10|T4T_TIPO|C|1|0|Tipo|Tipo da Solicitacacao
T4T|11|T4T_IDREG|C|200|0|Id Solicitaç|ID Solicitação
T4T|12|T4T_APROV|C|1|0|Flag Aprov|Flag Aprovação
T4T|13|T4T_ITGRD|C|3|0|Item Grade|Item Grade
T4T|14|T4T_DOCUM|C|13|0|Documento|Documento
--- ### T4U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4U|01|T4U_FILIAL|C|6|0|Filial|Filial do Sistema
T4U|02|T4U_NUM|C|6|0|Num. Pedido|Número do pedido
T4U|03|T4U_SEQ|C|4|0|Sequência|Sequência
T4U|04|T4U_PROD|C|90|0|Produto|Produto
T4U|05|T4U_OP|C|14|0|Ordem Prod.|Ordem de Produção
T4U|06|T4U_DTENT|D|8|0|Data Entrega|Data de Entrega
T4U|07|T4U_QTD|N|15|3|Quantidade|Quantidade
T4U|08|T4U_QUJE|N|15|3|Quant. Atend|Quantidade Atendida
T4U|09|T4U_LOCAL|C|10|0|Armazém|Armazém de Consumo
T4U|10|T4U_TIPO|C|1|0|Tipo|Tipo da ordem de produção
T4U|11|T4U_IDREG|C|200|0|Id Pedido|Id do pedido de compra
T4U|12|T4U_ORIGEM|C|1|0|Origem Ped.|Origem Pedido de Compras
T4U|13|T4U_ITGRD|C|3|0|Item Grade|Item Grade
T4U|14|T4U_DOCUM|C|13|0|Documento|Documento
--- ### T4V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4V|01|T4V_FILIAL|C|6|0|Filial|Filial do Sistema
T4V|02|T4V_PROD|C|90|0|Produto|Produto
T4V|03|T4V_LOCAL|C|10|0|Armazém|Armazém de Estoque
T4V|04|T4V_LOTE|C|10|0|Lote|Lote
T4V|05|T4V_SLOTE|C|6|0|Sublote|Sublote
T4V|06|T4V_VALID|D|8|0|Validade|Validade
T4V|07|T4V_QTD|N|15|3|Qnt. Disp.|Quantidade Disponível
T4V|08|T4V_QNPT|N|15|3|Qnt. Em Ter.|Quantidade em Terceiros
T4V|09|T4V_QTNP|N|15|3|Qnt. De Terc|Quantidade de Terceiros
T4V|10|T4V_QTIND|N|15|3|Qnt. Indisp.|Quantidade Indisponível
T4V|11|T4V_IDREG|C|200|0|Id Registro|identificador do registro
T4V|12|T4V_SLDBQ|N|15|3|Saldo Bloq.|Saldo Bloqueado em CQ
--- ### T4W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4W|01|T4W_FILIAL|C|6|0|Filial|Código da filial
T4W|02|T4W_ID|C|10|0|ID|Identificador
T4W|03|T4W_PROD|C|15|0|Produto|Código do produto
T4W|04|T4W_LOTE|C|10|0|Lote|Lote do produto
T4W|05|T4W_SUBLOT|C|6|0|Sub-lote|Sub-lote do produto
T4W|06|T4W_NUMSER|C|20|0|Série|Número de série
T4W|07|T4W_QTTRAN|N|14|2|Quantidade|Quantidade a transferir
--- ### T4X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4X|01|T4X_FILIAL|C|6|0|Filial|Filial do Sistema
T4X|02|T4X_PROG|C|10|0|Programação|Código da Programação
T4X|03|T4X_STATUS|C|1|0|Status|Status da Programação
T4X|04|T4X_USER|C|6|0|Usuário|Código do Usuário
T4X|05|T4X_DTINI|D|8|0|Data inicial|Data Inicial
T4X|06|T4X_HRINI|C|8|0|Hora inicial|Hora Inicial
T4X|07|T4X_DTFIM|D|8|0|Data final|Data Final
T4X|08|T4X_HRFIM|C|8|0|Hora final|Hora Final
T4X|09|T4X_REPROC|N|1|0|Pend. Reproc|Reprocessamento pendente
T4X|10|T4X_DESCRI|C|50|0|Descrição|Descrição da programação
--- ### T4Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4Y|01|T4Y_FILIAL|C|6|0|Filial|Filial do Sistema
T4Y|02|T4Y_PROG|C|10|0|Programação|Código da Programação
T4Y|03|T4Y_SEQ|N|4|0|Sequência|Sequência
T4Y|04|T4Y_PARAM|C|100|0|Parâmetro|Código do Parâmetro
T4Y|05|T4Y_VALOR|C|100|0|Valor|Valor do Parâmetro
T4Y|06|T4Y_LISTA|M|8|0|Lista|Valor Lista
--- ### T4Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4Z|01|T4Z_FILIAL|C|6|0|Filial|Filial do Sistema
T4Z|02|T4Z_PROG|C|10|0|Programação|Código da Programação
T4Z|03|T4Z_SEQ|N|2|0|Sequência|Sequência
T4Z|04|T4Z_ETAPA|C|50|0|Etapa|Código da Etapa
T4Z|05|T4Z_STATUS|C|1|0|Status|Status da Etapa
T4Z|06|T4Z_PERCT|N|6|2|Percentual|Percentual da Etapa
T4Z|07|T4Z_MSG|C|254|0|Mensagem|Mensagem
T4Z|08|T4Z_MSGDET|M|8|0|Msg. Det.|Mensagem Detalhada
T4Z|09|T4Z_DTINI|D|8|0|Data inicial|Data Inicial
T4Z|10|T4Z_DTFIM|D|8|0|Data final|Data Final
T4Z|11|T4Z_HRINI|C|8|0|Hora inicial|Hora Inicial
T4Z|12|T4Z_HRFIM|C|8|0|Hora final|Hora Final
--- ### TLE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLE|01|TLE_FILIAL|C|6|0|Filial|Filial do Sistema
TLE|02|TLE_NUMCON|C|10|0|Num. Progr.|Numero da Programacao
TLE|03|TLE_CODRES|C|12|0|Responsavel|Codigo do Responsavel
TLE|04|TLE_NOMRES|C|80|0|Nome Resp.|Nome do Responsavel
TLE|05|TLE_DTINI|D|8|0|Data Inicio|Data Inicio Programacao
TLE|06|TLE_DTFIM|D|8|0|Data Fim|Data Fim Programacao
TLE|07|TLE_DTGERA|D|8|0|Data Geracao|Data da Geracao
TLE|08|TLE_OBSERV|C|100|0|Observacao|Observacao
TLE|09|TLE_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TP0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP0|01|TP0_FILIAL|C|6|0|Filial|Filial do Sistema
TP0|02|TP0_CODGRP|C|3|0|Cod. Grupo|Codigo Grupo
TP0|03|TP0_NOMGRP|C|40|0|Nome Grupo|Nome do Grupo
TP0|04|TP0_DESGRP|M|10|0|Descricao|Descricao
TP0|05|TP0_CODPRO|C|10|0|Cd. Programa|Codigo do Programa
--- ### TP1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP1|01|TP1_FILIAL|C|6|0|Filial|Filial do Sistema
TP1|02|TP1_CODBEM|C|16|0|Bem|Codigo do Bem
TP1|03|TP1_SERVIC|C|6|0|Servico|Codigo do Servico
TP1|04|TP1_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
TP1|05|TP1_TAREFA|C|6|0|Tarefa|Tarefa da Manutencao
TP1|06|TP1_ETAPA|C|6|0|Etapa|Codigo da Etapa da Tarefa
TP1|07|TP1_OPCAO|C|15|0|Opcao|Opcao da Etapa
TP1|08|TP1_TIPRES|C|1|0|Tp. Resposta|Tipo de Resposta
TP1|09|TP1_CONDOP|C|2|0|Operador|Operador   da Condicao
TP1|10|TP1_CONDIN|C|10|0|Informacao|Informacao da Condicao
TP1|11|TP1_TIPCAM|C|1|0|Tp.Campo Res|Tipo de Campo de Resposta
TP1|12|TP1_TPMANU|C|1|0|Tipo Manut.|Tipo Manutencao a Gerar
TP1|13|TP1_BEMIMN|C|16|0|Bem Manut.|Bem da Manutencao
TP1|14|TP1_SERVMN|C|6|0|Servico Man.|Servico da Manutencao
TP1|15|TP1_SEQUMN|N|3|0|Sequenc Man.|Sequencia da Manutencao
TP1|16|TP1_BLOQMA|C|1|0|Bloq.Produto|Bloqueia Produto
TP1|17|TP1_BLOQFU|C|1|0|Bloq.Funcion|Bloqueia Funcionario
TP1|18|TP1_BLOQFE|C|1|0|Bloq.Ferram.|Bloqueia Ferramenta
TP1|19|TP1_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TP1|20|TP1_SEQRMN|C|3|0|Seq.Manut.|Sequencia da Manutencao
TP1|21|TP1_FORMUL|C|80|0|Fórmula|Fórmula do Item
TP1|22|TP1_DESOPC|C|20|0|Descrição|Descrição do Item
--- ### TP2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP2|01|TP2_FILIAL|C|6|0|Filial|Filial do Sistema
TP2|02|TP2_CODFAM|C|6|0|Familia|Codigo da Familia
TP2|03|TP2_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TP2|04|TP2_SERVIC|C|6|0|Servico|Codigo do Servico
TP2|05|TP2_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
TP2|06|TP2_TAREFA|C|6|0|Tarefa|Tarefa da Manutencao
TP2|07|TP2_ETAPA|C|6|0|Etapa|Codigo da Etapa da Tarefa
TP2|08|TP2_OPCAO|C|15|0|Opcao|Opcao da Etapa
TP2|09|TP2_TIPRES|C|1|0|Tp. Resposta|Tipo de Resposta
TP2|10|TP2_CONDOP|C|2|0|Operador|Operador   da Condicao
TP2|11|TP2_CONDIN|C|10|0|Informacao|Informacao da Condicao
TP2|12|TP2_TIPCAM|C|1|0|Tp.Campo Res|Tipo de Campo de Resposta
TP2|13|TP2_TPMANU|C|1|0|Tipo Manut.|Tipo Manutencao a Gerar
TP2|14|TP2_SERVMN|C|6|0|Servico Man.|Servico da Manutencao
TP2|15|TP2_PORBEM|C|1|0|Para o Bem|Para que Bem gerar O.S.
TP2|16|TP2_DESCRI|C|20|0|Descricao|Descricao
TP2|17|TP2_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TP2|18|TP2_FORMUL|C|80|0|Fórmula|Fórmula do Item
TP2|19|TP2_DESOPC|C|20|0|Descrição|Descrição do Item
--- ### TP3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP3|01|TP3_FILIAL|C|6|0|Filial|Filial do Sistema
TP3|02|TP3_CONTRA|C|8|0|Contrato|Codigo do Contrato
TP3|03|TP3_DESCRI|C|40|0|Descricao|Descricao do Contrato
TP3|04|TP3_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TP3|05|TP3_LOJA|C|2|0|Loja|Loja Fornecedor
TP3|06|TP3_NOMFOR|C|80|0|Nome Fornec|Nome do Fornecedor
TP3|07|TP3_VALOR|N|12|2|Valor|Valor do Contrato
--- ### TP4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP4|01|TP4_FILIAL|C|6|0|Filial|Filial do Sistema
TP4|02|TP4_CODIGO|C|6|0|Codigo|Codigo da Equipe
TP4|03|TP4_DESCRI|C|30|0|Nome Equipe|Nome da Equipe
TP4|04|TP4_CODRES|C|6|0|Responsavel|Codigo do Responsavel
TP4|05|TP4_DESRES|C|30|0|Nome Resp.|Nome do Responsavel
TP4|06|TP4_BLOQPT|C|1|0|Bloq. Porta.|Bloqueia Portaria
TP4|07|TP4_TEMPOM|C|5|0|Tempo Medio|Tempo Medio
--- ### TP5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP5|01|TP5_FILIAL|C|6|0|Filial|Filial do Sistema
TP5|02|TP5_CODFAM|C|6|0|Familia|Codigo da Familia
TP5|03|TP5_SERVIC|C|6|0|Servico|Codigo do Servico
TP5|04|TP5_SEQREL|C|3|0|Sequen.Rel.|Sequencia Relacionamento
TP5|05|TP5_TAREFA|C|6|0|Tarefa|Codigo da Tarefa
TP5|06|TP5_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TP5|07|TP5_DESCRI|C|40|0|Descrição|Descricao da Tarefa
TP5|08|TP5_DOCFIL|C|6|0|Filial Proc.|Filial Procedimento
TP5|09|TP5_DOCTO|C|16|0|Procedimento|Procedimento Manutencao
TP5|10|TP5_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TP5|11|TP5_TEENMA|N|3|0|Tempo Manut.|Tempo Entre Manutenções
TP5|12|TP5_UNENMA|C|1|0|Unid. Manut.|Unidade Tempo Manutenção
TP5|13|TP5_INENMA|N|6|0|Incr. Manut.|Incremento entre Manut.
--- ### TP6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP6|01|TP6_FILIAL|C|6|0|Filial|Filial do Sistema
TP6|02|TP6_EQUIPE|C|6|0|Equipe|Codigo da Equipe
TP6|03|TP6_CALEND|C|3|0|Calendario|Calendario Utilizado
TP6|04|TP6_DESCAL|C|30|0|Descricao|Descricao do Calendario
TP6|05|TP6_DTINI|D|8|0|Data Inicial|Data Inicial do Bloqueio
TP6|06|TP6_DTFIM|D|8|0|Data Final|Data Final do Bloqueio
--- ### TP7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP7|01|TP7_FILIAL|C|6|0|Filial|Filial do Sistema
TP7|02|TP7_CODIRE|C|3|0|Cod. Irreg.|Codigo da Irregularidade
TP7|03|TP7_NOME|C|40|0|Nome|Nome da Irregularidade
TP7|04|TP7_GRAVID|C|1|0|Gravidade|Gravidade
TP7|05|TP7_DESCRI|M|10|0|Descricao|Descricao
TP7|06|TP7_QTDALE|N|3|0|Qtd p/Alerta|Quantidade para Alerta
TP7|07|TP7_QTDTMP|N|4|0|Qtd Tempo|Quantidade de Tempo
TP7|08|TP7_UNDTMP|C|1|0|Und. Tempo|Unidade de Tempo
--- ### TP8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP8|01|TP8_FILIAL|C|6|0|Filial|Filial do Sistema
TP8|02|TP8_CODBEM|C|16|0|Cod. Bem|Codigo do Bem
TP8|03|TP8_NOMBEM|C|30|0|Nome Bem|Nome do Bem
TP8|04|TP8_CODIRE|C|3|0|Cod. Irreg.|Codigo da Irregularidade
TP8|05|TP8_NOMIRE|C|30|0|Nome Irreg.|Nome da Irregularidade
TP8|06|TP8_DTOCOR|D|8|0|Dt. Ocorrenc|Data da Ocorrencia
TP8|07|TP8_HROCOR|C|5|0|Hr. Ocorrenc|Hora da Ocorrencia
TP8|08|TP8_ORIGEM|C|1|0|Origem|Origem
--- ### TP9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TP9|01|TP9_FILIAL|C|6|0|Filial|Filial do Sistema
TP9|02|TP9_CODFAM|C|6|0|Família|Codigo da Familia do Bem
TP9|03|TP9_FAMINO|C|20|0|Nome Família|Nome da familia
TP9|04|TP9_NOME|C|40|0|Nome|Nome do Bem
TP9|05|TP9_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TP9|06|TP9_CUSTNO|C|20|0|Descrição|Nome do Centro Custo
TP9|07|TP9_CALEND|C|3|0|Turno|Turno Trabalho
TP9|08|TP9_CALENO|C|20|0|Nome Turno|Nome do Turno
TP9|09|TP9_CENTRA|C|6|0|Centro Trab.|Centro Trabalho
TP9|10|TP9_CTRANO|C|20|0|Nome C. Trab|Nome do C. Trabalho
TP9|11|TP9_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TP9|12|TP9_LOJA|C|2|0|Loja|Loja do Fornecedor
TP9|13|TP9_FORNNO|C|80|0|Nome Fornec.|Nome Fornecedor
TP9|14|TP9_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TP9|15|TP9_DESMOD|C|20|0|Descrição|Descricao Tipo do Modelo
TP9|16|TP9_FABRIC|C|6|0|Fabricante|Codigo do Fabricante
TP9|17|TP9_FABRNO|C|20|0|Nome Fabric.|Nome do Fabricante
TP9|18|TP9_MODELO|C|10|0|Modelo|Modelo do Bem
TP9|19|TP9_SERIE|C|15|0|Série|Numero Serie do Bem
TP9|20|TP9_CODEST|C|15|0|Estoque|Codigo no Estoque
TP9|21|TP9_ESTQNO|C|70|0|Nome Estoque|Nome Estoque
TP9|22|TP9_PRIORI|C|3|0|Prioridade|Prioridade na Producao
TP9|23|TP9_MOVBEM|C|1|0|Movim. Bem|Indica Bem é Movimentado
TP9|24|TP9_CUSTOH|N|9|2|Custo Hora|Custo Hora do Bem
TP9|25|TP9_TEMCON|C|1|0|Tem Contador|Bem possui Contador
TP9|26|TP9_TPCONT|C|20|0|Tipo Cont.|Tipo de Contador
TP9|27|TP9_PERACO|N|3|0|Per. Acomp.|Periodo Entre Acompanh.
TP9|28|TP9_UNIACO|C|1|0|Unid. Medida|Unidade do Periodo Acomp.
TP9|29|TP9_BITMAP|C|8|0|Imagem|Imagem do Bem
TP9|30|TP9_DESCRI|M|10|0|Descrição|Descricao do Bem
TP9|31|TP9_ACOPLA|C|1|0|Acoplamento|Permite Acoplamento
TP9|32|TP9_VALANO|N|9|2|Val. Ac. Ano|Val. Estimat. Gasto Anual
--- ### TPA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPA|01|TPA_FILIAL|C|6|0|Filial|Filial do Sistema
TPA|02|TPA_ETAPA|C|6|0|Etapa|Codigo da Etapa
TPA|03|TPA_DESCRI|C|150|0|Descrição|Descricao da Etapa
TPA|04|TPA_DOCFIL|C|6|0|Filial Docto|Filial Documentacao
TPA|05|TPA_DOCTO|C|16|0|Documento|Documentacao Etapa Manut
TPA|06|TPA_CDAREA|C|6|0|Área Manut.|Codigo Area de Manutencao
TPA|07|TPA_NOAREA|C|20|0|Nome da Área|Nome da Area do servico
TPA|08|TPA_OPCOES|C|1|0|Tipo Opção|Tipo de Opcoes  resposta
TPA|09|TPA_FORMUL|M|10|0|Formula Calc|Formula de Calculo
TPA|10|TPA_TEMPOM|C|5|0|Tempo Médio|Tempo Medio
TPA|11|TPA_BLOQPT|C|1|0|Bloq. Porta.|Bloqueia Portaria
--- ### TPB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPB|01|TPB_FILIAL|C|6|0|Filial|Filial do Sistema
TPB|02|TPB_CODFAM|C|6|0|Familia|Codigo da Familia
TPB|03|TPB_CARACT|C|6|0|Caract.|Codigo da Caracteristica
TPB|04|TPB_NOMETT|C|40|0|Descrição|Descricao Caracteristica
TPB|05|TPB_CONDOP|C|1|0|Operador|Operador
TPB|06|TPB_DETALH|C|15|0|Detalhe 1|Detalhe da Caracteristica
TPB|07|TPB_INFO02|C|15|0|Detalhe 2|Detalhe 2
TPB|08|TPB_UNIDAD|C|2|0|Unidade|Unidade da Caracteristica
TPB|09|TPB_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
--- ### TPC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPC|01|TPC_FILIAL|C|6|0|Filial|Filial do Sistema
TPC|02|TPC_ETAPA|C|6|0|Etapa|Etapa
TPC|03|TPC_OPCAO|C|15|0|Opções|Opcao da Etapa
TPC|04|TPC_DESOPC|C|20|0|Descrição|Descrição do Item
TPC|05|TPC_CONDOP|C|2|0|Operador|Operador da Condicao
TPC|06|TPC_CONDIN|C|10|0|Informações|Valor de Comparacao
TPC|07|TPC_TIPRES|C|1|0|Tipo|Tipo de Resposta
TPC|08|TPC_TPMANU|C|1|0|Ação|Tipo de Manutencao  gerar
TPC|09|TPC_SERVIC|C|6|0|Serviço|Servico da Manutencao
TPC|10|TPC_PORBEM|C|1|0|Gera Para|Para que Bem gerar O.S.
TPC|11|TPC_DESCRI|C|20|0|Descrição|Descricao
TPC|12|TPC_TIPCAM|C|1|0|Tipo Campo|Tipo de Campo de Resposta
TPC|13|TPC_FORMUL|C|80|0|Fórmula|Fórmula do Item
TPC|14|TPC_PERCEN|N|6|2|Perc. Aviso|Percent. p/dispara Aviso
TPC|15|TPC_OBSERV|C|40|0|Msg. Alerta|Mensagem de Alerta
--- ### TPD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPD|01|TPD_FILIAL|C|6|0|Filial|Filial do Sistema
TPD|02|TPD_CODBEM|C|16|0|Bem|Codigo do Bem
TPD|03|TPD_ETAPA|C|6|0|Etapa|Codigo da Etapa
TPD|04|TPD_DTULTM|D|8|0|Dt.Ult.Manut|Data da Ultima Manutencao
TPD|05|TPD_POSCON|N|9|0|Pos.Contador|Pos.Contad.Ult.Manutencao
--- ### TPE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPE|01|TPE_FILIAL|C|6|0|Filial|Filial do Sistema
TPE|02|TPE_CODBEM|C|16|0|Bem|Codigo do Bem
TPE|03|TPE_TPCONT|C|20|0|Tipo Cont.|Tipo do Contador
TPE|04|TPE_POSCON|N|9|0|Pos.Contador|Posicao Atual do Contador
TPE|05|TPE_DTULTA|D|8|0|Últ. Acomp.|Data Ult. Acompanhamento
TPE|06|TPE_VARDIA|N|6|0|Variação Dia|Variacao Media Dia Cont.
TPE|07|TPE_LIMICO|N|9|0|Limite Cont.|Limite Superior Contador
TPE|08|TPE_CONTAC|N|12|0|Cont. Acum.|Contador Acumulado
TPE|09|TPE_VIRADA|N|6|0|Viradas Cont|Viradas do Contador
TPE|10|TPE_AJUSCO|N|9|0|Ajuste Cont.|Valor Ajuste do Contador
TPE|11|TPE_CONTGA|N|9|0|Cont.Garant.|Contador da Garantia
TPE|12|TPE_SITUAC|C|1|0|Situação|Situação do Contador
--- ### TPF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPF|01|TPF_FILIAL|C|6|0|Filial|Filial do Sistema
TPF|02|TPF_CODFAM|C|6|0|Família|Codigo da Familia Padrao
TPF|03|TPF_NOMFAM|C|40|0|Nome Família|Nome da Familia Padrao
TPF|04|TPF_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TPF|05|TPF_DESMOD|C|20|0|Descrição|Descricao Tipo do Modelo
TPF|06|TPF_SEQREL|C|3|0|Sequência|Sequencia Relacionamento
TPF|07|TPF_SERVIC|C|6|0|Serviço|Codigo do Servico
TPF|08|TPF_NOMSER|C|40|0|Nome Serviço|Nome do Servico
TPF|09|TPF_NOMEMA|C|40|0|Nome Manut.|Nome da Manutencao
TPF|10|TPF_CODARE|C|6|0|Área Manut.|Codigo Area de Manutencao
TPF|11|TPF_NOMARE|C|30|0|Nome da Área|Nome da Area do servico
TPF|12|TPF_TIPO|C|3|0|Tipo Manut.|Codigo do Tipo Manutencao
TPF|13|TPF_NOMTIP|C|40|0|Nome do Tipo|Nome do Tipo do servico
TPF|14|TPF_CALEND|C|3|0|Calendario|Calendario da Manutencao
TPF|15|TPF_NOMCAL|C|30|0|Nome Calend.|Nome do Calendario
TPF|16|TPF_TIPACO|C|1|0|Tipo Acomp.|Tipo do Acompanhamento
TPF|17|TPF_PRIORI|C|3|0|Prioridade|Prioridade da Manutencao
TPF|18|TPF_PARADA|C|1|0|Parada Bem|Indicacao de Parada Bem
TPF|19|TPF_TEPAAN|N|3|0|Parada Antes|Tempo Parada Antes Manut.
TPF|20|TPF_UNPAAN|C|1|0|Un. P. Antes|Unidade Tpo. Parada Antes
TPF|21|TPF_TEPADE|N|3|0|Un. Parada|Tempo de Para Depois Manu
TPF|22|TPF_UNPADE|C|1|0|Uni.Par.Dep.|Unidade Tpo.Parada Depois
TPF|23|TPF_TEENMA|N|3|0|Tempo Manut.|Tempo Entre Manutencoes
TPF|24|TPF_UNENMA|C|1|0|Un. Manut.|Unidade Tempo Manutencao
TPF|25|TPF_INENMA|N|6|0|Incr. Manut.|Incremento Entre Manut.
TPF|26|TPF_NAOUTI|C|1|0|Dia Não Útil|Atitude Para Dia Nao Util
TPF|27|TPF_PERIOD|C|1|0|Período|Tipo de Periodo de Manut.
TPF|28|TPF_DOCFIL|C|6|0|Filial Proc.|Filial Procedimento
TPF|29|TPF_DOCTO|C|16|0|Procedimento|Procedimento Manutencao
TPF|30|TPF_DESCRI|M|10|0|Descrição|Descricao da Manutenção
TPF|31|TPF_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TPF|32|TPF_TIPLUB|C|1|0|Servico Lubr|Servico Lubrificacao
TPF|33|TPF_TOLERA|N|6|0|Toler. Tempo|Tempo Toleran OS a Vencer
TPF|34|TPF_TOLECO|N|9|0|Toler. Cont.|Tolerancia Contador
--- ### TPG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPG|01|TPG_FILIAL|C|6|0|Filial|Filial do Sistema
TPG|02|TPG_CODFAM|C|6|0|Familia|Codigo da Familia
TPG|03|TPG_SERVIC|C|6|0|Servico|Codigo do Servico
TPG|04|TPG_SEQREL|C|3|0|Sequen.Rel.|Sequencia Relacionamento
TPG|05|TPG_TAREFA|C|6|0|Tarefa|Tarefa do Servico
TPG|06|TPG_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TPG|07|TPG_NOMETA|C|40|0|Nome Tarefa|Nome da tarefa
TPG|08|TPG_TIPORE|C|1|0|Tipo Inform.|Tipo de Informacao
TPG|09|TPG_DESREG|C|13|0|Nome|Descritivo tipo Registro
TPG|10|TPG_CODIGO|C|15|0|Codigo|Codigo da Informacao
TPG|11|TPG_NOMECO|C|30|0|Desc. Código|Descricao do Codigo
TPG|12|TPG_QUANRE|N|3|0|Quant. Rec..|Quantidade de Recurso
TPG|13|TPG_QUANTI|N|9|2|Quantidade|Quant. Prevista Consumo
TPG|14|TPG_UNIDAD|C|2|0|Unid. Medida|Unidade de Medida
TPG|15|TPG_RESERV|C|1|0|Gera Reserva|Gera Reserva?
TPG|16|TPG_DESTIN|C|1|0|Destino|Destino do Produto
TPG|17|TPG_QTDGAR|N|9|0|Qtde. Garan.|Quantidade para Garantia
TPG|18|TPG_UNIGAR|C|1|0|Un. Garantia|Unidade de Garantia
TPG|19|TPG_CONGAR|C|1|0|Cont. Garan.|Contador para Garantia
TPG|20|TPG_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TPG|21|TPG_LOCAL|C|2|0|Almoxarifado|Codigo do Almoxarifado
TPG|22|TPG_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
TPG|23|TPG_LOJA|C|2|0|Loja|Código da Loja
--- ### TPH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPH|01|TPH_FILIAL|C|6|0|Filial|Filial do Sistema
TPH|02|TPH_CODFAM|C|6|0|Familia|Codigo da Familia
TPH|03|TPH_SERVIC|C|6|0|Servico|Codigo do Servico
TPH|04|TPH_SEQREL|C|3|0|Sequen.Rel.|Sequencia Relacionamento
TPH|05|TPH_TAREFA|C|6|0|Tarefa|Tarefa da Manutencao
TPH|06|TPH_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TPH|07|TPH_ETAPA|C|6|0|Etapa|Codigo da Etapa da Tarefa
TPH|08|TPH_NOMETA|C|150|0|Descr. Etapa|Descricao da Etapa
TPH|09|TPH_OPCOES|C|1|0|Tipo Opcoes|Tipo de Opcoes da Etapa
TPH|10|TPH_DOCFIL|C|6|0|Filial Doc.|Filial Documentacao
TPH|11|TPH_DOCTO|C|16|0|Documento|Documentacao Etapa Manut
TPH|12|TPH_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
TPH|13|TPH_SEQETA|C|3|0|Seq. Etapa|Sequencia da Etapa
TPH|14|TPH_TIPOPE|C|6|0|Tp. Operac.|Tipo de Operação
TPH|15|TPH_DSCOPE|C|15|0|Desc. Oper.|Desc. do Tipo de Oper.
--- ### TPI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPI|01|TPI_FILIAL|C|6|0|Filial|Filial do Sistema
TPI|02|TPI_CODBEM|C|16|0|Bem|Codigo do Bem
TPI|03|TPI_SERVIC|C|6|0|Servico|Codigo do Servico
TPI|04|TPI_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
TPI|05|TPI_PERACO|N|3|0|Periodo Acom|Periodo Entre Acompanham.
TPI|06|TPI_UNIACO|C|1|0|Unid.Acomp.|Unidade Periodo Acompanha
TPI|07|TPI_CONMAN|N|12|0|Cont.Manut.|Contador Ultima Manutenc.
TPI|08|TPI_INENMA|N|6|0|Incr.Manut.|Incremento Entre Manutenc
TPI|09|TPI_AJUSCO|N|9|0|Ajuste Cont.|Valor Ajuste de Contador
TPI|10|TPI_SEQUEN|N|3|0|Sequencia|Sequencia da Manutencao
--- ### TPJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPJ|01|TPJ_FILIAL|C|6|0|Filial|Filial do Sistema
TPJ|02|TPJ_CODMOT|C|4|0|Motivo|Codigo do Motivo
TPJ|03|TPJ_DESMOT|C|40|0|Descricao|Descricao Motivo
--- ### TPK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPK|01|TPK_FILIAL|C|6|0|Filial|Filial do Sistema
TPK|02|TPK_CODFAM|C|6|0|Familia|Codigo da Familia
TPK|03|TPK_CODPRO|C|15|0|Código|Codigo do Produto
TPK|04|TPK_NOMPEC|C|70|0|Nome Peça|Nome da Peca
TPK|05|TPK_QUANTI|N|9|2|Quantidade|Quantidade Utilizada
TPK|06|TPK_UNIDAD|C|10|0|Unidade Med.|Unidade de Medida
TPK|07|TPK_CRITIC|C|1|0|Criticidade|Criticidade da Peca
TPK|08|TPK_QTDGAR|N|9|0|Qtd. Garant.|Quantidade Garantia
TPK|09|TPK_UNIGAR|C|1|0|Unid.Garant.|Unidade de Garantia
TPK|10|TPK_CONGAR|C|1|0|Cont Garant|Contador Garantia
TPK|11|TPK_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TPK|12|TPK_QTDCON|N|9|0|Qtd.Gar.Cont|Qtd.Garantia Contador
TPK|13|TPK_LOCGAR|C|6|0|Local Garant|Localizacao da Garantia
TPK|14|TPK_ALTER|C|1|0|Alternativo|Peca Alternativo
TPK|15|TPK_SALDIS|N|14|2|Saldo Atual|Saldo Atual do Produto
--- ### TPL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPL|01|TPL_FILIAL|C|6|0|Filial|Filial do Sistema
TPL|02|TPL_ORDEM|C|6|0|Ordem|Ordem de Servico
TPL|03|TPL_CODMOT|C|4|0|Motivo|Codigo do Motivo
TPL|04|TPL_DESMOT|C|40|0|Descr Motivo|Descricao Motivo
TPL|05|TPL_DTINIC|D|8|0|Data Inicio|Data Inicio do Atraso
TPL|06|TPL_HOINIC|C|5|0|Hora Inicio|Hora Inicio do Atraso
TPL|07|TPL_DTFIM|D|8|0|Data Fim|Data Termino do Atraso
TPL|08|TPL_HOFIM|C|5|0|Hora Fim|Hora Termino do Atraso
--- ### TPM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPM|01|TPM_FILIAL|C|6|0|Filial|Filial do Sistema
TPM|02|TPM_CODFAM|C|6|0|Familia|Codigo da Familia
TPM|03|TPM_SERVIC|C|6|0|Servico|Codigo do Servico
TPM|04|TPM_SEQREL|C|3|0|Sequen.Rel.|Sequencia Relacionamento
TPM|05|TPM_TAREFA|C|6|0|Tarefa|Codigo da Tarefa
TPM|06|TPM_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TPM|07|TPM_DEPEND|C|6|0|Dependência|Tarefa de Dependencia
TPM|08|TPM_NOME|C|20|0|Nome Depend.|Descricao da Dependencia
TPM|09|TPM_SOBREP|N|5|2|Sobreposição|Fator de Sobreposicao
TPM|10|TPM_SEQUEN|N|3|0|Sequencia|Sequencia da manutencao
--- ### TPN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPN|01|TPN_FILIAL|C|6|0|Filial|Filial do Sistema
TPN|02|TPN_CODBEM|C|16|0|Bem|Codigo do Bem
TPN|03|TPN_DTINIC|D|8|0|Data Inicio|Data Inicio do Retorno
TPN|04|TPN_HRINIC|C|5|0|Hora Inicio|Hora Inicio do Retorno
TPN|05|TPN_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TPN|06|TPN_CTRAB|C|6|0|C.Trabalho|Centro de Trabalho
TPN|07|TPN_UTILIZ|C|1|0|Utilizacao|Estado do Bem
TPN|08|TPN_POSCON|N|9|0|Pos.Contador|Posicao Atual do Contador
TPN|09|TPN_POSCO2|N|9|0|2. Contador|Posicao Segundo Contador
TPN|10|TPN_OBSERV|C|40|0|Observacao|Observacao
--- ### TPO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPO|01|TPO_FILIAL|C|6|0|Filial|Filial do Sistema
TPO|02|TPO_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TPO|03|TPO_LOJA|C|2|0|Loja|Loja do Fornecedor
TPO|04|TPO_NOMFOR|C|80|0|Nome Fornece|Nome do Fornecedor
TPO|05|TPO_SERVIC|C|6|0|Servico|Codigo do Servico
TPO|06|TPO_NOMSER|C|20|0|Nome Servico|Nome do Servico
TPO|07|TPO_ESPECI|C|3|0|Especialidad|Codigo Especialidade
TPO|08|TPO_NOMESP|C|20|0|Nome Espec|Nome da Especialidade
TPO|09|TPO_CUSTO|N|10|2|Custo Hora|Custo Hora do Servico
--- ### TPP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPP|01|TPP_FILIAL|C|6|0|Filial|Filial do Sistema
TPP|02|TPP_ORDEM|C|6|0|Ordem Serv.|Numero da Ordem Servico
TPP|03|TPP_PLANO|C|6|0|Plano Acomp.|Nro. Plano Acompanhamento
TPP|04|TPP_CODBEM|C|16|0|Bem|Codigo do Bem
TPP|05|TPP_NOMBEM|C|20|0|Nome do Bem|Nome do Bem
TPP|06|TPP_SERVIC|C|6|0|Servico|Codigo do Servico
TPP|07|TPP_NOMSER|C|20|0|Nome Servico|Nome do Servico
TPP|08|TPP_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
TPP|09|TPP_DTORIG|D|8|0|Dt Original|Data Original Ordem Serv.
TPP|10|TPP_POSCON|N|9|0|Contador|Posicao do Contador
TPP|11|TPP_DTREAL|D|8|0|Data Plano|Data Plano de acompanham.
TPP|12|TPP_DTLEIT|D|8|0|Data Leitura|Data da Leitura
TPP|13|TPP_SITUAC|C|1|0|Situacao|Situacao da Ordem Servico
TPP|14|TPP_TERMIN|C|1|0|Termino|Indica Termino da O.S.
TPP|15|TPP_USUCAN|C|25|0|Usuario Canc|Usuario do Cancelamento
TPP|16|TPP_USULEI|C|25|0|Usuario Leit|Usuario da Leitura
TPP|17|TPP_DTULTA|D|8|0|Data Ult.Ac.|Data Ult. Acompanhamento
TPP|18|TPP_COULTA|N|9|0|Cont.Ult.Ac.|Contador Ultimo Acompan.
TPP|19|TPP_CCUSTO|C|9|0|Centro Custo|Centro de Custos
TPP|20|TPP_NOMCUS|C|20|0|Nome C.Custo|Nome do Centro de Custo
TPP|21|TPP_CENTRA|C|6|0|Centro Trab.|Centro de Trabalho
TPP|22|TPP_NOMTRA|C|20|0|Nome C.Traba|Nome do Centro de Trabalh
TPP|23|TPP_VARDIA|N|6|0|Variacao Dia|Variaco Dia Ult.Acompanha
TPP|24|TPP_ACUMCO|N|12|0|Ac. Contador|Acumulador do Contador
TPP|25|TPP_VIRACO|N|3|0|Virada Contd|Virada do Contador do Bem
TPP|26|TPP_HORA|C|5|0|Hora lancam.|Hora do lancamento
TPP|27|TPP_TIPOLA|C|1|0|Tipo Lancam.|Tipo do Lancamento
TPP|28|TPP_SEQUEN|N|3|0|Sequencia|Sequencia da Manutencao
TPP|29|TPP_APROPR|C|1|0|Apropriado?|Apropriado - integracao
TPP|30|TPP_ORIGEM|C|10|0|Rotina Ger.|Rotina Geradora
--- ### TPQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPQ|01|TPQ_FILIAL|C|6|0|Filial|Filial do Sistema
TPQ|02|TPQ_ORDEM|C|6|0|Ordem|Ordem de Servico
TPQ|03|TPQ_PLANO|C|6|0|Plano|Plano de Manutencao
TPQ|04|TPQ_TAREFA|C|6|0|Tarefa|Tarefa da Manutencao
TPQ|05|TPQ_ETAPA|C|6|0|Etapa|Etapa da tarefa manutenc.
TPQ|06|TPQ_OPCAO|C|15|0|Opcao|Opcao da Etapa
TPQ|07|TPQ_RESPOS|C|10|0|Resposta|Resposta da Opcao da Etap
TPQ|08|TPQ_ORDEMG|C|6|0|Ordem Gerada|Ordem Servico Gerada
TPQ|09|TPQ_CODFUN|C|6|0|Funcionario|Codigo do Funcionario
TPQ|10|TPQ_NOME|C|20|0|Nome Func|Nome do Funcionario
TPQ|11|TPQ_TIPRES|C|1|0|Tipo|Tipo de Resposta
TPQ|12|TPQ_CONDOP|C|2|0|Operador|Operador da Condicao
TPQ|13|TPQ_CONDIN|C|10|0|Informacao|Valor de Comparacao
TPQ|14|TPQ_TIPCAM|C|1|0|Tp.Campo Res|Tipo de Campo de Resposta
TPQ|15|TPQ_TPMANU|C|1|0|Tipo Man.|Tipo de manutencao gerar
TPQ|16|TPQ_SERVIC|C|6|0|Servico|Servico de Manutencao
TPQ|17|TPQ_PORBEM|C|1|0|Para o Bem|Para que Bem gerar O.S
TPQ|18|TPQ_DESCRI|C|20|0|Descricao|Descricao
TPQ|19|TPQ_PERCEN|N|6|0|Perc.Aviso|Percent. p/disparar Aviso
TPQ|20|TPQ_OBSERV|C|40|0|Msg. Alerta|Mensagem de Alerta
TPQ|21|TPQ_OK|C|2|0|Situacao|Situacao da Opcao
--- ### TPR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPR|01|TPR_FILIAL|C|6|0|Filial|Filial do Sistema
TPR|02|TPR_CODCAR|C|6|0|Caracterist.|Codigo da Caracteristica
TPR|03|TPR_NOME|C|40|0|Nome|Nome Caracteristica
TPR|04|TPR_TPINFO|C|1|0|Tipo Inf.|Tipo da Informação
--- ### TPS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPS|01|TPS_FILIAL|C|6|0|Filial|Filial do Sistema
TPS|02|TPS_CODLOC|C|6|0|Local|Codigo do Local
TPS|03|TPS_NOME|C|40|0|Nome Local|Nome do Local
--- ### TPT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPT|01|TPT_FILIAL|C|6|0|Filial|Filial do Sistema
TPT|02|TPT_CODGRP|C|3|0|Cod. Grupo|Codigo do Grupo
TPT|03|TPT_DESGRP|C|30|0|Nome Grupo|Nome do Grupo
TPT|04|TPT_CODFUN|C|6|0|Matricula|Matricula
TPT|05|TPT_NOMFUN|C|30|0|Funcionario|Funcionario
TPT|06|TPT_EMAIL|C|50|0|E-mail|E-mail
--- ### TPU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPU|01|TPU_FILIAL|C|6|0|Filial|Filial do Sistema
TPU|02|TPU_CODROT|C|6|0|Roteiro|Codigo do Roteiro
TPU|03|TPU_DESCRI|C|40|0|Descricao|Descricao Roteiro
--- ### TPV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPV|01|TPV_FILIAL|C|6|0|Filial|Filial do Sistema
TPV|02|TPV_CODROT|C|6|0|Roteiro|Codigo do Roteiro
TPV|03|TPV_DESCRI|C|20|0|Descr.Roteir|Descriaco Roteiro
TPV|04|TPV_CODBEM|C|16|0|Bem|Codigo do Bem
TPV|05|TPV_NOMBEM|C|40|0|Nome Bem|Nome do Bem
TPV|06|TPV_SEQREL|C|5|0|Sequencia|Sequencia do Roteiro
TPV|07|TPV_SEQUEN|N|5|0|Sequencia|Sequencia do Roteiro
--- ### TPW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPW|01|TPW_FILIAL|C|6|0|Filial|Filial do Sistema
TPW|02|TPW_ORDEM|C|6|0|Ordem Serv.|Numero Ordem de Servico
TPW|03|TPW_PLANO|C|6|0|Plano Acomp.|Nr. Plano Acompanhamento
TPW|04|TPW_CODBEM|C|16|0|Bem|Codigo do Bem
TPW|05|TPW_SERVIC|C|6|0|Servico|Codigo do Serviço
TPW|06|TPW_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
TPW|07|TPW_DTORIG|D|8|0|Dt Original|Data Original Ordem Serv.
TPW|08|TPW_DTREAL|D|8|0|Data Plano|Data Plano Acompanhamento
TPW|09|TPW_POSCON|N|9|0|Contador|Posicao do Contador
TPW|10|TPW_DTLEIT|D|8|0|Data Leitura|Data da Leitura
TPW|11|TPW_SITUAC|C|1|0|Situacao|Situacao da Ordem Servico
TPW|12|TPW_TERMIN|C|1|0|Termino|Indica Termino da O.S.
TPW|13|TPW_USUCAN|C|25|0|Usuario Canc|Usuario do Cancelamento
TPW|14|TPW_USULEI|C|25|0|Usuario Leit|Usuario da Leitura
TPW|15|TPW_DTULTA|D|8|0|Data Ult.Ac.|Data Ult. Acompanhamento
TPW|16|TPW_COULTA|N|9|0|Cont.Ult.Ac.|Cont. Ult. Acompanhamento
TPW|17|TPW_CCUSTO|C|9|0|Centro Custo|Centro de Custos
TPW|18|TPW_CENTRA|C|6|0|Centro Trab.|Centro de Trabalho
TPW|19|TPW_TEMCON|C|1|0|Tem Contador|O Bem Tem Contador
TPW|20|TPW_ACUMCO|N|12|0|Ac.Contador|Acumulador do Contador
TPW|21|TPW_VIRACO|N|3|0|Virada Cont.|Virada do Contador do Bem
TPW|22|TPW_VARDIA|N|6|0|Variacao Dia|Variaco Dia Ult.Acompanha
TPW|23|TPW_HORA|C|5|0|Hora lancam.|Hora do lamcamento
TPW|24|TPW_TIPOLA|C|1|0|Tipo Lanc.|Tipo  de Lancamento
TPW|25|TPW_SEQUEN|N|3|0|Sequencia|Sequencia da Manutencao
--- ### TPX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPX|01|TPX_FILIAL|C|6|0|Filial|Filial do Sistema
TPX|02|TPX_ORDEM|C|6|0|Ordem|Ordem de Servico
TPX|03|TPX_PLANO|C|6|0|Plano|Plano de Manutencao
TPX|04|TPX_TAREFA|C|6|0|Tarefa|Tarefa da Manutencao
TPX|05|TPX_ETAPA|C|6|0|Etapa|Etapa da tarefa manutenc.
TPX|06|TPX_OPCAO|C|15|0|Opcao|Opcao da Etapa
TPX|07|TPX_RESPOS|C|10|0|Resposta|Resposta da etapa
TPX|08|TPX_CODFUN|C|6|0|Matricula|Matricula do Funcionario
TPX|09|TPX_NOMFUN|C|20|0|Nome Func.|Nome do Funcionario
TPX|10|TPX_ORDEMG|C|6|0|Ordem Gerada|Ordem Gerada pela Etapa
TPX|11|TPX_TIPRES|C|1|0|Tipo|Tipo de Resposta
TPX|12|TPX_CONDOP|C|2|0|Operador|Operador da Condicao
TPX|13|TPX_CONDIN|C|10|0|Informacao|Valor de Informacao
TPX|14|TPX_TIPCAM|C|1|0|Tp.Campo Res|Tipo de Campo de Resposta
TPX|15|TPX_TPMANU|C|1|0|Tipo Man.|Tipo de Manutencao gerar
TPX|16|TPX_SERVIC|C|6|0|Servico|Servico da Manutencao
TPX|17|TPX_PORBEM|C|1|0|Para o Bem|Para que Bem gerar O.S
TPX|18|TPX_DESCRI|C|20|0|Descricao|Descricao
TPX|19|TPX_PERCEN|N|6|0|Perc.Aviso|Percent. p/disparar Aviso
TPX|20|TPX_OBSERV|C|40|0|Msg. Alerta|Mensagem de Alerta
TPX|21|TPX_OK|C|2|0|Situacao|Situacao
--- ### TPY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPY|01|TPY_FILIAL|C|6|0|Filial|Filial do Sistema
TPY|02|TPY_CODBEM|C|16|0|Bem|Codigo do Bem
TPY|03|TPY_CODPRO|C|15|0|Código|Codigo do Produto
TPY|04|TPY_NOMPEC|C|70|0|Nome Peca|Nome da Peca
TPY|05|TPY_QUANTI|N|9|2|Quantidade|Quantidade Utilizada
TPY|06|TPY_UNIDAD|C|10|0|Unidade Med.|Unidade de Medida
TPY|07|TPY_CRITIC|C|1|0|Criticidade|Criticidade da Peca
TPY|08|TPY_QTDGAR|N|9|0|Quant. Gar.|Quantidade Garantia
TPY|09|TPY_UNIGAR|C|1|0|Unid.Garant.|Unidade de Garantia
TPY|10|TPY_CONGAR|C|1|0|Cont. Gar.|Contador Garantia
TPY|11|TPY_QTDCON|N|9|0|Quant. Cont.|Qtd.Garantia Contador
TPY|12|TPY_LOCGAR|C|6|0|Local Gar.|Localizacao da Garantia
TPY|13|TPY_ALTER|C|1|0|Alternativo|Peca Alternativo
TPY|14|TPY_SALDIS|N|14|2|Saldo Atual|Saldo Atual do Produto
--- ### TPZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TPZ|01|TPZ_FILIAL|C|6|0|Filial|Filial do Sistema
TPZ|02|TPZ_CODBEM|C|16|0|Bem|Codigo do Bem
TPZ|03|TPZ_TIPORE|C|1|0|Tipo Insumo|Codigo do Tipo de Insumo
TPZ|04|TPZ_CODIGO|C|15|0|Codigo|Codigo do Detalhe
TPZ|05|TPZ_LOCGAR|C|6|0|Local Garant|Localizacao da Garantia
TPZ|06|TPZ_ORDEM|C|6|0|Ordem|Ordem de Servico
TPZ|07|TPZ_PLANO|C|6|0|Plano|Plano de Manutencao
TPZ|08|TPZ_SEQREL|C|3|0|Sequencia|Sequencia do Retorno
TPZ|09|TPZ_QTDGAR|N|9|0|Qtde Garant|Quantidade Garantia
TPZ|10|TPZ_UNIGAR|C|1|0|Unid.Garant.|Unidade de Tempo Garantia
TPZ|11|TPZ_DTGARA|D|8|0|Dt.Garantia|Data Inicio Garantia
TPZ|12|TPZ_CONGAR|C|1|0|Cont. Garant|Contador Garantia
TPZ|13|TPZ_SEQUEN|N|2|0|Sequencia|Sequencia do Retorno
TPZ|14|TPZ_QTDCON|N|9|0|Qtd.Gar.Cont|Qtd.Garantia Contador
--- ### TQ0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ0|01|TQ0_FILIAL|C|6|0|Filial|Filial do Sistema
TQ0|02|TQ0_DESENH|C|6|0|Esquema|Codigo do Esquema Padrao
TQ0|03|TQ0_NOMDES|C|30|0|Descricao|Descricao Esquema Padrao
TQ0|04|TQ0_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo
TQ0|05|TQ0_DESMOD|C|20|0|Descricao|Descricao Tipo do Modelo
TQ0|06|TQ0_EIXOS|N|3|0|Eixos|Quant. Eixos do Esquema
TQ0|07|TQ0_STEPES|C|1|0|Tem Estepes|Tem Estepes?
TQ0|08|TQ0_ANEXO1|C|6|0|Fam. Anexo 1|Familia do Anexo 1
TQ0|09|TQ0_ANEXO2|C|6|0|Fam. Anexo 2|Familia do Anexo 2
TQ0|10|TQ0_ANEXO3|C|6|0|Fam. Anexo 3|Familia do Anexo 3
TQ0|11|TQ0_CODEST|C|3|0|Cód. Estrutu|Código da Estrutura
--- ### TQ1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ1|01|TQ1_FILIAL|C|6|0|Filial|Filial do Sistema
TQ1|02|TQ1_DESENH|C|6|0|Esquema|Codigo do Esquema Padrao
TQ1|03|TQ1_SEQREL|C|4|0|Sequencia|Sequencia dos Itens
TQ1|04|TQ1_EIXO|C|10|0|Eixo|Nome do Eixo
TQ1|05|TQ1_TIPEIX|C|1|0|Tipo do Eixo|Tipo do Eixo
TQ1|06|TQ1_QTDPNE|N|2|0|Rodados|Quant.Rodados por Eixo
TQ1|07|TQ1_LOCPN1|C|6|0|Loc.Rodado 1|Loc.Primeiro Rodado Eixo
TQ1|08|TQ1_FAMIL1|C|6|0|Familia L. 1|Codigo Familia Localiz. 1
TQ1|09|TQ1_LOCPN2|C|6|0|Loc.Rodado 2|Loc. Segundo Rodado Eixo
TQ1|10|TQ1_FAMIL2|C|6|0|Familia L. 2|Codigo Familia Localiz. 2
TQ1|11|TQ1_LOCPN3|C|6|0|Loc.Rodado 3|Loc.Terceiro Rodado Eixo
TQ1|12|TQ1_FAMIL3|C|6|0|Familia L. 3|Codigo Familia Localiz. 3
TQ1|13|TQ1_LOCPN4|C|6|0|Loc.Rodado 4|Loc.Quarto Rodado Eixo
TQ1|14|TQ1_FAMIL4|C|6|0|Familia L. 4|Codigo Familia Localiz. 4
TQ1|15|TQ1_LOCPN5|C|6|0|Loc.Rodado 5|Loc. quinto rodado eixo
TQ1|16|TQ1_FAMIL5|C|6|0|Familia L. 5|Codigo familia localiz. 5
TQ1|17|TQ1_LOCPN6|C|6|0|Loc.Rodado 6|Loc. sexto rodado eixo
TQ1|18|TQ1_FAMIL6|C|6|0|Familia L. 6|Godigo familia localiz. 6
TQ1|19|TQ1_LOCPN7|C|6|0|Loc.Rodado 7|Loc.Setimo Rodado Eixo
TQ1|20|TQ1_FAMIL7|C|6|0|Familia L. 7|Codigo Familia Localiz. 7
TQ1|21|TQ1_LOCPN8|C|6|0|Loc.Rodado 8|Loc.Oitava Rodado Eixo
TQ1|22|TQ1_FAMIL8|C|6|0|Familia L. 8|Codigo Familia Localiz. 8
TQ1|23|TQ1_LOCPN9|C|6|0|Loc.Rodado 9|Loc.Nono Rodado Eixo
TQ1|24|TQ1_FAMIL9|C|6|0|Familia L. 9|Codigo Familia Localiz. 9
TQ1|25|TQ1_LOCPN0|C|6|0|Loc.Rodad.10|Loc.Decimo Rodado Eixo
TQ1|26|TQ1_FAMIL0|C|6|0|Familia L.10|Codigo Familia Localiz. 1
TQ1|27|TQ1_SEQUEN|N|4|0|Sequencia|Sequencia dos Itens
TQ1|28|TQ1_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo
TQ1|29|TQ1_SUSPEN|C|1|0|Eixo Susp.?|Eixo Suspenso?
--- ### TQ2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ2|01|TQ2_FILIAL|C|6|0|Filial|Filial do Sistema
TQ2|02|TQ2_NUMME|C|6|0|Num. ME|Num. ME
TQ2|03|TQ2_STATUS|C|1|0|Status|Status da Transferência
TQ2|04|TQ2_CODBEM|C|16|0|Bem|Codigo do Bem
TQ2|05|TQ2_NOMBEM|C|20|0|Nome do Bem|Nome do Bem
TQ2|06|TQ2_DESMOD|C|20|0|Modelo|Descrição do Modelo
TQ2|07|TQ2_DATATR|D|8|0|Data Transf.|Data da Transferência
TQ2|08|TQ2_HORATR|C|5|0|Hora Transf.|Hora da Transferência
TQ2|09|TQ2_EMPORI|C|2|0|Emp. Origem|Empresa Origem
TQ2|10|TQ2_DEFIOR|C|20|0|Descrição|Descrição Filial Origem
TQ2|11|TQ2_FILORI|C|6|0|Filial Orig.|Descrição Filial Origem
TQ2|12|TQ2_CCORIG|C|9|0|Centro C.Ori|Centro Custo Original
TQ2|13|TQ2_DESCC2|C|20|0|CC Origem|Descrição CC Origem
TQ2|14|TQ2_CTRAOR|C|6|0|Cent.Trab Or|Centro Trabalho Original
TQ2|15|TQ2_POSCON|N|9|0|Pos.Contador|Posição do Contador
TQ2|16|TQ2_POSCO2|N|9|0|Pos.Cont2|Posição do Contador 2
TQ2|17|TQ2_EMPDES|C|2|0|Emp. Destino|Empresa Destino
TQ2|18|TQ2_DEFIDE|C|16|0|Descrição|Descrição Filial Destino
TQ2|19|TQ2_FILDES|C|6|0|Filial Dest.|Filial Destino
TQ2|20|TQ2_CCUSTO|C|9|0|Centro Custo|Centro Custo
TQ2|21|TQ2_DESCC1|C|20|0|CC Destino|Descrição CC Destino
TQ2|22|TQ2_CENTRA|C|6|0|Centro Traba|Centro Trabalho
TQ2|23|TQ2_EMAIL1|C|254|0|Email NF|Email Responsável NF
TQ2|24|TQ2_EMAIL2|C|254|0|Email Conf.|Email Resp. Confirmação
TQ2|25|TQ2_NOTFIS|C|9|0|Nota Fiscal|Núm. Nota Fiscal
TQ2|26|TQ2_SERIE|C|3|0|Série|Série
TQ2|27|TQ2_USERIN|C|25|0|Usuário Inc.|Usuário da Inclusão
TQ2|28|TQ2_USERAL|C|25|0|Usuár. Alt.|Usuario da Alteração
TQ2|29|TQ2_USERCO|C|25|0|Usuár. Conf.|Usuario da Confirmação
TQ2|30|TQ2_DATAIN|D|8|0|Dt. Inclusão|Data da Inclusão
TQ2|31|TQ2_HORAIN|C|5|0|Hr. Inclusão|Hora da Inclusão
TQ2|32|TQ2_DATAAL|D|8|0|Dt. Alter.|Data da Alteração
TQ2|33|TQ2_HORAAL|C|5|0|Hr. Alter.|Hora da Alteração
TQ2|34|TQ2_DATACO|D|8|0|Dt. Confirm.|Data da Confirmação
TQ2|35|TQ2_HORACO|C|5|0|Hr. Confirm.|Hora da Confirmação
TQ2|36|TQ2_ORDEM|C|6|0|Ordem Serv.|Número da Ordem Serviço
TQ2|37|TQ2_CAUSA|C|6|0|Causa Remoç.|Causa Remoção
TQ2|38|TQ2_DESCAU|C|20|0|Desc. Causa|Descrição da Causa
TQ2|39|TQ2_MOTTRA|M|10|0|Mot.Transf.|Motivo Transferência
--- ### TQ3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ3|01|TQ3_FILIAL|C|6|0|Filial|Filial do Sistema
TQ3|02|TQ3_CDSERV|C|6|0|Cod. Servico|Codigo do Servico
TQ3|03|TQ3_NMSERV|C|40|0|Nome Servico|Nome do Servico
TQ3|04|TQ3_CDRESP|C|25|0|Supervisor|Codigo do Supervisor
TQ3|05|TQ3_NMRESP|C|40|0|Nome Superv.|Nome Supervisor da Area
TQ3|06|TQ3_EMAIL|C|50|0|Email|Email
TQ3|07|TQ3_DISTRI|C|1|0|Distribuicao|Distribuicao de S.S.
TQ3|08|TQ3_PESQST|C|1|0|Pesq.Satis.|Pesquisa Satisfacao
--- ### TQ4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ4|01|TQ4_FILIAL|C|6|0|Filial|Filial do Sistema
TQ4|02|TQ4_CDEXEC|C|25|0|Executante|Executante da SS
TQ4|03|TQ4_NMEXEC|C|40|0|Nome|Nome do Executante
TQ4|04|TQ4_EMAIL1|C|50|0|Email 1|Email 1
TQ4|05|TQ4_CEL1|C|15|0|Celular 1|Celular para SMS
TQ4|06|TQ4_SMS1|C|1|0|Envia SMS?|Envia SMS?
TQ4|07|TQ4_CEL2|C|15|0|Celular 2|Celular para SMS
TQ4|08|TQ4_SMS2|C|1|0|Envia SMS?|Envia SMS?
--- ### TQ5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ5|01|TQ5_FILIAL|C|6|0|Filial|Filial do Sistema
TQ5|02|TQ5_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TQ5|03|TQ5_TIPO|C|1|0|Tipo Carac.|Tipo da Caracteristica
TQ5|04|TQ5_CODOCR|C|6|0|Ocorr. Rel.|Ocorrencia Relacionada
TQ5|05|TQ5_NOMEOR|C|20|0|Nome Ocorr.|Nome Ocor. Relacionada
TQ5|06|TQ5_TIPOR|C|1|0|Tipo Carac.|Tipo Carac. Relacionada
--- ### TQ6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ6|01|TQ6_FILIAL|C|6|0|Filial|Filial do Sistema
TQ6|02|TQ6_ORDEM|C|6|0|Ordem|Ordem de Servico
TQ6|03|TQ6_CODMOT|C|4|0|Motivo|Codigo do Motivo
TQ6|04|TQ6_DESMOT|C|20|0|Descr Motivo|Descricao Motivo
TQ6|05|TQ6_DTINIC|D|8|0|Data Inicio|Data Inicio do Atraso
TQ6|06|TQ6_HOINIC|C|5|0|Hora Inicio|Hora Inicio do Atraso
TQ6|07|TQ6_DTFIM|D|8|0|Data Fim|Data Termino do Atraso
TQ6|08|TQ6_HOFIM|C|5|0|Hora Fim|Hora Termino do Atraso
--- ### TQ9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ9|01|TQ9_FILIAL|C|6|0|Filial|Filial do Sistema
TQ9|02|TQ9_ORDEM|C|6|0|Ordem Serv.|Ordem de Servico
TQ9|03|TQ9_PLANO|C|6|0|Plano|Codigo do Plano
TQ9|04|TQ9_USUARI|C|25|0|Usuario Alt.|Usuario da Alteracao
TQ9|05|TQ9_STAORI|C|6|0|Stat.OS Orig|Status da OS Original
TQ9|06|TQ9_STAALT|C|6|0|Stat.OS Alt.|Status da OS Alterada
TQ9|07|TQ9_DATAAL|D|8|0|Dt. Alterac.|Data Alter. Status da OS
TQ9|08|TQ9_HRALTE|C|5|0|Hr. Alterac.|Hora Alter. Status da OS
TQ9|09|TQ9_MOTALT|M|10|0|Motivo Alt.|Motivo Alteracao Status
--- ### TQA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQA|01|TQA_FILIAL|C|6|0|Filial|Filial do sistema
TQA|02|TQA_PLANO|C|6|0|Plano|Plano de acompanhamento
TQA|03|TQA_ORDEM|C|6|0|Ordem|Ordem de acompanhamento
TQA|04|TQA_CODBEM|C|16|0|Bem|Codigo do bem
TQA|05|TQA_NOMBEM|C|20|0|Nome Bem|Nome do bem
TQA|06|TQA_DTORIG|D|8|0|Dt.Original|Data original
TQA|07|TQA_DTREAL|D|8|0|Dt. Real|Data real de inicio
TQA|08|TQA_POSCON|N|9|0|Contador 1|Contador 1
TQA|09|TQA_DTLEI1|D|8|0|Dt. Cont. 1|Data leitura contador 1
TQA|10|TQA_HORAC1|C|5|0|Hora Cont.1|Hora leit. cont. 1
TQA|11|TQA_POSCO2|N|9|0|Contador 2|Contador 2
TQA|12|TQA_DTLEI2|D|8|0|Dt. Cont. 2|Data leit. contador 2
TQA|13|TQA_HORAC2|C|5|0|Hora C. 2|Hora leit. contador 2
TQA|14|TQA_SITUAC|C|1|0|Situacao|Situacao da ordem
TQA|15|TQA_TERMIN|C|1|0|Termino|Termino do ordem
TQA|16|TQA_CCUSTO|C|9|0|Centro custo|Centro de custo
TQA|17|TQA_NOMCUS|C|20|0|Nome C.custo|Nome do centro de custo
TQA|18|TQA_CENTRA|C|6|0|Centro trab.|Centro de trabalho
TQA|19|TQA_NOMTRA|C|20|0|Nome C.trab.|Nome centro trabalho
TQA|20|TQA_RETORN|C|1|0|Retorno|Retorno ordem
TQA|21|TQA_USUCAN|C|25|0|Usuario Can.|Usuario cancelamento
TQA|22|TQA_USULEI|C|25|0|Usuario ret.|Usuario que retorno a O.S
--- ### TQB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQB|01|TQB_FILIAL|C|6|0|Filial|Filial do Sistema
TQB|02|TQB_SOLICI|C|6|0|Solicitacao|Numero da Solicitacao
TQB|03|TQB_TIPOSS|C|1|0|Tipo Item|Tipo Item
TQB|04|TQB_CODBEM|C|16|0|Bem/Localiz.|Bem/Localizacao
TQB|05|TQB_NOMBEM|C|40|0|Desc.Bem/Loc|Descricao Bem/Localizacao
TQB|06|TQB_CCUSTO|C|9|0|Centro Custo|Codigo do Centro de Custo
TQB|07|TQB_NOMCUS|C|40|0|Nome C.Custo|Nome do Centro de Custo
TQB|08|TQB_CENTRA|C|6|0|Centro Trab.|Codigo do Centro Trabalho
TQB|09|TQB_NOMCTR|C|30|0|Nome C.Trab.|Nome Centro Trabalho
TQB|10|TQB_LOCALI|C|6|0|Localizacao|Codigo da Localizacao
TQB|11|TQB_NOMLOC|C|20|0|Nome Locali.|Nome da Localizacao
TQB|12|TQB_DTABER|D|8|0|Dt. Abertura|Data de Abertura
TQB|13|TQB_HOABER|C|5|0|Hr. Abertura|Hora da Abertura
TQB|14|TQB_USUARI|C|30|0|Solicitante|Nome do Solicitante
TQB|15|TQB_RAMAL|C|10|0|Ramal|Numero do Ramal do Func.
TQB|16|TQB_SOLUCA|C|1|0|Situacao S.S|Situacao da Solicitacao
TQB|17|TQB_CODMSS|C|6|0|Servico|Codigo do Memo de Servico
TQB|18|TQB_DESCSS|M|80|0|Servico|Servico a ser executado
TQB|19|TQB_CDSERV|C|6|0|Tipo Servico|Tipo de Servico
TQB|20|TQB_NMSERV|C|20|0|Nome Servico|Nome do Servico
TQB|21|TQB_FUNEXE|C|6|0|Supervisor|Supervisor que Liberou
TQB|22|TQB_NOMFUN|C|40|0|Nome Superv.|Nome do Supervisor
TQB|23|TQB_DTFECH|D|8|0|Data Enc.|Data de Encerramento
TQB|24|TQB_HOFECH|C|5|0|Hora Enc.|Hora de Encerramento
TQB|25|TQB_TEMPO|C|10|0|Tempo SS|Tempo da Solicitacao
TQB|26|TQB_CODMSO|C|6|0|Solucao SS|Codigo do Memo de Solucao
TQB|27|TQB_DESCSO|M|80|0|Solucao SS|Solucao Solicitacao
TQB|28|TQB_ORDEM|C|6|0|Ordem Servic|Numero da Ordem Servico
TQB|29|TQB_CDSOLI|C|6|0|Solicitante|Codigo do Solicitante
TQB|30|TQB_NMSOLI|C|40|0|Nome Solicit|Nome do Solicitante
TQB|31|TQB_EMSOLI|C|50|0|Email Solici|Email do Solicitante
TQB|32|TQB_CDEXEC|C|25|0|Executante|Codigo do Executante
TQB|33|TQB_NMEXEC|C|20|0|Nome Exec.|Nome do Executante
TQB|34|TQB_PRIORI|C|1|0|Prioridade|Prioridade
TQB|35|TQB_PSAP|C|1|0|Atend. Prazo|Atendimento no Prazo
TQB|36|TQB_PSAN|C|1|0|Atend. Neces|Atendimento Necessidade
TQB|37|TQB_OBSPRA|M|80|0|Satis.Prazo|Satisfacao com o Prazo
TQB|38|TQB_OBSATE|M|80|0|Satis.Atend.|Satisfacao Atendimento
TQB|39|TQB_POSCON|N|9|0|Contador|Posicao do Contador
TQB|40|TQB_POSCO2|N|9|0|2. Contador|Posicao Segundo Contador
TQB|41|TQB_INTPRJ|C|10|0|Projeto TOP|Codigo do Projeto TOP]
TQB|42|TQB_INTTSK|C|12|0|Tarefa TOP|Codigo da Tarefa TOP
TQB|43|TQB_MMPRAZ|C|6|0|Satis.Prazo|Cod. Memo Satis.Prazo
TQB|44|TQB_MMATEN|C|6|0|Satis.Atend.|Cod. Memo Satis.Atend.
TQB|45|TQB_MEMODG|C|6|0|Q. Sintomas|Q. Sintomas
TQB|46|TQB_TPSERV|C|1|0|Tipo Solicit|Tipo de Solicitação
TQB|47|TQB_CRITIC|N|8|0|Criticidade|Criticidade
TQB|48|TQB_SEQQUE|C|9|0|Seq. Quest.|Sequência do Questionário
TQB|49|TQB_SATISF|C|1|0|Pesq. Resp.?|Pesquisa Respondida?
TQB|50|TQB_DTCANC|D|8|0|Dt. Canc.|Data de Cancelamento
TQB|51|TQB_FOTO|C|200|0|Imagem|Imagem S.S.
TQB|52|TQB_HRCANC|C|5|0|Hr. Canc.|Hora de Cancelamento
TQB|53|TQB_ORIGEM|C|20|0|Orig. Regist|Origem Registro
TQB|54|TQB_CDCANC|C|6|0|Mot. Canc.|Motivo do Cancelamento
TQB|55|TQB_BITMAP|C|8|0|Imagem|Imagem S.S.
TQB|56|TQB_MECANC|M|80|0|Mot. Canc.|Motivo do Cancelamento
TQB|57|TQB_AS|C|27|0|Nr. A.S.|Nº A.S.
TQB|58|TQB_PROJET|C|22|0|Nro.Projeto|Numero do Projeto
TQB|59|TQB_OBRA|C|3|0|Obra|Obra
--- ### TQC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQC|01|TQC_FILIAL|C|6|0|Filial|Filial do Sistema
TQC|02|TQC_PROGRA|C|8|0|Programa|Programa Chamador
TQC|03|TQC_DESCRI|C|80|0|Descrição|Descrição do Programa
--- ### TQD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQD|01|TQD_FILIAL|C|6|0|Filial|Filial do Sistema
TQD|02|TQD_PROGRA|C|8|0|Programa|Programa Chamador
TQD|03|TQD_SEQUEN|C|2|0|Sequencia|Sequencia de Montagem
TQD|04|TQD_TIPOFU|C|1|0|Tipo|Tipo de Função
TQD|05|TQD_FUNCAO|C|40|0|Função|Função a ser chamada
TQD|06|TQD_DESPOR|C|40|0|Descrição|Descrição Português
TQD|07|TQD_DESING|C|40|0|Descrição|Descrição Inglês
TQD|08|TQD_DESESP|C|40|0|Descrição|Descrição Espanhol
TQD|09|TQD_PARAM|C|80|0|Parâmetros|Parâmetros da Função
TQD|10|TQD_IMAGEM|C|25|0|Imagem|Imagem
TQD|11|TQD_ATIVAR|C|1|0|Ativar?|Ativar o click?
--- ### TQE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQE|01|TQE_FILIAL|C|6|0|Filial|Filial do sistema
TQE|02|TQE_ORDEM|C|6|0|Ordem|Numero da ordem de servic
TQE|03|TQE_PLANO|C|6|0|Plano|Numero do plano
TQE|04|TQE_PRIORI|C|3|0|Prioridade|Codigo da prioridade
TQE|05|TQE_DTORIG|D|8|0|Dt. Original|Dt. Original da ordem
TQE|06|TQE_CODFUN|C|6|0|Funcionario|Codigo funcionario
TQE|07|TQE_NOMFUN|C|20|0|Nome Funcio.|Nome do funcionario
TQE|08|TQE_CODBEM|C|16|0|Bem|Codigo do bem
TQE|09|TQE_NOMBEM|C|20|0|Descricao|Descricao do bem
TQE|10|TQE_SERVIC|C|6|0|Servico|Codigo do servico
TQE|11|TQE_NOMSER|C|20|0|Descricao|Descrico do servico
TQE|12|TQE_SEQUEN|N|3|0|Sequencia|Sequencia
TQE|13|TQE_DTPRIN|D|8|0|Dt. Prev. In|Dt. prevista inicio
TQE|14|TQE_HOPRIN|C|5|0|Hr.Prev.Ini.|Hora prevista inicio
TQE|15|TQE_SITUAC|C|1|0|Situacao|Situacao
TQE|16|TQE_SEQREL|C|3|0|Sequencia|Sequencia da Manutencao
--- ### TQR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQR|01|TQR_FILIAL|C|6|0|Filial|Filial do Sistema
TQR|02|TQR_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo do Modelo
TQR|03|TQR_DESMOD|C|20|0|Descricao|Descricao Tipo do Modelo
TQR|04|TQR_FABRIC|C|6|0|Fabricante|Codigo do Fabricante
TQR|05|TQR_NOMFAB|C|20|0|Nome|Nome do Fabricante
TQR|06|TQR_CPPROD|N|9|2|Capac. Prod.|Capacidade Produtiva
TQR|07|TQR_UNPROD|C|2|0|Un. Med. C.|Unidade de Med. Cap. Prod
TQR|08|TQR_CATBEM|C|1|0|Categ. Bem|Categoria do Bem
TQR|09|TQR_VALALU|N|12|2|Val. Locação|Valor Locação
--- ### TQW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQW|01|TQW_FILIAL|C|6|0|Filial|Filial do Sistema
TQW|02|TQW_STATUS|C|6|0|Status da OS|Status Ordem de Servico
TQW|03|TQW_DESTAT|C|40|0|Desc. Status|Descricao do Status da OS
TQW|04|TQW_CORSTA|C|2|0|Cor Status|Cor Status
TQW|05|TQW_TIPOST|C|2|0|Tipo Status|Tipo do Status da OS
--- ### TQY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQY|01|TQY_FILIAL|C|6|0|Filial|Filial do Sistema
TQY|02|TQY_STATUS|C|2|0|Cod Status|Codigo do Status
TQY|03|TQY_DESTAT|C|30|0|Desc Status|Descricao do Status
TQY|04|TQY_CATBEM|C|1|0|Categ. Bem|Categoria do Bem
--- ### TR5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR5|01|TR5_FILIAL|C|6|0|Filial|Filial do Sistema
TR5|02|TR5_CODPEN|C|6|0|Cod Pendenc.|Codigo da Pendencia
TR5|03|TR5_DESPEN|C|40|0|Descricao|Descricao da Pendencia
--- ### TRW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRW|01|TRW_FILIAL|C|6|0|Filial|Filial do Sistema
TRW|02|TRW_HUB|C|2|0|Grupo Filial|Codigo Grupo de Filial
TRW|03|TRW_DESHUB|C|40|0|Descricao|Descricao Grupo de Filial
TRW|04|TRW_MAT|C|6|0|Responsavel|Matric Funcionario Respon
TRW|05|TRW_MATRES|C|40|0|Nome Resp|Nome Responsavel
--- ### TSA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSA|01|TSA_FILIAL|C|6|0|Filial|Filial do Sistema
TSA|02|TSA_NIVEL|C|2|0|Nivel|Nivel Hierarquia Aprovac.
TSA|03|TSA_SERVIC|C|6|0|Servico|Servico
TSA|04|TSA_DESSER|C|30|0|Nome Servico|Nome Servico
TSA|05|TSA_TPCTRL|C|1|0|Tip.Controle|Tip.Controle
TSA|06|TSA_ITNGRT|C|1|0|Itens Garant|Itens Garantia
TSA|07|TSA_VALINI|N|9|2|Valor Inic.|Valor Inicial
TSA|08|TSA_VALFIM|N|9|2|Valor Final|Valor Final
TSA|09|TSA_GERFLX|C|1|0|Gera Fluxo ?|Gera Fluxo ?
TSA|10|TSA_FILAPR|C|6|0|F.Aprovador|Filial Aprovadores
TSA|11|TSA_APROV1|C|6|0|Aprovador 1|Usuario Aprovador 1
TSA|12|TSA_NAPRO1|C|30|0|Nome|Nome Aprovador 1
TSA|13|TSA_APROV2|C|6|0|Aprovador 2|Usuario do Aprovador 2
TSA|14|TSA_NAPRO2|C|30|0|Nome|Nome Aprovador 2
--- ### TSB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSB|01|TSB_FILIAL|C|6|0|Filial|Filial do Sistema
TSB|02|TSB_NIVEL|C|2|0|Nivel Aprov.|Nivel de Aprovacao
TSB|03|TSB_ORDEM|C|6|0|Ordem Serv.|Numero da Ordem Servico
TSB|04|TSB_PLANO|C|6|0|Plano Manut.|Numero do Plano de Manut.
TSB|05|TSB_FILAPR|C|6|0|Filial Aprov|Codigo da Filial Aprovado
TSB|06|TSB_APROV1|C|15|0|Aprovador 1|Codigo do Aprovador 1
TSB|07|TSB_APROV2|C|15|0|Aprovador 2|Codigo do Aprovador 2
TSB|08|TSB_FLGAPR|C|1|0|Flag de Apro|Flag de Aprovacao
TSB|09|TSB_SITUAC|C|1|0|Situacao|Situacao da Aprovacao
TSB|10|TSB_CUSTOS|N|12|2|Custo da OS|Custo da Ordem de servico
TSB|11|TSB_CUSTOM|N|12|2|Custo no Mes|Custo no Mes
TSB|12|TSB_CUSTOA|N|12|2|Custo no Ano|Custo no Ano
TSB|13|TSB_OBSERV|M|10|0|Oservacao|Oservacao
--- ### TSC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSC|01|TSC_FILIAL|C|6|0|Filial|Filial do Sistema
TSC|02|TSC_CODBEM|C|16|0|Bem|Codigo do Bem
TSC|03|TSC_ANO|C|4|0|Ano Lancamen|Ano do Lancamento
TSC|04|TSC_MES|C|2|0|Mes Lancamen|Mes do Lancamento
TSC|05|TSC_CUSTOS|N|12|2|Custo das OS|Custo das OS no Ano Mes
--- ### TSK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSK|01|TSK_FILIAL|C|6|0|Filial|Filial do Sistema
TSK|02|TSK_FILMS|C|6|0|Fil. Totvs|Filial Totvs
TSK|03|TSK_TIPUSE|C|1|0|Tipo Usuário|Tipo de Usuário
TSK|04|TSK_CODFUN|C|6|0|Funcionário|Código do Funcionário
TSK|05|TSK_NOME|C|20|0|Nome|Nome do Funcionário
TSK|06|TSK_EMAIL|C|50|0|Email|Email do Funcionario
TSK|07|TSK_PROCES|C|1|0|Processo|Indica o Processo
TSK|08|TSK_LISTWF|M|10|0|Lista WFs.|Lista de Workflows
--- ### TSL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSL|01|TSL_FILIAL|C|6|0|Filial|Filial do Sistema
TSL|02|TSL_FILMS|C|6|0|Fil. Totvs|Filial Totvs
TSL|03|TSL_DESFIL|C|25|0|Descrição|Descrição Filial Totvs
TSL|04|TSL_MEDIA|N|9|2|Média|Média Consumo Combustível
TSL|05|TSL_HUB|C|2|0|Grupo|Código do Grupo
TSL|06|TSL_DESHUB|C|20|0|Descrição|Descrição do Grupo
--- ### TSM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSM|01|TSM_FILIAL|C|6|0|Filial|Filial do Sistema
TSM|02|TSM_LOTE|C|6|0|Lote Transf.|Lote de Transferencia
TSM|03|TSM_DESLOT|C|40|0|Desc. Lote|Descricao do Lote
TSM|04|TSM_DTLOTE|D|8|0|Data do Lote|Data do Lote
TSM|05|TSM_DESTIN|C|40|0|Destino|Destino do Lote
TSM|06|TSM_DTFECH|D|8|0|Dt.Fech.Lote|Data Fechamento Lote
TSM|07|TSM_OBSERV|M|10|0|Observacao|Observacao
--- ### TSN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSN|01|TSN_FILIAL|C|6|0|Filial|Filial do Sistema
TSN|02|TSN_LOTE|C|6|0|Lote Transf.|Lote de Transferencia
TSN|03|TSN_CODBEM|C|16|0|Bem|Codigo do Bem
TSN|04|TSN_DESBEM|C|40|0|Desc. Bem|Descricao do Bem
TSN|05|TSN_FILBEM|C|6|0|Filial Bem|Filial do Bem
TSN|06|TSN_STATUS|C|2|0|Status|Status do Bem
TSN|07|TSN_DESTAT|C|40|0|Desc. Status|Descricao do Bem
--- ### TSW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSW|01|TSW_FILIAL|C|6|0|Filial|Filial do Sistema
TSW|02|TSW_CUNNEG|C|2|0|U. Negocio|Unidade de Negocio
TSW|03|TSW_DUNNEG|C|40|0|Descricao|Descricao
--- ### TSZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSZ|01|TSZ_FILIAL|C|6|0|Filial|Filial do Sistema
TSZ|02|TSZ_CODSER|C|3|0|Operacao|Codigo da Operacao
TSZ|03|TSZ_DESSER|C|40|0|Descricao|Descricao da Operacao
--- ### TT0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT0|01|TT0_FILIAL|C|6|0|Filial|Filial do Sistema
TT0|02|TT0_ORDEM|C|6|0|Ordem Serv.|Ordem de Servico
TT0|03|TT0_PLANO|C|6|0|Plano|Codigo do Plano
TT0|04|TT0_USUARI|C|25|0|Usuario Alt.|Usuario da Alteracao
TT0|05|TT0_STAORI|C|6|0|Stat.OS Orig|Status da OS Original
TT0|06|TT0_STAALT|C|6|0|Stat.OS Alt.|Status da OS Alterada
TT0|07|TT0_DATAAL|D|8|0|Dt. Alterac.|Data Alter. Status da OS
TT0|08|TT0_HRALTE|C|5|0|Hr. Alterac.|Hora Alter. Status da OS
TT0|09|TT0_MOTALT|M|10|0|Motivo Alt.|Motivo Alteracao Status
--- ### TT1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT1|01|TT1_FILIAL|C|6|0|Filial|Filial do Sistema
TT1|02|TT1_CODIGO|C|6|0|Programacao|Programacao
TT1|03|TT1_DESCRI|C|60|0|Descricao|Descricao
TT1|04|TT1_DTPROG|D|8|0|Data Prog.|Data Programacao
TT1|05|TT1_DTFIM|D|8|0|Data Fim|Data Fim
TT1|06|TT1_RESPON|C|6|0|Responsavel|Responsavel
TT1|07|TT1_NOMRES|C|30|0|Nome Resp.|Nome Resp.
TT1|08|TT1_USERGI|C|17|0|Log de Inclu|Log de Inclusao
TT1|09|TT1_USERGA|C|17|0|Log de Alter|Log de Alteracao
TT1|10|TT1_BEMDE|C|16|0|De Bem|De Bem
TT1|11|TT1_BEMATE|C|16|0|Ate Bem|Ate Bem
TT1|12|TT1_EQUDE|C|6|0|De Equipe|De Equipe
TT1|13|TT1_EQUATE|C|6|0|Ate Equipe|Ate Equipe
TT1|14|TT1_CCDE|C|9|0|De C.Custo|De C.Custo
TT1|15|TT1_CCATE|C|9|0|Ate C.Custo|Ate C.Custo
TT1|16|TT1_STADE|C|6|0|De Status|De Status
TT1|17|TT1_STAATE|C|6|0|Ate Status|Ate Status
TT1|18|TT1_DTDE|D|8|0|De Data|De Data
TT1|19|TT1_DTATE|D|8|0|Ate Data|Ate Data
TT1|20|TT1_DTCALE|D|8|0|Dt. Calendar|Data Calendario
TT1|21|TT1_TRADE|C|6|0|De C. Trab.|De Centro Trabalho
TT1|22|TT1_TRAATE|C|6|0|Ate C. Trab.|Ate Centro Trabalho
TT1|23|TT1_TIPDE|C|3|0|De Tipo|De Tipo Manutencao
TT1|24|TT1_TIPATE|C|3|0|Ate Tipo|Ate Tipo Manutencao
TT1|25|TT1_AREDE|C|6|0|De Area|De Area Manutencao
TT1|26|TT1_AREATE|C|6|0|Ate Area|Ate Area Manutencao
TT1|27|TT1_FAMDE|C|6|0|De Familia|De Familia
TT1|28|TT1_FAMATE|C|6|0|Ate Familia|Ate Familia
TT1|29|TT1_SERDE|C|6|0|De Servico|De Servico
TT1|30|TT1_SERATE|C|6|0|Ate Servico|Ate Servico
TT1|31|TT1_ORDDE|C|6|0|De Ordem|De Ordem
TT1|32|TT1_ORDATE|C|6|0|Ate Ordem|Ate Ordem
TT1|33|TT1_PLADE|C|6|0|De Plano|De Plano
TT1|34|TT1_PLAATE|C|6|0|Ate Plano|Ate Plano
TT1|35|TT1_VEROSS|C|1|0|Ver OS?|Ver OS?
TT1|36|TT1_EVEDE|C|6|0|De Evento|De Evento
TT1|37|TT1_EVEATE|C|6|0|Ate Evento|Ate Evento
TT1|38|TT1_CDEVEN|C|6|0|Evento|Evento
TT1|39|TT1_INDLUB|C|1|0|O.S. Lubrif.|O.S. Lubrif.
TT1|40|TT1_INDLOC|C|1|0|O.S. Locali.|O.S. Locali.
TT1|41|TT1_CONDTA|C|1|0|Dt. atrasada|Data Atrasada?
TT1|42|TT1_PROGAU|C|1|0|Prog. Auto.?|Prgramação Automatica?
TT1|43|TT1_PRIDE|C|3|0|De Priorid.|De Prioridade
TT1|44|TT1_PRIATE|C|3|0|Ate Priorid.|Ate Prioridade
TT1|45|TT1_ETADE|C|6|0|De Etapa|De Etapa
TT1|46|TT1_ETAAT|C|6|0|Ate Etapa|Ate Etapa
TT1|47|TT1_INCRE|C|1|0|Incremento|Incremento
TT1|48|TT1_QTDDIA|N|4|0|Dias|Dias
TT1|49|TT1_CALEDE|C|3|0|De Calend.|De Calendario
TT1|50|TT1_CALEAT|C|3|0|Ate Calend.|Ate Calendario
TT1|51|TT1_ESTRUT|C|1|0|Estrutura|Estrutura
--- ### TT2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT2|01|TT2_FILIAL|C|6|0|Filial|Filial do Sistema
TT2|02|TT2_CODIGO|C|6|0|Codigo|Codigo
TT2|03|TT2_TIPO|C|1|0|Tipo OS|Tipo OS
TT2|04|TT2_MARCA|C|2|0|Marcado|Marcado
TT2|05|TT2_SEQ|C|5|0|Sequencia|Sequencia
TT2|06|TT2_PRIORI|C|3|0|Prioridade|Prioridade
TT2|07|TT2_ORDEM|C|6|0|Ordem|Ordem
TT2|08|TT2_PLANO|C|6|0|Plano|Plano
TT2|09|TT2_CODBEM|C|16|0|Codigo Bem|Codigo Bem
TT2|10|TT2_EQUIPE|C|6|0|Equipe|Equipe
TT2|11|TT2_DTORIG|D|8|0|Dt. Original|Dt. Original
TT2|12|TT2_DTINI|D|8|0|Data Inicio|Data Inicio
TT2|13|TT2_STATUS|C|6|0|Status|Status
TT2|14|TT2_SITUAC|C|1|0|Situacao|Situacao
TT2|15|TT2_REALIZ|C|1|0|Insumo Reali|Insumo Reali
TT2|16|TT2_LIBERA|C|1|0|Liberado|Liberado
TT2|17|TT2_DTPROG|D|8|0|Data Prog.|Data Prog.
TT2|18|TT2_EVENTO|C|6|0|Evento|Evento
--- ### TT3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT3|01|TT3_FILIAL|C|6|0|Filial|Filial do Sistema
TT3|02|TT3_NUMERO|C|6|0|Num. Program|Num. Program
TT3|03|TT3_ORDEM|C|6|0|Ordem|Ordem
TT3|04|TT3_PLANO|C|6|0|Plano|Plano
TT3|05|TT3_CODIGO|C|6|0|Codigo|Codigo
TT3|06|TT3_QTDE|N|8|2|Quantidade|Quantidade
--- ### TT4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT4|01|TT4_FILIAL|C|6|0|Filial|Filial do Sistema
TT4|02|TT4_NUMERO|C|6|0|Num. Program|Num. Program
TT4|03|TT4_ORDEM|C|6|0|Ordem|Ordem
TT4|04|TT4_PLANO|C|6|0|Plano|Plano
TT4|05|TT4_CODIGO|C|15|0|Codigo|Codigo
TT4|06|TT4_QTDE|N|10|2|Quantidade|Quantidade
TT4|07|TT4_NUMSC|C|6|0|Numero S.C.|Numero S.C.
TT4|08|TT4_DATASC|D|8|0|Dt. Prevista|Dt. Prevista
TT4|09|TT4_NUMSA|C|6|0|Numero S.A.|Numero S.A.
TT4|10|TT4_ITEMSA|C|2|0|Item S.A.|Item S.A.
--- ### TT5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT5|01|TT5_FILIAL|C|6|0|Filial|Filial do Sistema
TT5|02|TT5_NUMERO|C|6|0|Num. Program|Num. Program
TT5|03|TT5_ORDEM|C|6|0|Ordem|Ordem
TT5|04|TT5_PLANO|C|6|0|Plano|Plano
TT5|05|TT5_CODIGO|C|3|0|Codigo|Codigo
TT5|06|TT5_QTDTEC|N|6|0|Qtd Recurso|Qtd Recurso
TT5|07|TT5_TOTTEC|N|6|0|Qtd Tecnicos|Qtd Tecnicos
TT5|08|TT5_TECADD|N|3|0|Tec.Adicion.|Tec.Adicion.
TT5|09|TT5_DIAADD|N|4|1|Dias Adicion|Dias Adicion
TT5|10|TT5_TECAUS|N|3|0|Tec.Ausentes|Tec.Ausentes
TT5|11|TT5_DIAAUS|N|4|1|Dias Ausente|Dias Ausente
TT5|12|TT5_TEMPRO|C|8|0|Tempo Previs|Tempo Progr.
TT5|13|TT5_TEMDIS|C|8|0|Tempo Dispon|Tempo Dispon
TT5|14|TT5_OBS|C|50|0|Observacao|Observacao
TT5|15|TT5_TEMREA|C|8|0|Tempo Progr.|Tempo Progr.
--- ### TT6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT6|01|TT6_FILIAL|C|6|0|Filial|Filial do Sistema
TT6|02|TT6_PROTHE|C|3|0|Tab Protheus|Tabela Protheus
TT6|03|TT6_LOGIX|C|30|0|Tabela Logix|Tabela Logix
TT6|04|TT6_DE|C|30|0|De Logix|De Logix
TT6|05|TT6_PARA|C|30|0|P/ Protheus|Para Protheus
TT6|06|TT6_ORIGEM|C|1|0|Origem Inf.|Origem da informação
--- ### TT7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT7|01|TT7_FILIAL|C|6|0|Filial|Filial do Sistema
TT7|02|TT7_SOLICI|C|6|0|Solicitacao|Solicitacao de Servico
TT7|03|TT7_ORDEM|C|6|0|Ordem Servic|Ordem de Servico
TT7|04|TT7_PLANO|C|6|0|Plano Manut.|Plano de Manutencao
TT7|05|TT7_SITUAC|C|1|0|Situacao|Situacao da Ordem de Serv
TT7|06|TT7_TERMIN|C|1|0|Termino|OS Terminada? (S/N)
--- ### TT8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT8|01|TT8_FILIAL|C|6|0|Filial|Filial do Sistema
TT8|02|TT8_CODBEM|C|16|0|Bem|Código do Bem
TT8|03|TT8_TIPO|C|1|0|Tipo|Tipo Produto
TT8|04|TT8_CODCOM|C|15|0|Produto|Produto/Aditivo
TT8|05|TT8_NOMCOM|C|20|0|Descrição|Descrição do Combustível
TT8|06|TT8_CAPMAX|N|7|0|Cap. Tanque|Capacidade do Tanque
TT8|07|TT8_MEDIA|N|9|2|Consumo Méd.|Consumo Médio
TT8|08|TT8_MEDMIN|N|9|2|Med. Minima|Consumo Minimo
TT8|09|TT8_TPCONT|C|1|0|Tip.Contador|Tipo  de Contador
--- ### TT9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TT9|01|TT9_FILIAL|C|6|0|Filial|Filial do Sistema
TT9|02|TT9_TAREFA|C|6|0|Tarefa|Codigo Tarefa
TT9|03|TT9_DESCRI|C|40|0|Descricao|Descricao Tarefa
TT9|04|TT9_CARACT|C|1|0|Caracterist.|Caracteristica da tarefa
--- ### TTB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTB|01|TTB_FILIAL|C|6|0|Filial|Filial do Sistema
TTB|02|TTB_CDSINT|C|6|0|Cod. Sintoma|Código do Sintoma
TTB|03|TTB_DESSIN|C|40|0|Descrição|Descrição do Sintoma
TTB|04|TTB_CDSERV|C|6|0|Área Serviço|Área Serviço
TTB|05|TTB_TEMPOM|C|5|0|Tempo Médio|Tempo Médio
TTB|06|TTB_BLOQPT|C|1|0|Bloq. Porta.|Bloqueia Portaria
--- ### TTC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTC|01|TTC_FILIAL|C|6|0|Filial|Filial do Sistema
TTC|02|TTC_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TTC|03|TTC_ORDEM|C|6|0|Ordem Serv.|Ordem de Servico
TTC|04|TTC_PLANO|C|6|0|Plano Manut.|Plano de Manutencao
TTC|05|TTC_DATA|D|8|0|Data da O.S.|Data da O.S.
TTC|06|TTC_CDSINT|C|6|0|Sintoma|Codigo do Sintoma
TTC|07|TTC_DESSIN|C|20|0|Desc Sintoma|Descricao do Sintoma
--- ### TTD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTD|01|TTD_FILIAL|C|6|0|Filial|Filial do Sistema
TTD|02|TTD_CODFAM|C|6|0|Familia|Codigo da Familia
TTD|03|TTD_NOMFAM|C|20|0|Nome Familia|Nome da Familia
TTD|04|TTD_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo de Modelo
TTD|05|TTD_DESMOD|C|20|0|Descricao|Descricao Tipo do Modelo
TTD|06|TTD_SEQFAM|C|3|0|Seq. Fam.|Sequência da Família
--- ### TTE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTE|01|TTE_FILIAL|C|6|0|Filial|Filial do Sistema
TTE|02|TTE_CODFAM|C|6|0|Familia|Codigo da Familia
TTE|03|TTE_TIPMOD|C|10|0|Tipo do Mode|Codigo do Tipo de Modelo
TTE|04|TTE_ETAPA|C|6|0|Etapa|Codigo da Etapa
TTE|05|TTE_NOMETA|C|40|0|Descr. Etapa|Descricao da Etapa
TTE|06|TTE_ALTA|C|1|0|Alta|Alta
TTE|07|TTE_MEDIA|C|1|0|Media|Media
TTE|08|TTE_BAIXA|C|1|0|Baixa|Baixa
TTE|09|TTE_SERVIC|C|6|0|Servico|Codigo do Servico
TTE|10|TTE_NOMSER|C|20|0|Desc Servico|Descricao do Servico
TTE|11|TTE_SEQFAM|C|3|0|Seq. Fam.|Sequência da Família
--- ### TTF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTF|01|TTF_FILIAL|C|6|0|Filial|Filial do Sistema
TTF|02|TTF_CHECK|C|6|0|Check List|Check List
TTF|03|TTF_CODBEM|C|16|0|Bem|Codigo do Bem
TTF|04|TTF_NOMBEM|C|20|0|Descrição|Descrição do Bem
TTF|05|TTF_PLACA|C|8|0|Placa|Placa
TTF|06|TTF_CODFAM|C|6|0|Família|Codigo da Família
TTF|07|TTF_NOMFAM|C|20|0|Nome Família|Nome da Família
TTF|08|TTF_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo de Modelo
TTF|09|TTF_DESMOD|C|20|0|Descrição|Descrição Tipo do Modelo
TTF|10|TTF_CODFUN|C|6|0|Executante|Codigo do Executante
TTF|11|TTF_NOMFUN|C|20|0|Nome|Nome
TTF|12|TTF_DATA|D|8|0|Data|Data
TTF|13|TTF_HORA|C|5|0|Hora|Hora
TTF|14|TTF_POSCON|N|9|0|Contador 1|Posicao do Contador 1
TTF|15|TTF_POSCO2|N|9|0|Contador 2|Posicao do Contador 2
TTF|16|TTF_RAMAL|C|10|0|Ramal|Numero do Ramal do Exec.
TTF|17|TTF_OBS|M|10|0|Observação|Observação
TTF|18|TTF_SEQFAM|C|3|0|Seq. Fam.|Sequência da Família
--- ### TTG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTG|01|TTG_FILIAL|C|6|0|Filial|Filial do Sistema
TTG|02|TTG_CHECK|C|6|0|Check List|Check List
TTG|03|TTG_ETAPA|C|6|0|Etapa|Codigo da Etapa
TTG|04|TTG_NOMETA|C|40|0|Descr. Etapa|Descricao da Etapa
TTG|05|TTG_EVENTO|C|1|0|Evento|Evento do Check List
TTG|06|TTG_NUMERO|C|6|0|Número|Número da O.S ou S.S
TTG|07|TTG_SERVIC|C|6|0|Serviço|Codigo do Serviço
TTG|08|TTG_CRITIC|C|1|0|Criticidade|Criticidade
--- ### TTJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTJ|01|TTJ_FILIAL|C|6|0|Filial|Filial do Sistema
TTJ|02|TTJ_TPHORA|C|6|0|Tipo Hora|Tipo de Hora
TTJ|03|TTJ_DESCRI|C|40|0|Descrição|Descrição do Tipo de Hora
TTJ|04|TTJ_CLASSI|C|1|0|Classific.|Classificação
TTJ|05|TTJ_USACAL|C|1|0|Usa Calend.|Usa Calendario
--- ### TTL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTL|01|TTL_FILIAL|C|6|0|Filial|Filial do Sistema
TTL|02|TTL_CODFUN|C|6|0|Cod. Func.|Código Funcionário
TTL|03|TTL_NOMFUN|C|20|0|Nome|Nome do Funcionario
TTL|04|TTL_TPHORA|C|6|0|Tipo Hora|Tipo de Hora
TTL|05|TTL_NOMTPH|C|40|0|Descrição|Descrição do Tipo Hora
TTL|06|TTL_QUANTI|N|9|2|Quant. Hora|Quantidade de Horas
TTL|07|TTL_DTINI|D|8|0|Dt. Início|Data Início
TTL|08|TTL_HRINI|C|5|0|Hr. Início|Hora Início
TTL|09|TTL_DTFIM|D|8|0|Dt. Fim|Data Fim
TTL|10|TTL_HRFIM|C|5|0|Hr. Fim|Hora Fim
TTL|11|TTL_TIPOHO|C|1|0|Tipo Hora|Tipo de Hora
TTL|12|TTL_PCTHRE|N|6|2|% Hr. Extra|Percentual Hora Extra
--- ### TTQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTQ|01|TTQ_FILIAL|C|6|0|Filial|Filial do Sistema
TTQ|02|TTQ_CODIGO|C|6|0|Evento|Evento
TTQ|03|TTQ_DESCRI|C|60|0|Descricao|Descricao
TTQ|04|TTQ_RESPON|C|6|0|Responsavel|Responsavel
TTQ|05|TTQ_NOMRES|C|30|0|Nome Resp.|Nome Responsavel
TTQ|06|TTQ_DTINI|D|8|0|Data Inicio|Data Inicio
TTQ|07|TTQ_DTFIM|D|8|0|Data Fim|Data Fim
--- ### TTY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTY|01|TTY_FILIAL|C|6|0|Filial|Filial do Sistema
TTY|02|TTY_CODESP|C|3|0|Cod. Espec.|Codigo Especialidade
TTY|03|TTY_ORDEM|C|6|0|Ordem|Ordem de Servico
TTY|04|TTY_PLANO|C|6|0|Plano|Plano
TTY|05|TTY_TAREFA|C|6|0|Tarefa|Tarefa
TTY|06|TTY_DTINI|D|8|0|Dt. Bloqueio|Data do Bloqueio
TTY|07|TTY_HRINI|C|5|0|Hr. Bloqueio|Hora do Bloqueio
TTY|08|TTY_DTFIM|D|8|0|Data Fim|Data Fim
TTY|09|TTY_HRFIM|C|5|0|Hora Fim|Hora Fim
TTY|10|TTY_QUANTI|N|3|0|Quantidade|Quantidade Bloqueada
TTY|11|TTY_MOTIVO|C|40|0|Motivo|Motivo do Bloqueio
--- ### TU0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU0|01|TU0_FILIAL|C|6|0|Filial|Filial do Sistema
TU0|02|TU0_OPCAO|C|6|0|Codigo|Codigo da Opcao
TU0|03|TU0_DESCRI|C|20|0|Descrição|Descrição da Opção
TU0|04|TU0_VISIBL|C|1|0|Visível|Item Visível
TU0|05|TU0_PROPRI|C|1|0|Proprietário|Proprietário
--- ### TU1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU1|01|TU1_FILIAL|C|6|0|Filial|Filial do Sistema
TU1|02|TU1_OPCAO|C|6|0|Código Opção|Código da Opção
TU1|03|TU1_TIPIMG|C|1|0|Tipo Imagem|Tipo de Imagem
TU1|04|TU1_IMAGEM|C|30|0|Imagem|Imagem
TU1|05|TU1_DESCRI|C|15|0|Descrição|Descrição da Imagem
TU1|06|TU1_TOOLTI|C|40|0|ToolTip|Tooltip
TU1|07|TU1_VISIBL|C|1|0|Visível|Item Visível
TU1|08|TU1_PROPRI|C|1|0|Proprietário|Proprietário
--- ### TU2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU2|01|TU2_FILIAL|C|6|0|Filial|Filial do Sistema
TU2|02|TU2_CODFAM|C|6|0|Família|Família Bem/Loc.
TU2|03|TU2_DESFAM|C|30|0|Descrição|Descrição Fam.
TU2|04|TU2_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo
TU2|05|TU2_DESMOD|C|30|0|Descrição|Descrição Tipo
--- ### TU3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU3|01|TU3_FILIAL|C|6|0|Filial|Filial do Sistema
TU3|02|TU3_CODFAM|C|6|0|Família|Família Bem/Loc.
TU3|03|TU3_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo
TU3|04|TU3_CODNIV|C|3|0|Código Item|Código Item
TU3|05|TU3_NIVSUP|C|3|0|Item Super.|Item Superior
TU3|06|TU3_ORDEM|C|3|0|Ordem|Ordem
TU3|07|TU3_TIPO|C|1|0|Tipo|Tipo Item
TU3|08|TU3_CODOCO|C|6|0|Ocorrência|Ocorrência
TU3|09|TU3_DESOCO|C|40|0|Descrição|Descrição Ocorrência
TU3|10|TU3_CDSERV|C|6|0|Tipo Serviço|Código do Tipo Serviço
TU3|11|TU3_NMSERV|C|30|0|Nome Serviço|Nome do Tipo Serviço
TU3|12|TU3_PERGUN|C|50|0|Pergunta|Pergunta
TU3|13|TU3_COMBO|C|250|0|Opções|Opções
TU3|14|TU3_TPLIST|C|1|0|Tipo Respost|Tipo Resposta
TU3|15|TU3_PERGOP|C|100|0|Opção Perg.|Opção Perg.
--- ### TU7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU7|01|TU7_FILIAL|C|6|0|Filial|Filial do Sistema
TU7|02|TU7_OPCAO|C|1|0|Opção|Opção
TU7|03|TU7_CODIGO|C|20|0|Código|Código
TU7|04|TU7_DESCRI|C|40|0|Descrição|Descrição
TU7|05|TU7_CRITIC|N|3|0|Criticidade|Criticidade
--- ### TU9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU9|01|TU9_FILIAL|C|6|0|Filial|Filial do Sistema
TU9|02|TU9_CODIGO|C|3|0|Código|Código
TU9|03|TU9_PERCIN|N|3|0|% Inicial|% Inicial
TU9|04|TU9_PERCFI|N|3|0|% Final|% Final
TU9|05|TU9_DESCRI|C|40|0|Descrição|Descrição
TU9|06|TU9_OBSERV|C|6|0|Observação|Observação
TU9|07|TU9_MEMO|M|80|0|Observação|Observação
TU9|08|TU9_CORLEG|C|1|0|Cor Legenda|Cor Legenda
TU9|09|TU9_DESLEG|C|20|0|Desc. Leg.|Desc. Leg.
TU9|10|TU9_TMPMAX|C|7|0|Tempo Máx.|Tempo Máx.
TU9|11|TU9_PRIORI|C|1|0|Prioridade|Prioridade
--- ### TUA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUA|01|TUA_FILIAL|C|6|0|Filial|Filial do Sistema
TUA|02|TUA_TIPRES|C|1|0|Tp. Restri.|Tipo Restrição
TUA|03|TUA_TIPO|C|1|0|Tipo|Tipo
TUA|04|TUA_GRPUSR|C|6|0|Codigo|Codigo
TUA|05|TUA_NOME|C|30|0|Nome|Nome
TUA|06|TUA_INFSER|C|1|0|Inf. Serviço|Informa Serviço
TUA|07|TUA_INCTER|C|1|0|Outro Usuár.|Inclui Para Outro Usuário
TUA|08|TUA_INFTPS|C|1|0|Inf. Tp. Ser|Inf. Tp. Ser."
TUA|09|TUA_VISBEM|C|1|0|Vis. Td. Ben|Vis. Td. Bens
TUA|10|TUA_DISTSS|C|1|0|Distrib. SS?|Distrib. SS?
TUA|11|TUA_TRANSS|C|1|0|Transf. SS?|Transf. SS?
TUA|12|TUA_CANCSS|C|1|0|Cancela SS?|Cancela SS?
TUA|13|TUA_FECHSS|C|1|0|Fecha SS?|Fecha SS?
--- ### TUB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUB|01|TUB_FILIAL|C|6|0|Filial|Filial do Sistema
TUB|02|TUB_TIPRES|C|1|0|Tp. Restri.|Tipo Restrição
TUB|03|TUB_TIPO|C|1|0|Tipo|Tipo
TUB|04|TUB_GRPUSR|C|6|0|Codigo|Codigo
TUB|05|TUB_OPCAO|C|1|0|Opção|Opção
TUB|06|TUB_CODIGO|C|20|0|Codigo|Codigo
TUB|07|TUB_FILTRO|C|1|0|Ger. Filtro|Gerado pelo Filtro
TUB|08|TUB_MARCA|C|1|0|Marcado|Marcado ou Desmarcado
TUB|09|TUB_RESTRI|C|50|0|Restrições|Restrições
--- ### TUC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUC|01|TUC_FILIAL|C|6|0|Filial|Filial do Sistema
TUC|02|TUC_OPCAO|C|1|0|Opção|Opção
TUC|03|TUC_CODIGO|C|20|0|Código|Código
TUC|04|TUC_PERINI|C|5|0|Período Ini.|Período Início
TUC|05|TUC_PERFIM|C|5|0|Período Fim|Período Fim
TUC|06|TUC_CRITIC|N|3|0|Criticidade|Criticidade
--- ### TUD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUD|01|TUD_FILIAL|C|6|0|Filial|Filial do Sistema
TUD|02|TUD_CODIGO|C|6|0|Código|Código
TUD|03|TUD_TIPATE|C|1|0|Tipo Atend.|Tipo Atendente
TUD|04|TUD_FILATE|C|6|0|Filial Atend|Filial Atendente
TUD|05|TUD_CODATE|C|6|0|Atendente|Atendente
TUD|06|TUD_DESATE|C|30|0|Nome|Nome do Atendente
TUD|07|TUD_DESCRI|C|40|0|Descrição|Descrição
TUD|08|TUD_LOGICA|C|1|0|Lógica de Va|Lógica de Validação
--- ### TUE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUE|01|TUE_FILIAL|C|6|0|Filial|Filial do Sistema
TUE|02|TUE_CODREG|C|6|0|Código Regra|Código Regra
TUE|03|TUE_TIPO|C|1|0|Tipo|Tipo Parâmetro
TUE|04|TUE_CODIGO|C|9|0|Código|Código
TUE|05|TUE_DESCRI|C|30|0|Descrição|Descrição
TUE|06|TUE_PERINI|C|5|0|Período Inic|Período Inicio
TUE|07|TUE_PERFIM|C|5|0|Período Fim|Período Fim
--- ### TUF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUF|01|TUF_FILIAL|C|6|0|Filial|Filial do Sistema
TUF|02|TUF_CODUSR|C|6|0|Usuário|Usuário
TUF|03|TUF_LOGUSR|C|25|0|Login|Login
TUF|04|TUF_NOMUSR|C|40|0|Nome|Nome
TUF|05|TUF_DEPUSR|C|40|0|Departamento|Departamento
TUF|06|TUF_CARUSR|C|40|0|Cargo|Cargo
TUF|07|TUF_EMAUSR|C|60|0|E-mail|E-mail
TUF|08|TUF_RAMUSR|C|4|0|Ramal|Ramal
TUF|09|TUF_TE1USR|C|14|0|Contato 1|Contato 1
TUF|10|TUF_TE2USR|C|14|0|Contato 2|Contato 2
--- ### TUG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUG|01|TUG_FILIAL|C|6|0|Filial|Filial do Sistema
TUG|02|TUG_CODFAM|C|6|0|Família|Família Bem/Loc.
TUG|03|TUG_DESFAM|C|30|0|Descrição|Descrição Fam.
TUG|04|TUG_CDSERV|C|6|0|Tipo Serviço|Código do Tipo Serviço
TUG|05|TUG_NMSERV|C|20|0|Nome Serviço|Nome do Tipo Serviço
TUG|06|TUG_QTDREI|N|3|0|Tempo Reinc.|Tempo Reincidência
TUG|07|TUG_UNIREI|C|1|0|Un. Reincid.|Unidade Reincidência
TUG|08|TUG_TMPMAX|C|6|0|Tempo Máx.|Tempo Máx. Atendimento
--- ### TUH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUH|01|TUH_FILIAL|C|6|0|Filial|Filial do Sistema
TUH|02|TUH_CODFAM|C|6|0|Família|Família Bem/Loc.
TUH|03|TUH_CDSERV|C|6|0|Tipo Serviço|Código do Tipo Serviço
TUH|04|TUH_TIPATE|C|1|0|Tipo Atend.|Tipo Atendente
TUH|05|TUH_FILATE|C|6|0|Filial Atend|Filial do Atendente
TUH|06|TUH_CODATE|C|20|0|Atendente|Atendente
TUH|07|TUH_LOJATE|C|2|0|Loja Atend.|Loja do Atendente
TUH|08|TUH_DESATE|C|30|0|Nome|Nome do Atendente
TUH|09|TUH_CCUSTO|C|9|0|Centro Custo|Centro Custo
TUH|10|TUH_DESCC|C|30|0|Descrição|Descrição
--- ### TUM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUM|01|TUM_FILIAL|C|6|0|Filial|Filial do Sistema
TUM|02|TUM_SOLICI|C|6|0|Solicitação|Número da Solicitação
TUM|03|TUM_CODFOL|C|6|0|Follow-up|Número do Follow-up
TUM|04|TUM_NOMFOL|C|25|0|Descrição|Descrição
TUM|05|TUM_USUARI|C|6|0|Usuário|Usuário da Ação
TUM|06|TUM_NOMUSU|C|30|0|Nome|Nome do Usuário
TUM|07|TUM_DTINIC|D|8|0|Dt. Inic.|Data de Início do Follw-u
TUM|08|TUM_HRINIC|C|8|0|Hr. Inic.|Hora de Início do Follw-u
TUM|09|TUM_DTFIM|D|8|0|Dt. Fim|Data de Term. do Follw-up
TUM|10|TUM_HRFIM|C|8|0|Hr. Fim|Hora de Term. do Follw-up
TUM|11|TUM_HRTOTA|C|9|0|Hora Total|Hora Total Atendimento
TUM|12|TUM_FILATE|C|6|0|Filial Atend|Filial do Atendente
TUM|13|TUM_ATENDE|C|6|0|Atendente|Atendente da Ação
TUM|14|TUM_NOMATE|C|40|0|Nome|Nome do Atendente
TUM|15|TUM_OBSERV|C|6|0|Observação|Observação do Follow-Up
TUM|16|TUM_MEMO1|M|80|0|Observação|Observação do Follow-Up
--- ### TUN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUN|01|TUN_FILIAL|C|6|0|Filial|Filial do Sistema
TUN|02|TUN_CODIGO|C|3|0|Código|Código do Grupo
TUN|03|TUN_DESCRI|C|40|0|Descrição|Descrição do Grupo
--- ### TUO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUO|01|TUO_FILIAL|C|6|0|Filial|Filial do Sistema
TUO|02|TUO_TIPO|C|1|0|Opção|Opção
TUO|03|TUO_CODIGO|C|20|0|Código|Código
TUO|04|TUO_LOJA|C|2|0|Loja|Loja
TUO|05|TUO_DESCRI|C|40|0|Descrição|Descrição
TUO|06|TUO_DESABI|C|1|0|Desabilita?|Questionário desabilita?
--- ### TUP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUP|01|TUP_FILIAL|C|6|0|Filial|Filial do Sistema
TUP|02|TUP_TIPO|C|1|0|Opção|Opção
TUP|03|TUP_QUESTI|C|20|0|Questionário|Código do Questionário
TUP|04|TUP_LOJA|C|2|0|Loja|Loja
TUP|05|TUP_NOMQUE|C|40|0|Descrição|Descrição do Questionário
TUP|06|TUP_QUESTA|C|3|0|Questão|Código da Questão
TUP|07|TUP_PERGUN|C|60|0|Pergunta|Pergunta da Questão
TUP|08|TUP_CODGRU|C|3|0|Grupo|Grupo Pergunta
TUP|09|TUP_NOMGRU|C|40|0|Nome Grupo|Nome Grupo Pergunta
TUP|10|TUP_ORDEM|C|6|0|Ordem|Ordem
TUP|11|TUP_TPLIST|C|1|0|Tipo Respos.|Tipo Resposta
TUP|12|TUP_ONMEMO|C|1|0|Campo Obs.|Campo Obs.
TUP|13|TUP_PERGUT|C|205|0|Respostas|Respostas Pergunta
TUP|14|TUP_2PERGU|C|205|0|Cont. Respos|Cont. Respostas Pergunta
TUP|15|TUP_VALORE|C|205|0|Valores|Valores das Respostas
--- ### TUQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUQ|01|TUQ_FILIAL|C|6|0|Filial|Filial do Sistema
TUQ|02|TUQ_SEQUEN|C|9|0|Sequência|Sequência do Questionário
TUQ|03|TUQ_TIPO|C|1|0|Opção|Opção
TUQ|04|TUQ_QUESTI|C|20|0|Questinário|Código do Questinário
TUQ|05|TUQ_LOJA|C|2|0|Loja|Loja
TUQ|06|TUQ_QUESTA|C|3|0|Questão|Código da Questão
TUQ|07|TUQ_PERGUN|C|60|0|Pergunta|Pergunta da Questão
TUQ|08|TUQ_RESPOS|C|205|0|Resposta|Resposta Pergunta
TUQ|09|TUQ_VALOR|N|2|0|Valor da Res|Valor da Resposta
TUQ|10|TUQ_CODCOM|C|6|0|Cod. Comp.|Código Complemento
TUQ|11|TUQ_COMPLE|M|80|0|Complemento|Complemento da Resposta
TUQ|12|TUQ_ORDEM|C|6|0|Ordem|Ordem
TUQ|13|TUQ_CODGRU|C|3|0|Grupo|Grupo Pergunta
TUQ|14|TUQ_TPLIST|C|1|0|Tipo Respos.|Tipo Resposta
TUQ|15|TUQ_ONMEMO|C|1|0|Campo Obs.|Campo Obs.
TUQ|16|TUQ_PERGUT|C|205|0|Respostas|Respostas Pergunta
TUQ|17|TUQ_2PERGU|C|205|0|Cont. Respos|Cont. Respostas Pergunta
--- ### TUR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUR|01|TUR_FILIAL|C|6|0|Filial|Filial do Sistema
TUR|02|TUR_SOLICI|C|6|0|Solicitação|Número da Solicitação
TUR|03|TUR_TIPO|C|1|0|Tp. Exec.|Tipo do Executante
TUR|04|TUR_FILATE|C|6|0|Filial Atend|Filial do Atendente
TUR|05|TUR_CODATE|C|20|0|Código|Código do Atendente
TUR|06|TUR_LOJATE|C|2|0|Loja Atend.|Loja do Atendente
TUR|07|TUR_DESATE|C|30|0|Nome|Nome do Atendente
TUR|08|TUR_DTRECE|D|8|0|Data Receb.|Data de Recebimento
TUR|09|TUR_HRRECE|C|8|0|Hora Receb.|Hora de Recebimento
TUR|10|TUR_DTFINA|D|8|0|Data Fim|Data Fim Atendimento
TUR|11|TUR_HRFINA|C|8|0|Hora Fim|Hora Fim Atendimento
TUR|12|TUR_HRREAL|C|9|0|Hr. Real.|Horas Realizadas
--- ### TUS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUS|01|TUS_FILIAL|C|6|0|Filial|Filial do Sistema
TUS|02|TUS_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TUS|03|TUS_TIPO|C|1|0|Tipo Carac.|Tipo da Característica
TUS|04|TUS_FAMILI|C|6|0|Família|Código da Família
TUS|05|TUS_NOMFAM|C|40|0|Descrição|Descrição da Família
--- ### TUT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUT|01|TUT_FILIAL|C|6|0|Filial|Filial do Sistema
TUT|02|TUT_CODBEM|C|16|0|Bem|Código do Bem
TUT|03|TUT_TPCONT|C|1|0|Tipo Cont.|Tipo Contador
TUT|04|TUT_CLSPRE|C|1|0|Class. Preço|Classificação do Preço
TUT|05|TUT_VALOR|N|12|2|Valor|Valor
TUT|06|TUT_CUSTHO|N|9|2|Custo Hora|Custo Hora
TUT|07|TUT_CODPRO|C|15|0|Produto|Código do produto
TUT|08|TUT_LOCAL|C|2|0|Local|Local do Produto
TUT|09|TUT_CUSTD|N|12|2|Custo Stand.|Custo Standard
TUT|10|TUT_CUSTM|N|14|4|Custo Médio|Custo Médio
--- ### TUV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUV|01|TUV_FILIAL|C|6|0|Filial|Filial
TUV|02|TUV_CODBEM|C|16|0|Bem|Código do Bem
TUV|03|TUV_TIPO|C|1|0|Tp. Status|Tipo do Status
TUV|04|TUV_DTALT|D|8|0|Dt.Alteração|Data de Alteração
TUV|05|TUV_HRALT|C|8|0|Hr.Alteração|Hora de Alteração
TUV|06|TUV_SITUAC|C|1|0|Cnt. Status|Conteúdo do Status
--- ### TUW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUW|01|TUW_FILIAL|C|6|0|Filial|Filial do Sistema
TUW|02|TUW_CODIGO|C|3|0|Código|Código do Limiar
TUW|03|TUW_DESCRI|C|40|0|Descrição|Descrição do Limiar
--- ### TUX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUX|01|TUX_FILIAL|C|6|0|Filial|Filial do Sistema
TUX|02|TUX_CODIGO|C|6|0|Código|Código
TUX|03|TUX_CODBEM|C|16|0|Bem|Bem
TUX|04|TUX_FOLDER|C|1|0|Folder|Folder
TUX|05|TUX_OBRIGA|C|1|0|Obrigatório?|Obrigatório?
TUX|06|TUX_TPINCO|C|2|0|Tp. Incons.|Tipo Inconsistência
TUX|07|TUX_CODORI|C|30|0|Cód. Origem|Cód. Origem
TUX|08|TUX_LOJORI|C|2|0|Loja Origem|Loja Origem
TUX|09|TUX_DESORI|C|30|0|Descrição|Descrição
TUX|10|TUX_CODDES|C|30|0|Cód. Destino|Cód. Destino
TUX|11|TUX_LOJDES|C|2|0|Loja Destino|Loja Destino
TUX|12|TUX_DESDES|C|30|0|Descrição|Descrição
--- ### TUY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUY|01|TUY_FILIAL|C|6|0|Filial|Filial do Sistema
TUY|02|TUY_TIPO|C|1|0|Opção|Opção
TUY|03|TUY_QUESTI|C|20|0|Questionário|Questionário
TUY|04|TUY_LOJA|C|2|0|Loja|Loja
TUY|05|TUY_LIMIAR|C|3|0|Limiar|Código do Limiar
TUY|06|TUY_DESLIM|C|40|0|Des. Limiar|Descrição do Limiar
TUY|07|TUY_LIMDE|N|4|0|De Valor|De Valor
TUY|08|TUY_LIMATE|N|4|0|Até Valor|Até Valor
--- ### TUZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUZ|01|TUZ_FILIAL|C|6|0|Filial|Filial do Sistema
TUZ|02|TUZ_CODIGO|C|6|0|Código|Código
TUZ|03|TUZ_TPOPER|C|1|0|Operação|Operação
TUZ|04|TUZ_EMPORI|C|2|0|Emp. Origem|Empresa Origem
TUZ|05|TUZ_FILORI|C|6|0|Fil. Origem|Filial Origem
TUZ|06|TUZ_DESORI|C|50|0|Desc. Orig.|Descrição Origem
TUZ|07|TUZ_CODBEM|C|16|0|Bem|Bem
TUZ|08|TUZ_DESBEM|C|20|0|Descrição|Descrição
TUZ|09|TUZ_EMPDES|C|2|0|Emp. Destino|Empresa Destino
TUZ|10|TUZ_FILDES|C|6|0|Fil. Destino|Filial Destino
TUZ|11|TUZ_DESDES|C|50|0|Desc. Dest.|Descrição Destino
TUZ|12|TUZ_DATAIN|D|8|0|Data Envio|Data Envio
TUZ|13|TUZ_HORAIN|C|5|0|Hora Envio|Hora Envio
TUZ|14|TUZ_STATUS|C|1|0|Status|Status
TUZ|15|TUZ_ORDEM|C|6|0|Ordem Serv.|Ordem Serviço
TUZ|16|TUZ_CAUSA|C|6|0|Causa Remoç.|Causa Remoção
TUZ|17|TUZ_DESCAU|C|20|0|Descrição|Descrição
TUZ|18|TUZ_MOTSYP|C|6|0|Motivo|Motivo
TUZ|19|TUZ_MOTIVO|M|80|0|Motivo|Motivo
TUZ|20|TUZ_DATATR|D|8|0|Data Transf.|Data Transferência
TUZ|21|TUZ_HORATR|C|5|0|Hora Transf.|Hora Transferência
TUZ|22|TUZ_POSCON|N|9|0|Contador 1|Contador 1
TUZ|23|TUZ_POSCO2|N|9|0|Contador 2|Contador 2
TUZ|24|TUZ_CODREL|C|6|0|Cód. Relac.|Transferência Relacionada
--- ### TV0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV0|01|TV0_FILIAL|C|6|0|Filial|Filial do Sistema
TV0|02|TV0_CODATI|C|3|0|Atividade|Atividade
TV0|03|TV0_NOME|C|40|0|Descricao|Descricao da Atividade
TV0|04|TV0_TIPHOR|C|1|0|Tipo de Hora|Tipo de Hora
TV0|05|TV0_BITMAP|C|8|0|Imagem|Imagem da Atividade
--- ### TV2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV2|01|TV2_FILIAL|C|6|0|Filial|Filial do Sistema
TV2|02|TV2_EMPRES|C|2|0|Empresa|Empresa
TV2|03|TV2_CODBEM|C|16|0|Equipamento|Equipamento
TV2|04|TV2_DTSERV|D|8|0|Data|Data Servico
TV2|05|TV2_TURNO|C|3|0|Turno|Turno
TV2|06|TV2_CODATI|C|3|0|Atividade|Atividade
TV2|07|TV2_NOMATI|C|20|0|Descrição|Descrição Atividade
TV2|08|TV2_HRINI|C|5|0|Hora Início|Hora Início Atividade
TV2|09|TV2_HRFIM|C|5|0|Hora Término|Hora Término da Atividade
TV2|10|TV2_CODFRE|C|9|0|Frente|Frente de Trabalho
TV2|11|TV2_NOMFRE|C|20|0|Nome Frente|Frente de Trabalho
TV2|12|TV2_TOTHOR|C|5|0|Total Horas|Total de Horas
TV2|13|TV2_PDIHRI|C|5|0|Hora Inicio|Hora Inicio Pt.Diaria
TV2|14|TV2_PDIHRF|C|5|0|Hora Termino|Hora Termino Pt.Diaria
TV2|15|TV2_CONTAD|N|9|0|Contador At.|Contador da Atividade
TV2|16|TV2_INTTSK|C|10|0|Tarefa TOP|Tarefa TOP
TV2|17|TV2_INDERR|C|1|0|Possui erro?|Registro com erro
TV2|18|TV2_MSGERR|M|10|0|Erro Import.|Erros de Importacao
TV2|19|TV2_WEBFLE|C|1|0|WebFleet?|Importado via WebFleet?
TV2|20|TV2_SEQREL|C|3|0|Sequência|Sequência
--- ### TVR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVR|01|TVR_FILIAL|C|6|0|Filial|Código da Filial
TVR|02|TVR_TAREFA|C|6|0|Tarefa|Código da Tarefa
TVR|03|TVR_GRUPO|C|6|0|Grupo|Código do Grupo
TVR|04|TVR_NOME|C|40|0|Nome|Nome do Grupo
--- ### TVS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVS|01|TVS_FILIAL|C|6|0|Filial|Código da Filial
TVS|02|TVS_TAREFA|C|6|0|Tarefa|Código da Tarefa
TVS|03|TVS_GRUPO|C|6|0|Grupo|Código do Grupo da Tarefa
TVS|04|TVS_ETAPA|C|6|0|Etapa|Código da Etapa do Grupo
--- ### TVT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVT|01|TVT_FILIAL|C|6|0|Filial|Código da Filial
TVT|02|TVT_ETAPA|C|8|0|Etapa|Código da Etapa
TVT|03|TVT_CODFAM|C|6|0|Família|Código da Família
TVT|04|TVT_NOMFAM|C|40|0|Nome Fam.|Nome da Familia
TVT|05|TVT_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo Modelo
TVT|06|TVT_NOMMOD|C|40|0|Nome Modelo|Nome do Tipo Modelo
TVT|07|TVT_ANO|C|4|0|Ano Modelo|Ano do Modelo
TVT|08|TVT_TEMPO|C|5|0|Tempo|Tempo Medio de Execucao
--- ### TZ1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ1|01|TZ1_FILIAL|C|6|0|Filial|Filial do Sistema
TZ1|02|TZ1_MODULO|C|2|0|Modulo|Modulo
TZ1|03|TZ1_CODCLA|C|3|0|Codigo Class|Codigo Classificacao
TZ1|04|TZ1_DESCRI|C|40|0|Descricao|Descricao Classificacao
--- ### TZ2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ2|01|TZ2_FILIAL|C|6|0|Filial|Filial do Sistema
TZ2|02|TZ2_MODULO|C|2|0|Modulo|Modulo
TZ2|03|TZ2_CODVAR|C|12|0|Variavel|Codigo da Variavel
TZ2|04|TZ2_TIPO|C|1|0|Tipo Funcao|Tipo Funcao
TZ2|05|TZ2_FUNCAO|C|30|0|Funcao|Funcao
TZ2|06|TZ2_TITULO|C|40|0|Titulo|Titulo
TZ2|07|TZ2_DESCRI|C|6|0|Cod. Descric|Cod. Descricao
TZ2|08|TZ2_MEMO1|M|80|0|Descricao|Descricao
--- ### TZ3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ3|01|TZ3_FILIAL|C|6|0|Filial|Filial do Sistema
TZ3|02|TZ3_MODULO|C|2|0|Modulo|Modulo
TZ3|03|TZ3_CODVAR|C|12|0|Cod. Variav.|Codigo da Variavel
TZ3|04|TZ3_ORDEM|C|3|0|Ordem|Ordem do Parametro
TZ3|05|TZ3_CODPAR|C|12|0|Cod. Paramet|Codigo Parametro
TZ3|06|TZ3_DESPAR|C|30|0|Desc. Param.|Descricao Parametro
TZ3|07|TZ3_VIRPAR|C|30|0|Parametro|Parametro
--- ### TZ4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ4|01|TZ4_FILIAL|C|6|0|Filial|Filial do Sistema
TZ4|02|TZ4_MODULO|C|2|0|Modulo|Modulo
TZ4|03|TZ4_CODPAR|C|12|0|Parametro|Codigo Parametro
TZ4|04|TZ4_DESCRI|C|40|0|Descricao|Descricao Parametro
TZ4|05|TZ4_TIPO|C|1|0|Tipo|Tipo Parametro
TZ4|06|TZ4_TAMANH|N|3|0|Tamanho|Tamanho
TZ4|07|TZ4_DECIMA|N|1|0|Decimal|Decimal
TZ4|08|TZ4_PICTUR|C|40|0|Formato|Formato
TZ4|09|TZ4_TABELA|C|3|0|Tabela|Tabela
TZ4|10|TZ4_CAMPOS|C|10|0|Campo|Campo
TZ4|11|TZ4_F3|C|6|0|Cons. Padrao|Consulta Padrao
TZ4|12|TZ4_OPCOES|C|200|0|Lista Opcoes|Lista Opcoes
TZ4|13|TZ4_RELACA|C|80|0|Inic. Padrao|Inicializador Padrao
TZ4|14|TZ4_VALID|C|200|0|Validacao|Validacao
--- ### TZ5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ5|01|TZ5_FILIAL|C|6|0|Filial|Filial do Sistema
TZ5|02|TZ5_MODULO|C|2|0|Modulo|Modulo
TZ5|03|TZ5_CODIND|C|12|0|Cod. Indica.|Codigo Indicador
TZ5|04|TZ5_NOME|C|40|0|Indicador|Indicador
TZ5|05|TZ5_FORMUL|C|254|0|Formula|Formula
TZ5|06|TZ5_CODCLA|C|3|0|Codigo Class|Codigo Classificacao
TZ5|07|TZ5_DESCLA|C|20|0|Desc. Class.|Descricao Classificacao
TZ5|08|TZ5_DESCRI|C|6|0|Cod. Descric|Cod. Descric
TZ5|09|TZ5_MEMO1|M|80|0|Descricao|Descricao
TZ5|10|TZ5_UNIMED|C|2|0|Unidade Med.|Unidade Medida
TZ5|11|TZ5_DESMED|C|40|0|Des. Unidade|Des. Unidade
TZ5|12|TZ5_TAMMED|N|2|0|Tamanho|Tamanho
TZ5|13|TZ5_DECMED|N|2|0|Decimal|Decimal
TZ5|14|TZ5_TIPRES|C|1|0|Tipo Result.|Tipo Resultado
TZ5|15|TZ5_VALOR1|C|40|0|Primeiro Val|Primeiro Valor
TZ5|16|TZ5_VALOR2|C|40|0|Segundo Val.|Segundo Valor
TZ5|17|TZ5_TIPVAL|C|1|0|Tipo Valor|Tipo Valor
TZ5|18|TZ5_FORCON|C|246|0|Cont. Formul|Continuacao da Formula
TZ5|19|TZ5_ATIVO|C|1|0|Ativo?|Indicador Ativo?
--- ### TZ6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ6|01|TZ6_FILIAL|C|6|0|Filial|Filial do Sistema
TZ6|02|TZ6_MODULO|C|2|0|Modulo|Modulo
TZ6|03|TZ6_CODIND|C|12|0|Cod. Indica.|Codigo Indicador
TZ6|04|TZ6_DESIND|C|30|0|Des. Indica.|Descricao Indicador
TZ6|05|TZ6_CODVAR|C|12|0|Cod. Variav.|Codigo Variavel
TZ6|06|TZ6_DESVAR|C|30|0|Des. Variav.|Descricao Variavel
--- ### TZ7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ7|01|TZ7_FILIAL|C|6|0|Filial|Filial do Sistema
TZ7|02|TZ7_MODULO|C|2|0|Modulo|Modulo
TZ7|03|TZ7_CODIND|C|12|0|Cod. Indica.|Codigo Indicador
TZ7|04|TZ7_DESIND|C|30|0|Des. Indica.|Descricao Indicador
TZ7|05|TZ7_TIPO|C|1|0|Tipo|Tipo
TZ7|06|TZ7_CODPAR|C|12|0|Parametro|Parametro
TZ7|07|TZ7_DESPAR|C|30|0|Desc. Param.|Descricao Parametro
TZ7|08|TZ7_CONTEU|C|200|0|Conteudo|Conteudo
--- ### TZ8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ8|01|TZ8_FILIAL|C|6|0|Filial|Filial do Sistema
TZ8|02|TZ8_MODULO|C|2|0|Modulo|Modulo
TZ8|03|TZ8_USER|C|15|0|Usuário|Usuário do Sistema
TZ8|04|TZ8_IND|C|12|0|Indicador|Indicador
TZ8|05|TZ8_CODPAR|C|12|0|Parâmetro|Parâmetro
TZ8|06|TZ8_VALOR|C|25|0|Valor|Valor
--- ### TZ9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZ9|01|TZ9_FILIAL|C|6|0|Filial|Filial do Sistema
TZ9|02|TZ9_CODIGO|C|3|0|Código|Código Indicador Gráfico
TZ9|03|TZ9_TITULO|C|25|0|Título|Título do Indicador
TZ9|04|TZ9_SUBTIT|C|10|0|Subtítulo|Subtítulo do Indicador
TZ9|05|TZ9_DESCRI|M|10|0|Descrição|Descrição do Indicador
TZ9|06|TZ9_CODDES|C|6|0|Código Desc.|Código da Descrição SYP
TZ9|07|TZ9_PROPRI|C|1|0|Proprietário|Proprietário do Indicador
TZ9|08|TZ9_DTCAD|D|8|0|Dt. Cad.|Data do Cadastro
TZ9|09|TZ9_HRCAD|C|5|0|Hr. Cad.|Hora do Cadastro
TZ9|10|TZ9_USCAD|C|6|0|Usuário|Usuário do Cadastro
TZ9|11|TZ9_NOCAD|C|40|0|Nome Usuário|Nome do Usuário do Cad.
TZ9|12|TZ9_ATIVO|C|1|0|Ativo?|Indicador Ativo?
TZ9|13|TZ9_MODULO|C|2|0|Módulo|Módulo do Indicador
TZ9|14|TZ9_NOMMOD|C|40|0|Nome Módulo|Nome do Módulo do Painel
TZ9|15|TZ9_MODELO|C|1|0|Modelo|Modelo do Indicador
TZ9|16|TZ9_TIPCON|C|1|0|Conteúdo|Tipo de Conteúdo
TZ9|17|TZ9_VAL01|N|15|2|Valor 01|Valor 01
TZ9|18|TZ9_VAL02|N|15|2|Valor 02|Valor 02
TZ9|19|TZ9_VAL03|N|15|2|Valor 03|Valor 03
TZ9|20|TZ9_VAL04|N|15|2|Valor 04|Valor 04
TZ9|21|TZ9_VAL05|N|15|2|Valor 05|Valor 05
TZ9|22|TZ9_VAL06|N|15|2|Valor 06|Valor 06
TZ9|23|TZ9_VAL07|N|15|2|Valor 07|Valor 07
TZ9|24|TZ9_SECMIN|N|15|2|Sec. Min.|Porcentagem Secao Minima
TZ9|25|TZ9_SECMAX|N|15|2|Sec. Max.|Porcentagem Secao Maxima
TZ9|26|TZ9_LEGMIN|C|60|0|Leg. Min.|Legenda Secao Minima
TZ9|27|TZ9_LEGMED|C|60|0|Leg. Inter.|Legenda Secao Intermed.
TZ9|28|TZ9_LEGMAX|C|60|0|Leg. Max.|Legenda Secao Maxima
TZ9|29|TZ9_SOMB01|C|1|0|Somb. Centr.|Sombreamento Central
TZ9|30|TZ9_SOMB02|C|1|0|Somb. Inf.|Sombreamento Inferior
TZ9|31|TZ9_SOMB03|C|1|0|Somb. Aux.|Sombreamento Auxiliar
TZ9|32|TZ9_COR01|C|7|0|Cor 01|Cor 01
TZ9|33|TZ9_COR02|C|7|0|Cor 02|Cor 02
TZ9|34|TZ9_COR03|C|7|0|Cor 03|Cor 03
TZ9|35|TZ9_COR04|C|7|0|Cor 04|Cor 04
TZ9|36|TZ9_COR05|C|7|0|Cor 05|Cor 05
TZ9|37|TZ9_COR06|C|7|0|Cor 06|Cor 06
TZ9|38|TZ9_COR07|C|7|0|Cor 07|Cor 07
TZ9|39|TZ9_COR08|C|7|0|Cor 08|Cor 08
TZ9|40|TZ9_COR09|C|7|0|Cor 09|Cor 09
TZ9|41|TZ9_COR10|C|7|0|Cor 10|Cor 10
TZ9|42|TZ9_COR11|C|7|0|Cor 11|Cor 11
TZ9|43|TZ9_COR12|C|7|0|Cor 12|Cor 12
TZ9|44|TZ9_COR13|C|7|0|Cor 13|Cor 13
TZ9|45|TZ9_COR14|C|7|0|Cor 14|Cor 14
--- ### TZA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZA|01|TZA_FILIAL|C|6|0|Filial|Filial do Sistema
TZA|02|TZA_CODGRA|C|3|0|Cód. Gráf.|Código Indicador Gráfico
TZA|03|TZA_CODIND|C|12|0|Cód. Fórm.|Código da Fórmula
TZA|04|TZA_NOMIND|C|40|0|Nome Fórm.|Nome da Fórmula
--- ### TZB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZB|01|TZB_FILIAL|C|6|0|Filial|Filial do Sistema
TZB|02|TZB_CODIGO|C|6|0|Código|Código do Painel
TZB|03|TZB_NOME|C|40|0|Nome Painel|Nome do Painel
TZB|04|TZB_CODUSU|C|6|0|Usuário|Usuário do Sistema
TZB|05|TZB_NOMUSU|C|40|0|Nome Usuário|Nome do Usuário
TZB|06|TZB_MODULO|C|2|0|Módulo|Módulo do Painel
TZB|07|TZB_NOMMOD|C|8|0|Nome Módulo|Nome do Módulo do Painel
TZB|08|TZB_ATIVO|C|1|0|Ativo?|Painel Ativo?
--- ### TZC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZC|01|TZC_FILIAL|C|6|0|Filial|Filial do Sistema
TZC|02|TZC_CODPNL|C|6|0|Código|Código do Painel
TZC|03|TZC_CODIND|C|12|0|Cód. Fórm.|Código da Fórmula
--- ### TZD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZD|01|TZD_FILIAL|C|6|0|Filial|Filial do Sistema
TZD|02|TZD_CODUSR|C|6|0|Usuario|Usuario do Sistema
TZD|03|TZD_CODPNL|C|6|0|Código|Código do Painel
TZD|04|TZD_FUNPAI|C|15|0|Função Pai|Código da Função Pai
TZD|05|TZD_CFGTIP|C|15|0|Tipo Config.|Tipo de Configuração
TZD|06|TZD_CFGAX1|C|15|0|Auxiliar 01|Auxiliar 01 de Config.
TZD|07|TZD_CFGDAT|C|1|0|Tipo de Dado|Tipo de Dado da Resposta
TZD|08|TZD_CFGRES|C|100|0|Resposta|Resposta da Configuração
--- ### TZE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZE|01|TZE_FILIAL|C|6|0|Filial|Filial do Sistema
TZE|02|TZE_CODIGO|C|15|0|Codigo|Codigo ID do Historico
TZE|03|TZE_MODULO|C|2|0|Modulo|Modulo do Sistema
TZE|04|TZE_NOMMOD|C|40|0|Nome Módulo|Nome do Módulo
TZE|05|TZE_INDIC|C|12|0|Indicador|Indicador (Fórmula)
TZE|06|TZE_NOMFOR|C|40|0|Nome|Nome do Indicador
TZE|07|TZE_FORMUL|C|254|0|Fórmula|Fórmula
TZE|08|TZE_DATA|D|8|0|Data|Data do Histórico
TZE|09|TZE_HORA|C|5|0|Hora|Hora do Histórico
TZE|10|TZE_TIPMET|C|1|0|Tipo Meta|Tipo de Meta
TZE|11|TZE_META|N|16|3|Meta|Meta do Indicador
TZE|12|TZE_META2|N|16|3|Meta 2|Meta 2 do Indicador
TZE|13|TZE_TIPVAL|C|1|0|Tipo Valor|Tipo de Valor
TZE|14|TZE_RESULT|N|16|3|Resultado|Resultado do Indicador
TZE|15|TZE_FUNPAI|C|15|0|Função Pai|Código da Função Pai
TZE|16|TZE_CODUSR|C|6|0|Usuário|Usuário do Sistema
TZE|17|TZE_NOMUSR|C|40|0|Nome Usuário|Nome do Usuário
--- ### TZF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZF|01|TZF_FILIAL|C|6|0|Filial|Filial do Sistema
TZF|02|TZF_CODIGO|C|15|0|Código|Código ID do Histórico
TZF|03|TZF_VARIAV|C|12|0|Variável|Variável (Função)
TZF|04|TZF_SEQUEN|C|5|0|Sequência|Sequência do Histórico
TZF|05|TZF_TABELA|C|3|0|Tabela|Tabela do Processo
TZF|06|TZF_CAMPO|C|10|0|Campo|Campo do Processo
TZF|07|TZF_ORDEM|C|2|0|Ordem Campo|Ordem do Campo
TZF|08|TZF_TIPDAD|C|1|0|Tipo de Dado|Tipo de Dado do Campo
TZF|09|TZF_CONTEU|C|100|0|Conteúdo|Conteúdo do Campo
TZF|10|TZF_AUXTIT|C|30|0|Título|Título do Campo
TZF|11|TZF_AUXTAM|N|3|0|Tamanho|Tamanho do Campo
TZF|12|TZF_AUXDEC|N|3|0|Decimal|Decimal do Campo
TZF|13|TZF_AUXPIC|C|20|0|Picture|Picture do Campo
TZF|14|TZF_AUXOPC|C|200|0|Opções|Opções do Campo
--- ### TZG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZG|01|TZG_FILIAL|C|6|0|Filial|Filial do Sistema
TZG|02|TZG_CODIGO|C|15|0|Código|Código ID do Histórico
TZG|03|TZG_VARIAV|C|12|0|Variável|Variável (Função)
TZG|04|TZG_ORDEM|C|3|0|Ordem|Ordem do Parâmetro
TZG|05|TZG_PARAM|C|12|0|Parâmetro|Parâmetro do Processo
TZG|06|TZG_TIPDAD|C|1|0|Tipo de Dado|Tipo de Dado do Campo
TZG|07|TZG_CONTEU|C|100|0|Conteúdo|Conteúdo do Campo
TZG|08|TZG_AUXTIT|C|30|0|Título|Título do Campo
TZG|09|TZG_AUXTAM|N|3|0|Tamanho|Tamanho do Campo
TZG|10|TZG_AUXDEC|N|3|0|Decimal|Decimal do Campo
TZG|11|TZG_AUXPIC|C|20|0|Picture|Picture do Campo
TZG|12|TZG_AUXOPC|C|200|0|Opções|Opções do Campo
--- ### TZH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZH|01|TZH_FILIAL|C|6|0|Filial|Filial do Sistema
TZH|02|TZH_CODPNL|C|6|0|Código|Código do Painel
TZH|03|TZH_TIPO|C|1|0|Tipo|Tipo de Permissão
TZH|04|TZH_USRGRP|C|30|0|Código|Código do Usuário/Grupo
TZH|05|TZH_NOME|C|40|0|Nome|Nome do Usuário/Grupo
--- ### TZI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZI|01|TZI_FILIAL|C|6|0|Filial|Filial do Sistema
TZI|02|TZI_CODIGO|C|15|0|Código|Código ID do Histórico
TZI|03|TZI_VARIAV|C|12|0|Variável|Variável (Função)
TZI|04|TZI_VARNOM|C|40|0|Nome Var.|Nome da Variável
TZI|05|TZI_RESULT|N|16|3|Resultado|Resultado do Indicador
--- ### TZZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TZZ|01|TZZ_FILIAL|C|6|0|Filial|Filial do Sistema
TZZ|02|TZZ_PRODUT|C|15|0|Produto|Código do Lubrificante
TZZ|03|TZZ_DESCRI|C|30|0|Descrição|Descrição do Lubrificante
TZZ|04|TZZ_FORNEC|C|6|0|Fornecedor|Fornecedor do Lubrif.
TZZ|05|TZZ_TIPLUB|C|1|0|Tipo Lubrif.|Tipo de Lubrificante
TZZ|06|TZZ_METAPL|C|1|0|Método Apl.|Método de Aplicação
TZZ|07|TZZ_TOXICO|C|1|0|Toxidade|Toxidade do Lubrificante
TZZ|08|TZZ_VISCO|C|10|0|Viscosidade|Viscosidade do Lubrif.
TZZ|09|TZZ_INDVIS|C|10|0|Índice Visc.|Índice de Viscosidade
TZZ|10|TZZ_DENSID|C|10|0|Densidade|Densidade do Lubrificante
TZZ|11|TZZ_FULGOR|C|10|0|Pto. Fulgor|Ponto de Fulgor
TZZ|12|TZZ_COMBUS|C|10|0|Pto. Combus.|Ponto de Combustão
TZZ|13|TZZ_FLUIDE|C|10|0|Pto. Fluidez|Ponto de Fluidez
TZZ|14|TZZ_RESIDU|C|10|0|Resíduos|Resíduos do Lubrificante
TZZ|15|TZZ_CONSIS|C|10|0|Consistência|Consistência do Lubrif.
TZZ|16|TZZ_ESTRUT|C|40|0|Estrutura|Característica do Lubrif.
TZZ|17|TZZ_FILAME|C|40|0|Filamentação|Filamentação do Lubrif.
TZZ|18|TZZ_ADEREN|C|10|0|Densidade|Densidade do Lubrificante
TZZ|19|TZZ_GOTEJA|C|10|0|Pto. Gotej.|Ponto de Gotejamento
TZZ|20|TZZ_OBSERV|M|10|0|Observação|Observação
TZZ|21|TZZ_BITMAP|C|20|0|Imagem Prod.|Imagem do Produto
--- ### T40
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T40|01|T40_FILIAL|C|6|0|Filial|Filial
T40|02|T40_VALCON|C|16|0|Control.Marc|Controle de matcação
T40|03|T40_CODREL|C|100|0|Cod. Relogio|Código do relogio
T40|04|T40_CODFUN|C|100|0|Cod.Func|Código do Funcionario
T40|05|T40_LOGIP|C|1|0|Log.Importaç|Log de Importação
T40|06|T40_CODNSR|N|9|0|Cod. NSR|Código NSR
T40|07|T40_CODPIS|C|12|0|Cod.PIS|Código do PIS
T40|08|T40_DATMAR|D|8|0|Data.Marcaça|Data da marcação
T40|09|T40_NUMMAR|N|6|0|Hora Realiza|Hora Realizada
T40|10|T40_CODREP|C|17|0|Cod.REP|Código do REP
T40|11|T40_CODUNI|C|100|0|Cod. Unid.|Código da Unidade
T40|12|T40_CODUSU|C|100|0|Cod. Usuario|Código do usuário
T40|13|T40_LONGIT|C|30|0|Longitude|Longitude
T40|14|T40_LATITU|C|30|0|Latitude|Latitude
T40|15|T40_GEOFEN|C|1|0|Status Perim|Status Perimetro
T40|16|T40_AGEINT|C|1|0|Agenda Integ|Agenda integrada?
T40|17|T40_TIPOMA|C|15|0|Tipo Marcaçã|Tipo Marcação
T40|18|T40_HPREVI|C|15|0|Hora Previst|Hora Prevista
T40|19|T40_CIC|C|11|0|CPF|CPF
--- ### T45
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T45|01|T45_FILIAL|C|6|0|Filial|Filial do sistema
T45|02|T45_CODIGO|C|6|0|Cód.reg.cxa.|Cód.do regime de caixa
T45|03|T45_CONTRT|C|15|0|Nr. contrato|Número do contrato
T45|04|T45_DTINI|D|8|0|Data inicial|Dt.inicio vigência rg.cxa
T45|05|T45_DTFIM|D|8|0|Data final|Dt.final vigência rg.cxa
T45|06|T45_STATUS|C|1|0|Status|Status do regime de caixa
--- ### T46
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T46|01|T46_FILIAL|C|6|0|Filial|Filial do sistema
T46|02|T46_CODIGO|C|6|0|Cód.reg.cxa.|Cód.do regime de caixa
T46|03|T46_ITEM|C|3|0|Item|Item
T46|04|T46_CODTEC|C|14|0|Atendente|Código do atendente
T46|05|T46_NOME|C|50|0|Nome atend.|Nome do atendente
T46|06|T46_LOCAL|C|8|0|Local|Local de atendimento
T46|07|T46_DSCLOC|C|50|0|Descr. local|Descrição local atendim.
T46|08|T46_CODTFF|C|6|0|Cód.Rec.Hum.|Cód.do recurso humano
T46|09|T46_NUMPED|C|6|0|Núm.pedido|Número do pedido de venda
--- ### T47
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T47|01|T47_FILIAL|C|6|0|Filial|Filial do sistema
T47|02|T47_CODIGO|C|6|0|Cód.reg.cxa.|Cód.do regime de caixa
T47|03|T47_CODTEC|C|14|0|Cód. atend.|Código do atendente
T47|04|T47_ITEM|C|3|0|Item|Item
T47|05|T47_SBITEM|C|2|0|Item|Subitem
T47|06|T47_DSCCAL|C|50|0|Desc. calc.|Descrição do cálculo
T47|07|T47_TABELA|C|6|0|Tb.precific.|Cód. tabela precificação
T47|08|T47_REVISA|C|3|0|Rv.tb.precif|Revisão tab. precificação
T47|09|T47_XML|M|10|0|Cálc período|Cálculo do período
T47|10|T47_VALOR|N|14|2|Vl.calculado|Valor calculado
--- ### T48
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T48|01|T48_FILIAL|C|6|0|Filial|Filial
T48|02|T48_CODABB|C|12|0|Cod. Agenda|Código da agenda
T48|03|T48_ITEM|C|3|0|Item|Item
T48|04|T48_TIPO|C|1|0|Tipo da foto|Tipo da foto
T48|05|T48_FOTO|M|10|0|Foto|Foto
--- ### T49
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T49|01|T49_FILIAL|C|6|0|Filial|Filial do Sistema
T49|02|T49_CODIGO|C|6|0|Código|Código
T49|03|T49_LOCINT|C|8|0|Local int|Local interno
T49|04|T49_CODFOR|C|6|0|Cod. Fornec.|Cod. Fornecedor
T49|05|T49_LOJA|C|2|0|Loja|Loja Fornecedor
T49|06|T49_NOME|C|80|0|Razao Social|Razao Social
T49|07|T49_CNPJ|C|14|0|CNPJ|CNPJ Fornecedor
T49|08|T49_DOC|C|9|0|Num. Nota|Numero da Nota
T49|09|T49_SERIE|C|3|0|Serie Nota|Serie da Nota
T49|10|T49_ITEM|C|4|0|Item|Item da Nota
T49|11|T49_CODPRO|C|15|0|Cod. Produto|Codigo Produto
T49|12|T49_QTDEMU|N|5|0|Qtd. Municao|Qtd. Municoes
T49|13|T49_DTNOTA|D|8|0|Data Nota|Data da Nota
T49|14|T49_COMPRA|D|8|0|Dta Compra|Data de Compra
T49|15|T49_ORIGEM|C|8|0|Origem|Origem
T49|16|T49_CODMUN|C|6|0|Codigo|Codigo da Municao
T49|17|T49_FILLOC|C|6|0|Filial Local|Filial Local
--- ### T4B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T4B|01|T4B_FILIAL|C|6|0|Filial|Filial
T4B|02|T4B_TAB|C|3|0|Tabela|Tabela
T4B|03|T4B_RECNO|N|8|0|Recno|Recno
T4B|04|T4B_CAMPO|C|20|0|Campo|Campo
T4B|05|T4B_VALOR|C|200|0|Valor|Valor
T4B|06|T4B_MEMO|M|10|0|Memo|Memo
--- ### TCT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCT|01|TCT_FILIAL|C|6|0|Filial|Filial do Sistema
TCT|02|TCT_GRUPO|C|3|0|Grupo/Perfil|Grupo/Perfil
TCT|03|TCT_ITEM|C|3|0|Item|Item do acesso
TCT|04|TCT_ACESSO|C|100|0|Item|Item do Acesso
TCT|05|TCT_PODE|C|1|0|Permite?|Permissão
--- ### TCU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCU|01|TCU_FILIAL|C|6|0|Filial|Filial do Sistema
TCU|02|TCU_COD|C|3|0|Codigo|Codigo do Tipo
TCU|03|TCU_EXALOC|C|1|0|Exibe Aloc?|Exibe na alocação?
TCU|04|TCU_EXMANU|C|1|0|Exibe Manut?|Exibe na manutenção?
TCU|05|TCU_RESTEC|C|1|0|Res. Tecnica|Reserva Tecnica
TCU|06|TCU_DESC|C|15|0|Descrição|Descrição tp.movimentação
TCU|07|TCU_RESFTR|C|1|0|Ag Res Futur|Agenda de Reserva Futura
TCU|08|TCU_ALOCEF|C|1|0|Aloc.Efetivo|Alocação de Efetivo?
TCU|09|TCU_LIBERA|C|1|0|Aloc. Libera|Alocação Liberada?
TCU|10|TCU_TIPOMV|C|1|0|Tipo Movimen|Tipo de Movimentação
--- ### TCV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCV|01|TCV_FILIAL|C|6|0|Filial|Filial do Sistema
TCV|02|TCV_NUMAPU|C|6|0|Cod. Apurac.|Código Apuração
TCV|03|TCV_NUMPED|C|6|0|Numero|Numero do Pedido
TCV|04|TCV_ALIAS|C|3|0|Cod. Tabela|Codigo da Tabela
TCV|05|TCV_CODITE|C|6|0|Cod. Item|Codigo do Item
TCV|06|TCV_ITEMPV|C|2|0|Item PV|Item do Pedido de Venda
TCV|07|TCV_PRODPV|C|15|0|Produto. PV.|Produto Pedido de Venda
--- ### TCW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCW|01|TCW_FILIAL|C|6|0|Filial      |Filial do Sistema
TCW|02|TCW_CODIGO|C|6|0|Codigo      |Codigo da tabela
TCW|03|TCW_DESCRI|C|30|0|Descricao   |Descricao
TCW|04|TCW_CODCCT|C|8|0|Codigo CCT  |Codigo CCT
TCW|05|TCW_DSCCCT|C|30|0|Desc. CCT   |Desc. CCT
TCW|06|TCW_NCKCUS|C|25|0|Nom Cel Cust|Nome Celula Custo
TCW|07|TCW_CUSTO|C|99|0|Formula Cust|Formula do Custo
TCW|08|TCW_NICKLI|C|25|0|Nome Cel Liq|Nome Celula Liquido
TCW|09|TCW_FORLIQ|C|99|0|Formula Liq|Formula do Tot. Liquido
TCW|10|TCW_NICKBR|C|25|0|Nome Cel Brt|Nome Celula Bruto
TCW|11|TCW_FORBRT|C|99|0|Formula Brut|Formula do Total Bruto
TCW|12|TCW_REVISA|C|4|0|Revisão|Controle de Revisão
TCW|13|TCW_ULTIMA|C|1|0|Ult. Revisão|Ultima Revisão
TCW|14|TCW_USRREV|C|6|0|Usuário Rev.|Usuário da Revisão
TCW|15|TCW_DTHREV|C|16|0|Dt. Hr. Rev.|Data e Hora da Revisão
--- ### TCX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCX|01|TCX_FILIAL|C|6|0|Filial|Filial do Sistema
TCX|02|TCX_CODIGO|C|6|0|Codigo|Codigo da Tabela
TCX|03|TCX_TIPOPE|C|1|0|Tipo Item|Tipo do Item
TCX|04|TCX_CODTCW|C|6|0|Cod. Config|Codigo da Configuracao
TCX|05|TCX_ITEM|C|3|0|Item|Item da tabela
TCX|06|TCX_DESCRI|C|50|0|Descrição|Descrição da tabela
TCX|07|TCX_TIPTBL|C|1|0|Tipo|Tipo
TCX|08|TCX_TABELA|C|1|0|Tabela|Tabela
TCX|09|TCX_CODTBL|C|6|0|Cod. Tabela|Codigo da Tabela
TCX|10|TCX_PORCEN|N|14|2|Porcentagem|Porcentagem
TCX|11|TCX_OBRGT|C|1|0|Obrigatório?|Preenche na planilha ?
TCX|12|TCX_PORALT|N|14|2|Porcent Alt.|Porcentagem Alterada
TCX|13|TCX_NICKPO|C|25|0|Nome Porcent|Nome Celula Porcentagem
TCX|14|TCX_NICK|C|25|0|Nome Celula|Nome da Celula da Planilh
TCX|15|TCX_FORMUL|C|99|0|Formula Vlr.|Formula Celula Valor
TCX|16|TCX_REVISA|C|4|0|Revisão|Controle de Revisão
--- ### TCZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCZ|01|TCZ_FILIAL|C|6|0|FILIAL|FILIAL
TCZ|02|TCZ_COD|C|6|0|Código|Código
TCZ|03|TCZ_DESC|C|60|0|Descrição|Descrição
--- ### TDS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDS|01|TDS_FILIAL|C|6|0|FILIAL|FILIAL
TDS|02|TDS_COD|C|6|0|Código|Código
TDS|03|TDS_CODTFF|C|6|0|Código RH|Código Recursos Humanos
TDS|04|TDS_CODTCZ|C|6|0|Caract.|Característica
TDS|05|TDS_DSCTCZ|C|60|0|Desc. Carac|Desc. da característica
--- ### TDT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDT|01|TDT_FILIAL|C|6|0|FILIAL|FILIAL
TDT|02|TDT_COD|C|6|0|Código|Código
TDT|03|TDT_CODTFF|C|6|0|Código RH|Código Recursos Humanos
TDT|04|TDT_CODHAB|C|6|0|Habilidade|Habilidade
TDT|05|TDT_DSCHAB|C|60|0|Desc. Hab|Descrição da Habilidade
TDT|06|TDT_ESCALA|C|2|0|Cód. Escala|Codigo da Escala
TDT|07|TDT_DSCESC|C|60|0|Des. Escala|Descrição da Escala
TDT|08|TDT_ITESCA|C|2|0|Item Escala|Item Da Escala
TDT|09|TDT_DSCITE|C|60|0|D. Item Esc.|Desc. Item da escala
TDT|10|TDT_HABX5|C|6|0|Habilidade|Código da Habilidade
TDT|11|TDT_DHABX5|C|60|0|Desc. Hab.|Descrição da Habilidade
--- ### TDU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDU|01|TDU_FILIAL|C|6|0|Filial|Filial
TDU|02|TDU_COD|C|6|0|Código|Código
TDU|03|TDU_CODTEC|C|14|0|Atendente|Código Atendente
TDU|04|TDU_CODTCZ|C|6|0|Cod. Caract.|Código da Característica
TDU|05|TDU_DESTCZ|C|60|0|Característi|Desc. Característica
--- ### TDV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDV|01|TDV_FILIAL|C|6|0|Filial|Filial do Sistema
TDV|02|TDV_CODABB|C|12|0|Cod. Agenda|Codigo da Agenda
TDV|03|TDV_DTREF|D|8|0|Data Ref.|Data de Referencia
TDV|04|TDV_TURNO|C|3|0|Turno|Turno
TDV|05|TDV_SEQTRN|C|2|0|Seq. Turno|Sequencia de Turno
TDV|06|TDV_TPEXT|C|1|0|Tp.He Normal|Tipo de Hora Extra Normal
TDV|07|TDV_TPEXTN|C|1|0|Tp.He Not.|Tipo de Hora Ext Noturna
TDV|08|TDV_NONHOR|C|1|0|Nona Hora|Apura Nona Hora
TDV|09|TDV_CODREF|C|2|0|Cod.Refeicao|Codigo da Refeicao
TDV|10|TDV_INSREP|C|2|0|Interv.SREP|Intervalo para ACJEF
TDV|11|TDV_TPDIA|C|1|0|Tipo Dia|Tipo Dia
TDV|12|TDV_HRMEN|N|5|2|Limite Infer|Limite Minimo da Tabela
TDV|13|TDV_HRMAI|N|5|2|Limite Super|Limite Maximo da Tabela
TDV|14|TDV_INTVL1|C|1|0|1a.S.Interv|1a Saida e Intervalo
TDV|15|TDV_INTVL2|C|1|0|2a.S.Interv|2a Saida e Intervalo
TDV|16|TDV_INTVL3|C|1|0|3a.S.Interv.|3a Saida e Intervalo
TDV|17|TDV_FERIAD|C|30|0|Feriado|Feriado
TDV|18|TDV_FTPEXT|C|1|0|Tp.He Nor. F|Tipo de Hora Ext Nor Fer.
TDV|19|TDV_FEXTN|C|1|0|Tp.He Not.|Tipo de Hr Ext N. Fer
TDV|20|TDV_CODFER|C|6|0|Feriado|Feriado
TDV|21|TDV_GRUPO|N|3|0|Grupo|Grupo da escala
TDV|22|TDV_FERSAI|C|30|0|Feriado Said|Feriado Saida
TDV|23|TDV_FSTPEX|C|1|0|Tp.He Nor.|Tp Hora Ext Nor Fer. Sai.
TDV|24|TDV_FSEXTN|C|1|0|Tp.He Not.|Tp Hr Ext N. Fer Sai.
--- ### TDW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDW|01|TDW_FILIAL|C|6|0|Filial|Filal do Sistema
TDW|02|TDW_COD|C|6|0|Código|Código
TDW|03|TDW_DESC|C|60|0|Escala|Escala
TDW|04|TDW_STATUS|C|1|0|Status|Status
TDW|05|TDW_STACFG|C|1|0|Status Conf.|Status da Configuração
TDW|06|TDW_INTRA|C|1|0|Intrajornada|Intrajornada
TDW|07|TDW_CODHOR|C|4|0|Codigo RM|Codigo da escala RM
TDW|08|TDW_RPLFER|C|1|0|Réplica Fer.|Réplica de Feriados
TDW|09|TDW_TRBSDF|C|1|0|SDF|Sábados Domingos Feriados
TDW|10|TDW_QTDALO|N|2|0|Qtde. Alocaç|Quantidade de Alocações
TDW|11|TDW_ADCNOT|C|1|0|Calc.Ad.Not.|Calcula Adicional Noturno
TDW|12|TDW_PERIOD|C|1|0|Período|Período de Supervisão
--- ### TDX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDX|01|TDX_FILIAL|C|6|0|Filial|Filial
TDX|02|TDX_COD|C|6|0|Código|Código
TDX|03|TDX_CODTDW|C|6|0|Escala|Escala
TDX|04|TDX_TURNO|C|3|0|Turno|Turno
TDX|05|TDX_DESTUR|C|50|0|Desc. Turno|Descrição do Turno
TDX|06|TDX_SEQTUR|C|2|0|Seq. Turno|Sequencia do turno
TDX|07|TDX_QUANT|N|3|0|Quantidade|Quantidade
TDX|08|TDX_TIPO|C|1|0|Tipo|Tipo do recurso
TDX|09|TDX_STATUS|C|1|0|Status|Status
TDX|10|TDX_INIHOR|C|1|0|Indice RM|Indice RM
--- ### TDY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDY|01|TDY_FILIAL|C|6|0|Filial|Filial do Sistema
TDY|02|TDY_COD|C|6|0|Código|Código
TDY|03|TDY_DIASEM|C|1|0|Dia da Sem.|Dia da Semana
TDY|04|TDY_ENTRA1|N|5|2|1ª Entrada|1ª Entrada
TDY|05|TDY_SAIDA1|N|5|2|1ª Saida|1ª Saida
TDY|06|TDY_ENTRA2|N|5|2|2ª Entrada|2ª Entrada
TDY|07|TDY_SAIDA2|N|5|2|2ª Saida|2ª Saida
TDY|08|TDY_ENTRA3|N|5|2|3ª Entrada|3ª Entrada
TDY|09|TDY_SAIDA3|N|5|2|3ª Saida|3ª Saida
TDY|10|TDY_ENTRA4|N|5|2|4ª Entrada|4ª Entrada
TDY|11|TDY_SAIDA4|N|5|2|4ª Saida|4ª Saida
TDY|12|TDY_HREXT|C|1|0|Hora Extra|Hora Extra
TDY|13|TDY_CODTDX|C|6|0|Cod.Conf.Esc|Codigo Conf. Escala
TDY|14|TDY_FERIAD|C|1|0|Feriado|Feriado
TDY|15|TDY_TROSEQ|C|1|0|Troca Seq.|Troca Seq.
TDY|16|TDY_HORMEN|N|5|2|Limite.Inf|Limite.Inferior
TDY|17|TDY_HORMAI|N|5|2|Limite Sup.|Limite Superior
TDY|18|TDY_TRBFOL|C|1|0|Trb. Folga?|Trabalha na Folga?
TDY|19|TDY_APLMAN|C|1|0|Aplica Man.?|Aplica Manutenção Plan.?
--- ### TDZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDZ|01|TDZ_FILIAL|C|6|0|Filial|Filial do Sistema
TDZ|02|TDZ_CODIGO|C|6|0|Codigo|Codigo
TDZ|03|TDZ_CODTCW|C|6|0|Cod. Benefic|Codigo do Beneficios
TDZ|04|TDZ_ITEM|C|3|0|Item|Item
TDZ|05|TDZ_TABELA|C|1|0|Tabela|Tabela
TDZ|06|TDZ_TIPBEN|C|2|0|Tip. Benefic|Tipo de Beneficio
TDZ|07|TDZ_DESCRI|C|50|0|Beneficio|Descrição do Beneficio
TDZ|08|TDZ_CODSLY|C|8|0|Cod. Benefic|Codigo do Beneficios
TDZ|09|TDZ_DSCBEN|C|30|0|Descrição|Descrição do Beneficio
TDZ|10|TDZ_VALOR|N|12|2|Vlr. Dia CCT|Valor dia da CCT
TDZ|11|TDZ_VLRDIF|N|14|2|Vlr Dia Dif|Valor diario diferenciado
TDZ|12|TDZ_NICKVL|C|25|0|Nome Cel Vlr|Nome da Celula de Valor
TDZ|13|TDZ_NICK|C|25|0|Nome Celula|Nome Celula
TDZ|14|TDZ_FORMUL|C|99|0|Formula Plan|Formula Planilha de Calc.
TDZ|15|TDZ_REVISA|C|4|0|Revisão|Controle de Revisão
TDZ|16|TDZ_OBRGT|C|1|0|Obrigatório?|Preenche na planilha ?
TDZ|17|TDZ_ALTERA|C|1|0|Alterável|Campo pode ser alterado?
--- ### TE0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE0|01|TE0_FILIAL|C|6|0|Filial|Filial do Sistema
TE0|02|TE0_COD|C|6|0|Codigo|Codigo da Arma
TE0|03|TE0_DOC|C|9|0|Num. Nota|Numero da Nota
TE0|04|TE0_SERIE|C|3|0|Serie|Serie da Nota Fiscal
TE0|05|TE0_DTNOTA|D|8|0|Data da Nota|Data da Nota Fiscal
TE0|06|TE0_COMPRA|D|8|0|Dt Compra|Data da Compra
TE0|07|TE0_CODFOR|C|6|0|Cod. Fornec.|Codigo do Fornecedor
TE0|08|TE0_LOJA|C|2|0|Loja|Loja do Fornecedor
TE0|09|TE0_NOME|C|80|0|Razão Social|Razão Social Fornecedor
TE0|10|TE0_CNPJ|C|14|0|CNPJ|CNPJ do Fornecedor
TE0|11|TE0_CODPRO|C|15|0|Cod. Produto|Codigo do Produto
TE0|12|TE0_DESPRO|C|70|0|Descrição|Descrição do Produto Arma
TE0|13|TE0_ITEM|C|4|0|Item|Item da Nota Fiscal
TE0|14|TE0_SEQ|C|4|0|Sequencia|Sequencia da Nota
TE0|15|TE0_ATIVO|C|14|0|Numero Ativo|Numero do Ativo
TE0|16|TE0_ESPEC|C|1|0|Especie|Especie da Arma
TE0|17|TE0_MARCA|C|6|0|Marca|Marca da Arma
TE0|18|TE0_CALIBR|C|6|0|Calibre|Calibre da Arma
TE0|19|TE0_MODELO|C|6|0|Modelo|Modelo da Arma de Fogo
TE0|20|TE0_FUNCIO|C|1|0|Func. Arma|Funcionamento da Arma
TE0|21|TE0_CORON|C|1|0|Coronha|Acabamento da Coronha
TE0|22|TE0_ACABA|C|1|0|Acabamento|Acabamento da Arma
TE0|23|TE0_CANO|C|1|0|Cano|Cano da Arma
TE0|24|TE0_QTDCAN|C|1|0|Qtd. Canos|Quantidade de Canos
TE0|25|TE0_TPRAIA|C|10|0|Tp. Raia|Tipo da Raia da Arma
TE0|26|TE0_QTDRAI|N|2|0|Qtd. Raia|Quantidade de Raia Arma
TE0|27|TE0_SENTRA|C|10|0|Sent. Raia|Sentido da Raia
TE0|28|TE0_CAPMUN|N|3|0|Cap. Munição|Capacidade de Munição
TE0|29|TE0_VALIDA|D|8|0|Dt Validade|Data Validade da Arma
TE0|30|TE0_NUMREG|C|10|0|Num Registro|Numero de Registro
TE0|31|TE0_DTREG|D|8|0|Dt. Registro|Data de Registro
TE0|32|TE0_ORGAO|C|3|0|Orgao Exp.|Orgão Expedidor
TE0|33|TE0_SINAE|N|10|0|Num. SINAE|Numero do SINAE
TE0|34|TE0_SINARM|C|17|0|Num. SINARM|Numero do SINARM
TE0|35|TE0_CDPAIS|C|6|0|Cod. Pais|Codigo do Pais Arma
TE0|36|TE0_DCPAIS|C|50|0|Descrição|Descrição do Pais Arma
TE0|37|TE0_DELEG|C|30|0|Delegacia|Delegacia Fiscalização
TE0|38|TE0_DOU|C|15|0|Public D.O.U|Protocolo Public D.O.U
TE0|39|TE0_DTDOU|D|8|0|Dt. D.O.U|Data Publicação D.O.U
TE0|40|TE0_SITUA|C|1|0|Situação|Situação da Arma
TE0|41|TE0_OBS|M|10|0|Observação|Observação
TE0|42|TE0_LOCAL|C|8|0|Local|Local de Alocação
TE0|43|TE0_CLIDES|C|30|0|Descrição|Descrição Cliente
TE0|44|TE0_POSTAL|C|8|0|Posto|Posto de Alocação
TE0|45|TE0_DSCPOS|C|50|0|Descrição|Descrição do Posto
TE0|46|TE0_DTALOC|D|8|0|Dt Alocação|Data de Alocação
TE0|47|TE0_ORIGEM|C|8|0|Origem|Origem
TE0|48|TE0_ENTIDA|C|3|0|Entidade|Entidade de Alocação
TE0|49|TE0_AGEND|D|8|0|Data Agend.|Data de Agendamento
TE0|50|TE0_PRVRET|D|8|0|Prev. Ret.|Previsão de Retorno
TE0|51|TE0_CODMOV|C|6|0|Cod. Mov|Codigo da Movimentação
TE0|52|TE0_FILLOC|C|6|0|Filial Local|Filial Local
TE0|53|TE0_ESPDSC|C|30|0|Esp.Arm|Espécie de arma
TE0|54|TE0_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### TE1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE1|01|TE1_FILIAL|C|6|0|Filial|Filial do Sistema
TE1|02|TE1_CODCOL|C|6|0|Cod. Col|Codigo do Colete
TE1|03|TE1_DOC|C|9|0|Num. Nota|Numero da Nota
TE1|04|TE1_SERIE|C|3|0|Serie Nota|Serie da Nota
TE1|05|TE1_DTNOTA|D|8|0|Data Nota|Data da Nota
TE1|06|TE1_COMPRA|D|8|0|Data Compra|Data de Compra
TE1|07|TE1_CODFOR|C|6|0|Cod. Fornec.|Cod. Fornecedor
TE1|08|TE1_LOJA|C|2|0|Loja|Loja Fornecedor
TE1|09|TE1_NOME|C|80|0|Razao Social|Razao Social Fornecedor
TE1|10|TE1_CNPJ|C|14|0|CNPJ|CNPJ Fornecedor
TE1|11|TE1_CODPRO|C|15|0|Cod. Produto|Codigo Produto
TE1|12|TE1_DESPRO|C|70|0|Descrição|Descrição Produto
TE1|13|TE1_ITEM|C|4|0|Item|Item da Nota
TE1|14|TE1_SEQ|C|4|0|Sequencia|Sequencia Nota
TE1|15|TE1_EXPED|C|3|0|Orgão Exped.|Orgão Expedidor
TE1|16|TE1_CERTAP|C|10|0|C.A|Cert. Aprovação
TE1|17|TE1_DTCA|D|8|0|Dt. C.A|Data C.A
TE1|18|TE1_LICENC|C|30|0|Lic. Prop|Lic. Propriedade
TE1|19|TE1_EMISSA|D|8|0|Dt. Lic|Dt. Emissão Lic.
TE1|20|TE1_NUMPUB|C|30|0|Num. Pub.|Num. Publicação
TE1|21|TE1_DTDOU|D|8|0|Dt. D.O.U|Dt. D.O.U
TE1|22|TE1_MARCA|C|15|0|Marca|Nome do Fabricante
TE1|23|TE1_COR|C|10|0|Cor|Cor Predominante
TE1|24|TE1_NIVEL|C|6|0|Nivel|Nivel de Segurança
TE1|25|TE1_DTFABR|D|8|0|DT Fabrica|Data de Fabricação
TE1|26|TE1_VALIDA|D|8|0|Dt. Validade|Data de Validade
TE1|27|TE1_NUMCOL|C|30|0|Num Colete|Numero do Colete
TE1|28|TE1_NUMSER|C|20|0|Num Serie|Numero de Serie
TE1|29|TE1_SINARM|C|17|0|SINARM|Num Sinarm
TE1|30|TE1_DTSINA|D|8|0|Dt. SINARM|Dt. SINARM
TE1|31|TE1_PLCDIA|C|10|0|Placa Diant.|Numero Placa Dianteira
TE1|32|TE1_PLCTRA|C|10|0|Placa. Tras.|Numero Placa Traseira
TE1|33|TE1_SITUA|C|1|0|Situação|Situação do Colete
TE1|34|TE1_OBSER|M|10|0|Observação|Observação
TE1|35|TE1_LOCAL|C|8|0|Local|Local de Alocação
TE1|36|TE1_CLIDES|C|30|0|Descrição|Descrição Local Alocação
TE1|37|TE1_POSTAL|C|8|0|Posto|Posto de Alocação
TE1|38|TE1_DSCPOS|C|50|0|Descrição|Descrição do Posto
TE1|39|TE1_DTALOC|D|8|0|Data|Data de Alocação
TE1|40|TE1_ORIGEM|C|8|0|Origem|Origem
TE1|41|TE1_ENTIDA|C|3|0|Entidade|Entidade
TE1|42|TE1_CODMOV|C|6|0|Cod. Mov.|Codigo da Movimentação
TE1|43|TE1_PRVRET|D|8|0|Data Retorno|Data de Retorno
TE1|44|TE1_TIPO|C|20|0|Tipo|Tipo do Colete
TE1|45|TE1_MODELO|C|20|0|Mod.Colete|Modelo do Colete
TE1|46|TE1_TAM|C|10|0|Tamanho|Tamanho do Colete
TE1|47|TE1_ALUGAD|C|1|0|Alugado|Col.Alugado
TE1|48|TE1_FILLOC|C|6|0|Filial Local|Filial Local
TE1|49|TE1_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### TE2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE2|01|TE2_FILIAL|C|6|0|Filial|Filial do Sistema
TE2|02|TE2_CODMUN|C|6|0|Codigo|Codigo da Munição
TE2|03|TE2_DOC|C|9|0|Num. Nota|Numero da Nota
TE2|04|TE2_SERIE|C|3|0|Serie Nota|Serie da Nota
TE2|05|TE2_DTNOTA|D|8|0|Data Nota|Data da Nota
TE2|06|TE2_COMPRA|D|8|0|Dta Compra|Data de Compra
TE2|07|TE2_CODFOR|C|6|0|Cod. Fornec.|Cod. Fornecedor
TE2|08|TE2_LOJA|C|2|0|Loja|Loja Fornecedor
TE2|09|TE2_NOME|C|80|0|Razão Social|Razão Social
TE2|10|TE2_CNPJ|C|14|0|CNPJ|CNPJ Fornecedor
TE2|11|TE2_REGFOR|C|15|0|Reg. Fornec.|Registro do Fornecedor
TE2|12|TE2_EMISSA|D|8|0|Dt. Registro|Data Emissao Registro
TE2|13|TE2_ORGAO|C|3|0|Órgão Exp.|Órgão Expedidor Registro
TE2|14|TE2_CODPRO|C|15|0|Cod. Produto|Código Produto
TE2|15|TE2_DESPRO|C|70|0|Descrição|Descrição Produto
TE2|16|TE2_ITEM|C|4|0|Item|Item da Nota
TE2|17|TE2_SEQ|C|4|0|Sequencia|Sequencia da  Nota
TE2|18|TE2_QTDMUN|N|5|0|Qtd. Municao|Qtd. Municoes do Blister
TE2|19|TE2_LOTE|C|30|0|Lote Blister|Numero do Lote do Blister
TE2|20|TE2_VALIDA|D|8|0|Validade|Validade do Blister
TE2|21|TE2_ESPEC|C|1|0| Espécie|Espécie da Municao
TE2|22|TE2_MARCA|C|6|0|Marca|Marca da Munição
TE2|23|TE2_CALIBR|C|6|0|Calibre|Calibre da Arma de Fogo
TE2|24|TE2_MODELO|C|6|0|Modelo|Modelo da Arma de Fogo
TE2|25|TE2_SINAE|N|10|0|Num. Sinae|Numero do SINAE
TE2|26|TE2_SINARM|C|15|0|Num. Sinarm|Numero do Sinarm
TE2|27|TE2_DTSINA|D|8|0|Dt. Sinarm|Data de Emissão do SINARM
TE2|28|TE2_OBSER|M|10|0|Observação|Observação
TE2|29|TE2_LOCAL|C|8|0|Local|Local de Alocação
TE2|30|TE2_CLIDES|C|30|0|Nome Cli|Descrição
TE2|31|TE2_POSTAL|C|8|0|Posto|Posto de Alocação
TE2|32|TE2_DSCPOS|C|50|0|Descrição|Descrição do Posto
TE2|33|TE2_DTALOC|D|8|0|DATA|Data de Alocação
TE2|34|TE2_ORIGEM|C|8|0|Origem|Origem
TE2|35|TE2_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### TE3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE3|01|TE3_FILIAL|C|6|0|Filial|Filial do Sistema
TE3|02|TE3_CODIGO|C|6|0|Codigo|Codigo do Limite
TE3|03|TE3_DESC|C|30|0|Descrição|Descrição do registro
TE3|04|TE3_ENTEXE|N|2|0|Entrada ext.|Entrada extra
TE3|05|TE3_ENTATE|N|2|0|Entrada Atr.|Entrada Atraso
TE3|06|TE3_SAIEXE|N|2|0|Saída Extra|Saída Extra
TE3|07|TE3_SAIATE|N|2|0|Saída Atraso|Saída Atraso
TE3|08|TE3_ENTEXL|N|2|0|Entrada ext.|Entrada extra
TE3|09|TE3_ENTATL|N|2|0|Entrada Atr.|Entrada Atraso
TE3|10|TE3_SAIEXL|N|2|0|Saída Extra|Saída Extra
TE3|11|TE3_SAIATL|N|2|0|Saída Atraso|Saída Atraso
TE3|12|TE3_MINSAI|N|2|0|Mínimo saída|Mínimo saída
TE3|13|TE3_MAXSAI|N|2|0|Máximo saída|Máximo saída
TE3|14|TE3_RETANT|N|2|0|Retorno Ant.|Retorno Antecipado
TE3|15|TE3_RETATR|N|2|0|Retorno Atr.|Retorno Atraso
--- ### TE4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE4|01|TE4_FILIAL|C|6|0|Filial|Filial do Sistema
TE4|02|TE4_COD|C|6|0|Cod. Ocorre|Cód. Ocorrência
TE4|03|TE4_TPOCOR|C|1|0|Tp. Ocorrenc|Tipo da Ocorrência
TE4|04|TE4_CONTAT|C|6|0|Contato|Contato da Ocorrência
TE4|05|TE4_NOMCTN|C|50|0|Nome|Nome do Contato
TE4|06|TE4_DTOCOR|D|8|0|Data da Ocor|Data da Ocorrência
TE4|07|TE4_NUMBO|C|15|0|Numero B.O|Numero B.O
TE4|08|TE4_DTBO|D|8|0|Data B.O.|Data de Abertura B.O.
TE4|09|TE4_DELEGA|C|15|0|Delegacia|Nome da Delegacia
TE4|10|TE4_NOMDEL|C|30|0|Delegado|Nome do Delegado
TE4|11|TE4_ESCRIV|C|30|0|Escrivão|Nome do Escrivão
TE4|12|TE4_OCPOST|C|1|0|Ocor Posto?|Ocorreu no Posto?
TE4|13|TE4_LOCAL|C|8|0|Posto|Posto de Trabalho
TE4|14|TE4_DSCPOS|C|50|0|Nome Posto|Nome do Posto Atendimento
TE4|15|TE4_LOCINT|C|8|0|Local Inter.|Local Interno
TE4|16|TE4_DSCINT|C|30|0|Descrição|Descrição Local Interno
TE4|17|TE4_END|C|40|0|Endereço|Endereço da Ocorrência
TE4|18|TE4_BAIRRO|C|30|0|Bairro|Bairro da Ocorrência
TE4|19|TE4_CEP|C|8|0|CEP|CEP da Ocorrência
TE4|20|TE4_EST|C|2|0|Estado|Estado da Ocorrência
TE4|21|TE4_ESTADO|C|20|0|Nome Estado|Nome do Estado
TE4|22|TE4_CODMUN|C|5|0|Cod. Mun|Código do Município
TE4|23|TE4_MUN|C|60|0|Município|Município da Ocorrência
TE4|24|TE4_NUMOS|C|6|0|Número O.S|Número dOrdem de Serviço
TE4|25|TE4_FREAR|C|1|0|FREAR|FREAR
TE4|26|TE4_DESCRI|M|10|0|Descrição|Descrição do Fato
TE4|27|TE4_MOTIVO|M|10|0|Motivo Alter|Motivo de Alteração FREAR
TE4|28|TE4_OBS|M|10|0|Observação|Observação
TE4|29|TE4_CDUSER|C|6|0|Cod. Usuário|Código do Usuário
TE4|30|TE4_CODTIX|C|6|0|Motivo|Código do Motivo
TE4|31|TE4_DSCMOT|C|40|0|Descrição|Descrição do Motivo
TE4|32|TE4_FILLOC|C|6|0|Filial Local|Filial do Local
TE4|33|TE4_FILINT|C|6|0|Filial Inter|Filial de Local Interno
--- ### TE5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE5|01|TE5_FILIAL|C|6|0|Filial|Filial do Sistema
TE5|02|TE5_CDOCOR|C|6|0|Cod. Ocorr.|Codigo da Ocorrencia
TE5|03|TE5_ITEM|C|2|0|Item|Item
TE5|04|TE5_ATEND|C|14|0|Atendente|Codigo do atendente
TE5|05|TE5_NOMATE|C|30|0|Nome Atend.|Nome do Atendente
TE5|06|TE5_FUNCAO|C|5|0|Funcao|Função do Atendente
TE5|07|TE5_CDFUNC|C|6|0|Cod. Func.|Codigo do Funcionario
TE5|08|TE5_TURNO|C|3|0|Turno|Turno de Trabalho
TE5|09|TE5_CODTIT|C|6|0|Disciplina|Código da disciplina
--- ### TE6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE6|01|TE6_FILIAL|C|6|0|Filial|Filial do Sistema
TE6|02|TE6_CDOCOR|C|6|0|Cod. Ocor.|Codigo da ocorrencia
TE6|03|TE6_ATEND|C|14|0|Cod. Atend.|Codigo do Atendente
TE6|04|TE6_ITEM|C|2|0|Item|Item
TE6|05|TE6_SBITEM|C|2|0|Item|Item Filho
TE6|06|TE6_ARMA|C|6|0|Cod. Arma|Codigo da Arma
TE6|07|TE6_DSCPRO|C|70|0|Descrição|Descrição da Arma
TE6|08|TE6_ATIVO|C|14|0|Ativo|Numero do Ativo da Arma
TE6|09|TE6_MARCA|C|6|0|Marca|Marca da Arma
TE6|10|TE6_MODELO|C|6|0|Modelo|Modelo da Arma
TE6|11|TE6_NUMREG|C|10|0|Num Reg|Numero do Registro
TE6|12|TE6_NSINAR|C|17|0|Num. Sinarm.|Numero do Sinarm
TE6|13|TE6_MOTIVO|M|10|0|Motivo FREAR|Informe o Motivo do FREAR
TE6|14|TE6_FREAR|C|1|0|FREAR|FREAR
--- ### TE7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE7|01|TE7_FILIAL|C|6|0|Filial|Filial do Sistema
TE7|02|TE7_ITEM|C|2|0|Item|Item
TE7|03|TE7_CONTAT|C|6|0|Cod. Contato|Código do Contato
TE7|04|TE7_NOME|C|50|0|Nome|Nome do Contato
TE7|05|TE7_ENVOLV|C|1|0|Vit. ou Test|Vitima ou Testemunha?
TE7|06|TE7_CDOCOR|C|6|0|Cod. Ocorr.|Código da Ocorrência
--- ### TEP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEP|01|TEP_FILIAL|C|6|0|Filial|Filial do Sistema
TEP|02|TEP_CODDES|C|6|0|Cod. Dest.|Código Destinatário
TEP|03|TEP_NOME|C|40|0|Nome Dest.|Nome Destinatário
TEP|04|TEP_EMAIL|C|50|0|Email|Email do Destinatário
TEP|05|TEP_PERFIL|C|1|0|Perfil|Perfil Destinatário
TEP|06|TEP_OUTPER|C|40|0|Outro Dest.|Outro Destinatário
TEP|07|TEP_STATUS|C|1|0|Status|Status do Destinatário
--- ### TEQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEQ|01|TEQ_FILIAL|C|6|0|Filial|Filial do Sistema
TEQ|02|TEQ_CODEVE|C|6|0|Cod. Evento|Código Evento
TEQ|03|TEQ_DESCRI|C|30|0|Desc.Evento|Descrição do Evento
TEQ|04|TEQ_TABELA|C|3|0|Tabela|Tabela de verificação
TEQ|05|TEQ_NTAB|C|30|0|Nom.Tab.|Nome das Tabelas
TEQ|06|TEQ_CAMPO|C|10|0|Campo Tab.|Campo da Tabela
TEQ|07|TEQ_NCAMP|C|25|0|Nome Campo|Nome dos campos
TEQ|08|TEQ_OPEMAT|C|1|0|Op.Aritmetic|Operador Aritmético
TEQ|09|TEQ_PARAME|N|8|0|Val.Param.|Parâmetro
TEQ|10|TEQ_TPOORE|C|1|0|Oper. Relac.|Operador Relacional
TEQ|11|TEQ_CONDIC|C|1|0|Cond. Valid.|Condição de validação
TEQ|12|TEQ_VLRRES|N|8|0|Val. Cond.|Valor Condição
TEQ|13|TEQ_TITEML|C|30|0|Tit.Email|Título Email
TEQ|14|TEQ_TXTEML|M|10|0|Texto Email|Texto do Email
TEQ|15|TEQ_CPORET|C|10|0|Campo Ret.|Campo de Retorno
TEQ|16|TEQ_NCPORE|C|25|0|Nome Cpo.Ret|Nome do campo retorno
TEQ|17|TEQ_INFEVE|C|1|0|Infs. Evento|Infs. Evento Email
TEQ|18|TEQ_STATUS|C|1|0|Status|Status do Evento
--- ### TER
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TER|01|TER_FILIAL|C|6|0|Filial|Filial do Sistema
TER|02|TER_CODIGO|C|8|0|Cod Local|Codigo do Local Interno
TER|03|TER_DESCRI|C|50|0|Descrição|Descrição do Local
TER|04|TER_END|C|40|0|Endereço|Endereço do Local
TER|05|TER_BAIRRO|C|30|0|Bairro|Bairro do Local
TER|06|TER_ESTADO|C|2|0|Estado|Estado do Local
TER|07|TER_NOMEST|C|20|0|Nome Estado|Nome do Estado
TER|08|TER_CODMUN|C|5|0|Cd municipio|Codigo do Municipio
TER|09|TER_NOMMUN|C|60|0|Municipio|Municipio do Local
TER|10|TER_CCUSTO|C|9|0|C. Custo|Centro de Custo
--- ### TES
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TES|01|TES_FILIAL|C|6|0|Filial|Filial do Sistema
TES|02|TES_CDOCOR|C|6|0|Cod. Ocorr.|Código da Ocorrência
TES|03|TES_ATEND|C|14|0|Cod. Atend.|Código do Atendente
TES|04|TES_ITEM|C|2|0|Item|Item do colete
TES|05|TES_CODCOL|C|6|0|Cod. Colete|Código do Colete
TES|06|TES_DSCPRO|C|30|0|Descrição|Descrição do Colete
TES|07|TES_FABRIC|C|15|0|Fabricante|Fabricante
TES|08|TES_VALIDA|D|8|0|Validade|Validade do Colete
TES|09|TES_COLETE|C|30|0|Num. Colete|Número do Colete
TES|10|TES_NUMSER|C|20|0|Num. Serie|Número de Série do Colete
TES|11|TES_SINARM|C|17|0|Num. Sinarm|Número do Sinarm
TES|12|TES_PLCDIA|C|10|0|Placa Diant.|Placa Dianteira
TES|13|TES_PLCTRA|C|10|0|Placa Tras.|Placa Traseira
TES|14|TES_MOTIVO|M|10|0|Motivo|Motivo Frear
TES|15|TES_FREAR|C|1|0|FREAR|FREAR
--- ### TET
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TET|01|TET_FILIAL|C|6|0|Filial|Filial do Sistema
TET|02|TET_CDOCOR|C|6|0|Cod. Ocorr.|Código da Ocorrência
TET|03|TET_ATEND|C|14|0|Cod. Atend.|Código do Atendente
TET|04|TET_ITEM|C|2|0|Item|Item da Munição
TET|05|TET_PRODUT|C|15|0|Cód. Produto|Codigo do Produto
TET|06|TET_DSCPRO|C|70|0|Descrição|Descrição do Produto
TET|07|TET_LOTE|C|30|0|Lote Blister|Lote Blister da Munição
TET|08|TET_DTVAL|D|8|0|Dt. Validade|Data Validade Munição
TET|09|TET_MARCA|C|6|0|Marca|Marca da Munição
TET|10|TET_CALIBR|C|6|0|Calibre|Calibre da Munição
TET|11|TET_SINARM|C|15|0|Num Sinarm|Número do Sinarm
TET|12|TET_FREA|C|1|0|F.R.E.A|status do frear
TET|13|TET_QTDMUN|N|5|0|Qtd Munição|Quantidade de Munição
TET|14|TET_UTILIZ|C|1|0|Utilizada|Número Utilizado
TET|15|TET_RECUPE|C|1|0|Recuperada|munição recuperada
TET|16|TET_RECDE|C|1|0|Recuper. De|Munições recuperadas de
TET|17|TET_CODMUN|C|6|0|Cod. Munição|Código da Munição
--- ### TEU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEU|01|TEU_FILIAL|C|6|0|Filial|Filial do Sistema
TEU|02|TEU_CODIGO|C|6|0|Codigo|Codigo da Manutenção
TEU|03|TEU_TPARMA|C|1|0|Tp Armamento|Tipo de Armamento
TEU|04|TEU_CDARM|C|6|0|Armamento|Codigo do Armamento
TEU|05|TEU_DSCARM|C|30|0|Descrição|Descrição do Armamento
TEU|06|TEU_ENTORI|C|1|0|Entidade Ori|Entidade de Origem
TEU|07|TEU_CODLOC|C|8|0|Cod Loc Mun.|Codigo do Local Municao
TEU|08|TEU_DSCLOC|C|50|0|Descrição|Descrição do Local
TEU|09|TEU_QTDMUN|N|5|0|Qtd Municao|Quantidade de Munição
TEU|10|TEU_CDRESP|C|14|0|Responsavel|Codigo do Responsavel
TEU|11|TEU_RESPON|C|50|0|Nome Resp|Nome do Responsavel
TEU|12|TEU_DTABER|D|8|0|Dt. Abertura|Data de Abertura
TEU|13|TEU_DTINI|D|8|0|Data Inicio|Data de Inicio Manutenção
TEU|14|TEU_HRINI|C|5|0|Hora Inicio|Hora Inicio Manutenção
TEU|15|TEU_DTFIM|D|8|0|Data Termino|Data Termino Manutenção
TEU|16|TEU_HRFIM|C|5|0|Hora Termino|Hora Termino Manutenção
TEU|17|TEU_LOCAL|C|1|0|Mnt. Local?|Manutencao no Local?
TEU|18|TEU_TPMNT|C|1|0|Tp. Manut|Tipo de manutenção
TEU|19|TEU_MOTIVO|M|10|0|Motivo|Motivo da manutenção
TEU|20|TEU_LAUDO|M|10|0|Laudo|Laudo da Manutenção
TEU|21|TEU_HRMNT|C|5|0|Horas Manut.|Horas de Manutencao
TEU|22|TEU_STATUS|C|1|0|Status|Status da Manutencao
TEU|23|TEU_ULTSTA|C|1|0|Ult. Status|Ultimo Status
TEU|24|TEU_ENTIDA|C|1|0|Entidade|Entidade
TEU|25|TEU_ORIGEM|C|8|0|Origem|Origem da Manutenção
TEU|26|TEU_TPREST|C|1|0|Tipo Resp.|Tipo do Responsável
--- ### TEV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEV|01|TEV_FILIAL|C|6|0|Filial|Filial do Sistema
TEV|02|TEV_CODLOC|C|6|0|Cod. Locacao|Codigo da Locacao
TEV|03|TEV_ITEM|C|2|0|Item|Item
TEV|04|TEV_MODCOB|C|1|0|Cobrança|Modo de Cobrança
TEV|05|TEV_UM|C|2|0|Unidade|Unidade de Medida
TEV|06|TEV_QTDE|N|11|2|Quantidade|Quantidade
TEV|07|TEV_VLRUNI|N|14|2|Valor Unitar|Valor Unitario
TEV|08|TEV_SUBTOT|N|14|2|Subtotal|Subtotal
TEV|09|TEV_VLTOT|N|14|2|Vlr. Total|Valor Total
TEV|10|TEV_SLD|N|11|2|Saldo|Saldo do Item
TEV|11|TEV_LUCRO|N|5|2|%Lucro|Percentual de lucro
TEV|12|TEV_TXLUCR|N|14|2|Vlr. Lucro|Valor da taxa de lucro
TEV|13|TEV_ADM|N|5|2|%Adm|% Taxa da Administrativa
TEV|14|TEV_TXADM|N|14|2|Vlr. Tx Adm|Valor taxa administrativa
TEV|15|TEV_OBS|M|10|0|Observacao|Observacao
--- ### TEW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEW|01|TEW_FILIAL|C|6|0|Filial|Filial do Sistema
TEW|02|TEW_CODMV|C|10|0|Cod Moviment|Cod. Mov. Equipamento
TEW|03|TEW_ORCSER|C|11|0|No Orcamento|Codigo Orcamento Serviços
TEW|04|TEW_CODEQU|C|6|0|Cod. Loc. Eq|Codigo Conf. Loc Equip
TEW|05|TEW_PRODUT|C|15|0|Produto|Codigo do Produto
TEW|06|TEW_BAATD|C|20|0|Base Atend.|Base de Atendimento
TEW|07|TEW_FILBAT|C|6|0|Fil Base Atd|Fil. Base Atendimento
TEW|08|TEW_DTSEPA|D|8|0|Dt Separa.|Data da Separacao Equip
TEW|09|TEW_DTRINI|D|8|0|Dt Real Inic|Dt Ini Real da Alocacao
TEW|10|TEW_DTRFIM|D|8|0|Dt Real Fim|Data Final Real Alocacao
TEW|11|TEW_NUMPED|C|6|0|Num. Pedido|Numero do Pedido
TEW|12|TEW_ITEMPV|C|2|0|Item PV|Item do Pedido de Remessa
TEW|13|TEW_NFSAI|C|9|0|Cod Doc Said|Numero do Docto. de Saida
TEW|14|TEW_SERSAI|C|3|0|Ser Doc Said|Serie do Documento Saida
TEW|15|TEW_ITSAI|C|2|0|It NF Saida|Item da Nota Fiscal
TEW|16|TEW_NFENT|C|9|0|Cod Doc Entr|Numero do Documento
TEW|17|TEW_SERENT|C|3|0|Ser Doc Entr|Serie Documento Entrada
TEW|18|TEW_ITENT|C|4|0|It NF Entrad|Item Nota Fiscal Entrada
TEW|19|TEW_SUBSTI|C|10|0|Cod Mov Subs|Codigo Mov. Substituto
TEW|20|TEW_OBSMNT|C|60|0|Obs. Mnt.|Observacao da Manutencao
TEW|21|TEW_MOTIVO|C|1|0|Situação|Sit. Movimento
TEW|22|TEW_DTAMNT|D|8|0|Data Manut|Data Realiz. Manutencao
TEW|23|TEW_CODKIT|C|15|0|Codigo Kit|Codigo do Kit
TEW|24|TEW_TPOS|C|1|0|Origem OS|Origem OS
TEW|25|TEW_KITSEQ|C|6|0|Cod Agrp Kit|Codigo Agrupamento Kit
TEW|26|TEW_NUMOS|C|6|0|OS Manut|OS Manutencao Preventiva
TEW|27|TEW_ITEMOS|C|2|0|It OS Manut|Item da OS Manut Preventi
TEW|28|TEW_FECHOS|D|8|0|Dt Fecham OS|Data Fechamento da OS
TEW|29|TEW_TIPO|C|1|0|Movimento|Tipo do Movimento
TEW|30|TEW_RESCOD|C|6|0|Cod. Reserva|Código da Reserva
TEW|31|TEW_ITAPUR|C|6|0|Cod. Apur|Código Apuração
TEW|32|TEW_DSPROD|C|70|0|Prod. Desc.|Desc. Produto
TEW|33|TEW_EQ3|C|1|0|Eq. Terceiro|Equipamento de terceiros?
TEW|34|TEW_CODATD|C|6|0|Cód. Atenden|Cód. Atendente
TEW|35|TEW_DSATD|C|30|0|Atendente|Nome Atendente
TEW|36|TEW_LOCAL|C|8|0|Cod. Local|Cod. Local
TEW|37|TEW_DSLOC|C|50|0|Desc. Local|Descrição do Local
TEW|38|TEW_CODCLI|C|6|0|Cod Cliente|Código Cliente
TEW|39|TEW_LOJCLI|C|2|0|Loja Cliente|Loja Cliente
TEW|40|TEW_DESCLI|C|80|0|Nome Cliente|Nome do Cliente
TEW|41|TEW_CONTRT|C|30|0|Contrato|Número Contrato
TEW|42|TEW_LEGEND|C|30|0|Status Equip|Status do Equipamento
TEW|43|TEW_SDOCE|C|3|0|Sér Doc Entr|Série Documento Entrada
TEW|44|TEW_SDOCS|C|3|0|Sér Doc Sai.|Série Documento Saida
TEW|45|TEW_DTPFIM|D|8|0|Dt. Fim Prev|Data fim parada prevista
TEW|46|TEW_QTDVEN|N|11|0|Quantidade|Quantidade de venda
TEW|47|TEW_QTDRES|N|11|0|Qtd Res|Quantidade Reservada
TEW|48|TEW_QTDRET|N|11|0|Qtd. Retorno|Quantidade de Retorno
--- ### TEX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEX|01|TEX_FILIAL|C|6|0|Filial|Filial
TEX|02|TEX_CODIGO|C|6|0|Codigo|Codigo
TEX|03|TEX_CODTCW|C|6|0|Cod. Config|Codigo Configuracao
TEX|04|TEX_TIPOPE|C|1|0|Tipo Item|Tipo Item
TEX|05|TEX_DESCRI|C|30|0|Descricao|Descricao
TEX|06|TEX_TIPOTX|C|1|0|Tipo Taxa|Tipo Taxa
TEX|07|TEX_VALOR|N|14|2|Valor|Valor
TEX|08|TEX_ITEM|C|3|0|Item|Item
TEX|09|TEX_NICKPO|C|25|0|Nome Porcent|Nome Cel Porcentagem
TEX|10|TEX_FORMPO|C|99|0|Formula Porc|Formula Porcentagem
TEX|11|TEX_NICK|C|25|0|Nome Celula|Nome Celula
TEX|12|TEX_FORMUL|C|99|0|Formula Plan|Formula Planilha de Calc.
TEX|13|TEX_REVISA|C|4|0|Revisão|Controle de Revisão
--- ### TEY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEY|01|TEY_FILIAL|C|6|0|Filial|Filial do Sistema
TEY|02|TEY_CODIGO|C|6|0|Codigo|Codigo Relacionameto
TEY|03|TEY_ITEM|C|4|0|Item|Item Destinatário
TEY|04|TEY_CODEVE|C|6|0|Cod. Evento|Código do Evento
TEY|05|TEY_CODDES|C|6|0|Cod. Dest.|Código do Destinatário
TEY|06|TEY_NOME|C|40|0|Nome Dest.|Nome do Destinatário
TEY|07|TEY_EMAIL|C|50|0|Email|Email do Destinatário
TEY|08|TEY_PERFIL|C|1|0|Perfil|Perfil Destinatário
TEY|09|TEY_OUTPER|C|40|0|Outro Dest.|Outro Destinatário
TEY|10|TEY_STATUS|C|1|0|Status|Status do Destinatário
--- ### TEZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEZ|01|TEZ_FILIAL|C|6|0|Filial|Filial do Sistema
TEZ|02|TEZ_PRODUT|C|15|0|Produto Kit|Produto Referência
TEZ|03|TEZ_PRODES|C|70|0|Descrição Ki|Descrição do Produto Kit
TEZ|04|TEZ_ITPROD|C|15|0|Item do Kit|Produto Item do Kit
TEZ|05|TEZ_ITPDES|C|70|0|Desc It Kit|Descrição do Item do Kit
TEZ|06|TEZ_ITQTDE|N|2|0|Quantidade|Quantidade
--- ### TFF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFF|01|TFF_FILIAL|C|6|0|Filial|Filial do Sistema
TFF|02|TFF_COD|C|6|0|Código|Código recursos humanos
TFF|03|TFF_ITEM|C|2|0|Item|Número do Item do produto
TFF|04|TFF_PRODUT|C|15|0|Produto|Código do Produto
TFF|05|TFF_DESCRI|C|70|0|Descrição|Descrição Produto
TFF|06|TFF_UM|C|2|0|Unidade|Unidade de Medida
TFF|07|TFF_QTDVEN|N|11|0|Quantidade|Quantidade de Venda
TFF|08|TFF_PRCVEN|N|14|2|Vlr Unit Rh|Valor Unitario do Recurso
TFF|09|TFF_SUBTOT|N|14|2|SubTotal|SubTotal
TFF|10|TFF_TOTMI|N|14|2|Tot Mat Impl|Total Mat. Implantacao
TFF|11|TFF_TOTMC|N|14|2|Tot Mat Cons|Total Material de Consumo
TFF|12|TFF_TOTUNI|N|14|2|Total.Unifor|Total do Uniforme
TFF|13|TFF_TOTARM|N|14|2|Tot. Armame |Total do Armamento
TFF|14|TFF_TOTPLA|N|14|2|Tot. Plan.|Total da Planilha
TFF|15|TFF_GERPLA|N|14|2|Tot. Ger Pla|Total Geral da Planilha
TFF|16|TFF_TOTAL|N|14|2|Vlr. Total|Valor Total dos Recursos
TFF|17|TFF_LOCAL|C|8|0|Local|Cód. Local de Atend.
TFF|18|TFF_PERINI|D|8|0|Per. Inicio|Periodo Inicial Aloc
TFF|19|TFF_PERFIM|D|8|0|Per. Final|Período Final Aloc
TFF|20|TFF_HORAIN|C|5|0|Hora Inicio|Hora Inicio Alocação
TFF|21|TFF_HORAFI|C|5|0|Hora Final|Hora Final Alocação
TFF|22|TFF_FUNCAO|C|5|0|Função|Código da Função
TFF|23|TFF_DFUNC|C|20|0|Descrição|Descrição da Função
TFF|24|TFF_TURNO|C|3|0|Turno|Código do Turno
TFF|25|TFF_DTURNO|C|50|0|Descrição|Descrição do Turno
TFF|26|TFF_SEQTRN|C|2|0|Seq. turno|Seq. Ini. do Turno
TFF|27|TFF_CARGO|C|5|0|Cargo|Cargo do Recurso
TFF|28|TFF_DCARGO|C|30|0|Desc.Cargo|Descrição do Cargo
TFF|29|TFF_DESCON|N|5|2|%Desconto|Percentual de Desconto
TFF|30|TFF_ESCALA|C|6|0|Escala|Codigo da Escala
TFF|31|TFF_NOMESC|C|60|0|Desc. Escala|Descricao da Escala
TFF|32|TFF_CALEND|C|6|0|Calendario|Codigo do Calendario
TFF|33|TFF_QTPREV|N|11|0|Aloc. Previs|Previsão de Pessoas no po
TFF|34|TFF_DSCALE|C|30|0|Desc. Calend|Descricao do Calendario
TFF|35|TFF_VALDES|N|14|2|Vlr.Desconto|Valor do Desconto
TFF|36|TFF_CODPAI|C|6|0|Cod Local|Codigo Local x Orçamento
TFF|37|TFF_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TFF|38|TFF_CONREV|C|3|0|Revisao|Sequencia da Revisao
TFF|39|TFF_CALCMD|M|10|0|Mem. de Calc|Memória de calculo
TFF|40|TFF_CODSUB|C|6|0|Cod Subst.|Código Subst
TFF|41|TFF_LUCRO|N|5|2|%Lucro|Percentual de lucro
TFF|42|TFF_TXLUCR|N|14|2|Vlr. Lucro|Valor da taxa de lucro
TFF|43|TFF_ADM|N|5|2|%Adm|% da Taxa administrativa
TFF|44|TFF_TXADM|N|14|2|Vlr. Tx Adm|Valor taxa administrativa
TFF|45|TFF_COBCTR|C|1|0|Cob.Contrato|Cobra Contrato?
TFF|46|TFF_NARMA|N|3|0|Num. Armas|Número de armas
TFF|47|TFF_NCOLE|N|3|0|Num. Coletes|Número de coletes
TFF|48|TFF_PERMAT|N|12|2|% Material|% Material apontado
TFF|49|TFF_VLRMAT|N|14|2|Vlr Mat Impl|Vlr Materiais Implantação
TFF|50|TFF_TOTMES|N|14|2|Mensal RH|Total mensal do RH
TFF|51|TFF_INSALU|C|1|0|Insalub.|Insalubridade
TFF|52|TFF_GRAUIN|C|1|0|Grau Insal.|Grau de Insalubridade
TFF|53|TFF_PERICU|C|1|0|Pericul.|Periculosidade
TFF|54|TFF_ENCE|C|1|0|Encerrado?|Encerrado?
TFF|55|TFF_PROCES|L|1|0|Processado|Processado
TFF|56|TFF_TESPED|C|3|0|TES Pedido|TES Pedido de venda
TFF|57|TFF_CHVTWO|C|21|0|Chav. Facili|Chave do Faciltador
TFF|58|TFF_ITCNB|C|3|0|Item CNB|Item CNB
TFF|59|TFF_TABXML|M|10|0|XML|XML tabela precificação
TFF|60|TFF_DPLAN|C|30|0|Desc Planil|Descricao da Planilha
TFF|61|TFF_PLACOD|C|6|0|Cód.Planilha|Código Planilha de Preço
TFF|62|TFF_PLAREV|C|3|0|Revisão Plan|Revisão Planilha de Preço
TFF|63|TFF_QTDHRS|C|5|0|Quant. Horas|Quantidade de Horas
TFF|64|TFF_HRSSAL|C|5|0|Saldo Horas|Saldo de Horas
TFF|65|TFF_VLPRPA|N|14|2|Vlr.Prox.Par|Valor da Próxima Parcela
TFF|66|TFF_ITEXOP|C|1|0|It. Ext. Op.|Item Extra Operacional
TFF|67|TFF_MODPLA|C|1|0|Planeja Revi|Planeja Revisão
TFF|68|TFF_CODREL|C|6|0|Cod.Relacion|Codigo Relacionado
TFF|69|TFF_DTENCE|D|8|0| DT.Encerrad|Data do Encerramento
TFF|70|TFF_GERVAG|C|1|0|Gera Vaga?|Gera vaga operacional?
TFF|71|TFF_PRDRET|C|15|0|Prd. Ret|Produto Retroativo
TFF|72|TFF_CODTWO|C|6|0|Cod. Facilit|Codigo do Facilitador
TFF|73|TFF_CODLIM|C|6|0|Cod. Limite|Codigo Limite
TFF|74|TFF_TPCOBR|C|2|0|Tipo de Cobr|Tipo de Cobrança
TFF|75|TFF_DSCCOB|C|30|0|Desc. Tp. Cb|Descrição do Tipo de Cob.
TFF|76|TFF_QTDTIP|N|14|2|Quantidade|Quantidade
TFF|77|TFF_VLRPRP|N|14|2|Valor Propos|Valor Proposto
TFF|78|TFF_VLRCOB|N|14|2|Valor Cobrad|Valor Cobrado
TFF|79|TFF_FINDME|C|1|0|Int.Find-me?|Integra Find-me?
TFF|80|TFF_QTDVAG|N|2|0|Qtd. Vagas|Qtd. de vagas solicitadas
TFF|81|TFF_VLRCON|N|14|2|Vlr Mat Cons|Vlr Materiais de Consumo
TFF|82|TFF_PLUCRO|N|6|2|Margem Lucro|Margem de Lucro
TFF|83|TFF_VLFIXO|N|12|2|Vl Fixo Brut|Valor Fixo Bruto
TFF|84|TFF_AREAPR|N|9|2|Area de Prod|Area de Produtividade
TFF|85|TFF_METRAT|N|9|2|Metra. Atend|Metragem Atendida
TFF|86|TFF_REGRA|C|2|0|Regra Apont.|Regra de Apontamento
TFF|87|TFF_NOMSPA|C|20|0|Desc. Regra|Descrição da Regra de Ap.
--- ### TFG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFG|01|TFG_FILIAL|C|6|0|Filial|Filial do Sistema
TFG|02|TFG_COD|C|6|0|Código|Código de Recursos MI
TFG|03|TFG_LOCAL|C|8|0|Local|Cód. Local de Atend.
TFG|04|TFG_ITEM|C|2|0|Item|Número do Item do produto
TFG|05|TFG_PRODUT|C|15|0|Produto|Código do Produto
TFG|06|TFG_DESCRI|C|70|0|Descrição|Descrição do Produto
TFG|07|TFG_UM|C|2|0|Unidade|Unidade de Medida
TFG|08|TFG_QTDVEN|N|11|2|Quantidade|Quantidade de Venda
TFG|09|TFG_PRCVEN|N|14|2|Vlr. Venda|Valor Unitário Venda
TFG|10|TFG_PERINI|D|8|0|Per. Inicio|Período Inicial Aloc
TFG|11|TFG_PERFIM|D|8|0|Per. Final|Período Final Aloc
TFG|12|TFG_TOTAL|N|14|2|SubTotal|Valor Unitario na Tabela
TFG|13|TFG_DESCON|N|5|2|%Desconto|Percentual de Desconto
TFG|14|TFG_VALDES|N|14|2|Vlr.Desconto|Valor do Desconto
TFG|15|TFG_TES|C|3|0|TES Estoque|TES Controle de Estoque
TFG|16|TFG_CODPAI|C|6|0|Codigo Pai|Codigo da Tabela Pai
TFG|17|TFG_SLD|N|11|2|Saldo|Saldo do Item
TFG|18|TFG_CODSUB|C|6|0|Cod. Subst.|Código Subst
TFG|19|TFG_TOTGER|N|14|2|Vlr.Total|Valor Total Geral
TFG|20|TFG_LUCRO|N|5|2|%Lucro|Percentual de lucro
TFG|21|TFG_TXLUCR|N|14|2|Vlr. Lucro|Valor da taxa de lucro
TFG|22|TFG_ADM|N|5|2|%Adm|% da Taxa Administrativa
TFG|23|TFG_TXADM|N|14|2|Vlr. Tx Adm|Valor taxa administrativa
TFG|24|TFG_COBCTR|C|1|0|Cob.Contrato|Cobra Contrato?
TFG|25|TFG_VIDMES|N|3|0|Vida Útil|Vida Útil
TFG|26|TFG_DPRMES|N|14|2|Depr. Mens.|Depr. Mensal
TFG|27|TFG_RESRET|N|11|2|Res. Elim.|Resíduo Eliminado
TFG|28|TFG_CHVTWO|C|21|0|Chv Facilita|Chave do Facilitador
TFG|29|TFG_ITCNB|C|3|0|Item CNB|Item CNB
TFG|30|TFG_CONTRT|C|15|0|Contrato|Contrato
TFG|31|TFG_CONREV|C|3|0|Revisão|Revisão
TFG|32|TFG_VLATIV|N|14|2|Vl Ativo|Valor do Ativo de Implant
TFG|33|TFG_TESPED|C|3|0|TES Pedido|TES Pedido de venda
TFG|34|TFG_VLPRPA|N|14|2|Vlr.Prox.Par|Valor da Próxima Parcela
TFG|35|TFG_MODPLA|C|1|0|Planeja Revi|Planeja Revisão
TFG|36|TFG_CODREL|C|6|0|Cod.Relacion|Codigo Relacionado
TFG|37|TFG_CODTWO|C|6|0|Cod. Facilit|Codigo do Facilitador
--- ### TFH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFH|01|TFH_FILIAL|C|6|0|Filial|Filial do Sistema
TFH|02|TFH_COD|C|6|0|Código|Código do Mater. Consumo
TFH|03|TFH_LOCAL|C|8|0|Local|Cód. Local de Atend.
TFH|04|TFH_ITEM|C|2|0|Item|Número do Item do produto
TFH|05|TFH_PRODUT|C|15|0|Produto|Código do Produto
TFH|06|TFH_DESCRI|C|70|0|Descrição|Descrição Produto
TFH|07|TFH_UM|C|2|0|Unidade|Unidade de Medida
TFH|08|TFH_QTDVEN|N|11|2|Quantidade|Quantidade de Venda
TFH|09|TFH_PRCVEN|N|14|2|Vlr. Venda|Valor Unitário Venda
TFH|10|TFH_PERINI|D|8|0|Per. Inicio|Período Inicial Aloc
TFH|11|TFH_PERFIM|D|8|0|Per. Final|Período Final Aloc.
TFH|12|TFH_TOTAL|N|14|2|SubTotal|Valor Unitario na Tabela
TFH|13|TFH_DESCON|N|5|2|%Desconto|Percentual de Desconto
TFH|14|TFH_VALDES|N|14|2|Vlr.Desconto|Valor do Desconto
TFH|15|TFH_TES|C|3|0|TES Estoque|TES Controle Estoque
TFH|16|TFH_CODPAI|C|6|0|Codigo Pai|Codigo Tabela Pai
TFH|17|TFH_SLD|N|11|2|Saldo|Saldo do Item
TFH|18|TFH_CODSUB|C|6|0|Cod. Subst|Código Subst
TFH|19|TFH_TOTGER|N|14|2|Vlr.Total|Valor total geral
TFH|20|TFH_LUCRO|N|5|2|%Lucro|Percentual de lucro
TFH|21|TFH_TXLUCR|N|14|2|Vlr. Lucro|Valor da taxa de lucro
TFH|22|TFH_ADM|N|5|2|%Adm|% da Taxa Administrativa
TFH|23|TFH_TXADM|N|14|2|Vlr. Tx Adm|Valor taxa administrativa
TFH|24|TFH_COBCTR|C|1|0|Cob.Contrato|Cobra Contrato?
TFH|25|TFH_VIDMES|N|3|0|Vida Útil|Vida Útil
TFH|26|TFH_DPRMES|N|14|2|Depr. Mens.|Depr. Mensal
TFH|27|TFH_CHVTWO|C|21|0|Chv Facilita|Chave do Facilitador
TFH|28|TFH_ITCNB|C|3|0|Item CNB|Item CNB
TFH|29|TFH_CONTRT|C|15|0|Contrato|Contrato
TFH|30|TFH_CONREV|C|3|0|Revisão|Revisão
TFH|31|TFH_TESPED|C|3|0|TES Pedido|TES Pedido de Venda
TFH|32|TFH_VLPRPA|N|14|2|Vlr.Prox.Par|Valor da Próxima Parcela
TFH|33|TFH_MODPLA|C|1|0|Planeja Revi|Planeja Revisão
TFH|34|TFH_CODREL|C|6|0|Cod.Relacion|Codigo Relacionado
TFH|35|TFH_CODTWO|C|6|0|Cod. Facilit|Codigo do Facilitador
--- ### TFI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFI|01|TFI_FILIAL|C|6|0|Filial|Filial do Sistema
TFI|02|TFI_COD|C|6|0|Código|Código da Locação de Eq.
TFI|03|TFI_LOCAL|C|8|0|Local|Cód. Local de Atend.
TFI|04|TFI_ITEM|C|2|0|Item|Número do Item do produto
TFI|05|TFI_PRODUT|C|15|0|Produto|Código do Produto
TFI|06|TFI_DESCRI|C|70|0|Descrição|Descrição do produto
TFI|07|TFI_UM|C|2|0|Unidade|Unidade de Medida
TFI|08|TFI_TPCOBR|C|1|0|Tp. Cobrança|Tp.Cobr. (Dias/Horimetro)
TFI|09|TFI_QTDVEN|N|11|0|Quantidade|Quantidade de venda
TFI|10|TFI_SEPSLD|N|11|0|Saldo Separ.|Saldo da Separação
TFI|11|TFI_PERINI|D|8|0|Per. Inicio|Período Inicial Aloc
TFI|12|TFI_PERFIM|D|8|0|Per. Final|Período Final Aloc.
TFI|13|TFI_HORAIN|C|5|0|Hora Inicio|Hora Inicio Alocação
TFI|14|TFI_HORAFI|C|5|0|Hora Final|Hora Final Alocação
TFI|15|TFI_TOTAL|N|14|2|Vlr.Total|Valor Unitario na Tabela
TFI|16|TFI_DESCON|N|5|2|%Desconto|Percentual de Desconto
TFI|17|TFI_VALDES|N|14|2|Vlr.Desconto|Valor do Desconto
TFI|18|TFI_TES|C|3|0|TES Remessa|TES de Remessa
TFI|19|TFI_SEPARA|C|1|0|Eq. Separado|Equipamento Separado?
TFI|20|TFI_CODPAI|C|6|0|Loc x Propos|Codigo Local x Proposta
TFI|21|TFI_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TFI|22|TFI_CONREV|C|3|0|Revisao|Sequencia da Revisao
TFI|23|TFI_RESERV|C|6|0|Cod. Reserva|Código da Reserva
TFI|24|TFI_CODSUB|C|6|0|Cod. Subst.|Codigo Subst.
TFI|25|TFI_OK|C|2|0|Ok|Mark
TFI|26|TFI_CODTGQ|C|6|0|Código Req.|Código Requisição
TFI|27|TFI_ITTGR|C|2|0|Item Req.|Item Requisição
TFI|28|TFI_CODATD|C|14|0|Atendente|Atendente
TFI|29|TFI_ENCE|C|1|0|Encerrado?|Encerrado?
TFI|30|TFI_NOMATD|C|30|0|Nome Atenden|Nome Atendente
TFI|31|TFI_ENTEQP|D|8|0|Agenda. Ent.|Agendamento da Entrega Eq
TFI|32|TFI_COLEQP|D|8|0|Coleta Equip|Coleta do Equipamento
TFI|33|TFI_APUMED|C|1|0|Tp. Apuração|Tp. Apuração da Medição
TFI|34|TFI_OSMONT|C|1|0|Exige Mont?|Exige Montagem?
TFI|35|TFI_CONENT|C|1|0|Confir. Entr|Confirma Entrega Equip.
TFI|36|TFI_CONCOL|C|1|0|Conf. Coleta|Confirma Coleta Equip.
TFI|37|TFI_CHVTWO|C|21|0|Chv Facilita|Chave do Facilitador
TFI|38|TFI_DTPFIM|D|8|0|Dt. FIm Prev|Data fim parada Prevista
TFI|39|TFI_ITCNB|C|3|0|Item CNB|Item CNB
TFI|40|TFI_CALCMD|M|10|0|Mem. de Calc|Memória de Calculo
TFI|41|TFI_SRVEXT|C|1|0|Serv. Extra?|Serviço Extra?
TFI|42|TFI_PLACOD|C|6|0|Código Plan|Codigo Planilha de Preço
TFI|43|TFI_PLAREV|C|3|0|Revisão Plan|Revisão Planilha de Preço
TFI|44|TFI_TESPED|C|3|0|TES Pedido|TES do Pedido de Venda
--- ### TFJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFJ|01|TFJ_FILIAL|C|6|0|Filial|Filial do Sistema
TFJ|02|TFJ_CODIGO|C|11|0|Codigo|Codigo do Orcamento
TFJ|03|TFJ_PROPOS|C|6|0|Num.Proposta|Num.Proposta
TFJ|04|TFJ_PREVIS|C|2|0|Rev.Proposta|Revisao da Proposta
TFJ|05|TFJ_ENTIDA|C|1|0|Tp.Entidade|Tipo da Entidade
TFJ|06|TFJ_CODENT|C|6|0|Cod.Entidade|Codigo da Entidade
TFJ|07|TFJ_LOJA|C|2|0|Lj.Entidade|Loja da Entidade
TFJ|08|TFJ_CONDPG|C|3|0|Cond.Pagto.|Condicao de Pagamento
TFJ|09|TFJ_AGRUP|C|1|0|Agrupa?|Agrupa Faturamento
TFJ|10|TFJ_DESCON|N|5|2|%Desconto|Percentual de Desconto
TFJ|11|TFJ_GRPRH|C|15|0|Grupo R.H|Grupo Recursos Humanos
TFJ|12|TFJ_DSCRH|C|70|0|Dsc.Agrup.RH|Descricao Agrupamento RH
TFJ|13|TFJ_ITEMRH|C|2|0|Item RH|Posicao do Item de RH
TFJ|14|TFJ_TES|C|3|0|TES|Tipo de Saida
TFJ|15|TFJ_GRPMI|C|15|0|Grupo M.I.|Grupo Material Implantac.
TFJ|16|TFJ_DSCMI|C|70|0|Dsc.Agrup.MI|Descricao Agrupamento MI
TFJ|17|TFJ_ITEMMI|C|2|0|Item MI|Posicao do Item MI
TFJ|18|TFJ_TESMI|C|3|0|TES|TES Mat. Imp.
TFJ|19|TFJ_GRPMC|C|15|0|Grupo M.C.|Grupo Material Consumo
TFJ|20|TFJ_DSCMC|C|70|0|Dsc.Agrup.MC|Descricao Agrupamento RH
TFJ|21|TFJ_ITEMMC|C|2|0|Item MC|Posicao Item MC
TFJ|22|TFJ_TESMC|C|3|0|TES|TES Mat. Cons.
TFJ|23|TFJ_GRPLE|C|15|0|Grupo L.E.|Grupo Locacao Equipamto.
TFJ|24|TFJ_DSCLE|C|70|0|Dsc.Agrup.LE|Descricao Agrupamento LE
TFJ|25|TFJ_ITEMLE|C|2|0|Item LE|Posicao do Item de LE
TFJ|26|TFJ_TESLE|C|3|0|TES|TES Loc. Eq.
TFJ|27|TFJ_TOTRH|N|14|2|Total RH|Total Geral RH
TFJ|28|TFJ_TOTMI|N|14|2|Total MI|Total Geral MI
TFJ|29|TFJ_TOTMC|N|14|2|Total MC|Total Geral MC
TFJ|30|TFJ_TOTLE|N|14|2|Total LE|Total Geral LE
TFJ|31|TFJ_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TFJ|32|TFJ_CONREV|C|3|0|Revisao|Sequencia da Revisao
TFJ|33|TFJ_STATUS|C|1|0|Status|Status do item
TFJ|34|TFJ_LUCRO|N|5|2|%Lucro|Percentual de lucro
TFJ|35|TFJ_ADM|N|5|2|%Adm|% da Taxa Administrativa
TFJ|36|TFJ_CODVIS|C|6|0|Vistoria|Código da Vist. Tecnica
TFJ|37|TFJ_TIPREV|C|3|0|Tp. Revisao|Tipo revisao do contrato
TFJ|38|TFJ_CODTAB|C|6|0|Tabela|Numero da tabela
TFJ|39|TFJ_TABREV|C|3|0|Revisão|Revisão da tabela
TFJ|40|TFJ_TABXML|M|10|0|XML|XML tabela precificação
TFJ|41|TFJ_GESMAT|C|1|0|Ges. Mat.|Gestão Materiais
TFJ|42|TFJ_OBSPRC|M|10|0|Observação|Observação do orçamento
TFJ|43|TFJ_TPFRET|C|1|0|Tipo Frete|Tipo Frete
TFJ|44|TFJ_SRVEXT|C|1|0|Serv. Extra?|Serviço Extra?
TFJ|45|TFJ_ORCPAI|C|11|0|Orc Serv Pai|Orc. Serviços Pai
TFJ|46|TFJ_CLIPED|C|1|0|Cli Ped Rem|Cliente do Ped.de Remessa
TFJ|47|TFJ_GRPCOM|C|8|0|Grp Comunica|Cód do Grupo Comunicação
TFJ|48|TFJ_DSGCN|C|1|0|Desg Cont|Desg Cont
TFJ|49|TFJ_ANTECI|C|1|0|Fat Antecip?|Faturamento Antecipado?
TFJ|50|TFJ_CNTREC|C|1|0|Contr. Rec.|Contrato Recorrente
TFJ|51|TFJ_RGMCX|C|1|0|Regime Caixa|Utiliza regime de caixa?
TFJ|52|TFJ_ORCSIM|C|1|0|Orc. Simp.|Orc. Simplificado
TFJ|53|TFJ_VEND|C|6|0|Vendedor|Vendedor
TFJ|54|TFJ_DATA|D|8|0|Data|Data de inclusao
TFJ|55|TFJ_DTPLRV|D|8|0|Dt.Planejada|Data da Rev. Planejada
TFJ|56|TFJ_CODREL|C|11|0|Cod.Relacion|Código relacionado
TFJ|57|TFJ_PRDRET|C|15|0|Prd. Ret|Produto Retroativo
TFJ|58|TFJ_APRVOP|C|1|0|Aprovação Op|Aprovação Operacional
TFJ|59|TFJ_USAPRO|C|6|0|Cód. Usuário|Código do Usuário
TFJ|60|TFJ_DTAPRO|D|8|0|Dt. Aprov.|Data de Aprovação
TFJ|61|TFJ_RESTEC|C|1|0|Reserva Téc.|Reserva Técnica
TFJ|62|TFJ_TOTUNI|N|14|2|Total.Unifom|Total do uniforme
TFJ|63|TFJ_TOTARM|N|14|2|Tot. Armame |Total do Armamento
TFJ|64|TFJ_GERPLA|N|14|2|Tot. Ger Pla|Total Geral da Planilha
TFJ|65|TFJ_OBSREJ|M|10|0|Obs.Rejeição|Observação da Rejeição
TFJ|66|TFJ_ANIVER|C|5|0|Dt. Aniver.|Data de Aniversário do Ct
TFJ|67|TFJ_TOTCUS|N|14|2|Tot. Custos|Total Custos
TFJ|68|TFJ_TOTGER|N|14|2|Tot. Geral|Tot. Geral
TFJ|69|TFJ_TREINA|C|1|0|Treinamento?|Orç. Reserva Treinamento
TFJ|70|TFJ_FINDME|C|1|0|Flag FindMe|Integraçao FindMe
--- ### TFK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFK|01|TFK_FILIAL|C|6|0|Filial|FIlial do Sistema
TFK|02|TFK_CODIGO|C|6|0|Código Log.|Código Log.
TFK|03|TFK_CODEVE|C|6|0|Cod. Event|Código Evento
TFK|04|TFK_DESEVE|C|30|0|Desc. Event|Descrição Evento
TFK|05|TFK_EXPEVE|C|40|0|Exp. Regra|Exp. Regra Evento
TFK|06|TFK_DATEML|D|8|0|Data Disparo|Data Disparo Email
TFK|07|TFK_HOREML|C|5|0|Hora Disparo|Hora Disparo Email
TFK|08|TFK_UNICO|C|100|0|Vlr.  Unico|Valor Unico
TFK|09|TFK_VALOR|C|100|0|Vlr. Encontr|Valor Encontrado
TFK|10|TFK_VLRRET|C|100|0|Vlr. Retorno|Valor do retorno
--- ### TFL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFL|01|TFL_FILIAL|C|6|0|Filial|Filial do Sistema
TFL|02|TFL_CODIGO|C|6|0|Codigo|Código Local x Prop
TFL|03|TFL_LOCAL|C|8|0|Local Atend.|Local de Atendimento
TFL|04|TFL_DESLOC|C|50|0|Desc.Local|Descricao Local Atendim.
TFL|05|TFL_DTINI|D|8|0|Vig. Inicial|Data Inicio da Vigencia
TFL|06|TFL_DTFIM|D|8|0|Vigenc.Final|Data do Final da Vigencia
TFL|07|TFL_ESTADO|C|2|0|Estado|Estado
TFL|08|TFL_MUNIC|C|60|0|Municipio|Municipio
TFL|09|TFL_TOTRH|N|14|2|Total RH|Total dos itens de RH
TFL|10|TFL_TOTMI|N|14|2|Total MI|Total dos Itens MI
TFL|11|TFL_TOTMC|N|14|2|Total MC|Total Material de Consumo
TFL|12|TFL_TOTLE|N|14|2|Total LE|Total Loc de Equipamento
TFL|13|TFL_TOTUNI|N|14|2|Tot. Uniform|Total do Uniforme
TFL|14|TFL_TOTARM|N|14|2|Tot. Armame |Total do Armamento
TFL|15|TFL_TOTAL|N|15|2|Total Local|Total Local no Orçamento
TFL|16|TFL_CODPAI|C|11|0|Orcamento|Numero do Orcamento
TFL|17|TFL_GERPLA|N|14|2|Tot. Ger. Pl|Total Geral Planilha
TFL|18|TFL_PLAN|C|6|0|Nr Planilha|Número da Planilha
TFL|19|TFL_ITPLRH|C|3|0|Nr. It. Plan|Nr Item da Planilha
TFL|20|TFL_ITPLMI|C|3|0|Nr Item Plan|Número Item da Planilha
TFL|21|TFL_ITPLMC|C|3|0|Nr. It. Plan|Número item da planilha
TFL|22|TFL_ITPLLE|C|3|0|Nr. It. Plan|Número item da Planilha
TFL|23|TFL_CODSUB|C|6|0|Cod. Subst|Código Subst
TFL|24|TFL_PEDTIT|C|1|0|Nota/Titulo?|Nota Fiscal ou Titulo?
TFL|25|TFL_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TFL|26|TFL_CONREV|C|3|0|Revisao|Sequencia da Revisao
TFL|27|TFL_MESRH|N|14|2|Mensal RH|Total Mensal do RH
TFL|28|TFL_MESMI|N|14|2|Mensal MI|Total Mensal do MI
TFL|29|TFL_MESMC|N|14|2|Mensal MC|Total Mensal do MC
TFL|30|TFL_OBS|M|10|0|Observações|Observações
TFL|31|TFL_CALCMD|M|10|0|Mem. de Calc|Memoria Calculo - Imposto
TFL|32|TFL_ENCE|C|1|0|Encerrado?|Encerrado?
TFL|33|TFL_TOTIMP|N|14|2|Tot Imposto|Total Imposto
TFL|34|TFL_ATCC|C|1|0|Atualiza CC|Atualiza Centro de Custo
TFL|35|TFL_VLPRPA|N|14|2|Vlr.Prox.Par|Valor da Próxima Parcela
TFL|36|TFL_MODPLA|C|1|0|Planeja Revi|Planeja Revisão
TFL|37|TFL_CODREL|C|6|0|Cod.Relacion|Codigo Relacionado
TFL|38|TFL_DTENCE|D|8|0|DT.Encerrado|Data do Encerramento
TFL|39|TFL_PLUCRO|N|6|2|Margem Lucro|Margem de Lucro
TFL|40|TFL_DTFIND|D|8|0|Dt. FindMe|Data da última integração
TFL|41|TFL_METRO|N|9|2|Metragem|Metragem
--- ### TFM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFM|01|TFM_FILIAL|C|6|0|Filial|Filial do Sistema
TFM|02|TFM_CODIGO|C|6|0|Código Item|Cód.Item.Log
TFM|03|TFM_CODLOG|C|6|0|Cod. Log.|Codigo do Log
TFM|04|TFM_CODDES|C|6|0|Cod. Dest.|Codigo do Destinatario
TFM|05|TFM_NOME|C|40|0|Nome Dest.|Nome Destinatario
TFM|06|TFM_EMAIL|C|50|0|Email|Email do Destinatário
TFM|07|TFM_STATUS|C|1|0|Status|Status do Envio
--- ### TFN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFN|01|TFN_FILIAL|C|6|0|Filial|Filial do Sistema
TFN|02|TFN_CODLOC|C|8|0|Cod. Local|Codigo do Local Interno
TFN|03|TFN_ITEM|C|2|0|Item|Item do Responsavél
TFN|04|TFN_CODIGO|C|14|0|Codigo|Codigo do Responsavel
TFN|05|TFN_NOME|C|30|0|Nome|Nome do Atendente
TFN|06|TFN_CODFUN|C|6|0|Funcionario|Codigo do Funcionario
--- ### TFO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFO|01|TFO_FILIAL|C|6|0|Filial|Filial do Sistema
TFO|02|TFO_CDMOV|C|6|0|Cód.Mov.|Código da Movimentação
TFO|03|TFO_ITMOV|C|1|0|Item Mov.|Item da Movimentação
TFO|04|TFO_PRODUT|C|15|0|Cod. Produto|Codigo do Produto
TFO|05|TFO_CODIGO|C|6|0|Item|Código do Item
TFO|06|TFO_DESCR|C|30|0|Descrição|Descrição do Item
TFO|07|TFO_ARMA|C|6|0|Cód. Arma|Código da Arma
TFO|08|TFO_LOTE|C|30|0|Lote Municao|Lote da Municao
TFO|09|TFO_CARGA|N|4|0|Cargas|Quantidade de Cargas
TFO|10|TFO_QTDE|N|6|0|Quantidade|Quantidade do item
TFO|11|TFO_LGUIA|C|1|0|Emite Guia|Emite Guia de Tráfego
TFO|12|TFO_NRGUIA|C|11|0|Nr. Guia|Número da Guia de Tráfego
TFO|13|TFO_LRET|C|1|0|Prev. Ret.|Tem previsão de Retorno
TFO|14|TFO_DTRET|D|8|0|Dt. Retorno|Data Prevista para o Reto
TFO|15|TFO_DATA|D|8|0|Gravacao|Data da Gravação
TFO|16|TFO_ITCOD|C|6|0|Armamento|Código do Armamento
TFO|17|TFO_DSCMUN|C|70|0|Descricao Mu|Descrição da Munição
TFO|18|TFO_CODTXQ|C|6|0|Cod.Orc.Arm|Cod.Orc.Arm
--- ### TFP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFP|01|TFP_FILIAL|C|6|0|Filial|Filial do Sistema
TFP|02|TFP_CODIGO|C|6|0|Codigo|Codigo Historico
TFP|03|TFP_ENTIDA|C|1|0|Entidade|Entidade de Alocação
TFP|04|TFP_CODINT|C|8|0|Cod. Loc. In|Codigo Local Interno
TFP|05|TFP_CODLOC|C|8|0|Cod. Loc. At|Codigo Local Atendimento
TFP|06|TFP_MOVIM|C|1|0|Movimentação|Tipo de Movimentação
TFP|07|TFP_CODMUN|C|6|0|Cod. Mun|Codigo da Munição
TFP|08|TFP_LOTE|C|30|0|Lote|Lote da Munição
TFP|09|TFP_SALDO|N|6|0|Saldo|Saldo da munição
TFP|10|TFP_STATUS|C|1|0|Status|Status da Munição
TFP|11|TFP_MANUT|C|6|0|Cod. Manut|Codigo da Manutenção
TFP|12|TFP_CODMOV|C|6|0|Cod. Mov.|Codigo da Movimentação
TFP|13|TFP_CODOCO|C|6|0|Cod. Ocorr.|Codigo da Ocorrencia
TFP|14|TFP_DTHIST|D|8|0|Dta Inclusão|Data de Inclusão
TFP|15|TFP_FREA|C|1|0|FREA|Item do FREA
TFP|16|TFP_RECDE|C|1|0|Rec. De?|Recuperada de?
TFP|17|TFP_PRODUT|C|15|0|Cód.Produto|Código do Produto
TFP|18|TFP_FILLOC|C|6|0|Filial Local|Filial Local
--- ### TFQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFQ|01|TFQ_FILIAL|C|6|0|Filial|Filial do Sistema
TFQ|02|TFQ_CODIGO|C|6|0|Codigo|Codigo da Movimentação
TFQ|03|TFQ_DMOVIM|D|8|0|Data Movim.|Data Movimentação
TFQ|04|TFQ_MOTIVO|C|1|0|Motivo|Motivo da Movimentação
TFQ|05|TFQ_STATUS|C|1|0|Status|Status da Movimentação
TFQ|06|TFQ_ENTORI|C|1|0|Entidade Ori|Entidade de Origem
TFQ|07|TFQ_ORIGEM|C|8|0|Origem|Origem da Movimentação
TFQ|08|TFQ_DSCLOC|C|50|0|Desc. Local|Descrição do Local
TFQ|09|TFQ_ENTDES|C|1|0|Ent. Destino|Entidade de Destino
TFQ|10|TFQ_DESTIN|C|8|0|Cod. Destino|Codigo do Destino
TFQ|11|TFQ_DDESTI|C|50|0|Dsc. destino|Descrição do Destino
TFQ|12|TFQ_RESTRA|C|14|0|Resp. Transp|Responsavel Transporte
TFQ|13|TFQ_DRESP|C|30|0|Nome Resp.|Nome Responsavel
TFQ|14|TFQ_JUSTIF|M|10|0|Just. Mov.|Just. Movimentação
TFQ|15|TFQ_USUAR|C|6|0|Usuario|Usuario
TFQ|16|TFQ_DATA|D|8|0|Data Inc|Data de Inclusão
TFQ|17|TFQ_HORA|C|5|0|Hora Inc|Hora de Inclusão
TFQ|18|TFQ_ENTIDA|C|1|0|Entidade|Entidade Movimentação
TFQ|19|TFQ_ULTSTA|C|1|0|Ult. Status|Ultimo Status
TFQ|20|TFQ_CDRESP|C|14|0|Responsavel|Responsavel Manutenção
TFQ|21|TFQ_TPMNT|C|1|0|Tp. Manut|Tipo de Manutenção
TFQ|22|TFQ_MOTMNT|M|10|0|Motivo Manut|Motivo da Manutenção
TFQ|23|TFQ_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TFQ|24|TFQ_ITMOV|C|1|0|Item Mov.|Item da Movimentação
TFQ|25|TFQ_ITARMA|C|6|0|Armamento|Codigo do Armamento
TFQ|26|TFQ_DITEM|C|30|0|Descrição|Descrição do Item
TFQ|27|TFQ_LOTE|C|30|0|Lote Munição|Lote da Munição
TFQ|28|TFQ_ORIMUN|C|8|0|Ori. Munição|Origem Munição
TFQ|29|TFQ_DSCMUN|C|50|0|Dsc. Munição|Descrição Local Munição
TFQ|30|TFQ_QTDMUN|N|4|0|Qtd. Mun|Quantidade de Munição
TFQ|31|TFQ_GUIA|C|1|0|Guia Trafego|Emite Guia de Trafego
TFQ|32|TFQ_NGUIA|C|11|0|Numero Guia|Numero da Guia de Trafego
TFQ|33|TFQ_PRVRET|C|1|0|Prev Retorno|Previsão de Retorno
TFQ|34|TFQ_DTRETO|D|8|0|Data Retorno|Data de Retorno
TFQ|35|TFQ_FILORI|C|6|0|Filial Orig.|Filial de Origem
TFQ|36|TFQ_FILDES|C|6|0|Filial Dest.|Filial de Destino
TFQ|37|TFQ_CODTFL|C|6|0|Cod.Local|Cod.Local
TFQ|38|TFQ_CONREV|C|3|0|Revisão|Sequência de revisão
TFQ|39|TFQ_POSTO|C|6|0|Posto|Posto
--- ### TFR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFR|01|TFR_FILIAL|C|6|0|Filial|Filial do Sistema
TFR|02|TFR_CODMOV|C|6|0|Cod. Mov.|Codigo da Movimentação
TFR|03|TFR_ITEM|C|2|0|Item|Item
TFR|04|TFR_CODTEC|C|14|0|Cod. Atend.|Codigo do Atendente
TFR|05|TFR_NOMTEC|C|30|0|Nome Atend.|Nome do Atendente
TFR|06|TFR_FUNCAO|C|30|0|Função|Função do Atendente
TFR|07|TFR_CDFUNC|C|6|0|Cod. Func.|Codigo Funcionario
TFR|08|TFR_TURNO|C|6|0|Turno|Turno de trabalho
--- ### TFS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFS|01|TFS_FILIAL|C|6|0|Filial|Filial
TFS|02|TFS_CODIGO|C|6|0|Cod. Apont.|Código do Apontamento
TFS|03|TFS_CODTFG|C|6|0|Mat. Imp|Código Mat. Implantaçao
TFS|04|TFS_PRODUT|C|15|0|Produto|Produto
TFS|05|TFS_DPROD|C|70|0|Desc. Prod.|Desc. Produto
TFS|06|TFS_QUANT|N|11|2|Quant.|Quantidade
TFS|07|TFS_CC|C|9|0|Cent. Cust.|Centro de Custo
TFS|08|TFS_LOCAL|C|2|0|Armaz.|Armazém
TFS|09|TFS_LOCALI|C|15|0|Localização|Localização
TFS|10|TFS_LOTECT|C|10|0|Lote|Lote
TFS|11|TFS_NUMLOT|C|10|0|SubLote|SubLote
TFS|12|TFS_NUMSER|C|20|0|Num. Série|Número de Série
TFS|13|TFS_TM|C|3|0|Tp. Moviment|Tipo Movimento
TFS|14|TFS_NUMMOV|C|6|0|Num. Movim.|Num. Movimentação
TFS|15|TFS_DTAPON|D|8|0|Dt. Apont.|Data Apontamento
TFS|16|TFS_ITAPUR|C|6|0|Item Apurac.|Item da Apuração
TFS|17|TFS_CODTFL|C|6|0|Orç. Serv|Num. Orçamento Serv
TFS|18|TFS_MOV|C|1|0|Movimento|Movimento
TFS|19|TFS_CODTWZ|C|6|0|Cod. TWZ|Cod. Tabela de Custo
TFS|20|TFS_CONTA|C|20|0|Conta Contáb|Conta Contábil
TFS|21|TFS_ITEM|C|9|0|Item Contáb.|Item Contábil
TFS|22|TFS_CLVL|C|9|0|Classe Valor|Classe de Valor
TFS|23|TFS_CODSA|C|6|0|Numero da SA|Numero da SA
TFS|24|TFS_FINDME|C|1|0|Integ.Findme|Reg. Integrado Findme?
--- ### TFT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFT|01|TFT_FILIAL|C|6|0|Filial|Filial
TFT|02|TFT_CODIGO|C|6|0|Cod. Apont.|Código Apontamento
TFT|03|TFT_CODTFH|C|6|0|Mat. Consumo|Material de Consumo
TFT|04|TFT_PRODUT|C|15|0|Produto|Produto
TFT|05|TFT_DPROD|C|70|0|Desc. Prod.|Desc. Produto
TFT|06|TFT_QUANT|N|11|2|Quant.|Quantidade
TFT|07|TFT_CC|C|9|0|Cent. Cust.|Centro de Custo
TFT|08|TFT_LOCAL|C|2|0|Armaz.|Armazém
TFT|09|TFT_LOCALI|C|15|0|Localização|Localização
TFT|10|TFT_LOTECT|C|10|0|Lote|Lote
TFT|11|TFT_NUMLOT|C|10|0|SubLote|SubLote
TFT|12|TFT_NUMSER|C|20|0|Num. Série|Número de Série
TFT|13|TFT_TM|C|3|0|Tp. Moviment|Tipo de Movimento
TFT|14|TFT_NUMMOV|C|6|0|Num. Movim.|Número do Movimento
TFT|15|TFT_DTAPON|D|8|0|Dt. Apont.|Data Apontamento
TFT|16|TFT_ITAPUR|C|6|0|Item Apurac.|Item de Apuração
TFT|17|TFT_CODTFL|C|6|0|Orç. Serv.|Num. Orçamento Serv
TFT|18|TFT_CODTWZ|C|6|0|Cod. Twz|Cod. Tabela de Custo
TFT|19|TFT_CONTA|C|20|0|Conta Contáb|Conta Contábil
TFT|20|TFT_ITEM|C|9|0|Item Contáb.|Item Contábil
TFT|21|TFT_CLVL|C|9|0|Classe Valor|Classe de Valor
TFT|22|TFT_CODSA|C|6|0|Numero da SA|Numero da SA
TFT|23|TFT_FINDME|C|1|0|Integ.Findme|Reg. Integrado Findme?
--- ### TFU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFU|01|TFU_FILIAL|C|6|0|Filial|Filial do Sistema
TFU|02|TFU_CODIGO|C|6|0|Cod. Config.|Codigo Hora Extra
TFU|03|TFU_CODTFF|C|6|0|Rec. Humano|Codigo Recurso Humano
TFU|04|TFU_CODABN|C|6|0|Mot. Manut.|Código Mot. Manut.
TFU|05|TFU_ABNDES|C|30|0|Desc. Motivo|Descrição do Motivo
TFU|06|TFU_VALOR|N|14|2|Vlr. Hora|Valor Hora
TFU|07|TFU_LOCAL|C|8|0|Local Atend.|Local de Atendimento
TFU|08|TFU_MODPLA|C|1|0|Planeja Revi|Planeja Revisão
TFU|09|TFU_CODREL|C|6|0|Cod.Relacion|Codigo Relacionado
--- ### TFV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFV|01|TFV_FILIAL|C|6|0|Filial|Filial do Sistema
TFV|02|TFV_CODIGO|C|6|0|Cod. Apurac.|Codigo Apuração
TFV|03|TFV_CONTRT|C|15|0|Contrato|Contrato
TFV|04|TFV_REVISA|C|3|0|Ver. Contr.|Revisão Contrato
TFV|05|TFV_DTINI|D|8|0|Dt. Inicial|Data Inicial Apuração
TFV|06|TFV_DTFIM|D|8|0|Dt. Final|Data Final Apuração
TFV|07|TFV_DTAPUR|D|8|0|Dt. Apuração|Data Apuração
TFV|08|TFV_HREXTR|C|1|0|Hora Extra|Hora Extra
TFV|09|TFV_ANTECI|C|1|0|Fat Antecip?|Faturamento Antecipado?
TFV|10|TFV_AGRUP|C|1|0|Agrupa Med.?|Medição Agrupada?
TFV|11|TFV_MEDAGI|C|1|0|Medi. Ágil?| Medição Agil?
TFV|12|TFV_TIPO|C|1|0|Tipo|Tipo da Apuração
TFV|13|TFV_TOTEXC|N|14|2|Vl.Excedente|Valor Excedente
--- ### TFW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFW|01|TFW_FILIAL|C|6|0|Filial|Filial do Sistema
TFW|02|TFW_CODIGO|C|6|0|Item Apur.|Codigo Item Apuração
TFW|03|TFW_APURAC|C|6|0|Apuração|Apuração
TFW|04|TFW_NUMMED|C|6|0|Medição|Numero Medição
TFW|05|TFW_ITMED|C|6|0|Item Med.|Item da Medição
TFW|06|TFW_CODTFL|C|6|0|Orç. Serv.|Codigo Orç. Serv.
TFW|07|TFW_HORAN|N|16|2|Hr. Normais|Horas Normais
TFW|08|TFW_VLHORN|N|16|2|Vlr Hor. Nor|Valor Hora Normal
TFW|09|TFW_HORAE|N|16|2|Hr. Extras|Horas Extras
TFW|10|TFW_VLHORE|N|16|2|Vlr Hr. Ext.|Valor Hora Extra
TFW|11|TFW_VLRMED|N|16|2|Vlr Medido|Valor Medido
TFW|12|TFW_VLREXT|N|16|2|Vlr Extra|Valor Extra
TFW|13|TFW_TOTMUL|N|16|2|Multas|Total de Multas
TFW|14|TFW_VLRAPU|N|16|2|Vlr. Apurado|Valor apurado
TFW|15|TFW_TOTBON|N|16|2|Bonificações|Total de Bonificações
TFW|16|TFW_TOTDES|N|16|2|Descontos|Total de Descontos
TFW|17|TFW_VLRCON|N|16|2|Vlr. Contr.|Valor contrato
TFW|18|TFW_CODTFF|C|6|0|Rec.Humano|Codigo Recursos humanos
TFW|19|TFW_HREXTN|N|15|2|Ext. Nâo Cob|Horas Extras Não Cobradas
TFW|20|TFW_QTDAPU|N|5|0|Qtd. Apur.|Quantidade Apurada
TFW|21|TFW_VLRCOB|N|14|2|Valor Cobrad|Valor Cobrado
--- ### TFX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFX|01|TFX_FILIAL|C|6|0|Filial|Filial do Sistema
TFX|02|TFX_CODIGO|C|6|0|Item Apur.|Codigo Item Apuração
TFX|03|TFX_APURAC|C|6|0|Apuração|Apuração
TFX|04|TFX_NUMMED|C|6|0|Medição|Numero Medição
TFX|05|TFX_ITMED|C|6|0|Item Med.|Item Medição
TFX|06|TFX_CODTFL|C|6|0|Orç. Serv.|Codigo Orç. Serv.
TFX|07|TFX_TOTMUL|N|16|2|Multas|Total de Multas
TFX|08|TFX_TOTDES|N|16|2|Descontos|Descontos
TFX|09|TFX_TOTBON|N|16|2|Bonificações|Total de Bonificações
TFX|10|TFX_VLRAPU|N|16|2|Vlr. Apurado|Valor Apurado
TFX|11|TFX_VLRCON|N|16|2|Vlr. Contr.|Valor do Contrato
TFX|12|TFX_CODTFG|C|6|0|Cod TFG|Cod TFG
TFX|13|TFX_VLRMED|N|16|2|Vlr. Medição|Valor Medição
TFX|14|TFX_CODTFF|C|6|0|Rec.Humano|Codigo Recursos humanos
--- ### TFY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFY|01|TFY_FILIAL|C|6|0|Filial|Filial do Sistema
TFY|02|TFY_CODIGO|C|6|0|Item Apur.|Codigo Item Apuração
TFY|03|TFY_APURAC|C|6|0|Apuração|Apuração
TFY|04|TFY_NUMMED|C|6|0|Medição|Numero Medição
TFY|05|TFY_ITMED|C|6|0|Item Med.|Item Medição
TFY|06|TFY_CODTFL|C|6|0|Orç. Serv.|Codigo Orç. Serv.
TFY|07|TFY_VLRAPU|N|16|2|Vlr. Apurado|Valor Apurado
TFY|08|TFY_VLRCON|N|16|2|Vlr. Contr.|Valor Contrato
TFY|09|TFY_TOTMUL|N|16|2|Multas|Total de multas
TFY|10|TFY_TOTBON|N|16|2|Bonificações|Total de Bonificações
TFY|11|TFY_TOTDES|N|16|2|Descontos|Descontos
TFY|12|TFY_CODTFH|C|6|0|Código TFH|Código TFH
TFY|13|TFY_VLRMED|N|16|2|Vlr. Medição|Valor Medição
TFY|14|TFY_CODTFF|C|6|0|Rec.Humano|Codigo Recursos humanos
--- ### TFZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFZ|01|TFZ_FILIAL|C|6|0|Filial|Filial do Sistema
TFZ|02|TFZ_CODIGO|C|6|0|Item Apur.|Codigo Item Apuração
TFZ|03|TFZ_APURAC|C|6|0|Apuração|Apuração
TFZ|04|TFZ_NUMMED|C|6|0|Medição|Numero Medição
TFZ|05|TFZ_ITMED|C|6|0|Item Med.|Item Medição
TFZ|06|TFZ_CODTFL|C|6|0|Orç. Serv.|Codigo Orç. Serv.
TFZ|07|TFZ_QTDAPU|N|11|2|Quant.Apur|Quantidade a Apurar
TFZ|08|TFZ_CODTFI|C|6|0|ProdLoc|Prod. Locação
TFZ|09|TFZ_VLRUNI|N|14|2|Val. Unit.|Valor Unitário
TFZ|10|TFZ_TOTAL|N|16|2|Total|Total
TFZ|11|TFZ_CODTEV|C|6|0|Cob. Locacao|Cobrança de Locação
TFZ|12|TFZ_MODCOB|C|1|0|Mod.Cobranca|Modo de cobrança do produ
--- ### TGQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGQ|01|TGQ_FILIAL|C|6|0|Filial|Filial
TGQ|02|TGQ_CODIGO|C|6|0|Cod. Requsiç|Código da Requisição
TGQ|03|TGQ_CODATE|C|14|0|Cod. Atenden|Código do Atendente
TGQ|04|TGQ_NOMATE|C|30|0|Nome Atenden|Nome do Atendente
TGQ|05|TGQ_SITUAC|C|1|0|Situação|Situação
TGQ|06|TGQ_OBS|M|10|0|Observação|Observação
--- ### TGR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGR|01|TGR_FILIAL|C|6|0|Filial|Filial
TGR|02|TGR_CODTGQ|C|6|0|Código Req.|Código Requisição
TGR|03|TGR_ITEM|C|2|0|Item Req.|Item Requisição
TGR|04|TGR_PRODUT|C|15|0|Prod. Req.|Produto para requisição
TGR|05|TGR_DSPROD|C|70|0|Desc. Produt|Descrição Produto
TGR|06|TGR_QUANT|N|3|0|Quantidade|Quantidade
TGR|07|TGR_DTINI|D|8|0|Data Início|Data Início
TGR|08|TGR_DTFIM|D|8|0|Data Fim|Data Fim
--- ### TGS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGS|01|TGS_FILIAL|C|6|0|Filial|Filial
TGS|02|TGS_COD|C|6|0|Código|Código
TGS|03|TGS_REGIAO|C|3|0|Região|Região
TGS|04|TGS_DESREG|C|50|0|Descrição|Descrição da Região
TGS|05|TGS_DPTO|C|9|0|Departamento|Departamento
TGS|06|TGS_DESDPT|C|30|0|Desc. Depto|Descrição do departamento
TGS|07|TGS_SUPERV|C|14|0|Cod. Superv.|Supervisor
TGS|08|TGS_NOMSUP|C|30|0|Nome Superv.|Nome do Supervisor
TGS|09|TGS_DESCRI|C|50|0|Descrt. Área|Descritivo da Área
--- ### TGT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGT|01|TGT_FILIAL|C|6|0|Filial|Filial do Sistema
TGT|02|TGT_CODIGO|C|10|0|Código|Código
TGT|03|TGT_TPITEM|C|3|0|Tp.Item|Tipo do item
TGT|04|TGT_CDITEM|C|6|0|Cod.Item|Código do Item
TGT|05|TGT_COMPET|C|7|0|Competência|Competência
TGT|06|TGT_VALOR|N|14|2|Valor|Valor
TGT|07|TGT_CODTFJ|C|11|0|Cd.Orcamento|Código do Orçamento
TGT|08|TGT_EXCEDT|C|1|0|Excedente?|Excedente?
TGT|09|TGT_CODTFV|C|6|0|Cod.Apuracao|Cod.Apuracao
TGT|10|TGT_PRDRET|C|15|0|Prod.Exceden|Produto Excedente
TGT|11|TGT_NUMPV|C|6|0|Num.PV|Número do Pedido
--- ### TGU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGU|01|TGU_FILIAL|C|6|0|Filial|Filial
TGU|02|TGU_CODTFL|C|6|0|Orc. Serv|Num. Orcamento Serviço
TGU|03|TGU_COD|C|6|0|Código|Código
TGU|04|TGU_DATA|D|8|0|Data|Data
TGU|05|TGU_PROD|C|15|0|Produto|Produto
TGU|06|TGU_DESCPR|C|70|0|Descrição|Descrição
TGU|07|TGU_QUANT|N|11|2|Quantidade|Quantidade
TGU|08|TGU_VALOR|N|14|2|Valor|Valor
TGU|09|TGU_TOTAL|N|14|2|Vlr Tot.|Valor Total
TGU|10|TGU_APURAC|C|6|0|Cod. Apurac.|Codigo apuração
TGU|11|TGU_CODTWZ|C|6|0|Cod. TWZ|Cod. Tabela de Custo
TGU|12|TGU_LOCAL|C|2|0|Aramazém|Aramazém
TGU|13|TGU_CC|C|9|0|Cent. Custo|Centro de Custo
TGU|14|TGU_CODSA|C|6|0|Número da SA|Nro Solicitaçao ao Armazé
TGU|15|TGU_CONTA|C|20|0|Conta Contáb|Conta Contábil
TGU|16|TGU_ITEM|C|9|0|Item Contábi|Item Contábil
TGU|17|TGU_CLVL|C|9|0|Classe Valor|Classe de Valor
--- ### TGV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGV|01|TGV_FILIAL|C|6|0|FILIAL|FILIAL
TGV|02|TGV_COD|C|6|0|Código|Código
TGV|03|TGV_CODTFF|C|6|0|Código RH|Código Recursos Humanos
TGV|04|TGV_CURSO|C|4|0|Cod. Curso|Código do Curso
TGV|05|TGV_DCURSO|C|30|0|Desc. Curso|Descrição do curso
--- ### TGW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGW|01|TGW_FILIAL|C|6|0|Filial|Filial do Sistema
TGW|02|TGW_COD|C|6|0|Codigo|Codigo
TGW|03|TGW_EFETDX|C|6|0|Efetivo|Codigo do Efetivo
TGW|04|TGW_DIASEM|C|1|0|Dia da Sem.|Dia da Semana
TGW|05|TGW_HORINI|N|5|2|Entrada|Hora de Entrada
TGW|06|TGW_HORFIM|N|5|2|Saida|Hora de Saida
TGW|07|TGW_STATUS|C|1|0|Status|Status
TGW|08|TGW_COBTDX|C|2|0|Cobertura|Item da cobertura
TGW|09|TGW_COBTIP|C|1|0|Tipo|Tipo da cobertura
--- ### TGX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGX|01|TGX_FILIAL|C|6|0|Filial|Filial do Sistema
TGX|02|TGX_COD|C|6|0|Codigo|Codigo
TGX|03|TGX_CODTDW|C|6|0|Escala|Escala
TGX|04|TGX_QUANT|N|3|0|Quantidade|Quantidade
TGX|05|TGX_TIPO|C|1|0|Tipo|Tipo cobertura
TGX|06|TGX_ITEM|C|2|0|Item|Item da cobertura
--- ### TGY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGY|01|TGY_FILIAL|C|6|0|Filial|Filial do Sistema
TGY|02|TGY_ESCALA|C|6|0|Cod. Escala|Codigo da Escala
TGY|03|TGY_CODTDX|C|6|0|Conf. Escala|Codigo configuracao escal
TGY|04|TGY_ITEM|C|2|0|Item|Item do relacionamento
TGY|05|TGY_ATEND|C|14|0|Cod. Atend|Codigo Atendente
TGY|06|TGY_NOME|C|30|0|Nome Atend.|Nome do Atendente
TGY|07|TGY_TURNO|C|3|0|Turno|Turno do Atendente
TGY|08|TGY_DESC|C|50|0|Descricao|Descricao do Turno
TGY|09|TGY_SEQ|C|2|0|Seq. Ini tur|Sequencia do Turno
TGY|10|TGY_DTINI|D|8|0|Data Inicial|Data Inicial
TGY|11|TGY_DTFIM|D|8|0|Data Final|Data Final
TGY|12|TGY_GRUPO|N|3|0|Grupo|Grupo
TGY|13|TGY_CODTFF|C|6|0|Codigo RH|Codigo recursos humanos
TGY|14|TGY_ULTALO|D|8|0|Ult.Alocacao|Data da ultima Alocacao
TGY|15|TGY_TIPALO|C|3|0|Tp. Movim.|Tipo Movimentacao
TGY|16|TGY_DESMOV|C|15|0|Desc.Mov.|Descrição da movimentação
TGY|17|TGY_ENTRA1|C|5|0|Hora Ini 1|Horario de Entrada 1
TGY|18|TGY_SAIDA1|C|5|0|Hora Fim 1|Horario de Saida 1
TGY|19|TGY_ENTRA2|C|5|0|Hora Ini 2|Horario de Entrada 2
TGY|20|TGY_SAIDA2|C|5|0|Hora Fim 2|Horario de Saida 2
TGY|21|TGY_ENTRA3|C|5|0|Hora Ini 3|Horario de Entrada 3
TGY|22|TGY_SAIDA3|C|5|0|Hora Fim 3|Horario de Saida 3
TGY|23|TGY_ENTRA4|C|5|0|Hora Ini 4|Horario de Entrada 4
TGY|24|TGY_SAIDA4|C|5|0|Hora Fim 4|Horario de Saida 4
TGY|25|TGY_PROXFE|C|1|0|Trab.Prx.Fer|Trabalha Próximo Feriado
TGY|26|TGY_RESTEC|C|1|0|Alocacao Res|Alocaçao de Reserva ?
--- ### TGZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGZ|01|TGZ_FILIAL|C|6|0|Filial|Filial do Sistema
TGZ|02|TGZ_ESCALA|C|6|0|Cod. Escala|Codigo da Escala
TGZ|03|TGZ_CODTDX|C|6|0|Conf. Escala|Configuracao Escala
TGZ|04|TGZ_ITEM|C|2|0|Item|Item
TGZ|05|TGZ_ATEND|C|14|0|Cod. Atend.|Codigo do Atendente
TGZ|06|TGZ_NOME|C|30|0|Nome Atend.|Nome do Atendente
TGZ|07|TGZ_TURNO|C|3|0|Turno|Turno do Atendente
TGZ|08|TGZ_DESC|C|50|0|Descricao|Descricao do Turno
TGZ|09|TGZ_SEQ|C|2|0|Seq Ini Tur|Sequencia Inicial Turno
TGZ|10|TGZ_DTINI|D|8|0|Data Inicial|Data Inicial
TGZ|11|TGZ_DTFIM|D|8|0|Data Final|Data Final
TGZ|12|TGZ_GRUPO|N|3|0|Grupo|Grupo
TGZ|13|TGZ_CODTFF|C|6|0|Codigo|Codigo recursos humanos
TGZ|14|TGZ_CODTW0|C|6|0|Rota de Cob.|Rota de Cobertura
TGZ|15|TGZ_ROTA|C|60|0|Desc. Rota|Desc. Rota de Cobertura
TGZ|16|TGZ_HORINI|N|5|2|Entrada|Hora de Entrada
TGZ|17|TGZ_HORFIM|N|5|2|Saída|Hora de Saída
--- ### TIM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIM|01|TIM_FILIAL|C|6|0|Filial|Filial do Sistema
TIM|02|TIM_EVENTO|C|14|0|Tp.Evento|Tipo do Evento
TIM|03|TIM_STATUS|C|1|0|Status|Status do Check-In
TIM|04|TIM_DATA|D|8|0|Data CheckIn|Data do Check-In
TIM|05|TIM_HORA|C|5|0|Hora CheckIn|Hora do Check-In
TIM|06|TIM_CODTEC|C|14|0|Cod.Registro|Cod.Registro Funcionario
TIM|07|TIM_LOCAL|C|8|0|Local|Local de Atendimento
TIM|08|TIM_MOTIVO|C|6|0|Motivo|Mot.Divergencia Check-In
TIM|09|TIM_DESMOT|C|30|0|Descricao|Descricao Motivo
TIM|10|TIM_GPS|C|30|0|Gps|GPS Coletado Check-In
TIM|11|TIM_CODABB|C|12|0|Cod.ABB|Código ABB
--- ### TIN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIN|01|TIN_FILIAL|C|6|0|Filial|Filial do Sistema
TIN|02|TIN_GRUPO|C|3|0|Grupo/Perfil|Grupo/Perfil
TIN|03|TIN_NOME|C|30|0|Nome Grupo|Nome do grupo/perfil
TIN|04|TIN_MSBLQL|C|1|0|Bloqueado?|Bloqueado?
TIN|05|TIN_ITEM|C|3|0|Item|Item do usuário
TIN|06|TIN_CODUSR|C|25|0|Usuário|Código do usuário
TIN|07|TIN_NOMUSR|C|40|0|Nome Usuário|Nome do usuário
--- ### TIO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIO|01|TIO_FILIAL|C|6|0|Filial|Filial do sistema
TIO|02|TIO_CODIGO|C|6|0|Codigo|Codigo Historico FREAR
TIO|03|TIO_CDOCOR|C|6|0|Cod. Ocor|Codigo da Ocorrencia
TIO|04|TIO_DTALT|D|8|0|Dt Altera|Data da Alteração
TIO|05|TIO_MOTIVO|M|10|0|Motivo|Motivo da Alteracao FREAR
TIO|06|TIO_FREAR|C|1|0|FREAR|Tipo FREAR
TIO|07|TIO_ARMA|C|6|0|Cod. Arma|Codigo da Arma
TIO|08|TIO_COLETE|C|6|0|Cod. Colete|Codigo do Colete
TIO|09|TIO_CODMNT|C|6|0|Cod. Manut|Codigo da Manutenção
TIO|10|TIO_CODMOV|C|6|0|Cod. Mov|Codigo da Movimentação
TIO|11|TIO_CODUSU|C|6|0|Cod. Usuario|Codigo do Usuario
--- ### TIP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIP|01|TIP_FILIAL|C|6|0|Filial|Filial do Sistema
TIP|02|TIP_COD|C|6|0|Cód. Detalhe|Código do item do detalhe
TIP|03|TIP_CODTEC|C|14|0|Atendente|Cód. do Atendente
TIP|04|TIP_CODEQU|C|20|0|Equipamento|Cod. Equipamento
TIP|05|TIP_DTINI|D|8|0|Dt Inicial|Data Inicial da Apuração
TIP|06|TIP_DTFIM|D|8|0|Data Final|Data Final da Apuração
TIP|07|TIP_QTDE|N|16|4|Qtd Apurada|Quantidade de Horas ou Di
TIP|08|TIP_QTDMED|N|16|4|Qtd Apurada|Quantidade de Dias
TIP|09|TIP_VLRAPR|N|16|4|Vlr. Apurado|Valor Apurado
TIP|10|TIP_VLRMED|N|16|4|Vlr. Medido|Valor Medido
TIP|11|TIP_ITAPUR|C|6|0|It. Apuração|Cód. Apuração
TIP|12|TIP_HEMOT|C|6|0|Motivo HE|Motivo HE
--- ### TIW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIW|01|TIW_FILIAL|C|6|0|Filial|Filial do Sistema
TIW|02|TIW_CODIGO|C|6|0|Código|Código do Registro
TIW|03|TIW_OCORRE|C|1|0|Ocorrencias|Existem Ocorrências?
TIW|04|TIW_NOCOR|C|6|0|Cod. Ocorr.|Código Ocorrência
TIW|05|TIW_TPOCOR|C|50|0|Tp.Ocorrenc.|Descrição Ocorrência
TIW|06|TIW_DATA|D|8|0|Data Invest.|Data da Investigação
TIW|07|TIW_HORA|C|5|0|Hora Invest.|Hora da Investigação
TIW|08|TIW_CODTEC|C|14|0|C.Atendente|Codigo do Atendente
TIW|09|TIW_NOMETE|C|50|0|Nome|Nome do Atendente
TIW|10|TIW_NLOCAL|C|8|0|Local|Local de Atendimento
TIW|11|TIW_DLOCAL|C|30|0|Descrição|Descrição do Local de Ate
TIW|12|TIW_BO|C|20|0|Numero B.O.|Número do B.O
TIW|13|TIW_DTBO|D|8|0|Data B.O.|Data Realização B.O.
TIW|14|TIW_DELEG|C|40|0|Delegacia BO|Delegacia Registro B.O.
TIW|15|TIW_REPOR|C|50|0|Responsavel|Responsavel BO
TIW|16|TIW_DESCRI|M|10|0|Descr. Fatos|Descrição dos Fatos
TIW|17|TIW_CODRES|C|14|0|Resp.Invest.|Cod. Respons. Investig
TIW|18|TIW_RESPON|C|40|0|Nome|Nome Resp. Investigacao
TIW|19|TIW_DTCONC|D|8|0|Dt.Conclusao|Data Conclusão Investig.
TIW|20|TIW_CONCLU|M|10|0|Conclusao|Conclusão Final
TIW|21|TIW_ACAO|M|10|0|Ação Corret.|Descr. da Ação Corretiva
TIW|22|TIW_FECHAR|C|1|0|Final.Invest|Finalizar Investigação
--- ### TIX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIX|01|TIX_FILIAL|C|6|0|Filial|Filial do Sistema
TIX|02|TIX_TPOCOR|C|1|0|Tp. Ocorr.|Tipo de Ocorrência
TIX|03|TIX_CODIGO|C|6|0|Código|Cód. do Motivo da Ocorrên
TIX|04|TIX_DESCRI|C|40|0|Descrição|Descrição do Motivo
--- ### TIY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIY|01|TIY_FILIAL|C|6|0|Filial|Filial do Sistema
TIY|02|TIY_CODTIW|C|6|0|Codigo|Código do Processo invest
TIY|03|TIY_ITEM|C|6|0|Item|Item do Registro
TIY|04|TIY_PARTES|C|1|0|Partes|Partes da Investigação
TIY|05|TIY_NOME|C|50|0|Nome Parte|Nome da Parte
TIY|06|TIY_DATA|D|8|0|Data Relato|Data do Relato
TIY|07|TIY_OBS|C|60|0|Observação|Observação
TIY|08|TIY_DESCRI|M|10|0|Descr.Relato|Descrição do Relato
--- ### TIZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIZ|01|TIZ_FILIAL|C|6|0|Filial|Filial do sistema
TIZ|02|TIZ_SEQ|C|6|0|Sequencia|Cod. Sequencia
TIZ|03|TIZ_CODUSR|C|6|0|Usuário|Cod. Usuário
TIZ|04|TIZ_TABELA|C|6|0|Alias|Alias
TIZ|05|TIZ_NICK|C|3|0|Id|Identificador
TIZ|06|TIZ_CAMPOS|C|50|0|Campos|Campos
TIZ|07|TIZ_VALOR|C|100|0|Conteúdo|Conteúdo
TIZ|08|TIZ_FILTRA|C|1|0|Filtra?|Filtra?
TIZ|09|TIZ_NOME|C|30|0|Nome|Nome da Consulta
--- ### TV3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV3|01|TV3_FILIAL|C|6|0|Filial|Filial do Sistema
TV3|02|TV3_CODIGO|C|6|0|Codigo|Codigo da Tabela
TV3|03|TV3_CODABB|C|12|0|Cod. ABB|Codigo da ABB
TV3|04|TV3_FILABB|C|6|0|Filial ABB|Filial da ABB
TV3|05|TV3_DTINI|D|8|0|Data Inicio|Data Inicio da ABB
TV3|06|TV3_HRCHIN|C|5|0|Hora Checkin|Hora do Checkin da ABB
TV3|07|TV3_DTFIM|D|8|0|Data Fim|Data Fim da ABB
TV3|08|TV3_HRCOUT|C|5|0|Hr Checkout|Hora de checkout da ABB
TV3|09|TV3_JUSTIF|M|10|0|Justif|Justificativa
TV3|10|TV3_CODUSR|C|6|0|Cod. Usuario|Codigo do Usuario
TV3|11|TV3_DTALT|D|8|0|Dt Alteração|Data de Alteração
TV3|12|TV3_HRALT|C|8|0|Hr Alteraçao|Hora de alteração
--- ### TV6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV6|01|TV6_FILIAL|C|6|0|Filial|FIlial do Sistema
TV6|02|TV6_CODIGO|C|6|0|Código|Código
TV6|03|TV6_NUMERO|C|6|0|Número|Numero da tabela
TV6|04|TV6_REVISA|C|3|0|Revisão|Revisão da tabela
TV6|05|TV6_DESC|C|60|0|Descrição|Descrição da tabela
TV6|06|TV6_STATUS|C|1|0|Status|Status
TV6|07|TV6_DATA|D|8|0|Data Contr.|Controle: Uso interno
TV6|08|TV6_TPAPUR|C|1|0|Tp. Apuração|Tipo de apuração
--- ### TV7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV7|01|TV7_FILIAL|C|6|0|FIlial|Filial
TV7|02|TV7_CODIGO|C|6|0|Código|Código
TV7|03|TV7_CODTAB|C|6|0|Cod. Tabela|Codigo da Tabela
TV7|04|TV7_GRUPO|C|1|0|Grupo Dados|Grupo de Dados
TV7|05|TV7_ABA|C|30|0|Aba|Aba tabela precificação
TV7|06|TV7_ORDEM|C|4|0|Ordem|Numero de ordem do campo
TV7|07|TV7_IDENT|C|15|0|Identidade|Identificação do campo
TV7|08|TV7_TITULO|C|12|0|Tit. Campo|Titulo do Campo
TV7|09|TV7_DESC|C|100|0|Descrição|Descrição do Campo
TV7|10|TV7_MODO|C|1|0|Modo|Modo Edição
TV7|11|TV7_TAM|N|3|0|Tamanho|Tamanho do Campo
TV7|12|TV7_DEC|N|2|0|Decimais|Quantidade de Decimais
TV7|13|TV7_EDICAO|C|1|0|Edição|Edição do campo
TV7|14|TV7_VALID|C|128|0|Validação|Validação do campo
TV7|15|TV7_INIT|C|128|0|Inicial.|Inicializador do campo
TV7|16|TV7_FORM|C|254|0|Formula|Formula do campo
--- ### TW0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW0|01|TW0_FILIAL|C|6|0|Filial|Filial
TW0|02|TW0_COD|C|6|0|Código|Código
TW0|03|TW0_DESC|C|60|0|Descrição|Descrição
TW0|04|TW0_ATEND|C|14|0|Atendente|Atendente
TW0|05|TW0_NOME|C|60|0|Nome|Nome
TW0|06|TW0_TIPO|C|1|0|Tipo Cobert.|Tipo de Cobertura
TW0|07|TW0_STATUS|C|1|0|Status|Status da Rota
TW0|08|TW0_VLDTEF|C|1|0|Vld.Trn.Efet|Valida Turno Efetivo
TW0|09|TW0_VAGA|C|1|0|Rota Vaga|Rota Vaga
--- ### TW1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW1|01|TW1_FILIAL|C|6|0|Filial|Filial
TW1|02|TW1_COD|C|6|0|Código|Código
TW1|03|TW1_CODTW0|C|6|0|Cd.Rota Cob.|Cód.Rota de cobertura
TW1|04|TW1_CODTFF|C|6|0|Codigo RH|Codigo recursos humanos
TW1|05|TW1_CODTGX|C|6|0|Conf. Escala|Configuração da Escala
TW1|06|TW1_GRUPO|N|3|0|Grupo|Grupo
TW1|07|TW1_HORINI|N|5|2|Entrada|Hora Entrada
TW1|08|TW1_HORFIM|N|5|2|Saída|Hora Saída
TW1|09|TW1_CODABS|C|8|0|Local|Código do Local
TW1|10|TW1_LOCAL|C|50|0|Desc.Local|Descrição do Local
TW1|11|TW1_CODTDW|C|6|0|Código da Es|Código da Escala
TW1|12|TW1_ESCALA|C|60|0|Desc.Escala|Escala
TW1|13|TW1_CODSUP|C|14|0|Supervisor|Supervisor
TW1|14|TW1_SUPERV|C|30|0|Nome Sup.|Nome Supervisor
TW1|15|TW1_TURNO|C|3|0|Turno Esc.|Turno Escala
TW1|16|TW1_SEQ|C|2|0|Sequencia|Sequencia
TW1|17|TW1_MOV|C|1|0|Movimentado?|Item movimentado
TW1|18|TW1_FILTFF|C|6|0|Filial TFF|Filial da TFF
TW1|19|TW1_ATDTGY|C|14|0|Atend. Flex|Atendente Flexível
TW1|20|TW1_CODTDX|C|6|0|Conf. Aloc.|Configuração de Alocação
TW1|21|TW1_CODHE|C|6|0|Cód. Hr. Ext|Código da Hora Extra
--- ### TW2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW2|01|TW2_FILIAL|C|6|0|Filial|Filial
TW2|02|TW2_COD|C|6|0|Código|Código
TW2|03|TW2_TIPO|C|1|0|Tipo|Tipo de Restrição
TW2|04|TW2_CODTEC|C|14|0|Atendente|Atendente
TW2|05|TW2_NOME|C|30|0|Nome|Nome Atendente
TW2|06|TW2_CLIENT|C|6|0|Cod. Cli.|Cod. Cliente
TW2|07|TW2_LOJA|C|2|0|Loja Cli.|Loja Cliente
TW2|08|TW2_NOMCLI|C|80|0|Cliente|Cliente
TW2|09|TW2_LOCAL|C|8|0|Local|Local de Atend
TW2|10|TW2_DESLOC|C|50|0|Descr. Local|Descrição Local
TW2|11|TW2_TEMPO|C|1|0|Tempo|Tempo da Restr.
TW2|12|TW2_DTINI|D|8|0|Data|Data
TW2|13|TW2_DTFIM|D|8|0|Data Final|Data Final
TW2|14|TW2_RESTRI|C|1|0|Restrição|Restrição
TW2|15|TW2_OBS|M|10|0|Observação|Observação
--- ### TW6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW6|01|TW6_FILIAL|C|6|0|Filial|Filial do Sistema
TW6|02|TW6_CODIGO|C|6|0|Código|Código
TW6|03|TW6_TPPAI|C|2|0|Tp. Registro|Tipo do registro
TW6|04|TW6_CODPAI|C|6|0|Código Pai|Código da entidade pai
TW6|05|TW6_TPDESC|C|4|0|Tipo Desc.|Tipo de Desconto
TW6|06|TW6_DESCRI|C|20|0|Descrição|Desc. Tipo de Desconto
TW6|07|TW6_VALOR|N|16|2|Valor|Valor do Desconto
TW6|08|TW6_OS|L|1|0|OS|Campo gerado por OS
--- ### TW7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW7|01|TW7_FILIAL|C|6|0|Filial|Filial do Sistema
TW7|02|TW7_CODIGO|C|6|0|Codigo|Codigo
TW7|03|TW7_TPPAI|C|2|0|Tp. Registro|Tipo do Registro
TW7|04|TW7_CODPAI|C|6|0|Codigo Pai|Codigo da entidade Pai
TW7|05|TW7_TPMOV|C|1|0|Tipo / Movto|Tipo de movimento
TW7|06|TW7_CODMOV|C|5|0|Cod.Mult/Bon|Cod. da Multa/Bonificacao
TW7|07|TW7_DESCRI|C|50|0|Descricao|Descr.Multa/Bonificacao
TW7|08|TW7_VALOR|N|16|2|Valor|Valor do Movimento
TW7|09|TW7_MODO|C|1|0|Modo|Modo do Movimento
TW7|10|TW7_FLGPED|C|1|0|Interf. Ped.|Interfere Valor do Pedido
--- ### TW8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW8|01|TW8_OK|L|1|0|OK|OK
TW8|02|TW8_FILIAL|C|6|0|Filial|Filial do Sistema
TW8|03|TW8_ORDEM|C|6|0|Ordem Serv.|Numero da Ordem Serviço
TW8|04|TW8_CODBEM|C|16|0|Bem|Código do Bem
TW8|05|TW8_PLANO|C|6|0|Plano Manut.|Numero do Plano de Manut.
TW8|06|TW8_DTMRIN|D|8|0|R. In. Man.|Data Inicio Manut. Real
TW8|07|TW8_HOMINI|C|5|0|H. Ini. Man.|Hora Inicio Manut. Real
TW8|08|TW8_DTMFIM|D|8|0|R. Fim Man.|Data Fim de Manut. Real
TW8|09|TW8_HOMFIM|C|5|0|R. Fim Man.|Hora Fim de Manut. Real
TW8|10|TW8_CODTFI|C|6|0|Código|Código da Locação de Eq.
TW8|11|TW8_NUMSER|C|20|0|Id. Unico|Ident. Unico
TW8|12|TW8_CUSTOT|N|16|2|Custo Total|Custo Total da Manutenção
--- ### TW9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TW9|01|TW9_FILIAL|C|6|0|Filial|Filial do sistema
TW9|02|TW9_CODIGO|C|6|0|Código|Código
TW9|03|TW9_STATUS|C|1|0|Situação|Situação
TW9|04|TW9_CONTRT|C|15|0|Contrato|Num. Contrato
TW9|05|TW9_LOCAL|C|8|0|Local Atend.|Cód.local de atendimento
TW9|06|TW9_DSCLOC|C|50|0|Desr.Local|Descrição loc.atendimento
TW9|07|TW9_CLIENT|C|6|0|Cliente Fat.|Cliente de faturamento
TW9|08|TW9_CLILOJ|C|2|0|Loja|Loja
TW9|09|TW9_CLINOM|C|80|0|Nome Cliente|Nome Cliente
TW9|10|TW9_AGPPED|C|1|0|Agrup.Itens?|Agrupa Itens?
TW9|11|TW9_PRODUT|C|15|0|Prod. Agrup.|Produto Agrup.
TW9|12|TW9_TES|C|3|0|TES|Tip. Ent/Sai
TW9|13|TW9_CONDPG|C|3|0|Cond. Pg|Cond. Pg
TW9|14|TW9_NATCOB|C|10|0|Nat.Pedido|Nat.Pedido
TW9|15|TW9_NUMPED|C|6|0|Num. Pedido|Num. Pedido
TW9|16|TW9_DTFINA|D|8|0|Dt. Finaliz.|Data de finalização
--- ### TWA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWA|01|TWA_FILIAL|C|6|0|Filial|Filial
TWA|02|TWA_CODIGO|C|6|0|Cód.It.Inden|Cód. Item Indeniz.
TWA|03|TWA_CODTW9|C|6|0|Cod. Inden.|Cod. Inden.
TWA|04|TWA_TPOS|C|1|0|Tipo OS|Tipo OS
TWA|05|TWA_CODAB6|C|6|0|Num. O.S.|Num. O.S.SIGATEC
TWA|06|TWA_CODAB7|C|2|0|It. OS|Item OS
TWA|07|TWA_CODSTJ|C|6|0|Num. O.S.|Num. O.S. SIGAMNT
TWA|08|TWA_CODTFI|C|6|0|It. Loc.|It. Locação
TWA|09|TWA_CODTEW|C|10|0|Movim. Loc.|Movimento de Locação
TWA|10|TWA_NUMSER|C|20|0|Equipamento|Equipamento
TWA|11|TWA_CUSTO|N|10|2|Custo|Custo OS
TWA|12|TWA_VLRCOB|N|10|2|Vlr.Cobrança|Valor cobrança
TWA|13|TWA_PRODUT|C|15|0|Produto|Produto
TWA|14|TWA_TES|C|3|0|TES|Tipo Ent/Sai
TWA|15|TWA_BLQAA3|C|1|0|Bloq. eqto?|Bloqueia equipamento?
TWA|16|TWA_OBS|M|10|0|Observação|Observação
TWA|17|TWA_ITEMPD|C|2|0|Num. Item|Numero do Item no Pedido
TWA|18|TWA_QTDSEP|N|11|0|Qtd. Separ.|Quantidade Separada.
--- ### TWB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWB|01|TWB_FILIAL|C|6|0|Filial|Filial do Sistema
TWB|02|TWB_COD|C|6|0|Codigo|Codigo
TWB|03|TWB_CODTFV|C|6|0|Cod. Apurac|Codigo Apuracao
TWB|04|TWB_CODTFL|C|6|0|Cod Loc Orc|Cod. Local Oramento
TWB|05|TWB_CODABS|C|8|0|Cod. Local|Codigo do Local
TWB|06|TWB_IMPMED|N|14|2|Vlr Imp Med|Vlr Imp Med
TWB|07|TWB_VLRRH|N|14|2|Vlr Rh|Valor Rh
TWB|08|TWB_VLRMI|N|14|2|Vlr Mat. Imp|Vlr Mat. Imp
TWB|09|TWB_VLRMC|N|14|2|Vlr Mat Cons|Vlr Mat Cons
TWB|10|TWB_VLRLE|N|14|2|Vlr Loc Equi|Vlr Loc Equi
TWB|11|TWB_VLRMUL|N|14|2|Vlr Multa|Valor de Multa do Item
TWB|12|TWB_VLRBON|N|14|2|Vlr Bonifica|Valor de Bonificacao
TWB|13|TWB_VLRDES|N|14|2|Vlr Desconto|Vlr Desconto
TWB|14|TWB_TOTMED|N|14|2|Vlr Med Loc|Vlr Med Loc
TWB|15|TWB_VLORIG|N|14|2|Vlr Imp Orig|Valor Original de Imposto
TWB|16|TWB_DESABS|C|50|0|Desc. Local|Descricao do Local
--- ### TWC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWC|01|TWC_FILIAL|C|6|0|Filial|Filial do Sistema
TWC|02|TWC_CODIGO|C|6|0|Código|Cód.Checklist da Locação
TWC|03|TWC_DESCRI|C|30|0|DscChecklist|Descrição Checklist
TWC|04|TWC_MSBLQL|C|1|0|Bloqueado?|Bloqueado?
--- ### TWD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWD|01|TWD_FILIAL|C|6|0|Filial|Filial do Sistema
TWD|02|TWD_CODTWC|C|6|0|CódChecklist|Código do Checklist
TWD|03|TWD_ITEM|C|3|0|Item|Item do Checklist
TWD|04|TWD_TIPO|C|1|0|Tipo|Tipo execução Checklist
TWD|05|TWD_DESCIT|C|40|0|Descrição|Descrição Item Checklist
TWD|06|TWD_PRINT|C|1|0|Impr.ChkLst?|Imprime no Checklist
TWD|07|TWD_COMEXE|C|20|0|Ação(Marcar)|Exec.Rot.Externa-Marcar
TWD|08|TWD_COMDES|C|20|0|Ação (Desm.)|Exec.Rot.Externa-Desmarca
--- ### TWE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWE|01|TWE_FILIAL|C|6|0|Filial|Filial do Sistema
TWE|02|TWE_CODTWC|C|6|0|Cód.Checklst|Código do Checklist
TWE|03|TWE_DESTWC|C|30|0|DscChecklist|Descrição Checklist
TWE|04|TWE_CODPRO|C|15|0|Prod.Locação|Produto Locação
TWE|05|TWE_DESPRO|C|70|0|Desc.Produto|Descrição do produto
TWE|06|TWE_CODTWE|C|6|0|Check X Prod|CheckList X Produto
--- ### TWF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWF|01|TWF_FILIAL|C|6|0|Filial|Filial do Sistema
TWF|02|TWF_CODIGO|C|8|0|ID do Item|ID do Item do Checklist
TWF|03|TWF_CODTFI|C|6|0|Cód. Locação|Código da locação
TWF|04|TWF_CODTEW|C|10|0|CódMovimenta|Codigo da movimentação
TWF|05|TWF_KITSEQ|C|10|0|Agrup. Kit|Agrupamento do Kit
TWF|06|TWF_CODTWC|C|6|0|CódChecklist|Código do Checklist
TWF|07|TWF_ITEM|C|3|0|It Checklist|Item do Checklist
TWF|08|TWF_DESCIT|C|40|0|Descr. Item|Descrição Item Checklist
TWF|09|TWF_EXEC|C|1|0|Executado?|Executado?
TWF|10|TWF_CODUSR|C|6|0|Cód usuário|Código do. usuário
TWF|11|TWF_NOMUSR|C|30|0|Nome usuário|Nome do usuário
TWF|12|TWF_DTEXEC|D|8|0|Dt Execução|Dt.execução It. Checklist
TWF|13|TWF_HREXEC|C|5|0|Hr Execução|Hora Exec. do Checklist
TWF|14|TWF_TIPTWD|C|1|0|Tipo Check|Tipo Execução Checklist
--- ### TWG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWG|01|TWG_FILIAL|C|6|0|Filial|Filial do Sistema
TWG|02|TWG_BASE|C|20|0|Cód. do Bem|Código base do Bem
TWG|03|TWG_FILORI|C|6|0|Fil Origem|Filial de origem
TWG|04|TWG_BEMORI|C|10|0|Cód.Bem Orig|Cód Bem Origem
TWG|05|TWG_ITEORI|C|4|0|Item.Bem Ori|Item Bem Origem
--- ### TWH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWH|01|TWH_FILIAL|C|6|0|Filial|Filial do Sistema
TWH|02|TWH_BASE|C|20|0|Base Atd.|Código Base Atendimento
TWH|03|TWH_FILORI|C|6|0|Fil. Ativo|Filial Original do Ativo
TWH|04|TWH_DESC|C|60|0|Descricao|Descricao da Base de Aten
TWH|05|TWH_ATVCBA|C|10|0|Cód. Ativo|Código do Ativo
TWH|06|TWH_ATVITE|C|4|0|Item Ativo|Item do Ativo
TWH|07|TWH_DESCRI|C|80|0|Descr. Sint.|Descrição Sintética
TWH|08|TWH_QUANTD|N|11|3|Quantidade|Quantidade do Bem
TWH|09|TWH_DTINVI|D|8|0|Dt Ini Vinc|Data Inicial Vínculo
TWH|10|TWH_CHAPA|C|20|0|Núm.Plaqueta|Número da Plaqueta
TWH|11|TWH_QTDATF|N|11|2|Ativo Fixo|Ativo Fixo
TWH|12|TWH_SLDLOC|N|11|2|Locado|Locado
TWH|13|TWH_SLDRES|N|11|2|Reservado|Reservado
TWH|14|TWH_SLDMAN|N|11|2|Manutenção|Manutenção
TWH|15|TWH_SLDBLQ|N|11|2|Bloqueado|Bloqueado
TWH|16|TWH_SLDDIS|N|11|2|Disponível|Disponível
--- ### TWI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWI|01|TWI_FILIAL|C|6|0|Filial|Filial do Sistema
TWI|02|TWI_IDREG|C|20|0|Id Registro|Id único de registro
TWI|03|TWI_BASE|C|20|0|Base|Base de atendimento
TWI|04|TWI_QTDSAI|N|12|2|Qtd saída|Quantidade saída
TWI|05|TWI_QTDRET|N|12|0|Qtd Retorno|Quantidade de retorno
TWI|06|TWI_CODCLI|C|6|0|Cód Cliente|Código do cliente
TWI|07|TWI_LOJA|C|2|0|Loja|Loja do cliente
TWI|08|TWI_NUMNF|C|9|0|Número NF|Número da Nota Fiscal
TWI|09|TWI_SERNF|C|3|0|Série NF|Série da Nota Fiscal
TWI|10|TWI_SDOCNF|C|3|0|Série NF|Série da Nota Fiscal
TWI|11|TWI_ITEMNF|C|2|0|Item NF|Item da Nota Fiscal
TWI|12|TWI_EXIGNF|C|1|0|Exige NF|Exige NF
TWI|13|TWI_LIBERA|C|1|0|Liberado|Liberado
TWI|14|TWI_DTRET|D|8|0|Data Ret|Data Retorno
TWI|15|TWI_DTSAI|D|8|0|Data Saída|Data Saída
TWI|16|TWI_FILNF|C|6|0|Filial NF|Filial Nota Fiscal
--- ### TWJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWJ|01|TWJ_FILIAL|C|6|0|FIlial|Filial do Sistema
TWJ|02|TWJ_CODIGO|C|8|0|Cód Grupo|Cód do Grupo Comunicação
TWJ|03|TWJ_DESCR|C|40|0|Descr.Grupo|Descr. Grupo Comunicação
--- ### TWK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWK|01|TWK_FILIAL|C|6|0|Filial|Filial do Sistema
TWK|02|TWK_CODTWJ|C|8|0|Cód Grupo|Cód do Grupo Comunicação
TWK|03|TWK_ATIVO|C|1|0|Ativo?|E-mail ativo p/a etapa?
TWK|04|TWK_CODIGO|C|6|0|Etapa Grupo|Etapa do Grupo
TWK|05|TWK_DESCR|C|60|0|Descr. Etapa|Descrição da Etapa
--- ### TWL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWL|01|TWL_FILIAL|C|6|0|Filial|Filial do Sistema
TWL|02|TWL_CODTWJ|C|8|0|Cód Grupo|Cód do Grupo Comunicação
TWL|03|TWL_CODTWK|C|6|0|Etapa Grupo|Etapa do Grupo
TWL|04|TWL_ITEM|C|2|0|Item Etapa|Item da etapa do grupo
TWL|05|TWL_USER|C|6|0|Usuário|Usuario Grupo Comunicação
TWL|06|TWL_NOMUSR|C|40|0|Nome usuário|Nome do usuário
TWL|07|TWL_EMAIL|C|150|0|E-mail|E-mail do usuário
--- ### TWM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWM|01|TWM_FILIAL|C|6|0|Filial|Filial do Sistema
TWM|02|TWM_CODIGO|C|15|0|Cód. Facilit|Código do Facilitador
TWM|03|TWM_DESCRI|C|40|0|Desc. Facili|Desc. do Facilitador
TWM|04|TWM_DTVALI|D|8|0|Dt. Validade|Data de Validade
TWM|05|TWM_PRECIF|L|1|0|Precificação|Ut. Precificação
--- ### TWN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWN|01|TWN_FILIAL|C|6|0|Filial|Filial do Sistema
TWN|02|TWN_ITEM|C|3|0|Item|Item do Facilitador
TWN|03|TWN_CODPRO|C|15|0|Cod. Produto|Código do Produto
TWN|04|TWN_DESCRI|C|70|0|Desc. Produt|Descrição do Produto
TWN|05|TWN_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TWN|06|TWN_VLUNIT|N|12|2|Vl. Unitário|Valor Unitário
TWN|07|TWN_TPITEM|C|1|0|Tipo do Item|Tipo do item usado
TWN|08|TWN_CODTWM|C|15|0|Cod. TWM|Código da TWM
TWN|09|TWN_ITEMRH|C|3|0|Item RH|Item RH
TWN|10|TWN_FUNCAO|C|5|0|Função|Código da Função
TWN|11|TWN_DESFUN|C|20|0|Descrição|Descrição da Função
TWN|12|TWN_TURNO|C|3|0|Turno|Código do Turno
TWN|13|TWN_DTURNO|C|50|0|Descrição|Descrição do Turno
TWN|14|TWN_CARGO|C|5|0|Cargo|Cargo do Recurso
TWN|15|TWN_DCARGO|C|30|0|Desc. Cargo|Descrição do Cargo
TWN|16|TWN_TES|C|3|0|Tipo Saida|Tipo de Saída
TWN|17|TWN_TESPED|C|3|0|TES Pedido|TES Pedido de Venda
--- ### TWO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWO|01|TWO_FILIAL|C|6|0|Filial|Filial do Sistema
TWO|02|TWO_ITEM|C|3|0|Item Facilit|Item do Facilitador
TWO|03|TWO_CODFAC|C|15|0|Cód. Facilit|Código do Facilitador
TWO|04|TWO_DESCRI|C|40|0|Des. Facilit|Descrição Facilitador
TWO|05|TWO_QUANT|N|4|0|Quantidade|Quantidade de Facilitador
TWO|06|TWO_CODORC|C|11|0|Codigo Orc.|Código do Orçamento
TWO|07|TWO_PROPOS|C|6|0|Cód. Propost|Código da Proposta
TWO|08|TWO_OPORTU|C|6|0|Cod. Oportun|Código da Oportunidade
TWO|09|TWO_LOCAL|C|6|0|Local Atend.|Local de Atendimento
TWO|10|TWO_CODIGO|C|6|0|Cod. Facilit|Codigo do Facilitador
TWO|11|TWO_CODRH|C|6|0|Cod. RH|Código RH
TWO|12|TWO_ITEMRH|C|2|0|Item RH|Item RH
--- ### TWP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWP|01|TWP_FILIAL|C|6|0|Filial|Filial do SIstema
TWP|02|TWP_IDREG|C|10|0|Id Registro|Id único do registro
TWP|03|TWP_NUMNF|C|9|0|Número NF|Número da Nota Fiscal
TWP|04|TWP_SERNF|C|3|0|Série NF|Série NF
TWP|05|TWP_QTDRET|N|12|0|Qtd Retorno|Quantidade de retorno
TWP|06|TWP_SDOCNF|C|3|0|Sér Doc NF|Série Doc NF
TWP|07|TWP_ITEMNF|C|4|0|Item NF|Item NF
TWP|08|TWP_OSTIPO|C|1|0|Tipo OS|Tipo OS
TWP|09|TWP_OSNUM|C|6|0|Número OS|Número OS
TWP|10|TWP_OSITEM|C|2|0|Item OS|Item OS
TWP|11|TWP_EXIGNF|C|1|0|Exige NF|Exige NF
TWP|12|TWP_DTRET|D|8|0|Data Ret|Data retorno
TWP|13|TWP_FILNF|C|6|0|Filial NF|Filial Nota Fiscal
--- ### TWR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWR|01|TWR_FILIAL|C|6|0|Filial|Filial do sistema
TWR|02|TWR_CODMOV|C|10|0|Movimento|Código Movimentação
TWR|03|TWR_DESTIN|C|1|0|Dest. Pedido|Destino Pedido
TWR|04|TWR_FILPED|C|6|0|Fil Pedido|Filial do Pedido
TWR|05|TWR_NUMPED|C|6|0|Num. Pedido|Número do Pedido
TWR|06|TWR_PEDIT|C|2|0|Item Ped.|Item do Pedido
TWR|07|TWR_ATUFIL|C|1|0|Atu. Fil.|Atualiza Fil de Locação
TWR|08|TWR_NUMSER|C|20|0|Num Serie|Numero de Serie
TWR|09|TWR_CLIENT|C|6|0|Cod Cliente|Código do Cliente
TWR|10|TWR_LOJACL|C|2|0|Loja Cliente|Loja do Cliente
TWR|11|TWR_CNPJ|C|14|0|CNPJ|CNPJ
TWR|12|TWR_NOME|C|40|0|Nome|Nome
TWR|13|TWR_CONDPG|C|3|0|Cond. Pagto|Condição Pagamento
TWR|14|TWR_PRODUT|C|15|0|Produto|Cod. Produto
TWR|15|TWR_TES|C|3|0|TES|Tipo Ent/Sai
TWR|16|TWR_CLENTR|C|6|0|Cli Entrega|Cliente de Entrega
TWR|17|TWR_LOJENT|C|2|0|Lj Entrega|Loja de Entrega
TWR|18|TWR_CNPJEN|C|14|0|CNPJ|CNPJ
TWR|19|TWR_NOMENT|C|80|0|Nome Cl Ent|Nome Cliente Entrega
TWR|20|TWR_CODTFI|C|6|0|Item Locação|Item Locação
TWR|21|TWR_SAIDOC|C|9|0|Doc. Saída|Doc. Saída
TWR|22|TWR_SAISER|C|3|0|Série Saída|Série Saída
TWR|23|TWR_SAIITE|C|3|0|Item Saída|Item Saída
TWR|24|TWR_SDOCS|C|3|0|Novo Id Saíd|Novo Id Saida
TWR|25|TWR_ENTDOC|C|9|0|Doc. Entrada|Doc. Entrada
TWR|26|TWR_ENTSER|C|3|0|Série Entrad|Série Entrada
TWR|27|TWR_ENTITE|C|3|0|Item Entrada|Item Entrada
TWR|28|TWR_SDOCE|C|3|0|Novo Id Ent|Novo Id Ent
TWR|29|TWR_QTDSAI|N|11|0|Qtd Saída|Quantidade Saida
TWR|30|TWR_QTDRET|N|11|0|Qtd Retorno|Quantidade Retorno
--- ### TWS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWS|01|TWS_FILIAL|C|6|0|Filial|Filial do sistema
TWS|02|TWS_CODIGO|C|6|0|Código|Código Prod. Loc.
TWS|03|TWS_DESCRI|C|40|0|Descrição|Descri. Agrupamento
TWS|04|TWS_FILPRD|C|6|0|Fil. Prod.|Filial do Produto
TWS|05|TWS_PRDCOD|C|15|0|Cód. Prod.|Código do Produto
TWS|06|TWS_PRDDES|C|70|0|Prod. Desc.|Descrição do Produto
--- ### TWT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWT|01|TWT_FILIAL|C|6|0|Filial|Filial do Sistema
TWT|02|TWT_CODAA3|C|20|0|Base|Cód. base de atendimento
TWT|03|TWT_ITEM|C|3|0|Nro do Item|Número do Item
TWT|04|TWT_DTMARC|D|8|0|Dt. Marcação|Dt. marcação do horimetro
TWT|05|TWT_HRMARC|C|4|0|Hr. Marcação|Hr. marcação do horimetro
TWT|06|TWT_NUMHOR|C|3|0|No.Horimetro|Número do horimetro
TWT|07|TWT_VALHOR|N|8|0|VlrHorimetro|Valor do horimetro
TWT|08|TWT_MOTIVO|C|1|0|Motivo|Motivo
TWT|09|TWT_DSCMOT|M|10|0|Descr.Motivo|Descrição do motivo
TWT|10|TWT_HMELIM|N|2|0|Horim.Limite|Limite dígitos horimetro
TWT|11|TWT_VIRADA|C|1|0|Virada?|Virada marcação horimetro
TWT|12|TWT_TPLCTO|C|1|0|TpLançamento|Tipo de lançamento
TWT|13|TWT_CODTFV|C|6|0|Cód.Apuração|Código apuração / medição
TWT|14|TWT_CODMV|C|10|0|Cód.Moviment|Cód.Movto.Equipamento
--- ### TWU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWU|01|TWU_FILIAL|C|6|0|Filial|Filial do sistema
TWU|02|TWU_CODTEW|C|10|0|Movimentação|Código Movimentação
TWU|03|TWU_BASE|C|20|0|Base|Base de Atendimento
TWU|04|TWU_DESC|C|60|0|Desc Prod|Descrição
TWU|05|TWU_SEQ|C|3|0|Sequência|Sequência
TWU|06|TWU_QTDBLQ|N|12|0|Qt.Bloqueada|Quantidade bloqueada
TWU|07|TWU_QTDLIB|N|12|0|Qtd.Liberada|Quantidade liberada
TWU|08|TWU_TIPO|C|1|0|Tipo|Tipo
TWU|09|TWU_OSTIPO|C|1|0|Tipo OS|Tipo OS
TWU|10|TWU_OSNUM|C|6|0|Número OS|Número da OS
TWU|11|TWU_OSITEM|C|2|0|Item OS|Item da OS
TWU|12|TWU_OSDTFI|D|8|0|Dt Fech OS|Data Fechamento OS
TWU|13|TWU_OBSERV|M|10|0|Obs|Observação
TWU|14|TWU_SLDDIS|N|12|2|Saldo Disp|Saldo Disponível
--- ### TWY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWY|01|TWY_FILIAL|C|6|0|Filial|Filial
TWY|02|TWY_CODPRO|C|15|0|Cod. Produto|Codigo do Produto
TWY|03|TWY_DESPRO|C|70|0|Desc.Produto|Descrição do Produto
TWY|04|TWY_ATIVO|C|1|0|Ativo|Ativo
TWY|05|TWY_ITEM|C|3|0|Item|Item
TWY|06|TWY_CODINT|C|15|0|Cod.Intercam|Codigo Intercambiaveis
TWY|07|TWY_DESINT|C|70|0|Desc.Interca|Descrição Intercambiaveis
--- ### TWZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TWZ|01|TWZ_FILIAL|C|6|0|Filial|Filial
TWZ|02|TWZ_CODORC|C|11|0|Orçamento|Código Orçamento
TWZ|03|TWZ_CODIGO|C|6|0|Código|Código
TWZ|04|TWZ_LOCAL|C|6|0|Código Local|Código Local
TWZ|05|TWZ_DESLOC|C|50|0|Desc Loc|Desc Local
TWZ|06|TWZ_TPSERV|C|1|0|Tipo serviço|Tipo serviço
TWZ|07|TWZ_ITEM|C|6|0|Item Orçamen|Item Orçamento
TWZ|08|TWZ_PRODUT|C|15|0|Produto|Produto
TWZ|09|TWZ_DESCRI|C|70|0|Desc Prod|Descrição Produto
TWZ|10|TWZ_VLCUST|N|14|2|Vlr Custo|Valor Custo
TWZ|11|TWZ_DTINC|D|8|0|Data Inc|Data Inclusão
TWZ|12|TWZ_ROTINA|C|10|0|Origem|Origem
TWZ|13|TWZ_OBSERV|M|10|0|Obs|Observação
--- ### TX2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX2|01|TX2_FILIAL|C|6|0|Filial|Filial do Sistema
TX2|02|TX2_CODIGO|C|11|0|Código|Código da Tarefa
TX2|03|TX2_DESCR|C|30|0|Descrição|Descrição da Tarefa
TX2|04|TX2_TEMPO|N|3|0|Tempo|Tempo Execução (min)
--- ### TX3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX3|01|TX3_FILIAL|C|6|0|Filial|Filial do Sistema
TX3|02|TX3_CODIGO|C|11|0|Código|Código da Atividade
TX3|03|TX3_DESCR|C|35|0|Descrição|Descrição da Atividade
TX3|04|TX3_TOTAL|N|5|0|Tempo Total|Tempo Total (em minutos)
--- ### TX4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX4|01|TX4_FILIAL|C|6|0|Filial|Filial do Sistema
TX4|02|TX4_CODPAI|C|11|0|Atividade|Código da Atividade
TX4|03|TX4_CODTAR|C|11|0|Tarefa|Código da Tarefa
TX4|04|TX4_DESCTA|C|35|0|Descr Tarefa|Descrição da Tarefa
TX4|05|TX4_ORDEM|C|2|0|Ordem|Ordem da Tarefa
TX4|06|TX4_TEMPO|N|3|0|Tempo (min)|Tempo em minutos
--- ### TX5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX5|01|TX5_FILIAL|C|6|0|Filial|Filial do Sistema
TX5|02|TX5_CODIGO|C|11|0|Código|Código
TX5|03|TX5_DESCRI|C|30|0|Descrição|Descrição
TX5|04|TX5_CONTRT|C|15|0|Contrato|Código do Contrato
TX5|05|TX5_CODTFL|C|8|0|Local|Código do Local
TX5|06|TX5_DESLOC|C|50|0|Descr. Local|Descrição do Local
TX5|07|TX5_CODTFF|C|6|0|Local|Código do Local
TX5|08|TX5_DESFUN|C|20|0|Desc. Função|Descrição da Função
TX5|09|TX5_DESPRD|C|70|0|Descr. Prod|Descrição do Produto
TX5|10|TX5_TEMPO|N|5|0|Tempo Estm|Tempo Total Estimado
--- ### TX6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX6|01|TX6_FILIAL|C|6|0|Filial|Filial do Sistema
TX6|02|TX6_CODIGO|C|11|0|Código|Código do Item
TX6|03|TX6_CODPAI|C|11|0|Planejamento|Código do Planejamento
TX6|04|TX6_CODATI|C|11|0|Atividade|Código Atividade
TX6|05|TX6_DESCAT|C|35|0|Desc Ativ.|Descrição da Atividade
TX6|06|TX6_DOMING|N|2|0|Domingo|Domingo
TX6|07|TX6_SEGUNG|N|2|0|Segunda|Segunda-Feira
TX6|08|TX6_TERCA|N|2|0|Terça|Terça-Feira
TX6|09|TX6_QUARTA|N|2|0|Quarta|Quarta-feira
TX6|10|TX6_QUINTA|N|2|0|Quinta|Quinta-Feira
TX6|11|TX6_SEXTA|N|2|0|Sexta|Sexta-Feira
TX6|12|TX6_SABADO|N|2|0|Sábado|Sábado
TX6|13|TX6_TEMPO|N|3|0|Tempo|Tempo da Atividade
--- ### TX8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TX8|01|TX8_FILIAL|C|6|0|Filial|Filial do Sistema
TX8|02|TX8_PLANIL|C|6|0|Planilha|Codigo da Planilha
TX8|03|TX8_DPLAN|C|30|0|Desc Planilh|Descricao da Planilha
TX8|04|TX8_PRODUT|C|15|0|Produto|Código do Produto
TX8|05|TX8_DESCRI|C|70|0|Desc Prod|Descrição Produto
TX8|06|TX8_FUNCAO|C|5|0|Função|Código da Função
TX8|07|TX8_DFUNC|C|20|0|Desc Função|Descrição da Função
TX8|08|TX8_TURNO|C|3|0|Turno|Código do Turno
TX8|09|TX8_DTURNO|C|50|0|Desc Turno|Descrição do Turno
TX8|10|TX8_SEQTRN|C|2|0|Seq Turno|Sequência do Turno
TX8|11|TX8_CARGO|C|5|0|Cargo|Código do Cargo
TX8|12|TX8_DCARGO|C|30|0|Desc Cargo|Descrição do Cargo
TX8|13|TX8_ESCALA|C|6|0|Escala|Código da Escala
TX8|14|TX8_NOMESC|C|60|0|Desc Escala|Descrição da Escala
TX8|15|TX8_PRIORI|N|3|0|Prioridade|Prioridade
--- ### TXB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXB|01|TXB_FILIAL|C|6|0|Filial|Filial do Sistema
TXB|02|TXB_COD|C|6|0|Código|Código
TXB|03|TXB_CODTEC|C|14|0|Atendente|Atendente
TXB|04|TXB_NOME|C|30|0|Nome|Nome do Atendente
TXB|05|TXB_TEMPO|C|1|0|Tempo|Tempo
TXB|06|TXB_DTINI|D|8|0|Data Inicial|Data Inicial
TXB|07|TXB_DTFIM|D|8|0|Data Final|Data Final
TXB|08|TXB_RESTRI|C|1|0|Restrição|Restrição
TXB|09|TXB_MOTIVO|C|2|0|Motivo|Motivo da restrição
TXB|10|TXB_DMOTIV|C|60|0|Descrição|Descrição
TXB|11|TXB_OBS|M|10|0|Observação|Observação
TXB|12|TXB_CODGYG|C|6|0|Cod. Colab.|Codigo Colaborador
--- ### TXC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXC|01|TXC_FILIAL|C|6|0|Filial|Filial do Sistema
TXC|02|TXC_CODTEC|C|14|0|Cod. Atend.|Codigo do Atendente
TXC|03|TXC_NOMTEC|C|30|0|Nome Atend.|Nome do Atendente
TXC|04|TXC_TMREQ|C|3|0|Mov. Req|Tp. Movimento Requisicao
TXC|05|TXC_ARMUNI|C|2|0|Arm. Unif|Arm. Padrao p/ Uniforme
TXC|06|TXC_TMDEV|C|3|0|Mov. Dev.|Tp Movimento Devolução
TXC|07|TXC_ARMDEV|C|2|0|Arm. Dev.|Arm. Padrao p/ Devolução
TXC|08|TXC_CCUSTO|C|9|0|C. Custo|Centro de Custo
--- ### TXD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXD|01|TXD_FILIAL|C|6|0|Filial|Filial do Sistema
TXD|02|TXD_CODTEC|C|14|0|Cod Atend.|Codigo do Atendente
TXD|03|TXD_ITEM|C|3|0|Item|Item do Uniforme
TXD|04|TXD_CODPRO|C|15|0|Cod Uniforme|Codigo do Uniforme
TXD|05|TXD_DESCR|C|70|0|Descr. Unif.|Descrição do Uniforme
TXD|06|TXD_QTDE|N|2|0|Qtde. Unif|Qtde do Item/uniforme
TXD|07|TXD_DTENTR|D|8|0|Dt. Entrega|Dt. Entrega Item/Uniforme
TXD|08|TXD_QTDVIG|N|2|0|Vigencia|Vigencia do Uniforme
TXD|09|TXD_TIPVIG|C|1|0|Tp. Vigencia|Tipo da Vigencia
TXD|10|TXD_DTVAL|D|8|0|Dt. Validade|Data de Validade
TXD|11|TXD_CONTA|C|20|0|Conta Contáb|Conta Contábil
TXD|12|TXD_DEVOL|N|2|0|Qtd. devol.|Quantidade devolução
TXD|13|TXD_ITEMCO|C|9|0|Item Contáb.|Item Contábil
TXD|14|TXD_CLVL|C|9|0|Classe Valor|Classe de Valor
TXD|15|TXD_POSTO|C|6|0|Posto Trab.|Posto de Trabalho
TXD|16|TXD_CONTRT|C|15|0|Contrato|Contrato
TXD|17|TXD_FILTFF|C|6|0|Filial|Filial
TXD|18|TXD_CODTXP|C|6|0|Cod. Uni Orc|Cod Uniforme orçamento
TXD|19|TXD_CODSA|C|6|0|Código da SA|Cód Solicitaçao Armazem
TXD|20|TXD_CPQUJE|N|12|2|Qtd Atendida|Quantidade SA atendida
TXD|21|TXD_CCUSTO|C|9|0|C. Custo|Centro de Custo
TXD|22|TXD_CCDESC|C|40|0|Descriçao CC|Descriçao CC
--- ### TXE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXE|01|TXE_FILIAL|C|6|0|Filial|Filial do Sistema
TXE|02|TXE_CODTEC|C|14|0|Cod. Atend.|Codigo do Atendente
TXE|03|TXE_ITEM|C|3|0|Item|Item do Uniforme
TXE|04|TXE_CODPRO|C|15|0|Cod Uniforme|Codigo do Uniforme
TXE|05|TXE_DESCR|C|70|0|Descr. Unif.|Descrição do Uniforme
TXE|06|TXE_QTDE|N|2|0|Qtde. Unif.|Qtde. do Item/Uniforme
TXE|07|TXE_DTGERA|D|8|0|Dt. Geração|Data de Geração
TXE|08|TXE_DTTROC|D|8|0|Dt. Devoluc.|Data de devolução/Troca
TXE|09|TXE_CONTA|C|20|0|Conta Contáb|Conta Contábil
TXE|10|TXE_ITEMCO|C|9|0|Item Contáb.|Item Contábil
TXE|11|TXE_CLVL|C|9|0|Classe Valor|Classe de Valor
--- ### TXF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXF|01|TXF_FILIAL|C|6|0|Filial|Filial do Sistema
TXF|02|TXF_CODIGO|C|6|0|Codigo|Codigo do Historico
TXF|03|TXF_CODTEC|C|14|0|Cod. Atend.|Codigo do Atendente
TXF|04|TXF_TIPO|C|1|0|Tipo Mov.|Tipo da movimentação
TXF|05|TXF_MOTIVO|M|10|0|Mot. Troca|Motivo da Troca
TXF|06|TXF_PRDANT|C|15|0|Prd Tr. Ant.|Produto de Troca antigo
TXF|07|TXF_PRDNOV|C|15|0|Prd Tr. Nova|Produto de Troca Nova
TXF|08|TXF_PRDDEV|C|15|0|Prd. Devoluc|Produto devolução
TXF|09|TXF_USR|C|6|0|Usuario|Usuario Responsavel
TXF|10|TXF_DATA|D|8|0|Data|Data da Operação
TXF|11|TXF_DEVOL|N|2|0|Qtd. devol.|Quantidade devolução
--- ### TXG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXG|01|TXG_FILIAL|C|6|0|Filial|Filial
TXG|02|TXG_CODIGO|C|6|0|Código|Código do Agrupador
TXG|03|TXG_DESCR|C|30|0|Descrição|Descrição do Agrupador
TXG|04|TXG_ITEM|C|5|0|Item|Item
TXG|05|TXG_PLANIL|C|6|0|Planilha|Código da Planilha
TXG|06|TXG_DESPLA|C|30|0|Des Planilha|Descrição Planilha
TXG|07|TXG_CELULA|C|20|0|Célula|Célula
TXG|08|TXG_MULTI|N|6|2|Multiplicado|Fator Multiplicador
--- ### TXH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXH|01|TXH_FILIAL|C|6|0|Filial|Filial do Sistema
TXH|02|TXH_CODIGO|C|8|0|Codigo|Código
TXH|03|TXH_CODPAI|C|6|0|Cod.Dia|Código do Dia
TXH|04|TXH_MANUT|C|6|0|Cod.Manut|Código da Manutenção
TXH|05|TXH_DSMANU|C|30|0|Desc.Manut|Descrição da Manutenção
TXH|06|TXH_HORAIN|C|5|0|Hor.Início|Horário Inicial
TXH|07|TXH_HORAFI|C|5|0|Hor.Fim|Horário Final
TXH|08|TXH_CODTFF|C|6|0|Cod.Posto|Código do Posto
TXH|09|TXH_DSCTFF|C|30|0|Desc.Posto|Descrição do Posto
TXH|10|TXH_CODTCU|C|3|0|Cod.Moviment|Código da Movimentação
TXH|11|TXH_DSTCU|C|15|0|Desc.Movment|Descrição da Movimentação
TXH|12|TXH_MTFIL|C|6|0|Fil. Sistema|Filial do Sistema
TXH|13|TXH_DESLOC|C|50|0|Descri Local|Descrição do Local
TXH|14|TXH_FERIAD|C|1|0|Apl. Feriad?|Aplica em feriados?
--- ### TXI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXI|01|TXI_FILIAL|C|6|0|Filial|Filial
TXI|02|TXI_CODIGO|C|6|0|Código|Codigo
TXI|03|TXI_LOCAL|C|8|0|Cód. Local|Código do Local
TXI|04|TXI_DESLOC|C|50|0|Desc. Local|Descrição do Local
TXI|05|TXI_CODTEC|C|14|0|Cód. Supervi|Código do Supervisor
TXI|06|TXI_NOMTEC|C|30|0|Desc. Superv|Descrição do Supervisor
TXI|07|TXI_FUNCAO|C|5|0|Cód. Função|Código da função
TXI|08|TXI_DFUNC|C|20|0|Desc. Função|Descrição da Função
TXI|09|TXI_TURNO|C|3|0|Cód. Turno|Código do Turno
TXI|10|TXI_DTURNO|C|50|0|Desc. Turno|Descrição do Turno
TXI|11|TXI_DTINI|D|8|0|Ini Superv|Data Inicial Supervisão
TXI|12|TXI_DTFIM|D|8|0|Fim Superv|Data Final Supervisão
TXI|13|TXI_CODAA0|C|6|0|Cod. Base Op|Codigo Base Opercional
TXI|14|TXI_DSCAA0|C|50|0|Descr. Base|Descrição da Base de Aten
TXI|15|TXI_CODTGS|C|6|0|Área Sup.|Código Área de Supervisão
TXI|16|TXI_DSCTGS|C|50|0|Dsc Area Sup|Dsc Area Sup
TXI|17|TXI_PERIOD|C|1|0|Período|Período de Supervisão
--- ### TXJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXJ|01|TXJ_FILIAL|C|6|0|Filial|Filial
TXJ|02|TXJ_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
TXJ|03|TXJ_NUM|C|9|0|No. Titulo|Numero do Titulo
TXJ|04|TXJ_PARCEL|C|3|0|Parcela|Parcela do Titulo
TXJ|05|TXJ_TIPO|C|3|0|Tipo|Tipo do titulo
TXJ|06|TXJ_FILE1|C|6|0|Filial SE1|Filial da SE1
TXJ|07|TXJ_CLIENT|C|6|0|Cliente|Código do Cliente
TXJ|08|TXJ_LOJA|C|2|0|Loja|Loja do Cliente
TXJ|09|TXJ_VENCTO|D|8|0|Vencimento|Vencimento do Titulo
TXJ|10|TXJ_VENCTR|D|8|0|Vencto real|Vencimento real do Titulo
TXJ|11|TXJ_VALOR|N|16|2|Vlr.Titulo|Valor do Titulo
TXJ|12|TXJ_CTRMNT|C|15|0|No.Contrato|No.Contrato Manutencao
TXJ|13|TXJ_FILAAH|C|6|0|Filial AAH|Filial da AAH
--- ### TXK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXK|01|TXK_FILIAL|C|6|0|Filial|Filial
TXK|02|TXK_CODTWM|C|15|0|Cod. TWM|Cod. TWM
TXK|03|TXK_ITEM|C|3|0|Item|Item do Uniforme
TXK|04|TXK_CODPRO|C|15|0|Cod Uniforme|Codigo do Uniforme
TXK|05|TXK_DESCR|C|70|0|Descrição|Descrição Uniforme
TXK|06|TXK_QTDE|N|2|0|Qtde. Unif|Qtde do Item/uniforme
TXK|07|TXK_QTDVIG|N|2|0|Vigencia|Vigencia do Uniforme
TXK|08|TXK_TIPVIG|C|1|0|Tp. Vigencia|Tipo da Vigencia
--- ### TXL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXL|01|TXL_FILIAL|C|6|0|Filial|Filial
TXL|02|TXL_ITEM|C|3|0|Item Facilit|Item do Facilitador
TXL|03|TXL_CODFAC|C|15|0|Cód. Facilit|Código do Facilitador
TXL|04|TXL_DESCRI|C|40|0|Des. Facilit|Descrição Facilitador
TXL|05|TXL_QUANT|N|4|0|Quantidade|Quantidade facilitador
TXL|06|TXL_CODTEC|C|14|0|Cod. Tec|Codigo do Técnico
--- ### TXM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXM|01|TXM_FILIAL|C|6|0|Filial|Filial do Sistema
TXM|02|TXM_NUMOS|C|6|0|Num. O.S|Numero Ordem serviço
TXM|03|TXM_ITEM|C|2|0|Item O.S|Item ordem de serviço
TXM|04|TXM_STATUS|C|1|0|Status O.S|status ordem de serviço
TXM|05|TXM_ITFOTO|C|2|0|It Foto|Item foto ordem serviço
TXM|06|TXM_FOTO|M|10|0|Foto|Foto ordem serviço
TXM|07|TXM_DESCRI|C|60|0|Descrição|Descrição
--- ### TXN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXN|01|TXN_FILIAL|C|6|0|Filial|Filial do sistema
TXN|02|TXN_CODIGO|C|6|0|Cod. Paramet|Codigo do Parametro
TXN|03|TXN_CODTCW|C|6|0|Cod. Config|Codigo da Configuracao
TXN|04|TXN_ITEM|C|3|0|Item|Item Parametro
TXN|05|TXN_DESCRI|C|30|0|Desc. Param|Descrição do Parametro
TXN|06|TXN_FORMUL|C|250|0|Formula Para|Formula Parametro
TXN|07|TXN_NICK|C|25|0|Nome Celula|Nome da Celula
TXN|08|TXN_REVISA|C|4|0|Revisão|Controle de Revisão
--- ### TXO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXO|01|TXO_FILIAL|C|6|0|Filial|Filial do Sistema
TXO|02|TXO_COD|C|6|0|Código|Cod. Config
TXO|03|TXO_CODTCW|C|6|0|Cod. Config.|Código Configuração
TXO|04|TXO_ITEM|C|2|0|Item|Item da verba adicional
TXO|05|TXO_DESCRI|C|50|0|Descriçao|Descriçao na planilha
TXO|06|TXO_BENEFI|C|6|0|Cod. Benefic|Código do Benefício
TXO|07|TXO_DSBENE|C|30|0|Desc. Benef|Descriçao do Benefício
TXO|08|TXO_VERBA|C|3|0|Verba de Pgt|Verba de Pagamento
TXO|09|TXO_DSVERB|C|30|0|Desc. Verba|Descriçao da Verba
TXO|10|TXO_TPVERB|C|1|0|Tipo Verba|Tipo da Verba
TXO|11|TXO_PORALT|N|14|2|Valor|Valor da Verba
TXO|12|TXO_NICKPO|C|25|0|Nome Valor|Nome da celula
TXO|13|TXO_NICK|C|25|0|Nome Celula|Nome da Celula Total
TXO|14|TXO_FORMUL|C|250|0|Formula|Formula parametro
TXO|15|TXO_REVISA|C|4|0|Revisão|Controle de Revisão
--- ### TXP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXP|01|TXP_FILIAL|C|6|0|Filial|Filial do Sistema
TXP|02|TXP_CODIGO|C|6|0|Codigo|Codigo
TXP|03|TXP_CODUNI|C|15|0|Cod.Uniforme|Codigo do uniforme
TXP|04|TXP_DSCUNI|C|30|0|Desc. Unifor|Descricao do Uniforme
TXP|05|TXP_QTDVEN|N|11|0|Qtd.Uniforme|Quantidade do uniforme
TXP|06|TXP_PRCVEN|N|14|2|Vlr.Uniforme|Valor do uniforme
TXP|07|TXP_TOTAL|N|14|2|Sub Total|Sub Total
TXP|08|TXP_CODTFF|C|6|0|Codigo RH|Codigo Recursos Humanos
TXP|09|TXP_CONTRT|C|15|0|Nr. Contrato|Numero do Contrato
TXP|10|TXP_CONREV|C|3|0|Seq. Revisão|Sequencia da revisão
TXP|11|TXP_CODSUB|C|6|0|Cod.Subst|Codigo substituto
TXP|12|TXP_LUCRO|N|5|2|% Lucro|Percentual de lucro
TXP|13|TXP_TXLUCR|N|14|2|Vlr.Lucro|Valor do lucro
TXP|14|TXP_ADM|N|5|2|% Adm|Percentual da tx. Adminis
TXP|15|TXP_TXADM|N|14|2|Vlr.Tx Adm|Valor taxa administrativa
TXP|16|TXP_TOTGER|N|14|2|Total geral|Total geral
TXP|17|TXP_CHVTWO|C|21|0|Chav. Facili|Chave do Faciltador
TXP|18|TXP_CODTWO|C|6|0|Cod. Facilit|Codigo do Facilitador
TXP|19|TXP_VIDMES|N|3|0|Vida Útil|Vida Útil Depreciação
TXP|20|TXP_QTDUNI|N|11|0|Qtd.Total Un|Qtd. total de uniformes
TXP|21|TXP_COBCTR|C|1|0|Cob.Contrato|Cobra Contrato ?
--- ### TXQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXQ|01|TXQ_FILIAL|C|6|0|Filial|Filial do sistema
TXQ|02|TXQ_CODIGO|C|6|0|Código|Código
TXQ|03|TXQ_ITEARM|C|1|0|Item armamen|Item do armamamento
TXQ|04|TXQ_CODPRD|C|15|0|Cod.Produto|Código do produto
TXQ|05|TXQ_DSCPRD|C|30|0|Descrição|Descrição
TXQ|06|TXQ_QTDVEN|N|11|2|Quantidade|Quantidade
TXQ|07|TXQ_PRCVEN|N|14|2|Valor|Valor
TXQ|08|TXQ_TOTAL|N|14|2|Sub.Total|Sub Total
TXQ|09|TXQ_CODTFF|C|6|0|Cod.RH|Código Recursos Humanos
TXQ|10|TXQ_CONTRT|C|15|0|Nr.Contrato|Numero do Contrato
TXQ|11|TXQ_CONREV|C|3|0|Revisão|Sequncia revisão
TXQ|12|TXQ_CODSUB|C|6|0|Cod.Substitu|Código do Substituto
TXQ|13|TXQ_LUCRO|N|5|2|%Lucro|Percentual de lucro
TXQ|14|TXQ_TXLUCR|N|14|2|Vlr.Lucro|Valor do Lucro
TXQ|15|TXQ_ADM|N|5|2|%Adm|% tx Administrativa
TXQ|16|TXQ_TXADM|N|14|2|Vlr.TxAdm|Valor taxa administrativa
TXQ|17|TXQ_TOTGER|N|14|2|Total Geral|Total Geral
TXQ|18|TXQ_CHVTWO|C|21|0|Chav. Facili|Chave do Faciltador
TXQ|19|TXQ_CODTWO|C|6|0|Cod. Facilit|Codigo do Facilitador
TXQ|20|TXQ_QTDAPO|N|6|0|Qtd.Apontada|Qtd.Apontada
TXQ|21|TXQ_VIDMES|N|3|0|Vida Útil|Vida Útil Depreciação
TXQ|22|TXQ_COBCTR|C|1|0|Cob.Contrato|Cobra Contrato ?
--- ### TXR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXR|01|TXR_FILIAL|C|6|0|Filial|Filial
TXR|02|TXR_CODIGO|C|6|0|Código|Código
TXR|03|TXR_DESC|C|30|0|Desc. Facili|Descricao Facilitador
TXR|04|TXR_CODAA0|C|6|0|Base Op.|Base Operacional
TXR|05|TXR_DSCAA0|C|30|0|Desc. Base|Desc. Base Operacional
TXR|06|TXR_TOTRH|N|14|2|Total RH|Total de Recursos Humanos
TXR|07|TXR_TOTMI|N|14|2|Total MI|Total Material de Implant
TXR|08|TXR_TOTMC|N|14|2|Total MC|Total Material de Consumo
TXR|09|TXR_TOTUNI|N|14|2|Total Unifor|Total de Uniforme
TXR|10|TXR_TOTARM|N|14|2|Total Armam.|Total de Armamento
TXR|11|TXR_TOTGER|N|14|2|Total Geral|Total Geral do Facilit.
TXR|12|TXR_GERPLA|N|14|2|Tot. Ger Pla|Total Geral da Planilha
--- ### TXS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXS|01|TXS_FILIAL|C|6|0|Filial|Filial do Sistema
TXS|02|TXS_CODIGO|C|6|0|Codigo|Codigo
TXS|03|TXS_CODTXR|C|6|0|Cod. Cabec|Codigo do Cabecalho
TXS|04|TXS_CODPRD|C|15|0|Cod. Produto|Codigo do Produto
TXS|05|TXS_DESCRI|C|70|0|Desc. Produt|Descricao do Produto
TXS|06|TXS_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TXS|07|TXS_VLUNIT|N|14|2|Vl. Unitario|Valor Unitario
TXS|08|TXS_TOTRH|N|14|2|Total de RH|Total de Recursos Humanos
TXS|09|TXS_TOTMI|N|14|2|Total MI|Total de Material de Impl
TXS|10|TXS_TOTMC|N|14|2|Total MC|Total Material de Consumo
TXS|11|TXS_TOTUNI|N|14|2|Total. Unif.|Total do Uniforme
TXS|12|TXS_TOTARM|N|14|2|Total Armam.|Total de Armamento
TXS|13|TXS_TOTGER|N|14|2|Total Geral|Total Geral
TXS|14|TXS_TOTPLA|N|14|2|Tot. Plan.|Total de Planilha
TXS|15|TXS_GERPLA|N|14|2|Tot. Ger Pla|Total Geral da Planilha
TXS|16|TXS_FUNCAO|C|5|0|Funcao|Codigo da Funcao
TXS|17|TXS_DESFUN|C|20|0|Descricao|Descricao da Funcao
TXS|18|TXS_TURNO|C|3|0|Turno|Codigo do Turno
TXS|19|TXS_DESTUR|C|50|0|Desc. Turn|Descricao do Turno
TXS|20|TXS_ESCALA|C|6|0|Cod. Escala|Codigo da Escala
TXS|21|TXS_DSCESC|C|60|0|Desc. Escala|Descricao da Escala
TXS|22|TXS_CARGO|C|5|0|Cargo|Cargo do Recurso
TXS|23|TXS_DSCCAR|C|30|0|Desc. Cargo|Descricao do Cargo
TXS|24|TXS_TES|C|3|0|Tipo Saida|Tipo de Saida
TXS|25|TXS_CALCMD|M|10|0|Mem. de Calc|Memoria de calculo
TXS|26|TXS_PLACOD|C|6|0|Cod. Planilh|Codigo Planilha de Preco
TXS|27|TXS_PLAREV|C|3|0|Revisao Plan|Revisao Planilha de Preco
TXS|28|TXS_INSALU|C|1|0|Insalub.|Insalubridade
TXS|29|TXS_GRAUIN|C|1|0|Grau Insal.|Grau de Insalubridade
TXS|30|TXS_PERICU|C|1|0|Pericul.|Periculosidade
--- ### TXT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXT|01|TXT_FILIAL|C|6|0|Filial|Filial do Sistema
TXT|02|TXT_CODIGO|C|6|0|Codigo      |Codigo
TXT|03|TXT_CODTXS|C|6|0|Cod. Posto  |Codigo do Posto
TXT|04|TXT_CODPRD|C|15|0|Cod. Produto|Codigo do Produto
TXT|05|TXT_DESCRI|C|70|0|Desc. Produt|Descricao do Produto
TXT|06|TXT_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TXT|07|TXT_VLUNIT|N|12|2|Vl. Unitario|Valor Unitario
TXT|08|TXT_TES|C|3|0|Tipo Saida  |Tipo de Saida
TXT|09|TXT_TOTMI|N|14|2|Tot. MI|Total de Material de Impl
--- ### TXU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXU|01|TXU_FILIAL|C|6|0|Filial|Filial do Sistema
TXU|02|TXU_CODIGO|C|6|0|Codigo      |Codigo
TXU|03|TXU_CODTXS|C|6|0|Cod. Posto  |Codigo do Posto
TXU|04|TXU_CODPRD|C|15|0|Cod. Produto|Codigo do Produto
TXU|05|TXU_DESCRI|C|70|0|Desc. Produt|Descricao do Produto
TXU|06|TXU_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TXU|07|TXU_VLUNIT|N|12|2|Vl. Unitario|Valor Unitario
TXU|08|TXU_TOTMC|N|14|2|Tot. MC|Total de Material de Cons
TXU|09|TXU_TES|C|3|0|Tipo Saida  |Tipo de Saida
--- ### TXV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXV|01|TXV_FILIAL|C|6|0|Filial|Filial do Sistema
TXV|02|TXV_CODIGO|C|6|0|Codigo      |Codigo
TXV|03|TXV_CODTXS|C|6|0|Cod. Posto  |Codigo do Posto
TXV|04|TXV_CODPRD|C|15|0|Cod. Produto|Codigo do Produto
TXV|05|TXV_DESCRI|C|70|0|Desc. Produt|Descricao do Produto
TXV|06|TXV_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TXV|07|TXV_VLUNIT|N|12|2|Vl. Unitario|Valor Unitario
TXV|08|TXV_TOTUNI|N|14|2|Tot. Uniform|Total de Uniforme
--- ### TXW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXW|01|TXW_FILIAL|C|6|0|Filial      |Filial do Sistema
TXW|02|TXW_CODIGO|C|6|0|Codigo      |Codigo
TXW|03|TXW_CODTXS|C|6|0|Cod. Posto  |Codigo do Posto
TXW|04|TXW_ITEARM|C|1|0|Item Armamen|Item do Armamento
TXW|05|TXW_CODPRD|C|15|0|Cod. Prod.  |Codigo do Produto
TXW|06|TXW_DESCRI|C|70|0|Desc. Produt|Descricao do Produto
TXW|07|TXW_QUANTS|N|4|0|Quant. Suger|Quantidade Sugerida
TXW|08|TXW_VLUNIT|N|12|2|Vl. Unitario|Valor Unitario
TXW|09|TXW_TOTARM|N|14|2|Tot. Armamen|Total de Armamento
--- ### TXX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TXX|01|TXX_FILIAL|C|6|0|Filial|Filial do Sistema
TXX|02|TXX_CODIGO|C|6|0|Codigo|Codigo da Tabela
TXX|03|TXX_CODTXS|C|6|0|Codigo posto|Codigo do Posto
TXX|04|TXX_BENEFI|C|6|0|Cod. Benef.|Codigo do Beneficio
TXX|05|TXX_DESCRI|C|30|0|Desc Benefi.|Descricao do Beneficio
TXX|06|TXX_VERBA|C|3|0|Verba de Pgt|Verba de Pgt do Beneficio
TXX|07|TXX_DSVERB|C|30|0|Descricao|Descricao da verba de pgt
TXX|08|TXX_TPVERB|C|1|0|Tipo Verba|Tipo da Verba
TXX|09|TXX_VALOR|N|6|2|Valor|Valor do Beneficio
TXX|10|TXX_QTDMIN|N|5|0|QtdeMin|Quantidade minima
--- ### TCY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCY|01|TCY_FILIAL|C|6|0|Filial|Filial do Sistema
TCY|02|TCY_CODOCO|C|6|0|Ocorrrência|Ocorrrência
TCY|03|TCY_CODDAN|C|6|0|Dano|Dano
TCY|04|TCY_DESCRI|C|40|0|Descrição|Descrição
--- ### TDQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDQ|01|TDQ_FILIAL|C|6|0|Filial|Filial do Sistema
TDQ|02|TDQ_CODPLA|C|6|0|Plano Emerg.|"Código do Plano Emerg."
TDQ|03|TDQ_CODEQP|C|15|0|Equipamento|Cod. do Equipamento
TDQ|04|TDQ_DESEQP|C|70|0|Descrição|Descrição do Equipamento
--- ### TG0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG0|01|TG0_FILIAL|C|6|0|Filial|Filial do Sistema
TG0|02|TG0_CODFOR|C|3|0|Fórmula|Código da Fórmula
TG0|03|TG0_DESCRI|C|40|0|Desc Formula|Descricao da Formula
TG0|04|TG0_FORMUL|M|10|0|Formula|Formula
TG0|05|TG0_QUESTI|C|6|0|Questionário|Questionário
TG0|06|TG0_TPFORM|C|1|0|Tipo Fórmula|Tipo Fórmula
--- ### TG1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG1|01|TG1_FILIAL|C|6|0|Filial|Filial do Sistema
TG1|02|TG1_CODPER|C|6|0|Perigo|Código do Perigo
TG1|03|TG1_DESCRI|C|70|0|Descrição|Descrição do Perigo
TG1|04|TG1_AGENTE|C|9|0|Agente|Agente
TG1|05|TG1_NOMAGE|C|40|0|Nome Agente|Nome do Agente de Risco
TG1|06|TG1_FONTE|C|8|0|Fonte Gerad.|Fonte Geradora
TG1|07|TG1_NOMFON|C|40|0|Nome Fonte|Nome da Fonte Geradora
TG1|08|TG1_UNIMED|C|2|0|Unid. Med.|Unidade de Medição
TG1|09|TG1_OBSERV|M|10|0|Observações|Observações do Perigo
--- ### TG2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG2|01|TG2_FILIAL|C|6|0|Filial|Filial do Sistema
TG2|02|TG2_CODAVA|C|3|0|Critério|Cód Critério de Avaliação
TG2|03|TG2_DESCRI|C|40|0|Descrição|Descrição
TG2|04|TG2_TIPO|C|1|0|Tipo Aval.|Tipo de Avalicao
TG2|05|TG2_TITULO|C|1|0|Título|Título da Avaliação
TG2|06|TG2_PESO|N|3|0|Peso|Peso
TG2|07|TG2_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### TG3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG3|01|TG3_FILIAL|C|6|0|Filial|Filial do Sistema
TG3|02|TG3_CODAVA|C|3|0|Avaliação|Código Critério Avaliação
TG3|03|TG3_CODOPC|C|3|0|Cod. Opção|Cód. Opção Critério Aval.
TG3|04|TG3_OPCAO|C|30|0|Opcao Aval.|Opcao Criterio de Aval.
TG3|05|TG3_PESO|N|3|0|Peso|Peso Escolha Criterio
TG3|06|TG3_PLANAC|C|1|0|Plano Ação?|Necessita Plano Ação?
TG3|07|TG3_PLANEM|C|1|0|Plano Emerg?|Necessita Plano Emerg.?
TG3|08|TG3_OBJETI|C|1|0|Objetivo?|Exibe Objetivo?
TG3|09|TG3_MONITO|C|1|0|Monit.?|Necessita Monitoramento?
TG3|10|TG3_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### TG4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG4|01|TG4_FILIAL|C|6|0|Filial|Filial do Sistema
TG4|02|TG4_CODCLA|C|6|0|Classe|Código da Classe
TG4|03|TG4_DESCRI|C|40|0|Desc. Classe|Descrição da Classe
TG4|04|TG4_LIMMIN|N|9|2|Peso Minimo|Peso min. p/ se enquadrar
TG4|05|TG4_LIMMAX|N|9|2|Peso Máximo|Peso Máx. p/ se enquadrar
TG4|06|TG4_PLANAC|C|1|0|Plano Ação?|Necessita Plano Ação?
TG4|07|TG4_PLANEM|C|1|0|Plano Emerg?|Necessita Plano Emerg?
TG4|08|TG4_OBJETI|C|1|0|Objetivo?|Exibe Objetivo?
TG4|09|TG4_RISCO|C|1|0|Gera Risco?|Gera um Risco?
TG4|10|TG4_MONITO|C|1|0|Monit.?|Necessita Monitoramento?
TG4|11|TG4_REAVAL|C|1|0|Reavaliação?|Necessita Reavaliação?
--- ### TG5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG5|01|TG5_FILIAL|C|6|0|Filial|Filial do Sistema
TG5|02|TG5_CODPER|C|6|0|Perigo|Código do Perigo
TG5|03|TG5_CODAVA|C|3|0|Avaliação|Código da Avaliação
TG5|04|TG5_CODOPC|C|3|0|Opção|Código da Opção
TG5|05|TG5_DTRESU|D|8|0|Data Result.|Data do Resultado
TG5|06|TG5_PESO|N|3|0|Peso|Peso
TG5|07|TG5_RESULT|N|5|0|Resultado|Resultado da Avaliacao
--- ### TG6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG6|01|TG6_FILIAL|C|6|0|Filial|Filial do Sistema
TG6|02|TG6_ORDEM|C|6|0|Ordem|N. Ordem
TG6|03|TG6_CODPER|C|6|0|Perigo|Código do Perigo
TG6|04|TG6_NOMPER|C|40|0|Nome Perigo|Nome do Perigo
TG6|05|TG6_CODDAN|C|6|0|Dano|Código do Dano
TG6|06|TG6_NOMDAN|C|40|0|Nome Dano|Nome do Dano
TG6|07|TG6_CODCLA|C|6|0|Classe|Código da Classe
TG6|08|TG6_NOMCLA|C|20|0|Nome Classe|Nome da Classe
TG6|09|TG6_CODEST|C|3|0|Estrutura|Código da Estrutura
TG6|10|TG6_CODNIV|C|6|0|Nível|Código do Nível
TG6|11|TG6_DESNIV|C|56|0|Desc. Nível|Descrição do Nível
TG6|12|TG6_DTRESU|D|8|0|Dt Resultado|Data do Resultado
TG6|13|TG6_DESCRI|M|10|0|Observação|Observação da Avaliação
TG6|14|TG6_DTFINA|D|8|0|Data Final|Data Final da Avaliação
TG6|15|TG6_SITUAC|C|1|0|Situação|Situação da Análise
TG6|16|TG6_NUMRIS|C|9|0|Núm. Risco|Número Risco
TG6|17|TG6_REVISA|C|6|0|Revisão|Revisão
--- ### TG7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG7|01|TG7_FILIAL|C|6|0|Filial|Filial do Sistema
TG7|02|TG7_CODAVA|C|3|0|Avaliação|Código Avaliação
TG7|03|TG7_NOMAVA|C|20|0|Nome Aval.|Nome Avaliação
TG7|04|TG7_CODOPC|C|3|0|Opção|Código da Opção
TG7|05|TG7_PESO|N|3|0|Peso|Peso
TG7|06|TG7_INDICA|C|1|0|Indicação|Indicação da Avaliação
TG7|07|TG7_ORDEM|C|6|0|N. Ordem|Número da Ordem
TG7|08|TG7_OK|C|1|0|Marcado?|Registro Marcado
--- ### TG8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG8|01|TG8_FILIAL|C|6|0|Filial|Filial do Sistema
TG8|02|TG8_CODDAN|C|6|0|Dano|Código do Dano
TG8|03|TG8_DESCRI|C|40|0|Descrição|Descrição do Dano
TG8|04|TG8_OBSERV|M|10|0|Observações|Observações do Dano
--- ### TG9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TG9|01|TG9_FILIAL|C|6|0|Filial|Filial do Sistema
TG9|02|TG9_CODPER|C|6|0|Perigo|Código do Perigo
TG9|03|TG9_CODEST|C|3|0|Estrutura|Código da Estrutura
TG9|04|TG9_CODNIV|C|6|0|Nível|Código do Nível
TG9|05|TG9_NIVSUP|C|6|0|Niv.Superior|Nível Superior
--- ### TGA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGA|01|TGA_FILIAL|C|6|0|Filial|Filial do Sistema
TGA|02|TGA_CODDAN|C|6|0|Dano|Código do Dano
TGA|03|TGA_CODLEG|C|12|0|Requisitos|Código da Legislação
TGA|04|TGA_EMENTA|C|80|0|Ementa|Ementa da Legislação
--- ### TGB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGB|01|TGB_FILIAL|C|6|0|Filial|Filial do Sistema
TGB|02|TGB_CODPER|C|6|0|Perigo|Código do Perigo
TGB|03|TGB_CODLEG|C|12|0|Requisitos|Código da Legislação
TGB|04|TGB_EMENTA|C|80|0|Ementa|Ementa da Legislação
--- ### TGC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGC|01|TGC_FILIAL|C|6|0|Filial|Filial do Sistema
TGC|02|TGC_ORDEM|C|6|0|Ordem|Ordem
TGC|03|TGC_CODFUN|C|5|0|Função|Código da Função
TGC|04|TGC_MAT|C|6|0|Mat. Funcion|Matricula do Funcionário
--- ### TGD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGD|01|TGD_FILIAL|C|6|0|Filial|Filial do Sistema
TGD|02|TGD_CODHIS|C|6|0|Ordem|N. Ordem
TGD|03|TGD_CODPER|C|6|0|Perigo|Código do Perigo
TGD|04|TGD_NOMPER|C|40|0|Nome Perigo|Nome do Perigo
TGD|05|TGD_CODDAN|C|6|0|Dano|Código do Dano
TGD|06|TGD_NOMDAN|C|40|0|Nome Dano|Nome do Dano
TGD|07|TGD_CODCLA|C|6|0|Classe|Código da Classe
TGD|08|TGD_NOMCLA|C|20|0|Nome Classe|Nome da Classe
TGD|09|TGD_CODEST|C|3|0|Estrutura|Código da Estrutura
TGD|10|TGD_CODNIV|C|6|0|Nível|Código do Nível
TGD|11|TGD_DESNIV|C|56|0|Desc. Nível|Descricao do Nível
TGD|12|TGD_ORDEM|C|6|0|Ordem|N. Ordem
TGD|13|TGD_DTRESU|D|8|0|Dt Resultado|Data do Resultado
TGD|14|TGD_DESCRI|M|10|0|Observação|Observação da Avaliação
TGD|15|TGD_DTFINA|D|8|0|Data Final|Data Final da Avaliação
TGD|16|TGD_SITUAC|C|1|0|Situação|Situação da Análise
TGD|17|TGD_NUMRIS|C|9|0|Núm. Risco|Número Risco
TGD|18|TGD_REAVAL|C|6|0|Ordem Reav.|N. Ordem Reavaliação
TGD|19|TGD_REVISA|C|6|0|Revisão|Revisão
--- ### TGE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGE|01|TGE_FILIAL|C|6|0|Filial|Filial do Sistema
TGE|02|TGE_CODHIS|C|6|0|Histórico|Código do histórico
TGE|03|TGE_ORDEM|C|6|0|Ordem|Ordem da Avaliação
TGE|04|TGE_CODAVA|C|3|0|Avaliação|Código da Avaliação
TGE|05|TGE_CODOPC|C|3|0|Opção|Código da Opção
TGE|06|TGE_INDICA|C|1|0|Indicação|Indicação da Avaliação
TGE|07|TGE_PESO|N|3|0|Peso %|Peso %
TGE|08|TGE_OK|C|1|0|Marcado?|Registro Marcado
--- ### TGF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGF|01|TGF_FILIAL|C|6|0|Filial|Filial do Sistema
TGF|02|TGF_ANALIS|C|6|0|Análise|Análise Preliminar
TGF|03|TGF_CODPLA|C|6|0|Plano Ação|Plano Ação
TGF|04|TGF_DESCRI|C|40|0|Descrição|Descrição do Plano
TGF|05|TGF_DTIMPL|D|8|0|Dt. Implant.|Data da Implantação
TGF|06|TGF_PRIORI|C|1|0|Priorização|Priorização
--- ### TGG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGG|01|TGG_FILIAL|C|6|0|Filial|Filial do Sistema
TGG|02|TGG_ANALIS|C|6|0|Análise|Análise Preliminar
TGG|03|TGG_CODPLA|C|6|0|Plano Emerg.|Plano Emergencial
TGG|04|TGG_DESCRI|C|40|0|Descrição|Descrição do Plano
TGG|05|TGG_RESPON|C|30|0|Responsável|Nome do Responsável
--- ### TGH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGH|01|TGH_FILIAL|C|6|0|Filial|Filial do Sistema
TGH|02|TGH_ANALIS|C|6|0|Análise|Análise Preliminar
TGH|03|TGH_CODOBJ|C|6|0|Objetivo|Objetivo
TGH|04|TGH_DESCRI|C|40|0|Descrição|Descrição do Objetivo
--- ### TGI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGI|01|TGI_FILIAL|C|6|0|Filial|Filial do Sistema
TGI|02|TGI_ANALIS|C|6|0|Análise|Análise Preliminar
TGI|03|TGI_CODMON|C|6|0|Monit.|Monitoramento
TGI|04|TGI_DESCRI|C|40|0|Descrição|Descrição do Monitorament
TGI|05|TGI_PRIORI|C|1|0|Priorização|Priorização
--- ### TGJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGJ|01|TGJ_FILIAL|C|6|0|Filial|Filial do Sistema
TGJ|02|TGJ_CODHIS|C|6|0|Ordem|N. Ordem
TGJ|03|TGJ_ANALIS|C|6|0|Análise|Análise Preliminar
TGJ|04|TGJ_CODPLA|C|6|0|Plano Ação|Plano Ação
TGJ|05|TGJ_DESCRI|C|40|0|Descrição|Descrição do Plano
TGJ|06|TGJ_DTIMPL|D|8|0|Dt. Implant.|Data da Implantação
TGJ|07|TGJ_PRIORI|C|1|0|Priorização|Priorização
--- ### TGK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGK|01|TGK_FILIAL|C|6|0|Filial|Filial do Sistema
TGK|02|TGK_CODHIS|C|6|0|Ordem|N. Ordem
TGK|03|TGK_ANALIS|C|6|0|Análise|Análise Preliminar
TGK|04|TGK_CODPLA|C|6|0|Plano Emerg.|Plano Emergencial
TGK|05|TGK_DESCRI|C|40|0|Descrição|Descrição do Plano
TGK|06|TGK_RESPON|C|30|0|Responsável|Nome do Responsável
--- ### TGL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGL|01|TGL_FILIAL|C|6|0|Filial|Filial do Sistema
TGL|02|TGL_CODHIS|C|6|0|Ordem|N. Ordem
TGL|03|TGL_ANALIS|C|6|0|Análise|Análise Preliminar
TGL|04|TGL_CODOBJ|C|6|0|Objetivo|Objetivo
TGL|05|TGL_DESCRI|C|40|0|Descrição|Descrição do Objetivo
--- ### TGM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGM|01|TGM_FILIAL|C|6|0|Filial|Filial do Sistema
TGM|02|TGM_CODHIS|C|6|0|Ordem|N. Ordem
TGM|03|TGM_ANALIS|C|6|0|Análise|Análise Preliminar
TGM|04|TGM_CODMON|C|6|0|Monitoram.|Monitoramento
TGM|05|TGM_DESCRI|C|40|0|Descrição|Descrição do Monitorament
TGM|06|TGM_PRIORI|C|1|0|Priorização|Priorização
--- ### TGN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGN|01|TGN_FILIAL|C|6|0|Filial|Filial do Sistema
TGN|02|TGN_ANALIS|C|6|0|Análise|Análise Preliminar
TGN|03|TGN_CODFOR|C|3|0|Fórmula|Código da Fórmula
TGN|04|TGN_RESULT|N|9|2|Resultado|Resultado
--- ### TGO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGO|01|TGO_FILIAL|C|6|0|Filial|Filial do Sistema
TGO|02|TGO_CODHIS|C|6|0|Ordem|N. Ordem
TGO|03|TGO_ANALIS|C|6|0|Análise|Análise Preliminar
TGO|04|TGO_CODFOR|C|3|0|Fórmula|Código da Fórmula
TGO|05|TGO_RESULT|N|9|2|Resultado|Resultado
--- ### TGP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TGP|01|TGP_FILIAL|C|6|0|Filial|Filial do Sistema
TGP|02|TGP_REVISA|C|6|0|Revisão|Revisão
TGP|03|TGP_DESCRI|C|50|0|Descrição|Descrição
--- ### TI0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI0|01|TI0_FILIAL|C|6|0|Filial|Filial do Sistema
TI0|02|TI0_PERMIS|C|6|0|Núm. Perm.|Nº Permissão de Trabalho
TI0|03|TI0_SEQPER|C|3|0|Sequência|Sequência Permissão
TI0|04|TI0_DATIMP|D|8|0|Data Imp.|Data Imp. do Relatório
TI0|05|TI0_VIAIMP|C|1|0|Via|Via de Impressão
TI0|06|TI0_DTPINI|D|8|0|Dt Prev. Ini|Data Prevista Início
TI0|07|TI0_HRPINI|C|5|0|Hr Prev. Ini|Hora Prevista Início
TI0|08|TI0_DTPFIM|D|8|0|Dt Prev. Fim|Data Prevista Fim
TI0|09|TI0_HRPFIM|C|5|0|Hr Prev. Fim|Hora Prevista Fim
TI0|10|TI0_DTRINI|D|8|0|Dt. Real Ini|Data Real Início
TI0|11|TI0_HRRINI|C|5|0|Hr. Real Ini|Hora Real Início
TI0|12|TI0_DTRFIM|D|8|0|Dt. Real Fim|Data Real Fim
TI0|13|TI0_HRRFIM|C|5|0|Hr. Real Fim|Hora Real Fim
TI0|14|TI0_DTCONC|D|8|0|Dt Conclusão|Data Conclusão
TI0|15|TI0_HRCONC|C|5|0|Hr Conclusão|Hora Conclusão
TI0|16|TI0_DINIRV|D|8|0|Dt. Rev. Ini|Data Revalidação Início
TI0|17|TI0_HINIRV|C|5|0|Hr. Rev. Ini|Hora Revalidação Início
TI0|18|TI0_DFIMRV|D|8|0|Dt. Rev. Fim|Data Revalidação Fim
TI0|19|TI0_HFIMRV|C|5|0|Hr. Rev. Fim|Hora Revalidação Fim
TI0|20|TI0_TIPVIG|C|1|0|Tipo Vigia|Tipo do Vigia
TI0|21|TI0_CODVIG|C|6|0|Cód. Vigia|Código do Vigia
TI0|22|TI0_NOMVIG|C|40|0|Nome Vigia|Nome do Vigia
TI0|23|TI0_TIPERM|C|1|0|Tp Permissão|Tipo de Permissão
TI0|24|TI0_MAOBRA|N|3|0|Mão-de-Obra|Mão-de-Obra
TI0|25|TI0_FDSFER|C|1|0|Fds/Feriado?|Final de Semana ou Feriad
TI0|26|TI0_NOMEMP|C|40|0|Nome Empresa|Nome da Empresa Emissora
TI0|27|TI0_TIPRES|C|1|0|Tipo Resp.|Tipo do Responsável
TI0|28|TI0_CODRES|C|6|0|Resp.Técnico|Cód. Responsável Técnico
TI0|29|TI0_NOMRES|C|40|0|Resp.Técnico|Nome do Resp. Técnico
TI0|30|TI0_CCUSTO|C|9|0|Centro Custo|Desc. do Centro de Custo
TI0|31|TI0_DESCC|C|40|0|Desc. C.C.|Descrição do C. de Custo
TI0|32|TI0_FUNCAO|C|5|0|Função|Função da Permissão
TI0|33|TI0_DESFUN|C|40|0|Descrição|Descrição da Função
TI0|34|TI0_CODTAR|C|6|0|Tarefa|Código da Tarefa
TI0|35|TI0_NOMTAR|C|40|0|Nome Tarefa|Nome Tarefa
TI0|36|TI0_LOCTRA|C|30|0|Local Trab.|Cód. do Local de Trabalho
TI0|37|TI0_DESLOC|C|40|0|Descrição|Desc. Local de Trabalho
TI0|38|TI0_DEPTO|C|9|0|Departamento|Código Departamento
TI0|39|TI0_DESCDP|C|30|0|Descricao|Descricao Departamento
TI0|40|TI0_TIPSUP|C|1|0|Tipo Superv.|Tipo de Supervisor
TI0|41|TI0_CODSUP|C|6|0|Supervisor|Código do Supervisor
TI0|42|TI0_NOMSUP|C|40|0|Nome Sup.|Nome Supervisor
TI0|43|TI0_TIPSUE|C|1|0|Tipo Sup. E.|Tipo Supervisor Execução
TI0|44|TI0_CODSUE|C|6|0|Sup.Execução|Cód. Supervisor Execução
TI0|45|TI0_NOMSUE|C|40|0|Nome Sup.Ex.|Nome Supervisor Execução
TI0|46|TI0_DESTRA|C|40|0|Desc. Trab.|Descrição de Trabalho
TI0|47|TI0_EQUIPE|C|10|0|Eq. Resgate|Equipe de Resgate
TI0|48|TI0_NOMEQU|C|40|0|Descrição|Descrição Equipe Resgate
TI0|49|TI0_AREARE|C|1|0|Área Rest.?|Área Restrita?
TI0|50|TI0_EPINEC|C|1|0|EPI's Nec.|EPI's Necessários?
TI0|51|TI0_RISCOS|C|1|0|Riscos Exp.|Riscos Expostos?
TI0|52|TI0_EQUIPA|C|1|0|Equipamentos|Utiliza Equipamentos?
TI0|53|TI0_OBSERV|M|10|0|Observações|Observações Gerais
TI0|54|TI0_OBSSYP|C|6|0|Observações|Observações Gerais
TI0|55|TI0_IMPRES|C|1|0|Impresso?|Indica permissão imp.
TI0|56|TI0_STATUS|C|1|0|Status|Status da Permissão
TI0|57|TI0_MEDIDA|M|10|0|Med. Prev.|Medidas Preventivas
TI0|58|TI0_MEDSYP|C|6|0|Med. Prev.|Medidas Preventivas
TI0|59|TI0_LIBERA|C|40|0|Liberação|Termos Responsabilidade
TI0|60|TI0_CARACT|C|6|0|Caract.|Codigo da Característica
TI0|61|TI0_PROCED|M|10|0|Procediment.|Procedimentos Emergência
TI0|62|TI0_PROSYP|C|6|0|Procediment.|Procedimentos Emergência
TI0|63|TI0_SEQRES|C|9|0|Seq. Resp.|Sequência da Resposta
--- ### TI1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI1|01|TI1_FILIAL|C|6|0|Filial|Filial do Sistema
TI1|02|TI1_PERMIS|C|6|0|Núm. Perm.|Nº Permissão de Trabalho
TI1|03|TI1_SEQPER|C|3|0|Sequência|Sequência Permissão
TI1|04|TI1_TIPFUN|C|1|0|Tipo Func.|Tipo do Funcionário
TI1|05|TI1_CODFUN|C|6|0|Código Func.|Código do Funcionário
TI1|06|TI1_NOMFUN|C|40|0|Executante|Nome do Executante
--- ### TI2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI2|01|TI2_FILIAL|C|6|0|Filial|Filial do Sistema.
TI2|02|TI2_PERMIS|C|6|0|Núm. Perm.|Nº Permissão de Trabalho
TI2|03|TI2_SEQPER|C|3|0|Sequência|Sequência Permissão
TI2|04|TI2_NUMRIS|C|9|0|Número Risco|Número do Risco
TI2|05|TI2_AGENTE|C|9|0|Agente|Código do Agente
TI2|06|TI2_NOMAGE|C|20|0|Nome|Nome do Agente
TI2|07|TI2_DTRECO|D|8|0|Dt.Reconhec.|Data de Reconhecimento
TI2|08|TI2_DTAVAL|D|8|0|Dt.Avaliacao|Data de Avaliação
TI2|09|TI2_QTAGEN|N|10|4|Quantidade|Quantidade do Risco
TI2|10|TI2_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
--- ### TI3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI3|01|TI3_FILIAL|C|6|0|Filial|Filial do Sistema.
TI3|02|TI3_PERMIS|C|6|0|Núm. Perm.|Nº Permissão de Trabalho
TI3|03|TI3_SEQPER|C|3|0|Sequência|Sequência Permissão
TI3|04|TI3_CODEPI|C|15|0|Código EPI|Código do EPI
TI3|05|TI3_DESEPI|C|70|0|Descrição|Descrição do EPI
TI3|06|TI3_MARCAD|C|1|0|Marcado?|Informação foi marcada?
--- ### TI4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI4|01|TI4_FILIAL|C|6|0|Filial|Filial do Sistema
TI4|02|TI4_PERMIS|C|6|0|Num. Perm.|Nº Permissão de Trabalho
TI4|03|TI4_SEQPER|C|3|0|Sequência|Sequência Permissão
TI4|04|TI4_EQUIPA|C|6|0|Equipamento|Código do Equipamento
TI4|05|TI4_DESEQU|C|40|0|Descrição|Descrição do Equipamento
TI4|06|TI4_MARCAD|C|1|0|Marcado?|Informação foi marcada?
--- ### TI5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI5|01|TI5_FILIAL|C|6|0|Filial|Filial do Sistema
TI5|02|TI5_PERMIS|C|6|0|Num. Perm.|Nº Permissão de Trabalho
TI5|03|TI5_SEQPER|C|3|0|Sequência|Sequência da Permissão
TI5|04|TI5_CODCHK|C|2|0|Opção|Cod. Opção Check-list
TI5|05|TI5_DESCHK|C|80|0|Descrição|Desc. da Opção Check-list
TI5|06|TI5_QUESTI|C|6|0|Questionário|Código do Questionário
TI5|07|TI5_TIPO|C|1|0|Tipo|Tipo
TI5|08|TI5_CODGRU|C|6|0|Código Grupo|Código do Grupo
TI5|09|TI5_MARCAD|C|1|0|Marcado?|Informação foi marcada?
TI5|10|TI5_DESCRI|C|110|0|Descrição|Descrição
TI5|11|TI5_CONTEU|C|10|0|Conteúdo|Conteúdo a ser comparado
TI5|12|TI5_QUESTA|C|4|0|Questão|Questão
TI5|13|TI5_PERGUN|C|60|0|Pergunta|Pergunta do Questionário
TI5|14|TI5_OPERAD|C|1|0|Operadores|Operadores
TI5|15|TI5_RESULT|C|8|0|Valor Resp.|Valor da Resposta
TI5|16|TI5_RESPOS|C|100|0|Editar Opc.|Editar Opções
--- ### TI6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI6|01|TI6_FILIAL|C|6|0|Filial|Filial do Sistema
TI6|02|TI6_PERMIS|C|6|0|Num. Perm.|Nº Permissão de Trabalho
TI6|03|TI6_SEQPER|C|3|0|Sequência|Sequência Permissão
TI6|04|TI6_CODCON|C|6|0|Cod. Contato|Código do Contato
TI6|05|TI6_NOMCON|C|50|0|Nome Contato|Nome do Contato
TI6|06|TI6_TELEFO|C|15|0|Telefone|Telefone do Contato
--- ### TI7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI7|01|TI7_FILIAL|C|6|0|Filial|Filial
TI7|02|TI7_CODAMB|C|30|0|Cód. Amb.|Código ambiente físico
TI7|03|TI7_PONMED|C|10|0|Pto. Medição|Ponto de medição
TI7|04|TI7_TAXOBS|N|6|2|Taxa de Dose|Taxa Dose absorvida mGy/h
TI7|05|TI7_DESPAD|N|8|3|Desvio Pad.|Desvio Padrão
--- ### TI8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI8|01|TI8_FILIAL|C|6|0|Filial|Filial
TI8|02|TI8_PLACT|C|8|0|Plano Ação|Plano de Ação
TI8|03|TI8_QUESTI|C|6|0|Questionário|Questionário
TI8|04|TI8_NOMQUE|C|40|0|Nome Quest.|Nome Quest.
--- ### TI9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TI9|01|TI9_FILIAL|C|6|0|Filial|Filial
TI9|02|TI9_LAUDO|C|12|0|Cód. Laudo|Código do Laudo
TI9|03|TI9_CODEQP|C|16|0|Cód. Equip.|Código Equip. Radioativo
TI9|04|TI9_DESEQP|C|40|0|Nome|Desc. Equip. Radioativo
TI9|05|TI9_DESCRI|M|10|0|Descrição|Descrição
--- ### TIA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIA|01|TIA_FILIAL|C|6|0|Filial|Filial
TIA|02|TIA_LAUDO|C|12|0|Cód. Laudo|Código do Laudo
TIA|03|TIA_CODPRO|C|9|0|Prog. Saúde|Cód. Programa de Saúde
TIA|04|TIA_NOMPRO|C|40|0|Nome|Programa de Saúde
TIA|05|TIA_DESPRO|C|200|0|Descrição|Desc. Programa de Saúde
--- ### TIB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIB|01|TIB_FILIAL|C|6|0|Filial|Filial
TIB|02|TIB_CODIGO|C|6|0|Código|Código do Questionário
TIB|03|TIB_DESCRI|C|30|0|Descrição|Descrição do Questionário
TIB|04|TIB_CODPRO|C|15|0|Produto|Código do Produto
TIB|05|TIB_DESPRO|C|70|0|Descrição|Descrição do Produto
TIB|06|TIB_GRUPRO|C|5|0|Grupo|Grupo do produto
--- ### TIC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIC|01|TIC_FILIAL|C|6|0|Filial|Filial
TIC|02|TIC_CODIGO|C|6|0|Código|Código do Questionário
TIC|03|TIC_CODGRU|C|3|0|Código Grupo|Código do Grupo
TIC|04|TIC_NOMGRU|C|40|0|Nome Grupo|Nome do Grupo
TIC|05|TIC_ORDEM|C|3|0|Ordem|Ordem da Pergunta
TIC|06|TIC_PERG|C|40|0|Pergunta|Pergunta
TIC|07|TIC_TIPO|C|1|0|Tipo|Tipo do conteúdo
TIC|08|TIC_OBRIG|C|1|0|Obrigatório|Resposta Obrigatória
--- ### TID
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TID|01|TID_FILIAL|C|6|0|Filial|Filial
TID|02|TID_CODIGO|C|6|0|Código|Código do Questionário
TID|03|TID_DESC|C|30|0|Descrição|Descrição do Questionário
TID|04|TID_DTINI|D|8|0|Data Início|Data Início do Questionár
TID|05|TID_CODGRU|C|3|0|Código Grupo|Código do Grupo
TID|06|TID_ORDEM|C|3|0|Ordem|Ordem da Pergunta
TID|07|TID_PERG|C|40|0|Pergunta|Pergunta
TID|08|TID_RESP|C|6|0|Resposta|Resposta do Questionário
TID|09|TID_RESMV|M|10|0|Observação|Observação
TID|10|TID_CODPRO|C|15|0|Produto|Código do Produto
--- ### TIE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIE|01|TIE_FILIAL|C|6|0|Filial|Filial
TIE|02|TIE_CODDEL|C|12|0|Cod. Deleg.|Codigo Delegacia
TIE|03|TIE_NOME|C|60|0|Nome Deleg.|Nome Delegacia
TIE|04|TIE_ENTDEL|C|40|0|Entidade|Entidade Delegacia
--- ### TIF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIF|01|TIF_FILIAL|C|6|0|Filial|Filial
TIF|02|TIF_LAUDO|C|12|0|Laudo|Laudo
TIF|03|TIF_QUEST|C|6|0|Questionário|Questionário
TIF|04|TIF_DESQUE|C|30|0|Descrição|Descrição
--- ### TIG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIG|01|TIG_FILIAL|C|6|0|Filial|Filial do Sistema
TIG|02|TIG_LAUDO|C|12|0|Cód. Laudo|Código do Laudo
TIG|03|TIG_CODFAM|C|6|0|Cod. Família|Cod. Família Equip.
TIG|04|TIG_NOMFAM|C|40|0|Nome|Nome Família Equip.
--- ### TIH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIH|01|TIH_FILIAL|C|6|0|Filial|Filial do Sistema
TIH|02|TIH_CODCAI|C|12|0|Codigo CAI|Codigo CAI
TIH|03|TIH_DESCAI|C|40|0|Desc. CAI|Descrição CAI
TIH|04|TIH_CODDEL|C|12|0|Cod. Deleg.|Codigo Delegacia
TIH|05|TIH_CNAE|C|12|0|CNAE|CNAE
TIH|06|TIH_QTDFUN|N|6|0|Qtd. Func.|Qtd. Funcionários
TIH|07|TIH_MASMAI|N|6|0|Mas. Maiores|Masculino Maiores
TIH|08|TIH_MASMEN|N|6|0|Mas. Menores|Masculino Menores
TIH|09|TIH_FEMMAI|N|6|0|Fem. Maiores|Feminino Maiores
TIH|10|TIH_FEMMEN|N|6|0|Fem. Menores|Feminino Menores
TIH|11|TIH_TERRES|C|6|0|Termo Respon|Termo Responsabilidade
TIH|12|TIH_PERMAX|N|2|0|Per. Maximo|Período Máximo
TIH|13|TIH_INFONR|M|10|0|Info NR02|Informações NR02
TIH|14|TIH_MMSYP|C|6|0|Cod SYP|Codigo SYP
--- ### TII
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TII|01|TII_FILIAL|C|6|0|Filial|Filial do Sistema
TII|02|TII_CODCAI|C|12|0|Codigo CAI|Codigo CAI
TII|03|TII_CODAMB|C|30|0|Amb. Físico|Codigo Ambiente Físico
TII|04|TII_NOMAMB|C|40|0|Nome Amb.|Nome Ambiente Físico
TII|05|TII_QUESTI|C|6|0|Questionário|Questionário Inspeção
--- ### TIJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIJ|01|TIJ_FILIAL|C|6|0|Filial|Filial do Sistema
TIJ|02|TIJ_CODCAI|C|12|0|Codigo CAI|Codigo CAI
TIJ|03|TIJ_CODAMB|C|30|0|Amb. Físico|Codigo Ambiente Físico
TIJ|04|TIJ_NOMAMB|C|40|0|Nome Amb.|Nome Ambiente Físico
TIJ|05|TIJ_CODFAM|C|6|0|Família|Codigo Família
TIJ|06|TIJ_NOMFAM|C|40|0|Nome Família|Nome Família
TIJ|07|TIJ_TIPMOD|C|10|0|Tipo/Modelo|Codigo Tipo/Modelo
TIJ|08|TIJ_DESMOD|C|20|0|Desc. Modelo|Descrição Tipo/Modelo
--- ### TIK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIK|01|TIK_FILIAL|C|6|0|Filial|Filial
TIK|02|TIK_TAREFA|C|6|0|Tarefa|Código da Tarefa
TIK|03|TIK_EPI|C|15|0|EPI|Código do EPI
TIK|04|TIK_DESEPI|C|70|0|Descr. EPI|Descrição do EPI
--- ### TIL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIL|01|TIL_FILIAL|C|6|0|Filial|Filial do Sistema
TIL|02|TIL_CNES|C|7|0|Cód. CNES|Código CNES
TIL|03|TIL_ESTAB|C|80|0|Estab.|Estabelecimento
TIL|04|TIL_UF|C|2|0|UF CNES|Unidade Fed. CNES
TIL|05|TIL_CODMUN|C|5|0|Código IBGE|Cód. Município
TIL|06|TIL_DESMUN|C|60|0|Município|Município
TIL|07|TIL_FRMCTT|C|100|0|Forma Cont.|Forma de Contato
TIL|08|TIL_EMAIL|C|60|0|Email|Email de Contato
--- ### TJ0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ0|01|TJ0_FILIAL|C|6|0|Filial|Filial do Sistema
TJ0|02|TJ0_LAUDO|C|12|0|Laudo|Codigo do Laudo
TJ0|03|TJ0_NUMRIS|C|9|0|Risco|Numero do Risco
TJ0|04|TJ0_MAT|C|6|0|Matricula|Matricula do Funcionario
TJ0|05|TJ0_TIPOAD|C|1|0|Adicional|Tipo de Adicional
TJ0|06|TJ0_PERINT|C|1|0|Perc.SESMT|Percentual pelo SESMT
TJ0|07|TJ0_PERFOL|N|5|2|Perc.Folha|Percentual pela Folha
TJ0|08|TJ0_DTINEX|D|8|0|Dt.Ini.Expos|Dt.Inicio da Exposicao
TJ0|09|TJ0_DTFIEX|D|8|0|Dt.Fim.Expos|Dt.Final a Exposicao
TJ0|10|TJ0_CONFEX|C|1|0|Confirmado?|Confirma a Exposicao ?
TJ0|11|TJ0_DTCONF|D|8|0|Dt.Conf.Exp.|Dt.da Confir.a Exposicao
--- ### TJ1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ1|01|TJ1_FILIAL|C|6|0|Filial|Filial
TJ1|02|TJ1_QUESTI|C|6|0|Questionário|Questionário
TJ1|03|TJ1_FUNC|C|5|0|Função|Função
TJ1|04|TJ1_TAR|C|6|0|Tarefa|Tarefa
TJ1|05|TJ1_CC|C|9|0|Centro Custo|Centro de Custo
TJ1|06|TJ1_AMB|C|30|0|Amb. Fisico|Ambiente Físico
TJ1|07|TJ1_LOC|C|6|0|Localização|Localização
TJ1|08|TJ1_TPFUN|C|1|0|Tipo Func.|Tipo Funcionário
TJ1|09|TJ1_MAT|C|6|0|Funcionário|Matrícula Funcionário
TJ1|10|TJ1_OSSIMU|C|6|0|OS Simul.|Ordem de Serviço Simulaçã
TJ1|11|TJ1_TPRES|C|1|0|Tipo Respons|Tipo Responsável
TJ1|12|TJ1_RESPEN|C|12|0|Responsável|Responsável pela Entrevis
TJ1|13|TJ1_DTINC|D|8|0|Dt. Inclusão|Data Inclusão
TJ1|14|TJ1_USER|C|20|0|Usuário|Usuário
TJ1|15|TJ1_TITULO|C|40|0|Título|Título
TJ1|16|TJ1_COMTCM|C|6|0|Comentários|Comentários
TJ1|17|TJ1_COMTVM|M|10|0|Comentários|Comentários
TJ1|18|TJ1_SEQRES|C|9|0|Seq. Resp.|Sequência da Resposta
--- ### TJ2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ2|01|TJ2_FILIAL|C|6|0|Filial|Filial
TJ2|02|TJ2_QUESTI|C|6|0|Questionário|Questionário
TJ2|03|TJ2_NOMQUE|C|40|0|Nome Quest.|Nome Quest.
TJ2|04|TJ2_FUNC|C|5|0|Função|Função
TJ2|05|TJ2_TAR|C|6|0|Tarefa|Tarefa
TJ2|06|TJ2_CC|C|9|0|Centro Custo|Centro de Custo
TJ2|07|TJ2_AMB|C|30|0|Amb. Fisico|Ambiente Físico
TJ2|08|TJ2_LOC|C|6|0|Localização|Localização
TJ2|09|TJ2_INDDAT|C|1|0|Imp. Data?|Imprime Data?
TJ2|10|TJ2_INDEMP|C|1|0|Imp. Empresa|Imprime Empresa?
TJ2|11|TJ2_INDTIT|C|1|0|Imp. Nome|Imprime Nome Quest.?
TJ2|12|TJ2_INDPAG|C|1|0|Imp. Núm P.|Imp. Núm. da Página?
TJ2|13|TJ2_INDTEX|C|1|0|Imp. Texto ?|Imp. Campo Texto?
TJ2|14|TJ2_INDRES|C|1|0|Imp. Resp.?|Imp. Responsável?
TJ2|15|TJ2_CDTEXT|C|6|0|Texto|Código Texto
TJ2|16|TJ2_TPRES|C|1|0|Tipo Resp.|Tipo Responsável
TJ2|17|TJ2_CODRES|C|6|0|Responsável|Responsável
TJ2|18|TJ2_NOMRES|C|40|0|Responsável|Responsável
TJ2|19|TJ2_DTCAD|D|8|0|Data Cad.|Data Cadastro Questionári
TJ2|20|TJ2_USER|C|20|0|Usuário|Usuário
--- ### TJ3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ3|01|TJ3_FILIAL|C|6|0|Filial|Filial
TJ3|02|TJ3_QUESTI|C|6|0|Questionário|Questionário
TJ3|03|TJ3_NOMQUE|C|20|0|Nome Quest.|Nome Quest.
TJ3|04|TJ3_QUESTA|C|4|0|Questão|Número Questão
TJ3|05|TJ3_PERGUN|C|60|0|Pergunta|Pergunta do Questionário
TJ3|06|TJ3_INDSEX|C|1|0|Sexo|Indicador de Sexo
TJ3|07|TJ3_CODGRU|C|6|0|Grupo Perg.|Grupo Pergunta
TJ3|08|TJ3_NOMGRU|C|40|0|Nome Grupo|Nome Grupo
TJ3|09|TJ3_ORDGRP|C|3|0|Ord. Grupo|Ordem Grupo
TJ3|10|TJ3_TIPGRP|C|1|0|Tipo Grupo|Tipo Grupo
TJ3|11|TJ3_COMBO|C|250|0|Editar Opc.|Editar Opções
TJ3|12|TJ3_TPLIST|C|1|0|Tipo Resp.|Tipo Resp.
TJ3|13|TJ3_ONMEMO|C|1|0|Campo Obs.|Campo Obs.
TJ3|14|TJ3_DEFAUL|C|1|0|Default|Default
TJ3|15|TJ3_ORDEM|C|3|0|Ordem|Ordem
TJ3|16|TJ3_TAM|N|2|0|Tamanho|Tamanho
TJ3|17|TJ3_FORMAT|C|8|0|Formato|Formato
TJ3|18|TJ3_FORMUL|C|3|0|Fórmula|Fórmula
TJ3|19|TJ3_CATOT|C|1|0|Result. Tot|Resultado Linha Total
--- ### TJ4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ4|01|TJ4_FILIAL|C|6|0|Filial|Filial
TJ4|02|TJ4_CODGRU|C|6|0|Codigo Grupo|Codigo Grupo
TJ4|03|TJ4_DESCRI|C|110|0|Descrição|Descrição
TJ4|04|TJ4_TIPREG|C|1|0|Tipo Reg.|Tipo Registro
--- ### TJ5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ5|01|TJ5_FILIAL|C|6|0|Filial|Filial
TJ5|02|TJ5_QUEST|C|6|0|Questionário|Código do Questionário
TJ5|03|TJ5_DTRESP|D|8|0|Data Resp.|Data da Resposta
TJ5|04|TJ5_PERG|C|4|0|Pergunta|Pergunta
TJ5|05|TJ5_FUNC|C|5|0|Função|Função
TJ5|06|TJ5_TAR|C|6|0|Tarefa|Tarefa
TJ5|07|TJ5_CC|C|9|0|Centro Custo|Centro de Custo
TJ5|08|TJ5_AMB|C|30|0|Amb. Físico|Ambiente Físico
TJ5|09|TJ5_LOC|C|6|0|Localização|Localização
TJ5|10|TJ5_MAT|C|6|0|Funcionário|Funcionário
TJ5|11|TJ5_RESPCD|C|1|0|Res. Perg. C|Resposta Perg. Codificada
TJ5|12|TJ5_SEQGTD|C|3|0|Seq. Registr|Seq. Registro Get Dados
TJ5|13|TJ5_OSSIMU|C|6|0|OS Simul.|Ord. de Serviço Simulação
TJ5|14|TJ5_RSPSO|N|3|0|Peso|Peso da Resposta
TJ5|15|TJ5_TEXTD|C|80|0|Texto Desc.|Texto Descritivo
TJ5|16|TJ5_NUMERI|N|9|2|R. Numérica|Resposta Numérica
TJ5|17|TJ5_RESMCD|C|6|0|C. Obs. Memo|Código Memo Obs.
TJ5|18|TJ5_RESMV|M|10|0|Observação|Observação
TJ5|19|TJ5_SEQRES|C|9|0|Seq. Resp.|Sequência da Resposta
--- ### TJ6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ6|01|TJ6_FILIAL|C|6|0|Filial|Filial
TJ6|02|TJ6_CODFOR|C|3|0|Fórmula|Fórmula
TJ6|03|TJ6_IDFXA|C|3|0|Id Faixa|Id Faixa
TJ6|04|TJ6_RETOR|C|50|0|Editar Opc.|Editar Opções
TJ6|05|TJ6_ITDE|N|12|2|De Desem.|De Desempenho
TJ6|06|TJ6_ITATE|N|12|2|Até Desem.|Até Desempenho
--- ### TJ7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ7|01|TJ7_FILIAL|C|6|0|Filial|Filial do Sistema
TJ7|02|TJ7_TIPREG|C|1|0|Registro|Registro
TJ7|03|TJ7_CODIGO|C|30|0|Código|Código
TJ7|04|TJ7_NOME|C|20|0|Nome|Nome
TJ7|05|TJ7_DATA|D|8|0|Data|Data
TJ7|06|TJ7_PONTO|C|10|0|Ponto|Ponto
TJ7|07|TJ7_TIPO|C|40|0|Tipo|Tipo
TJ7|08|TJ7_OCUPAC|C|4|0|Ocupação|Ocupação
TJ7|09|TJ7_DOSE|C|4|0|Dose|Dose Medição
TJ7|10|TJ7_UNIDAD|C|2|0|Unidade|Unidade de Medida
TJ7|11|TJ7_DISTAN|N|6|2|Distância|Distância
TJ7|12|TJ7_EQUIPA|C|6|0|Equipamento|Equipamento
TJ7|13|TJ7_NOEQTO|C|20|0|Nome Equipam|Nome Equipamento
--- ### TJ9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJ9|01|TJ9_FILIAL|C|6|0|Filial|Filial
TJ9|02|TJ9_CODPRO|C|15|0|Prod. Quim.|Produto Químico
TJ9|03|TJ9_CODEPI|C|15|0|Cód. EPI|Código Produto(EPI)
TJ9|04|TJ9_DESC|C|70|0|Descrição|Descrição
--- ### TJA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJA|01|TJA_FILIAL|C|6|0|Filial|Filial
TJA|02|TJA_LAUDO|C|12|0|Laudo|Codigo do Laudo
TJA|03|TJA_CODLEG|C|12|0|Requisito|Requisito
TJA|04|TJA_EMENTA|C|80|0|Tema da Lei|Tema da Lei
--- ### TJB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJB|01|TJB_FILIAL|C|6|0|Filial|Filial do Sistema
TJB|02|TJB_CODPRO|C|15|0|Produto|Código do Produto Químico
TJB|03|TJB_DESPRO|C|70|0|Desc. Prod.|Descrição do Produto
TJB|04|TJB_MEDCON|C|6|0|Proteção|Medidas de Proteção
TJB|05|TJB_DESMED|C|40|0|Med.Control|Nome Medida Controle
TJB|06|TJB_PLANO|C|6|0|Emergência|Plano de Emergência
TJB|07|TJB_DESPLA|C|80|0|Desc. Plano|Descrição do Plano
TJB|08|TJB_CURSO|C|4|0|Curso|Código do Curso
TJB|09|TJB_DESCUR|C|30|0|Desc. Curso|Descrição do Curso
TJB|10|TJB_RISCOS|C|80|0|Riscos|Riscos à Saúde
TJB|11|TJB_CARACT|C|80|0|Característ.|Característ. do Produto
TJB|12|TJB_PRCATI|C|40|0|Princ. Ativo|Princípio Ativo
TJB|13|TJB_ESTOCA|C|80|0|Estocagem|Condições de estocagem
TJB|14|TJB_DESCAR|C|80|0|Descarte|Sistema de Descarte
TJB|15|TJB_TRANSP|C|80|0|Transporte|Condições de Transporte
TJB|16|TJB_LOCAL|C|40|0|Local Uso|Local de Uso
TJB|17|TJB_CONSUM|N|12|2|Consumo|Consumo Anual
TJB|18|TJB_RISSYP|C|6|0|Riscos|Riscos à Saúde
TJB|19|TJB_MRISCO|M|10|0|Riscos|Riscos à Saúde
TJB|20|TJB_CARSYP|C|6|0|Característ.|Característ. do Produto
TJB|21|TJB_MCARAC|M|10|0|Característ|Caracterist. do Produto
TJB|22|TJB_PRCSYP|C|6|0|Princ. Ativo|Principio Ativo
TJB|23|TJB_MPRCAT|M|10|0|Princ. Ativo|Principio Ativo
TJB|24|TJB_ESTSYP|C|6|0|Estocagem|Condicoes de estocagem
TJB|25|TJB_MESTOC|M|10|0|Estocagem|Condicoes de estocagem
TJB|26|TJB_DESSYP|C|6|0|Descarte|Sistema de Descarte
TJB|27|TJB_MDESCA|M|10|0|Descarte|Sistema de Descarte
TJB|28|TJB_TRASYP|C|6|0|Transporte|Condicoes de Transporte
TJB|29|TJB_MTRANS|M|10|0|Transporte|Condicoes de Transporte
TJB|30|TJB_LOCSYP|C|6|0|Local Uso|Local de Uso
TJB|31|TJB_MLOCAL|M|10|0|Local Uso|Local de Uso
--- ### TJC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJC|01|TJC_FILIAL|C|6|0|Filial|Filial do Sistema
TJC|02|TJC_AGENTE|C|9|0|Agente|Código do Agente
TJC|03|TJC_DESAGE|C|40|0|Desc. Agente|Descrição do Agente
TJC|04|TJC_CODPRO|C|15|0|Produto|Código do Produto Químico
TJC|05|TJC_DESPRO|C|70|0|Descr. Prod.|Descrição do Produto
--- ### TJD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJD|01|TJD_FILIAL|C|6|0|Filial|Filial do Sistema
TJD|02|TJD_NUMRIS|C|9|0|Risco|Número do Risco
TJD|03|TJD_AGENTE|C|9|0|Agente|Código do Agente
TJD|04|TJD_DESAGE|C|40|0|Desc. Agente|Descrição do Agente
TJD|05|TJD_CODPRO|C|15|0|Produto|Código do Produto Químico
TJD|06|TJD_DESPRO|C|70|0|Desc. Produt|Descrição do Produto
--- ### TJE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJE|01|TJE_FILIAL|C|6|0|Filial|Filial do Sistema
TJE|02|TJE_CODLEG|C|12|0|Requisito|Requisito
TJE|03|TJE_CALEND|C|4|0|Treinamento|Codigo do Treinamento
TJE|04|TJE_DESC|C|20|0|Descricao|Descricao do Treinamento
TJE|05|TJE_CURSO|C|4|0|Curso|Curso do Treinamento
TJE|06|TJE_DESCCU|C|30|0|Desc. Curso|Descricao do Curso
TJE|07|TJE_TURMA|C|3|0|Turma|Turma do Curso
--- ### TJF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJF|01|TJF_FILIAL|C|6|0|Filial|Filial do Sistema
TJF|02|TJF_NUMRIS|C|9|0|Num. Risco|Numero Identifica o Risco
TJF|03|TJF_MEDCON|C|6|0|Controle|Medida de Controle
TJF|04|TJF_DESMED|C|40|0|Descrição|Descrição Medida Controle
--- ### TJG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJG|01|TJG_FILIAL|C|6|0|Filial|Filial do Sistema
TJG|02|TJG_LAUDO|C|12|0|Laudo|Codigo do Laudo
TJG|03|TJG_CODPLA|C|6|0|Cod. PAE|Código do PAE
TJG|04|TJG_DESPLA|C|80|0|Descrição|Descrição do PAE
--- ### TJH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJH|01|TJH_FILIAL|C|6|0|Filial|Filial
TJH|02|TJH_SEQUEN|C|3|0|Sequência|Sequência da Simulação
TJH|03|TJH_CODCHK|C|6|0|Check-List|Código Check-List da Sim.
TJH|04|TJH_OPCAO|C|15|0|Opção|Opção do Checklist
TJH|05|TJH_TIPRES|C|1|0|Tp. Resposta|Tipo de Resposta
TJH|06|TJH_CONDOP|C|2|0|Operador|Operador da Condição
TJH|07|TJH_CONDIN|C|10|0|Informação|Informação da Condição
TJH|08|TJH_TIPCAM|C|1|0|Tp.Campo Res|Tipo do campo de Resposta
--- ### TJI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJI|01|TJI_FILIAL|C|6|0|Filial|Filial
TJI|02|TJI_ORDEM|C|6|0|Ordem|Ordem de Serviço
TJI|03|TJI_PLANO|C|6|0|Plano|Plano de Simulação
TJI|04|TJI_CODCHK|C|6|0|CheckList|Código Check-List da Sim.
TJI|05|TJI_DESCHK|C|80|0|Descrição|Descrição do CheckList
TJI|06|TJI_OK|C|2|0|Situação|Situação do CheckList
TJI|07|TJI_CONRES|C|6|0|Usuário|Código do Usuário
TJI|08|TJI_OPCOES|C|1|0|Tipo Opção|Tipo de Opções da Resp.
TJI|09|TJI_SEQCHK|C|3|0|Sequência|Sequência do CheckList
--- ### TJJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJJ|01|TJJ_FILIAL|C|6|0|Filial|Filial
TJJ|02|TJJ_CODPLA|C|6|0|PAE|Código do PAE
TJJ|03|TJJ_CODEST|C|3|0|Estrutura|Código da Estrutura
TJJ|04|TJJ_CODNIV|C|6|0|Nível|Código do Nível
TJJ|05|TJJ_NIVSUP|C|6|0|Niv.Superior|Nível Superior
TJJ|06|TJJ_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
--- ### TJK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJK|01|TJK_FILIAL|C|6|0|Filial|Filial
TJK|02|TJK_CODPLA|C|6|0|Cod. PAE|Codigo do Plano de Atend.
TJK|03|TJK_DESPLA|C|80|0|Descrição|Descrição do PAE
TJK|04|TJK_ELABOR|C|6|0|Elaborador|Código do Elaborador
TJK|05|TJK_NOMELA|C|30|0|Nome|Nome do Elaborador
TJK|06|TJK_RESPON|C|6|0|Responsável|Código do Responsável
TJK|07|TJK_NOMRES|C|30|0|Nome|Nome do Responsável
TJK|08|TJK_OBSPLA|M|10|0|Observação|Observação do PAE
--- ### TJL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJL|01|TJL_FILIAL|C|6|0|Filial|Filial
TJL|02|TJL_CODPLA|C|6|0|Cod. PAE|Codigo do Plano de Atend.
TJL|03|TJL_CODEST|C|3|0|Estrutura|Código da Estrutura
TJL|04|TJL_CODNIV|C|6|0|Nivel|Código do Nivel
--- ### TJM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJM|01|TJM_FILIAL|C|6|0|Filial|Filial
TJM|02|TJM_CODCHK|C|6|0|Checklist|Codigo do Checklist
TJM|03|TJM_DESCHK|C|80|0|Descrição|Descrição do Checklist
TJM|04|TJM_TIPOPC|C|1|0|Tipo Opção|Tipo de Opção
TJM|05|TJM_OBSERV|M|10|0|Observação|Observação do Checklist
--- ### TJN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJN|01|TJN_FILIAL|C|6|0|Filial|Filial
TJN|02|TJN_CODCHK|C|6|0|Check-list|Codigo do Check-list
TJN|03|TJN_CODOPC|C|6|0|Opção|Cod. da Opcao do ChkList
TJN|04|TJN_DESOPC|C|80|0|Descrição|Desc. da Opcao do ChkList
TJN|05|TJN_TIPRES|C|1|0|Tipo|Tipo de Resposta
TJN|06|TJN_CONDOP|C|1|0|Operador|Operador da Condição
TJN|07|TJN_CONDIN|C|10|0|Informação|Valor de Comparação
TJN|08|TJN_TIPACA|C|1|0|Tipo Ação|Tipo de Ação
--- ### TJO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJO|01|TJO_FILIAL|C|6|0|Filial|Filial
TJO|02|TJO_CODPLA|C|6|0|PAE|Codigo do PAE
TJO|03|TJO_DESPLA|C|80|0|Descrição|Descrição do Plano
TJO|04|TJO_SEQUEN|C|3|0|Sequência|Sequência da Simulação
TJO|05|TJO_FREQUE|C|1|0|Frequência|Frequência da Simualação
TJO|06|TJO_QUANTI|N|9|0|Quantidade|Quantidade de Frequência
TJO|07|TJO_DATPLA|D|8|0|Último Plano|Data do Último Plano
TJO|08|TJO_CODCAL|C|3|0|Calendário|Calendário da Simulação
TJO|09|TJO_DESCAL|C|80|0|Descrição|Descrição do Calendário
--- ### TJP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJP|01|TJP_FILIAL|C|6|0|Filial|Filial
TJP|02|TJP_CODPLA|C|6|0|PAE|Codigo do PAE
TJP|03|TJP_SEQUEN|C|3|0|Sequência|Sequência da Simulação
TJP|04|TJP_CODCHK|C|6|0|Check-list|Código do Check-list
TJP|05|TJP_DESCHK|C|80|0|Descrição|Descrição do Check-list
--- ### TJQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJQ|01|TJQ_FILIAL|C|6|0|Filial|Filial
TJQ|02|TJQ_CODPLA|C|6|0|Plano Simul.|Codigo do Plano de Simula
TJQ|03|TJQ_DATPLA|D|8|0|Data Plano|Data do Plano de Simul.
TJQ|04|TJQ_DESPLA|C|80|0|Descrição|Desc. do Plano de Simul.
TJQ|05|TJQ_DATINI|D|8|0|Data Inicial|Data Inicial do Plano
TJQ|06|TJQ_DATFIM|D|8|0|Data Final|Data de Finalização
TJQ|07|TJQ_PLAINI|C|6|0|Plano Inic.|Codigo Inicial do Plano
TJQ|08|TJQ_DESPIN|C|80|0|Descrição|Descrição do Plano Inic.
TJQ|09|TJQ_PLAFIM|C|6|0|Plano Final|Código do Plano Final
TJQ|10|TJQ_DESPFI|C|80|0|Descrição|Descrição do Plano Final
TJQ|11|TJQ_SITUAC|C|1|0|Situação|Situação do Plano
TJQ|12|TJQ_TERMIN|C|1|0|Terminado|Plano de Simul. Terminado
--- ### TJR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJR|01|TJR_FILIAL|C|6|0|Filial|Filial
TJR|02|TJR_CODORD|C|6|0|Ordem|Codigo da Ordem do PAE
TJR|03|TJR_CODPLA|C|6|0|Plano|Código do Plano
TJR|04|TJR_DATPLA|D|8|0|Data Plano|Data de Geração da Ordem
TJR|05|TJR_DATINP|D|8|0|Data Prev.|Data de Inicio Prevista
TJR|06|TJR_DATINR|D|8|0|Data Real.|Data de Inicio Realizada
TJR|07|TJR_DATFIN|D|8|0|Data Final.|Data de Finalização
TJR|08|TJR_PLAEME|C|6|0|PAE|Cod. do Plano Aten. Emerg
TJR|09|TJR_DESPLA|C|80|0|Descrição|Descrição do PAE
TJR|10|TJR_SEQUEN|C|3|0|Sequência|Sequência da Simulação
TJR|11|TJR_DATSIM|D|8|0|Data Simul|Data da Última Simulação
TJR|12|TJR_TERMIN|C|1|0|Terminada|Indica Termino da O.S.
TJR|13|TJR_SITUAC|C|1|0|Situação|Indica Situação da O.S.
TJR|14|TJR_USUARI|C|15|0|Usuário|Usuário que Finalizou
TJR|15|TJR_OBSERV|M|10|0|Observação|Observação da Ordem
--- ### TJS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJS|01|TJS_FILIAL|C|6|0|Filial|Filial
TJS|02|TJS_CODPLA|C|6|0|Plano|Codigo do PAE
TJS|03|TJS_DESPLA|C|40|0|Descrição|Descrição do PAE
TJS|04|TJS_CODACA|C|6|0|Ação|Código do Plano de Ação
TJS|05|TJS_DESACA|C|80|0|Descrição|Desc. do Plano de Ação
--- ### TJT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJT|01|TJT_FILIAL|C|6|0|Filial|Filial
TJT|02|TJT_CODPLA|C|6|0|Plano|Codigo do PAE
TJT|03|TJT_DESPLA|C|80|0|Descrição|Descrição do PAE
TJT|04|TJT_CODPAR|C|6|0|Participante|Código do Participante
TJT|05|TJT_NOMPAR|C|50|0|Nome|Nome do Participante
TJT|06|TJT_CODFUN|C|5|0|Função|Código da Função
TJT|07|TJT_DESFUN|C|80|0|Descrição|Descrição do Departamento
--- ### TJU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJU|01|TJU_FILIAL|C|6|0|Filial|Filial
TJU|02|TJU_ORDEM|C|6|0|Ordem|Ordem do Plano Simul.
TJU|03|TJU_PLANO|C|6|0|Plano|Plano de Simulação
TJU|04|TJU_CHKLIS|C|6|0|Check-list|Código do Check-list
TJU|05|TJU_DESCHK|C|60|0|Descrição|Descrição do Check-list
TJU|06|TJU_OK|C|2|0|Situação|Situação do Check-list
TJU|07|TJU_USUARI|C|6|0|Usuário|Código do Usuário
TJU|08|TJU_SEQCHK|C|3|0|Sequência|Sequencia do Check-List
TJU|09|TJU_OPCOES|C|1|0|Tipo Opção|Tipo de Opção de Resposta
--- ### TJV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJV|01|TJV_FILIAL|C|6|0|Filial|Filial
TJV|02|TJV_ORDEM|C|6|0|Ordem|Ordem do Plano de Simul.
TJV|03|TJV_PLANO|C|6|0|Plano|Plano Simulação
TJV|04|TJV_CHKLIS|C|6|0|Check-list|Código do Check-list
TJV|05|TJV_OPCAO|C|15|0|Opção|Opção do Check-list
TJV|06|TJV_RESPOS|C|10|0|Resposta|Resposta da Opção do Chk.
TJV|07|TJV_USUARI|C|6|0|Usuário|Código do Usuário
TJV|08|TJV_NOMUSU|C|80|0|Nome|Nome do Usuário
TJV|09|TJV_TIPRES|C|1|0|Tipo|Tipo de Resposta
TJV|10|TJV_OPERAD|C|2|0|Operador|Operador da Condição
TJV|11|TJV_CONDIN|C|10|0|Informação|Valor de Comparação
TJV|12|TJV_OK|C|2|0|Situação|Situação da Opção
TJV|13|TJV_OBSERV|C|40|0|Msg. Alerta|Mensagem de Alert
--- ### TJW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJW|01|TJW_FILIAL|C|6|0|Filial|Filial
TJW|02|TJW_CODPLA|C|6|0|Plano|Codigo do PAE
TJW|03|TJW_CODCON|C|6|0|Contato|Cod. Contato Ext.
TJW|04|TJW_DESCON|C|40|0|Descrição|Desc. Contato Ext.
TJW|05|TJW_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
TJW|06|TJW_LOJFOR|C|2|0|Loja Fornec.|Loja do Fornecedor
TJW|07|TJW_NOMFOR|C|80|0|Nome|Nome do Fornecedor
TJW|08|TJW_FONE|C|15|0|Fone|Número de Telefone
TJW|09|TJW_FAX|C|15|0|Fax|Número de Fax
TJW|10|TJW_EMAIL|C|50|0|End. E-mail|Endereço de E-mail
--- ### TJX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJX|01|TJX_FILIAL|C|6|0|Filial|Filial
TJX|02|TJX_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TJX|03|TJX_HORA|C|5|0|Hora|Hora da Ocorrência
TJX|04|TJX_DATA|D|8|0|Data|Data da Ocorrência
TJX|05|TJX_CODPLA|C|6|0|Cod. PAE|Código do PAE
TJX|06|TJX_DESPLA|C|80|0|Descrição|Descrição do PAE
TJX|07|TJX_RESPON|C|6|0|Responsável|Usuário Responsável
TJX|08|TJX_NOME|C|80|0|Nome|Nome do Usuário Resp.
TJX|09|TJX_OBSERV|M|10|0|Observação|Observação da Ocorrência
--- ### TJY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJY|01|TJY_FILIAL|C|6|0|Filial|Filial
TJY|02|TJY_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TJY|03|TJY_MAT|C|6|0|Usuário|Código do Usuário
TJY|04|TJY_AVISAD|C|1|0|Avisado?|Usuário Avisado?
TJY|05|TJY_OBSERV|M|10|0|Observação|Observação da Ocorrência
TJY|06|TJY_DATA|D|8|0|Data Aviso|Data de Aviso?
TJY|07|TJY_HORA|C|5|0|Hora Aviso|Hora de Aviso?
TJY|08|TJY_LOGIN|C|15|0|Login|Login do Informante
--- ### TJZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TJZ|01|TJZ_FILIAL|C|6|0|Filial|Filial
TJZ|02|TJZ_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TJZ|03|TJZ_CODRES|C|15|0|Resíduo|Resíduo Gerado
TJZ|04|TJZ_DESCRE|C|70|0|Desc. Resíd.|Descrição do Resíduo Ger.
TJZ|05|TJZ_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TJZ|06|TJZ_QTDE|N|10|2|Qtde. Resíd.|Qtde. de Resíduos Gerad.
--- ### TK0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK0|01|TK0_FILIAL|C|6|0|Filial|Filial do Sistema
TK0|02|TK0_CODGRU|C|3|0|Código Grupo|Código Grupo
TK0|03|TK0_DESCRI|C|40|0|Descrição|Descrição
--- ### TK1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK1|01|TK1_FILIAL|C|6|0|Filial|Filial do Sistema
TK1|02|TK1_CC|C|9|0|Obra|Obra
TK1|03|TK1_NOMECC|C|30|0|Nome da Obra|Nome da Obra
TK1|04|TK1_FASE|C|3|0|Fase da Obra|Fase da Obra
TK1|05|TK1_NOMFAS|C|30|0|Nome Fase|Nome Fase
TK1|06|TK1_SUBFAS|C|3|0|Sub-fase|Sub-fase
TK1|07|TK1_DESSUB|C|30|0|Nom Sub-Fase|Nom Sub-Fase
TK1|08|TK1_AREA|C|3|0|Área Vivenc.|Área Vivenc.
TK1|09|TK1_DESVIV|C|30|0|Descricao|Descricao
TK1|10|TK1_CARACT|C|6|0|Caracterist.|Caracterist.
TK1|11|TK1_MEMO1|M|10|0|Caracterist.|Caracterist.
--- ### TK2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK2|01|TK2_FILIAL|C|6|0|Filial|Filial do Sistema
TK2|02|TK2_CC|C|9|0|Obra|Obra
TK2|03|TK2_NOMECC|C|30|0|Nome da Obra|Nome da Obra
TK2|04|TK2_FASE|C|3|0|Fase da Obra|Fase da Obra
TK2|05|TK2_NOMFAS|C|30|0|Nome Fase|Nome Fase
TK2|06|TK2_SUBFAS|C|3|0|Sub-fase|Sub-fase
TK2|07|TK2_DESSUB|C|30|0|Nom Sub-Fase|Nom Sub-Fase
TK2|08|TK2_CODEQU|C|12|0|Equipamento|Equipamento
TK2|09|TK2_DESCRI|C|30|0|Descricao|Descricao
TK2|10|TK2_OBSERV|C|6|0|Observacao|Observacao
TK2|11|TK2_MEMO1|M|10|0|Observacao|Observacao
--- ### TK3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK3|01|TK3_FILIAL|C|6|0|Filial|Filial do Sistema
TK3|02|TK3_CC|C|9|0|Obra|Obra
TK3|03|TK3_NOMECC|C|30|0|Nome da Obra|Nome da Obra
TK3|04|TK3_FASE|C|3|0|Fase da Obra|Fase da Obra
TK3|05|TK3_NOMFAS|C|30|0|Nome Fase|Nome Fase
TK3|06|TK3_SUBFAS|C|3|0|Sub-fase|Sub-fase
TK3|07|TK3_DESSUB|C|30|0|Nom Sub-Fase|Nom Sub-Fase
TK3|08|TK3_CODEPC|C|16|0|Código EPC|Código EPC
TK3|09|TK3_DESCRI|C|30|0|Descricao|Descricao
TK3|10|TK3_OBSERV|C|6|0|Observacao|Observacao
TK3|11|TK3_MEMO1|M|10|0|Observacao|Observacao
--- ### TK4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK4|01|TK4_FILIAL|C|6|0|Filial|Filial do Sistema
TK4|02|TK4_CODIGO|C|3|0|Codigo|Codigo do Evento
TK4|03|TK4_DESCRI|C|30|0|Descrição|Descricao do Evento
--- ### TK5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK5|01|TK5_FILIAL|C|6|0|Filial|Filial do Sistema
TK5|02|TK5_ORDEM|C|6|0|Ordem|Ordem de Inspecao
TK5|03|TK5_EVENTO|C|3|0|Evento|Evento da Inspecao
TK5|04|TK5_DESCRI|C|30|0|Descricao|Descricao do Evento
TK5|05|TK5_REALIZ|C|1|0|Realizado|Inspecao Realizada
--- ### TK6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK6|01|TK6_FILIAL|C|6|0|Filial|Filial do Sistema
TK6|02|TK6_INSPEC|C|10|0|Inspecao|Tipo da Inspecao
TK6|03|TK6_EVENTO|C|3|0|Evento|Evento da Inspecao
TK6|04|TK6_DESCRI|C|30|0|Descrição|Descricao do Evento
--- ### TK7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK7|01|TK7_FILIAL|C|6|0|Filial|Filial do Sistema
TK7|02|TK7_NUMFIC|C|9|0|Ficha Medica|Ficha Medica
TK7|03|TK7_NOMFIC|C|80|0|Nome|Nome
TK7|04|TK7_CODESP|C|2|0|Cod. Espec.|Codigo Especialidade
TK7|05|TK7_NOMESP|C|20|0|Nome Espec.|Especialidade
TK7|06|TK7_DATAEN|D|8|0|Data Encam.|Data Encaminhamento
TK7|07|TK7_DATAEX|D|8|0|Data Exame|Data dos Exames
TK7|08|TK7_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TK8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK8|01|TK8_FILIAL|C|6|0|Filial|Filial do Sistema
TK8|02|TK8_TIPPAR|C|1|0|Tipo Partic.|Tipo de Participação
TK8|03|TK8_MANDAT|C|6|0|Mandato|Código do Mandato
TK8|04|TK8_FILRE|C|6|0|Filial Resp.|Filial do Responsável
TK8|05|TK8_MATRE|C|6|0|Responsável|Matrícula do Responsável
TK8|06|TK8_NOMRE|C|30|0|Nome|Nome do Responsável
TK8|07|TK8_NOMPAR|C|50|0|Nome Partic.|Nome Participante
--- ### TK9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TK9|01|TK9_FILIAL|C|6|0|Filial|Filial
TK9|02|TK9_CIDINI|C|8|0|C.I.D. Iníc.|C.I.D. Início
TK9|03|TK9_DESINI|C|20|0|Descr. Iníc.|Descrição Início
TK9|04|TK9_CIDFIM|C|8|0|C.I.D. Fim|CID Fim
TK9|05|TK9_DESFIM|C|20|0|Descr. Final|Descrição Final
TK9|06|TK9_INTERV|C|6|0|Intervalo|Intervalo
TK9|07|TK9_MARCA|C|1|0|Marca Todos?|Marca Todos?
--- ### TKA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKA|01|TKA_FILIAL|C|6|0|Filial|Filial
TKA|02|TKA_INTERV|C|6|0|Intervalo|Intervalo
TKA|03|TKA_CNAE|C|7|0|CNAE|CNAE
TKA|04|TKA_ATIVID|C|20|0|Descricao|Descricao
--- ### TKB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKB|01|TKB_FILIAL|C|6|0|Filial|Filial do Sistema
TKB|02|TKB_NUMASO|C|6|0|Num. ASO|Número do ASO
TKB|03|TKB_EXAME|C|6|0|Cod. Exame|Códugo do Exame
--- ### TKC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKC|01|TKC_FILIAL|C|6|0|Filial|Filial
TKC|02|TKC_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TKC|03|TKC_CODCON|C|6|0|Contato|Cód. do Contato Externo
TKC|04|TKC_AVISAD|C|1|0|Contatado?|Foi Contatado?
TKC|05|TKC_DTCONT|D|8|0|Data Contato|Data em que foi contatado
TKC|06|TKC_HRCONT|C|5|0|Hora Contato|Hora em que foi contatado
TKC|07|TKC_DTCHEG|D|8|0|Data Chegada|Data de Chegada
TKC|08|TKC_HRCHEG|C|5|0|Hora Chegada|Hora de Chegada
--- ### TKD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKD|01|TKD_FILIAL|C|6|0|Filial|Filial do Sistema
TKD|02|TKD_NUMFIC|C|9|0|Ficha Médica|Número da Ficha Médica
TKD|03|TKD_NOMFIC|C|80|0|Candidato|Nome do Candidato
TKD|04|TKD_CODTAR|C|6|0|Cód. Tarefa|Código da Tarefa
TKD|05|TKD_NOMTAR|C|20|0|Tarefa|Nome da Tarefa
TKD|06|TKD_DTINIC|D|8|0|Dt. início|Data de Início da Tarefa
TKD|07|TKD_DTTERM|D|8|0|Dt. Término|Data de Término da Tarefa
--- ### TKE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKE|01|TKE_FILIAL|C|6|0|Filial|Filial
TKE|02|TKE_TABELA|C|3|0|Tabela|Tabela
TKE|03|TKE_CODIGO|C|9|0|Codigo|Codigo
TKE|04|TKE_DIG|C|2|0|Dedo|Dedo
TKE|05|TKE_DIG1|C|200|0|Dig. Part. 1|Dig. Part. 1
TKE|06|TKE_DIG2|C|200|0|Dig. Part. 2|Dig. Part. 2
TKE|07|TKE_DIG3|C|200|0|Dig. Conf. 1|Dig. Conf. 1
TKE|08|TKE_DIG4|C|200|0|Dig. Conf. 2|Dig. Conf. 2
TKE|09|TKE_DIG5|C|200|0|Dig. Part. 5|Dig. Part. 5
TKE|10|TKE_DIG6|C|200|0|Dig. Part. 6|Dig. Part. 6
TKE|11|TKE_DIG7|C|200|0|Dig. Part. 7|Dig. Part. 7
TKE|12|TKE_DIG8|C|200|0|Dig. Part. 8|Dig. Part. 8
TKE|13|TKE_DIG9|C|200|0|Dig. Part. 9|Dig. Part. 9
TKE|14|TKE_DIG10|C|200|0|Dig. Part.10|Dig. Part. 10
TKE|15|TKE_DIG11|C|200|0|Dig. Part.11|Dig. Part. 11
TKE|16|TKE_DIG12|C|200|0|Dig. Part.12|Dig. Part. 12
TKE|17|TKE_DIG13|C|200|0|Dig. Part.13|Dig. Part. 13
TKE|18|TKE_DIG14|C|200|0|Dig. Part.14|Dig. Part. 14
TKE|19|TKE_DIG15|C|200|0|Dig. Part.15|Dig. Part. 15
TKE|20|TKE_DIG16|C|200|0|Dig. Part.16|Dig. Part. 16
TKE|21|TKE_DIG17|C|200|0|Dig. Part.17|Dig. Part. 17
TKE|22|TKE_DIG18|C|200|0|Dig. Part.18|Dig. Part. 18
TKE|23|TKE_DIG19|C|200|0|Dig. Part.19|Dig. Part. 19
TKE|24|TKE_DIG20|C|200|0|Dig. Part.20|Dig. Part. 20
--- ### TKF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKF|01|TKF_FILIAL|C|6|0|Filail|Filial
TKF|02|TKF_CODVAC|C|10|0|Cod. Vacina|Codigo da Vacina
TKF|03|TKF_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TKF|04|TKF_CODCC|C|9|0|Código CC|Código do Centro de Custo
TKF|05|TKF_NOMCC|C|40|0|Nome|Nome do Centro de Custo
TKF|06|TKF_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TKG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKG|01|TKG_FILIAL|C|6|0|Filial|Filial
TKG|02|TKG_CODVAC|C|10|0|Cod. Vacina|Código da Vacina
TKG|03|TKG_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TKG|04|TKG_CODFUN|C|5|0|Código Fun.|Código da Função
TKG|05|TKG_DESFUN|C|20|0|Desc. Função|Descrição da Função
TKG|06|TKG_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TKH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKH|01|TKH_FILIAL|C|6|0|Filial|Filial
TKH|02|TKH_CODVAC|C|10|0|Codigo Vacin|Código da Vacina
TKH|03|TKH_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TKH|04|TKH_MATFUN|C|6|0|Mat. Func.|Matrícula do Funcionário
TKH|05|TKH_NOMFUN|C|30|0|Nome Func.|Nome do Funcionário
TKH|06|TKH_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TKI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKI|01|TKI_FILIAL|C|6|0|Filial|Filial do Sistema
TKI|02|TKI_NATEST|C|10|0|No. Atestado|No. Atestado
TKI|03|TKI_GRPCID|C|3|0|Grupo CID|Grupo CID
TKI|04|TKI_DESGRP|C|220|0|Descrição|Desc. Grupo
TKI|05|TKI_CID|C|8|0|CID Compl.|CID Compl.
TKI|06|TKI_DOENCA|C|220|0|Descrição|Desc. Doenca
TKI|07|TKI_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TKJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKJ|01|TKJ_FILIAL|C|6|0|Filial|Filial
TKJ|02|TKJ_NUMFIC|C|9|0|Ficha Médica|Ficha Médica
TKJ|03|TKJ_DTCONS|D|8|0|Dt. Consulta|Dt. Consulta
TKJ|04|TKJ_HRCONS|C|5|0|Hr. Consulta|Hr. Consulta
TKJ|05|TKJ_GRPCID|C|3|0|Grupo CID|Grupo CID
TKJ|06|TKJ_DESGRP|C|220|0|Desc. Grupo|Desc. Grupo
TKJ|07|TKJ_CID|C|8|0|CID Compl.|CID Compl.
TKJ|08|TKJ_DOENCA|C|220|0|Desc. Doenca|Desc. Doenca
--- ### TKK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKK|01|TKK_FILIAL|C|6|0|Filial|Filial
TKK|02|TKK_ACIDEN|C|6|0|Acidente|Acidente
TKK|03|TKK_GRPCID|C|3|0|Grupo CID|Grupo CID
TKK|04|TKK_DESGRP|C|220|0|Desc. Grupo|Desc. Grupo
TKK|05|TKK_CID|C|8|0|CID Compl.|CID Compl.
TKK|06|TKK_DOENCA|C|220|0|Desc. Doenca|Desc. Doenca
--- ### TKL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKL|01|TKL_FILIAL|C|6|0|Filial|Filial
TKL|02|TKL_BRIGAD|C|10|0|Cod. Brigada|Código da Brigada
TKL|03|TKL_DESC|C|40|0|Desc.Brigada|Descrição da Brigada
TKL|04|TKL_DTVIIN|D|8|0|Vigência In.|Data de Início da Vigênci
TKL|05|TKL_DTVIFI|D|8|0|Vigência Fim|Data de Fim da Vigência
--- ### TKM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKM|01|TKM_FILIAL|C|6|0|Filial|Filial
TKM|02|TKM_BRIGAD|C|10|0|Brigada|Código da Brigada
TKM|03|TKM_CODNIV|C|3|0|Nível|Codigo do Nível
TKM|04|TKM_NIVEL|N|3|0|Nível|Nível
TKM|05|TKM_NIVSUP|C|3|0|C. Nivel Sup|Código do Nivel Superior
TKM|06|TKM_ORDEM|C|3|0|Ordem|Define a posição do nível
TKM|07|TKM_FILMAT|C|6|0|Filial Matr.|Filial Matrícula
TKM|08|TKM_MATFUN|C|6|0|Componente|Código do Componente
TKM|09|TKM_NOMFUN|C|30|0|Nome|Nome do Componente
TKM|10|TKM_DTINCL|D|8|0|Dt. Inclusão|Data de Inclusão
TKM|11|TKM_DTSAID|D|8|0|Dt. Saída|Data de Saída
TKM|12|TKM_FUNCAO|C|5|0|Função|Função na Brigada
TKM|13|TKM_DESFUN|C|20|0|Desc. Função|Descrição da Função Brig.
TKM|14|TKM_TIPO|C|1|0|Tipo|Tipo do Brigadista
TKM|15|TKM_ATRIB|M|10|0|Atribuições|Atribuições do Brigadista
--- ### TKN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKN|01|TKN_FILIAL|C|6|0|Filial|Filial
TKN|02|TKN_BRIGAD|C|10|0|Brigada|Código da Brigada
TKN|03|TKN_EXAME|C|6|0|Exame|Código do Exame
TKN|04|TKN_NOMEXA|C|40|0|Nome Exame|Nome do Exame
TKN|05|TKN_FAIXA|C|2|0|Faixa|Faixa do Exame
--- ### TKO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKO|01|TKO_FILIAL|C|6|0|Filial|Filial
TKO|02|TKO_BRIGAD|C|10|0|Brigada|Código da Brigada
TKO|03|TKO_CODTRE|C|4|0|Treinamento|Código do Treinamento
TKO|04|TKO_DESTRE|C|30|0|Desc. Trein.|Descrição do Treinamento
TKO|05|TKO_CURSO|C|4|0|Curso|Curso do Treinamento
TKO|06|TKO_DESCUR|C|30|0|Desc. Curso|Descrição do Curso do Tre
TKO|07|TKO_DURTRE|N|7|0|Durac. Trein|Duração do Treinamento
TKO|08|TKO_UNITRE|C|1|0|Unid. Durac.|Unidade de Duração
--- ### TKP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKP|01|TKP_FILIAL|C|6|0|Filial|Filial
TKP|02|TKP_ROTINA|C|12|0|Rotina|Rotina
TKP|03|TKP_DESCRI|C|60|0|Descrição|Descrição Rotina
TKP|04|TKP_DESSPA|C|60|0|Desc. Esp|Descrição Espanhol Rotina
TKP|05|TKP_DESENG|C|60|0|Desc. Ing|Descrição Inglês Rotina
TKP|06|TKP_GRUPOS|C|74|0|Grupos|Grupos Habilitados
--- ### TKQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKQ|01|TKQ_FILIAL|C|6|0|Filial|Filial
TKQ|02|TKQ_BRIGAD|C|10|0|Cod. Brigada|Codigo da Brigada
TKQ|03|TKQ_DTREUN|D|8|0|Data Reunião|Data da Reunião da Brigad
TKQ|04|TKQ_HRREUN|C|5|0|Hora Reunião|Hora da Reunião
TKQ|05|TKQ_TIPREU|C|1|0|Tipo Reunião|Tipo da Reunião
TKQ|06|TKQ_ASSUNT|C|60|0|Assunto|Assunto da Reunião
TKQ|07|TKQ_DTREAL|D|8|0|Data Real|Data Real da Reunião
TKQ|08|TKQ_HRREAL|C|5|0|Hora Real|Hora Real da Reunião
TKQ|09|TKQ_DURAC|C|5|0|Duração|Duração Real da Reunião
TKQ|10|TKQ_LOCAL|C|60|0|Local|Local da Reunião
TKQ|11|TKQ_ATA|M|10|0|Ata Reunião|Ata da Reunião
--- ### TKR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKR|01|TKR_FILIAL|C|6|0|Filial|Filial
TKR|02|TKR_BRIGAD|C|10|0|Cod. Brigada|Codigo da Brigada
TKR|03|TKR_DTREUN|D|8|0|Dt. Reunião|Data da Reunião
TKR|04|TKR_HRREUN|C|5|0|Hora Reunião|Hora da Reunião
TKR|05|TKR_TIPPAR|C|1|0|Tipo Part.|Tipo do Participante
TKR|06|TKR_FILPAR|C|6|0|Filial Par.|Filial do Brigadista
TKR|07|TKR_MAT|C|6|0|Matrícula|Matrícula do Brigadista
TKR|08|TKR_NOME|C|30|0|Nome Par.|Nome do Brigadista
TKR|09|TKR_COMPAR|C|1|0|Compareceu?|Participante Compareceu?
--- ### TKS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKS|01|TKS_FILIAL|C|6|0|Filial|Filial
TKS|02|TKS_CODCJN|C|10|0|Cod. Cj. Hid|Codigo do Conjunto Hidr.
TKS|03|TKS_BEM|C|16|0|Bem|Codigo do Bem
TKS|04|TKS_DESCJN|C|40|0|Des. Cj. Hid|Descrição do Conjunto Hid
TKS|05|TKS_FAMCJN|C|6|0|Família|Família do Conjunto
TKS|06|TKS_NFACJN|C|40|0|Nome Família|Nome da Família do Conjun
TKS|07|TKS_CCCJN|C|9|0|Centro Custo|Centro de Custo do Conjun
TKS|08|TKS_NCCCJN|C|40|0|Nome C.C.|Nome do Centro de Custo
TKS|09|TKS_LOCCJN|C|40|0|Localização|Localização do Conjunto
TKS|10|TKS_TURCJN|C|3|0|Turno|Turno do Conjunto
TKS|11|TKS_NTUCJN|C|20|0|Nome Turno|Nome do Turno
TKS|12|TKS_MARCA|C|20|0|Marca|Marca
TKS|13|TKS_MODELO|C|10|0|Modelo|Modelo
TKS|14|TKS_CAPACI|N|12|3|Capacidade|Capacidade
TKS|15|TKS_UNIMED|C|6|0|Und. Medida|Unidade de Medida
TKS|16|TKS_SITUAC|C|1|0|Situação|Situação do Cjn. Hidr.
TKS|17|TKS_DTMANU|D|8|0|Dt. Ult.Manu|Data da Última Manutenção
TKS|18|TKS_ANOFAB|C|4|0|Ano Fabric.|Ano da Fabricação
TKS|19|TKS_DTCOMP|D|8|0|Dt. Compra|Data da Compra
TKS|20|TKS_FABRIC|C|6|0|Fabricante|Fabricante do Conjunto
TKS|21|TKS_NOMFAB|C|40|0|Nome Fabric.|Nome Fabric. do Conjunto
TKS|22|TKS_FORNEC|C|6|0|Fornecedor|Fornecedor do Conjunto
TKS|23|TKS_LOJA|C|2|0|Loja Fornec.|Loja Fornec. do Conjunto
TKS|24|TKS_NOMFOR|C|80|0|Nome Fornec.|Nome Fornec. do Conjunto
--- ### TKT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKT|01|TKT_FILIAL|C|6|0|Filial|Filial
TKT|02|TKT_INSPEC|C|10|0|Inspeção|Codigo da Inspeção
TKT|03|TKT_FAMILI|C|6|0|Família|Família da Inspeção
TKT|04|TKT_NOMFAM|C|40|0|Descrição|Nome da Famíla Inspeção
--- ### TKU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKU|01|TKU_FILIAL|C|6|0|Filial|Filial
TKU|02|TKU_CODIGO|C|5|0|Cod. Função|Codigo da Função da Brig.
TKU|03|TKU_DESC|C|20|0|Descrição|Descrição da Função Brig.
TKU|04|TKU_ATIVID|M|10|0|Atividades|Adividades do PAE
TKU|05|TKU_ATVSYP|C|6|0|Ativid. SYP|Atividades SYP
--- ### TKW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKW|01|TKW_FILIAL|C|6|0|Filial|Filial
TKW|02|TKW_CODPLA|C|6|0|PAE|Plano de Atend. Emerg.
TKW|03|TKW_DESPLA|C|80|0|Descrição|Descrição do PAE
TKW|04|TKW_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TKW|05|TKW_DATA|D|8|0|Data|Data da Ocorrência
TKW|06|TKW_HORA|C|5|0|Hora|Hora da Ocorrência
--- ### TKX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKX|01|TKX_FILIAL|C|6|0|Filial|Filial
TKX|02|TKX_CODPLA|C|6|0|PAE|Plano de Atend. Emerg.
TKX|03|TKX_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TKX|04|TKX_DTOCO|D|8|0|Data|Data da Ocorrência
TKX|05|TKX_HROCO|C|5|0|Hora|Hora da Ocorrência
TKX|06|TKX_CODACA|C|6|0|Ação|Código da Ação do PAE
TKX|07|TKX_DESACA|C|80|0|Descrição|Descrição da Ação do PAE
TKX|08|TKX_CODPAC|C|6|0|Plano Ação|Código do Plano de Ação
TKX|09|TKX_OK|C|1|0|Respondido|Identifica Medidas Resp.
TKX|10|TKX_DTINIC|D|8|0|Data Inicial|Data de Início da Ação
TKX|11|TKX_DTFIM|D|8|0|Data Termino|Data de Termino da Ação
--- ### TKY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKY|01|TKY_FILIAL|C|6|0|Filial|Filial
TKY|02|TKY_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TKY|03|TKY_TIPENV|C|1|0|Tipo|Tipo de Envolvido
TKY|04|TKY_CODMAT|C|6|0|Matrícula|Matrícula do Funcionário
TKY|05|TKY_NOME|C|80|0|Participante|Nome do Envolvido
--- ### TKZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TKZ|01|TKZ_FILIAL|C|6|0|Filial|Filial
TKZ|02|TKZ_NUM|C|6|0|ID Proc.|ID Processamento
TKZ|03|TKZ_DTPRC|D|8|0|Data Proc.|Data Processamento
TKZ|04|TKZ_HRPRC|C|5|0|Hora Proc.|Hora Processamento
TKZ|05|TKZ_TIPPER|C|1|0|Tipo Per.|Tipo Periodicidade
TKZ|06|TKZ_QTREG|N|7|0|Qtd. Exa.Del|Qtd. Exames Deletados
--- ### TL0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL0|01|TL0_FILIAL|C|6|0|Filial|Filial
TL0|02|TL0_EPIGEN|C|15|0|Cod. EPI Pai|Codigo EPI Pai
TL0|03|TL0_FORNEC|C|6|0|Fornecedor|Cod. Fornecedor
TL0|04|TL0_LOJA|C|2|0|Loja do Forn|Loja do Fornecedor
TL0|05|TL0_EPIFIL|C|15|0|Epi Filho|Codigo EPI Filho
TL0|06|TL0_DESCRI|C|70|0|Descr.|Descricao EPI
TL0|07|TL0_NUMCAP|C|12|0|Num. C.A.|Num. Cert. Aprovacao
TL0|08|TL0_DTVENC|D|8|0|Venc. C.A.|Dt. Vencimento C.A.
TL0|09|TL0_DTINIC|D|8|0|Data Inicio|Data Inicio
TL0|10|TL0_DTFIM|D|8|0|Data Fim|Data Fim
TL0|11|TL0_DTVALI|D|8|0|Data Valid.|Data de Validade
--- ### TL5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL5|01|TL5_FILIAL|C|6|0|Filial|Filial do Sistema
TL5|02|TL5_DTATEN|D|8|0|Data Atend.|Data de Atendimento
TL5|03|TL5_HRATEN|C|5|0|Hora Atend.|Hora do Atendimento
TL5|04|TL5_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TL5|05|TL5_NOMFIC|C|80|0|Nome|Nome
TL5|06|TL5_INDICA|C|1|0|Indicação|Indicacao
TL5|07|TL5_MOTIVO|C|3|0|Mot. Atend.|Motivo do Atendimento
TL5|08|TL5_DESMOT|C|20|0|Descr.Motivo|Descricao do Motivo
TL5|09|TL5_CODMED|C|15|0|Cód. Medic.|Codigo do Medicamento
TL5|10|TL5_DESMED|C|30|0|Descrição|Descricao do Medicamento
TL5|11|TL5_QTDADE|N|9|2|Quantidade|Quantidade
TL5|12|TL5_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
TL5|13|TL5_OBSERV|C|100|0|Observacao|Observacao
TL5|14|TL5_CODUSU|C|12|0|Cod. Usuario|Codigo Usuario
TL5|15|TL5_NOMUSU|C|20|0|Nome Usuario|Nome do Usuario
TL5|16|TL5_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TL5|17|TL5_TEMPER|N|5|2|Temperatura|Temperatura Corporal
TL5|18|TL5_ALTURA|N|4|2|Altura|Altura do Paciente
TL5|19|TL5_PESO|N|6|2|Peso|Peso
TL5|20|TL5_MASSA|C|20|0|Massa|Massa Corporal
TL5|21|TL5_PRESIS|N|3|0|Sistólica|Pressão Sistólica
TL5|22|TL5_PREDIS|N|3|0|Diastólica|Pressão Diastólica
TL5|23|TL5_PULSO|C|10|0|Pulso|Pulso do Paciente
TL5|24|TL5_RESPI|C|12|0|Respiração|Respiração do Paciente
TL5|25|TL5_DINAMO|N|9|3|Dinamometria|Dinamometria
TL5|26|TL5_MOBSER|M|10|0|Observação|Observação
TL5|27|TL5_OBSSYP|C|6|0|Observação|Observação
--- ### TL6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL6|01|TL6_FILIAL|C|6|0|Filial|Filial do Sistema
TL6|02|TL6_VACINA|C|10|0|Cod. Vacina|Codigo da Vacina
TL6|03|TL6_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TL6|04|TL6_DESVAC|C|60|0|Descrição|Descricao da Vacina
TL6|05|TL6_SEXO|C|1|0|Sexo|Vac. para deter. sexo
TL6|06|TL6_CC|C|1|0|Centro Custo|Filtro por Centro de Cust
TL6|07|TL6_FUNC|C|1|0|Função|Filtro por Função
TL6|08|TL6_FNCR|C|1|0|Funcionário|Filtro por Funcionário
TL6|09|TL6_USERGI|C|17|0|Log de Inclu|Log de Inclusao
TL6|10|TL6_MMVNG|C|6|0|Resp. Receb.|Resposta Recebida
TL6|11|TL6_VANTAG|M|10|0|Vantagens|Descrição das Vantagens
TL6|12|TL6_MMEFTO|C|6|0|Resp. Receb.|Resposta Recebida
TL6|13|TL6_EFEITO|M|10|0|Efeitos|Efeitos Colaterais
TL6|14|TL6_MMRCMC|C|6|0|Res. Receb.|Resposta Recebida
TL6|15|TL6_RECOME|M|10|0|Recomend.|Recomendações Importantes
--- ### TL7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL7|01|TL7_FILIAL|C|6|0|Filial|Filial do Sistema
TL7|02|TL7_VACINA|C|10|0|Cod. Vacina|Codigo da Vacina
TL7|03|TL7_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TL7|04|TL7_IDADEI|C|3|0|De Idade|De Idade
TL7|05|TL7_IDADEF|C|3|0|Ate Idade|Ate Idade
TL7|06|TL7_DOSMAX|N|3|0|Doses Max.|Quantidade Doses Maxima
TL7|07|TL7_USERGI|C|17|0|Log de Inclu|Log de Inclusao
--- ### TL8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL8|01|TL8_FILIAL|C|6|0|Filial|Filial do Sistema
TL8|02|TL8_VACINA|C|10|0|Cod Vacina|Codigo da Vacina
TL8|03|TL8_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TL8|04|TL8_IDADEI|C|3|0|De Idade|De Idade
TL8|05|TL8_DOSEID|C|2|0|Dose|Dose
TL8|06|TL8_DESCRI|C|20|0|Descrição|Descricao
TL8|07|TL8_REPETI|C|1|0|Repetição|Repeticao
TL8|08|TL8_PERIOD|N|4|0|Periodic.|Periodicidade repeticao
TL8|09|TL8_UNIDA1|C|1|0|Unidade|Unidade
TL8|10|TL8_INIDOS|N|4|0|Quant. Doses|Inicio Apos Ultima Dose
TL8|11|TL8_UNIDA2|C|1|0|Unidade Após|Unidade Apos Ultima Dose
--- ### TL9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TL9|01|TL9_FILIAL|C|6|0|Filial|Filial do Sistema
TL9|02|TL9_NUMFIC|C|9|0|Ficha Médica|Ficha Medica
TL9|03|TL9_NOMFIC|C|80|0|Nome|Nome
TL9|04|TL9_VACINA|C|10|0|Cod. Vacina|Codigo da Vacina
TL9|05|TL9_NOMVAC|C|30|0|Nome Vacina|Nome da Vacina
TL9|06|TL9_DOSE|C|2|0|Dose|Dose da Vacina
TL9|07|TL9_DTPREV|D|8|0|Data Prev.|Data Prevista
TL9|08|TL9_INDVAC|C|1|0|Vacinado ?|Foi Vacinado ?
TL9|09|TL9_NUMCON|C|10|0|Num. Convoc.|Numero Convocacao
TL9|10|TL9_DTREAL|D|8|0|Data Real|Data Real
TL9|11|TL9_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TL9|12|TL9_USERGA|C|17|0|Log de Alter|Log de Alteração
--- ### TLA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLA|01|TLA_FILIAL|C|6|0|Filial|Filial do Sistema
TLA|02|TLA_CODEXT|C|16|0|Código|Codigo do Extintor
TLA|03|TLA_DESCRI|C|30|0|Descrição|Descricao
TLA|04|TLA_CC|C|9|0|Centro Custo|Centro Custo
TLA|05|TLA_NOMECC|C|20|0|Nome|Nome do C. Custo
TLA|06|TLA_LOCAL|C|20|0|Localização|Localizacao
TLA|07|TLA_MARCA|C|20|0|Marca|Marca
TLA|08|TLA_TIPO|C|15|0|Tipo|Tipo
TLA|09|TLA_CAPACI|N|12|3|Capacidade|Capacidade
TLA|10|TLA_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
TLA|11|TLA_SITUAC|C|1|0|Situação|Situação
TLA|12|TLA_DTMANU|D|8|0|Ult. Manut.|Data Ultima Manutencao
TLA|13|TLA_DTRECA|D|8|0|Ult. recarga|Data Ultima Recarga
TLA|14|TLA_NUMFAB|C|15|0|Num. Fabric.|Numero Fabricacao
TLA|15|TLA_PESOVZ|N|8|1|Peso Vazio|Peso Vazio
TLA|16|TLA_PESOCH|N|8|1|Peso Cheio|Peso Cheio
TLA|17|TLA_PESOUN|C|6|0|Un.Med. Peso|Unidade Medida do Peso
TLA|18|TLA_ATIFIX|C|14|0|Ativo Fixo|Código Ativo Fixo
TLA|19|TLA_ABNT|C|15|0|ABNT|Código ABNT
--- ### TLB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLB|01|TLB_FILIAL|C|6|0|Filial|Filial do Sistema
TLB|02|TLB_CODIGO|C|10|0|Tipo insp.|Tipo de Inspecao
TLB|03|TLB_DESCRI|C|30|0|Descrição|Descricao
TLB|04|TLB_CALEND|C|3|0|Calendario|Calendario
TLB|05|TLB_DESCAL|C|20|0|Desc. Calend|Descricao do Calendario
TLB|06|TLB_PERIOD|N|4|0|Period.|Periodicidade Inspecoes
TLB|07|TLB_UNIDAD|C|1|0|Unidade|Unidade
TLB|08|TLB_CATEGO|C|1|0|Categoria|Categoria
--- ### TLC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLC|01|TLC_FILIAL|C|6|0|Filial|Filial do Sistema
TLC|02|TLC_PLANO|C|6|0|Plano|Numero do Plano
TLC|03|TLC_DTGERA|D|8|0|Data Geração|Data Geracao
TLC|04|TLC_DESCRI|C|80|0|Descrição|Descricao
TLC|05|TLC_DTINI|D|8|0|Data Início|Data Inicio
TLC|06|TLC_DTFIM|D|8|0|Data Fim|Data do Fim do Plano
TLC|07|TLC_CATEGO|C|1|0|Categoria|Categoria do Plano
TLC|08|TLC_TIPINI|C|10|0|De Inspeção|De Tipo de Inspecao
TLC|09|TLC_TIPFIM|C|10|0|Até Inspeção|Ate Tipo de Inspecao
TLC|10|TLC_EXTINI|C|16|0|De Extintor|De Extintor
TLC|11|TLC_EXTFIM|C|16|0|Até Extintor|Ate Extintor
TLC|12|TLC_CCINI|C|9|0|De C. Custo|De Centro de Custo
TLC|13|TLC_CCFIM|C|9|0|Até C. Custo|Ate Centro de Custo
TLC|14|TLC_CJNINI|C|10|0|De Conj.|De Conjunto Hidráulico
TLC|15|TLC_CJNFIM|C|10|0|Até Conj.|Ate Conjunto Hidráulico
TLC|16|TLC_USUARI|C|25|0|Responsável|Usuario Responsavel Plano
--- ### TLD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLD|01|TLD_FILIAL|C|6|0|Filial|Filial do Sistema
TLD|02|TLD_ORDEM|C|6|0|Ordem|Numero da Ordem Inspecao
TLD|03|TLD_PLANO|C|6|0|Plano|Numero do Plano
TLD|04|TLD_CATEGO|C|1|0|Categoria|Categoria Ordem de Insp.
TLD|05|TLD_CODEXT|C|16|0|Sist. Ext.|Cod. do Sis. de Extincao
TLD|06|TLD_DESEXT|C|20|0|Descrição|Desc. do Sis. de Extincao
TLD|07|TLD_CODTIP|C|10|0|Tipo Insp.|Codigo Tipo de Inspecao
TLD|08|TLD_DESTIP|C|20|0|Descrição|Descricao Tipo Inspecao
TLD|09|TLD_CC|C|9|0|Centro Custo|Centro de Custo
TLD|10|TLD_DTPREV|D|8|0|Data Prev.|Data Prevista
TLD|11|TLD_DTREAL|D|8|0|Data Real|Data da Realizacao
TLD|12|TLD_SITUAC|C|1|0|Situação|Situacao Ordem Inspecao
TLD|13|TLD_DTINCL|D|8|0|Data Incl.|Data da Inclusao
TLD|14|TLD_CODUSU|C|12|0|Responsável|Codigo Responsavel
TLD|15|TLD_NOMUSU|C|20|0|Nome|Nome do Responsavel
TLD|16|TLD_SUBGAT|C|1|0|Subs.Gatilho|Substituicao do Gatilho
TLD|17|TLD_SUBDIF|C|1|0|Subs.Difusor|Substituicao do Difusor
TLD|18|TLD_MANGOT|C|1|0|Mangote|Mangote
TLD|19|TLD_VALSEG|C|1|0|Valvula Seg.|Valvula de Seguranca
TLD|20|TLD_VALCOM|C|1|0|Valvula Comp|Valvula Completa
TLD|21|TLD_VALCIL|C|1|0|Valvula Cili|Valvula Cilindro Adic.
TLD|22|TLD_PINTUR|C|1|0|Pintura|Pintura
TLD|23|TLD_MANOME|C|1|0|Manometro|Manometro
TLD|24|TLD_HIDROS|C|1|0|Teste Hidros|Teste Hidrostatico
TLD|25|TLD_RECARG|C|1|0|Recarregado|Recarregado
TLD|26|TLD_USAINC|C|1|0|Usado Incend|Usado Incendio
TLD|27|TLD_USAINS|C|1|0|Usado Instru|Usado Instrucao
TLD|28|TLD_DIVERS|C|1|0|Diversos|Diversos
TLD|29|TLD_DTRECA|D|8|0|Data Recarga|Data da Recarga
TLD|30|TLD_OBSERV|M|10|0|Observação|Observacao
TLD|31|TLD_RECEBI|C|1|0|Recebido|Extintor Recebido
--- ### TLG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLG|01|TLG_FILIAL|C|6|0|Filial|Filial
TLG|02|TLG_GRUPO|C|3|0|Codigo Grupo|Codigo Grupo
TLG|03|TLG_DESCRI|C|220|0|Descricao|Descricao
TLG|04|TLG_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TLH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLH|01|TLH_FILIAL|C|6|0|Filial|Filial
TLH|02|TLH_SIPAT|C|6|0|SIPAT|SIPAT
TLH|03|TLH_NOME|C|60|0|Nome SIPAT|Nome SIPAT
TLH|04|TLH_DTINI|D|8|0|Data Início|Data Inicio
TLH|05|TLH_DTFIM|D|8|0|Data Fim|Data Fim
TLH|06|TLH_MANDAT|C|6|0|Mandato|Mandato
TLH|07|TLH_DESCRI|M|10|0|Descrição|Descrição
--- ### TLI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLI|01|TLI_FILIAL|C|6|0|Filial|Filial
TLI|02|TLI_SIPAT|C|6|0|SIPAT|SIPAT
TLI|03|TLI_NSIPAT|C|20|0|Nome SIPAT|Nome SIPAT
TLI|04|TLI_DTPROG|D|8|0|Data Evento|Data Evento
TLI|05|TLI_HRPROG|C|5|0|Hora Inicio|Hora Inicio
TLI|06|TLI_HRFIM|C|5|0|Hora Fim|Hora Fim
TLI|07|TLI_LOCAL|C|60|0|Local|Local
TLI|08|TLI_DESCRI|C|60|0|Nome Evento|Nome Evento
TLI|09|TLI_INDRES|C|1|0|Ind. Respon.|Ind. Respon.
TLI|10|TLI_CODRES|C|6|0|Cod. Respon.|Cod. Respon.
TLI|11|TLI_NOMRES|C|40|0|Responsavel|Responsavel
TLI|12|TLI_OBSERV|M|10|0|Observacoes|Observacoes
--- ### TLJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLJ|01|TLJ_FILIAL|C|6|0|Filial|Filial do Sistema
TLJ|02|TLJ_MANDAT|C|6|0|Mandato|Mandato
TLJ|03|TLJ_CC|C|9|0|Centro Custo|Centro de Custo
TLJ|04|TLJ_NOMECC|C|20|0|Desc. C.C.|Desc. C.C.
TLJ|05|TLJ_AREA|C|9|0|Área|Área
TLJ|06|TLJ_NOAREA|C|20|0|Nome Área|Nome Área
--- ### TLK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLK|01|TLK_FILIAL|C|6|0|Filial|Filial do Sistema
TLK|02|TLK_AGENTE|C|9|0|Agente|Codigo do Agente
TLK|03|TLK_NOMAGE|C|20|0|Nome Agente|Nome do Agente
TLK|04|TLK_DEQTDE|N|10|4|Intensidade|Intensidade
TLK|05|TLK_HRLIMI|C|5|0|Tempo Máximo|Tempo Maximo
TLK|06|TLK_GRAU|C|1|0|Grau Insal.|Grau Insalubridade
TLK|07|TLK_DEQTCH|C|9|0|Intensidad.|Intensidad.
TLK|08|TLK_NORMAT|C|1|0|Normativa|Normativa
--- ### TLL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLL|01|TLL_FILIAL|C|6|0|Filial|Filial do Sistema
TLL|02|TLL_CC|C|9|0|Obra|Codigo Obra
TLL|03|TLL_NOMECC|C|60|0|Nome da Obra|Nome da Obra
TLL|04|TLL_ENDERE|C|50|0|Endereço|Endereco da Obra
TLL|05|TLL_BAIRRO|C|25|0|Bairro|Bairro da Obra
TLL|06|TLL_MUN|C|30|0|Município|Municipio da Obra
TLL|07|TLL_ESTADO|C|2|0|Estado|Estado da Obra
TLL|08|TLL_CODCON|C|6|0|Contratante|Contratante da Obra
TLL|09|TLL_LOJCON|C|2|0|Loja|Loja do Contratante
TLL|10|TLL_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
TLL|11|TLL_TIPO|C|3|0|Tipo da Obra|Tipo da Obra
TLL|12|TLL_DESTIP|C|20|0|Descr. Tipo|Descricao Tipo Obra
TLL|13|TLL_NUMERO|N|6|0|Nº Max.Trab.|Nº Maximo Trabalhadores
TLL|14|TLL_DTINIP|D|8|0|Início Prev.|Data Inicio Previsto
TLL|15|TLL_DTFIMP|D|8|0|Term. Prev.|Data Fim Previsto
TLL|16|TLL_DTINIR|D|8|0|Início Real.|Data Inicio Realizado
TLL|17|TLL_DTFIMR|D|8|0|Term. Real.|Data Fim Realizado
TLL|18|TLL_DESCLO|C|6|0|Carac. Local|Caracteristica Local
TLL|19|TLL_MEMOLO|M|10|0|Carac. Local|Caracteristica Local
TLL|20|TLL_DESCEM|C|6|0|Empreendim.|Empreendimento
TLL|21|TLL_MEMOEM|M|10|0|Empreendim.|Empreendimento
TLL|22|TLL_DESCIN|C|6|0|Ins.Eletrica|Instalacao Eletrica
TLL|23|TLL_MEMOIN|M|10|0|Inst. Elétr.|Instalacao Eletrica
TLL|24|TLL_DESCPE|C|6|0|Proc.Emergen|Procedimento Emergencia
TLL|25|TLL_MEMOPE|M|10|0|Proc. Emerg.|Procedimento Emergencia
TLL|26|TLL_DESCSI|C|6|0|Sinalizacao|Sinalizacao
TLL|27|TLL_MEMOSI|M|10|0|Sinalizacao|Sinalizacao
--- ### TLM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLM|01|TLM_FILIAL|C|6|0|Filial|Filial do Sistema
TLM|02|TLM_CC|C|9|0|Obra|Obra
TLM|03|TLM_NOMECC|C|30|0|Nome da Obra|Nome da Obra
TLM|04|TLM_FASE|C|3|0|Fase da Obra|Fase da Obra
TLM|05|TLM_DESCRI|C|20|0|Nome Fase|Nome da Fase
TLM|06|TLM_SUBFAS|C|3|0|Sub-fase|Sub-fase
TLM|07|TLM_DESSUB|C|20|0|Nom Sub-Fase|Nome Sub-Fase
TLM|08|TLM_DTINIP|D|8|0|Início Prev.|Data Inicio Previsto
TLM|09|TLM_DTFIMP|D|8|0|Fim Prev.|Data Fim Previsto
TLM|10|TLM_DTINIR|D|8|0|Início Real.|Data Inicio Realizado
TLM|11|TLM_DTFIMR|D|8|0|Fim Real.|Data Fim Realizado
--- ### TLN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLN|01|TLN_FILIAL|C|6|0|Filial|Filial do Sistema
TLN|02|TLN_CC|C|9|0|Obra|Obra
TLN|03|TLN_NOMECC|C|20|0|Nome da Obra|Nome da Obra
TLN|04|TLN_AREA|C|3|0|Área de Viv.|Área Vivencia
TLN|05|TLN_DESCRI|C|20|0|Descrição|Descrição
TLN|06|TLN_CARACT|C|6|0|Detalhamento|Detalhamento
TLN|07|TLN_MEMO1|M|10|0|Detalhamento|Detalhamento
--- ### TLO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLO|01|TLO_FILIAL|C|6|0|Filial|Filial do Sistema
TLO|02|TLO_CC|C|9|0|Obra|Obra
TLO|03|TLO_ANEXO|C|5|0|Anexo|Anexo
TLO|04|TLO_TIPO|C|1|0|Tipo Anexo|Tipo Anexo
TLO|05|TLO_CODIGO|C|15|0|Código|Codigo
TLO|06|TLO_TITULO|C|40|0|Título|Titulo do Anexo
TLO|07|TLO_BITMAP|C|8|0|Imagem|Imagem
--- ### TLP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLP|01|TLP_FILIAL|C|6|0|Filial|Filial do Sistema
TLP|02|TLP_CC|C|9|0|Obra|Obra
TLP|03|TLP_FASE|C|3|0|Fase da Obra|Fase da Obra
TLP|04|TLP_SUBFAS|C|3|0|Sub-fase|Sub-fase
TLP|05|TLP_CODTAR|C|6|0|Tarefa|Codigo da Tarefa
TLP|06|TLP_DESATI|C|20|0|Nome Ativid.|Nome Atividade
--- ### TLQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLQ|01|TLQ_FILIAL|C|6|0|Filial|Filial do Sistema
TLQ|02|TLQ_TIPO|C|3|0|Tipo de Obra|Tipo de Obra
TLQ|03|TLQ_DESTIP|C|60|0|Descrição|Descricao do Tipo
--- ### TLR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLR|01|TLR_FILIAL|C|6|0|Filial|Filial do Sistema
TLR|02|TLR_CC|C|9|0|Obra|Obra
TLR|03|TLR_NOMECC|C|20|0|Nome da Obra|Nome da Obra
TLR|04|TLR_CODEQU|C|12|0|Equipamento|Equipamento
TLR|05|TLR_DESCRI|C|20|0|Descricao|Descricao
TLR|06|TLR_OBSERV|C|6|0|Observacao|Observacao
TLR|07|TLR_MEMO1|M|10|0|Observacao|Observacao
--- ### TLS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLS|01|TLS_FILIAL|C|6|0|Filial|Filial do Sistema
TLS|02|TLS_AREA|C|3|0|Area Vivenc.|Area Vivencia
TLS|03|TLS_DESVIV|C|60|0|Descricao|Descricao da Area
TLS|04|TLS_CODMEM|C|6|0|Caract.|Caracteristica Padrao
TLS|05|TLS_DESMEM|M|10|0|Caract.|Caracteristica Padrao
--- ### TLW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLW|01|TLW_FILIAL|C|6|0|Filial|Filial do Sistema
TLW|02|TLW_FORNEC|C|6|0|Fornecedor|Fornecedor
TLW|03|TLW_LOJA|C|2|0|Loja|Loja
TLW|04|TLW_CODEPI|C|15|0|EPI|EPI
TLW|05|TLW_NUMCAP|C|12|0|Num. C. A.|Num. C. A.
TLW|06|TLW_MAT|C|6|0|Matricula|Matricula
TLW|07|TLW_DTENTR|D|8|0|Data Entrega|Data Entrega
TLW|08|TLW_HRENTR|C|5|0|Hora Entrega|Hora Entrega
TLW|09|TLW_DTDEVO|D|8|0|Data Dev.|Dt Devolucao
TLW|10|TLW_HRDEVO|C|5|0|Hora Dev.|Hr Devolucao
TLW|11|TLW_QTDEVO|N|6|2|Quant. Dev.|Quant. Devo.
TLW|12|TLW_LOCAL|C|2|0|Almoxarifado|Almoxarifado
TLW|13|TLW_TIPODV|C|1|0|Repor Estoq.|Repor Estoque
TLW|14|TLW_NUMSEQ|C|6|0|Num.Seq.SD3|Num.Seq.SD3
--- ### TLX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLX|01|TLX_FILIAL|C|6|0|Filial|Filial
TLX|02|TLX_PROGRA|C|6|0|Programacao|Programacao de Epi
TLX|03|TLX_DTGERA|D|8|0|Data Geracao|Data da Geracao
TLX|04|TLX_DTINI|D|8|0|Data Inicio|Data de Inicio
TLX|05|TLX_DTFIM|D|8|0|Data Fim|Data Fim
TLX|06|TLX_INDCLA|C|1|0|Classificar|Classificar por?
TLX|07|TLX_TIPOSA|C|1|0|Tipo Ger. SA|Tipo Geracao de SA
TLX|08|TLX_FUNINI|C|6|0|Func. Inic.|Funcionario Inicio
TLX|09|TLX_FUNFIM|C|6|0|Func. Fim|Funcionario Fim
--- ### TLY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLY|01|TLY_FILIAL|C|6|0|Filial|Filial
TLY|02|TLY_PROGRA|C|6|0|Programacao|Nº Programacao
TLY|03|TLY_ITEM|C|6|0|Item|Item da Programacao
TLY|04|TLY_FILMAT|C|6|0|Filial Func.|Filial do Funcionario
TLY|05|TLY_MAT|C|6|0|Matricula|Matricula do Funcionario
TLY|06|TLY_CODEPI|C|15|0|Codigo Epi|Codigo do Epi
TLY|07|TLY_QUANTI|N|6|2|Quantidade|Quantidade Necessaria
TLY|08|TLY_OK|C|2|0|Marcado?|Marcado?
TLY|09|TLY_NUMSA|C|6|0|Numero S.A.|Numero S.A.
TLY|10|TLY_ITEMSA|C|2|0|Item S.A.|Item S.A.
TLY|11|TLY_DATASA|D|8|0|Dt. Necessid|Data da Necessidade
TLY|12|TLY_FORNEC|C|6|0|Fornecedor|Fornecedor
TLY|13|TLY_LOJA|C|2|0|Loja|Loja
TLY|14|TLY_NUMCAP|C|12|0|Numero C.A.|Numero C.A.
--- ### TLZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TLZ|01|TLZ_FILIAL|C|6|0|Filial|Filial do Sistema
TLZ|02|TLZ_FASE|C|3|0|Fase de Obra|Fase de Obra
TLZ|03|TLZ_DESCRI|C|40|0|Descrição|Descricao
--- ### TM0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM0|01|TM0_FILIAL|C|6|0|FILIAL|FILIAL DO SISTEMA
TM0|02|TM0_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TM0|03|TM0_CANDID|C|6|0|Candidato|Candidato a Emprego
TM0|04|TM0_FILFUN|C|6|0|Filial Func.|Filial do Funcionario
TM0|05|TM0_MAT|C|6|0|Funcionário|Matricula do Funcionario
TM0|06|TM0_NUMDEP|C|2|0|Dependente|Numero do Dependente
TM0|07|TM0_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TM0|08|TM0_DTIMPL|D|8|0|Implantação|Data Implantacao Ficha
TM0|09|TM0_DOADOR|C|1|0|Doador|Doador de Sangue
TM0|10|TM0_DTDOAC|D|8|0|Últ. Doação|Data Ultima Doacao
TM0|11|TM0_SANGUE|C|1|0|Tipo San.|Tipo de Sangue
TM0|12|TM0_FATORH|C|1|0|Fator Rh|Fator RH do Sangue
TM0|13|TM0_FICANT|C|12|0|Ficha Ant.|Ficha Anterior
TM0|14|TM0_DTNASC|D|8|0|Nascimento|Data Nascimento
TM0|15|TM0_SEXO|C|1|0|Sexo|Sexo Proprietario Ficha
TM0|16|TM0_PESO|N|7|3|Peso|Peso da Pessoa em Kg.
TM0|17|TM0_ALTURA|N|4|2|Altura|Altura da Pessoa
TM0|18|TM0_MASSA|C|20|0|Massa Corp.|Massa Corporea
TM0|19|TM0_ALTOLH|N|4|2|Alt. Olhos|Altura dos Olhos
TM0|20|TM0_LMAMIL|N|4|2|Linh. Mamila|Linha Mamilar
TM0|21|TM0_ALTPUB|N|4|2|Alt. Púbis|Altura do Pubis
TM0|22|TM0_ALTJOE|N|4|2|Alt. Joelho|Altura do Joelho
TM0|23|TM0_ALTCOT|N|4|2|Alt.Cotovelo|Altura do Cotovelo
TM0|24|TM0_TAMBRA|N|4|2|Tam. Braço|Tamanho do Braco
TM0|25|TM0_TAMANT|N|4|2|Tam. Ant.|Tamanho do Ante-Braco
TM0|26|TM0_TAMMAO|N|4|2|Tam. Mão|Tamanho da Mao
TM0|27|TM0_COMPPE|N|4|2|Comp. Pé|Comprimento do Pe
TM0|28|TM0_NUMCAL|N|2|0|Núm. Calçado|Numero do Calcado
TM0|29|TM0_TIPFIS|C|20|0|Tipo Físico|Tipo Fisico da Pessoa
TM0|30|TM0_FUMA|C|1|0|Fuma|Indicador de Fumante
TM0|31|TM0_QTCIG|N|3|0|Quant. Cig.|Quant. cigarros por dia
TM0|32|TM0_QTTEMP|N|2|0|Quantos Anos|Qtde Tempo em Anos (Fuma)
TM0|33|TM0_RG|C|15|0|R.G.|RG - Registro Geral
TM0|34|TM0_LOCFIC|C|30|0|Local Ficha|Localizacao da Ficha
TM0|35|TM0_DESCRI|M|10|0|Histórico|Antecedentes Profis.
TM0|36|TM0_CODFUN|C|5|0|Função|Codigo da Funcao
TM0|37|TM0_DESCFU|C|20|0|Descrição|Descrição Função
TM0|38|TM0_CC|C|9|0|Centro Custo|Codigo do centro de custo
TM0|39|TM0_CCDESC|C|40|0|Descrição|Descrição centro de custo
TM0|40|TM0_DEPTO|C|9|0|Departamento|Codigo Departamento
TM0|41|TM0_DESCDP|C|30|0|Descrição|Descricao Departamento
TM0|42|TM0_COROLH|C|1|0|Cor Olhos|Cor dos Olhos
TM0|43|TM0_CORCAB|C|1|0|Cor Cabelos|Cor dos Cabelos
TM0|44|TM0_CORPEL|C|1|0|Cor Pele|Cor da Pele
TM0|45|TM0_NUMCP|C|10|0|Núm. Cart.|Numero Carteira Proficion
TM0|46|TM0_SERCP|C|10|0|Sér. Cart.|Serie da Carteira Prof.
TM0|47|TM0_UFCP|C|2|0|U.F. Cart.|UF da Carteira Prof.
TM0|48|TM0_CLIENT|C|6|0|Cliente|Codigo do Cliente
TM0|49|TM0_LOJA|C|2|0|Loja|Loja do Cliente
TM0|50|TM0_NOMCLI|C|80|0|Nome Cliente|Nome do Cliente
TM0|51|TM0_ESTCIV|C|1|0|Estado Civil|Estado Civil
TM0|52|TM0_CPF|C|11|0|C.P.F.|CPF
TM0|53|TM0_BITMAP|C|8|0|Foto|Foto
TM0|54|TM0_CODCID|C|8|0|CID Def.|CID da Deficiência
TM0|55|TM0_TIPDEF|C|1|0|Tipo Def.|Tipo de Deficiência
TM0|56|TM0_DOENCA|C|150|0|Descrição|Descrição Doença
TM0|57|TM0_INDBIO|C|1|0|Biometria|Biometria
TM0|58|TM0_CTPCD|C|1|0|Cota Def.|Cota de Deficiente
TM0|59|TM0_REGBIO|M|10|0|Reg. Biom.|Registro Biométrico
TM0|60|TM0_NOMSOC|C|70|0|Nome Social|Nome Social
--- ### TM1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM1|01|TM1_FILIAL|C|6|0|Filial|FILIAL DO SISTEMA
TM1|02|TM1_CODMED|C|15|0|Medicamento|Codigo do Medicamento
TM1|03|TM1_NOMEDI|C|35|0|Nome|Nome do Medicamento
TM1|04|TM1_QTINVE|N|9|2|Qtd. Invent.|Quantidade no Inventario
TM1|05|TM1_QTATUA|N|9|2|Quant. Atual|Quantidade atual em estoq
TM1|06|TM1_UNIDAD|C|6|0|Unid. Medida|Unidade de Medida
TM1|07|TM1_DESUNI|C|20|0|Descr. Unid.|Descricao Unidade Medida
TM1|08|TM1_INDEST|C|1|0|Cont. Estoq.|Controla Estoque
TM1|09|TM1_QTMINI|N|9|2|Quant. Min.|Quantidade Minima Estoq.
TM1|10|TM1_DTINVE|D|8|0|Dt. Invent.|Data do Inventario
TM1|11|TM1_INDUSO|C|1|0|Tipo Uso|Indica Tipo de Uso
TM1|12|TM1_DESUSO|C|80|0|Indicacao|Indicacao de Uso
TM1|13|TM1_CONIND|C|80|0|Contra Ind.|Contra Indicacao
TM1|14|TM1_DTVALI|D|8|0|Data Valid.|Dt. Validade Medicamento
TM1|15|TM1_INDAMB|C|1|0|Med. Ambul.|Medicamento Ambulatorio
TM1|16|TM1_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TM2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM2|01|TM2_FILIAL|C|6|0|Filial|FILIAL DO SISTEMA
TM2|02|TM2_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TM2|03|TM2_NOMFIC|C|80|0|Nome|Nome Paciente
TM2|04|TM2_DTCONS|D|8|0|Consulta|Data da Consulta Medica
TM2|05|TM2_HRCONS|C|5|0|Consulta|Hora da Consulta Medica
TM2|06|TM2_CODMED|C|15|0|Medicamento|Codigo do Medicamento
TM2|07|TM2_NOMEDI|C|20|0|Nome|Nome do Medicamento
TM2|08|TM2_QTUTIL|N|9|2|Utilizada|Quantidade Utilizada
TM2|09|TM2_QTUTES|N|9|2|Baixar|Qtd. Baixar do Estoque
TM2|10|TM2_UNIDAD|C|6|0|Medida|Unidade de Medida
TM2|11|TM2_DESUNI|C|20|0|Descrição|Descricao Unidade Medida
TM2|12|TM2_SEQMOV|C|6|0|Movimentação|Sequencia Movto Estoque
TM2|13|TM2_PSOLOG|C|80|0|Posologia|Descricao da Posologia
TM2|14|TM2_INDREC|C|1|0|Imprime|Inclui Medicam. Receita
TM2|15|TM2_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TM2|16|TM2_DOSE|C|20|0|Dose|Dose do medicamento
TM2|17|TM2_FORFAR|C|25|0|Forma|Forma farmacêutica
TM2|18|TM2_QTDATU|N|9|2|Quant. Atual|Quantidade atual
TM2|19|TM2_QTDMIN|N|9|2|Quant. Mín.|Quantidade mínima
--- ### TM3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM3|01|TM3_FILIAL|C|6|0|Filial|FILIAL DO SISTEMA
TM3|02|TM3_SEQMOV|C|6|0|Seq. Movim.|Sequencia do Movimento
TM3|03|TM3_INDMOV|C|1|0|Cod. Movto|Codigo Movimento Estoque
TM3|04|TM3_CODMED|C|15|0|Medicamento|Codigo do Medicamento
TM3|05|TM3_NOMEDI|C|20|0|Nome|Nome do Medicamento
TM3|06|TM3_QTMOVI|N|9|2|Quant.Movim.|Quantidade Movimentada
TM3|07|TM3_UNIDAD|C|6|0|Unid. Medida|Unidade de Medida
TM3|08|TM3_DTMOVI|D|8|0|Data Movim.|Data do Movimeto Estoque
TM3|09|TM3_DTVALI|D|8|0|Data Valid.|Data Validade
TM3|10|TM3_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TM4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM4|01|TM4_FILIAL|C|6|0|Filial|FILIAL DO SISTEMA
TM4|02|TM4_EXAME|C|6|0|Exame|Codigo do Exame
TM4|03|TM4_NOMEXA|C|40|0|Nome Exame|Nome do Exame Medico
TM4|04|TM4_DESEXA|C|100|0|Descrição|Descricao detalhes Exame
TM4|05|TM4_INDRES|C|1|0|Ind. Result.|Indica Tipo Resultado
TM4|06|TM4_ADMISS|C|1|0|Admissional?|Obrigatorio na Admissao?
TM4|07|TM4_DEMISS|C|1|0|Demissional?|Obrigatorio na Demissao?
TM4|08|TM4_RETORN|C|1|0|Ret. Trab. ?|Obrigatorio Ret.Trabalho?
TM4|09|TM4_PREPAR|C|6|0|Prep. Exame|Preparação para o Exame
TM4|10|TM4_MEMOPR|M|10|0|Prep. Exame|Preparação para o Exame
TM4|11|TM4_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TM4|12|TM4_TUSS|C|8|0|TUSS|Código TUSS
TM4|13|TM4_DESTUS|C|200|0|Desc. TUSS|Descrição na TUSS
TM4|14|TM4_OFTIPO|C|1|0|Tipo Oftalm.|Tipo Oftalmológico
TM4|15|TM4_PROCRE|C|4|0|Proc. Realiz|Procedimento Realizado
--- ### TM5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM5|01|TM5_FILIAL|C|6|0|Filial|Filial do Sistema
TM5|02|TM5_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TM5|03|TM5_NOMFIC|C|80|0|Nome|Nome Paciente
TM5|04|TM5_EXAME|C|6|0|Cod. Exame|Codigo do Exame Medico
TM5|05|TM5_NOMEXA|C|40|0|Nome Exame|Nome do Exame Medico
TM5|06|TM5_DTPROG|D|8|0|Data Exame|Data Programacao Exame
TM5|07|TM5_FORNEC|C|6|0|Fornecedor|Codigo da Entidade Extern
TM5|08|TM5_LOJA|C|2|0|Loja Fornec.|Loja do Fornecedor
TM5|09|TM5_FILFUN|C|6|0|Filial Func.|Filial do Funcionario
TM5|10|TM5_MAT|C|6|0|Matricula|Matricula do Funcionario
TM5|11|TM5_ORIGEX|C|1|0|Origem Exame|Origem do Exame
TM5|12|TM5_PCMSO|C|6|0|Num.PCMSO|Numero do PCMSO
TM5|13|TM5_DTRESU|D|8|0|Data Result.|Data Resultado Exame
TM5|14|TM5_CODRES|C|4|0|Conclusão|Cod Conclusao Resultado
TM5|15|TM5_RESULT|C|50|0|Descrição|Descricao do Resultado
TM5|16|TM5_INDRES|C|1|0|Ind. Result.|Indicador Resultado Exame
TM5|17|TM5_NATEXA|C|1|0|Natureza|Indicador Natureaza Exame
TM5|18|TM5_OBSERV|C|80|0|Obs. Result.|Observacao Sobre Result.
TM5|19|TM5_CC|C|9|0|Centro Custo|Codigo do Centro de Custo
TM5|20|TM5_CODFUN|C|5|0|Cod. Funcao|Funcao do Funcionario
TM5|21|TM5_CBO|C|6|0|C.B.O.|C.B.O.
TM5|22|TM5_NUMASO|C|6|0|Num. ASO|Numero do ASO
TM5|23|TM5_TNOTRA|C|3|0|Turno Trab.|Codigo do Turno Trabalho
TM5|24|TM5_DESRES|M|10|0|Det. Resum.|Detalhes Resultado Exame
TM5|25|TM5_EXAREF|C|1|0|Referencial?|Exame Referencial?
TM5|26|TM5_INDAGR|C|1|0|Agravamento?|Agravamento?
TM5|27|TM5_ORIAGR|C|1|0|Origem Agrav|Origem Agravamento
TM5|28|TM5_HRPROG|C|5|0|Hor. Prog.|Horario Programacao
TM5|29|TM5_USERGI|C|17|0|Log de Inclu|Log de Inclusao
TM5|30|TM5_USERGA|C|17|0|Log de Alter|Log de Alteracao
TM5|31|TM5_CODDET|C|17|0|Seq. Exame|Cód. Sequencial do Exame
TM5|32|TM5_USUARI|C|12|0|Med. Exam.|Médico Examinador
TM5|33|TM5_NOMMED|C|80|0|Nome Med.|Nome do Médico
--- ### TM6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM6|01|TM6_FILIAL|C|6|0|Filial|Filial do Sistema
TM6|02|TM6_NUMFIC|C|9|0|Ficha Medica|Numero da Ficha Medica
TM6|03|TM6_DTPROG|D|8|0|Data Exame|Data Programacao Exame
TM6|04|TM6_EXAME|C|6|0|Exame|Codigo do Exame Medico
TM6|05|TM6_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TM6|06|TM6_ITEM|C|6|0|Item Exame|Codigo do item Exame
TM6|07|TM6_NOMITE|C|20|0|Nome Item|Nome do Item
TM6|08|TM6_QTDITE|N|13|3|Qtde Item|Quantidade Encontrada
TM6|09|TM6_DESRES|C|40|0|Desc.Result.|Descricao do Resultado
TM6|10|TM6_HRPROG|C|5|0|Horario Prog|Horario Programacao
--- ### TM7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM7|01|TM7_FILIAL|C|6|0|Filial|Filial do Sistema
TM7|02|TM7_EQPTO|C|6|0|Equipamento|Cod.Equipamento Medicao
TM7|03|TM7_NOEQTO|C|40|0|Descrição|Nome Equipamento
TM7|04|TM7_DTAFER|D|8|0|Aferição|Data de Afericao
TM7|05|TM7_NOMFAB|C|40|0|Fabricante|Nome Empresa Fabricante
TM7|06|TM7_DTCALI|D|8|0|Calibracao|Data de Calibracao Eqpto
TM7|07|TM7_DTVALI|D|8|0|Validade|Data Validade da Calib.
--- ### TM8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM8|01|TM8_FILIAL|C|6|0|FILIAL|FILIAL DO SISTEMA
TM8|02|TM8_EXAME|C|6|0|Exame|Codigo do Exame Medico
TM8|03|TM8_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TM8|04|TM8_ITEM|C|6|0|Item Exame|Codigo do item Exame
TM8|05|TM8_NOMITE|C|25|0|Nome Item|Nome do Subitem do Exame
TM8|06|TM8_SEXO|C|1|0|Sexo|Sexo
TM8|07|TM8_UNIDAD|C|4|0|Unid. Medid.|Unidade de Medida do Item
TM8|08|TM8_LIMMIN|N|13|3|Lim. Minimo|Limite Minimo Normalidade
TM8|09|TM8_LIMMAX|N|13|3|Lim. Maximo|Limite Maximo Normalidade
--- ### TM9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TM9|01|TM9_FILIAL|C|6|0|Filial|Filial do Sistema
TM9|02|TM9_NUMFIC|C|9|0|Ficha Medica|Numero da Ficha Medica
TM9|03|TM9_EXAME|C|6|0|Exame|Codigo do Exame Medico
TM9|04|TM9_DTPROG|D|8|0|Data Exame|Data Programacao Exame
TM9|05|TM9_EQPTO|C|6|0|Equipamento|Cod.Equipamento Medicao
TM9|06|TM9_NOEQTO|C|20|0|Nome Eqpto|Nomedo Equipamento
TM9|07|TM9_REPOUS|N|2|0|Hrs Repouso|Quantidade Horas Repouso
TM9|08|TM9_ODREFE|C|1|0|Refer. O.D.|Ind.Exame Referencia O.D
TM9|09|TM9_USURES|C|12|0|Responsavel|Responsavel
TM9|10|TM9_OD025K|N|3|0|Qtde 0,25KHz|Qtde Decibeis 0,25 KHz OD
TM9|11|TM9_OD05KH|N|3|0|Qtde 0,5 KHz|Qtde Decibeis 0,5 KHz O.D
TM9|12|TM9_OD1KHZ|N|3|0|Qtde 1 KHz|Qtde Decibeis 1 KHZ O.D.
TM9|13|TM9_OD2KHZ|N|3|0|Qtde 2 KHz|Qtde Decibeis 2 KHz O.D.
TM9|14|TM9_OD3KHZ|N|3|0|Qtde 3 KHz|Qtde Decibeis 3 KHz O.D.
TM9|15|TM9_OD4KHZ|N|3|0|Qtde 4 KHz|Qtde Decibeis 4 KHz O.D.
TM9|16|TM9_OD6KHZ|N|3|0|Qtde 6 KHz|Qtde Decibeis 6 KHz O.D.
TM9|17|TM9_OD8KHZ|N|3|0|Qtde 8 KHz|Qtde Decibeis 8 KHz O.D.
TM9|18|TM9_ODMEAT|C|20|0|Meatoscopia|Exame Meatoscopia O.D.
TM9|19|TM9_ODRECF|N|4|0|Rec.Fala O.D|Reconhec Fala em KHz
TM9|20|TM9_ODREMO|N|3|0|Qt.Db.Monos|Qtde Db Para Monossilaba
TM9|21|TM9_ODREDI|N|3|0|Qt.Db.Dissil|Qtde Db Para Dissilaba
TM9|22|TM9_ODRESU|C|1|0|Result O.D.|Resultado O.D.
TM9|23|TM9_OEREFE|C|1|0|Refer. O.E.|Indicador Referencia O.E.
TM9|24|TM9_OE025K|N|3|0|Qtde 0,25KHz|Qtde Decibeis 0,25 KHz O
TM9|25|TM9_OE05KH|N|3|0|Qtde 0,5 KHz|Qtde Decibeis 0,5 MHz O.E
TM9|26|TM9_OE1KHZ|N|3|0|Qtde 1 KHz|Qtde Decibeis 1 KHz O.E
TM9|27|TM9_OE2KHZ|N|3|0|Qtde 2 KHz|Qtde Decibeis 2 KHz O.E
TM9|28|TM9_OE3KHZ|N|3|0|Qtde 3 KHz|Qtde Decibeis 3 KHz O.E
TM9|29|TM9_OE4KHZ|N|3|0|Qtde 4 KHz|Qtde Decibeis 4 KHz O.E
TM9|30|TM9_OE6KHZ|N|3|0|Qtde 6 KHz|Qtde Decibeis 6 MHz O.E
TM9|31|TM9_OE8KHZ|N|3|0|Qtde 8 KHz|Qtde Decibeis 8 MHz O.E
TM9|32|TM9_OERESU|C|1|0|Result. O.E.|Resultado O.E
TM9|33|TM9_OEMEAT|C|20|0|Meatoscopia|Exame Meatoscopia O.E.
TM9|34|TM9_OERECF|N|4|0|Rec.Fala O.E|Reconhecimento Fala O.E.
TM9|35|TM9_OEREMO|N|3|0|Qt.Db.Monos|Monossilaba O.E.
TM9|36|TM9_OEREDI|N|3|0|Qt.Db.Dissil|Dissilaba O.E.
TM9|37|TM9_INDVIA|C|1|0|Via Conducao|Via de Conducao
TM9|38|TM9_DTAFER|D|8|0|Dt. Afericao|Data de Afericao
TM9|39|TM9_DTCALI|D|8|0|Dt. Calibrac|Data Calibracao
TM9|40|TM9_ODORIG|C|1|0|Anormal. O.D|Origem Anormalidade O.D.
TM9|41|TM9_OEORIG|C|1|0|Anormal. O.E|Origem Anormalidade O. E.
TM9|42|TM9_ODMERL|C|1|0|Merluzi.O.D.|Merluzzi O. Direita
TM9|43|TM9_HRPROG|C|5|0|Horario Prog|Horario Programacao
TM9|44|TM9_OEMERL|C|1|0|Merluzi.O.E.|Merluzzi O. Esquerda
TM9|45|TM9_ODMA25|N|3|0|Qtde 0,25KH|Qtde Decibeis 0,25 KHz OD
TM9|46|TM9_ODMA50|N|3|0|Qtde 0,5 KHz|Qtde Decibeis 0,5 KHz O.D
TM9|47|TM9_ODMA10|N|3|0|Qtde 1 KHz|Qtde Decibeis 1 KHZ O.D.
TM9|48|TM9_ODMA20|N|3|0|Qtde 2 KHz|Qtde Decibeis 2 KHz O.D.
TM9|49|TM9_ODMA30|N|3|0|Qtde 3 KHz|Qtde Decibeis 3 KHz O.D.
TM9|50|TM9_ODMA40|N|3|0|Qtde 4 KHz|Qtde Decibeis 4 KHz O.D.
TM9|51|TM9_ODMA60|N|3|0|Qtde 6 KHz|Qtde Decibeis 6 KHz O.D.
TM9|52|TM9_ODMA80|N|3|0|Qtde 8 KHz|Qtde Decibeis 8 KHz O.D.
TM9|53|TM9_OEMA25|N|3|0|Qtde 0,25KHz|Qtde Decibeis 0,25 KHz OD
TM9|54|TM9_OEMA50|N|3|0|Qtde 0,5 KHz|Qtde Decibeis 0,5 KHz O.D
TM9|55|TM9_OEMA10|N|3|0|Qtde 1 KHz|Qtde Decibeis 1 KHZ O.D.
TM9|56|TM9_OEMA20|N|3|0|Qtde 2 KHz|Qtde Decibeis 2 KHz O.D.
TM9|57|TM9_OEMA30|N|3|0|Qtde 3 KHz|Qtde Decibeis 3 KHz O.D.
TM9|58|TM9_OEMA40|N|3|0|Qtde 4 KHz|Qtde Decibeis 4 KHz O.D.
TM9|59|TM9_OEMA60|N|3|0|Qtde 6 KHz|Qtde Decibeis 6 KHz O.D.
TM9|60|TM9_OEMA80|N|3|0|Qtde 8 KHz|Qtde Decibeis 8 KHz O.D.
TM9|61|TM9_ODMED5|N|6|2|Med[.5,1,2]|Média OD [.5,1,2]
TM9|62|TM9_ODMED3|N|6|2|Med[3,4,6]|Média OD [3,4,6]
TM9|63|TM9_OEMED5|N|6|2|Med[.5,1,2]|Média OE [.5,1,2]
TM9|64|TM9_OEMED3|N|6|2|Med[3,4,6]|Média OE [3,4,6]
TM9|65|TM9_ODCLIN|C|1|0|Clinico O.D.|Clinico O. Direita
TM9|66|TM9_ODPERE|C|1|0|Pereira O.D.|Pereira O. Direita
TM9|67|TM9_ODCOST|C|1|0|Costa 92 OD|Costa 92 O. Direita
TM9|68|TM9_ODINSS|C|1|0|INSS OD|INSS O. Direita
TM9|69|TM9_OECLIN|C|1|0|Clinico O.E.|Clinico O. Esquerda
TM9|70|TM9_OEPERE|C|1|0|Pereira O.E.|Pereira O. Esquerda
TM9|71|TM9_OECOST|C|1|0|Costa 92 OE|Costa 92 O. Esquerda
TM9|72|TM9_OEINSS|C|1|0|INSS OE|INSS O. Esquerda
TM9|73|TM9_ODTIPE|C|1|0|Tip.Perda OD|Tipo de Perda Or. Direita
TM9|74|TM9_OETIPE|C|1|0|Tip.Perda OE|Tipo de Perda Or. Esquerd
TM9|75|TM9_ODAS25|C|3|0|Aus. OD .25|Ausente OD .25
TM9|76|TM9_ODAS50|C|3|0|Aus. OD .50|Ausente OD .50
TM9|77|TM9_ODAS10|C|3|0|Aus. OD 1|Ausente OD 1
TM9|78|TM9_ODAS20|C|3|0|Aus. OD 2|Ausente OD 2
TM9|79|TM9_ODAS30|C|3|0|Aus. OD 3|Ausente OD 3
TM9|80|TM9_ODAS40|C|3|0|Aus. OD 4|Ausente OD 4
TM9|81|TM9_ODAS60|C|3|0|Aus. OD 6|Ausente OD 6
TM9|82|TM9_ODAS80|C|3|0|Aus. OD 8|Ausente OD 8
TM9|83|TM9_OEAS25|C|3|0|Aus. OE .25|Ausente OE .25
TM9|84|TM9_OEAS50|C|3|0|Aus. OE .50|Ausente OE .50
TM9|85|TM9_OEAS10|C|3|0|Aus. OE 1|Ausente OE 1
TM9|86|TM9_OEAS20|C|3|0|Aus. OE 2|Ausente OE 2
TM9|87|TM9_OEAS30|C|3|0|Aus. OE 3|Ausente OE 3
TM9|88|TM9_OEAS40|C|3|0|Aus. OE 4|Ausente OE 4
TM9|89|TM9_OEAS60|C|3|0|Aus. OE 6|Ausente OE 6
TM9|90|TM9_OEAS80|C|3|0|Aus. OE 8|Ausente OE 8
TM9|91|TM9_ODLMIN|C|3|0|Mas.Min.O.D.|Mas.Min.O.D.
TM9|92|TM9_ODLMAX|C|3|0|Mas.Max.O.D.|Mas.Max.O.D.
TM9|93|TM9_OELMIN|C|3|0|Mas.Min.O.E.|Mas.Min.O.E.
TM9|94|TM9_OELMAX|C|3|0|Mas.Max.O.E.|Mas.Max.O.E.
TM9|95|TM9_ODMSRT|N|4|0|Mas.SRT O.D.|Mas.SRT O.D.
TM9|96|TM9_OEMSRT|N|4|0|Mas.SRT O.E.|Mas.SRT O.E.
TM9|97|TM9_ODSDT|N|4|0|SDT O.D.|SDT O.D.
TM9|98|TM9_OESDT|N|4|0|SDT O.E.|SDT O.E.
TM9|99|TM9_ODMIRF|N|4|0|Mas.IRF O.D.|Mas.IRF O.D.
TM9|9A|TM9_OEMIRF|N|4|0|Mas.IRF O.E.|Mas.IRF O.E.
--- ### TMA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMA|01|TMA_FILIAL|C|6|0|Filial|Filial do Sistema
TMA|02|TMA_AGENTE|C|9|0|Agente Risco|Codigo do Agente de Risco
TMA|03|TMA_NOMAGE|C|40|0|Nome Agente|Nome do Agente
TMA|04|TMA_GRISCO|C|1|0|Grupo|Indicador Grupo de Risco
TMA|05|TMA_DESCRI|C|200|0|Descrição|Descr Cuidados com Agente
TMA|06|TMA_SUBATI|C|40|0|Subst. Ativa|Substancia Ativa
TMA|07|TMA_TIPADI|C|1|0|Adicional De|Adicional De
TMA|08|TMA_AVALIA|C|1|0|Avaliação|Tipo de Avaliacao
TMA|09|TMA_CLASSI|C|1|0|Classific.|Classificação dos Agentes
TMA|10|TMA_FONTES|C|80|0|Fontes Exp.|Fontes de exposição e res
TMA|11|TMA_TRANSM|C|80|0|Transmissib.|Transmissibilidade do vír
TMA|12|TMA_PROPAG|C|25|0|Meio Propag.|Meio Propagacao
TMA|13|TMA_TIPENT|C|1|0|Tipo Entrada|Tipo Entrada
TMA|14|TMA_ENTRAD|C|80|0|Descr. Entr.|Entrada do vírus
TMA|15|TMA_PATOGE|C|80|0|Patogenicid.|Patogenicidade
TMA|16|TMA_VIRULE|C|80|0|Virulência|Virulência
TMA|17|TMA_PERSIS|C|80|0|Persistência|Persistência do agente bi
TMA|18|TMA_ESTUDO|C|80|0|Estudos|Estudos epidemiológicos
TMA|19|TMA_VIASTR|C|40|0|Vias Transm.|Vias de Transmissão do Ag
TMA|20|TMA_ESOC|C|9|0|Cod. eSocial|Código eSocial
TMA|21|TMA_PATSYP|C|6|0|Patogêneses|Patogêneses
TMA|22|TMA_MPATOG|M|10|0|Patogêneses|Patogêneses
TMA|23|TMA_SINSYP|C|6|0|Sintomat.|Sintomatologia
TMA|24|TMA_MSINTO|M|10|0|Sintomat.|Sintomatologia
TMA|25|TMA_METERG|M|10|0|Met. Ergon.|Metodologia Ris. Erg.
TMA|26|TMA_CAS|C|11|0|Cód. CAS|Código elemento CAS
TMA|27|TMA_PROCES|C|21|0|Processo|Número do processo.
--- ### TMB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMB|01|TMB_FILIAL|C|6|0|Filial|Filial do Sistema
TMB|02|TMB_AGENTE|C|9|0|Agente|Codigo Agente Risco
TMB|03|TMB_NOMAGE|C|40|0|Nome Agente|Nome do Agente de Risco
TMB|04|TMB_EXAME|C|6|0|Exame|Codigo Exame Medico
TMB|05|TMB_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TMB|06|TMB_VALREF|N|10|2|Valor Refer.|Valor Referencia
TMB|07|TMB_QTIBMP|N|10|2|IBMP|IBMP
TMB|08|TMB_UNIDAD|C|6|0|Unid. Medida|Unidade de Medida
TMB|09|TMB_DESUNI|C|20|0|Descr. Unid.|Descricao Unidade Medida
TMB|10|TMB_MATBIO|C|1|0|Mat. Biolog.|Material Biologico
TMB|11|TMB_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TMB|12|TMB_ESOC|C|7|0|Cód. eSocial|Código eSocial
TMB|13|TMB_FAIXA|C|2|0|Faixa|Faixa Periódica
TMB|14|TMB_INTERP|C|1|0|Interpr.|Interpretação do Exame
--- ### TMC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMC|01|TMC_FILIAL|C|6|0|Filial|Filial do Sistema
TMC|02|TMC_NUMASO|C|6|0|Num. ASO|Numero do ASO
TMC|03|TMC_AGENTE|C|9|0|Agente|Codigo Agente risco
TMC|04|TMC_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
--- ### TMD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMD|01|TMD_FILIAL|C|6|0|Filial|Filial do Sistema
TMD|02|TMD_FORNEC|C|6|0|Fornecedor|Cod Fornecedor Exames
TMD|03|TMD_LOJA|C|2|0|Loja|Loja do Fornecedor
TMD|04|TMD_NREDUZ|C|20|0|Nome Fant.|Nome de Fantasia Fornec
TMD|05|TMD_EXAME|C|6|0|Exame|Codigo do Exame Medico
TMD|06|TMD_NOMEXA|C|40|0|Nome Exame|Nome do Exame
TMD|07|TMD_DTINIC|D|8|0|Inicio|Data Inicio Validade Prec
TMD|08|TMD_DTFIM|D|8|0|Fim|Data Fim Validade Preco
TMD|09|TMD_VALEXA|N|12|2|Valor|Valor do Exame
TMD|10|TMD_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TME
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TME|01|TME_FILIAL|C|6|0|Filial|Filial do Sistema
TME|02|TME_RESTRI|C|6|0|Restricao|Codigo da Restricao
TME|03|TME_NOMRES|C|40|0|Nome|Nome da Restricao
TME|04|TME_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMF|01|TMF_FILIAL|C|6|0|Filial|Filial do Sistema
TMF|02|TMF_RESTRI|C|6|0|Restricao|Codigo da Restricao
TMF|03|TMF_NOMRES|C|20|0|Nome Restr.|Nome da Restricao
TMF|04|TMF_DTINIC|D|8|0|Inicio|Data inicio Restricao
TMF|05|TMF_DTFIM|D|8|0|Termino|Data de Termino Restricao
TMF|06|TMF_NUMFIC|C|9|0|Ficha Medica|Numero Ficha Medica
TMF|07|TMF_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TMF|08|TMF_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMG|01|TMG_FILIAL|C|6|0|Filial|Filial do Sistema
TMG|02|TMG_QUESTI|C|6|0|Questionario|Codigo do Questionario
TMG|03|TMG_NOMQUE|C|40|0|Nome Quest.|Nome do Questionario
--- ### TMH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMH|01|TMH_FILIAL|C|6|0|Filial|Filial do Sistema
TMH|02|TMH_QUESTI|C|6|0|Quetionario|Codigo do Questionario
TMH|03|TMH_NOMQUE|C|20|0|Nome Quest.|Nome do Questionario
TMH|04|TMH_QUESTA|C|3|0|Questao|Numero da Questao
TMH|05|TMH_PERGUN|C|60|0|Pergunta|Pergunta do Questionario
TMH|06|TMH_INDSEX|C|1|0|Sexo|Indicador de Sexo
TMH|07|TMH_CODGRU|C|3|0|Grupo Perg.|Grupo Pergunta
TMH|08|TMH_COMBO|C|250|0|Editar Opc.|Editar Opcoes
TMH|09|TMH_TPLIST|C|1|0|Tipo Resp.|Tipo Resp
TMH|10|TMH_ONMEMO|C|1|0|Campo Obs.|Campo Obs.
TMH|11|TMH_COMBO2|C|250|0|Cont. Lista|Cont. Lista
TMH|12|TMH_NOMGRU|C|40|0|Nome Grupo|Nome Grupo
TMH|13|TMH_DEFAUL|C|1|0|Default|Default
TMH|14|TMH_RESPOS|M|10|0|Respostas|Respostas do Questionário
TMH|15|TMH_ORDEM|C|6|0|Ordem|Ordem
--- ### TMI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMI|01|TMI_FILIAL|C|6|0|Filial|Filial do Sistema
TMI|02|TMI_NUMFIC|C|9|0|Ficha Medica|Numero da Ficha Medica
TMI|03|TMI_NOMFIC|C|80|0|Nome|Nome da Pessoa
TMI|04|TMI_DTREAL|D|8|0|Realização|Data da Realizacao
TMI|05|TMI_QUESTI|C|6|0|Questionário|Codigo do Questionario
TMI|06|TMI_NOMQUE|C|20|0|Nome Quest.|Nome do Questionario
TMI|07|TMI_QUESTA|C|3|0|Questão|Numero da Questao
TMI|08|TMI_PERGUN|C|40|0|Pergunta|Pergunta
TMI|09|TMI_RESPOS|C|1|0|Resposta|Resposta a Pergunta
TMI|10|TMI_DESRES|C|30|0|Descrição|Resposta a Pergunta
TMI|11|TMI_QTRESP|N|9|2|Quantidade|Quantidade Respondida
TMI|12|TMI_COMRES|C|30|0|Complemento|Complemento da Resposta
TMI|13|TMI_DESCRI|M|10|0|Descrição|Descricao
TMI|14|TMI_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMJ|01|TMJ_FILIAL|C|6|0|Filial|Filial do Sistema
TMJ|02|TMJ_CODUSU|C|12|0|Atendente|Codigo Medico Atendente
TMJ|03|TMJ_NOMUSU|C|20|0|Nome|Nome do Usuario
TMJ|04|TMJ_DTCONS|D|8|0|Data Cons.|Data da Consulta
TMJ|05|TMJ_HRCONS|C|5|0|Hora Cons.|Hora da Consulta
TMJ|06|TMJ_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TMJ|07|TMJ_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TMJ|08|TMJ_MAT|C|6|0|Matricula|Matricula do Funcionario
TMJ|09|TMJ_EXAME|C|6|0|Exame|Codigo do Exame
TMJ|10|TMJ_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TMJ|11|TMJ_MOTIVO|C|2|0|Motivo|Motivo Consulta
TMJ|12|TMJ_NOMOTI|C|20|0|Descrição|Descricao do Motivo
TMJ|13|TMJ_CONVOC|C|4|0|Convocacao|Numero da Convocacao
TMJ|14|TMJ_DTPROG|D|8|0|Data Progr.|Data da Programação
TMJ|15|TMJ_DTATEN|D|8|0|Data Atend.|Data Atendimento
TMJ|16|TMJ_OBSCON|C|50|0|Observação|Observacao do Medico
TMJ|17|TMJ_PCMSO|C|6|0|PCMSO|Numero do PCMSO
TMJ|18|TMJ_FILFUN|C|6|0|Filial Func.|Filial do Funcionário
TMJ|19|TMJ_USERGI|C|17|0|Log de Inclu|Log de Inclusao
TMJ|20|TMJ_ATEENF|C|1|0|Atend.Enfe.?|Atendimento de Enfermagem
TMJ|21|TMJ_CODENF|C|12|0|Atend.Ambul.|Atendente Ambulatorial
TMJ|22|TMJ_DESENF|C|12|0|Nome Atend.|Nome Atendente
TMJ|23|TMJ_DTENFE|D|8|0|Data Enferm.|Data Atend. Enferm.
TMJ|24|TMJ_HRENFE|C|5|0|Hora Enferm.|Hora Atend. Enferm.
TMJ|25|TMJ_INDENF|C|1|0|Tipo|Tipo Atendimento
TMJ|26|TMJ_QTDHRS|C|5|0|Quant. Horas|Quant. Horas Atend.
TMJ|27|TMJ_HRCHGD|C|5|0|Hora Chegada|Horario de chegada
TMJ|28|TMJ_HRSAID|C|5|0|Hora Saída|Horário de Saída
--- ### TMK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMK|01|TMK_FILIAL|C|6|0|Filial|Filial do Sistema
TMK|02|TMK_CODUSU|C|12|0|Usuário|Codigo Usuario Atendente
TMK|03|TMK_NOMUSU|C|80|0|Nome|Nome do Usuario
TMK|04|TMK_ENTCLA|C|8|0|Ent. Classe|Entidade de Classe
TMK|05|TMK_NUMENT|C|12|0|Num.Ent.Cl.|Numero na Entidade Classe
TMK|06|TMK_DTINIC|D|8|0|Data Início|Data Inicio
TMK|07|TMK_DTTERM|D|8|0|Data Term.|Data Termino
TMK|08|TMK_REGMTB|C|12|0|Registro MTb|Registro MTb
TMK|09|TMK_SESMT|C|1|0|Compõe SESMT|Componente SESMT (S/N)
TMK|10|TMK_INDFUN|C|1|0|Função|Funcao do Usuario
TMK|11|TMK_DESFUN|C|30|0|Descrição|Descrição da Função
TMK|12|TMK_CALEND|C|3|0|Calendário|Calendário
TMK|13|TMK_DESCAL|C|30|0|Descrição|Descrição
TMK|14|TMK_ENDUSU|C|30|0|Endereço|Endereco do Usuario
TMK|15|TMK_UF|C|2|0|UF Ent.|UF Ent. Classe
TMK|16|TMK_TELUSU|C|15|0|Telefone|Telefone do Usuario
TMK|17|TMK_NIT|C|11|0|NIT|NIT
TMK|18|TMK_CC|C|9|0|Centro Custo|Centro de Custo
TMK|19|TMK_NOMECC|C|20|0|Descrição|Nome do Centro de Custo
TMK|20|TMK_MONBIO|C|1|0|Monit.Biolog|Resp. Monitoracao Biologi
TMK|21|TMK_RESAMB|C|1|0|Resp. Amb.|Responsável Ambiental
TMK|22|TMK_EMAIL|C|50|0|E-mail|E-mail
TMK|23|TMK_CIC|C|11|0|C.P.F.|C.P.F.
TMK|24|TMK_USUARI|C|25|0|Login|Login do Usuário
TMK|25|TMK_ESOC|C|6|0|Cód. eSocial|Código eSocial
TMK|26|TMK_QTDHRS|C|5|0|Quant. Horas|Quant. Horas Atend.
--- ### TML
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TML|01|TML_FILIAL|C|6|0|Filial|Filial do Sistema
TML|02|TML_CODUSU|C|12|0|Usuário|Codigo usuario Medicina
TML|03|TML_NOMUSU|C|20|0|Nome|Nome do Usuario
TML|04|TML_CALEND|C|3|0|Calendário|Cod Calendario Atendiment
TML|05|TML_DESCRI|C|30|0|Descrição|Descrição do Calendário
TML|06|TML_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TML|07|TML_QTDHRS|C|5|0|Quant. Horas|Quant. Horas Atend.
--- ### TMN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMN|01|TMN_FILIAL|C|6|0|Filial|Filial do Sistema
TMN|02|TMN_CODPRO|C|9|0|Progr. Saúde|Codigo Programa de Saude
TMN|03|TMN_NOMPRO|C|20|0|Nome|Nome do Programa de Saude
TMN|04|TMN_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TMN|05|TMN_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TMN|06|TMN_DTINIC|D|8|0|Data Inicio|Data Inicio no Programa
TMN|07|TMN_DTTERM|D|8|0|Data Término|Data Termino no Programa
TMN|08|TMN_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMO|01|TMO_FILIAL|C|6|0|Filial|Filial do Sistema
TMO|02|TMO_CODPRO|C|9|0|Progr. Saúde|Codigo Programa de Saude
TMO|03|TMO_NOMPRO|C|40|0|Nome|Nome do Programa de Saude
TMO|04|TMO_DESPRO|C|200|0|Descrição|Descricao do Programa
TMO|05|TMO_TIPO|C|1|0|Tipo|Tipo de Programa
TMO|06|TMO_PERIOD|C|1|0|Ex. Period.|Gera Exame Periodico ?
TMO|07|TMO_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMQ|01|TMQ_FILIAL|C|6|0|Filial|Filial do Sistema
TMQ|02|TMQ_FAIXA|C|2|0|Faixa|Numero da Faixa
TMQ|03|TMQ_1DE|N|2|0|Per. 1 De:|Idade Inicio 1. Period.
TMQ|04|TMQ_1ATE|N|2|0|Per. 1 Ate:|Idade Final  1. Period.
TMQ|05|TMQ_1QTMES|N|2|0|Per. 1 Meses|Qtde Meses   1. Period.
TMQ|06|TMQ_2DE|N|2|0|Per. 2 De:|Idade Inicio 2. Period.
TMQ|07|TMQ_2ATE|N|2|0|Per. 2 Ate:|Idade Final  2. Period.
TMQ|08|TMQ_2QTMES|N|2|0|Per. 2 Meses|Qtde Meses   2. Period.
TMQ|09|TMQ_3DE|N|2|0|Per. 3 De:|Idade Inicio 3. Period.
TMQ|10|TMQ_3ATE|N|2|0|Per. 3 Ate:|Idade Final  3. Period.
TMQ|11|TMQ_3QTMES|N|2|0|Per. 3 Meses|Qtde Meses   3. Period.
TMQ|12|TMQ_4DE|N|2|0|Per. 4 De:|Idade Inicio 4. Period.
TMQ|13|TMQ_4ATE|N|2|0|Per. 4 Ate:|Idade Final  4. Period.
TMQ|14|TMQ_4QTMES|N|2|0|Per. 4 Meses|Qtde Meses   4. Period.
TMQ|15|TMQ_POSADM|N|2|0|Pos Admissao|Qtde Meses Pos Admissao
TMQ|16|TMQ_SEXO|C|1|0|Indica Sexo|Indica p / que Sexo Gerar
TMQ|17|TMQ_POSAD1|N|2|0|Pós Admis. 2|Segunda Qnt Meses Pós Adm
--- ### TMR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMR|01|TMR_FILIAL|C|6|0|Filial|Filial do Sistema
TMR|02|TMR_CID|C|8|0|C.I.D.|Codigo do C.I.D.
TMR|03|TMR_DOENCA|C|220|0|Desc. Doença|Descrição da  Doença
TMR|04|TMR_DOENGL|C|220|0|Desc. Doença|Descrição da Doença
TMR|05|TMR_DOESPA|C|220|0|Desc. Doença|Descrição da Doença
TMR|06|TMR_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMS|01|TMS_FILIAL|C|6|0|Filial|Filial do Sistema
TMS|02|TMS_MOTIVO|C|2|0|Motivo|Motivo Consulta
TMS|03|TMS_NOMOTI|C|40|0|Nome Motivo|Nome
--- ### TMT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMT|01|TMT_FILIAL|C|6|0|Filial|Filial do Sistema
TMT|02|TMT_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TMT|03|TMT_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TMT|04|TMT_DTCONS|D|8|0|Consulta|Data da Consulta
TMT|05|TMT_HRCONS|C|5|0|Consulta|Hora da Consulta
TMT|06|TMT_CODUSU|C|12|0|Médico|Codigo Medico Atendente
TMT|07|TMT_NOMUSU|C|80|0|Nome|Nome do Medico Atendente
TMT|08|TMT_DTATEN|D|8|0|Atendimento|Data Atendimento
TMT|09|TMT_HRATEN|C|5|0|Atendimento|Hora Atendimento
TMT|10|TMT_HRRETO|C|5|0|Retorno|Horário de retorno
TMT|11|TMT_GRPCID|C|3|0|Grupo CID|Grupo C.I.D.
TMT|12|TMT_DESGRP|C|220|0|Descrição|Desc. Grupo
TMT|13|TMT_CID|C|8|0|CID Princip.|CID Principal
TMT|14|TMT_DOENCA|C|220|0|Descrição|Descricao da  Doenca
TMT|15|TMT_GRPCI2|C|3|0|Grupo Compl.|Grupo Compl.
TMT|16|TMT_CID2|C|8|0|CID Complem.|CID Complementar
TMT|17|TMT_DOENC2|C|150|0|Desc. Doenca|Descricao da  Doenca
TMT|18|TMT_DIAGNO|C|100|0|Diagnóstico|Descricao Diagnostico Med
TMT|19|TMT_DESATE|C|80|0|Atend. Med.|Descricao Atendimento Med
TMT|20|TMT_OCORRE|C|1|0|Ind. Atendim|Ind. Atendim. Realizado
TMT|21|TMT_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TMT|22|TMT_DESACI|C|40|0|Descrição|Descrição do acidente
TMT|23|TMT_QTAFAS|N|3|0|Dias Afast.|Qtde Dias de Afastamento
TMT|24|TMT_QUEIXA|C|80|0|Queixa|Queixa Princ
TMT|25|TMT_HDA|C|80|0|Hist. Doença|Historioco Doenca Acumul.
TMT|26|TMT_CABECA|C|80|0|Cabeça|Cabeca
TMT|27|TMT_OLHOS|C|80|0|Olhos|Olhos
TMT|28|TMT_OUVIDO|C|80|0|Ouvidos|Ouvidos
TMT|29|TMT_PESCOC|C|80|0|Pescoço|Pescoço
TMT|30|TMT_APRESP|C|80|0|Apar. Resp.|Aparelho Respiratório
TMT|31|TMT_APDIGE|C|80|0|Apar. Gast.|Apar Gasstrointestinal
TMT|32|TMT_APCIRC|C|80|0|Apar. Card.|Apar Cardiovasculatorio
TMT|33|TMT_APURIN|C|80|0|Apar. Urin.|Aparelho Urinario
TMT|34|TMT_MMIISS|C|80|0|Membro|Membros Inferiores e Sup.
TMT|35|TMT_PELE|C|80|0|Pele|Pele
TMT|36|TMT_HISPRE|C|80|0|Hist. Pregr.|Hist.Pregres
TMT|37|TMT_EXAMEF|C|80|0|Exame Fis.|Ex. Fisico
TMT|38|TMT_TEMPER|N|5|2|Temperatura|Temperatura
TMT|39|TMT_PREART|C|10|0|Pressao Art.|Pressao Art.
TMT|40|TMT_PRESIS|N|3|0|Sistólica|Pressão Sistólica
TMT|41|TMT_PREDIS|N|3|0|Diastólica|Pressão Diastólica
TMT|42|TMT_ALTURA|N|4|2|Altura|Altura
TMT|43|TMT_PESO|N|6|2|Peso|Peso
TMT|44|TMT_MASSA|C|20|0|Massa Corp.|Massa Corporea
TMT|45|TMT_OROFAR|C|80|0|Orofaringe|Orofaringe
TMT|46|TMT_OTOSCO|C|80|0|Otoscopia|Otoscopia
TMT|47|TMT_ABDOME|C|80|0|Abdomem|Abdomem
TMT|48|TMT_AUSCAR|C|80|0|Aus.Cardiaca|Frequencia Cardiaca
TMT|49|TMT_AUSPUL|C|80|0|Aus.Pulmonar|Aus.Pulmonar
TMT|50|TMT_FILFUN|C|6|0|Filial|Filial
TMT|51|TMT_CC|C|9|0|Centro Custo|Centro de Custo
TMT|52|TMT_CODUSA|C|12|0|Atend.Ambul.|Atendente Abulatorial
TMT|53|TMT_CBO|C|6|0|C.B.O.|Codigo C.B.O.
TMT|54|TMT_CODFUN|C|5|0|Função|Funcao do Funcionario
TMT|55|TMT_MMSS|C|30|0|Membros Sup.|Membros Superiores
TMT|56|TMT_MMII|C|30|0|Membros Inf.|Membros Inferiores
TMT|57|TMT_AVODSE|N|4|1|Ac.V.O.D.S/C|Ac.Vis. O. Direito S/Corr
TMT|58|TMT_AVOESE|N|4|1|Ac.V.O.E.S/C|Ac.Vis.O. Esquerdo S/Corr
TMT|59|TMT_AVODCO|N|4|1|Ac.V.O.D.C/C|Ac.Vis. O. Direito C/Corr
TMT|60|TMT_AVOECO|N|4|1|Ac.V.O.E.C/C|Ac.Vis.O. Esquerdo C/Corr
TMT|61|TMT_OUTROS|M|10|0|Outros|Outros
TMT|62|TMT_MAT|C|6|0|Matrícula|Matricula Funcionario
TMT|63|TMT_TIPDEF|C|1|0|Tipo Def.|Tipo de Deficiência
TMT|64|TMT_CIDDEF|C|8|0|CID Def.|CID da Deficiência
TMT|65|TMT_PULSO|C|10|0|Pulso|Pulso
TMT|66|TMT_RESPI|C|12|0|Respiração|Respiração
TMT|67|TMT_DOENC3|C|150|0|Descrição|Descrição Doença
TMT|68|TMT_DINAMO|N|9|3|Dinamometria|Dinamometria
TMT|69|TMT_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TMT|70|TMT_HISSYP|C|6|0|Hist. Pregr.|Hist. Pregres
TMT|71|TMT_MHISPR|M|10|0|Hist. Pregr.|Hist.Pregres
TMT|72|TMT_DIASYP|C|6|0|Diagnóstico|Descricao Diagnostico Med
TMT|73|TMT_MDIAGN|M|10|0|Diagnóstico|Descrição Diagnostico Med
TMT|74|TMT_DATSYP|C|6|0|Atend. Med.|Descrição Atendimento Med
TMT|75|TMT_MDESAT|M|10|0|Atend. Med.|Descrição Atendimento Med
TMT|76|TMT_QUESYP|C|6|0|Queixa|Queixa Principal
TMT|77|TMT_MQUEIX|M|10|0|Queixa|Queixa Principal
TMT|78|TMT_HDASYP|C|6|0|Hist. Doença|Histórico Doença Acumul.
TMT|79|TMT_MHDA|M|10|0|Hist. Doença|Histórico Doença Acumul.
TMT|80|TMT_CABSYP|C|6|0|Cabeça|Cabeça
TMT|81|TMT_MCABEC|M|10|0|Cabeça|Cabeça
TMT|82|TMT_OLHSYP|C|6|0|Olhos|Olhos
TMT|83|TMT_MOLHOS|M|10|0|Olhos|Olhos
TMT|84|TMT_OUVSYP|C|6|0|Ouvidos|Ouvidos
TMT|85|TMT_MOUVID|M|10|0|Ouvidos|Ouvidos
TMT|86|TMT_PESSYP|C|6|0|Pescoço|Pescoço
TMT|87|TMT_MPESCO|M|10|0|Pescoço|Pescoço
TMT|88|TMT_APRSYP|C|6|0|Apar. Resp.|Aparelho Respiratório
TMT|89|TMT_MAPRES|M|10|0|Apar. Resp.|Aparelho Respiratório
TMT|90|TMT_APDSYP|C|6|0|Apar. Gast.|Apar. Gasstrointestinal
TMT|91|TMT_MAPDIG|M|10|0|Apar. Gast.|Apar. Gasstrointestinal
TMT|92|TMT_APCSYP|C|6|0|Apar. Card.|Apar. Cardiovascular
TMT|93|TMT_MAPCIR|M|10|0|Apar. Card.|Apar. Cardiovascular
TMT|94|TMT_APUSYP|C|6|0|Apar. Urin.|Aparelho Urinário
TMT|95|TMT_MAPURI|M|10|0|Apar. Urin.|Aparelho Urinário
TMT|96|TMT_MISSYP|C|6|0|Membro|Membros Inferiores e Sup.
TMT|97|TMT_MMIS|M|10|0|Membro|Membros Inferiores e Sup.
TMT|98|TMT_PELSYP|C|6|0|Pele|Pele
TMT|99|TMT_MPELE|M|10|0|Pele|Pele
TMT|9A|TMT_EXFSYP|C|6|0|Ex. Físico|Exame Físico
TMT|9B|TMT_MEXAME|M|10|0|Ex. Físico|Exame Físico
TMT|9C|TMT_ORFSYP|C|6|0|Orofaringe|Orofaringe
TMT|9D|TMT_MOROFA|M|10|0|Orofaringe|Orofaringe
TMT|9E|TMT_OTSSYP|C|6|0|Otoscopia|Otoscopia
TMT|9F|TMT_MOTOSC|M|10|0|Otoscopia|Otoscopia
TMT|9G|TMT_ABDSYP|C|6|0|Abdomem|Abdomem
TMT|9H|TMT_MABDOM|M|10|0|Abdomem|Abdomem
TMT|9I|TMT_AUCSYP|C|6|0|Ausc. Card.|Frequência Cardíaca
TMT|9J|TMT_MAUSCA|M|10|0|Ausc. Card.|Frequência Cardíaca
TMT|9K|TMT_AUPSYP|C|6|0|Ausc. Pulm.|Aus. Pulmonar
TMT|9L|TMT_MAUSPU|M|10|0|Ausc. Pulm.|Aus. Pulmonar
--- ### TMU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMU|01|TMU_FILIAL|C|6|0|Filial|Filial do Sistema
TMU|02|TMU_CODRES|C|4|0|Cod.Result.|Codigo Resultado Exame
TMU|03|TMU_RESULT|C|50|0|Desc.Result.|Descricao Resultado Exame
--- ### TMV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMV|01|TMV_FILIAL|C|6|0|Filial|Numero da Filial
TMV|02|TMV_PCMSO|C|6|0|PCMSO|Numero do PCMSO
TMV|03|TMV_CONVOC|C|4|0|Convocacao|Numero da Convocacao
TMV|04|TMV_DTINPR|D|8|0|Inic. Progr.|Data de Inicio Programaca
TMV|05|TMV_DTFIPR|D|8|0|Term. Progr.|Data de Termino Programac
TMV|06|TMV_CODUSU|C|12|0|Medico|Codigo do Medico
TMV|07|TMV_NOMUSU|C|20|0|Nome|Nome do Usuario
TMV|08|TMV_DTINRE|D|8|0|Início Real.|Data Incio Realizacao
TMV|09|TMV_DTFIRE|D|8|0|Term. Real.|Data Final Realizacao
TMV|10|TMV_EXAME|C|6|0|Exame|Codigo do Exame Periodico
TMV|11|TMV_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TMV|12|TMV_CC|C|9|0|Centro Custo|Codigo do centro de custo
TMV|13|TMV_CODFUN|C|5|0|Funcao|Codigo da Funcao
TMV|14|TMV_CALEND|C|3|0|Calendario|Codigo do  Calendario
TMV|15|TMV_QTATEN|N|3|0|Tempo (min.)|Tempo Adendimento (minut)
TMV|16|TMV_MOTIVO|C|4|0|Motivo|Codigo do Motivo Consulta
TMV|17|TMV_NOMOTI|C|20|0|Descricao|Descricao do Motivo
TMV|18|TMV_TNOTRA|C|3|0|Turno|Codigo do Turno Trabalho
TMV|19|TMV_LOCAL|C|30|0|Local Exame|Local do Exame
TMV|20|TMV_TIPODT|C|1|0|Dt. Prevista|Dt. Prevista
TMV|21|TMV_DTEXC1|D|8|0|Dt.Excecao1|Data Excecao Calendarrio
TMV|22|TMV_DTEXC2|D|8|0|Dt.Excecao2|Data Excecao Calendarrio
TMV|23|TMV_DTEXC3|D|8|0|Dt.Excecao3|Data Excecao Calendarrio
TMV|24|TMV_DTEXC4|D|8|0|Dt.Excecao4|Data Excecao Calendarrio
TMV|25|TMV_DTEXC5|D|8|0|Dt.Excecao5|Data Excecao Calendarrio
TMV|26|TMV_DTEXC6|D|8|0|Dt.Excecao6|Data Excecao Calendarrio
TMV|27|TMV_FILDE|C|6|0|De Filial|De Filial
TMV|28|TMV_FILATE|C|6|0|Ate Filial|Ate Filial
TMV|29|TMV_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMW|01|TMW_FILIAL|C|6|0|Filial|Numero da Filial
TMW|02|TMW_PCMSO|C|6|0|PCMSO|Numero do PCMSO
TMW|03|TMW_CODUSU|C|12|0|Med. Resp.|Codigo do Medico Responsa
TMW|04|TMW_NOMUSU|C|40|0|Nome|Nome do Usuario
TMW|05|TMW_DTINIC|D|8|0|Data Inic.|Data de Inicio  PCMSO
TMW|06|TMW_DTFIM|D|8|0|Data Term.|Data de Termino PCMSO
TMW|07|TMW_DTGERA|D|8|0|Data Gerac.|Data da Geracao Programac
TMW|08|TMW_DESCRI|C|200|0|Observação|Observacao
TMW|09|TMW_CCDE|C|9|0|De C. Custo|De Centro de Custo
TMW|10|TMW_CCATE|C|9|0|Ate C. Custo|Ate Centro de Custo
TMW|11|TMW_CLIDE|C|6|0|De Cliente|De Cliente
TMW|12|TMW_CLIATE|C|6|0|Ate Cliente|Ate Cliente
TMW|13|TMW_BASEDT|C|1|0|Data Prog.|Data Base Programacao Exa
TMW|14|TMW_DTREFE|D|8|0|Data Infor.|Data Informada
TMW|15|TMW_FILDE|C|6|0|De Filial|De Filial
TMW|16|TMW_FILATE|C|6|0|Ate Filial|Ate Filial
TMW|17|TMW_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TMX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMX|01|TMX_FILIAL|C|6|0|Filial|Filial do Sistema
TMX|02|TMX_NUMASO|C|6|0|Num. ASO|Numero do ASO
TMX|03|TMX_NUMRIS|C|9|0|Num. Risco|Numero do Risco
TMX|04|TMX_NOMAGE|C|20|0|Nome Agente|Nome Agente de Risco
--- ### TMY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMY|01|TMY_FILIAL|C|6|0|Filial|Filial do Sistema
TMY|02|TMY_NUMASO|C|6|0|Numero ASO|Numero do ASO
TMY|03|TMY_NUMFIC|C|9|0|Ficha Medica|Numero da Ficha Medica
TMY|04|TMY_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TMY|05|TMY_EXAME|C|6|0|Exame|Codigo do Exame Medico
TMY|06|TMY_DTPROG|D|8|0|Data Prog.|Data Programacao Exame
TMY|07|TMY_DTGERA|D|8|0|Data Geracao|Data de Geracao do ASO
TMY|08|TMY_DTEMIS|D|8|0|Data Emissao|Data da Emissao do ASO
TMY|09|TMY_DTCANC|D|8|0|Data Cancel.|Data do Cancelamento
TMY|10|TMY_QTDTRA|N|4|0|Dias Trat.|Quant. Dias Tratamento
TMY|11|TMY_INDPAR|C|1|0|Ind. Parec.|Indicacao do Parecer
TMY|12|TMY_DESPAR|C|25|0|Desc. Parec.|Descricao do Parecer
TMY|13|TMY_CODUSU|C|12|0|Medico Resp.|Medico resp. ASO.
TMY|14|TMY_NOMUSU|C|20|0|Nome|Nome do Usuario
TMY|15|TMY_DESCRI|C|200|0|Descricao|Descricao Parecer
TMY|16|TMY_NATEXA|C|1|0|Natureza|Natureza do Exame
TMY|17|TMY_DESNAT|C|20|0|Desc. Nat.|Descricao da Natureza
TMY|18|TMY_EMPFUT|C|2|0|Emp. Futura|Empresa Futura
TMY|19|TMY_FILFUT|C|6|0|Fil. Futura|Filial Futura
TMY|20|TMY_NOVFUN|C|5|0|Nova Função|Nova Função do Func.
TMY|21|TMY_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TMY|22|TMY_NOVCC|C|9|0|Novo C.Custo|Novo Centro de Custo
TMY|23|TMY_USERGA|C|17|0|Log de Alter|Log de Alteracao
TMY|24|TMY_NOVTAR|C|6|0|Nova Tarefa|Nova Tarefa do Func.
TMY|25|TMY_ALTURA|C|1|0|Trab. Altura|Trabalho em Altura
TMY|26|TMY_CONFIN|C|1|0|Trab. Confin|Trabalho Espaco Confinado
TMY|27|TMY_TMC|C|1|0|Tra/Mov Carg|Transp. Movi. de Cargas
TMY|28|TMY_NOVDEP|C|9|0|Novo dep.|Novo Departamento
TMY|29|TMY_ELETRI|C|1|0|Trab. Eletr.|Trabalho com eletricidade
TMY|30|TMY_CNES|C|7|0|Cod. CNES|Código de CNES
TMY|31|TMY_ESTAB|C|80|0|Estabelecim.|Estabelcimento do CNES
TMY|32|TMY_INDEXA|C|1|0|Ind. Exame|Indicação de Exame
TMY|33|TMY_PLAT|C|1|0|Trab. Plat.|Trabalho em plataforma
TMY|34|TMY_MANCIV|C|1|0|Trab Man Civ|Trabalho Manutencao Civil
TMY|35|TMY_EXPLO|C|1|0|Trab. Explo|Trabalho com Explosoes
TMY|36|TMY_ESCAV|C|1|0|Trab. Escav|Trabalhocom Escav/Demol
TMY|37|TMY_SOLDA|C|1|0|Trab. Solda|Trabalho com Solda
TMY|38|TMY_FRIO|C|1|0|Trab. Frio|Trabalho Frio
TMY|39|TMY_RADIA|C|1|0|Trab. Radiac|Trabalho em Radiação
TMY|40|TMY_PRESS|C|1|0|Trab Pressao|Trabalho Pressao
TMY|41|TMY_OUTROS|C|1|0|Trab. Outros|Trabalho Outros
TMY|42|TMY_INFLA|C|1|0|Trab. Infl.|Trabalho Inflamável
--- ### TMZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TMZ|01|TMZ_FILIAL|C|6|0|Filial|Filial do Sistema
TMZ|02|TMZ_TERMO|C|6|0|Cod. Termo|Codigo do Termo
TMZ|03|TMZ_NOMTER|C|40|0|Nome Termo|Nome do Termo
TMZ|04|TMZ_DESCRI|M|10|0|Descricao|Descricao do Termo
--- ### TN0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN0|01|TN0_FILIAL|C|6|0|Filial|Filial do Sistema
TN0|02|TN0_NUMRIS|C|9|0|Num. Risco|Numero Identifica o Risco
TN0|03|TN0_DTRECO|D|8|0|Data Reconh.|Data Reconecimento
TN0|04|TN0_AGENTE|C|9|0|Agente|Codigo do Agente Risco
TN0|05|TN0_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TN0|06|TN0_FONTE|C|8|0|Fonte Ger.|Fonte Geradora
TN0|07|TN0_NOMFON|C|20|0|Nome Fonte|Nome da Fonte Geradora
TN0|08|TN0_DTAVAL|D|8|0|Dt.Avaliacao|Data Avaliacao
TN0|09|TN0_DTELIM|D|8|0|Data Elim.|Data Eliminação
TN0|10|TN0_CC|C|9|0|Centro Custo|Centro de Custo
TN0|11|TN0_DESCCC|C|20|0|Descrição|Desc.Centro de Custo
TN0|12|TN0_CODFUN|C|5|0|Funcao|Codigo da Funcao
TN0|13|TN0_DESCFU|C|20|0|Desc. Função|Descricao da Funcao
TN0|14|TN0_CODTAR|C|6|0|Tarefa|Codigo da Tarefa
TN0|15|TN0_NOMTAR|C|20|0|Nome Tarefa|Nome da Tarefa
TN0|16|TN0_DEPTO|C|9|0|Departamento|Codigo Departamento
TN0|17|TN0_DESCDP|C|30|0|Descrição|Descrição Departamento
TN0|18|TN0_QTAGEN|N|10|4|Qtd. Agente|Quantidade de Agente
TN0|19|TN0_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TN0|20|TN0_QTEXPO|C|5|0|Tempo Expos.|Tempo de Exposicao(hh:mm)
TN0|21|TN0_REPETE|C|2|0|Repetição|Qtde vezes que Repete
TN0|22|TN0_INTERV|C|5|0|Intervalo|Intervalo Entre Exposicao
TN0|23|TN0_LISASO|C|1|0|Considerar|Considerar Risco em
TN0|24|TN0_GRAU|C|1|0|Grau Risco|Grau de Risco
TN0|25|TN0_MAPRIS|C|1|0|Mapa Risco|Mapa de Risco
TN0|26|TN0_CODAMB|C|30|0|Ambiente|Codigo do Ambiente Fisico
TN0|27|TN0_NOMAMB|C|20|0|Nome Amb.|Nome do Ambiente
TN0|28|TN0_INDEXP|C|1|0|Tipo Exposic|Tipo da Exposicao
TN0|29|TN0_COMEXP|C|60|0|Compl. Exp.|Complemento de Exposicao
TN0|30|TN0_SEFIP|C|2|0|Cod. SEFIP|Código SEFIP
TN0|31|TN0_EPC|C|1|0|Utiliza EPC?|Utiliza EPC?
TN0|32|TN0_MEDCON|C|6|0|Controle|Medida de Controle
TN0|33|TN0_DESMED|C|40|0|Desc. Med.|Descrição Medida
TN0|34|TN0_NECEPI|C|1|0|Nec. EPI|Necessita de EPI
TN0|35|TN0_CODFAS|C|3|0|Fase Obra|Fase da Obra
TN0|36|TN0_DESFAS|C|20|0|Nome Fase|Nome da Fase
TN0|37|TN0_SUBFAS|C|3|0|Sub-Fase|Sub-Fase da Obra
TN0|38|TN0_DESSUB|C|20|0|Nome Subfase|Nome da Subfase
TN0|39|TN0_ATISAL|C|1|0|Ativ. Insal.|Atividade Insalubre
TN0|40|TN0_ATIPER|C|1|0|Ativ. Peric.|Atividade Periculosa
TN0|41|TN0_APOESP|C|1|0|Aposen. Esp?|Aposentadoria Especial?
TN0|42|TN0_ENQLEG|C|100|0|Enqu. Legal|Enquadramento Legal
TN0|43|TN0_VM_ADI|C|16|0|Adicional|Adicional de Risco
TN0|44|TN0_TECUTI|C|40|0|Tec. Utiliz.|Tecnica Utilizada
TN0|45|TN0_CATRIS|C|1|0|Categ. Risco|Categoria do Risco
TN0|46|TN0_SITSYP|C|6|0|Sit. Encont.|Sit. Ergonomica Encontrad
TN0|47|TN0_PERINT|C|1|0|Intensidade|Percentual de Intensidade
TN0|48|TN0_MSITUA|M|10|0|Sit. Encont.|Sit. Ergonomica Encontrad
TN0|49|TN0_SI2SYP|C|6|0|Sit. Desej.|Sit. Ergonomica Desejada
TN0|50|TN0_ADIFOL|C|1|0|Adic.Folha|Adicional em Folha ?
TN0|51|TN0_DANSYP|C|6|0|Danos Caus.|Danos Causados
TN0|52|TN0_MSITU2|M|10|0|Sit. Desej.|Sit. Ergonomica Desejada
TN0|53|TN0_SITUAC|C|1|0|Status|Status da Situação
TN0|54|TN0_DANCAU|M|10|0|Danos Caus.|Danos Causados
TN0|55|TN0_CONFUN|C|1|0|Cond. Funcio|Condição de Funcionamento
TN0|56|TN0_PRZVLD|C|1|0|Prazo Valid.|Prazo de Validade
TN0|57|TN0_PERTRC|C|1|0|Period. Troc|Periodicidade de Troca
TN0|58|TN0_HIGIEN|C|1|0|Higienização|Higienização
TN0|59|TN0_SEVERI|C|1|0|Severidade|Severidade do risco
TN0|60|TN0_PROBAB|C|1|0|Probab.|Probabilidade
TN0|61|TN0_CLASSI|C|11|0|Classif.|Classificação
--- ### TN1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN1|01|TN1_FILIAL|C|6|0|Filial|Filial do Sistema
TN1|02|TN1_SEQGER|C|6|0|Num. Geração|Numero da Geração
TN1|03|TN1_DTGERA|D|8|0|Data Geracao|Data Geracao Exame x Risc
TN1|04|TN1_AGENTE|C|9|0|Agente|Codigo do Agente de risco
TN1|05|TN1_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TN1|06|TN1_FAIXA|C|2|0|Faixa|Numero da Faixa
TN1|07|TN1_DEINTE|N|10|4|De Intens.|De Intensidade
TN1|08|TN1_ATEINT|N|10|4|Ate Intens.|Ate Intensidade
TN1|09|TN1_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TN2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN2|01|TN2_FILIAL|C|6|0|Filial|Filial do Sistema
TN2|02|TN2_NUMRIS|C|9|0|Risco|Numero do Risco
TN2|03|TN2_AGENTE|C|9|0|Agente|Codigo  Agente
TN2|04|TN2_NOMAGE|C|40|0|Nome Agente|Nomde do Agente
TN2|05|TN2_EXAME|C|6|0|Exame|Codigo do Exame
TN2|06|TN2_NOMEXA|C|40|0|Nome Exame|Nome do Exame
TN2|07|TN2_FAIXA|C|2|0|Faixa|Numero da Faixa
TN2|08|TN2_SEQGER|C|6|0|Num. Geração|Numero da Geração
TN2|09|TN2_TIPOEX|C|2|0|Tipo Exame|Tipo Exame
TN2|10|TN2_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TN3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN3|01|TN3_FILIAL|C|6|0|Filial|Filial do Sistema
TN3|02|TN3_CODEPI|C|15|0|Código|Codigo do Produto (EPI)
TN3|03|TN3_DESC|C|70|0|Descrição|Descricao do Produto
TN3|04|TN3_FORNEC|C|6|0|Fornecedor|Cod Fornecedor Exames
TN3|05|TN3_LOJA|C|2|0|Loja|Loja do Fornecedor
TN3|06|TN3_NREDUZ|C|20|0|N Fantasia|Nome de Fantasia Fornec
TN3|07|TN3_GENERI|C|1|0|Genérico ?|Produto Generico
TN3|08|TN3_NUMCAP|C|12|0|Num. C.A.|Num. Certificado Aprovac.
TN3|09|TN3_DTVENC|D|8|0|Venc. CA|Data Vencimento C.A.
TN3|10|TN3_DURABI|N|4|0|Dias Utiliz.|Qtde Dias de Utilizacao
TN3|11|TN3_INDEVO|C|1|0|Devolução|Indica Devolucao EPI.
TN3|12|TN3_DTAVAL|D|8|0|Data Aval.|Data de Avaliacao
TN3|13|TN3_NUMCRF|C|12|0|Num. CRF|Num. Certificado Fabrican
TN3|14|TN3_NUMCRI|C|12|0|Num. Cert.|Num. Certificado Importac
TN3|15|TN3_DTVALI|D|8|0|Data Valid.|Data de Validade
TN3|16|TN3_OBSAVA|C|80|0|Observação|Obs. sobre Avaliacao EPI
TN3|17|TN3_TIPEPI|C|25|0|Tipo EPI|Tipo de EPI
TN3|18|TN3_AREEPI|C|80|0|Área|Área de Uso do EPI
TN3|19|TN3_PERMAN|N|4|0|Per. Manut.|Periodicidade da Manutenc
TN3|20|TN3_TPDURA|C|1|0|Tipo Durab.|Tipo Durabilidade
--- ### TN4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN4|01|TN4_FILIAL|C|6|0|Filial|Filial do Sistema
TN4|02|TN4_NUMFIC|C|9|0|Ficha Medic|Numero Ficha Medica
TN4|03|TN4_DTPROG|D|8|0|Dt. Program.|Data Programacao Exame
TN4|04|TN4_EXAME|C|6|0|Exame|Codigo do Exame Medico
TN4|05|TN4_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TN4|06|TN4_AGENTE|C|9|0|Agente|Codigo do Agente
TN4|07|TN4_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TN4|08|TN4_QTDENC|N|8|2|Qtde Encont.|Qtde Encontrada no Exame
TN4|09|TN4_UNIDAD|C|6|0|Unid. Medida|Unidade de Medida
TN4|10|TN4_HRPROG|C|5|0|Horario Prog|Horario Programacao
TN4|11|TN4_DTINIM|D|8|0|Data Início|Data Início
TN4|12|TN4_DTFIMM|D|8|0|Data Fim|Data Fim
--- ### TN5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN5|01|TN5_FILIAL|C|6|0|Filial|Filial do Sistema
TN5|02|TN5_CODTAR|C|6|0|Tarefa Risco|Codigo Tarefa de Risco
TN5|03|TN5_NOMTAR|C|254|0|Nome Tarefa|Nome da Tarefa
TN5|04|TN5_DESTAR|C|200|0|Descricao|Descricao Tarefa
TN5|05|TN5_DESCR1|C|80|0|Compl Desc1|Complemento Descricao
TN5|06|TN5_DESCR2|C|80|0|Compl Desc2|Complemento Descricao
TN5|07|TN5_DESCR3|C|80|0|Compl Desc3|Complemento Descricao
TN5|08|TN5_DESCR4|C|80|0|Compl Desc4|Complemento Descricao
TN5|09|TN5_ESFORC|C|1|0|Grau Esforço|Grau de Esforco da Tarefa
TN5|10|TN5_DESCRI|M|10|0|Descrição|Descrição
TN5|11|TN5_HRDIA|C|5|0|Horas Trab.|Horas Trabalhadas
TN5|12|TN5_VESSYP|C|6|0|Vestimenta|Vestimenta Utilizada
TN5|13|TN5_MVESTI|M|10|0|Vestimenta|Vestimenta Utilizada
TN5|14|TN5_ESOC|C|6|0|Cód. eSoc.|Cód. Ativ. eSocial
--- ### TN6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN6|01|TN6_FILIAL|C|6|0|Filial|Filial do Sistema
TN6|02|TN6_CODTAR|C|6|0|Tarefa|Codigo da Tarefa
TN6|03|TN6_NOMTAR|C|20|0|Nome Tarefa|Nome da Tarefa de Risco
TN6|04|TN6_MAT|C|6|0|Matrícula|Matricula Funcionario
TN6|05|TN6_NOME|C|30|0|Funcionário|Nome do Funcionario
TN6|06|TN6_DTINIC|D|8|0|Data Início|Data Inicio Tarefa
TN6|07|TN6_DTTERM|D|8|0|Data Término|Data Termino Tarefa
--- ### TN7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN7|01|TN7_FILIAL|C|6|0|Filial|Filial do Sistema
TN7|02|TN7_FONTE|C|8|0|Fonte Gerad.|Fonte Geradora de Risco
TN7|03|TN7_NOMFON|C|40|0|Nome Fonte|Nome da Fonte Geradora
TN7|04|TN7_BITMAP|C|8|0|Imagem|Imagem da Fonte Geradora
--- ### TN8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN8|01|TN8_FILIAL|C|6|0|Filial|Filial do Sistema
TN8|02|TN8_CODPRO|C|9|0|Programa|Codigo do Programa
TN8|03|TN8_NOMPRO|C|20|0|Nome Progr.|Nome do Programa Saude
TN8|04|TN8_EXAME|C|6|0|Exame|Codigo do Exame
TN8|05|TN8_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TN8|06|TN8_FAIXA|C|2|0|Faixa|Numero da Faixa
TN8|07|TN8_TIPOEX|C|2|0|Tipo Exame|Tipo Exame
--- ### TN9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TN9|01|TN9_FILIAL|C|6|0|Filial|Filial do Sistema
TN9|02|TN9_EXAME|C|6|0|Exame|Codigo do Exame
TN9|03|TN9_NOMEXA|C|20|0|Nome Exame|Nome do Exame
TN9|04|TN9_FAIXA|C|2|0|Faixa|Numero da Faixa
TN9|05|TN9_TIPOEX|C|2|0|Tipo Exame|Tipo Exame
TN9|06|TN9_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TNA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNA|01|TNA_FILIAL|C|6|0|Filial|Filial do Sistema
TNA|02|TNA_CID|C|8|0|CID|Classif Internac Doenca
TNA|03|TNA_DOENCA|C|100|0|Desc. Doença|Descricao da  Doenca
TNA|04|TNA_DTINIC|D|8|0|Data Inicio|Data Inicio Doenca
TNA|05|TNA_DTFIM|D|8|0|Data Termino|Data da Cura Total
TNA|06|TNA_NUMFIC|C|9|0|Ficha Medica|Numero Ficha Medica
TNA|07|TNA_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TNA|08|TNA_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TNB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNB|01|TNB_FILIAL|C|6|0|Filial|Filial do Sistema
TNB|02|TNB_CODFUN|C|5|0|Função|Funcao do Funcionario
TNB|03|TNB_DESCFU|C|30|0|Desc.Funcao|Descricao da Funcao
TNB|04|TNB_CODEPI|C|15|0|Código|Codigo do Produto (EPI)
TNB|05|TNB_DESC|C|70|0|Descr. EPI|Descricao do Produto
TNB|06|TNB_COMBO|C|1|0|Tipo Epi|Tipo de Epi
--- ### TNC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNC|01|TNC_FILIAL|C|6|0|Filial|Filial do Sistema
TNC|02|TNC_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNC|03|TNC_DESACI|C|80|0|Descrição|Descricao do Acidente
TNC|04|TNC_HRACID|C|5|0|Hora Acid.|Hora do Acidente
TNC|05|TNC_DTACID|D|8|0|Data Acident|Data do Acidente
TNC|06|TNC_INDACI|C|1|0|Ind. Acid.|Indica tipo Acidente
TNC|07|TNC_TPACID|C|6|0|Acid eSocial|Cód. Acidente eSocial
TNC|08|TNC_VITIMA|C|1|0|Vítima|Houve Vitima no Acidente
TNC|09|TNC_NUMFIC|C|9|0|Ficha Médica|Numero da Ficha Medica
TNC|10|TNC_NOMFIC|C|80|0|Nome|Nome Proprietario Ficha
TNC|11|TNC_TIPACI|C|12|0|Tipo Acid.|Tipo de Acidente
TNC|12|TNC_DESTIP|C|220|0|Descrição|Descricao Tipo Acidente
TNC|13|TNC_CODOBJ|C|12|0|Objeto Caus.|Objeto Causador
TNC|14|TNC_DESOBJ|C|40|0|Desc. Objeto|Descricao Objeto Causador
TNC|15|TNC_NUMRIS|C|9|0|Num. Risco|Numero do  Risco
TNC|16|TNC_TRANSF|C|1|0|Transf. Set.|Transferencia de C.Custo
TNC|17|TNC_EMITEN|C|1|0|Emitente|Emitente
TNC|18|TNC_TIPCAT|C|1|0|Tipo CAT|Tipo CAT
TNC|19|TNC_AFASTA|C|1|0|Afastamento|Houve Afastamento?
TNC|20|TNC_QTAFAS|N|3|0|Dias Perd.|Qtde Dias Perdidos
TNC|21|TNC_DIASDB|N|4|0|Dias Debtos|Qtde Dias de Debitados
TNC|22|TNC_DTOBIT|D|8|0|Data Obito|Data Obito
TNC|23|TNC_TIPREV|C|1|0|Filiac.Prev.|Filiacao a Previdencia
TNC|24|TNC_AREA|C|1|0|Área Serviço|Area Prestacao Servico
TNC|25|TNC_APOSEN|C|1|0|Aposentado|Indica Aposentado
TNC|26|TNC_HRTRAB|C|5|0|Horas. Trab.|Após qtdas Hrs Trabalho?
TNC|27|TNC_DTULTI|D|8|0|Ult.Dia Trab|Ultimo Dia Trabalhado
TNC|28|TNC_INDLOC|C|1|0|Ind. Local|Local Acidente
TNC|29|TNC_TPINS|C|1|0|Tp. Inscr.|Tipo de Inscrição
TNC|30|TNC_CGCPRE|C|14|0|CNPJ Prestad|CNPJ Prestador Servico
TNC|31|TNC_CODPAI|C|6|0|Cod. País|Código do País
TNC|32|TNC_DESPAI|C|220|0|Descrição|Descrição
TNC|33|TNC_ESTACI|C|2|0|Estado Acid.|Estado Acidente
TNC|34|TNC_CODPOS|C|6|0|Cod. Postal|Código Postal
TNC|35|TNC_CODCID|C|5|0|Cód. Cidade|Código Cidade
TNC|36|TNC_CIDACI|C|60|0|Cidade Acid.|Cidade Acidente
TNC|37|TNC_LOCAL|C|254|0|Local  Acid.|Local Detelhado Acidente
TNC|38|TNC_CODAMB|C|30|0|Cod. Amb.|Codigo do Ambiente Fisico
TNC|39|TNC_DESLOG|C|100|0|Desc. Logr.|Desc. Logradouro do Acid.
TNC|40|TNC_NUMLOG|N|10|0|Núm Logr.|Número do Logradouro
TNC|41|TNC_COMPL|C|30|0|Complemento|Compl. Logradouro
TNC|42|TNC_BAIRRO|C|60|0|Bairro|Bairro Logradouro
TNC|43|TNC_CEP|C|8|0|CEP|Cep Logradouro
TNC|44|TNC_PARTE|C|80|0|Parte Ating.|Parte do Corpo Atingida
TNC|45|TNC_DESCR1|C|80|0|Des Acid.CAT|Descr. Acidente p/CAT L1
TNC|46|TNC_DESCR2|C|80|0|Compl.Desc.|Descr. Acidente p/CAT L2
TNC|47|TNC_POLICI|C|1|0|Reg.Policial|Reg.Policial
TNC|48|TNC_MORTE|C|1|0|Houve Morte|Houve Morte
TNC|49|TNC_NUEND1|N|6|0|Núm. Tes. 1|Núm. Testemunha 1
TNC|50|TNC_MTEST1|C|6|0|Mat. Test. 1|Matricula Testemunha 1
TNC|51|TNC_TESTE1|C|30|0|Testemunha 1|Nome da Testemunha (1)
TNC|52|TNC_BAIRR1|C|15|0|Bairro Tes 1|Bairro Testemunha (1)
TNC|53|TNC_ESTAD1|C|2|0|Estado Tes.1|Estado Testemunha 1
TNC|54|TNC_ENDTE1|C|30|0|End.Testem.1|End. Testemunha (1)
TNC|55|TNC_CIDT1|C|5|0|Cid. Tes. 1|Cidade Testemunha 1
TNC|56|TNC_CIDAD1|C|60|0|Cidade Tes.1|Cidade Testemunha 1
TNC|57|TNC_CEP1|C|8|0|Cep Testem.1|Cep Testemunha (1)
TNC|58|TNC_TELEF1|C|12|0|Telef. Tes.1|Telefone Testemunha 1
TNC|59|TNC_MTEST2|C|6|0|Mat. Test. 2|Matricula testemunha 2
TNC|60|TNC_TESTE2|C|30|0|Testemunha 2|Nome da Testemunha (2)
TNC|61|TNC_ENDTE2|C|30|0|End.Testem.2|End. Testemunha (2)
TNC|62|TNC_NUEND2|N|6|0|Núm. Tes. 2|Núm. Testemunha 2
TNC|63|TNC_BAIRR2|C|15|0|Bairro Tes 2|Bairro Testemunha (2)
TNC|64|TNC_CIDT2|C|5|0|Cid. Tes.2|Cidade Testemunha 2
TNC|65|TNC_ESTAD2|C|2|0|Estado Tes.2|Estado Testemunha 2
TNC|66|TNC_CIDAD2|C|60|0|Cidade Tes.2|Cidade Testemunha 2
TNC|67|TNC_CEP2|C|8|0|Cep Testem.2|Cep Testemunha (2)
TNC|68|TNC_INTERN|C|1|0|Internacao|Houve Internação
TNC|69|TNC_HRATEN|C|5|0|Hr. Atendim.|Hora Atendimento
TNC|70|TNC_TELEF2|C|12|0|Telef. Tes.2|Telefone Testemunha 2
TNC|71|TNC_LOCATE|C|80|0|Atend.Medico|Local Atendimento Medico
TNC|72|TNC_DESLES|C|220|0|Descr. Lesao|Descricão Natureza Lesão
TNC|73|TNC_OBSERV|C|80|0|Observacoes|Observações
TNC|74|TNC_DTATEN|D|8|0|Dt.Atend.Med|Dt. Atendimento Medico
TNC|75|TNC_CC|C|9|0|Centro Custo|Centro de Custo
TNC|76|TNC_DESCCC|C|220|0|Descr.CCusto|Descr.Centro de Custo
TNC|77|TNC_CATINS|C|13|0|CAT INSS|Numero CAT INSS
TNC|78|TNC_DTEMIS|D|8|0|Dt. Emissao|Dt. Emissao
TNC|79|TNC_CODFUN|C|5|0|Funcao|Funcao do Funcionario
TNC|80|TNC_DESCFU|C|20|0|Desc.Funcao|Descricao da Funcao
TNC|81|TNC_DETALH|M|10|0|Detalhe Acid|Detalhe Acidente
TNC|82|TNC_CATORI|C|15|0|CAT Origem|Núm. CAT Origem
TNC|83|TNC_DTCATO|D|8|0|Dt. CAT Or.|Data do CAT Origem
TNC|84|TNC_CONFIN|C|80|0|Conclusoes|Conclusoes Finais
TNC|85|TNC_HRRPAD|C|20|0|Hrr. Padrao|Horario de Trab. Padrao
TNC|86|TNC_HRRDIA|C|20|0|Hrr. Acident|Horario no dia Acidente
TNC|87|TNC_LOCACT|C|1|0|Local Ocorr.|Local da Ocorrencia
TNC|88|TNC_HORSAI|C|5|0|Hora Saida|Hora de Saida
TNC|89|TNC_TRAJET|C|80|0|Traje. Usual|Trajeto Usual
TNC|90|TNC_MEIO|C|15|0|Meio Locomo.|Meio de Locomocao
TNC|91|TNC_LOCACI|C|30|0|Local Acide.|Local do Acidente
TNC|92|TNC_DISTAC|N|5|0|Dist. Acid.|Distancia ate Acidente
TNC|93|TNC_DISTUN|C|6|0|Unid. Medida|Unidade de Medida
TNC|94|TNC_MUDANC|C|1|0|Mud. Trajeto|Mudanca de Trajeto
TNC|95|TNC_MOTIVO|C|40|0|Mot. Mudanca|Motivo da Mudanca Trajeto
TNC|96|TNC_TIPOAT|C|1|0|Acid. Trans.|Tipo Acidente Transito
TNC|97|TNC_ADMITE|C|1|0|Admite|Admite
TNC|98|TNC_CODPAR|C|12|0|Codigo Parte|Codigo Parte Atingida
TNC|99|TNC_DESPAR|C|30|0|Desc. Parte|Desc. Parte
TNC|9A|TNC_CODLES|C|12|0|Natur. Lesao|Natur. Lesao
TNC|9B|TNC_NOMLES|C|220|0|Desc. N. Le.|Desc. N. Le.
TNC|9C|TNC_GRPCID|C|3|0|Grupo C.I.D.|Grupo C.I.D.
TNC|9D|TNC_DESGRP|C|220|0|Desc. Grupo|Desc. Grupo
TNC|9E|TNC_CID|C|8|0|CID Princip.|CID Principal
TNC|9F|TNC_FILFUN|C|6|0|Filial Func.|Filial Func.
TNC|9G|TNC_DOENCA|C|220|0|Desc. Doenca|Descricao da  Doenca
TNC|9H|TNC_MAT|C|6|0|Matrícula|Número da Matrícula
TNC|9I|TNC_ANALIS|C|6|0|Análise|Cod. Analise Prelim.
TNC|9J|TNC_OCOPLA|C|6|0|Ocorrência|Ocor. Plan. Emerg.
TNC|9K|TNC_CNES|C|7|0|Cod. CNES|Código CNES
TNC|9L|TNC_INDAPR|C|1|0|Outra ocup.|Outra Ocupação
TNC|9M|TNC_TPINSC|C|1|0|Tipo Inscr.|Tipo de Inscrição
TNC|9N|TNC_NRINSC|C|15|0|Num. Inscr.|Número da Inscrição
TNC|9O|TNC_TPLOGR|C|4|0|Tipo Logr.|Tipo Logradouro eSocial
TNC|9P|TNC_RECIBO|C|44|0|Recibo|Recibo CAT
TNC|9Q|TNC_RECORI|C|44|0|Recibo Ori.|Recibo CAT Origem
TNC|9R|TNC_DTRECB|D|8|0|Data Receb.|Data do Recebimento
TNC|9S|TNC_EXCLU|C|1|0|Exclusão CAT|Situação Exclusão CAT
--- ### TND
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TND|01|TND_FILIAL|C|6|0|Filial|Filial do Sistema
TND|02|TND_CAUSA|C|6|0|Causa|Causa do Acidente
TND|03|TND_NOME|C|40|0|Nome Causa|Descricao da Causa Acid.
TND|04|TND_INDCAU|C|1|0|Indic. Causa|Indica Causa do Acidente
--- ### TNE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNE|01|TNE_FILIAL|C|6|0|Filial|Filial do Sistema
TNE|02|TNE_CODAMB|C|30|0|Ambiente|Codigo do Ambiente Fisico
TNE|03|TNE_NOME|C|40|0|Nome Amb.|Nome do  Ambiente Fisico
TNE|04|TNE_DESAMB|C|80|0|Descricao|Descricao detalhada
TNE|05|TNE_MEMODS|M|10|0|Descrição|Descrição
TNE|06|TNE_DESAM1|C|80|0|Compl. Desc1|Complemento Descrição 1
TNE|07|TNE_DESAM2|C|80|0|Compl. Desc2|Complemento Descrição 2
TNE|08|TNE_DESAM3|C|80|0|Compl. Desc3|Complemento Descrição 3
TNE|09|TNE_DESAM4|C|80|0|Compl. Desc4|Complemento Descrição 4
TNE|10|TNE_BITMAP|C|8|0|Imagem|Imagem do Bem
TNE|11|TNE_TETO|N|5|2|Teto|Altura do pé direito em m
TNE|12|TNE_PORTAS|C|1|0|Portas|Tipos de Portas
TNE|13|TNE_JANELA|C|1|0|Janelas|Tipos de Janelas
TNE|14|TNE_PISO|C|1|0|Piso|Tipo do Piso
TNE|15|TNE_MAQUIN|C|80|0|Máquina|Maquinas e Equipamentos
TNE|16|TNE_PAREDE|C|1|0|Paredes|Tipos de Paredes
TNE|17|TNE_ILUMIN|C|1|0|Iluminação|Tipos de Iluminação
TNE|18|TNE_NATPAR|C|1|0|Nat. Parede|Natureza Parede
TNE|19|TNE_ESPPAR|N|5|2|Esp. parede.|Espessura da parede.
TNE|20|TNE_UNIPAR|C|2|0|Un. parede.|Un. espessura da parede.
TNE|21|TNE_LOCPAR|C|40|0|Loc. parede|Localização da parede.
TNE|22|TNE_NATPIS|C|1|0|Nat. Piso|Natureza Piso
TNE|23|TNE_ESPPIS|N|5|2|Esp. piso.|Espessura do piso.
TNE|24|TNE_UNIPIS|C|2|0|Un. piso.|Un. espessura do piso.
TNE|25|TNE_LOCPIS|C|40|0|Loc. piso.|Localização do piso.
TNE|26|TNE_NATTET|C|1|0|Nat. Teto|Natureza Teto
TNE|27|TNE_ESPTET|N|5|2|Esp. teto.|Espessura do teto.
TNE|28|TNE_UNITET|C|2|0|Un. teto.|Un. espessura do teto.
TNE|29|TNE_NATPOR|C|1|0|Nat. Porta|Natureza Porta
TNE|30|TNE_ESPPOR|N|5|2|Esp. porta.|Espessura da porta.
TNE|31|TNE_UNIPOR|C|2|0|Un. porta.|Un. espessura da porta."
TNE|32|TNE_LOCPOR|C|40|0|Loc. porta.|Localização da porta.
TNE|33|TNE_NATRE1|C|1|0|Rev. Amb. 1|Revestimento Ambiente 1
TNE|34|TNE_ESPRE1|N|5|2|Esp. 1° rev.|Esp. 1° revestimento
TNE|35|TNE_UNIRE1|C|2|0|Un. 1° rev.|Un. espessura 1° rev.
TNE|36|TNE_LOCRE1|C|40|0|Loc. 1° rev.|Loc. 1° revestimento.
TNE|37|TNE_NATRE2|C|1|0|Rev. Amb. 2|Revestimento Ambiente 2
TNE|38|TNE_ESPRE2|N|5|2|Esp. 2° rev.|Esp. 2° revestimento.
TNE|39|TNE_UNIRE2|C|2|0|Un. 2° rev.|Un. esp. 2° revestimento
TNE|40|TNE_LOCRE2|C|40|0|Loc. 2° rev.|Loc. 2° revestimento.
TNE|41|TNE_NATVIS|C|1|0|Tipo visor|Tipo do visor do biombo.
TNE|42|TNE_ESPVIS|N|5|2|Esp. visor.|Espessura do visor.
TNE|43|TNE_UNIVIS|C|2|0|Un. visor.|Un. Espessura do visor.
TNE|44|TNE_LOCVIS|C|40|0|Loc. visor.|Localização do visor.
TNE|45|TNE_DTVINI|D|8|0|Valid.Inic.|Data de Validade Inicial
TNE|46|TNE_LOCAMB|C|1|0|Loc. Amb.|Local do Ambiente Físico
TNE|47|TNE_TPINS|C|1|0|Tp. Inscr.|Tipo de Inscrição
TNE|48|TNE_NRINS|C|14|0|Nr. Inscr.|Número de Inscrição
TNE|49|TNE_CODLOT|C|9|0|Centro Custo|Centro de Custo
--- ### TNF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNF|01|TNF_FILIAL|C|6|0|Filial|Filial do Sistema
TNF|02|TNF_CODEPI|C|15|0|Código|Codigo do Produto (EPI)
TNF|03|TNF_DESC|C|70|0|Descrição|Descricao do Produto
TNF|04|TNF_FORNEC|C|6|0|Fornecedor|Cod Fornecedor Exames
TNF|05|TNF_LOJA|C|2|0|Loja|Loja do Fornecedor
TNF|06|TNF_NUMCAP|C|12|0|Num. C. A.|Num. Certificado Aprov.
TNF|07|TNF_MAT|C|6|0|Matrícula|Matricula Funcionario
TNF|08|TNF_NOME|C|20|0|Funcionário|Nome do Funcionario
TNF|09|TNF_DTENTR|D|8|0|Data Entrega|Dt. Entrega do Epi p/func
TNF|10|TNF_HRENTR|C|8|0|Hora Entrega|Hr. Entregua EPI
TNF|11|TNF_QTDENT|N|6|2|Quant. Entr.|Qtd. de EPI Entregue
TNF|12|TNF_QTDEVO|N|6|2|Quant.Devol.|Quantidade Devolvida
TNF|13|TNF_MOTIVO|C|1|0|Motivo Entr.|Motivo Entrega EPI
TNF|14|TNF_LOCAL|C|2|0|Almoxarifado|Almoxarifado
TNF|15|TNF_INDDEV|C|1|0|Situação EPI|Situacao do Epi
TNF|16|TNF_DTDEVO|D|8|0|Data Devol.|Data da Devolucao do EPI
TNF|17|TNF_LOCDV|C|2|0|Armazém Dev.|Armazém Devolução
TNF|18|TNF_TIPODV|C|1|0|Repor Estoq.|Repor Estoque
TNF|19|TNF_EPIEFI|C|1|0|Epi Eficaz|Existe Epi Eficaz
TNF|20|TNF_DTRECI|D|8|0|Data Emissão|Dt. Emissao do Recibo
TNF|21|TNF_DTMANU|D|8|0|Ult. Manut.|Data da Ultima Manutencao
TNF|22|TNF_CODFUN|C|5|0|Função|Codigo da Funcao
TNF|23|TNF_NUMSEQ|C|6|0|Num.Seq.SD3|Num. Sequencial do SD3
TNF|24|TNF_CUSTO|N|12|2|Custo|Custo
TNF|25|TNF_NUMSA|C|6|0|Número S.A.|Numero SA
TNF|26|TNF_ITEMSA|C|2|0|Item S.A.|Item S.A.
TNF|27|TNF_LOTECT|C|10|0|Lote|Lote
TNF|28|TNF_LOTESB|C|6|0|Sub-Lote|Sub-Lote
TNF|29|TNF_ENDLOC|C|15|0|Localização|Localizacao
TNF|30|TNF_NSERIE|C|20|0|Número Série|Numero de Serie
TNF|31|TNF_DIGIT1|C|200|0|Dig. Part. 1|Dig. Part. 1
TNF|32|TNF_DIGIT2|C|200|0|Dig. Part. 2|Dig. Part. 2
TNF|33|TNF_DEVBIO|C|1|0|Dev. Biomet|Devolucao Biometria
TNF|34|TNF_SAILOG|C|15|0|Saida Logix|Código de Saida Logix
TNF|35|TNF_ENTLOG|C|15|0|Entr. Logix|Código de Entrega Logix
TNF|36|TNF_CODOBS|C|6|0|Observações|Observações
TNF|37|TNF_OBSLOG|M|10|0|Observações|Observações
TNF|38|TNF_ENTBIO|C|1|0|Ent. Biomet.|Entrega por Biometria
--- ### TNG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNG|01|TNG_FILIAL|C|6|0|Filial|Filial do Sistema
TNG|02|TNG_TIPACI|C|12|0|Tipo Aciden.|Tipo Acidente
TNG|03|TNG_DESTIP|C|220|0|Descricao|Descricao Tipo Acidente
TNG|04|TNG_ESOC|C|9|0|Cod. eSocial|Código eSocial
TNG|05|TNG_ESOC1|C|9|0|Cód. eSoc. 1|Código eSocial 1
TNG|06|TNG_DETAIL|M|10|0|Detalhamento|Detalh. da Situação Ger.
--- ### TNH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNH|01|TNH_FILIAL|C|6|0|Filial|Filial do Sistema
TNH|02|TNH_CODOBJ|C|12|0|Cod. Objeto|Cod. Objeto Causador Acid
TNH|03|TNH_DESOBJ|C|220|0|Descricao|Descricao Objeto Causador
TNH|04|TNH_TIPOBJ|C|1|0|Exibir PCMAT|Exibir PCMAT
TNH|05|TNH_ESOC|C|9|0|Obj. eSocial|Código eSocial
TNH|06|TNH_ESOC1|C|9|0|Sit. eSocial|Código eSocial
--- ### TNI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNI|01|TNI_FILIAL|C|6|0|Filial|Filial do Sistema
TNI|02|TNI_CODPLA|C|8|0|Plano Ação|Codigo do Plano de Acao
TNI|03|TNI_NOMPLA|C|40|0|Nome Plano|Nome Plano
TNI|04|TNI_DTIMPL|D|8|0|Data Impl.|Dt. Implantacao do Plano
TNI|05|TNI_DTINPR|D|8|0|Início Prev.|Dt.Inicio Previsao
TNI|06|TNI_DTFIPR|D|8|0|Term. Prev.|Dt.Fim  Previsao
TNI|07|TNI_DTINRE|D|8|0|Inic. Real|Dt.Inicio Real
TNI|08|TNI_DTFIRE|D|8|0|Term. Real|Dt. Fim Real
TNI|09|TNI_OQUE|C|80|0|O que?|O Que?
TNI|10|TNI_QUEM|C|12|0|Resp. SESMT|Responsavel do SESMT
TNI|11|TNI_ONDE|C|80|0|Onde?|Onde?
TNI|12|TNI_PORQUE|C|80|0|Porque|Porque?
TNI|13|TNI_COMO|C|80|0|Como?|Porque?
TNI|14|TNI_CUSTOP|N|10|2|Custo Prev.|Custo Previsto
TNI|15|TNI_CUSTOR|N|10|2|Custo Real|Custo Real
TNI|16|TNI_QTDEAT|N|8|2|Quant. Atual|Qtde Atual
TNI|17|TNI_META|N|8|2|Meta|Meta
TNI|18|TNI_QTDEFI|N|8|2|Quant. Final|Qtde Final
TNI|19|TNI_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
TNI|20|TNI_QDOCTO|C|16|0|Documento|Documentacao Plano Acao
TNI|21|TNI_CC|C|9|0|Centro Custo|Codigo do Centro de Custo
TNI|22|TNI_MAT|C|6|0|Func. Resp.|Funcionario Responsavel
TNI|23|TNI_ORDEM|C|6|0|Ord. Serviço|Ordem de Servico
TNI|24|TNI_OBS|C|80|0|Observacao|Observacao
TNI|25|TNI_PERCEN|N|3|0|% Concluido|Percentual de Conclusao
TNI|26|TNI_DOCFIL|C|6|0|Filial Doc.|Filial Documentacao
TNI|27|TNI_DOCTO|C|60|0|Documento|Documento Relacionado
TNI|28|TNI_FILFUN|C|6|0|Filial Func.|Filial Func.
TNI|29|TNI_FUNRES|C|6|0|Responsavel|Funcionario Responsavel
TNI|30|TNI_NOMERE|C|20|0|Nome|Nome do Funcionario Resp.
TNI|31|TNI_TIPOPL|C|1|0|Planejamento|Planejamento
TNI|32|TNI_DETALH|M|10|0|Detalhamento|Detalhamento
TNI|33|TNI_MMSYP1|C|6|0|Detalhamento|Detalhamento
--- ### TNJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNJ|01|TNJ_FILIAL|C|6|0|Filial|Filial do Sistema
TNJ|02|TNJ_NUMRIS|C|9|0|Num. Risco|Numero Identifica o Risco
TNJ|03|TNJ_CODPLA|C|6|0|Cod. Plano|Codigo do Plano de Acao
TNJ|04|TNJ_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TNJ|05|TNJ_NOMPLA|C|20|0|Nome Plano|Nome Plano
--- ### TNK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNK|01|TNK_FILIAL|C|6|0|Filial|Filial do Sistema
TNK|02|TNK_CODAMB|C|30|0|Ambiente|Codigo do Ambiente Fisico
TNK|03|TNK_NOMAMB|C|20|0|Nome Ambient|Nome do Ambiente
TNK|04|TNK_MAPA|C|6|0|Mapa Risco|Codigo do Mapa de Risco
TNK|05|TNK_AGENTE|C|9|0|Agente Risco|Codigo do Agente de Risco
TNK|06|TNK_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TNK|07|TNK_QTFUNC|N|5|0|Quant. Func.|Qtde Funcionarios no Amb.
TNK|08|TNK_GRAU|C|1|0|Grau Risco|Grau de Risco
TNK|09|TNK_POSX|N|5|2|Pos. Risco|Posicao do Risco ( x )
TNK|10|TNK_POSY|N|5|2|Pos.-y Risco|Posicao do Risco ( y )
--- ### TNL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNL|01|TNL_FILIAL|C|6|0|Filial|Filial do Sistema
TNL|02|TNL_CODDES|C|8|0|Código|Código da Despesa
TNL|03|TNL_NOMDES|C|40|0|Nome|Nome Despesa
TNL|04|TNL_TIPDES|C|1|0|Tipo|Tipo da Despesa
TNL|05|TNL_INDDES|C|1|0|Indicação|Indicação de Despesas
--- ### TNM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNM|01|TNM_FILIAL|C|6|0|Filial|Filial do Sistema
TNM|02|TNM_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNM|03|TNM_DESACI|C|20|0|Descrição|Descricao do Acidente
TNM|04|TNM_CODDES|C|8|0|Cod. Despesa|Codigo da Despesa Acident
TNM|05|TNM_NOMDES|C|40|0|Nome Despesa|Nome Despesa
TNM|06|TNM_VALDES|N|10|2|Val. Despesa|Val. Despesa
TNM|07|TNM_DTDESP|D|8|0|Data Despesa|Data da Despesa
--- ### TNN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNN|01|TNN_FILIAL|C|6|0|Filial|Filial do Sistema
TNN|02|TNN_MANDAT|C|6|0|Mandato|Codigo do Mandato
TNN|03|TNN_DTINIC|D|8|0|Dt. Inicio|Data Inicio
TNN|04|TNN_DTTERM|D|8|0|Data Term.|Data Termino
TNN|05|TNN_DESCRI|C|40|0|Descrição|Descricao Mandato
TNN|06|TNN_ELEICA|D|8|0|Prev. Eleic.|Data Eleicao
TNN|07|TNN_CONVOC|D|8|0|Conv. Eleic.|Data Convocacao Eleicao
TNN|08|TNN_COMISS|D|8|0|Form. Comis.|Formacao Comissao Eleicao
TNN|09|TNN_COPEDI|D|8|0|Copia Sind.|Copia do Edital Convocaca
TNN|10|TNN_INSCRI|D|8|0|Inscrição|Data Inicio Inscricoes
TNN|11|TNN_EDITAL|D|8|0|Publ. Edital|Publicacao Edital Inscri.
TNN|12|TNN_INSCRF|D|8|0|Fim Inscric.|Data Termino Inscricoes
TNN|13|TNN_ELEICR|D|8|0|Real. Eleic.|Dt. Eleicao
TNN|14|TNN_RESULT|D|8|0|Res. Eleição|Result.Eleic
TNN|15|TNN_CURCIP|D|8|0|Curso|Dt.Curso
TNN|16|TNN_COSIND|D|8|0|Comunc.Resul|Comunc.Resul
TNN|17|TNN_POSSE|D|8|0|Real. Posse|Dt.Rea.Posse
TNN|18|TNN_CALREU|D|8|0|Org. Reun.|Org.Reunioes
TNN|19|TNN_REGURT|D|8|0|Reg. SRTE|Registro DRT
TNN|20|TNN_FILRE1|C|6|0|Filial Secr.|Filial Secretário
TNN|21|TNN_MATRE1|C|6|0|Secretário|Matrícula do Secretário
TNN|22|TNN_FILRE2|C|6|0|Filial Subs.|Filial Secretário Substi.
TNN|23|TNN_MATRE2|C|6|0|Substituto|Matrícula Secretário Sub.
TNN|24|TNN_HORAIN|C|5|0|Hora Início|Hora Inicio Eleicao
TNN|25|TNN_HORAFI|C|5|0|Hora Fim|Hora Fim Eleicao
TNN|26|TNN_VOTOS|N|6|0|Quant. Votos|Quantidade Func. Votou
TNN|27|TNN_VTNULO|N|6|0|Votos Nulos|Qtd. de Votos Nulos.
TNN|28|TNN_FILPRE|C|6|0|Filial Dirig|Filial Dirigente da Mesa
TNN|29|TNN_VTBRAN|N|6|0|Vot. Brancos|Qtd. de Votos Brancos.
TNN|30|TNN_PRESID|C|6|0|Dirig. Mesa|Dirigente de Mesa
TNN|31|TNN_FILSEC|C|6|0|Filial Secr.|Filial Secretario da Mesa
TNN|32|TNN_SECRET|C|6|0|Secr. Mesa|Secretario da Mesa
TNN|33|TNN_OCORRE|M|10|0|Ocorrências|Ocorrencias
TNN|34|TNN_FILPSE|C|6|0|Filial Dirig|Filial Dirigente Sessao
TNN|35|TNN_LOCAL|C|40|0|Local Vot.|Local Votacao
TNN|36|TNN_PRESES|C|6|0|Dirig. Mesa|Dirigente da Sessao
TNN|37|TNN_FILSSE|C|6|0|Filial Sec.|Filial Secretario Sessao
TNN|38|TNN_SECSES|C|6|0|Secretário|Secretario da Sessao
TNN|39|TNN_CC|C|9|0|Centro Custo|Centro de Custo
TNN|40|TNN_NOMECC|C|20|0|Descrição|Nome do centro de custo
TNN|41|TNN_NOMPRE|C|40|0|Nome|Nome Dirigente
TNN|42|TNN_NOMSEC|C|40|0|Nome|Nome Secretário
TNN|43|TNN_CODORI|C|6|0|Cód. Origem|Código Origem
--- ### TNO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNO|01|TNO_FILIAL|C|6|0|Filial|Filial do Sistema
TNO|02|TNO_MANDAT|C|6|0|Mandato|Codigo do Mandato
TNO|03|TNO_FILMAT|C|6|0|Filial Matr.|Filial Matrícula
TNO|04|TNO_MAT|C|6|0|Matrícula|Matricula Funcionario
TNO|05|TNO_NOME|C|20|0|Nome|Nome do Funcionario
TNO|06|TNO_DTCAND|D|8|0|Data Cand.|Data Candidatura Cipa
TNO|07|TNO_VOTOS|N|5|0|Quant. Votos|Quantidade de Votos
TNO|08|TNO_CHAPA|C|4|0|Chapa|Codigo da Chapa
TNO|09|TNO_INDICA|C|1|0|Indicação|Indicacao
TNO|10|TNO_AREA|C|9|0|Área|Área
TNO|11|TNO_NOAREA|C|20|0|Nome|Nome Área
TNO|12|TNO_DTESTB|D|8|0|Data Estab.|Data Estabilidade CIPA
TNO|13|TNO_JUSTIF|M|10|0|Justif. Alt.|Justificativa Alteração
TNO|14|TNO_DTALT|D|8|0|Data Alt.|Data Alteração Estab.
TNO|15|TNO_USUARI|C|40|0|Usuário Alt.|Usuário Alteração Estab.
--- ### TNP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNP|01|TNP_FILIAL|C|6|0|Filial|Filial do Sistema
TNP|02|TNP_EMITEN|C|12|0|Cod. Emit.|Cod. Emit. de Atest/Aut
TNP|03|TNP_NOME|C|80|0|Nome Emiten.|Nome Emit. de Atest/Aut
TNP|04|TNP_ENTCLA|C|8|0|Ent. Classe|Entidade de Classe
TNP|05|TNP_NUMENT|C|12|0|Num. Ent.|Numero na Entidade Classe
TNP|06|TNP_INDFUN|C|1|0|Funcao|Funcao do Usuario
TNP|07|TNP_DESFUN|C|30|0|Desc. Funcao|Descricao da Funcao
TNP|08|TNP_USUARI|C|25|0|Login|Login do Usuário
TNP|09|TNP_UF|C|2|0|UF Ent.|UF Ent. Classe
TNP|10|TNP_ESOC|C|60|0|Cód. eSocial|Código eSocial
--- ### TNQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNQ|01|TNQ_FILIAL|C|6|0|Filial|Filial do Sistema
TNQ|02|TNQ_MANDAT|C|6|0|Mandato|Codigo do Mandato
TNQ|03|TNQ_FILMAT|C|6|0|Filial Matr.|Filial da Matrícula
TNQ|04|TNQ_MAT|C|6|0|Matrícula|Matricula Funcionario
TNQ|05|TNQ_DTINIC|D|8|0|Data Início|Data Início Participanto
TNQ|06|TNQ_DTSAID|D|8|0|Data Saída|Data da Saida da Cipa
TNQ|07|TNQ_NOME|C|20|0|Nome|Nome do Funcionario
TNQ|08|TNQ_TIPCOM|C|1|0|Tipo Compon.|Tipo Componente
TNQ|09|TNQ_INDICA|C|1|0|Indicação|Indicacao
TNQ|10|TNQ_INDFUN|C|1|0|Função Esp.|Funcao Especial
TNQ|11|TNQ_AREA|C|9|0|Área|Área
TNQ|12|TNQ_NOAREA|C|20|0|Nome|Nome Área
TNQ|13|TNQ_MANEXT|C|6|0|Mat. Test. 1|Matricula testemunha 1
TNQ|14|TNQ_DTESTB|D|8|0|Data. Estab.|Data Estabilidade CIPA
TNQ|15|TNQ_JUSTIF|M|10|0|Justif. Alt.|Justificativa Alteração
TNQ|16|TNQ_DTALT|D|8|0|Data Alt.|Data Alteração Estab.
TNQ|17|TNQ_USUARI|C|40|0|Usuário Alt.|Usuário Alteração Estab.
--- ### TNR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNR|01|TNR_FILIAL|C|6|0|Filial|Filial do Sistema
TNR|02|TNR_MANDAT|C|6|0|Mandato|Codigo do Mandato
TNR|03|TNR_DTREUN|D|8|0|Data|Data da Reuniao da Cipa
TNR|04|TNR_HRREUN|C|5|0|Hora|Hora da Reuniao
TNR|05|TNR_TIPREU|C|1|0|Tipo|Tipo Reuniao
TNR|06|TNR_ASSUNT|C|60|0|Assunto|Assunto para Reuniao
TNR|07|TNR_DTREAL|D|8|0|Data Real|Data Realizacao Reuniao
TNR|08|TNR_HRREAL|C|5|0|Hora Real|Hora Real da Reuniao
TNR|09|TNR_DURACA|C|5|0|Duração|Duracao da Reuniao
TNR|10|TNR_LOCAL|C|60|0|Local|Local da Reuniao
TNR|11|TNR_ATA|M|10|0|Ata|Ata Reuniao
TNR|12|TNR_DOCFIL|C|6|0|Filial Docto|Filial Documentacao
TNR|13|TNR_DOCTO|C|16|0|Documento|Documentacao Ord. Serv.
--- ### TNS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNS|01|TNS_FILIAL|C|6|0|Filial|Filial do Sistema
TNS|02|TNS_TIPPAR|C|1|0|Tipo Partic.|Tipo de Participante
TNS|03|TNS_FILMAT|C|6|0|Filial Matr.|Filial Matricula
TNS|04|TNS_MAT|C|6|0|Matricula|Matricula Funcionario
TNS|05|TNS_NOME|C|20|0|Funcionario|Nome do Funcionario
TNS|06|TNS_PRESEN|C|1|0|Compareceu ?|Compareceu na Reuniao ?
TNS|07|TNS_NOMPAR|C|50|0|Nome Partic.|Nome do Participante
TNS|08|TNS_DTREUN|D|8|0|Dt. Reuniao|Data da Reuniao da Cipa
TNS|09|TNS_HRREUN|C|5|0|Hora Reuniao|Hora da Reuniao
TNS|10|TNS_MANDAT|C|6|0|Cod. Mandato|Codigo do Mandato
--- ### TNT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNT|01|TNT_FILIAL|C|6|0|Filial|Filial do Sistema
TNT|02|TNT_MANDAT|C|6|0|Cod. Mandato|Codigo do Mandato
TNT|03|TNT_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNT|04|TNT_DESACI|C|20|0|Nome Acid.|Nome Acidente
TNT|05|TNT_CODPLA|C|6|0|Cod. Plano|Codigo do Plano de Acao
TNT|06|TNT_NOMPLA|C|20|0|Nome Plano|Nome Plano
--- ### TNU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNU|01|TNU_FILIAL|C|6|0|Filial|Filial do Sistema
TNU|02|TNU_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNU|03|TNU_MANDAT|C|6|0|Cod. Mandato|Codigo do Mandato
TNU|04|TNU_RESINV|C|12|0|Resp. Inves.|Responsavel p/Investigac
TNU|05|TNU_NOME|C|20|0|Nome|Nome Responsavel Invest
TNU|06|TNU_DTINVE|D|8|0|Data Invest.|Data da Investigacao
TNU|07|TNU_INVEST|M|10|0|Rel. Invest.|Relatorio da Investigacao
TNU|08|TNU_TREINA|C|1|0|Treinado|Treinado para Funcao ?
TNU|09|TNU_USOEPI|C|1|0|Utiliz. EPI|Utilizava EPI ?
TNU|10|TNU_NORMAS|C|1|0|Conh. Normas|Conhecimento das Normas ?
TNU|11|TNU_DEFEIT|C|1|0|Def. Equip.|Defeito do Equipamento  ?
TNU|12|TNU_IMPROV|C|1|0|Improvisacao|Houve Improvisacao      ?
--- ### TNV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNV|01|TNV_FILIAL|C|6|0|Filial|Filial do Sistema
TNV|02|TNV_MANDAT|C|6|0|Cod. Mandato|Codigo do Mandato
TNV|03|TNV_CODPLA|C|6|0|Cod. Plano|Codigo do Plano de Acao
TNV|04|TNV_NOMPLA|C|20|0|Nome Plano|Nome Plano
--- ### TNW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNW|01|TNW_FILIAL|C|6|0|Filial|Filial do Sistema
TNW|02|TNW_SEQUEN|C|5|0|Sequencial|Numero Sequencial Mensag.
TNW|03|TNW_LOGIN|C|25|0|Login Usuar.|Login do Usuario
TNW|04|TNW_CODUSU|C|12|0|Usuario|Codigo Usuario
TNW|05|TNW_NOMUSU|C|40|0|Nome Usuario|Nome do Usuario
TNW|06|TNW_DTINIC|D|8|0|Data Início|Data Inic.Apres.Mesnagem
TNW|07|TNW_HRINIC|C|5|0|Hora Início|Hora de Inicio Mensagem
TNW|08|TNW_DTFIM|D|8|0|Data Fim|Data Fim Apres. Mensagem
TNW|09|TNW_HRFIM|C|5|0|Hora Fim|Hora Fim Apres. Mensagem
TNW|10|TNW_MENSAG|M|10|0|Mensagem|Descricao da Mensagem
TNW|11|TNW_MOSTRA|C|1|0|Mostrar|Mostrar Mensagem ?
TNW|12|TNW_ANTES|N|3|0|Dias Antes|Avisa quantos dias antes
TNW|13|TNW_CODIGO|C|6|0|Lembrete|Codigo Mandato
TNW|14|TNW_TIPO|C|1|0|Tipo Mensag.|Tipo da Mensagem
TNW|15|TNW_DESTIP|C|60|0|Desc. Tipo|Descricao do Tipo
TNW|16|TNW_USUFIM|C|25|0|Usuário Fin.|Usuário Finalizador
--- ### TNX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNX|01|TNX_FILIAL|C|6|0|Filial|Filial do Sistema
TNX|02|TNX_NUMRIS|C|9|0|Num. Risco|Numero do Risco
TNX|03|TNX_EPI|C|15|0|Cod. EPI|Codigo do EPI
TNX|04|TNX_NOMAGE|C|20|0|Nome Agente|Nome do Agente de Risco
TNX|05|TNX_AGENTE|C|9|0|Agente|Codigo do Agente Risco
TNX|06|TNX_NOMEPI|C|70|0|Nome EPI|Nome do EPI
TNX|07|TNX_TIPO|C|1|0|Tipo Utiliz.|Tipo de Utilizacao do EPI
TNX|08|TNX_FAMIL|C|1|0|Familia EPI|Familia do EPI
--- ### TNY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNY|01|TNY_FILIAL|C|6|0|Filial|Filial do Sistema
TNY|02|TNY_NUMFIC|C|9|0|Ficha Medica|Numero da Ficha Medica
TNY|03|TNY_NOMFIC|C|80|0|Nome|Nome Paciente
TNY|04|TNY_DTINIC|D|8|0|Inic. Afast.|Data Inicio Afastamento
TNY|05|TNY_HRINIC|C|5|0|Hora Inic.|Hora Inicio do Afastament
TNY|06|TNY_DTFIM|D|8|0|Data Fim|Data Final  Afastamento
TNY|07|TNY_HRFIM|C|5|0|Hora Fim|Hora Fim do Afastamento
TNY|08|TNY_GRPCID|C|3|0|Grupo C.I.D.|Grupo C.I.D.
TNY|09|TNY_DESGRP|C|220|0|Descrição|Desc. Grupo
TNY|10|TNY_CID|C|8|0|CID Princip.|CID Principal
TNY|11|TNY_DOENCA|C|220|0|Descrição|Descricao da  Doenca
TNY|12|TNY_EMITEN|C|12|0|Emit. Atest.|Emitente do Atestado
TNY|13|TNY_NOMUSU|C|80|0|Nome|Nome do Usuário
TNY|14|TNY_TIPAFA|C|1|0|Tipo Afasta.|Tipo de Afastamento
TNY|15|TNY_CODAFA|C|3|0|Cód.Ausência|Código da Ausência
TNY|16|TNY_TIPATE|C|1|0|Tipo Atest.|Tipo Atestado
TNY|17|TNY_OBSERV|C|80|0|Observacao|Observacao
TNY|18|TNY_NATEST|C|10|0|Num. Atest.|Numero do Atestado
TNY|19|TNY_DTCONS|D|8|0|Data Cons.|Data da Consulta
TNY|20|TNY_HRCONS|C|5|0|Hora Cons.|Hora da Consulta
TNY|21|TNY_ENDERE|C|30|0|End. Emit.|Endereco do Emitente
TNY|22|TNY_CODESP|C|2|0|Cod. Espec.|Codigo da especialidade
TNY|23|TNY_ESPDES|C|30|0|Descrição|Descricao da Especialidad
TNY|24|TNY_CODABO|C|3|0|Cod. Abono|Codigo do Abono
TNY|25|TNY_ABODES|C|25|0|Descrição|Desc. Abono
TNY|26|TNY_DESCAD|C|30|0|Descrição|Desc. Afast.
TNY|27|TNY_QTDIAS|N|4|0|Dias Afast.|Qtd. Dias Afastado
TNY|28|TNY_DTSAID|D|8|0|Dt.Saida A.D|Dt.Saida A.D
TNY|29|TNY_DTALTA|D|8|0|Dt.Alta A.D|Dt.Alta A.D
TNY|30|TNY_DTSAI2|D|8|0|Dt.Saida A.D|Dt.Saida A.D
TNY|31|TNY_DTALT2|D|8|0|Dt.Alta A.D|Dt.Alta A.D
TNY|32|TNY_DTSAI3|D|8|0|Dt.Saida A.D|Dt.Saida A.D
TNY|33|TNY_DTALT3|D|8|0|Dt.Alta A.D|Dt.Alta A.D
TNY|34|TNY_INDMED|C|1|0|Ind. Medico|Indica Medico Emitente
TNY|35|TNY_OCORRE|C|1|0|Ind. Atend.|Ind. Atendim. Realizado
TNY|36|TNY_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNY|37|TNY_DESACI|C|80|0|Descrição|Descricao do Acidente
TNY|38|TNY_AFRAIS|C|2|0|Afast. RAIS|Cod.Afast.RAIS
TNY|39|TNY_QTDTRA|C|4|0|Dias Trat.|Quant. Dias Tratamento
TNY|40|TNY_ATEANT|C|10|0|Atest. Ant.|Atestado Anterior
TNY|41|TNY_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TNY|42|TNY_TPEFD|C|2|0|Mot. Afast.|Motivo de Afastamento
TNY|43|TNY_COMUOK|C|2|0|Comunicado|Indica se foi comunicado
TNY|44|TNY_COMUNI|C|3|0|Comunicado|Indica se foi comunicado
--- ### TNZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TNZ|01|TNZ_FILIAL|C|6|0|Filial|Filial do Sistema
TNZ|02|TNZ_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TNZ|03|TNZ_CAUSA|C|6|0|Causa Acid.|Causa do Acidente
TNZ|04|TNZ_NOME|C|20|0|Nome Causa|Nome da Causa do Acidente
TNZ|05|TNZ_INDCAU|C|1|0|Indic. Causa|Indica Causa do Acidente
--- ### TO0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO0|01|TO0_FILIAL|C|6|0|Filial|Filial do Sistema
TO0|02|TO0_LAUDO|C|12|0|Laudo|Codigo do Laudo
TO0|03|TO0_NOME|C|60|0|Nome Laudo|Nome do Laudo
TO0|04|TO0_DTINIC|D|8|0|Data Início|Data Inicio Laudo
TO0|05|TO0_DTFIM|D|8|0|Data Final|Data Final do Laudo
TO0|06|TO0_DTVALI|D|8|0|Data Valid.|Data Final Validade Laudo
TO0|07|TO0_CLIENT|C|6|0|Cliente|Codigo do Cliente
TO0|08|TO0_LOJA|C|2|0|Loja|Loja do Cliente
TO0|09|TO0_NOMECL|C|80|0|Nome Cliente|Nome do Cliente
TO0|10|TO0_GRISCO|C|1|0|Grau Risco|Grau de Risco
TO0|11|TO0_QTDFUN|N|5|0|Qtde Funcion|Quantidade Funcionarios
TO0|12|TO0_OBJETI|C|80|0|Objetivo|Objetivo do Laudo
TO0|13|TO0_TIPELA|C|1|0|Tp. Elab.|Tipo de Elaborador
TO0|14|TO0_CODUSU|C|12|0|Resp. Elab.|Responsável Elaboração
TO0|15|TO0_NOMUSU|C|20|0|Nome|Nome do Responsavel
TO0|16|TO0_TERMO|C|12|0|Termo|Termo de Responsabilidade
TO0|17|TO0_FILDOC|C|6|0|Filial Docto|Filial do Documento
TO0|18|TO0_DOCTO|C|16|0|Documento|Documento Relacionado
TO0|19|TO0_RV|C|3|0|Revisao|Num.Sequencial da Revisao
TO0|20|TO0_TIPREL|C|1|0|Tipo Laudo|Tipo de Laudo
TO0|21|TO0_CC|C|9|0|Centro Custo|Centro de Custo
TO0|22|TO0_NOMECC|C|20|0|Descrição|Descricao C.Custo
TO0|23|TO0_DESCRI|M|10|0|Descricao|Descricao do Laudo
TO0|24|TO0_DESC2|M|10|0|Cont. Descr.|Continuacao da Descricao
TO0|25|TO0_MMSYP2|C|6|0|Cont. Descr.|Continuacao da Descricao
TO0|26|TO0_FINALI|C|1|0|Finalidade|Finalidade
TO0|27|TO0_TIPAPR|C|1|0|Tipo Aprov.|Tipo de Aprovador
TO0|28|TO0_APROVA|C|6|0|Aprovador|Código do Aprovador
TO0|29|TO0_NOMAPR|C|30|0|Nome Aprov.|Nome do Aprovador
TO0|30|TO0_ATIVID|C|6|0|Atividade|Atividade Industrial
TO0|31|TO0_DESATI|C|40|0|Descrição|Descrição da Atividade
--- ### TO1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO1|01|TO1_FILIAL|C|6|0|Filial|Filial do Sistema
TO1|02|TO1_LAUDO|C|12|0|Laudo|Codigo do Laudo
TO1|03|TO1_NOMLAU|C|20|0|Nome Laudo|Nome do Laudo
TO1|04|TO1_NUMRIS|C|9|0|Risco|Numero do Risco
TO1|05|TO1_NOMRIS|C|20|0|Nome Risco|Nome do Risco
TO1|06|TO1_RECOME|M|10|0|Recomendacao|Recomendacoes e Consider.
--- ### TO2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO2|01|TO2_FILIAL|C|6|0|Filial|Filial do Sistema
TO2|02|TO2_LAUDO|C|12|0|Laudo|Codigo do Laudo
TO2|03|TO2_NOMLAU|C|20|0|Nome Laudo|Nome do Laudo
TO2|04|TO2_EQPTO|C|6|0|Equipamento|Cod.Equipamento Medicao
TO2|05|TO2_NOEQTO|C|20|0|Nome Equipam|Nome do Equipamento
--- ### TO3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO3|01|TO3_FILIAL|C|6|0|Filial|Filial do Sistema
TO3|02|TO3_LAUDO|C|12|0|Laudo|Codigo do Laudo
TO3|03|TO3_CONTRO|C|6|0|Medida Cont.|Cod.Medida de Controle
TO3|04|TO3_NOMCTR|C|20|0|Nome Medida|Nome Medida de Controle
TO3|05|TO3_DESCRI|M|10|0|Descricao|Descricao Med. Controle
--- ### TO4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO4|01|TO4_FILIAL|C|6|0|Filial|Filial do Sistema
TO4|02|TO4_CONTRO|C|6|0|Controle|Medida de Controle
TO4|03|TO4_NOMCTR|C|40|0|Medida Cont.|Nome Medida Controle
TO4|04|TO4_TIPCTR|C|1|0|Tipo Cont.|Tipo Medida Controle
TO4|05|TO4_DESCRI|M|10|0|Meta|Meta Medida
--- ### TO5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO5|01|TO5_FILIAL|C|6|0|Filial|Filial do Sistema
TO5|02|TO5_LAUDO|C|12|0|Laudo|Codigo do Laudo
TO5|03|TO5_SEQUEN|C|5|0|Sequencia|Sequencia da Avaliacao
TO5|04|TO5_CODAMB|C|30|0|Ambiente|Codigo do Ambiente Fisico
TO5|05|TO5_NOMAMB|C|20|0|Nome|Nome Ambient
TO5|06|TO5_CODFUN|C|5|0|Funcao|Codigo da Funcao
TO5|07|TO5_DESCFU|C|20|0|Desc.Função|Descricao da Funcao
TO5|08|TO5_DESCRI|C|40|0|Descrição|Descricao
TO5|09|TO5_QTD1|N|11|6|Quantidade 1|Quantidade 1
TO5|10|TO5_UNIME1|C|2|0|Unid. Med. 1|Unidade de Medida 1
TO5|11|TO5_QTD2|N|11|6|Quantidade 2|Quantidade 2
TO5|12|TO5_UNIME2|C|2|0|Unid. Med. 2|Unidade de Medida 2
TO5|13|TO5_OBSERV|C|40|0|Observação|Observacao
--- ### TO6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO6|01|TO6_FILIAL|C|6|0|Filial|Filial do Sistema
TO6|02|TO6_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TO6|03|TO6_QUESTI|C|6|0|Questionario|Codigo do Questionario
TO6|04|TO6_NOMQUE|C|20|0|Nome Quest|Nome do Questionario
TO6|05|TO6_DTREAL|D|8|0|Realizacao|Data da Realizacao
TO6|06|TO6_QUESTA|C|3|0|Questao|Numero da Questao
TO6|07|TO6_PERGUN|C|40|0|Pergunta|Pergunta
TO6|08|TO6_RESPOS|C|1|0|Resposta|Resposta a Pergunta
TO6|09|TO6_DESRES|C|30|0|Descr. Resp.|Resposta a Pergunta
TO6|10|TO6_QTRESP|N|9|2|Quantidade|Quantidade Respondida
TO6|11|TO6_COMRES|C|30|0|Complemento|Complemento da Resposta
TO6|12|TO6_DESCRI|M|10|0|Descrição|Descrição
--- ### TO7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO7|01|TO7_FILIAL|C|6|0|Filial|Filial do Sistema
TO7|02|TO7_CODOCO|C|6|0|Ocorrencia|Codigo do Ocorrencia
TO7|03|TO7_DESOCO|C|80|0|Descricao|Descricao da Ocorrencia
--- ### TO8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO8|01|TO8_FILIAL|C|6|0|Filial|Filial do Sistema
TO8|02|TO8_CODOCO|C|6|0|Ocorrencia|Codigo do Ocorrencia
TO8|03|TO8_DESOCO|C|30|0|Desc. Ocorr.|Descrição da Ocorrência
TO8|04|TO8_MAT|C|6|0|Matricula|Matricula Funcionario
TO8|05|TO8_NOME|C|20|0|Funcionario|Nome do Funcionario
TO8|06|TO8_DTOCOR|D|8|0|Dt. Ocorren.|Data Ocorrencia
TO8|07|TO8_GRAVID|C|1|0|Gravidade|Gravidade da Ocorrencia
--- ### TO9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TO9|01|TO9_FILIAL|C|6|0|Filial|Filial do Sistema
TO9|02|TO9_OPCEPC|C|1|0|Opção|Opção ECP
TO9|03|TO9_NUMRIS|C|9|0|Num. Risco|Numero do Risco
TO9|04|TO9_EPC|C|16|0|Codigo EPC|Codigo do EPC
TO9|05|TO9_AGENTE|C|9|0|Agente|Codigo do Agente
TO9|06|TO9_NOMAGE|C|20|0|Nome Agente|Nome do Agente
TO9|07|TO9_NOMEPC|C|20|0|Nome EPC|Nome do EPC
TO9|08|TO9_EFIEPC|C|1|0|EPC Eficaz?|Eficiência do EPC
--- ### TOA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOA|01|TOA_FILIAL|C|6|0|Filial|Filial do Sistema
TOA|02|TOA_CODREQ|C|12|0|Requisito|Codigo do Requisito Legal
TOA|03|TOA_NOMREQ|C|40|0|Nome|Nome do Requisito Legal
TOA|04|TOA_TIPREQ|C|1|0|Tipo|Tipo de Requisito
TOA|05|TOA_CODIGO|C|9|0|Nome Neces.|Cod. Necessidade Legal
TOA|06|TOA_NOME|C|20|0|Nome Neces.|Nome da Necessidade Legal
--- ### TOB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOB|01|TOB_FILIAL|C|6|0|Filial|Filial do Sistema
TOB|02|TOB_CODFUN|C|5|0|Funcao|Codigo da Funcao
TOB|03|TOB_NOMFUN|C|20|0|Nome Funcao|Nome da Funcao
TOB|04|TOB_CC|C|9|0|Centro Custo|Centro de Custo
TOB|05|TOB_DESCC|C|20|0|Nome C.Custo|Nome do Centro de Custo
TOB|06|TOB_DEPTO|C|9|0|Departamento|Codigo Departamento
TOB|07|TOB_TEXTO|M|10|0|Detalhe OS.|Detalhe Ordem de Servico
TOB|08|TOB_TERMO|C|6|0|Termo Resp.|Termo de Responsabilidade
TOB|09|TOB_CODRES|C|12|0|Responsavel|Cod. Usuario Responsavel
TOB|10|TOB_NOMRES|C|20|0|Nome Resp.|Nome  Usuario Responsavel
TOB|11|TOB_DTELAB|D|8|0|Data Elab.|Data de Elaboracao
TOB|12|TOB_DTREVI|D|8|0|Ult. Revisao|Data da Ultima Revisao
TOB|13|TOB_DOCFIL|C|6|0|Filial Docto|Filial Documentacao
TOB|14|TOB_DOCTO|C|16|0|Docto|Documentacao Ord. Serv.
--- ### TOC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOC|01|TOC_FILIAL|C|6|0|Filial|Filial do Sistema
TOC|02|TOC_CODFUN|C|5|0|Funcao|Codigo da Funcao
TOC|03|TOC_CC|C|9|0|Centro Custo|Centro de Custo
TOC|04|TOC_MAT|C|6|0|Matricula|Matricula do Funcionario
TOC|05|TOC_NOME|C|25|0|Nome Func.|Nome do Funcionario
TOC|06|TOC_DTENT|D|8|0|Dt. Entrega|Data de Entrada na O.S.
TOC|07|TOC_DTFIM|D|8|0|Dt. Devol.|Data de saída na O.S.
TOC|08|TOC_DEPTO|C|9|0|Departamento|Codigo Departamento
--- ### TOD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOD|01|TOD_FILIAL|C|6|0|Filial|Filial
TOD|02|TOD_LAUDO|C|12|0|Laudo|Laudo
TOD|03|TOD_CODBEM|C|16|0|Bem|Bem
TOD|04|TOD_NOME|C|40|0|Nome do Bem|Nome do Bem
--- ### TOE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOE|01|TOE_FILIAL|C|6|0|Filial|Filial do Sistema
TOE|02|TOE_CNAE|C|7|0|CNAE|Cod. Nacional Ativ. Econ.
TOE|03|TOE_DESCRI|C|60|0|Descricao|Descricao Ativ. Economica
TOE|04|TOE_GRISCO|C|1|0|Grau Risco|Grau de Risco
TOE|05|TOE_GCIPA|C|5|0|Grupos|Grupos
TOE|06|TOE_GRUPO|C|6|0|Grupo|Código do Grupo
--- ### TOF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOF|01|TOF_FILIAL|C|6|0|Filial|Filial do Sistema
TOF|02|TOF_NUMFIC|C|9|0|Ficha Medica|Ficha Medica
TOF|03|TOF_NOMFIC|C|80|0|Nome|Nome da Funcionaria
TOF|04|TOF_DTULME|D|8|0|Ult. Menstr.|Data Ultima Menstruacao
TOF|05|TOF_DTPART|D|8|0|Data Parto|Data Provavel Parto
TOF|06|TOF_DTSLIC|D|8|0|Data Saida|Data Saida p/ Licenca Mat
TOF|07|TOF_DTRLIC|D|8|0|Data Retorno|Data Retorno licenca mat.
TOF|08|TOF_USERGI|C|17|0|Log de Inclu|Log de Inclusão
TOF|09|TOF_CODAFA|C|3|0|Cód.Ausência|Código da Ausência
TOF|10|TOF_DESCAF|C|30|0|Descrição|Descrição da Ausência
--- ### TOG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOG|01|TOG_FILIAL|C|6|0|Filial|Filial do Sistema
TOG|02|TOG_CODESP|C|2|0|Cod. Espec.|Código da Especialidade
TOG|03|TOG_NOME|C|40|0|Nome Especi.|Nome Especialidade Medica
TOG|04|TOG_DESCRI|C|80|0|Descrição|Descrição Espec. Médica
TOG|05|TOG_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TOH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOH|01|TOH_FILIAL|C|6|0|Filial|Filial do Sisitema
TOH|02|TOH_CC|C|9|0|C.Custo|Centro de Custo
TOH|03|TOH_DESCCC|C|20|0|Desc. CC|Descricao  C. Custo
TOH|04|TOH_CODEPI|C|15|0|EPI|Codigo do EPI
TOH|05|TOH_DESC|C|70|0|Descricao|Descricao EPI
--- ### TOI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOI|01|TOI_FILIAL|C|6|0|Filial|Filial
TOI|02|TOI_CODPAR|C|12|0|Parte Ating.|Parte Ating.
TOI|03|TOI_DESPAR|C|160|0|Descricao|Descricao
TOI|04|TOI_ESOC|C|9|0|Cod. eSocial|Código eSocial
--- ### TOJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOJ|01|TOJ_FILIAL|C|6|0|Filial|Filial
TOJ|02|TOJ_CODLES|C|12|0|Natur. Lesão|Natur. Lesao
TOJ|03|TOJ_NOMLES|C|220|0|Descrição|Descricao
TOJ|04|TOJ_ESOC|C|9|0|Cod. eSocial|Código eSocial
--- ### TOK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOK|01|TOK_FILIAL|C|6|0|Filial|Filial
TOK|02|TOK_GRUPO|C|6|0|Grupo|Código do Grupo
TOK|03|TOK_DESCRI|C|240|0|Descrição|Descrição do Grupo
--- ### TON
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TON|01|TON_FILIAL|C|6|0|Filial|Filial
TON|02|TON_CODFUN|C|5|0|Funcao|Funcao
TON|03|TON_DESFUN|C|30|0|Desc.Funcao|Desc.Funcao
TON|04|TON_CODEXA|C|6|0|Exame|Exame
TON|05|TON_DESEXA|C|30|0|Desc. Exame|Desc. Exame
TON|06|TON_FAIXA|C|2|0|Faixa|Numero Faixa
TON|07|TON_CLIENT|C|6|0|Cliente|Cliente
TON|08|TON_LOJA|C|2|0|Loja|Loja
TON|09|TON_TIPOEX|C|2|0|Tipo Exame|Tipo Exame
TON|10|TON_USERGI|C|17|0|Log de Inclu|Log de Inclusão
--- ### TOQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOQ|01|TOQ_FILIAL|C|6|0|Filial|Filial do Sistema
TOQ|02|TOQ_CODAMB|C|30|0|Amb. Físico|Ambiente Físico
TOQ|03|TOQ_CC|C|9|0|Centro Custo|Centro de Custo
TOQ|04|TOQ_DESCCC|C|40|0|Descrição|Descrição Centro de Custo
--- ### TOR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOR|01|TOR_FILIAL|C|6|0|Filial|Filial do Sistema
TOR|02|TOR_CODAMB|C|30|0|Amb. Físico|Ambiente Físico
TOR|03|TOR_DEPTO|C|9|0|Departamento|Código Departamento
TOR|04|TOR_DESDEP|C|30|0|Descrição|Descrição Departamento
--- ### TOS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOS|01|TOS_FILIAL|C|6|0|Filial|Filial do Sistema
TOS|02|TOS_CODAMB|C|30|0|Amb. Físico|Ambiente Físico
TOS|03|TOS_FUNCAO|C|5|0|Função|Código da Função
TOS|04|TOS_DESFUN|C|20|0|Descrição|Descrição Função
--- ### TOT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOT|01|TOT_FILIAL|C|6|0|Filial|Filial do Sistema
TOT|02|TOT_CODAMB|C|30|0|Amb. Físico|Ambiente Físico
TOT|03|TOT_TAREFA|C|6|0|Tarefa|Código da Tarefa
TOT|04|TOT_DESTAR|C|254|0|Descrição|Descrição Tarefa
--- ### TOU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOU|01|TOU_FILIAL|C|6|0|Filial|Filial do Sistema
TOU|02|TOU_CODAMB|C|30|0|Amb. Físico|Ambiente Físico
TOU|03|TOU_MAT|C|6|0|Matrícula|Matrícula Funcionário
TOU|04|TOU_NOME|C|30|0|Nome|Nome Funcionário
--- ### TOX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOX|01|TOX_FILIAL|C|6|0|Filial|Filial
TOX|02|TOX_LAUDO|C|12|0|Laudo|Numero Laudo Ambiental
TOX|03|TOX_QUESTI|C|6|0|Questionario|Codigo do Questionario
TOX|04|TOX_NOMQUE|C|20|0|Nome Quest|Nome do Questionario
TOX|05|TOX_DTREAL|D|8|0|Realizacao|Data Realizacao
TOX|06|TOX_QUESTA|C|3|0|Questao|Numero da Questao
TOX|07|TOX_PERGUN|C|40|0|Pergunta|Pergunta
TOX|08|TOX_RESPOS|C|1|0|Resposta|Resposta a Pergunta
TOX|09|TOX_DESRES|C|3|0|Descr. Resp.|Reposta a Pergunta
TOX|10|TOX_QTRESP|N|9|0|Quantidade|Quantidade Respondida
TOX|11|TOX_COMRES|C|30|0|Complemento|Complemento da Resposta
TOX|12|TOX_DESCRI|M|10|0|Descrição|Descrição
--- ### TOZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TOZ|01|TOZ_FILIAL|C|6|0|Filial|Filial
TOZ|02|TOZ_LAUDO|C|12|0|Laudo|Laudo
TOZ|03|TOZ_NOMLAU|C|20|0|Nome Laudo|Nome Laudo
TOZ|04|TOZ_PLANO|C|6|0|Plano|Plano
TOZ|05|TOZ_NOMPLA|C|20|0|Descrição|Descrição do Plano
TOZ|06|TOZ_CLIENT|C|6|0|Cliente|Cliente
TOZ|07|TOZ_LOJA|C|2|0|Loja|Loja
--- ### TY0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY0|01|TY0_FILIAL|C|6|0|Filial|Filial
TY0|02|TY0_GRUPO|C|3|0|Grupo|Código do Grupo
TY0|03|TY0_DESCRI|C|200|0|Descrição|Descrição do Grupo
--- ### TY1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY1|01|TY1_FILIAL|C|6|0|Filial|Filial
TY1|02|TY1_SUBGRU|C|4|0|Subgrupo|Código do Subgrupo
TY1|03|TY1_DESCRI|C|200|0|Descrição|Descrição do Subgrupo
TY1|04|TY1_GRUPO|C|3|0|Grupo|Código do Grupo
TY1|05|TY1_DESGRU|C|200|0|Desc. Grupo|Descrição do Grupo
--- ### TY2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY2|01|TY2_FILIAL|C|6|0|Filial|Filial
TY2|02|TY2_CODIGO|C|8|0|Código|Código na TUSS
TY2|03|TY2_DESCRI|C|200|0|Descrição|Descrição na TUSS
TY2|04|TY2_GRUPO|C|3|0|Grupo|Código do Grupo
TY2|05|TY2_DESGRU|C|200|0|Descr. Grupo|Descrição do Grupo
TY2|06|TY2_SUBGRU|C|4|0|Subgrupo|Código do Subgrupo
TY2|07|TY2_DESSUB|C|200|0|Descr. Subg.|Descrição do Subgrupo
--- ### TY3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY3|01|TY3_FILIAL|C|6|0|Filial|Filial
TY3|02|TY3_NUMFIC|C|9|0|Ficha Médica|Ficha Médica
TY3|03|TY3_DTATEN|D|8|0|Dt. Atend.|Data Atedimento
TY3|04|TY3_HRATEN|C|5|0|Hr. Atend.|Hora Atendimento
TY3|05|TY3_INDICA|C|1|0|Indicação|Indicação
TY3|06|TY3_CODMED|C|15|0|Código|Código do Medicamento
TY3|07|TY3_DESMED|C|30|0|Descrição|Descrição do Medicamento
TY3|08|TY3_QUANT|N|9|2|Quantidade|Quantidade de Medicamento
TY3|09|TY3_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
TY3|10|TY3_MPSOLO|M|10|0|Posologia|Posologia
TY3|11|TY3_PSOSYP|C|6|0|Posologia|Posologia
--- ### TY4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY4|01|TY4_FILIAL|C|6|0|Filial|Filial do Sistema
TY4|02|TY4_ID|C|4|0|ID|ID
TY4|03|TY4_TIPO|C|1|0|Tipo|Tipo da Relação
TY4|04|TY4_CC|C|9|0|Centro Custo|Centro de Custo
TY4|05|TY4_CODFUN|C|5|0|Função|Código da Função
TY4|06|TY4_TAREFA|C|6|0|Tarefa|Código da Tarefa
TY4|07|TY4_NUMRIS|C|9|0|Num. Risco|Número do Risco
TY4|08|TY4_CALEND|C|4|0|Treinamento|Código do Treinamento
TY4|09|TY4_DESC|C|20|0|Descrição|Descrição do Treinamento
TY4|10|TY4_CURSO|C|4|0|Curso|Curso do Treinamento
TY4|11|TY4_DESCCU|C|30|0|Desc. Curso|Descrição do Curso
TY4|12|TY4_TURMA|C|3|0|Turma|Turma do Treinamento
--- ### TY7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY7|01|TY7_FILIAL|C|6|0|Filial|Filial do Sistema
TY7|02|TY7_NUMASO|C|6|0|Número ASO|Número do ASO
TY7|03|TY7_PERMIS|C|6|0|Num. Perm.|Nº Permissão de Trabalho
TY7|04|TY7_SEQPER|C|3|0|Sequência|Sequência Permissão
TY7|05|TY7_TIPERM|C|1|0|Tipo Per.|Tipo de Permissão
--- ### TY8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY8|01|TY8_FILIAL|C|6|0|Filial|Filial do Sistema
TY8|02|TY8_FORNEC|C|6|0|Fornecedor|Fornecedor
TY8|03|TY8_LOJA|C|2|0|Loja|Loja
TY8|04|TY8_CODEPI|C|15|0|EPI|EPI
TY8|05|TY8_MAT|C|6|0|Matrícula|Matrícula
TY8|06|TY8_DTREAL|D|8|0|Dt. Real.|Data de Realização
TY8|07|TY8_QUESTI|C|6|0|Questionário|Questionário
TY8|08|TY8_QUESTA|C|3|0|Questão|Questão
TY8|09|TY8_RESPOS|C|1|0|Resposta|Resposta
TY8|10|TY8_DESCRI|M|10|0|Descrição|Descrição
TY8|11|TY8_USERGI|C|17|0|Log de inc.|Log de Inclusão
TY8|12|TY8_APROVA|C|1|0|EPI Aprov.?|EPI Aprovado?
--- ### TY9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TY9|01|TY9_FILIAL|C|6|0|Filial|Filial Sistema
TY9|02|TY9_CODUSU|C|12|0|Atendente|Codigo Medico Atendente
TY9|03|TY9_NOMUSU|C|20|0|Nome|Nome do Usuario
TY9|04|TY9_DTCONS|D|8|0|Data|Data da Consulta
TY9|05|TY9_HRCONS|C|5|0|Hora|Hora da Consulta
TY9|06|TY9_OBSCON|C|50|0|Observação|Observação do Médico
TY9|07|TY9_QTDHRS|C|5|0|Quant. Horas|Quant. Horas Atend.
TY9|08|TY9_TIPOAG|C|1|0|Tipo Agend.|Tipo de Agendendamento
--- ### TYA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYA|01|TYA_FILIAL|C|6|0|Filial|Filial do Sistema
TYA|02|TYA_CODFUN|C|5|0|Função|Código da Função
TYA|03|TYA_PERINI|D|8|0|Vigência|Data Vigência
TYA|04|TYA_MDESFU|M|10|0|Descr. Per.|Descrição do Período
TYA|05|TYA_ODESFU|C|6|0|Descr. Per.|Descrição do Periodo
TYA|06|TYA_CC|C|9|0|Centro Custo|Codigo do Centro de Custo
TYA|07|TYA_DESCCC|C|40|0|Descrição|Descrição Centro Custo
TYA|08|TYA_DEPTO|C|9|0|Departamento|Codigo Departamento
TYA|09|TYA_DESCDP|C|30|0|Descricao|Descricao Departamento
--- ### TYB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYB|01|TYB_FILIAL|C|6|0|Filial|Filial do Sistema
TYB|02|TYB_NUMFIC|C|9|0|Ficha Médica|Número da Ficha Médica
TYB|03|TYB_NOMFIC|C|80|0|Nome|Nome Ficha Médica
TYB|04|TYB_EXAME|C|6|0|Exame|Exame
TYB|05|TYB_HRPROG|C|5|0|Hora Prog.|Hora Programada
TYB|06|TYB_DTPROG|D|8|0|Data Exame|Data Exame
TYB|07|TYB_OFTIPO|C|1|0|Tipo Oftalm.|Tipo Oftalmológico
TYB|08|TYB_OLHOEL|N|3|0|Olho Esq.|Olho Esquerdo
TYB|09|TYB_OLHODL|N|3|0|Olho Dir.|Olho Direito
TYB|10|TYB_OLHOAL|N|3|0|Ambos|Ambos Olhos
TYB|11|TYB_FORILL|N|3|1|Foria Lat.|Foria Lateral
TYB|12|TYB_FORIVL|N|3|1|Foria Vert.|Foria Vertical
TYB|13|TYB_FORRPL|C|1|0|Resposta|Resposta da Fusão
TYB|14|TYB_FORIFL|C|60|0|Fusão|Fusão
TYB|15|TYB_ESTREL|C|1|0|Resposta|Resposta da Esteropsia
TYB|16|TYB_ESTERL|C|60|0|Estereopsia|Estereopsia
TYB|17|TYB_CORREL|C|1|0|C/ Correção|Com Correção
TYB|18|TYB_OLHOEP|N|3|0|Olho Esq.|Olho Esquerdo
TYB|19|TYB_OLHODP|N|3|0|Olho Dir.|Olho Direito
TYB|20|TYB_OLHOAP|N|3|0|Ambos|Ambos Olhos
TYB|21|TYB_FORILP|N|3|1|Foria Lat.|Foria Lateral
TYB|22|TYB_FORIVP|N|3|1|Foria Vert.|Foria Vertical
TYB|23|TYB_FORRPP|C|1|0|Resposta|Resposta da Fusão
TYB|24|TYB_FORIFP|C|60|0|Fusão|Fusão
TYB|25|TYB_ESTREP|C|1|0|Resposta|Resposta da Esteropsia
TYB|26|TYB_ESTERP|C|60|0|Estereopsia|Estereopsia
TYB|27|TYB_CORREP|C|1|0|C/ Correção|Com Correção
TYB|28|TYB_COR1|C|1|0|92|92
TYB|29|TYB_COR2|C|1|0|56|56
TYB|30|TYB_COR3|C|1|0|79|79
TYB|31|TYB_COR4|C|1|0|23|23
TYB|32|TYB_VISUE|C|1|0|Olho Esq.|Olho Esquerdo
TYB|33|TYB_VISUD|C|1|0|Olho Dir.|Olho Direito
TYB|34|TYB_REFERE|C|1|0|Referencial|Referencial
TYB|35|TYB_AGRAVA|C|1|0|Agravamento|Agravamento
TYB|36|TYB_ORIGEM|C|1|0|Origem|Origem
TYB|37|TYB_USACOR|C|1|0|Usa Correção|Usa Correção?
TYB|38|TYB_TIPO|C|1|0|Tipo|Tipo de Correção
TYB|39|TYB_DTRESU|D|8|0|Data Result.|Data do Resultado
TYB|40|TYB_CODRES|C|4|0|Resultado|Código Resultado
TYB|41|TYB_INDRES|C|1|0|Ind. Result.|Indica Tipo Resultado
TYB|42|TYB_EQUIPA|C|6|0|Equipamento|Equipamento
TYB|43|TYB_NOMEQ|C|20|0|Descrição|Nome do Equipamento
TYB|44|TYB_DTAFER|D|8|0|Aferição|Data Aferição
TYB|45|TYB_CALIBR|D|8|0|Calibração|Data Calibração
TYB|46|TYB_ATENDE|C|12|0|Atendente|Atendente
TYB|47|TYB_NOMATE|C|20|0|Nome Atend.|Nome do Atendente
TYB|48|TYB_DETALH|C|6|0|Detalhes|Detalhes
TYB|49|TYB_DETALM|M|10|0|Detalhes|Detalhes
TYB|50|TYB_OBSERV|C|6|0|Observação|Observação
TYB|51|TYB_OBSERM|M|10|0|Observação|Observação
--- ### TYC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYC|01|TYC_FILIAL|C|6|0|Filial|Filial do Sistema
TYC|02|TYC_NUMFIC|C|9|0|Ficha Médica|Número da Ficha Médica
TYC|03|TYC_NOMFIC|C|80|0|Nome|Nome Ficha Médica
TYC|04|TYC_EXAME|C|6|0|Exame|Exame
TYC|05|TYC_HRPROG|C|5|0|Hora Prog.|Hora Programada
TYC|06|TYC_DTPROG|D|8|0|Data Exame|Data Exame
TYC|07|TYC_OLHOEL|N|3|0|Olho Esq.|Olho Esquerdo
TYC|08|TYC_OLHODL|N|3|0|Olho Dir.|Olho Direito
TYC|09|TYC_OLHOAL|N|3|0|Ambos|Ambos Olhos
TYC|10|TYC_CORREL|C|1|0|C/ Correção|Com Correção
TYC|11|TYC_REFERE|C|1|0|Referencial|Referencial
TYC|12|TYC_AGRAVA|C|1|0|Agravamento|Agravamento
TYC|13|TYC_ORIGEM|C|1|0|Origem|Origem
TYC|14|TYC_USACOR|C|1|0|Usa Correção|Usa Correção?
TYC|15|TYC_TIPO|C|1|0|Tipo|Tipo de Correção
TYC|16|TYC_DTRESU|D|8|0|Data Result.|Data do Resultado
TYC|17|TYC_CODRES|C|4|0|Resultado|Código Resultado
TYC|18|TYC_INDRES|C|1|0|Ind. Result.|Indica Tipo Resultado
TYC|19|TYC_EQUIPA|C|6|0|Equipamento|Equipamento
TYC|20|TYC_NOMEQ|C|20|0|Descrição|Nome do Equipamento
TYC|21|TYC_DTAFER|D|8|0|Aferição|Data Aferição
TYC|22|TYC_CALIBR|D|8|0|Calibração|Data Calibração
TYC|23|TYC_ATENDE|C|12|0|Atendente|Atendente
TYC|24|TYC_NOMATE|C|20|0|Nome Atend.|Nome do Atendente
TYC|25|TYC_DETALH|C|6|0|Detalhes|Detalhes
TYC|26|TYC_DETALM|M|10|0|Detalhes|Detalhes
TYC|27|TYC_OBSERV|C|6|0|Observação|Observação
TYC|28|TYC_OBSERM|M|10|0|Observações|Observações
TYC|29|TYC_OFTIPO|C|1|0|Tipo Oftalm.|Tipo Oftalmológico
--- ### TYD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYD|01|TYD_FILIAL|C|6|0|Filial|Filial do Sistema
TYD|02|TYD_NUMASO|C|6|0|Num. ASO|Número do ASO
TYD|03|TYD_CODTAR|C|6|0|Tarefa|Código da Tarefa
TYD|04|TYD_NOMTAR|C|40|0|Nome Tarefa|Nome Tarefa
--- ### TYE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYE|01|TYE_FILIAL|C|6|0|Filial|Filial
TYE|02|TYE_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TYE|03|TYE_CAUSA|C|12|0|Agente Causa|Agente Causador de Acid.
TYE|04|TYE_DESCAU|C|220|0|Descr. Causa|Descrição Causador Acid.
--- ### TYF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYF|01|TYF_FILIAL|C|6|0|Filial|Filial do Sistem
TYF|02|TYF_ACIDEN|C|6|0|Acidente|Numero Acidente Trabalho
TYF|03|TYF_CODPAR|C|12|0|Codigo Parte|Codigo Parte Atingida
TYF|04|TYF_DESPAR|C|160|0|Desc. Parte|Descrição Parte
TYF|05|TYF_LATERA|C|1|0|Lateralidade|Lateralidade
--- ### TYG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYG|01|TYG_FILIAL|C|6|0|Filial|Filial do Sistema
TYG|02|TYG_CODAMB|C|30|0|Cod. Amb.|Código do Ambiente
TYG|03|TYG_AGENTE|C|9|0|Agente|Código do Agente de Risco
TYG|04|TYG_NOMAGE|C|40|0|Nome Agente|Nome do Agente de Risco
--- ### TYH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYH|01|TYH_FILIAL|C|6|0|Filial|Filial do sistema
TYH|02|TYH_ANO|C|4|0|Ano|Ano do custo
TYH|03|TYH_BENEF|N|12|2|Benefício|Valor pago em benefícios
TYH|04|TYH_REMUN|N|12|2|Remuneração|Valor pago em remuneração
--- ### TYZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TYZ|01|TYZ_FILIAL|C|6|0|Filial|Filial do Sistema
TYZ|02|TYZ_SEQ|C|3|0|Sequencia|Sequencia
TYZ|03|TYZ_MAT|C|6|0|Matricula|Matricula
TYZ|04|TYZ_TIPO|C|1|0|Tipo Afast.|Tipo Afastamento
TYZ|05|TYZ_DTSAID|D|8|0|Data Saída|Data Saída
TYZ|06|TYZ_DTALTA|D|8|0|Data Alta|Data  Alta
TYZ|07|TYZ_NATEST|C|10|0|Num. Atest.|Numero Atestado
TYZ|08|TYZ_TIPOAF|C|3|0|Cod. Ausenc.|Código Ausência
--- ### TA0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA0|01|TA0_FILIAL|C|6|0|Filial|Filial do Sistema
TA0|02|TA0_CODLEG|C|12|0|Requisito|Requisito
TA0|03|TA0_EMENTA|C|80|0|Tema da Lei|Tema da Lei
TA0|04|TA0_TIPO|C|12|0|Tipo|Tipo
TA0|05|TA0_DESCRI|M|10|0|Descrição|Descrição
TA0|06|TA0_ORIGEM|C|1|0|Origem|Origem da Legislacao
TA0|07|TA0_CODRES|C|12|0|Resolução|Resolução
TA0|08|TA0_NUMRES|C|12|0|Nº Resolução|Nº Resolução
TA0|09|TA0_OREMIS|C|12|0|Órgão Em.|Órgão Emissor
TA0|10|TA0_DTEMIS|D|8|0|Data Emissão|Data Emissão
TA0|11|TA0_DTPUBL|D|8|0|Data Public.|Data de Publicacao
TA0|12|TA0_SITE|C|80|0|Site|Site
TA0|13|TA0_DOCFIL|C|6|0|Filial Docum|Filial do Documento
TA0|14|TA0_DOCTO|C|16|0|Documento|Documento da Demanda
TA0|15|TA0_DTVIGE|D|8|0|Vig. Inic.|Vig. Inic.
TA0|16|TA0_DTVENC|D|8|0|Vig. Fim|Vig. Fim
TA0|17|TA0_RESPON|C|16|0|Responsavel|Codigo do Responsavel
TA0|18|TA0_NOMRES|C|40|0|Nome|Nome do Responsavel
TA0|19|TA0_OBRIGA|M|10|0|Obrigações|Obrigações da Empresa
TA0|20|TA0_ACOES|M|10|0|Ações|Ações de Controle Amb.
TA0|21|TA0_EST|C|2|0|Estado|Sigla da Federacao
TA0|22|TA0_DTVCTO|N|3|0|Dias Venc.|Dias para verificar venc
TA0|23|TA0_TIPCER|C|1|0|Tip. Cert.|Tip. Cert.
TA0|24|TA0_ORGCER|C|3|0|Org. Certif.|Org. Ceriti.
TA0|25|TA0_NOMCER|C|40|0|Certificador|Certificador
TA0|26|TA0_SITUAC|C|1|0|Situacao|Situacao
TA0|27|TA0_RV|C|3|0|Cod. Revisão|Código revisão documento
--- ### TA1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA1|01|TA1_FILIAL|C|6|0|Filial|Filial do Sistema
TA1|02|TA1_CODAVA|C|3|0|Avaliação|Cód Critério de Avaliação
TA1|03|TA1_DESCRI|C|40|0|Descrição|Descricao
TA1|04|TA1_PESO|N|3|0|Peso|Peso escolha do criterio
--- ### TA2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA2|01|TA2_FILIAL|C|6|0|Filial|Filial do Sistema
TA2|02|TA2_CODAVA|C|3|0|Avaliação|Cód Critério de Avaliação
TA2|03|TA2_CODOPC|C|3|0|Cod. Opção|Cód. Opção de Avaliação
TA2|04|TA2_OPCAO|C|20|0|Opção|Opcao do Criterio de Aval
TA2|05|TA2_PESO|N|3|0|Peso %|Peso Escolha do Criterio
--- ### TA3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA3|01|TA3_FILIAL|C|6|0|Filial|Filial do Sistema
TA3|02|TA3_CODFOR|C|3|0|Fórmula|Código da Fórmula
TA3|03|TA3_DESCRI|C|40|0|Descrição|Descricao da Formula
TA3|04|TA3_FORMUL|M|10|0|Formula|Formula
TA3|05|TA3_QUESTI|C|6|0|Questionário|Questionário
TA3|06|TA3_TPFORM|C|1|0|Tipo Fórmula|Tipo Fórmula
--- ### TA4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA4|01|TA4_FILIAL|C|6|0|Filial|Filial do Sistema
TA4|02|TA4_CODASP|C|6|0|Aspecto|Código do Aspecto
TA4|03|TA4_DESCRI|C|70|0|Descrição|Descricao do Aspecto
TA4|04|TA4_MEIO|C|1|0|Meio Afetado|Meio Afetado
TA4|05|TA4_ELEMEN|C|1|0|Elem Afetado|Elemento Afetado
TA4|06|TA4_OBSERV|M|10|0|Observações|Observações do Aspecto
--- ### TA5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA5|01|TA5_FILIAL|C|6|0|Filial|Filial do Sistema
TA5|02|TA5_CODLEG|C|12|0|Requisitos|Requisitos
TA5|03|TA5_NOMLEG|C|20|0|Descrição|Desc Requisito
TA5|04|TA5_RESULT|C|10|0|Resultado|Resultado
TA5|05|TA5_CODCLA|C|6|0|Classe|Código da Classe
TA5|06|TA5_NOMCLA|C|20|0|Nome Classe|Nome da Classe
TA5|07|TA5_CODFOR|C|3|0|Fórmula|Código da Fórmula
TA5|08|TA5_DESFOR|C|20|0|Desc Formula|Descricao da Formula
TA5|09|TA5_DTRESU|D|8|0|Data Aval.|Data do Resultado
--- ### TA6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA6|01|TA6_FILIAL|C|6|0|Filial|Filial do Sistema
TA6|02|TA6_CODAVA|C|3|0|Critério|Cód Critério de Avaliação
TA6|03|TA6_DESCRI|C|40|0|Descricao|Descricao
TA6|04|TA6_TIPO|C|1|0|Tipo Aval.|Tipo de Avalicao
TA6|05|TA6_TITULO|C|1|0|Titulo|Titulo da Avaliacao
TA6|06|TA6_PESO|N|3|0|Peso|Peso
TA6|07|TA6_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### TA7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA7|01|TA7_FILIAL|C|6|0|Filial|Filial do Sistema
TA7|02|TA7_CODAVA|C|3|0|Avaliação|Código Critério Avaliação
TA7|03|TA7_CODOPC|C|3|0|Cod. Opção|Cód. Opção Critério Aval.
TA7|04|TA7_OPCAO|C|30|0|Opcao Aval.|Opcao Criterio de Aval.
TA7|05|TA7_PESO|N|3|0|Peso|Peso Escolha Criterio
TA7|06|TA7_PLANAC|C|1|0|Plano Ação?|Necessita Plano Ação?
TA7|07|TA7_PLANEM|C|1|0|Plano Emerg?|Necessita Plano Emerg?
TA7|08|TA7_OBJETI|C|1|0|Objetivo?|Exibe Objetivo?
TA7|09|TA7_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### TA8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA8|01|TA8_FILIAL|C|6|0|Filial|Filial do Sistema
TA8|02|TA8_CODCLA|C|6|0|Classe|Código da Classe
TA8|03|TA8_DESCRI|C|40|0|Desc. Classe|Descricao da Classe
TA8|04|TA8_LIMMIN|N|9|2|Peso Minimo|Peso min. p/ se enquadrar
TA8|05|TA8_LIMMAX|N|9|2|Peso Maximo|Peso Max. p/ se enquadrar
TA8|06|TA8_PLANAC|C|1|0|Plano Ação?|Necessita Plano Ação?
TA8|07|TA8_PLANEM|C|1|0|Plano Emerg?|Necessita Plano Emerg?
TA8|08|TA8_OBJETI|C|1|0|Objetivo?|Exige Objetivo?
--- ### TA9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TA9|01|TA9_FILIAL|C|6|0|Filial|Filial do Sistema
TA9|02|TA9_CODASP|C|6|0|Aspecto|Código do Aspecto
TA9|03|TA9_CODAVA|C|3|0|Avaliação|Código da Avaliação
TA9|04|TA9_CODOPC|C|3|0|Opção|Código da Opção
TA9|05|TA9_DTRESU|D|8|0|Data Result.|Data do Resultado
TA9|06|TA9_PESO|N|3|0|Peso|Peso
TA9|07|TA9_RESULT|N|5|0|Resultado|Resultado da Avaliacao
--- ### TAA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAA|01|TAA_FILIAL|C|6|0|Filial|Filial do Sistema
TAA|02|TAA_SUBPLA|C|6|0|Sub. Plano|Sub Plano de Acäo
TAA|03|TAA_CODPLA|C|6|0|Plano Ação|Cód. do Plano de Ação
TAA|04|TAA_NOME|C|80|0|Nome Plano|Nome do Plano de Acao
TAA|05|TAA_DTIMPL|D|8|0|Data Impl.|Data da Implantacao
TAA|06|TAA_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TAA|07|TAA_NOMCC|C|40|0|Nome C.Custo|Nome do Centro de Custo
TAA|08|TAA_DTINPR|D|8|0|Inic. Prev.|Data Inicio Previsto
TAA|09|TAA_DTFIPR|D|8|0|Term. Prev.|Data de Termino Previsto
TAA|10|TAA_DTINRE|D|8|0|Inic. Real|Data Inicio Real
TAA|11|TAA_DTFIRE|D|8|0|Term. Real|Data de Termino Real
TAA|12|TAA_OQUE|C|80|0|O que?|O que?
TAA|13|TAA_MAT|C|16|0|Responsavel|Responsavel
TAA|14|TAA_NOMRES|C|30|0|Nome Resp.|Nome do Responsavel
TAA|15|TAA_ONDE|C|80|0|Onde?|Onde?
TAA|16|TAA_PORQUE|C|80|0|Por que?|Por que?
TAA|17|TAA_COMO|C|80|0|Como?|Como?
TAA|18|TAA_CUSTOP|N|10|2|Custo Prev.|Custo Previsto
TAA|19|TAA_CUSTOR|N|10|2|Custo Real|Custo Real
TAA|20|TAA_QTDATU|N|9|2|Quant. Atual|Quantidade Atual
TAA|21|TAA_META|N|9|2|Meta|Meta
TAA|22|TAA_QTDFIM|N|9|2|Quant. Final|Quantidade Final
TAA|23|TAA_PERCEN|N|3|0|% Concluido|Percentual Concluido
TAA|24|TAA_OBS|M|10|0|Observação|Observacao
TAA|25|TAA_DOCFIL|C|6|0|Filial Doc.|Filial do Documento
TAA|26|TAA_DOCTO|C|16|0|Documento|Documento Relacionado
TAA|27|TAA_USUARI|C|8|0|Usuario|Usuario
TAA|28|TAA_STATUS|C|1|0|Status|Status do Plano de Acäo
TAA|29|TAA_TPMETA|C|1|0|Tipo de Meta|Tipo de Meta
TAA|30|TAA_FORMUL|C|3|0|Fórmula Meta|Fórmula da meta
TAA|31|TAA_DESMET|C|40|0|Descrição|Descrição da Fórmula
TAA|32|TAA_METINI|N|12|3|Meta Inicial|Meta Inicial
TAA|33|TAA_METFIM|N|12|3|Meta Final|Meta Final
TAA|34|TAA_UNIMET|C|2|0|Unidade Meta|Unidade de Medida da Meta
TAA|35|TAA_FORFEC|C|3|0|Form. Fech.|Fórmula de Fechamento
TAA|36|TAA_DESFFE|C|40|0|Descrição|Descrição da Fórmula
TAA|37|TAA_TIPMET|C|1|0|Tipo da Meta|Tipo da Meta
TAA|38|TAA_DTPRFI|C|1|0|Final Prev.|Finaliza na data prevista
TAA|39|TAA_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
TAA|40|TAA_ORDEM|C|6|0|Ord. Servico|Ordem de Servico
TAA|41|TAA_FILFUN|C|6|0|Filial Func.|Filial Funcionario
TAA|42|TAA_TIPOPL|C|1|0|Planejamento|Planejamento
--- ### TAB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAB|01|TAB_FILIAL|C|6|0|Filial|Filial do Sistema
TAB|02|TAB_ORDEM|C|6|0|Ordem|N. Ordem
TAB|03|TAB_CODASP|C|6|0|Aspecto|Código do Aspecto
TAB|04|TAB_NOMASP|C|40|0|Nome Aspecto|Nome do Aspecto
TAB|05|TAB_CODIMP|C|6|0|Impacto|Código do Impacto
TAB|06|TAB_NOMIMP|C|40|0|Nome Impacto|Nome do Impacto
TAB|07|TAB_CODCLA|C|6|0|Classe|Código da Classe
TAB|08|TAB_NOMCLA|C|20|0|Nome Classe|Nome da Classe
TAB|09|TAB_CODFOR|C|3|0|Fórmula|Código da Fórmula
TAB|10|TAB_DESFOR|C|20|0|Desc Formula|Descricao da Formula
TAB|11|TAB_CODPLA|C|6|0|Plano|Código do Plano de Ação
TAB|12|TAB_NOMPLA|C|20|0|Nome Plano|Nome do Plano
TAB|13|TAB_RESULT|N|9|2|Resultado|Resultado
TAB|14|TAB_CODEST|C|3|0|Estrutura|Código da Estrutura
TAB|15|TAB_CODNIV|C|3|0|Nível|Código do Nível
TAB|16|TAB_DESNIV|C|56|0|Desc. Nivel|Descricao do Nivel
TAB|17|TAB_DTRESU|D|8|0|Data Result.|Data do Resultado
TAB|18|TAB_DESCRI|M|10|0|Observacao|Observacao da Avaliacao
TAB|19|TAB_DTFINA|D|8|0|Data Final|Data Final da Avaliacao
TAB|20|TAB_RESUL2|N|9|2|Resultado 2|Resultado da fórmula 2
TAB|21|TAB_RESUL3|N|9|2|Resultado 3|Resultado da fórmula 3
TAB|22|TAB_RESUL4|N|9|2|Resultado 4|Resultado da fórmula 4
TAB|23|TAB_RESUL5|N|9|2|Resultado 5|Resultado da fórmula 5
TAB|24|TAB_CODEME|C|6|0|Plano Emerg.|Cod. do Plano Emergencial
TAB|25|TAB_SITUAC|C|1|0|Situacao|Situacao do Desempenho
TAB|26|TAB_CODOBJ|C|6|0|Objetivo|Código do Objetivo
TAB|27|TAB_NOMOBJ|C|40|0|Descrição|Descrição do Objetivo
TAB|28|TAB_REVISA|C|6|0|Cod.Revisao|Codigo da Revisao
--- ### TAC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAC|01|TAC_FILIAL|C|6|0|Filial|Filial do Sistema
TAC|02|TAC_CODLEG|C|12|0|Legislação|Código da Legislação
TAC|03|TAC_CODAVA|C|3|0|Avaliação|Código Avaliação
TAC|04|TAC_NOMAVA|C|20|0|Nome Aval.|Nome da Avaliacao
TAC|05|TAC_CODOPC|C|3|0|Opção|Código da Opção
TAC|06|TAC_DTRESU|D|8|0|Dt Resultado|Data do Resultado
TAC|07|TAC_PESO|N|3|0|Peso|Peso
TAC|08|TAC_RESULT|N|9|2|Resultado|Resultado Avaliacao
--- ### TAD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAD|01|TAD_FILIAL|C|6|0|Filial|Filial do Sistema
TAD|02|TAD_CODAVA|C|3|0|Avaliação|Código Avaliação
TAD|03|TAD_NOMAVA|C|20|0|Nome Aval.|Nome Avaliacao
TAD|04|TAD_CODOPC|C|3|0|Opção|Código da Opção
TAD|05|TAD_OK|C|1|0|Marcado?|Registro Marcado
TAD|06|TAD_PESO|N|3|0|Peso %|Peso
TAD|07|TAD_INDICA|C|1|0|Indicacao|Indicacao da Avaliacao
TAD|08|TAD_ORDEM|C|6|0|N. Ordem|Numero da Ordem
--- ### TAE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAE|01|TAE_FILIAL|C|6|0|Filial|Filial do Sistema
TAE|02|TAE_CODIMP|C|6|0|Impacto|Código do Impacto
TAE|03|TAE_DESCRI|C|40|0|Desc Impacto|Descricao do Impacto
TAE|04|TAE_OBSERV|M|10|0|Observações|Observações do Impacto
--- ### TAF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAF|01|TAF_FILIAL|C|6|0|Filial|Filial do Sistema
TAF|02|TAF_CODEST|C|3|0|Estrutura|Código da Estrutura
TAF|03|TAF_CODNIV|C|6|0|Nível|Código Nível
TAF|04|TAF_NOMNIV|C|56|0|Nome Nível|Nome do Nivel
TAF|05|TAF_NIVEL|N|3|0|Nível|Nivel
TAF|06|TAF_NIVSUP|C|6|0|Cod. Niv Sup|Codigo do Nivel Superior
TAF|07|TAF_MAT|C|16|0|Responsável|Responsavel
TAF|08|TAF_NOMRES|C|30|0|Nome|Nome do Responsavel
TAF|09|TAF_INDCON|C|1|0|Ind Conteudo|Indicador de Conteudo
TAF|10|TAF_CODCON|C|16|0|Conteúdo|Código do Conteúdo
TAF|11|TAF_MODSGA|C|1|0|Usado SGA|Usado no Mod. SGA
TAF|12|TAF_MODMNT|C|1|0|Usado MNT|Usado no Mod. MNT
TAF|13|TAF_MODMDT|C|1|0|Usado MDT|Usado no Mod. MDT
TAF|14|TAF_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TAF|15|TAF_NOMCC|C|20|0|Nome C.C.|Nome do Centro de Custo
TAF|16|TAF_CENTRA|C|6|0|C. Trabalho|Centro de Trabalho
TAF|17|TAF_NOMTRA|C|20|0|Nome C.Trab.|Nome Centro Trabalho
TAF|18|TAF_DOCFIL|C|6|0|Filial Docto|Filial do Documento
TAF|19|TAF_DOCTO|C|16|0|Documento|Documento
TAF|20|TAF_ORDEM|C|6|0|Ordem|Define a posicao do nivel
TAF|21|TAF_ETAPA|C|1|0|Etapa ?|E uma etapa do Processo ?
TAF|22|TAF_PLANTA|C|1|0|Planta Gráf.|Planta Gráfica
TAF|23|TAF_TIPIMG|C|1|0|Tipo Imagem|Tipo de Imagem
TAF|24|TAF_IMAGEM|C|30|0|Imagem|Imagem
TAF|25|TAF_POSX|N|4|0|Posicao em X|Posicao em X
TAF|26|TAF_POSY|N|4|0|Posicao em Y|Posicao em Y
TAF|27|TAF_TAMX|N|7|2|Largura|Largura da Imagem
TAF|28|TAF_TAMY|N|7|2|Altura|Altura da Imagem
TAF|29|TAF_MOVBLO|C|1|0|Movim. Bloq.|Movimentação Bloqueada
TAF|30|TAF_EVENTO|C|250|0|Eventos PG|Eventos da Planta Grafica
TAF|31|TAF_EVEMDT|C|250|0|Eventos PG|Eventos da Planta Gráfica
TAF|32|TAF_ALERTX|N|4|0|Alerta em X|Alerta em X
TAF|33|TAF_ALERTY|N|4|0|Alerta em Y|Alerta em Y
TAF|34|TAF_SITNIV|C|1|0|Situação|Situação do Nível
TAF|35|TAF_CODFAM|C|6|0|Família|Família Local.
TAF|36|TAF_DESFAM|C|20|0|Descrição|Descrição Fam.
TAF|37|TAF_CODAMB|C|30|0|Cód. Amb.|Código do Ambiente Físico
TAF|38|TAF_NOMAMB|C|40|0|Nome Amb.|Nome do Ambiente Físico
TAF|39|TAF_EVESGA|C|250|0|Eventos PG|Eventos da Planta Gráfica
TAF|40|TAF_DEPTO|C|9|0|Departamento|Codigo Departamento
TAF|41|TAF_DESCDP|C|30|0|Descrição|Descrição Departamento
TAF|42|TAF_NOMSOC|C|70|0|Nome Social|Nome Social
--- ### TAG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAG|01|TAG_FILIAL|C|6|0|Filial|Filial do Sistema
TAG|02|TAG_CODASP|C|6|0|Aspecto|Código do Aspecto
TAG|03|TAG_CODEST|C|3|0|Estrutura|Código da Estrutura
TAG|04|TAG_CODNIV|C|6|0|Nível|Código do Nível
TAG|05|TAG_NIVSUP|C|6|0|Niv.Superior|Nivel Superior
TAG|06|TAG_SEQUEN|C|3|0|Sequencia|Sequencia
TAG|07|TAG_PLANTA|C|1|0|Planta Gráf.|Planta Gráfica
TAG|08|TAG_TIPIMG|C|1|0|Tipo Imagem|Tipo de Imagem
TAG|09|TAG_IMAGEM|C|30|0|Imagem|Imagem
TAG|10|TAG_POSX|N|4|0|Posicao em X|Posicao em X
TAG|11|TAG_POSY|N|4|0|Posicao em Y|Posicao em Y
TAG|12|TAG_MOVBLO|C|1|0|Movim. Bloq.|Movimentação Bloqueada
TAG|13|TAG_ALERTX|N|4|0|Alerta em X|Alerta em X
TAG|14|TAG_ALERTY|N|4|0|Alerta em Y|Alerta em Y
TAG|15|TAG_TAMX|N|7|2|Largura|Largura da Imagem
TAG|16|TAG_TAMY|N|7|2|Altura|Altura da Imagem
--- ### TAH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAH|01|TAH_FILIAL|C|6|0|Filial|Filial do Sistema
TAH|02|TAH_ORDEM|C|6|0|Ordem|N. Ordem
TAH|03|TAH_CODFOR|C|3|0|Fórmula|Código da Fórmula
TAH|04|TAH_RESULT|N|9|2|Resultado|Resultado da Formula
--- ### TAI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAI|01|TAI_FILIAL|C|6|0|Filial|Filial do Sistema
TAI|02|TAI_CODIMP|C|6|0|Impacto|Código do Impacto
TAI|03|TAI_CODLEG|C|12|0|Requisitos|Código do Requisito
TAI|04|TAI_EMENTA|C|80|0|Ementa|Ementa da Legislacao
--- ### TAJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAJ|01|TAJ_FILIAL|C|6|0|Filial|Filial do Sistema
TAJ|02|TAJ_CODASP|C|6|0|Aspecto|Código do Aspecto
TAJ|03|TAJ_CODLEG|C|12|0|Requisitos|Código da Legislação
TAJ|04|TAJ_EMENTA|C|80|0|Ementa|Ementa da Legislacao
--- ### TAK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAK|01|TAK_FILIAL|C|6|0|Filial|Filial do Sistema
TAK|02|TAK_CODEST|C|3|0|Estrutura|Código da Estrutura
TAK|03|TAK_CODNIV|C|6|0|Nível|Código do Nível
TAK|04|TAK_CODFUN|C|9|0|Função|Código da Função
TAK|05|TAK_MAT|C|16|0|Cod. Partici|Codigo do Participante
--- ### TAL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAL|01|TAL_FILIAL|C|6|0|Filial|Filial do Sistema
TAL|02|TAL_CODEST|C|3|0|Estrutura|Código da Estrutura
TAL|03|TAL_CODNIV|C|6|0|Nível|Cód. Nível da Estrutura
TAL|04|TAL_FILDOC|C|6|0|Filial Docum|Filial do Documento
TAL|05|TAL_DOCTO|C|16|0|Documento|Documento Relacionado
--- ### TAM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAM|01|TAM_FILIAL|C|6|0|Filial|Filial do Sistema
TAM|02|TAM_CODLEG|C|12|0|Demanda|Código da Demanda
TAM|03|TAM_EMENTA|C|80|0|Tema da Lei|Tema da Lei
TAM|04|TAM_TIPO|C|12|0|Tipo Demanda|Tipo de Demanda
TAM|05|TAM_DESCRI|M|10|0|Descricao|Descricao da Demanda
TAM|06|TAM_ORIGEM|C|1|0|Origem|Origem da Demanda
TAM|07|TAM_CODRES|C|12|0|Resolução|Código da Resolução
TAM|08|TAM_NUMRES|C|12|0|Num Resoluc|Numero da Resolucao
TAM|09|TAM_OREMIS|C|12|0|Orgao Emiss.|Orgao Emissor
TAM|10|TAM_DTEMIS|D|8|0|Data Emissao|Data de Emissao
TAM|11|TAM_DTPUBL|D|8|0|Data Public.|Data de Publicacao
TAM|12|TAM_SITE|C|40|0|Site|Site da Internet
TAM|13|TAM_DOCFIL|C|6|0|Filial Doc.|Filial do Documento
TAM|14|TAM_DOCTO|C|16|0|Documento|Documento da Demanda
TAM|15|TAM_DTVENC|D|8|0|Vencimento|Data Vencimento Licenca
TAM|16|TAM_DTVIGE|D|8|0|Vigencia|Data de Vigencia
TAM|17|TAM_RESPON|C|10|0|Responsavel|Codigo do Responsavel
TAM|18|TAM_NOMRES|C|40|0|Nome|Nome do Responsavel
TAM|19|TAM_OBRIGA|M|10|0|Obrigações|Obrigações da Empresa
TAM|20|TAM_ACOES|M|10|0|Ações|Ações de Controle Amb.
TAM|21|TAM_EST|C|2|0|Estado|Sigla da Federacao
TAM|22|TAM_DTALTE|D|8|0|Data Alterac|Data da Alteracao
TAM|23|TAM_HRALTE|C|5|0|Hora Alterac|Hora de Alteracao
--- ### TAN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAN|01|TAN_FILIAL|C|6|0|Filial|Filial do Sistema
TAN|02|TAN_ORDEM|C|6|0|Ordem|Ordem
TAN|03|TAN_CODFUN|C|5|0|Função|Código da Função
TAN|04|TAN_MAT|C|6|0|Mat. Funcion|Matricula do Funcionario
--- ### TAO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAO|01|TAO_FILIAL|C|6|0|Filial|Filial do Sistema
TAO|02|TAO_CODHIS|C|6|0|Histórico|Código do Histórico
TAO|03|TAO_CODASP|C|6|0|Aspecto|Código do Aspecto
TAO|04|TAO_CODIMP|C|6|0|Impacto|Código do Impacto
TAO|05|TAO_CODCLA|C|6|0|Classe|Código da Classe
TAO|06|TAO_CODPLA|C|6|0|Plano|Código do Plano
TAO|07|TAO_RESULT|N|9|2|Resultado|Resultado da Formula
TAO|08|TAO_CODEST|C|3|0|Estrutura|Código da Estrutura
TAO|09|TAO_CODNIV|C|6|0|Nível|Código do Nível
TAO|10|TAO_DTRESU|D|8|0|Dt. Result.|Data do Resultado
TAO|11|TAO_ORDEM|C|6|0|Ordem|Ordem da Avaliacao
TAO|12|TAO_DTHIST|D|8|0|Data Histor.|Data de Entrada Historico
TAO|13|TAO_CODFOR|C|3|0|Fórmula|Código da Fórmula
TAO|14|TAO_DESCRI|M|10|0|Descricao|Descricao
TAO|15|TAO_DTFINA|D|8|0|Data Final|Data de Finalizacao
TAO|16|TAO_RESUL2|N|9|0|Resultado 2|Resultado da fórmula 2
TAO|17|TAO_RESUL3|N|9|0|Resultado 3|Resultado da fórmula 3
TAO|18|TAO_RESUL4|N|9|0|Resultado 4|Resultado da fórmula 4
TAO|19|TAO_RESUL5|N|9|0|Resultado 5|Resultado da fórmula 5
TAO|20|TAO_CODEME|C|6|0|Plano Emerg.|Cod. do Plano Emergencial
TAO|21|TAO_SITUAC|C|1|0|Situacao|Situacao do Desempenho
TAO|22|TAO_CODOBJ|C|6|0|Objetivo|Código do Objetivo
TAO|23|TAO_NOMOBJ|C|40|0|Descrição|Descrição do Objetivo
--- ### TAP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAP|01|TAP_FILIAL|C|6|0|Filial|Filial do Sistema
TAP|02|TAP_CODHIS|C|6|0|Histórico|Código do Histórico
TAP|03|TAP_ORDEM|C|6|0|Ordem|Ordem da Avaliacäo
TAP|04|TAP_CODAVA|C|3|0|Avaliação|Código da Avaliação
TAP|05|TAP_CODOPC|C|3|0|Opção|Código da Opção
TAP|06|TAP_INDICA|C|1|0|Indicacao|Indicacao da Avaliacao
TAP|07|TAP_PESO|N|3|0|Peso %|Peso %
TAP|08|TAP_OK|C|1|0|Marcado?|Registro Marcado
--- ### TAQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAQ|01|TAQ_FILIAL|C|6|0|Filial|Filial do Sistema
TAQ|02|TAQ_USUARI|C|15|0|Usuario|Usuario do Sistema
TAQ|03|TAQ_PENDEN|C|6|0|Pendencia|Pendencia
TAQ|04|TAQ_ORDEM|C|40|0|Ordem|Ordem
TAQ|05|TAQ_MOSTRA|C|1|0|Mostrar|Mostrar
TAQ|06|TAQ_DATA|D|8|0|Data|Data
TAQ|07|TAQ_TIPO|C|1|0|Tipo|Tipo
TAQ|08|TAQ_DESC|C|100|0|Descricao|Descricao
TAQ|09|TAQ_SITUAC|C|1|0|Situacao|Situacao
TAQ|10|TAQ_USUFIM|C|15|0|Usuario Fina|Usuario que deu Baixa
--- ### TAR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAR|01|TAR_FILIAL|C|6|0|Filial|Filial do Sistema
TAR|02|TAR_CODATI|C|6|0|Atividade|Código da Atividade
TAR|03|TAR_DESATI|C|40|0|Desc. Ativ.|Descricäo da Atividade
TAR|04|TAR_CODCAL|C|3|0|Calendário|Código do Calendário
TAR|05|TAR_NUMPRO|N|9|0|Producao|Num. Func. Na Producao
TAR|06|TAR_NUMADM|N|9|0|Num. Admin.|Num. Func. na Admin.
TAR|07|TAR_NUMOUT|N|9|0|Num. Outros|Num. Func. de Outras Area
TAR|08|TAR_LAT|N|6|0|Lat. Graus|Latitude em Graus
TAR|09|TAR_LATMIN|N|6|0|Lat. Minutos|Latitude em Minutos
TAR|10|TAR_LONG|N|6|0|Long. Graus|Longitude em Graus
TAR|11|TAR_LONGMI|N|6|0|Long. Minut.|Longitude em Minutos
TAR|12|TAR_CODFUN|C|16|0|Funcionário|Código do Funcionário
TAR|13|TAR_AREA|N|9|2|Area Util|Area Util Total
TAR|14|TAR_DETAL|M|10|0|Detalhes|Detalhes
--- ### TAS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAS|01|TAS_FILIAL|C|6|0|Filial|Filial do Sistema
TAS|02|TAS_CODATI|C|6|0|Atividade|Código da Atividade
TAS|03|TAS_CODPRO|C|15|0|Produto|Código do Produto
TAS|04|TAS_DESPRO|C|40|0|Desc. Prod.|Descricäo do Produto
TAS|05|TAS_QTDATU|N|9|0|Qtde Atual|Quantidade Atual
TAS|06|TAS_CAPMAX|N|9|0|Qtde Maxima|Quantidade Maxima
TAS|07|TAS_UM|C|2|0|Unid. Medida|Unidade de Medida
--- ### TAU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAU|01|TAU_FILIAL|C|6|0|Filial|Filial do Sistema
TAU|02|TAU_CODPOL|C|6|0|Política|Cód. Política Ambiental
TAU|03|TAU_DTVIGE|D|8|0|Dt. Vigência|Data de Vigência
TAU|04|TAU_DESC|M|10|0|Descricäo|Desc. Politica Ambiental
TAU|05|TAU_MISSAO|M|10|0|Missao|Descricao da Missao
TAU|06|TAU_VISAO|M|10|0|Visao|Descricao da Visao
TAU|07|TAU_VALORE|M|10|0|Valores|Descricao dos Valores
TAU|08|TAU_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
TAU|09|TAU_MMMISS|C|6|0|ChaveMM SYP|ChaveMM SYP
TAU|10|TAU_MMVISA|C|6|0|ChaveMM SYP|Chave Memo SYP
TAU|11|TAU_MMVALO|C|6|0|ChaveMM SYP|Chave Memo SYP
TAU|12|TAU_FLAG|C|1|0|Módulo|Módulo de Criação
TAU|13|TAU_TIPO|C|1|0|Tipo|Tipo Política
--- ### TAV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAV|01|TAV_FILIAL|C|6|0|Filial|Filial do Sistema
TAV|02|TAV_CODRES|C|15|0|Resíduo|Código do Resíduo
TAV|03|TAV_CODEST|C|3|0|Estrutura|Código da Estrutura
TAV|04|TAV_CODNIV|C|6|0|Nível|Código do Nível
TAV|05|TAV_NIVSUP|C|6|0|Niv. Sup.|Nivel Superior
TAV|06|TAV_SEQUEN|C|3|0|Sequencia|Sequencia
TAV|07|TAV_PLANTA|C|1|0|Planta Gráf.|Planta Gráfica
TAV|08|TAV_TIPIMG|C|1|0|Tipo Imagem|Tipo de Imagem
TAV|09|TAV_IMAGEM|C|30|0|Imagem|Imagem
TAV|10|TAV_POSX|N|4|0|Posicao em X|Posicao em X
TAV|11|TAV_POSY|N|4|0|Posicao em Y|Posicao em Y
TAV|12|TAV_TAMX|N|7|2|Largura|Largura da Imagem
TAV|13|TAV_TAMY|N|7|2|Altura|Altura da Imagem
TAV|14|TAV_MOVBLO|C|1|0|Movim. Bloq.|Movimentação Bloqueada
TAV|15|TAV_ALERTX|N|4|0|Alerta em X|Alerta em X
TAV|16|TAV_ALERTY|N|4|0|Alerta em Y|Alerta em Y
--- ### TAW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAW|01|TAW_FILIAL|C|6|0|Filial|Filial do Sistema
TAW|02|TAW_CODCLA|C|6|0|Classificaçã|Código da Classificação
TAW|03|TAW_DESCLA|C|40|0|Desc. Class.|Desc. da Classificacäo
TAW|04|TAW_TIPCLA|C|1|0|Tipo Classe|Tipo de Classe
--- ### TAX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAX|01|TAX_FILIAL|C|6|0|Filial|Filial do Sistema
TAX|02|TAX_CODRES|C|15|0|Resíduo|Código do Resíduo
TAX|03|TAX_DESCRE|C|70|0|Desc. Resid.|Desc. de Residuos
TAX|04|TAX_CLASSE|C|6|0|Classe|Classificação de Resíduos
TAX|05|TAX_DESCLA|C|20|0|Desc. Classe|Descricao da Classe
TAX|06|TAX_ESTADO|C|1|0|Est. Fisico|Estado Fisico
TAX|07|TAX_CODFON|C|16|0|Fonte|Código da Fonte Geradora
TAX|08|TAX_DESFON|C|40|0|Desc. Fonte|Desc. da Fonte Geradora
TAX|09|TAX_TPGERA|C|1|0|Tp. Geracao|Tipo de Geracao
TAX|10|TAX_DENSID|N|8|3|Densidade|Densidade
TAX|11|TAX_IBAMA|C|10|0|Cod. Ibama|Cóigo do Ibama
TAX|12|TAX_RSS|C|1|0|RSS?|RSS?
TAX|13|TAX_IDENTI|C|1|0|Identific.|Identificação
TAX|14|TAX_DOCTO|C|16|0|Documento|Código do Documento
TAX|15|TAX_DOCFIL|C|6|0|Filial Doc.|Filial do Documento
--- ### TAZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TAZ|01|TAZ_FILIAL|C|6|0|Filial|Filial do Sistema
TAZ|02|TAZ_CODRES|C|15|0|Resíduo|Código do Resíduo
TAZ|03|TAZ_CODCRI|C|6|0|Critério|Cód. Critério de Controle
TAZ|04|TAZ_DESCRI|C|40|0|Desc. Crit.|Desc. Criterios de Cont.
TAZ|05|TAZ_LIMMIN|N|9|2|Lim. Minimo|Limite Minimo
TAZ|06|TAZ_LIMMAX|N|9|2|Lim. Maximo|Limite Maximo
TAZ|07|TAZ_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TAZ|08|TAZ_RESPON|C|16|0|Responsável|Código do Responsável
TAZ|09|TAZ_NOMRES|C|20|0|Nome Resp.|Nome do Responsavel
--- ### TB0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB0|01|TB0_FILIAL|C|6|0|Filial|Filial do Sistema
TB0|02|TB0_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TB0|03|TB0_DATA|D|8|0|Data Ocor.|Data da Ocorrrencia
TB0|04|TB0_HORA|C|5|0|Hora Ocor.|Hora da Ocorrencia
TB0|05|TB0_CODRES|C|15|0|Resíduo|Código do Resíduo
TB0|06|TB0_QTDE|N|9|2|Quant. Res.|Qtde. de Residuos Gerado
TB0|07|TB0_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TB0|08|TB0_RESPON|C|6|0|Responsável|Código do Responsável
TB0|09|TB0_ORIGEM|C|1|0|Origem|Origem do Resíduo
TB0|10|TB0_NUMCER|N|15|0|Certificado|Numero do Certificado
TB0|11|TB0_FATOR|N|10|3|Fator Conv.|Fator de Convercao
TB0|12|TB0_NUMSEQ|C|6|0|Sequencial|Numeracao Sequencial
TB0|13|TB0_FILORD|C|6|0|Filial Ordem|Filial da Ordem Servico
TB0|14|TB0_ORDEM|C|6|0|Ordem Serv.|Numero da Ordem Servico
TB0|15|TB0_QTDDES|N|9|2|Qtd. Destin.|Qtd. Destinada
TB0|16|TB0_QTDRED|N|9|2|Qtd. Real D.|Qtd. Real Destinada
TB0|17|TB0_ORIGE2|C|20|0|Orig. Regist|Origem Registro
--- ### TB1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB1|01|TB1_FILIAL|C|6|0|Filial|Filial do Sistema
TB1|02|TB1_OK|C|2|0|Ok|Ok
TB1|03|TB1_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TB1|04|TB1_CODCRI|C|6|0|Critério|Cód. do Critério de Aval.
TB1|05|TB1_DESCRI|C|40|0|Desc. Crit.|Descricäo do Criterio
TB1|06|TB1_QTDE|N|9|2|Quantidade|Quantidade
TB1|07|TB1_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TB1|08|TB1_CONFOR|C|1|0|Conformidade|Conformidade
TB1|09|TB1_CODPLA|C|6|0|Plano Ação|Código do Plano de Ação
TB1|10|TB1_COMPLE|M|10|0|Complemento|Complemento
--- ### TB2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB2|01|TB2_FILIAL|C|6|0|Filial|Filial do Sistema
TB2|02|TB2_CODDES|C|6|0|Destino|Código do Destino
TB2|03|TB2_TIPO|C|1|0|Tipo Destino|Tipo de Destino
TB2|04|TB2_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
TB2|05|TB2_DESFOR|C|80|0|Desc. Forn.|Descricäo do Fornecedor
TB2|06|TB2_CODTRA|C|6|0|Cod. Transp.|Codigo da Transportadora
TB2|07|TB2_DESTRA|C|40|0|Descricao|Descricao Transportadora
TB2|08|TB2_CODLOC|C|6|0|Local|Código do Local
TB2|09|TB2_DESLOC|C|40|0|Desc. Local|Descricäo do Local
TB2|10|TB2_CODALM|C|2|0|Almoxarifado|Código do Almoxarifado
TB2|11|TB2_GRAUS1|N|9|0|Lat. Graus|Latitude em Graus
TB2|12|TB2_MINUT1|N|9|0|Lat. Minutos|Latitude em Minutos
TB2|13|TB2_GRAUS2|N|9|0|Long. Graus|Longitude em Graus
TB2|14|TB2_MINUT2|N|9|0|Long. Minut.|Longitude em Minutos
TB2|15|TB2_QUANTI|N|9|0|Quant. Res.|Quantidade de Residuos
TB2|16|TB2_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TB2|17|TB2_TOLERA|N|3|0|Toleran. (%)|Tolerancia
TB2|18|TB2_TPRECE|C|1|0|Tp. Receptor|Tipo de Receptor
TB2|19|TB2_SEGUN1|N|6|2|Lat. Segs.|Latitude Segundos
TB2|20|TB2_SEGUN2|N|6|2|Long. Segs.|Longitude Segundos
TB2|21|TB2_TPLATI|C|1|0|Tipo Lat.|Tipo Latitude
TB2|22|TB2_TPLONG|C|1|0|Tipo Long.|Tipo Longitude
TB2|23|TB2_LOJA|C|2|0|Loja|Loja do fornecedor
--- ### TB3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB3|01|TB3_FILIAL|C|6|0|Filial|Filial do Sistema
TB3|02|TB3_CODCLA|C|6|0|Classific.|Código da Classificação
TB3|03|TB3_TIPO|C|1|0|Tipo Clas.|Tipo clas. do Destino
TB3|04|TB3_DESCLA|C|40|0|Desc. Cals.|Descricäo da Classific.
--- ### TB4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB4|01|TB4_FILIAL|C|6|0|Filial|Filial do Sistema
TB4|02|TB4_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TB4|03|TB4_CODRES|C|15|0|Resíduo|Código do Resíduo
TB4|04|TB4_CODDES|C|6|0|Destino|Código do Destino
TB4|05|TB4_DESCDE|C|20|0|Desc. Dest.|Descricäo do Destino
TB4|06|TB4_CODCLA|C|6|0|Classe|Código da Classificação
TB4|07|TB4_DESCLA|C|40|0|Desc. Clas.|Desc. da Classificacäo
TB4|08|TB4_QUANTI|N|9|2|Quantidade|Quantidade
TB4|09|TB4_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TB4|10|TB4_LOTECT|C|10|0|Lote|Numero do Lote
TB4|11|TB4_NUMLOT|C|6|0|Sub-Lote|Numero do Sub-Lote
TB4|12|TB4_DTVALI|D|8|0|Dt. Validade|Data de Validade do Lote
--- ### TB5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB5|01|TB5_FILIAL|C|6|0|Filial|Filial do Sistema
TB5|02|TB5_CODIGO|C|6|0|Código|Código Receptor
TB5|03|TB5_TPRECE|C|1|0|Tp. Receptor|Tipo de Receptor
TB5|04|TB5_FORNEC|C|6|0|Receptor|Receptor
TB5|05|TB5_LOJA|C|2|0|Loja|Loja do Fornecedor
TB5|06|TB5_DESC|C|40|0|Desc. Forn.|Descricäo do Fornecedor
TB5|07|TB5_END|C|40|0|Endereco|Endereco do Funcionario
TB5|08|TB5_TEL|C|20|0|Telefone|Numero do Telefone
TB5|09|TB5_CODLAM|C|12|0|Licença|Código Licença Ambiental
TB5|10|TB5_DESLAM|C|80|0|Descrição|Desc. Licença Ambiental
TB5|11|TB5_DATAVA|D|8|0|Dt. Validade|Data da Validade
TB5|12|TB5_STATUS|C|1|0|Status|Status do Receptor
TB5|13|TB5_MOTIVO|M|10|0|Motivo Inat.|Motivo da Inatividade
TB5|14|TB5_DOCFIL|C|6|0|Filial Docum|Filial do Documento
TB5|15|TB5_DOCTO|C|16|0|Documento|Documento Relacionado
--- ### TB6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB6|01|TB6_FILIAL|C|6|0|Filial|Filial do Sistema
TB6|02|TB6_CODTIP|C|6|0|Cód. Tipo|Cód. Tipo Destinação
TB6|03|TB6_DESCRI|C|60|0|Descricao|Descricao do Tipo Destin.
TB6|04|TB6_TIPO|C|1|0|Tipo|Tipo de Destinacäo
TB6|05|TB6_PROD|C|15|0|Produto|Codigo do Produto
TB6|06|TB6_NOMPRO|C|70|0|Nome Produto|Nome do Produto
TB6|07|TB6_SIGLA|C|10|0|Sigla|Sigla do Acondicionamento
TB6|08|TB6_UM|C|2|0|Unidade|Unidade de Medida
TB6|09|TB6_STATUS|C|1|0|Status|Status do Tipo de Dest.
TB6|10|TB6_ORIGEM|C|1|0|Origem|Procedencia do Coletor
TB6|11|TB6_DOCFIL|C|6|0|Filial Docum|Filial do Documento
TB6|12|TB6_DOCTO|C|16|0|Documento|Documento Relacionado
--- ### TB7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB7|01|TB7_FILIAL|C|6|0|Filial|Filial do Sistema
TB7|02|TB7_CODRES|C|15|0|Resíduo|Código do Resíduo
TB7|03|TB7_METODO|C|1|0|Metodo|Metodo de Coleta
TB7|04|TB7_TIPO|C|1|0|Tipo|Tipo de Destinacao
TB7|05|TB7_CODTIP|C|6|0|Cód. Tipo|Cód do Tipo de Destinação
TB7|06|TB7_DESC|C|20|0|Descricao|Descricao do Tipo de Dest
TB7|07|TB7_ONDEMA|C|1|0|Lote Econom.|Lote Econômico?
TB7|08|TB7_FREQUE|N|5|0|Frequencia|Frequencia da Destinacao
TB7|09|TB7_UM|C|1|0|Unidade|Unidade da Frequencia
TB7|10|TB7_COLETA|C|1|0|Coleta|Tipo de Coleta
--- ### TB8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB8|01|TB8_FILIAL|C|6|0|Filial|Filial do Sistema
TB8|02|TB8_CODTRA|C|6|0|Transporte|Código do Transporte
TB8|03|TB8_DESCRI|C|40|0|Descricao|Descricao do Transporte
--- ### TB9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TB9|01|TB9_FILIAL|C|6|0|Filial|Filial do Sistema
TB9|02|TB9_CODRES|C|15|0|Resíduo|Código do Resíduo
TB9|03|TB9_TIPTRA|C|6|0|Transporte|Tipo do Transporte
TB9|04|TB9_DESCRI|C|20|0|Descricao|Descricao do Transporte
TB9|05|TB9_ONDEMA|C|1|0|Sob Demanda|Sob Demanda
TB9|06|TB9_FREQUE|N|5|0|Frequencia|Frequencia do Transporte
TB9|07|TB9_UM|C|1|0|Unidade|Unidade de Medida
--- ### TBA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBA|01|TBA_FILIAL|C|6|0|Filial|Filial do Sistema
TBA|02|TBA_CODRES|C|15|0|Resíduo|Código do Resíduo
TBA|03|TBA_DESRES|C|70|0|Descrição|Descrição do Resíduo
TBA|04|TBA_DTTRAN|D|8|0|Data Transf.|Data da Transferencia
TBA|05|TBA_HRTRAN|C|5|0|Hora Transf.|Hora da Transferencia
TBA|06|TBA_CODDES|C|6|0|Dest. Origem|Destino de Origem
TBA|07|TBA_DESCDE|C|20|0|Descrição|Descricao do Destino
TBA|08|TBA_QTDSAI|N|9|2|Qtd. Transf.|Qtd. Transf.
TBA|09|TBA_UM|C|2|0|Un. Medida|Unidade de Medida
TBA|10|TBA_CODPRO|C|15|0|Produto|Código do Produto
TBA|11|TBA_DESPRO|C|70|0|Descrição|Descricao do Produto
TBA|12|TBA_CODREC|C|6|0|Receptor|Código Receptor
TBA|13|TBA_DESFOR|C|40|0|Descrição|Descrição do Fornecedor
TBA|14|TBA_TRANSP|C|6|0|Transport.|Código da Transportadora
TBA|15|TBA_DESTRA|C|40|0|Descrição|Descrição Transportadora
TBA|16|TBA_DOCTO|C|15|0|Docto Fiscal|Documento Fiscal
TBA|17|TBA_NUMMTR|C|15|0|Número MTR|Número MTR
TBA|18|TBA_FATOR|N|10|2|Fator Conv.|Fator de Conversão
TBA|19|TBA_NUMSEQ|C|6|0|Sequencial|Numeracao Sequencial
TBA|20|TBA_LOTECT|C|10|0|Lote|Numero do Lote
TBA|21|TBA_NUMLOT|C|6|0|Sub-Lote|Numero do Sub-Lote
TBA|22|TBA_DTVALI|D|8|0|Dt. Validade|Data de Validade do Lote
TBA|23|TBA_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TBA|24|TBA_TIPDES|C|1|0|Tipo|Tipo de Destinacao
TBA|25|TBA_CODTIP|C|6|0|Cod. Tipo|Cod. Tipo de Destinação
--- ### TBB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBB|01|TBB_FILIAL|C|6|0|Filial|Filial do Sistema
TBB|02|TBB_CODPLA|C|6|0|Plano|Código do Plano Emerg.
TBB|03|TBB_DESPLA|C|80|0|Descrição|Descrição
TBB|04|TBB_TIPELA|C|1|0|Tipo Elab.|Tipo de Elaborado
TBB|05|TBB_ELABOR|C|16|0|Elaborador|Codigo do Elaborador
TBB|06|TBB_NOMELA|C|30|0|Nome|Nome do Elaborador
TBB|07|TBB_TIPRES|C|1|0|Tipo Resp.|Tipo de Responsável
TBB|08|TBB_RESPON|C|16|0|Responsavel|Codigo do Responsavel
TBB|09|TBB_NOMRES|C|30|0|Nome|Nome do Responsavel
TBB|10|TBB_OBSPLA|M|10|0|Observacäo|Obs. do Plano Emergencial
TBB|11|TBB_MODULO|C|1|0|Módulo|Módulo
TBB|12|TBB_INDAVA|C|1|0|Avaliação|Indica Avaliação
--- ### TBC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBC|01|TBC_FILIAL|C|6|0|Filial|Filial do Sistema
TBC|02|TBC_CODPLA|C|6|0|Plano|Codigo do Plano Emerg.
TBC|03|TBC_CODEST|C|3|0|Estrutura|Codigo da Estrutura
TBC|04|TBC_CODNIV|C|3|0|Nivel|Codigo do Nivel
--- ### TBD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBD|01|TBD_FILIAL|C|6|0|Filial|Filial do Sistema
TBD|02|TBD_CODCHK|C|6|0|CheckList|Codigo do CheckList
TBD|03|TBD_DESCHK|C|80|0|Descricao|Descricao do CheckList
TBD|04|TBD_TIPOPC|C|1|0|Tipo Opcao|Tipo de Opcao
TBD|05|TBD_OBSERV|M|10|0|Observacao|Observacao do CheckList
--- ### TBE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBE|01|TBE_FILIAL|C|6|0|Filial|Filial do Sistema
TBE|02|TBE_CODCHK|C|6|0|CheckList|Codigo do CheckList
TBE|03|TBE_CODOPC|C|6|0|Opcao|Cod. da Opcao do ChkList
TBE|04|TBE_DESOPC|C|80|0|Descricao|Desc. da Opcao do ChkList
TBE|05|TBE_TIPRES|C|1|0|Tipo|Tipo de Resposta
TBE|06|TBE_CONDOP|C|1|0|Operador|Operador da Condicao.
TBE|07|TBE_CONDIN|C|10|0|Informacao|Valor de Comparacao
TBE|08|TBE_TIPACA|C|1|0|Tipo Acao|Tipo de Acao
--- ### TBF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBF|01|TBF_FILIAL|C|6|0|Filial|Filial do Sistema
TBF|02|TBF_CODPLA|C|6|0|Plano|Codigo do Plano de Simul.
TBF|03|TBF_DESPLA|C|80|0|Descricao|Descricao do Plano.
TBF|04|TBF_SEQUEN|C|3|0|Sequencia|Sequencia da Simulacao
TBF|05|TBF_FREQUE|C|1|0|Frequencia|Frequencia da Simulacao
TBF|06|TBF_QUANTI|N|9|0|Período|Período de Frequencia
TBF|07|TBF_DATPLA|D|8|0|Ultimo Plano|Data do Ultimo Plano
TBF|08|TBF_CODCAL|C|3|0|Calendario|Calendario da Simulacao
TBF|09|TBF_DESCAL|C|80|0|Descricao|Descricao do Calendario
--- ### TBG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBG|01|TBG_FILIAL|C|6|0|Filial|Filial do Sistema
TBG|02|TBG_CODPLA|C|6|0|Plano|Codigo do Plano de Simul.
TBG|03|TBG_SEQUEN|C|3|0|Sequencia|Sequencia da Simulacao
TBG|04|TBG_TIPQUE|C|1|0|Tip. Chk.|Tipo CheckList
TBG|05|TBG_CODCHK|C|6|0|CheckList|Codigo do CheckList
TBG|06|TBG_DESCHK|C|80|0|Descrição|Descricao do CheckList
--- ### TBH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBH|01|TBH_FILIAL|C|6|0|Filial|Filial do Sistema
TBH|02|TBH_CODOBJ|C|6|0|Objetivo|Código do Objetivo
TBH|03|TBH_DESCRI|C|40|0|Descr. Obj.|Descrição do Objetivo
TBH|04|TBH_SITUAC|C|1|0|Situação|Situação do Objetivo
TBH|05|TBH_PRAZO|D|8|0|Prazo|Prazo do Objetivo
TBH|06|TBH_ABERTU|D|8|0|Abertura|Data da Abertura
TBH|07|TBH_FECHAM|D|8|0|Fechamento|Data de Fechamento
TBH|08|TBH_RESPON|C|16|0|Responsavel|Codigo do Responsavel
TBH|09|TBH_NOME|C|30|0|Nome|Nome do Responsavel
TBH|10|TBH_PRIORI|C|1|0|Prioridade|Prioridade do objetivo
TBH|11|TBH_FLAG|C|1|0|Módulo|Módulo de Criação
TBH|12|TBH_TIPO|C|1|0|Tipo|Tipo Objetivo
--- ### TBI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBI|01|TBI_FILIAL|C|6|0|Filial|Filial do Sistema
TBI|02|TBI_OBJETI|C|6|0|Objetivo|Objetivo ambiental
TBI|03|TBI_META|C|6|0|Meta|Meta Ambiental
TBI|04|TBI_DTFIPR|D|8|0|Dt Term Prev|Data Termino Previsto
TBI|05|TBI_NOME|C|40|0|Nome Meta|Nome da Meta
--- ### TBJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBJ|01|TBJ_FILIAL|C|6|0|Filial|Filial do Sistema
TBJ|02|TBJ_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TBJ|03|TBJ_CODEST|C|3|0|Estrutura|Código da Estrutura
TBJ|04|TBJ_CODNIV|C|6|0|Nível|Código do Nível
TBJ|05|TBJ_NIVSUP|C|6|0|Nível Sup.|Nível Superior
--- ### TBK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBK|01|TBK_FILIAL|C|6|0|Filial|Filial do Sistema
TBK|02|TBK_CODOBJ|C|6|0|Objetivo|Codigo do Objetivo
TBK|03|TBK_META|C|6|0|Meta|Codigo da Meta
TBK|04|TBK_DTRESU|D|8|0|Data Result.|Data do Resultado
TBK|05|TBK_VALOR|N|9|2|Valor|Valor do Resultado
TBK|06|TBK_RESPON|C|10|0|Responsavel|Codigo Responsavel
TBK|07|TBK_NOME|C|30|0|Nome|Nome do Responsavel
TBK|08|TBK_CODFOR|C|3|0|Fórmula|Código da Fórmula
--- ### TBM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBM|01|TBM_FILIAL|C|6|0|Filial|Filial do Sistema
TBM|02|TBM_CODPLA|C|6|0|Plano|Codigo do Plano de Simul.
TBM|03|TBM_DATPLA|D|8|0|Data Plano|Data do Plano de Simul.
TBM|04|TBM_DESPLA|C|80|0|Descricao|Desc. do Plano de Simul.
TBM|05|TBM_DATINI|D|8|0|Data Inicial|Data de Inicio do Plano
TBM|06|TBM_DATFIM|D|8|0|Data Final|Data de Finalizacao
TBM|07|TBM_PLAINI|C|6|0|Plano Inic.|Codigo Inicial do Plano
TBM|08|TBM_DESPIN|C|80|0|Descricao|Descricao do Plano Inic.
TBM|09|TBM_PLAFIM|C|6|0|Plano Final|Codigo do Plano Final
TBM|10|TBM_DESPFI|C|80|0|Descricao|Descricao do Plano Final
TBM|11|TBM_SITUAC|C|1|0|Situacao|Situacao do Plano
TBM|12|TBM_TERMIN|C|1|0|Terminado|Plano de Simul. Terminado
--- ### TBN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBN|01|TBN_FILIAL|C|6|0|Filial|Filial do Sistema
TBN|02|TBN_CODORD|C|6|0|Ordem|Codigo da Ordem do Plano
TBN|03|TBN_CODPLA|C|6|0|Plano|Codigo do Plano
TBN|04|TBN_DATPLA|D|8|0|Data Plano|Data de Geracao da Ordem
TBN|05|TBN_DATINP|D|8|0|Data Prev.|Data de Inicio Prevista
TBN|06|TBN_DATINR|D|8|0|Data Real.|Data de Inicio Realizada
TBN|07|TBN_DATFIN|D|8|0|Data Canc.|Data de Cancelamento
TBN|08|TBN_PLAEME|C|6|0|Plano Emerg.|Cod. do Plano Emergencial
TBN|09|TBN_DESPLA|C|80|0|Descricao|Descricao do Plano Emerg.
TBN|10|TBN_SEQUEN|C|3|0|Sequencia|Sequencia da Simulacao
TBN|11|TBN_DATSIM|D|8|0|Data Simul.|Data da Ultima Simulacao
TBN|12|TBN_TERMIN|C|1|0|Terminada|Indica Termino da O.S.
TBN|13|TBN_SITUAC|C|1|0|Situacao|Indica a Situacao da O.S.
TBN|14|TBN_USUARI|C|15|0|Usuario|Usuario que Finalizou
TBN|15|TBN_OBSERV|M|10|0|Observacao|Observacao da Ordem
--- ### TBO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBO|01|TBO_FILIAL|C|6|0|Filial|Filial do Sistema
TBO|02|TBO_CODPLA|C|6|0|Plano|Codigo do Plano Emerg.
TBO|03|TBO_CODACA|C|6|0|Ação|Código da Ação
TBO|04|TBO_DESACA|C|80|0|Descrição|Descrição
--- ### TBP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBP|01|TBP_FILIAL|C|6|0|Filial|Filial do Sistema
TBP|02|TBP_CODPLA|C|6|0|Plano|Codigo do Plano
TBP|03|TBP_DESPLA|C|80|0|Descricao|Descricao do Plano Emerg.
TBP|04|TBP_TIPPAR|C|1|0|Tp. Partici.|Tipo de Participante
TBP|05|TBP_CODPAR|C|16|0|Participante|Codigo do Participante
TBP|06|TBP_NOMPAR|C|50|0|Nome|Nome do Participante
TBP|07|TBP_CODFUN|C|9|0|Função|Função
TBP|08|TBP_DESFUN|C|80|0|Descrição|Descrição
--- ### TBQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBQ|01|TBQ_FILIAL|C|6|0|Filial|Filial do Sistema
TBQ|02|TBQ_ORDEM|C|6|0|Ordem|Ordem do Plano de Simul.
TBQ|03|TBQ_PLANO|C|6|0|Plano|Plano de Simulacao
TBQ|04|TBQ_CHKLIS|C|6|0|CheckList|Codigo do CheckList
TBQ|05|TBQ_DESCHK|C|60|0|Descricao|Descricao do CheckList
TBQ|06|TBQ_OK|C|2|0|Situacao|Situacao do CheckList
TBQ|07|TBQ_TIPUSU|C|1|0|Tp. Usuário|Tipo de Usuário
TBQ|08|TBQ_USUARI|C|16|0|Usuario|Codigo do Usuario
TBQ|09|TBQ_SEQCHK|C|3|0|Seq. ChkList|Sequencia do CheckList
TBQ|10|TBQ_OPCOES|C|1|0|Tipo Opcao|Tipo de Opcao de Resposta
TBQ|11|TBQ_TIPQUE|C|1|0|Tip. Chk.|Tipo CheckList
--- ### TBR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBR|01|TBR_FILIAL|C|6|0|Filial|Filial do Sistema
TBR|02|TBR_ORDEM|C|6|0|Ordem|Ordem do Plano de Simul.
TBR|03|TBR_PLANO|C|6|0|Plano|Plano de Simulacao
TBR|04|TBR_CHKLIS|C|6|0|CheckList|Codigo do CheckList
TBR|05|TBR_OPCAO|C|15|0|Opcao|Opcao do CheckList
TBR|06|TBR_RESPOS|C|10|0|Resposta|Resposta da Opcao do Chk.
TBR|07|TBR_TIPUSU|C|1|0|Tp. Usuário|Tipo de Usuário
TBR|08|TBR_USUARI|C|16|0|Usuario|Codigo do Usuario
TBR|09|TBR_NOMUSU|C|80|0|Nome|Nome do Usuario
TBR|10|TBR_TIPRES|C|1|0|Tipo|Tipo de Resposta
TBR|11|TBR_OPERAD|C|2|0|Operador|Operador da Condicao
TBR|12|TBR_CONDIN|C|10|0|Informacao|Valor de Comparacao
TBR|13|TBR_OK|C|2|0|Situacao|Situacao da Opcao
TBR|14|TBR_OBSERV|C|40|0|Msg. Alerta|Mensagem de Alerta
--- ### TBS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBS|01|TBS_FILIAL|C|6|0|Filial|Filial do Sistema
TBS|02|TBS_ORDEM|C|6|0|Ordem|Ordem de Servico
TBS|03|TBS_PLANO|C|6|0|Plano|Plano de Simulacao
TBS|04|TBS_CODCHK|C|6|0|CheckList|Codigo do CheckList
TBS|05|TBS_DESCHK|C|80|0|Descricao|Descricao do CheckList
TBS|06|TBS_OK|C|2|0|Situacao|Situacao do CheckList
TBS|07|TBS_TIPRES|C|1|0|Tp. Respon.|Tipo de Responsável
TBS|08|TBS_CODRES|C|16|0|Usuario|Codigo do Usuario
TBS|09|TBS_OPCOES|C|1|0|Tipo Opcao|Tipo de Opcoes da Resp.
TBS|10|TBS_SEQCHK|C|3|0|Sequencia|Sequencia do CheckList
--- ### TBT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBT|01|TBT_FILIAL|C|6|0|Filial|Filial do Sistema
TBT|02|TBT_SEQUEN|C|3|0|Sequencia|Sequencia da Simulacao
TBT|03|TBT_CODCHK|C|6|0|CheckList|Codigo CheckList da Sim.
TBT|04|TBT_OPCAO|C|15|0|Opcao|Opcao do CheckList
TBT|05|TBT_TIPRES|C|1|0|Tp. Resposta|Tipo de Resposta
TBT|06|TBT_CONDOP|C|2|0|Operador|Operador da Condicao
TBT|07|TBT_CONDIN|C|10|0|Informacao|Informacao da Condicao
TBT|08|TBT_TIPCAM|C|1|0|Tp.Campo Res|Tipo do campo de Resposta
--- ### TBU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBU|01|TBU_FILIAL|C|6|0|Filial|Filial do Sistema
TBU|02|TBU_CODPLA|C|6|0|Plano Emerg.|Codigo do Plano Emerg.
TBU|03|TBU_CODCON|C|6|0|Contato|Codigo do Contato Ext.
TBU|04|TBU_DESCON|C|40|0|Descrição|Descrição
TBU|05|TBU_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TBU|06|TBU_DESFOR|C|80|0|Desc. Forn.|Desc. Forn.
TBU|07|TBU_FONE|C|15|0|Fone|Numero do Telefone
TBU|08|TBU_FAX|C|15|0|Fax|Numero do Fax
TBU|09|TBU_EMAIL|C|50|0|End. E-mail|Endereco de E-mail
TBU|10|TBU_ENDERE|C|40|0|Endereço|Endereço
--- ### TBV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBV|01|TBV_FILIAL|C|6|0|Filial|Filial do Sistema
TBV|02|TBV_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TBV|03|TBV_HORA|C|5|0|Hora|Hora da Ocorrencia
TBV|04|TBV_DATA|D|8|0|Data|Data da Ocorrencia
TBV|05|TBV_CODPLA|C|6|0|Plano Emerg.|Plano Emergencial
TBV|06|TBV_DESPLA|C|80|0|Descricao|Descricao do Plano Emerg.
TBV|07|TBV_TIPRES|C|1|0|Tp. Respon.|Tipo de Responsável
TBV|08|TBV_RESPON|C|16|0|Responsavel|Usuario Responsavel
TBV|09|TBV_NOME|C|80|0|Nome|Nome do Usuario Resp.
TBV|10|TBV_PERIME|C|1|0|Perimetro|Perimetro da Ocorrencia.
TBV|11|TBV_PROXIM|C|1|0|Proximo|Prox. a recursos Hidricos
TBV|12|TBV_AMBIEN|C|1|0|Area Amb.?|Area Ambiental
TBV|13|TBV_TIPACI|C|1|0|Acidente|Tipo de Acidente Ocorrido
TBV|14|TBV_OBSERV|M|10|0|Observacao|Observacao da Ocorrencia
TBV|15|TBV_DESOCO|C|40|0|Descricao|Descricao da Ocorrencia
TBV|16|TBV_ACIDEN|C|6|0|Acidente|Acidente de Trabalho
TBV|17|TBV_DESACI|C|80|0|Descricao|Descricao do Acidente
--- ### TBW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBW|01|TBW_FILIAL|C|6|0|Filial|Filial do Sistema
TBW|02|TBW_CODTIP|C|6|0|Cod. Tipo|Cod. Tipo Destinação
TBW|03|TBW_TIPO|C|1|0|Tipo|Tipo Destinação
TBW|04|TBW_CODPRO|C|15|0|Coletor|Código Coletor
TBW|05|TBW_NOMPRO|C|70|0|Desc. Colet.|Descrição Coletor
--- ### TBX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBX|01|TBX_FILIAL|C|6|0|Filial|Filial do Sistema
TBX|02|TBX_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TBX|03|TBX_MAT|C|16|0|Usuario|Codigo do Usuario
TBX|04|TBX_AVISAD|C|1|0|Avisado?|Usuario Avisado?
TBX|05|TBX_OBSERV|M|10|0|Observacao|Observacao sobre o Aviso
TBX|06|TBX_DATA|D|8|0|Data Aviso|Data de Aviso?
TBX|07|TBX_HORA|C|5|0|Hora Aviso|Hora de Aviso?
TBX|08|TBX_LOGIN|C|15|0|Login|Login do Informante
TBX|09|TBX_TIPRES|C|1|0|Tp. Respon.|Tipo de Responsável
--- ### TBY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBY|01|TBY_FILIAL|C|6|0|Filial|Filial do Sistema
TBY|02|TBY_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TBY|03|TBY_CODPLA|C|6|0|Plano Emerg.|Codigo do Plano Emerg.
TBY|04|TBY_CODCON|C|6|0|Contato|Codigo do Contato Externo
--- ### TBZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TBZ|01|TBZ_FILIAL|C|6|0|Filial|Filial do Sistema
TBZ|02|TBZ_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TBZ|03|TBZ_CODPLA|C|6|0|Plano Emerg.|Codigo do Plano Emerg.
TBZ|04|TBZ_CODMED|C|6|0|Medida|Codigo da Acao/Medida
TBZ|05|TBZ_CODACA|C|6|0|Plano Acao|Codigo do Plano de Acao
--- ### TC0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC0|01|TC0_FILIAL|C|6|0|Filial|Filial do Sistema
TC0|02|TC0_CODPRO|C|15|0|Produto|Codigo do Produto
TC0|03|TC0_NOMPRO|C|70|0|Nome Produto|Nome do Produto
--- ### TC1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC1|01|TC1_FILIAL|C|6|0|Filial|Filial do Sistema
TC1|02|TC1_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC1|03|TC1_CODPLA|C|6|0|Plano Emerg.|Codigo do Plano Emerg.
TC1|04|TC1_CODEST|C|3|0|Estrutura|Codigo da Estrutura
TC1|05|TC1_CODNIV|C|3|0|Nivel|Codigo do Nivel
TC1|06|TC1_NIVSUP|C|3|0|Niv.Superior|Nivel Superior
--- ### TC2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC2|01|TC2_FILIAL|C|6|0|Filial|Filial do Sistema
TC2|02|TC2_CODPLA|C|6|0|Plano Emerg.|Plano Emergencial
TC2|03|TC2_DESPLA|C|80|0|Descricao|Descricao do Plano Emerg.
TC2|04|TC2_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC2|05|TC2_DATA|D|8|0|Data|Data da Ocorrencia
TC2|06|TC2_HORA|C|5|0|Hora|Hora da Ocorrencia
--- ### TC3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC3|01|TC3_FILIAL|C|6|0|Filial|Filial do Sistema
TC3|02|TC3_CODPLA|C|6|0|Plano Emerg.|Plano Emergencial
TC3|03|TC3_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC3|04|TC3_DTOCO|D|8|0|Data|Data da Ocorrencia
TC3|05|TC3_HROCO|C|5|0|Hora|Hora da Ocorrencia
TC3|06|TC3_CODACA|C|6|0|Acao|Codigo da Acao do P.E.
TC3|07|TC3_DESACA|C|80|0|Descricao|Descricao da Acao do P.E.
TC3|08|TC3_CODPAC|C|6|0|Plano Acao|Codigo do Plano de Acao.
TC3|09|TC3_OK|C|1|0|Respondido|Identifica Medidas Resp.
TC3|10|TC3_DTINIC|D|8|0|Data Inicial|Data de Inicio da Acao
TC3|11|TC3_DTFIM|D|8|0|Data Termino|Data de Termino da Acao
--- ### TC4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC4|01|TC4_FILIAL|C|6|0|Filial|Filial do Sistema
TC4|02|TC4_CODIGO|C|6|0|Código|Código Receptor
TC4|03|TC4_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TC4|04|TC4_LOJA|C|2|0|Loja|Loja do Fornecedor
TC4|05|TC4_CODPRO|C|15|0|Resíduo|Código do Resíduo
TC4|06|TC4_DESPRO|C|70|0|Desc. Prod.|Descricäo do Produto
TC4|07|TC4_NUMLIC|C|20|0|Licenc.|Numero do Licenciamento
TC4|08|TC4_CODLEG|C|12|0|Requisito|Requisito Legal
TC4|09|TC4_EMENTA|C|80|0|Descrição|Desc. Licença Ambiental
--- ### TC5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC5|01|TC5_FILIAL|C|6|0|Filial|Filial do Sistema
TC5|02|TC5_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC5|03|TC5_TIPENV|C|1|0|Tipo|Tipo de Envolvido
TC5|04|TC5_CODMAT|C|16|0|Matricula|Codigo de Mat. do Usuario
TC5|05|TC5_NOME|C|80|0|Nome|Nome do Envolvido
--- ### TC6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC6|01|TC6_FILIAL|C|6|0|Filial|Filial do Sistema
TC6|02|TC6_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC6|03|TC6_CODIMP|C|6|0|Impacto|Codigo do Impacto
TC6|04|TC6_DESIMP|C|40|0|Descricao|Descricao do Impacto
--- ### TC7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC7|01|TC7_FILIAL|C|6|0|Filial|Filial do Sistema
TC7|02|TC7_CODOCO|C|6|0|Ocorrencia|Codigo da Ocorrencia
TC7|03|TC7_CODCON|C|6|0|Contato|Codigo do Contato Externo
TC7|04|TC7_AVISAD|C|1|0|Contatado?|Foi Contatado?
TC7|05|TC7_DTCONT|D|8|0|Data Contato|Data em que foi contatado
TC7|06|TC7_HRCONT|C|5|0|Hora Contato|Hora em que foi contatado
TC7|07|TC7_DTCHEG|D|8|0|Data Chegada|Data de Chegada
TC7|08|TC7_HRCHEG|C|5|0|Hora Chegada|Hora de Chegada
--- ### TC8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC8|01|TC8_FILIAL|C|6|0|Filial|Filial do Sistema
TC8|02|TC8_CODPRO|C|15|0|Produto|Codigo do Produto
TC8|03|TC8_CODRES|C|15|0|Residuo|Codigo do Residuo
TC8|04|TC8_NOMRES|C|70|0|Nome Residuo|Nome do Residuo
TC8|05|TC8_TIPO|C|1|0|Controle|Tipo de Controle
TC8|06|TC8_QUANT|N|9|2|Quantidade|Quantidade Gerada
TC8|07|TC8_UM|C|2|0|Unidade|Unidade de Medida
--- ### TC9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TC9|01|TC9_FILIAL|C|6|0|Filial|Filial do Sistema
TC9|02|TC9_CODPLA|C|6|0|Plano Acao|Codigo do Plano de Acao
TC9|03|TC9_TIPRES|C|1|0|Tipo Resp.|Tipo de Responsavel
TC9|04|TC9_CODRES|C|16|0|Responsavel|Codigo do Responsavel
TC9|05|TC9_NOMRES|C|40|0|Nome|Nome do Responsavel
--- ### TCA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCA|01|TCA_FILIAL|C|6|0|Filial|Filial do Sistema
TCA|02|TCA_CODIGO|C|6|0|Codigo|Codigo do Grupo Gerador
TCA|03|TCA_DESCRI|C|40|0|Descricao|Descricao do Grupo
TCA|04|TCA_OBSERV|M|10|0|Observacao|Observacao do Grupo
--- ### TCB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCB|01|TCB_FILIAL|C|6|0|Filial|Filial do Sistema
TCB|02|TCB_CODIGO|C|6|0|Codigo|Cod. da Fonte de Medicao
TCB|03|TCB_DESCRI|C|40|0|Descricao|Descricao da Fonte
--- ### TCC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCC|01|TCC_FILIAL|C|6|0|Filial|Filial do Sistema
TCC|02|TCC_CODIGO|C|6|0|Codigo|Codigo do Criterio
TCC|03|TCC_DESCRI|C|40|0|Descricao|Descricao do Criterio
TCC|04|TCC_UNIMED|C|2|0|Unid. Medida|Codigo da Unid. de Medida
TCC|05|TCC_DESUNI|C|40|0|Descricao|Desc. da Unid. de Medida
--- ### TCD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCD|01|TCD_FILIAL|C|6|0|Filial|Filial do Sistema
TCD|02|TCD_CODIGO|C|6|0|Codigo|Codigo do Monitoramento
TCD|03|TCD_DTCAD|D|8|0|Dt. Cadastro|Data do Cadastro
TCD|04|TCD_DESCRI|C|40|0|Descricao|Desc. do Monitoramento
TCD|05|TCD_FONTE|C|6|0|Fonte|Cod. da Fonte de Medicao
TCD|06|TCD_DESFON|C|40|0|Descricao|Desc. da Fonte de Medicao
TCD|07|TCD_STATUS|C|1|0|Status|Status do Monitoramento
TCD|08|TCD_GRUPO|C|6|0|Grupo|Codigo do Grupo Gerador
TCD|09|TCD_DESGRP|C|40|0|Desc. Grupo|Descricao do Grupo
TCD|10|TCD_ASPECT|C|6|0|Aspecto|Codigo do Aspecto
TCD|11|TCD_DESASP|C|40|0|Descricao|Descricao do Aspecto
TCD|12|TCD_IMPACT|C|6|0|Impacto|Codigo do Impacto
TCD|13|TCD_DESIMP|C|40|0|Descricao|Descricao do Impacto
TCD|14|TCD_OBSERV|M|10|0|Observacao|Observacao da Medicao
TCD|15|TCD_DTINI|D|8|0|Data Início|Data Início Monint.
TCD|16|TCD_HRINI|C|5|0|Hora inicio|Hora Inicio Monit.
TCD|17|TCD_FLAG|C|1|0|Módulo|Módulo de Criação
TCD|18|TCD_TIPO|C|1|0|Tipo|Tipo Monitoramento
TCD|19|TCD_CODPER|C|6|0|Perigo|Código do Perigo
TCD|20|TCD_NOMPER|C|40|0|Nome Perigo|Nome do Perigo
TCD|21|TCD_CODDAN|C|6|0|Dano|Código do Dano
TCD|22|TCD_DESDAN|C|40|0|Nome Dano|Nome do Dano
--- ### TCE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCE|01|TCE_FILIAL|C|6|0|Filial|Filial do Sistema
TCE|02|TCE_CODMON|C|6|0|Cod. Monit.|Codigo do Monitoramento
TCE|03|TCE_CODCRI|C|6|0|Criterio|Codigo do Criterio
TCE|04|TCE_DESCRI|C|40|0|Descricao|Descricao do Criterio
TCE|05|TCE_LIMMIN|N|8|4|Lim. Minimo|Limite Minimo
TCE|06|TCE_LIMMAX|N|8|4|Lim. Maximo|Limite Maximo do Criterio
TCE|07|TCE_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TCE|08|TCE_FREQUE|N|3|0|Frequencia|Frequencia das Medicoes
TCE|09|TCE_TIPFRE|C|1|0|Tipo Freq.|Tipo de Frequencia
TCE|10|TCE_DTMED|D|8|0|Dt. Ult. Med|Data da Ultima Medicao
TCE|11|TCE_HRMED|C|5|0|Hr. Ult. Med|Hora da Ultima Medicao
TCE|12|TCE_CODLAB|C|6|0|Laboratório|Código do Laboratório
TCE|13|TCE_NOMLAB|C|80|0|Nome Lab.|Nome do Laboratório
--- ### TCF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCF|01|TCF_FILIAL|C|6|0|Filial|Filial do Sistema
TCF|02|TCF_CODMON|C|6|0|Cod. Monit.|Codigo do Monitoramento
TCF|03|TCF_CODREQ|C|12|0|Requisito|Codigo do Requisito
TCF|04|TCF_DESREQ|C|40|0|Tema|Tema do Requisito
--- ### TCG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCG|01|TCG_FILIAL|C|6|0|Filial|Filial do Sistema
TCG|02|TCG_CODMON|C|6|0|Cod. Monit.|Codigo do Monitoramento
TCG|03|TCG_TIPRES|C|1|0|Tip. Resp.|Tipo Responsável
TCG|04|TCG_CODRES|C|16|0|Responsavel|Codigo do Responsavel
TCG|05|TCG_NOMRES|C|40|0|Nome|Nome do Responsavel
--- ### TCH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCH|01|TCH_FILIAL|C|6|0|Filial|Filial do Sistema
TCH|02|TCH_ANALIS|C|10|0|Analise|Codigo da Analise
TCH|03|TCH_DTCOLE|D|8|0|Dt. Coleta|Data da Coleta
TCH|04|TCH_HRCOLE|C|5|0|Hr. Coleta|Hora da Coleta
TCH|05|TCH_CODCRI|C|6|0|Criterio|Codigo do Criterio
TCH|06|TCH_DESCRI|C|40|0|Descricao|Descricao do Criterio
TCH|07|TCH_QUANTI|N|8|4|Quantidade|Quantidade Analisada
TCH|08|TCH_UNIMED|C|2|0|Unid. Medida|Cod. da Unidade de Medida
TCH|09|TCH_FORNEC|C|6|0|Laboratorio|Codigo do Laboratorio
TCH|10|TCH_DESFOR|C|80|0|Descrição|Descrição do Laboratório
TCH|11|TCH_FONTE|C|6|0|Fonte|Fonte de Medicao
TCH|12|TCH_DESFON|C|80|0|Descrição|Descrição da Fonte
TCH|13|TCH_GRUPO|C|6|0|Grupo|Grupo de Medicao
TCH|14|TCH_DESGRU|C|40|0|Descrição|Descrição do Grupo
TCH|15|TCH_MONIT|C|6|0|Monitoramen.|Cód. Monitoramento
TCH|16|TCH_DESMON|C|40|0|Descrição|Descrição do Monitorament
TCH|17|TCH_STATUS|C|1|0|Status Ana.|Status Analise
TCH|18|TCH_DESPLA|C|40|0|Descrição|Descrição do Plano
TCH|19|TCH_CODPLA|C|6|0|Plano|Código do Plano de Ação
TCH|20|TCH_LOJA|C|2|0|Loja|Loja Fornecedor
--- ### TCI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCI|01|TCI_FILIAL|C|6|0|Filial|Filial do Sistema
TCI|02|TCI_CODOCO|C|6|0|Ocorrência|Código da Ocorrência
TCI|03|TCI_CODRES|C|15|0|Resíduo|Código do Resíduo
TCI|04|TCI_DESCRE|C|70|0|Desc. Resid.|Desc. de Residuos
TCI|05|TCI_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TCI|06|TCI_QTDE|N|9|2|Qtde. Resid.|Qtde. de Residuos Gerado
--- ### TCJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCJ|01|TCJ_FILIAL|C|6|0|Filial|Filial do Sistema
TCJ|02|TCJ_CODNIV|C|6|0|Nivel|Codigo do nivel
TCJ|03|TCJ_DESNIV|C|56|0|Desc. Nivel|Descricao do Nivel
TCJ|04|TCJ_NIVSUP|C|6|0|C. Nivel Sup|Codigo do Nivel Superior
TCJ|05|TCJ_DATA|D|8|0|Data Proc.|Data do Processamento
TCJ|06|TCJ_HORA|C|5|0|Hora Proc.|Hora do Processamento
TCJ|07|TCJ_TIPROC|C|1|0|Tipo Proc.|Tipo de Processamento
TCJ|08|TCJ_NIVEL|N|3|0|Nivel|Nível da Localização
TCJ|09|TCJ_MODSGA|C|1|0|Usado SGA|Usado no Mod. SGA
TCJ|10|TCJ_MODMDT|C|1|0|Usado MDT|Usado no Mod. MDT
TCJ|11|TCJ_MODMNT|C|1|0|Usado MNT|Usado no Mod. MNT
--- ### TCK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCK|01|TCK_FILIAL|C|6|0|Filial|Filial do Sistema
TCK|02|TCK_CODLEG|C|12|0|Requisito|Codigo do Requisito
TCK|03|TCK_CODPRO|C|20|0|Protocolo|Codigo do Protocolo
TCK|04|TCK_DESPRO|C|40|0|Descrição|Descrição
TCK|05|TCK_OBSERV|M|10|0|Observação|Observação
TCK|06|TCK_ORGAO|C|10|0|Órgão Amb.|Órgão Amb.
TCK|07|TCK_DTENTR|D|8|0|Entrega|Data de Entrega
TCK|08|TCK_QTDIAS|N|4|0|Quant. Dias|Qtde. de Dias
TCK|09|TCK_DTALER|D|8|0|Alerta|Data de Alerta
TCK|10|TCK_RESPON|C|16|0|Responsável|Responsável
TCK|11|TCK_NOMRES|C|40|0|Nome Resp.|Nome do Responsavel
TCK|12|TCK_STATUS|C|1|0|Status|Status do Protocolo
TCK|13|TCK_NOTAS|M|10|0|Notas|Notas do Protocolo
TCK|14|TCK_CODLIC|C|10|0|Nº Licença|Nº Licença
TCK|15|TCK_NAOCON|M|10|0|Motivo|Motivo
TCK|16|TCK_MMOBS|C|6|0|ChaveMM SYP|Chave Memo SYP
TCK|17|TCK_MMNOT|C|6|0|ChaveMM SYP|Chave Memo SYP
TCK|18|TCK_MMNCON|C|6|0|ChaveMM SYP|Chave Memo SYP
--- ### TCL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCL|01|TCL_FILIAL|C|6|0|Filial|Filial do Sistema
TCL|02|TCL_CODLEG|C|12|0|Requisito|Requisito
TCL|03|TCL_CODPLA|C|6|0|Plano Ação|Cod. do Plano de Ação
TCL|04|TCL_DESPLA|C|40|0|Descrição|Descrição
--- ### TCM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCM|01|TCM_FILIAL|C|6|0|Filial|Filial do Sistema
TCM|02|TCM_CODLEG|C|12|0|Requisito|Codigo do Requisito
TCM|03|TCM_RESPON|C|10|0|Responsável|Responsável
TCM|04|TCM_NOMRES|C|40|0|Nome|Nome do Responsavel
--- ### TCN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCN|01|TCN_FILIAL|C|6|0|Filial|Filial do Sistema
TCN|02|TCN_CODPLA|C|6|0|Plano Ação|Cod. do Plano de Ação
TCN|03|TCN_DATA|D|8|0|Data|Data do Planejamento
TCN|04|TCN_NOMPLA|C|40|0|Descrição|Desc. do Planejamento
TCN|05|TCN_META|N|3|0|Meta|Meta do Planejamento
TCN|06|TCN_WFPROC|C|1|0|WF Proc.|Workflow Processado
TCN|07|TCN_PLANEJ|C|6|0|Planejamento|Codigo do Planejamento
--- ### TCO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCO|01|TCO_FILIAL|C|6|0|Filial|Filial do Sistema
TCO|02|TCO_CODMEL|C|6|0|Codigo|Codigo da Melhoria
TCO|03|TCO_DESMEL|C|40|0|Descrição|Desc. da Melhoria
TCO|04|TCO_LOCAL|C|3|0|Local|Código do Local
TCO|05|TCO_DESLOC|C|40|0|Descrição|Desc. do Local
TCO|06|TCO_OBSMEL|M|10|0|Op. Melhoria|Oportunidade da Melhoria
TCO|07|TCO_CODIMP|C|6|0|Impacto|Código do Impacto
TCO|08|TCO_DESIMP|C|40|0|Descrição|Descricao do Impacto
TCO|09|TCO_PRIORI|C|1|0|Prioridade|Prioridade da Melhoria
TCO|10|TCO_CODRES|C|16|0|Autor|Código do Autor
TCO|11|TCO_DESRES|C|40|0|Nome|Nome do Autor
TCO|12|TCO_DATA|D|8|0|Data|Data da Melhoria
TCO|13|TCO_CODACA|C|6|0|Plano Ação|Código do Plano de Ação
TCO|14|TCO_DESACA|C|40|0|Descrição|Descrição do Plano deAção
TCO|15|TCO_FLAG|C|1|0|Módulo|Módulo de Criação
TCO|16|TCO_TIPO|C|1|0|Tipo|Tipo Oport.
TCO|17|TCO_CODDAN|C|6|0|Dano|Código do Dano
TCO|18|TCO_DESDAN|C|20|0|Nome Dano|Nome do Dano
TCO|19|TCO_CODFUN|C|6|0|Func. Autor|Funcionário Autor
TCO|20|TCO_NOMFUN|C|20|0|Nome Func.|Nome do Funcionário
TCO|21|TCO_STATUS|C|1|0|Status|Status da Oport. Melhoria
--- ### TCP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCP|01|TCP_FILIAL|C|6|0|Filial|Filial do Sistema
TCP|02|TCP_CODEXP|C|6|0|Codigo|Codigo Cont. Expedicao
TCP|03|TCP_CODLEG|C|12|0|Requisito|Codigo do Requisito
TCP|04|TCP_EMENTA|C|80|0|Ementa|Ementa da Legislacao
TCP|05|TCP_TIPO|C|12|0|Tipo Docto.|Tipo Documento de Expedic
TCP|06|TCP_OREMIS|C|12|0|Orgao Emiss.|Orgao Ambiental Emissor
TCP|07|TCP_EST|C|2|0|Estado|Sigla da Federacao
TCP|08|TCP_DTVIGE|D|8|0|Vigencia|Data de Vigencia
TCP|09|TCP_DTVENC|D|8|0|Vencimento|Data de Vencimento
TCP|10|TCP_CODRES|C|15|0|Resíduo|Codigo do Residuo
TCP|11|TCP_NOMRES|C|70|0|Descricao|Descricao do Residuo
TCP|12|TCP_QUANTI|N|9|2|Qtde. Limite|Quantidade Limite
TCP|13|TCP_TOTAL|N|9|2|Total Exp.|Total Expedido
TCP|14|TCP_SALDO|N|9|2|Saldo|Saldo Disponível
TCP|15|TCP_CODREC|C|6|0|Receptor|Código Receptor
TCP|16|TCP_DESFOR|C|40|0|Descricao|Descricao do Fornecedor
TCP|17|TCP_ATIVID|C|25|0|Atividade|Atividade Industrial
TCP|18|TCP_DOCTO|N|10|0|Nr. Docto|Numero Documento de Exped
TCP|19|TCP_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
--- ### TCQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCQ|01|TCQ_FILIAL|C|6|0|Filial|Filial do Sistema
TCQ|02|TCQ_CODEXP|C|6|0|Codigo|Codigo Cont. Expedicao
TCQ|03|TCQ_CODRES|C|15|0|Residuo|Codigo do Residuo
TCQ|04|TCQ_DTTRAN|D|8|0|Data Transf.|Data da Transferencia
TCQ|05|TCQ_HRTRAN|C|5|0|Hora Transf.|Hora da Transferencia
TCQ|06|TCQ_RETMTR|C|1|0|Retorno MTR|Retorno MTR (1=Sim,2=Nao)
TCQ|07|TCQ_CODCER|N|10|0|Nº Cert.|Numero do Certificado
TCQ|08|TCQ_CAPINM|C|10|0|Nº Cap.Inmet|Nº do Cert. Cap. INMETRO
--- ### TCS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TCS|01|TCS_FILIAL|C|6|0|Filial|Filial do Sistema
TCS|02|TCS_CLASSE|C|6|0|Classe|Classificação de Resíduos
TCS|03|TCS_DESCRI|C|40|0|Desc. Classe|Descricao da Classe
TCS|04|TCS_PERIGO|C|1|0|Perigosa?|Classe Perigosa?
--- ### TD0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD0|01|TD0_FILIAL|C|6|0|Filial|Filial do Sistema
TD0|02|TD0_CODIGO|C|10|0|Gás|Gás
TD0|03|TD0_DESCRI|C|40|0|Descrição|Descrição
TD0|04|TD0_UNIMED|C|2|0|Unid. Medida|Unidade de Medida
TD0|05|TD0_OBSERV|C|6|0|Observação|Observação
TD0|06|TD0_MEMO1|M|10|0|Observação|Observação
TD0|07|TD0_PAG|N|11|5|PAG|PAG
--- ### TD1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD1|01|TD1_FILIAL|C|6|0|Filial|Filial do Sistema
TD1|02|TD1_CODIGO|C|10|0|Fonte|Fonte
TD1|03|TD1_DESCRI|C|40|0|Descrição|Descrição
TD1|04|TD1_ESCOPO|C|1|0|Escopo|Escopo
TD1|05|TD1_TIPFON|C|1|0|Tipo Fonte|Tipo Fonte
TD1|06|TD1_OBSERV|C|6|0|Observação|Observação
TD1|07|TD1_MEMO1|M|10|0|Observação|Observação
--- ### TD2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD2|01|TD2_FILIAL|C|6|0|Filial|Filial do Sistema
TD2|02|TD2_CODPRO|C|15|0|Produto|Produto
TD2|03|TD2_DESPRO|C|70|0|Descrição|Descrição
TD2|04|TD2_UNIPRO|C|2|0|Unid. Medida|Unidade de Medida
TD2|05|TD2_OBSERV|C|6|0|Observação|Observação
TD2|06|TD2_MEMO1|M|10|0|Observação|Observação
--- ### TD3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD3|01|TD3_FILIAL|C|6|0|Filial|Filial do Sistema
TD3|02|TD3_CODPRO|C|15|0|Produto|Produto
TD3|03|TD3_ESTRUT|C|3|0|Estrutura|Estrutura
TD3|04|TD3_CODNIV|C|6|0|Nível|Nível
TD3|05|TD3_NOMNIV|C|30|0|Nome Nível|Nome Nível
TD3|06|TD3_PORCEN|N|5|1|% PCP/MNT|% PCP/MNT
--- ### TD4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD4|01|TD4_FILIAL|C|6|0|Filial|Filial do Sistema
TD4|02|TD4_CODPRO|C|15|0|Produto|Produto
TD4|03|TD4_CODGAS|C|10|0|Gás|Gás
TD4|04|TD4_DESGAS|C|30|0|Descrição|Descrição
TD4|05|TD4_UNIGAS|C|2|0|Unid. Medida|Unidade de Medida
TD4|06|TD4_FATOR|N|11|5|Fator Emis.|Fator Emis.
--- ### TD5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD5|01|TD5_FILIAL|C|6|0|Filial|Filial do Sistema
TD5|02|TD5_CODPRO|C|15|0|Produto|Produto
TD5|03|TD5_ESTRUT|C|3|0|Estrutura|Estrutura
TD5|04|TD5_CODNIV|C|3|0|Nível|Nível
TD5|05|TD5_CODFON|C|10|0|Fonte|Fonte
TD5|06|TD5_DESFON|C|30|0|Descrição|Descrição
TD5|07|TD5_PORCEN|N|5|1|% PCP/MNT|% PCP/MNT
--- ### TD6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD6|01|TD6_FILIAL|C|6|0|Filial|Filial do Sistema
TD6|02|TD6_CODPRO|C|15|0|Produto|Produto
TD6|03|TD6_ESTRUT|C|3|0|Estrutura|Estrutura
TD6|04|TD6_CODNIV|C|6|0|Nível|Nível
TD6|05|TD6_NOMNIV|C|30|0|Nome Nível|Nome Nível
TD6|06|TD6_PORCEN|N|5|1|% PCP/MNT|% PCP/MNT
TD6|07|TD6_DATA|D|8|0|Data Alter.|Data Alter.
TD6|08|TD6_HORA|C|8|0|Hora Alter.|Hora Alter.
TD6|09|TD6_OPERAC|C|1|0|Operação|Operação
--- ### TD7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD7|01|TD7_FILIAL|C|6|0|Filial|Filial do Sistema
TD7|02|TD7_CODPRO|C|15|0|Produto|Produto
TD7|03|TD7_CODGAS|C|10|0|Gás|Gás
TD7|04|TD7_DESGAS|C|30|0|Descrição|Descrição
TD7|05|TD7_UNIGAS|C|2|0|Unid. Medida|Unidade de Medida
TD7|06|TD7_FATOR|N|11|4|Fator Emis.|Fator Emis.
TD7|07|TD7_DATA|D|8|0|Data Alter.|Data Alter.
TD7|08|TD7_HORA|C|8|0|Hora Alter.|Hora Alter.
TD7|09|TD7_OPERAC|C|1|0|Operação|Operação
--- ### TD8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD8|01|TD8_FILIAL|C|6|0|Filial|Filial do Sistema
TD8|02|TD8_CODPRO|C|15|0|Produto|Produto
TD8|03|TD8_ESTRUT|C|3|0|Estrutura|Estrutura
TD8|04|TD8_CODNIV|C|3|0|Nível|Nível
TD8|05|TD8_CODFON|C|10|0|Fonte|Fonte
TD8|06|TD8_DESFON|C|30|0|Descrição|Descrição
TD8|07|TD8_PORCEN|N|5|1|% PCP/MNT|% PCP/MNT
TD8|08|TD8_DATA|D|8|0|Data Alter.|Data Alter.
TD8|09|TD8_HORA|C|8|0|Hora Alter.|Hora Alter.
TD8|10|TD8_OPERAC|C|1|0|Operação|Operação
--- ### TD9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TD9|01|TD9_FILIAL|C|6|0|Filial|Filial do Sistema
TD9|02|TD9_CODIGO|C|6|0|Ocorrência|Ocorrência
TD9|03|TD9_DATA|D|8|0|Data Ocor.|Data Ocor.
TD9|04|TD9_HORA|C|5|0|Hora Ocor.|Hora Ocor.
TD9|05|TD9_CODPRO|C|15|0|Produto|Produto
TD9|06|TD9_DESPRO|C|70|0|Descrição|Descrição
TD9|07|TD9_QUANTI|N|9|2|Qtde. Prod.|Qtde. Prod.
TD9|08|TD9_UNIPRO|C|2|0|Unid. Medida|Unidade de Medida
TD9|09|TD9_ESTRUT|C|3|0|Estrutura|Estrutura
TD9|10|TD9_CODNIV|C|3|0|Nível|Nível
TD9|11|TD9_CODFON|C|15|0|Fonte|Fonte
TD9|12|TD9_DESFON|C|30|0|Descrição|Descrição
TD9|13|TD9_ORIGEM|C|1|0|Origem|Origem
TD9|14|TD9_OP|C|14|0|Ord Produção|Ord Produção
TD9|15|TD9_ORDEM|C|6|0|Ordem Serv.|Ordem Serv.
--- ### TDA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDA|01|TDA_FILIAL|C|6|0|Filial|Filial do Sistema
TDA|02|TDA_CODOCO|C|6|0|Ocorrência|Ocorrência
TDA|03|TDA_CODGAS|C|10|0|Gás|Gás
TDA|04|TDA_DESGAS|C|30|0|Descrição|Descrição
TDA|05|TDA_GERADO|N|11|4|Qtde. Ger.|Qtde. Ger.
TDA|06|TDA_UNIGAS|C|2|0|Unid. Medida|Unidade de Medida
--- ### TDB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDB|01|TDB_FILIAL|C|6|0|Filial|Filial do Sistema
TDB|02|TDB_DEPTO|C|6|0|Localização|Localização
TDB|03|TDB_CODIGO|C|6|0|Código|Código do Ponto
TDB|04|TDB_DESCRI|C|40|0|Descrição|Descrição do Ponto
TDB|05|TDB_BITMAP|C|20|0|Imagem|Imagem do Ponto
TDB|06|TDB_PLANTA|C|1|0|Planta Gráf.|Planta Gráfica
TDB|07|TDB_TIPIMG|C|1|0|Tipo Imagem|Tipo de Imagem
TDB|08|TDB_IMAGEM|C|30|0|Imagem|Imagem
TDB|09|TDB_POSX|N|4|0|Posicao em X|Posicao em X
TDB|10|TDB_POSY|N|4|0|Posicao em Y|Posicao em Y
TDB|11|TDB_TAMX|N|7|2|Largura|Largura da Imagem
TDB|12|TDB_TAMY|N|7|2|Altura|Altura da Imagem
TDB|13|TDB_MOVBLO|C|1|0|Movim. Bloq.|Movimentação Bloqueada
TDB|14|TDB_ALERTX|N|4|0|Alerta em X|Alerta em X
TDB|15|TDB_ALERTY|N|4|0|Alerta em Y|Alerta em Y
TDB|16|TDB_DESDEP|C|56|0|Descrição|Descrição
--- ### TDC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDC|01|TDC_FILIAL|C|6|0|Filial|Filial do Sistema
TDC|02|TDC_CODFMR|C|6|0|Cod. FMR|Código da FMR
TDC|03|TDC_DATA|D|8|0|Data|Data da FMR
TDC|04|TDC_DEPTO|C|6|0|Localização|Localização da FMR
TDC|05|TDC_DESDEP|C|30|0|Desc. Depto.|Desc. do Localização
TDC|06|TDC_CODPNT|C|6|0|Ponto Coleta|Código do Ponto
TDC|07|TDC_DESCRI|C|30|0|Desc. Ponto|Desc. do Ponto
TDC|08|TDC_CODRES|C|15|0|Resíduo|Código do Resíduo
TDC|09|TDC_DESCRE|C|70|0|Desc. Resíd.|Desc. do Resíduo
TDC|10|TDC_RESPON|C|25|0|Responsável|Responsável pela FMR
TDC|11|TDC_NOMRES|C|30|0|Nome Resp.|Nome do Responsável
TDC|12|TDC_MMOBS|C|6|0|Observação|Observação
TDC|13|TDC_OBSERV|M|10|0|Observação|Observação
TDC|14|TDC_STATUS|C|1|0|Status|Status da FMR
TDC|15|TDC_LIBRES|C|1|0|Lib. Rest.?|Lib. C/ Restrições?
TDC|16|TDC_MMNC|C|6|0|Descrição NC|Desc. Não Conformidade
TDC|17|TDC_DESCNC|M|10|0|Descrição NC|Desc. Não Conformidade
TDC|18|TDC_CODOCO|C|6|0|Ocorrência|Código Ocorrência
TDC|19|TDC_FNC|C|15|0|Cód. FNC|Código FNC
--- ### TDD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDD|01|TDD_FILIAL|C|6|0|Filial|Filial do Sistema
TDD|02|TDD_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TDD|03|TDD_SEQUEN|C|3|0|Sequência|Sequência
TDD|04|TDD_ACONDI|C|6|0|Acondicion.|Acondicionamento
TDD|05|TDD_DESCAC|C|30|0|Desc. Acond.|Desc. Acondicionamento
TDD|06|TDD_COLET|C|15|0|Coletor|Código Coletor
TDD|07|TDD_DESCCO|C|70|0|Desc. Colet.|Descrição Coletor
TDD|08|TDD_UNICOL|C|2|0|Un. Coletor|Unidade do Coletor
TDD|09|TDD_PESO|N|9|2|Peso|Peso do Resíduo
TDD|10|TDD_UNIRES|C|2|0|Un. Resíduo|Unidade do Resíduo
--- ### TDE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDE|01|TDE_FILIAL|C|6|0|Filial|Filial do Sistema
TDE|02|TDE_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TDE|03|TDE_MAT|C|16|0|Usuário|Codigo do Usuário
TDE|04|TDE_NOME|C|30|0|Nome Usuário|Nome do Usuário
--- ### TDF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDF|01|TDF_FILIAL|C|6|0|Filial|Filial do Sistema
TDF|02|TDF_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TDF|03|TDF_DTALT|D|8|0|Data Alteraç|Data da Alteração
TDF|04|TDF_HRALT|C|8|0|Hora Alteraç|Hora da Alteração
TDF|05|TDF_DATA|D|8|0|Data|Data da FMR
TDF|06|TDF_DEPTO|C|3|0|Localização|Localização da FMR
TDF|07|TDF_DESDEP|C|30|0|Desc. Depto.|Desc. do Localização
TDF|08|TDF_CODPNT|C|6|0|Ponto Coleta|Código do Ponto
TDF|09|TDF_DESCRI|C|30|0|Desc. Ponto|Desc. do Ponto
TDF|10|TDF_CODRES|C|15|0|Resíduo|Código do Resíduo
TDF|11|TDF_DESCRE|C|70|0|Desc. Resíd.|Desc. de Resíduo
TDF|12|TDF_RESPON|C|25|0|Responsável|Responsável pela FMR
TDF|13|TDF_NOMRES|C|30|0|Nome Resp.|Nome do Responsável
TDF|14|TDF_MMOBS|C|6|0|Observação|Observação
TDF|15|TDF_OBSERV|M|10|0|Observação|Observação
TDF|16|TDF_STATUS|C|1|0|Status|Status da FMR
TDF|17|TDF_LIBRES|C|1|0|Lib. Rest.?|Lib. C/ Restrições?
TDF|18|TDF_MMNC|C|6|0|Descrição NC|Desc. Não Conformidade
TDF|19|TDF_DESCNC|M|10|0|Descrição NC|Desc. Não Conformidade
TDF|20|TDF_USUALT|C|25|0|Usuário Alte|Usuário da Alteração
TDF|21|TDF_NOMUSU|C|30|0|Nome Usuário|Nome Usuário Alteração
TDF|22|TDF_FNC|C|15|0|Cód. FNC|Código FNC
TDF|23|TDF_CODOCO|C|6|0|Ocorrência|Código Ocorrência
--- ### TDG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDG|01|TDG_FILIAL|C|6|0|Filial|Filial do Sistema
TDG|02|TDG_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TDG|03|TDG_DTALT|D|8|0|Data Alteraç|Data da Alteração
TDG|04|TDG_HRALT|C|8|0|Hora Alteraç|Hora da Alteração
TDG|05|TDG_SEQUEN|C|3|0|Sequência|Sequência
TDG|06|TDG_ACONDI|C|6|0|Acondicion.|Acondicionamento
TDG|07|TDG_DESCAC|C|30|0|Desc. Acond.|Desc. Acondicionamento
TDG|08|TDG_COLET|C|15|0|Coletor|Código Coletor
TDG|09|TDG_DESCCO|C|70|0|Desc. Colet.|Descrição Coletor
TDG|10|TDG_UNICOL|C|2|0|Un. Coletor|Unidade do Coletor
TDG|11|TDG_PESO|N|9|2|Peso|Peso do Resíduo
TDG|12|TDG_UNIRES|C|2|0|Un. Resíduo|Unidade do Resíduo
--- ### TDH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDH|01|TDH_FILIAL|C|6|0|Filial|Filial do Sistema
TDH|02|TDH_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TDH|03|TDH_DTALT|D|8|0|Data Alteraç|Data da Alteração
TDH|04|TDH_HRALT|C|8|0|Hora Alteraç|Hora da Alteração
TDH|05|TDH_MAT|C|10|0|Usuário|Codigo do Usuário
TDH|06|TDH_NOME|C|30|0|Nome Usuário|Nome do Usuário
--- ### TDI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDI|01|TDI_FILIAL|C|6|0|Filial|Filial do Sistema
TDI|02|TDI_CODCOM|C|6|0|Composição|Composição Carga
TDI|03|TDI_CODRES|C|15|0|Resíduo|Código do Resíduo
TDI|04|TDI_DESCRE|C|70|0|Desc. Resíd.|Desc. do Resíduo
TDI|05|TDI_DESEST|C|15|0|Est. Físico|Estado Físico
TDI|06|TDI_DTCOMP|D|8|0|Data|Data Composição
TDI|07|TDI_HRCOMP|C|5|0|Hora|Hora Composição
TDI|08|TDI_NUMMTR|C|15|0|Número MTR|Número do MTR
TDI|09|TDI_PESOTO|N|9|2|Peso Total|Peso Total
TDI|10|TDI_UNIDAD|C|2|0|Unid. Med.|Unidade de Medida
TDI|11|TDI_PESOBA|N|9|2|Peso Balança|Peso Balança
TDI|12|TDI_UNIBAL|C|1|0|Unid. Balan.|Unidade da Balança
TDI|13|TDI_STATUS|C|1|0|Status|Status
TDI|14|TDI_ORIGEM|C|3|0|Origem|Origem
TDI|15|TDI_DESORI|C|30|0|Desc. Orig.|Descrição da Origem
TDI|16|TDI_PROCED|C|3|0|Procedência|Procedência
TDI|17|TDI_DESPRO|C|30|0|Desc. Proc.|Descrição da Procedência
TDI|18|TDI_CODTRA|C|3|0|Tratamento|Tratamento
TDI|19|TDI_DESTRA|C|30|0|Desc. Trat.|Descrição do Tratamento
TDI|20|TDI_DTALTE|D|8|0|Data Altera|Data Altera
TDI|21|TDI_HRALTE|C|5|0|Hora Altera|Hora Altera
TDI|22|TDI_EMPGER|C|2|0|Emp. Gerado|Empresa Geradora
TDI|23|TDI_FILGER|C|6|0|Fil. Gerado|Filial Geradora
TDI|24|TDI_NOMGER|C|40|0|Razão Social|Razão Social da Indústria
TDI|25|TDI_ENDGER|C|30|0|Logradouro/n|Logradouro/número
TDI|26|TDI_CIDGER|C|20|0|Município|Município
TDI|27|TDI_ESTGER|C|2|0|UF|Unidade Federativa
TDI|28|TDI_TELGER|C|18|0|Telefone|Telefone
TDI|29|TDI_LICGER|C|12|0|N. Licença|N. Licença
TDI|30|TDI_RESPEX|C|10|0|Resp. Exped.|Responsável Expedição
TDI|31|TDI_NMREEX|C|40|0|Nome|Nome Responsável
TDI|32|TDI_CARGRE|C|40|0|Cargo|Cargo Resp. Expedição
TDI|33|TDI_DTEGER|D|8|0|Data Entrega|Data Entrega
TDI|34|TDI_TPTRAN|C|1|0|Transporte|Tipo do Transporte
TDI|35|TDI_CDTRAN|C|6|0|Transport.|Código do Transportador
TDI|36|TDI_EMPTRA|C|2|0|Emp. Transp.|Empresa Transportadora
TDI|37|TDI_FILTRA|C|6|0|Fil. Transp.|Filial Transportadora
TDI|38|TDI_NOMTRA|C|40|0|Razão Social|Razão Social da Indústria
TDI|39|TDI_ENDTRA|C|40|0|Logradouro/n|Logradouro/número
TDI|40|TDI_CIDTRA|C|15|0|Município|Município
TDI|41|TDI_ESTTRA|C|2|0|UF|Unidade Federativa
TDI|42|TDI_TELTRA|C|18|0|Telefone|Telefone
TDI|43|TDI_LICTRA|C|12|0|N. Licença|N. Licença
TDI|44|TDI_RESPTR|C|40|0|Resp. Trans.|Responsável pelo Transpor
TDI|45|TDI_CODMOT|C|6|0|Motorista|Código do Motorista
TDI|46|TDI_NOMMOT|C|40|0|Nome|Nome do Motorista
TDI|47|TDI_DTRTRA|D|8|0|Data Receb.|Data Receb.
TDI|48|TDI_CODREC|C|6|0|Receptor|Código Receptor
TDI|49|TDI_NOMREC|C|40|0|Razão Social|Razão Social da Indústria
TDI|50|TDI_ENDREC|C|40|0|Logradouro/n|Logradouro/número
TDI|51|TDI_CIDREC|C|15|0|Município|Município
TDI|52|TDI_ESTREC|C|2|0|UF|Unidade Federativa
TDI|53|TDI_TELREC|C|18|0|Telefone|Telefone
TDI|54|TDI_LICREC|C|12|0|N. Licença|N. Licença
TDI|55|TDI_RESPRE|C|40|0|Resp. Receb.|Responsável Recebimento
TDI|56|TDI_CARGRR|C|40|0|Cargo|Cargo Responsável Recebim
TDI|57|TDI_DTEREC|D|8|0|Data Entrega|Data Entrega
TDI|58|TDI_CONPAG|C|3|0|Cond. Pagto.|Condição de Pagamento
TDI|59|TDI_TES|C|3|0|Tipo Saída|Tipo de Saída do Item
TDI|60|TDI_NUM|C|6|0|Num. Pedido|Número do Pedido Venda
TDI|61|TDI_PREVEN|N|12|2|Preço Venda|Preço de Venda
TDI|62|TDI_MENNOT|C|60|0|Desc. NF|Descri. Nota Fiscal
TDI|63|TDI_MENPAD|C|3|0|Mens. Padrao|Mensagem Padrão
TDI|64|TDI_DESPAD|C|30|0|Desc. Mens.|Desc. Mens. Padrão
TDI|65|TDI_ESPEC1|C|10|0|Espécie 1|Espécie do Volume tipo 1
TDI|66|TDI_VOLUM1|N|5|0|Volume 1|Qtde de Volumes tipo 1
TDI|67|TDI_PESOL|N|11|4|Peso Líquido|Peso Líquido
TDI|68|TDI_PBRUTO|N|11|4|Peso Bruto|Peso Bruto
TDI|69|TDI_TPDEST|C|1|0|Tp. Destin.|Tipo Destinatário
TDI|70|TDI_FORNNF|C|6|0|Dest. NF|Destinatário da NF
TDI|71|TDI_LOJANF|C|2|0|Loja. Dest.|Loja Destinat. da NF
TDI|72|TDI_NOMDES|C|40|0|Razão Social|Razão Social da Indústria
TDI|73|TDI_DOC|C|9|0|Documento|Documento Movimen.
TDI|74|TDI_TIPDES|C|1|0|Tipo|Tipo de Destinação
TDI|75|TDI_CODTIP|C|6|0|Cod. Tipo|Cod. Tipo de Destinação
--- ### TDJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDJ|01|TDJ_FILIAL|C|6|0|Filial|Filial do Sistema
TDJ|02|TDJ_CODCOM|C|6|0|Composição|Composição Carga
TDJ|03|TDJ_CODOCO|C|6|0|Ocorrência|Código Ocorrência
TDJ|04|TDJ_PESOUT|N|9|2|Peso Util.|Peso Utilizado
--- ### TDK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDK|01|TDK_FILIAL|C|6|0|Filial|Filial do Sistema
TDK|02|TDK_CODCOM|C|6|0|Composição|Composição Carga
TDK|03|TDK_CODVEI|C|8|0|Veículo|Código Veículo
TDK|04|TDK_TIPVEI|C|1|0|Tipo Veículo|Tipo Veículo
TDK|05|TDK_PLACA|C|8|0|Placa|Placa do Veículo
TDK|06|TDK_NOMVEI|C|30|0|Nome Veículo|Nome Veículo
--- ### TDL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDL|01|TDL_FILIAL|C|6|0|Filial|Filial do Sistema
TDL|02|TDL_CODTRA|C|6|0|Cód. Transp.|Cód. Transp.
TDL|03|TDL_DESTRA|C|40|0|Desc. Trans.|Desc. Trans.
TDL|04|TDL_CODLAM|C|12|0|Licença|Codigo Licença Ambiental
TDL|05|TDL_DESLAM|C|80|0|Descrição|Desc. Licença Ambiental
TDL|06|TDL_OREMIS|C|12|0|Órgão Exp.|Órgão Expedidor
TDL|07|TDL_DATAVA|D|8|0|Dt. Validade|Data da Validade
TDL|08|TDL_INMETR|C|12|0|Cert.Inmetro|Codigo Licença Ambiental
TDL|09|TDL_DESINM|C|80|0|Descricao|Descricao Certif. Inmetro
TDL|10|TDL_STATUS|C|1|0|Status|Status da Transportadora
TDL|11|TDL_DOCFIL|C|6|0|Filial Docum|Filial do Documento
TDL|12|TDL_DOCTO|C|16|0|Documento|Documento Relacionado
--- ### TDM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDM|01|TDM_FILIAL|C|6|0|Filial|Filial do Sistema
TDM|02|TDM_CODVEI|C|8|0|Veículo|Código Veículo
TDM|03|TDM_PLACA|C|8|0|Placa|Placa do Veículo
TDM|04|TDM_NOMVEI|C|30|0|Nome|Nome Veículo
TDM|05|TDM_TPVEIC|C|1|0|Tipo Veículo|Tipo Veículo
TDM|06|TDM_CODTRA|C|6|0|Cód. Transp.|Cód. Transp.
TDM|07|TDM_DESTRA|C|40|0|Desc. Trans.|Desc. Trans.
TDM|08|TDM_CRLV|C|12|0|CRLV|Código CRLV
TDM|09|TDM_DTCRLV|D|8|0|Dt. Validade|Data da Validade
TDM|10|TDM_CIV|C|12|0|CIV|Código CIV
TDM|11|TDM_DTCIV|D|8|0|Dt. Validade|Data da Validade
TDM|12|TDM_CIPP|C|12|0|CIPP|Código CIPP
TDM|13|TDM_DTCIPP|D|8|0|Dt. Validade|Data da Validade
TDM|14|TDM_STATUS|C|1|0|Status|Status do Veículo
TDM|15|TDM_DOCFIL|C|6|0|Filial Docum|Filial do Documento
TDM|16|TDM_DOCTO|C|16|0|Documento|Documento Relacionado
--- ### TDN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDN|01|TDN_FILIAL|C|6|0|Filial|Filial
TDN|02|TDN_VAR|C|6|0|Variável|Código da Variável
TDN|03|TDN_DESCRI|C|40|0|Descrição|Descrição da Variável
TDN|04|TDN_UM|C|2|0|Unid. Med.|Unidade de Medida
--- ### TDO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDO|01|TDO_FILIAL|C|6|0|Filial|Filial do Sistema
TDO|02|TDO_VAR|C|6|0|Variável|Código da Variável
TDO|03|TDO_DTINI|D|8|0|Data Início|Data Início
TDO|04|TDO_DTFIM|D|8|0|Data Fim|Data Fim
TDO|05|TDO_RESULT|N|12|3|Resultado|Resultado no Período
--- ### TDP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDP|01|TDP_FILIAL|C|6|0|Filial|Filial do Sistema
TDP|02|TDP_CODFOR|C|3|0|Fórmula|Código da Fórmula
TDP|03|TDP_DESCRI|C|40|0|Descrição|Descrição da Fórmula
TDP|04|TDP_FORMUL|C|6|0|Chave Memo|Chave Memo SYP
--- ### TDR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TDR|01|TDR_FILIAL|C|6|0|Filial|Filial do Sistema
TDR|02|TDR_REVISA|C|6|0|Revisao|Codigo da Revisao
TDR|03|TDR_DESCRI|C|50|0|Descricao|Descricao da Revisao
--- ### TE8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE8|01|TE8_FILIAL|C|6|0|Filial|Filial do Sistema
TE8|02|TE8_CODLEG|C|12|0|Legislacao|Legislacao
TE8|03|TE8_DATA|D|8|0|Data Alt.|Data Alt.
TE8|04|TE8_HORA|C|8|0|Hora Alt.|Hora Alt.
TE8|05|TE8_DTVIGE|D|8|0|Vigencia|Vigencia
TE8|06|TE8_DTVENC|D|8|0|Vencimento|Vencimento
TE8|07|TE8_TIPCER|C|1|0|Tipo Cert.|Tipo Cert.
TE8|08|TE8_ORGCER|C|3|0|Org. Ceriti.|Org. Ceriti.
TE8|09|TE8_SITUAC|C|1|0|Situacao|Situacao
--- ### TE9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TE9|01|TE9_FILIAL|C|6|0|Filial|Filial do Sistema
TE9|02|TE9_CODIGO|C|3|0|Código|Código do Certificador
TE9|03|TE9_DESCRI|C|80|0|Orgão Cert.|Descrição do Certificador
--- ### TEA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEA|01|TEA_FILIAL|C|6|0|Filial|Filial do Sistema
TEA|02|TEA_CODCRE|C|6|0|C. Receptor|C. Receptor
TEA|03|TEA_DESCRE|C|40|0|Descricao|Descricao
TEA|04|TEA_BITMAP|C|8|0|Imagem|Imagem
TEA|05|TEA_TIPCOR|C|1|0|Tipo Corpo|Tipo Corpo
TEA|06|TEA_CLACOR|C|1|0|Classe Corpo|Classe Corpo
TEA|07|TEA_LATGRA|N|2|0|Lat. Graus|Lat. Graus
TEA|08|TEA_LATMIN|N|2|0|Lat. Minut.|Lat. Minut.
TEA|09|TEA_LATSEG|N|4|1|Lat. Segun.|Lat. Segun.
TEA|10|TEA_LATTIP|C|1|0|Tipo Lat.|Tipo Lat.
TEA|11|TEA_LONGRA|N|2|0|Lon. Graus|Lon. Graus
TEA|12|TEA_LONMIN|N|2|0|Lon. Minut.|Lon. Minut.
TEA|13|TEA_LONSEG|N|4|1|Lon. Segun.|Lon. Segun.
--- ### TEB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEB|01|TEB_FILIAL|C|6|0|Filial|Filial do Sistema
TEB|02|TEB_ANO|C|4|0|Ano|Ano
TEB|03|TEB_FONTE|C|6|0|Fonte|Fonte
TEB|04|TEB_DESFON|C|30|0|Desc. Fonte|Desc. Fonte
TEB|05|TEB_TRATAM|C|6|0|Tratamento|Tratamento
TEB|06|TEB_DESTRA|C|30|0|Desc. Trat.|Desc. Trat.
TEB|07|TEB_DESCRI|M|10|0|Descrição|Descrição
TEB|08|TEB_EFICIE|N|3|0|Eficiencia %|Eficiencia %
TEB|09|TEB_NIVELT|C|1|0|Nível Tratam|Nível Tratamento
TEB|10|TEB_COMPAR|C|1|0|Compart. Em.|Compart. Em.
TEB|11|TEB_TIPOEM|C|1|0|Tipo Emissao|Tipo Emissao
TEB|12|TEB_CORHID|C|6|0|C. Hidrico|C. Hidrico
TEB|13|TEB_DESCRE|C|40|0|Descricao|Descricao
TEB|14|TEB_CORPRE|C|1|0|Corpo Recep.|Corpo Recep.
TEB|15|TEB_OUTCOR|C|35|0|Qual?|Qual?
TEB|16|TEB_EMPREC|C|6|0|Emp. Recept.|Emp. Recept.
TEB|17|TEB_LOJREC|C|2|0|Emp. Recept.|Emp. Recept.
TEB|18|TEB_DESFOR|C|80|0|Descricao|Descricao
TEB|19|TEB_TPSOLO|C|1|0|Tp. Em. Solo|Tp. Em. Solo
TEB|20|TEB_OUTSOL|C|35|0|Qual?|Qual?
TEB|21|TEB_EMISSA|C|1|0|Emissao|Emissao
--- ### TEC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEC|01|TEC_FILIAL|C|6|0|Filial|Filial do Sistema
TEC|02|TEC_ANO|C|4|0|Ano|Ano
TEC|03|TEC_FONTE|C|6|0|Unidade Pol.|Unidade Pol.
TEC|04|TEC_TRATAM|C|6|0|Tratamento|Tratamento
TEC|05|TEC_CODPOL|C|6|0|Poluente|Poluente
TEC|06|TEC_DESPOL|C|30|0|Descricao|Descricao
TEC|07|TEC_DATA|D|8|0|Data|Data
TEC|08|TEC_QUANTI|N|8|2|Quantidade|Quantidade
TEC|09|TEC_UNIDAD|C|2|0|Unidade Med.|Unidade Med.
TEC|10|TEC_METODO|C|1|0|Metodo Afer.|Metodo Afer.
TEC|11|TEC_IDMETO|C|12|0|Iden. Metodo|Iden. Metodo
TEC|12|TEC_CONSIG|C|1|0|Sigilo|Sigilo
TEC|13|TEC_JUSSIG|M|10|0|Justif. Sig.|Justif. Sig.
--- ### TED
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TED|01|TED_FILIAL|C|6|0|Filial|Filial do Sistema
TED|02|TED_ANO|C|4|0|Ano|Ano
TED|03|TED_TIPO|C|1|0|Tipo|Tipo
TED|04|TED_BRWTIP|C|30|0|Tipo|Tipo
TED|05|TED_AUTGER|N|16|2|Auto-Ger. %|Auto-Ger. %
TED|06|TED_REDPUB|N|16|2|Rede Pub. %|Rede Pub. %
TED|07|TED_TEENXO|N|6|2|Teor Enxof.%|Teor Enxof.%
TED|08|TED_TENITR|N|6|2|Teor Nitro.%|Teor Nitro.%
TED|09|TED_TECINZ|N|6|2|Teor Cinzas%|Teor Cinzas%
TED|10|TED_QTCONS|N|16|2|Qtd. Consum.|Qtd. Consum.
TED|11|TED_CAUTGE|C|24|0|Auto-Ger. %|Auto-Ger. %
TED|12|TED_CREDPU|C|24|0|Red Pub. %|Red Pub. %
--- ### TEE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEE|01|TEE_FILIAL|C|6|0|Filial|Filial do Sistema
TEE|02|TEE_CODIGO|C|6|0|Código|Código
TEE|03|TEE_DESCRI|C|50|0|Descrição|Descrição
--- ### TEF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEF|01|TEF_FILIAL|C|6|0|Filial|Filial do Sistema
TEF|02|TEF_CODIGO|C|6|0|Código|Código
TEF|03|TEF_DESCRI|C|50|0|Descrição|Descrição
--- ### TEG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEG|01|TEG_FILIAL|C|6|0|Filial|Filial do Sistema
TEG|02|TEG_CODIGO|C|6|0|Código|Código
TEG|03|TEG_DESCRI|C|50|0|Descrição|Descrição
--- ### TEH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEH|01|TEH_FILIAL|C|6|0|Filial|Filial do Sistema
TEH|02|TEH_ANO|C|4|0|Ano|Ano
TEH|03|TEH_CODIGO|C|10|0|Código|Código
TEH|04|TEH_DESCRI|C|50|0|Descrição|Descrição
TEH|05|TEH_FONPOL|C|6|0|Fonte Polui.|Fonte Polui.
TEH|06|TEH_DESFON|C|30|0|Desc. Fonte|Desc. Fonte
TEH|07|TEH_CAPNOM|N|11|3|Cap. Nominal|Cap. Nominal
TEH|08|TEH_FUNDIA|N|2|0|Func. Diário|Func. Diário
TEH|09|TEH_EQTCON|C|6|0|Eqpto. Cont.|Eqpto. Cont.
TEH|10|TEH_DESEQT|C|50|0|Desc. Eqpto.|Desc. Eqpto.
TEH|11|TEH_POSCHA|C|1|0|Tem Chaminé|Tem Chaminé
TEH|12|TEH_TIPEMI|C|1|0|Tipo Emissão|Tipo Emissão
TEH|13|TEH_ALTITU|N|4|0|Altitude (m)|Altitude (m)
TEH|14|TEH_ALTURA|N|7|0|Altura (m)|Altura (m)
TEH|15|TEH_TMPGAS|N|6|2|Temp. Gases|Temp. Gases
TEH|16|TEH_DIAINT|N|7|2|Diam.Int.(m)|Diam.Int.(m)
TEH|17|TEH_VAZGAS|N|7|0|Vazão Gases|Vazão Gases
TEH|18|TEH_LATGRA|N|2|0|Lat. Graus|Lat. Graus
TEH|19|TEH_LATMIN|N|2|0|Lat. Minut.|Lat. Minut.
TEH|20|TEH_LATSEG|N|4|1|Lat. Segun.|Lat. Segun.
TEH|21|TEH_LATTIP|C|1|0|Tipo Lat.|Tipo Lat.
TEH|22|TEH_LONGRA|N|2|0|Lon. Graus|Lon. Graus
TEH|23|TEH_LONMIN|N|2|0|Lon. Minut.|Lon. Minut.
TEH|24|TEH_LONSEG|N|4|1|Lon. Segun.|Lon. Segun.
--- ### TEI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEI|01|TEI_FILIAL|C|6|0|Filial|Filial do Sistema
TEI|02|TEI_ANO|C|4|0|Ano|Ano
TEI|03|TEI_CODUNI|C|10|0|Fonte|Fonte
TEI|04|TEI_CODPOL|C|6|0|Poluente|Poluente
TEI|05|TEI_DESPOL|C|30|0|Descrição|Descrição
TEI|06|TEI_DATA|D|8|0|Data|Data
TEI|07|TEI_QUANTI|N|8|2|Quantidade|Quantidade
TEI|08|TEI_UNIDAD|C|2|0|Unidade Med.|Unidade Med.
TEI|09|TEI_METODO|C|1|0|Método Afer.|Método Afer.
TEI|10|TEI_IDMETO|C|12|0|Iden. Método|Iden. Método
TEI|11|TEI_CONSIG|C|1|0|Sigilo|Sigilo
TEI|12|TEI_JUSSIG|M|10|0|Justif. Sig.|Justif. Sig.
--- ### TEJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEJ|01|TEJ_FILIAL|C|6|0|Filial|Filial do Sistema
TEJ|02|TEJ_CODIGO|C|10|0|Código|Código
TEJ|03|TEJ_DESCRI|C|254|0|Descricao|Descricao
TEJ|04|TEJ_CAPMAX|N|14|2|Cap Pro/Con|Cap Pro/Con
TEJ|05|TEJ_UNIMED|C|2|0|Unid. Medida|Unid. Medida
TEJ|06|TEJ_DESUNI|C|40|0|Descricao|Descricao
TEJ|07|TEJ_TIPCLA|C|1|0|Tipo Classe|Tipo Classe
TEJ|08|TEJ_OBSERV|M|10|0|Observacoes|Observacoes
TEJ|09|TEJ_SIGILO|C|1|0|Sigilo?|Sigilo?
TEJ|10|TEJ_INFSI|M|10|0|Inf. Sigilo|Inf. Sigilo
TEJ|11|TEJ_TPSIGI|C|1|0|Tp. Sigilo|Tp. Sigilo
TEJ|12|TEJ_CODLEG|C|12|0|Requisito|Requisito
TEJ|13|TEJ_EMENTA|C|80|0|Tema da Lei|Tema da Lei
TEJ|14|TEJ_RELATO|C|1|0|Relatorio|Relatorio
--- ### TEK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEK|01|TEK_FILIAL|C|6|0|Filial|Filial do Sistema
TEK|02|TEK_CODIGO|C|6|0|Contrato|Cód. Contrato
TEK|03|TEK_FORNEC|C|6|0|Fornecedor|Fornecedor
TEK|04|TEK_DESFOR|C|80|0|Desc. Fornec|Desc. do Fornecedor
TEK|05|TEK_ANO|C|4|0|Ano Vigen.|Ano de Vigência
TEK|06|TEK_CODRES|C|15|0|Resíduo|Código do Resíduo
TEK|07|TEK_DESCRE|C|70|0|Desc. Resid.|Desc. de Residuo
TEK|08|TEK_VLTONE|N|12|2|Vl. Tonelada|Valor Tonelada
--- ### TEL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEL|01|TEL_FILIAL|C|6|0|FIlial|Filial do Sistema
TEL|02|TEL_PLACA|C|8|0|Placa|Placa do Caminhão
TEL|03|TEL_CODCAM|C|8|0|Caminhão|Código Caminhão
TEL|04|TEL_NOMCAM|C|30|0|Nome|Nome Caminhão
TEL|05|TEL_TRANSP|C|6|0|Transport.|Código do Transportadora
TEL|06|TEL_NOMTRA|C|40|0|Razão|Razão
TEL|07|TEL_CODLAM|C|12|0|Licença|Código Licença Ambiental
TEL|08|TEL_DATAVA|D|8|0|Dt. Validade|Data da Validade
TEL|09|TEL_DESLAM|C|80|0|Descrição|Desc. Licença Ambiental
TEL|10|TEL_CRLV|C|12|0|CRLV|Código CRLV
TEL|11|TEL_DTCRLV|D|8|0|Dt. Validade|Data da Validade
TEL|12|TEL_CIPP|C|12|0|CIPP|Código CIPP
TEL|13|TEL_DTCIPP|D|8|0|Dt. Validade|Data da Validade
TEL|14|TEL_STATUS|C|1|0|Status|Status do Caminhão
TEL|15|TEL_MOTIVO|M|10|0|Motivo Inat.|Motivo da Inatividade
--- ### TEM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEM|01|TEM_FILIAL|C|6|0|Filial|Filial do Sistema
TEM|02|TEM_CODIGO|C|10|0|Código|Codigo Agropesca/Prodlist
TEM|03|TEM_CODPRO|C|15|0|Produto|Produto
TEM|04|TEM_DESPRO|C|70|0|Descrição|Descricao do Produto
--- ### TEO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TEO|01|TEO_FILIAL|C|6|0|Filial|Filial
TEO|02|TEO_CODRES|C|15|0|Resíduo|Código do Resíduo
TEO|03|TEO_DATHIS|D|8|0|Data|Data do Histórico
TEO|04|TEO_HORHIS|C|5|0|Hora|Hora do Histórico
TEO|05|TEO_USUARI|C|15|0|Utilizador|Usuário do Histórico
TEO|06|TEO_OPERAC|C|1|0|Operação|Operação do Histórico
--- ### TF0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF0|01|TF0_FILIAL|C|6|0|Filial|Filial do Sistema
TF0|02|TF0_TIPO|C|1|0|Tp. Destin.|Tp. Destin.
TF0|03|TF0_TPRECE|C|1|0|Tp. Receptor|Tipo de Receptor
TF0|04|TF0_MENNOT|M|10|0|Descri. NF|Descri. NF
TF0|05|TF0_CODCOM|C|6|0|Cód.Composi.|Cód.Composi.
TF0|06|TF0_CODRES|C|15|0|Cod Residuo|Cod Residuo
TF0|07|TF0_DESCRE|C|70|0|Desc. Resíd.|Desc. do Resíd
TF0|08|TF0_DESEST|C|15|0|Est. Físico|Estado Físico
TF0|09|TF0_DTCOMP|D|8|0|Data|Data Composição
TF0|10|TF0_HRCOMP|C|5|0|Hora|Hora Composição
TF0|11|TF0_NUMMTR|C|15|0|Número MTR|Número MTR
TF0|12|TF0_PESOTO|N|9|2|Peso Total|Peso Total
TF0|13|TF0_UNIDAD|C|2|0|Unid. Med.|Unidade de Medida
TF0|14|TF0_PESOBA|N|9|2|Peso Balan|Peso Balança
TF0|15|TF0_UNIBAL|C|1|0|Unid. Balan.|Unidade da Balança
TF0|16|TF0_STATUS|C|1|0|Status|Status
TF0|17|TF0_ORIGEM|C|3|0|Origem|Origem
TF0|18|TF0_DESORI|C|20|0|Desc. Orig.|Descrição da Origem
TF0|19|TF0_PROCED|C|3|0|Procedência.|Procedência.
TF0|20|TF0_DESPRO|C|20|0|Desc. Proc.|Descrição da Procedência
TF0|21|TF0_CODTRA|C|3|0|Tratamento|Tratamento
TF0|22|TF0_DESTRA|C|20|0|Desc. Trat.|Descrição do Tratamento
TF0|23|TF0_CODTIP|C|6|0|Cód. Tipo|Cód. Tipo
TF0|24|TF0_DESTIP|C|30|0|Descrição|Descrição
TF0|25|TF0_EMPGER|C|2|0|Emp. Gerad.|Empresa Geradora
TF0|26|TF0_FILGER|C|6|0|Fil. Gerad.|Filial Geradora
TF0|27|TF0_LICGER|C|12|0|Nr. Licença|Nr. Licença
TF0|28|TF0_RESPEX|C|10|0|Resp. Exped.|Responsável Expedição
TF0|29|TF0_DTEGE|D|8|0|Data Entrega|Data Entrega
TF0|30|TF0_CDTRAN|C|6|0|Transport.|Código do Transportador
TF0|31|TF0_NOMTRA|C|40|0|Razão|Razão Social Transport.
TF0|32|TF0_RESPTR|C|40|0|Resp. Transp|Responsável pela Empresa
TF0|33|TF0_CODMOT|C|6|0|Condutor|Código do Condutor
TF0|34|TF0_DTRTRA|D|8|0|Data Receb.|Data Receb.
TF0|35|TF0_FORREC|C|6|0|Documento Mo|Documento Movimen.
TF0|36|TF0_LOJREC|C|2|0|Loja|Loja
TF0|37|TF0_NOMREC|C|80|0|Razão Social|Razão Social da Indústria
TF0|38|TF0_ENDREC|C|40|0|Morada/nº|Morada/número
TF0|39|TF0_CIDREC|C|15|0|Concelho|Município
TF0|40|TF0_ESTREC|C|2|0|Distrito|Unidade Federativa
TF0|41|TF0_TELREC|C|18|0|Telefone|Telefone
TF0|42|TF0_LICREC|C|12|0|Nr. Licença|Nr. Licença
TF0|43|TF0_RESPRE|C|40|0|Resp. Receb.|Responsável Recebimento
TF0|44|TF0_CARGRR|C|40|0|Cargo|Cargo Responsável Recebim
TF0|45|TF0_DTEREC|D|8|0|Data Entrega|Data Entrega
TF0|46|TF0_CONPAG|C|15|0|Cond. Pagto.|Condição de Pagamento
TF0|47|TF0_TES|C|15|0|Tipo Saída|Tipo de Saída do Item
TF0|48|TF0_NUM|C|15|0|Nr. Pedido|Número do Pedido Venda
TF0|49|TF0_PREVEN|N|15|2|Preço Venda|Preço de Venda
TF0|50|TF0_DTALTE|D|8|0|Data Alter.|Data Alter.
TF0|51|TF0_HRALTE|C|5|0|Hora Alter.|Hora Alter.
TF0|52|TF0_TPDEST|C|1|0|Tp. Destin.|Tipo Destinatário
TF0|53|TF0_FORNNF|C|6|0|Dest. Fact.|Destinatário da Factura
TF0|54|TF0_LOJANF|C|2|0|Loja. Dest.|Loja Destinat. da Fact.
TF0|55|TF0_NOMDES|C|40|0|Razão Social|Razão Social da Indústria
TF0|56|TF0_MENPAD|C|15|0|Mens. Padrão|Mensagem Padrão
TF0|57|TF0_ESPEC1|C|15|0|Espécie 1|Espécie do Volume tipo 1
TF0|58|TF0_PESOL|N|15|0|Peso Líquido|Peso Líquido
TF0|59|TF0_PBRUTO|N|15|0|Peso Bruto|Peso Bruto
TF0|60|TF0_VOLUM1|N|5|0|Volume 1|Qtd. de Volumes tipo 1
--- ### TF1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF1|01|TF1_FILIAL|C|6|0|Filial|Filial do Sistema
TF1|02|TF1_CODRES|C|15|0|Resíduo|Resíduo
TF1|03|TF1_CODPOL|C|6|0|Poluente|Poluente
TF1|04|TF1_DESPOL|C|30|0|Descrição|Descrição
TF1|05|TF1_DATA|D|8|0|Data|Data
TF1|06|TF1_COEFIC|N|8|3|Coeficiente|Coeficiente
TF1|07|TF1_UNIDAD|C|2|0|Unidade Med.|Unidade Med.
TF1|08|TF1_METODO|C|1|0|Método Afer.|Método Afer.
TF1|09|TF1_IDMETO|C|12|0|Iden. Método|Iden. Método
TF1|10|TF1_CONSIG|C|1|0|Sigilo|Sigilo
TF1|11|TF1_JUSSIG|M|10|0|Justif. Sig.|Justif. Sig.
--- ### TF2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF2|01|TF2_FILIAL|C|6|0|Filial|Filial do Sistema
TF2|02|TF2_CODRES|C|15|0|Resíduo|Resíduo
TF2|03|TF2_ANO|C|4|0|Ano|Ano
TF2|04|TF2_EFICIE|N|3|0|Efic. Trata.|Efic. Trata.
TF2|05|TF2_TIPMON|C|100|0|Tipo Monit.|Tipo Monit.
--- ### TF3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF3|01|TF3_FILIAL|C|6|0|Filial|Filial do Sistema
TF3|02|TF3_CODCOM|C|6|0|Cód.Composi.|Cód.Composi.
TF3|03|TF3_CODFMR|C|6|0|Cód. FMR|Código da FMR
--- ### TF4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF4|01|TF4_FILIAL|C|6|0|Filial|Filial do Sistema
TF4|02|TF4_CODCOM|C|6|0|Cód.Composi.|Cód.Composi.
TF4|03|TF4_TIPVEI|C|1|0|Tipo Veículo|Tipo Veículo
TF4|04|TF4_PLACA|C|8|0|Placa|Placa do Veículo
TF4|05|TF4_NOMVEI|C|30|0|Nome Veículo|Nome Veículo
--- ### TF5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF5|01|TF5_FILIAL|C|6|0|Filial|Filial do Sistema
TF5|02|TF5_CODFMR|C|6|0|Cód. FMR|Código da FMR
TF5|03|TF5_DATA|D|8|0|Data|Data da FMR
TF5|04|TF5_DEPTO|C|6|0|Departamento|Departamento da FMR
TF5|05|TF5_DESDEP|C|30|0|Desc. Depto.|Desc. do Departamento
TF5|06|TF5_CODPNT|C|6|0|Ponto Coleta|Código do Ponto
TF5|07|TF5_DESCRI|C|30|0|Desc. Ponto|Desc. do Ponto
TF5|08|TF5_CODRES|C|15|0|Resíduo|Código do Resíduo
TF5|09|TF5_DESCRE|C|70|0|Desc. Resid.|Desc. de Residuo
TF5|10|TF5_RESPON|C|15|0|Responsável|Responsável pela FMR"
TF5|11|TF5_NOMRES|C|30|0|Nome Resp.|Nome do Responsável
TF5|12|TF5_ORDPRO|C|6|0|Ord. Produçã|Ordem de Produção
TF5|13|TF5_OBSERV|M|10|0|Observação|Observação
TF5|14|TF5_STATUS|C|1|0|Status|Status da FMR
TF5|15|TF5_LIBRES|C|1|0|Lib. Restric|Lib. C/ Restrições?
TF5|16|TF5_DESCNC|M|10|0|Descrição NC|Desc. Não Conformidade
TF5|17|TF5_FNC|C|10|0|Cód. FNC|Código FNC
TF5|18|TF5_CODOCO|C|6|0|Ocorrência|Código Ocorrência
--- ### TF6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF6|01|TF6_FILIAL|C|6|0|Filial|Filial do Sistema
TF6|02|TF6_CODFMR|C|6|0|Cód. FMR|Código da FMR
TF6|03|TF6_MAT|C|15|0|Utilizador|Código do Utilizador
TF6|04|TF6_NOME|C|30|0|Nome Utiliza|Nome do Utilizador
--- ### TF7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF7|01|TF7_FILIAL|C|6|0|Filial|Filial do Sistema
TF7|02|TF7_DEPTO|C|3|0|Departamento|Departamento
TF7|03|TF7_CODIGO|C|6|0|Código|Código do Ponto
TF7|04|TF7_DESCRI|C|40|0|Descrição|Descrição do Ponto
TF7|05|TF7_BITMAP|C|8|0|Imagem| Imagem do Ponto
--- ### TF8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF8|01|TF8_FILIAL|C|6|0|Filial|Filial do Sistema
TF8|02|TF8_CODFMR|C|6|0|Cód. da FMR|Código da FMR
TF8|03|TF8_SEQUEN|C|3|0|Sequência|Sequência
TF8|04|TF8_ACONDI|C|6|0|Acondicionam|Acondicionamento
TF8|05|TF8_DESCAC|C|30|0|Desc. Acond.|Desc. Acondicionamento
TF8|06|TF8_COLET|C|15|0|Coletor|Coletor
TF8|07|TF8_DESCCO|C|70|0|Desc Coletor|Descrição Coletor
TF8|08|TF8_UNICOL|C|2|0|Unid Coletor|Unidade do Coletor
TF8|09|TF8_PESO|N|9|2|Peso|Peso do Resíduo
TF8|10|TF8_UNIRES|C|2|0|Un. Resíduo|Unidade do Resíduo
TF8|11|TF8_ORIGEM|C|1|0|Origem|Origem Coletor
--- ### TF9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TF9|01|TF9_FILIAL|C|6|0|Filial|Filial do Sistema
TF9|02|TF9_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TF9|03|TF9_DTALT|D|8|0|Data Alter.|Data da Alteração
TF9|04|TF9_HRALT|C|8|0|Hora Alter.|Hora da Alteração
TF9|05|TF9_DATA|D|8|0|Data|Data da FMR
TF9|06|TF9_DEPTO|C|3|0|Departamento|Departamento da FMR
TF9|07|TF9_DESDEP|C|30|0|Desc. Depto.|Desc. do Departamento
TF9|08|TF9_CODPNT|C|6|0|Ponto Coleta|Código do Ponto
TF9|09|TF9_DESCRI|C|30|0|Desc. Ponto|Desc. Ponto
TF9|10|TF9_CODRES|C|15|0|Resíduo|Código do Resíduo
TF9|11|TF9_DESCRE|C|70|0|Desc. Resid.|Desc. de Residuo
TF9|12|TF9_RESPON|C|15|0|Responsável|Responsável pela FMR
TF9|13|TF9_NOMRES|C|30|0|Nome Resp.|Nome do Responsável
TF9|14|TF9_ORDPRO|C|15|0|Ordem Prod.|Ordem de Produção
TF9|15|TF9_OBSERV|M|10|0|Observação|Observação
TF9|16|TF9_STATUS|C|1|0|Estado|Estado da FMR
TF9|17|TF9_LIBRES|C|1|0|Lib. Restric|Lib. C/ Restrições?
TF9|18|TF9_DESCNC|M|10|0|Descrição NC|Desc. Não Conformidade
TF9|19|TF9_USUALT|C|15|0|Utilizador A|Utilizador da Alteração
TF9|20|TF9_NOMUSU|C|30|0|Nome Utiliza|Nome Utilizador Alteração
TF9|21|TF9_FNC|C|15|0|Cód. FNC|Código FNC
TF9|22|TF9_CODOCO|C|6|0|Ocorrência|Código Ocorrência
--- ### TFA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFA|01|TFA_FILIAL|C|6|0|Filial|Filial do Sistema
TFA|02|TFA_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TFA|03|TFA_DTALT|D|8|0|Dt Alteração|Data da Alteração
TFA|04|TFA_HRALT|C|8|0|Hr Alteração|Hora da Alteração
TFA|05|TFA_SEQUEN|C|3|0|Sequência|Sequência
TFA|06|TFA_ACONDI|C|6|0|Acondicion.|Acondicionamento
TFA|07|TFA_DESCAC|C|30|0|Desc. Acond.|Desc. Acondicionamento
TFA|08|TFA_COLET|C|15|0|Coletor|Código Coletor
TFA|09|TFA_DESCCO|C|70|0|Desc Coletor|Descrição Coletor
TFA|10|TFA_UNICOL|C|2|0|Unid Coletor|Unidade do Coletor
TFA|11|TFA_PESO|N|9|2|Peso|Peso do Resíduo
TFA|12|TFA_UNIRES|C|2|0|Unid Resíduo|Unidade do Resíduo
TFA|13|TFA_ORIGEM|C|1|0|Origem|Origem
--- ### TFB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFB|01|TFB_FILIAL|C|6|0|Filial|Filial do Sistema
TFB|02|TFB_CODFMR|C|6|0|Cod. FMR|Codigo da FMR
TFB|03|TFB_DTALT|D|8|0|Data Alter.|Data da Alteração
TFB|04|TFB_HRALT|C|8|0|Hora Alter.|Hora da Alteração
TFB|05|TFB_MAT|C|15|0|Utilizador|Código do Utilizador
TFB|06|TFB_NOME|C|30|0|Nome Utiliz.|Nome Utilizador
--- ### TFC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFC|01|TFC_FILIAL|C|6|0|Filial|Filial do Sistema
TFC|02|TFC_CODIBA|C|10|0|Item|Item
TFC|03|TFC_IBAMA|C|10|0|Cód. Ibama|Código do Ibama
TFC|04|TFC_DESCRI|C|150|0|Nome IBAMA|Nome do Código IBAMA
--- ### TFD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFD|01|TFD_FILIAL|C|6|0|Filial|Filial do Sistema
TFD|02|TFD_PLACA|C|8|0|Placa|Placa do Caminhão
TFD|03|TFD_CAVALO|C|20|0|Cavalo|Código do Cavalo.
TFD|04|TFD_NOMCAV|C|40|0|Descrição|Descrição do Cavalo
TFD|05|TFD_TRANSP|C|6|0|Transport.|Código do Transportadora
TFD|06|TFD_NOMTRA|C|40|0|Razão|Razão Social Transport.
TFD|07|TFD_CODLAM|C|12|0|Licença|Código Licença Ambiental
TFD|08|TFD_DATAVA|D|8|0|Dt. Validade|Data da Validade
TFD|09|TFD_DESLAM|C|80|0|Descrição|Desc. Licença Ambiental
TFD|10|TFD_CRLV|C|12|0|CRLV|Código CRLV
TFD|11|TFD_DTCRLV|D|8|0|Dt. Validade|Data da Validade
TFD|12|TFD_CIPP|C|12|0|CIPP|Código CIPP
TFD|13|TFD_DTCIPP|D|8|0|Dt. Validade|Data da Validade
TFD|14|TFD_STATUS|C|1|0|Estado|Status do Cavalo
TFD|15|TFD_MOTIVO|M|10|0|Motivo Inat.|Motivo da Inatividade
--- ### TFE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TFE|01|TFE_FILIAL|C|6|0|Filial|Filial do Sistema
TFE|02|TFE_PLACA|C|8|0|Placa|Placa do Caminhão
TFE|03|TFE_CARRET|C|20|0|Carreta|Código da Carreta
TFE|04|TFE_NOMCAR|C|40|0|Descrição|Descrição da Carreta
TFE|05|TFE_TRANSP|C|6|0|Transport.|Código do Transportadora
TFE|06|TFE_NOMTRA|C|40|0|Razão|Razão Social Transport.
TFE|07|TFE_CODLAM|C|12|0|Licença|Código Licença Ambiental
TFE|08|TFE_DATAVA|D|8|0|Dt. Validade|Data da Validade
TFE|09|TFE_DESLAM|C|80|0|Descrição|Desc. Licença Ambiental
TFE|10|TFE_CRLV|C|12|0|CRLV|Código CRLV
TFE|11|TFE_DTCRLV|D|8|0|Dt. Validade|Data da Validade
TFE|12|TFE_CIPP|C|12|0|CIPP|Código CIPP
TFE|13|TFE_DTCIPP|D|8|0|Dt. Validade|Data da Validade
TFE|14|TFE_STATUS|C|1|0|Status|Status da Carreta
TFE|15|TFE_MOTIVO|M|10|0|Motivo Inat.|Motivo da Inatividade
--- ### TH0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TH0|01|TH0_FILIAL|C|6|0|Filial|Filial do Sistema
TH0|02|TH0_CODRES|C|15|0|Resíduo|Resíduo
TH0|03|TH0_DESTIN|C|6|0|Destino|Destino do Sistema
TH0|04|TH0_DESCRI|C|40|0|Descrição|Descrição
--- ### TH1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TH1|01|TH1_FILIAL|C|6|0|Filial|Filial do Sistema
TH1|02|TH1_CODROT|C|6|0|Rota|Código Rota
TH1|03|TH1_DESROT|C|30|0|Desc. Rota|Descrição da Rota
TH1|04|TH1_RESPON|C|16|0|Elaborador|Elaborador da Rota
TH1|05|TH1_NOMRES|C|30|0|Nome|Nome do Elaborador
TH1|06|TH1_PRDCD|C|1|0|Periodicid.|Periodicidade da Rota
TH1|07|TH1_NTEMPO|N|4|0|Tempo|Tempo da Rota
TH1|08|TH1_OBSERV|M|10|0|Observação|Observação da Rota
TH1|09|TH1_DATELA|D|8|0|Dt. Elab|Data Elaboração
--- ### TH2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TH2|01|TH2_FILIAL|C|6|0|Filial|Filial do Sistema
TH2|02|TH2_CODROT|C|6|0|Código Rota|Código Rota
TH2|03|TH2_CODORD|C|3|0|Ordem|Sequência de ordenação
TH2|04|TH2_CODLOC|C|6|0|Localização|Descrição do Código Local
TH2|05|TH2_DESLOC|C|56|0|Descrição|Descrição da Localização
TH2|06|TH2_CODPTO|C|6|0|Pto. Coleta.|Código do Ponto de Coleta
TH2|07|TH2_DESPTO|C|40|0|Descrição|Descrição Pontos Coleta
--- ### TH3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TH3|01|TH3_FILIAL|C|6|0|Filial|Filial do Sistema
TH3|02|TH3_CODCOM|C|6|0|Codigo|Código Disposição
TH3|03|TH3_DTCOMP|D|8|0|Data|Data Composição
TH3|04|TH3_HRCOMP|C|5|0|Hora|Hora Composição
TH3|05|TH3_ORIGEM|C|3|0|Origem|Origem
TH3|06|TH3_DESORI|C|30|0|Descr. Orig.|Descrição da Origem
TH3|07|TH3_PROCED|C|3|0|Procedência|Procedência
TH3|08|TH3_DESPRO|C|30|0|Descr. Proc.|Descrição da Procedência
TH3|09|TH3_CODTRA|C|3|0|Tratamento|Tratamento
TH3|10|TH3_DESTRA|C|30|0|Descr. Trat.|Descrição do Tratamento
TH3|11|TH3_TIPDES|C|1|0|Tipo|Tipo de Destinação
TH3|12|TH3_CODTIP|C|6|0|Cod. Tipo|Cod. Tipo de Destinação
TH3|13|TH3_DOC|C|9|0|Documento|Documento Moviment.
--- ### TH4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TH4|01|TH4_FILIAL|C|6|0|Filial|Filial do Sistema
TH4|02|TH4_CODCOM|C|6|0|Disposição|Código Disposição
TH4|03|TH4_CODOCO|C|6|0|Ocorrência|Código Ocorrência
TH4|04|TH4_PESOUT|N|9|2|Peso Util.|Peso Utilizado
TH4|05|TH4_UNIMED|C|6|0|Unid. Medida|Unidade de Medida
--- ### TIQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIQ|01|TIQ_FILIAL|C|6|0|Filial|Filial do Sistema
TIQ|02|TIQ_TIPO|C|1|0|Tipo|Tipo de Disciplina
TIQ|03|TIQ_CODIGO|C|6|0|Codigo|Codigo da Disciplina
TIQ|04|TIQ_DESCR|C|50|0|Descrição|Descrição da Disciplina
TIQ|05|TIQ_TEXTO1|M|10|0|Cabeçalho|Texto 1 para Disciplina
TIQ|06|TIQ_TEXTO2|M|10|0|Complemento|Texto 2 para Disciplina
--- ### TIR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIR|01|TIR_FILIAL|C|6|0|Filial|Filial do Sistema
TIR|02|TIR_CODIGO|C|6|0|Codigo|Codigo da tabela
TIR|03|TIR_CODTIQ|C|6|0|Cod.Discipl.|Codigo da tabela TIQ
TIR|04|TIR_QTD|N|2|0|Quantidade|Quantidade de Disciplia
TIR|05|TIR_SUGERI|C|1|0|Sugere|Sugere Disciplina
TIR|06|TIR_SUGEST|C|6|0|Disciplina|Pesq. Disciplina Sugerida
TIR|07|TIR_DESCRI|C|50|0|Descrição|Descr. Disciplina Sugerid
TIR|08|TIR_PPERDA|N|6|2|%Perda PLR|Perc. Perda PLR
TIR|09|TIR_PONTO|N|3|0|Pontução|Pontuação a Receber
--- ### TIS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIS|01|TIS_FILIAL|C|6|0|Filial|Filial do Sistema
TIS|02|TIS_TIPO|C|1|0|Tipo|Tipo da Disciplina
TIS|03|TIS_CODIGO|C|6|0|Código|Código Automático
TIS|04|TIS_DESCRI|C|50|0|Descrição|Descrição Tipo Disciplina
--- ### TIT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIT|01|TIT_FILIAL|C|6|0|Filial|Filial do Sistema
TIT|02|TIT_CODIGO|C|6|0|Código|Código da Disciplina
TIT|03|TIT_TIPO|C|1|0|Tipo|Tipo da Disciplina
TIT|04|TIT_CODTIQ|C|6|0|Disciplina|Código da Disciplina
TIT|05|TIT_DISCIP|C|50|0|Descrição|Descrição da Disciplina
TIT|06|TIT_DATA|D|8|0|Data Disc.|Data aplicação Disciplina
TIT|07|TIT_HORA|C|5|0|Hora Disc.|Hora aplicação Disciplina
TIT|08|TIT_CODTIS|C|6|0|Motivo|Codigo Motivo Disciplina
TIT|09|TIT_MOTIVO|C|50|0|Descr.Mot.|Descricao Motivo
TIT|10|TIT_CODTEC|C|14|0|Cod.Atend.|Código do Atendente
TIT|11|TIT_NOMTEC|C|50|0|Nome Atend.|Nome do Atendente
TIT|12|TIT_TURNO|C|3|0|Turno|Turno do Atendente
TIT|13|TIT_CODABS|C|8|0|Local|Local de Atendimento
TIT|14|TIT_LOCAL|C|50|0|Descrição|Descrição do Local Atendi
TIT|15|TIT_REGIAO|C|3|0|Região|Descrição da Região
TIT|16|TIT_CODRES|C|14|0|Cod.Resp.|Código do Responsável
TIT|17|TIT_RESPON|C|50|0|Responsável|Nome do Responsável
TIT|18|TIT_AFASTA|C|1|0|Afastamento|Afastamento
TIT|19|TIT_QTDDIA|N|2|0|Dias Afast.|Quantidade Dias Afastam.
TIT|20|TIT_APLICA|C|1|0|Local Disc.|Local Aplic. Disciplina
TIT|21|TIT_TEXTO1|M|10|0|Texto 1|Texto 1 corpo do relat.
TIT|22|TIT_DESCRI|M|10|0|Descr.Discip|Desc. da Disciplina
TIT|23|TIT_TEXTO2|M|10|0|Texto 2|Texto 2 corpo do relat.
TIT|24|TIT_PONTOS|N|3|0|Pontuacao|Pontuacao Disciplinar
TIT|25|TIT_PLR|N|3|0|% Perda PLR|% Perda na PLR
TIT|26|TIT_USUARI|C|20|0|Usuário|Usuário Cadastro
TIT|27|TIT_MAT|C|6|0|Matrícula|Matrícula do Funcionário
TIT|28|TIT_NOMFUN|C|30|0|Nome Func.|Nome do Funcionário
TIT|29|TIT_MATRES|C|6|0|Mat.Resp.|Matrícula do Responsável
TIT|30|TIT_NOMRSF|C|30|0|Nome Fun.Res|Nome Funcion.Responsável
TIT|31|TIT_RCMSUS|C|3|0|Tp.Ausência|Tipo de Ausência
TIT|32|TIT_CODTIV|C|6|0|Código TIV|Importar código TIV
--- ### TIU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIU|01|TIU_FILIAL|C|6|0|Filial|Filial do Sistema
TIU|02|TIU_CODTIT|C|6|0|Cod.Discip|Código da Disciplina
TIU|03|TIU_CODIGO|C|6|0|Código|Cod Processo Disciplinar
TIU|04|TIU_RELACI|C|1|0|Processo|Relacionar Processos
TIU|05|TIU_OCORR|C|6|0|Cod.Ocorrenc|Relacionar Ocorrência
TIU|06|TIU_INVEST|C|6|0|Cod.Ivestiga|Relacionar Investigação
TIU|07|TIU_DESCRI|C|30|0|Descricao|Descrição Processo
TIU|08|TIU_DATA|D|8|0|Data Proc.|Data do Processo
TIU|09|TIU_HORA|C|5|0|Hora Proc.|Hora do Processo relac
TIU|10|TIU_LOCAL|C|40|0|Local Proc.|Local do Processo
--- ### TIV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TIV|01|TIV_FILIAL|C|6|0|Filial|Filial do Sistema
TIV|02|TIV_CODIGO|C|6|0|Código|Código Pontuação Mérito
TIV|03|TIV_CODTIQ|C|6|0|Disciplina|Código da Disciplina
TIV|04|TIV_DISCIP|C|50|0|Descrição|Descrição da Disciplina
TIV|05|TIV_CODTIS|C|6|0|Motivo|Código Motivo Disciplina
TIV|06|TIV_MOTIVO|C|50|0|Descrição|Descrição do Motivo
TIV|07|TIV_DESCRI|C|50|0|Descrição|Descrição da Pontuação
TIV|08|TIV_PONTOS|N|3|0|Qtd.Pontos|Qtd. de Pontos Atribuídos
TIV|09|TIV_ADMITI|D|8|0|Admissao Ate|Admitidos Até a Data
--- ### T00
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T00|01|T00_FILIAL|C|6|0|Filial|Filial
T00|02|T00_CHVNF|C|36|0|Cód. Documen|Cód. Documento Fiscal
T00|03|T00_IDSUBI|C|36|0|ID. Subitem|Identificador do Subitem
T00|04|T00_VALOR|N|16|2|Val. Cred.|Valor Crédito Acumulado
T00|05|T00_CODIGO|C|12|0|Cod. Autorz.|Código de Autorização
T00|06|T00_ID|C|36|0|ID|Identificador do Registro
--- ### T01
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T01|01|T01_FILIAL|C|6|0|Filial|Filial
T01|02|T01_CODFIL|C|6|0|Filial|Filial
T01|03|T01_ALIAS|C|3|0|Alias|Alias tabela TAF
T01|04|T01_REGKEY|C|228|0|Chave Reg.|Chave do registro
T01|05|T01_MSGERR|M|255|0|Msg. Erro|Mensagem de erro
T01|06|T01_DATA|D|8|0|Data erro|Data de ocorrencia
T01|07|T01_HORA|C|8|0|Hora|Hora de ocorrencia
T01|08|T01_ALSERP|C|3|0|Alias ERP|Alias da tabela do ERP
T01|09|T01_ERPKEY|C|228|0|Chave Reg.|Chave de registro do ERP
--- ### T02
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T02|01|T02_FILIAL|C|6|0|Filial|Filial
T02|02|T02_ID|C|6|0|ID|Identificador do Registro
T02|03|T02_CODAJU|C|10|0|Cod. Ajuste|Código do Ajuste
T02|04|T02_IDSUBI|C|36|0|ID. Subitem|Identificador do Subitem
T02|05|T02_IDTMOT|C|36|0|Id. Tipo Mot|Id. Tipo do Motivo
T02|06|T02_VALOR|N|16|2|Vl.Cred.Icms|Valor Credito ICMS Acum.
T02|07|T02_SEQREG|N|4|0|Seq Registro|Sequência do Registro
T02|08|T02_CODIGO|C|12|0|Cód.Autoriz|Código da Autorização
--- ### T03
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T03|01|T03_FILIAL|C|6|0|Filial|Filial
T03|02|T03_ID|C|6|0|ID|Identificador do registro
T03|03|T03_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T03|04|T03_FPAS|C|6|0|Id. Cód Terc|Código Terceiro
T03|05|T03_CODTER|C|4|0|Desc Cod Ter|Desc. de Código Terceiro
T03|06|T03_IDPROC|C|6|0|ID Processo|ID Processo
T03|07|T03_DNRPRO|C|21|0|Num. Proc|Numero do Processo
T03|08|T03_CODSUS|C|14|0|Cod Susp|Cod Indic Supensao
T03|09|T03_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
--- ### T04
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T04|01|T04_FILIAL|C|6|0|Filial|Filial
T04|02|T04_ID|C|6|0|ID|Identificador do registro
T04|03|T04_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T04|04|T04_CODIGO|C|30|0|Cod Amb Trab|Código do Ambiente de Tra
T04|05|T04_DTINI|C|6|0|Per Ini Vld|Período Inicial Validade
T04|06|T04_DTFIN|C|6|0|Per. Fim Vld|Período Final Validade
T04|07|T04_NMAMB|C|100|0|Nome Amb.|Nome do Ambiente
T04|08|T04_DESCRI|M|10|0|Des Amb Trab|Desc Ambiente de Trabalho
T04|09|T04_LOCAMB|C|1|0|Local Amb|Local Ambiente de Trabalh
T04|10|T04_TPINSC|C|1|0|Tp.Inscrição|Tp. Inscrição do Ambiente
T04|11|T04_NRINSC|C|15|0|Nr.Insc.|Nr. Inscrição do Ambiente
T04|12|T04_LOTACA|C|6|0|Cod. Lotação|Código da Lotação
T04|13|T04_VERANT|C|14|0|Id. Ver. Ant|Id versão anterior reg.
T04|14|T04_STATUS|C|1|0|Status Reg.|Status do registro
T04|15|T04_PROTUL|C|44|0|Nº do Recibo|Número do Recibo
T04|16|T04_PROTPN|C|44|0|Nº Recibo A|Número do Recibo Anterior
T04|17|T04_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T04|18|T04_LOGOPE|C|1|0|Log Operacao|Log Operacao
T04|19|T04_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T04|20|T04_XMLID|C|36|0|Id do XML.|Id do XML.
--- ### T05
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T05|01|T05_FILIAL|C|6|0|Filial|Filial
T05|02|T05_ID|C|6|0|ID|Identificador do Registro
T05|03|T05_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T05|04|T05_CODRUB|C|6|0|Cód Rubrica|Código de Rúbrica
T05|05|T05_DCODRU|C|220|0|Desc Cod Rub|Descrição Código Rúbrica
T05|06|T05_QTDRUB|N|7|2|Qtd. Rubr|Quantidade de Rúbrica
T05|07|T05_FATRUB|N|6|2|Fator Rubric|Fator de Rubrica
T05|08|T05_VLRUNI|N|15|2|Vlr Unit Rub|Valor Unitário da Rubrica
T05|09|T05_VLRRUB|N|15|2|Vlr Rubrica|Valor Total da Rubrica
T05|10|T05_LOTTRB|C|6|0|Lot.Tribut|Lotação Tributária
T05|11|T05_RECPAG|C|30|0|Rec. Pagamen|Recibo de Pagamento
T05|12|T05_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T05|13|T05_NRINSC|C|15|0|Nr Inscrição|Numero de Inscrição
T05|14|T05_ESTABE|C|6|0|Id Estab Lot|Ident Estabelecimento Lot
T05|15|T05_SEQUEN|C|3|0|Sequencia|Sequencia
T05|16|T05_SQTDRB|N|13|2|Qtd. Rubr|Quantidade de Rúbrica
T05|17|T05_APURIR|C|1|0|Tp.Apur.IR|Tipo Apuração IR
T05|18|T05_TPDESC|C|1|0|Tipo Descont|Indicativo doTp de Descon
T05|19|T05_INTFIN|C|6|0|Inst.Fin.|Instituição Financeira
T05|20|T05_DINTFI|C|3|0|Cód. Institu|Cód. Instituição Financei
T05|21|T05_NRDOC|C|15|0|Nr. Contrato|Nr. Contrato Emprestimo
T05|22|T05_OBSERV|C|254|0|Info. Descon|Info. Desconto
--- ### T06
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T06|01|T06_FILIAL|C|6|0|Filial|Filial
T06|02|T06_ID|C|6|0|ID|Identificador do Registro
T06|03|T06_IDEDMD|C|30|0|Ident Dem Va|Ident Dem Valor
T06|04|T06_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T06|05|T06_INDRRA|C|1|0|Ind. Ren RRA|Ind. Redimentos RRA
T06|06|T06_TPPRRA|C|1|0|Tp. Proc RRA|Tp. Processo RRA
T06|07|T06_NRPRRA|C|21|0|Nr Proc. RRA|Nr. Processo RRA
T06|08|T06_DESCRA|C|50|0|Des. Ren RRA|Desc. Rendimentos RRA
T06|09|T06_QTMRRA|N|5|1|Qt. Mes. RRA|Qtd. Meses RRA
T06|10|T06_VLRCUS|N|15|2|Vl. Desp. Ju|Vlr. Despesas Judiciais
T06|11|T06_VLRADV|N|15|2|Vl. Des. Adv|Vlr. Despesas Advogados
T06|12|T06_NOTAFT|C|9|0|Número FGTS|Número notificação FGTS
--- ### T07
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T07|01|T07_FILIAL|C|6|0|Filial|Filial
T07|02|T07_ID|C|6|0|ID|Identificador do Registro
T07|03|T07_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T07|04|T07_PBALVO|C|1|0|Tp Publ Alvo|Tipo de Público Alvo
T07|05|T07_SEGDIF|C|50|0|Seg Diferenc|Descrição Segur Diferenc
T07|06|T07_ALQSEG|N|5|2|Aliq Seg Ben|Aliq Contrib Segur/Benef
T07|07|T07_ALQNOR|N|5|2|Aliq Ctb Nor|Aliq Contribuição Normal
T07|08|T07_ALQSUP|N|5|2|Aliq Ent Fed|Aliq Contrib Ente Federat
--- ### T08
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T08|01|T08_FILIAL|C|6|0|Filial|Filial
T08|02|T08_ID|C|6|0|ID|Identificador do Registro
T08|03|T08_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T08|04|T08_SUBTET|C|1|0|Ident Subtet|Ident Poder Subteto
T08|05|T08_VALSUB|N|14|2|Val Subteto|Valor do Subteto
T08|06|T08_IDMAI|N|2|0|Idade Maior|Idade Maior
--- ### T09
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T09|01|T09_FILIAL|C|6|0|Filial|Filial
T09|02|T09_ID|C|6|0|ID|Identificador do registro
T09|03|T09_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T09|04|T09_FATRIS|C|10|0|Cod. Fat. Ri|Código do Fator de Risco
T09|05|T09_DFATRI|C|220|0|Des Fat Ris|Descrição Fator de Risco
T09|06|T09_UTIEPC|C|1|0|Utiliz.EPC|Utilização de EPC
--- ### T0A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0A|01|T0A_FILIAL|C|6|0|Filial|Filial
T0A|02|T0A_ID|C|6|0|ID|Identificador do registro
T0A|03|T0A_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0A|04|T0A_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T0A|05|T0A_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T0A|06|T0A_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T0A|07|T0A_CNPJOP|C|14|0|CNPJ Op.Port|CNPJ Operador Portuario
--- ### T0B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0B|01|T0B_FILIAL|C|6|0|Filial|Filial
T0B|02|T0B_ID|C|6|0|ID|Identificador do registro
T0B|03|T0B_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0B|04|T0B_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T0B|05|T0B_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T0B|06|T0B_INDCOM|C|6|0|Indic. Comer|Indic. Comer
T0B|07|T0B_DINDCO|C|220|0|Dsc. Indic.|Desc. Ind Comercialização
T0B|08|T0B_DINDCR|C|220|0|Dsc. Indic.|Desc. Ind Comercializaçao
T0B|09|T0B_VLBCCO|N|16|2|Vlr Bc Co PR|Vlr Bs Cal Com Prod Rural
T0B|10|T0B_VLCPSU|N|16|2|Vlr CP Susp|Valor Cont Prev Susp
T0B|11|T0B_VLRASU|N|16|2|Vlr Rat Susp|Valor Con Gilrat Suspensa
T0B|12|T0B_VLSESU|N|16|2|Vlr Senar Su|Valor Con Senar Susp
T0B|13|T0B_DIDCOM|C|6|0|Ind. Comer.|Indicativo de comercializ
--- ### T0C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0C|01|T0C_FILIAL|C|6|0|Filial|Filial
T0C|02|T0C_ID|C|6|0|ID|Identificador do registro
T0C|03|T0C_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0C|04|T0C_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T0C|05|T0C_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T0C|06|T0C_IDCODR|C|6|0|Id. Cód. Rec|Id. Código da Receita
T0C|07|T0C_DCODRE|C|220|0|Desc Cod Rec|Descrição do Código da Re
T0C|08|T0C_DCODRR|C|220|0|Desc Cod Rec|Descriçao do Código da Re
T0C|09|T0C_VLCOCR|N|16|2|Vlr CR|Valor do CR
T0C|10|T0C_VLSUCR|N|16|2|Vlr Susp CR|Valor Suspenso do CR
T0C|11|T0C_LOTACA|C|6|0|Lotacao Trib|Lotacao Tributaria
T0C|12|T0C_CODLOT|C|30|0|Codigo Lotac|Codigo de Lotacao
T0C|13|T0C_CODLOR|C|30|0|Codigo Lotac|Codigo de Lotacao
T0C|14|T0C_CODREC|C|6|0|Cod Receita|Código da Receita
--- ### T0D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0D|01|T0D_FILIAL|C|6|0|Filial|Filial
T0D|02|T0D_ID|C|6|0|ID|Identificador do registro
T0D|03|T0D_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0D|04|T0D_IDCODR|C|6|0|Id. Cód. Rec|Id. Código da Receita
T0D|05|T0D_DCODRE|C|220|0|Desc Cod Rec|Descrição Código da Rec
T0D|06|T0D_DCODRR|C|220|0|Desc Cod Rec|Descriçao Código da Rec
T0D|07|T0D_VRCOCR|N|16|2|Vlr CR|Valor do Código de Receit
T0D|08|T0D_VRCRSU|N|16|2|Vlr Susp CR|Valor suspenso CR
T0D|09|T0D_CODREC|C|6|0|Cod Receita|Código da Receita
--- ### T0E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0E|01|T0E_FILIAL|C|6|0|Filial|Filial
T0E|02|T0E_ID|C|6|0|ID|Identificador do registro
T0E|03|T0E_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0E|04|T0E_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T0E|05|T0E_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T0E|06|T0E_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T0E|07|T0E_CODTER|C|6|0|Id.Cod.Terc|Código Terceiro
T0E|08|T0E_DTERC|C|30|0|Cod Terceiro|Código Terceiro
T0E|09|T0E_DTERR|C|30|0|Cod Terceiro|Código Terceiro
--- ### T0F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0F|01|T0F_FILIAL|C|6|0|Filial|Filial
T0F|02|T0F_ID|C|6|0|ID|Identificador do Registro
T0F|03|T0F_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T0F|04|T0F_NOME|C|70|0|Nome|Nome do Funcionário
T0F|05|T0F_CPF|C|11|0|CPF|CPF Trabalhador
T0F|06|T0F_DTALT|D|8|0|Dt.Alteração|Data Alteração Contratual
T0F|07|T0F_NATATV|C|1|0|Nat Atividad|Natureza da Atividade
T0F|08|T0F_CARCI|C|6|0|Id. Cargo|Id. Cargo Contrib. Indiv.
T0F|09|T0F_DCARCI|C|220|0|Descr. Cargo|Descr. Cargo Contrib. Ind
T0F|10|T0F_CATAV|C|6|0|Id. Categ.|Id. Categ. Trab. Avulso
T0F|11|T0F_DCATAV|C|220|0|Descr. Categ|Descr. Categ. Trab. Avuls
T0F|12|T0F_VLSLCI|N|16|2|Vlr Sal Fixo|Vlr. Sal. Fixo Contr. Ind
T0F|13|T0F_UNSLCI|C|1|0|Uni Sal Fixo|Unid. Sal. Fixo Contr. In
T0F|14|T0F_DSVRCI|C|254|0|Desc Sal Var|Desc. Sal. Var. Contr. In
T0F|15|T0F_NATEES|C|1|0|Nat. Estágio|Natureza Estagio
T0F|16|T0F_NIVEES|C|1|0|Niv. Estágio|Nivel Estágio
T0F|17|T0F_AREAES|C|100|0|Área Atuação|Área Atuação Estágio
T0F|18|T0F_NRAPES|C|30|0|Nr. Apólice|Número Apólice Seguro
T0F|19|T0F_VLBLES|N|16|2|Vlr. Bolsa|Valor Bolsa
T0F|20|T0F_DTTEES|D|8|0|Dt Prev Térm|Data Prevista Término
T0F|21|T0F_CNPEES|C|14|0|CNPJ Ins Ens|CNPJ Instituição Ensino
T0F|22|T0F_NOMEES|C|100|0|Nome Ins Ens|Nome Instituição Ensino
T0F|23|T0F_LOGEES|C|100|0|Log Inst Ens|Logradouro Inst. Ensino
T0F|24|T0F_NLGEES|C|10|0|Nr Log Inst|Número Lograd. Inst. Ens.
T0F|25|T0F_BAREES|C|90|0|Bairro Inst.|Bairro Instituição Ensino
T0F|26|T0F_CEPES|C|8|0|CEP Ag. Int.|CEP Agente Integração
T0F|27|T0F_UFES|C|6|0|Id. UF Ag.|Id. UF Agente Integração
T0F|28|T0F_DUFES|C|220|0|Des UF Inst.|Descr. UF Inst. Ensino
T0F|29|T0F_MUNES|C|6|0|Id. Mun. Ag.|Id. Mun. Ag. Integração
T0F|30|T0F_DMUNES|C|220|0|Desc Mun Ag|Descr. Mun. Ag. Integ.
T0F|31|T0F_CNPAES|C|14|0|CNPJ Ag. Int|CNPJ Agente Integração
T0F|32|T0F_NOMAES|C|100|0|Nome Ag. Int|Nome Agente Integracao
T0F|33|T0F_LOGAES|C|100|0|Log. Ag. Int|Logradouro Ag. Integração
T0F|34|T0F_NLGAES|C|10|0|Nr. Log. Ag.|Número Log. Agente Integ.
T0F|35|T0F_BARAES|C|90|0|Bairro Ag.|Bairro Agente Integração
T0F|36|T0F_CEPAES|C|8|0|CEP Ag. Int.|CEP Agente Integração
T0F|37|T0F_UFAES|C|6|0|Id. UF Ag.|Id. UF Agente Integração
T0F|38|T0F_DUFAES|C|220|0|Descr. UF Ag|Descr. UF Ag. Integração
T0F|39|T0F_MUNAES|C|6|0|Id. Mun. Ag.|Id. Mun. Ag. Integração
T0F|40|T0F_DMUNAE|C|220|0|Desc Mun Ag|Descr. Mun. Ag. Integ.
T0F|41|T0F_CPFCES|C|11|0|CPF Sup. Est|CPF Supervisor Estágio
T0F|42|T0F_NOMCES|C|70|0|Nome Sup.|Nome Supervisor Estágio
T0F|43|T0F_PROTUL|C|44|0|Ult. Prot.|Prot. Ultima Transmissao
T0F|44|T0F_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penultima Transm.
T0F|45|T0F_STATUS|C|1|0|Status Reg.|Status do Registro
T0F|46|T0F_VERANT|C|14|0|Ver Ant Reg.|Versão Anterior Registro
T0F|47|T0F_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T0F|48|T0F_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T0F|49|T0F_NIS|C|11|0|NIS|NIS
T0F|50|T0F_FUNCI|C|6|0|Id. Função|Id. Funcao Contrib. Ind.
T0F|51|T0F_DFUNCI|C|220|0|Descr Funcao|Descri. Funcao Contr. Ind
T0F|52|T0F_XMLID|C|36|0|Id do XML.|Id do XML
T0F|53|T0F_STASEC|C|1|0|StatusSecund|Status Secundário
T0F|54|T0F_LOGOPE|C|1|0|Log Operacao|Log Operacao
T0F|55|T0F_DINSIS|D|8|0|Dt Inc Sist|Data Inclusão Sistêmica
T0F|56|T0F_DTRANS|D|8|0|Dt. Transm|Data Transmissao
T0F|57|T0F_MATTSV|C|30|0|Matricula|Matricula do Trabalhador
T0F|58|T0F_CBOCAR|C|6|0|CBO Cargo|CBO Cargo
T0F|59|T0F_HTRANS|C|8|0|Hr. Transm|Hora Transmissao
T0F|60|T0F_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T0F|61|T0F_NMCARG|C|100|0|Nome Cargo|Nome Cargo
T0F|62|T0F_CBOFUN|C|6|0|CBO Funcao|CBO Funcao
T0F|63|T0F_HRRECP|C|8|0|Hr. Recept|Hora Receptacao
T0F|64|T0F_NMFUNC|C|100|0|Nome Funcao|Nome da Funcao
T0F|65|T0F_REGPRE|C|1|0|Tipo Reg Pre|Tipo Regime Prev Sindical
T0F|66|T0F_TPREGP|C|1|0|Tp Reg Prev|Tp Regime Previdenciario
T0F|67|T0F_INDREM|C|1|0|Ind. Rem. Cg|Ind. Rem. Cargo
T0F|68|T0F_TPRPRE|C|1|0|Reg. Prev.|Regime Previdenciário
T0F|69|T0F_DSCSAL|M|10|0|Desc.Salario|Descriçao de Salario
T0F|70|T0F_TPLOCT|C|1|0|Tp Inscrição|Tipo de Inscrição
T0F|71|T0F_NRLOCT|C|14|0|Nr Inscrição|Número de Inscrição
T0F|72|T0F_DSLOCT|C|80|0|Desc. Compl.|Descrição Complementar
--- ### T0G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0G|01|T0G_FILIAL|C|6|0|Filial|Filial
T0G|02|T0G_ID|C|6|0|ID|Identificador do registro
T0G|03|T0G_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0G|04|T0G_STATUS|C|1|0|Status Reg.|Status do Registro
T0G|05|T0G_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T0G|06|T0G_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T0G|07|T0G_PERAPU|C|6|0|Per.Apuração|Período Apuração
T0G|08|T0G_NRARQB|C|44|0|Nr. Rec. Arq|Número do Recibo do Arq.
T0G|09|T0G_INDEXI|C|1|0|Ind. Ex. Val|Ind. de Ex. de Valores
T0G|10|T0G_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T0G|11|T0G_LOGOPE|C|1|0|Log Operacao|Log Operacao
T0G|12|T0G_LAYOUT|C|30|0|Layout|Controle de Layout
--- ### T0H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0H|01|T0H_FILIAL|C|6|0|Filial|Filial
T0H|02|T0H_ID|C|6|0|ID|Identificador do Registro
T0H|03|T0H_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0H|04|T0H_IDCODR|C|6|0|Id. Cód. Rec|Id. Código da Receita
T0H|05|T0H_DCODRE|C|220|0|Desc Cod Rec|Descrição do Código da Re
T0H|06|T0H_PERAPU|C|6|0|Per Apuração|Período Apuração
T0H|07|T0H_VRCOCR|N|15|2|Vlr CR|Valor do Código de Receit
T0H|08|T0H_VLCRSU|N|15|2|Vlr Men Susp|Valor exigibilidade suspe
--- ### T0I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0I|01|T0I_FILIAL|C|6|0|Filial|Filial
T0I|02|T0I_ID|C|6|0|ID|Identificador Registro
T0I|03|T0I_CODIGO|C|1|0|Codigo|Cod Info. iden. Reg. CAT
T0I|04|T0I_DESCRI|C|220|0|Descricao|Info. iden. Reg CAT
T0I|05|T0I_VALIDA|C|8|0|Data Vigenc.|Data da vigencia
--- ### T0J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0J|01|T0J_FILIAL|C|6|0|Filial|Filial
T0J|02|T0J_ID|C|36|0|ID|Identificador do Registro
T0J|03|T0J_CODIGO|C|6|0|Código|Código do Tributo
T0J|04|T0J_DESCRI|C|220|0|Descrição|Descrição do Tributo
T0J|05|T0J_TPALIQ|C|1|0|Tipo Alíq.|Tipo da Alíquota
T0J|06|T0J_VLALIQ|N|7|4|Valor Alíq.|Valor da Alíquota
T0J|07|T0J_TPTRIB|C|6|0|Tipo Trib.|Tipo do Tributo
T0J|08|T0J_DTPTRI|C|220|0|Desc Tp Trib|Descrição Tipo do Tributo
T0J|09|T0J_CODREC|C|6|0|Cód. Receita|Cód. Receita Recolhimento
T0J|10|T0J_DCODRE|C|220|0|Desc Cód Rec|Descrição Código Receita
T0J|11|T0J_COMPTB|C|1|0|Comp. Trib.|Competência Tributária
T0J|12|T0J_PERAPU|C|1|0|Per. Apur.|Periodicidade de Apuração
T0J|13|T0J_ALADIR|N|7|4|Alíq Ad IRPJ|Alíquota Adicional IRPJ
T0J|14|T0J_PARCIS|N|16|2|Parc. Isenta|Parcela Isenta Mensal
T0J|15|T0J_PERCAD|N|7|4|Perc. Adição|Percentual Adição Doação
T0J|16|T0J_ALIQL1|N|8|4|Alíq. Pres 1|Alíq. Presunção Lucro 1
T0J|17|T0J_DALIQ1|C|220|0|Desc. Alíq 1|Desc. Alíq. Pres. Lucro 1
T0J|18|T0J_ALIQL2|N|8|4|Alíq. Pres 2|Alíq. Presunção Lucro 2
T0J|19|T0J_DALIQ2|C|220|0|Desc. Alíq 2|Desc. Alíq. Pres. Lucro 2
T0J|20|T0J_ALIQL3|N|8|4|Alíq. Pres 3|Alíq. Presunção Lucro 3
T0J|21|T0J_DALIQ3|C|220|0|Desc. Alíq 3|Desc. Alíq. Pres. Lucro 3
T0J|22|T0J_ALIQL4|N|8|4|Alíq. Pres 4|Alíq. Presunção Lucro 4
T0J|23|T0J_DALIQ4|C|220|0|Desc. Alíq 4|Desc. Alíq. Pres. Lucro 4
--- ### T0K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0K|01|T0K_FILIAL|C|6|0|Filial|Filial
T0K|02|T0K_ID|C|36|0|ID|Identificador do Registro
T0K|03|T0K_CODIGO|C|6|0|Código|Código
T0K|04|T0K_DESCRI|C|100|0|Descrição|Descrição
--- ### T0L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0L|01|T0L_FILIAL|C|6|0|Filial|Filial
T0L|02|T0L_ID|C|36|0|ID|Identificador do Registro
T0L|03|T0L_CODIGO|C|6|0|Código|Código
T0L|04|T0L_DESCRI|C|100|0|Descrição|Descrição
--- ### T0M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0M|01|T0M_FILIAL|C|6|0|Filial|Filial
T0M|02|T0M_ID|C|36|0|ID|Identificador do Registro
T0M|03|T0M_DATA|D|8|0|Data|Data de entrada ou saida
T0M|04|T0M_NUMDOC|C|50|0|Num. Doc.|Número do Documento
T0M|05|T0M_HIST|C|220|0|Histórico|Histórico
T0M|06|T0M_VLENT|N|16|2|Valor Ent.|Valor de entrada
T0M|07|T0M_VLSAI|N|16|2|Valor Sai.|Valor de saída
T0M|08|T0M_SLDFIN|N|16|2|Saldo Final|Saldo Final
T0M|09|T0M_STATUS|C|1|0|Status|Status
--- ### T0N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0N|01|T0N_FILIAL|C|6|0|Filial|Filial
T0N|02|T0N_ID|C|36|0|ID|Identificador do Registro
T0N|03|T0N_CODIGO|C|6|0|Código|Código do Evento
T0N|04|T0N_DESCRI|C|100|0|Descrição|Descrição
T0N|05|T0N_IDFTRI|C|36|0|Id. Tributaç|Id. Tributação
T0N|06|T0N_CODFTR|C|6|0|Cód. Tribut.|Código Tributação
T0N|07|T0N_DFTRIB|C|100|0|Tributação|Desc. Tributação
T0N|08|T0N_IDEVEN|C|36|0|Id. Evento|Id. Evento Ativ. Rural
T0N|09|T0N_CODEVE|C|6|0|Ativ. Rural|Evento Ativ. Rural
T0N|10|T0N_DEVENT|C|100|0|Desc. Evento|Desc. Evento Tributário
T0N|11|T0N_IDTRIB|C|36|0|Id. Tributo|Identificador do Tributo
T0N|12|T0N_COTRIB|C|6|0|Tributo|Tributo
T0N|13|T0N_DTRIBU|C|100|0|Desc. Tribut|Descrição do Tributo
--- ### T0O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0O|01|T0O_FILIAL|C|6|0|Filial|Filial
T0O|02|T0O_ID|C|36|0|ID|Identificador do Registro
T0O|03|T0O_IDGRUP|N|2|0|Grupo Trib.|Id. Grupo Trib.
T0O|04|T0O_SEQITE|C|6|0|Seq. Item|Sequência do Item
T0O|05|T0O_ORIGEM|C|1|0|Origem|Origem
T0O|06|T0O_DESCRI|C|100|0|Descrição|Descrição
T0O|07|T0O_IDECF|C|36|0|Tabela ECF|Id. Tabela ECF
T0O|08|T0O_CODECF|C|10|0|Código ECF|Código ECF
T0O|09|T0O_DTDECF|C|100|0|Desc. ECF|Descrição tabela ECF
T0O|10|T0O_OPERAC|C|1|0|Operação|Operação
T0O|11|T0O_PERDED|N|5|2|% Ded./Comp.|% Dedução/Compensação
T0O|12|T0O_IDLIDC|C|36|0|Id. Ded/Comp|Id. Ded./Comp.
T0O|13|T0O_CODLID|C|6|0|Cód. Limite|Limite dedução/comp.
T0O|14|T0O_DLIMDC|C|100|0|Desc. Limite|Desc. Limite Ded./Comp.
T0O|15|T0O_FILITE|C|40|0|Filial|Filial
T0O|16|T0O_IDCC|C|36|0|Conta Contáb|Conta Contábil
T0O|17|T0O_CODCC|C|60|0|Conta Contáb|Conta Contábil
T0O|18|T0O_DCONTC|C|125|0|Desc. Conta|Desc. Conta Contábil
T0O|19|T0O_TIPOCC|C|1|0|Tipo|Tipo
T0O|20|T0O_IDCUST|C|6|0|Id. C. Custo|Id. Centro de Custo
T0O|21|T0O_DCUSTO|C|123|0|Centro Custo|Desc. Centro de Custo
T0O|22|T0O_EFEITO|C|1|0|Efeito Lalur|Efeito Lalur
T0O|23|T0O_IDEVEN|C|36|0|Evento|Evento
T0O|24|T0O_CODEVE|C|6|0|Evento|Evento
T0O|25|T0O_DEVENT|C|100|0|Desc. Evento|Desc. Evento
T0O|26|T0O_ATIVID|C|1|0|Tipo Ativ.|Tipo de Atividade
T0O|27|T0O_PROUNI|C|1|0|Prouni|Prouni
T0O|28|T0O_PERRED|N|5|2|% de Redução|% de Redução
T0O|29|T0O_IDTDEX|C|36|0|Id.Cód. ECF|Id. Cód. ECF Luc. Explora
T0O|30|T0O_CODTDE|C|10|0|Cód. ECF Luc|Cód. ECF Luc. Exploração
T0O|31|T0O_DTDEXP|C|100|0|Desc. ECF Ex|Descrição tabela ECF Expl
T0O|32|T0O_IDLAL|C|36|0|Tabela Lalur|Id. Tabela Lalur
T0O|33|T0O_CODLAL|C|12|0|Código Lalur|Código Lalur
T0O|34|T0O_DTDLAL|C|100|0|Desc. Lalur|Descrição tabela Lalur
T0O|35|T0O_IDPARB|C|36|0|Id. Parte B|Id. Parte B
T0O|36|T0O_CODPAB|C|60|0|Cód. Parte B|Cód. Conta Parte B
T0O|37|T0O_DPARTB|C|100|0|Des. Parte B|Descrição Conta Parte B
T0O|38|T0O_PERCON|N|6|2|% da Conta|% da Conta
--- ### T0P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0P|01|T0P_FILIAL|C|6|0|Filial|Filial
T0P|02|T0P_ID|C|36|0|ID|Identificador do Registro
T0P|03|T0P_IDGRUP|N|2|0|Grupo Trib.|Id. Grupo Trib.
T0P|04|T0P_SEQITE|C|6|0|Seq. Item|Sequência do Item
T0P|05|T0P_SEQPRO|C|6|0|Seq. Process|Sequencial do Processo
T0P|06|T0P_IDPROC|C|6|0|Processo|Processo
T0P|07|T0P_DPROCE|C|123|0|Desc. Proces|Descrição do Processo
--- ### T0Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0Q|01|T0Q_FILIAL|C|6|0|Filial|Filial
T0Q|02|T0Q_ID|C|6|0|ID|Identificador do registro
T0Q|03|T0Q_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T0Q|04|T0Q_CODAMB|C|6|0|Id. Cod. Amb|Id. Cod. Amb. Trabalho
T0Q|05|T0Q_DCODAM|C|220|0|Desc.Cod.Amb|Desc. Cod. Amb. Trabalho
T0Q|06|T0Q_DATIVD|M|10|0|Dsc.Ativ.Des|Desc. Ativ. Desenvolvida
T0Q|07|T0Q_LAMB|C|1|0|Amb Trab|Ambiente de trabalho
T0Q|08|T0Q_DSETOR|M|10|0|Lg. Adm|Lugar Administrativo
T0Q|09|T0Q_TPINSC|C|1|0|Tp.inscr|Tipo de inscrição.
T0Q|10|T0Q_NRINSC|C|14|0|Nr.Inscr|Nr. de inscriçao.
--- ### T0R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0R|01|T0R_FILIAL|C|6|0|Filial|Filial
T0R|02|T0R_ID|C|36|0|ID|Identificador do Registro
T0R|03|T0R_IDGRUP|N|2|0|Grupo Trib.|Id. Grupo Trib.
T0R|04|T0R_SEQITE|C|6|0|Seq. Item|Sequência do Item
T0R|05|T0R_SEQHIS|C|6|0|Seq. Históri|Sequência do Histórico
T0R|06|T0R_IDHIST|C|36|0|Hist. Padrão|Histórico Padrão
T0R|07|T0R_CODHIS|C|30|0|Hist. Padrão|Histórico Padrão
T0R|08|T0R_DHISTO|C|100|0|Desc. Hist.|Descrição Histórico Padrã
T0R|09|T0R_ACAO|C|1|0|Ação|Ação
--- ### T0S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0S|01|T0S_FILIAL|C|6|0|Filial|Filial
T0S|02|T0S_ID|C|36|0|ID|Identificador do Registro
T0S|03|T0S_CODIGO|C|60|0|Código|Código da Conta Parte B
T0S|04|T0S_DESCRI|C|220|0|Descrição|Descrição Conta Parte B
T0S|05|T0S_DTFINA|D|8|0|Data Final|Data Final
T0S|06|T0S_DTLIMI|D|8|0|Data Limite|Data Limite
T0S|07|T0S_NATURE|C|1|0|Natureza|Natureza da Conta
T0S|08|T0S_CNPJRE|C|14|0|CNPJ Relac|CNPJ da Relacionada
T0S|09|T0S_CODPB|C|6|0|Tab. Parte B|Cod tab padrao da parte B
T0S|10|T0S_DCODP|C|220|0|Desc Parte B|Desc Cod padrao parte B
T0S|11|T0S_IDCODP|C|36|0|Id. Parte B|Id código parte B
--- ### T0T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0T|01|T0T_FILIAL|C|6|0|Filial|Filial
T0T|02|T0T_ID|C|36|0|ID|Identificador do Registro
T0T|03|T0T_IDCODT|C|36|0|Id Cód Trib|Identificador Cód Tributo
T0T|04|T0T_CODLAN|C|6|0|Código|Código do Lançamento
T0T|05|T0T_DTLANC|D|8|0|Data|Data do Lançamento
T0T|06|T0T_VLLANC|N|16|2|Valor|Valor do Lançamento
T0T|07|T0T_TPLANC|C|1|0|Tipo|Tipo do Lançamento
T0T|08|T0T_INDDIF|C|1|0|Vlr Diferido|Realiza Valores Diferidos
T0T|09|T0T_HISTOR|M|10|0|Histórico|Histórico
T0T|10|T0T_ORIGEM|C|1|0|Origem|Origem do Lançamento
T0T|11|T0T_CTDEST|C|78|0|Conta Dest|Conta Destino Reclassific
T0T|12|T0T_IDDETA|C|42|0|Id. Detalha.|Id. Detalhamento
T0T|13|T0T_RURAL|C|1|0|Ativ. Rural|Atividade Rural
--- ### T0U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0U|01|T0U_FILIAL|C|6|0|Filial|Filial
T0U|02|T0U_ID|C|36|0|ID|Identificador do Registro
T0U|03|T0U_IDCODT|C|36|0|Id Cód Trib|Identificador Cód Tributo
T0U|04|T0U_CODLAN|C|6|0|Cód Lançamen|Código do Lançamento
T0U|05|T0U_IDPROC|C|6|0|Código|Código do Processo
T0U|06|T0U_DIDPRO|C|220|0|Descrição|Descrição do Processo
--- ### T0V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0V|01|T0V_FILIAL|C|6|0|Filial|Filial do Sistema
T0V|02|T0V_ID|C|36|0|Id|Identificador do registro
T0V|03|T0V_CODIGO|C|5|0|Código|Código do Motivo
T0V|04|T0V_DESCRI|C|220|0|Descrição|Descrição do Motivo
T0V|05|T0V_DCOMPL|C|220|0|Desc. Compl.|Descrição Complementar
T0V|06|T0V_SUBITE|C|5|0|Código|Código do Subitem
T0V|07|T0V_DESSUB|C|220|0|Desc.Subitem|Descrição do subitem
T0V|08|T0V_IDSBIT|C|36|0|Id. Subitem|Identificador do Subitem
T0V|09|T0V_UF|C|2|0|UF|UF do código de motivo
T0V|10|T0V_IDUF|C|6|0|Id. UF|Identificador da UF
T0V|11|T0V_DESCUF|C|220|0|Descrição UF|Descrição UF
T0V|12|T0V_VALIDA|D|8|0|Dt. Validade|Data de Validade
--- ### T0W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0W|01|T0W_FILIAL|C|6|0|Filial|Filial
T0W|02|T0W_ID|C|6|0|ID|Identificador do registro
T0W|03|T0W_NOMEOP|C|220|0|Nome Operad.|Nome da Operadora
T0W|04|T0W_REGANS|C|6|0|Reg. ANS|Registro ANS
T0W|05|T0W_CNPJOP|C|14|0|CNPJ da Oper|CNPJ da Operadora
T0W|06|T0W_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T0W|07|T0W_VERSAO|C|14|0|Id. Ver. Reg|Id.da versao do Registro
--- ### T0X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0X|01|T0X_FILIAL|C|6|0|Filial|Filial
T0X|02|T0X_ID|C|36|0|ID|Identificador do Registro
T0X|03|T0X_IDEVEN|C|6|0|Id. Evento|Id. do Evento
T0X|04|T0X_IDCHVE|C|55|0|Chave Evt.|Chave do Evento
T0X|05|T0X_PREDEC|C|220|0|Eventos Pred|Eventos Predecessores
T0X|06|T0X_TPERRO|C|1|0|Tipo do Erro|Tipo do Erro
T0X|07|T0X_CDERRO|C|10|0|Código Erro|Código do erro
T0X|08|T0X_DCERRO|M|10|0|Desc Erro|Descrição do Erro
T0X|09|T0X_DATA|D|8|0|Data do Erro|Data do erro
T0X|10|T0X_HORA|C|8|0|Hora do Erro|Hora do erro
T0X|11|T0X_USER|C|30|0|Usuario|Nome do Usuário Logado
--- ### T0Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T0Z|01|T0Z_FILIAL|C|6|0|Filial|Filial
T0Z|02|T0Z_ID|C|6|0|ID|ID
T0Z|03|T0Z_CNPJEE|C|14|0|CNPJ Ent Edu|CNPJ Entidade Educacional
T0Z|04|T0Z_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
--- ### T10
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T10|01|T10_FILIAL|C|6|0|Filial|Filial
T10|02|T10_ID|C|6|0|ID|Identificador do Registro
T10|03|T10_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T10|04|T10_ACUMCG|C|1|0|Cod Acum Car|Código Acumulação Cargos
T10|05|T10_CONESP|C|1|0|Cod Temp Esp|Código Contag Temp Espec
T10|06|T10_DEDEXC|C|1|0|Car Ded Excl|Cargo Dedicação Exclusiva
--- ### T11
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T11|01|T11_FILIAL|C|6|0|Filial|Filial
T11|02|T11_ID|C|6|0|ID|Identificador do Registro
T11|03|T11_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T11|04|T11_ACUMCG|C|1|0|Cod Acum Car|Código Acumulação Cargos
T11|05|T11_NRLEI|C|12|0|Número Lei|Número da Lei
T11|06|T11_DTLEI|D|8|0|Data da Lei|Data da Lei
T11|07|T11_SITCGO|C|1|0|Situac. Lei|Situação Gerada pela Lei
--- ### T12
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T12|01|T12_FILIAL|C|6|0|Filial|Filial
T12|02|T12_ID|C|6|0|ID|Identificador do registro
T12|03|T12_CODGRU|C|10|0|Gru Fat Ris|Grupo Fator Risco Amb.
T12|04|T12_DESGRU|C|220|0|Des Gru Fat|Descr Grupo Fat Ris Amb
T12|05|T12_CODFAT|C|10|0|Cod Fat Ris|Código Fator Risco Amb.
T12|06|T12_DESFAT|C|220|0|Fat Ris Amb|Descr Fator Risco Amb.
T12|07|T12_VALIDA|D|8|0|Data Vigênc.|Dt vig Fator Risco Amb.
--- ### T13
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T13|01|T13_FILIAL|C|6|0|Filial|Filial
T13|02|T13_ID|C|6|0|ID.|Identificador do Registro
T13|03|T13_CODIGO|C|2|0|Código|Cód. Classif. Trabalhador
T13|04|T13_DESCRI|C|220|0|Descrição|Descrição Classificação
T13|05|T13_VALIDA|D|8|0|Dt. Vigência|Data Fim Vigência
--- ### T14
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T14|01|T14_FILIAL|C|6|0|Filial|Filial
T14|02|T14_ID|C|36|0|ID|Identificador do registro
T14|03|T14_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T14|04|T14_INDAPU|C|1|0|Per.Apuração|Período da Apuração
T14|05|T14_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T14|06|T14_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T14|07|T14_IDEDMD|C|30|0|Iden Dem Pgt|Iden Dem Pgt
T14|08|T14_CODCAT|C|6|0|Cod. Categor|Codigo Categoria
T14|09|T14_DCATEG|C|220|0|Des Categ|Des. Categoria
T14|10|T14_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T14|11|T14_CODCBO|C|6|0|Cód.Ocupação|Código da Ocupação
T14|12|T14_DCODCB|C|220|0|Desc.Ocupac.|Descrição da Ocupação
T14|13|T14_NATATV|C|1|0|Nat.Atividad|Natureza da Atividade
T14|14|T14_QTDTRB|C|2|0|Qt Dias Trab|Qtd. De dias trabalhados
T14|15|T14_INDRRA|C|1|0|Ind. Rec RRA|Ind. Rend. Recebidos RRA
T14|16|T14_TPPRRA|C|1|0|Tp. Proc.|Tp. Processo RRA
T14|17|T14_NRPRRA|C|21|0|Num. Proc.|Num. Processo RRA
T14|18|T14_DESCRA|C|50|0|Desc. Rend.|Desc. Rendimentos RRA
T14|19|T14_QTMRRA|N|5|1|Qtd. Meses|Qtd. Meses RRA
T14|20|T14_VLRCUS|N|15|2|Vlr. Des. Ju|Vlr. Despesas Judiciais
T14|21|T14_VLRADV|N|15|2|Vlr. Des. Ad|Vlr. Despesas Advogados
T14|22|T14_NOTAFT|C|9|0|Número FGTS|Número notificação FGTS
--- ### T15
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T15|01|T15_FILIAL|C|6|0|Filial|Filial
T15|02|T15_ID|C|6|0|ID|Identificador do Registro
T15|03|T15_VERSAO|C|14|0|Id. Ver. Reg|Id. Da Versão do Registro
T15|04|T15_RECIBO|C|30|0|Num Id. Rec.|Num Id. Rec. Pagto
T15|05|T15_LOTACA|C|6|0|Id. Lotação|Ident Lotaçã
T15|06|T15_CNPJOP|C|14|0|Cnpj Operado|CNPJ Oper. Plano Saude
T15|07|T15_REGANS|C|6|0|Reg. ANS|Reg. Agencia Nacional Saú
T15|08|T15_VLPGTI|N|15|2|Vl. Pg. Titu|Vlr. Pago pelo Titular
T15|09|T15_TRABAL|C|6|0|Id. Trab.|Id. do Trabalhador
T15|10|T15_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T15|11|T15_TPINSC|C|1|0|Tp Inscricao|Tipo de Inscrição
T15|12|T15_NRINSC|C|15|0|Nr.Inscrição|Número de Inscrição
T15|13|T15_ESTABE|C|6|0|Id Estab Lot|Id do Estabelecimento Lot
--- ### T16
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T16|01|T16_FILIAL|C|6|0|Filial|Filial
T16|02|T16_ID|C|6|0|ID|Identificador do Registro
T16|03|T16_VERSAO|C|14|0|Id. Ver. Reg|Id. Da Versão do Registro
T16|04|T16_IDOPER|C|6|0|Id Operadora|Id. Operadora Plano Saude
T16|05|T16_SEQUEN|C|3|0|Sequencia|Sequencia
T16|06|T16_CPFDEP|C|11|0|CPF Depend.|CPF Dependente
T16|07|T16_DTNDEP|D|8|0|Dt. Nas. Dep|Data Nascimento Dependent
T16|08|T16_NOMDEP|C|60|0|Nome Depend.|Nome do Dependente
T16|09|T16_RELDEP|C|2|0|Rel. Depend.|Relação do Dependente
T16|10|T16_VPGDEP|N|15|2|Vlr. Pgo Dep|Vlr. Ref. Plano Saude Dep
T16|11|T16_LOTACA|C|6|0|Id. Lotação|Ident Lotação
T16|12|T16_TRABAL|C|6|0|Id. Trab.|Id. do Trabalhador
T16|13|T16_RECIBO|C|30|0|Num Id. Rec.|Num Id. Rec. Pagto
T16|14|T16_CNPJOP|C|14|0|Cnpj Operado|CNPJ Oper. Plano Saude
T16|15|T16_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T16|16|T16_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T16|17|T16_NRINSC|C|15|0|Nr.Inscrição|Número de Inscrição
T16|18|T16_ESTABE|C|6|0|Id Estab Lot|Ident Estabelecimento Lot
T16|19|T16_TPDEP|C|6|0|Id Tp Dep|Id. Tipo Dependente
T16|20|T16_DTPDE|C|220|0|Descr Tp Dep|Descricao Tipo Dependente
T16|21|T16_REGANS|C|6|0|Reg. ANS|Reg. Agencia Nacional Saú
--- ### T17
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T17|01|T17_FILIAL|C|6|0|Filial|Filial
T17|02|T17_ID|C|36|0|ID|Identificador do registro
T17|03|T17_CODIGO|C|6|0|Código|Código
T17|04|T17_DESCRI|C|254|0|Descriçao|Descriçao Pagto/remessa
T17|05|T17_DTINI|D|8|0|Data inicial|Data Inicial
T17|06|T17_DTFIM|D|8|0|Data Final|Data Final
--- ### T18
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T18|01|T18_FILIAL|C|6|0|Filial|Filial
T18|02|T18_ID|C|36|0|ID|Identificador do Registro
T18|03|T18_DTINI|D|8|0|Dt. Inic Per|Data Inicial do Período
T18|04|T18_DTFIN|D|8|0|Dt. Fin Per.|Data Final do Período
T18|05|T18_STATUS|C|1|0|Status Reg.|Status do Registro
--- ### T19
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T19|01|T19_FILIAL|C|6|0|Filial|Filial
T19|02|T19_ID|C|36|0|ID|Identificador do Registro
T19|03|T19_DTEST|D|8|0|Dt. Est. Fin|Data Estoque Final
T19|04|T19_CODITE|C|36|0|Id. Item|Identificador do Item
T19|05|T19_ITEM|C|60|0|Item|Código do Item
T19|06|T19_DESITE|C|220|0|Desc. Item|Descrição do Item
T19|07|T19_QTDEST|N|16|3|Qtd. Estoque|Quantidade em Estoque
T19|08|T19_INDEST|C|1|0|Ind. Tipo Es|Ind. Tipo Estoque
T19|09|T19_CODPAR|C|36|0|Id. Particip|Id. Participante
T19|10|T19_CPARTI|C|60|0|Cód. Partic.|Código do Participante
T19|11|T19_DESPAR|C|220|0|Nome Partic.|Nome Participante
--- ### T1A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1A|01|T1A_FILIAL|C|6|0|Filial|Filial
T1A|02|T1A_FILORI|C|40|0|Filial Docum|Filial do Documento
T1A|03|T1A_ID|C|36|0|ID|ID da tabela
T1A|04|T1A_IDDEBI|N|6|0|ID Débito|ID Sequencial Débito
T1A|05|T1A_ANOPOS|C|4|0|Ano Pos.|Ano Postergado
T1A|06|T1A_IDTRIB|C|6|0|ID Trib|ID do Tributo
T1A|07|T1A_CODTRI|C|2|0|Cod. Trib.|Código Tributo
T1A|08|T1A_DESTRI|C|254|0|Desc. Trib.|Descriçao Tributo
T1A|09|T1A_PERAPU|C|6|0|Per. Apu.|Período Apuração
T1A|10|T1A_CODREC|C|6|0|Cod. Receita|Código de Receita
T1A|11|T1A_TRIPOS|C|1|0|Trim. Poster|Trimestre Postergado
T1A|12|T1A_PERIOD|C|1|0|Period.|Periodicidade
T1A|13|T1A_CPNEST|C|14|0|CNPJ Estab.|CNPJ Estabelecimento
T1A|14|T1A_CNPINC|C|14|0|CNPJ Incorp.|CNPJ Incorporação
T1A|15|T1A_VALTRI|N|16|2|Val. Trib.|Valor Tributo
T1A|16|T1A_CODMUN|C|6|0|Cod. Mun.|Código Município
T1A|17|T1A_IDSCP|C|36|0|ID SCP|ID SCP
T1A|18|T1A_CNPSCP|C|14|0|CNPJ SCP|CNPJ SCP
T1A|19|T1A_NOMSCP|C|100|0|Nome SCP|Nome SCP
T1A|20|T1A_UF|C|6|0|UF|Unidade Federativa
T1A|21|T1A_DESCUF|C|220|0|Desc UF|Desc Unidade Federativa
T1A|22|T1A_DCODMU|C|220|0|Des Municip|Desc Municipio
T1A|23|T1A_DTDEBI|D|8|0|Dt. Debito|Data do Debito
T1A|24|T1A_IDDOC|C|32|0|Id. Doc.|Identif. Documento
--- ### T1B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1B|01|T1B_FILIAL|C|6|0|Filial|Filial do Sistema
T1B|02|T1B_ID|C|36|0|ID|ID do registro
T1B|03|T1B_IDPROC|C|6|0|ID Proc|ID Processo
T1B|04|T1B_DESPRO|C|220|0|Desc. Proc.|Descrição Processo
T1B|05|T1B_CODSUS|C|14|0|Cod. Susp.|Código de Suspensão
T1B|06|T1B_TERCEI|C|1|0|Terceiro|Terceiro
T1B|07|T1B_VALSUS|N|16|2|Val. Susp.|Valor Suspensão
T1B|08|T1B_IDSUSP|C|34|0|ID Susp.|ID Suspensão
--- ### T1C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1C|01|T1C_FILIAL|C|6|0|Filial|Filial
T1C|02|T1C_CODIGO|C|6|0|Código|Código
T1C|03|T1C_DESCRI|C|254|0|Descriçao|Descriçao
T1C|04|T1C_IDCPAG|C|36|0|Id Cod Pag|Id codigo de pagamento
T1C|05|T1C_VALOR|N|16|2|Valor|Valor do pagamento
T1C|06|T1C_ID|C|36|0|Id|Id do registro
--- ### T1M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1M|01|T1M_FILIAL|C|6|0|Filial|Filial
T1M|02|T1M_ID|C|6|0|ID|Identificador do registro
T1M|03|T1M_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1M|04|T1M_INDAPU|C|1|0|Ind Apuração|Ind. Período Apuração
T1M|05|T1M_PERAPU|C|6|0|Per Apuração|Período Apuração
T1M|06|T1M_NRINSC|C|15|0|Nr Ins Rural|Núm. Insc. Estab. Rural
T1M|07|T1M_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T1M|08|T1M_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T1M|09|T1M_STATUS|C|1|0|Status Reg.|Status do registro
T1M|10|T1M_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T1M|11|T1M_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T1M|12|T1M_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T1M|13|T1M_IDESTA|C|6|0|Id. Estab|Identificador do Estab.
T1M|14|T1M_NRCAEP|C|15|0|Nr. CAEPF|Numero do CAEPF
T1M|15|T1M_STASEC|C|1|0|Status Sec.|Status Secundario
T1M|16|T1M_XMLID|C|36|0|Id do XML.|Id do XML
T1M|17|T1M_LOGOPE|C|1|0|Log Operacao|Log Operacao
T1M|18|T1M_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T1M|19|T1M_TPGUIA|C|1|0|Ind. Guia|Ind. do tipo de guia
T1M|20|T1M_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T1M|21|T1M_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T1M|22|T1M_DTRECP|D|8|0|Dt. Recept|Data Receptação
T1M|23|T1M_HRRECP|C|8|0|Hr. Recept|Hora Repectação
--- ### T1N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1N|01|T1N_FILIAL|C|6|0|Filial|Filial
T1N|02|T1N_ID|C|6|0|ID|Identificador do registro
T1N|03|T1N_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1N|04|T1N_NRINSC|C|15|0|Nr Ins Rural|Núm. Insc. Estab. Rural
T1N|05|T1N_INDCOM|C|6|0|Indic. Comer|Indicativ Comercialização
T1N|06|T1N_DINDCO|C|220|0|Dsc. Indic.|Desc. Ind Comercialização
T1N|07|T1N_VLRTOT|N|16|2|Valor Total|Val Total Comercialização
T1N|08|T1N_IDESTA|C|6|0|Id. Estab.|Id do Estabelecimento
--- ### T1O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1O|01|T1O_FILIAL|C|6|0|Filial|Filial
T1O|02|T1O_ID|C|6|0|ID|Identificador do registro
T1O|03|T1O_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1O|04|T1O_NRINSC|C|15|0|Nr Ins Rural|Núm. Insc. Estab. Rural
T1O|05|T1O_INDCOM|C|6|0|Indic. Comer|Indicativ Comercialização
T1O|06|T1O_TPINSA|C|1|0|Tp Inscrição|Tipo de Inscrição
T1O|07|T1O_NRINSA|C|15|0|Num. Insc.|Número de Inscrição
T1O|08|T1O_VLRCOM|N|16|2|Vlr. Comerc.|Vlr Bruto Comerc Produção
T1O|09|T1O_IDESTA|C|6|0|Id. Estab.|Id. Estabelecimento
--- ### T1P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1P|01|T1P_FILIAL|C|6|0|Filial|Filial
T1P|02|T1P_ID|C|6|0|ID|Identificador do registro
T1P|03|T1P_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1P|04|T1P_NRINSC|C|15|0|Nr Ins Rural|Núm. Insc. Estab. Rural
T1P|05|T1P_IDESTA|C|6|0|Id. Estab.|Id. do Estabelecimento
T1P|06|T1P_INDCOM|C|6|0|Indic. Comer|Indicativ Comercialização
T1P|07|T1P_IDPROC|C|6|0|Proc. Judici|Processo Judicial
T1P|08|T1P_DSCPRO|C|220|0|Des Proc Jud|Desc. Processo Judicial
T1P|09|T1P_CODSUS|C|14|0|Codigo Susp|Cod Indic Suspensão
T1P|10|T1P_IDSUSP|C|34|0|Chave Susp|Chave Cod. Suspensao
T1P|11|T1P_VLRPRV|N|16|2|Vlr Cont Pre|Vlr Contr Previdenciária
T1P|12|T1P_VLRRAT|N|16|2|Vlr Cont Gil|Vlr Contribuição Gilrat
T1P|13|T1P_VLRSEN|N|16|2|Vlr Cont Sen|Vlr Contribuição Senar
--- ### T1Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1Q|01|T1Q_FILIAL|C|6|0|Filial|Filial
T1Q|02|T1Q_ID|C|6|0|ID|Identificador do registro
T1Q|03|T1Q_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1Q|04|T1Q_DTPGTO|D|8|0|Dt. Pgto.|Data de Pagamento
T1Q|05|T1Q_PERREF|C|6|0|Per.Referenc|Período Referência
T1Q|06|T1Q_VLRLIQ|N|14|2|Vlr. Liquido|Valor Líquido
T1Q|07|T1Q_VLREAJ|N|14|2|Vlr. Reajust|Valor Reajustado
T1Q|08|T1Q_VLIRRF|N|14|2|Vlr. IRRF|Valor IRRF
--- ### T1R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1R|01|T1R_FILIAL|C|6|0|Filial|Filial
T1R|02|T1R_ID|C|6|0|ID|Identificador do Registro
T1R|03|T1R_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1R|04|T1R_OPCONS|C|1|0|Op. Consulta|Opções de consulta
T1R|05|T1R_PERSOL|C|6|0|Per.Solicit.|Periodo Solicitado
T1R|06|T1R_IDTRAB|C|6|0|ID Trab.|ID do Trabalhador
T1R|07|T1R_CPFTRA|C|11|0|CPF Trab.|CPF do Trabalhador
T1R|08|T1R_STATUS|C|1|0|Status Reg.|Status do Registro
T1R|09|T1R_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T1R|10|T1R_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T1R|11|T1R_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T1R|12|T1R_INDEST|C|1|0|Ind. Estabel|Indicativo Estabeleciment
--- ### T1S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1S|01|T1S_FILIAL|C|6|0|Filial|Filial
T1S|02|T1S_ID|C|6|0|ID|Identificador do Registro
T1S|03|T1S_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T1S|04|T1S_INDAPU|C|1|0|Ind.Apuração|Ind. Período Apuração
T1S|05|T1S_PERAPU|C|6|0|Per.Apuração|Período de Apuração
T1S|06|T1S_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T1S|07|T1S_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T1S|08|T1S_STATUS|C|1|0|Status Reg.|Status do Registro
T1S|09|T1S_VERANT|C|14|0|Ver. Ant.Reg|Versão anterior registro
T1S|10|T1S_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T1S|11|T1S_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T1S|12|T1S_XMLID|C|36|0|Id do XML.|Id do XML
T1S|13|T1S_LOGOPE|C|1|0|Log Operacao|Log Operacao
T1S|14|T1S_TPGUIA|C|1|0|Tipo de Guia|Ind.Tipo de Guia
T1S|15|T1S_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T1S|16|T1S_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T1S|17|T1S_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T1S|18|T1S_DTRECP|D|8|0|Dt. Recept|Data Recepção
T1S|19|T1S_HRRECP|C|8|0|Hr. Recept.|Hora Receptação
--- ### T1T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1T|01|T1T_FILIAL|C|6|0|Filial|Filial
T1T|02|T1T_ID|C|6|0|ID|Identificador do registro
T1T|03|T1T_CODIGO|C|1|0|Código|Cód. Indic. Comercializ.
T1T|04|T1T_DESCRI|C|220|0|Descrição|Desc. Indic. Comercializ
T1T|05|T1T_VALIDA|D|8|0|Dt. Vigência|Data Fim Vigência
--- ### T1U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1U|01|T1U_FILIAL|C|6|0|Filial|Filial
T1U|02|T1U_ID|C|6|0|ID|Identificador do registro
T1U|03|T1U_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1U|04|T1U_CPF|C|11|0|CPF|CPF do Funcionario
T1U|05|T1U_NOME|C|70|0|Nome|Nome do Funcionario
T1U|06|T1U_DTALT|D|8|0|Dt. Alterac.|Data da Alteracao
T1U|07|T1U_NIS|C|11|0|NIS|NIS
T1U|08|T1U_SEXO|C|1|0|Sexo|Sexo do Funcionario
T1U|09|T1U_RCCOR|C|1|0|Raca/Cor|Raca/Cor do Funcionario
T1U|10|T1U_ESTCIV|C|1|0|Estado Civil|Estado Civil Funcionario
T1U|11|T1U_GRINST|C|6|0|Id Grau Inst|Id. Grau Instrucao Func.
T1U|12|T1U_DGRINS|C|220|0|Des Grau Ins|Descr.Grau Instrucao Func
T1U|13|T1U_NRCTPS|C|11|0|Num. CTPS|Numero da CTPS
T1U|14|T1U_SERCTP|C|6|0|Serie CTPS|Serie da CTPS
T1U|15|T1U_UFCTPS|C|6|0|Id. UF CTPS|Identificador UF CTPS
T1U|16|T1U_DUFCTP|C|220|0|Desc UF CTPS|Descrição da UF CTPS
T1U|17|T1U_NRRIC|C|14|0|Num. RIC|Numero do RIC.
T1U|18|T1U_OREMRI|C|20|0|Org Emis RIC|Órgão Emissão do RIC.
T1U|19|T1U_DTEXRI|D|8|0|Dt. Exp. RIC|Data Expedicao do RIC
T1U|20|T1U_NRRG|C|14|0|Num. RG|Numero do RG
T1U|21|T1U_OREMRG|C|20|0|Org Emis RG.|Órgão Emissão RG.
T1U|22|T1U_DTEMRG|D|8|0|Dt. Exp. RG|Data Expedicao do RG
T1U|23|T1U_NRRNE|C|14|0|Num. RNE|Numero do RNE
T1U|24|T1U_OREMRN|C|20|0|Org Emis RNE|Órgão Emissão RNE.
T1U|25|T1U_DTEMRN|D|8|0|Dt. Exp. RNE|Data Expedicao do RNE
T1U|26|T1U_NUMOC|C|14|0|Num. OC|Numero no OC
T1U|27|T1U_OREMOC|C|20|0|Org Emis OC.|Órgão Emissor OC.
T1U|28|T1U_DTEXOC|D|8|0|Dt. Exp. OC|Data Expedicao OC
T1U|29|T1U_DTVLOC|D|8|0|Dt. Val. OC|Data Validade OC
T1U|30|T1U_NRCNH|C|12|0|Num. CNH|Numero da CNH
T1U|31|T1U_DTEXCN|D|8|0|Dt. Exp. CNH|Data Expedicao da CNH
T1U|32|T1U_UFCNH|C|6|0|UF CNH|UF CNH
T1U|33|T1U_DUFCN|C|220|0|Desc. UF CNH|Descricao da UF da CNH
T1U|34|T1U_DTVLCN|D|8|0|Dt. Val. CNH|Data Validade da CNH
T1U|35|T1U_DTPCNH|D|8|0|Primeira CNH|Data Primeira CNH
T1U|36|T1U_CATCNH|C|1|0|Categ. CNH|Categoria da CNH
T1U|37|T1U_PAIS|C|6|0|Id Pais End|Id. Pais do Endereco
T1U|38|T1U_DPAIS|C|220|0|Des Pais End|Descr. Pais do Endereco
T1U|39|T1U_UF|C|6|0|Id. UF End.|Id. UF do Endereco
T1U|40|T1U_DUF|C|220|0|Descr UF End|Descricao UF do Endereco
T1U|41|T1U_MUN|C|6|0|Id. Mun. End|Id. Municipio do Endereco
T1U|42|T1U_DMUN|C|220|0|Des Mun End|Descr. Municipio Endereco
T1U|43|T1U_NOMCID|C|50|0|Nome Cid Ext|Nome Cidade Exterior
T1U|44|T1U_TPLOGR|C|6|0|Id. Tp. Log.|Id. Tipo Logradouro
T1U|45|T1U_DTPLOG|C|220|0|Des Tp Log|Descicao Tipo Logradouro
T1U|46|T1U_LOGRAD|C|100|0|Descr. Logr.|Descricao do Logradouro
T1U|47|T1U_NRLOG|C|10|0|Numero Log.|Numero Logradouro
T1U|48|T1U_COMLOG|C|30|0|Comp. Log.|Complemento Logradouro
T1U|49|T1U_BAIRRO|C|90|0|Bairro|Bairro
T1U|50|T1U_CEP|C|10|0|CEP|CEP
T1U|51|T1U_APOSEN|C|1|0|Aposentado?|Funcionario Aposentado?
T1U|52|T1U_DTCHEG|D|8|0|Dt. Chegada|Data Chegada
T1U|53|T1U_CCTRAE|C|6|0|Cond. Trab.|Cond. Trab. Estr
T1U|54|T1U_DCONTE|C|220|0|Desc. Cond T|Desc. Cond. Trab Extrang.
T1U|55|T1U_CASBRA|C|1|0|Cas. Brasil?|Casado com Brasileiro(a)?
T1U|56|T1U_FILBRA|C|1|0|Fil. Brasil?|Filhos com Brasileiro(a)?
T1U|57|T1U_DEFFIS|C|1|0|Def.Fisica ?|Deficiencia Fisica ?
T1U|58|T1U_DEFVIS|C|1|0|Def. Visual?|Deficiencia Visual?
T1U|59|T1U_DEFAUD|C|1|0|Def. Audit?|Deficiencia Auditiva?
T1U|60|T1U_DEFMEN|C|1|0|Def. Mental?|Deficiencia Mental?
T1U|61|T1U_DEFINT|C|1|0|Def.Intelec?|Deficiencia Intelectual ?
T1U|62|T1U_REABIL|C|1|0|Reab/Readap?|Reabilitado ou Readap.?
T1U|63|T1U_OBSDEF|M|10|0|Obs Info Def|Obs. Info. Deficiencia
T1U|64|T1U_DDDFPR|C|3|0|DDD Fone Pri|DDD Fone Principal
T1U|65|T1U_FONPRC|C|10|0|Fone Princ.|Fone Principal
T1U|66|T1U_DDDFAL|C|3|0|DDD Fone Alt|DDD Fone Alternativo
T1U|67|T1U_FONALT|C|10|0|Fone Altern.|Fone Alternativo
T1U|68|T1U_EMAILP|C|60|0|Email Prin.|Email principal
T1U|69|T1U_EMAILA|C|60|0|Email Altern|Email Alternativo
T1U|70|T1U_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T1U|71|T1U_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T1U|72|T1U_STATUS|C|1|0|Status Reg.|Status do registro
T1U|73|T1U_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T1U|74|T1U_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T1U|75|T1U_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T1U|76|T1U_NOMSOC|C|70|0|Nome Social|Nome Social
T1U|77|T1U_INFCOT|C|1|0|Cota Defic.|Cota Deficiente
T1U|78|T1U_XMLID|C|36|0|Id do XML.|Id do XML
T1U|79|T1U_STASEC|C|1|0|StatusSecund|Status Secundário
T1U|80|T1U_LOGOPE|C|1|0|Log Operacao|Log Operacao
T1U|81|T1U_DINSIS|D|8|0|Dt Inc Sist|Data Inclusão Sistêmica
T1U|82|T1U_DTNASC|D|8|0|Data Nascim.|Data de Nascimento
T1U|83|T1U_CODPAI|C|6|0|Id País Nasc|Id País Nacimento
T1U|84|T1U_DCODPA|C|220|0|Des País Nas|Descr. País Nascimento
T1U|85|T1U_CODUF|C|6|0|Id. UF Nasc.|Id. UF de Nascimento
T1U|86|T1U_DCODUF|C|220|0|Descr UF Nas|Descri. UF de Nascimento
T1U|87|T1U_CODMUN|C|6|0|Id. Mun. Nas|Id Municipio de Nasciment
T1U|88|T1U_DCODMU|C|220|0|Des Mun Nasc|Desc Municipio Nascimento
T1U|89|T1U_PAINAC|C|6|0|Id. Pais Nac|Id. Pais de Nacionalidade
T1U|90|T1U_DPAINA|C|220|0|Des Pais Nac|Descr. Pais Nacionalidade
T1U|91|T1U_NOMMAE|C|70|0|Nome Mae|Nome da Mae
T1U|92|T1U_NOMPAI|C|70|0|Nome Pai|Nome do Pai
T1U|93|T1U_DDIFPR|C|2|0|DDI Fone Pri|DDI Fone Principal
T1U|94|T1U_DDIFAL|C|2|0|DDI Fone Alt|DDI Fone Alternativo
T1U|95|T1U_TPRESI|C|1|0|Tempo Resid.|Tempo de residência
T1U|96|T1U_DTRANS|D|8|0|Dt. Transm.|Data Transmissão
T1U|97|T1U_HTRANS|C|8|0|Hr. Transm|Hora Transmissao
T1U|98|T1U_CNDING|C|1|0|Cond. Ingres|Condição de ingresso
T1U|99|T1U_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T1U|9A|T1U_HRRECP|C|8|0|Hr. Recept|Hora Receptação
--- ### T1V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1V|01|T1V_FILIAL|C|6|0|Filial|Filial
T1V|02|T1V_ID|C|6|0|ID|Identificador do registro
T1V|03|T1V_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1V|04|T1V_CPF|C|11|0|CPF do Trab.|CPF do Trabalhador
T1V|05|T1V_MATRIC|C|30|0|Matricula|Matricula do Funcionario
T1V|06|T1V_NOME|C|70|0|Nome|Nome do Funcionário
T1V|07|T1V_DTALT|D|8|0|Dt. Alterac.|Data da Alteracao
T1V|08|T1V_NIS|C|11|0|NIS|NIS
T1V|09|T1V_TPREGT|C|1|0|Tp Reg Trab|Tipo Regime Trabalhista
T1V|10|T1V_TPREGP|C|1|0|Tp Reg Prev|Tp. Regime Previdenciario
T1V|11|T1V_TPREGJ|C|1|0|Tp Reg Jor|Tp. Regime Jornada
T1V|12|T1V_NATATV|C|1|0|Nat. Ativid.|Natureza da Atividade
T1V|13|T1V_DATAB|C|2|0|Data Base|Data Base Categ. Prof. Tr
T1V|14|T1V_CNPJCP|C|14|0|CNPJ Cat Pro|CNPJ Sindicato da Categor
T1V|15|T1V_CODCGO|C|6|0|Cód. Cargo|Código do Cargo
T1V|16|T1V_DCODCG|C|220|0|Desc. Cargo|Descrição do Cargo
T1V|17|T1V_CODFUN|C|6|0|Cód. Função|Código da Função
T1V|18|T1V_DCODFU|C|220|0|Desc. Função|Descrição da Função
T1V|19|T1V_CODCAT|C|6|0|Cód. Categ.|Código da Categoria
T1V|20|T1V_DCODCA|C|220|0|Desc. Categ.|Descrição da Categoria
T1V|21|T1V_VLSLFX|N|16|2|Vlr Sal Fixo|Valor Salario Fixo
T1V|22|T1V_UNSLFX|C|1|0|Und Sal Fixo|Unidade Salario Fixo
T1V|23|T1V_DESSVR|C|254|0|Desc Sal Var|Desc Salario Variavel
T1V|24|T1V_TPCONT|C|1|0|Tp. Contrato|Tipo Contrato
T1V|25|T1V_DTTERM|D|8|0|Dt Term Con|Data Termino Contrato
T1V|26|T1V_TPINSC|C|1|0|Tp Inscricao|Tipo de Inscricao
T1V|27|T1V_NRINSC|C|15|0|Nr Inscricao|Numero de Inscricao
T1V|28|T1V_DESLOT|C|220|0|Desc. Compl.|Descricao da Lotacao
T1V|29|T1V_TPLOGD|C|6|0|Tp Logr Dom.|Tp Logr. Trab Domestico
T1V|30|T1V_DSCTPL|C|220|0|Log. Domest.|Desc Tp Log Domestico
T1V|31|T1V_DELOGD|C|100|0|Des. Lg Dom.|Desc Logr. Trab Domestico
T1V|32|T1V_NRLOGD|C|10|0|Nr. Logr Dom|Nr. Logr Domestico
T1V|33|T1V_COMLGD|C|30|0|Comp. Logr D|Comp. Logr Trab Domestico
T1V|34|T1V_BAIRTD|C|90|0|Bairro Trb D|Bairro Trab Domestico
T1V|35|T1V_CEPLTD|C|8|0|CEP Logr Dom|CEP Logr. Trab Domestico
T1V|36|T1V_UFTRBD|C|6|0|UF. Trb Dom.|UF Trabalhador Domestico
T1V|37|T1V_DUFTRD|C|220|0|Des. UF Dom.|Desc UF. Trab Domestico
T1V|38|T1V_CMUNTD|C|6|0|Mun Trb Dom|Mun Trab Doméstico
T1V|39|T1V_DSCMTD|C|220|0|Desc Mun Trb|Desc Mun. Trab. Doméstico
T1V|40|T1V_QTDHJS|N|5|2|Qtd. Horas|Qtd. Horas Jornada Semana
T1V|41|T1V_TPJORN|C|1|0|Tp. Jornada|Tipo de Jornada Trabalho
T1V|42|T1V_DTPJOR|C|100|0|Desc.Jornada|Descricao Tipo Jornada
T1V|43|T1V_CNPJSD|C|14|0|CNPJ Sind.|CNPJ Sindicato do Trab.
T1V|44|T1V_ALVJUD|C|6|0|Id Proc Jud|Id. Processo Judicial
T1V|45|T1V_DALVJU|C|220|0|Des Proc Jud|Descr. Processo Judicial
T1V|46|T1V_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T1V|47|T1V_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T1V|48|T1V_STATUS|C|1|0|Status Reg.|Status do registro
T1V|49|T1V_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T1V|50|T1V_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T1V|51|T1V_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T1V|52|T1V_TMPARC|C|1|0|Temp Parcial|Contrat. Tempo Parcial
T1V|53|T1V_DTEF|D|8|0|Data Efeito|Data de Efeito Alteração
T1V|54|T1V_DESALT|C|150|0|Desc. Alter.|Descrição da Alteração
T1V|55|T1V_CODCAR|C|6|0|Cod.Carreira|Código da Carreira
T1V|56|T1V_DESCAR|C|220|0|Des.Carreira|Descrição da Carreira
T1V|57|T1V_DTINGC|D|8|0|Dt. Ingresso|Data Ingresso Carreira
T1V|58|T1V_JUSTPR|M|10|0|Just. Prorr.|Prorrogação Trabalho Temp
T1V|59|T1V_TPLASM|C|1|0|Tp. de Plano|Tipo de Plano
T1V|60|T1V_MTVALT|C|1|0|Motivo Alter|Mtv Alteração Servidor P.
T1V|61|T1V_TPINAP|C|1|0|Tp. Ins Apre|Tp Inscr. Contr. Aprendiz
T1V|62|T1V_NRINAP|C|15|0|Nr. Insc.Apr|Nr. Inscrição Aprendiz
T1V|63|T1V_STASEC|C|1|0|StatusSecund|Status Secundário
T1V|64|T1V_XMLID|C|36|0|Id do XML.|Id do XML
T1V|65|T1V_LOGOPE|C|1|0|Log Operacao|Log Operacao
T1V|66|T1V_DINSIS|D|8|0|Dt Inc Sist|Data Inclusão Sistêmica
T1V|67|T1V_OBJDET|C|254|0|Obj. Determi|Objeto Determinante Contr
T1V|68|T1V_DTRANS|D|8|0|Dt. Transm|Data Transmissao
T1V|69|T1V_CODTRE|C|6|0|Trein. Cap.|Treinamento e capacitação
T1V|70|T1V_DSCTRE|C|220|0|Des. Treinam|Descriçao de Treinamento
T1V|71|T1V_HTRANS|C|8|0|Hr. Trans|Hora Transmissao
T1V|72|T1V_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T1V|73|T1V_TERGPS|C|1|0|Teto RGPS|Teto do RGPS
T1V|74|T1V_ABOPER|C|1|0|Abono Perm|Abono Permanência
T1V|75|T1V_HRRECP|C|8|0|Hr. Recept|Hora Receptacao
T1V|76|T1V_NMCARG|C|100|0|Nome Cargo|Nome Cargo
T1V|77|T1V_CBOCAR|C|6|0|CBO Cargo|CBO Cargo
T1V|78|T1V_DCBOCG|C|220|0|Desc. CBO C.|Descrição do CBO do Cargo
T1V|79|T1V_NMFUNC|C|100|0|Nome Função|Nome da função
T1V|80|T1V_CBOFUN|C|6|0|CBO Função|CBO Função
T1V|81|T1V_DCBOFC|C|220|0|Desc.CBO F.|Descrição do CBO Função
T1V|82|T1V_ACCARG|C|1|0|Acumulado|Cargo acumulável
T1V|83|T1V_HRSNOT|C|1|0|Hor. Noturno|Horário noturno
T1V|84|T1V_DSCJOR|M|10|0|Desc.Jornada|Descrição de jornada
T1V|85|T1V_DSCSAL|M|10|0|Desc.Salario|Descriçao Salário
T1V|86|T1V_INDAPR|C|1|0|Modalidade|Indicativo de modalidade
T1V|87|T1V_CNPJEN|C|14|0|CNPJ Entidad|CNPJ da entidade qualific
T1V|88|T1V_CNPJAT|C|14|0|CNPJ Ativida|CNPJ atividades práticas
--- ### T1X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1X|01|T1X_FILIAL|C|6|0|Filial|Filial
T1X|02|T1X_ID|C|6|0|ID|Identificador do registro
T1X|03|T1X_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do Registro
T1X|04|T1X_CNPJSI|C|14|0|CNPJ Sindic.|CNPJ Sindical
T1X|05|T1X_FPAS|C|6|0|Id Cod. FPAS|Id. Código FPAS
T1X|06|T1X_DFPAS|C|220|0|Desc. FPAS|Descrição Código FPAS
T1X|07|T1X_CODTER|C|6|0|Cód Terceiro|Desc. Código de Terceiro
T1X|08|T1X_DCODTE|C|220|0|Desc Cód Ter|Descrição Código de Terce
--- ### T1Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1Y|01|T1Y_FILIAL|C|6|0|Filial|Filial
T1Y|02|T1Y_ID|C|6|0|ID|Identificador do registro
T1Y|03|T1Y_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T1Y|04|T1Y_CNPJSI|C|14|0|CNPJ Sindic.|CNPJ Sindical
T1Y|05|T1Y_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T1Y|06|T1Y_DESTAB|C|220|0|Desc. Estab.|Descrição do Estabelecime
T1Y|07|T1Y_VLRREM|N|15|2|Vlr. Remun.|Valor da Remuneração
T1Y|08|T1Y_VLRDEC|N|15|2|Vlr. Déc Ter|Valor do décimo terceiro
T1Y|09|T1Y_VLBCCP|N|15|2|Vlr Base CP.|Valor Base Contrib. Prev.
T1Y|10|T1Y_VBCP13|N|15|2|Base C.P. 13|Base Contr. Prev. 13º
T1Y|11|T1Y_VLBCFG|N|15|2|Vl.Base FGTS|Valor Base FGTS
T1Y|12|T1Y_VLRDES|N|15|2|Vlr. Total|Valor Total da Contribuiç
T1Y|13|T1Y_LOTACA|C|6|0|Id Lotação|Id. Lotação
T1Y|14|T1Y_DLOTAC|C|220|0|Desc.Lotação|Descrição da Lotação
T1Y|15|T1Y_VBCP15|N|15|2|Base C.P. 15|Base Contr. Prev. 15
T1Y|16|T1Y_VBCP20|N|15|2|Base C.P. 20|Base Contr. Prev. 20
T1Y|17|T1Y_VBCP25|N|15|2|Base C.P. 25|Base Contr. Prev. 25
--- ### T1Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T1Z|01|T1Z_FILIAL|C|6|0|Filial|Filial
T1Z|02|T1Z_ID|C|6|0|ID| Identificador do registr
T1Z|03|T1Z_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T1Z|04|T1Z_INSCES|C|14|0|Nr.Inscrição|Numero da Inscrição
T1Z|05|T1Z_INDAQU|C|1|0|Id.Aquisição|Indicativo da Aquisição
T1Z|06|T1Z_INSCPR|C|14|0|Nr.Inscrição|Numero da Inscrição
T1Z|07|T1Z_IDPROC|C|6|0|Proc. Judic.|Processo Judicial
T1Z|08|T1Z_DESCPR|C|220|0|Desc Proc J.|Desc. Processo Judicial
T1Z|09|T1Z_VLRPRV|N|15|2|   Vlr. Cont|Vlr Contr Previdenciária
T1Z|10|T1Z_VLRRAT|N|15|2|Vlr. Cont. R|Vlr Contribuição Gilrat
T1Z|11|T1Z_VLRSEN|N|15|2|Vlr Cont Sen|Vlr Contribuição Senar
T1Z|12|T1Z_CODSUS|C|14|0|Cod. Susp.|Código de Suspensão
T1Z|13|T1Z_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
--- ### T20
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T20|01|T20_FILIAL|C|6|0|Filial|Filial
T20|02|T20_ID|C|36|0|ID|Identificador do Registro
T20|03|T20_DTMOV|D|8|0|Dt. Moviment|Data Movimentação
T20|04|T20_CODITO|C|36|0|ID. Item Ori|Id. Item Origem
T20|05|T20_ITORIG|C|60|0|Item Origem|Código do item de Origem
T20|06|T20_DESITO|C|220|0|Descri. Item|Descrição Item Origem
T20|07|T20_CODITD|C|36|0|ID. Item Des|Id. Item Destino
T20|08|T20_ITDEST|C|60|0|Item Destino|Código do Item de Destino
T20|09|T20_DESITD|C|220|0|Descri. Item|Descrição do Item
T20|10|T20_QTDMOV|N|16|3|Qtd.Mov. Ori|Quantidade Movimentada
T20|11|T20_QTDMDE|N|16|3|Qtd.Mov.Dest|Qtd Movimentada Destino.
--- ### T21
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T21|01|T21_FILIAL|C|6|0|Filial|Filial
T21|02|T21_ID|C|36|0|ID|Identificador do Registro
T21|03|T21_DTINIO|D|8|0|Dt. Ini. OP|Data Inicio Ordem Prod
T21|04|T21_DTFINO|D|8|0|Dt. Fim. OP|Dt. Final. Ordem Prod.
T21|05|T21_CODOP|C|30|0|Ordem Prod.|Ordem Produção
T21|06|T21_CODITE|C|36|0|ID. Item|ID. Item
T21|07|T21_ITEM|C|60|0|Cód. Item|Código do Item
T21|08|T21_DESITE|C|220|0|Descri. Item|Descrição do Item
T21|09|T21_QTDPRO|N|16|3|Qtd Produção|Qtd. Produção Acabada
--- ### T22
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T22|01|T22_FILIAL|C|6|0|Filial|Filial
T22|02|T22_ID|C|36|0|ID|Identificador do Registro
T22|03|T22_CODOP|C|30|0|Cod. OP.|Código Ordem Produção
T22|04|T22_CODITE|C|36|0|Id. do Item|Id. do Item
T22|05|T22_DTSAID|D|8|0|Dt. Saída|Data Saída
T22|06|T22_CODINS|C|36|0|Id. Ins/Cons|Id. Insumo/Componente
T22|07|T22_ITINSU|C|60|0|Cód. Insumo|Código do Item de Insumo
T22|08|T22_DESINS|C|220|0|Desc. Insumo|Descrição Item Insumo
T22|09|T22_QTDCON|N|16|3|Qtd. Consum.|Quantidade Consumida
T22|10|T22_INSSUB|C|36|0|Id. Ins. Sub|Identificador Insumo Subs
T22|11|T22_ITSUBS|C|60|0|Insumo Subst|Insumo Substituído
T22|12|T22_DEINSS|C|220|0|Insumo Subst|Descr. Insumo Substituído
--- ### T23
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T23|01|T23_FILIAL|C|6|0|Filial|Filial
T23|02|T23_ID|C|36|0|ID|Identificador do Registro
T23|03|T23_DTPROD|D|8|0|Dt. Produção|Data. Produção Terceiro
T23|04|T23_CODITE|C|36|0|Id. do Item|Id. Item Produzido
T23|05|T23_ITEM|C|60|0|Item Produz.|Código do Item Produzido
T23|06|T23_DESITE|C|220|0|Descr. Item|Descrição do Item
T23|07|T23_QTDPRO|N|16|3|Qtd. Produz.|Quantidade Produzida
--- ### T24
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T24|01|T24_FILIAL|C|6|0|Filial|Filial
T24|02|T24_ID|C|36|0|iD|Identificador do Registro
T24|03|T24_DTPROD|D|8|0|Dt. Produção|Data. Produção Terceiro
T24|04|T24_CODITE|C|36|0|Id. do Item|Id. Item Produzido
T24|05|T24_DTCONS|D|8|0|Dt Cons Item|Dt. Consumo Item
T24|06|T24_ITECON|C|36|0|Item Insumo|Item Insumo
T24|07|T24_ITINSU|C|60|0|Item Insumo|Código do Item de Insumo
T24|08|T24_DESITI|C|220|0|Desc Insumo|Desc. Item Insumo
T24|09|T24_QTDINS|N|16|3|Qtd. Insumo|Qtd. Consumo Insumo
T24|10|T24_INSSUB|C|36|0|Insumo Subst|Insumo Substituído
T24|11|T24_ITSUBS|C|60|0|Insumo Subst|Insumo Substituído
T24|12|T24_DEINSS|C|220|0|Desc. Insumo|Desc. Insumo Substituído.
--- ### T25
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T25|01|T25_FILIAL|C|6|0|Filial|Filial
T25|02|T25_ID|C|36|0|ID|Identificador do Registro
T25|03|T25_IDINSU|C|36|0| Id. Insumo|Id. Item Componente/Insum
T25|04|T25_INSUMO|C|60|0|Componen.|Item Componente/Insum
T25|05|T25_DESINS|C|220|0|Desc. Insumo|Desc. Componente/Insumo
T25|06|T25_QTDITE|N|16|6|Qtd. Compone|Qtd. Componente/Insumo
T25|07|T25_PERDA|N|16|4|Perc. Perda|Percentual de Perda.
--- ### T26
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T26|01|T26_FILIAL|C|6|0|Filial|Filial
T26|02|T26_ID|C|36|0|ID|Identificador do Registro
T26|03|T26_CODIGO|C|2|0|Código|Código do Tributo
T26|04|T26_DESCRI|C|220|0|Descrição|Descrição do Tributo
--- ### T27
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T27|01|T27_FILIAL|C|6|0|Filial|Filial
T27|02|T27_ID|C|36|0|ID|Identificador do Registro
T27|03|T27_PERIOD|D|8|0|Período|Período
T27|04|T27_NUMDOS|C|32|0|Núm e-Dossiê|Número do e-Dossiê
T27|05|T27_DTINAT|D|8|0|Data Ini Ato|Data de Início de Ato
T27|06|T27_DTFNAT|D|8|0|Dt Fn Ato|Data Final de Ato
T27|07|T27_ANOINI|C|4|0|Ano Inicial|Ano-calendário Inicial
T27|08|T27_ANOFIN|C|4|0|Ano Final|Ano-calendário Final
T27|09|T27_INDODB|C|1|0|Oper Dep Bra|Oper Partes Dep Brasil
T27|10|T27_INDODE|C|1|0|Oper Dep Ext|Oper Partes Dep Exterior
T27|11|T27_INDOER|C|1|0|Oper Dep Res|Oper Dep Ext Residentes
T27|12|T27_INDOIB|C|1|0|Oper Ind Bra|Oper Partes Ind Brasil
T27|13|T27_INDOIE|C|1|0|Oper Ind Ext|Oper Partes Ind Exterior
T27|14|T27_INDOID|C|1|0|Oper Ind Res|Oper Ind Ext Residentes
T27|15|T27_INDGAF|C|1|0|Ger Ativ Fis|Geração de Ativo Fiscal
T27|16|T27_INDRSO|C|1|0|Reorg Soc|Reorganização Societária
T27|17|T27_INDGPT|C|1|0|Ger Pas Terc|Geração Passivo Terceiros
T27|18|T27_INDBGP|C|1|0|Ben Ger Pas|Beneficiários Ger Pas Ter
T27|19|T27_INDRBT|C|1|0|Red Bas Trib|Redução Base Tributária
T27|20|T27_INDRAT|C|1|0|Red Ativos|Redução de Ativos
T27|21|T27_PERCRA|N|6|2|Perc Red At|Percentual Redução Ativos
T27|22|T27_DSCSUM|M|10|0|Desc Sumária|Descrição Sumária Fatos
T27|23|T27_FUNJUR|M|10|0|Fund Jur|Fundamentação Jurídica
T27|24|T27_JSTSUM|M|10|0|Just Sumária|Justificativa Sumária
T27|25|T27_STATUS|C|1|0|Status Reg|Status do Registros
--- ### T28
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T28|01|T28_FILIAL|C|6|0|Filial|Filial
T28|02|T28_ID|C|36|0|ID|Identificador do Registro
T28|03|T28_CODTRB|C|2|0|Cód Tributo|Código do Tributo
T28|04|T28_DCODTR|C|220|0|Desc Tributo|Descrição do Tributo
T28|05|T28_IDCODT|C|36|0|ID Cód Trib|ID Código do Tributo
T28|06|T28_VLRTRB|N|16|2|Vlr Tributo|Valor Repercussão Tributo
T28|07|T28_ANOTRB|C|4|0|Ano Tributo|Ano Repercussão Tributo
--- ### T29
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T29|01|T29_FILIAL|C|6|0|Filial|Filial
T29|02|T29_ID|C|36|0|ID|Identificador do Registro
T29|03|T29_PERIOD|D|8|0|Período|Período
T29|04|T29_VLRLUC|N|16|2|Luc Líquido|Lucro Líquido
T29|05|T29_DTLUCL|D|8|0|Dt Apur Luc|Data Final Apuração Lucro
T29|06|T29_VLRREC|N|16|2|Rec Bruta|Receita Bruta Período Ant
T29|07|T29_STATUS|C|1|0|Status Reg|Status do Registro
T29|08|T29_ITMCAO|C|1|0|Intimação|Intimação
T29|09|T29_INTATR|C|1|0|Int. Atraso|Int. Atraso
--- ### T2A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2A|01|T2A_FILIAL|C|6|0|Filial|Filial
T2A|02|T2A_ID|C|6|0|ID|Identificador do registro
T2A|03|T2A_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do Registro
T2A|04|T2A_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T2A|05|T2A_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T2A|06|T2A_EVENTO|C|1|0|Id. Evento|Identificação do evento
T2A|07|T2A_STATUS|C|1|0|Status Reg.|Status do registro
T2A|08|T2A_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T2A|09|T2A_PROTUL|C|44|0|Ult. Prot.|Prot. última transmissão
T2A|10|T2A_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transmiss
T2A|11|T2A_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T2A|12|T2A_STASEC|C|1|0|Status Sec.|Status Secundario
T2A|13|T2A_XMLID|C|36|0|Id do XML.|Id do XML
T2A|14|T2A_LOGOPE|C|1|0|Log Operacao|Log Operacao
T2A|15|T2A_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T2A|16|T2A_TPGUIA|C|1|0|Tipo de guia|Indicativo tipo de guia
T2A|17|T2A_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T2A|18|T2A_HTRANS|C|8|0|Hr. Trans|Hora Transmissão
T2A|19|T2A_DTRECP|D|8|0|Dt. Recept|Data Receptação
T2A|20|T2A_HRRECP|C|8|0|Hr. Recept|Hora Receptação
--- ### T2D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2D|01|T2D_FILIAL|C|6|0|filial|filial
T2D|02|T2D_ID|C|36|0|ID|Identificador do Registro
T2D|03|T2D_IDMUN|C|6|0|ID Munic.|ID Município
T2D|04|T2D_TPCLAS|C|20|0|Tipo Classif|Tipo de Classificação
T2D|05|T2D_CODMUN|C|20|0|Cod. Municip|Código do Município
--- ### T2E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2E|01|T2E_FILIAL|C|6|0|Filial|Filial
T2E|02|T2E_ID|C|6|0|Id. Func.|Ident. do Funcinário
T2E|03|T2E_VERSAO|C|14|0|Id. Ver. Reg|Id da Versao do Registro
T2E|04|T2E_IDDEP|C|6|0|ID|Identificador do Registro
T2E|05|T2E_TPDEP|C|6|0|Id Tp Dep|Id. Tipo Dependente
T2E|06|T2E_DTPDE|C|220|0|Descr Tp Dep|Descricao Tipo Dependente
T2E|07|T2E_NOMDEP|C|70|0|Nome Dep.|Nome Dependente
T2E|08|T2E_DTNASC|D|8|0|Dt. Nasc.|Data Nascimento
T2E|09|T2E_CPFDEP|C|11|0|CPF Dep.|CPF Dependente
T2E|10|T2E_DEPIRF|C|1|0|Dep. IRRF?|Dependente IRRF?
T2E|11|T2E_DEPSFA|C|1|0|Dep Sal Fam?|Dep. Salario Familia?
T2E|12|T2E_DPFPR|C|1|0|Dep Fins Pre|Dep. Fins Prev.
T2E|13|T2E_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T2E|14|T2E_DPPLPS|C|1|0|Dep. Pl. Pri|Dependente Plano Privado?
T2E|15|T2E_INCTRB|C|1|0|Incapac.Trab|Incapacidade p/ Trabalho
--- ### T2F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2F|01|T2F_FILIAL|C|6|0|Filial|Filial
T2F|02|T2F_ID|C|6|0|Id. Func.|Id. do Funcionário
T2F|03|T2F_VERSAO|C|14|0|Id. Ver. Reg|Id da Versao do Registro
T2F|04|T2F_IDDEP|C|6|0|ID|Identificador do Registro
T2F|05|T2F_TPDEP|C|6|0|Id Tp Dep|Id. Tipo Dependente
T2F|06|T2F_DTPDE|C|220|0|Descr Tp Dep|Descricao Tipo Dependente
T2F|07|T2F_NOMDEP|C|70|0|Nome Dep.|Nome Dependente
T2F|08|T2F_DTNASC|D|8|0|Dt. Nasc.|Data Nascimento
T2F|09|T2F_CPFDEP|C|11|0|CPF Dep.|CPF Dependente
T2F|10|T2F_DEPIRF|C|1|0|Dep. IRRF?|Dependente IRRF?
T2F|11|T2F_DEPSFA|C|1|0|Dep Sal Fam?|Dep. Salario Familia?
T2F|12|T2F_DEPFPR|C|1|0|Dep Fins Pre|Dep. Fins Prev.
T2F|13|T2F_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T2F|14|T2F_DPPLPS|C|1|0|Dep. Pl. Pri|Dependente Plano Privado?
T2F|15|T2F_INCTRB|C|1|0|Incapac.Trab|Incapacidade p/ Trabalho
T2F|16|T2F_DESDEP|C|100|0|Dependência|Descrição da Dependência
--- ### T2G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2G|01|T2G_FILIAL|C|6|0|Filial|Filial
T2G|02|T2G_ID|C|6|0|ID|Identificador do Registro
T2G|03|T2G_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2G|04|T2G_NISV|C|11|0|NIS|NIS
T2G|05|T2G_NOMEV|C|70|0|Nome|Nome
T2G|06|T2G_MATV|C|30|0|Matricula|Matricula
T2G|07|T2G_CPFV|C|11|0|CPF|CPF
T2G|08|T2G_RECBAS|C|44|0|Rec.Arq.Base|Num. Recibo Arquivo Base
T2G|09|T2G_PERAPU|C|6|0|Per.Apur.|Período Apuração
T2G|10|T2G_CPFTRA|C|11|0|CPF|CPF do Trabalhador
T2G|11|T2G_VERANT|C|14|0|Ver Ant Reg|Versão Anterior  Registro
T2G|12|T2G_STATUS|C|1|0|Status Reg.|Status do  Registro
T2G|13|T2G_VRDEDD|N|15|2|Vlr Ded Base|Vlr Dedução Base Dependen
T2G|14|T2G_PROTUL|C|44|0|Últ. Prot.|Prot. Última  Transmissão
T2G|15|T2G_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima  Transm.
T2G|16|T2G_EVENTO|C|1|0|Id. Evento|Identificação do  Evento
T2G|17|T2G_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T2G|18|T2G_LOGOPE|C|1|0|Log Operacao|Log Operacao
T2G|19|T2G_CPFBEN|C|11|0|CPF|CPF Trabalhador
T2G|20|T2G_LAYOUT|C|30|0|Layout|Layout
T2G|21|T2G_DTLAUD|D|8|0|Data Laudo|Data Laudo
T2G|22|T2G_CHKDIR|L|1|0|Check DIrf|Check DIrf
--- ### T2H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2H|01|T2H_FILIAL|C|6|0|Filial|Filial
T2H|02|T2H_ID|C|6|0|ID|Identificador do Registro
T2H|03|T2H_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2H|04|T2H_SEQUEN|C|3|0|Sequencia|Sequencia
T2H|05|T2H_CODCAT|C|6|0|Id. Categ.|Id. Categoria
T2H|06|T2H_DCODCA|C|220|0|Des. Categ.|Descrição da Categoria
T2H|07|T2H_INDRES|C|1|0|Ind Resid BR|Indicar Residente BR
T2H|08|T2H_IDPAIS|C|6|0|ID. Pais|ID. Pais
T2H|09|T2H_DPAIS|C|220|0|Desc. Pais|Desc. Pais
T2H|10|T2H_INDNIF|C|1|0|Ind. NIF|Ind. Nr. Id. Fiscal
T2H|11|T2H_NIFBEN|C|20|0|NIF Benf.|NIF do Benefic.
T2H|12|T2H_DLOUGR|C|100|0|Des. Logr.|Des. Logradouro
T2H|13|T2H_NUMLOG|C|10|0|Nr. Log.|Numero Logradouro
T2H|14|T2H_COMPLE|C|30|0|Complemento|Complemento
T2H|15|T2H_BAIRRO|C|90|0|Bairro|Bairro
T2H|16|T2H_CIDADE|C|50|0|Cidade|Cidade
T2H|17|T2H_CEP|C|12|0|CEP|CEP
--- ### T2I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2I|01|T2I_FILIAL|C|6|0|Filial|Filial
T2I|02|T2I_ID|C|6|0|ID|Identificador do Registro
T2I|03|T2I_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2I|04|T2I_SEQUEN|C|3|0|Sequencia|Sequencia
T2I|05|T2I_CODCAT|C|6|0|Id. Categ.|Id. Categoria
T2I|06|T2I_INDRES|C|1|0|Ind Resid BR|Indicar Residente BR
T2I|07|T2I_CTPVAL|C|6|0|Id. Tp. Val.|Id. Tipo Valor
T2I|08|T2I_DTPVAL|C|220|0|Des.Tp.Val|Descrição Tipo Valor
T2I|09|T2I_VLIRRF|N|15|2|Vl.Base IRRF|Valor Base IRRF
T2I|10|T2I_INDDEV|C|30|0|Iden Dem Pgt|Iden Dem Pgt
T2I|11|T2I_TPPAG|C|1|0|Tipo Pgto.|Tipo de Pagamento
T2I|12|T2I_PERREF|C|6|0|Periodo Ref.|Período de Referência
T2I|13|T2I_DESCRE|C|100|0|Desc. Rend.|Descrição do rendimento
--- ### T2J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2J|01|T2J_FILIAL|C|6|0|Filial|Filial
T2J|02|T2J_ID|C|6|0|ID|Identificador do Registro
T2J|03|T2J_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2J|04|T2J_SEQUEN|C|3|0|Sequencia|Sequencia
T2J|05|T2J_CODCAT|C|6|0|Id. Categ.|Id. Categoria
T2J|06|T2J_INDRES|C|1|0|Ind Resid BR|Indicar Residente BR
T2J|07|T2J_CTPCR|C|6|0|Id. Tp. CR.|Id. Tipo Cod.Receita
T2J|08|T2J_DTPCR|C|220|0|Des.Tp.CR.|Desc. Tipo Código Receita
T2J|09|T2J_VLDESC|N|15|2|Vl.IRRF Desc|Valor IRRF Descontado
T2J|10|T2J_CODREC|C|6|0|Cod Receita|Código da Receita
--- ### T2L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2L|01|T2L_FILIAL|C|6|0|Filial|Filial
T2L|02|T2L_ID|C|6|0|ID|Identificador do registro
T2L|03|T2L_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2L|04|T2L_INDAPU|C|1|0|Ind. Apuraçã|Ind. Período Apuração
T2L|05|T2L_PERAPU|C|6|0|Per Apuração|Período Apuração
T2L|06|T2L_CNPJSD|C|14|0|CNPJ Ent Sin|CNPJ da Ent Sind Ben
T2L|07|T2L_TPCONT|C|1|0|Tp Cont Sind|Tipo de Contribuição Sind
T2L|08|T2L_DTRECO|D|8|0|Dt Cont Sind|Data de Contribuição Sind
T2L|09|T2L_VLRCS|N|15|2|Vlr Cont Sin|Vlr Contribuição Sindical
T2L|10|T2L_VLRECS|N|14|2|Vlr Enc. Inc|Valor dos Encargos Incide
--- ### T2M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2M|01|T2M_FILIAL|C|6|0|Filial|Filial
T2M|02|T2M_ID|C|6|0|ID|Identificador do Registro
T2M|03|T2M_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T2M|04|T2M_INDAPU|C|1|0|Ind.Per.Apur|Indic. Período Apuração
T2M|05|T2M_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T2M|06|T2M_NRRECI|C|44|0|Rec.Arq.Base|Num. Recibo Arquivo Base
T2M|07|T2M_CPFTRB|C|11|0|CPF|CPF do Trabalhador
T2M|08|T2M_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T2M|09|T2M_STATUS|C|1|0|Status Reg.|Status do Registro
T2M|10|T2M_PROTUL|C|44|0|Ult. Prot.|Prot. Última Transmissão
T2M|11|T2M_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T2M|12|T2M_LOGOPE|C|1|0|Log Operacao|Log Operacao
T2M|13|T2M_NISV|C|11|0|NIS|NIS
T2M|14|T2M_MATV|C|30|0|Matricula|Matricula
T2M|15|T2M_NOMEV|C|70|0|Nome|Nome
T2M|16|T2M_IDEVEN|C|6|0|Id Ev Orig|Identificador Evento Orig
--- ### T2N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2N|01|T2N_FILIAL|C|6|0|Filial|Filial
T2N|02|T2N_ID|C|6|0|ID|Identificador do Registro
T2N|03|T2N_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T2N|04|T2N_IDPROC|C|6|0|Id. Processo|Id. Processo Judicial
T2N|05|T2N_NPROCJ|C|21|0|Núm.Proc.|Núm. Processo Judicial
T2N|06|T2N_NPROCR|C|21|0|Núm.Proc.|Núm. Processo Judicial
T2N|07|T2N_CODSUS|C|14|0|Cod. Susp|Cod Indic Suspensao
T2N|08|T2N_CODSUR|C|14|0|Cod. Susp.|Cod Indic Suspensao
T2N|09|T2N_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
--- ### T2O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2O|01|T2O_FILIAL|C|6|0|Filial|Filial
T2O|02|T2O_ID|C|6|0|ID|Identificador do Registro
T2O|03|T2O_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T2O|04|T2O_IDCODR|C|6|0|Id. Cód. Rec|Id. Código da Receita
T2O|05|T2O_DCODRE|C|220|0|Desc Cod Rec|Descrição do Código da Re
T2O|06|T2O_DCODRR|C|220|0|Desc Cod Rec|Descriçao do Código da Re
T2O|07|T2O_VRCPSE|N|15|2|Vlr Segurado|Valor do Segurado
T2O|08|T2O_VRDESC|N|15|2|Vlr Desc Seg|Valor Descontado do Segur
--- ### T2P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2P|01|T2P_FILIAL|C|6|0|Filial|Filial
T2P|02|T2P_ID|C|6|0| ID|Identificador do Registro
T2P|03|T2P_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T2P|04|T2P_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T2P|05|T2P_DESTAB|C|220|0|Desc. Estab.|Descrição do Estabelecime
T2P|06|T2P_DESTAR|C|220|0|Desc. Estab.|Descriçao do Estabelecime
T2P|07|T2P_LOTACA|C|6|0|Id. Lotação|Id. da Lotação Tributária
T2P|08|T2P_DLOTAC|C|220|0|Desc Lotação|Descrição da Lotação
T2P|09|T2P_DLOTAR|C|220|0|Desc Lotaçao|Descriçao da Lotaçao
T2P|10|T2P_CLATRI|C|6|0|Class. Trib|Classificação Tributária
T2P|11|T2P_DESCLA|C|220|0|Des.Clas.Tri|Desc. Class. Tributária
T2P|12|T2P_CODLOT|C|30|0|Cod. Lotacao|Codigo da Lotacao
T2P|13|T2P_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T2P|14|T2P_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
T2P|15|T2P_SEQUEN|C|3|0|Sequência|Sequência Estabelecimento
--- ### T2Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2Q|01|T2Q_FILIAL|C|6|0|Filial|Filial
T2Q|02|T2Q_ID|C|6|0|ID|Identificador do Registro
T2Q|03|T2Q_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T2Q|04|T2Q_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T2Q|05|T2Q_LOTACA|C|6|0|Id. Lotação|Id. da Lotação Tributária
T2Q|06|T2Q_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T2Q|07|T2Q_CODCAT|C|6|0|Cod. Categor|Codigo Categoria
T2Q|08|T2Q_DCODCA|C|220|0|Des. Categor|Des. Categoria
T2Q|09|T2Q_DCODCR|C|220|0|Des. Categor|Des. Categoria
T2Q|10|T2Q_INDCON|C|1|0|Ind. C. Subs|Ind. Contribuição Substit
T2Q|11|T2Q_CODLOT|C|30|0|Cod. Lotacao|Codigo da Lotacao
T2Q|12|T2Q_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T2Q|13|T2Q_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
--- ### T2R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2R|01|T2R_FILIAL|C|6|0|Filial|Filial
T2R|02|T2R_ID|C|6|0|ID|Identificador do Registro
T2R|03|T2R_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T2R|04|T2R_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T2R|05|T2R_LOTACA|C|6|0|Id. Lotação|Id. da Lotação Tributária
T2R|06|T2R_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T2R|07|T2R_CODCAT|C|6|0|Cod. Categor|Codigo da Categoria
T2R|08|T2R_INDDEC|C|1|0|Ind. Décimo|Indicativo Décimo Tercei
T2R|09|T2R_TPVLR|C|6|0|Id. Tipo Val|Tipo Valor da Apuração
T2R|10|T2R_DTPVLR|C|220|0|Desc Tp Val|Descrição do Tipo do Valo
T2R|11|T2R_DTPVRR|C|220|0|Desc Tp Val|Descriçao do Tipo do Valo
T2R|12|T2R_VALOR|N|15|2|Valor|Valor
T2R|13|T2R_CODLOT|C|30|0|Cod. Lotacao|Codigo da Lotacao
T2R|14|T2R_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T2R|15|T2R_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
--- ### T2S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2S|01|T2S_FILIAL|C|6|0|Filial|Filial
T2S|02|T2S_ID|C|6|0|ID|Identificador do Registro
T2S|03|T2S_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T2S|04|T2S_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T2S|05|T2S_LOTACA|C|6|0|Id. Lotação|Id. da Lotação Tributária
T2S|06|T2S_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T2S|07|T2S_CODCAT|C|6|0|Cod. Categor|Codigo da Categoria
T2S|08|T2S_IDCODR|C|6|0|Id. Cód. Rec|Id. Código da Receita
T2S|09|T2S_DCODRE|C|220|0|Desc Cod Rec|Descrição do Código da Re
T2S|10|T2S_DCODRR|C|220|0|Desc Cod Rec|Descriçao do Código da Re
T2S|11|T2S_VLRCON|N|15|2|Vlr Contrib.|Valor da Contrib Social
T2S|12|T2S_VLRDES|N|15|2|Valor Desc|Valor Descontado
--- ### T2T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2T|01|T2T_FILIAL|C|6|0|Filial|Filial
T2T|02|T2T_ID|C|6|0|ID|Identificador do Registro
T2T|03|T2T_CODIGO|C|2|0|Código|Código
T2T|04|T2T_DESCRI|C|220|0|Descrição|Descrição
T2T|05|T2T_VALIDA|D|8|0|Data Vigenc.|Data final da vigência
--- ### T2U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2U|01|T2U_FILIAL|C|6|0|Filial|Filial do Sistema
T2U|02|T2U_ID|C|36|0|ID|ID
T2U|03|T2U_ESCOPO|C|1|0|Escopo|Escopo
T2U|04|T2U_CODIGO|C|3|0|Código|Código da Tabela
T2U|05|T2U_DESCRI|C|100|0|Descrição|Descrição da Tabela
T2U|06|T2U_ROTINA|C|40|0|Rotina Owner|Nome da Rotina Owner
T2U|07|T2U_VERSAO|C|20|0|Versão|Versão da tabela
--- ### T2V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2V|01|T2V_FILIAL|C|6|0|Filial|Filial
T2V|02|T2V_ID|C|6|0|ID|Identificador do registro
T2V|03|T2V_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2V|04|T2V_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T2V|05|T2V_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T2V|06|T2V_IDARQB|C|40|0|Id Rec Arq|Id do Recibo do Arq
T2V|07|T2V_INDEXI|C|1|0|In Ex Val Bs|Ind Ex Valores Base e Con
T2V|08|T2V_VRDESC|N|14|2|Vlr Desc CP|Vlr Descon Cont Prev
T2V|09|T2V_VRCPSE|N|15|2|Vlr Cp Seg|Vlr Cal Rel Cont Segurado
T2V|10|T2V_IDCLAS|C|6|0|ID.Clas.Trib|Clas. Trib. Contribuinte
T2V|11|T2V_DCLASS|C|220|0|Des. Clas.Tr|Descr. Clas. Trib. Contri
T2V|12|T2V_DCLASR|C|220|0|Des. Clas.Tr|Descr. Clas. Trib. Contri
T2V|13|T2V_INDCOO|C|1|0|Ind. de Coop|Indicativo de Cooperativa
T2V|14|T2V_INDCON|C|1|0|Ind de Const|Indicativo de Construtora
T2V|15|T2V_INDPAT|C|1|0|Ind Cont Pre|Ind Sub Cont Prev Pat
T2V|16|T2V_PERCON|N|6|2|% Red Con Pr|% Red da Cont Prevista
T2V|17|T2V_FATMES|N|6|2|Fator Mês|Fator para Cal Cont Mês
T2V|18|T2V_FATDEC|N|6|2|Fator 13|Fator para Cal da Cont 13
T2V|19|T2V_STATUS|C|1|0|Status Reg.|Status do registro
T2V|20|T2V_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T2V|21|T2V_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T2V|22|T2V_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T2V|23|T2V_LOGOPE|C|1|0|Log Operacao|Log Operacao
T2V|24|T2V_PERCTR|C|1|0|Perc Contrib|Percent. Contrib Social
T2V|25|T2V_INDPIS|C|1|0|Ind. Trib. F|Ind Trib Folha Pis Cofins
T2V|26|T2V_LAYOUT|C|30|0|Layout|Layout
--- ### T2X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2X|01|T2X_FILIAL|C|6|0|Filial|Filial
T2X|02|T2X_ID|C|6|0|ID|Identificador do registro
T2X|03|T2X_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2X|04|T2X_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T2X|05|T2X_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T2X|06|T2X_CNAEPR|C|7|0|CNAE Prep.|CNAE Preponderante Estab.
T2X|07|T2X_ALIRAT|N|1|0|Alíq.Rat Est|Alíquota RAT
T2X|08|T2X_FAP|N|6|4|FAP|Fat. Acid. Prevenção
T2X|09|T2X_ALIAJU|N|6|4|Rat.Ajustada|Alíquota RAT Ajustada Est
T2X|10|T2X_INDPAT|C|1|0|Ind. Sub Pat|Ind Subst. Contrib. Patr.
T2X|11|T2X_FPAS|C|6|0|Id. Cod FPAS|Id. Código FPAS
T2X|12|T2X_DFPAS|C|220|0|Desc. FPAS|Descrição Código FPAS
T2X|13|T2X_CODTER|C|6|0|Cód Terceiro|Desc Código de Terceiro
T2X|14|T2X_VLREMU|N|14|2|Vlr. Remun|Valor da Remuneração
T2X|15|T2X_VLR13|N|14|2|Valor 13°|Valor do 13°
T2X|16|T2X_VLDESC|N|14|2|Vlr. Desc|Valor Total Descontado
T2X|17|T2X_CNPJRE|C|14|0|CNPJ Resp|CNPJ responsável
T2X|18|T2X_VRBPIS|N|14|2|Vlr. Pis.Pas|Valor PisPasesp
T2X|19|T2X_VRPISU|N|14|2|Vlr.Sup Pase|Vlr. Susp. PispPasep
--- ### T2Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2Y|01|T2Y_FILIAL|C|6|0|Filial|Filial
T2Y|02|T2Y_ID|C|6|0|ID|Identificador do registro
T2Y|03|T2Y_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2Y|04|T2Y_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T2Y|05|T2Y_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T2Y|06|T2Y_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T2Y|07|T2Y_CODLOT|C|30|0|Cód. Lotação|Código Lotação
T2Y|08|T2Y_CODLOR|C|30|0|Cód. Lotaçao|Código Lotaçao
T2Y|09|T2Y_FPAS|C|6|0|Id.Cod.FPAS|Código FPAS
T2Y|10|T2Y_DFPAS|C|220|0|Des.FPAS|Descrição FPAS
T2Y|11|T2Y_DFPASR|C|220|0|Des. FPAS|Descriçao FPAS
T2Y|12|T2Y_CODTER|C|4|0|Cod. Terc|Código de Terceiros
T2Y|13|T2Y_CODTRR|C|4|0|Cod. Terc|Código de Terceiros
T2Y|14|T2Y_TERSUS|C|4|0|Cod Ter Susp|Cód Terc Susp PJ
T2Y|15|T2Y_TPINCO|C|1|0|Tp.Insc.Cont|Tp Inscrição Contratante
T2Y|16|T2Y_NRINCO|C|14|0|Núm.Insc.Con|Núm inscrição Contratante
T2Y|17|T2Y_TPINPR|C|1|0|Tp.Insc.Prop|Tp Inscrição Proprietário
T2Y|18|T2Y_NRINPR|C|14|0|Núm.Insc.Pro|Núm insc. Proprietário
T2Y|19|T2Y_CNPJOP|C|14|0|CNPJ Op.Port|CNPJ Op. Portuário
T2Y|20|T2Y_ALIRAT|N|1|0|Aliq. Rat|Alíquota RAT
T2Y|21|T2Y_FAP|N|6|4|FAP|Fator Acident. Prevenção
T2Y|22|T2Y_ALRATF|N|6|4|Alq.Rat.Aju|Alíquota RAT Ajustada
T2Y|23|T2Y_VRBCCP|N|15|2|Vlr BC CP 00|Base de Cál da Cont Prev
T2Y|24|T2Y_VRBCCQ|N|15|2|Vlr Bc Cp 15|Vlr Base Cal Cont 15 anos
T2Y|25|T2Y_VRBCCV|N|15|2|Vlr Bc Cp 20|Vlr Base Cal Cont 20 anos
T2Y|26|T2Y_VRBCVQ|N|15|2|Vlr Bc Cp 25|Vlr Base Cal Cont 25 anos
T2Y|27|T2Y_VRBCCT|N|15|2|Vlr Bc Cp 13|Vlr Base Cal Cont 13º sal
T2Y|28|T2Y_VRBCFG|N|15|2|Vlr BC FGTS|Vlr Base Cal FGTS
T2Y|29|T2Y_VRDESC|N|15|2|Vlr Desc CP|Vlr Descontada
T2Y|30|T2Y_NRCNO|C|12|0|Num CNO Obra|Número do CNO da Obra.
T2Y|31|T2Y_DCODLO|C|30|0|Cód. Lota.|Código da Lotação
--- ### T2Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T2Z|01|T2Z_FILIAL|C|6|0|Filial|Filial
T2Z|02|T2Z_ID|C|6|0|ID|Identificador do registro
T2Z|03|T2Z_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T2Z|04|T2Z_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T2Z|05|T2Z_NRINSE|C|15|0|Nr Inscrição|Número de Inscrição
T2Z|06|T2Z_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T2Z|07|T2Z_INDINC|C|1|0|Tp. Incid.|Tipo de Incidência
T2Z|08|T2Z_CODCAT|C|6|0|Id. Cat|Id. Categoria
T2Z|09|T2Z_DCODCA|C|220|0|Des. Cat|Des Categoria
T2Z|10|T2Z_DCODCR|C|220|0|Des. Cat.|Des Categoria
T2Z|11|T2Z_VLBCCP|N|16|2|Vlr Base Cal|Valor Calc Cont Prev
T2Z|12|T2Z_VLBCAQ|N|16|2|Vl Cal Ad 15|Valor Cal Cont Ad após 15
T2Z|13|T2Z_VLBCAV|N|16|2|Vl Cal Ad 20|Valor Cal Cont Ad após 20
T2Z|14|T2Z_VLBCVC|N|16|2|Vl Cal Ad 25|Valor Cal Cont Ad após 25
T2Z|15|T2Z_VLSUBC|N|16|2|Vlr BC In Su|Valor BC Ind Susp
T2Z|16|T2Z_VLSUBQ|N|16|2|Vlr Bs Ca Co|Valor Base Calc Cont
T2Z|17|T2Z_VLSUBV|N|16|2|Vlr Su Bc 20|Valor Bs Cal Con 20 anos
T2Z|18|T2Z_VLSUVC|N|16|2|Vlr Su Bc 25|Valor Bs Cal Con 25 anos
T2Z|19|T2Z_VLDESE|N|16|2|Vlr Des Sest|Valor Total Des Trab Sest
T2Z|20|T2Z_VLCASE|N|16|2|Vlr Cal Sest|Valor Ca Con Trb Rec Sest
T2Z|21|T2Z_VLDESN|N|16|2|Vlr Des Sena|Valor Total Des Trb Senat
T2Z|22|T2Z_VLCASN|N|16|2|Vlr Cal Sena|Vlr Cal Cont Trb Senat
T2Z|23|T2Z_VLSAFA|N|16|2|Vlr Sal Fam|Valor Total Sal Família
T2Z|24|T2Z_VLSAMA|N|16|2|Vlr Sal Mat|Valor Total Sal Matern
T2Z|25|T2Z_DIDCAT|C|30|0|Id. Cat.|Id. Categoria
T2Z|26|T2Z_BC00VA|N|15|2|Contr. VA|Contrato Verde Amarelo
T2Z|27|T2Z_BC15VA|N|15|2|Contr. VA 15|Contrato Verde Amarelo 15
T2Z|28|T2Z_BC20VA|N|15|2|Contr. VA 20|Contrato Verde Amarelo 20
T2Z|29|T2Z_BC25VA|N|15|2|Contr. VA 25|Contrato Verde Amarelo 25
T2Z|30|T2Z_SB00VA|N|15|2|Susp BC VA|Suspensão BC VA
T2Z|31|T2Z_SB15VA|N|15|2|Sus BC VA 15|Suspensão BC VA 15
T2Z|32|T2Z_SB20VA|N|15|2|Sus BC VA 20|Suspensão BC VA 20
T2Z|33|T2Z_SB25VA|N|15|2|Sus BC VA 25|Suspensão BC VA 25
--- ### T30
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T30|01|T30_FILIAL|C|6|0|Filial|Filial
T30|02|T30_ID|C|36|0|ID|Identificador do Registro
T30|03|T30_PERIOD|C|8|0|Período|Período das movimentações
T30|04|T30_STATUS|C|1|0|Status Reg.|Status do registro
--- ### T31
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T31|01|T31_FILIAL|C|6|0|Filial|Filial
T31|02|T31_ID|C|36|0|ID|Identificador do Registro
T31|03|T31_CODPAR|C|36|0|ID Participa|Identificador do Particip
T31|04|T31_PARTIC|C|60|0|Participante|Código Participante
T31|05|T31_NOME|C|254|0|Nome|Nome do Participante
T31|06|T31_VLRFAT|N|13|2|Faturamento|Valor do faturamento
T31|07|T31_VLRDEB|N|13|2|Débitos|Débitos Faturados
--- ### T32
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T32|01|T32_FILIAL|C|6|0|Filial|Filial
T32|02|T32_ID|C|36|0|ID|Identificador do Registro
T32|03|T32_PERIOD|C|8|0|Período|Período das movimentações
T32|04|T32_STATUS|C|1|0|Status Reg.|Status do registro
--- ### T33
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T33|01|T33_FILIAL|C|6|0|Filial|Filial
T33|02|T33_ID|C|36|0|ID|Identificador do Registro
T33|03|T33_NDIV|N|15|0|Num Dívida|Número da Dívida
T33|04|T33_DESC|M|10|0|Descrição|Descrição da Dívida
T33|05|T33_VLRDIV|N|13|2|Valor|Valor da Compensação
T33|06|T33_CHVDIV|C|36|0|Chv da Divid|Chave da Divida
--- ### T34
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T34|01|T34_FILIAL|C|6|0|Filial|Filial do Sistema
T34|02|T34_ID|C|36|0|ID|Identificador do registro
T34|03|T34_CODAJU|C|5|0|Cod. Ajuste|Código do Ajuste
T34|04|T34_DESCRI|C|100|0|Desc. Ajuste|Descrição do Ajuste
T34|05|T34_TIPREG|C|1|0|Tp. Regime|Tipo do Regime
T34|06|T34_VALIDA|D|8|0|Dat. Valida|Data Valida
--- ### T35
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T35|01|T35_FILIAL|C|6|0|Filial|Filial do Sistema
T35|02|T35_ID|C|36|0|ID|Identificador do Registro
T35|03|T35_IDCODA|C|36|0|ID Ajuste|Identificação do Ajuste
T35|04|T35_CODAJU|C|5|0|Cod. Ajuste|Código do Ajuste
T35|05|T35_DCODAJ|C|220|0|Desc. Ajuste|Descrição do Ajuste
T35|06|T35_VLRAJU|N|16|2|Vlr Ajuste|Valor Ajuste
--- ### T36
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T36|01|T36_FILIAL|C|6|0|Filial|Filial do Sistema
T36|02|T36_ID|C|36|0|ID|Identificador do registro
T36|03|T36_IDCODI|C|36|0|ID Distrib|ID Distribuição
T36|04|T36_IDCODL|C|6|0|ID Localidad|Identificação Localidade
T36|05|T36_CODDIS|C|5|0|Cod. Distrib|Código da Distribuição
T36|06|T36_DESDIS|C|220|0|Desc.Distrib|Descrição da Distribuição
T36|07|T36_VLRDIS|N|16|2|Vlr Distrib|Valor Distribuição
T36|08|T36_CODLOC|C|8|0|Cod Localid|Código Localidade
T36|09|T36_DESLOC|C|220|0|Desc. Local|Descrição da Localidade
--- ### T37
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T37|01|T37_FILIAL|C|6|0|Filial|Filial do Sistema
T37|02|T37_ID|C|36|0|ID|Indentificação do Registr
T37|03|T37_CODDIS|C|5|0|Cod. Distrib|Código da Distribuição
T37|04|T37_DESCRI|C|100|0|Descrição|Descrição da Distribuição
T37|05|T37_TIPREG|C|1|0|Tip. Regime|Tipo de Regime
T37|06|T37_TIPPES|C|1|0|Tip. Pessoal|Tipo de Pessoa
T37|07|T37_VALIDA|D|8|0|Dat. Valida|Data Valida
--- ### T38
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T38|01|T38_FILIAL|C|6|0|FILIAL|FILIAL DO SISTEMA
T38|02|T38_ID|C|36|0|ID|Identificador do registro
T38|03|T38_MES|C|2|0|Mes|Mes
T38|04|T38_RECBRU|N|16|2|REC. BRUTA|Receita Bruta
T38|05|T38_RECEMP|N|16|2|Rec. Empresa|Receita Bruta da Empresa
T38|06|T38_TIPREG|C|1|0|Tip. Regime|Tipo do Regime
--- ### T39
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T39|01|T39_FILIAL|C|6|0|FILIAL|Filial
T39|02|T39_ID|C|36|0|ID|Indentificador do regist
T39|03|T39_PERINI|C|7|0|Per. Inicial|Periodo inicial para obri
T39|04|T39_ANOREF|C|4|0|Ano Ref.|Ano Referencia
T39|05|T39_TIPREG|C|1|0|Tip Regime|Tipo de Regime
T39|06|T39_PERFIN|C|7|0|Per. Final|Periodo Final da Obrig
T39|07|T39_STATUS|C|1|0|Status Reg.|Status do Registro
T39|08|T39_ATODEC|C|30|0|Ato Decl.|Número ato declaratório
--- ### T3A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3A|01|T3A_FILIAL|C|6|0|Filial|Filial
T3A|02|T3A_ID|C|6|0|ID|Identificador do registro
T3A|03|T3A_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3A|04|T3A_CPF|C|11|0|CPF|CPF do Funcionário
T3A|05|T3A_DTNASC|D|8|0|Dt. Nasc.|Data Nasc. Funcionário
T3A|06|T3A_DTADMI|D|8|0|Dt. Admissão|Data Admissão
T3A|07|T3A_STATUS|C|1|0|Status Reg|Status do registro
T3A|08|T3A_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T3A|09|T3A_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T3A|10|T3A_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T3A|11|T3A_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3A|12|T3A_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T3A|13|T3A_STASEC|C|1|0|Status Sec.|Status Secundario
T3A|14|T3A_XMLID|C|36|0|Id do XML.|Id do XML
T3A|15|T3A_LOGOPE|C|1|0|Log Operacao|Log Operacao
T3A|16|T3A_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T3A|17|T3A_CODCBO|C|6|0|Cód.Ocupação|Código da Ocupação
T3A|18|T3A_DCODCB|C|220|0|Desc.Ocupac.|Descrição da Ocupação
T3A|19|T3A_VLSLFX|N|16|2|Vlr Sal Fixo|Valor Salario Fixo
T3A|20|T3A_UNSLFX|C|1|0|Und Sal Fixo|Unidade Salario Fixo
T3A|21|T3A_TPCONT|C|1|0|Tp. Contrato|Tipo Contrato
T3A|22|T3A_DTTERM|D|8|0|Dt Term Con|Data Termino Contrato
T3A|23|T3A_MATRIC|C|30|0|Matricula|Matricula do Funcionario
T3A|24|T3A_CODCAT|C|6|0|Cod. Categor|Codigo Categoria
T3A|25|T3A_DCATEG|C|220|0|Des Categ|Des. Categoria
T3A|26|T3A_NATATV|C|1|0|Nat.Atividad|Natureza da Atividade
T3A|27|T3A_DTRANS|D|8|0|Dt. Transm|Data Transmissao
T3A|28|T3A_HTRANS|C|8|0|Hr. Transm|Hora Transmissao
T3A|29|T3A_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T3A|30|T3A_HRRECP|C|8|0|Hr. Recept|Hora Receptacao
--- ### T3B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3B|01|T3B_FILIAL|C|6|0|Filial|Filial
T3B|02|T3B_ID|C|6|0|ID|Identificador do Registro
T3B|03|T3B_VERSAO|C|14|0|Id. Ver. Reg|Id. Versão do Registro
T3B|04|T3B_IDTRAB|C|6|0|Id.Trabalhad|Identificador Trabalhador
T3B|05|T3B_NOMTRB|C|220|0|Nome Trab.|Nome Trabalhador
T3B|06|T3B_DTINI|D|8|0|Dt. Início|Data Início Insalub./Peri
T3B|07|T3B_DTALT|D|8|0|Dt Alteração|Dt.Alteração Insalub./Per
T3B|08|T3B_DTFIN|D|8|0|Dt. Final|Data Final Insalub./Peric
T3B|09|T3B_DTINIA|D|8|0|Dt. Ini. Apo|Dt. Inicio Aposent.Espec.
T3B|10|T3B_DTALTA|D|8|0|Dt. Alt. Apo|Dt. Alteração Aposen. Esp
T3B|11|T3B_DTFINA|D|8|0|Dt. Fin.Apos|Dt. Final Aposent. Espec.
T3B|12|T3B_EVENTO|C|1|0|Id. Evento|Identificador do Evento
T3B|13|T3B_STATUS|C|1|0|Status Reg.|Status do Registro
T3B|14|T3B_VERANT|C|14|0|Ver Ant Reg.|Versão Anterior Registro
T3B|15|T3B_PROTUL|C|44|0|Ult. Prot.|Prot. Última Transmissão
T3B|16|T3B_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transmiss
T3B|17|T3B_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3B|18|T3B_LOGOPE|C|1|0|Log Operacao|Log Operacao
T3B|19|T3B_STASEC|C|1|0|Status Sec.|Status Secundario
T3B|20|T3B_XMLID|C|36|0|Id do XML.|Id do XML
T3B|21|T3B_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T3B|22|T3B_DTRANS|D|8|0|Dt. Transm|Data Transmissao
T3B|23|T3B_HTRANS|C|8|0|Hr. Transm|Hora Transmissao
T3B|24|T3B_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T3B|25|T3B_HRRECP|C|8|0|Hr. Recept|Hora Receptacao
--- ### T3C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3C|01|T3C_FILIAL|C|6|0|Filial|Filial
T3C|02|T3C_ID|C|6|0|ID|Identificador do Registro
T3C|03|T3C_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T3C|04|T3C_IDAMB|C|6|0|Cód.Ambiente|Código do Ambiente
T3C|05|T3C_DESAMB|C|220|0|Des.Ambiente|Descrição do Ambiente
T3C|06|T3C_FIMAMB|C|1|0|Finaliz. Amb|Finalizada Atividade Amb.
--- ### T3D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3D|01|T3D_FILIAL|C|6|0|Filial|Filial
T3D|02|T3D_ID|C|6|0|ID|Identificador do Registro
T3D|03|T3D_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3D|04|T3D_IDAMB|C|6|0|Cód.Ambiente|Código Ambiente Trabalho
T3D|05|T3D_IDFATR|C|6|0|Fator Risco|Id. Fator Risco
T3D|06|T3D_DESFAT|C|220|0|Des.Fat.Risc|Des. Fator de Risco
T3D|07|T3D_INTEXP|C|15|0|Intens. Expo|Intens./Concentração Expo
T3D|08|T3D_TECMED|C|40|0|Téc. Medição|Téc. Utilizada Medição
--- ### T3E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3E|01|T3E_FILIAL|C|6|0|Filial|Filial
T3E|02|T3E_ID|C|6|0|ID|Identificador de Registro
T3E|03|T3E_CODIGO|C|10|0|Cod. Fator|Código do Fator de Risco
T3E|04|T3E_DESCRI|C|220|0|Descrição|Descrição Fator de Risco
T3E|05|T3E_DOCUMT|C|10|0|Documento|Documento
T3E|06|T3E_TPRISC|C|6|0|Grupo Risco|Grupo do Risco
T3E|07|T3E_DTPRIS|C|220|0|D Grp Risc|Descricao Grp Risco
T3E|08|T3E_CAS|C|100|0|num. CAS|Numero CAS
T3E|09|T3E_VALIDA|D|8|0|Fim Validade|Data Fim Validade
--- ### T3G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3G|01|T3G_FILIAL|C|6|0|Filial|Filial
T3G|02|T3G_ID|C|6|0|ID|Identificador do Registro
T3G|03|T3G_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg.
T3G|04|T3G_RECPAG|C|30|0|Rec. Pagamen|Recibo de Pagamentos
T3G|05|T3G_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T3G|06|T3G_NRINSE|C|30|0|Nr Ins Est|Nr. Insc. Estabelecimento
T3G|07|T3G_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T3G|08|T3G_CODLOT|C|30|0|Cód. Lotação|Código Lotação
T3G|09|T3G_TPINSC|C|1|0|Tp Inscriçâo|Tipo Inscrição
T3G|10|T3G_NRINSC|C|15|0|Nr.Inscrição|Número de Inscrição
T3G|11|T3G_GRAUEX|C|6|0|Grau Expo Ag|Grau Expo Ag Nocivo
T3G|12|T3G_DGRAUE|C|220|0|Des.Grau Exp|Desc.Grau Expo Ag. Nocivo
T3G|13|T3G_INDCSU|C|1|0|Ind. Contr.|Ind. Contribuição Subst.
--- ### T3H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3H|01|T3H_FILIAL|C|6|0|Filial|Filial
T3H|02|T3H_ID|C|6|0|ID|Identificador do registro
T3H|03|T3H_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3H|04|T3H_TPTRIB|C|1|0|Tp Trib./Con|Tipo Tributo/Contribuição
T3H|05|T3H_IDPROC|C|6|0|ID. Process.|ID. Process. Judicial
T3H|06|T3H_NRPROC|C|220|0|Nr. Process.|Nr. Processo Judicial
T3H|07|T3H_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T3H|08|T3H_CODSUS|C|14|0|Cod Susp|Cod Indic Suspensao
T3H|09|T3H_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
--- ### T3I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3I|01|T3I_FILIAL|C|6|0|Filial|Filial
T3I|02|T3I_ID|C|6|0|ID|Identificador do registro
T3I|03|T3I_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3I|04|T3I_IDEDMD|C|30|0|Ident Dem Vl|Ident Dem Valores
T3I|05|T3I_IDRPGT|C|30|0|Id. Rec. Pgt|Id. Recimento Pgto
T3I|06|T3I_VLRPGT|N|14|2|Valor. Pgto|Valor do Pagamento
T3I|07|T3I_INDRRA|C|1|0|Ind. Ren RRA|Ind. Rendimentos RRA
T3I|08|T3I_TPPRRA|C|1|0|Tp. Proc RRA|Tp. Processo RRA
T3I|09|T3I_NRPRRA|C|21|0|Nr. Proc RRA|Nr. Processo RRA
T3I|10|T3I_DESCRA|C|50|0|Des. Ren RRA|Des. Rendimentos RRA
T3I|11|T3I_QTMRRA|N|5|1|Qt. Mes. RRA|Qt. Meses RRA
T3I|12|T3I_VLRCUS|N|15|2|Vl. Desp Jud|Vlr. Depesas Judiciais
T3I|13|T3I_VLRADV|N|15|2|Vl. Desp Adv|Vlr. Depesas Advogados
T3I|14|T3I_NOTAFT|C|9|0|Número FGTS|Número notificação FGTS
--- ### T3J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3J|01|T3J_FILIAL|C|6|0|Filial|Filial
T3J|02|T3J_ID|C|6|0|ID|Identificador do registro
T3J|03|T3J_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3J|04|T3J_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T3J|05|T3J_NRINSE|C|220|0|Nr Ins Est|Nr. Insc. Estabelecimento
T3J|06|T3J_LOTTRB|C|6|0|Lotação Trib|Lotação Tributária
T3J|07|T3J_CODLOT|C|30|0|Código Lotaç|Código de Lotação
T3J|08|T3J_TPINSC|C|1|0|Tipo Insc|Tipo Inscrição
T3J|09|T3J_NRINSC|C|15|0|Nro. Insc|Número de Inscrição
T3J|10|T3J_GRAUEX|C|6|0|Grau Expo Ag|Grau Expo Ag. Nocivo
T3J|11|T3J_DGRAUE|C|220|0|DescGrauExpo|Desc. Grau Expo Ag.
T3J|12|T3J_INDCSU|C|1|0|Ind. Contr.|Ind. Contr. Subs.
T3J|13|T3J_IDRPGT|C|30|0|Id. Rec. Pgt|Id. Recimento Pgto
T3J|14|T3J_IDEDMD|C|30|0|Ident Dem Vl|Ident Dem Valores
--- ### T3L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3L|01|T3L_FILIAL|C|6|0|Filial|Filial
T3L|02|T3L_ID|C|6|0|ID|Identificador do registro
T3L|03|T3L_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3L|04|T3L_CPF|C|11|0|CPF Trab.Sub|CPF Trabal. Substituído
T3L|05|T3L_MATRIC|C|30|0|Matric. Sub.|Matrícula Trab. Subst.
T3L|06|T3L_NOMEVE|C|5|0|Nome Evento|Nome do Evento
--- ### T3M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3M|01|T3M_FILIAL|C|6|0|Filial|Filial
T3M|02|T3M_ID|C|6|0|ID|ID do registro
T3M|03|T3M_CODERP|C|20|0|Código ERP|Código ERP
T3M|04|T3M_VERSAO|C|14|0|Id. Ver. Reg|Id da versao do registro
--- ### T3N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3N|01|T3N_FILIAL|C|6|0|Filial|Filial
T3N|02|T3N_ID|C|6|0|ID.|Identificador do Registro
T3N|03|T3N_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T3N|04|T3N_IDAMB|C|6|0|Cod.Ambiente|Codigo do Ambiente
T3N|05|T3N_DESAMB|C|220|0|Des.Ambiente|Descrição do Ambiente
T3N|06|T3N_FIMAMB|C|1|0|Finaliz. Amb|Finalizada Atividade Amb.
--- ### T3O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3O|01|T3O_FILIAL|C|6|0|Filial|Filial
T3O|02|T3O_ID|C|6|0|ID.|Identificador do Registro
T3O|03|T3O_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3O|04|T3O_IDAMB|C|6|0|Cód.Ambiente|Código Ambiente Trabalho
T3O|05|T3O_IDFATR|C|6|0|Fator Risco|Id. Fator Risco
T3O|06|T3O_DESFAT|C|220|0|Des.Fat.Risc|Des. Fator de Risco
T3O|07|T3O_INTEXP|C|15|0|Intens. Expo|Intens. Expo
T3O|08|T3O_TECMED|C|40|0|Tec. Medição|Tec. Utilizada Medição
--- ### T3P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3P|01|T3P_FILIAL|C|6|0|Filial|Filial
T3P|02|T3P_ID|C|36|0|ID|Identificador do registro
T3P|03|T3P_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3P|04|T3P_INDAPU|C|1|0|Ind. Apura.|Ind. Período Apuração
T3P|05|T3P_PERAPU|C|6|0|Per. Apur.|Período Apuração
T3P|06|T3P_BENEFI|C|6|0|Id. Benefic.|Id. Beneficiário
T3P|07|T3P_NOME|C|220|0|Nome Benef.|Nome Beneficiário
T3P|08|T3P_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T3P|09|T3P_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T3P|10|T3P_STATUS|C|1|0|Status Reg.|Status do registro
T3P|11|T3P_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T3P|12|T3P_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3P|13|T3P_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T3P|14|T3P_VLDEDB|N|15|2|Vl Ded Dep|Valor Dedução Dependente
T3P|15|T3P_LOGOPE|C|1|0|Log Operacao|Log Operacao
T3P|16|T3P_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T3P|17|T3P_XMLID|C|36|0|Id do XML.|Id do XML.
T3P|18|T3P_STASEC|C|1|0|Status Sec.|Status Secundario
T3P|19|T3P_CPF|C|11|0|CPF|CPF Trabalhador
T3P|20|T3P_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T3P|21|T3P_NOMER|C|220|0|Nome Benef.|Nome Beneficiário
T3P|22|T3P_GRVTOT|L|1|0|Totalizador|Gerou Totalizador ?
T3P|23|T3P_CPFV|C|11|0|CPF|CPF
T3P|24|T3P_NISV|C|11|0|NIS|NIS
T3P|25|T3P_MATV|C|30|0|Matricula|Matricula
T3P|26|T3P_NOMEV|C|70|0|Nome|Nome
T3P|27|T3P_OWNER|C|40|0|OWNER|Origem do registro
T3P|28|T3P_TRABEV|C|5|0|Evt Trabalh.|Evento Orig. Trabalhador
T3P|29|T3P_TAFKEY|C|100|0|TAFKEY|Valor do tafkey.
T3P|30|T3P_TPGUIA|C|1|0|Tipo de Guia|Indicativo Tipo de Guia
T3P|31|T3P_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T3P|32|T3P_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T3P|33|T3P_DTRECP|D|8|0|Dt. Recept|Data Receptação
T3P|34|T3P_HRRECP|C|8|0|Hr. Recept|Hora Receptação
T3P|35|T3P_ORIEVE|C|5|0|NOME EVENTO|NOME DO EVENTO
T3P|36|T3P_DTLAUD|D|8|0|Dt. Laudo|Data do Laudo
T3P|37|T3P_LAYOUT|C|30|0|Layout|Layout
T3P|38|T3P_CHKDIR|L|1|0|Check DIrf|Check DIrf
--- ### T3Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3Q|01|T3Q_FILIAL|C|6|0|Filial|Filial
T3Q|02|T3Q_ID|C|36|0|ID|Identificador do registro
T3Q|03|T3Q_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3Q|04|T3Q_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
T3Q|05|T3Q_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T3Q|06|T3Q_INDRES|C|1|0|Reside Brasi|Residente no Brasil
T3Q|07|T3Q_IDPAIS|C|6|0|ID. Pais|ID. Pais
T3Q|08|T3Q_DPAIS|C|220|0|Desc. Pais|Desc. Pais
T3Q|09|T3Q_INDNIF|C|1|0|Ind. NIF|Ind. Nr. Id. Fiscal
T3Q|10|T3Q_NIFBEN|C|20|0|NIF Benf.|NIF do Benefic.
T3Q|11|T3Q_DLOUGR|C|100|0|Des. Logr.|Des. Logradouro
T3Q|12|T3Q_NUMLOG|C|10|0|Nr. Log.|Numero Logradouro
T3Q|13|T3Q_COMPLE|C|30|0|Complemento|Complemento
T3Q|14|T3Q_BAIRRO|C|90|0|Bairro|Bairro Logr. Exterior
T3Q|15|T3Q_CIDADE|C|50|0|Cidade|Cidade Logr. Exterior
T3Q|16|T3Q_CEP|C|10|0|CEP|CEP Logr. Exterior
--- ### T3R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3R|01|T3R_FILIAL|C|6|0|Filial|Filial
T3R|02|T3R_ID|C|36|0|ID|Identificador do registro
T3R|03|T3R_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3R|04|T3R_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
T3R|05|T3R_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T3R|06|T3R_PERREF|C|6|0|Per. Referen|Per. Referencia
T3R|07|T3R_IDEDMD|C|30|0|Ident Dem Vl|Ident Demonstrativo Valor
T3R|08|T3R_INDPGT|C|1|0|Ind Pgto|Indicativo Pgto
T3R|09|T3R_VLRLIQ|N|15|2|Valor Líquid|Valor Líquido
T3R|10|T3R_NRARQ|C|44|0|Nr Rec Arq|Nr Recibo do Arquivo
T3R|11|T3R_IDENPG|C|2|0|Ident Pgto|Identificação Pagamento
--- ### T3S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3S|01|T3S_FILIAL|C|6|0|Filial|Filial
T3S|02|T3S_ID|C|6|0|ID|Identificador do Registro
T3S|03|T3S_VERSAO|C|14|0|Id. Ver. Reg|Id da Versão do Registro
T3S|04|T3S_DTINI|D|8|0|Data Inicio|Data de Inicio Respons.
T3S|05|T3S_DTFIM|D|8|0|Data Final|Data Final da Respons.
T3S|06|T3S_NISRES|C|11|0|Nis Respons.|Nis do Resp. Monitoração
T3S|07|T3S_NROC|C|14|0|Nr Insc OC|N. Inscr. orgão da classe
T3S|08|T3S_UFOC|C|6|0|Id UF Orgao|Id UF do orgão da classe
T3S|09|T3S_DUFOC|C|220|0|Desc. UF OC|Descr. UF orgao de classe
T3S|10|T3S_CPFRES|C|11|0|CPF Resp.|CPF Responsavel
T3S|11|T3S_NMRES|C|70|0|Nome Resp.|Nome Responsável
T3S|12|T3S_IDEOC|C|1|0|Orgao Classe|Orgao Classe
T3S|13|T3S_DSCOC|C|20|0|Desc OC.|Descricao Orgao de Classe
--- ### T3T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3T|01|T3T_FILIAL|C|6|0|Filial|Filial
T3T|02|T3T_ID|C|6|0|Id. Func.|Id. do Funcionário
T3T|03|T3T_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T3T|04|T3T_IDDEP|C|6|0|ID|Identificador do Registro
T3T|05|T3T_TPDEP|C|6|0|Id. Tp. Dep.|Id. Tipo Dependente
T3T|06|T3T_DTPDE|C|220|0|Descr Tp Dep|Descricao Tipo Dependente
T3T|07|T3T_NOMDEP|C|70|0|Nome Dep.|Nome Dependente
T3T|08|T3T_DTNASC|D|8|0|Dt. Nasc.|Data Nascimento
T3T|09|T3T_CPFDEP|C|11|0|CPF Dep.|CPF Dependente
T3T|10|T3T_DEPIRF|C|1|0|Dep. IRRF?|Dependente IRRF?
T3T|11|T3T_DEPSFA|C|1|0|Dep Sal Fam?|Dep. Salario Familia?
T3T|12|T3T_DEPFPR|C|1|0|Dep Fins Pre|Dep. Fins Prev.
T3T|13|T3T_DPPLPS|C|1|0|Dep. Pl. Pri|Dependente Plano Privado?
T3T|14|T3T_INCTRB|C|1|0|Incapac.Trab|Incapacidade p/ Trabalho
T3T|15|T3T_SEXDEP|C|1|0|Sexo Dep.|Sexo dependente
T3T|16|T3T_DESDEP|C|100|0|Dependência|Descrição da Dependência
--- ### T3U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3U|01|T3U_FILIAL|C|6|0|Filial|Filial
T3U|02|T3U_ID|C|6|0|Id. Func.|Id. do Funcionario
T3U|03|T3U_VERSAO|C|14|0|Id. Ver Reg|Id da Versao do Registro
T3U|04|T3U_CODDIA|C|1|0|Código Dia|Código Dia
T3U|05|T3U_CODHOR|C|6|0|Cod. Horário|Código do Horário
T3U|06|T3U_DCODHO|C|220|0|Desc.Horário|Descrição Horário
T3U|07|T3U_NOMEVE|C|5|0|Nome Evento|Nome do Evento
--- ### T3V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3V|01|T3V_FILIAL|C|6|0|Filial|Filial
T3V|02|T3V_ID|C|6|0|ID|Identificador do Registro
T3V|03|T3V_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3V|04|T3V_INDPAT|C|1|0|Ind.Sub.Patr|Ind.Sub.Con.Prev.Patronal
T3V|05|T3V_PRCONT|N|6|2|Per.Red.Cont|Perc.Red. da Contribuição
T3V|06|T3V_FATMES|N|6|2|Fator Mês|Fator Calc. Mes Patronal
T3V|07|T3V_FAT13|N|6|2|Fator 13º|Fator Décimo Terceiro
T3V|08|T3V_VERANT|C|14|0|Ver Ant Reg|Versão Anterior Registro
T3V|09|T3V_STATUS|C|1|0|Status Reg.|Status do Registro
T3V|10|T3V_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T3V|11|T3V_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T3V|12|T3V_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T3V|13|T3V_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3V|14|T3V_INDAPU|C|1|0|Ind.Per.Apur|Indic.Periodo Apuracao
T3V|15|T3V_PERAPU|C|6|0|Per.Apuracao|Periodo da Apuracao
T3V|16|T3V_LOGOPE|C|1|0|Log Operacao|Log Operacao
T3V|17|T3V_STASEC|C|1|0|Status Sec.|Status Secundario
T3V|18|T3V_XMLID|C|36|0|Id do XML|Id do XML.
T3V|19|T3V_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T3V|20|T3V_TPGUIA|C|1|0|Tp. Guia|Tipo de Guia
T3V|21|T3V_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T3V|22|T3V_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T3V|23|T3V_DTRECP|D|8|0|Dt. Recept|Data Receptação
T3V|24|T3V_HRRECP|C|8|0|Hr. Recept|Hora Receptação
T3V|25|T3V_T11096|C|1|0|Transf 11096|Info Percent transf 11096
--- ### T3W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3W|01|T3W_FILIAL|C|6|0|Filial|Filial
T3W|02|T3W_ID|C|6|0|ID|Identificador do registro
T3W|03|T3W_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3W|04|T3W_INDAPU|C|1|0|Ind.Apuração|Ind. Período Apuração
T3W|05|T3W_PERAPU|C|6|0|Per.Apuração|Período Apuração
T3W|06|T3W_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T3W|07|T3W_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T3W|08|T3W_STATUS|C|1|0|Status Reg.|Status do registro
T3W|09|T3W_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T3W|10|T3W_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3W|11|T3W_EVENTO|C|1|0|Id. Evento|Identificação do Evento
--- ### T3X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3X|01|T3X_FILIAL|C|6|0|Filial|Filial
T3X|02|T3X_ID|C|6|0|ID|Identificador do Registro
T3X|03|T3X_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3X|04|T3X_IDCNPJ|C|6|0|Id CNPJ Port|Ident. CNPJ Op. Portuario
T3X|05|T3X_CNPJOP|C|18|0|CNPJ Op.Port|CNPJ Operador Portuario
T3X|06|T3X_INDOPP|C|1|0|Ind.Sub.Port|Ind.Sub.Patr.Op.Port
T3X|07|T3X_PRCOOP|N|6|2|Per.Red.Op|Perc.Red. pelo Operador
T3X|08|T3X_CODLOT|C|6|0|Id. Lotação|Identificador da Lotação
T3X|09|T3X_DCODLO|C|220|0|Desc.Lotação|Descrição da Lotação
--- ### T3Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3Y|01|T3Y_FILIAL|C|6|0|Filial|Filial
T3Y|02|T3Y_ID|C|6|0|ID|Identificador do Registro
T3Y|03|T3Y_VERSAO|C|14|0|Id. Ver. Reg|Id. Da Versão do Registro
T3Y|04|T3Y_RECIBO|C|6|0|Num. Id. Rec|Num. Id. Rec. Patgo
T3Y|05|T3Y_VLRECI|N|14|2|Vl. Recibo|Valor de Recibo
T3Y|06|T3Y_DTACOR|D|8|0|Dt. Acordo|Data do acordo
T3Y|07|T3Y_TPACOR|C|1|0|Tp. Acordo|Tipo de acordo
--- ### T3Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T3Z|01|T3Z_FILIAL|C|6|0|Filial|Filial
T3Z|02|T3Z_ID|C|6|0|ID|Identificador do registro
T3Z|03|T3Z_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T3Z|04|T3Z_INDAPU|C|1|0|Ind Apuração|Ind. Período Apuração
T3Z|05|T3Z_PERAPU|C|6|0|Per Apuração|Período Apuração
T3Z|06|T3Z_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T3Z|07|T3Z_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T3Z|08|T3Z_STATUS|C|1|0|Status Reg.|Status do registro
T3Z|09|T3Z_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T3Z|10|T3Z_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T3Z|11|T3Z_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T3Z|12|T3Z_LOGOPE|C|1|0|Log Operacao|Log Operacao
T3Z|13|T3Z_STASEC|C|1|0|Status Sec.|Status Secundario
T3Z|14|T3Z_XMLID|C|36|0|Id do XML.|Id do XML
T3Z|15|T3Z_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T3Z|16|T3Z_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T3Z|17|T3Z_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T3Z|18|T3Z_DTRECP|D|8|0|Dt. Recept|Data Receptação
T3Z|19|T3Z_HRRECP|C|8|0|Hr. Recept|Hora Receptação
--- ### T50
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T50|01|T50_FILIAL|C|6|0|Filial|Filial
T50|02|T50_ID|C|36|0|ID|Identificador do Registro
T50|03|T50_IDGUIA|C|6|0|Código|Código da Guia
T50|04|T50_DIDGUI|C|220|0|Descrição|Descrição da Guia
--- ### T51
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T51|01|T51_FILIAL|C|6|0|Filial|Filial
T51|02|T51_ID|C|36|0|ID|ID
T51|03|T51_NUMPAR|C|3|0|Num Parcela|Número da Parcela
T51|04|T51_VLRPAR|N|16|2|Vlr Parcela|Valor da Parcela
T51|05|T51_INDSEX|C|1|0|Ind Exig Sus|Ind. Exigibilidade Susp.
T51|06|T51_INDC13|C|1|0|Ind. 13º Sal|Indicativo 13º Salário
T51|07|T51_COMPAC|N|16|2|Comp Jud AC|Comp. Judicial Ano Calend
T51|08|T51_COMPAT|N|16|2|Comp Jud AA|Comp. Jud. de Anos Anter.
T51|09|T51_VLRDPJ|N|16|2|Vlr Dep Jud|Vlr do Depósito Judicial
T51|10|T51_TPREXT|C|6|0|Tp Rend Ext|Tipo de Rend. Exterior
T51|11|T51_DRENEX|C|220|0|Desc Rend Ex|Descr Tipo Rend. Exterior
T51|12|T51_TRIBEX|C|6|0|Trib Rend Ex|Trib Rendimentos Exterior
T51|13|T51_DTRIEX|C|220|0|Desc Trib Ex|Desc Tributação Rend. Ext
T51|14|T51_TPISEN|C|6|0|Tp Isenção R|Tipo Isenção Rendimentos
T51|15|T51_DESTRE|C|220|0|Desc Isenc R|Desc Isenção Rendimentos
T51|16|T51_VLISEN|N|16|2|Vlr Isenção|Valor da Isenção
T51|17|T51_DESCRE|C|100|0|Desc Rendim.|Descrição Rend. Isento/NT
T51|18|T51_IDPART|C|36|0|Participante|Id do Participante
T51|19|T51_NUMFAT|C|15|0|Num. Fat/Rec|Numero Fatura Recibo
T51|20|T51_IDTSER|C|6|0|Tipo Serviço|Tipo de Serviço
--- ### T52
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T52|01|T52_FILIAL|C|6|0|Filial|Filial
T52|02|T52_ID|C|36|0|ID|Identificador do Registro
T52|03|T52_CODTRI|C|6|0|Cod. Tributo|Código do Tributo
T52|04|T52_DESTRI|C|220|0|Desc Tributo|Descrição do Tributo
T52|05|T52_CODPAG|C|6|0|Id Cod Pagam|Id do Código de Pagamento
T52|06|T52_DESPAG|C|220|0|D Cod Pagamt|Desc. Código do Pagamento
T52|07|T52_BASECA|N|16|2|Base Calculo|Base de Calculo Tributo
T52|08|T52_ALIQ|N|8|4|Alíquota|Alíquota
T52|09|T52_VLTRIB|N|16|2|Vlr. Tributo|Valor do Tributo
T52|10|T52_IDPART|C|36|0|Participante|ID do Participante
T52|11|T52_NUMFAT|C|15|0|Num. Fat/Rec|Numero da Fatura/Recibo
T52|12|T52_NUMPAR|C|3|0|Num Parcela|Número da Parcela
T52|13|T52_IDTSER|C|6|0|Tipo Serviço|Tipo de Serviço
T52|14|T52_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
--- ### T53
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T53|01|T53_FILIAL|C|6|0|Filial|Filial
T53|02|T53_ID|C|36|0|ID|Identificador do Registro
T53|03|T53_REFREN|C|1|0|Ref. Rendim.|Referência do Rendimento
T53|04|T53_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T53|05|T53_NRINSC|C|14|0|Nº Inscrição|Número de Inscrição
T53|06|T53_VLDESP|N|16|2|Valor Desp.|Valor Despesas Advogado
T53|07|T53_IDPART|C|36|0|Participante|ID do Participante
T53|08|T53_NUMFAT|C|15|0|Num Fat/Rec|Número da Fatura/Recibo
--- ### T54
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T54|01|T54_FILIAL|C|6|0|Filial|Filial do sistema
T54|02|T54_ID|C|36|0|Id|Identificador do Registro
T54|03|T54_CHAVE|C|30|0|Chave|Código da chave
T54|04|T54_TPDADO|C|1|0|Tipo dado|Tipo de dado
T54|05|T54_TITULO|C|12|0|Titulo campo|Título do campo
T54|06|T54_DESCRI|C|25|0|Descrição|Descrição do campo
T54|07|T54_PICTUR|C|45|0|Picture|Picture
T54|08|T54_CPADR|C|6|0|Cons. Padrão|Consulta padrão
T54|09|T54_COMBO|C|128|0|Vlr. Combo|Valores combobox
T54|10|T54_TAMANH|N|6|0|Tamanho|Tamanho do campo
T54|11|T54_DECIMA|N|2|0|Decimal|Qtd. Decimais
T54|12|T54_FVALID|C|30|0|Validação|Função de validação
T54|13|T54_STRHLP|C|11|0|String Help|String do help
--- ### T55
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T55|01|T55_FILIAL|C|6|0|Filial|Filial do Sistema
T55|02|T55_ID|C|36|0|Id.|Identificador do Registro
T55|03|T55_IDOBRG|C|36|0|Id. Obrig.|Identificador obrigação
T55|04|T55_IDCHAV|C|36|0|Id. Chave|Identificador da chave
T55|05|T55_OBRG|C|6|0|Obrigação|Obrigação
T55|06|T55_DSOBRG|C|220|0|Desc.Obrig.|Descrição da Obrigação
T55|07|T55_CHAVE|C|30|0|Chave|Chave
--- ### T56
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T56|01|T56_FILIAL|C|6|0|Filial|Filial
T56|02|T56_ID|C|36|0|Id.|Identificador do Registro
T56|03|T56_DTINI|D|8|0|Data inicial|Data inicial
T56|04|T56_DTFIN|D|8|0|Data final|Data final
T56|05|T56_IDUF|C|6|0|ID UF|Identificador da UF
T56|06|T56_UF|C|2|0|UF|UF do período
T56|07|T56_DESCUF|C|220|0|Desc. UF|Descrição da UF
T56|08|T56_STATUS|C|1|0|Status Reg.|Status do registro
--- ### T57
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T57|01|T57_FILIAL|C|6|0|Filial|Filial do sistema
T57|02|T57_ID|C|36|0|Id.|Identificador do registro
T57|03|T57_IDCHAV|C|36|0|Id. Chave|Id. Chave
T57|04|T57_VLCHAV|C|220|0|Valor chave|Valor da chave
T57|05|T57_CHAVE|C|30|0|Chave|Chave
--- ### T58
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T58|01|T58_FILIAL|C|6|0|Filial|Filial
T58|02|T58_ID|C|36|0|ID|Indentificação do Registr
T58|03|T58_CODIGO|C|8|0|Código|Código Inf Ad
T58|04|T58_DESCRI|C|254|0|Descr Inf Ad|Descrição Inf Adicional
T58|05|T58_VALIDA|D|8|0| Data Vigenc|Data Vigenc. Cred
--- ### T59
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T59|01|T59_FILIAL|C|6|0|Filial|Filail
T59|02|T59_ID|C|10|0|ID|Identificador do Registro
T59|03|T59_CODIGO|C|2|0|Codigo|Código da Unidade
T59|04|T59_UNMEDI|C|30|0|Un.Medida|Unidade de Medida
T59|05|T59_DINIVA|C|6|0|Ini.Validade|Data Início Validade
T59|06|T59_DFINVA|C|6|0|Fin.Validade|Data Final Validade
--- ### T5A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5A|01|T5A_FILIAL|C|6|0|filial|filial
T5A|02|T5A_ID|C|36|0|ID|Identificador do registro
T5A|03|T5A_TIPO|C|1|0|Tipo|Tipo
T5A|04|T5A_FINALI|C|1|0|finalidade|finalidade
T5A|05|T5A_CLASSE|C|1|0|Classe|Classe
T5A|06|T5A_ESPECI|C|220|0|Especific.|especificação
T5A|07|T5A_SEQUEN|C|3|0|sequencia|Sequancia
T5A|08|T5A_CODOPE|C|7|0|codigo|Código da operação
T5A|09|T5A_DATINI|C|6|0|data inicial|data inicial de validade
T5A|10|T5A_DATFIN|C|6|0|Data Final|Data Final de validade
T5A|11|T5A_ORGOPE|C|1|0|Origem Oper.|Origem da Operação
--- ### T5B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5B|01|T5B_FILIAL|C|6|0|filial|filia
T5B|02|T5B_ID|C|36|0|ID|Identificação do Registro
T5B|03|T5B_CODIGO|C|5|0|Ativ. Econo.|Atividade Economica
T5B|04|T5B_DESATI|C|150|0|Descr. Ativ|Descrição da Atividade
T5B|05|T5B_DATINI|C|6|0|Data Inicial|Data inicial validade
T5B|06|T5B_DATFIN|C|6|0|Dat. Final|Data final validade
--- ### T5C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5C|01|T5C_FILIAL|C|6|0|filial|filial
T5C|02|T5C_ID|C|36|0|ID|Identificador Registro
T5C|03|T5C_CODIGO|C|3|0|Codigo ANP|Código ANP
T5C|04|T5C_CARACT|C|150|0|Carac. Fis\q|Característica Fisico\qui
T5C|05|T5C_UNIMED|C|50|0|Uni. Med.|Unidade de Medida
T5C|06|T5C_DATINI|C|6|0|Dat. Ini|Data Inicial
T5C|07|T5C_DATFIN|C|6|0|Dat. Fin.|Data Final
--- ### T5D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5D|01|T5D_FILIAL|C|6|0|filial|filial
T5D|02|T5D_ID|C|36|0|ID|Identificação Registro
T5D|03|T5D_CODIGO|C|2|0|código ANP|Código ANP
T5D|04|T5D_CARACT|C|220|0|Caracteris.|Características
T5D|05|T5D_DTINI|C|6|0|Dat Ini|Data Inicial
T5D|06|T5D_DATFIN|C|6|0|Data Final|Data final de validade
--- ### T5E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5E|01|T5E_FILIAL|C|6|0|filial|filial
T5E|02|T5E_ID|C|36|0|ID|Identificação Registro
T5E|03|T5E_CODIGO|C|2|0|Código|Código vasilhame ANP
T5E|04|T5E_VASILH|C|150|0|Vasilhame|Vasilhame GLP
T5E|05|T5E_DATINI|C|6|0|data inicial|data inicial de validade
T5E|06|T5E_DATFIN|C|6|0|data final|data final de validade
--- ### T5F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5F|01|T5F_FILIAL|C|6|0|filial|filial
T5F|02|T5F_ID|C|36|0|ID|Identificação do registro
T5F|03|T5F_CODIGO|C|3|0|codigo|Codigo ANP
T5F|04|T5F_METODO|C|50|0|Método|Método Aferição
T5F|05|T5F_DATINI|C|6|0|data ini|data inicial
T5F|06|T5F_DATFIN|C|6|0|data final|data final validade
--- ### T5G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5G|01|T5G_FILIAL|C|6|0|Filial|Filial
T5G|02|T5G_ID|C|6|0|ID|Identificador do Registro
T5G|03|T5G_CODIGO|C|2|0|Código|Cód. Benef. Previd.
T5G|04|T5G_DESCRI|C|220|0|Descrição|Desc. Benefício
T5G|05|T5G_VALIDA|D|8|0|Data Vigenc.|Dt Vig Cod Tp Dependente
--- ### T5H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5H|01|T5H_FILIAL|C|6|0|Filial|Filial
T5H|02|T5H_ID|C|6|0|ID|Identificador do Registro
T5H|03|T5H_CODIGO|C|2|0|Código|Cód. Motiv. Benef. Previd
T5H|04|T5H_DESCRI|C|220|0|Descrição|Desc. Motiv. Cessação Pre
T5H|05|T5H_VALIDA|D|8|0|Data Vigenc.|Data da Vigência
--- ### T5I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5I|01|T5I_FILIAL|C|6|0|Filial|Filial
T5I|02|T5I_ID|C|6|0|ID|Identificador do Registro
T5I|03|T5I_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5I|04|T5I_IDEDMD|C|30|0|Iden Dem Val|Identificador Dem Valores
T5I|05|T5I_DTACCO|D|8|0|Dt Assinatur|Dt Assinatura
T5I|06|T5I_TPACCO|C|1|0|Tp de Acordo|Tipo de Acordo
T5I|07|T5I_DTEFAC|D|8|0|Dt Acordo|Dt Acordo
T5I|08|T5I_DSC|M|10|0|Detalhamento|Detalhamento Intr. ou Sit
T5I|09|T5I_COMPAC|C|6|0|Comp. Ac.|Comp. Acordo Coletivo
--- ### T5J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5J|01|T5J_FILIAL|C|6|0|Filial|Filial
T5J|02|T5J_ID|C|6|0|ID|Identificador do Registro
T5J|03|T5J_VERSAO|C|14|0|Id. Ver. R|Id da versão do registro
T5J|04|T5J_PERREF|C|6|0|Periodo Ref|Periodo Referencia
T5J|05|T5J_IDEDMD|C|30|0|Ident Dem Va|Ident Dem Valor
T5J|06|T5J_DTACCO|D|8|0|Dt Assinatur|Dt Assinatura
T5J|07|T5J_TPACCO|C|1|0|Tp de Acordo|Tipo de Acordo
--- ### T5K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5K|01|T5K_FILIAL|C|6|0|Filial|Filial
T5K|02|T5K_ID|C|6|0|ID|Identificador do Registro
T5K|03|T5K_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T5K|04|T5K_DTINI|C|6|0|Per. Ini Vld|Período Inicial Validade
T5K|05|T5K_DTFIN|C|6|0|Per. Fim Vld|Período Final Validade
T5K|06|T5K_CODIGO|C|30|0|Código|Código Carreira Pública
T5K|07|T5K_DESCRI|C|100|0|Descrição|Descrição Carreira Púb
T5K|08|T5K_LEICAR|C|12|0|Lei Car Púb|Lei da Carreira Pública
T5K|09|T5K_DTLEI|D|8|0|Data Lei|Data Lei Carreira Pública
T5K|10|T5K_SITCAR|C|1|0|Sit Car Púb|Sit. da Carreira Pública
T5K|11|T5K_VERANT|C|14|0|Id. Ver. Ant|Id versão anterior reg.
T5K|12|T5K_STATUS|C|1|0|Status Reg.|Status do registro
T5K|13|T5K_PROTUL|C|44|0|Ult.Prot.Tr.|Prot. Última transmissão
T5K|14|T5K_PROTPN|C|44|0|Pnlt.Prot.Tr|Prot. Penúltima transm.
T5K|15|T5K_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T5K|16|T5K_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T5K|17|T5K_XMLID|C|36|0|Id do XML.|Id do XML
T5K|18|T5K_LOGOPE|C|1|0|Log Operacao|Log Operacao
--- ### T5L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5L|01|T5L_FILIAL|C|6|0|Filial|Filial
T5L|02|T5L_ID|C|6|0|ID|Identificador do Registro
T5L|03|T5L_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T5L|04|T5L_CODSUS|C|14|0|Código Susp.|Código de Suspensão
T5L|05|T5L_INDDEC|C|6|0|Id.Ind.Susp.|Id. Indicador Suspensão
T5L|06|T5L_DINDDE|C|220|0|Des.Ind.Susp|Des. Indicador Suspensão
T5L|07|T5L_DTDEC|D|8|0|Dt.Decisão|Data da Decisão
T5L|08|T5L_INDDEP|C|1|0|Ind.Depósito|Indicador de Depósito
T5L|09|T5L_VLRDEP|N|14|2|Vlr Depósito|Valor do Depósito
--- ### T5M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5M|01|T5M_FILIAL|C|6|0|Filial|Filial
T5M|02|T5M_ID|C|36|0|ID|Identificador do Registro
T5M|03|T5M_IDTSER|C|6|0|Tipo Serviço|Tipo de Serviço
T5M|04|T5M_DTPSER|C|220|0|Desc Tp Serv|Desc. do Tipo de Serviço
T5M|05|T5M_IDATVE|C|6|0|Id Atv Econo|Id Atividade Econômica
T5M|06|T5M_DATIVE|C|220|0|Desc Atv Eco|Desc. Ativ. Economica
T5M|07|T5M_VLMTEQ|N|16|2|Vl Mat Equip|Vlr. Mat. ou Equipamentos
T5M|08|T5M_VLDALI|N|16|2|Vl Custo Ali|Valor Ded. Custo de Alim.
T5M|09|T5M_VLCTRA|N|16|2|Vl Custo Tra|Vlr. Ded. C. Transporte
T5M|10|T5M_VLBRET|N|16|2|BC Retenc.|Base Calculo Retenção
T5M|11|T5M_VLRETE|N|16|2|Vrl Retenção|Valor da Retenção
T5M|12|T5M_VLRETS|N|16|2|Vlr. Ret Sub|Valor Retenção Serv. Sub.
T5M|13|T5M_VLRETP|N|16|2|Vl Ret Princ|Valor Retenção Principal
T5M|14|T5M_VLSV15|N|16|2|Vlr Apos 15|Vlr Serv Apos Esp 15 anos
T5M|15|T5M_VLSV20|N|16|2|Vlr Apos 20|Vlr Serv Apos Esp 20 anos
T5M|16|T5M_VLSV25|N|16|2|Vlr Apos 25|Vlr Serv Apos Esp 25 anos
T5M|17|T5M_VLRADI|N|16|2|Vlr. Adicion|Valor Adicional
T5M|18|T5M_VRTADI|N|16|2|Vlr Ret Adic|Valor Ret. Adicional INSS
T5M|19|T5M_IDPART|C|36|0|Id do Partic|Id do Participante
T5M|20|T5M_NUMFAT|C|15|0|Num. Fat/Rec|Numero Fatura Recibo
T5M|21|T5M_VLADIC|N|16|2|Vl.Adicional|Valor Adic. Ret
T5M|22|T5M_VLADNE|N|16|2|Vl.Adc.NEfet|Vl.Adic Não Efetivado
T5M|23|T5M_BSINSS|N|16|2|Vl Base INSS|Valor Base Calculo INSS
T5M|24|T5M_VLINSS|N|16|2|Valor INSS|Valor Apurado INSS
T5M|25|T5M_TPREPA|C|1|0|Tipo Repasse|Tipo de Repasse
T5M|26|T5M_DESCRI|C|20|0|Descrição|Descrição Resumida
T5M|27|T5M_VLBRUT|N|14|2|Valor Bruto|Valor Bruto do Repasse
T5M|28|T5M_VLREAP|N|14|2|Vlr Apur Ret|Valor Apuração Retenção
--- ### T5N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5N|01|T5N_FILIAL|C|6|0|Filial|Filial
T5N|02|T5N_ID|C|6|0|ID|Identificador do Registro
T5N|03|T5N_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T5N|04|T5N_IDPROC|C|6|0|ID Processo|ID Processo
T5N|05|T5N_DNRPRO|C|21|0|Num. Proc|Numero do Processo
T5N|06|T5N_NINCID|C|2|0|Não Incid.|Não Incidência
T5N|07|T5N_EXTDEC|C|1|0|Ext. Decisao|Extensao da Decisao
T5N|08|T5N_CODSUS|C|14|0|Cod Susp|Cod Indic Suspensao
T5N|09|T5N_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
--- ### T5O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5O|01|T5O_FILIAL|C|6|0|Filial|Filial
T5O|02|T5O_ID|C|36|0|ID|Id. do Registro
T5O|03|T5O_IDTPTR|C|6|0|Id. Tip. Tra|Id. Tipo de Transporte
T5O|04|T5O_TPTRAN|C|6|0|Cód. Tp Tran|Cód. Tipo de Transporte
T5O|05|T5O_DTPTRA|C|220|0|Desc. Tp. Tr|Descrição Tip. Transp.
T5O|06|T5O_CODANP|C|6|0|Cód.ANP|Código ANP
T5O|07|T5O_DESCRI|C|220|0|Descrição|Descrição ANP
T5O|08|T5O_VALID|D|8|0|Dt. Validade|Data de Validade
--- ### T5P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5P|01|T5P_FILIAL|C|6|0|Filial|Filial
T5P|02|T5P_ID|C|36|0|ID|Identificador do Registro
T5P|03|T5P_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
T5P|04|T5P_VLPGTO|N|16|2|Valor Pgto|Valor do Pagamento
T5P|05|T5P_IDPART|C|36|0|Participante|ID do Participante
T5P|06|T5P_NUMFAT|C|15|0|Num. Fat/Rec|Numero da Fatura/Recibo
T5P|07|T5P_NUMPAR|C|3|0|Num Parcela|Número da Parcela
T5P|08|T5P_IDTSER|C|6|0|Tipo Serviço|Tipo de Serviço
T5P|09|T5P_PROCID|C|6|0|Proc ID|ID de Processos.
--- ### T5Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5Q|01|T5Q_FILIAL|C|6|0|Filial|Filial
T5Q|02|T5Q_ID|C|6|0|ID|Identificador do Registro
T5Q|03|T5Q_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T5Q|04|T5Q_IDEDMD|C|30|0|Ident Dem Vl|Ident Dem Vl
T5Q|05|T5Q_DTACCO|D|8|0|Dt Assinatur|Dt Assinatura
T5Q|06|T5Q_TPACCO|C|1|0|Tp de Acordo|Tipo de Acordo
T5Q|07|T5Q_PERREF|C|6|0|Periodo Ref|Periodo Referencia
T5Q|08|T5Q_LOTTRB|C|6|0|Lotacao Trib|Lotacao Tributaria
T5Q|09|T5Q_CODLOT|C|30|0|Cod. Lotacao|Codigo Lotacao
T5Q|10|T5Q_TPINSC|C|1|0|Tp Inscricao|Tipo Inscricao
T5Q|11|T5Q_NRINSC|C|15|0|Nr.Inscricao|Numero de Inscricao
T5Q|12|T5Q_GRAUEX|C|6|0|Grau Expo Ag|Grau Expo Ag Nocivo
T5Q|13|T5Q_DGRAUE|C|220|0|Des.Grau Exp|Desc.Grau Expo Ag. Nocivo
T5Q|14|T5Q_INDCSU|C|1|0|Ind. Contr.|Ind. Contribuicao Subst.
T5Q|15|T5Q_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T5Q|16|T5Q_NRINSE|C|30|0|Nr Ins Est|Nr. Insc. Estabelecimient
--- ### T5R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5R|01|T5R_FILIAL|C|6|0|Filial|Filial
T5R|02|T5R_ID|C|6|0|ID|ID Class Trib
T5R|03|T5R_CCLATR|C|6|0|Class. Trib.|Código Class. Trib
T5R|04|T5R_DCLATR|C|254|0|Descricao|Descriçao Class. Trib.
T5R|05|T5R_CODCST|C|3|0|CST|Código CST
T5R|06|T5R_DESCST|C|254|0|Descriçao|Descriçao CST
T5R|07|T5R_DTINI|D|8|0|Data Inicial|Data Inicial
T5R|08|T5R_DTFIN|D|8|0|Data Final|Data Final
--- ### T5S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5S|01|T5S_FILIAL|C|6|0|Filial|Filial
T5S|02|T5S_ID|C|6|0|ID|Identificador do Registro
T5S|03|T5S_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T5S|04|T5S_IDEDMD|C|30|0|Ident Dem Vl|Ident Dem Valor
T5S|05|T5S_DTACCO|D|8|0|Dt Assinat|Dt Assinatura
T5S|06|T5S_TPACCO|C|1|0|Tp de Acordo|Tipo de Acordo
T5S|07|T5S_LOTTRB|C|6|0|Lot.Tribut|Lotacao Tributaria
T5S|08|T5S_TPINSC|C|1|0|Tp Inscricao|Tipo de Inscricao
T5S|09|T5S_NRINSC|C|15|0|Nr Inscricao|Numero de Inscricao
T5S|10|T5S_CODRUB|C|6|0|Cod Rubrica|Codigo de Rubrica
T5S|11|T5S_DCODRU|C|220|0|Desc Cod Rub|Descricao Codigo Rubrica
T5S|12|T5S_QTDRUB|N|7|2|Qtd. Rubr|Quantidade de Rubrica
T5S|13|T5S_FATRUB|N|6|2|Fator Rubric|Fator de Rubrica
T5S|14|T5S_VLRUNI|N|15|2|Vlr Unit Rub|Valor Unitario da Rubric
T5S|15|T5S_VLRRUB|N|15|2|Vlr Rubrica|Valor Total da Rubrica
T5S|16|T5S_PERREF|C|6|0|Periodo Ref|Periodo Referencia
T5S|17|T5S_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T5S|18|T5S_SQTDRB|N|13|2|Qtd. Rubr|Quantidade de Rúbrica
T5S|19|T5S_APURIR|C|1|0|Tp.Apur.IR|Tipo Apuração IR
--- ### T5T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5T|01|T5T_FILIAL|C|6|0|Filial|Filial
T5T|02|T5T_ID|C|6|0|ID|Identificador do Registro
T5T|03|T5T_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T5T|04|T5T_CPF|C|11|0|CPF Benef.|CPF do Beneficiário
T5T|05|T5T_NOME|C|70|0|Nome Benef|Nome do Beneficiário
T5T|06|T5T_DTNASC|D|8|0|Data Nasc|Data de Nascimento
T5T|07|T5T_CODPAI|C|6|0|Id Pais Nasc|Id. Pais de Nascimento
T5T|08|T5T_DCODPA|C|220|0|Des Pais Nas|Descr. Pais de Nascimento
T5T|09|T5T_CODUF|C|6|0|Id. UF Nasc.|Id. da UF de Nascimento
T5T|10|T5T_DCODUF|C|220|0|Descr UF Nas|Descr. UF de Nascimento
T5T|11|T5T_CODMUN|C|6|0|Id. Mun. Nas|Id. Município Nascimento
T5T|12|T5T_DCODMU|C|220|0|Des Mun Nasc|Desc Municipio Nascimento
T5T|13|T5T_PAINAC|C|6|0|Id. Pais Nac|Id. Pais de Nacionalidade
T5T|14|T5T_DPAINA|C|220|0|Des Pais Nac|Descr. Pais Nacionalidade
T5T|15|T5T_NOMMAE|C|70|0|Nome Mãe|Nome da Mãe
T5T|16|T5T_NOMPAI|C|70|0|Nome Pai|Nome do Pai
T5T|17|T5T_PAIS|C|6|0|Id Pais End|Id. Pais do Endereço
T5T|18|T5T_DPAIS|C|220|0|Des Pais End|Descr. País do Endereco
T5T|19|T5T_UF|C|6|0|Id. UF End.|Id. UF do Endereco
T5T|20|T5T_DUF|C|220|0|Descr UF End|Descrição UF do Endereço
T5T|21|T5T_MUN|C|6|0|Id. Mun. End|Id. Municipio do Endereço
T5T|22|T5T_DMUN|C|220|0|Des Mun En|Descr. Municipio Endereço
T5T|23|T5T_TPLOGR|C|6|0|Id. Tp. Log.|Id. Tipo Logradouro
T5T|24|T5T_DTPLOG|C|220|0|Des Tp Log|Descrição Tipo Logradouro
T5T|25|T5T_LOGRAD|C|100|0|Descr. Log|Descrição do Logradouro
T5T|26|T5T_NRLOG|C|10|0|Número Log.|Número Logradouro
T5T|27|T5T_COMLOG|C|30|0|Compl. Log|Complemento Logradouro
T5T|28|T5T_BAIRRO|C|90|0|Bairro|Bairro
T5T|29|T5T_CEP|C|8|0|CEP|CEP
T5T|30|T5T_NOMCID|C|50|0|Nome Cid Ext|Nome Cidade Exterior
T5T|31|T5T_CXPOST|C|12|0|Caixa Postal|Caixa Postal Exterior
T5T|32|T5T_TPPLRP|C|1|0|Tp Plano RP|Tp Plano Segregação Massa
T5T|33|T5T_TPBENE|C|6|0|Tp. Benef.|Tp. Benef. Previdenciário
T5T|34|T5T_DTPBEN|C|220|0|Des Tp Ben.|Descr. Tipo do Benefício
T5T|35|T5T_NUMBEN|C|20|0|Núm. Benef.|Núm. Benef Previdenciário
T5T|36|T5T_DTINIB|D|8|0|Dt Ini Benef|Dt Ini. Benef. Previdenc.
T5T|37|T5T_VLRBEN|N|16|2|Vl Benefício|Vlr Benef. Previdenciário
T5T|38|T5T_IDQUOT|C|30|0|Id Quota Ben|Id. da Quota do Benefício
T5T|39|T5T_CPFINS|C|11|0|CPF Instit.|CPF Instit. Pensão Morte
T5T|40|T5T_DTFIMB|D|8|0|Dt Fim Benef|Dt Fim Benef Previdenciár
T5T|41|T5T_MTVFIM|C|6|0|Motivo Fim|Motivo Fim do Benefício
T5T|42|T5T_DMTVFI|C|220|0|Des Motv Fim|Desc Motiv Fim Benefício
T5T|43|T5T_VERANT|C|14|0|Id. Ver. Ant|Id Versão Anterior Reg.
T5T|44|T5T_STATUS|C|1|0|Status Reg.|Status do registro
T5T|45|T5T_PROTUL|C|44|0|Ult.Prot.Tr.|Prot. Última Transmissão
T5T|46|T5T_PROTPN|C|44|0|Pnlt.Prot.Tr|Prot. Penultima Transm.
T5T|47|T5T_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T5T|48|T5T_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T5T|49|T5T_LOGOPE|C|1|0|Log Operacao|Log Operacao
T5T|50|T5T_XMLID|C|36|0|Id do XML.|Id do XML
T5T|51|T5T_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T5T|52|T5T_DTRANS|D|8|0|Dt.Transm.|Data Transmissão
T5T|53|T5T_HTRANS|C|8|0|Hr.Transm|Hora Transmissão
T5T|54|T5T_DTRECP|D|8|0|Dt.Recept|Data Receptação
T5T|55|T5T_HRRECP|C|8|0|Hr.Recept|Hora Receptação
--- ### T5U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5U|01|T5U_FILIAL|C|6|0|Filial|Filial
T5U|02|T5U_ID|C|36|0|ID|Identificador do Registro
T5U|03|T5U_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5U|04|T5U_DTPGTO|D|8|0|Data Pgto|Data de Pagamento
T5U|05|T5U_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T5U|06|T5U_IDCATE|C|6|0|Id Categ Trb|Categ. Trabalhador
T5U|07|T5U_DCATEG|C|220|0|Des Categ Tr|Des. Categ. Trabalhador
T5U|08|T5U_DTINIG|D|8|0|Dt Ini Fer|Data Inicio Ferias
T5U|09|T5U_QTDIAS|N|2|0|Qtd. Dias|Qtd. Dias Ferias Gozadas
T5U|10|T5U_VLRLIQ|N|15|2|Vlr Liquido|Vlr Liquido Receb Trab
T5U|11|T5U_MATRIC|C|30|0|Matricula|Matricula
--- ### T5V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5V|01|T5V_FILIAL|C|6|0|Filial|Filial
T5V|02|T5V_ID|C|36|0|ID|Identificador do Registro
T5V|03|T5V_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5V|04|T5V_DTPGTO|D|8|0|Data Pgto |Data de Pagamento
T5V|05|T5V_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T5V|06|T5V_IDCATE|C|6|0|Id Categ Trb|Categ. Trabalhador
T5V|07|T5V_DCATEG|C|220|0|Des. Categor|Descrição Categoria
T5V|08|T5V_PERREF|C|6|0|Período Pgto|Período Pagamento
--- ### T5X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5X|01|T5X_FILIAL|C|6|0|Filial|Filial
T5X|02|T5X_ID|C|36|0|ID|Identificador do Registro
T5X|03|T5X_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5X|04|T5X_DTPGTO|D|8|0|  Data Pgto|Data de Pagamento
T5X|05|T5X_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T5X|06|T5X_IDCATE|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T5X|07|T5X_PERREF|C|6|0|Período Pgto|Período Pagamento
T5X|08|T5X_SEQUEN|C|3|0|Sequencia|Sequencia
T5X|09|T5X_IDTPIR|C|6|0|Id Tp Ded IR|Id Tp Deducao IRRF
T5X|10|T5X_DTPIRR|C|220|0|Des Tp Ded|Des Tp Deducao IRRF
T5X|11|T5X_VLRBCI|N|15|2|Vl Dedução|Vlr Bs Calculo Ded
--- ### T5Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5Y|01|T5Y_FILIAL|C|6|0|Filial|Filial
T5Y|02|T5Y_ID|C|36|0|ID|Identificador do registro
T5Y|03|T5Y_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5Y|04|T5Y_DTPGTO|D|8|0|Data Pgto|Data de Pagamento
T5Y|05|T5Y_TPPGTO|C|1|0|Tipo Pgto|Tipo de Pagamento
T5Y|06|T5Y_IDCATE|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T5Y|07|T5Y_DTINIG|D|8|0|Dt In Ferias|Data Inicio Ferias
T5Y|08|T5Y_IDRUBR|C|6|0|Cod. Rubrica|Codigo da Rubrica
T5Y|09|T5Y_DRUBR|C|220|0|Des. Rubrica|Descricao Rubrica
T5Y|10|T5Y_QTDRUB|N|7|2|Qtd. Rubrica|Quantidade da Rubrica
T5Y|11|T5Y_FATRUB|N|6|2|Fat. Rubrica|Fator da Rubrica
T5Y|12|T5Y_VLRUNI|N|15|2|Vlr Unitario|Valor Unitário da Rubrica
T5Y|13|T5Y_VLRRUB|N|15|2|Vlr Rubrica|Vlr Total Rubrica
T5Y|14|T5Y_QTDIAS|N|2|0|Qtd. Dias|Qtd Dias Ferias Gozadas
T5Y|15|T5Y_RUBRIC|C|30|0|Cod. Rubrica|Codigo da Rubrica
T5Y|16|T5Y_IDTABR|C|8|0|Id. Tab Rubr|Id. Tab Rubrica
T5Y|17|T5Y_MATRIC|C|30|0|matricula|matricula
--- ### T5Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T5Z|01|T5Z_FILIAL|C|6|0|Filial|Filial
T5Z|02|T5Z_ID|C|36|0|ID|Identificador do registro
T5Z|03|T5Z_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T5Z|04|T5Z_DTPGTO|D|8|0|Data Pgto|Data de Pagamento
T5Z|05|T5Z_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T5Z|06|T5Z_IDCATE|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T5Z|07|T5Z_DTINIG|D|8|0|Dt Ini Feria|Data Inicio Ferias
T5Z|08|T5Z_IDRUBR|C|6|0|Cod. Rubrica|Codigo da Rubrica
T5Z|09|T5Z_CPFBEN|C|11|0|CPF Benefici|CPF Beneficiario Pgto
T5Z|10|T5Z_DTNSBE|D|8|0|Dt Nasc Bene|Data Nascimento Benef.
T5Z|11|T5Z_NMBEN|C|70|0|Nome Benefic|Nome do Beneficiario
T5Z|12|T5Z_VLRPEN|N|15|2|Vlr Pensao|Valor Pensao Alimenticio
T5Z|13|T5Z_QTDIAS|N|2|0|Qtd. Dias|Qtd Dias Ferias Gozadas
T5Z|14|T5Z_RUBRIC|C|30|0|Rubrica|Rubrica
T5Z|15|T5Z_MATRIC|C|30|0|matricula|matricula
--- ### T60
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T60|01|T60_FILIAL|C|6|0|Filial|Filial
T60|02|T60_CHVNF|C|36|0|Chave NF|Chave Nota Fiscal
T60|03|T60_NUMDOC|C|60|0|Num. Docum.|Numero Documento Fiscal
T60|04|T60_SERIE|C|20|0|Série|Série do Doc. Transporte
T60|05|T60_SUBSER|C|20|0|Sub. Série|Sub-Série Conhec. Transp.
T60|06|T60_CODPAR|C|6|0|Cod. Part|Código do participante
T60|07|T60_DPART|C|220|0|Desc. Part|Descrição Participante
T60|08|T60_CPARTI|C|60|0|Cód. Partic.|Código do Participante
--- ### T61
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T61|01|T61_FILIAL|C|6|0|Filial|Filial
T61|02|T61_ID|C|36|0|ID|Identificador do Registro
T61|03|T61_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T61|04|T61_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T61|05|T61_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T61|06|T61_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T61|07|T61_DEMPAG|C|30|0|Id Dem. Pag.|Ident. Demonst. Pagamento
T61|08|T61_DTLEI|D|8|0|Data Lei|Data da Lei
T61|09|T61_NUMLEI|C|12|0|Núm. Lei|Número da Lei
T61|10|T61_DTEFET|D|8|0|Dt Efet Lei|Dt. Lei Produz. Efeitos
T61|11|T61_ORGSUC|C|1|0|Rem.Org.Suce|Remuneração Org. Sucessão
--- ### T62
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T62|01|T62_FILIAL|C|6|0|Filial|Filial
T62|02|T62_ID|C|6|0|ID|Identificador do Registro
T62|03|T62_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T62|04|T62_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T62|05|T62_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T62|06|T62_IDBEN|C|6|0|Id. Benef.|ID do Beneficiário
T62|07|T62_NOMEB|C|220|0|Nome Benef.|Nome do Beneficiário
T62|08|T62_CPF|C|11|0|CPF Benef.|CPF do Beneficiário
T62|09|T62_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T62|10|T62_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T62|11|T62_VERANT|C|14|0|Id. Ver. Ant|Id Versão Anterior Reg.
T62|12|T62_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T62|13|T62_STATUS|C|1|0|Status Reg.|Status do registro
T62|14|T62_PROTUL|C|44|0|Ult.Prot.Tr.|Prot. Ùltima Transmissão
T62|15|T62_PROTPN|C|44|0|Pnlt.Prot.Tr|Prot. Penultima Transm.
T62|16|T62_LOGOPE|C|1|0|Log Operacao|Log Operacao
T62|17|T62_XMLID|C|36|0|Id do XML.|Id do XML
T62|18|T62_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusão Sistemica
T62|19|T62_DTRANS|D|8|0|Dt Transmi|Data Transmissão
T62|20|T62_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T62|21|T62_DTRECP|D|8|0|Hr. Recept|Hora Receptação
T62|22|T62_HRRECP|C|8|0|Hr. Recept|Hora Receptação
T62|23|T62_LAYOUT|C|30|0|Ver. Layout|Versão do Layout
--- ### T63
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T63|01|T63_FILIAL|C|6|0|Filial|Filial
T63|02|T63_ID|C|6|0|ID|Identificador do Registro
T63|03|T63_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T63|04|T63_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T63|05|T63_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T63|06|T63_CPF|C|11|0|CPF Benef.|CPF do Beneficiário
T63|07|T63_IDBENE|C|6|0|Id. Benef.|Id. Benef. Previdenciário
T63|08|T63_TPBENE|C|2|0|Tipo Benef.|Tipo do Benefício Previd.
T63|09|T63_NUMBEN|C|20|0|Núm. Benef.|Núm Benef. Previdenciário
T63|10|T63_DEMPAG|C|30|0|Ident. Dem.|Núm Benef. Previdenciário
T63|11|T63_IDBEN|C|6|0|Id. Benef.|ID do Beneficiário
T63|12|T63_INDRRA|C|1|0|Ind. Ren RRA|Ind. Rendimentos RRA
T63|13|T63_TPPRRA|C|1|0|Tp. Proc RRA|Tp. Processo RRA
T63|14|T63_NRPRRA|C|21|0|Nr Proc. RRA|Nr. Processo RRA
T63|15|T63_DESCRA|C|50|0|Des. Ren RRA|Des. Rendimentos RRA
T63|16|T63_QTMRRA|N|5|1|Qt. Mes. RRA|Qtd. Meses RRA
T63|17|T63_VLRCUS|N|15|2|Vlr. Des. Ju|Vlr. Despesas Judicias
T63|18|T63_VLRADV|N|15|2|Vlr. Des Adv|Vlr. Despesas Advogados
--- ### T64
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T64|01|T64_FILIAL|C|6|0|Filial|Filial
T64|02|T64_ID|C|6|0|ID|Identificador do Registro
T64|03|T64_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T64|04|T64_INDINC|C|1|0|Tipo Incidên|Tipo de Incidência
T64|05|T64_IDCATE|C|6|0|Id. Categ|Id Categoria
T64|06|T64_DCATEG|C|220|0|Des. Categor|Descrição da Categoria
--- ### T65
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T65|01|T65_FILIAL|C|6|0|Filial|Filial
T65|02|T65_ID|C|6|0|ID|Identificador do Registro
T65|03|T65_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T65|04|T65_IDTRAB|C|6|0|ID Trab.|ID do Trabalhador
T65|05|T65_CPFTRA|C|11|0|CPF Trab.|CPF do Trabalhador
--- ### T66
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T66|01|T66_FILIAL|C|6|0|Filial|Filial
T66|02|T66_ID|C|6|0|ID|Identificador do Regist
T66|03|T66_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T66|04|T66_ESTAB|C|6|0|Id. Estab.|Ident. Estabelecimento
T66|05|T66_NRINSE|C|30|0|Nr Ins Est|Nr. Insc. Estabelecimento
--- ### T67
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T67|01|T67_FILIAL|C|6|0|Filial|Filail do Sistema
T67|02|T67_ID|C|36|0|ID|Identificacao do Registro
T67|03|T67_NOMULT|C|250|0|Nome Mult|Nome Multinacional.
T67|04|T67_IDCONT|C|1|0|Ind. Control|Indentificac. Controlador
T67|05|T67_NCONTR|C|254|0|Nome. Contr.|Nome Controladora
T67|06|T67_IDJURC|C|6|0|Id Juris.Con|Id Jusrisdicao Controld.
T67|07|T67_JURCON|C|2|0|Jurisd.Contr|Jurisdicao Controladora
T67|08|T67_TIN|C|254|0|Tin. Control|Tax Identification Number
T67|09|T67_IENTRG|C|1|0|Resp.Entr.PP|Resp.Entrg.Pais.a.Pais
T67|10|T67_INDMOD|C|1|0|Ind. Modalid|Identifica a Modalidade
T67|11|T67_SUBSTI|C|254|0|Substitututa|Nome Substituta
T67|12|T67_IDJURS|C|6|0|Id Jur.Subs|Id Jurisdicao Subistitut.
T67|13|T67_JURSUB|C|2|0|Jur.Substit.|Jusrisdicao Substituta
T67|14|T67_TINSUB|C|14|0|TIN. Substit|TAX.Identit.Number.Subst.
T67|15|T67_DTINI|D|8|0|Dt. Inicio|Dt.Inicio.Per.Societario
T67|16|T67_DTFIM|D|8|0|Dt. Fim|Dt.Final.Per. Societario
T67|17|T67_MOEDA|C|3|0|Tip.Moeda|Moeda Pais a Pais
T67|18|T67_DMOEDA|C|220|0|Desc Moeda|Descição Moeda
T67|19|T67_STATUS|C|1|0|Status Reg|Status do Registro
T67|20|T67_IDIOMA|C|2|0|Idioma|idioma Info. Adicionais
--- ### T68
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T68|01|T68_FILIAL|C|6|0|Filial|Filial do Sistema
T68|02|T68_ID|C|36|0|ID|Identificacao do Registro
T68|03|T68_IDJURI|C|6|0|Id Jusrisdic|Id Jusrisdicao
T68|04|T68_JURIDC|C|2|0|Jurisdicao|Jurisdicao
T68|05|T68_VLRECE|N|16|2|Receit. Estr|Rec.Proven.Moed.Estrangei
T68|06|T68_VLRECR|N|16|2|Vl.Rec.Reais|Receitas em Reais
T68|07|T68_VLRELE|N|16|2|Vl.Rel.Estr.|Vl.Parts.Relac.Moed.Estr.
T68|08|T68_VLRELR|N|16|2|Vl.Rec.Real|Vl.Receit.Parts.Rel.Reias
T68|09|T68_VLTOTE|N|16|2|Vl.Rec.Tot.E|Rec.Total.Moeda.Estrang.
T68|10|T68_VLTOTA|N|16|2|Rec.Total|Receita Total
T68|11|T68_LPESTR|N|16|2|Lucr.Prej.Es|Vl.Luc.Prej.Antes.IR.Estr
T68|12|T68_LPREAL|N|16|2|Lucr.Prej.Re|Vl.Luc.Prej.Antes.IR.Real
T68|13|T68_IRESTR|N|16|2|Vl.IR.Estran|Vl IR Pago Moeda Estrang.
T68|14|T68_IRREAL|N|16|2|Vl.Ir.Real|Vl IR Pago em Reais
T68|15|T68_IRDEVE|N|16|2|Vl.Dev.Estr.|IR Devido Moeda Estrang.
T68|16|T68_IRDEVR|N|16|2|Vl.Dev.Real|IR Devido Em Reais
T68|17|T68_CPSOCE|N|16|2|Cap.Soc.Estr|Capital Social Moeda Estr
T68|18|T68_CPSOCR|N|16|2|Cap.Soc.Real|Capital Social em Reais
T68|19|T68_LACUME|N|16|2|Lucr.Acmul.E|Lucro Acumulado Moeda Est
T68|20|T68_LACUMR|N|16|2|Lucr.Acuml.R|Lucro Acumulado Em Reais
T68|21|T68_ATVTES|N|16|2|Ativ.Tang.E|Ativ.Tangiveis Moeda Es
T68|22|T68_ATVTR|N|16|2|Ativ.Tang.R|Atv.Tangiveis Em Reais
T68|23|T68_NUMEMP|N|16|0|Num.Empreg.|Numero de Empregados
T68|24|T68_STATUS|C|1|0|Status Reg|Status Registro
--- ### T69
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T69|01|T69_FILIAL|C|6|0|Filial|Filial do Sistema
T69|02|T69_ID|C|36|0|ID|Identificador do Registro
T69|03|T69_IDJRDF|C|6|0|Id Jur Difer|Id Jurisdicao Diferente
T69|04|T69_JURDIF|C|2|0|Jurididc.Dif|Jurisdicao Diferente
T69|05|T69_NOME|C|254|0|Nome|Nome/Raz.Soc.Entid.Enteg.
T69|06|T69_TIN|C|240|0|TAX Iden.Num|TAX Identification Number
T69|07|T69_IDJRTI|C|6|0|Id Jur. Tin|Id Jusrisdicao TIN
T69|08|T69_JURTIN|C|2|0|Jur.Emis.TIN|Jurisdicao Emissao TIN
T69|09|T69_NI|C|254|0|Num. Identif|Numero de Identificacao
T69|10|T69_IDJRNI|C|6|0|Id Jur. NI|Id Juridic NI
T69|11|T69_JURNI|C|2|0|Jur.Emiss.NI|Jurisdicao de Emissao NI
T69|12|T69_TIPONI|C|2|0|Tipo do NI|Tipo do NI
T69|13|T69_TIPEND|C|7|0|Tipo Enderec|Tipo Endereco
T69|14|T69_ENDERE|C|150|0|Endereco|Endereco
T69|15|T69_NUMTEL|C|15|0|Num.Telefone|Numero Telefone
T69|16|T69_EMAIL|C|115|0|E-mail Cont.|E-mail para Contato
T69|17|T69_ATIV_1|C|1|0|Pesq.Desenv.|Pesquisa e Desenvolv.
T69|18|T69_ATIV_2|C|1|0|Gest.Intelec|Gestao Propried.Intelect.
T69|19|T69_ATIV_3|C|1|0|Compras|Compras
T69|20|T69_ATIV_4|C|1|0|Manuf.Produc|Manufatura ou Producao
T69|21|T69_ATIV_5|C|1|0|Ven.Mark.Dis|Venda, Marketing ou Distr
T69|22|T69_ATIV_6|C|1|0|Srv.Gest.Sup|Servico Admin.Gest.ou Sup
T69|23|T69_ATIV_7|C|1|0|P.S.Parts.NR|Prest.Serv.Parts.N.Relac.
T69|24|T69_ATIV_8|C|1|0|Dpt.Fin.Grup|Depto. Financeiro do Grup
T69|25|T69_ATIV_9|C|1|0|Serv.Fin.Reg|Serv.Fin.Regulamentados
T69|26|T69_ATIV10|C|1|0|Seguro|Seguro
T69|27|T69_ATIV11|C|1|0|Gstao Acoes|Gst.Ac.e Outros Instr.Cap
T69|28|T69_ATIV12|C|1|0|Inativa|Inativa
T69|29|T69_ATIV13|C|1|0|Outros|Outros
T69|30|T69_DESCOU|C|254|0|Desc.Ativ.ED|Descr.Ativ.Econ.Desemp.
T69|31|T69_OBSERV|C|254|0|Observacao|Outras Informacoes
T69|32|T69_STATUS|C|1|0|Status Reg|Status Registro
T69|33|T69_INCREM|C|36|0|Incremental|Incremental
T69|34|T69_IDJPAI|C|6|0|Id Jur Pai|Id Jur Pai
--- ### T6A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6A|01|T6A_FILIAL|C|6|0|Filial|Filial do Sistema
T6A|02|T6A_ID|C|36|0| ID|Identificacao do Registro
T6A|03|T6A_IDJURI|C|6|0|Id Juridic|Id Jusrisdicao
T6A|04|T6A_JURIDC|C|254|0|Jurisdicao|Jurisdicao Trinutaria
T6A|05|T6A_RNRELC|C|1|0|Rec.N.Relaci|Rec.Proven.Parts.N.Relaci
T6A|06|T6A_RRELAC|C|1|0|Rec.Relacion|Rec.Proven.Relacionadas
T6A|07|T6A_RECTOT|C|1|0|Receit.Total|Receita Total
T6A|08|T6A_LPANIR|C|1|0|Luc.Pre.A.IR|Lucr.Prejuiso Antes do IR
T6A|09|T6A_IRPAGO|C|1|0|Ind.IR Pago|Idicador IR Pago
T6A|10|T6A_IRDEVI|C|1|0|IR Devido|Idicador IR Devido
T6A|11|T6A_CAPSOC|C|1|0|Ind.Cap.Soc.|Indicador Capital Social
T6A|12|T6A_LUCACU|C|1|0|Luc.Acumulad|Indicador Lucro Acumulado
T6A|13|T6A_ATIVOT|C|1|0|Ativo Tangiv|Ativo Tangivel
T6A|14|T6A_NUMEMP|C|1|0|Ind.Num.Empr|Indicador Num. Empregados
T6A|15|T6A_OBS|C|254|0|Observacoes|Observacoes
T6A|16|T6A_INCREM|C|36|0|Auto Imcrem.|Campo Auto Incrementavel
--- ### T6B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6B|01|T6B_FILIAL|C|6|0|Filial|Filial
T6B|02|T6B_ID|C|6|0|ID|Identificador do Registro
T6B|03|T6B_VERSAO|C|14|0|Id. Ver. Reg| Id da versão do registro
T6B|04|T6B_IDESTA|C|6|0|Id. Estab.|Id. Estabelecimento
T6B|05|T6B_INDCOM|C|6|0|Indic. Comer|Indicativ Comercialização
T6B|06|T6B_TPINSA|C|1|0|Tp Inscrição|Tipo de Inscrição
T6B|07|T6B_NRINSA|C|15|0|Num. Insc.|Número de Inscrição
T6B|08|T6B_SERIE|C|5|0|Série|Série
T6B|09|T6B_NUMDOC|C|20|0|Num. Documen|Numero do Documento
T6B|10|T6B_DTEMIS|D|8|0|Dt. Emissão|Data de Emissão
T6B|11|T6B_VLBRUT|N|15|2|Val. Bruto|Valor Bruto
T6B|12|T6B_VLCONT|N|15|2|Val. Contrib|Valor da Contribuição
T6B|13|T6B_VLGILR|N|15|2|Val. Gilrat|Valor Gilrat
T6B|14|T6B_VLSENA|N|15|2|Val. Senar|Valor Senar
--- ### T6C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6C|01|T6C_FILIAL|C|6|0|Filial|Filial
T6C|02|T6C_ID|C|36|0|ID|Identificador do Registro
T6C|03|T6C_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6C|04|T6C_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6C|05|T6C_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6C|06|T6C_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6C|07|T6C_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6C|08|T6C_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6C|09|T6C_DESTAB|C|220|0|Desc. Estab.|Descrição Estabelecimento
--- ### T6D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6D|01|T6D_FILIAL|C|6|0|Filial|Filial
T6D|02|T6D_ID|C|36|0|ID|Identificador do Registro
T6D|03|T6D_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6D|04|T6D_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6D|05|T6D_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6D|06|T6D_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6D|07|T6D_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6D|08|T6D_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6D|09|T6D_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6D|10|T6D_DTRABA|C|30|0|Matric. Trab|Matricula Trabalhador
T6D|11|T6D_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6D|12|T6D_DCODCA|C|220|0|Des.Categ.Tr|Des. Categ. Trabalhador
T6D|13|T6D_NOMEVE|C|5|0|Nome Evento|Nome do Evento
--- ### T6E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6E|01|T6E_FILIAL|C|6|0|Filial|Filial
T6E|02|T6E_ID|C|36|0|ID|Identificador do Registro
T6E|03|T6E_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6E|04|T6E_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6E|05|T6E_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6E|06|T6E_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6E|07|T6E_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6E|08|T6E_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6E|09|T6E_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6E|10|T6E_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6E|11|T6E_IDRUBR|C|6|0|Cód. Rubrica|Código da Rubrica
T6E|12|T6E_DRUBR|C|220|0|Des. Rubrica|Descrição Rubrica
T6E|13|T6E_QTDRUB|N|13|2|Qtd. Rubrica|Quantidade da Rubrica
T6E|14|T6E_FATORR|N|6|2|Fator Rubric|Fator Rubrica
T6E|15|T6E_VLRUNT|N|15|2|Vlr.Unit.|Valor Unitário
T6E|16|T6E_VLRRUB|N|15|2|Vlr. Rubrica|Valor da Rubrica
T6E|17|T6E_APURIR|C|1|0|Tp.Apur.IR|Tipo de Apuração IR
T6E|18|T6E_DTRABA|C|30|0|Matric. Trab|Matricula Trabalhador
T6E|19|T6E_TPDESC|C|1|0|tipo de desc|Tipo de desconto.
T6E|20|T6E_INTFIN|C|6|0|Inst. Fin|Instituiçao financeira
T6E|21|T6E_DINTFI|C|3|0|Descr. Inst|Descri. Inst. Fin.
T6E|22|T6E_NRDOC|C|15|0|Nr Con. Empr|Nr. Contr. Emprestimo
T6E|23|T6E_OBSERV|M|10|0|Info. Descon|Info. Desconto
--- ### T6F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6F|01|T6F_FILIAL|C|6|0|Filial|Filial
T6F|02|T6F_ID|C|36|0|ID|Identificador do Registro
T6F|03|T6F_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6F|04|T6F_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6F|05|T6F_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6F|06|T6F_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6F|07|T6F_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6F|08|T6F_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6F|09|T6F_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6F|10|T6F_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6F|11|T6F_CNPJOP|C|14|0|CNPJ Operado|CNPJ Oper. Plano Saude
T6F|12|T6F_REGANS|C|6|0|Reg. ANS|Reg. Agencia Nacional Sau
T6F|13|T6F_VLPGTI|N|15|2|Vl. Pg. Titu|Vlr. Pago pelo Titular
--- ### T6G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6G|01|T6G_FILIAL|C|6|0|Filial|Filial
T6G|02|T6G_ID|C|36|0|ID|Identificador do Registro
T6G|03|T6G_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6G|04|T6G_INDAPU|C|1|0|IInd.Per.Apu|Indic.Período Apuração
T6G|05|T6G_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6G|06|T6G_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6G|07|T6G_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6G|08|T6G_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6G|09|T6G_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6G|10|T6G_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6G|11|T6G_CNPJOP|C|14|0|CNPJ Operado|CNPJ Oper. Plano Saude
T6G|12|T6G_CPFDEP|C|11|0|CPF Depend.|CPF Dependente
T6G|13|T6G_NOMDEP|C|60|0|Nome Depend.|Nome do Dependente
T6G|14|T6G_DTNDEP|D|8|0|Dt. Nas. Dep|Data Nascimento Dependent
T6G|15|T6G_VPGDEP|N|15|2|Vlr. Pgo Dep|Vlr. Ref. Plano Saude Dep
T6G|16|T6G_TPDEP|C|6|0|Id Tp Dep|Id. Tipo Dependente
--- ### T6H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6H|01|T6H_FILIAL|C|6|0|Filial|Filial
T6H|02|T6H_ID|C|36|0|ID|Identificador do Registro
T6H|03|T6H_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6H|04|T6H_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6H|05|T6H_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6H|06|T6H_TRABAL|C|6|0|Id.Trabalh.|Id. do Trabalhador
T6H|07|T6H_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6H|08|T6H_DTLEI|D|8|0|Data Lei|Data da Lei
T6H|09|T6H_NUMLEI|C|12|0|Núm. Lei|Número da Lei
T6H|10|T6H_PERREF|C|6|0|Periodo|Período Ref. Difer. Remun
T6H|11|T6H_ORGSUC|C|1|0|Rem.Org.Suce|Remuneração Org. Sucessão
--- ### T6I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6I|01|T6I_FILIAL|C|6|0|Filial|Filial
T6I|02|T6I_ID|C|36|0|ID|Identificador do Registro
T6I|03|T6I_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6I|04|T6I_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6I|05|T6I_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6I|06|T6I_TRABAL|C|6|0|Id.Trabalh.|Id. do Trabalhador
T6I|07|T6I_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6I|08|T6I_DTLEI|D|8|0|Data Lei|Data da Lei
T6I|09|T6I_NUMLEI|C|12|0|Núm. Lei|Número da Lei
T6I|10|T6I_PERREF|C|6|0|Período|Período Ref. Dif. Remun
T6I|11|T6I_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6I|12|T6I_DESTAB|C|220|0|Desc. Estab.|Descrição Estabelecimento
T6I|13|T6I_ORGSUC|C|1|0|Rem.Org.Suce|Remuneração Org. Sucessão
--- ### T6J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6J|01|T6J_FILIAL|C|6|0|Filial|Filial
T6J|02|T6J_ID|C|36|0|ID|Identificador do Registro
T6J|03|T6J_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6J|04|T6J_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6J|05|T6J_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6J|06|T6J_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6J|07|T6J_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6J|08|T6J_DTLEI|D|8|0|Data Lei|Data da Lei
T6J|09|T6J_NUMLEI|C|12|0|Núm. Lei|Número da Lei
T6J|10|T6J_PERREF|C|6|0|Período|Período Ref. Dif. Remun
T6J|11|T6J_ESTABE|C|6|0|Ident. Estab|Ident. Estabelecimento
T6J|12|T6J_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6J|13|T6J_DTRABA|C|30|0|Matric. Trab|Matricula Trabalhador
T6J|14|T6J_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6J|15|T6J_DCODCA|C|220|0|Des.Categ.Tr|Des.Categ. Trabalhador
T6J|16|T6J_ORGSUC|C|1|0|Rem.Org.Suce|Rem.Org.Suce Remuneração
T6J|17|T6J_NOMEVE|C|5|0|Nome Evento|Nome do Evento
--- ### T6K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6K|01|T6K_FILIAL|C|6|0|Filial|Filial
T6K|02|T6K_ID|C|36|0|ID|Identificador do Registro
T6K|03|T6K_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6K|04|T6K_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T6K|05|T6K_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T6K|06|T6K_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T6K|07|T6K_DEMPAG|C|30|0|Id. Dem. Pag|Ident. Demonst. Pagamento
T6K|08|T6K_DTLEI|D|8|0|Data Lei|Data da Lei
T6K|09|T6K_NUMLEI|C|12|0|Núm. Lei|Número da Lei
T6K|10|T6K_PERREF|C|6|0|Período|Período Ref. Dif. Remun
T6K|11|T6K_ESTABE|C|6|0|Id. Estab.|Ident. Estabelecimento
T6K|12|T6K_IDTRAB|C|6|0|Id. Trabalh.|ID do Trabalhador
T6K|13|T6K_CODCAT|C|6|0|Id.Categ.Trb|Categ. Trabalhador
T6K|14|T6K_IDRUBR|C|6|0|Cód. Rubrica|Código da Rubrica
T6K|15|T6K_DRUBR|C|220|0|Des. Rubrica|Descrição Rubrica
T6K|16|T6K_QTDRUB|N|13|2|Qtd. Rubrica|Quantidade da Rubrica
T6K|17|T6K_FATORR|N|6|2|Fator Rubric|Fator Rubrica
T6K|18|T6K_VLRUNT|N|16|2|Vlr.Unit.|Valor Unitário
T6K|19|T6K_VLRRUB|N|16|2|Vlr. Rubrica|Valor da Rubrica
T6K|20|T6K_APURIR|C|1|0|Tp.Apur.IR|Tipo Apuração IR
T6K|21|T6K_DTRABA|C|30|0|Matric. Trab|Matricula Trabalhador
--- ### T6L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6L|01|T6L_FILIAL|C|6|0|Filial|Filial
T6L|02|T6L_ID|C|36|0|Id.|Identificador do Registro
T6L|03|T6L_DTLANC|D|8|0|Data Lanc.|Data do Lançamento
T6L|04|T6L_IDANPI|C|10|0|Id. ANP Item|Id. ANP Item
T6L|05|T6L_ANPITE|C|9|0|ANP Item|Código ANP Item
T6L|06|T6L_DANPIT|C|220|0|Desc. ANP It|Descrição ANP Item
T6L|07|T6L_IDOANP|C|36|0|Id. Op. ANP|Id. Operação ANP
T6L|08|T6L_OPEANP|C|7|0|Oper. ANP|Cod. Operação ANP.
T6L|09|T6L_ESPECI|C|220|0|Espec. Oper.|Espec. Oper. ANP
T6L|10|T6L_QTDANP|N|16|5|Qtd. ANP|Quantidade ANP
T6L|11|T6L_STATUS|C|1|0|Status Reg.|Status do Registro
T6L|12|T6L_IDANPT|C|10|0|ID ANP Trans|ID ANP Item Transferência
T6L|13|T6L_ITANPT|C|9|0|ANP It Trans|Código ANP Item Transfer
T6L|14|T6L_DANPTR|C|220|0|Dsc ANP Tran|Dsc item ANP Tranferência
--- ### T6M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6M|01|T6M_FILIAL|C|6|0|Filial|Filial
T6M|02|T6M_ID|C|6|0|ID|Id. Ver. Reg
T6M|03|T6M_VERSAO|C|14|0|Id. Ver. Reg|Id Versão Registro
T6M|04|T6M_SEQUEN|C|3|0|Sequência|Sequência
T6M|05|T6M_CODCID|C|6|0|Id.CID|Id.CID
T6M|06|T6M_DCODCI|C|220|0|Des.CID|Des.CID
T6M|07|T6M_DIASAF|C|3|0|Qtde.Dias Af|Qtde.Dias Afast.
T6M|08|T6M_IDPROF|C|6|0|Id. Profissi|Id. Profissional Saúde
T6M|09|T6M_DIDPRO|C|220|0|Des.Prof.|Des. Profissional
T6M|10|T6M_NRIUFD|C|220|0|UF do OC|UF do Orgão de Classe
--- ### T6N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6N|01|T6N_FILIAL|C|6|0|Filial|Filial do Sistema
T6N|02|T6N_ID|C|36|0|ID|Identificação do Registro
T6N|03|T6N_NMTRAB|C|60|0|Nome Trabalh|Nome Trab.Sem Vínculo
T6N|04|T6N_CODCBO|C|6|0|CBO|Classificação Brasileira
T6N|05|T6N_QTDDIA|N|8|0|Dias Trab.|Qtd. Dias Trabalho
T6N|06|T6N_DTNASC|D|8|0|Dat. Nascim.|Data de Nascimento
T6N|07|T6N_NATATI|C|1|0|Nat. Ativid.|Natureza da Atividade
--- ### T6O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6O|01|T6O_FILIAL|C|6|0|Filial|Filial
T6O|02|T6O_ID|C|6|0|ID|Identificador do Registro
T6O|03|T6O_VERSAO|C|14|0|Id. Ver. Reg|Id Versao Registro
T6O|04|T6O_INDAPU|C|1|0|Ind.Per.Apur|Indic.Periodo Apuração
T6O|05|T6O_PERAPU|C|6|0|Per.Apuração|Per.Apuração
T6O|06|T6O_CPF|C|11|0|CPF Benef.|CPF do Beneficiario
T6O|07|T6O_IDBENE|C|6|0|Id. Benef.|Id. Benef. Previdenciario
T6O|08|T6O_IDRUBR|C|6|0|Cod. Rubrica|Codigo da Rubrica
T6O|09|T6O_DRUBR|C|220|0|Des. Rubrica|Descricao Rubrica
T6O|10|T6O_VLRRUB|N|16|2|Vlr. Rubrica|Valor da Rubrica
T6O|11|T6O_TABRUB|C|8|0|Tab Rubrica|Tabela Rubrica
T6O|12|T6O_QTDRUB|N|12|2|Qtd Rubrica|Quantidade Rubrica
T6O|13|T6O_FATRUB|N|6|2|Fat Rubrica|Fator Rubrica
T6O|14|T6O_APUIR|C|1|0|Ind Apur IR|Ind Apuraçao IR
T6O|15|T6O_DEMPAG|C|30|0|Ident. Dem.|Núm Benef. Previdenciário
T6O|16|T6O_TPINSC|C|1|0|Tp. Insc.|Tipo de Inscriçao
T6O|17|T6O_NRINSC|C|15|0|Nr. Insc.|Numero de Inscrição
T6O|18|T6O_IDBEN|C|6|0|Id. Benef.|ID do Beneficiário
T6O|19|T6O_TPDESC|C|1|0|tpDesc|Tipo de desconto
T6O|20|T6O_INTFIN|C|6|0|inst.Financ|Inituiçao financeira
T6O|21|T6O_DINTFI|C|3|0|Descri. Inst|Desriçao Instituiçao Fin.
T6O|22|T6O_NRDOC|C|15|0|Nr. con. Emp|Número do contrato Empr.
T6O|23|T6O_OBSERV|M|10|0|Info. Desc.|Informações do desconto
--- ### T6P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6P|01|T6P_FILIAL|C|6|0|Filial|Filial
T6P|02|T6P_ID|C|36|0|ID|Identificador do registro
T6P|03|T6P_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T6P|04|T6P_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
T6P|05|T6P_TPPGTO|C|1|0|Tipo Pgto.|Tipo de Pagamento
T6P|06|T6P_PERREF|C|6|0|Per. Referen|Per. Referencia
T6P|07|T6P_IDEDMD|C|30|0|Ident Dem Vl|Ident Demonstrativo Valor
T6P|08|T6P_INDPGT|C|1|0|Ind Pgto|Indicativo Pgto
T6P|09|T6P_VLRLIQ|N|15|2|Valor Líquid|Valor Líquido
--- ### T6Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6Q|01|T6Q_FILIAL|C|6|0|Filial|Filial
T6Q|02|T6Q_ID|C|36|0|ID|Identificador do registro
T6Q|03|T6Q_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T6Q|04|T6Q_DTPGTO|D|8|0|Data Pgto|Data do Pagamento
T6Q|05|T6Q_TPPGTO|C|1|0|Tipo Pgto.|TIpo de Pagamento
T6Q|06|T6Q_PERREF|C|6|0|Per. Referen|Per. Referencia
T6Q|07|T6Q_IDEDMD|C|30|0|Ident Dem Vl|Ident Demonstrativo Vlr
T6Q|08|T6Q_INDPGT|C|1|0|Ind Pgto|Indicativo Pgto
T6Q|09|T6Q_IDRUBR|C|6|0|Cód. Rubrica|Código da Rubrica
T6Q|10|T6Q_DRUBR|C|220|0|Des. Rubrica|Descrição da Rubrica
T6Q|11|T6Q_QTDRUB|N|7|2|Qtd. Rubrica|Quantidade da Rubrica
T6Q|12|T6Q_FATRUB|N|6|2|Fat. Rubrica|Fator da Rubrica
T6Q|13|T6Q_VLRUNI|N|15|2|Vlr Unitário|Valor unitário da rubrica
T6Q|14|T6Q_VLRRUB|N|15|2|Vlr. Rubrica|Valor da Rubrica
T6Q|15|T6Q_RUBRIC|C|30|0|Cod. Rubrica|Cod. Rubrica
T6Q|16|T6Q_IDTABR|C|8|0|Id. Tab Rubr|Ident. Tab. Rubrica
--- ### T6R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6R|01|T6R_FILIAL|C|6|0|Filial|Filial
T6R|02|T6R_ID|C|36|0|ID|Identificação do registro
T6R|03|T6R_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T6R|04|T6R_DTPGTO|D|8|0|Dt Pgto|Data de Pagamento
T6R|05|T6R_TPPGTO|C|1|0|Tipo Pgto| Tipo de Pagamento
T6R|06|T6R_PERREF|C|6|0|Per. Referen|Per. Referencia
T6R|07|T6R_IDEDMD|C|30|0|Ident Dem Vl|Ident Demonstrativo de Vl
T6R|08|T6R_INDPGT|C|1|0|Ind Pgto|Indicativo Pgto
T6R|09|T6R_IDRUBR|C|6|0|Cod. Rubrica|Codigo da Rubrica
T6R|10|T6R_DRUBR|C|220|0|Des. Rubrica|Descrição da Rubrica
T6R|11|T6R_QTDRUB|N|7|2|Qtd. Rubrica|Quantidade da Rubrica
T6R|12|T6R_FATRUB|N|6|2|Fat. Rubrica|Fator da Rubrica
T6R|13|T6R_VLRUNI|N|15|2|Vlr. Unitari|Vlr. Unitario
T6R|14|T6R_VLRRUB|N|15|2|Vlr. Rubrica|Valor da Rubrica
T6R|15|T6R_RUBRIC|C|30|0|Cod. Rubrica|Cod. Rubrica
T6R|16|T6R_IDTABR|C|8|0|Id. Tab Rubr|Id. Tab Rubrica
--- ### T6S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6S|01|T6S_FILIAL|C|6|0|Filial|Filial
T6S|02|T6S_ID|C|6|0|ID|Identificador do Registro
T6S|03|T6S_HABILI|C|1|0|Habilitado|Evento Habilitado
T6S|04|T6S_IDEVEN|C|6|0|Id. Evento|Id. do Evento
T6S|05|T6S_EVENTO|C|220|0|Evento|Descrição do Evento
--- ### T6T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6T|01|T6T_FILIAL|C|6|0|Filial|Filial
T6T|02|T6T_ID|C|6|0|ID|Identificador do Registro
T6T|03|T6T_IDEVEN|C|6|0|Id. Evento|Id. do Evento
T6T|04|T6T_EVENTO|C|220|0|Evento|Descrição do Evento
--- ### T6U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6U|01|T6U_FILIAL|C|6|0|Filial|Filial
T6U|02|T6U_ID|C|6|0|ID|Identificador Registro
T6U|03|T6U_NATOPE|C|36|0|Id. Nat.Oper|Id. Natureza da Operação
T6U|04|T6U_CODNAT|C|8|0|Nat.Oper.|Natureza Operação
T6U|05|T6U_DNATOP|C|220|0|Desc. Nat.Op|Descrição Nat. Operação
T6U|06|T6U_TPOPER|C|1|0|Tp. Oper.|Tipo de Operação
T6U|07|T6U_VLCONT|N|16|2|Vlr.Contab.|Valor Contábil
T6U|08|T6U_BASE|N|16|2|B.Cálculo|Base de Cálculo
T6U|09|T6U_IMPCRD|N|16|2|Vl.Crdto.Déb|Vlr.Crédito/Débito
T6U|10|T6U_ISENNT|N|16|2|Vl.Isen.NT|Vlr. Isento / NT
T6U|11|T6U_OUTROS|N|16|2|Vlr.Outros|Vlr.Outros
--- ### T6V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6V|01|T6V_FILIAL|C|6|0|Filial|Filial
T6V|02|T6V_ID|C|6|0|ID|Identificador do Registro
T6V|03|T6V_ESTADO|C|6|0|Id.Estado|Identificador do Estado
T6V|04|T6V_DESTAD|C|220|0|Des.Estado|Descrição do Estado
T6V|05|T6V_NATOPE|C|36|0|Id.Nat.Oper.|Id. Natureza Operação
T6V|06|T6V_CODNAT|C|8|0|Nat.Oper.|Natureza Operação
T6V|07|T6V_DNATOP|C|220|0|D.Nat.Oper.|Desc. Nat. Operação
T6V|08|T6V_TPOPER|C|1|0|Tp. Operação|Tipo da operação
T6V|09|T6V_BASE|N|16|2|B.Cálculo|Base de cálculo
T6V|10|T6V_IMPCRD|N|16|2|Vl.Crdto/Déb|Vlr. Crédito/Débito
T6V|11|T6V_ISENNT|N|16|2|Vl.Isen/NT|Vlr. Isento / NT
T6V|12|T6V_OUTROS|N|16|2|Vl.Outros|Vlr. Outros
--- ### T6W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6W|01|T6W_FILIAL|C|6|0|Filial|Filial
T6W|02|T6W_ID|C|36|0|ID|Identificador do Registro
T6W|03|T6W_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T6W|04|T6W_TPINSC|C|1|0|Tp.Ins.Out.E|Tp.Insc. Outras empresas
T6W|05|T6W_NRINSC|C|15|0|Nr.Insc.Out.|Núm.Insc Outras Empresas
T6W|06|T6W_VLREMU|N|15|2|Vlr.Remuner.|Vlr.Remuneração
T6W|07|T6W_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T6W|08|T6W_CODCAT|C|6|0|Cod. Categor|Codigo Categoria
T6W|09|T6W_DCODCA|C|220|0|Des. Categor|Des. Categoria
--- ### T6X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6X|01|T6X_FILIAL|C|6|0|Filial|Filial
T6X|02|T6X_ID|C|6|0|ID|Identificador do registro
T6X|03|T6X_NATOPE|C|36|0|Id.Nat.Oper.|Id. Natureza da Operação
T6X|04|T6X_CODNAT|C|8|0|Nat.Oper.|Natureza Operação
T6X|05|T6X_DNATOP|C|220|0|Des.Nat.Oper|Desc. Natureza Operação
T6X|06|T6X_TPOPER|C|1|0|Tp. Operação|Tipo da Operação
T6X|07|T6X_BASE|N|16|2|B.Cálculo|Base de Cálculo
T6X|08|T6X_IMPCRD|N|16|2|Vl.Crdto/Déb|Vlr. Crédito/Débito
T6X|09|T6X_ISENNT|N|16|2|Vl.Isento/NT|Vlr. Isento / NT
T6X|10|T6X_OUTROS|N|16|2|Vl. Outros|Vlr. Outros
--- ### T6Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6Y|01|T6Y_FILIAL|C|6|0|Filial|Filial
T6Y|02|T6Y_ID|C|36|0|ID|Identificador do Registro
T6Y|03|T6Y_VERSAO|C|14|0|Id. Ver. Reg|Id. Da Versão do Registro
T6Y|04|T6Y_RECIBO|C|30|0|Num Id. Rec.|Num Id. Rec. Pagto
T6Y|05|T6Y_LOTACA|C|6|0|Id. Lotação|Id. Lotação
T6Y|06|T6Y_CNPJOP|C|14|0|Cnpj Operado|CNPJ Oper. Plano Saude
T6Y|07|T6Y_REGANS|C|6|0|Reg. ANS|Reg. Agencia Nacional Saú
T6Y|08|T6Y_VLPGTI|N|15|2|Vl. Pg. Titu|Vlr. Pago pelo Titular
T6Y|09|T6Y_TRABAL|C|6|0|Id. Trab.|Id. do Trabalhador
T6Y|10|T6Y_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T6Y|11|T6Y_TPINSC|C|1|0|Tp Inscricao|Tipo de Inscrição
T6Y|12|T6Y_NRINSC|C|15|0|Nr.Inscrição|Número de Inscrição
T6Y|13|T6Y_ESTABE|C|6|0|Id Estab Lot|Id do Estabelecimento Lot
T6Y|14|T6Y_SEQPER|C|3|0|Sequencial|Sequencial
T6Y|15|T6Y_CODLOT|C|30|0|Cod. Lotacao|Codigo da Lotacao
T6Y|16|T6Y_DTRABA|C|30|0|Matricula|Matricula do Trabalhador
--- ### T6Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T6Z|01|T6Z_FILIAL|C|6|0|Filial|Filial
T6Z|02|T6Z_ID|C|36|0|ID|Identificador do Registro
T6Z|03|T6Z_VERSAO|C|14|0|Id. Ver. Reg|Id. Da Versão do Registro
T6Z|04|T6Z_IDOPER|C|6|0|Id Operadora|Id. Operadora Plano Saude
T6Z|05|T6Z_SEQUEN|C|3|0|Sequencia|Sequencia
T6Z|06|T6Z_CPFDEP|C|11|0|CPF Depend.|CPF Dependente
T6Z|07|T6Z_DTNDEP|D|8|0|Dt. Nas. Dep|Data Nascimento Dependent
T6Z|08|T6Z_NOMDEP|C|60|0|Nome Depend.|Nome do Dependente
T6Z|09|T6Z_RELDEP|C|2|0|Rel. Depend.|Relação do Dependente
T6Z|10|T6Z_VPGDEP|N|15|2|Vlr. Pgo Dep|Vlr. Ref. Plano Saude Dep
T6Z|11|T6Z_LOTACA|C|6|0|Id. Lotação|Ident Lotação
T6Z|12|T6Z_TRABAL|C|6|0|Id. Trab.|Id. do Trabalhador
T6Z|13|T6Z_RECIBO|C|30|0|Num Id. Rec.|Num Id. Rec. Pagto
T6Z|14|T6Z_CNPJOP|C|14|0|Cnpj Operado|CNPJ Oper. Plano Saude
T6Z|15|T6Z_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T6Z|16|T6Z_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T6Z|17|T6Z_NRINSC|C|15|0|Nr.Inscrição|Número de Inscrição
T6Z|18|T6Z_ESTABE|C|6|0|Id Estab Lot|Ident Estabelecimento Lot
T6Z|19|T6Z_SEQPER|C|3|0|Sequencial|Sequencial
T6Z|20|T6Z_TPDEP|C|6|0|Id Tp Dep|Id. Tipo Dependente
T6Z|21|T6Z_DTPDE|C|220|0|Descr Tp Dep|Descricao Tipo Dependente
T6Z|22|T6Z_REGANS|C|6|0|Reg. ANS|Reg. Agencia Nacional Saú
T6Z|23|T6Z_CODLOT|C|30|0|Cod. Lotacao|Código da Lotacao
T6Z|24|T6Z_DTRABA|C|30|0|Matricula|Matricula do Trabalhador
--- ### T70
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T70|01|T70_FILIAL|C|6|0|Filial|Filial
T70|02|T70_ID|C|6|0|ID|Identificador do registro
T70|03|T70_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Registro
T70|04|T70_TPINSE|C|1|0|Tp Inscrição|Tipo de Inscrição
T70|05|T70_NRINSE|C|15|0|Nr Inscrição|Numero de Inscrição
T70|06|T70_INDAQU|C|1|0|Ind da Aquis|Indicativo da Aquisição
T70|07|T70_VLAQUI|N|16|2|Vl.Aquisição|Valor da Aquisição
T70|08|T70_VLCPPR|N|16|2|Val. Contrib|Valor da Contribuição
T70|09|T70_VLCPRE|N|16|2|Vlr Cont Jud|Valor da Contrib Judicial
T70|10|T70_VLRATN|N|16|2|Vlr GILRAT|Valor do GILRAT
T70|11|T70_VLSENR|N|16|2|Vlr SENAR|Valor do SENAR
T70|12|T70_VLCPCA|N|16|2|Vlr Cal Cont|Valor Cal Contrib Previd
T70|13|T70_VLRAPR|N|16|2|Vlr Cont Ben|Valor Cont Des dos Benef
T70|14|T70_VLRACA|N|16|2|Vlr Cal RAT|Valor Cálculado do RAT
T70|15|T70_VLSEDE|N|16|2|Vlr SENAR De|Valor Cont Dest ao SENAR
T70|16|T70_VLSECA|N|16|2|Vlr SENAR Ca|Valor Calc Contrib SENAR
--- ### T71
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T71|01|T71_FILIAL|C|6|0|Filial|Filial
T71|02|T71_ID|C|36|0|ID|Identificador Registro
T71|03|T71_CODIGO|C|7|0|CEST|Cod. Espec. ST
T71|04|T71_DESCRI|M|10|0|Descrição|Descrição
T71|05|T71_CONV|C|10|0|Convênio|Convênio
T71|06|T71_VALIDA|D|8|0|Data Vigenc.|Data final vigência CEST
--- ### T72
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T72|01|T72_FILIAL|C|6|0|Filial|Filial
T72|02|T72_ID|C|36|0|ID|Identificador do registro
T72|03|T72_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do Registro
T72|04|T72_INDAPU|C|1|0|Ind.Per.Apur|Indic.Período Apuração
T72|05|T72_PERAPU|C|6|0|Per.Apuração|Período da Apuração
T72|06|T72_IDRESP|C|36|0|Id. Resp.|Id. Responsavel
T72|07|T72_DESCRE|C|220|0|Desc. Resp.|Desc. Responsavel
T72|08|T72_EVENTO|C|1|0|Id. Evento|Identificação do evento
T72|09|T72_STATUS|C|1|0|Status Reg.|Status do registro
T72|10|T72_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T72|11|T72_PROTUL|C|44|0|Ult. Prot.|Prot. última transmissão
T72|12|T72_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transmiss
T72|13|T72_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T72|14|T72_XMLID|C|36|0|Id do XML.|Id do XML
T72|15|T72_LOGOPE|C|1|0|Log Operacao|Log Operacao
T72|16|T72_GRVTOT|L|1|0|Totalizador|           Gerou Totaliza
T72|17|T72_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusão Sistemica
T72|18|T72_DTRANS|D|8|0|Dt. Transm|Data Transmissão
T72|19|T72_HTRANS|C|8|0|Hr. Transm|Hora Transmissão
T72|20|T72_DTRECP|D|8|0|Dt. Recept|Data Receptação
T72|21|T72_HRRECP|C|8|0|Hr. Recept|Hora de Receptação
--- ### T79
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T79|01|T79_FILIAL|C|6|0|Filial|Filial
T79|02|T79_ID|C|6|0|Id. Func.|Id. do Funcionario
T79|03|T79_VERSAO|C|14|0|Id. Ver Reg|Id da Versao do Registro
T79|04|T79_CNPJSD|C|14|0|CNPJ Sind.|CNPJ Sindical Trabalhador
--- ### T7A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7A|01|T7A_FILIAL|C|6|0|Filial|Filial do Sistema
T7A|02|T7A_IDENT|C|36|0|ID|Identificação
T7A|03|T7A_TPEVEN|C|6|0|Cod. Evento|Código do evento
T7A|04|T7A_DESCRI|C|100|0|Desc Evento|Descrição do evento
T7A|05|T7A_CHVNF|C|36|0|Chave NF|Chave da Nota Fiscal
T7A|06|T7A_EST|C|6|0|Estado Autor|Estado autor
T7A|07|T7A_CANC|C|1|0|Cancelamento|Cancelamento
T7A|08|T7A_TPAUT|C|1|0|Tipo Autor|Tipo do autor
T7A|09|T7A_PGTO|C|1|0|PAGTO|Indicador de Quitação
T7A|10|T7A_INDACE|C|1|0|Aceitação|Indicador de Aceitação
T7A|11|T7A_MOTIVO|M|255|0|Motivo|Justificativa
T7A|12|T7A_PROT|C|17|0|Protocolo|Protocolo do evento
T7A|13|T7A_SERIE|C|20|0|Serie|Serie Documento Fiscal
T7A|14|T7A_NUMDOC|C|60|0|Numero NF|Número Documento Fiscal
T7A|15|T7A_CODPAR|C|36|0|Participante|Codigo do Participante
T7A|16|T7A_NOME|C|220|0|Nome Partic|Nome do Participante
T7A|17|T7A_ESPECI|C|5|0|Especie NF|Especie NF
T7A|18|T7A_STATUS|C|1|0|Status|Status do Evento
T7A|19|T7A_DTPREV|D|8|0|Dt Entrega|Data Prevista de Entrega
T7A|20|T7A_DTEMIS|D|8|0|Data Emissao|Data de Emissao do Evento
T7A|21|T7A_CHVELE|C|44|0|Chv Eletr|Chv Eletrônica Documento
T7A|22|T7A_SEQLOT|C|6|0|Seq Lote|Sequência do Lote
--- ### T7B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7B|01|T7B_FILIAL|C|6|0|Filial|Filial do Sistema
T7B|02|T7B_IDENT|C|36|0|Ident Evento|Identificação do Evento
T7B|03|T7B_ITEM|C|4|0|Item Nota|Item da nota fiscal
T7B|04|T7B_CODTRI|C|6|0|C. tributo|Código do tributo
T7B|05|T7B_DCODTR|C|220|0|Desc Trib.|Descrição tributo
T7B|06|T7B_VLBASE|N|14|2|Vlr Base|Valor base do tributo
T7B|07|T7B_CODCRE|N|2|0|Cod Cred Pre|Código Crédito Presumido
T7B|08|T7B_PERC|N|5|2|% Cred. Pres|% Crédito Presumido
T7B|09|T7B_VALOR|N|14|2|Vlr Cred Pre|Vlr de Crédito Presumido
--- ### T7C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7C|01|T7C_FILIAL|C|6|0|Filial|Filial do Sistema
T7C|02|T7C_IDENT|C|36|0|ID|Identificação
T7C|03|T7C_ITEM|C|4|0|Item|Item
T7C|04|T7C_CODTRI|C|6|0|Cod Trib|Código do Tributo
T7C|05|T7C_DCODTR|C|220|0|Desc Trib|Descrição do Tributo
T7C|06|T7C_QUANT|N|14|2|Quantidade|Quantidade
T7C|07|T7C_UM|C|6|0|Unidade|Unidade
T7C|08|T7C_VALOR|N|14|2|Val Tributo|Valor do Tributo
--- ### T7D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7D|01|T7D_FILIAL|C|6|0|Filial|Filial do Sistema
T7D|02|T7D_IDLOG|C|36|0|Chave do Log|Chave Log de Processament
T7D|03|T7D_IDENT|C|36|0|Id Evento|Identificação do Evento
T7D|04|T7D_DATA|D|8|0|Data Proc|Data de Processamento
T7D|05|T7D_HORA|C|8|0|Hora Proc|Hora de Processamento
T7D|06|T7D_XMSG|M|255|0|Mensagem|Mesagem de processamento
T7D|07|T7D_SNDXML|M|255|0|XML Enviado|XML do evento enviado
--- ### T7E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7E|01|T7E_FILIAL|C|6|0|Filial|Filial do sistema
T7E|02|T7E_ID|C|6|0|ID.|Identificador do Registro
T7E|03|T7E_EVENTO|C|6|0|Eventos|Lista de Eventos
T7E|04|T7E_DESCRI|C|100|0|Descrição|Descrição do Evento
T7E|05|T7E_AUTOR|C|1|0|Autor Evento|Autor do Evento
T7E|06|T7E_TEMITE|C|1|0|Tem itens?|Evento tem itens?
--- ### T7H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7H|01|T7H_FILIAL|C|6|0|Filial|Filial do sistema
T7H|02|T7H_ID|C|36|0|ID|Identificador do Registro
T7H|03|T7H_PERIOD|D|8|0|Data da Ded.|Data da dedução
T7H|04|T7H_TIPDED|C|4|0|Tipo Ded.|Tipo de dedução
T7H|05|T7H_TIPO|C|4|0|Tipo|Tipo
T7H|06|T7H_TPDEST|C|1|0|Tp. Destinat|Tipo de Destinatário
T7H|07|T7H_CGC|C|14|0|Destinatário|Identific. do destinatári
T7H|08|T7H_VALDED|N|16|2|Valor Ded.|Valor da dedução
T7H|09|T7H_OBSERV|C|250|0|Obs/Ato Norm|Observ./Ato normativo
--- ### T7I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7I|01|T7I_FILIAL|C|6|0|Filial|Filial
T7I|02|T7I_DTINC|D|8|0|Dt Inclusão|Data Inclusão
T7I|03|T7I_USRINC|C|6|0|Usuário inc|Usuário de inclusão
T7I|04|T7I_SEQUEN|C|6|0|Sequencial|Sequencial diário
T7I|05|T7I_EVENTO|C|6|0|Evento|Evento
T7I|06|T7I_STATUS|C|1|0|Status Lote|Status do Lote
--- ### T7R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7R|01|T7R_FILIAL|C|6|0|Filial|Filial
T7R|02|T7R_ID|C|36|0|ID|ID
T7R|03|T7R_INDMOV|C|1|0|Tp. Oper.|Tipo de Operaçao
T7R|04|T7R_CHVNF|C|36|0|Chv. NF|Chave Nota Fiscal
T7R|05|T7R_ITEMNF|C|4|0|Item|Item Nota Fiscal
T7R|06|T7R_CHVREF|C|36|0|Chv. Ref.|Chv. Nf. Referência
T7R|07|T7R_ITEREF|C|4|0|Item Ref|Item NF Referência
T7R|08|T7R_ITEXML|C|4|0|Item XML.|Item XML.
T7R|09|T7R_MOVREF|C|1|0|Tp. Ope. Ref|Tipo de Operaçao Ref.
--- ### T7S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T7S|01|T7S_FILIAL|C|6|0|Filial|Filial do Sistema
T7S|02|T7S_IDPROC|C|36|0|Id Processam|Id de Processamento
T7S|03|T7S_ORIGEM|C|10|0|Origem|Origem Processsamento
T7S|04|T7S_TABELA|C|10|0|Tabela Orig.|Tabela de Origem
T7S|05|T7S_CHVNFE|C|44|0|Chave NFE|Chave NFE
T7S|06|T7S_XML|M|255|0|XML Evento|XML do Evento
T7S|07|T7S_EVENTO|C|6|0|Evento|Codigo do Evento
--- ### T80
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T80|01|T80_FILIAL|C|6|0|FILIAL|FILIAL
T80|02|T80_ID|C|6|0|Id. Func.|Id. do Funcionario
T80|03|T80_VERSAO|C|14|0|Id. Ver Reg|Id da Versao do Registro
T80|04|T80_CNPJSD|C|14|0|CNPJ Sind.|CNPJ Sindical Trabalhador
T80|05|T80_NOMEVE|C|5|0|Nome Evento|Nome do Evento
--- ### T81
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T81|01|T81_FILIAL|C|6|0|Filial|Filial
T81|02|T81_ID|C|36|0|ID.|Identificador do Registro
T81|03|T81_CODIGO|C|2|0|Código.|Código da Obrigação
T81|04|T81_CODSEC|C|4|0|Código Sec.|Código Secundário
T81|05|T81_DESCRI|C|60|0|Descrição.|Descrição Não Retenção
--- ### T82
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T82|01|T82_FILIAL|C|6|0|Filial|Filial
T82|02|T82_ID|C|36|0|ID.|Identificador do Registro
T82|03|T82_CODIGO|C|2|0|Código.|Código da Obrigação
T82|04|T82_CODSEC|C|4|0|Código Sec.|Código Secundário
T82|05|T82_DESCRI|C|60|0|Descrição.|Descrição Reg. Esp. Trib.
--- ### T83
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T83|01|T83_FILIAL|C|6|0|Filial|Filial
T83|02|T83_ID|C|36|0|ID.|Identificador do Registro
T83|03|T83_CODIGO|C|2|0|Código.|Código da Obrigação
T83|04|T83_CODSEC|C|4|0|Código.Sec.|Código Secundário
T83|05|T83_DESCRI|C|80|0|Descrição.|Descrição Tipo de Negócio
--- ### T84
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T84|01|T84_FILIAL|C|6|0|Filial|Filial
T84|02|T84_ID|C|36|0|ID.|Identificador do Registro
T84|03|T84_CODIGO|C|2|0|Código.|Código da Obrigação
T84|04|T84_CODSEC|C|4|0|Código.Sec.|Código Secundário
T84|05|T84_DESCRI|C|80|0|Descrição.|Descição
--- ### T85
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T85|01|T85_FILIAL|C|6|0|Filial|Filial
T85|02|T85_ID|C|36|0|ID.|Identificador de Registro
T85|03|T85_CODIGO|C|2|0|Código.|Código da Obrigação
T85|04|T85_CODSEC|C|4|0|Código.Sec.|Código Secundário
T85|05|T85_DESCRI|C|80|0|Descrição.|Descrição Exig. ISSQN
--- ### T86
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T86|01|T86_FILIAL|C|6|0|Filial|Filial
T86|02|T86_ID|C|6|0|ID.|Identificador Registro
T86|03|T86_CODAJU|C|6|0|Cod.Ajust.|Código Ajuste
T86|04|T86_CODPAR|C|36|0|Id.Particip.|Id. Participante
T86|05|T86_CPARTI|C|60|0|Cód.Partic.|Código do Participante
T86|06|T86_DCODPA|C|220|0|Nome.|Nome do Participante
T86|07|T86_CODMOD|C|6|0|ID.Modelo.|Cod. Identificação Modelo
T86|08|T86_DCODMO|C|220|0|Descr.Modelo|Descrição do Modelo
T86|09|T86_NUMDOC|C|9|0|Num.Docum.|Número do Documento
T86|10|T86_DTDOC|D|8|0|Dt.Emissão.|Data de Emissão
T86|11|T86_SERDOC|C|4|0|Série.Doc.|Série do documento
T86|12|T86_SUBSER|C|3|0|Sub-Série.|Sub-Série do documento
T86|13|T86_CODITE|C|36|0|Id.Item.|Id Item
T86|14|T86_ITEM|C|60|0|Cód.Item.|Código do Item
T86|15|T86_DCODIT|C|220|0|Descr.Item.|Descrição do Item
T86|16|T86_VLRAJU|N|16|2|Vlr. Ajuste.|Valor do ajuste operação
T86|17|T86_CHVELE|C|44|0|Chv.Eletr.|Chv Eletronica Documento
--- ### T87
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T87|01|T87_FILIAL|C|6|0|Filial|Filial
T87|02|T87_ID|C|36|0|ID|Identificador do Registro
T87|03|T87_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do Registro
T87|04|T87_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T87|05|T87_DTRABA|C|220|0|Nome do Trab|Nome do Trabalhador
T87|06|T87_CONVOC|C|30|0|Cod.Convoc.|Codigo Convocação
T87|07|T87_DTINIP|D|8|0|Ini. Prest.|Data Inicio Prestação
T87|08|T87_DTFIMP|D|8|0|Fim Prest.|Termino Prest. Trabalho
T87|09|T87_CODHOR|C|6|0|Cod. Horário|Codigo Horário
T87|10|T87_DCODHO|C|220|0|Desc.Horário|Descriçao do horário
T87|11|T87_DTPJOR|C|220|0|Desc.Jornada|Descrição Tipo Jornada
T87|12|T87_LOCTRB|C|1|0|Local Trab.|Local Prestação Trabalho
T87|13|T87_UF|C|6|0|UF|UF
T87|14|T87_DUF|C|220|0|Descr. UF|Descrição da UF
T87|15|T87_MUN|C|6|0|Id. Mun. End|Id. Município do Endereço
T87|16|T87_DMUN|C|220|0|Des Mun End|Descr. Município Endereço
T87|17|T87_TPLOGR|C|6|0|Id. Tp. Log.|Identif. Tipo Logradouro
T87|18|T87_DTPLOG|C|220|0|Des Tp Log|Descrição Tipo Logradouro
T87|19|T87_LOGRAD|C|220|0|Descr. Logr.|Descriçao do Logradouro
T87|20|T87_NRLOG|C|10|0|Número Log.|Número Logradouro
T87|21|T87_COMLOG|C|30|0|Comp. Log.|Complemento Logradouro
T87|22|T87_BAIRRO|C|90|0|Bairro|Bairro
T87|23|T87_CEP|C|10|0|CEP|CEP
T87|24|T87_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T87|25|T87_STATUS|C|1|0|Status Reg.|Status do Registro
T87|26|T87_VERANT|C|14|0|Ver Ant Reg|Versão anterior registro
T87|27|T87_PROTUL|C|44|0|Últ. Prot.|Prot. Última Transmissão
T87|28|T87_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penúltima Transm.
T87|29|T87_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T87|30|T87_XMLID|C|36|0|Id do XML.|Id do XML.
T87|31|T87_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T87|32|T87_LOGOPE|C|1|0|Log Operacao|Log Operacao
T87|33|T87_STASEC|C|1|0|Status Sec.|Status Secundario
T87|34|T87_DTPREV|D|8|0|Dt Prv Pagto|Data Prevista Pagamento
T87|35|T87_DTRANS|D|8|0|Dt.Transm.|Data Transmissão
T87|36|T87_HTRANS|C|8|0|Hr.Transm|Hora Transmissão
T87|37|T87_DTRECP|D|8|0|Dt.Recept|Data Receptação
T87|38|T87_HRRECP|C|8|0|Hr.Recept|Hora Receptação
--- ### T88
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T88|01|T88_FILIAL|C|6|0|Filial|Filial
T88|02|T88_ID|C|6|0|ID|Identificador do Registro
T88|03|T88_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T88|04|T88_IDEDMD|C|30|0|Ident Dem Va|Ident Dem Valor
T88|05|T88_CODCON|C|30|0|Código Conv|Código da Convocação
T88|06|T88_DCODCO|C|220|0|Desc Convoc|Descrição da Convocação
T88|07|T88_IDCODC|C|36|0|ID Cód Conv|ID Código Convovação
--- ### T89
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T89|01|T89_FILIAL|C|6|0|Filial|Filial
T89|02|T89_ID|C|36|0|ID|Identificador do registro
T89|03|T89_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versão do Registro
T89|04|T89_IDEDMD|C|30|0|Iden Dem Pgt|Iden Dem Pgt
T89|05|T89_CODCON|C|30|0|Convoc Trab|C. Conv Trab Intermitente
T89|06|T89_IDCONV|C|36|0|ID Conv Trab|ID Convocação Trab. Inter
--- ### T8D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8D|01|T8D_FILIAL|C|6|0|Filial|Filial
T8D|02|T8D_ID|C|6|0|ID|Id da tabela
T8D|03|T8D_CODIGO|C|3|0|Cod institu.|Cod instituiçao
T8D|04|T8D_DESCRI|C|220|0|Descrição|Descrição da Inst.
T8D|05|T8D_VALIDA|D|8|0|Data Valid.|Data de validade
T8D|06|T8D_CNPJ|C|14|0|cnpj|Cnpj da Inst.
--- ### T8E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8E|01|T8E_FILIAL|C|6|0|fILIAL|fILIAL
T8E|02|T8E_ID|C|36|0|Id|Id da tabela
T8E|03|T8E_VERSAO|C|14|0|Versao|Versao
T8E|04|T8E_PERREF|C|6|0|Per. Ref.|Per. Ref Ajuste
T8E|05|T8E_NRREC|C|44|0|Rec. 1210Ori|Nr. Recibo S-1210 origem.
T8E|06|T8E_SEQIRC|C|2|0|Sequencia|Sequencia
T8E|07|T8E_DTLAUD|D|8|0|Dt. Laudo|Data do Laudo
--- ### T8F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8F|01|T8F_FILIAL|C|6|0|Filial|Filial do Sistema
T8F|02|T8F_ID|C|6|0|ID|Id do registro
T8F|03|T8F_VERSAO|C|14|0|Id. Ver. Reg|Id. Ver. Reg
T8F|04|T8F_NRPROC|C|20|0|Nr. Proc|Número do processo
T8F|05|T8F_CPFTRA|C|11|0|CPF|CPF do trabalhador
T8F|06|T8F_MATRIC|C|30|0|Matricula|Matricula
T8F|07|T8F_CODCAT|C|6|0|Cod Cat|Codigo de categoria
T8F|08|T8F_DTINIC|D|8|0|Dt Inic|Data Inicío
T8F|09|T8F_TPINSC|C|1|0|Tp Insc|Tipo de inscrição
T8F|10|T8F_NRINSC|C|14|0|Nr Insc|Número de inscrição
T8F|11|T8F_DIATRA|C|2|0|Dia Trab.|Dias do mês trabalhado
T8F|12|T8F_HRSTRA|C|4|0|Horas trab|Horas trabalhada
--- ### T8G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8G|01|T8G_FILIAL|C|6|0|Filial|Filial do Sistema
T8G|02|T8G_ID|C|6|0|ID|Identificador do registro
T8G|03|T8G_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T8G|04|T8G_CRMEN|C|6|0|Cód.receita| Código de Receita
T8G|05|T8G_RENDTR|N|14|2|Vl Rend Trib|Vlr Rend Trib
T8G|06|T8G_RENT13|N|14|2|Rend Trib 13|Vlr Rend Trib 13
T8G|07|T8G_PREVOF|N|14|2|Vlr Prev Ofi|Vlr Prev Oficial
T8G|08|T8G_PROF13|N|14|2|Prev Ofi 13|Vlr Prev Oficial 13
T8G|09|T8G_VCRMEN|N|14|2|Vlr CR Men|Vlr CR Men
T8G|10|T8G_CR13ME|N|14|2|Vlr CR 13 Me|Vlr CR 13 Me
T8G|11|T8G_PAIS65|N|14|2|Parc Ise 65|Vlr Parc Isenta 65
T8G|12|T8G_PIS65D|N|14|2|Par Ise 65 D|Vlr Parc Isenta 65 Dec
T8G|13|T8G_VLDIAR|N|14|2|Vlr Diárias|Valor relativo a diárias.
T8G|14|T8G_VLAJUC|N|14|2|Vl Ajud Cust|Valor a ajuda de custo
T8G|15|T8G_VINRES|N|14|2|Ind Res Cont|vlr Ind Res Contrato
T8G|16|T8G_ABONPE|N|14|2|Vl abono Pec|vlr Abono Pec
T8G|17|T8G_VLRIMG|N|14|2|Vl Rend Mole|vlr Rend Mole Grave
T8G|18|T8G_IMG13|N|14|2|Vl Ren M13|vlr Rend Mole Grave 13
T8G|19|T8G_VLMORD|N|14|2|Vlr Aux Mora|vlr Aux Moradia
T8G|20|T8G_BOLMED|N|14|2|Vl Bolsa Med|  Vlr Bolsa Médico
T8G|21|T8G_BOLM13|N|14|2|Vl Bol Méd13|Vlr Bolsa Médico 13
T8G|22|T8G_JURMOR|N|14|2|Vl Juros Mor|vlr Juros Mora
T8G|23|T8G_ISEOUT|N|14|2|Vl redn Isen|vlr Isen Outros
T8G|24|T8G_DESCRE|C|220|0|Desc Rend.|Desc Rend não Tributario
T8G|25|T8G_SEQUEN|C|3|0|Sequencia|Sequencia
T8G|26|T8G_PERREF|C|6|0|Período|Período Refer.
--- ### T8H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8H|01|T8H_FILIAL|C|6|0|Filial|Filial do Sistema
T8H|02|T8H_ID|C|6|0|ID|Identificador do Registro
T8H|03|T8H_VERSAO|C|14|0|Id. Ver. Reg|Id.da versão do Registro
T8H|04|T8H_DTLAUD|D|8|0|Data Laudo|Data Laudo
T8H|05|T8H_PERREF|C|7|0|Per Ref Aju|Per Ref. Ajuste
T8H|06|T8H_NR1210|C|23|0|Nr Rec 1210|Nr Rec 1210 Orig
T8H|07|T8H_SEQIRC|C|3|0|Sequencia|Sequencia
--- ### T8I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8I|01|T8I_FILIAL|C|6|0|Filial|Filial
T8I|02|T8I_ID|C|6|0|ID|Identificador do Registro
T8I|03|T8I_VERSAO|C|14|0|Id.Ver.Reg.|Id da versão do registro
T8I|04|T8I_NRPROC|C|20|0|Nr. Proc|Número do Processo
T8I|05|T8I_PERAPU|C|6|0|Per. Apur.|Per. Apur. Pgto.
T8I|06|T8I_STATUS|C|1|0|Status|Status do registro
T8I|07|T8I_PROTUL|C|44|0|Protocolo|Protocolo do registro
T8I|08|T8I_PROTPN|C|44|0|protpn|Protocolo anterior
T8I|09|T8I_ATIVO|C|1|0|Ativo|Ativo
T8I|10|T8I_LOGOPE|C|1|0|log de oper.| Log de operaçao.
T8I|11|T8I_XMLID|C|36|0|xmlid|ID do XML
T8I|12|T8I_DINSIS|D|8|0|data ini sis|Data Inicio do Sistema
T8I|13|T8I_DTRAN|D|8|0|Dt. Trans.|Data de Transmissão
T8I|14|T8I_HTRANS|C|8|0|Hr. trans|Hora da transmissão.
T8I|15|T8I_DTRECP|D|8|0|Dt. Recep.|Data Recepção
T8I|16|T8I_HRRECP|C|8|0|Hr recept|Hora Recepção
T8I|17|T8I_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T8I|18|T8I_LAYOUT|C|30|0|Layout|Versão do layout
T8I|19|T8I_TAFKEY|C|100|0|Layout eSoci|Layout eSocial.
T8I|20|T8I_VERANT|C|14|0|Ver. Ant.|Versão anterior
T8I|21|T8I_GRVTOT|L|1|0|Totalizador| Gerou Totalizador ?
--- ### T8J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8J|01|T8J_FILIAL|C|6|0|Filial|Filial
T8J|02|T8J_ID|C|6|0|ID|Identificador do Registro
T8J|03|T8J_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T8J|04|T8J_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T8J|05|T8J_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
--- ### T8K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8K|01|T8K_FILIAL|C|6|0|Filial|Filial
T8K|02|T8K_ID|C|6|0|ID|Identificador do Registro
T8K|03|T8K_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T8K|04|T8K_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T8K|05|T8K_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
T8K|06|T8K_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T8K|07|T8K_CODCAT|C|3|0|Cod. Categor|Codigo Categoria
T8K|08|T8K_DESCAT|C|220|0|Desc. Categ|Descrição da categoria
--- ### T8L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8L|01|T8L_FILIAL|C|6|0|Filial|Filial
T8L|02|T8L_ID|C|6|0|ID|Identificador do Registro
T8L|03|T8L_VERSAO|C|14|0|Id. Ver. Reg|Id.da Versão do Registro
T8L|04|T8L_TPINSC|C|1|0|Tipo Inscr.|Tipo Inscriçao
T8L|05|T8L_NRINSC|C|15|0|Num. Inscr.|Numero Inscricao
T8L|06|T8L_MATRIC|C|30|0|Matricula|Matricula do Trabalhador
T8L|07|T8L_CODCAT|C|3|0|Cod. Categor|Codigo Categoria
T8L|08|T8L_IND13|C|1|0|Ind 13°|Indicativo de 13°
T8L|09|T8L_TPPIS|C|2|0|Tp. Valor|Tipo de Valor
T8L|10|T8L_VLRPIS|N|15|2|Vl PIS/PASEP|Vlr. PIS/PASEP
--- ### T8M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8M|01|T8M_FILIAL|C|6|0|Filial|Filial do Sistema
T8M|02|T8M_USUARI|C|6|0|Usuário|Usuário do sistema
T8M|03|T8M_DIAINI|C|2|0|Dia Inicio|Dia inicial trans/consult
T8M|04|T8M_DIAFIM|C|2|0|Dia Fim|Dia final trans/consult
T8M|05|T8M_RECORR|C|1|0|Recorrência|Recorrência de execução
T8M|06|T8M_CODSCH|C|6|0|Cod. Sched|Cod. Schedule
T8M|07|T8M_PEREXE|C|1|0|Perido Exec.|Período de Execuçao
--- ### T8N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8N|01|T8N_FILIAL|C|6|0|Filial|Filial
T8N|02|T8N_ID|C|36|0|Id|Id da tabela
T8N|03|T8N_VERSAO|C|14|0|Versão|Versão do regsitro
T8N|04|T8N_ATIVO|C|1|0|Ativo|Ativo
T8N|05|T8N_LAYOUT|C|30|0|Layout|Layout eSocial
T8N|06|T8N_GRVTOT|L|1|0|gravou tot|agravou totalizador
T8N|07|T8N_DTRECP|D|8|0|Dt. Recept|Data de receptaçao
T8N|08|T8N_HRRECP|C|8|0|Hr. Recept|Hora da receptaçao.
T8N|09|T8N_LOGOPE|C|1|0|Log de opera|Log de operaçao
T8N|10|T8N_TAFKEY|C|100|0|Tafkey|Tafkey do registro
T8N|11|T8N_NRPROC|C|20|0|Nr. Proc|Nr. Processo
T8N|12|T8N_CPF|C|11|0|CPF|CPF do trabalhador
T8N|13|T8N_XMLGRV|M|10|0|Xml|Grava xml.
T8N|14|T8N_VIEW|M|10|0|View json|Json para view
T8N|15|T8N_NOME|C|70|0|Nome|Nome do trabalhador
T8N|16|T8N_PERAPU|C|6|0|Periodo|Periodo
T8N|17|T8N_PROTUL|C|23|0|Nr. Recibo|Numero do recibo
--- ### T8O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8O|01|T8O_FILIAL|C|6|0|Filial|Filial da tabela
T8O|02|T8O_ID|C|36|0|Id da tabela|Id da tabela
T8O|03|T8O_VERSAO|C|14|0|Versao do re|Versao do registro
T8O|04|T8O_SEQUEN|C|2|0|Campo de seq|Campo de sequencia
T8O|05|T8O_MATCAT|M|10|0|Json view|Json para view matcat
--- ### T8P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8P|01|T8P_FILIAL|C|6|0|FILIAL|Filial do registro
T8P|02|T8P_ID|C|36|0|Id da tab.|Id da tabela
T8P|03|T8P_VERSAO|C|14|0|Versão reg.|versão do registro
T8P|04|T8P_CHAVE|C|2|0|Campo relaci|Campo relacional
T8P|05|T8P_SEQUEN|C|7|0|Sequencial|Campo sequencial
T8P|06|T8P_STABPA|M|10|0|Estab.|Estabelecimento
--- ### T8R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T8R|01|T8R_FILIAL|C|6|0|Filial|Filial
T8R|02|T8R_ID|C|36|0|ID|Identificador do registro
T8R|03|T8R_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T8R|04|T8R_PERAPU|C|6|0|Per. Apur.|Período Apuração
T8R|05|T8R_CPF|C|11|0|CPF|CPF do Trabalhador
T8R|06|T8R_NOME|C|70|0|Nome|Nome do Trabalhador
T8R|07|T8R_EVENTO|C|6|0|Cód Evento|Código do Evento
T8R|08|T8R_CODREC|C|30|0|Cod. Receita|Código de Receita
T8R|09|T8R_SEQUEN|C|3|0|Sequencia|Campo Sequencial
T8R|10|T8R_VLRTRI|N|15|2|Vlr Rend Tri|Valor Rendimento Tribut.
T8R|11|T8R_VRTR13|N|15|2|Vlr Rd Tr 13|Valor Rend do 13º Salário
T8R|12|T8R_VLRPRE|N|15|2|Vlr Previden|Valor Relat. Previdência
T8R|13|T8R_VPRE13|N|15|2|Vlr Prev 13º|Valor Relat. Previd. 13º
T8R|14|T8R_VLIRRF|N|15|2|Vlr IRRF|Valor IRRF Mensal e Féria
T8R|15|T8R_IRRF13|N|15|2|Vlr IRRF 13|Valor IRRF 13º salário
T8R|16|T8R_VLRISE|N|15|2|Vlr Par Isen|Valor Parcela Isenta Prov
T8R|17|T8R_VLRI13|N|15|2|Vlr Ise 13º|Valor Parcela Isenta 13º
T8R|18|T8R_VLRDIA|N|15|2|Vlr Diarias|Valor Relativo a Diárias
T8R|19|T8R_VLRAJU|N|15|2|Vlr Ajud Dia|Valor de Ajuda Diárias
T8R|20|T8R_VLRRSC|N|15|2|Vlr Resc Con|Valor Rescisão Contrato
T8R|21|T8R_VLRABN|N|15|2|Vlr Abono|Valor Relativo ao Abono
T8R|22|T8R_VLRMLG|N|15|2|Vlr Mol Grve|Vlr Molestia Grave
T8R|23|T8R_VMLG13|N|15|2|Vlr Mol 13º|Valor Molestia Grave 13º
T8R|24|T8R_VLRAXM|N|15|2|Vlr Aux Mora|Valor Auxilio Moradia
T8R|25|T8R_VLBMED|N|15|2|Vlr Bols Med|Valor Bolsa Medico
T8R|26|T8R_BMED13|N|15|2|Vlr B Med 13|Vlr Bolsa Medica 13º
T8R|27|T8R_VLRMOR|N|15|2|Vlr Juros|Vlr Juros Mora
T8R|28|T8R_VLRISO|N|15|2|Vlr Isen Out|Valor Isentos Outros
T8R|29|T8R_TPREND|C|50|0|Tipo de Rend|Tipo de Rendimento
T8R|30|T8R_CPFDEP|C|11|0|CPF Dep.|CPF Dependente
T8R|31|T8R_VLRDED|N|15|2|Vlr Dedução|Vlr Dedução Dependente
T8R|32|T8R_TPRPAL|C|110|0|Tp Rend Pen|Tp Rend. Pensão Aliment.
T8R|33|T8R_CPFDPA|C|11|0|CPF Dep Pen|CPF Dep Pens Alimenticia
T8R|34|T8R_VLRPAL|N|15|2|Vlr Ded PA|Valor Ded. da Pensão Alim
T8R|35|T8R_TPPREV|C|60|0|Tipo Previd.|Tipo de Previdencia
T8R|36|T8R_CNPJPC|C|14|0|CNPJ Previd.|CNPJ Previdência Complem.
T8R|37|T8R_VLDEPC|N|15|2|Vlr Ded Prev|Vlr Dedud Previdencia Com
T8R|38|T8R_VLPC13|N|15|2|Vlr Prev Com|Vlr Ded Prev Complem 13°
T8R|39|T8R_VLPCSP|N|15|2|V PC Serv Pu|Vlr Prv Compl Serv Public
T8R|40|T8R_PCVP13|N|15|2|V PC S P 13|Vlr Prv Compl Serv Public
T8R|41|T8R_TPPROC|C|30|0|Tipo Process|Tipo de Processo
T8R|42|T8R_NRPROC|C|21|0|Num Processo|Número do Processo
T8R|43|T8R_CODSUP|C|14|0|Cód Suspensã|Código de Suspensão
T8R|44|T8R_INDAPU|C|30|0|Ind. Apuraçã|Indica Apuração
T8R|45|T8R_VLRRTC|N|15|2|Vlr Retenção|Vlr Retenção de Processo
T8R|46|T8R_DEPJUD|N|15|2|Dep Judicial|Vlr Deposito Judicial Pro
T8R|47|T8R_CANOCA|N|15|2|Comp Ano Cal|Vlr Compensação Ano Calen
T8R|48|T8R_CANOAN|N|15|2|Comp Ano Ant|Vlr Compensação Ano Ant
T8R|49|T8R_RENDSU|N|15|2|Rend. Susp|Vlr Rend. Suspenso
T8R|50|T8R_INDDED|C|80|0|Tp. Dedução|Tipo de Dedução
T8R|51|T8R_DEDSUS|N|15|2|Vlr Ded Exig|Vlr de Ded. IR Exibilidad
T8R|52|T8R_CNPJEC|C|14|0|CNPJ Prev Co|CNPJ Ent. Prev. Complemen
T8R|53|T8R_VLCONT|N|15|2|Vlr Contribu|Vlr Contrib. Ente Pub Pre
T8R|54|T8R_CPFSUS|C|11|0|CPF Ben Susp|CPF Beneficiario Susp
T8R|55|T8R_DEPSUS|N|15|2|Vlr Ben Susp|Valor Ded Benf Susp
T8R|56|T8R_CNPJOP|C|14|0|CNPJ Op.Plan|CNPJ Op. Plano de Saúde
T8R|57|T8R_REGANS|C|6|0|Registro ANS|Registro ANS
T8R|58|T8R_VLRPLS|N|15|2|Vlr Plan Sau|Vlr Relativo Plano de Saú
T8R|59|T8R_CPFDPS|C|11|0|CPF Dep Pl S|CPF Dep Plano Saude
T8R|60|T8R_VLRDPS|N|15|2|Vlr Dep PS|Vlr Dep Plano Saude
T8R|61|T8R_ORIREE|C|110|0|Origem Reemb|Origem Reembolso PS
T8R|62|T8R_CNPJPS|C|14|0|CNPJ Oper PS|CNPJ Oper. Plano Saúde
T8R|63|T8R_ANSRRE|C|6|0|Reg ANS Reem|Registro ANS Reembolso
T8R|64|T8R_INSCRE|C|10|0|Tp. Insc|Tipo Inscrição
T8R|65|T8R_NRPSRE|C|14|0|Nr Inscriçao|Numero de Inscriçao
T8R|66|T8R_VLREEM|N|15|2|Vlr Reemb|Vlalor Reembolso
T8R|67|T8R_VLRANT|N|15|2|Vlr Reem Ant|Vlr Reembolso Anterior
T8R|68|T8R_CPFRED|C|11|0|CPF Reem Dep|CPF Reembolso Dependente
T8R|69|T8R_DINSCR|C|10|0|Det Tp Insc|Det Tipo de Inscrição
T8R|70|T8R_DNRPSR|C|14|0|Det Nr Inscr|Det Numero de Inscriçao
T8R|71|T8R_DVLRRE|N|15|2|Det Vlr Reem|Det Valor Reembolso
T8R|72|T8R_DVLRAN|N|15|2|Det Vlr Reem|Det Vlr Reembolso Anterio
T8R|73|T8R_FORABA|C|6|0|Controle Aba|Controle Aba
T8R|74|T8R_ABAFOL|C|3|0|Aba Folha|Aba Folha
T8R|75|T8R_PERREF|C|6|0|Per Apur Ref|Periodo Apuraçao Referenc
T8R|76|T8R_ORIGEM|C|1|0|Origem|Etapa de Origem
T8R|77|T8R_RELACO|C|254|0|Relacao|Chave de Relacionamento
--- ### T90
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T90|01|T90_FILIAL|C|6|0|Filial|Filial do Sistema
T90|02|T90_ID|C|6|0|ID|Identificador de Registro
T90|03|T90_VERSAO|C|14|0|Id. Ver. Reg|Id da Versao do Registro
T90|04|T90_NOMEVE|C|5|0|Nome Evento|Nome do Evento
T90|05|T90_CODOBS|C|6|0|Cod.Observac|Codigo Sequenc Observacao
T90|06|T90_OBSERV|M|10|0|Observação|Observação Contrato Trab.
--- ### T91
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T91|01|T91_FILIAL|C|6|0|Filial|Filial
T91|02|T91_ID|C|6|0|Id. Func.|Id. do Funcionario
T91|03|T91_VERSAO|C|14|0|Id. Ver Reg|Id da Versao do Registro
T91|04|T91_CODOBS|C|6|0|Cod.Observac|Codigo Sequenc Observacao
T91|05|T91_OBSERV|M|10|0|Observacao|Observacao Contrato Trab.
--- ### T92
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T92|01|T92_FILIAL|C|6|0|Filial|Filial
T92|02|T92_ID|C|6|0|ID|Identificador do Registro
T92|03|T92_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T92|04|T92_TRABAL|C|6|0|Id.Trab.|Id. do Trabalhador
T92|05|T92_DTRABA|C|220|0|Nome Trab.|Nome do Trabalhador
T92|06|T92_DTERAV|D|8|0|Dt. Término|Dt. Término Trab. Avulso
T92|07|T92_MOTDES|C|6|0|Mot. Término|Motivo Término
T92|08|T92_DMOTDE|C|220|0|Descr Motivo|Descr Motivo Desligamento
T92|09|T92_VERANT|C|14|0|Id. Ver. Ant|Id versão anterior reg.
T92|10|T92_STATUS|C|1|0|Status Reg.|Status do registro
T92|11|T92_PROTUL|C|44|0|Ult.Prot.Tr.|Prot. Última transmissão
T92|12|T92_PROTPN|C|44|0|Pnlt.Prot.Tr|Prot. Penúltima transm.
T92|13|T92_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T92|14|T92_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T92|15|T92_DTQUA|D|8|0|Dt Fim Quar|Data Final da Quarentena
T92|16|T92_INDMVI|C|1|0|Ind.Mult.Vin|Indic.Mult.Vinculos
T92|17|T92_STASEC|C|1|0|Status Sec.|Status Secundario
T92|18|T92_XMLID|C|36|0|Id do XML|Id do XML.
T92|19|T92_LOGOPE|C|1|0|Log Operacao|Log Operacao
T92|20|T92_DINSIS|D|8|0|Dt Inc. Sist|Data Inclusao Sistemica
T92|21|T92_GRVTOT|L|1|0|Totalizador| Gerou Totalizador ?
T92|22|T92_PENALI|C|1|0|Pensao Alime|Pensão Alimenticia
T92|23|T92_PERALI|N|6|2|Perc. Alimen|Perc. Alimentado
T92|24|T92_VLPALI|N|15|2|Vlr Pensão A|Valor Pensão Alimentícia
T92|25|T92_CPFV|C|11|0|CPF|CPF do Trabalhador
T92|26|T92_MATV|C|30|0|Matrícula|Matrícula do Trabalhador
T92|27|T92_NISV|C|11|0|NIS|NIS do Trabalhador
T92|28|T92_NEWCPF|C|11|0|Novo CPF|Novo CPF do TSVE
T92|29|T92_NRPROC|C|20|0|Núm. Process|Número do Processo
T92|30|T92_DTRANS|D|8|0|Dt. Transm|Data Transmissao
T92|31|T92_TPGUIA|C|1|0|Tipo de Guia|Indicativo Tipo de Guia
T92|32|T92_HTRANS|C|8|0|Hr. Transm|Hora Transmissao
T92|33|T92_DTRECP|D|8|0|Dt. Recept|Data Receptacao
T92|34|T92_HRRECP|C|8|0|Hr. Recept|Hora Receptacao
T92|35|T92_INDREM|C|1|0|Ind. Remuner|Ind. remuneração
T92|36|T92_LAYOUT|C|30|0|Ver. Layout|Versão do Layout
T92|37|T92_DTFREM|D|8|0|Dt. Fim Remu|Data Fim remuneração
--- ### T93
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T93|01|T93_FILIAL|C|6|0|Filial|Filial
T93|02|T93_EVENTO|C|6|0|Cod. Evento|Codigo do Evento
T93|03|T93_DESEVE|C|220|0|Desc. Evento|Descrição do Evento
T93|04|T93_ATIVO|C|1|0|Ativo ?|Controle de Tag Ativo ?
T93|05|T93_PADRAO|C|1|0|Comp. Padrão|Comportamento Padrão Tags
--- ### T94
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T94|01|T94_FILIAL|C|6|0|Filial|Filial
T94|02|T94_EVENTO|C|6|0|Evento|Evento E-Social
T94|03|T94_NODE|C|170|0|Caminho / Nó|Caminho completo da Tag
T94|04|T94_PROPRI|C|40|0|Proprietário|Proprietário da Tag
T94|05|T94_EXCLUI|C|1|0|Ativo ?|TAG com Controle Ativo
--- ### T95
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T95|01|T95_FILIAL|C|6|0|Filial|Filial
T95|02|T95_ID|C|36|0|ID|Identificador do registro
T95|03|T95_VERSAO|C|14|0|Id Ver Reg|Id da versão do Registro
T95|04|T95_PERAPU|C|6|0|Per Apuração|Período da Apuração
T95|05|T95_IDESTA|C|6|0|Id Estab|Id do estabelecimento
T95|06|T95_DESTAB|C|220|0|Desc Estab|Descrição do Estab.
T95|07|T95_TPNUOB|C|16|0|Insc Obra|Tipo e Num Insc. da Obra
T95|08|T95_DOBRA|C|30|0|Desc Obra|Descrição da Obra
T95|09|T95_IDOBRA|C|36|0|Id Obra|Id da Obra
T95|10|T95_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T95|11|T95_NRINSC|C|14|0|Nr Insc Est|Núm. Inscrição do Contrib
T95|12|T95_INDOBR|C|1|0|Ind Obra|Indicativo de Prest. Obra
T95|13|T95_CODPAR|C|60|0|Cód Part|Código do Participante
T95|14|T95_DPARTI|C|220|0|Desc Part|Descrição do Participante
T95|15|T95_IDPART|C|36|0|Id Particip|Id do participante
T95|16|T95_CNPJPR|C|14|0|CNPJ Prest|CNPJ do prestador serviço
T95|17|T95_VLRBRU|N|14|2|Vlr Bruto NF|Valor Bruto da NF
T95|18|T95_VLRBRE|N|14|2|Vlr Bc Ret|Valor BC da Ret. Contrib.
T95|19|T95_VLRPRI|N|14|2|Vlr NF Contr|Valor Ret NF Contratante
T95|20|T95_VLRADI|N|14|2|Vlr Adic NF|Valor Adicional da NF
T95|21|T95_VLRNPR|N|14|2|Vlr Ret Prin|Valor de Ret. Principal
T95|22|T95_VLRNAD|N|14|2|Vlr Ad N Con|Valor Ret Não Contratante
T95|23|T95_INDCPR|C|1|0|Ind CPRB|Indicativo de Prest. CPRB
T95|24|T95_VERANT|C|14|0|Ver Ant Reg|Versão Anterior Registro
T95|25|T95_STATUS|C|1|0|Status Reg|Status do Registro
T95|26|T95_PROTUL|C|52|0|Recibo|Recibo da Transmissão
T95|27|T95_PROTPN|C|52|0|Recibo Ant|Recibo Trans Anterior
T95|28|T95_EVENTO|C|1|0|Id Evento|Identificação do Evento
T95|29|T95_ATIVO|C|1|0|Reg Ativo|Registro Ativo
T95|30|T95_PROCID|C|6|0|Proc ID|ID de Processos.
T95|31|T95_XMLID|C|36|0|Id do XML.|Id do XML.
--- ### T96
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T96|01|T96_FILIAL|C|6|0|Filial|Filial
T96|02|T96_ID|C|36|0|ID|Identificador do Registro
T96|03|T96_VERSAO|C|14|0|Id Ver Reg|Id da versão do registro
T96|04|T96_CHVNF|C|36|0|Cód NF|Código da Nota Fiscal
T96|05|T96_NUMFAT|C|15|0|Núm Fat|Número da Fatura
T96|06|T96_IDFAT|C|36|0|Id Fatura|Id da Fatura
T96|07|T96_SERIE|C|5|0|Série|Série
T96|08|T96_NUMDOC|C|15|0|Núm NF|Número do Nota Fiscal
T96|09|T96_DTEMIS|D|8|0|Dt. Emissão|Data de Emissão
T96|10|T96_VLBRUT|N|14|2|Vlr Bruto|Valor Bruto
T96|11|T96_OBSERV|C|250|0|Observação|Observação
--- ### T97
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T97|01|T97_FILIAL|C|6|0|Filial|Filial
T97|02|T97_ID|C|36|0|ID|Identificador do Registro
T97|03|T97_VERSAO|C|14|0|Id Ver Reg|Id da versão do registro
T97|04|T97_SERIE|C|5|0|Série|Série
T97|05|T97_NUMDOC|C|15|0|Núm Documen|Número do Documento
T97|06|T97_NUMFAT|C|15|0|Núm Fat|Número da Fatura
T97|07|T97_TPSERV|C|6|0|Tipo Serviço|Tipo de serviço
T97|08|T97_CODSER|C|9|0|Cód Tp Serv|Código do tipo de Serviço
T97|09|T97_DTPSER|C|250|0|Desc Tp Serv|Desc. do tipo de serviço
T97|10|T97_VLRBAS|N|14|2|Vlr Bc Ret|Valor Bc Retenção
T97|11|T97_VLRRET|N|14|2|Vlr Retenção|Valor da Retenção
T97|12|T97_VLRRSU|N|14|2|Vlr Ret Sub|Valor Ret Subcontratados
T97|13|T97_VLRNPR|N|14|2|Vlr Ret Prin|Valor de Retenção Princip
T97|14|T97_VLRS15|N|14|2|Vlr Serv 15|Valor Serv 15 anos Cont
T97|15|T97_VLRS20|N|14|2|Vlr Serv 20|Valor Serv 20 anos Cont
T97|16|T97_VLRS25|N|14|2|Vlr Serv 25|Valor Serv 25 anos Cont
T97|17|T97_VLRADI|N|14|2|Vlr Adic|Valor Adicional
T97|18|T97_VLRNRE|N|14|2|Vlr Ad N Con|Valor Ret Não Contratante
--- ### T98
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T98|01|T98_FILIAL|C|6|0|Filial|Filial
T98|02|T98_ID|C|36|0|ID|Identificador do registro
T98|03|T98_VERSAO|C|14|0|Id Ver Reg|Id da versão do Registro
T98|04|T98_IDPROC|C|6|0|Id Processo|Id do Processo Ret
T98|05|T98_TPPROC|C|1|0|Tp Processo|Tipo de processo
T98|06|T98_NUMPRO|C|21|0|Núm Processo|Número do Processo
T98|07|T98_CODSUS|C|14|0|Cód Susp|Código de Suspensão
T98|08|T98_IDSUSP|C|34|0|Chave Susp|Chave do Cod. Suspensão
T98|09|T98_VLRPRI|N|14|2|Vlr Princip|Valor Principal
--- ### T99
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T99|01|T99_FILIAL|C|6|0|Filial|Filial
T99|02|T99_ID|C|36|0|ID|Identificador do registro
T99|03|T99_VERSAO|C|14|0|Id Ver Reg|Id da versão do Registro
T99|04|T99_IDPROC|C|6|0|Id Processo|Id do Processo Ret
T99|05|T99_TPPROC|C|1|0|Tp Processo|Tipo de processo
T99|06|T99_NUMPRO|C|21|0|Núm Processo|Número do Processo
T99|07|T99_CODSUS|C|14|0|Cód Susp|Código de Suspensão
T99|08|T99_IDSUSP|C|34|0|Chave Susp|Chave do Cod. Suspensão
T99|09|T99_VLRADI|N|14|2|Vlr Adic|Valor Adicional
--- ### T9A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9A|01|T9A_FILIAL|C|6|0|Filial|Filial
T9A|02|T9A_ID|C|36|0|ID|Identificador do Registro
T9A|03|T9A_CODIGO|C|4|0|Código|Código Forma Tributacao
T9A|04|T9A_DESCRI|C|220|0|Descrição|Descrição forma de tribut
T9A|05|T9A_DTINI|D|8|0|Dt. Ini. Val|Data Inicial da Validade
T9A|06|T9A_DTFIN|D|8|0|Dt. Fin Vld|Data final da validade
T9A|07|T9A_CREINF|C|2|0|Código REINF|Código REINF
--- ### T9B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9B|01|T9B_FILIAL|C|6|0|Filial|Filial
T9B|02|T9B_ID|C|36|0|ID|identificador Registro
T9B|03|T9B_CODIGO|C|6|0|Cod Tp Arq|Codigo tipos de arq Reinf
T9B|04|T9B_DESCRI|C|220|0|Descrição|Descrição Evento Reinf
T9B|05|T9B_VALIDA|D|8|0|Data Vigenc.|Data Vigenc. Tp Arq Reinf
--- ### T9C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9C|01|T9C_FILIAL|C|6|0|Filial|Filial
T9C|02|T9C_ID|C|36|0|Id Registro|Identificador do Registro
T9C|03|T9C_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T9C|04|T9C_NRINSC|C|14|0|Nr Inscrição|Número de Inscrição
T9C|05|T9C_INDOBR|C|1|0|Ind Obra|Ind. Prest. Serv em Obras
T9C|06|T9C_DSCOBR|C|30|0|Desc.Obra|Descricao da Obra
T9C|07|T9C_INDTER|C|1|0|Ind Terceiro|Ind.Obra Pertenc Terceiro
T9C|08|T9C_CPRB|C|1|0|Contrib CPRB|Contrib CPRB
T9C|09|T9C_STAMP|C|23|0|Stamp|Controle e integraçao
T9C|10|T9C_CODART|C|15|0|Código ART|Código ART Serv.Cons.Civi
--- ### T9D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9D|01|T9D_FILIAL|C|6|0|Filial|Filial
T9D|02|T9D_ID|C|36|0|ID|Identificador do Registro
T9D|03|T9D_VERSAO|C|14|0|Id Ver Reg|Id Versao do Registro
T9D|04|T9D_TPEVEN|C|6|0|Tp Evento|Tipo do Evento
T9D|05|T9D_DTPEVE|C|220|0|Des. Evento|Descrição do Envento
T9D|06|T9D_IDTPEV|C|36|0|ID Tipo Even|Identificador Tipo Evento
T9D|07|T9D_NRRECI|C|52|0|Nr. Recibo|Número do Recibo
T9D|08|T9D_PERAPU|C|6|0|Per.Apuracao|Período de Apuração
T9D|09|T9D_PERAPR|D|8|0|Per Apuracao|Período da apuração
T9D|10|T9D_VERANT|C|14|0|Ver Ant Reg|Versão Anterior Registro
T9D|11|T9D_STATUS|C|1|0|Status Reg.|Status do Registro
T9D|12|T9D_PROTUL|C|52|0|Util. Prot.|Ultima Transmissão
T9D|13|T9D_PROTPN|C|52|0|Pnlt. Prot.|Prot. penúltima transmiss
T9D|14|T9D_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T9D|15|T9D_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo ?
T9D|16|T9D_REGREF|N|12|0|Registro Ref|Registro Referência
T9D|17|T9D_PROCID|C|6|0|Proc ID|ID de Processos.
T9D|18|T9D_XMLID|C|36|0|Id do XML.|Id do XML.
--- ### T9E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9E|01|T9E_FILIAL|C|6|0|Filial|Filial
T9E|02|T9E_ID|C|36|0|ID|Identificador do Registro
T9E|03|T9E_IDPART|C|36|0|Participante|ID do Participante
T9E|04|T9E_NUMFAT|C|15|0|Num Fat/Rec|Numero da Fatura/Recibo
T9E|05|T9E_NUMPRO|C|6|0|Id. Processo|Id. do Processo
T9E|06|T9E_DESPRO|C|220|0|Desc Process|Descrição do Processo
T9E|07|T9E_TPPROC|C|1|0|Tip Processo|Tipo de Processo
T9E|08|T9E_CODSUS|C|14|0|Suspensão|Código da Suspensão
T9E|09|T9E_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
T9E|10|T9E_CODTRI|C|6|0|Cod Tributo|Código Tributo
T9E|11|T9E_DESTRI|C|220|0|Desc Tributo|Descricao do Tributo
T9E|12|T9E_VALSUS|N|16|2|Vl Suspensão|Valor Rentenção Suspensa
T9E|13|T9E_CNATRE|C|6|0|Cod Nat Ren|Cod Natureza de Rendiment
T9E|14|T9E_NATREN|C|5|0|Cod Nat Ren|Cod Natureza de Rendiment
T9E|15|T9E_DNATRE|C|254|0|Desc Nat Ren|Desc Natureza Rendimento
T9E|16|T9E_BSSUSP|N|14|2|Base Susp|Valor Base Suspensa
T9E|17|T9E_VLRANO|N|14|2|Comp.Jud.Ano|Compensação Judic Ano Cal
T9E|18|T9E_VLRANA|N|14|2|Comp.Jud.Ant|Compensação Judic Ano Ant
--- ### T9F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9F|01|T9F_FILIAL|C|6|0|Filial|Filial
T9F|02|T9F_ID|C|36|0|ID|Identificador Registro
T9F|03|T9F_DTAPUR|D|8|0|Dt Espetacul|Dt espetáculo desportivo
T9F|04|T9F_VALTOT|N|14|2|Val Rec Brut|Valor da Receita Bruta
T9F|05|T9F_VALPRE|N|14|2|Val Con Prev|Valor cont previdenciaria
T9F|06|T9F_VALCLU|N|14|2|Val Rec Club|Val Receita Cubes
T9F|07|T9F_VALRET|N|14|2|Valor Retido|Val Ret Amortização
T9F|08|T9F_PROCID|C|6|0|Proc ID|ID de Processos.
--- ### T9G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9G|01|T9G_FILIAL|C|6|0|Filial|Filial do sistema
T9G|02|T9G_ID|C|36|0|ID|Idenficador do registro
T9G|03|T9G_DTAPUR|D|8|0|Dt Espetacul|Dt espetáculo desportivo
T9G|04|T9G_NUMBOL|C|7|0|Nro Boletim|Número do boletim
T9G|05|T9G_TPCOMP|C|1|0|Tp Compet|Tipo de Competição
T9G|06|T9G_CATEVE|C|1|0|Cat. Evento|Categoria do Evento
T9G|07|T9G_MODDES|C|100|0|Modalidade|Descrição da modalidade
T9G|08|T9G_NOMCOM|C|100|0|Nome Compet|Nome da competição
T9G|09|T9G_CNPJMA|C|14|0|CNPJ Mandant|CNPJ Clube Mandante
T9G|10|T9G_CNPJVI|C|14|0|CNPJ Visit|CNPJ Visitante
T9G|11|T9G_NOMVIS|C|100|0|Nome visit|Nome do clube visitante
T9G|12|T9G_PRADES|C|100|0|Praça Desp.|Praça desportiva
T9G|13|T9G_UF|C|6|0|ID UF|Cod. Id. UF
T9G|14|T9G_DUF|C|220|0|Desc UF|Descrição UF
T9G|15|T9G_CODMUN|C|6|0|ID Município|Cod. Ident.Municipio
T9G|16|T9G_DCODMU|C|220|0|Des Mun|Descrição Municipio
T9G|17|T9G_PAGANT|N|6|0|Qtd pagantes|Quantidade de pagantes
T9G|18|T9G_NPAGAN|N|6|0|Qtd não pag|Quantidades não pagantes
--- ### T9H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9H|01|T9H_FILIAL|C|6|0|Filial|Filial
T9H|02|T9H_ID|C|36|0|ID|ID
T9H|03|T9H_DTAPUR|D|8|0|Dt Apuração|Data da Apuração
T9H|04|T9H_NUMBOL|C|7|0|Num Boletim|Numero do Boletim
T9H|05|T9H_TPCOMP|C|1|0|Tp Compet|Tipo de Competição
T9H|06|T9H_CATEVE|C|1|0|Cat Evento|Categoria do Evento
T9H|07|T9H_CODSEQ|C|36|0|Código Seq|Código Sequencial
T9H|08|T9H_TPINGR|C|1|0|Tp Ingresso|Tipo de Ingresso
T9H|09|T9H_INGRES|C|220|0|Des Ingresso|Descrição do Ingresso
T9H|10|T9H_QTDVDA|N|6|0|Qtd a Venda|Qtd Ingressos a Venda
T9H|11|T9H_QTDVDO|N|6|0|Qtd Vendidos|Qtd de Ingressos Vendidos
T9H|12|T9H_QTDDEV|N|6|0|Qt Devolvido|Qtd Ingressos Devolvidos
T9H|13|T9H_PREIND|N|14|2|Preço Indiv|Preço Individual
T9H|14|T9H_VLRTOT|N|14|2|Vlr Total|Valor total arrecadado
--- ### T9I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9I|01|T9I_FILIAL|C|6|0|Filial|Filial
T9I|02|T9I_ID|C|36|0|ID|ID
T9I|03|T9I_DTAPUR|D|8|0|Dt Apuração|Data de Apuração
T9I|04|T9I_NUMBOL|C|7|0|Num Boletim|Numero do Boletim
T9I|05|T9I_TPCOMP|C|1|0|Tp Compet|Tipo de Competição
T9I|06|T9I_CATEVE|C|1|0|Cat Evento|Categoria do Evento
T9I|07|T9I_CODSEQ|C|36|0|Código Seq.|Código sequenciador
T9I|08|T9I_TPREC|C|1|0|Tp Receita|Tipo da receita
T9I|09|T9I_VALREC|N|14|2|Vl Rec Aufer|Valor da receita auferida
T9I|10|T9I_DESREC|C|20|0|Desc Receita|Descrição da receita
--- ### T9J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9J|01|T9J_FILIAL|C|6|0|Filial|Filial
T9J|02|T9J_ID|C|36|0|ID|Identificador do registro
T9J|03|T9J_DTAPUR|D|8|0|Dt Apuração|Data da apuração
T9J|04|T9J_IDPROC|C|6|0|ID Processo|ID Processo
T9J|05|T9J_DNRPRO|C|21|0|Num. Proc|Numero do Processo
T9J|06|T9J_CODSUS|C|14|0|Cod Susp|Cod Indic Suspensao
T9J|07|T9J_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
T9J|08|T9J_VLRSUS|N|14|2|Vl Suspensão|Vl exigibilidade suspensa
--- ### T9K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9K|01|T9K_FILIAL|C|6|0|Filial|Filial
T9K|02|T9K_ID|C|36|0|ID|Identificador do Registro
T9K|03|T9K_VERSAO|C|14|0|Id Ver Reg|Id da Versão do Registro
T9K|04|T9K_PERAPU|C|6|0|Per Apuração|Período de Apuração
T9K|05|T9K_TPINSC|C|1|0|Tp Inscrição|Tipo de Inscrição
T9K|06|T9K_NRINSC|C|14|0|Nr Insc Est|Num. Inscrição do Contrib
T9K|07|T9K_VERANT|C|14|0|Id Ver Ant|Id Versão Anterior Reg
T9K|08|T9K_STATUS|C|1|0|Status|Status do Registro
T9K|09|T9K_PROTUL|C|52|0|Recibo|Recibo da Transmissão
T9K|10|T9K_PROTPN|C|52|0|Recibo Ant|Recibo Trans Anterior
T9K|11|T9K_EVENTO|C|1|0|Id Evento|Identificação do Evento
T9K|12|T9K_ATIVO|C|1|0|Reg Ativo|Registro Ativo
T9K|13|T9K_PROCID|C|6|0|Proc ID|ID de Processos
T9K|14|T9K_XMLID|C|36|0|Id do XML.|Id do XML.
T9K|15|T9K_IDESTA|C|6|0|Id Estab|Id do Estabelecimento
T9K|16|T9K_DESTAB|C|220|0|Desc Estab|Descrição do Estab.
--- ### T9L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9L|01|T9L_FILIAL|C|6|0|Filial|Filial
T9L|02|T9L_ID|C|36|0|ID|Identificador do Registro
T9L|03|T9L_VERSAO|C|14|0|Id Ver Reg|Id da Versão do Registro
T9L|04|T9L_IDCODP|C|36|0|Id Cód Part|Id Cód Participante
T9L|05|T9L_CODFAT|C|10|0|Cód Fatura|Código da Fatura
T9L|06|T9L_PREFIX|C|5|0|Prefixo|Prefixo da Fatura
T9L|07|T9L_IDCODF|C|36|0|ID Cód Fat|Identificador Cód Fatura
T9L|08|T9L_CHVNF|C|36|0|Cód Docto|Código Documento Fiscal
T9L|09|T9L_SERIE|C|20|0|Série|Série Documento Fiscal
T9L|10|T9L_SUBSER|C|20|0|Sub-Série|Sub-Série Docto Fiscal
T9L|11|T9L_NUMDOC|C|60|0|Núm Doc Fisc|Número Documento Fiscal
T9L|12|T9L_TPREPA|C|1|0|Tipo Repasse|Tipo de Repasse
T9L|13|T9L_DESCRE|C|20|0|Desc Recurso|Descrição Recurso Rep
T9L|14|T9L_VLBRUT|N|16|2|Valor Bruto|Valor Bruto Repassado
T9L|15|T9L_VLRECP|N|16|2|Valor Retido|Valor Retenção CP
--- ### T9M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9M|01|T9M_FILIAL|C|6|0|Filial|Filial
T9M|02|T9M_ID|C|36|0|ID|Identificador do Registro
T9M|03|T9M_VERSAO|C|14|0|Id Ver Reg|Id da Versão do Registro
T9M|04|T9M_IDCODP|C|36|0|Id Cód Part|Id Cód Participante
T9M|05|T9M_CODFAT|C|10|0|Núm Fatura|Número da Fatura
T9M|06|T9M_PREFIX|C|5|0|Prefixo|Prefixo da Fatura
T9M|07|T9M_IDCODF|C|36|0|ID Cód Fat|Identificador Cód Fatura
T9M|08|T9M_CHVNF|C|36|0|Cód Docto|Código Documento Fiscal
T9M|09|T9M_SERIE|C|20|0|Série|Série Documento Fiscal
T9M|10|T9M_SUBSER|C|20|0|Sub-Série|Sub-Série Docto Fiscal
T9M|11|T9M_NUMDOC|C|60|0|Núm Doc Fisc|Número Documento Fiscal
T9M|12|T9M_IDPROC|C|6|0|ID Processo|Identificador do Processo
T9M|13|T9M_TPPROC|C|1|0|Tipo Proc|Tipo do Processo
T9M|14|T9M_NUMPRO|C|21|0|Núm Proc|Número do Processo
T9M|15|T9M_CODSUS|C|14|0|Cód Susp|Código da Suspensão
T9M|16|T9M_IDSUSP|C|34|0|ID Cód Susp|Id Código Suspensão
T9M|17|T9M_VLNRET|N|16|2|Vlr Não Ret|Valor não Retido
--- ### T9N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9N|01|T9N_FILIAL|C|6|0|Filial|Filial
T9N|02|T9N_ID|C|36|0|ID|Identificador do registro
T9N|03|T9N_VERSAO|C|14|0|Id. Ver. Reg|Id da versao do registro
T9N|04|T9N_VERANT|C|14|0|Ver Ant Reg|Versao anterior registro
T9N|05|T9N_STATUS|C|1|0|Status Reg.|Status do registro
T9N|06|T9N_ATIVO|C|1|0|Reg. Ativo?|Registro ativo?
T9N|07|T9N_PROTUL|C|44|0|Ult. Prot.|Prot. ultima transmissao
T9N|08|T9N_PROTPN|C|44|0|Pnlt. Prot.|Prot. penultima transm.
T9N|09|T9N_EVENTO|C|1|0|Id. Evento|Identificacao do evento
T9N|10|T9N_PERAPU|C|6|0|Per Apuracao|Periodo Apuracao
T9N|11|T9N_VRECBT|N|14|2|Vr.Rec.Bruta|Vr.Rec.Bruta Total Estab.
T9N|12|T9N_VCPAPU|N|14|2|Vr.Cont.Prev|Vr.Contrib.Previdenciaria
T9N|13|T9N_VRAAPU|N|14|2|V.Pre.GILRAT|Vr.Previdenciária GILRAT
T9N|14|T9N_VSEAPU|N|14|2|V.Cont.SENAR|Vr.Contribuicao SENAR
T9N|15|T9N_VCPSUS|N|14|2|V.exigi.Susp|Vr.Cont.Prev.exig.suspens
T9N|16|T9N_VRASUS|N|14|2|V.GILRAT Exi|V.Cont.GILRAT Exig.Suspen
T9N|17|T9N_VSESUS|N|14|2|V.SENAR Exig|V.Cont.SENAR Exig.Suspens
T9N|18|T9N_PROCID|C|6|0|Proc ID|ID de Processos
T9N|19|T9N_XMLID|C|36|0|Id do XML.|Id do XML.
T9N|20|T9N_IDESTA|C|6|0|Id Estab|Id do estabelecimento
T9N|21|T9N_DESTAB|C|220|0|Desc Estab|Descricao do Estab.
T9N|22|T9N_TPINSC|C|1|0|Tp Inscricao|Tipo de Inscricao
T9N|23|T9N_NRINSC|C|14|0|Nr Insc Est|Num. Inscricao do Contrib
--- ### T9O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9O|01|T9O_FILIAL|C|6|0|Filial|Filial
T9O|02|T9O_ID|C|36|0|ID|Identificador Registro
T9O|03|T9O_VERSAO|C|14|0|Id. Ver. Reg|Id da versao do registro
T9O|04|T9O_IDCOM|C|1|0|Ind.Comercia|Indicat.Comercializacao
T9O|05|T9O_VRECBR|N|14|2|Vl.Tot.Comer|Vl.Tot.Comercializacao
--- ### T9P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9P|01|T9P_FILIAL|C|6|0|Filial|Filial
T9P|02|T9P_ID|C|36|0|ID|Identificador Registro
T9P|03|T9P_VERSAO|C|14|0|Id. Ver. Reg|Id da versao do registro
T9P|04|T9P_IDCOM|C|1|0|Ind.Comercia|Indicativo Comercializaca
T9P|05|T9P_TPPROC|C|1|0|Tipo Process|Tipo de Processo
T9P|06|T9P_NRPROC|C|21|0|Num.Processo|Numero do Processo
T9P|07|T9P_CODSUS|C|14|0|Indic.Suspen|Indicativo da Suspensao
T9P|08|T9P_VCPSUS|N|14|2|Contr.Previd|Vl.Contr.Prevididenciaria
T9P|09|T9P_VRASUS|N|14|2|Contr.Gilrat|Vl.Contribuicao Gilrat
T9P|10|T9P_VSESUS|N|14|2|Contr.Senar|Vl.Contribuicao Senar
--- ### T9Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9Q|01|T9Q_FILIAL|C|6|0|Filial|Filial da Tabela
T9Q|02|T9Q_CHVNF|C|36|0|Chave N.F.|Código Chave N.F.
T9Q|03|T9Q_NUMITE|C|4|0|Num. Item|Numero do Item
T9Q|04|T9Q_ID|C|36|0|Id do Regist|Id do Registro
T9Q|05|T9Q_NUMPRO|C|6|0|Ident. Proce|Ident Proces ou Ato Conce
T9Q|06|T9Q_DESPRO|C|220|0|Desc. Proce.|Descrição do Processo
T9Q|07|T9Q_TPPROC|C|1|0|Tipo Process|Tipo de Processo
T9Q|08|T9Q_CODSUS|C|14|0|Cod. Suspens|Cód Indic da Suspensão
T9Q|09|T9Q_IDSUSP|C|34|0|Chave Susp.|Chave Cod. Suspensao
T9Q|10|T9Q_CODTRI|C|6|0|Cod. Tributo|Codigo do Tributo
T9Q|11|T9Q_DESTRI|C|220|0|Desc. Tribu.|Descrição do Tributo
T9Q|12|T9Q_VALSUS|N|16|2|Valor Retenç|Valor da Retenção
T9Q|13|T9Q_BSSUSP|N|14|2|Base Susp|Valor da base suspensa
T9Q|14|T9Q_VLRANO|N|14|2|Comp.Jud.Ano|Compensação Judic Ano Cal
T9Q|15|T9Q_VLRANA|N|14|2|Comp.Jud.Ant|Compensação Judic Ano Ant
--- ### T9R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9R|01|T9R_FILIAL|C|6|0|Filial|Filial
T9R|02|T9R_ID|C|36|0|ID|Identificação do Registro
T9R|03|T9R_VERSAO|C|14|0|Id. Ver. Reg|Id. da Versao do Registro
T9R|04|T9R_DTAPUR|D|8|0|Dt. Esp. Des|Dt Espetáculo Desportivo
T9R|05|T9R_VERANT|C|14|0|Ver Ant Reg|Versão Anterior Registro
T9R|06|T9R_STATUS|C|1|0|Status Reg|Status do Registro
T9R|07|T9R_PROTUL|C|44|0|Recibo|Recibo da Transmissão
T9R|08|T9R_PROPTN|C|44|0|Recibo Ant|Recibo Trans Anterior
T9R|09|T9R_EVENTO|C|1|0|Id Evento|Identificação do Evento
T9R|10|T9R_PROCID|C|6|0|Proc ID|ID de Processos.
T9R|11|T9R_ATIVO|C|1|0|Reg Ativo|Registro Ativo
--- ### T9S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9S|01|T9S_FILIAL|C|6|0|Filial|Filial
T9S|02|T9S_ID|C|36|0|ID|Identificador do Registro
T9S|03|T9S_VERSAO|C|14|0|Id Ver Reg|Id Versao do Registro
T9S|04|T9S_CODFIL|C|8|0|Cod Filial|Cod.Filial.Comerc.Evento
T9S|05|T9S_DESFIL|C|220|0|Desc. Filial|Descrição Filail
T9S|06|T9S_TPINSC|C|1|0|Tp Insc|Tipo de Inscrção
T9S|07|T9S_NRINSC|C|15|0|Nr. Insc|Numero de inscrição Estab
T9S|08|T9S_VERANT|C|14|0|Ver Ant Reg|Versão Anterior Registro
T9S|09|T9S_STATUS|C|1|0|Status Reg.|Status do Registro
T9S|10|T9S_PROTUL|C|44|0|Ult. Prot|Prot. Última transmissão
T9S|11|T9S_PROTPN|C|44|0|Pnlt. Prot.|Prot. Penultima Transmiss
T9S|12|T9S_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T9S|13|T9S_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
--- ### T9T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9T|01|T9T_FILIAL|C|6|0|Filial|Filial
T9T|02|T9T_ID|C|6|0|ID|Identificador Registro
T9T|03|T9T_TPAJUS|C|1|0|Tipo Ajuste|Tipo de Ajuste
T9T|04|T9T_CODAJU|C|2|0|Cod Ajuste|Código de Ajuste
T9T|05|T9T_VLRAJU|N|14|2|Valor Ajuste|Valor do Ajuste
T9T|06|T9T_DESCAJ|C|20|0|Desc Ajuste|Descrição do ajuste
T9T|07|T9T_DTAJUS|C|6|0|Data Ajuste|Data do Ajuste
T9T|08|T9T_CODSEQ|C|36|0|Cod. Sequenc|Código Sequencial
--- ### T9U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9U|01|T9U_FILIAL|C|6|0|Filial|Filial
T9U|02|T9U_ID|C|6|0|ID|Identificador do Registro
T9U|03|T9U_VERSAO|C|14|0|Id Ver Reg|Id da Versão do registro
T9U|04|T9U_TPINSC|C|1|0|Tp. Insc|Tipo de Inscrição
T9U|05|T9U_NRINSC|C|15|0|Nr. Insc|Número de Inscrição
T9U|06|T9U_DTINI|C|6|0|Per. Ini Vld|Periodo Inicial Validade
T9U|07|T9U_DTFIN|C|6|0|Per. Fim Vld|Periodo Final Validade
T9U|08|T9U_CLAFIS|C|6|0|ID.Clas.Trib|Clas. Trib. Contribuinte
T9U|09|T9U_CCLAFI|C|2|0|Cód.Clas.Fis|Cód. Classificação Ttrib.
T9U|10|T9U_DCLAFI|C|220|0|Desc. Clafis|Desc. Classificação Trib.
T9U|11|T9U_INDECD|C|1|0|Ind. Escr.|Ind. Obrig. Escritur. ECD
T9U|12|T9U_IDCPRB|C|1|0|Ind.Des.CPRB|Ind. Desoneração CPRB
T9U|13|T9U_INDACR|C|1|0|Ind. Acordo|Ind. Acordo Isenção Multa
T9U|14|T9U_INDSPJ|C|1|0|Ind. Sit. PJ|Indicador Situação PJ
T9U|15|T9U_NOMCTT|C|70|0|Nome Contato|Nome Contato Rec. Federal
T9U|16|T9U_CPFCTT|C|11|0|CPF Contato|CPF Contato
T9U|17|T9U_FONFIX|C|13|0|Telefone|Telefone
T9U|18|T9U_FONCEL|C|13|0|Celular|Telefone Celular
T9U|19|T9U_EMAIL|C|60|0|E-mail|Endereço eletrônico
T9U|20|T9U_INDEFR|C|1|0|Ind. EFR|Indicado EFR
T9U|21|T9U_EFRCNP|C|14|0|CNPJ EFR|CNPJ Ente Federativo Resp
T9U|22|T9U_VERANT|C|14|0|Id Ver Reg|Id da Versão do registro
T9U|23|T9U_STATUS|C|1|0|Status Reg.|Status do Registro
T9U|24|T9U_PROTUL|C|52|0|Ult. Prot.|Prot. Última Transmissão
T9U|25|T9U_PROTPN|C|52|0|Pnlt. Prot.|Penultima Transmiss
T9U|26|T9U_EVENTO|C|1|0|Pnlt. Prot.|Prot. Penultima Transmiss
T9U|27|T9U_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T9U|28|T9U_PROCID|C|6|0|Proc ID|Id de Processamento
T9U|29|T9U_VERORI|C|14|0|Ver. Legado|Versao Legado
T9U|30|T9U_XMLID|C|36|0|Id do XML.|Id do XML.
T9U|31|T9U_INDUNI|C|1|0|Ind Entidade|Ind. Entidade Vinculada
T9U|32|T9U_DTFINS|D|8|0|Dt. Transf|Dt. Transf. Entidade
T9U|33|T9U_DTOBIT|D|8|0|Dt. Óbito|Dt Óbito Contribuente
T9U|34|T9U_INDPER|C|1|0|Id Pert IRRF|Ind. Pertecimento IRRF
--- ### T9V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9V|01|T9V_FILIAL|C|6|0|Filial|Filial
T9V|02|T9V_ID|C|6|0|Id|Id do Registro
T9V|03|T9V_VERSAO|C|14|0|Versão|Versão do Registro
T9V|04|T9V_TPPROC|C|1|0|Tp. Processo|Tipo Processo
T9V|05|T9V_NUMPRO|C|21|0|Nº Processo|Número do Processo
T9V|06|T9V_DTINI|C|6|0|InicValidade|Início da Validade
T9V|07|T9V_DTFIN|C|6|0|Fim Validade|Fim da Validade
T9V|08|T9V_INDAUD|C|1|0|IndAuditoria|Indicativo da autoria
T9V|09|T9V_IDUFVA|C|6|0|Id. UF Vara|Identificador UF da Vara
T9V|10|T9V_CDUFVA|C|2|0|UF Vara|UF da Vara
T9V|11|T9V_DSUFVA|C|220|0|Desc UF Vara|Descrição UF Vara
T9V|12|T9V_IDMUNI|C|6|0|Id Município|Id do Município
T9V|13|T9V_CDMUNI|C|6|0|CodMunicípio|Código do Município
T9V|14|T9V_DSMUNI|C|220|0|Município|Nome do Município
T9V|15|T9V_IDVARA|C|4|0|Id Vara|Id da Vara
T9V|16|T9V_EVENTO|C|1|0|Id. Evento|Identificação do Evento
T9V|17|T9V_STATUS|C|1|0|Status Reg.|Status do registro
T9V|18|T9V_ATIVO|C|1|0|Reg. Ativo?|Registro Ativo?
T9V|19|T9V_PROTPN|C|44|0|Pnlt.Prot.Tr|Prot. Penúltima transm.
T9V|20|T9V_PROTUL|C|44|0|Ult.Prot.Tr.|Prot. Última transmissão
T9V|21|T9V_VERANT|C|14|0|Id. Ver. Ant|Id versão anterior reg.
T9V|22|T9V_PROCID|C|6|0|Proc ID|ID de Processos
T9V|23|T9V_VERORI|C|14|0|Ver. Legado|Versao Legado
T9V|24|T9V_XMLID|C|36|0|Id do XML.|Id do XML.
--- ### T9W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9W|01|T9W_FILIAL|C|6|0|Filial|Filial
T9W|02|T9W_ID|C|6|0|ID|Identificador do Registro
T9W|03|T9W_VERSAO|C|14|0|Id Ver Reg|Id da Versão do registro
T9W|04|T9W_SHCNPJ|C|14|0|S.House.CNPJ|Softwer House CNPJ
T9W|05|T9W_SHNOME|C|115|0|Razão|Razão Social
T9W|06|T9W_SHCONT|C|70|0|Nome Ctt|Nome Contato na Empresa
T9W|07|T9W_SHTEL|C|13|0|S. House Tel|Telefone da Softwer House
T9W|08|T9W_EMAIL|C|60|0|E-MAIL|Endereço Eletronico
--- ### T9X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9X|01|T9X_FILIAL|C|6|0|Filial|Filial
T9X|02|T9X_ID|C|6|0|ID|Identificador do Registro
T9X|03|T9X_VERSAO|C|14|0|Id. Ver. Reg|Id da versão do registro
T9X|04|T9X_CODSUS|C|14|0|Código Susp.|Código de Suspensão
T9X|05|T9X_IDSUSP|C|6|0|ID Ind Susp|ID Indicativo Suspensão
T9X|06|T9X_CIDSUS|C|2|0|Cod ID Susp|Código ID Suspensão
T9X|07|T9X_DIDSUS|C|220|0|Des.Ind.Susp|Descrição Indic Suspensão
T9X|08|T9X_DTDECI|D|8|0|Data Decisão|Data da decisão Sentença
T9X|09|T9X_INDDEP|C|1|0|Ind.Depósito|Indicativo de Depósito
--- ### T9Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9Y|01|T9Y_FILIAL|C|6|0|Filial|Filial
T9Y|02|T9Y_ID|C|36|0|ID|Identificador do Registro
T9Y|03|T9Y_VERSAO|C|14|0|Id Ver Reg.|Id da versão do registro
T9Y|04|T9Y_SERIE|C|5|0|Série|Série
T9Y|05|T9Y_NUMDOC|C|15|0|Núm Docto.|Número do Documento
T9Y|06|T9Y_NUMFAT|C|15|0|Núm Fat.|Número da Fatura
T9Y|07|T9Y_TPSERV|C|6|0|Tipo Serviço|Tipo de serviço
T9Y|08|T9Y_CODSER|C|9|0|Cód Tp Serv.|Código do tipo de Serviço
T9Y|09|T9Y_DTPSER|C|250|0|Desc Tp Serv|Desc. do tipo de serviço
T9Y|10|T9Y_VLRBAS|N|14|2|Vlr Bc Ret.|Valor Bc Retenção
T9Y|11|T9Y_VLRRET|N|14|2|Vlr Retenção|Valor da Retenção
T9Y|12|T9Y_VLRRSU|N|14|2|Vlr Ret Sub.|Valor Ret Subcontratados
T9Y|13|T9Y_VLRNPR|N|14|2|Vlr Ret Prin|Valor de Retenção Princip
T9Y|14|T9Y_VLRS15|N|14|2|Vlr Serv 15|Valor Serv 15 anos Cont
T9Y|15|T9Y_VLRS20|N|14|2|Vlr Serv 20|Valor Serv 20 anos Cont
T9Y|16|T9Y_VLRS25|N|14|2|Vlr Serv 25|Valor Serv 25 anos Cont
T9Y|17|T9Y_VLRADI|N|14|2|Vlr Adic.|Valor Adicional
T9Y|18|T9Y_VLRNRE|N|14|2|Vlr Ad N Con|Valor Ret Não Contratante
--- ### T9Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
T9Z|01|T9Z_FILIAL|C|6|0|Filial|Filial
T9Z|02|T9Z_ID|C|36|0|ID|Identificador do registro
T9Z|03|T9Z_VERSAO|C|14|0|Id Ver Reg|Id da versão do Registro
T9Z|04|T9Z_IDPROC|C|6|0|Id Processo|Id do Processo Ret
T9Z|05|T9Z_TPPROC|C|1|0|Tp Processo|Tipo de processo
T9Z|06|T9Z_NUMPRO|C|21|0|Núm Processo|Número do Processo
T9Z|07|T9Z_CODSUS|C|14|0|Cód Susp|Código de Suspensão
T9Z|08|T9Z_IDSUSP|C|34|0|Chave Susp|Chave do Cod. Suspensão
T9Z|09|T9Z_VLRPRI|N|14|2|Vlr Princip|Valor Principal
--- ### TQ7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ7|01|TQ7_FILIAL|C|6|0|Filial|Filial
TQ7|02|TQ7_CODLAY|C|6|0|Cód. Layout|Código do Layout
TQ7|03|TQ7_DESLAY|C|150|0|Desc. Layout|Descrição do Layout
TQ7|04|TQ7_TABELA|C|3|0|Cód. Tabela|Tabela Principal
TQ7|05|TQ7_DESTAB|C|150|0|Desc. Tabela|Descrição da Tabela
TQ7|06|TQ7_TIPARQ|C|1|0|Arquivo TXT|Tipo de Arquivo TXT
TQ7|07|TQ7_SEPARD|C|1|0|Separador|Tipo de Separador
TQ7|08|TQ7_FORDTA|C|1|0|Formato Data|Formato da Data
TQ7|09|TQ7_SEPDEC|C|1|0|Sep. Decimal|Separador Decimal
TQ7|10|TQ7_INDCAB|C|1|0|Cabeçalho|Indica cabeçalho
TQ7|11|TQ7_INDROD|C|1|0|Ind. Rodapé|Indica Rodapé
TQ7|12|TQ7_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### TQ8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQ8|01|TQ8_FILIAL|C|6|0|Filial|Filial
TQ8|02|TQ8_CODLAY|C|6|0|Cód. Layout|Código do Layout
TQ8|03|TQ8_SEQUEN|N|3|0|Seq. Campo|Sequência do Campo
TQ8|04|TQ8_CPOTAB|C|10|0|Campo|Campos do layout
TQ8|05|TQ8_TIPO|C|1|0|Tipo|Tipo do Campo
TQ8|06|TQ8_POSINI|N|4|0|Início|Posição Inicial da Linha
TQ8|07|TQ8_TAMARQ|N|3|0|Tamanho|Tamanho do Campo
TQ8|08|TQ8_POSFIM|N|3|0|Fim|Posição Final da Linha
TQ8|09|TQ8_CONTEU|C|20|0|Contéudo|Contéudo do registro
TQ8|10|TQ8_FUNCAO|C|80|0|Função|Função de processamento
--- ### TQF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQF|01|TQF_FILIAL|C|6|0|Filial|Filial do Sistema
TQF|02|TQF_COMBOI|C|1|0|Comboio?|Comboio?
TQF|03|TQF_CODIGO|C|6|0|Codigo|Codigo do Posto
TQF|04|TQF_LOJA|C|2|0|Loja|Codigo da Loja
TQF|05|TQF_POSTO|C|50|0|Posto|Nome do Posto
TQF|06|TQF_CNPJ|C|14|0|CNPJ/CPF|CNPJ/CPF Fornecedor
TQF|07|TQF_NREDUZ|C|30|0|Nom.Fantasia|Nome Fantasia
TQF|08|TQF_CIDADE|C|20|0|Cidade|Nome Cidade
TQF|09|TQF_BAIRRO|C|20|0|Bairro|Nome do Bairro
TQF|10|TQF_ESTADO|C|2|0|Estado|Estado
TQF|11|TQF_TIPPOS|C|1|0|Tipo Posto|Tipo de Posto
TQF|12|TQF_CONVEN|C|1|0|Convenio|Tipo de Convenio
TQF|13|TQF_ATIVO|C|1|0|Ativo|Ativo
TQF|14|TQF_CODFIL|C|6|0|Cod. Filial|Codigo Filial
TQF|15|TQF_CONTAT|C|30|0|Contato|Contato Posto
TQF|16|TQF_FUNCAO|C|20|0|Funcao|Funcao do Contato
TQF|17|TQF_CONTFN|C|15|0|Fone Contato|Fone Contato
TQF|18|TQF_DTCAD|D|8|0|Dt. Cadastro|Data do Cadastro
TQF|19|TQF_DTDESA|D|8|0|Desativacao|Data Desativacao
TQF|20|TQF_DTREAT|D|8|0|Reativacao|Data Reativacao
TQF|21|TQF_LANMAN|C|1|0|Lanc. Manual|Lancamento Manual
TQF|22|TQF_DTUMOD|D|8|0|Dt. Modific.|Data Ultima Modificacao
TQF|23|TQF_USUARI|C|15|0|Usuario|Usuario
TQF|24|TQF_FROTA|C|16|0|Frota|Frota do Comboio
--- ### TQG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQG|01|TQG_FILIAL|C|6|0|Filial|Filial do Sistema
TQG|02|TQG_CODPOS|C|6|0|Posto|Codigo do Posto
TQG|03|TQG_LOJA|C|2|0|Loja|Codigo da Loja
TQG|04|TQG_DTNEG|D|8|0|Negociacao|Data da Negociacao
TQG|05|TQG_HRNEG|C|5|0|Hora Negoc.|Hora da Negociacao
TQG|06|TQG_PRAZO|N|3|0|Nº Dias Pgto|Prazo Pagamento
TQG|07|TQG_DIAFAT|N|2|0|Nº Dias Fat.|Dias do Faturamento
TQG|08|TQG_DIALIM|N|2|0|NºD.Envio NF|Dia Limite Envio NF
TQG|09|TQG_CONTAT|C|30|0|Contato|Nome Contato
TQG|10|TQG_FUNCAO|C|20|0|Funcao|Funcao do Contato
TQG|11|TQG_ORDENA|C|8|0|Ordenacao|Ordenacao
TQG|12|TQG_CODTRA|C|6|0|Cód. Transf.|Código da Transferência
--- ### TQH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQH|01|TQH_FILIAL|C|6|0|Filial|Filial do Sistema
TQH|02|TQH_CODPOS|C|6|0|Posto|Codigo do Posto
TQH|03|TQH_LOJA|C|2|0|Loja|Loja
TQH|04|TQH_CODCOM|C|3|0|Combustivel|Tipo de Combustivel
TQH|05|TQH_NOMCOM|C|20|0|Descricao|Descricao do Combustivel
TQH|06|TQH_DTNEG|D|8|0|Negociacao|Data da Negociacao
TQH|07|TQH_HRNEG|C|5|0|Hora Negoc.|Hora da Negociacao
TQH|08|TQH_PREBOM|N|9|3|Preco Bomba|Preco Bomba
TQH|09|TQH_PRENEG|N|9|3|Preco Negoc.|Preco Negociado
TQH|10|TQH_DESCON|N|6|3|%Desconto|Percentual de Desconto
TQH|11|TQH_DTATUA|D|8|0|Atualizacao|Data da Atualizacao
TQH|12|TQH_USUARI|C|15|0|Usuario|Usuario
TQH|13|TQH_ORDENA|C|8|0|Ordenacao|Ordenacao
TQH|14|TQH_CODTRA|C|6|0|Cód. Transf.|Código da Transferência
--- ### TQI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQI|01|TQI_FILIAL|C|6|0|Filial|Filial do Sistema
TQI|02|TQI_CODPOS|C|6|0|Posto|Codigo do Posto
TQI|03|TQI_NREDUZ|C|30|0|Descricao|Nome do Posto
TQI|04|TQI_LOJA|C|2|0|Loja|Codigo da Loja
TQI|05|TQI_TANQUE|C|2|0|Tanque|Tanque de Combustivel
TQI|06|TQI_CODCOM|C|3|0|Combustivel|Codigo do Combustivel
TQI|07|TQI_PRODUT|C|15|0|Produto|Codigo do Produto
TQI|08|TQI_FABRIC|C|6|0|Fabricante|Codigo do Fabricante
TQI|09|TQI_CAPNOM|N|8|2|Cap. Nominal|Capacidade Nominal
TQI|10|TQI_CAPMAX|N|8|2|Cap. Maxima|Capacidade Maxima do Tanq
TQI|11|TQI_INSTAL|C|1|0|Instalacao|Tipo de Instalacao
TQI|12|TQI_DIAMET|N|8|3|Diametro/mm|Diametro do Tanque
TQI|13|TQI_INCLIN|N|2|0|º Inclinacao|Graus de Inclinacao
--- ### TQJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQJ|01|TQJ_FILIAL|C|6|0|Filial|Filial do Sistema
TQJ|02|TQJ_CODPOS|C|6|0|Posto|Codigo do Posto
TQJ|03|TQJ_NREDUZ|C|30|0|Descricao|Nome do Posto
TQJ|04|TQJ_LOJA|C|2|0|Loja|Codigo da Loja
TQJ|05|TQJ_TANQUE|C|2|0|Tanque|Tanque de Combustiveis
TQJ|06|TQJ_BOMBA|C|3|0|Bomba|Bomba de Combustiveis
TQJ|07|TQJ_FABRIC|C|6|0|Fabric.Bomba|Fabricante da Bomba
TQJ|08|TQJ_FABBIC|C|6|0|Fabric. Bico|Fabricante do Bico Bomba
TQJ|09|TQJ_DIAMBO|N|5|2|Diam.Bico/mm|Diametro do Bico Bomba
TQJ|10|TQJ_CONINI|N|10|2|Cont.Inicial|Contador Inicial
TQJ|11|TQJ_DTCONT|D|8|0|Dt.Inic.Cont|Data Inicial do Contador
TQJ|12|TQJ_HRCONT|C|5|0|Hr.Inic.Cont|Hora Inicial Contador
TQJ|13|TQJ_MOTIVO|C|1|0|Motivo|Motivo Marcacao Contador
TQJ|14|TQJ_LIMCON|N|10|2|Limite Cont.|Limite do Contador
--- ### TQK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQK|01|TQK_FILIAL|C|6|0|Filial|Filial do Sistema
TQK|02|TQK_POSTO|C|6|0|Posto Int.|Posto Interno
TQK|03|TQK_LOJA|C|2|0|Loja|Codigo da Loja
TQK|04|TQK_NOME|C|40|0|Nome|Nome Reduzido do Posto
TQK|05|TQK_TANQUE|C|2|0|Tanque|Tanque de Combustivel
TQK|06|TQK_DTMEDI|D|8|0|Data Medicao|Data da Medicao do Tanque
TQK|07|TQK_HRMEDI|C|5|0|Hora Medicao|Hora da Medicao do Tanque
TQK|08|TQK_QTDINI|N|8|2|Qtde Inicial|Qtde da Ultima Medicao
TQK|09|TQK_QTDMED|N|8|2|Qtde Medida|Quantidade Medida
TQK|10|TQK_CODFUN|C|6|0|Funcionario|Codigo do Funcionario
TQK|11|TQK_NOMFUN|C|20|0|Nome|Nome do Funcionario
--- ### TQL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQL|01|TQL_FILIAL|C|6|0|Filial|Filial do Sistema
TQL|02|TQL_POSTO|C|6|0|Posto Int.|Posto Interno
TQL|03|TQL_LOJA|C|2|0|Loja|Codigo da Loja
TQL|04|TQL_NOME|C|40|0|Nome|Nome do Posto Reduzido
TQL|05|TQL_DTCOLE|D|8|0|Data Coleta|Data da Coleta
TQL|06|TQL_TANQUE|C|2|0|Tanque|Tanque
TQL|07|TQL_BOMBA|C|3|0|Bomba|Bomba de Combustivel
TQL|08|TQL_FUNINI|C|6|0|Fun. Inicial|Funcionario Inicial
TQL|09|TQL_FUNNOM|C|30|0|Nome|Nome do Funcionario
TQL|10|TQL_HRINIC|C|5|0|Hora Inicial|Hora Inicial
TQL|11|TQL_POSINI|N|9|2|Posicao Inic|Posicao Inicial Contador
TQL|12|TQL_FUNFIM|C|6|0|Fun. Final|Funcionario Final
TQL|13|TQL_FUNNOF|C|30|0|Nome|Nome Funcionario Final
TQL|14|TQL_HRFIM|C|5|0|Hora Final|Hora Final
TQL|15|TQL_POSFIM|N|9|2|Posicao Fim|Posicao Final
TQL|16|TQL_CONSUM|N|11|2|Consumo|Consumo
--- ### TQM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQM|01|TQM_FILIAL|C|6|0|Filial|Filial do Sistema
TQM|02|TQM_CODCOM|C|3|0|Cod.Combust.|Codigo Combustivel
TQM|03|TQM_NOMCOM|C|20|0|Descrição|Descrição Combustivel
TQM|04|TQM_UM|C|2|0|Unidade|Unidade de Medida
TQM|05|TQM_CONVEN|C|1|0|Convenio|Tipo de Convenio
TQM|06|TQM_CODCON|C|10|0|Cod.Convenio|Codigo Combustivel Conven
--- ### TQN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQN|01|TQN_FILIAL|C|6|0|Filial|Filial do Sistema
TQN|02|TQN_NABAST|C|15|0|N. Abastec.|Numero do Abastecimento
TQN|03|TQN_PLACA|C|8|0|Placa|Placa do Veiculo
TQN|04|TQN_FROTA|C|16|0|Frota|Codigo da Frota
TQN|05|TQN_DESFRO|C|40|0|Descricao|Descricao do Veiculo
TQN|06|TQN_POSTO|C|6|0|Cod. Posto|Codigo do Posto
TQN|07|TQN_LOJA|C|2|0|Loja|Codigo da Loja
TQN|08|TQN_DESCPO|C|30|0|Descricao|Nome do Posto
TQN|09|TQN_CNPJ|C|14|0|CNPJ/CPF|CNPJ/CPF Fornecedor
TQN|10|TQN_CODCOM|C|3|0|Combustivel|Codigo do Combustivel
TQN|11|TQN_NOTFIS|C|9|0|N. Nota/Req|Num. Nota Fiscal/Requisic
TQN|12|TQN_DTABAS|D|8|0|Dt. Abastec.|Data do Abastecimento
TQN|13|TQN_HRABAS|C|5|0|Hora|Hora do Abastecimento
TQN|14|TQN_TANQUE|C|2|0|Tanque|Tanque
TQN|15|TQN_BOMBA|C|3|0|Bomba|Bomba de Combustiveis
TQN|16|TQN_QUANT|N|9|3|Quantidade|Quantidade de Combustivel
TQN|17|TQN_VALUNI|N|9|3|Vlr.Unitario|Valor Unitario
TQN|18|TQN_VALTOT|N|15|3|Valor Total|Valor Total do Abastecim.
TQN|19|TQN_HODOM|N|9|0|Contador 1|Hodometro(Km)
TQN|20|TQN_POSCO2|N|9|0|Contador 2|Posicao do 2 Contador
TQN|21|TQN_CODVIA|C|6|0|Cod. Viagem|Codigo da Viagem
TQN|22|TQN_ESCALA|C|8|0|Escala|Escala
TQN|23|TQN_NABAAN|C|15|0|N.Abast.Ant.|Numero Abastec. Anterior
TQN|24|TQN_CODMOT|C|6|0|Motorista|Codigo do Motorista
TQN|25|TQN_NOMMOT|C|40|0|Nome|Nome do Motorista
TQN|26|TQN_USUARI|C|15|0|Usuario|Usuario
TQN|27|TQN_DTCON|D|8|0|Dt.Concilia.|Data Conciliacao
TQN|28|TQN_AUTO|C|1|0|Ent.Automat.|Entrada Automatica
TQN|29|TQN_DTDIGI|D|8|0|Dt.Digitacao|Data da Digitacao
TQN|30|TQN_DTPGMT|D|8|0|Data Pagamto|Data do Pagamento
TQN|31|TQN_NUMSEQ|C|6|0|Sequencial|Sequencial
TQN|32|TQN_NUMCON|C|15|0|NºAbast.Conv|Numero Abast.Convenio
TQN|33|TQN_DTPREV|D|8|0|Dt. Previsao|Data Previsao
TQN|34|TQN_DTPROV|D|8|0|Dt. Provisao|Data de Provisao
TQN|35|TQN_DTEMIS|D|8|0|Data Emis NF|Data Emis. NF
TQN|36|TQN_DTINTE|D|8|0|Dt.Integ.Est|Data Integracao Estoque
TQN|37|TQN_DINTMS|D|8|0|Dt.Integ.TMS|Dt.Integ.TMS
TQN|38|TQN_DINTCG|D|8|0|Dt.Int.Cogno|Data Integracao Cognos
TQN|39|TQN_CCUSTO|C|9|0|Centro Custo|Centro Custo
TQN|40|TQN_CENTRA|C|6|0|Centro trab.|Centro trab.
TQN|41|TQN_ORDENA|C|8|0|Ordenacao|Ordenacao
TQN|42|TQN_NUMSGC|C|6|0|Num.Seq.SGC|Num.Seq.SGC
TQN|43|TQN_DTAANT|D|8|0|Dt.Abas.Ant|Data Abastec. Anterior
TQN|44|TQN_HRAANT|C|5|0|Hr.Abas.Ant.|Hora Abastec. Anterior
TQN|45|TQN_HODANT|N|9|0|Hodom.Ant.|Hodometro Anterior
TQN|46|TQN_VARDIA|N|6|0|Variacao Dia|Variacao Dia
TQN|47|TQN_KMROD|N|9|0|Km. Rodado|Km. Rodado
TQN|48|TQN_MEDIA|N|9|2|Media KM/L|Media KM/L
TQN|49|TQN_OSLUBR|C|6|0|O.S. Lubrif.|O.S. Lubrificante
TQN|50|TQN_FILORI|C|6|0|Filial Orig.|Filial Origem
TQN|51|TQN_ITEMSC|C|4|0|Item PC|Item do Pedido de Compra
TQN|52|TQN_NUMSC7|C|6|0|Número PC|Número do Pedido de Compr
--- ### TQO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQO|01|TQO_FILIAL|C|6|0|Filial|Filial do Sistema
TQO|02|TQO_CODPOS|C|6|0|Posto|Codigo do Posto
TQO|03|TQO_NREDUZ|C|30|0|Descricao|Nome do Posto
TQO|04|TQO_LOJA|C|2|0|Loja|Codigo da Loja
TQO|05|TQO_ATIVO|C|1|0|Ativo|Ativo
TQO|06|TQO_DTCAD|D|8|0|Dt. Cadastro|Data Cadastro
TQO|07|TQO_DTDESA|D|8|0|Desativacao|Data Desativacao
TQO|08|TQO_DTUMOD|D|8|0|Dt. Modific.|Data Ultima Modificacao
TQO|09|TQO_USUARI|C|15|0|Usuario|Usuario
--- ### TQP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQP|01|TQP_FILIAL|C|6|0|Filial|Filial do Sistema
TQP|02|TQP_NABAST|C|15|0|Cod.Abastec.|Codigo do Abastecimento
TQP|03|TQP_CNPJ|C|14|0|CNPJ|CNPJ
TQP|04|TQP_CODERR|C|3|0|Cod. Erro|Codigo do Erro
TQP|05|TQP_DTABAS|D|8|0|Dt. Abastec.|Data do Abastecimento
--- ### TQQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQQ|01|TQQ_FILIAL|C|6|0|Filial|Filial do Sistema
TQQ|02|TQQ_PLACA|C|8|0|Placa|Placa do Veiculo
TQQ|03|TQQ_CNPJ|C|14|0|CNPJ|CNPJ do Posto
TQQ|04|TQQ_DTABAS|D|8|0|Dt. Abastec.|Data do Abastecimento
TQQ|05|TQQ_HRABAS|C|5|0|Hora|Hora do Abastecimento
TQQ|06|TQQ_QUANT|N|9|3|Quantidade|Quantidade de Combustivel
TQQ|07|TQQ_VALTOT|N|15|2|Valor Total|Valor Total do Abastecim.
TQQ|08|TQQ_VALUNI|N|9|3|Vlr.Unitario|Valor Unitario
TQQ|09|TQQ_CODCOM|C|10|0|Comb. Conv.|Combustivel Conveniado
TQQ|10|TQQ_NOMCOM|C|20|0|Combustivel|Descricao do Combustivel
TQQ|11|TQQ_HODOM|N|9|0|Hodom.(Km)|Hodometro(Km)
TQQ|12|TQQ_NABAST|C|15|0|N. Abastec.|Numero do Abastecimento
TQQ|13|TQQ_NABAAN|C|15|0|N.Abast.Ant.|Numero Abastec. Anterior
TQQ|14|TQQ_CODMOT|C|14|0|CPF Motorist|Codigo do Motorista
TQQ|15|TQQ_USUARI|C|15|0|Usuario|Usuario
TQQ|16|TQQ_ERROVA|C|3|0|Erro VD Auto|Erro Var.Dia ou Autonomia
TQQ|17|TQQ_TANQUE|C|2|0|Tanque|Tanque de Combustiveis
TQQ|18|TQQ_BOMBA|C|3|0|Bomba|Bomba de Combustiveis
TQQ|19|TQQ_POSCO2|N|9|0|2. Contador|Posicao Segundo Contador
TQQ|20|TQQ_EMPORI|C|2|0|Emp. Orig.|Empresa Origem
TQQ|21|TQQ_FILORI|C|6|0|Filial Orig.|Filial Origem
TQQ|22|TQQ_EMPDES|C|2|0|Emp. Dest.|Empresa Destino
TQQ|23|TQQ_FILDES|C|6|0|Filial Dest.|Filial Destino
TQQ|24|TQQ_POSTO|C|6|0|Posto|Posto
TQQ|25|TQQ_LOJA|C|2|0|Loja|Loja
TQQ|26|TQQ_POSDES|C|6|0|Posto Dest.|Posto Destino
TQQ|27|TQQ_LOJDES|C|2|0|Loja Dest.|Loja Destino
TQQ|28|TQQ_TANDES|C|2|0|Tanque Dest.|Tanque Destino
TQQ|29|TQQ_MOTTRA|C|6|0|Mot. Transf.|Motivo da Transferência
TQQ|30|TQQ_OBSERV|M|80|0|Observações|Código da Observação SYP
TQQ|31|TQQ_CODOBS|C|6|0|Código Obs.|Código da Observação SYP
TQQ|32|TQQ_CONVEN|C|1|0|Convenio|Tipo de Convenio
--- ### TQS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQS|01|TQS_FILIAL|C|6|0|Filial|Filial do Sistema
TQS|02|TQS_CODBEM|C|16|0|Codigo Pneu|Codigo do Pneu
TQS|03|TQS_DESBEM|C|20|0|Desc. Pneu|Descricao do Pneu
TQS|04|TQS_MEDIDA|C|6|0|Cod. Medida|Codigo da medida
TQS|05|TQS_DESMED|C|20|0|Medida Pneu|Medida do Pneu
TQS|06|TQS_NUMFOG|C|10|0|Nº Fogo Pneu|Numero de Fogo Pneu
TQS|07|TQS_SULCAT|N|6|2|Sulco Atual|Profundidade Sulco Atual
TQS|08|TQS_DTMEAT|D|8|0|Dt Sulco At.|Data Med. Sulco Atual
TQS|09|TQS_HRMEAT|C|5|0|Hr Med Sulco|Hora Medicao do Sulco
TQS|10|TQS_BANDAA|C|1|0|Cod Banda At|Codigo Banda Atual
TQS|11|TQS_DESENH|C|10|0|Des. Atual|Codigo Banda Atual
TQS|12|TQS_KMOR|N|12|0|Km Percor Or|Km Perc na banda Original
TQS|13|TQS_KMR1|N|12|0|Km Banda R1|Km percorridos na BandaR1
TQS|14|TQS_KMR2|N|12|0|Km Banda R2|Km percorridos na BandaR2
TQS|15|TQS_KMR3|N|12|0|Km Banda R3|Km percorridos na BandaR3
TQS|16|TQS_KMR4|N|12|0|Km Banda R4|Km percorridos na BandaR4
TQS|17|TQS_DOT|C|4|0|DOT|Data de Fabricacao
TQS|18|TQS_EIXO|C|2|0|Número Eixo|Numero Eixo pneu
TQS|19|TQS_TIPEIX|C|1|0|Tipo do Eixo|Tipo do Eixo pneu
TQS|20|TQS_PLACA|C|8|0|Placa Veicul|Placa do Veiculo
TQS|21|TQS_NOMPAI|C|20|0|Nome Bem Pai|Nome Bem Pai
TQS|22|TQS_POSIC|C|6|0|Posição Pneu|Posicao Pneu na Estrutura
TQS|23|TQS_TWI|N|6|2|TWI|Tread Wear Indicator
--- ### TQT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQT|01|TQT_FILIAL|C|6|0|Filial|Filial do Sistema
TQT|02|TQT_MEDIDA|C|6|0|Medida|Codigo da Medida
TQT|03|TQT_DESMED|C|20|0|Descricao|Descricao da Medida
--- ### TQU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQU|01|TQU_FILIAL|C|6|0|Filial|Filial do Sistema
TQU|02|TQU_DESENH|C|10|0|Desenho|Codigo do desenho
TQU|03|TQU_FABRIC|C|6|0|Fabricante|Codigo do Fabricante
TQU|04|TQU_NOMFAB|C|20|0|Nome Fabrica|Nome do Fabricante
TQU|05|TQU_SULCO|N|6|2|Prof. sulco|Profundidade do sulco
TQU|06|TQU_KMESP1|N|3|0|Perc. Esp. 1|Percentual Km Esperado 1
TQU|07|TQU_KMESP2|N|3|0|Perc. Esp. 2|Percentual Km Esperado 2
TQU|08|TQU_KMESP3|N|3|0|Perc. Esp. 3|Percentual Km Esperado 3
TQU|09|TQU_KMESP4|N|3|0|Perc. Esp. 4|Percentual Km Esperado 4
TQU|10|TQU_TWI|N|6|2|TWI|Tread Wear Indicator
--- ### TQV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQV|01|TQV_FILIAL|C|6|0|Filial|Filial do Sistema
TQV|02|TQV_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TQV|03|TQV_DTMEDI|D|8|0|Data Medicao|Data da Medicao
TQV|04|TQV_HRMEDI|C|5|0|Hora Medicao|Hora da Medicao
TQV|05|TQV_BANDA|C|1|0|Banda rod.|Cod da Banda de Rodagem
TQV|06|TQV_DESENH|C|10|0|Cod Desenho|Codigo do Desenho
TQV|07|TQV_SULCO|N|6|2|Prof. Sulco|Profundidade do Sulco
--- ### TQX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQX|01|TQX_FILIAL|C|6|0|Filial|Filial do Sistema
TQX|02|TQX_MEDIDA|C|6|0|Medida|Codigo da Medida
TQX|03|TQX_DESMED|C|20|0|Desc Medida|Descricao da Medida
TQX|04|TQX_TIPMOD|C|10|0|Tipo Pneu|Codigo do Tipo do Pneu
TQX|05|TQX_DESMOD|C|20|0|Descricao|Desc. Tipo Modelo do Pneu
TQX|06|TQX_SULCOO|N|6|2|Sulco B. Or.|Sulco Banda Original
TQX|07|TQX_KMESPO|N|6|0|Km Esp Banda|Km Esp. na Banda Original
TQX|08|TQX_LONAS|N|2|0|Num. Lonas|Numero de Lonas
TQX|09|TQX_TIPCAR|C|1|0|Carcaca Pneu|Tipo da Carcaca do Pneu
TQX|10|TQX_CALMIN|N|3|0|Calib. Min.|Calibragem Minima
TQX|11|TQX_CALMAX|N|3|0|Calib. Max.|Calibragem Maxima
--- ### TQZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TQZ|01|TQZ_FILIAL|C|6|0|Filial|Filial do Sistema
TQZ|02|TQZ_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TQZ|03|TQZ_DTSTAT|D|8|0|Data Alt.|Data Alteracao Status
TQZ|04|TQZ_HRSTAT|C|5|0|Hora Alt.|Hora Alteracao Status
TQZ|05|TQZ_STATUS|C|2|0|Cod. Status|Codigo do Status
TQZ|06|TQZ_DESTAT|C|20|0|Desc. Status|Descricao do Status
TQZ|07|TQZ_PRODUT|C|15|0|Produto|Produto
TQZ|08|TQZ_ALMOX|C|2|0|Almoxarifado|Almoxarifado
TQZ|09|TQZ_NUMSEQ|C|6|0|Num.Sequenc.|Numeração Sequencial
TQZ|10|TQZ_ORIGEM|C|3|0|Origem|Origem
--- ### TR0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR0|01|TR0_FILIAL|C|6|0|Filial|Filial do Sistema
TR0|02|TR0_CODPOS|C|6|0|Posto|Código do Posto
TR0|03|TR0_LOJPOS|C|2|0|Loja|Loja do Posto
TR0|04|TR0_TANPOS|C|2|0|Tanque|Tanque do Posto
TR0|05|TR0_BOMPOS|C|3|0|Bomba|Bomba do Posto
TR0|06|TR0_TERMIN|C|4|0|Terminal|Terminal GTFrota
TR0|07|TR0_EXTRA|C|1|0|Extra|Informação Extra
--- ### TR1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR1|01|TR1_FILIAL|C|6|0|Filial|Filial do Sistema
TR1|02|TR1_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TR1|03|TR1_DESBEM|C|20|0|Desc. Bem|Descricao do Bem
TR1|04|TR1_BEMPAI|C|16|0|Bem Pai|Bem Pai
TR1|05|TR1_DESPAI|C|20|0|Descricao|Descricao do Bem Pai
TR1|06|TR1_DTPEND|D|8|0|Data Penden.|Data da Pendencia
TR1|07|TR1_HRPEND|C|5|0|Hora Penden.|Hora da Pendencia
TR1|08|TR1_CODPEN|C|6|0|Cod Penden.|Codigo da Pendencia
TR1|09|TR1_DESPEN|C|20|0|Descricao|Descricao da Pendencia
TR1|10|TR1_LOCAL|C|6|0|Local|Local
TR1|11|TR1_DESLOC|C|20|0|Desc. Local|Descricao do Local
TR1|12|TR1_DTSOLU|D|8|0|Data Solucao|Data da Solucao
TR1|13|TR1_HRSOLU|C|5|0|Hora Solucao|Hora da Solucao
TR1|14|TR1_USUSOL|C|15|0|Usuario Sol.|Usuario da Solucao
--- ### TR2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR2|01|TR2_FILIAL|C|6|0|Filial|Filial do Sistema
TR2|02|TR2_LOTE|C|6|0|Numero Lote|Numero Lote Transfencia
TR2|03|TR2_DTTRAN|D|8|0|Data Transf.|Data da Transferencia
TR2|04|TR2_HRTRAN|C|5|0|Hora Transf.|Hora da Transferencia
TR2|05|TR2_USUENV|C|15|0|Usuario Env.|Usuario de Envio
TR2|06|TR2_FILORI|C|6|0|Fil. Origem|Filial de Origem
TR2|07|TR2_DESORI|C|15|0|Descricao O.|Descricao Filial Origem
TR2|08|TR2_FILDES|C|6|0|Fil. Destino|Filial de Destino
TR2|09|TR2_DESDES|C|15|0|Descricao D.|Descricao Filial Destino
TR2|10|TR2_DTREC|D|8|0|Data Receb.|Data de Recebimento
TR2|11|TR2_HRREC|C|5|0|Hora Receb.|Hora de Recebimento
TR2|12|TR2_USUREC|C|15|0|Usuario Rec.|Usuario de Recebimento
TR2|13|TR2_CCUSTO|C|9|0|C.C. Destino|Centro de Custo Destino
TR2|14|TR2_NOMCUS|C|20|0|Nome C.Custo|Nome do Centro de Custo
TR2|15|TR2_OBSENV|C|80|0|Obs. Envio|Observacoes do Envio
TR2|16|TR2_OBSREC|C|80|0|Obs. Receb.|Observacoes Recebimento
--- ### TR3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR3|01|TR3_FILIAL|C|6|0|Filial|Filial do Sistema
TR3|02|TR3_LOTE|C|6|0|Lote Trans.|Numero Lote Transferencia
TR3|03|TR3_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TR3|04|TR3_CODPRO|C|15|0|Cod Produto|Codigo do Produto
TR3|05|TR3_NREQIN|C|15|0|Num Requis.|Numero da Requisicao
TR3|06|TR3_NUMSEQ|C|6|0|Seq. Requis.|Num Sequencia Requisicao
TR3|07|TR3_NUMSMA|C|6|0|Sol. Materia|Numero Solicit Materiais
TR3|08|TR3_ITEMSM|C|2|0|Item S.M.|Item Solicitacao Material
TR3|09|TR3_NUMOS|C|6|0|Ordem Serv.|Numero da Ordem Servico
TR3|10|TR3_RECEBI|C|1|0|Recebimento?|Recebimento?
TR3|11|TR3_DTENVC|D|8|0|Data Envio|Data do Envio da Carcaca
--- ### TR4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR4|01|TR4_FILIAL|C|6|0|Filial|Filial do Sistema
TR4|02|TR4_NUMANA|C|6|0|Nº Análise|Numero Analise Tecnica
TR4|03|TR4_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TR4|04|TR4_NOMBEM|C|40|0|Descricao|Descricao  do Pneu
TR4|05|TR4_MEDIDA|C|6|0|Medida|Medida
TR4|06|TR4_BANDA|C|1|0|Banda|Banda
TR4|07|TR4_MODELO|C|10|0|Modelo|Modelo
TR4|08|TR4_DOT|C|4|0|Dot|Dot
TR4|09|TR4_KMTOT|N|12|0|Km Total|Km Total
TR4|10|TR4_KMBAND|N|12|0|Km. Banda|Km. Banda
TR4|11|TR4_DTANAL|D|8|0|Data Analise|Data Analise Tecnica
TR4|12|TR4_HRANAL|C|5|0|Hora Analise|Hora Analise Tecnica
TR4|13|TR4_DESTIN|C|1|0|Destino Pneu|Destino dado ao Pneu
TR4|14|TR4_MOTIVO|C|6|0|Motivo Dest.|Motivo do destino
TR4|15|TR4_DESMOT|C|20|0|Desc Motivo|Descricao do Motivo
TR4|16|TR4_SULCO|N|6|2|Prof. Sulco|Profundidade do Sulco
TR4|17|TR4_PAREC|C|80|0|Parecer|Descricao Analise Tecnica
TR4|18|TR4_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TR4|19|TR4_LOJA|C|2|0|Codigo Loja|Codigo Loja Fornecedor
TR4|20|TR4_NOMFOR|C|80|0|Desc Fornec.|Descricao do Fornecedor
TR4|21|TR4_DTANFN|D|8|0|Dt.An.Fornec|Data Analise Fornecedor
TR4|22|TR4_LAUDO|C|12|0|Cod. Laudo|Codigo do Laudo Fornecedo
TR4|23|TR4_ACEITE|C|1|0|Aceite(S/N)?|Aceita?
TR4|24|TR4_PERCRE|N|6|2|% de Credito|Percentual de Credito
TR4|25|TR4_VLCRED|N|9|2|Val. Credito|Valor do Credito
TR4|26|TR4_INDAPD|C|1|0|Apur. Debito|Apuracao de Debito(S/N)
TR4|27|TR4_OBS|C|80|0|Observacao|Obs. analise tecnica
TR4|28|TR4_NUMSEQ|C|6|0|N.Seq. Saida|Num. Sequencial Saida
TR4|29|TR4_NUMSE2|C|6|0|N.Seq.Entrad|Num. Sequencial Entrada
TR4|30|TR4_PRDORI|C|15|0|Prod. Atu.|Produto Atual
TR4|31|TR4_LOCORI|C|2|0|Local Atu.|Local Atual
TR4|32|TR4_ENDORI|C|15|0|Endereço|Endereço Atual
TR4|33|TR4_PRDDES|C|15|0|Prod. Devol.|Produto Devolvido
TR4|34|TR4_LOCDES|C|2|0|Local Devol.|Local Devolução
TR4|35|TR4_TM|C|3|0|TP Movimento|Tipo de movimento
TR4|36|TR4_ORDEM|C|6|0|Ordem Serv.|Ordem de Serviço
--- ### TR6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR6|01|TR6_FILIAL|C|6|0|Filial|Filial do Sistema
TR6|02|TR6_NUMABA|C|15|0|Nr.Seq.Abast|Numero Seq. Abastecimento
TR6|03|TR6_PLACA|C|8|0|Placa Veicul|Placa do Veiculo
TR6|04|TR6_CNPJ|C|14|0|CNPJ Posto|CNPJ do Posto
TR6|05|TR6_TIPCOM|C|10|0|Tipo Combust|Tipo Combustivel abastec.
TR6|06|TR6_CPFMOT|C|14|0|CPF Motorist|CPF do Motorista
TR6|07|TR6_KMABAS|N|10|0|Pos Contador|Posicao do Contador
TR6|08|TR6_QTDCOM|N|9|3|Qtde C. Abas|Qtde Combust. Abastecida
TR6|09|TR6_VLCOMB|N|15|3|Vl. Un. Comb|Vl. Unitario Combustivel
TR6|10|TR6_VLTOT|N|15|2|Vl Tot Abast|Valor Total Abastecimento
TR6|11|TR6_DTABAS|D|8|0|Data Abast.|Data do Abastecimento
TR6|12|TR6_HRABAS|C|5|0|Hora Abast.|Hora do Abastecimento
TR6|13|TR6_NABANT|C|15|0|N. Abas Ant.|N. Abastecimento Anterior
TR6|14|TR6_DTPROC|D|8|0|Dt Proc Imp.|Dt Proc Rotina Importacao
TR6|15|TR6_HRPROC|C|5|0|Hr. Proc Imp|Hora Processamento Import
TR6|16|TR6_TANQUE|C|2|0|Tanque|Tanque de Combustiveis
TR6|17|TR6_BOMBA|C|3|0|Bomba|Bomba de Combustiveis
TR6|18|TR6_POSCO2|N|9|0|2. Contador|Posicao Segundo Contador
TR6|19|TR6_EMPORI|C|2|0|Emp. Orig.|Empresa Origem
TR6|20|TR6_FILORI|C|6|0|Filial Orig.|Filial Origem
TR6|21|TR6_EMPDES|C|2|0|Emp. Dest.|Empresa Destino
TR6|22|TR6_FILDES|C|6|0|Filial Dest.|Filial Destino
TR6|23|TR6_POSTO|C|6|0|Posto|Posto
TR6|24|TR6_LOJA|C|2|0|Loja|Loja
TR6|25|TR6_POSDES|C|6|0|Posto Dest.|Posto Destino
TR6|26|TR6_LOJDES|C|2|0|Loja Dest.|Loja Destino
TR6|27|TR6_TANDES|C|2|0|Tanque Dest.|Tanque Destino
TR6|28|TR6_MOTTRA|C|6|0|Mot. Transf.|Motivo da Transferência
TR6|29|TR6_OBSERV|M|80|0|Observacoes|Observações
TR6|30|TR6_CODOBS|C|6|0|Código Obs.|Código da Observação SYP
TR6|31|TR6_CONVEN|C|1|0|Convenio|Tipo de Convenio
--- ### TR7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR7|01|TR7_FILIAL|C|6|0|Filial|Filial do Sistema
TR7|02|TR7_LOTE|C|6|0|Lote Servico|Lote do Servico externo
TR7|03|TR7_DTLOTE|D|8|0|Data do Lote|Data de criacao do Lote
TR7|04|TR7_HRLOTE|C|5|0|Hora do Lote|Hora do Lote
TR7|05|TR7_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TR7|06|TR7_LOJA|C|2|0|Loja|Loja do Fornecedor
TR7|07|TR7_NOMFOR|C|80|0|Nome Fornec.|Nome do Fornecedor
TR7|08|TR7_SERVIC|C|6|0|Servico|Codigo do Servico
TR7|09|TR7_NOMSER|C|20|0|Nome Servico|Nome Servico
TR7|10|TR7_ESPECI|C|3|0|Especialid.|Codigo da Especialidade
TR7|11|TR7_NOMESP|C|20|0|Nome Espec.|Nome da Especialidade
TR7|12|TR7_DTRECI|D|8|0|Data Receb.|Data Recebimento
TR7|13|TR7_HRRECI|C|5|0|Hora Receb.|Hora do Recebimento
TR7|14|TR7_NFE|C|9|0|Nota Fiscal|Nota Fiscal de Entrada
TR7|15|TR7_SERIE|C|3|0|Serie Nf|Serie Nota Fiscal Entrada
TR7|16|TR7_NUMSC|C|6|0|Numero SC|Numero Solicitacao Compra
TR7|17|TR7_REABRE|C|1|0|Reaberto?|Reaberto?
TR7|18|TR7_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### TR8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR8|01|TR8_FILIAL|C|6|0|Filial|Filial do Sistema
TR8|02|TR8_LOTE|C|6|0|Lote Servico|Lote do Servico Externo
TR8|03|TR8_CODBEM|C|16|0|Pneu|Codigo do Pneu
TR8|04|TR8_MEDIDA|C|6|0|Medida|Medida do Pneu
TR8|05|TR8_DESMED|C|20|0|Desc. Medida|Descricao da Medida
TR8|06|TR8_TIPMOD|C|10|0|Modelo|Modelo do Pneu
TR8|07|TR8_DESMOD|C|20|0|Desc. Modelo|Descricao do Modelo
TR8|08|TR8_SULCO|N|6|2|Sulco|Sulco do Pneu
TR8|09|TR8_DESENH|C|10|0|Desenho|Desenho do Pneu
TR8|10|TR8_BANDA|C|1|0|Banda|Codigo da Banda Atual
TR8|11|TR8_INDREL|C|1|0|Realizado?|Servico Realizado ou nao?
TR8|12|TR8_VALOR|N|9|2|Vl. Servico|Valor do Servico
TR8|13|TR8_MOTIVO|C|6|0|Motivo|Motivo da nao realizacao
TR8|14|TR8_DESMOT|C|20|0|Desc. Motivo|Descricao do Motivo
TR8|15|TR8_GARANT|C|1|0|Garantia?|Indica Servico Garantia
TR8|16|TR8_OBS|C|40|0|Observacoes|Observacoes
TR8|17|TR8_OS|C|6|0|Numero OS|Numero da Ordem Servico
TR8|18|TR8_ORDEM|C|6|0|Ord. Serv.|Numero da Ordem Servico
TR8|19|TR8_PLANO|C|6|0|Plano Manut.|Numero do Plano de Manut.
TR8|20|TR8_CREDIT|N|3|0|% Credito|% Credito
TR8|21|TR8_NUMCP|C|6|0|C. Parceria|Número Contrato Parceria
TR8|22|TR8_ITEMCP|C|4|0|Item Contr.|Item Contrato Parceria
--- ### TR9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TR9|01|TR9_FILIAL|C|6|0|Filial|Filial do Sistema
TR9|02|TR9_ORDEM|C|6|0|OS Inspecao|Numero da OS de Inspecao
TR9|03|TR9_PLANO|C|6|0|Numero Plano|Numero do Plano
TR9|04|TR9_CICLO|C|2|0|Ciclo|Numero do ciclo inspecao
TR9|05|TR9_DTINSP|D|8|0|Data Inspec.|Data de Inspecao
TR9|06|TR9_HRINSP|C|5|0|Hora Inspec.|Hora da Inspecao
TR9|07|TR9_KMATU|N|9|0|Contador|Contador Atual
TR9|08|TR9_DTDIGI|D|8|0|Data Digit.|Data de Digitacao
TR9|09|TR9_HRDIGI|C|5|0|Hora Digit.|Hora de Digitacao
TR9|10|TR9_USUDIG|C|15|0|Usuario|Usuario da digitacao
TR9|11|TR9_STATUS|C|1|0|Status Ciclo|Status Ciclo
TR9|12|TR9_QTDATU|N|2|0|Quantidade|Quantidade de pneus
TR9|13|TR9_FROTA|C|16|0|Frota|Frota
TR9|14|TR9_NOME|C|40|0|Nome Frota|Nome Frota
TR9|15|TR9_PLACA|C|8|0|Placa|Placa do Veiculo
TR9|16|TR9_CODFAM|C|6|0|Familia|Familia do Bem
TR9|17|TR9_DESFAM|C|20|0|Descricao|Descricao Familia do Bem
TR9|18|TR9_TIPMOD|C|12|0|Tipo Modelo|Tipo do Modelo
TR9|19|TR9_DESMOD|C|20|0|Descricao|Descricao Tipo do Modelo
TR9|20|TR9_NUMCAL|C|8|0|Número|Número Sequencial
--- ### TRA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRA|01|TRA_FILIAL|C|6|0|Filial|Filial do Sistema
TRA|02|TRA_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TRA|03|TRA_LOJA|C|2|0|Loja|Loja
TRA|04|TRA_SERVIC|C|6|0|Servico|Codigo do Servico
TRA|05|TRA_ESPECI|C|3|0|Especialid.|Codigo da Especialidade
TRA|06|TRA_MEDIDA|C|6|0|Medida|Codigo da Medida
TRA|07|TRA_DESMED|C|20|0|Descricao|Descricao da Medida
TRA|08|TRA_BANDA|C|1|0|Banda|Codigo da Banda
TRA|09|TRA_CUSTO|N|9|2|Custo Serv.|Custo do Servico
--- ### TRC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRC|01|TRC_FILIAL|C|6|0|Filial|Filial do Sistema
TRC|02|TRC_ORDEM|C|6|0|Numero da OS|Numero Ordem de Servico
TRC|03|TRC_PLANO|C|6|0|Codigo Plano|Codigo Plano
TRC|04|TRC_CICLO|C|2|0|Numero Plano|Numero Ciclo de Inspecao
TRC|05|TRC_EIXO|C|10|0|Codigo Eixo|Codigo do Eixo
TRC|06|TRC_QTDPNE|N|2|0|Qtde Pneus|Quantidade Pneus no Eixo
TRC|07|TRC_NFOGO1|C|10|0|Num Fogo 1|Numero de fogo do pneu 1
TRC|08|TRC_LOCPN1|C|6|0|Local Pneu 1|Local Pneu 1
TRC|09|TRC_PN1M1|N|6|2|1 Med Pneu 1|1a Medida do sulco Pneu 1
TRC|10|TRC_PN1M2|N|6|2|2 Med Pneu 1|2a Medida do sulco Pneu 1
TRC|11|TRC_PN1M3|N|6|2|3 Med Pneu 1|3a Medida do sulco Pneu 1
TRC|12|TRC_NFOGO2|C|10|0|Num Fogo 2|Numero de fogo do pneu 2
TRC|13|TRC_LOCPN2|C|6|0|Local Pneu 2|Local Pneu 2
TRC|14|TRC_PN2M1|N|6|2|1 Med Pneu 2|1a Medida do sulco Pneu 2
TRC|15|TRC_PN2M2|N|6|2|2 Med Pneu 2|2a Medida do sulco Pneu 2
TRC|16|TRC_PN2M3|N|6|2|3 Med Pneu 2|3a Medida do sulco Pneu 2
TRC|17|TRC_NFOGO3|C|10|0|Num Fogo 3|Numero de fogo do pneu 3
TRC|18|TRC_LOCPN3|C|6|0|Local Pneu 3|Local Pneu 3
TRC|19|TRC_PN3M1|N|6|2|1 Med Pneu 3|1a Medida do sulco Pneu 3
TRC|20|TRC_PN3M2|N|6|2|2 Med Pneu 3|2a Medida do sulco Pneu 3
TRC|21|TRC_PN3M3|N|6|2|3 Med Pneu 3|3a Medida do sulco Pneu 3
TRC|22|TRC_NFOGO4|C|10|0|Num Fogo 4|Numero de fogo do pneu 4
TRC|23|TRC_LOCPN4|C|6|0|Local Pneu 4|Local Pneu 4
TRC|24|TRC_PN4M1|N|6|2|1 Med Pneu 4|1a Medida do sulco Pneu 4
TRC|25|TRC_PN4M2|N|6|2|2 Med Pneu 4|2a Medida do sulco Pneu 4
TRC|26|TRC_PN4M3|N|6|2|3 Med Pneu 4|3a Medida do sulco Pneu 4
TRC|27|TRC_NFOGO5|C|10|0|Num Fogo 5|Numero de fogo do pneu 5
TRC|28|TRC_LOCPN5|C|6|0|Local Pneu 5|Local Pneu 5
TRC|29|TRC_PN5M1|N|6|2|1 Med Pneu 5|1a Medida do sulco Pneu 5
TRC|30|TRC_PN5M2|N|6|2|2 Med Pneu 5|2a Medida do sulco Pneu 5
TRC|31|TRC_PN5M3|N|6|2|3 Med Pneu 5|3a Medida do sulco Pneu 5
TRC|32|TRC_NFOGO6|C|10|0|Num Fogo 6|Numero de fogo do pneu 6
TRC|33|TRC_LOCPN6|C|6|0|Local Pneu 6|Local Pneu 6
TRC|34|TRC_PN6M1|N|6|2|1 Med Pneu 6|1a Medida do sulco Pneu 6
TRC|35|TRC_PN6M2|N|6|2|2 Med Pneu 6|2a Medida do sulco Pneu 6
TRC|36|TRC_PN6M3|N|6|2|3 Med Pneu 6|3a Medida do sulco Pneu 6
TRC|37|TRC_NFOGO7|C|10|0|Num Fogo 7|Numero de fogo do pneu 7
TRC|38|TRC_LOCPN7|C|6|0|Local Pneu 7|Local Pneu 7
TRC|39|TRC_PN7M1|N|6|2|1 Med Pneu 7|1a Medida do sulco Pneu 7
TRC|40|TRC_PN7M2|N|6|2|2 Med Pneu 7|2a Medida do sulco Pneu 7
TRC|41|TRC_PN7M3|N|6|2|3 Med Pneu 7|3a Medida do sulco Pneu 7
TRC|42|TRC_NFOGO8|C|10|0|Num Fogo 8|Numero de fogo do pneu 8
TRC|43|TRC_LOCPN8|C|6|0|Local Pneu 8|Local Pneu 8
TRC|44|TRC_PN8M1|N|6|2|1 Med Pneu 8|1a Medida do sulco Pneu 8
TRC|45|TRC_PN8M2|N|6|2|2 Med Pneu 8|2a Medida do sulco Pneu 8
TRC|46|TRC_PN8M3|N|6|2|3 Med Pneu 8|3a Medida do sulco Pneu 8
TRC|47|TRC_NFOGO9|C|10|0|Num Fogo 9|Numero de fogo do pneu 9
TRC|48|TRC_LOCPN9|C|6|0|Local Pneu 9|Local Pneu 9
TRC|49|TRC_PN9M1|N|6|2|1 Med Pneu 9|1a Medida do sulco Pneu 9
TRC|50|TRC_PN9M2|N|6|2|2 Med Pneu 9|2a Medida do sulco Pneu 9
TRC|51|TRC_PN9M3|N|6|2|3 Med Pneu 9|3a Medida do sulco Pneu 9
TRC|52|TRC_NFOG10|C|10|0|Num Fogo 10|Numero de fogo do pneu 10
TRC|53|TRC_LOCP10|C|6|0|Local Pneu10|Local Pneu 10
TRC|54|TRC_PN10M1|N|6|2|1 Med Pneu10|1a Medida sulco Pneu 10
TRC|55|TRC_PN10M2|N|6|2|2 Med Pneu10|2a Medida do sulco Pneu 1
TRC|56|TRC_PN10M3|N|6|2|3 Med Pneu10|3a Medida do sulco Pneu 1
--- ### TRF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRF|01|TRF_FILIAL|C|6|0|Filial|Filial do Sistema
TRF|02|TRF_NUMENV|C|6|0|Numero Envio|Numero Envio da Carcaca
TRF|03|TRF_DTENVI|D|8|0|Data Envio|Data de Envio da Carcaca
TRF|04|TRF_HRENVI|C|5|0|Hora Envio|Hora de Envio da Carcaca
TRF|05|TRF_QTDENV|N|4|0|Qtde Enviada|Quantidade Pneus Enviada
TRF|06|TRF_QTDREC|N|4|0|Qtde Receb.|Qtde Sucatas Recebidas
TRF|07|TRF_DTREC|D|8|0|Data Receb.|Data Recebimento Carcacas
TRF|08|TRF_HRREC|C|5|0|Hora Receb.|Hora Recebimento Carcacas
TRF|09|TRF_CCUSTO|C|9|0|C.C. Destino|Centro de Custo Destino
TRF|10|TRF_NOMCUS|C|40|0|Nome C.Custo|Nome do Centro de Custo
--- ### TRG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRG|01|TRG_FILIAL|C|6|0|Filial|Filial do Sistema
TRG|02|TRG_NUMENV|C|6|0|Numero Envio|Numero Envio da Carcaca
TRG|03|TRG_CODBEM|C|16|0|Codigo Pneu|Codigo do Pneu
TRG|04|TRG_NOME|C|40|0|Nome do Pneu|Nome do Pneu
TRG|05|TRG_DESENH|C|10|0|Desenho|Desenho do Pneu
TRG|06|TRG_MEDIDA|C|6|0|Medida|Medida do Pneu
TRG|07|TRG_DESMED|C|20|0|Desc. Medida|Descricao do Pneu
TRG|08|TRG_TIPMOD|C|10|0|Tipo Modelo|Tipo do Modelo do Pneu
TRG|09|TRG_DESMOD|C|20|0|Desc. Modelo|Descricao do Modelo
--- ### TRH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRH|01|TRH_FILIAL|C|6|0|Filial|Filial do Sistema
TRH|02|TRH_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRH|03|TRH_DTACID|D|8|0|Dt. Sinistro|Data do Sinistro
TRH|04|TRH_HRACID|C|5|0|Hr. Acidente|Hora do Acidente
TRH|05|TRH_EVENTO|C|1|0|Evento Sin.|Evento Sinistro
TRH|06|TRH_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TRH|07|TRH_NOMBEM|C|30|0|Nome do Bem|Nome do Bem
TRH|08|TRH_OCORRE|C|4|0|Ocorrencia|Codigo da Ocorrencia
TRH|09|TRH_DESOCO|C|30|0|Des. Ocorre.|Descricao da Ocorrencia
TRH|10|TRH_TIPACI|C|2|0|Tipo Evento|Tipo de Evento
TRH|11|TRH_DESTIP|C|20|0|Des. Tp Eve.|Descricao do Tipo de Even
TRH|12|TRH_CAUPRE|C|2|0|Causa Preli.|Causa Premilinar Acidente
TRH|13|TRH_DESCAU|C|20|0|Des. Causa|Descricao Causa Prel. Aci
TRH|14|TRH_PLACA|C|8|0|Placa do Bem|Placa do Bem
TRH|15|TRH_GRAVID|C|1|0|Gravidade|Gravidade
TRH|16|TRH_NUMBO|C|10|0|Numero do BO|Numero Boletim Ocorrencia
TRH|17|TRH_NOMDP|C|40|0|Nome do DP|Nome Departamento Policia
TRH|18|TRH_TEMPO|C|1|0|Cond. Tempo|Condicoes do Tempo
TRH|19|TRH_VIA|C|1|0|Tracado Via|Tracado da Via
TRH|20|TRH_PERIOD|C|1|0|Periodo Dia|Periodo do Dia
TRH|21|TRH_VIADIR|C|1|0|Mao Direcao|Mao Direcao
TRH|22|TRH_LOCAL|C|60|0|Local Acid.|Local Exato do Acidente
TRH|23|TRH_CIDACI|C|40|0|Cidade Acid.|Cidade do Acidente
TRH|24|TRH_UFACID|C|2|0|UF Acidente|UF do Acidente
TRH|25|TRH_VELOC|N|4|0|Veloc. Acid.|Velocidade do Acidente
TRH|26|TRH_KMACID|N|6|0|Km Acidente|Km Acidente
TRH|27|TRH_VELPER|N|4|0|Veloc. Perm.|Velocidade Permitida
TRH|28|TRH_INTERR|C|1|0|Int. Viagem?|Interrupcao da Viagem?
TRH|29|TRH_GUINCH|C|1|0|Nec Guincho?|Necessidade de Guincho?
TRH|30|TRH_VALGUI|N|14|2|Val. Guincho|Valor do Guincho
TRH|31|TRH_VEIROU|C|1|0|Veic. Roub.?|Veiculo Roubado?
TRH|32|TRH_RECVEL|C|1|0|Veic. Recup?|Veiculo Recuperado?
TRH|33|TRH_SEQUES|C|1|0|Mot Sequest?|Motorista Sequestrado?
TRH|34|TRH_MOTLIB|C|1|0|Mot. Libera?|Motorista Liberado?
TRH|35|TRH_CONDEL|C|1|0|Delito Con.?|Roubo/Furto/Assalto Con.?
TRH|36|TRH_STATUS|C|2|0|Status Proc.|Status do Processo
TRH|37|TRH_NOMPRO|C|40|0|Prop. Animal|Proprietario dos Animais
TRH|38|TRH_ENDPRO|C|40|0|End. Propr.|End. Proprietario Animal
TRH|39|TRH_CIDPRO|C|20|0|Cidade Prop.|Cidade do Proprietario
TRH|40|TRH_UFPRO|C|2|0|Estado Prop.|Estado Proprietar. Animal
TRH|41|TRH_TELPRO|C|15|0|Tel. Prop.|Tel Proprietario Animais
TRH|42|TRH_TIPANI|C|20|0|Tipo Animal|Tipo de Animal
TRH|43|TRH_QTDANI|N|2|0|Qtd. Animais|Quantidade de Animais
TRH|44|TRH_VALANI|N|14|2|Valor Animal|Valor Despesa Animais
TRH|45|TRH_DESCRI|M|80|0|Desc. Acid.|Descricao do Acidente
TRH|46|TRH_FLGDAN|C|1|0|Danos Frota?|Indica se houve danos
TRH|47|TRH_VALDAN|N|12|2|Valor Danos|Valor dos Danos
TRH|48|TRH_DANOS|C|40|0|Desc. Danos|Descricao Danos Veiculo
TRH|49|TRH_DANOS2|M|80|0|Desc. Danos|Descricao Danos Veiculo
TRH|50|TRH_TEREVA|C|1|0|Ter. Evadiu?|Terceiro Evadiu do Local?
TRH|51|TRH_FLGCOM|C|1|0|Completado?|Sinistro foi completado?
TRH|52|TRH_DTDIG|D|8|0|Dt Digitacao|Data de Digitacao
TRH|53|TRH_HRDIG|C|5|0|Hr Digitacao|Hora da Digitacao
TRH|54|TRH_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
TRH|55|TRH_ORDEM|C|6|0|Ordem Serv.|Numero da Ordem Servico
TRH|56|TRH_MMDAN2|C|6|0|ChaveMM SYP|Chave Memo SYP
--- ### TRI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRI|01|TRI_FILIAL|C|6|0|Filial|Filial do Sistema
TRI|02|TRI_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRI|03|TRI_CODBEM|C|16|0|Bem|Codigo do Bem
TRI|04|TRI_NOMBEM|C|30|0|Nome do Bem|Nome do Bem
TRI|05|TRI_CODDOC|C|6|0|Documento|Codigo do Documento
TRI|06|TRI_NOMDOC|C|30|0|Nome Doc.|Nome do Documento
TRI|07|TRI_DTREC|D|8|0|Data Receb.|Data de Recebimento
TRI|08|TRI_HRREC|C|5|0|Hora Receb.|Hora do Recebimento
--- ### TRJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRJ|01|TRJ_FILIAL|C|6|0|Filial|Filial do Sistema
TRJ|02|TRJ_NUMINQ|C|9|0|Inquerito|Numero do Inquerito
TRJ|03|TRJ_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRJ|04|TRJ_DTENJU|D|8|0|Dt. Env. Jur|Data Envio ao Juridico
TRJ|05|TRJ_DTREJU|D|8|0|Dt. Rec. Jur|Data Receb. do Juridico
TRJ|06|TRJ_TETOJU|N|5|0|Tem. Tot. Ju|Tempo Total do Juridico
TRJ|07|TRJ_CAUJUR|C|2|0|Causa Acid.|Causa do Acidente
TRJ|08|TRJ_DESCAU|C|30|0|Desc. Causa|Descricao Causa Acidente
TRJ|09|TRJ_CULAPU|C|2|0|Culpa Apur.|Culpa Apurada
TRJ|10|TRJ_DESCUL|C|40|0|Desc. Culpa|Descricao da Culpa
TRJ|11|TRJ_PASTA|C|6|0|Numero Pasta|Numero da Pasta Suspensa
TRJ|12|TRJ_PROCES|C|10|0|Num Processo|Numero Processo Juridico
TRJ|13|TRJ_DTFIPR|D|8|0|Dt. Enc. Pro|Data Final do Processo
TRJ|14|TRJ_OBS|C|80|0|Observacoes|Observacoes
TRJ|15|TRJ_DTENMA|D|8|0|Dt. Env. Man|Data Envio Manutencao
TRJ|16|TRJ_DTREMA|D|8|0|Dt. Rec. Man|Data Recebim. Manutencao
TRJ|17|TRJ_TETOMA|N|5|0|Tem. Tot. Ma|Tempo Total Manutencao
TRJ|18|TRJ_TETOPR|N|5|0|Tem. Tot Pro|Tempo Total do Processo
TRJ|19|TRJ_ACOES|C|50|0|Acoes Tomada|Acoes Tomada
TRJ|20|TRJ_PARECE|M|10|0|Parecer Jur.|Parecer Juridico
--- ### TRK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRK|01|TRK_FILIAL|C|6|0|Filial|Filial do Sistema
TRK|02|TRK_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRK|03|TRK_SEQCAR|C|3|0|Sequencia|Sequencial Env. Sinistro
TRK|04|TRK_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TRK|05|TRK_DESBEM|C|20|0|Descricao|Descricao do Bem
TRK|06|TRK_CODCAR|C|6|0|Codigo Carga|Codigo da Carga
TRK|07|TRK_VALCAR|N|14|2|Vl. Faturado|Valor Faturado da Carga
TRK|08|TRK_VALAVA|N|14|2|Preju. Carga|Prejuizo da Carga
TRK|09|TRK_VALREC|N|14|2|Vl. Recuper.|Valor Recuperado
--- ### TRL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRL|01|TRL_FILIAL|C|6|0|Filial|Filial do Sistema
TRL|02|TRL_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRL|03|TRL_SEQIMO|C|3|0|Num. Seq.|Num. Seq Imoveis/Sinistro
TRL|04|TRL_TIPIMO|C|1|0|Tipo Imovel|Tipo do Imovel
TRL|05|TRL_DESIMO|C|40|0|Desc. Imovel|Descricao Imovel Acident.
TRL|06|TRL_DANOS|C|1|0|Danos Imovel|Danos do Imovel
TRL|07|TRL_VALPRE|N|14|2|Vl. Prejuizo|Valor do Prejuizo
TRL|08|TRL_NOMPRO|C|40|0|Proprietario|Nome do Proprietario
TRL|09|TRL_TELPRO|C|15|0|Telefone|Telefone do Proprietario
TRL|10|TRL_ENDPRO|C|40|0|Endereco|Endereco do Proprietario
TRL|11|TRL_CODPRO|C|20|0|Cidade|Cidade do Proprietario
TRL|12|TRL_UF|C|2|0|Estado|Estado do Proprietario
TRL|13|TRL_DESCRI|M|10|0|Desc. Danos|Descricao Danos Sofridos
TRL|14|TRL_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
--- ### TRM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRM|01|TRM_FILIAL|C|6|0|Filial|Filial do Sistema
TRM|02|TRM_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRM|03|TRM_SEQVIT|C|3|0|Seq. Vitima|Seq. Vitimas por Sinistro
TRM|04|TRM_INDFUN|C|1|0|Funcionario?|Funcionario da Empresa?
TRM|05|TRM_MATVIT|C|6|0|Cod. Vitima|Codigo da Vitima
TRM|06|TRM_NOMVIT|C|40|0|Nome Vitima|Nome da Vitima
TRM|07|TRM_TELVIT|C|15|0|Telefone|Telefone da Vitima
TRM|08|TRM_ENDVIT|C|40|0|Endereco|Endereco da Vitima
TRM|09|TRM_CIDVIT|C|20|0|Cidade|Cidade da Vitima
TRM|10|TRM_UFVIT|C|2|0|Estado|Estado da Vitima
TRM|11|TRM_LESOES|C|80|0|Desc. Lesoes|Descricao das Lesoes
TRM|12|TRM_ACAO|C|80|0|Acao Tomada|Acao Tomada
TRM|13|TRM_DESFUN|C|40|0|Funcao|Descricao da Funcao
TRM|14|TRM_FATAL|C|1|0|Vitima Fatal|Vitima Fatal?
TRM|15|TRM_CODVIT|C|1|0|Cond. Vitima|Condicao da Vitima
TRM|16|TRM_VALVIT|N|14|2|Valor Vitima|Valor Gasto com a Vitima
--- ### TRN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRN|01|TRN_FILIAL|C|6|0|Filial|Filial do Sistema
TRN|02|TRN_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRN|03|TRN_SEQTES|C|3|0|Seq.Testem.|Seq.Testemunha Sinistro
TRN|04|TRN_NOMTES|C|40|0|Testemunha|Nome da Testemunha
TRN|05|TRN_TELTES|C|15|0|Fone Testem.|Telefone da Testemunha
TRN|06|TRN_ENDTES|C|40|0|Endereco|Endereco da Testemunha
TRN|07|TRN_CIDTES|C|20|0|Cidade|Cidade da Testemunha
TRN|08|TRN_UFTES|C|2|0|Estado|Estado da Testemunha
TRN|09|TRN_TIPDOC|C|1|0|Tipo Docto.|Tipo do Documento
TRN|10|TRN_DOCTO|C|15|0|Documento|Documento da Testemunha
TRN|11|TRN_QLFTES|C|15|0|Qualificacao|Qualificacao Testemunha
--- ### TRO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRO|01|TRO_FILIAL|C|6|0|Filial|Filial do Sistema
TRO|02|TRO_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRO|03|TRO_SEQVEI|C|3|0|Seq.Veiculo|Sequencial Veiculos Sinis
TRO|04|TRO_PLACA|C|8|0|Placa|Placa
TRO|05|TRO_TIPVEI|C|1|0|Tipo Veiculo|Tipo Veiculo
TRO|06|TRO_DESVEI|C|40|0|Veiculo|Descricao do Veiculo
TRO|07|TRO_MOTVEI|C|40|0|Condutor|Nome Motorista
TRO|08|TRO_TELMOT|C|15|0|Fone|Telefone Motorista
TRO|09|TRO_ENDMOR|C|40|0|Endereco|Endereco do Motorista
TRO|10|TRO_CIDMOT|C|20|0|Cidade|Cidade do Motorista
TRO|11|TRO_UFMOT|C|2|0|UF Condutor|UF Motorista
TRO|12|TRO_CNHMOT|C|15|0|CNH Condutor|CNH do Motorista
TRO|13|TRO_DTVALC|D|8|0|Validade CNH|Validade CNH do Condutor
TRO|14|TRO_SSPMOT|C|6|0|Orgao Emiss.|Orgao Emissor Motorista
TRO|15|TRO_UFCNH|C|2|0|UF da CNH|UF da CNH
TRO|16|TRO_RG|C|15|0|RG|Registro de Identidade
TRO|17|TRO_RGORG|C|6|0|Org. Emissor|Orgao Emissor RG
TRO|18|TRO_UFREG|C|2|0|UF do RG|UF Emissao do RG
TRO|19|TRO_CPF|C|14|0|CPF Condutor|CPF Motorista
TRO|20|TRO_DANOS|C|1|0|Danos ?|Danos no Veiculo ?
TRO|21|TRO_VALPRE|N|12|2|Vlr.Prejuizo|Valor do Prejuizo
TRO|22|TRO_NOMPR|C|40|0|Proprietario|Nome Proprietario Veiculo
TRO|23|TRO_TELPRO|C|15|0|Fone Propr.|Fone Proprietario Veiculo
TRO|24|TRO_ENDPRO|C|40|0|End. Propr.|Endereco do Proprietario
TRO|25|TRO_CIDPRO|C|20|0|Cidade Prop.|Cidade do Proprietario
TRO|26|TRO_UFPRO|C|2|0|UF Propriet.|UF Proprietario
TRO|27|TRO_SEGUR|C|1|0|Segurado ?|Veiculo Segurado ?
TRO|28|TRO_SEGCOR|C|40|0|Seguradora|Nome da Seguradora
TRO|29|TRO_APOLIC|C|20|0|Nº Apolice|Numero da Apolice
TRO|30|TRO_TELSEG|C|15|0|Fone Seguro|Telefone da Seguradora
TRO|31|TRO_RENAVA|C|15|0|Cod. Renavam|Codigo Renavam
TRO|32|TRO_DESC|M|10|0|Desc.Danos|Descricao dos Danos
TRO|33|TRO_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
TRO|34|TRO_VALTER|N|12|2|Val Pag Ter.|Valor Pago a Terceiros
TRO|35|TRO_PERCEN|N|8|2|% de Ganho|Percentagem de Ganho
--- ### TRP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRP|01|TRP_FILIAL|C|6|0|Filial|Filial do Sistema
TRP|02|TRP_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRP|03|TRP_DTOCOR|D|8|0|Data Ocor.|Data de Ocorrencia
TRP|04|TRP_HROCOR|C|5|0|Hora Ocor.|Hora de Ocorrencia
TRP|05|TRP_STATUS|C|2|0|Status|Codigo Status do Sinistro
TRP|06|TRP_CODUSU|C|15|0|Usuario|Login do Usuario
--- ### TRQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRQ|01|TRQ_FILIAL|C|6|0|Filial|Filial do Sistema
TRQ|02|TRQ_ACAO|C|6|0|Acao|Codigo da Acao
TRQ|03|TRQ_DESACA|C|40|0|Descricao|Descricao da Acao
--- ### TRR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRR|01|TRR_FILIAL|C|6|0|Filial|Filial do Sistema
TRR|02|TRR_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRR|03|TRR_DTOCOR|D|8|0|Dt. Acao|Data da Acao
TRR|04|TRR_HROCOR|C|5|0|Hr. Acao|Hora da Acao
TRR|05|TRR_ACAO|C|6|0|Cod. Acao|Codigo da Acao
TRR|06|TRR_DESACA|C|20|0|Desc. Acao|Descricao da Acao
TRR|07|TRR_CODUSU|C|15|0|Usuario|Usuario
--- ### TRS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRS|01|TRS_FILIAL|C|6|0|Filial|Filial do Sistema
TRS|02|TRS_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRS|03|TRS_DTABER|D|8|0|Dt. Abertura|Data Abertura
TRS|04|TRS_NUMAPD|C|10|0|Numero APD|Numero APD
TRS|05|TRS_MATRES|C|6|0|Responsavel|Responsavel
TRS|06|TRS_NOMRES|C|20|0|Nome Resp.|Nome Responsavel
TRS|07|TRS_VALAPD|N|12|2|Valor APD|Valor APD
TRS|08|TRS_DTCONC|D|8|0|Dt.Conclusao|Data de Conclusao APD
TRS|09|TRS_STAPD|C|1|0|Status APD|Status da APD
TRS|10|TRS_TIPAPD|C|80|0|Tipo APD|Descricao do Tipo do APD
--- ### TRT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRT|01|TRT_FILIAL|C|6|0|Filial|Filial do Sistema
TRT|02|TRT_NUMOS|C|6|0|Numero O.S.|Numero da O.S.
TRT|03|TRT_PLANO|C|6|0|Plano|Plano de Manutencao
TRT|04|TRT_NUMSIN|C|6|0|Sinistro|Numero do Sinistro
TRT|05|TRT_PARECE|M|80|0|Parecer|Parecer
TRT|06|TRT_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
--- ### TRU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRU|01|TRU_FILIAL|C|6|0|Filial|Filial do Sistema
TRU|02|TRU_CODDOC|C|6|0|Documento|Codigo do Documento
TRU|03|TRU_NOMDOC|C|40|0|Nome|Nome do Documento
TRU|04|TRU_TIPEVE|C|1|0|Evento Doc.|Codigo Evento Documento
--- ### TRV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRV|01|TRV_FILIAL|C|6|0|Filial|Filial do Sistema
TRV|02|TRV_NUMSIN|C|6|0|Num Sinistro|Numero do Sinistro
TRV|03|TRV_CAUREA|C|2|0|Causa Real|Causa Real
TRV|04|TRV_RASTRE|C|1|0|Frota Rast.?|Frota Rastreada?
TRV|05|TRV_TIPRAS|C|1|0|Tp Rastream.|Tipo de Rastreamento
TRV|06|TRV_CODVIA|C|6|0|Viagem|Codigo da Viagem
TRV|07|TRV_CODMOT|C|6|0|Motorista|Codigo do Motorista
TRV|08|TRV_NOMMOT|C|40|0|Nome Motor.|Nome do Motorista
TRV|09|TRV_TIPCAR|C|3|0|Tipo Carga|Tipo Carga
TRV|10|TRV_FILORI|C|6|0|Fil. Origem|Filial Origem
TRV|11|TRV_CIDORI|C|40|0|Cidade Orig.|Cidade de Origem
TRV|12|TRV_UFORI|C|2|0|UF Origem|UF de Origem
TRV|13|TRV_FILDES|C|6|0|Fil. Destino|Filial Destino
TRV|14|TRV_CIDDES|C|40|0|Cidade Dest.|Cidade de Destino
TRV|15|TRV_UFDES|C|2|0|UF Destino|UF de Destino
TRV|16|TRV_HRDIRI|C|6|0|Horas Dirig.|Horas Dirigidas ate Acid.
TRV|17|TRV_KMPERC|N|6|0|Kms Percor.|Kms Percorridos Acidente
TRV|18|TRV_RECCAR|C|1|0|Carga Recup?|Carga Recuperada?
TRV|19|TRV_DTRESS|D|8|0|Dt. Ressarc.|Data do Ressarcimento
TRV|20|TRV_VALRES|N|14|2|Val. Ressar.|Valor Ressarcido
TRV|21|TRV_LAUEMP|C|1|0|Laudo Peri.?|Laudo Pericial?
TRV|22|TRV_DESEVI|C|80|0|Como Evitar?|Como poderia evitar?
TRV|23|TRV_RESABE|C|6|0|Responsavel|Matricula do Responsavel
TRV|24|TRV_NOMRES|C|30|0|Nome Resp.|Nome do Responsavel
TRV|25|TRV_DESPAR|C|80|0|Parecer Sup.|Parecer do Superior
TRV|26|TRV_MATGER|C|6|0|Gerente|Matricula do Gerente
TRV|27|TRV_NOMGER|C|30|0|Nome Gerente|Nome do Gerente
TRV|28|TRV_DESGER|C|80|0|Parecer Ger.|Parecer do Gerente
TRV|29|TRV_BITMAP|C|8|0|Imagem|Imagem do Sinistro
TRV|30|TRV_COMLOC|C|1|0|Compareceu?|Compareceu ao Local?
TRV|31|TRV_ABEAPD|C|1|0|Abre APD?|Indica Abertura de APD
TRV|32|TRV_NUMAPD|C|10|0|Numero APD|Numero da APD
TRV|33|TRV_STAPD|C|1|0|Status APD|Status da APD
--- ### TRX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRX|01|TRX_FILIAL|C|6|0|Filial|Filial do Sistema
TRX|02|TRX_MULTA|C|18|0|Multa|Codigo da Multa
TRX|03|TRX_TPMULT|C|20|0|Tipo Multa|Tipo de Multa
TRX|04|TRX_DTINFR|D|8|0|Dta Infracao|Data da Infracao
TRX|05|TRX_RHINFR|C|5|0|Hra Infracao|Hora da Infracao
TRX|06|TRX_DTREC|D|8|0|Dta Recebime|Data do Recebimento
TRX|07|TRX_NUMAIT|C|14|0|Nro Infracao|Numero da Infracao
TRX|08|TRX_CODINF|C|8|0|Infracao|Codigo da Infracao
TRX|09|TRX_ARTIGO|C|30|0|Artigo|Codigo do Artigo
TRX|10|TRX_DESART|C|80|0|Descricao|Descricao do Artigo
TRX|11|TRX_PONTUA|C|1|0|Pontuacao|Pontuacao da Infracao
TRX|12|TRX_RODOVI|C|6|0|Rodovia|Rodovia
TRX|13|TRX_NOMROD|C|40|0|Nome Rodov.|Nome da Rodovia
TRX|14|TRX_LOCAL|C|240|0|Local Infrac|Local exato da Infracao
TRX|15|TRX_CIDINF|C|40|0|Cidade|Cidade Ocorreu a Infracao
TRX|16|TRX_UFINF|C|2|0|Uf Infracao|UF da Infracao
TRX|17|TRX_CODOR|C|6|0|Orgao Autuad|Codigo do Orgao autuado
TRX|18|TRX_NOMOR|C|40|0|Descricao|Descricao do Orgao
TRX|19|TRX_PLACA|C|8|0|Placa Veicu.|Placa do Veiculo
TRX|20|TRX_CODBEM|C|16|0|Veiculo|Codigo do Veiculo
TRX|21|TRX_OPERAC|C|1|0|Operacao|Codigo da Operacao
TRX|22|TRX_RENAVA|C|15|0|Renavam|Renavam do Veiculo
TRX|23|TRX_CODMO|C|6|0|Motorista|Codigo do Motorista
TRX|24|TRX_NOME|C|40|0|Nome Motoris|Nome do Motorista
TRX|25|TRX_FILMOT|C|6|0|Filial Mot.|Filial do Motorista
TRX|26|TRX_REPON|C|1|0|Responsabili|Indicad. Responsabilidade
TRX|27|TRX_PAGTO|C|1|0|Pagamento?|Houve o Pagamento?
TRX|28|TRX_DTVECI|D|8|0|Dt. Vencto.|Data de vencimento Multa
TRX|29|TRX_VALOR|N|12|2|Valor Multa|Valor da Multa
TRX|30|TRX_DESCON|N|12|2|Valor Desc.|Valor do Desconto
TRX|31|TRX_DTPGTO|D|8|0|Dt. Pgto.|Data de Pgamento da Multa
TRX|32|TRX_PCTDSC|N|6|2|% Desconto|% Desconto
TRX|33|TRX_VALPAG|N|12|2|Valor Pago|Valor Pago
TRX|34|TRX_DTEMIS|D|8|0|Dt. Emissao|Data de Emissao
TRX|35|TRX_NUMSP|C|15|0|Nro S. Paga.|Numero Solicitacao Pagam.
TRX|36|TRX_CODAC|C|6|0|Codigo Acao|Codigo da Acao
TRX|37|TRX_DESACA|C|40|0|Descri. Acao|Descricao da Acao
TRX|38|TRX_INFRAC|C|1|0|Ind Condutor|Indica Condutor p/ Orgao
TRX|39|TRX_DTIND|D|8|0|Data Ind.|Data Indicacao Condutor
TRX|40|TRX_DTNAR|D|8|0|Dt. Aviso|Data Envio Aviso Pontos
TRX|41|TRX_NUMAR|C|20|0|Documento|Docto Correio Aviso Ptos
TRX|42|TRX_STATUS|C|1|0|Status Multa|Status Porecesso da Multa
TRX|43|TRX_RECURS|C|1|0|Tem Recurso?|Indica se possui Recurso
TRX|44|TRX_INDREC|C|1|0|Recurso|Tipo do Recurso
TRX|45|TRX_DTENRE|D|8|0|Entr Recurso|Data Entrega do Recurso
TRX|46|TRX_NUMCI|C|10|0|Nro CI Recur|Numero da CI do Recurso
TRX|47|TRX_MOTREC|C|6|0|Motivo Recur|Motivo do Recurso
TRX|48|TRX_DESMOT|C|30|0|Desc. Motivo|Descricao do Motivo
TRX|49|TRX_SITREC|C|1|0|Sit. Recurso|Situacao do Recurso
TRX|50|TRX_DTFIRE|D|8|0|Dt. Fim Rec.|Data Fim do Recurso
TRX|51|TRX_SEGINS|C|1|0|Segunda In.?|Segunda Instancia Recurso
TRX|52|TRX_DTENR2|D|8|0|Entr Rec. 2|Data Entrega do Recurso 2
TRX|53|TRX_NUMCI2|C|10|0|Nro CI Rec 2|Numero da CI do Recurso 2
TRX|54|TRX_MOTRE2|C|6|0|Motivo Rec 2|Motivo do Recurso 2
TRX|55|TRX_SITRE2|C|1|0|Sit. Rec. 2|Situacao do Recurso 2
TRX|56|TRX_DTFIR2|D|8|0|Dt. Fim Rec2|Data Fim do Recurso 2
TRX|57|TRX_ORIGEM|C|1|0|Origem Multa|Origem da Multa
TRX|58|TRX_RECAUT|C|1|0|Rec Auto Inf|Recebeu Auto da Infracao
TRX|59|TRX_RECNOT|C|1|0|Rec Notifica|Recebeu Notificacao
TRX|60|TRX_NOTDT|D|8|0|Dt Notifica.|Data da Notificacao
TRX|61|TRX_DTDIGI|D|8|0|Dt Digitacao|Data da Digitacao
TRX|62|TRX_HRDIGI|C|5|0|Hr Digitacao|Hora da Digitacao
TRX|63|TRX_USUDIG|C|15|0|Usuario Dig.|Usuario da Digitacao
TRX|64|TRX_NF|C|9|0|Nota Fiscal|Numero da Nota Fiscal
TRX|65|TRX_DATADV|D|8|0|Dt. Advert.|Data de Advertencia
TRX|66|TRX_CABREC|C|1|0|Cabe Rec.?|Cabe Recurso?
TRX|67|TRX_RESTIT|C|1|0|Restituicao|Solicitacao Restituicao
TRX|68|TRX_OBS|M|80|0|Observacao|Observacoes
TRX|69|TRX_OBPAGA|M|80|0|Observacao|Observacoes do Pagamento
TRX|70|TRX_OBCOND|M|80|0|Observacao|Observacoes do Condutor
TRX|71|TRX_OBRECU|M|80|0|Observacao|Observacoes do Recurso
TRX|72|TRX_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TRX|73|TRX_NOMCUS|C|30|0|Nome C.Custo|Nome do Centro de Custo
TRX|74|TRX_ADVERT|C|1|0|Ger. Advert?|Gerar Advertencia ?
TRX|75|TRX_NUMAPD|C|10|0|N. da APD|Numero da APD
TRX|76|TRX_DTSOLI|D|8|0|Dt Solicit.|Data da Solicitacao
TRX|77|TRX_VLRSOL|N|9|2|Valor Restit|Valor da Restituicao
TRX|78|TRX_STSOL|C|1|0|Status|Status Solicitacao
TRX|79|TRX_DTEFET|D|8|0|Dt. Ef. Rest|Efetivacao Restituicao
TRX|80|TRX_OBREST|M|80|0|Observacao|Observacoes Restituicao
TRX|81|TRX_INDFOB|C|1|0|Viagem FOB?|Indica se a viagem e FOB
TRX|82|TRX_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
TRX|83|TRX_MMPAGA|C|6|0|ChaveMM SYP|Chave Memo SYP
TRX|84|TRX_MMCOND|C|6|0|ChaveMM SYP|Chave Memo SYP
TRX|85|TRX_MMRECU|C|6|0|ChaveMM SYP|Chave Memo SYP
TRX|86|TRX_MMREST|C|6|0|ChaveMM SYP|Chave Memo SYP
TRX|87|TRX_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
TRX|88|TRX_TIPO|C|3|0|Tipo|Tipo do Titulo
TRX|89|TRX_NUMSE2|C|9|0|No. Titulo|Numero do Titulo
TRX|90|TRX_NATURE|C|10|0|Natureza|Codigo da Natureza
TRX|91|TRX_CONPAG|C|3|0|Cond. Pagto|Codigo do Condicao
TRX|92|TRX_GRPVEN|C|6|0|Grupo Região|Grupo de Região
TRX|93|TRX_ITEMCT|C|9|0|Item Conta|Item da Conta Contabil
TRX|94|TRX_AS|C|27|0|Nr. A.S.|Nr. A.S.
TRX|95|TRX_PROJET|C|22|0|Nro.Projeto|Numero do projeto
TRX|96|TRX_FIC|C|20|0|Fic|Formulario Iden. Condutor
--- ### TRZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TRZ|01|TRZ_FILIAL|C|6|0|Filial|Filial do Sistema
TRZ|02|TRZ_CODOR|C|6|0|Orgao|Codigo do Orgao
TRZ|03|TRZ_NOMOR|C|40|0|Nome Orgao|Nome do Orgao
TRZ|04|TRZ_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TRZ|05|TRZ_LOJA|C|2|0|Loja|Loja do Fornecedor
TRZ|06|TRZ_NOMFOR|C|80|0|Nome Fornec.|Nome do Fornecedor
TRZ|07|TRZ_CONPAG|C|3|0|Cond. Pagto|Codigo da Condicao
--- ### TS0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS0|01|TS0_FILIAL|C|6|0|Filial|Filial do Sistema
TS0|02|TS0_DOCTO|C|6|0|Taxa|Codigo da Taxa
TS0|03|TS0_NOMDOC|C|40|0|Nome|Nome da Taxa
TS0|04|TS0_VALID|N|2|0|Validade|Validade da Taxa
TS0|05|TS0_UNIDAD|C|1|0|Unidade|Identifica a Unidade
TS0|06|TS0_AVIVEN|N|2|0|Dias Aviso|Dias Aviso Antes Vencim.
TS0|07|TS0_TIPO|C|3|0|Tipo|Tipo do Titulo
TS0|08|TS0_NATURE|C|10|0|Natureza|Codigo da Natureza
TS0|09|TS0_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
TS0|10|TS0_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TS0|11|TS0_LOJA|C|2|0|Loja|Loja do Fornecedor
TS0|12|TS0_NOMFOR|C|80|0|Nome Fornece|Nome do Fornecedor
TS0|13|TS0_CONPAG|C|3|0|Cond. Pagto|Codigo da Condicao
--- ### TS1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS1|01|TS1_FILIAL|C|6|0|Filial|Filial do Sistema
TS1|02|TS1_CODBEM|C|16|0|Codigo Bem|Codigo do Bem
TS1|03|TS1_PLACA|C|8|0|Placa|Placa do Veiculo
TS1|04|TS1_DOCTO|C|6|0|Documento|Codigo do Documento
TS1|05|TS1_DESDOC|C|40|0|Desc. Doc.|Descricao do Documento
TS1|06|TS1_VALOR|N|9|2|Valor|Valor do Documento
TS1|07|TS1_DTEMIS|D|8|0|Emissao|Data de Emissao
TS1|08|TS1_UFEMIS|C|2|0|U.F.|Estado do Documento
TS1|09|TS1_DTVENC|D|8|0|Vencimento|Data do Vencimento
TS1|10|TS1_QTDPAR|N|2|0|Parcelas|Quantidade de Parcelas
TS1|11|TS1_RENAVA|C|15|0|Renavam|Renavam
TS1|12|TS1_CHASSI|C|20|0|Chassi|Chassi do Veiculo
TS1|13|TS1_IDDOCT|C|12|0|Id. Docto.|Identificacao Documento
TS1|14|TS1_TIPO|C|3|0|Tipo|Tipo do Título
TS1|15|TS1_NATURE|C|10|0|Natureza|Codigo da Natureza
TS1|16|TS1_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
TS1|17|TS1_NUMSE2|C|9|0|No. Titulo|Numero do Titulo
TS1|18|TS1_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TS1|19|TS1_LOJA|C|2|0|Loja|Loja do Fornecedor
TS1|20|TS1_NOMFOR|C|80|0|Nome Fornece|Nome do Fornecedor
TS1|21|TS1_CONPAG|C|3|0|Cond. Pagto|Codigo da Condicao
TS1|22|TS1_VALPAG|N|9|2|Valor Pago|Valor Pago
TS1|23|TS1_DTVALI|D|8|0|Validade|Data Validade do Document
--- ### TS2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS2|01|TS2_FILIAL|C|6|0|Filial|Filial do Sistema
TS2|02|TS2_PLACA|C|8|0|Placa|Placa do Veiculo
TS2|03|TS2_CODBEM|C|16|0|Bem|Codigo do Bem
TS2|04|TS2_DOCTO|C|6|0|Documento|Codigo do Documento
TS2|05|TS2_DTPGTO|D|8|0|Data Pgto.|Data de Pagamento
TS2|06|TS2_DTVENC|D|8|0|Data Venc.|Data de Vencimento
TS2|07|TS2_DTEMIS|D|8|0|Emissao|Data de Emissao
TS2|08|TS2_UFEMIS|C|2|0|U.F.|Estado do Documento
TS2|09|TS2_PARCEL|C|3|0|Parcela|Numero da Parcela
TS2|10|TS2_VALOR|N|9|2|Valor|Valor do Documento
TS2|11|TS2_CCUSTO|C|9|0|C. Custo|Codigo do Centro de Custo
TS2|12|TS2_NOTFIS|C|9|0|Nota Fiscal|Número da Nota Fiscal
TS2|13|TS2_NUMSEQ|C|6|0|Numero Seq.|Numero Seq. Honorarios
TS2|14|TS2_VALPAG|N|9|2|Valor Pago|Valor Pago
--- ### TS3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS3|01|TS3_FILIAL|C|6|0|Filial|Filial do Sistema
TS3|02|TS3_CODBEM|C|16|0|Bem|Codigo do Bem
TS3|03|TS3_DESBEM|C|40|0|Desc. Bem|Descricao do Bem
TS3|04|TS3_PLACA|C|8|0|Placa|Placa do Veiculo
TS3|05|TS3_STATUS|C|1|0|Status|Status
TS3|06|TS3_DTIND|D|8|0|Dt. Ind. Bem|Data Indicacao do Bem
TS3|07|TS3_DTACAO|D|8|0|Dt. Ent Acao|Data Entrada da Acao
TS3|08|TS3_RECLAM|C|40|0|Nome Reclam.|Nome do Reclamante
TS3|09|TS3_ADVOG|C|40|0|Advogado|Nome do Advogado
TS3|10|TS3_PROCES|C|40|0|Processo|Processo
TS3|11|TS3_VALVEI|N|12|2|Valor Bem|Valor do Bem
TS3|12|TS3_TIPMAT|C|1|0|Tipo Acao|Tipo da Acao
TS3|13|TS3_DTLIB|D|8|0|Dt. Liberac.|Data da Liberacao
TS3|14|TS3_VALACA|N|12|2|Valor Acao|Valor da Acao
TS3|15|TS3_CDDESC|C|6|0|Cd Descricao|Cd Descricao da Penhora/L
TS3|16|TS3_DESCR|M|80|0|Descricao|Descricao da Penhora/Lib.
TS3|17|TS3_T9STAT|C|2|0|Status ST9|Historico do T9_STATUS
--- ### TS4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS4|01|TS4_FILIAL|C|6|0|Filial|Filial do Sistema
TS4|02|TS4_CODSDP|C|6|0|Codigo|Cod. Servico Despachante
TS4|03|TS4_DESCRI|C|40|0|Descricao|Desc. Servico Despachante
TS4|04|TS4_PAGHON|C|1|0|Pag. Honor.|Ind. Pagamento Honorario
--- ### TS5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS5|01|TS5_FILIAL|C|6|0|Filial|Filial do Sistema
TS5|02|TS5_CODFAM|C|6|0|Familia|Codigo da Familia
TS5|03|TS5_NOMFAM|C|30|0|Nome Familia|Nome da Familia
TS5|04|TS5_TIPMOD|C|10|0|Tipo Modelo|Codigo do Tipo de Modelo
TS5|05|TS5_NOMMOD|C|30|0|Nome Modelo|Nome do Tipo de Modelo
TS5|06|TS5_DOCTO|C|6|0|Taxa|Codigo da Taxa
TS5|07|TS5_NOMDOC|C|30|0|Nome Taxa|Descricao da Taxa
--- ### TS6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS6|01|TS6_FILIAL|C|6|0|Filial|Filial do Sistema
TS6|02|TS6_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TS6|03|TS6_LOJA|C|2|0|Loja|Loja
TS6|04|TS6_SERVIC|C|6|0|Servico|Codigo do Servico
TS6|05|TS6_DESERV|C|40|0|Descricao|Descricao do Servico
TS6|06|TS6_DOCTO|C|6|0|Ano|Ano do Servico
TS6|07|TS6_NOMDOC|C|40|0|Descricao|Descricao do Documento
TS6|08|TS6_VALOR|N|9|2|Valor|Valor do Documento
--- ### TS7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS7|01|TS7_FILIAL|C|6|0|Filial|Filial do Sistema
TS7|02|TS7_CODFAM|C|6|0|Familia|Codigo da Familia
TS7|03|TS7_TIPMOD|C|10|0|Tp Modelo|Codigo do Tipo de Modelo
TS7|04|TS7_DOCTO|C|6|0|Documento|Codigo do Documento
TS7|05|TS7_ANO|C|4|0|Ano|Ano
TS7|06|TS7_VALOR|N|9|2|Valor|Valor
--- ### TS8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TS8|01|TS8_FILIAL|C|6|0|Filial|Filial do Sistema
TS8|02|TS8_CODBEM|C|16|0|Bem|Codigo do Bem
TS8|03|TS8_PLACA|C|8|0|Placa|Placa do Veiculo
TS8|04|TS8_DOCTO|C|6|0|Documento|Codigo do Documento
TS8|05|TS8_DTPGTO|D|8|0|Data Pgto.|Data de Pagamento
TS8|06|TS8_PARCEL|C|3|0|Parcela|Numero da Parcela
TS8|07|TS8_VALOR|N|9|2|Valor|Valor do Documento
TS8|08|TS8_NOTFIS|C|9|0|Nota Fiscal|Número da Nota Fiscal
TS8|09|TS8_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TS8|10|TS8_LOJA|C|2|0|Loja|Loja
TS8|11|TS8_SERVIC|C|6|0|Servico|Servico
TS8|12|TS8_DTEMIS|D|8|0|Dt. Emissao|Data de Emissao
TS8|13|TS8_DTVENC|D|8|0|Vencimento|Data do Vencimento
TS8|14|TS8_NUMSEQ|C|6|0|Numero Seq.|Numero Seq. Honorarios
TS8|15|TS8_NUMSE2|C|9|0|No. Titulo|Numero do Titulo
TS8|16|TS8_VALPAG|N|9|2|Valor Pago|Valor Pago
TS8|17|TS8_PREFIX|C|3|0|Prefixo|Prefixo do Título
TS8|18|TS8_TIPO|C|3|0|Tipo|Tipo do Título
TS8|19|TS8_NATURE|C|10|0|Natureza|Código da Natureza
--- ### TSD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSD|01|TSD_FILIAL|C|6|0|Filial|Filial do Sistema
TSD|02|TSD_MOTREC|C|6|0|Motivo|Codigo do Motivo Recurso
TSD|03|TSD_DESMOT|C|40|0|Descrico|Descricao do Motivo
--- ### TSE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSE|01|TSE_FILIAL|C|6|0|Filial|Filial do Sistema
TSE|02|TSE_MULTA|C|18|0|Multa|Codigo da Multa
TSE|03|TSE_CODACA|C|6|0|Acao|Codigo da Acao
TSE|04|TSE_DESACA|C|40|0|Descricao|Descricao da Acao
TSE|05|TSE_DTACAO|D|8|0|Data da Acao|Data da Acao
TSE|06|TSE_HRACAO|C|5|0|Hora da Acao|Hora da Acao
TSE|07|TSE_SITUAC|C|1|0|Situacao|Situacao da Acao
TSE|08|TSE_DTREAL|D|8|0|Data Realiz.|Data da Realizacao
TSE|09|TSE_HRREAL|C|5|0|Hora Realiz.|Hora da Realizacao
--- ### TSF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSF|01|TSF_FILIAL|C|6|0|Filial|Filial do Sistema
TSF|02|TSF_CODACA|C|6|0|Codigo Acao|Codigo da Acao
TSF|03|TSF_DESACA|C|40|0|Descricao|Descricao da Acao
--- ### TSG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSG|01|TSG_FILIAL|C|6|0|Filial|Filial do Sistema
TSG|02|TSG_MULTA|C|18|0|Codigo Multa|Codigo da Multa
TSG|03|TSG_NUMAIT|C|14|0|Numero AIT|Auto de Infracao Transito
TSG|04|TSG_TIPOMO|C|1|0|Movimentacao|Tipo da Movimentacao
TSG|05|TSG_DTPAG|D|8|0|Pagamento|Data de Pagamento
TSG|06|TSG_VALORI|N|12|2|Valor Boleto|Valor do Boleto
TSG|07|TSG_DESCON|N|4|1|% Desconto|Percentual de Desconto
TSG|08|TSG_VALPGO|N|12|2|Valor Pago|Valor Pago
TSG|09|TSG_DTDIG|D|8|0|Data Digit.|Data da Digitacao
TSG|10|TSG_HRDIG|C|5|0|Hora Digit.|Hora da Digitacao
TSG|11|TSG_USUDIG|C|15|0|Usuario Dig.|Usuario da Digitacao
TSG|12|TSG_DESVAL|C|1|0|Dest. Valor|Destino Valor Restituicao
--- ### TSH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSH|01|TSH_FILIAL|C|6|0|Filial|Filial do Sistema
TSH|02|TSH_CODINF|C|8|0|Infracao|Codigo da Infracao
TSH|03|TSH_ARTIGO|C|30|0|Artigo|Codigo do Artigo
TSH|04|TSH_DESART|C|80|0|Desc. Artigo|Descricao do Artigo
TSH|05|TSH_VALOR|N|12|2|Valor Multa|Valor da Multa
TSH|06|TSH_PONTOS|C|1|0|Pontos|Pontos
TSH|07|TSH_QTDUFI|N|8|2|Qtd. UFIR|Quantidade de UFIR
TSH|08|TSH_RESPON|C|1|0|Responsabili|Responsabilizacao
TSH|09|TSH_DESDET|M|10|0|Descricao|Descricao Detalhada
TSH|10|TSH_FLGTPM|C|1|0|Tp Infracao|Flag do Tipo de Infracao
TSH|11|TSH_MMSYP|C|6|0|ChaveMM SYP|Chave Memo SYP
--- ### TSI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSI|01|TSI_FILIAL|C|6|0|Filial|Filial do Sistema
TSI|02|TSI_MULTA|C|18|0|Multa|Codigo da Multa
TSI|03|TSI_LOCAL|C|40|0|Local Infr.|Local da Multa
TSI|04|TSI_DTINFR|D|8|0|Dt.Infração|Data da Infracao
TSI|05|TSI_RHINFR|C|5|0|Hr.Infracão|Hora da Infracao
TSI|06|TSI_DTABER|D|8|0|Dt.Abertura|Data da Abertura
TSI|07|TSI_NUMAPD|C|10|0|Num. da APD|Numero da APD
TSI|08|TSI_CODINF|C|8|0|Infração|Codigo da Infracao
TSI|09|TSI_ARTIGO|C|30|0|Artigo|Artigo Legislacao
TSI|10|TSI_CODMOT|C|6|0|Motorista|Codigo do Motorista
TSI|11|TSI_NOMMOT|C|40|0|Nome Motoris|Nome do Motorista
TSI|12|TSI_VIAGEM|C|6|0|Viagem|Viagem
TSI|13|TSI_CODBEM|C|16|0|Veículo|Codigo do Bem
TSI|14|TSI_NOMBEM|C|40|0|Descrição|Nome do Bem
TSI|15|TSI_PLACA|C|8|0|Placa Veícu.|Numero da Placa
TSI|16|TSI_MATRES|C|6|0|Responsável|Matricula do Responsavel
TSI|17|TSI_NOMRES|C|30|0|Nome|Nome do Responsavel
TSI|18|TSI_VALAPD|N|12|2|Valor APD|Valor APD
TSI|19|TSI_DTCONC|D|8|0|Enc. APD|Data Conclusao APD
TSI|20|TSI_DESOBS|C|60|0|Observação|Observacao da Multa
--- ### TSJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSJ|01|TSJ_FILIAL|C|6|0|Filial|Filial do Sistema
TSJ|02|TSJ_CODBEM|C|16|0|Bem|Codigo do Bem
TSJ|03|TSJ_NOME|C|40|0|Nome|Nome do Bem
TSJ|04|TSJ_PLACA|C|8|0|Placa|Placa do Veiculo
TSJ|05|TSJ_ANOMOD|C|4|0|Ano Modelo|Ano Modelo do Veiculo
TSJ|06|TSJ_ANOFAB|C|4|0|Ano Fabric.|Ano Fabricacao do Veiculo
TSJ|07|TSJ_MODELO|C|10|0|Modelo Veic|Modelo do Veiculo
TSJ|08|TSJ_MATRES|C|6|0|Responsavel|Responsavel pelo Veiculo
TSJ|09|TSJ_NOMRES|C|40|0|Nome Resp|Nome Responsavel Veiculo
TSJ|10|TSJ_FILRES|C|6|0|Filial Resp.|Filial Responsavel Veic.
TSJ|11|TSJ_EMAIL|C|50|0|Email|Email do Responsavel
TSJ|12|TSJ_DTINIC|D|8|0|Inic Leasing|Data de Inicio do Leasing
TSJ|13|TSJ_DTFINA|D|8|0|Fim Leasing|Data Final do Leasing
TSJ|14|TSJ_NUMPAR|N|3|0|No Parcelas|Numero de Parcelas
TSJ|15|TSJ_DTQULE|D|8|0|Qui. Leasing|Data Quitacao do Leasing
TSJ|16|TSJ_CODCON|C|6|0|Condutor|Matricula do Condutor
TSJ|17|TSJ_NOMCON|C|40|0|Nome Condut.|Nome Condutor do Veiculo
TSJ|18|TSJ_FILCON|C|6|0|Filial Cond.|Filial Condutor Veic.
TSJ|19|TSJ_CCUCON|C|9|0|C.Custo Cond|Centro Custo Condutor
TSJ|20|TSJ_VALEAS|N|12|2|Val. Leasing|Valor do Leasing
TSJ|21|TSJ_BANCOA|C|80|0|Banco Arren.|Banco do Arrendamento
TSJ|22|TSJ_NUMCON|C|20|0|Num Contrato|Numero Contrato Leasing
TSJ|23|TSJ_EMPROP|C|80|0|Empresa Prop|Empresa Propriet. Veiculo
--- ### TSO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSO|01|TSO_FILIAL|C|6|0|Filial|Filial do Sistema
TSO|02|TSO_MULTA|C|18|0|Codigo Multa|Codigo da Multa
TSO|03|TSO_INCONS|C|1|0|Cod. Incons.|Codigo da Inconsistencia
TSO|04|TSO_STATUS|C|1|0|Status|Status da Inconsistencia
--- ### TSP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSP|01|TSP_FILIAL|C|6|0|Filial|Filial do Sistema
TSP|02|TSP_NUMREQ|C|6|0|Requisicao|Numero da Requisicao
TSP|03|TSP_DATARE|D|8|0|Data Requis.|Data da Requisicao
TSP|04|TSP_HORARE|C|5|0|Hora Requis.|Hora da Requisicao
TSP|05|TSP_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TSP|06|TSP_DESFOR|C|80|0|Nome|Nome do Fornecedor
TSP|07|TSP_OBSERV|M|10|0|Observacao|Observacao sobre Pedido
TSP|08|TSP_STATUS|C|1|0|Status Ped.|Status do Pedido
TSP|09|TSP_LOJA|C|2|0|Loja|Codigo da Loja
--- ### TSQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSQ|01|TSQ_FILIAL|C|6|0|Filial|Filial do Sistema
TSQ|02|TSQ_NUMREQ|C|6|0|Requisicao|Numero da Requisicao
TSQ|03|TSQ_PLACA|C|8|0|Placa|Placa do Veiculo
TSQ|04|TSQ_DESCRI|C|60|0|Tarjeta|Tarjeta da Placa
TSQ|05|TSQ_UFTARJ|C|2|0|UF Tarjeta|Estado da Tarjeta
TSQ|06|TSQ_CORPLA|C|2|0|Cor da Placa|Cor da Placa
TSQ|07|TSQ_DESCOR|C|20|0|Descricao|Descricao da Cor
TSQ|08|TSQ_TAMPLA|C|2|0|Tamanho|Tamanho da Placa
TSQ|09|TSQ_DESTAM|C|20|0|Descricao|Descricao do Tamanho
TSQ|10|TSQ_MATPLA|C|2|0|Material|Material da Placa
TSQ|11|TSQ_DESMAT|C|20|0|Descricao|Descricao do Material
TSQ|12|TSQ_POSICA|C|1|0|Posicao|Posicao da Placa
TSQ|13|TSQ_PELPLA|C|1|0|Pelicula|Pelicula da Placa
--- ### TSR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSR|01|TSR_FILIAL|C|6|0|Filial|Filial do Sistema
TSR|02|TSR_NUMREQ|C|6|0|Requisicao|Numero da Requisicao
TSR|03|TSR_DESCRI|C|60|0|Tarjeta|Tarjeta da Placa
TSR|04|TSR_UFTARJ|C|2|0|UF Tarjeta|Estado da Tarjeta
TSR|05|TSR_CODTAR|C|2|0|Cor Tarjeta|Cor da Tarjeta
TSR|06|TSR_DESCOR|C|20|0|Descricao|Descricao da Cor
TSR|07|TSR_TAMTAR|C|2|0|Tamanho|Tamanho da Tarjeta
TSR|08|TSR_DESTAM|C|20|0|Descricao|Descricao do Tamanho
TSR|09|TSR_MATARJ|C|2|0|Material|Material da Tarjeta
TSR|10|TSR_DESMAT|C|20|0|Descricao|Descricao do Tamanho
TSR|11|TSR_QTDTAR|N|3|0|Quantidade|Quantidade de Tarjetas
TSR|12|TSR_PELTAR|C|1|0|Pelicula|Pelicula da Tarjeta
--- ### TSS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSS|01|TSS_FILIAL|C|6|0|Filial|Filial do Sistema
TSS|02|TSS_NUMREQ|C|6|0|Requisicao|Numero da Requisicao
TSS|03|TSS_MATARA|C|2|0|Material|Material do Arame
TSS|04|TSS_DESMAT|C|20|0|Descricao|Descricao do Material
TSS|05|TSS_QTDARA|N|4|0|Quantidade|Quantidade de Arame
--- ### TST
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TST|01|TST_FILIAL|C|6|0|Filial|Filial do Sistema
TST|02|TST_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TST|03|TST_LOJA|C|2|0|Loja|Codigo da Loja
TST|04|TST_NOMFOR|C|80|0|Nome Fornec.|Nome do Fornecedor
--- ### TSV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSV|01|TSV_FILIAL|C|6|0|Filial|Filial do Sistema
TSV|02|TSV_CODBEM|C|16|0|Bem|Codigo do Bem
TSV|03|TSV_NOMBEM|C|40|0|Nome do Bem|Nome do Bem
TSV|04|TSV_FABRIC|C|6|0|Fabricante|Codigo do Fabricante
TSV|05|TSV_TIPMOD|C|10|0|Tipo Modelo|Tipo do Modelo
TSV|06|TSV_PLACA|C|8|0|Placa|Placa do Bem
TSV|07|TSV_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TSV|08|TSV_FILATU|C|6|0|Filial Atual|Filial Atual
TSV|09|TSV_SERVIC|C|6|0|Servico|Codigo do Servico
TSV|10|TSV_NOMSER|C|40|0|Nome Servico|Nome do Servico
TSV|11|TSV_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TSV|12|TSV_LOJA|C|2|0|Loja|Codigo da Loja
TSV|13|TSV_NOMFOR|C|80|0|Nome Fornec.|Nome do Fornecedor
TSV|14|TSV_QTDSER|N|5|0|Quantidade|Quantidade do Servico
TSV|15|TSV_VALOR|N|10|2|Val. Servico|Valor do Servico
TSV|16|TSV_DTINIC|D|8|0|Data Inicio|Data de Inicio
TSV|17|TSV_STATUS|C|1|0|Status|Status Servico Solicit.
TSV|18|TSV_DTFIM|D|8|0|Data Fim|Data Fim
TSV|19|TSV_OBSERV|M|80|0|Observacao|Observacao
TSV|20|TSV_MMOBS|C|6|0|Chave MMSYP|Chave MMSYP
--- ### TSX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSX|01|TSX_FILIAL|C|6|0|Filial|Filial do Sistema
TSX|02|TSX_NUMREQ|C|6|0|Requisicao|Codigo da Requisicao
TSX|03|TSX_DTSOLI|D|8|0|Data|Data da Solicitacao
TSX|04|TSX_REQUIS|C|40|0|Requisitante|Requisitante
TSX|05|TSX_DEPTO|C|50|0|Departamento|Departamento Requisitante
TSX|06|TSX_EMPRES|C|15|0|Empresa|Empresa
TSX|07|TSX_CCUSTO|C|9|0|Centro Custo|Centro de Custo
TSX|08|TSX_NOMCUS|C|40|0|Nome C.Custo|Nome do Centro de Custo
TSX|09|TSX_NROCPJ|C|9|0|Numero CPJ|Numero do CPJ
TSX|10|TSX_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
TSX|11|TSX_LOJA|C|2|0|Loja|Codigo da Loja
TSX|12|TSX_NOMFOR|C|80|0|Nome Fornec.|Nome do Fornecedor
TSX|13|TSX_OBSERV|M|80|0|Observação|Observação
TSX|14|TSX_STATUS|C|1|0|Status|Status da Requisicao
TSX|15|TSX_MMOBS|C|6|0|Chave MMSYP|Chave MMSYP
--- ### TSY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TSY|01|TSY_FILIAL|C|6|0|Filial|Filial do Sistema
TSY|02|TSY_NUMREQ|C|6|0|Requisicao|Codigo da Requisicao
TSY|03|TSY_SERVIC|C|6|0|Servico|Codigo do Servico
TSY|04|TSY_DESERV|C|40|0|Descricao|Descricao do Servico
TSY|05|TSY_VALOR|N|9|2|Valor|Valor do Servico
TSY|06|TSY_QTDE|N|6|0|Quantidade|Quantidade do Servico
TSY|07|TSY_TOTAL|N|12|2|Total Servic|Total do Servico
--- ### TTA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTA|01|TTA_FILIAL|C|6|0|Filial|Filial do Sistema
TTA|02|TTA_FOLHA|C|9|0|Folha|Folha de Abastecimentos
TTA|03|TTA_POSTO|C|6|0|Posto|Posto Interno
TTA|04|TTA_LOJA|C|2|0|Loja|Codigo da Loja
TTA|05|TTA_TANQUE|C|2|0|Tanque|Tanque do Combustivel
TTA|06|TTA_BOMBA|C|3|0|Bomba|Bomba do Combustivel
TTA|07|TTA_DTABAS|D|8|0|Data|Data dos Abastecimentos
TTA|08|TTA_HRABAS|C|5|0|Hora|Hora dos Abastecimentos
TTA|09|TTA_CONBOM|N|11|3|Cont. Bomba|Contador da Bomba
TTA|10|TTA_TOTCOM|N|11|3|Tot.Combust.|Qtd. Total Combustivel
TTA|11|TTA_SERTRO|C|6|0|Servic.Troca|Servico de Troca
TTA|12|TTA_SERREP|C|6|0|Servic.Repos|Servico de Reposicao
TTA|13|TTA_TOTLUB|N|10|2|Tot.Lubrific|Qtd. Total  Lubrificante
TTA|14|TTA_RESPON|C|6|0|Responsavel|Responsavel
TTA|15|TTA_FILORI|C|6|0|Filial Orig.|Filial Origem
TTA|16|TTA_ORIGEM|C|8|0|Origem|Programa Origem
TTA|17|TTA_CODCOM|C|3|0|Combustível|Código do Combustível
--- ### TTH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTH|01|TTH_FILIAL|C|6|0|Filial|Filial do Sistema
TTH|02|TTH_POSTO|C|6|0|Posto|Posto Interno
TTH|03|TTH_LOJA|C|2|0|Loja|Codigo da Loja
TTH|04|TTH_DESCPO|C|30|0|Nome Posto|Nome do Posto
TTH|05|TTH_TANQUE|C|2|0|Tanque|Tanque do Combustivel
TTH|06|TTH_CODCOM|C|3|0|Combustivel|Combustivel
TTH|07|TTH_TIPO|C|1|0|Tipo Saida|Tipo Saida
TTH|08|TTH_BOMBA|C|3|0|Bomba|Bomba do Combustivel
TTH|09|TTH_FOLHA|C|9|0|Folha|Folha de Abastecimentos
TTH|10|TTH_DTABAS|D|8|0|Data|Data do Lancamento
TTH|11|TTH_HRABAS|C|5|0|Hora|Hora dos Lancamentos
TTH|12|TTH_MOTIVO|C|1|0|Motivo|Motivo
TTH|13|TTH_MOTIV2|C|6|0|Motivo|Codigo do Motivo
TTH|14|TTH_DESCRI|C|40|0|Descricao|Descricao do Motivo
TTH|15|TTH_NUMSEQ|C|6|0|Num.Seq.SD3|Num.Seq.SD3
TTH|16|TTH_QUANT|N|10|2|Quantidade|Quantidade
TTH|17|TTH_MATRIC|C|6|0|Matricula|Matricula Funcionario
TTH|18|TTH_DESCFU|C|30|0|Nome Func.|Nome Funcionario
TTH|19|TTH_FILORI|C|6|0|Filial Orig.|Filial Origem
TTH|20|TTH_CCUSTO|C|9|0|Centro Custo|Centro Custo
--- ### TTI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTI|01|TTI_FILIAL|C|6|0|Filial|Filial do Sistema
TTI|02|TTI_EMPMOV|C|2|0|Emp. Mov.|Empresa da Movimentacao
TTI|03|TTI_FILMOV|C|6|0|Fil. Mov.|Filial da Movimentacao
TTI|04|TTI_EMPVEI|C|2|0|Emp. Veic.|Empresa do Veiculo
TTI|05|TTI_FILVEI|C|6|0|Fil. Veic.|Filial do Veiculo
TTI|06|TTI_CODVEI|C|16|0|Veiculo|Codigo do Veiculo
TTI|07|TTI_NOMVEI|C|40|0|Nome|Nome do Veiculo
TTI|08|TTI_TIPMOV|C|1|0|Tipo Mov.|Tipo Movimento
TTI|09|TTI_DTENT|D|8|0|Data Ent.|Data Entrada
TTI|10|TTI_DTSAI|D|8|0|Data Sai.|Data Saida
TTI|11|TTI_HRENT|C|5|0|Hora Ent.|Hora Entrada
TTI|12|TTI_HRSAI|C|5|0|Hora Sai.|Hora Saida
TTI|13|TTI_MOTENT|C|6|0|Motorista|Cod. Motorista Entrada
TTI|14|TTI_MOTSAI|C|6|0|Motorista|Cod. Motorista Saida
TTI|15|TTI_NOMMOT|C|40|0|Nome|Nome do Motorista
TTI|16|TTI_ROTAEN|C|6|0|Rota Entrada|Codigo da Rota de Entrada
TTI|17|TTI_ROTASA|C|6|0|Rota Saida|Codigo da Rota de Saida
TTI|18|TTI_DESROT|C|80|0|Descricao|Descricao da Rota
TTI|19|TTI_ESCENT|C|3|0|Escala Entr.|Codigo da Escala de Entr.
TTI|20|TTI_ESCSAI|C|3|0|Escala Saida|Codigo da Escala de Saida
TTI|21|TTI_DESESC|C|20|0|Descricao|Descricao da Escala
TTI|22|TTI_POS1EN|N|9|0|Cont. Ent.|Contador de Entrada
TTI|23|TTI_POS2EN|N|9|0|2. Cont. Ent|2. Contador de Entrada
TTI|24|TTI_POS1SA|N|9|0|Cont. Sai.|Contador de Saida
TTI|25|TTI_POS2SA|N|9|0|2. Cont. Sai|2. Contador de Saida
TTI|26|TTI_OBSENT|C|80|0|Obs. Ent.|Observacoes Entrada
TTI|27|TTI_OBSSAI|C|80|0|Obs. Sai.|Observacoes Saida
TTI|28|TTI_USUENT|C|25|0|Usuario|Usuario Operador Entrada
TTI|29|TTI_USUSAI|C|25|0|Usuario|Usuario Operador Saida
--- ### TTK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTK|01|TTK_FILIAL|C|6|0|Filial|Filial do Sistema
TTK|02|TTK_PLACA|C|8|0|Placa|Placa do Veiculo
TTK|03|TTK_DTENT|D|8|0|Data Ent.|Data Entrada
TTK|04|TTK_DTSAI|D|8|0|Data Sai.|Data Saida
TTK|05|TTK_HRENT|C|5|0|Hora Ent.|Hora Entrada
TTK|06|TTK_HRSAI|C|5|0|Hora Sai.|Hora Saida
TTK|07|TTK_NOMMOT|C|40|0|Motorista|Nome do Motorista
TTK|08|TTK_DOCMOT|C|40|0|Documento|Documento
TTK|09|TTK_VEICUL|C|40|0|Veiculo|Veiculo
TTK|10|TTK_CORVEI|C|2|0|Cor|Cor
TTK|11|TTK_DESCOR|C|30|0|Desc. Cor|Descricao Cor
TTK|12|TTK_AUTORI|C|40|0|Autorizacao|Autorizacao
TTK|13|TTK_OBSERV|C|80|0|Observacao|Observacao
TTK|14|TTK_BITMAP|C|8|0|Foto|Foto do Visitante
--- ### TTM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTM|01|TTM_FILIAL|C|6|0|Filial|Filial do Sistema
TTM|02|TTM_CODBEM|C|16|0|Código Bem|Código do Bem
TTM|03|TTM_NOMBEM|C|20|0|Nome do Bem|Nome do Bem
TTM|04|TTM_PLACA|C|8|0|Placa|Placa do Veículo
TTM|05|TTM_EMPROP|C|2|0|Emp. Propri.|Empresa Proprietária
TTM|06|TTM_FILPRO|C|6|0|Filial Prop.|Filial Proprietária
TTM|07|TTM_CATBEM|C|1|0|Categ. Bem|Categoria do Bem
TTM|08|TTM_ALUGUE|C|1|0|Aluguel ?|Indica se permite aluguel
TTM|09|TTM_PROPRI|C|1|0|Propriet.|Proprietário
--- ### TTO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTO|01|TTO_FILIAL|C|6|0|Filial|Filial do Sistema
TTO|02|TTO_NUMCAL|C|8|0|Número|Número Sequencial
TTO|03|TTO_DTCALI|D|8|0|Data|Data calibragem e medição
TTO|04|TTO_HRCALI|C|5|0|Hora|Hora calibragem e medição
TTO|05|TTO_EXECUT|C|6|0|Executante|Codigo do Executante
TTO|06|TTO_NMEXEC|C|30|0|Executante|Nome do Executante
TTO|07|TTO_BEMPAI|C|16|0|Bem|Codigo do Bem
TTO|08|TTO_NMBEM|C|40|0|Nome Bem Pai|Nome do Bem Pai
--- ### TTP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTP|01|TTP_FILIAL|C|6|0|Filial|Filial do Sistema
TTP|02|TTP_NUMCAL|C|8|0|Número|Número Sequencial
TTP|03|TTP_PNEU|C|16|0|Codigo Pneu|Codigo do Pneu
TTP|04|TTP_DESPN|C|30|0|Descricao|Descricao do Pneu
TTP|05|TTP_CODLOC|C|6|0|Local|Codigo do Local
TTP|06|TTP_DESLOC|C|40|0|Nome Local|Nome do Local
TTP|07|TTP_CALATU|N|3|0|Calib. Atual|Calibragem Atual
TTP|08|TTP_CALREA|N|3|0|Calib. Real.|Calibragem Realizada
TTP|09|TTP_SULCO1|N|6|2|Prof. Sulco1|Profundidade do Sulco 1
TTP|10|TTP_SULCO2|N|6|2|Prof. Sulco2|Profundidade do Sulco 2
TTP|11|TTP_SULCO3|N|6|2|Prof. Sulco3|Profundidade do Sulco 3
TTP|12|TTP_PROBLE|C|6|0|Problema|Problema do Pneu
--- ### TTS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTS|01|TTS_FILIAL|C|6|0|Filial|Filial do Sistema
TTS|02|TTS_EMPROP|C|2|0|Emp. Prop.|Empresa Proprietaria
TTS|03|TTS_FILPRO|C|6|0|Fil. Prop.|Filial Proprietaria
TTS|04|TTS_CODROT|C|6|0|Codigo Rota|Codigo da Rota do MNT
TTS|05|TTS_CODIGO|C|3|0|Escala|Codigo da Escala
TTS|06|TTS_TIPESC|C|1|0|Tipo|Tipo de Escala
TTS|07|TTS_EMPESC|C|2|0|Emp. Escala|Empresa da Escala
TTS|08|TTS_FILESC|C|6|0|Fil. Escala|Filial da Escala
TTS|09|TTS_DESCRI|C|20|0|Descrição|Descrição da Escala
TTS|10|TTS_HORARI|C|5|0|Horário|Horário
TTS|11|TTS_EMPFIL|C|6|0|Fil. Escala|Filial da Escala
--- ### TTT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTT|01|TTT_FILIAL|C|6|0|Filial|Filial
TTT|02|TTT_EMPROP|C|2|0|Emp. Prop|Empresa Proprietaria
TTT|03|TTT_FILPRO|C|6|0|Fil. Prop|Filial Proprietaria
TTT|04|TTT_CODROT|C|6|0|Código Rota|Código da Rota do MNT
TTT|05|TTT_NMROTA|C|40|0|Descrição|Descrição do Tipo Serviço
TTT|06|TTT_EXTENS|N|9|2|Extensão|Extensão da Rota
TTT|07|TTT_LIMVEL|N|6|2|Limite Veloc|Limite de Velocidade
TTT|08|TTT_SITUAC|C|1|0|Situação|Situação da Rota
--- ### TTV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTV|01|TTV_FILIAL|C|6|0|Filial|Filial do Sistema
TTV|02|TTV_POSTO|C|6|0|Cod. Posto|Codigo do Posto
TTV|03|TTV_LOJA|C|2|0|Loja|Codigo da Loja
TTV|04|TTV_DESCPO|C|20|0|Descricao|Nome do Posto
TTV|05|TTV_TANQUE|C|2|0|Tanque|Tanque
TTV|06|TTV_BOMBA|C|3|0|Bomba|Bomba de Combustiveis
TTV|07|TTV_DATA|D|8|0|Data|Data da Afericao
TTV|08|TTV_HORA|C|5|0|Hora|Hora da Afericao
TTV|09|TTV_POSINI|N|11|3|Posicao Inic|Posicao Inicial Contador
TTV|10|TTV_POSFIM|N|11|3|Posicao Fim|Posicao Final Contador
TTV|11|TTV_MOTIVO|C|1|0|Motivo|Motivo Marcacao Contador
TTV|12|TTV_ACUMCO|N|15|3|Ac. Contador|Acumulador do Contador
TTV|13|TTV_TIPOLA|C|1|0|Tipo Lancam.|Tipo do Lancamento
TTV|14|TTV_CONSUM|N|11|3|Consumo|Consumo
TTV|15|TTV_USUARI|C|20|0|Usuario|Usuario
TTV|16|TTV_DTINCL|D|8|0|Data da Incl|Data da Inclusao
TTV|17|TTV_HRINCL|C|5|0|Hora da Incl|Hora da Inclusao
TTV|18|TTV_NABAST|C|15|0|N. Abastec.|Numero do Abastecimento
TTV|19|TTV_DOC|C|9|0|Numero Doc.|Numero do documento
TTV|20|TTV_SERIE|C|3|0|Doc. Serie|Serie do documento
--- ### TTX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TTX|01|TTX_FILIAL|C|6|0|Filial|Filial do Sistema
TTX|02|TTX_MOTIVO|C|6|0|Motivo|Codigo do Motivo
TTX|03|TTX_DESCRI|C|40|0|Descricao|Descricao do Motivo
TTX|04|TTX_ATUEST|C|1|0|Atu. Estoque|Atualiza o Estoque?
TTX|05|TTX_MOTTTH|C|1|0|Tipo Lancam.|Tipo de Lancamento
--- ### TU4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU4|01|TU4_FILIAL|C|6|0|Filial|Filial do Sistema
TU4|02|TU4_NUMSIN|C|6|0|Num Sinistro|Número do Sinistro
TU4|03|TU4_SEQANI|C|3|0|Num. Seq.|Num. Seq Animais/Sinistro
TU4|04|TU4_NOMPRO|C|40|0|Prop. Animal|Proprietário dos Animais
TU4|05|TU4_ENDPRO|C|40|0|End. Propr.|End. Proprietário Animal
TU4|06|TU4_CIDPRO|C|20|0|Cidade Prop.|Cidade do Proprietário
TU4|07|TU4_UFPRO|C|2|0|Estado Prop.|Estado Proprietar. Animal
TU4|08|TU4_TELPRO|C|15|0|Tel. Prop.|Tel. Proprietário Animais
TU4|09|TU4_TIPANI|C|20|0|Tipo Animal|Tipo de Animal
TU4|10|TU4_QTDANI|N|2|0|Qtd. Animais|Quantidade de Animais
TU4|11|TU4_VALANI|N|14|2|Valor Animal|Valor Despesa Animais
--- ### TU5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TU5|01|TU5_FILIAL|C|6|0|Filial|Filial do Sistema
TU5|02|TU5_CODSDP|C|6|0|Codigo|Cod. Servico Despachante
TU5|03|TU5_DOCTO|C|6|0|Documento|Codigo do Documento
TU5|04|TU5_DESDOC|C|40|0|Descricao|Descricao do Documento
--- ### TUI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TUI|01|TUI_FILIAL|C|6|0|Filial|Filial do Sistema
TUI|02|TUI_CODIGO|C|6|0|Código|Código da Transferência
TUI|03|TUI_DATA|D|8|0|Data|Data da Transferência
TUI|04|TUI_HORA|C|5|0|Hora|Hora da Transferência
TUI|05|TUI_MOTIVO|C|6|0|Motivo|Motivo da Transferência
TUI|06|TUI_DESMOT|C|40|0|Desc. Motivo|Descrição Motivo
TUI|07|TUI_OBSERV|M|80|0|Observações|Observações
TUI|08|TUI_CODOBS|C|6|0|Código Obs.|Código da Obsevação SYP
TUI|09|TUI_RESPON|C|6|0|Responsável|Responsável pela Transf.
TUI|10|TUI_NOMRES|C|40|0|Nome|Nome do Responsável
TUI|11|TUI_DOC|C|9|0|Documento|Documento Vinculado
TUI|12|TUI_STATUS|C|1|0|Status|Status da Transferência
TUI|13|TUI_EMPORI|C|2|0|Empresa|Empresa Origem
TUI|14|TUI_FILORI|C|6|0|Filial|Filial Origem
TUI|15|TUI_POSORI|C|6|0|Posto|Posto Origem
TUI|16|TUI_LOJORI|C|2|0|Loja|Loja Origem
TUI|17|TUI_TANORI|C|2|0|Tanque|Tanque Origem
TUI|18|TUI_COMORI|C|3|0|Combustível|Combustível Origem
TUI|19|TUI_PROORI|C|15|0|Produto|Produto Origem
TUI|20|TUI_NSEORI|C|9|0|Seq.|Num. Sequencial Origem
TUI|21|TUI_SAIORI|C|1|0|Saída|Tipo de Saída Origem
TUI|22|TUI_BOMORI|C|3|0|Bomba|Bomba Origem
TUI|23|TUI_QUANTI|N|10|3|Quant. Comb.|Quantidade Combustível
TUI|24|TUI_EMPDES|C|2|0|Empresa|Empresa Destino
TUI|25|TUI_FILDES|C|6|0|Filial|Filial Destino
TUI|26|TUI_POSDES|C|6|0|Posto|Posto Destino
TUI|27|TUI_LOJDES|C|2|0|Loja|Loja Destino
TUI|28|TUI_TANDES|C|2|0|Tanque|Tanque Destino
TUI|29|TUI_COMDES|C|3|0|Combustível|Combustível Destino
TUI|30|TUI_PRODES|C|15|0|Produto|Produto Destino
TUI|31|TUI_NSEDES|C|9|0|Seq.|Num. Sequencial Destino
--- ### TV1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV1|01|TV1_FILIAL|C|6|0|Filial|Filial do Sistema
TV1|02|TV1_EMPRES|C|2|0|Empresa|Empresa
TV1|03|TV1_CODBEM|C|16|0|Equipamento|Equipamento
TV1|04|TV1_NOME|C|20|0|Nome|Nome do Equipamento
TV1|05|TV1_PLACA|C|8|0|Placa|Placa
TV1|06|TV1_TURNO|C|3|0|Turno|Turno
TV1|07|TV1_DTSERV|D|8|0|Data|Data Servico
TV1|08|TV1_HREXI|C|5|0|Exped. Inic.|Hora Inicio Expediente
TV1|09|TV1_HREXF|C|5|0|Exped. Fim|Hora Final Expediente
TV1|10|TV1_HRINI|C|5|0|Hora Inicio|Hora Inicio Atividade
TV1|11|TV1_CONINI|N|9|0|Contad. Inic|Contador Inicial
TV1|12|TV1_HRFIM|C|5|0|Hora Final|Hora Final Atividade
TV1|13|TV1_CONFIM|N|9|0|Contador Fim|Contador Final
TV1|14|TV1_TERCEI|C|1|0|Terceiro|Terceiro
TV1|15|TV1_OPERAD|C|6|0|Operador|Operador
TV1|16|TV1_NOMEOP|C|40|0|Nome|Nome
TV1|17|TV1_OBS1|C|250|0|Observação 1|Observação 1
TV1|18|TV1_OBS2|C|250|0|Observação 2|Observação 2
TV1|19|TV1_HRAMNT|C|5|0|Horas MNT|Horas de Manutencao
TV1|20|TV1_HRATRA|C|5|0|Horas Trab.|Horas Trabalhadas
TV1|21|TV1_HRACHU|C|5|0|Horas Chuva|Horas Parada Chuva
TV1|22|TV1_HRAPLA|C|5|0|Horas Plane.|Horas Planejamento
TV1|23|TV1_HRAEXP|C|5|0|Horas Exped.|Horas de Expediente
TV1|24|TV1_INDERR|C|1|0|Possui erro?|Registro com erro
TV1|25|TV1_MSGERR|M|10|0|Erro Import.|Erros de Importacao
TV1|26|TV1_WEBFLE|C|1|0|WebFleet?|Importado via WebFleet?
--- ### TV4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV4|01|TV4_FILIAL|C|6|0|Filial|Filial do Sistema
TV4|02|TV4_COMBOI|C|6|0|Comboio|Comboio
TV4|03|TV4_LOJA|C|2|0|Loja|Loja
TV4|04|TV4_BOMBA|C|3|0|Bomba|Bomba
TV4|05|TV4_TANQUE|C|2|0|Tanque|Tanque
--- ### TV5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV5|01|TV5_FILIAL|C|6|0|Filial|Filial do Sistema
TV5|02|TV5_CODBEM|C|16|0|Bem|Bem
TV5|03|TV5_LARSAP|N|6|2|Larg.Sapatas|Largura Sapatas
TV5|04|TV5_NUMSEC|N|4|0|Núm. Secões|Número de Seções
TV5|05|TV5_TIPEST|C|1|0|Tipo Esteira|Tipo Esteira
TV5|06|TV5_ELOESQ|N|6|2|Elo Esquerdo|Medida Elo Esquerdo
TV5|07|TV5_ELODIR|N|6|2|Elo Direito|Medida Elo Direito
TV5|08|TV5_UMELO|C|2|0|Unidade|Unidade de Medida
TV5|09|TV5_NUMPEC|N|4|0|Núm. Peças|Número Peças
TV5|10|TV5_BUCESQ|N|6|2|Bucha Esquer|Bucha Esquerda
TV5|11|TV5_BUCDIR|N|6|2|Bucha Dir.|Bucha Direito
TV5|12|TV5_UMBUC|C|2|0|Unidade|Unidade de Medida
TV5|13|TV5_GIRADA|C|1|0|Giradas|Giradas
TV5|14|TV5_SAPESQ|N|6|2|Sapata Esq.|Sapata Esquerda
TV5|15|TV5_SAPDIR|N|6|2|Sapata Dir.|Sapata Direita
TV5|16|TV5_UMSAP|C|2|0|Unidade|Unidade de Medida
TV5|17|TV5_GARSIM|C|1|0|Garra Simp.|Garra Simples
TV5|18|TV5_RDDESQ|N|6|2|Roda G.D.Es.|Roda Guia Diant.Esquerda
TV5|19|TV5_RDDDIR|N|6|2|Roda G.D.Dir|Roda Guia Diant.Direita
TV5|20|TV5_UMRDD|C|2|0|Unidade|Unidade de Medida
TV5|21|TV5_RDTESQ|N|6|2|Roda G.T.Es.|Roda Guia Tras.Esquerda
TV5|22|TV5_RDTDIR|N|6|2|Roda G.T.Dir|Roda Guia Tras.Direita
TV5|23|TV5_UMRDT|C|2|0|Unidade|Unidade de Medida
TV5|24|TV5_RS1ESQ|N|6|2|Rol.Sup1 Esq|Roletes Superior 1 Esq.
TV5|25|TV5_RS1DIR|N|6|2|Rol.Sup1 Dir|Roletes Superior 1 Dir.
TV5|26|TV5_UMRS1|C|2|0|Unidade|Unidade de Medida
TV5|27|TV5_RS2ESQ|N|6|2|Rol.Sup2 Esq|Roletes Superior 2 Esq.
TV5|28|TV5_RS2DIR|N|6|2|Rol.Sup2 Dir|Roletes Superior 2 Dir.
TV5|29|TV5_UMRS2|C|2|0|Unidade|Unidade de Medida
TV5|30|TV5_RE1ESQ|N|6|2|Rol.Est1 Esq|Roletes Esteira 1 Esq.
TV5|31|TV5_RE1DIR|N|6|2|Rol.Est1 Dir|Roletes Esteira 1 Dir.
TV5|32|TV5_UMRE1|C|2|0|Unidade|Unidade de Medida
TV5|33|TV5_FLARE1|C|1|0|Flange|Flange RE1
TV5|34|TV5_RE2ESQ|N|6|2|Rol.Est2 Esq|Roletes Esteira 2 Esq.
TV5|35|TV5_RE2DIR|N|6|2|Rol.Est2 Dir|Roletes Esteira 2 Dir.
TV5|36|TV5_UMRE2|C|2|0|Unidade|Unidade de Medida
TV5|37|TV5_FLARE2|C|1|0|Flange|Flange RE2
TV5|38|TV5_RE3ESQ|N|6|2|Rol.Est3 Esq|Roletes Esteira 3 Esq.
TV5|39|TV5_RE3DIR|N|6|2|Rol.Est3 Dir|Roletes Esteira 3 Dir.
TV5|40|TV5_UMRE3|C|2|0|Unidade|Unidade de Medida
TV5|41|TV5_FLARE3|C|1|0|Flange|Flange RE3
TV5|42|TV5_RE4ESQ|N|6|2|Rol.Est4 Esq|Roletes Esteira 4 Esq.
TV5|43|TV5_RE4DIR|N|6|2|Rol.Est4 Dir|Roletes Esteira 4 Dir.
TV5|44|TV5_UMRE4|C|2|0|Unidade|Unidade de Medida
TV5|45|TV5_FLARE4|C|1|0|Flange|Flange RE4
TV5|46|TV5_RE5ESQ|N|6|2|Rol.Est5 Esq|Roletes Esteira 5 Esq.
TV5|47|TV5_RE5DIR|N|6|2|Rol.Est5 Dir|Roletes Esteira 5 Dir.
TV5|48|TV5_UMRE5|C|2|0|Unidade|Unidade de Medida
TV5|49|TV5_FLARE5|C|1|0|Flange|Flange RE5
TV5|50|TV5_RE6ESQ|N|6|2|Rol.Est6 Esq|Roletes Esteira 6 Esq.
TV5|51|TV5_RE6DIR|N|6|2|Rol.Est6 Dir|Roletes Esteira 6 Dir.
TV5|52|TV5_UMRE6|C|2|0|Unidade|Unidade de Medida
TV5|53|TV5_FLARE6|C|1|0|Flange|Flange RE6
TV5|54|TV5_RE7ESQ|N|6|2|Rol.Est7 Esq|Roletes Esteira 7 Esq.
TV5|55|TV5_RE7DIR|N|6|2|Rol.Est7 Dir|Roletes Esteira 7 Dir.
TV5|56|TV5_UMRE7|C|2|0|Unidade|Unidade de Medida
TV5|57|TV5_FLARE7|C|1|0|Flange|Flange RE7
TV5|58|TV5_RE8ESQ|N|6|2|Rol.Est8 Esq|Roletes Esteira 8 Esq.
TV5|59|TV5_RE8DIR|N|6|2|Rol.Est8 Dir|Roletes Esteira 8 Dir.
TV5|60|TV5_UMRE8|C|2|0|Unidade|Unidade de Medida
TV5|61|TV5_FLARE8|C|1|0|Flange|Flange RE8
TV5|62|TV5_RDMESQ|N|6|2|Roda Mot.Es.|Rodas Motrizes Esquerda
TV5|63|TV5_RDMDIR|N|6|2|Roda Mot.Dir|Rodas Motrizes Direita
TV5|64|TV5_UMRDM|C|2|0|Unidade|Unidade de Medida
--- ### TV8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV8|01|TV8_FILIAL|C|6|0|Filial|Filial do Sistema
TV8|02|TV8_CODBEM|C|16|0|Código Bem|Código do Bem
TV8|03|TV8_DATALT|D|8|0|Data Alter.|Data da Alteração
TV8|04|TV8_HORALT|C|8|0|Hora Alter.|Hora da Alteração
TV8|05|TV8_USUARI|C|20|0|Usuário|Usuário da Alteração
TV8|06|TV8_MOTIVO|M|10|0|Motivo|Motivo
TV8|07|TV8_ANTALU|C|1|0|Aluguel ?|Aluguel (Anterior)
TV8|08|TV8_NOVALU|C|1|0|Aluguel ?|Aluguel (Novo)
TV8|09|TV8_ROTINA|C|10|0|Nome Rotina|Nome da Rotina
--- ### TV9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TV9|01|TV9_FILIAL|C|6|0|Filial|Filial do Sistema
TV9|02|TV9_CODBEM|C|16|0|Bem|Bem
TV9|03|TV9_ORDEM|C|6|0|Ordem|Ordem de Serviço
TV9|04|TV9_PLANO|C|6|0|Plano|Plano
TV9|05|TV9_DTMED|D|8|0|Dt. Medição|Data Medição
TV9|06|TV9_ELOESQ|N|6|2|Elo Esquerdo|Medida Elo Esquerdo
TV9|07|TV9_ELODIR|N|6|2|Elo Direito|Medida Elo Direito
TV9|08|TV9_ELOEDG|N|5|2|Elo Esquerdo|Desgaste Elo Esquerdo
TV9|09|TV9_ELODDG|N|5|2|Elo Direito|Desgaste Elo Direito
TV9|10|TV9_MEDELO|C|1|0|Medidor|Responsavel Medida
TV9|11|TV9_OBSELO|M|10|0|Observação|Observação Elo
TV9|12|TV9_BUCESQ|N|6|2|Bucha Esq.|Bucha Esquerda
TV9|13|TV9_BUCDIR|N|6|2|Bucha Dir.|Bucha Direita
TV9|14|TV9_BUCEDG|N|5|2|Bucha Esq.|Desgaste Bucha Esq.
TV9|15|TV9_BUCDDG|N|5|2|Bucha Dir.|Desgaste Bucha Dir.
TV9|16|TV9_MEDBUC|C|1|0|Medidor|Responsavel Medida
TV9|17|TV9_OBSBUC|M|10|0|Observação|Observação Buchas
TV9|18|TV9_SAPESQ|N|6|2|Sapata Dir.|Sapata Direita
TV9|19|TV9_SAPDIR|N|6|2|Sapata Dir.|Sapata Direita
TV9|20|TV9_SAPEDG|N|5|2|Sapata Esq.|Desgaste Sapata Esq.
TV9|21|TV9_SAPDDG|N|5|2|Sapata Dir.|Desgaste Sapata Dir.
TV9|22|TV9_MEDSAP|C|1|0|Medidor|Responsavel Medida
TV9|23|TV9_OBSSAP|M|10|0|Observação|Observação Sapata
TV9|24|TV9_RDDESQ|N|6|2|Roda G.D.Es.|Roda Guia Diant.Esquerda
TV9|25|TV9_RDDDIR|N|6|2|Roda G.D.Dir|Roda Guia Diant.Direita
TV9|26|TV9_RDDEDG|N|5|2|Roda G.D.Es.|Roda G.D.Es.
TV9|27|TV9_RDDDDG|N|5|2|Roda G.D.Dir|Desgaste Roda Dian.Dir.
TV9|28|TV9_MEDRDD|C|1|0|Medidor|Responsavel Medida
TV9|29|TV9_OBSRDD|M|10|0|Observação|Observação RDD
TV9|30|TV9_RDTESQ|N|6|2|Roda G.T.Es.|Roda Guia Tras.Esquerda
TV9|31|TV9_RDTDIR|N|6|2|Roda G.T.Dir|Roda Guia Tras.Direita
TV9|32|TV9_RDTEDG|N|5|2|Roda G.T.Es.|Desgaste Roda Tras.Esq.
TV9|33|TV9_RDTDDG|N|5|2|Roda G.T.Dir|Desgaste Roda Tras.Dir.
TV9|34|TV9_MEDRDT|C|1|0|Medidor|Responsavel Medida
TV9|35|TV9_OBSRDT|M|10|0|Observação|Observação RDT
TV9|36|TV9_RS1ESQ|N|6|2|Rol.Sup1 Esq|Roletes Superior 1 Esq.
TV9|37|TV9_RS1DIR|N|6|2|Rol.Sup1 Dir|Roletes Superior 1 Dir.
TV9|38|TV9_RS1EDG|N|5|2|Rol.Sup1 Esq|Desgaste Rol.Sup.1 Esq.
TV9|39|TV9_RS1DDG|N|5|2|Rol.Sup1 Dir|Desgaste Rol.Sup.1 Dir.
TV9|40|TV9_MEDRS1|C|1|0|Medidor|Responsavel Medida
TV9|41|TV9_OBSRS1|M|10|0|Observação|Observação RS1
TV9|42|TV9_RS2ESQ|N|6|2|Rol.Sup2 Esq|Roletes Superior 2 Esq.
TV9|43|TV9_RS2DIR|N|6|2|Rol.Sup2 Dir|Roletes Superior 2 Dir.
TV9|44|TV9_RS2EDG|N|5|2|Rol.Sup2 Esq|Desgaste Rol.Sup.2 Esq.
TV9|45|TV9_RS2DDG|N|5|2|Rol.Sup2 Dir|Desgaste Rol.Sup.2 Dir.
TV9|46|TV9_MEDRS2|C|1|0|Medidor|Responsavel Medida
TV9|47|TV9_OBSRS2|M|10|0|Observação|Observação RS2
TV9|48|TV9_RE1ESQ|N|6|2|Rol.Est1 Esq|Roletes Esteira 1 Esq.
TV9|49|TV9_RE1DIR|N|6|2|Rol.Est1 Dir|Roletes Esteira 1 Dir.
TV9|50|TV9_RE1EDG|N|5|2|Rol.Est1 Esq|Desgaste Rol.Est.1 Esq.
TV9|51|TV9_RE1DDG|N|5|2|Rol.Est1 Dir|Desgaste Rol.Est.1 Dir.
TV9|52|TV9_MEDRE1|C|1|0|Medidor|Responsavel Medida
TV9|53|TV9_OBSRE1|M|10|0|Observação|Observação RE1
TV9|54|TV9_FLARE1|C|1|0|Flange|Flange RE1
TV9|55|TV9_RE2ESQ|N|6|2|Rol.Est2 Esq|Roletes Esteira 2 Esq.
TV9|56|TV9_RE2DIR|N|6|2|Rol.Est2 Dir|Roletes Esteira 2 Dir.
TV9|57|TV9_RE2EDG|N|5|2|Rol.Est2 Esq|Desgaste Rol.Est.2 Esq.
TV9|58|TV9_RE2DDG|N|5|2|Rol.Est2 Dir|Desgaste Rol.Est.2 Dir.
TV9|59|TV9_MEDRE2|C|1|0|Medidor|Responsavel Medida
TV9|60|TV9_OBSRE2|M|10|0|Observação|Observação RE2
TV9|61|TV9_FLARE2|C|1|0|Flange|Flange RE2
TV9|62|TV9_RE3ESQ|N|6|2|Rol.Est3 Esq|Roletes Esteira 3 Esq.
TV9|63|TV9_RE3DIR|N|6|2|Rol.Est3 Dir|Roletes Esteira 3 Dir.
TV9|64|TV9_RE3EDG|N|5|2|Rol.Est3 Esq|Desgaste Rol.Est.3 Esq.
TV9|65|TV9_RE3DDG|N|5|2|Rol.Est3 Dir|Desgaste Rol.Est.3 Dir.
TV9|66|TV9_MEDRE3|C|1|0|Medidor|Responsavel Medida
TV9|67|TV9_OBSRE3|M|10|0|Observação|Observação RE3
TV9|68|TV9_FLARE3|C|1|0|Flange|Flange RE3
TV9|69|TV9_RE4ESQ|N|6|2|Rol.Est4 Esq|Roletes Esteira 4 Esq.
TV9|70|TV9_RE4DIR|N|6|2|Rol.Est4 Dir|Roletes Esteira 4 Dir.
TV9|71|TV9_RE4EDG|N|5|2|Rol.Est4 Esq|Desgaste Rol.Est.4 Esq.
TV9|72|TV9_RE4DDG|N|5|2|Rol.Est4 Dir|Desgaste Rol.Est.4 Dir.
TV9|73|TV9_MEDRE4|C|1|0|Medidor|Responsavel Medida
TV9|74|TV9_OBSRE4|M|10|0|Observação|Observação RE4
TV9|75|TV9_FLARE4|C|1|0|Flange|Flange RE4
TV9|76|TV9_RE5ESQ|N|6|2|Rol.Est5 Esq|Roletes Esteira 5 Esq.
TV9|77|TV9_RE5DIR|N|6|2|Rol.Est5 Dir|Roletes Esteira 5 Dir.
TV9|78|TV9_RE5EDG|N|5|2|Rol.Est5 Esq|Desgaste Rol.Est.5 Esq.
TV9|79|TV9_RE5DDG|N|5|2|Rol.Est5 Dir|Desgaste Rol.Est.5 Dir.
TV9|80|TV9_MEDRE5|C|1|0|Medidor|Responsavel Medida
TV9|81|TV9_OBSRE5|M|10|0|Observação|Observação RE5
TV9|82|TV9_FLARE5|C|1|0|Flange|Flange RE5
TV9|83|TV9_RE6ESQ|N|6|2|Rol.Est6 Esq|Roletes Esteira 6 Esq.
TV9|84|TV9_RE6DIR|N|6|2|Rol.Est6 Dir|Roletes Esteira 6 Dir.
TV9|85|TV9_RE6EDG|N|5|2|Rol.Est6 Esq|Desgaste Rol.Est.6 Esq.
TV9|86|TV9_RE6DDG|N|5|2|Rol.Est6 Dir|Desgaste Rol.Est.6 Dir.
TV9|87|TV9_MEDRE6|C|1|0|Medidor|Responsavel Medida
TV9|88|TV9_OBSRE6|M|10|0|Observação|Observação RE6
TV9|89|TV9_FLARE6|C|1|0|Flange|Flange RE6
TV9|90|TV9_RE7ESQ|N|6|2|Rol.Est7 Esq|Roletes Esteira 7 Esq.
TV9|91|TV9_RE7DIR|N|6|2|Rol.Est7 Dir|Roletes Esteira 7 Dir.
TV9|92|TV9_RE7EDG|N|5|2|Rol.Est7 Esq|Desgaste Rol.Est.7 Esq.
TV9|93|TV9_RE7DDG|N|5|2|Rol.Est7 Dir|Desgaste Rol.Est.7 Dir.
TV9|94|TV9_MEDRE7|C|1|0|Medidor|Responsavel Medida
TV9|95|TV9_OBSRE7|M|10|0|Observação|Observação RE7
TV9|96|TV9_FLARE7|C|1|0|Flange|Flange RE7
TV9|97|TV9_RE8ESQ|N|6|2|Rol.Est8 Esq|Roletes Esteira 8 Esq.
TV9|98|TV9_RE8DIR|N|6|2|Rol.Est8 Dir|Roletes Esteira 8 Dir.
TV9|99|TV9_RE8EDG|N|5|2|Rol.Est8 Esq|Desgaste Rol.Est.8 Esq.
TV9|9A|TV9_RE8DDG|N|5|2|Rol.Est8 Dir|Desgaste Rol.Est.8 Dir.
TV9|9B|TV9_MEDRE8|C|1|0|Medidor|Responsavel Medida
TV9|9C|TV9_OBSRE8|M|10|0|Observação|Observação RE8
TV9|9D|TV9_FLARE8|C|1|0|Flange|Flange RE8
TV9|9E|TV9_RDMESQ|N|6|2|Roda Mot.Es.|Rodas Motrizes Esquerda
TV9|9F|TV9_RDMDIR|N|6|2|Roda Mot.Dir|Rodas Motrizes Direita
TV9|9G|TV9_RDMEDG|N|5|2|Roda Mot.Es.|Desgaste Rodas Mot.Esq.
TV9|9H|TV9_RDMDDG|N|5|2|Roda Mot.Dir|Desgaste Rodas Mot.Dir.
TV9|9I|TV9_MEDRDM|C|1|0|Medidor|Responsavel Medida
TV9|9J|TV9_OBSRDM|M|10|0|Observação|Observação RDM
TV9|9K|TV9_OBSCOM|M|10|0|Comentarios|Comentarios
--- ### TVA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVA|01|TVA_FILIAL|C|6|0|Filial|Filial do Sistema
TVA|02|TVA_CODBEM|C|16|0|Código Bem|Código do Bem
TVA|03|TVA_ANOREF|C|4|0|Ano Refer.|Ano Referencia
TVA|04|TVA_MESREF|C|2|0|Mês Refer.|Mês Referência
TVA|05|TVA_VALAQU|N|12|2|Valor Aquis.|Valor da Aquisição
TVA|06|TVA_VIDUTI|N|9|0|Vida Útil|Vida Útil
TVA|07|TVA_DEPREM|N|12|2|Vida U.Rem.|Vida Útil Remanescente
TVA|08|TVA_VALRES|N|15|2|Valor Resid.|Valor Residual
TVA|09|TVA_VALPRE|N|16|2|Valor Pres.|Valor Presente
TVA|10|TVA_PARDEP|N|15|2|Parcela Dep.|Parcela da Depreciação
TVA|11|TVA_FUNMNT|N|16|2|Fundo Manut.|Fundo Manutenção Prevent.
TVA|12|TVA_TAXCUS|N|16|2|T. Cus. Cap.|Taxa Custo Capital
TVA|13|TVA_CLEVAR|N|16|2|CLE Variável|CLE Variável
TVA|14|TVA_SEGLIC|N|16|2|Seguro Lic.|Seguro Licenciamento
TVA|15|TVA_TAXADM|N|16|2|Taxa Admin.|Taxa Administrativa
TVA|16|TVA_INDOCI|N|16|2|Ind. Ocios.|Índice de Ociosidade
TVA|17|TVA_CLEFIX|N|16|2|CLE Fixo|CLE Fixo
TVA|18|TVA_CLETOT|N|16|2|CLE Total|CLE Total
TVA|19|TVA_CLEHOR|N|16|2|CLE Hora|CLE Hora
TVA|20|TVA_MPAR09|N|6|2|P. Cus. Cap.|Parâmetro Custo Capital
TVA|21|TVA_MPAR10|N|6|2|P. Tx. Adm.|Parâmetro Taxa Adm.
TVA|22|TVA_MPAR11|N|6|2|P. Ind. Oc.|Parâmetro Índice Ociosid.
--- ### TVB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVB|01|TVB_FILIAL|C|6|0|Filial|Filial do Sistema
TVB|02|TVB_CODBEM|C|16|0|Código Bem|Código do Bem
TVB|03|TVB_NOME|C|40|0|Nome|Nome do Bem
TVB|04|TVB_MOTIVO|C|6|0|Motivo|Motivo Suspensão Aluguel
TVB|05|TVB_DESMOT|C|40|0|Descrição|Desc. Motivo Susp.Aluguel
TVB|06|TVB_DATINI|D|8|0|Início Susp.|Data Início Suspensão
TVB|07|TVB_DATFIM|D|8|0|Fim Susp.|Data Final Suspensão
--- ### TVC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVC|01|TVC_FILIAL|C|6|0|Filial|Filial do Sistema
TVC|02|TVC_MOTIVO|C|6|0|Motivo|Motivo de Suspensão
TVC|03|TVC_DESMOT|C|40|0|Descrição|Descrição do Motivo
--- ### TVH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVH|01|TVH_FILIAL|C|6|0|Filial|Filial do Sistema
TVH|02|TVH_CODFAM|C|6|0|Familia|Código da Familia
TVH|03|TVH_TIPMOD|C|10|0|Tipo Modelo|Código do Tipo Modelo
TVH|04|TVH_LARSAP|N|6|2|Larg.Sapatas|Largura Sapatas
TVH|05|TVH_NUMSEC|N|4|0|Núm. Secões|Número de Seções
TVH|06|TVH_TIPEST|C|1|0|Tipo Esteira|Tipo Esteira
TVH|07|TVH_ELOESQ|N|6|2|Elo Esquerdo|Medida Elo Esquerdo
TVH|08|TVH_ELODIR|N|6|2|Elo Direito|Medida Elo Direito
TVH|09|TVH_UMELO|C|2|0|Unidade|Unidade de Medida
TVH|10|TVH_NUMPEC|N|4|0|Núm. Peças|Número Peças
TVH|11|TVH_BUCESQ|N|6|2|Bucha Esquer|Bucha Esquerda
TVH|12|TVH_BUCDIR|N|6|2|Bucha Dir.|Bucha Direito
TVH|13|TVH_UMBUC|C|2|0|Unidade|Unidade de Medida
TVH|14|TVH_GIRADA|C|1|0|Giradas|Giradas
TVH|15|TVH_SAPESQ|N|6|2|Sapata Esq.|Sapata Esquerda
TVH|16|TVH_SAPDIR|N|6|2|Sapata Dir.|Sapata Direita
TVH|17|TVH_UMSAP|C|2|0|Unidade|Unidade de Medida
TVH|18|TVH_GARSIM|C|1|0|Garra Simp.|Garra Simples
TVH|19|TVH_RDDESQ|N|6|2|Roda G.D.Es.|Roda Guia Diant.Esquerda
TVH|20|TVH_RDDDIR|N|6|2|Roda G.D.Dir|Roda Guia Diant.Direita
TVH|21|TVH_UMRDD|C|2|0|Unidade|Unidade de Medida
TVH|22|TVH_RDTESQ|N|6|2|Roda G.T.Es.|Roda Guia Tras.Esquerda
TVH|23|TVH_RDTDIR|N|6|2|Roda G.T.Dir|Roda Guia Tras.Direita
TVH|24|TVH_UMRDT|C|2|0|Unidade|Unidade de Medida
TVH|25|TVH_RS1ESQ|N|6|2|Rol.Sup1 Esq|Roletes Superior 1 Esq.
TVH|26|TVH_RS1DIR|N|6|2|Rol.Sup1 Dir|Roletes Superior 1 Dir.
TVH|27|TVH_UMRS1|C|2|0|Unidade|Unidade de Medida
TVH|28|TVH_RS2ESQ|N|6|2|Rol.Sup2 Esq|Roletes Superior 2 Esq.
TVH|29|TVH_RS2DIR|N|6|2|Rol.Sup2 Dir|Roletes Superior 2 Dir.
TVH|30|TVH_UMRS2|C|2|0|Unidade|Unidade de Medida
TVH|31|TVH_RE1ESQ|N|6|2|Rol.Est1 Esq|Roletes Esteira 1 Esq.
TVH|32|TVH_RE1DIR|N|6|2|Rol.Est1 Dir|Roletes Esteira 1 Dir.
TVH|33|TVH_UMRE1|C|2|0|Unidade|Unidade de Medida
TVH|34|TVH_FLARE1|C|1|0|Flange|Flange RE1
TVH|35|TVH_RE2ESQ|N|6|2|Rol.Est2 Esq|Roletes Esteira 2 Esq.
TVH|36|TVH_RE2DIR|N|6|2|Rol.Est2 Dir|Roletes Esteira 2 Dir.
TVH|37|TVH_UMRE2|C|2|0|Unidade|Unidade de Medida
TVH|38|TVH_FLARE2|C|1|0|Flange|Flange RE2
TVH|39|TVH_RE3ESQ|N|6|2|Rol.Est3 Esq|Roletes Esteira 3 Esq.
TVH|40|TVH_RE3DIR|N|6|2|Rol.Est3 Dir|Roletes Esteira 3 Dir.
TVH|41|TVH_UMRE3|C|2|0|Unidade|Unidade de Medida
TVH|42|TVH_FLARE3|C|1|0|Flange|Flange RE3
TVH|43|TVH_RE4ESQ|N|6|2|Rol.Est4 Esq|Roletes Esteira 4 Esq.
TVH|44|TVH_RE4DIR|N|6|2|Rol.Est4 Dir|Roletes Esteira 4 Dir.
TVH|45|TVH_UMRE4|C|2|0|Unidade|Unidade de Medida
TVH|46|TVH_FLARE4|C|1|0|Flange|Flange RE4
TVH|47|TVH_RE5ESQ|N|6|2|Rol.Est5 Esq|Roletes Esteira 5 Esq.
TVH|48|TVH_RE5DIR|N|6|2|Rol.Est5 Dir|Roletes Esteira 5 Dir.
TVH|49|TVH_UMRE5|C|2|0|Unidade|Unidade de Medida
TVH|50|TVH_FLARE5|C|1|0|Flange|Flange RE5
TVH|51|TVH_RE6ESQ|N|6|2|Rol.Est6 Esq|Roletes Esteira 6 Esq.
TVH|52|TVH_RE6DIR|N|6|2|Rol.Est6 Dir|Roletes Esteira 6 Dir.
TVH|53|TVH_UMRE6|C|2|0|Unidade|Unidade de Medida
TVH|54|TVH_FLARE6|C|1|0|Flange|Flange RE6
TVH|55|TVH_RE7ESQ|N|6|2|Rol.Est7 Esq|Roletes Esteira 7 Esq.
TVH|56|TVH_RE7DIR|N|6|2|Rol.Est7 Dir|Roletes Esteira 7 Dir.
TVH|57|TVH_UMRE7|C|2|0|Unidade|Unidade de Medida
TVH|58|TVH_FLARE7|C|1|0|Flange|Flange RE7
TVH|59|TVH_RE8ESQ|N|6|2|Rol.Est8 Esq|Roletes Esteira 8 Esq.
TVH|60|TVH_RE8DIR|N|6|2|Rol.Est8 Dir|Roletes Esteira 8 Dir.
TVH|61|TVH_UMRE8|C|2|0|Unidade|Unidade de Medida
TVH|62|TVH_FLARE8|C|1|0|Flange|Flange RE8
TVH|63|TVH_RDMESQ|N|6|2|Roda Mot.Es.|Rodas Motrizes Esquerda
TVH|64|TVH_RDMDIR|N|6|2|Roda Mot.Dir|Rodas Motrizes Direita
TVH|65|TVH_UMRDM|C|2|0|Unidade|Unidade de Medida
--- ### TVI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVI|01|TVI_FILIAL|C|6|0|Filial|Filial do Sistema
TVI|02|TVI_CODFAM|C|6|0|Família|Código da Família
TVI|03|TVI_TIPMOD|C|10|0|Tipo Modelo|Código do Tipo Modelo
TVI|04|TVI_SERVIC|C|6|0|Serviço|Código do Serviço
TVI|05|TVI_ELOPAV|N|5|2|% Aviso Elo|% Aviso Elo
TVI|06|TVI_ELOPOS|N|5|2|% Elo OS.|% Desgaste Elo Gera OS.
TVI|07|TVI_SERELO|C|6|0|Serviço|Serviço OS.
TVI|08|TVI_BUCPAV|N|5|2|% Bucha Av.|% Bucha Aviso
TVI|09|TVI_BUCPOS|N|5|2|% Bucha OS.|% Bucha Gera OS.
TVI|10|TVI_SERBUC|C|6|0|Serviço|Serviço OS.
TVI|11|TVI_SAPPAV|N|5|2|% Sapata Av.|% Sapata Aviso
TVI|12|TVI_SAPPOS|N|5|2|% Sapata OS.|% Sapata Gera OS.
TVI|13|TVI_SERSAP|C|6|0|Serviço|Serviço OS.
TVI|14|TVI_RDDPAV|N|5|2|Roda G.D.Av.|% Roda Guia Diant. Aviso
TVI|15|TVI_RDDPOS|N|5|2|Roda G.D.OS.|% Roda Guia Diant. OS.
TVI|16|TVI_SERRDD|C|6|0|Serviço|Serviço OS.
TVI|17|TVI_RDTPAV|N|5|2|Roda G.T.Av.|% Roda Guia Tras. Aviso
TVI|18|TVI_RDTPOS|N|5|2|Roda G.T.OS.|% Roda Guia Tras. OS.
TVI|19|TVI_SERRDT|C|6|0|Serviço|Serviço OS.
TVI|20|TVI_RS1PAV|N|5|2|R. Sup.1 Av.|% Roletes Superior 1 Av.
TVI|21|TVI_RS1POS|N|5|2|R. Sup.1 OS.|% Roletes Superior 1 OS.
TVI|22|TVI_SERRS1|C|6|0|Serviço|Serviço OS.
TVI|23|TVI_RS2PAV|N|5|2|R. Sup.2 Av.|% Roletes Superior 2 Av.
TVI|24|TVI_RS2POS|N|5|2|R. Sup.2 OS.|% Roletes Superior 2 OS.
TVI|25|TVI_SERRS2|C|6|0|Serviço|Serviço OS.
TVI|26|TVI_RE1PAV|N|5|2|R. Est.1 Av.|% Roletes Esteira 1 Aviso
TVI|27|TVI_RE1POS|N|5|2|R. Est.1 OS.|% Roletes Esteira 1 OS.
TVI|28|TVI_SERRE1|C|6|0|Serviço|Serviço OS.
TVI|29|TVI_RE2PAV|N|5|2|R. Est.2 Av.|% Roletes Esteira 2 Aviso
TVI|30|TVI_RE2POS|N|5|2|R. Est.2 OS.|% Roletes Esteira 2 OS.
TVI|31|TVI_SERRE2|C|6|0|Serviço|Serviço OS.
TVI|32|TVI_RE3PAV|N|5|2|R. Est.3 Av.|% Roletes Esteira 3 Aviso
TVI|33|TVI_RE3POS|N|5|2|R. Est.3 OS.|% Roletes Esteira 3 OS.
TVI|34|TVI_SERRE3|C|6|0|Serviço|Serviço OS.
TVI|35|TVI_RE4PAV|N|5|2|R. Est.4 Av.|% Roletes Esteira 4 Aviso
TVI|36|TVI_RE4POS|N|5|2|R. Est.4 OS.|% Roletes Esteira 4 OS.
TVI|37|TVI_SERRE4|C|6|0|Serviço|Serviço OS
TVI|38|TVI_RE5PAV|N|5|2|R. Est.5 Av.|% Roletes Esteira 5 Aviso
TVI|39|TVI_RE5POS|N|5|2|R. Est.5 OS.|% Roletes Esteira 5 OS.
TVI|40|TVI_SERRE5|C|6|0|Serviço|Serviço OS.
TVI|41|TVI_RE6PAV|N|5|2|R. Est.6 Av.|% Roletes Esteira 6 Aviso
TVI|42|TVI_RE6POS|N|5|2|R. Est.6 OS.|% Roletes Esteira 6 OS.
TVI|43|TVI_SERRE6|C|6|0|Serviço|Serviço OS.
TVI|44|TVI_RE7PAV|N|5|2|R. Est.7 Av.|% Roletes Esteira 7 Aviso
TVI|45|TVI_RE7POS|N|5|2|R. Est.7 OS.|% Roletes Esteira 7 OS.
TVI|46|TVI_SERRE7|C|6|0|Serviço|Serviço OS.
TVI|47|TVI_RE8PAV|N|5|2|R. Est.8 Av.|% Roletes Esteira 8 Aviso
TVI|48|TVI_RE8POS|N|5|2|R. Est.8 OS.|% Roletes Esteira 8 OS.
TVI|49|TVI_SERRE8|C|6|0|Serviço|Serviço OS.
TVI|50|TVI_RDMPAV|N|5|2|Roda Mot.Av.|% Rodas Motrizes Aviso
TVI|51|TVI_RDMPOS|N|5|2|Rd. Mot. OS.|% Rodas Motrizes OS.
TVI|52|TVI_SERRDM|C|6|0|Serviço|Serviço OS.
--- ### TVJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVJ|01|TVJ_FILIAL|C|6|0|Filial|Filial do Sistema
TVJ|02|TVJ_FOLHA|C|9|0|Folha|Folha
TVJ|03|TVJ_OBRA|C|6|0|Filial|Filial
TVJ|04|TVJ_POSTO|C|6|0|Comboio|Comboio
TVJ|05|TVJ_LOJA|C|2|0|Loja|Loja
TVJ|06|TVJ_DTABAS|D|8|0|Data|Data do Abastecimento
TVJ|07|TVJ_CCUSTO|C|9|0|Centro Custo|Centro Custo
TVJ|08|TVJ_STATUS|C|1|0|Status|Status
TVJ|09|TVJ_PROD01|C|15|0|Produto 1|Produto 1
TVJ|10|TVJ_DESC01|C|70|0|Desc. 1|Descrição 1
TVJ|11|TVJ_PROD02|C|15|0|Produto 2|Produto 2
TVJ|12|TVJ_DESC02|C|70|0|Desc. 2|Desc. 2
TVJ|13|TVJ_PROD03|C|15|0|Produto 3|Produto 3
TVJ|14|TVJ_DESC03|C|70|0|Desc. 3|Desc. 3
TVJ|15|TVJ_PROD04|C|15|0|Produto 4|Produto 4
TVJ|16|TVJ_DESC04|C|70|0|Desc. 4|Desc. 4
TVJ|17|TVJ_PROD05|C|15|0|Produto 5|Produto 5
TVJ|18|TVJ_DESC05|C|70|0|Desc. 5|Desc. 5
TVJ|19|TVJ_PROD06|C|15|0|Produto 6|Produto 6
TVJ|20|TVJ_DESC06|C|70|0|Desc. 6|Desc. 6
TVJ|21|TVJ_PROD07|C|15|0|Produto 7|Produto 7
TVJ|22|TVJ_DESC07|C|70|0|Desc. 7|Desc. 7
TVJ|23|TVJ_USUARI|C|25|0|Usuário|Usuário
--- ### TVK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVK|01|TVK_FILIAL|C|6|0|Filial|Filial do Sistema
TVK|02|TVK_CODBEM|C|16|0|Bem|Bem
TVK|03|TVK_SERVIC|C|6|0|Serviço|Serviço
TVK|04|TVK_SEQREL|C|3|0|Sequência|Sequência
TVK|05|TVK_ELOPAV|N|5|2|% Aviso Elo|% Aviso Elo
TVK|06|TVK_ELOPOS|N|5|2|%Elo GeraOS|%Elo GeraOS
TVK|07|TVK_SERELO|C|6|0|Serviço|Serviço O.S.
TVK|08|TVK_BUCPAV|N|5|2|%Bucha Aviso|%Bucha Aviso
TVK|09|TVK_BUCPOS|N|5|2|%Bucha O.S.|%Bucha Gera O.S.
TVK|10|TVK_SERBUC|C|6|0|Serviço|Serviço O.S.
TVK|11|TVK_SAPPAV|N|5|2|%Sapata Avi.|%Sapata Aviso
TVK|12|TVK_SAPPOS|N|5|2|%Sapata O.S.|%Sapata Gera O.S.
TVK|13|TVK_SERSAP|C|6|0|Serviço|Serviço O.S.
TVK|14|TVK_RDDPAV|N|5|2|Roda G.D.Av.|Roda Guia Diant.Aviso
TVK|15|TVK_RDDPOS|N|5|2|Roda G.D.O.S|Roda Guia Diant. O.S.
TVK|16|TVK_SERRDD|C|6|0|Serviço|Serviço O.S.
TVK|17|TVK_RDTPAV|N|5|2|Roda G.T.Av.|Roda Guia Tras.Aviso
TVK|18|TVK_RDTPOS|N|5|2|Roda G.T.O.S|Roda Guia Tras. O.S.
TVK|19|TVK_SERRDT|C|6|0|Serviço|Serviço O.S.
TVK|20|TVK_RS1PAV|N|5|2|Rol.Sup1 %AV|Roletes Superior 1 % Avis
TVK|21|TVK_RS1POS|N|5|2|Rol.Sup1 %OS|Roletes Superior 1 Dir.
TVK|22|TVK_SERRS1|C|6|0|Serviço|Serviço O.S.
TVK|23|TVK_RS2PAV|N|5|2|Rol.Sup2 %AV|Roletes Superior 2 % Avis
TVK|24|TVK_RS2POS|N|5|2|Rol.Sup2 %OS|Roletes Superior 2 Dir.
TVK|25|TVK_SERRS2|C|6|0|Serviço|Serviço O.S.
TVK|26|TVK_RE1PAV|N|5|2|Rol.Est1 %AV|Roletes Esteira 1 % Aviso
TVK|27|TVK_RE1POS|N|5|2|Rol.Est1 %OS|Roletes Esteira 1 Dir.
TVK|28|TVK_SERRE1|C|6|0|Serviço|Serviço O.S.
TVK|29|TVK_RE2PAV|N|5|2|Rol.Est2 %AV|Roletes Esteira 2 % Aviso
TVK|30|TVK_RE2POS|N|5|2|Rol.Est2 %OS|Roletes Esteira 2 Dir.
TVK|31|TVK_SERRE2|C|6|0|Serviço|Serviço O.S.
TVK|32|TVK_RE3PAV|N|5|2|Rol.Est3 %AV|Roletes Esteira 3 % Aviso
TVK|33|TVK_RE3POS|N|5|2|Rol.Est3 %OS|Roletes Esteira 3 Dir.
TVK|34|TVK_SERRE3|C|6|0|Serviço|Serviço O.S.
TVK|35|TVK_RE4PAV|N|5|2|Rol.Est4 %AV|Roletes Esteira 4 % Aviso
TVK|36|TVK_RE4POS|N|5|2|Rol.Est4 %OS|Roletes Esteira 4 Dir.
TVK|37|TVK_SERRE4|C|6|0|Serviço|Serviço O.S.
TVK|38|TVK_RE5PAV|N|5|2|Rol.Est5 %AV|Roletes Esteira 5 % Aviso
TVK|39|TVK_RE5POS|N|5|2|Rol.Est5 %OS|Roletes Esteira 5 Dir.
TVK|40|TVK_SERRE5|C|6|0|Serviço|Serviço O.S.
TVK|41|TVK_RE6PAV|N|5|2|Rol.Est6 %AV|Roletes Esteira 6 % Aviso
TVK|42|TVK_RE6POS|N|5|2|Rol.Est6 %OS|Roletes Esteira 6 Dir.
TVK|43|TVK_SERRE6|C|6|0|Serviço|Serviço O.S.
TVK|44|TVK_RE7PAV|N|5|2|Rol.Est7 %AV|Roletes Esteira 7 % Aviso
TVK|45|TVK_RE7POS|N|5|2|Rol.Est7 %OS|Roletes Esteira 7 Dir.
TVK|46|TVK_SERRE7|C|6|0|Serviço|Serviço O.S.
TVK|47|TVK_RE8PAV|N|5|2|Rol.Est8 %AV|Roletes Esteira 8 % Aviso
TVK|48|TVK_RE8POS|N|5|2|Rol.Est8 %OS|Roletes Esteira 8 Dir.
TVK|49|TVK_SERRE8|C|6|0|Serviço|Serviço O.S.
TVK|50|TVK_RDMPAV|N|5|2|Roda Mot.Av.|Rodas Motrizes Aviso
TVK|51|TVK_RDMPOS|N|5|2|Roda Mot.%OS|Rodas Motrizes %O.S.
TVK|52|TVK_SERRDM|C|6|0|Serviço|Serviço O.S.
--- ### TVL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVL|01|TVL_FILIAL|C|6|0|Filial|Filial do Sistema
TVL|02|TVL_EMPRES|C|2|0|Grupo Cons.|Grupo da Empresa Cons.
TVL|03|TVL_CODBEM|C|16|0|Código Bem|Código do Bem
TVL|04|TVL_ANOREF|C|4|0|Ano Refer.|Ano Referência
TVL|05|TVL_MESREF|C|2|0|Mês Refer.|Mês Referência
TVL|06|TVL_EMPOPE|C|2|0|Grupo Oper.|Grupo da Emp. de Operação
TVL|07|TVL_FILOPE|C|6|0|Filial Oper.|Filial de Operação
TVL|08|TVL_CCUSTO|C|9|0|CC Operação|Centro de Custo Operação
TVL|09|TVL_VALAQU|N|12|2|Valor Aquis.|Valor da Aquisição
TVL|10|TVL_VIDUTI|N|9|0|Vida Útil|Vida Útil
TVL|11|TVL_UNIDES|C|1|0|Unid. Vida|Unid. Contr. Vida Útil
TVL|12|TVL_DEPREM|N|13|0|Vida U.Rem.|Vida Útil Remanescente
TVL|13|TVL_VALPRE|N|14|2|Valor Pres.|Valor Presente
TVL|14|TVL_VALRES|N|15|2|Valor Resid.|Valor Residual
TVL|15|TVL_PARDEP|N|16|2|Parc. Dep/h.|Parcela da Depreciação
TVL|16|TVL_FUNMNT|N|16|2|Fundo Manut.|Fundo MNT Prev. por Hora
TVL|17|TVL_TAXCUS|N|16|2|T. Cus. Cap.|Taxa Custo Capital
TVL|18|TVL_CLEVAR|N|16|2|CLE Variável|CLE Variável
TVL|19|TVL_SEGLIC|N|16|2|Seguro Lic.|Seguro Licenciamento
TVL|20|TVL_TAXADM|N|16|3|Taxa Admin.|Taxa Administrativa
TVL|21|TVL_INDOCI|N|16|2|Índ. Ocios.|Índice de Ociosidade
TVL|22|TVL_CLEFIX|N|16|2|CLE Fixo|CLE Fixo
TVL|23|TVL_BASHOR|N|16|2|Base Hr. Mi.|Base de Hora Mínima
TVL|24|TVL_CLETOT|N|16|2|CLE Total|CLE Total
TVL|25|TVL_CLEHOR|N|16|2|CLE Hora|CLE Hora
TVL|26|TVL_CLEHRE|N|16|2|CLE Hora R.|CLE Hora
TVL|27|TVL_VALFAT|N|14|2|Valor Fatur.|Valor Faturado
TVL|28|TVL_INDCAL|C|1|0|Ind. Cálculo|Indicador Cálculo Custo
TVL|29|TVL_MOTIVO|M|10|0|Motivo|Motivo Alt. Indicador
TVL|30|TVL_DIALOC|N|2|0|Dias Aloc.|Dias Alocado na Filial
TVL|31|TVL_CONTAD|N|12|0|Contador|Contador
--- ### TVP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVP|01|TVP_FILIAL|C|6|0|Filial|Filial do Sistema
TVP|02|TVP_FOLHA|C|9|0|Folha|Folha
TVP|03|TVP_CODBEM|C|16|0|Cod. Bem|Código do Bem
--- ### TVX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVX|01|TVX_FILIAL|C|6|0|Filial|Filial do Sistema
TVX|02|TVX_ID|C|6|0|Código|Código do Planejamento
TVX|03|TVX_SEQUEN|C|3|0|Sequência|Sequência Planejamento
TVX|04|TVX_DTINIC|D|8|0|Data Início|Data Início
TVX|05|TVX_DTFIM|D|8|0|Data Fim|Data Fim
TVX|06|TVX_QUANT|N|9|0|Quantidade|Quantidade de Bens
TVX|07|TVX_MOTIVO|M|80|0|Motivo|Motivo da Alteração
TVX|08|TVX_CODMOT|C|6|0|Cód. Motivo|Motivo da Alteração
TVX|09|TVX_DTALT|D|8|0|Última Alt.|Data da Última Alteração
TVX|10|TVX_CODUSU|C|6|0|Responsável|Código do Responsável
TVX|11|TVX_NOMUSU|C|40|0|Nome Resp.|Nome do Responsável
--- ### TVY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVY|01|TVY_FILIAL|C|6|0|Filial|Filial do Sistema
TVY|02|TVY_ID|C|6|0|Código|Código do Planejamento
TVY|03|TVY_DESCRI|C|60|0|Descrição|Descrição do Planejamento
TVY|04|TVY_CODFAM|C|6|0|Família|Código da Família
TVY|05|TVY_DESFAM|C|40|0|Descrição|Descrição da Família
TVY|06|TVY_TIPMOD|C|10|0|Modelo|Código do Modelo
TVY|07|TVY_DESMOD|C|20|0|Descrição|Descrição do Modelo
TVY|08|TVY_DTPLAN|D|8|0|Data Plan.|Data do Planejamento
TVY|09|TVY_SEQUEN|C|3|0|Sequência|Sequência Planejamento
TVY|10|TVY_DTINIC|D|8|0|Data Início|Data Início
TVY|11|TVY_DTFIM|D|8|0|Data Fim|Data Fim
TVY|12|TVY_QUANT|N|9|0|Quantidade|Quantidade de Bens
TVY|13|TVY_DTALT|D|8|0|Última Alt.|Data da Última Alteração
TVY|14|TVY_CODUSU|C|6|0|Responsável|Código do Responsável
TVY|15|TVY_NOMUSU|C|40|0|Descrição|Descrição do Responsável
--- ### TVZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
TVZ|01|TVZ_FILIAL|C|6|0|Filial|Filial do Sistema
TVZ|02|TVZ_CODBEM|C|16|0|Código Bem|Código do Bem
TVZ|03|TVZ_NOMBEM|C|40|0|Nome Bem|Nome do Bem
TVZ|04|TVZ_DTALT|D|8|0|Data Alt.|Data da Alteração
TVZ|05|TVZ_HRALT|C|5|0|Hora Alt.|Hora da Alteração
TVZ|06|TVZ_DTDES|D|8|0|Data Desmob.|Data de Desmobilização
TVZ|07|TVZ_CODUSU|C|6|0|Usuário|Código do Usuário
TVZ|08|TVZ_NOMUSU|C|40|0|Nome Usuário|Nome do Usuário
--- ###
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
||||0|0||

