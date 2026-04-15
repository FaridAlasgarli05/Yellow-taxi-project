# Yellow-taxi-project
Yellow Taxi datası ilə həftəlik gedişlərin və sürücülərin analizi

Sürücülərin gedişlərinə əsasən kateqoriyalara bölünməsi, kateqoriyalarına əsasən bonus sisteminin tətbiqi və növbəti həftəlik planın təyin edilməsi. Müştərilərin taksi xidmətindən istifadə sıxlığına əsasən fərdi kampaniyların tətbiqi.
 
Sizə 13-19 fevral 2023-cü il tarixlər (gecə saatları) üzrə olan gedişlərdən ibarət data verilib.
Qeyd: trip distance sütununda 0 olan sifarişlər ləğv edilmiş sifarişlərdir. 
 
1.	“Aktiv qalma müddəti” adlı səhifə yaradaraq: 

Sürücülərin tarixlər üzrə (gündəlik) aktiv qalma müddətlərini və orta günlük aktiv qalma müddətini hesablayın (saat olaraq) 

2.	“Reyting-Bonus-Plan” adlı səhifə yaradaraq: 

Sürücülər üzrə ümumi gediş sayını, ümumi müştəri sayını və ümumi gəliri hesablayın. 
Sürücüləri aşağıdakı şərt daxilində 3 kateqoriyaya bölün: Green kateqoriyası: Ya orta günlük aktiv qalma müddəti 5-dən çox, gediş sayı 100-dən və ya ümumi müştəri sayı 120-dən çox olmalıdır; ya da sürücülərin ümumi gəliri 1500-dən çox olmalıdır. Yellow kateqoriyası: Ya orta günlük aktiv qalma müddəti 4-dən çox, gediş sayı 80-dən və ya ümumi müştəri sayı 100-dən çox olmalıdır; ya da sürücülərin ümumi gəliri 1000-dən çox olmalıdır. Bu kriteriyalara uyğun gəlməyən sürücülərin Red kateqoriyasına aid edilməlidir. 
Kateqoriyalara əsasən sürücülərə bonus hesablayın: Green kateqoriyasına ümumi gəlirin 10%-i, Yellow kateqoriyasına ümumi gəlirin 5%-i. Red kateqoriyasına bonus nəzərdə tutulmur 
Kateqoriyalara əsasən növbəti həftəlik planı (gediş sayı) müəyyən edin: Green kateqoriyasına aid edilən sürücülər növbəti həftə faktiki gediş sayını təkrarlamalı, Yellow kateqoriyasına aid edilən sürücülər növbəti həftə faktiki gediş sayını 10% artırmalı, Red kateqoriyasına aid edilən sürücülər isə növbəti həftə faktiki gediş sayını 30 % artırmalıdır.
 
3.	“Kampaniya” adlı səhifə yaradaraq: 

Müştərilər üzrə günlük orta gediş sayı və günlük orta gediş məsafəsini müəyyən edərək aşağıdakı şərt daxilində (ardıcıllıqla) növbəti həftə üçün kampaniyalar tətbiq edilməlidir: günlük orta gediş sayı 1-dən kiçik olanlara - gündəlik bir gedişə 30% endirim, günlük orta gediş sayı 1.5-dən böyük olanlara - 10 mildən çox sifarişə 20 faiz endirim, yerdə qalanlar üçün günlük orta gediş məsafəsi 7-dən az olanlara - 10 mildən çox sifarişə 30 faiz endirim, günlük orta gediş məsafəsi  7-dən çox olanlara - tətbiq edilmir.

4.	“Outliers” adlı səhifə yaradaraq: 

Gediş məsafələrini (trip distance) {<1; 1-3; 3-5; 5-7; 7-9; 9-11; >11} şəkildə qruplaşdıraraq hər sürücünün yerinə yetirdiyi sifariş sayını tapın. Yaradılmış qruplar üzrə outliers-ləri tapın. Sürücünün hər hansısa qrup üzrə gediş sayı outliers olarsa həmin sürücünün məlumatları olan sətrə şərti format tətbiq edilməlidir.


