hubot-buffer
============

Hubot interface for Buffer.

## Configuration
- `HUBOT_BUFFER_TOKEN`
- `HUBOT_BUFFER_FACEBOOK`
- `HUBOT_BUFFER_LINKEDIN`
- `HUBOT_BUFFER_GOOGLE`
- `HUBOT_BUFFER_TWITTER`

## Commands
- `hubot <service> buffer <text>`
- `hubot buffer <text>`
- `hubot immediate <service> buffer <text>`
- `hubot immediate buffer <text>`
- `hubot show (me) (my) <service> buffer`
- `hubot show (me) (my) sent <service> buffer(s)`

## Notes
`HUBOT_BUFFER_TOKEN` is your API token. You'll need to create an app in the Buffer dashboard to get this value.

The rest of the environment variables are your profile IDs, and you're welcome to configure as few or many as you wish. You can get them from the buffer web interface, since your URL will look something like: `https://bufferapp.com/app/profile/<PROFILE ID>/buffer`


## Todo
- Tests!

## License
MIT
