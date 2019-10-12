node('master'){
   stage('git checkout'){
                  git 'https://github.com/ajitesh17/UI_NEW'
              }
   stage('angular build'){
             sh 'npm build'
             sh 'npm install'
             sh 'ng build'
         }
}
