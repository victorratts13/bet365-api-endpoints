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

> VSports: https://vsports.bet365.com/

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

## Bet labels Reference

- ApplyTolerence: "at"
- AusBetTypes: "ab"
- AusCombination: "ac"
- AusDropdownAvailable: "dd"
- AusRacingBetType: "rt"
- AusToteOfferId: "ao"
- AutoVoid: "av"
- AutoVoidAvailable: "va"
- BankerSelected: "bk"
- BaseballPitcher: "bp"
- BetBuilderIndicator: "bb"
- BetCreditStake: "bc"
- BetReference: "br"
- BetTypeId: "bt"
- CastBetCount: "cc"
- CastMask: "cm"
- CastType: "ct"
- Classification: "cl"
- DisplayOdds: "do"
- EWEX: "ee"
- EachWay: "ew"
- EachWayAvailable: "ea"
- EachWayPlaceDivider: "ed"
- EachWayTerms: "et"
- EnhancedPrices: "ep"
- EwexAvailable: "ex"
- ExcludeFromReceipt: "er"
- Excluded: "xc"
- FixtureDescription: "fd"
- FixtureID: "fi"
- ForceEachWay: "fe"
- FreeBetAmount: "fb"
- FreeBetQualifiedAmount: "fa"
- FreeBetQualifiedStatus: "fq"
- FreeBetToken: "ft"
- FreeBetTokenSelected: "fs"
- IfBetAction: "ac"
- IfBetDescription: "id"
- IsBetCall: "ib"
- ItalianBetType: "it"
- ItalyADMReference: "ar"
- ItalyComplementarePlaceOdds: "eo"
- ItalyComplementarePlaceParticipant: "ic"
- MarketDescription: "md"
- MatchId: "mi"
- MaximumStake: "ms"
- MediaType: "mt"
- MinimumStake: "mn"
- MultiMin: "mm"
- MultiplesRestricted: "mr"
- NoReserves: "nr"
- NoReservesAvailable: "na"
- Odds: "od"
- OddsChanged: "oc"
- OddsHash: "sa"
- OddsTypeOverride: "oo"
- OfferBadges: "ob"
- OfferSPOdds: "os"
- PartType: "pf"
- Participants: "pt"
- PennyWagering: "pw"
- PitcherDescription: "pd"
- PlaceBetResult: "pr"
- PlayerId: "pi"
- Protocol: "pr"
- PushStatus: "ps"
- QuickCode: "qc"
- RecalculatedStake: "rs"
- ReferralAmount: "ra"
- ReferralAmountApproved: "aa"
- ReferralAmountRejected: "rr"
- ReferralPlaceAmount: "rp"
- SPOddsSelected: "ss"
- SelectedPitcher: "sp"
- SlipResult: "sr"
- SplitIndex: "ix"
- SportType: "sk"
- Stake: "st"
- StakeMultiple: "sm"
- Suspended: "su"
- TempReceiptReference: "tr"
- TempReceiptStatus: "te"
- ToReturn: "re"
- TopicId: "tp"
- TotalStake: "ts"
- ToteLegId: "li"
- ToteMeetingId: "ti"
- ToteMeetingNumber: "tn"
- ValidStakes: "vs"

## Bet Document Attribut Reference

- AccountNumber: "ac"
- AccumulatorType: "at"
- BetBuilderObjects: "bb"
- BetGuid: "bg"
- BetObjects: "bt"
- BetReference: "br"
- BetslipTypes: "bs"
- CastObjects: "ci"
- CurrentState: "cs"
- DefaultMultiple: "dm"
- EnhancedPrices: "ep"
- EquallyDivided: "cp"
- ExchangeRate: "er"
- ExchangeRateUS: "eu"
- InPlayItemExists: "ir"
- LiveAlerts: "la"
- LiveStreaming: "ls"
- MessageId: "mi"
- MessageValues: "mv"
- MultipleOptions: "mo"
- MultiplesRestricted: "mr"
- OfferBadges: "ob"
- PlaceBetDisabled: "pd"
- QuickCode: "qc"
- QuickDepositAllowed: "qd"
- ReferralAmount: "ra"
- ReferralPlaceAmount: "rp"
- ReferrralCode: "rc"
- ReferrralReference: "rr"
- ReferrralTime: "rt"
- SessionExpired: "se"
- ShortfallAmount: "sf"
- SlipResult: "sr"
- SlipType: "st"
- TeaserID: "ti"
- TeaserOptions: "to"
- TempReceiptReference: "tr"
- TokenExpired: "tx"
- TotalBetCreditStake: "tc"
- TotalFreeBetTokenStake: "tf"
- TotalStake: "ts"
- TotalToReturn: "re"
- TotalUserStake: "tu"
