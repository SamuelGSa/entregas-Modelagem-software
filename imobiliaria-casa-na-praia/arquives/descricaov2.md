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

- Controlar reserva por data ou periodo
- Emissão de boleto bancario
- Confirmação de reserva
- Identificação da Casa Reservada
- Controlar despesas na lanchonete
- Emissão de nota fiscal

#  Requisitos do usuário – Regras de Negócio
> Regras identificadas para cada requisito do usuario

## Controlar reserva por data ou periodo
- O cliente pode solicitar uma reserva para uma data ou período específico.
- A reserva deve ser feita para uma casa disponível no condomínio.
- A reserva só pode ser confirmada após o pagamento do boleto bancário.

## Emissão de boleto bancario
- Ao efetuar a reservar da casa.
- Numero do boleto
- Data de vencimento
- Valor do aluguel.

## Confirmação de reserva
- Após a solicitação de reserva, é gerado um boleto. O boleto deve ser pago para confirmar a reserva.

## Identificação da Casa Reservada
- Cada reserva está associada a um código único.
- Esse código é apresentado na recepção do condomínio para identificar a casa reservada.

## Controlar despesas na lanchonete
- Durante a estadia do cliente, as despesas na lanchonete do condomínio são registradas.
- Essas despesas serão cobradas no momento da saída.

## Emissão de nota fiscal
- Ao fechar a conta do hóspede, é gerada uma nota fiscal contendo todas as despesas registradas durante a estadia

---

# Funcionalidades identificadas
> Funcionalidades identificadas de acordo com os requisitos do usuario

- Cadastro e Manutenção da conta do Usuário:
- Cadastro e Manutenção da conta de Funcionarios:
- Consulta de Disponibilidade de Casas
- Solicitação de Reserva
- Geração de Boleto Bancário
- Confirmação de Reserva
- Identificação da Casa Reservada
- Registro de Despesas na Lanchonete
- Emissão de Nota Fiscal
- Notificação de Reservas Pendentes



# Diagrama de casos de Uso
> Diagrama visual dos casos de uso, disponivel em outra pasta
> 
