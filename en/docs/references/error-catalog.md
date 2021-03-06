# Error Catalog
This document describes all the REST API error codes that are used in WSO2 Identity Server. 

## Common Errors

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
  <tr>
    <td>UE-10000</a></td>
    <td>400</td>
    <td>Invalid Request</td>
    <td>Provided request body content is not in the expected format.</td>
  </tr>
    <tr>
    <td>SE-50000</td>
    <td>500</td>
    <td>Unexpected processing error</td>
    <td>Server encountered an error while serving the request.</td>
  </tr>
  </tbody>
</table>
</div>

## Challenge Question Management

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
  <tr>
    <td>CQM-10002</td>
    <td>500</td>
    <td>Unable to retrieve challenges for the user</td>
    <td>Server encountered an error while retrieving challenges for the user.</td>
  </tr>
  <tr>
    <td>CQM-10003</td>
    <td>500</td>
    <td>Unable to retrieve all user challenge answers</td>
    <td>Server encountered an error while retrieving challenge answers of the user.</td>
  </tr>
  <tr>
    <td>CQM-10004</td>
    <td>500</td>
    <td>Unable to retrieve the user challenge answer of a specific challenge</td>
    <td>Server encountered an error while retrieving the challenge answer of a specific challenge.</td>
  </tr>
  <tr>
    <td>CQM-10005</td>
    <td>500</td>
    <td>Unable to set user challenge answers.</td>
    <td>Server encountered an error while setting answers to the user challenges.</td>
  </tr>
  <tr>
    <td>CQM-20053</td>
    <td>400</td>
    <td>Unable to set user challenge answers.</td>
    <td>Validation error. Cannot answer two questions from the same question set claim uri.</td>
  </tr>
  <tr>
    <td>CQM-10006</td>
    <td>500</td>
    <td>Unable to update user challenge answer.</td>
    <td>Server encountered an error while updating the answers to the user challenges.</td>
  </tr>
  <tr>
    <td>CQM-10007</td>
    <td>500</td>
    <td>Unable to remove user challenge answers.</td>
    <td>Server encountered an error while removing answers of the user challenges.</td>
  </tr>
  <tr>
    <td>CQM-10008</td>
    <td>500</td>
    <td>Unable to update user challenge answer.</td>
    <td>Server encountered an error while updating the answer of a specific user challenge.</td>
  </tr>
  <tr>
    <td>CQM-10009</td>
    <td>500</td>
    <td>Unable to update user challenge answer.</td>
    <td>Server encountered an error while updating the answer of the user challenge.</td>
  </tr>
  <tr>
    <td>CQM-10010</td>
    <td>500</td>
    <td>Unable to remove user challenge answer.</td>
    <td>Server encountered an error while removing answer of the user challenge.</td>
  </tr>
  <tr>
    <td>CQM-10011</td>
    <td>400</td>
    <td>Invalid Request.</td>
    <td>Challenge question is missing in the user challenge answer request.</td>
  </tr>
  <tr>
    <td>CQM-10012</td>
    <td>409</td>
    <td>Challenge questions are already answered.</td>
    <td>User has already answered some challenges. Hence, the system is unable to add new answers.</td>
  </tr>
  <tr>
    <td>CQM-10013</td>
    <td>404</td>
    <td>Challenge answers not set</td>
    <td>User has not answered any challenges. Hence, the system is unable to process.</td>
  </tr>
  <tr>
    <td>CQM-10014</td>
    <td>409</td>
    <td>Challenge answer already set</td>
    <td>User has already answered this challenge. Hence, the system is unable to add a new challenge answer.</td>
  </tr>
  <tr>
    <td>CQM-10015</td>
    <td>404</td>
    <td>Challenge answer not set </td>
    <td>User has not answered this challenge. Hence, the system is unable to process.</td>
  </tr>
  <tr>
    <td>CQM-20054</td>
    <td>400</td>
    <td>Unable to set user challenge answer(s).</td>
    <td>Invalid Locale value provided : <locale>.</td>
  </tr>
  <tr>
    <td>CQM-20056</td>
    <td>400</td>
    <td>Unable to add challenge set.</td>
    <td>ChallengeSetId contains non alpha-numeric characters.</td>
  </tr>
  <tr>
    <td>CQM-18017</td>
    <td>400</td>
    <td>Unable to set user challenge answers.</td>
    <td>No challenge question found. Error persisting user challenge answers for user. Challenge question answered is not registered with <tenant> domain.</td>
  </tr>
  <tr>
    <td>CQM-20057</td>
    <td>500</td>
    <td></td>
    <td>Error when deleting challenge question sets.</td>
  </tr>
  <tr>
    <td>CQM-50002</td>
    <td>500</td>
    <td>Unable to get challenge</td>
    <td>Server encountered an error while retrieving a specific challenge.</td>
  </tr>
  <tr>
    <td>CQM-50003</td>
    <td>500</td>
    <td>Unable to get the challenges</td>
    <td>Server encountered an error while retrieving all challenges.</td>
  </tr>
  <tr>
    <td>CQM-50004</td>
    <td>500</td>
    <td>Unable to add challenge set</td>
    <td>Server encountered an error while setting answers to the user challenges.</td>
  </tr>
  <tr>
    <td>CQM-50005</td>
    <td>500</td>
    <td>Unable to update challenge set</td>
    <td>Server encountered an error while updating answers to the user challenges.</td>
  </tr>
  <tr>
    <td>CQM-50006</td>
    <td>500</td>
    <td>Unable to add a new challenge question</td>
    <td>Server encountered an error while adding a new question to the set.</td>
  </tr>
  <tr>
    <td>CQM-50007</td>
    <td>500</td>
    <td>Unable to remove challenges</td>
    <td>Server encountered an error while removing the challenge set.</td>
  </tr>
  <tr>
    <td>CQM-50008</td>
    <td>500</td>
    <td>Unable to remove challenge question</td>
    <td>Server encountered an error while removing a specific challenge question.</td>
  </tr>
  <tr>
    <td>CQM-50009</td>
    <td>400</td>
    <td>Patch operation not supported</td>
    <td>Operation is not supported on the challenge set patch API.</td>
  </tr>
  <tr>
    <td>CQM-50010</td>
    <td>404</td>
    <td>Challenge set does not exist</td>
    <td>Specified challenge set does not exist in the system, hence unable to proceed.</td>
  </tr>
  <tr>
    <td>CQM-20055</td>
    <td>400</td>
    <td>Unable to add challenge set</td>
    <td>Attributes of hallenge question to be set cannot be empty.</td>
  </tr>
  </tbody>
