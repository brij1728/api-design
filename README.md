# Initialize a new Node.js project

npm init -y

# Install typescript with the required packages:

npm install express typescript @types/node @types/express --save

# Initialize a TypeScript configuration file:

npx tsc --init

# Install Prisma CLI globally (optional but recommended):

npm install -g prisma

# Initialize Prisma: (if you not install it globally)

npx prisma init

# Install Prisma Client:

npm install @prisma/client

# Generate Prisma Client:

npx prisma generate

# Prisma client, which is sdk for migration

npm i @prisma/client --save
