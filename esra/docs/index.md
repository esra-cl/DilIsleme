# Doğal dili İşleme Nedir ? 

Doğal Dil İşleme (NLP), insan dilinin yapısını analiz ederek anlamak veya yeniden oluşturmak için kullanılan bir alandır. Bu alandaki çalışmaların getirdiği faydalar arasında yazılı metinlerin otomatik çevirisi, soru-cevap sistemleri, otomatik konuşma anlama ve üretme, konuşma sentezi, otomatik metin özetleme ve bilgi sağlama gibi birçok uygulama bulunmaktadır. Bilgisayar teknolojisinin yaygınlaşmasıyla, bu alanın uzmanlık gerektiren yazılımları günlük hayatımızın birçok alanına entegre olmuştur. Örneğin, neredeyse tüm kelime işlem programları dilbilgisini kontrol eden doğal dil işleme yazılımlarını içerir ve bu sayede yazılan metinlerin dil kurallarına uygunluğunu denetler.

## Doğal Dil İşlemenin Temel Prensipleri

### 1.	Temel Kavramlar

I.	Metin İşleme,Tokenization (Belirteçleme),
II.	Morphological Analysis (Morfolojik Analiz)
III.	Sentiment Analysis (Duygu Analizi),Part-of-Speech (POS) 
IV.	Tagging (Sözcük Türü Etiketleme),Part-of-Speech (POS) 
V.	Tagging (Sözcük Türü Etiketleme)


### 2.	İşlemleri

I.	Metin Temizleme (Text Cleaning),
II.	Metin Normalleştirme (Text Normalization)
III.	Feature Extraction (Öznitelik Çıkarımı)
IV.	Feature Extraction (Öznitelik Çıkarımı)
V.	Feature Extraction (Öznitelik Çıkarımı)
VI.	Modelleme ve Öğrenme

### 3.	Modelleme ve Öğrenme

I.	Naive Bayes Sınıflandırıcısı
II.	Word2Vec
III.	Transformer Modelleri



# Zorluklar ve Etik Sorunlar

## NLP uygulamalarının karşılaştığı teknik zorluklar:

###	Dil Karmaşıklığı Ve Semantik Belirsizliği: 

İnsan dili, genellikle birden fazla anlama gelebilecek belirsiz ifadeler içerebilir çünkü dil çok çeşitli anlamları ifade edebilen zengin ve karmaşık bir yapıya sahiptir ve bu belirsizlik ve karmaşıklık NLP uygulamalarının hatasız bir şekilde çalışması için büyük bir zorluk oluşturup ve istenen sonucu üretmesini zorlaştırabilir.

### Veri Seti Bulması: 

Veri setleri bulunmasında zorluklar yaşanıyor ve herhangi bir makine öğrenme aşamalarında insanın dilini, doğru bir şekilde anlaşılması ve yorumlanması için çok büyük miktarda veriye ihtiyaç duyar.

###	Yanlılık:

Eğitildikleri verilerdeki önyargıları yansıtabilir. Bu önyargılar, NLP uygulamalarının adil ve kapsayıcı olmasını engelleyebilir tam tersi bazen tek taraflı yargıları oluşabilir.
Örnek olarak insanların cinsiyetlerini belirlemek için eğitilen bir NPl modeli düşenelim, toplumun genel eğilimlerine göre tek cinsiyetin belirli mesleklerle bağlandırılmasına dayalı olarak taraflı bir şekilde hazırlanmıştır, model kendisine "doktor" kelimesi verildiğinde, toplumda daha yaygın olarak erkeklere atfedilen bir meslek olduğunu öğrenebilir ve "doktor" kelimesini gördüğünde erkek cinsiyetini otomatik olarak tahmin edebilir. Bu durum, modelin kadınları bu mesleklerle ilişkilendirmekte daha az başarılı olmasına neden olabilir.

### Çekimli Atıf:

