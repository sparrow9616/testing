# Project file store
#### 91 leannerOctober 09, 2024

> File store repository or auto approval channel repository ka combination hoga. Jis ke under paytm merchent payment getaway, url shurtner, my website for link redirect ,meybee  integrate hoga 
>
>
> Sub features ko handle karne ke liye ek primary bot hoga sudo user SUB KUCH  es se hi Karega and welcome msg leave msg verify jaise msg bhi es bot se jyega 



## Types of plan 

- Plan 1 24hrs ACCESKEY 

- Plan 2 30days accesskey 

- Plan 3 30days  download 


Note inki  ache se information es Mai nhi hai

- text , button, photo, forwardmsg , sticker,, voice msg 

-  photo replacer 

- pic1 pic2  thumails2

- 92% complete bata raha hai  baki jan meeting pe bethoge  baki cheeze clear kar duga 

- choti choti cheeze jo progress ke sath hi bata sakta hu  like kaha delay chahiye kaha nhi etc etc 





## A. ✅internal requirements

-  Code clear likhna hona chahiye 

-  tg api hash 2 use karna hai  

-  same vps pe bot host ho jye and site bhi Dono ko host karne liye .sh create kar dena donk ke liye alag 

-  hosting error clear samj aajye 

-   same function 1se jada button peho ho toh var bana dena edit karne mai essy ho 

-   auto delete restricted content etc etc jaise feature true false karne ka options 

-   text, pic, voice, forwardmsg, in subko edit karne ke liye tample.py bana dena aus ke under clearly sub ho edit karne mai essy ho 

-   configuration ko edit karne ke liye config.py kar dena jis ke under auto delete time , api, hash , etc etc jesi cheeze edit karne ke liye ho 

-   error delay floods tes tarh se jo internal problem hoti hai yeh sub aap ache se handle karoge problem na aaye aage 

- jis tarh se maira yeh project hai aus mai ager multiple bot side kuch hota hai toh links mai problem nhi aayegi  chache new bot add Karu remove Karu na dump mai 

-  mongodb type jo database hote hai wo es tarh se ho ki kabhi bhi aus se side problem na aaye 

-  batane ki jarurat nhi but file sharing system wo har type ke format ko support karega link generate karne ke liye 


## ✅ B. AUTO APPROVAL CHANNEL FEATURES 

- only fsub channel1 Join req auto approve 

- welcome msg User DM if user joined fsub1 only 

- leave msg userDM if user joined fsub1 only 

- Verify when user send join req  before approving user have to click Verify button ( detels puch lena )

- panding join req also approves 

-  ban/unabn if user ko ban kardu toh user joinreq reject kar de or ager user joined hai toh aus ko Kick kar de or parinay bot ko chhor ke sub bot aus user ko response Dena band kar denge 


## ~~C. Miniapp  Requirement~~ 

-  ~~SINGLE PAGE ka miniapp hoga premium about ke liye popup aayega jis ke under text  dalna hai icon ya sticker ke sath  ek button hoga~~ 

- ~~ui ux kafi sahi ho~~

- ~~delay set karne ka option essy ho . redirect ke wakt~~

- ~~self promotion ke liye ek acha sa space ho~~

- ~~social media icons 2 tg and wp both page~~

- ~~if delay hai toh countdown~~

- ~~countdown 0 hint hote hi vibration~~

- ~~skip name se Button~~

   #### ~~**How ?**~~

    - ~~User side se Link pe click krte hi primary bot ka mini app open hoga open hone ke bad mini app se mere kisi bot pe redirect ho jyega random~~ 

    - ~~Note ~ same hosting wala vps ka ip use hoga if aisa hota hai toh jo mere pass vps hote hai wo life time stable nhi hote har month' new vps pe hosting hoti hai toh aus hesab se karna esko ki ager Ip change bhi ho toh problem na aaye~~ 


## D. ⌛Payment Getaway 


### ⌛1.1 Payment getaway T&C

- user side koi bhi information na manage 

- user ko sirf payment karni padhe backend mai khud se identify kare payment aayi ya nhi

- payment getaway without gst wala ho 

-  0 Cost Payment getaway chahiye if not posible than par tra mai kuch % de sakta hu 

- waie toh mere pass  getway hai  wanra aapko payment getaway dundne mai aap help karoge 

- muje domain buy nhi karna 



### ⌛ 1.2 Payment getaway UI 

