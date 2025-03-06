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

Men [Google Intervyu Universitetigoogle-interview-university](https://github.com/jwasham/coding-interview-university)dan ilhomlanganman. Bu mahorat/bilimlar avvalgiga nisbatan hozir kamyob bo'lganligi uchun, men o'zimning tajribamni ulashmoqchiman hamda quyi-daraja dasturchisi bo'lishdagi yo'lni ko'rsatmoqchiman. Shuningdek, ko'p student va yangi boshlovchilar mendan qanday qilib quyi-daraja dasturchisi va Linux kerneli muhandislari bo'lish haqi ko'plab so'rashadi.

Bu sahifa hamma havola/kitob/kurslarni o'z ichiga ololmaydi. Misol uchun, ushbu sahifada Arduino tanishtirilgan bo'lsada, bu yerda u va embedded tizimlar haqida chuqur ma'lumot yo'q.  Siz o'zingiz mustaqil chuqurroq o'rganishingiz kerak. Sizda boshlash uchun "Arduino" kalit so'zi bor. Demak, Sizning keyingi qadamlaringiz havolalar va bepul kitoblarni yig'ib yurish emas, balki "Arduino" deb Google'dan qidirishingiz, [Arduino] to'plam sotib olishingiz, va o'zingiz uchun nimadur qilishingiz bo'lishi mumkin. Iltimos, bu sahifa yangi boshlovchilar uchun yo'riqnoma hisoblanadi.

Quyi-daraja dasturlashi Kompyuter Fanining (Computer Science) bir qismidir.
Umuman olganda, birinchi o'rinda Kompyuter Fani (Computer Science) bo'yicha bilim olinganida afzalroq bo'lar edi.
* [Kompyuter Fanini mustaqil va bepul o'rganish uchun yo'riqnoma](ttps://github.com/ossu/computer-science)


## Quyi-daraja (low-level) nima?

Men quyi-daraja dasturlashini C va assembly kabi quyi-daraja dasturlash tillari ishlatiladigan va mashinaga (kompyuter) yaqin bo'lgan dasturlash deb tasniflayman. Bu yuqori-darajadagi, odatda foydalanuvchi maydoni dasturlarida (user-space applications) namoyon bo'ladigan va yuqori-darajali dasturlash tillari (Python, Java kabilar) ishlatilinadigan dasturlashga qarama qarshidir.
* [Wikipedia: Quyi-daraja dasturlash tili (ingliz tilida)](https://en.wikipedia.org/wiki/Low-level_programming_language)

Ha, tizim dasturlashi (systems programming) quyi-daraja dasturlashiga yaqin tushuncha. Bu sahifa tizim dasturlashida bo'lmagan hardware dizayni va firmware'ni qurishni o'z ichiga oladi.
- [Wikipedia: System programming](https://en.wikipedia.org/wiki/System_programming)

Nihoyat, bu sahifa hardware qismlaridan tortib Linux kerneligacha bo'lga mavzularni o'z ichiga oladi. Bu turli xil qatlamlarning (layers) ulkan  ????? (range'ga nima tarjima?). Bir sahifalik dokument hech qachon barcha qatlarmlarning detallarini qamrab ololmaydi. Shuning uchun buning asosiy maqsadi quy-daraja dasturlashi uchun boshlang'ich nuqta bo'lib xizmat qilishdir.

## Nazariya

Quyi-daraja dasturlashiga asosiy tayanch nazariyalar ushbular hisoblanadi:
* Kompyuter Arxitetkturasi
* Operatsion Tizimlar

Menimcha nazariyani o'rganishning eng zo'r yo'li bu kursdir. Kitoblarni o'qish ham yomon yo'l emas-u, lekin juda ko'p vaqt va mehnat talab qiladi. Siz ko'plab yaxshi kurslar (classes) va onlayn universitelarni topa olasiz. Misol uchun, Coursera.org va edx.org.
Nazary bu nazariya. Siz kursda A+ olishingiz kerak deb o'ylamayman. Shunchaki asosiy g'oyani tushuning.
Siz bilimingiz/mahoratingizni tajriba orqali yaxshilab borasiz.

Endi Sizga o'zim o'qigan bir necha kitoblarni tanishtirsam. Bu kitoblar odatda universitetlarda darsliklar sifatida ishlatiladi. Agar Sizning universitetingizda bu kitoblar ishlatilgan kurslar bo'lmasa, bir qancha vaqtingizni ularni o'qishga sarflasangiz arziydi.
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
		* Bu  kitob qanday qilib yaxshi dasturchi bo'lish haqida. Sizga nafaqat nazariya, balki faqat texnika (technique) kerak. Sababi, dasturlash bir narsa qurishdir. ??? (yaxshi chqimadi)
		* Agar Siz List/Scheme tillarini o'rgansangiz, boshqa tillarni tezda o'rgana olishingiz mumkin
		* [Men bu kitobdagi mashqlarni 80% atrofida yechib chiqdim. Ularni ishlash arzirli deb o'ylayman (???? bu yerdayam tarjima yemadi)](https://github.com/gurugio/sicp_exercise)
	
