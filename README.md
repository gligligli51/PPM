### TRABALHO FINAL PPM ###

O trabalho apresentado e um programa utilizado na materia passada de  Desenvolvimento para Dispositivos Móveis
Onde foi desenvolvido um APP de camera, que pode tirar fotos, editar e armazenar.
A linguagem utilizada para o desenvolvimento do trabalho foi em Kotlin.

                                                                                                    ### Melhorias ###


### 1.MVC: Adaptar o projeto para um melhor entendimento das classes ###

Model: gerencia a lógica de dados.

View: cuida da apresentação e da interface do usuário.

Controller: atua como intermediário, processando as entradas do usuário e interagindo com o Model e a View implementando as regras de negocio.

Facilidade de manutenção: Com a separação clara das responsabilidades, é mais fácil identificar e corrigir problemas em uma parte específica do sistema sem afetar as outras.
Reutilização de código: As classes e componentes podem ser reutilizados em diferentes partes da aplicação, reduzindo a duplicação de código.

Essa implementacao seria para o projeto inteiro como um todo.

### 2.Refatorar as classes: ###

Ao refatorar o código, o objetivo é torná-lo mais claro, mais fácil de manter e mais eficiente, modificando a estrutura interna e a forma como os objetos são gerados, sem alterar o comportamento externo do sistema.

### 2.1 Separar da activity EditImage as funções de edição e mandar elas para uma classe nova separada. ###

![image](https://github.com/user-attachments/assets/b09689d1-4d7c-45b9-86dd-c2167ca8248e)
![image](https://github.com/user-attachments/assets/16ec653c-1db4-4797-99e4-5a559452d564)
![image](https://github.com/user-attachments/assets/03f2e566-a8a3-4dfe-b333-ae45ad96bbe9)

 
### 2.2 Criar uma classe com o final da EditImage para separar a responsabilidade de salvar deste codigo. ###

![image](https://github.com/user-attachments/assets/600fb8e4-f380-422d-8337-609a4d3c3e6b)

 
### 2.3 Colocar tudo pertinente a camera da mainactivity para a sua classe separada.  ###

![image](https://github.com/user-attachments/assets/ad3b1f12-3ae5-4972-b6cb-05d3f30cf20d)
![image](https://github.com/user-attachments/assets/01387c6f-b52f-4de7-8948-66144a0c8962)
![image](https://github.com/user-attachments/assets/f5625b35-d71e-432a-ad8e-fd865294af50)
![image](https://github.com/user-attachments/assets/245609bf-f8b5-487c-a322-d644063d89db)

 
### 3.Usar uma classe builder para as activities (definir uma visualização padrão) ###


Uma classe builder é um padrão de design que tem como objetivo facilitar a construção de objetos complexos, fornecendo uma maneira fluida e legível de configurar suas propriedades antes de criar a instância final. Em vez de passar um número grande de parâmetros no construtor ou configurar as propriedades diretamente, o builder permite configurar as propriedades de forma mais controlada e modular.

![image](https://github.com/user-attachments/assets/3c97e34f-1cd0-467e-8a7f-6a256bfb7948)
