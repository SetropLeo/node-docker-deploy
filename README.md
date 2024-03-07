### Important

1. You need postgres
2. Configure DB URL
   a. "postgresql://postgres:123@localhost:5432/nodedeploy?schema=public"
3. Run "npx prisma migrate dev" (create a migration)
4. Run "npx prisma studio" (you can see your db)