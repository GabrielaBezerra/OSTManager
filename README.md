# OSTManager

OSTManager enables you to work with multiple *AVAudioPlayers* at the same time, anywhere in your code, and it's meant to be simple. It works like this: it has a singleton that needs to be initialized with the names of your tracks and *voilla*! You can play with your tracks anywhere you want, referencing them only by their file name! 

It's perfect for managing background music and ambience sounds in games, or when you need to play many sounds at the same time (dealing with channels) and mute/unmute them whenever you want and similar scenarios. 

**Important Info:** It is made on *Swift 3*, for *iOS 10*. So if you're using and older version of *Swift* or you project's *Deployment Target* is less than that, you are going to have a trouble when you use *Fade*. 

There's still a lot to be done. I'm doing my best to improve it! So, if you want to help me, feel free to contribute. 