Bir cümlede geçen bir ismin, zamirinin veya sıfatların, cümlenin yapısına göre farklı şekillerde çekilmesidir. 
Örneğin, "Bu kitap benim" cümlesinde "bu" kelimesi, "kitap" isminin öznesi olarak kullanıldığı için "bu" şeklinde çekilmiştir. Ancak, "Bu kitabı ben yazdım" cümlesinde "bu" kelimesi, "kitap" isminin dolaylı tümleci olarak kullanıldığı için "bu" şeklinde çekilmiştir. 
NLP uygulamalarında, bir cümledeki isimlerin, zamirleri ve sıfatların doğru bir şekilde çekilmesini gerektirmektir. Fakat çekimli Atıf, NLP uygulamalarının hata yapmasına ve zorluk oluşturmasına neden olmaktadır.

* Bu zorlukları çözmek için çeşitli yaklaşımlar geliştirilmiştir; bunlardan bazıları aşağıda bahsedilmektir:

#### Derin öğrenme

Derin öğrenme modelleri, dilin karmaşıklığını daha iyi anlamasına, dilinin nüanslarını kavraması, çekimli atıf kurallarını öğrenebilmesi ve daha doğru sonuçlar üretmesi amaçla çok büyük miktarda veri kullanılarak eğitilir. Semantik belirsizliği sorunları gidermek ise semantik analizi yapılarak belirsiz ifadelerini anlamak mümkün olmaktadır. Özellikle Gramer, sözlükler gibi dil bilimin teorilerinden yararlanan semantik analizi, çok önemli bir rol oynuyor.

#### Önyargıyı Azaltma

Yanlılık azaltma “veri etiketleme”, “veri setlerini dengeleme” gibi bazı teknikleri, eğitilirken kullanılan verilerin önyargılarını azaltmaya veya NLP modellerinin önyargılarını azaltmayı amaçlamaktadır.

#### Dilbilgisi analiz

Bir cümlenin dilbilgisi yapısını analiz edilmek için dilbilgisi analiz teknikleri yapıldı böylece bu dilbilgisi yapısını analiz ederek, çekimli atıf kurallarını belirlemektedir.
NLP araştırmaları, bu zorlukları ele almak için sürekli yeni yaklaşımlar geliştirmektedir. 
Gördüğümüz gibi; derin öğrenme, doğal dil işleme alanında önemli ilerlemeler gerçekleştirdi.


#### * Veri gizliliği ve etik konuları.
NLP uygulamaları, büyük miktarda veriye ihtiyaç duymaktadır. Veriler, kişisel, hassas bilgiler ve gizli bilgiler gibi çeşitli türleri içerebilir. Bu nedenle, NLP uygulamalarını geliştirirken ve kullanırken sırasında veri gizliliği ve etik konularına dikkat edilmesi büyük önem taşımaktadır.

Veri gizliliği, bireylerin verilerinin nasıl toplanıldı, saklanıldı ve kullanıldı önem verilir. Kişisel gizliliği koruması için yapılan uygulamaları etik bir zeminde olmalıdır.

* 	NLP uygulamalarının geliştirilmesi ve kullanımı sırasında bireylerin kişisel verileri korunmalı ve gizlilikleri sağlanmalıdır. Bu amaçla, NLP uygulamalarının veri toplanırken bireylerin kişisel verileri izinleri olmadan toplanmamalı, paylaşılmamalı veya kullanılmamalıdır, ek olarak veri toplama, işleme ve kullanma yöntemleri şeffaf ve açık olmalıdır. Etik konular, ahlaki değerlere uyumu içerir. 

* 	NLP uygulamalarının geliştirilmesi ve kullanımı sırasında etik değerlere uygun davranılması gerekmektedir. NLP uygulamaları adil, kapsayıcı ve ayrımcılık yapmayan şekilde olmalıdır ve kesenlikle NLP uygulamaları insan haklarını ihlal etmemelidir.

Bu değerlerin ve prensiplerin NLP'nin her aşamasında benimsenmesi, teknolojinin daha güvenilir, etik ve kullanıcı dostu olmasını sağlayabilir.

### KAYNAKÇA:

 *	"Speech and Language Processing" - Daniel Jurafsky ve James H. Martin.
https://scholar.google.com.tr/scholar?q=Speech+and+Language+Processing%22+-+Daniel+Jurafsky+ve+James+H.+Martin.&hl=tr&as_sdt=0&as_vis=1&oi=scholart

 *	BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" - Devlin et al. (2018).
https://arxiv.org/abs/1810.04805

 *	Ders Notları.
https://medium.com/sciforce/biggest-open-problems-in-natural-language-processing-7eb101ccfc9
