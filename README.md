# CivBot

- [**invite code**](https://discordapp.com/api/oauth2/authorize?client_id=614086832245964808&permissions=0&scope=bot)
*(Invite does not give CreditBot any permissions.)*
- prefix : %

CivBot is a discord bot for Civ-servers like [Civclassic](https://reddit.com/r/civclassics/). 


## CivBot Commands
### Meme

#### Image

| Command | Usage |
| ------------- | ------------- |
| `pearl [pearlee] [pearler]` | Returns image of exilepearl with the players names. Can be followed with `pplocate [player]` or `ppfree [player]`|
| `derelict <text1> <text2> <text3> <text4>`  | Places a dereliction sign on the previously posted image |
| `joinedweezer [player1] <player2> <player3> <player4>` | Returns an image of the players minecraft skins in weezer  |
| `laughat` | Returns the image with a black outline and 'LAUGH' appended |
| `cryat` | Returns the image with a black outline and 'CRY' appended |
| `getalong [player1] [player2]` | Places a get along shirt over two players minecraft skins |
| `dontcare [player]` | Appends the player head and a message about how little you care |
| `chart create <chart name>` | Creates a chart to plot minecraft skin heads to. Use `chart view <chart code>` and `chart edit <chart code> <minecraft username> <xcoord> <ycoord>`. |
| `grey` | Makes an image greyscale |
| `step [number]` | Shows you step *n* |
| `grimreminder [player]` | Shows you a grim reminder | 
| `election [player]` | Declares the new mayor | 


#### Text

| Command | Usage |
| ------------- | ------------- |
| `drama` | Returns some randomly generated drama. To edit drama see [here](https://github.com/squareblob/CivBot/blob/master/resources/perchance.txt)|
| `generateplugin` | Returns a randomly generated plugin |
| `respond` | Returns a randomised reponse, such as "shaking and crying" or "oscillating, crying, deleting vault group" |
| `wiard [text]` | wiardifies text by changing vowels and consonants |
| `pickle [name]` | Returns a food based alliterative adjective |
| `animemer` | Returns a screenshot of one of animemer's first ever reddit comments. |
| `nato` | Messages NATO image response |
| `entente` | Messages entente image response |
| `topher` `thraldrek` `oracle` `freestyle` `allen` `pac` | Gives a characteristic response |
| *delusional* | Responds with "Edit Civ Wiki" whenever 'delusional' is sent by a user.|
| *his final message* | Responds with "To live as a septembrian, is to embrace death." whenever 'his final message' is sent by a user.|


### Useful

| Command | Usage |
| ------------- | ------------- |
| `whereis [x] [z]` | Gives nearby markers from CCmap data. *Note : Cardinal directions probably need to be fixed* |
| `whois [player]`| Get info about that IGN from namemc.com and minecraft-statistic.net (Note : may be broken) |
| `invite` | gives CivBot invite |
| *[[CIVWIKI PAGE]]* or *{{CIVWIKI TEMPLATE}}* | returns embed summary of linked civwiki page. Note that pages can be prefixed with `w:` to link to wikipedia. |
| `civdiscord search [searchterm]` | Searches for fuzzy match in [Discord Servers Wiki collection](https://civclassic.miraheze.org/wiki/Discord_Servers) |
| `civdiscord add [discord invite]` | Adds a discord to [Discord Servers Wiki collection](https://civclassic.miraheze.org/wiki/Discord_Servers) |
| `civdiscord nick [invite] [nickname]` | Nicknames a discord, which can be used to aide searches |
| `civdiscord rate [invite] [rating(1-5)]`| Rates a discord server


### Broken

`selectvoicechannels`
* Selects which voice channels to relay member amount of. Requires `manage_channels` permission.

`voicerelay [create|remove]`
* Uses current channel to relay member counts of servers which have used `selectvoicechannels`
* TODO : probably broken

*Upload .schematica file*
* Returns list of material
* TODO : probably broken

---

![pearl](https://cdn.discordapp.com/attachments/614147625809346581/778718066447876133/output.png)
