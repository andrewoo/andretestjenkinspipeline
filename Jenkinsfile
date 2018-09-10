// Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
        stage('Checking Technopedia version') {
            def testvalue='test'
            steps {
                
                echo ${testvalue}
                // println 'Technopedis DB host: 192.168.10.89'
                // def batstatus = bat(returnStatus: true, script: 'C:\\Users\\Administrator\\AppData\\Local\\Programs\\Python\\Python37\\python C:\\py\\getTechnopediaVersion.py') 
                // if ( batstatus==2 ) {
                //     currentBuild.result = 'FAILURE'
                //     println 'Unable connect to database.'
                //     bat 'python C:\\py\\common\\sendDingdingMessagepy.py --url="https://oapi.dingtalk.com/robot/send?access_token=b6297c7195cc4e7a35e30e13ddd1446c1d48ac77d8b6ddf0847d2e19cbd9fb4a" --content="Unable connect to database." --at="13570462144"'
                //     return
                // }else if (batstatus==1) {
                //         println 'Technopedia version no match,ignore this job.'
                //         bat 'python C:\\py\\common\\sendDingdingMessagepy.py --url="https://oapi.dingtalk.com/robot/send?access_token=b6297c7195cc4e7a35e30e13ddd1446c1d48ac77d8b6ddf0847d2e19cbd9fb4a" --content="Technopedia version no match,ignore this job." --at="13570462144"'
                //         return
                // }
        }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}