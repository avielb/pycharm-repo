properties([parameters([string(defaultValue: 'aviel', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/avielb/pycharm-repo.git'
        sh "cat 1.txt"
        //bat "more 1.txt"
    }
}
