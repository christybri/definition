devops is a big methodologie in a IT field.
having a knowdlege on his concept will make you a success person in the field.
here is pipeline description
when the dev people plan code build the code,they perform a first test locally then commit to vcs.
now the ci tool come in place : the big jenkins which is an automation tool. before jenkins run the code,sonarqube do a test analytic on it to make sure the code have all the requierement necessary to go to the next step,so jenkins pull and run the test with maven integration and create an atifact who will be stored in the artifactory.
then will be deploy to the dev environement for other testing then in qa for more test and will continue to pre-prod then producton.
thank you. 