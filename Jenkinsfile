pipeline{
    agent any
    stages{
        stage("Build"){
            when{
                changeRequest title:"when-pr"
            }
            steps{
                echo "Hello World building for change request"
            }
        }
    }
}
