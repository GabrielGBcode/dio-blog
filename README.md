# Blog com Angular

## Descrição

O blog foi ao decorrer do bootcamp da [DIO](https://web.dio.me) oferecido pelo _Santander_. No projeto, foram criados "notícias", utilizando components e organizando as pastas separadamentes de acordo com cada item.

Foi utilizado `AngularCLI - 14.1.2`

## Estrutura do Projeto

- `src`: Pasta onde contém todos os arquivos do projeto.
  - `app`: aplicação principal, onde se encontra todos os components, páginas e dados.
    - `components`: Onde foram criados todos os components para fazer a aplicação dinámica.
    - `datas`: Criado para gerar os dados utilizado em cada notícia.
    - `pages`: Páginas do projeto, sendo a principal (**_home_**) e a uma equivalente a cada notícia (**_content_**)
  - `index.html`: Arquivo html principal do projeto.
  - `maint.ts`: Arquivo _Typescript_ que engloba os demais arquivos **_.ts_**
  - `polyfills.ts`: Utilizado para configuração de compatibilidade para diferentes browsers
  - `styles.css`: Estilização global do projeto.
- Os demais arquivos fora do projeto são para configuração.

- Arquivos como `test.ts` ou `*.spec.ts` não foram utilizado, por serem ambientes de testes.

### Comandos ng utilizado

1. `ng version`
2. `ng new [nome]`
   - _ng new angular-blog_
3. `ng generate component [nome]`
   - _ng g c menu-bar_
4. `ng serve`

<!-- # AngularBlog

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page. -->
