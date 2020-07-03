###This is a test project.

To make it run:

Go to "server" folder:
- Run `npm install`
- Run `npm start`
- Go to http://localhost:3001

Go to "client" folder:
- Run `npm install`
- Run `npm start`
- Go to http://localhost:3000

### 1. Created the note dispenser ATM POST API /api that can deposit, withdraw and check balance of account in ATM and in case of errors in outputs error as json. The interface is shown when you visit at your browser http://localhost:3001

#To deposit: 
- Switch selector to Deposit
- Enter "test" in text input field
- Press "+" and insert value of dispense (for now allowed: 1, 2 and 5) and amount of dispense
- Press Deposit button
- In alert box, will be shown as json


#To withdraw: 
- Switch selector to Withdraw
- Enter "test" in text input field
- Enter the value to withdraw
- Press Withdraw button
- In alert box, will be shown as json the value and amount

#To check balance
- Enter "test" in text input field
- Press "Get Balance" button

### 2. Build a reusable React Grid component that allows the user to filter the displayed data
The data are in JSON. The interface is shown at: localhost:3000

### 3. Build a page in frontend that uses the Grid to display data loaded from server
I have creted the endpoint in server with some dummy data as json (http://localhost:3001/getData)
The data are displayed in grid at http://localhost:3000