</table>
</div>

## Human Task Approval Errors

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
      <tr>
        <td>HTA-10001</a></td>
        <td>403</td>
        <td>Access denied.</td>
        <td>You are not authorized to perform this task.</td>
      </tr>
      <tr>
        <td>HTA-10002</a></td>
        <td>400</td>
        <td>Invalid input provided.</td>
        <td>The provided Task ID is not in the correct format.</td>
      </tr>
      <tr>
        <td>HTA-10003</a></td>
        <td>404</td>
        <td>Task does not exist.</td>
        <td> </td>
      </tr>
      <tr>
        <td>HTA-10004</a></td>
        <td>400</td>
        <td>Invalid input data provided.</td>
        <td> </td>
      </tr>
      <tr>
        <td>HTA-10005</a></td>
        <td>400</td>
        <td>Unacceptable input provided.</td>
        <td>Only [CLAIM, RELEASE, APPROVED, REJECTED] are acceptable.</td>
      </tr>
      <tr>
        <td>HTA-10006</a></td>
        <td>400</td>
        <td>Unable to change the approval status.</td>
        <td>Invalid state change is requested for the given task.</td>
      </tr>
      <tr>
        <td>HTA-10007</a></td>
        <td>400</td>
        <td>Unable to update the approval status.</td>
        <td>Invalid state change is requested for the given task.</td>
      </tr>
      <tr>
        <td>HTA-15002</a></td>
        <td>500</td>
        <td>Unable to retrieve approvals for the user.</td>
        <td>Server encountered an error while retrieving approvals for user.</td>
      </tr>
      <tr>
        <td>HTA-15003</a></td>
        <td>500</td>
        <td>Unable to retrieve the user approval.</td>
        <td>Server encountered an error while retrieving information on the approval task.</td>
      </tr>
      <tr>
        <td>HTA-15004</a></td>
        <td>500</td>
        <td>Unable to update the approval status.</td>
        <td>Server encountered an error while updating the approval task status.</td>
      </tr>
  </tbody>
