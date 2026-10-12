# Case Studies

## Excel to API

<h3> Challenge </h3>
A mortgage portfolio management team relied heavily on a fragile Excel spreadsheet to manage and report risk. The process relied upon error prone copying and pasting from various external sources and templates were modified at will creating audit and compliance issues.

<h3> Solution </h3>
Bond-Bridge translated their Excel Risk sheet to an equivalent REST API that perfectly matched analytics. We programatically connected direct inputs without manual copy/paste of data and stored time-series of results into a database.  We then linked the analytics to business intelligence reporting for final presentation layer creating a hands-off Risk process.

<h3> Outcome </h3>
Calculation speed improved 2x+. Immutable audit trail without manual copy/paste dependencies. Presentation layer enhanced and separate from calculation layer.  Timeseries database storage of all analytics and assumptions.
 
## PnL Attribution

<h3> Challenge </h3>
Firm wanted a scalable API process to calculate PnL attribution across multi-asset portfolio including treasuries, mortgages and various derivatives.

<h3> Solution </h3>
Bond-Bridge created a consistent analytics approach across security types and implemented calculations via the REST API.  Raw analytics data was stored in a database and linked to positions and pricing data to create custom business intelligence reports capturing daily, monthly, annual PnL attribution.

<h3> Outcome </h3>
client was able to see attribution results right after market close.  Analytics were calculated and merged with position data dynamically avoiding the need for re-run of the entire portfolio for minor position changes.  BI reports presented daily and period to date tables and charts.
 
## YB batch to REST API

<h3> Challenge </h3>
Client has built an extensive and complicated Yield Book batch process with hundreds of lines of commands.  Internal knowledge and ownership of the batch process has moved on and the process did not have a technology owner and many updates have been delayed.

<h3> Solution </h3>
Converted the Batch process to a REST API implementation matching analytics for each asset class. Embedded a clear set of assumptions that allowed the customer to control inputs of model choices etc more clearly.  Produced output files in exact format as Batch so that upstream processes were seamless.

<h3> Outcome </h3>
Process was now much more clear to client in a modern REST process that was understood by all IT.  Business user’s had clear method of making analytics assumptions changes for curves and models as needed. Process timing was accelerated for results to be available same day instead of next business morning.
