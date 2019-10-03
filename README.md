# YML Debugging

# Teammates:
* Brandon Hurrington
* Chris Coulon
* Marisha Hoza

# File 1:
* Error: during yml file upload, we could not progress to the next step because of an "invalid alphanumeric error" on the s3 bucket name
* Bug: bucket name was kebab-case
* Resolution: changed to camelCase
* PR: no, not pushing my github key thankyou
* [Front End](http://template1-coolreactbucket-qg9efn7xcu76.s3-website-us-west-2.amazonaws.com/)

We reviewed additional yml files for errors. Found some missing sections and keywords, but did not create additional pipelines.

### File 2:
* Bug: line 74 s3 bucket was private

### File 3:
* Bug: lines 40-43 did not reference variables

### File 4:
* Bug: missing CodeBuildRole entirely

### File 5:
* Bug: incorrect category on line 32, incorrect action on line 135, missing recursive on line 174

### File 6:
* Bug: order of github repo and github owner was flipped
