# Cryptomancy for Fate

## _Based on the **Cryptomancer** RPG by **Chad Walker**_

## Version 0.1 - 2017-06-23

### `/user/fabiocosta/ Disclamer_and_notes`

This is an adaptation of _Cryptomancy_, from [**Cryptomancer** RPG by Chad Walker](http://cryptorpg.com), for [**Fate Accelerated Edition** by _Evil Hat_](http://www.evilhat.com/home/wp-content/uploads/FAE.zip). Although this refers in some points to [_Masters of Umdaar_](http://www.drivethrurpg.com/product/155458/Masters-of-Umdaar-o-A-World-of-Adventure-for-Fate-Core), a _World of Adventure_ for Fate Accelerated by _Dave Joria_, the rules are generic enough to be used in any Fate Core or Accelerated based setting with little to nothing adaptation. All the moral rights were respected here.

This is part of [Mozilla Cryptomancer Challenge](https://github.com/MozillaFoundation/mpa-cryptomancer-challenge).

### `/user/fabiocosta/ Changelog`

+ 0.1: The first _"usable"_ adaptation - small fluffy, no setting (beside some tangent talk with Dave Joria's _Masters of Umdaar_) and no playtest done, some of the rules and fluffy from _Cryptomancer_ left behind. Bare metal to go Rock'n'roll. KILL THE MASTERS! HACK THE THINGS!

### `/root/fate/ Shards_and_Shardnet`

> #### Permissions and Costs
>
> + ___Permission:___ None
> + ___Cost:___ Stunt (indicating the posse of a Shard)

The Shards are special mystical crystals from the Demiurge Age (or before), that can be used to send _echoes_, messages to a _Shardnet_. There's no need to roll to send an _echo_: just take an action (or even a free action) to just _think_ about the message while holding the shard. 

So, to send an message to another person, one needs to have a shard from the same crystal the other have, so he can _echo_ his message into his _private shardnet_. The echo stays into the _shardnet_ by a time based on the number of shards that make them, in hours. For example, in a shardnet made of 6 shards, an echo stays on the shardnet by 6 hours, fading away after that.

Also, the most recent echoes resonates more powerful into the shardnet than the older ones, so sometimes try to read an older echo could be burdensome, needing some roll to find his total content (although just _know_ that there's an echo needs no check). This is useful as a way to find if an information is useful or not, or to find if someone echoed something and then echoed some corrections on his information from the older echoes.

There's no way to avoid someone to see shards not intended to him, except using the _Cryptomancy_ techniques: _cleartext_ echoes are public inside an _specific shardnet_, made from shards from the same crystal. There's some special magical procedures to hide and cypher the _echoes_, beside other things, called Cryptomancy.

### `/root/fate/ Cryptomancy`

> #### Permissions and Costs
>
> + ___Permission:___ Aspect indicating the knowledge on Cryptomancy
> + ___Cost:___ Stunts (for the _Cryptomancy_ Magics)

#### Keyphrase using

Using a _Keyphrase_ to send an _echo_ into a _shardnet_ (either private or Shardspace), is considered a _Clever_ _Create Advantage_ Roll against _Fair (+2)_ difficulty. In Failure, the echo was sent as _cleartext_ and/or there's a chance the sender sent the _Keyphrase_. In a Tie, the echo was sent as _cyphertext_, however there's a chance the sender accidently sent the _Keyphrase_ for the _echo_ with it (GM discretion).

Those who knows the _Keyphrase_ will automatically receive the _echo_ as cleartext: the mystical decrypting process is automatic as long the target knows the keyphrase. Anyone that looks for an encrypted echo into a shardnet but doesn't know the _keyphrase_ will only see gobleedegook. However, as this _keyphrase_ method is _simmetric_, those who use it need to secure the _shardnet_ by other was, as people that knows the keyphrase can either send or receive any message encrypted with the keyphrase.

##### Brute Force

Using Brute Force to discover the _Keyphrase_ has a difficult based on (a) the number of words in the keyphrase and (b) the size and how common it is in idioms. Foreigner words can offer +1 on the difficult to brute force the _keyphrase_. The roll is done by _Clever_ (or _Careful_) using the difficult based on the _Keyphrase_ (normally _Fair (+2)_). A Failure could result either in still having gibberish or on the original user being alerted on the compromise of that _Keyphrase_. However, in a Success, the character discover the _keyphrase_ and so can decrypt the _echo_.

#### True Name and Soul Key

Every living thing has a True Name, a special and unique name that was given someway (normally by their parents) to him. And with him there's a _Soul Key_ a mystical word, so powerful that freezes time. The Soul Key can't be passed through voice: even someone could say another's Soul Key (which is almost impossible), this would be not effective for any cryptomancy reason.

Anyone that knows someone's True Name can encrypt an echo that will be decrypt just by the Soul Key of that person. Also, someone can "authenticate" an echo by sending a message encrypted using his Soul Key, so someone that knows his True Name could see this message as sent by the person.

To use this, the sender needs to know the True Name of the receiver (as an Aspect) and use a _Clever_ _Create Advantage_, as in the _Keyphrase_. However, in case of failure, there's no way to either reveal the receiver's True Name or Soul Key, just the message was sent as _Cleartext_.

An important thing: ___if someone dies, his True Name became a simple Keyphrase___. This is important because, if someone kills other person and knows his True Name, there's some ways for him to pass on it, and, as the True Name is now a common _Keyphrase_, he could decrypt echoes sent encrypted with it. This will be important in the future. 

#### Cryptomancy Stunts

+ ___Denier:___ By using some Cryptomancy techniques, there's a way to bring down for some time a private shardnet. The character rolls his _Powerful_ against a difficult based on the size of the shardnet and if there's some kind of protections, from _Fair (+2)_ for shardnet with less than or 6 shards from even _Fantastic (+6)_ for shardnets with 20+ shards, as an _Attack_ action. If successful, ___No new shards___ can be created for some turns (at most, the end of the scene). This don't avoid people to look for echoes that were in the shardnet before the _Denier_
+ ___Tracer:___ Using his Cryptomancy techniques, a Tracer can track down where all the shards in the private shardnet is phisically. The characters needs to roll his _Careful_ against the size of the shardnet (as in the ___Denier___) as an _Overcome_ action. A Tie can result in general locations, while a success shows where each one is. A _Success With Style_ can result into a ___Precise location___ Aspect
+ ___Shard Scry:___ Using this magic, a cryptomancer can see everything that is happening where there's other shards from the shardnet, as the shards were security cameras. This is considered a _Create Advantage_ being _Clever_ action, against a difficult based on the Shardnet size. A _Tie_ gives a Scry boost that can be used only in shards that sent recently echoes that the user could understand (either cleartext or using _keyphrases_ or _True Names_ the user knows). With a Success, he can see everything in any shard that recently echoed anything, even the character being unable to decrypt. A _Success with Style_ allows the user to see everywhere, even on those places whose shards had not sent any live echo recently. Lasts by one scene or until disarmed by the cryptomancer
+ ___Shard Spike:___ a offensive tracking technique, is based on the cryptomancer lace the magic into an echo that will be encrypted and sent in the shardnet. When someone decrypt it, the Spike explodes, and the Cryptomancer knows it. This is a _Create Advantage_ action being _Sneaky_, the difficult based on the _Shardnet_. A Tie allow the cryptomancer to knows the Spike was triggered. A Success geolocate the victim (as by _Tracer_). A _Success with Style_ will also deal a 2-stress damage straight the victim's Consequences, because of the _Brain frying_ effect of the magic. Last until the spike is triggered or defused by the cryptomancer, and the cryptomancer can have only one spike active.

### `/root/fate/ The_Shardscape`

In the ancient past, even before the Demiurge time, a massive shard crystal was found in a big mountain. The Demiurge documents founds says that this crystal crashed in Umdaar ages before the Demiurge ascension, and the Gods themselves sent it to Umdaar. Some says that those who touched this crystal found knowledge beyond the wildest dreams from the humans or any race. Some, however, says that those who tried to touch it straight had gone totally, utterly bonkers, babbling about the future, the past, the stars and utterly having their mind shattered, crashed by the sheer, massive, quantities of knowledge they needed to process all those.

However, some discovered how to safely lapidate the crystal, taking some big shards to cities and, using this, they could create the _Shardscape_, a kind of public network where everyone could search for information.

However, there's some problems on the Shardscape.

First of all, the shards from _Shardscape_ are really big, too much to be practical for common use, the smallest ones at the size of a melon. So, very difficult to be transported.

Second, the ___Sheer volume of information___ on it turns very difficult to use it as communication network. The one who tries to find things into the Shardscape needs to really focus himself into the action, to "search" for the _echoes_ that they wants.

Third, unlike the _private shardnets_, in the Shardscape ___there's almnost no echo fading___, echoes getting into the Shardscape for months. This is important because:

1. There's no way to remove an echo from the Shardscape, so there's some problemns with fake information and so on;
2. Echoes encrypted with True Name can be read for other people, as soon the True Name owner is dead: this because the True Name then turns itself into a common _Keyphrase_, so everyone who knew it can decrypt any echo still on the True Name;

Fourth, if you want to send a message to a specific person, you'll need to make it clear somewhat that the message is for her specifically. Some techniques for this:

1. Using Cryptomancy, either by arranging a common _Keyphrase_ or by know her True Name
2. Just send as cleartext and using his common name, as it's a common practice for those who use the Shardscape search for their own common name to find information about him;
3. Using some initial information that put on focus on the message, like _"Looking for bodyguards at the Fartime Elysium"_, so everyone that is looking for a job as bodyguard and uses the Shardscape could find this echo easily. This can be used as a way to stabilish social networks inside the Shardscape: the _Fartime Monastery Monks_ are knows by using this, confident into the Elysium tradition of non-violence as a way to propagate echoes with information and requests otherwise impossible to be done. Some of the Masters, however, are accomplished on use this technique to bring innocent people under their grasp.

And another problem, no Cryptomancy spell (like _Denier, Tracer, Shard Spike_ and so) don't work in the _Shardscape_

#### Querying the Shardscape

For searching for some information in the Shardscape, the character needs to be totally concentrated on the action of _querying the Shardscape_ and roll against a _Fair (+2)_ difficult, until otherwise said, even if he was expecting echoes encrypted with _Keyphrases_ or _True Name_ cryptomancy: the sheer volume of information in the Shardscape is enough to make things burdensome. The GM can increase the difficult based on time and specifics, or can decrese it if he was trying some generic information (like, discovering if there's some job from a group he knows).

A Tie should be treated as an Success, but maybe he can take some ___Irrelevant Information___ with the desired echo. In case of Failure, a character can suffer a ___Too Much Information!!!___ Aspect (or similar), representing the amount of echoes he somewhat bring with the one he needed, as a Cost for the Success. A _Sucess with Style_ can bring some ___Extra Information___ useful for the characters.

### `/root/fate/ Bridging_Shardnets`

A _Private Shardnet_ is a good thing, but sometimes the use of private shardnets are limited by the small number of shards oft the same shard crystal, and so in the same shardnet. But using the _Shardscape_ has the drawbacks on the privacy and limitations because of the sheer volume of echoes on it.

But there's a way to use more than a shardnet for communication, and it is by bridging the communication between two shardnets by holding shards of each shardnet on each hand, so the echoes from both shardnet resonates in both. The one who works as bridge can listen all the echoes on it (as long he could do it normally, like by knowing the _keyphrases_ involved), but can't echo himself any message. Also, this would be apply only for new echoes: old echoes don't replicate into the shardnets.

The new echoes into group of bridged shardnets stays on them as the bridged shardnets where only one: so, in two bridged shardnets with 4 shards each, the echoes resonates for 8 hours. So, a way to discover if there's any bridge in a shardnet that should not be bridged is by how much the echo stays on it.

You can expand even more the bridge, by putting a _"broker"_ shardnet that surrogates the echoes between two shardnets that otherwise could not be bridged (by any reason). The resonation time is calculated the same way, by summing all the shards in the shardnets in hours. Normally, when someone wants to send an echo to other people using a third shardnet as bridge, by travesing it, uses True Name to warrant the message arrive to the sender and only for them.

This can be used agrresively, by offer access to a shardnet for people that should not, and as long no echoes are send, it difficult to detect the bridge. It can be done even by bridging the shardnet to the _Shardspace_, by touching a Shardscape shard while holding a private shardnet. Or people could send echoes and echoes, so creating so much noise in the private shardnet that the communication could be impractical for hours!

#### Cryptoadmin

A _Cryptoadmin_ is someone that act as a facilitator on bridging shardnets, and as a registrar of all communications that passed by him, with informations on who created an echo (if possible), the content and keyphrases used (if possible). They also know the authorized users and their passphrases they use to prove their identities and to access their services, all of them registered into a _registry_.

A _Cryptoadmin_ can enforce security policies, by forcing people to exchange periodically their _Keyphrases_, scolding or kicking users that uses cleartext in the shardnet, query the Shardscape on the users' behalf if needed, and using challenge questions to detect if the shardnet was somehow compromised.

As they can take information from a shardnet and repass them to another, they can work as information broker for some groups: some of the Masters uses henchmen as Cryptoadmins, so they could insolate themselves and send information to and from troop via a broker. Because of this, their homes, _cryptovaults_, tends to be heavily fortified and/or in a inaccesible place. Considering the _registry_, this is also very important.

When they bridge two shardnets, is common protocol the Cryptoadmin to create and send into each shardnet a keyphrase that they could use for secure communication, so if there was a illegal bridge after the bridge being stabilished the communications could be still secure.

#### Golems

Created by the Demiurges or some people before, they are artificial constructs that, when he first activates, create a True Name and tell to a cryptoadmin. Since them he use his multiple squid like limbs to bridge shardnets, while one of them register the operations into a registry. In a very simple understanding, the Golems are a kinds of automated cryptoadmin, fasters and more capable than common cryptoadmins. So, a Golem has lots of shards near himself, and sometimes even a Shardscape shard.

The main problem is that Golems are expensive, needs a constant power source (like a waterwell or steam), and a cryptoadmin needs to be there to make maintenances on it. Also, a Golem is somewhat vulnerable physically, so they should be put into _cryptovaults_.

To use a Golem to send an echo to another shardnet he could, the sender should first send a message to the Golem encrypted with his True Name, and them the message, encrypted by any keyphrase or True Name that he wants. Then the Golem will send the echo through all the shardnets he can, including if needed the Shardscape.

Also, he can listen for echoes that are encrypted with his True Name from all shardnets he's connected, including the Shardscape: if someone in the Shardscape wants to send something to the shardnets connected to that Golem, he can do this by sending a message to it encripted with his True Name, the message being encrypted with any keyphrase or True Name he wanted.

Someone that knows the True Name of a Golem can use it to listen for some specifics keyphrases, by sending them to the Golem using a message encrypted with its True Name. Every echo in the shardnets that the Golem can access, including the Shardscape, are sent for the shardnet that send the message. This could be a problem, as someone could try to take down the shardnet and even the Golem by sending lots and lots of messages and mae the Golem goes down being unable to traverse all the messages to the shardnet, or to create so much noise the target shardnet could not be usable.

### `/root/fate/ Authentication_And_Cryptogears`

Many shardnets, specially those that have cryptoadmins and/or Golems on it, can use some _Authentication_ to use it, so the cryptoadmin/Golem could verify if the user is who they say they are and, by this, registry and somehow grant or forbid access to some shardnets or keyphrases he can listen or echo on it. Normally, the authentication on a shardnet secured this way is done by sending his name and a presetted passphrase, encrypting this message by the same combination of name and passphrase as keyphrase. When he authenticates, the cryptoadmin confirms if he's an authorized user and grants the access for the resources he can use. Sometimes, in some shardnets that has some secured parts, some kind of Banners (we'll see more about this later) can be set by Cryptoadmins, so new users (or lazy ones) can be remembered on the procedures to authenticate into the shardnet.

An even more complex and secure authentication is the _True Authentication_, that is based on _True Name_: when touching the secure shard, the used send his common name. The cryptoadmin/Golem encrypt a keyphrase with the True Name of the user (that he gave to them before). As only the Soul Key that matches that True Name (the user's) can receive the message, only him could receive the _keyphrase_. After that, the user uses the _keyphrase_ to ask for access to shardnet resources.

When the authentication potential of Cryptomancy was shown, some people started to develop _cryptogears_, mechanical devices that respond to operations based on cryptomancy authentication. The simpler one is the _cryptolock_, a lock with a shard imbedded on it that responds only when touched by the user, that them send a message with the passphrase encrypt with the passphrase (this is done to avoid the risk of someone just take an unused shard and listen to the passphrase as cleartext).

To change a cryptolock passphrase, you just need to send an echo with the new passphrase encrypted by the old one. If the cryptolock shard is removed, he can either get into a default state (like a door that should stay shut) or engage a security protocol (like start to make gas gone into the place).

There's some more complex cryptogears, like those who would rotate a chamber accordingly with the passphrase used. Constructing and repairing cryptogears (including changing the shard) are _Challenges_. Specially when repairing, while repairing, the cryptolock goes either in the default state or in the security protocol.

Some of the most complex or secure cryptogears can have their shards hidden somewhere, only a remotely placed "command shard" being used for issuing commands.

In Fate Rules, you can treat _cryptogears_ as Extras, and _cryptolocks_ as Aspects on it. If you have access to the _Fate Adversary Toolkit_, _Cryptolocks_ can be treated as a _Distraction_, _Countdowns_ and _Hazards_, like the sample below:

> __*Distraction:* A common Cryptolock__
>
> + __*Choice:*__ How the character will open the Cryptolock?
> + __*Opposition:*__ _Fair (+2)_
> + __*Repercussion (using the correct* Keyphrase *to activate it:)*__ The cryptolock will open correctly
> + __*Repercussion (trying to remove/change the Cryptolock shard:)*__ The cryptolock engage into a default state or security protocol
> + __*Hazard:*__ _Fair (+2)_ ***Knockout Gas Security Protocol*** _Weapon: 3_

### `/root/fate/ Cryptomancy_Magics_In_Real_Life`

There's some cryptomantic spells that can be used in "real life", to somewhat encrypt parts of reality or make some of the reality works with the shardnets. Some of them have limitations, the main one being that no cryptomantic spell works against the _Shardscape_: it's impossible to use the _Shardspace_ as a Shard Scry or to Trace someone via Shardscape. Also, it's impossible to do this by traversing shardnets, althought those directly bridged by real people (not by Golems) can be target of cryptomantic spells.

Below we list some of the more common cryptomantic spells that works into real life. Each one is treated as a Stunt, with an _Cryptomancer_ Aspect as a Permission, with the optional rule for the GM to treat them as small artifacts: the user needs to pay 1 FP to be able to use them for an adventure, and they need to find someone the give them some kind of parchment or otherwise give them a copy of the spell.

+ ___Babel:___ This magic can turn the voice of a target into a great babble for anyone that doesn't know an specific keyphrase, the Caster's Soul Key or a True Name that's not his own. It's considered an _Create Advantage_ action and the difficult is the _Careful_ (or _Powerful_) of the target (that can be the caster itself). In case of Failure, the caster itself is put under the Babel magic. The spell last until the caster revokes the spell, dies, or when too much people knows the keyphrase. During the effect of the spell, the target is under a _Incompreensive gobbledygook_ Aspect for everyone except the ones that know the keyphrase.
+ ___Dissemble:___ By touching the target face, the caster can turn the target face into an unrecognizable shifting mess for everyone that doesn't know an specific keyphrase, the Caster's Soul Key or a True Name that's not his own. It's considered an _Create Advantage_ action and the difficult is the _Careful_ (or _Powerful_) of the target (that can be the caster itself). In case of Failure, the caster itself is put under the Dissemble magic. The spell last until the caster revokes the spell, dies, or when too much people knows the keyphrase. During the effect of the spell, the target is under a _Unrecognizable shifting mess_ Aspect for everyone except the ones that know the keyphrase, his face and any distinguishible features turned into anything that could not be recognized by anyone except those who knows the keyphrase.
+ ___Messenger:___ By using this, the caster can invoke a magical creature that can deliver small objects for someone who he knows his True Name. This creature will do anything he can to deliver his cargo for the person, and he'll always who is the one he need to deliver the cargo (because of the True Name). He can be really fast and is ___Almost undetectable___, and they would not try to defend themselves if detected. It's a _Creat Advantage_ action being clever with a _Fair (+2)_ difficult to create the Messenger, with the result being the difficult of any roll to detect it.
+ ___Share Sight:___ With this spell, the character can share what he's seeing with a target. The character rolls his _Clever_ agains target's _Powerful_. If the target is a voluntary one, the roll is against _Mediocre (+0)_. This is considered a _Create Advantage_ action, but in case of Failure, _False visions_ can be sent for a voluntary target and for an involuntary target some _tactical advantage_ can be provided.
+ ___Maze:___ by using a Keyphrase, the caster can transform a door, portal or entrance of any kind into a vertigo-inducing puzzle for anyone that doesn't know the keyphrase, the Caster's Soul Key or a True Name that's not his own. This is a _Create Advantage_ being _Clever_ (or _Sneaky_) roll against _Fair (+2)_ difficult. The GM can raise the difficult by the size of the object. The spell last until the caster revokes the spell, dies, or when too much people knows the keyphrase. Closing the eyes doesn't work to try to cross a Maze enchanted entrance, but people can be led through the a Maze for someone that knows the keyphrase.
+ ___Name Wraith:___ (___Permission:___ at least two other Cryptomancy Spells) By using a target's True Name, the caster can invoke a shadowy spirit that will torment him to do whatever the Caster wants. Every night, the spirit get to the caster to see if there's new orders. This is a _Create Advantage_ roll using any specific Approach against target's _Powerful_. The compulsions will be based on the Approach used: a _Clever_ roll can maje the target do something that could be beneficial for the caster, but that could not necessarily put the target into risk (like _"I need to spy the Master's cargos"_), while a __Powerful_ or _Flashy_ roll could make the target takes unnecessary risks or fight their allies. The compulsion is put under the target as an Aspect. The spell last until the caster revokes the spell, dies, or when too much people knows the keyphrase. Every night, the caster can exchange the compulsion with another roll, with a +1 as the target is already enchanted. However, in a Failure the Name Wraith is dispelt and the target can grow conscious that he was under a Name Wraith. A Failure in the first cast can result in the Name Wraith offering the caster True Name and the target collude with it to torment or deceive the caster.
+ ___Shard Warp:___  (___Permission:___ at least two other Cryptomancy Spells) By focusing into a recently sent echo into a shard that the caster can Decrypt or that is a clear-text, the caster can teleport himself (and nothing else) through the shardnet to the place where the shard that sent the echo is. This is an _Overcome_ roll being _Clever_ (or Sneaky), the difficult based on the Shardnet size, as per the _Denier_ magic. In a _Tie_ the character arrives into the place he wants to but receive a 2-stress damage, although not straight in the Consequences. With a _Success with Style_, the caster can see the place before arrive and chose exactly the place and position he wants to arrive. In a Failure, the caster can turn into a bodiless consciousness into the shardnet, arrive somewhere else, or suffer a Moderate Consequence by lefting behind some of his limbs or forgetting something very important. Also he can send his plans as a cleartext into the shardnet and so on.

