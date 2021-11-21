func init LocalAzureFuncProject --python
func init getnotes --python
func init NeighborlyAPI --python

cd LocalAzureFuncProj

func new --name getNotes --template "HTTP trigger" --authlevel "anonymous"
func new --name getNote --template "HTTP trigger" --authlevel "anonymous"

func start

func azure functionapp fetch-app-settings 'eventHubTrigger' --output-file local.settings.json

func azure functionapp publish l2p3DemoPythonFunctionApp12345abc

Invoke funcition 
?name=Azure%20Functions