</table>
</div>

## OAuth Authorized Apps Errors

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
      <tr>
        <td>OAA-10001</a></td>
        <td>404</td>
        <td>Invalid application ID.</td>
        <td>An application with provided ID cannot be found for the user.</td>
      </tr>
      <tr>
        <td>OAA-10002</a></td>
        <td>500</td>
        <td>Error retrieving authorized application.</td>
        <td>A system error occurred while retrieving the provided authorized application for the user.</td>
      </tr>
      <tr>
        <td>OAA-10003</a></td>
        <td>500</td>
        <td>Error retrieving authorized applications.</td>
        <td>A system error occurred while retrieving authorized applications for the provided user.</td>
      </tr>
      <tr>
        <td>OAA-10004</a></td>
        <td>500</td>
        <td>Error revoking authorized application.</td>
        <td>A system error occurred while revoking the provided authorized application for the user.</td>
      </tr>
      <tr>
        <td>OAA-10005</a></td>
        <td>500</td>
        <td>Error revoking authorized application.</td>
        <td>A system error occurred while revoking authorized applications for the provided user.</td>
      </tr>
  </tbody>
</table>
</div>

## User Associations Errors

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
      <tr>
        <td>UAA-8500</a></td>
        <td>400</td>
        <td>Error while adding associations of user</td>
        <td>Valid username and password must be provided.</td>
      </tr>
      <tr>
        <td>UAA-8501</a></td>
        <td>500</td>
        <td>Error while adding associations of user.</td>
        <td>Error occurred while associating the user account.</td>
      </tr>
      <tr>
        <td>UAA-8503</a></td>
        <td>500</td>
        <td>Error while deleting user association</td>
        <td>Database error occurred while deleting user account association.</td>
      </tr>
      <tr>
        <td>UAA-8504</a></td>
        <td>500</td>
        <td>Error while adding associations of user.</td>
        <td>Database error occurred while creating user account association.</td>
      </tr>
      <tr>
        <td>UAA-8505</a></td>
        <td>500</td>
        <td>Error while adding associations of user</td>
        <td>Database error occurred while updating user account association.</td>
      </tr>
      <tr>
        <td>UAA-8506</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Database error occurred while validating user association.</td>
      </tr>
      <tr>
        <td>UAA-8507</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Database error occurred while deleting user account associations.</td>
      </tr>
      <tr>
        <td>UAA-8508</a></td>
        <td>500</td>
        <td>Error while etting/creating/deleting associations of user.</td>
        <td>Error occurred while getting the RealmService.</td>
      </tr>
      <tr>
        <td>UAA-8509</a></td>
        <td>500</td>
        <td>Error while etting/creating/deleting associations of user.</td>
        <td>Error occurred while accessing the RealmService.</td>
      </tr>
      <tr>
        <td>UAA-8510</a></td>
        <td>500</td>
        <td>Error while etting/creating/deleting associations of user.</td>
        <td>Error occurred while getting the RealmService.</td>
      </tr>
      <tr>
        <td>UAA-8511</a></td>
        <td>500</td>
        <td>Error while getting associations of user.</td>
        <td>Error occurred while getting tenant name from tenant id.</td>
      </tr>
      <tr>
        <td>UAA-8512</a></td>
        <td>500</td>
        <td>Error while getting/creating/deleting associations of user</td>
        <td>Error occurred while getting tenant id from tenant name.</td>
      </tr>
      <tr>
        <td>UAA-8512</a></td>
        <td>400</td>
        <td>Error while getting/creating/deleting associations of user</td>
        <td>Error occurred while getting tenant id from tenant name.</td>
      </tr>      
      <tr>
        <td>UAA-8513</a></td>
        <td>500</td>
        <td>Error while creating associations of user</td>
        <td>Error occurred while authenticating user.</td>
      </tr>
      <tr>
        <td>UAA-8514</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Error occurred while deleting user account association for user {{user}}.</td>
      </tr>
      <tr>
        <td>UAA-8517</a></td>
        <td>500</td>
        <td>Error while creating associations of user.</td>
        <td>Error occurred while executing pre/post user authenticators.</td>
      </tr>
      <tr>
        <td>UAA-8524</a></td>
        <td>400</td>
        <td>Error while getting/creating/deleting associations of user.</td>
        <td>Invalid or inactivated tenant domain</td>
      </tr>
      <tr>
        <td>UAA-8525</a></td>
        <td>409</td>
        <td>Error while adding associations of user</td>
        <td>Provided user account is already associated to the logged in user</td>
      </tr>
      <tr>
        <td>UAA-8526</a></td>
        <td>400</td>
        <td>Error while adding associations of user.</td>
        <td>The user name or password you entered is incorrect.</td>
      </tr>
      <tr>
        <td>UAA-8527</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Error occurred while deleting the user account association.</td>
      </tr>
      <tr>
        <td>UAA-8528</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Error occurred while deleting the user account associations for tenant id {{tenant Id}}.</td>
      </tr>
      <tr>
        <td>UAA-8533</a></td>
        <td>400</td>
        <td>Error while adding associations of user.</td>
        <td>User can not associate logged in user account to itself.</td>
      </tr>
      <tr>
        <td>UAA-8535</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Database error occurred while deleting user association from {{user store domain}} domain  in the tenant 
        {{tenant}}.</td>
      </tr>
      <tr>
        <td>UAA-8536</a></td>
        <td>500</td>
        <td>Error while adding associations of user.</td>
        <td>Error occurred while updating user domain of account associations with domain {{user store domain}}</td>
      </tr>
      <tr>
        <td>UAA-8537</a></td>
        <td>500</td>
        <td>Error while deleting user association.</td>
        <td>Error occurred while deleting user account associations with domain {{user store domain}} .</td>
      </tr>
      <tr>
        <td>UAA-8538</a></td>
        <td>500</td>
        <td>Error while getting associations of user</td>
        <td>Database error occurred while retrieving account associations of user {{user}}</td>
      </tr> 
      <tr>
        <td>UAA-8539</a></td>
        <td>500</td>
        <td>Error while getting/creating/deleting associations of user.</td>
        <td>Error while retrieving tenant ID of user {{user}}.</td>
      </tr>                       
  </tbody>
