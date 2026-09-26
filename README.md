# Dashboard de vendas de assinaturas Xbox

Projeto desenvolvido para o desafio da DIO de criação de um dashboard de vendas no Excel. A planilha organiza os dados de assinaturas e apresenta indicadores e gráficos para apoiar a leitura dos resultados.

## Arquivos

- `dashboard_vendas_xbox.xlsx`: arquivo Excel com o dashboard, os cálculos e a base de dados usada.
- `README.md`: descrição do projeto e instruções para reproduzir ou atualizar a análise.

## Dados utilizados

A base didática fornecida pela DIO contém 295 registros de assinaturas, com datas de início entre janeiro e dezembro de 2024. Os campos incluem plano, periodicidade, renovação automática, preço da assinatura, vendas adicionais de EA Play e Minecraft, cupons e valor total.

O arquivo original pode ser baixado em [base.xlsx](https://hermes.dio.me/files/assets/805d54f9-6d53-4246-bed7-4aa2da615923.xlsx). A planilha final inclui uma cópia dos dados na aba **Base de Dados**. Os valores monetários foram mantidos em dólares americanos, como aparecem na base.

## O que o dashboard apresenta

- Faturamento total, quantidade de assinaturas, ticket médio e faturamento de planos anuais.
- Evolução mensal do faturamento, agrupada pela data de início da assinatura.
- Faturamento por plano e por periodicidade.
- Vendas de EA Play e Minecraft.
- Na aba **Análise**, faturamento anual separado por renovação automática, descontos e as tabelas que alimentam os gráficos.

Os valores principais calculados para a base fornecida são: faturamento total de **US$ 7.633,00**, **295** assinaturas, ticket médio de **US$ 25,87**, **US$ 1.754,00** em planos anuais, **US$ 2.940,00** em EA Play e **US$ 3.880,00** em Minecraft.

## Estrutura do arquivo Excel

1. **Dashboard**: indicadores e quatro gráficos vinculados aos resumos da aba Análise.
2. **Análise**: fórmulas e tabelas-resumo que agregam os dados por mês, plano, periodicidade e renovação.
3. **Base de Dados**: registros originais organizados em uma tabela do Excel.

## Como reproduzir no Excel

1. Baixe o arquivo de origem pelo link acima e abra `dashboard_vendas_xbox.xlsx`.
2. Consulte a aba **Base de Dados**. Ela contém os mesmos registros da base fornecida, com os cabeçalhos traduzidos para facilitar a leitura.
3. Na aba **Análise**, confira os cálculos: soma do valor total, contagem de assinaturas, ticket médio, somas condicionais por plano e periodicidade e agrupamento mensal pela data de início.
4. Para refazer os gráficos, use as tabelas-resumo da aba **Análise** como fonte. Os quatro gráficos do dashboard usam tabelas auxiliares nas colunas **T:U** da aba **Dashboard**, ligadas por fórmulas aos resumos.
5. Para atualizar os dados, substitua ou acrescente registros na tabela **Base de Dados**, mantendo a ordem e o significado das colunas. As fórmulas consideram linhas até a 1000. Se a base passar desse limite, amplie os intervalos das fórmulas na aba **Análise** e nas referências do dashboard.
6. O agrupamento mensal está configurado para 2024, período da base original. Para analisar outro ano, ajuste as datas das fórmulas mensais e os rótulos correspondentes.

## Publicar no GitHub

Crie um repositório chamado `dio-dashboard-vendas-xbox` e envie para ele `README.md` e `dashboard_vendas_xbox.xlsx`. Na página do repositório, use **Add file → Upload files**, selecione os dois arquivos e confirme em **Commit changes**. O endereço do repositório será `https://github.com/SEU-USUARIO/dio-dashboard-vendas-xbox`; substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub.
