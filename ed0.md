## Módulo: SIGANFS (Nota Fiscal de Serviço Eletrônica - Legado)  
--- ### ED0  
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC  
ED0|01|ED0_FILIAL|C|6|0|Filial|Filial do Sistema
ED0|02|ED0_PD|C|13|0|Ped.Drawback|Pedido de Drawback
ED0|03|ED0_AC|C|13|0|Ato Concess.|Ato Concessorio
ED0|04|ED0_IMPORT|C|2|0|Beneficiária|Beneficiária
ED0|05|ED0_DESCIM|C|30|0|Descr. Benef|Nome Beneficiaria
ED0|06|ED0_MODAL|C|1|0|Modalidade|Modalidade
ED0|07|ED0_ELETRO|C|1|0|Ctr.Siscomex|Suspensao Eletronica?
ED0|08|ED0_STATUS|C|1|0|Situacao|Sit. Pedido de DrawBack
ED0|09|ED0_CAPITA|C|1|0|Bem Capital|Bem de Capital
ED0|10|ED0_TIPOAC|C|2|0|Tipo AC|Tipo do Ato Concessorio
ED0|11|ED0_VMTIPO|C|50|0|Desc Tipo|Descricao Tipo Drawback
ED0|12|ED0_FRETE|N|14|2|Frete Estim.|Frete Estimado
ED0|13|ED0_SEGURO|N|14|2|Seguro Estim|Seguro Estimado
ED0|14|ED0_DEFERI|D|8|0|Dt Deferim.|Data de Deferimento
ED0|15|ED0_DT_REG|D|8|0|Dt. Registro|Data do Registro
ED0|16|ED0_DT_VA1|D|8|0|Dt. Validade|Data da Validade Digitada
ED0|17|ED0_DT_VA2|D|8|0|Val. Ap.Emb.|Data Validade Ap. Embarq.
ED0|18|ED0_DT_PR1|D|8|0|Prorrog. 1a|Data da Prorrogacao 1a
ED0|19|ED0_PROAP1|C|1|0|1a Aprovada|Prorrogacao 1a Aprovada?
ED0|20|ED0_DT_PR2|D|8|0|Prorrog. 2a|Data da Prorrogacao 2a
ED0|21|ED0_PROAP2|C|1|0|2a Aprovada|Prorrogacao 2a Aprovada?
ED0|22|ED0_DT_PR3|D|8|0|Prorrog. 3a|Data da Prorrogacao 3a
ED0|23|ED0_PROAP3|C|1|0|3a Aprovada|Prorrogacao 3a Aprovada?
ED0|24|ED0_DIAG|N|3|0|Diagnostico|Numero do Diagnostico
ED0|25|ED0_DT_ENV|D|8|0|Data Envio|Data de Envio p/ SISCOMEX
ED0|26|ED0_ENV|N|3|0|Nr. Envio|Numero do Envio
ED0|27|ED0_OBS|C|6|0|Obs|Observacao
ED0|28|ED0_VM_OBS|M|60|0|Observacao|Observacao
ED0|29|ED0_PRACA|C|20|0|Prac.Emissao|Praca de Emissao
ED0|30|ED0_DELEGA|C|20|0|Delegacia RF|Del. da Receita Federal
ED0|31|ED0_CNPJ1|C|14|0|CNPJ 1|CNPJ Emp. Exportadora
ED0|32|ED0_CNPJ2|C|14|0|CNPJ 2|CNPJ Emp. Exportadora
ED0|33|ED0_CNPJ3|C|14|0|CNPJ 3|CNPJ Emp. Exportadora
ED0|34|ED0_CNPJ4|C|14|0|CNPJ 4|CNPJ Emp. Exportadora
ED0|35|ED0_CNPJ5|C|14|0|CNPJ 5|CNPJ Emp. Exportadora
ED0|36|ED0_CNPJ6|C|14|0|CNPJ 6|CNPJ Emp. Exportadora
ED0|37|ED0_CNPJ7|C|14|0|CNPJ 7|CNPJ Emp. Exportadora
ED0|38|ED0_CNPJ8|C|14|0|CNPJ 8|CNPJ Emp. Exportadora
ED0|39|ED0_CNPJ9|C|14|0|CNPJ 9|CNPJ Emp. Exportadora
ED0|40|ED0_CNPJ10|C|14|0|CNPJ 10|CNPJ Emp. Exportadora
ED0|41|ED0_CNPJ11|C|14|0|CNPJ 11|CNPJ Emp. Exportadora
ED0|42|ED0_CNPJ12|C|14|0|CNPJ 12|CNPJ Emp. Exportadora
ED0|43|ED0_CNPJ13|C|14|0|CNPJ 13|CNPJ Emp. Exportadora
ED0|44|ED0_CNPJ14|C|14|0|CNPJ 14|CNPJ Emp. Exportadora
ED0|45|ED0_CNPJ15|C|14|0|CNPJ 15|CNPJ Emp. Exportadora
ED0|46|ED0_CNPJ16|C|14|0|CNPJ 16|CNPJ Emp. Exportadora
ED0|47|ED0_CNPJ17|C|14|0|CNPJ 17|CNPJ Emp. Exportadora
ED0|48|ED0_CNPJ18|C|14|0|CNPJ 18|CNPJ Emp. Exportadora
ED0|49|ED0_CNPJ19|C|14|0|CNPJ 19|CNPJ Emp. Exportadora
ED0|50|ED0_CNPJ20|C|14|0|CNPJ 20|CNPJ Emp. Exportadora
ED0|51|ED0_OK|C|2|0|Ok|Flag para PD's marcados
ED0|52|ED0_RET|C|6|0|Ret.SISCOMEX|Retorno do SISCOMEX
ED0|53|ED0_DT_ENC|D|8|0|Dt. Encerra.|Data de Encerramento
ED0|54|ED0_ARQ|C|50|0|Arquivo|Arquivo de envio SISCOMEX
ED0|55|ED0_ANEEXP|C|1|0|Anexo Exp.|Opc. Imp.Anexo Exportacao
ED0|56|ED0_PERCTO|N|6|2|Perc. Toler.|Percentual de Tolerancia
ED0|57|ED0_RUD|C|1|0|Rud|Rel. Unico de Drawback
ED0|58|ED0_FRE_S|C|1|0|Frete/Seguro|Frete/Seg. Capa ou Carta
ED0|59|ED0_DT_PED|D|8|0|Dt Env. Ped.|Data de Envio do Pedido
ED0|60|ED0_ALTERA|C|1|0|Alteracao|Pedido Tem Alteracao?
ED0|61|ED0_CDIAG|C|1|0|Cons. Diag.|Consulta Diagnostico
ED0|62|ED0_ENQCOD|C|5|0|Cod.Enquadr.|Codigo do Enquadramento
ED0|63|ED0_SUBTOT|C|1|0|Imp.Subt.It.|Imprime Subtotal Por Item
ED0|64|ED0_DEDUZP|C|1|0|Deduz Perc.?|Deduz Perc.Perda no Anexo
ED0|65|ED0_SEQED3|C|3|0|Seq ED3|Ultima Sequencia ED3
ED0|66|ED0_SEQED4|C|3|0|Seq ED4|Ultima Sequencia ED4
ED0|67|ED0_PTOTAL|N|5|2|Sub Residuo|Percentual de Sub Residuo
ED0|68|ED0_PERCPE|C|1|0|Quebra Perca|Quebra por % de perda
ED0|69|ED0_INTEGR|C|1|0|Integrado?|Indica se é Drawback Inte
ED0|70|ED0_MIED4|C|4|0|Seq MI ED4|Ultima Sequencia ED4 MI
ED0|71|ED0_TIPINS|C|1|0|Insumos?|Tipo de Insumos
ED0|72|ED0_AGRSLD|C|1|0|Agrp. Saldo?|Agrupa Saldo?

