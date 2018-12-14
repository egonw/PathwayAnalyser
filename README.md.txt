# PathwayAnalyser

Product for Programming of Life Sciences 2018. PathwayAnalyser aims to find other pathways related to the targets present in a specific pathway. PathwayAnalyser provides the user with general information on a pathway of choice. It also provides a list of pathways in wich a concrete gene or protein is involved.

The application consists of a website that displays information on the pathway and on the targets in different tabs. Each tab consists of a html file. For the information.html file, the user can change the wikidata query in order to obtain information on the targets of interest. The information will always be displayed as a list.

In order to use the target.htm file the user has to first modify the information.html file to display the information needed to run the database calls in the target.html file. In the example, the ensemble IDs obtained from the targets in the file information.html are used to complete de Open Phacts API calls in the target.html file.

<p>Group members: Inma Carrascosa, Yul van der Stap, Maaike Tran.
</p>