pipeline {
agent any
stages {
stage('Test') {
steps {
echo "steps"
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
