@Library('jenkins-shared-libraries')_

def configMap = [
    project = "roboshop",
    component = "payment"
]

if( ! env.BRANCH_NAME.equalsIngnoreCase('main') ){
    pythonEKSPipeline(configMap)
}
else{
        echo "Proceed with PROD"
}