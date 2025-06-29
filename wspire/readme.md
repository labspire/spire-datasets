# WSPIRE

The **wSPIRE corpus** is an extensive multi-device speech database specifically designed to capture recordings in both **neutral** and **whispered** modes. It encompasses recordings from 92 speakers, utilizing 5 different devices to ensure diverse audio capture scenarios. The corpus features parallel recordings in both neutral and whispered speech, allowing for detailed comparative analysis. All recordings were meticulously conducted in a soundproof recording room at the Electrical Engineering Department of the Indian Institute of Science (IISc), Bangalore. The participants, who contributed to this dataset, are primarily graduate students, interns, or employees affiliated with IISc. This dataset is a valuable resource for research in speech processing and acoustic analysis, offering high-quality recordings across neutral and whispered speech modes and consistent environmental conditions using multiple recording devices.

- **Speakers:** 92 total
- **Devices:** 5 distinct devices for diverse audio conditions
- **Speech Modes:** Parallel recordings in **neutral** and **whispered** modes
- **Environment:** Soundproof studio at the **Electrical Engineering Department**, Indian Institute of Science (IISc), Bangalore


---
### Directory Strcture:
Directory Structure:
```
IISc_wSPIRE/
├── [Gender]_[Mode]_[Device]/ (example: F_Neutral_Headset) (It contains wav files and their correspnding word-level annotations according to gender of the speaker, mode of speech and recording device)
│   ├── wav/ (It contains audio files in .wav format)
│   │   ├── ID0[ID]_00[SET]_[GENDER]_[MODE]_[DEVICE]_[SENTNUM].wav
│   │   ├── ID0100_001_F_Neutral_Headset_01.wav (example)
│   │   ├── ....
│   ├── timestamp/ (It contains word-level annotations)
│   │   ├── ID0[ID]_00[SET]_[GENDER]_[MODE]_[DEVICE]_[SENTNUM].lab
│   │   ├── ID0100_001_F_Neutral_Headset_01.lab.txt (example)
│   │   ├── ....
```


---

## Recording and Setup

### Audio Specs
- **Original Sample Rate:** 44.1 kHz  
- **Downsampled To:** 16 kHz

