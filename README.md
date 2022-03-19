# Unity NFT Storage Client
A client for "nft.storage" and "IPFS" APIs, written in C# and compatible with Unity Engine. This is edit code from another github : https://github.com/filipepolizel/unity-nft-storage#Edited

the problem with main code was limited to text file but with this script you can put any format file (mp4,zip,...)
Support **HttpClient** and **unityWebrequest** . Use whichever you want . **unityWebrequest** have upload progess too.

## Setup
For using this library, just copy the [NFTStorageClient.cs](./NFTStorageClient.cs) source code file to your Unity project, preferably alongside other scripts. As any regular Unity C# script, the main class defined in this library inherits Unity's [MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html) class.


## Usage

Anyone registered to *nft.storage* (an API key is required) can use this library to store and persist game assets using IPFS system. Please check nft.storage [docs](https://nft.storage/#docs) for additional details.

The client library code is available in `NFTStorageClient.cs`, and contains the following public methods:

- **SetApiToken:** Configure nft.storage API token
- **ListFiles:** List all NFT uploaded files
- **GetFile:** Retrieve details on a specific uploaded file
- **GetFileData:** Retrieve data from a specific uploaded file
- **CheckFile:** Perform a integrity check on a specific uploaded file
- **DeleteFile:** Delete a specific uploaded file
- **UploadDataFromStringHttpClient:** Uploads a new file based on a file httpClient
- **UploadDataFromStringUnityWebrequest:** Uploads a new file based on a file unityWebrequest with upload progress

# Important
this code just edited And only to help other developers **Main Sourse** : https://github.com/filipepolizel/unity-nft-storage#Edited
