I woke up and I didn’t remember who I was, but nothing else seemed out of the ordinary.  My head, and the rest of my body, seemed totally uninjured.  The apartment room in which I awoke looked ordinary, albeit messy…whoever had been living there, and that was probably me, cooked a dinner and didn’t wash the dishes.  The stove was still warm.  The clock said 8PM.  

I checked the mirror.  I looked 16, but something I couldn’t put into words told me I was a little older than that.  I looked Asian, probably Filipino or Korean.  I could remember the title of every recent Marvel movie, the lyrics to every Coldplay song in existence, and every power of 2 from 2^0 to 2^32 (for some unknown reason).  What I couldn’t remember was anything about myself or how I had gotten here.

I explored the town that I found myself in.  It was snowing, but there were no people to shovel snow.  I traversed the entire thing, a dinky little town with shops and houses and roads but no people, all contained as a gated community with no marked path to lead out.  There were no vehicles, either, but they felt the need to make roads.  I couldn’t understand it at all.

There are lots of bottled water and ramen, though.  I spent the next two months subsisting on that.

In those two months, I investigated my surroundings more closely and tried to figure out who I was.  I found a book called Journal, but it was gibberish—it was written in greek letters, and weird line formations that looked kind of like musical notes, and at one point I swear I saw the fucking anarchy symbol.  I found a more sensible file called README, and I figured that was supposed to be read, but it was equally mysterious:

-initial commit

-making a building

-merge pull request #18 from branch c00lhacker1337/feature9

-prototype complete

-weird bug

-no No NO NO NO NO

-pray to God for help

-GOD CANT HELP US NOW

-….

-….

-Commit Message

I found a lot of notes, but they were long-winded and usually wrong.  Some labeled houses, but they gave them worthlessly non-descriptive names like house1, thisHouse, and houseInstance.  Most diagrams led me to an enormous hotel-like building in the center of town I had apparently been designing.  This building was awful, as if someone was simply asked to continually add rooms to something with no initial plan.  The hallways winded endlessly.  Some of the doors, even as high up as the 14th floor,  just led outside.  The rooms, instead of having numbers, had confusing word names that were the same for entire floors.  On one floor, every single room was called hotelSystemConfig.  On another floor, which was like an identical copy but with a few added differences, every single room was called HotelSystemConfig.  On the ground floor, for no reason at all, every room was just called FuckYouSteven.

I reached a point where I just couldn’t take it anymore, so on an impulse I set the whole thing on fire.  This was a mistake.  The building was surprisingly flammable.  The entire town doesn’t exist anymore because it’s ashes, and I was forced to take a backpack full of canned food I salvaged and head North, into the unknown.

Part I. The Jewels and Stones

After three days I met a kind man who lived by a river.

I was being pursued by something.  It was night and I could hardly see.  I had encountered birds, rabbits, and feral cats…never anything like this.  In the dark, it looked like a monster wolf that was three or four times larger than a normal wolf.  It was fast-moving, and it made a sound like an auto-tuned whale in agony.

I saw a lighted cabin and made a run for it.  The door opened and a man, unphased and with a large item in his hand, shut the door and kept his ground.  He took aim with his gun (I could see it now, it was a rifle) and fired.  The beast stopped and screamed in pain as the shots kept coming.  It died, and the thorough work of the shooter ensured that it would stay down.

“Come inside,” said the man, his face illuminated by the porchlight and his gun smoking, “it’s cold out there.”

His name, I learned, was K.  When he asked me for mine, I lied and said it was J because J comes before K.  K let me stay with him for two weeks, and he seemed to genuinely enjoy the company.  It was the most relaxed, most peaceful two weeks I would have.  It was all downhill after that, and if I knew how insane everything would become after I left then I might have stayed.

In the mornings he would leave for his work, which was at at a mine he operated entirely by himself.  I read the books he had lying around, which were mostly on geology.  He told me there was a large town nearby, but that the rocky terrain made it only possible to get there on foot, with a walk that took four hours.  Every day, they would present him with a handful of stones identified as the current set of jewels.  

