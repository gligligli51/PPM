

### TRABALHO FINAL PPM ###

O trabalho apresentado e um programa utilizado na materia passada de  Desenvolvimento para Dispositivos Móveis
Onde foi desenvolvido um APP de camera, que pode tirar fotos, editar e armazenar.
A linguagem utilizada para o desenvolvimento do trabalho foi em Kotlin.


### Melhorias ###

### 1. MVC: Adaptar o projeto para um melhor entendimento das classes ###

Model: gerencia a lógica de dados.

View: cuida da apresentação e da interface do usuário.

Controller: atua como intermediário, processando as entradas do usuário e interagindo com o Model e a View implementando as regras de negocio.

Facilidade de manutenção: Com a separação clara das responsabilidades, é mais fácil identificar e corrigir problemas em uma parte específica do sistema sem afetar as outras.
Reutilização de código: As classes e componentes podem ser reutilizados em diferentes partes da aplicação, reduzindo a duplicação de código.

Essa implementacao seria para o projeto inteiro como um todo.

### 2. Refatorar as classes: ###

Ao refatorar o código, o objetivo é torná-lo mais claro, mais fácil de manter e mais eficiente, modificando a estrutura interna e a forma como os objetos são gerados, sem alterar o comportamento externo do sistema.

### 2.1 Separar da activity EditImage as funções de edição e mandar elas para uma classe nova separada. ###


![image](https://github.com/user-attachments/assets/003703bd-0a1d-4cd8-b195-7c39f28f63e7)


![image](https://github.com/user-attachments/assets/73b44087-adf4-4702-95fc-7d65bcfd1ff6)


![image](https://github.com/user-attachments/assets/37067d2f-5a34-4505-81bd-abc439004ef9)

 
### 2.2 Criar uma classe com o final da EditImage para separar a responsabilidade de salvar deste codigo. ###

![image](https://github.com/user-attachments/assets/e46ba4ec-42e9-43af-b731-96218d24b437)


 
### 2.3 Colocar tudo pertinente a camera da mainactivity para a sua classe separada.  ###


![image](https://github.com/user-attachments/assets/3cda26cf-22e6-4630-a3f8-a9cb8649baa4)


![image](https://github.com/user-attachments/assets/cda94692-2d24-4184-a69a-7cae4248b558)


![image](https://github.com/user-attachments/assets/5dd2437b-f861-47fd-965e-5ac4d99adc9d)


![image](https://github.com/user-attachments/assets/abaec07b-e2bc-4fbc-b3fc-13d64a4c40a0)


### 3. Usar uma classe builder para as activities (definir uma visualização padrão) ###


Uma classe builder é um padrão de design que tem como objetivo facilitar a construção de objetos complexos, fornecendo uma maneira fluida e legível de configurar suas propriedades antes de criar a instância final. Em vez de passar um número grande de parâmetros no construtor ou configurar as propriedades diretamente, o builder permite configurar as propriedades de forma mais controlada e modular.

![image](https://github.com/user-attachments/assets/3835d261-90c6-441a-adff-c3526212ec32)
