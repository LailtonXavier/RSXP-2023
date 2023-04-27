### RSXT - project mobile and api in Nest

# map front
  - Expo
    - expo init mobile
  - NativeWind (tailwind in react native)
    - npm i nativewind
    - npm i tailwindcss -D
    - npx tailwindcss init
      - config add content `tailwind.config.js`
      - config add plugin `babel.config.js`
    - Eslint
      - npm i eslint @rocketseat/eslint-config -D

# map back
  - Nest
    - npm install -g @nestjs/cli
    - npm nest new name
    - ... config
    - Eslint
      - npm i eslint @rocketseat/eslint-config -D
    - Prisma
      - npm i prisma -D
      - npx prisma
      - npx prisma init
      - test connection to bank
        - after add the the docker (user e name)
          - create a model `prisma/schema.prisma`
          - create image docker
            - sudo docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres
            - port machine fisic 5433
          - start docker
          - npx prisma migrate dev
          - interface do prisma
            - npx prisma studio
            - 