</table>
</div>

## Session Management Errors

<div class="errorcode">
<table>
  <thead>
    <th>Error Code</th>
    <th>HTTP Status Code</th>
    <th>Error Message</th>
    <th>Possible Cause</th>
  </thead>
  <tbody>
      <tr>
        <td>USM-15001</a></td>
        <td>500</td>
        <td>Unable to retrieve session information.</td>
        <td>Server encountered an error while retrieving session information.</td>
      </tr>
      <tr>
        <td>USM-15002</a></td>
        <td>500</td>
        <td>Unable to retrieve sessions.</td>
        <td>Server encountered an error while retrieving session list of user, {userid/username}.</td>
      </tr>      
      <tr>
        <td>USM-10003</a></td>
        <td>501</td>
        <td>Pagination not supported.</td>
        <td>Pagination capabilities are not supported in this version of the API.</td>
      </tr>
      <tr>
        <td>USM-10004</a></td>
        <td>501</td>
        <td>Filtering not supported.</td>
        <td>Filtering capability is not supported in this version of the API.</td>
      </tr>  
      <tr>
        <td>USM-10005</a></td>
        <td>501</td>
        <td>Sorting not supported.</td>
        <td>Sorting capability is not supported in this version of the API.</td>
      </tr>
      <tr>
        <td>USM-15006</a></td>
        <td>500</td>
        <td>Unable to validate user.</td>
        <td>Server encountered an error while authorizing user, {userid/username}.</td>
      </tr> 
      <tr>
        <td>USM-10007</a></td>
        <td>403</td>
        <td>Action forbidden.</td>
        <td>User is not authorized to terminate this session.</td>
      </tr> 
      <tr>
        <td>USM-10008</a></td>
        <td>400</td>
        <td>Invalid user.</td>
        <td>User is not provided to perform session management tasks.</td>
      </tr>                 
      <tr>
        <td>USM-10009</a></td>
        <td>400</td>
        <td>Invalid session.</td>
        <td>Session ID is not provided to perform session termination.</td>
      </tr>  
      <tr>
        <td>USM-10010</td>
        <td>403</td>
        <td>Action Forbidden.</td>
        <td>User is not authorized to terminate the session/s.</td>      
      </tr>                 
  </tbody>
