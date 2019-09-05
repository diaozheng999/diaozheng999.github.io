# VAS links

## Successful links (staging)

- [Bundle Pack applink](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b)
- [Bundle Pack weblink](https://mym1.m1.com.sg/app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b)
- [3 Day Dummy applink](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?vasid=11548)
- [3 Day Dummy weblink](https://mym1.m1.com.sg/app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?vasid=11548)
- [Single VAS group (M1 Cyber Guardian GSM) applink](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066)
- [Single VAS (M1 Cyber Guardian GSM) applink](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?vasid=19152)
- [Single VAS group (M1 Cyber Guardian MBB) applink](mym1:///app/account/valueaddedservices/8d7b80f7-cdc8-40ca-a767-fe33fd541692)
- [Single VAS (M1 Cyber Guardian MBB) applink](mym1:///app/account/valueaddedservices/8d7b80f7-cdc8-40ca-a767-fe33fd541692?vasid=19152)
- [Single VAS group (M1 Cyber Guardian HBB) applink](mym1:///app/account/valueaddedservices/176b94ab-e6e3-4a29-91ff-57b30e9a26f3)
- [Single VAS (M1 Cyber Guardian HBB) applink](mym1:///app/account/valueaddedservices/176b94ab-e6e3-4a29-91ff-57b30e9a26f3?vasid=19153)
- [Single VAS group (M1 Cyber Guardian) targeted (81012511)](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?s=81012511)
- [Single VAS (M1 Cyber Guardian) targeted (81012511)](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?vasid=19152&s=81012511)
- [Single VAS group (M1 Cyber Guardian) weblink targeted (81012542)](https://mym1.m1.com.sg/app/account/valueaddedservices/8d7b80f7-cdc8-40ca-a767-fe33fd541692?s=81012542)
- [Single VAS (M1 Cyber Guardian) weblink targeted (81012542)](https://mym1.m1.com.sg/app/account/valueaddedservices/8d7b80f7-cdc8-40ca-a767-fe33fd541692?vasid=19152&s=81012542)
- [Single VAS group (M1 Cyber Guardian) targeted (hbb000159531)](mym1:///app/account/valueaddedservices/176b94ab-e6e3-4a29-91ff-57b30e9a26f3?s=hbb000159531)
- [Single VAS (M1 Cyber Guardian) targeted (hbb000159531)](mym1:///app/account/valueaddedservices/176b94ab-e6e3-4a29-91ff-57b30e9a26f3?s=hbb000159531&vasid=19153)

## Edge cases (staging)

Weird, but should still pass.

- [Weird query strings (Valid) (M1 Cyber Guardian GSM)](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?q=81012511/19152)
- [VASID is not part of VAS Group (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?vasid=1234)
- [VASID is not part of VAS Group (Use VAS Group UUID as VASID) (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?vasid=b04db9df-6c50-447c-b797-596df0c9345b)
- [VASID is not part of Single target VAS Group (M1 Cyber Guardian GSM)](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?vasid=1234)
- [$10 Bundle Pack (subscribed), targeted 86927103](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?s=86927103&vasid=11527)
- [Additional query parameters (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?s=81012511&)
- [Additional query parameters with stuff (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?s=81012511&cat=dog)
- [HBB Cyber Guardian with MBB/GSM vasid](mym1:///app/account/valueaddedservices/176b94ab-e6e3-4a29-91ff-57b30e9a26f3?vasid=19152)
- [multiple VASIDs, should use first one (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?vasid=11548&vasid=11527)
- [multiple targets, should use first one (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?s=81012511&s=81012542)

## Invalid cases (staging)

- [link typo (Bundle Pack)](mym1:///app/account/valueaddedservice/b04db9df-6c50-447c-b797-596df0c9345b/11548)
- [Weird query strings (Invalid) (M1 Cyber Guardian GSM)](mym1:///app/account/valueaddedservices/70f192a4-9728-435b-bb1c-f1f11267f066?s=81012511/19152)
- [Customer (81012542) not allowed (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b?s=81012542)
- [Random stuff at the end of VAS Group (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b/index.do)
- [Non-terminal link (Bundle Pack)](mym1:///app/account/valueaddedservices/b04db9df-6c50-447c-b797-596df0c9345b/do?vasid=11548)
