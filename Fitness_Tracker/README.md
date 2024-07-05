# Setting Up angu;ar material

- [Setting Up angu;ar material](#setting-up-anguar-material)
  - [Deployment](#deployment)
  - [Instalaltion](#instalaltion)
  - [Steps to use](#steps-to-use)
  - [fxLayout](#fxlayout)
  - [Angular Fire](#angular-fire)
  - [State management using RxjS](#state-management-using-rxjs)
  - [Redux](#redux)
  - [Steps to Implement redux](#steps-to-implement-redux)


## Instalaltion 
`ng add @angular/material`

## Steps to use
1. Create a separate module for importing all matrial components
```ts
@NgModule({
  imports: [MatButtonModule],
  exports: [MatButtonModule],
})
export class MaterialDemoModule {}
```
2. Import the module in main module
`imports: [MaterialDemoModule]`
3. Start using button module inside the code
`<button mat-button>Basic</button>`
**NOTE** To prevent errors on importing a material module, Restart the server after importing a new material module or try running npm install


## State management using RxjS
1. Execution of certain Event (button click)
2. State change even execition
3. Emitting an event using rxjs (Observable)
4. Listen to event (Subscription)
5. Update UI

