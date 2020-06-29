![logo](https://raw.githubusercontent.com/victorratts13/bet365-api-endpoints/master/assets/img/endpoint-logo.jpg)
![label](https://img.shields.io/badge/Mark-Down-orange) ![test](https://img.shields.io/badge/test-pass-brightgreen) ![version](https://img.shields.io/badge/Version-20.6-yellowgreen)

## API endpoint For devs on Bet365
>- Warning: Bet365 does not authorize the use of bots on your personal account or that of your customers. Any misuse will be penalized and the unrestricted use of these EndPoints is the sole responsibility of the developer or user. This documentation is intended for academic purposes only.
### Indice

### Links
> SportsBook: https://www.bet365.com/SportsBook.API/

> OfferApi: https://www.bet365.com/offersapi/offers/v2/

> StreamEvents: https://extra.bet365.com/StreamingEvents/

> DefautApi: https://www.bet365.com/defaultapi/

> GetQuicklinkFixtures: https://extra.bet365.com/ResultsApi/GetQuicklinkFixtures (```Auth```)


### Descriptions

endPoint name | description | use method 
--------------|-------------|------------
SportsBook | Endpoint for obtaining game data (this endpoint retrieves live and future game data) | GET
OfferApi | this request returns an access token | GET
StreamEvents | This endpoint returns the Stream Data of future events | GET
GetQuicklinkFixtures | This endpoint returns data from Matches | GET

### Requests SportBook

- Definition

protocol | link | endPoint | query 
---------|------|----------|-------
https:// | mobile.bet365.com | SportsBook.API | Mobile?lid=33&zid=0&pd=%23AS%23B1%23&cid=28&ctid=28

- query Description
> Mobile: <span style="color: #11665c;"> Device Identification </span>
> lid: <span style="color: #11665c;"> Language Id </span>
> zid: <span style="color: #11665c;"> uknow </span>
> pd: <span style="color: #11665c;"> post Date </span>
> cid: <span style="color: #11665c;"> Country Region ID </span>
> ctid: <span style="color: #11665c;"> uknow </span>

- example

~~~javascript
get('https://mobile.bet365.com/SportsBook.API/Mobile?lid=33&zid=0&pd=%23AS%23B1%23&cid=28&ctid=28').then((rest) => {
    console.log(rest)
})
~~~




