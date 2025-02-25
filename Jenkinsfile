pipeline{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/Vamshi0105/vamshi.git'
}
}
stage('build')
{
steps{
sh'javac hello.java'
}
}
stage('run')
{
steps{
sh 'hello.java'
}
}
}
}
