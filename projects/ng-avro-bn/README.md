# NgAvroBn

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.3.

## Code scaffolding

Run `ng generate component component-name --project NgAvroBn` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module --project NgAvroBn`.

> Note: Don't forget to add `--project NgAvroBn` or else it will be added to the default project in your `angular.json` file.

## Build

Run `ng build NgAvroBn` to build the project. The build artifacts will be stored in the `dist/` directory.

## Publishing

After building your library with `ng build NgAvroBn`, go to the dist folder `cd dist/ng-avro-bn` and run `npm publish`.

## Running unit tests

Run `ng test NgAvroBn` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

#uses:

```


import { NgAvroBnModule } from 'src/app/avro/ng-avro-bn.module';

@NgModule({
imports: [
CommonModule,
...
FormsModule,
ReactiveFormsModule,
NgAvroBnModule
],
declarations: [...],
})
export class AnyModule {}
```

````
<input NgAvroBn [avroFormField]="passportForm.controls['bn_name']" type="text" formControlName="bn_name" placeholder="Name in bangla" />
````
