pipeline{

agent any

stages{

	stage('Check Out SCM')
	{steps { git branch: 'main', url: 'https://github.com/kiran136/Pipeline-Job.git'}}
	
	stage('clone the code')
	{ 
	steps {
	sh 'echo clone the code'
	}
	}

stage('Execute unit test cases')
	{ 
	steps {
	sh 'echo Execute unit test cases'
	}}

stage('Building code')
	{ 
	steps {
	sh 'echo Building code'
	}}

stage('Deploy package to a dev server')
	{ 
	steps {
	sh 'echo Deploy package to a dev server'
	}}

stage('Deploy package to a QA server')
	{ 
	steps {
	sh 'echo Deploy package to a QA server'
	input 'Please approve for QA deployment'
	}}

stage('Deploy package to a Prod server')
	{ 
	steps {
	sh 'echo Deploy package to a Prod server'
		
	}}



}
}

