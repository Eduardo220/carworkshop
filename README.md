# Refinando um design conceitual de banco de dados
Segundo desafio de projeto do curso "SQL Database Specialist" da [DIO](https://www.dio.me/).

### 🚗 Car Workshop
Entidades: Cliente, Veiculo, Mecanicos, Time, Ordem de serviço, Serviiço, Recibo.

### 📖 História
#### Sistema de Controle e Gestão de Ordens de Serviço para Oficina Mecânica
#### Fluxo Geral:
- Clientes levam veículos à oficina para reparos ou inspeções periódicas.
- Cada veículo é atribuído a uma equipe de mecânicos responsável pela avaliação e execução dos serviços.

#### Ordem de Serviço (OS):
- A equipe identifica os serviços necessários e registra as informações em uma OS.
#### A OS inclui:
- Número da OS
- Data de emissão
- Valor total (calculado)
- Status (ex: pendente, em execução, finalizada)
- Data de conclusão

#### Serviços:
Cada serviço executado tem seu valor calculado com base em uma tabela de referência.
Uma OS pode conter múltiplos serviços.
Um mesmo tipo de serviço pode estar presente em várias OSs.

#### Execução:
A equipe que realizou a avaliação do veículo é a mesma responsável pela execução dos serviços.

#### Equipe Técnica (Mecânicos):
Cada mecânico possui:
- Código identificador
- Nome completo
- Endereço
- Especialidade (ex: motor, elétrica, suspensão)

### 💻 Descrição do desafio
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida.

### ✅ Solução
<img align="center" src="https://github.com/Eduardo220/carworkshop/blob/main/Car_workshop.png" width=""/> 

## 🛠️ Minhas tecnologias
<p align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="100">   
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="100">      

</p> 
