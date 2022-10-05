# custom-build-in-JS-TS-

###### Typescript
 
1. **custom Partial** ==> type CustomPartial<T> = {[key in keyof T]?: T[key]};
2. **custom required** ==> type CustomRequired<T> = {[key in keyof T]-?: T[key]};
