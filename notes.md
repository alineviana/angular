# Angular

## Property Binding
- Passar valores de uma propriedade do component para atributos de tag dentro do template
- Ex:  [value]="pensamento.conteudo"

## Interpolação
- Mostrar valores de propriedades do component no template
- Ex:  {{ pensamento.autoria }}

## Event Biding
- Escutar eventos do template e fazer a chamada de métodos no component com o event binding
- Ex: (click)="criarPensamento()"

## NgModel
- Usar a diretiva ngModel que pertence ao FormsModule para a comunicação bidirecional entre component e template
- Ex: [(ngModel)]="pensamento.conteudo"

## Diretivas de componentes: usado com um modelo. Esse tipo de diretiva é a mais comum.
- Ex: app-listarPensamentos

## Diretivas estruturais: altera o layout do DOM adicionando e removendo elementos DOM.
- Ex: NgIf, NgFor. NgSwitch.

## Diretivas de atributos: altera a aparência ou o comportamento de um elemento, componente ou outra diretiva.
- Ex: NgClass, NgStyle.