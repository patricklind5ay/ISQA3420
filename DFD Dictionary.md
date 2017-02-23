<h1>DFD Dictionary</h1>

<h2>Entities</h2>
•	**Manager:** manages developer and sets open-source software policies

•	**Developer:** software developer that brings in open-source software packages
<h2>Processes</h2>
•	**Orchestrator:** gives software packages to Scanner and NIST Vulnerability Database, stores those results in the License and Vulnerability Database, and sends the results back to the Developer

•	**Scanner (FOSSology):** Scanner for license information in open-source software

•	**Request Info:** queries the License and Vulnerability Database and returns those results back to the Developer or Manager

•	**Edit Policy:** Accepts policy name from the Manager, gets the policy information from the Policy Database, returns the policy information to the Manager, accepts policy update from the Manager, and uploads policy update to the Policy Database

•	**Create Policy:** Receives a new policy from the Manager and uploads into the Policy Database

•	**Retrieve Info:** Retrieves information about a specific policy from the Policy Database and sends it to the Manager
<h2>Data Stores</h2>
•	**NIST Vulnerability Database:** National Institute of Standards and Technology’s Vulnerability Database

•	**License and Vulnerability Database:** Database for storing scanned license information and known vulnerabilities

•	**Policy Database:** Database for storing company policies and policy information
<h2>Data Flows</h2>
•	**Vulnerability Results:** Results of querying the NIST Vulnerability Database

•	**Software Name:** Name of the software

•	**Software Package:** a collection of open-source software files

•	**Scan Results:** License information found from scanning the software

•	**License and Vulnerability Results:** Vulnerability Results and Scan Results

•	**Policy Name:** Name of the policy

•	**Policy Update:** Revisions made to an existing policy

•	**Policy Info:** all of the information about a specific policy

•	**New Policy:** A new policy

