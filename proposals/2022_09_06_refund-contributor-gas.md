## Proposal

Refund gas incurred by contributors executing Peel-related transactions between block `14561235` and `15481186` (a reasonably recent block).

## Specification

Send the following ETH to the following addresses for the following activities:
- executing Peel `tap` transactions (fund distributions),
- executing multisig transactions.

| address | name | amount (ETH) |
| --- | --- | --- |
| 0x63a2368f4b509438ca90186cb1c15156713d5834 | peri | 0.155098518894669418 |
| 0xc0b8eed3314b625d0c4ebc5432a5bd4f31370b4d |  wraeth | 0.030362801777366501 |
| 0xc33e51fe166c65c1dde7db68d981437aa8fd8e98 | benajmin | 0.005185976260956417 |
| 0xf0fe43a75ff248fd2e75d33fa1ebde71c6d1abad | johnnyd | 0.090232301275219707 | 
| 0x123a3c28eb9e701c173d3a73412489f3554f3005 | jmill | 0.031726311584720568 |
| 0xe16a238d207b9ac8b419c7a866b0de013c73357b | aeolian | 0.19641759936691577 |
| 0x0028c35095d34c9c8a3bc84cb8542cb182fcfa8e | aeolian (alt) | 0.031261950448753779 |

Once executed, we shall update the RECORD table https://github.com/peeldao/gasman/blob/main/RECORD.md

### verifying the data

This data was collated using [gasman](https://github.com/peeldao/gasman) - a script I wrote to calc gas across the juicebox project and the multisig.

Please verify the data for yourself if interested.
