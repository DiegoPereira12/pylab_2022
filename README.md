# Plataforma Seleti.ve

Projeto desenvolvido durante o Bootcamp Pylab 2022 do Canal Pythonando. Trata-se de uma aplicação para gerenciar processos seletivos,
que terá empresas e vagas de emprego, onde usuário poderá interagir com o sistema via web.

### 1) API

A modelagem do projeto terá os seguintes modelos.

## Empresa	
- Tecnologias(tecnologia)
- Empresa (logo, name, email, cidade, tecnologias, endereço, caracterisca_empresa, nicho de mercado)
- Vagas (empresa, titulo, nivel_experiencia, data_final, email, status, tecnologias_dominadas, tecnologias_estudar)

## Vagas
- Tarefa(vaga, titulo, prioridade, data, realizada)
- Emails(vaga, assunto, corpo, enviado)

A API deverá fornecer recursos para:

- Cadastrar listar e excluir empresas
- Filtrar por empresa ou tecnologia
- Acessar uma empresa em especifico e visualizar sua vagas
- Acessar uma vaga em especifico(criar tarefas e enviar email)

- Listar todos os cursos do catalogo 
- Cadastrar e atualizar novos cursos 
- Excluir cursos existentes 
- Listar todos os alunos 
- Cadastrar/Editar novos alunos 
- Matricular um aluno em um curso
- Remover o aluno de um curso


