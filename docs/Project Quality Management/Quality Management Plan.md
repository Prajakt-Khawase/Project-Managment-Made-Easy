# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Project Quality Management

### Prepared by:  Prajakt Uttamrao Khawase &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Date: 06/02/2018

The purpose of project quality management is to ensure that the project will satisfy the needs for which it was undertaken. A metric is a standard of measurement whether the produced product is upto the desired standard or not. In project quality planning, it is important to identify relevant quality standards, such as ISO standards. To maintain the quality first we should know what kind of quality the stakeholders associated with the project expecting. The project team must develop good relationships with key stakeholders, especially the main customer for the project, to understand what quality means to them. After all, the customer ultimately decides if quality is acceptable. Many technical projects fail because the project team focuses only on meeting the written requirements for the main products being created and ignores other stakeholder needs and expectations for the project. Quality Management includes the following processes.

*	Quality Planning – It would be taken care during the project planning process.
*	Quality Assurance  – It would be taken care during the project execution process.
*	Quality Control  – It would be taken care during the project monitoring and controlling process.

1. Planning quality management:
The main outputs of planning quality management are a quality management plan, a process improvement plan, quality metrics, quality checklists, and project documents updates.

2. Performing quality assurance
Quality assurance ensures that project processes are used effectively to produce quality project deliverables. It involves following and meeting standards, continuously improving project work, and correcting project defects. The main outputs of this process are change requests, project management plan updates, project documents updates, and organizational process asset updates.

3. Controlling quality involves
The main outputs of quality control include quality control measurements, validated changes, validated deliverables, work performance information, change requests, project management plan updates, project documents updates, and organizational process asset updates.

### Quality Management Plan

TSoftware testing metrics are a way to measure and monitor test activities. If our test cases are getting passed then we can determine that we are also meeting the quality requirement. Software testing metrics are use to determine the team progress. The aim of collecting test metrics is to use the data for improving the test process, rather than to just show fancy reports.
<br>
###### We have decide to use Percentage test coverage matrix in which we are following specific measures.

1. Number of test run per time period = Number of test run / Total Time.
2. Test review Efficiency = Number of test reviewed  / Total Time.
3. Passed Test Cases Percentage = (Number of Passed Tests/Total number of tests executed) * 100
4. Failed Test Cases Percentage = (Number of Failed Tests/Total number of tests executed) * 100
5. Fixed Defects Percentage = (Defects Fixed/Total Defects Reported) * 100
6. Bug find rate = Total number of defects/Total number of test hours

### Test Cases by Requirement
It allows us to implement Most common way to see what features are being tested, and see how many tests we have aligned with a user story or requirement.

<table>
  <tr>
    <th>REQ</th>
    <th>TC Name</th>
    <th>Test Result</th>
  </tr>
  <tr>
    <td>REQ 1</td>
    <td>Hosted Site is working or not</td>
    <td>Pass</td>
  </tr>
  <tr>
    <td>REQ 2</td>
    <td>New pages added successfully or not</td>
    <td>Failed</td>
  </tr>
  
</table>

### Defects per Requirement (Requirement Defect Density)
Defect density per requirement helps uncover which requirement are more risky than others. For example, the test cases might be fine, but the requirement might be what’s causing all the problems.

<table>
  <tr>
    <th>Req name</th>
    <th>Total Number of Defects</th>
  </tr>
  <tr>
    <td>Adding new Pages</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Gathering info</td>
    <td>2</td>
  </tr>
</table>

### Referances 


[Referance](https://www.qasymphony.com/blog/64-test-metrics/)