-  BUTTON PE CLICK kar ke mini app open hoga or aus mai payment modes show honge 

- qr ka background UI  bhi awasome ho 

-  if posible qr ke niche button ho aus pe click karte hi user ke device pe jo bhi payment mode available ho aus pe redirect ho jye 



### E. BREIF ABOUT  FEATURES 

#### ✅ ACESSKEY

- IF enable hai toh ab se file store bot ka use karne k liye key kind of req hongi same jaise url shurtner hota hai na 24h ke liye waisa hi kuch hoga jis ke under url shurtner ke sath payment getaway se pay kar sakte ho 

- `Example `
- User ne link pe click liya  ---- bot pe aaya bot ne Check kiya fusb if not pass toh FSUB msg show kar diya jaise hi FSUB oe joined huwa aus msg ko delete karke new msg send karega for accesskey generate ka niche main 2 buttons honge  

    - B1 url shurtner ka  jaise user ads dekh leta hai site aus user ko aushi bot pe redirect kardega jis bot ke buton se url shurtner pe gya tha  or bot aus ko msg send kar dega key generated for start click activate button aus pe click karte hi 24hs tak mere sub bot ka use kar sakta hai 

    - B2 payment getaway ka same aise hoga bus es Mai payment karni hogi 

    - Accesskey enable hai toh 5 links without getting access key bot send kar dega  but FSUB required 
---



#### ✅ AUTO DELETE 

- Jo bot User ke dm mai file send kar raha hai aus file ko set kiye hue time pe  delete kar de

- ~Time ki koi limits na ho normal 5h use hoha 

- ~ file send krne ke bad text hoga text = file will be deleted in ** jaise hi file delete ho jye toh es text ko edit kar ke text = file deleted {samecount} or es ke niche 

- ~watch again ka button ho aus pe click karte hi same file jo aus mai delete hue thi wo wapis aajye 

---

#### ✅ DOWNLOAD 

- user dm mai jab wo file send karta hai tab sub files ke niche ek button hoga download name se

- Aus pe click  karte hi voice msg hoga aus ke niche button hoga payment getaway wala jaise hi user payment kar deta hai toh wo user 30dsys tak mere sabhi bot se  sirf aus user ke liye restricted mode disable ho jayega 

---

#### ~~REDIRECT SYSTEM~~ 

- ~~IF  enable hai toh jo bhi link generate hoga wo meri site ka hoga~~
- 
-  ~~user aus link pe click karta hai toh pahle meri site open hogi site se mere hi multiple bot mai se kisi ek bot pe wo user redirect ho jyega or wo bot aus user ko wo file provide kar dega~~ 

- ~~NOTE (IF) mere multiple bot mai se koi bot baned ho toh website link ko fark na padhe~~ 

---

#### ~~PHOTO REPLACER~~ 

- ~~Eska puch lena text Mai muskil ho jyega~~ 

---

####  🔎 VERIFY 

- IF enabled hai toh jab user req send kaega toh user ke dm mai msg jayega verify button ke sath jab tak user aus button pe click nhi karega req approve nhi hogi jaise hi user click karta hai same bot pe aus user ke side se /start msg send hoga or req approve ho jyegi 

---

#### ✅ DATABASE/DUMP

- 4 DB CHANNEL honge  

- Example 

- File send ki sudo ne wo file sub db mai forward hoga or link gen kar ke dega kal ko ager wo file db1 pe nhi milti toh wo db2 se dund ke dedega  same DB2 se nhi mila toh db3 db3 se nhi mila toh 4 se

---

#### ~~DELAY~~ 

~~Ye wo miniapp  redirect system ke liye hai~~

~~Es pe 5sec ka delay hai toh jab user link pe click kar ke site pe jayega  toh aus ko 5sec wait karna hoga phir wo redirect ho jyega bot pe~~ 

---

#### ✅ COUNT 

- Bot ne kitne link gen kiye aus ka count rakhega or wo count link gen text pe bhi show karega 

- Same count db pe bhi store hoga or auto delete wale text pe bhi

---

#### 🔎 DURETONS

- Jis file ka wo link gen kar raha hai aus ka duration hai toh kitna duration hai wo link gen text Mai bhi show kare 

