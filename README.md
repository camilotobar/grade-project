# Grade Project
Logs and files for the grade project.<br>
**Project Name:** A Self-Adaptive Controller Prototype for Automated Trading Systems.<br>
**Students:** Andrés Felipe Borrero y Juan Camilo Tobar.<br>
**University:** Universidad Icesi.<br>

## Logs
All the project logs were made via LogWarning to be completely differentiated to the ASP.NET logs, coming from the IIS or from the .NET Core.<br>
Therefore, the logs that begin with 'warn' are from the project. The 'info' starting logs are from ASP.NET.<br>
The **pattern** for every project log is: <br>
warn: {FromApplication.FromModule.FromClass} <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{DATE dd/MM/YY HH:MM:SS} + {MESSAGE}


### Portfolio Controller
Controller component of the Self-Adaptive System.<br>

### Asynchronous Server Connection Provider
Financial context component of the Self-Adaptive System.<br>

### Strategies
Target component of the Self-Adaptive System.<br>

### Subscription
Trading subscription and scheduler component.<br>

## Statements
Trading account statements.
There are 3 statements for 3 trading moments of the account.<br>
On the statements are overall performance data that summarizes the account trades, such as Direction (Buy/Sell), Closing Time, Balance, Pips, Volume and Quantity.
