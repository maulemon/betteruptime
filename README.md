# Better Uptime
GitHub Actions packaging up subset of API calls [Better Uptime](https://betteruptime.com/)

[API documentation](https://docs.betteruptime.com/api/getting-started)

# Usage

Pause or unpause a Monitor Group

````yaml
- uses: maulemon/betteruptime/monitorgroup@v1
  with:
    token: '' # Bearer token https://docs.betteruptime.com/api/getting-started#obtaining-an-api-token
    monitorGroupId: 12345 # https://docs.betteruptime.com/api/monitor-groups-api#updating-an-existing-monitor-group
    paused: 'true' # or 'false'
````
