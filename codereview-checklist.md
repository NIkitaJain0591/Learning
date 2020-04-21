
<ul><b>Pre development checklist</b>
  <li>proper local setup with properly working pages</li>
  <li>latest code in local</li>
  <li>Dependency on other classes</li>
  <li>Impact on other components</li>
  <li>Negative and positive test cases</li>
</ul>
<ul><b>Development checklist</b>
  <li>null check for arguments and variables</li>
  <li>method should perform only one operation - use sub methods if required</li>
  <li>no hard coding - use contants(check if already available)</li>
  <li>avoid multiple if/else blocks</li>
  <li>avoid unneccessary loops</li>
  <li>donot repeat the code</li>
  <li>code should be formatted</li>
  <li>follow naming conventions</li>
  <li>avoid unnecessary comments</li>
  <li>avoid unnecessary logs</li>
  <li>write JUnit test cases if required</li>
</ul>
<ul><b>Architecture</b>
  <li>should be in sync with existing format</li>
  <li>should be placed under correct module</li>
  <li>components & templates should be named according to philips standards</li>
</ul>
<ul><b>AEM checklist</b>
  <li>Check if the path is a valid path before performing some operation on path</li>
  <li>Before getting a property, check if the node has the property</li>
  <li>configure proper values for different runmodes</li>
</ul>
<ul><b>Post development checklist</b>
  <li>Build the code and test all scenarios in local before committing to the branch</li>
  <li>Add proper commit message</li>
  <li>Build the module in Dev</li>
  <li>Execute the test cases for multiple locales</li>
  <li>If all test cases are success, raise a PR to master attaching the workitem</li>
  <li>Before assigning the story to QA, perform one round of testing in tst environment</li>
</ul>


