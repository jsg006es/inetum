//pipeline declarativo
pipeline {
    
    //ejecutar desde cualquier nodo-agente disponible
    agent any
    
    //fases
    stages{
        
        stage("Build"){
            
            //pasos de la fase
            steps{
                
                echo "Building artifact";
            }
            
        }
        
        stage("Testing"){
            
            //pasos de la fase
            steps{
                
                echo "test unitarios";
                echo "test integracion";
                echo "test aceptacion";
            }
            
        }
        
        stage("Deploy"){
            
            //pasos de la fase
            steps{
                
                echo "desplegando artefacto";
            }
            
        }
        
    }
}
