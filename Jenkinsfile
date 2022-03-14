pipeline{

  agent any
parameters {
        choice(
            name: 'LOB',
            choices: ['marsmaly', 'batauat', 'ckuatunnati'],
            description: 'Lobs for clients'
        )
	choice(
            name: 'ENVIRONMENT',
            choices: ['uat', 'dev', 'prod','demo'],
            description: 'Environemnt to run'
        )
	choice(
            name: 'VERSION',
            choices: ['1.0', '2.0', '3.0'],
            description: 'Versions'
        )
    }

  stages{
	stage("build"){
		steps{
      echo "build successfully"
    }
	}
		stage("Test"){
		steps{
			
      echo "tested successfully"
    }
		}
			stage("deploy"){
		steps{
      echo "deploy successfully"
			echo "LOB ${params.LOB}"
			echo "Environment ${params.ENVIRONMENT}"
			echo "Versions ${params.VERSION}"
    }
}
}
}
