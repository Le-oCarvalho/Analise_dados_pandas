# Analise_dados_pandas
 Repositório com projeto simples de Análise de Dados
 A premissa do desafio é a seguinte:
 
 Uma empresa de telecom tem clientes de vários serviços diferentes, entre os principais: internet e telefone.
 
O problema é, analisando o histórico dos clientes dos últimos anos, percebe-se que a empresa está com Churn (cancelamentos) de mais de 26%.
Isso representaria uma perda de milhões para a empresa.

O que a empresa precisa fazer para resolver isso?

Para fazer a analise utilizamos a biblioteca Pandas, juntamente com Jupyter Notebook;
A escolha do Jupyter para a escrita do código se dá pela melhor visualização das tabelas e a capacidade de dividir cada parte da análise em células separadas;

Conclusões da análise e possiveis ações:

- Clientes com contrato mensal tem maior chance de cancelar:
    - Fazer promoções para o cliente ir para o contrato anual/semestral
    
- Familias maiores tendem a cancelar menos do que famílias menores:
    - Criar e oferecer planos mais convidátivos para pessoas que vivem sozinhas e/ou com familias menores
    
- MesesComoCliente baixos tem MUITO cancelamento. Clientes com pouco tempo de serviço tendem a cancelar muito:
    - A primeira experiência do cliente na operadora pode ser ruim
    - Talvez a captação de clientes está trazendo clientes fora do padrão de serviço
    - Ideia: criar incentivo para que os clientes fiquem mais tempo como usuário
    
- QUanto mais serviços o cliente tem, menor a chance de cancelar:
    - fazer promoções com mais serviços pro cliente
    
- Algo no serviço de Fibra está fazendo os clientes cancelarem:
    - Agir sobre a fibra
    
- Clientes no boleto tem MUITO mais chance de cancelar:
    - Buscar meios ou oferecer incentivos para que os usuários mudem a forma de pagamento 
