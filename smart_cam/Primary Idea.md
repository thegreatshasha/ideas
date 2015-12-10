# Cloud based smart surveillance 

## How is this smart
Multi actor identity recogniser(neural net) + Activity mapper(neural net) + Threat assesment(neural net). It can identify multiple actors in the scene + what activity each actor is doing.
Have a default threat level for each actor. Terrorists + People with prior criminal backgrounds
Raise threat levels through a combination of user's threat level

## Components
* Actor database: Have a databse of actors. Actors all have bayesian threat levels as well as any other useful info. Don't know if we need support for non human actors.
* Identity Recogniser: The identity recogniser tells the most likely match in the actor databse.
* Activity Mapper: The activity mapper tells you the activity going on from a dataset of activites. Each activity has a threat level. For eg combat is a high threat activity.
* Miscellaneous Event Recogniser: Recognize events like fire which don't have an actor. This needs to be improved upon.
* Notifier: Notify people of the threat along with the assesment level. Support for sms, email, in app notifications.

## Applications
* Baby monitor
* Pet monitor
* Activity threat coupled with Actor history allows you to predict criminal 
* Detect key events like fighting, fire, tresspassing,  
* Government city wide surveillance. Smart city.
* Airport threat assesment by comparison with existing terrorist databases.
* Bank threat assesment.
* Monitor elderly people and kids in nursing homes. Threat if they fall down etc.
* Road safety: Detect collisions, traffic accidents on the streets and send emergency alert to hospitals.
* Detect 

## ThinkList
* Write this like a research paper.
* How can we apply this to services like periscope, meerkat? Can this help in indexing the videos somehow?

* Have to compare with existing approaches.
* Find out which companies use cctv control rooms. Should be a good application.
* Add a unique identifier for each object detected like man#34591, dog#91231  https://www.youtube.com/watch?v=aG7V7_zowZU

* If the identity mapper can further map identities
* Discuss this idea with profs etc.
* Does our actor recognizer work even in the night with infrared cameras?
* Turn on lights etc in the area, sound alarms
* For the cloud streaming feature, you can google up on meerkat, periscope etc's tech stack since they have nice 
* Make it smarter by adding focus on key event functionality. Restore to normal after key event gone.
* Can we use raspberry pi gpu in order to 

## Potential Issues
* How easy is the criminal database to find? Might be tougher in a country like India. How frequently is it updated?
* Will the intelligence layer be on the cloud or each individual webcam.
* Architecture of the neural nets. Do we need 3 of the time. How much time does it take for a feedforward pass?
* Internet connectivity: Do each of the smart cams have enough bandwidth to operate. How much band
* Video storage + Image storage.
* How safe are the video and image storage since historical values are of very high value here.
* Read up on live video architecture

## Competitor and what are you better at
* Smart cctv https://smartcctvfrs.wordpress.com/2015/03/06/your-face-becomes-a-barcode-algorithmic-surveillance/
* https://nest.com/camera/meet-nest-cam/
* https://www.youtube.com/watch?v=aG7V7_zowZU
* 

## Prototype Iterations
* v1: Just the cloud based camera
* v2: Activity detection for baby monitor, elderly monitor

## References
https://www.facebook.com/Engineering/videos/10153621574817200/