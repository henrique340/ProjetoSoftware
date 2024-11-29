<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema de presença Gupo&gt;*
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do Projeto](#descrição-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
- [Descrição dos Casos de Uso](#descrição-dos-casos-de-uso)
- [Diagrama de Senquencia](#diagrama-de-sequência)
- [Diagrama de Classes](#diagrama-de-classes)
- [Diagrama de Estados](#diagrama-de-estados)
- [Diagrama de Implantação](#diagrama-de-implantação)

# Autores

* André Sapucaia                 10418734
* Bernardo Souza Oliveira        10312871
* Henrique Yuji Isogai Yoneoka   10418153


# Descrição do Projeto

O projeto consistirá de um sistema de presença para a escola INFINITO. Ele terá que computar as faltas dos alunos de todas as turmas da escola (do primeiro ao quinto ano do ensino fundamental). Haverá um professor que é responsável por ministrar as disciplinas .</br> Esse sistema deverá gerar um relatório de faltas organizados por diversas categorias, como data, ano de ensino, turma, professor, disciplina ou aluno. Nessa escola, a chamada é feita duas vezes ao dia, já que a maior parte das matérias é ministrada pelo mesmo professor. Caso o aluno termine o ano com menos de 75% de presença, o sistema deverá considerá-lo como "reprovado por faltas". Portanto, a partir do momento em que o aluno tiver uma porcentagem de presença menor do que 80%, o sistema deverá enviar uma notificação aos responsáveis do aluno avisando que ele está próximo do limite de faltas.</br> Adicionalmente, o sistema deverá ser inclusivo, de forma que pessoas portadoras de deficiências físicas sejam capazes de utilizá-lo sem dificuldades com o aumento do tamanho dos textos e uma opção para ouvir as funcionalidades em áudio, de forma que os usuários consigam utilizá-lo de forma prática, e por meio de qualquer navegador web.

# Análise de Requisitos Funcionais e Não-Funcionais
[RF001  - Login]: O usuário deve ser capaz de entrar no sistema utilizando o nome de usuário e senha.</br>
[RF002  -  Cadastro]: O usuário deve ser capaz de criar uma conta no sistema inserindo os dados pessoais.</br>
[RF003  -  Registro de faltas]: O sistema deve permitir que o professor registre as faltas dos alunos duas vezes por dia</br>
[RF004  -  Relatório de faltas]: O sistema deve permitir que o professor gere relatorios capaz de visualizar as faltas organizadas em datas, turmas, disciplinas, professor, ano de ensino e faltas.</br>
[RF005  -  Notificação ao responsável]: O sistema deve enviar uma notificação por e-mail ao responsável do aluno quando o mesmo atinge 80% de presença.</br>
[RF006  -  Visualizar perfil]: O aluno, o professor e o responsável deve ser capaz de acessar o perfil do aluno com as suas informações.</br>
[RF007  -  Pesquisar aluno]: O professor deve ser capaz de encontrar o aluno desejado por nome e turma.</br>
[RF008  -  Gestão de turmas]: O sistema deve permitir a criação e gerenciamento de turmas, alocando alunos e professores em cada turma.</br>
[RF009 - Exportação de relatórios]: O sistema deve permitir a exportação de relatórios de faltas e presenças em formatos como PDF ou Excel.</br>
[RF010 - Níveis de acesso]: O sistema deve suportar diferentes níveis de acesso, como administrador, professor, aluno e responsável, com permissões específicas para cada perfil.</br>



[RNF001  -  Configuração]: O sistema deve ser capaz de suportar minimamente 300 computações de falta por dia</br>
[RNF002  -  Acessibilidade]: O sistema deve ser acessível, permitindo alterações como tamanho da fonte, reconhecimento por voz, plugin de acessibilidade em línguas de sinais e software de leitura de tela.</br>
[RNF003  -  Compatibilidade]: O sistema deve permitir o acesso em dispositivos móveis e computadores, tendo seu próprio aplicativo ou via web.</br>
[RNF004 - Desempenho]: O sistema deve responder às ações do usuário em até 2 segundos para garantir uma experiência fluida.</br>
[RNF005 - Usabilidade]: O sistema deve ser intuitivo e fácil de usar, seguindo as melhores práticas de design de interface e experiência do usuário.</br>
[RNF006 - Escalabilidade]: O sistema deve ser escalável para suportar um aumento no número de usuários sem perda de desempenho.</br>

# Diagrama de Atividades
![image](https://github.com/user-attachments/assets/6ba2fc0f-e42d-4d74-a695-20b1f7ca9e14)
![image](https://github.com/user-attachments/assets/937af0d5-c827-4252-b78b-93f738208170)
link: https://app.diagrams.net/#G1cr0_u92LDlYab_agNlxLE18xNJm6x0E1#%7B%22pageId%22%3A%22cSahUEfquRX7Xm5HyozH%22%7D

# Diagrama de Casos de Uso
![image](https://github.com/user-attachments/assets/5c481b71-a741-43ea-a87c-536ef4787271)
link: https://app.diagrams.net/#G1t5n4MYqT5EJt036Dnl3jX7yXbz_8akx1#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D

# Descrição dos Casos de Uso
![image](https://github.com/user-attachments/assets/12f0775e-a994-4e5a-8ae9-ad142e1db1a9)
![image](https://github.com/user-attachments/assets/d50934bc-dfb0-4c07-b461-7037f088fac3)
![image](https://github.com/user-attachments/assets/1c324f0c-7b28-4828-bd5f-552afde8d557)

# Diagrama de Sequência
![image](https://github.com/user-attachments/assets/aa85b882-ad50-4674-9104-971d6522c39e)
![image](https://github.com/user-attachments/assets/77ed8b47-b978-49ce-878b-245dd7002303)
![image](https://github.com/user-attachments/assets/c407a5ba-7081-4a40-9c6e-e4a9c384988b)
link: https://drive.google.com/file/d/1YyPYPdg6DNRE4hYbI1sdvzSwZoQqP2BH/view?usp=sharing

# Diagrama de Classes
![image](https://github.com/user-attachments/assets/ba9a9cbf-d664-4355-aa4d-6d1c727ffc25)
link: https://drive.google.com/file/d/1r2AfY2D1O5fbTIcj-jkiGvuq9aVBdwDo/view?usp=sharing
# Diagrama de Estados

![image](https://github.com/user-attachments/assets/5812ea1c-d356-4b13-bc51-f63348f84629)
![image](https://github.com/user-attachments/assets/81234ae5-a8cc-4f94-b271-869726a81e83)
link: https://drive.google.com/file/d/17tIcUFA2IrFAwJtxyC-lgTvkIWhP9oxT/view?usp=sharing

# Diagrama de Implantação
![image](https://github.com/user-attachments/assets/d9764296-270c-40fe-866e-b08f5df6ac7a)
link: https://drive.google.com/file/d/11OZrV2fVJO5PISJPKQslbey-KyKKWFdP/view?usp=sharing
