
<ul><b>Pre development checklist</b>
  <li>Proper local setup with properly working pages</li>
  <li>Latest code in local</li>
  <li>Understand the functionality of the component</li>
  <li>Dependency on other classes</li>
  <li>Impact on other components</li>
  <li>Negative and positive test cases</li>
  <li>Check if any sitetext is required</li>
</ul>
<ul><b>Development checklist</b>
  <li>Null check for arguments and variables</li>
  <li>Method should perform only one operation - use sub methods if required</li>
  <li>backward compatibility</li>
  <li>No hard coding - use contants(check if already available)</li>
  <li>Avoid multiple if/else blocks(use ternry operators if possible)</li>
  <li>Avoid unneccessary loops</li>
  <li>Donot repeat the code</li>
  <li>Code should be formatted</li>
  <li>Follow naming conventions</li>
  <li>Avoid unnecessary comments</li>
  <li>Avoid unnecessary log statements</li>
  <li>Check for sonar issues</li>
  <li>Write JUnit test cases if required</li>
</ul>
<ul><b>Architecture</b>
  <li>Should be in sync with existing format</li>
  <li>Should be placed under correct module</li>
  <li>Components & templates should be named according to philips standards</li>
</ul>
<ul><b>AEM checklist</b>
  <li>Check if the path is a valid path before performing any operation on path</li>
  <li>Before getting a property, check if the node has the property</li>
  <li>Configure proper values for different runmodes</li>
</ul>
<ul><b>Post development checklist</b>
  <li>Build the code and test all scenarios in local before committing to the branch</li>
  <li>Add proper commit message</li>
  <li>Build the module in Dev</li>
  <li>Execute the test cases for multiple locales</li>
  <li>If all test cases are success, raise a PR to master attaching the workitem</li>
  <li>Add a demo page link to the PR.</li>
  <li>Before assigning the story to QA, perform one round of testing in tst environment</li>
</ul>


