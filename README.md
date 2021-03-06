<h1>Օբյեկտ կողմնորոշված ծրագրավորում (ՕԿԾ)</h1> (անգլ.՝ Object-oriented programming (OOP)) 

<h3>Պատմություն</h3>
<p align = "justify">
Գոյություն ունեն կոդերի երկու գրելաձևեր՝ պրոցեդուրային և օբյեկտ կողմնորոշված։ Պրոցեդուրային  եղանակի դեպքում կոդը դառնում է ավելի ծավալուն և դժվար հասկանալի։ Օբյեկտ կողմնորոշված ծրագրավորման դեպքում նման խնդիրներ չեն առաջանում։ Սա հանդիսանում է ՕԿԾ-ի առավելություններից մեկը` պրոցեդուրային եղանակով ծրագրավորման նկատմամբ։</br>
ՕԿԾ-ն առաջացել է պրոցեդուրային ծրագրավորման գաղափարախոսության զարգացման արդյունքում, որտեղ տվյալները, և դրանք մշակող ֆունկցիաները ձևականորեն կապված չեն։</br>
Առաջին ծրագրավորման լեզուն, որտեղ ներկայացված են եղել օբյեկտ կողմնորոշված ծրագրավորման սկզբունքները՝ Սիմուլան (Simula) էր։ Իր հայտնվելու պահին (1967թ.) այն առաջարկում էր հեղափոխական գաղափարներ՝ օբյեկտ, դաս, վիրտուալ մեթոդ և այլն։ Սակայն այս ամենը այնքան էլ մեծ իրարանցմամբ չընդուվեց ժամանակին։ Ամեն դեպքում Սիմուլայի գաղափարների մեծ մասը զարգացվեցին Ալան Քեյի և Դեն Ինգալսի կողմից՝ Սմոլթոկ (Smalltalk) լեզվի մեջ։ Վերջինս էլ դարձավ առաջին լայն տարածում գտած օբյեկտ-կողմնորոշված ծրագրավորման լեզուն։</br>
Ներկայումս օբյեկտ-կողմնորոշված ծրագրավորման լեզուները ամենատարածվածն են աշխարհում, սակայն, օրինակ՝ օպերացիոն համակարգերի ծրագրավորման ոլորտում մինչև հիմա օգտագործվում են պրոցեդուրային մոտեցման սկզբունքները, որոնց կրիչն է լայն տարածում գտած Սի (C) լեզուն։</br>

Օբյեկտ կողմնորոշված ծրագրավորումն գաղափարական հիմք են հանդիսանում Դաս (class) և Օբյեկտ (object) հասկացությունները.

<h5>Class</h5> Class-ը հանդիսանում է ելակետային կոդի տերմինալոգիայով նկարագրված, դեռ գոյություն չունեցող object-ի մոդել։ Փաստացի այն նկարագրում է object-ի կառուցվածքը, հանդիսանալով նրա «գծագիր»։ Տրված class-ի յուրաքանչյուր object պարունակում է այդ class-ի կողմից սահմանված կառուցվածքը և պահվածքը։ Հենց այս պատճառով էլ, երբեմն, օբյեկտներին անվանում են կլասների նմուշներ։ Այսպիսով, class-ը հանդիսանում է տրամաբանական կառուցվածքը, իսկ object-ը՝ նրա ֆիզիկական մարմնավորումը։

<h5>Object</h5> Հաշվողական համակարգի հասցեային տիրույթի իմաստային հատված է, որը առաջանում է calss-ի օրինակ (object) ստեղծելիս։</br>

ՕԿԾ-ի երեք հիմնական հասկացություններն են՝ ինկապսուլացիա, ժառանգականություն և պոլիմորֆիզմ։ Երբեմն ՕԿԾ-ի հիմնական հասկացություններին են դասում նաև աբստրակցիան։ Այն պաշտոնապես չի համարվում ՕԿԾ-ի հիմնական գաղափարներից մեկը, սակայն ոչ պակաս կարևոր նշանակություն ունեցող գաղափար է։

<h2>Ինկապսուլացիա</h2> 

ինկապսուլացիան իրենից ներկայացնում է մեխանիզմ, որը կապում է կոդը տվյալների հետ (որոնք այն օգտագործում է)՝ պաշտպանելով այդ երկուսը արտաքին ներգործությունից։ Ինկապսուլացիան կարելի է համարել պաշտպանիչ շերտ, որը պաշտպանում է կոդը և տվյալները այլ արտաքին կոդի կողմից շահագործումից։

Ինկապսուլացիայի օրինակ, իրական կյանքում, կարող է հանդիսանալ ավտոմեքենայի փոխանցման տուփը։ Վարորդը հասանելիություն չունի փոխանցման տուփում կատարվող գործողություններին։ Նա կարող է ազդեցություն ունենալ այդ համակարգի վրա միայն փոխանցման լծակի օգնությամբ։ Ավտոմատ փոխանցման տուփում կատարվող գործողությունները ինկապսուլացված են, այդ իսկ պատճառով յուրաքանչյուր արտադրող կարող է իրականցնել այդ գործողությունները յուրովի։

Նմանատիպ սկզբունք կարելի է կիրառել ծրագրավորման ոլորտում։ Ինկապսուլացված կոդի առավելությունը կայանում է նրանում, որ բոլորին հայտնի է, թե ինչպես հասանելիություն ստանալ այդ կոդին, և այն կարող են օգտագործել, առանց իմանալու, թե ինչպես է այն իրականացված։

Ինկապսուլացիայի հիմքը հանդիսանում է կլասը։ Կլասը ստեղծելիս հայտարարվում են կոդը և տվյալները, որոնք կազմում են այդ կլասը։ Այս տարրերը միասին կոչվում են կլասի անդամներ։ Կլասում հայտարարված տվյալները կոչվում են կլասի փոփոխական-անդամներ կամ հատկություններ (տարբեր ծրագրավորման լեզուներում դրանց տարբեր կերպ են անվանում), իսկ կոդը, որը ղեկավարում է այդ տվյալները՝ մեթոդներ կամ ֆունկցիաներ (կրկին այս տարբերությունը կախած է ծրագրավորման լեզուներից)։ Ճիշտ գրված ծրագրերում մեթոդները որոշում են, թե ինչպես են օգտագործվելու փոփոխական-անդամները։

Ինչպես արդեն նշեցի, ինկապսուլացիայի հիմքը հանդիսանում է կլասը, որում յուրաքանչյուր անդամ (մեթոդ կամ փոփոխական-անդամ) կարող է հայտարարվել բաց կամ փակ։ Բաց հանդիսանում են այն անդամները, որոնց կարող են կամ պետք է հասանելիություն ունենան արտաքին միջավայրի կոդերը։ Փակ անդամներն այն անդամներն են, որոնք հասանելի են միայն տվյալ կլասի անդամներին։ Հետևաբար յուրաքանչյուր այլ կոդ, որը չի հանդիսանում տվյալ կլասի անդամ՝ չի կարող հասանելիություն ունենալ կլասի փակ անդամներին։ Կլասի փակ անդամները կարող են հասանելի լինել կոդի այլ հատվածներին բաց անդամների միջոցով։ Դրա շնորհիվ բացառվում է արտաքին կոդի կողմից սխալ գործողությունների իրականացումը։ Դա, իհարկե, նշանակում է, որ բաց ինտերֆեյսը պետք է մանրակրկտորեն նախագծվի և չպետք է շատ բացահայտի կլասի ներքին կառուցվածքը։


<h2>Ժառանգականություն</h2>
Այն գործընթացը, որի ընթացքում մի օբյեկտը ստանում է մեկ այլ օբյեկտի հատկությունները, կոչվում է ժառանգականություն։ Ժառանգականության դեպքում մի օբյեկտը մասնակի կամ ամբողջությամբ ժառանգում է մեկ այլ օբյեկտի հատկությունները, և կարող է ունենալ իրեն բնորոշ հատկությունները։

<h2>Պոլիմորֆիզմ</h2> 
Ծրագրավորման լեզուներում և տիպերի տեսությունում պոլիմորֆիզմ (Հունարեն πολύς, պոլիս, "շատ" և μορφή, մորֆ, "ձև") կոչվում է տարբեր տեսակի տվյալները կարգավորելու ունակությունը։ Գոյություն ունեն մի քանի տեսակի պոլիմորֆիզմներ։ Երկու ամենատարբեր տեսակի պոլիմորֆիզմները 1967 թ.-ին նկարագրվել են Քրիսթոֆեր Սթրեչիի կողմից։ Մեկը հատուկ պոլիմորֆիզմն է (կամ ad hoc պոլիմորֆիզմ), մյուսը՝ պարամետրիկ պոլիմորֆիզմը։ Հակիրճ՝ հատուկ պոլիմորֆիզմը նկարագրվում է «նման ինտերֆեյսով շատ իրագործումներ» սկզբունքով, իսկ պարամետրիկը՝ «մեկ իրագործում ընդհանրացված ինտերֆեյսով» պրինցիպով։ Այլ կերպ ասած՝ պոլիմորֆիզմը նույն օբեկտը տարբեր միջավայրերում իրեն տարբեր կերպ դրսևորելու հատկությունն է:


<h2>Աբստրակցիա</h2> 
Աբստրակցիան մի միջոց է, որով առանձնացվում են օբյեկտի կարևոր բնութագրերը, դիտարկումից դուրս թողնելով ոչ կարևորները։ Հետևաբար, աբստրակցիան հանդիսանում է բոլոր այդպիսի բնութագրերի համախումբ։
</p>
