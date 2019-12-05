
Download this repository

 `$ git colne https://github.com/harshchinu/Finin-Intern.git`

`$ npm install`

Create a specific AWS IAM user and add to group 'AmazonSNSFullAccess'

Edit `.env` and enter your correct AWS access key, secret and region.

`$ npm start`

Open browser and visit something like,

`http://localhost:3000/?number=[The Number]&subject=[The Subject]`

The mobile number should be E.164 format but without the + character.

eg, 

You want to send a message to a number,

The country code is 91

The mobile number is (0)90331 23754

The E.164 format would be +919033123754

Remove the + character

Then Visit 

`http://localhost:3000/?number=919033123754&subject=My Subject`

