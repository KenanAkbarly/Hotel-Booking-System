# Hotel Rezervasiya Sistemi

Üç directory-dən ibarət tətbiqdir: `admin`, `client`, və `api`. Hər directory öz kod bazasına sahibdir.

## Directory Structure

- **admin**: Admin panel kodlarından ibarətdir.
- **client**:Client app kodlarından ibarətdir.
- **api**: API server BackEnd kodlarından ibarətdir.


### 1. Admin Directory

```bash
cd admin
npm install
npm run dev
```


### 2. Client Directory 
```bash
cd client
npm install
npm run dev
```

### 3. API Directory

```bash
cd api
npm install
npm start
```

### 4. Socket Directory (Real vaxt rezervasiyası üçün *istəyə bağlıdır)

```bash
cd api/socket
npm start
```