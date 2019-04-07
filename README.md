# Student Donation Analysis
This source code represents data visualization using d3.js, dc.js, node.js and mongodb.  A dashboard has been established which shows the analysis of Student Donation with respect to grades and states. The data has been represented by different graphs with multiple options for the users to select from.
<br/>
Required Components:<br/>
D3.js<br/>
Dc.js<br/>
Node.js<br/>
Crossfilter.js<br/>
Jquery<br/>
MongoDB<br/>

Steps for successful execution:<br/>
1.Install MongoDB <br/>
2.Go to C:\Program Files\MongoDB\Server\4.0\bin and paste the dataset.csv
3.Run mongod.exe and open another command prompt at the same place
4.Run the following code at the command prompt mongoimport --db users --collection contacts --type csv --headerline --file dataset.csv
5.Install Nodejs and NPM<br/>
6.Navigate to the node-dc-mongo directory using command prompt and run npm install, this will install the dependencies<br/>
7.Navigate to the node-dc-mongo directory using command prompt and run npm start<br/>
8.In your browser go to localhost:8080/index.html<br/>
