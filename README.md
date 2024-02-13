This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Bug

NextJS 14 bug `TypeError: Cannot read properties of undefined (reading 'call')`

## Replicate

Run development server:

```sh
yarn install && yarn dev
```

Navigate to [http://localhost:3000](http://localhost:3000) in the browser. Notice that there is already an error popping out. You cannot even trace where the error is coming from.

## Learn More

To learn more about this issue, visit the submitted issue [#61995](https://github.com/vercel/next.js/issues/61995)
