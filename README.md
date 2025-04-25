# Amazon Token Exchange (Vercel)

Esta é uma API serverless para trocar o authorization code da Amazon Advertising API por um access_token, usando Vercel + Next.js.

## Como usar

1. Configure suas variáveis no `.env.local`.
2. Faça o deploy no Vercel.
3. Após o usuário autorizar, a Amazon redirecionará para:

```
https://amazon-oauth-callback.vercel.app/?code=SEU_CODE
```

Você verá o JSON com os tokens de acesso.