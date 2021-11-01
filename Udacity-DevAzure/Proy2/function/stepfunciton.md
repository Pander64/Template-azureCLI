func init LocalAzureFuncProject --python
func init getnotes --python

cd LocalAzureFuncProj

func new --name getNotes --template "HTTP trigger" --authlevel "anonymous"
func new --name getNote --template "HTTP trigger" --authlevel "anonymous"

func start

func azure functionapp publish l2p3DemoPythonFunctionApp12345abc

Invoke funcition 
?name=Azure%20Functions