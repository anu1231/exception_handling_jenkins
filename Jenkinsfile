pipeline {
agent any
stages {
stage('Test') {
steps {
sh 'make check'
}
}
}
post {
always {
echo "good"
}
failure {
echo "failed"
}
}
}
