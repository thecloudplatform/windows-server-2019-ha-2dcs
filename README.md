# Create 2 new Windows Server 2019 VMs, create a new AD Forest, Domain and 2 DCs in an availability set

This template will deploy 2 new VMs (along with a new VNet, Storage Account and Load Balancer) and create a new AD forest and domain, each VM will be created as a DC for the new domain and will be placed in an availability set. Each VM will also have an RDP endpoint added with a public load balanced IP address.

Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fthecloudplatform%2Fwindows-server-2016-ha-2dcs%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fthecloudplatform%2Fwindows-server-2016-ha-2dcs%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
