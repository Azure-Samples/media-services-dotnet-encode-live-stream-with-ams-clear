---
services: media-services
platforms: dotnet
author: Juliako
---

# Encode and Deliver a Live Stream with Azure Media Services using .NET SDK

The sample shows how to create a channel that receives a single-bitrate live stream and encodes it to multi-bitrate stream.

## Running this sample

1. Use Nuget to install the latest Azure Media Services .NET SDK.
	
	[Install-Package windowsazure.mediaservices](https://www.nuget.org/packages/windowsazure.mediaservices).
2. Add the appSettings section to the app.config file, and set the values for your Media Services account name and account key.
		
		<?xml version="1.0"?>
		<configuration>
		  <appSettings>
		      <add key="MediaServicesAccountName" value="YouMediaServicesAccountName" />
		      <add key="MediaServicesAccountKey" value="YouMediaServicesAccountKey" />
		  </appSettings>
		</configuration>

3. Review the [Working with Channels that are Enabled to Perform Live Encoding with Azure Media Services](http://azure.microsoft.com/documentation/articles/media-services-manage-live-encoder-enabled-channels/) topic.


## About the code

For more information, see [Create Channels that Perform Live Encoding from a Single-bitrate to Multi-bitrate Stream using .NET SDK](https://azure.microsoft.com/en-us/documentation/articles/media-services-dotnet-creating-live-encoder-enabled-channel/).

## More information


You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
