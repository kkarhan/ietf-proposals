####	DRAFT PROPOSAL
#	MALICIOUS URL CLASS
###	A public draft to handle malicious URLs.

---

##	Why this proposal?
###	Enshuring User Safety & Formalizing Industry Standards
Already it's been common for decades to deface malicious links using `hxxp` and `hxxps` to prevent them from being parsed by Browsers and other Applications as clickable links.
- This is a good and intentional behaviour as to prevent harm towards users, whilst also enshuring researches who know how to handle said URLs and the contents they lead to properly.

Thus it seems reasonable to formalize this as a standard within the IETF framework (ideally as RFC) as to enshure this to continue.

###	Preventing the useage of said URL types for bona-fide useage.
Having these malicious URLs classified as such will prevent - or at least give pause - to protocol developers that may otherwise think of using them.
- Whether that's due to lack of knowledge or ignorance is not scope of this drafr.

### Encouraging the implementation of proper safeguards.
Having said URLs as malicious will instead encourage them from being not displayed Client-Side as to prevent novice users from reverting the URL and ignoring warnings.
- Instead it would encourage programs to at the very least warn users and block connection attempts unless they acknowledge what they're doing.

---

##	List of malicious URLs to be proposed
This could be implemented with basically any URL type, but for the sake of simplicity in this draft, it's recommended to at least norm them.
- `hxxp://` Already used to mark malicious `http://`urls: ( i.e. `hxxp://malicious.example`)
- `hxxps://` - Analogous to `hxxp://`: (i.e. `hxxps://malicious.example.com`)
- `fxxp://` - Analog of  `ftp://`
- `fxxps://` - Analog of `ftps://`
