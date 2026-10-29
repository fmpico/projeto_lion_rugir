# LION RUGIR 🦁

**Planilha Excel para organização de informações financeiras e fiscais de pessoa física.**

O **LION rugIR** é um modelo de pasta de trabalho desenvolvido no Microsoft Excel para reunir, em um único lugar, dados cadastrais, informes bancários, receitas e pagamentos ao longo do ano. Seu objetivo é facilitar a organização dos documentos e a conferência das informações que podem ser necessárias na preparação da declaração de Imposto de Renda da Pessoa Física (IRPF).

> **Aviso:** esta planilha é uma ferramenta de organização. Não realiza a declaração do IRPF, não substitui o programa ou os serviços oficiais da Receita Federal e não constitui orientação contábil ou tributária.

## Funcionalidades

- Organização dos dados de identificação do contribuinte.
- Registro de informes de rendimentos bancários, com totalização dos valores informados.
- Controle de entradas de receitas, com data, categoria e valor.
- Registro de pagamentos, beneficiários, valores pagos e parcelas não dedutíveis.
- Consulta uma tabela auxiliar de códigos de pagamentos e uma relação de códigos bancários.
- Listas suspensas em determinados campos para padronizar o preenchimento.
- Aba com orientações de utilização.
- **Sem macros VBA:** o arquivo utiliza funcionalidades nativas do Excel.

## Estrutura da planilha

| Aba | Finalidade |
| --- | --- |
| `TITULAR` | Dados cadastrais e informações de identificação do contribuinte. |
| `INFORMES` | Registro de instituições financeiras, valores e referências a documentos de rendimentos. |
| `RECEITAS` | Lançamento de receitas por data, categoria e valor. |
| `PAGAMENTOS` | Registro de pagamentos e despesas, com código, beneficiário e valores. |
| `LISTAS` | Consulta aos códigos e descrições de pagamentos e a códigos bancários. |
| `COMO USAR ESSA PLANILHA` | Orientações para o preenchimento das demais abas. |

## Como utilizar

1. **Baixe o arquivo `.xlsx`** disponível no repositório e abra-o no Microsoft Excel.
2. Na aba **TITULAR**, preencha os dados de identificação necessários.
3. Em **INFORMES**, registre as informações de cada instituição financeira e confira o total apresentado.
4. Em **RECEITAS**, lance os recebimentos com suas datas, categorias e valores.
5. Em **PAGAMENTOS**, informe o código, os dados do beneficiário e os valores correspondentes. Para identificar o código adequado, consulte a aba **LISTAS**.
6. Consulte **COMO USAR ESSA PLANILHA** para obter orientações adicionais e revise todos os registros antes de utilizá-los em qualquer procedimento fiscal.

**Observação:** na versão atual, o código de pagamento é informado manualmente na aba `PAGAMENTOS`, com apoio da consulta à aba `LISTAS`. Não há janela de pesquisa por macro nem preenchimento automático do código por descrição.


## Tecnologias e recursos utilizados

- Microsoft Excel (`.xlsx`)
- Fórmulas de planilha
- Validação de dados e listas suspensas
- Formatação de células e organização em abas

## Limitações

- A planilha **não transmite informações** à Receita Federal e **não calcula automaticamente o imposto devido**.
- Os códigos de pagamentos e as regras de dedutibilidade devem ser conferidos com as orientações oficiais aplicáveis ao **ano-calendário e exercício** da declaração.
- A existência de um campo ou código não garante que determinada despesa seja dedutível.
- O modelo não substitui a revisão por profissional habilitado quando necessária.

## Próximas melhorias possíveis

- Aperfeiçoar a consulta e a seleção de códigos sem acrescentar colunas à aba de pagamentos.
- Ampliar as validações de preenchimento.
- Proteger células com fórmulas sem impedir a edição dos campos de entrada.
- Criar resumos e indicadores para facilitar a conferência dos registros.

## Contribuições

Sugestões, relatos de problemas e propostas de melhoria podem ser registrados nas **Issues** do repositório. Ao compartilhar exemplos, remova previamente qualquer dado pessoal ou financeiro.



