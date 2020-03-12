# phalcon-react
Steps to run this project:

run docker-compose up<br> 
Backend: http://0.0.0.0:5000/<br> 
Frontend: http://0.0.0.0:3000/<br> 
Since we are using Nginx - open app on http://0.0.0.0:8000/ or http://localhost:8000/

### Migrations:

To create time-based migration versions make sure you <br> 
generate your migrations with the --descr=s option. <br>
Example: phalcon migration generate --descr=init <br>

To run your time-based migrations, you need to use the <br>
--ts-based option on your migration run. <br>
Example: phalcon migration run --ts-based. 

### Running the tests:

Inside /src folder use composer install command and <br>
it will install all the dependencies as specified in the composer.json file. <br>

Execute phpunit in your command-line from the tests directory. 
