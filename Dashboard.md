# DASHBOARD API

## GET TEAM STATISTIC

The API is to help Hogo Admin manage the number of different type of teams in Hogo system.

### URL
- POST
```` URL
  (POST)https://www.689cloud.com/api/admin/teamstatistic
````

### Header

  --------------------------------------------------------------------------------------------------
  *application/x-www-form-urlencoded;charset=UTF-8*
  --------------------------------------------------------------------------------------------------

### Request parameters

  ---------------------------------------------------------------------------- --------------------------------------------------------------------------------- -----------------------
| Name | Data Format | Description |
|:---|:---|:---|
| auth_token | String | (Required) require the Hogo Admin auth_token |

#### Response example
```json

```

## NEW ACCOUNT REGISTERED STATISTIC

The API is to support Hogo Admin to check the new team registration in specify time.

### URL
- POST
```` URL
  (POST)https://www.689cloud.com/api/admin/newaccountstatistic
````

### Header

  --------------------------------------------------------------------------------------------------
  *application/x-www-form-urlencoded;charset=UTF-8*
  --------------------------------------------------------------------------------------------------

### Request parameters

  ---------------------------------------------------------------------------- --------------------------------------------------------------------------------- -----------------------
| Name | Data Format | Description |
|:---|:---|:---|
| auth_token | String | (Required) require the Hogo Admin auth_token |
| duration_id | int | (Required) time id (0:last week, 1:last 2 weeks, 2: last month, 3: last 3 months, 4: last 6 months, 5: last year) |

#### Response example
```json

```

## GET STORAGE STATISTIC

The API is to help Hogo Admin to check the capacity of files in system. The API will return the total storage of HoGo system, and storage of each Team in HoGo.

### URL
- POST
```` URL
  (POST)https://www.689cloud.com/api/admin/storagestatistic
````

### Header

  --------------------------------------------------------------------------------------------------
  *application/x-www-form-urlencoded;charset=UTF-8*
  --------------------------------------------------------------------------------------------------

### Request parameters

  ---------------------------------------------------------------------------- --------------------------------------------------------------------------------- -----------------------
| Name | Data Format | Description |
|:---|:---|:---|
| auth_token | String | (Required) require the Hogo Admin auth_token |

#### Response example
```json

```

## TEAM INFO STATISTIC

The API is to help Team Admin to view overall statistic of his/her team.

### URL
- POST
```` URL
  (POST)https://www.689cloud.com/api/team/infostatistic
````

### Header

  --------------------------------------------------------------------------------------------------
  *application/x-www-form-urlencoded;charset=UTF-8*
  --------------------------------------------------------------------------------------------------

### Request parameters

  ---------------------------------------------------------------------------- --------------------------------------------------------------------------------- -----------------------
| Name | Data Format | Description |
|:---|:---|:---|
| auth_token | String | (Required) require Team Admin auth_token |

#### Response example
```json

```