properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/BBlackHorsee/my-0507-project.git'
    }
    stage("show files"){
        // bat "dir"
    }
}
