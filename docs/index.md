<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciências da Computação</a></h3>


<font size="+12"><center>
<h1>Sistema de Presenças 8000</h1>
</center></font>


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


# Análise de requisitos funcionais e não-funcionais
**Requisitos Funcionais:**

* Registro de faltas: O sistema deve permitir que os professores registrem as faltas dos alunos de forma fácil e intuitiva.
* Relatórios de faltas: O sistema deve ser capaz de gerar relatórios de faltas agrupados por data, ano do ensino, turma, professor, disciplina ou aluno.
* Reprovação: Reprovar alunos que faltem em mais de 25% das aulas.
* Notificações: O sistema deve ser capaz de enviar notificações por e-mail para os pais ou responsáveis em caso de faltas ou reprovações. (quando a porcentagem de comparecimento às aulas dadas até o momento estiver abaixo de 80%).

**Requisitos Não-Funcionais**

* Acessibilidade: O sistema deve ser acessível a todos os usuários, incluindo pessoas com deficiências. Deve ter recursos de acessibilidade como tamanho de fonte ajustável.
* Compatibilidade com navegadores web: O sistema deve ser compatível com todos os principais navegadores web, incluindo navegadores para dispositivos móveis.
* Desempenho: O sistema deve ser capaz de lidar com o número de alunos e professores da escola sem atrasos perceptíveis na interface do usuário.
* Segurança: O sistema deve aderir às melhores práticas de segurança para proteger os dados dos alunos.
* Facilidade de uso: O sistema deve ter um sistema de filtro por data, disciplina ou aluno, para facilitar ao professor em caso de busca.
  
# **Diagrama de casos de uso**

![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/8d347c9f-2bbf-4ffe-88e7-c822a30a9d1d)


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
## Diagrama de uso do caso: Registrar faltas
![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/595bff26-eb76-4cb5-8efa-99b555cf93d5)

## Diagrama de uso do caso: Visualizar relatórios de faltas (Professor)
![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/dc90d039-dd17-4f62-af2c-8d0f0888c0d9)
## Diagrama de uso do caso: Visualizar relatórios de faltas (Administrador)
![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/d7f27424-e38c-4990-8273-4da0088bced7)
## Caso de Uso: Enviar notificações
![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/5c2fb05d-8370-407f-82b2-d650e2709044)
## Caso de Uso: Receber notificações
![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/4557fbf5-af4f-45ee-84c7-564b40fbbb9d)


# Diagrama de classes

![image](https://github.com/Darkyie/UML-Classroom-FCI/assets/88231773/72b80d7f-47c7-490f-bcd0-724a6c67d17a)


# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
