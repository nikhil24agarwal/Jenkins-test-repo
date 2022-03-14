pipeline{

  agent any
parameters {
        choice(
            name: 'LOB',
            choices: ['marsmaly', 'batauat', 'ckuatunnati'],
            description: 'Lobs for clients'
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
    }
}
}
