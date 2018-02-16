pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				sh 'rm -rf /tmp/test_nginx'
				sh 'git clone https://Galucinogen:gfhjkmgfhjkm123@github.com/Galucinogen/test_nginx /tmp/test_nginx'
				sh 'git config --global user.name "Ruslan Shevchenko"'
				sh 'git config --global user.email galucinogen@gmail.com'
				sh 'cd /tmp/test_nginx && git commit --allow-empty -m "Trigger notification"'
				sh 'cd /tmp/test_nginx && git push'
            }
        }
    }
}