-  0 to 60S  exact batayega. 1M-60M roundfiger 
- 60H se jada ki hai toh 1H 1h+
- ~For example kisi file ka duration 1m 10S hai toh 1M
- Batch link ke under  duration ka total count karega 
- ~For example 10 10Sec ki 5 files thi toh 50S aayega 
- ~Batch file ke under mix hai pic video dono hai toh 
- duration sath **
---


#### 🔎 THUMBNAIL/ PIC1/PIC2

- Es ke liye baat kar Lena better rahega 
---
#### ✅ FSUB

- Jis channel pe wo joined nhi sirf aus ka button show karega 

- Fsub1 pe joined hona jauri hai other FSUB pe ager user req bhi send karta hai toh user ka FSUB pass ho jayega 

---

#### USELESS 

- Jab user aisa  msg send kare jo cmand mai nhi like hello hi toh bot user ko msg send karega 

- Work example 

- 10S ke under 10 times useless msg send kar deta hai kisi bot ko jis user ko send Kiya aus ko msg jayega aus ke bad 10min tak bot aus user ke useless msg pe response nhi dega 

- Same cheez 3 times hogi 4th time voice msg send karega or wo count reset ho jyega same 3 time msg or 4rh mai msg 

#### USELESS IMPORTANT BUTTON 

- AUS BUTTON OE CLICK KAETE HI text aayega aus text ke bad user jo bhi bejta hai jaise bhi bejta hai maan lo hello bej diya bot msg bejega text ke sath 2 button send or cancel 

- Jase hi send pe click karega toh mere ek channel pe aus ka aise ka kase jo aus ne msg beja wo forward ho jayega aus user. Ke mention ke sath mentons text ke niche 2 button honge upload reject 

    - UPLOAD 

        - ES pe click karte hi wo msg ya post aise ki aise ek dusre channel pe upload ho jyegi without mentions without forward tag 
    - REJECT 

        - REJECT karte hi sudo user ko bot msg send karega button ke sath aus button pe sudo user ne 5min under click Kiya toh aus hi user ko aapni baat likh ke bej sakta ager click nhi karta toh kuch nhi hoga 

---

### ✅F. FEATURES

- No limits in link gen time 

- link generate mai koi limitation na ho for example ager maine bot dm mai 100 files di 20 link gen ke bad kosis  flood or kisis resons se stop huwa toh jaise. Hi wo problem hat jayegi toh baki ke 80 file ka link gen karne lagega 



#### ~~Hosting problem~~ 

- ~~if kisi reson se hosting stop ho jati hai aus bich jo work under processing mai hoga wapis hosting.mikte hi ager aus mai time hoga toh aus ko karne lag jayega~~ 



#### ✅Batch channel

- ek channel hoga jis ke under kuch bhi dalu aus ke niche button aajyega ek batch or Thumbnail name se   imshot multiple batch link generate kar wane ke liye essy method

    - Example 

    - Msgid1 se msgid20 tak maine aus channel pe photos send kar di msgid20 means 20pic upload hue 
    - Sub msgid ke niche khud ka batch or Thumbnail name se button hai 
    - Ab yeh 20 pic ka muje batch chahiye with thumbnails 
    - Toh jis ka msgid1 hai aus pe jo thumbnail hai aus pe click kar diya bot samj gya jo link gen hoga aus pic ke caption mai link dal ke dena hai 
    - Phir maine msgid2  pe jo batch button hai aus pe click kar diya phir sidha maine msgid20 batch Button pe click kar diya 
    - Ab huwa kya 19pic ka batch link generate huwa  jo link generate hoke aaya wo aus ke caption mai aaya 

#### ✅ LIKE DISLIKE

- mere fsub1 Channel pe jo bhi post ho bot asu channel ki post pe ek like or ek dislike de reaction ke under 



#### Userless important button 

- es ke liye baat kar Lena 

---

### G. CMAMNDS

1. ✅`/user`: Sab running bots ke users  show karega 

    How ? 
       
    Botname aus ke sath aus ke kitne user {users}

2.  ✅ `/batch` es ki help se multiple file ka single link gen kar sakta hu 

    HOW ?
    >
    >`/Batch` karte hi bot text send karega aus text ke bad muje jitn files ka single link chahiye mai wo send kar duga  for example maine 5 files send karni thi maine kar di aus ke bad link gen ke liye muje /makeit karna hoga /makeit karte hi bot un 5 file ka single link gen kar ke send kar dega 
    
