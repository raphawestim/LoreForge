# Loreforge MVP

## Requisitos
- Node.js 20+
- PostgreSQL 15+

## Setup local
1. `npm install`
2. `cp .env.example .env.local`
3. `npx prisma migrate dev --name init`
4. `npx prisma db seed`
5. `npm run dev`

## Credenciais seed
- admin@loreforge.com / admin123
- writer1@test.com..writer3@test.com / test123
- reader1@test.com..reader5@test.com / test123

## Fluxo MVP
1. Registrar usuário
2. Criar perfil de escritor
3. Criar tier
4. Criar obra
5. Criar post premium
6. Leitor assina via checkout mock
7. Leitor acessa conteúdo premium

## Próximos passos
- Integrar Stripe real
- Integrar Mercado Pago
- Migrar uploads para storage cloud
- Adicionar emails com Resend
- Rate limit nas actions
- Testes E2E com Playwright
- Otimização com next/image
- CDN para assets
