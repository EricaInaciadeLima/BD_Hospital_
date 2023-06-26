# Sistema de Gestão de Consultas Médicas

![Imagem 1](https://github.com/EricaInaciadeLima/BD_Hospital_/assets/98967783/da97d600-6b2b-4f28-acb2-79c31b6aa1ef)
![Imagem 2](https://github.com/EricaInaciadeLima/BD_Hospital_/assets/98967783/923db55a-9fba-40ab-9dfd-725f74eeb2e4)

Este é um sistema de gestão de consultas médicas desenvolvido em SQL. O objetivo do sistema é permitir o gerenciamento de consultas entre médicos e pacientes, incluindo informações sobre médicos, pacientes, consultas, receitas médicas, internações e convênios.


## Funcionalidades

O sistema permite realizar as seguintes operações:

- Cadastrar médicos, pacientes e convênios.
- Agendar consultas entre médicos e pacientes.
- Registrar receitas médicas relacionadas a consultas.
- Registrar internações de pacientes.
- Associar médicos e enfermeiros às internações.
- Consultar informações sobre médicos, pacientes, consultas, receitas e internações.

## Estrutura do Banco de Dados

O banco de dados é composto pelas seguintes tabelas:

- `Medico`: Armazena informações sobre os médicos, incluindo nome, CPF, RG, endereço, telefone e e-mail.
- `Especialidade`: Armazena informações sobre as especialidades médicas.
- `Medico_Especialidade`: Tabela de associação entre médicos e suas especialidades.
- `Paciente`: Armazena informações sobre os pacientes, incluindo nome, data de nascimento, endereço, telefone, e-mail, CPF e RG.
- `Convenio`: Armazena informações sobre os convênios médicos, incluindo nome, CNPJ e tempo de carência.
- `Consulta`: Armazena informações sobre as consultas médicas, incluindo data e hora, médico, paciente, valor da consulta, convênio, número da carteira e especialidade.
- `Receita`: Armazena informações sobre as receitas médicas, incluindo a consulta associada, medicamento, quantidade e instruções de uso.
- `Internacao`: Armazena informações sobre as internações de pacientes, incluindo data de entrada, data prevista de alta, data efetiva de alta, procedimentos realizados, quarto, paciente e médico.
- `Quarto`: Armazena informações sobre os quartos de internação, incluindo numeração, tipo, descrição e valor diário.
- `Enfermeiro`: Armazena informações sobre os profissionais de enfermagem, incluindo nome, CPF e registro de enfermagem.
- `Enfermeiro_Internacao`: Tabela de associação entre enfermeiros e internações.

## Instruções

1. Execute o script SQL fornecido para criar as tabelas do banco de dados e inserir dados de exemplo.
2. Utilize as consultas SQL para realizar operações no banco de dados de acordo com as funcionalidades desejadas.
3. Consulte a documentação do banco de dados para obter mais informações sobre a estrutura das tabelas e as operações disponíveis.

## Requisitos

- Banco de dados MySQL ou compatível.
- Cliente de banco de dados SQL para executar as consultas no banco de dados.


## Licença

Este projeto está licenciado sob a licença [MIT](LICENSE).


