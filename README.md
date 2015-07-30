### Track ngrok

UPDATED for NGROK 2!  Now without the need to `watir`, a browser, or anything
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
```
### Usage

```
bin/track_ngrok -t your_twitter_handle -n "your ngrok options"
```
~~NOTE: don't close the browser window that opens.~~

You can also leave off the ngrok options if you want to default to
sharing the SSH port 22

### Contribution

I'm looking for some serious intrest in this project.  If it gets
the love and attention it deserves I'll add some Open Source license
to it.  It's free to use now.  I'm thinking some flavor of GPL license
would be good (a NOT for profit tool).
