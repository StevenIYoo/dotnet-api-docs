all: server.exe client.exe

server.exe: ChannelServices_registeredchannels_Server.cpp ChannelServices_registeredchannels_Share.dll
	cl /clr:pure ChannelServices_registeredchannels_Server.cpp

client.exe: channelservices_registeredchannels_client.cpp ChannelServices_registeredchannels_Share.dll
	cl /clr:pure ChannelServices_registeredchannels_client.cpp

ChannelServices_RegisteredChannels_Share.dll: ChannelServices_RegisteredChannels_Share.cpp
	cl /clr:pure /LD ChannelServices_RegisteredChannels_Share.cpp
