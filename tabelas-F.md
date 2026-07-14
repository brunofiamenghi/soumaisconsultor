## Módulo: Módulo Não Identificado
--- ### FRA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRA|01|FRA_FILIAL|C|6|0|Filial|Filial do sistema
FRA|02|FRA_NUM|C|6|0|Numero|Num. da transferência
FRA|03|FRA_DATA|D|8|0|Data|Data de transferencia
FRA|04|FRA_LOTE|C|8|0|Num. do lote|Num. do lote
FRA|05|FRA_ORIGEM|C|8|0|Origem|Origem transferência
FRA|06|FRA_PREFIX|C|3|0|Prefixo|Prefixo do titulo
FRA|07|FRA_NUMTIT|C|6|0|Titulo|Numero do titulo
FRA|08|FRA_PARC|C|3|0|Parcela|Parcela do titulo
FRA|09|FRA_TIPO|C|3|0|Tipo|Tipo do titulo
FRA|10|FRA_CLIENT|C|6|0|Cliente|Codigo do cliente
FRA|11|FRA_LOJA|C|2|0|Loja|Loja do cliente
FRA|12|FRA_BCORIG|C|3|0|Banco origem|Banco origem
FRA|13|FRA_AGORIG|C|5|0|Agenc.origem|Agencia origem
FRA|14|FRA_CTORIG|C|10|0|Conta origem|Conta origem
FRA|15|FRA_CRORIG|C|1|0|Cart. orig.|Carteira origem
FRA|16|FRA_BCDEST|C|3|0|Banco dest.|Banco de destino
FRA|17|FRA_AGDEST|C|5|0|Agenc.dest.|Agencia destino
FRA|18|FRA_CTDEST|C|10|0|Conta dest.|Conta destino
FRA|19|FRA_CRDEST|C|1|0|Cart. dest.|Carteira destino
FRA|20|FRA_LJCXOR|C|3|0|Cx. Origem|Caixa de origem
FRA|21|FRA_LJESTA|C|3|0|Estaçao|Estaçao
FRA|22|FRA_LJPDV|C|10|0|PDV|PDV
FRA|23|FRA_LJMOV|C|2|0|Num. movim.|Numero do movimento
FRA|24|FRA_LJDTFE|D|8|0|Fechamento|Dt.fechamento.movto.
--- ### FX7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FX7|01|FX7_FILIAL|C|6|0|Filial|Filial
FX7|02|FX7_MODELO|C|1|0|Mod Credenc|Modelo de credencial
FX7|03|FX7_NOMECO|C|60|0|Descrição|Descrição da Filial
FX7|04|FX7_PJCPF|C|14|0|CNPJ/CPF|Campo de CNPJ ou CPF
FX7|05|FX7_CREDEN|C|40|0|Client ID|Identificação do TSS
FX7|06|FX7_CREKEY|C|200|0|Cli. Secret|Chave Secreta
FX7|07|FX7_STATUS|C|1|0|Status|Status do Registro
FX7|08|FX7_OK|C|2|0|OK|Marca no registro oBrowse
FX7|09|FX7_TIPO|C|20|0|Tipo|Tipo do certificado digit
FX7|10|FX7_CERT|C|250|0|Arquivo Cert|Certificado  Digital
FX7|11|FX7_PRIKEY|C|250|0|Private Key|Nome do arq, private Key
FX7|12|FX7_SLOT|C|100|0|Slot|Slot do cert digital
FX7|13|FX7_SENHA|C|30|0|Senha|Senha do arquivo digital
FX7|14|FX7_URL|C|250|0|URL do TSS|URL do TSS
FX7|15|FX7_HSM|C|250|0|Arquivo HSM|Informe o Arquivo HSM
FX7|16|FX7_LABEL|C|250|0|Label|Label do cert. digital
FX7|17|FX7_IDHEX|C|30|0| ID Hexa| ID Hexa
FX7|18|FX7_STCERT|C|1|0|Status Cert|Status do certificado
--- ### FM3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FM3|01|FM3_FILIAL|C|6|0|Filial|Filial do Sistema
FM3|02|FM3_CODIGO|C|9|0|Código|Código Agrupador
FM3|03|FM3_DESCR|C|50|0|Descrição|Descrição do Agrupador
FM3|04|FM3_CODUSR|C|66|0|Cód Usuario|Código do Usuário
FM3|05|FM3_DATAGR|D|8|0|DT Agrupador|Data Agrupador
FM3|06|FM3_HORAGR|C|5|0|Hora Agrupad|Hora do Agrupador
FM3|07|FM3_SITUAC|C|1|0|Situação|Situação do Agrupador
FM3|08|FM3_DATAIN|D|8|0|Data Inicial|Data Inicial
FM3|09|FM3_DATAFI|D|8|0|Data Fim|Data Final
--- ### FM4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FM4|01|FM4_FILIAL|C|6|0|Filial|Filial do Sistema
FM4|02|FM4_CBASE|C|10|0|Cod Bem|Código do Bem
FM4|03|FM4_ITEM|C|4|0|Item|Numero do Item
FM4|04|FM4_CHAPA|C|20|0|Num.Plaqueta|Número Plaqueta
FM4|05|FM4_QUANTD|N|11|3|Qunatidade|Quantidade
FM4|06|FM4_DESCR|C|40|0|Descrição|Descrição
FM4|07|FM4_GRUPO|C|4|0|Grupo|Grupo
FM4|08|FM4_LOCAL|C|6|0|Endereço|Endereço
FM4|09|FM4_CODIGO|C|9|0|Codigo|Código do Agrupador
FM4|10|FM4_TIPO|C|2|0|Tipo|Tipo do Bem
FM4|11|FM4_FILORI|C|6|0|Fil Orig Ati|Filial Origem do Ativo
--- ### FM5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FM5|01|FM5_FILIAL|C|6|0|Filial|Filial do Sistema
FM5|02|FM5_CBASE|C|10|0|Cod Base Bem|Codigo Base do Bem
FM5|03|FM5_ITEM|C|4|0|Codigo Item|Codigo do Item do Bem
FM5|04|FM5_TIPO|C|2|0|Tipo Ativo|Tipo Ativo
FM5|05|FM5_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FM5|06|FM5_MOEDA|C|2|0|Moeda|Moeda do registro
FM5|07|FM5_DATA|D|8|0|Data|Data Alteração
FM5|08|FM5_HORA|C|8|0|Hora|Hora Alteração
FM5|09|FM5_TXORI|N|9|4|Taxa Origem|Taxa Origem
FM5|10|FM5_TXDES|N|9|4|Taxa Destino|Taxa Destino
FM5|11|FM5_USER|C|50|0|Usuario|Usuario Alteração Taxa
FM5|12|FM5_OBS|M|255|0|Obs. Hist.|Observacao Historico
--- ### FN0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN0|01|FN0_FILIAL|C|6|0|Filial|Filial do Sistema
FN0|02|FN0_CBASE|C|10|0|Cod.Base Bem|Código de Base do Bem
FN0|03|FN0_ITEM|C|4|0|Item Bem|Código Item da Base Bem
FN0|04|FN0_NFISCA|C|9|0|Documento|Documento Vinc. Base Bem
FN0|05|FN0_NSERIE|C|3|0|Serie|Serie Doc.Vinc.Base Bem
FN0|06|FN0_FORNEC|C|6|0|Fornecedor|Fornecedor Vinc. Base Bem
FN0|07|FN0_LOJA|C|2|0|Loja Fornec.|Loja do Fornecedor
FN0|08|FN0_CODPRO|C|15|0|Cod.Produto|Código do Produto
FN0|09|FN0_ITEMPR|C|4|0|Item Produto|Item do produto
FN0|10|FN0_TES|C|3|0|Tipo Entrada|Tipo de Entrada
FN0|11|FN0_TOTAL|N|14|2|Vlr.Total|Valor Total Nota Fiscal
FN0|12|FN0_ICMS|N|14|2|ICMS|Valor do ICMS
FN0|13|FN0_ESPECI|C|5|0|Espec.Docum.|Especie Documento
FN0|14|FN0_TIPDOC|C|1|0|Tipo da Nota|Tipo da Nota
FN0|15|FN0_IDTRIB|C|36|0|ID Tributos|ID dos Tributos
--- ### FN1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN1|01|FN1_FILIAL|C|6|0|Filial|Filial do Sistema
FN1|02|FN1_PROC|C|10|0|Cod Processo|Codigo do Processo
FN1|03|FN1_DATA|D|8|0|Data Proc|Data do processamento
FN1|04|FN1_DESC|C|40|0|Descricao|Descricao do processo
FN1|05|FN1_STATUS|C|1|0|Status|Status do Processo
FN1|06|FN1_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FN1|07|FN1_USERGA|C|17|0|Log de Alter|Log de Alteracao
FN1|08|FN1_TIPO|C|1|0|Tipo|Tipo do Processo
--- ### FN2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN2|01|FN2_FILIAL|C|6|0|Filial|FIlial do Sistema
FN2|02|FN2_PROC|C|10|0|Cod Processo|Codigo do processamento
FN2|03|FN2_LINHA|C|6|0|Linha|Linha de Conf Contrato
FN2|04|FN2_IDCONT|C|20|0|ID Contrato|Identificador Contrato
FN2|05|FN2_DESC|C|40|0|Descricao|Descricao Contrato
FN2|06|FN2_VLRCON|N|16|2|Vlr Contrato|Valor do Contrato
FN2|07|FN2_VLRSAL|N|16|2|Saldo Cont|Saldo do Contrato
FN2|08|FN2_JURCOM|N|16|2|Juros Compet|Juros Competencia
--- ### FN3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN3|01|FN3_FILIAL|C|6|0|Filial|Filial do Sistema
FN3|02|FN3_PROC|C|10|0|Cod Processo|Codigo do processamento
FN3|03|FN3_LINHA|C|6|0|Linha|Linha Conf Transac
FN3|04|FN3_CBASE|C|10|0|C Base Trans|C Base Custo Transacao
FN3|05|FN3_ITEM|C|4|0|Item Transac|Item Custo Transacao
FN3|06|FN3_TIPO|C|2|0|Tipo|Tipo de Bem
FN3|07|FN3_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FN3|08|FN3_DESC|C|40|0|Descricao|Descrição da Amortizacao
FN3|09|FN3_AMORT|N|16|2|Vlr Amort|Valor Amortização
--- ### FN4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN4|01|FN4_FILIAL|C|6|0|Filial|Filial do Sistema
FN4|02|FN4_PROC|C|10|0|Cod Processo|Codigo do Processo
FN4|03|FN4_LINHA|C|6|0|Linha|Linha Cfg Rendimento
FN4|04|FN4_DESC|C|40|0|Descricao|Descricao Rendimento
FN4|05|FN4_VALOR|N|16|2|Valor Rendim|Valor do Rendimento
--- ### FN5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN5|01|FN5_FILIAL|C|6|0|Filial|Filial do Sistema
FN5|02|FN5_PROC|C|10|0|Cod Processo|Codigo do Processamento
FN5|03|FN5_LINHA|C|6|0|Linha|Linha Conf Fichas Custo
FN5|04|FN5_CBAORI|C|10|0|C Base Orig|Código Base Origem
FN5|05|FN5_ITEORI|C|4|0|Item Origem|Item Origem
FN5|06|FN5_TIPORI|C|2|0|Tipo de orig|Tipo Atf Original
FN5|07|FN5_SLDORI|C|1|0|Tp Sld Ori|Tipo de saldo Original
FN5|08|FN5_VLRORI|N|16|2|Valor Origem|Valor Original Moeda 01
FN5|09|FN5_CBACEM|C|10|0|C Base Emp|Cod Base do Custo de Emp
FN5|10|FN5_ITECEM|C|4|0|Item Cust Em|Item do Custo de Emp
FN5|11|FN5_TIPEMP|C|2|0|Tipo C Emp|Tipo da ficha de custo
FN5|12|FN5_SLDEMP|C|1|0|Tp Sld Emp|Tp saldo do custo emp
FN5|13|FN5_GRPCEM|C|4|0|Grupo|Grupo Custo Emp
FN5|14|FN5_TXCAP|N|12|8|Taxa Cap|Taxa de capitalização
FN5|15|FN5_VLRAPR|N|16|2|Valor Aprop|Valor da Apropriacao
--- ### FN6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN6|01|FN6_FILIAL|C|6|0|FIlial|Filial do Sistema
FN6|02|FN6_CODBX|C|10|0|Cod. Baixa|Codigo da baixa
FN6|03|FN6_CBASE|C|10|0|Cod. Bem|Código Base do bem
FN6|04|FN6_CITEM|C|4|0|Item|Código do Item do Bem
FN6|05|FN6_DESCRI|C|40|0|Descrição|Descrição do Bem
FN6|06|FN6_DTBAIX|D|8|0|Dt. Baixa|Data da baixa
FN6|07|FN6_BAIXA|N|6|2|% Baixa|% para baixa
FN6|08|FN6_QTDATU|N|11|3|Qtd. Atual|Quantidade atual do bem
FN6|09|FN6_QTDBX|N|11|3|Qtd. Baixa|Quantidade da baixa
FN6|10|FN6_PERCBX|N|6|2|% Baixado|% Quantidade baixada
FN6|11|FN6_MOTIVO|C|2|0|Motivo|Motivo da Baixa
FN6|12|FN6_DEPREC|C|1|0|Depreciar|Depreciar na baixa?
FN6|13|FN6_GERANF|C|1|0|Gerar NF|Gerar NF de Saída?
FN6|14|FN6_NUMNF|C|9|0|Num. NF|Número da NF
FN6|15|FN6_SERIE|C|3|0|Série|Série da NF
FN6|16|FN6_LOTE|C|10|0|Lote|Lote da baixa
FN6|17|FN6_ITEMNF|C|4|0|It. Nf Saida|Item da Nf de Saída
FN6|18|FN6_STATUS|C|1|0|Status|Status da baixa
FN6|19|FN6_FILORI|C|6|0|Filial Orig.|Filial de origem
FN6|20|FN6_CLIENT|C|6|0|Cliente|Cliente p/ NF de Saída
FN6|21|FN6_LOJA|C|2|0|Loja|Loja do Cliente
FN6|22|FN6_VALNF|N|16|2|Valor NF/Ven|Valor NF/Valor de Venda
FN6|23|FN6_CNDPAG|C|3|0|Cond. Pagto.|Condição de pagto da NF
FN6|24|FN6_TESSAI|C|3|0|TES Saída|Tipo de Saída para a NF
FN6|25|FN6_NATURE|C|10|0|Natureza|Natureza
FN6|26|FN6_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
FN6|27|FN6_TRANSP|C|6|0|Transp.|Codigo da Transportadora
FN6|28|FN6_TPFRET|C|1|0|Tipo Frete|Tipo do Frete Utilizado
FN6|29|FN6_PESOL|N|11|4|Peso Liquido|Peso Liquido
FN6|30|FN6_PBRUTO|N|11|4|Peso Bruto|Peso Bruto
FN6|31|FN6_VOLUM1|N|5|0|Volume 1|Qtde de Volumes tipo 1
FN6|32|FN6_ESPEC1|C|10|0|Especie 1|Especie do Volume tipo 1
FN6|33|FN6_VEICU1|C|8|0|Veiculo 1|Veiculo do Transporte 1
FN6|34|FN6_ESPECI|C|5|0|Espécie NF|Espécie Nota Fiscal
--- ### FN7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN7|01|FN7_FILIAL|C|6|0|Filial|Filial do Sistema
FN7|02|FN7_CODBX|C|10|0|Cod. Baixa|Codigo da Baixa
FN7|03|FN7_ITEM|C|3|0|Item|Item da Baixa
FN7|04|FN7_CBASE|C|10|0|Cod. Bem|Código base do bem
FN7|05|FN7_CITEM|C|4|0|Item do bem|Código do item do bem
FN7|06|FN7_TIPO|C|2|0|Tipo Ativo|Tipo do Ativo
FN7|07|FN7_DESCRI|C|40|0|Descrição|Descrição do Bem
FN7|08|FN7_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FN7|09|FN7_SEQ|C|3|0|Seq. Aquisic|Sequencia de Aquisição
FN7|10|FN7_MOEDA|C|2|0|Moeda|Moeda
FN7|11|FN7_SEQREA|C|2|0|Seq. Reaval|Seq de Reavaliação do Bem
FN7|12|FN7_MOTIVO|C|2|0|Motivo|Motivo da Baixa
FN7|13|FN7_DTBAIX|D|8|0|Dt. Baixa|Data da Baixa
FN7|14|FN7_VLATU|N|16|2|Vl. Atual|Valor Atual
FN7|15|FN7_VLDEPR|N|16|2|Vl.Deprec|Valor da depreciacao
FN7|16|FN7_VLRESI|N|16|2|Vlr Residual|Valor Residual
FN7|17|FN7_PERCBX|N|6|2|% Baixado|Percentual de Baixa
FN7|18|FN7_VLBAIX|N|16|2|Vl.Baixa|Valor da Baixa
FN7|19|FN7_STATUS|C|1|0|Status|Status da baixa
FN7|20|FN7_FILORI|C|6|0|Filial Orig.|Filial de origem
--- ### FN8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN8|01|FN8_FILIAL|C|6|0|Filial|Filial do Sistema
FN8|02|FN8_LOTE|C|10|0|Lote|Lote de Baixa
FN8|03|FN8_MOTIVO|C|2|0|Motivo|Motivo da Baixa
FN8|04|FN8_BAIXA|N|6|2|% Baixa|% para Baixa
FN8|05|FN8_DTBAIX|D|8|0|Dt. Baixa|Data da Baixa
FN8|06|FN8_DEPREC|C|1|0|Depreciar|Depreciar na Baixa?
FN8|07|FN8_STATUS|C|1|0|Status|Status da Baixa
FN8|08|FN8_GERANF|C|1|0|Gerar NF|Gerar NF de Saída?
FN8|09|FN8_NUMNF|C|9|0|Num NF|Número da NF
FN8|10|FN8_SERIE|C|3|0|Série|Série da NF
FN8|11|FN8_CLIENT|C|6|0|Cliente|Cliente p/ NF de Saída
FN8|12|FN8_LOJA|C|2|0|Loja|Loja do Cliente
FN8|13|FN8_VALNF|N|16|2|Valor NF|Valor da NF
FN8|14|FN8_CNDPAG|C|3|0|Cond. Pagto.|Condição de pagto da NF
FN8|15|FN8_TESSAI|C|3|0|TES Saída|Tipo de Saída para a NF
FN8|16|FN8_NATURE|C|10|0|Natureza|Natureza
FN8|17|FN8_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
FN8|18|FN8_TRANSP|C|6|0|Transp.|Codigo da Transportadora
FN8|19|FN8_TPFRET|C|1|0|Tipo Frete|Tipo do Frete Utilizado
FN8|20|FN8_PESOL|N|11|4|Peso Liquido|Peso Liquido
FN8|21|FN8_PBRUTO|N|11|4|Peso Bruto|Peso Bruto
FN8|22|FN8_VOLUM1|N|5|0|Volume 1|Qtde de Volumes Tipo 1
FN8|23|FN8_ESPEC1|C|10|0|Especie 1|Especie do Volume Tipo 1
FN8|24|FN8_VEICU1|C|8|0|Veiculo 1|Veiculo do Transporte 1
FN8|25|FN8_ESPECI|C|5|0|Espécie NF|Espécie da Nota Fiscal
--- ### FN9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FN9|01|FN9_FILIAL|C|6|0|Filial|Filial do Sistema
FN9|02|FN9_IDMOV|C|6|0|ID do Mov.|ID do Movimento
FN9|03|FN9_DATA|D|8|0|Data do Mov.|Data do Movimento
FN9|04|FN9_FILDES|C|6|0|Filial Dest.|Filial de Destino
FN9|05|FN9_GRPDES|C|4|0|Grupo Dest.|Grupo de Destino
FN9|06|FN9_LOCDES|C|6|0|Local Dest.|Local Destino do Bem
FN9|07|FN9_TXPADD|C|6|0|Cod Tx Pad D|Cod. da Taxa Padrão Dest.
FN9|08|FN9_CCDESD|C|9|0|CC Desp Dest|C Custo Despesa Destino
FN9|09|FN9_CONTAD|C|20|0|Ct Bem Dest|Conta do Bem de Destino
FN9|10|FN9_CONCOD|C|20|0|Ct Cor Mon D|Conta Corr. Monet. Dest.
FN9|11|FN9_CONDDD|C|20|0|Ct Des Dep D|Conta Desp. Deprec. Dest.
FN9|12|FN9_CONDAD|C|20|0|Ct Dep Acu D|Conta Deprec Acumul Dest
FN9|13|FN9_CONCDD|C|20|0|Ct Cor Dep D|Conta Corr. Deprec. Dest.
FN9|14|FN9_CCBEMD|C|9|0|CC Bem Dest|C Custo do Bem Destino
FN9|15|FN9_CCCORD|C|9|0|CC Cor Mon D|C Custo Corr Monet Dest
FN9|16|FN9_CCDDD|C|9|0|CC Des Dep D|C Custo Desp Deprec Dest
FN9|17|FN9_CCDAD|C|9|0|CC Dep Acu D|C Custo Deprec Acumul Des
FN9|18|FN9_CCCDD|C|9|0|CC Cor Dep D|C Custo Corr Deprec Dest
FN9|19|FN9_ITBEMD|C|9|0|It Bem Dest|Item Contábil do Bem Dest
FN9|20|FN9_ITCORD|C|9|0|It Cor Mon D|Item Corr. Monet. Dest.
FN9|21|FN9_ITDEDD|C|9|0|It Des Dep D|Item Desp. Deprec. Dest.
FN9|22|FN9_ITDEAD|C|9|0|It Dep Acu D|Item Deprec Acumul Dest
FN9|23|FN9_ITCDED|C|9|0|It Cor Dep D|Item Corr. Deprec. Dest.
FN9|24|FN9_CVBEMD|C|9|0|CV Bem Dest|Classe de Val do Bem Dest
FN9|25|FN9_CVCORD|C|9|0|CV Cor Mon D|Cl Vl Corr. Monet. Dest.
FN9|26|FN9_CVDEPD|C|9|0|CV Des Dep D|Cl Vl Desp. Deprec. Dest.
FN9|27|FN9_CVCDED|C|9|0|CV Dep Acu D|Cl Vl Deprec Acumul Dest
FN9|28|FN9_CVDESD|C|9|0|CV Cor Dep D|Cl Vl Corr. Deprec. Dest.
FN9|29|FN9_GERNF|C|1|0|Gera NF|Gera Nota Fiscal
FN9|30|FN9_SERIE|C|3|0|Serie|Serie da Nota Fiscal
FN9|31|FN9_CLSNF|C|1|0|Class NF|Classificação NF
FN9|32|FN9_TESSAI|C|3|0|TES Saída|TES de Saída
FN9|33|FN9_TESENT|C|3|0|TES Entrada|TES de Entrada
FN9|34|FN9_VALNF|N|14|2|Valor da NF|Valor da Nota Fiscal
FN9|35|FN9_QTDDES|N|11|3|Quant. Dest.|Quantidade Destino
FN9|36|FN9_ESPECI|C|5|0|Espécie NF|Espécie Nota Fiscal Ent
FN9|37|FN9_ARMAZE|C|2|0|Armazem|Armazem Estoque Destino
FN9|38|FN9_ITDESD|C|9|0|IT Desp Dest|Item Despesa Dest
FN9|39|FN9_CVDSPD|C|9|0|CV Desp Dest|Classe de Val Desp Dest
FN9|40|FN9_TRANSP|C|6|0|Transp.|Codigo da Transportadora
FN9|41|FN9_TPFRET|C|1|0|Tipo Frete|Tipo do Frete Utilizado
FN9|42|FN9_PESOL|N|11|4|Peso Liquido|Peso Liquido
FN9|43|FN9_PBRUTO|N|11|4|Peso Bruto|Peso Bruto
FN9|44|FN9_VOLUM1|N|5|0|Volume 1|Qtde de Volumes tipo 1
FN9|45|FN9_ESPEC1|C|10|0|Especie 1|Especie do Volume tipo 1
FN9|46|FN9_VEICU1|C|8|0|Veiculo 1|Veiculo do Transporte 1
--- ### FNA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNA|01|FNA_FILIAL|C|6|0|Filial|Filial do Sistema
FNA|02|FNA_IDMOV|C|10|0|ID Movto.|Identificação movimento
FNA|03|FNA_ITMOV|C|6|0|Item Movto.|Item do movimento
FNA|04|FNA_CBASE|C|10|0|Código Base|Código Base do Bem
FNA|05|FNA_ITEM|C|4|0|Item|Item do Bem
FNA|06|FNA_DESCRI|C|40|0|Descr. Sint.|Descricao Sintetica
FNA|07|FNA_TIPO|C|2|0|Tipo|Tipo do Bem
FNA|08|FNA_SEQ|C|3|0|Sequência|Sequência do Tipo do Bem
FNA|09|FNA_SEQREA|C|2|0|Seq. Reav.|Seq. de Reav. Tipo do Bem
FNA|10|FNA_TPSALD|C|1|0|Tipo saldo|Tipo de saldo
FNA|11|FNA_TPDEPR|C|1|0|Mtd. Deprec.|Método de Depreciação
FNA|12|FNA_DATA|D|8|0|Data Movto.|Data da movimentação
FNA|13|FNA_OCORR|C|2|0|Ocorrência|Ocorrência do movimento
FNA|14|FNA_DTPERI|D|8|0|Dt. Per. Ini|Data do período inicial
FNA|15|FNA_DTPERF|D|8|0|Dt. Per. Fim|Data do período final
FNA|16|FNA_QUANTD|N|16|2|Quantidade|Quantidade do apontamento
FNA|17|FNA_COEFIC|N|16|8|Coef. Exaust|Coeficiente de exaustão
FNA|18|FNA_MOEDA|C|2|0|Moeda|Moeda da movimentação
FNA|19|FNA_VALOR|N|16|2|Valor|Valor da movimentação
FNA|20|FNA_ESTORN|C|1|0|Estornado?|Apontamento Estornado?
--- ### FNB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNB|01|FNB_FILIAL|C|6|0|Filial|Filial do Sistema
FNB|02|FNB_CODPRJ|C|10|0|Codigo|Codigo do Projeto
FNB|03|FNB_REVIS|C|4|0|Revisao|Revisao de Projeto
FNB|04|FNB_DESC|C|40|0|Descricao|Descricao do Projeto
FNB|05|FNB_TIPO|C|1|0|Tipo|Tipo do Projeto
FNB|06|FNB_SBTIPO|C|1|0|Sub-Tipo|Sub-Tipo do Projeto
FNB|07|FNB_INDAVP|C|2|0|Indice AVP|Indice para calculo AVP
FNB|08|FNB_MRGREC|C|1|0|Margem Rec.?|Controla margem receita?
FNB|09|FNB_MOEDA|C|2|0|Moeda|Moeda de controle do prj.
FNB|10|FNB_CBASE|C|10|0|Cod Base ATF|Codigo base dos Ativos
FNB|11|FNB_DTINIC|D|8|0|Inicio Prj|Data de Inicio do Projeto
FNB|12|FNB_STATUS|C|1|0|Status|Status do projeto
FNB|13|FNB_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FNB|14|FNB_CODPMS|C|10|0|Projeto PMS|Codigo do projeto PMS
FNB|15|FNB_EDTPMS|C|12|0|EDT PMS|EDT do projeto PMS
FNB|16|FNB_DTENCR|D|8|0|Dt Encerram|Data de encerramento
FNB|17|FNB_LOCPRJ|C|6|0|Local Prj|Local do Projeto
FNB|18|FNB_DTREV|D|8|0|Dt Revisao|Data de revisão
FNB|19|FNB_DTPROV|D|8|0|Inicio Prov|Data de Inicio da Prov
FNB|20|FNB_PRVEXC|D|8|0|Dt.Prev.Exec|Data de previsao de exec
FNB|21|FNB_TPAVP|C|1|0|Tipo AVP|Tipo de AVP
--- ### FNC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNC|01|FNC_FILIAL|C|6|0|Filial|Filial do Sistema
FNC|02|FNC_CODPRJ|C|10|0|Projeto|Codigo do Projeto
FNC|03|FNC_REVIS|C|4|0|Revisao|Revisao do projeto
FNC|04|FNC_ETAPA|C|3|0|Etapa|Etapa do projeto
FNC|05|FNC_DSCETP|C|40|0|Desc Etapa|Descricao da etapa
FNC|06|FNC_TIPO|C|1|0|Tipo|Tipo do Item da etapa
FNC|07|FNC_SBTIPO|C|1|0|Sub-Tipo|Sub-Tipo da Etapa
FNC|08|FNC_INDAVP|C|2|0|Indice AVP|Indice AVP da Etapa
FNC|09|FNC_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FNC|10|FNC_CODPMS|C|10|0|Projeto PMS|Codigo do projeto PMS
FNC|11|FNC_EDTPMS|C|12|0|EDT PMS|EDT do projeto PMS
FNC|12|FNC_STATUS|C|1|0|Status|Status da Etapa
FNC|13|FNC_DTENCR|D|8|0|Dt Encerram|Data de encerramento
FNC|14|FNC_DTPROV|D|8|0|Inicio Prov|Data de Inicio da Provis
FNC|15|FNC_PRVEXC|D|8|0|Dt.Prev.Exec|Data de previsao de exec
FNC|16|FNC_TPAVP|C|1|0|Tipo AVP|Tipo de AVP
--- ### FND
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FND|01|FND_FILIAL|C|6|0|Filial|Filial do Sistema
FND|02|FND_CODPRJ|C|10|0|Projeto|Codigo do Projeto
FND|03|FND_REVIS|C|4|0|Revisao|Revisao do projeto
FND|04|FND_ETAPA|C|3|0|Etapa|Etapa do projeto
FND|05|FND_ITEM|C|3|0|Item|Item da Etapa
FND|06|FND_DSCITE|C|40|0|Desc.Item|Descricao item da etapa
FND|07|FND_TIPO|C|1|0|Tipo|Tipo do item da etapa
FND|08|FND_CTRATF|C|1|0|Contrl Atf|Controla Ativo?
FND|09|FND_SBTIPO|C|1|0|Sub-tipo|Sub-tipo do item da etapa
FND|10|FND_DTPROV|D|8|0|Inicio Prov|Data de Inicio da Provis
FND|11|FND_PERINI|D|8|0|Periodo ini|Periodo inicial do item
FND|12|FND_PERFIM|D|8|0|Periodo fim|Periodo final da etapa
FND|13|FND_PRVEXC|D|8|0|Dt.Prev.Exec|Data de previsao de exec
FND|14|FND_INDAVP|C|2|0|Indice AVP|Indice de AVP do item
FND|15|FND_VLRPLN|N|16|2|Vlr. Planej|Valor planejado do item
FND|16|FND_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FND|17|FND_CODPMS|C|10|0|Projeto PMS|Codigo do projeto PMS
FND|18|FND_EDTPMS|C|12|0|EDT PMS|EDT do projeto PMS
FND|19|FND_DTENCR|D|8|0|Dt.Encerram|Data de encerramento
FND|20|FND_STATUS|C|1|0|Status|Status Item da Etapa
FND|21|FND_TPAVP|C|1|0|Tipo AVP|Tipo de AVP
--- ### FNE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNE|01|FNE_FILIAL|C|6|0|Filial|Filial do Sistema
FNE|02|FNE_CODPRJ|C|10|0|Projeto|Codigo do projeto
FNE|03|FNE_REVIS|C|4|0|Revisao|Revisao do projeto
FNE|04|FNE_ETAPA|C|3|0|Etapa|Etapa do projeto
FNE|05|FNE_ITEM|C|3|0|Item Etapa|Item Etapa
FNE|06|FNE_ITVIRT|C|3|0|Item|Item Virtual
FNE|07|FNE_LINHA|C|3|0|Linha|Linha configuracao Etapa
FNE|08|FNE_TPCLAS|C|1|0|Tipo Classif|Tipo da classificacao
FNE|09|FNE_TPATF|C|2|0|Tipo ATF|Tipo de ativo
FNE|10|FNE_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FNE|11|FNE_TPDEPR|C|1|0|Tipo Deprec|Metodo de depreciacao
FNE|12|FNE_DINDEP|D|8|0|Dt In Deprec|Data de Inicio Deprec
FNE|13|FNE_VORIG|N|16|2|Vlr.Original|Valor original do item
FNE|14|FNE_VRDACM|N|16|2|Vlr. Dep Acm|Valor Dep Acm do item
FNE|15|FNE_AVPPLN|N|16|2|AVP Planejad|AVP planejado do item
FNE|16|FNE_AVPRLZ|N|16|2|AVP Realiz|AVP realizado do item
FNE|17|FNE_VLRRLZ|N|16|2|Vlr. Realiz|Valor realizado do item
FNE|18|FNE_GRPBEM|C|4|0|Grupo Bem|Grupo de bens
FNE|19|FNE_ENT01B|C|20|0|Conta Bem|Entidade do bem conta
FNE|20|FNE_ENT02B|C|9|0|C Custo Bem|Entidade do bem c.custo
FNE|21|FNE_ENT03B|C|9|0|Item Ctb Bem|Entidade do bem item ctb
FNE|22|FNE_ENT04B|C|9|0|Class Vl Bem|Entidade do bem classe
FNE|23|FNE_ENT01D|C|20|0|Conta Desp|Entidade despesa conta
FNE|24|FNE_ENT02D|C|9|0|C Custo Desp|Entidade despesa c.cust
FNE|25|FNE_ENT03D|C|9|0|It Ctb Desp|Entidade despesa item
FNE|26|FNE_ENT04D|C|9|0|Classe Desp|Entidade despesa classe
FNE|27|FNE_ENT01A|C|20|0|Conta Dep Ac|Entidade depr.acm conta
FNE|28|FNE_ENT02A|C|9|0|CC Dep Acm|Entidade depr.acm c.custo
FNE|29|FNE_ENT03A|C|9|0|Item Dep Acm|Entidade depr.acm item
FNE|30|FNE_ENT04A|C|9|0|Cl Vl Dep Ac|Entidade depr.acm classe
FNE|31|FNE_CALCDE|C|1|0|Calc.Depr.|Periodicidade do calculo
FNE|32|FNE_PERDEP|N|4|0|Per. Depr.|Periodos de Depreciacao
FNE|33|FNE_TAXA|N|6|2|Tx. Depr.|Taxa anual de depreciacao
FNE|34|FNE_CRIDEP|C|1|0|Crit. Depr.|Criterio de Depreciacao
FNE|35|FNE_CALDEP|C|15|0|Calendario|Calendario de depreciacao
FNE|36|FNE_MOEDRF|C|2|0|Moeda Ref.|Moeda de referencia
FNE|37|FNE_VLMXDP|N|16|2|Vlr Max Dep|Valor maximo de deprec
FNE|38|FNE_VLSALV|N|16|2|V Salvamento|Valor de salvamento
FNE|39|FNE_PRDEST|N|16|2|Prd Estimada|Producao estimada
FNE|40|FNE_CODIND|C|2|0|Índ.calculo|Codigo do indice de depr.
FNE|41|FNE_USRAVP|C|20|0|Usuário AVP|Usuário alteracao AVP
--- ### FNF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNF|01|FNF_FILIAL|C|6|0|Filial|Filial do Sistema
FNF|02|FNF_CBASE|C|10|0|Cod. do Bem|Codigo Base do Bem
FNF|03|FNF_ITEM|C|4|0|Item|Numero do Item
FNF|04|FNF_TIPO|C|2|0|Tipo Bem|Tipo de Bem
FNF|05|FNF_SEQ|C|3|0|Seq.Item ATF|Sequenc. do Item do Ativo
FNF|06|FNF_TPSALD|C|1|0|Tp Sld Item|Tipo Saldo Item do Ativo
FNF|07|FNF_REVIS|C|4|0|Revisao|Revisao do AVP
FNF|08|FNF_SEQAVP|C|4|0|Sequencia|Sequencia do AVP
FNF|09|FNF_TPMOV|C|1|0|Tp. Movto.|Tipo Movto. AVP
FNF|10|FNF_DTAVP|D|8|0|Data Movto|Data do Movimento
FNF|11|FNF_INDAVP|C|2|0|Indice AVP|Indice do Movto AVP
FNF|12|FNF_PERIND|C|1|0|Periodic.|Periodicidade do Indice
FNF|13|FNF_TAXA|N|14|8|Taxa indice|Taxa do indice
FNF|14|FNF_VALOR|N|16|2|Valor Movto|Valor do Movimento
FNF|15|FNF_BASE|N|16|2|Base Calculo|Base de calculo do Movto.
FNF|16|FNF_ENT01|C|20|0|Cta. Bem|Conta contabil do bem
FNF|17|FNF_ENT02|C|9|0|C.Custo Bem|Centro de Custo do bem
FNF|18|FNF_ENT03|C|9|0|Item Cta.Bem|Item Contabil do Bem
FNF|19|FNF_ENT04|C|9|0|CLVL Bem|Classe de valor do bem
FNF|20|FNF_STATUS|C|1|0|Status|Status da config. AVP
FNF|21|FNF_MSBLQL|C|1|0|Bloqueado|Bloqueia configuracao
FNF|22|FNF_MOEDA|C|2|0|Moeda AVP|Moeda do AVP
FNF|23|FNF_DTCONT|D|8|0|Dt.Contabil|Data Contabilizacao
FNF|24|FNF_ACMAVP|N|16|2|AVP Acumulad|AVP Acumulado
FNF|25|FNF_AVPVLP|N|16|2|Vlr.Presente|Valor presente do bem
FNF|26|FNF_IDPROC|C|20|0|Id.Proc.AVP|ID do processo de AVP
FNF|27|FNF_IDPRCP|C|20|0|Id.Proc.Pai|ID do processo pai de AVP
FNF|28|FNF_IDMVAF|C|10|0|Id.Movt.ATF|ID do movimento ATF
FNF|29|FNF_DTEXEC|D|8|0|Dt. Execucao|Data Prevista de Execucao
FNF|30|FNF_LA|C|1|0|Ident. Lanc.|Identificador de LA
FNF|31|FNF_ORIGEM|C|8|0|Origem|Origem do Movimento
FNF|32|FNF_LP|C|6|0|Lanc Pad.|Lançamento Padrão
--- ### FNG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNG|01|FNG_FILIAL|C|6|0|Filial|Filial de Sistema
FNG|02|FNG_GRUPO|C|4|0|Grupo Bens|Codigo do Grupo de Bens
FNG|03|FNG_TIPO|C|2|0|Tipo Ativo|Tipo de Ativo
FNG|04|FNG_HISTOR|C|40|0|Historico|Historico do Valor
FNG|05|FNG_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FNG|06|FNG_TPDEPR|C|1|0|Tipo Deprec|Tipo de Depreciacao
FNG|07|FNG_TXDEP1|N|9|4|Tx.An.Depr1|Taxa Anual Depreciacao 1
FNG|08|FNG_TXDEP2|N|9|4|Tx.An.Depr2|Taxa Anual Depreciacao 2
FNG|09|FNG_TXDEP3|N|9|4|Tx.An.Depr3|Taxa Anual Depreciacao 3
FNG|10|FNG_TXDEP4|N|9|4|Tx.An.Depr4|Taxa Anual Depreciacao 4
FNG|11|FNG_TXDEP5|N|9|4|Tx.An.Depr5|Taxa Anual Depreciacao 5
FNG|12|FNG_ATFCPR|C|1|0|Atf.Custo/Pr|Ativo de Custo/Provisão
--- ### FNH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNH|01|FNH_FILIAL|C|6|0|Filial|Filial do Sistema
FNH|02|FNH_ROTINA|C|10|0|Rotina|Rotina do ambiente
FNH|03|FNH_DESCRT|C|20|0|Desc. Rotina|Descrição da rotina
FNH|04|FNH_OPER|C|2|0|Operação|Operação da rotina
FNH|05|FNH_DESCOP|C|20|0|Desc. Opera.|Descrição da operação
FNH|06|FNH_STATUS|C|1|0|Status|Status controle operação
--- ### FNI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNI|01|FNI_FILIAL|C|6|0|Filial|Filial do Sistema
FNI|02|FNI_CODIND|C|2|0|Cod.Índice|Código do Índice
FNI|03|FNI_REVIS|C|4|0|Revisão|Revisão do Indice
FNI|04|FNI_DSCIND|C|20|0|Descrição|Descrição do índice
FNI|05|FNI_PERIOD|C|1|0|Período|Periodicidade do Índice
FNI|06|FNI_MSBLQL|C|1|0|Bloqueado|Registro Bloqueado
FNI|07|FNI_TIPO|C|1|0|Tipo|Tipo do Indice
FNI|08|FNI_CURVIN|D|8|0|Ini Curva|Inicio Curva Demanda
FNI|09|FNI_CURVFI|D|8|0|Fim Curva|Fim Curva Demanda
FNI|10|FNI_DTREV|D|8|0|Dt Revis|Data Revis Curva Demanda
FNI|11|FNI_STATUS|C|1|0|Status|Status do Indice Deprec
--- ### FNJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNJ|01|FNJ_FILIAL|C|6|0|Filial|Filial do Sistema
FNJ|02|FNJ_CODPRJ|C|10|0|Projeto|Codigo do projeto
FNJ|03|FNJ_REVIS|C|4|0|Revisao|Revisao do projeto
FNJ|04|FNJ_ETAPA|C|3|0|Etapa|Etapa do projeto
FNJ|05|FNJ_ITEM|C|3|0|Item Etapa|Item da Etapa
FNJ|06|FNJ_LINHA|C|3|0|Linha|Linha configuracao Etapa
FNJ|07|FNJ_TAFPRJ|C|2|0|Tipo ATF Prj|Tipo de ativo Projeto
FNJ|08|FNJ_SLDPRJ|C|1|0|Tipo Sld Prj|Tipo de Saldo Projeto
FNJ|09|FNJ_ITRELA|C|3|0|Item Relac|Item do Relacionamento
FNJ|10|FNJ_CBAEXE|C|10|0|C Base Exec|Código Base  Execução
FNJ|11|FNJ_ITEXE|C|4|0|Item Exec|Item Execução
FNJ|12|FNJ_TAFEXE|C|2|0|Tipo ATF Exe|Tipo de ativo Execução
FNJ|13|FNJ_SLDEXE|C|1|0|Tipo SLD Exe|Tipo de Saldo Execução
FNJ|14|FNJ_VLREXE|N|16|2|Valor Exec|Valor Execução
FNJ|15|FNJ_DTCONT|D|8|0|Data Contab|Data Contabilização
--- ### FNK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNK|01|FNK_FILIAL|C|6|0|Filial|Filial do Sistema
FNK|02|FNK_ROTINA|C|10|0|Rotina|Rotina do Ambiente
FNK|03|FNK_DESCRT|C|20|0|Desc.Rotina|Descrição da rotina
FNK|04|FNK_REVIS|C|4|0|Revisão|Revisão da alçada
FNK|05|FNK_STATUS|C|1|0|Status|Status controle operacao
--- ### FNL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNL|01|FNL_FILIAL|C|6|0|Filial|Filial do Sistema
FNL|02|FNL_ROTINA|C|10|0|Rotina|Rotina do ambiente
FNL|03|FNL_REVIS|C|4|0|Revisão|revisão da alçada
FNL|04|FNL_STATUS|C|1|0|Status|Status controle operacao
FNL|05|FNL_OPER|C|2|0|Operação|Operação da rotina
FNL|06|FNL_DESCOP|C|20|0|Desc.Oper.|Descrição da operação
FNL|07|FNL_TIPO|C|1|0|Tipo Alçada|Tipo controle de alçada
FNL|08|FNL_CODAPR|C|6|0|Aprovador|Codigo do Aprovador
FNL|09|FNL_NOMAPR|C|25|0|Nome Aprov|Nome do aprovador
FNL|10|FNL_PERIOD|C|1|0|Per.Alçada|Periodicidade da alçada
FNL|11|FNL_VALOR|N|16|2|Valor|Valor da alçada
--- ### FNM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNM|01|FNM_FILIAL|C|6|0|Filial|Filial do Sistema
FNM|02|FNM_IDMOV|C|10|0|ID Movimen.|ID Movimentos
FNM|03|FNM_ROTINA|C|10|0|Rotina|Rotina do ambiente
FNM|04|FNM_DESCRT|C|20|0|Desc. Rotina|Descrição da rotina
FNM|05|FNM_REVIS|C|4|0|Revisão|Revisão da alçada
FNM|06|FNM_OPER|C|2|0|Operação|Operação da rotina
FNM|07|FNM_DESCOP|C|20|0|Desc. Opera.|Descrição da operação
FNM|08|FNM_DATA|D|8|0|Data movimen|Data da movimentação
FNM|09|FNM_CODSOL|C|6|0|Solicitante|Código do solicitante
FNM|10|FNM_NOMSOL|C|25|0|Nome solici.|Nome do solicitante
FNM|11|FNM_CODAPR|C|6|0|Aprovador|Código do aprovador
FNM|12|FNM_NOMAPR|C|25|0|Nome aprova.|Nome do aprovador
FNM|13|FNM_MOEDA|C|2|0|Moeda|Moeda da operação
FNM|14|FNM_VALOR|N|16|2|Valor|Valor da operação
FNM|15|FNM_STATUS|C|1|0|Status|Status da solicitação
FNM|16|FNM_MEMSOL|M|10|0|Jus. Soli.|Justificativa solicitante
FNM|17|FNM_MEMAPR|M|10|0|Jus. aprova.|Justificativa aprovador
FNM|18|FNM_ORIGEM|C|10|0|Origem|Rotina de origem
FNM|19|FNM_TABORI|C|3|0|Tabe. Origem|Alias da tabela de origem
FNM|20|FNM_RECORI|N|16|0|Recno Origem|Recno do registro de orig
--- ### FNN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNN|01|FNN_FILIAL|C|6|0|Filial|Filial do Sistema
FNN|02|FNN_DTPROC|D|8|0|Data Proc.|Data do Processamento
FNN|03|FNN_IDPROC|C|10|0|Processo|Identificador do Processo
FNN|04|FNN_STATUS|C|1|0|Status|Status do Processo
FNN|05|FNN_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FNN|06|FNN_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FNO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNO|01|FNO_FILIAL|C|6|0|Filial|Filial do Sistema
FNO|02|FNO_IDPROC|C|10|0|Processo|Identificador do Processo
FNO|03|FNO_DTPROC|D|8|0|Data Proc.|Data de Processamento
FNO|04|FNO_CBASE|C|10|0|Cod.Base Prv|Codigo Base Provisao
FNO|05|FNO_ITEM|C|4|0|Item Prv|Item Provisao
FNO|06|FNO_BASESP|C|10|0|Cod.base Sup|Codigo Base Superior
FNO|07|FNO_ITEMSP|C|4|0|Item Sup.|Item Superior
FNO|08|FNO_MSG|M|10|0|Mensag.Proc.|Mensagem Proc
FNO|09|FNO_STATUS|C|1|0|Status|Status do processo
FNO|10|FNO_IDMVAF|C|10|0|Id.Movt.ATF|ID do movimento ATF
--- ### FNP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNP|01|FNP_FILIAL|C|6|0|Filial|Filial do Sistema
FNP|02|FNP_DTPROC|D|8|0|Data Proc.|Data do Processamento
FNP|03|FNP_IDPROC|C|20|0|Id.Proc.AVP|ID do processo de AVP
FNP|04|FNP_STATUS|C|1|0|Status|Status do processo
FNP|05|FNP_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FNP|06|FNP_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FNQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNQ|01|FNQ_FILIAL|C|6|0|Filial|Filial do Sistema
FNQ|02|FNQ_COD|C|6|0|Codigo|Codigo da Margem
FNQ|03|FNQ_REV|C|4|0|Revisao|Revisao da Margem
FNQ|04|FNQ_DESC|C|40|0|Descricao|Descricao da Margem
FNQ|05|FNQ_TIPO|C|1|0|Tipo Margem|Tipo de Margem
FNQ|06|FNQ_VLRFIX|N|16|2|Valor Fixo|Valor Fixo Margem
FNQ|07|FNQ_PERCEN|N|7|2|Percentual|Percentual da Margem
FNQ|08|FNQ_STATUS|C|1|0|Status|Status de Margem
FNQ|09|FNQ_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
--- ### FNR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNR|01|FNR_FILIAL|C|6|0|Filial|Filial do Sistema
FNR|02|FNR_IDMOV|C|6|0|ID Movim|ID do Movimento
FNR|03|FNR_DATA|D|8|0|Data Movim|Data do Movimento
FNR|04|FNR_CODREL|C|6|0|Cod. Rel.|Cod. Relacionamento
FNR|05|FNR_STATUS|C|1|0|Status|Status da Transferencia
FNR|06|FNR_CBAORI|C|10|0|C Base Ori|Código Base de Origem
FNR|07|FNR_ITEORI|C|4|0|Item Ori|Item do ativo de origem
FNR|08|FNR_DESCRI|C|40|0|Descr. Sint.|Descrição Sintética
FNR|09|FNR_CBADES|C|10|0|C Base Des|Código Base de Destino
FNR|10|FNR_ITEDES|C|4|0|Item Des|Item do ativo de destino
FNR|11|FNR_FILORI|C|6|0|Filial Orig|Filial de Origem
FNR|12|FNR_FILDES|C|6|0|Filial Dest|Filial de Destino
FNR|13|FNR_GRPORI|C|4|0|Grupo Origem|Grupo de Bem Origem
FNR|14|FNR_GRPDES|C|4|0|Grupo Dest|Grupo de Destino
FNR|15|FNR_LOCORI|C|6|0|Local Origem|Local Origem do Bem
FNR|16|FNR_LOCDES|C|6|0|Local Dest.|Local Destino do Bem
FNR|17|FNR_TXPADO|C|6|0|Cod Tx Pad O|Cod. da Taxa Padrão Orig.
FNR|18|FNR_TXPADD|C|6|0|Cod.Tx.Pa.De|Codigo da Classif. Fiscal
FNR|19|FNR_QTDORI|N|11|3|Quant. Orig.|Quantidade na Origem
FNR|20|FNR_QTDDES|N|11|3|Quant. Dest.|Quantidade no Destino
FNR|21|FNR_GERNF|C|1|0|Gera NF|Gera Nota Fiscal
FNR|22|FNR_NOTA|C|9|0|Nota Fiscal|Nota Fiscal
FNR|23|FNR_SERIE|C|3|0|Série NF|Série da Nota Fiscal
FNR|24|FNR_TESSAI|C|3|0|TES Saída|TES Saída
FNR|25|FNR_TESENT|C|3|0|TES Entrada|TES Entrada
FNR|26|FNR_CLSNF|C|1|0|Class NF|Classificação da NF
FNR|27|FNR_VALNF|N|14|2|Valor da NF|Valor da Nota Fiscal
FNR|28|FNR_ESPECI|C|5|0|Espécie NF|Espécie Nota Fiscal Ent.
FNR|29|FNR_ARMAZE|C|2|0|Armazem|Armazem Estoque Destino
FNR|30|FNR_TRANSP|C|6|0|Transp.|Codigo da Transportadora
FNR|31|FNR_TPFRET|C|1|0|Tipo Frete|Tipo do Frete Utilizado
FNR|32|FNR_PESOL|N|11|4|Peso Liquido|Peso Liquido
FNR|33|FNR_PBRUTO|N|11|4|Peso Bruto|Peso Bruto
FNR|34|FNR_VOLUM1|N|5|0|Volume 1|Qtde de Volumes tipo 1
FNR|35|FNR_ESPEC1|C|10|0|Especie 1|Especie do Volume tipo 1
FNR|36|FNR_VEICU1|C|8|0|Veiculo 1|Veiculo do Transporte 1
--- ### FNS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNS|01|FNS_FILIAL|C|6|0|Filial|Filial do Sistema
FNS|02|FNS_IDMOV|C|6|0|ID Mov|ID Movimento
FNS|03|FNS_DATA|D|8|0|Data Mov|Data de Movimento
FNS|04|FNS_CODREL|C|6|0|Cod. Rel.|Cod. Relelacionamento
FNS|05|FNS_TIPO|C|2|0|Tipo Ativo|Tipo do Ativo
FNS|06|FNS_SEQ|C|3|0|Seq. Aquisi.|Sequencia de Aquisicao
FNS|07|FNS_HISTOR|C|40|0|Historico|Historico
FNS|08|FNS_CCDESO|C|9|0|CC Desp Orig|C Custo Despesa Origem
FNS|09|FNS_CCDESD|C|9|0|CC Desp Dest|C Custo Despesa Destino
FNS|10|FNS_CONTAO|C|20|0|Ct Bem Orig|Conta do Bem de Origem
FNS|11|FNS_CONTAD|C|20|0|Ct Bem Dest|Conta do Bem de Destino
FNS|12|FNS_CONCOO|C|20|0|Ct Cor Mon O|Conta Corr. Monet. Orig.
FNS|13|FNS_CONCOD|C|20|0|Ct Cor Mon D|Conta Corr. Monet. Dest.
FNS|14|FNS_CONDDO|C|20|0|Ct Des Dep O|Conta Desp. Deprec. Orig.
FNS|15|FNS_CONDDD|C|20|0|Ct Des Dep D|Conta Desp. Deprec. Dest.
FNS|16|FNS_CONDAO|C|20|0|Ct Dep Acu O|Conta Deprec Acumul Orig
FNS|17|FNS_CONDAD|C|20|0|Ct Dep Acu D|Conta Deprec Acumul Dest
FNS|18|FNS_CONCDO|C|20|0|Ct Cor Dep O|Conta Corr. Deprec. Orig.
FNS|19|FNS_CONCDD|C|20|0|Ct Cor Dep D|Conta Corr. Deprec. Dest.
FNS|20|FNS_CCBEMO|C|9|0|CC Bem Orig|C Custo do Bem Origem
FNS|21|FNS_CCBEMD|C|9|0|CC Bem Dest|C Custo do Bem Destino
FNS|22|FNS_CCCORO|C|9|0|CC Cor Mon O|C Custo Corr Monet Orig
FNS|23|FNS_CCCORD|C|9|0|CC Cor Mon D|C Custo Corr Monet Dest
FNS|24|FNS_CCDDO|C|9|0|CC Des Dep O|C Custo Desp Deprec Orig
FNS|25|FNS_CCDDD|C|9|0|CC Des Dep D|C Custo Desp Deprec Dest
FNS|26|FNS_CCDAO|C|9|0|CC Dep Acu O|C Custo Deprec Acumul Ori
FNS|27|FNS_CCDAD|C|9|0|CC Dep Acu D|C Custo Deprec Acumul Des
FNS|28|FNS_CCCDO|C|9|0|CC Cor Dep O|C Custo Corr Deprec Orig
FNS|29|FNS_CCCDD|C|9|0|CC Cor Dep D|C Custo Corr Deprec Dest
FNS|30|FNS_ITBEMO|C|9|0|It Bem Orig|Item Contábil do Bem Orig
FNS|31|FNS_ITBEMD|C|9|0|It Bem Dest|Item Contábil do Bem Dest
FNS|32|FNS_ITCORO|C|9|0|It Cor Mon O|Item Corr. Monet. Orig.
FNS|33|FNS_ITCORD|C|9|0|It Cor Mon D|Item Corr. Monet. Dest.
FNS|34|FNS_ITDEDO|C|9|0|It Des Dep O|Item Desp. Deprec. Orig.
FNS|35|FNS_ITDEDD|C|9|0|It Des Dep D|Item Desp. Deprec. Dest.
FNS|36|FNS_ITDEAO|C|9|0|It Dep Acu O|Item Deprec Acumul Orig
FNS|37|FNS_ITDEAD|C|9|0|It Dep Acu D|Item Deprec Acumul Dest
FNS|38|FNS_ITCDEO|C|9|0|It Cor Dep O|Item Corr. Deprec. Orig.
FNS|39|FNS_ITCDED|C|9|0|It Cor Dep D|Item Corr. Deprec. Dest.
FNS|40|FNS_CVBEMO|C|9|0|CV Bem Orig|Classe de Val do Bem Orig
FNS|41|FNS_CVBEMD|C|9|0|CV Bem Dest|Classe de Val do Bem Dest
FNS|42|FNS_CVCORO|C|9|0|CV Cor Mon O|Cl Vl Corr. Monet. Orig.
FNS|43|FNS_CVCORD|C|9|0|CV Cor Mon D|Cl Vl Corr. Monet. Dest.
FNS|44|FNS_CVDEPO|C|9|0|CV Des Dep O|Cl Vl Desp. Deprec. Orig.
FNS|45|FNS_CVDEPD|C|9|0|CV Des Dep D|Cl Vl Desp. Deprec. Dest.
FNS|46|FNS_CVCDEO|C|9|0|CV Dep Acu O|Cl Vl Deprec Acumul Orig
FNS|47|FNS_CVCDED|C|9|0|CV Dep Acu D|Cl Vl Deprec Acumul Dest
FNS|48|FNS_CVDESO|C|9|0|CV Cor Dep O|Cl Vl Corr. Deprec. Orig.
FNS|49|FNS_CVDESD|C|9|0|CV Cor Dep D|Cl Vl Corr. Deprec. Dest.
FNS|50|FNS_ITDESO|C|9|0|IT Desp Orig|Item Despesa Orig
FNS|51|FNS_ITDESD|C|9|0|IT Desp Dest|Item Despesa Dest
FNS|52|FNS_CVDSPO|C|9|0|CV Desp Orig|Classe de Val Desp Orig
FNS|53|FNS_CVDSPD|C|9|0|CV Desp Dest|Classe de Val Despesa Des
--- ### FNT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNT|01|FNT_FILIAL|C|6|0|Filial|Filial do Sistema
FNT|02|FNT_CODIND|C|2|0|Cod.Índice|Código do Índice
FNT|03|FNT_REVIS|C|4|0|Rev.Tx.Ind.|Revisão da taxa do Índice
FNT|04|FNT_DATA|D|8|0|Dt.Tx.Ind.|Data da taxa do índice
FNT|05|FNT_TAXA|N|14|8|Taxa índice|Taxa do índice
FNT|06|FNT_CURVA|N|16|2|Curva|Curva de Demanda
FNT|07|FNT_TIPO|C|1|0|Tipo da taxa|Tipo da taxa
FNT|08|FNT_STATUS|C|1|0|Status|Status da taxa
FNT|09|FNT_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FNT|10|FNT_DTVLDF|D|8|0|Dt.Valid. Tx|Data de Validade da Taxa
--- ### FNU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNU|01|FNU_FILIAL|C|6|0|Filial|Filial do Sistema
FNU|02|FNU_COD|C|10|0|Código|Código da Provisão
FNU|03|FNU_REV|C|4|0|Revisão|Revisão da Provisão
FNU|04|FNU_DESCR|C|40|0|Descrição|Descrição da Provisão
FNU|05|FNU_DTINI|D|8|0|Dt Reconhec|Data Reconhecimento
FNU|06|FNU_INIPRJ|D|8|0|Dt Ini Proj|Data Início Projeto
FNU|07|FNU_DTAVP|D|8|0|Data Ref AVP|Data de Referencia AVP
FNU|08|FNU_TPCALC|C|1|0|Tipo Calculo|Tipo do Cálculo Provisão
FNU|09|FNU_INDICE|C|2|0|Ind. Curva|indice de curva
FNU|10|FNU_TAXAVP|N|14|8|Taxa AVP|Taxa de AVP Provisão
FNU|11|FNU_INDAVP|C|2|0|Indice AVP|Indice AVP Provisão
FNU|12|FNU_CONTA|C|20|0|Conta Contab|Conta contábil provisão
FNU|13|FNU_CUSTO|C|9|0|C.Custo|Centro de Custo Provisão
FNU|14|FNU_ITEM|C|9|0|Item Contab.|Item Contabil Provisão
FNU|15|FNU_CLVL|C|9|0|Classe Valor|Classe Valor Provisão
FNU|16|FNU_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo da Provisão
FNU|17|FNU_DTREV|D|8|0|Dt. Revisão|Data de revisão
FNU|18|FNU_STATUS|C|1|0|Status|Status Controle Provisão
FNU|19|FNU_MSBLQL|C|1|0|Bloqueado|Registro bloqueado
FNU|20|FNU_VLRBRT|N|16|2|Total Bruto|Valor Bruto Total
FNU|21|FNU_VLRPRE|N|16|2|Tot.Presente|Valor Presente Total
--- ### FNV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNV|01|FNV_FILIAL|C|6|0|Filial|Filial do Sistema
FNV|02|FNV_COD|C|10|0|Cód. Provis.|Código da Provisão
FNV|03|FNV_REV|C|4|0|Rev. Provis.|Revisão da Provisão
FNV|04|FNV_ITEM|C|3|0|Item|Item da Provisão
FNV|05|FNV_DTFIN|D|8|0|Data Final|Data Final da Provisão
FNV|06|FNV_VLRBRT|N|16|2|Valor Bruto|Valor Bruto do Item
FNV|07|FNV_VLRPRE|N|16|2|Vlr Presente|Valor Presente do Item
FNV|08|FNV_RLZEFT|C|1|0|Rlz.Efetivad|Realização Efetivada
--- ### FNW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNW|01|FNW_FILIAL|C|6|0|Filial|Filial do sistema
FNW|02|FNW_COD|C|10|0|Código|Código da Provisão
FNW|03|FNW_REV|C|4|0|Revisão|Revisão da Provisão
FNW|04|FNW_PERIOD|C|6|0|Periodo|Periodo do movimento
FNW|05|FNW_DTMOV|D|8|0|Dt. Movto.|Data do Movimento
FNW|06|FNW_OCOR|C|2|0|Ocorrência|Ocorrencia do movimento
FNW|07|FNW_VALOR|N|16|2|Valor|Valor do movimento
FNW|08|FNW_LA|C|1|0|Ident. Lanc.|Identificador Contabil
FNW|09|FNW_IDMOV|C|10|0|Id. Movto.|Identificador movimentos
FNW|10|FNW_PRAZO|C|1|0|Tipo Prazo|Tipo de Prazo Movimento
FNW|11|FNW_DTEFET|D|8|0|Data Efetiva|Data da Efetivação
FNW|12|FNW_DCONTA|D|8|0|Data Contab.|Data de Contabilizacao
FNW|13|FNW_ORIGEM|C|8|0|Origem|Origem do Movimento
FNW|14|FNW_LP|C|6|0|Lanc Pad.|Lançamento padrão
--- ### FNX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNX|01|FNX_FILIAL|C|6|0|Filial|Filial do sistema
FNX|02|FNX_COD|C|10|0|Código|Código da Provisão
FNX|03|FNX_REV|C|4|0|Revisão|Revisão da Provisão
FNX|04|FNX_LINHA|C|3|0|Linha|Linha de Realização
FNX|05|FNX_DTMOV|D|8|0|Dt. Movto.|Data do Movimento
FNX|06|FNX_CBASE|C|10|0|Código Base|Código Base do Ativo
FNX|07|FNX_ITEM|C|4|0|Item|Item do Ativo de Execução
FNX|08|FNX_TIPO|C|2|0|Tipo|Tipo do Ativo de Execução
FNX|09|FNX_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo do Ativo
FNX|10|FNX_VALOR|N|16|2|Valor Exec.|Valor da Execução
FNX|11|FNX_DTCONT|D|8|0|Data Efetiva|Data da Efetivação
FNX|12|FNX_FILATF|C|6|0|Filial ATF|Filial do Ativo
--- ### FNY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNY|01|FNY_FILIAL|C|6|0|Filial|Filial do Sistema
FNY|02|FNY_PROCID|C|20|0|Processo|Processo
FNY|03|FNY_DESC|C|40|0|Descricao|Descricao
FNY|04|FNY_DTEMIS|D|8|0|Data Emis.|Data da Emissão
FNY|05|FNY_DTAJST|D|8|0|Data Ajuste|Data Ajusete
FNY|06|FNY_LA|C|1|0|Ident. Lanc.|Ident. Lanc.
FNY|07|FNY_STATUS|C|1|0|Status|Status
FNY|08|FNY_ROTINA|C|1|0|Rotina|Rotina
FNY|09|FNY_PARAM|M|10|0|Parâmetros|Parâmetros
--- ### FNZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FNZ|01|FNZ_FILIAL|C|6|0|Filial|Filial do Sistema
FNZ|02|FNZ_PROCID|C|20|0|Processo|Processo
FNZ|03|FNZ_ITEM|C|6|0|Item Proc.|Item Proc.
FNZ|04|FNZ_BEM|C|10|0|Cod.Bem|Codigo do Bem
FNZ|05|FNZ_ITBEM|C|4|0|Item do Bem|Item do Bem
FNZ|06|FNZ_TIPO|C|2|0|Tipo|Tipo
FNZ|07|FNZ_VLORI1|N|16|2|Vl Orig|Valor Contábil M1
FNZ|08|FNZ_TPSALD|C|1|0|Tipo Saldo|Tipo de Saldo
FNZ|09|FNZ_TPDEPR|C|1|0|Tipo deprec.|Tipo de depreciação
FNZ|10|FNZ_CCONTA|C|20|0|Conta|Conta Contábil
FNZ|11|FNZ_CUSTBE|C|9|0|C Custo Bem|C Custo da Conta do Bem
FNZ|12|FNZ_CDEPRE|C|20|0|Cta Desp Dep|Conta Despesa Depreciação
FNZ|13|FNZ_CCUSTO|C|9|0|CC Despesa|Centro de Custo Despesa
FNZ|14|FNZ_CCDEPR|C|20|0|Cta Dep Acum|Conta Deprec. Acumulada
FNZ|15|FNZ_CDESP|C|20|0|Cta Cor Depr|Cta Correção Depreciação
FNZ|16|FNZ_CCORRE|C|20|0|Conta Correc|Conta Correção Bem
FNZ|17|FNZ_VLAJS1|N|16|2|Vlr.Ajuste|Valor Ajuste
FNZ|18|FNZ_VLTAX1|N|6|2|Taxa|Taxa do Valor Ajuste
FNZ|19|FNZ_VLACM1|N|16|2|Dep Acm|Deprec acum Valor Ajuste
FNZ|20|FNZ_VORIG2|N|16|2|Vl Orig M2|Valor Contábil M2
FNZ|21|FNZ_VLAJS2|N|16|2|Vlr.Ajst M2|Valor Ajuste M2
FNZ|22|FNZ_TXDEP2|N|6|2|Taxa M2|Taxa do Valor Ajuste M2
FNZ|23|FNZ_VRDAC2|N|16|2|Dep Acm M2|Deprec acum Valor Ajuste
FNZ|24|FNZ_VORIG3|N|16|2|Vl Orig M3|Valor Contábil M3
FNZ|25|FNZ_VLAJS3|N|16|2|Vlr.Ajst M3|Valor Ajuste M3
FNZ|26|FNZ_TXDEP3|N|6|2|Taxa M3|Taxa do Valor Ajuste M3
FNZ|27|FNZ_VRDAC3|N|16|2|Dep Acm M3|Deprec acum Valor Ajuste
FNZ|28|FNZ_VORIG4|N|16|2|Vl Orig M4|Valor Contábil M4
FNZ|29|FNZ_VLAJS4|N|16|2|Vlr.Ajst M4|Valor Ajuste M4
FNZ|30|FNZ_TXDEP4|N|6|2|Taxa M4|Taxa do Valor Ajuste M4
FNZ|31|FNZ_VRDAC4|N|16|2|Dep Acm M4|Deprec acum Valor Ajuste
FNZ|32|FNZ_VORIG5|N|16|2|Vl Orig M5|Valor Contábil M5
FNZ|33|FNZ_VLAJS5|N|16|2|Vlr.Ajst M5|Valor Ajuste M5
FNZ|34|FNZ_TXDEP5|N|6|2|Taxa M5|Taxa do Valor Ajuste M5
FNZ|35|FNZ_VRDAC5|N|16|2|Dep Acm M5|Deprec acum Valor Ajuste
FNZ|36|FNZ_CCDESP|C|9|0|Cc Des Depr|Centro Custo Desp Depr.
FNZ|37|FNZ_CCCDEP|C|9|0|Cc Depr Ac|CCentro Custo Dep. Acumul
FNZ|38|FNZ_CCCDES|C|9|0|Cc Cor Dep|Centro Custo Corr. Depr
FNZ|39|FNZ_CCCORR|C|9|0|Cc Correção|Centro Custo Corr. Monet.
FNZ|40|FNZ_SUBCTA|C|9|0|Item Despesa|Item Despesa
FNZ|41|FNZ_SUBCCO|C|9|0|Item do Bem|Item Conta do Bem
FNZ|42|FNZ_SUBCDS|C|9|0|Item Ds.Dep|Item Despesa Depreciação
FNZ|43|FNZ_SUBCCD|C|9|0|Item Dep.Ac.|Item Depr. Acumulada
FNZ|44|FNZ_SUBCDE|C|9|0|Item Dep.Ac.|Item Depr. Acumulada
FNZ|45|FNZ_SUBCOR|C|9|0|Item Cor.Bem|Item Correção Monetária
FNZ|46|FNZ_CLVL|C|9|0|ClVl Despesa|Classe de Valor Despesa
FNZ|47|FNZ_CLVLCN|C|9|0|Cl Vlr Bem|Classe de Valor do Bem
FNZ|48|FNZ_CLVLDP|C|9|0|Clvl Des.Dep|Classe Vlr Despesa Dep.
FNZ|49|FNZ_CLVLCE|C|9|0|Clvl Dep.Acu|Classe de Vlr Dep. Acum.
FNZ|50|FNZ_CLVLDS|C|9|0|Clvl Cor.Dep|Classe de Vlr Cor. Depr.
FNZ|51|FNZ_CLVLCR|C|9|0|Clvl Correc.|Classe de Vlr Correc Bem
FNZ|52|FNZ_PERDEP|N|4|0|Per Deprec|Periodicidade Depreciac
FNZ|53|FNZ_VSALV1|N|16|2|Vlr Salv|Valor de salvamento
FNZ|54|FNZ_PRDANO|N|15|3|Prod. Estim.|Producao Estimada
FNZ|55|FNZ_PRDMES|N|15|3|Prod. period|producao do periodo
FNZ|56|FNZ_PRDACM|N|16|3|Prod. acum.|Producao acumulada do bem
FNZ|57|FNZ_VMXDEP|N|16|2|Vl Max Depr|Valor Maximo Depreciacao
--- ### F70
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F70|01|F70_FILIAL|C|6|0|Filial|Filial do Sistema
F70|02|F70_COD|C|3|0|Código Banco|Código Banco
F70|03|F70_AGENCI|C|5|0|Nro Agência|Agência do Banco
F70|04|F70_DVAGE|C|1|0|DV Agência|Dígito Verific. Agência
F70|05|F70_NUMCON|C|10|0|Nro Conta|Conta Corrente no Banco
F70|06|F70_DVCTA|C|1|0|DV Conta|Dígito Verific. Conta
F70|07|F70_TPCHV|C|2|0|Tipo Chv PIX|Tipo de Chave Pix
F70|08|F70_CHVPIX|C|100|0|Chave PIX|Chave PIX
F70|09|F70_ACTIVE|C|1|0|Principal|Chave principal
--- ### F71
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F71|01|F71_FILIAL|C|6|0|Filial|Filial do Sistema
F71|02|F71_STATUS|C|1|0|Status|Status
F71|03|F71_PREFIX|C|3|0|Prefixo|Prefixo do titulo
F71|04|F71_NUM|C|9|0|No. Titulo|Numero do Titulo
F71|05|F71_PARCEL|C|3|0|Parcela|Parcela do Titulo
F71|06|F71_TIPO|C|3|0|Tipo|Tipo do titulo
F71|07|F71_SEQ|C|2|0|Sequência|Sequencia do Registro
F71|08|F71_VALOR|N|16|2|Vlr.Titulo|Valor do Titulo
F71|09|F71_VLRPIX|N|16|2|Valor PIX|Valor enviado ao PIX
F71|10|F71_EMISSA|D|8|0|Dt. Emissão|Data Emissão
F71|11|F71_VENCTO|D|8|0|Vencimento|Vencimento do Titulo
F71|12|F71_CODCLI|C|6|0|Cliente|Codigo do Cliente
F71|13|F71_LOJCLI|C|2|0|Loja|Loja do Cliente
F71|14|F71_NOMCLI|C|80|0|Nome Cliente|Nome do cliente
F71|15|F71_SOLCAN|C|1|0|Solicita Can|Solicita Cancelamento
F71|16|F71_DTPSP|D|8|0|Data Geração|Data da Geração Arquivo
F71|17|F71_HRPSP|C|8|0|Hora Geração|Hora Geração Arquivo
F71|18|F71_DTMAIL|D|8|0|Dt Env Email|Data Envio Email Cadastro
F71|19|F71_HRMAIL|C|8|0|Hr Env Email|Hora Envio Email Cadastro
F71|20|F71_DTMACA|D|8|0|Dt Email Can|Data Envio Email Cancelam
F71|21|F71_HRMACA|C|8|0|Hr Email Can|Hora Envio Email Cancelam
F71|22|F71_FILBCO|C|6|0|Filial Banco|Filial do Banco
F71|23|F71_CODBAN|C|3|0|Cód. Banco|Código do Banco
F71|24|F71_AGENCI|C|5|0|Nro Agência|Agencia do banco
F71|25|F71_NUMCON|C|10|0|Nro Conta|Conta Corrente no Banco
F71|26|F71_TPCHV|C|2|0|Tipo Chv PIX|Tipo de Chave Pix
F71|27|F71_CHVPIX|C|100|0|Chave PIX|Chave PIX
F71|28|F71_CODRET|C|2|0|Cód. Retorno|Codigo de Retorno
F71|29|F71_LNKPIX|M|10|0|Link PIX|Link PIX
F71|30|F71_EMVPIX|M|10|0|EMV PIX|EMV do QR Code Pix
F71|31|F71_IDDOC|C|32|0|Id. Doc.|Identif. Documento
F71|32|F71_IDTRAN|C|35|0|ID Transação|ID da transacao PIX
F71|33|F71_IDPROC|C|36|0|ID Processad|ID Processadora
F71|34|F71_IDPD|C|36|0|ID Pag.Digit|ID Pagamentos Digitais
F71|35|F71_MENSAG|M|10|0|Msg Status|Mensagem Status PIX
F71|36|F71_IDFK1|C|32|0|Id. Baixas|Identif. Baixas
F71|37|F71_DECRES|N|16|2|Decréscimo|Valor do Decréscimo
F71|38|F71_ACRESC|N|16|2|Acréscimo|Valor do Acréscimo
F71|39|F71_VASOMA|N|16|2|VA Soma|Vlr VA de soma
F71|40|F71_VASUBT|N|16|2|VA Subtração|Vlr VA de subtração
F71|41|F71_ABATIM|N|16|2|Abatimento|Valor do Abatimento
F71|42|F71_TPDESC|C|1|0|Tipo Descont|Tipo do Desconto
F71|43|F71_DTLIMI|D|8|0|Dt Lim Desco|Data Limite do Desconto
F71|44|F71_DESFIN|N|5|2|Desc Financ.|Desconto Financeiro
F71|45|F71_TXPERM|N|14|2|Taxa Perman.|Taxa Permanencia Diaria
F71|46|F71_PERJUR|N|5|2|Perc Juros|Percentual Juros Diario
F71|47|F71_MULTA|N|16|2|Multa|Valor da Multa
F71|48|F71_DIAEXP|N|2|0|Dias Expira.|Dias para Expiração
--- ### F72
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F72|01|F72_FILIAL|C|6|0|Filial|Filial do Sistema
F72|02|F72_COD|C|6|0|Codigo|Codigo do Fornecedor
F72|03|F72_LOJA|C|2|0|Loja|Loja do Fornecedor
F72|04|F72_TPCHV|C|2|0|Tipo Chv PIX|Tipo de Chave Pix
F72|05|F72_CHVPIX|C|100|0|Chave PIX|Chave PIX
F72|06|F72_ACTIVE|C|1|0|Principal|Chave principal
F72|07|F72_NOME|C|80|0|Razao Social|Nome ou Razao Social
--- ### F73
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F73|01|F73_FILIAL|C|6|0|Filial|Filial do Sistema
F73|02|F73_NATUR|C|10|0|Natureza|Codigo da Natureza
F73|03|F73_DESNAT|C|30|0|Desc Naturez|Descricao da Natureza
F73|04|F73_ITEM|C|4|0|Item|Item Sequencial
F73|05|F73_COINI|C|12|0|Cta. Orc. De|Cod Cta Orcament Inicial
F73|06|F73_COFIM|C|12|0|Cta. Orc Ate|Cod Cta Orcament Final
F73|07|F73_CLASSE|C|6|0|Classe|Codigo da Classe
F73|08|F73_CCINI|C|9|0|CC De|Cod CC inicial.
F73|09|F73_CCFIM|C|9|0|CC Ate|Cod Centro de Custo final
F73|10|F73_ITCTBI|C|9|0|CR. Cont De|Cod CR Contabil Inicial
F73|11|F73_ITCTBF|C|9|0|CR. Cont Ate|Cod CR Contabil Final
F73|12|F73_CLVRLI|C|9|0|Clas Vlr De|Cod Classe Valor Inicial
F73|13|F73_CLVRLF|C|9|0|Clas Vlr Ate|Cod Classe Valor Final
--- ### F74
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F74|01|F74_FILIAL|C|6|0|Filial|Cod Filial
F74|02|F74_DTPROC|D|8|0|Dt Processo|Data do Processamento
F74|03|F74_ROTINA|C|40|0|Rot. Origem|Rotina processadora
F74|04|F74_KEY|C|200|0|ID Processo|ID de processamento
F74|05|F74_USER|C|25|0|Usuario|Responsável processamento
F74|06|F74_IDTHR|C|32|0|ID THREAD|ID THREAD SMARTCLIENT
F74|07|F74_SIDTHR|C|32|0|SID THREAD|ID TOTVSDBACCESS
F74|08|F74_ENVIR|C|50|0|Ambiente|Ambiente do processamento
--- ### F75
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F75|01|F75_FILIAL|C|6|0|Filial|Filial do Sistema
F75|02|F75_PREFIX|C|3|0|Prefixo|Prefixo do titulo
F75|03|F75_NUM|C|9|0|No. Titulo|Numero do Titulo
F75|04|F75_PARCEL|C|3|0|Parcela|Parcela do Titulo
F75|05|F75_TIPO|C|3|0|Tipo|Tipo do titulo
F75|06|F75_CLIFOR|C|6|0|Cli/For|Cliente / Fornecedor
F75|07|F75_LOJA|C|2|0|Loja|Loja Cliente/Fornecedor
F75|08|F75_RECPAG|C|1|0|Carteira|Carteira receber / pagar
F75|09|F75_FLUXO|C|1|0|Fluxo caixa|Fluxo de caixa
F75|10|F75_DTATU|D|8|0|Atualizado|Data de atualização
F75|11|F75_VENCTO|D|8|0|Vencimento|Vencimento do Titulo
F75|12|F75_MOEDA|N|2|0|Moeda|Moeda do título
F75|13|F75_TXMOED|N|11|4|Taxa moeda|Taxa da moeda
F75|14|F75_VLTIT|N|16|2|Saldo Moeda|Saldo na moeda do título
F75|15|F75_SALDO|N|16|2|Saldo|Saldo do título
F75|16|F75_ABATIM|N|16|2|Abatimentos|Abatimentos
F75|17|F75_FILORI|C|6|0|Filial Orig|Filial Origem do Título
F75|18|F75_VLVA|N|16|8|VL acessorio|Valor acessório do título
F75|19|F75_MULTA|N|16|8|Multa|Multa
F75|20|F75_JUROS|N|16|2|Juros|Juros
--- ### F76
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F76|01|F76_FILIAL|C|6|0|Filial|Filial do Sistema
F76|02|F76_PEDIDO|C|6|0|Numero|Numero do Pedido
F76|03|F76_ITEM|C|4|0|Item|Item do Pedido
F76|04|F76_CLIFOR|C|6|0|Cli/For|Codigo do Cli/For
F76|05|F76_LOJA|C|2|0|Loja|Loja do Cli/For
F76|06|F76_TIPO|C|1|0|Tipo Pedido|Tipo de Pedido
F76|07|F76_DATA|D|8|0|Data Saldo|Data do Saldo
F76|08|F76_VALOR|N|12|2|Valor|Valor na Data do Saldo
F76|09|F76_VLORIG|N|12|2|Valor Origin|Valor Original
F76|10|F76_MOEDA|N|2|0|Moeda|Moeda do Pedido
F76|11|F76_TXMOED|N|11|4|Taxa Moeda|Taxa da Moeda
F76|12|F76_COND|C|3|0|Cond. Pag.|Código da Condição de Pag
F76|13|F76_SEQ|C|3|0|Sequencia|Sequencia de Valor
F76|14|F76_DTJOBT|D|8|0|Data Job|Data Execução Job
F76|15|F76_FILORI|C|6|0|Fil Orig|Filial Origem Pedido
F76|16|F76_BLQLIB|N|1|0|Bloq/Liber|Ped.Bloqueados/Liberados
--- ### F77
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F77|01|F77_FILIAL|C|6|0|Filial|Filial do Sistema
F77|02|F77_BANCO|C|3|0|Banco|Codigo do Banco
F77|03|F77_ESPECI|C|2|0|Espécie|Código Espécie do Boleto
F77|04|F77_DESCRI|C|40|0|Descrição|Descrição da Espécie
F77|05|F77_SIGLA|C|4|0|Sigla|Sigla da Espécie
--- ### F78
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F78|01|F78_FILIAL|C|6|0|Filial|Filial do Sistema
F78|02|F78_ID|C|20|0|Cod. Id|Código de Identificação
F78|03|F78_FILPED|C|6|0|Filial Ped|Filial do Pedido
F78|04|F78_NUMPD|C|6|0|Número Ped|Número do Pedido de Venda
F78|05|F78_FILCR|C|6|0|Filial CR|Filial do Conta a Receber
F78|06|F78_PRFCR|C|3|0|Prefixo CR|Prefixo Contas a Receber
F78|07|F78_NUMCR|C|9|0|Número CR|Número Contas a Receber
F78|08|F78_PARCCR|C|3|0|Parcela CR|Parcela Contas a Receber
F78|09|F78_TPCR|C|3|0|Tipo CR|Tipo Contas a Receber
--- ### F79
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F79|01|F79_FILIAL|C|6|0|Filial|Filial
F79|02|F79_CODIGO|C|10|0|Codigo Log|Codigo do Log
F79|03|F79_BANCO|C|3|0|Banco|Banco do Retorno
F79|04|F79_AGENCI|C|5|0|Agência|Agênciaorno
F79|05|F79_ESTCOB|C|2|0|Processo|Processo
F79|06|F79_CONTA|C|10|0|Nro Conta|Conta Corrente
F79|07|F79_DTPROC|D|8|0|Dt. Proces.|Data do Processamento
F79|08|F79_HRPROC|C|8|0|Hr. Proces|Hora do Processamento
F79|09|F79_QTDTIT|C|4|0|Qtde Títulos|Qtde Titulos Processados
F79|10|F79_NBAIXA|C|4|0|Qtde Falhas|Quantidade de Falhas
F79|11|F79_RECPAG|C|3|0|Rec / Pagar|Movimento Receber / Pagar
F79|12|F79_JSON|M|10|0|Json Retorno|Json Retorno Banco
F79|13|F79_QTPROC|C|4|0|Qtde Process|Quantidade Processados
--- ### F7A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7A|01|F7A_FILIAL|C|6|0|Filial|Filial
F7A|02|F7A_CODIGO|C|10|0|Codigo|Codigo ID tabela Pai
F7A|03|F7A_ESTCOB|C|2|0|Processo|Estado da Cobrança
F7A|04|F7A_FILORI|C|6|0|Filial Orig|Filial Origem do Titulo
F7A|05|F7A_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
F7A|06|F7A_NUMERO|C|9|0|No. Titulo|Numero do Título
F7A|07|F7A_PARCEL|C|3|0|Parcela|Parcela do Título
F7A|08|F7A_TIPO|C|3|0|Tipo|Tipo do Título
F7A|09|F7A_CLIENT|C|6|0|Cliente|Codigo do Cliente
F7A|10|F7A_LOJA|C|2|0|Loja|Loja do Cliente
F7A|11|F7A_STATUS|C|1|0|Status|Status do Registro
F7A|12|F7A_BORDER|C|6|0|Bordero|Bordero do Título
F7A|13|F7A_ERREXE|M|10|0|Msg Erro|Mensagem Erro ExecAuto
F7A|14|F7A_EMISSA|D|8|0|Dt Emissão|Data da Emissão do Titulo
F7A|15|F7A_VALOR|N|16|2|Vlr. Título|Valor do Titulo
F7A|16|F7A_MULTA|N|16|2|Vlr. Multa|Valor da Multa
F7A|17|F7A_DESCON|N|16|2|Vlr.Desconto|Valor do Desconto
F7A|18|F7A_JUROS|N|16|2|Vlr. Juros|Valor do Juros
F7A|19|F7A_JSON|M|10|0|Json Retorno|Json Retorno Banco
F7A|20|F7A_FORNEC|C|6|0|Fornecedor|Código do fornecedor
--- ### F7B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7B|01|F7B_FILIAL|C|6|0|Filial|Filial do sistema
F7B|02|F7B_CODIGO|C|6|0|Código|Código do template
F7B|03|F7B_DESCRI|C|50|0|Descrição|Descrição dos templates
F7B|04|F7B_APLEMP|C|3|0|Operação|Operação APL / EMP
--- ### F7C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7C|01|F7C_FILIAL|C|6|0|Filial|Filial do Sistema
F7C|02|F7C_CODIGO|C|6|0|Código|Código da Fórmula
F7C|03|F7C_APLEMP|C|3|0|APL / EMP|Operação APL / EMP
F7C|04|F7C_ITEM|C|3|0|Cod. Item|Codigo do Item
F7C|05|F7C_DESCRI|C|50|0|Descrição|Descrição da Fórmula
F7C|06|F7C_TIPO|C|10|0|Tipo|Tipo de Fórmula
F7C|07|F7C_FORM|C|200|0|Fórmula|Fórmula do Item
F7C|08|F7C_CONFIG|M|10|0|Configuração|Configuração da Fórmula
--- ### F7D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7D|01|F7D_FILIAL|C|6|0|Filial|Filial do sistema
F7D|02|F7D_IDSIMU|C|32|0|ID|Id da simulação
F7D|03|F7D_TITULO|C|50|0|Titulo|Titulo da simulação
F7D|04|F7D_DATA|D|8|0|Data|Data da simulação
F7D|05|F7D_HORA|C|8|0|Hora|Hora da simulação
F7D|06|F7D_USER|C|25|0|Usuario|Login do usuario Protheus
F7D|07|F7D_PUBLI|C|1|0|Publico|Simulação publica
--- ### F7E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7E|01|F7E_FILIAL|C|6|0|Filial|Filial do sistema
F7E|02|F7E_IDSIMU|C|32|0|ID|Id da simulação
F7E|03|F7E_ITEM|C|3|0|Item|Sequencia dos itens
F7E|04|F7E_TIPO|C|1|0|Tipo|Tipo do valor
F7E|05|F7E_VALOR|N|16|2|Valor|Valor de entrada/saida
F7E|06|F7E_DESCRI|C|50|0|Descrição|Descrição do valor
F7E|07|F7E_DATA|D|8|0|Data|Data da entrada/saida
--- ### F7F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7F|01|F7F_FILIAL|C|6|0|Filial|Filial do sistema
F7F|02|F7F_CODCLI|C|6|0|Cliente|Código do cliente
F7F|03|F7F_LOJA|C|2|0|Loja|Loja do cliente
F7F|04|F7F_IDHIST|C|32|0|Id do hist.|ID do histórico
F7F|05|F7F_TXTJUS|M|10|0|Just. limite|Justificativa novo limite
F7F|06|F7F_DATA|D|8|0|Data|Data da alteração
F7F|07|F7F_HORA|C|8|0|Hora|Hora da alteração
F7F|08|F7F_USER|C|25|0|Usuário|Login do usuario Protheus
F7F|09|F7F_APIMSG|M|10|0|Json API|Json Resp. Vadu
F7F|10|F7F_LIMATU|N|14|2|Limite atual|Limite de crédito atual
F7F|11|F7F_LIMANT|N|14|2|Limite ant.|Limite de crédito anterio
F7F|12|F7F_RISATU|C|1|0|Risco atual|Grau de risco atual
F7F|13|F7F_RISANT|C|1|0|Risco ant.|Grau de risco anterior
F7F|14|F7F_HIST|C|1|0|Tipo Hist.|Tipo de histórico
--- ### F7G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7G|01|F7G_FILIAL|C|6|0|Filial|Filial do sistema
F7G|02|F7G_SEQUEN|C|3|0|Sequência|Sequência de Apresentação
F7G|03|F7G_SIGLA|C|3|0|Sigla|Sigla do Motivo de Baixa
F7G|04|F7G_DESCRI|C|10|0|Descrição|Descrição
F7G|05|F7G_CART|C|1|0|Carteira|Caretira Pagar/Receber
F7G|06|F7G_MOVBCO|C|1|0|Mov Bancária|Movimentação Bancária
F7G|07|F7G_COMIS|C|1|0|Comissão|Gera Comissão
F7G|08|F7G_CHEQUE|C|1|0|Cheque|Movimentação c/ Cheque
F7G|09|F7G_ESPEC|C|1|0|Especie?|Movimento em Especie?
F7G|10|F7G_FORMRC|C|6|0|Forma Recbto|Forma de Recebimento
--- ### F7H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7H|01|F7H_FILIAL|C|6|0|Filial|Filial do Sistema
F7H|02|F7H_EST|C|2|0|UF|Unidade Federativa
F7H|03|F7H_CODMUN|C|5|0|Cd.Municipio|Código do Município
F7H|04|F7H_MUN|C|50|0|Municipio|Municipio
F7H|05|F7H_URLPRE|C|254|0|URL Prefeit.|URL da Prefeitura
--- ### F7I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7I|01|F7I_MOEDA|N|2|0|Moeda|Moeda
F7I|02|F7I_IDPROC|C|32|0|ID Processo|ID do Processamento
F7I|03|F7I_FILIAL|C|6|0|Filial|Filial do Sistema
F7I|04|F7I_EXTCDH|C|32|0|Cod.Header|Identif. Header
F7I|05|F7I_EXTCDD|C|36|0|Cod.Detail|Identif. Movimento Detail
F7I|06|F7I_GRPEMP|C|2|0|Grp.Empresa|Grupo de Empresa
F7I|07|F7I_EMPR|C|6|0|Empresa|Empresa
F7I|08|F7I_UNID|C|6|0|Unidade Neg.|Unidade de Negócio
F7I|09|F7I_FILNEG|C|6|0|Fil. Neg.|Filial de Negócio
F7I|10|F7I_ORGSYT|C|2|0|Origem Sist|Origem do Sistema
F7I|11|F7I_EMISSA|D|8|0|DT Emissão|Data de Emissao do Titulo
F7I|12|F7I_EMIS1|D|8|0|Dt Contab|Data de Contabilizacao
F7I|13|F7I_HIST|C|40|0|Historico|Historico do Título
F7I|14|F7I_TIPO|C|3|0|Tipo|Tipo do Titulo
F7I|15|F7I_TIPDSC|C|55|0|Descrição Tp|Descrição do Tipo
F7I|16|F7I_PREFIX|C|3|0|Prefixo|Prefixo do Título
F7I|17|F7I_NUM|C|9|0|Numero Titul|Número do Titulo
F7I|18|F7I_PARCEL|C|3|0|Parcela|Parcela do Titulo
F7I|19|F7I_DSCMDA|C|10|0|Desc.Moeda|Descrição Moeda
F7I|20|F7I_MOEDB|N|2|0|Moeda Banco|Moeda do Banco
F7I|21|F7I_DSCMDB|C|10|0|Desc.Moeda B|Descrição Moeda de Banco
F7I|22|F7I_VENCTO|D|8|0|Vencimento|Vencimento do Titulo
F7I|23|F7I_VENCRE|D|8|0|Vencto Real|Vencimento real do título
F7I|24|F7I_DTPGTO|D|8|0|Data  Mov|Data do movimento
F7I|25|F7I_TPEVNT|C|1|0|Tp. Evento|Tipo do Evento
F7I|26|F7I_BANCO|C|3|0|Banco|Código do Banco
F7I|27|F7I_AGENCI|C|5|0|Agência|Agência do banco
F7I|28|F7I_CONTA|C|10|0|Conta Banco|Conta Corrente no banco
F7I|29|F7I_FLBENF|C|6|0|Filial Benef|Filial do Beneficiário
F7I|30|F7I_CDBENF|C|6|0|Cod. Benef|Código do Beneficiário
F7I|31|F7I_LJBENF|C|2|0|Loja Benef|Loja do Beneficiário
F7I|32|F7I_NBENEF|C|80|0|Nome Benef.|Nome do Beneficiário
F7I|33|F7I_TPBENF|C|1|0|Tipo Benef.|Tipo do Beneficiário
F7I|34|F7I_ORBENF|C|2|0|Origem Benef|Origem do Beneficiário
F7I|35|F7I_MOVIM|C|3|0|Movimento|Maneira de Movimento
F7I|36|F7I_DSCMOV|C|55|0|Descrição|Descrição Movimento
F7I|37|F7I_IDMOV|C|32|0|Id. Mov.|Identif. Movimento
F7I|38|F7I_SALDO|N|16|2|Saldo|Saldo a Receber
F7I|39|F7I_VLPROP|N|16|2|Valor Propor|Valor Proporcional
F7I|40|F7I_VLCRUZ|N|16|2|Vlr R$|Valor na moeda nacional
F7I|41|F7I_CONVBS|N|11|4|Valor Conv.|Valor de Conversão
F7I|42|F7I_FXRTBS|C|1|0|Taxa Negocio|Taxa Fixa de Negócio
F7I|43|F7I_VLRCNT|N|16|2|Valor Mov.|Valor do Movimento
F7I|44|F7I_CONVCT|N|11|4|Conta Conv.|Conta de conversão
F7I|45|F7I_FXRTCT|C|1|0|Conta Conv|Taxa Fixa de Conta
F7I|46|F7I_CNTCTB|C|20|0|Cod. Conta|Código da Conta
F7I|47|F7I_DSCCTB|C|40|0|Desc.Conta|Descrição da Conta
F7I|48|F7I_NATCTA|C|2|0|Nat. Conta|Natureza da conta Contabi
F7I|49|F7I_CCUSTO|C|9|0|C. de Custo|Centro de Custo
F7I|50|F7I_DSCCCT|C|40|0|Desc.C.Custo|Descrição Centro de Custo
F7I|51|F7I_INTEGR|C|1|0|Integração|Tipo de Integração
F7I|52|F7I_DTDISP|D|8|0|Data Dispon.|Data de Disponibilização
F7I|53|F7I_NATURE|C|10|0|Natureza|Natureza
F7I|54|F7I_NATRAT|C|10|0|Nat. Rateio|Natureza do Orçamento
F7I|55|F7I_CCDRAT|C|9|0|CC Rateio|C.Custo Rateio
F7I|56|F7I_PAMOV|C|1|0|PA Mov?|PA Movimentou
F7I|57|F7I_CREDIT|C|20|0|Conta Cred|Conta Contabil a Credito
F7I|58|F7I_DEBITO|C|20|0|Conta Deb|Conta a Debito
F7I|59|F7I_CCD|C|9|0|C.Custo Deb|C.Custo a Debito
F7I|60|F7I_CCC|C|9|0|C.Custo Cred|C.Custo a Credito
F7I|61|F7I_ITEMCT|C|9|0|Item Contab|Item Contábil
F7I|62|F7I_ITEMD|C|9|0|Item Ctb Deb|Item Contabil a Debito
F7I|63|F7I_ITEMC|C|9|0|Item Ctb Crd|Item Contabil a Credito
F7I|64|F7I_CLVL|C|9|0|Classe Valor|Classe Valor
F7I|65|F7I_CLVLDB|C|9|0|Cl.Vlr. Deb|Classe de Valor a Debito
F7I|66|F7I_CLVLCR|C|9|0|Cl.Vlr. Cred|Classe de Valor a Credito
F7I|67|F7I_NUMBOR|C|6|0|Num Bordero|Numero do Bordero
F7I|68|F7I_HISTOR|C|40|0|Histórico|Histórico do Movimento
F7I|69|F7I_ORIGIN|C|10|0|Origem Cons.|Origem da Consulta
F7I|70|F7I_STAMP|C|26|0|Data/Hora|Data/Hora
F7I|71|F7I_FLXF01|C|30|0|FlexField01|Campo Flex 01
F7I|72|F7I_FLXF02|C|30|0|FlexField02|Campo Flex 02
F7I|73|F7I_FLXF03|C|30|0|FlexField03|Campo Flex 03
F7I|74|F7I_FLXF04|C|30|0|FlexField04|Campo Flex 04
F7I|75|F7I_FLXF05|C|30|0|FlexField05|Campo Flex 05
F7I|76|F7I_FLXF06|C|30|0|FlexField06|Campo Flex 06
F7I|77|F7I_FLXF07|C|30|0|FlexField07|Campo Flex 07
F7I|78|F7I_FLXF08|C|30|0|FlexField08|Campo Flex 08
F7I|79|F7I_FLXF09|C|30|0|FlexField09|Campo Flex 09
F7I|80|F7I_FLXF10|C|30|0|FlexField10|Campo Flex 10
F7I|81|F7I_FLXF11|C|100|0|FlexField11|Campo Flex 11
F7I|82|F7I_FLXF12|C|100|0|FlexField12|Campo Flex 12
F7I|83|F7I_FLXF13|C|100|0|FlexField13|Campo Flex 13
F7I|84|F7I_FLXF14|C|100|0|FlexField14|Campo Flex 14
F7I|85|F7I_FLXF15|C|100|0|FlexField15|Campo Flex 15
F7I|86|F7I_MSUID|C|36|0|Campo UUID|Campo UUID
--- ### F7J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7J|01|F7J_FILIAL|C|6|0|Filial|Filial do Sistema
F7J|02|F7J_ALIAS|C|3|0|Alias|Alias de Processamento
F7J|03|F7J_RECNO|N|15|0|Recno Origem|Recno de Origem
F7J|04|F7J_STAMP|C|26|0|Stamp Origem|Stamp Origem
F7J|05|F7J_MSUID|C|36|0|UUID|UUID
--- ### F7K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7K|01|F7K_FILIAL|C|6|0|Filial|Filial do Sistema
F7K|02|F7K_COD|C|3|0|Codigo|Codigo do Banco
F7K|03|F7K_AGENCI|C|5|0|Nro Agencia|Agencia do banco
F7K|04|F7K_DVAGE|C|1|0|DV Agencia|Digito Verific. Agencia
F7K|05|F7K_NUMCON|C|10|0|Nro Conta|Conta Corrente no Banco
F7K|06|F7K_DVCTA|C|1|0|DV Conta|Digito Verific. Conta
F7K|07|F7K_NOME|C|40|0|Nome Banco|Nome do banco
F7K|08|F7K_MOEDA|N|2|0|Moeda|Moeda
F7K|09|F7K_CONTA|C|20|0|Conta Contab|Conta Contabil do Banco
--- ### F7N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7N|01|F7N_IDPROC|C|32|0|ID Processo|ID do Processamento
F7N|02|F7N_FILIAL|C|6|0|Filial|Filial do Sistema
F7N|03|F7N_EXTCDH|C|32|0|Id. Mov.|Identif. Movimento
F7N|04|F7N_EXTCDD|C|32|0|Id. Mov. Det|Identif. Movimento Detail
F7N|05|F7N_DATA|D|8|0|Data Mov.|Data do Movimento
F7N|06|F7N_VALOR|N|16|2|Valor Mov.|Valor do Movimento
F7N|07|F7N_NATURE|C|10|0|Natureza|Natureza
F7N|08|F7N_TPEVNT|C|1|0|Rec/Pag|Recebimento ou Pagamento
F7N|09|F7N_BENEF|C|2|0|Beneficiário|Beneficiário
F7N|10|F7N_TPDOC|C|2|0|Tipo do Doc.|Tipo da movimentação
F7N|11|F7N_DOC|C|50|0|Documento|Numero documento
F7N|12|F7N_HISTOR|C|40|0|Histórico|Histórico do Movimento
F7N|13|F7N_CCUSTO|C|9|0|C. de Custo|Centro de Custo
F7N|14|F7N_CNTCTB|C|1|0|Conta Contab|Conta Contábil
F7N|15|F7N_ORGSYT|C|2|0|Origem Sist|Origem do Sistema
F7N|16|F7N_TXMOED|N|11|4|Tx moeda Mov|Taxa contratada moeda Mov
F7N|17|F7N_ORIGEM|C|10|0|Origem|Origem Movimento
F7N|18|F7N_DTDISP|D|8|0|Data Dispon.|Data de Disponibilidade
F7N|19|F7N_DEBITO|C|20|0|Conta Debito|Conta Debito
F7N|20|F7N_CREDIT|C|20|0|Cta. Credito|Conta Credito
F7N|21|F7N_CCD|C|9|0|C.Custo Deb|Centro de Custo Debito
F7N|22|F7N_CCC|C|9|0|C.Custo Crd|Centro de Custo Credito
F7N|23|F7N_ITEMD|C|9|0|Item Debito|Item Contábil Debito
F7N|24|F7N_ITEMC|C|9|0|Item Credito|Item Contábil Credito
F7N|25|F7N_CLVLDB|C|9|0|Cl Valor Deb|Classe Valor Debito
F7N|26|F7N_CLVLCR|C|9|0|Cl Valor Crd|Classe Valor Credito
F7N|27|F7N_MOEDA|C|2|0|Moeda|Moeda
F7N|28|F7N_DSCMDA|C|10|0|Desc.Moeda|Descrição Moeda
F7N|29|F7N_BANCO|C|3|0|Banco|Código do Banco
F7N|30|F7N_AGENCI|C|5|0|Agência|Agência do Banco
F7N|31|F7N_CONTA|C|10|0|Conta Banco|Conta Corrente no Banco
F7N|32|F7N_FLXF01|C|30|0|FlexField01|Campo Flex 01
F7N|33|F7N_FLXF02|C|30|0|FlexField02|Campo Flex 01
F7N|34|F7N_FLXF03|C|30|0|FlexField03|Campo Flex 03
F7N|35|F7N_FLXF04|C|30|0|FlexField04|Campo Flex 04
F7N|36|F7N_FLXF05|C|30|0|FlexField05|Campo Flex 05
F7N|37|F7N_GRPEMP|C|2|0|Grp. Empresa|Grupo de Empresa
F7N|38|F7N_EMPR|C|6|0|Empresa|Empresa
F7N|39|F7N_UNID|C|6|0|Unidade Neg.|Unidade de Negócio
F7N|40|F7N_FILNEG|C|6|0|Fil. Neg.|Filial de Negocio
F7N|41|F7N_MSUID|C|36|0|Campo UUID|Campo UUID
F7N|42|F7N_STAMP|C|26|0|Data/Hora|Data/Hora
--- ### F7O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7O|01|F7O_FILIAL|C|6|0|Filial|Filial do Sistema
F7O|02|F7O_ORIGEM|C|1|0|Processo|Processo Origem
F7O|03|F7O_TABELA|C|3|0|Tabela|Tabela a Filtro Campo
F7O|04|F7O_COLUNA|C|10|0|Campo|Campo
F7O|05|F7O_FLEX|C|2|0|Numero|Numero
--- ### F7P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7P|01|F7P_FILIAL|C|6|0|Filial|Filial do Sistema
F7P|02|F7P_PROCES|C|7|0|Processo|Processo Executado
F7P|03|F7P_INICIO|C|26|0|Data Inicio|Inicio do Processamento
F7P|04|F7P_FIM|C|26|0|Data Fim|Fim do Processamento
F7P|05|F7P_QTDE|C|15|0|Quantidade|Quantidade de Processados
F7P|06|F7P_IDPROC|C|32|0|ID Processo|ID do Processamento
F7P|07|F7P_LOTE|C|6|0|Lote|Lote de Processamento
--- ### F7Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7Q|01|F7Q_FILIAL|C|6|0|Filial|Filial do Sistema
F7Q|02|F7Q_IDF7Q|C|32|0|Código|Código
F7Q|03|F7Q_IDDOC|C|32|0|ID Adiantam.|ID Título de Adiantamento
F7Q|04|F7Q_TABORI|C|3|0|Tab Orig.|Tabela de origem
F7Q|05|F7Q_SERIE|C|3|0|Série|Série da Nota Fiscal
F7Q|06|F7Q_DOC|C|9|0|Nota Fiscal|Número da Nota Fiscal
F7Q|07|F7Q_CLIFOR|C|6|0|Cliente/Forn|Código Cliente/Fornecedor
F7Q|08|F7Q_LOJA|C|2|0|Loja|Loja Cliente/Fornecedor
F7Q|09|F7Q_FILORI|C|6|0|Filial Orig|Filial de Origem
--- ### F7R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7R|01|F7R_FILIAL|C|6|0|Filial|Filial do Sistema
F7R|02|F7R_IDRET|C|32|0|ID Dedução|ID Dedução
F7R|03|F7R_TIPDED|C|1|0|Tipo Dedução|Tipo de dedução
F7R|04|F7R_VALOR|N|16|2|Valor|Valor da dedução
F7R|05|F7R_APLIC|C|1|0|Aplicação|Tipo de aplicação
--- ### F7S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7S|01|F7S_FILIAL|C|6|0|Filial|Filial do Sistema
F7S|02|F7S_IDRET|C|32|0|Id Tabela|Identificação da tabela
F7S|03|F7S_ITEM|C|4|0|Item|Item da tabela
F7S|04|F7S_FAIXA|N|16|2|Valor Limite|Valor limite da faixa
F7S|05|F7S_VLRRED|N|16|2|Vlr. Redução|Valor da redução
F7S|06|F7S_FATOR|N|16|8|Fator|Fator de redução
--- ### F7U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F7U|01|F7U_FILIAL|C|6|0|Filial|Filial do Sistema
F7U|02|F7U_TPNEG|C|2|0|Cod. Tp Nego|Codigo Tipo Negociação
F7U|03|F7U_DESCNE|C|30|0|Desc. Tp Neg|Descrição Tp Negociação
F7U|04|F7U_SITUAC|C|1|0|Situação|Situação do Título
F7U|05|F7U_DESCSI|C|40|0|Desc. Situac|Descrição Situação
F7U|06|F7U_BAIXA|C|1|0|Efetua Baixa|Efetua Baixa?
--- ### FI0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI0|01|FI0_FILIAL|C|6|0|Filial|Filial do sistema
FI0|02|FI0_DTPRC|D|8|0|Dt. Proc.|Data do processamento
FI0|03|FI0_HRPRC|C|5|0|Hora Proc.|Hora do processamento
FI0|04|FI0_BCO|C|3|0|Banco|Banco processamento
FI0|05|FI0_AGE|C|5|0|Agencia|Agencia processamento
FI0|06|FI0_CTA|C|10|0|Conta|Conta processamento
FI0|07|FI0_ARQ|C|40|0|Arq. Proc.|Arquivo processado
FI0|08|FI0_IDARQ|C|10|0|Id. Arq Proc|Id Arquivo processado
FI0|09|FI0_USU|C|9|0|Usuario|Usuario que processou
FI0|10|FI0_LASTLN|N|8|0|Ult.lin.Proc|Ultima linha processada
FI0|11|FI0_SEQ|C|2|0|Seq. Proc.|Sequencia processamento
FI0|12|FI0_LOTE|C|4|0|Lote|Lote da Baixa
--- ### FI1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI1|01|FI1_FILIAL|C|6|0|Filial|Filial do sistema
FI1|02|FI1_IDARQ|C|10|0|Id Arq. Proc|Id arquivo processado
FI1|03|FI1_IDTIT|C|23|0|Id Titulo|Id titulo processado
FI1|04|FI1_OCORB|C|3|0|Ocor.Arq.Ret|Ocorrencia Arq Retorno
FI1|05|FI1_OCORS|C|3|0|Ocorr. Sist.|Ocorrencia no sistema
FI1|06|FI1_SEQ|C|2|0|Seq. Proc.|Seq. Processamento
--- ### FI2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI2|01|FI2_FILIAL|C|6|0|Filial|Filial do Sistema
FI2|02|FI2_OCORR|C|2|0|Ocorrencia|Ocorrencia
FI2|03|FI2_DESCOC|C|20|0|Desc Ocorr|Desc Ocorr
FI2|04|FI2_PREFIX|C|3|0|Prefixo|Prefixo
FI2|05|FI2_TITULO|C|9|0|Titulo|Titulo
FI2|06|FI2_PARCEL|C|3|0|Parcela|Parcela
FI2|07|FI2_TIPO|C|3|0|Tipo|Tipo
FI2|08|FI2_CODCLI|C|6|0|Cliente|Cliente
FI2|09|FI2_LOJCLI|C|2|0|Loja Cliente|Loja Cliente
FI2|10|FI2_CODFOR|C|6|0|Fornecedor|Fornecedor
FI2|11|FI2_LOJFOR|C|2|0|Loja Forn.|Loja Forn.
FI2|12|FI2_GERADO|C|1|0|Gerado|Gerado
FI2|13|FI2_NUMBOR|C|6|0|BORDERO|BORDERO
FI2|14|FI2_CARTEI|C|1|0|Carteira|Carteira
FI2|15|FI2_DTGER|D|8|0|Data geracao|Data geracao
FI2|16|FI2_DTOCOR|D|8|0|Data Ocorr.|Data Ocorr.
FI2|17|FI2_VALANT|C|30|0|Valor anter.|Valor anterior
FI2|18|FI2_VALNOV|C|30|0|Valor novo|Valor novo
FI2|19|FI2_CAMPO|C|10|0|Campo|Campo
FI2|20|FI2_TIPCPO|C|1|0|Tipo Campo|Tipo Campo
FI2|21|FI2_SEQ|C|6|0|Sequencia|Sequencia da Ocorrencia
FI2|22|FI2_HISTOR|M|80|0|Historico|Historico
FI2|23|FI2_BORAPI|C|1|0|Bordero API|Bordero API
FI2|24|FI2_TRANSF|C|1|0|Status Trans|Status de Transferencia
FI2|25|FI2_APIMSG|M|10|0|Eventos API|Enventos da API
FI2|26|FI2_APILOG|M|10|0|Mensagem API|Mensagem da API
FI2|27|FI2_OPEAPI|C|1|0|Operacao API|Pperaçao API
--- ### FI4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI4|01|FI4_FILIAL|C|6|0|Filial|Filial do Sistema
FI4|02|FI4_CODIGO|C|3|0|Codigo|Codigo
FI4|03|FI4_OPER|C|50|0|Operação|Operação
--- ### FI5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI5|01|FI5_FILIAL|C|6|0|Filial|Filial do Sistema
FI5|02|FI5_CENDAT|D|8|0|Data Cenário|Data do Cenário
FI5|03|FI5_CENCOD|C|3|0|Cod. Cenário|Código do Cenário
FI5|04|FI5_CENSIT|C|1|0|Sit. Cenario|Situação do Cenário
FI5|05|FI5_CENSEQ|N|3|0|Seq. Cenario|Seq. Aplic. Cenario
--- ### FI6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI6|01|FI6_FILIAL|C|6|0|Filial|Filial do Sistema
FI6|02|FI6_CENCOD|C|3|0|Cod. Cenario|Codigo Cenario
FI6|03|FI6_CENDAT|D|8|0|Data Cenario|Data do Cenario
FI6|04|FI6_CENTAB|C|3|0|Tab. Cenario|Tabela do Cenario
FI6|05|FI6_CENREC|C|20|0|Rec.Cenario|Recno do Cenario
FI6|06|FI6_CENCOP|C|3|0|Cod.Op. Real|Codigo Operacao Realizada
FI6|07|FI6_CENIDT|C|20|0|Id.Transfer.|ID da Transferência
FI6|08|FI6_CENOCT|C|50|0|Cont.Campo|Conteúdo Antigo do Campo
FI6|09|FI6_CENNCT|C|50|0|Cont.Campo|Conteúdo Novo do campo
--- ### FI7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI7|01|FI7_FILIAL|C|6|0|Filial|Filial do Sistema
FI7|02|FI7_PRFORI|C|3|0|Pref. Ori.|Prefixo Origem
FI7|03|FI7_NUMORI|C|9|0|Num. Ori.|Numero Origem
FI7|04|FI7_PARORI|C|3|0|Parc. Ori.|Parcela Origem
FI7|05|FI7_TIPORI|C|3|0|Tipo Ori.|Tipo Origem
FI7|06|FI7_CLIORI|C|6|0|Cliente Ori|Cliente Origem
FI7|07|FI7_LOJORI|C|2|0|Loja Ori|Loja Origem
FI7|08|FI7_FILDES|C|6|0|Filial Dest|Filial Titulo Destino
FI7|09|FI7_PRFDES|C|3|0|Pref.Dest.|Prefixo Destino
FI7|10|FI7_NUMDES|C|9|0|Num.Dest.|Numero Destino
FI7|11|FI7_PARDES|C|3|0|Parc.Dest.|Parcela Destino
FI7|12|FI7_TIPDES|C|3|0|Tipo Dest.|Tipo Destino
FI7|13|FI7_CLIDES|C|6|0|Cliente Dest|Cliente Destino
FI7|14|FI7_LOJDES|C|2|0|Loja Dest|Loja Destino
FI7|15|FI7_VALOR|N|16|2|Valor|Valor Titulo Destino
FI7|16|FI7_STATUS|C|1|0|Status|Status Tit. Destino
FI7|17|FI7_DATA|D|8|0|Data Ocorr|Data Ocorrência
FI7|18|FI7_CHKORI|C|100|0|Chk. Origem|Chave do Registro Origem
--- ### FI8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI8|01|FI8_FILIAL|C|6|0|Filial|Filial do Sistema
FI8|02|FI8_PRFORI|C|3|0|Pref. Ori.|Prefixo Origem
FI8|03|FI8_NUMORI|C|9|0|Num. Ori.|Numero Origem
FI8|04|FI8_PARORI|C|3|0|Parc.Ori|Parcela Origem
FI8|05|FI8_TIPORI|C|3|0|Tipo Ori.|Tipo Origem
FI8|06|FI8_FORORI|C|6|0|Forn. Ori.|Fornecedor Origem
FI8|07|FI8_LOJORI|C|2|0|Loja Ori|Loja Origem
FI8|08|FI8_FILDES|C|6|0|Filial Dest|Filial Titulo Destino
FI8|09|FI8_PRFDES|C|3|0|Pref.Dest.|Prefixo Destino
FI8|10|FI8_NUMDES|C|9|0|Num.Dest.|Numero Destino
FI8|11|FI8_PARDES|C|3|0|Parc.Dest.|Parcela Destino
FI8|12|FI8_TIPDES|C|3|0|Tipo Dest.|Tipo Destino
FI8|13|FI8_FORDES|C|6|0|Forn. Dest.|Fornecedor Destino
FI8|14|FI8_LOJDES|C|2|0|Loja Dest|Loja Destino
FI8|15|FI8_VALOR|N|16|2|Valor|Valor Titulo Destino
FI8|16|FI8_STATUS|C|1|0|Status|Status Tit. Destino
FI8|17|FI8_DATA|D|8|0|Data Ocorr|Data Ocorrência
FI8|18|FI8_CHKORI|C|100|0|Chk. Origem|Chave do Registro Origem
--- ### FI9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FI9|01|FI9_FILIAL|C|6|0|Filial|Filial do Sistema
FI9|02|FI9_IDDARF|C|20|0|ID Darf|Identificação DARF
FI9|03|FI9_EMISS|D|8|0|Emissão|Data de Emissão DARF
FI9|04|FI9_PREFIX|C|3|0|Prefixo|Prefixo do titulo
FI9|05|FI9_NUM|C|9|0|Número|Número do Titulo
FI9|06|FI9_PARCEL|C|3|0|Parcela|Parcela do Titulo
FI9|07|FI9_TIPO|C|3|0|Tipo|Tipo do Titulo
FI9|08|FI9_FORNEC|C|6|0|Forn. Orig.|Fornecedor Original
FI9|09|FI9_LOJA|C|2|0|Loja Ori.|Loja do Fornecedor Origin
FI9|10|FI9_VALOR|N|16|2|Valor|Valor do Titulo
FI9|11|FI9_STATUS|C|1|0|Status|Status Darf
FI9|12|FI9_CODRET|C|4|0|Cd. Retencao|Codigo de Retencao
FI9|13|FI9_FILCTR|C|6|0|Fil.Central|Filial Centralizadora
FI9|14|FI9_REFER|C|15|0|Num Refer|Numero Referencia DARF
FI9|15|FI9_APURA|D|8|0|Apuração|Período de Apuração
FI9|16|FI9_PERIOD|C|2|0|Periodicid.|Periodicidade
FI9|17|FI9_VENCIM|D|8|0|Vencimento|Vencimento do DARF
FI9|18|FI9_INCORP|C|14|0|CNPJ INCORP|CNPJ DA INCORPORADORA
FI9|19|FI9_ESTABE|C|14|0|CNPJ Estabe|CNPJ Estabelecimento
FI9|20|FI9_FILORI|C|6|0|Fil.Orig.Tit|Filial Origem do Título
--- ### FIA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIA|01|FIA_FILIAL|C|6|0|Filial|Filial
FIA|02|FIA_CLIENT|C|6|0|Cliente|Cliente
FIA|03|FIA_LOJA|C|2|0|Loja|Loja
FIA|04|FIA_PREFIX|C|3|0|Prefixo|Prefixo
FIA|05|FIA_NUM|C|9|0|Numero|Numro
FIA|06|FIA_DTPROV|D|8|0|Data Provis.|Data Provisao
FIA|07|FIA_PARCEL|C|3|0|Parcela|Parcela
FIA|08|FIA_TIPO|C|3|0|Tipo|Tipo
FIA|09|FIA_VALOR|N|14|2|Valor|Valor
FIA|10|FIA_MOEDA|N|2|0|Moeda|Moeda
FIA|11|FIA_VLLOC|N|14|2|Vl. M. Local|Valor moeda local
FIA|12|FIA_SEQ|C|3|0|Sequencia|Sequencia provisao
FIA|13|FIA_DIACTB|C|2|0|Código Diár.|Código diário da contab.
FIA|14|FIA_LA|C|1|0|Flag Contab|Flag Contabil
FIA|15|FIA_NODIA|C|10|0|Seq. Diário|Seq. diário Contabilidade
--- ### FIB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIB|01|FIB_FILIAL|C|6|0|Filial|Filial do sistema.
FIB|02|FIB_LOTE|C|10|0|Lote|Numero Lote
FIB|03|FIB_USER|C|6|0|Usuário|Usuário
FIB|04|FIB_NOME|C|20|0|Nome|Nome
FIB|05|FIB_DTABR|D|8|0|Dt Abre|Data Abertura
FIB|06|FIB_HRABR|C|5|0|Hr Abre|Hora Abertura
FIB|07|FIB_VLRABR|N|12|2|Valor Abertu|Valor Abertura
FIB|08|FIB_DTFCH|D|8|0|Dt. Fechamen|Dt. Fechamento
FIB|09|FIB_HRFCH|C|5|0|Hora Fecha|Hora Fechamento
FIB|10|FIB_DTCONC|D|8|0|Dt. Concilia|Dt. Conciliação
FIB|11|FIB_SITCON|C|1|0|Situação|Sit. Conciliacao
FIB|12|FIB_VLRDN|N|12|2|V. Efetivo D|V. Efetivo DN
FIB|13|FIB_VLRCH|N|12|2|V. Efetivo C|Valor Efetivo CH
FIB|14|FIB_VLRCC|N|12|2|V. Efetivo C|V. Efetivo C. Cred
FIB|15|FIB_VLRCD|N|12|2|V. Efetivo C|V. Efetivo C. Deb
FIB|16|FIB_VLRNC|N|12|2|V. Efetivo N|V. Efetivo NCC
FIB|17|FIB_TPABRE|C|1|0|Tipo Abertur|Tipo Abertura
FIB|18|FIB_TPFECH|C|1|0|Tp Fecha|Tipo Fechamento
FIB|19|FIB_USABRE|C|10|0|Usuario Abre|Usuario Abre
FIB|20|FIB_USFECH|C|10|0|Usuario Fech|Usuario Fecha
FIB|21|FIB_ENCER|C|1|0|Encerrado|Encerrado
--- ### FIC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIC|01|FIC_FILIAL|C|6|0|Filial|Filial
FIC|02|FIC_FLGSIT|C|1|0|Sit.|Situação Caixa
FIC|03|FIC_LOTE|C|10|0|Lote|Cód. Lote
FIC|04|FIC_TRANS|N|11|0|Transação|Numero Transação
FIC|05|FIC_CODCXA|C|10|0|Caixa|Código do Caixa.
FIC|06|FIC_VLRREC|N|12|2|Valor Recebi|Valor Recebido
FIC|07|FIC_TPPAG|C|1|0|Tp. Pagto|Tipo Pagamento
FIC|08|FIC_DTREC|D|8|0|Dt. Recebime|Dt. Recebimento
FIC|09|FIC_HRREC|C|5|0|Hora Recebim|Hora Recebimento
FIC|10|FIC_ATIVO|C|1|0|Lote Ativo|Lote Ativo
FIC|11|FIC_CARTR|C|40|0|Trans. Cart|Trans. Cart
FIC|12|FIC_CAROPE|C|10|0|Operadora CC|Operadora CC
FIC|13|FIC_MIXDIN|N|12|2|Valor Dn|Valor Dn (mix)
FIC|14|FIC_MIXCHQ|N|12|2|Valor Chq|Valor Cheque (mix)
FIC|15|FIC_MIXDEB|N|12|2|Valor C.Deb|Valor C.Deb (mix)
FIC|16|FIC_MIXCRD|N|12|2|Valor C.Cred|Valor C.Cred (mix)
FIC|17|FIC_MIXNCC|N|12|2|Valor NCC|Valor NCC (mix)
--- ### FID
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FID|01|FID_FILIAL|C|6|0|Filial|Filial
FID|02|FID_USER|C|6|0|Usuario|Usuario
FID|03|FID_NOME|C|40|0|Nome|Nome Operador
FID|04|FID_BLOQ|C|1|0|Bloqueado|Usuário Bloqueado
FID|05|FID_DESC|C|1|0|Desconto|Pode Atribuir desconto
FID|06|FID_MULTA|C|1|0|Multas|Pode alterar multas
FID|07|FID_MAXDES|N|10|0|Desc. Max|Valor maximo descon
FID|08|FID_MAXMUL|N|10|0|Multa Max|Valor maximo multa
FID|09|FID_SUPER|C|1|0|Supervisor|User Supervisor
FID|10|FID_ABRECX|C|1|0|Abre Cx|Abre Caixa
FID|11|FID_FECHCX|C|1|0|Fecha Caixa|Fecha Caixa
FID|12|FID_NCAIXA|C|10|0|Nro Caixa|Nro Caixa
FID|13|FID_TPDES|C|1|0|Tipo Desc|Tipo Desconto
FID|14|FID_TPMUL|C|1|0|Tipo Multa|Tipo Multa
FID|15|FID_ESTOR|C|1|0|Estorno|Pode estornar Oper.
FID|16|FID_JUROS|C|1|0|Juros|Pode alterar Juros
FID|17|FID_MAXJUR|N|10|2|Juros Max|Valor maximo Juros.
FID|18|FID_TPJUR|C|1|0|Tipo Juros|Tipo Juros
FID|19|FID_TROCOP|N|11|2|Troco Padrao|Troco Padrao
FID|20|FID_CHEQP|C|1|0|Pode Ch-Pre|Oper. recebe chq-pré?
FID|21|FID_QTDCHQ|N|3|0|Lim Dias Ch|Limite Dias Chq-pré
--- ### FIE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIE|01|FIE_FILIAL|C|6|0|Filial|Filial do Sistema
FIE|02|FIE_CART|C|1|0|Carteira|Identificação da carteira
FIE|03|FIE_PEDIDO|C|6|0|Pedido|Número do pedido
FIE|04|FIE_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FIE|05|FIE_NUM|C|9|0|Número|Número do Titulo
FIE|06|FIE_PARCEL|C|3|0|Parcela|Parcela do Titulo
FIE|07|FIE_TIPO|C|3|0|Tipo|Tipo do Titulo
FIE|08|FIE_CLIENT|C|6|0|Cliente|Cliente
FIE|09|FIE_FORNEC|C|6|0|Fornec.|Fornecedor
FIE|10|FIE_LOJA|C|2|0|Loja|Loja do Cliente/Fornec
FIE|11|FIE_VALOR|N|16|2|Valor|Valor Relacionado
FIE|12|FIE_SALDO|N|16|2|Saldo|Valor  relacionado usado
FIE|13|FIE_FILORI|C|6|0|Fil Origem|Filial de Origem
--- ### FIF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIF|01|FIF_FILIAL|C|6|0|Filial|Filial do Sistema
FIF|02|FIF_TPREG|C|2|0|Tp Registro|Tiipo do registro
FIF|03|FIF_INTRAN|C|30|0|Ind. Trans.|Indicador de transação
FIF|04|FIF_CODEST|C|15|0|Cod Estab|Código do estabelecimento
FIF|05|FIF_DTTEF|D|8|0|Data Venda|Data da Venda
FIF|06|FIF_NURESU|C|10|0| Nr Resumo|Número do resumo
FIF|07|FIF_NUCOMP|C|100|0|Comprovante|Número do comprovante
FIF|08|FIF_NSUTEF|C|50|0|NSU Sitef|NSU Sitef
FIF|09|FIF_NUCART|C|19|0|Nro Cartão|Número do cartão
FIF|10|FIF_VLBRUT|N|16|2|Vlr Venda|Valor da venda (Bruto)
FIF|11|FIF_TOTPAR|C|2|0|Tot.Parcelas|Total de parcelas
FIF|12|FIF_VLLIQ|N|16|2|Vlr Liquido|Valor Líquido
FIF|13|FIF_DTCRED|D|8|0|Dt Crédito|Data de Crédito
FIF|14|FIF_PARCEL|C|3|0|Parcela|Parcela Sitef
FIF|15|FIF_TPPROD|C|1|0|Tipo Produto|Tipo do produto
FIF|16|FIF_CAPTUR|C|1|0|Captura|Captura
FIF|17|FIF_CODRED|C|6|0|Ident. Rede|Código ident. rede
FIF|18|FIF_CODBCO|C|3|0|Código banco|Código do banco
FIF|19|FIF_CODAGE|C|5|0|Agência|Código da agência
FIF|20|FIF_NUMCC|C|10|0|Conta Corren|Conta corrente
FIF|21|FIF_VLCOM|N|16|2|Vlr Comissão|Valor da Comissão
FIF|22|FIF_TXSERV|N|6|2|Taxa Serv|Valor da taxa de serviço
FIF|23|FIF_CODLOJ|C|15|0|Loja SITEF|Código da loja sitef
FIF|24|FIF_CODAUT|C|50|0|Autorização|Código de autorização
FIF|25|FIF_CUPOM|C|20|0|Cupom Fiscal|Cupom Fiscal
FIF|26|FIF_SEQREG|C|6|0|Seq. Registr|Seq. Registro no Arquivo
FIF|27|FIF_DTAJST|D|8|0|Data Ajuste|Data do Ajuste
FIF|28|FIF_CODMAJ|C|15|0|Motivo Ajust|Cód. Motivo Ajuste
FIF|29|FIF_DSCMAJ|C|64|0|Desc Ajuste|Descrição do ajuste
FIF|30|FIF_STATUS|C|1|0|Status|Status do Título
FIF|31|FIF_DTBAIX|D|8|0|Data Baixa|Data da Baixa
FIF|32|FIF_DTIMP|D|8|0|Data Import|Data da importação
FIF|33|FIF_USERGA|C|17|0|Log de Alter|Log de Alteracao
FIF|34|FIF_MSIMP|C|8|0|Ident. Impor|Ident. Imp. Dados
FIF|35|FIF_PREFIX|C|3|0|Prefixo|Rastro Prefixo SE1
FIF|36|FIF_NUM|C|9|0|No Titulo|Rastro Titulo SE1
FIF|37|FIF_PARC|C|3|0|Rastro Parc.|Rastro Parcela SE1
FIF|38|FIF_TIPO|C|3|0|Tipo|Rastro Tipo SE1
FIF|39|FIF_PARALF|C|3|0|Parc.Alfanum|Parcela Alfanumerica
FIF|40|FIF_CODFIL|C|6|0|Filial Tef|Filial Tef
FIF|41|FIF_CODBAN|C|4|0|Cod. Bandeir|Codigo Bandeira
FIF|42|FIF_SEQFIF|C|6|0|Seq. Tab FIF|Sequencial
FIF|43|FIF_DTANT|D|8|0|Dt. Antec.|Data Credito Antecipado
FIF|44|FIF_STVEND|C|1|0|Status Venda|Status Venda
FIF|45|FIF_DTCONV|D|8|0|Dt.Conc.Vend|Data Conciliação Venda
FIF|46|FIF_CODJUS|C|4|0|Cod. Just.|Codigo Justificativa
FIF|47|FIF_DESJUS|C|30|0|Desc. Just.|Descrição Justificativa
FIF|48|FIF_DESJUT|C|150|0|Justificar|Justificar
FIF|49|FIF_CODADM|C|3|0|Adm. Financ.|Administradora Financeira
FIF|50|FIF_DTVEN|D|8|0|Dt.Conc.Ven|Data Conciliação Venda.
FIF|51|FIF_DTPAG|D|8|0|Dt.Conc.Pag|Data Conciliação Pagto
FIF|52|FIF_USUVEN|C|20|0|Usr Conc Ven|Usuário conciliação venda
FIF|53|FIF_USUPAG|C|20|0|Usr Conc Pag|Usuário Pagamento
FIF|54|FIF_ARQVEN|C|50|0|Arq. Venda|Arquivo de Venda
FIF|55|FIF_PGJUST|C|4|0|Cd.Just.Pagt|Cod. Justificativa Pagto.
FIF|56|FIF_PGDES1|C|30|0|Desc. Just.|Descrição Justificativa
FIF|57|FIF_ARQPAG|C|50|0|Arq. Pagto|Arquivo de Pagamento
FIF|58|FIF_NSUARQ|C|50|0|NSU SITEF|NSU SITEF do Arquivo
FIF|59|FIF_PGDES2|C|150|0|Justificar|Justificar
FIF|60|FIF_IDORAJ|C|20|0|Id Or. Aj.|Id Original Ajuste
FIF|61|FIF_MODPAG|C|1|0|Modo Pagto.|Modo de Pagamento
FIF|62|FIF_CNPJRE|C|14|0|CNPJ/CPF Rec|CNPJ/CPF Recebedor
FIF|63|FIF_DTNEG|D|8|0|Data Negocia|Data Negociacao
FIF|64|FIF_NUMNEG|C|20|0|Numero Negoc|Numero Negociacao
FIF|65|FIF_TPNEG|C|2|0|Tipo Negocia|Tipo Negociação
FIF|66|FIF_VLNEG|N|16|2| Valor Negoc| Valor Negociado
FIF|67|FIF_VLORIG|N|16|2|Valor Origin|Valor Original
FIF|68|FIF_TPPLAN|C|1|0|TP Plano RV|Tipo do plano da Transaçã
FIF|69|FIF_DTCROR|D|8|0|Dt Cred Orig|Data Credito Original
FIF|70|FIF_CNPJPA|C|14|0|CNPJ/CPF Par|CNPJ/CPF Parceiro
--- ### FIG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIG|01|FIG_FILIAL|C|6|0|Filial|Filial do Sistema
FIG|02|FIG_DATA|D|8|0|Data Process|Dt. Processamento Arquivo
FIG|03|FIG_FORNEC|C|6|0|Fornecedor|Codigo Fornecedor
FIG|04|FIG_LOJA|C|2|0|Loja|Loja Fornecedor
FIG|05|FIG_NOMFOR|C|20|0|Nome Fornec.|Nome do Fornecedor
FIG|06|FIG_TITULO|C|15|0|Doc.Cobranca|Cod.Titulo DDA
FIG|07|FIG_TIPO|C|3|0|Tipo|Espécie do titulo DDA
FIG|08|FIG_VENCTO|D|8|0|Dt. Vencto.|Data de Vencimento
FIG|09|FIG_VALOR|N|16|2|Valor|Valor do Titulo
FIG|10|FIG_CONCIL|C|1|0|Conciliado|Conciliado
FIG|11|FIG_DTCONC|D|8|0|Dt.Conciliac|Data da Conciliacao
FIG|12|FIG_USCONC|C|25|0|Usuario Conc|Usuario Conciliacao DDA
FIG|13|FIG_DDASE2|C|100|0|Titulo SE2|Titulo Relacionado SE2
FIG|14|FIG_CNPJ|C|14|0|CNPJ/CPF|CNPJ/CPF
FIG|15|FIG_CODBAR|C|44|0|Cod. Barras|Codigo de Barras DDA
FIG|16|FIG_IDEKEY|C|36|0|Idempotencia|Chave de idempotencia
--- ### FIH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIH|01|FIH_FILIAL|C|6|0|Filial|Filial do sistema
FIH|02|FIH_ENTORI|C|3|0|Ent.Orig.|Entidade Origem
FIH|03|FIH_PREFOR|C|3|0|Pref.Orig.|Prefixo Origem
FIH|04|FIH_NUMORI|C|9|0|Num.Orig.|Numero Origem
FIH|05|FIH_PARCOR|C|3|0|Parc.Orig.|Parcela Origem
FIH|06|FIH_TIPOOR|C|3|0|Tipo Orig.|Tipo Origem
FIH|07|FIH_CFORI|C|6|0|Cli/For Orig|Cliente/Fornecedor Origem
FIH|08|FIH_LOJAOR|C|2|0|Loja Orig.|Loja Origem
FIH|09|FIH_SEQ|C|2|0|Sequencia|Sequencia
FIH|10|FIH_ENTDES|C|3|0|Ent. Dest.|Entidade Destino
FIH|11|FIH_PREFDE|C|3|0|Pref.Dest.|Prefixo destino
FIH|12|FIH_NUMDES|C|9|0|Num.Dest.|numero Destino
FIH|13|FIH_PARCDE|C|3|0|Parc.Dest.|Parcela Destino
FIH|14|FIH_TIPODE|C|3|0|Tipo Dest.|Tipo Destino
FIH|15|FIH_CFDES|C|6|0|Cli/For Dest|Cliente/Fornecedor Dest.
FIH|16|FIH_LOJADE|C|2|0|Loja Dest.|Loja Destino
FIH|17|FIH_FILDES|C|6|0|Filial Dest.|Filial Destino
FIH|18|FIH_ROTINA|C|10|0|Rotina|Rotina
FIH|19|FIH_OPERAC|C|2|0|Operação|Operação
--- ### FII
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FII|01|FII_FILIAL|C|6|0|Filial|Filial do Sistema
FII|02|FII_ENTORI|C|3|0|Ent.Orig.|Entidade Origem
FII|03|FII_PREFOR|C|3|0|Pref.Orig.|Prefixo Origem
FII|04|FII_NUMORI|C|9|0|Num.Orig.|Numero Origem
FII|05|FII_PARCOR|C|3|0|Parc.Orig.|Parcela Origem
FII|06|FII_TIPOOR|C|3|0|Tipo Orig.|Tipo Origem
FII|07|FII_CFORI|C|6|0|Cli/For Orig|Cliente/Fornecedor
FII|08|FII_LOJAOR|C|2|0|Loja Orig.|Loja Origem
FII|09|FII_SEQ|C|2|0|Sequencia|Sequencia
FII|10|FII_ENTDES|C|3|0|Ent.Dest.|Entidade Destino
FII|11|FII_PREFDE|C|3|0|Pref.Dest.|Prefixo Destino
FII|12|FII_NUMDES|C|9|0|Num.Dest|Numero Destino
FII|13|FII_PARCDE|C|3|0|Parc.Dest.|Parcela Destino
FII|14|FII_TIPODE|C|3|0|Tipo Dest.|Tipo Destino
FII|15|FII_CFDES|C|6|0|Cli/For Dest|Cliente/Fornecedor Dest.
FII|16|FII_LOJADE|C|2|0|Loja Dest.|Loja Destino
FII|17|FII_FILDES|C|6|0|Filial Dest.|Filial do titulo destino
FII|18|FII_ROTINA|C|10|0|Rotina|Rotina
FII|19|FII_OPERAC|C|2|0|Operacao|Operacao
--- ### FIJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIJ|01|FIJ_FILIAL|C|6|0|Filial|Filial do Sistema
FIJ|02|FIJ_CODCX|C|3|0|Caixinha|Codigo do Caixinha
FIJ|03|FIJ_DATA|D|8|0|Dt. Saldo|Data do Saldo do Caixnha
FIJ|04|FIJ_SALDO|N|16|2|Saldo Atual|Saldo do Caixinha
--- ### FIK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIK|01|FIK_FILIAL|C|6|0|Filial|Filial do Sistema
FIK|02|FIK_CODPRC|C|10|0|Cod.Processo|Codigo Processo Liberacao
FIK|03|FIK_PREFIX|C|3|0|Prefixo|Prefixo do Titulo CP
FIK|04|FIK_NUM|C|9|0|No. Titulo|Numero do Titulo
FIK|05|FIK_PARCEL|C|3|0|Parcela|Parcela do titulo
FIK|06|FIK_TIPO|C|3|0|Tipo|Tipo do Titulo
FIK|07|FIK_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
FIK|08|FIK_LOJA|C|2|0|Loja|Loja do Fornecedor
FIK|09|FIK_VALLIB|N|16|2|Vlr Liberado|Valor Liberado
FIK|10|FIK_DATLIB|D|8|0|Dt Liberacao|Data da Liberação
FIK|11|FIK_DATVEN|D|8|0|Dt Vencto|Data do Vencimento
FIK|12|FIK_STATUS|C|1|0|Sit Liberac.|Situação da Liberação
--- ### FIL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIL|01|FIL_FILIAL|C|6|0|Filial|Filial do Sistema
FIL|02|FIL_FORNEC|C|6|0|Fornecedor|Fornecedor
FIL|03|FIL_LOJA|C|2|0|Loja Ori.|Loja do Fornecedor Origin
FIL|04|FIL_BANCO|C|3|0|Banco|Banco da C. Corrente
FIL|05|FIL_AGENCI|C|5|0|Agencia|Código da Agencia
FIL|06|FIL_DVAGE|C|1|0|DV Agência|Dígito Verificador Agênc.
FIL|07|FIL_CONTA|C|10|0|Conta|Código da Conta Corrente
FIL|08|FIL_DVCTA|C|2|0|DV Conta|Dígito Verificador Conta
FIL|09|FIL_TIPO|C|1|0|Tipo C/C|Tipo da C/C
FIL|10|FIL_DETRAC|C|1|0|C. de Detrac|Conta de Detraccion
FIL|11|FIL_MOEDA|N|2|0|Moeda|Moeda
FIL|12|FIL_TIPCTA|C|1|0|Tipo Conta|Tipo de Conta Bancária
FIL|13|FIL_MOVCTO|C|1|0|Permite C/C|Permite C/C
--- ### FIM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIM|01|FIM_FILIAL|C|6|0|Filial|Filial do Sistema
FIM|02|FIM_CODISS|C|6|0|Codigo ISS|Codigo ISS
FIM|03|FIM_EST|C|2|0|Estado|Unidade Federativa
FIM|04|FIM_CODMUN|C|5|0|Cd.Municipio|Codigo do Municipio
FIM|05|FIM_MUN|C|15|0|Municipio|Nome do Municipio
FIM|06|FIM_ALQISS|N|5|2|Aliq. ISS|Aliq. ISS
FIM|07|FIM_CDISSM|C|9|0|Cod. ISS Mun|Codigo do Servico
FIM|08|FIM_DESCRI|C|50|0|Desc. Servic|Descricao do Servico
FIM|09|FIM_CODFOR|C|6|0|Fornecedor|Fornecedor
FIM|10|FIM_FORLOJ|C|2|0|Loja Forn.|Loja Fornecedor
FIM|11|FIM_CDTRIB|C|20|0|C. Trib. Mun|Cod. Trib. Municipal
--- ### FIN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIN|01|FIN_FILIAL|C|6|0|Filial|Filial do Sistema
FIN|02|FIN_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FIN|03|FIN_NUM|C|9|0|Número|Numero do Titulo
FIN|04|FIN_PARCEL|C|3|0|Parcela|Parcela
FIN|05|FIN_TIPO|C|3|0|Tipo|Tipo
FIN|06|FIN_CLIENT|C|6|0|Cliente|Cliente
FIN|07|FIN_LOJA|C|2|0|Loja|Loja
FIN|08|FIN_SEQ|C|4|0|Sequencia|Sequencia
FIN|09|FIN_DTAVP|D|8|0|Data AVP|Data AVP
FIN|10|FIN_TAXAVP|N|14|8|Taxa AVP|Taxa AVP
FIN|11|FIN_VLRAVP|N|16|2|Valor AVP|Valor AVP
FIN|12|FIN_FORMUL|C|3|0|Formula|Formula
FIN|13|FIN_CODIND|C|2|0|Cod.Indice|Cod.Indice
FIN|14|FIN_INDAVP|N|14|8|Indice AVP|Indice AVP
FIN|15|FIN_PERIOD|C|1|0|Periodic.|Periodic.
FIN|16|FIN_STATUS|C|1|0|Status|Status
FIN|17|FIN_BASE|N|16|2|Valor Base|Valor Base
--- ### FIO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIO|01|FIO_FILIAL|C|6|0|Filial|Filial
FIO|02|FIO_PROC|C|20|0|Proc AVP|Processo de Ajuste
FIO|03|FIO_DTAVP|D|8|0|Data AVP|Data AVP
FIO|04|FIO_STATUS|C|1|0|Status|Status Processo
FIO|05|FIO_VLRDE|N|16|2|Valor De|Valor De
FIO|06|FIO_VLRATE|N|16|2|Valor Ate|Valor Ate
FIO|07|FIO_VENDE|D|8|0|Vencto De|Vencto De
FIO|08|FIO_VENATE|D|8|0|Vencto Ate|Vencto Ate
FIO|09|FIO_NATDE|C|10|0|Natureza De|Natureza De
FIO|10|FIO_NATATE|C|10|0|Natureza Ate|Natureza Ate
FIO|11|FIO_PORDE|C|3|0|Portador De|Portador De
FIO|12|FIO_PORATE|C|3|0|Portador Ate|Portador Ate
FIO|13|FIO_CLIDE|C|6|0|Cliente De|Cliente De
FIO|14|FIO_LOJDE|C|2|0|Loja De|Loja De
FIO|15|FIO_CLIATE|C|6|0|Cliente Ate|Cliente Ate
FIO|16|FIO_LOJATE|C|2|0|Loja Ate|Loja Ate
FIO|17|FIO_METODO|C|1|0|Metodo|Metodo de Constituicao
FIO|18|FIO_EMSDE|D|8|0|Emissão De|Emissão De
FIO|19|FIO_EMSATE|D|8|0|Emissão Até|Emissão Até
--- ### FIP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIP|01|FIP_FILIAL|C|6|0|Filial|Filial do Sistema
FIP|02|FIP_PROC|C|20|0|Proc AVP|Processo de Ajuste
FIP|03|FIP_IDMOV|C|10|0|ID Mov|ID do movimento
FIP|04|FIP_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FIP|05|FIP_NUM|C|9|0|Número|Número do Título
FIP|06|FIP_PARCEL|C|3|0|Parcela|Parcela do Título
FIP|07|FIP_TIPO|C|3|0|Tipo|Tipo Título
FIP|08|FIP_CLIENT|C|6|0|Cliente|Cliente
FIP|09|FIP_LOJA|C|2|0|Loja|Loja
FIP|10|FIP_TIPAVP|C|1|0|Tipo AVP|Tipo do Ajuste
FIP|11|FIP_DTAVP|D|8|0|Data AVP|Data AVP
FIP|12|FIP_VLRAVP|N|16|2|Valor AVP|Valor do Ajuste
FIP|13|FIP_TAXAVP|N|14|8|Taxa AVP|Taxa do ajuste
FIP|14|FIP_FORMUL|C|3|0|Formula|Fórmula utilizada
FIP|15|FIP_CODIND|C|2|0|Codigo Indic|Codigo do Indice
FIP|16|FIP_VLRIND|N|14|8|Valor Indice|Valor Indice
FIP|17|FIP_CRITIC|M|10|0|Crit Mov|Crit Mov
FIP|18|FIP_PERIOD|C|1|0|Periodic.|Periodic.
FIP|19|FIP_STATUS|C|1|0|Status|Status Movimento
FIP|20|FIP_LA|C|1|0|Ident. Lanc.|Identificador Laçamento
FIP|21|FIP_SEQ|C|4|0|Sequencia|Sequencia do AVP
FIP|22|FIP_LE|C|1|0|Id Lanc Est|Id Lanc Estorno
FIP|23|FIP_SEQBX|C|2|0|Sequencia Bx|Sequencia da Baixa
FIP|24|FIP_MSUIDT|C|36|0|Campo UUID|
--- ### FIQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIQ|01|FIQ_FILIAL|C|6|0|Filial|Filial do Sistema
FIQ|02|FIQ_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FIQ|03|FIQ_NUM|C|9|0|Número|Número do Título
FIQ|04|FIQ_PARCEL|C|3|0|Parcela|Parcela do Título
FIQ|05|FIQ_TIPO|C|3|0|Tipo|Tipo Título
FIQ|06|FIQ_LOJA|C|2|0|Loja|Loja
FIQ|07|FIQ_FORNEC|C|6|0|Fornecedor|Fornecedor
FIQ|08|FIQ_SEQ|C|4|0|Sequencia|Sequencia
FIQ|09|FIQ_DTAVP|D|8|0|Data AVP|Data do Ajuste
FIQ|10|FIQ_TAXAVP|N|14|8|Taxa AVP|Taxa do Ajuste
FIQ|11|FIQ_VLRAVP|N|16|2|Valor AVP|Valor do Ajuste
FIQ|12|FIQ_FORMUL|C|3|0|Formula|Fórmula utilizada
FIQ|13|FIQ_CODIND|C|2|0|Codigo Indic|Codigo do Indice
FIQ|14|FIQ_VLRIND|N|14|8|Valor Indice|Valor Indice
FIQ|15|FIQ_PERIOD|C|1|0|Period|Periodicidade Ajuste
FIQ|16|FIQ_STATUS|C|1|0|Status|Status Processo
FIQ|17|FIQ_BASE|N|16|2|Valor Base|Valor Base
--- ### FIR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIR|01|FIR_FILIAL|C|6|0|Filial|Filial do Sistema
FIR|02|FIR_PROC|C|20|0|Proc AVP|Processo de Ajuste
FIR|03|FIR_DTAVP|D|8|0|Data AVP|Data AVP
FIR|04|FIR_STATUS|C|1|0|Status|Status Processo
FIR|05|FIR_VLRDE|N|16|2|Valor De|Valor De
FIR|06|FIR_VLRATE|N|16|2|Valor Ate|Valor Ate
FIR|07|FIR_VENDE|D|8|0|Vencto De|Vencto De
FIR|08|FIR_VENATE|D|8|0|Vencto Ate|Vencto Ate
FIR|09|FIR_NATDE|C|10|0|Natureza De|Natureza De
FIR|10|FIR_NATATE|C|10|0|Natureza Ate|Natureza Ate
FIR|11|FIR_PORDE|C|3|0|Portador De|Portador De
FIR|12|FIR_PORATE|C|3|0|Portador Ate|Portador Ate
FIR|13|FIR_FORDE|C|6|0|Fornec De|Fornecedor De
FIR|14|FIR_FORATE|C|6|0|Fornec Ate|Fornecedor Ate
FIR|15|FIR_LOJDE|C|2|0|Loja De|Loja De
FIR|16|FIR_LOJATE|C|2|0|Loja Ate|Loja Ate
FIR|17|FIR_METODO|C|1|0|Metodo|Metodo de Constituicao
FIR|18|FIR_EMSDE|D|8|0|Emissão De|Emissão De
FIR|19|FIR_EMSATE|D|8|0|Emissão Até|Emissão Até
--- ### FIS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIS|01|FIS_FILIAL|C|6|0|Filial|Filial do Sistema
FIS|02|FIS_PROC|C|20|0|Processo|Processo de Ajuste
FIS|03|FIS_IDMOV|C|10|0|ID Mov|ID do movimento
FIS|04|FIS_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FIS|05|FIS_NUM|C|9|0|Número|Número do Título
FIS|06|FIS_TIPO|C|3|0|Tipo|Tipo Título
FIS|07|FIS_PARCEL|C|3|0|Parcela|Parcela do Título
FIS|08|FIS_FORNEC|C|6|0|Fornecedor|Fornecedor
FIS|09|FIS_LOJA|C|2|0|Loja|Loja
FIS|10|FIS_TIPAVP|C|1|0|Tipo AVP|Tipo do Ajuste
FIS|11|FIS_DTAVP|D|8|0|Data AVP|Data do ajuste
FIS|12|FIS_VLRAVP|N|16|2|Valor AVP|Valor do Ajuste
FIS|13|FIS_TAXAVP|N|14|8|Taxa AVP|Taxa do Ajuste
FIS|14|FIS_FORMUL|C|3|0|Fórmula|Fórmula utilizada
FIS|15|FIS_CODIND|C|2|0|Codigo Indic|Codigo Indice
FIS|16|FIS_VLRIND|N|14|8|Valor Indice|Valor Indice
FIS|17|FIS_CRITIC|M|10|0|Crit Mov|Crit Mov
FIS|18|FIS_PERIOD|C|1|0|Period.|Periodicidade Ajuste
FIS|19|FIS_STATUS|C|1|0|Status|Status Movimento
FIS|20|FIS_LA|C|1|0|Ident. Lanc.|Identificador Laçamento
FIS|21|FIS_SEQ|C|4|0|Sequencia|Sequencia do AVP
FIS|22|FIS_LE|C|1|0|Id Lanc Est|Id Lanc Estorno
FIS|23|FIS_SEQBX|C|2|0|Sequencia Bx|Sequencia da Baixa
FIS|24|FIS_MSUIDT|C|36|0|Campo UUID|
--- ### FIT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIT|01|FIT_FILIAL|C|6|0|Filial|Filial do Sistema
FIT|02|FIT_CODIND|C|2|0|Indice|Codigo Indice
FIT|03|FIT_DESC|C|10|0|Descricao|Descricao
FIT|04|FIT_BLOQ|C|1|0|Bloqueada|Indice Bloqueado?
FIT|05|FIT_PERIOD|C|1|0|Periodo|Periodicidade Indice
FIT|06|FIT_BACEN|C|6|0|Série Bacen|Código da série do Bacen
FIT|07|FIT_DBACEN|C|40|0|Desc. Série|Descrição da Série
--- ### FIU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIU|01|FIU_FILIAL|C|6|0|Filial|Filial do Sistema
FIU|02|FIU_DATA|D|8|0|Data|Data
FIU|03|FIU_CODIND|C|2|0|Indice|Codigo Indice
FIU|04|FIU_INDICE|N|14|8|Taxa|Taxa do Indice
FIU|05|FIU_BLOQ|C|1|0|Bloqueada|Indice Bloqueado?
FIU|06|FIU_DESCIN|C|10|0|Desc. Índice|Descrição do Índice
--- ### FIV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIV|01|FIV_FILIAL|C|6|0|Filial|Filial do Sistema
FIV|02|FIV_NATUR|C|10|0|Natureza|Codigo da natureza
FIV|03|FIV_MOEDA|C|2|0|Moeda|Codigo da moeda
FIV|04|FIV_TPSALD|C|1|0|Tipo Saldo|Tipo do saldo
FIV|05|FIV_CARTEI|C|1|0|Carteira|Codigo da Carteira
FIV|06|FIV_DATA|D|8|0|Data saldo|Data do saldo
FIV|07|FIV_VALOR|N|16|2|Valor saldo|Valor do saldo
FIV|08|FIV_ABATI|N|16|2|Abatimento|Valor do Abatimento
FIV|09|FIV_PAI|C|10|0|Natureza Pai|Codigo da Natureza Pai
--- ### FIW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIW|01|FIW_FILIAL|C|6|0|Filial|Filial do Sistema
FIW|02|FIW_NATUR|C|10|0|Natureza|Codigo da natureza
FIW|03|FIW_MOEDA|C|2|0|Moeda|Codigo da moeda
FIW|04|FIW_TPSALD|C|1|0|Tipo Saldo|Tipo do saldo
FIW|05|FIW_CARTEI|C|1|0|Carteira|Codigo da Carteira
FIW|06|FIW_DATA|D|8|0|Data saldo|Data do saldo
FIW|07|FIW_VALOR|N|16|2|Valor|Valor do saldo
FIW|08|FIW_ABATI|N|16|2|Abatimentos|Valor dos Abatimentos
FIW|09|FIW_PAI|C|10|0|Natureza Pai|Codigo da Natureza Pai
--- ### FIX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIX|01|FIX_FILIAL|C|6|0|Filial|Filial do Sistema
FIX|02|FIX_CODIGO|C|10|0|Codigo|Codigo da persistencia
FIX|03|FIX_DATA|D|8|0|Data|Data de gravacao
FIX|04|FIX_HORA|C|4|0|Hora|Hora de gravacao
FIX|05|FIX_CODUSR|C|6|0|Cod. Usuario|Codigo do usuario
FIX|06|FIX_NOMUSR|C|30|0|Nome Usuario|Nome do usuario
FIX|07|FIX_CODPAR|C|6|0|Cod. Param.|Codigo Parametros
FIX|08|FIX_PARAM|M|80|0|Parametros|Parametros
FIX|09|FIX_OBS1|M|10|0|Notas Explic|Notas Explicativas
--- ### FIY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FIY|01|FIY_FILIAL|C|6|0|Filial|Filial do Sistema
FIY|02|FIY_CODIGO|C|10|0|Codigo|Codigo da persitencia
FIY|03|FIY_NATUR|C|10|0|Natureza|Codigo da natureza
FIY|04|FIY_MOEDA|C|2|0|Moeda|Codigo da moeda
FIY|05|FIY_TPSALD|C|1|0|Tipo Saldo|Tipo do saldo
FIY|06|FIY_CARTEI|C|1|0|Carteira|Codigo da Carteira
FIY|07|FIY_DATA|D|8|0|Data saldo|Data do saldo
FIY|08|FIY_VALOR|N|16|2|Valor|Valor do saldo
--- ### FJ0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ0|01|FJ0_FILIAL|C|6|0|Filial|Filial do Sistema
FJ0|02|FJ0_CODIGO|C|12|0|Cód. do Mov|Código do Movimento
FJ0|03|FJ0_CLASSI|C|1|0|Classif. Mov|Classificação Movimento
FJ0|04|FJ0_DATA|D|8|0|Data Venc.|Data do Vencimento
FJ0|05|FJ0_NATURE|C|10|0|Natureza|Código da Natureza
FJ0|06|FJ0_CCUSTO|C|9|0|C. de Custo|Centro de Custo
FJ0|07|FJ0_VALOR|N|16|2|Valor Mov.|Valor do Movimento
--- ### FJ1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ1|01|FJ1_FILIAL|C|6|0|Filial|Filial do Sistema
FJ1|02|FJ1_CODIGO|C|3|0|Cod Visao|Codigo da Visao Gerencial
FJ1|03|FJ1_DESCRI|C|30|0|Desc Ent Ger|Descricao Entid Gerencial
FJ1|04|FJ1_OBS|C|100|0|Observação|Observação da Visal Geren
--- ### FJ2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ2|01|FJ2_FILIAL|C|6|0|Filial|Filial do Sistema
FJ2|02|FJ2_CODIGO|C|3|0|Cod Visao|Codigo da Visao Gerencial
FJ2|03|FJ2_CONTAG|C|20|0|Entid Gerenc|Entidade Gerencial
FJ2|04|FJ2_ORDEM|C|10|0|Ordem|Ordem de Exibicao
FJ2|05|FJ2_CLASSE|C|1|0|Classe|Classe de Entid Gerencial
FJ2|06|FJ2_CTASUP|C|20|0|Entid Super|Entidade Superior
FJ2|07|FJ2_DESCCG|C|40|0|Desc Ent Ger|Descricao Entid Gerencial
FJ2|08|FJ2_NORMAL|C|1|0|Cond Normal|Condicao Normal da Entid
FJ2|09|FJ2_COLUNA|C|1|0|Coluna|Coluna
FJ2|10|FJ2_NEGRIT|L|1|0|Negrito|Negrito
FJ2|11|FJ2_TOTAL|L|1|0|Total Geral|Total Geral
FJ2|12|FJ2_SEPARA|L|1|0|Sem Valor|Linha Sem Valor
FJ2|13|FJ2_TRACO|L|1|0|Traco|Traco
FJ2|14|FJ2_IDENT|C|1|0|Identificad.|Identificador
FJ2|15|FJ2_TOTVIS|C|1|0|Resul.Visao?|Resultado da Visao?
FJ2|16|FJ2_VISENT|C|1|0|Vis. Entid.?|Visualiza Entidade?
FJ2|17|FJ2_SLDENT|C|1|0|Sld. Entid.?|Saldo Entidade?
FJ2|18|FJ2_FATSLD|C|1|0|Fator Entid?|Fator Entidade?
--- ### FJ3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ3|01|FJ3_FILIAL|C|6|0|Filial|Filial do Sistema
FJ3|02|FJ3_CODPLA|C|3|0|Cod Visao|Codigo da Visao Gerencial
FJ3|03|FJ3_ORDEM|C|10|0|Ordem|Ordem de Exibicao
FJ3|04|FJ3_CONTAG|C|20|0|Entid Gerenc|Entidade Gerencial
FJ3|05|FJ3_CTASUP|C|20|0|Entid Super|Entidade Superior
FJ3|06|FJ3_DESCCG|C|40|0|Desc Ent Ger|Descricao Entid Gerencial
FJ3|07|FJ3_DETHCG|C|200|0|Cont. Descr.|Continuacao Descr Ent Ger
FJ3|08|FJ3_NORMAL|C|1|0|Cond Normal|Condicao Normal da Entid
FJ3|09|FJ3_COLUNA|N|1|0|Coluna|Coluna
FJ3|10|FJ3_CLASSE|C|1|0|Classe|Classe da Entid Gerencial
FJ3|11|FJ3_IDENT|C|1|0|Identific.|Identificador
FJ3|12|FJ3_NOME|C|40|0|Nome Visao|Nome da Visao Gerencial
FJ3|13|FJ3_LINHA|C|3|0|Linha|Linha da Composicao Vlrs
FJ3|14|FJ3_SEDINI|C|20|0|Naturez Ini|Natureza Financeira Inici
FJ3|15|FJ3_SEDFIM|C|20|0|Natureza Fim|Natureza Financeira Final
FJ3|16|FJ3_FORMUL|C|40|0|Formula|Formula a ser digitada
FJ3|17|FJ3_TOTVIS|C|1|0|Resul.Visao?|Resultado da Visao?
FJ3|18|FJ3_VISENT|C|1|0|Vis. Entid.?|Visualiza Entidade?
FJ3|19|FJ3_SLDENT|C|1|0|Sld. Entid.?|Saldo Entidade?
FJ3|20|FJ3_FATSLD|C|1|0|Fator Entid?|Fator Entidade?
FJ3|21|FJ3_IDENTI|C|1|0|Identific.|Identificador
--- ### FJ4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ4|01|FJ4_FILIAL|C|6|0|Filial|Filial do sistema
FJ4|02|FJ4_NUM|C|10|0|Numero Int.|Numero interno
FJ4|03|FJ4_SEQ|C|3|0|Seq Rateio|Sequência Rateio
FJ4|04|FJ4_SEQJUR|C|8|0|Seq.Juridico|Sequencial do Juridico
FJ4|05|FJ4_VALOR|N|16|2|Valor|Valor rateado
FJ4|06|FJ4_PERC|N|11|7|Perc. Distr.|Perc. Distribuido Despesa
FJ4|07|FJ4_FATJUR|C|1|0|Desp.Cliente|Despesa de Cliente
FJ4|08|FJ4_PROFIS|C|5|0|Prof.Favorec|Profissional Favorecido
FJ4|09|FJ4_TIPDSP|C|4|0|Tipo Despesa|Tipo de Despesa
FJ4|10|FJ4_CLIENT|C|6|0|Cliente|Código do Cliente
FJ4|11|FJ4_LOJA|C|2|0|Loja|Loja do cliente
FJ4|12|FJ4_CASO|C|6|0|Num Caso|Num Caso
FJ4|13|FJ4_ESCRIT|C|5|0|Escritorio|Escritorio
FJ4|14|FJ4_GRPJUR|C|5|0|Grp.Juridico|Grupo Juridico
FJ4|15|FJ4_DESCRI|M|10|0|Descrição|Descrição da Despesa
--- ### FJ5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ5|01|FJ5_FILIAL|C|6|0|Filial|Filial do Sistema
FJ5|02|FJ5_CODCAP|C|8|0|Codigo|Código da Captação
FJ5|03|FJ5_DESC|C|40|0|Descrição|Descrição da Captação
--- ### FJ6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ6|01|FJ6_FILIAL|C|6|0|Filial|Filial do Sistema
FJ6|02|FJ6_CODCAP|C|8|0|Codigo Cap|Codigo da Captação
FJ6|03|FJ6_ITPAR|C|5|0|Item Parcela|Item da Parcela
FJ6|04|FJ6_VALOR|N|16|2|Valor|Valor da Parcela
--- ### FJ7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ7|01|FJ7_FILIAL|C|6|0|Filial|Filial do Sistema
FJ7|02|FJ7_CODCAP|C|8|0|Codigo Cap|Codigo da Capitação
FJ7|03|FJ7_ITCTRA|C|5|0|Item C Trans|Item Custo Transação
FJ7|04|FJ7_DESC|C|40|0|Descrição|Descrição do Custo Trans
--- ### FJ8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ8|01|FJ8_FILIAL|C|6|0|Filial|Filial do Sistema
FJ8|02|FJ8_CODCAP|C|8|0|Codigo Cap|Codigo da Captação
FJ8|03|FJ8_ITPAR|C|5|0|Item Parcela|Item da Parcela
FJ8|04|FJ8_ITPAGA|C|5|0|Item Pag|Item Pagamento
FJ8|05|FJ8_VALOR|N|16|2|Valor|Valor Pagamento
--- ### FJ9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJ9|01|FJ9_FILIAL|C|6|0|FIlial|Filial do Sistema
FJ9|02|FJ9_CODCAP|C|8|0|Codigo Cap|Codigo da Captação
FJ9|03|FJ9_ITREC|C|5|0|Item Recurso|Item do Recurso
FJ9|04|FJ9_DESC|C|40|0|Descricao|Descrição do Recurso
--- ### FJA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJA|01|FJA_FILIAL|C|6|0|Filial|Filial do sstema
FJA|02|FJA_PREFIX|C|3|0|Prefixo|Prefixo do Tíitulo
FJA|03|FJA_NUMTIT|C|9|0|Número|Número do Título
FJA|04|FJA_PARCEL|C|3|0|Parcela|Parcela do Título
FJA|05|FJA_TIPO|C|3|0|Tipo Título|Típo do Título
FJA|06|FJA_SOLFUN|C|10|0|Cod da Solic|Codigo da Solic Fundo
FJA|07|FJA_VALOR|N|16|2|Valor|Valor para pagamento
FJA|08|FJA_DATA|D|8|0|Dt Solic|Data da Solicitação
FJA|09|FJA_FORNEC|C|6|0|Fornecedor|Código do fornecedor
FJA|10|FJA_LOJA|C|2|0|Loja|Loja
FJA|11|FJA_OBSERV|C|50|0|Observação|Observação
FJA|12|FJA_CODAPR|C|6|0|Cod Aprov|Código do Aprovador
FJA|13|FJA_RESPON|C|6|0|Responsável|Responsável da Operação
FJA|14|FJA_DTOPER|D|8|0|Dt Operação|Data Aprov / Reprov / Can
FJA|15|FJA_OBOPER|C|50|0|Obs Aprov|Obs Aprovação/Reprov/Canc
FJA|16|FJA_ORDPAG|C|12|0|Ordem Pago|Nr. da ordem de pago
FJA|17|FJA_ESTADO|C|1|0|Estado|Situação da solicitação
FJA|18|FJA_DATAPR|D|8|0|Dt.PrevPagto|Data Prevista Pagto
FJA|19|FJA_NATURE|C|10|0|Natureza|Natureza Financeira
FJA|20|FJA_DESTIN|C|25|0|Destinatário|Destinatário
FJA|21|FJA_CUIT|C|14|0|CNPJ/CPF|CNPJ/CPF
FJA|22|FJA_MOEDA|C|2|0|Moeda|Moeda da Solicitação
--- ### FJH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJH|01|FJH_FILIAL|C|6|0|Filial|Filial do Sistema
FJH|02|FJH_CODCAP|C|8|0|Codigo Cap|Codigo da Captacao
FJH|03|FJH_ITEM|C|8|0|Item|Item do Movimento
FJH|04|FJH_DATA|D|8|0|Data|Data do Movimento
FJH|05|FJH_OCORR|C|3|0|Ocorrencia|Codigo da ocorrencia
FJH|06|FJH_VALOR|N|16|2|Valor|Valor Movimento
--- ### FJI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJI|01|FJI_FILIAL|C|6|0|Filial|Filial do Sistema
FJI|02|FJI_CODTIP|C|3|0|Codigo|Codigo Tipo Captacao
FJI|03|FJI_DESC|C|40|0|Descricao|Descricao
--- ### FJJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJJ|01|FJJ_FILIAL|C|6|0|Filial|Filial do Sistema
FJJ|02|FJJ_CODCAP|C|8|0|Codigo Cap|Codigo Captacao
FJJ|03|FJJ_ITTAX|C|5|0|Item|Item da Taxa
FJJ|04|FJJ_TAXA|N|11|8|Taxa TIR|Taxa TIR da Captação
--- ### FJM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJM|01|FJM_FILIAL|C|6|0|Filial|Filial do Sistema
FJM|02|FJM_PREOP|C|6|0|Pre-ordem|Numero da pre-ordem
FJM|03|FJM_MOEDA|C|2|0|Moeda|Moeda
FJM|04|FJM_PERC|N|6|2|Percentual %|Percentual %
FJM|05|FJM_VLCONV|N|16|4|Convertido|Valor Convertido
FJM|06|FJM_TAXA|N|16|4|Taxa|Taxa da Moeda
FJM|07|FJM_VLMDOP|N|16|4|Vl Moeda OP|Vl. Moeda Pre-Ordem Pago
--- ### FJP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJP|01|FJP_FILIAL|C|6|0|Filial|Filial do Sistema
FJP|02|FJP_IDPROC|C|36|0|Id. Processo|Identif Proc
FJP|03|FJP_CONTR|C|50|0|Contr Banc|Contr Bancario
FJP|04|FJP_DTIMP|D|8|0|Dt IMP|Data IMP
FJP|05|FJP_DTPARC|D|8|0|Dt PARC|Data Parcela
FJP|06|FJP_VALOR|N|16|2|Vlr Parcela|Valor da Parcela
FJP|07|FJP_SITUAC|C|1|0|St. Registro|Status do registro
FJP|08|FJP_HISTOR|C|40|0|Histórico|Histórico do registro
FJP|09|FJP_TITULO|C|100|0|Tit Baix|Titulo baixado
FJP|10|FJP_IDARQU|C|70|0|Id Arquivo|Identificacao do arquivo
--- ### FJQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJQ|01|FJQ_CODRET|C|4|0|Cd.Retenção|Cd.Retenção
FJQ|02|FJQ_FILIAL|C|6|0|FILIAL|FILIAL
FJQ|03|FJQ_PERIOD|C|1|0|Período|Período
--- ### FJR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJR|01|FJR_FILIAL|C|6|0|Filial|Filial do Sistema
FJR|02|FJR_ORDPAG|C|6|0|Ordem Pagto.|Ordem de Pagamento
FJR|03|FJR_EMISSA|D|8|0|Dt. Emissão|Data de Emissão
FJR|04|FJR_NATURE|C|10|0|Natureza|Natureza
FJR|05|FJR_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
FJR|06|FJR_LOJA|C|2|0|Loja|Loja do Fornecedor
FJR|07|FJR_TOTPAG|N|16|2|Total Pago|Valor total pago
FJR|08|FJR_TOTRET|N|16|2|Tot. Ret.|Valor total das retenções
FJR|09|FJR_TOTFAT|N|16|2|Tot. Faturas|Valor total das faturas
FJR|10|FJR_TOTDES|N|16|2|Total Desc.|Total dos desc. e comp.
FJR|11|FJR_TOTTER|N|16|2|Total Terc.|Total dos títulos de terc
FJR|12|FJR_CANCEL|L|1|0|OP Cancelada|Ordem de Pago Cancelada
FJR|13|FJR_DOCREC|C|12|0|Num.Doc.Lib.|Num. do Doc. de Liberação
--- ### FJS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJS|01|FJS_FILIAL|C|6|0|Filial|Filial do SIstema
FJS|02|FJS_TIPO|C|3|0|Tipo|Tipo
FJS|03|FJS_CARTE|C|1|0|Carteira|Carteira
FJS|04|FJS_DESC|C|20|0|Descricao|Descricao
FJS|05|FJS_RCOP|C|1|0|Gera|Gera quando receb./ent. ?
FJS|06|FJS_TRANS|C|1|0|Doc.Transito|Documento em transito
FJS|07|FJS_TERCEI|C|1|0|Doc.Terceiro|Documento de terceiros
FJS|08|FJS_BLOQ|C|1|0|Doc.Bloquead|Documento bloqueado
FJS|09|FJS_TIPOIN|C|2|0|Tipo Interno|Tipo de Movimento Interno
--- ### FJU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJU|01|FJU_FILIAL|C|6|0|Filial|Filial do Sistema
FJU|02|FJU_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FJU|03|FJU_NUM|C|9|0|Numero|Numero do titulo
FJU|04|FJU_PARCEL|C|3|0|Parcela|Parcela do Titulo
FJU|05|FJU_CLIFOR|C|6|0|CliFor|Cliente/Fornecedor do tit
FJU|06|FJU_LOJA|C|2|0|LOJA|Loja do CLI/FOR
FJU|07|FJU_CART|C|2|0|Carteira|Carteira do Titulo
FJU|08|FJU_EMIS|D|8|0|Emissao|Data de Emissao do titulo
FJU|09|FJU_VALOR|N|16|2|Valor|Valor do Titulo
FJU|10|FJU_DTEXCL|D|8|0|Exclusao|Data de exclusao do titul
FJU|11|FJU_TIPO|C|3|0|Tipo|Tipo do Titulo
FJU|12|FJU_VENREA|D|8|0|Vencto.Real| Vencimento real do Titul
FJU|13|FJU_LA|C|1|0|Ident. Lanc.|Identificador de LA
FJU|14|FJU_VLCRUZ|N|16|2|Vlr R$|Valor na moeda nacional
FJU|15|FJU_EMIS1|D|8|0|DT Contab.|Data de Contabilizacao
FJU|16|FJU_MOEDA|N|2|0|Moeda|Codigo da Moeda
FJU|17|FJU_HIST|C|25|0|Historico|Historico do Titulo
FJU|18|FJU_TITPAI|C|50|0|Tit. Pai|Titulo Pai dos impostos
FJU|19|FJU_RECORI|N|10|0|Rec.Orig|Recno Origem
FJU|20|FJU_FILPAI|C|6|0|Fil. Tit Pai|Filial do titulo Pai
FJU|21|FJU_PREPAI|C|3|0|Pref. Tit Pa|Prefixo do titulo Pai
FJU|22|FJU_NUMPAI|C|9|0|Num. Tit Pai|Numero do titulo Pai
FJU|23|FJU_PARPAI|C|3|0|Par.Tit Pai|Parcela do titulo Pai
FJU|24|FJU_TIPPAI|C|3|0|Tipo Tit Pai|Tipo do titulo Pai
FJU|25|FJU_FORPAI|C|6|0|Cli/For Pai|Codigo Cli/For Tit. Pai
FJU|26|FJU_LOJPAI|C|2|0|Loja Tit Pai|Loja do Cli/For do Tit. P
FJU|27|FJU_RECPAI|N|10|0|Rec.Tit Pai|Recno do titulo Pai
FJU|28|FJU_DOCTEF|C|100|0|Num. NSU|Numero NSU-SITEF
--- ### FJV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJV|01|FJV_FILIAL|C|6|0|Filial|Filial do Sistema
FJV|02|FJV_CODIGO|C|12|0|Codigo|Codigo de identificação
FJV|03|FJV_NATUR|C|10|0|Natureza|Codigo da Natureza
FJV|04|FJV_MOEDA|C|2|0|Moeda|Codigo da Moeda
FJV|05|FJV_TPSALD|C|1|0|Tipo Saldo|Tipo do Saldo
FJV|06|FJV_CARTEI|C|1|0|Carteira|Codigo da Carteira
FJV|07|FJV_DATA|D|8|0|Data Saldo|Data do Saldo
FJV|08|FJV_VALOR|N|16|2|Valor Saldo|Valor do Saldo
FJV|09|FJV_ALIAS|C|3|0|Alias|Alias de Origem
FJV|10|FJV_RECNO|N|15|0|RECNO|RECNO
FJV|11|FJV_TPMOV|C|1|0|Tipo Movim|Tipo da Movimentacao
FJV|12|FJV_ORIGEM|C|20|0|Origem|Origem
FJV|13|FJV_CLORIG|C|10|0|Origem Movim|Origem do Movimento
--- ### FJW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJW|01|FJW_FILIAL|C|6|0|Filial|Filial do sistema
FJW|02|FJW_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
FJW|03|FJW_LOJA|C|2|0|Loja|Loja do Fornecedor
FJW|04|FJW_NOME|C|80|0|Nome|Nome do Fornecedor
--- ### FJX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJX|01|FJX_FILIAL|C|6|0|Filial|Filial do Sistema
FJX|02|FJX_PROC|C|6|0|Código|Código do Processamento
FJX|03|FJX_DTPROC|D|8|0|Data do Proc|Data de Processamento
FJX|04|FJX_DTREF|D|8|0|Data da Ref|Data de Referência
FJX|05|FJX_PARAM|M|10|0|Parametros|Param do processamento
FJX|06|FJX_TIPO|C|1|0|Tipo|Tipo de processamento
FJX|07|FJX_STATUS|C|1|0|Status|Status do processamento
FJX|08|FJX_DTEFET|D|8|0|Data Efetiva|Data de Efetivação
FJX|09|FJX_VLRPRO|N|16|2|Valor Total|Valor Total do Processo
--- ### FJY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJY|01|FJY_FILIAL|C|6|0|Filial|Filial do Sistema
FJY|02|FJY_OK|L|1|0|Check Seleçã|Campo Check para Seleção
FJY|03|FJY_SITPDD|C|1|0|Situação|Situação de Cobrança
FJY|04|FJY_PROC|C|6|0|Código|Codigo do processamento
FJY|05|FJY_ITEM|C|4|0|Item Cliente|Item do processamento
FJY|06|FJY_FILCLI|C|6|0|Filial|Filial do Cliente
FJY|07|FJY_CLIENT|C|6|0|Cliente|Código do cliente
FJY|08|FJY_LOJA|C|2|0|Loja|Loja do Cliente
FJY|09|FJY_NOME|C|80|0|Nome|Nome do Cliente
FJY|10|FJY_QTDMAX|N|15|0|Qtd dias max|Qtd maxima dias de atraso
FJY|11|FJY_VLRPRO|N|16|2|Valor Total|Total vlr titulos provi
--- ### FJZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FJZ|01|FJZ_FILIAL|C|6|0|Filial|Filial do Sistema
FJZ|02|FJZ_OK|L|1|0|Check Seleçã|Campo Check para Seleção
FJZ|03|FJZ_SITPDD|C|1|0|Situação PDD|Situação PDD
FJZ|04|FJZ_PROC|C|6|0|Código|Código do processamento
FJZ|05|FJZ_ITCLI|C|4|0|Item Cliente|Item do Cliente
FJZ|06|FJZ_ITEM|C|4|0|Item Titulo|Item do Titulo
FJZ|07|FJZ_FILTIT|C|6|0|Filial|Filial do título
FJZ|08|FJZ_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FJZ|09|FJZ_NUM|C|9|0|Numero|Numero do Titulo
FJZ|10|FJZ_PARCEL|C|3|0|Parcela|Parcela do Título
FJZ|11|FJZ_TIPO|C|3|0|Tipo|Tipo do titulo
FJZ|12|FJZ_VALOR|N|16|2|Vlr titulo|Valor do título
FJZ|13|FJZ_SALDO|N|16|2|Saldo|Sld em aberto do titulo
FJZ|14|FJZ_EMISS|D|8|0|Emissao|Data de emissão do titulo
FJZ|15|FJZ_VENCTO|D|8|0|Vencimento|Data de vcto do titulo
FJZ|16|FJZ_QTDATR|N|15|0|Atraso|Dias de Atraso
FJZ|17|FJZ_SITUAC|C|1|0|Sit Orig Tit|Situação Orig. do Titulo
FJZ|18|FJZ_VENCRE|D|8|0|Venc Real|Vencimento Real
FJZ|19|FJZ_QTDARE|N|15|0|Atraso Real|Dias de Atraso Real
FJZ|20|FJZ_VLRBX|N|16|2|Valor Baixa|Valor da baixa
FJZ|21|FJZ_MOTBX|C|3|0|Motivo Baixa|Motivo Baixa
FJZ|22|FJZ_STATUS|C|1|0|Status|Status do Titulo
FJZ|23|FJZ_REVSTA|C|1|0|Status Rev|Status da Revisão
FJZ|24|FJZ_SLDBRT|N|16|2|Saldo Bruto|Saldo Bruto do Titulo
FJZ|25|FJZ_DTBAIX|D|8|0|Data baixa|Data da Baixa
FJZ|26|FJZ_LA|C|1|0|Ident. Lanc.|Identificador de LA
FJZ|27|FJZ_SITPAI|C|1|0|Sit Tit Pai|Situação do Título Pai
FJZ|28|FJZ_ULTSEQ|C|2|0|Ult. Seq.|Ultima Sequencia
--- ### FK0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK0|01|FK0_FILIAL|C|6|0|Filial|Filial do Sistema
FK0|02|FK0_IDDOC|C|32|0|ID Doc|ID do Documento
FK0|03|FK0_IDFK4|C|10|0|Id. Ret.|Identificação da Retenção
FK0|04|FK0_IDPAI|C|32|0|ID Tit. Pai|ID Titulo Pai do Imposto
FK0|05|FK0_CODFKM|C|6|0|Tipo Imposto|Código do Tipo de Imposto
FK0|06|FK0_TABORI|C|3|0|Tab. Origem|Tabela Origem do Imposto
FK0|07|FK0_PRCAGL|C|9|0|Proc. Aglut.|Processo Aglutinação
FK0|08|FK0_IDORIG|C|32|0|Id. Origem|Id. Origem
FK0|09|FK0_FILORI|C|6|0|Filial Orig.|Filial de Origem
--- ### FK1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK1|01|FK1_FILIAL|C|6|0|Filial|Filial do sistema
FK1|02|FK1_IDFK1|C|32|0|Id. Baixas|Identif. Baixas
FK1|03|FK1_DATA|D|8|0|Dt. Baixa|Data Baixa
FK1|04|FK1_VALOR|N|16|2|Valor Baixa|Valor da Baixa
FK1|05|FK1_MOEDA|C|2|0|Moeda|Moeda
FK1|06|FK1_NATURE|C|10|0|Natureza|Natureza
FK1|07|FK1_VENCTO|D|8|0|Vencimento|Vencimento
FK1|08|FK1_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK1|09|FK1_TPDOC|C|2|0|Tipo do Doc|Tipo da movimentacao
FK1|10|FK1_HISTOR|C|40|0|Histórico|Histórico do movimento
FK1|11|FK1_VLMOE2|N|16|2|Vlr.Moeda 2|Valor na Moeda 2
FK1|12|FK1_LOTE|C|4|0|Lote|Lote da Baixa
FK1|13|FK1_MOTBX|C|3|0|Motivo Baixa|Motivo da baixa do título
FK1|14|FK1_ORDREC|C|6|0|Rec/Ordem|Numero do Recibo/Ordem
FK1|15|FK1_FILORI|C|6|0|Filial Orig.|Filial Origem
FK1|16|FK1_ARCNAB|C|12|0|Arquivo CNAB|Arquivo CNAB
FK1|17|FK1_CNABOC|C|2|0|Ocorr. CNAB|Ocorrencia Baixa CNAB
FK1|18|FK1_TXMOED|N|11|4|Tx Moeda Tit|Taxa contratada moeda tit
FK1|19|FK1_SITCOB|C|1|0|Sit.Cobranca|Situacao de Cobranca
FK1|20|FK1_SERREC|C|3|0|Série Recibo|Série do Recibo
FK1|21|FK1_MULNAT|C|1|0|Mult.Nat.|Rat. Mult Natureza
FK1|22|FK1_AUTBCO|C|25|0|Aut.Bancaria|Autenticacao Bancaria
FK1|23|FK1_CCUSTO|C|9|0|C. de Custo|Centro de Custo
FK1|24|FK1_ORIGEM|C|8|0|Origem|Origem Movimento Baixas
FK1|25|FK1_SEQ|C|2|0|Sequencia|Sequencia da Baixa
FK1|26|FK1_DIACTB|C|2|0|Cod. Diario|Cod. Diario Contabilidade
FK1|27|FK1_NODIA|C|10|0|Seq. Diario|Seq. Diario Contabilidade
FK1|28|FK1_LA|C|1|0|Ident.Lanc.|Identifica Lançamento
FK1|29|FK1_IDDOC|C|32|0|Id. Doc|Identif Documento
FK1|30|FK1_IDCOMP|C|32|0|ID Compensac|ID Compensação CR
FK1|31|FK1_DOC|C|50|0|Documento|Número do documento
FK1|32|FK1_IDPROC|C|7|0|ID Processo|Identificador de Processo
FK1|33|FK1_DTDISP|D|8|0|Data Dispon.|Data de Disponibilizacao
FK1|34|FK1_DTDIGI|D|8|0|Data Digit.|Data da Digitacao
FK1|35|FK1_NUMBOR|C|6|0|Borderô|Número do Borderô
--- ### FK2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK2|01|FK2_FILIAL|C|6|0|Filial|Filial do Sistema
FK2|02|FK2_IDFK2|C|32|0|Id Baixas|Identif Baixas
FK2|03|FK2_DATA|D|8|0|Data Baixa|Data Baixa
FK2|04|FK2_VALOR|N|16|2|Valor Baixa|Valor da Baixa
FK2|05|FK2_MOEDA|C|2|0|Moeda|Moeda
FK2|06|FK2_NATURE|C|10|0|Natureza|Natureza
FK2|07|FK2_VENCTO|D|8|0|Vencimento|Vencimento
FK2|08|FK2_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK2|09|FK2_TPDOC|C|2|0|Tipo do Doc.|Tipo da movimentacao
FK2|10|FK2_HISTOR|C|40|0|Histórico|Histórico do movimento
FK2|11|FK2_VLMOE2|N|16|2|Vlr. Moeda 2|Valor na Moeda 2
FK2|12|FK2_LOTE|C|4|0|Lote|Lote da Baixa
FK2|13|FK2_MOTBX|C|3|0|Mot. Baixa|Motivo da Baixa do Título
FK2|14|FK2_ORDREC|C|6|0|Rec/Ordem|Numero do Recibo/Ordem
FK2|15|FK2_FILORI|C|6|0|Filial Orig.|Filial Origem
FK2|16|FK2_ARCNAB|C|12|0|Arquivo CNAB|Arquivo CNAB
FK2|17|FK2_CNABOC|C|2|0|Ocorr. CNAB|Ocorrencia Baixa CNAB
FK2|18|FK2_TXMOED|N|11|4|Tx Moeda Tit|Taxa contratada moeda tit
FK2|19|FK2_SERREC|C|3|0|Serie Recibo|Serie do Recibo
FK2|20|FK2_MULNAT|C|1|0|Mult. Nat.|Rat. Mult Natureza
FK2|21|FK2_AUTBCO|C|25|0|Aut.Bancaria|Autenticacao Bancaria
FK2|22|FK2_CCUSTO|C|9|0|C. de Custo|Centro de Custo
FK2|23|FK2_ORIGEM|C|8|0|Origem|Origem Movimento Baixas
FK2|24|FK2_SEQ|C|2|0|Sequencia|Sequencia da Baixa
FK2|25|FK2_DIACTB|C|2|0|Cod Diario|Cod Diario Contabilidade
FK2|26|FK2_NODIA|C|10|0|Seq. Diario|Seq. Diario Contabilidade
FK2|27|FK2_LA|C|1|0|Ident. Lanc.|Identifica Lançamento
FK2|28|FK2_IDDOC|C|32|0|Id. Doc|Identif Documento
FK2|29|FK2_DOC|C|50|0|Documento|Número do documento
FK2|30|FK2_IDCOMP|C|32|0|ID Compensac|Identificador Compensação
FK2|31|FK2_IDPROC|C|7|0|ID Processo|Identificador de Processo
FK2|32|FK2_DTDISP|D|8|0|Data Dispon.|Data de Disponibilizacao
FK2|33|FK2_DTDIGI|D|8|0|Data Digit.|Data da Digitacao
FK2|34|FK2_REINF|C|1|0|Env. TAF?|Enviado ao TAF?
--- ### FK3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK3|01|FK3_FILIAL|C|6|0|Filial|Filial do Sistema
FK3|02|FK3_IDFK3|C|10|0|Id Calculo.|Identificação Calculo.
FK3|03|FK3_DATA|D|8|0|Data Calculo|Data Calculo
FK3|04|FK3_VALOR|N|16|2|Valor Calc.|Valor Calculado
FK3|05|FK3_MOEDA|C|2|0|Moeda|Moeda
FK3|06|FK3_NATURE|C|10|0|Natureza|Natureza
FK3|07|FK3_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK3|08|FK3_IDRET|C|10|0|Id Retenção|Identifacação da Retencão
FK3|09|FK3_IMPOS|C|6|0|Imposto Calc|Imposto Calculado
FK3|10|FK3_FILORI|C|6|0|Filial Orig.|Filial Origem
FK3|11|FK3_BASIMP|N|16|2|Base Calculo|Base Calculo
FK3|12|FK3_ORIGEM|C|8|0|Origem|Origem Movimento Calc.
FK3|13|FK3_VLMOE2|N|16|2|Vlr.Moeda 2|Vlr.Moeda 2
FK3|14|FK3_IDORIG|C|32|0|Id. Origem|Id. Origem
FK3|15|FK3_TABORI|C|3|0|Tab. Origem|Tabela Origem
FK3|16|FK3_STATUS|C|1|0|St. Registro|Status do registro
FK3|17|FK3_CLIFOR|C|6|0|Cli/For|Codigo Cli/For
FK3|18|FK3_LOJA|C|2|0|Loja|Loja do Cli/For
FK3|19|FK3_CGC|C|14|0|CNPJ/CPF|CNPJ/CPF Cli/For
FK3|20|FK3_RAICGC|C|8|0|Raiz CNPJ|Raiz CNPJ
FK3|21|FK3_CODFKM|C|6|0|Tipo Imposto|Código do Tipo de Imposto
FK3|22|FK3_CODRET|C|4|0|Cod Retencao|Codigo de retençao
FK3|23|FK3_TABPRO|C|1|0|Tab. Progr.?|Tabela progressiva?
--- ### FK4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK4|01|FK4_FILIAL|C|6|0|Filial|Filial do Sistema
FK4|02|FK4_IDFK4|C|10|0|Id. Ret.|Identificação da Retenção
FK4|03|FK4_DATA|D|8|0|Data Ret.|Data Retenção
FK4|04|FK4_VALOR|N|16|2|Valor Calc.|Valor Calculado
FK4|05|FK4_MOEDA|C|2|0|Moeda|Moeda
FK4|06|FK4_NATURE|C|10|0|Natureza|Natureza
FK4|07|FK4_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK4|08|FK4_IMPOS|C|6|0|Imp. Calc.|Imposto Calculado
FK4|09|FK4_FILORI|C|6|0|Filial Orig.|Filial Origem.
FK4|10|FK4_BASIMP|N|16|2|Base Calculo|Base Calculo
FK4|11|FK4_ORIGEM|C|8|0|Origem|Origem Movimento Calc.
FK4|12|FK4_VLMOE2|N|16|2|Vlr.Moeda 2|Vlr.Moeda 2
FK4|13|FK4_IDORIG|C|32|0|Id. Origem|Id. Origem
FK4|14|FK4_STATUS|C|1|0|St. Registro|Status do registro
FK4|15|FK4_CLIFOR|C|6|0|Cli/For|Cli/For Origem Rentenção
FK4|16|FK4_LOJA|C|2|0|Loja|Loja do Cli/For
FK4|17|FK4_CGC|C|14|0|CNPJ/CPF|CNPJ/CPF Cli/For
FK4|18|FK4_RAICGC|C|8|0|Raiz CNPJ|Raiz CNPJ
FK4|19|FK4_CODFKM|C|6|0|Tipo Imposto|Código do Tipo de Imposto
FK4|20|FK4_CODRET|C|4|0|Cod Retencao|Codigo de retençao
FK4|21|FK4_DEDIRS|N|16|2|Ded IRPF Sim|Dedução IRPF Simplificado
FK4|22|FK4_TABPRO|C|1|0|Tab. Progr.?|Tabela Progressiva?
FK4|23|FK4_TABORI|C|3|0|Tab. Origem|Tabela Origem
--- ### FK5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK5|01|FK5_FILIAL|C|6|0|Filial|Filial do Sistema
FK5|02|FK5_IDMOV|C|32|0|Id. Mov.|Identif. Movimento
FK5|03|FK5_DATA|D|8|0|Data Mov.|Data do Movimento
FK5|04|FK5_VALOR|N|16|2|Valor Mov.|Valor do Movimento
FK5|05|FK5_MOEDA|C|2|0|Moeda|Moeda
FK5|06|FK5_NATURE|C|10|0|Natureza|Natureza
FK5|07|FK5_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK5|08|FK5_TPDOC|C|2|0|Tipo do Doc.|Tipo da movimentação
FK5|09|FK5_FILORI|C|6|0|Filial Orig.|Filial Origem
FK5|10|FK5_ORIGEM|C|8|0|Origem|Origem Movimento Calc.
FK5|11|FK5_BANCO|C|3|0|Banco|Codigo do Banco
FK5|12|FK5_AGENCI|C|5|0|Agencia|Agencia do banco
FK5|13|FK5_CONTA|C|10|0|Conta Banco|Conta corrente no banco
FK5|14|FK5_NUMCH|C|15|0|Num Cheque|Número do Cheque
FK5|15|FK5_DOC|C|50|0|Documento|Número do documento
FK5|16|FK5_HISTOR|C|40|0|Historico|Historico do movimento
FK5|17|FK5_VLMOE2|N|16|2|Vlr. Moeda 2|Valor na Moeda 2
FK5|18|FK5_DTCONC|D|8|0|Dt. Conc.|Data Conciliação
FK5|19|FK5_DTDISP|D|8|0|Data Dispon.|Data de Disponibilizacao
FK5|20|FK5_MODSPB|C|1|0|Modalid. SPB|Modalidade SPB
FK5|21|FK5_SEQCON|C|10|0|Seq. Conc.|Sequência Conciliação
FK5|22|FK5_TERCEI|C|1|0|Doc Terceiro|Documento de terceiros
FK5|23|FK5_TPMOV|C|1|0|Tipo Movim.|Tipo do Movimento
FK5|24|FK5_OK|C|2|0|Iden.Selecao|Identificador de Seleção
FK5|25|FK5_STATUS|C|1|0|Status Orig.|Staus do Titulo Origem
FK5|26|FK5_RATEIO|C|1|0|Rateio|Rateio Centro Custo
FK5|27|FK5_SEQ|C|2|0|Sequencia|Sequencia da Baixa
FK5|28|FK5_PROTRA|C|20|0|Proc. Transf|Numero do Processo na Tra
FK5|29|FK5_CCUSTO|C|9|0|C. de Custo|Centro de Custo
FK5|30|FK5_NUMBOR|C|6|0|Num Bordero|Número do Bordero
FK5|31|FK5_LA|C|1|0|Ident. Lanc.|Identifica Lançamento
FK5|32|FK5_TXMOED|N|11|4|Tx moeda Mov|Taxa contratada moeda Mov
FK5|33|FK5_ORDREC|C|6|0|Rec/Ordem|Numero do Recibo/Ordem
FK5|34|FK5_LOTE|C|4|0|Lote|Lote da Baixa
FK5|35|FK5_IDDOC|C|32|0|Id. Doc|Identif Documento
FK5|36|FK5_IDFK7|C|32|0|Id. FK7|Identificador do Título
FK5|37|FK5_CODBAR|C|48|0|Cod Barras|Código de Barras
FK5|38|FK5_CODPIX|C|35|0|Cod. PIX|Código PIX
FK5|39|FK5_MSUIDT|C|36|0|Campo UUID|
FK5|40|FK5_BENEF|C|30|0|Beneficiário|Descrição do beneficiário
--- ### FK6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK6|01|FK6_FILIAL|C|6|0|Filial|Filial do Sistema
FK6|02|FK6_IDFK6|C|10|0|Id. Calc.|Identif. Calculo
FK6|03|FK6_VALCAL|N|16|2|Valor Calc.|Valor Calculado
FK6|04|FK6_VALMOV|N|16|2|Vl Movimento|Valor Movimento
FK6|05|FK6_TPDESC|C|1|0|Desc. F100|Desconto F100
FK6|06|FK6_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
FK6|07|FK6_TPDOC|C|2|0|Tipo do Doc.|Tipo da movimentacao
FK6|08|FK6_IDORIG|C|32|0|Id. Origem|Id. Origem
FK6|09|FK6_TABORI|C|3|0|Tab. Orig.|Tabela origem
FK6|10|FK6_HISTOR|C|40|0|Historico|Historico do movimento
FK6|11|FK6_CODVAL|C|6|0|Código|Código do Valor Acessório
FK6|12|FK6_ACAO|C|1|0|Ação|Ação Valor Acessório
FK6|13|FK6_IDFKD|C|32|0|Id. FKD|Identif. da tabela FKD
FK6|14|FK6_DATA|D|8|0|Data|Data da ocorrência
FK6|15|FK6_MOEDA|C|2|0|Numerario|Numerário
FK6|16|FK6_VLMOE2|N|16|2|Vlr.Moeda 2|Valor na moeda 2
FK6|17|FK6_TXMOED|N|11|4|Tx Moeda Tit|Taxa da moeda no processo
FK6|18|FK6_LA|C|1|0|Flag|Flag de contabilização
FK6|19|FK6_ORIGEM|C|8|0|Origem|Origem do movimento
--- ### FK7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK7|01|FK7_FILIAL|C|6|0|Filial|Filial do Sistema
FK7|02|FK7_IDDOC|C|32|0|Id. Doc.|Identif. Documento
FK7|03|FK7_ALIAS|C|3|0|Tab. Orig.|Tabela Origem
FK7|04|FK7_CHAVE|C|100|0|Chave|Chave do documento
FK7|05|FK7_FILTIT|C|6|0|Filial Titul|Filial do Título
FK7|06|FK7_PREFIX|C|3|0|Prefixo|Prefixo do título
FK7|07|FK7_NUM|C|9|0|No. Titulo|Número do Título
FK7|08|FK7_PARCEL|C|3|0|Parcela|Parcela do título
FK7|09|FK7_TIPO|C|3|0|Tipo|Tipo do título
FK7|10|FK7_CLIFOR|C|6|0|Cli/For|Código Cliente/Fornecedor
FK7|11|FK7_LOJA|C|2|0|Loja|Loja Cliente/Fornecedor
FK7|12|FK7_IDPAI|C|32|0|Id. Doc. Pai|ID. Doc. Título Pai
--- ### FK8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK8|01|FK8_FILIAL|C|6|0|Filial|Filial do Sistema
FK8|02|FK8_IDMOV|C|32|0|Id. Mov.|Identif. Mov.
FK8|03|FK8_TPLAN|C|1|0|Tipo Lanc.|Tipo Lancamento contabil
FK8|04|FK8_DEBITO|C|20|0|Conta Debito|Conta Debito
FK8|05|FK8_CREDIT|C|20|0|Cta. Credito|Conta Credito
FK8|06|FK8_CCD|C|9|0|C.Custo Deb.|Centro de Custo Debito
FK8|07|FK8_CCC|C|9|0|C.Custo Crd.|Centro de Custo Credito
FK8|08|FK8_ARQRAT|C|50|0|Arq. Rateio|Arquivo no Rateio
FK8|09|FK8_ITEMD|C|9|0|Item Debito|Item Contabil Debito
FK8|10|FK8_ITEMC|C|9|0|Item Credito|Item Contabil Credito
FK8|11|FK8_CLVLDB|C|9|0|Cl Valor Deb|Classe Valor Debito
FK8|12|FK8_CLVLCR|C|9|0|Cl Valor Crd|Classe Valor Credito
FK8|13|FK8_DIACTB|C|2|0|Cod. Diario|Cod. Diario Contabilidade
FK8|14|FK8_NODIA|C|10|0|Seq. Diario|Seq. Diario Contabilidade
--- ### FK9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FK9|01|FK9_FILIAL|C|6|0|Filial|Filial do Sistema
FK9|02|FK9_IDMOV|C|32|0|Id. Mov.|Identificação Movimento
FK9|03|FK9_SITUA|C|2|0|Situacao Frt|Sit.Registro no FrontLoja
FK9|04|FK9_PRJPMS|C|10|0|Projeto|Codigo do Projeto
FK9|05|FK9_EDTPMS|C|12|0|EDT|EDT do Projeto
FK9|06|FK9_TASPMS|C|12|0|Tarefa|Tarefa do Projeto
FK9|07|FK9_OPERAD|C|6|0|Operador|Operador Telecobranca
FK9|08|FK9_NUMMOV|C|2|0|Movimento|Movimento do Dia
FK9|09|FK9_FLDMED|C|1|0|St. DMED|Status do registro
FK9|10|FK9_FORMPG|C|5|0|Forma pagto|Forma de pagamento
--- ### FKA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKA|01|FKA_FILIAL|C|6|0|Filial|Filial do Sistema
FKA|02|FKA_IDFKA|C|32|0|Id. Mov.|Identificação Movimento
FKA|03|FKA_IDPROC|C|20|0|Id. Processo|Id. Processo
FKA|04|FKA_IDORIG|C|32|0|Id. Origem|Id. Origem
FKA|05|FKA_TABORI|C|3|0|Tab. Orig.|Tabela origem
--- ### FKB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKB|01|FKB_FILIAL|C|6|0|Filial|Filial do Sistema
FKB|02|FKB_TPDOC|C|2|0|Tipo do Doc.|Tipo da movimentação
FKB|03|FKB_DESCR|C|20|0|Desc. Mov.|Descrição do movimento
FKB|04|FKB_ATUBCO|C|1|0|Atualiza Bco|Atualiza Banco
FKB|05|FKB_PERALT|C|1|0|Permite Alt.|Permite alteração
--- ### FKC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKC|01|FKC_FILIAL|C|6|0|Filial|Filial do Sistema
FKC|02|FKC_CODIGO|C|6|0|Código|Código do Valor Acessório
FKC|03|FKC_DESC|C|40|0|Descrição|Descrição
FKC|04|FKC_ACAO|C|1|0|Ação|Ação Vl. Acessório
FKC|05|FKC_TPVAL|C|1|0|Tipo Valor|Tipo de Valor
FKC|06|FKC_APLIC|C|1|0|Aplicação|Aplicação
FKC|07|FKC_PERIOD|C|1|0|Período|Periodo de Aplicação
FKC|08|FKC_ATIVO|C|1|0|Ativo|Ativo
FKC|09|FKC_RECPAG|C|1|0|Carteira|Carteira
FKC|10|FKC_VARCTB|C|8|0|Variável CTB|Variável Contabilização
FKC|11|FKC_REGRA|C|120|0|Regra|Regra complementar
FKC|12|FKC_NDIAS|N|5|0|Fator dia|Fator dia
--- ### FKD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKD|01|FKD_FILIAL|C|6|0|Filial|Filial do Sistema
FKD|02|FKD_CODIGO|C|6|0|Código|Código do Valor Acessório
FKD|03|FKD_DESC|C|40|0|Descrição|Descrição
FKD|04|FKD_ACAO|C|1|0|Ação|Ação Valor Acessório
FKD|05|FKD_TPVAL|C|1|0|Tipo Valor|Tipo de Valor
FKD|06|FKD_APLIC|C|1|0|Aplicação|Aplicação
FKD|07|FKD_PERIOD|C|1|0|Período|Período de aplicação
FKD|08|FKD_VALOR|N|16|2|Valor|Valor Acessório
FKD|09|FKD_IDDOC|C|32|0|Id do Título|ID do Título
FKD|10|FKD_SALDO|N|16|2|Vl. Baixado|Valor baixado
FKD|11|FKD_DTBAIX|D|8|0|Dt.Baixa|Data de Baixa
FKD|12|FKD_RECPAG|C|1|0|Carteira|Carteira
FKD|13|FKD_VLCALC|N|16|2|Valor Calc.|Valor Calculado
FKD|14|FKD_VLINFO|N|16|2|Vl.Informado|Valor Informado Baixa
FKD|15|FKD_IDFKD|C|32|0|Id. FKD|Identif. da FKD
--- ### FKE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKE|01|FKE_FILIAL|C|6|0|Filial|Filial do Sistema
FKE|02|FKE_IDFKE|C|6|0|Código|Cod. complemento imposto
FKE|03|FKE_DESCR|C|30|0|Descrição|Desc. Complemento imposto
FKE|04|FKE_TPIMP|C|6|0|Tipo Imposto|Tipo do Imposto
FKE|05|FKE_DEDACR|C|1|0|Ação|Subtrai, Soma ou Informa
FKE|06|FKE_APLICA|C|1|0|Aplicação|Ap.regra na base ou valor
FKE|07|FKE_CARTEI|C|1|0|Carteira|Regra valida p/ carteira
FKE|08|FKE_CALCUL|C|1|0|Calcula por|Calcula por Valor ou %
FKE|09|FKE_PERCEN|N|6|2|Percentual|Percentual para cálculo
FKE|10|FKE_TPATRB|C|6|0|Tipo Ação|Tipo ação do complem. imp
FKE|11|FKE_DESATR|C|55|0|Descr.Compl|Descrição complemento
FKE|12|FKE_CLASSI|C|1|0|Classif. IR|Classificação IR
--- ### FKF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKF|01|FKF_FILIAL|C|6|0|Filial|Filial do Sistema
FKF|02|FKF_IDDOC|C|32|0|Id. Doc.|Identif. Documento
FKF|03|FKF_CPRB|C|1|0|Ret. CPRB|Indicativo Retenção CPRB
FKF|04|FKF_CNAE|C|8|0|CNAE|Código atividade econômic
FKF|05|FKF_TPREPA|C|6|0|Tp. Repasse|Tipo de Repasse
FKF|06|FKF_INDSUS|C|1|0|Susp. INSS|Ind.Exigibilidade Suspens
FKF|07|FKF_INDDEC|C|1|0|Ind 13o. Sal|Indicativo de 13o Salário
FKF|08|FKF_TPSERV|C|2|0|Tipo serviço|Classif tipo de serviço
FKF|09|FKF_CNO|C|6|0|Cod. CNO|Código do CNO
FKF|10|FKF_ORIINS|N|14|2|Vlr Ori INSS|Valor Original INSS
FKF|11|FKF_CODBEM|C|2|0|Cód. do Bem|Código do Bem
FKF|12|FKF_CODSER|C|4|0|Cód. Serviço|Código do Serviço
FKF|13|FKF_ESPEC|C|1|0|Espécie|Recebimento em espécie
FKF|14|FKF_CEDENT|C|6|0|Cedente|Código do cedente
FKF|15|FKF_LOJACE|C|2|0|Loja cedente|Loja do cedente
FKF|16|FKF_CEDNOM|C|80|0|Nome cedente|Nome do cedente
FKF|17|FKF_PAGPIX|M|10|0|QR Code|Conteudo do QR Code
FKF|18|FKF_RECPIX|C|1|0|Gera PIX|Gera Titulo no PIX
FKF|19|FKF_IOF|N|16|2|Valor IOF|Valor do IOF
FKF|20|FKF_NATREN|C|5|0|Natur. Rend.|Natureza do Rendimento
FKF|21|FKF_CGCSCP|C|14|0|CNPJ SCP|CNPJ SCP
FKF|22|FKF_REINF|C|1|0|Env. TAF?|Enviado para o TAF?
FKF|23|FKF_ORINAT|C|1|0|Origem NRT|Origem Nat. Rendimento
FKF|24|FKF_DTECON|D|8|0|Dt Escr Cont|Data escrituraçao contab.
--- ### FKG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKG|01|FKG_FILIAL|C|6|0|Filial|Filial do Sistema
FKG|02|FKG_ITEM|C|6|0|Item|Item
FKG|03|FKG_IDDOC|C|32|0|Id. Doc.|Identif. Documento
FKG|04|FKG_IDFKE|C|6|0|Código|Cod. complemento imposto
FKG|05|FKG_TPIMP|C|6|0|Tipo Imposto|Tipo do Imposto
FKG|06|FKG_DEDACR|C|1|0|Ação|Subtrai, Soma ou Informa
FKG|07|FKG_APLICA|C|1|0|Aplicação|Ap.regra na base ou valor
FKG|08|FKG_CALCUL|C|1|0|Calcula por|Calcula por Valor ou %
FKG|09|FKG_PERCEN|N|6|2|Percentual|Percentual para cálculo
FKG|10|FKG_TPATRB|C|6|0|Tipo Ação|Tipo ação do complem. imp
FKG|11|FKG_DESATR|C|55|0|Descr.Compl|Descrição complemento
FKG|12|FKG_DESCR|C|20|0|Descrição|Descrição
FKG|13|FKG_BASECA|N|14|2|Base de Calc|Base para cálculo do %
FKG|14|FKG_VALOR|N|16|2|Valor|Valor de dedução/adição
FKG|15|FKG_NUMPRO|C|10|0|Processo Jud|Numero Processo Judicial
FKG|16|FKG_TPPROC|C|1|0|Tipo Process|Tipo Processo
FKG|17|FKG_TITINS|C|32|0|Tit. INS.|Título de INSS
FKG|18|FKG_APURIN|C|1|0|Apur. INS.|Apuração INSS
FKG|19|FKG_CODSUS|C|14|0|Ind Suspens.|Cod. Indicativo suspensão
FKG|20|FKG_INSPRE|C|14|0|Prev.Complem|Inscrição Prev.Complement
FKG|21|FKG_CODDEP|C|6|0|Dependente|Dependente
--- ### FKH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKH|01|FKH_FILIAL|C|6|0|Filial|Filial do Sistema
FKH|02|FKH_LAYOUT|C|6|0|Layout|Codigo Layout TAF
FKH|03|FKH_ID|C|32|0|ID|ID do registro
FKH|04|FKH_REVISA|C|6|0|Revisão|Numero da revisao
FKH|05|FKH_MSGTAF|M|10|0|Mensagem|Mensagem TAF
FKH|06|FKH_IDMOV|C|32|0|IDMOV|ID do Movimento
FKH|07|FKH_TABORI|C|3|0|Tab.Origem|Tabela de origem
FKH|08|FKH_REINF|C|1|0|Env. TAF?|Flag de Integração TAF
--- ### FKI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKI|01|FKI_FILIAL|C|6|0|Filial|Filial do Sistema
FKI|02|FKI_MES|C|2|0|Mês|Mês de Referencia
FKI|03|FKI_ANO|C|4|0|Ano|Ano de Referencia
FKI|04|FKI_VALOR|N|8|2|Valor Dep.|Valor por Dependente
--- ### FKJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKJ|01|FKJ_FILIAL|C|6|0|Filial|Filial do sistema
FKJ|02|FKJ_COD|C|6|0|Codigo|Codigo do fornecedor
FKJ|03|FKJ_LOJA|C|2|0|Loja|Loja do fornecedor
FKJ|04|FKJ_CPF|C|11|0|CPF|Numero CPF
FKJ|05|FKJ_PERCEN|N|6|2|Percentual|Percentual de rateio IR
FKJ|06|FKJ_NOME|C|30|0|Nome|Nome do portador do CPF
FKJ|07|FKJ_NUMDEP|N|2|0|Dependentes|Nro. Dependentes
--- ### FKK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKK|01|FKK_FILIAL|C|6|0|Filial|Filial do sistema
FKK|02|FKK_CODIGO|C|6|0|Código|Código regra de retenção
FKK|03|FKK_DESCR|C|40|0|Descrição|Descr. regra Financeira
FKK|04|FKK_VERSAO|C|4|0|Versão|Versão da Regra
FKK|05|FKK_IDRET|C|32|0|ID Retenção|ID Retenção
FKK|06|FKK_VIGINI|D|8|0|Ini.Vigência|Data início de Vigência
FKK|07|FKK_VIGFIM|D|8|0|Fim Vigência|Data final da Vigência
FKK|08|FKK_FATGER|C|1|0|Fato Gerador|Fato gerador da Retenção
FKK|09|FKK_CART|C|1|0|Carteira|Carteira de Aplicação
FKK|10|FKK_CODRET|C|4|0|Cod.Retenção|Código de Retenção
FKK|11|FKK_ATIVO|C|1|0|Ativo|Ativo
FKK|12|FKK_CODFKP|C|6|0|Regra Vencto|Regra de Vencto Tributo
FKK|13|FKK_CODFKL|C|6|0|Regra Titulo|Regra Geração Titulo
FKK|14|FKK_CODFKN|C|6|0|Regra Calc.|Regra do calculo imposto
FKK|15|FKK_CODFKO|C|6|0|Regra Retenc|Regra de Retenção
FKK|16|FKK_CODFKU|C|6|0|Vl. Acessor|Regra Valores Acessórios
FKK|17|FKK_CONTA|C|20|0|Cta.Contábil|Conta contábil
FKK|18|FKK_CUSTO|C|9|0|Centro Custo|Centro Custo
FKK|19|FKK_ITEM|C|9|0|Item Contáb.|Item Contábil
FKK|20|FKK_CLVL|C|9|0|Classe Valor|Classe de Valor
FKK|21|FKK_VARCTB|C|8|0|Variável CTB|Variável Contábil
FKK|22|FKK_IDFKL|C|32|0|ID Regra Tit|Id Regra Titulo
FKK|23|FKK_IDFKN|C|32|0|Id Regra Cal|Id Regra Calculo
FKK|24|FKK_IDFKO|C|32|0|Id Regra Ret|Id Regra Retenção
FKK|25|FKK_IDFKU|C|32|0|ID VA|ID Valores Acessórios
FKK|26|FKK_IDFKP|C|32|0|Id Regra Vct|Id Regra Vencimentos
FKK|27|FKK_PROVIS|C|1|0|Gerar Provis|Gerar Provisório
FKK|28|FKK_VLNOTA|C|1|0|Vlr. Titulo|Valor do Titulo
FKK|29|FKK_ADTO|C|1|0|Antecipações|Titulos de Antecipação
FKK|30|FKK_PARCTO|C|1|0|Parcelamento|Parcelamento
--- ### FKL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKL|01|FKL_FILIAL|C|6|0|Filial|Filial do sistema
FKL|02|FKL_CODIGO|C|6|0|Código|Código da regra Títulos
FKL|03|FKL_DESCR|C|40|0|Descrição|Descrição Regra Titulos
FKL|04|FKL_TIPMOV|C|1|0|Tp. Movto.|Tipo de Movimento
FKL|05|FKL_RTPART|C|1|0|Participante|Tipo de Participante
FKL|06|FKL_PARTIC|C|6|0|Cod.Particip|Código do Participante
FKL|07|FKL_LOJA|C|2|0|Loja|Loja do Participante
FKL|08|FKL_NATUR|C|10|0|Natureza|Natureza do titulo
FKL|09|FKL_TIPO|C|3|0|Tipo Titulo|Tipo titulo a ser gerado
FKL|10|FKL_CARTMV|C|1|0|Carteira|Carteira do Movimento
FKL|11|FKL_IDRET|C|32|0|Id Regra|Id Regra Titulos
FKL|12|FKL_PREFIX|C|3|0|Prefixo|Prefixo Tit. Recolhimento
FKL|13|FKL_MINDIS|N|16|2|Vlr.Min.Disp|Vlr. Mínimo para Dispensa
--- ### FKM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKM|01|FKM_FILIAL|C|6|0|Filial|Filial do sistema
FKM|02|FKM_CODIGO|C|6|0|Código|Código do tipo de imposto
FKM|03|FKM_DESCR|C|40|0|Descrição|Descrição tipo de imposto
FKM|04|FKM_VERSAO|C|4|0|Versão|Versão do tipo de imposto
FKM|05|FKM_IDRET|C|32|0|ID Retenção|ID Retenção
FKM|06|FKM_VIGINI|D|8|0|Ini.Vigência|Data início de vigência
FKM|07|FKM_VIGFIM|D|8|0|Fim Vigência|Data final da vigência
FKM|08|FKM_FATGER|C|1|0|Fato Gerador|Fato gerador da retenção
FKM|09|FKM_PESSOA|C|1|0|Tipo Pessoa|Tipo de Pessoa
FKM|10|FKM_CODRET|C|4|0|Cod. Retenc.|Código de retenção
FKM|11|FKM_CART|C|1|0|Carteira|Carteira de Aplicação
FKM|12|FKM_ATIVO|C|1|0|Ativo|Ativo
FKM|13|FKM_TPCALC|C|1|0|Tp. Cálculo|Tipo de cálculo
FKM|14|FKM_ORIRET|C|1|0|Ori.Retenção|Origem da retenção
FKM|15|FKM_CODPCF|C|10|0|Código PCF|Cód. Pre Classif. Financ.
FKM|16|FKM_TPMVEM|C|1|0|Tipo Movto.|Tipo de movimento
FKM|17|FKM_PROVIS|C|1|0|Gerar Provis|Gerar Provisão
FKM|18|FKM_RTRSPE|C|1|0|Participante|Participante da retenção
FKM|19|FKM_RESPEM|C|6|0|Cod. Partic.|Código do Participante
FKM|20|FKM_LOJA|C|2|0|Loja|Loja do participante
FKM|21|FKM_CRTMVE|C|1|0|Carteira Mov|Carteira de movimento
FKM|22|FKM_NATUEM|C|10|0|Natureza|Natureza titulo destacado
FKM|23|FKM_TIPOEM|C|3|0|Tipo Titulo|Tipo titulo a ser gerado
FKM|24|FKM_PARCME|C|1|0|Parcelamento|Parcelamento na emissão
FKM|25|FKM_VLNOTE|C|1|0|Vlr. da Nota|Valor da nota
FKM|26|FKM_TPMVBX|C|1|0|Tipo Movto.|Tipo de movimento
FKM|27|FKM_RTRSPB|C|1|0|Resp.Retenc.|Responsável pela retenção
FKM|28|FKM_RESPBX|C|6|0|Responsável|Código do responsável
FKM|29|FKM_LOJABX|C|2|0|Loja|Loja do responsável
FKM|30|FKM_CRTMVB|C|1|0|Carteira Mov|Carteira de movimento
FKM|31|FKM_NATUBX|C|10|0|Natureza|Natureza titulo destacado
FKM|32|FKM_TIPOBX|C|3|0|Tipo Titulo|Tipo título a ser gerado
FKM|33|FKM_ANTEBX|C|1|0|Antecipações|Antecipaçõe
FKM|34|FKM_TIPANT|C|3|0|Tp.Tit.Adto.|Tipo Titulo Adiantamento
FKM|35|FKM_PGTPAR|C|1|0|Pg. Parciais|Pagamentos Parciais
FKM|36|FKM_VLNOTB|C|1|0|Vlr. Pagto.|Ação Sobre Vlr Pagamento
FKM|37|FKM_EDTCAL|C|1|0|Edita calc.|Edição de cálculo
FKM|38|FKM_DIFPRV|C|1|0|Dif.Provisão|Diferença de Provisão
FKM|39|FKM_DIFCAL|C|1|0|Dif. Cálculo|Diferença cálculo sistema
FKM|40|FKM_VLRDEC|C|1|0|Vlr. Decimal|Valor decimal
FKM|41|FKM_DIAVCT|N|2|0|Dia Vencto.|Dia do Vencimento
FKM|42|FKM_TIPVCT|C|1|0|Tipo Vencto.|Tipo de Vencimento
FKM|43|FKM_PRDVCT|C|1|0|Periodo Vct.|Periodo do Vencimento
FKM|44|FKM_QTPERI|N|3|0|Qtd.Periodos|Quantidade de períodos
FKM|45|FKM_DTVLVC|C|1|0|Data Válida|Data válida p/ vencimento
FKM|46|FKM_DATVCT|C|1|0|Tipo Dia|Tipo de dias para calculo
FKM|47|FKM_PCBASE|N|6|2|% Base|Percentual Base
FKM|48|FKM_PORCEN|N|6|2|Porcentual|Porcentual do imposto
FKM|49|FKM_CUMULA|C|1|0|Cumulativid.|Cumulatividade
FKM|50|FKM_MINRET|N|16|2|Vlr.Min.Ret.|Valor mínimo de retenção
FKM|51|FKM_MAXRET|N|16|2|Vlr.Max.Ret.|Valor máximo de retenção
FKM|52|FKM_PERCUM|C|1|0|Periodo Cum.|Periodo de Cumulatividade
FKM|53|FKM_MODCUM|C|1|0|Acumula Por|Regra de Cumulatividade
FKM|54|FKM_CONTA|C|20|0|Cta.Contábil|Conta Contábil
FKM|55|FKM_CUSTO|C|9|0|Centro Custo|Centro de custo
FKM|56|FKM_ITEM|C|9|0|Item Contáb.|Item Contábil
FKM|57|FKM_CLVL|C|9|0|Classe Valor|Classe de Valor
FKM|58|FKM_VARCTB|C|8|0|Variável CTB|Variável contabilização
FKM|59|FKM_CUMFIL|C|1|0|Acum. Filial|Cumulatividade por Filial
FKM|60|FKM_CUMDAT|C|1|0|Data Cumulat|Data para cumulatividade
--- ### FKN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKN|01|FKN_FILIAL|C|6|0|Filial|Filial do Sistema
FKN|02|FKN_CODIGO|C|6|0|Código|Código Regra Calculo
FKN|03|FKN_DESCR|C|40|0|Descrição|Descrição Regra Cálculo
FKN|04|FKN_IDRET|C|32|0|Id Regra|Id Regra Calculo
FKN|05|FKN_PCBASE|N|6|2|% Base|Percentual da Base
FKN|06|FKN_PORCEN|N|6|2|Porcentual|Porcentual do Imposto
FKN|07|FKN_EDTCAL|C|1|0|Edita Calc.|Edita cálculo
FKN|08|FKN_DIFPRV|C|1|0|Dif.Provisão|Diferença provisão
FKN|09|FKN_DIFCAL|C|1|0|Dif. Calculo|Diferença de cálculo
FKN|10|FKN_VLRDEC|C|1|0|Vlr. Decimal|Valor decimais
FKN|11|FKN_CODFOS|C|6|0|Tab. Progres|Tabela Progressiva
FKN|12|FKN_CODFOV|C|6|0|Regra Deduc.|Regra de Deduções
FKN|13|FKN_VLNOTA|C|1|0|Vlr. Titulo|Valor do Titulo
FKN|14|FKN_IDFKS|C|32|0|Id Tabela|Id Tabela Progressiva
FKN|15|FKN_IDFKV|C|32|0|Id Retenção|ID Regra Dedução
--- ### FKO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKO|01|FKO_FILIAL|C|6|0|Filial|Filial do Sistema
FKO|02|FKO_CODIGO|C|6|0|Código|Código da regra Retenção
FKO|03|FKO_DESCR|C|40|0|Descrição|Descrição Regra Retenção
FKO|04|FKO_CUMULA|C|1|0|Cumulativid.|Cumulatividade
FKO|05|FKO_MINRET|N|16|2|Vlr.Min.Ret.|Valor mínimo de Retenção
FKO|06|FKO_MAXRET|N|16|2|Vlr.Max.Ret.|Valor máximo de Retenção
FKO|07|FKO_PERCUM|C|1|0|Periodo Cum.|Periodo de Cumulatividade
FKO|08|FKO_MODCUM|C|1|0|Acumula Por|Regra de Cumulatividade
FKO|09|FKO_CUMFIL|C|1|0|Acum. Filial|Cumulatividade por Filial
FKO|10|FKO_CUMDAT|C|1|0|Data Cumulat|Data para cumulatividade
FKO|11|FKO_CUMUL|C|1|0|Tipo Cumulat|Tipo Cumulatividade
FKO|12|FKO_CODFKT|C|6|0|Cod.Cumulat.|Cod. Regra Cumulatividade
FKO|13|FKO_IDFKT|C|32|0|ID Retenção|Identificador de retenção
FKO|14|FKO_IDRET|C|32|0|Id Regra Ret|Id Regra Retenção
FKO|15|FKO_USOURF|C|1|0|Consid. URF|Considera URF
--- ### FKP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKP|01|FKP_FILIAL|C|6|0|Filial|Filial do Sistema
FKP|02|FKP_CODIGO|C|6|0|Código|Código Regra Vencimento
FKP|03|FKP_DESCR|C|40|0|Descrição|Descrição Regra Venctos.
FKP|04|FKP_DIAVCT|N|2|0|Dia Vencto.|Dia do vencimento
FKP|05|FKP_TIPVCT|C|1|0|Tipo Vencto.|Tipo de vencimento
FKP|06|FKP_PRDVCT|C|1|0|Periodo Vct.|Periodos do vencimento
FKP|07|FKP_QTPERI|N|3|0|Qtd.Periodos|Quantidade de Periodos
FKP|08|FKP_DATVCT|C|1|0|Tipo Dia|Tipo de dias para calculo
FKP|09|FKP_DTVLVC|C|1|0|Data Válida|Data válida p/ vencimento
FKP|10|FKP_BASEVC|C|1|0|Base Vcto|Data Base Vencimento
FKP|11|FKP_IDRET|C|32|0|Id Regra|ID Regra Vencimento
FKP|12|FKP_DIAQUI|C|1|0|Dia Quinzena|Primeiro/Último dia útil
--- ### FKQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKQ|01|FKQ_FILIAL|C|6|0|Filial|Filial do Sistema
FKQ|02|FKQ_CODFKK|C|6|0|Tributo|Código do Tributo
FKQ|03|FKQ_IDF2B|C|36|0|Id Cad. Trib|Id cadastro do tributo
FKQ|04|FKQ_IDFK7|C|32|0|ID Parcela|Identificador Parcela
FKQ|05|FKQ_CODF2E|C|6|0|Tributo|Tributo
FKQ|06|FKQ_VLBASE|N|16|2|Vl. Base|Valor Base Tributo
FKQ|07|FKQ_VLIMPO|N|16|2|Vl. Tributo|Valor do Tributo
FKQ|08|FKQ_FATGER|C|1|0|Regime Trib.|Regime do tributo
FKQ|09|FKQ_CODURF|C|6|0|Cod. URF|Código URF
FKQ|10|FKQ_PCTURF|N|9|5|% URF|Percentual URF
FKQ|11|FKQ_TABPRO|C|1|0|Tab. Progr.?|Tabela progressiva?
--- ### FKS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKS|01|FKS_FILIAL|C|6|0|Filial|Filial do Sistema
FKS|02|FKS_CODIGO|C|6|0|Código|Código tabela financeira
FKS|03|FKS_DESCR|C|40|0|Descrição|Descrição Tabela Valores
FKS|04|FKS_IDRET|C|32|0|Id Ret|Identificador do cadastro
FKS|05|FKS_DEDSIM|N|16|2|Ded. Simplif|Vlr. Dedução Simplificada
--- ### FKT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKT|01|FKT_FILIAL|C|6|0|Filial|Filial do Sistema
FKT|02|FKT_IDRET|C|32|0|Id Retenção|Id Interno do tipo de ret
FKT|03|FKT_CODIGO|C|6|0|Código|Cód. Regra Cumulatividade
FKT|04|FKT_DESCR|C|40|0|Descrição|Desc.Regra Cumulatividade
--- ### FKU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKU|01|FKU_FILIAL|C|6|0|Filial|Filial do Sistema
FKU|02|FKU_IDRET|C|32|0|IdRet|ID Regra Valor Acessório
FKU|03|FKU_CODIGO|C|6|0|Código|Cód.Regra Vl. Acessororio
FKU|04|FKU_DESCR|C|40|0|Descrição|Desc. Regra Val. Acess.
--- ### FKV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKV|01|FKV_FILIAL|C|6|0|Filial|Filial do Sistema
FKV|02|FKV_IDRET|C|32|0|ID Ret|ID Regra Cumulatividade
FKV|03|FKV_CODIGO|C|6|0|Código|Cód. Regra Deduções
FKV|04|FKV_DESCR|C|40|0|Descrição|Desc. Regra Deduções
--- ### FKW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKW|01|FKW_FILIAL|C|6|0|Filial|Filial do Sistema
FKW|02|FKW_IDFKW|C|32|0|Código|Código
FKW|03|FKW_IDDOC|C|32|0|ID Documento|ID Documento
FKW|04|FKW_CARTEI|C|1|0|Carteira|Carteira do titulo
FKW|05|FKW_TPIMP|C|6|0|Tipo Imposto|Tipo de Imposto
FKW|06|FKW_NATREN|C|5|0|Natur. Rend.|Natureza de Rendimento
FKW|07|FKW_PERC|N|11|7|Percentual|Percentual
FKW|08|FKW_BASETR|N|14|2|Base Tribut.|Base Tributável
FKW|09|FKW_VLIMP|N|14|2|Vlr. Imposto|Valor do imposto
FKW|10|FKW_BASENR|N|14|2|Base Nao Ret|Base imposto nao retido
FKW|11|FKW_VLIMPN|N|14|2|Vl Imp N Ret|Valor imposto não retido
FKW|12|FKW_NUMPRO|C|10|0|Processo Jud|Numero Processo Judicial
FKW|13|FKW_TPPROC|C|1|0|Tipo Process|Tipo Processo
FKW|14|FKW_CODSUS|C|14|0|Ind Suspens.|Cod. Indicativo suspensao
FKW|15|FKW_PERCNR|N|11|7|Percent NR|Percentual não Retido
FKW|16|FKW_CGC|C|14|0|CNPJ/CPF|CNPJ/CPF IR Aluguel
FKW|17|FKW_VLBRUT|N|14|2|Valor Bruto|Valor bruto
--- ### FKX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKX|01|FKX_FILIAL|C|6|0|Filial|Filial
FKX|02|FKX_CODIGO|C|5|0|Codigo|Codigo
FKX|03|FKX_DESCR|C|60|0|Descr. Resum|Descrição Resumida
FKX|04|FKX_FCI|C|1|0|FCI|Fundo/Clube Investimento
FKX|05|FKX_DECSAL|C|1|0|13º Salário|13º Salário
FKX|06|FKX_RRA|C|1|0|RRA|Rendimentos Receb. Acum.
FKX|07|FKX_TRIBUT|C|1|0|Tributos|Tributos
FKX|08|FKX_EXTPF|C|1|0|Pais Ext PF|Pais Ext PF
FKX|09|FKX_EXTPJ|C|1|0|Pais Ext PJ|Pais Ext PJ
FKX|10|FKX_TPDECL|C|1|0|Declarante|Declarante
FKX|11|FKX_DESEXT|M|10|0|Descr. Exten|Descrição Extendida
--- ### FKY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKY|01|FKY_FILIAL|C|6|0|Filial|Filial do Sistema
FKY|02|FKY_IDFKY|C|32|0|Código|Código
FKY|03|FKY_IDDOC|C|32|0|ID Documento|ID Documento
FKY|04|FKY_IDFK2|C|32|0|Id Baixas|Id Baixas
FKY|05|FKY_TPIMP|C|6|0|Tipo Imposto|Tipo do Imposto
FKY|06|FKY_NATREN|C|5|0|Natur. Rend.|Natureza de Rendimento
FKY|07|FKY_BASETR|N|14|2|Base Tribut.|Base Tributável
FKY|08|FKY_VLIMP|N|14|2|Vlr. Imposto|Valor do Imposto
FKY|09|FKY_BASENR|N|14|2|Base Nao Ret|Base imposto não retido
FKY|10|FKY_VLIMPN|N|14|2|Vl Imp N Ret|Valor imposto não retido
FKY|11|FKY_NUMPRO|C|10|0|Processo Jud|Numero Processo Judicial
FKY|12|FKY_TPPROC|C|1|0|Tipo Process|Tipo Processo
FKY|13|FKY_CODSUS|C|14|0|Ind Suspens.|Cod. Indicativo suspensao
FKY|14|FKY_IDORIG|C|32|0|ID Origem|ID Origem
FKY|15|FKY_TABORI|C|3|0|Tab Orig.|Tabela de origem
FKY|16|FKY_VLBRUT|N|14|2|Valor Bruto|Valor bruto
--- ### FKZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FKZ|01|FKZ_FILIAL|C|6|0|Filial|Filial
FKZ|02|FKZ_CODIGO|C|5|0|Cod.Natureza|Cod.Natureza Rendimento
FKZ|03|FKZ_DEDISE|C|1|0|Mod.Tribut|Tratamento Tributario
FKZ|04|FKZ_DEDUCA|C|2|0|Tipo Dedução|Tipo de Dedução
FKZ|05|FKZ_ISENCA|C|2|0|Tipo Isenção|Tipo de Isenção
--- ### FL0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL0|01|FL0_FILIAL|C|6|0|Filial|Filial do Sistema
FL0|02|FL0_CODIGO|C|12|0|Cód. do log|Código do log
FL0|03|FL0_ENTIDA|C|3|0|Entidade|Entidade do log
FL0|04|FL0_DATA|D|8|0|Data do log|Data do registro do log
FL0|05|FL0_HORA|C|8|0|Hora do log|Hora do registro do log
FL0|06|FL0_DESCRI|M|10|0|Desc. do log|Descrição do log
--- ### FL1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL1|01|FL1_FILIAL|C|6|0|Filial|Filial do Sistema
FL1|02|FL1_LICENC|C|20|0|Licenciado|Licenciado Reserve
FL1|03|FL1_IDPED|C|8|0|ID pedido|ID do Pedido no Rerserve
--- ### FL2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL2|01|FL2_FILIAL|C|6|0|Filial|Filial do Sistema
FL2|02|FL2_BKOAGE|C|20|0|BKO Agência|Código Empresa Agência
FL2|03|FL2_BKOEMP|C|20|0|BKO Empresa|Código da Empresa/Filial
FL2|04|FL2_USER|C|30|0|Usuário Inte|Usuário de Integração Res
FL2|05|FL2_PSWRES|C|30|0|Senha Integr|Senha Integração Reserve
FL2|06|FL2_LICENC|C|20|0|Licenciado|Licenciado no Reserve
FL2|07|FL2_GRPEMP|C|30|0|Grupo Empres|Grupo de Empresas
FL2|08|FL2_CC|C|1|0|Centro Custo|Centro Custo Compart.
FL2|09|FL2_CLIENT|C|1|0|Cliente|Compartilhamento Cliente
--- ### FL3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL3|01|FL3_FILIAL|C|6|0|Filial|Filial do Sistema
FL3|02|FL3_NIVEL|C|6|0|Nivel Cargo|Nivel Cargo
FL3|03|FL3_DESCRI|C|80|0|Descrição|Descrição do Nivel
--- ### FL4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL4|01|FL4_FILIAL|C|6|0|Filial|Filial do Sistema
FL4|02|FL4_ALIAS|C|3|0|Tabela|Tabela do Sistema
FL4|03|FL4_CAMPO|C|10|0|Campo Obrig.|Campo Obrigatório
FL4|04|FL4_CPODES|C|12|0|Descrição|Descrição do Campo
--- ### FL5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL5|01|FL5_FILIAL|C|6|0|Filial|Filial do Sistema
FL5|02|FL5_VIAGEM|C|10|0|Viagem|Codigo da Viagem
FL5|03|FL5_CODORI|C|10|0|Origem|Codigo origem da viagem
FL5|04|FL5_DESORI|C|40|0|Desc.Origem|Descricao da Origem
FL5|05|FL5_CODDES|C|10|0|Cod. Destino|Codigo do Local Destino
FL5|06|FL5_DESDES|C|40|0|Desc.Destino|Descricao do Destino
FL5|07|FL5_DTINI|D|8|0|Data Inicial|Data de inicio da viagem
FL5|08|FL5_DTFIM|D|8|0|Dt Final|Data final da viagem
FL5|09|FL5_NACION|C|1|0|Nacional|Indica viagem nacional
FL5|10|FL5_IDRESE|C|10|0|ID Reserve|Codigo do grupo reserve
FL5|11|FL5_LICRES|C|30|0|Lic.Reserve|Licenciado Reserve
FL5|12|FL5_STATUS|C|1|0|Status|Status da Solicitação
FL5|13|FL5_OBS|M|10|0|Observacao|Observacao sobre a viagem
FL5|14|FL5_CLIENT|C|6|0|Cliente|Codigo do cliente destino
FL5|15|FL5_LOJA|C|2|0|Loja|Loja do Cliente
FL5|16|FL5_NOME|C|80|0|Nome|Nome do Cliente
FL5|17|FL5_CC|C|9|0|Centro Custo|Cod. Centro Custo
FL5|18|FL5_ADIANT|C|1|0|Adiantamento|Viagem com adiantamento
FL5|19|FL5_VALCOB|N|14|2|Vlr Cobrado|Valor Cobrado do Cliente
FL5|20|FL5_PEDIDO|C|6|0|Pedido|Pedido de Venda
FL5|21|FL5_IDSOL|C|10|0|ID Solic.|Código da Solicitação
--- ### FL6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL6|01|FL6_FILIAL|C|6|0|Filial|Filial do Sistema
FL6|02|FL6_VIAGEM|C|10|0|Viagem|Solicitacao de Viagem
FL6|03|FL6_ITEM|C|2|0|Item Viagem|Item Solicitacao Viagem
FL6|04|FL6_LICENC|C|30|0|Licenciado|Licenciado Reserve
FL6|05|FL6_IDRESE|C|10|0|ID Reserve|ID do site Reserve
FL6|06|FL6_DTCRIA|D|8|0|Dt.Criacao|Data de Criacao
FL6|07|FL6_TIPO|C|1|0|Tipo Reserva|Tipo da Reserva
FL6|08|FL6_TOTFEE|N|15|2|Total Fee|Valor total Fee
FL6|09|FL6_DTEMIS|D|8|0|Dt Emissao|Data Emissao da Reserva
FL6|10|FL6_LOCALI|C|20|0|Localizador|Codigo do Localizador
FL6|11|FL6_LOCPAS|C|20|0|Loc.Passivo|Localizador Passivo
FL6|12|FL6_ORIRES|C|2|0|Orig.Reserva|Origem da Reserva
FL6|13|FL6_DTRESE|D|8|0|Dt.Reserva|Data da Reserva
FL6|14|FL6_TARPAX|N|15|2|Trf. Passag.|Tarifa por Passageiro
FL6|15|FL6_TAXPAX|N|15|2|Taxa Passag.|Taxa por Passageiro
FL6|16|FL6_TAXSER|N|15|2|Taxa Servico|Valor da Taxa de Servico
FL6|17|FL6_TARACO|N|15|2|Tarifa Acord|Valor da Tarifa Acordo
FL6|18|FL6_TARPRO|N|15|2|Tarifa Promo|Tarifa Promocional
FL6|19|FL6_TARREF|N|15|2|Tarifa Refer|Tarifa de Referencia
FL6|20|FL6_MENTAR|N|15|2|Menor Tarifa|Valor da menor tarifa
FL6|21|FL6_MOEDA|C|2|0|Moeda Tarifa|Cod. da Moeda Tarifa
FL6|22|FL6_MOETAX|C|2|0|Moeda Taxa|Cod. Moeda da Taxa
FL6|23|FL6_MULTA|N|15|2|Multa|Valor da Multa
FL6|24|FL6_CREDIT|N|15|2|Credito|Valor do Credito
FL6|25|FL6_TOTAL|N|15|2|Total|Valor Total da Reserva
FL6|26|FL6_IDSOL|C|10|0|ID Solic.|ID no Reserve Solicitante
FL6|27|FL6_NOMESO|C|50|0|Nome Solic.|Nome do Solicitante
FL6|28|FL6_PARTSO|C|6|0|Partic.Solic|Cod. Participante Solic.
FL6|29|FL6_IDRESP|C|10|0|ID Resp.|ID Reserve Responsavel
FL6|30|FL6_NOMERE|C|50|0|Nome Resp.|Nome do Responsavel
FL6|31|FL6_CONFER|N|14|2|Conferido|Valor Conferido
FL6|32|FL6_VINFOR|N|14|2|Informado|Valor Informado
FL6|33|FL6_INFORM|N|14|2|Informado|Valor Informado
FL6|34|FL6_PARTRE|C|6|0|Partic. Resp|Cod. Participante Resp.
FL6|35|FL6_IDREMA|C|10|0|Ped.Original|ID do Pedido Remarcado
FL6|36|FL6_STATUS|C|1|0|Status|Status da Conferencia
FL6|37|FL6_FPAGTO|C|2|0|Forma Pgto|Forma de Pagamento
FL6|38|FL6_BKOFAT|C|10|0|BKO Fatura|BKO da empresa Faturar
FL6|39|FL6_MOTIVO|C|25|0|Motivo|Motivo da Viagem
FL6|40|FL6_ATIVI|C|40|0|Atividade|Atividade
FL6|41|FL6_EXTRA1|C|25|0|Adiantamento|Adiantamento
FL6|42|FL6_EXTRA2|C|25|0|Cpo Extra2|Campo Extra 2
FL6|43|FL6_EXTRA3|C|40|0|Cpo Extra3|Campo Extra 3
FL6|44|FL6_VCONFE|N|14|2|Vl Conferido|Valor Conferido
FL6|45|FL6_NRCART|C|15|0|Num.Cartao|Número Cartão
--- ### FL7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL7|01|FL7_FILIAL|C|6|0|Filial|Filial do sistema
FL7|02|FL7_VIAGEM|C|10|0|Viagem|Codigo da Viagem
FL7|03|FL7_ITEM|C|2|0|Item Viagem|Item da Viagem Reserva
FL7|04|FL7_SUBITM|C|2|0|Subitem|Subitem da reserva
FL7|05|FL7_DSAIDA|D|8|0|Data Saida|Data de saida do voo
FL7|06|FL7_HSAIDA|C|5|0|Hora Saida|Horario de saida do voo
FL7|07|FL7_CODORI|C|10|0|Cod.Origem|Cod. do aerporto origem
FL7|08|FL7_ORIGEM|C|40|0|Nome Origem|Nome aeroporto origem
FL7|09|FL7_DCHEGA|D|8|0|Data chegada|Data de chegada do voo
FL7|10|FL7_HCHEGA|C|5|0|Hora Chegada|Horario de chegada do voo
FL7|11|FL7_CODES|C|10|0|Cod.Destino|Codigo aeroporto destino
FL7|12|FL7_DESTIN|C|40|0|Destino|Aeroporto Destino
FL7|13|FL7_CODCIA|C|20|0|Cia Aerea|Codigo da Companhia aerea
FL7|14|FL7_NOME|C|40|0|Nome|Nome da companhia
FL7|15|FL7_CLASSE|C|40|0|Classe|Classe da Passagem
FL7|16|FL7_VOO|C|40|0|Voo|Codigo do Voo
FL7|17|FL7_TE|C|3|0|Tp. Entrada|Tipo de Entrada
FL7|18|FL7_STATUS|C|40|0|Status|Status da Reserva
FL7|19|FL7_PROD|C|15|0|Produto|Produto
--- ### FL8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL8|01|FL8_FILIAL|C|6|0|Filial|Filial do Sistema
FL8|02|FL8_VIAGEM|C|10|0|Viagem|Solicitacao de Viagem
FL8|03|FL8_ITEM|C|2|0|Item|Item da Viagem
FL8|04|FL8_SUBITM|C|2|0|Subitem|Subitem da Reserva
FL8|05|FL8_DSAIDA|D|8|0|Data Saida|Data de Saida do Onibus
FL8|06|FL8_HSAIDA|C|5|0|Hora Saida|Horario saida do onibus
FL8|07|FL8_CODORI|C|10|0|Cod.Origem|Codigo origem rodoviaria
FL8|08|FL8_ORIGEM|C|40|0|Origem|Nome rodoviaria de origem
FL8|09|FL8_DCHEGA|D|8|0|Dt.Chegada|Data de chegada do onibus
FL8|10|FL8_HCHEGA|C|5|0|Hora Chegada|Horario chegada destino
FL8|11|FL8_CODDES|C|10|0|Cod.Destino|Cod.Rodoviario Destino
FL8|12|FL8_DESTIN|C|40|0|Destino|Rodoviaria Destino
FL8|13|FL8_CODCIA|C|15|0|Cod.Comp.|Cod.da comp. rodoviaria
FL8|14|FL8_NOME|C|40|0|Nome|Nome da companhia
FL8|15|FL8_CLASSE|C|40|0|Classe|Classe do onibus
FL8|16|FL8_PROD|C|15|0|Produto|Produto
FL8|17|FL8_TE|C|3|0|Tp. Entrada|Tipo de Entrada
--- ### FL9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FL9|01|FL9_FILIAL|C|6|0|Filial|Filial do Sistema
FL9|02|FL9_VIAGEM|C|10|0|Viagem|Codigo da Viagem
FL9|03|FL9_ITEM|C|2|0|Item Viagem|Item da viagem
FL9|04|FL9_SUBITM|C|2|0|Subitem|Subitem da Viagem
FL9|05|FL9_CODCID|C|10|0|Cod.Cidade|Código da cidade do hotel
FL9|06|FL9_CIDADE|C|40|0|Cidade|Nome da cidade
FL9|07|FL9_CODHOT|C|15|0|Codigo Hotel|Codigo do hotel
FL9|08|FL9_NOME|C|40|0|Nome|Nome do Hotel
FL9|09|FL9_DCHKIN|D|8|0|Dt. Checkin|Data do checkin
FL9|10|FL9_HCHKIN|C|5|0|Hr. Check-in|Hora do check-in
FL9|11|FL9_DCHKOU|D|8|0|Dt.Check-Out|Data do Check-Out
FL9|12|FL9_HCHKOU|C|5|0|Hr Check-Out|Horário do Check-Out
FL9|13|FL9_CATEG|C|40|0|Categoria|Categoria da acomodação
FL9|14|FL9_DIARIA|N|3|0|Diarias|Num. diarias reservadas
FL9|15|FL9_CNPJ|C|14|0|CNPJ|CNPJ do Hotel
FL9|16|FL9_PROD|C|15|0|Produto|Produto
FL9|17|FL9_TE|C|3|0|Tp. Entrada|Tipo de Entrada
FL9|18|FL9_DSAIDA|D|8|0|Data Ini.|Data de Inicio da Saida
--- ### FLA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLA|01|FLA_FILIAL|C|6|0|Filial|Filial do Sistema
FLA|02|FLA_VIAGEM|C|10|0|Viagem|Cod. Solicitacao Viagem
FLA|03|FLA_ITEM|C|2|0|Item|Item da viagem
FLA|04|FLA_SUBITM|C|2|0|Subitem|Subitem da reserva
FLA|05|FLA_INICIO|D|8|0|Inicio|Inicio da Validade
FLA|06|FLA_FINAL|D|8|0|Final|Final da Validade
FLA|07|FLA_CODCID|C|10|0|Cod.Cidade|Codigo da cidade
FLA|08|FLA_CIDADE|C|40|0|Cidade|Nome da cidade
FLA|09|FLA_CODSEG|C|10|0|Cod.Segurado|Codigo do segurado
FLA|10|FLA_NOME|C|50|0|Seguradora|Nome da Seguradora
FLA|11|FLA_PLANO|C|50|0|Plano|Descricao do plano
FLA|12|FLA_DIARIA|N|3|0|Diarias|Numero de diarias
FLA|13|FLA_PROD|C|15|0|Produto|Produto
FLA|14|FLA_TE|C|3|0|Tp. Entrada|Tipo de Entrada
--- ### FLB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLB|01|FLB_FILIAL|C|6|0|Filial|Filial do sistema
FLB|02|FLB_VIAGEM|C|10|0|Viagem|Solicitacao da Viagem
FLB|03|FLB_ITEM|C|2|0|Item|Item da viagem
FLB|04|FLB_SUBITM|C|2|0|Subitem|Subitem da viagem
FLB|05|FLB_CODRET|C|10|0|Cod.Cidade|Codigo da Cidade Retirada
FLB|06|FLB_CIDRET|C|40|0|Cidade Ret.|Cidade retirada veiculo
FLB|07|FLB_DRETIR|D|8|0|Retirada|Data de Retirada Veiculo
FLB|08|FLB_CODDEV|C|10|0|Cod.Devol.|Codigo cidade devolucao
FLB|09|FLB_CIDDEV|C|40|0|Cidade Devol|Cidade de Devolucao Veic.
FLB|10|FLB_DDEVOL|D|8|0|Devolucao|Data de devolucao
FLB|11|FLB_LOCDEV|C|40|0|Local Devol.|Local de devolução
FLB|12|FLB_IDLOC|C|10|0|Cod.Locadora|Codigo da locadora
FLB|13|FLB_NOME|C|40|0|Locadora|Nome da locadora
FLB|14|FLB_TIPVEI|C|40|0|Tipo Veiculo|Tipo do veiculo
FLB|15|FLB_DIARIA|N|3|0|Diarias|Numero de diarias
FLB|16|FLB_PROD|C|15|0|Produto|Produto
FLB|17|FLB_TE|C|3|0|Tp. Entrada|Tipo de entrada
--- ### FLC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLC|01|FLC_FILIAL|C|6|0|Filial|Filial do Sistema
FLC|02|FLC_VIAGEM|C|10|0|Viagem|Solicitacao de Viagem
FLC|03|FLC_PARTIC|C|6|0|Cod.Partic.|Cod. Participante
FLC|04|FLC_IDRESE|C|9|0|Id Reserve|Id Passageiro na Reserve
FLC|05|FLC_NOME|C|50|0|Participante|Nome do Passageiro
FLC|06|FLC_BILHET|C|20|0|Bilhete|Bilhete do Passageiro
--- ### FLD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLD|01|FLD_FILIAL|C|6|0|Filial|Filial do Sistema
FLD|02|FLD_VIAGEM|C|10|0|Cod. Viagem|Código da Viagem
FLD|03|FLD_ITEM|C|2|0|Item|Item da Reserva
FLD|04|FLD_PARTIC|C|6|0|Cód. Partic.|Código do Participante
FLD|05|FLD_NOMEPA|C|50|0|Participante|Nome do Participante
FLD|06|FLD_ADIANT|C|2|0|Adiantamento|Código do Adiantamento
FLD|07|FLD_SOLIC|C|6|0|Cód. Solic.|Código do Solicitante
FLD|08|FLD_NOMESO|C|50|0|Solicitante|Nome do Solicitante
FLD|09|FLD_DTSOLI|D|8|0|Dt. Solicit.|Data da Solicitação
FLD|10|FLD_DTPREV|D|8|0|Dt. Prev. Pg|Dt. de Previsão do Pagto
FLD|11|FLD_DTPAGT|D|8|0|Dt. Pagto.|Dt. do Pagamento
FLD|12|FLD_VALOR|N|15|2|Valor|Valor do Adiantamento
FLD|13|FLD_MOEDA|C|1|0|Moeda|Moeda
FLD|14|FLD_VALAPR|N|15|2|Vl. Aprovado|Valor Aprovado
FLD|15|FLD_APROV|C|6|0|Cód. Aprov.|Código do Aprovador
FLD|16|FLD_NOMEAP|C|50|0|Aprovador|Nome do Aprovador
FLD|17|FLD_DTAPRO|D|8|0|Dt. Aprov.|Data da Aprovação
FLD|18|FLD_OBSAPR|C|100|0|Obs. Aprov.|Obs. Aprovação
FLD|19|FLD_STATUS|C|1|0|Status|Status do Adiantamento
FLD|20|FLD_ENCERR|C|1|0|Encerrado|Adiantamento Encerrado
FLD|21|FLD_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
FLD|22|FLD_LOJA|C|2|0|Loja|Loja do Fornecedor
FLD|23|FLD_PREFIX|C|3|0|Prefixo|Prefixo do Título
FLD|24|FLD_TIPO|C|3|0|Tipo|Tipo do Título
FLD|25|FLD_TITULO|C|9|0|Num. Título|Número do Título
FLD|26|FLD_PARCEL|C|3|0|Parcela|Parcela do Título
FLD|27|FLD_JUSTIF|M|80|0|Justific.|Justificativa
FLD|28|FLD_WFKID|C|100|0|Workflow ID|ID de Workflow
FLD|29|FLD_TAXA|N|6|2|Taxa|Taxa de Conversão
FLD|30|FLD_WFOBS|C|80|0|Obs. Aprova|Observação de Aprovação
--- ### FLE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLE|01|FLE_FILIAL|C|6|0|Filial|Filial do Sistema
FLE|02|FLE_TIPO|C|1|0|Tipo|Tipo da Prest. de Contas
FLE|03|FLE_PRESTA|C|10|0|Pres. Contas|Prestação de Contas
FLE|04|FLE_PARTIC|C|6|0|Cod. Partic.|Código do Participante
FLE|05|FLE_ITEM|C|3|0|Item|Item prestação de contas
FLE|06|FLE_DATA|D|8|0|Data|Data da despesa
FLE|07|FLE_LOCAL|C|4|0|Cód.Local|Código do Local
FLE|08|FLE_DESPES|C|6|0|Despesa|Código da Despesa
FLE|09|FLE_DESCRI|C|40|0|Descrição|Descrição da Despesa
FLE|10|FLE_GRUPO|C|6|0|Grupo|Grupo da Despesa
FLE|11|FLE_QUANT|N|4|0|Quantidade|Quantidade da despesa
FLE|12|FLE_MOEDA|C|1|0|Moeda|Moeda
FLE|13|FLE_TOTAL|N|15|2|Valor Total|Valor Total da Despesa
FLE|14|FLE_TXCONV|N|15|2|Tx.Conversão|Taxa de conversão
FLE|15|FLE_VALREE|N|15|2|Reembolsável|Valor Reembolsável
FLE|16|FLE_VALNRE|N|15|2|Não Reembol.|Valor Não Reembolsavel
FLE|17|FLE_DESCON|N|15|2|Desconto|Valor de Desconto
FLE|18|FLE_DETDES|C|100|0|Detalhe Desc|Detalhe do Desconto
FLE|19|FLE_VALUNI|N|15|2|Val. Unit.|Valor unitário
FLE|20|FLE_CONTA|C|20|0|Conta Contab|Conta Contábil
FLE|21|FLE_CUSTO|C|9|0|C.Custo|Centro de Custo
FLE|22|FLE_ITECTB|C|9|0|Item Contab.|Item Contabil
FLE|23|FLE_CLVL|C|9|0|Classe Valor|Classe de Valor
FLE|24|FLE_LA|C|1|0|Ident. Lanc.|Identificador de LA
FLE|25|FLE_OBS|C|254|0|Observação|Observação da despesa
--- ### FLF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLF|01|FLF_FILIAL|C|6|0|Filial|Filial do Sistema
FLF|02|FLF_TIPO|C|1|0|Tipo|Tipo da Prestação
FLF|03|FLF_PRESTA|C|10|0|Pres. Contas|Cod. Prestação de Contas
FLF|04|FLF_VIAGEM|C|10|0|Cod. Viagem|Codigo da viagem
FLF|05|FLF_ITEM|C|2|0|Item|Item da Reserva
FLF|06|FLF_PARTIC|C|6|0|Cod. Partic.|Código do Participante
FLF|07|FLF_NOMEPA|C|50|0|Participante|Nome do participante
FLF|08|FLF_EMISSA|D|8|0|Emissão|Data de Emissão
FLF|09|FLF_DTINI|D|8|0|Saída|Data de Saída
FLF|10|FLF_DTFIM|D|8|0|Chegada|Data de chegada
FLF|11|FLF_NACION|C|1|0|Nacional|Viagem Nacional
FLF|12|FLF_MOTIVO|M|80|0|Motivo|Motivo da Viagem
FLF|13|FLF_CLIENT|C|6|0|Cliente|Código do Cliente
FLF|14|FLF_LOJA|C|2|0|Loja|Loja do Cliente
FLF|15|FLF_RAZAO|C|80|0|Nome Cliente|Nome do Cliente
FLF|16|FLF_CC|C|9|0|Centro Custo|Centro de Custo
FLF|17|FLF_DTFECH|D|8|0|Fechamento|Data do Fechamento
FLF|18|FLF_STATUS|C|1|0|Status|Status da prestação
FLF|19|FLF_FATCLI|N|3|0|% Cliente|% Faturamento do cliente
FLF|20|FLF_FATEMP|N|3|0|% Empresa|% Faturamento Empresa
FLF|21|FLF_RECPAG|C|1|0|Receb/Pagam|Recebimento ou Pagamento
FLF|22|FLF_CONFER|C|6|0|Cod. Confer.|Código do conferente
FLF|23|FLF_NOMECF|C|50|0|Conferente|Nome do conferente
FLF|24|FLF_DTCONF|D|8|0|Conferencia|Data da Conferência
FLF|25|FLF_OBCONF|C|100|0|Obs. Confer.|Observação da conferência
FLF|26|FLF_CLIFOR|C|6|0|Cli/For|Cliente / Fornec.
FLF|27|FLF_FLOJA|C|2|0|Loja Cli/For|Loja Cliente/Fornecedor
FLF|28|FLF_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FLF|29|FLF_TIPTIT|C|3|0|Tipo Titulo|Tipo do Título
FLF|30|FLF_TITULO|C|9|0|Num. Titulo|NUmero do Título
FLF|31|FLF_PARCEL|C|3|0|Parcela|Parcela do Título
FLF|32|FLF_PEDIDO|C|6|0|Pedido|Pedido Gerado
FLF|33|FLF_VALCOB|N|14|2|Vlr Cobrado|Valor Cobrado do Cliente
FLF|34|FLF_TDESP1|N|15|2|Tot. Desp. 1|Total Despesa Moeda 1
FLF|35|FLF_TDESP2|N|15|2|Tot. Desp. 2|Total Despesa Moeda 2
FLF|36|FLF_TDESP3|N|15|2|Tot. Desp. 3|Total Despesa Moeda 3
FLF|37|FLF_TVLRE1|N|15|2|Tot.Reemb.1|Total Reembolsavel Moeda1
FLF|38|FLF_TVLRE2|N|15|2|Tot.Reemb. 2|Total Reembolsável Moeda2
FLF|39|FLF_TVLRE3|N|15|2|Tot.Reemb. 3|Total Reembolsavel Moeda3
FLF|40|FLF_TDESC1|N|15|2|Tot. Desco 1|Total Desconto Moeda 1
FLF|41|FLF_TDESC2|N|15|2|Tot. Desco 2|Total Desconto Moeda 2
FLF|42|FLF_STATMX|C|1|0|Fecham.Moeda|Fecham. Moeda Estrangeira
FLF|43|FLF_TDESC3|N|15|2|Tot. Desco 3|Total Desconto Moeda 3
FLF|44|FLF_TADIA1|N|15|2|Tot. Adia.M1|Total de Adiantam. Moeda1
FLF|45|FLF_TADIA2|N|15|2|Tot. Adia M2|Total de Adiantam. Moeda2
FLF|46|FLF_TADIA3|N|15|2|Tot. Adia M3|Total de Adiantam. Moeda3
FLF|47|FLF_DTBAIX|D|8|0|Dt Baixa|Data da baixa do titulo
FLF|48|FLF_ABONO|C|1|0|Abono|Titulo Abono
FLF|49|FLF_ITECTA|C|9|0|Item Contab.|Item Contabil
FLF|50|FLF_DSITCT|C|50|0|Descrição|Descrição
FLF|51|FLF_CLVL|C|9|0|Classe Valor|Classe de Valor
FLF|52|FLF_DSCLVL|C|50|0|Descrição|Descrição
FLF|53|FLF_TXTUR2|N|6|2|Dólar Turis.|Cotação Dólar
FLF|54|FLF_TXTUR3|N|6|2|Euro Turismo|Cotação Euro Turismo
FLF|55|FLF_WFKID|C|100|0|Workflow ID|ID do Workflow
FLF|56|FLF_MOTVFL|C|80|0|Motivo Rej.|Motivo da Rejeição
FLF|57|FLF_SERIE|C|3|0|Serie|Serie da Nota Fiscal
FLF|58|FLF_DOC|C|9|0|Documento|Número do Documento
FLF|59|FLF_LA|C|1|0|LA|Marca de Contabilização
--- ### FLG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLG|01|FLG_FILIAL|C|6|0|Filial|Filial do Sistema
FLG|02|FLG_CODIGO|C|6|0|Codigo Desp|Codigo da Despesa
FLG|03|FLG_DESCRI|C|40|0|Descricao|Descricao Tipo de Despesa
FLG|04|FLG_LIMITE|C|1|0|Tipo Limite|Tipo Limite da Despesa
FLG|05|FLG_GRUPO|C|6|0|Grupo|Codigo do Grupo de Despes
FLG|06|FLG_CONTA|C|20|0|Conta Contab|Codigo da Conta Contabil
FLG|07|FLG_CUSTO|C|9|0|C.Custo|Centro de Custo
FLG|08|FLG_ITECTB|C|9|0|Item Contab.|Item Contabil
FLG|09|FLG_CLVL|C|9|0|Classe Valor|Classe de Valor
--- ### FLH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLH|01|FLH_FILIAL|C|6|0|Filial|Filial do Sistema
FLH|02|FLH_VIAGEM|C|10|0|Viagem|Solicitacao da viagem
FLH|03|FLH_ITEM|C|2|0|Item|Item da reserva
FLH|04|FLH_CC|C|9|0|Centro Custo|Cod. Centro de Custo
FLH|05|FLH_PORCEN|N|6|2|Porcentagem|Porcentagem de rateio
FLH|06|FLH_CLVL|C|9|0|Classe Valor|Classe de Valor
FLH|07|FLH_DSCLVL|C|50|0|Descrição|Descrição
FLH|08|FLH_ITECTA|C|9|0|Item Contab.|Item Contábil
FLH|09|FLH_DSITCT|C|50|0|Descrição|Descrição
--- ### FLI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLI|01|FLI_FILIAL|C|6|0|Filial|Filial do Sistema
FLI|02|FLI_GRUPO|C|6|0|Grupo|Grupo de Acesso
FLI|03|FLI_DESCRI|C|40|0|Descricao|Descricao do Grupo
FLI|04|FLI_RESPON|C|6|0|Responsavel|Codigo do Responsavel
FLI|05|FLI_NOME|C|50|0|Nome|Nome do Responsavel
--- ### FLJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLJ|01|FLJ_FILIAL|C|6|0|Filial|Filial do Sistema
FLJ|02|FLJ_VIAGEM|C|10|0|Viagem|Codigo da Viagem
FLJ|03|FLJ_ITEM|C|2|0|Pedido|Pedido da Viagem
FLJ|04|FLJ_SUBITM|C|2|0|Sequencia|Sequencia da Aprovação
FLJ|05|FLJ_PARTIC|C|6|0|Cód. Aprov.|Código do Aprovador
FLJ|06|FLJ_NOME|C|50|0|Aprovador|Nome do Aprovador
FLJ|07|FLJ_EMAIL|C|200|0|Email|Email do aprovador
--- ### FLK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLK|01|FLK_FILIAL|C|6|0|Filial|Filial do sistema
FLK|02|FLK_GRUPO|C|6|0|Grupo|Grupo de despesas
FLK|03|FLK_DESCRI|C|40|0|Descricao|Descricao do Grupo
FLK|04|FLK_LIMITE|C|1|0|Tipo Limite|Tipo do Limite da Despesa
--- ### FLL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLL|01|FLL_FILIAL|C|6|0|Filial|Filial do Sistema
FLL|02|FLL_GRUPO|C|6|0|Grupo|Codigo do Grupo de Acesso
FLL|03|FLL_PARTIC|C|6|0|Participante|Codigo do Participante
FLL|04|FLL_NOME|C|50|0|Nome|Nome do Participante
--- ### FLM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLM|01|FLM_FILIAL|C|6|0|Filial|Filial do Sistema
FLM|02|FLM_VIAGEM|C|10|0|Cod. Viagem|Código da Viagem
FLM|03|FLM_PARTIC|C|6|0|Participante|Código do Participante
FLM|04|FLM_ADIANT|C|2|0|Adiantamento|Código do Adiantamento
FLM|05|FLM_SEQ|C|1|0|Seq.|Sequência de Liberação
FLM|06|FLM_APROV|C|6|0|Cód. Aprov.|Código do Aprovador
FLM|07|FLM_NOMEAP|C|50|0|Aprovador|Nome do Aprovador
FLM|08|FLM_STATUS|C|1|0|Status|Status da Liberação
FLM|09|FLM_DTLIB|D|8|0|Dt.Liberação|Dt. da Liberação
FLM|10|FLM_TIPO|C|1|0|Tipo|Tipo da liberação
--- ### FLN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLN|01|FLN_FILIAL|C|6|0|Filial|Filial do Sistema
FLN|02|FLN_TIPO|C|1|0|Tipo|Tipo da Prestação
FLN|03|FLN_PRESTA|C|10|0|Prest.Contas|Prestação de Contas
FLN|04|FLN_PARTIC|C|6|0|Participante|Código do Participante
FLN|05|FLN_SEQ|C|1|0|Seq.|Sequencia de Aprovação
FLN|06|FLN_TPAPR|C|1|0|Tp. Aprov.|Tipo da Aprovação
FLN|07|FLN_APROV|C|6|0|Cód. Aprov.|Código do Aprovador
FLN|08|FLN_NOMEAP|C|50|0|Aprovador|Nome do Aprovador
FLN|09|FLN_STATUS|C|1|0|Status|Status da aprovação
FLN|10|FLN_DTAPRO|D|8|0|Avaliado em|Data da Avaliação
FLN|11|FLN_MOTREJ|C|80|0|Motivo Rej.|Motivo da rejeição
--- ### FLO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLO|01|FLO_FILIAL|C|6|0|Filial|Filial do Sistema
FLO|02|FLO_CODIGO|C|12|0|Cód. do Hist|Código do Histórico
FLO|03|FLO_LICENC|C|20|0|Licenciado|Licenciado Reserve
FLO|04|FLO_IDPED|C|8|0|ID Pedido|ID do Pedido no Reserve
FLO|05|FLO_HISTOR|C|200|0|Histórico|Histórico para o pedido
--- ### FLP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLP|01|FLP_FILIAL|C|6|0|Filial|Filial do Sistema
FLP|02|FLP_CCUSTO|C|9|0|C. Custo|Cod. C. Custo
FLP|03|FLP_CODAPR|C|6|0|Cod. Aprov.|Cod. Aprovador
FLP|04|FLP_NOMAPR|C|50|0|Nome|Nome Aprov.
--- ### FLQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLQ|01|FLQ_FILIAL|C|6|0|Filial|Filial do Sistema
FLQ|02|FLQ_CONFER|C|10|0|Conferencia|Codigo da Conferencia
FLQ|03|FLQ_FORNEC|C|6|0|Fornecedor|Codigo Fornecedor
FLQ|04|FLQ_LOJA|C|2|0|Loja|Loja do Fornecedor
FLQ|05|FLQ_NOMEFO|C|80|0|Nome Fornec.|Nome do Fornecedor
FLQ|06|FLQ_TOTAL|N|14|2|Valor Total|Valor Total Conferência
FLQ|07|FLQ_DATA|D|8|0|Data Confer.|Data da Conferencia
FLQ|08|FLQ_HISTOR|C|80|0|Historico|Historico da Conferencia
FLQ|09|FLQ_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FLQ|10|FLQ_NUMTIT|C|9|0|No. Titulo|Numero do Titulo
FLQ|11|FLQ_PARC|C|3|0|Parcela|Parcela do Titulo
FLQ|12|FLQ_STATUS|C|1|0|Status|Status do Conferencia
FLQ|13|FLQ_VENCTO|D|8|0|Vencimento|Vencimento Previsto
FLQ|14|FLQ_PEDIDO|C|6|0|Ped. Compra|Pedido de Compra
FLQ|15|FLQ_TPPGTO|C|1|0|Tipo Pagto.|Tipo de Pagamento
FLQ|16|FLQ_NATUR|C|10|0|Natureza|Natureza financeira
FLQ|17|FLQ_TIPO|C|3|0|Tipo|Tipo do titulo
FLQ|18|FLQ_COND|C|3|0|Cond. Pagto.|Código condição de pagto.
FLQ|19|FLQ_ORIGEM|C|8|0|Origem|Rotina de Origem
FLQ|20|FLQ_DNATUR|C|30|0|Desc Natur|Descricao da Natureza
FLQ|21|FLQ_DCPAG|C|15|0|Desc.Cond.Pg|Descricao da Cond.Pagto.
--- ### FLR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLR|01|FLR_FILIAL|C|6|0|FIlial|Filial do Sistema
FLR|02|FLR_CONFER|C|10|0|Conferencia|Codigo da Conferencia
FLR|03|FLR_VIAGEM|C|10|0|Cod. Viagem|Codigo da Viagem
FLR|04|FLR_ITEMVI|C|2|0|Item Viagem|Código Item Viagem
FLR|05|FLR_PARTIC|C|6|0|Participante|Código Participante
FLR|06|FLR_VALOR|N|14|2|Valor|Valor Informado
FLR|07|FLR_DESCRI|C|80|0|Descricao|Descrição da Despesa
--- ### FLS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLS|01|FLS_FILIAL|C|6|0|Filial|Filial do Sistema
FLS|02|FLS_CODIGO|C|6|0|Codigo Desp.|Codigo da Despesa
FLS|03|FLS_DTINI|D|8|0|Data Inicio|Data inicio Vigencia
FLS|04|FLS_DTFIM|D|8|0|Data Final|Data Final da Vigencia
FLS|05|FLS_VALUNI|N|14|2|Val. Unit.|Valor Unitário
FLS|06|FLS_LIMITS|N|14|2|Lim.Sem Pern|Limite sem Pernoite
FLS|07|FLS_LIMITP|N|14|2|Limite Perno|Limite com Pernoite
FLS|08|FLS_LIMM02|N|14|2|Lim. Moeda 2|Limite Moeda 02
FLS|09|FLS_LIMM03|N|14|2|Lim. Moeda 3|Limite Moeda 03
--- ### FLT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLT|01|FLT_FILIAL|C|6|0|Filial|Filial do Sistema
FLT|02|FLT_CODIGO|C|6|0|Codigo Desp.|Codigo da Despesa
FLT|03|FLT_DTINI|D|8|0|Data Inicio|Data Inicio Vigencia
FLT|04|FLT_DTFIM|D|8|0|Data Final|Data Final da Vigencia
FLT|05|FLT_LIMITS|N|14|2|Lim.Sem Pern|Limite sem Pernoite
FLT|06|FLT_LIMITP|N|14|2|Limite Perno|Limite com Pernoite
FLT|07|FLT_LIMM02|N|14|2|Lim. Moeda 2|Limite Despesa Moeda 02
FLT|08|FLT_LIMM03|N|14|2|Lim. Moeda 3|Limite Despesa Moeda 03
--- ### FLU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLU|01|FLU_FILIAL|C|6|0|Filial|Filial do Sistema
FLU|02|FLU_VIAGEM|C|10|0|Viagem|Solicitacao da Viagem
FLU|03|FLU_ITEM|C|2|0|Item|Item da Viagem
FLU|04|FLU_PARTIC|C|6|0|Cod.Partic.|Cod. Participante
FLU|05|FLU_IDRESE|C|9|0|Id Reserve|Id Passageiro Reserve
FLU|06|FLU_NOME|C|50|0|Participante|Nome do Passageiro
FLU|07|FLU_BILHET|C|20|0|Bilhete|Bilhete do Passageiro
FLU|08|FLU_VCONFE|N|14|2|Valor Confer|Valor Conferido
FLU|09|FLU_VINFOR|N|14|2|Valor Inform|Valor informado
--- ### FLV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLV|01|FLV_FILIAL|C|6|0|Filial|Filial do Sistema
FLV|02|FLV_CONFER|C|10|0|Conf.Serviço|Conferência do serviço
FLV|03|FLV_VIAGEM|C|10|0|Viagem|Viagem do pedido
FLV|04|FLV_ITEM|C|2|0|Item|Item do pedido
FLV|05|FLV_VALOR|N|16|2|Valor|Valor conferido
FLV|06|FLV_STATUS|C|1|0|Status|Status do registro
--- ### FLW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLW|01|FLW_FILIAL|C|6|0|Filial|Filial do sistema
FLW|02|FLW_CODIGO|C|10|0|Codigo|Codigo da comparação
FLW|03|FLW_DATA|D|8|0|Data|Data de gravação
FLW|04|FLW_ENTRAD|N|16|2|Entrada|Valor das entradas
FLW|05|FLW_SAIDA|N|16|2|Saida|Valor das Saidas
--- ### FLX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLX|01|FLX_FILIAL|C|6|0|Filial|Filial do Sistema
FLX|02|FLX_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
FLX|03|FLX_LOJA|C|2|0|Loja|Loja do Fornecedor
FLX|04|FLX_NOME|C|80|0|Nome|Nome Fornecedor
FLX|05|FLX_ITEM|C|6|0|Item|Item
FLX|06|FLX_DTINI|D|8|0|Dt Inicial|Data Inicial
FLX|07|FLX_DTFIM|D|8|0|Dt Final|Data Final
FLX|08|FLX_ENTIDA|C|20|0|Entidade|Entidade Tomadora
FLX|09|FLX_TIPO|C|1|0|TP Pessoa|Tipo de Pessoa
FLX|10|FLX_CNPJ|C|14|0|CNPJ/CPF|CNPJ/CPF
FLX|11|FLX_BASE|N|16|2|Valor Base|Base de Retençao
FLX|12|FLX_INSS|N|16|2|INSS|Valor do INSS
FLX|13|FLX_CATEFD|C|3|0|Cat eSocial|Categoria Trab. eSocial
FLX|14|FLX_TPREC|C|1|0|Tp Recolhim.|Tipo de Recolhimento
--- ### FLY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLY|01|FLY_FILIAL|C|6|0|Filial|Filial
FLY|02|FLY_SERRPS|C|3|0|Série do RPS|Série do RPS
FLY|03|FLY_NUMRPS|C|20|0|Num. do RPS|Número do RPS
FLY|04|FLY_NUMFAT|C|9|0|Num. NFe|Número da nota fiscal
FLY|05|FLY_TRANSM|C|1|0|Transmitido|Transmitido
--- ### FLZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FLZ|01|FLZ_CODIGO|C|10|0|Codigo|Codigo do Fluxo
FLZ|02|FLZ_CODUSR|C|6|0|Cod.Usuario|Codigo do Usuario
FLZ|03|FLZ_DATA|D|8|0|Data|Data de Gravação
FLZ|04|FLZ_FILIAL|C|6|0|Filial|Filial do sistema
FLZ|05|FLZ_HORA|C|5|0|Hora|Hora de Gravação
FLZ|06|FLZ_NOMUSR|C|30|0|Nome Usuario|Nome do Usuario
FLZ|07|FLZ_PERIOD|N|2|0|Periodicidad|Periodicidade
FLZ|08|FLZ_QTDPER|N|4|0|Qtd.Periudo|Quantidade de Periudos
--- ### FO0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO0|01|FO0_FILIAL|C|6|0|Filial|Filial do sistema
FO0|02|FO0_PROCES|C|15|0|Processo|Processo de Simulação
FO0|03|FO0_VERSAO|C|4|0|Versao|Versão da Simulação
FO0|04|FO0_NUMLIQ|C|6|0|Liquidação|Número da Liquidação
FO0|05|FO0_DATA|D|8|0|Data|Data da Negociação
FO0|06|FO0_DTVALI|D|8|0|Validade|Data Validade
FO0|07|FO0_COND|C|3|0|Cond. Pgto.|Condição de Pagamento
FO0|08|FO0_TXJUR|N|5|2|Tx. Juros|Taxa de Juros
FO0|09|FO0_TXMUL|N|5|2|Tx. Multa|Taxa de Multa
FO0|10|FO0_TXJRG|N|5|2|Tx.Jur.Ger.|Taxa de Juros na Geração
FO0|11|FO0_CLIENT|C|6|0|Cliente|Código do Cliente
FO0|12|FO0_LOJA|C|2|0|Loja|Loja de Cliente
FO0|13|FO0_NATURE|C|10|0|Natureza|Natureza do Títulos
FO0|14|FO0_STATUS|C|1|0|Status|Status da Simulação
FO0|15|FO0_MOEDA|N|2|0|Moeda|Moeda Liquidação
FO0|16|FO0_BKPSTT|C|1|0|Bkp Status|Status Anterior
FO0|17|FO0_ORIGEM|C|8|0|Origem|Origem da Simulação
FO0|18|FO0_CODLIG|C|6|0|Atendimento|Número do atendimento
FO0|19|FO0_TIPO|C|3|0|Tipo|Tipo de Título
FO0|20|FO0_TXMOED|N|11|4|Tx Moeda|Taxa da Moeda
FO0|21|FO0_CALJUR|N|5|2|Juros Futuro|Calculo Juros Futuro
--- ### FO1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO1|01|FO1_FILIAL|C|6|0|Filial|Filial do Sistema
FO1|02|FO1_PROCES|C|15|0|Processo|Processo de Simulação
FO1|03|FO1_VERSAO|C|4|0|Versão|Versão da Simulação
FO1|04|FO1_IDDOC|C|32|0|Id Título|Identificação do Título
FO1|05|FO1_SALDO|N|16|2|Vl Original|Valor Original
FO1|06|FO1_TXJUR|N|5|2|Tx. Juros|Taxa de Juros
FO1|07|FO1_VLJUR|N|12|2|Valor Juros|Valor de Juros
FO1|08|FO1_TXMUL|N|5|2|Tx. Multa|Taxa de Multa
FO1|09|FO1_VLMUL|N|12|2|Val. Multa|Valor da Multa
FO1|10|FO1_DESCON|N|12|2|Val.Desconto|Valor de Desconto
FO1|11|FO1_ACRESC|N|12|2|Acréscimo|Acréscimo
FO1|12|FO1_DECRES|N|12|2|Decréscimo|Decréscimo
FO1|13|FO1_VLABT|N|12|2|Abatimento|Abatimento
FO1|14|FO1_VACESS|N|12|2|Vlr.Acess.|Valor Acessório
FO1|15|FO1_TOTAL|N|12|2|Total Neg.|Total Negociado
FO1|16|FO1_MOEDA|N|2|0|Moeda|Moeda do título
FO1|17|FO1_TXMOED|N|11|4|Tx Moeda|Taxa Moeda
FO1|18|FO1_FILORI|C|6|0|Fil Origem|Filial de Origem
FO1|19|FO1_VLDIA|N|12|2|Taxa Perman.|Taxa Permanencia diaria.
FO1|20|FO1_DESJUR|N|14|2|Desc.Juros|Desconto sobre Juros
FO1|21|FO1_VLADIC|N|12|2|Vlr.Adic.Neg|Valor Adicional Negociado
--- ### FO2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO2|01|FO2_FILIAL|C|6|0|Filial|Filial do Sistema
FO2|02|FO2_PROCES|C|15|0|Processo|Processo de Simulação
FO2|03|FO2_VERSAO|C|4|0|Versão|Versão da Simulação
FO2|04|FO2_IDSIM|C|32|0|Id Título|Identificação do Título
FO2|05|FO2_PREFIX|C|3|0|Prefixo|Prefixo do Título
FO2|06|FO2_NUM|C|9|0|Número|Número do Título
FO2|07|FO2_PARCEL|C|3|0|Parcela|Parcela do Título
FO2|08|FO2_VENCTO|D|8|0|Vencimento|Data de Vencimento
FO2|09|FO2_VALOR|N|16|2|Val. Parcela|Valor da Parcela
FO2|10|FO2_TXJUR|N|5|2|Tx. Juros|Taxa de Juros
FO2|11|FO2_VLJUR|N|12|2|Valor Juros|Valor de Juros
FO2|12|FO2_TXCALC|N|5|2|Tx Jrs Futur|Taxa de Juros Futuro
FO2|13|FO2_VLRJUR|N|16|2|Vlr Jrs Futu|Valor do Juros Futuro
FO2|14|FO2_ACRESC|N|12|2|Acréscimo|Acréscimo
FO2|15|FO2_DECRES|N|12|2|Decréscimo|Decréscimo
FO2|16|FO2_TOTAL|N|16|2|Total Neg.|Total Negociado
FO2|17|FO2_BANCO|C|3|0|Banco|Código do Banco
FO2|18|FO2_AGENCI|C|5|0|Agencia|Agencia do Banco
FO2|19|FO2_CONTA|C|10|0|Conta Banco|Conta corrente no cheque
FO2|20|FO2_NUMCH|C|15|0|Cheque|Número do Cheque
FO2|21|FO2_EMITEN|C|40|0|Emitente|Emitente do Cheque
FO2|22|FO2_TIPO|C|3|0|Tp Titulo|Tipo de titulo
--- ### FO3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO3|01|FO3_FILIAL|C|6|0|Filial|Filial do Sistema
FO3|02|FO3_DATA|D|8|0|Dt do Índice|Data do Índice
FO3|03|FO3_IDXCPA|N|7|4|Tx CP Antiga|Taxa da poupança antiga
FO3|04|FO3_IDXCPN|N|7|4|Tx CP Nova|Taxa da poupança nova
FO3|05|FO3_IDXSLM|N|5|2|Meta Selic|Tx.da Meta Selic na data
FO3|06|FO3_IDXSLC|N|5|2|Selic|Taxa da Selic na data
FO3|07|FO3_IDXTR|N|7|4|Taxa da TR|Taxa da TR na data
FO3|08|FO3_PERC|N|5|1|% da M Selic|Percentual da Meta Selic
FO3|09|FO3_CDI|N|5|2|Tx. CDI|Taxa do CDI na data
FO3|10|FO3_PERCDI|N|6|2|% do CDI|Percentual do CDI
--- ### FO4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO4|01|FO4_FILIAL|C|6|0|Filial|Filial do Sistema
FO4|02|FO4_CODIGO|C|6|0|Código|Código
FO4|03|FO4_ITEM|C|2|0|Item|Item
FO4|04|FO4_NRCART|C|15|0|Num.Cartão|Número do Cartão
FO4|05|FO4_IDRESE|C|10|0|ID Reserve|Identificador Reserve
FO4|06|FO4_VALOR|N|16|2|Valor Total|Valor total
FO4|07|FO4_VCONFE|N|16|2|Vlr. Confer.|Valor Conferido
FO4|08|FO4_VINFOR|N|16|2|Vlr. Infor.|Valor Informado
--- ### FO6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO6|01|FO6_FILIAL|C|6|0|Filial|Filial do Sistema
FO6|02|FO6_CODIGO|C|12|0|Cod. Reg.|Código do Registro
FO6|03|FO6_IDRESE|C|10|0|ID Reserve|ID do site Reserve
FO6|04|FO6_ACAO|C|1|0|Ação Ped.|Ação do Pedido
FO6|05|FO6_TIPO|C|1|0|Tipo Reserva|Tipo da Reserva
FO6|06|FO6_CC|C|9|0|Centro Custo|Centro de Custo
FO6|07|FO6_TOTAL|N|15|2|Total|Valor total da reserva
FO6|08|FO6_TOTFEE|N|15|2|Total Fee|Valor total Fee
FO6|09|FO6_MOTIVO|C|25|0|Motivo|Motivo da viagem
FO6|10|FO6_CLIENT|C|6|0|Cliente|Código do cliente destino
FO6|11|FO6_LOJA|C|2|0|Loja|Loja do Cliente
FO6|12|FO6_ATIVI|C|40|0|Atividade|Atividade
FO6|13|FO6_EXTRA1|C|25|0|Adiantamento|Adiantamento
FO6|14|FO6_EXTRA2|C|25|0|Cpo Extra2|Campo Extra 2
FO6|15|FO6_EXTRA3|C|40|0|Cpo Extra3|Campo Extra 3
FO6|16|FO6_DTCRIA|D|8|0|Data Criação|Data de criação
FO6|17|FO6_DTCANC|D|8|0|Data Canc.|Data de canc. do pedido
FO6|18|FO6_DTEMIS|D|8|0|Data Emissão|Data Emissão da Reserva
FO6|19|FO6_DTAUTO|D|8|0|Data de Aut.|Data de aut. do ped.
FO6|20|FO6_DTMIGR|D|8|0|Dt. Migração|Data de migração do ped.
FO6|21|FO6_DTRESE|D|8|0|Data Reserva|Data da Reserva
FO6|22|FO6_DTCIAC|D|8|0|Checkin Acom|Data checkin acomodação
FO6|23|FO6_DTCOAC|D|8|0|Checkout Ac.|Data checkout acomodação
FO6|24|FO6_DTIVSE|D|8|0|Data Ini Seg|Data inicial do seguro
FO6|25|FO6_DTFVSE|D|8|0|Data Fim Seg|Data final do seguro
FO6|26|FO6_DTRELC|D|8|0|Dt Ret Veic|Data de ret. do veiculo
FO6|27|FO6_DTDELC|D|8|0|Dt Dev Veic|Data de dev. do veiculo
FO6|28|FO6_DTSAPR|D|8|0|Dt Saída Rod|Data de saída rodoviário
FO6|29|FO6_DTCHPR|D|8|0|Dt Cheg Rod|Dt de chegada rodoviário
FO6|30|FO6_DTSAPA|D|8|0|Dt Saída Voo|Data de saída do voo
FO6|31|FO6_DTCHPA|D|8|0|Dt Cheg Voo|Data de chegada do voo
--- ### FO7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO7|01|FO7_FILIAL|C|6|0|Filial|Filial do Sistema
FO7|02|FO7_CODIGO|C|10|0|Código|Código Identificador
FO7|03|FO7_PREFIX|C|3|0|Prefixo|Prefixo do título
FO7|04|FO7_TITULO|C|9|0|Título|Título Financeiro
FO7|05|FO7_PARCEL|C|3|0|Parcela|Parcela
FO7|06|FO7_TIPO|C|3|0|Tipo|Tipo
FO7|07|FO7_CLIFOR|C|6|0|Cliente/Forn|Cliente/Fornecedor
FO7|08|FO7_LOJA|C|2|0|Loja|Loja
FO7|09|FO7_NOME|C|50|0|Nome|Nome
FO7|10|FO7_DTBAIX|D|8|0|Dt.Baixa|Data Baixa
FO7|11|FO7_PRESTA|C|10|0|Prest.Contas|Prestação de Contas
FO7|12|FO7_RECPAG|C|1|0|RecPag|Recebimento/Pagamento
FO7|13|FO7_TPVIAG|C|1|0|Tipo Viagem|Tipo de Viagem
FO7|14|FO7_PARTIC|C|6|0|Cod. Partic.|Código do Participante
--- ### FO8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO8|01|FO8_FILIAL|C|6|0|Filial|Filial do Sistema
FO8|02|FO8_NUM|C|9|0|Num. Fatura|Número da Fatura
FO8|03|FO8_DATA|D|8|0|Data|Data da Fatura
FO8|04|FO8_CLI|C|6|0|Cod. Cliente|Código do Cliente.
FO8|05|FO8_LOJA|C|2|0|Loja|Loja do Cliente.
FO8|06|FO8_NCLI|C|80|0|Desc.Cliente|Descrição do Cliente.
FO8|07|FO8_VALOR|N|16|2|Valor|Valor da Fatura.
FO8|08|FO8_STATUS|C|1|0|Status|Status Fatura.
--- ### FO9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FO9|01|FO9_FILIAL|C|6|0|Filial|Filial do Sistema
FO9|02|FO9_NUMFAT|C|9|0|Num. Fatura|Número da Fatura
FO9|03|FO9_CLIFAT|C|6|0|Cod. Cliente|Código do Cliente.
FO9|04|FO9_LOJFAT|C|2|0|Loja|Loja do Cliente.
FO9|05|FO9_ITEM|C|4|0|Item|Item da Fatura
FO9|06|FO9_SERIE|C|3|0|Série|Série da nota
FO9|07|FO9_NUMDOC|C|9|0|Num. Doc.|Número da nota
FO9|08|FO9_DATA|D|8|0|Data Emissão|Data de Emissão.
FO9|09|FO9_VALOR|N|16|2|Valor|Valor da nota.
FO9|10|FO9_ESPECI|C|5|0|Especie Doc.|Espécie do Documento
--- ### FOA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOA|01|FOA_FILIAL|C|6|0|Filial|Filial do Sistema
FOA|02|FOA_NUMFAT|C|9|0|Num. Fatura|Número da Fatura
FOA|03|FOA_CLIFAT|C|6|0|Cod. Cliente|Código do Cliente.
FOA|04|FOA_LOJFAT|C|2|0|Loja|Loja do Cliente.
FOA|05|FOA_ITEM|C|4|0|Item|Item
FOA|06|FOA_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FOA|07|FOA_NUM|C|9|0|Numero|Numero do Titulo
FOA|08|FOA_PARCEL|C|3|0|Parcela|Parcela do Título
FOA|09|FOA_TIPO|C|3|0|Tipo|Tipo do titulo
FOA|10|FOA_VALOR|N|16|2|Vlr titulo|Valor do título
FOA|11|FOA_SALDO|N|16|2|Saldo|Saldo do Titulo
FOA|12|FOA_EMISS|D|8|0|Emissao|Emissao
FOA|13|FOA_VENCTO|D|8|0|Vencimento|Vencimento
FOA|14|FOA_VENCRE|D|8|0|Venc Real|Vencimento Real
FOA|15|FOA_TITFIL|C|6|0|Filial Ori|Filial de Origem
--- ### FOB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOB|01|FOB_FILIAL|C|6|0|Filial|Filial do Sistema
FOB|02|FOB_NUMFAT|C|9|0|Num. Fatura|Número da Fatura
FOB|03|FOB_CLIFAT|C|6|0|Cod. Cliente|Código do Cliente.
FOB|04|FOB_LOJFAT|C|2|0|Loja|Loja do Cliente.
FOB|05|FOB_ITEM|C|4|0|Item|Item
FOB|06|FOB_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FOB|07|FOB_NUM|C|9|0|Numero|Numero do Titulo
FOB|08|FOB_PARCEL|C|3|0|Parcela|Parcela do Título
FOB|09|FOB_TIPO|C|3|0|Tipo|Tipo do titulo
FOB|10|FOB_VALOR|N|16|2|Vlr titulo|Valor do título
FOB|11|FOB_SALDO|N|16|2|Saldo|Saldo do Titulo
FOB|12|FOB_EMISS|D|8|0|Emissao|Emissao
FOB|13|FOB_VENCTO|D|8|0|Vencimento|Vencimento
FOB|14|FOB_VENCRE|D|8|0|Venc Real|Vencimento Real
FOB|15|FOB_TITFIL|C|6|0|Filial Ori|Filial de Origem
FOB|16|FOB_FORCOM|C|6|0|Forne Comiss|Fornecedor Comissão
FOB|17|FOB_LOJCOM|C|2|0|Loja Comiss|Loja Comissão
--- ### FOC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOC|01|FOC_FILIAL|C|6|0|Filial|Filial do Sistema
FOC|02|FOC_NUMFAT|C|9|0|Num. Fatura|Número da Fatura
FOC|03|FOC_CLIFAT|C|6|0|Cod. Cliente|Código do Cliente.
FOC|04|FOC_LOJFAT|C|2|0|Loja|Loja do Cliente
FOC|05|FOC_ITEM|C|4|0|Item|Item da Fatura
FOC|06|FOC_SERIE|C|3|0|Série|Série da Nota
FOC|07|FOC_NUMDOC|C|9|0|Num. Doc.|Número da nota
FOC|08|FOC_DATA|D|8|0|Data Emissão|Data de Emissão
--- ### FOD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOD|01|FOD_FILIAL|C|6|0|Filial|Filial do sistema
FOD|02|FOD_FILCEN|C|6|0|Fil Central.|Filial centralizadora SCP
FOD|03|FOD_FILSCP|C|6|0|Filial SCP|Filial principal SCP
FOD|04|FOD_FILSOC|C|6|0|Filial Sócio|Filial sócio da SCP
FOD|05|FOD_NOME|C|60|0|Nome|Nome do socio(a)
FOD|06|FOD_CGCCPF|C|14|0|CPF ou CNPJ|Numero do CPF ou CNPJ
FOD|07|FOD_PERCEN|N|5|2|% Particip.|Percentual participacao
FOD|08|FOD_TIPOPE|C|1|0|Tipo Pessoa|Tipo Pessoa fisica ou jur
FOD|09|FOD_CGCSCP|C|14|0|CNPJ SCP|CNPJ da SCP
FOD|10|FOD_INIVIG|C|7|0|Ini Vigência|Data inicio de Vigência
FOD|11|FOD_FIMVIG|C|7|0|Fim Vigência|Data final de vigencia
--- ### FOE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOE|01|FOE_FILIAL|C|6|0|Filial|Filial do Sistema
FOE|02|FOE_FILCEN|C|6|0|FIL CENTR.|FILIAL CENTRALIZADORA SCP
FOE|03|FOE_FILSCP|C|6|0|FILIAL SCP|FILIAL PRINCIPAL SCP
FOE|04|FOE_FILSOC|C|6|0|FILIAL SOCIO|FILIAL SOCIO DA SCP
FOE|05|FOE_MES|C|2|0|Mes|Mes de Referencia
FOE|06|FOE_ANO|C|4|0|Ano|Ano de Referencia
FOE|07|FOE_VALOR|N|16|2|Valor|Valor do lucro/dividendo
--- ### FOF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOF|01|FOF_FILIAL|C|6|0|Filial|Filial
FOF|02|FOF_CODIGO|C|32|0|Codigo|Codigo
FOF|03|FOF_TITADI|C|32|0|Tit Adian|Titulo de Adiantamento
FOF|04|FOF_TITREC|C|32|0|Tit Comp|Título Para Compensação
FOF|05|FOF_RECPAG|C|1|0|Rec/Pag|Recebimento ou Pagamento
--- ### FOI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOI|01|FOI_FILIAL|C|6|0|Filial|Filial do Sistema
FOI|02|FOI_NATURE|C|10|0|Natureza|Código da Natureza
FOI|03|FOI_CODIGO|C|6|0|Código|Código do imposto
FOI|04|FOI_IDFKK|C|32|0|ID FKK|ID Regra Financeira
--- ### FOJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOJ|01|FOJ_FILIAL|C|6|0|Filial|Filial do sistema
FOJ|02|FOJ_CLIENT|C|6|0|Cliente|Código do cliente
FOJ|03|FOJ_LOJA|C|2|0|Loja|Loja do cliente
FOJ|04|FOJ_CODIGO|C|6|0|Código|Código do Imposto
FOJ|05|FOJ_IDFKK|C|32|0|Regra Financ|ID Regra Financ Impostos
--- ### FOK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOK|01|FOK_FILIAL|C|6|0|Filial|Filial do Sistema
FOK|02|FOK_FORNEC|C|6|0|Fornecedor|Código do Fornecedor
FOK|03|FOK_LOJA|C|2|0|Loja|Loja do Fornecedor
FOK|04|FOK_CODIGO|C|6|0|Código|Código do Imposto
FOK|05|FOK_IDFKK|C|32|0|ID Regra Fin|ID Regra Financeira
--- ### FOL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOL|01|FOL_FILIAL|C|6|0|Filial|Filial do Sistema
FOL|02|FOL_PRODUT|C|15|0|Produto|Código do Produto
FOL|03|FOL_CODIGO|C|6|0|Código|Código do Imposto
--- ### FOM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOM|01|FOM_FILIAL|C|6|0|Filial|Filial
FOM|02|FOM_IDDOC|C|32|0|ID Doc|ID do Documento
FOM|03|FOM_DOCUME|C|9|0|Documento|Numero do Documento
FOM|04|FOM_FORNEC|C|6|0|Fornecedor|Codigo Fornecedor
FOM|05|FOM_LOJA|C|2|0|Loja|Loja do Fornecedor
FOM|06|FOM_RAZAO|C|80|0|Razão Social|Nome ou Razão Social
FOM|07|FOM_CNPJ|C|14|0|CNPJ|CNPJ do Fornecedor
FOM|08|FOM_CODRET|C|4|0|Cod.Reten.|Código de Retenção
FOM|09|FOM_ANO|C|4|0|Ano|Ano Calendário
FOM|10|FOM_FILORI|C|6|0|Filial Orig.|Filial de Origem
--- ### FON
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FON|01|FON_FILIAL|C|6|0|Filial|Filial do Sistema
FON|02|FON_IDDOC|C|32|0|ID Doc|ID do Documento
FON|03|FON_ITEM|C|4|0|Item Doc|Item do Docto Repasse
FON|04|FON_MES|C|2|0|Mês|Mês
FON|05|FON_RNDBRT|N|16|2|Rend. Bruto|Rendimento Bruto
FON|06|FON_BASE|N|16|2|Base Retenc.|Valor base da retenção
FON|07|FON_IMPREC|N|16|2|Vlr. Imposto|Valor Imposto Recolhido
FON|08|FON_DIRF|C|1|0|Dirf Gerada|Dirf Gerada
--- ### FOO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOO|01|FOO_FILIAL|C|6|0|Filial|Filial do Sistema
FOO|02|FOO_IDRET|C|32|0|ID Retenção|Id interno tipo retenção
FOO|03|FOO_CODIGO|C|6|0|Código|Código do Imposto
FOO|04|FOO_TIPIMP|C|1|0|Class.Tp.Imp|Classificação Tp Imposto
--- ### FOP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOP|01|FOP_FILIAL|C|6|0|Filial|Filial do Sistema
FOP|02|FOP_CODIGO|C|6|0|Codigo|Codigo Sequencial
FOP|03|FOP_IDELIN|C|1|0|Identif Linh|Identificação da Linha
FOP|04|FOP_HEADET|C|1|0|Head Detal|Header X Detalhe
FOP|05|FOP_CHALIN|C|1|0|Chave Lin|Chave da Linha
FOP|06|FOP_IDESEG|C|1|0|Identi Segui|Identificação Seguimento
FOP|07|FOP_BANCO|C|3|0|Banco|Banco Arquivo CNAB
FOP|08|FOP_DESSEG|C|30|0|Desc Segment|Descrição Segmento
FOP|09|FOP_POSINI|C|3|0|Pos. Inicial|Posição inicial
FOP|10|FOP_POSFIM|C|3|0|Pos. Final|Posição Final
FOP|11|FOP_DECIMA|C|1|0|Decimal|Campo CTRL Decimal
FOP|12|FOP_DESMOV|C|40|0|Desc.Movimen|Descrição do Movimento
FOP|13|FOP_CONARQ|C|135|0|Cont Arquivo|Conteudo do Arquivo
FOP|14|FOP_VERARQ|C|8|0|Versao Arqui|Versão do Arquivo
FOP|15|FOP_BLOQUE|C|1|0|Bloqueado|Registro Bloqueado
FOP|16|FOP_EDITAD|C|1|0|Editado|Arquivo Editado
FOP|17|FOP_DTGRAV|D|8|0|Data Gravaça|Data da Gravação do Regis
FOP|18|FOP_PAGREC|C|3|0|Pagar Recebe|Contas a Pagar ou Receber
FOP|19|FOP_REMRET|C|3|0|Rem ou Ret|Remessa ou Retorno
FOP|20|FOP_SEQUEN|C|3|0|Sequencia|Sequencia Linhas
FOP|21|FOP_CTREDI|C|1|0|Ctr Edicao|Controle de Edicao
FOP|22|FOP_CTDEDI|C|135|0|Cont. Edicao|Conteudo da Edicao
FOP|23|FOP_NEWVLR|C|135|0|Novo Valor|Novo Valor
--- ### FOQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOQ|01|FOQ_FILIAL|C|6|0|Filial|Filial do Sistema
FOQ|02|FOQ_CODIGO|C|6|0|Codigo|Codigo Sequencial
FOQ|03|FOQ_DATA|D|8|0|Data Lacto|Data do Lançamento
FOQ|04|FOQ_HORA|C|8|0|Hora|Hora da inclusão Sistema
FOQ|05|FOQ_CHVCTR|C|40|0|Chave Ctrl|Chave de Controle
FOQ|06|FOQ_DESBCO|C|10|0|Nome Banco|Nome do Banco
FOQ|07|FOQ_PGRECT|C|3|0|Pag ou Rec|Pagar ou Receber
FOQ|08|FOQ_ENRETT|C|3|0|Rem ou Ret|Remessa ou Retorno
FOQ|09|FOQ_VERTVS|C|8|0|Versão Totvs|Versão Totvs
FOQ|10|FOQ_CTRVAL|C|1|0|Contato Val.|Contrato Ativo na Totvs
FOQ|11|FOQ_CTRVER|C|1|0|Controla Ver|Controla Versão
FOQ|12|FOQ_VERCLI|C|8|0|Versão Clien|Versão Arquivo do Cliente
FOQ|13|FOQ_NOMARQ|C|60|0|Nome Arquivo|Nome do Arquivo CNAB
FOQ|14|FOQ_PGRECC|C|3|0|Pag Rec Clie|Pagar ou Receber Cliente
FOQ|15|FOQ_ENRETC|C|3|0|Rem Ret Clie|Remessa ou Retorno Client
FOQ|16|FOQ_BLOQUE|C|1|0|Bloqueado|Registro Bloqueado
FOQ|17|FOQ_BANCO|C|3|0|Banco|Banco CNAB
--- ### FOS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOS|01|FOS_FILIAL|C|6|0|Filial|Filial do Sistema
FOS|02|FOS_IDRET|C|32|0|ID Retenção|Id interno tipo de ret
FOS|03|FOS_ITEM|C|4|0|Item|Item
FOS|04|FOS_FAIXA|N|16|2|Valor Limite|Valor Limite da faixa
FOS|05|FOS_PERC|N|6|2|Alíquota|Alíquota
FOS|06|FOS_VLRDED|N|16|2|Vlr Dedução|Valor para dedução
FOS|07|FOS_TIPDED|C|1|0|Tipo Ded|Tipo de dedução
--- ### FOT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOT|01|FOT_FILIAL|C|6|0|Filial|Filial do Sistema
FOT|02|FOT_CODIGO|C|6|0|Código|Cód. Regra Cumulatividade
FOT|03|FOT_ITEM|C|4|0|Item|Item da Cumulatividade
FOT|04|FOT_IDRET|C|32|0|Id Retenção|Id Interno do tipo de ret
--- ### FOU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOU|01|FOU_FILIAL|C|6|0|Filial|Filial do sistema
FOU|02|FOU_CODIGO|C|6|0|Código|Cód. Regra Vlr Acessório
FOU|03|FOU_ACAO|C|1|0|Ação|Ação do Valor Acessório
FOU|04|FOU_APLICA|C|1|0|Aplicação|Aplicação Valor Acessório
FOU|05|FOU_IDRET|C|32|0|ID Retenão|ID interno da retenção
--- ### FOV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOV|01|FOV_FILIAL|C|6|0|Filial|Filial do Sistema
FOV|02|FOV_CODIGO|C|6|0|Código|Código Regra Deduções
FOV|03|FOV_PERDED|N|6|2|% Dedução|Porcentual de dedução
FOV|04|FOV_TIPDED|C|1|0|Tipo Dedução|Tipo de Dedução
FOV|05|FOV_IDRET|C|32|0|ID Retenção|Id interno tipo imposto
--- ### FOZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FOZ|01|FOZ_FILIAL|C|6|0|Filial|Filial do Sistema
FOZ|02|FOZ_CODIGO|C|6|0|Codigo|Codigo Sequencial
FOZ|03|FOZ_BANCO|C|3|0|Banco|Banco CNAB
FOZ|04|FOZ_MODULO|C|3|0|Modulo|Modulo CNAB em Uso
FOZ|05|FOZ_TIPO|C|3|0|Tipo CNAB|Tipo Arquivo CNAB
FOZ|06|FOZ_EDITAV|C|1|0|Tab Editada|Tabela Editada
FOZ|07|FOZ_DTGRV|D|8|0|Data Grv|Data da Gravação
FOZ|08|FOZ_USER|C|6|0|User|Codigo do Usuario
FOZ|09|FOZ_BLOQUE|C|1|0|Bloqueado|Registro Bloqueado
--- ### FR0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR0|01|FR0_FILIAL|C|6|0|FILIAL|Filial do Sistema
FR0|02|FR0_TABELA|C|3|0|Tabela|Tabela
FR0|03|FR0_CHAVE|C|6|0|Chave|Chave
FR0|04|FR0_CHVAUX|C|6|0|Chave Aux.|Chave Aux.
FR0|05|FR0_DESC01|C|150|0|Descric M1|Descrição Moeda 01
FR0|06|FR0_DESC02|C|150|0|Descric M2|Descrição moeda 02
FR0|07|FR0_DESC03|C|150|0|Descric M3|Descrição Moeda 03
FR0|08|FR0_DESC04|C|150|0|Descric M4|Descrição Moeda 04
FR0|09|FR0_DESC05|C|150|0|Descric M5|Descrição Moeda 05
FR0|10|FR0_COMPLE|C|60|0|Complemento|Complemento
--- ### FR1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR1|01|FR1_FILIAL|C|6|0|Filial|Filial
FR1|02|FR1_IDMOV|C|10|0|ID. Mov.|Id. Movimento
FR1|03|FR1_SEQMOV|C|2|0|Seq. Mov.|Seq. do movimento
FR1|04|FR1_OCORR|C|3|0|Ocorrência|Ocorrência
FR1|05|FR1_DETOCR|C|3|0|Det. Ocorr.|Detalhe da Ocorrência
FR1|06|FR1_MOEDA|C|2|0|Moeda|Moeda
FR1|07|FR1_STATUS|C|1|0|Status|Status Mov.
FR1|08|FR1_BASE|N|16|2|Base|Valor Base
FR1|09|FR1_PERC|N|5|2|Perc.|Percentual
FR1|10|FR1_PREDC|N|5|2|Redução|Perc. de Redução
FR1|11|FR1_CONCP|C|3|0|Conceito|Id. Conceito
FR1|12|FR1_VLCLC|N|16|2|Vl. Calculad|Valor Calculado
FR1|13|FR1_VLEFT|N|16|2|Vl. Efetivad|Valor Efetivado
FR1|14|FR1_PEFTV|N|6|2|% Efetivado|Perc. Efetivado
FR1|15|FR1_PDEFT|C|1|0|Pendências|Cont. Pendências
FR1|16|FR1_IDEFET|C|10|0|Efetivador|Id. do Efetivador
--- ### FR2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR2|01|FR2_FILIAL|C|6|0|Filial|Filial
FR2|02|FR2_IDMOV|C|10|0|Id. Mov.|Id. Movimento
FR2|03|FR2_SEQMOV|C|2|0|Seq. Mov|Seq. do movimento
FR2|04|FR2_OCORR|C|3|0|Ocorrencia|Ocorrencia
FR2|05|FR2_DETOCR|C|3|0|Det. Ocorr.|Detalhe da Ocorrência
FR2|06|FR2_MOEDA|C|2|0|Moeda|Moeda
FR2|07|FR2_STATUS|C|1|0|Status|Status Mov.
FR2|08|FR2_BASE|N|16|2|Base|Valor Base
FR2|09|FR2_PERC|N|5|2|Perc.|Percentual
FR2|10|FR2_PREDC|N|5|2|Redução|Perc. de Redução
FR2|11|FR2_CONCP|C|3|0|Conceito|Id. Conceito
FR2|12|FR2_VLCLC|N|16|2|Vl. Calc.|Valor Calculado
FR2|13|FR2_VLEFT|N|16|2|Vl. Efetiv.|Valor Efetivado
FR2|14|FR2_PEFTV|N|6|2|% Efetivado|Perc. Efetivado
FR2|15|FR2_PDEFT|C|1|0|Pendências|Cont. Pendências
FR2|16|FR2_IDEFET|C|10|0|Efetivador|Id. Efetivador
FR2|17|FR2_SEQBX|C|2|0|Seq. Baixa|Sequência de Baixa
--- ### FR3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR3|01|FR3_FILIAL|C|6|0|Filial|Filial
FR3|02|FR3_CART|C|1|0|Carteira|Carteira
FR3|03|FR3_PEDIDO|C|6|0|Pedido|Codigo Pedido
FR3|04|FR3_PREFIX|C|3|0|Prefixo|Prefixo Origem
FR3|05|FR3_PARCEL|C|3|0|Parcela|Parcela
FR3|06|FR3_TIPO|C|3|0|Tipo|Tipo do titulo
FR3|07|FR3_CLIENT|C|6|0|Cliente|Cliente
FR3|08|FR3_FORNEC|C|6|0|Fornec.|Fornecedor
FR3|09|FR3_LOJA|C|2|0|Loja|Loja Cli/For
FR3|10|FR3_VALOR|N|16|2|Valor|Valor Relacionado
FR3|11|FR3_DOC|C|9|0|Num. Doc.|Numero do Documento Fisca
FR3|12|FR3_SERIE|C|3|0|Serie Docto.|Serie do Documento Fiscal
FR3|13|FR3_DATAE|D|8|0|Data Emissao|Data Emissao Documento
FR3|14|FR3_ITEM|C|2|0|Item Relac|Item Relacionado
FR3|15|FR3_FILORI|C|6|0|Fil Orig|Filial Origem
FR3|16|FR3_NUM|C|9|0|Num.Tit.|Numero Titulo Adiantament
FR3|17|FR3_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### FR4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR4|01|FR4_FILIAL|C|6|0|Filial|Filial do Sistema
FR4|02|FR4_CODAPU|C|6|0|Codigo|Codigo da Apuração
FR4|03|FR4_DESC|C|40|0|Descricao|Descricao da apuração
FR4|04|FR4_TIPAPU|C|1|0|Tipo|Tipo de apuração
FR4|05|FR4_DTINI|D|8|0|Data Inicial|Data Inicial da apuração
FR4|06|FR4_DTFIM|D|8|0|Data Final|Data Final
FR4|07|FR4_QTMES|N|3|0|Meses Ap|Quantidade de Meses
FR4|08|FR4_TPVAL|C|1|0|Tipo Valor|Tipo Valor
FR4|09|FR4_LIVRES|C|3|0|L Res CTB|Livro Resultado Contábil
FR4|10|FR4_LIVADI|C|3|0|L Adição|Livro Adição
FR4|11|FR4_LIVEXC|C|3|0|L Exclusão|Livro Exclusão
FR4|12|FR4_LIVCOM|C|3|0|L Compensa|Livro Compensação
FR4|13|FR4_LIVDED|C|3|0|L Dedução|Livro de Dedução
FR4|14|FR4_RESCTB|N|16|2|Res CTB|Resultado Contábil
FR4|15|FR4_ADICAO|N|16|2|Adição|Total da aba Adição
FR4|16|FR4_EXCLUS|N|16|2|Exclusao|Total de Exclusão
FR4|17|FR4_BACOMP|N|16|2|Base Ant Com|Base antes compensação
FR4|18|FR4_COMP|N|16|2|Compensação|Total das Compensações
FR4|19|FR4_RECTRI|N|16|2|Res Tribut|Resultado Tributavel
FR4|20|FR4_DEDUC|N|16|2|Deduções|Total das deduções
FR4|21|FR4_IRNORM|N|16|2|IRPJ Normal|IRPJ Normal
FR4|22|FR4_ALINOR|N|6|2|Aliq IR Norm|Aliquota IRPJ Normal
FR4|23|FR4_PISENT|N|16|2|Parc Isenta|Parcela Isenta
FR4|24|FR4_ALIADI|N|6|2|Aliq Adic|Aliquota IRPJ Adicional
FR4|25|FR4_BASADI|N|16|2|Base IR Adic|Base IR Adicional
FR4|26|FR4_IRADIC|N|16|2|IR Adicional|IR Adicional
FR4|27|FR4_IRTOT|N|16|2|IRPJ Total|IRPJ Total
FR4|28|FR4_IRPAG|N|16|2|IRPJ Pagar|IRPJ a pagar
FR4|29|FR4_ALICSL|N|6|2|Aliq CSLL|Aliquota CSLL
FR4|30|FR4_CSLL|N|16|2|CSLL Total|CSLL Total
FR4|31|FR4_CSLP|N|16|2|CSLL Pagar|CSLL a pagar
FR4|32|FR4_PREFIX|C|3|0|Prefixo|Prefixo
FR4|33|FR4_NUM|C|9|0|Numero|Numero do Titulo
FR4|34|FR4_COND|C|5|0|Cond Pag|Condição de Pagamento
FR4|35|FR4_CODRET|C|4|0|Cod Ret|Codigo de Retenção
FR4|36|FR4_STATUS|C|1|0|Status|Status
FR4|37|FR4_EMISSA|D|8|0|Dt Emissao|Data de Emissao
FR4|38|FR4_LA|C|1|0|Ident. Lanc.|Identificador de LA.
FR4|39|FR4_DTVENC|D|8|0|Dt Vcto Apur|Data Vencimento Tit Apura
--- ### FR5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR5|01|FR5_FILIAL|C|6|0|Filial|Filial do sistema
FR5|02|FR5_CODAPU|C|6|0|Codigo|Codigo Apuracao
FR5|03|FR5_TIPO|C|1|0|Tipo|Tipo de Componente
FR5|04|FR5_ITEM|C|4|0|Item|Item Componente
FR5|05|FR5_ENTID|C|20|0|Entid Gerenc|Entidade Gerencial
FR5|06|FR5_DESC|C|40|0|Descrição|Descrição da Entidade
FR5|07|FR5_VALOR|N|16|2|Valor|Valor Entidade
FR5|08|FR5_DC|C|1|0|Deb/Cred|Tipo do valor
FR5|09|FR5_TPREG|C|1|0|Tipo Reg|Tipo do Registro
FR5|10|FR5_TOTVIS|C|1|0|Total Vis|Total da Visão
FR5|11|FR5_USER|C|6|0|Cod Usuario|Codigo do Usuário
FR5|12|FR5_NOMEUS|C|40|0|Nome Usuario|Nome do Usuário
FR5|13|FR5_LA|C|1|0|Ident. Lanc.|Identificador de LA.
FR5|14|FR5_DTALT|D|8|0|Data Alt|Data alteração
--- ### FR6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR6|01|FR6_FILIAL|C|6|0|Filial|Filial do Sistema
FR6|02|FR6_CODAPU|C|6|0|Codigo|Codigo da Apuração
FR6|03|FR6_ITEM|C|4|0|Item|Item
FR6|04|FR6_FILTIT|C|6|0|Fil Titulo|Filial do Título
FR6|05|FR6_PREFIX|C|3|0|Prefixo|Prefixo
FR6|06|FR6_NUM|C|9|0|Num Titulo|Numero do Título
FR6|07|FR6_PARC|C|3|0|Parcela|Parcela do Título
FR6|08|FR6_TIPO|C|3|0|Tipo|Tipo do Título
FR6|09|FR6_FORNEC|C|6|0|Forncedor|Codigo do Fornecedor
FR6|10|FR6_LOJA|C|2|0|Loja|Loja do Fornecedor
FR6|11|FR6_EMISSA|D|8|0|DT Emissao|Data de Emissao do Titulo
FR6|12|FR6_VENCTO|D|8|0|Vencimento|Vencimento do Titulo
FR6|13|FR6_VALOR|N|16|2|Vlr.Titulo|Valor do Titulo
--- ### FR7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR7|01|FR7_FILIAL|C|6|0|Filial|Filial do Sistema
FR7|02|FR7_CODAPU|C|6|0|Codigo|Codigo da Apuração
FR7|03|FR7_ITEM|C|4|0|Item|Item
FR7|04|FR7_GRUEMP|C|2|0|Grupo/Empres|Código do Grupo / Empresa
FR7|05|FR7_GRUDES|C|15|0|Desc Emp|Descrição do Grupo / Emp
FR7|06|FR7_FILTIT|C|6|0|Cod Fil|Filial do Titulo
FR7|07|FR7_CODFIL|C|6|0|Código|Código da Entidade
FR7|08|FR7_FILDES|C|15|0|Desc Filial|Descrição da Filial
FR7|09|FR7_CNPJ|C|14|0|CNPJ|CNPJ da Filial
--- ### FR9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FR9|01|FR9_FILIAL|C|6|0|Filial|Filial do Sistema
FR9|02|FR9_EVENTO|C|2|0|Cod.Evento|Codigo do Evento
FR9|03|FR9_DOCUM|C|3|0|Cod.Document|Codigo do Documento
FR9|04|FR9_DESCRI|C|30|0|Descricao|Descricao do Documento
--- ### FRD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRD|01|FRD_FILIAL|C|6|0|Filial|Filial do Sistema
FRD|02|FRD_PREFIX|C|3|0|Prefixo|Prefixo do Titulo
FRD|03|FRD_NUM|C|9|0|No. Titulo|Numero do Titulo
FRD|04|FRD_PARCEL|C|3|0|Parcela|Parcela do Titulo
FRD|05|FRD_TIPO|C|3|0|Tipo|Tipo do Titulo
FRD|06|FRD_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
FRD|07|FRD_LOJA|C|2|0|Loja|Loja do Fornecedor
FRD|08|FRD_DOCUM|C|3|0|Cod.Document|Codigo do Document
FRD|09|FRD_DESCRI|C|30|0|Descricao|Descricao do Documento
FRD|10|FRD_RECEB|C|1|0|Recebido|Recebido
--- ### FRH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRH|01|FRH_FILIAL|C|6|0|Filial|Filial do Sistema
FRH|02|FRH_PLNPGT|C|10|0|Plano Pgto|Plano de Pagamento
FRH|03|FRH_CODCOL|C|8|0|Coligada|Código de Coligada
FRH|04|FRH_IDPERL|C|4|0|Id Perlet|Id Periodo Letivo
FRH|05|FRH_DESCRI|C|60|0|Descrição|Descrição Plano
FRH|06|FRH_DTINI|D|8|0|Data Inicio|Data Inicio
FRH|07|FRH_DTFIM|D|8|0|Data Final|Data Final
--- ### FRI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRI|01|FRI_FILIAL|C|6|0|Filial|Filial
FRI|02|FRI_CODCOL|C|8|0|Coligada|Código Coligada
FRI|03|FRI_IDPERL|C|4|0|Id Perlet|Id Periodo Letivo
FRI|04|FRI_PLNPGT|C|10|0|Plano Pgto|Cód Plano Pagamento
FRI|05|FRI_PARC|C|3|0|Parcela|Parcela
FRI|06|FRI_VALOR|N|12|2|Valor|Valor Original
FRI|07|FRI_VENORI|D|8|0|Venc. Origin|Vencimento Original
FRI|08|FRI_PERC1|N|6|2|Percentual 1|Percentual Desconto 1
FRI|09|FRI_DATE1|D|8|0|Data Lim 1|Data Limite 1
FRI|10|FRI_PERC2|N|6|2|Percentual 2|Percentual Desconto 2
FRI|11|FRI_DATE2|D|8|0|Data Lim 2|Data Limite 2
FRI|12|FRI_PERC3|N|6|2|Percentual 3|Percentual Desconto 3
FRI|13|FRI_DATE3|D|8|0|Data Lim 3|Data Limite 3
--- ### FRJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRJ|01|FRJ_FILIAL|C|6|0|Filial|Filial
FRJ|02|FRJ_NUMPRO|C|10|0|Num Proc.|Num. Processo Simulação
FRJ|03|FRJ_LOTE|C|30|0|Lote do Proc|Lote do Processo
FRJ|04|FRJ_STATUS|C|1|0|Status|Status do Processo
FRJ|05|FRJ_DTSIMU|D|8|0|Data Simul.|Data da Simulacao
FRJ|06|FRJ_HRSIMU|C|8|0|Hora Simul.|Hora da Simulacao
FRJ|07|FRJ_USSIMU|C|15|0|Usuario Sim.|Usuario da Simulacao
FRJ|08|FRJ_DTGENF|D|8|0|Dt.Ger.NF|Data da Geração da NF
FRJ|09|FRJ_HRGENF|C|8|0|Hr. Ger. NF|Hora da Geraçao da NF
FRJ|10|FRJ_USGENF|C|15|0|Usr. Ger. NF|Usuario da Geração da NF
--- ### FRK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRK|01|FRK_FILIAL|C|6|0|Filial|Filial do Sistema
FRK|02|FRK_NUMPRO|C|10|0|Num Proc.|Num. Processo Simulação
FRK|03|FRK_LOTE|C|30|0|Lote Proc.|Lote do Processo
FRK|04|FRK_ITEM|C|3|0|Item|Item
FRK|05|FRK_NUMRA|C|20|0|RA do Aluno|RA do Aluno
FRK|06|FRK_CLIENT|C|6|0|Cliente|Cliente
FRK|07|FRK_VENCTO|D|8|0|Data Venc|Data de Vencimento
FRK|08|FRK_NUMTIT|C|9|0|Num. Titulo|Numero do Titulo
FRK|09|FRK_PRODUT|C|15|0|Produto|Cod. do Produto
FRK|10|FRK_VALOR|N|14|2|Valor|Valor
FRK|11|FRK_DEDUC|N|14|2|Vlr.Deducao|Valor de deducao/Desconto
FRK|12|FRK_AGRUP|C|1|0|Tipo Agrup.|Tipo de agrupamento
FRK|13|FRK_NOTA|C|9|0|Numero NF|Numero da Nota Fiscal
FRK|14|FRK_SERIE|C|3|0|Serie Nota|Serie da Nota
FRK|15|FRK_NFITEM|C|2|0|Item NF|Item NF
FRK|16|FRK_DTFAT|D|8|0|Dt. faturam.|Data faturamento
FRK|17|FRK_IDBOLE|N|9|0|Id Boleto|Id Boleto
FRK|18|FRK_TES|C|3|0|TES|Tipo de Ent/Saida
FRK|19|FRK_CCUSTO|C|9|0|C. Custo|C. Custo
FRK|20|FRK_CLVL|C|9|0|C Valor|C Valor
FRK|21|FRK_ITEMCC|C|9|0|Item Cont.|Item Contabil
FRK|22|FRK_CONITE|N|1|0|Conf. Itens|Conf. Itens
FRK|23|FRK_ITPROC|C|3|0|Sequencial|Numero sequencial
FRK|24|FRK_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### FRL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRL|01|FRL_FILIAL|C|6|0|FIlial|Filial
FRL|02|FRL_NUMPRO|C|10|0|Num Proc.|Num. Processo Simulação
FRL|03|FRL_TIPFIL|C|2|0|Tipo Filtro|Tipo do Filtro
FRL|04|FRL_NUMRA|C|20|0|RA do Aluno|RA do Aluno
FRL|05|FRL_CONTEU|C|30|0|Conteudo Fil|Conteudo do Filtro
--- ### FRO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRO|01|FRO_FILIAL|C|6|0|Filial|Filial do Sistema
FRO|02|FRO_COD|C|6|0|Código|Código
FRO|03|FRO_USER|C|6|0|Cód. Usuário|Código do Usuário
FRO|04|FRO_NOME|C|40|0|Nome|Nome do Analista
FRO|05|FRO_TEL|C|30|0|Fone|Fone
FRO|06|FRO_FAX|C|30|0|Fax|Fax
FRO|07|FRO_EMAIL|C|30|0|E-mail|E-mail
FRO|08|FRO_GRAPRO|C|6|0|Grupo Aprov.|Grupo de Aprovação
FRO|09|FRO_GRPANA|C|6|0|Grupo Padrão|Grupo Analista Padrão
FRO|10|FRO_ACCID|C|22|0|Perfil ACC|Perfil ACC
--- ### FRP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRP|01|FRP_FILIAL|C|6|0|Filial|Filial do Sistema
FRP|02|FRP_COD|C|6|0|Código|Código do Gestor
FRP|03|FRP_USER|C|6|0|Cód. Usuário|Código do Usuário
FRP|04|FRP_NOME|C|25|0|Nome|Nome Completo
FRP|05|FRP_LIMMIN|N|14|2|Val. Mínimo|Limite Mínimo Aprovação
FRP|06|FRP_LIMMAX|N|14|2|Val. Máximo|Limite Máximo Aprovação
FRP|07|FRP_CODSUP|C|6|0|Gestor Super|Gestor Superior
FRP|08|FRP_MOEDA|C|2|0|Moeda|Moeda do Limite
FRP|09|FRP_LIMITE|N|14|2|Limite|Limite de Aprovação
FRP|10|FRP_TIPO|C|1|0|Tipo Limite|Tipo do Limite de Aprov.
FRP|11|FRP_LIMTIT|N|14|2|Lim. Título|Limite do Título
FRP|12|FRP_MSBLQL|C|1|0|Bloqueado|Registro bloqueado
--- ### FRQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRQ|01|FRQ_FILIAL|C|6|0|Filial|Filial do Sistema
FRQ|02|FRQ_GRPANA|C|6|0|Grupo|Grupo de Analistas
FRQ|03|FRQ_DESC|C|25|0|Descricao|Descricao do Grupo
FRQ|04|FRQ_ITEM|C|2|0|Item|Item do Grupo
FRQ|05|FRQ_USER|C|6|0|Cód Analista|Código do Analista
FRQ|06|FRQ_NOME|C|25|0|Nome|Nome do usuário
--- ### FRR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRR|01|FRR_FILIAL|C|6|0|Filial|Filial do Sistema
FRR|02|FRR_COD|C|6|0|Cód. Grupo|Código Grupo de Gestores
FRR|03|FRR_DESC|C|20|0|Descrição|Descrição do Grupo
FRR|04|FRR_MOEDA|C|2|0|Moeda|Moeda do Grupo
FRR|05|FRR_ITEM|C|2|0|Item|Item do Grupo
FRR|06|FRR_CODGES|C|6|0|Cód. Gestor|Código do Gestor
FRR|07|FRR_USER|C|6|0|Cód. Usuário|Código de Usuário
FRR|08|FRR_NOME|C|25|0|Nome|Nome do Usuário Gestor
FRR|09|FRR_NIVEL|C|2|0|Nível|Nível de Aprovação Gestor
FRR|10|FRR_LIBAPR|C|1|0|Tipo Aprova.|Tipo de Aprovação
FRR|11|FRR_AUTLIM|C|1|0|Utiliza Lim.|Utiliza Limite do Gestor
FRR|12|FRR_TIPLIB|C|1|0|Tipo Lib.|Tipo de Liberação
--- ### FRS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRS|01|FRS_FILIAL|C|6|0|Filial|Filial do Sistema
FRS|02|FRS_TIPO|C|1|0|Tipo|Tipo do Aprovador
FRS|03|FRS_CODAPR|C|6|0|Aprovador|Código do Aprovador
FRS|04|FRS_NOME|C|20|0|Nome|Nome do Aprovador
FRS|05|FRS_SEQ|C|2|0|Sequência|Sequência de Aprovação
FRS|06|FRS_CODSUP|C|6|0|Superior|Código do Superior
FRS|07|FRS_NOMSUP|C|20|0|Nome|Nome do Superior
--- ### FRT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRT|01|FRT_FILIAL|C|6|0|Filial|Filial do Sistema
FRT|02|FRT_CODGES|C|6|0|Cód. Gestor|Código do Gestor
FRT|03|FRT_USER|C|6|0|Cód. Usuário|Código do Usuário
FRT|04|FRT_TIPO|C|1|0|Tipo Movimen|Tipo de Movimento
FRT|05|FRT_MOEDA|C|2|0|Moeda|Moeda de Movimento
FRT|06|FRT_DATA|D|8|0|Dt. Moviment|Data do Movimento
FRT|07|FRT_SEQ|C|6|0|Sequência|Sequência do Movimento
FRT|08|FRT_SALDO|N|14|2|Saldo Mov.|Saldo do Movimento
--- ### FRU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRU|01|FRU_FILIAL|C|6|0|Filial|Filial do sistema
FRU|02|FRU_COD|C|9|0|Código|Código do componente
FRU|03|FRU_PREFIX|C|3|0|Prefixo|Prefixo do título
FRU|04|FRU_NUM|C|9|0|Número|Número do título
FRU|05|FRU_PARCEL|C|3|0|Parcela|Parcela do título
FRU|06|FRU_TIPO|C|3|0|Tipo|Tipo do título
FRU|07|FRU_FORNEC|C|6|0|Fornecedor|Fornecedor do ti. a pagar
FRU|08|FRU_LOJA|C|2|0|Loja|Loja do fornecedor
FRU|09|FRU_DESC|C|30|0|Descrição|Descrição do componente
FRU|10|FRU_VALOR|N|16|2|Valor|Valor do componente
--- ### FRV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FRV|01|FRV_FILIAL|C|6|0|Filial|Filial do Sistema
FRV|02|FRV_CODIGO|C|1|0|Código|Código situação cobrança
FRV|03|FRV_DESCRI|C|40|0|Descrição|Descrição Sit. Cobrança
FRV|04|FRV_BANCO|C|1|0|Usa Banco|Utiliza Banco
FRV|05|FRV_DESCON|C|1|0|Descontada|Cobrança descontada
FRV|06|FRV_PROTES|C|1|0|Protesto|Protesto
FRV|07|FRV_PERCEN|N|6|2|Perc. Desc.|Percentual de desconto
FRV|08|FRV_NATIOF|C|10|0|Natureza|Natureza para IOF
FRV|09|FRV_BLQMOV|C|1|0|Bloqueio Mov|Bloqueio Movtos de titulo
FRV|10|FRV_SITPDD|C|1|0|Situação PDD|Situação PDD
FRV|11|FRV_PIX|C|1|0|Situação PIX|Situação PIX
FRV|12|FRV_JURIDC|C|1|0|Judicial|Situação Judicial
FRV|13|FRV_GRRCOD|C|32|0|Carteir. GRR|Cod. Carteira GRR
--- ### FV0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV0|01|FV0_FILIAL|C|6|0|Filial|Filial do Sistema
FV0|02|FV0_UGEMIT|C|6|0|UG Emitente|Unidade Gestora Emitente
FV0|03|FV0_UGDESC|C|50|0|Desc. UG|Descrição Unidade Gestora
FV0|04|FV0_TIPODC|C|6|0|Tipo Doc.|Tipo de Documento Hábil
FV0|05|FV0_NTIPDC|C|55|0|Desc. Tipo|Descrição Tipo Documento
FV0|06|FV0_CODSIA|C|12|0|Código SIAFI|Código Documento SIAFI
FV0|07|FV0_CODIGO|C|6|0|ID Processo|Identificação Processo
FV0|08|FV0_STATUS|C|1|0|Status|Status
FV0|09|FV0_FORNEC|C|6|0|Fornecedor|Fornecedor
FV0|10|FV0_LOJA|C|2|0|Loja|Loja do Fornecedor
FV0|11|FV0_NFORNE|C|80|0|Desc. Forn.|Descrição do Fornecedor
FV0|12|FV0_UGPAGA|C|6|0|UG Pagadora|Unidade Gestora Pagadora
FV0|13|FV0_UGDSPG|C|30|0|Desc. UG Pag|Descrição UG Pagadora
FV0|14|FV0_SISORI|C|3|0|Sist. Origem|Sistema de Origem
FV0|15|FV0_DTEMIS|D|8|0|Data Emissão|Data de Emissão
FV0|16|FV0_DTVENC|D|8|0|Data Venc.|Data de Vencimento
FV0|17|FV0_TAXACA|N|6|4|Taxa Câmbio|Taxa de Câmbio
FV0|18|FV0_PROCES|C|20|0|Processo|Processo
FV0|19|FV0_ATESTE|D|8|0|Ateste|Ateste
FV0|20|FV0_VLRDOC|N|16|2|Valor Doc.|Valor do Documento
FV0|21|FV0_OBS|M|10|0|Observação|Observação Documento
FV0|22|FV0_ADICIO|M|6|0|Info. Adic.|Informação Adicional
FV0|23|FV0_OK|C|2|0|Iden.Selecao|Identificador de Selecao
FV0|24|FV0_DATPAG|D|8|0|Dat. Pag.|Data de Pagamento
--- ### FV1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV1|01|FV1_ITEM|C|4|0|Item|Item
FV1|02|FV1_CODPRO|C|6|0|Código DH|Código Documento Hábil
FV1|03|FV1_EMISSA|D|8|0|Emissão|Data de Emissão
FV1|04|FV1_DOCORI|C|17|0|Doc. Origem|Nº Documento de Origem
FV1|05|FV1_PREFIX|C|3|0|Prefixo|Prefixo do Título
FV1|06|FV1_NUMERO|C|9|0|Número|Número do Título
FV1|07|FV1_PARCEL|C|3|0|Parcela|Parcela do Título
FV1|08|FV1_TIPO|C|3|0|Tipo Título|Tipo do Título
FV1|09|FV1_FILIAL|C|6|0|Filial|Filial do Sistema
FV1|10|FV1_VALOR|N|16|2|Valor|Valor Documento Origem
--- ### FV2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV2|01|FV2_FILIAL|C|6|0|Filial|Filial do Sistema
FV2|02|FV2_CODPRO|C|6|0|ID Processo|Identificação Processo
FV2|03|FV2_ITEM|C|4|0|Item|Item
FV2|04|FV2_SITUAC|C|6|0|Situação|Situação do DH
FV2|05|FV2_NSITUA|C|100|0|Desc.Situa|Descrição da Situação
FV2|06|FV2_UGEMPE|C|6|0|UG Empenho|Unidade Gestora Empenho
FV2|07|FV2_NUGEMP|C|30|0|Desc. UG Emp|Descrição UG Empenho
FV2|08|FV2_CONTRA|C|1|0|Contrato?|Tem contrato?
--- ### FV3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV3|01|FV3_FILIAL|C|6|0|Filial|Filial do Sistema
FV3|02|FV3_IDPROC|C|10|0|ID Process|ID do processamento
FV3|03|FV3_LINARQ|C|16|0|Linha Proc|Linha do arq processado
FV3|04|FV3_NOMARQ|C|100|0|Nome Arquivo|Nome do Arquivo
FV3|05|FV3_DTPROC|D|8|0|Data Process|Data Processamento TEF
FV3|06|FV3_HRPROC|C|8|0|Hora Process|Hora do Processamento Tef
FV3|07|FV3_CODEST|C|15|0|Codigo Estab|Código do Estabelecimento
FV3|08|FV3_NUCOMP|C|100|0|Comprovante|Número do Comprovante
FV3|09|FV3_MOTIVO|C|150|0|Motivo|Motivo do Log. importação
--- ### FV4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV4|01|FV4_FILIAL|C|6|0|Filial|Filial do Sistema
FV4|02|FV4_SITUAC|C|6|0|Situação|Situação do DH
FV4|03|FV4_IDCAMP|C|4|0|Id. Campo|Id. Campo
FV4|04|FV4_DSCAMP|C|50|0|Descrição|Descrição do Campo
FV4|05|FV4_TPCAMP|C|1|0|Tipo Campo|Tipo de Campo
FV4|06|FV4_TAMCAM|N|3|0|Tamanho|Tamanho do Campo
FV4|07|FV4_DECCAM|N|1|0|Decimal|Decimal do Campo
FV4|08|FV4_OBGCAM|C|1|0|Obrigatório?|Campo obrigatório?
FV4|09|FV4_CSPCAM|C|6|0|Cons. Padrão|Consulta Padrão
FV4|10|FV4_PICCAM|C|45|0|Picture|Picture do Campo
FV4|11|FV4_OPCOES|C|100|0|Opções|Opções do Campo
FV4|12|FV4_VALID|C|128|0|Validação|Validação do Campo
FV4|13|FV4_WHEN|C|60|0|Modo Edição|Modo Edição
FV4|14|FV4_STATUS|C|1|0|Ativo ?|Campo Ativo?
FV4|15|FV4_LOCAL|C|1|0|Local. Cpo.|Localização do campo
FV4|16|FV4_TAGXML|C|30|0|Tag XML|Tag para o XML
--- ### FV5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV5|01|FV5_FILIAL|C|6|0|Filial|Filial do Sistema
FV5|02|FV5_ITEM|C|4|0|Item|Item
FV5|03|FV5_NEMPE|C|12|0|Nº Empenho|Número do Empenho
FV5|04|FV5_SUBEMP|C|2|0|SubItem|SubItem do Empenho
FV5|05|FV5_ITEMP|C|3|0|Item Emp|Item da Nota Empenho
FV5|06|FV5_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FV5|07|FV5_NFONRE|C|40|0|Desc.Fonte|Desc. Fonte do Recurso
FV5|08|FV5_RPLIQU|C|1|0|RP Liquid.|RP em Liquidação
FV5|09|FV5_EVALOR|N|16|2|Valor|Valor do Empenho
FV5|10|FV5_CODPRO|C|6|0|ID Processo|Identificação do Processo
FV5|11|FV5_SITUAC|C|6|0|Situacão|Situação
FV5|12|FV5_ITEFV2|C|4|0|Item|Item
--- ### FV6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV6|01|FV6_FILIAL|C|6|0|Filial|Filial do Sistema
FV6|02|FV6_ITEM|C|4|0|Item|Item
FV6|03|FV6_FAVORE|C|6|0|Favorecido|Favorecido
FV6|04|FV6_LOJA|C|2|0|Loja|Loja Favorecido
FV6|05|FV6_NFAVOR|C|80|0|Desc. Fav.|Descrição do Favorecido
FV6|06|FV6_TIPO|C|1|0|Tipo|Tipo do Favorecido
FV6|07|FV6_CGC|C|14|0|CNPJ/CPF|CNPJ/CPF do Favorecido
FV6|08|FV6_VLREAL|N|16|2|Vlr. Realiz.|Valor Realizado
FV6|09|FV6_CODPRO|C|6|0|ID Processo|Identificação do Processo
FV6|10|FV6_VALOR|N|16|2|Valor Pag.|Valor de Pagamento
--- ### FV7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV7|01|FV7_FILIAL|C|6|0|Filial|Filial do Sistema
FV7|02|FV7_CODPRO|C|6|0|ID Processo|Identificação do Processo
FV7|03|FV7_FAVORE|C|6|0|Favorecido|Favorecido da OB
FV7|04|FV7_LOJA|C|2|0|Loja|Loja do Fornecedor
FV7|05|FV7_TIPOOB|C|6|0|Tipo OB|Tipo de Ordem Bancária
FV7|06|FV7_NTIPOB|C|55|0|Desc. OB|Descrição OB
FV7|07|FV7_LISTA|C|12|0|Lista|Número da Lista
FV7|08|FV7_CIT|C|25|0|CIT|CIT
FV7|09|FV7_BCOFAV|C|3|0|Banco Fav.|Banco do Favorecido
FV7|10|FV7_AGEFAV|C|5|0|Agência Fav.|Agência Bancária Fav.
FV7|11|FV7_CTAFAV|C|10|0|Conta Fav.|Conta Bancária Favorecido
FV7|12|FV7_BCOUG|C|3|0|Banco UG|Banco da Unidade Gestora
FV7|13|FV7_AGEUG|C|5|0|Agência UG|Agência Bancária UG
FV7|14|FV7_CTAUG|C|10|0|Conta UG|Conta Bancária UG
FV7|15|FV7_ITEM|C|4|0|Item|Item
FV7|16|FV7_RECURS|C|1|0|Recurso|Recurso
FV7|17|FV7_NRECUR|C|55|0|Desc.Tp.Rec.|Desc. Tipo Recurso
FV7|18|FV7_PERAPU|D|8|0|Apuração|Período Apuração
FV7|19|FV7_REFERE|C|8|0|Referência|Referência
FV7|20|FV7_PROCES|C|8|0|Processo|Processo
FV7|21|FV7_RDBTAC|N|12|2|Rec.Br.Acu.|Receita Bruta Acum.
FV7|22|FV7_PERCEN|N|5|2|Percentual|Percentual
FV7|23|FV7_UGFAVO|C|6|0|UG Favor.|UG Favorecida
FV7|24|FV7_RECOLH|C|14|0|Recolhedor|Recolhedor
FV7|25|FV7_NNUMER|C|20|0|Nº Rf/Nos.Nº|Nº Referência/Nosso Nº
FV7|26|FV7_MESCOM|C|2|0|Mês Compet.|Mês de Competência
FV7|27|FV7_ANOCOM|C|4|0|Ano Compet.|Ano de Competência
FV7|28|FV7_VLRDOC|N|12|2|Vlr. Doc.|(=) Valor Documento (VD)
FV7|29|FV7_VLRABA|N|12|2|Desc. Aba.|(-) Desc. Abatiment. (VA)
FV7|30|FV7_UGTMSV|C|6|0|UG Tom. Serv|UG Tomadora do Serviço
FV7|31|FV7_MUNICI|C|4|0|Mun. NF|Município da NF
FV7|32|FV7_NUMNF|C|9|0|Nº NF|Número da NF
FV7|33|FV7_DTEMNF|D|8|0|Dt. Em. NF|Data Emissão NF
FV7|34|FV7_SERINF|C|4|0|Série NF|Série da NF
FV7|35|FV7_SBSRNF|C|8|0|Nº Sub. NF.|Nº SubSérie da NF
FV7|36|FV7_ALIQNF|N|7|3|Alíquota NF|Alíquota NF
FV7|37|FV7_VALNF|N|12|2|Valor NF|Valor da Nota Fiscal
FV7|38|FV7_AGEREC|C|4|0|Agência Rec.|Agência do Recolhedor
FV7|39|FV7_IDGFIP|C|20|0|Id. GFIP|Identificador GFIP
FV7|40|FV7_IDRECO|C|7|0|Id. Rec.|Ident. Recolhimento
FV7|41|FV7_FPAS|C|3|0|FPAS|FPAS
FV7|42|FV7_ENTIDA|C|4|0|Entidades|Entidades
FV7|43|FV7_SIMPLE|C|1|0|Simples|Simples Nacional
FV7|44|FV7_QTDTRA|N|7|0|Qtd. Trabal.|Qtd. Trabalhadores
FV7|45|FV7_REMFG8|N|7|2|Rem. FGTS 8%|Remessa FGTS 8%
FV7|46|FV7_REMFG2|N|7|2|Rem. FGTS 2%|Remessa FGTS 2%
FV7|47|FV7_INSSMS|N|7|2|INSS Mensal|INSS Mensal
FV7|48|FV7_CTSGDV|N|7|2|Cont. Seg.|Cont. Seg. Devida
FV7|49|FV7_PRVSOC|N|7|2|Prev. Social|Previdência Social
FV7|50|FV7_CTSGDC|N|7|2|Cont.Seg.Des|Cont.Seg.Descontado
FV7|51|FV7_DEPCTS|N|7|2|Dep.Cont.Soc|Depósito + Cont. Social
FV7|52|FV7_ENCARG|N|7|2|Encargos|Encargos
FV7|53|FV7_PREDOC|C|1|0|Tipo Pre-Doc|Tipo Pre-Doc
FV7|54|FV7_IDTAB|C|1|0|Identif. Tab|Identificador da Tabela
FV7|55|FV7_ITEDOC|C|4|0|Item|Item
FV7|56|FV7_VLRDED|N|12|2|Valor Ded.|(-)  Outras Deduções (OD)
FV7|57|FV7_TXCAMB|N|7|2|Taxa Cambio|Taxa de Cambio
FV7|58|FV7_ADT|L|1|0|Adt 13º|Adiantamento de 13º
FV7|59|FV7_SITUAC|C|6|0|Situação|Situação do DH
FV7|60|FV7_OBS|M|6|0|Observação|Observação da OB
--- ### FV8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV8|01|FV8_FILIAL|C|6|0|Filial|Filial do Sistema
FV8|02|FV8_CODPRO|C|6|0|ID Processo|Identificação do Processo
FV8|03|FV8_ITEM|C|4|0|Item|Item
FV8|04|FV8_SITUAC|C|6|0|Situação|Situação do DH
FV8|05|FV8_NSITUA|C|100|0|Desc.Situa|Descrição da Situação
--- ### FV9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FV9|01|FV9_ITEM|C|4|0|Item|Item
FV9|02|FV9_CODPRO|C|6|0|ID Processo|Identificação do Processo
FV9|03|FV9_ITEFV8|C|4|0|Item Sit.|Item da Situação
FV9|04|FV9_FILIAL|C|6|0|Filial|Filial do Sistema
FV9|05|FV9_SITUAC|C|6|0|Situacao|Situacao do DH
FV9|06|FV9_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FV9|07|FV9_NFONRE|C|40|0|Desc.Fonte|Desc. Fonte do Recurso
FV9|08|FV9_CATGAS|C|6|0|Cat. Gastos|Categoria de Gastos
FV9|09|FV9_NCATGA|C|55|0|Desc.Cat.Gs.|Descrição Categoria Gasto
FV9|10|FV9_VALOR|N|16|2|Valor|Valor
--- ### FVA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVA|01|FVA_FILIAL|C|6|0|Filial|Filial do Sistema
FVA|02|FVA_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVA|03|FVA_ITEM|C|4|0|Item|Item
FVA|04|FVA_SITUAC|C|6|0|Situação|Situação do DH
FVA|05|FVA_NSITUA|C|100|0|Desc. Situac|Descrição da Situação
FVA|06|FVA_VALOR|N|16|2|Valor|Valor
--- ### FVB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVB|01|FVB_ITEM|C|4|0|Item|Item
FVB|02|FVB_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVB|03|FVB_FILIAL|C|6|0|Filial|Filial do Sistema
FVB|04|FVB_SITUAC|C|6|0|Situação|Situação do DH
FVB|05|FVB_NSITUA|C|100|0|Desc. Situac|Descrição da Situação
FVB|06|FVB_NEMPE|C|12|0|Nº Empenho|Número do Empenho
FVB|07|FVB_SUBEMP|C|2|0|SubItem|SubItem do Empenho
FVB|08|FVB_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FVB|09|FVB_NFONRE|C|40|0|Fonte de Rec|Fonte de Recurso
FVB|10|FVB_RPLIQU|C|1|0|RP Liquid.|RP em Liquidação
FVB|11|FVB_UGEMPE|C|6|0|UG. Empenho|UG do Empenho
FVB|12|FVB_NUGEMP|C|30|0|Desc. UG Emp|Descricao UG Empenho
FVB|13|FVB_DTVENC|D|8|0|Data Venc.|Data de Vencimento
FVB|14|FVB_DTPAGA|D|8|0|Data Pagto.|Data de Pagamento
FVB|15|FVB_VALOR|N|16|2|Valor|Valor
--- ### FVD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVD|01|FVD_ITEM|C|4|0|Item|Item
FVD|02|FVD_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVD|03|FVD_FILIAL|C|6|0|Filial|Filial do Sistema
FVD|04|FVD_SITUAC|C|6|0|Situação|Situação do DH
FVD|05|FVD_NSITUA|C|100|0|Desc. Situac|Descrição da Situação
FVD|06|FVD_DTVENC|D|8|0|Data Venc.|Data de Vencimento
FVD|07|FVD_DTPAGA|D|8|0|Data Pagam.|Data de Pagamento
FVD|08|FVD_VALOR|N|16|2|Valor|Valor
--- ### FVE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVE|01|FVE_FILIAL|C|6|0|Filial|Filial do Sistema
FVE|02|FVE_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVE|03|FVE_ITEM|C|4|0|Item|Item
FVE|04|FVE_SITUAC|C|6|0|Situação|Situação do DH
FVE|05|FVE_FORNEC|C|6|0|Fornecedor|Fornecedor
FVE|06|FVE_LOJA|C|2|0|Loja|Loja
FVE|07|FVE_NFORNE|C|80|0|Desc. Forn.|Descrição do Fornecedor
FVE|08|FVE_TIPO|C|1|0|Tipo|Tipo do Recolhedor
FVE|09|FVE_CGC|C|14|0|CNPJ/CPF|CNPJ/CPF do Recolhedor
FVE|10|FVE_VLRINS|N|16|2|Valor|Valor
FVE|11|FVE_VLROEN|N|16|2|Val. Entidad|Valores outras entidades
FVE|12|FVE_VLRACR|N|16|2|Vlr. A/M/J.|Valor ATM/Multa/Juros
FVE|13|FVE_ITETAB|C|4|0|Item|Item
FVE|14|FVE_BSCALC|N|12|2|Base Cálculo|Base de Cálculo
FVE|15|FVE_VLRMUL|N|12|2|Vlr. Multa|Valor de Multa
FVE|16|FVE_VLRJUR|N|12|2|Vlr. Juros|Valor de Juros
FVE|17|FVE_TABREL|C|3|0|Tab. Rel.|Tabela de Relacionamento
--- ### FVF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVF|01|FVF_ITEM|C|4|0|Item|Item
FVF|02|FVF_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVF|03|FVF_SECAO|C|6|0|Seção/Aba|Seção/Aba
FVF|04|FVF_ITETAB|C|4|0|Item|Item
FVF|05|FVF_SITUAC|C|6|0|Situação|Situação do DH
FVF|06|FVF_FILIAL|C|6|0|Filial|Filial do Sistema
FVF|07|FVF_TIPO|C|1|0|Tipo|Tipo de Acréscimo
FVF|08|FVF_NEMPE|C|12|0|Nº Empenho|Número Empenho
FVF|09|FVF_SUBEMP|C|2|0|Subitem|SubItem do Empenho
FVF|10|FVF_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FVF|11|FVF_NFONRE|C|40|0|Fonte de Rec|Fonte de Recurso
FVF|12|FVF_RPLIQU|C|1|0|RP Liquid.|RP em Liquidação
FVF|13|FVF_VALOR|N|16|2|Valor|Valor
--- ### FVG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVG|01|FVG_FILIAL|C|6|0|Filial|Filial
FVG|02|FVG_CODIMO|C|6|0|Cód. Imóvel|Código do Imóvel
FVG|03|FVG_TPPES|C|1|0|Tp. Pessoa|Tipo da Pessoa
FVG|04|FVG_CODPES|C|6|0|Cód. Pessoa|Código da Pessoa
FVG|05|FVG_NOMPES|C|40|0|Nome|Nome do Terceiro
FVG|06|FVG_TIPO|C|1|0|Exploração|Tipo de Expl. do terceiro
FVG|07|FVG_PERC|N|6|2|Particip.(%)|Percentual exploração
FVG|08|FVG_CAEPF|C|14|0|CAEPF|Cad. Ativ. Economica PF
FVG|09|FVG_NUMIMO|C|3|0|Núm. Imóvel|Núm. Imóvel
FVG|10|FVG_ORIG|C|1|0|Orig. Terc.|Origem do Terceiro
FVG|11|FVG_VERSAO|C|4|0|Versão|Versão do imóvel
--- ### FVH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVH|01|FVH_FILIAL|C|6|0|Filial|Filial do Sistema
FVH|02|FVH_TIPODC|C|6|0|Tipo Doc.|Tipo de Documento Hábil
FVH|03|FVH_NTIPDC|C|55|0|Desc. Tipo|Descrição Tipo Documento
FVH|04|FVH_SECAO|C|6|0|Seção/Aba|Seção/Aba
FVH|05|FVH_NSECAO|C|55|0|Desc.Seção|Descrição da Seção
--- ### FVI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVI|01|FVI_FILIAL|C|6|0|Filial|Filial do Sistema
FVI|02|FVI_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVI|03|FVI_ITESEC|C|6|0|Seção/Aba|Seção/Aba
FVI|04|FVI_ITETAB|C|4|0|Item|Item
FVI|05|FVI_ITESIT|C|6|0|Situação|Situação do DH
FVI|06|FVI_ITEM|C|4|0|Item|Item
FVI|07|FVI_SITUAC|C|6|0|Situação|Situação do DH
FVI|08|FVI_NEMPE|C|12|0|NºEmpenho|Número de Empenho
FVI|09|FVI_SUBEMP|C|2|0|SubItem|SubItem do Empenho
FVI|10|FVI_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FVI|11|FVI_NFONRE|C|10|0|Desc. Fonte|Desc.Font.Rec
FVI|12|FVI_CATGAS|C|6|0|Cat. Gastos|Categoria de Gastos
FVI|13|FVI_NCATGA|C|55|0|Desc.Cat.Gs.|Descrição Categoria Gasto
FVI|14|FVI_VALOR|N|16|2|Valor|Valor
--- ### FVJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVJ|01|FVJ_FILIAL|C|6|0|Filial|Filial do Sistema
FVJ|02|FVJ_ID|C|6|0|Situac. Doc.|Situação do Doc. Hábil
FVJ|03|FVJ_DESCRI|C|100|0|Desc.Situac.|Descrição da Situação
FVJ|04|FVJ_PREDOC|C|1|0|Tipo Pré-Doc|Tipo Pré-Doc
FVJ|05|FVJ_TIPO|C|1|0|Tipo Situac.|Tipo da Situacao
--- ### FVK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVK|01|FVK_FILIAL|C|6|0|Filial|Filial do Sistema
FVK|02|FVK_TIPODC|C|6|0|Tipo Doc.|Tipo de Documento Hábil
FVK|03|FVK_NTIPDC|C|55|0|Desc. Tipo|Descrição Tipo Documento
FVK|04|FVK_SECAO|C|6|0|Seção/Aba|Seção/Aba
FVK|05|FVK_NSECAO|C|55|0|Desc.Seção|Descrição da Seção
FVK|06|FVK_SITUAC|C|6|0|Situação|Situação do DH
FVK|07|FVK_NSITUA|C|100|0|Desc.Situa.|Descrição da Situação
--- ### FVL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVL|01|FVL_ITEM|C|4|0|Item|Item
FVL|02|FVL_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVL|03|FVL_FILIAL|C|6|0|Filial|Filial do Sistema
FVL|04|FVL_SITUAC|C|6|0|Situação|Situação do DH
FVL|05|FVL_NSITUA|C|100|0|Desc.Situac|Descrição da Situação
FVL|06|FVL_UGEMPE|C|6|0|UG Empenho|Unidade Gestora Empenho
FVL|07|FVL_NUGEMP|C|30|0|Desc. UG Emp|Descrição UG Empenho
--- ### FVM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVM|01|FVM_ITEM|C|4|0|Item|Item
FVM|02|FVM_CODPRO|C|6|0|ID Processo|Identificação do Processo
FVM|03|FVM_ITEFVL|C|4|0|Item|Item
FVM|04|FVM_FILIAL|C|6|0|Filial|Filial do Sistema
FVM|05|FVM_SITUAC|C|6|0|Situação|Situação do DH
FVM|06|FVM_NEMPE|C|12|0|Nº Empenho|Número de Empenho
FVM|07|FVM_SUBEMP|C|2|0|Subitem|Subitem do Empenho
FVM|08|FVM_FONREC|C|10|0|Fonte de Rec|Fonte de Recurso
FVM|09|FVM_NFONRE|C|40|0|Fonte de Rec|Fonte de Recurso
FVM|10|FVM_VALOR|N|16|2|Valor|Valor
--- ### FVN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVN|01|FVN_FILIAL|C|6|0|Filial|Filial do Sistema
FVN|02|FVN_CODPRO|C|6|0|ID Processo|Identificação Processo
FVN|03|FVN_TABELA|C|3|0|Tabela|Tabela Relacionada
FVN|04|FVN_ITETAB|C|4|0|Item|Item da Tabela
FVN|05|FVN_CAMPO|C|6|0|ID Campo|ID Campo
FVN|06|FVN_VALOR|C|50|0|Valor|Valor do Campo
FVN|07|FVN_TABPAI|C|3|0|Tabela Pai|Tabela Pai do item
FVN|08|FVN_ITEPAI|C|4|0|Item Pai|Item Pai
--- ### FVO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVO|01|FVO_FILIAL|C|6|0|Filial|Filial do Sistema
FVO|02|FVO_CODIGO|C|6|0|Código|Código UG Responsável
FVO|03|FVO_DESCRI|C|100|0|Desc. UGR|Descrição da UGR
FVO|04|FVO_CODORG|C|6|0|Unid.Gestora|Unidade Gestora
FVO|05|FVO_ORGDSC|C|30|0|Descrição UG|Descrição UG
--- ### FVP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVP|01|FVP_FILIAL|C|6|0|Filial|FIlial do Sistema
FVP|02|FVP_CODPRO|C|6|0|Código DH|Código Documento Hábil
FVP|03|FVP_ITEM|C|4|0|Item|Item
FVP|04|FVP_SITUAC|C|6|0|Situação|Situação do DH
FVP|05|FVP_VALOR|N|16|2|Valor|Valor do Imposto
FVP|06|FVP_PREFIX|C|3|0|Prefixo|Prefixo do Título
FVP|07|FVP_NUMERO|C|9|0|Número|Número do Título
FVP|08|FVP_PARCEL|C|3|0|Parcela|Parcela do Título
FVP|09|FVP_TIPO|C|3|0|Tipo|Tipo do Título
FVP|10|FVP_SUBITE|C|4|0|SubItem|SubItem
--- ### FVQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVQ|01|FVQ_FILIAL|C|6|0|Filial|Filial do Sistema
FVQ|02|FVQ_CODPRO|C|6|0|ID Processo|Identificação Processo
FVQ|03|FVQ_CODOBR|C|12|0|Cód. OB|Cód. Ordem Bancária
FVQ|04|FVQ_UGEMIT|C|6|0|UG Emitente|Unidade Gestora Emitente
FVQ|05|FVQ_VLRDOC|N|16|2|Valor Doc.|Valor do Documento
FVQ|06|FVQ_DTEMIS|D|8|0|Data Emissão|Data de Emissão
--- ### FVR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVR|01|FVR_FILIAL|C|6|0|Filial|Filial do Sistema
FVR|02|FVR_DESCLE|C|100|0|Status|Status Processamento
FVR|03|FVR_IDPROC|C|10|0|Id process|ID de processamento
FVR|04|FVR_NOMARQ|C|100|0|Nome arquivo|Nome do Arquivo
FVR|05|FVR_DTPROC|D|8|0|Data Process|Data Processamento TEF
FVR|06|FVR_HRPROC|C|8|0|Hora Process|Hora processamento TEF
FVR|07|FVR_QTDPRO|N|16|0|Reg Incluido|Qtd.Registros Incluidos
FVR|08|FVR_QTDALT|N|16|0|Lin Editadas|Linhas Editadas
FVR|09|FVR_QTDINC|N|16|0|Nao Processa|Qtd não processada
FVR|10|FVR_QTDLIN|N|16|0|Linhas lidas|Qtd Linhas lidas
FVR|11|FVR_QTDTOT|N|16|0|Tot Lin Arq|Qtd Total Linhas Arquivo
FVR|12|FVR_NOMUSU|C|50|0|Nome Usuário|Nome do Usuário do proces
FVR|13|FVR_STATUS|C|1|0|Status|Status da importação.
FVR|14|FVR_CODUSU|C|6|0|Cod. Usuário|Código Usuário.
FVR|15|FVR_NOMADM|C|50|0|Nome Adm|Nome da administradora.
FVR|16|FVR_CODADM|C|3|0|Cod. Adm|Código administradora.
FVR|17|FVR_MODPAG|C|1|0|Modo Pagto.|Modo de Pagamento
--- ### FVU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVU|01|FVU_FILIAL|C|6|0|Filial|Filial do sistema
FVU|02|FVU_CODIGO|C|6|0|Código|Código da Pessoa
FVU|03|FVU_NOME|C|50|0|Nome|Nome / Razão da Pessoa
FVU|04|FVU_TIPCAD|C|1|0|Tipo|Tipo Contribuinte da SRF
FVU|05|FVU_TPPES|C|1|0|Pessoa|Tipo de Pessoa
FVU|06|FVU_CNPJ|C|14|0|Cpf/Cnpj|Número de cadastro na SRF
FVU|07|FVU_END|C|150|0|Endereço|Endereço da Pessoa
FVU|08|FVU_NUM|N|6|0|Número|Número da residência
FVU|09|FVU_COMPL|C|50|0|Complemento|Complemento do endereço
FVU|10|FVU_BAIRRO|C|50|0|Bairro|Bairro do endereço
FVU|11|FVU_EST|C|2|0|Estado|Estado do endereço
FVU|12|FVU_CODMUN|C|5|0|Cód. Munic.|Cód. Municipio IBGE
FVU|13|FVU_CEP|C|8|0|CEP|Cód. End. Postal
FVU|14|FVU_FONE|C|15|0|Telefone|Núm. de Telefone Pessoa
FVU|15|FVU_EMAIL|C|115|0|Email|Email da Pessoa
FVU|16|FVU_FILORI|C|6|0|Fil. Origem|Filial de Origem
--- ### FVV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVV|01|FVV_FILIAL|C|6|0|Filial|Filial do Sistema
FVV|02|FVV_CODIGO|C|6|0|Código|Código do Imóvel
FVV|03|FVV_CODPES|C|6|0|Proprietário|Proprietário Contribuint
FVV|04|FVV_NOMPES|C|40|0|Nome Propr.|Nome do Proprietário
FVV|05|FVV_TIPOEX|C|1|0|Exploração|Tipo de Exploração
FVV|06|FVV_PARTIC|N|6|2|Particip.(%)|Percentual de Participaçã
FVV|07|FVV_NOME|C|50|0|Nome Imóvel|Nome do Imóvel
FVV|08|FVV_END|C|150|0|Endereço|Endereço
FVV|09|FVV_NUM|N|6|0|Número|Número do endereço
FVV|10|FVV_COMPL|C|50|0|Complemento|Complemento
FVV|11|FVV_BAIRRO|C|50|0|Bairro|Bairro/Distrito
FVV|12|FVV_UF|C|2|0|Estado|Estado
FVV|13|FVV_CODMUN|C|5|0|Cód. Munic.|Código Município no IBGE
FVV|14|FVV_MUNIC|C|60|0|Município|Município
FVV|15|FVV_CEP|C|8|0|CEP|Cód. Endereçamento Postal
FVV|16|FVV_PAIS|C|2|0|País|País do Imóvel
FVV|17|FVV_MOEDA|C|3|0|Moeda|Moeda do imóvel
FVV|18|FVV_INSCR|C|14|0|Ins. Estad.|Inscrição Estadual
FVV|19|FVV_CAFIR|C|8|0|CAFIR c/ DV|CAFIR (com DV)
FVV|20|FVV_CAEPF|C|14|0|CAEPF|CAEPF
FVV|21|FVV_MSBLQL|C|1|0|Bloqueado?|Imóvel ativo ou não?
FVV|22|FVV_VIGFIM|D|8|0|Fim Vigência|Fim da vigência
FVV|23|FVV_VERSAO|C|4|0|Versão|Versão do cadastro
FVV|24|FVV_VIGINI|D|8|0|Ini.Vigência|Início da Vigência
--- ### FVW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVW|01|FVW_FILIAL|C|6|0|Filial|Filial do Sistema
FVW|02|FVW_IDPROC|C|20|0|ID Process|ID de processamento.
FVW|03|FVW_NOMARQ|C|100|0|Nome Arquivo|Nome do Arquivo
FVW|04|FVW_DTPROC|D|8|0|Data Process|Data Processamento Sitef
FVW|05|FVW_HRPROC|C|8|0|Hora Process|Horário do Processamento
FVW|06|FVW_DESCLE|C|100|0|Desc. Legend|Descrição da Legenda.
FVW|07|FVW_NOMOPE|C|20|0|Nome Operad.|Nome da Operadora
FVW|08|FVW_QTDPRO|N|16|0|Qtd.Reg.Proc|Qtd. Reg. Processados
FVW|09|FVW_QTDINC|N|16|0|Qtd.Nao Proc|Qtd.Nao Proc Inconsistenc
FVW|10|FVW_NOMUSU|C|20|0|Nome Usuario|Nome do Usuario
FVW|11|FVW_STATUS|C|1|0|Status|Status da Importação
--- ### FVX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVX|01|FVX_FILIAL|C|6|0|Filial|Filial do Sistema
FVX|02|FVX_CODIGO|C|4|0|Código|Cód. da Justificativa
FVX|03|FVX_DESCRI|C|30|0|Descrição|Desc. da Justificativa
--- ### FVY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVY|01|FVY_FILIAL|C|6|0|Filial|Filial do Sistema
FVY|02|FVY_CODOPE|C|3|0|Cod. Oper.|Código da Operadora
FVY|03|FVY_NOMEOP|C|50|0|Nome Operad.|Nome da Operadora
FVY|04|FVY_CODMOT|C|6|0|Cod. Mot.|Codigo Moitvo
FVY|05|FVY_DESCR|C|20|0|Desc. Motivo|Descrição do Motivo
--- ### FVZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FVZ|01|FVZ_FILIAL|C|6|0|Filial|Filial do Sistema
FVZ|02|FVZ_FILCON|C|6|0|Filial|Filial
FVZ|03|FVZ_DSCFIL|C|40|0|Descrição|Descrição da Filial
--- ### FW0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW0|01|FW0_FILIAL|C|6|0|Filial|Filial do Sistema
FW0|02|FW0_CLASS|C|1|0|Classif.|Classificação
FW0|03|FW0_ADIANT|C|1|0|Adiantamento|Etapas do adiantamento
FW0|04|FW0_PREST|C|1|0|Prest.Contas|Etapas Prest.Contas
FW0|05|FW0_VIAGE|C|1|0|Viagens|Etapas da sol.viagens
--- ### FW1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW1|01|FW1_FILIAL|C|6|0|Filial|Filial do Sistema
FW1|02|FW1_CODIGO|C|4|0|Código|Código do Processo
FW1|03|FW1_DESCRI|C|40|0|Descrição|Descrição do Processo
--- ### FW2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW2|01|FW2_FILIAL|C|6|0|Filial|Filial do Sistema
FW2|02|FW2_SITUAC|C|1|0|Situação|Situação de cobrança
FW2|03|FW2_CODIGO|C|4|0|Código|Código do Processo
FW2|04|FW2_DESCRI|C|40|0|Descrição|Descrição do Processo
--- ### FW3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW3|01|FW3_FILIAL|C|6|0|Filial|Filial do Sistema
FW3|02|FW3_SOLICI|C|10|0|ID Solic.|Código da Solicitação
FW3|03|FW3_NACION|C|1|0|Nacional|Viagem Nacional
FW3|04|FW3_CODORI|C|10|0|Origem|Código origem da viagem
FW3|05|FW3_DESORI|C|40|0|Desc Origem|Descrição de Origem
FW3|06|FW3_CODDES|C|10|0|Destino|Código Destino da Viagem
FW3|07|FW3_DESDES|C|40|0|Desc.Destino|Descrição do Destino
FW3|08|FW3_DTINI|D|8|0|Data Inicial|Data Inicial da Viagem
FW3|09|FW3_DTFIM|D|8|0|Data Final|Data Final da Viagem
FW3|10|FW3_CLIENT|C|6|0|Cliente|Código do Cliente
FW3|11|FW3_LOJA|C|2|0|Loja|Loja do Cliente
FW3|12|FW3_NOME|C|80|0|Nome|Nome do Cliente
FW3|13|FW3_USER|C|15|0|Usuário|Usuário do Solicitante
FW3|14|FW3_STATUS|C|1|0|Status|Status da Solicitação
FW3|15|FW3_PARTIC|C|50|0|Participante|Participante
FW3|16|FW3_WFKID|C|100|0|Workflow ID|Workflow ID
FW3|17|FW3_MOTVFL|M|10|0|Motivo Rej.|Motivo da Rejeição
--- ### FW4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW4|01|FW4_FILIAL|C|6|0|Filial|Filial
FW4|02|FW4_SOLICI|C|10|0|ID Solic.|Código da Solicitação
FW4|03|FW4_ITEM|C|2|0|Item|Item da Solicitação
FW4|04|FW4_TIPO|C|1|0|Tipo|Tipo do Serviço
FW4|05|FW4_OBS|M|10|0|Detalhes|Detalhes do Serviço
--- ### FW5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW5|01|FW5_FILIAL|C|6|0|Filial|Filial do Sistema
FW5|02|FW5_SOLICI|C|10|0|ID Solici.|Código da Solicitação
FW5|03|FW5_ITEM|C|2|0|Item|Item da Solicitação
FW5|04|FW5_PARTIC|C|6|0|Participante|Código do Participante
FW5|05|FW5_NOME|C|50|0|Nome|Nome do Participante
FW5|06|FW5_ADIANT|L|1|0|Adiantamento|Adiantamento
FW5|07|FW5_VALOR|N|16|2|Valor Adiant|Valor do Adiantamento
--- ### FW6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW6|01|FW6_FILIAL|C|6|0|Filial|Filial do Sistema
FW6|02|FW6_SOLICI|C|10|0|ID Solic|Código da Solicitação
FW6|03|FW6_ITEM|C|2|0|Item|Item da Solicitação
FW6|04|FW6_CC|C|9|0|Centro Custo|Centro de Custo
FW6|05|FW6_DESC|C|40|0|Descrição|Descrição do CC
FW6|06|FW6_PORCEN|N|6|2|Porcentagem|Porcentagem do CC
FW6|07|FW6_ITECTA|C|9|0|Item Contab.|Item Contabil
FW6|08|FW6_DSITCT|C|50|0|Descrição|Descrição Item Contabil
FW6|09|FW6_CLVL|C|9|0|Classe Valor|Classe de Valor
FW6|10|FW6_DSCLVL|C|50|0|Descrição|Descrição Classe de Valor
--- ### FW7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW7|01|FW7_FILIAL|C|6|0|Filial|Filial do Sistema
FW7|02|FW7_VIAGEM|C|10|0|Viagem|Código da Viagem
FW7|03|FW7_ITEM|C|2|0|Item|Item da Viagem
FW7|04|FW7_SUBITM|C|2|0|SubItem|SubItem da Viagem
FW7|05|FW7_CODORI|C|10|0|Origem|Origem da Viagem
FW7|06|FW7_DESORI|C|40|0|Desc.Origem|Descrição de Origem
FW7|07|FW7_CODDES|C|10|0|Destino|Código de Destino
FW7|08|FW7_DESDES|C|40|0|Desc.Destino|Descrição do Destino
FW7|09|FW7_OBS|C|40|0|Observação|Observação
FW7|10|FW7_DTINIC|D|8|0|Data Inicial|Data Inicial
--- ### FW8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW8|01|FW8_FILIAL|C|6|0|Filial|Filial do sistema
FW8|02|FW8_LOTE|C|6|0|Lote|Codigo Lote Serasa
FW8|03|FW8_DTLOTE|D|8|0|Data|Data de Geração Lote
FW8|04|FW8_DTARQ|D|8|0|Data Arquivo|Data Geração Arquivo
FW8|05|FW8_DTPROC|D|8|0|Data Proces.|Data Process. Arquivo
FW8|06|FW8_TIPO|C|1|0|Tp. Lote|Tipo do Lote Serasa
FW8|07|FW8_ARQSER|C|6|0|Arquivo|Cod. Arquivo Serasa
--- ### FW9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FW9|01|FW9_FILIAL|C|6|0|Filial|Filial do sistema
FW9|02|FW9_LOTE|C|6|0|Lote|Codigo Lote Serasa
FW9|03|FW9_IDDOC|C|32|0|ID Docto|ID do título
FW9|04|FW9_PREFIX|C|3|0|Prefixo|Prefixo Título
FW9|05|FW9_NUM|C|9|0|Número|Número Título
FW9|06|FW9_PARCEL|C|3|0|Parcela|Parcela Título
FW9|07|FW9_TIPO|C|3|0|Tipo|Tipo Título
FW9|08|FW9_CLIENT|C|6|0|Cliente|Cliente
FW9|09|FW9_LOJA|C|2|0|Loja|Loja
FW9|10|FW9_VALOR|N|16|2|Valor|Valor Documento Origem
FW9|11|FW9_FILORI|C|6|0|Filial Ori.|Filial do Original
FW9|12|FW9_OBS|C|140|0|Observação|Observação
FW9|13|FW9_IDTITU|C|16|0|Id Titulo|Identificação do Titulo
--- ### FWA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWA|01|FWA_FILIAL|C|6|0|Filial|Filial do sistema
FWA|02|FWA_IDDOC|C|32|0|ID Docto|ID do título
FWA|03|FWA_PREFIX|C|3|0|Prefixo|Prefixo Título
FWA|04|FWA_NUM|C|9|0|Número|Número Título
FWA|05|FWA_PARCEL|C|3|0|Parcela|Parcela Título
FWA|06|FWA_TIPO|C|3|0|Tipo|Tipo Título
FWA|07|FWA_CLIENT|C|6|0|Cliente|Cliente
FWA|08|FWA_LOJA|C|2|0|Loja|Loja
FWA|09|FWA_SEQ|C|3|0|Sequência|Sequência de ocorrência
FWA|10|FWA_STATUS|C|1|0|Status|Status no processo
FWA|11|FWA_FILORI|C|6|0|Filial Ori.|Filial do Original
--- ### FWB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWB|01|FWB_FILIAL|C|6|0|Filial|Filial do sistema
FWB|02|FWB_IDDOC|C|32|0|ID Docto|ID do título
FWB|03|FWB_SEQ|C|3|0|Sequência|Sequência de ocorrência
FWB|04|FWB_LOTE|C|6|0|Lote|Codigo Lote Serasa
FWB|05|FWB_OCORR|C|1|0|Ocorrência|Ocorrência
FWB|06|FWB_DESCR|C|20|0|Descr. Mov.|Descrição do Movimento
FWB|07|FWB_DTOCOR|D|8|0|Dt. Ocor.|Data da ocorrência
FWB|08|FWB_VALOR|N|16|2|Valor|Valor Documento Origem
FWB|09|FWB_CODERR|C|3|0|Cod. Erro|Código Erro (Serasa)
FWB|10|FWB_DTSERA|D|8|0|Dt.Serasa|Data evento Serasa
--- ### FWC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWC|01|FWC_FILIAL|C|6|0|Filial|Filial do Sistema
FWC|02|FWC_CODIGO|C|10|0|Identific.|Identificador
FWC|03|FWC_DESPES|C|6|0|Despesa|Código da Despesa
FWC|04|FWC_CLASS|C|1|0|Classific|Classificação
FWC|05|FWC_ORIGEM|C|1|0|Origem Cad|Origem do Cadastro
FWC|06|FWC_DESCDP|C|40|0|Desc.Desp|Descricao da Despesa
--- ### FWD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWD|01|FWD_FILIAL|C|6|0|Filial|Filial do Sistema
FWD|02|FWD_CODIGO|C|10|0|Identific|Identificador
FWD|03|FWD_ITEM|C|4|0|Item|Item
FWD|04|FWD_NACION|C|1|0|Nacional|Despesa Nacional
FWD|05|FWD_LOCAL|C|4|0|Cód.Local|Código do Local
FWD|06|FWD_DESCLC|C|40|0|Desc. Local|Descricao do Local
--- ### FWI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWI|01|FWI_FILIAL|C|6|0|Filial|Filial do Sistema
FWI|02|FWI_PREFIX|C|3|0|Prefixo|Prefixo do Título
FWI|03|FWI_NUMERO|C|9|0|Numero|Numero do Título
FWI|04|FWI_PARCEL|C|3|0|Parcela|Parcela do Título
FWI|05|FWI_TIPO|C|3|0|Tipo|Tipo do Título
FWI|06|FWI_CLIENT|C|6|0|Cliente|Cliente
FWI|07|FWI_LOJA|C|2|0|Loja|Loja
FWI|08|FWI_SEQ|C|3|0|Sequencia|Sequencia
FWI|09|FWI_FILORI|C|6|0|Filial Orig|Filial Origem
FWI|10|FWI_DTMOVI|D|8|0|Dt. Moviment|Data do Movimento
FWI|11|FWI_LA|C|1|0|Ident.Lanc|Identificação Lançamento
FWI|12|FWI_LANPAD|C|3|0|Cod. Lanc|Codigo Lançamento Padrão
FWI|13|FWI_VLRORI|N|16|2|Vlr Original|Valor Original
FWI|14|FWI_VALOR|N|16|4|Vlr Moviment|Valor da movimentação
FWI|15|FWI_DESCON|N|16|5|Vlr Desconto|Valor do Desconto
FWI|16|FWI_IOF|N|16|5|IOF|IOF
FWI|17|FWI_SITUAC|C|1|0|Situação|Situação Cobrança Atual
FWI|18|FWI_SITANT|C|1|0|Situação Ant|Situação Anterior
FWI|19|FWI_BANCO|C|3|0|Banco|Banco atual
FWI|20|FWI_AGENCI|C|5|0|Agencia|Agencia
FWI|21|FWI_CONTA|C|10|0|Conta|Conta bancária
FWI|22|FWI_BCOANT|C|3|0|Banco Ant|Banco Anterior
FWI|23|FWI_AGEANT|C|5|0|Agencia Ant|Agencia Anterior
FWI|24|FWI_CONANT|C|10|0|Conta Ant|Conta Bancária Anterior
FWI|25|FWI_CONTRA|C|15|0|Contrato|Contrato
FWI|26|FWI_IDMOV|C|32|0|Id Movimento|Id Movimento
FWI|27|FWI_NUMBOR|C|6|0|Num Bordero|Numero do Bordero
FWI|28|FWI_IDF71|C|35|0|ID Pix|ID da Transação PIX
FWI|29|FWI_VLRBOR|N|16|4|Vlr. Borderô|Valor que compôs Borderô
FWI|30|FWI_DESTIT|N|16|5|Vlr Desc Tit|Vlr do desconto do título
FWI|31|FWI_IOFTIT|N|16|5|IOF Título|IOF do título
--- ### FWM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWM|01|FWM_FILIAL|C|6|0|Filial|Filial do sistema
FWM|02|FWM_PROCES|C|6|0|Processo|Processo Aglut.
FWM|03|FWM_SUBPRO|C|9|0|Sub Processo|SubProc. Aglut.
FWM|04|FWM_FK7ORI|C|32|0|Tít. Ori.|Título Origem
FWM|05|FWM_FK7DES|C|32|0|Tít. Agl.|Tít. Aglut.
FWM|06|FWM_STATUS|C|1|0|Status|Status
FWM|07|FWM_EMISS|D|8|0|Data Emissão|Data de Emissão
--- ### FWN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWN|01|FWN_FILIAL|C|6|0|Filial|Filial do Sistema
FWN|02|FWN_CODIGO|C|10|0|Codigo|Codigo da Conciliação
FWN|03|FWN_ITEM|C|4|0|Item|Item
FWN|04|FWN_EBTA|C|15|0|N. Cartão|Número do Cartão
FWN|05|FWN_TPREG|C|1|0|Tipo Reg|Tipo do Registro
FWN|06|FWN_TIPO|C|1|0|Tipo Trans.|Tipo da Transação
FWN|07|FWN_NUMFAT|C|9|0|Num. Fatura|Número da Fatura
FWN|08|FWN_DTFAT|D|8|0|Data Fat.|Data de Faturamento
FWN|09|FWN_PASSAG|C|50|0|Passageiro|Nome do Passageiro
FWN|10|FWN_CCUSTO|C|9|0|Centro Custo|Centro de Custo
FWN|11|FWN_VTRANS|N|16|2|Valor Trans.|Valor da Transação
FWN|12|FWN_STRANS|C|1|0|Sinal Trans.|Sinal da Transação
FWN|13|FWN_BILHET|C|14|0|Bilhete|Número do Bilhete
FWN|14|FWN_TXEMB|N|16|2|Tx. Embarque|Taxa de Embarque
FWN|15|FWN_STXEMB|N|16|2|Sinal Taxa|Sinal da Taxa de Embarque
FWN|16|FWN_VALOR|N|16|2|Valor Passag|Valor da Passagem
FWN|17|FWN_SNVAL|C|1|0|Sinal do Val|Sinal do Valor Passagem
FWN|18|FWN_DEPART|C|10|0|Departamento|Departamento
FWN|19|FWN_MATRIC|C|10|0|Matricula|Código da Matricula
FWN|20|FWN_IDRESE|C|10|0|ID Viagem|Identificador da Viagem
FWN|21|FWN_VIAGEM|C|10|0|Viagem|Viagem
FWN|22|FWN_CONFER|C|10|0|Conferencia|Conferencia de Viagem
FWN|23|FWN_MOEDA|N|1|0|Moeda|Código da Moeda
FWN|24|FWN_TPDESP|C|1|0|Tipo Despesa|Tipo de Despesa
FWN|25|FWN_TPESTA|C|2|0|Tipo Estabel|Tipo de Estabelecimento
FWN|26|FWN_DESCRI|C|120|0|Descrição|Descrição
FWN|27|FWN_ARQUIV|C|90|0|Arquivo|Nome do Arquivo
--- ### FWO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWO|01|FWO_FILIAL|C|6|0|Filial|Filial do Sistema
FWO|02|FWO_LOTE|C|9|0|Processo|Processo
FWO|03|FWO_NUMBOR|C|6|0|Borderô|Número do borderô
FWO|04|FWO_ARQUIV|C|50|0|Arq. gerado|Arquivo gerado
FWO|05|FWO_DTENV|D|8|0|Data envio|Data envio da integração
FWO|06|FWO_HRENV|C|5|0|Hora envio|Hora envio da integração
FWO|07|FWO_USUAR|C|6|0|Usuário|Usuário logado
FWO|08|FWO_NOMUSE|C|50|0|Nome Usuário|Nome do Usuário
FWO|09|FWO_IDTCB|C|10|0|ID|ID TCB
FWO|10|FWO_STATUS|C|1|0|Status|Status integração
FWO|11|FWO_CODRET|N|3|0|Retorno|Código retorno integração
FWO|12|FWO_JSONRT|M|10|0|Mensagem|Json retorno
--- ### FWP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWP|01|FWP_FILIAL|C|6|0|Filial|Filial do sistema
FWP|02|FWP_CODCRT|C|6|0|Cód. Layout|Código do Layout
FWP|03|FWP_DESCRI|C|40|0|Descrição|Descrição do layout
FWP|04|FWP_STATUS|C|1|0|Status|Status do layout
FWP|05|FWP_TXTSAU|C|60|0|Saudação|Texto da Saudação
FWP|06|FWP_TXTCRT|M|500|0|Txt Carta|Texto da Carta
FWP|07|FWP_TXTCON|M|500|0|Conclusão|Texto de Conclusão
FWP|08|FWP_ENVIO|C|1|0|Tp Envio|Tipo de Envio
FWP|09|FWP_POSVER|N|4|0|Pos Vertical|Pos Vertical do Endereço
FWP|10|FWP_POSHOR|N|4|0|P Horizontal|P Horizontal do Endereço
FWP|11|FWP_TXTASS|C|60|0|Assunto|Assunto email boleto
--- ### FWQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWQ|01|FWQ_FILIAL|C|6|0|Filial|Filial do sistema
FWQ|02|FWQ_LAYOUT|C|6|0|Cód Layout|Código do Layout
FWQ|03|FWQ_FILTRA|C|254|0|Expressão|Exp de filtros adicionais
--- ### FWS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWS|01|FWS_FILIAL|C|6|0|Filial|Filial do Sistema
FWS|02|FWS_LAYOUT|C|6|0|Cód. Layout|Código do Layout
FWS|03|FWS_SEQ|C|4|0|Sequência|Sequência de Campos
FWS|04|FWS_CAMPO|C|10|0|Campo|Campo do título
FWS|05|FWS_DESCRI|C|15|0|Descrição|Descrição do Campo
--- ### FWT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWT|01|FWT_FILIAL|C|6|0|Filial|Filial do Sistema
FWT|02|FWT_LAYOUT|C|6|0|Cód. Layout|Código do Layout
FWT|03|FWT_DTENVI|D|8|0|Dt Envio|Data de Envio
FWT|04|FWT_CHAVE|C|32|0|Chave|Chave do Documento
FWT|05|FWT_PROCES|C|32|0|Processo|Número do Processo
FWT|06|FWT_DTREFE|D|8|0|Dt. Referenc|Data de Referencia
FWT|07|FWT_FILLYT|C|6|0|Fil. Layout|Filial do Layout
FWT|08|FWT_STATUS|C|1|0|Status|Status do envio do email
--- ### FWZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FWZ|01|FWZ_FILIAL|C|6|0|Filial|Filial do Sistema
FWZ|02|FWZ_PROC|C|6|0|Codigo|Codigo do processamento
FWZ|03|FWZ_ITCLI|C|4|0|Item Cliente|Item do Cliente
FWZ|04|FWZ_ITTIT|C|4|0|Item Titulo|Item do Titulo Financeiro
FWZ|05|FWZ_DOC|C|9|0|Num. Docto|Numero do Documento/Nota
FWZ|06|FWZ_SERIE|C|3|0|Serie|Serie da Nota Fiscal
FWZ|07|FWZ_ITEM|C|4|0|Item|Item da Nota Fiscal
FWZ|08|FWZ_CODPRO|C|15|0|Cod Prod|Código do Produto
FWZ|09|FWZ_DESPRO|C|70|0|Desc Prod|Descrição do Produto
FWZ|10|FWZ_PERCEC|N|14|8|Percentual|Percentual do Rateio
FWZ|11|FWZ_VLRRAT|N|16|2|Valor Rat|Valor Rateado
FWZ|12|FWZ_SLDRAT|N|16|2|Saldo Rat|Saldo Rateado
FWZ|13|FWZ_BXRAT|N|16|2|Vlr Bx Rat|Valor da Baixa Rateado
FWZ|14|FWZ_LA|C|1|0|Ident. Lanc|Identificador de LA
--- ### FX0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FX0|01|FX0_FILIAL|C|6|0|Filial|Filial do Sistema
FX0|02|FX0_CODIGO|C|6|0|ID PF|Identificação PF
FX0|03|FX0_CODSIA|C|12|0|Código SIAFI|Código Documento SIAFI
FX0|04|FX0_UGEMIT|C|6|0|UG Emitente|Unidade Gestora Emitente
FX0|05|FX0_UGDESC|C|50|0|Desc. UG|Descrição Unidade Gestora
FX0|06|FX0_UGFAVO|C|6|0|UG Favorec.|Unidade Gestora Favorec.
FX0|07|FX0_UGDSFV|C|50|0|Desc. UF Fav|Descrição UG Favorecida
FX0|08|FX0_STATUS|C|1|0|Status PF|Status PF
FX0|09|FX0_DTINCL|D|8|0|Dt. Inclusao|Data inclusão PF
FX0|10|FX0_DTAPRV|D|8|0|Dt.Aprovação|Data Aprovação PF
FX0|11|FX0_DTLIB|D|8|0|Dt.Liberação|Data de Liberação da PF
FX0|12|FX0_OBS|M|6|0|Observação|Observação Documento
--- ### FX1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FX1|01|FX1_FILIAL|C|6|0|Filial|Filial do Sistema
FX1|02|FX1_CODIGO|C|6|0|Código PF|Código PF
FX1|03|FX1_ITEM|C|4|0|Item|Item
FX1|04|FX1_SITUAC|C|6|0|Situação|Situação da PF
FX1|05|FX1_NSITUA|C|100|0|Desc.Situac.|Descrição da Situação
FX1|06|FX1_VINCPA|C|3|0|Vinc.Pag.|Vinculação de Pagamento
FX1|07|FX1_FONREC|C|10|0|Fonte Rec.|Fonte de Recursos
FX1|08|FX1_NFONRE|C|50|0|Dsc.Font.Rec|Desc. Fonte de Recursos
FX1|09|FX1_CATGAS|C|6|0|Cat. Gastos|Categoria de Gastos
FX1|10|FX1_NCATGA|C|55|0|Desc.Cat.Gas|Descrição Cat. Gastos
FX1|11|FX1_DTPREV|D|8|0|Dt. Prevista|Data Prevista
FX1|12|FX1_VALOR|N|16|2|Valor. Sol.|Valor Solicitado
--- ### FX2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FX2|01|FX2_FILIAL|C|6|0|Filial|Filial do Sistema
FX2|02|FX2_CODIGO|C|6|0|Codigo PF|Codigo PF
FX2|03|FX2_CODDH|C|6|0|Código DH|Código Documento Hábil
FX2|04|FX2_VLRDH|N|16|2|Valor DH|Valor DH
FX2|05|FX2_STATUS|C|1|0|Status DH|Status DH
--- ### FXV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FXV|01|FXV_FILIAL|C|6|0|Filial|Filial do sistema
FXV|02|FXV_CODIGO|C|6|0|Código|Código do imóvel
FXV|03|FXV_NUMIMO|C|3|0|Núm Imóvel|Número do Imóvel
FXV|04|FXV_ATIVO|C|1|0|Ativo|Cafir Ativo
FXV|05|FXV_CAFIR|C|8|0|CAFIR c/ DV|CAFIR com DV
FXV|06|FXV_CODPES|C|6|0|Proprietário|Proprietário Contribuinte
FXV|07|FXV_NOME|C|50|0|Nome Imóvel|Nome do Imóvel
FXV|08|FXV_END|C|150|0|Endereço|Endereço do Imóvel
FXV|09|FXV_NUM|N|6|0|Número|Núm do imóvel
FXV|10|FXV_COMPL|C|50|0|Complemento|Compl do endereço
FXV|11|FXV_BAIRRO|C|50|0|Bairro|Bairro do imóvel
FXV|12|FXV_UF|C|2|0|Estado|Estado
FXV|13|FXV_CODMUN|C|5|0|Cód. Munic.|Cód. do município no IBGE
FXV|14|FXV_CEP|C|8|0|Cep|Cód. Ender. Postal
FXV|15|FXV_TIPOEX|C|1|0|Exploração|Tipo de Exploração
FXV|16|FXV_PARTIC|N|6|2|Particip.(%)|Percentual de Participaçã
FXV|17|FXV_CAEPF|C|14|0|CAEPF|CAEPF
FXV|18|FXV_VERSAO|C|4|0|Versão|Versão
--- ### FS0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS0|01|FS0_FILIAL|C|6|0|Filial|Filial do Sistema
FS0|02|FS0_CODIGO|C|40|0|Código|Código Palavra Reservada
FS0|03|FS0_IDIOMA|C|3|0|Idioma|Idioma da Mensagem
FS0|04|FS0_DESCRI|M|80|0|Mensagem|Mensagem da P. Reservada
FS0|05|FS0_CODDES|C|6|0|Cód.Mens.|Código da Mensagem
--- ### FS1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS1|01|FS1_FILIAL|C|6|0|Filial|Filial do Sistema
FS1|02|FS1_CODIGO|C|3|0|Cod. Excecao|Cod. Excecao Despesa
FS1|03|FS1_ITEM|C|2|0|Item|Item do Custo
FS1|04|FS1_VLINI|N|14|2|Vlr. Inicial|Valor Inicial
FS1|05|FS1_VLFIM|N|14|2|Vlr. Final|Valor Final
FS1|06|FS1_PERCAP|N|6|2|% Aplicado|Percentual Aplicado
FS1|07|FS1_VLRCOB|N|14|2|Vlr. Cobrado|Valor Cobrado
FS1|08|FS1_SEQUEN|C|6|0|Sequencia|Sequência da Versão
--- ### FS2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS2|01|FS2_FILIAL|C|6|0|Filial|Filial do Sistema
FS2|02|FS2_CODIGO|C|3|0|Codigo|Codigo do Idioma
FS2|03|FS2_DESCRI|C|20|0|Descricao|Descricao do Idioma
--- ### FS3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS3|01|FS3_FILIAL|C|6|0|Filial|Filial do Sistema
FS3|02|FS3_CODIGO|C|6|0|Código|Código da Exceção
FS3|03|FS3_ITEM|C|2|0|Item|Item da Tabela de Honorar
FS3|04|FS3_CLASSE|C|1|0|Classe Tmkp.|Classe do Timekeeper
FS3|05|FS3_CATEG|C|4|0|Categoria|Codigo de Categoria
FS3|06|FS3_AREAPR|C|4|0|Area Pratica|Area de Pratica
FS3|07|FS3_TMK|C|8|0|Timekeeper|Codigo de Timekeeper
FS3|08|FS3_VLRREA|N|12|2|Valor Real|Valor Real do Honorario
FS3|09|FS3_PERC|N|6|2|Percentual|Percentual abatimento
FS3|10|FS3_VLRCOB|N|12|2|Vlr.a Cobrar|Valor a Cobrar
FS3|11|FS3_VLRVIS|N|14|2|Vlr.Efetivo|Valor Efetivo
FS3|12|FS3_SEQUEN|C|6|0|Sequencia|Sequencia da Versão
--- ### FS4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS4|01|FS4_FILIAL|C|6|0|Filial|Filial do Sistema
FS4|02|FS4_CONTRA|C|10|0|Contrato|Numero do contrato
FS4|03|FS4_SEQ|C|6|0|Versao|Versao
FS4|04|FS4_CONDFI|C|2|0|Cond.Financ.|Cond. Fin. do Contrato
FS4|05|FS4_SEQUEN|C|3|0|Sequencia|Sequencia
FS4|06|FS4_FLGLIM|C|1|0|Flag Limitac|Flag de limitacao
FS4|07|FS4_LIMITE|N|14|2|Limite|Limite da Cond.Financ.
FS4|08|FS4_TPFAIX|C|1|0|Tp. de Faixa|Tipo do limite da faixa
FS4|09|FS4_FXINI|N|12|2|FaixaInicial|Faixa Inicial
FS4|10|FS4_FXFIN|N|12|2|Faixa Final|Faixa Final
FS4|11|FS4_PERC|N|6|2|% a Cobrar|Percentual a ser cobrado
FS4|12|FS4_VLRUNI|N|14|2|Vl.Unit/Cobr|Valor Unitario a Cobrar
FS4|13|FS4_VLRTOT|N|14|2|Vlr.Tot.Cobr|Valor Total a Cobrar
FS4|14|FS4_VLRTIT|N|14|2|Vlr. Titulo|Valor do Titulo
FS4|15|FS4_DTEMIS|D|8|0|Dt. Emissao|Data de Emissao do Titulo
FS4|16|FS4_NUMPFA|C|6|0|Pre-Fatura|Numero da Pre-Fatura
FS4|17|FS4_DTPFAT|D|8|0|Dt.Pre-Fat.|Data da Pre-Fatura
FS4|18|FS4_NUMFAT|C|6|0|Fatura|Numero da Fatura
FS4|19|FS4_DTFAT|D|8|0|Dta. Faturam|Dta. de Fat. do Titulo
FS4|20|FS4_VLRFAT|N|12|2|Vlr.Faturado|Valor ja Faturado
FS4|21|FS4_HORFAT|N|18|7|Horas Fat.|Horas Faturadas
FS4|22|FS4_APONTA|C|1|0|Aponta?|Considera Apontamento ?
FS4|23|FS4_FATMAX|C|1|0|Faturamento?|Flag de faturamento ?
FS4|24|FS4_FATDES|C|1|0|Fat. Despesa|Fatura despesas?
--- ### FS5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS5|01|FS5_FILIAL|C|6|0|Filial|Filial do Sistema
FS5|02|FS5_CODIGO|C|3|0|Cod.Rateio|Codigo do Rateio
FS5|03|FS5_ASSUND|C|11|0|Ass.Destino|Cod.Assunto de Destino
FS5|04|FS5_PERC|N|6|2|Perc.Rateio|Percentual de Rateio
FS5|05|FS5_CDCLID|C|6|0|Clie.Destino|Codigo de Cliente Destino
FS5|06|FS5_LOJAD|C|2|0|Loja Destino|Loja do Cliente Destino
FS5|07|FS5_CONTRD|C|10|0|Cont.Destino|Num.Contrato de Destino
FS5|08|FS5_VALORI|C|1|0|Valorização|Valorização do Rateio
FS5|09|FS5_TPAPON|C|1|0|Apontamento|Tipo de Apontamento
--- ### FS6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS6|01|FS6_FILIAL|C|6|0|Filial|Filial do Sistema
FS6|02|FS6_CONTRA|C|10|0|Contrato|Cod. do Contrato
FS6|03|FS6_ASSUNT|C|11|0|Assunto|Cod. do Assunto
FS6|04|FS6_TIMEK|C|8|0|Codigo|Cod. do Timekeeper
FS6|05|FS6_NOMTMK|C|30|0|Nome Adotado|Apel. do Timekeeper
--- ### FS7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS7|01|FS7_FILIAL|C|6|0|Filial|Filial do Sistema
FS7|02|FS7_CODIGO|C|4|0|Junc.Assunto|Codigo Juncao de Assuntos
FS7|03|FS7_ASSUNT|C|11|0|Cod.Assunto|Codigo do Assunto
FS7|04|FS7_DESASS|C|40|0|Desc.Assunto|Descricao do Assunto
FS7|05|FS7_CONTAT|C|6|0|Contato|Contato
FS7|06|FS7_CONTRA|C|10|0|Contrato|Numero do Contrato
--- ### FS8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS8|01|FS8_FILIAL|C|6|0|Filial|Filial do Sistema
FS8|02|FS8_DATA|D|8|0|Data|Data da Ocorrencia
FS8|03|FS8_CODCRI|C|3|0|Cod.Criterio|Codigo do Criterio
FS8|04|FS8_ALIAS|C|3|0|AliasArquivo|Alias do Arquivo
FS8|05|FS8_IDPAI|C|8|0|Id.Reg.Orig.|Ident. Registro Original
FS8|06|FS8_VLROP|N|18|7|Vlr.Operacao|Valor da Operacao
FS8|07|FS8_FATUR|C|1|0|Flag Faturav|Flag de Faturavel
FS8|08|FS8_ORIGEM|C|8|0|Origem|Origem do Apontamento
--- ### FS9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FS9|01|FS9_FILIAL|C|6|0|Filial|Filial do Sistema
FS9|02|FS9_TIPO|C|1|0|Tipo|Tipo de Sumario
FS9|03|FS9_NUMERO|C|6|0|Número|Número da Pré-Fat./Fatura
FS9|04|FS9_SEQ|C|3|0|Sequência|Sequência do registro
FS9|05|FS9_TIPSUM|C|2|0|Tp.Sumário|Tipo de Sumário
FS9|06|FS9_CODIGO|C|11|0|Cód.Sumariz.|Código do Sumarizador
FS9|07|FS9_QTRHON|N|10|2|Horas Reais|Qtde. Horas Reais
FS9|08|FS9_VLRHON|N|12|2|Vlr.Real Hon|Valor Real de Honorários
FS9|09|FS9_QTSHON|N|10|2|Saldo Horas|Saldo de Horas
FS9|10|FS9_VLSHON|N|12|2|Vlr.Sld.Hon.|Valor do Saldo de Honor.
FS9|11|FS9_QTRDES|N|10|2|Qtd. Despesa|Qtde. Real de Desp.
FS9|12|FS9_VLRDES|N|12|2|Vlr. Despesa|Vlr. Real de Despesas
FS9|13|FS9_QTSDES|N|10|2|Saldo Desp.|Saldo de Despesas
FS9|14|FS9_VLSDES|N|12|2|Vlr.Sld.Desp|Valor do Saldo de Desp.
FS9|15|FS9_QTEVHO|N|10|2|Qtd.Ev.Honor|Qtde. de Eventos de Honor
FS9|16|FS9_VLEVHO|N|12|2|Vlr. Ev. Hon|Valor de Eventos de Honor
FS9|17|FS9_QTEVDE|N|10|2|Qt.Ev. Desp.|Qtde. de Eventos de Desp.
FS9|18|FS9_VLEVDE|N|12|2|Vlr.Ev.Desp.|Valor dos Ev. Despesas
FS9|19|FS9_QHRTAC|N|12|2|Hr.Retif.Acr|Horas Retif. Acréscimo
FS9|20|FS9_VHRTAC|N|12|2|V.Hr.Ret.Acr|Valor Horas Ret. Acrésc.
FS9|21|FS9_QHRTDC|N|12|2|Hr.Re. Decr.|Horas Retif. Decréscimo
FS9|22|FS9_VHRTDC|N|12|2|V.Hr.Ret.Dec|Vlr.Horas Ret. Decrescimo
FS9|23|FS9_QDRTAC|N|12|2|Desp.Ret.Ac.|Qtde.Despesas Ret. Acrésc
FS9|24|FS9_VDRTAC|N|12|2|Vl.Dsp.Ret.A|Vlr.Desp.Retif. Acréscimo
FS9|25|FS9_QDRTDC|N|12|2|Dsp.Ret.Decr|Qtde.Despesas Ret.Decrésc
FS9|26|FS9_VDRTDC|N|12|2|Vl.Dsp.Ret.D|Vlr.Desp.Retif.Decréscimo
--- ### FSA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSA|01|FSA_FILIAL|C|6|0|Filial|Filial do Sistema
FSA|02|FSA_CODIGO|C|8|0|Codigo TK|Codigo do Timekeeper
FSA|03|FSA_NOME|C|20|0|Nome|Nome do TimeKeeper
FSA|04|FSA_SOBREN|C|40|0|Sobrenome|Sobrenome do timekeeper
FSA|05|FSA_APELID|C|30|0|Nome Adotado|Nome Adotado
FSA|06|FSA_EMAIL|C|45|0|E-mail|E-mail
FSA|07|FSA_SIGLA|C|3|0|Sigla|Sigla do Timekeeper
FSA|08|FSA_CLASSE|C|1|0|Classe|Classe do Timekeeper
FSA|09|FSA_LOCAL|C|4|0|Localidade|Localidade do Timekeeper
FSA|10|FSA_CATEG|C|4|0|Categoria|Categoria do TimeKeeper
FSA|11|FSA_DEPTO|C|4|0|Departamento|Departamento TimeKeeper
FSA|12|FSA_ARPRPR|C|4|0|Pratica|Pratica Principal
FSA|13|FSA_PERCUS|C|1|0|Permis.Custo|Permissao de Custo
FSA|14|FSA_DTENTR|D|8|0|Data Entrada|Data da Entrada Empresa
FSA|15|FSA_DTSAI|D|8|0|Data Saida|Data da Saida da Empresa
FSA|16|FSA_VIGINI|D|8|0|Vig.Inicial|Dta. Inicial da Vig. Cad.
FSA|17|FSA_VIGFIN|D|8|0|Vig. Final|Dta. Vig. Final Cadastro
FSA|18|FSA_SEQ|C|6|0|Sequencia|Sequencia de Alteracoes
FSA|19|FSA_TETOAD|N|12|2|Teto Adiant.|Teto de Adiantamento
FSA|20|FSA_QTDEAD|N|3|0|Qtde. Adiant|Quant. de Adiantamentos
--- ### FSB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSB|01|FSB_FILIAL|C|6|0|Filial|Filial do Sistema
FSB|02|FSB_CONTRA|C|10|0|Num.Contrato|Numero do Contrato
FSB|03|FSB_CODIGO|C|11|0|Cod.Assunto|Codigo do Assunto
FSB|04|FSB_DESCRI|C|144|0|Descricao|Descricao do Assunto
FSB|05|FSB_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FSB|06|FSB_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FSB|07|FSB_CONTAT|C|6|0|Contato|Contato no Cliente
FSB|08|FSB_NOMCON|C|30|0|Nome Contato|Nome do Contato
FSB|09|FSB_TMKRES|C|8|0|Tk.responsav|Timekeeper Responsavel
FSB|10|FSB_NTKRES|C|30|0|Nome Tk.Resp|Nome Timek. Responsavel
FSB|11|FSB_STATUS|C|1|0|Situacao|Situacao do Assunto
FSB|12|FSB_LOCAL|C|4|0|Localidade|Localidade do Assunto
FSB|13|FSB_DEPTO|C|4|0|Departamento|Codigo do Departamento
FSB|14|FSB_AREAPR|C|4|0|Area Pratica|Codigo de Area de Pratica
FSB|15|FSB_TMKIND|C|8|0|Tk.Indicador|Timekeeper Indicador
FSB|16|FSB_NTKIND|C|30|0|Nome Tk. Ind|Nome Timek. Indicador
FSB|17|FSB_TMKREV|C|8|0|Tk.Revisor|Timekeeper revisor
FSB|18|FSB_NTKREV|C|30|0|Nome Tk.Rev.|Nome Timek. Revisor
FSB|19|FSB_VARA|C|30|0|Vara|Descricao-Vara
FSB|20|FSB_FORO|C|40|0|Foro/comarca|Foro ou comarca
FSB|21|FSB_PROCES|C|20|0|Num.Processo|Numero do processo
FSB|22|FSB_CLASER|C|3|0|Classif.Serv|Classif. de Serviços
FSB|23|FSB_LINGUA|C|3|0|Idioma|Idioma do Assunto
FSB|24|FSB_DESLIN|C|20|0|Desc.Idioma|Descricao do Idioma
FSB|25|FSB_OBSERV|M|80|0|Observacoes|Observacoes
FSB|26|FSB_DTABER|D|8|0|Dt.Abertura|Data de Abertura Assunto
FSB|27|FSB_DLIMAP|D|8|0|Limite Apont|Dt. Limite de Apont.
FSB|28|FSB_DTMOD|D|8|0|Dt.Modificac|Data da Modificacao
FSB|29|FSB_JUNCAO|C|4|0|Cod.Juncao|Codigo da Juncao
FSB|30|FSB_DESJUN|C|40|0|Descr.Juncao|Descricäo da Juncäo
FSB|31|FSB_TRANSF|C|22|0|Ass.Destino|Assunto Destino
FSB|32|FSB_OK|C|2|0|OK|OK
FSB|33|FSB_CODOBS|C|6|0|Cod.Obs.|Codigo da Observacao
FSB|34|FSB_VLRASS|N|12|2|Vlr. Assunto|Valor do Assunto
FSB|35|FSB_CODETA|C|3|0|Código Etapa|Código da Etapa
FSB|36|FSB_DSCETA|C|40|0|Descrição|Descrição das Etapas
--- ### FSC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSC|01|FSC_FILIAL|C|6|0|Filial|Filial do Sistema
FSC|02|FSC_CODIGO|C|10|0|Numero|Numero do Contrato
FSC|03|FSC_DESCRI|C|60|0|Descricao|Descricao contrato/adendo
FSC|04|FSC_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FSC|05|FSC_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FSC|06|FSC_RSCLI|C|60|0|Razao Social|Razao Social
FSC|07|FSC_CONTAT|C|6|0|Contato|Contato do Cliente
FSC|08|FSC_NOMCON|C|30|0|Nome Contato|Nome do Contato
FSC|09|FSC_TMKRES|C|8|0|TK Responsav|Timekeeper Responsavel
FSC|10|FSC_NTKRES|C|30|0|Nome Tk.Resp|Nome do Timek.Responsavel
FSC|11|FSC_STATUS|C|1|0|Situacao|Situacao do Contrato
FSC|12|FSC_DTVIG|D|8|0|Vig.Inicial|Data de Vigencia
FSC|13|FSC_VIGFIN|D|8|0|Vig. Final|Data da Vigencia Final
FSC|14|FSC_CONDFI|C|2|0|Cond.financ.|Condicao financeira
FSC|15|FSC_MOEDA|C|1|0|Moeda|Codigo da Moeda
FSC|16|FSC_MOEDDE|C|1|0|Moeda Desp.|Moeda das Despesas
FSC|17|FSC_TABHON|C|4|0|Tab.Honors.|Tabela de Honorarios
FSC|18|FSC_CNDPAG|C|3|0|Cond.Pagto.|Condicao de Pagamento
FSC|19|FSC_IDIOMA|C|3|0|Idioma|Idioma do Contrato
FSC|20|FSC_PERFAT|N|3|0|Per.Faturam.|Periodo de Faturamento
FSC|21|FSC_DIACOR|C|2|0|Dia de Corte|Dia de Corte Apontamentos
FSC|22|FSC_CUSTOS|C|1|0|Apont.Fatura|Apontantamentos na Fatura
FSC|23|FSC_TIPFAT|C|1|0|Tipo Fatur.|Tipo de Faturamento
FSC|24|FSC_EXITO|C|1|0|Neg.Exito?|Exito
FSC|25|FSC_ATO|C|1|0|Neg.Ato?|Ato
FSC|26|FSC_DESCON|N|5|2|Desc.Contr.|Desconto Contratual
FSC|27|FSC_TXCONT|N|12|2|Taxa Contrat|Taxa Contratada
FSC|28|FSC_TXDESP|N|12|2|Tx.Cont.Desp|Taxa Contratada de Desp.
FSC|29|FSC_JUNCAO|C|4|0|Cod. Juncao|Codigo da Juncao
FSC|30|FSC_DESJUN|C|40|0|Descr.Juncao|Descricao da Juncao
FSC|31|FSC_DTULFT|D|8|0|Dt.Ult.Fatur|Data Ultimo Faturamento
FSC|32|FSC_SEQ|C|6|0|Sequencia|Versao do contrato
FSC|33|FSC_OK|C|2|0|OK|OK
FSC|34|FSC_DTVERS|D|8|0|Data Versao|Data da Versao
FSC|35|FSC_DISTRI|C|3|0|Distribuicao|Distribuicäo de Faturas
FSC|36|FSC_CODETA|C|3|0|Código Etapa|Código da Etapa
FSC|37|FSC_DSCETA|C|40|0|Descrição|Descrição das Etapas
FSC|38|FSC_CFGPRE|C|3|0|Conf.Pre-Fat|Config.Pre-Fatura
FSC|39|FSC_CFGFAT|C|3|0|Conf. Fatura|Configurador Fatura
--- ### FSD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSD|01|FSD_FILIAL|C|6|0|Filial|Filial do Sistema
FSD|02|FSD_CODIGO|C|4|0|Codigo|Codigo do Historico
FSD|03|FSD_CONTRA|C|10|0|Contrato|Numero do Contrato
FSD|04|FSD_USURES|C|6|0|UsuarioResp.|Usuario Responsavel
FSD|05|FSD_TITULO|C|40|0|Titulo|Titulo do Historico
FSD|06|FSD_DATA|D|8|0|Data|Data do Historico
FSD|07|FSD_OBSERV|M|80|0|Observacoes|Observacoes
FSD|08|FSD_CODOBS|C|6|0|Cod.Obs.|Codigo da Observacao
--- ### FSE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSE|01|FSE_FILIAL|C|6|0|Filial|Filial do Sistema
FSE|02|FSE_CODIGO|C|4|0|Codigo|Codigo de Localidade
FSE|03|FSE_NOME|C|40|0|Nome|Nome da Empresa
FSE|04|FSE_ENDER|C|40|0|Endereco|Endereco da Localidade
FSE|05|FSE_BAIRRO|C|20|0|Bairro|Bairro da Localidade
FSE|06|FSE_CIDADE|C|20|0|Cidade|Cidade da Localidade
FSE|07|FSE_ESTADO|C|2|0|Estado|Estado da localidade
FSE|08|FSE_CEP|C|9|0|Cep|Cep da Localidade
FSE|09|FSE_CNPJ|C|14|0|CNPJ|CNPJ
FSE|10|FSE_INSEST|C|21|0|Insc.Estad.|Inscricao Estadual
--- ### FSF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSF|01|FSF_FILIAL|C|6|0|Filial|Filial do Sistema
FSF|02|FSF_CODIGO|C|4|0|Area Pratica|Codigo de area de pratica
FSF|03|FSF_DESCRI|C|48|0|Descricao|Descricao da Area de Prat
FSF|04|FSF_CLASSE|C|1|0|Classe|Classe de Area de Pratica
--- ### FSG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSG|01|FSG_FILIAL|C|6|0|Filial|Filial do Sistema
FSG|02|FSG_CODIGO|C|3|0|Cod.Despesa|Codigo da Despesa
FSG|03|FSG_DESCRI|C|48|0|Descricao|Descricao da Despesa
FSG|04|FSG_VLRUNI|N|14|2|Vlr.Unitario|Valor Unitario
FSG|05|FSG_TXADM|N|5|2|Tx.Administr|Taxa de Administracao
FSG|06|FSG_VLMAXD|N|12|2|Vlr.Max.Desp|Valor Maximo por Despesa
--- ### FSH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSH|01|FSH_FILIAL|C|6|0|Filial|Filial do Sistema
FSH|02|FSH_CODIGO|C|4|0|Cod.Juncao|Codigo da Juncao
FSH|03|FSH_CONTRA|C|10|0|Num.contrato|Numero de contrato
FSH|04|FSH_DESCRC|C|40|0|Descr.Contr.|Descricao do contrato
--- ### FSI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSI|01|FSI_FILIAL|C|6|0|Filial|Filial do Sistema
FSI|02|FSI_REFER|C|6|0|Referencia|Referencia do Lote
FSI|03|FSI_CODDOC|C|10|0|Documento|Cod. do Documento de Desp
FSI|04|FSI_ASSUNT|C|11|0|Assunto|Codigo do Assunto
FSI|05|FSI_DESASS|C|144|0|Descricao|Descricao do Assunto
FSI|06|FSI_CONTRA|C|10|0|Contrato|Numero do Contrato
FSI|07|FSI_CODCLI|C|6|0|Cliente|Codigo do Cliente
FSI|08|FSI_LOJA|C|2|0|Loja|Loja do Cliente
FSI|09|FSI_NOMCLI|C|30|0|Cliente|Nome do Cliente
FSI|10|FSI_DATA|D|8|0|Data|Data do Apontamento
FSI|11|FSI_LOCALI|C|4|0|Localidade|Localidade
FSI|12|FSI_DSCLOC|C|40|0|Desc. Local.|Descricao da Localidade
FSI|13|FSI_TIPOD|C|3|0|Tipo Despesa|Tipo de Despesa
FSI|14|FSI_DESCRI|C|48|0|Descricao|Descricao de Despesa
FSI|15|FSI_IDIORI|C|3|0|Idioma Orig.|Idioma da Narrativa
FSI|16|FSI_IDIOMA|C|20|0|Idioma|Idioma do Assunto
FSI|17|FSI_NARRAT|M|80|0|Narrativa|Narrativa do Apontamento
FSI|18|FSI_IDITRD|C|3|0|Idioma Trad.|Idioma Trad. Narrativa
FSI|19|FSI_NARRLI|M|80|0|Narr.Lingua|Narr.Lingua Estrangeira
FSI|20|FSI_PERCEN|N|6|2|Perc.Rateio|Percentual Rateado
FSI|21|FSI_VLRORI|N|12|2|Valor Rateio|Valor Rateado
FSI|22|FSI_DATDIG|D|8|0|Dt.Digitacao|Data de Digitacao
FSI|23|FSI_TIMEK|C|8|0|Timekeeper|Timekeeper da Despesa
FSI|24|FSI_NOMTMK|C|30|0|Nome Adotado|Nome Adotado
FSI|25|FSI_QUANT|N|12|2|Quantidade|Quantidade da Despesa
FSI|26|FSI_SALDO|N|18|7|Saldo|Saldo da Quantidade
FSI|27|FSI_VLRUNI|N|14|4|Vlr.Unitario|Valor Unitario
FSI|28|FSI_VLRTOT|N|12|2|Valor Total|Valor Total
FSI|29|FSI_MOEDA|C|1|0|Moeda|Moeda do Contrato
FSI|30|FSI_VLMCON|N|14|2|V.Moeda Cont|Vlr na Moeda do Contrato
FSI|31|FSI_OK|C|2|0|Marca Brw|Marca do MarkBrowse
FSI|32|FSI_IDPFAT|C|7|0|Id Pre-Fat|Id Pre-Fatura
FSI|33|FSI_FFATU|C|1|0|Flag Fatura|Flag Fatura Emitida
FSI|34|FSI_MSIDEN|C|8|0|Ident.Reg.|Ident. Registros
FSI|35|FSI_IDPAI|C|8|0|ID Origem|ID Apontamento Original
FSI|36|FSI_ASSORI|C|11|0|Ass. Orig.|Assunto Original
FSI|37|FSI_STATUS|C|1|0|Situacao|Situacao da despesa
FSI|38|FSI_ORIGEM|C|8|0|Origem|Origem do apontamento
FSI|39|FSI_CODRAT|C|6|0|Cod.Narrat.|Codigo da Narrativa
FSI|40|FSI_CODRLI|C|6|0|Cd.Nar.Estr.|Cod.Narrat.Outro Idioma
FSI|41|FSI_DTLANC|D|8|0|Data Lancto.|Data do Lancto. Contábil
FSI|42|FSI_DTLCFT|D|8|0|Lanc.Ctb.Fat|Data Lanc.Cont.da Fatura
FSI|43|FSI_DATFAT|D|8|0|Dt.Faturam.|Data do Faturamento
FSI|44|FSI_VLUREA|N|12|2|V.Unit. Real|Valor Unitário Real
FSI|45|FSI_APPRIM|C|1|0|Ap.Primário|Apontamento Primário
FSI|46|FSI_RATEIO|C|3|0|Cód. Rateio|Código do Rateio
FSI|47|FSI_TIPRAT|C|1|0|Tipo Rateio|Tipo do Rateio
FSI|48|FSI_CCUSTO|C|9|0|Centro Custo|C. Custo da Despesa
--- ### FSJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSJ|01|FSJ_FILIAL|C|6|0|Filial|Filial do Sistema
FSJ|02|FSJ_CODIGO|C|4|0|Cod.Categ.|Codigo da Categoria
FSJ|03|FSJ_DESCRI|C|40|0|Descricao|Descricao
--- ### FSK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSK|01|FSK_FILIAL|C|6|0|Filial|Filial do Sistema
FSK|02|FSK_CODIGO|C|3|0|Crit.Retific|Cod.Criterios Retificacao
FSK|03|FSK_DESCRI|C|40|0|Descricao|Descricaocrit.retificacao
FSK|04|FSK_FATUR|C|1|0|Faturavel|Flag de Faturavel
--- ### FSL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSL|01|FSL_FILIAL|C|6|0|Filial|Filial do Sistema
FSL|02|FSL_DATA|D|8|0|Data|Data do Apontamento
FSL|03|FSL_CONTRA|C|10|0|Contrato|Numero do Contrato
FSL|04|FSL_ASSUNT|C|11|0|Cod.Assunto|Codigo do Assunto
FSL|05|FSL_CODCLI|C|6|0|Cliente|Codigo do Cliente
FSL|06|FSL_LOJA|C|2|0|Loja|Loja do Cliente
FSL|07|FSL_NOMCLI|C|40|0|Razão|Razão Social do Cliente
FSL|08|FSL_TIMEK|C|8|0|Timekeeper|Timekeeper
FSL|09|FSL_NOMTMK|C|30|0|Nome Adotado|Nome Adotado
FSL|10|FSL_CATEG|C|4|0|Categoria|Categoria do Timekeeper
FSL|11|FSL_LOCTMK|C|4|0|Local.Tmkp.|Localidade do Timekeeper
FSL|12|FSL_NOMLTK|C|40|0|Nome.Loc.Tmk|Nome da Loc.Timek.
FSL|13|FSL_LOCALI|C|4|0|Loc. Apont.|Local do Apontamento
FSL|14|FSL_AREAPR|C|4|0|Area Pratica|Area de pratica
FSL|15|FSL_QTDHOR|C|4|0|Qtd. Horas|Horas Apontadas
FSL|16|FSL_HRCENT|N|12|2|Qt.Hrs.Cent.|Qtde.Horas Centesimais
FSL|17|FSL_IDIORI|C|3|0|Idioma Orig.|Idioma da Narrativa
FSL|18|FSL_NARRAT|M|80|0|Narrativa|Narrativa do Apontamento
FSL|19|FSL_IDITRD|C|3|0|Idioma Trad.|Idioma Trad. Narrativa
FSL|20|FSL_NARRLI|M|80|0|Narr.Lingua|Narr.Lingua Estrangeira
FSL|21|FSL_VLRUNI|N|12|2|Vlr.Unitario|Valor Unitario
FSL|22|FSL_VLRTOT|N|12|2|Vlr. Total|Vlr.Total do Apontamento
FSL|23|FSL_MOEDA|C|1|0|Moeda|Moeda do Contrato
FSL|24|FSL_DIGITA|D|8|0|Dt.Digitacao|Data da digitacäo
FSL|25|FSL_STATUS|C|1|0|Situacao|Situacao horas apontadas
FSL|26|FSL_SALDO|N|18|7|Saldo Horas|Saldo das Horas
FSL|27|FSL_IDPFAT|C|7|0|Id Pre-Fat|Id Pre-Fatura
FSL|28|FSL_FFATU|C|1|0|Flag Fatura|Flag Fatura Gerada
FSL|29|FSL_MSIDEN|C|8|0|Ident.Reg.|Ident. Registros
FSL|30|FSL_IDPAI|C|8|0|Id.Apont Pai|Id do Apontamento Pai
FSL|31|FSL_ASSORI|C|11|0|Ass. Orig.|Assunto Original
FSL|32|FSL_CODRAT|C|6|0|Cod.Narrat.|Codigo da Narrativa
FSL|33|FSL_CODRLI|C|6|0|Cd.Nar.Estr.|Cod.narrat.outro Idioma
FSL|34|FSL_OK|C|2|0|Marca Brw|Marca do MarkBrowse
FSL|35|FSL_DTLCFT|D|8|0|Lanc.Ctb.Fat|Data Lanc.Cont.da Fatura
FSL|36|FSL_DATFAT|D|8|0|Dt.Faturam.|Data do Faturamento
FSL|37|FSL_VLUREA|N|12|2|V.Unit. Real|Valor Unitário Real
FSL|38|FSL_APPRIM|C|1|0|Ap.Primário|Apontamento Primário
FSL|39|FSL_RATEIO|C|3|0|Cód. Rateio|Código do Rateio
FSL|40|FSL_TIPRAT|C|1|0|Tipo Rateio|Tipo do Rateio
--- ### FSM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSM|01|FSM_FILIAL|C|6|0|Filial|Filial do Sistema
FSM|02|FSM_CODIGO|C|2|0|Codigo|Codigo de Encerramento
FSM|03|FSM_DESCRI|C|40|0|Descricäo|Descricao do Encerramento
FSM|04|FSM_REABRE|C|1|0|Reabre?|Permite reabertura?
FSM|05|FSM_OBSERV|C|1|0|Obs.Obrigat?|Observacäo Obrigatoria?
--- ### FSN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSN|01|FSN_FILIAL|C|6|0|Filial|Filial do Sistema
FSN|02|FSN_CODIGO|C|3|0|Codigo|Codigo da Distribuicao
FSN|03|FSN_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FSN|04|FSN_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FSN|05|FSN_NOMCLI|C|40|0|Nome Cliente|Nome do Cliente
FSN|06|FSN_CONTAT|C|6|0|Contato|Contato da Distribuicao
FSN|07|FSN_TIPAPO|C|1|0|Tipo Apontam|Tipo de Aponamento
FSN|08|FSN_PERC|N|6|2|Percentual|Percentual do Cliente
FSN|09|FSN_CNDPAG|C|3|0|Cond.Pagto.|Condição de Pagamento
FSN|10|FSN_MOEDA|C|1|0|Moeda|Moeda da distribuição
FSN|11|FSN_SEQUEN|C|6|0|Sequencia|Sequencia da versão
--- ### FSO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSO|01|FSO_FILIAL|C|6|0|Filial|Filial do Sistema
FSO|02|FSO_TABELA|C|4|0|Tabela|Tabela do Contrato
FSO|03|FSO_DSCTAB|C|40|0|Desc. Tab.|Descricäo da Tabela
FSO|04|FSO_LOCALI|C|4|0|Localidade|Loc. do Relacionamento
FSO|05|FSO_DSCLOC|C|40|0|Desc. Local|Descricäo do Local
FSO|06|FSO_TABLOC|C|4|0|Tab. Loc.|Tab. utilizada para a Loc
FSO|07|FSO_DCTLOC|C|40|0|Dsc.Tab.Loc.|Descricao Tab. Local
--- ### FSP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSP|01|FSP_FILIAL|C|6|0|Filial|Filial do Sistema
FSP|02|FSP_NUMPFA|C|6|0|Num.Pre-fat.|Numero da Pre-fatura
FSP|03|FSP_DATA|D|8|0|Data Pre-fat|Data da Pre-fatura
FSP|04|FSP_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FSP|05|FSP_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FSP|06|FSP_ENTIDA|C|1|0|Entidade|Tipo de Entidade
FSP|07|FSP_CODENT|C|11|0|Cod.Entidade|Codigo da Entidade
FSP|08|FSP_CONTAT|C|6|0|Cod.Contato|Codigo do Contato
FSP|09|FSP_DATVIS|D|8|0|Data Visao|Data Lim. p/Visao Apont.
FSP|10|FSP_MOEDA|C|1|0|Moeda|Moeda da Pre-fatura
FSP|11|FSP_VLREAL|N|12|2|Vlr.Real Hon|Vlr.Real dos Honorarios
FSP|12|FSP_VLRHON|N|12|2|Vl.Honorario|Valor dos Honorarios
FSP|13|FSP_VLDESP|N|12|2|Vlr.Despesas|Valor das Despesas
FSP|14|FSP_VLEVCO|N|12|2|Vl. Ev.Contr|Vlr. Eventos Contratuais
FSP|15|FSP_VLEVDE|N|12|2|Vl. Ev. Desp|Valor de Ev. de Despesas
FSP|16|FSP_VLRCFI|N|12|2|Vlr.Cond.Fin|Valor da Cond. Financ.
FSP|17|FSP_ABATSU|N|12|2|Abat.Suplem.|Abatimento Suplementar
FSP|18|FSP_DSCCFI|N|12|2|Desc.C.Finan|Desconto S/ Cond.Financ.
FSP|19|FSP_VLRBRU|N|14|2|Total Bruto|Valor Total Bruto
FSP|20|FSP_VLRLIQ|N|14|2|Tot. Liquido|Valor Total Liquido
FSP|21|FSP_IDPFAT|C|7|0|Id.Pre-Fat.|Id. Pre-Fatura
FSP|22|FSP_CNDPAG|C|3|0|Cond.Pagto.|Condicäo de Pagamento
FSP|23|FSP_STATUS|C|1|0|Status|Status da Pre-fatura
FSP|24|FSP_IRRF|N|14|2|IRRF|IRRF
FSP|25|FSP_ISS|N|14|2|ISS|ISS
FSP|26|FSP_INSS|N|14|2|INSS|INSS
FSP|27|FSP_CSLL|N|14|2|CSLL|CSLL
FSP|28|FSP_PIS|N|14|2|PIS|PIS
FSP|29|FSP_COFINS|N|14|2|COFINS|COFINS
FSP|30|FSP_RETAUT|C|1|0|Ret.Automat?|Retificacao automatica
FSP|31|FSP_OK|C|2|0|OK|OK
FSP|32|FSP_NATHON|C|10|0|Nat. Honor.|Natureza dos Honorarios
FSP|33|FSP_NATDES|C|10|0|Nat.Despesas|Natueza das Despesas
FSP|34|FSP_ORIGEM|C|10|0|Origem|Rotina geradora da P.F.
FSP|35|FSP_CODMSG|C|6|0|Código Msg|Código da Mensagem PF
FSP|36|FSP_MSG|M|80|0|Mensagem|Mensagem da Pré-Fatura
FSP|37|FSP_PERIOD|C|1|0|Resp.Período|Respeita Período Fatur.
FSP|38|FSP_TIPOPF|C|1|0|Tipo Geração|Tipo de Geração da PF
--- ### FSQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSQ|01|FSQ_FILIAL|C|6|0|Filial|Filial do Sistema
FSQ|02|FSQ_CODIGO|C|3|0|Codigo|Codigo do Evento
FSQ|03|FSQ_DESPRI|C|48|0|Descr.Princ.|Descr.no Idioma Principal
FSQ|04|FSQ_VALOR|N|14|2|Valor|Valor do Evento
--- ### FSR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSR|01|FSR_FILIAL|C|6|0|Filial|Filial do Sistema
FSR|02|FSR_DATA|D|8|0|Data Evento|Data do Evento
FSR|03|FSR_DATDIG|D|8|0|Dt.Digitação|Data de Digitação
FSR|04|FSR_CODCLI|C|6|0|Cliente|Código do Cliente
FSR|05|FSR_LOJA|C|2|0|Loja|Loja do Cliente
FSR|06|FSR_NOMCLI|C|60|0|Nome|Nome do Cliente
FSR|07|FSR_CONTRA|C|10|0|Num.Contrato|Numero do Contrato
FSR|08|FSR_ASSUNT|C|11|0|Cod.Assunto|Codigo do Assunto
FSR|09|FSR_TIPEVC|C|3|0|Tipo Evento|Tipo Evento Contratual
FSR|10|FSR_DESCRI|C|48|0|Desc.Ev.Cont|Descr. Evento Contratual
FSR|11|FSR_ANTREC|C|1|0|Ant.Recebim?|Antecipação Recebimento
FSR|12|FSR_TPAPON|C|1|0|Tipo Adiant.|Tipo de Adiantamento
FSR|13|FSR_COMPL|M|80|0|Compl.Desc.|Complemento da Descricao
FSR|14|FSR_TIMEK|C|8|0|Timekeeper|Timekeeper Evento Contrat
FSR|15|FSR_NOMTMK|C|30|0|Nome Tmkp.|Nome do Timekeeper
FSR|16|FSR_NUMDOC|C|8|0|Num.Docto.|Numero do Documento
FSR|17|FSR_VLRUNI|N|14|2|Vlr.Unitario|Vlr.Unitario
FSR|18|FSR_VLREAL|N|14|2|Valor Real|Valor real do apontamento
FSR|19|FSR_MOEDA|C|1|0|Moeda|Moeda do Contrato
FSR|20|FSR_FFATU|C|1|0|Flag Fatura|Flat de Fatura
FSR|21|FSR_IDPFAT|C|7|0|Id. Pre-Fat|Id. da Pre-Fatura
FSR|22|FSR_MSIDEN|C|8|0|Ident.Reg.|Ident. Registros
FSR|23|FSR_IDADI|C|8|0|ID Origem|ID Apontamento Original
FSR|24|FSR_DTORI|D|8|0|Dt. Origem|Dt. Apontamento Original
FSR|25|FSR_ASSORI|C|11|0|Ass. Orig.|Assunto Original
FSR|26|FSR_ORIGEM|C|8|0|Origem|Origem do Apontamento
FSR|27|FSR_DESCTR|C|48|0|Desc.Traduz.|Descricao Traduzida
FSR|28|FSR_COMPTR|M|80|0|Compl.Traduz|Complemento Traduzido
FSR|29|FSR_CODMPL|C|6|0|Cod. Memo|Codigo do Memo
FSR|30|FSR_CODPTR|C|6|0|Cod. Memo|Codigo do Memo
FSR|31|FSR_OK|C|2|0|Marca|Campo para MarkBrowse
FSR|32|FSR_DTLCFT|D|8|0|Lanc.Ctb.Fat|Data Lanc.Cont.da Fatura
FSR|33|FSR_DATFAT|D|8|0|Dt.Faturam.|Data do Faturamento
--- ### FSS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSS|01|FSS_FILIAL|C|6|0|Filial|Filial do Sistema
FSS|02|FSS_CODIGO|C|3|0|Codigo Etapa|Codiga da Etapa
FSS|03|FSS_DESCRI|C|20|0|Descricao|Descricao da Etapa
FSS|04|FSS_PRAZO|N|3|0|Prazo Maximo|Prazo Maximo
FSS|05|FSS_ALTVCT|C|1|0|Altera Prazo|Permite alterar prazo
FSS|06|FSS_LIBERA|C|1|0|Perm.Liberar|Permite Liberar?
FSS|07|FSS_TPAPON|C|1|0|Tipo Apontam|Tipo de Apontamento
--- ### FST
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FST|01|FST_FILIAL|C|6|0|Filial|Filial do Sistema
FST|02|FST_CODIGO|C|3|0|Cód.Etapa|Código da Etapa de P.F.
FST|03|FST_SEQETA|C|2|0|Seq.Etapa|Sequencia da Etapa
FST|04|FST_CODETA|C|3|0|Esp. Etapa|Espécie de Etapa de P.F.
FST|05|FST_DSCETA|C|20|0|Desc.Etapa|Descricao da Etapa
FST|06|FST_PRAZO|N|3|0|Prazo Maximo|Prazo Maximo
FST|07|FST_TPAPON|C|1|0|Tipo Apontam|Tipo de Apontamento
FST|08|FST_MSIDEN|C|8|0|Ident.Reg.|Ident. Registros
--- ### FSU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSU|01|FSU_FILIAL|C|6|0|Filial|Filial do Sistema
FSU|02|FSU_CODIGO|C|6|0|Cod.Cont.Eta|Codigo Controle Etapas
FSU|03|FSU_PREFAT|C|6|0|Num.Pre-Fat.|Numero da Pre-fatura
FSU|04|FSU_TPENPF|C|1|0|Ent.Pre-Fat.|Entidade da Pre-Fatura
FSU|05|FSU_CDENPF|C|11|0|Cód.Ent.PF|Código da Entidade da P.F
FSU|06|FSU_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FSU|07|FSU_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FSU|08|FSU_TIPENT|C|1|0|Tipo Entidad|Tipo da Entidade
FSU|09|FSU_CODENT|C|11|0|Cod.Entidade|Cod.Registro da Entidade
FSU|10|FSU_CODETA|C|3|0|Cod.Etapa|Codigo da Etapa
FSU|11|FSU_SEQETA|C|2|0|Seq.da Etapa|Sequencia da Etapa
FSU|12|FSU_DESTIN|C|1|0|Destinatario|Tipo do Destinatario
FSU|13|FSU_CODDES|C|6|0|Cod.Destinat|Codigo do Destinatario
FSU|14|FSU_TIMEK|C|8|0|Timekeeper|Timekeeper Responsável
FSU|15|FSU_DTEMPF|D|8|0|Dt.Emis.P.F.|Data Emissao Pre-Fatura
FSU|16|FSU_DTINET|D|8|0|Dt.Inic.Etap|Data de Inicio da Etapa
FSU|17|FSU_DTPREN|D|8|0|Dt.Prev.Enc.|Data Prevista Encerrament
FSU|18|FSU_DTENCE|D|8|0|Dt.Encerram.|Data de Encerramento
FSU|19|FSU_STATUS|C|1|0|Status Etapa|Status da Etapa
FSU|20|FSU_USUEXE|C|6|0|Usu.Executor|Codigo Usuario Executor
FSU|21|FSU_USUADM|C|6|0|Usu.Administ|Cod.Usuario Administrador
FSU|22|FSU_JUSTIF|C|60|0|Justif.Canc.|JustificativaCancelamento
FSU|23|FSU_OK|C|2|0|OK|OK
--- ### FSV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSV|01|FSV_FILIAL|C|6|0|Filial|Filial do Sistema
FSV|02|FSV_COD|C|4|0|Codigo|Codigo Departamento
FSV|03|FSV_DESCRI|C|48|0|Descrição|Descrição do Depto.
--- ### FSW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSW|01|FSW_FILIAL|C|6|0|Filial|Filial do Sistema
FSW|02|FSW_ENTIDA|C|1|0|Entidade|Tipo de Entidade da Etapa
FSW|03|FSW_CODENT|C|11|0|Cód.Entidade|Código da Entidade
FSW|04|FSW_JOGOET|C|3|0|Jogo Etapas|Codigo do Jogo de Etapas
FSW|05|FSW_SEQETA|C|2|0|Seq.Etapa|Sequencia da Etapa
FSW|06|FSW_CODETA|C|3|0|Esp. Etapa|Espécie de Etapa
FSW|07|FSW_PRAZO|N|3|0|Prazo Máximo|Prazo Máximo de Execução
FSW|08|FSW_DESTIN|C|1|0|Destinatário|Destinatário da Etapa
FSW|09|FSW_CODDES|C|6|0|Cód. Destin.|Código do Destinatário
FSW|10|FSW_NOMDES|C|30|0|Nome Destin.|Nome do Destinatario
FSW|11|FSW_TPAPON|C|1|0|Tipo Apontam|Tipo de Apontamento
FSW|12|FSW_DESDOB|C|1|0|Desdobra ?|Desdobramento da Etapa
FSW|13|FSW_IDPAI|C|8|0|Id Etapa Pai|Id do Item do Jogo Princ.
--- ### FSX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSX|01|FSX_FILIAL|C|6|0|Filial|Filial do Sistema
FSX|02|FSX_IDPFAT|C|7|0|Id. Pre-Fat.|Id da Pre-Fatura
FSX|03|FSX_IDFAT|C|7|0|Id. Fatura|Id da Fatura
FSX|04|FSX_NUMPFA|C|6|0|Nro.Pre-Fat.|Número da Pré-Fatura
FSX|05|FSX_NUMFAT|C|6|0|Nro.Fatura|Número da Fatura
--- ### FSY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSY|01|FSY_FILIAL|C|6|0|Filial|Filial do Sistema
FSY|02|FSY_TABELA|C|4|0|Num.Tabela|Numero Tab.de Honorarios
FSY|03|FSY_MOEDA|C|1|0|Moeda|Codigo da Moeda
FSY|04|FSY_DESCRI|C|40|0|Descricao|Descricao da Tabela
FSY|05|FSY_VIGINI|D|8|0|Dt.Vig.Inic.|Data Vigencia Inicial
FSY|06|FSY_VIGFIN|D|8|0|Dt.Vig.Final|Data Vigencia Final
FSY|07|FSY_CODIGO|C|6|0|Codigo Tabel|Codigo Tab.de Honorarios
--- ### FSZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FSZ|01|FSZ_FILIAL|C|6|0|Filial|Filial do Sistema
FSZ|02|FSZ_TABELA|C|4|0|Num.Tabela|Numero Tab.de Honorarios
FSZ|03|FSZ_MOEDA|C|1|0|Moeda|Codigo da Moeda
FSZ|04|FSZ_CLASSE|C|1|0|Classe|Classe do Timekeeper
FSZ|05|FSZ_CATTMK|C|4|0|Categ.TK|Categoria do timekeeper
FSZ|06|FSZ_AREAPR|C|4|0|Area Pratica|Area de Pratica
FSZ|07|FSZ_VLRUNI|N|14|2|Vlr.Unitario|Valor Unitario
FSZ|08|FSZ_CODIGO|C|6|0|Cod.Tabela|Codigo Tab.de Honorarios
--- ### FT0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT0|01|FT0_FILIAL|C|6|0|Filial|Filial do Sistema
FT0|02|FT0_CODIGO|C|40|0|Código|Código da Palavra
FT0|03|FT0_DESCRI|C|60|0|Descrição|Descrição da Palavra
--- ### FT1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT1|01|FT1_FILIAL|C|6|0|Filial|Filial do Sistema
FT1|02|FT1_CODIGO|C|3|0|Cod. Excecao|Codigo da Excecao Despesa
FT1|03|FT1_DESCRI|C|60|0|Descrição|Descrição da Exceção
FT1|04|FT1_CODESP|C|3|0|Cod. Despesa|Codigo da Despesa
FT1|05|FT1_GRPCLI|C|6|0|Grp.Clientes|Grupo de Clientes
FT1|06|FT1_CODCLI|C|6|0|Cliente|Código do Cliente
FT1|07|FT1_LOJA|C|2|0|Loja|Loja do Cliente
FT1|08|FT1_NOMCLI|C|60|0|Nome Cliente|Nome do Cliente
FT1|09|FT1_CONTRA|C|10|0|Cod.Contrato|Codigo do Contrato
FT1|10|FT1_DESCON|C|60|0|Desc. Contra|Descricao do Contrato
FT1|11|FT1_ASSUNT|C|11|0|Assunto|Cod. do Assunto
FT1|12|FT1_VLRREA|N|14|2|Vlr.Original|Valor Original do Tp. Des
FT1|13|FT1_TIPOFX|C|1|0|Tipo Faixa|Tipo de Faixa
FT1|14|FT1_SEQUEN|C|6|0|Sequencia|Sequencia da Versao
FT1|15|FT1_VIGINI|D|8|0|Vig. Inicial|Vigência Inicial
FT1|16|FT1_VIGFIN|D|8|0|Vig. Final|Vigência Final
--- ### FT2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT2|01|FT2_FILIAL|C|6|0|Filial|Filial do Sistema
FT2|02|FT2_ENTIDA|C|3|0|Entidade|Entidade
FT2|03|FT2_CODENT|C|4|0|Codigo|Codigo da Entidade
FT2|04|FT2_SEQUEN|C|3|0|Sequencia|Sequencia do Codigo
FT2|05|FT2_IDIOMA|C|3|0|Idioma|Idioma
FT2|06|FT2_DESCRI|C|48|0|Descricao|Descricao no Idioma
--- ### FT3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT3|01|FT3_FILIAL|C|6|0|Filial|Filial do Sistema
FT3|02|FT3_CODIGO|C|6|0|Código|Código da Exceção
FT3|03|FT3_DESCRI|C|60|0|Descrição|Descrição da Exceção
FT3|04|FT3_CONTRA|C|10|0|Contrato|Numero do Contrato
FT3|05|FT3_DESCON|C|60|0|Descricao|Descricao do Contrato
FT3|06|FT3_ASSUNT|C|11|0|Assunto|Código do Assunto
FT3|07|FT3_DESASS|C|144|0|Descrição|Descrição do Assunto
FT3|08|FT3_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FT3|09|FT3_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FT3|10|FT3_NOMCLI|C|60|0|Nome Cliente|Nome do Cliente
FT3|11|FT3_TABHON|C|4|0|Tab. Honor.|Tabela de Honorarios
FT3|12|FT3_MOEDA|C|1|0|Moeda|Moeda da Tab. Honorarios
FT3|13|FT3_SEQUEN|C|6|0|Sequencia|Sequencia da Versao
FT3|14|FT3_VIGINI|D|8|0|Vig.Inicial|Vigencia Inicial
FT3|15|FT3_VIGFIN|D|8|0|Vig. Final|Vigência Final
--- ### FT4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT4|01|FT4_FILIAL|C|6|0|Filial|Filial do Sistema
FT4|02|FT4_CODIGO|C|3|0|Codigo|Codigo
FT4|03|FT4_DESCRI|C|40|0|Descricao|Descricao
--- ### FT5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT5|01|FT5_FILIAL|C|6|0|Filial|Filial do Sistema
FT5|02|FT5_CODIGO|C|3|0|Codigo|Codigo do Apontamento
FT5|03|FT5_DESCRI|C|40|0|Descricao|Descricao do Apontamento
FT5|04|FT5_CONTRO|C|10|0|Contr. Orig.|Contrato Original Rateio
FT5|05|FT5_ASSUNO|C|11|0|Ass.Orig.|Assunto Original Rateio
FT5|06|FT5_CDCLIO|C|6|0|Cliente Orig|Cliente Origem do Rateio
FT5|07|FT5_LOJAO|C|2|0|Loja|Loja do Cliente Origem
FT5|08|FT5_TPRAT|C|1|0|Tipo Rateio|Tipo de Rateio
FT5|09|FT5_TPCALC|C|1|0|Tipo Cálc.H.|Tipo de Cálc. p/Honorário
FT5|10|FT5_TPCALD|C|1|0|Tp.Calc.Desp|Tipo de Cálc. p/ Despesas
--- ### FT6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT6|01|FT6_FILIAL|C|6|0|Filial|Filial do Sistema
FT6|02|FT6_CONTRA|C|10|0|Contrato|Cod. do Contrato
FT6|03|FT6_DSCCON|C|60|0|Descrição|Descrição do Contrato
FT6|04|FT6_ASSUNT|C|11|0|Assunto|Cod. do Assunto
FT6|05|FT6_DSCASS|C|144|0|Descrição|Descrição do Assunto
--- ### FT7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT7|01|FT7_FILIAL|C|6|0|Filial|Filial do Sistema
FT7|02|FT7_CODIGO|C|4|0|Junc.Assunto|Codigo Juncao de Assuntos
FT7|03|FT7_DESCRI|C|40|0|Descricao|Descricao Juncao Assuntos
FT7|04|FT7_CONTRA|C|10|0|Contrato|Codigo do Contrato
FT7|05|FT7_CONTAT|C|6|0|Contato|Contato
FT7|06|FT7_OK|C|2|0|Ok|OK
FT7|07|FT7_TRANSF|C|3|0|Transf.|Transferencia
FT7|08|FT7_CODETA|C|3|0|Código Etapa|Código da Etapa
FT7|09|FT7_DSCETA|C|40|0|Descrição|Descrição das Etapas
--- ### FT8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT8|01|FT8_FILIAL|C|6|0|Filial|Filial do Sistema
FT8|02|FT8_TIPDES|C|3|0|Tipo Despesa|Tipo de Despesa
FT8|03|FT8_TIPDOC|C|1|0|Tipo Docto.|Tipo de Documento
FT8|04|FT8_DSCDOC|C|40|0|Descrição|Descrição do Tipo de Doc.
FT8|05|FT8_NATURE|C|10|0|Natureza|Natureza Ctas.Pagar
--- ### FT9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FT9|01|FT9_FILIAL|C|6|0|Filial|Filial do Sistema
FT9|02|FT9_TIPO|C|1|0|Tipo|Tipo do detalhe de apont.
FT9|03|FT9_NUMERO|C|6|0|Número|Número da Pré-Fat./Fatura
FT9|04|FT9_SEQ|C|4|0|Sequência|Sequência do Registro
FT9|05|FT9_ALIAS|C|4|0|Alias|Alias do registro
FT9|06|FT9_ID|C|8|0|Id Apont.|ID do Apontamento
FT9|07|FT9_CONTRA|C|10|0|Contrato|Código do Contrato
FT9|08|FT9_ASSUNT|C|11|0|Assunto|Código do Assunto
FT9|09|FT9_DATA|D|8|0|Data|Data do Apontamento
FT9|10|FT9_TIMEK|C|8|0|Timekeeper|Código do Timekeeper
FT9|11|FT9_AREAPR|C|4|0|Área Prática|Área de Prática
FT9|12|FT9_CATEG|C|4|0|Categoria|Categoria do Timekeeper
FT9|13|FT9_LOCALI|C|4|0|Localidade|Localidade do Apontamento
FT9|14|FT9_VLRUNI|N|12|2|Vlr. Unit.|Valor Unitário
FT9|15|FT9_QTREAL|N|12|2|Qtde. Real|Quantidade Real do Apont.
FT9|16|FT9_VLREAL|N|12|2|Vlr. Real|Valor Real do Apontam.
FT9|17|FT9_QTSALD|N|12|2|Saldo Qtde.|Saldo da quantidade
FT9|18|FT9_VLSALD|N|12|2|Saldo Valor|Saldo do Valor do Apont.
FT9|19|FT9_QTRTAC|N|12|2|Qt.Retif.Acr|Qt Retificações Acréscimo
FT9|20|FT9_VLRTAC|N|12|2|Vl.Retif.Acr|Valor Retif. Acréscimo
FT9|21|FT9_QTRTDC|N|12|2|Qt.Ret.Decr.|Qt Retific. Decréscimo
FT9|22|FT9_VLRTDC|N|12|2|Vl.Ret.Decr.|Vl. Retif. Decréscimo
--- ### FTA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTA|01|FTA_FILIAL|C|6|0|Filial|Filial do Sistema
FTA|02|FTA_CODIGO|C|6|0|Código|Código da Atividade
FTA|03|FTA_DESCRI|C|40|0|Descrição|Descrição da Atividade
--- ### FTB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTB|01|FTB_FILIAL|C|6|0|Filial|Filial do Sistema
FTB|02|FTB_CONTRA|C|10|0|Contrato|Contrato do Assunto
FTB|03|FTB_ASSUNT|C|11|0|Assunto|Assunto
FTB|04|FTB_DTSTAT|D|8|0|Data Status|Dt.de alteracao do status
FTB|05|FTB_STANTE|C|1|0|St.Anterior|Status Anterior
FTB|06|FTB_STNOVO|C|1|0|Novo Status|Novo Status
FTB|07|FTB_CODENC|C|2|0|Cod.Encerram|Codigo de Encerramento
FTB|08|FTB_OBSERV|M|80|0|Observacöes|Observacöes
FTB|09|FTB_CODOBS|C|6|0|Cod.Observ.|Codigo das Observacoes
FTB|10|FTB_REABRE|C|1|0|Reabre Ass?|Permite Reabertura?
FTB|11|FTB_MSIDEN|C|8|0|Ident.Reg.|Ident. Registros
--- ### FTC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTC|01|FTC_FILIAL|C|6|0|Filial|Filial do Sistema
FTC|02|FTC_ENTIDA|C|1|0|Entidade|Entidade do Faturamento
FTC|03|FTC_CODIGO|C|10|0|Cód.Entidade|Código da Entidade
FTC|04|FTC_DATINI|D|8|0|Data Inicial|Data Inicial do Período
FTC|05|FTC_DATFIN|D|8|0|Data Final|Data Final do Período
FTC|06|FTC_TIPOPF|C|1|0|Tipo Pré-Fat|Tipo da Pre-Fatura
FTC|07|FTC_IDPFAT|C|7|0|ID Pre-Fat.|ID da Pré-Fatura
--- ### FTD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTD|01|FTD_FILIAL|C|6|0|Filial|Filial do Sistema
FTD|02|FTD_CODIGO|C|3|0|Codigo|Codifo do Caixinha
FTD|03|FTD_NOME|C|30|0|Nome|Nome do Caixinha
FTD|04|FTD_VALOR|N|16|2|Valor|Valor do Caixinha
FTD|05|FTD_TPREP|C|1|0|Tipo Repos.|Tipo de Reposicao
FTD|06|FTD_LIMREP|N|16|2|Valor Rep.|Valor/Percent. Reposicao
FTD|07|FTD_SITUAC|C|1|0|Situacao|Situacao do Caixinha
FTD|08|FTD_NATURE|C|10|0|Natureza|Codigo da natureza
FTD|09|FTD_SALDO|N|16|2|Saldo|Saldo do Caixinha
FTD|10|FTD_ULTREP|D|8|0|Ultima Rep.|Data da Ultima Reposicao
FTD|11|FTD_DTCRIA|D|8|0|Data Criacäo|Dt da criacao do caixinha
FTD|12|FTD_SEQRP|C|8|0|Seq. Repos.|Seqüencia de Reposição
FTD|13|FTD_VREEMB|N|16|2|V.Teto Reemb|Valor Teto de Reembolso
--- ### FTE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTE|01|FTE_FILIAL|C|6|0|Filial|Filial do Sistema
FTE|02|FTE_CODCX|C|3|0|Cod.Caixinha|Codigo do Caixinha.
FTE|03|FTE_NUM|C|8|0|Numero Int.|Numero interno
FTE|04|FTE_ITEM|C|3|0|Item|Sequencia do lancamento
FTE|05|FTE_TIPO|C|2|0|Tipo Movto.|Tipo do movimento
FTE|06|FTE_TIMEK|C|8|0|Timekeeper|Codigo do timekeeper
FTE|07|FTE_NOMTMK|C|30|0|Nome Adotado|Nome Adotado Timekeeper
FTE|08|FTE_CDDESP|C|3|0|Cod. Despesa|Codigo da Despesa
FTE|09|FTE_NRDTO|C|8|0|Nro. Docto.|Numero do comprovante
FTE|10|FTE_DTEMIS|D|8|0|Dt. Docto.|Data de Emissao do Docto.
FTE|11|FTE_NATURE|C|10|0|Natureza|Natureza Financeira
FTE|12|FTE_DTDIG|D|8|0|Dt.Digitacao|Data de digitacäo
FTE|13|FTE_SLDADT|N|16|2|Sld.Anterior|Saldo Anterior
FTE|14|FTE_NRADTO|C|8|0|Nro. Adto.|Numeto do Adiantamento
FTE|15|FTE_CODFOR|C|6|0|Fornecedor|Codigo do Fornecedor
FTE|16|FTE_LJFOR|C|2|0|Lj. Fornec.|Loja do fornecedor
FTE|17|FTE_VALOR|N|16|2|Valor|Valor do Lancamento
FTE|18|FTE_HISTOR|C|30|0|Historico|Historico
FTE|19|FTE_SEQRP|C|8|0|Seq. Repos.|Seqüencia de Reposição
FTE|20|FTE_VLRADT|N|16|2|Vlr. S/Adto.|Valor base sobre adto.
FTE|21|FTE_VLREEM|N|16|2|Vlr.S/ Reemb|Valor de reembolso
FTE|22|FTE_DTBX|D|8|0|Dt. Baixa|Data de Baixa
FTE|23|FTE_CHVSE2|C|24|0|Chave SE2|Chave Contas a Pagar
FTE|24|FTE_STATUS|C|1|0|Ap.Revertido|Aporte Revertido
--- ### FTF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTF|01|FTF_FILIAL|C|6|0|Filial|Filial do Sistema
FTF|02|FTF_CODCX|C|3|0|Cod.Caixinha|Codigo do Caixinha.
FTF|03|FTF_NUM|C|8|0|Numero Int.|Numero interno
FTF|04|FTF_TIPO|C|2|0|Tipo Movto.|Tipo do movimento
FTF|05|FTF_TIMEK|C|8|0|Timekeeper|Codigo do timekeeper
FTF|06|FTF_DTEMIS|D|8|0|Dt. Adto.|Data de Emissao do Adto.
FTF|07|FTF_DTDIG|D|8|0|Dt.Digitacao|Data de digitacäo
FTF|08|FTF_NATURE|C|10|0|Natureza|Natureza
FTF|09|FTF_DTBX|D|8|0|Dt. Baixa|Data de Baixa
FTF|10|FTF_SLDADT|N|16|2|Saldo Adto.|Saldo do Adiantamento
FTF|11|FTF_VALOR|N|16|2|Valor|Valor do Lancamento
FTF|12|FTF_NRDEV|C|8|0|Num. Dev.|Numero da Devolucao.
FTF|13|FTF_DEVADT|C|1|0|Adto. Dev;|Adiantamento Devolvido
FTF|14|FTF_HISTOR|C|30|0|Historico|Historico
FTF|15|FTF_NRADTO|C|8|0|Nro. Adto.|Numeto do Adiantamento
FTF|16|FTF_SEQRP|C|8|0|Seq. Repos.|Seqüencia de Reposição
--- ### FTG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTG|01|FTG_FILIAL|C|6|0|Filial|Filial do Sistema
FTG|02|FTG_CODDES|C|3|0|Cod.Despesa|Codigo da Despesa
FTG|03|FTG_CODFOR|C|6|0|Fornecedor|Codigo do Fornecedor
FTG|04|FTG_LOJA|C|2|0|Loja|Loja do Fornecedor
FTG|05|FTG_NOMFOR|C|40|0|Razão|Razão Social do Fornec.
--- ### FTH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTH|01|FTH_FILIAL|C|6|0|Filial|Filial do Sistema
FTH|02|FTH_CODIGO|C|4|0|Codigo|Codigo da Juncao
FTH|03|FTH_DESCRI|C|40|0|Descricao|Descricao da juncao
FTH|04|FTH_CODCLI|C|6|0|Cod.Cliente|Codigo do cliente
FTH|05|FTH_LOJA|C|2|0|Loja Cliente|Loja Cliente
FTH|06|FTH_CONTAT|C|6|0|Contato|Contato
FTH|07|FTH_CNDPAG|C|3|0|Cond.Pagto.|Condicäo de pagamento
FTH|08|FTH_CUSTOS|C|1|0|Apont.Fatura|Apontamentos na Fatura
FTH|09|FTH_PERFAT|N|3|0|Per.Faturam.|Periodo de Faturamento
FTH|10|FTH_DIACOR|C|2|0|Dia de Corte|Dia de Corte
FTH|11|FTH_CFGPRE|C|3|0|Conf.Pre-Fat|Config.Pre-Fatura
FTH|12|FTH_CFGFAT|C|3|0|Conf.Fatura|Configurador de Fatura
FTH|13|FTH_DISTRI|C|3|0|Distribuicao|Distribuicäo de Faturas
FTH|14|FTH_DTCRIA|D|8|0|Dt. Criacao|Data de Criacäo
FTH|15|FTH_CODETA|C|3|0|Código Etapa|Código da Etapa
FTH|16|FTH_DSCETA|C|40|0|Descrição|Descrição das Etapas
--- ### FTI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTI|01|FTI_FILIAL|C|6|0|Filial|Filial do Sistema
FTI|02|FTI_CODIGO|C|6|0|Referencia|Numero de Referencia
FTI|03|FTI_STATUS|C|1|0|Status|Status do Grupo de Desp.
FTI|04|FTI_DTABER|D|8|0|Abertura|Data de Abertura
FTI|05|FTI_CODUSU|C|6|0|Usuario|Usuario
FTI|06|FTI_DTENCE|D|8|0|Encerramento|Data de Encerramento
FTI|07|FTI_ULTDAT|D|8|0|Dt.Ult.Apont|Data ultimo apontamento
FTI|08|FTI_ROTCHV|C|1|0|Rot. Chave|Rotina Chave
--- ### FTJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTJ|01|FTJ_FILIAL|C|6|0|Filial|Filial do Sistema
FTJ|02|FTJ_REFER|C|6|0|Referencia|Referencia do Lote
FTJ|03|FTJ_CODIGO|C|10|0|Codigo|Codigo do Documento
FTJ|04|FTJ_DATA|D|8|0|Data|Data do Apontamento
FTJ|05|FTJ_DATDIG|D|8|0|Dt.Digitacao|Data de Digitacao
FTJ|06|FTJ_TIPDOC|C|1|0|Tipo Docum.|Tipo de Documento
FTJ|07|FTJ_TIMEK|C|8|0|Timekeeper|Timekeeper da Despesa
FTJ|08|FTJ_NOMTMK|C|30|0|Nome Adotado|Nome Adotado
FTJ|09|FTJ_FORNEC|C|6|0|Fornecedor|Codigo do Fornecedor
FTJ|10|FTJ_LOJA|C|2|0|Loja|Loja do Fornecedor
FTJ|11|FTJ_NFISC|C|8|0|Nota Fiscal|Nota Fiscal
FTJ|12|FTJ_VLCPAG|N|12|2|Vl.Documento|Valor Total do Documento
FTJ|13|FTJ_MOEDA|C|1|0|Moeda|Moeda da Despesa
FTJ|14|FTJ_ORIGEM|C|8|0|Origem|Origem da Despesa
FTJ|15|FTJ_ROTCHV|C|1|0|Rot. Chave|Rotina Chave
FTJ|16|FTJ_CHAVE|C|22|0|Chave|Chave de documento
FTJ|17|FTJ_STATCP|C|1|0|Stat.C.Pagar|Status do Contas a Pagar
FTJ|18|FTJ_OK|C|2|0|OK|Campo para MarkBrowse
FTJ|19|FTJ_DTLANC|D|8|0|Dt.Lancto.|Data do Lancto. Contabil
--- ### FTK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTK|01|FTK_FILIAL|C|6|0|Filial|Filial do Sistema
FTK|02|FTK_CDUSER|C|6|0|Cod. Usuario|Codigo do Usuario
FTK|03|FTK_NOME|C|15|0|Nome|Nome do usuario
FTK|04|FTK_CODCX|C|3|0|Cod.Caixinha|Cod do Caixinha
FTK|05|FTK_VERSLD|C|1|0|Visual.Saldo|Visializar o Saldo
--- ### FTL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTL|01|FTL_FILIAL|C|6|0|Filial|Filial do Sistema
FTL|02|FTL_CODCX|C|3|0|Cód.Caixinha|Código do Caixinha
FTL|03|FTL_NRAPOR|C|8|0|Nro. Aporte|Número do Aporte
FTL|04|FTL_DTEMIS|D|8|0|Data Emissão|Data de Emissão do Aporte
FTL|05|FTL_VLAPOR|N|16|2|Vlr. Aporte|Valor do Aporte
FTL|06|FTL_TABTIT|C|3|0|Tabela Tít.|Tabela do Título
FTL|07|FTL_FILTIT|C|6|0|Fil.Título|Filial do Título
FTL|08|FTL_PRFTIT|C|3|0|Prefixo Tit.|Prefixo do Titulo
FTL|09|FTL_NUMTIT|C|6|0|Num.Título|Número do Título
FTL|10|FTL_PRCTIT|C|1|0|Parcela Tit.|Parcela do Título
FTL|11|FTL_TIPTIT|C|3|0|Tipo Tit.|Tipo do Título
FTL|12|FTL_STATUS|C|1|0|Status|Status
--- ### FTM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTM|01|FTM_FILIAL|C|6|0|Filial|Filial do Sistema
FTM|02|FTM_CODIGO|C|2|0|Codigo|Codigo do Modelo
FTM|03|FTM_DESCRI|C|40|0|Descricäo|Descricäo do Modelo
FTM|04|FTM_ROTINA|C|10|0|Rotina|Nome da Rotina
FTM|05|FTM_TPIMP|C|1|0|Tp.Impressao|Tipo de Impressäo
--- ### FTN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTN|01|FTN_FILIAL|C|6|0|Filial|Filial do Sistema
FTN|02|FTN_CODIGO|C|3|0|Codigo|Codigo da Distribuicao
FTN|03|FTN_DESCRI|C|30|0|Descricao|Descricao Distribuicao
FTN|04|FTN_CODCLI|C|6|0|Cliente|Cliente
FTN|05|FTN_LOJA|C|2|0|Loja|Loja do Cliente
FTN|06|FTN_NOMCLI|C|60|0|Nome|Nome do Cliente
FTN|07|FTN_SEQUEN|C|6|0|Sequencia|Sequencia da Versão
FTN|08|FTN_VIGINI|D|8|0|Vig. Inicial|Data de Vigência Inicial
FTN|09|FTN_VIGFIN|D|8|0|Vig. Final|Data da Vigência Final
FTN|10|FTN_VALIDA|D|8|0|Válida Até|Data de validade
--- ### FTO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTO|01|FTO_FILIAL|C|6|0|Filial|Filial do Sistema
FTO|02|FTO_CODIGO|C|1|0|Codigo|Codigo do Tipo de Docto.
FTO|03|FTO_DESCRI|C|40|0|Descrição|Descrição do Tipo de Doct
--- ### FTP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTP|01|FTP_FILIAL|C|6|0|Filial|Filial do Sistema
FTP|02|FTP_IDPFAT|C|7|0|Id. Pre-Fat.|Id. da Pre-Fatura
FTP|03|FTP_CONTRA|C|10|0|Contrato|Contrato
FTP|04|FTP_ASSUNT|C|11|0|Assunto|Assunto
FTP|05|FTP_STATUS|C|1|0|Status|St. do Contr. ou Assunto
FTP|06|FTP_DATINI|D|8|0|Data Inicial|Data Inicial do Periodo
FTP|07|FTP_DATFIM|D|8|0|Data Final|Data Final do Periodo
FTP|08|FTP_CNDFIN|C|2|0|Cond.Financ.|Condicao Financeira
FTP|09|FTP_HRREAL|N|12|2|Horas Reais|Qtde.Horas Trabalhadas
FTP|10|FTP_VLREAL|N|12|2|Vlr.Real Hon|Vlr.Real dos Honorarios
FTP|11|FTP_HRPFAT|N|12|2|Hr.Pre-Fatur|Horas Pré-Faturadas
FTP|12|FTP_VLHONO|N|12|2|Vl.Honorario|Valor dos Honorarios
FTP|13|FTP_VLDESP|N|12|2|Vl.Despesas|Valor das Despesas
FTP|14|FTP_VLEVCO|N|12|2|Vl.Ev.Contr.|Valor dos Ev. Contratuais
FTP|15|FTP_VLEVDE|N|12|2|Vl. Ev. Desp|Valor de Ev. de Despesas
FTP|16|FTP_VLCFIN|N|12|2|Vl.Cnd.Finan|Valor da Cond.Financ.
FTP|17|FTP_VLRREF|N|12|2|Referencia|Valor de Referencia
FTP|18|FTP_DSCCFI|N|12|2|Desc.C.Finan|Desconto S/ Cond.Financ.
FTP|19|FTP_CONTAT|C|6|0|Contato|Contato
--- ### FTQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTQ|01|FTQ_FILIAL|C|6|0|Filial|Filial do Sistema
FTQ|02|FTQ_DESCRI|C|60|0|Descrição|Descrição da Exceção
FTQ|03|FTQ_CONTRA|C|10|0|Contrato|Numero do contrato
FTQ|04|FTQ_DESCON|C|60|0|Descr.Contr.|Descricao do contrato
FTQ|05|FTQ_ASSUNT|C|11|0|Assunto|Assunto
FTQ|06|FTQ_CODEVC|C|3|0|Cod.Ev.Cont.|Cod.Tipo EventoContratual
FTQ|07|FTQ_VLRREA|N|14|2|Vlr.Original|Vlr. Original do Tp. Desp
FTQ|08|FTQ_PERCAP|N|6|2|% a Cobrar|Percentual a Cobrar
FTQ|09|FTQ_VLRCOB|N|14|2|Vlr. Cobrado|Valor Cobrado
FTQ|10|FTQ_VLRVIS|N|14|2|Vlr.Efetivo|Valor Efetivo
--- ### FTR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTR|01|FTR_FILIAL|C|6|0|Filial|Filial do Sistema
FTR|02|FTR_NUMFAT|C|6|0|Num.Fatura|Numero da Fatura
FTR|03|FTR_IDFAT|C|7|0|Id. Fatura|Rel.c/Pre ou Fatura
FTR|04|FTR_DATA|D|8|0|Data Fatura|Data da fatura
FTR|05|FTR_CODCLI|C|6|0|Cod.Cliente|Codigo do Cliente
FTR|06|FTR_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FTR|07|FTR_CONTAT|C|6|0|Cod.Contato|Codigo do Contato
FTR|08|FTR_PREFIX|C|3|0|Pref.Titulo|Prefixo do Titulo Ct.Rec.
FTR|09|FTR_TIPO|C|3|0|Tipo Titulo|Tipo do Titulo no C.Receb
FTR|10|FTR_NATURE|C|10|0|Natureza|Natureza do Titulo
FTR|11|FTR_MOEDA|C|1|0|Moeda|Moeda da Pre-fatura
FTR|12|FTR_VLRHON|N|12|2|Vl.Honorario|Valor dos Honorarios
FTR|13|FTR_VLDESP|N|12|2|Vlr.Despesas|Valor das Despesas
FTR|14|FTR_VLEVCO|N|12|2|Vl. Ev.Contr|Vlr. Eventos Contratuais
FTR|15|FTR_VLEVDE|N|12|2|Vl. Ev. Desp|Valor de Ev. Despesas
FTR|16|FTR_VLRCFI|N|12|2|Vlr.Cond.Fin|Valor da Cond. Financ.
FTR|17|FTR_ABATSU|N|12|2|Abat.Suplem.|Abatimento Suplementar
FTR|18|FTR_CNDPAG|C|3|0|Cond.Pagto.|Condicäo de Pagamento
FTR|19|FTR_DISTRI|C|3|0|Distribuida|Fatura foi distribuida
FTR|20|FTR_STATUS|C|1|0|Situacao|Situacäo da Fatura
FTR|21|FTR_DTCANC|D|8|0|Cancelamento|Data de cancelamento
FTR|22|FTR_ORIGEM|C|10|0|Origem|Rotina que gerou a fatura
FTR|23|FTR_ADENTI|C|1|0|Ent. Adiant.|Entidade do Adiantamento
FTR|24|FTR_ADCOD|C|11|0|Cod.Ent.Ad.|Código da Ent. de Adiant.
FTR|25|FTR_ADTIPO|C|1|0|Tipo Adiant.|Tipo de Adiantamento.
FTR|26|FTR_CODMSG|C|6|0|Código Msg|Código da Mensagem Fatura
FTR|27|FTR_MSG|M|80|0|Mensagem|Mensagem da Fatura
FTR|28|FTR_DTLANC|D|8|0|Dt.Lcto.Cont|Data Lancto. Contábil
FTR|29|FTR_DTLNCA|D|8|0|Dt.Lanc.Canc|Data do Lanc.Contab.Canc.
--- ### FTS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTS|01|FTS_FILIAL|C|6|0|Filial|Filial do Sistema
FTS|02|FTS_TIPO|C|1|0|Tipo Modelo|Tipo do Modelo/Template
FTS|03|FTS_NUMERO|C|6|0|Numero|Numero da Pré-Fat./Fatura
FTS|04|FTS_SEQ|C|2|0|Sequencia|Sequencia do registro
FTS|05|FTS_MODELO|C|3|0|Modelo|Código do Modelo
FTS|06|FTS_CODCLI|C|6|0|Cliente|Código do Cliente
FTS|07|FTS_LOJA|C|2|0|Loja|Loja do Cliente
FTS|08|FTS_VLREAL|N|12|2|Vlr. Real|Valor Real dos Honorários
FTS|09|FTS_VLRHON|N|12|2|Vlr.Honor.|Valor dos Honorários
FTS|10|FTS_VLDESP|N|12|2|Vlr. Despesa|Valor das Despesas
FTS|11|FTS_VLEVCO|N|12|2|Vlr.Ev.Honor|Vlr.Eventos de Honorário
FTS|12|FTS_VLEVDE|N|12|2|V.Ev.Despesa|Valor de Ev. de Despesas
FTS|13|FTS_VLRCFI|N|12|2|V.C.Financ.|Vlr. Cond. Financeira
FTS|14|FTS_ABATSU|N|12|2|Abat. Suplem|Abatimento Suplementar
FTS|15|FTS_IRRF|N|12|2|IRRF|Valor do IRRF previsto
FTS|16|FTS_ISS|N|12|2|ISS|Valor do ISS previsto
FTS|17|FTS_INSS|N|12|2|INSS|Valor do INSS previsto
FTS|18|FTS_CSLL|N|12|2|CSLL|Valor do CSLL previsto
FTS|19|FTS_PIS|N|12|2|PIS|Valor do PIS previsto
FTS|20|FTS_COFINS|N|12|2|COFINS|Valor do COFINS previsto
FTS|21|FTS_TXCONV|N|9|2|Taxa de Conv|Taxa de Conversão
FTS|22|FTS_CONTRA|C|10|0|Contrato|Código do Contrato
FTS|23|FTS_CNDFIN|C|2|0|Cond.Financ.|Condição Financeira
FTS|24|FTS_MOEDA|C|1|0|Moeda|Moeda da Fatura/Pré-Fat.
--- ### FTT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTT|01|FTT_FILIAL|C|6|0|Filial|Filial do Sistema
FTT|02|FTT_CODETA|C|3|0|Código Etapa|Código da  Etapa
FTT|03|FTT_DESCRI|C|40|0|Descr.Etapa|Descricao da Etapa
--- ### FTU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTU|01|FTU_FILIAL|C|6|0|Filial|Filial do Sistema
FTU|02|FTU_CODDES|C|3|0|Cod.Despesa|Codigo da Despesa
FTU|03|FTU_CODUSR|C|6|0|Usuario|Codigo do Usuario
FTU|04|FTU_NOMUSR|C|40|0|Nome Usuario|Nome do Usuario
FTU|05|FTU_REQUIS|C|1|0|Requisicäo?|Permite Requisicäo?
FTU|06|FTU_VOUCHE|C|1|0|Voucher?|Permite Voucher?
FTU|07|FTU_DOCFIS|C|1|0|Doc.Fiscal?|Permite Doc. Fiscal?
--- ### FTV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTV|01|FTV_FILIAL|C|6|0|Filial|Filial do Sistema
FTV|02|FTV_CODIGO|C|3|0|Codigo|Codigo do Modelo
FTV|03|FTV_DESCRI|C|40|0|Descrição|Descrição do Modelo
FTV|04|FTV_MOEDA|C|1|0|Moeda|Moeda do Modelo
FTV|05|FTV_IDIOMA|C|3|0|Idioma|Idioma do Modelo
FTV|06|FTV_MASCVL|C|16|0|Máscara Vlr.|Máscara de Valores
FTV|07|FTV_MASCDT|C|10|0|Máscara Data|Máscara de Data
FTV|08|FTV_CTAREC|C|1|0|Ctas.Receber|Contas a Receber
FTV|09|FTV_NUMDIA|N|3|0|Dias C.Receb|Dias do Ctas. a Receber
FTV|10|FTV_ARQUIV|C|20|0|Arquivo|Arquivo de Impressão
FTV|11|FTV_SUMARY|C|30|0|Sumários|Sumários do Modelo
--- ### FTW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTW|01|FTW_FILIAL|C|6|0|Filial|Filial do Sistema
FTW|02|FTW_CODIGO|C|3|0|Codigo|Codigo do Modelo
FTW|03|FTW_SEQ|C|3|0|Sequencia|Sequencia da Mensagem
FTW|04|FTW_DESCRI|C|20|0|Titulo|Titulo do Sumario
FTW|05|FTW_MENSAG|M|80|0|Mensagem|Mensagem do Modelo
FTW|06|FTW_CODMEN|C|6|0|Código Mens.|Código da Mensagem
--- ### FTX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTX|01|FTX_FILIAL|C|6|0|Filial|Filial do Sistema
FTX|02|FTX_CODIGO|C|2|0|Codigo|Codigo
FTX|03|FTX_DESCRI|C|40|0|Descricao|Descricao
FTX|04|FTX_CALCDE|C|1|0|Calc.Desc.|Calcula Desconto
FTX|05|FTX_CONTAT|C|1|0|Sep.Contato?|Separa por Contato?
--- ### FTZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FTZ|01|FTZ_FILIAL|C|6|0|Filial|Filial do Sistema
FTZ|02|FTZ_CHAVE|C|6|0|Chave|Chave de Acesso
FTZ|03|FTZ_SEQ|C|3|0|Sequencia|Sequencia de Acesso
FTZ|04|FTZ_TEXTO|C|80|0|Linha|Linha de Descricao
FTZ|05|FTZ_CAMPO|C|10|0|Campo|Campo onde vai ser gravad
--- ### FU1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FU1|01|FU1_FILIAL|C|6|0|Filial|Filial do Sistema
FU1|02|FU1_REFER|C|6|0|Grupo|Grupo
FU1|03|FU1_CODDOC|C|10|0|Nro Document|Nro Documento
FU1|04|FU1_IDENT|C|8|0|COD IDENTIF|COD IDENTIF
FU1|05|FU1_TIPOD|C|3|0|COD DESPESA|COD DESPESA
FU1|06|FU1_TIMEK|C|8|0|TimeKeeper|TimeKepper
FU1|07|FU1_SJCASO|C|9|0|Caso|Caso
FU1|08|FU1_SJCLIE|C|6|0|Cliente|Cliente
FU1|09|FU1_LOJA|C|2|0|Loja|Loja
FU1|10|FU1_MOEDA|C|1|0|Moeda|Moeda
FU1|11|FU1_VALOR|N|12|2|Valor|Valor
FU1|12|FU1_SALDO|N|18|7|Saldo|Saldo
FU1|13|FU1_FILDES|C|2|0|Filial Desp|Filial Desp
FU1|14|FU1_MANUT|C|2|0|Manutencao|Manutencao
FU1|15|FU1_CODRAT|C|6|0|Cod Narrativ|Cod. de Narrativa
FU1|16|FU1_DATA|C|10|0|Data Apont|Data Apont (AAAA-MM-DD)
FU1|17|FU1_OK|C|1|0|Controle|Controle
FU1|18|FU1_DTSIST|C|8|0|DATA SISTEMA|DATA SISTEMA
FU1|19|FU1_HRSIST|C|8|0|HORA SISTEMA|HORA SISTEMA
FU1|20|FU1_OPERAC|C|15|0|OPERACAO|OPERACAO
FU1|21|FU1_PROCED|C|15|0|PROCEDIMENTO|PROCEDIMENTO
FU1|22|FU1_MSGERR|C|40|0|MSG ERROR|MSG ERROR
FU1|23|FU1_SEQ|C|6|0|SEQUENCIA|SEQUENCIA
--- ### F00
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F00|01|F00_FILIAL|C|6|0|Filial|Filial do Sistema
F00|02|F00_UF|C|2|0|UF|Sigla do Estado
F00|03|F00_CFOP|C|4|0|CFOP|CFOP
F00|04|F00_CODAJU|C|1|0|Cód.Ajuste|Código do Ajuste
F00|05|F00_DTINIV|D|8|0|Dt.Início|Data Início Vigência
F00|06|F00_DTFIMV|D|8|0|Dt.Final|Data Final Vigência
--- ### F01
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F01|01|F01_FILIAL|C|6|0|Filial|Filial
F01|02|F01_PERIOD|C|6|0|Período|Período da Movimentação
F01|03|F01_PRODUT|C|15|0|Produto|Produto
F01|04|F01_PERRAT|N|6|2|Perc. Rat.|Percentual Rateio
F01|05|F01_PRCM|N|14|2|Prç. Médio|Prç. Médio
F01|06|F01_FICHA|C|1|0|Ficha|Ficha
F01|07|F01_INSCON|C|15|0|Ins.Conj|Código insumo conjunto
--- ### F02
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F02|01|F02_FILIAL|C|6|0|Filial|Filial do Sistema
F02|02|F02_TIPO|C|1|0|Tp. Reg.|Tipo de Registro
F02|03|F02_MATRIZ|C|1|0|Matriz?|Matriz?
F02|04|F02_EMPRAS|C|45|0|Razão Social|Razão Social
F02|05|F02_EMPCGC|C|14|0|CNPJ|CNPJ
F02|06|F02_FORRAZ|C|45|0|Razão Forn.|Razão Social Fornecedor
F02|07|F02_FORCGC|C|14|0|CNPJ|CNPJ
F02|08|F02_MESREF|C|2|0|Mês Ref.|Mês de Referência
F02|09|F02_ANOREF|C|4|0|Ano ref.|Ano Referência
F02|10|F02_VLTOTN|N|14|2|Vlr. Total|Valor Total Notas
F02|11|F02_VLDEDU|N|14|2|Vlr.Dedutiv.|Valor Parc. Dedutível
--- ### F04
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F04|01|F04_FILIAL|C|6|0|Filial|Filial do Sistema
F04|02|F04_PERIOD|D|8|0|Período|Período da Movimentação
F04|03|F04_PROD|C|15|0|Prod. Ficha|Produto da Ficha
F04|04|F04_FICHA|C|2|0|Ficha|Identificação da Ficha
F04|05|F04_ID|C|6|0|Id Cabec|Id do Cabeçalho
F04|06|F04_STATUS|C|1|0|Status|Status
F04|07|F04_PROC|C|1|0|Processa|Controle Processamento
F04|08|F04_FATORI|N|14|6|Fator ICMS|Fator cálculo ICMS
F04|09|F04_FATORC|N|14|6|Fator Custo|Fator cálculo Custo
F04|10|F04_OBSER|C|60|0|Observação|Observação da Ficha
F04|11|F04_QTDE|N|14|6|Quantidade|Quantidade
--- ### F06
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F06|01|F06_FILIAL|C|6|0|Filial|Filial do Sistema
F06|02|F06_REGRA|C|3|0|Hipótese|Hipótese
F06|03|F06_DREGRA|C|60|0|Descr.Hip|Desc.Hipótese
F06|04|F06_PRODEL|C|15|0|Prd.Elaborad|Prd.Elaborado
F06|05|F06_DPRDEL|C|70|0|Desc.Prd.Ela|Desc.Prd.Elaborado
F06|06|F06_CODINS|C|15|0|Cód.Insumo|Cód.Insumo
F06|07|F06_DINSUM|C|70|0|Desc.Insumo|Desc.Insumo
F06|08|F06_CODLAN|C|6|0|Cod. Lanc.|Código do Lançamento
F06|09|F06_DCODL|C|60|0|Desc.Cod.Lan|Desc.Código de Lançamento
--- ### F07
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F07|01|F07_FILIAL|C|6|0|Filial|Filial do sistema
F07|02|F07_PER|D|8|0|Per. Apur.|Período de Apuração
F07|03|F07_ID|C|46|0|Id Cont.|ID Contador
F07|04|F07_INDPRO|C|1|0|nd.Proc.|Ind. Proc.Referenciado
F07|05|F07_NUMPRO|C|10|0|Num.Proc.|Num. Proc. Referenciado
F07|06|F07_IDITEM|C|8|0|Id Item Proc|Id. Item do Processo
F07|07|F07_INDAUT|C|1|0|Aut. Ação Ju|Autoria da Ação Judicial
--- ### F08
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F08|01|F08_FILIAL|C|6|0|Filial|Filial do sistema
F08|02|F08_CODIGO|C|3|0|Código|Código
F08|03|F08_GRPCST|C|10|0|Grupo CST|Grupo CST de IPI
F08|04|F08_DESCRI|C|50|0|Descrição|Desc. Enquadramento Legal
F08|05|F08_DESCR2|C|6|0|Descr2|Descr2
F08|06|F08_DESCRV|M|10|0|Descr. Compl|Descrição Complementar
--- ### F09
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F09|01|F09_FILIAL|C|6|0|Filial|Filial do Sistema
F09|02|F09_TES|C|3|0|Cod TES|Código do TES
F09|03|F09_UF|C|2|0|UF|Sigla do Estado
F09|04|F09_CODIPM|C|60|0|Cod. IPM|Codigo IPM
F09|05|F09_DSCIPM|C|20|0|Decrição|Decrição Código IPM
--- ### F0A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0A|01|F0A_FILIAL|C|6|0|Filial|Filial do sistema
F0A|02|F0A_TPMOV|C|1|0|Tipo Mov.|Tipo do Movimento
F0A|03|F0A_SERIE|C|3|0|Série NF|Série do documento fiscal
F0A|04|F0A_DOC|C|9|0|Doc. Fiscal|Número do documento
F0A|05|F0A_CLIFOR|C|6|0|Cli/For|Cliente / Fornecedor
F0A|06|F0A_LOJA|C|2|0|Loja|Loja
F0A|07|F0A_ITEM|C|4|0|Num. Item|Item do documento
F0A|08|F0A_COD|C|15|0|Cod. Produto|Código do Produto
F0A|09|F0A_LOTE|C|20|0|Lote|Lote
F0A|10|F0A_QTDLOT|N|13|3|Qtde. Lote|Qtde. de produto no lote
F0A|11|F0A_FABRIC|D|8|0|Dt. Fabric.|Data de Fabricação
F0A|12|F0A_VALID|D|8|0|Dt. Valid.|Data de Validade
F0A|13|F0A_CODAGR|C|20|0|Cod. Agreg.|Código de Agregação
F0A|14|F0A_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal
--- ### F0D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0D|01|F0D_FILIAL|C|6|0|Filial|Filial do Sistema
F0D|02|F0D_CODPRD|C|15|0|Cod. Produto|Código do Produto
F0D|03|F0D_DTINIP|D|8|0|Dt. Ini. Per|Data de Início do Período
F0D|04|F0D_DTFIMP|D|8|0|Dt. Fim. Per|Data Final do Periodo
F0D|05|F0D_VLEEST|N|14|2|Vl.Ent.Est|Valor Entradas do Estado
F0D|06|F0D_VLEINT|N|14|2|Vl.Ent.Int|Valor Entr. Interestadual
F0D|07|F0D_VLEEXT|N|14|2|Vl.Ent.Ext|Valor Entradas Exterior
--- ### F0E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0E|01|F0E_FILIAL|C|6|0|Filial|Filial do Sistema
F0E|02|F0E_NUMERO|C|10|0|Numero|Numero do processo
F0E|03|F0E_TIPO|C|1|0|Tp. processo|Tipo do processo
F0E|04|F0E_CODIGO|C|14|0|Cod.Susp.Exi|Cod.Susp.Exigibilidade
F0E|05|F0E_INDSUS|C|2|0|Ind.Susp.Exi|Ind.Susp.Exigibilidade
F0E|06|F0E_DTDECI|D|8|0|Dt decisão|Data da decisão
F0E|07|F0E_INDDEP|C|1|0|Dep.Mont.Int|Depósito Montante Integ.
--- ### F0F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0F|01|F0F_INDPAA|C|1|0|Pert PAA?|Pert. Prog. Aq. Alim.
F0F|02|F0F_FILIAL|C|6|0|Filial|Filial do Sistema
F0F|03|F0F_CODFIL|C|6|0|Cód. Filial|Código da Filial
F0F|04|F0F_CAEPF|C|14|0|Número CAEPF|Número do CAEPF
F0F|05|F0F_TPCAEP|C|1|0|Tipo CAEPF|Tipo do CAEPF
F0F|06|F0F_OBRA|C|6|0|Código CNO|Código do CNO
F0F|07|F0F_CNO|C|14|0|Número CNO|Número do CNO
F0F|08|F0F_TPOBRA|C|1|0|Tipo de Obra|Tipo de Obra
F0F|09|F0F_ASSDES|C|1|0|Assoc. Desp.|Associação Desportiva
--- ### F0G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0G|01|F0G_FILIAL|C|6|0|Filial|Filial
F0G|02|F0G_CEST|C|7|0|CEST|Cod. Especificador ST
F0G|03|F0G_DESCRI|C|50|0|Descrição|Descrição
F0G|04|F0G_CONV|C|10|0|Nro.convênio|Convênio CEST
F0G|05|F0G_DESCR2|C|6|0|Descr2|Descr2
F0G|06|F0G_DESCRV|M|10|0|Descricao|Desc. Especificador ST
--- ### F0H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0H|01|F0H_FILIAL|C|6|0|Filial|Filial do Sistema
F0H|02|F0H_ID|C|15|0|Chave|Chave
F0H|03|F0H_TABORI|C|3|0|Tabela Orig.|Tabela Original
F0H|04|F0H_RECTAB|N|10|0|Recno Ori|Recno Original
F0H|05|F0H_FICHA|C|2|0|Ficha|Ficha
F0H|06|F0H_NF|C|9|0|Num Docto.|Número do Documento
F0H|07|F0H_SERIE|C|3|0|Série|Série do Documento
F0H|08|F0H_DATA|C|20|0|Data|Data de Emissão
F0H|09|F0H_FORNEC|C|30|0|Fornecedor|Fornecedor da NF
F0H|10|F0H_ITEM|C|4|0|Num. Item|Número do Item
F0H|11|F0H_PRODUT|C|15|0|Produto|Produto
F0H|12|F0H_QTD|N|14|6|Quantidade|Quantidade
F0H|13|F0H_ICMS|N|14|6|Vl. ICMS|Valor do ICMS
F0H|14|F0H_CUSTO|N|14|6|Vl. CUSTO|Valor do CUST
F0H|15|F0H_CUSOLD|N|14|6|Custo Ant|Valor do CUSTO Ant.
F0H|16|F0H_CUSNEW|N|14|6|Custo|Novo Vl. Custo
F0H|17|F0H_ICMOLD|N|14|6|ICMS Ant|Valor do ICMS Ant.
F0H|18|F0H_ICMNEW|N|14|6|Vl. ICMS|Novo Vl. ICMS
F0H|19|F0H_LGNOME|C|20|0|Log Nome|Log Data
F0H|20|F0H_LGDATA|C|20|0|Log Data|Log Data
--- ### F0I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0I|01|F0I_FILIAL|C|6|0|Filial|Filial do Sistema
F0I|02|F0I_PER|D|8|0|Per.Apuracao|Periodo da Apuracao
F0I|03|F0I_LIVRO|C|1|0|Livro|Livro de Apuracao
F0I|04|F0I_UF|C|2|0|UF|Unidade Federativa
F0I|05|F0I_DEBDIF|N|14|2|Deb.Difal|Debito do Difal
F0I|06|F0I_OUTDEB|N|14|2|Out.Deb|Outros Debitos Difal
F0I|07|F0I_ESTCRD|N|14|2|Est.Cred|Estorno de Credito
F0I|08|F0I_OUTCRE|N|14|2|Out.Cred|Outros Creditos Difal
F0I|09|F0I_SADIF|N|14|2|Sld.Ant.Dif|Saldo Credor Ant. Difal
F0I|10|F0I_CRDDIF|N|14|2|Cred.Dif|Credito do Difal
F0I|11|F0I_ESTDEB|N|14|2|Est.Deb.|Estorno do Debito Difal
F0I|12|F0I_DEVDIF|N|14|2|Sld.Dev.Dif|Saldo Devedor Difal
F0I|13|F0I_DEDDIF|N|14|2|Ded.Difal|Deducoes do Difal
F0I|14|F0I_DIFREC|N|14|2|Dif.Recolher|Difal a recolher
F0I|15|F0I_SPDIF|N|14|2|Sld.Dif|Saldo credor Difal
F0I|16|F0I_DEBESP|N|14|2|Deb.Esp.|Debitos Especiais Difal
F0I|17|F0I_DEBFCP|N|14|2|Deb.Fecp|Debitos FECP
F0I|18|F0I_SAFCP|N|14|2|Sld.Ant.FECP|Saldo Credor Ant. FECP
F0I|19|F0I_CRDFCP|N|14|2|Cred.FECP|Credito do FECP
F0I|20|F0I_FCPREC|N|14|2|FCP.Recolher|FECP a recolher
F0I|21|F0I_SPFCP|N|14|2|Sld FECP|Saldo Credor FECP
F0I|22|F0I_OUTDBF|N|14|2|Out.Deb.FECP|Outros Débitos FECP
F0I|23|F0I_OUTCRF|N|14|2|Out.Cre.FECP|Outros Créditos FECP
F0I|24|F0I_DEVFCP|N|14|2|Sld.Dev.FECP|Saldo Devedor FECP
F0I|25|F0I_DEDFCP|N|14|2|Ded.FECP|Deduções do FECP
F0I|26|F0I_DBESPF|N|14|2|Deb.Esp.FECP|Débitos Especiais FECP
F0I|27|F0I_ESTDBF|N|14|2|Est.Deb.FECP|Estorno do Débito FECP
F0I|28|F0I_ESTCRF|N|14|2|Est.Cre.FECP|Estorno do Crédito FECP
--- ### F0J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0J|01|F0J_FILIAL|C|6|0|Filial|Filial do Sistema
F0J|02|F0J_PER|D|8|0|Per.Apuracao|Periodo da Apuracao
F0J|03|F0J_LIVRO|C|1|0|Livro|Livro de Apuracao
F0J|04|F0J_UF|C|2|0|UF|Unidade Federativa
F0J|05|F0J_NUMTIT|C|9|0|Num.Tit|Numero de Titulo gerado
F0J|06|F0J_PRFTIT|C|3|0|Prefixo Tit|Prefixo do Titulo Gerado
F0J|07|F0J_PARC|C|3|0|Parcela|Parcela do Titulo Gerado
F0J|08|F0J_TPTIT|C|3|0|Tipo Tit.|Tipo do Titulo
F0J|09|F0J_FORN|C|6|0|Fornecedor|Fornecedor do Titulo
F0J|10|F0J_LOJA|C|2|0|Loja|Loja do Fornecedor
F0J|11|F0J_VALOR|N|14|2|Valor|Valor do Titulo
F0J|12|F0J_GNRE|C|12|0|GNRE|Numero da GNRE
F0J|13|F0J_DTVENC|D|8|0|Vencimento|Vencimento do Titulo
F0J|14|F0J_TIPO|C|1|0|Tipo Inf.|Tipo das informacoes
--- ### F0K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0K|01|F0K_FILIAL|C|6|0|Filial|Filial do Sistema
F0K|02|F0K_PER|D|8|0|Per.Apuracao|Periodo da Apuracao
F0K|03|F0K_LIVRO|C|1|0|Livro|Livro de Apuracao
F0K|04|F0K_UF|C|2|0|UF|Unidade Federativa
F0K|05|F0K_CODAPU|C|8|0|Lanc. Apur|Cod Lancto Apuracao
F0K|06|F0K_VALOR|N|14|2|Valor|Valor Codigo Lancamento
F0K|07|F0K_DESCR|C|50|0|Descr Lancto|Descricao Codigo Lancto
F0K|08|F0K_GNRE|C|12|0|GNRE|Codigo da GNRE
F0K|09|F0K_SUBITE|C|10|0|SubItem|SubItem da Apuracao
F0K|10|F0K_TPLANC|C|38|0|Tp Lanc.|Tipo de lancamento
F0K|11|F0K_PROCES|C|10|0|Num processo|Número do processo
F0K|12|F0K_PROIND|C|1|0|Aut Ação Jud|Autoria da Ação Judicial
F0K|13|F0K_PROCTP|C|1|0|Tp. processo|Tipo de Processo
F0K|14|F0K_ITPROC|C|8|0|Item Process|Item do Processo
--- ### F0L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0L|01|F0L_FILIAL|C|6|0|Filial|Filial do Sistema
F0L|02|F0L_UF|C|2|0|Estado|Sigla do Estado
F0L|03|F0L_INSCR|C|18|0|Ins. Estad.|Inscricao Estadual
F0L|04|F0L_CGC|C|14|0|CNPJ|CNPJ do Contribuinte
--- ### F0M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0M|01|F0M_FILIAL|C|6|0|Filial|Filial do Sistema
F0M|02|F0M_REGRA|C|1|0|Regra Calc|Regra de Calculo
F0M|03|F0M_SITUA|C|1|0|Situação|Situação
F0M|04|F0M_DTFECH|D|8|0|Dt. Fecham.|Dt. Fechamento de estoque
F0M|05|F0M_CODIGO|C|15|0|Codigo|Codigo do Produto
F0M|06|F0M_CST|C|3|0|Sit.Tribut.|Situacao Tributaria
F0M|07|F0M_BASICM|N|14|2|Base Unit|Base unitaria de ICM
F0M|08|F0M_ALIQ|N|14|4|Aliq. ICM|Aliquota de ICMS
F0M|09|F0M_VALICM|N|14|2|Vlr.Unit.ICM|Valor unitario ICMS
F0M|10|F0M_MVA|N|6|2|MVA|Margem Vlr. ICMS/ST
F0M|11|F0M_QUANT|N|14|2|Quantidade|Quantidade em estoque
F0M|12|F0M_VALCMD|N|14|4|V. C. Med.|Valor Custo Médio
F0M|13|F0M_CLIFOR|C|6|0|Cli/For|Cliente / Fornecedor
F0M|14|F0M_LOJA|C|2|0|Loja|Loja Cliente / Fornecedor
F0M|15|F0M_TOTICM|N|14|2|Total ICMS|Valor total de ICMS
F0M|16|F0M_DESPRO|C|70|0|Des. Produto|Descrição Produto
F0M|17|F0M_UM|C|2|0|Unidade|Unidade de Medida
F0M|18|F0M_VUNIT|N|16|6|Valor Unit.|Valor Unitário
F0M|19|F0M_TPCF|C|1|0|Cli/For|Cliente/Fornecedor
F0M|20|F0M_CONTA|C|20|0|Cta Contabil|Conta Contábil
F0M|21|F0M_MOTINV|C|2|0|Mot. Invent.|Motivo de Inventário
F0M|22|F0M_QTDCST|N|14|2|Qtd. Por CST|Quantidade por CST
--- ### F0N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0N|01|F0N_FILIAL|C|6|0|Filial|Filial do Sistema
F0N|02|F0N_UF|C|2|0|UF|UF
F0N|03|F0N_CODREC|C|15|0|Cod. Receita|Código da Receita
F0N|04|F0N_AMBWS|C|1|0|Ambiente|Ambiente Web Service.
F0N|05|F0N_CODSEF|C|3|0|Cod. Sefaz|Código Sefaz.
F0N|06|F0N_TIPO|C|1|0|TIPO|Tipo Inf. Extra
F0N|07|F0N_TAMANH|C|3|0|Tamanho|Tamanho
F0N|08|F0N_DECIMA|C|2|0|Decimal|Decimal
F0N|09|F0N_TITULO|C|60|0|Título|Título Sefaz.
F0N|10|F0N_OBRIGA|C|1|0|Obrg?|Campo Obrigatório ?
F0N|11|F0N_CODINT|C|3|0|Cod. Int.|Código Interno
F0N|12|F0N_DTATLZ|D|8|0|Dt. Atualiza|Data de Atualização
F0N|13|F0N_ATUALI|C|1|0|Atualiza|Atualização Inf. Extra
--- ### F0Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0Q|01|F0Q_FILIAL|C|6|0|Filial|Filial do Sistema
F0Q|02|F0Q_DTFECH|D|8|0|Dt. Fecham.|Dt. Fechamento de estoque
F0Q|03|F0Q_CODIGO|C|15|0|Codigo|Codigo do Produto
F0Q|04|F0Q_MOTINV|C|2|0|Mot Inv|Motivo do inventário
F0Q|05|F0Q_DESPRO|C|70|0|Des. Produto|Descrição Produto
F0Q|06|F0Q_MODAL|C|1|0|Alteração?|Motivo da Alteração
F0Q|07|F0Q_ID|C|36|0|Chave|Chave
F0Q|08|F0Q_PERIOD|C|6|0|Per.Apuração|Período de Apuração
F0Q|09|F0Q_FECP|N|6|2|Aliq. FECP|Alíquota FECP
F0Q|10|F0Q_CRGTRB|N|6|2|Carga Trb.|Carga Tributária
F0Q|11|F0Q_MVA|N|6|2|MVA|Margem Vlr. ICMS/ST
F0Q|12|F0Q_PREDBS|N|6|2|Red. Base ST|Perc. de Redução ICMS ST
--- ### F0R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0R|01|F0R_FILIAL|C|6|0|Filial|Filial do Sistema
F0R|02|F0R_UF|C|2|0|UF|Estado
F0R|03|F0R_PERIOD|C|6|0|Período|Período
F0R|04|F0R_INDICE|N|16|4|Indicador|Indicador
--- ### F0S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0S|01|F0S_FILIAL|C|6|0|Filial|Filial do Sistema
F0S|02|F0S_DOCCRE|C|9|0|Doc. Créd.|Documento Crédito
F0S|03|F0S_SERCRE|C|3|0|Série Doc.|Série Doc. Crédito
F0S|04|F0S_FORCRE|C|6|0|Forn. Créd.|Código Fornecedor Crédito
F0S|05|F0S_LOJCRE|C|2|0|Loja Créd.|Loja Fornecedor Crédito
F0S|06|F0S_EMICRE|D|8|0|Data Emis.|Data Emissão Doc. Crédito
F0S|07|F0S_ESPCRE|C|5|0|Espécie|Espécie
F0S|08|F0S_DOCSAI|C|9|0|Doc. Saída|Número Documento Saída
F0S|09|F0S_SERSAI|C|3|0|Série Saída|Série do Documento Saída
F0S|10|F0S_CLISAI|C|6|0|Cliente|Código do Cliente
F0S|11|F0S_LOJSAI|C|2|0|Loja|Loja do Cliente
F0S|12|F0S_EMISAI|D|8|0|Data Emis.|Data de Emissão Saída
F0S|13|F0S_UFSAI|C|2|0|UF Cliente|UF do Cliente
F0S|14|F0S_ESPSAI|C|5|0|Espécie|Espécie
F0S|15|F0S_CRESAI|N|14|2|Vlr. Cred.|Valor do Crédito
F0S|16|F0S_SDOCCR|C|3|0|Série Doc.|Série Doc. Crédito
F0S|17|F0S_SDOCSA|C|3|0|Série Saída|Série do Documento Saída
--- ### F0T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0T|01|F0T_FILIAL|C|6|0|Filial|Filial do Sistema
F0T|02|F0T_FILAPU|C|6|0|Fil. Orig|Filial Original
F0T|03|F0T_PER|D|8|0|Per.Apuração|Período de Apuração
F0T|04|F0T_CHAVE|C|36|0|Chave|Chave
F0T|05|F0T_TIPO|C|1|0|Tipo Det.|Tipo de Detalhamento
F0T|06|F0T_NUMNF|C|9|0|Número Nota|Número da Nota Fiscal
F0T|07|F0T_SER|C|3|0|Série NF|Série da Nota Fiscal
F0T|08|F0T_DTEMI|D|8|0|Data Emissão|Data de Emissão
F0T|09|F0T_DTRECB|D|8|0|Data Recebim|Data de Recebimento
F0T|10|F0T_CFOP|C|4|0|CFOP|CFOP
F0T|11|F0T_ITEM|C|4|0|Item NF|Item da Nota Fiscal
F0T|12|F0T_MODELO|C|5|0|Modelo NF|Modelo Documento Fiscal
F0T|13|F0T_NUMTIT|C|9|0|Número do Tí|Número do Título
F0T|14|F0T_PREFIX|C|3|0|Prefixo|Prefixo do Título
F0T|15|F0T_PARC|C|3|0|Parcela|Parcela do Título
F0T|16|F0T_IDCF8|C|6|0|Demais Docs.|Demais Documentos
F0T|17|F0T_PERREC|N|6|2|Perc.Receb.|Percentual de Recebimento
F0T|18|F0T_VLCONT|N|14|2|Vl.Contábil|Valor Contábil
F0T|19|F0T_CSTPIS|C|2|0|CST PIS|CST PIS
F0T|20|F0T_CSTCOF|C|2|0|CST COF|CST COF
F0T|21|F0T_BASPIS|N|14|2|Base PIS|Base de Cálculo PIS
F0T|22|F0T_BASCOF|N|14|2|Base COF|Base de Cálculo COF
F0T|23|F0T_ALQPIS|N|14|4|Alq.PIS|Alíquota de PIS
F0T|24|F0T_ALQCOF|N|14|4|Alq.COF|Alíquota de COF
F0T|25|F0T_VALPIS|N|14|2|Val. PIS|Valor de PIS
F0T|26|F0T_VALCOF|N|14|2|Val. COF|Valor de COF
F0T|27|F0T_EXCPRB|N|14|2|Exclu.CPRB|Exclusão da CPRB
F0T|28|F0T_BCCPRB|N|14|2|Base CPRB|Base de Cálculo CPRB
F0T|29|F0T_AQCPRB|N|5|2|Alq.CPRB|Alíquota de CPRB
F0T|30|F0T_VLCPRB|N|14|2|Val. CPRB|Valor de CPRB
F0T|31|F0T_RECDIF|N|14|2|Rec.Dif|Receita Diferida
F0T|32|F0T_VALREC|N|14|2|Val. Rec.|Valor Recebido
F0T|33|F0T_CODATV|C|8|0|Cod. Ativ.|Código de Atividade
F0T|34|F0T_IFEXCL|N|14|2|Excl BlocoI|Exclusões do Bloco I
F0T|35|F0T_CDBLCI|C|8|0|Cod BlocoI|Código Bloco I
F0T|36|F0T_CNPJ|C|14|0|CNPJ|CNPJ
--- ### F0U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0U|01|F0U_FILIAL|C|6|0|Filial|Filial do Sistema
F0U|02|F0U_STATUS|C|2|0|Status|Status
F0U|03|F0U_NUMNF|C|9|0|Nota Fiscal|Número da Nota Fiscal
F0U|04|F0U_SER|C|3|0|Série|Série
F0U|05|F0U_EMISSA|D|8|0|Data Emissão|Data de Emissão
F0U|06|F0U_LIMITE|D|8|0|Data Limite|Data Limite Suspensão
F0U|07|F0U_ITEM|C|2|0|Item NF|Item da Nota Fiscal
F0U|08|F0U_CLIFOR|C|6|0|Cliente|Código do Cliente
F0U|09|F0U_LOJA|C|2|0|Loja|Loja
F0U|10|F0U_PROD|C|15|0|Produto|Código do Produto
F0U|11|F0U_QUANTD|N|14|2|Qtde Disp.|Quantidade Disponível
F0U|12|F0U_QUANTN|N|14|2|Qtde Não Ret|Quantidade Não Retornada
F0U|13|F0U_QUANTS|N|14|2|Qtde Selec.|Quantidade Selecionada
F0U|14|F0U_CHVNFE|C|44|0|Chave NFe|Chave NFe
F0U|15|F0U_OK|C|1|0|Marcado|Marcado
F0U|16|F0U_EVEENV|C|6|0|Event.Trans.|Evento Transmitido
F0U|17|F0U_EVEESP|C|6|0|Event.Esper.|Evento Esperado
F0U|18|F0U_SEQ|C|2|0|Sequência|Sequência
F0U|19|F0U_IDTSS|C|54|0|Id TSS|Código Id. do TSS
F0U|20|F0U_IDTSST|C|54|0|Id TSS Tran.|Código Id. do TSS Trans.
F0U|21|F0U_MONOK|C|1|0|Monitor OK|Monitor OK
F0U|22|F0U_QUANT1|N|14|2|Qtde. 1ªPro|Quantidade 1ªProrrogação
F0U|23|F0U_QUANT2|N|14|2|Qtde. 2ªPro|Quantidade 2ªProrrogação
F0U|24|F0U_PROT1|C|15|0|1º Protocolo|1º Protocolo autorização
F0U|25|F0U_PROT2|C|15|0|2º Protocolo|2º Protocolo autorização
F0U|26|F0U_CFOP|C|5|0|Cod. Fiscal|Codigo Fiscal da Operacao
--- ### F0V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0V|01|F0V_FILIAL|C|6|0|Filial|Filial do Sistema
F0V|02|F0V_ID|C|36|0|Chave|Chave
F0V|03|F0V_DTOCOR|D|8|0|Ocorrência|Data de ocorrência
F0V|04|F0V_HORA|C|8|0|Hora|Hora Ocorrência
F0V|05|F0V_STATUS|C|2|0|Status|Status
F0V|06|F0V_CHVNFE|C|44|0|Chave NFe|Chave NFe
F0V|07|F0V_ITEM|C|2|0|Item NF|Item da Nota Fiscal
F0V|08|F0V_EVENTO|C|6|0|Evento Sefaz|Código do Evento Sefaz
F0V|09|F0V_SEQ|C|2|0|Sequência|Sequência
F0V|10|F0V_DESCR|C|160|0|Descr Sefaz|Descrição Retorno Sefaz
F0V|11|F0V_IDTSS|C|54|0|Id TSS|Código Id. do TSS
--- ### F0W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0W|01|F0W_FILIAL|C|6|0|Filial|Filial do sistema
F0W|02|F0W_CODIGO|C|6|0|Cod. do Ativ|Código do Ativo
F0W|03|F0W_DTINI|D|8|0|Dt.Inicial|Data Inicial do Período
F0W|04|F0W_DTFIM|D|8|0|Dt.Final|Data Final do Período
F0W|05|F0W_PARCEL|N|3|0|Parcela|Numero da Parcela
F0W|06|F0W_VLPARC|N|14|2|Vl.Parc.ICMS|Valor da Parcela do ICMS
F0W|07|F0W_VLTRIB|N|14|2|Vl. Trib. IC|Valor Saídas Tributadas
F0W|08|F0W_VTOTAL|N|14|2|Vlr. Total|Valor Total Saídas
F0W|09|F0W_INDPAR|N|14|8|Ind.Particip|Índice de Participação
F0W|10|F0W_VLRAPR|N|14|2|Vlr.Out.Cred|Valor Outros Créditos
F0W|11|F0W_PERIOD|C|6|0|Per.Apuração|Período de Apuração
--- ### F0X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F0X|01|F0X_FILIAL|C|6|0|Filial|Filial do Sistema
F0X|02|F0X_NATEVE|C|2|0|Ind.Nat.|Indicador da Natureza
F0X|03|F0X_DTEVEN|D|8|0|Data Evento|Data do Evento
F0X|04|F0X_SUCNPJ|C|14|0|CNPJ|CNPJ da Pessoa Jurídica
F0X|05|F0X_PERIOD|C|6|0|Per.Apuração|Período de Apuração
F0X|06|F0X_CODCRE|C|3|0|Código.Créd|Codigo do Crédito
F0X|07|F0X_VALPIS|N|14|2|Val. PIS|Valor de PIS
F0X|08|F0X_VALCOF|N|14|2|Val. COF|Valor de COF
F0X|09|F0X_PCCISA|N|6|2|Perc.Cred.|Percentual do Crédito
--- ### F10
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F10|01|F10_FILIAL|C|6|0|Filial|Filial do Sistema
F10|02|F10_ANEXO|C|2|0|Anexo|Anexo do Simples Nacional
F10|03|F10_DESCR|C|100|0|Descrição|Descrição do Anexo
F10|04|F10_INIVIG|D|8|0|Data Início|VIgência inicial do anexo
F10|05|F10_FIMVIG|D|8|0|Data Fim|VIgência Final do Anexo
F10|06|F10_RIIRPJ|N|5|2|Rateio IRPJ|Rateio de ISS - IRPJ
F10|07|F10_RICSLL|N|5|2|Rateio CSLL|Rateio de ISS - CSLL
F10|08|F10_RICOF|N|5|2|Rateio COF|Rateio de ISS - COFINS
F10|09|F10_RIPIS|N|5|2|Rateio PIS|Rateio de ISS - PIS
F10|10|F10_RICPP|N|5|2|Rateio CPP|Rateio de ISS - CPP
F10|11|F10_ID|C|36|0|ID|Identificador
--- ### F11
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F11|01|F11_FILIAL|C|6|0|Filial|Filial do Sistema
F11|02|F11_FAIXA|C|2|0|Número Faixa|Número da Faixa
F11|03|F11_RECINI|N|14|2|Receita Ini|Receita Inicial
F11|04|F11_RECFIM|N|14|2|Receita Fim|Receita Final
F11|05|F11_ALIQSN|N|14|4|Aliq. Total|Alíquota Total do Simples
F11|06|F11_VALDED|N|14|2|Dedução|Valor da Dedução
F11|07|F11_IRPJ|N|5|2|IRPJ|Rateio IRPJ
F11|08|F11_CSLL|N|5|2|CSLL|Rateio CSLL
F11|09|F11_COFINS|N|5|2|COFINS|Rateio COFINS
F11|10|F11_PIS|N|5|2|PIS|Rateio PIS
F11|11|F11_CPP|N|5|2|CPP|Rateio CPP
F11|12|F11_ICMS|N|5|2|ICMS|Rateio ICMS
F11|13|F11_IPI|N|5|2|IPI|Rateio do IPI
F11|14|F11_ISS|N|5|2|ISS|Rateio ISS
F11|15|F11_ID|C|36|0|ID da Faixa|Identificador
F11|16|F11_IANEXO|C|36|0|Id Anexo|Id do Anexo
--- ### F12
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F12|01|F12_FILIAL|C|6|0|Filial|Filial do Sistema
F12|02|F12_CODATV|C|2|0|Atividade|Código da Atividade
F12|03|F12_DESCR|C|250|0|Descrição|Descrição
F12|04|F12_TPREC|C|1|0|Tipo Receita|Tipo da Receita
F12|05|F12_TPATIV|C|1|0|Tp Atividade|Tipo de Atividade.
F12|06|F12_ID|C|36|0|ID Atividade|Identificador
--- ### F13
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F13|01|F13_FILIAL|C|6|0|Filial|Filial do Sistema
F13|02|F13_CODATV|C|2|0|Atividade|Código da Atividade
F13|03|F13_CODISS|C|9|0|Código ISS|Código do ISS
F13|04|F13_DISS|C|55|0|Desc Cod ISS|Descrição Codigo ISS
F13|05|F13_FATORR|C|1|0|Fator R|Indica se Incide Fator R
F13|06|F13_CFOP|C|4|0|CFOP|Código de CFOP
F13|07|F13_DCFOP|C|55|0|Desc CFOP|Descrição do CFOP
F13|08|F13_GRUPO|C|5|0|Grp Locação|Grupo de Locação
F13|09|F13_DGRUPO|C|30|0|Desc Grupo|Descrição do Grupo
F13|10|F13_ANEXO|C|2|0|Anexo|Anexo
F13|11|F13_DANEXO|C|100|0|Descr. Anexo|Descrição do Anexo
F13|12|F13_ASUB|C|2|0|Anexo Subst.|Anexo Substituto
F13|13|F13_DASUB|C|100|0|Anexo Sub|Descrição do Anexo Substi
F13|14|F13_TPSERV|C|1|0|Tipo Serviço|TIpo Serviço
F13|15|F13_IDATV|C|36|0|ID ATividade|Id da Atividade
F13|16|F13_TIPO|C|1|0|Tipo Det.|Tipo do Detalhe
F13|17|F13_ID|C|36|0|ID Det Atv|Identificador
F13|18|F13_INIVIG|D|8|0|Data Início|Data inicial da vigência
F13|19|F13_FIMVIG|D|8|0|Data Fim|Data final da vigência
--- ### F14
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F14|01|F14_FILIAL|C|6|0|Filial|Filial do Sistema
F14|02|F14_UF|C|2|0|UF|Unidade Federativa
F14|03|F14_LFED|N|14|2|Limite Fed.|Limite Federal.
F14|04|F14_LEST|N|14|2|Limite Est.|Limite Estadual
F14|05|F14_INIVIG|D|8|0|Data Inicio|Início da Vigência
F14|06|F14_FIMVIG|D|8|0|Data Fim|Fim da Vigência
F14|07|F14_ID|C|36|0|ID|Identificador
--- ### F15
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F15|01|F15_FILIAL|C|6|0|Filial|Filial
F15|02|F15_MES|C|2|0|Mês Ref.|Mês de Referência
F15|03|F15_ANO|C|4|0|Ano Ref.|Ano de Referência
F15|04|F15_TPREC|C|1|0|Tp Receita|Tipo de Receita
F15|05|F15_VALOR|N|14|2|Valor|Valor
F15|06|F15_ID|C|36|0|ID|Identificador
--- ### F16
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F16|01|F16_FILIAL|C|6|0|Filial|Filial do Sistema
F16|02|F16_MES|C|2|0|Mês Ref.|Mês de Referência
F16|03|F16_ANO|C|4|0|Ano Ref.|Ano de Referência
F16|04|F16_ANEXO|C|2|0|Anexo|Anexo
F16|05|F16_IRPJ|N|5|2|Alq IRPJ|Alíquota de IRPJ
F16|06|F16_CSLL|N|5|2|Alq CSLL|Alíquota de CSLL
F16|07|F16_COFINS|N|5|2|Alq COFINS|Alíquota de COFINS
F16|08|F16_PIS|N|5|2|Alq PIS|Alíquota de PIS
F16|09|F16_CPP|N|5|2|Alq CPP|Alíquota de CPP
F16|10|F16_IPI|N|5|2|Alq IPI|Alíquota de IPI
F16|11|F16_ICMS|N|5|2|Alq ICMS|Alíquota de ICMS
F16|12|F16_ISS|N|5|2|Alq ISS|Alíquota de ISS
F16|13|F16_ID|C|36|0|ID|Identificador
F16|14|F16_APROV|C|1|0|Aprovação|Aprovação da Aliquota
--- ### F17
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F17|01|F17_FILIAL|C|6|0|Filial|Filial do Sistema
F17|02|F17_CODATV|C|2|0|Atividade|Código da Atividade
F17|03|F17_SUBATV|C|4|0|SubAtividade|Sub Atividade
F17|04|F17_DESCR|C|250|0|Descrição|Descrição
F17|05|F17_IRPJ|C|1|0|IRPJ|Opções do IRPJ
F17|06|F17_CSLL|C|1|0|CSLL|Opções da CSLL
F17|07|F17_COFINS|C|1|0|COFINS|COFINS
F17|08|F17_PIS|C|1|0|PIS|Opções do PIS
F17|09|F17_CPP|C|1|0|CPP|Opções da CPP
F17|10|F17_ICMS|C|1|0|ICMS|Opções do ICMS
F17|11|F17_IPI|C|1|0|IPI|Opções do IPI
F17|12|F17_ISS|C|1|0|ISS|Opções do ISS
F17|13|F17_IDATV|C|36|0|Id Atividade|Id da Atividade
F17|14|F17_ID|C|36|0|ID|Identificador
--- ### F18
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F18|01|F18_FILIAL|C|6|0|Filial|Filial
F18|02|F18_ID|C|36|0|Id|Id da tabela
F18|03|F18_PER|D|8|0|Período|Período de Apuração
F18|04|F18_IRPJ|N|14|2|IRPJ|Valor do IRPJ
F18|05|F18_CSLL|N|14|2|CSLL|Valor da CSLL
F18|06|F18_COFINS|N|14|2|COFINS|Valor da COFINS
F18|07|F18_PIS|N|14|2|PIS|Valor do PIS
F18|08|F18_CPP|N|14|2|CPP|Valor da CPP
F18|09|F18_IPI|N|14|2|IPI|Valor do IPI
F18|10|F18_ICMS|N|14|2|ICMS|Valor do ICMS
F18|11|F18_ISS|N|14|2|ISS|Valor do ISS
F18|12|F18_LIMITE|C|1|0|Limite|Status do Limite
F18|13|F18_SUBLIM|C|1|0|Sub Limite|Sub Limite do Simples Nac
F18|14|F18_LEXT|C|1|0|Lim Exterior|Limite Exterior
F18|15|F18_SUBEXT|C|1|0|Sub Exterior|Sub Limite Exterior
F18|16|F18_VALREC|N|14|2|Vl Receita|Valor da Receita
F18|17|F18_FATORR|N|4|2|Fator R|Fator R
F18|18|F18_REGIME|C|1|0|Regime|Regime da Apuração
F18|19|F18_IDAPUR|C|36|0|ID Apuração|ID da Apuração da matriz
F18|20|F18_ESTABE|C|20|0|Id. Estab.|ID Estabelecimento
F18|21|F18_VALLIM|N|14|2|Limite|Limite Efetivo
F18|22|F18_VALSUB|N|14|2|Sublimite|Sublimite Efetivo
--- ### F19
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F19|01|F19_FILIAL|C|6|0|Filial|Filial do Sistema
F19|02|F19_ID|C|36|0|ID|Identificador
F19|03|F19_IDAPUR|C|36|0|Id Apuração|Id da Apuração
F19|04|F19_PER|D|8|0|Período|Período de apuração
F19|05|F19_CODATV|C|2|0|Atividade|Código da atividade
F19|06|F19_SUBATV|C|4|0|Subatividade|Código da subatividade
F19|07|F19_DESCR|C|150|0|Descrição|Descrição da subatividade
F19|08|F19_ANEXO|C|2|0|Anexo|Anexo Utilizado
F19|09|F19_IRPJ|N|14|2|IRPJ|IRPJ
F19|10|F19_CSLL|N|14|2|CSLL|CSLL
F19|11|F19_COFINS|N|14|2|COFINS|COFINS
F19|12|F19_PIS|N|14|2|PIS|PIS
F19|13|F19_CPP|N|14|2|CPP|CPP
F19|14|F19_IPI|N|14|2|IPI|IPI
F19|15|F19_ICMS|N|14|2|ICMS|ICMS
F19|16|F19_ISS|N|14|2|ISS|ISS
F19|17|F19_TOTAL|N|14|2|Tot Tributo|Total dos Tributos
F19|18|F19_RECBRU|N|14|2|Rec. Bruta|Receita Bruta
F19|19|F19_TOTDEV|N|14|2|Tot. Devol.|Total de Devoluções
F19|20|F19_TOTREC|N|14|2|Rec. Líquida|Receita Líquida
F19|21|F19_TPREC|C|1|0|Tp Receita|Tipo da Receita
--- ### F1A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1A|01|F1A_FILIAL|C|6|0|Filial|Filial do Sistema
F1A|02|F1A_ID|C|36|0|ID|ID da apuração
F1A|03|F1A_MES|C|2|0|Mês Ref.|Mês de Referência
F1A|04|F1A_ANO|C|4|0|Ano Ref.|Ano de Referência
F1A|05|F1A_REGIME|C|1|0|Regime|Regime de Apuração
F1A|06|F1A_RBT12I|N|14|2|RBT12|RBT12
F1A|07|F1A_RBT12E|N|14|2|RBT12E|RBT12E
F1A|08|F1A_RPAI|N|14|2|RPAI|RPAI
F1A|09|F1A_RPAE|N|14|2|RPAE|RPAE
F1A|10|F1A_FS12|N|14|2|FS12|FS12
F1A|11|F1A_NUMTIT|C|9|0|Num Título|Número do Titulo
F1A|12|F1A_PRETIT|C|3|0|Prefixo Tit|Prefixo do Título
F1A|13|F1A_PARTIT|C|3|0|Parcela Tit|Parcela do Titulo
F1A|14|F1A_TPTIT|C|3|0|Tipo do Tit|Tipo do Título
F1A|15|F1A_FORTIT|C|6|0|Fornecedor|Fornecedor do Titulo
F1A|16|F1A_LOJTIT|C|2|0|Loja|Loja Titulo
F1A|17|F1A_TRIB|N|14|2|Tot Tributos|Total dos tributos
F1A|18|F1A_STATUS|C|1|0|Status|Status da Apuração
F1A|19|F1A_RBAI|N|14|2|RBAI|RBAI
F1A|20|F1A_RBAE|N|14|2|RBAE|RBAE
--- ### F1B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1B|01|F1B_FILIAL|C|6|0|Filial|Filial
F1B|02|F1B_ID|C|36|0|ID|Id da tabela
F1B|03|F1B_IDAPUR|C|36|0|Id Apuração|Id da apuração
F1B|04|F1B_MES|C|2|0|Mês Ref.|Mês de Referência
F1B|05|F1B_ANO|C|4|0|Ano Ref.|Ano de Referência
F1B|06|F1B_SUBATV|C|4|0|Subatividade|Código da Subatividade
F1B|07|F1B_TPPARC|C|1|0|Tipo Parcela|Tipo da Parcela
F1B|08|F1B_VLPARC|N|14|2|Val Parcela|Valor da Parcela
F1B|09|F1B_TRIB|C|1|0|Tributo|Tributo
F1B|10|F1B_RECENQ|N|14|2|Rec. Enq.|Receita Enquadrada
F1B|11|F1B_ANEXO|C|2|0|Anexo|Anexo
F1B|12|F1B_FAIXA|C|2|0|Faixa|Faixa do Anexo
F1B|13|F1B_ALQNOM|N|14|4|Alq Nominal|Alíquota Nominal
F1B|14|F1B_VALDED|N|14|2|Val Dedução|Valor da Dedução
F1B|15|F1B_EFET|N|11|8|Alq Efetiva|Alíquota Efetiva Total
F1B|16|F1B_PARTTB|N|5|2|Part Tributo|Partilha do Tributo
F1B|17|F1B_EFETTB|N|11|8|Alq Efet Trb|Alíquota Efetiva Tributo
F1B|18|F1B_VALOR|N|14|2|Val Tributo|Valor do Tributo
F1B|19|F1B_PREDBC|N|14|2|% Red.BC|Perc.Red.Base do Calculo
F1B|20|F1B_PERRED|N|12|4|% de Red. Bs|Perc. Redução de Bs Calc.
--- ### F1C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1C|01|F1C_FILIAL|C|6|0|Filial|Filial do Sistema
F1C|02|F1C_ID|C|36|0|ID|Id da tabela
F1C|03|F1C_MES|C|2|0|Mês Ref.|Mês de Referência
F1C|04|F1C_ANO|C|4|0|Ano Ref.|Ano de Referência
F1C|05|F1C_VALOR|N|14|2|Valor|Valor do Encargo da Folha
--- ### F1D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1D|01|F1D_FILIAL|C|6|0|Filial|Filial do Sistema
F1D|02|F1D_ID|C|36|0|ID Saldo|ID do saldo
F1D|03|F1D_MES|C|2|0|Mês Ref.|Mês de Referência
F1D|04|F1D_ANO|C|4|0|Ano Ref.|Ano de Referência
F1D|05|F1D_MESUTI|C|2|0|Mês Util.|Mês de Utilização
F1D|06|F1D_ANOUTI|C|4|0|Ano Util.|Ano de Utilização
F1D|07|F1D_CODATV|C|2|0|Atividade|Código da Atividade
F1D|08|F1D_DATV|C|250|0|Desc. Ativ.|Descrição da Atividade
F1D|09|F1D_SUBATV|C|4|0|Subatividade|Código da Subatividade
F1D|10|F1D_DSUBAT|C|250|0|Desc. Subat.|Descrição da Subatividade
F1D|11|F1D_ANEXO|C|2|0|Anexo|Anexo
F1D|12|F1D_DANEXO|C|100|0|Descr. Anexo|Descrição do Anexo
F1D|13|F1D_TPREC|C|1|0|Tp. Receita|Tipo da Receita
F1D|14|F1D_SALDO|N|14|2|Saldo|Saldo
--- ### F1E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1E|01|F1E_FILIAL|C|6|0|Filial|Filial
F1E|02|F1E_ID|C|36|0|ID|ID
F1E|03|F1E_MES|C|2|0|Mês Ref.|Mês de referência
F1E|04|F1E_ANO|C|4|0|Ano Ref.|Ano de referência
F1E|05|F1E_APROV|C|1|0|Aprovação|Aprovação das Alíquotas
--- ### F1F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1F|01|F1F_FILIAL|C|6|0|Filial|Filial do Sistema
F1F|02|F1F_OPERAN|C|2|0|Operando|Operando
F1F|03|F1F_ID|C|36|0|Id Tabela|Identificador da Tabela
--- ### F1G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1G|01|F1G_FILIAL|C|6|0|Filial|Filial do sistema
F1G|02|F1G_CFOP|C|4|0|CFOP|CFOP
F1G|03|F1G_DESCR|C|60|0|Descr. CFOP|Descrição do CFOP
F1G|04|F1G_CST|C|2|0|CST ICMS|CST do ICMS
F1G|05|F1G_DCST|C|60|0|Descr. CST|Descrição do CST
F1G|06|F1G_VLORIG|C|2|0|Vl. Origem|Valor Origem
F1G|07|F1G_ID|C|36|0|ID|Id da tabeal
F1G|08|F1G_IDCAB|C|36|0|Id Cabeçalho|Identificador Cabeçalho
F1G|09|F1G_OPERAN|C|2|0|Operando|Operando
--- ### F1H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1H|01|F1H_FILIAL|C|6|0|Filial|Filial do Sistema
F1H|02|F1H_IDDET|C|36|0|ID Det Atv|Identificador
F1H|03|F1H_ORIGEM|C|1|0|Origem Prod.|Origem do Produto
F1H|04|F1H_DESORI|C|55|0|Descrição|Descrição da Origem
F1H|05|F1H_CFOP|C|4|0|CFOP|Código de CFOP
F1H|06|F1H_IDATV|C|36|0|ID Atividade|ID da Atividade
--- ### F1I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1I|01|F1I_FILIAL|C|6|0|Filial|Filial do Sistema
F1I|02|F1I_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1I|03|F1I_ANOMES|C|6|0|Período Apur|Período da Apuração
F1I|04|F1I_VLREST|N|14|2|Vlr. Restit.|Valor ICMS ST - Restituir
F1I|05|F1I_VLCOMP|N|14|2|Vlr. Complem|Valor ICMS ST - Complemen
F1I|06|F1I_SDREST|N|14|2|Sld. Restit.|Saldo ICMS ST - Restituir
F1I|07|F1I_SDRESS|N|14|2|Sld. Ressar.|Saldo ICMS ST - Ressarcir
F1I|08|F1I_SDCOMP|N|14|2|Sld. Complem|Saldo ICMS ST - Complemen
F1I|09|F1I_SDICOP|N|14|2|Sld. ICMS OP|Saldo ICMS - Op. Próprias
F1I|10|F1I_VLACRE|N|14|2|Vlr.Ap.Cred.|Valor Apurado - Crédito
F1I|11|F1I_VLACOM|N|14|2|Vlr.Ap.Comp.|Valor Apurado - Complemen
F1I|12|F1I_SDRES1|N|14|2|Sld Res Tp 1|Saldo ICMS ST Res Sai Tp1
F1I|13|F1I_SDRES2|N|14|2|Sld Res Tp 2|Saldo ICMS ST Res Sai Tp2
F1I|14|F1I_SDRES3|N|14|2|Sld Res Tp 2|Saldo ICMS ST Res Sai Tp3
F1I|15|F1I_FECRES|N|14|2| Vlr.FECP.Re|Valor FECP - Ressarcir
F1I|16|F1I_FECCMP|N|14|2|Vlr.FECP.Com|Valor FECP - Complemen
F1I|17|F1I_ORIGEM|C|15|0|Origem Apur.|Origem da Apuração
F1I|18|F1I_REVOP1|C|1|0|Cd Reav Tp 1|Cod Reaver Imp Sai Tipo 1
F1I|19|F1I_REVOP2|C|1|0|Cd Reav Tp 2|Cod Reaver Imp Sai Tipo 2
F1I|20|F1I_REVOP3|C|1|0|Cd Reav Tp 3|Cod Reaver Imp Sai Tipo 3
F1I|21|F1I_REVOP4|C|1|0|Cd Reav Tp 4|Cod Reaver Imp Sai Tipo 4
--- ### F1J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1J|01|F1J_FILIAL|C|6|0|Filial|Filial do Sistema
F1J|02|F1J_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1J|03|F1J_ANOMES|C|6|0|Período Apur|Período da Apuração
F1J|04|F1J_PRODUT|C|15|0|Cód. Produto|Código do Produto
F1J|05|F1J_QTDVCF|N|16|5|Qtd Venda CF|Qtde Total de Venda a CF
F1J|06|F1J_VLRVCF|N|14|2|Vlr Venda CF|Valor Total de Venda a CF
F1J|07|F1J_VMUVCF|N|14|3|Vl.Med.Un.CF|Valor Med Unit Venda a CF
F1J|08|F1J_VBSTCF|N|14|2|Vlr.BC.ST.CF|Valor Base Calc ST Ven CF
F1J|09|F1J_VMABST|N|14|2|Vl.Dif.Maior|Valor Dif Mai BCST Vlr CF
F1J|10|F1J_VMEBST|N|14|2|Vl.Dif.Menor|Valor Dif Men BCST Vlr CF
F1J|11|F1J_ALIQEF|N|14|4|Aliq. Efetiv|Alíquota Efetiva do ICMS
F1J|12|F1J_VLREST|N|14|2|Vlr. Restit.|Valor ICMS ST - Restituir
F1J|13|F1J_VLCOMP|N|14|2|Vlr. Complem|Valor ICMS ST - Complemen
F1J|14|F1J_QTDSOE|N|16|5|Qtd Venda OE|Qtde Total de Venda a OE
F1J|15|F1J_VICMOE|N|14|2|Vlr ICMS OE|Valor ICMS Ref Saidas OE
F1J|16|F1J_VISTOE|N|14|2|Vlr ICMST OE|Valor ICMST Ref Saidas OE
F1J|17|F1J_QTDSSN|N|16|5|Qtd Venda SN|Qtde Total de Venda a SN
F1J|18|F1J_VCRDSN|N|14|2|Vlr Cred SN|Valor Total Cred Venda SN
--- ### F1K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1K|01|F1K_FILIAL|C|6|0|Filial|Filial do Sistema
F1K|02|F1K_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1K|03|F1K_ANOMES|C|6|0|Período Apur|Período da Apuração
F1K|04|F1K_PRODUT|C|15|0|Cód. Produto|Código do Produto
F1K|05|F1K_QTDVCF|N|16|5|Qtd Vd CF NF|Qtde Total Venda a CF NF
F1K|06|F1K_UNID|C|2|0|Unid Prod NF|Unidade do Produto na NF
F1K|07|F1K_FATCON|N|9|6|Fator Conver|Fator Convers. p/ Un 0200
F1K|08|F1K_QTVCFC|N|16|5|Qtd Venda CF|Qtde Total de Venda a CF
F1K|09|F1K_VLRVCF|N|14|2|Vlr Venda CF|Valor Total de Venda a CF
--- ### F1L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1L|01|F1L_FILIAL|C|6|0|Filial|Filial do Sistema
F1L|02|F1L_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1L|03|F1L_ANOMES|C|6|0|Período Apur|Período da Apuração
F1L|04|F1L_PRODUT|C|15|0|Cód. Produto|Código do Produto
F1L|05|F1L_QTDENT|N|16|5|Qtd Entradas|Qtde Total de Entradas
F1L|06|F1L_TOTBST|N|14|2|Vlr.Tot.BCST|Valor Total da BC ICMS ST
F1L|07|F1L_VMUBST|N|14|3|V.Med.Un.BST|Valor Med Unit BC ICMS ST
F1L|08|F1L_TOTICM|N|14|2|Vlr.Tot.ICMS|Valor Total do ICMS OP
F1L|09|F1L_VMUICM|N|14|3|V.Med.Un.ICM|Valor Med Unit ICMS OP
F1L|10|F1L_TOTIST|N|14|2|Vlr.Tot.ST|Valor Total do ICMS ST
F1L|11|F1L_VMUIST|N|14|3|Vl.Med.Un.ST|Valor Med Unit ICMS ST
F1L|12|F1L_QTDVLM|N|16|5|Qtd Val Med|Qtde Entradas Valid Media
F1L|13|F1L_CODREG|C|4|0|Cód Registro|Código do Registro
F1L|14|F1L_TOTSUP|N|14|2|Vlr.Tot.Sup|Valor Tot. ICMS Suportado
F1L|15|F1L_VMUSUP|N|14|3|V.Med.Un.Sup|Valor Med Unit ICMS Supor
F1L|16|F1L_VMENUN|N|14|2|V.Men.Uni.En|Valor Menor Unit. Entrada
F1L|17|F1L_PRCMVA|N|9|2|Perc MVA|Percentual MVA
--- ### F1M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1M|01|F1M_FILIAL|C|6|0|Filial|Filial do Sistema
F1M|02|F1M_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1M|03|F1M_ANOMES|C|6|0|Período Apur|Período da Apuração
F1M|04|F1M_PRODUT|C|15|0|Cód. Produto|Código do Produto
F1M|05|F1M_ORDEM|C|9|0|Ordem Movim.|Ordem do Movimento
F1M|06|F1M_DTMOV|D|8|0|Data Movim.|Data do Movimento
F1M|07|F1M_TPMOV|C|1|0|Tipo Movim.|Tipo do Movimento
F1M|08|F1M_INDOP|C|1|0|Ind.Operacao|Indicador da Operação
F1M|09|F1M_NFISCA|C|9|0|Num.Doc.Fisc|Núm. do Documento Fiscal
F1M|10|F1M_SERIE|C|3|0|Ser.Doc.Fisc|Série do Documento Fiscal
F1M|11|F1M_ITEM|C|4|0|Ite.Doc.Fisc|Item do Documento Fiscal
F1M|12|F1M_CFOP|C|5|0|CFOP|Código Fiscal Oper/Prest
F1M|13|F1M_ESPECI|C|5|0|Espécie Doc|Espécie Documento Fiscal
F1M|14|F1M_CHVDOC|C|44|0|Chav.Doc.Fis|Chave do Documento Fiscal
F1M|15|F1M_SERECF|C|21|0|N. Série ECF|Número de Série do ECF
F1M|16|F1M_PARTIC|C|6|0|Participante|Código do Participante
F1M|17|F1M_LOJA|C|2|0|Loja|Loja do Participante
F1M|18|F1M_CNPJ|C|14|0|CNPJ/CPF|CNPJ ou CPF Participante
F1M|19|F1M_QTDMOV|N|16|5|Qtd. Mov. NF|Qtde do Movimento na NF
F1M|20|F1M_UNIDAD|C|2|0|Unid Prod NF|Unidade do Produto na NF
F1M|21|F1M_FATCON|N|9|6|Fator Conver|Fator Convers. p/ Un 0200
F1M|22|F1M_QTDCON|N|16|5|Qtd.Mov.Conv|Qtde do Movimento Convert
F1M|23|F1M_VLRCON|N|14|2|Vlr.Doc.Fisc|Valor do Documento Fiscal
F1M|24|F1M_BASICM|N|14|2|Vlr. BC. ICM|Valor da Bas Calc ICMS OP
F1M|25|F1M_ALQICM|N|14|4|Alq. ICMS OP|Alíquota do ICMS OP
F1M|26|F1M_VLRICM|N|14|2|Vlr. ICMS OP|Valor do ICMS OP
F1M|27|F1M_BASIST|N|14|2|Vlr.BC.ICMST|Valor da Bas Calc ICMS ST
F1M|28|F1M_ALQIST|N|14|4|Alq. ICMS ST|Alíquota do ICMS ST
F1M|29|F1M_VLRIST|N|14|2|Vlr. ICMS ST|Valor do ICMS ST
F1M|30|F1M_BCEFST|N|14|2|Vlr.BC.EF.ST|Valor da Bas Calc Efet ST
F1M|31|F1M_ALQEST|N|14|4|Alq. EFE. ST|Alíquota Efetiva ICMS ST
F1M|32|F1M_CALCST|N|14|3|Vlr. CAL. ST|Valor Calc. Bas X Aliq ST
F1M|33|F1M_CODAJU|C|10|0|Cód. Ajuste|Código Ajuste Débito C197
F1M|34|F1M_CODDA|C|1|0|Cód.Mod.Arre|Código do Mod. de Arrecad
F1M|35|F1M_NMDARE|C|45|0|Num. DARE|Número do DARE
F1M|36|F1M_CODRES|C|1|0|Cód.Resp.Ret|Código Respons. Retenção
F1M|37|F1M_INDSAI|C|2|0|Ind. Saída|Indicador do Tipo Saida
F1M|38|F1M_VCRDSN|N|14|2|Vlr.Cred.SN|Valor de Créd. Venda SN
F1M|39|F1M_NUMPDV|C|10|0|N. Caixa ECF|Num caixa atribuído ECF
F1M|40|F1M_COO|C|9|0|Cont.Ord.Ope|Num. Cont. Ordem Operação
F1M|41|F1M_TAGRET|C|1|0|Ind.Tag.Ret|Ind.Tag.Retido Anteriorm.
F1M|42|F1M_NFCOMP|C|1|0|Ind.Doc.Comp|Ind. Doc. Complementar
F1M|43|F1M_VLUNIT|N|14|2|Vlr.Uni.Item|Valor Unitário do Item
F1M|44|F1M_VLRSUP|N|14|2|Vlr.ICMS.Sup|Valor do ICMS Suportado
F1M|45|F1M_VLREFE|N|14|2|Vlr.ICMS.Efe|Valor do ICMS Efetivo
F1M|46|F1M_VLDESP|N|14|2|Vlr.Despesas|Valor das Despesas
F1M|47|F1M_VLDESC|N|14|2|Vlr.Desconto|Valor dos Descontos
F1M|48|F1M_VLRTOT|N|16|2|Vlr.Tot.Item|Valor Total Item
--- ### F1N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1N|01|F1N_FILIAL|C|6|0|Filial|Filial do Sistema
F1N|02|F1N_ID|C|36|0|ID|Identificador
F1N|03|F1N_LEGEND|C|15|0|Status|Status
F1N|04|F1N_IDAPUR|C|36|0|ID Apur.|ID Apuração
F1N|05|F1N_STATUS|C|1|0|Status|Status
F1N|06|F1N_UF|C|2|0|Estado|Unidade Federativa
F1N|07|F1N_CODMUN|C|5|0|Município|Código do Municipio
F1N|08|F1N_MUN|C|60|0|Município|Descrição do Municipio
F1N|09|F1N_ISSPRO|N|14|2|ISS Proprio|ISS Próprio
F1N|10|F1N_ISSSUB|N|14|2|Iss Sub.|ISS Substituto
F1N|11|F1N_ISSUNI|N|14|2|Iss Uni.|Iss Uniprofissionais
F1N|12|F1N_DEDPRP|N|14|2|Ded. Próprio|Dedução ISS Proprio
F1N|13|F1N_DEDSUB|N|14|2|Ded. Subst.|Deduções ISS Substituto
F1N|14|F1N_DEDUNI|N|14|2|Ded. Uni.|Ded. ISS Uniprofissionais
F1N|15|F1N_RECUNI|N|14|2|Receita Uni.|Receita Uniprofissionais
F1N|16|F1N_QTDUNI|N|14|0|Qtde. Uni.|Qtde. Uniprofissional
F1N|17|F1N_VLFUNI|N|14|2|Vl. Fixo Uni|Vl Mensal Uniprofissional
--- ### F1O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1O|01|F1O_FILIAL|C|6|0|Filial|Filial do Sistema
F1O|02|F1O_ID|C|36|0|ID|Identificador
F1O|03|F1O_IDAPUR|C|36|0|ID Apuração|ID da Apuração
F1O|04|F1O_CODISS|C|9|0|Cód. Serviço|Código do Serviço
F1O|05|F1O_SERV|C|60|0|Serviço|Descrição do Serviço
F1O|06|F1O_VLCONT|N|14|2|Vl. Contábil|Valor Contábil
F1O|07|F1O_MATTER|N|14|2|Mat. Terc.|Material de Terceiros
F1O|08|F1O_MATPRO|N|14|2|Mat. Próprio|Material Próprio
F1O|09|F1O_SUBEMP|N|14|2|Subempr.|Valor das Subempreitadas
F1O|10|F1O_VLISEN|N|14|2|Vlr. Isentas|Operações Isentas
F1O|11|F1O_VLOUTR|N|14|2|Vlr. Outras|Valor Outras
F1O|12|F1O_BSCALC|N|14|2|Base Calc.|Base de Cálculo
F1O|13|F1O_BSRETP|N|14|2|Bs.Ret.Prest|Bs. de Cálculo Ret. Prest
F1O|14|F1O_ISSDES|N|14|2|ISS Destac.|Valor do ISS Destacado
F1O|15|F1O_ISRETP|N|14|2|ISS Ret. Pr.|ISS Retido - Prestações
F1O|16|F1O_ISRETA|N|14|2|ISS Ret. Aq.|ISS Retido - Aquisições
--- ### F1P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1P|01|F1P_FILIAL|C|6|0|Filial|Filial do Sistema
F1P|02|F1P_ID|C|36|0|ID|ID da tabela
F1P|03|F1P_DTINI|D|8|0|Data Inicial|Data Inicial de Apuração
F1P|04|F1P_DTFIM|D|8|0|Data Final|Data Final da apuração
--- ### F1Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1Q|01|F1Q_FILIAL|C|6|0|Filial|Filial do Sistema
F1Q|02|F1Q_ID|C|36|0|ID|Identificador
F1Q|03|F1Q_IDAPUR|C|36|0|ID Apur.|ID da apuração.
F1Q|04|F1Q_TPDED|C|1|0|Tp. Dedução|Tipo de dedução
F1Q|05|F1Q_VLDED|N|14|2|Vl. Dedução|Valor da Dedução
F1Q|06|F1Q_NUMPRO|C|10|0|Num.Processo|Número do Processo
F1Q|07|F1Q_ORIPRO|C|1|0|Orig. Proc.|Origem do Processo
F1Q|08|F1Q_DESPRO|C|100|0|Descr. Proc.|Descrição do Processo
F1Q|09|F1Q_CODOBS|C|60|0|Cod. Obs.|Código da Observação
F1Q|10|F1Q_INDOBR|C|1|0|Ind. Obrig.|Indicador da Obrigação
--- ### F1R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1R|01|F1R_FILIAL|C|6|0|Filial|Filial do Sistema
F1R|02|F1R_ID|C|36|0|ID|Identificador
F1R|03|F1R_IDAPUR|C|36|0|ID Apur|ID Apuração
F1R|04|F1R_LEGEND|C|15|0|Status|Status
F1R|05|F1R_TPIMP|C|2|0|Tp. Imp|Tipo de Imposto
F1R|06|F1R_PREFIX|C|3|0|Prefixo|Prefixo Tìtulo
F1R|07|F1R_NUM|C|9|0|Núm Título|Número do título
F1R|08|F1R_PARC|C|3|0|Parcela|Parcela do Título
F1R|09|F1R_TIPO|C|3|0|Tipo|Tipo do Titulo
F1R|10|F1R_FORN|C|6|0|Fornecedor|Fornecedor
F1R|11|F1R_LOJA|C|2|0|Loja|Loja
F1R|12|F1R_DFORN|C|80|0|Razão Social|Razão Social
F1R|13|F1R_VALOR|N|14|2|Valor|Valor do Titulo
F1R|14|F1R_VENCTO|D|8|0|Vencimento|Vencimento
F1R|15|F1R_NATURE|C|10|0|Natureza|Natureza Financeira
F1R|16|F1R_DNATU|C|30|0|Descr. Nat.|Descrição da Natureza
F1R|17|F1R_STATUS|C|1|0|Status|Status
--- ### F1S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1S|01|F1S_FILIAL|C|6|0|Filial|Filial do Sistema
F1S|02|F1S_ID|C|36|0|ID|Identificador
F1S|03|F1S_ESCOL|C|1|0|Ind. Escolar|Indicador de Escolaridade
F1S|04|F1S_PARSOC|C|1|0|Ind. Par.Soc|Indicador Part Societaria
F1S|05|F1S_CPF|C|11|0|CPF|Num. Insc. CPF
F1S|06|F1S_NOME|C|100|0|Nome|Nome do Profissional
F1S|07|F1S_INIHAB|D|8|0|Dt .Ini.Hab.|Data Inicio Habilitação
F1S|08|F1S_FIMHAB|D|8|0|Dt. Fim.Hab.|Data Fim Habilitação
--- ### F1T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1T|01|F1T_FILIAL|C|6|0|Filial|Filial do Sistema
F1T|02|F1T_UF|C|2|0|UF|Unidade Federativa
F1T|03|F1T_CODMUN|C|5|0|Cod. Mun.|Código Municipio
F1T|04|F1T_FORN|C|6|0|Fornecedor|Fornecedor
F1T|05|F1T_LOJA|C|2|0|Loja|Loja do Fornecedor
F1T|06|F1T_DFORN|C|80|0|Razão Social|Razão Social
F1T|07|F1T_NATURE|C|10|0|Natureza|Natureza Financeira
F1T|08|F1T_DNATUR|C|30|0|Descr. Nat.|Descrição da Natureza
--- ### F1U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1U|01|F1U_FILIAL|C|6|0|Filial|Filial do Sistema
F1U|02|F1U_UF|C|2|0|Estado|Estado
F1U|03|F1U_DUF|C|100|0|Descrição|Descrição do Estado
F1U|04|F1U_CODMUN|C|5|0|Município|Código do município
F1U|05|F1U_DMUNIC|C|100|0|Descrição|Descrição do Municipio
F1U|06|F1U_DTINI|D|8|0|Data Início|Data inicial da vigência
F1U|07|F1U_DTFIM|D|8|0|Data Fim|Data final da vigência
F1U|08|F1U_VALOR|N|14|2|Valor|Valor mensal de ISS
--- ### F1Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F1Z|01|F1Z_FILIAL|C|6|0|Filial|Filial do Sistema
F1Z|02|F1Z_IDAPUR|C|36|0|Id. Apuração|Identificador da Apuração
F1Z|03|F1Z_ANOMES|C|6|0|Período Apur|Período da Apuração
F1Z|04|F1Z_PRODUT|C|15|0|Cód. Produto|Código do Produto
F1Z|05|F1Z_INDSAI|C|2|0|Ind. Saída|Indicador do Tipo Saida
F1Z|06|F1Z_QTDSAI|N|16|5|Qtd Tot Said|Quantidade Total de Saída
F1Z|07|F1Z_VTOSAI|N|14|2|Vlr Tot Said|Valor Total de Saida
F1Z|08|F1Z_VCONFE|N|14|2|Vlr Conf Ent|Valor Confronto Entrada
F1Z|09|F1Z_VMABST|N|14|2|Vl.Dif.Maior|Valor Dif Mai BCST Vlr CF
F1Z|10|F1Z_VMEBST|N|14|2|Vl.Dif.Menor|Valor Dif Men BCST Vlr CF
F1Z|11|F1Z_ALIEFE|N|14|4|Aliq. Efetiv|Alíquota Efetiva do ICMS
F1Z|12|F1Z_ALIFEC|N|14|4|Aliq. FECP|Alíquota FECP
F1Z|13|F1Z_VLRESS|N|14|2|Vlr. Ressarc|Valor ICMS ST - Ressarcir
F1Z|14|F1Z_VLCOMP|N|14|2|Vlr. Complem|Valor ICMS ST - Complemen
F1Z|15|F1Z_VLFRES|N|14|2|Vlr.FECP Res|Valor FECP - Ressarcir
F1Z|16|F1Z_VLFCOM|N|14|2|Vlr.FECP Cmp|Valor FECP - Complementar
--- ### F20
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F20|01|F20_FILIAL|C|6|0|Filial|Filial do Sistema
F20|02|F20_CODIGO|C|6|0|Cód. Perfil|Cód. Perfil Tributário
F20|03|F20_DESC|C|100|0|Descrição|Descrição do Perfil
F20|04|F20_TIPO|C|2|0|Tipo Perfil|Tipo do Perfil Tributário
F20|05|F20_NATOPE|C|4|0|Nat. Oper.|Natureza de Operação
F20|06|F20_STATUS|C|1|0|Status|Status Otimizador Perfil
--- ### F21
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F21|01|F21_FILIAL|C|6|0|Filial|Filial
F21|02|F21_CODIGO|C|6|0|Cód. Perfil|Codigo do Perfil
F21|03|F21_UFORI|C|6|0|UF Origem|UF de Origem
F21|04|F21_DUFORI|C|30|0|Desc. UF Ori|Descrição UF Origem
F21|05|F21_UFDEST|C|2|0|UF Destino|UF de Destino
F21|06|F21_DUFDST|C|30|0|Desc. UF Dst|Descrição da UF Destino
F21|07|F21_TIPOPF|C|2|0|Tipo perfil|Tipo de Perfil
--- ### F22
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F22|01|F22_FILIAL|C|6|0|Filial|Filial do Sistema
F22|02|F22_CODIGO|C|6|0|Cód. Perfil|Código do Perfil
F22|03|F22_TPPART|C|1|0|Tipo|Tipo do Participante
F22|04|F22_CLIFOR|C|6|0|Participante|Codigo Participante
F22|05|F22_LOJA|C|2|0|Loja|Loja do Participante
F22|06|F22_RAZSOC|C|80|0|Razão Social|Razao Social do Participa
F22|07|F22_TIPOPF|C|2|0|Tipo Perfil|Tipo Perdil
F22|08|F22_STATUS|C|1|0|Status|Status Otimizador Perfil
--- ### F23
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F23|01|F23_FILIAL|C|6|0|Filial|Filial do Sistema
F23|02|F23_CODIGO|C|6|0|Cód. Perfil|Código do Perfil
F23|03|F23_CFOP|C|4|0|CFOP|Código Fiscal
F23|04|F23_DCFOP|C|55|0|Descr. CFOP|Descrição do CFOP
F23|05|F23_TIPOPF|C|2|0|Tipo Perfil|Tipo de Perfil
--- ### F24
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F24|01|F24_FILIAL|C|6|0|Filial|Filial doSistema
F24|02|F24_CODIGO|C|6|0|Cód. Perfil|Código do Perfil
F24|03|F24_CDPROD|C|15|0|Cód. Produto|Código do Produto
F24|04|F24_DSPROD|C|70|0|Desc. Prod.|Descrição do Produto
F24|05|F24_TIPOPF|C|2|0|Tipo Perfil|Tipo de perfil
F24|06|F24_CODNCM|C|10|0|NCM|NCM
F24|07|F24_STATUS|C|1|0|Status|Status Otimizador Perfil
--- ### F25
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F25|01|F25_FILIAL|C|6|0|Filial|Filial do Sistema
F25|02|F25_CODIGO|C|6|0|Cód. Perfil|Código do Perfil
F25|03|F25_ORIGEM|C|1|0|Origem Prod.|Origem do Produto
F25|04|F25_DSORIG|C|55|0|Descrição|Descrição do Perfil
F25|05|F25_TIPOPF|C|2|0|Tipo Perfil|Tipo de Perfil
--- ### F26
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F26|01|F26_FILIAL|C|6|0|Filial|Filial do Sistema
F26|02|F26_CODIGO|C|6|0|Código|Código da Regra
F26|03|F26_TPOPER|C|6|0|Tp. Operação|Tipo de Operação
F26|04|F26_DESCRI|C|60|0|Descrição|Descrição
F26|05|F26_TIPOPF|C|2|0|Tipo Perfil|Tipo de Perfil
--- ### F27
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F27|01|F27_FILIAL|C|6|0|Filial|Filial do Sistema
F27|02|F27_CODIGO|C|6|0|Cód. Regra|Cód. Regra Base Cálculo
F27|03|F27_DESC|C|100|0|Descrição|Descrição da Regra
F27|04|F27_VALORI|C|2|0|Valor Origem|Valor de Origem
F27|05|F27_DESCON|C|1|0|Desconto|Ações do Desconto
F27|06|F27_FRETE|C|1|0|Frete|Ações do valor do frete
F27|07|F27_SEGURO|C|1|0|Seguro|Ações do valor de Seguro
F27|08|F27_DESPE|C|1|0|Despesas|Ações das Despesas
F27|09|F27_ICMDES|C|1|0|ICMS Deson.|Ações ICMS Desonerado
F27|10|F27_ICMRET|C|1|0|ICMS Retido|Ações ICMS Retido
F27|11|F27_REDBAS|N|6|3|% Redução|Percentual de redução
F27|12|F27_TPRED|C|1|0|Tipo Redução|Tipo da redução
F27|13|F27_UM|C|2|0|Unidade|Unidade de medida
F27|14|F27_UMDESC|C|40|0|Descrição|Descrição Unidade Medida
F27|15|F27_ALTERA|C|1|0|Alterado|Indicação de alteração
F27|16|F27_DTALT|D|8|0|Dt Alteração|Data de alteração
F27|17|F27_HRALT|C|8|0|Hora Alt.|Hora de alteração.
F27|18|F27_ID|C|36|0|Id|Identificação do Cadastro
F27|19|F27_CHVMD5|C|42|0|MD5|Chave MD5 do Registro
--- ### F28
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F28|01|F28_FILIAL|C|6|0|Filial|Filial do Sistema
F28|02|F28_CODIGO|C|6|0|Cód. Regra|Código da Regra
F28|03|F28_DESC|C|100|0|Descrição|Descrição da Regra
F28|04|F28_VALORI|C|2|0|Valor Origem|Valor de Origem
F28|05|F28_TPALIQ|C|1|0|Tp. Alíquota|Tipo de Alíquota
F28|06|F28_ALIQ|N|14|4|Alíquota|Alíquota
F28|07|F28_URF|C|6|0|Código URF|Código da URF
F28|08|F28_DSURF|C|100|0|Descr. URF|Descrição da URF
F28|09|F28_UFRPER|N|9|5|Perc. URF|Percentual da URF
F28|10|F28_ALTERA|C|1|0|Alterado|Registro alterado
F28|11|F28_DTALT|D|8|0|Dt Alteração|Data da alteração
F28|12|F28_HRALT|C|8|0|Hora Alt.|Horário de Alteração
F28|13|F28_ID|C|36|0|Id Cadastro|Id do Cadastro Alíquota
F28|14|F28_CHVMD5|C|42|0|MD5|Chave MD5 do Registro
F28|15|F28_REDALI|N|7|3|Red. Aliq. %|Perc. Redução Alíquota
--- ### F29
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F29|01|F29_FILIAL|C|6|0|Filial|Filial do Sistema
F29|02|F29_CODIGO|C|6|0|Cód.Unidade|Código da Unidade
F29|03|F29_DESC|C|100|0|Descrição|Descrição da URF
F29|04|F29_ID|C|36|0|Id Cadastro|Id do Cadastro URF
--- ### F2A
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2A|01|F2A_FILIAL|C|6|0|Filial|Filial do Sistema
F2A|02|F2A_URF|C|6|0|Código URF|Código da URF
F2A|03|F2A_MES|C|2|0|Mês|Mês de Referência
F2A|04|F2A_ANO|C|4|0|Ano|Ano de Referência
F2A|05|F2A_VALOR|N|12|4|Valor da URF|Valor da URF no período.
--- ### F2B
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2B|01|F2B_FILIAL|C|6|0|Filial|Filial do Sistema
F2B|02|F2B_ID|C|36|0|Id Cad. Trib|Id cadastro do tributo
F2B|03|F2B_REGRA|C|6|0|Código Regra|Código da Regra Fiscal
F2B|04|F2B_DESC|C|100|0|Descrição|Descrição da Regra
F2B|05|F2B_TRIB|C|6|0|Tributo|Tributo
F2B|06|F2B_DTRIB|C|100|0|Descrição|Descrição do Tributo
F2B|07|F2B_VIGINI|D|8|0|Data Início|Data inicial da vigência
F2B|08|F2B_VIGFIM|D|8|0|Data Final|Data final de vigência
F2B|09|F2B_RBASE|C|6|0|Base Cálculo|Regra de Base de Cálculo
F2B|10|F2B_DBASE|C|100|0|Desc. Base|Descrição Base de Cálculo
F2B|11|F2B_RALIQ|C|6|0|Alíquota|Regra da Alíquota
F2B|12|F2B_DALIQ|C|100|0|Desc. Aliq.|Descrição Regra Aliquota
F2B|13|F2B_PEROD|C|6|0|Perf.Ori/Des|Perfil Origem e Destino
F2B|14|F2B_DOD|C|100|0|Desc Ori/Des|Descrição Origem Destino
F2B|15|F2B_PERFPA|C|6|0|Perf. Part.|Perfil do Participante.
F2B|16|F2B_DPA|C|100|0|Desc. Part.|Descrição Participante
F2B|17|F2B_PERFOP|C|6|0|Perf. Oper.|Perfil da Operação.
F2B|18|F2B_DOP|C|100|0|Desc. Oper.|Descrição da Operação
F2B|19|F2B_PERFPR|C|6|0|Perf. Prod.|Perfil do Produto
F2B|20|F2B_DPR|C|100|0|Desc. Prod.|Descrição Regra Produto
F2B|21|F2B_RFIN|C|6|0|Financeira|Regra Financeira
F2B|22|F2B_DFIN|C|100|0|Desc. Fin.|Desc. da Regra Financeira
F2B|23|F2B_RAPUR|C|6|0|Regra Apur.|Regra de apuração
F2B|24|F2B_DAPUR|C|100|0|Descrição|Descrição da Apuração
F2B|25|F2B_ALTERA|C|1|0|Alterado|Indicação de alteração
F2B|26|F2B_RND|C|1|0|Config Arred|Config. Arredondamento
F2B|27|F2B_DTALT|D|8|0|Dt Alteração|Data de alteração
F2B|28|F2B_HRALT|C|8|0|Hora Alt.|Hora de alteração.
F2B|29|F2B_RBASES|C|6|0|Bas. Second.|Base secundária
F2B|30|F2B_DBASES|C|100|0|Descr. Base|Descrição Base de Cálculo
F2B|31|F2B_TRBMAJ|C|6|0|Trib. Maj,|Tributo Majoração
F2B|32|F2B_DETMAJ|C|100|0|Desc.Trb.Maj|Descr. Tributo Majorado
F2B|33|F2B_DEDDEP|C|6|0|Dedução Dep.|Dedução por Dependente
F2B|34|F2B_DETDEP|C|100|0|Descr. Dep|Descrição Dependentes
F2B|35|F2B_DEDPRO|C|6|0|Ded. Prog.|Dedução Tab. Progressiva
F2B|36|F2B_DETPRO|C|100|0|Desc. Pro|Descricao Ded. Prog
F2B|37|F2B_CODESC|C|6|0|Cod. Escrit.|Código da escrituração
F2B|38|F2B_DESESC|C|100|0|Descrição|Descrição
F2B|39|F2B_MAXMIN|C|1|0|Maior Menor|Maior ou Menor Valor
F2B|40|F2B_RGGUIA|C|6|0|Reg.Ger.Guia|Cod. Regra Geração Guia
F2B|41|F2B_DRGUIA|C|100|0|Desc. R.Guia|Descrição Regra de Guia
F2B|42|F2B_VLRMIN|N|14|2|Vlr. Minimo|Valor minimo do Tributo
F2B|43|F2B_VLRMAX|N|14|2|Vlr. Maximo|Valor Maximo Tributo
F2B|44|F2B_OPRMIN|C|30|0|Oper. Minimo|Operador minimo
F2B|45|F2B_OPRMAX|C|30|0|Oper. Maximo|Operador Maximo
F2B|46|F2B_ORIGEM|C|1|0|Origem Regra|Origem da Regra
F2B|47|F2B_CHVMD5|C|42|0|MD5|Chave MD5 do Registro
F2B|48|F2B_RDBASE|N|3|0|% Base Aux|% Base Aux. ao Comparar
F2B|49|F2B_RCUSTO|C|6|0|Custo|Regra Custo
F2B|50|F2B_STATUS|C|1|0|Status|Status da Regra Trib.
F2B|51|F2B_DCUSTO|C|100|0|Desc. Custo|Descricao da Regra Custo
F2B|52|F2B_TPREGR|C|30|0|Tipo Regra|Tipo da Regra
F2B|53|F2B_TBCONF|C|6|0|Trib Generic|Cod. Trib Generico
F2B|54|F2B_CONREG|C|30|0|Consulta Reg|Consulta Regra
F2B|55|F2B_ACMAX|C|1|0|Acao Vl. Max|Acao ao exceder maximo
F2B|56|F2B_ACMIN|C|1|0|Acao Vl. Mim|Acao ao Nao atingir o min
F2B|57|F2B_MSGCOD|C|6|0|Cód. Grupo|Código do Grupo de Mens.
F2B|58|F2B_MSGDES|C|100|0|Descrição|Descrição grupo de mensag
--- ### F2C
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2C|01|F2C_FILIAL|C|6|0|Filial|Filial do Sistema
F2C|02|F2C_CODIGO|C|6|0|Tributo|Tributo
F2C|03|F2C_DESC|C|100|0|Descrição|Descrição do Tributo
--- ### F2D
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2D|01|F2D_FILIAL|C|6|0|Filial|Filial do Sistema
F2D|02|F2D_ID|C|36|0|ID|Identificador
F2D|03|F2D_IDREL|C|36|0|Id. Tab. Ori|Id relacionamento Tabela
F2D|04|F2D_IDCAD|C|36|0|Id Cadastro|Id Cadastro Tributo
F2D|05|F2D_IDBASE|C|36|0|Id Base Calc|Id regra base de calculo
F2D|06|F2D_IDALIQ|C|36|0|Id Alíquota|Id da regra de alíquota
F2D|07|F2D_TABELA|C|3|0|Tab. Origem|Tabela de Origem
F2D|08|F2D_TRIB|C|6|0|Tributo|Sigla do Tributo
F2D|09|F2D_BASE|N|14|2|Base Cálculo|Base de Cálculo
F2D|10|F2D_BASQTD|N|14|2|Base Qtde.|Base Cálculo QTDE
F2D|11|F2D_ALIQ|N|14|4|Alíquota|Alíquota do Tributo
F2D|12|F2D_VALOR|N|14|2|Val Tributo|Valor do Tributo
F2D|13|F2D_VALURF|N|12|4|Val. URF.|Valor da URF
F2D|14|F2D_DTEXCL|D|8|0|Dt. Exclusão|Data de Exclusão
F2D|15|F2D_RFIN|C|6|0|Regra Fin.|Cód. da Regra Financeira
F2D|16|F2D_IFBAS|C|36|0|Id For. Base|Id da fórmula da base
F2D|17|F2D_IFALQ|C|36|0|Id For Aliq|Id da formula da aliquota
F2D|18|F2D_IFVAL|C|36|0|Id For. Val|Id Fórmula Valor
F2D|19|F2D_MVA|N|8|4|MVA|Marge Valor Agregado
F2D|20|F2D_AUXMVA|N|8|4|Índice MVA|Índice Auxiliar MVA
F2D|21|F2D_PAUTA|N|14|4|Pauta|Valor da Pauta
F2D|22|F2D_MAJORA|N|7|4|Maj.Alíquota|Majoração da alíquota
F2D|23|F2D_AUXMAJ|N|7|4|Indice Maj.|Índice Auxiliar Majoração
F2D|24|F2D_TRBMAJ|C|6|0|Trib. Maj.|Tributo Majorado
F2D|25|F2D_VALMAJ|N|14|2|Val.Majorado|Valor Majorado
F2D|26|F2D_ALQMAJ|N|14|4|Alq.Majorada|Alíquoat Majorada
F2D|27|F2D_DEDDEP|N|14|2|Dedução Dep.|Dedução por dependentes
F2D|28|F2D_IDESCR|C|36|0|ID Escritur.|ID Regra de Escrituracao
F2D|29|F2D_IDTGEN|C|36|0|ID Trib. Gen|ID Trib Generico
F2D|30|F2D_ALIQTR|N|6|2|Aliquota|Indice de Aliquota
F2D|31|F2D_DEDSIM|N|16|4|Ded Simplif|Dedução Simplificada
--- ### F2E
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2E|01|F2E_FILIAL|C|6|0|Filial|Filial do Sistema
F2E|02|F2E_ID|C|36|0|ID|Id do Tributo
F2E|03|F2E_TRIB|C|6|0|Tributo|Tributo
F2E|04|F2E_DESC|C|100|0|Descrição|Descrição do Tributo
F2E|05|F2E_ESFERA|C|1|0|Esfera|Esfera Tributária
F2E|06|F2E_ESPECI|C|1|0|Espécie|Espécie Tributária
F2E|07|F2E_IDTRIB|C|6|0|Id. Tributo|Identificador do Tributo
F2E|08|F2E_DIDTRB|C|100|0|Descrição|Descrição do Tributo
--- ### F2F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2F|01|F2F_FILIAL|C|6|0|Filial|Filial do Sistema
F2F|02|F2F_IDNF|C|36|0|ID da NF|ID da Nota Fiscal
F2F|03|F2F_TABELA|C|3|0|Tab. Origem|Tabela de Origem
F2F|04|F2F_IDFK7|C|32|0|ID Tit. FK7|ID do título - FK7
F2F|05|F2F_IDF2B|C|36|0|ID F2B|ID da regra de cálculo
--- ### F2G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2G|01|F2G_FILIAL|C|6|0|Filial|Filial do Sistema
F2G|02|F2G_ID|C|36|0|ID|ID da regra de apuração
F2G|03|F2G_CODIGO|C|6|0|Código|Código da Regra
F2G|04|F2G_DESCRI|C|100|0|Descrição|Descrição da Regra
F2G|05|F2G_SAIDA|C|1|0|Saida|Ação Operações Saidas
F2G|06|F2G_ENTRAD|C|1|0|Entrada|Ação Operações Entradas
F2G|07|F2G_DEVOL|C|1|0|Devoluções|Ação Operações Devoluções
--- ### F2H
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2H|01|F2H_FILIAL|C|6|0|Filial|Filial do Sistema
F2H|02|F2H_ID|C|36|0|ID|ID da Apuração
F2H|03|F2H_STATUS|C|1|0|Status|Status da Apuração
F2H|04|F2H_TRIB|C|6|0|Tributo|Tributo Apurado
F2H|05|F2H_DESCRI|C|100|0|Descrição|Descrição do Tributo
F2H|06|F2H_DTINI|D|8|0|Data Inicial|Data Inicial da Apuração
F2H|07|F2H_DTFIN|D|8|0|Data FInal|Data Final da Apuração
--- ### F2I
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2I|01|F2I_FILIAL|C|6|0|Filial|Filial do Sistema
F2I|02|F2I_ID|C|36|0|ID|Identificador da Tabela
F2I|03|F2I_IDAPUR|C|36|0|ID Apuração|ID da Apuração
F2I|04|F2I_TPSLD|C|1|0|Tipo Saldo|Tipo de Saldo
F2I|05|F2I_DTORI|D|8|0|Dt. Origem|Data de origem do Saldo
F2I|06|F2I_SLDINI|N|14|2|Saldo Inic.|Saldo Inicial do Período
F2I|07|F2I_SLDUTI|N|14|2|Saldo Uti.|Saldo utiliz. no período
F2I|08|F2I_SLDFIN|N|14|2|Saldo Final|Saldo Final do Período
--- ### F2J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2J|01|F2J_FILIAL|C|6|0|Filial|Filial do Sistema
F2J|02|F2J_ID|C|36|0|ID|ID da tabela
F2J|03|F2J_IDAPUR|C|36|0|ID Apur.|ID da Apuração
F2J|04|F2J_RTRIB|C|36|0|Regra Trib|ID da Regra do Tributo
F2J|05|F2J_RAPUR|C|36|0|ID Regra Apu|ID da Regra de Apuração.
F2J|06|F2J_TIPO|C|1|0|Tipo Resumo|Tipo do Resumo
F2J|07|F2J_VLTRIB|N|14|2|Vl Tributado|Valor Tributado
F2J|08|F2J_VLDEV|N|14|2|Vl. Devol.|Valor de Devoluções
--- ### F2K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2K|01|F2K_FILIAL|C|6|0|Filial|Filial do Sistema
F2K|02|F2K_ID|C|36|0|ID da Tabela|Identificador da Tabela
F2K|03|F2K_IDAPUR|C|36|0|ID Apur|Identificador da Apuração
F2K|04|F2K_OPTRIB|N|14|2|Oper. Trib.|Operações Tributado
F2K|05|F2K_ESTCRD|N|14|2|Est. Crédito|Estorno de Crédito
F2K|06|F2K_TOTDEB|N|14|2|Tot. Débito|Total dos Débitos
F2K|07|F2K_SLDANT|N|14|2|Saldo Ant.|Saldo Credor Per.Anterior
F2K|08|F2K_OPCRED|N|14|2|Op. Credito|Operações com Credito
F2K|09|F2K_ESTDEB|N|14|2|Est. Crédito|Estorno de Crédito
F2K|10|F2K_TOTCRD|N|14|2|Tot. Crédito|Valor Total do Crédito
F2K|11|F2K_SLDDEV|N|14|2|Sld Devedor|Saldo Devedor
F2K|12|F2K_SLDATU|N|14|2|Sld Credor|Saldo Credor
F2K|13|F2K_SLDUTI|N|14|2|Saldo Util.|Saldo Credor Utilizado
F2K|14|F2K_AJUCRD|N|14|2|Ajustes Crd.|Ajustes de Crédito
F2K|15|F2K_AJUDEB|N|14|2|Ajustes Déb.|Ajustes de Débito
--- ### F2L
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2L|01|F2L_FILIAL|C|6|0|Filial|Filial do Sistema
F2L|02|F2L_ID|C|36|0|ID|ID
F2L|03|F2L_IDAPUR|C|36|0|ID Apuração|ID da Apuração
F2L|04|F2L_CHVFK7|C|32|0|Chave FK7|Chave da Tabela FK7
F2L|05|F2L_RFIN|C|6|0|Regra Fin.|Regra Financeira
--- ### F2M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2M|01|F2M_FILIAL|C|6|0|Filial|Filial do Sistema
F2M|02|F2M_ID|C|36|0|ID|Identificador
F2M|03|F2M_IDRAPU|C|36|0|ID. Res. Apu|Id do Resumo da Apuração
F2M|04|F2M_TPAJUS|C|1|0|Tp. Ajuste|Tipo de Ajuste
F2M|05|F2M_DESCRI|C|100|0|Descrição|Descrição do Ajuste
F2M|06|F2M_VALOR|N|14|2|Valor|Valor do Ajuste
--- ### F2N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2N|01|F2N_FILIAL|C|6|0|Filial|Filial do Sistema
F2N|02|F2N_TRIB|C|6|0|Tributo|Código do Tributo
F2N|03|F2N_DTRIB|C|100|0|Desc.Tributo|Descrição do Tributo
F2N|04|F2N_RTIT|C|6|0|Regra Título|Código da Regra de Título
F2N|05|F2N_DTIT|C|100|0|Desc. Título|Descrição regra de Título
F2N|06|F2N_RGGUIA|C|6|0|Reg.Ger.Guia|Cod. Regra Geração Guia
F2N|07|F2N_DRGUIA|C|100|0|Desc. R.Guia|Descrição Regra de Guia
--- ### F2P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2P|01|F2P_FILIAL|C|6|0|Filial|Filial do Sistema
F2P|02|F2P_UF|C|2|0|UF|Unidade da Federacao
F2P|03|F2P_CREDAC|C|1|0|Or.Cred.Acum|Orig.Cred. Acumulado ICMS
F2P|04|F2P_CODAJU|C|8|0|Cod.Aj.Apur.|Codigo do Ajuste Apuracao
F2P|05|F2P_CODCRE|C|8|0|Cod.Aj.Cred.|Codigo do Ajuste Crédito
--- ### F2Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2Q|01|F2Q_FILIAL|C|6|0|Filial|Filial de controle
F2Q|02|F2Q_PRODUT|C|15|0|Produto|Codigo do produto
F2Q|03|F2Q_CODANV|C|13|0|Cód. ANVISA|Código de produto ANVISA
F2Q|04|F2Q_PMXANV|N|14|2|$ Máx ANVISA|Preço máx/tabelado ANVISA
F2Q|05|F2Q_REFANV|C|1|0|Ref. Base ST|Referência base ST
F2Q|06|F2Q_TIPANV|C|1|0|Tp. Medicam.|Tipo de medicamento
F2Q|07|F2Q_RESVSN|C|1|0|Ress.Vend.SN|Ress. ICMS-ST Venda p/ SN
F2Q|08|F2Q_TPSERV|C|2|0|Tipo serviço|Classif tipo de serviço
F2Q|09|F2Q_MOTISE|C|254|0|Mot. Isenção|Mot. da Isenção da ANVISA
F2Q|10|F2Q_NATREN|C|5|0|Nat. Rend.|Natureza de Rendimento
F2Q|11|F2Q_PRDINC|C|1|0|Prod Incent |Produto Incentivado - AM
--- ### F2R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2R|01|F2R_FILIAL|C|6|0|Filial|Filial do Sistema
F2R|02|F2R_ANOMES|C|6|0|Ano Mes|Ano e Mês da apuração
F2R|03|F2R_LIVRO|C|1|0|Nr. Livro|Numero do Livro
F2R|04|F2R_CREDAC|C|1|0|Or.Cred.Acum|Orig.Cred. Acumulado ICMS
F2R|05|F2R_DESCRI|C|60|0|Desc Op Cred|Descricao op credito acum
F2R|06|F2R_CODAJU|C|8|0|Cod.Aj.Apur.|Codigo do Ajuste Apuracao
F2R|07|F2R_DESAJU|C|254|0|Desc Ajuste|Descricao do Ajuste
F2R|08|F2R_CODCRE|C|8|0|Cod.Aj.Cred.|Codigo do Ajuste Crédito
F2R|09|F2R_DESCRE|C|254|0|Desc Aj Cred|Descricao Ajuste Crédito
F2R|10|F2R_SUBITE|C|10|0|SubItem Apur|SubItem da apuracao ICMS
F2R|11|F2R_INDICE|N|7|5|Indice|Indice Saidas incentivada
F2R|12|F2R_VALOR|N|16|2|Vlr Crd Mes|Valor Credito gerado mês
--- ### F2S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2S|01|F2S_FILIAL|C|6|0|Filial|Filial do sistema
F2S|02|F2S_TRIBUT|C|1|0|Tributo|Tributo do detalhe
F2S|03|F2S_TPAJUS|C|1|0|Tp Ajuste|Tipo de Ajuste
F2S|04|F2S_CODAJU|C|2|0|Cód. Ajuste|Código do Ajuste
F2S|05|F2S_VLRAJU|N|14|2|Vlr. Ajuste|Valor do Ajuste
F2S|06|F2S_DESCRI|C|20|0|Descrição|Descrição do Ajuste
F2S|07|F2S_PER|D|8|0|Período|Período de Referência
--- ### F2T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2T|01|F2T_FILIAL|C|6|0|Filial|Filial do Sistema
F2T|02|F2T_ANOMES|C|6|0|Ano/Mês|Ano/Mês da Apuração
F2T|03|F2T_IDAPUR|C|36|0|Id Apuração|Id da Apuração
F2T|04|F2T_ENQLEG|C|2|0|Enquad.Legal|Enquadramento Legal
F2T|05|F2T_VRESSA|N|14|2|Vlr Ressarc.|Valor Ressarcimento
F2T|06|F2T_VCOMPL|N|14|2|Vlr Complem.|Valor do Complemento
F2T|07|F2T_VCREDI|N|14|2|Vlr Cred ICM|Vlr Cred ICMS Próprio
--- ### F2U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2U|01|F2U_FILIAL|C|6|0|Filial|Filial do Sistema
F2U|02|F2U_IDAPUR|C|36|0|Id Apuração|Identificador da Apuração
F2U|03|F2U_ANOMES|C|6|0|Ano/Mês|Ano/Mês da Apurado
F2U|04|F2U_ENQLEG|C|2|0|Enq.Legal|Enquadramento Legal
F2U|05|F2U_VUISUP|N|14|2|V.Un ICM Sup|Valor Unit ICMS Suportado
F2U|06|F2U_VTISUP|N|14|2|V.To ICM Sup|Vlr total ICMS Suportado
F2U|07|F2U_ICMEFS|N|14|2|ICM Efet Sai|ICMS Efetivo Saída
F2U|08|F2U_ICMEFE|N|14|2|ICM Efet Ent|ICMS Efetivo Entrada
F2U|09|F2U_NFISCA|C|9|0|Nota Fiscal|Nº da Nota Fiscal
F2U|10|F2U_SERIE|C|3|0|Série|Série da Nota Fiscal
F2U|11|F2U_ITEM|C|4|0|Item da Nota|Código do Item da Nota
F2U|12|F2U_PARTIC|C|6|0|Participante|Código do Participante
F2U|13|F2U_LOJA|C|2|0|Loja|Loja do Participante
F2U|14|F2U_CFOP|C|5|0|CFOP|Código Fiscal Oper/Prest
F2U|15|F2U_PRODUT|C|15|0|Produto|Código do Produto
F2U|16|F2U_DTMOV|D|8|0|Dt Movimento|Data do movimento
F2U|17|F2U_QTDMOV|N|16|2|Qtde|Quantidade movimento
F2U|18|F2U_TPMOV|C|1|0|Tipo Mov|Tipo do Movimento
F2U|19|F2U_QTDSLD|N|16|2|Qtde Saldo|Quantidade Saldo
F2U|20|F2U_VUNSLD|N|14|2|Vlr Un Saldo|Valor Unit Saldo
F2U|21|F2U_VTOSLD|N|14|2|Vl Tot Saldo|Valor Total Saldo
F2U|22|F2U_VRESSA|N|14|2|Vlr Ressarc|Valor Ressarcimento
F2U|23|F2U_VCOMPL|N|14|2|Vl Complento|Valor Complemento
F2U|24|F2U_VCREDI|N|14|2|Vl Cred ICMS|Valor Cred.ICMS
F2U|25|F2U_TPREG|C|1|0|Tp Registro|Tipo de Registro
F2U|26|F2U_ORDEM|C|9|0|Ordem|Ordem do Registros
F2U|27|F2U_SERECF|C|21|0|Série ECF|N.Série ECF
F2U|28|F2U_CHVDOC|C|44|0|Chave NFe|Chave doc. eletrônico
F2U|29|F2U_ALIQIC|N|14|4|Aliq.ICMS|Aliquota de ICMS
F2U|30|F2U_TIPO|C|1|0|Tipo da Nota|Tipo da Nota
F2U|31|F2U_ESPECI|C|5|0|Espécie NF|Espécie da NF
--- ### F2V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2V|01|F2V_FILIAL|C|6|0|Filial|Filial do Sistema
F2V|02|F2V_ANOMES|C|6|0|Ano/Mês|Ano/Mês do Processamento
F2V|03|F2V_PRODUT|C|15|0|Produto|Código do Produto
F2V|04|F2V_DESPRO|C|70|0|Desc.Produto|Descrição do Produto
F2V|05|F2V_QTDSLD|N|16|2|Qtde Inicial|Qtde Saldo Inicial
F2V|06|F2V_VUNSLD|N|14|2|Vlr Unit.Ini|Vlr Unit Saldo Inicial
F2V|07|F2V_VTOSLD|N|14|2|Vlr Tot. Ini|Vlr total saldo inicial
F2V|08|F2V_QTDFIM|N|16|2|Qtde Final|Qtde saldo final
F2V|09|F2V_VUNFIM|N|14|2|Vlr Un Final|Valor Unit Final
F2V|10|F2V_VTOFIM|N|14|2|Vlr To Final|Valor Total Final
F2V|11|F2V_TPREG|C|1|0|Tp Registro|Tipo de Registro
F2V|12|F2V_ICMSEN|N|14|2|Vl.Un.ICM.En|Valor Unit ICMS Prop Entr
--- ### F2W
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2W|01|F2W_FILIAL|C|6|0|Filial|Filial do Sistema
F2W|02|F2W_IDTAB|C|36|0|Id Tabela|Identificador único
F2W|03|F2W_CFOP|C|5|0|CFOP|Cod.Fiscal Operação
F2W|04|F2W_DECFOP|C|60|0|Descrição|Descrição do CFOP
F2W|05|F2W_FATGER|C|1|0|Fato Gerador|Indicador de Fato Gerador
--- ### F2X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2X|01|F2X_FILIAL|C|6|0|Filial|Filial do Sistema
F2X|02|F2X_IDAPUR|C|36|0|Id Apuração|Id da Apuração
F2X|03|F2X_ANOMES|C|6|0|Ano/Mês|Ano/Mês Apuração
F2X|04|F2X_VRESSA|N|14|2|Vlr Ressarc.|Valor Ressarcimento
F2X|05|F2X_VCOMPL|N|14|2|Vlr Complem.|Valor do Complemento
F2X|06|F2X_VCREDI|N|14|2|Vlr Cred ICM|Vlr Cred ICMS Próprio
--- ### F2Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2Y|01|F2Y_FILIAL|C|6|0|Filial|Filial do Sistema
F2Y|02|F2Y_CODAJU|C|8|0|Código|Código
F2Y|03|F2Y_DESCR|C|254|0|Desc.Complem|Desc.Completa
F2Y|04|F2Y_VERSAO|C|5|0|Versão|Versão
F2Y|05|F2Y_DTINI|D|8|0|Data Início|Data Início
F2Y|06|F2Y_DTFIM|D|8|0|Data Fim|Data Fim
--- ### F2Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F2Z|01|F2Z_FILIAL|C|6|0|Filial|Filial do Sistema
F2Z|02|F2Z_CHV|C|23|0|Chave EFD|Chave EFD
F2Z|03|F2Z_ID|C|36|0|ID da tabela|Identificação da tabela
F2Z|04|F2Z_TRIB|C|1|0|Tributo|Tributo
F2Z|05|F2Z_INDAJU|C|1|0|Ind. Ajuste|Indicador do Ajuste
F2Z|06|F2Z_VALAJU|N|14|2|Val. Ajuste|Valor do Ajuste
F2Z|07|F2Z_CODAJU|C|2|0|Cód. Ajuste|Codigo do Ajuste
F2Z|08|F2Z_CODCON|C|2|0|Cod. Contrib|Codigo da Contribuição
F2Z|09|F2Z_DCODCO|C|60|0|Desc. CodCon|Desc. Código Contribuição
F2Z|10|F2Z_NUM|C|50|0|Num.Doc/Proc|Número documento/processo
F2Z|11|F2Z_DESCR|C|200|0|Descrição|Descrição do ajuste
F2Z|12|F2Z_DTREF|D|8|0|Data Refer.|Data de Referência
F2Z|13|F2Z_CONTA|C|20|0|Cta Contabil|Conta Contabil
F2Z|14|F2Z_CNPJ|C|14|0|CNPJ|CNPJ do estabelecimento
F2Z|15|F2Z_COMPL|C|200|0|Inf. Compl.|Informação Complementar
F2Z|16|F2Z_ORIG|C|1|0|Origem|Origem do Ajuste
F2Z|17|F2Z_CONSOL|C|1|0|Consolidado|Consolid. visao Empresa
F2Z|18|F2Z_PERAPU|D|8|0|Per.Apuração|Período de Apuração
--- ### F3F
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3F|01|F3F_FILIAL|C|6|0|Filial|Filial do Sistema
F3F|02|F3F_PER|C|6|0|Período|Periodo (MM/AAAA)
F3F|03|F3F_CST|C|2|0|CST|Codigo do CST PIS/COF
F3F|04|F3F_BCPIS|N|16|2|Vl Base PIS|Valor Base PIS
F3F|05|F3F_ALQPIS|N|14|4|Aliquota PIS|Aliquota do PIS
F3F|06|F3F_VLRPIS|N|16|2|Valor PIS|Valor do PIS
F3F|07|F3F_BCCOF|N|16|2|Vl Base COF|Valor Base COFINS
F3F|08|F3F_ALQCOF|N|14|4|Aliq COFINS|Aliquota do COFINS
F3F|09|F3F_VLRCOF|N|16|2|Valor COFINS|Valor do COFINS
F3F|10|F3F_NATREC|C|4|0|Tab.Nat.Rec|Tab. Nat. Receita
F3F|11|F3F_CNATRE|C|3|0|Cod.Nat.Rec|Codigo Natureza Receita
F3F|12|F3F_GRPNAT|C|2|0|Grp.Nat.Rec|Grupo Natureza Receita
F3F|13|F3F_DTFIMN|D|8|0|Dt.Fim.N.R|Data Fim Nat.Receita
F3F|14|F3F_IDCMP|C|1|0|ID Campo|ID Campo Valor I100
F3F|15|F3F_DEBCRE|C|1|0|Tipo|Tipo de Lancamento
F3F|16|F3F_BLOCOI|C|8|0|Clas.Bloco I|Classificacao Bloco I
F3F|17|F3F_CONTA|C|20|0|Cod.Conta|Codigo da Conta
F3F|18|F3F_INFO|C|200|0|Inf Compl|Inf. Complementares
F3F|19|F3F_VALOR|N|16|2|Valor Reg|Valor do Registro
F3F|20|F3F_VDEGER|N|16|2|Vl Ded Ger|Valor Deducao Geral
F3F|21|F3F_VDEESP|N|16|2|Vl Ded Esp|Valor Deducao Especif
F3F|22|F3F_IDFIL|C|36|0|ID.Reg.Filho|Identificador Reg.Filho
F3F|23|F3F_CTB|C|1|0|Integ. CTB|Integração com CTB
F3F|24|F3F_TPREG|C|1|0|Tipo Reg|Tipo de Registro
F3F|25|F3F_IDPAI|C|36|0|ID Reg Pai|ID Registro Pai
F3F|26|F3F_ID|C|36|0|Cod. Ident|Cod. Identificador
--- ### F3G
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3G|01|F3G_FILIAL|C|6|0|Filial|Filial do Sistema
F3G|02|F3G_TRIBUT|C|1|0|Tributo|Tributo
F3G|03|F3G_REGIME|C|1|0|Regime|Regime
F3G|04|F3G_CODREC|C|6|0|Cod. Receita|Código da Receita
F3G|05|F3G_DESC|C|50|0|Desc. Rec.|Descrição da Receita
F3G|06|F3G_CST|C|2|0|CST|Código do CST Pis/Cof
F3G|07|F3G_CODCON|C|2|0|Cod. Contr.|Código Contrib.
F3G|08|F3G_NATREC|C|4|0|Tab.Nat.Rec|Tab. Nat. Receita
F3G|09|F3G_CNATRE|C|3|0|Cod.Nat.Rec|Código Natureza Receita
F3G|10|F3G_ID|C|36|0|Chave|Chave
--- ### F3J
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3J|01|F3J_FILIAL|C|6|0|Filial|Filial do Sistema
F3J|02|F3J_PER|D|8|0|Per.Apuração|Período de Apuração
F3J|03|F3J_CODREC|C|6|0|Cod. Receita|Código da Receita
F3J|04|F3J_VLTRIB|N|14|2|Vl.TRibuto|Valor do Tributo
F3J|05|F3J_TOTPAG|N|14|2|Vl.Tot.Pagar|Valor Total a Pagar
F3J|06|F3J_TRIBUT|C|1|0|Tributo|Tributo
F3J|07|F3J_CONSOL|C|1|0|Consolidado|Consolid. visão Empresa
F3J|08|F3J_CODPAG|N|14|2|Tot.Pagar|Valor Pagar Cod. Receita
F3J|09|F3J_PERCEN|N|6|2|Perc.Tot.Deb|Percentual Total débito
--- ### F3K
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3K|01|F3K_FILIAL|C|6|0|Filial|Filial do Sistema
F3K|02|F3K_PROD|C|15|0|Produto|Produto
F3K|03|F3K_CFOP|C|5|0|CFOP|CFOP
F3K|04|F3K_CODAJU|C|8|0|Cod.Val.Decl|Cod.Val.Decl
F3K|05|F3K_VALOR|C|1|0|Valor|Valor
F3K|06|F3K_CST|C|2|0|CST|CST
F3K|07|F3K_CODREF|C|7|0|Cod. Reflexo| Código Reflexo
F3K|08|F3K_GRCLAN|C|3|0|Grp.Clientes|Grupo de Clientes
F3K|09|F3K_GRPLAN|C|6|0|Grp.Produto|Grupo de Produtos
F3K|10|F3K_GRFLAN|C|3|0|Grp.Fornec|Grupo de Fornecedores
F3K|11|F3K_IFCOMP|C|6|0|Obs.Lanc.Fis|Obs. Lancamento Fiscal
F3K|12|F3K_CODLAN|C|10|0|Cod Lanc|Código Lançamento
--- ### F3M
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3M|01|F3M_FILIAL|C|6|0|Filial|Filial do Sistema
F3M|02|F3M_CSTICM|C|2|0|CST ICMS|CST do ICMS
F3M|03|F3M_DESCST|C|60|0|Descrição|Desc. CST ICMS
F3M|04|F3M_IDF2W|C|36|0|Id Tabela|Identificador da Tab F2W
--- ### F3N
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3N|01|F3N_FILIAL|C|6|0|Filial|Filial do Sistema
F3N|02|F3N_MES|C|2|0|Mês|Mês do Recibo
F3N|03|F3N_ANO|C|4|0|Ano|Ano do Recibo
F3N|04|F3N_RECIBO|C|41|0|Num Recibo|Número do Recibo
--- ### F3O
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3O|01|F3O_FILIAL|C|6|0|Filial|Filial do Sistema
F3O|02|F3O_PER|D|8|0|Per. Apur|Período de Apuração
F3O|03|F3O_CONSOL|C|1|0|Consolidado|COnsolidado Matriz
F3O|04|F3O_CST|C|2|0|CST|CST de Pis e Cofins
F3O|05|F3O_RECBA|N|14|2|Rec.Bloco A|Receita Bloco A
F3O|06|F3O_RECBC|N|14|2|Rec.Bloco C|Receita Bloco C
F3O|07|F3O_RECBD|N|14|2|Rec.Bloco D|Receita do Bloco D
F3O|08|F3O_RECBF|N|14|2|Rec.Bloco F|Receita Bloco F
F3O|09|F3O_RECBCD|N|14|2|Rec.Bloco CD|Receita Blocos C e D
F3O|10|F3O_TOTREC|N|14|2|Tot. Receita|Total Receita A, C, D e F
F3O|11|F3O_PERCD|N|12|8|Perc. C e D|Percentual C e D.
F3O|12|F3O_REGIME|C|1|0|Regime|Regime de Apuração
F3O|13|F3O_METODO|C|1|0|Método|Método de Rateio
--- ### F3P
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3P|01|F3P_FILIAL|C|6|0|Filial|Filial do Sistema
F3P|02|F3P_PER|D|8|0|Per. Apur.|Período da Apuração
F3P|03|F3P_CONSOL|C|1|0|Consolidado|Consolidado Empresa.
F3P|04|F3P_CODAJU|C|2|0|Cod. Ajuste|Código do Ajuste
F3P|05|F3P_CNPJ|C|14|0|CNPJ|CNPJ do Estabelecimento
F3P|06|F3P_TOTAJU|N|14|2|Tot. Ajuste|Total do Ajuste.
F3P|07|F3P_CST01|N|14|2|Aju. CST 01|Ajuste CST 01
F3P|08|F3P_CST02|N|14|2|Aju. CST 02|Ajuste CST 02
F3P|09|F3P_CST03|N|14|2|Aju. CST 03|Ajuste do CST 03.
F3P|10|F3P_CST04|N|14|2|Aju. CST 04|Ajuste CST 04
F3P|11|F3P_CST05|N|14|2|Aju. CST 05|Ajuste CST 05
F3P|12|F3P_CST06|N|14|2|Aju. CST 06|Ajuste CST 06
F3P|13|F3P_CST07|N|14|2|Aju. CST 07|Ajuste CST 07
F3P|14|F3P_CST08|N|14|2|Aju. CST 08|Ajuste CST 08
F3P|15|F3P_CST09|N|14|2|Aju. CST 09|Ajuste CST 09
F3P|16|F3P_CST49|N|14|2|Aju. CST 49|Ajuste CST 49
F3P|17|F3P_CST99|N|14|2|Aju. CST 99|Ajuste CST 99
F3P|18|F3P_INDAP|C|2|0|Ind. Aprop.|Indicador de Apropriação
F3P|19|F3P_RECIBO|C|80|0|Num. Recibo|Númedo do Recibo
F3P|20|F3P_INFCOM|C|100|0|Inf. Compl.|Informação Complementar
F3P|21|F3P_VALICM|N|14|2|Val. ICMS|ICMS a Recolher
F3P|22|F3P_REGIME|C|1|0|Regime|Regime de Apuração
F3P|23|F3P_AJMANU|C|1|0|Aj. Manual?|Ajuste Manual?
--- ### F3Q
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3Q|01|F3Q_FILIAL|C|6|0|Filial|Filial do Sistema
F3Q|02|F3Q_PERIOD|C|6|0|Mês/Ano|Mês/Ano Periodo Apuração
F3Q|03|F3Q_LIVRO|C|1|0|Livro|Livro
F3Q|04|F3Q_ICMSEF|N|14|2|ICMS Efetivo|ICMS Efetivo
F3Q|05|F3Q_ICMSPR|N|14|2|ICMS Presumi|ICMS Presumido
F3Q|06|F3Q_ICMSDE|N|14|2|ICMS Ded|ICMS Deduzido
F3Q|07|F3Q_TOTCOM|N|14|2|Tot. Complem|Total ICMS Complementar
F3Q|08|F3Q_TOTRES|N|14|2|Tot.Restitui|Total ICMS a Restituir
--- ### F3R
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3R|01|F3R_FILIAL|C|6|0|Filial|Filial do Sistema
F3R|02|F3R_PERIOD|C|6|0|Mês/Ano|Mês/Ano Apuração
F3R|03|F3R_ICMSEF|N|14|2|ICMS Efetivo|ICMS Efetivo
F3R|04|F3R_ICMSPR|N|14|2|ICMS Presumi|ICMS Presumido
F3R|05|F3R_ICMSDE|N|14|2|ICMS Deduzir|ICMS Deduções
F3R|06|F3R_NFISCA|C|9|0|Nota Fiscal|Nº da Nota Fiscal
F3R|07|F3R_SERIE|C|3|0|Série|Série da Nota Fiscal
F3R|08|F3R_ITEM|C|4|0|Item da Nota|Código do Item da Nota
F3R|09|F3R_PARTIC|C|6|0|Participante|Código do Participante
F3R|10|F3R_LOJA|C|2|0|Loja|Loja do Participante
F3R|11|F3R_PRODUT|C|15|0|Produto|Código do Produto
F3R|12|F3R_VLRRES|N|14|2|Vlr Ressarc|Valor Ressarcimento
F3R|13|F3R_VLRCOM|N|14|2|Vlr Complem|Valor Complemento
F3R|14|F3R_LOTE|C|10|0|Lote|Lote
F3R|15|F3R_TIPO|C|1|0|Tipo Mov|Tipo do Movimento
F3R|16|F3R_QTDMOV|N|16|2|Qtde|Quantidade movimento
F3R|17|F3R_DTMOV|D|8|0|Dt Movimento|Data do movimento
F3R|18|F3R_LIVRO|C|1|0|Nr. Livro|Numero do Livro
F3R|19|F3R_DOCENT|C|9|0|Numero NF|Numero da NF Entrada
F3R|20|F3R_FORNE|C|6|0|Fornec.|Fornecedor
F3R|21|F3R_LOJENT|C|2|0|Codigo Loja|Codigo da loja do Forn.
F3R|22|F3R_SERENT|C|3|0|Serie NF Ent|Serie da NF de Entrada
F3R|23|F3R_QTDENT|N|11|3|Qtd. de Item|Quantidade de Item de Ent
F3R|24|F3R_CHVENT|C|44|0|Chave NF-e|Chave NF-e
F3R|25|F3R_ITENFE|C|4|0|Item NF Ent.|Item da Nota Fiscal Entra
F3R|26|F3R_ID|C|36|0|Chave|Chave
F3R|27|F3R_MODENT|C|5|0|Espec NF Ent|Especie Nota Entrada
F3R|28|F3R_DTENT|D|8|0|Dt NF Entrad|Data Nota Entrada
--- ### F3S
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3S|01|F3S_FILIAL|C|6|0|Filial|Filial do Sistema
F3S|02|F3S_PERIOD|C|6|0|Mês/Ano|Mês/Ano Apuração
F3S|03|F3S_REGRA|C|2|0|Regra Calc.|Regra de Cálculo
F3S|04|F3S_LIVRO|C|1|0|Livro|Livro
F3S|05|F3S_ICMSEF|N|14|2|ICMS Efetivo|ICMS Efetivo
F3S|06|F3S_ICMSPR|N|14|2|ICMS Presumi|ICMS Presumido
F3S|07|F3S_ICMSDE|N|14|2|ICMS Ded|ICMS Deduzido
F3S|08|F3S_QTDPAR|N|2|0|Qtd. Parcela|Quantidade Parcela
F3S|09|F3S_UTLPAR|N|2|0|Parc. Utiliz|Parcela Utilizada
F3S|10|F3S_VLRTOT|N|14|2|Valor Total|Valor Total
F3S|11|F3S_VLRPAR|N|14|2|Vlr. Parcela|Valor Parcela
--- ### F3T
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3T|01|F3T_FILIAL|C|6|0|Filial|Filial do Sistema
F3T|02|F3T_CODIGO|C|8|0|Cod. Ajuste|Codigo de Ajuste
F3T|03|F3T_REGRA|C|2|0|Regra Calc.|Regra de Cálculo
F3T|04|F3T_DESCRI|C|100|0|Descri Regra|Descrição da Regra
F3T|05|F3T_PARCEL|N|2|0|Qtd. Parcela|Quantidade de Parcelas
--- ### F3U
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3U|01|F3U_FILIAL|C|6|0|Filial|Filial do Sistema
F3U|02|F3U_CODCRE|C|3|0|Cod. Crédito|Código do Crédito
F3U|03|F3U_DCC|C|56|0|Descrição|Desc. Código de Crédito.
F3U|04|F3U_CODBCC|C|2|0|Código BCC|Cod. Base Cálculo Crédito
F3U|05|F3U_DCBCC|C|56|0|Descrição|Descrição Cod BCC
--- ### F3V
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3V|01|F3V_FILIAL|C|6|0|Filial|Filial do Sistema
F3V|02|F3V_PERAPU|C|6|0|Per.Apuração|Período de Apuração
F3V|03|F3V_PEREST|N|6|2|Perc.Estorno|Percentual de Estorno
F3V|04|F3V_DESCHP|C|100|0|Descrição|Descrição
F3V|05|F3V_PERDET|N|6|2|Perc. Det.|Percentual Detalhamento
F3V|06|F3V_ORIG|C|1|0|Origem|Origem dos percentuais
F3V|07|F3V_CODAJU|C|2|0|Cod. Ajuste|Código do Ajuste
F3V|08|F3V_CODCTA|C|20|0|Ct. Contábil|Conta Contabil
--- ### F3X
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3X|01|F3X_FILIAL|C|6|0|Filial|Filial do Sistema
F3X|02|F3X_PERIOD|C|6|0|Mês/Ano|Mês/Ano Ref.
F3X|03|F3X_VLRCOM|N|16|2|Valor Compl.|Valor do Complemento
F3X|04|F3X_VLRRES|N|16|2|Valor Restit|Valor da Restituição
--- ### F3Y
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3Y|01|F3Y_FILIAL|C|6|0|Filial|Filial do Sistema
F3Y|02|F3Y_PERIOD|C|6|0|Mês/Ano Ref.|Mês/Ano Referência
F3Y|03|F3Y_PRODUT|C|15|0|Cod.Produto|Código do Produto
F3Y|04|F3Y_TIPOMO|C|1|0|Tipo Movimen|Tipo Movimento
F3Y|05|F3Y_SERIE|C|3|0|Serie Doc|Serie do documento fiscal
F3Y|06|F3Y_NFISCA|C|9|0|Nota Fiscal|Num Nota Fiscal
F3Y|07|F3Y_CODPAR|C|6|0|Participante|Código do Participante
F3Y|08|F3Y_LOJPAR|C|2|0|Loja Partic|Loja do Participante
F3Y|09|F3Y_DTMOVT|D|8|0|Data Movimen|Data do Movimento
F3Y|10|F3Y_QUANT|N|16|2|Quantidade|Quantidade
F3Y|11|F3Y_VLRUNI|N|16|2|Vlr Unitário|Valor Unitário
F3Y|12|F3Y_VLRTOT|N|16|2|Vlr Total|Valor Total]
F3Y|13|F3Y_VLRPRE|N|16|2|Bs ST Presum|Base ST Presumida
F3Y|14|F3Y_VLRCOM|N|16|2|Vlr Compleme|Valor do Complemento
F3Y|15|F3Y_VLRRES|N|16|2|Vlr Restitui|Valor da Restituição
F3Y|16|F3Y_ITEM|C|4|0|Item|Item da Nota Fiscal
F3Y|17|F3Y_ALIQIC|N|14|4|Aliq.ICMS|Aliquota de ICMS
--- ### F3Z
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
F3Z|01|F3Z_FILIAL|C|6|0|Filial|Filial
F3Z|02|F3Z_PER|D|8|0|Per de Apur|Período de apuração
F3Z|03|F3Z_CODATI|C|8|0|Cód. Ativ.|Código de Atividade
F3Z|04|F3Z_VLATI|N|14|2|Rec Ativ|Receita ref cód. ativ.
F3Z|05|F3Z_BASE|N|14|2|Base Calc.|Base de calculo
F3Z|06|F3Z_ALIQ|N|14|4|Aliquota|Aliquota da CPRBxCNO
F3Z|07|F3Z_VLCPRB|N|14|2|Val. CPRB|Valor da CPRB
F3Z|08|F3Z_CONTA|C|20|0|Conta CTB|Conta Contábil
F3Z|09|F3Z_SALDO|C|1|0|Saldo Exclu|Saldo de exclusão
F3Z|10|F3Z_FILAPU|C|6|0|Filial apur|Filial da apuração
F3Z|11|F3Z_CNO|C|14|0|Número CNO|Número de CNO
F3Z|12|F3Z_EXCLU|N|14|2|Vl Exclusão|Exclusão da receita
F3Z|13|F3Z_VLBRUT|N|16|2|Vlr Brut|Valor bruto do período
--- ### FH0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FH0|01|FH0_FILIAL|C|6|0|Filial|Filial do sistema
FH0|02|FH0_PROJET|C|22|0|Projeto|Projeto
FH0|03|FH0_CODPRO|C|15|0|Cod. Produto|Cod. Produto
FH0|04|FH0_DESPRO|C|70|0|Desc Produto|Desc Produto
FH0|05|FH0_POSCON|N|9|0|Pos Contador|Pos Contador
FH0|06|FH0_CODFAM|C|6|0|Cod Familia|Cod Familia
FH0|07|FH0_NOMFAM|C|40|0|Nome Familia|Nome Familia
FH0|08|FH0_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo
FH0|09|FH0_DESMOD|C|20|0|Desc Modelo|Desc Modelo
FH0|10|FH0_TIPCOB|C|1|0|Tip Cobranca|Tip Cobranca
--- ### FH1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FH1|01|FH1_FILIAL|C|6|0|Filial|Filialdo Sistema]
FH1|02|FH1_ORDEM|C|6|0|Ordem|Ordem de Servico
FH1|03|FH1_PLANO|C|6|0|Plano|Plano de Manutencao
FH1|04|FH1_TAREFA|C|6|0|Tarefa|Cod Tarefa
FH1|05|FH1_TIPORE|C|1|0|Tipo Insumo|Tipo Insumo
FH1|06|FH1_CODIGO|C|15|0|Codigo|Codigo do Detalhe
FH1|07|FH1_SEQREL|C|3|0|Sequencia|Sequencia do Retorno
FH1|08|FH1_SEQTAR|C|3|0|Seq. Tarefa|Sequencia da Tarefa
FH1|09|FH1_CODFOR|C|6|0|Cod Fornec|Codigo Fornecedor
FH1|10|FH1_LOJFOR|C|2|0|Loja Fornec|Loja fornecedor
FH1|11|FH1_STAPRO|C|1|0|Status Aprov|Status Aprovacao
FH1|12|FH1_CODAPR|C|6|0|Cod Aprov|Codigo Aprovador
FH1|13|FH1_NOMAPR|C|40|0|Nome Aprov|Nome Aprovador
FH1|14|FH1_OBSREJ|M|10|0|Obs Rejeicao|OBS Rejeição
FH1|15|FH1_DTAPRO|D|8|0|Dt Aprovação|Data Aprovação
FH1|16|FH1_HRAPRO|C|5|0|Hr AProvação|Hora Aprovação
FH1|17|FH1_DTENC|D|8|0|Data Encerra|Data Encerramento
FH1|18|FH1_HRENC|C|5|0|Hora Encerra|Hora Encerramento
FH1|19|FH1_PEDCOM|C|6|0|Ped Compra|Pedido de Compra
FH1|20|FH1_QUANTI|N|12|2|Quantidade|Quantidade
FH1|21|FH1_VLRUNI|N|12|2|Vlr Unitario|Valor Unitário
FH1|22|FH1_VLRTOT|N|12|2|Valor Total|Valor Total
FH1|23|FH1_VLRAUN|N|12|2|Vl Unit Apro|Valor unitario aprovado
FH1|24|FH1_VLRATO|N|12|2|Vl Tot Apro|Valor total aprovado
FH1|25|FH1_CODFIN|C|6|0|Cod Fin Ger|Cod Finalidade Gerencial
FH1|26|FH1_DESFIN|C|50|0|Desc Fin Ger|Desc Finalidade Gerencial
FH1|27|FH1_COBRA|C|1|0|Cobra|Cobra OS do Cliente
FH1|28|FH1_CUSEX|N|12|2|Custo Extra|Custo Extra
--- ### FP0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP0|01|FP0_FILIAL|C|6|0|Filial|Filial do Sistema
FP0|02|FP0_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FP0|03|FP0_REVISA|C|2|0|Revisao|Revisao
FP0|04|FP0_TIPO|C|1|0|Tipo|Tipo
FP0|05|FP0_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FP0|06|FP0_RECEIT|C|1|0|Receita|Receita
FP0|07|FP0_STATUS|C|1|0|Status|Status
FP0|08|FP0_MODPRO|C|1|0|Mod.Proposta|Mod.Proposta
FP0|09|FP0_DATINC|D|8|0|Dt.Inclusao|Dt.Inclusao
FP0|10|FP0_HORINC|C|4|0|Hr.Inclusao|Hr.Inclusao
FP0|11|FP0_CLI|C|6|0|Cliente|Cliente
FP0|12|FP0_LOJA|C|2|0|Loja Cliente|Loja Cliente
FP0|13|FP0_CLINOM|C|80|0|Nome Cliente|Nome Cliente
FP0|14|FP0_CLICGC|C|14|0|CNPJ|CNPJ
FP0|15|FP0_CLIINS|C|19|0|Ins.Estadual|Ins.Estadual
FP0|16|FP0_PROSPE|C|6|0|Prospect|Prospect
FP0|17|FP0_LOJAP|C|2|0|Loja Prospec|Loja Prospec
FP0|18|FP0_PRONOM|C|40|0|Nome Prospec|Nome Prospec
FP0|19|FP0_CLIEND|C|40|0|Endereco|Endereco
FP0|20|FP0_CLIMUN|C|20|0|Municipio|Municipio
FP0|21|FP0_CLIBAI|C|20|0|Bairro|Bairro
FP0|22|FP0_CLIEST|C|2|0|UF|UF
FP0|23|FP0_CLICEP|C|8|0|Cep|Cep
FP0|24|FP0_ENDOBR|C|40|0|End. Obra|End. Obra
FP0|25|FP0_CLICON|C|6|0|Contato|Contato
FP0|26|FP0_NOMECO|C|50|0|Nome Contato|Nome Contato
FP0|27|FP0_CLIDEP|C|20|0|Departamento|Departamento
FP0|28|FP0_CLIEMA|C|80|0|E-Mail|E-Mail
FP0|29|FP0_CLIDDD|C|3|0|DDD|DDD
FP0|30|FP0_CLITEL|C|16|0|Telefone|Telefone
FP0|31|FP0_CLIFAX|C|16|0|Fax|Fax
FP0|32|FP0_VENDED|C|6|0|Gestor|Gestor
FP0|33|FP0_NOMVEN|C|30|0|Nome Gestor|Nome Gestor
FP0|34|FP0_OBS|M|10|0|Observacao|Observacao
FP0|35|FP0_OBSDOC|M|10|0|Obs s/ Doc|Obs Sobre Documentacao
FP0|36|FP0_OBSPRO|M|10|0|Obs.Proposta|Obs.Proposta
FP0|37|FP0_DTPARA|D|8|0|Dt.Entrega|Dt.Entrega
FP0|38|FP0_HRPARA|C|4|0|Hr.Entrega|Hr.Entrega
FP0|39|FP0_DTENVI|D|8|0|Dt.Envio|Dt.Envio
FP0|40|FP0_TPENVI|C|1|0|Tipo Envio|Tipo Envio
FP0|41|FP0_DTRETO|D|8|0|Dt.Retorno|Dt.Retorno
FP0|42|FP0_PRVALI|N|3|0|Prz.Validade|Prz.Validade
FP0|43|FP0_DTVALI|D|8|0|Dt.Validade|Dt.Validade
FP0|44|FP0_DATAS|D|8|0|Dt.Ger.AS|Dt.Ger.AS
FP0|45|FP0_ESCOPO|M|10|0|ObsTransport|ObsTransport
FP0|46|FP0_RETAGE|C|1|0|Ret.Agenda|Ret.Agenda
FP0|47|FP0_USUINC|C|15|0|Usuario|Usuario
FP0|48|FP0_PREVFT|N|3|0|Dias Prev FT|Dias Previsto p/ Faturar
FP0|49|FP0_OBSCOB|M|10|0|Obs.Cobranca|Obs.Cobranca
FP0|50|FP0_DTLIBE|D|8|0|Dt.Licitacao|Dt.Licitacao
FP0|51|FP0_HRLIBE|C|4|0|Hr.Licitatac|Hr.Licitatac
FP0|52|FP0_CONVIT|C|20|0|Nro.Convite|Nro.Convite
FP0|53|FP0_TIPOPR|C|1|0|Projeto/Lic.|Projeto/Lic.
FP0|54|FP0_CODCON|C|6|0|Cod Concorr.|Cod Concorr.
FP0|55|FP0_NOMCON|C|40|0|Nome Concorr|Nome Concorr
FP0|56|FP0_VALCON|N|12|2|Vr.Concorr.|Vr.Concorr.
FP0|57|FP0_VALLOC|N|12|2|Vr.Locacao|Vr.Locacao
FP0|58|FP0_CODPRJ|C|6|0|Cod.Projeto|Cod.Projeto
FP0|59|FP0_NOMPRJ|C|40|0|Nome Projeto|Nome Projeto
FP0|60|FP0_CONDPG|C|3|0|Cond.Pagto|Cond.Pagto
FP0|61|FP0_HORAPR|C|5|0|Hora Aprovac|Hora Aprovac
FP0|62|FP0_DTAPRO|D|8|0|Data Aprovac|Data Aprovacao
FP0|63|FP0_USUAPR|C|15|0|Usuario Aprv|Usuario Aprovacao
FP0|64|FP0_CLIENT|L|1|0|Cliente S/N?|Ja e Cliente?
FP0|65|FP0_COD|C|5|0|Codigo|Codigo
FP0|66|FP0_CODANT|C|8|0|Cod Anterior|Cod Anterior
FP0|67|FP0_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP0|68|FP0_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP0|69|FP0_DTIMPT|D|8|0|Dt. Import|Data. Importacao
FP0|70|FP0_DTUPDT|D|8|0|Dt. Update|Data Update
FP0|71|FP0_ORCAM|C|6|0|Orcamento|Orcamento
FP0|72|FP0_TPRAT|C|1|0|Tipo de RAT|Tipo de RAT
FP0|73|FP0_PRJSP|C|1|0|Proj/Fil SP|Projeto/Filial SP
FP0|74|FP0_NUMPED|C|6|0|Numero PV|Numero PV
FP0|75|FP0_FILPED|C|6|0|Filial PV|Filial PV
FP0|76|FP0_PMEDIC|C|6|0|Per. Medicao|Periodo de Medicao
FP0|77|FP0_TIPFAT|C|1|0|Tipo Faturam|Tipo Faturamento
FP0|78|FP0_POSSIB|C|3|0|% Possibilid|% Possibilid
FP0|79|FP0_UNINEG|C|6|0|Uni. de Neg.|Unidade de negocio
FP0|80|FP0_UNIDES|C|20|0|Desc.Unidade|Descricao da unidade
FP0|81|FP0_ORICLI|C|2|0|Ori. Cliente|Origem do cliente
FP0|82|FP0_DESORI|C|30|0|Desc. Origem|Descricao da origem
FP0|83|FP0_COMPLE|C|50|0|Complemento|Complemento Endereco
FP0|84|FP0_VALPRO|N|14|2|Val. Projeto|Valor do projeto
FP0|85|FP0_WFID|C|15|0|Id WF|Id do processo WF
FP0|86|FP0_PERSEG|N|7|3|% Seguro|Percentual de seguro
FP0|87|FP0_VRSEGU|N|14|2|Vr.Seguro|Valor do seguro
FP0|88|FP0_TOTSEG|N|14|2|Tot. Seguro|Total do seguro
FP0|89|FP0_RENOVA|C|1|0|Renovacao?|Contrato renovado?
FP0|90|FP0_VRTEC|N|6|2|Vlr. Tecnico|Valor do tecnico/manut.
FP0|91|FP0_VRDESL|N|6|2|Vlr. Desloc.|Valor do deslocamento
FP0|92|FP0_CONARE|C|1|0|Cond. Area|Condicoes de area
FP0|93|FP0_LOCTRA|C|1|0|Loc. de Trab|Local de trabalho
FP0|94|FP0_HRSDES|C|3|0|Hr. S/ Desc.|Hora sem desconto.
FP0|95|FP0_MINPFT|C|1|0|Tipo Fatura|Tipo Fatura
FP0|96|FP0_MOEDA|N|2|0|Moeda|Moeda do PV
FP0|97|FP0_NIVEL|C|1|0|Nivel|Nivel de aprovacao
FP0|98|FP0_PDESCO|N|6|2|% Desconto|% Desconto
FP0|99|FP0_PMARGE|N|6|2|% Margem|% Margem
FP0|9A|FP0_AGLUNF|C|1|0|Aglutina NF|Aglutina NF
FP0|9B|FP0_PRODL|C|15|0|Prod.Locação|Produto Locação
FP0|9C|FP0_PRODM|C|15|0|Prod.M.Obra|Produto mão obra
FP0|9D|FP0_PRODOZ|C|15|0|Prod.Outros|Produto Outros
FP0|9E|FP0_TPFRAN|C|1|0|Tp.Cons.Fran|Tipo consumo de franquia
FP0|9F|FP0_PROV|C|1|0|Provisório|Título provisório
--- ### FP1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP1|01|FP1_FILIAL|C|6|0|Filial|Filial
FP1|02|FP1_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FP1|03|FP1_OBRA|C|3|0|Obra|Obra
FP1|04|FP1_TPMES|C|1|0|Tipo de Mes|Tipo de Mes
FP1|05|FP1_CLIORI|C|6|0|Cliente|Cliente Orig
FP1|06|FP1_LOJORI|C|2|0|Loja|Loja Origem
FP1|07|FP1_NOMORI|C|80|0|Nome da Obra|Nome da Obra
FP1|08|FP1_TEMVIS|C|1|0|Tem Vistoria|Tem Vistoria
FP1|09|FP1_DTVIS|D|8|0|Przo.Vistori|Dt.Vistoria
FP1|10|FP1_HRVIS|C|4|0|Hr.Vistoria|Hr.Vistoria
FP1|11|FP1_TIPRAT|C|1|0|Tipo RAT|Tipo RAT
FP1|12|FP1_NOMRES|C|30|0|Nome do Resp|Nome do responsavel
FP1|13|FP1_RESPON|C|30|0|E-mail Resp.|E-mail do resp. da R.A.T
FP1|14|FP1_EMARAT|C|1|0|E-Mail RAT|E-Mail RAT
FP1|15|FP1_CGCORI|C|14|0|CNPJ|CNPJ Origem
FP1|16|FP1_INSORI|C|15|0|Ins.Estadual|Ins.Est.Orig
FP1|17|FP1_CEIORI|C|15|0|CEI|CEI
FP1|18|FP1_ENDORI|C|40|0|Endereco|End.Origem
FP1|19|FP1_BAIORI|C|25|0|Bairro|Bairro Orig.
FP1|20|FP1_MUNORI|C|25|0|Cidade|Cidade Orig.
FP1|21|FP1_ESTORI|C|2|0|UF|UF Origem
FP1|22|FP1_CEPORI|C|8|0|Cep|Cep Origem
FP1|23|FP1_CONORI|C|40|0|Contato|Contato Orig
FP1|24|FP1_RG|C|12|0|RG|RG do contato
FP1|25|FP1_DEPORI|C|20|0|Depto|Depto.Origem
FP1|26|FP1_EMAORI|C|60|0|EMail|EMail Origem
FP1|27|FP1_DDDORI|C|3|0|DDD|DDD Origem
FP1|28|FP1_TELORI|C|15|0|Telefone|Tel.Origem
FP1|29|FP1_RAMAL|C|5|0|Ramal|Ramal do contato
FP1|30|FP1_CELULA|C|20|0|Celular|Celular do contato
FP1|31|FP1_FAXORI|C|15|0|Fax|Fax Origem
FP1|32|FP1_CLIDES|C|6|0|Cliente Fat.|Cliente faturamento
FP1|33|FP1_LOJDES|C|2|0|Loja fat|Loja faturamento
FP1|34|FP1_NOMDES|C|80|0|Local fat|Local faturamento
FP1|35|FP1_ENDDES|C|40|0|End.fat.|End.faturamento
FP1|36|FP1_BAIDES|C|25|0|Bairro fat|Bairro faturamento
FP1|37|FP1_MUNDES|C|25|0|Cidade fat|Cidade faturamento
FP1|38|FP1_ESTDES|C|2|0|UF fat|UF faturamento
FP1|39|FP1_CEPDES|C|8|0|Cep fat|Cep faturamento
FP1|40|FP1_CONDES|C|40|0|Contato fat|Contato faturamento
FP1|41|FP1_RGDEST|C|15|0|RG Cont fat|RG Contato faturamento
FP1|42|FP1_DEPDES|C|20|0|Depto.Dest.|Depto.Dest.
FP1|43|FP1_EMADES|C|60|0|EMail fat|EMail faturamento
FP1|44|FP1_DDDDES|C|3|0|DDD fat|DDD faturamento
FP1|45|FP1_TELDES|C|15|0|Tel.fat|Tel.faturamento
FP1|46|FP1_FAXDES|C|15|0|Fax.fat|Fax.faturamento
FP1|47|FP1_ESCOPO|M|10|0|Desc.Servico|Desc.Servico
FP1|48|FP1_OBSVIS|M|10|0|Observacao|Obs.Vistoria
FP1|49|FP1_OBSFAT|M|10|0|Obs.Faturam.|Obs.Faturam.
FP1|50|FP1_ORIGEM|C|6|0|Origem|Origem
FP1|51|FP1_DESTIN|C|6|0|Destino|Destino
FP1|52|FP1_ROTA|C|3|0|Rota|Rota
FP1|53|FP1_CGCDES|C|14|0|CNPJ.fat|CNPJ.faturamento
FP1|54|FP1_INSDES|C|15|0|Ins.Est.fat|Ins.Est.faturamento
FP1|55|FP1_DATINC|D|8|0|Dt.Inclusao|Dt.Inclusao
FP1|56|FP1_HORINC|C|6|0|Hr.Inclusao|Hr.Inclusao
FP1|57|FP1_USUINC|C|15|0|Data Envio|Data Envio
FP1|58|FP1_NOMOBR|C|40|0|Nome da Obra|Nome da Obra
FP1|59|FP1_TIPOCA|C|1|0|Tipo Calculo|Tipo Calculo
FP1|60|FP1_DIASV|N|4|0|Dias Vazio|Dias Vazio
FP1|61|FP1_DIASC|N|4|0|Dias Carreg.|Dias Carreg.
FP1|62|FP1_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FP1|63|FP1_DTINI|D|8|0|Dt.Inicio|Dt.Inicio
FP1|64|FP1_DTFIM|D|8|0|Dt.Final|Dt.Final
FP1|65|FP1_PREDIA|C|3|0|Prev.Dias|Prev.Dias
FP1|66|FP1_PREHOR|C|4|0|Prev.Horas|Prev.Horas
FP1|67|FP1_OBSVIA|M|10|0|Obs.Viagem|Obs.Viagem
FP1|68|FP1_VRESTA|N|12|2|Vlr. Estadia|Vlr. Estadia
FP1|69|FP1_VRDIA|N|12|2|Valor Dia|Valor Dia
FP1|70|FP1_QTEIXO|N|3|0|Qtde Eixos|Qtde Eixos
FP1|71|FP1_PTB|C|10|0|P.T.B|P.T.B
FP1|72|FP1_EHTERC|C|1|0|Terceiro|Terceiro
FP1|73|FP1_HRINI|C|8|0|Hora Inicio|Hora Inicial
FP1|74|FP1_HRFIM|C|8|0|Hora Fim|Hora Fim
FP1|75|FP1_SEQTRA|C|3|0|Seq Transp.|Seq Transp.
FP1|76|FP1_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP1|77|FP1_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP1|78|FP1_COMPLE|C|50|0|complemento|complemento endereco
FP1|79|FP1_COMORI|C|100|0|Comp. Origem|Complemento Origem
FP1|80|FP1_COMDES|C|100|0|Comp. Destin|Complemento Destino
FP1|81|FP1_TROCEQ|C|1|0|Troca equip.|Troca equipamento
--- ### FP2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP2|01|FP2_FILIAL|C|6|0|Filial|Filial do Sistema
FP2|02|FP2_CODIGO|C|6|0|Codigo|Codigo
FP2|03|FP2_DESCRI|C|60|0|Descricao|Descricao
FP2|04|FP2_PAIS|C|30|0|Pais|Pais
FP2|05|FP2_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP2|06|FP2_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP2|07|FP2_CDPAIS|C|3|0|Cod. Pais|Cod. Pais
FP2|08|FP2_ESTADO|C|2|0|UF|UF
FP2|09|FP2_CODMUN|C|5|0|Cod. Munic|Cod. Munic
FP2|10|FP2_PORTO|C|1|0|Portuario ?|Portuario ?
--- ### FP3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP3|01|FP3_FILIAL|C|6|0|Filial|Filial do Sistema
FP3|02|FP3_ORIGEM|C|6|0|Origem|Origem
FP3|03|FP3_MUNORI|C|25|0|Cid.Origem|Cid.Origem
FP3|04|FP3_ESTORI|C|2|0|UF Origem|UF Origem
FP3|05|FP3_DESTIN|C|6|0|Destino|Destino
FP3|06|FP3_MUNDES|C|25|0|Cid.Destino|Cid.Destino
FP3|07|FP3_ROTA|C|3|0|Rota|Rota
FP3|08|FP3_NOMROT|C|30|0|Nome da Rota|Nome da Rota
FP3|09|FP3_ESTDES|C|2|0|UF Destino|UF Destino
FP3|10|FP3_ETAPA|C|3|0|Etapa|Etapa
FP3|11|FP3_DE|C|6|0|De|De
FP3|12|FP3_MUNDE|C|25|0|Cidade De|Cidade De
FP3|13|FP3_ATE|C|6|0|Ate|Ate
FP3|14|FP3_ESTDE|C|2|0|UF De|UF De
FP3|15|FP3_MUNATE|C|25|0|Cidade Ate|Cidade Ate
FP3|16|FP3_ESTATE|C|2|0|UF Ate|UF Ate
FP3|17|FP3_DISTAN|N|5|0|Distancia KM|Distancia KM
FP3|18|FP3_RODOVI|C|20|0|Rodovia|Rodovia
FP3|19|FP3_QTDPED|N|3|0|Qtd.Pedagios|Qtd.Pedagios
FP3|20|FP3_VREIXO|N|12|2|Vr.Por Eixo|Vr.Por Eixo
FP3|21|FP3_TIPORO|C|1|0|Tipo Rodovia|Tipo Rodovia
FP3|22|FP3_TIPOPI|C|1|0|Tipo Pista|Tipo Pista
FP3|23|FP3_TRANSU|C|1|0|Trans.Urbano|Trans.Urbano
FP3|24|FP3_OBS|M|10|0|Obs.|Obs.
FP3|25|FP3_TEMALE|C|1|0|Alemoa?|Alemoa?
FP3|26|FP3_TEMBLO|C|1|0|Bloq.Serra?|Bloq.Serra?
FP3|27|FP3_FATTAP|N|1|0|Fator TAP|Fator TAP
FP3|28|FP3_TEMTUR|C|1|0|Calcula TUR?|Calcula TUR?
FP3|29|FP3_IDA|C|1|0|Ida/Volta?|Ida/Volta?
FP3|30|FP3_TEMPO|N|8|2|Tempo (Hs)|Tempo (Hs)
FP3|31|FP3_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP3|32|FP3_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP3|33|FP3_VAZIO|C|1|0|Vazio/Carreg|Vazio/Carreg
--- ### FP4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP4|01|FP4_FILIAL|C|6|0|Filial|Filial do Sistema
FP4|02|FP4_PROJET|C|22|0|Projeto|Projeto
FP4|03|FP4_OBRA|C|3|0|Obra|Obra
FP4|04|FP4_SEQGUI|C|3|0|Seq.Guind.|Seq
FP4|05|FP4_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FP4|06|FP4_CODTAB|C|3|0|Tabela Preco|Codigo Tabela de Preco
FP4|07|FP4_DESTAB|C|30|0|Descr.Tabela|Descr. da tabela de preco
FP4|08|FP4_PRODUT|C|15|0|Produto|Codigo do Produto
FP4|09|FP4_DESPRO|C|70|0|Desc. Produt|Descricao do produto
FP4|10|FP4_GUINDA|C|16|0|Frota|Frota
FP4|11|FP4_CODMAO|C|5|0|Mao-de-Obra|Mao-de-Obra
FP4|12|FP4_DESGUI|C|40|0|Equip./ M.O.|Equip./ M.O.
FP4|13|FP4_CONFIG|C|80|0|Configuracao|Configuracao
FP4|14|FP4_LOCTER|C|1|0|Loc.Terceiro|Loc.Terceiro
FP4|15|FP4_TIPOCA|C|1|0|Base Calculo|Base Calculo
FP4|16|FP4_PREDIA|N|4|0|Previs.Base|Previs.Base
FP4|17|FP4_QTMES|N|2|0|Qtd. Meses|QTD. MESES
FP4|18|FP4_QTDIA|N|2|0|Qtd. Dias|Qtd. Dias
FP4|19|FP4_MINDIA|N|2|0|Min.Hrs.Dia|Min.Hrs.Dia
FP4|20|FP4_MINMES|N|3|0|Min.Hrs.Mes|Min.Hrs.Mes
FP4|21|FP4_VRHOR|N|12|2|Vr.Base|Vr.Base
FP4|22|FP4_VRDIS|N|12|2|Vr. a Dispos|Vr. a Disposicao
FP4|23|FP4_SAIRET|C|1|0|Saida ao Ret|Saida ao Ret
FP4|24|FP4_VRMOB|N|12|2|Mob/ Frete|Valor do Mob ou Frete ida
FP4|25|FP4_VRDES|N|12|2|Desmob/Frete|Desmob/Frete
FP4|26|FP4_VLPEDA|N|6|2|Vlr. Pedagio|Valor do pedagio
FP4|27|FP4_RATEIO|C|6|0|Rateio Filia|Rateio Filial
FP4|28|FP4_FLMAQ|C|6|0|Filial MAQ|Filial MAQ
FP4|29|FP4_FLMO|C|6|0|Filial M.O.|Filial M.O.
FP4|30|FP4_QVEICP|N|3|0|Qtd.Veiculos|Qtde Veic CP
FP4|31|FP4_VRUNIT|N|12|2|Transp.Acess|Valor Base
FP4|32|FP4_VRPESO|N|12|2|Vr.Tot.T.A.|Vr.T.C.Peso
FP4|33|FP4_VRESTA|N|12|2|Vlr. Estadia|Vlr. Estadia
FP4|34|FP4_TPMEDI|C|1|0|Med.Locacao|Tipo Medicao
FP4|35|FP4_APOHRS|C|1|0|Apont.Horas|Apontamento de Horas
FP4|36|FP4_TPMEDM|C|1|0|Med.Mob.|Tp.Med.Mob.
FP4|37|FP4_TPMEDD|C|1|0|Med.Desmob.|Tp.Med.Desm.
FP4|38|FP4_VRCARG|N|12|2|Vr.Segurado|Vr.Segurado
FP4|39|FP4_TPSEGU|C|1|0|Tipo Seguro|Tipo Seguro
FP4|40|FP4_PERSEG|N|7|3|% Seguro|% Seguro
FP4|41|FP4_VRSEGU|N|14|2|Vr.Seguro|Vr.Seguro
FP4|42|FP4_TPISS|C|1|0|Tipo ISS|Tipo ISS
FP4|43|FP4_PERISS|N|6|2|% ISS|% ISS
FP4|44|FP4_VRISS|N|14|2|Valor ISS|Valor ISS
FP4|45|FP4_VRICMS|N|12|2|Vlr. ICMS|Valor do ICMS.
FP4|46|FP4_PERMAO|N|6|2|% M.de Obra|% M.de Obra
FP4|47|FP4_DTINI|D|8|0|Dt.Inicio|Dt.Inicio
FP4|48|FP4_DTFIM|D|8|0|Dt.Final|Dt.Final
FP4|49|FP4_HRINI|C|4|0|Hr.Inicio|Hr.Inicio
FP4|50|FP4_HRFIM|C|4|0|HR Fim|HR Fim
FP4|51|FP4_SABADO|C|1|0|Sabado?|Trabalha Sabado?
FP4|52|FP4_DOMING|C|1|0|Domingo?|Trabalha Domingo?
FP4|53|FP4_HORVIA|N|4|0|Hrs.Viagem|Hrs.Viagem
FP4|54|FP4_CONPAG|C|3|0|Cond.Pagto|Cond.Pagto
FP4|55|FP4_TIPPAG|C|1|0|Tipo Pagto|Tipo Pagto
FP4|56|FP4_RESPC|C|1|0|Resp. Carga|Responsavel pela carga
FP4|57|FP4_RESPD|C|1|0|Resp. Descg.|Responsavel pela descarga
FP4|58|FP4_OBS|M|10|0|Observacao|Observacao
FP4|59|FP4_VIAGEM|C|6|0|Viagem|Viagem
FP4|60|FP4_AS|C|27|0|Nr. A.S.|Nr. A.S.
FP4|61|FP4_THORAS|N|5|0|Total Horas|Total Horas
FP4|62|FP4_CUSIND|N|6|2|%Custo Indi.|%Custo Indireto
FP4|63|FP4_VALAS|N|12|2|Valor Tot.AS|Valor Total AS
FP4|64|FP4_LARG|N|6|2|Largura (mm)|Largura (mm)
FP4|65|FP4_ALTU|N|6|2|Altura (mm)|Altura (mm)
FP4|66|FP4_DIAM|N|6|0|Diametro(mm)|Diametro(mm)
FP4|67|FP4_PESO|N|9|3|Peso (Ton)|Peso (Ton)
FP4|68|FP4_QUANT|N|4|0|Quantidade|Quantidade
FP4|69|FP4_VRHORN|N|12|2|Vr.Hr.Negoci|Vr.Hr.Negoci
FP4|70|FP4_PREKM|N|14|4|Total de Km|Total de Km
FP4|71|FP4_PREHOR|N|4|0|Previs.Horas|Previs.Horas
FP4|72|FP4_VRHOR1|N|12|2|Vr.Hr.Minimo|Vr.Hr.Minimo
FP4|73|FP4_COMP|N|6|2|Compr.(mm)|Compr.(mm)
FP4|74|FP4_VRHOR2|N|12|2|Vr.Hr.Maximo|Vr.Hr.Maximo
FP4|75|FP4_VREXCE|N|12|2|Vr.Hr.Exced.|Vr.Hr.Exced.
FP4|76|FP4_VRMOB1|N|12|2|Vr.Mobil.Min|Vr.Mobil.Min
FP4|77|FP4_VRMOB2|N|12|2|Vr.Mobil.Max|Vr.Mobil.Max
FP4|78|FP4_CARACT|C|50|0|Caract. Prod|Caracteristica do produto
FP4|79|FP4_VRMOBN|N|12|2|Vr.Mob.Negoc|Vr.Mob.Negoc
FP4|80|FP4_VRDES1|N|12|2|Vr.Desmo.Min|Vr.Desmo.Min
FP4|81|FP4_VRDES2|N|12|2|Vr.Desmo.Max|Vr.Desmo.Max
FP4|82|FP4_VRDESN|N|12|2|Vr.Desm.Nego|Vr.Desm.Nego
FP4|83|FP4_PRENEG|N|12|2|Preco Negoc.|Preco Negoc.
FP4|84|FP4_PREFEC|N|12|2|Pre.Fechado|Pre.Fechado
FP4|85|FP4_OBSSER|M|10|0|Desc.Servico|Desc.Servico
FP4|86|FP4_OBSOBR|M|10|0|Observacoes|Observacoes
FP4|87|FP4_VRKM|N|12|2|Valor KM|Valor KM
FP4|88|FP4_TOTKM|N|12|2|Vr.Total KM|Vr.Total KM
FP4|89|FP4_GUIALO|C|16|0|Guind.Alocad|Guind.Alocad
FP4|90|FP4_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FP4|91|FP4_VRTOTA|N|12|2|Preco Total|Preco Total
FP4|92|FP4_TPVAL|C|1|0|Tipo Valor|Tipo Valor
FP4|93|FP4_QTEIXO|N|2|0|Qtd.Eixos|Qtd.Eixos
FP4|94|FP4_QTMONT|C|3|0|Qt Montagem|Qt Montagem
FP4|95|FP4_QTDESM|C|3|0|Qt Desmonta|Qt Desmonta
FP4|96|FP4_SEQCAR|C|3|0|Seq.Carga|Seq.Carga
FP4|97|FP4_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP4|98|FP4_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP4|99|FP4_REVNAS|N|2|0|Revisao AS|Revisao AS
FP4|9A|FP4_DTAS|D|8|0|Geracao AS|Geracao AS
FP4|9B|FP4_FORPG|C|1|0|Forma de Pag|Forma de Pag
FP4|9C|FP4_FORPAG|C|1|0|Forma Pgto|Forma Pgto
FP4|9D|FP4_DESCON|C|1|0|Desconto|Desconto
FP4|9E|FP4_VALDES|N|12|2|Vlr desconto|Vlr desconto
FP4|9F|FP4_HPROD|N|12|2|Vl Hr Produt|Valor Hrs Produtivas
FP4|9G|FP4_HIMPR|N|12|2|Vl Hrs Impro|Valor Hrs Improdutivas
FP4|9H|FP4_HEXCED|N|12|2|Vl Hrs Exced|Valor Hrs Excedentes
FP4|9I|FP4_HADICI|N|12|2|Vl Hrs Adici|Valor Hrs Adicionais
FP4|9J|FP4_HGREVE|N|12|2|Vl Hrs de Gr|Valor Hrs de Greve
FP4|9K|FP4_HCHUVA|N|12|2|Vl Hrs de Ch|Valor Hrs de Chuva
FP4|9L|FP4_HDISPO|N|12|2|Vl Hrs a Dis|Valor Hrs a Disposicao
FP4|9M|FP4_CABTEN|N|12|2|Vl Hrs Cab T|Valor Hrs Cabo Tencionado
FP4|9N|FP4_VLMOBR|N|12|2|Vl Mao obra|Vlr Mao obra destacada
FP4|9O|FP4_HEMOBR|N|12|2|Vl HE mao ob|Vl HE mao obra destacada
FP4|9P|FP4_KMROD|N|12|2|Vl KM Rodado|Valor KM Rodado
FP4|9Q|FP4_HORIME|N|12|2|Vl Horimetro|Valor Horimetro
FP4|9R|FP4_JUNKH|C|1|0|Jun KM/Horim|Junta KM/Horimetro
FP4|9S|FP4_ALEVEN|C|1|0|Alerta Venc?|Alerta Vencimento?
FP4|9T|FP4_FERIAD|C|1|0|Feriado?|Trabalha Feriado?
FP4|9U|FP4_NOTURN|C|1|0|Noturno?|Trabalha Noturno?
FP4|9V|FP4_PEDCLI|C|15|0|Ped. Cliente|Pedido de cliente
FP4|9W|FP4_SOLICT|C|50|0|Solicitante|Solicitante
FP4|9X|FP4_PERICM|N|6|2|Perc. ICMS|Percentual de ICMS.
--- ### FP5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP5|01|FP5_FILIAL|C|6|0|Filial|Filial do Sistema
FP5|02|FP5_PROJET|C|22|0|Projeto|Projeto
FP5|03|FP5_CODCLI|C|6|0|COD.CLIENTE|COD.CLIENTE
FP5|04|FP5_LOJA|C|2|0|LOJA CLIENTE|LOJA CLIENTE
FP5|05|FP5_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FP5|06|FP5_OBRA|C|3|0|Obra|Obra
FP5|07|FP5_COD|C|6|0|Codigo RAT|Codigo RAT
FP5|08|FP5_REVISA|C|3|0|Revisao|Revisao
FP5|09|FP5_COMPLE|C|3|0|Complementar|Complementar
FP5|10|FP5_ITEM|C|3|0|Item|Item
FP5|11|FP5_CODST9|C|16|0|Cod Bem/Equi|Cod Bem/Equipamento
FP5|12|FP5_DESC|C|50|0|Descricao|Descricao Operacao
FP5|13|FP5_COMP|N|12|3|Compr(mm)|Compr(mm)
FP5|14|FP5_LARG|N|12|3|Largura(mm)|Largura(mm)
FP5|15|FP5_ALTU|N|12|3|Altura (mm)|Altura (mm)
FP5|16|FP5_DIAM|N|12|3|Diametro(mm)|Diametro(mm)
FP5|17|FP5_PESO|N|12|3|Peso (Ton)|Peso (Ton)
FP5|18|FP5_DTVIS|D|8|0|Dt.Vistoria|Dt.Vistoria
FP5|19|FP5_GESTOR|C|20|0|Gestor Obra|Gestor Obra
FP5|20|FP5_RESPON|C|30|0|Responsavel|Responsavel
FP5|21|FP5_EMISSA|D|8|0|Emissao|Emissao
FP5|22|FP5_INLOCO|C|1|0|In Loco|In Loco
FP5|23|FP5_DESEN|C|20|0|Desenho|Desenho
FP5|24|FP5_PRAZO|D|8|0|Prazo Exec|Prazo Exec
FP5|25|FP5_VRSERV|N|12|2|Vr.Servico|Vr.Servico
FP5|26|FP5_SITUAC|C|1|0|Status|Status
FP5|27|FP5_DTREAL|D|8|0|Dt. Realizac|Dt. Realizac
FP5|28|FP5_SEQTRA|C|3|0|SEQ CAR|SEQ CAR
FP5|29|FP5_OBSERV|M|10|0|Obs Servico|Obs Servico
FP5|30|FP5_OBS|M|10|0|Observacao|Observacao
FP5|31|FP5_OBSOPE|M|10|0|Obs Operador|Obs Operador
FP5|32|FP5_OBSEQU|M|10|0|Obs. Equipa|Obs. Equipa
FP5|33|FP5_OBSACE|M|10|0|Obs. Acessor|Obs. Acessor
FP5|34|FP5_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP5|35|FP5_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP5|36|FP5_PRIORI|C|6|0|Prioridade|Prioridade
FP5|37|FP5_TPPROJ|C|1|0|Tp Projeto|Tp Projeto
FP5|38|FP5_TPSERV|C|1|0|Tp Servico|Tipo Servico
FP5|39|FP5_PRODUT|C|15|0|Produto|Produto
FP5|40|FP5_DIAMCA|N|12|3|Dimen.Carga|Dimensao de Carga
FP5|41|FP5_QUANTC|N|9|2|Quant.Carga|Quantidade Carga
--- ### FP6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP6|01|FP6_FILIAL|C|6|0|Filial|Filial do Sistema
FP6|02|FP6_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FP6|03|FP6_OBRA|C|3|0|Obra|Obra
FP6|04|FP6_SEQGUI|C|3|0|Seq. Loc.|Sequencia Locacao
FP6|05|FP6_SEQRES|C|3|0|Seq|Seq
FP6|06|FP6_CODIGO|C|3|0|Responsabil.|Responsabil.
FP6|07|FP6_DESCRI|C|30|0|Desc.Respons|Desc.Respons
FP6|08|FP6_RESPON|C|1|0|Responsavel|Responsavel
FP6|09|FP6_DESCCO|M|10|0|Des.Completa|Des.Completa
FP6|10|FP6_VALOR|N|14|2|Custo|Custo
FP6|11|FP6_VALCOB|N|14|2|Valor Cobrar|Valor Cobrar
FP6|12|FP6_TRECHO|C|3|0|Trecho|Trecho
FP6|13|FP6_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP6|14|FP6_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FP7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP7|01|FP7_FILIAL|C|6|0|Filial|Filial do Sistema
FP7|02|FP7_CODIGO|C|3|0|Responsabil.|Responsabil.
FP7|03|FP7_DESCRI|C|80|0|Desc.Respons|Desc.Respons
FP7|04|FP7_DESCCO|M|10|0|Des.Completa|Des.Completa
FP7|05|FP7_RESPON|C|1|0|Responsavel|Responsavel
FP7|06|FP7_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FP7|07|FP7_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP7|08|FP7_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP7|09|FP7_NTREZA|C|10|0|Natureza|Natureza
FP7|10|FP7_ID|C|2|0|ID|ID
FP7|11|FP7_ALTURA|N|5|2|Alt.Superior|Altura Superior
FP7|12|FP7_VLR|N|12|2|Valor Noite|Valor Noite
FP7|13|FP7_PADRAO|C|1|0|Padrao?|Padrao?
--- ### FP8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP8|01|FP8_FILIAL|C|6|0|Filial|Filial do Sistema
FP8|02|FP8_PROJET|C|22|0|Projeto|Projeto
FP8|03|FP8_OBRA|C|3|0|Viagem|Obra
FP8|04|FP8_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FP8|05|FP8_SEQCAR|C|3|0|Seq.Carga|Seq.Carga
FP8|06|FP8_SEQCON|C|3|0|Seq.Conjunto|Seq.Conjunto
FP8|07|FP8_TRANSP|C|16|0|Transporte|Transporte
FP8|08|FP8_DESTRA|C|40|0|Desc.Transp.|Desc.Transp.
FP8|09|FP8_COMP|N|6|2|Compr.(mt)|Compr.(mt)
FP8|10|FP8_LARG|N|6|2|Largura (mt)|Largura (mt)
FP8|11|FP8_ALTU|N|6|2|Altura (mt)|Altura (mt)
FP8|12|FP8_DIAM|N|6|0|Diametro(mm)|Diametro(mm)
FP8|13|FP8_PESO|N|9|3|Peso (Ton)|Peso (Ton)
FP8|14|FP8_QTEIXO|N|3|0|Qtde Eixos|Qtde Eixos
FP8|15|FP8_TIPOCA|C|1|0|Tipo Calculo|Tipo Calculo
FP8|16|FP8_DIASV|N|4|0|Dias Vazio|Dias Vazio
FP8|17|FP8_DIASC|N|4|0|Dias Carreg.|Dias Carreg.
FP8|18|FP8_VRDIA|N|12|2|Valor Base|Valor Base
FP8|19|FP8_VRESTA|N|12|2|Vr.Estadia|Vr.Estadia
FP8|20|FP8_CARENC|C|3|0|Carencia|Carencia
FP8|21|FP8_HORADI|N|6|2|Hr.Adicional|Hora Adicional
FP8|22|FP8_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FP8|23|FP8_DTINI|D|8|0|Dt.Inicio|Dt.Inicio
FP8|24|FP8_DTFIM|D|8|0|Dt.Final|Dt.Final
FP8|25|FP8_PREDIA|C|3|0|Prev.Dias|Prev.Dias
FP8|26|FP8_PREHOR|C|4|0|Prev.Horas|Prev.Horas
FP8|27|FP8_OBSVIA|M|10|0|Obs.Viagem|Obs.Viagem
FP8|28|FP8_OPERCD|N|4|0|Op.Carga/Des|Op.Carga/Des
FP8|29|FP8_EHTERC|C|1|0|Terceiro|Terceiro
FP8|30|FP8_HRINI|C|8|0|Hora Inicio|Hora Inicial
FP8|31|FP8_HRFIM|C|8|0|Hora Fim|Hora Fim
FP8|32|FP8_TRALOC|C|16|0|Transp Aloca|Transp Aloca
FP8|33|FP8_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FP8|34|FP8_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP8|35|FP8_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FP9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FP9|01|FP9_FILIAL|C|6|0|Filial|Filial do Sistema
FP9|02|FP9_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FP9|03|FP9_OBRA|C|3|0|Obra|Obra
FP9|04|FP9_FOLLOW|M|10|0|Follow-up|Follow-up
FP9|05|FP9_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FP9|06|FP9_USERGA|C|17|0|Log de Alter|Log de Alteracao
FP9|07|FP9_ITEM|C|3|0|Item|Item
FP9|08|FP9_DATA|D|8|0|Data|Data
FP9|09|FP9_DDIA|D|8|0|Data do dia|Data do dia
FP9|10|FP9_USER|C|30|0|Usuario|Usuario
FP9|11|FP9_MAIL|C|50|0|Email|Email
--- ### FPA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPA|01|FPA_FILIAL|C|6|0|Filial|Filial do Sistema
FPA|02|FPA_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FPA|03|FPA_OBRA|C|3|0|Obra|Obra
FPA|04|FPA_SEQGRU|C|3|0|Sequencia|Sequencia
FPA|05|FPA_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FPA|06|FPA_SEQSUB|C|3|0|Equip. Subs.|Equipamento Substituido
FPA|07|FPA_CODTAB|C|3|0|Tab. Preco|Tabela de preco
FPA|08|FPA_DESTAB|C|30|0|Desc. Tab|Desc. Tab
FPA|09|FPA_PRODUT|C|15|0|Produto|Codigo do Produto
FPA|10|FPA_DESPRO|C|70|0|Desc. Produt|Desc. Produt
FPA|11|FPA_LOCAL|C|2|0|Armazem|Armazem
FPA|12|FPA_GRUA|C|16|0|Equipamento|Codigo Equipamento
FPA|13|FPA_DESGRU|C|40|0|Descricao|Descricao do Equipamento
FPA|14|FPA_CARAC|C|50|0|Caract. Prod|Caracterisitca do Produto
FPA|15|FPA_OBSSER|M|10|0|Desc.Servico|Desc.Servico
FPA|16|FPA_PREDIA|N|3|0|Qtd.Base|Qtd.Base
FPA|17|FPA_MINDIA|N|3|0|Min.Hrs.Dia|Min.Hrs.Dia
FPA|18|FPA_MINMES|N|3|0|Min.Hrs.Mes|Min.Hrs.Mes
FPA|19|FPA_QUANT|N|4|0|Quantidade|Quantidade
FPA|20|FPA_ACRESC|N|12|2|Acrescimo|Valor Acrescimo
FPA|21|FPA_PRCUNI|N|12|2|Valor Unit.|Valor Unitario
FPA|22|FPA_CARENC|C|3|0|Carencia|Carencia
FPA|23|FPA_VLBRUT|N|12|2|Valor Bruto|Valor Bruto
FPA|24|FPA_PDESC|N|5|2|% Desconto|% Desconto
FPA|25|FPA_VRHOR|N|12|2|Vr.Base|Vr.Base
FPA|26|FPA_TPGUIM|C|1|0|Resp.Frt Ida|Resp.Frt Ida
FPA|27|FPA_GUIMON|N|12|2|Vl.Frete Ida|Vl.Frete Ida
FPA|28|FPA_TPGUID|C|1|0|Resp.F Volta|Respons. Frete Volta
FPA|29|FPA_GUIDES|N|12|2|Vl. Fr Volta|Valor Frete Volta
FPA|30|FPA_VLPEDA|N|6|2|Vlr. Pedagio|Valor do pedagio
FPA|31|FPA_HRENRE|N|6|2|Hr. Ent/Ret.|Hora adicional de Ent/Ret
FPA|32|FPA_VREXCE|N|12|2|Vr.Hr.Exced.|Vr.Hr.Exced.
FPA|33|FPA_DIARIA|N|12|2|Diaria|Diaria
FPA|34|FPA_HORADI|N|6|2|Hr.Adicional|Hora adicional do equipa.
FPA|35|FPA_UTIMES|C|3|0|Utilz/Mes|Utilizacao/Mes-Horimetro
FPA|36|FPA_DIAFEC|C|2|0|Dia Fech. Ms|Dia de fechamento mensal
FPA|37|FPA_TPISS|C|1|0|Tipo ISS|Tipo ISS
FPA|38|FPA_PERISS|N|6|2|% ISS|% ISS
FPA|39|FPA_VRISS|N|14|2|Valor ISS|Valor ISS
FPA|40|FPA_VRSEGU|N|14|2|Vr Seguro|Vr Seguro
FPA|41|FPA_DTINI|D|8|0|Dt.Inicio|Dt.Inicio
FPA|42|FPA_HRINI|C|4|0|Hr.Inicio|Hr.Inicio
FPA|43|FPA_HRFIM|C|4|0|Hora Fim|Hora Fim
FPA|44|FPA_DTFIM|D|8|0|Dt.Prox.Fat|Data do Proximo Faturamen
FPA|45|FPA_DTENRE|D|8|0|Dt.Fim Loc.|Data fim de locacao
FPA|46|FPA_LOCDIA|N|6|0|Dias de loc.|Dias de Locacao
FPA|47|FPA_DTPRRT|D|8|0|Prev. Retira|Previsao de Retirada
FPA|48|FPA_ULTFAT|D|8|0|Ult. Faturam|Ultimo Faturamento
FPA|49|FPA_SABADO|C|1|0|Trab.Sabado|Trab.Sabado
FPA|50|FPA_DOMING|C|1|0|Trab.Domingo|Trab.Domingo
FPA|51|FPA_CONPAG|C|3|0|Cond.Pagto|Cond.Pagto
FPA|52|FPA_TIPPAG|C|1|0|Tipo Pagto|Tipo Pagto
FPA|53|FPA_OBS|M|10|0|Observacao|Observacao
FPA|54|FPA_REVNAS|N|2|0|Revisao AS|Revisao AS
FPA|55|FPA_AS|C|27|0|Nr. A.S.|Nr. A.S.
FPA|56|FPA_VIAGEM|C|6|0|Viagem|Viagem
FPA|57|FPA_DTPREN|D|8|0|Prev. Entreg|Prev. Entreg
FPA|58|FPA_MOTENT|C|6|0|Motor. Entre|Motorita Entrega
FPA|59|FPA_NMOTEN|C|40|0|Motorista|Motorista
FPA|60|FPA_NFREM|C|9|0|NF Remessa|NF Remessa
FPA|61|FPA_DNFREM|D|8|0|DT NF Remess|DT NF Remessa
FPA|62|FPA_NFENT|C|9|0|N. Canhoto|Numero do canhoto
FPA|63|FPA_DNFENT|D|8|0|Dt Ent. Real|Data de entrega real
FPA|64|FPA_PLACAI|C|7|0|Placa Ida|Placa do Caminha Ida
FPA|65|FPA_REBOQI|C|30|0|Reboque Ida|Reboque Ida
FPA|66|FPA_DTSCRT|D|8|0|Dat Solic Re|Data Solictacao de Retira
FPA|67|FPA_MOTRET|C|6|0|Motor. Retir|Motorista Retirada
FPA|68|FPA_NMOTRE|C|40|0|Motorista|Motorista
FPA|69|FPA_NFRET|C|9|0|NF Retorno|NF Retorno
FPA|70|FPA_DNFRET|D|8|0|Dt. NF. Ret|Dt. NF. Retorno
FPA|71|FPA_ALEVEN|C|1|0|Alerta Venc?|Alerta Vencimento?
FPA|72|FPA_CNJ|C|2|0|Conj. Transp|Conj. Transportador
FPA|73|FPA_COMP|N|6|0|Compr.(mm)|Compr.(mm)
FPA|74|FPA_LARG|N|6|0|Largura (mm)|Largura (mm)
FPA|75|FPA_ALTU|N|6|0|Altura (mm)|Altura (mm)
FPA|76|FPA_DIAM|N|6|0|Diametro(mm)|Diametro(mm)
FPA|77|FPA_PESO|N|9|3|Peso (Ton)|Peso (Ton)
FPA|78|FPA_TPBASE|C|1|0|Base Calculo|Base Calculo
FPA|79|FPA_HORVIA|N|4|0|Hrs.Viagem|Hrs.Viagem
FPA|80|FPA_VRHORN|N|12|2|Vr.Hr.Negoci|Vr.Hr.Negoci
FPA|81|FPA_VRMOB|N|12|2|Vr.Mobiliz.|Vr.Mobilização
FPA|82|FPA_VRDES|N|12|2|Vr.Desmob.|Vr.Desmobilização
FPA|83|FPA_PREHOR|N|4|0|Previs.Horas|Previs.Horas
FPA|84|FPA_VRHOR1|N|12|2|Vr.Hr.Minimo|Vr.Hr.Minimo
FPA|85|FPA_VRHOR2|N|12|2|Vr.Hr.Maximo|Vr.Hr.Maximo
FPA|86|FPA_VRMOB1|N|12|2|Vr.Mobil.Min|Vr.Mobil.Min
FPA|87|FPA_VRMOB2|N|12|2|Vr.Mobil.Max|Vr.Mobil.Max
FPA|88|FPA_VRMOBN|N|12|2|Vr.Mob.Negoc|Vr.Mob.Negoc
FPA|89|FPA_VRDES1|N|12|2|Vr.Desmo.Min|Vr.Desmo.Min
FPA|90|FPA_VRDES2|N|12|2|Vr.Desmo.Max|Vr.Desmo.Max
FPA|91|FPA_VRDESN|N|12|2|Vr.Desm.Nego|Vr.Desm.Nego
FPA|92|FPA_PRENEG|N|12|2|Preco Negoc.|Preco Negoc.
FPA|93|FPA_PREFEC|N|12|2|Pre.Fechado|Pre.Fechado
FPA|94|FPA_OBSOBR|M|10|0|Observacoes|Observacoes
FPA|95|FPA_LOCTER|C|1|0|Loc.Terceiro|Loc.Terceiro
FPA|96|FPA_SAIRET|C|1|0|Saida ao Ret|Saida ao Ret
FPA|97|FPA_QVEICP|N|3|0|Qtde Veic CP|Qtde Veic CP
FPA|98|FPA_VRKM|N|12|2|Valor KM|Valor KM
FPA|99|FPA_TOTKM|N|12|2|Vr.Total KM|Vr.Total KM
FPA|9A|FPA_VRPESO|N|12|2|Vr.T.C.Peso|Vr.T.C.Peso
FPA|9B|FPA_TPMEDI|C|1|0|Tipo Medicao|Tipo Medicao
FPA|9C|FPA_TPSEGU|C|1|0|Tipo Seguro|Tipo Seguro
FPA|9D|FPA_PERSEG|N|6|2|% Seguro|% Seguro
FPA|9E|FPA_PERMAO|N|6|2|% M.de Obra|% M.de Obra
FPA|9F|FPA_TIPOCA|C|1|0|Tp.Franquia|Tipo da franquia
FPA|9G|FPA_GUIALO|C|16|0|Guind.Alocad|Guind.Alocad
FPA|9H|FPA_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FPA|9I|FPA_VRUNIT|N|12|2|Preco Unit.|Preco Unit.
FPA|9J|FPA_VRTOTA|N|12|2|Preco Total|Preco Total
FPA|9K|FPA_TPVAL|C|1|0|Tipo Valor|Tipo Valor
FPA|9L|FPA_QTEIXO|N|2|0|Qtd.Eixos|Qtd.Eixos
FPA|9M|FPA_MONTAG|N|12|2|Montagem|Montagem
FPA|9N|FPA_DESMON|N|12|2|Desmontagem|Desmontagem
FPA|9O|FPA_TELESC|N|12|2|Telescopagem|Telescopagem
FPA|9P|FPA_ANCORA|N|12|2|Ancoragem|Ancoragem
FPA|9Q|FPA_OPERAD|N|12|2|Operador|Operador
FPA|9R|FPA_TPMED1|C|1|0|Med.Montagem|Med.Montagem
FPA|9S|FPA_TPMED2|C|1|0|Med.Desmont.|Med.Desmont.
FPA|9T|FPA_TPMED3|C|1|0|Med.Telescop|Med.Telescop
FPA|9U|FPA_TPMED4|C|1|0|Med.Ancorag.|Med.Ancorag.
FPA|9V|FPA_SEQEST|C|19|0|Estrutura|Seq.Estrutura
FPA|9W|FPA_TPMED5|C|1|0|Med.Gui.Mont|Med.Gui.Mont
FPA|9X|FPA_TPMED6|C|1|0|Med.Gui.Desm|Med.Gui.Desm
FPA|9Y|FPA_TPMED7|C|1|0|Med.Operador|Med.Operador
FPA|9Z|FPA_HEMAQ|N|12|2|HE Maquina|HE Maquina
FPA|A0|FPA_HEOPE|N|12|2|HE Operador|HE Operador
FPA|A1|FPA_HEFDS|N|12|2|H.E  F.D.S|H.E  F.D.S
FPA|A2|FPA_LANCA|N|12|2|Compr.Lanca|Compr.Lanca
FPA|A3|FPA_TORREI|N|12|2|Torre Inic.|Torre Inic.
FPA|A4|FPA_TORREF|N|12|2|Torre Final|Torre Final
FPA|A5|FPA_CAPACI|N|12|2|Carga Max.|Carga Max.
FPA|A6|FPA_CARACT|C|1|0|Caracterist.|Caracterist.
FPA|A7|FPA_VRCARG|N|12|2|Vlr.Base Seg|Valor base do seguro
FPA|A8|FPA_TPMOBI|C|1|0|Med.Mob|Med.Mob
FPA|A9|FPA_TPDESM|C|1|0|Med.Desmob|Med.Desmob
FPA|AA|FPA_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPA|AB|FPA_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPA|AC|FPA_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPA|AD|FPA_PES|N|3|0|Altura (Pes)|Altura (Pes)
FPA|AE|FPA_CONJT|C|30|0|Conj Transp|Conjunto Transportador
FPA|AF|FPA_VLEST|N|12|2|Vlr Estadia|Valor da Estadia
FPA|AG|FPA_DTAS|D|8|0|Geracao AS|Geracao AS
FPA|AH|FPA_CHUMBA|N|12|2|Emissa carb.|Emissão de carbno
FPA|AI|FPA_DIASM|N|2|0|Dias Montage|Dias Montage
FPA|AJ|FPA_DIASD|N|2|0|Dias Desmont|Dias Desmontagem
FPA|AK|FPA_DIAST|N|2|0|Dias Tel/Anc|Dias Telescopagem/Ancorag
FPA|AL|FPA_TPOPER|C|1|0|Resp.Operac.|Responsavel pela operacao
FPA|AM|FPA_TPMEDB|C|1|0|Tp Med base|Tipo de Medicao da Base
FPA|AN|FPA_FORPG|C|1|0|Forma de Pag|Forma de Pag
FPA|AO|FPA_RATEIO|C|3|0|Rateio Filia|Rateio Filiais
FPA|AP|FPA_FLMAQ|C|6|0|Filial Maq|Filial Maq
FPA|AQ|FPA_FLMO|C|6|0|Filial M.O.|Filial M.O.
FPA|AR|FPA_FORPAG|C|1|0|Forma Pgto|Forma Pgto
FPA|AS|FPA_DESCON|C|1|0|Desconto|Desconto
FPA|AT|FPA_VALDES|N|12|2|Vlr desconto|Vlr desconto
FPA|AU|FPA_HPROD|N|12|2|Vl Hr Produt|Vl Hr Produt
FPA|AV|FPA_HIMPR|N|12|2|Vl Hrs Impro|Valor Hrs Improdutivas
FPA|AW|FPA_HEXCED|N|12|2|Vl Hrs Exced|Valor Hrs Excedentes
FPA|AX|FPA_HADICI|N|12|2|Vl Hrs Adici|Valor Hrs Adicionais
FPA|AY|FPA_HGREVE|N|12|2|Vl Hrs de Gr|Valor Hrs de Greve
FPA|AZ|FPA_HCHUVA|N|12|2|Vl Hrs de Ch|Valor Hrs de Chuva
FPA|B0|FPA_HDISPO|N|12|2|Vl Hrs a Dis|Valor Hrs a Disposicao
FPA|B1|FPA_CABTEN|N|12|2|Vl Hrs Cab T|Valor Hrs Cabo Tencionado
FPA|B2|FPA_VLMOBR|N|12|2|Vl Mao obra|Vlr Mao obra destacada
FPA|B3|FPA_HEMOBR|N|12|2|Vl HE mao ob|Vl HE mao obra destacada
FPA|B4|FPA_KMROD|N|12|2|Vl KM Rodado|Vl KM Rodado
FPA|B5|FPA_HORIME|N|12|2|Vl Horimetro|Vl Horimetro
FPA|B6|FPA_JUNKH|C|1|0|Jun KM/Horim|Jun KM/Horim
FPA|B7|FPA_THORAS|N|5|0|Total horas|Total horas
FPA|B8|FPA_CONFIG|C|80|0|Configuracao|Configuracao
FPA|B9|FPA_EMBARC|C|1|0|Embarcado|Embarcado
FPA|BA|FPA_CACAMB|C|1|0|Util.Cacamba|Utiliza Cacamba
FPA|BB|FPA_XRETRE|D|8|0|Dt.Ret Real|Data de retirada real
FPA|BC|FPA_PARIDA|C|9|0|NF PAR IDA|NF PAR IDA
FPA|BD|FPA_PARVOL|C|9|0|NF PAR VOLTA|NF PAR VOLTA
FPA|BE|FPA_SERRET|C|3|0|Serie Ret NF|Serie Ret NF
FPA|BF|FPA_PLACAV|C|7|0|Placa Volta|Placa Volta
FPA|BG|FPA_REBOQV|C|30|0|Reboq. Volta|Reboque Volta
FPA|BH|FPA_PEDIDO|C|6|0|PV remessa|Pedido Venda p/ Remessa
FPA|BI|FPA_FILREM|C|6|0|Filial Remes|Filial Remessa
FPA|BJ|FPA_SERREM|C|3|0|Serie Remess|Serie Remessa
FPA|BK|FPA_ITEREM|C|2|0|Item Remessa|Item Remessa
FPA|BL|FPA_HRFRAQ|N|8|2|Franquia|Franquia de Horas
FPA|BM|FPA_VLHREX|N|8|2|R$ Hrs Extra|R$ Horas Extras
FPA|BN|FPA_CUSTO|C|9|0|C Custo|Centro de Custo
FPA|BO|FPA_ITERET|C|4|0|Item.Ret|Item Retorno
FPA|BP|FPA_NATURE|C|10|0|Natureza|Natureza p/ PV Locacao
FPA|BQ|FPA_FILEMI|C|6|0|Fil.Remessa|Filial para remessa
FPA|BR|FPA_AJUSTE|C|3|0|Reajuste|Fator para reajuste
FPA|BS|FPA_DAJUST|C|30|0|Desc.ajuste|Descriçao do ajuste
FPA|BT|FPA_NIVER|D|8|0|Aniversario|Aniversario para reajuste
FPA|BU|FPA_TESFAT|C|3|0|TES Fat|TES faturamento
FPA|BV|FPA_TESREM|C|3|0|TES remessa|TES para remessa
FPA|BW|FPA_QTDPRC|N|3|0|Qtd. Parcela|Quantidade de parcelas
FPA|BX|FPA_CLIFAT|C|6|0|Cli.fat|Cliente de faturamento
FPA|BY|FPA_LOJFAT|C|2|0|Loj.fat|Loja faturamento
FPA|BZ|FPA_NOMFAT|C|80|0|Nom.fat|Nome faturamento
FPA|C0|FPA_PACRES|N|7|4|% Acrescimo|% Acrescimo
FPA|C1|FPA_GERAEM|D|8|0|Gera em|Gera em
FPA|C2|FPA_BASFRA|C|1|0|Base Franq.|Base da franquia
FPA|C3|FPA_GRUPOM|C|3|0|Grp.Medição|Grupo da medição
--- ### FPB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPB|01|FPB_FILIAL|C|6|0|Filial|Filial do Sistema
FPB|02|FPB_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FPB|03|FPB_OBRA|C|3|0|Obra|Obra
FPB|04|FPB_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FPB|05|FPB_SEQDOC|C|3|0|Item Docto|Item Docto
FPB|06|FPB_CODIGO|C|3|0|Cod.Docto|Cod.Docto
FPB|07|FPB_DESCRI|C|30|0|Desc.Docto|Desc.Docto
FPB|08|FPB_APRESE|C|1|0|Apresenta ?|Apresenta ?
FPB|09|FPB_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPB|10|FPB_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPB|11|FPB_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FPB|12|FPB_VALOBR|C|1|0|Vld.Obra|Valida a obra informada
FPB|13|FPB_TPDOC|C|2|0|Tp.Documento|Tipo do documento
FPB|14|FPB_DESCR|C|40|0|Descrição|Descrição
FPB|15|FPB_CODCON|C|6|0|Cod.Contato|Código do contato
FPB|16|FPB_NOME|C|50|0|Nome|Nome do contato
FPB|17|FPB_EMAIL|C|40|0|E-Mail|E-Mail
FPB|18|FPB_CPF|C|11|0|CPF|CPF
FPB|19|FPB_CARGO|C|6|0|Função|Função
FPB|20|FPB_DFUNCA|C|30|0|Descrição|Descrição da função
FPB|21|FPB_STATUS|C|1|0|Status|Status
FPB|22|FPB_APROV|C|1|0|Ação|Ação na aprovação
FPB|23|FPB_DOC|C|10|0|Documento|Documento
FPB|24|FPB_DESDOC|C|60|0|Descr.Doc.|Descrição do documento
FPB|25|FPB_IDTAE|C|9|0|Envelope|ID da integração TAE
FPB|26|FPB_DATAE|D|8|0|Data envio|Data de envio ao TAE
FPB|27|FPB_HORAE|C|8|0|Hora envio|Hora de envio ao TAE
--- ### FPC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPC|01|FPC_FILIAL|C|6|0|Filial|Filial do Sistema
FPC|02|FPC_CODIGO|C|3|0|Cod.Docto|Cod.Docto
FPC|03|FPC_DESCRI|C|100|0|Desc.Docto|Desc.Docto
FPC|04|FPC_USERGI|C|17|0|Log de Inclu|Log de Inclu
FPC|05|FPC_USERGA|C|17|0|Log de Alter|Log de Alter
FPC|06|FPC_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FPC|07|FPC_ASSINA|C|1|0|Assinatura|Enviar para Assinatura
FPC|08|FPC_BLGERA|C|1|0|Blq.Gera.Con|Bloqueia gerar contrato
FPC|09|FPC_BLREME|C|1|0|Blq.Remessa|Bloqueia remessa
--- ### FPD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPD|01|FPD_FILIAL|C|6|0|Filial|Filial do Sistema
FPD|02|FPD_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FPD|03|FPD_OBRA|C|3|0|Obra|Obra
FPD|04|FPD_SEQGUI|C|3|0|Seq.Guind.|Seq.Guind.
FPD|05|FPD_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FPD|06|FPD_SEQGRU|C|3|0|Seq.Grua|Seq.Grua
FPD|07|FPD_SEQCAR|C|3|0|Seq.Carga|Seq.Carga
FPD|08|FPD_ROTA|C|3|0|Rota|Rota
FPD|09|FPD_ETAPA|C|3|0|Etapa|Etapa
FPD|10|FPD_DE|C|6|0|De|De
FPD|11|FPD_MUNDE|C|25|0|Cidade De|Cidade De
FPD|12|FPD_ESTDE|C|2|0|UF De|UF De
FPD|13|FPD_ATE|C|6|0|Ate|Ate
FPD|14|FPD_MUNATE|C|25|0|Cidade Ate|Cidade Ate
FPD|15|FPD_ESTATE|C|2|0|UF Ate|UF Ate
FPD|16|FPD_DISTAN|N|5|0|Distancia KM|Distancia KM
FPD|17|FPD_TEMPO|N|7|2|Tempo (Dias)|Tempo (Dias)
FPD|18|FPD_VAZIO|C|1|0|Vazio/Carreg|Vazio/Carreg
FPD|19|FPD_IDAVOL|C|1|0|Dir Trecho|Direcao Trecho-ida/Volta
FPD|20|FPD_RODOVI|C|20|0|Rodovia|Rodovia
FPD|21|FPD_TEMTUR|C|1|0|Calcula TUR?|Calcula TUR?
FPD|22|FPD_QTDPED|N|3|0|Qtd.Pedagios|Qtd.Pedagios
FPD|23|FPD_VALPED|N|12|2|Vr.Pedagio|Vr.Pedagio
FPD|24|FPD_TIPORO|C|1|0|Tipo Rodovia|Tipo Rodovia
FPD|25|FPD_TIPOPI|C|1|0|Tipo Pista|Tipo Pista
FPD|26|FPD_ORIGEM|C|6|0|Origem|Origem
FPD|27|FPD_DESTIN|C|6|0|Destino|Destino
FPD|28|FPD_CET|C|1|0|Utiliza CET|Utiliza CET
FPD|29|FPD_DER|C|1|0|Utiliza DER|Utiliza DER
FPD|30|FPD_DNIT|C|1|0|Utiliza DNIT|Utiliza DNIT
FPD|31|FPD_CRED|N|2|0|Batedor Cred|Batedor Credenciado
FPD|32|FPD_MUNORI|C|25|0|Cid. Origem|Cid. Origem
FPD|33|FPD_MUNDES|C|25|0|Cid. Destino|Cid. Destino
FPD|34|FPD_ESTORI|C|2|0|UF Origem|UF Origem
FPD|35|FPD_ESTDES|C|2|0|UF Destino|UF Destino
FPD|36|FPD_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPD|37|FPD_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPD|38|FPD_CODIGO|C|6|0|Código|Código
FPD|39|FPD_DESC|C|40|0|Descrição|Descrição
--- ### FPE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPE|01|FPE_FILIAL|C|6|0|Filial|Filial do Sistema
FPE|02|FPE_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FPE|03|FPE_OBRA|C|3|0|Obra|Obra
FPE|04|FPE_FROTA|C|16|0|Equipamento|Equipamento
FPE|05|FPE_SEQGUI|C|3|0|Seq.Gui|Seq.Gui
FPE|06|FPE_TURNO|C|3|0|Turno|Turno
FPE|07|FPE_MINDIT|C|2|0|Min Dia Turn|Minino Dia Turno
FPE|08|FPE_DIASEM|C|1|0|Tp.Turno|Tipo do turno
FPE|09|FPE_HRINIT|C|4|0|Hr. Ini. Tur|Hora Inicial do Turno
FPE|10|FPE_HOFIMT|C|4|0|Hr. Fim. Tur|Hora Final do Turno
FPE|11|FPE_VALTUR|N|12|2|Vlr.Hr.Base|Valor base
FPE|12|FPE_VROPER|N|12|2|Vlr.Hr.Tur.|Valor final
FPE|13|FPE_PORCEN|N|6|2|%Hr.Extra|%Hr.Extra
FPE|14|FPE_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
--- ### FPF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPF|01|FPF_FILIAL|C|6|0|Filial|Filial do Sistema
FPF|02|FPF_COD|C|3|0|Codigo|Codigo
FPF|03|FPF_DESC|C|20|0|Descricao|Descricao do Grupo
FPF|04|FPF_FROTA|C|16|0|Frota|Frota
FPF|05|FPF_AS|C|27|0|Numero AS|Numero AS
FPF|06|FPF_DATA|D|8|0|Data|Data
FPF|07|FPF_MINUTA|C|6|0|Minuta|Minuta
FPF|08|FPF_PROJET|C|22|0|Projeto|Projeto
FPF|09|FPF_OBRA|C|3|0|OBRA|OBRA
FPF|10|FPF_MINUTM|C|6|0|MinutaManual|MinutaManual
FPF|11|FPF_NROMED|C|6|0|Nro Medicao|Nro Medicao
FPF|12|FPF_HORAI|C|4|0|Hora Inicial|Hora Inicial
FPF|13|FPF_HORAF|C|4|0|Hora Final|Hora Final
FPF|14|FPF_HRPARA|C|4|0|Hora Parada|Hora Parada
FPF|15|FPF_MOTIVO|C|1|0|Mot. Parada|Mot. Parada
FPF|16|FPF_MOTCAN|C|6|0|Motivo Canc.|Motivo Canc.
FPF|17|FPF_STATUS|C|1|0|Status|Status
FPF|18|FPF_TIPOSE|C|1|0|Tipo Bem|Tipo Bem
FPF|19|FPF_BXJANI|C|4|0|Jantar Ini|Jantar Inicio
FPF|20|FPF_BXJANF|C|4|0|Jantar Fim|Jantar Fim
FPF|21|FPF_BXOBS|M|10|0|Obs Baixa|Obs Baixa
FPF|22|FPF_BXALMI|C|4|0|Almoco Ini|Almoco Inicio
FPF|23|FPF_BXALMF|C|4|0|Almoco Fim|Almoco Fim
FPF|24|FPF_HREALI|C|4|0|Real Ini|Real Inicio
FPF|25|FPF_HREALF|C|4|0|Real Fim|Real Fim
FPF|26|FPF_EMISSA|D|8|0|Emissao|Emissao MINUTA
FPF|27|FPF_DTOCOR|D|8|0|Dt Ocorrenci|Dt Ocorrenci
FPF|28|FPF_HTB|C|4|0|H.Tot.Baixad|Hs.Tot.Baixado
FPF|29|FPF_HTR|C|4|0|H.Tot.Realiz|Hs.Tot.Realizado
FPF|30|FPF_MINDIA|N|3|0|Min.Dia|Mínimo de dias
FPF|31|FPF_TURNO|C|3|0|Turno|Turno
FPF|32|FPF_FILTRO|C|2|0|Filtro|Filtro do sistema
FPF|33|FPF_MEDSEQ|C|3|0|Seq.Medição|Sequência da Medição
--- ### FPG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPG|01|FPG_FILIAL|C|6|0|Filial|Filial do Sistema
FPG|02|FPG_PROJET|C|22|0|Projeto|Projeto
FPG|03|FPG_OBRA|C|3|0|Obra|Obra
FPG|04|FPG_NRAS|C|27|0|Nr. AS|Nr. AS
FPG|05|FPG_TIPO|C|1|0|Tipo|Tipo
FPG|06|FPG_CUSTO|C|9|0|Custo|Custo
FPG|07|FPG_CODDES|C|16|0|Equipamento|Equipamento
FPG|08|FPG_DESPES|C|40|0|Desc.Equip.|Desc.Equipamento
FPG|09|FPG_PRODUT|C|15|0|Produto|Produto
FPG|10|FPG_DESCRI|C|70|0|Desc.Produto|Desc.Produto
FPG|11|FPG_QUANT|N|12|2|Quantidade|Quantidade
FPG|12|FPG_VLUNIT|N|12|2|Vl.Unitario|Vl.Unitario
FPG|13|FPG_VALOR|N|12|2|Valor Total|Valor Total
FPG|14|FPG_TAXAP|N|5|2|Taxa Percent|Taxa Percent
FPG|15|FPG_TAXAV|N|12|2|Taxa Valor|Taxa Valor
FPG|16|FPG_VALTOT|N|12|2|Valor+Taxa|Valor+Taxa
FPG|17|FPG_COBRA|C|1|0|Cobrar?|Cobrar do Cliente?
FPG|18|FPG_DTENT|D|8|0|Dt.Entrada|Dt.Entrada
FPG|19|FPG_DTPAG|D|8|0|Dt.Pagto|Dt.Pagto
FPG|20|FPG_STATUS|C|1|0|Status|Status
FPG|21|FPG_OK|C|2|0|OK|OK
FPG|22|FPG_DOCORI|C|30|0|Docto Origem|Docto Origem
FPG|23|FPG_RECORI|N|10|0|Recno Origem|Recno Origem
FPG|24|FPG_COBRAT|C|1|0|Cobrar Taxa?|Cobrar Taxa de Intermedia
FPG|25|FPG_JUNTO|C|1|0|Junto?|Junto?
FPG|26|FPG_PVNUM|C|6|0|Pedido Venda|Pedido de Venda
FPG|27|FPG_PVITEM|C|2|0|Item PV|Item Pedido de Venda
FPG|28|FPG_NATURE|C|10|0|Natureza|Natureza p/ PV C.Extra
FPG|29|FPG_SEQ|C|6|0|Sequencia|Seq. lançamento
FPG|30|FPG_DESCC|C|40|0|Desc. CC|Descricao Centro de Custo
FPG|31|FPG_DESCNA|C|30|0|Desc.Nat.|Descricao Natureza
FPG|32|FPG_FATLOT|C|9|0|Fat.Lote|Faturamento off-line
FPG|33|FPG_TPOFF|C|1|0|Tp.Off Line|Tp.Fat. Off-line
FPG|34|FPG_CMTBF|N|9|0|Cont. MTBF|Contador MTBF
FPG|35|FPG_CATUAL|N|9|0|Cont. Atual|Contador Atual
FPG|36|FPG_CANT|N|9|0|Cont. Anter.|Contador Anterior
FPG|37|FPG_APURA|N|9|0|Cont. Apurad|Contador Apurado MTBF
FPG|38|FPG_NPERC|N|6|2|Percent. Apu|Percentual de Apuração
FPG|39|FPG_CUSORI|N|12|2|Custo Orig.|Custo Original
FPG|40|FPG_TIPCOB|C|1|0|Tip Cobrança|Tipo de Cobrança
--- ### FPH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPH|01|FPH_FILIAL|C|6|0|Filial|Filial do Sistema
FPH|02|FPH_SOT|C|22|0|Nr. Projeto|Nr. Projeto
FPH|03|FPH_OBRA|C|3|0|Cod.Obra|Cod.Obra
FPH|04|FPH_EMISSA|D|8|0|Dt. Emissao|Dt. Emissao
FPH|05|FPH_DEPDT|D|8|0|Dt.Depos.|Dt.Depos.
FPH|06|FPH_NRVALE|C|9|0|Nr. Vale|Nr. Vale
FPH|07|FPH_MOTORI|C|6|0|Motorista|Motorista
FPH|08|FPH_NOMMOT|C|40|0|Nome Motoris|Nome Motorista
FPH|09|FPH_MODFOR|C|1|0|Modo Fornec.|Modo Fornecimento
FPH|10|FPH_BANCO|C|1|0|Banco Debito|Banco Aonde Sera Debitado
FPH|11|FPH_TIPAD|C|1|0|Tipo Adiant.|Tipo Adiant.
FPH|12|FPH_NRBV|C|9|0|Nr.BV|Nr.BV
FPH|13|FPH_VIAGEM|C|6|0|Viagem|Viagem
FPH|14|FPH_FROTA|C|6|0|Frota|Frota
FPH|15|FPH_DIARIA|N|9|2|Diaria(-)|Vl Diaria
FPH|16|FPH_PERNOI|N|9|2|Pernoite (-)|Pernoite (-)
FPH|17|FPH_TRAVES|N|9|2|Travessia|Travessia
FPH|18|FPH_ABASTE|N|9|2|Abastecim(-)|Abastecimento
FPH|19|FPH_EXTRA|N|9|2|Extra(-)|Extra(-)
FPH|20|FPH_OUTROS|N|9|2|Outros (-)|Outros (-)
FPH|21|FPH_VALOR|N|12|2|Valor Adto.|Valor Adiantamento
FPH|22|FPH_SALDO|N|12|2|Saldo Aberto|Saldo Aberto
FPH|23|FPH_ACERTO|C|1|0|Acerto P.C.|Acerto  Prest.Contas
FPH|24|FPH_OBS|M|10|0|Observacao|Observacao
FPH|25|FPH_APROVA|L|1|0|Aprovado|Aprovado
FPH|26|FPH_USUPRO|C|6|0|Usuar.Aprov.|Usuar.Aprov.
FPH|27|FPH_DTAPRO|D|8|0|Dt.Aprovacao|Dt.Aprovacao
FPH|28|FPH_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPH|29|FPH_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FPI
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPI|01|FPI_FILIAL|C|6|0|Filial|Filial do Sistema
FPI|02|FPI_AS|C|27|0|Nro. AS|Nro. AS
FPI|03|FPI_NRBV|C|9|0|Nro.BV|Nro.BV
FPI|04|FPI_SOT|C|22|0|Nro.Projeto|Nro.Projeto
FPI|05|FPI_OBRA|C|3|0|Cod.Obra|Cod.Obra
FPI|06|FPI_MOTORI|C|6|0|Motorista|Motorista
FPI|07|FPI_NOMMOT|C|30|0|Nome Motoris|Nome Motoris
FPI|08|FPI_CLIENT|C|6|0|Cliente|Cliente
FPI|09|FPI_LOJA|C|2|0|Loja|Loja
FPI|10|FPI_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FPI|11|FPI_TIPOD|C|1|0|Tipo Docto|Tipo Docto
FPI|12|FPI_CODDOC|C|22|0|Cod.Docto|Cod.Docto
FPI|13|FPI_CCUSTO|C|9|0|Centro Custo|Centro Custo
FPI|14|FPI_NOMCCU|C|30|0|Nome C.Custo|Nome C.Custo
FPI|15|FPI_FROTA|C|16|0|Frota|Frota
FPI|16|FPI_DEPTO|C|1|0|Departamento|Departamento
FPI|17|FPI_DTABER|D|8|0|Dt Abertura|Dt Abertura
FPI|18|FPI_TIMEAB|C|4|0|Hra Abertura|Hra Abertura
FPI|19|FPI_DTFECH|D|8|0|Dt Fechamen.|Dt Fechamen.
FPI|20|FPI_TIMEFE|C|4|0|Hra Fechamen|Hra Fechamen
FPI|21|FPI_STATUS|C|1|0|Situacao|Situacao
FPI|22|FPI_APROV|C|1|0|Aprovado|Aprovado
FPI|23|FPI_TOTVLE|N|12|2|Total Vl Dev|Total Vl Dev
FPI|24|FPI_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPI|25|FPI_DEVOLU|N|14|2|Vlr Devoluca|Valor da Devolucao
FPI|26|FPI_RSDEVO|N|14|2|Dinheiro Dev|Dinheiro Devolvido
FPI|27|FPI_DESFOL|N|14|2|Vlr Desc Fol|Valor para Desconto Folha
FPI|28|FPI_PENDEN|N|14|2|Vlr Pendente|Valor Pendente Proximo BV
FPI|29|FPI_OBS|C|40|0|Observacoes|Observacoes
FPI|30|FPI_USUAPR|C|15|0|Aprovador|Aprovador
FPI|31|FPI_USUABR|C|15|0|Usuario Aber|Usuario Abertura
FPI|32|FPI_USUFEC|C|15|0|Usuario Fech|Usuario Fechamento
FPI|33|FPI_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPI|34|FPI_USERGA|C|17|0|Log de Alter|Log de Alteracao
--- ### FPJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPJ|01|FPJ_FILIAL|C|6|0|Filial|Filial do Sistema
FPJ|02|FPJ_CODFOR|C|1|0|Código Form.|Código Formulário
FPJ|03|FPJ_NOMFOR|C|55|0|Nome Form.|Nome Formulário
FPJ|04|FPJ_CODFAM|C|6|0|Cód Família|Código Família
FPJ|05|FPJ_DESFAM|C|40|0|Desc Família|Descrição Família
FPJ|06|FPJ_SEQ|C|4|0|Sequência|Sequência
FPJ|07|FPJ_NOMSEQ|C|40|0|Nome Seq|Nome Sequência
--- ### FPK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPK|01|FPK_FILIAL|C|6|0|Filial|Filial do Sistema
FPK|02|FPK_NRBV|C|9|0|Fat.Lot.|Lote do faturamento
FPK|03|FPK_SOT|C|22|0|Nro.Projeto|Nro.Projeto
FPK|04|FPK_ITEM|C|4|0|Item|Item
FPK|05|FPK_CODDES|C|10|0|Cod.Despesa|Cod.Despesa
FPK|06|FPK_CCUSTO|C|9|0|C. Custo|Centro de Custo
FPK|07|FPK_DATA|D|8|0|Solicitação|Data da solicitação
FPK|08|FPK_QUANT|N|12|3|Quantidade|Quantidade
FPK|09|FPK_VLUNIT|N|12|3|Vlr.Unitario|Vlr.Unitario
FPK|10|FPK_VLTOT|N|12|2|Vlr.Total|Vlr.Total
FPK|11|FPK_DESPES|C|30|0|Despesa|Despesa
FPK|12|FPK_OBRA|C|3|0|Cod.Obra|Cod.Obra
FPK|13|FPK_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPK|14|FPK_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPK|15|FPK_SOTATE|C|22|0|Projeto Ate|Numero do projeto final
FPK|16|FPK_HORA|C|8|0|Hora Solicit|Hora da solicitação
FPK|17|FPK_TIPO|C|1|0|Tipo Fatura|Tipo do Faturamento
FPK|18|FPK_DTFIM|D|8|0|Dt.Término|Término do processamento
FPK|19|FPK_HFIM|C|8|0|Hora Término|Hora fim processamento
FPK|20|FPK_STATUS|C|1|0|Status|Status do processamento
FPK|21|FPK_ERROS|M|10|0|Falha|Falhas na geração
FPK|22|FPK_LOGAS|M|10|0|Log.AS|Log. das AS
FPK|23|FPK_RESULT|M|10|0|Log Proces.|Log de processamento
--- ### FPL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPL|01|FPL_FILIAL|C|6|0|Filial|Filial do Sistema
FPL|02|FPL_FROTA|C|16|0|Frota|Frota
FPL|03|FPL_ITEM|C|3|0|Item|Item
FPL|04|FPL_TIPO|C|1|0|Tipo|Tipo
FPL|05|FPL_MATRIC|C|6|0|Matricula|Matricula
FPL|06|FPL_NOME|C|40|0|Nome|Nome
FPL|07|FPL_DTINI|D|8|0|Data Entrada|Data Entrada
FPL|08|FPL_DTFIM|D|8|0|Data Saida|Data Saida
FPL|09|FPL_AS|C|27|0|Nr. AS|Nr. AS
FPL|10|FPL_PROJET|C|22|0|Projeto|Projeto
FPL|11|FPL_OBRA|C|3|0|Obra|Obra
FPL|12|FPL_VIAGEM|C|6|0|Viagem|Viagem
FPL|13|FPL_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPL|14|FPL_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPL|15|FPL_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPL|16|FPL_FILMAT|C|6|0|Fil Matricul|Fil Matricul
FPL|17|FPL_FUNCAO|C|20|0|Funcao|Funcao do Funcionario
--- ### FPM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPM|01|FPM_FILIAL|C|6|0|Filial|Filial do Sistema
FPM|02|FPM_ANOMES|C|6|0|Ano/Mes|Ano/Mes
FPM|03|FPM_DTPROG|D|8|0|Dt Programa|Dt Programacao
FPM|04|FPM_DIASEM|C|10|0|Dia Semana|Dia Semana
FPM|05|FPM_FROTA|C|16|0|Frota|Frota
FPM|06|FPM_DESCRO|C|40|0|Desc. Frota|Descricao Frota
FPM|07|FPM_CODBEM|C|16|0|Equipamento|Equipamento
FPM|08|FPM_DESCRI|C|40|0|Descricao|Descricao
FPM|09|FPM_CODMOT|C|6|0|Motorista|Motorista
FPM|10|FPM_NOMMOT|C|40|0|Nome Motori.|Nome Motori.
FPM|11|FPM_CODOPE|C|6|0|Cod.Operador|Cod.Operador
FPM|12|FPM_NOMOPE|C|40|0|Nome Oper.|Nome Operador
FPM|13|FPM_STATUS|C|1|0|Status|Status
FPM|14|FPM_LOCALI|C|60|0|Localidade|Localidade
FPM|15|FPM_VIAGEM|C|6|0|Viagem/Serv.|Viagem/Servico
FPM|16|FPM_AS|C|27|0|Numero AS|Numero AS
FPM|17|FPM_PROJET|C|22|0|Projeto|Projeto
FPM|18|FPM_OBRA|C|3|0|Obra|Obra
FPM|19|FPM_OBS|M|10|0|Observacao|Observacao
FPM|20|FPM_PROP|C|25|0|Propr.Equip.|Proprietario Equipamento
FPM|21|FPM_LOCTRA|C|25|0|Local Trab.|Local Trabalho
FPM|22|FPM_TIPO|C|1|0|Tipo Program|Tipo Programacao
FPM|23|FPM_HORA|C|4|0|Hora|Hora
FPM|24|FPM_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPM|25|FPM_USERGI|C|17|0|Log de Inclu|Log de Inclu
FPM|26|FPM_USERGA|C|17|0|Log de Alter|Log de Alter
FPM|27|FPM_FROTA1|C|16|0|Carreta 1|Carreta 1
FPM|28|FPM_FROTA2|C|16|0|Carreta 2|Carreta 2
FPM|29|FPM_FROTA3|C|16|0|Carreta 3|Carreta 3
FPM|30|FPM_FROTA4|C|16|0|Carreta 4|Carreta 4
FPM|31|FPM_CODOSM|C|6|0|Ordem Servic|Ordem Servico de Manutenc
FPM|32|FPM_CODFAN|C|30|0|Cod Fantasia|Cod Fantasia
FPM|33|FPM_FILNF|C|6|0|Filial NF|Filial NF
FPM|34|FPM_NUMNF|C|9|0|Numero NF|Numero NF
FPM|35|FPM_SERNF|C|3|0|Serie NF|Serie NF
FPM|36|FPM_CLINF|C|6|0|Cliente NF|Cliente NF
FPM|37|FPM_LOJNF|C|2|0|Loja Cli. NF|Loja Cli. NF
FPM|38|FPM_CARRET|C|3|0|Carreta|Informa Carreta x Acessor
FPM|39|FPM_CODCLI|C|6|0|Cliente|Cliente
FPM|40|FPM_LOJA|C|2|0|Loja Cliente|Loja Cliente
FPM|41|FPM_QTACES|N|4|0|Qtd. Acessor|Qtd Acessorios Rotativos
FPM|42|FPM_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FPM|43|FPM_DESCAC|C|40|0|Descricao|Descricao
FPM|44|FPM_MAILF|D|8|0|Dt.Email Fis|Dt. Email Fiscal solic.NF
FPM|45|FPM_DTINI|D|8|0|Data Inicio|Data Inicio
FPM|46|FPM_DTFIM|D|8|0|Dt Final|Dt Final
FPM|47|FPM_MOT_OS|C|1|0|Motivo O.S.|Motivo O.S.
FPM|48|FPM_LOCAL|C|40|0|Local Trab.|Local Trabalho
FPM|49|FPM_ZLESC6|C|9|0|VINC.ZLE SC6|VINC.ZLE SC6
FPM|50|FPM_DEVACE|C|2|0|Dev.Acessor.|Devolucao do Acessorio
FPM|51|FPM_UNIFIL|C|6|0|Unid/Filial|Unid/Filial
FPM|52|FPM_COMPR|N|5|2|Compr. (MT)|Compr. (MT)
FPM|53|FPM_ZLESD3|C|6|0|Vinc.ZLE SD3|Vinc.ZLE SD3
FPM|54|FPM_LARGUR|N|4|2|Largura (MT)|Largura (MT)
FPM|55|FPM_STATU|C|1|0|Status|Status
FPM|56|FPM_ALTURA|N|4|2|Altura (MT)|Altura (MT)
FPM|57|FPM_PESO|N|8|2|Peso (KG)|Peso (KG)
FPM|58|FPM_HRINI|C|4|0|Hr Inicial|Hr Inicial
FPM|59|FPM_HRFIM|C|4|0|Hr Final|Hr Final
FPM|60|FPM_MINUTA|C|6|0|Minuta|Minuta
--- ### FPN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPN|01|FPN_FILIAL|C|6|0|Filial|Filial do Sistema
FPN|02|FPN_AS|C|27|0|Numero AS|Numero AS
FPN|03|FPN_PROJET|C|22|0|Projeto|Projeto
FPN|04|FPN_OBRA|C|3|0|Obra|Obra
FPN|05|FPN_VIAGEM|C|6|0|Viagem|Viagem
FPN|06|FPN_COD|C|6|0|Nro Medicao|Nro Medicao
FPN|07|FPN_DTINIC|D|8|0|Data Inicial|Data Inicial
FPN|08|FPN_DTFIM|D|8|0|Data Final|Data Final
FPN|09|FPN_MOBDTP|D|8|0|Mob Dt Previ|Mobilizacao Data Prevista
FPN|10|FPN_MOBDTR|D|8|0|Mob Dt Reali|Mobilizacao data Realizad
FPN|11|FPN_DESDTP|D|8|0|Desmobi Prev|Desmobi data Prev
FPN|12|FPN_DESDTR|D|8|0|Dt Desm Real|Dt Desm Real
FPN|13|FPN_DTSEGP|D|8|0|Dt Seg Previ|Dt Seg Prevista
FPN|14|FPN_DTSEGR|D|8|0|Dt Seg Reali|Dt Seg Realizada
FPN|15|FPN_DTMEDP|D|8|0|Dt Medi Prev|Dt Medi Prevista
FPN|16|FPN_DTMEDR|D|8|0|Dt Medi Real|Dt Medi Real
FPN|17|FPN_CLIENT|C|6|0|Cliente|Cliente
FPN|18|FPN_LOJA|C|2|0|Loja|Loja
FPN|19|FPN_NOMAGE|C|80|0|Nome Cliente|Nome Cliente
FPN|20|FPN_CONDPA|C|3|0|Cond Pag|Cond Pagamento
FPN|21|FPN_VALSER|N|12|2|Vlr Servico|Vlr Servico
FPN|22|FPN_VLAISS|N|12|2|Vlr. ISS|Vlr. ISS
FPN|23|FPN_VALTOT|N|12|2|Vlr. Total|Vlr. Total
FPN|24|FPN_SITUAC|C|1|0|Situacao|Situacao
FPN|25|FPN_NUMPV|C|6|0|Pedido Venda|Pedido Venda
FPN|26|FPN_VLDESC|N|14|2|Desconto|Desconto
FPN|27|FPN_VLACRE|N|14|2|Acrescimo|Acrescimo
FPN|28|FPN_VLARRE|N|4|2|Arredondamen|Arredondamento
FPN|29|FPN_OBS|M|10|0|Observacao|Observacao
FPN|30|FPN_OBSDES|M|10|0|Obs.Desconto|Obs.Desconto
FPN|31|FPN_OBSACR|M|10|0|Obs.Acrescim|Obs.Acrescimo
FPN|32|FPN_ENCEAS|C|1|0|Encerra AS|Encerra AS
FPN|33|FPN_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPN|34|FPN_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPN|35|FPN_NATUR|C|10|0|Natureza|Natureza
FPN|36|FPN_CC|C|9|0|Centro Lucro|Centro de Lucro
FPN|37|FPN_DTIMPT|D|8|0|Dt. Import|Data Importacao
FPN|38|FPN_TES|C|3|0|Tes|Tes
FPN|39|FPN_DTUPDT|D|8|0|Dt. Update|Dt. Update
FPN|40|FPN_NPVEXT|C|6|0|Num Pv Extra|Numero Pedido V. Extra
FPN|41|FPN_FILFAT|C|6|0|Filial Fat|Filial para Faturamento
FPN|42|FPN_VALPRV|N|12|2|Valor Prev|Valor Prev
FPN|43|FPN_TIPO|C|1|0|Tipo|Tipo
FPN|44|FPN_EXIBE|C|1|0|Exibe|Exibe
FPN|45|FPN_BLQDAT|D|8|0|Data de Blq|Data de Blq
FPN|46|FPN_FILPV|C|6|0|Filial do PV|Filial do PV
FPN|47|FPN_MINMES|N|3|0|Min. Hrs.Mes|Min. Hrs.Mes
FPN|48|FPN_MEDSEQ|C|3|0|Seq. Medicao|Seq. Medicao
FPN|49|FPN_VRPEDA|N|12|2|Vr.Pedagio|Vr.Pedagio
FPN|50|FPN_DESCOM|N|12|2|Desc.Comissa|Desconto comissao
FPN|51|FPN_NUMPV2|C|6|0|PV. C.Extras|PV. C.Extras
FPN|52|FPN_OSSAID|C|6|0|OS Saida|OS Saida
FPN|53|FPN_OSENTR|C|6|0|OS Entrada|OS Entrada
FPN|54|FPN_CUSTO|C|9|0|C Custo|Centro de Custo
FPN|55|FPN_CODVEN|C|6|0|Cod Vendedor|Cod Vendedor
FPN|56|FPN_NOMVEM|C|50|0|Nome Vendedo|Nome Vendedo
FPN|57|FPN_CONANT|N|9|0|Hor Anterior|Horimetro Anterior
FPN|58|FPN_POSCON|N|9|0|Horimetro|Horimetro Atual
FPN|59|FPN_VLRMOB|N|12|2|Vlr. Frete|Valor total do frete
FPN|60|FPN_VALSEG|N|12|2|Vlr. Seguro|Valor total do seguro
FPN|61|FPN_VLRHOR|N|12|2|Valor Horim.|Valor do Horimetro
FPN|62|FPN_DESEQP|C|40|0|Desc. Eqpto.|Descricao do equipamento
FPN|63|FPN_CODBEM|C|16|0|Cod. Bem|Codigo do Bem
FPN|64|FPN_NOMBEM|C|40|0|Nome Bem|Nome do Bem
FPN|65|FPN_PERIOD|C|6|0|Periodo|Periodo
FPN|66|FPN_XOS|C|6|0|OS|Ordem de Serviço
--- ### FPO
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPO|01|FPO_FILIAL|C|6|0|Filial|Filial do Sistema
FPO|02|FPO_FROTA|C|16|0|Frota|Frota
FPO|03|FPO_NRAS|C|27|0|Nr. AS|Nr. AS
FPO|04|FPO_CODCLI|C|6|0|Cliente|Cliente
FPO|05|FPO_LOJA|C|2|0|Loja Cliente|Loja Cliente
FPO|06|FPO_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FPO|07|FPO_CODBEM|C|16|0|Cod. Acesso|Cod. Acessorio
FPO|08|FPO_DESCAC|C|40|0|Descricao|Descricao
FPO|09|FPO_DTINI|D|8|0|Data Inicio|Data Inicio
FPO|10|FPO_DTFIM|D|8|0|Dt Final|Dt Final
FPO|11|FPO_PROJET|C|22|0|Projeto|Projeto
FPO|12|FPO_OBRA|C|3|0|Obra|Obra
FPO|13|FPO_VIAGEM|C|6|0|Servico|Servico
FPO|14|FPO_STATUS|C|1|0|Status|Status
FPO|15|FPO_LOCAL|C|40|0|Local Trab.|Local Trabalho
FPO|16|FPO_IMOBIL|C|16|0|Imobilizado|Imobilizado
FPO|17|FPO_UNIFIL|C|6|0|Unid/Filial|Unid/Filial
FPO|18|FPO_COMPR|N|5|2|Compr. (MT)|Compr. (MT)
FPO|19|FPO_LARGUR|N|4|2|Largura (MT)|Largura (MT)
FPO|20|FPO_ALTURA|N|4|2|Altura (MT)|Altura (MT)
FPO|21|FPO_PESO|N|8|2|Peso (KG)|Peso (KG)
FPO|22|FPO_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPO|23|FPO_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPO|24|FPO_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPO|25|FPO_CODFAN|C|30|0|Cod Fantasia|Cod Fantasia
FPO|26|FPO_FILNF|C|6|0|Filial NF|Filial NF
FPO|27|FPO_NUMNF|C|9|0|Numero NF|Numero NF
FPO|28|FPO_SERNF|C|3|0|Serie NF|Serie NF
FPO|29|FPO_CLINF|C|6|0|Cliente NF|Cliente NF
FPO|30|FPO_LOJNF|C|2|0|Loja Cli. NF|Loja Cli. NF
FPO|31|FPO_CARRET|C|3|0|Carreta|Informa Carreta x Acessor
FPO|32|FPO_QTACES|N|4|0|Qtd. Acessor|Qtd Acessorios Rotativos
FPO|33|FPO_REVISA|C|2|0|Revisao AS|Revisao AS
FPO|34|FPO_FINAL|C|1|0|Finalizado|Esta Finalizado?
FPO|35|FPO_MAILF|D|8|0|Dt.Email Fis|Dt. Email Fiscal solic.NF
FPO|36|FPO_OS|C|6|0|O.Servico|O.Servico
FPO|37|FPO_MOT_OS|C|1|0|Motivo O.S.|Motivo O.S.
FPO|38|FPO_ZLGSC6|C|9|0|VINC.ZLG SC6|VINC.ZLG SC6
FPO|39|FPO_DEVACE|C|2|0|Dev.Acessor.|Devolucao do Acessorio
FPO|40|FPO_ZLGSD3|C|6|0|Vinc.ZLG SD3|Vinculo ZLG SD3
FPO|41|FPO_HRINI|C|4|0|Hr Inicial|Hr Inicial
FPO|42|FPO_HRFIM|C|4|0|Hr Final|Hr Final
FPO|43|FPO_MINUTA|C|6|0|Minuta|Minuta
FPO|44|FPO_REGORI|C|1|0|Origem Reg.|Origem Registro
--- ### FPP
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPP|01|FPP_FILIAL|C|6|0|Filial|Filial do Sistema
FPP|02|FPP_COD|C|6|0|Nro Medicao|Nro Medicao
FPP|03|FPP_ITEM|C|3|0|Item|Item
FPP|04|FPP_OS|C|6|0|Ord.Serv.|Ordem Servico
FPP|05|FPP_DTMEDI|D|8|0|Dt.Medicao|Dt.Medicao
FPP|06|FPP_FROTA|C|16|0|Frota|Frota
FPP|07|FPP_DESCEQ|C|40|0|Descricao|Descricao do Equipamento
FPP|08|FPP_HORAI|C|4|0|Hora Inicial|Hora Inicial
FPP|09|FPP_HORAF|C|4|0|Hora Final|Hora Final
FPP|10|FPP_HRPARA|C|5|0|Hr. Parada|Hr. Parada
FPP|11|FPP_MOTIVO|C|1|0|Mot. Hr. Par|Motivo Hora Parada
FPP|12|FPP_HORTOT|N|7|2|Tot.Horas|Tot.Horas
FPP|13|FPP_QTDHR|N|7|2|Hrs Real|Hrs Real
FPP|14|FPP_BASE|C|1|0|Base Calculo|Base Calculo
FPP|15|FPP_VALHOR|N|12|2|Vlr Base Hr|Vlr Base Hora
FPP|16|FPP_VLTOHR|N|13|2|Vlr.Tot.Hrs|Vlr.Tot.Hrs
FPP|17|FPP_VLRMOB|N|12|2|Vlr. Mobiliz|Vlr. Mobilizacao
FPP|18|FPP_VLRDES|N|12|2|Vlr Desmobil|Vlr Desmobilizacao
FPP|19|FPP_TIPO|C|1|0|Tipo Seguro|Tipo Seguro
FPP|20|FPP_PERSEG|N|7|3|% Seguro|% Seguro
FPP|21|FPP_VLBSEG|N|16|2|Vlr.Base Seg|Vlr.Base Seguro
FPP|22|FPP_VALSEG|N|12|2|Vlr Seguro|Vlr Seguro
FPP|23|FPP_TPISS|C|1|0|Tipo ISS|Tipo ISS
FPP|24|FPP_PERISS|N|7|3|% ISS|% ISS
FPP|25|FPP_VALISS|N|12|2|Valor ISS|Valor ISS
FPP|26|FPP_PERMO|N|7|3|% Mao Obra|% Mao Obra
FPP|27|FPP_VLTOTM|N|12|2|Vlr Mao Obra|Vlr Mao Obra
FPP|28|FPP_VLRTOT|N|12|2|Vl Total Med|Vl Total Medicao
FPP|29|FPP_VALPRV|N|12|2|Valor Prev|Valor Prev
FPP|30|FPP_TRSPES|N|12|2|Trans./Peso|Trans./Peso
FPP|31|FPP_ANCORA|N|12|2|Ancoragem|Ancoragem
FPP|32|FPP_TELESC|N|12|2|Telescopagem|Telescopagem
FPP|33|FPP_MONTAG|N|12|2|Montagem|Montagem
FPP|34|FPP_DESMON|N|12|2|Desmontagem|Desmontagem
FPP|35|FPP_CODLCR|C|16|0|Cod Anterior|Cod Anterior
FPP|36|FPP_ACESSO|N|12|2|Vl.Acessor.|Vl.Acessor.
FPP|37|FPP_ITEMBA|C|2|0|IT. Petrobas|IT. Petrobas
FPP|38|FPP_LINHA|C|2|0|Lin Petrobra|Lin Petrobra
FPP|39|FPP_OMPJ|C|6|0|Om / PJ|Om / PJ
FPP|40|FPP_CCUSTO|C|9|0|Cent  Custo|Cent  Custo
FPP|41|FPP_CODGER|C|7|0|Cod. Gerdau|Cod. Gerdau
FPP|42|FPP_FRKM|N|14|4|Franquia KM|Franquia KM
FPP|43|FPP_KMINI|N|14|4|Km Inicial|Km Inicial
FPP|44|FPP_KMFIM|N|14|4|Km Final|Km Final
FPP|45|FPP_QTDKM|N|14|4|Total de Km|Total de Km
FPP|46|FPP_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPP|47|FPP_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPP|48|FPP_AUTORI|C|1|0|Autor Manut|Autoriza Manutencao Medic
FPP|49|FPP_USRLIB|C|15|0|Usuar Liber|Usuario Efetuou Liberacao
FPP|50|FPP_DATLIB|D|8|0|Data Liberac|Data Liberacao
FPP|51|FPP_VENDA|C|2|0|Origem Venda|Origem Venda
FPP|52|FPP_HORLIB|C|8|0|Hora Liberac|Hora Liberacao
FPP|53|FPP_MAQUIN|C|6|0|Filial MAQ|Filial MAQ
FPP|54|FPP_MAO|C|6|0|Filial M.O.|Filial M.O.
FPP|55|FPP_PERVND|N|6|2|% Orig Venda|% Orig Venda
FPP|56|FPP_PERMAQ|N|6|2|% Maquina|% Maquina
FPP|57|FPP_VLVND|N|12|2|Vl Orig Vend|Vl Orig Vend
FPP|58|FPP_VLMAQ|N|12|2|Vl Maquina|Vl Maquina
FPP|59|FPP_VLMAO|N|12|2|Vl M.O.|Vl M.O.
FPP|60|FPP_PERMAO|N|6|2|% M.O.|% M.O.
FPP|61|FPP_LIBER|C|1|0|STA. LIB. PV|STATUS LIBERA PV
FPP|62|FPP_OBRA|C|3|0|Obra|Obra
FPP|63|FPP_TURNO|C|3|0|Turno|Turno
FPP|64|FPP_VALTUR|N|12|2|Vlr. Turno|Vlr. Turno
FPP|65|FPP_DTLIBE|D|8|0|Dt. Liber. M|Data Liber. Medicao
FPP|66|FPP_TPMEDI|C|1|0|Tipo Medicao|Tipo Medicao
FPP|67|FPP_ALTER|C|1|0|Alterado|Alterado
FPP|68|FPP_ORDEM|C|3|0|Ordem|Ordem
FPP|69|FPP_MINDIA|N|3|0|Min. Hrs.Dia|Min. Hrs.Dia
FPP|70|FPP_EXIBE|C|1|0|Exibe|Exibe
FPP|71|FPP_DTDIGI|D|8|0|Dt Atualiz|Dt Atualiz
FPP|72|FPP_DATBLQ|D|8|0|Dt Bloqueio|Dt Bloqueio
FPP|73|FPP_DTAPUR|D|8|0|Dt Apuracao|Dt Apuracao
FPP|74|FPP_XTIPOH|C|1|0|Tipo de Hora|Tipo de Hora
FPP|75|FPP_MINUTA|C|6|0|Minuta|Minuta
FPP|76|FPP_PERHAD|C|3|0|Per. Hr. Adi|Percentual de hora Adc.
FPP|77|FPP_NFRET|C|9|0|NF Retorno|NF Retorno
FPP|78|FPP_DNFRET|D|8|0|Dt. NF. Ret|Data NF. Retorno
FPP|79|FPP_SERRET|C|3|0|Serie Ret NF|Serie Nota Fiscal Retorno
FPP|80|FPP_ITERET|C|4|0|Item NF Ret|Item Nota Fiscal Retorno
--- ### FPQ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPQ|01|FPQ_FILIAL|C|6|0|Filial|Filial
FPQ|02|FPQ_MAT|C|6|0|Matricula|Matricula
FPQ|03|FPQ_DATA|D|8|0|Data Locacao|Data Locacao
FPQ|04|FPQ_AGENDA|C|1|0|Agendamento|Agendamento
FPQ|05|FPQ_STATUS|C|6|0|Status|Status
FPQ|06|FPQ_VT|C|1|0|Vale Transp|Vale Transporte
FPQ|07|FPQ_AS|C|27|0|Nr. A.S.|Nr. A.S.
FPQ|08|FPQ_PROJET|C|22|0|Projeto|Projeto
FPQ|09|FPQ_OBRA|C|3|0|Obra|Obra
FPQ|10|FPQ_SERVIC|C|40|0|Servico|Servico
FPQ|11|FPQ_DESC|C|80|0|Nome Cliente|Nome Cliente
FPQ|12|FPQ_HORAS|N|5|2|Hrs|Horas de Integracao
FPQ|13|FPQ_OBS|C|40|0|Observacao|Observacao
FPQ|14|FPQ_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPQ|15|FPQ_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPQ|16|FPQ_FILAUX|C|6|0|FILAUX|FILAUX
FPQ|17|FPQ_FIND|C|30|0|FIND|FIND
FPQ|18|FPQ_HRINI|C|5|0|Hora Inicial|Hora Inicial
FPQ|19|FPQ_HRFIN|C|5|0|Hora Final|Hora Final
FPQ|20|FPQ_FILMAT|C|6|0|Fil Matricul|Fil Matricul
FPQ|21|FPQ_TIPINC|C|1|0|Tp. Inclusao|Tp. Inclusao
FPQ|22|FPQ_CONTRO|C|2|0|CONTROLE|CONTROLE
FPQ|23|FPQ_CRACHA|C|1|0|Cracha Ativo|Cracha Ativo ?
FPQ|24|FPQ_FUNCAO|C|1|0|Funcao|Funcao do Recurso
FPQ|25|FPQ_XHINIR|C|5|0|Hora inicial|Hora de inicio
FPQ|26|FPQ_XHFIMR|C|5|0|Hora final|Hora final
--- ### FPR
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPR|01|FPR_FILIAL|C|6|0|Filial|Filial do Sistema
FPR|02|FPR_CODUSR|C|6|0|Cod Usuario|Cod Usuario
FPR|03|FPR_NOME|C|15|0|Usuario|Nome do Usuario
FPR|04|FPR_TIPOSE|C|1|0|Tipo Servico|Tipo Servico
FPR|05|FPR_NIVEL|C|1|0|Nivel|Nivel
FPR|06|FPR_LIMITE|N|16|2|Limite Aprov|Limite Aprovacao Projeto
FPR|07|FPR_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FPR|08|FPR_USERGA|C|17|0|Log de Alter|Log de Alteracao
FPR|09|FPR_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FPR|10|FPR_TIPAPR|C|1|0|Tip.Aprov.|Tipo de aprovação
FPR|11|FPR_PRCDES|N|6|2|% Desconto|% Aprovação lib. Desconto
FPR|12|FPR_PRCMRG|N|6|2|% Margem|% Aprovação Margem
--- ### FPS
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPS|01|FPS_FILIAL|C|6|0|FILIAL|FILIAL
FPS|02|FPS_PROJET|C|22|0|Projeto|Projeto
FPS|03|FPS_OBRA|C|3|0|Obra|Obra
FPS|04|FPS_SEQGUI|C|3|0|Seq. Guind|Seq. Guind
FPS|05|FPS_ITEM|C|2|0|Item|Item
FPS|06|FPS_X5COD|C|16|0|Codigo|Frota
FPS|07|FPS_DESCRI|C|55|0|Descricao|Descricao
FPS|08|FPS_PRECUS|N|14|2|Prev. Custo|Previsao de custos
FPS|09|FPS_VALOR|N|16|2|Vl. Cobrar|Valor    a cobrar
FPS|10|FPS_VIAGEM|C|6|0|Viagem|Viagem
FPS|11|FPS_DTLIM|D|8|0|Data Limite|Data Limite
FPS|12|FPS_OBS|M|10|0|Observacao|Observacao
FPS|13|FPS_LCCORI|C|6|0|Cliente Ori|Cliente Ori
FPS|14|FPS_LCLORI|C|2|0|Loja Ori|Loja Ori
FPS|15|FPS_LOCCAR|C|80|0|Local Carreg|Local Carregamento
FPS|16|FPS_ENDORI|C|40|0|End. Origem|End. Origem
FPS|17|FPS_BRRORI|C|25|0|Bairro Orig.|Bairro Orig.
FPS|18|FPS_MUNORI|C|6|0|Cod. Mun Ori|Cod. Mun Ori
FPS|19|FPS_CIDORI|C|30|0|Descr. Munic|Descr. Munic
FPS|20|FPS_UFORI|C|2|0|UF. Origem|UF. Origem
FPS|21|FPS_CEPORI|C|8|0|CEP Origem|CEP Origem
FPS|22|FPS_LCCDES|C|6|0|Cliente Des|Cliente Des
FPS|23|FPS_LCLDES|C|2|0|Loja Des|Loja Des
FPS|24|FPS_LOCDES|C|80|0|Local Descar|Locar Descarregamento
FPS|25|FPS_ENDEST|C|40|0|End Destino|End Destino
FPS|26|FPS_BRRDES|C|25|0|Bairro Desti|Bairro Destino
FPS|27|FPS_MUNDES|C|6|0|Mun. Destino|Mun. Destino
FPS|28|FPS_CIDEST|C|30|0|Desc Mun Des|Descr. municipio Destino
FPS|29|FPS_UFDEST|C|2|0|UF Destino|UF Destino
FPS|30|FPS_CEPDES|C|8|0|CEP Destino|CEP Destino
FPS|31|FPS_VIAORI|C|6|0|Viagem Orig.|Viagem Orig.
FPS|32|FPS_ALTERR|C|10|0|Alter|Alteracao de Campos
FPS|33|FPS_CC|C|9|0|Centro Custo|Centro Custo
--- ### FPT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPT|01|FPT_FILIAL|C|6|0|Filial|Filial do Sistema
FPT|02|FPT_CODCLI|C|6|0|Cod.Cliente|Cod.Cliente
FPT|03|FPT_LOJCLI|C|2|0|Loja Cliente|Loja Cliente
FPT|04|FPT_COD|C|8|0|Cod.proc|Codigo do Processo
FPT|05|FPT_DESCRI|C|30|0|Descricao|Descricao
FPT|06|FPT_CLIENT|C|6|0|Cliente|Cliente
FPT|07|FPT_LOJ|C|2|0|Loja Cliente|Loja Cliente
FPT|08|FPT_ASO|C|1|0|ASO|Processo ASO
--- ### FPU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPU|01|FPU_FILIAL|C|6|0|Filial|Filial do Sistema
FPU|02|FPU_AS|C|27|0|Nr. AS|Nr. AS
FPU|03|FPU_OBRA|C|3|0|Obra|Obra
FPU|04|FPU_PROJ|C|22|0|Projeto|Projeto
FPU|05|FPU_MAT|C|6|0|Mat.Func|Mat.Func
FPU|06|FPU_NOME|C|40|0|Funcionario|Funcionario
FPU|07|FPU_DTINI|D|8|0|Dt.Ini Integ|Data Inicio da Integracao
FPU|08|FPU_DTFIN|D|8|0|Dt.Fim Integ|Dt de Conclusao da Integr
FPU|09|FPU_QTDDIA|N|3|0|Qtd Dias Int|Qtd Dias Int
FPU|10|FPU_DTLIM|D|8|0|Dt.Lim Integ|Dt.Lim Integ
FPU|11|FPU_VALID|N|3|0|Validade|Qtd meses validade
FPU|12|FPU_CRACHA|C|1|0|Cracha Ativo|Cracha Ativo
FPU|13|FPU_OBS|M|10|0|Observacao|Observacao
FPU|14|FPU_DESIST|C|1|0|Desistencia|Desistencia
FPU|15|FPU_CONTRO|C|2|0|Qt Matricula|Qt Matricula
FPU|16|FPU_CARGAH|N|6|2|C. Horaria|Carga Horaria
FPU|17|FPU_CODCLI|C|6|0|Cod. Cliente|Codigo do cliente
FPU|18|FPU_LOJCLI|C|2|0|Loja do Cli.|Loja do cliente
--- ### FPV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPV|01|FPV_FILIAL|C|6|0|Filial|Filial do Sistema
FPV|02|FPV_AS|C|27|0|AS|AS
FPV|03|FPV_OBRA|C|3|0|Obra|Obra
FPV|04|FPV_PROJ|C|22|0|Projeto|Projeto
FPV|05|FPV_CODPRO|C|8|0|Cod.Processo|Cod.Processo
FPV|06|FPV_DESCRI|C|20|0|Descricao|Descricao
FPV|07|FPV_MAT|C|6|0|Funcionario|Funcionario
FPV|08|FPV_DTPREV|D|8|0|Dt. Prevista|Dt. Prevista
FPV|09|FPV_DTREAL|D|8|0|Dt Realizada|Dt Realizada
FPV|10|FPV_OBS|M|10|0|Observacao|Observacao
FPV|11|FPV_CONTRO|C|2|0|Qt Matricula|Qt Matricula
FPV|12|FPV_DATVLD|D|8|0|Dt.Validade|Data da Validade
FPV|13|FPV_CARGAH|N|6|2|C. Horaria|Carga Horaria
--- ### FPW
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPW|01|FPW_FILIAL|C|6|0|Filial|Filial do Sistema
FPW|02|FPW_EQUIP|C|16|0|Equipamento|Equipamento
FPW|03|FPW_CODACE|C|16|0|Cod. Acessor|Cod. Acessor
FPW|04|FPW_DESCAC|C|40|0|Desc. Acesso|Descricao do Acessorio
FPW|05|FPW_QUANT|N|10|2|Qtd Padrao|Qtd Padrao
FPW|06|FPW_ACESSO|C|1|0|Tp. Acessori|Tp. Acessori
--- ### FPX
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPX|01|FPX_FILIAL|C|6|0|Filial|Filial do Sistema
FPX|02|FPX_CODCHE|C|10|0|Cód Che.List|Código Check-List
FPX|03|FPX_CODTOP|C|6|0|Cód Tópico|Código Tópico
FPX|04|FPX_NOMTOP|C|40|0|Nome Tópico|Nome Tópico
FPX|05|FPX_CODITE|C|6|0|Cód Item|Código Item
FPX|06|FPX_NOMITE|C|40|0|Nome Item|Nome Item
FPX|07|FPX_RESPOS|C|2|0|Resposta|Resposta
FPX|08|FPX_STATUS|C|20|0|Status|Status
FPX|09|FPX_DTINI|D|8|0|Data Iniciou|Data Iniciou
FPX|10|FPX_HRINI|C|5|0|Hora Iniciou|Hora Iniciou
FPX|11|FPX_DTFIM|D|8|0|Data Finaliz|Data Finalizou
FPX|12|FPX_HRFIM|C|5|0|Hora Finaliz|Hora Finalizou
FPX|13|FPX_CODCPF|C|11|0|Cód Ou CPF|Código do usuário Ou CPF
FPX|14|FPX_LOGPOR|C|6|0|Logado Por|Logado Por
FPX|15|FPX_NOMUSR|C|40|0|Nome Usuário|Nome Usuário
FPX|16|FPX_OBS|M|10|0|Observação|Observação
FPX|17|FPX_STAT2|C|20|0|Status novo|Status novo
--- ### FPY
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPY|01|FPY_FILIAL|C|6|0|Filial|Filial do Sistema
FPY|02|FPY_NF|C|9|0|Nota Fiscal|Nota Fiscal
FPY|03|FPY_SERIE|C|3|0|Serie|Serie
FPY|04|FPY_CLIENT|C|6|0|Cliente|Cliente
FPY|05|FPY_LOJA|C|2|0|Loja|Loja
FPY|06|FPY_DTNF|D|8|0|Data NF|Data NF
FPY|07|FPY_DTINI|D|8|0|Dt. Inicio|Data Inicio
FPY|08|FPY_DTFIM|D|8|0|Dt. Fim|Data Fim
FPY|09|FPY_HORA|C|5|0|Hora|Hora
FPY|10|FPY_EQUIPA|C|19|0|Frota|Frota
FPY|11|FPY_AS|C|27|0|Nro AS|Nro AS
FPY|12|FPY_STATUS|C|2|0|Status|Status
FPY|13|FPY_FILNF|C|6|0|Filial NF|Filial NF
FPY|14|FPY_DATA|D|8|0|Data|Data
FPY|15|FPY_NFDEVO|C|9|0|N.Romaneio|Número do Romaneio
FPY|16|FPY_SERDEV|C|3|0|Serie NF Dev|Serie NF de Devolucao
FPY|17|FPY_FORNEC|C|6|0|Fornecedor|Fornecedor
FPY|18|FPY_LOJFOR|C|2|0|Loja Fornec.|Loja do Fornecedor
FPY|19|FPY_DTDEVO|D|8|0|Data Dev.NF|Data de devolucao da NF
FPY|20|FPY_OBS|C|100|0|Observacao|Observacao
FPY|21|FPY_CLIFAT|C|6|0|Cliente Fat.|Cliente Faturamento
FPY|22|FPY_LOJFAT|C|2|0|Loja Fat.|Loja Faturamento
FPY|23|FPY_PROJET|C|22|0|Nro.Projeto|Numero do Projeto
FPY|24|FPY_CICFAT|C|7|0|Ciclo Fatur.|Ciclo Faturamento
FPY|25|FPY_PRVFAT|D|8|0|Prev.Fatura.|Data Prevista Faturamento
FPY|26|FPY_SITEQU|C|2|0|Sit. Equip.|Sit. Equip.
FPY|27|FPY_PEDVEN|C|6|0|Pedido Venda|Pedido Venda
FPY|28|FPY_TIPFAT|C|1|0|Tip.Faturam.|Tip.Faturamento
FPY|29|FPY_OBRA|C|3|0|Obra|Obra
FPY|30|FPY_ROMAN|C|9|0|Num Romaneio|Numero do Romaneio
--- ### FPZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FPZ|01|FPZ_FILIAL|C|6|0|Filial|Filial do Sistema
FPZ|02|FPZ_AS|C|27|0|Nro AS|Numero AS
FPZ|03|FPZ_PEDVEN|C|6|0|Ped. Venda|Pedido de Venda
FPZ|04|FPZ_DTPED|D|8|0|Dt. Pedido|Data Pedido de Venda
FPZ|05|FPZ_STATUS|C|2|0|Status|Status Pedido de Venda
FPZ|06|FPZ_DTINI|D|8|0|Data Inicio|Data Inicio
FPZ|07|FPZ_DTFIM|D|8|0|Data Fim|Data Fim
FPZ|08|FPZ_CICFAT|C|7|0|Ciclo Fatura|Ciclo do Faturamento
FPZ|09|FPZ_PRVFAT|D|8|0|Prev.Fatura|Previsao do Faturamento
FPZ|10|FPZ_SITFAT|C|1|0|Status Fat.|Status do Faturamento
FPZ|11|FPZ_PROJET|C|22|0|Projeto|Projeto
FPZ|12|FPZ_ITEM|C|2|0|Item|Item
FPZ|13|FPZ_ROMAN|C|9|0|Romaneio|Romaneio
FPZ|14|FPZ_FROTA|C|16|0|Frota|Frota
FPZ|15|FPZ_EXTRA|C|1|0|Custo Extra|Custo Extra
FPZ|16|FPZ_PERLOC|C|50|0|Periodo Loc.|Periodo de locação
FPZ|17|FPZ_CCUSTO|C|9|0|Centro Custo|Centro de custo
FPZ|18|FPZ_GERAEM|D|8|0|Gera em|Gera em
FPZ|19|FPZ_ITMFPZ|C|3|0|Item FPZ|Item FPZ
FPZ|20|FPZ_QUANT|N|9|2|Quantidade|Quantidade do Pedido
FPZ|21|FPZ_VALUNI|N|11|2|Valor Unit|Valor Unitario
FPZ|22|FPZ_TOTAL|N|12|2|Total|Valor Total do Item
FPZ|23|FPZ_PROD|C|15|0|Produto|Produto
FPZ|24|FPZ_VIAGEM|C|6|0|Viagem|Codigo da Viagem
FPZ|25|FPZ_DIAS|N|4|0|Numero Dias|Numero de Dias do Periodo
FPZ|26|FPZ_TES|C|3|0|TES|Codigo TES
FPZ|27|FPZ_CLVL|C|9|0|Classe Valor| Classe de Valor
FPZ|28|FPZ_OBRA|C|3|0|Obra|Obra
FPZ|29|FPZ_MEDICA|C|6|0|Medicao|Codigo da Medicao
--- ### FQ0
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ0|01|FQ0_FILIAL|C|6|0|Filial|Filial do Sistema
FQ0|02|FQ0_DTINI|D|8|0|Inicio|Data inicial do Periodo
FQ0|03|FQ0_DTFIM|D|8|0|Termino|Data Final do Periodo
FQ0|04|FQ0_STATUS|C|1|0|Status|Status  do periodo
--- ### FQ1
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ1|01|FQ1_FILIAL|C|6|0|Filial|Filial do Sistema
FQ1|02|FQ1_CODUSR|C|6|0|Cod Usuario|Cod Usuario
FQ1|03|FQ1_NOME|C|40|0|Usuario|Nome do Usuario
FQ1|04|FQ1_NOMPRO|C|10|0|Nome do Prog|Nome do Programa
FQ1|05|FQ1_CC|C|100|0|Codigo Liber|Codigo de Liberacao
FQ1|06|FQ1_CC_OLD|C|9|0|CC Old|Centro de Custo Antigo
FQ1|07|FQ1_PSWEAS|C|8|0|Psw APP Rent|Psw APP Rent
FQ1|08|FQ1_CPF|C|11|0|CPF|CPF
--- ### FQ2
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ2|01|FQ2_FILIAL|C|6|0|Filial|Filial do Sistema
FQ2|02|FQ2_NUM|C|9|0|Num Romaneio|Numero do Romaneio
FQ2|03|FQ2_PROJET|C|22|0|Ped.Comercia|Pedido Comercial
FQ2|04|FQ2_OBRA|C|3|0|Obra|Obra
FQ2|05|FQ2_ASF|C|27|0|ASF|ASF
FQ2|06|FQ2_VIAGEM|C|6|0|Viagem|Viagem
FQ2|07|FQ2_DATA|D|8|0|Data|Data
FQ2|08|FQ2_CLIENT|C|6|0|Cod. Cliente|Codigo do Cliente
FQ2|09|FQ2_LOJA|C|2|0|Loja Cliente|Loja do Cliente
FQ2|10|FQ2_NOMCLI|C|80|0|Nome Cliente|Nome do Cliente
FQ2|11|FQ2_TPROMA|C|1|0|Tipo Transp.|Tipo de Transporte
FQ2|12|FQ2_NFSER|C|41|0|NF/Serie|NF/Serie
FQ2|13|FQ2_PEDIDO|C|12|0|Pedido Com.|Pedido Comercial
FQ2|14|FQ2_TIPOVE|C|2|0|Tipo Veiculo|Tipo do Veiculo
FQ2|15|FQ2_PTIPVE|C|15|0|Desc.Veiculo|Descricao Veiculo
FQ2|16|FQ2_PLACA|C|7|0|Placa|Placa
FQ2|17|FQ2_PLACA2|C|7|0|Placa 2|Placa 2
FQ2|18|FQ2_MOTORI|C|30|0|Motorista|Nome do Motorista
FQ2|19|FQ2_CPFMOT|C|11|0|CPF/RG|CPF/RG
FQ2|20|FQ2_XCODTR|C|6|0|Transp.|Codigo Transportadora
FQ2|21|FQ2_TRANSP|C|40|0|Transportad.|Transportador
FQ2|22|FQ2_PTCOL|C|1|0|Pont. Coleta|Pont. Coleta
FQ2|23|FQ2_PDTCOL|D|8|0|Prazo Coleta|Prazo da Coleta
FQ2|24|FQ2_RDTCOL|D|8|0|Coleta Real|Coleta Real
FQ2|25|FQ2_AHRCOL|C|5|0|Atra.Col.Hr.|Atra.Col.Hr.
FQ2|26|FQ2_PTENT|C|1|0|Pont.Entrega|Pont.Entrega
FQ2|27|FQ2_PDTENT|D|8|0|Prazo Entreg|Prazo da Entrega
FQ2|28|FQ2_RDTENT|D|8|0|Entrega Real|Entrega Real
FQ2|29|FQ2_AHRENT|C|5|0|Atra.Ent.Hr.|Atra.Ent.Hr.
FQ2|30|FQ2_AVARIA|C|1|0|Avaria Trans|Avaria Trans
FQ2|31|FQ2_COMUNI|C|1|0|Prob.Comunic|Prob.Comunic
FQ2|32|FQ2_PCOLET|N|2|0|Ponto Coleta|Pontos de Coleta
FQ2|33|FQ2_PENTRE|N|2|0|Ponto Entreg|Pontos de Entrega
FQ2|34|FQ2_PAVARI|N|2|0|Ponto Avaria|Pontos Avaria
FQ2|35|FQ2_PCOMUN|N|2|0|Ponto Comun.|Pontos de Comunicacao
FQ2|36|FQ2_TOTAL|N|3|0|Pontos Total|Pontos Totais
FQ2|37|FQ2_DTFISC|D|8|0|Data Fiscal|Data Fiscal
FQ2|38|FQ2_TRANS|C|40|0|Desc. Transp|Descricao Transportadora
FQ2|39|FQ2_OBS|M|10|0|Obs. Gerais|Observacoes Gerais
FQ2|40|FQ2_CLIFAT|C|6|0|Cliente fat.|Cliente faturamento
FQ2|41|FQ2_LOJFAT|C|2|0|Lojacli.fat|Lojacli.fat
FQ2|42|FQ2_NOMFAT|C|40|0|Nomecli.fat|Nomecli.fat
FQ2|43|FQ2_MOTCOD|C|6|0|Cod.motorist|Codico do motorista
FQ2|44|FQ2_VOLUM1|N|5|0|Volume|Volume
FQ2|45|FQ2_TPFRET|C|1|0|Tipo frete|Tipo do frete utilizado
FQ2|46|FQ2_MENNOT|C|254|0|Mens p/ nota|Mensagem para nota fiscal
FQ2|47|FQ2_ESPECI|C|10|0|Especie|Especie de volume
--- ### FQ3
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ3|01|FQ3_FILIAL|C|6|0|Filial|Filial do Sistema
FQ3|02|FQ3_FAMILI|C|40|0|Familia|Nome da Familia do Bem
FQ3|03|FQ3_NOMBEM|C|40|0|Nome do Bem|Nome do Bem
FQ3|04|FQ3_FAMBEM|C|6|0|Familia Bem|Familia Bem
FQ3|05|FQ3_CODBEM|C|16|0|Cod. Bem|Codigo do Bem
FQ3|06|FQ3_NUM|C|9|0|Num Romaneio|Numero do Romaneio
FQ3|07|FQ3_ASF|C|27|0|ASF|ASF
FQ3|08|FQ3_TIPORE|C|2|0|Tp. Registro|Tipo do Registro
FQ3|09|FQ3_ITEM|C|4|0|Item|Item
FQ3|10|FQ3_PROJET|C|22|0|Ped.Comercia|Ped.Comercia
FQ3|11|FQ3_OBRA|C|3|0|Obra|Obra
FQ3|12|FQ3_AS|C|27|0|AS|AS
FQ3|13|FQ3_VIAGEM|C|6|0|Viagem|Viagem
FQ3|14|FQ3_HORBEM|N|9|0|Horimetro|Horimetro do Bem
FQ3|15|FQ3_QTDDIE|N|7|2|Quant.Diesel|Quantidade Diesel
FQ3|16|FQ3_KVA|N|6|2|KVA(Transf.)|KVA do Transformador.
FQ3|17|FQ3_AMP|N|6|2|AMP(QTA/QTM)|AMP do QTA ou QTM.
FQ3|18|FQ3_HORREA|N|9|0|Horim. Real|Horim. Real
FQ3|19|FQ3_DTFISC|C|8|0|Data Fiscal|Data de Entrega ao Fiscal
FQ3|20|FQ3_PROD|C|15|0|Produto|Produto
FQ3|21|FQ3_DESPRO|C|70|0|Desc Prod|Desc Prod
FQ3|22|FQ3_QTD|N|9|2|Quantidade|Quantidade
FQ3|23|FQ3_ORDEM|C|6|0|Numero OS|Numero OS
FQ3|24|FQ3_NFREM|C|9|0|NF Insumo|NF Insumo
FQ3|25|FQ3_SERREM|C|3|0|Serie Insumo|Serie Insumo
FQ3|26|FQ3_NFRET|C|9|0|Nf.Retorno|Nf.Retorno
FQ3|27|FQ3_SERRET|C|3|0|Serie Ret.|Serie Retorno
FQ3|28|FQ3_FORNE|C|6|0|Cod.Fornec.|Codigo do fornecedor
FQ3|29|FQ3_LOJF|C|2|0|Loja Fornec.|Loja do fornecedor
FQ3|30|FQ3_OBSCCM|C|20|0|Tip.obs.cont|Titulo obs.contribuinte
FQ3|31|FQ3_OBSCON|C|60|0|Obs.contribu|Observaçao contribuinte
FQ3|32|FQ3_OBSFCM|C|20|0|Tit.obs.fisc|Titulo obs. fisco
FQ3|33|FQ3_OBSFIS|C|60|0|Obs.fisco|Observaçao do fisco
--- ### FQ4
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ4|01|FQ4_FILIAL|C|6|0|Filial|Filial do Sistema
FQ4|02|FQ4_CODBEM|C|16|0|Cod. Bem|Codigo do bem
FQ4|03|FQ4_NOME|C|40|0|Desc. Bem|Descricao do Bem
FQ4|04|FQ4_STATUS|C|2|0|Status|Status do bem
FQ4|05|FQ4_CODFAM|C|6|0|Cod. Familia|Codigo Familia Bem
FQ4|06|FQ4_DESTAT|C|30|0|Desc. Status|Descricao status do bem
FQ4|07|FQ4_TIPMOD|C|10|0|Tipo Modelo|Tipo Modelo do bem
FQ4|08|FQ4_FABRIC|C|6|0|Fabricante|Fabricante  do Bem
FQ4|09|FQ4_SUBLOC|C|1|0|Sublocado?|Bem Sublocado?
FQ4|10|FQ4_POSCON|N|9|0|Horimetro|Horimetro
FQ4|11|FQ4_CENTRA|C|6|0|C. Trabalho|Centro de Trabalho
FQ4|12|FQ4_NOMTRA|C|20|0|Nome Centrab|Nome Centro de trabalho
FQ4|13|FQ4_DOCUME|C|9|0|Documento|Documento
FQ4|14|FQ4_SERIE|C|3|0|Serie|Serie
FQ4|15|FQ4_OS|C|6|0|Numero OS|Numero OS
FQ4|16|FQ4_SERVIC|C|6|0|Servico|Servico
FQ4|17|FQ4_TPSERV|C|30|0|Tp. Servico|Tipo do Servico
FQ4|18|FQ4_PRELIB|C|8|0|Prev. Libera|Previsao de liberacao
FQ4|19|FQ4_PROJET|C|22|0|Projeto|Projeto
FQ4|20|FQ4_OBRA|C|3|0|Obra|Obra do Pedido Comercial
FQ4|21|FQ4_AS|C|27|0|AS Atual|AS Atual do Bem
FQ4|22|FQ4_CODCLI|C|6|0|Cli Obra|Cliente da Obra
FQ4|23|FQ4_LOJCLI|C|2|0|Loja Cli.|Loja Cliente
FQ4|24|FQ4_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FQ4|25|FQ4_NFREM|C|9|0|NF Remessa|NF Remessa
FQ4|26|FQ4_SERREM|C|3|0|Serie Remess|Serie da NF de Remessa
FQ4|27|FQ4_CODMUN|C|5|0|Cod. Municip|Codigo Municipio
FQ4|28|FQ4_MUNIC|C|60|0|Municipio|Municipio
FQ4|29|FQ4_EST|C|2|0|Estado|Estado
FQ4|30|FQ4_DTINI|D|8|0|Dt Inicio|Data de Inicio
FQ4|31|FQ4_DTFIM|D|8|0|Dt Fim|Data final da Locacao
FQ4|32|FQ4_PREDES|D|8|0|Prev Retirad|Previsao de Retirada
FQ4|33|FQ4_LOG|C|254|0|Log registro|Log registro
FQ4|34|FQ4_STSOLD|C|2|0|Status Ant.|Status Anterior
FQ4|35|FQ4_SEQ|C|6|0|Sequencia|Sequencia do lancamento
--- ### FQ5
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ5|01|FQ5_FILIAL|C|6|0|Filial|Filial do Sistema
FQ5|02|FQ5_FILORI|C|6|0|Fil.Origem|Filial de Origem
FQ5|03|FQ5_VIAGEM|C|6|0|Viagem|Numero da Viagem
FQ5|04|FQ5_SOT|C|22|0|Projeto|Projeto
FQ5|05|FQ5_NOMCLI|C|40|0|Cliente|Cliente
FQ5|06|FQ5_GUINDA|C|16|0|Locacao|Locacao/Guindaste
FQ5|07|FQ5_DATGER|D|8|0|Data Geracao|Data da Geracao
FQ5|08|FQ5_XPROD|C|15|0|Cod.Prod.|Código do Produto
FQ5|09|FQ5_XQTD|N|3|0|Qtd|Quantidade
FQ5|10|FQ5_HORGER|C|4|0|Hora Geracao|Hora Geracao
FQ5|11|FQ5_AS|C|27|0|Nr. A.S.|Nr. A.S.
FQ5|12|FQ5_OBRA|C|3|0|Obra|Obra
FQ5|13|FQ5_DESTIN|C|40|0|Destino|Destino
FQ5|14|FQ5_TIPVIA|C|1|0|Tipo Viagem|Tipo Viagem
FQ5|15|FQ5_ROTA|C|6|0|Rota|Rota
FQ5|16|FQ5_SERTMS|C|1|0|Serv.Transp.|Servico de Transporte
FQ5|17|FQ5_TIPTRA|C|1|0|Tipo Transp.|Tipo Transporte
FQ5|18|FQ5_DATFEC|D|8|0|Data Fechto.|Data de Fechamento
FQ5|19|FQ5_HORFEC|C|4|0|Hora Fechto.|Hora Fechto.
FQ5|20|FQ5_DATENC|D|8|0|Data Encerra|Data de Encerramento
FQ5|21|FQ5_HORENC|C|4|0|Hora Encerra|Hora de Encerramento
FQ5|22|FQ5_QTDPER|N|3|0|Qtd.Pernoite|Qtd de Pernoite a pagar
FQ5|23|FQ5_STATUS|C|1|0|Status|Status da Viagem
FQ5|24|FQ5_IDENT|C|9|0|Id.Vge/Carga|Id.Vge/Carga
FQ5|25|FQ5_DATINI|D|8|0|Data Inicio|Data Inicio Planejamento
FQ5|26|FQ5_HORINI|C|4|0|Hora Inicio| Hora Inicio Planejamento
FQ5|27|FQ5_DATFIM|D|8|0|Data Fim|Data Fim Planejamento
FQ5|28|FQ5_HORFIM|C|4|0|Hora Fim|Hora Fim Planejamento
FQ5|29|FQ5_TPAS|C|1|0|Tipo AS|Tipo AS
FQ5|30|FQ5_ORIGEM|C|40|0|Origem|Origem
FQ5|31|FQ5_EQUIP|C|16|0|Equipamento|Equipamento
FQ5|32|FQ5_CONTRA|C|15|0|Contrato|Contrato
FQ5|33|FQ5_ORCA|C|6|0|Orcamento|Orcamento
FQ5|34|FQ5_VLRINF|N|15|2|VLR FRETE|VLR FRETE
FQ5|35|FQ5_VALICM|N|10|2|Perc. ICMS|Perc. ICMS
FQ5|36|FQ5_PERICM|N|10|2|Perc. ICMS|Perc. ICMS
FQ5|37|FQ5_BASICM|N|12|2|Base ICMS|Base ICMS
FQ5|38|FQ5_VALADV|N|15|2|Valor Adv|Valor Adv
FQ5|39|FQ5_PERADV|N|12|4|Perc. AdVal.|Perc. AdVal.
FQ5|40|FQ5_ZLFTIP|C|1|0|Situacao Med|Situacao da Medicao
FQ5|41|FQ5_BASADV|N|12|2|Base ADV|Base ADV
FQ5|42|FQ5_NTCLI|C|9|0|Nota Fiscal|Nota Fiscal x CTRB
FQ5|43|FQ5_VALCAR|N|12|2|Valor Carga|Valor Carga CTRB
FQ5|44|FQ5_TOTFRE|N|15|2|Total frete|Total frete
FQ5|45|FQ5_CONHEC|C|6|0|Conhecimento|Conhecimento CTRB
FQ5|46|FQ5_IMPCTB|C|1|0|Adto ou Sld|Foi Gerado Adto ou Sld
FQ5|47|FQ5_TES|C|3|0|TES|TES
FQ5|48|FQ5_SEQCAR|C|3|0|SEQ CAR|SEQ CAR
FQ5|49|FQ5_ENCERR|C|1|0|AS Encerrada|AS Encerrada
FQ5|50|FQ5_CONDPG|C|3|0|Cond.Pagto|Cond.Pagto
FQ5|51|FQ5_SEQVIA|C|3|0|Seq. Viagem|Seq. Viagem
FQ5|52|FQ5_DCOND|C|100|0|Desc Cond PG|Desc Cond PG
FQ5|53|FQ5_DESICM|L|1|0|Destaca ICMS|Destaca ICMS
FQ5|54|FQ5_CFOP|C|5|0|CFOP|CFOP
FQ5|55|FQ5_PAGO|C|1|0|Frete Pago|Frete Pago
FQ5|56|FQ5_PLACAV|C|8|0|Placa Cavalo|Placa Cavalo
FQ5|57|FQ5_PLACAR|C|8|0|Plac Carreta|Plac Carreta
FQ5|58|FQ5_OBSCTR|M|10|0|Obs. CTRC|Obs. CTRC
FQ5|59|FQ5_MOTORI|C|40|0|Nm Motorista|Nm Motorista
FQ5|60|FQ5_NUMCTR|C|9|0|Num.CTR|Num.CTR
FQ5|61|FQ5_OBSCTB|M|10|0|Obs CTRB|Obs CTRB
FQ5|62|FQ5_OBSCOM|M|10|0|Obs Complem|Obs Complem
FQ5|63|FQ5_NUMSLD|C|9|0|Nr. CTRB SLD|Nr. CTRB SLD
FQ5|64|FQ5_SERCTR|C|3|0|Serie CTR|Serie CTR
FQ5|65|FQ5_NUMPV|C|6|0|Num.PV|Num.PV
FQ5|66|FQ5_NUMCTC|C|9|0|N.Vale Frete|N.Vale Frete
FQ5|67|FQ5_CTRORI|C|6|0|CTRC Origem|CTRC Complementar Origem
FQ5|68|FQ5_CTRDES|C|6|0|CTRC Destino|CTRC Complementar Destino
FQ5|69|FQ5_CCC|C|9|0|Centro Custo|Centro Custo
FQ5|70|FQ5_TIPAMA|C|6|0|Tip. Ama|Tip. Ama
FQ5|71|FQ5_OBSERV|C|40|0|Obs. Seguro|Obs. Seguro
FQ5|72|FQ5_DTPROG|D|8|0|Dt. Programa|Dt. Programa
FQ5|73|FQ5_TPSERV|C|1|0|Tipo Servico|Tipo Servico
FQ5|74|FQ5_DTINI|D|8|0|Data inicio|Data inicio
FQ5|75|FQ5_DTFIM|D|8|0|Data Final|Data Final
FQ5|76|FQ5_HRINI|C|4|0|Hora inicial|Hora inicial
FQ5|77|FQ5_HRFIM|C|4|0|Hora Final|Hora Final
FQ5|78|FQ5_PACLIS|C|3|0|No Carreta|No Carreta
FQ5|79|FQ5_ACEITE|D|8|0|DT ACEITE|DATA DO ACEITE
FQ5|80|FQ5_FRTINT|C|1|0|Frota Intern|Frota Interna
FQ5|81|FQ5_CODCLI|C|6|0|Cod.Cliente|Cod.Cliente
FQ5|82|FQ5_LOJA|C|2|0|Loja|Loja
FQ5|83|FQ5_XROMAN|C|9|0|Cod.Romaneio|Cod.Romaneio
FQ5|84|FQ5_CODORI|C|6|0|Cod.Cidade|Cod.Cidade de Origem
FQ5|85|FQ5_CODDES|C|6|0|Cod. Cidade|Cod. Cidade de Destino
FQ5|86|FQ5_AFRMM|N|9|2|AFRMM|AFRMM
FQ5|87|FQ5_IRIN|C|10|0|Irin|Irin
FQ5|88|FQ5_DIRNAV|C|1|0|Tp.Navegacao|Tipo da Navegacao
FQ5|89|FQ5_NAVEG|C|1|0|Tp.Navegacao|Tipo da Navegacao
FQ5|90|FQ5_TES2|C|3|0|TES AFRMM|TES AFRMM
FQ5|91|FQ5_CFOP2|C|5|0|CFOP AFRMM|CFOP AFRMM
FQ5|92|FQ5_JUNTO|C|3|0|Junto Transp|Junto Transporte
FQ5|93|FQ5_TPCTRC|C|1|0|Tipo Ctrc|Tipo Ctrc
FQ5|94|FQ5_VRESTA|N|12|2|Vr.Estadia|Valor Estadia
FQ5|95|FQ5_CARDES|N|12|2|Carga/Descar|Carga/Descarga
FQ5|96|FQ5_VRESCO|N|12|2|Vr.Escolta|Valor Escolta
FQ5|97|FQ5_VRPEDA|N|12|2|Vr. Pedagio|Vr. Pedagio
FQ5|98|FQ5_VRSCOM|N|12|2|Vr s/ comiss|Outros vlrs s/ comissao
FQ5|99|FQ5_VRCCOM|N|12|2|Vr c/ comiss|Outros vlrs c/ comissao
FQ5|9A|FQ5_DESCOM|N|12|2|Desc.Comissa|Desconto Comissao
FQ5|9B|FQ5_XFRETE|N|12|2|Vlr.Containe|Valor do Container
FQ5|9C|FQ5_VRCONT|N|12|2|Vlr.Containe|Valor do Container
FQ5|9D|FQ5_NSC|C|6|0|Numero da SC|Numero da Solic.de Compra
FQ5|9E|FQ5_ISC|C|4|0|Item da SC|Item da solicitacao
FQ5|9F|FQ5_IDUAA3|C|20|0|ID Unico GS|ID Unico Serviços
FQ5|9G|FQ5_NOMORI|C|80|0|Nome Obra|Nome da Obra
FQ5|9H|FQ5_DEMAND|C|6|0|Demamda|Codigo da Demanda
FQ5|9I|FQ5_QTD2|N|12|2|Qtd 2 Unid|Quantidade Segunda Unidad
FQ5|9J|FQ5_STDEMA|C|1|0|Status Demad|Status da demanda
FQ5|9K|FQ5_PESLIQ|N|15|4|Peso Liquido|Peso Liquido Total
FQ5|9L|FQ5_PESBRU|N|15|4|Peso Bruto|Peso Bruto da A.S.
FQ5|9M|FQ5_M3|N|15|4|m3|Volume em m3
--- ### FQ6
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ6|01|FQ6_FILIAL|C|6|0|Filial|Filial do Sistema
FQ6|02|FQ6_CODIGO|C|6|0|Código|Código do Item
FQ6|03|FQ6_DESC|C|40|0|Descrição|Descriçao do Item
--- ### FQ7
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ7|01|FQ7_FILIAL|C|6|0|FILIAL|FILIAL
FQ7|02|FQ7_PROJET|C|22|0|Projeto|Projeto
FQ7|03|FQ7_OBRA|C|3|0|Obra|Obra
FQ7|04|FQ7_SEQGUI|C|3|0|Locacao|Locacao
FQ7|05|FQ7_ITEM|C|2|0|Item|Item
FQ7|06|FQ7_X5COD|C|2|0|Codigo|Codigo
FQ7|07|FQ7_DESCRI|C|55|0|Descricao|Descricao
FQ7|08|FQ7_CC|C|9|0|Centro Custo|Centro Custo
FQ7|09|FQ7_PRECUS|N|14|2|Prev. Custo|Previsao de custos
FQ7|10|FQ7_VIAGEM|C|6|0|Viagem|Viagem
FQ7|11|FQ7_DTLIM|D|8|0|Data Limite|Data Limite
FQ7|12|FQ7_OBS|M|10|0|Observacao|Observacao
FQ7|13|FQ7_LCCORI|C|6|0|Cliente Ori|Cliente Ori
FQ7|14|FQ7_LCLORI|C|2|0|Loja Ori|Loja Ori
FQ7|15|FQ7_LOCCAR|C|80|0|Local Carreg|Local Carregamento
FQ7|16|FQ7_ENDORI|C|40|0|End. Origem|End. Origem
FQ7|17|FQ7_BRRORI|C|25|0|Bairro Orig.|Bairro Orig.
FQ7|18|FQ7_MUNORI|C|6|0|Cod. Mun Ori|Cod. Mun Ori
FQ7|19|FQ7_CIDORI|C|30|0|Descr. Munic|Descr. Munic
FQ7|20|FQ7_UFORI|C|2|0|UF. Origem|UF. Origem
FQ7|21|FQ7_CEPORI|C|8|0|CEP Origem|CEP Origem
FQ7|22|FQ7_LCCDES|C|6|0|Cliente Des|Cliente Des
FQ7|23|FQ7_LCLDES|C|2|0|Local Descar|Locar Descarregamento
FQ7|24|FQ7_LOCDES|C|80|0|Local Descar|Locar Descarregamento
FQ7|25|FQ7_ENDEST|C|40|0|End Destino|End Destino
FQ7|26|FQ7_BRRDES|C|25|0|Bairro Desti|Bairro Destino
FQ7|27|FQ7_MUNDES|C|6|0|Mun. Destino|Mun. Destino
FQ7|28|FQ7_CIDEST|C|30|0|Desc Mun Des|Descr. municipio Destino
FQ7|29|FQ7_UFDEST|C|2|0|UF Destino|UF Destino
FQ7|30|FQ7_CEPDES|C|8|0|CEP Destino|CEP Destino
FQ7|31|FQ7_VIAORI|C|6|0|Viagem Orig.|Viagem Orig.
FQ7|32|FQ7_VALOR|N|12|2|Vl. Cobrar|Valor a cobrar
FQ7|33|FQ7_ALTERR|C|10|0|Alter|Alteracao de Campos
FQ7|34|FQ7_TPROMA|C|1|0|Tipo Frete|Tipo de Frete
FQ7|35|FQ7_TPOPE|C|6|0|Tp Operacao|Tipo Operacao
FQ7|36|FQ7_KM|N|9|0|Distancia KM|Distancia KM
FQ7|37|FQ7_CLASS|C|22|0|Classificaca|Classificacao
FQ7|38|FQ7_NOMCLA|C|6|0|Nomeclatura|Nomeclatura
FQ7|39|FQ7_ITTPFR|C|2|0|Tp. Frete|Tipo do Frete
FQ7|40|FQ7_NFRET|C|9|0|NF Retorno|Nota de retorno
FQ7|41|FQ7_SERRET|C|3|0|Ser.Retorno|Ser.Retorno
FQ7|42|FQ7_FORNE|C|6|0|Cod.Fornec.|Codigo do fornecedor
FQ7|43|FQ7_LOJF|C|2|0|Loja Fornec.|Loja do fornecedor
--- ### FQ8
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ8|01|FQ8_FILIAL|C|6|0|Filial|Filial do Sistema
FQ8|02|FQ8_PROJET|C|22|0|Nro.Projeto|Nro.Projeto
FQ8|03|FQ8_OBRA|C|3|0|Obra|Obra
FQ8|04|FQ8_SEQGUI|C|3|0|Seq.Guind.|Seq.Guind.
FQ8|05|FQ8_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FQ8|06|FQ8_VALLSR|N|14|2|LSR Ida|LSR Ida
FQ8|07|FQ8_VALTUV|N|14|2|TUV Ida|TUV Ida
FQ8|08|FQ8_VALTUR|N|14|2|TUR Ida|TUR Ida
FQ8|09|FQ8_VALTAP|N|14|2|TAP Ida|TAP Ida
FQ8|10|FQ8_VALESC|N|14|2|Escolta Ida|Escolta Ida
FQ8|11|FQ8_VALPRF|N|14|2|PRF Ida|PRF Ida
FQ8|12|FQ8_VALPRE|N|14|2|PRE Ida|PRE Ida
FQ8|13|FQ8_VALINV|N|14|2|Inversao Ida|Inversao Ida
FQ8|14|FQ8_VALADI|N|14|2|Adicional 1|Adicional Ida
FQ8|15|FQ8_AQUISI|N|14|2|Aquisicao|Aquisicao
FQ8|16|FQ8_PERRSD|N|14|2|% Residual|% Residual
FQ8|17|FQ8_VALRSD|N|14|2|Residual|Residual
FQ8|18|FQ8_DISPVE|N|14|2|Dispon.Veic.|Dispon.Veic.
FQ8|19|FQ8_VIDAEF|N|14|2|Vida Ut.Efet|Vida Ut.Efet
FQ8|20|FQ8_JUROSM|N|14|2|Juros Mes|Juros Mes
FQ8|21|FQ8_SEGURP|N|14|2|% Seguro|% Seguro
FQ8|22|FQ8_LICENP|N|14|2|Licenciam.|Licenciam.
FQ8|23|FQ8_LAVAGE|N|14|2|Custo Lavag.|Custo Lavag.
FQ8|24|FQ8_FREQLA|N|14|2|Freq.Lavagem|Freq.Lavagem
FQ8|25|FQ8_COMBUS|N|14|2|Combustivel|Combustivel
FQ8|26|FQ8_LUBRIF|N|14|2|Custo Lubr.|Custo Lubr.
FQ8|27|FQ8_INTLUB|N|14|2|Interv.Lubr.|Interv.Lubr.
FQ8|28|FQ8_QTDPNE|N|14|2|Pneus|Pneus
FQ8|29|FQ8_PREPNE|N|14|2|Preco Pneu|Preco Pneu
FQ8|30|FQ8_VIDAPN|N|14|2|Vida Ut.Pneu|Vida Ut.Pneu
FQ8|31|FQ8_CONSER|N|14|2|Cons.Peca|Cons.Peca
FQ8|32|FQ8_VALCOM|N|14|2|Combustivel|Combustivel
FQ8|33|FQ8_VALPNE|N|14|2|Pneus|Pneus
FQ8|34|FQ8_VALLUB|N|14|2|Lubrificacao|Lubrificacao
FQ8|35|FQ8_VALLAV|N|14|2|Lavagem|Lavagem
FQ8|36|FQ8_REMCAP|N|14|2|Remu.Capital|Remu.Capital
FQ8|37|FQ8_PERRES|N|14|2|% Reserva|% Reserva
FQ8|38|FQ8_VALRES|N|14|2|Reserva|Reserva
FQ8|39|FQ8_CASCO|N|14|2| Seguro Casc|Seguro Casco
FQ8|40|FQ8_LICENC|N|14|2|Licenciam.|Licenciam.
FQ8|41|FQ8_SEGURO|N|14|2|Seguro Obrig|Seguro Obrig
FQ8|42|FQ8_QTDCOM|N|9|2|Cons.Combust|Cons.Combust
FQ8|43|FQ8_VALTRA|N|14|2|Travessia|Travessia
FQ8|44|FQ8_VALCON|N|14|2|Concession.1|Concession.Ida
FQ8|45|FQ8_VALPED|N|14|2|Pedagios Ida|Pedagios Ida
FQ8|46|FQ8_PERISS|N|6|2|% ISS|% ISS
FQ8|47|FQ8_PERPIS|N|6|2|% PIS/COFINS|% PIS/COFINS
FQ8|48|FQ8_PERADM|N|6|2|% Admin|% Admin
FQ8|49|FQ8_PERLUC|N|6|2|% LUCRO|% LUCRO
FQ8|50|FQ8_PERSEG|N|6|2|% SEGURO|% SEGURO
FQ8|51|FQ8_PERJUR|N|6|2|% JUROS|% JUROS
FQ8|52|FQ8_PERCPM|N|6|2|% CPMF|% CPMF
FQ8|53|FQ8_PERCSL|N|6|2|% CSLL|% CSLL
FQ8|54|FQ8_PERIRR|N|6|2|% IRRF|% IRRF
FQ8|55|FQ8_PERTOT|N|6|2|% BDI|% BDI
FQ8|56|FQ8_VALISS|N|14|2|ISS|ISS
FQ8|57|FQ8_VALPIS|N|14|2|PIS/COFINS|PIS/COFINS
FQ8|58|FQ8_VALADM|N|14|2|Administr.|Administr.
FQ8|59|FQ8_VALLUC|N|14|2|Lucro|Lucro
FQ8|60|FQ8_VALSEG|N|14|2|Seguro|Seguro
FQ8|61|FQ8_VALJUR|N|14|2|Juros|Juros
FQ8|62|FQ8_VALCPM|N|14|2|CPMF|CPMF
FQ8|63|FQ8_VALCSL|N|14|2|CSLL|CSLL
FQ8|64|FQ8_VALIRR|N|14|2|IRRF|IRRF
FQ8|65|FQ8_VALTOT|N|14|2|Total BDI|Total BDI
FQ8|66|FQ8_VIDAUT|N|5|0|Vida Util|Vida Util
FQ8|67|FQ8_VALIPT|N|12|2|Laudo IPT 1|Laudo IPT Ida
FQ8|68|FQ8_VALACO|N|12|2|Acomp.Tecn.1|Acomp.Tecn.Ida
FQ8|69|FQ8_VALSEM|N|12|2|Semaforica 1|Semaforica Ida
FQ8|70|FQ8_VALTVA|N|12|2|TV a Cabo 1|TV a Cabo Ida
FQ8|71|FQ8_VALTEL|N|12|2|Cia Telefon1|Cia Telefon. Ida
FQ8|72|FQ8_VALOUT|N|12|2|Outros Ida|Outros Ida
FQ8|73|FQ8_VALAUX|N|12|2|Equips.Auxs1|Equips.Auxs.Ida
FQ8|74|FQ8_VALCET|N|12|2|Acomp.CET 1|Acomp.CET Ida
FQ8|75|FQ8_VALVIS|N|12|2|Vr.Vistoria|Vr.Vistoria
FQ8|76|FQ8_VALTCP|N|12|2|Transp.Acess|Transp.Acess
FQ8|77|FQ8_VALMOB|N|12|2|Mob.|Mob.
FQ8|78|FQ8_DESMOB|N|12|2|Desmob.|Desmob.
FQ8|79|FQ8_SEGGUI|N|12|2|Seguro Carga|Seguro Carga
FQ8|80|FQ8_VALGUI|N|12|2|Resumo Guind|Resumo Guind
FQ8|81|FQ8_VALEQU|N|12|2|Equipamento|Equipamento
FQ8|82|FQ8_VRFRET|N|12|2|Vr.Frete|Vr.Frete
FQ8|83|FQ8_SEQGRU|C|3|0|Seq.Grua|Seq.Grua
FQ8|84|FQ8_SEQCAR|C|3|0|Seq.Carga|Seq.Carga
FQ8|85|FQ8_VL2LSR|N|14|2|LSR Volta|LSR Volta
FQ8|86|FQ8_VL2PRE|N|14|2|PRE Volta|PRE Volta
FQ8|87|FQ8_VL2PRF|N|14|2|PRF Volta|PRF Volta
FQ8|88|FQ8_VL2TAP|N|14|2|TAP Volta|TAP Volta
FQ8|89|FQ8_VL2TUV|N|14|2|TUV Volta|TUV Volta
FQ8|90|FQ8_VL2TUR|N|14|2|TUR Volta|TUR Volta
FQ8|91|FQ8_VL2ESC|N|14|2|Escolta 2|Escolta Volta
FQ8|92|FQ8_VL2PED|N|14|2|Pedagios 2|Pedagios Volta
FQ8|93|FQ8_VL2INV|N|14|2|Inversao 2|Inversao Volta
FQ8|94|FQ8_VL2IPT|N|12|2|Laudo IPT 2|Laudo IPT Volta
FQ8|95|FQ8_VL2ACO|N|12|2|Acomp.Tecn.2|Acomp.Tecn. Volta
FQ8|96|FQ8_VL2CET|N|12|2|Acomp.CET 2|Acomp.CET Volta
FQ8|97|FQ8_VL2SEM|N|12|2|Semaforica 2|Semaforica Volta
FQ8|98|FQ8_VL2TVA|N|12|2|TV a Cabo 2|TV a Cabo Volta
FQ8|99|FQ8_VL2TEL|N|12|2|Cia Telefon2|Cia Telefon. Volta
FQ8|9A|FQ8_VL2OUT|N|12|2|Outros Volta|Outros Volta
FQ8|9B|FQ8_VL2CON|N|14|2|Adicional 2|Adicional Volta
FQ8|9C|FQ8_VL2ADI|N|14|2|Adicional 2|Adicional Volta
FQ8|9D|FQ8_VL2AUX|N|12|2|Equips.Auxs2|Equips.Auxs.Volta
FQ8|9E|FQ8_USERGI|C|17|0|Log de Inclu|Log de Inclusao
FQ8|9F|FQ8_USERGA|C|17|0|Log de Alter|Log de Alteracao
FQ8|9G|FQ8_INSTRU|N|14|2|Instrument.|Instrumentacao
FQ8|9H|FQ8_BALSA|N|14|2|Balsa|Balsa
FQ8|9I|FQ8_DESDTA|N|14|2|Despac. DTA|Despachante DTA
FQ8|9J|FQ8_MONDES|N|14|2|Despac. DTA|Despachante DTA
FQ8|9K|FQ8_APOGUI|N|14|2|Apoio/Guinda|Carro Apoio / Guindauto
FQ8|9L|FQ8_CAVEXT|N|14|2|Cavalo Extra|Cavalo Extra
FQ8|9M|FQ8_MODENC|N|14|2|DesMob Encar|DesMOB Encarretado
FQ8|9N|FQ8_DMOENC|N|14|2|DesMob Encar|DesMOB Encarretado
FQ8|9O|FQ8_COMPT|N|7|2|Comprim. Tot|Comprimento total
FQ8|9P|FQ8_LARGT|N|7|2|Largura Tot.|Largura Total
FQ8|9Q|FQ8_ALTUT|N|7|2|Altura Total|Altura Total
FQ8|9R|FQ8_PESOT|N|16|8|Peso total|Peso total
FQ8|9S|FQ8_VALFEC|N|12|2|Valor Fechad|Valor Fechado
--- ### FQ9
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQ9|01|FQ9_FILIAL|C|6|0|FILIAL|FILIAL DO SISTEMA
FQ9|02|FQ9_PROJET|C|22|0|Nro. Projeto|Numero do projeto
FQ9|03|FQ9_OBRA|C|3|0|Obra|Obra
FQ9|04|FQ9_SEQGRU|C|3|0|Sequencia|Sequencia
FQ9|05|FQ9_PRODUT|C|15|0|Produto|Produto
FQ9|06|FQ9_GRUA|C|16|0|Equipamento|Equipamento
FQ9|07|FQ9_AS|C|27|0|Nro AS|Numero da AS
FQ9|08|FQ9_VRTOTO|N|12|2|Tot.Original|Vlr. Total original
FQ9|09|FQ9_VRTOTN|N|12|2|Tot,Reajuste|Total com reajuste
FQ9|10|FQ9_INDICE|C|3|0|Indice|Indice aplicado
FQ9|11|FQ9_TPCALC|C|1|0|Tipo calculo|Tipo do calculo aplicado
FQ9|12|FQ9_DATA|D|8|0|Data|Data
FQ9|13|FQ9_HORA|C|9|0|Horario|Horario
FQ9|14|FQ9_ANIVER|D|8|0|ANIVER. ORIG|Aniversario Orginal
FQ9|15|FQ9_OBS|M|10|0|Obs|Observacao
FQ9|16|FQ9_DTFIMO|D|8|0|Fim Original|Dt. Final Original
FQ9|17|FQ9_DTFIMN|D|8|0|Fim nova|Dt. final nova
FQ9|18|FQ9_ULTFAO|D|8|0|Fat.original|Ultimo fat. original
FQ9|19|FQ9_ULTFAN|D|8|0|fat.novo|Ultimo fat. nova
FQ9|20|FQ9_COD|C|15|0|Sequencial|Sequncial
FQ9|21|FQ9_XATUIN|N|6|2|% indice|% indice
FQ9|22|FQ9_ANIVE2|D|8|0|Aniver.novo|Aniversario novo
FQ9|23|FQ9_MSBLQL|C|1|0|Bloqueado|Registro bloquado
FQ9|24|FQ9_HISTC|C|15|0|hist.calc|Historico do calculo
FQ9|25|FQ9_VLHREX|N|12|2|Km excedente|Km excedente
FQ9|26|FQ9_VLHREO|N|12|2|Exced.Orig.|Exced.Orig.
--- ### FQA
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQA|01|FQA_FILIAL|C|6|0|Filial|Filial do Sistema
FQA|02|FQA_VIAGEM|C|6|0|Viagem|Viagem
FQA|03|FQA_DTINCL|D|8|0|Data Projeto|Data Projeto
FQA|04|FQA_PROJET|C|22|0|Projeto|Projeto
FQA|05|FQA_ENCERR|C|1|0|Encerrado ?|Encerrado ?
FQA|06|FQA_CODCLI|C|6|0|Cod.Cli|Cod.Cli
FQA|07|FQA_LOJCLI|C|2|0|Loja Cli.|Loja Cli.
FQA|08|FQA_CLINOM|C|40|0|Cliente|Cliente
FQA|09|FQA_SOLICT|C|80|0|Solicitante|Solicitante
FQA|10|FQA_PEDCLI|C|15|0|Ped.Cliente|Ped.Cliente
FQA|11|FQA_PLACA|C|40|0|Placa Cavalo|Placa Cavalo
FQA|12|FQA_VEICUL|C|40|0|Placa Reboq.|Placa Reboq.
FQA|13|FQA_NOMMOT|C|40|0|Motorista|Motorista
FQA|14|FQA_SEQCON|C|3|0|Seq.Conjunto|Seq.Conjunto
FQA|15|FQA_SEQCAR|C|3|0|Seq.Carga|Seq.Carga
FQA|16|FQA_SEQTRA|C|3|0|Seq.Transp.|Seq.Transp.
FQA|17|FQA_NOMAJU|C|40|0|Ajudante|Ajudante
--- ### FQB
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQB|01|FQB_FILIAL|C|6|0|Filial|Filial do sistema
FQB|02|FQB_PROJET|C|22|0|Projeto|Projeto
FQB|03|FQB_OBRA|C|3|0|Obra|Obra
FQB|04|FQB_SEQGRU|C|3|0|Sequencia|Sequencia
FQB|05|FQB_AS|C|27|0|AS|AS
FQB|06|FQB_PR|C|9|0|Titulo PR|Titulo PR
FQB|07|FQB_PREF|C|3|0|Prefixo|Prefixo
FQB|08|FQB_PARC|C|3|0|Parcela|Parcela
FQB|09|FQB_PERIOD|D|8|0|Periodo|Ciclo de faturamento
--- ### FQC
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQC|01|FQC_FILIAL|C|6|0|Filial|Filial do Sistema
FQC|02|FQC_CODCHE|C|10|0|Cód Che.List|Código Check-List
FQC|03|FQC_CODBEM|C|16|0|Cód Bem|Código Bem
FQC|04|FQC_CODFOR|C|6|0|Cód Form|Código Formulário
FQC|05|FQC_SEQ|C|4|0|Sequência|Sequência
FQC|06|FQC_STATUS|C|20|0|Status|Status
FQC|07|FQC_POSCON|N|12|0|Pos Contador|Posição do Contador(KM)
FQC|08|FQC_MODELO|C|40|0|Modelo|Modelo
FQC|09|FQC_CODCLI|C|6|0|Cód Cliente|Cód Cliente
FQC|10|FQC_LOJCLI|C|2|0|Loja Cliente|Loja Cliente
FQC|11|FQC_NOMCLI|C|80|0|Nome Cliente|Nome Cliente
FQC|12|FQC_PROJET|C|22|0|Projeto|Projeto
FQC|13|FQC_AS|C|27|0|Nr. AS|Número AS
FQC|14|FQC_OBRA|C|3|0|Obra|Obra
FQC|15|FQC_ESTADO|C|2|0|Estado|Estado
FQC|16|FQC_CIDADE|C|40|0|Cidade|Cidade
FQC|17|FQC_DTINI|D|8|0|Dt Iniciou|Data Iniciou
FQC|18|FQC_HRINI|C|5|0|Hr Iniciou|Hora Iniciou
FQC|19|FQC_DTFIM|D|8|0|Dt Finalizou|Data Finalizou
FQC|20|FQC_HRFIM|C|5|0|Hr Finalizou|Hora Finalizou
FQC|21|FQC_CODCPI|C|11|0|Cod/CPF Ini|Cod user/CPF inicializou
FQC|22|FQC_LOGPOI|C|6|0|Log por Ini|Logado por Inicializou
FQC|23|FQC_NOMUSI|C|40|0|Iniciado por|Iniciado por
FQC|24|FQC_CODCPF|C|11|0|Cod/CPF Fim|Cod user/CPF finalizou
FQC|25|FQC_LOGPOF|C|6|0|Log por fim|Logado por finalizou
FQC|26|FQC_NOMUSF|C|40|0|Finaliz por|Finaliz por
FQC|27|FQC_FILBEM|C|6|0|Filial bem|Filial do bem
FQC|28|FQC_PLACA|C|8|0|Placa|Placa
FQC|29|FQC_NIVELC|C|6|0|Nível combus|Nível combustivel
FQC|30|FQC_CLIAUT|C|50|0|Cliente aut|Cliente autorizado
FQC|31|FQC_CNHAUT|C|50|0|CNH autoriz|CNH autorizado
FQC|32|FQC_EMAAUT|C|70|0|E-mail autor|E-mail autorizado
FQC|33|FQC_STBEMA|C|2|0|St Bem Antig|Status Bem Antigo
FQC|34|FQC_DHFAUT|C|19|0|DtHr Ft CliA|Dt Hr Foto Cli Autorizado
FQC|35|FQC_FCHENT|C|6|0|Fil Chk Entr|Filial CheckList Entrada
FQC|36|FQC_CCHENT|C|10|0|CodChk Entr|Codigo CheckList Entrada
FQC|37|FQC_AUTCON|L|1|0|Aut Contato|Autoriza Contato
FQC|38|FQC_OBS|M|10|0|Observação|Observação
FQC|39|FQC_DESFOR|C|50|0|Desc Form|Descrição Formulário
FQC|40|FQC_CELAUT|C|15|0|Cel autoriz|Cel autoriz
FQC|41|FQC_RESERV|C|1|0|Reserva?|Reserva?
FQC|42|FQC_LJFOR|C|2|0|Loj. Fornec.|Loja Fornecdor
--- ### FQD
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQD|01|FQD_FILIAL|C|6|0|Filial|Filial do Sistema
FQD|02|FQD_STAREN|C|2|0|Stat.Rental|Status no Rental
FQD|03|FQD_DESREN|C|50|0|Desc.Rental|Desc.Rental
FQD|04|FQD_STATQY|C|2|0|Stat.Bem|Status no Manutenção
FQD|05|FQD_DESTQY|C|50|0|Desc.Bem|Desc. Manutenção de ativo
FQD|06|FQD_STAAA3|C|2|0|Stat.GS|Status no GS
FQD|07|FQD_DESAA3|C|50|0|Desc.GS|Desc.GS
--- ### FQE
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQE|01|FQE_FILIAL|C|6|0|Filial|Filial do Sistema
FQE|02|FQE_CODIGO|C|2|0|Sub Status|Cod.Sub Status
FQE|03|FQE_DESCRI|C|30|0|Descricao|Descrição do Sub-Status
FQE|04|FQE_CODSTA|C|2|0|Status|Cod.Status
FQE|05|FQE_DESCST|C|30|0|Sub-Status|Desc.Sub-Status
FQE|06|FQE_SUBST|C|1|0|Substituicao|Substituição do bem
FQE|07|FQE_CARACT|C|6|0|Caracterist.|Caracteristica do bem
FQE|08|FQE_DESCC|C|40|0|Desc.Caracte|Desc.Característica
FQE|09|FQE_TIPO|C|1|0|Tipo|Tipo do movimento
FQE|10|FQE_LOCBLQ|C|1|0|Locacao Bloq|Locacao Bloqueada
--- ### FQF
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQF|01|FQF_FILIAL|C|6|0|Filial|Filial do Sistema
FQF|02|FQF_CODBEM|C|16|0|Cod.Bem|Codigo do bem
FQF|03|FQF_DESBEM|C|40|0|Desc.Bem|Descrição do Bem
FQF|04|FQF_STATUS|C|2|0|Status|Status do bem
FQF|05|FQF_DESSTA|C|50|0|Desc.Status|Descrição do Status
FQF|06|FQF_CC|C|9|0|Centro Custo|Centro de Custo
FQF|07|FQF_DTINI|D|8|0|Data|Data do movimento
FQF|08|FQF_HORA|C|5|0|Hora|Hora do movimento
FQF|09|FQF_SUBST|C|2|0|Sub-Status|Sub-Status do bem
FQF|10|FQF_DESSUB|C|30|0|Desc.Subst.|Descrição Sub-Status
FQF|11|FQF_PROJET|C|22|0|Projeto|Projeto
FQF|12|FQF_AS|C|27|0|AS|Codigo da AS
FQF|13|FQF_OBS|M|10|0|Observacao|Observação
FQF|14|FQF_CONTA|N|9|0|Cont.Bem|Contador do bem
FQF|15|FQF_BEMRES|C|16|0|Bem Reserva|Código do bem reserva
FQF|16|FQF_CONRES|N|9|0|Cont.Reserva|Contador bem reserva
FQF|17|FQF_SEQ|C|6|0|Sequencia|Sequencia FQ4
FQF|18|FQF_OS|C|6|0|OS|Ordem de Serviço
FQF|19|FQF_DPINI|D|8|0|Par.Ini.Rel|Dt.parada inicial
FQF|20|FQF_DPFIM|D|8|0|Par.Fim.Rel|Dt.parada final
FQF|21|FQF_DPRE|D|8|0|Par.Ini.Prv|Dt.Prevista parada
FQF|22|FQF_DREAL|D|8|0|Par.Fim.Prv|Dt.Real parada
FQF|23|FQF_COD|C|10|0|Codigo|Codigo do movimento
FQF|24|FQF_DPPINI|D|8|0|DT.PAR.PR.I.|Data prevista inicial
FQF|25|FQF_HPPINI|C|5|0|HO.PAR.PR.I.|Hora prevista inicial
FQF|26|FQF_DPPFIM|D|8|0|DT.PAR.PR.F.|Data previsão fim
FQF|27|FQF_HPPFIM|C|5|0|HO.PAR.PR.F.|Hora prevista fim
FQF|28|FQF_DPRINI|D|8|0|DT.PAR.RE.I.|Data real inicial
FQF|29|FQF_HPRINI|C|5|0|HO.PAR.RE.I|Hora real inicial
FQF|30|FQF_DPRFIM|D|8|0|DT.PAR.RE.F.|Data real final
FQF|31|FQF_HPRFIM|C|5|0|HO.PAR.RE.F.|Hora real final
--- ### FQG
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQG|01|FQG_FILIAL|C|6|0|Filial|Filial do Sistema
FQG|02|FQG_PROJET|C|22|0|Projeto|Projeto
FQG|03|FQG_OBRA|C|3|0|Obra|Obra
FQG|04|FQG_SEQ|C|3|0|Sequencia|Sequencia
FQG|05|FQG_ETAPA|C|6|0|Etapa|Etapa
FQG|06|FQG_DESETA|C|150|0|Desc.Etapa|Descrição da etapa
FQG|07|FQG_OS|C|6|0|OS|Ordem de Serviço
FQG|08|FQG_SERV|C|6|0|Servico|Código do Serviço
FQG|09|FQG_DESSRV|C|20|0|Nome Servico|Nome do Serviço
FQG|10|FQG_FEITO|C|1|0|Realizado|Realização da OS
FQG|11|FQG_GERAOS|C|1|0|Gera OS|Gerar a OS
FQG|12|FQG_PRODUT|C|15|0|Produto|Código do produto
FQG|13|FQG_DESCPR|C|70|0|Desc.Prod.|Descrição Produto
FQG|14|FQG_QTD|N|9|2|Qtd|Quantidade
FQG|15|FQG_COD|C|6|0|Codigo|Código lançamento
--- ### FQH
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQH|01|FQH_FILIAL|C|6|0|Filial|Filial do Sistema
FQH|02|FQH_STATUS|C|2|0|Status|Código Status
FQH|03|FQH_SUBSTA|C|2|0|SubStatus|Código SubStatus
FQH|04|FQH_SERV|C|6|0|Servico|Cód.Serviço
FQH|05|FQH_DESSRV|C|40|0|Desc.Srv.|Descrição do Serviço
--- ### FQJ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQJ|01|FQJ_FILIAL|C|6|0|Filial|Filial do sistema
FQJ|02|FQJ_CODIGO|C|6|0|Código|Código do período
FQJ|03|FQJ_PERDE|C|2|0|Dia de|Dia de
FQJ|04|FQJ_PERATE|C|2|0|Dia até|Dia até
FQJ|05|FQJ_ATIVO|C|1|0|Ativo|Ativo
FQJ|06|FQJ_APELID|C|40|0|Descrição|Descrição
FQJ|07|FQJ_QTDMES|N|2|0|Qtd.Mês|Quantidade de mêses
--- ### FQK
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQK|01|FQK_FILIAL|C|6|0|Filial|Filial do sistema
FQK|02|FQK_TPMED|C|1|0|Tp.Medição|Tipo da medição
FQK|03|FQK_PROJET|C|22|0|Projeto|Código do projeto
FQK|04|FQK_GRPMD|C|3|0|Grp.Medição|Grupo da medição
FQK|05|FQK_AS|C|27|0|AS|Número da AS
FQK|06|FQK_PMEDI|C|6|0|Per.Medição|Período da medição
FQK|07|FQK_COD|C|6|0|Nro.Medição|Nro. da medição
FQK|08|FQK_MEDSEQ|C|3|0|Seq.Medição|Seq. medição
FQK|09|FQK_DTINIC|D|8|0|Data inicial|Data inicial
FQK|10|FQK_DTFIM|D|8|0|Data Final|Data final
FQK|11|FQK_CLIENT|C|6|0|Cliente|Cód. cliente do contrato
FQK|12|FQK_LOJA|C|2|0|Loja|Loja cliente contrato
FQK|13|FQK_NOMAGE|C|80|0|Nome Cliente|Nome cliente contrato
FQK|14|FQK_CONDPA|C|3|0|Cond.Pgto|Condição de pagamento
FQK|15|FQK_SITUAC|C|1|0|Situação|Situação
FQK|16|FQK_VLARRE|N|4|2|Arredonda|Arredondamento
FQK|17|FQK_NATUR|C|10|0|Natureza|Natureza
FQK|18|FQK_TIPO|C|1|0|Tipo|Tipo
FQK|19|FQK_CODVEN|C|6|0|Cód.Vendedor|Código do vendedor
FQK|20|FQK_NOMVEM|C|50|0|Nom.Vendedor|Nome do vendedor
FQK|21|FQK_CLIFAT|C|6|0|Cli.Fat.|Cod.cliente faturamento
FQK|22|FQK_LOJFAT|C|2|0|Loj.Cli.Fat.|Loja cliente faturamento
FQK|23|FQK_NOMFAT|C|80|0|Nom.Cli.Fat.|Nome cliente faturamento
FQK|24|FQK_INTCON|C|1|0|Int.Contador|Integra contador
FQK|25|FQK_TPFRAN|C|1|0|Tp.Cons.Fran|Tipo consumo da franquia
FQK|26|FQK_FILPV|C|6|0|Fil.PV|Filial pedido de venda
FQK|27|FQK_NUMPV|C|6|0|PV|Pedido de vendas
FQK|28|FQK_DESDTP|D|8|0|Desmogi Prev|Desmobi data prev.
FQK|29|FQK_ENCEAS|C|1|0|Encerra AS|Encerra AS
FQK|30|FQK_OBRA|C|3|0|Obra|Obra
FQK|31|FQK_VIAGEM|C|6|0|Viagem|Viagem
FQK|32|FQK_MINMES|N|3|0|Min. Hrs.Mes|Min. Hrs.Mes
FQK|33|FQK_VLRFRA|N|12|2|Franq.Calc.|Franquia Calculada
FQK|34|FQK_QTDKM|N|12|2|Qtd.Total|Quantidade total
FQK|35|FQK_DUBASE|N|12|2|Tot +/- Bas|Total +/- unid.base
FQK|36|FQK_QTDTOT|N|12|2|Qtd.Tot.Base|Quantidade total base
FQK|37|FQK_QTDHR|N|12|2|Tot.Cob.Base|Tot.Cob.Base
FQK|38|FQK_VALTOT|N|12|2|Vlr.Tot.Item|Valor total item
FQK|39|FQK_VLRTOT|N|12|2|Vlr.Tot.Medi|Valor total da medição
FQK|40|FQK_VLRDES|N|12|2|Vlr.Desconto|Total de desconto
FQK|41|FQK_VLRACR|N|12|2|Vlr.Acresc.|Vlr.Total de Acréscimo
FQK|42|FQK_VLRMOB|N|12|2|Vlr.Frete|Valor do frete
FQK|43|FQK_VALSEG|N|12|2|Vlr.Seguro|Valor do seguro
FQK|44|FQK_VLAISS|N|12|2|Vlr.ISS|Valor do ISS
FQK|45|FQK_VALSER|N|12|2|Vlr.Serviço|Valor do serviço
FQK|46|FQK_VLTOTM|N|12|2|Tot.Mão Obra|Total de mão de obra
FQK|47|FQK_VREXTR|N|12|2|Vlr.Extra|Valor extra
FQK|48|FQK_VLMAQ|N|12|2|Tot.Máquina|Total de máquinas
FQK|49|FQK_OBS|M|10|0|Observação|Observação
FQK|50|FQK_OBSDES|M|10|0|Obs.Desc.|Observação do desconto
FQK|51|FQK_OBSACR|M|10|0|Obs.Acresc.|Observação do acréscimo
FQK|52|FQK_TESMAO|C|3|0|TES Mão Obra|TES da mão de obra
FQK|53|FQK_TESMAQ|C|3|0|TES Máquina|TES para máquinas
--- ### FQL
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQL|01|FQL_FILIAL|C|6|0|Filial|Filial do sistema
FQL|02|FQL_ITEM|C|3|0|Item|Item
FQL|03|FQL_ORDEM|C|3|0|Ordem|Ordem
FQL|04|FQL_AS|C|27|0|AS|AS
FQL|05|FQL_DTMEDI|D|8|0|Dt.Medição|Data da medição
FQL|06|FQL_DTSAID|D|8|0|Dt.Exped|Data da expedição
FQL|07|FQL_DTENT|D|8|0|Dt.Devo|Data da devolução
FQL|08|FQL_FROTA|C|16|0|Bem|Código do bem
FQL|09|FQL_DESCEQ|C|40|0|Descrição|Descrição do equipamento
FQL|10|FQL_MINDIA|N|3|0|Min.Hrs.Dia|Min.Hrs.Dia
FQL|11|FQL_HRPARA|C|6|0|Hr.Parada|Horas paradas
FQL|12|FQL_BASE|C|1|0|Base Cálculo|Base do cálculo
FQL|13|FQL_GRPMD|C|3|0|Grp.Medição|Grupo da medição
FQL|14|FQL_BFRANQ|C|1|0|B.Franquia|Base da franquia
FQL|15|FQL_FRKM|N|14|4|Franquia|Franquia
FQL|16|FQL_VLRFRA|N|12|2|Franq.Calc|Franquia calculada
FQL|17|FQL_KMINI|N|14|4|Qtd.Inicial|Quantidade inicial
FQL|18|FQL_KMFIM|N|14|4|Qtd.Final|Quantidade final
FQL|19|FQL_COMPLE|N|14|4|Qtd.Complem.|Qtd.Complementar
FQL|20|FQL_QTDKM|N|14|4|Qtd.Total|Quantidade total
FQL|21|FQL_DUBASE|N|12|2|Qtd +/- Base|Qtd. +/- Uni.Base
FQL|22|FQL_HORTOT|N|12|2|Qtd.Tot.Base|Qtd.total da base
FQL|23|FQL_VALHOR|N|12|2|Vlr.Uni.Base|Vlr.Uni.Base
FQL|24|FQL_QTDHR|N|12|2|Qtd.Cob.Base|Qtd.cobr.base excedente
FQL|25|FQL_QTDHR2|N|12|2|Qtd.Compart.|Qtd.Compartilhada
FQL|26|FQL_VLTOHR|N|12|2|Vlr.Tot.Item|Valor Total Itens
FQL|27|FQL_VLRTOT|N|12|2|Vlr.Tot.Medi|Vlr.total da medição
FQL|28|FQL_PERD|N|6|2|% Desc|Percentual desconto
FQL|29|FQL_DESC|N|12|2|Vlr.Desconto|Valor do desconto
FQL|30|FQL_PERA|N|6|2|% Acresc.|Percentual acréscimo
FQL|31|FQL_ACRES|N|12|2|Vlr.Acresc.|Valor do acréscimo
FQL|32|FQL_VLRMOB|N|12|2|Vl.Mobiliz|Valor da mobilização
FQL|33|FQL_VLRDES|N|12|2|Vlr.Desmobil|Valor desmobilização
FQL|34|FQL_TIPO|C|1|0|Tipo Seguro|Tipo do seguro
FQL|35|FQL_PERSEG|N|7|3|% Seguro|% do seguro
FQL|36|FQL_VLBSEG|N|12|2|Vlr.Base Seg|Vlr.Base Seguro
FQL|37|FQL_VALSEG|N|12|2|Vlr.Seguro|Valor do seguro
FQL|38|FQL_TPISS|C|1|0|Tipo ISS|Tipo do ISS
FQL|39|FQL_PERISS|N|7|3|% ISS|% ISS
FQL|40|FQL_VALISS|N|12|2|Vlr.ISS|Valor do ISS
FQL|41|FQL_PERMO|N|7|3|% Mão Obra|% da mão de obra
FQL|42|FQL_VLTOTM|N|12|2|Vlr.Mão Obra|Vlr.mão de obra
FQL|43|FQL_TRSPES|N|12|2|Trans./Peso|Trans./Peso
FQL|44|FQL_ANCORA|N|12|2|Ancoragem|Ancoragem
FQL|45|FQL_TELESC|N|12|2|Telescopagem|Telescopagem
FQL|46|FQL_MONTAG|N|12|2|Montagem|Montagem
FQL|47|FQL_DESMON|N|12|2|Desmontagem|Desmontagem
FQL|48|FQL_ACESSO|N|12|2|Vlr.Acessor.|Valor acessório
FQL|49|FQL_CCUSTO|C|9|0|Centro Lucro|Centro de lucro
FQL|50|FQL_PERMAQ|N|6|2|% Máquina|% Máquina
FQL|51|FQL_VLMAQ|N|12|2|Vlr.Máquina|Valor da máquina
FQL|52|FQL_PERMAO|N|6|2|% M.Obra|% da mão de obra
FQL|53|FQL_VLMAO|N|12|2|Vlr.M.Obra|Valor da mão de obra
FQL|54|FQL_OBRA|C|3|0|Obra|Obra
FQL|55|FQL_TURNO|C|3|0|Turno|Turno
FQL|56|FQL_COD|C|6|0|Nro.Medição|Número da medição
FQL|57|FQL_XTIPOH|C|1|0|Tipo de hora|Tipo de hora
FQL|58|FQL_PERHAD|C|3|0|Per.Hr.Adi|% de hora adicional
FQL|59|FQL_TPAS|C|1|0|Tp.AS|Tipo de AS
FQL|60|FQL_TPCONT|C|20|0|Tp.Contador|Tipo do contador
FQL|61|FQL_PROD|C|15|0|Cód.Produto|Código do produto
FQL|62|FQL_BEMRES|C|10|0|Bem reserva|Bem reserva
FQL|63|FQL_TPMEDI|C|1|0|Tp.Medição|Tipo da medição
FQL|64|FQL_OS|C|6|0|OS|Ordem de serviço
FQL|65|FQL_MINUTA|C|6|0|Minuta|Minuta
FQL|66|FQL_LIBER|C|1|0|Sta.Lib.PV|Status libera PV
--- ### FQM
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQM|01|FQM_FILIAL|C|6|0|Filial|Filial do sistema
FQM|02|FQM_CODIGO|C|6|0|Código|Código
FQM|03|FQM_DESC|C|40|0|Descrição|Descrição
--- ### FQN
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQN|01|FQN_FILIAL|C|6|0|Filial|Filial do Sistema
FQN|02|FQN_CODFOR|C|1|0|Código Form.|Código Formulário
FQN|03|FQN_CODFAM|C|6|0|Cód Família|Código Família
FQN|04|FQN_SEQ|C|4|0|Sequência|Sequência
FQN|05|FQN_CODTOP|C|6|0|Cód Tópico|Código Tópico
FQN|06|FQN_CODITE|C|6|0|Cód Item|Código Item
FQN|07|FQN_DESITE|C|40|0|Desc Item|Descrição Item
FQN|08|FQN_NAOAPL|C|1|0|Não Aplica|Não Aplica
FQN|09|FQN_FOTO|C|1|0|Foto|Foto
--- ### FQT
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQT|01|FQT_FILIAL|C|6|0|Filial|Filial
FQT|02|FQT_DEMAND|C|6|0|Demanda|Codigo da Demanda
FQT|03|FQT_DESC|C|90|0|Descricao|Descrição da Demanda
FQT|04|FQT_PROJET|C|22|0|Nro Projeto|Numero do Projeto
FQT|05|FQT_CLIPRO|C|6|0|Cliente Proj|Cliente do Projeto
FQT|06|FQT_LOJPRO|C|2|0|Loja Projeto|Loja CLiente Projeto
FQT|07|FQT_NOMPRO|C|80|0|Nome Cliente|Nome Cliente Projeto
FQT|08|FQT_OBRA|C|3|0|Obra|Codigo da Obra
FQT|09|FQT_CLIOBR|C|6|0|Cliente Obra|Codigo do Cliente Obra
FQT|10|FQT_LOJOBR|C|2|0|Loja Cli Obr|Loja do Cliente da Obra
FQT|11|FQT_NOMOBR|C|80|0|Nome Obra|Nome Cliente da Obra
FQT|12|FQT_EMISSA|D|8|0|Emissao|Data de emissao
FQT|13|FQT_PRAZO|D|8|0|Prazo|Prazo de Atendimento
FQT|14|FQT_PRAZOH|C|5|0|Prazo Hora|Prazo Horas
FQT|15|FQT_OBSSER|M|10|0|Obs Servico|Observação do Serviço
FQT|16|FQT_OBSINT|M|10|0|Obs Interna|Observação Interna Demand
FQT|17|FQT_OBSNF|M|10|0|Obs Nota|Observação para Nota
FQT|18|FQT_ITENS|N|6|0|Qtd A.S.|Quantidade A.S. demanda
FQT|19|FQT_QTDPRO|N|12|2|Qtd Produto|Quantidade de Produtos
FQT|20|FQT_PESLIQ|N|15|4|Peso Liquido|Peso Liquido Total
FQT|21|FQT_PENDEN|N|12|2|Qtd Pendente|Quantidade Pendente
FQT|22|FQT_TIPFRE|C|1|0|Tipo Frete|Tipo do Frete Utilizado
FQT|23|FQT_SEPARA|N|12|2|Qtd Separada|Quantidade Separada
FQT|24|FQT_EMBARC|N|12|2|Qtd Embarca|Quantidade Embarcada
FQT|25|FQT_CONFER|N|12|2|Qtd Conferid|Quantidade Conferida
FQT|26|FQT_FATURA|N|12|2|Qtd Nota|Quantidade com Nota Emiti
FQT|27|FQT_M3|N|15|4|m3|Volume total m3
FQT|28|FQT_PESBRU|N|15|4|Peso Bruto|Peso Bruto Total
FQT|29|FQT_QTD2|N|12|2|Qtd 2 Unid|Quantidade Segunda Unidad
--- ### FQU
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQU|01|FQU_FILIAL|C|6|0|Filial|Filial
FQU|02|FQU_NUM|C|9|0|Num Romaneio|NUmero do Romaneio
FQU|03|FQU_PROJET|C|22|0|Projeto|Codigo do Projeto
FQU|04|FQU_OBRA|C|3|0|Obra|Obra
FQU|05|FQU_ASF|C|27|0|A.S.F.|Codigo da A.S.F.
FQU|06|FQU_VIAGEM|C|6|0|Viagem|Viagem
FQU|07|FQU_DATA|D|8|0|Data Geracao|Data Geração do Romaneio
FQU|08|FQU_CLIENT|C|6|0|Cliente Proj|Cliente do Projeto
FQU|09|FQU_LOJA|C|2|0|Loja Cliente|Loala do Cliente
FQU|10|FQU_NOMCLI|C|80|0|Nome Cliente|Nome do Cliente Projeto
FQU|11|FQU_CLIDES|C|6|0|Cliente Dest|Cliente de Destino
FQU|12|FQU_LOJDES|C|2|0|Loja Destino|Loja de Destino
FQU|13|FQU_NOMDES|C|80|0|Nome Destino|Nome do Destinatario
FQU|14|FQU_ENDDES|C|40|0|Endereço|Endereço de Destino
FQU|15|FQU_BAIDES|C|25|0|Bairro|Bairro de Destino
FQU|16|FQU_MUNDES|C|25|0|Municipio De|Municipio Destino
FQU|17|FQU_ESTDES|C|2|0|UF Destino|UF de destino
FQU|18|FQU_CEPDES|C|8|0|CEP Destino|CEP de destino
FQU|19|FQU_TIPOVE|C|2|0|Tipo Veiculo|Tipo do Veiculo
FQU|20|FQU_DTIPVE|C|30|0|Desc.Veiculo|Descricao Tipo Veiculo
FQU|21|FQU_VEICUL|C|8|0|Veiculo|Veiculo Principal
FQU|22|FQU_PLACA|C|8|0|Placa|Placa veiculo principal
FQU|23|FQU_VEICU2|C|8|0|Veiculo 2|Veiculo 2
FQU|24|FQU_PLACA2|C|8|0|Placa 2|Placa Veiculo 2
FQU|25|FQU_VEICU3|C|8|0|Veiculo 3|Codigo de Veiculo 3
FQU|26|FQU_PLACA3|C|8|0|Placa 3|Placa Terceiro Veiculo
FQU|27|FQU_TPFRET|C|1|0|Tipo Frete|Tipo do Frete
FQU|28|FQU_CODTRA|C|6|0|Cod.Transp.|Codigo Transportadora
FQU|29|FQU_TRANS|C|40|0|Desc.Transp.|Descricao Transportadora
FQU|30|FQU_OBS|M|10|0|Obs Internas|Observações Internas
FQU|31|FQU_MOTCOD|C|6|0|Cod Motorist|Codigo do Motorista
FQU|32|FQU_MOTORI|C|40|0|Motorista|Nome do Motorista
FQU|33|FQU_CPFMOT|C|14|0|CPF|CPF
FQU|34|FQU_DTFISC|D|8|0|Data Fiscal|Data Fiscal
FQU|35|FQU_VOLUME|N|6|0|Volume|Volume
FQU|36|FQU_PICKIN|C|6|0|Picking|Codigo do Picking
FQU|37|FQU_MENNOT|M|10|0|Obs p/ Nota|Observação para Nota
FQU|38|FQU_ESPECI|C|10|0|Especie|Especie de Volume
FQU|39|FQU_DINEMB|D|8|0|Dt Ini Embar|Data Inicio Embarque
FQU|40|FQU_HINEMB|C|5|0|Hora Ini Emb|Hora Inicio Embarque
FQU|41|FQU_DFIEMB|D|8|0|Data Fim Emb|Data Final Embarque
FQU|42|FQU_HFIEMB|C|5|0|Hora Fim Emb|Hora Final Embarque
FQU|43|FQU_DINDES|D|8|0|Dt Ini Desem|Data Inicio Desembarque
FQU|44|FQU_HINDES|C|5|0|Hora Ini Des|Hora Inicio Desembarque
FQU|45|FQU_DFIDES|D|8|0|Dt Fim Desem|Data Final Desembarque
FQU|46|FQU_HFIDES|C|5|0|Hr Fim Desem|Hora Final Desembarque
FQU|47|FQU_STATUS|C|1|0|Status|Status do Romaneio
FQU|48|FQU_FCHEMB|C|1|0|Fecha Embarq|Fecha Embarque
FQU|49|FQU_MENNF|C|60|0|Mens p/ Nota|Mensagem para Nota Fiscal
FQU|50|FQU_USREMB|C|6|0|Usuario Emba|Usuario Fecha Embarque
FQU|51|FQU_NUSEMB|C|40|0|Nome Us. Emb|Nome Usario Embarque
FQU|52|FQU_DFEEMB|D|8|0|Dt Fecha Emb|Data Fechamento Embarque
FQU|53|FQU_HFEEMB|C|5|0|Hora Embarqu|Hora Fechamento Embarque
--- ### FQV
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQV|01|FQV_FILIAL|C|6|0|FILIAL|Filial Sistemas
FQV|02|FQV_NUM|C|9|0|Num Romaneio|Numero do Romaneio
FQV|03|FQV_ITEM|C|4|0|Item|Item
FQV|04|FQV_PROD|C|15|0|Produto|Codigo Produto
FQV|05|FQV_DESPRO|C|70|0|Desc Prod|Descricao do Produto
FQV|06|FQV_QTD|N|12|2|Quantidade|Quantidade
FQV|07|FQV_FAMBEM|C|6|0|Familia|Familia do Bem
FQV|08|FQV_FAMILI|C|20|0|Desc Familia|Descrição da Familia
FQV|09|FQV_CODBEM|C|16|0|Cod Bem|Codigo do Bem
FQV|10|FQV_NOMBEM|C|40|0|Nome do Bem|Nome do Bem
FQV|11|FQV_NFREM|C|9|0|NF Remessa|Nota Fiscal Remessa
FQV|12|FQV_SERREM|C|3|0|Serie NF|Serie Nota Fiscal Remessa
FQV|13|FQV_ITEMNF|C|2|0|Item NF|Item Nota Fiscal
FQV|14|FQV_PEDIDO|C|6|0|Pedido Venda|Codigo do Pedido de Venda
FQV|15|FQV_ITEMPV|C|2|0|Item P.V.|Item do Pedido Venda
FQV|16|FQV_OBSCCM|C|20|0|Tit Obs Cont|Titulo Obs Contribuinte
FQV|17|FQV_OBSCON|C|60|0|Obs Contribu|Observação Contribuinte
FQV|18|FQV_OBSFCM|C|20|0|Tit Obs Fisc|Titulo Observacao Fiscal
FQV|19|FQV_OBSFIS|C|60|0|Obs Fisco|Observacao do Fisco
FQV|20|FQV_AS|C|27|0|A.S.|Codigo da A.S.
FQV|21|FQV_STATUS|C|1|0|Status|Status
--- ### FQZ
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC
FQZ|01|FQZ_FILIAL|C|6|0|Filial|Filial do Sistema
FQZ|02|FQZ_DOC|C|9|0|Nota|Numero da nota
FQZ|03|FQZ_SERIE|C|3|0|Serie|Serie da nota
FQZ|04|FQZ_ITEM|C|4|0|Item|Item da nota
FQZ|05|FQZ_FORNE|C|6|0|Fornecedor|Codigo do fornecedor
FQZ|06|FQZ_LOJA|C|2|0|Loja|Loja do fornecedor
FQZ|07|FQZ_NOME|C|80|0|Nome|Nome do fornecedor
FQZ|08|FQZ_EMISS|D|8|0|Emissão|Data da emissão da nota
FQZ|09|FQZ_COD|C|15|0|Produto|Codigo do produto
FQZ|10|FQZ_DESC|C|70|0|Descriçao|Descricao do produto
FQZ|11|FQZ_QTD|N|11|2|Quantidade|Quantidade
FQZ|12|FQZ_AS|C|27|0|AS|AS do contrato
FQZ|13|FQZ_MSBLQL|C|1|0|Bloqueado?|Registro bloqueado
FQZ|14|FQZ_DTCANC|D|8|0|Cancelamento|Data do cancelamento
FQZ|15|FQZ_PROJET|C|22|0|Projeto|Codigo do projeto
FQZ|16|FQZ_VLRUNI|N|12|2|Vlr.Unitário|Valor unitário
FQZ|17|FQZ_DTINI|D|8|0|Dt.Inicial|Data Inicial
FQZ|18|FQZ_DTFIM|D|8|0|Dt.Final|Data Final
FQZ|19|FQZ_VLRTOT|N|12|2|Vlr.Total|Valor Total
FQZ|20|FQZ_SOLRET|D|8|0|Sol.Retirada|Solicitação de Retirada
FQZ|21|FQZ_PERPRO|N|4|0|Pro rata|Pro rata
FQZ|22|FQZ_VLRPRO|N|12|2|Vlr.Pro Rata|Valor da Pro Rata
FQZ|23|FQZ_ULTFAT|D|8|0|Ultimo fat.|Ultimo faturamento
FQZ|24|FQZ_RETIRA|D|8|0|Dt.Retirada|Solicitacao da retirada
FQZ|25|FQZ_PV|C|6|0|PV|Pedido de Vendas
FQZ|26|FQZ_OBRA|C|3|0|Obra|Obra
FQZ|27|FQZ_SEQGUI|C|3|0|Locacao|Locacao
FQZ|28|FQZ_ZUCI|C|3|0|Item coleta|Item coleta
FQZ|29|FQZ_FORMUL|C|1|0|Form. Prop.|Formulario Proprio

