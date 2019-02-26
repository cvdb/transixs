# transixs
new age transaction processing platform made easy

### Project Goals
* Realiable transaction processing
* Transaction data is generic, sematics remain the same
* Always know what happened to each transaction
* Easy to customize and extend
* Easy to deploy and manage
* Transaction processing is not tied to reporting
* Focus on processing BUT allow reporting data to be extracted
* Transaction source does not matter. Generic well defined interface.
* Expose transaction processing data so it can be ingested by a console
* KISS or DIE

Our plans:
* Use CQRS to separate read and write models.
* Use event sourcing to keep a record of WHAT HAPPENED and allow replay
* Use kubernetes to deploy and manage applications....and allow pollygot development.
* Develop a GENERIC TRANSACTION PROCESSING systems that would be well suited to payment processing but can be used for other applications.
