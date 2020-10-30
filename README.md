## Class Note

https://btholt.github.io/complete-intro-to-react-v5/

## How to use this Repo

The course was teached by branches, so the master branch is the start point and exists all the branches above were we can learning a exciting new
thing about react:

- Emotion Code [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/emotion]
- Code Splitting [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/code-splitting]
- SSR [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/ssr]
- Typescript [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/typescript]
- Redux [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/redux]
- Testing [https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/tree/test]

## Code Splitting

Use lazy to load a component just when the component is need, just use lazy when the component/page is heavy like more
than 30kb, otherwise will be worst use lazy

## SSR

- renderToString class: https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/commit/ac8ecd88a05fb5c09aaf8acc06d4d8288d7cd062
- renderToNodeStream class: https://github.com/CaiqueCoelho/frontend-masters-intermediate-reactv2/commit/f377cc27e979b68f6d1c8644780b3636c7dc2a12

## Typescript

- `npx tsc --init` initiate a typescript project
- `npm run typecheck` check for erros in typescript

## Redux

Redux has been used less and less, so think carefully before using Redux, you may not need to, a great solution is to use useReducer
If you are getting or sending to several diferent API maybe Redux can be a good solution if you need to get the responses from this
APIs in an specif order, one example is Sagas

## Clear Cache

rm -rf .cache dist

## Hooks in Depth

Hooks in Depth was teached in code sand box, https://codesandbox.io/s/github/btholt/react-hooks-examples/tree/master/
