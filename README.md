# Introduce

<table><thead><tr><th>No</th><th>Aşamalar</th><th>Açıklama</th></tr></thead><tbody><tr><td>1</td><td>Exploratory Data Analysis</td><td>Bu aşamada, veri seti analiz edilerek, veri seti hakkında önemli bilgiler elde edilmiştir. Bu bilgiler ışığında belirli iç görüler doğrultusunda veri ön işleme adımında gerekli reaksiyonlar alınmıştır. Ayrıca, veri setinde bulunan özellikler (features) kullanılarak Google Data Studio aracılığıyla bir dashboard raporu hazırlanmıştır.</td></tr><tr><td>2</td><td>mintlemon-turkish-nlp</td><td>mintlemon-turkish-nlp kütüphanesi, henüz geliştirme aşamasında olan bir kütüphanedir. Bu kütüphane, yarışma kapsamında veri ön işleme adımlarının gerçekleştirilmesi için kullanılmıştır. Veri ön işleme aşamasında Normalizer modülü, mintlemon-turkish-nlp kütüphanesine eklenmiştir. Normalizer modülü, Türkçe metinlerdeki yazım hatalarını düzeltmek ve metinleri belirli bir formata getirmek için kullanılmıştır. Böylece, veri seti daha homojen ve işlenebilir bir hale getirilmiştir. Yarışmanın ardından da kütüphaneye katkı sağlamaya devam edeceğiz ve open-source olarak herkesin kullanımına açık bir kaynak haline getireceğiz. Bu sayede, geliştirmiş olduğumuz kütüphane, insanlar tarafından kullanılarak Türkçe doğal dil işleme alanında daha fazla gelişme kaydedebilecek. Amacımız, Türkçe doğal dil işleme alanına değerli bir kazanım sağlamak ve bu alanda çalışan herkesin işini kolaylaştırmak.</td></tr><tr><td>3</td><td>Preprocessing Micro Service</td><td>Preprocessing Micro Service, parametrik hale getirilen bir Flask API servisi olarak geliştirilmiştir ve Mintlemon Turkish NLP kütüphanesi kullanılarak Türkçe metinlerin çeşitli veri ön işleme adımlarından geçirilmesini sağlar. Bu araç, sayısal metinlerin normalleştirilmesi, noktalama işaretlerinin kaldırılması, Türkçe karakterlerin normalleştirilmesi, karakterlerin küçük harfe çevrilmesi ve kısa metinlerin kaldırılması gibi çeşitli veri ön işleme adımlarını içerir. Ayrıca, veri ön işleme adımları, kullanıcıların tercihlerine göre özelleştirilebilir ve Türkçe metinlerin özelliklerine uygun bir şekilde işlenmesi sağlanır. Bu sayede, Flask API servisi olarak geliştirilen Preprocessing Micro Service, Türkçe doğal dil işleme alanında verimli bir veri ön işleme aracı sunarak, Türkçe metinlerin daha etkili bir şekilde işlenebilmesine katkı sağlamayı hedefler.</td></tr><tr><td>4</td><td>Preprocessing Micro Service Params Tuning</td><td>-</td></tr><tr><td>5</td><td>multi class model </td><td>-</td></tr><tr><td>6</td><td>Shap analizi</td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td></tr><tr><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ekstra veri eklemenin katkıntısı</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td></tr><tr><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multilabel Model</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td></tr><tr><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">9</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">model hizmet</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td></tr><tr><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Uygulama</font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td></tr></tbody></table>

