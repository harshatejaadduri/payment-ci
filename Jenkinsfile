@Library('jenkins-shared-libraries')_

def configMap = [
    project = "roboshop",
    component = "payment"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    pythonEKSPipeline(configMap)
}
else{
        echo "Proceed with PROD"
}