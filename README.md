# Build simple Web Service with Node.js
create RESTful API from this website [Dicoding-notes](http://notesapp-v1.dicodingacademy.com/)

## Preparation
- initiate npm with npm init --y
- install nodemon with npm install nodemon --save-dev
- install ESLint with npm install eslint --save-dev
- install hapi framework with npm install @hapi/hapi
- ( using nodemon to reduce the restart service in web )
- make sure in package.json the ["scripts" > "start" = already run with nodemon (your_service.js)]
### - Configure ESLint
- How would you like to use ESLint? -> To check, find problems, and enforce code style.
- What type of modules does your project use? -> CommonJS (require/exports).
- Which framework did you use? -> None of these. 
- Does your project use TypeScript? -> N.
- Where does your code run? -> Node (pilih menggunakan tanda panah atau spasi di keyboard).
- How would you like to define a style for your project? -> Use a popular style guide.
- Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
- What format do you want your config file to be in? -> JSON.
- Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.

### Start Web Service App
- Open this [website](http://notesapp-v1.dicodingacademy.com/)
- Change URL to 'http://localhost:5000'
- npm run start
