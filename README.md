# ![LOGO](logo.png) DataFactoryManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataFactoryManagementClient API (version 2018-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/datafactory/2018-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:57+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the available Azure Data Factory API operations.

*Tags:* `operations`

#### Input Parameters
* `api-version` - _required_ - The API version.

### Lists factories under the specified subscription.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `api-version` - _required_ - The API version.

### Updates a factory's repo information.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `locationId` - _required_ - The location identifier.
* `api-version` - _required_ - The API version.

### Get exposure control feature for specific location.

*Tags:* `exposureControl`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `locationId` - _required_ - The location identifier.
* `api-version` - _required_ - The API version.

### Lists factories.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes a factory.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Gets a factory.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the factory entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Updates a factory.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Creates or updates a factory.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the factory entity. Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Lists datasets.

*Tags:* `datasets`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Deletes a dataset.

*Tags:* `datasets`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `datasetName` - _required_ - The dataset name.
* `api-version` - _required_ - The API version.

### Gets a dataset.

*Tags:* `datasets`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `datasetName` - _required_ - The dataset name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the dataset entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Creates or updates a dataset.

*Tags:* `datasets`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `datasetName` - _required_ - The dataset name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the dataset entity.  Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Get Data Plane access.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Get GitHub Access Token.

*Tags:* `factories`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Lists integration runtimes.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Deletes an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Gets an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the integration runtime entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Updates an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Creates or updates an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the integration runtime entity. Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Gets the on-premises integration runtime connection information for encrypting the on-premises data source credentials.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Get a SSIS integration runtime object metadata by specified path. The return is pageable metadata list.

*Tags:* `integrationRuntimeObjectMetadata`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Gets detailed status information for an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Create a linked integration runtime entry in a shared integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Retrieves the authentication keys for an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Get the integration runtime monitoring data, which includes the monitor data for all the nodes under this integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Deletes a self-hosted integration runtime node.

*Tags:* `integrationRuntimeNodes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `nodeName` - _required_ - The integration runtime node name.
* `api-version` - _required_ - The API version.

### Gets a self-hosted integration runtime node.

*Tags:* `integrationRuntimeNodes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `nodeName` - _required_ - The integration runtime node name.
* `api-version` - _required_ - The API version.

### Updates a self-hosted integration runtime node.

*Tags:* `integrationRuntimeNodes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `nodeName` - _required_ - The integration runtime node name.
* `api-version` - _required_ - The API version.

### Get the IP address of self-hosted integration runtime node.

*Tags:* `integrationRuntimeNodes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `nodeName` - _required_ - The integration runtime node name.
* `api-version` - _required_ - The API version.

### Refresh a SSIS integration runtime object metadata.

*Tags:* `integrationRuntimeObjectMetadata`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Regenerates the authentication key for an integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Remove all linked integration runtimes under specific data factory in a self-hosted integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Starts a ManagedReserved type integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Stops a ManagedReserved type integration runtime.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Force the integration runtime to synchronize credentials across integration runtime nodes, and this will override the credentials across all worker nodes with those available on the dispatcher node. If you already have the latest credential backup file, you should manually import it (preferred) on any self-hosted integration runtime node than using this API directly.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Upgrade self-hosted integration runtime to latest version if availability.

*Tags:* `integrationRuntimes`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `integrationRuntimeName` - _required_ - The integration runtime name.
* `api-version` - _required_ - The API version.

### Lists linked services.

*Tags:* `linkedServices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Deletes a linked service.

*Tags:* `linkedServices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `linkedServiceName` - _required_ - The linked service name.
* `api-version` - _required_ - The API version.

### Gets a linked service.

*Tags:* `linkedServices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `linkedServiceName` - _required_ - The linked service name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the linked service entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Creates or updates a linked service.

*Tags:* `linkedServices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `linkedServiceName` - _required_ - The linked service name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the linkedService entity.  Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Get a pipeline run by its run ID.

*Tags:* `pipelineruns`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `runId` - _required_ - The pipeline run identifier.
* `api-version` - _required_ - The API version.

### Cancel a pipeline run by its run ID.

*Tags:* `pipelineruns`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `runId` - _required_ - The pipeline run identifier.
* `isRecursive` - _optional_ - If true, cancel all the Child pipelines that are triggered by the current pipeline.
* `api-version` - _required_ - The API version.

### Query activity runs based on input filter conditions.

*Tags:* `activityruns`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `runId` - _required_ - The pipeline run identifier.
* `api-version` - _required_ - The API version.

### Lists pipelines.

*Tags:* `pipelines`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Deletes a pipeline.

*Tags:* `pipelines`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `pipelineName` - _required_ - The pipeline name.
* `api-version` - _required_ - The API version.

### Gets a pipeline.

*Tags:* `pipelines`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `pipelineName` - _required_ - The pipeline name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the pipeline entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Creates or updates a pipeline.

*Tags:* `pipelines`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `pipelineName` - _required_ - The pipeline name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the pipeline entity.  Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Creates a run of a pipeline.

*Tags:* `pipelines`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `pipelineName` - _required_ - The pipeline name.
* `api-version` - _required_ - The API version.
* `referencePipelineRunId` - _optional_ - The pipeline run identifier. If run ID is specified the parameters of the specified run will be used to create a new run.
* `isRecovery` - _optional_ - Recovery mode flag. If recovery mode is set to true, the specified referenced pipeline run and the new run will be grouped under the same groupId.
* `startActivityName` - _optional_ - In recovery mode, the rerun will start from this activity. If not specified, all activities will run.

### Query pipeline runs in the factory based on input filter conditions.

*Tags:* `pipelineruns`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Query trigger runs.

*Tags:* `triggerruns`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Lists triggers.

*Tags:* `triggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `api-version` - _required_ - The API version.

### Deletes a trigger.

*Tags:* `triggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.

### Gets a trigger.

*Tags:* `trigger`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.
* `If-None-Match` - _optional_ - ETag of the trigger entity. Should only be specified for get. If the ETag matches the existing entity tag, or if * was provided, then no content will be returned.

### Creates or updates a trigger.

*Tags:* `triggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.
* `If-Match` - _optional_ - ETag of the trigger entity.  Should only be specified for update, for which it should match existing entity or can be * for unconditional update.

### Lists rerun triggers by an original trigger name.

*Tags:* `rerunTriggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.

### Creates a rerun trigger.

*Tags:* `rerunTriggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `rerunTriggerName` - _required_ - The rerun trigger name.
* `api-version` - _required_ - The API version.

### Cancels a trigger.

*Tags:* `rerunTriggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `rerunTriggerName` - _required_ - The rerun trigger name.
* `api-version` - _required_ - The API version.

### Starts a trigger.

*Tags:* `rerunTriggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `rerunTriggerName` - _required_ - The rerun trigger name.
* `api-version` - _required_ - The API version.

### Stops a trigger.

*Tags:* `rerunTriggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `rerunTriggerName` - _required_ - The rerun trigger name.
* `api-version` - _required_ - The API version.

### Starts a trigger.

*Tags:* `triggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.

### Stops a trigger.

*Tags:* `triggers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The resource group name.
* `factoryName` - _required_ - The factory name.
* `triggerName` - _required_ - The trigger name.
* `api-version` - _required_ - The API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-datafactory-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
