# Monitorizarea la distanţă

```{image} ../images/KidsMonitoring.png
:alt: Monitorizarea copiilor
```

AndroidAPS oferă mai multe opțiuni pentru monitorizarea la distanță a copiilor și, de asemenea, permite trimiterea de comenzi la distanță. Desigur, se poate folosi monitorizarea de la distanta pentru supravegherea partenerului sau prietenului.

## Functii

- Kid's pump is controlled by kid's phone using AndroidAPS.
- Parents can remotely follow seeing all relevant data such as glucose levels, carbs on board, insulin on board etc. using **NSClient app** on their phone. Setările trebuie să fie aceleași pentru AndroidAPS și NSClient.
- Parents can be alarmed by using **xDrip+ app in follower mode** on their phone.
- Remote control of AndroidAPS using [SMS Commands](../Children/SMS-Commands.md) secured by two-factor authentication.
- Remote control through NSClient app is only recommended if your synchronization is working well (ie. you don’t see unwanted data changes like self modification of TT, TBR etc) see [release notes for Version 2.8.1.1](../Installing-AndroidAPS/Releasenotes.md#important-hints) for further details.

## Instrumente și aplicații pentru monitorizare la distanță

- [Nightscout](https://nightscout.github.io/) in web browser (mainly data display)
- NSClient app is a stripped down version of AAPS capable of following somebody, making profile switches, setting TTs and entering carbs. There are 2 apps:  [NSClient & NSClient2 to download](https://github.com/nightscout/AndroidAPS/releases/). Singura diferenţă este numele aplicaţiei. În acest fel puteți instala aplicația de două ori pe același telefon, pentru a putea urmari 2 persoane/nifghtscout-uri cu ele.
- Dexcom follow if you are using original Dexcom app (BG values only)
- [xDrip+](../Configuration/xdrip.md) in follower mode (mainly BG values and **alarms**)
- [Sugarmate](https://sugarmate.io/) or [Spike](https://spike-app.com/) on iOS (mainly BG values and **alarms**)

## Lucrurile de luat în considerare

- Setting the correct [treatment factors](../Getting-Started/FAQ.md#how-to-begin) (basal rate, DIA, ISF...) is difficult for kids, especially when growth hormones are involved.
- Setările trebuie să fie aceleași pentru AndroidAPS și NSClient.
- Consider time gap between master and follower due to time for up- and download as well as the fact that AAPS master phone will only upload after loop run.
- So take your time to set those correctly and test them in real life with your kid next to you before starting remote monitoring and remote treatment. Vacanța școlară ar putea fi o perioadă bună pentru asta.
- What is your emergency plan when remote control does not work (i.e. network problems)?
- Remote monitoring and treatment can be really helpful in kinder garden and elementary school. Dar asigurați-vă că profesorii și educatorii sunt conștienți de planul de tratament al copilului dumneavoastră. Examples for such care plans can be found in the [files section of AndroidAPS users](https://www.facebook.com/groups/AndroidAPSUsers/files/) on Facebook.