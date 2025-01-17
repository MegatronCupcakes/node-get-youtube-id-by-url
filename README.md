# Get YouTube ID By Url (Node.js Library)

Get YouTube channel or video id by url!

## Report Issues

Please report any bugs you discover at <https://github.com/MegatronCupcakes/node-get-youtube-id-by-url/issues>

## Installation

Node.js 12.0.0 or newer is required.

### With NPM

```sh-session
npm install @megatroncupcakes/get-youtube-id-by-url
```

## Examples

```javascript
import { channelId, videoId, channelIconById, channelIconByName } from '@megatroncupcakes/get-youtube-id-by-url'
```

### Get YouTube Channel ID By Url

```javascript
channelId('YouTube Channel Url').then((id) => {
  console.log(id)
})
```

Support URL format:

- https://www.youtube.com/channel/xxxxxxxxxxxxxxxxxxxxxxxx
- https://www.youtube.com/c/xxxxxxxx
- https://www.youtube.com/user/xxxxxxxx

### Get YouTube Video ID By Url

```javascript
videoId('YouTube Video Url').then((id) => {
  console.log(id)
})
```

Support URL format:

- https://www.youtube.com/watch?v=xxxxxxxxxxx
- https://youtu.be/xxxxxxxxxxx

### Get YouTube Channel Icon By Channel ID

```javascript
channelIconById('YouTube Channel ID').then((iconUrl) => {
  console.log(iconUrl)
})
```
### Get YouTube Channel Icon By Channel Name

```javascript
channelIconByName('YouTube Channel Name').then((iconUrl) => {
  console.log(iconUrl)
})
```

## License

[MIT](LICENSE)
