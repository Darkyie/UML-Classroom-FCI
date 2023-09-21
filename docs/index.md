<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciências da Computação</a></h3>


<font size="+12"><center>
<h1>Sistema de Presenças 8000</h1>
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Análise de requisitos funcionais e não-funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de Componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Igor Benites Moura
* João Pedro Maia Matulevicius Garcia
* Ricardo Lins Pires

# Descrição do projeto
Nossa equipe é responsável por desenvolver um Sistema de Presenças para uma escola do Ensino Fundamental, visando atender às necessidades dos gestores da escola. As informações incluem detalhes sobre as turmas, alunos, professores e o processo de registro de presenças e ausências, com um requisito de 75% de presença para evitar reprovação por faltas.
*&lt;Introdução do projeto&gt;*

# Análise de requisitos funcionais e não-funcionais
**Requisitos Funcionais:**

* Registro de faltas: O sistema deve permitir que os professores registrem as faltas dos alunos de forma fácil e intuitiva.
* Relatórios de faltas: O sistema deve ser capaz de gerar relatórios de faltas agrupados por data, ano do ensino, turma, professor, disciplina ou aluno.
* Notificações: O sistema deve ser capaz de enviar notificações por e-mail para os pais ou responsáveis em caso de faltas excessivas (quando a porcentagem de comparecimento às aulas dadas até o momento estiver abaixo de 80%).

**Requisitos Não-Funcionais**

* Acessibilidade: O sistema deve ser acessível a todos os usuários, incluindo pessoas com deficiências. Deve ter recursos de acessibilidade como tamanho de fonte ajustável.
* Compatibilidade com navegadores web: O sistema deve ser compatível com todos os principais navegadores web e otimizado para dispositivos móveis.
* Desempenho: O sistema deve ser capaz de lidar com o número de alunos e professores da escola sem atrasos perceptíveis na interface do usuário.
* Segurança: O sistema deve seguir as melhores práticas de segurança para proteger os dados dos alunos.

# Diagrama de casos de uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos casos de uso

## **Caso de Uso: Registrar faltas**
**Ator:** Professor.
<br>**Descrição:** O professor seleciona a turma e a data através de uma interface. Em seguida, ele marca os alunos que estão ausentes. As informações são então salvas no sistema.<br>

## **Caso de Uso: Visualizar relatórios de faltas**

**Ator:** Professor.
<br>**Descrição:** O professor pode visualizar relatórios de faltas para suas turmas. Ele pode filtrar os relatórios por data, disciplina ou aluno.<br>

 


## **Caso de Uso: Visualizar relatórios de faltas**

**Ator:** Administrador da escola.
<br>**Descrição:** O administrador pode visualizar relatórios de faltas para todas as turmas e alunos. Ele pode filtrar os relatórios por data, ano do ensino, turma, professor, disciplina ou aluno.



## **Caso de Uso: Enviar notificações**

**Ator:** Administrador da escola.
<br>**Descrição:** O administrador pode enviar notificações por e-mail para os pais ou responsáveis quando a porcentagem de comparecimento às aulas estiver abaixo de 80%.



## **Caso de Uso: Receber notificações**

  **Ator:** Pais ou responsáveis.
  <br>**Descrição:** Os pais ou responsáveis recebem notificações por e-mail em caso de faltas excessivas.



# Diagrama de sequencia

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
