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
sh'javac helloworld.java'
}
}
stage('run')
{
steps{
sh ' java helloworld'
}
}
}
}
