pipeline {
    agent {
        node {
            label "linux && java21"
        }
    }
    stages {

        stage("Build") {
            steps {
                echo("helo Build 1")
                sleep(5)
                echo("helo Build 2")
                echo("helo Build 3")
            }
        }

        stage("Test") {
            steps {
                echo("helo Test 1")
                sleep(5)
                echo("helo Test 2")
                echo("helo Test 3")
            }
        }

        stage("Deploy") {
            steps {
                echo("helo Deploy 1")
                sleep(5)
                echo("helo Deploy 2")
                echo("helo Deploy 3")
            }
        }
    }

    post {
        always {
            echo "saya berusaha untuk mengerti dan paham"
        }
        success {
            echo "yap, akhirnya saya sukses"
        }
        failure {
            echo "saya gagal, tapi akan mencoba terus"
        }
        cleanup {
            echo "ayo kita bangkit"
        }
    }
}
