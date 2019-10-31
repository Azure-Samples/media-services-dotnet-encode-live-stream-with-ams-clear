---
page_type: sample
languages:
- csharp
products:
- azure
description: "The sample shows how to create a channel that receives a single-bitrate live stream and encodes it to multi-bitrate stream."
urlFragment: media-services-dotnet-encode-live-stream-with-ams-clear
---

# Encode and Deliver a Live Stream with Azure Media Services v2 using .NET SDK

The sample shows how to create a channel that receives a single-bitrate live stream and encodes it to multi-bitrate stream.

## Running this sample

1. Use Nuget to install the latest Azure Media Services .NET SDK.
	
	[Install-Package windowsazure.mediaservices](https://www.nuget.org/packages/windowsazure.mediaservices).
2. Update the appSettings section of the app.config file with appropriate values. For more information, see [this](https://docs.microsoft.com/azure/media-services/media-services-use-aad-auth-to-access-ams-api) topic.

	<appSettings>
		<add key="AMSAADTenantDomain" value="tenant"/>
		<add key="AMSRESTAPIEndpoint" value="endpoint"/>
		<add key="AMSClientId" value="id"/>
		<add key="AMSClientSecret" value="secret"/>
	</appSettings>

3. Review the [Working with Channels that are Enabled to Perform Live Encoding with Azure Media Services](http://azure.microsoft.com/documentation/articles/media-services-manage-live-encoder-enabled-channels/) topic.

## About the code

For more information, see [Create Channels that Perform Live Encoding from a Single-bitrate to Multi-bitrate Stream using .NET SDK](https://azure.microsoft.com/en-us/documentation/articles/media-services-dotnet-creating-live-encoder-enabled-channel/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
