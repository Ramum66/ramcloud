pipeline {
    agent any
    stages {
        stage('invoking pr-pipeline') {
            steps {
                script {
                    println "if any changes come from outside prpipeline will invoke"
                    var1 = 10
                    println "my variable value is ${var1}"
                    for i in {1..10}
                    do
                        echo "my i value is $i"
                    done
                }
            }

        }

    }
}
