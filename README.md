# AnimationThrowdown
Animation Throwdown scripts


These scripts get your deck card inventory, and output it as text

## Setup

### User info

To do API calls to kongregate, you need your player ID and password hash.  You can get these 
by turning on the "Developer Console" in your web browser, and investigating some of the traffic
while playing the game.  e.g., <<showurl>>

Once you have these, add them to a file called `.at_creds` in your home directory (`~/.at_creds`),
formatted as follows:

```
user_id=8679305
password_hash=6223462354724572
```
I'll add more details on this later.


### Mac software dependencies

You'll need a few programs you may not have installed yet.

```
brew install curl
brew install XMLStarlet
brew install jq
```



## Generate card inventory

In the directory where you cloned this, simply run 
```
make
```