3. ✅ `/Info` es se vps ke related information share karega ram, core , version, speed , etc etc 

4. 🔎 `/Promo` (how it's work )

   - `/Promo` karte hi bot ek text send karega with button  aus text ke bad for example maine 5 pics send kar di pic send kar e ke bad maine aus button pe click kar diya bot ne ek text send Kiya aus text ke bad maine 5 videos send karni thi wo kar di phir maine /makeit kar diya  makeit ke bad bot link gen kar dega 



   - **User side interface** 

     - Jab user aus link pe click karega toh es case mai 5pics thi bot fusb + acesskey dono ko bypass kar ke wo 5pcis forward kar dega or file ke niche button hoga watch more name se 

     - Jab user aus wtach more pe click karega tab bot check karega user FSUB pass karta hai ya nhi ager  acesskey required hai toh wo aus ke pass hai ya nhi ager sub pass karta hai toh wo baki ki 5 video bhi forward kar dega 


5. ✅ `/bcast` ye brotcast ke liye hoga how ?

    - pbot pe jaise hi /bcast karne ke bad bot msg ssend karega  basically wo puchega ki konse bot se bcast karna hai jaise hi mai bot choose kar leta hu toh wo text edit ho jyega or text Mai aus bot ke users or niche 3 buttons aajyege 

    - b1 name orignal bcast 

      - Aus bot ke jitne users honge un subko mera msg forward ho jyega 

    - b2 name fake bcast

      - Mera ye msg kisi bhi users ko forward nhi hoga 

      - basically ye fake successful brotcast ka chart create karne ke liye hai for example es bot ke 10hazar user the toh 90% successful mai dikha diya or 5% unsuccessful etc etc etc 

   - b3 specific brotcast 

     - For example es bot ke 10hazar users the maine 1000 type kar ke send kar diya toh 10k mai se rendom 1k users ko wo msg forward kar dega

    - Ab es case mai maine bt click Kiya tha jaise hi mai choose kar leta hu toh msg edit ho jyega 

    - Edit ho jane ke bad muje jo msg bcast kar wama hai wo forward kar duga  msg send karte hi bot new msg send karega text= ager bcast cancel karna hai toh sttop button pe click karo ager mai 5sec ke under aus button pe click kar deta hu toh wo bcast nhi hoga warna ho jyega 

    > NOTE ager msg forwarded hai toh forward hi hoga ager msg ke pass forward tag nhi hai toh wo without forward tag ke sath jayega 



6. ✅ `/Msg` ye specific bot se specific user ko msg send karne ke liye hoga( how )



   - `/msg {userid}` jaise hi mai ye dal duga toh bot choose karne ke liye bolege jaise hi mai bot choose kar leta hu toh  msg send karne ke liye bole same cannel system hoga if click nhi karta toh jis ki userid hai wo msg aus user ko send ho jyega 



7. ✅ `/List` es se history batayega ki kitne logo ne url shurtner key acess liya kiyne logo ne payment getaway se liya or kitne logo ke pass download permission hai  with date  es ke niche button hoga reset ka aus pe click karte hi ye history reset ho jayegi 

8. 🔎 `/Reset` karte hi 2 buttons aajyege 

    - B1 count reset ~ es se jo counting chal rahi hai wo reset ho jyegi 



    - B2 total reset ~  sun settings information reset ho jayegi sirf users ko chhor ke 



9. ✅ `/free` user ko menual permission Dene ke liye hoga ( how ?)


   - `/free {userid}` ager user ke pass already koi plan hoga toh aus ka information text pe show kar dega warna text dura hoga /free userid karte hi 3-4buttoms honge 



     - b1 24h activate | enable/disable 

       - ES SE ACCESKEY menual allow karne ke liye hoga 

     - b2 download | enable/disable 

        - Es se menual download option allow karne ke liye hoga 

     - b3 BAN / UNBAN 

        - Es ke bare mai auto approval information mai bataya huwa hai 



10. ✅ `/Gen` basically `/batch` jesa hoga but Thora laga hoga es se multiple files ka link gen karene mai help karega (how ?) 



    - `/gen` mere sirf db1 Channel se commented hoga 

    - `/gen` karte hi bot text send karega aus mai likha hoga ki jaha se muje start karna hai waha ka link share karo mai db1 mai jake copylink kar duga or send kar duga 

    - aus ke bad text send kar ke bole ki kaha tak ke link gen karne hai mai db1 mai jake copy link dedeta hu 



    -  ab bot ko identify hogya ki kaha se leke kaha tak ke link generate karne hai  es ke bad bot ek text send kare text = kya ye files baki ke bd Channels mai forward karna hai button 1 yes button 2 no 



       -  if yes  ager yes kar deta toh same file ko baki ke db Channel mai forward kar ke link gen kar ke deta ager kal ko wo file db1 mai nhi milti woh wo file aus ko db2 mai mil jati same link se 



        - if no hota toh wo sirf db1 ki assisting msgid ki jelo se link gen kar ke dedeta ager db1 ban huwa toh wo link kam nhi karta 


    > NOTE db1 mai repost nhi karega

#### Settings 

11. `/Settings` panel kind off hoga jitne bhi feature ko mamange yahi se kar pauga mai 


    > NOTE single line mai 2 buttons honge jo text left side hai wo left side buttons pe hoga jo right pe hai wo leff side pe  eska puch lena kis type ka format chahiye 



    - A. **auto approval enable/disable** 

      -  ager  disable kar deta hu toh auto approval ka system off ho jyega 

      -  if auto approval pe click karta hu toh text edit ho jyega or 5buttons show karega 

          -  ✅ welcome msg enable/disable  
          -  ✅leave msg enable/disable    
          -   pending req enable/disable  
          -   verify assisting
          -   back 



    - ✅ B. **Acesskey enable/disable**

        - If  disable hai toh bot ko use karne ke liye acesskey ki requirment nhi hogi sirf FSUB chahiye hoga 

        - if Acesskey pe click karta hu toh text edit ho jyega or 3 button show karega 

            - payment getaway enable/disable 

            - url shurtner enable/disable 

            - back 
        > NOTE dono mai se koi disable hai toh jab bot Acesskey generate msg send karega aus pe aus ka buttons show nhi karega 



    - ✅ **C. Logs Channel logs1/logs2/useboth/disable** 

        - ager ye disable nhi hai kisi pe set hai toh jis pe send hai bot jis tarah se link gen karega aus link ko forward kar dega aus channel pe jis pe wo set hai 

        - Ager wo log1 Channel pe hai toh jitne links gen honge wo log channel pe  forwarding karega 

        - Useboth hai toh dono mai forward karega 



    - D. Want image pic1/pic2/thumbnail/disable 

        - Pic1 pic2 ka puch lena ot Thumbnail ka bata rakha hai 



    - E. Caption enable/disable 

        - If ye enable hai toh Jis file ka link gen kar ra hai ager aus ke niche koi caption hai toh aus Caption ko copy kar ke link gen text pe paste kar ke send karega 

        -  Waise by default caption rahega  sub pe
        > Note database pe jo bhi store hoga wo without caption store hoga 



    - ~~F. Link Type site/bot~~

        - ~~If site  bot jo bhi link gen karega wo site ka katega site se kisi bot pe redirect hoga user~~ 

        - ~~if bot es case mai jitne bot add honge direct bot username se link gen honge rendom~~ 



    - ✅ G. `/Gen` type 10/1

        - Ye `/gen` ke liye hai ager ye10 hai toh 10 file ka single link gen kar ke dega  ager 1 pe hai toh subka single link.



    - ~~H. Photo replacer~~ 

        - ~~Es ke liye baat kar Lena~~



    - ✅ I. Add es se multiple bots , multiple FSUB , tg account add karne ke liye hoga how ?

        -  add pe click karte hi text edit ho jyega or 4 button aajyege 
        -  b1 add bot 

            - Es Mai multiple bots add remove kar sakta ho jo file provide karnege 
        - b2 add FSUB 
            - Es se multiple FSUB bot add kar sakta hu 

            - Kis type se hoga like {buttonname} , {Channelid}
---
### ⌛ add tg account 

>Mai chahta hu ki mai bor se aapna account login Karu or aus se hi Channel or bot create kar pau 
>
>Ager channel banau toh puche private or public username kya rakha hai 
>
>Or ek user ko full tights ke sath admin de Sudo user ko de toh better 
>
>Bot username pic bio name yeh sub set kar pau 
>
>Or I'd logout karne ka option jitna ho sake utna safe rahe  ban na ho. Account fresh bhi login kar wana hai toh sirf code beje toh sms ya telegram pe call wala skip kar sms bej de 
