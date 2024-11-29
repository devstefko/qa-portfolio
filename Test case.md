1\. Using EP test design technique test following functionality \- *sort best rated benefit groups using location*.

| EP | TC |
| :---: | :---: |
| EP1: | Best Rated |
| EP2: | Beograd |
| EP3: | Novi Sad |

**Test case1**: Verify sorting best rated benefits using location filter.

**Precondition**: The user is logged in with his Benefiti account on a member page.

**Priority**: Medium  
 

| Steps | Test Steps | Test Data | Expected results |
| :---: | ----- | :---: | ----- |
| 1\. | Click on “Sort by” dropdown menu arrow from the right side bar under Sort Genefits Groups. | / | “Sort by” list is displayed. |
| 2\. | Select “Best rated” option from the list. | Best rated: Descending | Best rated: Descending is displayed. |
| 3\. | Click on locations drop down menu arrow from the sidebar and select Belgrade to choose the city. | Belgrade | The list of cities is displayed. The “Belgrade” option is selected and user is redirected to the page with best rated benefits in Belgrade. |

 

**Test case2**: Verify adding bonus budget for employees.

**Precondition**: User is logged in with an HR account.

**Priority**: High

 

| Steps | Test Steps | Test Data | Expected results |
| :---: | ----- | :---: | ----- |
| 1\. | Select “Search employees” field on top left side of the screen. | / | “Search employees” is selected. |
| 2\. | Type in the desired name in the selected field. | Stefanija | Employee with name “Stefanija” is displayed. |
| 3\. | Click on three dots on the right side to display a dropdown menu. | / | The dropdown menu is displayed. |
| 4\. | Select “Add bonus budget”. | Add bonus budget | The “Add bonus budget” option is selected. User is redirected to the pop-up page “Add bonus”. |
| 5\. | Select Bonus start day from the calendar | / | Today’s date is selected. |
| 6\. | Select Bonus end date. | / | The end bonus day is selected three months ahead today’s date. |
| 7\. | Enter numbers of tokens to add as bonus. | 500 | 500 tokens are displayed in token field. |
| 8\. | Click on blue button Add. | / | Green notification message is displayed: “Bonus successfully created.” and bonus is loaded to the employee’s account. |

**Test case3**: Verify adding company benefit group using wrong photo format.  
**Precondition**: The user is logged in with an HR account under company benefits tab.  
**Priority**: Medium

 

| Steps | Test Steps | Test Data | Expected results |
| :---: | ----- | :---: | ----- |
| 1\. | Click on “Add company benefit group” field on top left side of the screen. | / | A pop-up window “Add company benefit group” is open on the right side of the screen. |
| 2\. | Type in the desired name in the name field. | Testing Group | “Testing group” is displayed in the name field. |
| 3\. | Click on the arrow to access a dropdown menu and choose category. | / | The dropdown menu with listed categories is displayed. |
| 4\. | Select “IT equipment” category. | IT equipment | The “IT equipment” option is selected. |
| 5\. | Select “Click here to upload” at the bottom of the pop-up window. | Supported formats: .png, .jpg, .jpeg. | A new pop up window is open with “This PC” data. |
| 6\. | Choose the wrong format to upload. | .pdf | A broken image is displayed in the photo field. |
| 7\. | Click on “Add” blue button to upload the chosen file. | .pdf | The user remains on the same page and no warning notifications are displayed. |

**Test case4**: Verify that the graph-chart for best benefits is updated based on chosen month.

**Precondition**: The user is logged in HR dashboard.

**Priority**: Low

 

| Steps | Test Steps | Test Data | Expected results |
| :---: | ----- | :---: | ----- |
| 1\. | Click on date box within “Top benefits” card on top right side of the screen. | Calendar | A pop-up calendar is open with displayed months. |
| 2\. | Choose a previous month. | September | September is selected and the chart is updated. |
| 3\. | Click on the date box again and choose current month. | October | October is selected and the chart is updated. |
| 4\. | Click on the radio button “Previous month”. | Previous month | Previous month data are displayed and chart is updated. It is not written which month is displayed. |

   
