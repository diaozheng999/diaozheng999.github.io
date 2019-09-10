# VAS links

## Successful links (staging)

- [3 Day Dummy applink](mym1:///app/account/valueaddedservices/11548)
- [3 Day Dummy weblink](https://mym1.m1.com.sg/app/account/valueaddedservices/11548)
- [Single VAS (M1 Cyber Guardian GSM) applink](mym1:///app/account/valueaddedservices/19152)
- [Single VAS (M1 Cyber Guardian HBB) applink](mym1:///app/account/valueaddedservices/19153)
- [Single VAS (M1 Cyber Guardian) targeted (81012511)](mym1:///app/account/valueaddedservices/19152?s=81012511)
- [Single VAS (M1 Cyber Guardian) weblink targeted (81012542)](https://mym1.m1.com.sg/app/account/valueaddedservices/19152?s=81012542)
- [Single VAS (M1 Cyber Guardian) targeted (hbb000159531)](mym1:///app/account/valueaddedservices/19153?s=hbb000159531)

## Edge cases (staging)

Weird, but should still pass.

- [Weird query strings (Valid) (M1 Cyber Guardian GSM)](mym1:///app/account/valueaddedservices/?q=81012511/19152)
- [$10 Bundle Pack (subscribed), targeted 86927103](mym1:///app/account/valueaddedservices/11527?s=86927103)
- [Additional query parameters (Bundle Pack)](mym1:///app/account/valueaddedservices/11548?s=81012511&)
- [Additional query parameters with stuff (Bundle Pack)](mym1:///app/account/valueaddedservices/11548?s=81012511&cat=dog)
- [multiple VASIDs (Bundle Pack)](mym1:///app/account/valueaddedservices/11548?vasid=11527)
- [multiple targets, should use first one (Bundle Pack)](mym1:///app/account/valueaddedservices/11548?s=81012511&s=81012542)

## Invalid cases (staging)

- [link typo (Bundle Pack)](mym1:///app/account/valueaddedservice/b04db9df-6c50-447c-b797-596df0c9345b/11548)
- [Weird query strings (Invalid) (M1 Cyber Guardian GSM)](mym1:///app/account/valueaddedservices?s=81012511/19152)
- [Customer (81012542) not allowed (Bundle Pack)](mym1:///app/account/valueaddedservices/11548?s=81012542)
- [Random stuff at the end of VAS Group (Bundle Pack)](mym1:///app/account/valueaddedservices/11548/index.do)
- [Non-terminal link (Bundle Pack)](mym1:///app/account/valueaddedservices/11548/?s=81012511)
