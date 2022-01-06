pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh '''git clone https://github.com/abesrour1111/git_devops.git /var/lib/jenkinsdepotjenk
'''
      }
    }

    stage('stage2') {
      steps {
        sh '''if test `ls /var/lib/jenkins/depotjenk | wc ` -eq 2
then
grep -A1 modification gestion_groupes && grep -A1 modification gestion_utilisateurs 

else

echo "message d\'erreur, clone échoué"
fi
'''
      }
    }

  }
}