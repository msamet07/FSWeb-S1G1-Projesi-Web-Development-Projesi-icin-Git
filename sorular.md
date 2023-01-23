## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.  İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında Linus Torvalds tarafından tasarlanıp geliştirilmiş, 2019 yılı itibarıyla %70 pazar payına ulaşmıştır. Açık kaynaklı özgür bir yazılım ürünü.
2. Git ile GitHub arasında ne fark var?
Kısacası GitHub, Git adlı bir sürüm kontrol sistemini (VCS) barındıran bulut tabanlı bir hizmettir. Geliştiricilerin, ilerlemelerini ayrıntılı olarak takip ederken ortak projelerde işbirliği yapmasına ve değişiklikler yapmasına olanak tanır.

3. Neden bir branch oluşturuyoruz? 
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

git checkout

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch Uzaktaki değişiklikleri locale almak için kullanılır gücellemez 
git merge çalışmaları kendi localimize indirdikten sonra entegre etmemize yarar 
git pull git fetch ve git merge nin birleştirilip 1 komut ile yapılması için kullanılır.
7. Merge conflict nedir?
2 yada daha fazla kişinin yada 1 kişinin farklı zamanlarda girdiği çalışmaların aynı satırda karşıya yüklediklerinde çakışmalar gibi problemler olabiliyor.bunu da bize sorar ben hangi satırı kullanayım diye bu duruma diyoruz.
8. Merge conflict'i nasıl çözeriz?
değişikliklere tek tek bakarak doğru olanı seçerek ilerlemek gerekiyor.
