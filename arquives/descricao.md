# Descrição
Uma imobiliária possui um conjunto de casas em um condomínio na praia para alugar em temporada de férias ou feriados.
Quando um cliente deseja alugar uma casa, ele realiza uma reserva para uma data ou período específico.
O cliente Arecebe o código da reserva e um boleto bancário**, com o número do boleto, a data de vencimento e o valor do
aluguel. O boleto deve ser pago no banco para que a reserva seja confirmada e, com o código da reserva, o cliente se
apresenta na recepção do condomínio quando for hospedar-se. A reserva indica, para o condomínio,
o número da casa reservada. Ao chegar no condomínio, este código  é apresentado ao  funcionário da recepção  que
identifica qual a casa se refere aquela reserva. Durante a estadia do cliente, são registradas as despesas do hóspede
na lanchonete do condomínio, para que se possa efetuar a cobrança no momento da saída. No momento em que o hóspede pede
para fechar a conta, todas as despesas são totalizadas e é gerada uma nota fiscal.

# Requisitos do Usuario
> Necessidades identificadas no texto criado pelo usuário

- Controlar a reserva por data ou periodo
- Seja emitido um codigo de reserva
- Seja emitido um boleto bancario
- Seja emitido o numero da casa na reserva
- Confirmar se o boleto do usuario foi pago
- Controlar despesas do hospede na lanchonete
- Emitir nota fiscal com todos os gastos do hóspede

#  Requisitos do usuário – Regras de Negócio
> Regras identificadas para cada requisito do usuario

## Controlar a reserva por data ou periodo
- Todos os acessos ao sistema deve ser feito através de um usuário e senha
- Tanto clientes quanto administradores devem estar logados no sistema.

## Seja emitido um codigo de reserva
- Ao efetuar a reservar da casa.
- Codigo unico em formato UUID

## Seja emitido um boleto bancario
- Ao efetuar a reservar da casa.
- Numero do boleto
- Data de vencimento
- Valor do aluguel.

## Seja emitido o numero da casa na reserva
- Ao efetuar a reservar da casa.
- Numero da casa

## Confirmar se o boleto do usuario foi pago
- Validar se o boleto foi pago

## Controlar despesas do hospede na lanchonete
- Todos os acessos ao sistema deve ser feito através de um usuário e senha.
- Somente funcionarios teram acesso as comandas virtuais
- Comanda atrelada ao CPF do hóspede

## Emitir nota fiscal com todos os gastos do hóspede
- seja emitido nota fiscal contendo todos os gastos da lanchonete


# Funcionalidades identificadas
> Funcionalidades identificadas de acordo com os requisitos do usuario

- CRUD de Hóspedes
- CRUD de Casas
- Validacao de CPF
- Geração de Codigo de reserva
- Geração de boleto bancario
- Controle de disponibilidade das casas
- Validacao de boleto pago
- CRUD despesas dos hospedes
- Geração de Notas Fiscal

# Diagrama de casos de Uso
> Diagrama visual dos casos de uso, disponivel em outra pasta
