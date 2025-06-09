# Doorhi commanduudiig daraallaar ajiluulna

yarn install
docker compose up -d
npx prisma migrate dev --name init
yarn dev

# ENV file dotor torhiruulah

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME
NEXT_PUBLIC_CLOUDINARY_API_KEY
