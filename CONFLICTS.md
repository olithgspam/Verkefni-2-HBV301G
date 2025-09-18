# Árekstragreining

## Business Strategy Conflicts
1. **Dæmi #1**
   - Átaksþáttur: Samkvæmt viðskiptakröfu [#1](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/1), er markmiðið að minnka tíma starfsfólks í lyfjaskipulagningu um 50%. Forstöðumenn telja að til þess þurfi að fjárfesta í fullbúnu kerfi. Sveitarfélög (viðskiptavinur) telja markmiðið of metnaðarfullt og vilja ódýrari grunnútgáfu af kerfinu, sem myndi gera 50% markmiðið óraunhæft.
   - Hagsmunaaðilar: Sveitarfélög, Yfirmenn og forstöðumenn.
   - Lausn: Stjórnendur þurfa að taka ákvörðun byggða á langtímamarkmiðum. Lausnin felst í því að forstöðumenn útbúa skýra viðskiptaáætlun (business case) sem sýnir fram á hvernig dýrari útgáfa skilar sér í framtíðinni með minni yfirvinnu og betri þjónustu, og réttlætir þannig fjárfestinguna fyrir sveitarfélaginu.

2. **Dæmi #2**
   - Átaksþáttur: Samkvæmt viðskiptakröfu [#2](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/3), er stefnan að auka sjálfstæði notenda með AI stuðningi. Aðstandendur lýsa yfir áhyggjum af þessari stefnu og óttast að notkun gervigreindar komi í stað mannlegra samskipta og geti verið skaðleg fyrir félagslega líðan þjónustunotenda.
   - Hagsmunaaðilar: Aðstandendur, Yfirmenn og forstöðumenn (sem fylgja stefnunni).
   - Lausn: Halda þarf kynningarfundi fyrir aðstandendur þar sem virkni og takmarkanir AI spjallmennisins eru útskýrðar. Áhersla er lögð á að þetta sé *viðbót* við þjónustu en komi aldrei í staðinn fyrir mannlega umönnun. Setja þarf skýrar verklagsreglur um hvenær og hvernig spjallmennið er notað.

## Requirements Value Conflicts
3. **Dæmi #3**
   - Átaksþáttur: Starfsfólk (kjörinn notendahópur) biður um að forgangsraða þróun á betra verkefnastjórnunartóli í appinu því það myndi spara þeim mikinn tíma. Á sama tíma kemur ósk frá talsmönnum þjónustunotenda um að bæta virkni AI-spjallmennisins til að veita betri sálrænan stuðning. Þróunarteymið hefur aðeins tíma fyrir annan möguleikann í næsta spretti.
   - Hagsmunaaðilar: Starfsfólk á heimilum, Þjónustunotendur.
   - Lausn: Þar sem "Starfsfólk" er skilgreint sem kjörinn (favoured) notendahópur, er kröfum þeirra gefinn forgangur að þessu sinni. Mikilvægt er þó að setja kröfur þjónustunotenda strax á tímalínuna fyrir næsta sprett á eftir og upplýsa þá um það, til að allir viti að hlustað sé á þeirra þarfir.

4. **Dæmi #4**
   - Átaksþáttur: Starfsmaðurinn "Anna Karen" (persóna) vill að viðmótið fyrir dagbókarskráningu sé mjög einfalt og fljótlegt, með fáum reitum til að fylla út. Yfirmenn vilja hins vegar ítarlegri skráningu með fleiri flokkunarmöguleikum til að geta tekið saman tölfræði um atvik.
   - Hagsmunaaðilar: Starfsfólk, Yfirmenn og forstöðumenn.
   - Lausn: Hér þarf að finna málamiðlun. Vörustjóri (product owner) eða kröfugreinandi sest niður með báðum hópum. Lausnin gæti verið að hafa einfalt grunnviðmót fyrir hraðskráningu en með "Ítarlegri skráning" takka sem opnar fleiri valmöguleika fyrir þau tilfelli þar sem þess er þörf.

## Requirements Substance Conflicts
5. **Dæmi #5**
   - Átaksþáttur: Öryggis- og persónuverndarfulltrúi setur þá kröfu að kerfið skrái notanda sjálfkrafa út eftir 5 mínútna óvirkni til að koma í veg fyrir óviðkomandi aðgang. Starfsfólk (Anna Karen) kvartar undan þessu, þar sem þau eru oft gripin frá tölvunni í smástund til að sinna þjónustunotanda og þurfa stöðugt að vera að skrá sig inn aftur.
   - Hagsmunaaðilar: Öryggis- og persónuverndarfulltrúi, Starfsfólk.
   - Lausn: Vörustjóri (product champion) tekur ákvörðun. Hægt er að gera málamiðlun: lengja tímann í 15 mínútur og/eða bjóða upp á hraðari endurauðkenningu (t.d. með PIN-númeri eða fingrafari) í stað fulls lykilorðs eftir stutt hlé til að finna jafnvægi milli öryggis og notagildis.

6. **Dæmi #6**
   - Átaksþáttur: Í lyfjagjafarviðmótinu vill þjónustunotandi sjá mjög einfalda sýn: mynd af lyfinu og einn stóran takka til að haka við "tekið". Starfsmaður þarf hins vegar að sjá ítarlegar upplýsingar á sömu skjámynd: skammtastærð, tímasetningu, birgðastöðu o.s.frv. Það er ómögulegt að hanna eina skjámynd sem hentar báðum.
   - Hagsmunaaðilar: Þjónustunotendur, Starfsfólk.
   - Lausn: Þetta er tæknilegur árekstur sem er leystur með hönnun. Lausnin er að búa til tvö mismunandi viðmót (role-based views) fyrir sömu virknina. Kerfið birtir einföldu útgáfuna ef þjónustunotandi er innskráður, en ítarlegu útgáfuna ef starfsmaður er innskráður.

## Requirements Process Conflicts
7. **Dæmi #7**
   - Átaksþáttur: Kröfugreinandi þarf að halda vinnufundi með starfsfólki til að skilgreina þarfir fyrir nýja virkni. Starfsfólkið afboðar sig hins vegar ítrekað þar sem það er of upptekið við umönnun og segist ekki hafa tíma í "einhverja fundi".
   - Hagsmunaaðilar: Starfsfólk, Kröfugreinandi (þróunarteymi), Yfirmenn.
   - Lausn: Yfirmenn og forstöðumenn þurfa að grípa inn í. Þeir verða að útskýra gildi kröfusöfnunar og formlega setja þessa vinnu inn í vinnutíma starfsfólks, t.d. með því að fá afleysingu á meðan fundað er. Þannig er sýnt fram á að framlag þeirra er mikilvægt og hluti af starfinu.

8. **Dæmi #8**
   - Átaksþáttur: Aðstandendur (óbeinn notendahópur) óska eftir því að appið "auki öryggiskennd þeirra" en geta ekki útskýrt það nánar í virkniskröfum. Þróunarteymið veit ekki hvað það þýðir í practís eða hvernig er hægt að útfæra það.
   - Hagsmunaaðilar: Aðstandendur, Kröfugreinandi (þróunarteymi).
   - Lausn: Kröfugreinandi þarf að beita annarri aðferð en að spyrja beint. Hann gæti boðið í viðtöl og spurt spurninga eins og: "Hvaða upplýsingar myndu veita þér hugarró?" eða "Hvað veldur þér áhyggjum í dag?". Með þessu er hægt að brjóta óskýra ósk niður í mælanlegar kröfur, eins og "að fá tilkynningu ef lyfjagjöf seinkar um meira en klukkutíma".
