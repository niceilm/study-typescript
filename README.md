# Study TypeScript

## Pros
- Superset of JavsScript
  - Type
  - Most ES6 features
    - class, extends, super(), =>, ...
  - Some ES7 features
    - Decorator
  - Generate Code Not Overhead Just Build Time Check
    - 결국  VanilaJS로 변환되어서 성능상 하락이 없다!!
  - support thrid party library by declare files

## Cons
- Learning Curve
- TypeScript 코드가 아니면 Type Definition File 생성 필요
  - 일단 ```declare var $:any```로 쓸수 있음

## Link

### Official
- [http://www.typescriptlang.org](http://www.typescriptlang.org)
- [Roadmap](https://github.com/Microsoft/TypeScript/wiki/Roadmap)
- [Spec](https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md)

### Book
- [TypeScript Deep Dive](https://basarat.gitbooks.io/typescript/)
- [handbook](http://www.typescriptlang.org/Handbook)

### Useful
- [awesome-typescript](https://github.com/dzharii/awesome-typescript)

### Documents
- [Functional TypeScript](https://vsavkin.com/functional-typescript-316f0e003dc6?_branch_match_id=289185608293445594#.so6w267jb)
- [The Importance of import and export](http://benjamn.github.io/empirenode-2015/#/)
- [Learn TypeScript in 30 Minutes](http://tutorialzine.com/2016/07/learn-typescript-in-30-minutes/)
- [Playground](http://www.typescriptlang.org/play/)

## Module
- [ts-node - TypeScript execution environment for node](https://github.com/TypeStrong/ts-node)

## Test by mocha
- need ts-node devDependency
```
mocha --require ts-node/register tests/**/*.ts
```

## Webpack Config by typescript
- need ts-node devDependency
- create webpack.config.ts
- run webpack

## Finding Type Definition
- [TypeSearch](https://microsoft.github.io/TypeSearch/)

### use typings
[typings](https://github.com/typings/typings)
```bash
typings search [module name]
```

### use npm
```bash
npm i -D @types/[module name]
```