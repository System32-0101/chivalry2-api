# PlayFab Login
Returns some information about the account

## Params
```json
{
	"CreateAccount": 
	true,
	"InfoRequestParameters": 
	{
		"GetCharacterInventories": 
		false,
		"GetCharacterList": 
		false,
		"GetPlayerProfile": 
		false,
		"GetPlayerStatistics": 
		false,
		"GetTitleData": 
		false,
		"GetUserAccountInfo": 
		true,
		"GetUserData": 
		true,
		"GetUserInventory": 
		false,
		"GetUserReadOnlyData": 
		false,
		"GetUserVirtualCurrency": 
		false
	},
	"SteamTicket": 
	"ticket",
	"TitleId": 
	"EBF8D"
}
```

## Request
| URL | Method |
| - | - |
| `POST` | https://EBF8D.playfabapi.com/Client/LoginWithSteam?sdk=Chiv2_Version |
