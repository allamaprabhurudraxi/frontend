node('master'){
   stage('git checkout'){
                  git 'https://github.com/allamaprabhurudraxi/UI_NEW.git'
              }
   stage('angular build'){
             sh 'npm build'
             sh 'npm install'
             sh 'npm run ng -- build --prod'
         }
}
