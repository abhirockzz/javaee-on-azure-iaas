## JavaEE on Azure

We will follow the most basic approach of deploying our Java EE app to the [Payara](https://payara.fish) application server which is setup in a [Virtual Machine on Microsoft Azure](https://azure.microsoft.com/services/virtual-machines/?WT.mc_id=data-0000-abhishgu) along with the [Azure Database for PostgreSQL](https://azure.microsoft.com/services/postgresql/?WT.mc_id=data-0000-abhishgu) service as the backend database. In essence, this is the combination of IaaS (Azure VM) along with a PaaS (managed `PostgreSQL` on Azure) 