<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Sistema De Presenças Escola Infinito
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Enrico Najjar Galdeano - 32260407
* Mauricio Gabriel Gutierrez Garcia - 32266601
* Rodrigo Mironiuc Fernandes - 32274823

# Descrição do projeto

O projeto se trata da implementação de um sistema de controle de presença dos alunos da Escola Infinito, uma escola de turmas de Ensino Fundamental 2. O sistema de presenças pode ser usado para registrar o controle da frequência dos alunos nas aulas ao longo do ano letivo e gerar relatórios específicos a qualquer momento. Além disso, é capaz de controlar automaticamente a frequência de cada um dos alunos, notificando diretamente aos responsáveis caso seja necessário.

# Análise de requisitos funcionais e não-funcionais
Requisitos Funcionais:
- Permitir que professores registrem faltas de forma fácil e intuitiva.
- Gerar relatórios de faltas agrupados por data, ano do ensino, turma, professor, disciplina ou aluno.
- Notificar por e-mail pais ou responsáveis se comparecimento às aulas dadas até o momento for menor de 80%.
- Oferece recursos de acessibilidade para PCD. Exemplo: tamanho de fonte ajustável.
- A chamada será realizada duas vezes ao dia.
- O número de estudantes por sala de aula pode variar quando as chamadas são feitas.
- O estudante precisa comparecer em ao menos 75% das aulas para ser aprovado no fim do ano.


Requisitos Não – Funcionais:
- O sistema deve estar vinculado à um banco de dados.
- O banco de dados deve ser atualizado constantemente.
- O acesso do usuário deve ser sempre controlado por um tipo de cadastro.
- O sistema deve ser compatível com qualquer navegador Web e poderá ser acessado também por dispositivos móveis.
- Mais de um usuário pode acessar de forma síncrona.
- Tempo de manutenção / atualização dos dados, deve ser curto e em horários de pouco acesso.

# Diagrama de casos de uso

  ![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/fe5c856c-60f1-4a52-a8e5-536448c83479)


# Descrição dos casos de uso

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/937af51c-fb5b-4d26-98de-95678505179f)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/7832d6e9-7d6e-430b-ba17-f4d846461264)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/56a2b8c8-bfbd-43c4-8609-a2f53d65a7aa)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/81862148-f021-4370-98ed-6bf99e8743c7)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/6364c400-0e79-40c9-9813-c9787ca9681d)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/3c318bfb-cfe1-4492-8fb3-8607c3f5fc41)

# Diagrama de sequencia

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/0036fa2f-b59a-4464-9555-3414eba8373d)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/6530d790-854c-49e8-839a-d4ca3c6b84c0)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/d9115340-20d7-40e4-90d7-965858b8fd92)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/80ef6752-3ce0-4c7b-9250-1b0440c28623)

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/142501084/a6dc7a98-e0c1-4a55-9051-5934cf13410f)


# Diagrama de classes

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/100619939/c26a03e8-c318-4ff7-90cf-dfa72846d3aa)


# Diagrama de Componentes

![image](https://github.com/rodmironiuc/UML-SistemaDePresencas-EscolaInfinito/assets/100619939/cb03144e-a7b9-4881-b91a-6be5a1923cf5)


# Decisões de arquitetura

Decisões de arquitetura


     Este documento explicará as decisões de arquitetura que foram tomadas na criação dos diagramas UML necessários para atender às demandas do Sistema de Presenças da Escola Infinito:


Diagrama de casos de uso: Este diagrama representa as interações entre os atores, que neste caso são os professores, alunos e pais/responsáveis. Alguns dos casos de uso são, por exemplo, os registros de faltas, a geração de relatórios de faltas, o cálculo da porcentagem de faltas e o envio de uma notificação para os pais. Essas decisões foram tomadas para conectar todos os atores, levando em consideração as responsabilidades e necessidades de cada um.

Diagrama de Sequência: Este diagrama mostra as interações entre os objetos ao longo do uso do sistema. Ele foi dividido em cinco diagramas para gerar relatório de faltas, gerar recursos de acessibilidade, registrar faltas/presenças, calcular a porcentagem de faltas e para o envio de notificações. Nestes diagramas, buscamos representar de forma mais clara as interações entre os atores, visando também a eficácia das ações do usuário. Estamos buscando a melhor experiência do usuário e garantir que o sistema atenda às suas necessidades de maneira eficiente e eficaz.

Diagrama de Classes: O diagrama de classes representa a relação entre diferentes classes, seus atributos e métodos. Nele são representados as classes Professor, Acessibilidade, Relatório de Faltas, Porcentagem de faltas, Pais e Responsáveis. Este diagrama serve para entender e mostrar a estrutura organizacional, como os objetos interagem entre si no sistema, e fazer uma representação mais realista possível das entidades envolvidas.

Diagrama de Componentes: Este diagrama mostra os componentes de um sistema e como eles interagem entre si. Ele ajuda a visualizar a estrutura do sistema e como os componentes estão conectados.

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências
* Material disponibilizado pelo professor.
* https://creately.com/diagram-community/examples/t/sequence-diagram

