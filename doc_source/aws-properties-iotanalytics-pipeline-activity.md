# AWS IoT Analytics Pipeline Activity<a name="aws-properties-iotanalytics-pipeline-activity"></a>

<a name="aws-properties-iotanalytics-pipeline-activity-description"></a>The `Activity` property type specifies a list of activities for an AWS IoT Analytics pipeline\.

<a name="aws-properties-iotanalytics-pipeline-activity-inheritance"></a> `Activity` is a property of the [AWS::IoTAnalytics::Pipeline](aws-resource-iotanalytics-pipeline.md) resource\.

## Syntax<a name="aws-properties-iotanalytics-pipeline-activity-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-iotanalytics-pipeline-activity-syntax.json"></a>

```
{
  "[AddAttributes](#cfn-iotanalytics-pipeline-activity-addattributes)" : [*AddAttributes*](aws-properties-iotanalytics-pipeline-addattributes.md),
  "[Channel](#cfn-iotanalytics-pipeline-activity-channel)" : [*Channel*](aws-properties-iotanalytics-pipeline-channel.md),
  "[Datastore](#cfn-iotanalytics-pipeline-activity-datastore)" : [*Datastore*](aws-properties-iotanalytics-pipeline-datastore.md),
  "[DeviceRegistryEnrich](#cfn-iotanalytics-pipeline-activity-deviceregistryenrich)" : [*DeviceRegistryEnrich*](aws-properties-iotanalytics-pipeline-deviceregistryenrich.md),
  "[DeviceShadowEnrich](#cfn-iotanalytics-pipeline-activity-deviceshadowenrich)" : [*DeviceShadowEnrich*](aws-properties-iotanalytics-pipeline-deviceshadowenrich.md),
  "[Filter](#cfn-iotanalytics-pipeline-activity-filter)" : [*Filter*](aws-properties-iotanalytics-pipeline-filter.md),
  "[Lambda](#cfn-iotanalytics-pipeline-activity-lambda)" : [*Lambda*](aws-properties-iotanalytics-pipeline-lambda.md),
  "[Math](#cfn-iotanalytics-pipeline-activity-math)" : [*Math*](aws-properties-iotanalytics-pipeline-math.md),
  "[RemoveAttributes](#cfn-iotanalytics-pipeline-activity-removeattributes)" : [*RemoveAttributes*](aws-properties-iotanalytics-pipeline-removeattributes.md),
  "[SelectAttributes](#cfn-iotanalytics-pipeline-activity-selectattributes)" : [*SelectAttributes*](aws-properties-iotanalytics-pipeline-selectattributes.md)
}
```

### YAML<a name="aws-properties-iotanalytics-pipeline-activity-syntax.yaml"></a>

```
[AddAttributes](#cfn-iotanalytics-pipeline-activity-addattributes): 
  [*AddAttributes*](aws-properties-iotanalytics-pipeline-addattributes.md)
[Channel](#cfn-iotanalytics-pipeline-activity-channel): 
  [*Channel*](aws-properties-iotanalytics-pipeline-channel.md)
[Datastore](#cfn-iotanalytics-pipeline-activity-datastore): 
  [*Datastore*](aws-properties-iotanalytics-pipeline-datastore.md)
[DeviceRegistryEnrich](#cfn-iotanalytics-pipeline-activity-deviceregistryenrich): 
  [*DeviceRegistryEnrich*](aws-properties-iotanalytics-pipeline-deviceregistryenrich.md)
[DeviceShadowEnrich](#cfn-iotanalytics-pipeline-activity-deviceshadowenrich): 
  [*DeviceShadowEnrich*](aws-properties-iotanalytics-pipeline-deviceshadowenrich.md)
[Filter](#cfn-iotanalytics-pipeline-activity-filter): 
  [*Filter*](aws-properties-iotanalytics-pipeline-filter.md)
[Lambda](#cfn-iotanalytics-pipeline-activity-lambda): 
  [*Lambda*](aws-properties-iotanalytics-pipeline-lambda.md)
[Math](#cfn-iotanalytics-pipeline-activity-math): 
  [*Math*](aws-properties-iotanalytics-pipeline-math.md)
[RemoveAttributes](#cfn-iotanalytics-pipeline-activity-removeattributes): 
  [*RemoveAttributes*](aws-properties-iotanalytics-pipeline-removeattributes.md)
[SelectAttributes](#cfn-iotanalytics-pipeline-activity-selectattributes): 
  [*SelectAttributes*](aws-properties-iotanalytics-pipeline-selectattributes.md)
```

## Properties<a name="aws-properties-iotanalytics-pipeline-activity-properties"></a>

`AddAttributes`  <a name="cfn-iotanalytics-pipeline-activity-addattributes"></a>
Adds other attributes based on existing attributes in the message\.  
 *Required*: No  
 *Type*: [*AddAttributes*](aws-properties-iotanalytics-pipeline-addattributes.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Channel`  <a name="cfn-iotanalytics-pipeline-activity-channel"></a>
Determines the source of the messages to be processed\.  
 *Required*: No  
 *Type*: [*Channel*](aws-properties-iotanalytics-pipeline-channel.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Datastore`  <a name="cfn-iotanalytics-pipeline-activity-datastore"></a>
Specifies where to store the processed message data\.  
 *Required*: No  
 *Type*: [*Datastore*](aws-properties-iotanalytics-pipeline-datastore.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`DeviceRegistryEnrich`  <a name="cfn-iotanalytics-pipeline-activity-deviceregistryenrich"></a>
Adds data from the AWS IoT device registry to your message\.  
 *Required*: No  
 *Type*: [*DeviceRegistryEnrich*](aws-properties-iotanalytics-pipeline-deviceregistryenrich.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`DeviceShadowEnrich`  <a name="cfn-iotanalytics-pipeline-activity-deviceshadowenrich"></a>
Adds information from the AWS IoT Device Shadows service to a message\.  
 *Required*: No  
 *Type*: [*DeviceShadowEnrich*](aws-properties-iotanalytics-pipeline-deviceshadowenrich.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Filter`  <a name="cfn-iotanalytics-pipeline-activity-filter"></a>
Filters a message based on its attributes\.  
 *Required*: No  
 *Type*: [*Filter*](aws-properties-iotanalytics-pipeline-filter.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Lambda`  <a name="cfn-iotanalytics-pipeline-activity-lambda"></a>
Runs a Lambda function to modify the message\.  
 *Required*: No  
 *Type*: [*Lambda*](aws-properties-iotanalytics-pipeline-lambda.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`Math`  <a name="cfn-iotanalytics-pipeline-activity-math"></a>
Computes an arithmetic expression using the message's attributes and adds it to the message\.  
 *Required*: No  
 *Type*: [*Math*](aws-properties-iotanalytics-pipeline-math.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`RemoveAttributes`  <a name="cfn-iotanalytics-pipeline-activity-removeattributes"></a>
Removes attributes from a message\.  
 *Required*: No  
 *Type*: [*RemoveAttributes*](aws-properties-iotanalytics-pipeline-removeattributes.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`SelectAttributes`  <a name="cfn-iotanalytics-pipeline-activity-selectattributes"></a>
Creates a new message using only the specified attributes from the original message\.  
 *Required*: No  
 *Type*: [*SelectAttributes*](aws-properties-iotanalytics-pipeline-selectattributes.md)  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

## See Also<a name="aws-properties-iotanalytics-pipeline-activity-seealso"></a>
+ [ CreatePipeline](https://docs.aws.amazon.com/iotanalytics/latest/userguide/api.html#cli-iotanalytics-createpipeline) in the *AWS IoT Analytics User Guide\.*