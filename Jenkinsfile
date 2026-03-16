@Library('jenkins-shared-library') _

def configMap = [
    project : "roboshop",
    component: "catalogue"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase("main")) { //if not equals to main
    nodejsEKSpipeline(configMap)
}
else {
    echo "please proceed with PROD"
}