</table>
</div>

## Secondary User Store Errors

  <div class="errorcode">
  <table>
    <thead>
      <th>Error Code</th>
      <th>HTTP Status Code</th>
      <th>Error Message</th>
      <th>Possible Cause</th>
    </thead>
    <tbody>
        <tr>
          <td>SUS-50001</a></td>
          <td>500</td>
          <td>Unable to add the secondary user store.</td>
          <td>Server Encountered an error while adding secondary user store.</td>
        </tr>
        <tr>
          <td>SUS-50002</a></td>
          <td>500</td>
          <td>Unable to delete the secondary user store.</td>
          <td>Server Encountered an error while deleting the secondary user store.</td>
        </tr>
        <tr>
          <td>SUS-50003</a></td>
          <td>500</td>
          <td>Unable to get the configured user stores.</td>
          <td>Server Encountered an error while retrieving secondary user stores.</td>
        </tr>
        <tr>
          <td>SUS-50004</a></td>
          <td>500</td>
          <td>Unable to update the secondary user store configurations.</td>
          <td>Server Encountered an error while updating the secondary user store configurations.</td>
        </tr>
        <tr>
          <td>SUS-50005</a></td>
          <td>501</td>
          <td>Pagination not supported.</td>
          <td>Pagination capabilities are not supported in this version of the API.</td>
        </tr>
        <tr>
          <td>SUS-50006</a></td>
          <td>501</td>
          <td>Filtering not supported.</td>
          <td>Filtering capability is not supported in this version of the API.</td>
        </tr>
        <tr>
          <td>SUS-50007</a></td>
          <td>501</td>
          <td>Sorting not supported.</td>
          <td>Sorting capability is not supported in this version of the API.</td>
        </tr>
        <tr>
          <td>SUS-50008</a></td>
          <td>404</td>
          <td>Resource not found.</td>
          <td>Unable to find any user store's id with the provided identifier %s.</td>
        </tr>
        <tr>
          <td>SUS-50009</a></td>
          <td>500</td>
          <td>Unable to check RDBMS connection Health.</td>
          <td>Server Encountered an error while checking the data source connection.</td>
        </tr>
        <tr>
          <td>SUS-50010</a></td>
          <td>500</td>
          <td>Unable to retrieve the user store implementations.</td>
          <td>Server Encountered an error while retrieving the user store types.</td>
        </tr>
        <tr>
          <td>SUS-50011</a></td>
          <td>400</td>
          <td>Invalid Input.</td>
          <td>Provided Input is not valid.</td>
        </tr>
        <tr>
          <td>SUS-50012</td>
          <td>404</td>
          <td>Resource not found.</td>
          <td>Unable to find a required resource for this request.</td>
        </tr>
        <tr>
          <td>SUS-50013</td>
          <td>500</td>
          <td>Unable to get the user store by its domain id.</td>
          <td>Server Encountered an error while retrieving the user store by its domain id.</td>
         </tr>
    </tbody>
</table>
</div>
