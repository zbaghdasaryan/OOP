<h1>Օբյեկտ կողմնորոշված ծրագրավորում (ՕԿԾ)</h1> 

Օբյեկտ կողմնորոշված ծրագրավորում (ՕԿԾ) (անգլ.՝ Object-oriented programming (OOP)), ծրագրավորման մոտեցում, որի գաղափարական հիմք են հանդիսանում   Դաս (class) և Օբյեկտ (object)հասկացությունները.

Դաս ։ Դասը հանդիսանում է ելակետային կոդի տերմինալոգիայով նկարագրված, դեռ գոյություն չունեցող օբյեկտի մոդել։ Փաստացի այն նկարագրում է օբյեկտի կառուցվածքը, հանդիսանալով օբյեկտի ՛՛գծագիր՛՛։
Օբյեկտ ։ Հաշվողական համակարգի հասցեային տիրույթի իմաստային հատված է, որը առաջանում է դասի օրինակ(օբյեկտ) ստեղծելիս։

<h3>Պատմություն</h3>
ՕԿԾ-ն առաջացել է պրոցեդուրային ծրագրավորման գաղափարախոսության զարգացման արդյունքում, որտեղ տվյալները, և դրանք մշակող ֆունկցիաները ձևականորեն կապված չեն։

Առաջին ծրագրավորման լեզուն, որտեղ ներկայացված են եղել օբյեկտ կողմնորոշված ծրագրավորման սկզբունքները՝ Սիմուլան(simula) էր։ Իր հայտնվելու պահին (1967 թ.) այն առաջարկում էր հեղափոխական գաղափարներ՝ օբյեկտ, դաս, վիրտուալ մեթոդ և այլն։ Սակայն այս ամենը այնքան էլ մեծ իրարանցմամբ չընդուվեց ժամանակին։ Ամեն դեպքում Սիմուլայի գաղափարների մեծ մասը զարգացվեցին Ալան Քեյի և Դեն Ինգալսի կողմից՝ Սմոլթոկ(Smalltalk) լեզվի մեջ։ Վերջինս էլ դարձավ առաջին լայն տարածում գտած օբյեկտ-կողմնորոշված ծրագրավորման լեզուն։

Ներկայումս օբյեկտ-կողմնորոշված ծրագրավորման լեզուները ամենատարածվածն են աշխարհում, սակայն, օրինակ՝ օպերացիոն համակարգերի ծրագրավորման ոլորտում մինչև հիմա օգտագործվում են պրոցեդուրային մոտեցման սկզբունքները, որոնց կրիչն է լայն տարածում գտած Սի(C) լեզուն։


Գոյություն ունեն կոդերի երկու գրելաձևեր՝ պրոցեդուրային և օբյեկտ կողմնորոշված։ Պրոցեդուրային  եղանակի դեպքում կոդը դառնում է ավելի ծավալուն և դժվար հասկանալի։ Օբյեկտ կողմնորոշված ծրագրավորման դեպքում նման խնդիրներ չեն առաջանում։ Սա հանդիսանում է ՕԿԾ-ի առավելություններից մեկը` պրոցեդուրային եղանակով ծրագրավորման նկատմամբ։

Յուրաքանչյուր ոք, ով սկսում է օգտագործել ՕԿԾ, առաջինը պետք է սկսի օգտագործել օբյեկտային մտածելակերպ։ ՕԿԾ-ի ամենամեծ խնդիրը հանդիսանում է օբյեկտային մտածելակերպ սովորելը։ Առանց օբյեկտային մտածելակերպի հնարավոր չէ օգտագործել ՕԿԾ-ի ամբողջ ուժը և հզորությունը։

ՕԿԾ-ն հիմնված է կլասի (class) և օբյեկտի (object) հասկացությունների վրա։

Կլասը սահմանում է այն կառուցվածքն ու պահվածքը (տվյալներ և կոդ), որն օգտագործվելու է օբյեկտների կողմից։ Տրված կլասի յուրաքանչյուր օբյեկտ պարունակում է այդ կլասի կողմից սահմանված կառուցվածքը և պահվածքը։ Հենց այս պատճառով էլ, երբեմն, օբյեկտներին անվանում են կլասների նմուշներ։ Այսպիսով, կլասը հանդիսանում է տրամաբանական կառուցվածքը, իսկ օբյեկտը՝ նրա ֆիզիկական մարմնավորումը։

ՕԿԾ-ի երեք հիմնական հասկացություններն են՝ ինկապսուլացիա, ժառանգականություն և պոլիմորֆիզմ։ Երբեմն ՕԿԾ-ի հիմնական հասկացություններին են դասում նաև աբստրակցիան։ Այն պաշտոնապես չի համարվում ՕԿԾ-ի հիմնական գաղափարներից մեկը, սակայն ոչ պակաս կարևոր նշանակություն ունեցող գաղափար է։

<h2>Ինկապսուլացիա</h2> 
Ինկապսուլացիան իրենից ներկայացնում է մեխանիզմ, որը կապում է կոդը տվյալների հետ (որոնք այն օգտագործում է)՝ պաշտպանելով այդ երկուսը արտաքին ներգործությունից։ Ինկապսուլացիան կարելի է համարել պաշտպանիչ շերտ, որը պաշտպանում է կոդը և տվյալները այլ արտաքին կոդի կողմից շահագործումից։

<h2>Ժառանգականություն</h2>
Այն գործընթացը, որի ընթացքում մի օբյեկտը ստանում է մեկ այլ օբյեկտի հատկությունները, կոչվում է ժառանգականություն։ Ժառանգականության դեպքում մի օբյեկտը մասնակի կամ ամբողջությամբ ժառանգում է մեկ այլ օբյեկտի հատկությունները, և կարող է ունենալ իրեն բնորոշ հատկությունները։

<h2>Պոլիմորֆիզմ</h2> 
Պոլիմորֆիզմը հնարավորություն է տալիս օգտագործել նույն ինտերֆեյսը ընդհանուր դասի գործողությունների համար։ Յուրաքանչյուր գործողություն կախված է կոնկրետ իրադրությունից։

<h2>Աբստրակցիա</h2> 
Աբստրակցիան մի միջոց է, որով առանձնացվում են օբյեկտի կարևոր բնութագրերը, դիտարկումից դուրս թողնելով ոչ կարևորները։ Հետևաբար, աբստրակցիան հանդիսանում է բոլոր այդպիսի բնութագրերի համախումբ։

