Projeto feito com base no arquivo CSV de Cancelamentos.

Após a instalação do Pandas e Plotly foi identificado o seguinte:

- Clientes com mais de 50 anos tendem a cancelar;
- Clientes com contrato mensal tendem a cencelar;
- Clientes com pagamento em atraso de mais de 20 dias tendem a cancelar.
- Clientes que ligam mais de 4 vezes no callcenter tendem a cancelar.

Após estes findins foram levantadas as seguintes melhorias:
    1 - Buscar publico alvo de clientes com idade menor de 50 anos.
    2 - Ao inves de oferecer contratos mensais, oferecer anuais e trimestrais.
    3 - Quando o cliente estiver em atraso, antes dos 20 dias fazer um plano de ação de cobrança.
    4 - Criar um alerta para quando o cliente ligar mais de 3 vezes para na 4 ligação conseguir resolver o problema.


Caso queira replicar o passo a passo, observar os comentários dentro do código. Utilizar a base cancelamentos.csv. (foi postado a sample, para questões de conseguir upar para o GitHub)

att,
Marcos