### Devices Used
1. Zoom XYH-6 Adjustable Stereo Microphone Capsule - [LINK](https://www.zoom.co.jp/products/product-accessories/xyh-6-xy-stereo-microphone-capsule)
2. Philips Stereo Headphones SHP1900/97 - [LINK](https://www.philips.co.in/c-p/SHP1900_97/stereo-headphones)
3. Apple iPhone 7 - [LINK](https://www.gsmarena.com/apple_iphone_7-8064.php)
4. Nokia 5.1 - [LINK](https://www.nokia.com/phones/en_int/nokia-5-1)
5. Motorola moto e5 plus - [LINK](https://www.motorola.in/smartphones-moto-e5-plus/p)

### Sentences used:

Sentences Used (taken from MOCHA-TIMIT corpus):

001. This was easy for us.
002. Is this seesaw safe?
003. Those thieves stole thirty jewels.
004. Jane may earn more money by working hard.
005. She is thinner than I am.
006. Bright sunshine shimmers on the ocean.
007. Nothing is as offensive as innocence.
008. Why yell or worry over silly items?
009. Where were you while we were away?
010. Are your grades higher or lower than Nancy's?
011. He will allow a rare lie.
012. Will Robin wear a yellow lily?
013. Swing your arm as high as you can.
014. Before Thursday's exam, review every formula.
015. The museum hires musicians every evening.
016. A roll of wire lay near the wall.
017. Carl lives in a lively home.
018. Alimony harms a divorced man's wealth.
019. Aluminium cutlery can often be flimsy.
020. She wore warm, fleecy, woolen overalls.
021. Alfalfa is healthy for you.
022. When all else fails, use force.
023. Those musicians harmonize marvellously.
024. Although always alone, we survive.
025. Only lawyers love millionaires.
026. Most young rabbits rise early every morning.
027. Did dad do academic bidding?
028. Beg that guard for one gallon of petrol.
029. Help Greg to pick a peck of potatoes.
030. Get a calico cat to keep the rodents away.
031. A good attitude is unbeatable.
032. Tina Turner is a pop singer.
033. Coconut cream pie makes a nice dessert.
034. Don't do Charlie's dirty dishes.
035. Help celebrate your brother's success.
036. Only the most accomplished artists obtain popularity.
037. Critical equipment needs proper maintenance.
038. Young people participate in athletic activities.
039. Barb's gold bracelet was a graduation present.
040. Stimulating discussions keep students' attention.
041. Etiquette mandates compliance with existing regulations.
042. Biblical scholars argue history.
043. Elderly people are often excluded.
044. Basketball can be an entertaining sport.
045. Addition and subtraction are learned skills.
046. That pickpocket was caught red-handed.
047. Mum strongly dislikes appetizers.
048. Grandmother outgrew her upbringing in petticoats.
049. At twilight on the twelfth day we'll have Chablis.
050. Catastrophic economic cutbacks neglect the poor.
051. Ambidextrous pickpockets accomplish more.
052. Her classical repertoire gained critical acclaim.
053. Even a simple vocabulary contains symbols.
054. The eastern coast is a place for pure pleasure and excitement.
055. The lack of heat compounded the tenant's grievances.
056. Academic aptitude guarantees your diploma.
057. The prowler wore a ski mask for disguise.
058. We experience distress and frustration obtaining our degrees.
059. The singer's finger had a splinter.
060. The legislature met to judge the state of public education.
061. Chocolate and roses never fail as a romantic gift.
062. Any contributions will be greatly appreciated.
063. Continental drift is a geological theory.
064. Regular attendance is seldom required.
065. Challenge each general's intelligence.
066. We got drenched from the uninterrupted rain.
067. Last year's gas shortage caused steep price increases.
068. Upgrade your status to reflect your wealth.
069. Eat your raisins outdoors on the porch steps.
070. Did you eat lunch yesterday?
071. Porcupines resemble sea urchins.
072. Spring Street is straight ahead.
073. Cliff's display was misplaced on the screen.
074. An official deadline cannot be postponed.
075. Fill that canteen with fresh spring water.
076. Gently place Jim's foam sculpture in the box.
077. Bagpipes and bongos are musical instruments.
078. Doctors prescribe drugs too freely.
079. Will you please describe the idiotic predicament.
080. It's illegal to postdate a cheque.
081. It's impossible to deal with bureaucracy.
082. Good service should be rewarded by big tips.
083. My instructions desperately need updating.
084. Cooperation along with understanding alleviate dispute.
085. Cement is measured in cubic yards.
086. Hispanic costumes are quite colourful.
087. Primitive tribes have an upbeat attitude
088. Flying standby can be practical if you want to save money.
089. It's hard to tell an original from a forgery.
090. The Thinker is a famous sculpture.
091. The misprint provoked an immediate disclaimer.
092. A large household needs lots of appliances.
093. Cut a small corner off each edge.
094. Youngsters love corn candy as a treat.
095. Iguanas and alligators are tropical reptiles.
096. Masquerade parties tax one's imagination.
097. Glucose and fructose are natural sugars found in fruit.
098. Penguins live near the icy Antarctic.
099. Guess the question from the answer.
100. Medieval society was based on hierarchies.
101. Project development was proceeding too slowly.
102. Kindergarten children decorate their classrooms for all holidays.
103. Special task forces rescue hostages from kidnappers.
104. Call an ambulance for medical assistance.
105. He stole a dime from a beggar.
106. Few people live to be a hundred.
107. You must explicitly delete files.
108. A huge tapestry hung in her hallway.
109. Birthday parties have cupcakes and ice cream.
110. His scalp was blistered from today's hot sun.
111. She slipped and sprained her ankle on the steep slope.
112. The best way to learn is to solve extra problems.
113. His sudden departure shocked the cast.
114. Tugboats are capable of hauling huge loads.
115. A muscular abdomen is good for your back.
116. The cartoon features a muskrat and a tadpole.
117. The emblem depicts the Acropolis all aglow.
118. Clasp the screw in your left hand.
119. The mango and the papaya are in a bowl.
120. Combine all the ingredients in a large bowl.
121. The misquote was retracted with an apology.
122. The coyote, bobcat, and hyena are wild animals.
123. Trespassing is forbidden and subject to penalty.
124. Encyclopedias seldom present anecdotal evidence.
125. A screwdriver is made from vodka and orange juice.
126. Objects made of pewter are beautiful.
127. Westchester is a county in New York.
128. Artificial intelligence is for real.
129. The emperor had a mean temper.
130. Lots of foreign movies have subtitles.
131. Angora cats are furrier than Siamese.
132. He ate four extra eggs for breakfast.
133. We plan to build a new beverage plant.
134. Publicity and notoriety go hand in hand.
135. Pizzerias are convenient for a quick lunch.
136. December and January are nice months to spend in Miami.
137. Technical writers can abbreviate in bibliographies.
138. Scientific progress comes from the development of new techniques.
139. Tradition requires parental approval for under-age marriage.
140. The clumsy customer spilled some expensive perfume.
141. The bungalow was pleasantly situated near the shore.
142. Agricultural products are unevenly distributed.  
143. Pledge to participate in Nevada's aquatic competition.
144. Which long article was opaque and needed clarification?
145. The sound of Jennifer's bugle scared the antelope.
146. The willowy woman wore a muskrat coat.
147. Too much curiosity can get you into trouble.
148. Cyclical programs will never compile.
149. Correct execution of my instructions is crucial.
150. Most precincts had a third of the votes counted.
151. While waiting for Chipper she crisscrossed the square many times.
152. Vietnamese cuisine is exquisite.
153. The previous speaker presented ambiguous results.
154. Mosquitoes exist in warm, humid climates.
155. Scholastic aptitude is judged by standardized tests.
156. Orange juice tastes funny after toothpaste.
157. The water contained too much chlorine and stung his eyes.
158. Our experiment's positive outcome was unexpected.
159. Remove the splinter with a pair of tweezers.
160. The drunkard is a social outcast.
161. The government sought authorization of his citizenship.
162. As co-authors, we presented our new book to the haughty audience.
163. As a precaution, the outlaws bought gunpowder for their stronghold.
164. Her auburn hair reminded him of autumn leaves.
165. They remained lifelong friends and companions.
166. Curiosity and mediocrity seldom co-exist.
167. The easy going zoologist relaxed throughout the voyage.
168. Biologists use radioactive isotopes to study microorganisms. 
169. Employee layoffs coincided with the company's reorganization.
170. Who took the kayak down the bayou?
171. How would you evaluate this algebraic expression?
172. The Mayan neoclassic scholar disappeared while surveying ancient ruins.
173. The diagnosis was discouraging; however, he was not overly worried.
174. The altruistic dowager helped many malnourished vagrants.
175. The triumphant warrior exhibited naive heroism.
176. Whoever cooperates in finding Nan's cameo will be rewarded.
177. The haunted house was a hit due to outstanding audiovisual effects.
178. Severe myopia contributed to Ron's inferiority complex.
179. Buying a thoroughbred horse requires intuition and expertise.
180. Does creole cooking use curry? 
181. She encouraged her children to make their own Halloween costumes.
182. We could barely see the fjords through the snow flurries.
183. Almost all colleges are now co-educational.
184. Rich looked for spotted hyenas and jaguars on the safari.
185. Thick glue oozed out of the tube.
186. They all enjoy ice cream sundaes.
187. Why else would Danny allow others to go?
188. The cat's meow always hurts my ears.
189. Did you buy any corduroy overalls?
190. Would a tomboy often play outdoors?
191. They often go out in the evening.
192. Who authorized the unlimited expense account?
193. Destroy every file related to my audits.
194. Serve the coleslaw after I add the oil.
195. Withdraw all phony accusations at once.
196. Straw hats are out of fashion this year.
197. Why buy oil when you always use mine?
198. They enjoy it when I audition.
199. Would you allow acts of violence?
200. How do oysters make pearls?
201. Draw each graph on a new axis.
202. Norwegian sweaters are made of lamb's wool.
203. Young children should avoid exposure to contagious diseases.
204. Ralph controlled the stopwatch from the bleachers.
205. Approach your interview with statuesque composure.
206. How much allowance do you get?
207. The causeway ended abruptly at the shore.
208. Even I occasionally get the Monday blues!
209. Military personnel are expected to obey government orders.
210. When peeling an orange, it is hard not to spray juice.
211. Do you hear the sleigh bells ringing?
212. Rob sat by the pond and sketched the stray geese.
213. Michael colored the bedroom wall with crayons.
214. Jeff's toy go-cart never worked!
215. Only the best players enjoy popularity.
216. I gave them several choices and let them set the priorities.
217. The news agency hired a great journalist.
218. The morning dew on the spider web glistened in the sun.
219. The sermon emphasized the need for affirmative action.
220. The small boy put the worm on the hook.
221. How permanent are their records?
222. Try to recall the events in chronological order.
223. Non-profit organizations have frequent fundraisers.
224. The most recent geological survey found seismic activity.
225. Cory attacked the project with extra determination.
226. You always come up with pathological examples.
227. Put the butcher block table in the garage.
228. How good is your endurance?
229. Keep the thermometer under your tongue!
230. Steph could barely handle the psychological trauma.
231. It's healthier to cook without sugar.
232. The viewpoint overlooked the ocean.
233. Are you looking for employment?
234. Allow leeway here.
235. I honour my mum.
236. His failure to open the store by eight cost him his job.
237. Rationalize all errors.
238. Highway and freeway mean the same thing.
239. The paper boy bought two apples and three ices.
240. I itemize all accounts in my agency.
241. Clear pronunciation is appreciated.
242. The courier was a dwarf.
243. A doctor was in the ambulance with the patient.
244. Puree some fruit before preparing the skewers.
245. It's not easy to create illuminating examples.
246. The hallway opens into a huge chamber.
247. May I order a parfait after I eat dinner?
248. They all agree that the essay is barely intelligible.
249. Herb's birthday frequently occurs on Thanksgiving.
250. Does Hindu ideology honour cows?
251. How ancient is this subway escalator?
252. The cigarettes in the clay ashtray overflowed onto the oak table.
253. Reading in poor light gives you eyestrain.
254. I ate every oyster on Nora's plate.
255. The Boston Ballet overcame their funding shortage.
256. We apply auditory modelling to computer speech recognition.
257. The gorgeous butterfly ate a lot of nectar.
258. By eating yogurt, you may live longer.
259. Do they allow atheists in church?
260. My ideal morning begins with hot coffee.
261. The irate actor stomped away idiotically.
262. We are open every Monday evening.
263. The essay undeniably reflects our view ably.
264. Tornados often destroy aviaries.
265. Remember to allow identical twins to enter freely.
266. Do you have the yellow ointment ready?
267. Can the agency overthrow alien forces?
268. How oily do you like your salad dressing?
269. We saw eight tiny icicles below our roof.
270. The saw is broken, so chop the wood instead.
271. Withdraw only as much money as you need.
272. Draw every outer line first, then fill in the interior.
273. The jaw operates by using antagonistic muscles.
274. Do atypical farmers grow oats?
275. Are holiday aprons available to us?
276. Be careful not to plow over the flower beds.
277. Allow each child to have an ice pop.
278. The angry boy answered but didn't look up.
279. Cliff was soothed by the luxurious massage.
280. Steve wore a bright red cashmere sweater.
281. John's brother repainted the garage door.
282. The rose corsage smelled sweet.
283. To further his prestige, he occasionally reads the Wall Street Journal.
284. Alice's ability to work without supervision is noteworthy.
285. The oasis was a mirage.
286. Cory and Trish played tag with beach balls for hours.
287. The tooth fairy forgot to come when Roger's tooth fell out.
288. Planned parenthood organizations promote birth control.
289. Jeff thought you argued in favour of a centrifuge purchase.
290. Rich purchased several signed lithographs.
291. In every major cloverleaf, traffic sometimes gets backed up.
292. In the long run, it pays to buy quality clothing.
293. Brush fires are common in the dry underbrush of Nevada.
294. Weatherproof galoshes are very useful in Seattle.
295. This brochure is particularly informative for a prospective buyer.
296. The avalanche triggered a minor earthquake.
297. These exclusive documents must be locked up at all times.
298. Please take this dirty table cloth to the cleaners for me.
299. Should giraffes be kept in small zoos?
300. If Carol comes tomorrow, have her arrange for a meeting at two.
301. The two artists exchanged autographs.
302. Rock-and-roll music has a great rhythm.
303. I'd rather not buy these shoes than be overcharged.
304. Shaving cream is a popular item on Halloween.
305. Amoebas change shape constantly.
306. We like blue cheese but Victor likes brie.
307. Tofu is made from processed soybeans.
308. The bluejay flew over the high building.
309. Cheap stockings run the first time they're worn.
310. Cottage cheese with chives is delicious.
311. A chosen few will become Generals.
312. The meeting is now adjourned.
313. Shipbuilding is a most fascinating process.
314. The proof that you are seeking is not available in books.
315. The hood of the jeep was steaming in the hot sun.
316. My desires are simple: give me one informative paragraph on the subject.
317. Those answers will be straightforward if you think them through carefully
317. first.
318. Drop five forms in the box before you go out.
319. If people were more generous, there would be no need for welfare.
320. Bob found more clams at the ocean's edge.
321. That dog chases cats mercilessly.
322. The cranberry bog gets very pretty in Autumn.
323. Please dig my potatoes up before the frost.
324. A big goat idly ambled through the farmyard.
325. The nearest synagogue may not be within walking distance.
326. The groundhog clearly saw his shadow, but stayed out only a moment.
327. A leather handbag would be a suitable gift.
328. The fog prevented them from arriving on time.
329. The local drugstore was charged with illegally dispensing tranquilizers.
330. The full moon shone brightly that night.
331. Steve collects rare and novel coins.
332. Al received a joint appointment in the biology and the engineering
332. departments.
333. Gregory and Tom chose to watch cartoons in the afternoon.
334. Chip postponed alimony payments until the latest possible date.
335. Count the number of teaspoons of soysauce that you add.
336. The big dog loved to chew on the old rag doll.
337. Todd placed top priority on getting his bike fixed.
338. An adult male baboon's teeth are not suitable for eating shellfish.
339. Often you'll get back more than you put in.
340. Gus saw pine trees and redwoods on his walk through Sequoia National
340. Forest.
341. Rob made Hungarian goulash for dinner and gooseberry pie for desert.
342. Bob bandaged both wounds with the skill of a doctor.
343. The dark, murky lagoon wound around for miles.
344. Did Shawn catch that big goose without help?
345. Ducks have webbed feet and colorful feathers.
346. The high security prison was surrounded by barbed wire.
347. Take charge of choosing her bride's maids' gowns.
348. The frightened child was gently subdued by his big brother.
349. I know I didn't meet her early enough.
350. Trish saw hours and hours of movies this Saturday.
351. The barracuda recoiled from the serpent's poisonous fangs.
352. The patient and the surgeon are both recuperating from the lengthy
352. operation.
353. I'll have a scoop of that exotic purple and turquoise sherbet.
354. The preschooler couldn't verbalize her feelings about the emergency
354. conditions.
355. Many wealthy tycoons splurged and bought both a yacht and a schooner.
356. The new suburbanites worked hard on refurbishing their older home.
357. According to my interpretation of the problem, two lines must be
357. perpendicular.
358. A connoisseur will enjoy this shellfish dish.
359. A lawyer was appointed to execute her will.
360. Dolphins are intelligent marine mammals.
361. Diane may splurge and buy a turquoise necklace.
362. The moisture in my eyes is from eyedrops, not from tears.
363. George seldom watches daytime movies.
364. The system may break down soon, so save your files frequently.
365. I assume moisture will damage this ship's hull.
366. The speech symposium might begin on Monday.
367. The annoying raccoons slipped into Phil's garden every night.
368. The cow wandered from the farmland and became lost.
369. Each untimey income loss coincided with the breakdown of a heating
369. system part.
370. The gunman kept his victim cornered at gunpoint for three hours.
371. Will you please confirm government policy regarding waste removal?
372. The surplus shoes were sold at a discount price.
373. Lori's costume needed black gloves to be completely elegant.
374. Bob papered over the living room murals.
375. That noise problem grows more annoying each day.
376. Right now may not be the best time for business mergers.
377. That diagram makes sense only after much study.
378. Gremlins is yet another exciting movie b Steven Spielberg.
379. A boring novel is a superb sleeping pill.
380. John cleans shellfish for a living.
381. Growing well-kept gardens is very time consuming.
382. Women may never become completely equal to men.
383. She always jokes about too much garlic in his food.
384. I just saw Jim near the new archeological museum.
385. Pam gives driving lessons on Thursdays.
386. Why charge money for such garbage?
387. We welcome many new students each year.
388. George is paranoid about a future gas shortage.
389. The carpet cleaners shampooed our oriental rug.
390. Please shorten this skirt for Joyce.
391. His shoulder felt as if it were broken.
392. Which church do the Smiths worship in?
393. The giant redwoods shimmered in the glistening sun.
394. Is she going with you?
395. Her right hand aches whenever the barometric pressure changes.
396. They own a big house in the remote countryside.
397. He picked up nine pairs of socks for each brother.
398. They all like long hot showers.
399. A young mouse scampered across the field and disappeared.
400. She uses both names interchangeably.
401. Calcium makes bones and teeth strong.
402. I took her word for it.
403. The fish began to leap frantically on the surface of the small lake.
404. Tim takes Sheila to see movies twice a week.
405. Children can consume many fruit roll-ups in one sitting.
406. They assume no burglar will ever enter here.
407. Just drop notices in any suggestion box.
408. The taxicab broke down and caused a traffic jam.
409. We'll serve rhubarb pie after Rachel's talk.
410. Her wardrobe consists of only skirts and blouses.
411. Barb burned paper and leaves in a big bonfire.
412. Of course you can have another tunafish sandwich.
413. There was a gigantic wasp next to Irving's big top hat.
414. Laugh, dance, and sing if fortune smiles upon you.
415. I'd ride the subway, but I haven't enough change.
416. Eating spinach nightly increases strength miraculously.
417. People drink much water with horseradish relish.
418. Butterscotch fudge goes well with vanilla ice cream.
419. Gwen grows green beans in her vegetable garden.	
420. Daphne's Swedish needlepoint scarf matched her skirt.
421. Irish youngsters eat fresh kippers for breakfast.
422. Move the garbage nearer to the large window.
423. A huge power outage rarely occurs.
424. Valley lodge yearly celebrates the first calf born.
425. Iris thinks this zoo has eleven Spanish zebras.
426. The football team coach has a watch as thin as a dime.
427. Seamstresses attach zips with a thimble, needle, and thread.
428. Those who teach values first abolish cheating.
429. Once you finish greasing your chain, be sure to wash thoroughly.
430. Smash lightbulbs and their cash value will diminish to nothing.
431. Top zinnias rarely have crooked stems.
432. Movies never have enough villains.
433. A moth zig-zagged along the path through Otto's garden.
434. Every cab needs repainting often.
435. A crab challenged me, but a quick stab vanquished him.
436. A toothpaste tube should be squeezed from the bottom.
437. Those who are not purists use canned vegetables when making stew.
438. The fifth jar contains big, juicy peaches.
439. Coffee is grown on steep, jungle-like slopes in temperate zones.
440. The overweight charmer could slip poison into anyone's tea.
441. Each stag surely finds a big fawn.
442. The rich should invest in black zircons instead of stylish shoes.
443. Please sing just the club theme.
444. They used an aggressive policeman to flag thoughtless motorists.
445. Shell shock caused by shrapnel is sometimes cured through group therapy.
446. That stinging vapour was caused by chloride vaporization.
447. The advertising verse of Plymouth Variety Store never changes.
448. Don't look for cheap valuables in a bank vault.
449. Suburban housewives often suffer from the gab habit.
450. A lone star shone in the early evening sky.

---

### Recording Procedure

- At first, every speaker was asked to speak all the sentences in the assigned set in neutral mode and then in the whispered mode.
- Three different tones, each having a duration of 1 second, were used while recording.
- Further, to indicate the beginning of each sentence, a tone of constant frequency of 1kHz was played.
- An up-tone of 1-second duration, with frequency increasing from 1kHz to 2kHz, was played when the speaker pronounced the sentence correctly. Similarly, a down-tone of 1-second duration with frequency decreasing from 2kHz to 1kHz was played if the sentence was mispronounced.
- In case of wrong pronunciation, speakers were asked to repeat the sentence

---

## Data Description

- **Sentences:** First **450 sentences** from the [**MOCHA-TIMIT corpus**](https://data.cstr.ed.ac.uk/mocha/mocha-timit.txt) (phonetically balanced) 
- **Division:** 450 sentences split into **9 sets**, each with **50 sentences**

---

## File Naming Convention

Each audio and timestamp file is uniquely named using the following structure:

```
ID0[ID]_00[SET]_[GENDER]_[MODE]_[DEVICE]_[SENTNUM]
```

### Examples
- **Audio:**  
  `ID06_006_F_Neutral_Headset_11.wav`
- **Timestamp:**  
  `ID06_006_F_Neutral_Headset_11.lab`

### Fields
- **ID:** Speaker ID (e.g., `06`)
- **SET:** Sentence set number (1–9)
- **GENDER:** `M` for Male, `F` for Female
- **MODE:** `Neutral` or `Whisper`
- **DEVICE:** One of `Headset`, `Zoom`, `iPhone`, `Moto`, `Nokia`
- **SENTNUM:** Sentence number in that set (1–50)

### Word Transcription:

An example of word-level annotaion provided in wSPIRE. (.lab)
```
starting    ending      word
timestamp   timestamp
-----------------------------
0.000000	0.155025	SIL
0.155025	0.346414	How
0.346414	0.750245	ancient 
0.750245	0.782781	SIL
0.782781	1.014362	is
1.014362	1.071779	SIL
1.071779	1.282307	this
1.282307	1.494749	SIL
1.494749	1.940685	subway
1.940685	2.547389	escalator
2.547389	2.614375	SIL
```
---

## Speaker Information

| ID  | Age | Gender | Set |
|-----|-----|--------|-----|
| 4   | 24  | Male   | 4   |
| 5   | 24  | Male   | 5   |
| 6   | 21  | Female | 6   |
| 7   | 24  | Male   | 7   |
| 8   | 22  | Male   | 8   |
| 12  | 30  | Female | 2   |
| 13  | 24  | Male   | 3   |
| 14  | 26  | Male   | 4   |
| 16  | 23  | Male   | 6   |
| 17  | 24  | Female | 7   |
| 18  | 28  | Female | 8   |
| 19  | 23  | Female | 9   |
| 21  | 20  | Female | 3   |
| 22  | 25  | Female | 4   |
| 23  | 27  | Male   | 5   |
| 24  | 24  | Male   | 6   |
| 25  | 22  | Male   | 7   |
| 26  | 23  | Male   | 8   |
| 27  | 22  | Male   | 9   |
| 28  | 31  | Male   | 1   |
| 29  | 22  | Female | 2   |
| 30  | 22  | Female | 3   |
| 31  | 22  | Female | 4   |
| 32  | 22  | Female | 5   |
| 33  | 23  | Male   | 6   |
| 34  | 28  | Female | 7   |
| 35  | 23  | Male   | 8   |
| 36  | 26  | Female | 9   |
| 37  | 21  | Male   | 1   |
| 38  | 23  | Male   | 2   |
| 39  | 24  | Male   | 3   |
| 40  | 25  | Female | 4   |
| 41  | 28  | Male   | 5   |
| 42  | 21  | Female | 6   |
| 43  | 30  | Male   | 7   |
| 44  | 23  | Female | 9   |
| 45  | 24  | Male   | 1   |
| 46  | 37  | Female | 2   |
| 47  | 23  | Female | 3   |
| 48  | 30  | Male   | 4   |
| 49  | 23  | Male   | 5   |
| 50  | 31  | Female | 6   |
| 51  | 22  | Female | 7   |
| 52  | 24  | Male   | 8   |
| 53  | 21  | Male   | 9   |
| 54  | 25  | Male   | 1   |
| 55  | 24  | Male   | 2   |
| 56  | 28  | Female | 3   |
| 57  | 25  | Female | 4   |
| 58  | 32  | Male   | 5   |
| 59  | 25  | Male   | 6   |
| 60  | 23  | Male   | 7   |
| 62  | 22  | Male   | 9   |
| 63  | 22  | Male   | 1   |
| 64  | 24  | Male   | 2   |
| 65  | 20  | Male   | 3   |
| 66  | 23  | Male   | 4   |
| 67  | 24  | Female | 5   |
| 68  | 23  | Female | 6   |
| 69  | 21  | Female | 7   |
| 70  | 22  | Male   | 8   |
| 71  | 27  | Female | 9   |
| 72  | 24  | Male   | 1   |
| 73  | 24  | Male   | 2   |
| 74  | 22  | Female | 3   |
| 75  | 29  | Male   | 4   |
| 76  | 26  | Female | 5   |
| 77  | 29  | Male   | 6   |
| 79  | 23  | Male   | 8   |
| 80  | 27  | Female | 9   |
| 83  | 23  | Female | 3   |
| 84  | 30  | Female | 4   |
| 85  | 23  | Male   | 5   |
| 86  | 26  | Female | 6   |
| 87  | 23  | Male   | 7   |
| 88  | 25  | Male   | 8   |
| 89  | 23  | Male   | 9   |
| 90  | 23  | Female | 1   |
| 92  | 27  | Male   | 2   |
| 93  | 28  | Male   | 3   |
| 95  | 24  | Male   | 5   |
| 96  | 23  | Male   | 6   |
| 97  | 22  | Male   | 7   |
| 98  | 22  | Male   | 8   |
| 99  | 23  | Male   | 9   |
| 100 | 22  | Female | 1   |
| 101 | 25  | Male   | 2   |
| 102 | 24  | Male   | 3   |
| 103 | -   | Female | 4   | 
| 104 | -   | Male   | 5   |
| 105 | -   | Male   | 6   |
| 106 | -   | Male   | 7   |    


---

## License
wSPIRE data collected by Spire lab, Indian Institute of Science, Bengaluru is available at https://spiredatasets.ee.iisc.ac.in/wspirecorpus and the copyright for this data belongs to Indian Institute of Science, Bengaluru and the said data is released or distributed under CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en). Users are advised to refer to the "Disclaimer of Warranties" section in the license agreement before using the dataset.

## Citation

*If you use the **wSPIRE corpus** in your research, please cite the following publication:*

*Singhal, Bhavuk, Abinay Reddy Naini, and Prasanta Kumar Ghosh. ["wSPIRE: A parallel multi-device corpus in neutral and whispered speech."](https://ieeexplore.ieee.org/document/9660449) In 2021 24th Conference of the Oriental COCOSDA International Committee for the Co-ordination and Standardisation of Speech Databases and Assessment Techniques (O-COCOSDA), pp. 146-151. IEEE, 2021.*


For more details, visit the [wSPIRE Corpus](https://spiredatasets.ee.iisc.ac.in/wspirecorpus) page.
