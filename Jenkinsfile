properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/NastyaMor42/nastya-new-rep.git'
    }
    stage("see all files"){
        bat "dir"
    }
}
