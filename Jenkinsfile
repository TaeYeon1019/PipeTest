pipeline {
    agent any
    parameters {
        booleanParam(name: 'STAGE_TEST', defaultValue: true, description: '是否运行节点 TEST')
    }
    stages {
        stage('Hello') {
            when {
                expression { return params.STAGE_TEST }
            }
            steps {
                echo 'Hello World_IOSTEST'
            }
        }
    }
}
