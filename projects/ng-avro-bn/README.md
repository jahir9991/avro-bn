# NgAvroBn

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.3.

## Code scaffolding

Run `npm i ng-avro-bn`.


## uses:

in module:
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
## in html :
```
<input NgAvroBn [avroFormField]="passportForm.controls['bn_name']" type="text" formControlName="bn_name" placeholder="Name in bangla" />
```
