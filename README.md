# API DE ENVIO DE EMAIL

## PLUGINS USADOS
```sh
TYPESCRIPT
TSX
PRISMA
FASTIFY
ZOD
```

## PASSOS
1. ADD PLUGINS
```sh
yarn add -D typescript @types/node tsx tsup prisma
yarn add fastify @prisma/client zod
```

2. INICIAR O TSC
```sh
npx tsc --init
```

3. INICIAR O PRISMA
```sh
npx prisma init
```

4. SALVAR ALTERAÇÕES NO DB
```sh
npx prisma migrate dev
```



