
## My Tech Stack (MERN)

#### Front-end
* Front-end Framework: `React.js (with Redux)`
* Styling: `SASS` and `BOOTSTRAP`

#### Back-end
* For handling server requests: `Node.js with Express.js Framework`
* As Database: `MySQL`
* API tested using: `POSTMAN`

## Guidelines to setup
1. Open your local CLI -

    ```
    mkdir Stackoverflow-Clone
    cd Stackoverflow-Clone
    ```
2. Setup the backend code -

    - Create a `.env` file and the format should be as given in `.env.example`.
    - Clone the code & install the modules-
   
        ```
        git clone https://github.com/Taufiq-Y/StackOverflow-Clone-BE.git
        cd Stackoverflow-Clone-Backend

        npm install
        ```
    - Open your MySQL Client -
    
        ```
        source ./data/databaseConfig.sql
        source ./data/seed.sql
        ```
    - Run the server `npm run server`.
3. Open a new CLI terminal and goto the root `Stackoverflow-Clone` folder you created in the first step.
4. Setup the Frontend code -

    - Clone the code & install the modules-
    
        ```
        git clone https://github.com/Taufiq-Y/StackOverflow-Clone-FE.git
        cd Stackoverflow-Clone-Frontend
        
        npm install
        ```
    - Run the client server `npm start`.



