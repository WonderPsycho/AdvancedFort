Hey, you clicked the readme file! Good for you.

To install, simply extract anywhere you wish. Your generated language file will be in the Bin folder once it's done.


That said, this program takes a bit of explanation.

First, it'll ask you for a language name. Simple, right? DO NOT name it "DWARF", "ELF", "HUMAN", "SYM", or "GOBLIN". Caps or otherwise. Or any other language that you already have in a mod. This will end badly, as it will overwrite anything you already have.

Second is the tough part. It'll ask you for a few fake words to "grow" your language from. What you should do is exactly what it tells you, and READ THE INSTRUCTIONS. If you're reading this, I assume you already have... If it wasn't clear enough, here you go.

AT LEAST one word must start with a vowel, and AT LEAST one word must end with a vowel. The same goes for consonants. Therefore, if you put in APPLE (two vowels) and CAR (two consonants), you're good to go. But don't use those unless you're trying for a language like that.
Here's an example of a language:
Abacus,kalamazoo,mosquito,ridiculous,hello,talvieno,braincells,toady,avatar,bay,twelve

This would actually be enough to grow a whole language from. There are a few things to note.

 - Word lists with more consonants than vowels are likely to gen languages with more consonants than vowels, and vice versa.
 - Word lists with mostly words that start with consonants and end with vowels will gen languages like that.
 - Word lists with abnormally long words (supercalifredulisticexpialidocious) will gen languages with annoyingly long words.
 - Words that are longer in english will also be longer in your language. For example, "AWE_INSPIRING" will ALWAYS be a long word. This is to simulate how often-used words are shorter than rarely-used ones, in any given real-life language.

To sum it up... your language will be as close to what you put in as possible, and still resemble a real-world language.


ONLY USE STANDARD ENGLISH LETTERS! I can't stress this enough. Using non-standard english letters, like letters with dipthongs or accents, will either A. Crash the program, or B. spit out some really weird stuff. When I finally save up enough for a new computer, I'll rewrite the whole thing in C++ and you won't have these issues.

Three other characters are permitted, these being spaces, apostrophes, and dash lines (-). Be aware that languages with these may not generate exactly how you expect them to. I've been careful to make it as accurate as possible, however.


********SYMBOLS********
DFLangCreate will generate "word roots" for each symbol, and words with that symbol will gain a special prefix or suffix. If "anu-" is the root for "DOMESTIC", then many domestic words will start with anu-, allowing you (if you know your language well enough) to tell what symbol a word (probably) is just by looking at it. It simulates a real-life language to an extent. I say "many" and "probably" because "anu" can also be artificially generated at random, and many words have more than one symbol. If a word has more than one symbol, it chooses the root at random from a list. You can't assign your own roots. DFLangCreate does it on its own.



********WHY YOU CAN'T OMIT ALL VOWEL/CONSONANT BEGINNINGS/ENDINGS********
DFLangCreate tries to keep the genned words looking like, well... words. The letter combinations are split up into three categories: beginnings, middle portions, and ends. If a beginning ends with a consonant, it tries to choose a middle portion that starts with a vowel, so you don't end up with something like this: "schwchsklchthaiaoourtchsch". No, instead, you end up with something like this: "tamagong". To be sure that you can ALWAYS end up with something like this, the DFLangCreate is very careful to tell you that you need vowel/consonant beginnings/endings. 

It would also be wise of you to make sure your words are as distinct as possible. Making a list like this: 
mola,marto,manatee,mailbox,ail,malpractice,martyr,mario,marina,mattress
Would ensure that almost every word would start with an "m", and DFLangCreate might run out of unique words, which would force it to make the words LONGER.

********LANGUAGE EXAMPLES********
All of the following are perfectly fine.

Abacus,kalamazoo,mosquito,ridiculous,hello,talvieno,braincells,toady,avatar,bay,twelve
	[T_WORD:ABBEY:anciebo]
	[T_WORD:ACE:rames]
	[T_WORD:ACT:hair]
	[T_WORD:AFTER:hecamo]
	[T_WORD:AGE:azidy]
	[T_WORD:AGELESS:hasqezidy]
	[T_WORD:ALE:kator]
	[T_WORD:ANCIENT:ricocetidy]
	[T_WORD:ANGEL:toadady]
	[T_WORD:ANGER:raluto]

moka,toka,ibika,stola,cloda,tiki,matoka,sabonura,obunachi,kalatanafon,roboto,alkaseltzer
	[T_WORD:ABBEY:olakora]
	[T_WORD:ACE:cluba]
	[T_WORD:ACT:mar]
	[T_WORD:AFTER:otika]
	[T_WORD:AGE:rucha]
	[T_WORD:AGELESS:salukecha]
	[T_WORD:ALE:idota]
	[T_WORD:ANCIENT:sabiricha]
	[T_WORD:ANGEL:molori]
	[T_WORD:ANGER:clekala]

schaffendar,veluuren,hausen,einer,rabulstein,scroder,scruff,jahol,scheider,scheina,robscach,mascharae,luffscharocharen,scacslarkoken
	[T_WORD:ABBEY:scekobun]
	[T_WORD:ACE:heran]
	[T_WORD:ACT:scar]
	[T_WORD:AFTER:ranorodae]
	[T_WORD:AGE:leson]
	[T_WORD:AGELESS:hokabscehadul]
	[T_WORD:ALE:rera]
	[T_WORD:ANCIENT:schebscekoson]
	[T_WORD:ANGEL:herosebun]
	[T_WORD:ANGER:markerora]


And, now that I've provided examples and (hopefully) explained everything... Enjoy!
 - Talvieno