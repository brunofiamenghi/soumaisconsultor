## Módulo: SIGANFS (Nota Fiscal de Serviço Eletrônica - Legado)  
--- ### ED8  
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC  
ED8|01|ED8_FILIAL|C|6|0|Filial|Filial do Sistema
ED8|02|ED8_IMPORT|C|2|0|Importador|Importador
ED8|03|ED8_DESCIM|C|30|0|Nome Import.|Nome do Importador
ED8|04|ED8_CNPJIM|C|14|0|CNPJ Import.|CNPJ do Importador
ED8|05|ED8_DI_NUM|C|15|0|No. da DI|No. da DI
ED8|06|ED8_DTREG|D|8|0|Registro DI|Data de Registro D.I.
ED8|07|ED8_ADICAO|C|3|0|No. Adicao|No. Adicao
ED8|08|ED8_PEDIDO|C|20|0|Pedido|Nro. Do Pedido
ED8|09|ED8_POSDI|C|4|0| Posição|Posicao para DI ou para P
ED8|10|ED8_LI_NUM|C|10|0|No. PLI/Reg.|No. PLI/Reg.
ED8|11|ED8_DTLI|D|8|0|Registro LI|Data de Registro L.I.
ED8|12|ED8_COD_I|C|15|0|Cod. Item|Codigo do item
ED8|13|ED8_DESC|C|60|0|Descricao|Descricao da Mercadoria
ED8|14|ED8_DES_DI|C|6|0|Cod.Desc.Ite|Cod.Desc.Ite
ED8|15|ED8_DES_VM|M|65|0|Descricao DI|Descricao da DI
ED8|16|ED8_NCM|C|10|0|NCM|NCM
ED8|17|ED8_PESO|N|16|7|Peso Liq. Un|Peso Unitario
ED8|18|ED8_UM|C|2|0|UM. Compra|Unidade de medida CV
ED8|19|ED8_QTD|N|15|5|Qtd. Compra|Quantidade da UM.
ED8|20|ED8_UMNCM|C|2|0|UM. NCM|Unidade de medida
ED8|21|ED8_QTDNCM|N|15|5|Qtd. NCM|Quantidade da UM.
ED8|22|ED8_MOEDA|C|3|0|Moeda|Moeda
ED8|23|ED8_TX_MOE|N|15|8|Taxa Moeda|Taxa da moeda
ED8|24|ED8_VALORI|N|15|2|Val Tot. Moe|Valor na Moeda
ED8|25|ED8_TX_USS|N|15|8|Taxa US$|Taxa da Moeda
ED8|26|ED8_VALEMB|N|14|2|Val Tot. US$|Valor FOB
ED8|27|ED8_NF|C|9|0|Nota Fiscal|Nota Fiscal
ED8|28|ED8_SERIE|C|3|0|Serie|Serie
ED8|29|ED8_EMISSA|D|8|0|Data NF|Data de Emissao da NF
ED8|30|ED8_AC|C|13|0|Ato Concess.|Ato Concessorio
ED8|31|ED8_SEQSIS|C|3|0|Seq.AC.|Posicao
ED8|32|ED8_INVOIC|C|20|0|Invoice|Nr. da invoice
ED8|33|ED8_MOE_FR|C|3|0|Moeda Frete|Moeda do frete
ED8|34|ED8_TX_FR|N|15|8|Tx.Frete|Taxa do frete
ED8|35|ED8_FRETE|N|15|2|Vl.Frete Moe|Valor do frete
ED8|36|ED8_MOE_SE|C|3|0|Moeda Seguro|Moeda do seguro
ED8|37|ED8_TX_SE|N|15|8|Tx.Seguro|Taxa do seguro
ED8|38|ED8_SEGURO|N|15|2|Vl.Seg. Moe|Valor do seguro
ED8|39|ED8_SE_USS|N|15|2|Vl.Seg. US$|Valor do seguro
ED8|40|ED8_MRCDES|N|15|2|AFRMM|Desp.Marinha Mercante
ED8|41|ED8_ARMDES|N|15|2|Armazenagem|Despesas com armazenagem
ED8|42|ED8_INLAND|N|15|2|Inland|Inland Charge
ED8|43|ED8_OUTDES|N|15|2|Out.Despesas|Outras Despesas
ED8|44|ED8_DESCNT|N|15|2|Desconto|Desconto
ED8|45|ED8_PACKIN|N|15|2|Packing|Packing.Charges
ED8|46|ED8_FOBGER|N|15|2|Vl FOB Total|Valor FOB Total
ED8|47|ED8_VL_AC|N|15|2|Valor AC|Valor FOB
ED8|48|ED8_QT_AC|N|15|2|Qtd.Comp.AC|Quantidade de compra AC
ED8|49|ED8_SALISE|N|15|5|Sld.Isencao|Saldo de isencao
ED8|50|ED8_FASEDR|C|1|0|Fas.Drawback|Fase de drawback
ED8|51|ED8_DT_INT|D|8|0|Dt.Integrac.|Data da Integração
ED8|52|ED8_QT_AC2|N|15|2|Qtd.NCM AC|Quantidade de compra AC
ED8|53|ED8_ACISEN|C|13|0|Ato.Isencao|Ato de isencao
ED8|54|ED8_ISETOT|C|1|0|Isencao.Tot.|Isencao total
ED8|55|ED8_FORN|C|6|0|Fornecedor|Fornecedor do Insumo
ED8|56|ED8_LOJA|C|2|0|Loja|Loja do Fornecedor do ins
ED8|57|ED8_NMFORN|C|2|0|Desc. Forn.|Descrição do Fornecedor
ED8|58|ED8_VLII|N|15|2|I.I. R$|Valor II
ED8|59|ED8_VLIPI|N|15|2|I.P.I. R$|Valor IPI
ED8|60|ED8_VLICMS|N|15|2|I.C.M.S. R$|Valor ICMS
ED8|61|ED8_VLRPIS|N|15|2|Valor PIS|Valor PIS
ED8|62|ED8_VLRCOF|N|15|2|Valor COFINS|Valor COFINS
ED8|63|ED8_MOD_NF|C|6|0|Modelo NF|Modelo da Nota Fiscal
ED8|64|ED8_SEQMI|C|4|0|Seq. Sis. MI|Sequencia siscomex MI
ED8|65|ED8_SDOC|C|3|0|Série Doc.|Série do Documento Fiscal

