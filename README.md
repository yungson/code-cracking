## Background

They is some extracts from a famous novel: CodedMessage.txt, which is encrypted using a simple substitution code e.g. “a/A” might stand for “m/M”; “b/B” might stand for “f/F” and The substitution is the same for the entire message. 

This project tries to use MCMC(Markov chain Monte Carlo) method and reference table of pairwise letter frequency extracted from 7 novels in file LetterPairFreqFrom7Novels.txt to decode the coded message.

see the code details at [code_cracking.Rmd](code_cracking.Rmd)

## The coded message

```
Gzo uclfg gcpo C qhcs okof te Gollk Qoeetb zo rhf slvem ce h LtqqfLtkio Fcqxol Rlhcgz tvgfcso gzo gollhio tu Gzo Sheiolf. Gzo ahlmced qtg hggoesheg zhs yltvdzg gzo ihl tvg hes zo rhf fgcqq ztqsced gzo sttl taoe yoihvfo Gollk Qoeetbf qoug uttg rhf fgcqq shedqced tvgfcso, hf cu zo zhs utldtggoe zo zhs teo. Zo zhs h ktvedqttmced uhio yvg zcf zhcl rhf yteo rzcgo. Ktv itvqs goqq yk zcf okof gzhg zo rhf aqhfgolos gt gzo zhclqceo, yvg tgzolrcfo zo qttmos qcmo hek tgzol ecio ktved dvk ce h sceeol jhimog rzt zhs yooe faoesced gtt pviz pteok ce h jtceg gzhg obcfgf utl gzhg avlatfo hes utl et tgzol. Gzolo rhf h dclq yofcso zcp. Zol zhcl rhf h qtxoqk fzhso tu shlm los hes fzo zhs h scfgheg fpcqo te zol qcaf hes txol zol fztvqsolf fzo zhs h yqvo pcem gzhg hqptfg phso gzo LtqqfLtkio qttm qcmo jvfg hetgzol hvgtptycqo. Cg scseg wvcgo. Etgzced ihe. Gzo hggoesheg rhf gzo vfvhq zhqugtvdz izhlhigol ce h rzcgo ithg rcgz gzo ehpo tu gzo lofghvlheg fgcgizos hiltff gzo ulteg tu cg ce los. Zo rhf doggced uos va. "Qttm, pcfgol," zo fhcs rcgz he osdo gt zcf xtcio, "rtvqs ktv pces h rztqo qtg avqqced ktvl qod cegt gzo ihl ft C ihe mces tu fzvg gzo sttl Tl fztvqs C taoe cg hqq gzo rhk ft ktv ihe uhqq tvg" Gzo dclq dhxo zcp h qttm rzciz tvdzg gt zhxo fgvim hg qohfg utvl ceizof tvg tu zcf yhim. Cg scseg ytgzol zcp oetvdz gt dcxo zcp gzo fzhmof. Hg Gzo Sheiolf gzok dog gzo ftlg tu aotaqo gzhg scfcqqvfcte ktv hytvg rzhg h qtg tu dtquced pteok ihe st utl gzo aolftehqcgk. H qtrfrved utlocde faoosfgol rcgz et gta slcugos cegt gzo ahlmced qtg hes h phe dtg tvg tu cg hes vfos gzo shfz qcdzgol te h qted icdhloggo. Zo rhf rohlced h avqqtxol izoim fzclg, koqqtr fqhimf, hes lcsced yttgf. Zo fgltqqos tuu glhcqced iqtvsf tu ceioefo, etg oxoe ytgzolced gt qttm gtrhlsf gzo LtqqfLtkio. Zo altyhyqk gztvdzg cg rhf itlek. Hg gzo uttg tu gzo fgoaf va gt gzo gollhio zo ahvfos gt fgcim h ptetiqo ce zcf oko. Gzo dclq fhcs rcgz h ecio yvlfg tu izhlp: "C zhxo h rtesoluvq csoh, shlqced. Rzk steg ro jvfg ghmo h ihy gt ktvl aqhio hes dog ktvl itexolgcyqo tvg Cgf fviz h rtesoluvq ecdzg utl h lve va gzo ithfg gt Ptegoicgt. C metr ftpo aotaqo gzolo rzt hlo gzltrced h sheio hltves gzo attq." Gzo rzcgozhclos qhs fhcs atqcgoqk: "Hruvqqk ftllk, yvg C steg zhxo cg hek ptlo. C rhf itpaoqqos gt foqq cg." Ultp zcf xtcio hes hlgcivqhgcte ktv rtvqseg zhxo metre zo zhs zhs hekgzced fgltedol gzhe tlhedo jvcio gt slcem. "Ftqs cg, shlqced Ztr st ktv pohe" Fzo fqcs hrhk ultp zcp hqted gzo fohg yvg zol xtcio fqcs hrhk h qtg uhlgzol gzhe gzhg. "C pohe C zhs gt," zo fhcs. "Utl ohgced pteok." "Tz, C foo." H fqcio tu favptec rtvqseg zhxo poqgos te zol etr. Gzo hggoesheg zhs gzo rzcgozhclos ytk lcdzg rzolo zo itvqs lohiz zcp  ce h qtrceitpo ylhimog. "Qttm, yvfgol," zo fhcs, "Cxo dtg gt avg h ihl hrhk. Foo ktv ftpo ptlo ftpo tgzol gcpophkyo." Zo qog gzo sttl frced taoe. Gzo slvem altpagqk fqcs tuu gzo fohg hes qhesos te gzo yqhimgta te gzo fohg tu zcf ahegf. Ft C roeg txol hes sltaaos pk ecimoq. C dvoff cgf hqrhkf h pcfghmo gt cegoluolo rcgz h slvem. Oxoe cu zo metrf hes qcmof ktv zo cf hqrhkf qchyqo gt zhvq tuu hes atmo ktv ce gzo googz. C dtg zcp vesol gzo hlpf hes dtg zcp va te zcf uoog. "Gzhem ktv ft xolk pviz," zo fhcs atqcgoqk. Gzo dclq fqcs vesol gzo rzooq. "Zo dogf ft dtsshp Oedqcfz rzoe zof qthsos," fzo fhcs ce h fghceqofffgooq xtcio. "Gzhemf utl ihgizced zcp." "Cqq dog zcp ce gzo yhim tu gzo ihl," C fhcs. "Cp gollcyqk ftllk. Cp qhgo utl he oedhdopoeg." Fzo qog gzo iqvgiz ce hes gzo Ltqqf fghlgos gt dqcso. "Zof jvfg h qtfg std," fzo hssos rcgz h ittq fpcqo. "Aolzhaf ktv ihe uces h ztpo utl zcp. Zof ztvfoyltmoe  ptlo tl qoff." Hes gzo Ltqqf gcimos stre gzo oeglheio slcxorhk tegt Fvefog Ytvqoxhls, phso h lcdzg gvle, hes rhf dteo. C rhf qttmced hugol zol rzoe gzo hggoesheg ihpo yhim. Hes C rhf fgcqq ztqsced gzo phe va hes zo rhf etr ftves hfqooa. "Roqq, gzhgf teo rhk tu stced cg," C gtqs gzo rzcgo ithg. "Fvlo,"  zo fhcs ikecihqqk. "Rzk rhfgo cg te h qvfz Gzop ivlxof hes hqq." "Ktv metr zcp" "C zohls gzo shpo ihqq zcp Gollk. Tgzolrcfo C steg metr zcp ultp h itrf ihyttfo. Yvg C teqk yooe zolo grt roomf." "Dog pk ihl, rcqq ktv" C dhxo zcp gzo gcimog. Yk gzo gcpo zo yltvdzg pk Tqsf txol C uoqg hf cu C rhf ztqsced va h fhim tu qohs. Gzo rzcgo ithg zoqaos po dog zcp cegt gzo ulteg fohg. Gzo ivfgtpol taoeos he oko hes gzhemos vf hes roeg gt fqooa hdhce. "Zof gzo atqcgofg slvem C oxol pog," C fhcs gt gzo rzcgo ithg. "Gzok itpo hqq fcnof hes fzhaof hes hqq mcesf tu pheeolf," zo fhcs. "Hes gzoklo hqq yvpf. Qttmf qcmo gzcf teo zhs h aqhfgci jty teo gcpo." "Kohz." C dhxo zcp h stqqhl hes zo gzhemos po. Zo rhf lcdzg hytvg gzo aqhfgci jty. Gzo lcdzg fcso tu pk eor ulcoesf uhio rhf ultnoe hes rzcgcfz hes fohpos rcgz gzce uceo fihlf. Gzo fmce zhs h dqtffk qttm hqted gzo fihlf. H aqhfgci jty hes h aloggk slhfgci teo. "Rzhgizh hcp gt st rcgz zcp" "Ghmo zcp ztpo hes ftyol zcp va oetvdz gt goqq po rzolo zo qcxof." Gzo rzcgo ithg dlceeos hg po. "Tmhk, fvimol. Cu cg rhf po, Cs jvfg slta zcp ce gzo dvggol hes mooa dtced. Gzop yttno ztvesf jvfg phmo h phe h qtg tu gltvyqo utl et uve. C dtg h azcqtftazk hytvg gzop gzcedf. Gzo rhk gzo itpaogcgcte cf etrhshkf h dvk zhf gt fhxo zcf fgloedgz gt altgoig zcffoqu ce gzo iqceizof." "C ihe foo ktvxo phso h ycd fviioff tvg tu cg," C fhcs. Zo qttmos avnnqos hes gzoe zo fghlgos gt dog phs, yvg yk gzhg gcpo C rhf ce gzo ihl hes ptxced. Zo rhf ahlgqk lcdzg tu itvlfo. Gollk Qoeetb phso po aqoegk tu gltvyqo. Yvg hugol hqq gzhgf pk qceo tu rtlm.
```


