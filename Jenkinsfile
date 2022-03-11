pipeline {
    agent {
           any
           }
    stages {
      stage('Promote scan') {
		steps {
			script {

                                 veracodesummaryreportXML = new XmlParser().parseText(Veracode.xml)
                                 for(veracodesummary in veracodesummaryreportXML.value()){
					//if((veracodesummary.attributes().severity == "High" &&  veracodesummary.attributes().count > 0) ||  (veracodesummary.attributes().severity == "Very High" && veracodesummary.attributes().count > 0)){
						//scanresult = failure
						println "The scan result is:"
					}
                           }
                        }
                  }
              }
            }
 }    
