📊 ## Financial Reader
Análise e Extração de Metadados de Arquivos OFX
O UEX Financial Reader é uma ferramenta de front-end de alta performance projetada para converter arquivos bancários complexos (formato .ofx) em uma interface visual legível, organizada e técnica.

Diferente de leitores comuns, este projeto foca na extração de metadados e na integridade dos dados, sendo essencial para profissionais que precisam validar massa de dados bancários rapidamente.

🎯 Para que serve este projeto?
1. Validação de Massa de Dados (QA/Testes)
Para analistas de teste, validar se um arquivo OFX foi gerado corretamente é um desafio. Esta ferramenta permite:

Verificar se o FITID (ID único da transação) está presente e único.

Validar se as tags de Agência (BRANCHID) e Conta (ACCTID) foram extraídas corretamente.

Confirmar se os valores de débito e crédito batem com o esperado sem abrir o código bruto do arquivo.

2. Análise Financeira Rápida
Transforma um arquivo de texto difícil de ler em um painel de estatísticas em tempo real:

Balanço Líquido: Calcula automaticamente a diferença entre entradas e saídas.

Contagem de Transações: Exibe o volume total de movimentações no período.

Visualização Estilizada: Diferencia débitos de créditos visualmente para evitar erros de interpretação.

3. Segurança e Privacidade
Como o projeto é construído em JavaScript Puro (Client-side):

O arquivo não é enviado para nenhum servidor.

A leitura acontece inteiramente no navegador do usuário.

Garante conformidade com normas de privacidade de dados sensíveis.

🛠 Diferenciais Técnicos
Zero Dependências de Backend: Funciona como uma aplicação estática (GitHub Pages).

Tailwind CSS: Interface moderna, responsiva e com suporte a "Dark Mode".

Regex Engine: Motor de busca por expressões regulares customizado para garantir que as tags OFX sejam encontradas mesmo em arquivos com formatações variadas.

📂 Como utilizar
Acesse o link do projeto.

Faça o upload do arquivo .ofx.

Analise os cards de estatísticas no topo e a tabela detalhada logo abaixo.