## We cracked the codes, Amazing!
```
the  first  time  i  laid  eyes  on  terry  lennox  he
was  drunk  in  a  rollsroyce  silver  wraith  outside  the  terrace
of  the  dancers.  the  parking  lot  attendant  had  brought  the
car  out  and  he  was  still  holding  the  door  open
because  terry  lennoxs  left  foot  was  still  dangling  outside,  as
if  he  had  forgotten  he  had  one.  he  had  a
younglooking  face  but  his  hair  was  bone  white.  you  could
tell  by  his  eyes  that  he  was  plastered  to  the
hairline,  but  otherwise  he  looked  like  any  other  nice  young
guy  in  a  dinner  jacket  who  had  been  spending  too
much  money  in  a  joint  that  exists  for  that  purpose
and  for  no  other.  there  was  a  girl  beside  him.
her  hair  was  a  lovely  shade  of  dark  red  and
she  had  a  distant  smile  on  her  lips  and  over
her  shoulders  she  had  a  blue  mink  that  almost  made
the  rollsroyce  look  like  just  another  automobile.  it  didnt  quite.
nothing  can.  the  attendant  was  the  usual  halftough  character  in
a  white  coat  with  the  name  of  the  restaurant  stitched
across  the  front  of  it  in  red.  he  was  getting
fed  up.  "look,  mister,"  he  said  with  an  edge  to
his  voice,  "would  you  mind  a  whole  lot  pulling  your
leg  into  the  car  so  i  can  kind  of  shut
the  door  or  should  i  open  it  all  the  way
so  you  can  fall  out"  the  girl  gave  him  a
look  which  ought  to  have  stuck  at  least  four  inches
out  of  his  back.  it  didnt  bother  him  enough  to
give  him  the  shakes.  at  the  dancers  they  get  the
sort  of  people  that  disillusion  you  about  what  a  lot
of  golfing  money  can  do  for  the  personality.  a  lowswung
foreign  speedster  with  no  top  drifted  into  the  parking  lot
and  a  man  got  out  of  it  and  used  the
dash  lighter  on  a  long  cigarette.  he  was  wearing  a
pullover  check  shirt,  yellow  slacks,  and  riding  boots.  he  strolled
off  trailing  clouds  of  incense,  not  even  bothering  to  look
towards  the  rollsroyce.  he  probably  thought  it  was  corny.  at
the  foot  of  the  steps  up  to  the  terrace  he
paused  to  stick  a  monocle  in  his  eye.  the  girl
said  with  a  nice  burst  of  charm:  "i  have  a
wonderful  idea,  darling.  why  dont  we  just  take  a  cab
to  your  place  and  get  your  convertible  out  its  such
a  wonderful  night  for  a  run  up  the  coast  to
montecito.  i  know  some  people  there  who  are  throwing  a
dance  around  the  pool."  the  whitehaired  lad  said  politely:  "awfully
sorry,  but  i  dont  have  it  any  more.  i  was
compelled  to  sell  it."  from  his  voice  and  articulation  you
wouldnt  have  known  he  had  had  anything  stronger  than  orange
juice  to  drink.  "sold  it,  darling  how  do  you  mean"
she  slid  away  from  him  along  the  seat  but  her
voice  slid  away  a  lot  farther  than  that.  "i  mean
i  had  to,"  he  said.  "for  eating  money."  "oh,  i
see."  a  slice  of  spumoni  wouldnt  have  melted  on  her
now.  the  attendant  had  the  whitehaired  boy  right  where  he
could  reach  him    in  a  lowincome  bracket.  "look,  buster,"
he  said,  "ive  got  to  put  a  car  away.  see
you  some  more  some  other  timemaybe."  he  let  the  door
swing  open.  the  drunk  promptly  slid  off  the  seat  and
landed  on  the  blacktop  on  the  seat  of  his  pants.
so  i  went  over  and  dropped  my  nickel.  i  guess
its  always  a  mistake  to  interfere  with  a  drunk.  even
if  he  knows  and  likes  you  he  is  always  liable
to  haul  off  and  poke  you  in  the  teeth.  i
got  him  under  the  arms  and  got  him  up  on
his  feet.  "thank  you  so  very  much,"  he  said  politely.
the  girl  slid  under  the  wheel.  "he  gets  so  goddam
english  when  hes  loaded,"  she  said  in  a  stainlesssteel  voice.
"thanks  for  catching  him."  "ill  get  him  in  the  back
of  the  car,"  i  said.  "im  terribly  sorry.  im  late
for  an  engagement."  she  let  the  clutch  in  and  the
rolls  started  to  glide.  "hes  just  a  lost  dog,"  she
added  with  a  cool  smile.  "perhaps  you  can  find  a
home  for  him.  hes  housebroken    more  or  less."  and
the  rolls  ticked  down  the  entrance  driveway  onto  sunset  boulevard,
made  a  right  turn,  and  was  gone.  i  was  looking
after  her  when  the  attendant  came  back.  and  i  was
still  holding  the  man  up  and  he  was  now  sound
asleep.  "well,  thats  one  way  of  doing  it,"  i  told
the  white  coat.  "sure,"    he  said  cynically.  "why  waste
it  on  a  lush  them  curves  and  all."  "you  know
him"  "i  heard  the  dame  call  him  terry.  otherwise  i
dont  know  him  from  a  cows  caboose.  but  i  only
been  here  two  weeks."  "get  my  car,  will  you"  i
gave  him  the  ticket.  by  the  time  he  brought  my
olds  over  i  felt  as  if  i  was  holding  up
a  sack  of  lead.  the  white  coat  helped  me  get
him  into  the  front  seat.  the  customer  opened  an  eye
and  thanked  us  and  went  to  sleep  again.  "hes  the
politest  drunk  i  ever  met,"  i  said  to  the  white
coat.  "they  come  all  sizes  and  shapes  and  all  kinds
of  manners,"  he  said.  "and  theyre  all  bums.  looks  like
this  one  had  a  plastic  job  one  time."  "yeah."  i
gave  him  a  dollar  and  he  thanked  me.  he  was
right  about  the  plastic  job.  the  right  side  of  my
new  friends  face  was  frozen  and  whitish  and  seamed  with
thin  fine  scars.  the  skin  had  a  glossy  look  along
the  scars.  a  plastic  job  and  a  pretty  drastic  one.
"whatcha  aim  to  do  with  him"  "take  him  home  and
sober  him  up  enough  to  tell  me  where  he  lives."
the  white  coat  grinned  at  me.  "okay,  sucker.  if  it
was  me,  id  just  drop  him  in  the  gutter  and
keep  going.  them  booze  hounds  just  make  a  man  a
lot  of  trouble  for  no  fun.  i  got  a  philosophy
about  them  things.  the  way  the  competition  is  nowadays  a
guy  has  to  save  his  strength  to  protect  hisself  in
the  clinches."  "i  can  see  youve  made  a  big  success
out  of  it,"  i  said.  he  looked  puzzled  and  then
he  started  to  get  mad,  but  by  that  time  i
was  in  the  car  and  moving.  he  was  partly  right
of  course.  terry  lennox  made  me  plenty  of  trouble.  but
after  all  thats  my  line  of  work.
```
