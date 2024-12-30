# how to create cloudflare project 
- npm create cloudflare@latest


# how to add Hono to your project 
- npm install hono

# Add prisma 
for adding prisma you can add it as dev dependency : 
- npm i --save-dev prisma

# Adding schema in your DB 
- npx prisma migrate dev --name <name_your_migration>

# Note : usually you can now start doing your db operations where as now in serverless you cannot , you need to create connection pool

- create a connection pool using prisma accelerate

# install Prisma accelerate extension 
npm install @prisma/extension-accelerate 

# Now we want to generate our prisma client 
- npx prisma generate --no-engine