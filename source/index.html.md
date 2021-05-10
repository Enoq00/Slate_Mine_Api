--- 

title: LiveCasino.Report 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

**Version:** v1 

# /API/BLACKJACKGAMEREPORTS
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackGameReports` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| GameId | query |  | No |  |
| GameStartTime | query |  | No |  |
| GameEndTime | query |  | No |  |
| PartnerId | query |  | No |  |
| DealerName | query |  | No |  |
| DealerIdForNickname | query |  | No |  |
| CurrencyCode | query |  | No |  |
| TableId | query |  | No |  |
| RoundStatus | query |  | No |  |
| IsSortAsc | query |  | No |  |
| From | query |  | No |  |
| Count | query |  | No |  |
| Search | query |  | No |  |
| ColName | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKGAMEREPORTS/{ROUNDID}
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackGameReports/{roundId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| roundId | path |  | Yes |  |
| partnerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKPLAYERDETAIL/{ROUNDID}
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackPlayerDetail/{roundId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| roundId | path |  | Yes |  |
| partnerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKPLAYERDETAIL/ACTIVEROUNDHISTORY/{TABLEID}
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackPlayerDetail/ActiveRoundHistory/{tableId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| tableId | path |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKPLAYERREPORTS/{ROUNDID}
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackPlayerReports/{roundId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| roundId | path |  | Yes |  |
| partnerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKPLAYERREPORTS/ACTIVEPLAYERS
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackPlayerReports/ActivePlayers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| tableId | query |  | No |  |
| boxId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKPLAYERREPORTS/TOTALBETS
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackPlayerReports/TotalBets` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| tableIds | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/BLACKJACKREPORTFORPLAYERPROFILE
## ***GET*** 

### HTTP Request 
`***GET*** /api/BlackjackReportForPlayerProfile` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| playerId | query |  | No |  |
| roundId | query |  | No |  |
| date | query |  | No |  |
| partnerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/GAMEISSUES/FORDAY
## ***GET*** 

### HTTP Request 
`***GET*** /api/GameIssues/forday` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| unixSeconds | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/GAMEROUNDS/ID
## ***GET*** 

### HTTP Request 
`***GET*** /api/GameRounds/id` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/GETGAMESHISTORY
## ***GET*** 

### HTTP Request 
`***GET*** /api/PlayerReports/getGamesHistory` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| playerId | query |  | No |  |
| from | query |  | No |  |
| count | query |  | No |  |
| offset | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/GETROUNDDATA
## ***GET*** 

### HTTP Request 
`***GET*** /api/PlayerReports/getRoundData` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| playerId | query |  | No |  |
| roundId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/GETPLAYERS
## ***POST*** 

### HTTP Request 
`***POST*** /api/PlayerReports/getPlayers` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/COUNTS
## ***GET*** 

### HTTP Request 
`***GET*** /api/PlayerReports/counts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| ReportStartDate | query |  | No |  |
| ReportEndDate | query |  | No |  |
| PartnerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/PROFILE
## ***POST*** 

### HTTP Request 
`***POST*** /api/PlayerReports/profile` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/PROFILE/SUMMARY
## ***GET*** 

### HTTP Request 
`***GET*** /api/PlayerReports/profile/summary` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| ReportStartDate | query |  | No |  |
| ReportEndDate | query |  | No |  |
| PlayerId | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/PROFILE/SINGLEDAY
## ***GET*** 

### HTTP Request 
`***GET*** /api/PlayerReports/profile/singleday` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| playerId | query |  | No |  |
| date | query |  | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /API/PLAYERREPORTS/LOGIN
## ***POST*** 

### HTTP Request 
`***POST*** /api/PlayerReports/login` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
