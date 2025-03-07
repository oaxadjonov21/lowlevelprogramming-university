DIQQAT 1: Iltimos, ushbu sahifadagi kontentni blogingizga ko'chirmang. Siz bu sahifani ulashishingiz mumkin, ammo, iltimos, uni asl havolasi (link) bilan ulashing. Bu bizning yaxshi dokument hamda ochiq manbali loyihalar egalari (avtor) uchun bo'lgan hurmatimizdir.

DIQQAT 2: Iltimos, shunga e'tibor bering-ki, hozirda quyi-daraja dasturlashi trendda emas va bunday dasturchini ishga olayotgan kompaniyalar ko'p emas. Menga ham ish topish qiyinlashib bormoqda.
Agar Siz hali professional karyerangizni boshlamagan bo'lsangiz, Sizga boshqa yo'nalishlarni ko'rib chiqshingizni maslahat bergan bo'lardim.

DIQQAT 3: Agar Siz tezroq boshlashni istasangiz, "Qanday boshlash kerak?" bo'limiga o'ting.

* [Quyi-daraja Dasturlashi Universiteti](#quyi-daraja-dasturlashi-universiteti)
	* [Bu o'zi nima?](#bu-o'zi-nima)
	* [Quyi Daraja (Low Level) nima?](#quyi-daraja-(low-level)-nima)
	* [Nazariya](#nazariya)
	* [Tillar](#tillar)
		* [Assembly](#assembly)
		* [C dasturlash tili](#c-dasturlash-tili)
		* [Rust dasturlash tili](#rust-dasturlash-tili)
	* [Tatbiqlar (Applications)](#tatbiqlar)
		* [Hardware va Firware](#hardware-va-firmware)
		* [Linux kerneli va qurilmalar drayverlari](#linux-kerneli-va-qurilmalar-drayverlari)
			* [Qo'shimcha adabiyolar](#qo'shimcha-adabiyotlar)
		* [Boshqa tatbiqlar](#boshqa-tatbiqlar)
	* [Quyi-daraja dasturlashining kelajagi](#quyi-daraja-dasturlashi-kelajagi)
	* [Qanday boshlash kerak?](#qanday-boshlash-kerak)
* [Tarjimalar](#tarjimalar)
* [Men kimman?](#men-kimman)

# Quyi-daraja Dasturlashi Universiteti

## Bu o'zi nima?

Men [Google Intervyu Universitetigoogle-interview-university](https://github.com/jwasham/coding-interview-university)dan ilhomlanganman. Bu mahorat/bilimlar avvalgiga nisbatan hozir kamyob bo'lganligi uchun, men o'zimning tajribamni ulashmoqchiman hamda quyi-daraja dasturchisi bo'lishdagi yo'lni ko'rsatmoqchiman. Shuningdek, ko'p student va yangi boshlovchilar mendan qanday qilib quyi-daraja dasturchisi va Linux kerneli muhandislari bo'lish haqi ko'p so'rashadi.

Bu sahifa hamma havola/kitob/kurslarni o'z ichiga ololmaydi. Misol uchun, ushbu sahifada Arduino tanishtirilgan bo'lsada, bu yerda u va embedded tizimlar haqida chuqur ma'lumot yo'q.  Siz o'zingiz mustaqil chuqurroq o'rganishingiz kerak. Sizda boshlash uchun "Arduino" kalit so'zi bor. Demak, Sizning keyingi qadamlaringiz havolalar va bepul kitoblarni yig'ib yurish emas, balki "Arduino" deb Google'dan qidirishingiz, [Arduino] to'plam sotib olishingiz, va o'zingiz uchun nimadur qilishingiz bo'lishi mumkin. Iltimos bu sahifa yangi boshlovchilar uchun yo'riqnoma ekanligini unutmang.

Quyi-daraja dasturlashi Kompyuter Fanining (Computer Science) bir qismidir.
Umuman olganda, birinchi o'rinda Kompyuter Fani (Computer Science) bo'yicha bilim olinsa afzalroq bo'lar edi.
* [Kompyuter Fanini mustaqil va bepul o'rganish uchun yo'riqnoma (ingliz tilida)](ttps://github.com/ossu/computer-science)


## Quyi-daraja (low-level) nima?

Men quyi-daraja dasturlashini C va assembly kabi quyi-daraja dasturlash tillari ishlatiladigan va mashinaga (kompyuter) yaqin bo'lgan dasturlash deb tasniflayman. Bu yuqori-darajadagi, odatda foydalanuvchi maydoni dasturlarida (user-space applications) namoyon bo'ladigan va yuqori-darajali dasturlash tillari (Python, Java kabilar) ishlatilinadigan dasturlashga qarama qarshidir.
* [Wikipedia: Quyi-daraja dasturlash tili (ingliz tilida)](https://en.wikipedia.org/wiki/Low-level_programming_language)

Ha, tizim dasturlashi (systems programming) quyi-daraja dasturlashiga yaqin tushuncha. Bu sahifa tizim dasturlashida bo'lmagan hardware dizayni va firmware'ni rivojlantirishni o'z ichiga oladi.
- [Wikipedia: System programming](https://en.wikipedia.org/wiki/System_programming)

Nihoyat, bu sahifa hardware qismlaridan tortib Linux kerneligacha bo'lga mavzularni o'z ichiga oladi. Bu turli xil qatlamlarning (layers) keng  ko'lamidir. Bir sahifalik dokument hech qachon barcha qatlarmlarning detallarini qamrab ololmaydi. Shuning uchun buning asosiy maqsadi quyi-daraja dasturlashi uchun boshlang'ich nuqta bo'lib xizmat qilishdir.

## Nazariya

Quyi-daraja dasturlashiga asosiy tayanch nazariyalar ushbular hisoblanadi:
* Kompyuter Arxitetkturasi
* Operatsion Tizimlar

Menimcha nazariyani o'rganishning eng zo'r yo'li bu kursdir. Kitoblarni o'qish ham yomon yo'l emas-u, lekin juda ko'p vaqt va mehnat talab qiladi. Siz ko'plab yaxshi kurslar (classes) va onlayn universitelarni topa olasiz. Misol uchun, Coursera.org va edx.org.
Nazary bu nazariya. Siz kursda A+ olishingiz kerak deb o'ylamayman. Shunchaki asosiy g'oyani tushuning.
Siz bilimingiz/mahoratingizni tajriba orqali yaxshilab borasiz.

Endi Sizga o'zim o'qigan bir necha kitoblarni tanishtirsam. Bu kitoblar odatda universitetlarda darsliklar sifatida ishlatiladi. Agar Sizning universitetingizda bu kitoblar ishlatilgan kurslar bo'lmasa, bir muncha vaqtingizni ularni o'qishga sarflasangiz arziydi.
* Kompyuter Arxitekturasi
	* Computer Architecture, Fifth Edition: A Quantitative Approach
	* Computer Systems: A Programmer's Perspective
	* Compuer Organization and Design, Fourth Edition: The Hardware/Software Interface
* Operatsion Tizimlar
	* The Magic Garden Explained: The Internals of UNIX System V Release 4 an Open Systems Design
	* The Design of the UNIX Operating System
	* Operating Systems: Internals and Design Principles by William Stallings
* Tavsiya etiladigan Kurslar
	* [CS401: Operating Systems from saylor.org](https://learn.saylor.org/course/view.php?id=94)
* Umumiy Dasturlash Mahorati (General Programming Skill)
	* [Structure and Interpretation of Computer Programs](https://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs)
		* Bu  kitob qanday qilib yaxshi dasturchi bo'lish haqida. Sizga nafaqat nazariya, balki amaliy ko'nikmalar (techniques) ham kerak. Sababi, dasturlash hunarmandchilikka o'xshaydi.
		* Agar Siz List/Scheme tillarini o'rgansangiz, boshqa tillarni tezda o'rgana olishingiz mumkin.
		* [Men bu kitobdagi mashqlarni 80% atrofida yechib chiqdim. Ularning har birini ishlab chiqishga arziydi deb o'ylayman.)](https://github.com/gurugio/sicp_exercise)
* Hardware Dizayni
	* O'zingizning 8086 Mikroprotsessor to'plamingizni (kit) yasang
		* Siz o'z o'zingizning Hardware platangizni qurmas ekansiz, jismoniy xotira biriktirilgan (memory-mapped) qurilma nima ekaligini bilolmaysiz.
		* Zamonaviy dastur protsessorlari (Application Processor, AP) judayam ko'p Intellectual Property (IP) bloklariga ega. Shu tufayli, Sizda CPU va periferik (CPU ichida bo'lmagan lekin u bilan ishlaydigan) qurilmalar qanday bog'langanini tushunish imkoniyati yo'q (juda juda mushkulligi uchun).
		* Siz o'zingizning 8086 to'plamingizni yasaganda esa, Sizda har bir periferik qurilmani jismoniy xotiraga o'zingiz joylashtira olishingiz (locate on the physical memory) imkoniyati bor. Hamda, HW qismlarining eng asosiylari (BUS, IRQ, Clock, Power[ Quvvat ta'minoti ] va h.k.) qanday ishlashini o'z ko'zlaringiz bilan ko'ra olasiz.
		* Men o'zimning 8086 to'plamimni universitetda yasaganman. U men olgan kurslarning eng qimmatlilaridan bo'lgan. O'zingizning HW to'plamingizni yaratishga urinib ko'ring. U eski va oddiyroq bo'lsa yanayam yaxsi bo'ladi, chunki ko'p narsani Siz o'zingiz qilishingiz kerak.
		* "8086 kit" deb Google'dan qidiring. Siz HW sxema, qismlari va qo'llanmalarni sotib olish uchun bir qancha veb-saytlar topishingiz mumkin.
Hozirda yaxshi kitoblarning son-sanog'ii yo'q. Men Sizni ko'p kitob o'qishingiz kerak demoqchi emas. Bitta kitobning o'qing, uni uqib o'qing. Qachonki bir nazariya o'rgansangiz, uni simulyatsiya qiladigan kodni yozing (implement). Bir narsani yasash (implementing) yuzta nazariya bilishdan afzaldir.

## Tillar

### Assembly

x86 va ARM'lardan birini tanlang. Ikkisini ham bilishingiz shart emas. Assembly tilini o'rganish muhim emas. Muhimi CPU va kompyuterni ichki qismlarini (internals) tushunishdir. Shuning uchun Siz eng so'nggi CPU'larning assembly'sini ishlatishingizga hojat yo'q. 8086 yoki Cortex-M ni tanlang.
**Eslatma:** Berilgan havolalardagi resurslar ingliz tilida
* [emu8086 bilan assembly dasturlash -- 8086 assembly programming with emu8086](https://github.com/gurugio/book_assembly_8086)
	* CPU va kompyuter arxitekturasining asosiy tushunchalari
	* C dasturlash tilining asosiy tushunchalari
* [64bit assembly dasturlash -- 64bit assembly programming (translation in progress)](https://github.com/gurugio/book_assembly_64bit)
	* zamonaviy CPU va kompyuter arxitekturasining boshlang'ich tushunchalari
	* C dasturlash tili kodini disassembllash (C kodini assembly'ga o'girish) va debugging (xatolarni tuzatish) boshlang'ich tushunchalari
	* _usbu kitobni tarjima qilishda yordam kerak_
* [linux-x64 uchun assembly'ni o'rganish -- Learning assembly for linux-x64](https://github.com/0xAX/asm)
	* NASM bilan sof 64-bit assembly dasturlash va GCC bilan ichki (inline) assembly
* [ARM Arxitekturasi Qo'llanmasi ---- ARM Architecture Reference Manual, 2nd Edition](http://www.mypearsonstore.ca/bookstore/arm-architecture-reference-manual-9780201737196)
	* ARM dasturlash bo'yicha to'liq qo'llanman
* Kompyuter Tuzilishi va Dizayni ---- Computer Organization and Design
	* [MIPS Varianti ---- MIPS Edition](https://www.amazon.ca/Computer-Organization-Design-MIPS-Interface/dp/0124077269/)
	* [ARM Varianti ---- ARM Edition](https://www.amazon.ca/Computer-Organization-Design-ARM-Interface/dp/0128017333/)
	* [RISC-V Varianti ---- RISC-V Edition](https://www.amazon.com/Computer-Organization-Design-RISC-V-Architecture/dp/0128122757)
	* Kompyuterning harbir qismlari butunlay qanday ishlashi haqida akademik kitoblar.
	* Kompyuter arxitekturasini tashkil qiladigan turli xil tushunchalarni chuqur tushuntiradi.
	* Ular ma'lum bir assembly tilida mohir bo'lishni istaydigan o'quvchilar uchun mo'ljallanmagan.
	* MIPS va ARM variantlar bir xil mavzularni qamrab oladi, ammo bu ish ikki xil arxitekturada olib boriladi.
	* Ikki variantda ham x86 arxitekturasiga oid namunalar bor

### C dasturlash tili

Bu yerda qisqa yo'l yo'q. Shunchaki butun kitobni o'qing va mashqlarni bajaring.

* [C Programming: A Modern Approach, 2nd Edition](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
* [The C Programming Language 2nd Edition](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=60R1D2CHBA8DHYT6JNMN)
* Modern C: Jens Gustedt. Modern C. Manning, 2019, 9781617295812. ffhal-02383654f
	* C'ning yangi standardi uchun
* [Parallel dasturlash Qiyinmi? Agar shunday bo'lgan, u haqida Siz nima qila olasiz?  ----  Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://www.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)
	* C dasturlash tilida synxronizatsiyani yasash (implementation)
	* Essential for large scale C programming (especially for kernel programming)
* [Loyihaga asoslangan C tutoriallar?  ----  C Project Based Tutorials?](https://www.reddit.com/r/C_Programming/comments/872rlt/c_project_based_tutorials/)
	* Agar Siz bir yo ikki C dasturlash tili haqida kitob tugatsangiz, Siz ALBATTA nimadur qilishingiz/yasashingiz kerak.
	* Xohlagan narsangizni qiling.
	* Dastlab, o'zingiznikini yasang va keyin boshqalarning kodi bilan solishtiring. O'zingizning kodingizni boshqalarniki bilan solishtirish judayam **muhim**. Siz mahoratingizning faqat boshqalaring kodini o'qiganingizda va yaxshiroq usullarni o'rganganingizdagina yaxshilay olasiz. **Kitoblar o'lik, kodlar esa tirik** (ya'ni kodlar yangilanib, hozirgi zamonga moslanib aktuallikni saqlab tursa, kitoblar bunday emas).
* [C va boshqa tillar asosida loyhalar (Build Your Own X) ----  C and other languages based projects](https://github.com/danistefanovic/build-your-own-x)
	* yanada qiziqarli loyihalar topish uchun
* [Michael Abrash'ning Black Book bilan Grafik Dasturlashi  ----  Michael Abrash’s Graphics Programming Black Book, Special Edition](http://www.jagregory.com/abrash-black-book/)
	* C va biroz x86 assembly bilan optimizatsiya qilish b'yicha qo'llanma
	* 8088dan boshlab to hozirgilargacha yoritilgan
	* Quyi-daraja grafik optimizatsiyaga alohida e'tibor qaratilgan
* [C'da Freymvork va plagin dizayni  ----  Framework and plugin design in C](https://github.com/gurugio/book_cprogramming)
	* Qanday qilib C'da katta masshtabli loyihalar uchun freymwork qurish va plugin yasash
	* Linux kerneli mabda kodini o'qish bo'yicha judayam boshlang'ich dasturlash tiplari (tips)

Agar Siz C dasturlashda ekspert bo'lishni istasangiz, https://leetcode.com/ ga kiring. Omad!

### Rust dasturlash tili

Men aminmanki, tizim dasturlash uchun keyingi til bu Rust bo'ladi.
Rust'ni o'rganishda nima qilganimning ro'yxatini beraman.

Linus Torvalds aytgan:  "Agar biror noodatiy holat bo'lib qolmasa, 6.1 Rust'da bo'ladi."  ----[Linus Torvalds said "Unless something odd happens, it [Rust] will make it into 6.1."](https://www.zdnet.com/article/linus-torvalds-rust-will-go-into-linux-6-1/)

- `EN` [The Rust Programming Language](https://doc.rust-lang.org/book/)
	- `UZ` [Rust Dasturlash Tili](https://doc.rust-lang.uz/book/) ---  tarjima [orzklv](https://github.com/orzklv) tomonidan olib borilmoqda
	- Bu kitob boshlash uchun g'oyatda zo'r bo'lsada, mashq va masalalar kam.
- [Rust misollar bilan  ----  Rust by Example](https://doc.rust-lang.org/rust-by-example/)
	- "Rust Dasturlash Tili" kitobini o'qiyotgan paytingizda mashq va masalalarni bu yerdan topsagiz bo'ladi.
	- Ammo bu yerda o'zingiz mustaqil bajaradigan mashqlar kam. Faqatgina ba'zi misollar "buni-qil" (do-this) mashqlarini o'z ichiga oladi va ular judayam sodda.
- [Rust Dasturlash  ----- Programming Rust, 2nd](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586i/) 
	- Chuqurroq kirish. Lekin baribir misollar va mashqlar kam
- [Exercism](https://exercism.org/tracks/rust)
	- Rust'ning individual xususiyatlari bo'yicha yaxshi mashqlar.
	- Mentorlar bu ustida faol ishlayabdimi yo'qmi aniq bilmayman-u, lekin o'zingizning yechimingizni boshqalarniki bilan solishtirish yetarli bo'lishi kerak.
		- O'z yechimingizni jo'natganingizdna so'ng boshqalarning yechimlarnig "Community solutions" bo'limidan (Exercism V3'dan boshlab) ko'ra olasiz.
		- Ko'plab oson darajadagi mashqlar `map/filter/any` kabi funksional xususiyatlar bo'yichadir.
- [Oson Rust ---- Easy rust](https://dhghomon.github.io/easy_rust/)
	- Oson Ingliz tilida yozilgan kitob.
	- YouTube materiallari bilan: https://www.youtube.com/playlist?list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk
- [Let's get rusty](https://www.youtube.com/c/LetsGetRusty)
	- Rust bo'yicha YouTube'ga kurs qo'yuvchilar ko'p. Menga esa shu kurs judayam yoqdi.
	- U Rust bo'yicha eng so'nngi yangiliklarni joylab kelayotgan edi. Obuna bo'lishga arziydi.
- [Linux uchun Rust ---- Rust for Linux](https://github.com/Rust-for-Linux)
	- Na'munaviy manba kodlarni kuzating va Rust qanday qilib Linux kerneliga kirib kelganinig tekshiring.
- [(Ish davom etmoqda) Rustda Linux qurilma drayverlari  ----  (Work In Progress) Linux Device Drivers in Rust](https://github.com/gurugio/rust-for-linux)
	- "Linux device drivers" kitobidagi na'munalarni Rustda yasalishi.

## Tatbiqlar

### Hardware va Firmware

Agar siz embedded tizimlar muhandisi bo'lishni istasangiz, eng oxirgi  ARM chipsetidan (mikrosxemalar to'plami) boshlagandan ko'ra oddiy hardware to'plamidan boshlash eng yaxshi yo'ldir.

* [Arduino Start Kit](https://www.arduino.cc/)
	* Arduinolarning ko'p versiyalari bor. Ammo ulardan eng sodda protessor (ATmega328P) va qo'llanma kitobiga ega bo'lgani "Arduino Start Kit" hisoblanadi
	* ATmega328Pda 8-bit yadro borligi uni raqamli sxemani (digital circuit) dizay qilishni va firmware (o'rnatilgan dasturiy ta'minot) rivojlantirishni boshlashda yaxshi boshlanish nuqtasi qiladi