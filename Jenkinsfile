node('slave1') {
    stage('first') {
        echo "This is first stage"
    }
    stage('second') {
        echo"This is second stage"
    }
    stage('checkout') {
        git 'https://github.com/anjibabu006/ant-sample.git'
    }
    stage('Build') {
        
        sh'''/opt/ant/bin/ant build -f build.xml'''
    }
}
