## Módulo: SIGAREST (Gestão de Restaurantes / Bares)  
--- ### NT0  
X3_ARQUIVO|X3_ORDEM|X3_CAMPO|X3_TIPO|X3_TAMANHO|X3_DECIMAL|X3_TITULO|X3_DESCRIC  
NT0|01|NT0_FILIAL|C|6|0|Filial|Filial do Sistema
NT0|02|NT0_COD|C|6|0|Código|Código do contrato
NT0|03|NT0_NOME|C|200|0|Descrição|Descrição do contrato
NT0|04|NT0_CGRPCL|C|6|0|Cód Grp Cli|Código Grupo de Clientes
NT0|05|NT0_DGRPCL|C|30|0|Desc Grp Cli|Descrição Grupo Clientes
NT0|06|NT0_CCLIEN|C|6|0|Cl Principal|Cliente Principal
NT0|07|NT0_CLOJA|C|2|0|Cód Loja|Código da loja
NT0|08|NT0_DCLIEN|C|80|0|Nome cliente|Nome do cliente
NT0|09|NT0_SIGLA1|C|5|0|Sócio Resp.|Sigla Sócio responsável
NT0|10|NT0_CPART1|C|6|0|Cód Sócio|Código do Sócio
NT0|11|NT0_DPART1|C|50|0|Nome Sócio|Nome do Sócio
NT0|12|NT0_RELPRE|C|4|0|Cod Rel Pre|Cod Relatorio Pre
NT0|13|NT0_DRELPR|C|50|0|Desc Rel Pre|Desc Relatório Pré
NT0|14|NT0_CMOE|C|2|0|Moeda Préfat|Moeda da Pré-fatura
NT0|15|NT0_DMOE|C|10|0|Símb moeda|Símbolo da moeda
NT0|16|NT0_CESCR|C|5|0|Cód Esc Fat|Cód Escritório a Faturar
NT0|17|NT0_DESCR|C|100|0|Des Escr Fat|Desc Escritório a Faturar
NT0|18|NT0_CRELAT|C|4|0|Cód Relat|Cód Tipo de Relatório
NT0|19|NT0_DIDIO|C|100|0|Des Idi PreF|Desc Idioma Pré-Fatura
NT0|20|NT0_DRELAT|C|50|0|Desc Relat|Desc Tipo de Relatório
NT0|21|NT0_CIDIO|C|2|0|Cód Idi PreF|Código Idioma Pré-Fatura
NT0|22|NT0_DTINC|D|8|0|Dt Criação|Data Criação do Contrato
NT0|23|NT0_USRINC|C|30|0|Usuário inc|Usuario de inclusão
NT0|24|NT0_DTVIGI|D|8|0|Vigência Ini|Data Inicial da Vigência
NT0|25|NT0_DTVIGF|D|8|0|Vigência Fin|Data Final da Vigência
NT0|26|NT0_CTPHON|C|3|0|Cód honor|Cód tipo de honorários
NT0|27|NT0_DTPHON|C|100|0|Desc honor|Desc tipo de honorários
NT0|28|NT0_DESPES|C|1|0|Cob despesas|Cobrar despesas
NT0|29|NT0_SERTAB|C|1|0|Cobrar serv|Cobrar serviços tabelados
NT0|30|NT0_ENCH|C|1|0|Enc cob hon|Enc cobrança honorários
NT0|31|NT0_ENCD|C|1|0|Enc cob desp|Enc cobrança despesas
NT0|32|NT0_ENCT|C|1|0|Enc cob serv|Enc cobrança tabelados
NT0|33|NT0_CONTR|C|1|0|Contrato|Contrato
NT0|34|NT0_SIT|C|1|0|Situação|Situação do contrato
NT0|35|NT0_REV|C|1|0|Revisado?|Contrato revisado?
NT0|36|NT0_CMOELI|C|2|0|Cód Moeda|Moeda do valor limite
NT0|37|NT0_DMOELI|C|10|0|Desc Moeda|Desc moeda valor limite
NT0|38|NT0_VLRLI|N|13|2|Valor Limite|Valor limite
NT0|39|NT0_VLRLIF|N|13|2|Limite Fat|Valor limite por fatura
NT0|40|NT0_SALDOI|N|13|2|Vlr Util Lim|Valor Utilizado Limite
NT0|41|NT0_DTBASE|D|8|0|Data Base|Data base do contrato
NT0|42|NT0_DISPON|N|13|2|Disponível|Valor Disponível
NT0|43|NT0_CMOEF|C|2|0|Cód Moeda|Moeda do fixo
NT0|44|NT0_DMOEF|C|10|0|Desc Moeda|Desc moeda do fixo
NT0|45|NT0_VLRBAS|N|13|2|Valor Base|Valor base da Parcela
NT0|46|NT0_VALORA|N|13|2|Vlr Base Atu|Valor base atualizado
NT0|47|NT0_DATAAT|D|8|0|Dt Atu Base|Data de atualização
NT0|48|NT0_PERFIX|N|14|0|Per Cobranca|Periodicidade do cob fixo
NT0|49|NT0_PEREX|N|14|0|Per Excedent|Periodicidade cob exced
NT0|50|NT0_TPCEXC|C|1|0|Tp Cob Exc|Tipo de cob excedente
NT0|51|NT0_LIMEXH|N|14|2|Lim Horas|Limite tipo exc por H
NT0|52|NT0_PERCD|N|13|2|% Desc Exc|% desc tipo exced valor
NT0|53|NT0_PARFIX|C|1|0|Parc fixas?|Parcelas fixas?
NT0|54|NT0_FINAJU|C|1|0|Cob no final|Cobrar no fim do Caso
NT0|55|NT0_FIXEXC|C|1|0|Fixo e exc|Fixo e excedente juntos?
NT0|56|NT0_TPFX|C|1|0|Tipo Faixa|Tipo de faturamento faixa
NT0|57|NT0_CALFX|C|1|0|Tipo Cálculo|Calc faturamento faixa
NT0|58|NT0_CASPRO|C|1|0|Qtdade por?|Qtd Casos ou Processos?
NT0|59|NT0_COPFAT|C|254|0|Copia Fatura|Copia Fatura
NT0|60|NT0_FXENCM|C|1|0|Enc período?|Considera encerra no per?
NT0|61|NT0_FXABM|C|1|0|Aber períod?|Considera abertos no per?
NT0|62|NT0_DESPAD|N|12|8|% Desc Lin.|Perc. de desconto Linear
NT0|63|NT0_TPERCD|C|1|0|Tp Perc Desc|Tipo do perc de desconto
NT0|64|NT0_DTREFI|D|8|0|Ref Inicial|1ª dt referência inicial
NT0|65|NT0_DTREFF|D|8|0|Dt ref fim|1ª dt referência Final
NT0|66|NT0_QTPARC|N|11|0|Qtd Parcelas|Quantidade de parcelas
NT0|67|NT0_DTVENC|D|8|0|Prim Vencto|Primeira data de Vencimen
NT0|68|NT0_DIAEMI|N|2|0|Dia Máx Emi|Dia Máximo Emissão Fatura
NT0|69|NT0_DISCAS|C|1|0|Discr caso|Discrimina casos na fatur
NT0|70|NT0_TITFAT|C|200|0|Título Fatu|Título de Faturamento
NT0|71|NT0_DTENC|D|8|0|Data encerra|Data encerramento
NT0|72|NT0_ATIVO|C|1|0|Ativo?|Ativo?
NT0|73|NT0_TPVDIV|C|1|0|Tipo Divisão|Tipo de Divisão Vínculo
NT0|74|NT0_VALDIV|N|16|2|Vlr. Divisão|Valor da Divisão
NT0|75|NT0_TPCORR|C|1|0|Tp Correção|Tipo de Correção
NT0|76|NT0_PERCOR|N|14|0|Per Correção|Periodicidade correção
NT0|77|NT0_CINDIC|C|2|0|Cód Índice|Código do índice
NT0|78|NT0_DINDIC|C|10|0|Desc Índice|Descrição do índice
NT0|79|NT0_DESPAR|C|4|0|Cód Des Parc|Cód Desc Parcela
NT0|80|NT0_OBS|M|10|0|Observação|Observação
NT0|81|NT0_PARCE|C|1|0|Parcelar?|Parcelar?
NT0|82|NT0_DECPAR|C|100|0|Desc Parcela|Descrição das Parcelas
NT0|83|NT0_CFXCVL|C|1|0|Fixo Lim?|Fixo Limite?
NT0|84|NT0_CTBCVL|C|1|0|Serv Tb Lim?|Serv. Tabelado Limite?
NT0|85|NT0_CTIPOF|C|3|0|Cód Tp Fat|Código Tipo de Fatura
NT0|86|NT0_DTIPOF|C|100|0|Desc Tp Fat|Descrição Tipo de Fatura
NT0|87|NT0_PONUMB|C|100|0|PO Number|PO Number E-bill 1998BI
NT0|88|NT0_SERVIC|M|10|0|Frase Servic|Frase de Serviços
NT0|89|NT0_CASMAE|C|1|0|Aloc unific?|Alocação unificada?
NT0|90|NT0_CCLICM|C|6|0|Cód Cliente|Cliente agrupa caso mãe
NT0|91|NT0_CLOJCM|C|2|0|Cód Loja|Cód Loja agrupa caso mãe
NT0|92|NT0_CCASCM|C|6|0|Cód Caso Mãe|Cód Caso agrupa caso mãe
NT0|93|NT0_CFACVL|C|1|0|Fat Adi Lim?|Fat Adicional Limite?
NT0|94|NT0_CEXCVL|C|1|0|Êxito Lim?|Êxito Limite?
NT0|95|NT0_TPSERV|C|2|0|Tipo Serviço|Classif. Tipo de Serviço
NT0|96|NT0_FIXREV|C|1|0|Revisa Fixo?|Revisa as parcelas fixas?
NT0|97|NT0_TPFECH|C|3|0|Tipo Fecham.|Tipo de Fechamento
NT0|98|NT0_DESFET|C|50|0|Des. Fecham.|Desc. do Fechamento
NT0|99|NT0_SUGPLD|C|1|0|Sugere no LD|Sugere contrato no LD?

