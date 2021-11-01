func init NeighborlyAPI --python

cd NeighborlyAPI

func new -n createAdvertisement -t "HTTP trigger" --authlevel "anonymous"
func new -n deleteAdvertisement -t "HTTP trigger" --authlevel "anonymous"
func new -n eventHubTrigger -t "Azure Event Hub trigger"
func new -n getAdvertisement -t "HTTP trigger" --authlevel "anonymous"
func new -n getAdvertisements -t "HTTP trigger" --authlevel "anonymous"
func new -n getPost -t "HTTP trigger" --authlevel "anonymous"
func new -n getPosts -t "HTTP trigger" --authlevel "anonymous"
func new -n updateAdvertisement -t "HTTP trigger" --authlevel "anonymous"

func start

func azure functionapp publish l2p3DemoPythonFunctionApp12345abc

Invoke funcition 
?name=Azure%20Functions