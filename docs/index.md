# Calculadora de Notas

Alunos: Gabriel Henrique de Oliveira Campos , Bianca Ferreira Siqueira e Vitória Machado

## Requisitos funcionais:


`Cálculo da Nota Semestral:`

* O sistema deve calcular a nota semestral utilizando a fórmula NS = (N1 * 2 + N2 * 3) / 5.

`Verificação de Aprovação/Reprovação:`

* O sistema deve verificar se a nota semestral é igual ou superior a 70 para aprovação e inferior a 35 para reprovação.
* Se a nota estiver entre 35 e 70, o sistema deve direcionar para o exame final.

`Cálculo da Nota Final:`

* O sistema deve calcular a nota final utilizando a fórmula Nota Final = (NS * 3 + EF * 2) / 5, onde EF é a nota do exame final.
* Verificação de Aprovação na Nota Final:
* O sistema deve verificar se a nota final é igual ou superior a 50 para aprovação.

`Gerenciamento de Notas:`

* O sistema deve permitir que os alunos salvem as notas de cada disciplina (N1, N2, Exame Final) conforme são divulgadas.
* Os alunos devem poder visualizar as notas das disciplinas já cadastradas.
* Os alunos devem poder alterar as notas já cadastradas.
* Os alunos devem poder excluir uma disciplina cadastrada.

`Cálculo da Nota Mínima Necessária:`

* O sistema deve calcular a nota mínima necessária para aprovação em diferentes situações:
* Após a divulgação das notas do 1º bimestre.
* Após a divulgação das notas do 1º e 2º bimestres.
* Após a divulgação das notas finais para os alunos que ficaram de exame final.


## Requisitos não funcionais:

``Usabilidade:``

* O aplicativo deve ser fácil de usar e intuitivo para os alunos.
* Deve ter uma interface amigável e de fácil navegação.

``Segurança:``

* As informações das notas dos alunos devem ser armazenadas de forma segura e protegidas contra acessos não autorizados.

``Desempenho:``

* O sistema deve ter um desempenho rápido e eficiente no cálculo das notas e na exibição das informações.

``Disponibilidade:``

* O aplicativo deve estar disponível para acesso dos alunos sempre que necessário, sem interrupções significativas de serviço.

``Compatibilidade:``

* O aplicativo deve ser compatível com diferentes dispositivos, como computadores, tablets e smartphones, para facilitar o acesso dos alunos.

``Manutenção:``

* Deve ser fácil realizar atualizações e manutenções no sistema para garantir seu bom funcionamento ao longo do tempo.

## Diagrama de casos de usos

* A seguir temos a apresewntação do caso de uso da nossa aplicação: 
* [Link para visualização no LucidChart](https://lucid.app/lucidchart/740841c3-a1f7-41a5-ae29-69185dfd37a4/edit?invitationId=inv_6282b383-45e1-4c4f-a03b-204d4561398c&page=0_0#)


| Caso de Uso |
|----------|
| ![Caso de Uso](imagens/Caso_de_uso.png) |

## Especificação de caso dos casos de uso:

``Salvar Notas:``

* Descrição: Permite ao aluno salvar as notas de cada disciplina (N1, N2, Exame Final) assim que são divulgadas.
* Atores: Aluno

``Fluxo Principal:``

* O aluno acessa a função de salvar notas.
* O sistema solicita as notas de N1, N2 e Exame Final.
* O aluno insere as notas e confirma o salvamento.
* O sistema armazena as notas no banco de dados.

``Visualizar Notas:``

* Descrição: Permite ao aluno visualizar as notas das disciplinas já cadastradas.
* Atores: Aluno

``Fluxo Principal:``

* O aluno acessa a função de visualizar notas.
* O sistema exibe as notas de N1, N2 e Exame Final para cada disciplina cadastrada.

``Calcular Notas:``

* Descrição: Permite ao aluno calcular a nota mínima necessária para aprovação em diferentes situações.
* Atores: Aluno

``Fluxo Principal:``

* O aluno acessa a função de calcular notas.
* O sistema solicita informações relevantes para o cálculo (notas atuais, situação específica).
* O aluno fornece as informações necessárias.
* O sistema realiza o cálculo e exibe a nota mínima necessária para aprovação.

``Visualizar agenda:``

* Descrição: Permite ao aluno visualizar sua agenda de provas.
* Atores: Aluno

``Fluxo Principal:``

* O aluno acessa a função agenda.
* O sistema mostra sua agenda de provas do semestre.


## Prototipação da tela do app:

* A seguir podemos observar algumas telas criadas para representar nosso app, porém a visualização completa pode ser feita no link abaixo:
* [Link para visualização completa da protipação no figma](https://www.figma.com/file/PvOHqWEnZS1YCI6NsjqBgf/Trabalho-Luiz?type=design&node-id=0%3A1&mode=design&t=6IOMLsuhZB1JhUZa-1)

| Tela App |
|----------|
| ![Tela App](imagens/Figma_01.png) |
| ![Tela App](imagens/Figma_02.png) |
| ![Tela App](imagens/Figma_03.png) |
| ![Tela App](imagens/Figma_04.png) |
| ![Tela App](imagens/Figma_05.png) |

