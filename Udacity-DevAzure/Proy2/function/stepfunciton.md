func init LocalAzureFuncProject --python

cd LocalAzureFuncProj

func new --name PythonHttpExample --template "HTTP trigger" --authlevel "anonymous"

func start

func azure functionapp publish l2p3DemoPythonFunctionApp12345abc

Invoke funcition 
?name=Azure%20Functions