## Autotest UI project for demoqa.com
### Technologies used
<p  align="center">
<code><img width="5%" title="Python" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Python.svg/1024px-Python.svg.png"></code>
<code><img width="5%" title="Pycharm" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/PyCharm_Icon.svg/1200px-PyCharm_Icon.svg.png"></code>
<code><img width="5%" title="Pytest" src="https://upload.wikimedia.org/wikipedia/commons/b/ba/Pytest_logo.svg"></code>
<code><img width="5%" title="Selene" src="https://fs.getcourse.ru/fileservice/file/download/a/159627/sc/264/h/e0cabcb69a2df1e6b1086292c020a4a7.png"></code>
<code><img width="5%" title="Allure Report" src="https://avatars.githubusercontent.com/u/5879127?s=200&v=4"></code>
<code><img width="5%" title="Allure TestOps" src="https://marketplace-cdn.atlassian.com/files/92e2d8c3-2a30-46c0-bf21-2453a4a270d3?fileType=image&mode=full-fit"></code>
<code><img width="5%" title="Jira" src="https://logojinni.com/image/logos/jira-3.svg"></code>
<code><img width="5%" title="Jenkins" src="https://avatars.githubusercontent.com/u/2520748?v=4"></code>
<code><img width="5%" title="Selenoid" src="https://diginomica.com/sites/default/files/images/2017-09/docker-container.jpg"></code>
<code><img width="5%" title="GitHub" src="https://cdn-icons-png.flaticon.com/512/25/25231.png"></code>
</p>
<br> 

### What tests check
* Alert confirmation
* Alert confirmation with text field filling
* Opening a second tab in the browser
* Successful registration
* Successful registration with required fields
* Hint for text box
<br>


### <img width="3%" title="Jenkins" src="https://avatars.githubusercontent.com/u/2520748?v=4"> [Running a project in Jenkins](https://jenkins.autotests.cloud/job/qaguru_diploma_ui/)
##### Implemented parameterized assembly, to run the project you need to select a browser and its version.





### <img width="3%" title="Allure Report" src="https://avatars.githubusercontent.com/u/5879127?s=200&v=4"> Allure report
##### After passing the tests, the results can be viewed in the Allure report.


##### In the Behaviors tab there are collected test cases, which describe the steps. UI tests have attachments: screenshot, test video, log and page_source.


##### Test video Hint for text field.





### <img width="3%" title="Allure TestOps" src="https://marketplace-cdn.atlassian.com/files/92e2d8c3-2a30-46c0-bf21-2453a4a270d3?fileType=image&mode=full- fit"> [Integration with Allure TestOps](https://allure.autotests.cloud/project/2140/dashboards)

##### Also, all reporting is saved in Allure TestOps, where similar graphs are built.
![Graf](images/Testo.png)


#### In the suites tab, we can:
- Manage all test cases or each separately
- Rerun each test separately from all tests
- Set up integration with Jira
- Add manual tests, etc.

![tests](images/test cases.png)   

### <img width="3%" title="Jira" src="https://logojinni.com/image/logos/jira-3.svg"> [Jira Integration](https://jira.autotests.cloud/browse/HOMEWORK-658)
##### Having set up integration with Jira through Allure TestOps, you can forward the result of passing tests and a list of test cases from Allure to a ticket
