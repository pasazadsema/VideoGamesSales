# Data Cleaning Steps
- Dataset pandas ilə yükləndim
- ORDERDATE sütunu analiz üçün datetime formatına çevirdim (vaxt əsaslı analiz aparmaq üçün)
- ADDRESSLINE2, STATE və POSTALCODE sütunlarındakı çatışmayan dəyərlər "Unknown" ilə doldurdum(məlumat itkisini minimuma endirmək üçün)
- Missing values və dublikatlar yoxladlm
# Summary Statistics
SALES min: 482 ən aşağı sifariş dəyəri
SALES max: 14082 yüksək dəyərli
SALES ortalama: 3553
SALES median: 3184 median ortalamadan aşağıdır,buda göstərir ki satışların çoxu orta səviyyədədir amma bəzi çox yüksək sifarişlər ortalamanı yuxarı çəkir
# Business Insights
Ən çox sifariş 2004-cü ildə edilib
- Bu, həmin dövrdə satışların artmasına səbəb olan kampaniya, bazar genişlənməsi və ya yüksək tələbat olduğunu göstərə bilər və şirkət bu strategiyanı yenidən tətbiq edə bilər
Sifarişlərin böyük hissəsi "Shipped" statusundadır
- müştəri məmnuniyyətinin yüksək ola biləcəyinə işarədir
Bəzi ölkələr digərlərinə nisbətən daha çox sifariş verir
- Bu ölkələr əsas bazarlar hesab olunur və marketinq strategiyası bu regionlara daha çox fokuslana bilər, digər ölkələrdə isə böyümə potensialı araşdırıla bilər
Satış dəyərləri geniş aralıqda dəyişir
- Bu fərqli qiymət seqmentlərinə aid məhsulların mövcud olduğunu göstərir və şirkətin həm kütləvi, həm də premium müştərilərə xidmət etdiyini göstərir