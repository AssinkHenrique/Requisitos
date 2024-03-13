# 🚀 Projeto: Transporte Aéreo de Cargas Industriais 🛫

Esta especificação tem como objetivo definir claramente as funcionalidades e restrições do sistema a ser desenvolvido, o STACI (Sistema de Transporte Aéreo de Cargas Industriais). Destina-se à equipe de desenvolvimento de software e será utilizado e verificado por todas as partes envolvidas na elaboração do sistema. O documento está sujeito a modificações durante sua elaboração até a obtenção da aprovação, momento em que servirá como base para a construção do sistema pela equipe de desenvolvimento.

O STACI visa aprimorar a operação atual do sistema, aumentando os benefícios obtidos. Busca controlar todas as operações da transportadora, incluindo registros de aviões, datas e horários de voos, cargas suportadas, fabricantes, manutenções, dados sobre empregados e equipes de manutenção, informações sobre pilotos e modelos de aviões autorizados, entre outros serviços e regras de negócio necessários da GoAir.

## 1. Requisitos Funcionais 📋

### 1.1 Subsistema: Gerenciar informações de aviões ✈️

| Código | Requisito                                 | Prioridade           |
|--------|-------------------------------------------|----------------------|
| RF01   | Cadastro de aviões                         | Essencial            |
| RF02   | Cadastro de voos                           | Essencial            |
| RF03   | Cadastro de fabricante                     | Essencial            |
| RF04   | Cadastro de manutenção                     | Essencial            |
| RF05   | Listagem de aviões                         | Essencial            |
| RF06   | Listagem de voos                           | Essencial            |
| RF07   | Listagem de fabricantes                    | Essencial            |
| RF08   | Listagem de manutenções                    | Essencial            |

### 1.2 Subsistema: Gerenciar informações de empregados 👩‍💼

| Código | Requisito                                 | Prioridade           |
|--------|-------------------------------------------|----------------------|
| RF09   | Cadastro de empregados                     | Essencial            |
| RF10   | Listagem de empregados                     | Essencial            |

### 1.3 Subsistema: Gerenciar informações de pilotos ✈️👨‍✈️

| Código | Requisito                                 | Prioridade           |
|--------|-------------------------------------------|----------------------|
| RF11   | Cadastro de pilotos                        | Essencial            |
| RF12   | Cadastro de modelos                        | Essencial            |
| RF13   | Listagem de pilotos                        | Essencial            |
| RF14   | Listagem de modelos                        | Essencial            |
| RF15   | Exclusão de modelos                        | Essencial            |

## 2. Requisitos Não Funcionais ⚙️

### 2.1 Requisitos de Software 💻

| Requisito           | Descrição                           |
|---------------------|-------------------------------------|
| SGBD                | MySQL, versão 8.0 ou superior.      |
| Linguagem de Programação | Java                            |

### 2.2 Requisitos de Segurança 🔐

| Requisito           | Descrição                           |
|---------------------|-------------------------------------|
| Controle de Acesso  | Controle de acesso por usuário/subsistema. |

## 3. Requisitos de Negócio 💼

| Código | Requisito                                 | Descrição                                  |
|--------|-------------------------------------------|--------------------------------------------|
| RN01   | Manutenção única                          | A manutenção de um avião pode ser realizada somente por uma equipe de cada vez. |
| RN02   | Carga máxima                              | Os aviões de carga somente realizarão os voos quando possuírem a quantidade de carga para transporte igual a sua carga máxima. |
| RN03   | Manutenção preventiva                     | Todo avião deve receber uma checagem preventiva todo mês para conferência do seu estado geral. |

Este documento é uma base inicial e está sujeito a ajustes conforme o desenvolvimento progride. Qualquer alteração será devidamente documentada e submetida à aprovação das partes interessadas.

---
⌨️ com ❤️ por [Armstrong Lohãns](https://gist.github.com/lohhans) 😊
