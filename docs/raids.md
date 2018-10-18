# Raids

To assist in co-ordinating raids we use the Discord Bot PokeNav. PokeNav makes it easy to announce and receive notifications of upcoming raids by using simple Discord functions such as posting screenshots and reacting to posts.

## Regions / Areas

Each [region](trainer-setup#regions) has its own raid announcement channel.
You will need to be part of a region before you can post or see raids for that region.
To setup the regions you are part of, follow the instructions under [Trainer Setup](trainer-setup#regions).

## Announcing a Raid
To announce a raid simply take a screenshot in Pokemon Go showing either the egg or raid boss inside the gym screen.
Using the Discord mobile app, upload your screenshot to the region raid channel.

PokeNav will take a second to properly scan and identify the raid times and locations and will create a channel for your raid under the "Raid Channels" category.

You can also use the text commands for announcing a raid. The format for a raid command is:
```
.<raid|egg> <boss|tier> "<gym>" <timer>
```
* `<raid|egg>` Either `.raid` or `.egg` depending on if the raid has already hatched or not.
* `<boss|tier>` You can put the raid level as `t1` to `t5` or enter the Pokemon's name. Use double quotes around the Pokemon's name if there is a space.pokemon
* `"<gym>"` The name of the gym. This __requires__ double quotes both sides to be recognised.
* `<timer>` Enter the time remaining for the either the egg to hatch or for the boss to despawn

## Joining a raid
By default only users who have joined the raid will be able to discuss and talk about the raid.
To join a raid, simply use the head reaction at the bottom of the raid announcement post in the regional channel.
Or, on the first post in the raid channel in the "Raid Parties" category.

Once you have joined a raid, you will be able to discuss and talk about the raid with other users.

You can tag other people in your raid by using the discord `@` command and typing the name of the raid channel, e.g. `@raid-boss-gym-749`

To let others know you have arrived at the gym type the command `.here` and if you have changed your mind, and don't want to be in the raid anymore type `.leave`.

## Updating a raid
Sometimes you may need to update the details of a raid, such as when the boss has hatched, or where an incorrect time was detected by PokeNav.

```
$boss <pokemon>
```
Set the Pokemon that hatched from the raid egg.

```
.gym <gym>
```
Updates the gym name of the raid. Where this matches a gym on [pokemongomap.info](https://pokemongomap.info), directions will be added to the raid.

```
$address <address>
```
Set the address for the raid. This will update the raid to include a Google Maps link to help others with directions to the raid.

## Personal Settings
A list of available settings you can change to customise your raiding experience.

```
.toggle auto-join-raids
```
Use this command to change whether you are automatically added to raids that you announce. By default this is on.

