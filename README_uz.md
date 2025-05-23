**Men juda ko'p spam olayotganim uchun bu repozitoriyani vaqtinchalik read-only rejimiga o'tkazib qo'ydim.**

ESLATMA 1: Iltimos, ushbu sahifadagi kontentni blogingizga ko'chirmang. Siz bu sahifani ulashishingiz mumkin, ammo, iltimos, uni asl havolasi (link) bilan ulashing. Bu bizning yaxshi dokument hamda ochiq manbali loyihalar egalari (avtor) uchun bo'lgan odobimizdir.

ESLATMA 2: Iltimos, shunga e'tibor beringki, hozirda quyi-daraja dasturlashi trendda emas va bunday dasturchini ishga olayotgan kompaniyalar ko'p emas. Menga ham ish topish qiyinlashib bormoqda.
Agar Siz hali professional karyerangizni boshlamagan bo'lsangiz, Sizga boshqa yo'nalishlarni ko'rib chiqishingizni maslahat bergan bo'lardim.

ESLATMA 3: Agar Siz tezroq boshlashni istasangiz, "Qanday boshlash kerak?" bo'limiga o'ting.

* [Quyi-daraja Dasturlashi Universiteti](#quyi-daraja-dasturlashi-universiteti)
	* [Bu nima?](#bu--nima)
	* [Quyi Daraja (Low Level) nima?](#quyi-daraja-low-level-nima)
	* [Nazariya](#nazariya)
	* [Tillar](#tillar)
		* [Assembly](#assembly)
		* [C dasturlash tili](#c-dasturlash-tili)
		* [Rust dasturlash tili](#rust-dasturlash-tili)
	* [Qo'llanilish Sohalari](#Qo'llanilish Sohalari)
		* [Hardware va Firmware](#hardware-va-firmware)
		* [Linux kerneli va qurilmalar drayverlari](#linux-kerneli-va-qurilmalar-drayverlari)
			* [Qo'shimcha adabiyolar](#qo'shimcha-adabiyotlar)
		* [Boshqa tatbiqlar](#boshqa-tatbiqlar)
	* [Quyi-daraja dasturlashining kelajagi](#quyi-daraja-dasturlashi-kelajagi)
	* [Qanday boshlash kerak?](#qanday-boshlash-kerak)
* [Tarjimalar](#tarjimalar)
* [Men kimman?](#men-kimman)

# Quyi-daraja Dasturlashi Universiteti

## Bu nima?

Men [Google Intervyu Universiteti](https://github.com/jwasham/coding-interview-university)dan ilhomlanganman. Bu mahorat/bilimlar avvalgiga nisbatan hozir kamyob bo'lganligi uchun, men o'zimning tajribamni ulashmoqchiman hamda quyi-daraja dasturchisi bo'lishdagi yo'lni ko'rsatmoqchiman. Shuningdek, ko'p talaba va yangi boshlovchilar mendan qanday qilib quyi-daraja dasturchisi va Linux kerneli muhandislari bo'lish haqida ko'p so'rashadi.

Bu sahifa hamma havola/kitob/kurslarni o'z ichiga ololmaydi. Misol uchun, ushbu sahifada Arduino tanishtirilgan bo'lsada, bu yerda u va o'rnatilgan (**embedded**) tizimlar haqida chuqur ma'lumot yo'q.  Siz o'zingiz mustaqil chuqurroq o'rganishingiz kerak. Sizda boshlash uchun "Arduino" kalit so'zi bor. Demak, Sizning keyingi qadamlaringiz havolalar va bepul kitoblarni yig'ib yurish emas, balki "Arduino" deb Google'dan qidirishingiz, [Arduino] to'plam sotib olishingiz, va o'zingiz uchun nimadur qilishingiz bo'lishi mumkin. Iltimos bu sahifa **yangi boshlovchilar** uchun yo'riqnoma ekanligini unutmang.

Quyi-daraja dasturlashi Kompyuter Ta'limotining (keyingi o'rinlarda Computer Science) bir qismidir.
Umuman olganda, birinchi o'rinda Computer Science bo'yicha bilim olinsa afzalroq bo'lar edi.
* [Computer Science'ni mustaqil va bepul o'rganish uchun yo'riqnoma (ingliz tilida)](ttps://github.com/ossu/computer-science)


## Quyi-daraja (low-level) nima?

Men quyi-daraja dasturlashini C va assembly kabi quyi-daraja dasturlash tillari ishlatiladigan va mashinaga (kompyuter) yaqin bo'lgan dasturlash deb ta'riflayman. Bu esa yuqori-darajadagi, odatda foydalanuvchi maydoni dasturlarida (user-space applications) namoyon bo'ladigan va yuqori-darajali dasturlash tillari (Python, Java kabilar) ishlatilinadigan dasturlashga teskaridir.
* [Wikipedia: Quyi-daraja dasturlash tili (ingliz tilida)](https://en.wikipedia.org/wiki/Low-level_programming_language)

Ha, tizim dasturlashi (systems programming) quyi-daraja dasturlashiga yaqin tushuncha. Bu sahifa tizim dasturlashida bo'lmagan ***hardware*** dizayni va ***firmware***ni rivojlantirishni o'z ichiga oladi.
- [Wikipedia: System programming](https://en.wikipedia.org/wiki/System_programming)

Nihoyat, bu sahifa ***hardware*** qismlaridan tortib Linux kerneligacha bo'lga mavzularni o'z ichiga oladi. Bu turli xil qatlamlarning (layers) keng  qamrovidir. Bir sahifalik dokument hech qachon barcha qatlamlarni batafsil qamrab ololmaydi. Shuning uchun buning asosiy maqsadi quyi-daraja dasturlashi uchun **boshlang'ich nuqta** bo'lib xizmat qilishdir.

## Nazariya

Quyi-daraja dasturlashiga asosiy tayanch nazariy bilimlar ushbular hisoblanadi:
* Kompyuter Arxitekturasi
* Operatsion Tizimlar

Menimcha nazariyani o'rganishning eng yaxshi yo'li bu kurs olishdir. Kitoblarni o'qish ham yomon yo'l emas-u, lekin juda ko'p vaqt va mehnat talab qiladi. Siz onlayn universitetlardan ko'plab yaxshi kurslarni topa olasiz. Misol uchun, Coursera.org va edx.org.
Nazariya baribir nazariya. Siz kursda A+ olishingiz kerak deb o'ylamayman. Muhimi asosiy g'oyani tushuning.
Tajribangiz ortgani sari bilimingiz/mahoratingiz ham yaxshilanib boradi.

Endi Sizga o'zim o'qigan bir necha kitoblarni tanishtirsam. Bu kitoblar odatda universitetlarda darsliklar sifatida ishlatiladi. Agar Sizning universitetingizda bu kitoblar ishlatilgan kurslar bo'lmasa, vaqtingizning ma'lum bir qismini ularning mutolaasi bilan o'tkazsangiz arziydi.
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
		* Ushbu kitob yaxshi dasturchi bo'lish haqida. Sizga nafaqat nazariya, balki amaliy ko'nikmalar (techniques) ham kerak, chunki, dasturlash hunarmandchilikka o'xshaydi.
		* Agar Siz List/Scheme tillarini o'rgansangiz, boshqa tillarni tezda o'zlashtira olishingiz mumkin.
		* [Men bu kitobdagi mashqlarni 80% atrofida yechib chiqdim. Ularning har birini ishlab chiqishga arziydi deb o'ylayman.)](https://github.com/gurugio/sicp_exercise)
* Hardware Dizayni
	* O'zingizning 8086 Mikroprotsessor to'plamingizni (kit) yasang
		* Siz o'zingizning Hardware platangizni qurmas ekansiz, jismoniy xotira biriktirilgan (memory-mapped) qurilma nima ekaligini bilolmaysiz. ([physical memory mapped device](link))
		* Zamonaviy dastur protsessorlari (AP) judayam ko'p IP bloklariga ega, shuning uchun CPU yadrolari va periferik (CPU'ning bir qismi bo'lmagan) qurilmalar birga ishlash uchun qanday bog'langanini tushunishning deyarli imkoni yo'q.
		* O'zingizning 8086 to'plamingizni yasaganingizda esa, Sizda har bir periferik qurilmani jismoniy xotiraga o'zingiz joylashtirishingiz (locate on the physical memory) imkoniyati bor. Hamda, HW qismlarining eng asosiylari (BUS, IRQ, Clock, Power va h.k.) qanday ishlashini o'z ko'zlaringiz bilan ko'ra olasiz.
		* Men o'zimning 8086 to'plamimni universitetda yig'ganman. U men olgan kurslarning eng qimmatlilaridan biri edi. O'zingizning HW to'plamingizni yaratishga urinib ko'ring. U eski va oddiyroq bo'lsa yanayam yaxshi bo'ladi, chunki ko'p narsani Siz o'zingiz qilishingiz kerak (va shu tufayli ko'proq izlanib/or'ganishingiz kerak).
		* Google'dan "8086 kit" deb  qidirsangiz, HW sxema, qismlar va qo'llanmalarni sotib olish uchun bir qancha veb-saytlar topishingiz mumkin.

Hozirda yaxshi kitoblarning son-sanog'i yo'q. Men Sizni ko'p kitob o'qishingiz kerak demoqchi emasman. Aksincha, bitta kitobni e'tibor bilan o'qing. Qachonki bir nazariya o'rgansangiz, uni simulyatsiya qiluvchi kodni yozib ko'ring. Boshqacha aytganda, nazariyani **amaliyotda qo'llang**. **Bir narsani amalda qo'llash -- yuz xil nazariya bilishdan afzalroqdir.**

## Tillar

### Assembly

x86 va ARM arxitekturalaridan birini tanlang. Ikkisini ham bilish shart emas. Bu tanlovda ularning Assembly tilini bilishingiz muhim emas. Eng muhimi CPU va kompyuterni ichki qismlarini (internals) tushunishdir. Shuning uchun Siz eng so'nggi CPU'larning assembly'sini ishlatishingizga hojat yo'q. 8086 yoki Cortex-M ni tanlang.

**Eslatma:** Berilgan havolalardagi resurslar ingliz tilida
* [8086 assembly programming with emu8086](https://github.com/gurugio/book_assembly_8086)
	* CPU va kompyuter arxitekturasining boshlang'ich tushunchalari
	* C dasturlash tilining boshlang'ich tushunchalari
* [64bit assembly programming (translation in progress)](https://github.com/gurugio/book_assembly_64bit)
	* zamonaviy CPU va kompyuter arxitekturasining boshlang'ich tushunchalari
	* C dasturlash tili kodini disassembllash (C kodini assembly'ga o'girish) va debugging'ning (xatolarni tuzatish) boshlang'ich tushunchalari
	* _usbu kitobni tarjima qilishda yordam kerak_
* [Learning assembly for linux-x64](https://github.com/0xAX/asm)
	* NASM bilan sof 64-bit assembly dasturlash va GCC bilan ichki (inline) assembly
* [ARM Architecture Reference Manual, 2nd Edition](http://www.mypearsonstore.ca/bookstore/arm-architecture-reference-manual-9780201737196)
	* ARM dasturlash bo'yicha to'liq qo'llanma
* Kompyuter Tuzilishi va Dizayni ---- Computer Organization and Design
	* [MIPS Edition](https://www.amazon.ca/Computer-Organization-Design-MIPS-Interface/dp/0124077269/)
	* [ARM Edition](https://www.amazon.ca/Computer-Organization-Design-ARM-Interface/dp/0128017333/)
	* [RISC-V Edition](https://www.amazon.com/Computer-Organization-Design-RISC-V-Architecture/dp/0128122757)
	* Kompyuterning har bir qismlarini qanday ishlashini tubdan tushuntiruvchi akademik kitoblar.
	* Kompyuter arxitekturasini tashkil qiladigan turli xil tushunchalarni batafsil yoritadi.
	* Ular ma'lum bir assembly tilida mohir bo'lishni istaydigan o'quvchilar uchun mo'ljallanmagan.
	* MIPS va ARM nashrlar bir xil mavzularni qamrab oladi, ammo ikki xil arxitekturada asosida.
	* Ikki nashrda ham x86 arxitekturasiga oid namunalar bor

### C dasturlash tili

Bu yerda qisqa yo'l yo'q. Shunchaki butun kitobni o'qing va mashqlarni bajaring.

* [C Programming: A Modern Approach, 2nd Edition](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
* [The C Programming Language 2nd Edition](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=60R1D2CHBA8DHYT6JNMN)
* Modern C: Jens Gustedt. Modern C. Manning, 2019, 9781617295812. ffhal-02383654f
	* C'ning yangi standarti uchun
* [Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://www.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)
	* Noldan C dasturlash tilida synxronizatsiyani yasash
	* Katta masshtabbli C dasturlashda judayam muhim (ayniqsa kernel dasturlash)
* [C Project Based Tutorials?](https://www.reddit.com/r/C_Programming/comments/872rlt/c_project_based_tutorials/)
	* Agar Siz bir yo ikkita C dasturlash tili haqida kitob tugatsangiz, Siz ALBATTA nimadur qilishingiz/yasashingiz kerak.
	* Xohlagan narsangizni tanlang.
	* Dastlab, o'zingiznikini yasang va keyin boshqalarning kodi bilan solishtiring. O'zingizning kodingizni boshqalarniki bilan solishtirish judayam **muhim** ahamiyatga ega. Siz mahoratingizning faqat boshqalaring kodini o'qiganingizda va yaxshiroq usullarni o'rganganingizdagina yaxshilay olasiz. **Kitoblar jonsiz, kodlar esa jonli** (ya'ni kodlar yangilanib, hozirgi zamonga moslanib aktuallikni saqlab tursa, kitoblar bunday emas).
* [C and other languages based projects](https://github.com/danistefanovic/build-your-own-x)
	* yanada qiziqarli loyihalar topish uchun
* [Abrash’s Graphics Programming Black Book, Special Edition](http://www.jagregory.com/abrash-black-book/)
	* C va biroz x86 assembly bilan optimizatsiya qilish bo'yicha qo'llanma
	* 8088dan boshlab to hozirgilargacha yoritilgan
	* Quyi-daraja grafik optimizatsiyaga alohida e'tibor qaratilgan
* [Framework and plugin design in C](https://github.com/gurugio/book_cprogramming)
	* Qanday qilib C'da katta masshtabli loyihalar uchun freymwork qurish va plugin yasash
	* Linux kerneli manba kodini o'qish bo'yicha judayam boshlang'ich dasturlash maslahatlari (programming tips)

Agar Siz C dasturlashda ekspert bo'lishni istasangiz, https://leetcode.com/ ga kiring. Omad!

### Rust dasturlash tili

Mening ishonchim komilki, tizim dasturlashi uchun keyingi til Rust bo'ladi.
Rust'ni o'rganishda nima qilganimning ro'yxatini beraman.

[Linus Torvalds aytgan:  "Agar biror noodatiy holat bo'lib qolmasa, 6.1 Rust'da bo'ladi."](https://www.zdnet.com/article/linus-torvalds-rust-will-go-into-linux-6-1/)

- [The Rust Programming Language](https://doc.rust-lang.org/book/)
	- `UZ` [Rust Dasturlash Tili](https://doc.rust-lang.uz/book/) ---  tarjima [orzklv](https://github.com/orzklv) tomonidan olib borilmoqda
	- Bu kitob boshlash uchun g'oyatda zo'r bo'lsada, mashq va masalalar kam.
- [Rust misollar bilan  ----  Rust by Example](https://doc.rust-lang.org/rust-by-example/)
	- "Rust Dasturlash Tili" kitobini o'qiyotgan paytingizda mashq va masalalarni bu yerdan topsagiz bo'ladi.
	- Ammo bu yerda o'zingiz mustaqil bajaradigan mashqlar kam. Faqat ayrim misollar "buni-bajaring" (do-this) mashqlarini o'z ichiga oladi va ular judayam sodda.
- [Programming Rust, 2nd](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586i/) 
	- Chuqurroq kirish. Lekin baribir misollar va mashqlar kam.
- [Exercism](https://exercism.org/tracks/rust)
	- Rust'ning individual xususiyatlari bo'yicha yaxshi mashqlar.
	- Mentorlar faol ishlayabdimi yo'qmi aniq bilmayman-u, lekin o'zingizning yechimingizni boshqalarniki bilan solishtirish yetarli bo'lishi kerak.
		- O'z yechimingizni jo'natganingizdan so'ng boshqalarning yechimlarini "Community solutions" bo'limidan (Exercism V3'dan boshlab) ko'ra olasiz.
		- Ko'plab oson darajadagi mashqlar `map/filter/any` kabi funksional xususiyatlar bo'yichadir.
- [Easy rust](https://dhghomon.github.io/easy_rust/)
	- Oson Ingliz tilida yozilgan kitob.
	- YouTube materiallari bilan: https://www.youtube.com/playlist?list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk
- [Let's get rusty](https://www.youtube.com/c/LetsGetRusty)
	- Rust bo'yicha YouTube'ga kurs qo'yuvchilar ko'p. Menga esa shu kurs judayam yoqdi.
	- U Rust bo'yicha eng so'nngi yangiliklarni joylab kelayotgan edi. Obuna bo'lishga arziydi.
- [Rust for Linux](https://github.com/Rust-for-Linux)
	- Na'munaviy manba kodlarni kuzating va Rust qanday qilib Linux kerneliga kirib kelganinig tekshiring.
- [(Work In Progress) Linux Device Drivers in Rust](https://github.com/gurugio/rust-for-linux)
	- "Linux device drivers" kitobidagi na'munalarni Rustda yozilishi.

## Qo'llanilish sohalari

### Hardware va Firmware

Agar siz o'rnatilgan (embedded) tizimlar muhandisi bo'lishni istasangiz, eng oxirgi  ARM chipsetidan (mikrosxemalar to'plami) boshlagandan ko'ra eng yaxshisi oddiy hardware to'plamidan boshlashdir.

* [Arduino Start Kit](https://www.arduino.cc/)
	* Arduinolarning ko'p talqinlari bor. Ammo ulardan eng sodda protessor (ATmega328P) va qo'llanma kitobiga ega bo'lgani "Arduino Start Kit" hisoblanadi
	* ATmega328Pda 8-bit yadroli CPU borligi uni raqamli sxemani (digital circuit) dizayn qilishni va firmware (o'rnatilgan dasturiy ta'minot) rivojlantirishni yaxshi boshlanish nuqtasi qiladi
	* Siz sxemalarni va maketlarni (layouts) chizishni va chiplarni yig'ishni (assemble) bilishingiz shart emas.
	* Lekin sxemalarni qanday oq'ish va chiplar qanday bog'langanligini tushunishingiz albatta zarur.
	* Firmware dasturchilar sxemalarni o'qiy olishi va bundan ma'lumotlarni qanday qilib mo'ljallangan qurilmalarga jo'natishni anglab ola bilishi kerak.
	* Qo'llanma kitobiga ergashing!
* [8086 manual](https://edge.edx.org/c4x/BITSPilani/EEE231/asset/8086_family_Users_Manual_1_.pdf)
	* Agar Siz x86 arxitekturasiga yangi bo'lsangiz, 8086 ham protsessor arxitekturasi va x86 assembly uchun juda yaxshi qo'llanma
* [80386 manual](http://css.csail.mit.edu/6.858/2015/readings/i386.pdf)
	* 80x86 protsessorining `protected mode` (himoyalangan rejim) va `paging mechanism` uchun eng zo'r qo'llanma
	* Veb ko'rinishda: https://pdos.csail.mit.edu/6.828/2011/readings/i386/toc.htm

Bu yerga kelgach, Siz eng so'nggi ARM va x86 protessorini ishlatishni boshlashingiz mumkin.
* https://www.raspberrypi.org/
* https://beagleboard.org/
* https://www.arduino.cc/en/ArduinoCertified/IntelEdison

Misol uchun, Raspberry Pi platasi 64-bit buyruqlar to'plamini (instruction set) qo'llab-quvvatlovchi Cortex-A53 Protsessoriga ega.
Bu Sizga rPi orqali zamonaviy protsessorning arxitekturasi bilan tanishishingiz imkonini beradi.
Ha, Siz uni sotib ololasiz.... ammo.... u bilan nima qilmoqchisiz?
Agar Sizning biror ko'zlagan loyihangiz bo'lmasa, katta ehtimol bilan Siz platani javonga solasizda va uni boshqa avvallari sotib olgan qurilmalaringiz kabi unutib yuborasiz.

Shuning uchun men Sizga bir loyihani tavsiya qilaman.
* [Making your own kernel](http://wiki.osdev.org/Getting_Started)
	* Qo'shimcha yaxshi manbalar: https://www.reddit.com/r/osdev/
* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)
	* (loyiha haqida) Bu repozitoriya noldan sodda operatsion tizim yaratish bo'yicha qadamma-qadam o'rgatadigan qo'llanmani o'z ichiga oladi...(qism olib tashlandi)...Har bir dars shunday tuzilganki, birinchi navbatda kernelning ma'lum bir funksiyasi RPi OS'da qanday implementatsiya qilinganini tushuntiradi va so'ngra xuddi o'sha funksiya Linux kernelida qanday ishlashini ko'rsatishga harakat qiladi.

Men o'zimning 64-bit long rejimi (64-bit long mode), peyjing (paging) va sodda kontekst almashinuvini (context switching) qo'llab quvvatlovchi [kernelchamni](https://github.com/gurugio/caos) yasab ko'rganman. O'z kernelchangizni yasab ko'rish zamonaviy kompyuter arxitekturasini va hardware boshqaruvini tushunishni yaxshi yo'li hisoblanadi.

Darhaqiqat, Sizda eng so'nggi protsessor va eng so'nggi hardware qurilmalari bor. Sizning laptopingiz! Sizni desktopingiz! Sizga boshlash uchun hamma narsa muhayyo!
Siz biror narsa sotib olishingiz shartmas.
Qemu emulatori eng so'nggi ARM va Intel protessorlarini emulyatsiya qila oladi.
Demak, Sizga kerak bo'lgan barcha narsa qo'lingizda tayyor turibdi.
Siz foydalanishingiz uchun hozirda ko'plab kernelchalar va dokumentlar bor.
Shunchaki qemu emulatorini o'rnating va o'zingizning ishga tushadigan (boots), peyjingni yoqadigan (turns on paging) va bir qancha habarlarni chop etadigan kichik kernelingizni yasang.

Boshqa kernelchalar:
* https://littleosbook.github.io/
* https://tuhdo.github.io/os01/

### Linux kerneli va qurilma drayverlari

Siz butun boshli operatsion tizim qurishingiz shart emas.
Linux hamjamiyatiga qo'shiling va rivojlantirishda ishtirok eting.

Boshlang'ichdan yuqori darajagacha (advanced) bo'lgan Linux kerneli va qurilma drayverlarini rivojlantirish bo'yicha resurslar.
* Kitoblar: Ularni ushbu tartibda o'qing
	* [The Design of the Unix Operating System](https://www.amazon.com/Design-UNIX-Operating-System/dp/0132017997)
		* Unix'ning asosiy tushunchalari barcha operatsion tizimlarga taalluqlidir.
		* Bu kitob operatsion tizimlarning eng asosiy tushunchalarni o'rganish uchun judayam yaxshi joy.
	* [Linux Device Drivers](https://www.amazon.com/Linux-Device-Drivers-Jonathan-Corbet/dp/0596005903/ref=sr_1_4?ie=UTF8&qid=1483650712&sr=8-4&keywords=understanding+linux+kernel)
		* Barcha na'munalarni o'zingiz qilib ko'ring
	* [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468/ref=sr_1_2?ie=UTF8&qid=1483650712&sr=8-2&keywords=understanding+linux+kernel)
		* Linux kerneli dizaynini tushuning
	* [Understanding the Linux Kernel](https://www.amazon.com/Understanding-Linux-Kernel-Third-Daniel/dp/0596005652/ref=sr_1_1?ie=UTF8&qid=1483650712&sr=8-1&keywords=understanding+linux+kernel)
		* Ushbu kitobni o'qish bilan bir vaqtda Linux kernelinig v2.6'sining manba kodini birga o'qing
		* Hech qachon eng so'nggi talqin bilan boshlamang, v2.6 yetadi!
		* Qemu va gdb'ni ishlatgan holda kernel kodini satrma-satr yurgizing
			* http://stackoverflow.com/questions/11408041/how-to-debug-the-linux-kernel-with-gdb-and-qemu
			* https://github.com/gurugio/linuxdeveloptip/blob/master/qemu-gdb-kdump.md
		* busybox'ni ishga tushishda (boot) faqatgina bir soniya oladigan eng sodda fayl tizimini (filesystem) yasash uchun ishlating 
			* https://github.com/gurugio/linuxdeveloptip/blob/master/minikernelwithbusybox.md
* Boshqa resurslar: Men tavsiya qiladigan bepul manbalar
	* [Linux device driver labs](https://linux-kernel-labs.github.io/)
		* Asosiy kernel API'lari bilan Linux qurilma drayverlarini yasayotgan amaliy qo'llanma va ajoyib topshiriqlar
		* Mening fikrimcha bu dokument kernel API'larining barcha eng muhim qismlarini tanishtiradi
	* [The Eudyptula Challenge](http://eudyptula-challenge.org/)
		* _Afsuski, bu chellenj yangi ishtirokchilarni qabul qilolmaydi, sababi bu yerda boshqa chellenj yo'q._ Uning boshqaruvchisi aytdiki, u yangi format bilan chiqarishni rejalashtirmoqda ekan. Umid qilamanki bu tez orada qaytadi.
			* Lekin Siz chellenjning savollarini Google'dan qidirib topishingiz mumkin. Ba'zi odamlar o'zlarining qilgan ishlarini joylashga ulgurib bo'ldi. Savollarni toping va ularni mustaqil yechishga urining. Keyin esa o'zingizning yechimingizni boshqalarniki bilan solistiring.
		* Bu xuddi Sizni ishingizda yo'naltirib turadigan ajoyib shaxsiy o'qituvchingizga o'xshaydi.
		* Agar Siz nima qilishni bilmay turgan bo'lsangiz, shunchaki shuni boshlang.
	* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)
		* Bu loyiha hali tugallanmagan.
		* Men ishonamanki, Linux kerneliga o'xsash kernelni yasab ko'rish Linux kernelini tushunishning eng zo'r yo'li.
	* [Block layer and device driver](https://github.com/gurugio/book_linuxkernel_blockdrv)
		* Multi-queue rejimida ishlaydigan sodda blok qurilmasi (block device) drayveri na'munasidan (Ramdisk) boshlang
		* Keyin blok qatlamiga (block layer) o'ting
		* Men ingliz tiliga tarjima qilishni yakunladim. Iltimos, o'zingizning fikr-mulohazangizni menga yuboring.
	* [md driver of Linux kernel(Korean)](https://github.com/gurugio/book_linuxkernel_md)
		* mdadm asbobi (tool) qanday ishlashi va u qanday qilib md drayverini chaqirishi (call) haqida
		* md drayveri qanday ishlashi haqida
	* [Lions' Commentary on UNIX 6th Edition, with Source Code](https://en.wikipedia.org/wiki/Lions%27_Commentary_on_UNIX_6th_Edition,_with_Source_Code)

#### Qo'shimcha adabiyotlar

Bularni Sizga biror narsa kerak bo'lganida tekshirib ko'ring
* [Free-electrons homepage](http://free-electrons.com/docs/)
	* bu yerda yaxshi mavzularni, xususan ARM-linuxni, tanishtiradigan ko'p slayd fayllari bor
* [Julia Evans's posting: You can be a kernel hacker!](http://jvns.ca/blog/2014/09/18/you-can-be-a-kernel-hacker/)
	* kernel dasturlashni boshlash uchun qo'llanma

### Boshqa qo'llanilish sohalari

Ha, Siz Linux yoki firmware'ga qiziqmasligingiz mumkin. Agar shunday bo'lsa, Siz bu bilimlar/ko'nikmalar ishlatiladigan boshqa tatbiqlarni topishingiz mumkin:
- Windows tizim dasturlashi & qurilma drayverlari
- Xavfsizlik
- Reverse injiniring

Menda bu tatbiqlar bo'yicha hech qanday bilim yo'q. Iltimos, menga yangi boshlovchilarga mo'ljallangan har qanday ma'lumotni jo'natsangiz.

**Kernel va drayverlar quyi-daraja dasturlashining hamma qismi emas.** Quyi-daraja dasturlashning yana bir muhim tatbiqi bu dastur tomonidan belgilangan xotira (software-defined storage) yoki taqsimlangan fayl tizimidir (distributed filesystem). Ular haqida detallashtirilgan tavsif bu dokumentning qamrovidan tashqaridan, lekin Siz sodda taqsimlangan fayl tizimini sinab ko'rishingiz mumkin bo'lgan bir kurs bor.
* Kurs (ingliz tilida): https://pdos.csail.mit.edu/archive/6.824-2012/
* Kursga tegishli kodning manbasi: https://github.com/srned/yfs

## Quyi-daraja dasturlashining kelajagi

Men kelajakni bilmayman, lekin e'tiborimni Rust'ga qaratib turaman.
* https://hacks.mozilla.org/2016/11/rust-and-the-future-of-systems-programming/

Agar men to'liq bir hafta bo'sh bo'lganimda, men Rustni o'rgangan bo'lardim.
Buning sababi Rust Linux qurilma drayverlarini yasashim uchun eng so'nggi dastulash tilidir.
* https://github.com/tsgates/rust.ko

IoT yangi trend. Shu tufayli unga qanday OS'lar ishlatilishini ko'rib chiqishga arziydi.
ARM, Samsung va boshqa kompaniyalar o'zining real-vaqtda ishlaydigan OS'iga (real-time OS) ega. Ammo, afsuski, ularning ko'pi yopiq manbali.
Lekin Linux Foundation'ning yechimi bor: Zephyr
* https://www.zephyrproject.org/

Odatiy bulut serverlari (cloud servers) ko'p qatlamlarga (layers) ega. Misol uchun, host (ya'ni asosiy, jarayonlar olib borilayotgan) OS, KVM drayveri, qemu protsessi, guest OS (virtual mashinadagi OS) va xizmat dasturi (service application). Yengil virtualizatsiyaga ega bo'lish uchun konteyner (container) ishlab chiqilgan. Yaqin kelajakda, OSning yangi konsepti (turi), ya'ni bunday aytganda kutubxona OS (library OS) yoki Unikernel, hozirgi odatiy virtualizatsiyaga ishlatiladigan dasturlar (SoftWare) to'plamini o'rnini bosadi.
* https://unikernel.org

[Big Data](https://uz.wikipedia.org/wiki/Katta_hajmli_ma%CA%BClumot) va bulutli hisoblash judayam katta saqlash qurilmasi/tizimini talab qiladi. Serverlarga to'g'ridan-to'g'ri ulangan ba'zi disklar ularga kerak bo'lgan hajm, stabillik va  faoliyat sifati talablarini qoniqtirolmaydi. Shuning uchun bir-biriga katta tezlikdagi tarmoq (high speed network) orqali ulangan ko'plab saqlash mashinalari (storage machines) orqali ulkan saqlash tizimlarini (storage systems) qurish borasida izlanishlar bo'lgan. Avvallari bitta ulkan saqlash tizimiga (volume) e'tibor berilardi. Lekin hozirgi yechim beruvchilar bizga ko'p virtual mashinalarga ba'gishlangan (dedicated) ko'p saqlash hajmlarini (volume) taqdim etmoqda.
* https://en.wikipedia.org/wiki/Software-defined_storage
* https://en.wikipedia.org/wiki/Clustered_file_system
* https://en.wikipedia.org/wiki/Ceph_(software)

## Qanday boshlash kerak?

Men qanday boshlash kerakligi borasida email so'rov oldim. Bu yerda kitoblar, kurslar, hamda loyihalar borasida ko'p ma'lumotlar keltirilgan. Qanday boshlash haqida yozishni unutganim bu mening xatoyim. Afsuski, bu yerda [King's Landing](https://gameofthrones.fandom.com/wiki/King%27s_Landing)'ga olib boradigan ***King's Road*** yo'q. Men shunchaki o'zim nima qilganimni ketma-ketlikda yozaman. Agar Siz undan bir narsani qilib bo'lgan bo'lsangiz, iltimos, shunchaki o'tkazib yuboring. YANA ESLATAMAN, bu Siz qayerdan boshlashni yoki nima qilishni bilmay turganingizda shu tartibda qilib borishingiz mumkin bo'lgan bir na'munaviy yo'l xolos.

- Operatsion Tizim Nazariyasi boo'yicha kitob o'qish: eng kamida "The Design of the UNIX Operating System by Maurice J. Bach"
- Assembly va C'ni o'rganing
	- [8086 assembly programming with emu8086](https://github.com/gurugio/book_assembly_8086)
		- Assembly dasturlash tushunchasini tusunishingiz yetarli. Biror amaliy narsa qilishingiz shart emas.
	- [The C Programming Language 2nd Edition](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=60R1D2CHBA8DHYT6JNMN)
		- Har bir mashqni ishlash uchun QO'LINGIZDAN KELGANINI QILING!
	- [C Programming: A Modern Approach, 2nd Edition](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
- C bilan biror amaliy (practical) narsa qiling
	- [C Project Based Tutorials?](https://www.reddit.com/r/C_Programming/comments/872rlt/c_project_based_tutorials/): O'zingizga qiziq bo'lgan bir yoki ikki loyihalarni tanlang va o'zingizning loyihangizni qiling.
	- [leetcode.com](https://leetcode.com/): agarda Siz biror qiziq loyiha topolmasangiz, unda ma'lumotlar tuzilmalari va algoritmlarga e'tiborni qaratgan (focus) ham yaxshi bo'ladi.
- Birorta Hardware loyiha qiling
	- RaspberryPi yoki Arduino -- farqi yo'q. Sizga hardware'ni faqatgina C bilan to'g'ridan to'g'ri boshqarish tajribasi kerak. FAQAT C BILAN!
	- Mening tavsiyam shuki, ATmega128 to'plamini sotib oling va LEDlarni yoqib/o'chirishga, svitch kiritishini (switch input) aniqlashga va LCD displeyiga habar chiqarishga **firmware** yasang. Motorni boshqaradigan dastur ham juda yaxshi loyiha: masalan, chiziq bo'ylab harakatlnauvchi (the line tracer).
	- Birorta ham kutubxona ISHLATMANG. Dasturni hardware'ga yuklovchidan boshqa hamma narsani o'zingiz qilishingiz kerak.
- Linux kerneli asoslari
	- Quyi-daraja dasturlashi operatsion tizimga judayam yaqin. Siz OS ichida nima bo'lishini bilishingiz kerak.
	- Drayverlar bilan boshlang
		- [Linux Device Drivers](https://www.amazon.com/Linux-Device-Drivers-Jonathan-Corbet/dp/0596005903/ref=sr_1_4?ie=UTF8&qid=1483650712&sr=8-4&keywords=understanding+linux+kernel) kitobini o'qing.
		- [Linux device driver labs](https://linux-kernel-labs.github.io/)
		- [The Eudyptula Challenge](http://eudyptula-challenge.org/)
	- Linux kerneli ichki qismini o'rganish uchun [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468/ref=sr_1_2?ie=UTF8&qid=1483650712&sr=8-2&keywords=understanding+linux+kernel) kitobini o'qing.
- Professional sohaga kiring
	- Agar professional Linux Kernel Dasturchisi bo'lishni istasangiz
		- [Understanding the Linux Kernel](https://www.amazon.com/Understanding-Linux-Kernel-Third-Daniel/dp/0596005652/ref=sr_1_1?ie=UTF8&qid=1483650712&sr=8-1&keywords=understanding+linux+kernel) kitobini albatta o'qishingiz shart
			- So'ng kernelcha yasashga urinib ko'ring
			-  [Learn operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)
			- [Making your own kernel](http://wiki.osdev.org/Getting_Started)
			- Kernelingizning github linkini rezyumeyingizga qo'shib qo'ying (Commit habarlarida batafsil tavsif yozishni unutmang)
		- https://lwn.net/ da eng so'nggi muammolarni tekshiring va unga qo'shiling
			- "https://lwn.net/Kernel/" da yoki to'g'ridan-to'g'ri https://lwn.net/Kernel/Patches da "Recent kernel patches" bo'limini tekshiring
			- O'zingizga qiziq bo'lgan "patch"ni tanlang. Uning manba kodini tushunishga harakat qiling. Albatta, bu judayam qiyin bo'ladi, lekin urinib ko'ring. Uringaningiz sari yaqinlashib boraverasiz.
			- Kernelni "build" qiling (ishlatishga tayyor holatga keltiring) va o'zingizning tizimingizda test qilib ko'ring. Misol uchun, LTP'da (https://linux-test-project.github.io/) faoliyat sifati (performance) va stabillik testlarini yurgizib ko'rishingiz mumkin. Hamda kernelning o'zida ham ko'plab test instrumentlari (tools) bor (https://www.kernel.org/doc/html/latest/dev-tools/index.html).
			- Har qanaqa muammo chiqsa habar bering: kompilyatsiya ogohlantirishlari(compile warnings)/xatolari(errors); faoliyat sifatida pastlash; kernel panic/oops yoki har qanday muammolar
			- Agar u yaxshi ishlasa, tizimingizni harakateristikasi bilan qo'shib hisobot/habar bering. Patch'ning egasi Sizning ismingiz bilan "Reviewed-by", ya'ni ko'rib chiqildi, belgilashini (tag) yozishi mumkin.
			- O'zingizning ismingizni kernelning `git log`'idan toping
	- Yoki boshqa mavzularni toping
		- Quyi-daraja muhandisi ishlashi mumkin bo'lgan ko'plab sohalar bor: xavfsizlik, Kompaylerlar (compilers), Firmware, robot/mashina va h.k.

# Tarjimalar
Iltimos, agar Siz bu sahifani tarjima qilishni istasangiz, menga `pull request` yuboring. Men uni bu ro'yxatga qo'shib qo'yaman.

* [Xitoy (An'anaviy)](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_tw.md)
* [Xitoy (Soddalashtirilgan)](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_cn.md)
* [Braziliya Portugal](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_pt.md)
* [Italyan](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_it.md)
* [Chex](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_cz.md)
* [Rus](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_ru.md)
* [Turk](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_tr.md)
* [Fors](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_fa.md)
* [Ispan](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_es.md)
* [Fransuz](https://github.com/gurugio/lowlevelprogramming-university/blob/master/README_fr.md)

# Men kimman?

Men [Google Intervyu Universiteti](https://github.com/jwasham/coding-interview-university)dan ilhomlanganman. Bu mahorat/bilimlar avvalgiga nisbatan hozir kamyob bo'lganligi uchun, men o'zimning tajribamni ulashmoqchiman hamda quyi-daraja dasturchisi bo'lishdagi yo'lni ko'rsatmoqchiman. Shuningdek, ko'p talaba va yangi boshlovchilar mendan qanday qilib quyi-daraja dasturchilari va Linux kerneli muhandislari bo'lish haqida ko'p so'rashadi.

Ma'lumot uchun, men 10 yildan oshiq tajribaga ega quyi-daraja dasturchisiman:
* 80x86 Assembly dasturlash
* ATmel chiplari bilan hardware qurilmalari va firmware
* Unix uchun C tilida tizim dasturlash
* Linuxda qurilma drayveri
* Linux kernel: sahifa ajratish (page allocation)
* Linux kernel: blok qurilmasi drayveri (block device driver) va `md` moduli