K seemed amiable enough, but very introverted.  The few conversations we had were very nondescript.

“K, can I ask you something?”

“Sure.”

“Are you married?”

“No.”

“How long have you lived alone?”

“Ten years.”

“Oh wow.”

“Yeah.”

From the geology books, I learned that the subject worked differently in this place.  K’s mining work was very efficient, and his machines provided him with large collections of valuable stones every few hours.  The largest stones were the size of a standard wine glass bulb; the smallest were no larger than a water droplet.

At a point, I started to help him in his work.  The town provided him with sets of stones that were considered jewels, and he was asked to identify which of his stones were jewels and collect them.  He had a device that scanned stones, and represented their value with a letter.  

Example 1:

Jewels: “AC”

Stones: “ACACAC”

Result: All six are jewels

Example 2:

Jewels: “AD”

Stones: “ACACAC”

Result: The three As are jewels

Assumptions: Jewels are distinct, these letters are in English, every day the jewels list changes because of the S&P500 or something

On the first day I helped him, K gave me a set of about 12 stones and three jewels.  The work was tedious, but easy.  I followed his recommended approach and took the first jewel, scanned it, then scanned all 12 stones to see if any were jewels.  Then I took the second jewel, scanned it, and scanned the 12 again to see if any was a jewel.  Finally, I took the third jewel, scanned it, and scanned the 12 again to see if any was a jewel.  

That night, I excitedly asked K if he had ever thought of ways to optimize his methods.  He said he hadn’t, but he was very open to the idea.  In hindsight that would have been a good time to suggest removing stones already identified as jewels, but for some reason I never tried that.

On the second day I helped him, K gave me a set of 100 stones and seven jewels.  The work this time was far more intense and took me much longer.  In frustration, I started to take 15-minute runs by the river to cool off.

On the third day I helped him, K gave me a set of 1000 stones and 12 jewels.  In anger, and during a run, an idea came to me.

“Let’s start by scanning the jewels,” I explained, “and then use a notebook to mark down what the jewel letters are.  Then every time we scan a stone, we check to see if it matches anything written down in the notebook.”

“Wow, that’s much smarter.  You’ve basically created a hashmap.”

“No, I created a simple chart with 26 boxes that I use to keep track of jewels.”

“I hate to break it to you, but that’s a hashmap.”

“So it will work?”

“Yes, this is great.  It doesn’t solve space complexity, but it really improves on the asymptotic time.”

“Right, big oh of m plus n now.”  I said that last part automatically.  I still didn’t know what he was talking about, but this conversation brought back a strange memory in me.

“I hope this helps,” I said, opting to wrap this up and sleep instead of trying to bring back more memories.

“Absolutely.  Something that scales like this will improve my profits immensely.”

We worked together for a few more days.  He brought in much more money.  He was so pleased with my contribution that he gave me his most valuable jewel: An onion-sized red crystal he said had magical properties.  I didn’t know what the properties were, but it did glow in the dark and that was tight.

I decided it was time to go.  I don’t know why.  I guess I was getting a weird vibe.

“This path will take you to the town,” he said, in the last conversation we ever had.  “Around the midpoint in your journey, you’ll see a palace.  It’s impossible to miss.”

“Cool.”

“Avoid it!  Do not enter its gates, even if they open for you.  Those who enter, it’s said, never leave.”

“Is it a necessary part of the walk?”

“No.”

“Okay, then this should be very easy.”

“It is said that you will be tempted.  I always am.  I learned to gain the strength to walk around it, but it was incredibly difficult.  You need to have resolve, and discipline.  If you walk beyond those gates, you will not be saved.”

“K.”

I put the red stone in my backpack and left.  Walking past this palace did not sound like it would be hard at all.  Once I reached the town, I figured, things would start to fall into place.

I was wrong.  Not two hours later, I would see the gates open and walk right in.
