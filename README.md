# deeplinkdadu
Documentation for scheme deeplink dadu apps  

### For deeplink callback Gojek
BASE_URL = shober://gits.app/
link = link
type = gojek  
result = success or failure  
idorder = id order, ex : 97d136e3-978d-4882-a06d-4785cc83a600  

> Example :  
- [Deeplink Gojek Success](dadu://gits.app/link?type=gojek&result=success&idorder=97d136e3-978d-4882-a06d-4785cc83a600)  
dadu://gits.app/link?type=gojek&result=success&idorder=97d136e3-978d-4882-a06d-4785cc83a600  
- [Deeplink Gojek Failure](dadu://gits.app/link?type=gojek&result=failure)  
dadu://gits.app/link?type=gojek&result=failure  

### For deeplink go to promo detail page
BASE_URL = shober://gits.app/  
link = link  
type = promo  
idpromo = idpromo, ex : f35da629-0c7d-4184-87aa-b7c456945e59  

> Example :  
- [Deeplink Promo Detail](dadu://gits.app/link?type=promo&idpromo=f35da629-0c7d-4184-87aa-b7c456945e59)  
dadu://gits.app/link?type=promo&idpromo=f35da629-0c7d-4184-87aa-b7c456945e59  

### For deeplink go to order page
BASE_URL = shober://gits.app/  
link = link  
type = order  

> Example :  
- [Deeplink Order](dadu://gits.app/link?type=order)   
dadu://gits.app/link?type=order   

### For deeplink go to order detail page  
BASE_URL = shober://gits.app/  
link = link  
type = detailorder  
idorder = idorder, ex : 97d136e3-978d-4882-a06d-4785cc83a600 

> Example :  
- [Deeplink Promo Detail](dadu://gits.app/link?type=detailorder&idorder=97d136e3-978d-4882-a06d-4785cc83a600)  
dadu://gits.app/link?type=detailorder&idorder=97d136e3-978d-4882-a06d-4785cc83a600  

### For deeplink go to waiting order page
BASE_URL = shober://gits.app/  
link = link  
type = waitingorder  

> Example :  
- [Deeplink Order](dadu://gits.app/link?type=waitingorder)    
dadu://gits.app/link?type=waitingorder  

### For deeplink go to waiting order detail page  
BASE_URL = shober://gits.app/  
link = link  
type = detailwaitingorder  
url = url link go to midtrans web waiting, ex : https://app.sandbox.midtrans.com/snap/v2/vtweb/6b2d7e3b-8d09-47fc-ad8e-36551f24ed44  

> Example :  
- [Deeplink Promo Detail](dadu://gits.app/link?type=detailwaitingorder&url=https://app.sandbox.midtrans.com/snap/v2/vtweb/6b2d7e3b-8d09-47fc-ad8e-36551f24ed44)   
dadu://gits.app/link?type=detailwaitingorder&url=https://app.sandbox.midtrans.com/snap/v2/vtweb/6b2d7e3b-8d09-47fc-ad8e-36551f24ed44  
