# Sign Text

There are many things you can do with signs. A large amount of special codes can be typed into signs to make those signs do things (when written properly) This page will explain how to use these codes/signs.



## The Basics

First of all, most signs require a code word within a set of square brackets on the first line of the sign. Almost all sign's functions are determined by what the codeword is within those brackets. Secondly, most signs are only operable when your flying a ship, and others are part of multiblock machines (eg. shields, printers, turrets, ect.)



## Stand-alone Signs


### [helm]

#### Description:

The most vital and basic of the signs, by typing [helm] into a sign (should look like this)
{IMAGE OF SIGN APEARANCE BEFORE RIGHT-CLICKING}

followed by right-clicking that sign, will turn that sign into steering controls. (should look like this)
{IMAGE OF SIGN APEARANCE AFTER RIGHT-CLICKING}

These signs can only be used in a ship, but can be place anywhere in the ship

#### Usage:

While flying a ship, left-clicking that sign will turn your ship left, right-clicking that sign will turn your ship right. You can only rotate 90 degrees per a turn, and you cant turn your ship to face upwards or downwards. (See 'New Player Guide' for more on flying https://starlegacy.net/wiki/new_player_guide)



### [cruise]

#### Description:

The second-most vital and basic of the codewords, by typing [cruise] into a sign (should look like this)
{IMAGE OF SIGN APEARANCE BEFORE RIGHT-CLICKING}

followed by right-clicking that sign, will turn that sign into cruise controls.
{IMAGE OF SIGN APEARANCE AFTER RIGHT-CLICKING}

These signs can only be used in a ship, but can be place anywhere in the ship

#### Usage:

While flying a ship, right-clicking that sign will slowely and automaticaly make your ship move in the derection you were facing when you clicked the sign (Excluding up and down), you can only cruise in 8 directions. (north, east, south, west, NE, NW, SE, SW) While cruising, your ship will speed up at a certain rate utill you reach a certain speed (these factors depend on the amount and type of thrusters on your ship, and the power, size, wight, and class of your ship) (See 'Thrusters' for more info on that https://starlegacy.net/wiki/starships/thrusters)

If you turn your ship (using the [helm] sign) while cruising, your speed will temporarily decreese while your ship starts to arc into the new direction your facing (note, turning 180 degrees means your ship will come to a VERY slow stop before cruising in the new direction) even though you can cruise in 8 directions, you still can only do 90 degree turns. If your ship cant cruise any further because its ran into and object, then the ship will temporarily come to a halt, you'll have to shift-fly around that object, as soon as the object is out of the way, your ship will continue cruising without decreased speed.
{IMAGE OF TEXT SHOWN AT THE BOTTOM OF THE SCREEN SAYING "speed 'number'  bps 'number'"}
{IMAGE OF TEXT SHOWN AT THE BOTTOM OF THE SCREEN SAYING "path is blocked at 'xyz'"}

There are 3 ways to stop cruising, the first way is to left-click the sign, your ship's speed will slowely decrease at the same speed it accelerates at, untill it reaches a complete halt. The second way is to release your starship (by right-clicking the starship computer) the third way is by hitting the boarder of the map, as soon as it detects that it cant go any further without breaching the world boarder limit, your ship will instantly come to a halt.
{IMAGE OF TEXT SHOWN AT THE BOTTOM OF THE SCREEN SAYING "(left-click to stop) speed 'number'  bps 'number'"}
{IMAGE OF TEXT SHOWN WHEN CRUISING INTO THE BOARDER OF MAP}

 (See 'New Player Guide' for more on flying https://starlegacy.net/wiki/new_player_guide)



### [powermode]

#### Description:

A bit harder to understand when there isn't a wiki page about it or an admin/expirienced player online to help you, these signs allow you to change the power output around your ship of three catagorys: Shields, Weapons, & Thrusters.

To make these, you must know that theres a limit to the minimum power output:

> * Shields: 50%
>
> * Weapons: 10%
>
> * Thrusters: 10%

In the first line type [powermode], the second line must be a number between 50 & 80, the third must be a number between 10 & 40, the fourth must also be a number between 10 & 40, and MOST IMPORTANTLY, all three numbers MUST add up to 100, no more, no less, or the sign wont work. The end product should look something like this:
{IMAGE OF LOTS OF EXAMPLE SIGNs BEFORE RIGHT-CLICK}

Then right-click the sign to detect:
{IMAGE OF LOTS OF EXAMPLE SIGNs AFTER RIGHT-CLICK}

These signs can only be used in a ship, but can be placed anywhere in the ship.

#### Usage:

These signs can only be used in a ship, but can be place anywhere in the ship, and as long as your percentages are withing the limits, you can change the numbers to whatever you like. Right-clicking the sign while flying a ship will activate the effects of this sign, right-clicking another [powermode] with a different percentage will change your power output to that new signs stats, and releasing your starship will remove the effects.

> * A higher percentage for the shields will make the shields recharge faster.
>
> * A higher percentage for the weapons will make the heavy weapons recharge faster.
>
> * A higher percentage for the thrusters will make your cruise accelerate to max speed faster.





### [weaponset]

#### Description:

These signs allow you to select which weapons you want to shoot with, both the weaponset sign and the node sign MUST have tha same name inorder to work (see [node] under 'Multiblock Signs' for more information on nodes)
{IMAGE OF EXAMPLE [weaponset] SIGN NEXT TO EXAMPLE [node] SIGN ON GUN}

To make these, type in the first line [weaponset], and the name of the weaponset in the second line (note, you can't have spaces in the name otherwise the weaponset's functions wont work)
{IMAGE OF EDITING THE SIGN WITH AN EXAMPLE OF WHAT TO TYPE}

You don't need to right-click these signs, they automatically are detected as soon as you finish typing the sign.
{IMAGE OF EXAMPLE WEAPONSET SIGN}

#### Usage:

While flying a ship, right-clicking one of these signs willdisable every manual gun on your ship exept for the guns with [node] signs with the same name as the [weaponset] sign your using.

#### Before [weaponset] is activated
{IMAGE GIF OF BIRDS-EYE VIEW OF 3 GUNS SHOOTING}

#### After [weaponset] is activated
{IMAGE GIF OF BIRDS-EYE VIEW OF 1 OF 3 GUNS SHOOTING}

To deactivate the weaponset, just right click and this message should apear:
{IMAGE OF CHAT SAYING 'you have released EXAMPLE weaponset'}



## Multiblock Signs


### [node]

#### Description:

The more complex of the bunch, you make this by typing [node] in the first line, and what you want to name the node in the second line (note, you can't have spaces in the name otherwise the node's functions wont work)
{IMAGE OF EDITING THE SIGN WITH AN EXAMPLE OF WHAT TO TYPE}

Same as the [weaponset] signs, you don't need to right-click these signs, they automatically are detected as soon as you finish typing the sign.
{IMAGE OF EXAMPLE NODE SIGN}

These signs can only be used in a ship, but can be placed anywhere in the ship as long as its touching the base of a gun. (See image bellow)

There are 2 uses for nodes, option 1 is using them with an auto gun (see 'Weapons' https://starlegacy.net/wiki/starships/weapons) type the command "/st PLAYER-NAME NODE-NAME" to have all auto guns under that node name point and shoot at that player (excluding light and heavy auto turrets, which only shoot at a player when their flying a ship) Option 2 is to use them to select which guns you want to shoot with, to do this, place the sign at the base of the weapon:
{IMAGE OF MULTIABLE TYPES OF GUNS WITH [node] SIGNS}

See [weaponset] for more info on using guns with nodes.

### For more multiblock signs, see their respective pages.
