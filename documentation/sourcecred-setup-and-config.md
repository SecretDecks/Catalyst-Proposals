# SourceCred Setup & Config

## The best Setup guide

Can be found [here by SourceCred](https://sourcecred.io/docs/beta/setup-guide) directly. If you run into issues you can contact us directly in our [Discord server.](https://discord.gg/CT2GsCkXxy)

## The copy of our Discord config&#x20;

#### The channel ID's can be found within Discord (right click on a given channel and select 'ID') and need to be adapted!

_**default location:** SCinstance/config/plugins/sourcecred/discord/config.json_

```
[
  {
    "channelWeightConfig": {
      "defaultWeight": 1,
      "weights": {
	"849420124007956551": 1.5,
	"884143672004857936": 1.5,
	"845219237336842251": 2,
	"857223252953661442": 2,
	"864585492669399050": 1.5,
	"839844883124584486": 0.5,
	"839844883124584484": 1.5,
	"864211578499891241": 2,
	"864202096613785631": 0.1
      }
    },
    "guildId": "839844883124584478",
    "includeNsfwChannels": false,
    "includePrivate": true,	  
    "propsChannels": [
      "839844883124584483",
      "849420124007956551",
      "884143672004857936",
      "885413168879386624",
      "864585492669399050",
      "845219237336842251",
      "857223252953661442",
      "863517428713783328",
      "839844883124584484",
      "864211578499891241",
      "839844883124584485",
      "839844883124584486"
    ],
    "reactionWeightConfig": {
      "applyAveraging": false,
      "defaultWeight": 1,
      "weights": {
        "1CanD:874726609674965013": 2,
        "2CanDHeart:874726609725308959": 3,
        "3CanDGem:874726609767251968": 4,
        "4CanDprescription:874726611029733458": 5,
        "-1CanD:874726609909870676": -1,
        "poop:895067022021509152": 0,
        "face_vomiting:895067022021509152": 0
      }
    },
    "roleWeightConfig": {
      "defaultWeight": 0,
      "weights": {
        "842003562556424233": 2,
        "849414994541674597": 1
      }
    }
  }
]
```
