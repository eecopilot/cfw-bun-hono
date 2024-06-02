Install

```
bun install
```

Dev

```
bun run dev
```

Production

```
bun run deploy
```

其他说明

1. 创建 D1 数据库

bunx wrangler d1 create cfw-bun-hono-drizzle-d1

2. 创建 migration

bun run db:generate

3. D1 migration

------------------------- database name --------- local/remote -- file  
bunx wrangler d1 execute cfw-bun-hono-drizzle-d1 --local --file=本地 sql
