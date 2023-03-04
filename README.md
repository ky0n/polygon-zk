# polygon-zk

[tutorial to issue custom schema](https://0xpolygonid.github.io/tutorials/issuer/schema/)

Own notes: The Polygon ID is a way to issue verifiable informations.

Example 1:
* The swissDAO issues a certificate saying "John is great in Solidity development". The swissDAO is the [issuer](https://0xpolygonid.github.io/tutorials/issuer/issuer-overview/).
* A job agency requires applicants to be good in Solidity. This job agency has a real world trust towards swissDAO. It trusts certificates issued by swissDAO. If John applies for a job and showes his certificate, the job agency acts as a [verifier](https://0xpolygonid.github.io/tutorials/verifier/verifier-overview/), it verifies the swissDAO certificate and confirms that John's Solidity knowledge is sufficient for his desired job.

Example 2:
* The swissDAO issues a certificate saying: John is a member of swissDAO.
* The Ethereum Zurich conference registration requires attendees to fill in the organisation name in the registration form. Attendees must prove the affiliation to their organization by showing their membership certificate. The Ethereum Zurich conference website trusts certificates issued by swissDAO. John can prove that he is a swissDAO member.
