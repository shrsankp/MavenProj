node {
    stage('SCM Checkout')
    {
      git 'https://github.com/shrsankp/MavenProj.git'
    }
    stage('Compile & Package')
    {
      bat 'mvn clean compile'
    }
}
