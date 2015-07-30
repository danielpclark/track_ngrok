### Track ngrok

UPDATED for NGROK 2!  Now without the need for `watir`, a browser, or anything
other than `t`.

Sometimes the home network may temporarily lose a connection.
When that happens ngrok changes the port you need for remote access.
~~This uses Watir to open a web browser and monitor which port is being
used on your local machine.~~  If the port ever changes it will use the
twitter command line client 't' to direct message you.

### Installation
```
gem install t
t authenticate
wget https://github.com/danielpclark/track_ngrok/blob/master/bin/track_ngrok
chmod +x track_ngrok
```
### Usage

```
track_ngrok -t your_twitter_handle -n "your ngrok options"
```
You can generally just give your twitter handle without ngrok options if you want a standard SSH tunnel.

~~NOTE: don't close the browser window that opens.~~

You can also leave off the ngrok options if you want to default to
sharing the SSH port 22

### Contribution

Yes
