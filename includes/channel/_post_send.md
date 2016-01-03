## Send channel message

```cURL
curl -X POST "https://api.nightbot.tv/1/channel/send" \
  -H "Authorization: Bearer 4fb1fed8889ec9d1c319d5b3c9a54b23" \
  -d "message=test%20message"

{
    "status": 200
}
```

Makes Nightbot send a message to the channel

**HTTP Request**

`GET https://api.nightbot.tv/1/channel/send`

**Scope**

`channel_send`

**Parameters**

<table>
	<thead>
		<tr>
			<th>Parameter</th>
			<th>Type</th>
			<th>Required</th>
			<th>Description</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>message</td>
			<td>string</td>
			<td>Required</td>
			<td>The message to send to chat. Maximum length: 400 characters</td>
		</tr>
	</tbody>
</table>