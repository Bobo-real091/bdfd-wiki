# $channelID[]
Returns the channel ID for the given channel name.

## Syntax
```
$channelID[Channel name]
```

### Parameters
- `Channel name` `(Type: String || Flag: Required)`: The name of the channel.

## Example
```
$nomention
Channel ID: $channelID[$message]
```

``` discord yaml
- user_id: 803569638084313098
  username: RainbowKey
  avatar: https://github.com/NilPointer-Software/bdfd-wiki/assets/113303649/a9034fd5-40c2-4320-a408-2f2ee0071d9d
  color: "#E67E22"
  content: |
    !example main-chat
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Channel ID: 566370477967147018
```

> It supports category names.

``` discord yaml
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    !example BDFD
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Channel ID: 1009019011545178132
```
