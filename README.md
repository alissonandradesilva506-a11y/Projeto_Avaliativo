# Projeto_Avaliativo
Alisson Araujo Andrade Silva Filho.
Projeto de Banco de Dados.
Anderson Soares Costa.

# Tecnologias utilizadas
PostgreSQL e Python através de Supabase e Google Colab.

O projeto é focado na criação de um banco de dados para uma rede de hotéis, guardando os dados dos clientes e das reservas.
O sistema foi criado principalmente para salvar os dados dos clientes dessa rede e auxiliar no gerenciamento de 
reservas, cálculo de preços das reservas, tantos para as diárias normais e com descontos inseridos por promoções
do sistema.

# Tabelas
Hospedes: Os clientes da rede de hotéis e os dados importantes para identificação(nome) e comunicação(email e número).
Reservas: As reservas feitas nos hotéis com as datas, valor de diária e status.

# Views
vw_reservas_ativas:
vw_resumo_gastos_hospedes:
vw_faturamento_mensal_projetado:
# Functions

# Procedures
pr_calcular_valor_descontado: Aplica um desconto no preço total da reserva baseado em um desconto que a empresa insere.
pr_criar_reserva: Permite a criação de uma reserva pelo hóspede.
pr_cancelar_reserva: Permite que o cliente cancele uma reserva específica.
pr_finalizar_reserva: Atualiza o status da reserva para 'FINALIZADA' quando a data de término chegar.
pr_alterar_valor_diaria: Altera o valor da diária de uma reserva específica.

# Como Executar
Inserir as tabelas e inserts em um programa como o Supabase para salvar os dados dentro deles e inserir
as views, functions e procedures para testá-las.
