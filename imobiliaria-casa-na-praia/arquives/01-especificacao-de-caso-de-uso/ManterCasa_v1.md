
# ESPECIFICAÇÃO DE CASO DE USO

|   **Data**: 22/03/24    | **Autor**: Samuel Martins | **Versão**: 1         |
|:-----------------------:|:-------------------------:|:----------------------|
| **Identificação do UC** |       **Numero**: 2       | **Nome**: Manter Casa |

|  **Descrição**   | Este caso de uso deverá permitir que o ator faça inclusão, consulta e atualização e Exclusao de dados cadastrais das casas do Condominio. |
|:----------------:|:------------------------------------------------------------------------------------------------------------------------------------------|
|    **Atores**    | Cliente e Admin                                                                                                                           |
| **Pre-condição** | Para o cenário de incluir não há pré-condição, e para os demais cenários, a casa deverá estar previamente cadastrada                      |
| **Observações**  | Clientes e funcionarios podem apenas consultar Casas, enquanto Admin podem Criar, Atualizar e Excluir.                                    |


# ESPECIFICAÇÃO DE CENÁRIO DE CASO DE USO

| **Data**: 22/03/24            | **Autor**: Samuel Martins | Versão: 1                 |
|:------------------------------|---------------------------|:--------------------------|
| **Identificação do UC**       | **Numero**: 2             | **Nome**: Manter Casa  |
| **Identificação do Cenário**  | **Numero**: 1             | **Nome**: Incluir Casa |


|       **Descrição**       | Os atores incluem os dados dos clientes na base de dados do sistema                                                                                                                                                                                                                                                                                                                                                                                                |
|:-------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        **Atores**         | Admin                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Sequencia de Eventos**  | **1)** O Sistema deverá apresentar ao ator, a tela de inclusão.<br/> **2)** O ator digitará os dados no campos da tela de inclusao <br/> **3)** O sistema deverá fazer consistencias de todos os campos digitados de acordo com a sua caracteristicas. <br/> **4)** Quando o ator digitar o codigo da Casa, o sistema deverá verificar se a casa já existe na base de dados, caso já exista, seguir o caminho alternativo 01, caso não exista, incluir o registro. |
| **Caminhos alternativos** | **01)** Informar ao ator que aquele registro já existe no sistema.                                                                                                                                                                                                                                                                                                                                                                                                 |
|      **Observações**      | N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

---

|      **Data**: 22/03/24       | **Autor**: Samuel Martins |      **Versão**: 1      |
|:-----------------------------:|:--------------------------|:-----------------------:|
|    **Identificação do UC**    | **Numero**: 2             | **Nome**: Manter Casa   |
| **Identificação do Cenário**  | **Numero**: 2             | **Nome**: Alterar Casa  |

|       **Descrição**       | Os autores podem alterar os dados da casa na base de dados do sistema                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|:-------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        **Atores**         | Admin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Sequencia de Eventos**  | **1)** O sistema deverá apresentar ao ator a tela de alteração. <br/> **2)** O ator devera digitar o codigo da Casa a ser alterado. <br/> **3)** O sistema deverá procurar no banco de dados, a casa a ser alterada. Caso a casa nao seja encontrada, seguir o caminho alternativo 01. **4)** Ao encontrar o codigo da Casa, o sistema deverá apresentar na tela os dados da casa . <br/> **5)** Após o Admin digitar as alterações, o sistema deverá validar os campos alterados conforme as regras do cenário 01 (inclusao) e salvar os atributos modificados no banco do sistema. <br/> **5)** Caso tenha alguma incosistencia nos dados, seguir o caminho alterantivo 02 |
| **Caminhos alternativos** | **1)** Informar ao ator que aquele registro nao existe no sistema. <br/> **2)** Informar ao ator que os dados do cliente nao pode ser alterado pois existe inconsistencia nos atributos alterados                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|      **Observações**      | N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |


|      **Data**: 22/03/24       | **Autor**: Samuel Martins |      **Versão**: 1       |
|:-----------------------------:|:--------------------------|:------------------------:|
|    **Identificação do UC**    | **Numero**: 2             |  **Nome**: Manter Casa   |
| **Identificação do Cenário**  | **Numero**: 3             | **Nome**: Consultar Casa |

|       **Descrição**       | Os atores podem consultar os dados da casa na base de dados                                                                                                                                                                                                                                                             |
|:-------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        **Atores**         | Cliente e Admin                                                                                                                                                                                                                                                                                                         |
| **Sequencia de Eventos**  | **01)** O sistema deverá apresentar ao ator a tela de consulta <br/> **2)** O Ator deverá digitar o codigo da Casa a ser consultado <br/> 3) Caso o codigo da Casa nao seja encontrado, seguir caminho alterativo 01  <br/> **4)** Ao encontrar o codigo da Casa, o sistema deverá apresentar na tela os dados da casa. |
| **Caminhos alternativos** | **01)** Informar ao ator que aquele registro nao existe no sistema                                                                                                                                                                                                                                                      |
|      **Observações**      | N/A                                                                                                                                                                                                                                                                                                                     |

---

|      **Data**: 22/03/24       | **Autor**: Samuel Martins |       **Versão**: 1        |
|:-----------------------------:|:--------------------------|:--------------------------:|
|    **Identificação do UC**    | **Numero**: 2             |   **Nome**: Manter Casa    |
| **Identificação do Cenário**  | **Numero**: 4             |   **Nome**: Excluir Casa   |

|       **Descrição**       | Os atores podem excluir os dados da casa na base de dados do sistema                                                                                                                                                                                                                    |
|:-------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        **Atores**         | Admin                                                                                                                                                                                                                                                                                   |
| **Sequencia de Eventos**  | **1)** O sistema deverá apresentar ao ator a tela de exclusao. <br/> **2)** O ator deverá digitar o codigo da Casa a ser excluido. <br/> **3)** O sistema deverá procurar no banco, o cliente a ser excluido. Caso o codigo da Casa nao seja encontrado, seguir o caminho alterativo 01 |
| **Caminhos alternativos** | **1)** Informe ao ator que aquele registro nao existe no sistema.                                                                                                                                                                                                                       |
|      **Observações**      | N/A                                                                                                                                                                                                                                                                                     |
