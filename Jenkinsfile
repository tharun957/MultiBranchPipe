node('built-in')
{

stage('ContinuousDownload_loans')
         {
    git 'https://github.com/tharun957/MultiBranchPipe.git'
        }

stage('Continuousbuild_loans')
         {
   sh label: '', script: 'mvn package'
        }

}
