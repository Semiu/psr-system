node{'workers'}(
    try{
        stage('Checkout'){
            checkout scm
        }
        stage('Quality test'){
            echo 'Running quality tests'
        }
        stage('Unit test'){
            echo 'Running unit tests'
        }
        stage('Security test'){
            echo 'Running security tests'
        }
        stage('Build'){
            echo 'Building artifacts'
        }
        stage('Push'){
            echo 'Storing artifacts'
        }
        stage('Deploy'){
            echo 'Deploying artifacts'
        }
        stage('Acceptance Tests'){
            echo 'Running post-integrations tests'
        }
    }catch (err){
        echo 'Handling errors'

    }finally{
        echo 'Cleaning up'
    }
)