for this code to work you need to:

cd ../server
npm i 
npm start 

then go to client

cd ../client 
npm i 
npm start 

it will then open the local website.

if there is an error, check if you have ".env" in ../client/.env
if not, create and write " REACT_APP_API=http://localhost:5000 "

if the website doesn't open, you can try opening it yourself in http://localhost:3000/