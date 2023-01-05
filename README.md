<h1>Bussiness Process Tool</h1>
<p> Business Process Tool  is a web portal used when team members need to make a purchase on behalf of their organization.</p>
    <p>User can create  multiples requisition through this website.</p> 

<h2>General Info</h2>
<h2>Technologies</h2>
<ul>
  <h3>FRONTEND</h3>                  
  <li>HTML</li>
  <li>CSS3</li>
  <li>BOOTSTRAP</li>
  <li>JAVASCRIPT with jQuery "3.6.3" </li>
  <h3>BACKEND</h3>
  <li>NODE JS</li>
  <li>EXPRESS</li>
  <h3>DATABASE</h3>
  <li>MySQL</li>

</ul>

<h2>Install Dependencies</h2>
<ul>
    <li>For Backend - npm i </li>

   <li> For Frontend - cd frontend  npm i </li>

</ul>
<h3>Getting Started</h3>
    Clone this repo to your local machine using.
   #### git clone git@github.com:Juliest88/mysql-node-express.git

# Get into the directory
cd 

# Make it your own
rm -rf .git && git init

# Coppy .env and create your own .env file
cp .env .env

# Edit .env file and add your mysql username, mysql password and db name
vi .env
# you can edit the file also via text editor

# Get into the db directory
cd src/db

# Import mysql database using Command line
mysql -u [db_username] -p[db_password] < create-user-db.sql
# you can edit the file if you want to change the db_name
# if you are using a different db_name and it elready exists,
# you can comment the first two lines, remain the line => USE test_db;
# and just change the db_name

# Install dependencies
npm install

# Run the server locally
npm start

# Run the server locally in dev mode
npm run dev
