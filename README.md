Claro! Aqui está o **README.md** pronto para você copiar e colar, sem a parte de licença ou screenshots:

````markdown
# Agência Espacial POO

## Descrição
A atividade **Agência Espacial POO** simula o gerenciamento de uma agência espacial interplanetária, onde é possível cadastrar e gerenciar **agentes**, **missões**, e a **participação dos agentes nas missões**. O sistema permite criar, atualizar, remover e consultar informações sobre agentes e missões. Além disso, ele gerencia a participação dos agentes em missões e gera relatórios sobre os dados cadastrados.

Esta aplicação foi implementada utilizando **Programação Orientada a Objetos (POO)** em **Java**, demonstrando conceitos de classes, herança, polimorfismo, listas e gerenciamento de dados.

## Objetivos
- Implementar um sistema de gerenciamento de agentes e missões utilizando POO.
- Aplicar conceitos de herança e polimorfismo para diferentes tipos de agentes (Piloto, Engenheiro, Cientista).
- Criar funcionalidades para o gerenciamento completo de missões, agentes e participação de agentes em missões.
- Demonstrar o uso de listas para armazenar e manipular dados.

## Tecnologias Utilizadas
- **Linguagem**: Java
- **Estrutura**: Programação Orientada a Objetos (POO)
- **Bibliotecas**: `java.util.Scanner`, `java.util.ArrayList`

## Instalação
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/usuario/AgenciaEspacialPOO.git
````

2. **Compile o código**:

   * Se estiver usando um terminal, execute:

     ```bash
     javac Main.java
     ```

3. **Execute o código**:

   * Para rodar a aplicação, execute:

     ```bash
     java Main
     ```

## Como Executar

Após rodar o código, o menu interativo será exibido no terminal. Você pode escolher as opções para gerenciar **Agentes**, **Missões**, **Participação em Missões**, ou consultar **Relatórios**.

Exemplo de menu:

```
=== AGÊNCIA ESPACIAL INTERPLANETÁRIA ===
1. Gerenciar Agentes
2. Gerenciar Missões
3. Participação em Missões
4. Consultas e Relatórios
5. Sair
Escolha uma opção: 
```

## Funcionalidades

### Gerenciamento de Agentes:

* **Criar Agente**: Definir nome, classe (Piloto, Engenheiro ou Cientista), nível e atributos específicos do agente.
* **Atualizar Agente**: Alterar o nível ou a vida do agente.
* **Remover Agente**: Excluir um agente existente.

### Gerenciamento de Missões:

* **Criar Missão**: Definir nome e dificuldade da missão (Fácil, Médio, Difícil).
* **Atualizar Missão**: Alterar nome ou dificuldade da missão.
* **Remover Missão**: Excluir uma missão existente.

### Participação em Missões:

* **Adicionar Agente a Missão**: Incluir um agente a uma missão específica.
* **Remover Agente de Missão**: Retirar um agente de uma missão.
* **Iniciar Missão**: Iniciar a missão, se tiver agentes suficientes.

### Consultas e Relatórios:

* **Listar Agentes**: Exibir todos os agentes cadastrados.
* **Listar Missões**: Exibir todas as missões cadastradas.
* **Buscar Agente por Nome**: Buscar agentes específicos pelo nome.
* **Exibir Inventário de Agente**: Consultar o inventário de um agente.
* **Agrupar Agentes por Nível**: Agrupar e listar agentes por nível.
* **Agrupar Missões por Dificuldade**: Agrupar e listar missões por dificuldade.

## Exemplo de Uso

1. **Criar Agente**: Escolher a classe do agente (Piloto, Engenheiro ou Cientista), definir o nível e os atributos específicos.
2. **Criar Missão**: Definir nome e dificuldade da missão.
3. **Adicionar Agente a Missão**: Selecionar um agente e associá-lo a uma missão.
4. **Iniciar Missão**: Iniciar a missão com os agentes participantes.

## Contribuições

1. Fork este repositório.
2. Crie uma nova branch:

   ```bash
   git checkout -b feature/nova-feature
   ```
3. Faça suas alterações e envie para o repositório.
4. Envie um pull request.

```
