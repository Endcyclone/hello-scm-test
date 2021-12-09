node {
    stage('ハローワールド') {
        sh 'echo "Hello World!!!"'
    }
    stage('gitをクローン') {
        git('https://github.com/Endcyclone/hello-scm-test.git')
    }
    stage('ファイル確認') {
        sh 'ls -l'
    }
    stage('ファイル確認2') {
        sh 'ls -l'
    }
}